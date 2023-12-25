Linux in Italy - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 12808

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [33ab4000ee](https://linux-hardware.org/?probe=33ab4000ee) | Dec 24, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [aef21854a2](https://linux-hardware.org/?probe=aef21854a2) | Dec 23, 2023 |
| PC Special... | GK7NP5R                     | Notebook    | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [40ba77bcb8](https://linux-hardware.org/?probe=40ba77bcb8) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | Notebook    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [f30aec24c2](https://linux-hardware.org/?probe=f30aec24c2) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ab3cc8a89c](https://linux-hardware.org/?probe=ab3cc8a89c) | Dec 23, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [69571c0b91](https://linux-hardware.org/?probe=69571c0b91) | Dec 23, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [0275987230](https://linux-hardware.org/?probe=0275987230) | Dec 22, 2023 |
| AZW           | MINI S 10                   | Desktop     | [59d6fa667d](https://linux-hardware.org/?probe=59d6fa667d) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [e1225d2a37](https://linux-hardware.org/?probe=e1225d2a37) | Dec 22, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [83fd663b68](https://linux-hardware.org/?probe=83fd663b68) | Dec 22, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [60690b9d12](https://linux-hardware.org/?probe=60690b9d12) | Dec 22, 2023 |
| ASUSTek       | N551VW                      | Notebook    | [f73a190483](https://linux-hardware.org/?probe=f73a190483) | Dec 22, 2023 |
| ASUSTek       | N551VW                      | Notebook    | [467015083e](https://linux-hardware.org/?probe=467015083e) | Dec 22, 2023 |
| Dell          | Latitude 5501               | Notebook    | [0b6206153c](https://linux-hardware.org/?probe=0b6206153c) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [db6db43604](https://linux-hardware.org/?probe=db6db43604) | Dec 22, 2023 |
| HP            | Notebook                    | Notebook    | [7541fcf0c8](https://linux-hardware.org/?probe=7541fcf0c8) | Dec 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | Notebook    | [093906d110](https://linux-hardware.org/?probe=093906d110) | Dec 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [9fea6c876a](https://linux-hardware.org/?probe=9fea6c876a) | Dec 21, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [dd67c36ae3](https://linux-hardware.org/?probe=dd67c36ae3) | Dec 21, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [77760018a7](https://linux-hardware.org/?probe=77760018a7) | Dec 21, 2023 |
| HP            | 876C SMVB                   | Desktop     | [c13f4eb91b](https://linux-hardware.org/?probe=c13f4eb91b) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [ebaf3f3e71](https://linux-hardware.org/?probe=ebaf3f3e71) | Dec 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [fb2877e727](https://linux-hardware.org/?probe=fb2877e727) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [ad6cf02d18](https://linux-hardware.org/?probe=ad6cf02d18) | Dec 21, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [5e7428fc75](https://linux-hardware.org/?probe=5e7428fc75) | Dec 21, 2023 |
| HP            | 18E7                        | Desktop     | [fdb8b2d229](https://linux-hardware.org/?probe=fdb8b2d229) | Dec 21, 2023 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [16a8e6f875](https://linux-hardware.org/?probe=16a8e6f875) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [13432c28a6](https://linux-hardware.org/?probe=13432c28a6) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [0eb55bee7d](https://linux-hardware.org/?probe=0eb55bee7d) | Dec 20, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [1c3113c9b9](https://linux-hardware.org/?probe=1c3113c9b9) | Dec 20, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [18f5888ad5](https://linux-hardware.org/?probe=18f5888ad5) | Dec 20, 2023 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [942da4e853](https://linux-hardware.org/?probe=942da4e853) | Dec 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [2785a8b9c6](https://linux-hardware.org/?probe=2785a8b9c6) | Dec 20, 2023 |
| Lenovo        | 317C NOK                    | Desktop     | [87064e6d98](https://linux-hardware.org/?probe=87064e6d98) | Dec 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [398a10f8ce](https://linux-hardware.org/?probe=398a10f8ce) | Dec 20, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [d6a5b20ac6](https://linux-hardware.org/?probe=d6a5b20ac6) | Dec 20, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [23e7499358](https://linux-hardware.org/?probe=23e7499358) | Dec 20, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [06984b497c](https://linux-hardware.org/?probe=06984b497c) | Dec 20, 2023 |
| Lenovo        | ThinkPad S430 336457G       | Notebook    | [4acd70fc9f](https://linux-hardware.org/?probe=4acd70fc9f) | Dec 19, 2023 |
| Google        | Treeya                      | Notebook    | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1038e25caf](https://linux-hardware.org/?probe=1038e25caf) | Dec 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [8dac564efb](https://linux-hardware.org/?probe=8dac564efb) | Dec 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6184376b69](https://linux-hardware.org/?probe=6184376b69) | Dec 19, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [2501635862](https://linux-hardware.org/?probe=2501635862) | Dec 18, 2023 |
| HP            | 255 G1                      | Notebook    | [42faa8c263](https://linux-hardware.org/?probe=42faa8c263) | Dec 18, 2023 |
| HP            | 18E7                        | Desktop     | [20a3bd6bee](https://linux-hardware.org/?probe=20a3bd6bee) | Dec 17, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [cb94175bab](https://linux-hardware.org/?probe=cb94175bab) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [d1dcdfda30](https://linux-hardware.org/?probe=d1dcdfda30) | Dec 17, 2023 |
| Samsung       | 750XDA                      | Notebook    | [bdaba42db8](https://linux-hardware.org/?probe=bdaba42db8) | Dec 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [448a2dec7d](https://linux-hardware.org/?probe=448a2dec7d) | Dec 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ebfec06632](https://linux-hardware.org/?probe=ebfec06632) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [185314f313](https://linux-hardware.org/?probe=185314f313) | Dec 17, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [40545204ea](https://linux-hardware.org/?probe=40545204ea) | Dec 17, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [4ace5aeebe](https://linux-hardware.org/?probe=4ace5aeebe) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [87d3b447bb](https://linux-hardware.org/?probe=87d3b447bb) | Dec 17, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [7ff498fc83](https://linux-hardware.org/?probe=7ff498fc83) | Dec 17, 2023 |
| HP            | Notebook                    | Notebook    | [09981b3a71](https://linux-hardware.org/?probe=09981b3a71) | Dec 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [b595a47be1](https://linux-hardware.org/?probe=b595a47be1) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [78a88bfe8c](https://linux-hardware.org/?probe=78a88bfe8c) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [8833b0a058](https://linux-hardware.org/?probe=8833b0a058) | Dec 17, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [2335d46852](https://linux-hardware.org/?probe=2335d46852) | Dec 17, 2023 |
| HP            | 1790                        | Desktop     | [2d8c859110](https://linux-hardware.org/?probe=2d8c859110) | Dec 17, 2023 |
| Google        | Droid                       | Notebook    | [f08b6f3c68](https://linux-hardware.org/?probe=f08b6f3c68) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [8adfc82dc5](https://linux-hardware.org/?probe=8adfc82dc5) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [492e654dfb](https://linux-hardware.org/?probe=492e654dfb) | Dec 17, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [1442626988](https://linux-hardware.org/?probe=1442626988) | Dec 16, 2023 |
| Acer          | FIH57                       | Desktop     | [0edb232edf](https://linux-hardware.org/?probe=0edb232edf) | Dec 16, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [476c368866](https://linux-hardware.org/?probe=476c368866) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [7162b25b98](https://linux-hardware.org/?probe=7162b25b98) | Dec 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [57a64ca85e](https://linux-hardware.org/?probe=57a64ca85e) | Dec 16, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6e6dfdc457](https://linux-hardware.org/?probe=6e6dfdc457) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [2c4dba512d](https://linux-hardware.org/?probe=2c4dba512d) | Dec 16, 2023 |
| ASUSTek       | PRIME H510M-A WIFI          | Desktop     | [e97f16f34e](https://linux-hardware.org/?probe=e97f16f34e) | Dec 16, 2023 |
| HP            | 1790                        | Desktop     | [9bb2d6fcb4](https://linux-hardware.org/?probe=9bb2d6fcb4) | Dec 16, 2023 |
| HP            | 8653 A                      | Desktop     | [186fc771e8](https://linux-hardware.org/?probe=186fc771e8) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [7567b51bda](https://linux-hardware.org/?probe=7567b51bda) | Dec 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [678b41c4e7](https://linux-hardware.org/?probe=678b41c4e7) | Dec 16, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [50ad2630fb](https://linux-hardware.org/?probe=50ad2630fb) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [281c56510a](https://linux-hardware.org/?probe=281c56510a) | Dec 15, 2023 |
| Dell          | 0M5WNK A02                  | Desktop     | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e5916c58ec](https://linux-hardware.org/?probe=e5916c58ec) | Dec 15, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [94560c4ce8](https://linux-hardware.org/?probe=94560c4ce8) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [37495b67c9](https://linux-hardware.org/?probe=37495b67c9) | Dec 15, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [c3604a3f0d](https://linux-hardware.org/?probe=c3604a3f0d) | Dec 15, 2023 |
| HP            | 18E7                        | Desktop     | [5923f47c4b](https://linux-hardware.org/?probe=5923f47c4b) | Dec 15, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [49d4000148](https://linux-hardware.org/?probe=49d4000148) | Dec 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [166f55ae0b](https://linux-hardware.org/?probe=166f55ae0b) | Dec 15, 2023 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [e0e94706d7](https://linux-hardware.org/?probe=e0e94706d7) | Dec 15, 2023 |
| Acer          | MCP7A                       | Desktop     | [12708a342e](https://linux-hardware.org/?probe=12708a342e) | Dec 14, 2023 |
| HP            | ProBook 6450b               | Notebook    | [f63d5aa0f6](https://linux-hardware.org/?probe=f63d5aa0f6) | Dec 14, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| HP            | ProBook 6450b               | Notebook    | [1a762fe797](https://linux-hardware.org/?probe=1a762fe797) | Dec 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [8dd696472d](https://linux-hardware.org/?probe=8dd696472d) | Dec 14, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| Medion        | E16401                      | Notebook    | [0c81bbcb2b](https://linux-hardware.org/?probe=0c81bbcb2b) | Dec 14, 2023 |
| HP            | Notebook                    | Notebook    | [ac92e1373d](https://linux-hardware.org/?probe=ac92e1373d) | Dec 14, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [00f636bb09](https://linux-hardware.org/?probe=00f636bb09) | Dec 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [56b77e5a7d](https://linux-hardware.org/?probe=56b77e5a7d) | Dec 14, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [35a6370b07](https://linux-hardware.org/?probe=35a6370b07) | Dec 14, 2023 |
| HP            | 15                          | Notebook    | [2343c72691](https://linux-hardware.org/?probe=2343c72691) | Dec 13, 2023 |
| HP            | Laptop 17-by4xxx            | Notebook    | [0c728e7b27](https://linux-hardware.org/?probe=0c728e7b27) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [efe4c56706](https://linux-hardware.org/?probe=efe4c56706) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [c6a0ea6b45](https://linux-hardware.org/?probe=c6a0ea6b45) | Dec 13, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1785db3e7b](https://linux-hardware.org/?probe=1785db3e7b) | Dec 13, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [6e8b956266](https://linux-hardware.org/?probe=6e8b956266) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [b0c03a26ce](https://linux-hardware.org/?probe=b0c03a26ce) | Dec 13, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [5435277f12](https://linux-hardware.org/?probe=5435277f12) | Dec 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6a497408c3](https://linux-hardware.org/?probe=6a497408c3) | Dec 13, 2023 |
| HP            | 2AA7 H                      | Desktop     | [5e9703dff5](https://linux-hardware.org/?probe=5e9703dff5) | Dec 13, 2023 |
| HP            | 8169                        | Desktop     | [4f4439a6fb](https://linux-hardware.org/?probe=4f4439a6fb) | Dec 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6407db19a5](https://linux-hardware.org/?probe=6407db19a5) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cfa115323d](https://linux-hardware.org/?probe=cfa115323d) | Dec 13, 2023 |
| Valve         | Galileo                     | Notebook    | [d6ea0e047a](https://linux-hardware.org/?probe=d6ea0e047a) | Dec 13, 2023 |
| HP            | 15                          | Notebook    | [9c4fb8f41d](https://linux-hardware.org/?probe=9c4fb8f41d) | Dec 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS0TD00    | Notebook    | [e9df2cf93b](https://linux-hardware.org/?probe=e9df2cf93b) | Dec 12, 2023 |
| HP            | 829A                        | Mini pc     | [ba2b33f645](https://linux-hardware.org/?probe=ba2b33f645) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4cffef33b7](https://linux-hardware.org/?probe=4cffef33b7) | Dec 12, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [774925ed25](https://linux-hardware.org/?probe=774925ed25) | Dec 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a128efcd01](https://linux-hardware.org/?probe=a128efcd01) | Dec 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [894c4cf9fb](https://linux-hardware.org/?probe=894c4cf9fb) | Dec 12, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [5d637d06a3](https://linux-hardware.org/?probe=5d637d06a3) | Dec 12, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [3e8d09cc67](https://linux-hardware.org/?probe=3e8d09cc67) | Dec 12, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [27cbfe44c9](https://linux-hardware.org/?probe=27cbfe44c9) | Dec 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [1e1b5e9985](https://linux-hardware.org/?probe=1e1b5e9985) | Dec 12, 2023 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [34c5aec887](https://linux-hardware.org/?probe=34c5aec887) | Dec 12, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [a9d7c866c5](https://linux-hardware.org/?probe=a9d7c866c5) | Dec 12, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c12ada5b78](https://linux-hardware.org/?probe=c12ada5b78) | Dec 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7e201ea559](https://linux-hardware.org/?probe=7e201ea559) | Dec 11, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [1b4243a8d7](https://linux-hardware.org/?probe=1b4243a8d7) | Dec 11, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [48475b71d7](https://linux-hardware.org/?probe=48475b71d7) | Dec 11, 2023 |
| HP            | 255 G5                      | Notebook    | [9001fa872f](https://linux-hardware.org/?probe=9001fa872f) | Dec 11, 2023 |
| HP            | 255 G5                      | Notebook    | [d7df759d96](https://linux-hardware.org/?probe=d7df759d96) | Dec 11, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [9607b32c37](https://linux-hardware.org/?probe=9607b32c37) | Dec 11, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [d4c74075be](https://linux-hardware.org/?probe=d4c74075be) | Dec 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [584a9a153e](https://linux-hardware.org/?probe=584a9a153e) | Dec 11, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [30c8f1f622](https://linux-hardware.org/?probe=30c8f1f622) | Dec 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [2c6a120dd2](https://linux-hardware.org/?probe=2c6a120dd2) | Dec 10, 2023 |
| HP            | 3032h                       | Desktop     | [ca8902be00](https://linux-hardware.org/?probe=ca8902be00) | Dec 10, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [205a5c1696](https://linux-hardware.org/?probe=205a5c1696) | Dec 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [dc0acbdb23](https://linux-hardware.org/?probe=dc0acbdb23) | Dec 10, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [b9760dcf5a](https://linux-hardware.org/?probe=b9760dcf5a) | Dec 10, 2023 |
| MSI           | 970A-G46                    | Desktop     | [86bd084c44](https://linux-hardware.org/?probe=86bd084c44) | Dec 10, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [201fa157d6](https://linux-hardware.org/?probe=201fa157d6) | Dec 10, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [6e718e8473](https://linux-hardware.org/?probe=6e718e8473) | Dec 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [241c795a70](https://linux-hardware.org/?probe=241c795a70) | Dec 10, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [408ad7dd06](https://linux-hardware.org/?probe=408ad7dd06) | Dec 10, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [58ad170a68](https://linux-hardware.org/?probe=58ad170a68) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [bc8d773d9d](https://linux-hardware.org/?probe=bc8d773d9d) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [04e25c9660](https://linux-hardware.org/?probe=04e25c9660) | Dec 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [31821d09d8](https://linux-hardware.org/?probe=31821d09d8) | Dec 09, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [a51f4ce5e5](https://linux-hardware.org/?probe=a51f4ce5e5) | Dec 09, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [cbe77e84b7](https://linux-hardware.org/?probe=cbe77e84b7) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a0919a7fc](https://linux-hardware.org/?probe=7a0919a7fc) | Dec 09, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [5e6fc96a08](https://linux-hardware.org/?probe=5e6fc96a08) | Dec 09, 2023 |
| ASUSTek       | F1A55-M LE R2.0             | Desktop     | [83885aa02c](https://linux-hardware.org/?probe=83885aa02c) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [4684efbcaa](https://linux-hardware.org/?probe=4684efbcaa) | Dec 09, 2023 |
| Acer          | AOD270                      | Notebook    | [b5729a6428](https://linux-hardware.org/?probe=b5729a6428) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [5c1ffcfbe3](https://linux-hardware.org/?probe=5c1ffcfbe3) | Dec 09, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ad002286ac](https://linux-hardware.org/?probe=ad002286ac) | Dec 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [cf693d5429](https://linux-hardware.org/?probe=cf693d5429) | Dec 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [f61425f9af](https://linux-hardware.org/?probe=f61425f9af) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [47aafe0845](https://linux-hardware.org/?probe=47aafe0845) | Dec 08, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [40fae6bc6c](https://linux-hardware.org/?probe=40fae6bc6c) | Dec 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [afd88ac5ea](https://linux-hardware.org/?probe=afd88ac5ea) | Dec 08, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [a4eb4e410e](https://linux-hardware.org/?probe=a4eb4e410e) | Dec 08, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [5451582602](https://linux-hardware.org/?probe=5451582602) | Dec 08, 2023 |
| Dell          | 04YP6J A01                  | Desktop     | [186bb25f07](https://linux-hardware.org/?probe=186bb25f07) | Dec 08, 2023 |
| HP            | Compaq 610                  | Notebook    | [6104f16206](https://linux-hardware.org/?probe=6104f16206) | Dec 07, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [9a042578ee](https://linux-hardware.org/?probe=9a042578ee) | Dec 07, 2023 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | Notebook    | [f7511ff0d0](https://linux-hardware.org/?probe=f7511ff0d0) | Dec 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a39b24be90](https://linux-hardware.org/?probe=a39b24be90) | Dec 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [7144bda606](https://linux-hardware.org/?probe=7144bda606) | Dec 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7da432cd55](https://linux-hardware.org/?probe=7da432cd55) | Dec 07, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [572afff34b](https://linux-hardware.org/?probe=572afff34b) | Dec 07, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [2fc70886c6](https://linux-hardware.org/?probe=2fc70886c6) | Dec 07, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [7606deffc4](https://linux-hardware.org/?probe=7606deffc4) | Dec 07, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [96ab8b0be8](https://linux-hardware.org/?probe=96ab8b0be8) | Dec 07, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [8ec5586df3](https://linux-hardware.org/?probe=8ec5586df3) | Dec 07, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [52c0a2e6fa](https://linux-hardware.org/?probe=52c0a2e6fa) | Dec 07, 2023 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [b539c714c4](https://linux-hardware.org/?probe=b539c714c4) | Dec 07, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [4c19d8a91e](https://linux-hardware.org/?probe=4c19d8a91e) | Dec 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bd9d40cd17](https://linux-hardware.org/?probe=bd9d40cd17) | Dec 06, 2023 |
| ASUSTek       | GL702VSK                    | Notebook    | [d8547acd71](https://linux-hardware.org/?probe=d8547acd71) | Dec 06, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [a0391f219b](https://linux-hardware.org/?probe=a0391f219b) | Dec 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6aaaa355d3](https://linux-hardware.org/?probe=6aaaa355d3) | Dec 06, 2023 |
| HP            | 802E                        | Desktop     | [0f4d573a9b](https://linux-hardware.org/?probe=0f4d573a9b) | Dec 06, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [2edc689735](https://linux-hardware.org/?probe=2edc689735) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [7376c1f4cf](https://linux-hardware.org/?probe=7376c1f4cf) | Dec 06, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [26ab67528e](https://linux-hardware.org/?probe=26ab67528e) | Dec 06, 2023 |
| AMI           | Intel                       | Desktop     | [8649d088c6](https://linux-hardware.org/?probe=8649d088c6) | Dec 06, 2023 |
| HP            | 802E                        | Desktop     | [9b58aa9c3a](https://linux-hardware.org/?probe=9b58aa9c3a) | Dec 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [f42e951aa3](https://linux-hardware.org/?probe=f42e951aa3) | Dec 05, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [1be5bb95d1](https://linux-hardware.org/?probe=1be5bb95d1) | Dec 05, 2023 |
| Intel         | Unknown                     | Desktop     | [3ae9554945](https://linux-hardware.org/?probe=3ae9554945) | Dec 05, 2023 |
| Acer          | TravelMate P414-51          | Notebook    | [bc31600bfa](https://linux-hardware.org/?probe=bc31600bfa) | Dec 05, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [0d7f21475d](https://linux-hardware.org/?probe=0d7f21475d) | Dec 05, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [06fe795e93](https://linux-hardware.org/?probe=06fe795e93) | Dec 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [044e8ae8d6](https://linux-hardware.org/?probe=044e8ae8d6) | Dec 05, 2023 |
| ASUSTek       | GL702VSK                    | Notebook    | [20e6076fd3](https://linux-hardware.org/?probe=20e6076fd3) | Dec 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [56dab5d412](https://linux-hardware.org/?probe=56dab5d412) | Dec 04, 2023 |
| Lenovo        | ThinkPad X280 20KFS0ND00    | Notebook    | [b95db311ed](https://linux-hardware.org/?probe=b95db311ed) | Dec 04, 2023 |
| Acer          | AOD270                      | Notebook    | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [3965451e6d](https://linux-hardware.org/?probe=3965451e6d) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d91e8dc1a8](https://linux-hardware.org/?probe=d91e8dc1a8) | Dec 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8fd5e3b166](https://linux-hardware.org/?probe=8fd5e3b166) | Dec 04, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [b24c23dfd1](https://linux-hardware.org/?probe=b24c23dfd1) | Dec 04, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [9acc9cef23](https://linux-hardware.org/?probe=9acc9cef23) | Dec 04, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [3c8e9b9cc4](https://linux-hardware.org/?probe=3c8e9b9cc4) | Dec 04, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [001185a53f](https://linux-hardware.org/?probe=001185a53f) | Dec 04, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [e6d446fcd3](https://linux-hardware.org/?probe=e6d446fcd3) | Dec 04, 2023 |
| HP            | Notebook                    | Notebook    | [f347c4437d](https://linux-hardware.org/?probe=f347c4437d) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [b1fdfbc998](https://linux-hardware.org/?probe=b1fdfbc998) | Dec 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [0f16293fea](https://linux-hardware.org/?probe=0f16293fea) | Dec 03, 2023 |
| HP            | ProBook 470 G5              | Notebook    | [d12c9b1f20](https://linux-hardware.org/?probe=d12c9b1f20) | Dec 03, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ace4fe2fd9](https://linux-hardware.org/?probe=ace4fe2fd9) | Dec 03, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [1f8c488e82](https://linux-hardware.org/?probe=1f8c488e82) | Dec 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [47222bf19c](https://linux-hardware.org/?probe=47222bf19c) | Dec 03, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [5a5296e72f](https://linux-hardware.org/?probe=5a5296e72f) | Dec 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [e1edd54ac3](https://linux-hardware.org/?probe=e1edd54ac3) | Dec 03, 2023 |
| Jumper        | EZbook                      | Notebook    | [54cf2bf1d4](https://linux-hardware.org/?probe=54cf2bf1d4) | Dec 03, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [a28372598e](https://linux-hardware.org/?probe=a28372598e) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [203357a4dd](https://linux-hardware.org/?probe=203357a4dd) | Dec 03, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [288b6a2f75](https://linux-hardware.org/?probe=288b6a2f75) | Dec 02, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [706e9636ca](https://linux-hardware.org/?probe=706e9636ca) | Dec 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [5923988290](https://linux-hardware.org/?probe=5923988290) | Dec 02, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [1c843db61c](https://linux-hardware.org/?probe=1c843db61c) | Dec 02, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [c7563ee3bd](https://linux-hardware.org/?probe=c7563ee3bd) | Dec 02, 2023 |
| Lenovo        | ThinkPad E15 20RD0019IX     | Notebook    | [5d53fe03da](https://linux-hardware.org/?probe=5d53fe03da) | Dec 02, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9516f4d644](https://linux-hardware.org/?probe=9516f4d644) | Dec 02, 2023 |
| HP            | Notebook                    | Notebook    | [399699d1ce](https://linux-hardware.org/?probe=399699d1ce) | Dec 02, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [9e60faee5f](https://linux-hardware.org/?probe=9e60faee5f) | Dec 01, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2f6585635f](https://linux-hardware.org/?probe=2f6585635f) | Dec 01, 2023 |
| HP            | Notebook                    | Notebook    | [0a554c91b1](https://linux-hardware.org/?probe=0a554c91b1) | Dec 01, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [13e072ec20](https://linux-hardware.org/?probe=13e072ec20) | Dec 01, 2023 |
| Dell          | 0NW73C A00                  | Desktop     | [380639dd58](https://linux-hardware.org/?probe=380639dd58) | Dec 01, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [bf9f891fe4](https://linux-hardware.org/?probe=bf9f891fe4) | Dec 01, 2023 |
| Supermicro    | X10SLM-F                    | Server      | [7e32def223](https://linux-hardware.org/?probe=7e32def223) | Dec 01, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [f79a825fcd](https://linux-hardware.org/?probe=f79a825fcd) | Dec 01, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [22263182fb](https://linux-hardware.org/?probe=22263182fb) | Dec 01, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [f17a1eb208](https://linux-hardware.org/?probe=f17a1eb208) | Dec 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [100228341f](https://linux-hardware.org/?probe=100228341f) | Dec 01, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | Notebook    | [f98f84669d](https://linux-hardware.org/?probe=f98f84669d) | Dec 01, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [511b79d4dc](https://linux-hardware.org/?probe=511b79d4dc) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [4ba2fc285f](https://linux-hardware.org/?probe=4ba2fc285f) | Nov 30, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [e9e1177170](https://linux-hardware.org/?probe=e9e1177170) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [0f9a06cc9f](https://linux-hardware.org/?probe=0f9a06cc9f) | Nov 30, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [cba20469ce](https://linux-hardware.org/?probe=cba20469ce) | Nov 30, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [72fc73581b](https://linux-hardware.org/?probe=72fc73581b) | Nov 30, 2023 |
| HP            | ProBook 4540s               | Notebook    | [e1e15771c1](https://linux-hardware.org/?probe=e1e15771c1) | Nov 30, 2023 |
| HP            | Notebook                    | Notebook    | [93464a0904](https://linux-hardware.org/?probe=93464a0904) | Nov 30, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [78a6b232e3](https://linux-hardware.org/?probe=78a6b232e3) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [9fee8c35c3](https://linux-hardware.org/?probe=9fee8c35c3) | Nov 30, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [bc9394652a](https://linux-hardware.org/?probe=bc9394652a) | Nov 30, 2023 |
| HP            | 2AF7                        | Desktop     | [78514a9009](https://linux-hardware.org/?probe=78514a9009) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e0e3a6f229](https://linux-hardware.org/?probe=e0e3a6f229) | Nov 30, 2023 |
| HP            | Pavilion dv6000 (RY647EA... | Notebook    | [9940416812](https://linux-hardware.org/?probe=9940416812) | Nov 30, 2023 |
| AZW           | U59                         | Desktop     | [eccee157da](https://linux-hardware.org/?probe=eccee157da) | Nov 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [659a528e4a](https://linux-hardware.org/?probe=659a528e4a) | Nov 30, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [2b0642c446](https://linux-hardware.org/?probe=2b0642c446) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a27577cb3a](https://linux-hardware.org/?probe=a27577cb3a) | Nov 30, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [e0dead14ab](https://linux-hardware.org/?probe=e0dead14ab) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | Notebook    | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [ea63175ae6](https://linux-hardware.org/?probe=ea63175ae6) | Nov 29, 2023 |
| HP            | 1905                        | Desktop     | [8d1dfc94c1](https://linux-hardware.org/?probe=8d1dfc94c1) | Nov 29, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [be0c718878](https://linux-hardware.org/?probe=be0c718878) | Nov 29, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [616b02b268](https://linux-hardware.org/?probe=616b02b268) | Nov 29, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | Notebook    | [6b83c6bd43](https://linux-hardware.org/?probe=6b83c6bd43) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ff2ae39e03](https://linux-hardware.org/?probe=ff2ae39e03) | Nov 29, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [363701a47c](https://linux-hardware.org/?probe=363701a47c) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a326b802a3](https://linux-hardware.org/?probe=a326b802a3) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | Notebook    | [31b8894b55](https://linux-hardware.org/?probe=31b8894b55) | Nov 29, 2023 |
| HP            | Compaq 610                  | Notebook    | [f0022a2c56](https://linux-hardware.org/?probe=f0022a2c56) | Nov 28, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [a06c08c462](https://linux-hardware.org/?probe=a06c08c462) | Nov 28, 2023 |
| Sony          | VPCEL1E1E                   | Notebook    | [9c88ceb0b0](https://linux-hardware.org/?probe=9c88ceb0b0) | Nov 28, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [21451de65a](https://linux-hardware.org/?probe=21451de65a) | Nov 28, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [f0bd1c9fa9](https://linux-hardware.org/?probe=f0bd1c9fa9) | Nov 28, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [9e6c582721](https://linux-hardware.org/?probe=9e6c582721) | Nov 28, 2023 |
| Dell          | 0WCJNT A04                  | Server      | [3adc9b76ee](https://linux-hardware.org/?probe=3adc9b76ee) | Nov 28, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f502294656](https://linux-hardware.org/?probe=f502294656) | Nov 28, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [95a9c16f88](https://linux-hardware.org/?probe=95a9c16f88) | Nov 28, 2023 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [72f7a18db5](https://linux-hardware.org/?probe=72f7a18db5) | Nov 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [175562cf7d](https://linux-hardware.org/?probe=175562cf7d) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1f830eb37e](https://linux-hardware.org/?probe=1f830eb37e) | Nov 27, 2023 |
| HP            | 250 G3                      | Notebook    | [4bb11e9f60](https://linux-hardware.org/?probe=4bb11e9f60) | Nov 27, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | Notebook    | [399bf1aa5b](https://linux-hardware.org/?probe=399bf1aa5b) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | Notebook    | [705aa34dce](https://linux-hardware.org/?probe=705aa34dce) | Nov 27, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [b2deb81c19](https://linux-hardware.org/?probe=b2deb81c19) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | Notebook    | [569db41ca1](https://linux-hardware.org/?probe=569db41ca1) | Nov 27, 2023 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [38dd158d3e](https://linux-hardware.org/?probe=38dd158d3e) | Nov 27, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [856690d3f5](https://linux-hardware.org/?probe=856690d3f5) | Nov 27, 2023 |
| HP            | 250 G3                      | Notebook    | [275991de58](https://linux-hardware.org/?probe=275991de58) | Nov 27, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | Desktop     | [532f8ccb97](https://linux-hardware.org/?probe=532f8ccb97) | Nov 27, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [c744967be3](https://linux-hardware.org/?probe=c744967be3) | Nov 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3342bb8661](https://linux-hardware.org/?probe=3342bb8661) | Nov 27, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [b89bce359a](https://linux-hardware.org/?probe=b89bce359a) | Nov 27, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8474959120](https://linux-hardware.org/?probe=8474959120) | Nov 26, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [235bae508c](https://linux-hardware.org/?probe=235bae508c) | Nov 26, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [c314753a7c](https://linux-hardware.org/?probe=c314753a7c) | Nov 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [5f41ceb8ee](https://linux-hardware.org/?probe=5f41ceb8ee) | Nov 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [af468259f2](https://linux-hardware.org/?probe=af468259f2) | Nov 26, 2023 |
| HP            | 630                         | Notebook    | [cd7a4c040d](https://linux-hardware.org/?probe=cd7a4c040d) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [351dde4845](https://linux-hardware.org/?probe=351dde4845) | Nov 26, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [b25d830579](https://linux-hardware.org/?probe=b25d830579) | Nov 26, 2023 |
| HP            | 250 G1                      | Notebook    | [ac68122660](https://linux-hardware.org/?probe=ac68122660) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [7ea3637c4f](https://linux-hardware.org/?probe=7ea3637c4f) | Nov 26, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [d647ccba36](https://linux-hardware.org/?probe=d647ccba36) | Nov 26, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TM... | Notebook    | [c333f48b93](https://linux-hardware.org/?probe=c333f48b93) | Nov 26, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [be2ff8350a](https://linux-hardware.org/?probe=be2ff8350a) | Nov 26, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [3c423ffe17](https://linux-hardware.org/?probe=3c423ffe17) | Nov 26, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [439d50f8cc](https://linux-hardware.org/?probe=439d50f8cc) | Nov 26, 2023 |
| HP            | ENVY 15                     | Notebook    | [66a7391daf](https://linux-hardware.org/?probe=66a7391daf) | Nov 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e18bd022e8](https://linux-hardware.org/?probe=e18bd022e8) | Nov 25, 2023 |
| Chuwi         | Hi10 plus tablet            | Tablet      | [d5306a60da](https://linux-hardware.org/?probe=d5306a60da) | Nov 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [8cba28d4a5](https://linux-hardware.org/?probe=8cba28d4a5) | Nov 25, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [3ffe3ca5b7](https://linux-hardware.org/?probe=3ffe3ca5b7) | Nov 25, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [a80073b9be](https://linux-hardware.org/?probe=a80073b9be) | Nov 25, 2023 |
| Acer          | TravelMate P215-51          | Notebook    | [fd03901ed8](https://linux-hardware.org/?probe=fd03901ed8) | Nov 25, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [a3ff822987](https://linux-hardware.org/?probe=a3ff822987) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [23914b5dc2](https://linux-hardware.org/?probe=23914b5dc2) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e7d72eaf1d](https://linux-hardware.org/?probe=e7d72eaf1d) | Nov 25, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [ab26a80bc5](https://linux-hardware.org/?probe=ab26a80bc5) | Nov 25, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [a76eab064b](https://linux-hardware.org/?probe=a76eab064b) | Nov 25, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [51198853ca](https://linux-hardware.org/?probe=51198853ca) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [261d00b9c1](https://linux-hardware.org/?probe=261d00b9c1) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [fe4e9cf955](https://linux-hardware.org/?probe=fe4e9cf955) | Nov 25, 2023 |
| Dell          | Inspiron 15-7579            | Notebook    | [ece1644afb](https://linux-hardware.org/?probe=ece1644afb) | Nov 25, 2023 |
| DERE          | Unknown                     | Tablet      | [0b81551c86](https://linux-hardware.org/?probe=0b81551c86) | Nov 24, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [30586cdeb5](https://linux-hardware.org/?probe=30586cdeb5) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e39da12205](https://linux-hardware.org/?probe=e39da12205) | Nov 24, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3730101bfb](https://linux-hardware.org/?probe=3730101bfb) | Nov 24, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [dfe4473084](https://linux-hardware.org/?probe=dfe4473084) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | Notebook    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| MSI           | B550M PRO                   | Desktop     | [e834bc66b9](https://linux-hardware.org/?probe=e834bc66b9) | Nov 24, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [422a19e5a3](https://linux-hardware.org/?probe=422a19e5a3) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [499c7927dd](https://linux-hardware.org/?probe=499c7927dd) | Nov 23, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [502e296060](https://linux-hardware.org/?probe=502e296060) | Nov 23, 2023 |
| Unknown       | M17                         | Notebook    | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [95e7fd0511](https://linux-hardware.org/?probe=95e7fd0511) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9102327ebf](https://linux-hardware.org/?probe=9102327ebf) | Nov 23, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [1c9b64b051](https://linux-hardware.org/?probe=1c9b64b051) | Nov 23, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [9d7f74829e](https://linux-hardware.org/?probe=9d7f74829e) | Nov 23, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [30f2717a78](https://linux-hardware.org/?probe=30f2717a78) | Nov 23, 2023 |
| Chuwi         | X312B                       | Notebook    | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| ASRock        | X370 Gaming X               | Notebook    | [0c39910834](https://linux-hardware.org/?probe=0c39910834) | Nov 23, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [415b88184f](https://linux-hardware.org/?probe=415b88184f) | Nov 23, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [e01de3faf5](https://linux-hardware.org/?probe=e01de3faf5) | Nov 23, 2023 |
| HP            | 2B2C                        | Desktop     | [406c00d62a](https://linux-hardware.org/?probe=406c00d62a) | Nov 23, 2023 |
| Acer          | Aspire Z5610                | All in one  | [1390f1811a](https://linux-hardware.org/?probe=1390f1811a) | Nov 23, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [1097230d3f](https://linux-hardware.org/?probe=1097230d3f) | Nov 23, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [53ebec827d](https://linux-hardware.org/?probe=53ebec827d) | Nov 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [f918e70d3e](https://linux-hardware.org/?probe=f918e70d3e) | Nov 22, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [1a8702d13b](https://linux-hardware.org/?probe=1a8702d13b) | Nov 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [39c4acf035](https://linux-hardware.org/?probe=39c4acf035) | Nov 22, 2023 |
| ASUSTek       | BM2AD_D510MT_D310MT         | Desktop     | [03140aee39](https://linux-hardware.org/?probe=03140aee39) | Nov 22, 2023 |
| Acer          | TravelMate P2510-G2-M       | Notebook    | [262eaee181](https://linux-hardware.org/?probe=262eaee181) | Nov 22, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [ceffa3f19e](https://linux-hardware.org/?probe=ceffa3f19e) | Nov 22, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [fa85f5740d](https://linux-hardware.org/?probe=fa85f5740d) | Nov 22, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e73f1050cc](https://linux-hardware.org/?probe=e73f1050cc) | Nov 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [28729f536b](https://linux-hardware.org/?probe=28729f536b) | Nov 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4d128b611f](https://linux-hardware.org/?probe=4d128b611f) | Nov 22, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | Desktop     | [887bb8aabe](https://linux-hardware.org/?probe=887bb8aabe) | Nov 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e28d68acd6](https://linux-hardware.org/?probe=e28d68acd6) | Nov 21, 2023 |
| HP            | 18E7                        | Desktop     | [594059fee8](https://linux-hardware.org/?probe=594059fee8) | Nov 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [d3f91d31f6](https://linux-hardware.org/?probe=d3f91d31f6) | Nov 21, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [de97cb0d6f](https://linux-hardware.org/?probe=de97cb0d6f) | Nov 21, 2023 |
| HP            | 2AA7 H                      | Desktop     | [c98041f477](https://linux-hardware.org/?probe=c98041f477) | Nov 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [a6efd4193b](https://linux-hardware.org/?probe=a6efd4193b) | Nov 21, 2023 |
| Mediacom      | FlexBook edge11 - M-FBE1... | Notebook    | [9b0835e62d](https://linux-hardware.org/?probe=9b0835e62d) | Nov 21, 2023 |
| HP            | ProBook 4540s               | Notebook    | [59a7759558](https://linux-hardware.org/?probe=59a7759558) | Nov 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d91c731a96](https://linux-hardware.org/?probe=d91c731a96) | Nov 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [7fe73d7cf1](https://linux-hardware.org/?probe=7fe73d7cf1) | Nov 21, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [84df454a40](https://linux-hardware.org/?probe=84df454a40) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4191c265d7](https://linux-hardware.org/?probe=4191c265d7) | Nov 20, 2023 |
| MSI           | Thin GF63 12VF              | Notebook    | [ca1a9ef401](https://linux-hardware.org/?probe=ca1a9ef401) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Dell          | Latitude E6230              | Notebook    | [467d45ff38](https://linux-hardware.org/?probe=467d45ff38) | Nov 20, 2023 |
| HP            | 1905                        | Desktop     | [7f22b93c4b](https://linux-hardware.org/?probe=7f22b93c4b) | Nov 20, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [4464a0ee93](https://linux-hardware.org/?probe=4464a0ee93) | Nov 20, 2023 |
| HP            | Pavilion g6                 | Notebook    | [b81902d8d5](https://linux-hardware.org/?probe=b81902d8d5) | Nov 20, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [13e6e37377](https://linux-hardware.org/?probe=13e6e37377) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [6acae93e45](https://linux-hardware.org/?probe=6acae93e45) | Nov 19, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [7b5f6c8151](https://linux-hardware.org/?probe=7b5f6c8151) | Nov 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0B70... | Notebook    | [808b3a2a5d](https://linux-hardware.org/?probe=808b3a2a5d) | Nov 19, 2023 |
| Gigabyte      | Z690M AORUS ELITE AX DDR... | Desktop     | [e723e12a01](https://linux-hardware.org/?probe=e723e12a01) | Nov 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5c6de74207](https://linux-hardware.org/?probe=5c6de74207) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c75a0b3c07](https://linux-hardware.org/?probe=c75a0b3c07) | Nov 19, 2023 |
| Lenovo        | IdeaPad U330 Touch 20268    | Notebook    | [63884f09c6](https://linux-hardware.org/?probe=63884f09c6) | Nov 19, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [8f389f95a6](https://linux-hardware.org/?probe=8f389f95a6) | Nov 19, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [8f99d241f8](https://linux-hardware.org/?probe=8f99d241f8) | Nov 19, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [b20c5c71dd](https://linux-hardware.org/?probe=b20c5c71dd) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d957a1a8c5](https://linux-hardware.org/?probe=d957a1a8c5) | Nov 19, 2023 |
| HP            | 1905                        | Desktop     | [19cc0187db](https://linux-hardware.org/?probe=19cc0187db) | Nov 19, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [cd5e7b0924](https://linux-hardware.org/?probe=cd5e7b0924) | Nov 18, 2023 |
| ASUSTek       | K501UXM                     | Notebook    | [727b1debe1](https://linux-hardware.org/?probe=727b1debe1) | Nov 18, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [850a7f4e8e](https://linux-hardware.org/?probe=850a7f4e8e) | Nov 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [87132187f5](https://linux-hardware.org/?probe=87132187f5) | Nov 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [ed47d2c01d](https://linux-hardware.org/?probe=ed47d2c01d) | Nov 18, 2023 |
| HP            | ENVY dv6                    | Notebook    | [136bb5cac4](https://linux-hardware.org/?probe=136bb5cac4) | Nov 18, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [90d21a5044](https://linux-hardware.org/?probe=90d21a5044) | Nov 18, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [76c00a164a](https://linux-hardware.org/?probe=76c00a164a) | Nov 18, 2023 |
| ASRock        | 970 Performance             | Desktop     | [7b106f5305](https://linux-hardware.org/?probe=7b106f5305) | Nov 18, 2023 |
| Lenovo        | ThinkPad T530 23924FJ       | Notebook    | [b7a94da831](https://linux-hardware.org/?probe=b7a94da831) | Nov 17, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [eb8b271929](https://linux-hardware.org/?probe=eb8b271929) | Nov 17, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [51f28bbefb](https://linux-hardware.org/?probe=51f28bbefb) | Nov 17, 2023 |
| HP            | ENVY dv6                    | Notebook    | [58263cedeb](https://linux-hardware.org/?probe=58263cedeb) | Nov 17, 2023 |
| SiComputer    | Nauta 01E                   | Notebook    | [1631e065bd](https://linux-hardware.org/?probe=1631e065bd) | Nov 17, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [756a8e0f19](https://linux-hardware.org/?probe=756a8e0f19) | Nov 17, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [e52328d89f](https://linux-hardware.org/?probe=e52328d89f) | Nov 17, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [cdb7f0682b](https://linux-hardware.org/?probe=cdb7f0682b) | Nov 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [0619c3b255](https://linux-hardware.org/?probe=0619c3b255) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ff84b6e035](https://linux-hardware.org/?probe=ff84b6e035) | Nov 17, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [41d4402bf3](https://linux-hardware.org/?probe=41d4402bf3) | Nov 17, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [5a6066ab8c](https://linux-hardware.org/?probe=5a6066ab8c) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3204f2ad9f](https://linux-hardware.org/?probe=3204f2ad9f) | Nov 17, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [8274f1048a](https://linux-hardware.org/?probe=8274f1048a) | Nov 16, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [663c18d823](https://linux-hardware.org/?probe=663c18d823) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | Notebook    | [ba85d81d10](https://linux-hardware.org/?probe=ba85d81d10) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | Notebook    | [b2c3886395](https://linux-hardware.org/?probe=b2c3886395) | Nov 16, 2023 |
| HP            | 650                         | Notebook    | [86c4ffd3cc](https://linux-hardware.org/?probe=86c4ffd3cc) | Nov 16, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [ded5bb92bd](https://linux-hardware.org/?probe=ded5bb92bd) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7813c5e090](https://linux-hardware.org/?probe=7813c5e090) | Nov 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9096161802](https://linux-hardware.org/?probe=9096161802) | Nov 16, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [d1800f3356](https://linux-hardware.org/?probe=d1800f3356) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [925c8180fc](https://linux-hardware.org/?probe=925c8180fc) | Nov 16, 2023 |
| HP            | 650                         | Notebook    | [262ff4134d](https://linux-hardware.org/?probe=262ff4134d) | Nov 16, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [9443883eaf](https://linux-hardware.org/?probe=9443883eaf) | Nov 16, 2023 |
| Acer          | Extensa 5220                | Notebook    | [313dfe3829](https://linux-hardware.org/?probe=313dfe3829) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470 20HES04Q00    | Notebook    | [ebb179e02e](https://linux-hardware.org/?probe=ebb179e02e) | Nov 16, 2023 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [e4ac0f919f](https://linux-hardware.org/?probe=e4ac0f919f) | Nov 16, 2023 |
| Dell          | Vostro 16 5630              | Notebook    | [5716490407](https://linux-hardware.org/?probe=5716490407) | Nov 16, 2023 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [07a1bedd9b](https://linux-hardware.org/?probe=07a1bedd9b) | Nov 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [90b6757607](https://linux-hardware.org/?probe=90b6757607) | Nov 15, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [a21066a759](https://linux-hardware.org/?probe=a21066a759) | Nov 15, 2023 |
| Acer          | Extensa 5220                | Notebook    | [6b5e8902be](https://linux-hardware.org/?probe=6b5e8902be) | Nov 15, 2023 |
| HP            | 3031h                       | Desktop     | [41814a3ce4](https://linux-hardware.org/?probe=41814a3ce4) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [378bb9c07b](https://linux-hardware.org/?probe=378bb9c07b) | Nov 15, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [492ee4603f](https://linux-hardware.org/?probe=492ee4603f) | Nov 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7404738ed](https://linux-hardware.org/?probe=a7404738ed) | Nov 15, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [e6e07a90bf](https://linux-hardware.org/?probe=e6e07a90bf) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [0fae742aa3](https://linux-hardware.org/?probe=0fae742aa3) | Nov 15, 2023 |
| Dell          | 0HX555                      | Desktop     | [ca73b21791](https://linux-hardware.org/?probe=ca73b21791) | Nov 15, 2023 |
| HP            | Notebook                    | Notebook    | [2048deb542](https://linux-hardware.org/?probe=2048deb542) | Nov 15, 2023 |
| Dell          | Latitude E5540              | Notebook    | [75c5f17cf5](https://linux-hardware.org/?probe=75c5f17cf5) | Nov 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [4d7c838629](https://linux-hardware.org/?probe=4d7c838629) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ec3e7b63cb](https://linux-hardware.org/?probe=ec3e7b63cb) | Nov 14, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [5fbfbad938](https://linux-hardware.org/?probe=5fbfbad938) | Nov 14, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a6f59c7877](https://linux-hardware.org/?probe=a6f59c7877) | Nov 14, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [41e315a3e5](https://linux-hardware.org/?probe=41e315a3e5) | Nov 14, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [9d1c329ebb](https://linux-hardware.org/?probe=9d1c329ebb) | Nov 14, 2023 |
| Acer          | Extensa 2540                | Notebook    | [22e65d0a5b](https://linux-hardware.org/?probe=22e65d0a5b) | Nov 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a09eca53d5](https://linux-hardware.org/?probe=a09eca53d5) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | Notebook    | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | Notebook    | [3567b57191](https://linux-hardware.org/?probe=3567b57191) | Nov 14, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [c4b486ecb1](https://linux-hardware.org/?probe=c4b486ecb1) | Nov 13, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [42d05f19a2](https://linux-hardware.org/?probe=42d05f19a2) | Nov 13, 2023 |
| AZW           | Speed S                     | Desktop     | [d855e4476a](https://linux-hardware.org/?probe=d855e4476a) | Nov 13, 2023 |
| ASUSTek       | X55U                        | Notebook    | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision M4800             | Notebook    | [9a63057a12](https://linux-hardware.org/?probe=9a63057a12) | Nov 13, 2023 |
| HP            | ENVY 15                     | Notebook    | [b8ee2c11e1](https://linux-hardware.org/?probe=b8ee2c11e1) | Nov 13, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [accf863283](https://linux-hardware.org/?probe=accf863283) | Nov 13, 2023 |
| AMI           | Intel                       | Desktop     | [7c96434a18](https://linux-hardware.org/?probe=7c96434a18) | Nov 13, 2023 |
| HP            | 198E                        | Desktop     | [ea1760ddb6](https://linux-hardware.org/?probe=ea1760ddb6) | Nov 13, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [ca10e0d0f3](https://linux-hardware.org/?probe=ca10e0d0f3) | Nov 13, 2023 |
| HP            | 650                         | Notebook    | [c1ca175779](https://linux-hardware.org/?probe=c1ca175779) | Nov 12, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [ec1ca3afc1](https://linux-hardware.org/?probe=ec1ca3afc1) | Nov 12, 2023 |
| Dell          | Latitude 5580               | Notebook    | [4343277d0b](https://linux-hardware.org/?probe=4343277d0b) | Nov 12, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [539da3b61a](https://linux-hardware.org/?probe=539da3b61a) | Nov 12, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [872e6f2ca5](https://linux-hardware.org/?probe=872e6f2ca5) | Nov 12, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [7c3fc962ca](https://linux-hardware.org/?probe=7c3fc962ca) | Nov 12, 2023 |
| Dell          | Inspiron ME051              | Notebook    | [e0114c60de](https://linux-hardware.org/?probe=e0114c60de) | Nov 12, 2023 |
| Jumper        | EZbook                      | Notebook    | [682c154cdb](https://linux-hardware.org/?probe=682c154cdb) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fa8b97688](https://linux-hardware.org/?probe=2fa8b97688) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| Acer          | Aspire Z5610                | All in one  | [509a290097](https://linux-hardware.org/?probe=509a290097) | Nov 12, 2023 |
| HP            | 15                          | Notebook    | [dbd704fdbb](https://linux-hardware.org/?probe=dbd704fdbb) | Nov 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0ff417d90e](https://linux-hardware.org/?probe=0ff417d90e) | Nov 11, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [a833e9377a](https://linux-hardware.org/?probe=a833e9377a) | Nov 11, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [044d37ef79](https://linux-hardware.org/?probe=044d37ef79) | Nov 11, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3ab7186c9c](https://linux-hardware.org/?probe=3ab7186c9c) | Nov 11, 2023 |
| Acer          | Predator PT515-52           | Notebook    | [4f5c31bd64](https://linux-hardware.org/?probe=4f5c31bd64) | Nov 11, 2023 |
| Acer          | Predator PT515-52           | Notebook    | [ac3ab44d32](https://linux-hardware.org/?probe=ac3ab44d32) | Nov 11, 2023 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [a634797954](https://linux-hardware.org/?probe=a634797954) | Nov 11, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [b0bf1f1ac1](https://linux-hardware.org/?probe=b0bf1f1ac1) | Nov 11, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [9c77400bbf](https://linux-hardware.org/?probe=9c77400bbf) | Nov 11, 2023 |
| ASUSTek       | X202E                       | Notebook    | [b78da681e7](https://linux-hardware.org/?probe=b78da681e7) | Nov 11, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [9fde81d361](https://linux-hardware.org/?probe=9fde81d361) | Nov 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b88ecdebac](https://linux-hardware.org/?probe=b88ecdebac) | Nov 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4a09ae9d2](https://linux-hardware.org/?probe=e4a09ae9d2) | Nov 10, 2023 |
| Sony          | VPCEB1S1E                   | Notebook    | [b0d4e06348](https://linux-hardware.org/?probe=b0d4e06348) | Nov 10, 2023 |
| HP            | 1998                        | Desktop     | [3843c1d8d9](https://linux-hardware.org/?probe=3843c1d8d9) | Nov 10, 2023 |
| HP            | Pavilion g6                 | Notebook    | [450bb23de1](https://linux-hardware.org/?probe=450bb23de1) | Nov 10, 2023 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [dd73474667](https://linux-hardware.org/?probe=dd73474667) | Nov 10, 2023 |
| Dynabook      | PORTEGE X30L-G              | Notebook    | [64326392ac](https://linux-hardware.org/?probe=64326392ac) | Nov 10, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [fab830af79](https://linux-hardware.org/?probe=fab830af79) | Nov 10, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2788382d20](https://linux-hardware.org/?probe=2788382d20) | Nov 10, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [89b0efe7ed](https://linux-hardware.org/?probe=89b0efe7ed) | Nov 10, 2023 |
| Acer          | Veriton X2611G V1.0         | Desktop     | [aaca941b62](https://linux-hardware.org/?probe=aaca941b62) | Nov 10, 2023 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [6155a9c2ec](https://linux-hardware.org/?probe=6155a9c2ec) | Nov 10, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [906f638c34](https://linux-hardware.org/?probe=906f638c34) | Nov 10, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [cfc1427577](https://linux-hardware.org/?probe=cfc1427577) | Nov 10, 2023 |
| HP            | 3397                        | Desktop     | [83e88e81bf](https://linux-hardware.org/?probe=83e88e81bf) | Nov 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [644bf9e936](https://linux-hardware.org/?probe=644bf9e936) | Nov 09, 2023 |
| HP            | 250 G1                      | Notebook    | [a06122606d](https://linux-hardware.org/?probe=a06122606d) | Nov 09, 2023 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [5a58d53135](https://linux-hardware.org/?probe=5a58d53135) | Nov 09, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [43c69e6055](https://linux-hardware.org/?probe=43c69e6055) | Nov 09, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [448165ceca](https://linux-hardware.org/?probe=448165ceca) | Nov 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c6f89c817](https://linux-hardware.org/?probe=2c6f89c817) | Nov 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5c243dae6b](https://linux-hardware.org/?probe=5c243dae6b) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [e55e321a2e](https://linux-hardware.org/?probe=e55e321a2e) | Nov 09, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [46261b27de](https://linux-hardware.org/?probe=46261b27de) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [840241bcdd](https://linux-hardware.org/?probe=840241bcdd) | Nov 09, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [27571092d5](https://linux-hardware.org/?probe=27571092d5) | Nov 09, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [50a18dd494](https://linux-hardware.org/?probe=50a18dd494) | Nov 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [f5a16ecf27](https://linux-hardware.org/?probe=f5a16ecf27) | Nov 09, 2023 |
| Dell          | Latitude 5420               | Notebook    | [efa8caa859](https://linux-hardware.org/?probe=efa8caa859) | Nov 09, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [30673db04e](https://linux-hardware.org/?probe=30673db04e) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [6f78d1f11d](https://linux-hardware.org/?probe=6f78d1f11d) | Nov 08, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [3f45bd8f8d](https://linux-hardware.org/?probe=3f45bd8f8d) | Nov 08, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [a26aceca7f](https://linux-hardware.org/?probe=a26aceca7f) | Nov 08, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [e83f07f0c3](https://linux-hardware.org/?probe=e83f07f0c3) | Nov 08, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [47bd2b5230](https://linux-hardware.org/?probe=47bd2b5230) | Nov 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [96c0d6f52c](https://linux-hardware.org/?probe=96c0d6f52c) | Nov 08, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8ba89e650a](https://linux-hardware.org/?probe=8ba89e650a) | Nov 08, 2023 |
| ZOTAC         | ZBOX                        | Mini pc     | [c2064210a3](https://linux-hardware.org/?probe=c2064210a3) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [25fd8cabab](https://linux-hardware.org/?probe=25fd8cabab) | Nov 08, 2023 |
| Olivetti      | P55-AEU-323-4G320           | Notebook    | [5d53de5c7d](https://linux-hardware.org/?probe=5d53de5c7d) | Nov 08, 2023 |
| MSI           | Z790 GAMING PRO WIFI        | Desktop     | [44fcbf488b](https://linux-hardware.org/?probe=44fcbf488b) | Nov 08, 2023 |
| Lenovo        | ThinkPad T495 20NKS1YE00    | Notebook    | [ad892a8aea](https://linux-hardware.org/?probe=ad892a8aea) | Nov 07, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2259df96c0](https://linux-hardware.org/?probe=2259df96c0) | Nov 07, 2023 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [aa6ebeeff2](https://linux-hardware.org/?probe=aa6ebeeff2) | Nov 07, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [4f31a7817f](https://linux-hardware.org/?probe=4f31a7817f) | Nov 07, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a599d9b486](https://linux-hardware.org/?probe=a599d9b486) | Nov 07, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [c85bdae7e5](https://linux-hardware.org/?probe=c85bdae7e5) | Nov 07, 2023 |
| HP            | 8437                        | Desktop     | [818f52c6f0](https://linux-hardware.org/?probe=818f52c6f0) | Nov 07, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [1a8df0d5de](https://linux-hardware.org/?probe=1a8df0d5de) | Nov 07, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c2a37daf7d](https://linux-hardware.org/?probe=c2a37daf7d) | Nov 07, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [220d14894a](https://linux-hardware.org/?probe=220d14894a) | Nov 07, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XJ... | Notebook    | [5756bdb835](https://linux-hardware.org/?probe=5756bdb835) | Nov 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e874ddf25c](https://linux-hardware.org/?probe=e874ddf25c) | Nov 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [9f1e875996](https://linux-hardware.org/?probe=9f1e875996) | Nov 07, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [75a2534386](https://linux-hardware.org/?probe=75a2534386) | Nov 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [f93d40f708](https://linux-hardware.org/?probe=f93d40f708) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [166a9aee87](https://linux-hardware.org/?probe=166a9aee87) | Nov 06, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| HP            | 1495                        | Desktop     | [9bc696067b](https://linux-hardware.org/?probe=9bc696067b) | Nov 06, 2023 |
| NZXT          | N7 B550                     | Desktop     | [082ee28ba2](https://linux-hardware.org/?probe=082ee28ba2) | Nov 06, 2023 |
| HP            | 8458                        | Mini pc     | [3004e844fd](https://linux-hardware.org/?probe=3004e844fd) | Nov 06, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [98bc0094ec](https://linux-hardware.org/?probe=98bc0094ec) | Nov 06, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [83e5c381b2](https://linux-hardware.org/?probe=83e5c381b2) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [3cd8e36ab1](https://linux-hardware.org/?probe=3cd8e36ab1) | Nov 06, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [df52b675c8](https://linux-hardware.org/?probe=df52b675c8) | Nov 06, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [fe01dc6819](https://linux-hardware.org/?probe=fe01dc6819) | Nov 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0009d8a468](https://linux-hardware.org/?probe=0009d8a468) | Nov 06, 2023 |
| ASRock        | H110M-ITX                   | Desktop     | [c384352141](https://linux-hardware.org/?probe=c384352141) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [62b6928793](https://linux-hardware.org/?probe=62b6928793) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [10f2785958](https://linux-hardware.org/?probe=10f2785958) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [07ef51bd31](https://linux-hardware.org/?probe=07ef51bd31) | Nov 05, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [a8c249eafd](https://linux-hardware.org/?probe=a8c249eafd) | Nov 05, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [6407166dd5](https://linux-hardware.org/?probe=6407166dd5) | Nov 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3a69031984](https://linux-hardware.org/?probe=3a69031984) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8e3e7668cf](https://linux-hardware.org/?probe=8e3e7668cf) | Nov 05, 2023 |
| Sony          | VGN-N21S_W                  | Notebook    | [6ff4658440](https://linux-hardware.org/?probe=6ff4658440) | Nov 05, 2023 |
| Sony          | VGN-N21S_W                  | Notebook    | [266bedfdc3](https://linux-hardware.org/?probe=266bedfdc3) | Nov 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a1500e2e9c](https://linux-hardware.org/?probe=a1500e2e9c) | Nov 05, 2023 |
| HP            | 530                         | Notebook    | [710ba89827](https://linux-hardware.org/?probe=710ba89827) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [034b113ac8](https://linux-hardware.org/?probe=034b113ac8) | Nov 05, 2023 |
| HP            | Notebook                    | Notebook    | [8eea1901f7](https://linux-hardware.org/?probe=8eea1901f7) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a42da62572](https://linux-hardware.org/?probe=a42da62572) | Nov 05, 2023 |
| Lenovo        | ThinkPad X250 20CM001UUK    | Notebook    | [b0fd9fa3c0](https://linux-hardware.org/?probe=b0fd9fa3c0) | Nov 05, 2023 |
| HP            | 1998                        | Desktop     | [d454314b77](https://linux-hardware.org/?probe=d454314b77) | Nov 05, 2023 |
| ASRockRack    | EPC602D8A                   | Desktop     | [c1b6c06dc5](https://linux-hardware.org/?probe=c1b6c06dc5) | Nov 05, 2023 |
| ASUSTek       | UX370UAR                    | Convertible | [754b927267](https://linux-hardware.org/?probe=754b927267) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [62798aa8cf](https://linux-hardware.org/?probe=62798aa8cf) | Nov 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dd81ed04ea](https://linux-hardware.org/?probe=dd81ed04ea) | Nov 04, 2023 |
| Acer          | Aspire M1920                | Desktop     | [f6ffcb0c41](https://linux-hardware.org/?probe=f6ffcb0c41) | Nov 04, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [14dc35a1b9](https://linux-hardware.org/?probe=14dc35a1b9) | Nov 04, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [2b5c984cd8](https://linux-hardware.org/?probe=2b5c984cd8) | Nov 04, 2023 |
| HP            | Notebook                    | Notebook    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [76acaae6cc](https://linux-hardware.org/?probe=76acaae6cc) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [34e4bd156f](https://linux-hardware.org/?probe=34e4bd156f) | Nov 04, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7d38ea5f87](https://linux-hardware.org/?probe=7d38ea5f87) | Nov 04, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [d4b22ac16a](https://linux-hardware.org/?probe=d4b22ac16a) | Nov 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3922b02290](https://linux-hardware.org/?probe=3922b02290) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2d1116cd1b](https://linux-hardware.org/?probe=2d1116cd1b) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [798cba826c](https://linux-hardware.org/?probe=798cba826c) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c601304f7](https://linux-hardware.org/?probe=2c601304f7) | Nov 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bb7622a7ba](https://linux-hardware.org/?probe=bb7622a7ba) | Nov 04, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [8685e384af](https://linux-hardware.org/?probe=8685e384af) | Nov 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [547a248361](https://linux-hardware.org/?probe=547a248361) | Nov 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [574e5fd946](https://linux-hardware.org/?probe=574e5fd946) | Nov 03, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [4eae8e67db](https://linux-hardware.org/?probe=4eae8e67db) | Nov 03, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [44890192a1](https://linux-hardware.org/?probe=44890192a1) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ce98faee85](https://linux-hardware.org/?probe=ce98faee85) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [5339cc53ed](https://linux-hardware.org/?probe=5339cc53ed) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [157f3bd86a](https://linux-hardware.org/?probe=157f3bd86a) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [645fbe9fc3](https://linux-hardware.org/?probe=645fbe9fc3) | Nov 03, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [9c089ed10c](https://linux-hardware.org/?probe=9c089ed10c) | Nov 03, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [f16aeca403](https://linux-hardware.org/?probe=f16aeca403) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [2314e30b70](https://linux-hardware.org/?probe=2314e30b70) | Nov 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [ad12644dff](https://linux-hardware.org/?probe=ad12644dff) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7aa3982cb4](https://linux-hardware.org/?probe=7aa3982cb4) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [62579a601d](https://linux-hardware.org/?probe=62579a601d) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [9cabd6fd2c](https://linux-hardware.org/?probe=9cabd6fd2c) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [3414d178f2](https://linux-hardware.org/?probe=3414d178f2) | Nov 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ea92d94742](https://linux-hardware.org/?probe=ea92d94742) | Nov 02, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [8ab22982cc](https://linux-hardware.org/?probe=8ab22982cc) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [4d3101d9f8](https://linux-hardware.org/?probe=4d3101d9f8) | Nov 02, 2023 |
| Samsung       | 750XDA                      | Notebook    | [130a1273e5](https://linux-hardware.org/?probe=130a1273e5) | Nov 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0631c3ec84](https://linux-hardware.org/?probe=0631c3ec84) | Nov 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbe345cd5d](https://linux-hardware.org/?probe=bbe345cd5d) | Nov 02, 2023 |
| ASRock        | P67 Professional            | Desktop     | [c998340fa9](https://linux-hardware.org/?probe=c998340fa9) | Nov 02, 2023 |
| Fujitsu       | LIFEBOOK T937               | Convertible | [530a390355](https://linux-hardware.org/?probe=530a390355) | Nov 02, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [9690e7a65f](https://linux-hardware.org/?probe=9690e7a65f) | Nov 02, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [37dc32cd03](https://linux-hardware.org/?probe=37dc32cd03) | Nov 02, 2023 |
| ASRock        | Z77 WS                      | Desktop     | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| Lenovo        | ThinkPad P53 20QN000FIX     | Notebook    | [40de43c266](https://linux-hardware.org/?probe=40de43c266) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| Dell          | 0VC7DK A01                  | Server      | [5339dd25e2](https://linux-hardware.org/?probe=5339dd25e2) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L60017UK    | Notebook    | [e8b030e97f](https://linux-hardware.org/?probe=e8b030e97f) | Nov 02, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [b9532c1f86](https://linux-hardware.org/?probe=b9532c1f86) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [72a5b8f06a](https://linux-hardware.org/?probe=72a5b8f06a) | Nov 02, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [dad897d3c4](https://linux-hardware.org/?probe=dad897d3c4) | Nov 02, 2023 |
| ASRock        | 990FX Extreme3              | Desktop     | [ad8e4a9dae](https://linux-hardware.org/?probe=ad8e4a9dae) | Nov 02, 2023 |
| Acer          | One S1002                   | Notebook    | [a00e6d78a6](https://linux-hardware.org/?probe=a00e6d78a6) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| Chuwi         | CoreBook Pro                | Notebook    | [ac0f4a1ea9](https://linux-hardware.org/?probe=ac0f4a1ea9) | Nov 01, 2023 |
| Unknown       | 1.0                         | Desktop     | [6265787d93](https://linux-hardware.org/?probe=6265787d93) | Nov 01, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f1e35faa1a](https://linux-hardware.org/?probe=f1e35faa1a) | Nov 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [df4f43ca44](https://linux-hardware.org/?probe=df4f43ca44) | Nov 01, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [2de4949247](https://linux-hardware.org/?probe=2de4949247) | Nov 01, 2023 |
| HP            | 822A                        | Desktop     | [59c055e360](https://linux-hardware.org/?probe=59c055e360) | Nov 01, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [47abbeb9c1](https://linux-hardware.org/?probe=47abbeb9c1) | Nov 01, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [9fff1dc94c](https://linux-hardware.org/?probe=9fff1dc94c) | Nov 01, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [ae34108b69](https://linux-hardware.org/?probe=ae34108b69) | Nov 01, 2023 |
| HP            | 630                         | Notebook    | [634f46006b](https://linux-hardware.org/?probe=634f46006b) | Nov 01, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [4fc590fe55](https://linux-hardware.org/?probe=4fc590fe55) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [60edf3f76c](https://linux-hardware.org/?probe=60edf3f76c) | Nov 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ed95443390](https://linux-hardware.org/?probe=ed95443390) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Pegatron      | Benicia                     | Desktop     | [b253f40dc7](https://linux-hardware.org/?probe=b253f40dc7) | Nov 01, 2023 |
| Pegatron      | Benicia                     | Desktop     | [a3378fce47](https://linux-hardware.org/?probe=a3378fce47) | Nov 01, 2023 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [1ab426a7ed](https://linux-hardware.org/?probe=1ab426a7ed) | Nov 01, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [7c88fdcaa3](https://linux-hardware.org/?probe=7c88fdcaa3) | Nov 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1965aca64](https://linux-hardware.org/?probe=d1965aca64) | Nov 01, 2023 |
| HP            | 1497                        | Desktop     | [0fd6a908fe](https://linux-hardware.org/?probe=0fd6a908fe) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX0... | Notebook    | [d5fee530ee](https://linux-hardware.org/?probe=d5fee530ee) | Nov 01, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [0c38487bcf](https://linux-hardware.org/?probe=0c38487bcf) | Nov 01, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [0ea7f00b4e](https://linux-hardware.org/?probe=0ea7f00b4e) | Nov 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [50a30d4ebd](https://linux-hardware.org/?probe=50a30d4ebd) | Nov 01, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1bd48815fe](https://linux-hardware.org/?probe=1bd48815fe) | Nov 01, 2023 |
| Sapphire      | PE-AM2RS690V2               | Desktop     | [2b2de28f02](https://linux-hardware.org/?probe=2b2de28f02) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [0026b681e2](https://linux-hardware.org/?probe=0026b681e2) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | Notebook    | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [301a117426](https://linux-hardware.org/?probe=301a117426) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f557533925](https://linux-hardware.org/?probe=f557533925) | Nov 01, 2023 |
| Microtech     | CoreBookLite                | Notebook    | [1833fd5f0c](https://linux-hardware.org/?probe=1833fd5f0c) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [50880de513](https://linux-hardware.org/?probe=50880de513) | Nov 01, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [399fe59760](https://linux-hardware.org/?probe=399fe59760) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [cd9e941307](https://linux-hardware.org/?probe=cd9e941307) | Nov 01, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [460c9255bd](https://linux-hardware.org/?probe=460c9255bd) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | Notebook    | [0b21a4419d](https://linux-hardware.org/?probe=0b21a4419d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | Notebook    | [757199e3cf](https://linux-hardware.org/?probe=757199e3cf) | Nov 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5da84da52f](https://linux-hardware.org/?probe=5da84da52f) | Oct 31, 2023 |
| Gigabyte      | MJ11-EC1-OT 01000100        | Server      | [9a7be2dcbd](https://linux-hardware.org/?probe=9a7be2dcbd) | Oct 31, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [803bc8d1ed](https://linux-hardware.org/?probe=803bc8d1ed) | Oct 31, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [b24b974555](https://linux-hardware.org/?probe=b24b974555) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6c1c4ea069](https://linux-hardware.org/?probe=6c1c4ea069) | Oct 31, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| ASUSTek       | F5N                         | Notebook    | [8da324b4fa](https://linux-hardware.org/?probe=8da324b4fa) | Oct 31, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [d099ae69e8](https://linux-hardware.org/?probe=d099ae69e8) | Oct 31, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3b79851103](https://linux-hardware.org/?probe=3b79851103) | Oct 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4aa5e757eb](https://linux-hardware.org/?probe=4aa5e757eb) | Oct 31, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [341114c78a](https://linux-hardware.org/?probe=341114c78a) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [d2072a9949](https://linux-hardware.org/?probe=d2072a9949) | Oct 31, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [7b71031ba1](https://linux-hardware.org/?probe=7b71031ba1) | Oct 31, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [3ab77e3324](https://linux-hardware.org/?probe=3ab77e3324) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [1107919053](https://linux-hardware.org/?probe=1107919053) | Oct 31, 2023 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [90b5515582](https://linux-hardware.org/?probe=90b5515582) | Oct 31, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [ea29ba4b58](https://linux-hardware.org/?probe=ea29ba4b58) | Oct 31, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [8e86103e06](https://linux-hardware.org/?probe=8e86103e06) | Oct 31, 2023 |
| Samsung       | 750XED                      | Notebook    | [9dab50e37e](https://linux-hardware.org/?probe=9dab50e37e) | Oct 31, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [4f6d9ac7b5](https://linux-hardware.org/?probe=4f6d9ac7b5) | Oct 31, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [0c6a7cb928](https://linux-hardware.org/?probe=0c6a7cb928) | Oct 31, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [40f30de33b](https://linux-hardware.org/?probe=40f30de33b) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d370c488e4](https://linux-hardware.org/?probe=d370c488e4) | Oct 31, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [55f20f6750](https://linux-hardware.org/?probe=55f20f6750) | Oct 31, 2023 |
| Samsung       | 930XDB/931XDB/930XDY        | Notebook    | [421368e431](https://linux-hardware.org/?probe=421368e431) | Oct 31, 2023 |
| ASUSTek       | BT1AD                       | Desktop     | [133784e5ee](https://linux-hardware.org/?probe=133784e5ee) | Oct 31, 2023 |
| HP            | 18EB                        | Desktop     | [83596ab9d9](https://linux-hardware.org/?probe=83596ab9d9) | Oct 31, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [2b4315885f](https://linux-hardware.org/?probe=2b4315885f) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [90172d9cef](https://linux-hardware.org/?probe=90172d9cef) | Oct 31, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [d802042506](https://linux-hardware.org/?probe=d802042506) | Oct 31, 2023 |
| Dell          | Vostro 3549                 | Notebook    | [259c646ecb](https://linux-hardware.org/?probe=259c646ecb) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [1e3f228931](https://linux-hardware.org/?probe=1e3f228931) | Oct 31, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [56e4a560bc](https://linux-hardware.org/?probe=56e4a560bc) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [10382e8ed6](https://linux-hardware.org/?probe=10382e8ed6) | Oct 31, 2023 |
| AMI           | Intel                       | Notebook    | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [fb56165b30](https://linux-hardware.org/?probe=fb56165b30) | Oct 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [b4e85014cc](https://linux-hardware.org/?probe=b4e85014cc) | Oct 31, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [7941dfd8cf](https://linux-hardware.org/?probe=7941dfd8cf) | Oct 31, 2023 |
| Toshiba       | TECRA S11                   | Notebook    | [e2a669bf1a](https://linux-hardware.org/?probe=e2a669bf1a) | Oct 31, 2023 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [86dd25c85a](https://linux-hardware.org/?probe=86dd25c85a) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | Notebook    | [ebcacada49](https://linux-hardware.org/?probe=ebcacada49) | Oct 31, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [c77bed1e18](https://linux-hardware.org/?probe=c77bed1e18) | Oct 31, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [a0da22e928](https://linux-hardware.org/?probe=a0da22e928) | Oct 31, 2023 |
| ASUSTek       | X550EP                      | Notebook    | [81fdd48960](https://linux-hardware.org/?probe=81fdd48960) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | Notebook    | [d8658ea415](https://linux-hardware.org/?probe=d8658ea415) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [ed27ef3491](https://linux-hardware.org/?probe=ed27ef3491) | Oct 31, 2023 |
| Alienware     | 13 R3                       | Notebook    | [726415f251](https://linux-hardware.org/?probe=726415f251) | Oct 31, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [683545565a](https://linux-hardware.org/?probe=683545565a) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d1e473a77b](https://linux-hardware.org/?probe=d1e473a77b) | Oct 31, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [26533c338a](https://linux-hardware.org/?probe=26533c338a) | Oct 31, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6779e74408](https://linux-hardware.org/?probe=6779e74408) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [2a589a5505](https://linux-hardware.org/?probe=2a589a5505) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [53cd13281b](https://linux-hardware.org/?probe=53cd13281b) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [daa299c314](https://linux-hardware.org/?probe=daa299c314) | Oct 31, 2023 |
| Dell          | Latitude 5520               | Notebook    | [3803e551f1](https://linux-hardware.org/?probe=3803e551f1) | Oct 31, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [11ada26a4c](https://linux-hardware.org/?probe=11ada26a4c) | Oct 31, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [e150519e40](https://linux-hardware.org/?probe=e150519e40) | Oct 31, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [85cb35fdc6](https://linux-hardware.org/?probe=85cb35fdc6) | Oct 31, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f6e8c279ef](https://linux-hardware.org/?probe=f6e8c279ef) | Oct 31, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [fc223b91ed](https://linux-hardware.org/?probe=fc223b91ed) | Oct 31, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ee7bce3de](https://linux-hardware.org/?probe=6ee7bce3de) | Oct 31, 2023 |
| HP            | 86F1 10100                  | All in one  | [d3079638ae](https://linux-hardware.org/?probe=d3079638ae) | Oct 31, 2023 |
| Lenovo        | ThinkPad E470 20H1006KIX    | Notebook    | [d84959fadc](https://linux-hardware.org/?probe=d84959fadc) | Oct 31, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [c1d956674a](https://linux-hardware.org/?probe=c1d956674a) | Oct 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | Notebook    | [2f63bfb399](https://linux-hardware.org/?probe=2f63bfb399) | Oct 31, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [7634c564d0](https://linux-hardware.org/?probe=7634c564d0) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [54a64f0a7e](https://linux-hardware.org/?probe=54a64f0a7e) | Oct 31, 2023 |
| Dell          | Precision M6800             | Notebook    | [72c51649f1](https://linux-hardware.org/?probe=72c51649f1) | Oct 31, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [38b70999b9](https://linux-hardware.org/?probe=38b70999b9) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2eaf76ce92](https://linux-hardware.org/?probe=2eaf76ce92) | Oct 31, 2023 |
| Dell          | Latitude 5414               | Notebook    | [fd7b086e1b](https://linux-hardware.org/?probe=fd7b086e1b) | Oct 31, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [62adc05f6a](https://linux-hardware.org/?probe=62adc05f6a) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 15            | Notebook    | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [e0971c3b56](https://linux-hardware.org/?probe=e0971c3b56) | Oct 31, 2023 |
| Dell          | Latitude 5420               | Notebook    | [c2f4052fb4](https://linux-hardware.org/?probe=c2f4052fb4) | Oct 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ef307df799](https://linux-hardware.org/?probe=ef307df799) | Oct 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [487222ef3e](https://linux-hardware.org/?probe=487222ef3e) | Oct 31, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [1bdd8f14ad](https://linux-hardware.org/?probe=1bdd8f14ad) | Oct 31, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [55f41faf27](https://linux-hardware.org/?probe=55f41faf27) | Oct 31, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [64292785b9](https://linux-hardware.org/?probe=64292785b9) | Oct 31, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [8d764a9632](https://linux-hardware.org/?probe=8d764a9632) | Oct 31, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [01ce498c44](https://linux-hardware.org/?probe=01ce498c44) | Oct 30, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0251ada092](https://linux-hardware.org/?probe=0251ada092) | Oct 30, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [d339ee4dbc](https://linux-hardware.org/?probe=d339ee4dbc) | Oct 30, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [413254deb3](https://linux-hardware.org/?probe=413254deb3) | Oct 30, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [0b62ec2df6](https://linux-hardware.org/?probe=0b62ec2df6) | Oct 30, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [000230db12](https://linux-hardware.org/?probe=000230db12) | Oct 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [32d642cc3b](https://linux-hardware.org/?probe=32d642cc3b) | Oct 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [4bd69e46d1](https://linux-hardware.org/?probe=4bd69e46d1) | Oct 30, 2023 |
| ASUSTek       | X555LP                      | Notebook    | [1f57f57452](https://linux-hardware.org/?probe=1f57f57452) | Oct 30, 2023 |
| Lenovo        | ThinkPad L540 20AV005GIX    | Notebook    | [ca59c544ef](https://linux-hardware.org/?probe=ca59c544ef) | Oct 30, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [d63ccd5259](https://linux-hardware.org/?probe=d63ccd5259) | Oct 30, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [fb33e90b93](https://linux-hardware.org/?probe=fb33e90b93) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [4e5ba58b35](https://linux-hardware.org/?probe=4e5ba58b35) | Oct 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [309695dc7e](https://linux-hardware.org/?probe=309695dc7e) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ab5cef69c3](https://linux-hardware.org/?probe=ab5cef69c3) | Oct 30, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a9a2e2ab03](https://linux-hardware.org/?probe=a9a2e2ab03) | Oct 30, 2023 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [a2faa2b06a](https://linux-hardware.org/?probe=a2faa2b06a) | Oct 30, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [0fb7ced892](https://linux-hardware.org/?probe=0fb7ced892) | Oct 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [28ddca3b76](https://linux-hardware.org/?probe=28ddca3b76) | Oct 30, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [731cb3b152](https://linux-hardware.org/?probe=731cb3b152) | Oct 30, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [4d6c2166c8](https://linux-hardware.org/?probe=4d6c2166c8) | Oct 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [055e34b095](https://linux-hardware.org/?probe=055e34b095) | Oct 30, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [17dd2ce988](https://linux-hardware.org/?probe=17dd2ce988) | Oct 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [25431e9c91](https://linux-hardware.org/?probe=25431e9c91) | Oct 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [508c244637](https://linux-hardware.org/?probe=508c244637) | Oct 30, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [5f8cf197d5](https://linux-hardware.org/?probe=5f8cf197d5) | Oct 30, 2023 |
| Lenovo        | ThinkPad T530 23924FJ       | Notebook    | [c8b87fb249](https://linux-hardware.org/?probe=c8b87fb249) | Oct 30, 2023 |
| ASUSTek       | X555UJ                      | Notebook    | [de6e2775a4](https://linux-hardware.org/?probe=de6e2775a4) | Oct 30, 2023 |
| ASRock        | H77 Pro4-M                  | Desktop     | [83aeda3c64](https://linux-hardware.org/?probe=83aeda3c64) | Oct 30, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [f59457f708](https://linux-hardware.org/?probe=f59457f708) | Oct 30, 2023 |
| Intel         | X99                         | Desktop     | [8f60418655](https://linux-hardware.org/?probe=8f60418655) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [dd2e706549](https://linux-hardware.org/?probe=dd2e706549) | Oct 30, 2023 |
| Lenovo        | ThinkPad T530 23924FJ       | Notebook    | [b64508402a](https://linux-hardware.org/?probe=b64508402a) | Oct 30, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a198e0f9c2](https://linux-hardware.org/?probe=a198e0f9c2) | Oct 30, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fe3816864f](https://linux-hardware.org/?probe=fe3816864f) | Oct 30, 2023 |
| Dell          | Precision 3541              | Notebook    | [6857b35adc](https://linux-hardware.org/?probe=6857b35adc) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| HP            | 21F5 0A                     | Desktop     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f19f70993f](https://linux-hardware.org/?probe=f19f70993f) | Oct 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [64bc9621da](https://linux-hardware.org/?probe=64bc9621da) | Oct 30, 2023 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [47dbfa475a](https://linux-hardware.org/?probe=47dbfa475a) | Oct 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d5debf7011](https://linux-hardware.org/?probe=d5debf7011) | Oct 30, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2b883f993f](https://linux-hardware.org/?probe=2b883f993f) | Oct 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [daffd3cd06](https://linux-hardware.org/?probe=daffd3cd06) | Oct 30, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3f0259e17b](https://linux-hardware.org/?probe=3f0259e17b) | Oct 30, 2023 |
| ASUSTek       | F5N                         | Notebook    | [67f3a19888](https://linux-hardware.org/?probe=67f3a19888) | Oct 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [7bcf41bb9f](https://linux-hardware.org/?probe=7bcf41bb9f) | Oct 30, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [e06f6c5888](https://linux-hardware.org/?probe=e06f6c5888) | Oct 30, 2023 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [c9cb087088](https://linux-hardware.org/?probe=c9cb087088) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [b3e37008cb](https://linux-hardware.org/?probe=b3e37008cb) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| MSI           | GF75 Thin 10UEK             | Notebook    | [a58fbe3576](https://linux-hardware.org/?probe=a58fbe3576) | Oct 30, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [cd7ef88b8a](https://linux-hardware.org/?probe=cd7ef88b8a) | Oct 30, 2023 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [b160015184](https://linux-hardware.org/?probe=b160015184) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59f0a72f7b](https://linux-hardware.org/?probe=59f0a72f7b) | Oct 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [f8df9730e1](https://linux-hardware.org/?probe=f8df9730e1) | Oct 29, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [0c4a5a4137](https://linux-hardware.org/?probe=0c4a5a4137) | Oct 29, 2023 |
| HP            | 829A                        | Mini pc     | [b079de79bf](https://linux-hardware.org/?probe=b079de79bf) | Oct 29, 2023 |
| HP            | Notebook                    | Notebook    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [a72ac510df](https://linux-hardware.org/?probe=a72ac510df) | Oct 29, 2023 |
| HP            | 802E                        | Desktop     | [a57f8d5afa](https://linux-hardware.org/?probe=a57f8d5afa) | Oct 29, 2023 |
| Acer          | Nitro N50-610               | Desktop     | [b83310ffb8](https://linux-hardware.org/?probe=b83310ffb8) | Oct 29, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [3d2fe89bc1](https://linux-hardware.org/?probe=3d2fe89bc1) | Oct 29, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [0ff396f5c2](https://linux-hardware.org/?probe=0ff396f5c2) | Oct 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0f69bc7ea0](https://linux-hardware.org/?probe=0f69bc7ea0) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [65b2874cbb](https://linux-hardware.org/?probe=65b2874cbb) | Oct 28, 2023 |
| HP            | Notebook                    | Notebook    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b65d7d3b4a](https://linux-hardware.org/?probe=b65d7d3b4a) | Oct 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [e3154e94cf](https://linux-hardware.org/?probe=e3154e94cf) | Oct 28, 2023 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [fbaa37f3ad](https://linux-hardware.org/?probe=fbaa37f3ad) | Oct 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [198bee98eb](https://linux-hardware.org/?probe=198bee98eb) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [484d866dc6](https://linux-hardware.org/?probe=484d866dc6) | Oct 27, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a619c8a955](https://linux-hardware.org/?probe=a619c8a955) | Oct 27, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| Foxconn       | 17A0                        | Desktop     | [ce8f3561ee](https://linux-hardware.org/?probe=ce8f3561ee) | Oct 27, 2023 |
| Dell          | 0TY177 A05                  | Server      | [f59dfc5d01](https://linux-hardware.org/?probe=f59dfc5d01) | Oct 27, 2023 |
| HP            | 15                          | Notebook    | [a9e38be5d5](https://linux-hardware.org/?probe=a9e38be5d5) | Oct 27, 2023 |
| Dell          | 0VD5HY A07                  | Desktop     | [3db7e99c4a](https://linux-hardware.org/?probe=3db7e99c4a) | Oct 27, 2023 |
| Dell          | 0GTK4K A02                  | Desktop     | [df85a996c9](https://linux-hardware.org/?probe=df85a996c9) | Oct 27, 2023 |
| Dell          | 0PM2CW A02                  | Server      | [e1bb5de371](https://linux-hardware.org/?probe=e1bb5de371) | Oct 27, 2023 |
| Lenovo        | 376D SDK0T76465 WIN 3422... | Desktop     | [2a97bb6c00](https://linux-hardware.org/?probe=2a97bb6c00) | Oct 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [1971a346bf](https://linux-hardware.org/?probe=1971a346bf) | Oct 27, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [af9b5b05e9](https://linux-hardware.org/?probe=af9b5b05e9) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [50b77f9f9e](https://linux-hardware.org/?probe=50b77f9f9e) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | Desktop     | [a576bfd0b1](https://linux-hardware.org/?probe=a576bfd0b1) | Oct 26, 2023 |
| Unknown       | P4M800CE-8237               | Desktop     | [bf22b887f8](https://linux-hardware.org/?probe=bf22b887f8) | Oct 26, 2023 |
| OrangePi      | Zero3                       | Soc         | [0a9fbc0ea2](https://linux-hardware.org/?probe=0a9fbc0ea2) | Oct 26, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | Notebook    | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [884529eef1](https://linux-hardware.org/?probe=884529eef1) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f32e8922c8](https://linux-hardware.org/?probe=f32e8922c8) | Oct 26, 2023 |
| HP            | 8653 A                      | Desktop     | [07aae59bf1](https://linux-hardware.org/?probe=07aae59bf1) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [e2900eda68](https://linux-hardware.org/?probe=e2900eda68) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| HP            | 15                          | Notebook    | [629c50d53a](https://linux-hardware.org/?probe=629c50d53a) | Oct 25, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [21f871b008](https://linux-hardware.org/?probe=21f871b008) | Oct 25, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [cb2e25f26f](https://linux-hardware.org/?probe=cb2e25f26f) | Oct 25, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [7a88945a88](https://linux-hardware.org/?probe=7a88945a88) | Oct 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [b38766677c](https://linux-hardware.org/?probe=b38766677c) | Oct 25, 2023 |
| Dell          | 0PM2CW A02                  | Server      | [556c0f6d91](https://linux-hardware.org/?probe=556c0f6d91) | Oct 25, 2023 |
| Dell          | 0VD5HY A04                  | Desktop     | [36249c99ec](https://linux-hardware.org/?probe=36249c99ec) | Oct 25, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [5713b2f30e](https://linux-hardware.org/?probe=5713b2f30e) | Oct 24, 2023 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [3626d833e9](https://linux-hardware.org/?probe=3626d833e9) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [0abcd8d89e](https://linux-hardware.org/?probe=0abcd8d89e) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [fb6910c3c6](https://linux-hardware.org/?probe=fb6910c3c6) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [e51b3ff063](https://linux-hardware.org/?probe=e51b3ff063) | Oct 24, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [3669a01d21](https://linux-hardware.org/?probe=3669a01d21) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | Notebook    | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [660547e520](https://linux-hardware.org/?probe=660547e520) | Oct 24, 2023 |
| Acer          | Extensa 5220                | Notebook    | [eda0099ab4](https://linux-hardware.org/?probe=eda0099ab4) | Oct 24, 2023 |
| ASRock        | 880GMH/USB3                 | Desktop     | [4d3fcc56ec](https://linux-hardware.org/?probe=4d3fcc56ec) | Oct 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [dc730f5631](https://linux-hardware.org/?probe=dc730f5631) | Oct 23, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [61791a9250](https://linux-hardware.org/?probe=61791a9250) | Oct 23, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1be0a39692](https://linux-hardware.org/?probe=1be0a39692) | Oct 23, 2023 |
| HP            | 3397                        | Desktop     | [1344d9d38b](https://linux-hardware.org/?probe=1344d9d38b) | Oct 23, 2023 |
| ASUSTek       | X555YI                      | Notebook    | [0028f82c4d](https://linux-hardware.org/?probe=0028f82c4d) | Oct 23, 2023 |
| ASRock        | H81M-DG4                    | Desktop     | [3c73dc5daa](https://linux-hardware.org/?probe=3c73dc5daa) | Oct 23, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [7041a7ac55](https://linux-hardware.org/?probe=7041a7ac55) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [d04399e8fd](https://linux-hardware.org/?probe=d04399e8fd) | Oct 23, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [7981b12a61](https://linux-hardware.org/?probe=7981b12a61) | Oct 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [e3c5d45e2a](https://linux-hardware.org/?probe=e3c5d45e2a) | Oct 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [c725f222a3](https://linux-hardware.org/?probe=c725f222a3) | Oct 22, 2023 |
| Dell          | Latitude E5450              | Notebook    | [0f5e45f8e4](https://linux-hardware.org/?probe=0f5e45f8e4) | Oct 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6adb6574e7](https://linux-hardware.org/?probe=6adb6574e7) | Oct 22, 2023 |
| Acer          | Veriton S2680G              | Desktop     | [da6ff1f2f3](https://linux-hardware.org/?probe=da6ff1f2f3) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [428cf5b8dc](https://linux-hardware.org/?probe=428cf5b8dc) | Oct 21, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [78df342ad3](https://linux-hardware.org/?probe=78df342ad3) | Oct 21, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [41f4b8a93a](https://linux-hardware.org/?probe=41f4b8a93a) | Oct 21, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [cd365d2e35](https://linux-hardware.org/?probe=cd365d2e35) | Oct 21, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [3b1d62c873](https://linux-hardware.org/?probe=3b1d62c873) | Oct 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [943199c6c3](https://linux-hardware.org/?probe=943199c6c3) | Oct 21, 2023 |
| LG Electro... | 17Z90R-G.AP78D              | Notebook    | [8d320eb314](https://linux-hardware.org/?probe=8d320eb314) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f103762ce5](https://linux-hardware.org/?probe=f103762ce5) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [147d6ad175](https://linux-hardware.org/?probe=147d6ad175) | Oct 21, 2023 |
| ASRock        | 870 Extreme3 R2.0           | Desktop     | [a625868a25](https://linux-hardware.org/?probe=a625868a25) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [aed5514f95](https://linux-hardware.org/?probe=aed5514f95) | Oct 21, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [4aa0e3a887](https://linux-hardware.org/?probe=4aa0e3a887) | Oct 21, 2023 |
| Samsung       | R530/R730/P590              | Notebook    | [6a774fbae7](https://linux-hardware.org/?probe=6a774fbae7) | Oct 21, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [23c9a3dea4](https://linux-hardware.org/?probe=23c9a3dea4) | Oct 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [34ffce7f83](https://linux-hardware.org/?probe=34ffce7f83) | Oct 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3b88974986](https://linux-hardware.org/?probe=3b88974986) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES4VB00    | Notebook    | [423a16c64a](https://linux-hardware.org/?probe=423a16c64a) | Oct 20, 2023 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [68b2560530](https://linux-hardware.org/?probe=68b2560530) | Oct 19, 2023 |
| Acer          | AOD270                      | Notebook    | [20d5a5477c](https://linux-hardware.org/?probe=20d5a5477c) | Oct 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aad7482915](https://linux-hardware.org/?probe=aad7482915) | Oct 19, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d5669e2ea8](https://linux-hardware.org/?probe=d5669e2ea8) | Oct 19, 2023 |
| Samsung       | 700T1C                      | Notebook    | [f5668a0ef6](https://linux-hardware.org/?probe=f5668a0ef6) | Oct 19, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ec015a6c9e](https://linux-hardware.org/?probe=ec015a6c9e) | Oct 19, 2023 |
| Dell          | Latitude E7270              | Notebook    | [673245c691](https://linux-hardware.org/?probe=673245c691) | Oct 19, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b73212b85e](https://linux-hardware.org/?probe=b73212b85e) | Oct 18, 2023 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [df8d309418](https://linux-hardware.org/?probe=df8d309418) | Oct 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [1748fce718](https://linux-hardware.org/?probe=1748fce718) | Oct 18, 2023 |
| Dell          | 0MNPJ9 A03                  | Desktop     | [36e7a1e261](https://linux-hardware.org/?probe=36e7a1e261) | Oct 18, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [d906262d01](https://linux-hardware.org/?probe=d906262d01) | Oct 18, 2023 |
| HP            | 18E7                        | Desktop     | [3beee97f8b](https://linux-hardware.org/?probe=3beee97f8b) | Oct 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [dbb30ccac0](https://linux-hardware.org/?probe=dbb30ccac0) | Oct 18, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [8902ce3049](https://linux-hardware.org/?probe=8902ce3049) | Oct 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [7aded01681](https://linux-hardware.org/?probe=7aded01681) | Oct 17, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [42292e1deb](https://linux-hardware.org/?probe=42292e1deb) | Oct 17, 2023 |
| LG Electro... | 17Z90P-G.AA86D              | Notebook    | [afffdd63b5](https://linux-hardware.org/?probe=afffdd63b5) | Oct 17, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | Notebook    | [bb50abd0e6](https://linux-hardware.org/?probe=bb50abd0e6) | Oct 17, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [f3bd5c6632](https://linux-hardware.org/?probe=f3bd5c6632) | Oct 17, 2023 |
| Samsung       | 930QCG                      | Convertible | [26595d7bc0](https://linux-hardware.org/?probe=26595d7bc0) | Oct 17, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [85e4efe1d3](https://linux-hardware.org/?probe=85e4efe1d3) | Oct 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [843098c658](https://linux-hardware.org/?probe=843098c658) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [87edaec977](https://linux-hardware.org/?probe=87edaec977) | Oct 17, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e28562a4d2](https://linux-hardware.org/?probe=e28562a4d2) | Oct 17, 2023 |
| Dell          | XPS 9315                    | Notebook    | [e629bbd153](https://linux-hardware.org/?probe=e629bbd153) | Oct 16, 2023 |
| Dell          | XPS 9315                    | Notebook    | [a0b5099438](https://linux-hardware.org/?probe=a0b5099438) | Oct 16, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | Notebook    | [ddeaca23b4](https://linux-hardware.org/?probe=ddeaca23b4) | Oct 16, 2023 |
| HP            | 250 G4                      | Notebook    | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | Notebook    | [3b0d979b69](https://linux-hardware.org/?probe=3b0d979b69) | Oct 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | Notebook    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [084e18e78d](https://linux-hardware.org/?probe=084e18e78d) | Oct 15, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [5cc901b874](https://linux-hardware.org/?probe=5cc901b874) | Oct 15, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [6b4ccf6ef7](https://linux-hardware.org/?probe=6b4ccf6ef7) | Oct 15, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [3c6ab62b00](https://linux-hardware.org/?probe=3c6ab62b00) | Oct 15, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9bda720e30](https://linux-hardware.org/?probe=9bda720e30) | Oct 15, 2023 |
| LG Electro... | 14Z990-V.AR52D              | Notebook    | [9e7942d027](https://linux-hardware.org/?probe=9e7942d027) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | Notebook    | [c7b57a58b7](https://linux-hardware.org/?probe=c7b57a58b7) | Oct 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bc33324b0d](https://linux-hardware.org/?probe=bc33324b0d) | Oct 15, 2023 |
| HP            | Compaq 610                  | Notebook    | [78e999ba70](https://linux-hardware.org/?probe=78e999ba70) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| Trigkey       | S5 V2.0                     | Mini pc     | [5639ebab82](https://linux-hardware.org/?probe=5639ebab82) | Oct 15, 2023 |
| HP            | 15                          | Notebook    | [7cde663ae0](https://linux-hardware.org/?probe=7cde663ae0) | Oct 15, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [cf68d0c810](https://linux-hardware.org/?probe=cf68d0c810) | Oct 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 919       | 9.95%   |
| Ubuntu 22.04                 | 601       | 6.51%   |
| Ubuntu 18.04                 | 568       | 6.15%   |
| Arch Rolling                 | 314       | 3.4%    |
| OpenMandriva 4.2             | 221       | 2.39%   |
| Debian 11                    | 218       | 2.36%   |
| OpenMandriva 4.3             | 197       | 2.13%   |
| Linux Mint 21.1              | 154       | 1.67%   |
| Fedora 36                    | 152       | 1.65%   |
| Pop!_OS 22.04                | 141       | 1.53%   |
| Zorin 16                     | 133       | 1.44%   |
| Ubuntu 22.10                 | 132       | 1.43%   |
| Ubuntu 20.10                 | 131       | 1.42%   |
| Fedora 38                    | 130       | 1.41%   |
| Arch                         | 123       | 1.33%   |
| Ubuntu 19.10                 | 120       | 1.3%    |
| EndeavourOS Rolling          | 120       | 1.3%    |
| Linux Mint 20.3              | 117       | 1.27%   |
| Xubuntu 18.04                | 108       | 1.17%   |
| Ubuntu 19.04                 | 108       | 1.17%   |
| Xubuntu 20.04                | 104       | 1.13%   |
| OpenMandriva 23.03           | 103       | 1.12%   |
| Fedora 37                    | 103       | 1.12%   |
| KDE neon 20.04               | 102       | 1.1%    |
| Linux Mint 21.2              | 97        | 1.05%   |
| Linux Mint 21                | 97        | 1.05%   |
| Ubuntu 21.10                 | 96        | 1.04%   |
| OpenMandriva 23.01           | 93        | 1.01%   |
| Debian 12                    | 87        | 0.94%   |
| Ubuntu 21.04                 | 84        | 0.91%   |
| Kubuntu 22.04                | 84        | 0.91%   |
| Debian 10                    | 83        | 0.9%    |
| Manjaro                      | 81        | 0.88%   |
| Ubuntu 23.04                 | 74        | 0.8%    |
| openSUSE Tumbleweed-XXXXXXXX | 74        | 0.8%    |
| Zorin 15                     | 71        | 0.77%   |
| Ubuntu 18.10                 | 68        | 0.74%   |
| Fedora 35                    | 68        | 0.74%   |
| Linux Mint 19.3              | 66        | 0.71%   |
| Kubuntu 20.04                | 66        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2813      | 32.49%  |
| OpenMandriva  | 736       | 8.5%    |
| Linux Mint    | 700       | 8.09%   |
| Fedora        | 610       | 7.05%   |
| Debian        | 456       | 5.27%   |
| Arch          | 427       | 4.93%   |
| Xubuntu       | 320       | 3.7%    |
| Pop!_OS       | 288       | 3.33%   |
| Kubuntu       | 250       | 2.89%   |
| Manjaro       | 249       | 2.88%   |
| Zorin         | 214       | 2.47%   |
| ROSA          | 192       | 2.22%   |
| KDE neon      | 154       | 1.78%   |
| EndeavourOS   | 126       | 1.46%   |
| Lubuntu       | 106       | 1.22%   |
| openSUSE      | 105       | 1.21%   |
| Ubuntu MATE   | 90        | 1.04%   |
| Elementary    | 69        | 0.8%    |
| ArcoLinux     | 58        | 0.67%   |
| LMDE          | 52        | 0.6%    |
| Endless       | 48        | 0.55%   |
| Ubuntu Unity  | 46        | 0.53%   |
| Clear Linux   | 40        | 0.46%   |
| MX            | 39        | 0.45%   |
| Gentoo        | 39        | 0.45%   |
| BlackPanther  | 36        | 0.42%   |
| Kali          | 33        | 0.38%   |
| Garuda Linux  | 33        | 0.38%   |
| Ubuntu Budgie | 24        | 0.28%   |
| Peppermint    | 21        | 0.24%   |
| Nobara        | 21        | 0.24%   |
| SteamOS       | 20        | 0.23%   |
| Parrot        | 17        | 0.2%    |
| NixOS         | 15        | 0.17%   |
| Xero          | 14        | 0.16%   |
| Ubuntu Studio | 12        | 0.14%   |
| Raspbian      | 12        | 0.14%   |
| LinuxFX       | 12        | 0.14%   |
| Slackware     | 10        | 0.12%   |
| CentOS        | 10        | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 214       | 2.08%   |
| 5.16.7-desktop-1omv4003  | 185       | 1.8%    |
| 5.15.0-52-generic        | 169       | 1.65%   |
| 5.4.0-42-generic         | 125       | 1.22%   |
| 5.15.0-56-generic        | 123       | 1.2%    |
| 6.2.6-desktop-1omv2390   | 102       | 0.99%   |
| 5.4.0-52-generic         | 81        | 0.79%   |
| 6.1.1-desktop-1omv2290   | 78        | 0.76%   |
| 5.15.0-58-generic        | 76        | 0.74%   |
| 5.15.0-47-generic        | 71        | 0.69%   |
| 5.4.0-26-generic         | 68        | 0.66%   |
| 5.3.0-46-generic         | 66        | 0.64%   |
| 5.15.0-46-generic        | 65        | 0.63%   |
| 5.4.0-58-generic         | 61        | 0.59%   |
| 5.4.0-29-generic         | 59        | 0.57%   |
| 5.3.0-40-generic         | 58        | 0.57%   |
| 5.4.0-48-generic         | 56        | 0.55%   |
| 5.15.0-43-generic        | 55        | 0.54%   |
| 6.4.11-desktop-1omv2390  | 53        | 0.52%   |
| 5.3.0-42-generic         | 48        | 0.47%   |
| 5.4.0-54-generic         | 46        | 0.45%   |
| 6.2.0-26-generic         | 45        | 0.44%   |
| 6.2.0-36-generic         | 44        | 0.43%   |
| 5.10.0-19-amd64          | 43        | 0.42%   |
| 6.1.0-13-amd64           | 42        | 0.41%   |
| 5.19.0-35-generic        | 41        | 0.4%    |
| 5.19.0-23-generic        | 41        | 0.4%    |
| 5.15.0-76-generic        | 41        | 0.4%    |
| 5.15.0-60-generic        | 41        | 0.4%    |
| 5.15.0-53-generic        | 41        | 0.4%    |
| 5.15.0-41-generic        | 41        | 0.4%    |
| 6.0.2-arch1-1            | 40        | 0.39%   |
| 5.4.0-28-generic         | 40        | 0.39%   |
| 5.19.0-32-generic        | 40        | 0.39%   |
| 6.5.9-arch2-1            | 39        | 0.38%   |
| 5.15.0-88-generic        | 39        | 0.38%   |
| 5.0.0-37-generic         | 39        | 0.38%   |
| 5.4.0-56-generic         | 38        | 0.37%   |
| 5.4.0-37-generic         | 38        | 0.37%   |
| 5.4.0-33-generic         | 38        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1290      | 13.47%  |
| 5.15.0  | 1027      | 10.73%  |
| 4.15.0  | 474       | 4.95%   |
| 5.8.0   | 396       | 4.14%   |
| 5.19.0  | 389       | 4.06%   |
| 5.3.0   | 385       | 4.02%   |
| 5.11.0  | 310       | 3.24%   |
| 5.13.0  | 303       | 3.16%   |
| 6.2.0   | 289       | 3.02%   |
| 5.10.0  | 257       | 2.68%   |
| 5.0.0   | 224       | 2.34%   |
| 5.10.14 | 215       | 2.25%   |
| 5.16.7  | 188       | 1.96%   |
| 4.18.0  | 159       | 1.66%   |
| 6.2.6   | 129       | 1.35%   |
| 6.1.0   | 127       | 1.33%   |
| 6.1.1   | 91        | 0.95%   |
| 6.5.0   | 83        | 0.87%   |
| 6.0.2   | 83        | 0.87%   |
| 4.19.0  | 81        | 0.85%   |
| 6.4.11  | 70        | 0.73%   |
| 6.5.9   | 62        | 0.65%   |
| 5.19.16 | 47        | 0.49%   |
| 6.5.5   | 41        | 0.43%   |
| 6.6.2   | 40        | 0.42%   |
| 6.0.0   | 38        | 0.4%    |
| 4.9.60  | 36        | 0.38%   |
| 4.9.20  | 36        | 0.38%   |
| 6.5.6   | 35        | 0.37%   |
| 6.0.6   | 35        | 0.37%   |
| 4.18.16 | 35        | 0.37%   |
| 6.0.12  | 34        | 0.36%   |
| 5.17.5  | 32        | 0.33%   |
| 6.2.9   | 30        | 0.31%   |
| 4.4.0   | 30        | 0.31%   |
| 5.19.6  | 28        | 0.29%   |
| 6.5.8   | 27        | 0.28%   |
| 6.0.7   | 26        | 0.27%   |
| 6.0.10  | 24        | 0.25%   |
| 6.5.7   | 22        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1371      | 14.52%  |
| 5.15    | 1202      | 12.73%  |
| 5.19    | 576       | 6.1%    |
| 5.10    | 571       | 6.05%   |
| 6.2     | 545       | 5.77%   |
| 4.15    | 476       | 5.04%   |
| 5.8     | 466       | 4.94%   |
| 5.3     | 415       | 4.4%    |
| 6.1     | 409       | 4.33%   |
| 5.11    | 372       | 3.94%   |
| 5.13    | 336       | 3.56%   |
| 6.0     | 328       | 3.47%   |
| 6.5     | 315       | 3.34%   |
| 5.16    | 285       | 3.02%   |
| 5.0     | 232       | 2.46%   |
| 4.18    | 201       | 2.13%   |
| 6.4     | 190       | 2.01%   |
| 4.9     | 124       | 1.31%   |
| 6.6     | 110       | 1.17%   |
| 5.17    | 108       | 1.14%   |
| 4.19    | 106       | 1.12%   |
| 6.3     | 99        | 1.05%   |
| 5.18    | 99        | 1.05%   |
| 5.14    | 88        | 0.93%   |
| 5.9     | 82        | 0.87%   |
| 5.6     | 64        | 0.68%   |
| 5.12    | 62        | 0.66%   |
| 5.7     | 50        | 0.53%   |
| 5.5     | 47        | 0.5%    |
| 4.4     | 32        | 0.34%   |
| 4.1     | 16        | 0.17%   |
| 5.2     | 13        | 0.14%   |
| 4.13    | 12        | 0.13%   |
| 5.1     | 7         | 0.07%   |
| 4.20    | 5         | 0.05%   |
| 4.17    | 5         | 0.05%   |
| 4.12    | 5         | 0.05%   |
| 4.14    | 4         | 0.04%   |
| 3.10    | 3         | 0.03%   |
| 4.16    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7897      | 95.34%  |
| i686    | 330       | 3.98%   |
| aarch64 | 38        | 0.46%   |
| armv7l  | 17        | 0.21%   |
| ppc64le | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3677      | 42.32%  |
| KDE5              | 1734      | 19.96%  |
| Unknown           | 874       | 10.06%  |
| XFCE              | 724       | 8.33%   |
| X-Cinnamon        | 587       | 6.76%   |
| MATE              | 258       | 2.97%   |
| LXQt              | 145       | 1.67%   |
| KDE               | 141       | 1.62%   |
| KDE4              | 108       | 1.24%   |
| Pantheon          | 68        | 0.78%   |
| Cinnamon          | 61        | 0.7%    |
| LXDE              | 55        | 0.63%   |
| Unity             | 47        | 0.54%   |
| Budgie            | 37        | 0.43%   |
| GNOME Flashback   | 32        | 0.37%   |
| i3                | 26        | 0.3%    |
| GNOME Classic     | 17        | 0.2%    |
| hyprland          | 15        | 0.17%   |
| sway              | 13        | 0.15%   |
| Deepin            | 12        | 0.14%   |
| Openbox           | 9         | 0.1%    |
| Trinity           | 6         | 0.07%   |
| lightdm-xsession  | 6         | 0.07%   |
| bspwm             | 6         | 0.07%   |
| DWM               | 4         | 0.05%   |
| none+i3           | 3         | 0.03%   |
| xubuntu           | 2         | 0.02%   |
| Unicorn:XFCE      | 2         | 0.02%   |
| qtile             | 2         | 0.02%   |
| icewm             | 2         | 0.02%   |
| enlightenment     | 2         | 0.02%   |
| awesome           | 2         | 0.02%   |
| ubuntu:pika:GNOME | 1         | 0.01%   |
| ubuntu            | 1         | 0.01%   |
| pika:GNOME        | 1         | 0.01%   |
| onyx:GNOME        | 1         | 0.01%   |
| none+bspwm        | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| KDE6              | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 6293      | 73.1%   |
| Wayland | 1736      | 20.16%  |
| Unknown | 438       | 5.09%   |
| Tty     | 142       | 1.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3680      | 42.35%  |
| SDDM    | 1631      | 18.77%  |
| GDM3    | 1165      | 13.41%  |
| LightDM | 956       | 11%     |
| GDM     | 933       | 10.74%  |
| TDM     | 170       | 1.96%   |
| KDM     | 112       | 1.29%   |
| XDM     | 15        | 0.17%   |
| SLiM    | 9         | 0.1%    |
| LXDM    | 6         | 0.07%   |
| GREETD  | 4         | 0.05%   |
| SLIMSKI | 2         | 0.02%   |
| Ly      | 2         | 0.02%   |
| WDM     | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |
| EMPTTY  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang              | Computers | Percent |
|-------------------|-----------|---------|
| it_IT             | 5336      | 62.47%  |
| en_US             | 1813      | 21.22%  |
| Unknown           | 870       | 10.18%  |
| en_GB             | 190       | 2.22%   |
| C                 | 183       | 2.14%   |
| de_DE             | 27        | 0.32%   |
| fr_FR             | 17        | 0.2%    |
| es_ES             | 13        | 0.15%   |
| POSIX             | 12        | 0.14%   |
| de_IT             | 12        | 0.14%   |
| it_CH             | 9         | 0.11%   |
| ru_RU             | 8         | 0.09%   |
| en_IE             | 8         | 0.09%   |
| it_IT@euro        | 5         | 0.06%   |
| en_AG             | 5         | 0.06%   |
| de_AT             | 4         | 0.05%   |
| en_AU             | 3         | 0.04%   |
| fur_IT            | 2         | 0.02%   |
| en_US.UTF8        | 2         | 0.02%   |
| sc_IT             | 1         | 0.01%   |
| ro_RO             | 1         | 0.01%   |
| pt_BR             | 1         | 0.01%   |
| pl_PL             | 1         | 0.01%   |
| it_ITutf8         | 1         | 0.01%   |
| it_IT.UTF -8      | 1         | 0.01%   |
| it_IT.iso88591    | 1         | 0.01%   |
| it                | 1         | 0.01%   |
| hu_HU             | 1         | 0.01%   |
| fr_CH             | 1         | 0.01%   |
| fr_BE             | 1         | 0.01%   |
| es_US             | 1         | 0.01%   |
| es_MX             | 1         | 0.01%   |
| en_US@euro        | 1         | 0.01%   |
| en_US.utf-8       | 1         | 0.01%   |
| en_US.ISO-8859-15 | 1         | 0.01%   |
| en_US.ASCII       | 1         | 0.01%   |
| en_IN             | 1         | 0.01%   |
| en_DK             | 1         | 0.01%   |
| de_CH             | 1         | 0.01%   |
| Default           | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4278      | 50.39%  |
| BIOS | 4212      | 49.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 6260      | 72.98%  |
| Overlay  | 855       | 9.97%   |
| Btrfs    | 779       | 9.08%   |
| Tmpfs    | 263       | 3.07%   |
| Unknown  | 230       | 2.68%   |
| Xfs      | 93        | 1.08%   |
| Zfs      | 39        | 0.45%   |
| Ext2     | 19        | 0.22%   |
| Ext3     | 17        | 0.2%    |
| F2fs     | 14        | 0.16%   |
| Aufs     | 4         | 0.05%   |
| XXX4     | 2         | 0.02%   |
| XXXX     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3894      | 45.57%  |
| GPT     | 3649      | 42.7%   |
| MBR     | 1002      | 11.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7125      | 83.91%  |
| Yes       | 1366      | 16.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5376      | 63.36%  |
| Yes       | 3109      | 36.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1701      | 20.55%  |
| Hewlett-Packard         | 1403      | 16.95%  |
| Lenovo                  | 967       | 11.68%  |
| Dell                    | 676       | 8.17%   |
| Acer                    | 661       | 7.99%   |
| MSI                     | 476       | 5.75%   |
| ASRock                  | 357       | 4.31%   |
| Gigabyte Technology     | 295       | 3.56%   |
| Apple                   | 194       | 2.34%   |
| HUAWEI                  | 126       | 1.52%   |
| Intel                   | 118       | 1.43%   |
| Toshiba                 | 109       | 1.32%   |
| Sony                    | 100       | 1.21%   |
| Unknown                 | 93        | 1.12%   |
| Fujitsu                 | 90        | 1.09%   |
| Samsung Electronics     | 87        | 1.05%   |
| Packard Bell            | 60        | 0.72%   |
| Pegatron                | 47        | 0.57%   |
| Raspberry Pi Foundation | 40        | 0.48%   |
| Mediacom                | 38        | 0.46%   |
| Chuwi                   | 38        | 0.46%   |
| Fujitsu Siemens         | 34        | 0.41%   |
| AMI                     | 29        | 0.35%   |
| Teclast                 | 27        | 0.33%   |
| Notebook                | 27        | 0.33%   |
| Microsoft               | 26        | 0.31%   |
| Foxconn                 | 26        | 0.31%   |
| Microtech               | 21        | 0.25%   |
| BESSTAR Tech            | 21        | 0.25%   |
| AZW                     | 21        | 0.25%   |
| Timi                    | 19        | 0.23%   |
| TUXEDO                  | 15        | 0.18%   |
| PC Specialist           | 15        | 0.18%   |
| Valve                   | 14        | 0.17%   |
| Supermicro              | 14        | 0.17%   |
| Google                  | 11        | 0.13%   |
| Jumper                  | 10        | 0.12%   |
| eMachines               | 10        | 0.12%   |
| TrekStor                | 9         | 0.11%   |
| SANTECH                 | 9         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 112       | 1.35%   |
| ASUS All Series                       | 83        | 1%      |
| HP Pavilion dv6                       | 58        | 0.7%    |
| HP Notebook                           | 47        | 0.57%   |
| HP Pavilion 15                        | 31        | 0.37%   |
| HP 255 G8 Notebook PC                 | 28        | 0.34%   |
| HP Pavilion g6                        | 25        | 0.3%    |
| HUAWEI NBLK-WAX9X                     | 20        | 0.24%   |
| HP 15                                 | 19        | 0.23%   |
| Dell OptiPlex 7010                    | 19        | 0.23%   |
| MSI MS-7C37                           | 18        | 0.22%   |
| ASUS PRIME A320M-K                    | 18        | 0.22%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.21%   |
| MSI MS-7B86                           | 16        | 0.19%   |
| MSI MS-7C56                           | 15        | 0.18%   |
| Dell XPS 15 7590                      | 15        | 0.18%   |
| HP Pavilion x2 Detachable             | 14        | 0.17%   |
| HP ENVY 15                            | 14        | 0.17%   |
| HP 255 G7 Notebook PC                 | 14        | 0.17%   |
| AMI Intel                             | 14        | 0.17%   |
| Valve Jupiter                         | 13        | 0.16%   |
| HUAWEI KLVL-WXX9                      | 13        | 0.16%   |
| HP 255 G6 Notebook PC                 | 13        | 0.16%   |
| Apple MacBook4,1                      | 13        | 0.16%   |
| MSI MS-7B79                           | 12        | 0.14%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 12        | 0.14%   |
| HP G62                                | 12        | 0.14%   |
| HP Compaq Elite 8300 SFF              | 12        | 0.14%   |
| HP 250 G6 Notebook PC                 | 12        | 0.14%   |
| Dell XPS 15 9570                      | 12        | 0.14%   |
| ASUS TUF Gaming X570-PLUS             | 12        | 0.14%   |
| ASUS T101HA                           | 12        | 0.14%   |
| RPi Raspberry Pi                      | 11        | 0.13%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.13%   |
| HUAWEI BOD-WXX9                       | 11        | 0.13%   |
| HP Laptop 15s-eq2xxx                  | 11        | 0.13%   |
| HP 250 G3                             | 11        | 0.13%   |
| Gigabyte B450M DS3H                   | 11        | 0.13%   |
| Acer Aspire 5920G                     | 11        | 0.13%   |
| Acer Aspire 5750G                     | 11        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 405       | 4.89%   |
| Lenovo ThinkPad       | 386       | 4.66%   |
| HP Pavilion           | 304       | 3.67%   |
| Lenovo IdeaPad        | 205       | 2.48%   |
| Dell Latitude         | 190       | 2.3%    |
| HP Compaq             | 171       | 2.07%   |
| ASUS PRIME            | 148       | 1.79%   |
| HP EliteBook          | 131       | 1.58%   |
| ASUS VivoBook         | 124       | 1.5%    |
| Dell XPS              | 123       | 1.49%   |
| Unknown               | 112       | 1.35%   |
| Dell Inspiron         | 107       | 1.29%   |
| HP ProBook            | 105       | 1.27%   |
| HP Laptop             | 103       | 1.24%   |
| ASUS ROG              | 97        | 1.17%   |
| Dell OptiPlex         | 96        | 1.16%   |
| Toshiba Satellite     | 93        | 1.12%   |
| ASUS All              | 83        | 1%      |
| HP 255                | 75        | 0.91%   |
| ASUS TUF              | 71        | 0.86%   |
| HP 250                | 67        | 0.81%   |
| Dell Precision        | 61        | 0.74%   |
| Lenovo ThinkCentre    | 59        | 0.71%   |
| Dell Vostro           | 52        | 0.63%   |
| Acer Swift            | 48        | 0.58%   |
| HP Notebook           | 47        | 0.57%   |
| Acer TravelMate       | 44        | 0.53%   |
| HP ENVY               | 43        | 0.52%   |
| Fujitsu ESPRIMO       | 42        | 0.51%   |
| Lenovo Yoga           | 41        | 0.5%    |
| RPi Raspberry         | 40        | 0.48%   |
| Fujitsu LIFEBOOK      | 40        | 0.48%   |
| Acer Veriton          | 40        | 0.48%   |
| Acer Extensa          | 39        | 0.47%   |
| Lenovo ThinkBook      | 37        | 0.45%   |
| HP ProDesk            | 31        | 0.37%   |
| Packard Bell EasyNote | 27        | 0.33%   |
| Microsoft Surface     | 26        | 0.31%   |
| Gigabyte X570         | 25        | 0.3%    |
| ASUS P8H61-M          | 25        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 697       | 8.42%   |
| 2018    | 687       | 8.3%    |
| 2019    | 671       | 8.11%   |
| 2021    | 593       | 7.17%   |
| 2013    | 565       | 6.83%   |
| 2017    | 531       | 6.42%   |
| 2012    | 530       | 6.4%    |
| 2011    | 473       | 5.72%   |
| 2014    | 471       | 5.69%   |
| 2008    | 453       | 5.47%   |
| 2016    | 437       | 5.28%   |
| 2009    | 435       | 5.26%   |
| 2010    | 432       | 5.22%   |
| 2015    | 426       | 5.15%   |
| 2007    | 269       | 3.25%   |
| 2022    | 245       | 2.96%   |
| 2006    | 140       | 1.69%   |
| 2023    | 77        | 0.93%   |
| 2005    | 69        | 0.83%   |
| Unknown | 52        | 0.63%   |
| 2004    | 14        | 0.17%   |
| 2003    | 6         | 0.07%   |
| 2001    | 2         | 0.02%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4693      | 56.71%  |
| Desktop        | 2989      | 36.12%  |
| Convertible    | 180       | 2.17%   |
| Mini pc        | 122       | 1.47%   |
| All in one     | 115       | 1.39%   |
| Tablet         | 95        | 1.15%   |
| System on chip | 53        | 0.64%   |
| Server         | 28        | 0.34%   |
| Phone          | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7724      | 92.4%   |
| Enabled  | 635       | 7.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8257      | 99.77%  |
| Yes  | 19        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 2019      | 23.99%  |
| 3.01-4.0        | 1801      | 21.4%   |
| 16.01-24.0      | 1577      | 18.74%  |
| 8.01-16.0       | 1483      | 17.62%  |
| 32.01-64.0      | 594       | 7.06%   |
| 1.01-2.0        | 455       | 5.41%   |
| 2.01-3.0        | 147       | 1.75%   |
| 64.01-256.0     | 125       | 1.49%   |
| 24.01-32.0      | 117       | 1.39%   |
| 0.51-1.0        | 83        | 0.99%   |
| 0.01-0.5        | 8         | 0.1%    |
| More than 256.0 | 7         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3452      | 37.27%  |
| 2.01-3.0   | 2274      | 24.55%  |
| 4.01-8.0   | 1215      | 13.12%  |
| 3.01-4.0   | 1155      | 12.47%  |
| 0.51-1.0   | 713       | 7.7%    |
| 8.01-16.0  | 304       | 3.28%   |
| 0.01-0.5   | 109       | 1.18%   |
| 16.01-24.0 | 27        | 0.29%   |
| 24.01-32.0 | 8         | 0.09%   |
| 32.01-64.0 | 3         | 0.03%   |
| Unknown    | 3         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5188      | 60.79%  |
| 2       | 2096      | 24.56%  |
| 3       | 656       | 7.69%   |
| 4       | 279       | 3.27%   |
| 5       | 127       | 1.49%   |
| 0       | 74        | 0.87%   |
| 6       | 62        | 0.73%   |
| 7       | 21        | 0.25%   |
| 8       | 13        | 0.15%   |
| 9       | 7         | 0.08%   |
| 10      | 4         | 0.05%   |
| 12      | 3         | 0.04%   |
| Unknown | 2         | 0.02%   |
| 14      | 1         | 0.01%   |
| 13      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4541      | 54.4%   |
| Yes       | 3806      | 45.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7008      | 84.38%  |
| No        | 1297      | 15.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6423      | 77.11%  |
| No        | 1907      | 22.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4859      | 57.8%   |
| No        | 3547      | 42.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 8276      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 1159      | 12.15%  |
| Rome                | 951       | 9.97%   |
| Turin               | 302       | 3.17%   |
| Bologna             | 206       | 2.16%   |
| Florence            | 184       | 1.93%   |
| Naples              | 174       | 1.82%   |
| Milano              | 155       | 1.62%   |
| Genoa               | 138       | 1.45%   |
| Rho                 | 129       | 1.35%   |
| Padova              | 114       | 1.2%    |
| Palermo             | 106       | 1.11%   |
| Verona              | 90        | 0.94%   |
| Catania             | 80        | 0.84%   |
| Bari                | 77        | 0.81%   |
| Brescia             | 64        | 0.67%   |
| Trieste             | 63        | 0.66%   |
| Parma               | 63        | 0.66%   |
| Venice              | 59        | 0.62%   |
| Bergamo             | 55        | 0.58%   |
| Pisa                | 51        | 0.53%   |
| Monza               | 44        | 0.46%   |
| Reggio Emilia       | 43        | 0.45%   |
| Modena              | 43        | 0.45%   |
| Casalecchio di Reno | 43        | 0.45%   |
| Cagliari            | 42        | 0.44%   |
| Pescara             | 41        | 0.43%   |
| Perugia             | 38        | 0.4%    |
| Trento              | 37        | 0.39%   |
| Sesto San Giovanni  | 35        | 0.37%   |
| Vicenza             | 34        | 0.36%   |
| Bolzano             | 34        | 0.36%   |
| Taranto             | 33        | 0.35%   |
| Salerno             | 28        | 0.29%   |
| Udine               | 27        | 0.28%   |
| Mestre              | 27        | 0.28%   |
| Reggio Calabria     | 26        | 0.27%   |
| Como                | 26        | 0.27%   |
| Seregno             | 25        | 0.26%   |
| Legnano             | 24        | 0.25%   |
| Forlì              | 24        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1961      | 2912   | 16.28%  |
| Seagate                     | 1640      | 2539   | 13.62%  |
| WDC                         | 1572      | 2443   | 13.05%  |
| Kingston                    | 784       | 1053   | 6.51%   |
| Crucial                     | 724       | 921    | 6.01%   |
| Toshiba                     | 671       | 954    | 5.57%   |
| SanDisk                     | 626       | 854    | 5.2%    |
| Unknown                     | 562       | 773    | 4.67%   |
| Hitachi                     | 435       | 555    | 3.61%   |
| SK hynix                    | 282       | 347    | 2.34%   |
| HGST                        | 242       | 328    | 2.01%   |
| Micron Technology           | 212       | 271    | 1.76%   |
| Intel                       | 200       | 271    | 1.66%   |
| Maxtor                      | 196       | 267    | 1.63%   |
| Phison                      | 115       | 166    | 0.95%   |
| China                       | 112       | 131    | 0.93%   |
| KIOXIA                      | 92        | 123    | 0.76%   |
| SPCC                        | 86        | 106    | 0.71%   |
| Micron/Crucial Technology   | 76        | 101    | 0.63%   |
| Apple                       | 74        | 91     | 0.61%   |
| Phison Electronics          | 62        | 79     | 0.51%   |
| Intenso                     | 62        | 78     | 0.51%   |
| Fujitsu                     | 58        | 69     | 0.48%   |
| Transcend                   | 53        | 71     | 0.44%   |
| A-DATA Technology           | 48        | 64     | 0.4%    |
| Kingston Technology Company | 46        | 57     | 0.38%   |
| JMicron Technology          | 45        | 50     | 0.37%   |
| PNY                         | 42        | 53     | 0.35%   |
| Unknown                     | 40        | 53     | 0.33%   |
| Corsair                     | 39        | 57     | 0.32%   |
| KingDian                    | 38        | 45     | 0.32%   |
| Silicon Motion              | 36        | 51     | 0.3%    |
| LITEON                      | 35        | 44     | 0.29%   |
| Netac                       | 30        | 32     | 0.25%   |
| Patriot                     | 28        | 38     | 0.23%   |
| OCZ                         | 27        | 32     | 0.22%   |
| Drevo                       | 26        | 28     | 0.22%   |
| SABRENT                     | 25        | 27     | 0.21%   |
| Lexar                       | 25        | 29     | 0.21%   |
| Teclast                     | 24        | 30     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 210       | 1.59%   |
| Crucial CT500MX500SSD1 500GB                        | 171       | 1.3%    |
| Samsung SSD 860 EVO 500GB                           | 162       | 1.23%   |
| Samsung SSD 850 EVO 250GB                           | 135       | 1.02%   |
| Seagate ST500DM002-1BD142 500GB                     | 121       | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 103       | 0.78%   |
| Samsung SSD 850 EVO 500GB                           | 102       | 0.77%   |
| Kingston SA400S37480G 480GB SSD                     | 101       | 0.77%   |
| Unknown MMC Card  32GB                              | 99        | 0.75%   |
| Crucial CT240BX500SSD1 240GB                        | 87        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 86        | 0.65%   |
| Unknown MMC Card  64GB                              | 81        | 0.61%   |
| Crucial CT1000MX500SSD1 1TB                         | 80        | 0.61%   |
| Toshiba DT01ACA100 1TB                              | 77        | 0.58%   |
| Samsung SSD 860 EVO 250GB                           | 76        | 0.58%   |
| Toshiba MQ01ABF050 500GB                            | 74        | 0.56%   |
| Kingston SA400S37120G 120GB SSD                     | 72        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 70        | 0.53%   |
| Crucial CT480BX500SSD1 480GB                        | 70        | 0.53%   |
| HGST HTS545050A7E680 500GB                          | 64        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 63        | 0.48%   |
| Seagate ST1000LM035-1RK172 1TB                      | 60        | 0.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 60        | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                     | 59        | 0.45%   |
| Seagate ST3500418AS 500GB                           | 56        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 55        | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 55        | 0.42%   |
| Unknown SD/MMC/MS PRO 128GB                         | 54        | 0.41%   |
| SanDisk SSD PLUS 240GB                              | 52        | 0.39%   |
| Seagate M3 Portable 2TB                             | 49        | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 48        | 0.36%   |
| Seagate ST9500325AS 500GB                           | 47        | 0.36%   |
| Samsung SSD 860 EVO 1TB                             | 47        | 0.36%   |
| Unknown MMC Card  128GB                             | 46        | 0.35%   |
| Seagate ST31000528AS 1TB                            | 44        | 0.33%   |
| Seagate Expansion 1TB                               | 44        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB                      | 43        | 0.33%   |
| Samsung SSD 840 EVO 250GB                           | 43        | 0.33%   |
| Samsung NVMe SSD Drive 512GB                        | 43        | 0.33%   |
| Phison Sabrent 512GB                                | 43        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1588      | 2448   | 34.19%  |
| WDC                 | 1301      | 2047   | 28.01%  |
| Toshiba             | 493       | 688    | 10.62%  |
| Hitachi             | 435       | 555    | 9.37%   |
| HGST                | 241       | 327    | 5.19%   |
| Maxtor              | 194       | 265    | 4.18%   |
| Samsung Electronics | 154       | 194    | 3.32%   |
| Unknown             | 67        | 78     | 1.44%   |
| Fujitsu             | 58        | 69     | 1.25%   |
| Apple               | 25        | 28     | 0.54%   |
| External            | 13        | 14     | 0.28%   |
| TO Exter            | 9         | 9      | 0.19%   |
| ASMT                | 8         | 8      | 0.17%   |
| USB3.0              | 6         | 7      | 0.13%   |
| IBM/Hitachi         | 5         | 6      | 0.11%   |
| HGST HTS            | 5         | 5      | 0.11%   |
| SSK                 | 4         | 4      | 0.09%   |
| Inateck             | 4         | 4      | 0.09%   |
| Intenso             | 3         | 5      | 0.06%   |
| Hewlett-Packard     | 3         | 6      | 0.06%   |
| WD MediaMax         | 2         | 2      | 0.04%   |
| StoreJet            | 2         | 2      | 0.04%   |
| LaCie               | 2         | 3      | 0.04%   |
| Initio              | 2         | 2      | 0.04%   |
| ASMT109x            | 2         | 2      | 0.04%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| USB                 | 1         | 1      | 0.02%   |
| TDAS                | 1         | 1      | 0.02%   |
| SABRENT             | 1         | 1      | 0.02%   |
| QUANTUM             | 1         | 1      | 0.02%   |
| Promise             | 1         | 1      | 0.02%   |
| PI-041              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| IBM-ESXS            | 1         | 2      | 0.02%   |
| IBM-207x            | 1         | 4      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| FC-1307             | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| Config              | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1061      | 1528   | 25.94%  |
| Crucial             | 655       | 831    | 16.01%  |
| Kingston            | 648       | 877    | 15.84%  |
| SanDisk             | 355       | 497    | 8.68%   |
| WDC                 | 135       | 185    | 3.3%    |
| China               | 110       | 128    | 2.69%   |
| Micron Technology   | 81        | 104    | 1.98%   |
| SPCC                | 73        | 90     | 1.78%   |
| Toshiba             | 61        | 87     | 1.49%   |
| SK hynix            | 58        | 66     | 1.42%   |
| Intenso             | 54        | 65     | 1.32%   |
| Transcend           | 50        | 68     | 1.22%   |
| Intel               | 42        | 60     | 1.03%   |
| Apple               | 41        | 44     | 1%      |
| PNY                 | 39        | 49     | 0.95%   |
| A-DATA Technology   | 38        | 52     | 0.93%   |
| KingDian            | 37        | 44     | 0.9%    |
| Corsair             | 33        | 49     | 0.81%   |
| LITEON              | 31        | 35     | 0.76%   |
| Patriot             | 27        | 37     | 0.66%   |
| OCZ                 | 26        | 31     | 0.64%   |
| Netac               | 25        | 26     | 0.61%   |
| Teclast             | 24        | 30     | 0.59%   |
| Drevo               | 24        | 25     | 0.59%   |
| JMicron Technology  | 22        | 24     | 0.54%   |
| GOODRAM             | 19        | 27     | 0.46%   |
| Dogfish             | 19        | 23     | 0.46%   |
| Unknown             | 18        | 24     | 0.44%   |
| LITEONIT            | 16        | 28     | 0.39%   |
| Team                | 14        | 31     | 0.34%   |
| Lexar               | 14        | 17     | 0.34%   |
| Fanxiang            | 14        | 16     | 0.34%   |
| TCSUNBOW            | 13        | 14     | 0.32%   |
| Emtec               | 12        | 12     | 0.29%   |
| ASMT                | 12        | 15     | 0.29%   |
| Verbatim            | 11        | 17     | 0.27%   |
| FORESEE             | 11        | 13     | 0.27%   |
| Unknown             | 10        | 11     | 0.24%   |
| KingSpec            | 10        | 12     | 0.24%   |
| BAITITON            | 10        | 17     | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3904      | 6806   | 36.37%  |
| SSD     | 3626      | 5493   | 33.78%  |
| NVMe    | 2489      | 3661   | 23.19%  |
| MMC     | 506       | 721    | 4.71%   |
| Unknown | 208       | 269    | 1.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6141      | 11959  | 63.94%  |
| NVMe | 2473      | 3615   | 25.75%  |
| MMC  | 506       | 721    | 5.27%   |
| SAS  | 485       | 655    | 5.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4976      | 7973   | 64.66%  |
| 0.51-1.0        | 1958      | 2974   | 25.44%  |
| 1.01-2.0        | 443       | 749    | 5.76%   |
| 3.01-4.0        | 129       | 237    | 1.68%   |
| 2.01-3.0        | 111       | 192    | 1.44%   |
| 4.01-10.0       | 69        | 154    | 0.9%    |
| 10.01-20.0      | 9         | 19     | 0.12%   |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2354      | 26.44%  |
| 251-500        | 1944      | 21.84%  |
| 501-1000       | 1102      | 12.38%  |
| 1-20           | 875       | 9.83%   |
| 51-100         | 680       | 7.64%   |
| 1001-2000      | 651       | 7.31%   |
| 21-50          | 419       | 4.71%   |
| More than 3000 | 368       | 4.13%   |
| 2001-3000      | 269       | 3.02%   |
| Unknown        | 240       | 2.7%    |
| 0              | 1         | 0.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3682      | 39.95%  |
| 21-50          | 1423      | 15.44%  |
| 101-250        | 1155      | 12.53%  |
| 51-100         | 1028      | 11.15%  |
| 251-500        | 689       | 7.48%   |
| 501-1000       | 500       | 5.43%   |
| 1001-2000      | 267       | 2.9%    |
| Unknown        | 240       | 2.6%    |
| More than 3000 | 132       | 1.43%   |
| 2001-3000      | 99        | 1.07%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 22        | 25     | 2.72%   |
| HGST HTS545050A7E680 500GB                     | 21        | 25     | 2.6%    |
| Seagate ST3500418AS 500GB                      | 14        | 19     | 1.73%   |
| Seagate ST9500325AS 500GB                      | 11        | 11     | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB                 | 9         | 11     | 1.11%   |
| Toshiba MQ01ABF050 500GB                       | 8         | 9      | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 8         | 10     | 0.99%   |
| SanDisk SSD PLUS 480GB                         | 8         | 10     | 0.99%   |
| Maxtor STM3250310AS 250GB                      | 8         | 9      | 0.99%   |
| Hitachi HTS725050A9A364 500GB                  | 8         | 9      | 0.99%   |
| Seagate ST500LT012-1DG142 500GB                | 7         | 7      | 0.87%   |
| HGST HTS725050A7E630 500GB                     | 7         | 9      | 0.87%   |
| WDC WD40EFRX-68N32N0 4TB                       | 6         | 7      | 0.74%   |
| Maxtor STM3320820AS 320GB                      | 6         | 6      | 0.74%   |
| HGST HTS721010A9E630 1TB                       | 6         | 6      | 0.74%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 5         | 6      | 0.62%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 0.62%   |
| Toshiba DT01ACA100 1TB                         | 5         | 5      | 0.62%   |
| Seagate ST9320325AS 320GB                      | 5         | 5      | 0.62%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 5         | 7      | 0.62%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 5         | 5      | 0.62%   |
| Kingston SA400S37240G 240GB SSD                | 5         | 6      | 0.62%   |
| Hitachi HTS545050A7E380 500GB                  | 5         | 5      | 0.62%   |
| HGST HTS541010A9E680 1TB                       | 5         | 6      | 0.62%   |
| Crucial CT525MX300SSD1 528GB                   | 5         | 5      | 0.62%   |
| WDC WD30EFRX-68EUZN0 3TB                       | 4         | 4      | 0.49%   |
| Unknown MM0500EANCR 500GB                      | 4         | 9      | 0.49%   |
| Toshiba MK5065GSX 500GB                        | 4         | 5      | 0.49%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 4         | 4      | 0.49%   |
| Seagate ST31500341AS 1TB                       | 4         | 4      | 0.49%   |
| Seagate ST31000528AS 1TB                       | 4         | 7      | 0.49%   |
| Samsung Electronics SSD 860 EVO 500GB          | 4         | 5      | 0.49%   |
| Samsung Electronics HD103UJ 1TB                | 4         | 4      | 0.49%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 4         | 5      | 0.49%   |
| Kingston SA400S37480G 480GB SSD                | 4         | 4      | 0.49%   |
| Hitachi HTS547550A9E384 500GB                  | 4         | 4      | 0.49%   |
| Hitachi HTS545032B9A300 320GB                  | 4         | 4      | 0.49%   |
| Hitachi HTS543232A7A384 320GB                  | 4         | 5      | 0.49%   |
| HGST HTS541075A9E680 752GB                     | 4         | 7      | 0.49%   |
| WDC WD20EFRX-68EUZN0 2TB                       | 3         | 4      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 203       | 262    | 25.79%  |
| WDC                         | 152       | 187    | 19.31%  |
| Hitachi                     | 84        | 91     | 10.67%  |
| Toshiba                     | 51        | 56     | 6.48%   |
| Samsung Electronics         | 51        | 57     | 6.48%   |
| HGST                        | 47        | 57     | 5.97%   |
| Maxtor                      | 41        | 50     | 5.21%   |
| Crucial                     | 26        | 26     | 3.3%    |
| Kingston                    | 19        | 22     | 2.41%   |
| SK hynix                    | 16        | 18     | 2.03%   |
| SanDisk                     | 16        | 18     | 2.03%   |
| Micron Technology           | 11        | 12     | 1.4%    |
| Intel                       | 8         | 15     | 1.02%   |
| Fujitsu                     | 6         | 8      | 0.76%   |
| Unknown                     | 5         | 10     | 0.64%   |
| China                       | 4         | 4      | 0.51%   |
| OCZ                         | 3         | 3      | 0.38%   |
| Intenso                     | 3         | 4      | 0.38%   |
| Drevo                       | 3         | 3      | 0.38%   |
| Corsair                     | 3         | 4      | 0.38%   |
| ASMT                        | 3         | 3      | 0.38%   |
| Apple                       | 3         | 3      | 0.38%   |
| TCSUNBOW                    | 2         | 2      | 0.25%   |
| BAITITON                    | 2         | 4      | 0.25%   |
| A-DATA Technology           | 2         | 2      | 0.25%   |
| Yangtze Memory Technologies | 1         | 1      | 0.13%   |
| WINTEC                      | 1         | 1      | 0.13%   |
| WDC WDS2                    | 1         | 1      | 0.13%   |
| WD MediaMax                 | 1         | 1      | 0.13%   |
| USB3.0                      | 1         | 1      | 0.13%   |
| Transcend                   | 1         | 2      | 0.13%   |
| Teclast                     | 1         | 1      | 0.13%   |
| Team                        | 1         | 1      | 0.13%   |
| SSSTC                       | 1         | 2      | 0.13%   |
| Realtek Semiconductor       | 1         | 1      | 0.13%   |
| QUANTUM                     | 1         | 1      | 0.13%   |
| NGFF                        | 1         | 1      | 0.13%   |
| Micron/Crucial Technology   | 1         | 1      | 0.13%   |
| LITEONIT                    | 1         | 1      | 0.13%   |
| LITEON                      | 1         | 1      | 0.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 203       | 262    | 33.06%  |
| WDC                 | 147       | 179    | 23.94%  |
| Hitachi             | 84        | 91     | 13.68%  |
| Toshiba             | 49        | 54     | 7.98%   |
| HGST                | 47        | 57     | 7.65%   |
| Maxtor              | 41        | 50     | 6.68%   |
| Samsung Electronics | 23        | 25     | 3.75%   |
| Fujitsu             | 6         | 8      | 0.98%   |
| Unknown             | 5         | 10     | 0.81%   |
| Apple               | 3         | 3      | 0.49%   |
| ASMT                | 2         | 2      | 0.33%   |
| WD MediaMax         | 1         | 1      | 0.16%   |
| USB3.0              | 1         | 1      | 0.16%   |
| QUANTUM             | 1         | 1      | 0.16%   |
| IBM/Hitachi         | 1         | 1      | 0.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 575       | 745    | 76.77%  |
| SSD  | 149       | 171    | 19.89%  |
| NVMe | 25        | 31     | 3.34%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                        | 2         | 4      | 11.11%  |
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 11.11%  |
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 5.56%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 5.56%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 5.56%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 5.56%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 5.56%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 1      | 5.56%   |
| Seagate STM3250318AS 250GB                       | 1         | 1      | 5.56%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 5.56%   |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 5.56%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 5.56%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 5.56%   |
| Hitachi HTS543216L9A300 160GB                    | 1         | 1      | 5.56%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 10     | 38.89%  |
| WDC                 | 4         | 4      | 22.22%  |
| Hitachi             | 4         | 4      | 22.22%  |
| Toshiba             | 1         | 1      | 5.56%   |
| SK hynix            | 1         | 1      | 5.56%   |
| Samsung Electronics | 1         | 1      | 5.56%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4784      | 9537   | 52.72%  |
| Works    | 3549      | 6445   | 39.11%  |
| Malfunc  | 724       | 947    | 7.98%   |
| Failed   | 18        | 21     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5500      | 53.51%  |
| AMD                              | 1394      | 13.56%  |
| Samsung Electronics              | 892       | 8.68%   |
| SanDisk                          | 380       | 3.7%    |
| SK hynix                         | 211       | 2.05%   |
| Nvidia                           | 198       | 1.93%   |
| Phison Electronics               | 187       | 1.82%   |
| Kingston Technology Company      | 186       | 1.81%   |
| ASMedia Technology               | 156       | 1.52%   |
| Micron/Crucial Technology        | 145       | 1.41%   |
| JMicron Technology               | 144       | 1.4%    |
| Marvell Technology Group         | 140       | 1.36%   |
| Micron Technology                | 136       | 1.32%   |
| Toshiba America Info Systems     | 124       | 1.21%   |
| KIOXIA                           | 99        | 0.96%   |
| VIA Technologies                 | 64        | 0.62%   |
| Silicon Motion                   | 50        | 0.49%   |
| Silicon Integrated Systems [SiS] | 35        | 0.34%   |
| MAXIO Technology (Hangzhou)      | 24        | 0.23%   |
| ADATA Technology                 | 23        | 0.22%   |
| Union Memory (Shenzhen)          | 18        | 0.18%   |
| Solid State Storage Technology   | 17        | 0.17%   |
| Adaptec                          | 17        | 0.17%   |
| Silicon Image                    | 14        | 0.14%   |
| Shenzhen Longsys Electronics     | 14        | 0.14%   |
| LSI Logic / Symbios Logic        | 13        | 0.13%   |
| Apple                            | 12        | 0.12%   |
| Realtek Semiconductor            | 11        | 0.11%   |
| Broadcom / LSI                   | 11        | 0.11%   |
| Lite-On Technology               | 8         | 0.08%   |
| Lenovo                           | 8         | 0.08%   |
| Seagate Technology               | 6         | 0.06%   |
| INNOGRIT                         | 6         | 0.06%   |
| Yangtze Memory Technologies      | 4         | 0.04%   |
| Hewlett-Packard                  | 4         | 0.04%   |
| Solidigm                         | 3         | 0.03%   |
| Promise Technology               | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| HighPoint Technologies           | 3         | 0.03%   |
| Broadcom                         | 3         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 938       | 7.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 428       | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 416       | 3.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 343       | 2.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 300       | 2.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 275       | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 233       | 1.95%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 228       | 1.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 220       | 1.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 194       | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                            | 190       | 1.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 185       | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 180       | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                         | 175       | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 167       | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 165       | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 159       | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 152       | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 145       | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 144       | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 140       | 1.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 132       | 1.1%    |
| Intel SATA Controller [RAID mode]                                              | 130       | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 128       | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 127       | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 126       | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 121       | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 120       | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 119       | 1%      |
| Phison E12 NVMe Controller                                                     | 115       | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 103       | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 100       | 0.84%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 99        | 0.83%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 95        | 0.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 92        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 89        | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 87        | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 86        | 0.72%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 84        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 75        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5729      | 55.23%  |
| NVMe | 2487      | 23.98%  |
| IDE  | 1406      | 13.55%  |
| RAID | 726       | 7%      |
| SCSI | 13        | 0.13%   |
| SAS  | 12        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 6365      | 76.91%  |
| AMD                      | 1850      | 22.35%  |
| ARM                      | 55        | 0.66%   |
| CentaurHauls             | 4         | 0.05%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.01%   |
| Unknown                  | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 105       | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 97        | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 87        | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 83        | 1%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 76        | 0.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 75        | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 67        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 64        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 63        | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 61        | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 56        | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 56        | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 55        | 0.66%   |
| AMD Ryzen 5 3600 6-Core Processor             | 54        | 0.65%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 53        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 52        | 0.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 50        | 0.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 49        | 0.59%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 49        | 0.59%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 48        | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 47        | 0.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 44        | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 43        | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 39        | 0.47%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 39        | 0.47%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 38        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 36        | 0.43%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 36        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 36        | 0.43%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 36        | 0.43%   |
| ARM Processor                                 | 36        | 0.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 35        | 0.42%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 35        | 0.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 34        | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 0.4%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 32        | 0.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 31        | 0.37%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 31        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1604      | 19.35%  |
| Intel Core i5           | 1578      | 19.03%  |
| Other                   | 579       | 6.98%   |
| Intel Core i3           | 559       | 6.74%   |
| Intel Core 2 Duo        | 453       | 5.46%   |
| Intel Celeron           | 441       | 5.32%   |
| AMD Ryzen 5             | 436       | 5.26%   |
| AMD Ryzen 7             | 364       | 4.39%   |
| Intel Atom              | 282       | 3.4%    |
| Intel Pentium           | 150       | 1.81%   |
| Intel Pentium Dual-Core | 133       | 1.6%    |
| Intel Xeon              | 123       | 1.48%   |
| Intel Core 2 Quad       | 114       | 1.38%   |
| AMD Ryzen 9             | 96        | 1.16%   |
| AMD Ryzen 3             | 89        | 1.07%   |
| AMD FX                  | 82        | 0.99%   |
| Intel Core 2            | 78        | 0.94%   |
| Intel Pentium Dual      | 74        | 0.89%   |
| Intel Pentium 4         | 67        | 0.81%   |
| AMD A8                  | 61        | 0.74%   |
| AMD A10                 | 57        | 0.69%   |
| AMD E1                  | 56        | 0.68%   |
| Intel Core i9           | 52        | 0.63%   |
| AMD A4                  | 51        | 0.62%   |
| AMD Athlon 64 X2        | 50        | 0.6%    |
| AMD A6                  | 48        | 0.58%   |
| Intel Genuine           | 41        | 0.49%   |
| AMD Phenom II X4        | 35        | 0.42%   |
| AMD Sempron             | 33        | 0.4%    |
| AMD E2                  | 30        | 0.36%   |
| Intel Pentium D         | 24        | 0.29%   |
| AMD Ryzen 7 PRO         | 24        | 0.29%   |
| AMD Athlon              | 23        | 0.28%   |
| Intel Pentium Silver    | 22        | 0.27%   |
| AMD Phenom II X6        | 22        | 0.27%   |
| AMD Ryzen 5 PRO         | 20        | 0.24%   |
| AMD Athlon II X2        | 20        | 0.24%   |
| AMD E                   | 17        | 0.21%   |
| Intel Pentium M         | 16        | 0.19%   |
| AMD Turion 64 X2 Mobile | 16        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3292      | 39.7%   |
| 4       | 3114      | 37.55%  |
| 6       | 694       | 8.37%   |
| 8       | 553       | 6.67%   |
| 1       | 317       | 3.82%   |
| 12      | 103       | 1.24%   |
| 10      | 63        | 0.76%   |
| 14      | 55        | 0.66%   |
| 3       | 37        | 0.45%   |
| 16      | 32        | 0.39%   |
| 24      | 13        | 0.16%   |
| Unknown | 9         | 0.11%   |
| 40      | 3         | 0.04%   |
| 5       | 3         | 0.04%   |
| 28      | 2         | 0.02%   |
| 20      | 2         | 0.02%   |
| 64      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8211      | 99.21%  |
| 2       | 54        | 0.65%   |
| Unknown | 7         | 0.08%   |
| 4       | 3         | 0.04%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5093      | 61.41%  |
| 1       | 3184      | 38.39%  |
| Unknown | 9         | 0.11%   |
| 4       | 5         | 0.06%   |
| 12      | 1         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8063      | 97.29%  |
| 32-bit         | 128       | 1.54%   |
| Unknown        | 94        | 1.13%   |
| 64-bit         | 3         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2440      | 28.05%  |
| 0x206a7    | 386       | 4.44%   |
| 0x306a9    | 373       | 4.29%   |
| 0x306c3    | 316       | 3.63%   |
| 0x1067a    | 312       | 3.59%   |
| 0x806ea    | 186       | 2.14%   |
| 0x806c1    | 163       | 1.87%   |
| 0x40651    | 162       | 1.86%   |
| 0x806ec    | 158       | 1.82%   |
| 0x906ea    | 156       | 1.79%   |
| 0x806e9    | 156       | 1.79%   |
| 0x506e3    | 148       | 1.7%    |
| 0x406e3    | 140       | 1.61%   |
| 0x6fd      | 138       | 1.59%   |
| 0x906e9    | 131       | 1.51%   |
| 0x08108109 | 121       | 1.39%   |
| 0x20655    | 119       | 1.37%   |
| 0x10676    | 105       | 1.21%   |
| 0x08701021 | 103       | 1.18%   |
| 0x306d4    | 93        | 1.07%   |
| 0x406c4    | 85        | 0.98%   |
| 0x0a50000c | 84        | 0.97%   |
| 0x6fb      | 77        | 0.89%   |
| 0x406c3    | 77        | 0.89%   |
| 0x30678    | 76        | 0.87%   |
| 0x08608103 | 74        | 0.85%   |
| 0x20652    | 69        | 0.79%   |
| 0x706e5    | 67        | 0.77%   |
| 0x706a1    | 65        | 0.75%   |
| 0x706a8    | 59        | 0.68%   |
| 0x806eb    | 55        | 0.63%   |
| 0x6f6      | 55        | 0.63%   |
| 0x010000c8 | 53        | 0.61%   |
| 0x506c9    | 52        | 0.6%    |
| 0x08600106 | 51        | 0.59%   |
| 0x06006705 | 51        | 0.59%   |
| 0x106e5    | 48        | 0.55%   |
| 0x906ed    | 47        | 0.54%   |
| 0x0a50000d | 47        | 0.54%   |
| 0x0800820d | 46        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1235      | 14.88%  |
| Haswell          | 678       | 8.17%   |
| Penryn           | 560       | 6.75%   |
| SandyBridge      | 517       | 6.23%   |
| IvyBridge        | 506       | 6.1%    |
| Skylake          | 411       | 4.95%   |
| Core             | 372       | 4.48%   |
| Unknown          | 318       | 3.83%   |
| Silvermont       | 313       | 3.77%   |
| Zen 2            | 284       | 3.42%   |
| TigerLake        | 261       | 3.15%   |
| Westmere         | 252       | 3.04%   |
| Zen+             | 241       | 2.9%    |
| Zen 3            | 229       | 2.76%   |
| K10              | 177       | 2.13%   |
| Goldmont plus    | 172       | 2.07%   |
| CometLake        | 166       | 2%      |
| Broadwell        | 145       | 1.75%   |
| IceLake          | 137       | 1.65%   |
| Zen              | 130       | 1.57%   |
| Excavator        | 128       | 1.54%   |
| Alderlake Hybrid | 122       | 1.47%   |
| K8 Hammer        | 114       | 1.37%   |
| Piledriver       | 108       | 1.3%    |
| Bonnell          | 106       | 1.28%   |
| NetBurst         | 100       | 1.21%   |
| Nehalem          | 97        | 1.17%   |
| Goldmont         | 77        | 0.93%   |
| P6               | 61        | 0.74%   |
| Jaguar           | 59        | 0.71%   |
| Puma             | 56        | 0.67%   |
| Bobcat           | 41        | 0.49%   |
| K10 Llano        | 37        | 0.45%   |
| Steamroller      | 33        | 0.4%    |
| K8 & K10 hybrid  | 20        | 0.24%   |
| Tremont          | 16        | 0.19%   |
| Bulldozer        | 13        | 0.16%   |
| Gracemont        | 5         | 0.06%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4673      | 48.11%  |
| Nvidia                                       | 2719      | 27.99%  |
| AMD                                          | 2246      | 23.12%  |
| Silicon Integrated Systems [SiS]             | 22        | 0.23%   |
| Matrox Electronics Systems                   | 20        | 0.21%   |
| VIA Technologies                             | 16        | 0.16%   |
| ASPEED Technology                            | 10        | 0.1%    |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.03%   |
| S3 Graphics                                  | 2         | 0.02%   |
| ATI Technologies                             | 2         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 359       | 3.55%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 283       | 2.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 239       | 2.37%   |
| Intel UHD Graphics 620                                                                   | 232       | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 215       | 2.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 206       | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 177       | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 173       | 1.71%   |
| Intel HD Graphics 620                                                                    | 173       | 1.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 167       | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 150       | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 148       | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 146       | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 129       | 1.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 125       | 1.24%   |
| Intel Core Processor Integrated Graphics Controller                                      | 124       | 1.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 120       | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 117       | 1.16%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 116       | 1.15%   |
| Intel HD Graphics 5500                                                                   | 114       | 1.13%   |
| AMD Lucienne                                                                             | 114       | 1.13%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 107       | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 105       | 1.04%   |
| Intel HD Graphics 530                                                                    | 99        | 0.98%   |
| Intel HD Graphics 630                                                                    | 96        | 0.95%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 87        | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 79        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 79        | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 79        | 0.78%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 77        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 76        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 75        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 71        | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 69        | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 66        | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 65        | 0.64%   |
| Intel HD Graphics 500                                                                    | 65        | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 65        | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 62        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 62        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 3296      | 39.61%  |
| 1 x AMD                 | 1741      | 20.92%  |
| 1 x Nvidia              | 1529      | 18.37%  |
| Intel + Nvidia          | 1065      | 12.8%   |
| Intel + AMD             | 219       | 2.63%   |
| 2 x AMD                 | 179       | 2.15%   |
| AMD + Nvidia            | 105       | 1.26%   |
| Other                   | 63        | 0.76%   |
| 2 x Intel               | 36        | 0.43%   |
| 1 x SiS                 | 22        | 0.26%   |
| 1 x VIA                 | 16        | 0.19%   |
| 2 x Nvidia              | 12        | 0.14%   |
| 1 x Matrox              | 12        | 0.14%   |
| 1 x ASPEED              | 6         | 0.07%   |
| Nvidia + Matrox         | 4         | 0.05%   |
| 1 x XGI                 | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| AMD + Matrox            | 3         | 0.04%   |
| 1 x S3 Graphics         | 2         | 0.02%   |
| 3 x AMD                 | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + ASPEED            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6804      | 80.73%  |
| Proprietary | 1336      | 15.85%  |
| Unknown     | 288       | 3.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4650      | 54.3%   |
| 0.01-0.5   | 1142      | 13.34%  |
| 1.01-2.0   | 1104      | 12.89%  |
| 0.51-1.0   | 706       | 8.24%   |
| 3.01-4.0   | 445       | 5.2%    |
| 7.01-8.0   | 231       | 2.7%    |
| 5.01-6.0   | 164       | 1.92%   |
| 8.01-16.0  | 65        | 0.76%   |
| 2.01-3.0   | 52        | 0.61%   |
| 16.01-24.0 | 3         | 0.04%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1270      | 14.5%   |
| AU Optronics            | 1031      | 11.77%  |
| Chimei Innolux          | 799       | 9.12%   |
| BOE                     | 747       | 8.53%   |
| LG Display              | 707       | 8.07%   |
| Hewlett-Packard         | 437       | 4.99%   |
| Goldstar                | 406       | 4.64%   |
| Philips                 | 395       | 4.51%   |
| Ancor Communications    | 325       | 3.71%   |
| Acer                    | 278       | 3.17%   |
| Dell                    | 222       | 2.53%   |
| BenQ                    | 189       | 2.16%   |
| Apple                   | 165       | 1.88%   |
| Sharp                   | 158       | 1.8%    |
| Chi Mei Optoelectronics | 154       | 1.76%   |
| AOC                     | 147       | 1.68%   |
| Lenovo                  | 125       | 1.43%   |
| Sony                    | 82        | 0.94%   |
| HannStar                | 75        | 0.86%   |
| PANDA                   | 69        | 0.79%   |
| LG Philips              | 69        | 0.79%   |
| ASUSTek Computer        | 56        | 0.64%   |
| InfoVision              | 49        | 0.56%   |
| Unknown                 | 45        | 0.51%   |
| LG Electronics          | 40        | 0.46%   |
| MSI                     | 39        | 0.45%   |
| CSO                     | 30        | 0.34%   |
| Eizo                    | 28        | 0.32%   |
| Fujitsu Siemens         | 25        | 0.29%   |
| CPT                     | 25        | 0.29%   |
| Iiyama                  | 19        | 0.22%   |
| Toshiba                 | 18        | 0.21%   |
| Panasonic               | 18        | 0.21%   |
| NEC Computers           | 16        | 0.18%   |
| Vestel Elektronik       | 15        | 0.17%   |
| Packard Bell            | 15        | 0.17%   |
| Mi                      | 14        | 0.16%   |
| RTK                     | 13        | 0.15%   |
| Quanta Display          | 13        | 0.15%   |
| LGD                     | 13        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 74        | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 49        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 46        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 41        | 0.45%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 38        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 37        | 0.41%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 37        | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 36        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 35        | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 34        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 34        | 0.38%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 32        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 30        | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 29        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 28        | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 27        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 27        | 0.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 26        | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 26        | 0.29%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch    | 26        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 25        | 0.28%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 23        | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 23        | 0.26%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 23        | 0.26%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 22        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 22        | 0.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 21        | 0.23%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch                | 20        | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 19        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 19        | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 19        | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 19        | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 18        | 0.2%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 17        | 0.19%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 17        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 17        | 0.19%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 16        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 16        | 0.18%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 16        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3745      | 44.54%  |
| 1366x768 (WXGA)    | 1649      | 19.61%  |
| 3840x2160 (4K)     | 429       | 5.1%    |
| 1280x1024 (SXGA)   | 348       | 4.14%   |
| 1280x800 (WXGA)    | 318       | 3.78%   |
| 2560x1440 (QHD)    | 280       | 3.33%   |
| 1440x900 (WXGA+)   | 260       | 3.09%   |
| 1680x1050 (WSXGA+) | 237       | 2.82%   |
| 1600x900 (HD+)     | 211       | 2.51%   |
| 1920x1200 (WUXGA)  | 158       | 1.88%   |
| 1360x768           | 78        | 0.93%   |
| 1024x600           | 65        | 0.77%   |
| Unknown            | 63        | 0.75%   |
| 2560x1080          | 58        | 0.69%   |
| 3440x1440          | 51        | 0.61%   |
| 2560x1600          | 51        | 0.61%   |
| 2160x1440          | 44        | 0.52%   |
| 1024x768 (XGA)     | 41        | 0.49%   |
| 3840x1080          | 34        | 0.4%    |
| 2880x1800          | 32        | 0.38%   |
| 3840x2400          | 20        | 0.24%   |
| 1920x540           | 18        | 0.21%   |
| 1600x1200          | 15        | 0.18%   |
| 1280x720 (HD)      | 14        | 0.17%   |
| 1920x1280          | 13        | 0.15%   |
| 800x1280           | 12        | 0.14%   |
| 3000x2000          | 12        | 0.14%   |
| 2736x1824          | 11        | 0.13%   |
| 3200x1800 (QHD+)   | 10        | 0.12%   |
| 3072x1920          | 8         | 0.1%    |
| 3840x1600          | 7         | 0.08%   |
| 2520x1680          | 7         | 0.08%   |
| 2256x1504          | 7         | 0.08%   |
| 2880x1920          | 6         | 0.07%   |
| 2288x1287          | 6         | 0.07%   |
| 2240x1400          | 6         | 0.07%   |
| 1280x768           | 6         | 0.07%   |
| 4480x1440          | 5         | 0.06%   |
| 3200x2000          | 5         | 0.06%   |
| 1800x1200          | 5         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2671      | 30.43%  |
| 13      | 738       | 8.41%   |
| 24      | 614       | 6.99%   |
| 27      | 600       | 6.84%   |
| 21      | 557       | 6.35%   |
| 14      | 507       | 5.78%   |
| 23      | 471       | 5.37%   |
| Unknown | 416       | 4.74%   |
| 17      | 393       | 4.48%   |
| 19      | 314       | 3.58%   |
| 18      | 165       | 1.88%   |
| 12      | 155       | 1.77%   |
| 20      | 132       | 1.5%    |
| 22      | 122       | 1.39%   |
| 31      | 110       | 1.25%   |
| 34      | 99        | 1.13%   |
| 10      | 88        | 1%      |
| 16      | 86        | 0.98%   |
| 11      | 80        | 0.91%   |
| 40      | 62        | 0.71%   |
| 54      | 48        | 0.55%   |
| 84      | 44        | 0.5%    |
| 72      | 40        | 0.46%   |
| 32      | 28        | 0.32%   |
| 25      | 28        | 0.32%   |
| 26      | 19        | 0.22%   |
| 28      | 18        | 0.21%   |
| 46      | 15        | 0.17%   |
| 48      | 14        | 0.16%   |
| 65      | 13        | 0.15%   |
| 52      | 13        | 0.15%   |
| 7       | 12        | 0.14%   |
| 42      | 11        | 0.13%   |
| 37      | 10        | 0.11%   |
| 36      | 9         | 0.1%    |
| 39      | 7         | 0.08%   |
| 29      | 7         | 0.08%   |
| 142     | 6         | 0.07%   |
| 8       | 6         | 0.07%   |
| 43      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3644      | 42.02%  |
| 501-600        | 1587      | 18.3%   |
| 401-500        | 1100      | 12.68%  |
| 201-300        | 756       | 8.72%   |
| 351-400        | 492       | 5.67%   |
| Unknown        | 416       | 4.8%    |
| 601-700        | 194       | 2.24%   |
| 701-800        | 140       | 1.61%   |
| 1001-1500      | 125       | 1.44%   |
| 1501-2000      | 90        | 1.04%   |
| 801-900        | 86        | 0.99%   |
| 901-1000       | 16        | 0.18%   |
| 1-100          | 12        | 0.14%   |
| 101-200        | 8         | 0.09%   |
| More than 2000 | 6         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5929      | 73.64%  |
| 16/10   | 1072      | 13.32%  |
| Unknown | 342       | 4.25%   |
| 5/4     | 335       | 4.16%   |
| 3/2     | 122       | 1.52%   |
| 21/9    | 112       | 1.39%   |
| 4/3     | 88        | 1.09%   |
| 6/5     | 15        | 0.19%   |
| 32/9    | 14        | 0.17%   |
| 0.67    | 11        | 0.14%   |
| 1.00    | 6         | 0.07%   |
| 0.56    | 2         | 0.02%   |
| 2.65    | 1         | 0.01%   |
| 2.21    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2672      | 30.69%  |
| 201-250        | 1432      | 16.45%  |
| 81-90          | 908       | 10.43%  |
| 151-200        | 625       | 7.18%   |
| 301-350        | 618       | 7.1%    |
| Unknown        | 416       | 4.78%   |
| 71-80          | 340       | 3.91%   |
| 141-150        | 265       | 3.04%   |
| 351-500        | 256       | 2.94%   |
| 121-130        | 205       | 2.35%   |
| More than 1000 | 191       | 2.19%   |
| 251-300        | 191       | 2.19%   |
| 501-1000       | 138       | 1.59%   |
| 61-70          | 137       | 1.57%   |
| 41-50          | 87        | 1%      |
| 51-60          | 82        | 0.94%   |
| 111-120        | 60        | 0.69%   |
| 131-140        | 37        | 0.42%   |
| 91-100         | 27        | 0.31%   |
| 1-40           | 19        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2954      | 34.66%  |
| 101-120       | 2202      | 25.84%  |
| 121-160       | 2121      | 24.89%  |
| 161-240       | 508       | 5.96%   |
| Unknown       | 416       | 4.88%   |
| 1-50          | 171       | 2.01%   |
| More than 240 | 151       | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6955      | 82.2%   |
| 2     | 1086      | 12.84%  |
| 0     | 316       | 3.73%   |
| 3     | 98        | 1.16%   |
| 4     | 6         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4548      | 36.4%   |
| Intel                             | 3622      | 28.99%  |
| Qualcomm Atheros                  | 1454      | 11.64%  |
| Broadcom                          | 725       | 5.8%    |
| Marvell Technology Group          | 224       | 1.79%   |
| TP-Link                           | 180       | 1.44%   |
| Broadcom Limited                  | 171       | 1.37%   |
| MediaTek                          | 163       | 1.3%    |
| Nvidia                            | 152       | 1.22%   |
| Ralink Technology                 | 144       | 1.15%   |
| Ralink                            | 127       | 1.02%   |
| Huawei Technologies               | 62        | 0.5%    |
| Qualcomm Atheros Communications   | 58        | 0.46%   |
| ASIX Electronics                  | 58        | 0.46%   |
| Xiaomi                            | 53        | 0.42%   |
| Samsung Electronics               | 53        | 0.42%   |
| D-Link System                     | 49        | 0.39%   |
| D-Link                            | 44        | 0.35%   |
| Dell                              | 35        | 0.28%   |
| Sitecom Europe                    | 34        | 0.27%   |
| VIA Technologies                  | 33        | 0.26%   |
| NetGear                           | 31        | 0.25%   |
| Microsoft                         | 28        | 0.22%   |
| Silicon Integrated Systems [SiS]  | 26        | 0.21%   |
| ASUSTek Computer                  | 26        | 0.21%   |
| Sierra Wireless                   | 24        | 0.19%   |
| JMicron Technology                | 24        | 0.19%   |
| Ericsson Business Mobile Networks | 23        | 0.18%   |
| Qualcomm                          | 22        | 0.18%   |
| OPPO Electronics                  | 22        | 0.18%   |
| DisplayLink                       | 18        | 0.14%   |
| Attansic Technology               | 17        | 0.14%   |
| Microchip Technology              | 14        | 0.11%   |
| Hewlett-Packard                   | 14        | 0.11%   |
| Belkin Components                 | 14        | 0.11%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.09%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.07%   |
| Lenovo                            | 9         | 0.07%   |
| Gemtek                            | 9         | 0.07%   |
| Aquantia                          | 9         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3085      | 21.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 512       | 3.53%   |
| Intel Wi-Fi 6 AX200                                                     | 288       | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 283       | 1.95%   |
| Intel Wireless 8265 / 8275                                              | 239       | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 239       | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 217       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 214       | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 207       | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 200       | 1.38%   |
| Intel Wireless 7265                                                     | 196       | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 194       | 1.34%   |
| Intel Wi-Fi 6 AX201                                                     | 185       | 1.27%   |
| Intel Wireless 3165                                                     | 171       | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 164       | 1.13%   |
| Intel Ethernet Connection (2) I219-V                                    | 128       | 0.88%   |
| Intel I211 Gigabit Network Connection                                   | 125       | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 125       | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                       | 121       | 0.83%   |
| Intel Wireless 7260                                                     | 121       | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 106       | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 103       | 0.71%   |
| Intel Wireless 8260                                                     | 92        | 0.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 92        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 90        | 0.62%   |
| Intel Ethernet Connection I217-LM                                       | 90        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 89        | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 87        | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 85        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 85        | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 83        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                 | 83        | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 79        | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 78        | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 76        | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                           | 75        | 0.52%   |
| Intel WiFi Link 5100                                                    | 74        | 0.51%   |
| Intel Ethernet Controller I225-V                                        | 73        | 0.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 72        | 0.5%    |
| Intel Wireless-AC 9260                                                  | 67        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2738      | 40.3%   |
| Realtek Semiconductor                 | 1253      | 18.44%  |
| Qualcomm Atheros                      | 1228      | 18.07%  |
| Broadcom                              | 480       | 7.07%   |
| TP-Link                               | 163       | 2.4%    |
| MediaTek                              | 153       | 2.25%   |
| Ralink Technology                     | 144       | 2.12%   |
| Ralink                                | 127       | 1.87%   |
| Broadcom Limited                      | 103       | 1.52%   |
| Qualcomm Atheros Communications       | 58        | 0.85%   |
| D-Link                                | 43        | 0.63%   |
| D-Link System                         | 40        | 0.59%   |
| Sitecom Europe                        | 33        | 0.49%   |
| NetGear                               | 30        | 0.44%   |
| Microsoft                             | 25        | 0.37%   |
| ASUSTek Computer                      | 25        | 0.37%   |
| Sierra Wireless                       | 24        | 0.35%   |
| Dell                                  | 24        | 0.35%   |
| Marvell Technology Group              | 14        | 0.21%   |
| Belkin Components                     | 14        | 0.21%   |
| Gemtek                                | 9         | 0.13%   |
| Qualcomm                              | 8         | 0.12%   |
| Fibocom                               | 8         | 0.12%   |
| Ericsson Business Mobile Networks     | 8         | 0.12%   |
| AVM                                   | 7         | 0.1%    |
| Linksys                               | 6         | 0.09%   |
| ZyDAS                                 | 5         | 0.07%   |
| Edimax Technology                     | 5         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.06%   |
| ZyXEL Communications                  | 2         | 0.03%   |
| U.S. Robotics                         | 2         | 0.03%   |
| Qcom                                  | 2         | 0.03%   |
| Hewlett-Packard                       | 2         | 0.03%   |
| Wilocity                              | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Micro Star International              | 1         | 0.01%   |
| Fiberline                             | 1         | 0.01%   |
| Accton Technology                     | 1         | 0.01%   |
| AboCom Systems                        | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 288       | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 283       | 4.14%   |
| Intel Wireless 8265 / 8275                                              | 239       | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 214       | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 207       | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 200       | 2.92%   |
| Intel Wireless 7265                                                     | 196       | 2.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 194       | 2.84%   |
| Intel Wi-Fi 6 AX201                                                     | 185       | 2.7%    |
| Intel Wireless 3165                                                     | 171       | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 164       | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 125       | 1.83%   |
| Intel Wireless 7260                                                     | 121       | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 106       | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 103       | 1.51%   |
| Intel Wireless 8260                                                     | 92        | 1.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 92        | 1.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 89        | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 87        | 1.27%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 85        | 1.24%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 85        | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 83        | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 79        | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 78        | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 76        | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 75        | 1.1%    |
| Intel WiFi Link 5100                                                    | 74        | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 72        | 1.05%   |
| Intel Wireless-AC 9260                                                  | 67        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 67        | 0.98%   |
| Realtek 802.11ac NIC                                                    | 65        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 62        | 0.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 61        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 60        | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 57        | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 54        | 0.79%   |
| Qualcomm Atheros AR9271 802.11n                                         | 53        | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 50        | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 49        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 45        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4067      | 54.86%  |
| Intel                            | 1701      | 22.94%  |
| Qualcomm Atheros                 | 373       | 5.03%   |
| Broadcom                         | 337       | 4.55%   |
| Marvell Technology Group         | 210       | 2.83%   |
| Nvidia                           | 151       | 2.04%   |
| Broadcom Limited                 | 69        | 0.93%   |
| ASIX Electronics                 | 58        | 0.78%   |
| Xiaomi                           | 53        | 0.71%   |
| Huawei Technologies              | 50        | 0.67%   |
| Samsung Electronics              | 40        | 0.54%   |
| VIA Technologies                 | 31        | 0.42%   |
| Silicon Integrated Systems [SiS] | 24        | 0.32%   |
| JMicron Technology               | 24        | 0.32%   |
| OPPO Electronics                 | 22        | 0.3%    |
| DisplayLink                      | 18        | 0.24%   |
| TP-Link                          | 17        | 0.23%   |
| Attansic Technology              | 17        | 0.23%   |
| Qualcomm                         | 14        | 0.19%   |
| ZTE WCDMA Technologies MSM       | 10        | 0.13%   |
| Microchip Technology             | 10        | 0.13%   |
| MediaTek                         | 10        | 0.13%   |
| Lenovo                           | 9         | 0.12%   |
| D-Link System                    | 9         | 0.12%   |
| Aquantia                         | 9         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.11%   |
| HMD Global                       | 7         | 0.09%   |
| Apple                            | 7         | 0.09%   |
| 3Com                             | 6         | 0.08%   |
| Motorola PCS                     | 5         | 0.07%   |
| ICS Advent                       | 5         | 0.07%   |
| Hewlett-Packard                  | 5         | 0.07%   |
| Google                           | 5         | 0.07%   |
| T & A Mobile Phones              | 4         | 0.05%   |
| LG Electronics                   | 3         | 0.04%   |
| Standard Microsystems            | 2         | 0.03%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| NetXen Incorporated              | 2         | 0.03%   |
| Foxconn / Hon Hai                | 2         | 0.03%   |
| Dell                             | 2         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3085      | 40.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 512       | 6.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 239       | 3.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 217       | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 128       | 1.7%    |
| Intel I211 Gigabit Network Connection                             | 125       | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 121       | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 90        | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 90        | 1.19%   |
| Intel 82579V Gigabit Network Connection                           | 83        | 1.1%    |
| Intel Ethernet Controller I225-V                                  | 73        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 62        | 0.82%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 59        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 52        | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 52        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 50        | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 44        | 0.58%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 44        | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 43        | 0.57%   |
| ASIX AX88179 Gigabit Ethernet                                     | 42        | 0.56%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 41        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 40        | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 40        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 39        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 38        | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 38        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 37        | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 37        | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 36        | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 35        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 33        | 0.44%   |
| Huawei MAR-LX1M                                                   | 33        | 0.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 31        | 0.41%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.41%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 29        | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 29        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6990      | 51.61%  |
| WiFi     | 6419      | 47.4%   |
| Modem    | 123       | 0.91%   |
| Unknown  | 11        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4989      | 59.03%  |
| Ethernet | 3458      | 40.92%  |
| Unknown  | 3         | 0.04%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4452      | 53.61%  |
| 1     | 3474      | 41.84%  |
| 0     | 203       | 2.44%   |
| 3     | 147       | 1.77%   |
| 4     | 19        | 0.23%   |
| 5     | 4         | 0.05%   |
| 12    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7771      | 92.62%  |
| Yes  | 619       | 7.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2169      | 44.12%  |
| Realtek Semiconductor           | 632       | 12.86%  |
| Qualcomm Atheros Communications | 288       | 5.86%   |
| Cambridge Silicon Radio         | 280       | 5.7%    |
| IMC Networks                    | 266       | 5.41%   |
| Broadcom                        | 240       | 4.88%   |
| Lite-On Technology              | 207       | 4.21%   |
| Apple                           | 184       | 3.74%   |
| Foxconn / Hon Hai               | 166       | 3.38%   |
| Hewlett-Packard                 | 74        | 1.51%   |
| ASUSTek Computer                | 74        | 1.51%   |
| Realtek                         | 70        | 1.42%   |
| Dell                            | 46        | 0.94%   |
| Ralink                          | 39        | 0.79%   |
| Toshiba                         | 36        | 0.73%   |
| MediaTek                        | 32        | 0.65%   |
| Alps Electric                   | 17        | 0.35%   |
| Marvell Semiconductor           | 13        | 0.26%   |
| TP-Link                         | 12        | 0.24%   |
| Integrated System Solution      | 11        | 0.22%   |
| Ralink Technology               | 7         | 0.14%   |
| Foxconn International           | 7         | 0.14%   |
| Belkin Components               | 5         | 0.1%    |
| Sitecom Europe                  | 4         | 0.08%   |
| Chicony Electronics             | 4         | 0.08%   |
| Askey Computer                  | 4         | 0.08%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| Conwise Technology              | 3         | 0.06%   |
| SINO WEALTH                     | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| HTC (High Tech Computer)        | 2         | 0.04%   |
| Edimax Technology               | 2         | 0.04%   |
| D-Link System                   | 2         | 0.04%   |
| Accel Semiconductor             | 2         | 0.04%   |
| USI                             | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 838       | 17.04%  |
| Intel AX201 Bluetooth                                                               | 399       | 8.11%   |
| Realtek Bluetooth Radio                                                             | 392       | 7.97%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 303       | 6.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 280       | 5.69%   |
| Intel AX200 Bluetooth                                                               | 271       | 5.51%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 145       | 2.95%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 113       | 2.3%    |
| IMC Networks Bluetooth Device                                                       | 110       | 2.24%   |
| Apple Bluetooth Host Controller                                                     | 90        | 1.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 85        | 1.73%   |
| Intel Bluetooth Device                                                              | 74        | 1.5%    |
| IMC Networks Bluetooth Radio                                                        | 74        | 1.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 68        | 1.38%   |
| Realtek 802.11ac WLAN Adapter                                                       | 67        | 1.36%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 63        | 1.28%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 61        | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 58        | 1.18%   |
| Intel AX210 Bluetooth                                                               | 56        | 1.14%   |
| Realtek 802.11ac WLAN Adapter                                                       | 55        | 1.12%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 52        | 1.06%   |
| Lite-On Bluetooth Device                                                            | 52        | 1.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 51        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 48        | 0.98%   |
| IMC Networks Wireless_Device                                                        | 44        | 0.89%   |
| Broadcom BCM2045 Bluetooth                                                          | 43        | 0.87%   |
| Ralink RT3290 Bluetooth                                                             | 39        | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 39        | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 35        | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 35        | 0.71%   |
| Apple Bluetooth USB Host Controller                                                 | 34        | 0.69%   |
| Apple Bluetooth HCI                                                                 | 30        | 0.61%   |
| MediaTek Wireless_Device                                                            | 27        | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 26        | 0.53%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 25        | 0.51%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 25        | 0.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 25        | 0.51%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 24        | 0.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 23        | 0.47%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 20        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5970      | 54.24%  |
| AMD                                          | 2247      | 20.41%  |
| Nvidia                                       | 1762      | 16.01%  |
| C-Media Electronics                          | 191       | 1.74%   |
| Logitech                                     | 67        | 0.61%   |
| Creative Labs                                | 61        | 0.55%   |
| VIA Technologies                             | 44        | 0.4%    |
| JMTek                                        | 36        | 0.33%   |
| Silicon Integrated Systems [SiS]             | 35        | 0.32%   |
| GN Netcom                                    | 30        | 0.27%   |
| Generalplus Technology                       | 29        | 0.26%   |
| Texas Instruments                            | 27        | 0.25%   |
| Realtek Semiconductor                        | 26        | 0.24%   |
| Razer USA                                    | 24        | 0.22%   |
| Creative Technology                          | 24        | 0.22%   |
| Focusrite-Novation                           | 23        | 0.21%   |
| ASUSTek Computer                             | 19        | 0.17%   |
| M-Audio                                      | 18        | 0.16%   |
| Micro Star International                     | 17        | 0.15%   |
| Kingston Technology                          | 14        | 0.13%   |
| BEHRINGER International                      | 14        | 0.13%   |
| Samson Technologies                          | 13        | 0.12%   |
| Hewlett-Packard                              | 12        | 0.11%   |
| Corsair                                      | 12        | 0.11%   |
| Thesycon Systemsoftware & Consulting         | 11        | 0.1%    |
| Plantronics                                  | 11        | 0.1%    |
| Tenx Technology                              | 10        | 0.09%   |
| Dell                                         | 10        | 0.09%   |
| CMX Systems                                  | 10        | 0.09%   |
| DSEA A/S                                     | 9         | 0.08%   |
| BR25                                         | 9         | 0.08%   |
| Apple                                        | 9         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 8         | 0.07%   |
| Trust                                        | 8         | 0.07%   |
| Lenovo                                       | 8         | 0.07%   |
| Sony                                         | 7         | 0.06%   |
| Microsoft                                    | 7         | 0.06%   |
| Ensoniq                                      | 7         | 0.06%   |
| SteelSeries ApS                              | 6         | 0.05%   |
| Cambridge Silicon Radio                      | 6         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 677       | 5.21%   |
| Intel Sunrise Point-LP HD Audio                                            | 630       | 4.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 499       | 3.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 476       | 3.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 379       | 2.91%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 357       | 2.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 351       | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 329       | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 296       | 2.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 261       | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 254       | 1.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 253       | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 249       | 1.91%   |
| AMD FCH Azalia Controller                                                  | 242       | 1.86%   |
| AMD Starship/Matisse HD Audio Controller                                   | 233       | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 232       | 1.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 228       | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 217       | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 217       | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 171       | 1.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 167       | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 165       | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                               | 162       | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 162       | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 150       | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 141       | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 140       | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 138       | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 136       | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                              | 129       | 0.99%   |
| Nvidia High Definition Audio Controller                                    | 126       | 0.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 125       | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 120       | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 111       | 0.85%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 108       | 0.83%   |
| Intel Comet Lake PCH cAVS                                                  | 107       | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 103       | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 94        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 90        | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 89        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1216      | 22.34%  |
| SK hynix                     | 919       | 16.88%  |
| Kingston                     | 660       | 12.13%  |
| Unknown                      | 590       | 10.84%  |
| Micron Technology            | 545       | 10.01%  |
| Crucial                      | 378       | 6.94%   |
| Corsair                      | 331       | 6.08%   |
| G.Skill                      | 103       | 1.89%   |
| Unknown (ABCD)               | 102       | 1.87%   |
| Ramaxel Technology           | 95        | 1.75%   |
| Elpida                       | 92        | 1.69%   |
| A-DATA Technology            | 79        | 1.45%   |
| Nanya Technology             | 57        | 1.05%   |
| Team                         | 44        | 0.81%   |
| Unknown                      | 40        | 0.73%   |
| Patriot                      | 32        | 0.59%   |
| Transcend                    | 22        | 0.4%    |
| ASint Technology             | 14        | 0.26%   |
| Unifosa                      | 9         | 0.17%   |
| Timetec                      | 8         | 0.15%   |
| Toshiba                      | 6         | 0.11%   |
| Silicon Power                | 6         | 0.11%   |
| Qimonda                      | 6         | 0.11%   |
| 48spaces                     | 6         | 0.11%   |
| Patriot Memory (PDP Systems) | 4         | 0.07%   |
| Lexar                        | 4         | 0.07%   |
| Hewlett-Packard              | 4         | 0.07%   |
| GOODRAM                      | 4         | 0.07%   |
| GeIL                         | 4         | 0.07%   |
| CSX                          | 4         | 0.07%   |
| Unknown (AB)                 | 3         | 0.06%   |
| A Force                      | 3         | 0.06%   |
| PUSKILL                      | 2         | 0.04%   |
| PLEXHD                       | 2         | 0.04%   |
| Netac                        | 2         | 0.04%   |
| Hikvision                    | 2         | 0.04%   |
| Goldkey                      | 2         | 0.04%   |
| ChangXin Memory              | 2         | 0.04%   |
| Apacer                       | 2         | 0.04%   |
| Wodposit                     | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 71        | 1.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 53        | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 51        | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 42        | 0.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s             | 42        | 0.72%   |
| Unknown                                                           | 40        | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 38        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 38        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 35        | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 34        | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 32        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 31        | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 31        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 30        | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 30        | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 30        | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s            | 29        | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 28        | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 27        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s             | 26        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s             | 26        | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s          | 26        | 0.44%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s             | 26        | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                        | 25        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 25        | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 25        | 0.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 24        | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s          | 24        | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s            | 23        | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 22        | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 22        | 0.38%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                          | 21        | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s            | 21        | 0.36%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s             | 21        | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s            | 20        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 3200MT/s          | 20        | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 19        | 0.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s            | 18        | 0.31%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s       | 18        | 0.31%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s            | 18        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2177      | 45.73%  |
| DDR3    | 1523      | 31.99%  |
| DDR2    | 300       | 6.3%    |
| LPDDR4  | 237       | 4.98%   |
| SDRAM   | 161       | 3.38%   |
| LPDDR3  | 117       | 2.46%   |
| Unknown | 92        | 1.93%   |
| DDR5    | 66        | 1.39%   |
| DDR     | 38        | 0.8%    |
| LPDDR5  | 36        | 0.76%   |
| DRAM    | 14        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2774      | 58.6%   |
| DIMM         | 1551      | 32.76%  |
| Row Of Chips | 389       | 8.22%   |
| Chip         | 12        | 0.25%   |
| FB-DIMM      | 4         | 0.08%   |
| Unknown      | 4         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1958      | 37.7%   |
| 4096  | 1469      | 28.29%  |
| 2048  | 730       | 14.06%  |
| 16384 | 681       | 13.11%  |
| 1024  | 180       | 3.47%   |
| 32768 | 130       | 2.5%    |
| 512   | 37        | 0.71%   |
| 256   | 5         | 0.1%    |
| 3072  | 2         | 0.04%   |
| 32    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 937       | 18.13%  |
| 3200    | 768       | 14.86%  |
| 2667    | 726       | 14.05%  |
| 2400    | 378       | 7.31%   |
| 1333    | 313       | 6.06%   |
| 2133    | 226       | 4.37%   |
| 1334    | 164       | 3.17%   |
| Unknown | 143       | 2.77%   |
| 3600    | 135       | 2.61%   |
| 667     | 135       | 2.61%   |
| 800     | 129       | 2.5%    |
| 1867    | 115       | 2.23%   |
| 4267    | 84        | 1.63%   |
| 1066    | 68        | 1.32%   |
| 3266    | 57        | 1.1%    |
| 4800    | 53        | 1.03%   |
| 3733    | 49        | 0.95%   |
| 1067    | 44        | 0.85%   |
| 3400    | 43        | 0.83%   |
| 2933    | 40        | 0.77%   |
| 6400    | 37        | 0.72%   |
| 3000    | 36        | 0.7%    |
| 1800    | 35        | 0.68%   |
| 2666    | 31        | 0.6%    |
| 1866    | 30        | 0.58%   |
| 3533    | 27        | 0.52%   |
| 533     | 27        | 0.52%   |
| 3666    | 24        | 0.46%   |
| 2048    | 24        | 0.46%   |
| 4199    | 23        | 0.45%   |
| 3800    | 19        | 0.37%   |
| 8400    | 18        | 0.35%   |
| 400     | 17        | 0.33%   |
| 266     | 15        | 0.29%   |
| 4266    | 14        | 0.27%   |
| 2800    | 11        | 0.21%   |
| 975     | 11        | 0.21%   |
| 333     | 11        | 0.21%   |
| 2000    | 9         | 0.17%   |
| 3500    | 7         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 122       | 36.97%  |
| Samsung Electronics   | 59        | 17.88%  |
| Canon                 | 45        | 13.64%  |
| Brother Industries    | 37        | 11.21%  |
| Seiko Epson           | 36        | 10.91%  |
| Dymo-CoStar           | 5         | 1.52%   |
| Xerox                 | 4         | 1.21%   |
| Lexmark International | 4         | 1.21%   |
| Pantum                | 3         | 0.91%   |
| Prolific Technology   | 2         | 0.61%   |
| Oki Data              | 2         | 0.61%   |
| Kyocera               | 2         | 0.61%   |
| Apple                 | 2         | 0.61%   |
| Toshiba TEC           | 1         | 0.3%    |
| STMicroelectronics    | 1         | 0.3%    |
| Sato                  | 1         | 0.3%    |
| Sagem                 | 1         | 0.3%    |
| Ricoh                 | 1         | 0.3%    |
| QinHeng Electronics   | 1         | 0.3%    |
| ICS Advent            | 1         | 0.3%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                                  | 10        | 3.02%   |
| Seiko Epson WF-2510 Series                                            | 8         | 2.42%   |
| Samsung M267x 287x Series                                             | 8         | 2.42%   |
| HP OfficeJet 6950                                                     | 8         | 2.42%   |
| Seiko Epson Printer                                                   | 7         | 2.11%   |
| Samsung ML-216x Series Laser Printer                                  | 7         | 2.11%   |
| Samsung M2070 Series                                                  | 7         | 2.11%   |
| HP Deskjet 2050 J510                                                  | 7         | 2.11%   |
| HP LaserJet 1018                                                      | 6         | 1.81%   |
| HP ENVY 5000 series                                                   | 5         | 1.51%   |
| HP ENVY 4520 series                                                   | 5         | 1.51%   |
| Canon LiDE 400                                                        | 5         | 1.51%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 4         | 1.21%   |
| HP Officejet 2620 series                                              | 4         | 1.21%   |
| HP LaserJet P1102                                                     | 4         | 1.21%   |
| Canon PIXMA MG3600 Series                                             | 4         | 1.21%   |
| Samsung ML-1660 Series                                                | 3         | 0.91%   |
| Samsung ML-1640 Series Laser Printer                                  | 3         | 0.91%   |
| Samsung Composite Device                                              | 3         | 0.91%   |
| HP LaserJet Professional P 1102w                                      | 3         | 0.91%   |
| HP LaserJet P1005                                                     | 3         | 0.91%   |
| HP LaserJet 1200                                                      | 3         | 0.91%   |
| HP Deskjet F4500 series                                               | 3         | 0.91%   |
| HP Deskjet 3520 series                                                | 3         | 0.91%   |
| HP Deskjet 3050A                                                      | 3         | 0.91%   |
| Dymo-CoStar LabelWriter 450                                           | 3         | 0.91%   |
| Canon PIXMA MG2500 Series                                             | 3         | 0.91%   |
| Brother MFC-L2710DW series                                            | 3         | 0.91%   |
| Brother MFC-L2700DW                                                   | 3         | 0.91%   |
| Brother HL-3140CW series                                              | 3         | 0.91%   |
| Brother DCP-1610W                                                     | 3         | 0.91%   |
| Seiko Epson WF-2870 Series                                            | 2         | 0.6%    |
| Seiko Epson ET-2820 Series                                            | 2         | 0.6%    |
| Samsung SCX-4623 Series                                               | 2         | 0.6%    |
| Samsung SCX-4300 Series                                               | 2         | 0.6%    |
| Samsung ML-331x Series Laser Printer                                  | 2         | 0.6%    |
| Samsung CLP-325 Color Laser Printer                                   | 2         | 0.6%    |
| Prolific PL2305 Parallel Port                                         | 2         | 0.6%    |
| Oki Data USB Device                                                   | 2         | 0.6%    |
| Lexmark International InkJet Color Printer                            | 2         | 0.6%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 47        | 56.63%  |
| Seiko Epson        | 21        | 25.3%   |
| Hewlett-Packard    | 9         | 10.84%  |
| Mustek Systems     | 4         | 4.82%   |
| Ultima Electronics | 1         | 1.2%    |
| Plustek            | 1         | 1.2%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 10        | 11.9%   |
| Canon CanoScan LiDE 210                                                               | 7         | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 5         | 5.95%   |
| Canon CanoScan LiDE 120                                                               | 4         | 4.76%   |
| Canon CanoScan LiDE 100                                                               | 4         | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3         | 3.57%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 3.57%   |
| Canon CanoScan LiDE 60                                                                | 3         | 3.57%   |
| Canon CanoScan LiDE 220                                                               | 3         | 3.57%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2         | 2.38%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.38%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 2.38%   |
| HP Scanjet 200                                                                        | 2         | 2.38%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.38%   |
| Canon CanoScan LiDE 700F                                                              | 2         | 2.38%   |
| Canon CanoScan LIDE 25                                                                | 2         | 2.38%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.19%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 1.19%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 1.19%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 1.19%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 1.19%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.19%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.19%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.19%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1         | 1.19%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.19%   |
| Seiko Epson ES-D400 [GT-S80]                                                          | 1         | 1.19%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.19%   |
| Plustek 600DPI USB Scanner                                                            | 1         | 1.19%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.19%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 1.19%   |
| HP Scanjet G2710                                                                      | 1         | 1.19%   |
| HP ScanJet 3800c                                                                      | 1         | 1.19%   |
| HP ScanJet 3570c                                                                      | 1         | 1.19%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.19%   |
| HP ScanJet 2400c                                                                      | 1         | 1.19%   |
| HP PSC 1200                                                                           | 1         | 1.19%   |
| HP HP4470C                                                                            | 1         | 1.19%   |
| Canon CanoScan LiDE 90                                                                | 1         | 1.19%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.19%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1171      | 22.64%  |
| IMC Networks                           | 544       | 10.52%  |
| Microdia                               | 380       | 7.35%   |
| Realtek Semiconductor                  | 358       | 6.92%   |
| Bison Electronics                      | 284       | 5.49%   |
| Logitech                               | 259       | 5.01%   |
| Quanta                                 | 253       | 4.89%   |
| Sunplus Innovation Technology          | 219       | 4.23%   |
| Suyin                                  | 203       | 3.92%   |
| Cheng Uei Precision Industry (Foxlink) | 203       | 3.92%   |
| Apple                                  | 154       | 2.98%   |
| Syntek                                 | 128       | 2.47%   |
| Alcor Micro                            | 114       | 2.2%    |
| Lite-On Technology                     | 101       | 1.95%   |
| Luxvisions Innotech Limited            | 95        | 1.84%   |
| Acer                                   | 87        | 1.68%   |
| Microsoft                              | 79        | 1.53%   |
| Silicon Motion                         | 56        | 1.08%   |
| Ricoh                                  | 55        | 1.06%   |
| Samsung Electronics                    | 31        | 0.6%    |
| Z-Star Microelectronics                | 29        | 0.56%   |
| ARC International                      | 28        | 0.54%   |
| Trust                                  | 25        | 0.48%   |
| Sonix Technology                       | 22        | 0.43%   |
| Generalplus Technology                 | 18        | 0.35%   |
| ALi                                    | 18        | 0.35%   |
| Primax Electronics                     | 15        | 0.29%   |
| icSpring                               | 15        | 0.29%   |
| SunplusIT                              | 13        | 0.25%   |
| KYE Systems (Mouse Systems)            | 13        | 0.25%   |
| GEMBIRD                                | 12        | 0.23%   |
| Sunplus Technology                     | 11        | 0.21%   |
| Lenovo                                 | 10        | 0.19%   |
| Genesys Logic                          | 10        | 0.19%   |
| HDR webcam                             | 9         | 0.17%   |
| DigiTech                               | 9         | 0.17%   |
| Cubeternet                             | 9         | 0.17%   |
| WaveRider Communications               | 8         | 0.15%   |
| Importek                               | 8         | 0.15%   |
| Sunplus IT                             | 7         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 189       | 3.62%   |
| Microdia Integrated_Webcam_HD                           | 138       | 2.65%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 113       | 2.17%   |
| Chicony HD Webcam                                       | 95        | 1.82%   |
| Bison Integrated Camera                                 | 94        | 1.8%    |
| IMC Networks Integrated Camera                          | 92        | 1.76%   |
| Realtek Integrated_Webcam_HD                            | 85        | 1.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 79        | 1.52%   |
| Realtek USB Camera                                      | 77        | 1.48%   |
| Syntek Integrated Camera                                | 76        | 1.46%   |
| Logitech Webcam C270                                    | 73        | 1.4%    |
| Alcor Micro USB 2.0 Camera                              | 58        | 1.11%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 54        | 1.04%   |
| Chicony USB2.0 VGA UVC WebCam                           | 53        | 1.02%   |
| Apple Built-in iSight                                   | 52        | 1%      |
| Chicony HP TrueVision HD                                | 51        | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                            | 49        | 0.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 46        | 0.88%   |
| Sunplus Integrated_Webcam_HD                            | 44        | 0.84%   |
| Chicony HP TrueVision HD Camera                         | 44        | 0.84%   |
| Quanta HP TrueVision HD Camera                          | 41        | 0.79%   |
| Bison HD Webcam                                         | 41        | 0.79%   |
| Chicony HP HD Camera                                    | 39        | 0.75%   |
| Microdia Webcam Vitade AF                               | 38        | 0.73%   |
| IMC Networks ov9734_azurewave_camera                    | 36        | 0.69%   |
| Chicony HP Wide Vision HD Camera                        | 36        | 0.69%   |
| Microsoft LifeCam HD-3000                               | 35        | 0.67%   |
| IMC Networks HD Camera                                  | 35        | 0.67%   |
| Chicony HP Webcam                                       | 35        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 35        | 0.67%   |
| Quanta HD User Facing                                   | 34        | 0.65%   |
| Logitech HD Pro Webcam C920                             | 33        | 0.63%   |
| Chicony FJ Camera                                       | 32        | 0.61%   |
| Sunplus HD WebCam                                       | 31        | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 31        | 0.59%   |
| Apple FaceTime HD Camera (Built-in)                     | 31        | 0.59%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 29        | 0.56%   |
| Quanta HP Webcam                                        | 29        | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                           | 28        | 0.54%   |
| ARC International Camera                                | 28        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 260       | 28.57%  |
| Synaptics                          | 221       | 24.29%  |
| Shenzhen Goodix Technology         | 164       | 18.02%  |
| Elan Microelectronics              | 110       | 12.09%  |
| AuthenTec                          | 46        | 5.05%   |
| Upek                               | 45        | 4.95%   |
| LighTuning Technology              | 45        | 4.95%   |
| STMicroelectronics                 | 6         | 0.66%   |
| Focal-systems.Corp                 | 6         | 0.66%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.33%   |
| Samsung Electronics                | 1         | 0.11%   |
| Microsoft                          | 1         | 0.11%   |
| HOLTEK                             | 1         | 0.11%   |
| Dell                               | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 115       | 12.64%  |
| Elan ELAN:ARM-M4                                                           | 72        | 7.91%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 53        | 5.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 52        | 5.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 39        | 4.29%   |
| Elan ELAN:Fingerprint                                                      | 38        | 4.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 35        | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 3.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 2.97%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 26        | 2.86%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 25        | 2.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 2.64%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 24        | 2.64%   |
| Synaptics  WBDI                                                            | 19        | 2.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 18        | 1.98%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 1.98%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 1.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 16        | 1.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.65%   |
| Synaptics WBDI                                                             | 15        | 1.65%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 1.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.32%   |
| Validity Sensors VFS491                                                    | 11        | 1.21%   |
| Synaptics UWP WBDI                                                         | 11        | 1.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.21%   |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 1.21%   |
| Unknown                                                                    | 11        | 1.21%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 0.99%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.88%   |
| AuthenTec AES2810                                                          | 8         | 0.88%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.77%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.77%   |
| AuthenTec AES1600                                                          | 7         | 0.77%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.66%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.66%   |
| Synaptics TouchPad                                                         | 6         | 0.66%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.66%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 130       | 34.67%  |
| Alcor Micro               | 114       | 30.4%   |
| O2 Micro                  | 30        | 8%      |
| Advanced Card Systems     | 26        | 6.93%   |
| Lenovo                    | 16        | 4.27%   |
| Upek                      | 13        | 3.47%   |
| Bit4id                    | 13        | 3.47%   |
| Realtek Semiconductor     | 8         | 2.13%   |
| Gemalto (was Gemplus)     | 8         | 2.13%   |
| SCM Microsystems          | 6         | 1.6%    |
| OmniKey                   | 3         | 0.8%    |
| Clay Logic                | 3         | 0.8%    |
| Reiner SCT Kartensysteme  | 2         | 0.53%   |
| Microchip Technology      | 1         | 0.27%   |
| In Focus Systems          | 1         | 0.27%   |
| Fujitsu Siemens Computers | 1         | 0.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 109       | 28.99%  |
| Broadcom 58200                                                               | 41        | 10.9%   |
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 9.84%   |
| Broadcom 5880                                                                | 30        | 7.98%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 6.91%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 5.32%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 19        | 5.05%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 4.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 3.46%   |
| Bit4id miniLector EVO                                                        | 11        | 2.93%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 8         | 2.13%   |
| Advanced Card Systems ACR122U                                                | 7         | 1.86%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.33%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.06%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.8%    |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.8%    |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 2         | 0.53%   |
| SCM Microsystems Identiv SmartOS Reader                                      | 2         | 0.53%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.53%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.27%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.27%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.27%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.27%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.27%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.27%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.27%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.27%   |
| Bit4id miniLector-s                                                          | 1         | 0.27%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.27%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5963      | 70.06%  |
| 1     | 2062      | 24.23%  |
| 2     | 418       | 4.91%   |
| 3     | 46        | 0.54%   |
| 4     | 15        | 0.18%   |
| 5     | 5         | 0.06%   |
| 6     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 899       | 29.97%  |
| Graphics card            | 756       | 25.2%   |
| Net/wireless             | 357       | 11.9%   |
| Chipcard                 | 317       | 10.57%  |
| Multimedia controller    | 146       | 4.87%   |
| Camera                   | 104       | 3.47%   |
| Communication controller | 96        | 3.2%    |
| Bluetooth                | 72        | 2.4%    |
| Sound                    | 40        | 1.33%   |
| Unassigned class         | 38        | 1.27%   |
| Storage                  | 34        | 1.13%   |
| Modem                    | 26        | 0.87%   |
| Card reader              | 26        | 0.87%   |
| Net/ethernet             | 22        | 0.73%   |
| Flash memory             | 18        | 0.6%    |
| Network                  | 15        | 0.5%    |
| Storage/raid             | 9         | 0.3%    |
| Dvb card                 | 8         | 0.27%   |
| Storage/ide              | 5         | 0.17%   |
| Firewire controller      | 5         | 0.17%   |
| Wireless                 | 2         | 0.07%   |
| Video                    | 2         | 0.07%   |
| Tv card                  | 2         | 0.07%   |
| Storage/nvme             | 1         | 0.03%   |

