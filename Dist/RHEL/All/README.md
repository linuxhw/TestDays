RHEL - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for RHEL.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/RHEL/Desktop/README.md) and [notebooks](/Dist/RHEL/Notebook/README.md).

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

Total: 338

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire XC-330               | Desktop     | [2012033d09](https://linux-hardware.org/?probe=2012033d09) | Aug 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [cd8482ea72](https://linux-hardware.org/?probe=cd8482ea72) | Aug 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [3df0bebc37](https://linux-hardware.org/?probe=3df0bebc37) | Aug 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [fad6d4558f](https://linux-hardware.org/?probe=fad6d4558f) | Jul 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [4776ecdc2a](https://linux-hardware.org/?probe=4776ecdc2a) | Jul 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [71c31086e6](https://linux-hardware.org/?probe=71c31086e6) | Jul 11, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [714c212f51](https://linux-hardware.org/?probe=714c212f51) | Jul 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [ab729dc8a5](https://linux-hardware.org/?probe=ab729dc8a5) | Jul 04, 2022 |
| Gigabyte      | MU72-SU0-00 01000100        | Server      | [1cb6aead26](https://linux-hardware.org/?probe=1cb6aead26) | Jul 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [aaaaef108a](https://linux-hardware.org/?probe=aaaaef108a) | Jul 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [7e2ddf75e5](https://linux-hardware.org/?probe=7e2ddf75e5) | Jun 30, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [aca491bb91](https://linux-hardware.org/?probe=aca491bb91) | Jun 21, 2022 |
| Unknown       | A06                         | Server      | [3bf8edf992](https://linux-hardware.org/?probe=3bf8edf992) | Jun 18, 2022 |
| Supermicro    | X10DRi                      | Server      | [0cf218f7bf](https://linux-hardware.org/?probe=0cf218f7bf) | Jun 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d77ce7a3f7](https://linux-hardware.org/?probe=d77ce7a3f7) | Jun 13, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [8ee33363ef](https://linux-hardware.org/?probe=8ee33363ef) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [372a1d69d7](https://linux-hardware.org/?probe=372a1d69d7) | May 27, 2022 |
| Dell          | 02K9CR A03                  | Desktop     | [5656d7a0d5](https://linux-hardware.org/?probe=5656d7a0d5) | May 27, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [74525891a0](https://linux-hardware.org/?probe=74525891a0) | May 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f08ef13508](https://linux-hardware.org/?probe=f08ef13508) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Notebook    | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [0b0ffcbfee](https://linux-hardware.org/?probe=0b0ffcbfee) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [919abd9078](https://linux-hardware.org/?probe=919abd9078) | May 13, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [15bc7f6757](https://linux-hardware.org/?probe=15bc7f6757) | May 13, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | Notebook    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [a3ddc714b0](https://linux-hardware.org/?probe=a3ddc714b0) | Apr 28, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [604488642b](https://linux-hardware.org/?probe=604488642b) | Apr 25, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | Precision 5550              | Notebook    | [949f4a7658](https://linux-hardware.org/?probe=949f4a7658) | Apr 19, 2022 |
| Lenovo        | 3132 SDK0K17763 WIN 1801... | Desktop     | [a6e43346ba](https://linux-hardware.org/?probe=a6e43346ba) | Apr 16, 2022 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [82939dc69f](https://linux-hardware.org/?probe=82939dc69f) | Apr 05, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7763003308](https://linux-hardware.org/?probe=7763003308) | Mar 31, 2022 |
| Dell          | Precision 7560              | Notebook    | [2abd72978c](https://linux-hardware.org/?probe=2abd72978c) | Mar 29, 2022 |
| Intel         | NUC11DBBi7 M17027-302       | Mini pc     | [e1e4cbbe30](https://linux-hardware.org/?probe=e1e4cbbe30) | Mar 17, 2022 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [0cf67f0201](https://linux-hardware.org/?probe=0cf67f0201) | Mar 06, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [e7843ce1cf](https://linux-hardware.org/?probe=e7843ce1cf) | Mar 05, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [7fd2e4885c](https://linux-hardware.org/?probe=7fd2e4885c) | Mar 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [14ea45c4d7](https://linux-hardware.org/?probe=14ea45c4d7) | Mar 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [eed6e0f012](https://linux-hardware.org/?probe=eed6e0f012) | Mar 01, 2022 |
| Lenovo        | Z40-70 20366                | Notebook    | [5210de65b3](https://linux-hardware.org/?probe=5210de65b3) | Feb 27, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [cab21caab7](https://linux-hardware.org/?probe=cab21caab7) | Feb 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [081fe975ce](https://linux-hardware.org/?probe=081fe975ce) | Feb 07, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [36c52eaf3d](https://linux-hardware.org/?probe=36c52eaf3d) | Feb 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Notebook    | [7b31f4ca0b](https://linux-hardware.org/?probe=7b31f4ca0b) | Feb 05, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [b3ef38d0ef](https://linux-hardware.org/?probe=b3ef38d0ef) | Jan 31, 2022 |
| Dell          | Latitude E5570              | Notebook    | [87ec93dcdc](https://linux-hardware.org/?probe=87ec93dcdc) | Jan 31, 2022 |
| Lenovo        | ThinkPad T490 20N3S5DV0S    | Notebook    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| ASUSTek       | Maximus VII FORMULA         | Desktop     | [07de603a4a](https://linux-hardware.org/?probe=07de603a4a) | Jan 31, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [a60504e123](https://linux-hardware.org/?probe=a60504e123) | Jan 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [335a0c0490](https://linux-hardware.org/?probe=335a0c0490) | Jan 28, 2022 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [24b05b96d7](https://linux-hardware.org/?probe=24b05b96d7) | Jan 19, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [5808f89618](https://linux-hardware.org/?probe=5808f89618) | Jan 07, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [e3b3ac9f8b](https://linux-hardware.org/?probe=e3b3ac9f8b) | Jan 01, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [012f2de3d5](https://linux-hardware.org/?probe=012f2de3d5) | Dec 28, 2021 |
| HP            | ProLiant DL380e Gen8        | Server      | [a28b637049](https://linux-hardware.org/?probe=a28b637049) | Dec 28, 2021 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [2e716df6c6](https://linux-hardware.org/?probe=2e716df6c6) | Dec 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b6b4df52d0](https://linux-hardware.org/?probe=b6b4df52d0) | Dec 25, 2021 |
| Dell          | Precision 3551              | Notebook    | [cbddfb522a](https://linux-hardware.org/?probe=cbddfb522a) | Dec 21, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ba46713703](https://linux-hardware.org/?probe=ba46713703) | Dec 07, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [cda3dbe636](https://linux-hardware.org/?probe=cda3dbe636) | Dec 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a4e5f602c4](https://linux-hardware.org/?probe=a4e5f602c4) | Dec 01, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7cb04612a2](https://linux-hardware.org/?probe=7cb04612a2) | Nov 30, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [90eea91b30](https://linux-hardware.org/?probe=90eea91b30) | Nov 27, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [cfa38b921a](https://linux-hardware.org/?probe=cfa38b921a) | Nov 22, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [6827caed15](https://linux-hardware.org/?probe=6827caed15) | Nov 19, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [ea1413bf9e](https://linux-hardware.org/?probe=ea1413bf9e) | Nov 19, 2021 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | Notebook    | [df288ab5f0](https://linux-hardware.org/?probe=df288ab5f0) | Nov 18, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [7052b7628f](https://linux-hardware.org/?probe=7052b7628f) | Nov 18, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0178a25382](https://linux-hardware.org/?probe=0178a25382) | Nov 18, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [f766090339](https://linux-hardware.org/?probe=f766090339) | Nov 16, 2021 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [ece232f046](https://linux-hardware.org/?probe=ece232f046) | Nov 11, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [318b5aea2b](https://linux-hardware.org/?probe=318b5aea2b) | Nov 08, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | Notebook    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [d3d69e7587](https://linux-hardware.org/?probe=d3d69e7587) | Oct 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [59dfcd3b23](https://linux-hardware.org/?probe=59dfcd3b23) | Oct 22, 2021 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [07a5b3c465](https://linux-hardware.org/?probe=07a5b3c465) | Oct 16, 2021 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [49d20bd238](https://linux-hardware.org/?probe=49d20bd238) | Oct 12, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [66cd9bb2c9](https://linux-hardware.org/?probe=66cd9bb2c9) | Oct 09, 2021 |
| Lenovo        | ThinkPad P50 20ENS1L000     | Notebook    | [f8443770b9](https://linux-hardware.org/?probe=f8443770b9) | Oct 08, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [63b48dfa23](https://linux-hardware.org/?probe=63b48dfa23) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | Notebook    | [042f9bec29](https://linux-hardware.org/?probe=042f9bec29) | Oct 06, 2021 |
| HP            | 212B                        | Desktop     | [322371cc6a](https://linux-hardware.org/?probe=322371cc6a) | Oct 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [2792a3ef1c](https://linux-hardware.org/?probe=2792a3ef1c) | Oct 03, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [539316ac91](https://linux-hardware.org/?probe=539316ac91) | Sep 30, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | Notebook    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [95ae5d0e04](https://linux-hardware.org/?probe=95ae5d0e04) | Sep 29, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [a667466f62](https://linux-hardware.org/?probe=a667466f62) | Sep 17, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [502a6b96a3](https://linux-hardware.org/?probe=502a6b96a3) | Sep 13, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [fc498b8cb0](https://linux-hardware.org/?probe=fc498b8cb0) | Sep 10, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [35fa4b96f4](https://linux-hardware.org/?probe=35fa4b96f4) | Sep 09, 2021 |
| Lenovo        | HR630X                      | Server      | [0627db12df](https://linux-hardware.org/?probe=0627db12df) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [daadb8ccc0](https://linux-hardware.org/?probe=daadb8ccc0) | Sep 06, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [952dd9f6f5](https://linux-hardware.org/?probe=952dd9f6f5) | Sep 01, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [7bf4b860a8](https://linux-hardware.org/?probe=7bf4b860a8) | Aug 26, 2021 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7bcc3d753](https://linux-hardware.org/?probe=f7bcc3d753) | Aug 25, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [01e55d6021](https://linux-hardware.org/?probe=01e55d6021) | Aug 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [586add668c](https://linux-hardware.org/?probe=586add668c) | Aug 03, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [5096c7cbb6](https://linux-hardware.org/?probe=5096c7cbb6) | Aug 03, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [1bb9bd9d46](https://linux-hardware.org/?probe=1bb9bd9d46) | Jul 27, 2021 |
| Supermicro    | X10DRi                      | Server      | [6be87ab445](https://linux-hardware.org/?probe=6be87ab445) | Jul 26, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [cea7891e5a](https://linux-hardware.org/?probe=cea7891e5a) | Jul 26, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [54f44d70c5](https://linux-hardware.org/?probe=54f44d70c5) | Jul 24, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [9f9cc51cda](https://linux-hardware.org/?probe=9f9cc51cda) | Jul 20, 2021 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [a540fa2f59](https://linux-hardware.org/?probe=a540fa2f59) | Jul 19, 2021 |
| Dell          | Latitude E5510              | Notebook    | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e7fbaff11](https://linux-hardware.org/?probe=7e7fbaff11) | Jul 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c4091b8c8c](https://linux-hardware.org/?probe=c4091b8c8c) | Jul 09, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [a03b6b86cc](https://linux-hardware.org/?probe=a03b6b86cc) | Jul 03, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [500c95d16b](https://linux-hardware.org/?probe=500c95d16b) | Jul 03, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [ab6e7450c3](https://linux-hardware.org/?probe=ab6e7450c3) | Jul 01, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude E6430              | Notebook    | [ed72da5de8](https://linux-hardware.org/?probe=ed72da5de8) | Jun 25, 2021 |
| Dell          | Latitude E6430              | Notebook    | [899e8720e1](https://linux-hardware.org/?probe=899e8720e1) | Jun 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1f8b4df82](https://linux-hardware.org/?probe=b1f8b4df82) | Jun 25, 2021 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [eccdf8e8c1](https://linux-hardware.org/?probe=eccdf8e8c1) | Jun 20, 2021 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [a703424a8c](https://linux-hardware.org/?probe=a703424a8c) | Jun 13, 2021 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [380f10f479](https://linux-hardware.org/?probe=380f10f479) | Jun 10, 2021 |
| Dell          | Precision 3541              | Notebook    | [984db774ed](https://linux-hardware.org/?probe=984db774ed) | Jun 08, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [c3162a0346](https://linux-hardware.org/?probe=c3162a0346) | Jun 04, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [1a9225e48c](https://linux-hardware.org/?probe=1a9225e48c) | Jun 04, 2021 |
| ZTSYSTEMS     | A9DRPF TBD                  | Server      | [1b5977b024](https://linux-hardware.org/?probe=1b5977b024) | Jun 03, 2021 |
| HP            | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Dell          | 074H08 A00                  | Server      | [b7ac531bf5](https://linux-hardware.org/?probe=b7ac531bf5) | Jun 02, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| ZTSYSTEMS     | A9DRPF TBD                  | Server      | [57e5191283](https://linux-hardware.org/?probe=57e5191283) | Jun 01, 2021 |
| Dell          | 0CNCJW A08                  | Server      | [f90168c69d](https://linux-hardware.org/?probe=f90168c69d) | Jun 01, 2021 |
| Dell          | Latitude E6530              | Notebook    | [2e9b8200a9](https://linux-hardware.org/?probe=2e9b8200a9) | May 29, 2021 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [2eebd180f8](https://linux-hardware.org/?probe=2eebd180f8) | May 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c51ae8a5ff](https://linux-hardware.org/?probe=c51ae8a5ff) | May 28, 2021 |
| MiTAC         | HS-9215 R0A                 | Server      | [2f38c3fd0e](https://linux-hardware.org/?probe=2f38c3fd0e) | May 27, 2021 |
| HP            | ProLiant DL180 G6           | Server      | [28b04c3004](https://linux-hardware.org/?probe=28b04c3004) | May 26, 2021 |
| Dell          | 0971VF A01                  | Server      | [9d511d1a0b](https://linux-hardware.org/?probe=9d511d1a0b) | May 26, 2021 |
| Lenovo        | HR630X                      | Server      | [fd087082c0](https://linux-hardware.org/?probe=fd087082c0) | May 26, 2021 |
| HP            | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [9b11ff6d26](https://linux-hardware.org/?probe=9b11ff6d26) | May 22, 2021 |
| MSI           | Z77A-G45                    | Desktop     | [bd980d04be](https://linux-hardware.org/?probe=bd980d04be) | May 22, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [4a38b848dd](https://linux-hardware.org/?probe=4a38b848dd) | May 19, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [65666a7bec](https://linux-hardware.org/?probe=65666a7bec) | May 17, 2021 |
| HP            | 8054                        | Desktop     | [cf6b804c19](https://linux-hardware.org/?probe=cf6b804c19) | May 13, 2021 |
| ASRock        | X99E-ITX/ac                 | Desktop     | [9cacd1608e](https://linux-hardware.org/?probe=9cacd1608e) | May 08, 2021 |
| Lenovo        | 7D2XCTO1WW                  | Server      | [2175466ea1](https://linux-hardware.org/?probe=2175466ea1) | Apr 25, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [23f12250e5](https://linux-hardware.org/?probe=23f12250e5) | Apr 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [bf95cd0ce7](https://linux-hardware.org/?probe=bf95cd0ce7) | Apr 20, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [349f951788](https://linux-hardware.org/?probe=349f951788) | Apr 18, 2021 |
| Dell          | Inspiron 3559               | Notebook    | [854655e305](https://linux-hardware.org/?probe=854655e305) | Apr 14, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [46bb05613f](https://linux-hardware.org/?probe=46bb05613f) | Apr 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [ecc3dfa09a](https://linux-hardware.org/?probe=ecc3dfa09a) | Apr 13, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [a40c80d584](https://linux-hardware.org/?probe=a40c80d584) | Apr 11, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [f98af88440](https://linux-hardware.org/?probe=f98af88440) | Apr 06, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [4c3dd6a28b](https://linux-hardware.org/?probe=4c3dd6a28b) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [344f718da0](https://linux-hardware.org/?probe=344f718da0) | Mar 25, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [3dce7dc37d](https://linux-hardware.org/?probe=3dce7dc37d) | Mar 20, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ee5d8875e3](https://linux-hardware.org/?probe=ee5d8875e3) | Mar 11, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | Notebook    | [5bc6b53ecf](https://linux-hardware.org/?probe=5bc6b53ecf) | Mar 03, 2021 |
| Lenovo        | ThinkPad T460 20FMS1VA09    | Notebook    | [55314e09ff](https://linux-hardware.org/?probe=55314e09ff) | Mar 03, 2021 |
| Lenovo        | ThinkPad W530 2441B32       | Notebook    | [fb9b49c1d9](https://linux-hardware.org/?probe=fb9b49c1d9) | Mar 02, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [c6fd48fe3f](https://linux-hardware.org/?probe=c6fd48fe3f) | Feb 28, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [22c97ac8b2](https://linux-hardware.org/?probe=22c97ac8b2) | Feb 27, 2021 |
| Dell          | 0NNNCT A01                  | Desktop     | [3f081f03fe](https://linux-hardware.org/?probe=3f081f03fe) | Feb 22, 2021 |
| Dell          | Precision 5510              | Notebook    | [2d4aed7f6c](https://linux-hardware.org/?probe=2d4aed7f6c) | Feb 22, 2021 |
| Sony          | VPCEB4L1R                   | Notebook    | [1744d5db17](https://linux-hardware.org/?probe=1744d5db17) | Feb 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [071f1be343](https://linux-hardware.org/?probe=071f1be343) | Feb 09, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [29d0e20ba4](https://linux-hardware.org/?probe=29d0e20ba4) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [832d7f19ae](https://linux-hardware.org/?probe=832d7f19ae) | Feb 02, 2021 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [bdff7fe555](https://linux-hardware.org/?probe=bdff7fe555) | Jan 28, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [98ea3e97e6](https://linux-hardware.org/?probe=98ea3e97e6) | Jan 25, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [2da05b98bf](https://linux-hardware.org/?probe=2da05b98bf) | Jan 25, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [3e0d4ac7c7](https://linux-hardware.org/?probe=3e0d4ac7c7) | Jan 19, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1a1bbc078f](https://linux-hardware.org/?probe=1a1bbc078f) | Jan 18, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d0ac809f8a](https://linux-hardware.org/?probe=d0ac809f8a) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [038ccd7256](https://linux-hardware.org/?probe=038ccd7256) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [f0441f0a07](https://linux-hardware.org/?probe=f0441f0a07) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [3c396f0b59](https://linux-hardware.org/?probe=3c396f0b59) | Jan 15, 2021 |
| Dell          | PowerEdge FC630             | Desktop     | [ab4ea06f29](https://linux-hardware.org/?probe=ab4ea06f29) | Jan 15, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [e10979867d](https://linux-hardware.org/?probe=e10979867d) | Jan 13, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d606944d2b](https://linux-hardware.org/?probe=d606944d2b) | Jan 10, 2021 |
| ASRock        | H270 Pro4                   | Desktop     | [3a3b83a6ed](https://linux-hardware.org/?probe=3a3b83a6ed) | Jan 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e24d02bc67](https://linux-hardware.org/?probe=e24d02bc67) | Jan 05, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e1e788633e](https://linux-hardware.org/?probe=e1e788633e) | Dec 22, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [f95e7c46f7](https://linux-hardware.org/?probe=f95e7c46f7) | Dec 14, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [d99f937c68](https://linux-hardware.org/?probe=d99f937c68) | Dec 12, 2020 |
| Dell          | Latitude 5290               | Notebook    | [f69f594914](https://linux-hardware.org/?probe=f69f594914) | Dec 09, 2020 |
| Dell          | Latitude 5290               | Notebook    | [538342789e](https://linux-hardware.org/?probe=538342789e) | Dec 09, 2020 |
| HP            | 1905                        | Desktop     | [6690d08a07](https://linux-hardware.org/?probe=6690d08a07) | Dec 04, 2020 |
| HP            | Pavilion 14                 | Notebook    | [bed5ca82b9](https://linux-hardware.org/?probe=bed5ca82b9) | Dec 03, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [a70d23cd77](https://linux-hardware.org/?probe=a70d23cd77) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [b446c7d5a5](https://linux-hardware.org/?probe=b446c7d5a5) | Dec 02, 2020 |
| Lenovo        | ThinkPad X250 20CLS0H807    | Notebook    | [81c97fb756](https://linux-hardware.org/?probe=81c97fb756) | Dec 02, 2020 |
| Lenovo        | ThinkPad T460 20BUS0QT0A    | Notebook    | [c0487ec734](https://linux-hardware.org/?probe=c0487ec734) | Dec 02, 2020 |
| HP            | ZBook 14u G6                | Notebook    | [84782d875f](https://linux-hardware.org/?probe=84782d875f) | Nov 27, 2020 |
| Dell          | Precision 7510              | Notebook    | [0725f10b71](https://linux-hardware.org/?probe=0725f10b71) | Nov 23, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [8d9240a29c](https://linux-hardware.org/?probe=8d9240a29c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [f563b4b50d](https://linux-hardware.org/?probe=f563b4b50d) | Nov 18, 2020 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [ded8f80f0a](https://linux-hardware.org/?probe=ded8f80f0a) | Nov 18, 2020 |
| Dell          | 082WXT A01                  | Desktop     | [0a2176308f](https://linux-hardware.org/?probe=0a2176308f) | Nov 17, 2020 |
| HP            | 81B4                        | Desktop     | [12ac27dcb5](https://linux-hardware.org/?probe=12ac27dcb5) | Nov 14, 2020 |
| HP            | 81B4                        | Desktop     | [faf7b737fe](https://linux-hardware.org/?probe=faf7b737fe) | Nov 14, 2020 |
| Dell          | Latitude E6420              | Notebook    | [363320d61e](https://linux-hardware.org/?probe=363320d61e) | Nov 11, 2020 |
| Dell          | Latitude E6420              | Notebook    | [8a37aaac86](https://linux-hardware.org/?probe=8a37aaac86) | Nov 11, 2020 |
| MSI           | H310M PRO-VD                | Desktop     | [18c316813f](https://linux-hardware.org/?probe=18c316813f) | Nov 11, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Dell          | Precision 7510              | Notebook    | [432ebce0a4](https://linux-hardware.org/?probe=432ebce0a4) | Nov 03, 2020 |
| HP            | Pavilion 14                 | Notebook    | [d8220245e5](https://linux-hardware.org/?probe=d8220245e5) | Nov 01, 2020 |
| Dell          | Precision 7510              | Notebook    | [a564df5de7](https://linux-hardware.org/?probe=a564df5de7) | Nov 01, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [2dc26a5fbe](https://linux-hardware.org/?probe=2dc26a5fbe) | Oct 29, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [cf0c44ffb8](https://linux-hardware.org/?probe=cf0c44ffb8) | Oct 29, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [1ca04091de](https://linux-hardware.org/?probe=1ca04091de) | Oct 24, 2020 |
| Lenovo        | ThinkPad T520 42404CG       | Notebook    | [2e3d64e7c5](https://linux-hardware.org/?probe=2e3d64e7c5) | Oct 24, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [f2907d324d](https://linux-hardware.org/?probe=f2907d324d) | Oct 21, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4169f50442](https://linux-hardware.org/?probe=4169f50442) | Oct 18, 2020 |
| Dell          | Latitude 5300               | Notebook    | [4bd822b6e3](https://linux-hardware.org/?probe=4bd822b6e3) | Oct 15, 2020 |
| HP            | 1905                        | Desktop     | [0e53545ff8](https://linux-hardware.org/?probe=0e53545ff8) | Oct 14, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [7bf945cd18](https://linux-hardware.org/?probe=7bf945cd18) | Oct 13, 2020 |
| HP            | Pavilion 14                 | Notebook    | [b29b04ed35](https://linux-hardware.org/?probe=b29b04ed35) | Oct 08, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [2bc1a5b44a](https://linux-hardware.org/?probe=2bc1a5b44a) | Oct 01, 2020 |
| HP            | 1905                        | Desktop     | [48fd57f60f](https://linux-hardware.org/?probe=48fd57f60f) | Sep 24, 2020 |
| HP            | 1905                        | Desktop     | [0e2d6062d9](https://linux-hardware.org/?probe=0e2d6062d9) | Sep 24, 2020 |
| HP            | 843F                        | Desktop     | [6f9898a049](https://linux-hardware.org/?probe=6f9898a049) | Sep 24, 2020 |
| Lenovo        | ThinkPad P50 20EN0005UK     | Notebook    | [94c1b32081](https://linux-hardware.org/?probe=94c1b32081) | Sep 21, 2020 |
| HP            | 843F                        | Desktop     | [91498f153e](https://linux-hardware.org/?probe=91498f153e) | Sep 18, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [e3dab03999](https://linux-hardware.org/?probe=e3dab03999) | Sep 01, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [08f2b63110](https://linux-hardware.org/?probe=08f2b63110) | Aug 31, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [8b995a24c1](https://linux-hardware.org/?probe=8b995a24c1) | Aug 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [97293b7aa0](https://linux-hardware.org/?probe=97293b7aa0) | Aug 04, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0FA0... | Notebook    | [93b236ab24](https://linux-hardware.org/?probe=93b236ab24) | Aug 01, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [7556ef6b87](https://linux-hardware.org/?probe=7556ef6b87) | Jul 22, 2020 |
| HP            | 843F                        | Desktop     | [e0bdf38c8a](https://linux-hardware.org/?probe=e0bdf38c8a) | Jul 16, 2020 |
| Lenovo        | ThinkPad T490 20N3S5DU27    | Notebook    | [d4bb886295](https://linux-hardware.org/?probe=d4bb886295) | Jul 08, 2020 |
| Dell          | Latitude 5300               | Notebook    | [65284e0295](https://linux-hardware.org/?probe=65284e0295) | Jul 04, 2020 |
| Timi          | TM1707                      | Notebook    | [84538e3769](https://linux-hardware.org/?probe=84538e3769) | Jun 30, 2020 |
| Timi          | TM1707                      | Notebook    | [1267830169](https://linux-hardware.org/?probe=1267830169) | Jun 30, 2020 |
| ASUSTek       | GL502VMK                    | Notebook    | [45e4ef6c32](https://linux-hardware.org/?probe=45e4ef6c32) | Jun 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ce5bce7893](https://linux-hardware.org/?probe=ce5bce7893) | Jun 19, 2020 |
| Dell          | Latitude 5300               | Notebook    | [8ebae81f7c](https://linux-hardware.org/?probe=8ebae81f7c) | Jun 18, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [b9a88cd7cf](https://linux-hardware.org/?probe=b9a88cd7cf) | Jun 13, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [b74e2f66bd](https://linux-hardware.org/?probe=b74e2f66bd) | May 29, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [de063b9994](https://linux-hardware.org/?probe=de063b9994) | May 28, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [9b51817b92](https://linux-hardware.org/?probe=9b51817b92) | May 26, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [416ff2ebbb](https://linux-hardware.org/?probe=416ff2ebbb) | May 23, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [06bf1966d5](https://linux-hardware.org/?probe=06bf1966d5) | May 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b97f2eb31f](https://linux-hardware.org/?probe=b97f2eb31f) | May 20, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Dell          | 00V62H A01                  | Desktop     | [220c6fdf1c](https://linux-hardware.org/?probe=220c6fdf1c) | May 13, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6237c4cae4](https://linux-hardware.org/?probe=6237c4cae4) | May 10, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [0108b32128](https://linux-hardware.org/?probe=0108b32128) | May 07, 2020 |
| Dell          | G3 3779                     | Notebook    | [5416d30b40](https://linux-hardware.org/?probe=5416d30b40) | May 05, 2020 |
| Dell          | Precision 5540              | Notebook    | [3c0f6bcf28](https://linux-hardware.org/?probe=3c0f6bcf28) | Apr 29, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [9657b92263](https://linux-hardware.org/?probe=9657b92263) | Apr 14, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [ea2a99e61e](https://linux-hardware.org/?probe=ea2a99e61e) | Apr 12, 2020 |
| Gigabyte      | B75-D3V                     | Desktop     | [73b3145cb4](https://linux-hardware.org/?probe=73b3145cb4) | Apr 10, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [8dad315eb5](https://linux-hardware.org/?probe=8dad315eb5) | Apr 07, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [848a63637f](https://linux-hardware.org/?probe=848a63637f) | Apr 01, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [d955389819](https://linux-hardware.org/?probe=d955389819) | Mar 27, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [c86bb46fad](https://linux-hardware.org/?probe=c86bb46fad) | Mar 26, 2020 |
| Lenovo        | ThinkPad T590 20N5S2NC00    | Notebook    | [79d1c623b5](https://linux-hardware.org/?probe=79d1c623b5) | Mar 24, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [07d54a6a50](https://linux-hardware.org/?probe=07d54a6a50) | Mar 24, 2020 |
| Alienware     | 0VDT73 A00                  | Desktop     | [00cc8f89dc](https://linux-hardware.org/?probe=00cc8f89dc) | Mar 17, 2020 |
| Lenovo        | ThinkPad T450s 20BWS0B50... | Notebook    | [e2eabf79b0](https://linux-hardware.org/?probe=e2eabf79b0) | Mar 03, 2020 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [a018f0a4d4](https://linux-hardware.org/?probe=a018f0a4d4) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [908bc46e69](https://linux-hardware.org/?probe=908bc46e69) | Feb 27, 2020 |
| Sony          | VPCEB23FM                   | Notebook    | [654cbddfc9](https://linux-hardware.org/?probe=654cbddfc9) | Feb 26, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [e2a3815dd2](https://linux-hardware.org/?probe=e2a3815dd2) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [da0c7d43d0](https://linux-hardware.org/?probe=da0c7d43d0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [07bde7dae0](https://linux-hardware.org/?probe=07bde7dae0) | Feb 21, 2020 |
| Dell          | 0FRVY0 A05                  | Server      | [6e7911571a](https://linux-hardware.org/?probe=6e7911571a) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [502ac45263](https://linux-hardware.org/?probe=502ac45263) | Feb 21, 2020 |
| Dell          | 08D89F A02                  | Server      | [412539e106](https://linux-hardware.org/?probe=412539e106) | Feb 21, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [ce36caf100](https://linux-hardware.org/?probe=ce36caf100) | Feb 18, 2020 |
| Lenovo        | ThinkCentre M91p 0266RZ1    | Desktop     | [13d8453be0](https://linux-hardware.org/?probe=13d8453be0) | Feb 18, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [48c65f99c6](https://linux-hardware.org/?probe=48c65f99c6) | Feb 17, 2020 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [4e770d86e3](https://linux-hardware.org/?probe=4e770d86e3) | Feb 15, 2020 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [78dbc955e7](https://linux-hardware.org/?probe=78dbc955e7) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [0a9570ceaf](https://linux-hardware.org/?probe=0a9570ceaf) | Jan 29, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [2b0d41a249](https://linux-hardware.org/?probe=2b0d41a249) | Jan 29, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [319aa86f81](https://linux-hardware.org/?probe=319aa86f81) | Jan 25, 2020 |
| Dell          | 0XR1GT A00                  | Desktop     | [189883a0aa](https://linux-hardware.org/?probe=189883a0aa) | Jan 25, 2020 |
| Lenovo        | ThinkPad T490s 20NX002HU... | Notebook    | [622df7e336](https://linux-hardware.org/?probe=622df7e336) | Jan 24, 2020 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [bfacbe4d23](https://linux-hardware.org/?probe=bfacbe4d23) | Jan 18, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [ff60ab76a9](https://linux-hardware.org/?probe=ff60ab76a9) | Jan 15, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [6bffc36e6a](https://linux-hardware.org/?probe=6bffc36e6a) | Jan 06, 2020 |
| ASRock        | H91M-PLUS                   | Desktop     | [c90d6b4c4d](https://linux-hardware.org/?probe=c90d6b4c4d) | Dec 30, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [fff26d5712](https://linux-hardware.org/?probe=fff26d5712) | Dec 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [21aeb33209](https://linux-hardware.org/?probe=21aeb33209) | Dec 18, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [199fad181e](https://linux-hardware.org/?probe=199fad181e) | Nov 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7b90aa9c1b](https://linux-hardware.org/?probe=7b90aa9c1b) | Nov 21, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1858b15d73](https://linux-hardware.org/?probe=1858b15d73) | Nov 20, 2019 |
| Dell          | 0G919G A00                  | Desktop     | [bdf53b02dc](https://linux-hardware.org/?probe=bdf53b02dc) | Nov 18, 2019 |
| Lenovo        | ThinkPad X270 20HN001EMC    | Notebook    | [e052f322df](https://linux-hardware.org/?probe=e052f322df) | Nov 15, 2019 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [6a11247e37](https://linux-hardware.org/?probe=6a11247e37) | Nov 11, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [aba56c558d](https://linux-hardware.org/?probe=aba56c558d) | Nov 10, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [8dbaf2e95e](https://linux-hardware.org/?probe=8dbaf2e95e) | Nov 07, 2019 |
| HP            | 250 G4 Notebook PC          | Notebook    | [0347166558](https://linux-hardware.org/?probe=0347166558) | Nov 07, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f5adffebe4](https://linux-hardware.org/?probe=f5adffebe4) | Oct 30, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [505e506351](https://linux-hardware.org/?probe=505e506351) | Oct 26, 2019 |
| Supermicro    | X7DWN+                      | Desktop     | [5ad617d6ad](https://linux-hardware.org/?probe=5ad617d6ad) | Oct 25, 2019 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [2204d80ff6](https://linux-hardware.org/?probe=2204d80ff6) | Oct 22, 2019 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [d1d0246ce6](https://linux-hardware.org/?probe=d1d0246ce6) | Aug 09, 2019 |
| Dell          | Latitude 7390               | Notebook    | [9b0861a491](https://linux-hardware.org/?probe=9b0861a491) | Jul 04, 2019 |
| Dell          | Latitude 7390               | Notebook    | [5090404699](https://linux-hardware.org/?probe=5090404699) | Jul 04, 2019 |
| Lenovo        | ThinkPad L480 20LSS0M100    | Notebook    | [b1b6812c4f](https://linux-hardware.org/?probe=b1b6812c4f) | May 19, 2019 |
| Dell          | 0HHV7N A00                  | Desktop     | [9e55c4bdee](https://linux-hardware.org/?probe=9e55c4bdee) | Apr 05, 2019 |
| HP            | 158A                        | Desktop     | [6924d366ab](https://linux-hardware.org/?probe=6924d366ab) | Jan 09, 2019 |
| Dell          | 05DN3X A00                  | Desktop     | [4be9ce0f72](https://linux-hardware.org/?probe=4be9ce0f72) | Dec 20, 2018 |
| Lenovo        | ThinkPad X131e 3368CTO      | Notebook    | [c3f67b75e2](https://linux-hardware.org/?probe=c3f67b75e2) | Oct 31, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| RHEL 8 | 168       | 75.34%  |
| RHEL 7 | 39        | 17.49%  |
| RHEL 9 | 16        | 7.17%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| RHEL | 222       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                      | Computers | Percent |
|----------------------------------------------|-----------|---------|
| 4.18.0-240.10.1.el8_3.x86_64                 | 14        | 5.36%   |
| 4.18.0-240.1.1.el8_3.x86_64                  | 14        | 5.36%   |
| 4.18.0-348.20.1.el8_5.x86_64                 | 12        | 4.6%    |
| 4.18.0-240.15.1.el8_3.x86_64                 | 11        | 4.21%   |
| 4.18.0-305.el8.x86_64                        | 10        | 3.83%   |
| 4.18.0-80.11.2.el8_0.x86_64                  | 9         | 3.45%   |
| 4.18.0-348.12.2.el8_5.x86_64                 | 9         | 3.45%   |
| 4.18.0-240.22.1.el8_3.x86_64                 | 9         | 3.45%   |
| 4.18.0-305.3.1.el8_4.x86_64                  | 8         | 3.07%   |
| 4.18.0-305.19.1.el8_4.x86_64                 | 8         | 3.07%   |
| 4.18.0-305.10.2.el8_4.x86_64                 | 7         | 2.68%   |
| 5.14.0-70.17.1.el9_0.x86_64                  | 6         | 2.3%    |
| 4.18.0-348.2.1.el8_5.x86_64                  | 6         | 2.3%    |
| 4.18.0-193.el8.x86_64                        | 6         | 2.3%    |
| 4.18.0-193.19.1.el8_2.x86_64                 | 6         | 2.3%    |
| 4.18.0-147.5.1.el8_1.x86_64                  | 6         | 2.3%    |
| 4.18.0-147.3.1.el8_1.x86_64                  | 6         | 2.3%    |
| 3.10.0-1062.12.1.el7.x86_64                  | 6         | 2.3%    |
| 4.18.0-305.7.1.el8_4.x86_64                  | 5         | 1.92%   |
| 4.18.0-193.6.3.el8_2.x86_64                  | 5         | 1.92%   |
| 5.14.0-70.5.1.el9_0.x86_64                   | 4         | 1.53%   |
| 4.18.0-372.9.1.el8.x86_64                    | 4         | 1.53%   |
| 4.18.0-348.7.1.el8_5.x86_64                  | 4         | 1.53%   |
| 4.18.0-305.25.1.el8_4.x86_64                 | 4         | 1.53%   |
| 4.18.0-305.12.1.el8_4.x86_64                 | 4         | 1.53%   |
| 4.18.0-193.28.1.el8_2.x86_64                 | 4         | 1.53%   |
| 4.18.0-147.el8.x86_64                        | 4         | 1.53%   |
| 4.18.0-147.8.1.el8_1.x86_64                  | 3         | 1.15%   |
| 3.10.0-862.3.2.el7.x86_64                    | 3         | 1.15%   |
| 3.10.0-1062.4.3.el7.YAHOO.20191113.49.x86_64 | 3         | 1.15%   |
| 3.10.0-1062.18.1.el7.x86_64                  | 3         | 1.15%   |
| 5.14.0-70.13.1.el9_0.x86_64                  | 2         | 0.77%   |
| 4.18.0-348.el8.x86_64                        | 2         | 0.77%   |
| 4.18.0-305.17.1.el8_4.x86_64                 | 2         | 0.77%   |
| 4.18.0-240.8.1.el8_3.x86_64                  | 2         | 0.77%   |
| 4.18.0-193.14.3.el8_2.x86_64                 | 2         | 0.77%   |
| 4.18.0-193.1.2.el8_2.x86_64                  | 2         | 0.77%   |
| 3.10.0-1160.6.1.el7.x86_64                   | 2         | 0.77%   |
| 3.10.0-1160.2.2.el7.x86_64                   | 2         | 0.77%   |
| 3.10.0-1160.15.2.el7.x86_64                  | 2         | 0.77%   |
| 3.10.0-1127.13.1.el7.x86_64                  | 2         | 0.77%   |
| 5.9.1-1.el8.elrepo.x86_64                    | 1         | 0.38%   |
| 5.14.0-70.22.1.el9_0.x86_64                  | 1         | 0.38%   |
| 5.14.0-70.17.1.el9_0.aarch64                 | 1         | 0.38%   |
| 5.14.0-39.el9.x86_64                         | 1         | 0.38%   |
| 5.14.0-1.7.1.el9.x86_64                      | 1         | 0.38%   |
| 5.13.13-1.el8.elrepo.x86_64                  | 1         | 0.38%   |
| 5.13.0-1.el8.elrepo.x86_64                   | 1         | 0.38%   |
| 5.10.6-1.el8.elrepo.x86_64                   | 1         | 0.38%   |
| 4.19.150                                     | 1         | 0.38%   |
| 4.18.0-80.el8.x86_64                         | 1         | 0.38%   |
| 4.18.0-80.4.2.el8_0.x86_64                   | 1         | 0.38%   |
| 4.18.0-372.19.1.el8_6.x86_64                 | 1         | 0.38%   |
| 4.18.0-372.13.1.el8_6.x86_64                 | 1         | 0.38%   |
| 4.18.0-221.el8.x86_64                        | 1         | 0.38%   |
| 4.18.0-193.23.1.el8_2.x86_64                 | 1         | 0.38%   |
| 4.18.0-193.13.2.el8_2.x86_64                 | 1         | 0.38%   |
| 4.18.0-168.el8.x86_64                        | 1         | 0.38%   |
| 4.18.0-147.0.3.el8_1.x86_64                  | 1         | 0.38%   |
| 4.18.0-144.el8.x86_64                        | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.18.0   | 162       | 72.65%  |
| 3.10.0   | 39        | 17.49%  |
| 5.14.0   | 16        | 7.17%   |
| 5.9.1    | 1         | 0.45%   |
| 5.13.13  | 1         | 0.45%   |
| 5.13.0   | 1         | 0.45%   |
| 5.10.6   | 1         | 0.45%   |
| 4.19.150 | 1         | 0.45%   |
| Unknown  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 162       | 72.65%  |
| 3.10    | 39        | 17.49%  |
| 5.14    | 16        | 7.17%   |
| 5.13    | 2         | 0.9%    |
| 5.9     | 1         | 0.45%   |
| 5.10    | 1         | 0.45%   |
| 4.19    | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 220       | 99.1%   |
| aarch64 | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 164       | 71%     |
| Unknown       | 45        | 19.48%  |
| GNOME Classic | 13        | 5.63%   |
| KDE5          | 5         | 2.16%   |
| KDE           | 2         | 0.87%   |
| MATE          | 1         | 0.43%   |
| Cinnamon      | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 121       | 52.84%  |
| Wayland | 78        | 34.06%  |
| Unknown | 29        | 12.66%  |
| Tty     | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 174       | 75.65%  |
| GDM     | 54        | 23.48%  |
| SDDM    | 1         | 0.43%   |
| LightDM | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 147       | 65.04%  |
| Unknown | 26        | 11.5%   |
| en_GB   | 14        | 6.19%   |
| en_IN   | 5         | 2.21%   |
| ru_RU   | 4         | 1.77%   |
| pl_PL   | 4         | 1.77%   |
| fr_FR   | 4         | 1.77%   |
| de_DE   | 4         | 1.77%   |
| pt_BR   | 2         | 0.88%   |
| nl_NL   | 2         | 0.88%   |
| es_ES   | 2         | 0.88%   |
| es_AR   | 2         | 0.88%   |
| en_IE   | 2         | 0.88%   |
| ko_KR   | 1         | 0.44%   |
| ja_JP   | 1         | 0.44%   |
| it_IT   | 1         | 0.44%   |
| es_MX   | 1         | 0.44%   |
| es_EC   | 1         | 0.44%   |
| en_NZ   | 1         | 0.44%   |
| de_CH   | 1         | 0.44%   |
| cs_CZ   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 160       | 70.48%  |
| BIOS | 67        | 29.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 186       | 82.67%  |
| Ext4    | 27        | 12%     |
| Unknown | 12        | 5.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 61.74%  |
| GPT     | 69        | 30%     |
| MBR     | 19        | 8.26%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 195       | 86.28%  |
| Yes       | 31        | 13.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 92.89%  |
| Yes       | 16        | 7.11%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 82        | 36.94%  |
| Dell                    | 50        | 22.52%  |
| Hewlett-Packard         | 26        | 11.71%  |
| ASUSTek Computer        | 19        | 8.56%   |
| Gigabyte Technology     | 9         | 4.05%   |
| ASRock                  | 6         | 2.7%    |
| MSI                     | 4         | 1.8%    |
| Intel                   | 4         | 1.8%    |
| Unknown                 | 4         | 1.8%    |
| Supermicro              | 3         | 1.35%   |
| ZTSYSTEMS               | 2         | 0.9%    |
| Sony                    | 2         | 0.9%    |
| Acer                    | 2         | 0.9%    |
| TUXEDO                  | 1         | 0.45%   |
| Toshiba                 | 1         | 0.45%   |
| Timi                    | 1         | 0.45%   |
| Samsung Electronics     | 1         | 0.45%   |
| Raspberry Pi Foundation | 1         | 0.45%   |
| MiTAC                   | 1         | 0.45%   |
| CX / Air Computers.     | 1         | 0.45%   |
| AMI                     | 1         | 0.45%   |
| Alienware               | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge FC630                     | 6         | 2.7%    |
| Lenovo ThinkPad P1 Gen 3 20TJS2F40X      | 4         | 1.8%    |
| Dell PowerEdge R230                      | 4         | 1.8%    |
| ASUS All Series                          | 4         | 1.8%    |
| Unknown                                  | 4         | 1.8%    |
| Supermicro X10DRi                        | 2         | 0.9%    |
| Lenovo ThinkPad X1 Carbon 7th 20QES2P401 | 2         | 0.9%    |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00 | 2         | 0.9%    |
| Lenovo ThinkPad T590 20N5S2NC0N          | 2         | 0.9%    |
| Lenovo ThinkPad T490s 20NYS7K91R         | 2         | 0.9%    |
| Lenovo ThinkPad T14s Gen 1 20T1S39D08    | 2         | 0.9%    |
| Lenovo ThinkPad P1 Gen 3 20TJS2F42Q      | 2         | 0.9%    |
| Lenovo 7X56CTO1WW HR630X                 | 2         | 0.9%    |
| HP Z620 Workstation                      | 2         | 0.9%    |
| HP EliteBook 8460p                       | 2         | 0.9%    |
| Dell Precision 7510                      | 2         | 0.9%    |
| Dell PowerEdge R740                      | 2         | 0.9%    |
| Dell OptiPlex 9020                       | 2         | 0.9%    |
| Dell Latitude E6430                      | 2         | 0.9%    |
| Dell Latitude 5300                       | 2         | 0.9%    |
| ZTSYSTEMS Z802                           | 1         | 0.45%   |
| ZTSYSTEMS Z801                           | 1         | 0.45%   |
| TUXEDO N13xWU                            | 1         | 0.45%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.45%   |
| Timi TM1707                              | 1         | 0.45%   |
| Supermicro X7DW3                         | 1         | 0.45%   |
| Sony VPCEB4L1R                           | 1         | 0.45%   |
| Sony VPCEB23FM                           | 1         | 0.45%   |
| Samsung 730QCJ/730QCR                    | 1         | 0.45%   |
| RPi Raspberry Pi 4 Model B               | 1         | 0.45%   |
| MSI MS-7B51                              | 1         | 0.45%   |
| MSI MS-7B33                              | 1         | 0.45%   |
| MSI MS-7A37                              | 1         | 0.45%   |
| MSI MS-7752                              | 1         | 0.45%   |
| MiTAC C4I                                | 1         | 0.45%   |
| Lenovo Z40-70 20366                      | 1         | 0.45%   |
| Lenovo Yoga C640-13IML 81UE              | 1         | 0.45%   |
| Lenovo ThinkSystem SR645                 | 1         | 0.45%   |
| Lenovo ThinkPad X270 20HN001EMC          | 1         | 0.45%   |
| Lenovo ThinkPad X250 20CLS0H807          | 1         | 0.45%   |
| Lenovo ThinkPad X230 Tablet 34373KU      | 1         | 0.45%   |
| Lenovo ThinkPad X201 3680PKS             | 1         | 0.45%   |
| Lenovo ThinkPad X131e 3368CTO            | 1         | 0.45%   |
| Lenovo ThinkPad X1 Yoga 1st 20FRS17K00   | 1         | 0.45%   |
| Lenovo ThinkPad X1 Yoga 1st 20FCS2N100   | 1         | 0.45%   |
| Lenovo ThinkPad W530 2441B32             | 1         | 0.45%   |
| Lenovo ThinkPad W520 4284GN2             | 1         | 0.45%   |
| Lenovo ThinkPad T590 20N5S2NC0V          | 1         | 0.45%   |
| Lenovo ThinkPad T590 20N5S2NC00          | 1         | 0.45%   |
| Lenovo ThinkPad T520 42404CG             | 1         | 0.45%   |
| Lenovo ThinkPad T490s 20NYS7K905         | 1         | 0.45%   |
| Lenovo ThinkPad T490s 20NX002HUS         | 1         | 0.45%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.45%   |
| Lenovo ThinkPad T490 20N3S5DU27          | 1         | 0.45%   |
| Lenovo ThinkPad T480s 20L8S2N80V         | 1         | 0.45%   |
| Lenovo ThinkPad T480s 20L8S2N800         | 1         | 0.45%   |
| Lenovo ThinkPad T480 20L6S29E1T          | 1         | 0.45%   |
| Lenovo ThinkPad T480 20L6S29D02          | 1         | 0.45%   |
| Lenovo ThinkPad T480 20L60034MX          | 1         | 0.45%   |
| Lenovo ThinkPad T470p 20J7S0FA0E         | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 70        | 31.53%  |
| Dell PowerEdge       | 14        | 6.31%   |
| Dell Precision       | 13        | 5.86%   |
| Dell Latitude        | 10        | 4.5%    |
| HP ProLiant          | 5         | 2.25%   |
| HP EliteBook         | 4         | 1.8%    |
| Dell Inspiron        | 4         | 1.8%    |
| ASUS All             | 4         | 1.8%    |
| Unknown              | 4         | 1.8%    |
| Lenovo ThinkCentre   | 3         | 1.35%   |
| HP ZBook             | 3         | 1.35%   |
| Dell OptiPlex        | 3         | 1.35%   |
| ASUS PRIME           | 3         | 1.35%   |
| Supermicro X10DRi    | 2         | 0.9%    |
| Lenovo 7X56CTO1WW    | 2         | 0.9%    |
| HP Z620              | 2         | 0.9%    |
| HP Z230              | 2         | 0.9%    |
| Dell XPS             | 2         | 0.9%    |
| ASUS TUF             | 2         | 0.9%    |
| ASUS ROG             | 2         | 0.9%    |
| ZTSYSTEMS Z802       | 1         | 0.45%   |
| ZTSYSTEMS Z801       | 1         | 0.45%   |
| TUXEDO N13xWU        | 1         | 0.45%   |
| Toshiba Satellite    | 1         | 0.45%   |
| Timi TM1707          | 1         | 0.45%   |
| Supermicro X7DW3     | 1         | 0.45%   |
| Sony VPCEB4L1R       | 1         | 0.45%   |
| Sony VPCEB23FM       | 1         | 0.45%   |
| Samsung 730QCJ       | 1         | 0.45%   |
| RPi Raspberry        | 1         | 0.45%   |
| MSI MS-7B51          | 1         | 0.45%   |
| MSI MS-7B33          | 1         | 0.45%   |
| MSI MS-7A37          | 1         | 0.45%   |
| MSI MS-7752          | 1         | 0.45%   |
| MiTAC C4I            | 1         | 0.45%   |
| Lenovo Z40-70        | 1         | 0.45%   |
| Lenovo Yoga          | 1         | 0.45%   |
| Lenovo ThinkSystem   | 1         | 0.45%   |
| Lenovo ThinkBook     | 1         | 0.45%   |
| Lenovo S40-40        | 1         | 0.45%   |
| Lenovo Legion        | 1         | 0.45%   |
| Lenovo 10SFS03200    | 1         | 0.45%   |
| Intel NUC11BTMi7     | 1         | 0.45%   |
| Intel NUC10i7FNK     | 1         | 0.45%   |
| Intel H81            | 1         | 0.45%   |
| Intel DX79SR         | 1         | 0.45%   |
| HP Z840              | 1         | 0.45%   |
| HP Z440              | 1         | 0.45%   |
| HP ProBook           | 1         | 0.45%   |
| HP Pavilion          | 1         | 0.45%   |
| HP OMEN              | 1         | 0.45%   |
| HP ENVY              | 1         | 0.45%   |
| HP EliteDesk         | 1         | 0.45%   |
| HP 290               | 1         | 0.45%   |
| HP 260-P020il        | 1         | 0.45%   |
| HP 250               | 1         | 0.45%   |
| Gigabyte Z97N-WIFI   | 1         | 0.45%   |
| Gigabyte Z490        | 1         | 0.45%   |
| Gigabyte Z390        | 1         | 0.45%   |
| Gigabyte MU72-SU0-00 | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 39        | 17.57%  |
| 2019 | 37        | 16.67%  |
| 2018 | 32        | 14.41%  |
| 2017 | 19        | 8.56%   |
| 2016 | 19        | 8.56%   |
| 2015 | 15        | 6.76%   |
| 2012 | 15        | 6.76%   |
| 2013 | 12        | 5.41%   |
| 2021 | 11        | 4.95%   |
| 2011 | 8         | 3.6%    |
| 2010 | 6         | 2.7%    |
| 2014 | 5         | 2.25%   |
| 2022 | 2         | 0.9%    |
| 2009 | 2         | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 122       | 54.95%  |
| Desktop        | 68        | 30.63%  |
| Server         | 23        | 10.36%  |
| Mini pc        | 4         | 1.8%    |
| Convertible    | 3         | 1.35%   |
| System on chip | 1         | 0.45%   |
| All in one     | 1         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 198       | 88.39%  |
| Enabled  | 26        | 11.61%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 57        | 25.11%  |
| 4.01-8.0        | 38        | 16.74%  |
| 64.01-256.0     | 36        | 15.86%  |
| 8.01-16.0       | 36        | 15.86%  |
| 16.01-24.0      | 35        | 15.42%  |
| 24.01-32.0      | 10        | 4.41%   |
| 3.01-4.0        | 8         | 3.52%   |
| More than 256.0 | 5         | 2.2%    |
| 2.01-3.0        | 1         | 0.44%   |
| Unknown         | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 88        | 35.92%  |
| 2.01-3.0        | 46        | 18.78%  |
| 8.01-16.0       | 36        | 14.69%  |
| 3.01-4.0        | 34        | 13.88%  |
| 1.01-2.0        | 24        | 9.8%    |
| 24.01-32.0      | 5         | 2.04%   |
| 16.01-24.0      | 4         | 1.63%   |
| 0.51-1.0        | 3         | 1.22%   |
| 32.01-64.0      | 2         | 0.82%   |
| More than 256.0 | 1         | 0.41%   |
| 64.01-256.0     | 1         | 0.41%   |
| Unknown         | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 53.71%  |
| 2      | 49        | 21.4%   |
| 3      | 27        | 11.79%  |
| 5      | 9         | 3.93%   |
| 4      | 9         | 3.93%   |
| 12     | 3         | 1.31%   |
| 6      | 3         | 1.31%   |
| 8      | 2         | 0.87%   |
| 14     | 1         | 0.44%   |
| 11     | 1         | 0.44%   |
| 7      | 1         | 0.44%   |
| 0      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 176       | 78.57%  |
| Yes       | 48        | 21.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 91.48%  |
| No        | 19        | 8.52%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 71.17%  |
| No        | 64        | 28.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 130       | 57.27%  |
| No        | 97        | 42.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 57        | 25.68%  |
| India        | 19        | 8.56%   |
| UK           | 15        | 6.76%   |
| Germany      | 15        | 6.76%   |
| Czechia      | 13        | 5.86%   |
| Norway       | 7         | 3.15%   |
| France       | 6         | 2.7%    |
| Canada       | 6         | 2.7%    |
| Spain        | 5         | 2.25%   |
| Poland       | 5         | 2.25%   |
| Switzerland  | 4         | 1.8%    |
| Russia       | 4         | 1.8%    |
| Netherlands  | 4         | 1.8%    |
| Mexico       | 4         | 1.8%    |
| Italy        | 4         | 1.8%    |
| Lithuania    | 3         | 1.35%   |
| Brazil       | 3         | 1.35%   |
| Argentina    | 3         | 1.35%   |
| Ukraine      | 2         | 0.9%    |
| South Korea  | 2         | 0.9%    |
| South Africa | 2         | 0.9%    |
| Singapore    | 2         | 0.9%    |
| Romania      | 2         | 0.9%    |
| Japan        | 2         | 0.9%    |
| Egypt        | 2         | 0.9%    |
| China        | 2         | 0.9%    |
| Austria      | 2         | 0.9%    |
| Australia    | 2         | 0.9%    |
| Turkmenistan | 1         | 0.45%   |
| Turkey       | 1         | 0.45%   |
| Sweden       | 1         | 0.45%   |
| Sri Lanka    | 1         | 0.45%   |
| Saudi Arabia | 1         | 0.45%   |
| Portugal     | 1         | 0.45%   |
| Pakistan     | 1         | 0.45%   |
| New Zealand  | 1         | 0.45%   |
| Nepal        | 1         | 0.45%   |
| Myanmar      | 1         | 0.45%   |
| Morocco      | 1         | 0.45%   |
| Luxembourg   | 1         | 0.45%   |
| Kuwait       | 1         | 0.45%   |
| Israel       | 1         | 0.45%   |
| Ireland      | 1         | 0.45%   |
| Indonesia    | 1         | 0.45%   |
| Georgia      | 1         | 0.45%   |
| Finland      | 1         | 0.45%   |
| Ecuador      | 1         | 0.45%   |
| Colombia     | 1         | 0.45%   |
| Chile        | 1         | 0.45%   |
| Bulgaria     | 1         | 0.45%   |
| Belgium      | 1         | 0.45%   |
| Belarus      | 1         | 0.45%   |
| Armenia      | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Prague                   | 11        | 4.7%    |
| Quincy                   | 8         | 3.42%   |
| Langgons                 | 6         | 2.56%   |
| Tromsø                  | 4         | 1.71%   |
| San Jose                 | 3         | 1.28%   |
| Munich                   | 3         | 1.28%   |
| Milan                    | 3         | 1.28%   |
| Mexico City              | 3         | 1.28%   |
| Chicago                  | 3         | 1.28%   |
| Toronto                  | 2         | 0.85%   |
| Singapore                | 2         | 0.85%   |
| Oslo                     | 2         | 0.85%   |
| Montreal                 | 2         | 0.85%   |
| Madrid                   | 2         | 0.85%   |
| Kyiv                     | 2         | 0.85%   |
| Houston                  | 2         | 0.85%   |
| Didcot                   | 2         | 0.85%   |
| Des Moines               | 2         | 0.85%   |
| Chennai                  | 2         | 0.85%   |
| Berlin                   | 2         | 0.85%   |
| Bengaluru                | 2         | 0.85%   |
| Zaragoza                 | 1         | 0.43%   |
| Yorktown Heights         | 1         | 0.43%   |
| Yongin-si                | 1         | 0.43%   |
| Wroclaw                  | 1         | 0.43%   |
| Wiesbaden                | 1         | 0.43%   |
| Webster                  | 1         | 0.43%   |
| Vienna                   | 1         | 0.43%   |
| Vardenis                 | 1         | 0.43%   |
| Vaglio                   | 1         | 0.43%   |
| Udaipur                  | 1         | 0.43%   |
| Turku                    | 1         | 0.43%   |
| Tiruchi                  | 1         | 0.43%   |
| Temuco                   | 1         | 0.43%   |
| Temara                   | 1         | 0.43%   |
| Tauranga                 | 1         | 0.43%   |
| Taringa                  | 1         | 0.43%   |
| Talkha                   | 1         | 0.43%   |
| Syracuse                 | 1         | 0.43%   |
| Sutton                   | 1         | 0.43%   |
| Suffolk                  | 1         | 0.43%   |
| Streatham                | 1         | 0.43%   |
| Steamboat Springs        | 1         | 0.43%   |
| Stavropol                | 1         | 0.43%   |
| Spokane                  | 1         | 0.43%   |
| Sofia                    | 1         | 0.43%   |
| Skien                    | 1         | 0.43%   |
| Šilalė                 | 1         | 0.43%   |
| Šiauliai                | 1         | 0.43%   |
| Sheffield                | 1         | 0.43%   |
| Saratov                  | 1         | 0.43%   |
| San Francisco            | 1         | 0.43%   |
| San Fernando             | 1         | 0.43%   |
| Salzburg                 | 1         | 0.43%   |
| Salvador                 | 1         | 0.43%   |
| Saltillo                 | 1         | 0.43%   |
| Salt Lake City           | 1         | 0.43%   |
| Salisbury                | 1         | 0.43%   |
| Saint-Ismier             | 1         | 0.43%   |
| Saint-Alphonse-Rodriguez | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 90     | 16.18%  |
| WDC                 | 44        | 74     | 12.94%  |
| Seagate             | 44        | 88     | 12.94%  |
| Toshiba             | 32        | 45     | 9.41%   |
| SK hynix            | 18        | 22     | 5.29%   |
| SanDisk             | 18        | 27     | 5.29%   |
| Intel               | 16        | 23     | 4.71%   |
| Kingston            | 15        | 19     | 4.41%   |
| Micron Technology   | 11        | 19     | 3.24%   |
| Unknown             | 10        | 12     | 2.94%   |
| Crucial             | 9         | 12     | 2.65%   |
| Phison              | 6         | 10     | 1.76%   |
| HGST                | 6         | 9      | 1.76%   |
| Dell                | 5         | 9      | 1.47%   |
| A-DATA Technology   | 5         | 5      | 1.47%   |
| Hitachi             | 4         | 4      | 1.18%   |
| Hewlett-Packard     | 4         | 13     | 1.18%   |
| Silicon Motion      | 3         | 4      | 0.88%   |
| PNY                 | 3         | 4      | 0.88%   |
| Corsair             | 3         | 6      | 0.88%   |
| China               | 3         | 3      | 0.88%   |
| Western Digital     | 2         | 2      | 0.59%   |
| Lenovo              | 2         | 2      | 0.59%   |
| KIOXIA              | 2         | 2      | 0.59%   |
| Gigabyte Technology | 2         | 2      | 0.59%   |
| XUM                 | 1         | 1      | 0.29%   |
| XPG                 | 1         | 1      | 0.29%   |
| Transcend           | 1         | 1      | 0.29%   |
| Team                | 1         | 2      | 0.29%   |
| T-FORCE             | 1         | 2      | 0.29%   |
| SMI                 | 1         | 2      | 0.29%   |
| SCST_FIO            | 1         | 9      | 0.29%   |
| SABRENT             | 1         | 1      | 0.29%   |
| OCZ                 | 1         | 2      | 0.29%   |
| NVMe                | 1         | 1      | 0.29%   |
| Lite-On             | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| KingFast            | 1         | 1      | 0.29%   |
| KINGBANK            | 1         | 1      | 0.29%   |
| HPT                 | 1         | 1      | 0.29%   |
| Hoodisk             | 1         | 1      | 0.29%   |
| DELLBOSS            | 1         | 1      | 0.29%   |
| Anobit              | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| SK hynix NVMe SSD Drive 512GB           | 10        | 2.6%    |
| Samsung NVMe SSD Drive 512GB            | 8         | 2.08%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 6         | 1.56%   |
| SanDisk NVMe SSD Drive 256GB            | 6         | 1.56%   |
| Samsung NVMe SSD Drive 256GB            | 6         | 1.56%   |
| Samsung SSD 860 EVO 1TB                 | 5         | 1.3%    |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 5         | 1.3%    |
| Toshiba MG04ACA100NY 1TB                | 4         | 1.04%   |
| Samsung NVMe SSD Drive 500GB            | 4         | 1.04%   |
| Intel NVMe SSD Drive 512GB              | 4         | 1.04%   |
| HGST HTS721010A9E630 1TB                | 4         | 1.04%   |
| Dell MD34xx 26TB                        | 4         | 1.04%   |
| WDC WD5003ABYZ-011FA0 500GB             | 3         | 0.78%   |
| Toshiba NVMe SSD Drive 512GB            | 3         | 0.78%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.78%   |
| Samsung NVMe SSD Drive 2TB              | 3         | 0.78%   |
| Samsung NVMe SSD Drive 1TB              | 3         | 0.78%   |
| Micron NVMe SSD Drive 256GB             | 3         | 0.78%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.52%   |
| WDC WD1003FZEX-00MK2A0 1TB              | 2         | 0.52%   |
| WDC WD1002FAEX-00Z3A0 1TB               | 2         | 0.52%   |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.52%   |
| Unknown NVMe SSD Drive 256GB            | 2         | 0.52%   |
| Toshiba NVMe SSD Drive 1024GB           | 2         | 0.52%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.52%   |
| Toshiba KXG6AZNV256G 256GB              | 2         | 0.52%   |
| Toshiba DT01ACA200 2TB                  | 2         | 0.52%   |
| Toshiba AL14SEB18EQ 1.8TB               | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 1024GB          | 2         | 0.52%   |
| Seagate ST91000640NS 1TB                | 2         | 0.52%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 0.52%   |
| Seagate ST4000NM0033-9ZM170 4TB         | 2         | 0.52%   |
| Seagate ST300MP0026 304GB               | 2         | 0.52%   |
| Seagate ST2000NX0433 2TB                | 2         | 0.52%   |
| Seagate ST2000NX0273 2TB                | 2         | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB          | 2         | 0.52%   |
| Seagate ST1000LM049-2GH172 1TB          | 2         | 0.52%   |
| Seagate ST1000DM003-9YN162 1TB          | 2         | 0.52%   |
| Seagate Expansion 500GB                 | 2         | 0.52%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.52%   |
| SanDisk NVMe SSD Drive 1TB              | 2         | 0.52%   |
| Samsung Portable SSD T5 500GB           | 2         | 0.52%   |
| Kingston SUV500120G 120GB SSD           | 2         | 0.52%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 0.52%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 0.52%   |
| Intel SSDPEL1K100GA 100GB               | 2         | 0.52%   |
| Intel NVMe SSD Drive 2TB                | 2         | 0.52%   |
| HP SSD EX950 512GB                      | 2         | 0.52%   |
| Crucial CT480BX500SSD1 480GB            | 2         | 0.52%   |
| Crucial CT240BX500SSD1 240GB            | 2         | 0.52%   |
| Corsair Force LE SSD 240GB              | 2         | 0.52%   |
| XUM HX256GSSDSATA3 256GB                | 1         | 0.26%   |
| XPG NVMe SSD Drive 1024GB               | 1         | 0.26%   |
| Western Digital WUS3BA176C7P3E3 8TB     | 1         | 0.26%   |
| Western Digital NVMe SSD Drive 960GB    | 1         | 0.26%   |
| WDC WDS400T2B0A-00SM50 4TB SSD          | 1         | 0.26%   |
| WDC WDS250G2B0B-00YS70 250GB SSD        | 1         | 0.26%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.26%   |
| WDC WDS240G1G0A-00SS50 240GB SSD        | 1         | 0.26%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 87     | 36.97%  |
| WDC                 | 35        | 60     | 29.41%  |
| Toshiba             | 18        | 28     | 15.13%  |
| HGST                | 6         | 9      | 5.04%   |
| Hitachi             | 4         | 4      | 3.36%   |
| Dell                | 4         | 8      | 3.36%   |
| Unknown             | 2         | 2      | 1.68%   |
| Hewlett-Packard     | 2         | 9      | 1.68%   |
| SCST_FIO            | 1         | 9      | 0.84%   |
| Samsung Electronics | 1         | 2      | 0.84%   |
| SABRENT             | 1         | 1      | 0.84%   |
| DELLBOSS            | 1         | 1      | 0.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 31     | 26.04%  |
| Kingston            | 11        | 15     | 11.46%  |
| Crucial             | 9         | 12     | 9.38%   |
| WDC                 | 7         | 9      | 7.29%   |
| Micron Technology   | 7         | 13     | 7.29%   |
| SanDisk             | 6         | 12     | 6.25%   |
| A-DATA Technology   | 5         | 5      | 5.21%   |
| Intel               | 4         | 5      | 4.17%   |
| SK hynix            | 3         | 7      | 3.13%   |
| PNY                 | 3         | 4      | 3.13%   |
| Corsair             | 3         | 6      | 3.13%   |
| China               | 3         | 3      | 3.13%   |
| XUM                 | 1         | 1      | 1.04%   |
| Transcend           | 1         | 1      | 1.04%   |
| Toshiba             | 1         | 1      | 1.04%   |
| Team                | 1         | 2      | 1.04%   |
| Seagate             | 1         | 1      | 1.04%   |
| OCZ                 | 1         | 2      | 1.04%   |
| KingSpec            | 1         | 1      | 1.04%   |
| KINGBANK            | 1         | 1      | 1.04%   |
| Hoodisk             | 1         | 1      | 1.04%   |
| Anobit              | 1         | 1      | 1.04%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 110       | 169    | 36.18%  |
| HDD     | 97        | 220    | 31.91%  |
| SSD     | 87        | 134    | 28.62%  |
| MMC     | 6         | 7      | 1.97%   |
| Unknown | 4         | 6      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 133       | 327    | 49.26%  |
| NVMe | 110       | 169    | 40.74%  |
| SAS  | 21        | 33     | 7.78%   |
| MMC  | 6         | 7      | 2.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 149    | 44.16%  |
| 0.51-1.0   | 60        | 93     | 30.46%  |
| 1.01-2.0   | 25        | 51     | 12.69%  |
| 3.01-4.0   | 12        | 32     | 6.09%   |
| 4.01-10.0  | 7         | 19     | 3.55%   |
| 20.01-50.0 | 4         | 8      | 2.03%   |
| 2.01-3.0   | 1         | 1      | 0.51%   |
| 10.01-20.0 | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 73        | 31.33%  |
| 251-500        | 42        | 18.03%  |
| 501-1000       | 36        | 15.45%  |
| More than 3000 | 19        | 8.15%   |
| 1001-2000      | 18        | 7.73%   |
| Unknown        | 17        | 7.3%    |
| 51-100         | 11        | 4.72%   |
| 2001-3000      | 8         | 3.43%   |
| 1-20           | 6         | 2.58%   |
| 21-50          | 3         | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 61        | 24.8%   |
| 21-50          | 50        | 20.33%  |
| 101-250        | 42        | 17.07%  |
| 51-100         | 32        | 13.01%  |
| 251-500        | 17        | 6.91%   |
| Unknown        | 17        | 6.91%   |
| 501-1000       | 11        | 4.47%   |
| 1001-2000      | 9         | 3.66%   |
| More than 3000 | 4         | 1.63%   |
| 2001-3000      | 3         | 1.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD5003ABYZ-011FA0 500GB              | 1         | 1      | 9.09%   |
| WDC WD4000FYYZ-01UL1B1 4TB               | 1         | 3      | 9.09%   |
| WDC WD10EALX-759BA1 1TB                  | 1         | 2      | 9.09%   |
| Transcend TS512GMTS800 512GB SSD         | 1         | 1      | 9.09%   |
| Seagate ST91000640NS 1TB                 | 1         | 2      | 9.09%   |
| Seagate ST6000NM0024-1HT17Z 6TB          | 1         | 2      | 9.09%   |
| Seagate ST1000DM003-9YN162 1TB           | 1         | 1      | 9.09%   |
| Micron Technology M510_2.5 7MM 256GB SSD | 1         | 1      | 9.09%   |
| Intel SSDSC2BA800G4R 800GB               | 1         | 1      | 9.09%   |
| Hitachi HDS722020ALA330 2TB              | 1         | 1      | 9.09%   |
| A-DATA Technology SU800NS38 256GB SSD    | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 6      | 27.27%  |
| Seagate           | 3         | 5      | 27.27%  |
| Transcend         | 1         | 1      | 9.09%   |
| Micron Technology | 1         | 1      | 9.09%   |
| Intel             | 1         | 1      | 9.09%   |
| Hitachi           | 1         | 1      | 9.09%   |
| A-DATA Technology | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 6      | 42.86%  |
| Seagate | 3         | 5      | 42.86%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 12     | 60%     |
| SSD  | 4         | 4      | 40%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 146       | 323    | 61.86%  |
| Works    | 80        | 197    | 33.9%   |
| Malfunc  | 10        | 16     | 4.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 144       | 47.37%  |
| Samsung Electronics          | 37        | 12.17%  |
| SK hynix                     | 15        | 4.93%   |
| SanDisk                      | 15        | 4.93%   |
| AMD                          | 14        | 4.61%   |
| Toshiba America Info Systems | 13        | 4.28%   |
| Broadcom / LSI               | 13        | 4.28%   |
| Phison Electronics           | 8         | 2.63%   |
| LSI Logic / Symbios Logic    | 7         | 2.3%    |
| Silicon Motion               | 5         | 1.64%   |
| Micron Technology            | 4         | 1.32%   |
| Marvell Technology Group     | 4         | 1.32%   |
| KIOXIA                       | 4         | 1.32%   |
| Kingston Technology Company  | 4         | 1.32%   |
| Hewlett-Packard              | 4         | 1.32%   |
| ASMedia Technology           | 4         | 1.32%   |
| Western Digital              | 2         | 0.66%   |
| Lenovo                       | 2         | 0.66%   |
| Biwin Storage Technology     | 2         | 0.66%   |
| Lite-On Technology           | 1         | 0.33%   |
| HighPoint Technologies       | 1         | 0.33%   |
| ADATA Technology             | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 27        | 7.76%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 15        | 4.31%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 13        | 3.74%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 3.74%   |
| SK hynix Non-Volatile memory controller                                          | 12        | 3.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 3.45%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 3.16%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 10        | 2.87%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 10        | 2.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 8         | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 8         | 2.3%    |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                     | 8         | 2.3%    |
| Intel SATA Controller [RAID mode]                                                | 7         | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.72%   |
| Intel SSD 660P Series                                                            | 5         | 1.44%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 5         | 1.44%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5         | 1.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 5         | 1.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 5         | 1.44%   |
| Phison E12 NVMe Controller                                                       | 4         | 1.15%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.15%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3008 [Fury]                             | 4         | 1.15%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.15%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 4         | 1.15%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 4         | 1.15%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 4         | 1.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 4         | 1.15%   |
| Broadcom / LSI SAS3008 PCI-Express Fusion-MPT SAS-3                              | 4         | 1.15%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 1.15%   |
| SK hynix Gold P31 SSD                                                            | 3         | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.86%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.86%   |
| Phison PS5013 E13 NVMe Controller                                                | 3         | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.86%   |
| Intel C600/X79 series chipset SATA RAID Controller                               | 3         | 0.86%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 3         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3         | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                           | 3         | 0.86%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.57%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 2         | 0.57%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 0.57%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 0.57%   |
| Intel NVMe Datacenter SSD [Optane]                                               | 2         | 0.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.57%   |
| Intel C600/X79 series chipset 4-Port SATA IDE Controller                         | 2         | 0.57%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 2         | 0.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 0.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 2         | 0.57%   |
| HP Smart Array Gen8 Controllers                                                  | 2         | 0.57%   |
| Broadcom / LSI MegaRAID SAS 2208 [Thunderbolt]                                   | 2         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 133       | 44.33%  |
| NVMe | 111       | 37%     |
| RAID | 39        | 13%     |
| SAS  | 10        | 3.33%   |
| IDE  | 7         | 2.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 202       | 90.99%  |
| AMD    | 19        | 8.56%   |
| ARM    | 1         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10850H CPU @ 2.70GHz            | 10        | 4.5%    |
| Intel Core i7-8665U CPU @ 1.90GHz             | 9         | 4.05%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 9         | 4.05%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 5         | 2.25%   |
| Intel Xeon CPU E3-1220 v5 @ 3.00GHz           | 4         | 1.8%    |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 1.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.8%    |
| Intel Xeon CPU E5-2680 v3 @ 2.50GHz           | 3         | 1.35%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.35%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.35%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.35%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 1.35%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 2         | 0.9%    |
| Intel Xeon CPU E5620 @ 2.40GHz                | 2         | 0.9%    |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz           | 2         | 0.9%    |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz           | 2         | 0.9%    |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 2         | 0.9%    |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 2         | 0.9%    |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz           | 2         | 0.9%    |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 2         | 0.9%    |
| Intel Core i7-9850H CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.9%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.9%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.9%    |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.9%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| Intel Xeon W-11955M CPU @ 2.60GHz             | 1         | 0.45%   |
| Intel Xeon W-10855M CPU @ 2.80GHz             | 1         | 0.45%   |
| Intel Xeon Silver 4310 CPU @ 2.10GHz          | 1         | 0.45%   |
| Intel Xeon Gold 6263CY CPU @ 2.60GHz          | 1         | 0.45%   |
| Intel Xeon Gold 6140 CPU @ 2.30GHz            | 1         | 0.45%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.45%   |
| Intel Xeon CPU E5472 @ 3.00GHz                | 1         | 0.45%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz            | 1         | 0.45%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz            | 1         | 0.45%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2640 v4 @ 2.40GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-2407 0 @ 2.20GHz            | 1         | 0.45%   |
| Intel Xeon CPU E5-1650 v4 @ 3.60GHz           | 1         | 0.45%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 87        | 39.19%  |
| Intel Core i5      | 43        | 19.37%  |
| Intel Xeon         | 41        | 18.47%  |
| Intel Core i3      | 11        | 4.95%   |
| Other              | 8         | 3.6%    |
| AMD Ryzen 7        | 7         | 3.15%   |
| Intel Xeon Silver  | 3         | 1.35%   |
| AMD Ryzen 9        | 3         | 1.35%   |
| Intel Xeon Gold    | 2         | 0.9%    |
| Intel Pentium Gold | 2         | 0.9%    |
| Intel Pentium      | 2         | 0.9%    |
| Intel Core i9      | 2         | 0.9%    |
| AMD Ryzen 5        | 2         | 0.9%    |
| AMD Ryzen 3        | 2         | 0.9%    |
| AMD EPYC           | 2         | 0.9%    |
| Intel Core 2 Duo   | 1         | 0.45%   |
| Intel Celeron      | 1         | 0.45%   |
| AMD Ryzen 7 PRO    | 1         | 0.45%   |
| AMD FX             | 1         | 0.45%   |
| AMD A4             | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 95        | 42.79%  |
| 2      | 45        | 20.27%  |
| 6      | 32        | 14.41%  |
| 8      | 21        | 9.46%   |
| 12     | 10        | 4.5%    |
| 16     | 7         | 3.15%   |
| 20     | 4         | 1.8%    |
| 36     | 2         | 0.9%    |
| 24     | 2         | 0.9%    |
| 96     | 1         | 0.45%   |
| 64     | 1         | 0.45%   |
| 48     | 1         | 0.45%   |
| 32     | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 195       | 87.84%  |
| 2      | 27        | 12.16%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 186       | 83.41%  |
| 1      | 37        | 16.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 214       | 95.54%  |
| Unknown        | 10        | 4.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806ec    | 32        | 14.29%  |
| 0x906ea    | 15        | 6.7%    |
| 0x306c3    | 14        | 6.25%   |
| 0x806ea    | 13        | 5.8%    |
| Unknown    | 13        | 5.8%    |
| 0x306a9    | 12        | 5.36%   |
| 0xa0652    | 11        | 4.91%   |
| 0x506e3    | 10        | 4.46%   |
| 0x306f2    | 10        | 4.46%   |
| 0x206a7    | 9         | 4.02%   |
| 0x406e3    | 7         | 3.13%   |
| 0x906ed    | 6         | 2.68%   |
| 0x906e9    | 6         | 2.68%   |
| 0x806e9    | 5         | 2.23%   |
| 0x806d1    | 5         | 2.23%   |
| 0x406f1    | 5         | 2.23%   |
| 0x306e4    | 4         | 1.79%   |
| 0x206d7    | 4         | 1.79%   |
| 0x306d4    | 3         | 1.34%   |
| 0x206c2    | 3         | 1.34%   |
| 0x20655    | 3         | 1.34%   |
| 0x08600103 | 3         | 1.34%   |
| 0x08108102 | 3         | 1.34%   |
| 0x806c1    | 2         | 0.89%   |
| 0x40651    | 2         | 0.89%   |
| 0x08701021 | 2         | 0.89%   |
| 0xa0660    | 1         | 0.45%   |
| 0xa0655    | 1         | 0.45%   |
| 0x906eb    | 1         | 0.45%   |
| 0x906c0    | 1         | 0.45%   |
| 0x90672    | 1         | 0.45%   |
| 0x606a6    | 1         | 0.45%   |
| 0x50657    | 1         | 0.45%   |
| 0x50654    | 1         | 0.45%   |
| 0x20652    | 1         | 0.45%   |
| 0x1067a    | 1         | 0.45%   |
| 0x10676    | 1         | 0.45%   |
| 0x0a50000c | 1         | 0.45%   |
| 0x0a001119 | 1         | 0.45%   |
| 0x08701013 | 1         | 0.45%   |
| 0x08600106 | 1         | 0.45%   |
| 0x08600104 | 1         | 0.45%   |
| 0x08301034 | 1         | 0.45%   |
| 0x0810100b | 1         | 0.45%   |
| 0x08001138 | 1         | 0.45%   |
| 0x08001137 | 1         | 0.45%   |
| 0x06006705 | 1         | 0.45%   |
| 0x06000852 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 79        | 35.43%  |
| Haswell          | 28        | 12.56%  |
| Skylake          | 25        | 11.21%  |
| IvyBridge        | 17        | 7.62%   |
| SandyBridge      | 13        | 5.83%   |
| CometLake        | 13        | 5.83%   |
| Zen 2            | 9         | 4.04%   |
| Broadwell        | 8         | 3.59%   |
| Westmere         | 7         | 3.14%   |
| Icelake          | 5         | 2.24%   |
| Unknown          | 4         | 1.79%   |
| Zen+             | 3         | 1.35%   |
| Zen              | 3         | 1.35%   |
| TigerLake        | 2         | 0.9%    |
| Penryn           | 2         | 0.9%    |
| Zen 3            | 1         | 0.45%   |
| Tremont          | 1         | 0.45%   |
| Piledriver       | 1         | 0.45%   |
| Excavator        | 1         | 0.45%   |
| Alderlake Hybrid | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 134       | 49.81%  |
| Nvidia                     | 76        | 28.25%  |
| AMD                        | 30        | 11.15%  |
| Matrox Electronics Systems | 20        | 7.43%   |
| ASPEED Technology          | 9         | 3.35%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 17        | 6.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 15        | 5.51%   |
| Intel UHD Graphics 620                                                        | 13        | 4.78%   |
| Matrox Electronics Systems G200eR2                                            | 12        | 4.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 10        | 3.68%   |
| ASPEED Technology ASPEED Graphics Family                                      | 9         | 3.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 2.57%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 2.57%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 2.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 5         | 1.84%   |
| Intel HD Graphics 530                                                         | 5         | 1.84%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 5         | 1.84%   |
| AMD Renoir                                                                    | 5         | 1.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.47%   |
| Intel HD Graphics 630                                                         | 4         | 1.47%   |
| Intel HD Graphics 620                                                         | 4         | 1.47%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                         | 3         | 1.1%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 3         | 1.1%    |
| Matrox Electronics Systems MGA G200EH                                         | 3         | 1.1%    |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller      | 3         | 1.1%    |
| Intel HD Graphics 5500                                                        | 3         | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                           | 3         | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller     | 3         | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.1%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 0.74%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                         | 2         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 0.74%   |
| Nvidia GP107GLM [Quadro P620]                                                 | 2         | 0.74%   |
| Nvidia GP106GL [Quadro P2200]                                                 | 2         | 0.74%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 2         | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 2         | 0.74%   |
| Nvidia GM107GLM [Quadro M2000M]                                               | 2         | 0.74%   |
| Nvidia GM107GLM [Quadro M1000M]                                               | 2         | 0.74%   |
| Nvidia GK208B [GeForce GT 730]                                                | 2         | 0.74%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 2         | 0.74%   |
| Nvidia GF108GL [Quadro 600]                                                   | 2         | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 0.74%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)             | 2         | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 2         | 0.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 2         | 0.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                        | 2         | 0.74%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 2         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                    | 2         | 0.74%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 2         | 0.74%   |
| Nvidia TU117M [GeForce MX450]                                                 | 1         | 0.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.37%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                 | 1         | 0.37%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 1         | 0.37%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 1         | 0.37%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                         | 1         | 0.37%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 1         | 0.37%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                              | 1         | 0.37%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                         | 1         | 0.37%   |
| Nvidia GT218 [GeForce G210]                                                   | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX250]                                                 | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 0.37%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                    | 1         | 0.37%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                         | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 93        | 41.52%  |
| 1 x Nvidia              | 42        | 18.75%  |
| Intel + Nvidia          | 27        | 12.05%  |
| 1 x Matrox              | 19        | 8.48%   |
| 1 x AMD                 | 16        | 7.14%   |
| Intel + AMD             | 9         | 4.02%   |
| 1 x ASPEED              | 6         | 2.68%   |
| AMD + Nvidia            | 3         | 1.34%   |
| Other                   | 2         | 0.89%   |
| 2 x Nvidia              | 2         | 0.89%   |
| 2 x Nvidia + 1 x ASPEED | 1         | 0.45%   |
| 2 x AMD                 | 1         | 0.45%   |
| Nvidia + Matrox         | 1         | 0.45%   |
| Nvidia + ASPEED         | 1         | 0.45%   |
| AMD + ASPEED            | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 76.44%  |
| Proprietary | 32        | 14.22%  |
| Unknown     | 21        | 9.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 62.72%  |
| 1.01-2.0   | 24        | 10.53%  |
| 3.01-4.0   | 16        | 7.02%   |
| 0.51-1.0   | 12        | 5.26%   |
| 0.01-0.5   | 9         | 3.95%   |
| 7.01-8.0   | 8         | 3.51%   |
| 5.01-6.0   | 8         | 3.51%   |
| 2.01-3.0   | 3         | 1.32%   |
| 4.01-5.0   | 2         | 0.88%   |
| 8.01-16.0  | 2         | 0.88%   |
| 16.01-24.0 | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 32        | 12.5%   |
| AU Optronics            | 29        | 11.33%  |
| Samsung Electronics     | 26        | 10.16%  |
| BOE                     | 23        | 8.98%   |
| Lenovo                  | 22        | 8.59%   |
| LG Display              | 19        | 7.42%   |
| Chimei Innolux          | 17        | 6.64%   |
| Goldstar                | 16        | 6.25%   |
| Hewlett-Packard         | 11        | 4.3%    |
| Sharp                   | 8         | 3.13%   |
| InfoVision              | 5         | 1.95%   |
| Acer                    | 5         | 1.95%   |
| Philips                 | 4         | 1.56%   |
| Eizo                    | 4         | 1.56%   |
| BenQ                    | 4         | 1.56%   |
| Ancor Communications    | 3         | 1.17%   |
| ViewSonic               | 2         | 0.78%   |
| PANDA                   | 2         | 0.78%   |
| LGD                     | 2         | 0.78%   |
| Lenovo Group Limited    | 2         | 0.78%   |
| Iiyama                  | 2         | 0.78%   |
| Gigabyte Technology     | 2         | 0.78%   |
| BOE Technology Group    | 2         | 0.78%   |
| AOC                     | 2         | 0.78%   |
| Sun                     | 1         | 0.39%   |
| STD                     | 1         | 0.39%   |
| Sceptre Tech            | 1         | 0.39%   |
| Planar                  | 1         | 0.39%   |
| OUT                     | 1         | 0.39%   |
| LG Electronics          | 1         | 0.39%   |
| ITE                     | 1         | 0.39%   |
| Insignia                | 1         | 0.39%   |
| EVE                     | 1         | 0.39%   |
| Chi Mei Optoelectronics | 1         | 0.39%   |
| ASUSTek Computer        | 1         | 0.39%   |
| Unknown                 | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell IDRAC DEL0001 1280x1024                                          | 6         | 2.17%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 6         | 2.17%   |
| Lenovo LEN P27u-10 LEN61B0 3840x2160 600x340mm 27.2-inch              | 5         | 1.81%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 1.81%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 5         | 1.81%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 1.44%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch     | 3         | 1.08%   |
| LG Display LCD Monitor LGD0676 1920x1080 309x174mm 14.0-inch          | 3         | 1.08%   |
| Lenovo TIO24Gen3 LEN10B4 1920x1080 527x296mm 23.8-inch                | 3         | 1.08%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3         | 1.08%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 3         | 1.08%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 3         | 1.08%   |
| BOE LCD Monitor BOE086E 1920x1080 344x194mm 15.5-inch                 | 3         | 1.08%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 3         | 1.08%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 3         | 1.08%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.72%   |
| Sharp LCD Monitor SHP1430 3840x2160 350x190mm 15.7-inch               | 2         | 0.72%   |
| Philips PHL 272E1 PHLC210 1920x1080 598x336mm 27.0-inch               | 2         | 0.72%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.72%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.72%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.72%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch              | 2         | 0.72%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 2         | 0.72%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 2         | 0.72%   |
| Iiyama PL4840 IVM1065 1920x1080 1054x593mm 47.6-inch                  | 2         | 0.72%   |
| Hewlett-Packard 27yh HPN351C 1920x1080 600x340mm 27.2-inch            | 2         | 0.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch      | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO562D 1920x1080 293x165mm 13.2-inch        | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch         | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.72%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 1         | 0.36%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.36%   |
| Sun Monitor SUN059A 1920x1200 518x324mm 24.1-inch                     | 1         | 0.36%   |
| STD LED STD0110 1366x768 410x230mm 18.5-inch                          | 1         | 0.36%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch               | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.36%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.36%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch               | 1         | 0.36%   |
| Sceptre Tech Sceptre L24 SPT098C 1920x1080 530x300mm 24.0-inch        | 1         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.36%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch     | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 518x324mm 24.1-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0566 1440x900 408x255mm 18.9-inch   | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0526 1920x1080 510x287mm 23.0-inch  | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0370 1680x1050 459x296mm 21.5-inch  | 1         | 0.36%   |
| Samsung Electronics S24E450 SAM0C9B 1920x1080 521x293mm 23.5-inch     | 1         | 0.36%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.36%   |
| Samsung Electronics S22E390 SAM0C18 1920x1080 477x268mm 21.5-inch     | 1         | 0.36%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 440x250mm 19.9-inch      | 1         | 0.36%   |
| Samsung Electronics LS27R75 SAM0FAC 2560x1440 598x336mm 27.0-inch     | 1         | 0.36%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4143 3840x2160 344x194mm 15.5-inch | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 121       | 52.61%  |
| 3840x2160 (4K)     | 20        | 8.7%    |
| 1366x768 (WXGA)    | 18        | 7.83%   |
| 2560x1440 (QHD)    | 14        | 6.09%   |
| 1600x900 (HD+)     | 11        | 4.78%   |
| 1920x1200 (WUXGA)  | 7         | 3.04%   |
| 1280x1024 (SXGA)   | 7         | 3.04%   |
| 2560x1080          | 6         | 2.61%   |
| Unknown            | 5         | 2.17%   |
| 3840x1080          | 4         | 1.74%   |
| 3440x1440          | 4         | 1.74%   |
| 1680x1050 (WSXGA+) | 3         | 1.3%    |
| 1440x900 (WXGA+)   | 2         | 0.87%   |
| 9600x2160          | 1         | 0.43%   |
| 7680x2160          | 1         | 0.43%   |
| 6400x2160          | 1         | 0.43%   |
| 3840x1200          | 1         | 0.43%   |
| 2048x1152          | 1         | 0.43%   |
| 1280x800 (WXGA)    | 1         | 0.43%   |
| 1280x768           | 1         | 0.43%   |
| 1280x720 (HD)      | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 18.6%   |
| 14      | 33        | 12.79%  |
| 24      | 27        | 10.47%  |
| 27      | 25        | 9.69%   |
| 13      | 24        | 9.3%    |
| 23      | 21        | 8.14%   |
| Unknown | 20        | 7.75%   |
| 21      | 11        | 4.26%   |
| 34      | 7         | 2.71%   |
| 31      | 6         | 2.33%   |
| 12      | 5         | 1.94%   |
| 20      | 4         | 1.55%   |
| 17      | 4         | 1.55%   |
| 54      | 3         | 1.16%   |
| 18      | 3         | 1.16%   |
| 47      | 2         | 0.78%   |
| 32      | 2         | 0.78%   |
| 22      | 2         | 0.78%   |
| 19      | 2         | 0.78%   |
| 72      | 1         | 0.39%   |
| 64      | 1         | 0.39%   |
| 49      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 39      | 1         | 0.39%   |
| 28      | 1         | 0.39%   |
| 25      | 1         | 0.39%   |
| 16      | 1         | 0.39%   |
| 11      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 39.76%  |
| 501-600     | 63        | 25.3%   |
| 401-500     | 20        | 8.03%   |
| Unknown     | 20        | 8.03%   |
| 201-300     | 13        | 5.22%   |
| 601-700     | 10        | 4.02%   |
| 701-800     | 9         | 3.61%   |
| 1001-1500   | 7         | 2.81%   |
| 351-400     | 5         | 2.01%   |
| 801-900     | 2         | 0.8%    |
| 1501-2000   | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 161       | 77.4%   |
| 16/10   | 17        | 8.17%   |
| Unknown | 12        | 5.77%   |
| 21/9    | 8         | 3.85%   |
| 5/4     | 7         | 3.37%   |
| 4/3     | 1         | 0.48%   |
| 32/9    | 1         | 0.48%   |
| 3/2     | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 50        | 19.76%  |
| 101-110        | 48        | 18.97%  |
| 201-250        | 46        | 18.18%  |
| 301-350        | 25        | 9.88%   |
| Unknown        | 20        | 7.91%   |
| 351-500        | 14        | 5.53%   |
| 251-300        | 13        | 5.14%   |
| 71-80          | 7         | 2.77%   |
| 151-200        | 7         | 2.77%   |
| More than 1000 | 5         | 1.98%   |
| 61-70          | 5         | 1.98%   |
| 501-1000       | 5         | 1.98%   |
| 121-130        | 4         | 1.58%   |
| 141-150        | 2         | 0.79%   |
| 51-60          | 1         | 0.4%    |
| 131-140        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 91        | 36.99%  |
| 51-100        | 76        | 30.89%  |
| 101-120       | 34        | 13.82%  |
| Unknown       | 20        | 8.13%   |
| 161-240       | 14        | 5.69%   |
| More than 240 | 6         | 2.44%   |
| 1-50          | 5         | 2.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 60.52%  |
| 2     | 50        | 21.46%  |
| 0     | 27        | 11.59%  |
| 3     | 14        | 6.01%   |
| 4     | 1         | 0.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 173       | 52.58%  |
| Realtek Semiconductor             | 67        | 20.36%  |
| Broadcom                          | 19        | 5.78%   |
| Lenovo                            | 16        | 4.86%   |
| Qualcomm Atheros                  | 12        | 3.65%   |
| Dell                              | 5         | 1.52%   |
| Broadcom Limited                  | 5         | 1.52%   |
| Sierra Wireless                   | 2         | 0.61%   |
| Ralink Technology                 | 2         | 0.61%   |
| Ralink                            | 2         | 0.61%   |
| MediaTek                          | 2         | 0.61%   |
| Marvell Technology Group          | 2         | 0.61%   |
| Huawei Technologies               | 2         | 0.61%   |
| Ericsson Business Mobile Networks | 2         | 0.61%   |
| ASIX Electronics                  | 2         | 0.61%   |
| Xiaomi                            | 1         | 0.3%    |
| Samsung Electronics               | 1         | 0.3%    |
| Qualcomm Atheros Communications   | 1         | 0.3%    |
| QLogic                            | 1         | 0.3%    |
| Prolific Technology               | 1         | 0.3%    |
| Microchip Technology              | 1         | 0.3%    |
| Micro Star International          | 1         | 0.3%    |
| Mellanox Technologies             | 1         | 0.3%    |
| Luminary Micro                    | 1         | 0.3%    |
| ICS Advent                        | 1         | 0.3%    |
| IBM                               | 1         | 0.3%    |
| Emulex                            | 1         | 0.3%    |
| DisplayLink                       | 1         | 0.3%    |
| D-Link                            | 1         | 0.3%    |
| Arduino SA                        | 1         | 0.3%    |
| Aquantia                          | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 42        | 9.48%   |
| Intel Wireless 8265 / 8275                                                     | 17        | 3.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 16        | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 3.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 15        | 3.39%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 11        | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 2.26%   |
| Intel Wireless 8260                                                            | 10        | 2.26%   |
| Intel Wi-Fi 6 AX200                                                            | 10        | 2.26%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 2.26%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 2.26%   |
| Intel I350 Gigabit Network Connection                                          | 9         | 2.03%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 9         | 2.03%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 1.81%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 1.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 1.58%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.58%   |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 1.58%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 6         | 1.35%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 1.35%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.13%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.13%   |
| Intel 82574L Gigabit Network Connection                                        | 5         | 1.13%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 0.9%    |
| Intel Wireless-AC 9260                                                         | 4         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.9%    |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 0.9%    |
| Intel Centrino Ultimate-N 6300                                                 | 4         | 0.9%    |
| Intel Wireless 7265                                                            | 3         | 0.68%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.68%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.68%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.68%   |
| Dell iDRAC Virtual NIC                                                         | 3         | 0.68%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                             | 3         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.45%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.45%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.45%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.45%   |
| Intel Wireless 7260                                                            | 2         | 0.45%   |
| Intel Wireless 3165                                                            | 2         | 0.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 2         | 0.45%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.45%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.45%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.45%   |
| Intel Ethernet Controller X550                                                 | 2         | 0.45%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.45%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.45%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.45%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 121       | 73.33%  |
| Realtek Semiconductor             | 13        | 7.88%   |
| Qualcomm Atheros                  | 11        | 6.67%   |
| Broadcom                          | 5         | 3.03%   |
| Sierra Wireless                   | 2         | 1.21%   |
| Ralink Technology                 | 2         | 1.21%   |
| Ralink                            | 2         | 1.21%   |
| MediaTek                          | 2         | 1.21%   |
| Dell                              | 2         | 1.21%   |
| Qualcomm Atheros Communications   | 1         | 0.61%   |
| Micro Star International          | 1         | 0.61%   |
| Ericsson Business Mobile Networks | 1         | 0.61%   |
| D-Link                            | 1         | 0.61%   |
| Broadcom Limited                  | 1         | 0.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                 | 17        | 10.3%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                          | 16        | 9.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 15        | 9.09%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 11        | 6.67%   |
| Intel Wireless 8260                                                        | 10        | 6.06%   |
| Intel Wi-Fi 6 AX200                                                        | 10        | 6.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 9         | 5.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 6         | 3.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 2.42%   |
| Intel Wireless-AC 9260                                                     | 4         | 2.42%   |
| Intel Centrino Ultimate-N 6300                                             | 4         | 2.42%   |
| Intel Wireless 7265                                                        | 3         | 1.82%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                         | 3         | 1.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 2         | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 1.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 2         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.21%   |
| Intel Wireless 7260                                                        | 2         | 1.21%   |
| Intel Wireless 3165                                                        | 2         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                     | 2         | 1.21%   |
| Intel Wi-Fi 6 AX201                                                        | 2         | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2         | 1.21%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 2         | 1.21%   |
| Sierra Wireless EM7455                                                     | 1         | 0.61%   |
| Sierra Wireless AirPrime MC7455 3G/4G LTE Modem                            | 1         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 1         | 0.61%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1         | 0.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 1         | 0.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                            | 1         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1         | 0.61%   |
| Ralink RT5572 Wireless Adapter                                             | 1         | 0.61%   |
| Ralink RT5372 Wireless Adapter                                             | 1         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 0.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 1         | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 1         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 1         | 0.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 0.61%   |
| Micro Star International MS-3871 802.11bgn Wireless Module [Ralink RT8070] | 1         | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1         | 0.61%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                         | 1         | 0.61%   |
| Intel Wireless 3160                                                        | 1         | 0.61%   |
| Intel Wi-Fi 6 AX201 160MHz                                                 | 1         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 1         | 0.61%   |
| Intel Centrino Wireless-N 2230                                             | 1         | 0.61%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 0.61%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 1         | 0.61%   |
| Ericsson Business Mobile Networks N5321 gw                                 | 1         | 0.61%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1         | 0.61%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 0.61%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                         | 1         | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 134       | 55.14%  |
| Realtek Semiconductor    | 59        | 24.28%  |
| Lenovo                   | 16        | 6.58%   |
| Broadcom                 | 14        | 5.76%   |
| Broadcom Limited         | 4         | 1.65%   |
| Qualcomm Atheros         | 2         | 0.82%   |
| Marvell Technology Group | 2         | 0.82%   |
| ASIX Electronics         | 2         | 0.82%   |
| Xiaomi                   | 1         | 0.41%   |
| Samsung Electronics      | 1         | 0.41%   |
| QLogic                   | 1         | 0.41%   |
| Mellanox Technologies    | 1         | 0.41%   |
| ICS Advent               | 1         | 0.41%   |
| IBM                      | 1         | 0.41%   |
| Huawei Technologies      | 1         | 0.41%   |
| Emulex                   | 1         | 0.41%   |
| DisplayLink              | 1         | 0.41%   |
| Aquantia                 | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 42        | 15.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 5.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 3.72%   |
| Intel Ethernet Connection (6) I219-LM                                          | 10        | 3.72%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 3.72%   |
| Intel I350 Gigabit Network Connection                                          | 9         | 3.35%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 3.35%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 8         | 2.97%   |
| Intel Ethernet Connection (10) I219-LM                                         | 8         | 2.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 2.6%    |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.6%    |
| Intel Ethernet Connection (2) I219-LM                                          | 7         | 2.6%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 7         | 2.6%    |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 6         | 2.23%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.86%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.86%   |
| Intel 82574L Gigabit Network Connection                                        | 5         | 1.86%   |
| Broadcom NetXtreme II BCM57810 10 Gigabit Ethernet                             | 5         | 1.86%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 1.49%   |
| Intel Ethernet Connection (10) I219-V                                          | 4         | 1.49%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.12%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.12%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 1.12%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.12%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.74%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.74%   |
| Lenovo USB-C to LAN                                                            | 2         | 0.74%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.74%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.74%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.74%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                                  | 2         | 0.74%   |
| Intel Ethernet Controller X550                                                 | 2         | 0.74%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.74%   |
| Intel Ethernet Controller I225-LM                                              | 2         | 0.74%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.74%   |
| Intel Ethernet Connection (2) I218-LM                                          | 2         | 0.74%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.74%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.74%   |
| Intel 82599 10 Gigabit Network Connection                                      | 2         | 0.74%   |
| Intel 82599 10 Gigabit Dual Port Backplane Connection                          | 2         | 0.74%   |
| Intel 82576 Gigabit Network Connection                                         | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.37%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.37%   |
| QLogic cLOM8214 1/10GbE Controller                                             | 1         | 0.37%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                        | 1         | 0.37%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.37%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.37%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                               | 1         | 0.37%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.37%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.37%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.37%   |
| Intel DH8900CC Series Gigabit Network Connection                               | 1         | 0.37%   |
| Intel DH8900CC Series Gigabit Backplane Network Connection                     | 1         | 0.37%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 204       | 54.99%  |
| WiFi     | 158       | 42.59%  |
| Modem    | 6         | 1.62%   |
| Unknown  | 3         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 127       | 54.04%  |
| WiFi     | 107       | 45.53%  |
| Unknown  | 1         | 0.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 127       | 56.95%  |
| 1     | 60        | 26.91%  |
| 3     | 12        | 5.38%   |
| 4     | 11        | 4.93%   |
| 6     | 7         | 3.14%   |
| 132   | 1         | 0.45%   |
| 22    | 1         | 0.45%   |
| 12    | 1         | 0.45%   |
| 8     | 1         | 0.45%   |
| 5     | 1         | 0.45%   |
| 0     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 202       | 90.18%  |
| Yes  | 22        | 9.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 73.08%  |
| Cambridge Silicon Radio         | 9         | 6.92%   |
| Broadcom                        | 6         | 4.62%   |
| Realtek Semiconductor           | 4         | 3.08%   |
| Qualcomm Atheros Communications | 4         | 3.08%   |
| IMC Networks                    | 4         | 3.08%   |
| ASUSTek Computer                | 3         | 2.31%   |
| Foxconn / Hon Hai               | 2         | 1.54%   |
| Ralink                          | 1         | 0.77%   |
| Micro Star International        | 1         | 0.77%   |
| Dell                            | 1         | 0.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 30        | 23.08%  |
| Intel Bluetooth wireless interface                                                  | 28        | 21.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 16.15%  |
| Intel AX200 Bluetooth                                                               | 9         | 6.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 6.92%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.31%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.31%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 2.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.54%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.54%   |
| ASUS BCM20702A0                                                                     | 2         | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.77%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.77%   |
| Micro Star International Bluetooth Device                                           | 1         | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.77%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.77%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.77%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.77%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.77%   |
| Broadcom BCM20702A0 Bluetooth                                                       | 1         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.77%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.77%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 170       | 53.46%  |
| Nvidia                                       | 57        | 17.92%  |
| AMD                                          | 27        | 8.49%   |
| Lenovo                                       | 16        | 5.03%   |
| Texas Instruments                            | 5         | 1.57%   |
| Realtek Semiconductor                        | 5         | 1.57%   |
| Plantronics                                  | 4         | 1.26%   |
| JMTek                                        | 4         | 1.26%   |
| Creative Labs                                | 4         | 1.26%   |
| GN Netcom                                    | 3         | 0.94%   |
| Generalplus Technology                       | 3         | 0.94%   |
| Creative Technology                          | 3         | 0.94%   |
| Sennheiser Communications                    | 2         | 0.63%   |
| Logitech                                     | 2         | 0.63%   |
| C-Media Electronics                          | 2         | 0.63%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.31%   |
| Tenx Technology                              | 1         | 0.31%   |
| Sony                                         | 1         | 0.31%   |
| RODE Microphones                             | 1         | 0.31%   |
| LG Electronics                               | 1         | 0.31%   |
| Google                                       | 1         | 0.31%   |
| Focusrite-Novation                           | 1         | 0.31%   |
| Dynex                                        | 1         | 0.31%   |
| Dell                                         | 1         | 0.31%   |
| Corsair                                      | 1         | 0.31%   |
| ASUSTek Computer                             | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 25        | 7.29%   |
| Intel Cannon Lake PCH cAVS                                                        | 19        | 5.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 18        | 5.25%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 16        | 4.66%   |
| Intel Comet Lake PCH cAVS                                                         | 12        | 3.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 12        | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 11        | 3.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 11        | 3.21%   |
| AMD Family 17h/19h HD Audio Controller                                            | 10        | 2.92%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 9         | 2.62%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                      | 8         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 8         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 7         | 2.04%   |
| Nvidia GF108 High Definition Audio Controller                                     | 6         | 1.75%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 6         | 1.75%   |
| Realtek Semiconductor USB Audio                                                   | 5         | 1.46%   |
| Nvidia GP106 High Definition Audio Controller                                     | 5         | 1.46%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 5         | 1.46%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 5         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 5         | 1.46%   |
| Texas Instruments PCM2902 Audio Codec                                             | 4         | 1.17%   |
| Plantronics BT600                                                                 | 4         | 1.17%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 1.17%   |
| Lenovo Thinkcentre TIO24Gen3 for USB-audio                                        | 4         | 1.17%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4         | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 4         | 1.17%   |
| Nvidia GP104 High Definition Audio Controller                                     | 3         | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 3         | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 3         | 0.87%   |
| Intel CM238 HD Audio Controller                                                   | 3         | 0.87%   |
| Intel Broadwell-U Audio Controller                                                | 3         | 0.87%   |
| Intel 200 Series PCH HD Audio                                                     | 3         | 0.87%   |
| AMD Starship/Matisse HD Audio Controller                                          | 3         | 0.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 3         | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.87%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2         | 0.58%   |
| Nvidia GA106 High Definition Audio Controller                                     | 2         | 0.58%   |
| Nvidia Audio device                                                               | 2         | 0.58%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                          | 2         | 0.58%   |
| JMTek USB PnP Audio Device                                                        | 2         | 0.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 2         | 0.58%   |
| Intel Haswell-ULT HD Audio Controller                                             | 2         | 0.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 2         | 0.58%   |
| Intel 8 Series HD Audio Controller                                                | 2         | 0.58%   |
| Generalplus Technology USB Audio Device                                           | 2         | 0.58%   |
| Creative Technology Sound BlasterX G1                                             | 2         | 0.58%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]                     | 2         | 0.58%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 2         | 0.58%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                    | 1         | 0.29%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                 | 1         | 0.29%   |
| Tenx Technology USB AUDIO                                                         | 1         | 0.29%   |
| Sony DualSense wireless controller (PS5)                                          | 1         | 0.29%   |
| Sennheiser Communications Headset [PC 8]                                          | 1         | 0.29%   |
| Sennheiser Communications EPOS ADAPT 1x5T                                         | 1         | 0.29%   |
| RODE Microphones RODE NT-USB                                                      | 1         | 0.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1         | 0.29%   |
| Nvidia TU104 HD Audio Controller                                                  | 1         | 0.29%   |
| Nvidia High Definition Audio Controller                                           | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 31.3%   |
| SK hynix            | 33        | 28.7%   |
| Micron Technology   | 13        | 11.3%   |
| Crucial             | 9         | 7.83%   |
| Kingston            | 6         | 5.22%   |
| Unknown             | 4         | 3.48%   |
| Corsair             | 4         | 3.48%   |
| Hewlett-Packard     | 2         | 1.74%   |
| Goodram             | 2         | 1.74%   |
| Unknown (0x0205)    | 1         | 0.87%   |
| Transcend           | 1         | 0.87%   |
| Smart               | 1         | 0.87%   |
| Patriot             | 1         | 0.87%   |
| Elpida              | 1         | 0.87%   |
| Unknown             | 1         | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GU7AFR8N-UH 8192MB DIMM DDR4 2400MT/s    | 4         | 3.23%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s    | 3         | 2.42%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s      | 3         | 2.42%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s     | 3         | 2.42%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s               | 2         | 1.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 1.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 1.61%   |
| SK hynix RAM HMA82GR7MFR8N-UH 16384MB DIMM DDR4 2400MT/s   | 2         | 1.61%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s     | 2         | 1.61%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s     | 2         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 1.61%   |
| Samsung RAM M393B2G70QH0-YK0 16GB DIMM DDR3 1600MT/s       | 2         | 1.61%   |
| Samsung RAM M393A4K40DB3-CWE 32GB DIMM DDR4 3200MT/s       | 2         | 1.61%   |
| Samsung RAM M386A4G40DM0-CPB 32GB DIMM DDR4 2133MT/s       | 2         | 1.61%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s    | 2         | 1.61%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s       | 2         | 1.61%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s     | 2         | 1.61%   |
| Unknown RAM V3D4SF16GB1G81G82400 16GB SODIMM DDR4 2400MT/s | 1         | 0.81%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                | 1         | 0.81%   |
| Unknown (0x0205) RAM Module 8GB DIMM DDR3 1600MT/s         | 1         | 0.81%   |
| Transcend RAM TS1GLK72V3H 8GB DIMM DDR3 1333MT/s           | 1         | 0.81%   |
| Smart RAM SF4642G8CK8IEHLSBG 16384MB SODIMM DDR4 2667MT/s  | 1         | 0.81%   |
| SK hynix RAM Module 16GB Row Of Chips LPDDR4 2933MT/s      | 1         | 0.81%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s       | 1         | 0.81%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.81%   |
| SK hynix RAM HMT351S6EFR8C-PB 4096MB DIMM DDR3 1333MT/s    | 1         | 0.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB DIMM DDR3 1333MT/s    | 1         | 0.81%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.81%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s      | 1         | 0.81%   |
| SK hynix RAM HMAA8GL7CPR4N-VK 64GB DIMM DDR4 2666MT/s      | 1         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 1         | 0.81%   |
| SK hynix RAM HMA851U6CJR6N-VK 4GB DIMM DDR4 2667MT/s       | 1         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 1         | 0.81%   |
| SK hynix RAM HMA84GR7CJR4N-WM 32GB DIMM DDR4 2933MT/s      | 1         | 0.81%   |
| SK hynix RAM HMA82GS7MFR8N-TF 16GB SODIMM DDR4 2133MT/s    | 1         | 0.81%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s    | 1         | 0.81%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.81%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s    | 1         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.81%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1         | 0.81%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                  | 1         | 0.81%   |
| Samsung RAM Module 4GB DIMM DDR4 2133MT/s                  | 1         | 0.81%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s               | 1         | 0.81%   |
| Samsung RAM Module 16GB DIMM DDR4 2666MT/s                 | 1         | 0.81%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 1         | 0.81%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 0.81%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 1         | 0.81%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s      | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s   | 1         | 0.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 1         | 0.81%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s     | 1         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 1         | 0.81%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s      | 1         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 1         | 0.81%   |
| Samsung RAM M393B5173FHD-CF8 4096MB DIMM 1066MT/s          | 1         | 0.81%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s       | 1         | 0.81%   |
| Samsung RAM M378B5673FH0-CH9 2048MB DIMM DDR3 1600MT/s     | 1         | 0.81%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s        | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 61.22%  |
| DDR3    | 26        | 26.53%  |
| SDRAM   | 3         | 3.06%   |
| LPDDR4  | 3         | 3.06%   |
| LPDDR3  | 2         | 2.04%   |
| DRAM    | 2         | 2.04%   |
| DDR2    | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 53        | 54.64%  |
| SODIMM       | 38        | 39.18%  |
| Row Of Chips | 2         | 2.06%   |
| RIMM         | 2         | 2.06%   |
| Chip         | 2         | 2.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 34.62%  |
| 16384 | 32        | 30.77%  |
| 4096  | 22        | 21.15%  |
| 32768 | 9         | 8.65%   |
| 65536 | 2         | 1.92%   |
| 2048  | 2         | 1.92%   |
| 1024  | 1         | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 18.27%  |
| 2667    | 16        | 15.38%  |
| 2400    | 16        | 15.38%  |
| 3200    | 14        | 13.46%  |
| 2133    | 13        | 12.5%   |
| 1333    | 7         | 6.73%   |
| 2666    | 5         | 4.81%   |
| 2933    | 3         | 2.88%   |
| 3600    | 2         | 1.92%   |
| 1867    | 2         | 1.92%   |
| 3266    | 1         | 0.96%   |
| 2048    | 1         | 0.96%   |
| 1866    | 1         | 0.96%   |
| 1334    | 1         | 0.96%   |
| 1066    | 1         | 0.96%   |
| 800     | 1         | 0.96%   |
| Unknown | 1         | 0.96%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 50%     |
| Canon              | 2         | 33.33%  |
| Brother Industries | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| HP LaserJet Professional P 1102w   | 1         | 16.67%  |
| HP ENVY 4500 series                | 1         | 16.67%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 16.67%  |
| Canon E560 series                  | 1         | 16.67%  |
| Canon CanoScan LiDE 300            | 1         | 16.67%  |
| Brother DCP-1610W                  | 1         | 16.67%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 28.47%  |
| IMC Networks                           | 22        | 15.28%  |
| Acer                                   | 13        | 9.03%   |
| Realtek Semiconductor                  | 10        | 6.94%   |
| Logitech                               | 10        | 6.94%   |
| Microdia                               | 9         | 6.25%   |
| Sunplus Innovation Technology          | 7         | 4.86%   |
| Unknown                                | 5         | 3.47%   |
| Suyin                                  | 4         | 2.78%   |
| Samsung Electronics                    | 3         | 2.08%   |
| Microsoft                              | 3         | 2.08%   |
| Lite-On Technology                     | 3         | 2.08%   |
| Generalplus Technology                 | 3         | 2.08%   |
| Syntek                                 | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.39%   |
| Vimicro                                | 1         | 0.69%   |
| Ruision                                | 1         | 0.69%   |
| Quanta                                 | 1         | 0.69%   |
| LG Electronics                         | 1         | 0.69%   |
| Lenovo                                 | 1         | 0.69%   |
| Jieli Technology                       | 1         | 0.69%   |
| ARC International                      | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 22        | 14.97%  |
| IMC Networks Integrated Camera                               | 18        | 12.24%  |
| Realtek Integrated_Webcam_HD                                 | 8         | 5.44%   |
| Acer Integrated Camera                                       | 7         | 4.76%   |
| Chicony Integrated Camera (1280x720@30)                      | 5         | 3.4%    |
| Unknown FULL HD 1080P Webcam                                 | 4         | 2.72%   |
| Sunplus Integrated_Webcam_HD                                 | 4         | 2.72%   |
| Logitech HD Pro Webcam C920                                  | 4         | 2.72%   |
| Chicony HP HD Camera                                         | 4         | 2.72%   |
| Acer SunplusIT Integrated Camera                             | 4         | 2.72%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 3         | 2.04%   |
| Microdia Integrated_Webcam_HD                                | 3         | 2.04%   |
| Lite-On Integrated Camera                                    | 3         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 2.04%   |
| Generalplus GENERAL WEBCAM                                   | 3         | 2.04%   |
| Chicony ThinkPad T490 Webcam                                 | 3         | 2.04%   |
| Suyin Integrated_Webcam_HD                                   | 2         | 1.36%   |
| Microdia Webcam                                              | 2         | 1.36%   |
| Microdia Integrated Webcam                                   | 2         | 1.36%   |
| Chicony Integrated Camera [ThinkPad]                         | 2         | 1.36%   |
| Acer Integrated IR Camera                                    | 2         | 1.36%   |
| Vimicro Integrated Camera                                    | 1         | 0.68%   |
| Unknown 720p HD Camera                                       | 1         | 0.68%   |
| Syntek Lenovo EasyCamera                                     | 1         | 0.68%   |
| Syntek Integrated Camera                                     | 1         | 0.68%   |
| Suyin USB2.0 RGBIR Camera                                    | 1         | 0.68%   |
| Suyin HP Truevision HD                                       | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.68%   |
| Sunplus Integrated Webcam                                    | 1         | 0.68%   |
| Sunplus HP HD Webcam [Fixed]                                 | 1         | 0.68%   |
| Ruision UVC Camera                                           | 1         | 0.68%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.68%   |
| Realtek NexiGo N660P FHD Webcam                              | 1         | 0.68%   |
| Quanta HP HD Camera                                          | 1         | 0.68%   |
| Microsoft LifeCam VX-2000                                    | 1         | 0.68%   |
| Microsoft LifeCam HD-3000                                    | 1         | 0.68%   |
| Microsoft LifeCam Cinema                                     | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 1         | 0.68%   |
| Microdia Laptop_Integrated_Webcam_E4HD                       | 1         | 0.68%   |
| Logitech Webcam C925e                                        | 1         | 0.68%   |
| Logitech Webcam C310                                         | 1         | 0.68%   |
| Logitech Webcam C270                                         | 1         | 0.68%   |
| Logitech Webcam C250                                         | 1         | 0.68%   |
| Logitech HD Webcam C910                                      | 1         | 0.68%   |
| Logitech B525 HD Webcam                                      | 1         | 0.68%   |
| LG LG UltraFine Display Camera                               | 1         | 0.68%   |
| Lenovo Integrated Webcam                                     | 1         | 0.68%   |
| Jieli USB PHY 2.0                                            | 1         | 0.68%   |
| IMC Networks XHC Camera                                      | 1         | 0.68%   |
| Chicony TOSHIBA Web Camera - HD                              | 1         | 0.68%   |
| Chicony Lenovo Integrated Camera (0.3MP)                     | 1         | 0.68%   |
| Chicony Integrated IR Camera                                 | 1         | 0.68%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 0.68%   |
| Chicony HP Webcam                                            | 1         | 0.68%   |
| Chicony HD User Facing                                       | 1         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 1         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 0.68%   |
| ARC International Camera                                     | 1         | 0.68%   |
| Acer ThinkPad P50 Integrated Camera                          | 1         | 0.68%   |
| Acer LENOVO LBG 1080P CAM                                    | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 32        | 56.14%  |
| Validity Sensors           | 16        | 28.07%  |
| Shenzhen Goodix Technology | 5         | 8.77%   |
| Upek                       | 2         | 3.51%   |
| Samsung Electronics        | 1         | 1.75%   |
| Elan Microelectronics      | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 22        | 38.6%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 12.28%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 7.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 5.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.51%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.51%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 1.75%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.75%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.75%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 42.86%  |
| Alcor Micro           | 5         | 23.81%  |
| Lenovo                | 2         | 9.52%   |
| Yubico.com            | 1         | 4.76%   |
| Upek                  | 1         | 4.76%   |
| SCM Microsystems      | 1         | 4.76%   |
| OmniKey               | 1         | 4.76%   |
| Gemalto (was Gemplus) | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 23.81%  |
| Broadcom 5880                                              | 4         | 19.05%  |
| Broadcom 58200                                             | 3         | 14.29%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 9.52%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 4.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 4.76%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader     | 1         | 4.76%   |
| OmniKey CardMan 3121 (HID Technologies)                    | 1         | 4.76%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader          | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 107       | 47.35%  |
| 1     | 80        | 35.4%   |
| 2     | 24        | 10.62%  |
| 3     | 10        | 4.42%   |
| 5     | 3         | 1.33%   |
| 4     | 2         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 57        | 33.53%  |
| Graphics card            | 30        | 17.65%  |
| Unassigned class         | 23        | 13.53%  |
| Communication controller | 20        | 11.76%  |
| Chipcard                 | 11        | 6.47%   |
| Net/wireless             | 8         | 4.71%   |
| Card reader              | 5         | 2.94%   |
| Multimedia controller    | 3         | 1.76%   |
| Bluetooth                | 3         | 1.76%   |
| Storage                  | 2         | 1.18%   |
| Net/ethernet             | 2         | 1.18%   |
| Camera                   | 2         | 1.18%   |
| Storage/raid             | 1         | 0.59%   |
| Storage/ide              | 1         | 0.59%   |
| Sound                    | 1         | 0.59%   |
| Network                  | 1         | 0.59%   |

