Fedora 36 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 36.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_36/Desktop/README.md) and [notebooks](/Dist/Fedora_36/Notebook/README.md).

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

Total: 2970

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 2520                 | Notebook    | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [27c389d734](https://linux-hardware.org/?probe=27c389d734) | Jun 24, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [5043d686d8](https://linux-hardware.org/?probe=5043d686d8) | Jun 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [e8e25f684e](https://linux-hardware.org/?probe=e8e25f684e) | Jun 22, 2023 |
| Huanan        | X99-ZD4 V2.0                | Desktop     | [be1f0f151e](https://linux-hardware.org/?probe=be1f0f151e) | Jun 16, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [9cba8f7730](https://linux-hardware.org/?probe=9cba8f7730) | Jun 15, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [a280f19bb2](https://linux-hardware.org/?probe=a280f19bb2) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1fd265b6d8](https://linux-hardware.org/?probe=1fd265b6d8) | Jun 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4ab556e4b8](https://linux-hardware.org/?probe=4ab556e4b8) | Jun 10, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [e9ca405eff](https://linux-hardware.org/?probe=e9ca405eff) | Jun 08, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [e67581e121](https://linux-hardware.org/?probe=e67581e121) | Jun 07, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [f7178495c7](https://linux-hardware.org/?probe=f7178495c7) | Jun 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d70fe31101](https://linux-hardware.org/?probe=d70fe31101) | Jun 06, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [77b332cb2d](https://linux-hardware.org/?probe=77b332cb2d) | Jun 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [76a8e35b72](https://linux-hardware.org/?probe=76a8e35b72) | Jun 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [36173d5a42](https://linux-hardware.org/?probe=36173d5a42) | Jun 05, 2023 |
| MSI           | Modern 14 C12M              | Notebook    | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b951e6223c](https://linux-hardware.org/?probe=b951e6223c) | Jun 01, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [e8e3834bf8](https://linux-hardware.org/?probe=e8e3834bf8) | May 31, 2023 |
| Lenovo        | ThinkServer TS140           | Desktop     | [48cf9db6cd](https://linux-hardware.org/?probe=48cf9db6cd) | May 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3404cb6c67](https://linux-hardware.org/?probe=3404cb6c67) | May 31, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ffe895debc](https://linux-hardware.org/?probe=ffe895debc) | May 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7816244e1a](https://linux-hardware.org/?probe=7816244e1a) | May 30, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | Notebook    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7bfe35481d](https://linux-hardware.org/?probe=7bfe35481d) | May 29, 2023 |
| Biostar       | H310MHP                     | Desktop     | [7138f287c8](https://linux-hardware.org/?probe=7138f287c8) | May 29, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [0b7f7fb99a](https://linux-hardware.org/?probe=0b7f7fb99a) | May 29, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1b7089a58b](https://linux-hardware.org/?probe=1b7089a58b) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [1fd2d41164](https://linux-hardware.org/?probe=1fd2d41164) | May 22, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [9c923defd1](https://linux-hardware.org/?probe=9c923defd1) | May 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [14928b0276](https://linux-hardware.org/?probe=14928b0276) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [077df36551](https://linux-hardware.org/?probe=077df36551) | May 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2d942e3436](https://linux-hardware.org/?probe=2d942e3436) | May 14, 2023 |
| HP            | G50                         | Notebook    | [719a212774](https://linux-hardware.org/?probe=719a212774) | May 14, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [edc8069ae1](https://linux-hardware.org/?probe=edc8069ae1) | May 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2e2b57870b](https://linux-hardware.org/?probe=2e2b57870b) | May 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [08adc44b64](https://linux-hardware.org/?probe=08adc44b64) | May 12, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [c18cfbaca2](https://linux-hardware.org/?probe=c18cfbaca2) | May 10, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dfdc7713b6](https://linux-hardware.org/?probe=dfdc7713b6) | May 09, 2023 |
| AZW           | SER V01                     | Mini pc     | [a62bc3a279](https://linux-hardware.org/?probe=a62bc3a279) | May 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bc30b63ce3](https://linux-hardware.org/?probe=bc30b63ce3) | May 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a9d1794eec](https://linux-hardware.org/?probe=a9d1794eec) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [68c7b6891b](https://linux-hardware.org/?probe=68c7b6891b) | May 06, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ec4c764ea](https://linux-hardware.org/?probe=6ec4c764ea) | May 03, 2023 |
| Acer          | Veriton M2630G V:1.0        | Desktop     | [7ffa9c83d7](https://linux-hardware.org/?probe=7ffa9c83d7) | May 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [51c2405640](https://linux-hardware.org/?probe=51c2405640) | May 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f2c73a1fbb](https://linux-hardware.org/?probe=f2c73a1fbb) | May 01, 2023 |
| Dell          | Latitude 5521               | Notebook    | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [606b173cab](https://linux-hardware.org/?probe=606b173cab) | Apr 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6bf052a2f](https://linux-hardware.org/?probe=d6bf052a2f) | Apr 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [71983d0574](https://linux-hardware.org/?probe=71983d0574) | Apr 26, 2023 |
| Sony          | SVS13A25PXB                 | Notebook    | [a31acd0a66](https://linux-hardware.org/?probe=a31acd0a66) | Apr 25, 2023 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [297da8c979](https://linux-hardware.org/?probe=297da8c979) | Apr 24, 2023 |
| Sony          | SVS13A25PXB                 | Notebook    | [06138dd58a](https://linux-hardware.org/?probe=06138dd58a) | Apr 24, 2023 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [f4a215fc46](https://linux-hardware.org/?probe=f4a215fc46) | Apr 24, 2023 |
| BTO           | 17X1183                     | Notebook    | [134a6ead50](https://linux-hardware.org/?probe=134a6ead50) | Apr 23, 2023 |
| BTO           | 17X1183                     | Notebook    | [181163b5e8](https://linux-hardware.org/?probe=181163b5e8) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [1cc955413f](https://linux-hardware.org/?probe=1cc955413f) | Apr 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [4f473af7a9](https://linux-hardware.org/?probe=4f473af7a9) | Apr 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebdd0f2a6a](https://linux-hardware.org/?probe=ebdd0f2a6a) | Apr 20, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [a537c2bd18](https://linux-hardware.org/?probe=a537c2bd18) | Apr 17, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [264d99482b](https://linux-hardware.org/?probe=264d99482b) | Apr 17, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [acf5e9b9f5](https://linux-hardware.org/?probe=acf5e9b9f5) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c33ef2ceeb](https://linux-hardware.org/?probe=c33ef2ceeb) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [35d855a901](https://linux-hardware.org/?probe=35d855a901) | Apr 10, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3f8d1c6a26](https://linux-hardware.org/?probe=3f8d1c6a26) | Apr 09, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [a3ecc0f893](https://linux-hardware.org/?probe=a3ecc0f893) | Apr 07, 2023 |
| Intel         | S1200BTL E98681-352         | Server      | [891709c211](https://linux-hardware.org/?probe=891709c211) | Apr 07, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a44a4b80a](https://linux-hardware.org/?probe=9a44a4b80a) | Apr 03, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [aa74b25c97](https://linux-hardware.org/?probe=aa74b25c97) | Apr 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6f7c92fc7](https://linux-hardware.org/?probe=d6f7c92fc7) | Apr 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [50e745e72a](https://linux-hardware.org/?probe=50e745e72a) | Apr 01, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [41353f6a59](https://linux-hardware.org/?probe=41353f6a59) | Apr 01, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [b10ed7894c](https://linux-hardware.org/?probe=b10ed7894c) | Mar 31, 2023 |
| ASUSTek       | Leonite2                    | Desktop     | [21eb6fba07](https://linux-hardware.org/?probe=21eb6fba07) | Mar 30, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [5f0453caf8](https://linux-hardware.org/?probe=5f0453caf8) | Mar 28, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [761f7d71db](https://linux-hardware.org/?probe=761f7d71db) | Mar 27, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [dd6b3f7e44](https://linux-hardware.org/?probe=dd6b3f7e44) | Mar 26, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0749ec7b44](https://linux-hardware.org/?probe=0749ec7b44) | Mar 23, 2023 |
| HP            | 158A                        | Desktop     | [4bcb73e1bf](https://linux-hardware.org/?probe=4bcb73e1bf) | Mar 22, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8892fdfdf9](https://linux-hardware.org/?probe=8892fdfdf9) | Mar 19, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [08df29b00e](https://linux-hardware.org/?probe=08df29b00e) | Mar 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f842840cc9](https://linux-hardware.org/?probe=f842840cc9) | Mar 18, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [b09959cc0b](https://linux-hardware.org/?probe=b09959cc0b) | Mar 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [79c13317c6](https://linux-hardware.org/?probe=79c13317c6) | Mar 15, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c919e2da37](https://linux-hardware.org/?probe=c919e2da37) | Mar 12, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [d822a4112f](https://linux-hardware.org/?probe=d822a4112f) | Mar 11, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [d3ac8dd45f](https://linux-hardware.org/?probe=d3ac8dd45f) | Mar 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [089cafb799](https://linux-hardware.org/?probe=089cafb799) | Mar 11, 2023 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | Desktop     | [0dd36bc615](https://linux-hardware.org/?probe=0dd36bc615) | Mar 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [2246ef48c8](https://linux-hardware.org/?probe=2246ef48c8) | Mar 07, 2023 |
| HP            | ProBook 450 G4              | Notebook    | [72af4386e5](https://linux-hardware.org/?probe=72af4386e5) | Mar 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [46d39caf5c](https://linux-hardware.org/?probe=46d39caf5c) | Mar 06, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [08f74aef46](https://linux-hardware.org/?probe=08f74aef46) | Mar 05, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [bd0163923e](https://linux-hardware.org/?probe=bd0163923e) | Mar 04, 2023 |
| Lenovo        | ThinkPad X230 23255SM       | Notebook    | [2f5cd26eae](https://linux-hardware.org/?probe=2f5cd26eae) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b20cfbdfa1](https://linux-hardware.org/?probe=b20cfbdfa1) | Mar 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [989eed6d5f](https://linux-hardware.org/?probe=989eed6d5f) | Mar 03, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [aa0e36b22e](https://linux-hardware.org/?probe=aa0e36b22e) | Mar 02, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [d0ce638961](https://linux-hardware.org/?probe=d0ce638961) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ba4afa4d3b](https://linux-hardware.org/?probe=ba4afa4d3b) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [40516fd80e](https://linux-hardware.org/?probe=40516fd80e) | Mar 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f27314deb8](https://linux-hardware.org/?probe=f27314deb8) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [b4841d9589](https://linux-hardware.org/?probe=b4841d9589) | Feb 26, 2023 |
| Acer          | TravelMate P633-V           | Notebook    | [fd426b6c71](https://linux-hardware.org/?probe=fd426b6c71) | Feb 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d6c6778bb7](https://linux-hardware.org/?probe=d6c6778bb7) | Feb 25, 2023 |
| Lenovo        | 851F 60072                  | Tablet      | [8466ce344b](https://linux-hardware.org/?probe=8466ce344b) | Feb 24, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7b4981d722](https://linux-hardware.org/?probe=7b4981d722) | Feb 24, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [c3f49d4cee](https://linux-hardware.org/?probe=c3f49d4cee) | Feb 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f9314a0aa9](https://linux-hardware.org/?probe=f9314a0aa9) | Feb 19, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8dabbaa31c](https://linux-hardware.org/?probe=8dabbaa31c) | Feb 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [991b8b4361](https://linux-hardware.org/?probe=991b8b4361) | Feb 17, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [d112d85387](https://linux-hardware.org/?probe=d112d85387) | Feb 15, 2023 |
| Gigabyte      | H410M DS2V                  | Desktop     | [b2e8c15dc4](https://linux-hardware.org/?probe=b2e8c15dc4) | Feb 15, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0033422c4d](https://linux-hardware.org/?probe=0033422c4d) | Feb 14, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [387ec47efe](https://linux-hardware.org/?probe=387ec47efe) | Feb 14, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| MSI           | B250 GAMING PRO CARBON      | Desktop     | [0b05e41c64](https://linux-hardware.org/?probe=0b05e41c64) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1adfd2bb79](https://linux-hardware.org/?probe=1adfd2bb79) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [3482c24991](https://linux-hardware.org/?probe=3482c24991) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [147b5315c5](https://linux-hardware.org/?probe=147b5315c5) | Feb 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0376f0c65f](https://linux-hardware.org/?probe=0376f0c65f) | Feb 07, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [522dd694da](https://linux-hardware.org/?probe=522dd694da) | Feb 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [69b76f313e](https://linux-hardware.org/?probe=69b76f313e) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [09811b1f20](https://linux-hardware.org/?probe=09811b1f20) | Feb 02, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [6b007d74de](https://linux-hardware.org/?probe=6b007d74de) | Feb 02, 2023 |
| Lenovo        | 3000 N200 0769BAG           | Notebook    | [f8f410eb2a](https://linux-hardware.org/?probe=f8f410eb2a) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| Lenovo        | IdeaPad S340-14IML 81N9     | Notebook    | [58e620077b](https://linux-hardware.org/?probe=58e620077b) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [6d4ecb5a00](https://linux-hardware.org/?probe=6d4ecb5a00) | Jan 27, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| Dell          | Latitude 7480               | Notebook    | [3cb61c5b71](https://linux-hardware.org/?probe=3cb61c5b71) | Jan 26, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [3386aa1dce](https://linux-hardware.org/?probe=3386aa1dce) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d1c6e3c96f](https://linux-hardware.org/?probe=d1c6e3c96f) | Jan 24, 2023 |
| Dell          | Latitude 3420               | Notebook    | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7f36411ac1](https://linux-hardware.org/?probe=7f36411ac1) | Jan 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| ASRock        | Z690 PG Riptide             | Desktop     | [582e3e3026](https://linux-hardware.org/?probe=582e3e3026) | Jan 19, 2023 |
| HP            | ENVY Laptop 17-ce0xxx       | Notebook    | [1a0f3869dd](https://linux-hardware.org/?probe=1a0f3869dd) | Jan 18, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8da5286795](https://linux-hardware.org/?probe=8da5286795) | Jan 18, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0d7c3e0009](https://linux-hardware.org/?probe=0d7c3e0009) | Jan 17, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9f280d24f5](https://linux-hardware.org/?probe=9f280d24f5) | Jan 17, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [f26dbd644c](https://linux-hardware.org/?probe=f26dbd644c) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [84d86434e8](https://linux-hardware.org/?probe=84d86434e8) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7e67b2b3a0](https://linux-hardware.org/?probe=7e67b2b3a0) | Jan 14, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ea080033f1](https://linux-hardware.org/?probe=ea080033f1) | Jan 14, 2023 |
| HP            | 8753                        | Desktop     | [5cdf3ef632](https://linux-hardware.org/?probe=5cdf3ef632) | Jan 14, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c94f291c81](https://linux-hardware.org/?probe=c94f291c81) | Jan 13, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3128a21a3a](https://linux-hardware.org/?probe=3128a21a3a) | Jan 13, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [e78a057172](https://linux-hardware.org/?probe=e78a057172) | Jan 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [f9846c0e18](https://linux-hardware.org/?probe=f9846c0e18) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Lenovo        | ThinkPad T430 2347B85       | Notebook    | [01fce134df](https://linux-hardware.org/?probe=01fce134df) | Jan 12, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [eec3fcf9ff](https://linux-hardware.org/?probe=eec3fcf9ff) | Jan 11, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8e1eba4ad4](https://linux-hardware.org/?probe=8e1eba4ad4) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9eac6e2b97](https://linux-hardware.org/?probe=9eac6e2b97) | Jan 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b8ac11cfd3](https://linux-hardware.org/?probe=b8ac11cfd3) | Jan 08, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [9f84e9b911](https://linux-hardware.org/?probe=9f84e9b911) | Jan 07, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [153f5dbeb5](https://linux-hardware.org/?probe=153f5dbeb5) | Jan 07, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c8a281879a](https://linux-hardware.org/?probe=c8a281879a) | Jan 07, 2023 |
| ASUSTek       | H61M-C                      | Desktop     | [494e552521](https://linux-hardware.org/?probe=494e552521) | Jan 07, 2023 |
| HP            | 240 G8                      | Notebook    | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [94d61ca559](https://linux-hardware.org/?probe=94d61ca559) | Jan 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [01b93cba09](https://linux-hardware.org/?probe=01b93cba09) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| Toshiba       | Satellite C75D-B            | Notebook    | [d5380976a2](https://linux-hardware.org/?probe=d5380976a2) | Jan 03, 2023 |
| HP            | 8459                        | Desktop     | [18f44a4e07](https://linux-hardware.org/?probe=18f44a4e07) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [63c7138092](https://linux-hardware.org/?probe=63c7138092) | Jan 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1229c65c83](https://linux-hardware.org/?probe=1229c65c83) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Dell          | Inspiron 5580               | Notebook    | [c6a044c898](https://linux-hardware.org/?probe=c6a044c898) | Jan 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ca82922df4](https://linux-hardware.org/?probe=ca82922df4) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [178dcba2a5](https://linux-hardware.org/?probe=178dcba2a5) | Jan 01, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [f871c26332](https://linux-hardware.org/?probe=f871c26332) | Jan 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [8582096251](https://linux-hardware.org/?probe=8582096251) | Dec 31, 2022 |
| MAXSUN        | MS-TZZ A320M.2-VH           | Desktop     | [8f06578f10](https://linux-hardware.org/?probe=8f06578f10) | Dec 31, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [4e6065532f](https://linux-hardware.org/?probe=4e6065532f) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3b0d4e8973](https://linux-hardware.org/?probe=3b0d4e8973) | Dec 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [1c46a3fdd3](https://linux-hardware.org/?probe=1c46a3fdd3) | Dec 29, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [daf7777113](https://linux-hardware.org/?probe=daf7777113) | Dec 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [47f95e17c5](https://linux-hardware.org/?probe=47f95e17c5) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [7c6adb6279](https://linux-hardware.org/?probe=7c6adb6279) | Dec 28, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [59b38f9b63](https://linux-hardware.org/?probe=59b38f9b63) | Dec 28, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d572d06d7](https://linux-hardware.org/?probe=2d572d06d7) | Dec 28, 2022 |
| MSI           | GT60                        | Notebook    | [3917ca13e3](https://linux-hardware.org/?probe=3917ca13e3) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [cbe4c82d15](https://linux-hardware.org/?probe=cbe4c82d15) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [c546bb007b](https://linux-hardware.org/?probe=c546bb007b) | Dec 26, 2022 |
| HP            | 3397                        | Desktop     | [4286520907](https://linux-hardware.org/?probe=4286520907) | Dec 26, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8636b69474](https://linux-hardware.org/?probe=8636b69474) | Dec 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [a375cc62c7](https://linux-hardware.org/?probe=a375cc62c7) | Dec 24, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [4ea620705d](https://linux-hardware.org/?probe=4ea620705d) | Dec 24, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [04282775ba](https://linux-hardware.org/?probe=04282775ba) | Dec 24, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [6b2cd55178](https://linux-hardware.org/?probe=6b2cd55178) | Dec 23, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c36553b2b8](https://linux-hardware.org/?probe=c36553b2b8) | Dec 23, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [bfe7b1ec1d](https://linux-hardware.org/?probe=bfe7b1ec1d) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [3832e7e0af](https://linux-hardware.org/?probe=3832e7e0af) | Dec 21, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [b052f8434a](https://linux-hardware.org/?probe=b052f8434a) | Dec 20, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8a7ee1147b](https://linux-hardware.org/?probe=8a7ee1147b) | Dec 20, 2022 |
| MSI           | Boston                      | Desktop     | [8587c9cf45](https://linux-hardware.org/?probe=8587c9cf45) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [900fd62aaf](https://linux-hardware.org/?probe=900fd62aaf) | Dec 19, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [b34721e6cb](https://linux-hardware.org/?probe=b34721e6cb) | Dec 19, 2022 |
| MSI           | GL63 8RC                    | Notebook    | [6a5bc85513](https://linux-hardware.org/?probe=6a5bc85513) | Dec 18, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [b4d6964157](https://linux-hardware.org/?probe=b4d6964157) | Dec 18, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [0a7621cb40](https://linux-hardware.org/?probe=0a7621cb40) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [be93cca77c](https://linux-hardware.org/?probe=be93cca77c) | Dec 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [9caae58821](https://linux-hardware.org/?probe=9caae58821) | Dec 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5a071587fb](https://linux-hardware.org/?probe=5a071587fb) | Dec 15, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e647deca28](https://linux-hardware.org/?probe=e647deca28) | Dec 14, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [7c32d0f453](https://linux-hardware.org/?probe=7c32d0f453) | Dec 14, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c8ffea5473](https://linux-hardware.org/?probe=c8ffea5473) | Dec 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5ea80edee8](https://linux-hardware.org/?probe=5ea80edee8) | Dec 14, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [72b3306c33](https://linux-hardware.org/?probe=72b3306c33) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| MSI           | MEG B550 UNIFY              | Desktop     | [e9a996b54a](https://linux-hardware.org/?probe=e9a996b54a) | Dec 12, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8111a18c7c](https://linux-hardware.org/?probe=8111a18c7c) | Dec 12, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b7b1ed9d8b](https://linux-hardware.org/?probe=b7b1ed9d8b) | Dec 12, 2022 |
| Samsung       | 930X5J/910S5J/940X5J        | Notebook    | [deb721084b](https://linux-hardware.org/?probe=deb721084b) | Dec 11, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [01decbbb6d](https://linux-hardware.org/?probe=01decbbb6d) | Dec 10, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Dell          | G5 5505                     | Notebook    | [60053b5d4b](https://linux-hardware.org/?probe=60053b5d4b) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [ad87e1559a](https://linux-hardware.org/?probe=ad87e1559a) | Dec 09, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [ea91fc57ae](https://linux-hardware.org/?probe=ea91fc57ae) | Dec 09, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | Notebook    | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [1c73b61db3](https://linux-hardware.org/?probe=1c73b61db3) | Dec 08, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [2d35fb5bbb](https://linux-hardware.org/?probe=2d35fb5bbb) | Dec 08, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [6844d4578b](https://linux-hardware.org/?probe=6844d4578b) | Dec 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [3e50ee3f94](https://linux-hardware.org/?probe=3e50ee3f94) | Dec 07, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [9fb5c9d094](https://linux-hardware.org/?probe=9fb5c9d094) | Dec 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [7377ad6d99](https://linux-hardware.org/?probe=7377ad6d99) | Dec 05, 2022 |
| Lenovo        | ThinkPad neo 14 21DN0009... | Notebook    | [80c8d84387](https://linux-hardware.org/?probe=80c8d84387) | Dec 05, 2022 |
| HP            | 245 G7                      | Notebook    | [57ed16df1f](https://linux-hardware.org/?probe=57ed16df1f) | Dec 05, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [e6941ba491](https://linux-hardware.org/?probe=e6941ba491) | Dec 05, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [41a365e56e](https://linux-hardware.org/?probe=41a365e56e) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [cbb4692837](https://linux-hardware.org/?probe=cbb4692837) | Dec 04, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [8dd6905ba5](https://linux-hardware.org/?probe=8dd6905ba5) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3807efd1f4](https://linux-hardware.org/?probe=3807efd1f4) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [77651c30c5](https://linux-hardware.org/?probe=77651c30c5) | Dec 03, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [38d691df3b](https://linux-hardware.org/?probe=38d691df3b) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [8b85688e36](https://linux-hardware.org/?probe=8b85688e36) | Dec 02, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [2414a84e4f](https://linux-hardware.org/?probe=2414a84e4f) | Dec 02, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [0e87a76042](https://linux-hardware.org/?probe=0e87a76042) | Dec 01, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [a4ae0cdd6a](https://linux-hardware.org/?probe=a4ae0cdd6a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Unknown       | X99H                        | Desktop     | [b9e2236de7](https://linux-hardware.org/?probe=b9e2236de7) | Nov 30, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [d7025eb475](https://linux-hardware.org/?probe=d7025eb475) | Nov 30, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f4fa3a4e7f](https://linux-hardware.org/?probe=f4fa3a4e7f) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [bc3188dd75](https://linux-hardware.org/?probe=bc3188dd75) | Nov 29, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [ba6d4f20e7](https://linux-hardware.org/?probe=ba6d4f20e7) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | Notebook    | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [624e6b243c](https://linux-hardware.org/?probe=624e6b243c) | Nov 28, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [54e985a956](https://linux-hardware.org/?probe=54e985a956) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [68e68e1e01](https://linux-hardware.org/?probe=68e68e1e01) | Nov 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [8fa53292bf](https://linux-hardware.org/?probe=8fa53292bf) | Nov 27, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | EP45-DS3P                   | Desktop     | [20015fb913](https://linux-hardware.org/?probe=20015fb913) | Nov 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [07363955de](https://linux-hardware.org/?probe=07363955de) | Nov 26, 2022 |
| Intel         | NUC11PHBi7 M26151-402       | Mini pc     | [0c97f1e481](https://linux-hardware.org/?probe=0c97f1e481) | Nov 25, 2022 |
| Biostar       | H310MHC2                    | Desktop     | [49e09047c4](https://linux-hardware.org/?probe=49e09047c4) | Nov 25, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [45dc299d52](https://linux-hardware.org/?probe=45dc299d52) | Nov 25, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [1c648060f6](https://linux-hardware.org/?probe=1c648060f6) | Nov 25, 2022 |
| MSI           | H81M-E33                    | Desktop     | [80ec8663ac](https://linux-hardware.org/?probe=80ec8663ac) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [43fe4ed852](https://linux-hardware.org/?probe=43fe4ed852) | Nov 24, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Notebook    | [10e706472c](https://linux-hardware.org/?probe=10e706472c) | Nov 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [0f96032f10](https://linux-hardware.org/?probe=0f96032f10) | Nov 24, 2022 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [a5005bf517](https://linux-hardware.org/?probe=a5005bf517) | Nov 24, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [c1e62a557c](https://linux-hardware.org/?probe=c1e62a557c) | Nov 24, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [ced8851dc3](https://linux-hardware.org/?probe=ced8851dc3) | Nov 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [990ff088e8](https://linux-hardware.org/?probe=990ff088e8) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| Dell          | Precision 5510              | Notebook    | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ac4a817e75](https://linux-hardware.org/?probe=ac4a817e75) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [3b9a05e385](https://linux-hardware.org/?probe=3b9a05e385) | Nov 21, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [489ded27aa](https://linux-hardware.org/?probe=489ded27aa) | Nov 21, 2022 |
| ASUSTek       | X45C                        | Notebook    | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [09e98d8c02](https://linux-hardware.org/?probe=09e98d8c02) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8478dece38](https://linux-hardware.org/?probe=8478dece38) | Nov 21, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b41f6ec236](https://linux-hardware.org/?probe=b41f6ec236) | Nov 21, 2022 |
| HP            | 18E7                        | Desktop     | [0b963b44fb](https://linux-hardware.org/?probe=0b963b44fb) | Nov 21, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [a890ae6d6c](https://linux-hardware.org/?probe=a890ae6d6c) | Nov 20, 2022 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | Notebook    | [f5cbe0bfa2](https://linux-hardware.org/?probe=f5cbe0bfa2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [1755321c80](https://linux-hardware.org/?probe=1755321c80) | Nov 19, 2022 |
| HP            | Elite Dragonfly             | Convertible | [2630af5372](https://linux-hardware.org/?probe=2630af5372) | Nov 19, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [806ac66c75](https://linux-hardware.org/?probe=806ac66c75) | Nov 19, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [1af696c23c](https://linux-hardware.org/?probe=1af696c23c) | Nov 19, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [587db1b08f](https://linux-hardware.org/?probe=587db1b08f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [7de2db4d3a](https://linux-hardware.org/?probe=7de2db4d3a) | Nov 18, 2022 |
| Gigabyte      | H61M-USB3V                  | Desktop     | [e034e5bbb2](https://linux-hardware.org/?probe=e034e5bbb2) | Nov 18, 2022 |
| Lenovo        | Legion 5 82B5               | Notebook    | [907810c0ac](https://linux-hardware.org/?probe=907810c0ac) | Nov 18, 2022 |
| Dell          | 03GCPM A01                  | Server      | [396bc50b1c](https://linux-hardware.org/?probe=396bc50b1c) | Nov 18, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [a8847bb3ad](https://linux-hardware.org/?probe=a8847bb3ad) | Nov 18, 2022 |
| Dell          | 03GCPM A01                  | Server      | [53b560a9a9](https://linux-hardware.org/?probe=53b560a9a9) | Nov 18, 2022 |
| Dell          | 0X30MX A00                  | Desktop     | [c3657c7f97](https://linux-hardware.org/?probe=c3657c7f97) | Nov 18, 2022 |
| Exo           | Smart XS1                   | Notebook    | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e9eb63ca62](https://linux-hardware.org/?probe=e9eb63ca62) | Nov 17, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [5d1e2af2ea](https://linux-hardware.org/?probe=5d1e2af2ea) | Nov 17, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [cd01bd7dad](https://linux-hardware.org/?probe=cd01bd7dad) | Nov 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [69b281a787](https://linux-hardware.org/?probe=69b281a787) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [620dbe0a8f](https://linux-hardware.org/?probe=620dbe0a8f) | Nov 16, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9cd3d86efc](https://linux-hardware.org/?probe=9cd3d86efc) | Nov 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [76d056b728](https://linux-hardware.org/?probe=76d056b728) | Nov 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5e6c94e04c](https://linux-hardware.org/?probe=5e6c94e04c) | Nov 15, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [699ea2cc17](https://linux-hardware.org/?probe=699ea2cc17) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [74cfc7d01e](https://linux-hardware.org/?probe=74cfc7d01e) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [07d6aa9adc](https://linux-hardware.org/?probe=07d6aa9adc) | Nov 14, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [4a19565db2](https://linux-hardware.org/?probe=4a19565db2) | Nov 14, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [c050452a72](https://linux-hardware.org/?probe=c050452a72) | Nov 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5b9f10af19](https://linux-hardware.org/?probe=5b9f10af19) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| Samsung       | 730QDA                      | Convertible | [169bdd2f71](https://linux-hardware.org/?probe=169bdd2f71) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [9d942ddc9c](https://linux-hardware.org/?probe=9d942ddc9c) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [97bfce0a04](https://linux-hardware.org/?probe=97bfce0a04) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Dell          | G3 3579                     | Notebook    | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Alienware     | Area-51m                    | Notebook    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [256503ef7e](https://linux-hardware.org/?probe=256503ef7e) | Nov 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [eb533b483e](https://linux-hardware.org/?probe=eb533b483e) | Nov 12, 2022 |
| Dell          | Latitude E6420              | Notebook    | [056daa7806](https://linux-hardware.org/?probe=056daa7806) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [cedb086e46](https://linux-hardware.org/?probe=cedb086e46) | Nov 12, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [eb5ece0bb3](https://linux-hardware.org/?probe=eb5ece0bb3) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| ASUSTek       | X550JD                      | Notebook    | [9c88cc6c32](https://linux-hardware.org/?probe=9c88cc6c32) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [68e5509696](https://linux-hardware.org/?probe=68e5509696) | Nov 11, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2db7764d25](https://linux-hardware.org/?probe=2db7764d25) | Nov 11, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [2b59844827](https://linux-hardware.org/?probe=2b59844827) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0bd2321bee](https://linux-hardware.org/?probe=0bd2321bee) | Nov 11, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [ea30d00f9a](https://linux-hardware.org/?probe=ea30d00f9a) | Nov 10, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [f927960881](https://linux-hardware.org/?probe=f927960881) | Nov 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Monster       | ABRA A5 V15.6               | Notebook    | [3bf45390cc](https://linux-hardware.org/?probe=3bf45390cc) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fc22f217b3](https://linux-hardware.org/?probe=fc22f217b3) | Nov 10, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [7973c1467f](https://linux-hardware.org/?probe=7973c1467f) | Nov 10, 2022 |
| ASUSTek       | N752VX                      | Notebook    | [a5b6d827b2](https://linux-hardware.org/?probe=a5b6d827b2) | Nov 10, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [009f3d82e9](https://linux-hardware.org/?probe=009f3d82e9) | Nov 10, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | Notebook    | [7638b6abf6](https://linux-hardware.org/?probe=7638b6abf6) | Nov 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QQS44Q00     | Notebook    | [29ddbee669](https://linux-hardware.org/?probe=29ddbee669) | Nov 09, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [5bccf91e38](https://linux-hardware.org/?probe=5bccf91e38) | Nov 09, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [17c345f111](https://linux-hardware.org/?probe=17c345f111) | Nov 09, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [b10bd50d9c](https://linux-hardware.org/?probe=b10bd50d9c) | Nov 09, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [67fa42f70a](https://linux-hardware.org/?probe=67fa42f70a) | Nov 09, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [d224ed7da8](https://linux-hardware.org/?probe=d224ed7da8) | Nov 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [73c9a3d81e](https://linux-hardware.org/?probe=73c9a3d81e) | Nov 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [226409c98f](https://linux-hardware.org/?probe=226409c98f) | Nov 09, 2022 |
| Foxconn       | H61M-S/H61M                 | Desktop     | [81b2006fd3](https://linux-hardware.org/?probe=81b2006fd3) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [3900976672](https://linux-hardware.org/?probe=3900976672) | Nov 08, 2022 |
| Lenovo        | ThinkPad T480 20L6S24N00    | Notebook    | [0b17fc5246](https://linux-hardware.org/?probe=0b17fc5246) | Nov 08, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [3a4a75d603](https://linux-hardware.org/?probe=3a4a75d603) | Nov 08, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0b65e26932](https://linux-hardware.org/?probe=0b65e26932) | Nov 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33b2dbfcc2](https://linux-hardware.org/?probe=33b2dbfcc2) | Nov 08, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [265707c6a3](https://linux-hardware.org/?probe=265707c6a3) | Nov 08, 2022 |
| HP            | Notebook                    | Notebook    | [5cbade7533](https://linux-hardware.org/?probe=5cbade7533) | Nov 08, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [c949ec23ce](https://linux-hardware.org/?probe=c949ec23ce) | Nov 07, 2022 |
| Intel         | NUC11TNBi3 M11908-403       | Mini pc     | [02610c1e36](https://linux-hardware.org/?probe=02610c1e36) | Nov 07, 2022 |
| Dell          | Latitude 3410               | Notebook    | [f6532fe0ee](https://linux-hardware.org/?probe=f6532fe0ee) | Nov 07, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | Desktop     | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [d87a3e023a](https://linux-hardware.org/?probe=d87a3e023a) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f207bc4c3](https://linux-hardware.org/?probe=3f207bc4c3) | Nov 07, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [0373b83f63](https://linux-hardware.org/?probe=0373b83f63) | Nov 06, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [43eefaca07](https://linux-hardware.org/?probe=43eefaca07) | Nov 06, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [38d24e4b4a](https://linux-hardware.org/?probe=38d24e4b4a) | Nov 06, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [47ca2c5cb7](https://linux-hardware.org/?probe=47ca2c5cb7) | Nov 06, 2022 |
| Quanta        | TWS                         | Notebook    | [1ad872afcd](https://linux-hardware.org/?probe=1ad872afcd) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [af69f66287](https://linux-hardware.org/?probe=af69f66287) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [256002ea80](https://linux-hardware.org/?probe=256002ea80) | Nov 06, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | Notebook    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [12c49f9e36](https://linux-hardware.org/?probe=12c49f9e36) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [d9952c90a5](https://linux-hardware.org/?probe=d9952c90a5) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | Notebook    | [fb8bc290d6](https://linux-hardware.org/?probe=fb8bc290d6) | Nov 05, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [e8a62297a5](https://linux-hardware.org/?probe=e8a62297a5) | Nov 05, 2022 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [2b4987c9e8](https://linux-hardware.org/?probe=2b4987c9e8) | Nov 05, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| ASUSTek       | FX503VD                     | Notebook    | [f80b5eaa0b](https://linux-hardware.org/?probe=f80b5eaa0b) | Nov 05, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [e29a593971](https://linux-hardware.org/?probe=e29a593971) | Nov 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [56db615f30](https://linux-hardware.org/?probe=56db615f30) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| Dell          | Inspiron 15 3510            | Notebook    | [f0f862d5c5](https://linux-hardware.org/?probe=f0f862d5c5) | Nov 05, 2022 |
| ASUSTek       | X750JN                      | Notebook    | [3c8b130af7](https://linux-hardware.org/?probe=3c8b130af7) | Nov 05, 2022 |
| Dell          | Latitude 5591               | Notebook    | [e0e1ffe014](https://linux-hardware.org/?probe=e0e1ffe014) | Nov 05, 2022 |
| Dell          | Latitude 5591               | Notebook    | [b649030512](https://linux-hardware.org/?probe=b649030512) | Nov 05, 2022 |
| Acer          | Aspire 4820T                | Notebook    | [300aa32e45](https://linux-hardware.org/?probe=300aa32e45) | Nov 04, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [02a767e075](https://linux-hardware.org/?probe=02a767e075) | Nov 04, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [2c605465bb](https://linux-hardware.org/?probe=2c605465bb) | Nov 04, 2022 |
| HP            | 339A                        | Desktop     | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| HP            | 339A                        | Desktop     | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [3614ee4149](https://linux-hardware.org/?probe=3614ee4149) | Nov 04, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [4e666fbb8f](https://linux-hardware.org/?probe=4e666fbb8f) | Nov 04, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [c58816cb3d](https://linux-hardware.org/?probe=c58816cb3d) | Nov 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Packard Be... | EasyNote LX                 | Notebook    | [41070f6bfe](https://linux-hardware.org/?probe=41070f6bfe) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | Notebook    | [2a802edc5a](https://linux-hardware.org/?probe=2a802edc5a) | Nov 04, 2022 |
| GEO           | GEOBOOK 2E                  | Notebook    | [80e1206b6d](https://linux-hardware.org/?probe=80e1206b6d) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [775987aacb](https://linux-hardware.org/?probe=775987aacb) | Nov 04, 2022 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [876fc02284](https://linux-hardware.org/?probe=876fc02284) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0c186f330b](https://linux-hardware.org/?probe=0c186f330b) | Nov 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [2d53ffb628](https://linux-hardware.org/?probe=2d53ffb628) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [f027f3a4e2](https://linux-hardware.org/?probe=f027f3a4e2) | Nov 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40700 WIN     | Desktop     | [cb9374e939](https://linux-hardware.org/?probe=cb9374e939) | Nov 04, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [41e941e3ca](https://linux-hardware.org/?probe=41e941e3ca) | Nov 03, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [3480a7be5a](https://linux-hardware.org/?probe=3480a7be5a) | Nov 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [7a2dab8dde](https://linux-hardware.org/?probe=7a2dab8dde) | Nov 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [24eea2c3f7](https://linux-hardware.org/?probe=24eea2c3f7) | Nov 03, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ec0599883c](https://linux-hardware.org/?probe=ec0599883c) | Nov 03, 2022 |
| Acer          | Predator G9-591             | Notebook    | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [01381d41de](https://linux-hardware.org/?probe=01381d41de) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [921a646464](https://linux-hardware.org/?probe=921a646464) | Nov 03, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [cfc6040185](https://linux-hardware.org/?probe=cfc6040185) | Nov 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [03447f0763](https://linux-hardware.org/?probe=03447f0763) | Nov 03, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [457cdcf84a](https://linux-hardware.org/?probe=457cdcf84a) | Nov 03, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [4359d2a528](https://linux-hardware.org/?probe=4359d2a528) | Nov 02, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [2a280dc7df](https://linux-hardware.org/?probe=2a280dc7df) | Nov 02, 2022 |
| Lenovo        | ThinkPad T61 6464A13        | Notebook    | [5f850cbab6](https://linux-hardware.org/?probe=5f850cbab6) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c9041d22be](https://linux-hardware.org/?probe=c9041d22be) | Nov 02, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [4fa32ec6af](https://linux-hardware.org/?probe=4fa32ec6af) | Nov 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2d931f9e99](https://linux-hardware.org/?probe=2d931f9e99) | Nov 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [335af8b89b](https://linux-hardware.org/?probe=335af8b89b) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [22b32d9bac](https://linux-hardware.org/?probe=22b32d9bac) | Nov 02, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d4ac3a5f04](https://linux-hardware.org/?probe=d4ac3a5f04) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a156a7484d](https://linux-hardware.org/?probe=a156a7484d) | Nov 02, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [7b51138a0b](https://linux-hardware.org/?probe=7b51138a0b) | Nov 02, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d3beec5427](https://linux-hardware.org/?probe=d3beec5427) | Nov 02, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9b093574b9](https://linux-hardware.org/?probe=9b093574b9) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24c2a01761](https://linux-hardware.org/?probe=24c2a01761) | Nov 02, 2022 |
| Dell          | Latitude 5591               | Notebook    | [bcd8aef9a0](https://linux-hardware.org/?probe=bcd8aef9a0) | Nov 02, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [dfe5dc3d95](https://linux-hardware.org/?probe=dfe5dc3d95) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [379443a5d6](https://linux-hardware.org/?probe=379443a5d6) | Nov 01, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [5e099af04c](https://linux-hardware.org/?probe=5e099af04c) | Nov 01, 2022 |
| HP            | 829E                        | Mini pc     | [f568895fbb](https://linux-hardware.org/?probe=f568895fbb) | Nov 01, 2022 |
| Gigabyte      | B550 UD AC                  | Desktop     | [c5a5219cf3](https://linux-hardware.org/?probe=c5a5219cf3) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [766e7fb0d0](https://linux-hardware.org/?probe=766e7fb0d0) | Nov 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [9608724116](https://linux-hardware.org/?probe=9608724116) | Nov 01, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ee4c33d7b1](https://linux-hardware.org/?probe=ee4c33d7b1) | Nov 01, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| HP            | 339A                        | Desktop     | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d63c5de91b](https://linux-hardware.org/?probe=d63c5de91b) | Nov 01, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [f6b6afc8a3](https://linux-hardware.org/?probe=f6b6afc8a3) | Nov 01, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [274a3383db](https://linux-hardware.org/?probe=274a3383db) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [c91800e8c1](https://linux-hardware.org/?probe=c91800e8c1) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [46f1da66b6](https://linux-hardware.org/?probe=46f1da66b6) | Oct 31, 2022 |
| ASUSTek       | X510UAR                     | Notebook    | [1409a7f78d](https://linux-hardware.org/?probe=1409a7f78d) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [fffb5288e0](https://linux-hardware.org/?probe=fffb5288e0) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [15bdbbf952](https://linux-hardware.org/?probe=15bdbbf952) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [aa4b5e4400](https://linux-hardware.org/?probe=aa4b5e4400) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ac9bf1711](https://linux-hardware.org/?probe=4ac9bf1711) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [002ab67e5e](https://linux-hardware.org/?probe=002ab67e5e) | Oct 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [76906648cb](https://linux-hardware.org/?probe=76906648cb) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [cf460716f9](https://linux-hardware.org/?probe=cf460716f9) | Oct 30, 2022 |
| Dell          | Inspiron 14 7425 2-in-1     | Convertible | [e427e48710](https://linux-hardware.org/?probe=e427e48710) | Oct 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| Sony          | VAIO                        | All in one  | [b295b1cb6f](https://linux-hardware.org/?probe=b295b1cb6f) | Oct 30, 2022 |
| MSI           | B250M GAMING PRO            | Desktop     | [98979beea7](https://linux-hardware.org/?probe=98979beea7) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c52b1fe5fa](https://linux-hardware.org/?probe=c52b1fe5fa) | Oct 30, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [f1478df888](https://linux-hardware.org/?probe=f1478df888) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [df654ca0b1](https://linux-hardware.org/?probe=df654ca0b1) | Oct 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [32a6333f4b](https://linux-hardware.org/?probe=32a6333f4b) | Oct 30, 2022 |
| Aquarius      | Cmp NS765                   | Notebook    | [5e519edbee](https://linux-hardware.org/?probe=5e519edbee) | Oct 30, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [60ba0bc2dd](https://linux-hardware.org/?probe=60ba0bc2dd) | Oct 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1925c8ce1f](https://linux-hardware.org/?probe=1925c8ce1f) | Oct 29, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [b3dd383a83](https://linux-hardware.org/?probe=b3dd383a83) | Oct 29, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| ASUSTek       | Q550LF                      | Notebook    | [383c45edce](https://linux-hardware.org/?probe=383c45edce) | Oct 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [012cd7214b](https://linux-hardware.org/?probe=012cd7214b) | Oct 29, 2022 |
| Dell          | Latitude E7450              | Notebook    | [635a60671d](https://linux-hardware.org/?probe=635a60671d) | Oct 29, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| HP            | 82A5                        | Mini pc     | [c0be7985c0](https://linux-hardware.org/?probe=c0be7985c0) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| Lenovo        | ThinkPad P52 20M9S1EM00     | Notebook    | [40de74c5c5](https://linux-hardware.org/?probe=40de74c5c5) | Oct 28, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e06398e1bc](https://linux-hardware.org/?probe=e06398e1bc) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [83179a6cea](https://linux-hardware.org/?probe=83179a6cea) | Oct 28, 2022 |
| Lenovo        | 3172 NOK                    | Mini pc     | [1ddbbf71eb](https://linux-hardware.org/?probe=1ddbbf71eb) | Oct 28, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [72102d6890](https://linux-hardware.org/?probe=72102d6890) | Oct 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [38135da604](https://linux-hardware.org/?probe=38135da604) | Oct 28, 2022 |
| Sony          | VPCCB3S1R                   | Notebook    | [ee5b1465a1](https://linux-hardware.org/?probe=ee5b1465a1) | Oct 28, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [85019658e9](https://linux-hardware.org/?probe=85019658e9) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d64fb48e7](https://linux-hardware.org/?probe=1d64fb48e7) | Oct 27, 2022 |
| Timi          | TM1701                      | Notebook    | [f246345845](https://linux-hardware.org/?probe=f246345845) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [3a9f97607d](https://linux-hardware.org/?probe=3a9f97607d) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [36b663cec7](https://linux-hardware.org/?probe=36b663cec7) | Oct 27, 2022 |
| MSI           | H81M-E33                    | Desktop     | [f0613bfce8](https://linux-hardware.org/?probe=f0613bfce8) | Oct 27, 2022 |
| MSI           | PS63 Modern 8RC             | Notebook    | [e00fd51503](https://linux-hardware.org/?probe=e00fd51503) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [99152f7783](https://linux-hardware.org/?probe=99152f7783) | Oct 27, 2022 |
| Lenovo        | Yoga 720-13IKB              | Convertible | [1ca9551d4d](https://linux-hardware.org/?probe=1ca9551d4d) | Oct 27, 2022 |
| MSI           | Prestige 14 A10SC           | Notebook    | [263d47772c](https://linux-hardware.org/?probe=263d47772c) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [7d30f96368](https://linux-hardware.org/?probe=7d30f96368) | Oct 27, 2022 |
| Lenovo        | ThinkPad X260 20F5S2WX05    | Notebook    | [710f95eab8](https://linux-hardware.org/?probe=710f95eab8) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d2debd1dab](https://linux-hardware.org/?probe=d2debd1dab) | Oct 26, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [85b4bc70fa](https://linux-hardware.org/?probe=85b4bc70fa) | Oct 26, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6c7c7fa216](https://linux-hardware.org/?probe=6c7c7fa216) | Oct 26, 2022 |
| LincPlus      | P1                          | Notebook    | [cc97e9ec36](https://linux-hardware.org/?probe=cc97e9ec36) | Oct 26, 2022 |
| Lenovo        | 1048 SDK0Q40104 WIN 3915... | Desktop     | [2bed8fe9b1](https://linux-hardware.org/?probe=2bed8fe9b1) | Oct 26, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [0a658be9fc](https://linux-hardware.org/?probe=0a658be9fc) | Oct 26, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [d080f0956b](https://linux-hardware.org/?probe=d080f0956b) | Oct 26, 2022 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [958c0a2ae7](https://linux-hardware.org/?probe=958c0a2ae7) | Oct 25, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b35333d9c0](https://linux-hardware.org/?probe=b35333d9c0) | Oct 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [a8c29545e6](https://linux-hardware.org/?probe=a8c29545e6) | Oct 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [6764a6860f](https://linux-hardware.org/?probe=6764a6860f) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [c9123810fd](https://linux-hardware.org/?probe=c9123810fd) | Oct 25, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [0eb9c3ebff](https://linux-hardware.org/?probe=0eb9c3ebff) | Oct 25, 2022 |
| Dell          | Latitude 5500               | Notebook    | [6e1b321740](https://linux-hardware.org/?probe=6e1b321740) | Oct 25, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [29dd6b053b](https://linux-hardware.org/?probe=29dd6b053b) | Oct 25, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [0c63b974e1](https://linux-hardware.org/?probe=0c63b974e1) | Oct 25, 2022 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [10e0a497e9](https://linux-hardware.org/?probe=10e0a497e9) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [88e45a4e65](https://linux-hardware.org/?probe=88e45a4e65) | Oct 25, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [4474edfd79](https://linux-hardware.org/?probe=4474edfd79) | Oct 25, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [1537796302](https://linux-hardware.org/?probe=1537796302) | Oct 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b14c37f999](https://linux-hardware.org/?probe=b14c37f999) | Oct 25, 2022 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [91a8a52c4a](https://linux-hardware.org/?probe=91a8a52c4a) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Core ... | Desktop     | [601e080563](https://linux-hardware.org/?probe=601e080563) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [42647c28ba](https://linux-hardware.org/?probe=42647c28ba) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [e4d7dc5f38](https://linux-hardware.org/?probe=e4d7dc5f38) | Oct 25, 2022 |
| System76      | Galago UltraPro             | Notebook    | [caf6a992bb](https://linux-hardware.org/?probe=caf6a992bb) | Oct 24, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ad6b09bddc](https://linux-hardware.org/?probe=ad6b09bddc) | Oct 24, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [44375f0b06](https://linux-hardware.org/?probe=44375f0b06) | Oct 24, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [184139e7bc](https://linux-hardware.org/?probe=184139e7bc) | Oct 24, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [3f6368ca5a](https://linux-hardware.org/?probe=3f6368ca5a) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [95ad909dc8](https://linux-hardware.org/?probe=95ad909dc8) | Oct 24, 2022 |
| HP            | 3048h                       | Desktop     | [3c3f7eda5e](https://linux-hardware.org/?probe=3c3f7eda5e) | Oct 24, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [aea737fcab](https://linux-hardware.org/?probe=aea737fcab) | Oct 24, 2022 |
| ASRock        | X370 Gaming K4              | Desktop     | [5658dbff1b](https://linux-hardware.org/?probe=5658dbff1b) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [0ca2dff493](https://linux-hardware.org/?probe=0ca2dff493) | Oct 24, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [2a57a65990](https://linux-hardware.org/?probe=2a57a65990) | Oct 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5010a8ef47](https://linux-hardware.org/?probe=5010a8ef47) | Oct 24, 2022 |
| Dell          | Latitude E6420              | Notebook    | [eb53f0d580](https://linux-hardware.org/?probe=eb53f0d580) | Oct 24, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [5a928ace3b](https://linux-hardware.org/?probe=5a928ace3b) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8922b0767c](https://linux-hardware.org/?probe=8922b0767c) | Oct 24, 2022 |
| Lenovo        | ThinkPad X240 20AMS56K00    | Notebook    | [efa84f3716](https://linux-hardware.org/?probe=efa84f3716) | Oct 24, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [cb2480b22c](https://linux-hardware.org/?probe=cb2480b22c) | Oct 23, 2022 |
| Acer          | Nitro AN515-46              | Notebook    | [846cfe5273](https://linux-hardware.org/?probe=846cfe5273) | Oct 23, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b9e4b934ee](https://linux-hardware.org/?probe=b9e4b934ee) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [22ea226b97](https://linux-hardware.org/?probe=22ea226b97) | Oct 23, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [41dce71fbf](https://linux-hardware.org/?probe=41dce71fbf) | Oct 23, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [22a96186fa](https://linux-hardware.org/?probe=22a96186fa) | Oct 23, 2022 |
| Dell          | Inspiron 1564               | Notebook    | [754b4a0f04](https://linux-hardware.org/?probe=754b4a0f04) | Oct 23, 2022 |
| HP            | Notebook                    | Notebook    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | 86EE                        | All in one  | [4c631cdc18](https://linux-hardware.org/?probe=4c631cdc18) | Oct 22, 2022 |
| HP            | Notebook                    | Notebook    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [b42893c91e](https://linux-hardware.org/?probe=b42893c91e) | Oct 22, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [b633b478aa](https://linux-hardware.org/?probe=b633b478aa) | Oct 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b7ad660d88](https://linux-hardware.org/?probe=b7ad660d88) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [312828c6a3](https://linux-hardware.org/?probe=312828c6a3) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [9cfe9f3c51](https://linux-hardware.org/?probe=9cfe9f3c51) | Oct 22, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [0e07990bda](https://linux-hardware.org/?probe=0e07990bda) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [27c047341d](https://linux-hardware.org/?probe=27c047341d) | Oct 21, 2022 |
| Purism        | Librem 13 v2                | Notebook    | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| Unknown       | X79                         | Desktop     | [fd8f23bc70](https://linux-hardware.org/?probe=fd8f23bc70) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| Google        | Swanky                      | Notebook    | [19efb3ecc5](https://linux-hardware.org/?probe=19efb3ecc5) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| ASUSTek       | Q550LF                      | Notebook    | [0d24151944](https://linux-hardware.org/?probe=0d24151944) | Oct 21, 2022 |
| Itautec       | Infoway N8755               | Notebook    | [7eaba382a5](https://linux-hardware.org/?probe=7eaba382a5) | Oct 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| Acer          | One S1003                   | Tablet      | [304c23119d](https://linux-hardware.org/?probe=304c23119d) | Oct 20, 2022 |
| Lenovo        | B560                        | Notebook    | [3a61700f49](https://linux-hardware.org/?probe=3a61700f49) | Oct 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [33a4634aab](https://linux-hardware.org/?probe=33a4634aab) | Oct 20, 2022 |
| Dell          | Inspiron 7460               | Notebook    | [879fabd350](https://linux-hardware.org/?probe=879fabd350) | Oct 20, 2022 |
| Gigabyte      | 990FXA-UD5 R5               | Desktop     | [f03f1bb041](https://linux-hardware.org/?probe=f03f1bb041) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | Notebook    | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f966d5d584](https://linux-hardware.org/?probe=f966d5d584) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [e3265d4cdc](https://linux-hardware.org/?probe=e3265d4cdc) | Oct 20, 2022 |
| HP            | 8433 11                     | Desktop     | [7e28f54181](https://linux-hardware.org/?probe=7e28f54181) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f91d8722f9](https://linux-hardware.org/?probe=f91d8722f9) | Oct 20, 2022 |
| Dell          | Precision 5510              | Notebook    | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9594fcc1e0](https://linux-hardware.org/?probe=9594fcc1e0) | Oct 20, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [4c27c4945c](https://linux-hardware.org/?probe=4c27c4945c) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [d0dcb7e6e3](https://linux-hardware.org/?probe=d0dcb7e6e3) | Oct 20, 2022 |
| NZXT          | N7 B550                     | Desktop     | [f699b7e1d2](https://linux-hardware.org/?probe=f699b7e1d2) | Oct 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [866d0f49a2](https://linux-hardware.org/?probe=866d0f49a2) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| Framework     | Laptop                      | Notebook    | [ade55fca33](https://linux-hardware.org/?probe=ade55fca33) | Oct 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [76c0902958](https://linux-hardware.org/?probe=76c0902958) | Oct 19, 2022 |
| Gigabyte      | P67A-UD3                    | Desktop     | [96b72bfa8a](https://linux-hardware.org/?probe=96b72bfa8a) | Oct 19, 2022 |
| Framework     | Laptop                      | Notebook    | [57af01b405](https://linux-hardware.org/?probe=57af01b405) | Oct 19, 2022 |
| Shuttle       | FH67H                       | Desktop     | [6679449225](https://linux-hardware.org/?probe=6679449225) | Oct 19, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [980d0d7bb2](https://linux-hardware.org/?probe=980d0d7bb2) | Oct 19, 2022 |
| Dell          | Precision 7760              | Notebook    | [a5ab2793ae](https://linux-hardware.org/?probe=a5ab2793ae) | Oct 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [aeedc0bfd0](https://linux-hardware.org/?probe=aeedc0bfd0) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [71734a9abe](https://linux-hardware.org/?probe=71734a9abe) | Oct 19, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [8665ee6ba6](https://linux-hardware.org/?probe=8665ee6ba6) | Oct 19, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [d267c64062](https://linux-hardware.org/?probe=d267c64062) | Oct 19, 2022 |
| Lenovo        | Yoga 900-13ISK2 80UE        | Notebook    | [efadc96c65](https://linux-hardware.org/?probe=efadc96c65) | Oct 19, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [41d2e6298d](https://linux-hardware.org/?probe=41d2e6298d) | Oct 19, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [eab0779b74](https://linux-hardware.org/?probe=eab0779b74) | Oct 19, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [95a75ab35b](https://linux-hardware.org/?probe=95a75ab35b) | Oct 19, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [495c7fdc3d](https://linux-hardware.org/?probe=495c7fdc3d) | Oct 18, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [28a1d15220](https://linux-hardware.org/?probe=28a1d15220) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [aaa41de825](https://linux-hardware.org/?probe=aaa41de825) | Oct 18, 2022 |
| Lenovo        | B560                        | Notebook    | [717af973da](https://linux-hardware.org/?probe=717af973da) | Oct 18, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| MSI           | Summit E16Flip A11UCT       | Notebook    | [f1ec40e34d](https://linux-hardware.org/?probe=f1ec40e34d) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [9e1f6ae49e](https://linux-hardware.org/?probe=9e1f6ae49e) | Oct 17, 2022 |
| Dell          | Latitude 9420               | Convertible | [319c3b9f03](https://linux-hardware.org/?probe=319c3b9f03) | Oct 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7f9219a85f](https://linux-hardware.org/?probe=7f9219a85f) | Oct 17, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2fd734cbfb](https://linux-hardware.org/?probe=2fd734cbfb) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [f93d1bc535](https://linux-hardware.org/?probe=f93d1bc535) | Oct 17, 2022 |
| Dell          | Inspiron 13 5320            | Notebook    | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| Notebook      | W230SS                      | Notebook    | [abb5e7fda8](https://linux-hardware.org/?probe=abb5e7fda8) | Oct 16, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [50fe9fcad5](https://linux-hardware.org/?probe=50fe9fcad5) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [f98ff2b890](https://linux-hardware.org/?probe=f98ff2b890) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [f20a72be72](https://linux-hardware.org/?probe=f20a72be72) | Oct 16, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [77c8619d03](https://linux-hardware.org/?probe=77c8619d03) | Oct 16, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c78fae026e](https://linux-hardware.org/?probe=c78fae026e) | Oct 16, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0cceedcb07](https://linux-hardware.org/?probe=0cceedcb07) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [dce51f4ce7](https://linux-hardware.org/?probe=dce51f4ce7) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | Notebook    | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [156e3942e5](https://linux-hardware.org/?probe=156e3942e5) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [77f04d4628](https://linux-hardware.org/?probe=77f04d4628) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [ee436e327b](https://linux-hardware.org/?probe=ee436e327b) | Oct 16, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [86e01f1479](https://linux-hardware.org/?probe=86e01f1479) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8557c8b501](https://linux-hardware.org/?probe=8557c8b501) | Oct 15, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7979753fa9](https://linux-hardware.org/?probe=7979753fa9) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab212a80b4](https://linux-hardware.org/?probe=ab212a80b4) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [e1bc46388d](https://linux-hardware.org/?probe=e1bc46388d) | Oct 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49821787e4](https://linux-hardware.org/?probe=49821787e4) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6de814388c](https://linux-hardware.org/?probe=6de814388c) | Oct 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1200f4104f](https://linux-hardware.org/?probe=1200f4104f) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [f9c2c298c4](https://linux-hardware.org/?probe=f9c2c298c4) | Oct 14, 2022 |
| Acer          | Spin SP315-51               | Convertible | [28103297c2](https://linux-hardware.org/?probe=28103297c2) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2fb7882f4a](https://linux-hardware.org/?probe=2fb7882f4a) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [60b21aed9a](https://linux-hardware.org/?probe=60b21aed9a) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | Notebook    | [38739fd54f](https://linux-hardware.org/?probe=38739fd54f) | Oct 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a6083f4dfe](https://linux-hardware.org/?probe=a6083f4dfe) | Oct 13, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [47394cb2b5](https://linux-hardware.org/?probe=47394cb2b5) | Oct 13, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [0c7961c445](https://linux-hardware.org/?probe=0c7961c445) | Oct 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [7af879de72](https://linux-hardware.org/?probe=7af879de72) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [4a4b8d42fc](https://linux-hardware.org/?probe=4a4b8d42fc) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0d2949fd3](https://linux-hardware.org/?probe=d0d2949fd3) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [f20c990c1f](https://linux-hardware.org/?probe=f20c990c1f) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [0355b3f7b8](https://linux-hardware.org/?probe=0355b3f7b8) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | Desktop     | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [11f3146366](https://linux-hardware.org/?probe=11f3146366) | Oct 11, 2022 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [71c926fc14](https://linux-hardware.org/?probe=71c926fc14) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | Notebook    | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [5caff1861e](https://linux-hardware.org/?probe=5caff1861e) | Oct 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [cae3279751](https://linux-hardware.org/?probe=cae3279751) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e2d9db1022](https://linux-hardware.org/?probe=e2d9db1022) | Oct 10, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| ASRock        | X570 PG Velocita            | Desktop     | [ec3a819326](https://linux-hardware.org/?probe=ec3a819326) | Oct 10, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [59f6b7653c](https://linux-hardware.org/?probe=59f6b7653c) | Oct 10, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| Intel         | DG41TY AAE47335-302         | Desktop     | [c0d07ec775](https://linux-hardware.org/?probe=c0d07ec775) | Oct 10, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [6f95e1591a](https://linux-hardware.org/?probe=6f95e1591a) | Oct 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [6c2f880759](https://linux-hardware.org/?probe=6c2f880759) | Oct 09, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5d882bd47f](https://linux-hardware.org/?probe=5d882bd47f) | Oct 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [edb6e4180f](https://linux-hardware.org/?probe=edb6e4180f) | Oct 09, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [6a56a66eae](https://linux-hardware.org/?probe=6a56a66eae) | Oct 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [4aa8b37ac5](https://linux-hardware.org/?probe=4aa8b37ac5) | Oct 09, 2022 |
| Framework     | Laptop                      | Notebook    | [3d25e7f96c](https://linux-hardware.org/?probe=3d25e7f96c) | Oct 09, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [01abf75c2e](https://linux-hardware.org/?probe=01abf75c2e) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [30ff2d0e8f](https://linux-hardware.org/?probe=30ff2d0e8f) | Oct 09, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [19ad61d9c7](https://linux-hardware.org/?probe=19ad61d9c7) | Oct 09, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [cc8b98a2ff](https://linux-hardware.org/?probe=cc8b98a2ff) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f4a711f6a](https://linux-hardware.org/?probe=0f4a711f6a) | Oct 08, 2022 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | Notebook    | [3aee91df8c](https://linux-hardware.org/?probe=3aee91df8c) | Oct 08, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [126b7b85f2](https://linux-hardware.org/?probe=126b7b85f2) | Oct 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d968cc61a](https://linux-hardware.org/?probe=3d968cc61a) | Oct 08, 2022 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [9836cb655c](https://linux-hardware.org/?probe=9836cb655c) | Oct 08, 2022 |
| HP            | 3647h                       | Desktop     | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [973605d3af](https://linux-hardware.org/?probe=973605d3af) | Oct 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [74f6e9db69](https://linux-hardware.org/?probe=74f6e9db69) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8895a815c6](https://linux-hardware.org/?probe=8895a815c6) | Oct 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [812ed8c396](https://linux-hardware.org/?probe=812ed8c396) | Oct 07, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [26dfdb5aed](https://linux-hardware.org/?probe=26dfdb5aed) | Oct 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [d67006c592](https://linux-hardware.org/?probe=d67006c592) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [08e98e28c2](https://linux-hardware.org/?probe=08e98e28c2) | Oct 07, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Dell          | Latitude 5580               | Notebook    | [4bcae73c95](https://linux-hardware.org/?probe=4bcae73c95) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [d5247cbbc3](https://linux-hardware.org/?probe=d5247cbbc3) | Oct 06, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Dell          | Latitude 5400               | Notebook    | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [17d5aa4f87](https://linux-hardware.org/?probe=17d5aa4f87) | Oct 06, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [c8c6a428db](https://linux-hardware.org/?probe=c8c6a428db) | Oct 06, 2022 |
| ASUSTek       | X550LA                      | Notebook    | [c0c98c2051](https://linux-hardware.org/?probe=c0c98c2051) | Oct 06, 2022 |
| HP            | 0AECh D                     | Desktop     | [8fd13e9017](https://linux-hardware.org/?probe=8fd13e9017) | Oct 06, 2022 |
| MSI           | X370 SLI PLUS               | Desktop     | [ea7dc6a41a](https://linux-hardware.org/?probe=ea7dc6a41a) | Oct 06, 2022 |
| HP            | 15                          | Notebook    | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [20b6b5f918](https://linux-hardware.org/?probe=20b6b5f918) | Oct 06, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [b0fa4fab35](https://linux-hardware.org/?probe=b0fa4fab35) | Oct 05, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [7f2b63950d](https://linux-hardware.org/?probe=7f2b63950d) | Oct 05, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [368530a660](https://linux-hardware.org/?probe=368530a660) | Oct 05, 2022 |
| Dell          | Latitude 5400               | Notebook    | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [77176ee82a](https://linux-hardware.org/?probe=77176ee82a) | Oct 05, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [7590ca8bff](https://linux-hardware.org/?probe=7590ca8bff) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [3d5136540e](https://linux-hardware.org/?probe=3d5136540e) | Oct 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [b78c69e096](https://linux-hardware.org/?probe=b78c69e096) | Oct 04, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [dc80de33ee](https://linux-hardware.org/?probe=dc80de33ee) | Oct 04, 2022 |
| HP            | Laptop                      | Notebook    | [3a26ec874f](https://linux-hardware.org/?probe=3a26ec874f) | Oct 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [07d4cf95ec](https://linux-hardware.org/?probe=07d4cf95ec) | Oct 04, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [3a515cdda0](https://linux-hardware.org/?probe=3a515cdda0) | Oct 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2f9e023d1e](https://linux-hardware.org/?probe=2f9e023d1e) | Oct 03, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [45a46cdb72](https://linux-hardware.org/?probe=45a46cdb72) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [48e867fba8](https://linux-hardware.org/?probe=48e867fba8) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [92aca0d081](https://linux-hardware.org/?probe=92aca0d081) | Oct 02, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [253e143d94](https://linux-hardware.org/?probe=253e143d94) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [8f24127ac0](https://linux-hardware.org/?probe=8f24127ac0) | Oct 02, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [de64a1e585](https://linux-hardware.org/?probe=de64a1e585) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6121fee541](https://linux-hardware.org/?probe=6121fee541) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| Dell          | Inspiron 17-7779            | Notebook    | [5bd534e938](https://linux-hardware.org/?probe=5bd534e938) | Oct 02, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6d8ed9f182](https://linux-hardware.org/?probe=6d8ed9f182) | Oct 02, 2022 |
| ASRock        | X570 Phantom Gaming 4S      | Desktop     | [2215129a47](https://linux-hardware.org/?probe=2215129a47) | Oct 02, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [ee22a244e2](https://linux-hardware.org/?probe=ee22a244e2) | Oct 01, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | Notebook    | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [1fade0f247](https://linux-hardware.org/?probe=1fade0f247) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [d60b15ea91](https://linux-hardware.org/?probe=d60b15ea91) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f64b9ed3d](https://linux-hardware.org/?probe=9f64b9ed3d) | Oct 01, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [49bd2b0248](https://linux-hardware.org/?probe=49bd2b0248) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d5407763a0](https://linux-hardware.org/?probe=d5407763a0) | Sep 30, 2022 |
| Dell          | Latitude E4300              | Notebook    | [a860d9a446](https://linux-hardware.org/?probe=a860d9a446) | Sep 30, 2022 |
| GPD           | G1621-02                    | Notebook    | [6ae9fc596e](https://linux-hardware.org/?probe=6ae9fc596e) | Sep 30, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [162334ac1e](https://linux-hardware.org/?probe=162334ac1e) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| HP            | ProBook 6570b               | Notebook    | [d9be946342](https://linux-hardware.org/?probe=d9be946342) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [ed76eeb703](https://linux-hardware.org/?probe=ed76eeb703) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b15bae8e77](https://linux-hardware.org/?probe=b15bae8e77) | Sep 30, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [126b8dd3ec](https://linux-hardware.org/?probe=126b8dd3ec) | Sep 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0DK0... | Notebook    | [33353fc67c](https://linux-hardware.org/?probe=33353fc67c) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [d2a3575975](https://linux-hardware.org/?probe=d2a3575975) | Sep 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [9015ce1da8](https://linux-hardware.org/?probe=9015ce1da8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2c6b161d0f](https://linux-hardware.org/?probe=2c6b161d0f) | Sep 29, 2022 |
| Avell High... | A60 MUV                     | Notebook    | [888e375356](https://linux-hardware.org/?probe=888e375356) | Sep 29, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [18afdc2116](https://linux-hardware.org/?probe=18afdc2116) | Sep 29, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [99f729e814](https://linux-hardware.org/?probe=99f729e814) | Sep 29, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [7325511d27](https://linux-hardware.org/?probe=7325511d27) | Sep 29, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [5ec700ea0a](https://linux-hardware.org/?probe=5ec700ea0a) | Sep 29, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [c6ae2f8a45](https://linux-hardware.org/?probe=c6ae2f8a45) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [067b155d9b](https://linux-hardware.org/?probe=067b155d9b) | Sep 29, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [058aa145d3](https://linux-hardware.org/?probe=058aa145d3) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [a674def12d](https://linux-hardware.org/?probe=a674def12d) | Sep 29, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [23c809d2a7](https://linux-hardware.org/?probe=23c809d2a7) | Sep 29, 2022 |
| Dell          | Precision 7550              | Notebook    | [75f2949521](https://linux-hardware.org/?probe=75f2949521) | Sep 29, 2022 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | Notebook    | [9ac63cdce6](https://linux-hardware.org/?probe=9ac63cdce6) | Sep 29, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [fbba79fc43](https://linux-hardware.org/?probe=fbba79fc43) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [d137298cb5](https://linux-hardware.org/?probe=d137298cb5) | Sep 28, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [b30346135b](https://linux-hardware.org/?probe=b30346135b) | Sep 28, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [513d236a1f](https://linux-hardware.org/?probe=513d236a1f) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | Notebook    | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [89253de6f0](https://linux-hardware.org/?probe=89253de6f0) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| Medion        | Unknown                     | Notebook    | [821c3c8fed](https://linux-hardware.org/?probe=821c3c8fed) | Sep 28, 2022 |
| Alienware     | 14                          | Notebook    | [2d46ecc50e](https://linux-hardware.org/?probe=2d46ecc50e) | Sep 28, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a4b44081c2](https://linux-hardware.org/?probe=a4b44081c2) | Sep 27, 2022 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a6347449b3](https://linux-hardware.org/?probe=a6347449b3) | Sep 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| MSI           | GS66 Stealth 10SGS          | Notebook    | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [5c61df4d20](https://linux-hardware.org/?probe=5c61df4d20) | Sep 27, 2022 |
| Dell          | 0YGYJY A01                  | Desktop     | [73e69debd9](https://linux-hardware.org/?probe=73e69debd9) | Sep 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6677830ce4](https://linux-hardware.org/?probe=6677830ce4) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [3d86bcf1b7](https://linux-hardware.org/?probe=3d86bcf1b7) | Sep 27, 2022 |
| HP            | 829A                        | Mini pc     | [1e26c7813f](https://linux-hardware.org/?probe=1e26c7813f) | Sep 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c60d7e3375](https://linux-hardware.org/?probe=c60d7e3375) | Sep 27, 2022 |
| Gigabyte      | Z690I AORUS ULTRA DDR4      | Desktop     | [7af967061b](https://linux-hardware.org/?probe=7af967061b) | Sep 27, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [4308420b28](https://linux-hardware.org/?probe=4308420b28) | Sep 27, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [5535b3367e](https://linux-hardware.org/?probe=5535b3367e) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6373bf42ef](https://linux-hardware.org/?probe=6373bf42ef) | Sep 26, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [ed657bfbb6](https://linux-hardware.org/?probe=ed657bfbb6) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f1d78ca455](https://linux-hardware.org/?probe=f1d78ca455) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [d644aedbdd](https://linux-hardware.org/?probe=d644aedbdd) | Sep 26, 2022 |
| MSI           | GT72 6QE                    | Notebook    | [d739812ce7](https://linux-hardware.org/?probe=d739812ce7) | Sep 26, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [7ec3a25453](https://linux-hardware.org/?probe=7ec3a25453) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [6d8fc869e4](https://linux-hardware.org/?probe=6d8fc869e4) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [52a86d0701](https://linux-hardware.org/?probe=52a86d0701) | Sep 26, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [683aa83ea4](https://linux-hardware.org/?probe=683aa83ea4) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [64fd780b2f](https://linux-hardware.org/?probe=64fd780b2f) | Sep 26, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d557cdbe1c](https://linux-hardware.org/?probe=d557cdbe1c) | Sep 26, 2022 |
| HP            | Laptop                      | Notebook    | [be59fc7a97](https://linux-hardware.org/?probe=be59fc7a97) | Sep 26, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f8b76ec5f4](https://linux-hardware.org/?probe=f8b76ec5f4) | Sep 25, 2022 |
| AZW           | SEi                         | Notebook    | [063c3cc52e](https://linux-hardware.org/?probe=063c3cc52e) | Sep 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [e9205da026](https://linux-hardware.org/?probe=e9205da026) | Sep 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [be1d17baa4](https://linux-hardware.org/?probe=be1d17baa4) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [982d41c1eb](https://linux-hardware.org/?probe=982d41c1eb) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [82b73270ca](https://linux-hardware.org/?probe=82b73270ca) | Sep 25, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [b26f7bf9f5](https://linux-hardware.org/?probe=b26f7bf9f5) | Sep 25, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [a5d5950e29](https://linux-hardware.org/?probe=a5d5950e29) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [a1f261d09d](https://linux-hardware.org/?probe=a1f261d09d) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [f5e9524bff](https://linux-hardware.org/?probe=f5e9524bff) | Sep 25, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [6e7d310781](https://linux-hardware.org/?probe=6e7d310781) | Sep 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [593ef93760](https://linux-hardware.org/?probe=593ef93760) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [4f9ff1b402](https://linux-hardware.org/?probe=4f9ff1b402) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [307a3c2848](https://linux-hardware.org/?probe=307a3c2848) | Sep 24, 2022 |
| ASRock        | Z170M Extreme4              | Desktop     | [bd1e98639b](https://linux-hardware.org/?probe=bd1e98639b) | Sep 24, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [2bdc1228a1](https://linux-hardware.org/?probe=2bdc1228a1) | Sep 24, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [eef9de3daf](https://linux-hardware.org/?probe=eef9de3daf) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [542249f675](https://linux-hardware.org/?probe=542249f675) | Sep 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0170bcbb42](https://linux-hardware.org/?probe=0170bcbb42) | Sep 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [08843e7c7c](https://linux-hardware.org/?probe=08843e7c7c) | Sep 24, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2082a8668b](https://linux-hardware.org/?probe=2082a8668b) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2bb811e308](https://linux-hardware.org/?probe=2bb811e308) | Sep 23, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [c30d8893ca](https://linux-hardware.org/?probe=c30d8893ca) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31f1acf273](https://linux-hardware.org/?probe=31f1acf273) | Sep 23, 2022 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [2e45736b42](https://linux-hardware.org/?probe=2e45736b42) | Sep 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a4ce7c179e](https://linux-hardware.org/?probe=a4ce7c179e) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | Desktop     | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7d69f0c6c6](https://linux-hardware.org/?probe=7d69f0c6c6) | Sep 23, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [337c1097ef](https://linux-hardware.org/?probe=337c1097ef) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [f72f370511](https://linux-hardware.org/?probe=f72f370511) | Sep 23, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [79509e063b](https://linux-hardware.org/?probe=79509e063b) | Sep 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a5e851730c](https://linux-hardware.org/?probe=a5e851730c) | Sep 23, 2022 |
| Acer          | Aspire A715-43G             | Notebook    | [5ecaaef0b1](https://linux-hardware.org/?probe=5ecaaef0b1) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_36/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64       | 177       | 7.45%   |
| 6.0.5-200.fc36.x86_64        | 116       | 4.88%   |
| 5.18.13-200.fc36.x86_64      | 112       | 4.72%   |
| 5.19.16-200.fc36.x86_64      | 95        | 4%      |
| 5.18.11-200.fc36.x86_64      | 90        | 3.79%   |
| 5.19.9-200.fc36.x86_64       | 87        | 3.66%   |
| 5.18.16-200.fc36.x86_64      | 85        | 3.58%   |
| 5.18.5-200.fc36.x86_64       | 75        | 3.16%   |
| 5.17.6-300.fc36.x86_64       | 74        | 3.12%   |
| 5.17.11-300.fc36.x86_64      | 72        | 3.03%   |
| 5.19.8-200.fc36.x86_64       | 67        | 2.82%   |
| 5.19.6-200.fc36.x86_64       | 65        | 2.74%   |
| 5.18.17-200.fc36.x86_64      | 55        | 2.32%   |
| 5.17.13-300.fc36.x86_64      | 54        | 2.27%   |
| 5.19.4-200.fc36.x86_64       | 52        | 2.19%   |
| 5.18.19-200.fc36.x86_64      | 49        | 2.06%   |
| 5.19.15-201.fc36.x86_64      | 48        | 2.02%   |
| 5.19.11-200.fc36.x86_64      | 48        | 2.02%   |
| 5.18.9-200.fc36.x86_64       | 47        | 1.98%   |
| 5.17.12-300.fc36.x86_64      | 47        | 1.98%   |
| 5.18.18-200.fc36.x86_64      | 46        | 1.94%   |
| 5.18.10-200.fc36.x86_64      | 46        | 1.94%   |
| 5.17.8-300.fc36.x86_64       | 44        | 1.85%   |
| 5.19.14-200.fc36.x86_64      | 43        | 1.81%   |
| 5.18.6-200.fc36.x86_64       | 39        | 1.64%   |
| 5.19.13-200.fc36.x86_64      | 38        | 1.6%    |
| 5.19.12-200.fc36.x86_64      | 36        | 1.52%   |
| 5.18.7-200.fc36.x86_64       | 36        | 1.52%   |
| 5.17.7-300.fc36.x86_64       | 33        | 1.39%   |
| 5.17.9-300.fc36.x86_64       | 29        | 1.22%   |
| 5.17.1-300.fc36.x86_64       | 29        | 1.22%   |
| 6.0.7-200.fc36.x86_64        | 25        | 1.05%   |
| 5.17.2-300.fc36.x86_64       | 25        | 1.05%   |
| 5.19.10-200.fc36.x86_64      | 21        | 0.88%   |
| 5.17.3-302.fc36.x86_64       | 21        | 0.88%   |
| 5.17.0-0.rc7.116.fc36.x86_64 | 19        | 0.8%    |
| 6.0.8-200.fc36.x86_64        | 17        | 0.72%   |
| 5.18.15-200.fc36.x86_64      | 17        | 0.72%   |
| 6.0.9-200.fc36.x86_64        | 16        | 0.67%   |
| 6.0.15-200.fc36.x86_64       | 15        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.5  | 180       | 7.58%   |
| 6.0.5   | 116       | 4.89%   |
| 5.18.13 | 113       | 4.76%   |
| 5.19.16 | 96        | 4.04%   |
| 5.18.11 | 90        | 3.79%   |
| 5.19.9  | 88        | 3.71%   |
| 5.18.16 | 86        | 3.62%   |
| 5.18.5  | 82        | 3.45%   |
| 5.17.6  | 77        | 3.24%   |
| 5.17.11 | 75        | 3.16%   |
| 5.19.8  | 68        | 2.86%   |
| 5.19.6  | 67        | 2.82%   |
| 5.18.17 | 55        | 2.32%   |
| 5.17.13 | 54        | 2.27%   |
| 5.19.4  | 53        | 2.23%   |
| 5.18.9  | 50        | 2.11%   |
| 5.18.10 | 50        | 2.11%   |
| 5.19.15 | 49        | 2.06%   |
| 5.18.19 | 49        | 2.06%   |
| 5.18.18 | 49        | 2.06%   |
| 5.17.12 | 49        | 2.06%   |
| 5.19.11 | 48        | 2.02%   |
| 5.17.8  | 44        | 1.85%   |
| 5.19.14 | 43        | 1.81%   |
| 5.18.6  | 42        | 1.77%   |
| 5.19.13 | 39        | 1.64%   |
| 5.19.12 | 38        | 1.6%    |
| 5.18.7  | 37        | 1.56%   |
| 5.17.7  | 35        | 1.47%   |
| 5.17.9  | 32        | 1.35%   |
| 5.17.1  | 30        | 1.26%   |
| 5.17.0  | 28        | 1.18%   |
| 5.17.2  | 26        | 1.1%    |
| 6.0.7   | 25        | 1.05%   |
| 5.17.3  | 23        | 0.97%   |
| 5.19.10 | 21        | 0.88%   |
| 6.0.9   | 18        | 0.76%   |
| 6.0.8   | 18        | 0.76%   |
| 5.18.15 | 17        | 0.72%   |
| 5.19.7  | 16        | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.18    | 700       | 30.63%  |
| 5.17    | 644       | 28.18%  |
| 5.19    | 614       | 26.87%  |
| 6.0     | 239       | 10.46%  |
| 6.1     | 40        | 1.75%   |
| 6.2     | 26        | 1.14%   |
| 5.15    | 8         | 0.35%   |
| 5.16    | 7         | 0.31%   |
| 5.14    | 4         | 0.18%   |
| 5.4     | 1         | 0.04%   |
| 5.3     | 1         | 0.04%   |
| 5.11    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2124      | 99.86%  |
| aarch64 | 3         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 1578      | 73.64%  |
| KDE5          | 356       | 16.61%  |
| Unknown       | 53        | 2.47%   |
| XFCE          | 42        | 1.96%   |
| X-Cinnamon    | 30        | 1.4%    |
| Cinnamon      | 22        | 1.03%   |
| MATE          | 18        | 0.84%   |
| i3            | 11        | 0.51%   |
| LXQt          | 8         | 0.37%   |
| GNOME Classic | 8         | 0.37%   |
| sway          | 4         | 0.19%   |
| awesome       | 3         | 0.14%   |
| Deepin        | 2         | 0.09%   |
| Pantheon      | 1         | 0.05%   |
| openbox       | 1         | 0.05%   |
| LXDE          | 1         | 0.05%   |
| KDE:old       | 1         | 0.05%   |
| KDE           | 1         | 0.05%   |
| fluxbox       | 1         | 0.05%   |
| dwm           | 1         | 0.05%   |
| bspwm         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1516      | 70.45%  |
| X11     | 569       | 26.44%  |
| Tty     | 41        | 1.91%   |
| Unknown | 24        | 1.12%   |
| Web     | 2         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1105      | 51.52%  |
| GDM     | 721       | 33.61%  |
| SDDM    | 186       | 8.67%   |
| LightDM | 131       | 6.11%   |
| Ly      | 1         | 0.05%   |
| KDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1142      | 53.56%  |
| en_GB   | 131       | 6.14%   |
| ru_RU   | 126       | 5.91%   |
| it_IT   | 93        | 4.36%   |
| de_DE   | 85        | 3.99%   |
| pt_BR   | 79        | 3.71%   |
| en_AU   | 57        | 2.67%   |
| fr_FR   | 52        | 2.44%   |
| es_ES   | 40        | 1.88%   |
| en_CA   | 38        | 1.78%   |
| pl_PL   | 35        | 1.64%   |
| en_IN   | 26        | 1.22%   |
| es_MX   | 18        | 0.84%   |
| en_NZ   | 14        | 0.66%   |
| cs_CZ   | 11        | 0.52%   |
| tr_TR   | 10        | 0.47%   |
| nl_NL   | 10        | 0.47%   |
| hu_HU   | 10        | 0.47%   |
| nl_BE   | 9         | 0.42%   |
| es_AR   | 9         | 0.42%   |
| es_CL   | 8         | 0.38%   |
| Unknown | 8         | 0.38%   |
| pt_PT   | 7         | 0.33%   |
| zh_CN   | 6         | 0.28%   |
| sv_SE   | 6         | 0.28%   |
| en_IE   | 6         | 0.28%   |
| de_AT   | 6         | 0.28%   |
| ru_UA   | 5         | 0.23%   |
| fr_BE   | 5         | 0.23%   |
| es_CO   | 5         | 0.23%   |
| da_DK   | 5         | 0.23%   |
| ja_JP   | 4         | 0.19%   |
| en_ZA   | 4         | 0.19%   |
| de_CH   | 4         | 0.19%   |
| C       | 4         | 0.19%   |
| nb_NO   | 3         | 0.14%   |
| en_PH   | 3         | 0.14%   |
| en_NL   | 3         | 0.14%   |
| en_IL   | 3         | 0.14%   |
| en_DK   | 3         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1731      | 81%     |
| BIOS | 406       | 19%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 1685      | 79.07%  |
| Ext4    | 386       | 18.11%  |
| Xfs     | 55        | 2.58%   |
| F2fs    | 2         | 0.09%   |
| Zfs     | 1         | 0.05%   |
| Overlay | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1096      | 51.05%  |
| GPT     | 926       | 43.13%  |
| MBR     | 125       | 5.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1896      | 88.52%  |
| Yes       | 246       | 11.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1681      | 78.44%  |
| Yes       | 462       | 21.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 426       | 20.03%  |
| ASUSTek Computer       | 374       | 17.58%  |
| Hewlett-Packard        | 285       | 13.4%   |
| Dell                   | 263       | 12.36%  |
| MSI                    | 146       | 6.86%   |
| Gigabyte Technology    | 136       | 6.39%   |
| Acer                   | 87        | 4.09%   |
| ASRock                 | 66        | 3.1%    |
| Apple                  | 52        | 2.44%   |
| HUAWEI                 | 27        | 1.27%   |
| Intel                  | 21        | 0.99%   |
| Microsoft              | 15        | 0.71%   |
| Samsung Electronics    | 13        | 0.61%   |
| Framework              | 13        | 0.61%   |
| Unknown                | 13        | 0.61%   |
| Toshiba                | 12        | 0.56%   |
| Timi                   | 10        | 0.47%   |
| Sony                   | 10        | 0.47%   |
| Notebook               | 10        | 0.47%   |
| BESSTAR Tech           | 10        | 0.47%   |
| Chuwi                  | 7         | 0.33%   |
| Foxconn                | 6         | 0.28%   |
| TUXEDO                 | 5         | 0.24%   |
| Positivo               | 5         | 0.24%   |
| Huanan                 | 5         | 0.24%   |
| Alienware              | 5         | 0.24%   |
| System76               | 4         | 0.19%   |
| Fujitsu                | 4         | 0.19%   |
| Biostar                | 4         | 0.19%   |
| VALE                   | 3         | 0.14%   |
| Pegatron               | 3         | 0.14%   |
| Panasonic              | 3         | 0.14%   |
| Packard Bell           | 3         | 0.14%   |
| LG Electronics         | 3         | 0.14%   |
| HONOR                  | 3         | 0.14%   |
| GPU Company            | 3         | 0.14%   |
| Google                 | 3         | 0.14%   |
| AZW                    | 3         | 0.14%   |
| Avell High Performance | 3         | 0.14%   |
| Acidanthera            | 3         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 21        | 0.99%   |
| ASUS All Series                        | 14        | 0.66%   |
| Framework Laptop                       | 9         | 0.42%   |
| MSI MS-7C37                            | 8         | 0.38%   |
| MSI MS-7A38                            | 8         | 0.38%   |
| Dell XPS 15 9570                       | 8         | 0.38%   |
| HP Notebook                            | 7         | 0.33%   |
| ASUS ROG STRIX B550-F GAMING           | 7         | 0.33%   |
| MSI MS-7C91                            | 6         | 0.28%   |
| MSI MS-7B86                            | 6         | 0.28%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 6         | 0.28%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 5         | 0.24%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 5         | 0.24%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 5         | 0.24%   |
| HP Pavilion g6                         | 5         | 0.24%   |
| HP EliteBook 8470p                     | 5         | 0.24%   |
| Dell XPS 15 9510                       | 5         | 0.24%   |
| Dell XPS 13 9310                       | 5         | 0.24%   |
| Dell Latitude E6420                    | 5         | 0.24%   |
| ASUS TUF Gaming X570-PLUS              | 5         | 0.24%   |
| ASUS TUF Gaming B550M-PLUS             | 5         | 0.24%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 5         | 0.24%   |
| ASUS ROG STRIX X570-F GAMING           | 5         | 0.24%   |
| Apple MacBookPro12,1                   | 5         | 0.24%   |
| MSI MS-7B79                            | 4         | 0.19%   |
| Lenovo ThinkBook 15-IIL 20SM           | 4         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 4         | 0.19%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 4         | 0.19%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx   | 4         | 0.19%   |
| Gigabyte B550I AORUS PRO AX            | 4         | 0.19%   |
| Gigabyte B450M DS3H                    | 4         | 0.19%   |
| Gigabyte B450 AORUS ELITE              | 4         | 0.19%   |
| Framework Laptop (12th Gen Intel Core) | 4         | 0.19%   |
| Dell XPS 15 9520                       | 4         | 0.19%   |
| Dell OptiPlex 9020                     | 4         | 0.19%   |
| ASUS TUF Gaming B550-PLUS              | 4         | 0.19%   |
| ASUS ROG Strix G513QY_G513QY           | 4         | 0.19%   |
| ASUS ROG CROSSHAIR VIII HERO           | 4         | 0.19%   |
| ASUS PRIME Z370-A                      | 4         | 0.19%   |
| ASUS PRIME B450-PLUS                   | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 206       | 9.69%   |
| ASUS ROG           | 98        | 4.61%   |
| Lenovo IdeaPad     | 90        | 4.23%   |
| Dell Inspiron      | 73        | 3.43%   |
| Dell XPS           | 62        | 2.91%   |
| Dell Latitude      | 57        | 2.68%   |
| HP Pavilion        | 52        | 2.44%   |
| ASUS PRIME         | 48        | 2.26%   |
| Acer Aspire        | 42        | 1.97%   |
| ASUS TUF           | 40        | 1.88%   |
| HP EliteBook       | 36        | 1.69%   |
| ASUS VivoBook      | 35        | 1.65%   |
| HP Laptop          | 33        | 1.55%   |
| Dell Precision     | 30        | 1.41%   |
| HP ProBook         | 29        | 1.36%   |
| HP ENVY            | 29        | 1.36%   |
| Lenovo Yoga        | 26        | 1.22%   |
| Lenovo ThinkBook   | 24        | 1.13%   |
| Unknown            | 21        | 0.99%   |
| Lenovo Legion      | 20        | 0.94%   |
| Dell OptiPlex      | 18        | 0.85%   |
| ASUS ASUS          | 16        | 0.75%   |
| Microsoft Surface  | 15        | 0.71%   |
| ASUS All           | 14        | 0.66%   |
| HP ZBook           | 13        | 0.61%   |
| Framework Laptop   | 13        | 0.61%   |
| Acer Nitro         | 13        | 0.61%   |
| Lenovo IdeaPadFlex | 12        | 0.56%   |
| Dell Vostro        | 12        | 0.56%   |
| HP Compaq          | 11        | 0.52%   |
| Toshiba Satellite  | 10        | 0.47%   |
| Lenovo ThinkCentre | 10        | 0.47%   |
| Acer Swift         | 10        | 0.47%   |
| MSI Modern         | 9         | 0.42%   |
| MSI MS-7C37        | 8         | 0.38%   |
| MSI MS-7A38        | 8         | 0.38%   |
| Gigabyte B450      | 8         | 0.38%   |
| ASUS ZenBook       | 8         | 0.38%   |
| HP ProDesk         | 7         | 0.33%   |
| HP Notebook        | 7         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 375       | 17.63%  |
| 2020    | 334       | 15.7%   |
| 2019    | 244       | 11.47%  |
| 2018    | 211       | 9.92%   |
| 2017    | 138       | 6.49%   |
| 2022    | 132       | 6.21%   |
| 2012    | 108       | 5.08%   |
| 2014    | 102       | 4.8%    |
| 2016    | 100       | 4.7%    |
| 2013    | 99        | 4.65%   |
| 2015    | 98        | 4.61%   |
| 2011    | 74        | 3.48%   |
| 2010    | 41        | 1.93%   |
| 2009    | 31        | 1.46%   |
| 2008    | 23        | 1.08%   |
| 2007    | 9         | 0.42%   |
| 2006    | 5         | 0.24%   |
| 2023    | 1         | 0.05%   |
| 2005    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1231      | 57.87%  |
| Desktop        | 683       | 32.11%  |
| Convertible    | 117       | 5.5%    |
| Tablet         | 34        | 1.6%    |
| Mini pc        | 29        | 1.36%   |
| All in one     | 24        | 1.13%   |
| Server         | 6         | 0.28%   |
| System on chip | 3         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1750      | 81.93%  |
| Enabled  | 386       | 18.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2121      | 99.72%  |
| Yes  | 6         | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 541       | 25.27%  |
| 4.01-8.0        | 496       | 23.17%  |
| 8.01-16.0       | 403       | 18.82%  |
| 32.01-64.0      | 364       | 17%     |
| 3.01-4.0        | 170       | 7.94%   |
| 64.01-256.0     | 95        | 4.44%   |
| 24.01-32.0      | 38        | 1.77%   |
| 1.01-2.0        | 27        | 1.26%   |
| 2.01-3.0        | 5         | 0.23%   |
| More than 256.0 | 1         | 0.05%   |
| 0.51-1.0        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 682       | 30.22%  |
| 2.01-3.0    | 574       | 25.43%  |
| 3.01-4.0    | 521       | 23.08%  |
| 1.01-2.0    | 229       | 10.15%  |
| 8.01-16.0   | 188       | 8.33%   |
| 16.01-24.0  | 24        | 1.06%   |
| 0.51-1.0    | 22        | 0.97%   |
| 24.01-32.0  | 9         | 0.4%    |
| 0.01-0.5    | 4         | 0.18%   |
| 32.01-64.0  | 3         | 0.13%   |
| 64.01-256.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1239      | 57.52%  |
| 2      | 571       | 26.51%  |
| 3      | 183       | 8.5%    |
| 4      | 83        | 3.85%   |
| 5      | 32        | 1.49%   |
| 6      | 21        | 0.97%   |
| 7      | 11        | 0.51%   |
| 0      | 7         | 0.32%   |
| 11     | 2         | 0.09%   |
| 10     | 2         | 0.09%   |
| 13     | 1         | 0.05%   |
| 12     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1689      | 79.18%  |
| Yes       | 444       | 20.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1633      | 76.52%  |
| No        | 501       | 23.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1789      | 84.03%  |
| No        | 340       | 15.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1570      | 73.54%  |
| No        | 565       | 26.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 444       | 20.8%   |
| Germany     | 159       | 7.45%   |
| Russia      | 150       | 7.03%   |
| Italy       | 150       | 7.03%   |
| Brazil      | 119       | 5.57%   |
| UK          | 69        | 3.23%   |
| India       | 69        | 3.23%   |
| France      | 66        | 3.09%   |
| Australia   | 65        | 3.04%   |
| Poland      | 60        | 2.81%   |
| Spain       | 55        | 2.58%   |
| Netherlands | 53        | 2.48%   |
| Canada      | 48        | 2.25%   |
| Mexico      | 43        | 2.01%   |
| Turkey      | 34        | 1.59%   |
| Belgium     | 33        | 1.55%   |
| Argentina   | 24        | 1.12%   |
| Sweden      | 23        | 1.08%   |
| Indonesia   | 21        | 0.98%   |
| Hungary     | 20        | 0.94%   |
| Czechia     | 20        | 0.94%   |
| Finland     | 19        | 0.89%   |
| Portugal    | 17        | 0.8%    |
| Norway      | 17        | 0.8%    |
| Switzerland | 16        | 0.75%   |
| Belarus     | 15        | 0.7%    |
| Austria     | 15        | 0.7%    |
| Romania     | 14        | 0.66%   |
| New Zealand | 12        | 0.56%   |
| Philippines | 11        | 0.52%   |
| Israel      | 11        | 0.52%   |
| Denmark     | 11        | 0.52%   |
| Colombia    | 11        | 0.52%   |
| Japan       | 10        | 0.47%   |
| Ireland     | 10        | 0.47%   |
| Chile       | 10        | 0.47%   |
| Greece      | 8         | 0.37%   |
| China       | 8         | 0.37%   |
| Ukraine     | 7         | 0.33%   |
| Kenya       | 7         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 43        | 1.96%   |
| St Petersburg  | 28        | 1.28%   |
| Sao Paulo      | 20        | 0.91%   |
| Melbourne      | 20        | 0.91%   |
| Warsaw         | 19        | 0.87%   |
| Berlin         | 19        | 0.87%   |
| Brisbane       | 16        | 0.73%   |
| Rome           | 15        | 0.68%   |
| Milan          | 15        | 0.68%   |
| Istanbul       | 13        | 0.59%   |
| Chicago        | 13        | 0.59%   |
| Sydney         | 12        | 0.55%   |
| Paris          | 11        | 0.5%    |
| Minsk          | 11        | 0.5%    |
| Mexico City    | 11        | 0.5%    |
| Helsinki       | 11        | 0.5%    |
| Prague         | 9         | 0.41%   |
| New York       | 9         | 0.41%   |
| Munich         | 9         | 0.41%   |
| Launceston     | 9         | 0.41%   |
| Budapest       | 9         | 0.41%   |
| Auckland       | 9         | 0.41%   |
| Verona         | 8         | 0.36%   |
| Oslo           | 8         | 0.36%   |
| Kolkata        | 8         | 0.36%   |
| Bengaluru      | 8         | 0.36%   |
| Stockholm      | 7         | 0.32%   |
| Los Angeles    | 7         | 0.32%   |
| Jakarta        | 7         | 0.32%   |
| Izmir          | 7         | 0.32%   |
| Bucharest      | 7         | 0.32%   |
| Amsterdam      | 7         | 0.32%   |
| Vienna         | 6         | 0.27%   |
| Santiago       | 6         | 0.27%   |
| San Jose       | 6         | 0.27%   |
| Samara         | 6         | 0.27%   |
| Rio de Janeiro | 6         | 0.27%   |
| Porto Alegre   | 6         | 0.27%   |
| Novosibirsk    | 6         | 0.27%   |
| Nairobi        | 6         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 629       | 862    | 19.55%  |
| WDC                       | 410       | 586    | 12.74%  |
| Seagate                   | 336       | 475    | 10.44%  |
| SanDisk                   | 212       | 255    | 6.59%   |
| Kingston                  | 184       | 211    | 5.72%   |
| Toshiba                   | 159       | 192    | 4.94%   |
| SK hynix                  | 130       | 144    | 4.04%   |
| Crucial                   | 129       | 166    | 4.01%   |
| Intel                     | 105       | 141    | 3.26%   |
| Unknown                   | 101       | 124    | 3.14%   |
| Micron Technology         | 91        | 102    | 2.83%   |
| KIOXIA                    | 50        | 65     | 1.55%   |
| A-DATA Technology         | 47        | 51     | 1.46%   |
| Phison                    | 46        | 49     | 1.43%   |
| Hitachi                   | 41        | 56     | 1.27%   |
| HGST                      | 36        | 43     | 1.12%   |
| China                     | 27        | 31     | 0.84%   |
| Apple                     | 27        | 29     | 0.84%   |
| Silicon Motion            | 26        | 26     | 0.81%   |
| Micron/Crucial Technology | 21        | 26     | 0.65%   |
| SPCC                      | 19        | 24     | 0.59%   |
| PNY                       | 19        | 23     | 0.59%   |
| Unknown                   | 19        | 19     | 0.59%   |
| Phison Electronics        | 18        | 20     | 0.56%   |
| Patriot                   | 17        | 19     | 0.53%   |
| XPG                       | 14        | 18     | 0.44%   |
| LITEON                    | 14        | 14     | 0.44%   |
| ADATA Technology          | 12        | 13     | 0.37%   |
| SABRENT                   | 11        | 13     | 0.34%   |
| Netac                     | 11        | 11     | 0.34%   |
| UMIS                      | 10        | 14     | 0.31%   |
| Transcend                 | 10        | 13     | 0.31%   |
| Intenso                   | 10        | 12     | 0.31%   |
| Corsair                   | 10        | 13     | 0.31%   |
| Team                      | 9         | 12     | 0.28%   |
| SSSTC                     | 8         | 8      | 0.25%   |
| Gigabyte Technology       | 8         | 12     | 0.25%   |
| Realtek Semiconductor     | 7         | 7      | 0.22%   |
| LITEONIT                  | 7         | 7      | 0.22%   |
| Hewlett-Packard           | 7         | 15     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 45        | 1.27%   |
| Kingston SA400S37240G 240GB SSD                     | 43        | 1.21%   |
| Samsung NVMe SSD Drive 1TB                          | 36        | 1.02%   |
| SanDisk NVMe SSD Drive 512GB                        | 29        | 0.82%   |
| Samsung NVMe SSD Drive 512GB                        | 27        | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB                      | 26        | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 25        | 0.71%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.71%   |
| Samsung SSD 850 EVO 250GB                           | 25        | 0.71%   |
| Samsung NVMe SSD Drive 500GB                        | 25        | 0.71%   |
| SanDisk NVMe SSD Drive 1TB                          | 23        | 0.65%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.62%   |
| Unknown MMC Card  64GB                              | 20        | 0.56%   |
| Samsung NVMe SSD Drive 1024GB                       | 20        | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 19        | 0.54%   |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.54%   |
| Intel NVMe SSD Drive 512GB                          | 19        | 0.54%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.54%   |
| Crucial CT500MX500SSD1 500GB                        | 19        | 0.54%   |
| Unknown                                             | 19        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                     | 18        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 18        | 0.51%   |
| Samsung SSD 980 PRO 1TB                             | 17        | 0.48%   |
| Samsung SSD 850 EVO 500GB                           | 17        | 0.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 17        | 0.48%   |
| Samsung NVMe SSD Drive 2TB                          | 16        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 15        | 0.42%   |
| SK hynix NVMe SSD Drive 512GB                       | 15        | 0.42%   |
| SanDisk NVMe SSD Drive 500GB                        | 15        | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 15        | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                      | 14        | 0.4%    |
| Samsung SSD 860 EVO 1TB                             | 14        | 0.4%    |
| Micron NVMe SSD Drive 512GB                         | 14        | 0.4%    |
| KIOXIA NVMe SSD Drive 512GB                         | 14        | 0.4%    |
| Kingston SA400S37480G 480GB SSD                     | 14        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB                      | 13        | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB                      | 13        | 0.37%   |
| Samsung SSD 970 EVO Plus 2TB                        | 13        | 0.37%   |
| Crucial CT480BX500SSD1 480GB                        | 13        | 0.37%   |
| Unknown MMC Card  32GB                              | 12        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 323       | 455    | 39.83%  |
| WDC                 | 268       | 394    | 33.05%  |
| Toshiba             | 92        | 103    | 11.34%  |
| Hitachi             | 41        | 56     | 5.06%   |
| HGST                | 36        | 43     | 4.44%   |
| Samsung Electronics | 11        | 20     | 1.36%   |
| Apple               | 8         | 8      | 0.99%   |
| Unknown             | 7         | 8      | 0.86%   |
| Fujitsu             | 5         | 6      | 0.62%   |
| Hewlett-Packard     | 4         | 12     | 0.49%   |
| USB3.0              | 2         | 2      | 0.25%   |
| ASMT                | 2         | 2      | 0.25%   |
| USB                 | 1         | 1      | 0.12%   |
| Synology            | 1         | 2      | 0.12%   |
| SAGE                | 1         | 1      | 0.12%   |
| RSH-339             | 1         | 1      | 0.12%   |
| Maxtor              | 1         | 3      | 0.12%   |
| JMicron Technology  | 1         | 1      | 0.12%   |
| Intenso             | 1         | 1      | 0.12%   |
| IB-AC703            | 1         | 1      | 0.12%   |
| H/W                 | 1         | 3      | 0.12%   |
| ExcelStor           | 1         | 1      | 0.12%   |
| ASMT106x            | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 243       | 313    | 24.82%  |
| Kingston            | 129       | 148    | 13.18%  |
| Crucial             | 114       | 150    | 11.64%  |
| SanDisk             | 83        | 97     | 8.48%   |
| WDC                 | 62        | 87     | 6.33%   |
| Intel               | 29        | 40     | 2.96%   |
| China               | 26        | 30     | 2.66%   |
| A-DATA Technology   | 26        | 27     | 2.66%   |
| Micron Technology   | 22        | 23     | 2.25%   |
| PNY                 | 18        | 21     | 1.84%   |
| SPCC                | 16        | 21     | 1.63%   |
| Patriot             | 15        | 17     | 1.53%   |
| Apple               | 15        | 15     | 1.53%   |
| SK hynix            | 14        | 15     | 1.43%   |
| LITEON              | 12        | 12     | 1.23%   |
| Transcend           | 10        | 13     | 1.02%   |
| Toshiba             | 10        | 14     | 1.02%   |
| Netac               | 9         | 9      | 0.92%   |
| LITEONIT            | 7         | 7      | 0.72%   |
| Intenso             | 7         | 9      | 0.72%   |
| Gigabyte Technology | 7         | 11     | 0.72%   |
| Team                | 6         | 9      | 0.61%   |
| OCZ                 | 6         | 10     | 0.61%   |
| Lexar               | 6         | 7      | 0.61%   |
| GOODRAM             | 6         | 10     | 0.61%   |
| Seagate             | 5         | 5      | 0.51%   |
| Corsair             | 5         | 6      | 0.51%   |
| Apacer              | 5         | 5      | 0.51%   |
| KingSpec            | 4         | 4      | 0.41%   |
| KingDian            | 4         | 4      | 0.41%   |
| Verbatim            | 3         | 5      | 0.31%   |
| Plextor             | 3         | 5      | 0.31%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.31%   |
| GALAX               | 3         | 3      | 0.31%   |
| Unknown             | 3         | 3      | 0.31%   |
| Mushkin             | 2         | 3      | 0.2%    |
| Leven               | 2         | 2      | 0.2%    |
| GLOWAY              | 2         | 2      | 0.2%    |
| XSTAR               | 1         | 1      | 0.1%    |
| XrayDisk            | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1235      | 1620   | 42.78%  |
| SSD     | 822       | 1209   | 28.47%  |
| HDD     | 688       | 1126   | 23.83%  |
| MMC     | 96        | 123    | 3.33%   |
| Unknown | 46        | 50     | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1230      | 1602   | 46.57%  |
| SATA | 1196      | 2241   | 45.29%  |
| SAS  | 119       | 162    | 4.51%   |
| MMC  | 96        | 123    | 3.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 816       | 1232   | 50.65%  |
| 0.51-1.0   | 521       | 694    | 32.34%  |
| 1.01-2.0   | 148       | 218    | 9.19%   |
| 3.01-4.0   | 61        | 82     | 3.79%   |
| 4.01-10.0  | 32        | 62     | 1.99%   |
| 2.01-3.0   | 27        | 38     | 1.68%   |
| 10.01-20.0 | 6         | 9      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 456       | 20.97%  |
| 251-500        | 378       | 17.38%  |
| 1001-2000      | 322       | 14.8%   |
| 101-250        | 289       | 13.29%  |
| 1-20           | 229       | 10.53%  |
| More than 3000 | 167       | 7.68%   |
| Unknown        | 142       | 6.53%   |
| 2001-3000      | 92        | 4.23%   |
| 51-100         | 74        | 3.4%    |
| 21-50          | 26        | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 628       | 28.06%  |
| 21-50          | 345       | 15.42%  |
| 101-250        | 297       | 13.27%  |
| 51-100         | 261       | 11.66%  |
| 251-500        | 224       | 10.01%  |
| 501-1000       | 170       | 7.6%    |
| Unknown        | 142       | 6.34%   |
| 1001-2000      | 93        | 4.16%   |
| More than 3000 | 50        | 2.23%   |
| 2001-3000      | 28        | 1.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 5         | 11     | 3.73%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 2.99%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 2.99%   |
| Samsung Electronics SSD 870 EVO 1TB   | 4         | 4      | 2.99%   |
| HGST HTS721010A9E630 1TB              | 4         | 4      | 2.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 5      | 2.24%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 1.49%   |
| Toshiba MK3275GSX 320GB               | 2         | 3      | 1.49%   |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 1.49%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 3      | 1.49%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 1.49%   |
| Intel SSDSC2CT120A3 120GB             | 2         | 7      | 1.49%   |
| Intel SSDSC2BF180A4H 180GB            | 2         | 2      | 1.49%   |
| Hitachi HTS545032B9A300 320GB         | 2         | 2      | 1.49%   |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 0.75%   |
| WDC WD6400BPVT-75HXZT3 640GB          | 1         | 1      | 0.75%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 0.75%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-003CA0 500GB           | 1         | 1      | 0.75%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.75%   |
| WDC WD40EFRX-68WT0N0 4TB              | 1         | 1      | 0.75%   |
| WDC WD4001FAEX-00MJRA0 4TB            | 1         | 1      | 0.75%   |
| WDC WD3200AAKS-75B3A0 320GB           | 1         | 1      | 0.75%   |
| WDC WD3200AAJS-65M0A0 320GB           | 1         | 1      | 0.75%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1         | 1      | 0.75%   |
| WDC WD2500AAKX-753CA1 250GB           | 1         | 1      | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 1      | 0.75%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 1      | 0.75%   |
| WDC WD2003FYYS-02W0B1 2TB             | 1         | 6      | 0.75%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EZEX-00MFCA0 1TB              | 1         | 1      | 0.75%   |
| WDC WD10EARS-22Y5B1 1TB               | 1         | 1      | 0.75%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 0.75%   |
| WDC WD10EADS-65M2B1 1TB               | 1         | 1      | 0.75%   |
| WDC WD1003FBYX-01Y7B1 1TB             | 1         | 2      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 43     | 22.83%  |
| WDC                 | 25        | 32     | 19.69%  |
| Samsung Electronics | 15        | 25     | 11.81%  |
| Toshiba             | 10        | 12     | 7.87%   |
| Hitachi             | 8         | 8      | 6.3%    |
| Intel               | 7         | 13     | 5.51%   |
| HGST                | 5         | 5      | 3.94%   |
| SanDisk             | 4         | 5      | 3.15%   |
| Crucial             | 4         | 5      | 3.15%   |
| SK hynix            | 3         | 3      | 2.36%   |
| Kingston            | 3         | 3      | 2.36%   |
| LITEON              | 2         | 2      | 1.57%   |
| walram              | 1         | 1      | 0.79%   |
| SPCC                | 1         | 2      | 0.79%   |
| PNY                 | 1         | 1      | 0.79%   |
| Origin              | 1         | 1      | 0.79%   |
| OCZ-VERTEX3         | 1         | 1      | 0.79%   |
| Micron Technology   | 1         | 1      | 0.79%   |
| LITEONIT            | 1         | 1      | 0.79%   |
| Lenovo              | 1         | 2      | 0.79%   |
| KingSpec            | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |
| A-DATA Technology   | 1         | 1      | 0.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 43     | 35.37%  |
| WDC                 | 25        | 32     | 30.49%  |
| Toshiba             | 10        | 12     | 12.2%   |
| Hitachi             | 8         | 8      | 9.76%   |
| HGST                | 5         | 5      | 6.1%    |
| Samsung Electronics | 4         | 13     | 4.88%   |
| Fujitsu             | 1         | 1      | 1.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 79        | 114    | 64.75%  |
| SSD  | 37        | 48     | 30.33%  |
| NVMe | 6         | 8      | 4.92%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 50%     |
| Samsung Electronics SSD 980 500GB | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1218      | 2357   | 52.96%  |
| Works    | 960       | 1598   | 41.74%  |
| Malfunc  | 120       | 170    | 5.22%   |
| Failed   | 2         | 3      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1173      | 39.22%  |
| AMD                                     | 468       | 15.65%  |
| Samsung Electronics                     | 433       | 14.48%  |
| SanDisk                                 | 218       | 7.29%   |
| SK hynix                                | 115       | 3.84%   |
| Phison Electronics                      | 74        | 2.47%   |
| Micron Technology                       | 68        | 2.27%   |
| Kingston Technology Company             | 60        | 2.01%   |
| Toshiba America Info Systems            | 58        | 1.94%   |
| KIOXIA                                  | 50        | 1.67%   |
| ASMedia Technology                      | 40        | 1.34%   |
| ADATA Technology                        | 40        | 1.34%   |
| Micron/Crucial Technology               | 36        | 1.2%    |
| Silicon Motion                          | 32        | 1.07%   |
| Marvell Technology Group                | 16        | 0.53%   |
| Nvidia                                  | 13        | 0.43%   |
| Union Memory (Shenzhen)                 | 11        | 0.37%   |
| Solid State Storage Technology          | 11        | 0.37%   |
| JMicron Technology                      | 11        | 0.37%   |
| Realtek Semiconductor                   | 10        | 0.33%   |
| Seagate Technology                      | 7         | 0.23%   |
| LSI Logic / Symbios Logic               | 6         | 0.2%    |
| MAXIO Technology (Hangzhou)             | 5         | 0.17%   |
| Lite-On Technology                      | 5         | 0.17%   |
| Apple                                   | 5         | 0.17%   |
| Lenovo                                  | 4         | 0.13%   |
| Silicon Image                           | 3         | 0.1%    |
| INNOGRIT                                | 3         | 0.1%    |
| Hewlett-Packard                         | 3         | 0.1%    |
| Broadcom / LSI                          | 3         | 0.1%    |
| Adaptec                                 | 2         | 0.07%   |
| Yangtze Memory Technologies             | 1         | 0.03%   |
| VIA Technologies                        | 1         | 0.03%   |
| ULi Electronics                         | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| Netac Technology                        | 1         | 0.03%   |
| Integrated Technology Express           | 1         | 0.03%   |
| Biwin Storage Technology                | 1         | 0.03%   |
| Unknown                                 | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 336       | 10.23%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 199       | 6.06%   |
| Intel Volume Management Device NVMe RAID Controller                            | 112       | 3.41%   |
| Samsung NVMe SSD Controller 980                                                | 100       | 3.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 100       | 3.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 82        | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 78        | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 78        | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 77        | 2.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 73        | 2.22%   |
| AMD 500 Series Chipset SATA Controller                                         | 73        | 2.22%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 55        | 1.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 53        | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 50        | 1.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 46        | 1.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 45        | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 44        | 1.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 42        | 1.28%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 41        | 1.25%   |
| Micron NVMe Storage Controller                                                 | 40        | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                          | 40        | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 39        | 1.19%   |
| Phison E12 NVMe Controller                                                     | 38        | 1.16%   |
| Intel Tiger Lake-LP SATA Controller                                            | 38        | 1.16%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 38        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 32        | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 31        | 0.94%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 30        | 0.91%   |
| Intel SSD 660P Series                                                          | 29        | 0.88%   |
| Intel SATA Controller [RAID mode]                                              | 29        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 27        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 27        | 0.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 25        | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 24        | 0.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 24        | 0.73%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 23        | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 23        | 0.7%    |
| Intel Non-Volatile memory controller                                           | 22        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1394      | 47.02%  |
| NVMe | 1223      | 41.25%  |
| RAID | 242       | 8.16%   |
| IDE  | 98        | 3.31%   |
| SAS  | 5         | 0.17%   |
| SCSI | 3         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1470      | 69.11%  |
| AMD     | 653       | 30.7%   |
| ARM     | 2         | 0.09%   |
| Unknown | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 53        | 2.49%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 52        | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 1.6%    |
| AMD Ryzen 5 3600 6-Core Processor             | 32        | 1.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.36%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 1.36%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 1.13%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 23        | 1.08%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 23        | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 22        | 1.03%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 22        | 1.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 21        | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.89%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 19        | 0.89%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 19        | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.85%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 18        | 0.85%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 16        | 0.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 16        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.7%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 15        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 14        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.66%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 14        | 0.66%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 13        | 0.61%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 13        | 0.61%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 13        | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 13        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 0.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.56%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 12        | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 12        | 0.56%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 11        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 433       | 20.35%  |
| Intel Core i5                  | 431       | 20.25%  |
| Other                          | 280       | 13.16%  |
| AMD Ryzen 5                    | 237       | 11.14%  |
| AMD Ryzen 7                    | 182       | 8.55%   |
| Intel Core i3                  | 103       | 4.84%   |
| AMD Ryzen 9                    | 89        | 4.18%   |
| Intel Celeron                  | 54        | 2.54%   |
| Intel Xeon                     | 42        | 1.97%   |
| Intel Core 2 Duo               | 32        | 1.5%    |
| Intel Core i9                  | 24        | 1.13%   |
| Intel Atom                     | 24        | 1.13%   |
| AMD Ryzen 7 PRO                | 22        | 1.03%   |
| Intel Pentium                  | 21        | 0.99%   |
| AMD Ryzen 3                    | 19        | 0.89%   |
| AMD FX                         | 17        | 0.8%    |
| AMD A10                        | 15        | 0.7%    |
| AMD Ryzen 5 PRO                | 11        | 0.52%   |
| Intel Pentium Silver           | 10        | 0.47%   |
| AMD A6                         | 9         | 0.42%   |
| Intel Core 2 Quad              | 8         | 0.38%   |
| AMD A8                         | 7         | 0.33%   |
| AMD Phenom II X4               | 6         | 0.28%   |
| AMD A4                         | 5         | 0.23%   |
| Intel Pentium Gold             | 3         | 0.14%   |
| Intel Pentium Dual-Core        | 3         | 0.14%   |
| Intel Genuine                  | 3         | 0.14%   |
| Intel Core 2                   | 3         | 0.14%   |
| AMD Phenom II X2               | 3         | 0.14%   |
| AMD E1                         | 3         | 0.14%   |
| Intel Core m3                  | 2         | 0.09%   |
| AMD PRO A10                    | 2         | 0.09%   |
| AMD Phenom II X6               | 2         | 0.09%   |
| AMD Opteron                    | 2         | 0.09%   |
| AMD Athlon Dual Core           | 2         | 0.09%   |
| AMD Athlon 64 X2               | 2         | 0.09%   |
| AMD Athlon                     | 2         | 0.09%   |
| Intel Pentium Dual             | 1         | 0.05%   |
| Intel Core m5                  | 1         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 803       | 37.73%  |
| 2       | 520       | 24.44%  |
| 6       | 348       | 16.35%  |
| 8       | 290       | 13.63%  |
| 12      | 77        | 3.62%   |
| 16      | 27        | 1.27%   |
| 10      | 24        | 1.13%   |
| 14      | 21        | 0.99%   |
| 3       | 8         | 0.38%   |
| 1       | 5         | 0.23%   |
| Unknown | 3         | 0.14%   |
| 20      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2113      | 99.34%  |
| 2       | 11        | 0.52%   |
| Unknown | 3         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1756      | 82.52%  |
| 1       | 369       | 17.34%  |
| Unknown | 3         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2126      | 99.95%  |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x806c1    | 140       | 6.55%   |
| Unknown    | 114       | 5.33%   |
| 0x306a9    | 99        | 4.63%   |
| 0x306c3    | 87        | 4.07%   |
| 0x0a50000c | 84        | 3.93%   |
| 0x906ea    | 79        | 3.7%    |
| 0x806ea    | 77        | 3.6%    |
| 0x206a7    | 77        | 3.6%    |
| 0x806ec    | 74        | 3.46%   |
| 0x506e3    | 62        | 2.9%    |
| 0x806e9    | 61        | 2.85%   |
| 0x08701021 | 61        | 2.85%   |
| 0x40651    | 47        | 2.2%    |
| 0x08108109 | 47        | 2.2%    |
| 0x08600106 | 46        | 2.15%   |
| 0x906e9    | 45        | 2.1%    |
| 0xa0652    | 40        | 1.87%   |
| 0x0a201016 | 39        | 1.82%   |
| 0x406e3    | 38        | 1.78%   |
| 0x08608103 | 38        | 1.78%   |
| 0x906a3    | 35        | 1.64%   |
| 0x706e5    | 34        | 1.59%   |
| 0x306d4    | 33        | 1.54%   |
| 0x0800820d | 29        | 1.36%   |
| 0x1067a    | 25        | 1.17%   |
| 0x806d1    | 24        | 1.12%   |
| 0x90672    | 22        | 1.03%   |
| 0xa0653    | 21        | 0.98%   |
| 0x706a8    | 19        | 0.89%   |
| 0xa0655    | 18        | 0.84%   |
| 0x0a404101 | 18        | 0.84%   |
| 0x906ed    | 17        | 0.8%    |
| 0x0a404102 | 16        | 0.75%   |
| 0x08108102 | 16        | 0.75%   |
| 0x806eb    | 15        | 0.7%    |
| 0x20655    | 15        | 0.7%    |
| 0x08600104 | 15        | 0.7%    |
| 0x806c2    | 13        | 0.61%   |
| 0x506c9    | 12        | 0.56%   |
| 0x406c4    | 12        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 397       | 18.65%  |
| Zen 3            | 192       | 9.02%   |
| TigerLake        | 159       | 7.47%   |
| Haswell          | 157       | 7.37%   |
| Zen 2            | 149       | 7%      |
| Skylake          | 110       | 5.17%   |
| IvyBridge        | 109       | 5.12%   |
| Zen+             | 101       | 4.74%   |
| Unknown          | 99        | 4.65%   |
| SandyBridge      | 88        | 4.13%   |
| CometLake        | 87        | 4.09%   |
| Icelake          | 73        | 3.43%   |
| Alderlake Hybrid | 71        | 3.33%   |
| Zen              | 40        | 1.88%   |
| Penryn           | 40        | 1.88%   |
| Broadwell        | 39        | 1.83%   |
| Silvermont       | 34        | 1.6%    |
| Westmere         | 28        | 1.32%   |
| Goldmont plus    | 27        | 1.27%   |
| Piledriver       | 20        | 0.94%   |
| Excavator        | 18        | 0.85%   |
| K10              | 17        | 0.8%    |
| Goldmont         | 13        | 0.61%   |
| Core             | 10        | 0.47%   |
| Tremont          | 8         | 0.38%   |
| Nehalem          | 7         | 0.33%   |
| Steamroller      | 6         | 0.28%   |
| K8 Hammer        | 6         | 0.28%   |
| Jaguar           | 6         | 0.28%   |
| Bulldozer        | 5         | 0.23%   |
| Bonnell          | 5         | 0.23%   |
| Puma             | 4         | 0.19%   |
| K10 Llano        | 2         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.05%   |
| Bobcat           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1183      | 45.29%  |
| Nvidia                     | 730       | 27.95%  |
| AMD                        | 692       | 26.49%  |
| Matrox Electronics Systems | 6         | 0.23%   |
| ASPEED Technology          | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 145       | 5.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 86        | 3.22%   |
| Intel UHD Graphics 620                                                                   | 77        | 2.88%   |
| AMD Renoir                                                                               | 75        | 2.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 66        | 2.47%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 2.4%    |
| Intel HD Graphics 620                                                                    | 59        | 2.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 58        | 2.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 57        | 2.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 50        | 1.87%   |
| AMD Lucienne                                                                             | 50        | 1.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 49        | 1.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 48        | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 44        | 1.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 1.5%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 38        | 1.42%   |
| Intel HD Graphics 530                                                                    | 36        | 1.35%   |
| AMD Rembrandt [Radeon 680M]                                                              | 35        | 1.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 1.24%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 31        | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 31        | 1.16%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 29        | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 28        | 1.05%   |
| Intel HD Graphics 5500                                                                   | 28        | 1.05%   |
| Intel HD Graphics 630                                                                    | 27        | 1.01%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 24        | 0.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 22        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 20        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 20        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 20        | 0.75%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 18        | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 18        | 0.67%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 18        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 18        | 0.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 0.67%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 0.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 18        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 777       | 36.46%  |
| 1 x AMD         | 527       | 24.73%  |
| Intel + Nvidia  | 329       | 15.44%  |
| 1 x Nvidia      | 316       | 14.83%  |
| AMD + Nvidia    | 77        | 3.61%   |
| Intel + AMD     | 45        | 2.11%   |
| 2 x AMD         | 41        | 1.92%   |
| Other           | 4         | 0.19%   |
| 2 x Nvidia      | 4         | 0.19%   |
| 2 x Intel       | 3         | 0.14%   |
| 1 x Matrox      | 3         | 0.14%   |
| Nvidia + Matrox | 2         | 0.09%   |
| Intel + 2 x AMD | 1         | 0.05%   |
| 1 x ASPEED      | 1         | 0.05%   |
| AMD + Matrox    | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1718      | 80.36%  |
| Proprietary | 374       | 17.49%  |
| Unknown     | 46        | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1082      | 50.35%  |
| 1.01-2.0   | 267       | 12.42%  |
| 0.01-0.5   | 236       | 10.98%  |
| 3.01-4.0   | 182       | 8.47%   |
| 7.01-8.0   | 143       | 6.65%   |
| 0.51-1.0   | 117       | 5.44%   |
| 8.01-16.0  | 57        | 2.65%   |
| 5.01-6.0   | 55        | 2.56%   |
| 2.01-3.0   | 10        | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 309       | 12.4%   |
| BOE                     | 300       | 12.04%  |
| Samsung Electronics     | 222       | 8.91%   |
| Chimei Innolux          | 221       | 8.87%   |
| LG Display              | 192       | 7.71%   |
| Dell                    | 158       | 6.34%   |
| Goldstar                | 155       | 6.22%   |
| Hewlett-Packard         | 73        | 2.93%   |
| Sharp                   | 71        | 2.85%   |
| Acer                    | 68        | 2.73%   |
| BenQ                    | 66        | 2.65%   |
| AOC                     | 65        | 2.61%   |
| Philips                 | 61        | 2.45%   |
| Lenovo                  | 51        | 2.05%   |
| Apple                   | 50        | 2.01%   |
| Ancor Communications    | 38        | 1.53%   |
| PANDA                   | 34        | 1.36%   |
| ViewSonic               | 28        | 1.12%   |
| CSO                     | 26        | 1.04%   |
| ASUSTek Computer        | 25        | 1%      |
| Iiyama                  | 23        | 0.92%   |
| InfoVision              | 21        | 0.84%   |
| MSI                     | 18        | 0.72%   |
| Chi Mei Optoelectronics | 15        | 0.6%    |
| Gigabyte Technology     | 13        | 0.52%   |
| Sceptre Tech            | 12        | 0.48%   |
| TMX                     | 11        | 0.44%   |
| Vizio                   | 9         | 0.36%   |
| Eizo                    | 8         | 0.32%   |
| Sony                    | 7         | 0.28%   |
| Unknown                 | 6         | 0.24%   |
| Mi                      | 6         | 0.24%   |
| NEC Computers           | 5         | 0.2%    |
| HUAWEI                  | 5         | 0.2%    |
| HannStar                | 5         | 0.2%    |
| Toshiba                 | 4         | 0.16%   |
| Panasonic               | 4         | 0.16%   |
| Fujitsu Siemens         | 4         | 0.16%   |
| RTK                     | 3         | 0.12%   |
| ONN                     | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 17        | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch    | 15        | 0.58%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch             | 13        | 0.51%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch | 12        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 12        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch  | 11        | 0.43%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch             | 11        | 0.43%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                | 11        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch    | 10        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch           | 9         | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch          | 8         | 0.31%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch      | 8         | 0.31%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch             | 8         | 0.31%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch  | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch    | 8         | 0.31%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch          | 7         | 0.27%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch      | 7         | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch           | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch  | 7         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch  | 7         | 0.27%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch             | 7         | 0.27%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch             | 7         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 7         | 0.27%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch    | 7         | 0.27%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch         | 6         | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch | 6         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch | 6         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch      | 6         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 6         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch  | 6         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch  | 6         | 0.23%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch             | 6         | 0.23%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch             | 6         | 0.23%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch              | 6         | 0.23%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch    | 6         | 0.23%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch    | 6         | 0.23%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                  | 6         | 0.23%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch           | 5         | 0.19%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch      | 5         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1165      | 49.77%  |
| 1366x768 (WXGA)    | 276       | 11.79%  |
| 3840x2160 (4K)     | 197       | 8.42%   |
| 2560x1440 (QHD)    | 182       | 7.77%   |
| 1920x1200 (WUXGA)  | 75        | 3.2%    |
| 3440x1440          | 60        | 2.56%   |
| 1600x900 (HD+)     | 60        | 2.56%   |
| 2560x1600          | 45        | 1.92%   |
| 1280x1024 (SXGA)   | 33        | 1.41%   |
| 2560x1080          | 29        | 1.24%   |
| 1440x900 (WXGA+)   | 24        | 1.03%   |
| 3840x2400          | 20        | 0.85%   |
| 1680x1050 (WSXGA+) | 20        | 0.85%   |
| 1280x800 (WXGA)    | 20        | 0.85%   |
| 2880x1800          | 18        | 0.77%   |
| 2256x1504          | 14        | 0.6%    |
| 2160x1440          | 12        | 0.51%   |
| 1360x768           | 11        | 0.47%   |
| 2736x1824          | 10        | 0.43%   |
| 2288x1287          | 6         | 0.26%   |
| 1600x1200          | 6         | 0.26%   |
| 3840x1080          | 5         | 0.21%   |
| 3456x2160          | 5         | 0.21%   |
| 1920x540           | 5         | 0.21%   |
| 3840x1600          | 4         | 0.17%   |
| 3200x2000          | 4         | 0.17%   |
| 3000x2000          | 4         | 0.17%   |
| 2240x1400          | 4         | 0.17%   |
| 1920x1280          | 4         | 0.17%   |
| 1024x768 (XGA)     | 4         | 0.17%   |
| 3072x1920          | 3         | 0.13%   |
| 2520x1680          | 3         | 0.13%   |
| 3200x1800 (QHD+)   | 2         | 0.09%   |
| 3840x1100          | 1         | 0.04%   |
| 2560x2880          | 1         | 0.04%   |
| 2400x1600          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2200x1650          | 1         | 0.04%   |
| 2160x1200          | 1         | 0.04%   |
| 1920x550           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 593       | 23.69%  |
| 13      | 296       | 11.83%  |
| 14      | 263       | 10.51%  |
| 27      | 244       | 9.75%   |
| 24      | 187       | 7.47%   |
| 23      | 152       | 6.07%   |
| 21      | 148       | 5.91%   |
| 17      | 95        | 3.8%    |
| 31      | 79        | 3.16%   |
| 34      | 76        | 3.04%   |
| 12      | 45        | 1.8%    |
| 16      | 38        | 1.52%   |
| 18      | 36        | 1.44%   |
| 19      | 27        | 1.08%   |
| 20      | 25        | 1%      |
| 22      | 19        | 0.76%   |
| Unknown | 18        | 0.72%   |
| 11      | 17        | 0.68%   |
| 32      | 15        | 0.6%    |
| 40      | 14        | 0.56%   |
| 84      | 13        | 0.52%   |
| 72      | 8         | 0.32%   |
| 42      | 8         | 0.32%   |
| 26      | 8         | 0.32%   |
| 25      | 8         | 0.32%   |
| 142     | 6         | 0.24%   |
| 54      | 6         | 0.24%   |
| 48      | 6         | 0.24%   |
| 35      | 6         | 0.24%   |
| 10      | 6         | 0.24%   |
| 52      | 5         | 0.2%    |
| 37      | 5         | 0.2%    |
| 29      | 5         | 0.2%    |
| 69      | 3         | 0.12%   |
| 39      | 3         | 0.12%   |
| 36      | 3         | 0.12%   |
| 28      | 3         | 0.12%   |
| 100     | 2         | 0.08%   |
| 75      | 2         | 0.08%   |
| 58      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1025      | 41.63%  |
| 501-600        | 538       | 21.85%  |
| 401-500        | 234       | 9.5%    |
| 201-300        | 226       | 9.18%   |
| 601-700        | 117       | 4.75%   |
| 351-400        | 114       | 4.63%   |
| 701-800        | 94        | 3.82%   |
| 801-900        | 28        | 1.14%   |
| 1501-2000      | 26        | 1.06%   |
| 1001-1500      | 23        | 0.93%   |
| Unknown        | 18        | 0.73%   |
| 901-1000       | 11        | 0.45%   |
| More than 2000 | 8         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1711      | 78.7%   |
| 16/10   | 257       | 11.82%  |
| 21/9    | 90        | 4.14%   |
| 3/2     | 48        | 2.21%   |
| 5/4     | 29        | 1.33%   |
| 4/3     | 12        | 0.55%   |
| 32/9    | 7         | 0.32%   |
| Unknown | 7         | 0.32%   |
| 1.00    | 6         | 0.28%   |
| 6/5     | 3         | 0.14%   |
| 3.40    | 1         | 0.05%   |
| 1.96    | 1         | 0.05%   |
| 0.89    | 1         | 0.05%   |
| 0.80    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 591       | 23.85%  |
| 81-90          | 435       | 17.55%  |
| 201-250        | 397       | 16.02%  |
| 301-350        | 251       | 10.13%  |
| 351-500        | 182       | 7.34%   |
| 71-80          | 128       | 5.17%   |
| 151-200        | 98        | 3.95%   |
| 121-130        | 76        | 3.07%   |
| 251-300        | 59        | 2.38%   |
| More than 1000 | 50        | 2.02%   |
| 141-150        | 42        | 1.69%   |
| 501-1000       | 41        | 1.65%   |
| 111-120        | 39        | 1.57%   |
| 61-70          | 35        | 1.41%   |
| 51-60          | 19        | 0.77%   |
| Unknown        | 18        | 0.73%   |
| 131-140        | 8         | 0.32%   |
| 41-50          | 5         | 0.2%    |
| 91-100         | 4         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 822       | 34.01%  |
| 51-100        | 656       | 27.14%  |
| 101-120       | 518       | 21.43%  |
| 161-240       | 265       | 10.96%  |
| More than 240 | 98        | 4.05%   |
| 1-50          | 40        | 1.65%   |
| Unknown       | 18        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1592      | 73.77%  |
| 2     | 440       | 20.39%  |
| 3     | 59        | 2.73%   |
| 0     | 57        | 2.64%   |
| 4     | 9         | 0.42%   |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1228      | 39.17%  |
| Realtek Semiconductor             | 1117      | 35.63%  |
| Qualcomm Atheros                  | 224       | 7.15%   |
| Broadcom                          | 112       | 3.57%   |
| MediaTek                          | 95        | 3.03%   |
| TP-Link                           | 42        | 1.34%   |
| Broadcom Limited                  | 22        | 0.7%    |
| Ralink                            | 18        | 0.57%   |
| ASIX Electronics                  | 17        | 0.54%   |
| Ralink Technology                 | 16        | 0.51%   |
| Lenovo                            | 16        | 0.51%   |
| DisplayLink                       | 14        | 0.45%   |
| Qualcomm                          | 13        | 0.41%   |
| Nvidia                            | 13        | 0.41%   |
| Microsoft                         | 13        | 0.41%   |
| Marvell Technology Group          | 13        | 0.41%   |
| Samsung Electronics               | 12        | 0.38%   |
| Qualcomm Atheros Communications   | 12        | 0.38%   |
| Xiaomi                            | 10        | 0.32%   |
| Sierra Wireless                   | 10        | 0.32%   |
| Huawei Technologies               | 9         | 0.29%   |
| D-Link                            | 7         | 0.22%   |
| Aquantia                          | 7         | 0.22%   |
| Apple                             | 7         | 0.22%   |
| ASUSTek Computer                  | 6         | 0.19%   |
| Hewlett-Packard                   | 5         | 0.16%   |
| Ericsson Business Mobile Networks | 5         | 0.16%   |
| Edimax Technology                 | 5         | 0.16%   |
| Dell                              | 5         | 0.16%   |
| T & A Mobile Phones               | 4         | 0.13%   |
| NetGear                           | 4         | 0.13%   |
| Mellanox Technologies             | 4         | 0.13%   |
| Fibocom                           | 4         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 3         | 0.1%    |
| Microchip Technology              | 3         | 0.1%    |
| Linksys                           | 3         | 0.1%    |
| Google                            | 3         | 0.1%    |
| Belkin Components                 | 3         | 0.1%    |
| OPPO Electronics                  | 2         | 0.06%   |
| Motorola PCS                      | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 687       | 18.41%  |
| Intel Wi-Fi 6 AX200                                               | 178       | 4.77%   |
| Intel Wi-Fi 6 AX201                                               | 123       | 3.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 92        | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 91        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 2.41%   |
| Intel Wireless 8265 / 8275                                        | 82        | 2.2%    |
| Intel I211 Gigabit Network Connection                             | 73        | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 69        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 63        | 1.69%   |
| Intel Ethernet Controller I225-V                                  | 58        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 53        | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 53        | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 49        | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 46        | 1.23%   |
| Intel Wireless 7265                                               | 44        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 44        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 41        | 1.1%    |
| Intel Wireless 8260                                               | 40        | 1.07%   |
| Intel Ethernet Connection (2) I219-V                              | 38        | 1.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 36        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34        | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 30        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 30        | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29        | 0.78%   |
| Intel Wireless-AC 9260                                            | 29        | 0.78%   |
| Intel Wireless 7260                                               | 29        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 0.78%   |
| Intel Wireless 3165                                               | 28        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 28        | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 26        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 25        | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 24        | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 22        | 0.59%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                    | 21        | 0.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1015      | 54.31%  |
| Realtek Semiconductor           | 302       | 16.16%  |
| Qualcomm Atheros                | 191       | 10.22%  |
| MediaTek                        | 94        | 5.03%   |
| Broadcom                        | 86        | 4.6%    |
| TP-Link                         | 39        | 2.09%   |
| Broadcom Limited                | 19        | 1.02%   |
| Ralink                          | 18        | 0.96%   |
| Ralink Technology               | 16        | 0.86%   |
| Microsoft                       | 13        | 0.7%    |
| Qualcomm Atheros Communications | 12        | 0.64%   |
| Qualcomm                        | 11        | 0.59%   |
| Sierra Wireless                 | 10        | 0.54%   |
| Marvell Technology Group        | 8         | 0.43%   |
| Edimax Technology               | 5         | 0.27%   |
| ASUSTek Computer                | 5         | 0.27%   |
| Fibocom                         | 4         | 0.21%   |
| D-Link                          | 4         | 0.21%   |
| NetGear                         | 3         | 0.16%   |
| Linksys                         | 3         | 0.16%   |
| Dell                            | 3         | 0.16%   |
| Belkin Components               | 3         | 0.16%   |
| Sitecom Europe                  | 1         | 0.05%   |
| PLANEX                          | 1         | 0.05%   |
| IMC Networks                    | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| BUFFALO                         | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 178       | 9.5%    |
| Intel Wi-Fi 6 AX201                                            | 123       | 6.57%   |
| Intel Wireless 8265 / 8275                                     | 82        | 4.38%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 69        | 3.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 63        | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 53        | 2.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 53        | 2.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 49        | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 46        | 2.46%   |
| Intel Wireless 7265                                            | 44        | 2.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 44        | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 41        | 2.19%   |
| Intel Wireless 8260                                            | 40        | 2.14%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 36        | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34        | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 30        | 1.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 30        | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29        | 1.55%   |
| Intel Wireless-AC 9260                                         | 29        | 1.55%   |
| Intel Wireless 7260                                            | 29        | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 1.55%   |
| Intel Wireless 3165                                            | 28        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 28        | 1.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 26        | 1.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 25        | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 24        | 1.28%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 22        | 1.17%   |
| Intel Centrino Ultimate-N 6300                                 | 21        | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.01%   |
| Intel Wireless 3160                                            | 17        | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 15        | 0.8%    |
| Realtek 802.11ac NIC                                           | 13        | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 0.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 13        | 0.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 13        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 12        | 0.64%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 12        | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 981       | 55.17%  |
| Intel                             | 559       | 31.44%  |
| Qualcomm Atheros                  | 51        | 2.87%   |
| Broadcom                          | 44        | 2.47%   |
| ASIX Electronics                  | 17        | 0.96%   |
| Lenovo                            | 15        | 0.84%   |
| DisplayLink                       | 14        | 0.79%   |
| Nvidia                            | 13        | 0.73%   |
| Xiaomi                            | 10        | 0.56%   |
| Samsung Electronics               | 9         | 0.51%   |
| Huawei Technologies               | 7         | 0.39%   |
| Aquantia                          | 7         | 0.39%   |
| Apple                             | 7         | 0.39%   |
| Marvell Technology Group          | 5         | 0.28%   |
| TP-Link                           | 4         | 0.22%   |
| Mellanox Technologies             | 3         | 0.17%   |
| Google                            | 3         | 0.17%   |
| D-Link                            | 3         | 0.17%   |
| Broadcom Limited                  | 3         | 0.17%   |
| Qualcomm                          | 2         | 0.11%   |
| OPPO Electronics                  | 2         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.11%   |
| Motorola PCS                      | 2         | 0.11%   |
| T & A Mobile Phones               | 1         | 0.06%   |
| Sundance Technology Inc / IC Plus | 1         | 0.06%   |
| QNAP System                       | 1         | 0.06%   |
| NetGear                           | 1         | 0.06%   |
| MosChip Semiconductor             | 1         | 0.06%   |
| Microchip Technology              | 1         | 0.06%   |
| MediaTek                          | 1         | 0.06%   |
| LG Electronics                    | 1         | 0.06%   |
| Insyde Software                   | 1         | 0.06%   |
| ICS Advent                        | 1         | 0.06%   |
| HMD Global                        | 1         | 0.06%   |
| Hewlett-Packard                   | 1         | 0.06%   |
| Davicom Semiconductor             | 1         | 0.06%   |
| ASUSTek Computer                  | 1         | 0.06%   |
| ADMtek                            | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 687       | 37.73%  |
| Realtek RTL8125 2.5GbE Controller                                 | 92        | 5.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 91        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 4.94%   |
| Intel I211 Gigabit Network Connection                             | 73        | 4.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 3.79%   |
| Intel Ethernet Controller I225-V                                  | 58        | 3.19%   |
| Intel Ethernet Connection (2) I219-V                              | 38        | 2.09%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 20        | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 16        | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 16        | 0.88%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 14        | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 11        | 0.6%    |
| Intel Ethernet Connection (11) I219-LM                            | 10        | 0.55%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 9         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 9         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                             | 9         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.49%   |
| Intel 82574L Gigabit Network Connection                           | 9         | 0.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 9         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.38%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.38%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 7         | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 0.38%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.38%   |
| DisplayLink USB 3.0 Docking Station                               | 7         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1793      | 51.84%  |
| Ethernet | 1629      | 47.09%  |
| Modem    | 31        | 0.9%    |
| Unknown  | 6         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1434      | 64.33%  |
| Ethernet | 794       | 35.62%  |
| Modem    | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1092      | 51.32%  |
| 1     | 936       | 43.98%  |
| 3     | 62        | 2.91%   |
| 0     | 33        | 1.55%   |
| 4     | 5         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1582      | 73.82%  |
| Yes  | 561       | 26.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 888       | 55.74%  |
| Realtek Semiconductor           | 187       | 11.74%  |
| Qualcomm Atheros Communications | 96        | 6.03%   |
| IMC Networks                    | 67        | 4.21%   |
| Cambridge Silicon Radio         | 66        | 4.14%   |
| Broadcom                        | 55        | 3.45%   |
| Foxconn / Hon Hai               | 53        | 3.33%   |
| Apple                           | 48        | 3.01%   |
| Lite-On Technology              | 37        | 2.32%   |
| ASUSTek Computer                | 21        | 1.32%   |
| MediaTek                        | 13        | 0.82%   |
| Realtek                         | 12        | 0.75%   |
| Marvell Semiconductor           | 9         | 0.56%   |
| TP-Link                         | 8         | 0.5%    |
| Ralink                          | 7         | 0.44%   |
| Toshiba                         | 6         | 0.38%   |
| Hewlett-Packard                 | 5         | 0.31%   |
| Dell                            | 4         | 0.25%   |
| USI                             | 2         | 0.13%   |
| Opticis                         | 2         | 0.13%   |
| Edimax Technology               | 2         | 0.13%   |
| SINO WEALTH                     | 1         | 0.06%   |
| Qcom                            | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| HTC (High Tech Computer)        | 1         | 0.06%   |
| BUFFALO                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 224       | 14.05%  |
| Intel AX201 Bluetooth                               | 215       | 13.49%  |
| Intel AX200 Bluetooth                               | 170       | 10.66%  |
| Realtek Bluetooth Radio                             | 130       | 8.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 115       | 7.21%   |
| Intel AX210 Bluetooth                               | 66        | 4.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 66        | 4.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 48        | 3.01%   |
| IMC Networks Wireless_Device                        | 37        | 2.32%   |
| Realtek  Bluetooth 4.2 Adapter                      | 35        | 2.2%    |
| Intel Bluetooth Device                              | 30        | 1.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 28        | 1.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 26        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.38%   |
| Apple Bluetooth Host Controller                     | 22        | 1.38%   |
| Apple Bluetooth USB Host Controller                 | 19        | 1.19%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 18        | 1.13%   |
| IMC Networks Bluetooth Radio                        | 15        | 0.94%   |
| MediaTek Wireless_Device                            | 13        | 0.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 13        | 0.82%   |
| Realtek Bluetooth Radio                             | 12        | 0.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.75%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 11        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.63%   |
| TP-Link UB500 Adapter                               | 8         | 0.5%    |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.5%    |
| Ralink RT3290 Bluetooth                             | 7         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.44%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.44%   |
| Lite-On Wireless_Device                             | 7         | 0.44%   |
| Lite-On Bluetooth Device                            | 7         | 0.44%   |
| IMC Networks Bluetooth Device                       | 7         | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.44%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.44%   |
| Realtek RTL8821A Bluetooth                          | 6         | 0.38%   |
| ASUS Bluetooth Radio                                | 6         | 0.38%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.38%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1427      | 44.65%  |
| AMD                                  | 754       | 23.59%  |
| Nvidia                               | 533       | 16.68%  |
| C-Media Electronics                  | 67        | 2.1%    |
| Logitech                             | 34        | 1.06%   |
| Lenovo                               | 23        | 0.72%   |
| Realtek Semiconductor                | 22        | 0.69%   |
| GN Netcom                            | 16        | 0.5%    |
| Texas Instruments                    | 15        | 0.47%   |
| Creative Technology                  | 15        | 0.47%   |
| JMTek                                | 14        | 0.44%   |
| Corsair                              | 14        | 0.44%   |
| SteelSeries ApS                      | 13        | 0.41%   |
| Kingston Technology                  | 13        | 0.41%   |
| Creative Labs                        | 13        | 0.41%   |
| Samson Technologies                  | 11        | 0.34%   |
| Plantronics                          | 11        | 0.34%   |
| XMOS                                 | 10        | 0.31%   |
| Razer USA                            | 10        | 0.31%   |
| Generalplus Technology               | 10        | 0.31%   |
| ASUSTek Computer                     | 9         | 0.28%   |
| Hewlett-Packard                      | 8         | 0.25%   |
| Focusrite-Novation                   | 8         | 0.25%   |
| Sony                                 | 7         | 0.22%   |
| Conexant Systems                     | 6         | 0.19%   |
| Micro Star International             | 5         | 0.16%   |
| Blue Microphones                     | 5         | 0.16%   |
| Apple                                | 5         | 0.16%   |
| Yamaha                               | 4         | 0.13%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.13%   |
| Sennheiser Communications            | 4         | 0.13%   |
| PreSonus Audio Electronics           | 4         | 0.13%   |
| FiiO Electronics Technology          | 4         | 0.13%   |
| Dell                                 | 4         | 0.13%   |
| Scarlett                             | 3         | 0.09%   |
| Samsung Electronics                  | 3         | 0.09%   |
| Elgato Systems                       | 3         | 0.09%   |
| DSEA A/S                             | 3         | 0.09%   |
| ZOOM                                 | 2         | 0.06%   |
| USB MICROPHONE                       | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 348       | 8.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 214       | 5.51%   |
| Intel Sunrise Point-LP HD Audio                                            | 183       | 4.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 159       | 4.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 149       | 3.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 112       | 2.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 87        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 86        | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 85        | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 81        | 2.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 72        | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 65        | 1.67%   |
| Intel Comet Lake PCH cAVS                                                  | 61        | 1.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 57        | 1.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 56        | 1.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 56        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 53        | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 50        | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 49        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 48        | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 47        | 1.21%   |
| Intel 200 Series PCH HD Audio                                              | 45        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 41        | 1.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 39        | 1%      |
| Nvidia TU116 High Definition Audio Controller                              | 38        | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 38        | 0.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 37        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 36        | 0.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 32        | 0.82%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 32        | 0.82%   |
| Intel Alder Lake-S HD Audio Controller                                     | 31        | 0.8%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 31        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 29        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 29        | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 28        | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 28        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 27        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 303       | 24.11%  |
| SK hynix                                         | 226       | 17.98%  |
| Micron Technology                                | 161       | 12.81%  |
| Kingston                                         | 124       | 9.86%   |
| Crucial                                          | 91        | 7.24%   |
| Unknown                                          | 69        | 5.49%   |
| Corsair                                          | 56        | 4.46%   |
| G.Skill                                          | 51        | 4.06%   |
| A-DATA Technology                                | 28        | 2.23%   |
| Ramaxel Technology                               | 26        | 2.07%   |
| Patriot                                          | 20        | 1.59%   |
| Team                                             | 16        | 1.27%   |
| Unknown (ABCD)                                   | 15        | 1.19%   |
| Unknown                                          | 10        | 0.8%    |
| Nanya Technology                                 | 9         | 0.72%   |
| Smart                                            | 8         | 0.64%   |
| Elpida                                           | 8         | 0.64%   |
| Silicon Power                                    | 3         | 0.24%   |
| PNY                                              | 3         | 0.24%   |
| V-GEN                                            | 2         | 0.16%   |
| Goldkey                                          | 2         | 0.16%   |
| ChangXin Memory                                  | 2         | 0.16%   |
| Atermiter                                        | 2         | 0.16%   |
| AMD                                              | 2         | 0.16%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.08%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.08%   |
| Unifosa                                          | 1         | 0.08%   |
| Transcend                                        | 1         | 0.08%   |
| Timetec                                          | 1         | 0.08%   |
| Smart Brazil                                     | 1         | 0.08%   |
| Sesame                                           | 1         | 0.08%   |
| Samsung 1                                        | 1         | 0.08%   |
| Qimonda                                          | 1         | 0.08%   |
| PUSKILL                                          | 1         | 0.08%   |
| Patriot Memory                                   | 1         | 0.08%   |
| Neo Forza                                        | 1         | 0.08%   |
| Mushkin                                          | 1         | 0.08%   |
| Mircon                                           | 1         | 0.08%   |
| Kllisre                                          | 1         | 0.08%   |
| Hikvision                                        | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 15        | 1.14%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 15        | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 13        | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.99%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.99%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 0.84%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 11        | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.76%   |
| Unknown                                                          | 10        | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 9         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.46%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.46%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.46%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 6         | 0.46%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 6         | 0.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 6         | 0.46%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.38%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.38%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.38%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s               | 5         | 0.38%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.3%    |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 4         | 0.3%    |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 4         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 664       | 61.25%  |
| DDR3    | 235       | 21.68%  |
| LPDDR4  | 74        | 6.83%   |
| LPDDR3  | 34        | 3.14%   |
| Unknown | 22        | 2.03%   |
| DDR5    | 19        | 1.75%   |
| LPDDR5  | 15        | 1.38%   |
| DDR2    | 12        | 1.11%   |
| SDRAM   | 7         | 0.65%   |
| DDR     | 2         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 641       | 58.33%  |
| DIMM         | 303       | 27.57%  |
| Row Of Chips | 146       | 13.28%  |
| Chip         | 5         | 0.45%   |
| RIMM         | 2         | 0.18%   |
| Unknown      | 2         | 0.18%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 493       | 42.39%  |
| 4096  | 274       | 23.56%  |
| 16384 | 241       | 20.72%  |
| 2048  | 76        | 6.53%   |
| 32768 | 64        | 5.5%    |
| 1024  | 13        | 1.12%   |
| 3072  | 2         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 306       | 26.56%  |
| 2667    | 177       | 15.36%  |
| 1600    | 172       | 14.93%  |
| 2133    | 69        | 5.99%   |
| 2400    | 67        | 5.82%   |
| 3600    | 43        | 3.73%   |
| 4267    | 39        | 3.39%   |
| 1333    | 32        | 2.78%   |
| 1867    | 28        | 2.43%   |
| 4800    | 19        | 1.65%   |
| 6400    | 17        | 1.48%   |
| 3266    | 16        | 1.39%   |
| 1334    | 16        | 1.39%   |
| 3733    | 11        | 0.95%   |
| 1067    | 10        | 0.87%   |
| 667     | 9         | 0.78%   |
| Unknown | 9         | 0.78%   |
| 3400    | 8         | 0.69%   |
| 3800    | 7         | 0.61%   |
| 3466    | 7         | 0.61%   |
| 3000    | 7         | 0.61%   |
| 8400    | 6         | 0.52%   |
| 4266    | 6         | 0.52%   |
| 2933    | 6         | 0.52%   |
| 2800    | 6         | 0.52%   |
| 2666    | 6         | 0.52%   |
| 3866    | 5         | 0.43%   |
| 1066    | 5         | 0.43%   |
| 800     | 5         | 0.43%   |
| 4000    | 3         | 0.26%   |
| 3666    | 3         | 0.26%   |
| 3533    | 3         | 0.26%   |
| 3333    | 3         | 0.26%   |
| 1866    | 3         | 0.26%   |
| 1800    | 3         | 0.26%   |
| 400     | 3         | 0.26%   |
| 5200    | 2         | 0.17%   |
| 3100    | 2         | 0.17%   |
| 2048    | 2         | 0.17%   |
| 49926   | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 9         | 25.71%  |
| Hewlett-Packard       | 8         | 22.86%  |
| Canon                 | 7         | 20%     |
| Seiko Epson           | 3         | 8.57%   |
| Samsung Electronics   | 2         | 5.71%   |
| Prolific Technology   | 2         | 5.71%   |
| NXP Semiconductors    | 1         | 2.86%   |
| Lexmark International | 1         | 2.86%   |
| Kyocera               | 1         | 2.86%   |
| Graphtec America      | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port        | 2         | 5.71%   |
| Seiko Epson Printer                  | 1         | 2.86%   |
| Seiko Epson L3110 Series             | 1         | 2.86%   |
| Seiko Epson L300 Series              | 1         | 2.86%   |
| Samsung ML-1640 Series Laser Printer | 1         | 2.86%   |
| Samsung M2070 Series                 | 1         | 2.86%   |
| NXP Semiconductors Printer-80        | 1         | 2.86%   |
| Lexmark International 2200 series    | 1         | 2.86%   |
| Kyocera ECOSYS M5521cdw              | 1         | 2.86%   |
| HP Officejet 4630 series             | 1         | 2.86%   |
| HP Neverstop Laser 100x              | 1         | 2.86%   |
| HP LaserJet Pro M148-M149            | 1         | 2.86%   |
| HP LaserJet 1150                     | 1         | 2.86%   |
| HP Ink Tank 310 series               | 1         | 2.86%   |
| HP DeskJet 3700 series               | 1         | 2.86%   |
| HP DeskJet 3630 series               | 1         | 2.86%   |
| HP DeskJet 2700 series               | 1         | 2.86%   |
| Graphtec America Graphtec Printer    | 1         | 2.86%   |
| Canon TS3100 series                  | 1         | 2.86%   |
| Canon TR4500 series                  | 1         | 2.86%   |
| Canon TR150 series                   | 1         | 2.86%   |
| Canon PIXMA MG3600 Series            | 1         | 2.86%   |
| Canon PIXMA MG3500 Series            | 1         | 2.86%   |
| Canon MF3110                         | 1         | 2.86%   |
| Canon CanoScan LiDE 300              | 1         | 2.86%   |
| Brother Printer                      | 1         | 2.86%   |
| Brother MFC-9330CDW                  | 1         | 2.86%   |
| Brother HL-2270DW Laser Printer      | 1         | 2.86%   |
| Brother HL-2230 series               | 1         | 2.86%   |
| Brother HL-1110 series               | 1         | 2.86%   |
| Brother DCP-T510W                    | 1         | 2.86%   |
| Brother DCP-T220                     | 1         | 2.86%   |
| Brother DCP-L2530DW series           | 1         | 2.86%   |
| Brother DCP-7055W                    | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 6         | 66.67%  |
| Seiko Epson | 3         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                                 | 2         | 22.22%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 11.11%  |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 11.11%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 11.11%  |
| Canon CanoScan LiDE 70                                  | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                 | 1         | 11.11%  |
| Canon CanoScan LiDE 210                                 | 1         | 11.11%  |
| Canon CanoScan LiDE 200                                 | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 310       | 20.76%  |
| IMC Networks                           | 170       | 11.39%  |
| Microdia                               | 122       | 8.17%   |
| Realtek Semiconductor                  | 112       | 7.5%    |
| Logitech                               | 108       | 7.23%   |
| Quanta                                 | 89        | 5.96%   |
| Sunplus Innovation Technology          | 69        | 4.62%   |
| Bison Electronics                      | 65        | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 54        | 3.62%   |
| Acer                                   | 52        | 3.48%   |
| Apple                                  | 47        | 3.15%   |
| Syntek                                 | 44        | 2.95%   |
| Luxvisions Innotech Limited            | 43        | 2.88%   |
| Lite-On Technology                     | 29        | 1.94%   |
| Suyin                                  | 16        | 1.07%   |
| Microsoft                              | 16        | 1.07%   |
| Ricoh                                  | 12        | 0.8%    |
| Silicon Motion                         | 11        | 0.74%   |
| Samsung Electronics                    | 11        | 0.74%   |
| KYE Systems (Mouse Systems)            | 11        | 0.74%   |
| Lenovo                                 | 8         | 0.54%   |
| Alcor Micro                            | 8         | 0.54%   |
| SunplusIT                              | 7         | 0.47%   |
| Primax Electronics                     | 7         | 0.47%   |
| Hewlett-Packard                        | 6         | 0.4%    |
| Sonix Technology                       | 5         | 0.33%   |
| Razer USA                              | 5         | 0.33%   |
| USB Camera                             | 4         | 0.27%   |
| Generalplus Technology                 | 4         | 0.27%   |
| ARC International                      | 4         | 0.27%   |
| Jieli Technology                       | 3         | 0.2%    |
| Cubeternet                             | 3         | 0.2%    |
| Creative Technology                    | 3         | 0.2%    |
| Z-Star Microelectronics                | 2         | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.13%   |
| MacroSilicon                           | 2         | 0.13%   |
| Linux Foundation                       | 2         | 0.13%   |
| Intel                                  | 2         | 0.13%   |
| BKX-210918                             | 2         | 0.13%   |
| Asuscom Network                        | 2         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 105       | 6.94%   |
| Microdia Integrated_Webcam_HD                        | 76        | 5.02%   |
| IMC Networks Integrated Camera                       | 65        | 4.29%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 58        | 3.83%   |
| Realtek Integrated_Webcam_HD                         | 48        | 3.17%   |
| Syntek Integrated Camera                             | 33        | 2.18%   |
| Logitech HD Pro Webcam C920                          | 29        | 1.92%   |
| Chicony HD WebCam                                    | 29        | 1.92%   |
| Bison Integrated Camera                              | 27        | 1.78%   |
| Sunplus Integrated_Webcam_HD                         | 23        | 1.52%   |
| Quanta HD User Facing                                | 18        | 1.19%   |
| Logitech Webcam C270                                 | 18        | 1.19%   |
| Chicony Integrated Camera (1280x720@30)              | 17        | 1.12%   |
| Acer Integrated Camera                               | 17        | 1.12%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 16        | 1.06%   |
| Chicony HP Wide Vision HD Camera                     | 16        | 1.06%   |
| Apple FaceTime HD Camera (Built-in)                  | 16        | 1.06%   |
| Acer HD Webcam                                       | 15        | 0.99%   |
| Chicony HP HD Camera                                 | 14        | 0.92%   |
| Lite-On Integrated Camera                            | 13        | 0.86%   |
| Quanta HP TrueVision HD Camera                       | 12        | 0.79%   |
| Quanta HP HD Camera                                  | 12        | 0.79%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 12        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 12        | 0.79%   |
| Samsung Galaxy A5 (MTP)                              | 11        | 0.73%   |
| Chicony HP TrueVision HD Camera                      | 11        | 0.73%   |
| Logitech C920 PRO HD Webcam                          | 9         | 0.59%   |
| IMC Networks HD Camera                               | 9         | 0.59%   |
| Chicony EasyCamera                                   | 9         | 0.59%   |
| Apple Built-in iSight                                | 9         | 0.59%   |
| Quanta USB2.0 HD UVC WebCam                          | 8         | 0.53%   |
| Microdia Webcam Vitade AF                            | 8         | 0.53%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 8         | 0.53%   |
| Logitech C922 Pro Stream Webcam                      | 8         | 0.53%   |
| Lite-On HP Wide Vision HD Camera                     | 8         | 0.53%   |
| Sunplus HD 720P webcam                               | 7         | 0.46%   |
| Primax HP HD Webcam [Fixed]                          | 7         | 0.46%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 7         | 0.46%   |
| Luxvisions Innotech Limited Integrated Camera        | 7         | 0.46%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera     | 7         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 142       | 40%     |
| Validity Sensors           | 76        | 21.41%  |
| Shenzhen Goodix Technology | 74        | 20.85%  |
| Elan Microelectronics      | 23        | 6.48%   |
| LighTuning Technology      | 14        | 3.94%   |
| Upek                       | 10        | 2.82%   |
| AuthenTec                  | 8         | 2.25%   |
| Focal-systems.Corp         | 3         | 0.85%   |
| DigitalPersona             | 2         | 0.56%   |
| STMicroelectronics         | 1         | 0.28%   |
| Samsung Electronics        | 1         | 0.28%   |
| Dell                       | 1         | 0.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 52        | 14.65%  |
| Shenzhen Goodix  Fingerprint Device                                        | 37        | 10.42%  |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 6.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 5.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 4.23%   |
| Elan ELAN:ARM-M4                                                           | 14        | 3.94%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 3.66%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 3.38%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 3.1%    |
| Synaptics UWP WBDI                                                         | 11        | 3.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 2.82%   |
| Validity Sensors VFS491                                                    | 9         | 2.54%   |
| Synaptics WBDI                                                             | 9         | 2.54%   |
| Synaptics  WBDI                                                            | 9         | 2.54%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 2.25%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.97%   |
| Synaptics UWP WBDI Device                                                  | 7         | 1.97%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.97%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.41%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.13%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.85%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.85%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.56%   |
| Synaptics WBDI Device                                                      | 2         | 0.56%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.56%   |
| DigitalPersona Fingerprint Reader                                          | 2         | 0.56%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.28%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.28%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.28%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 53        | 45.69%  |
| Broadcom                   | 38        | 32.76%  |
| Upek                       | 7         | 6.03%   |
| Lenovo                     | 6         | 5.17%   |
| SCM Microsystems           | 3         | 2.59%   |
| OmniKey                    | 2         | 1.72%   |
| O2 Micro                   | 2         | 1.72%   |
| Yubico.com                 | 1         | 0.86%   |
| Realtek Semiconductor      | 1         | 0.86%   |
| Gemalto (was Gemplus)      | 1         | 0.86%   |
| Athena Smartcard Solutions | 1         | 0.86%   |
| Aktiv                      | 1         | 0.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 43.97%  |
| Broadcom 58200                                                               | 16        | 13.79%  |
| Broadcom 5880                                                                | 8         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 6.03%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.03%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 6.03%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.31%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.72%   |
| OmniKey CardMan 1021                                                         | 2         | 1.72%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.86%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.86%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.86%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.86%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 0.86%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.86%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.86%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.86%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.86%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.86%   |
| Aktiv Rutoken lite                                                           | 1         | 0.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1389      | 64.45%  |
| 1     | 628       | 29.14%  |
| 2     | 114       | 5.29%   |
| 3     | 16        | 0.74%   |
| 4     | 3         | 0.14%   |
| 7     | 2         | 0.09%   |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 349       | 38.86%  |
| Graphics card            | 190       | 21.16%  |
| Multimedia controller    | 96        | 10.69%  |
| Net/wireless             | 93        | 10.36%  |
| Camera                   | 46        | 5.12%   |
| Chipcard                 | 24        | 2.67%   |
| Bluetooth                | 23        | 2.56%   |
| Sound                    | 13        | 1.45%   |
| Card reader              | 11        | 1.22%   |
| Communication controller | 10        | 1.11%   |
| Storage                  | 9         | 1%      |
| Network                  | 9         | 1%      |
| Unassigned class         | 8         | 0.89%   |
| Modem                    | 6         | 0.67%   |
| Storage/raid             | 4         | 0.45%   |
| Net/ethernet             | 4         | 0.45%   |
| Wireless                 | 1         | 0.11%   |
| Tv card                  | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |

