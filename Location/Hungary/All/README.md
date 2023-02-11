Linux in Hungary - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Hungary/Desktop/README.md) and [notebooks](/Location/Hungary/Notebook/README.md).

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

Total: 7028

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| eMachines     | E725                        | Notebook    | [4b1805b3f6](https://linux-hardware.org/?probe=4b1805b3f6) | Feb 01, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [2f7f3a5b93](https://linux-hardware.org/?probe=2f7f3a5b93) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8a90f64e68](https://linux-hardware.org/?probe=8a90f64e68) | Feb 01, 2023 |
| HP            | 250 G1                      | Notebook    | [41f3eccf2e](https://linux-hardware.org/?probe=41f3eccf2e) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [2bdd007ce6](https://linux-hardware.org/?probe=2bdd007ce6) | Feb 01, 2023 |
| HP            | 250 G1                      | Notebook    | [345cb01bcc](https://linux-hardware.org/?probe=345cb01bcc) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [1a3af834c9](https://linux-hardware.org/?probe=1a3af834c9) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | Notebook    | [78f5b5c42b](https://linux-hardware.org/?probe=78f5b5c42b) | Feb 01, 2023 |
| HP            | 21EF                        | Desktop     | [0aacd43b02](https://linux-hardware.org/?probe=0aacd43b02) | Jan 31, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [04c77927f5](https://linux-hardware.org/?probe=04c77927f5) | Jan 31, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5dc21f30b5](https://linux-hardware.org/?probe=5dc21f30b5) | Jan 31, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [4762c2a35b](https://linux-hardware.org/?probe=4762c2a35b) | Jan 31, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [4aa843346a](https://linux-hardware.org/?probe=4aa843346a) | Jan 31, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [00fcd39954](https://linux-hardware.org/?probe=00fcd39954) | Jan 31, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [339aef175f](https://linux-hardware.org/?probe=339aef175f) | Jan 30, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [e0b08d335b](https://linux-hardware.org/?probe=e0b08d335b) | Jan 30, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [35edbda29f](https://linux-hardware.org/?probe=35edbda29f) | Jan 30, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [e21e3e152b](https://linux-hardware.org/?probe=e21e3e152b) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 431924G       | Notebook    | [c899463c77](https://linux-hardware.org/?probe=c899463c77) | Jan 30, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c89aeaf207](https://linux-hardware.org/?probe=c89aeaf207) | Jan 30, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a3e79a2330](https://linux-hardware.org/?probe=a3e79a2330) | Jan 30, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [5181ba0a3d](https://linux-hardware.org/?probe=5181ba0a3d) | Jan 30, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [5fe35cda58](https://linux-hardware.org/?probe=5fe35cda58) | Jan 29, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [ec1220585a](https://linux-hardware.org/?probe=ec1220585a) | Jan 29, 2023 |
| HP            | ProBook 4520s               | Notebook    | [6a16110b08](https://linux-hardware.org/?probe=6a16110b08) | Jan 29, 2023 |
| HP            | ProBook 4520s               | Notebook    | [e973aeb114](https://linux-hardware.org/?probe=e973aeb114) | Jan 29, 2023 |
| Samsung       | N102S                       | Notebook    | [c23908cf42](https://linux-hardware.org/?probe=c23908cf42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T480 20L6SF8C00    | Notebook    | [4ab453f835](https://linux-hardware.org/?probe=4ab453f835) | Jan 28, 2023 |
| Dell          | 0XGMD0 A00                  | All in one  | [c3438c97e8](https://linux-hardware.org/?probe=c3438c97e8) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f3530a6a1f](https://linux-hardware.org/?probe=f3530a6a1f) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [7597b19143](https://linux-hardware.org/?probe=7597b19143) | Jan 26, 2023 |
| MSI           | MS-9661 SA                  | Server      | [eb8c03cb10](https://linux-hardware.org/?probe=eb8c03cb10) | Jan 25, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4804425adc](https://linux-hardware.org/?probe=4804425adc) | Jan 25, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [60fffa5422](https://linux-hardware.org/?probe=60fffa5422) | Jan 25, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [2a1ad07cce](https://linux-hardware.org/?probe=2a1ad07cce) | Jan 25, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [2b83e8779f](https://linux-hardware.org/?probe=2b83e8779f) | Jan 25, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [cc3599afd2](https://linux-hardware.org/?probe=cc3599afd2) | Jan 24, 2023 |
| Dell          | Latitude 5480               | Notebook    | [0e21cc929a](https://linux-hardware.org/?probe=0e21cc929a) | Jan 24, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [16e64883d7](https://linux-hardware.org/?probe=16e64883d7) | Jan 24, 2023 |
| MSI           | MS-7817                     | Desktop     | [93d29f37d8](https://linux-hardware.org/?probe=93d29f37d8) | Jan 24, 2023 |
| MSI           | MS-7817                     | Desktop     | [db9c2416af](https://linux-hardware.org/?probe=db9c2416af) | Jan 24, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [39c54a5f09](https://linux-hardware.org/?probe=39c54a5f09) | Jan 24, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [123c1db6ac](https://linux-hardware.org/?probe=123c1db6ac) | Jan 23, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48ee4a3eef](https://linux-hardware.org/?probe=48ee4a3eef) | Jan 23, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [6727a94c5e](https://linux-hardware.org/?probe=6727a94c5e) | Jan 23, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b3e3fd8775](https://linux-hardware.org/?probe=b3e3fd8775) | Jan 23, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [561b2897e2](https://linux-hardware.org/?probe=561b2897e2) | Jan 23, 2023 |
| Acer          | RS880M05                    | Desktop     | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [00f2a52261](https://linux-hardware.org/?probe=00f2a52261) | Jan 22, 2023 |
| Gigabyte      | M52LT-D3                    | Desktop     | [b53ddd69a6](https://linux-hardware.org/?probe=b53ddd69a6) | Jan 22, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [dcecec2239](https://linux-hardware.org/?probe=dcecec2239) | Jan 22, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2851ee7994](https://linux-hardware.org/?probe=2851ee7994) | Jan 22, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [ae139e78a0](https://linux-hardware.org/?probe=ae139e78a0) | Jan 22, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [d43d26ff9f](https://linux-hardware.org/?probe=d43d26ff9f) | Jan 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [4584e904f8](https://linux-hardware.org/?probe=4584e904f8) | Jan 21, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [53fb561c53](https://linux-hardware.org/?probe=53fb561c53) | Jan 21, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [1abe984576](https://linux-hardware.org/?probe=1abe984576) | Jan 21, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e261893ec4](https://linux-hardware.org/?probe=e261893ec4) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0c77a64f45](https://linux-hardware.org/?probe=0c77a64f45) | Jan 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | Notebook    | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [221830de98](https://linux-hardware.org/?probe=221830de98) | Jan 17, 2023 |
| MSI           | MS-7817                     | Desktop     | [8eac0961cc](https://linux-hardware.org/?probe=8eac0961cc) | Jan 17, 2023 |
| MSI           | MS-7817                     | Desktop     | [14ae598595](https://linux-hardware.org/?probe=14ae598595) | Jan 17, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [3117124412](https://linux-hardware.org/?probe=3117124412) | Jan 16, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [61f16ccc60](https://linux-hardware.org/?probe=61f16ccc60) | Jan 15, 2023 |
| Acer          | TravelMate 8571             | Notebook    | [2933c64a6d](https://linux-hardware.org/?probe=2933c64a6d) | Jan 15, 2023 |
| Acer          | TravelMate 8571             | Notebook    | [ad01651917](https://linux-hardware.org/?probe=ad01651917) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [25f5800974](https://linux-hardware.org/?probe=25f5800974) | Jan 15, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [f1516ea54d](https://linux-hardware.org/?probe=f1516ea54d) | Jan 15, 2023 |
| Acer          | TravelMate B117-M           | Notebook    | [c760a021bf](https://linux-hardware.org/?probe=c760a021bf) | Jan 14, 2023 |
| Acer          | TravelMate B117-M           | Notebook    | [bee982f325](https://linux-hardware.org/?probe=bee982f325) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [1eb9f8fa55](https://linux-hardware.org/?probe=1eb9f8fa55) | Jan 14, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [79d2961429](https://linux-hardware.org/?probe=79d2961429) | Jan 14, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [798c78aaf7](https://linux-hardware.org/?probe=798c78aaf7) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c541b9f1cd](https://linux-hardware.org/?probe=c541b9f1cd) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Fujitsu       | LIFEBOOK T730               | Notebook    | [f9ba03526e](https://linux-hardware.org/?probe=f9ba03526e) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [61f80cd38a](https://linux-hardware.org/?probe=61f80cd38a) | Jan 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [8c2c6b3355](https://linux-hardware.org/?probe=8c2c6b3355) | Jan 13, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [10f4ae9765](https://linux-hardware.org/?probe=10f4ae9765) | Jan 12, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [48531d8e05](https://linux-hardware.org/?probe=48531d8e05) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [e3eb62db83](https://linux-hardware.org/?probe=e3eb62db83) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [b36d8e79ea](https://linux-hardware.org/?probe=b36d8e79ea) | Jan 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [47cd489d8b](https://linux-hardware.org/?probe=47cd489d8b) | Jan 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [80f84b2854](https://linux-hardware.org/?probe=80f84b2854) | Jan 11, 2023 |
| HP            | 8265                        | Desktop     | [ff276ee116](https://linux-hardware.org/?probe=ff276ee116) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [a941237bf3](https://linux-hardware.org/?probe=a941237bf3) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [9eebe49454](https://linux-hardware.org/?probe=9eebe49454) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [106e3d9073](https://linux-hardware.org/?probe=106e3d9073) | Jan 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [1ebf7a4a09](https://linux-hardware.org/?probe=1ebf7a4a09) | Jan 11, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [b1fb0a1f64](https://linux-hardware.org/?probe=b1fb0a1f64) | Jan 10, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [2baa58c11e](https://linux-hardware.org/?probe=2baa58c11e) | Jan 10, 2023 |
| HP            | 3032h                       | Desktop     | [1e729e9b75](https://linux-hardware.org/?probe=1e729e9b75) | Jan 09, 2023 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [07b77ef803](https://linux-hardware.org/?probe=07b77ef803) | Jan 09, 2023 |
| Lenovo        | ThinkCentre M58p 9728W47    | Desktop     | [cdf4eb72bb](https://linux-hardware.org/?probe=cdf4eb72bb) | Jan 09, 2023 |
| Acer          | A515-44G                    | Notebook    | [0589eb53fa](https://linux-hardware.org/?probe=0589eb53fa) | Jan 08, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [cfc6e0c455](https://linux-hardware.org/?probe=cfc6e0c455) | Jan 08, 2023 |
| VXL           | M6V90AI-VL                  | Desktop     | [1ad8dbaae1](https://linux-hardware.org/?probe=1ad8dbaae1) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [beef7a74d4](https://linux-hardware.org/?probe=beef7a74d4) | Jan 08, 2023 |
| HP            | ProBook 6570b               | Notebook    | [ac7eff1b5e](https://linux-hardware.org/?probe=ac7eff1b5e) | Jan 08, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [922b7a2305](https://linux-hardware.org/?probe=922b7a2305) | Jan 08, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [8866a21a4b](https://linux-hardware.org/?probe=8866a21a4b) | Jan 08, 2023 |
| HP            | ProBook 6570b               | Notebook    | [819a1c02df](https://linux-hardware.org/?probe=819a1c02df) | Jan 08, 2023 |
| HP            | 3029h                       | Desktop     | [8d20c516df](https://linux-hardware.org/?probe=8d20c516df) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [ffed123536](https://linux-hardware.org/?probe=ffed123536) | Jan 07, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f946892969](https://linux-hardware.org/?probe=f946892969) | Jan 07, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [daad153e9a](https://linux-hardware.org/?probe=daad153e9a) | Jan 06, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [7c62a0a238](https://linux-hardware.org/?probe=7c62a0a238) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [1473e6f0d9](https://linux-hardware.org/?probe=1473e6f0d9) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [74f479bd3e](https://linux-hardware.org/?probe=74f479bd3e) | Jan 06, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ca27e27e15](https://linux-hardware.org/?probe=ca27e27e15) | Jan 06, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [7535d6b22b](https://linux-hardware.org/?probe=7535d6b22b) | Jan 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [8b590c65fc](https://linux-hardware.org/?probe=8b590c65fc) | Jan 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [9a16949691](https://linux-hardware.org/?probe=9a16949691) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [b7119b52a7](https://linux-hardware.org/?probe=b7119b52a7) | Jan 05, 2023 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [b1132f1491](https://linux-hardware.org/?probe=b1132f1491) | Jan 04, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [30195a4ca0](https://linux-hardware.org/?probe=30195a4ca0) | Jan 04, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [2e29dd8142](https://linux-hardware.org/?probe=2e29dd8142) | Jan 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4247d8d8b0](https://linux-hardware.org/?probe=4247d8d8b0) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | Desktop     | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bd01380cb3](https://linux-hardware.org/?probe=bd01380cb3) | Jan 03, 2023 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [564a8cf5c2](https://linux-hardware.org/?probe=564a8cf5c2) | Jan 03, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cdb140b891](https://linux-hardware.org/?probe=cdb140b891) | Jan 03, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [42b1f8124d](https://linux-hardware.org/?probe=42b1f8124d) | Jan 03, 2023 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [7125f2d1da](https://linux-hardware.org/?probe=7125f2d1da) | Jan 02, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [8268625d25](https://linux-hardware.org/?probe=8268625d25) | Jan 02, 2023 |
| MSI           | MS-7817                     | Desktop     | [658352807e](https://linux-hardware.org/?probe=658352807e) | Jan 01, 2023 |
| MSI           | MS-7817                     | Desktop     | [135f56eb99](https://linux-hardware.org/?probe=135f56eb99) | Jan 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ed9ddacdce](https://linux-hardware.org/?probe=ed9ddacdce) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc19d2cf24](https://linux-hardware.org/?probe=cc19d2cf24) | Dec 31, 2022 |
| Lenovo        | ThinkCentre M58p 9728W47    | Desktop     | [68bc291efd](https://linux-hardware.org/?probe=68bc291efd) | Dec 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0f696a9b9](https://linux-hardware.org/?probe=e0f696a9b9) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| Dell          | G15 5520                    | Notebook    | [2e82f45fb6](https://linux-hardware.org/?probe=2e82f45fb6) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6c00206f7e](https://linux-hardware.org/?probe=6c00206f7e) | Dec 30, 2022 |
| Dell          | Latitude 5480               | Notebook    | [e02be15b45](https://linux-hardware.org/?probe=e02be15b45) | Dec 30, 2022 |
| Dell          | Latitude 5480               | Notebook    | [5afd8e73be](https://linux-hardware.org/?probe=5afd8e73be) | Dec 30, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [279718a62f](https://linux-hardware.org/?probe=279718a62f) | Dec 30, 2022 |
| Dell          | Latitude 5480               | Notebook    | [64aa4b9161](https://linux-hardware.org/?probe=64aa4b9161) | Dec 30, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [fd48487066](https://linux-hardware.org/?probe=fd48487066) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [199a8927b8](https://linux-hardware.org/?probe=199a8927b8) | Dec 29, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [012f398d07](https://linux-hardware.org/?probe=012f398d07) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [c286883155](https://linux-hardware.org/?probe=c286883155) | Dec 29, 2022 |
| Dell          | Latitude 5480               | Notebook    | [b578e196dd](https://linux-hardware.org/?probe=b578e196dd) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a8df3d8262](https://linux-hardware.org/?probe=a8df3d8262) | Dec 29, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a57d2f5ccb](https://linux-hardware.org/?probe=a57d2f5ccb) | Dec 29, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [11e78b0f9b](https://linux-hardware.org/?probe=11e78b0f9b) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [447852c33b](https://linux-hardware.org/?probe=447852c33b) | Dec 28, 2022 |
| Dell          | Latitude 5480               | Notebook    | [4b2fda33f4](https://linux-hardware.org/?probe=4b2fda33f4) | Dec 28, 2022 |
| Dell          | Latitude 5480               | Notebook    | [abcd3bea2f](https://linux-hardware.org/?probe=abcd3bea2f) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [5cbcee30c7](https://linux-hardware.org/?probe=5cbcee30c7) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [743ed4d93a](https://linux-hardware.org/?probe=743ed4d93a) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [819f9be803](https://linux-hardware.org/?probe=819f9be803) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ad4d919e36](https://linux-hardware.org/?probe=ad4d919e36) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [8b02482c16](https://linux-hardware.org/?probe=8b02482c16) | Dec 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [56ceb67978](https://linux-hardware.org/?probe=56ceb67978) | Dec 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [e44b069b44](https://linux-hardware.org/?probe=e44b069b44) | Dec 26, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [14611d6c99](https://linux-hardware.org/?probe=14611d6c99) | Dec 26, 2022 |
| HP            | Compaq 610                  | Notebook    | [198b4d0586](https://linux-hardware.org/?probe=198b4d0586) | Dec 25, 2022 |
| HP            | Compaq 610                  | Notebook    | [0e9ab46e66](https://linux-hardware.org/?probe=0e9ab46e66) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | Notebook    | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [3f022cb1a7](https://linux-hardware.org/?probe=3f022cb1a7) | Dec 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [7c5a7b9036](https://linux-hardware.org/?probe=7c5a7b9036) | Dec 24, 2022 |
| Dell          | 0PTTT9 A01                  | Desktop     | [4618f09759](https://linux-hardware.org/?probe=4618f09759) | Dec 23, 2022 |
| Dell          | Latitude 7490               | Notebook    | [d5223c073b](https://linux-hardware.org/?probe=d5223c073b) | Dec 23, 2022 |
| eMachines     | E725                        | Notebook    | [86939210d0](https://linux-hardware.org/?probe=86939210d0) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [7e77870894](https://linux-hardware.org/?probe=7e77870894) | Dec 21, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [04c205c943](https://linux-hardware.org/?probe=04c205c943) | Dec 21, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [95a82c6f4d](https://linux-hardware.org/?probe=95a82c6f4d) | Dec 19, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [3b2deb36cb](https://linux-hardware.org/?probe=3b2deb36cb) | Dec 19, 2022 |
| Dell          | Latitude E6230              | Notebook    | [80012cb415](https://linux-hardware.org/?probe=80012cb415) | Dec 19, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [6bfb0295df](https://linux-hardware.org/?probe=6bfb0295df) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT02    | Notebook    | [439cd38614](https://linux-hardware.org/?probe=439cd38614) | Dec 18, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [88fc771e47](https://linux-hardware.org/?probe=88fc771e47) | Dec 18, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [477947ea20](https://linux-hardware.org/?probe=477947ea20) | Dec 17, 2022 |
| Dell          | Latitude E6230              | Notebook    | [ba7fa25841](https://linux-hardware.org/?probe=ba7fa25841) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [265739601c](https://linux-hardware.org/?probe=265739601c) | Dec 16, 2022 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0ed9c8a241](https://linux-hardware.org/?probe=0ed9c8a241) | Dec 16, 2022 |
| HP            | 2215                        | Desktop     | [78151a5e1b](https://linux-hardware.org/?probe=78151a5e1b) | Dec 16, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [e350e12e7c](https://linux-hardware.org/?probe=e350e12e7c) | Dec 15, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [96929b34ef](https://linux-hardware.org/?probe=96929b34ef) | Dec 15, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| HP            | EliteBook 850 G4            | Notebook    | [0a2fc94b9a](https://linux-hardware.org/?probe=0a2fc94b9a) | Dec 14, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [fece9d45b4](https://linux-hardware.org/?probe=fece9d45b4) | Dec 14, 2022 |
| VXL           | M6V90AI-VL                  | Desktop     | [a16094bb41](https://linux-hardware.org/?probe=a16094bb41) | Dec 14, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a7c03c5bfd](https://linux-hardware.org/?probe=a7c03c5bfd) | Dec 14, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [42eef61903](https://linux-hardware.org/?probe=42eef61903) | Dec 14, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [0138a1b2d4](https://linux-hardware.org/?probe=0138a1b2d4) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [466ea5976d](https://linux-hardware.org/?probe=466ea5976d) | Dec 13, 2022 |
| ASUSTek       | GL10DH                      | Desktop     | [ca2fb9f1a2](https://linux-hardware.org/?probe=ca2fb9f1a2) | Dec 13, 2022 |
| ASUSTek       | GL10DH                      | Desktop     | [5c148c3a41](https://linux-hardware.org/?probe=5c148c3a41) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | Notebook    | [9dc9070ae6](https://linux-hardware.org/?probe=9dc9070ae6) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | Notebook    | [cf9f4d4a79](https://linux-hardware.org/?probe=cf9f4d4a79) | Dec 13, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [976923f807](https://linux-hardware.org/?probe=976923f807) | Dec 12, 2022 |
| Acer          | Extensa 5630                | Notebook    | [ec4f446d23](https://linux-hardware.org/?probe=ec4f446d23) | Dec 11, 2022 |
| Biostar       | A320MH                      | Desktop     | [31cc96d1d3](https://linux-hardware.org/?probe=31cc96d1d3) | Dec 11, 2022 |
| HP            | 1589                        | Desktop     | [4aa31e9d16](https://linux-hardware.org/?probe=4aa31e9d16) | Dec 11, 2022 |
| HP            | 8265                        | Desktop     | [da426053be](https://linux-hardware.org/?probe=da426053be) | Dec 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b7a944c773](https://linux-hardware.org/?probe=b7a944c773) | Dec 11, 2022 |
| HP            | 650                         | Notebook    | [add4ca69e3](https://linux-hardware.org/?probe=add4ca69e3) | Dec 11, 2022 |
| HP            | 650                         | Notebook    | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| Acer          | TravelMate 8571             | Notebook    | [63aa77ba8d](https://linux-hardware.org/?probe=63aa77ba8d) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [32870f2fa3](https://linux-hardware.org/?probe=32870f2fa3) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [fac8091847](https://linux-hardware.org/?probe=fac8091847) | Dec 10, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [eb1d437253](https://linux-hardware.org/?probe=eb1d437253) | Dec 10, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [2a7d96e2eb](https://linux-hardware.org/?probe=2a7d96e2eb) | Dec 10, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [afda77c820](https://linux-hardware.org/?probe=afda77c820) | Dec 10, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [94a6153aeb](https://linux-hardware.org/?probe=94a6153aeb) | Dec 09, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [1cb00c612b](https://linux-hardware.org/?probe=1cb00c612b) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9617825518](https://linux-hardware.org/?probe=9617825518) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [7b1075fd9b](https://linux-hardware.org/?probe=7b1075fd9b) | Dec 09, 2022 |
| Acer          | TravelMate 8571             | Notebook    | [89270d1f7c](https://linux-hardware.org/?probe=89270d1f7c) | Dec 08, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [177d3d8e16](https://linux-hardware.org/?probe=177d3d8e16) | Dec 08, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [f73021e3c7](https://linux-hardware.org/?probe=f73021e3c7) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [66433bdc5e](https://linux-hardware.org/?probe=66433bdc5e) | Dec 07, 2022 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [dfe2221b21](https://linux-hardware.org/?probe=dfe2221b21) | Dec 06, 2022 |
| Acer          | TravelMate 8571             | Notebook    | [9e7f0672b2](https://linux-hardware.org/?probe=9e7f0672b2) | Dec 06, 2022 |
| Lenovo        | ThinkPad T470 20HES0E71M    | Notebook    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [639497d7e0](https://linux-hardware.org/?probe=639497d7e0) | Dec 05, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6a477d4759](https://linux-hardware.org/?probe=6a477d4759) | Dec 05, 2022 |
| Lenovo        | Tilapia CRB                 | Desktop     | [a32aaf0f8c](https://linux-hardware.org/?probe=a32aaf0f8c) | Dec 05, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [cdd460e503](https://linux-hardware.org/?probe=cdd460e503) | Dec 04, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f8e5635371](https://linux-hardware.org/?probe=f8e5635371) | Dec 04, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [264d0d02bb](https://linux-hardware.org/?probe=264d0d02bb) | Dec 04, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [6136553624](https://linux-hardware.org/?probe=6136553624) | Dec 03, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [9ac464aa29](https://linux-hardware.org/?probe=9ac464aa29) | Dec 03, 2022 |
| Acer          | TravelMate 8571             | Notebook    | [df032cacb6](https://linux-hardware.org/?probe=df032cacb6) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [32dbbbf380](https://linux-hardware.org/?probe=32dbbbf380) | Dec 03, 2022 |
| Dell          | Latitude E6220              | Notebook    | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5e58cb10a5](https://linux-hardware.org/?probe=5e58cb10a5) | Dec 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [81315b2876](https://linux-hardware.org/?probe=81315b2876) | Dec 02, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [de19b92dda](https://linux-hardware.org/?probe=de19b92dda) | Nov 30, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [76b79932d5](https://linux-hardware.org/?probe=76b79932d5) | Nov 29, 2022 |
| MSI           | D2414 S26361-D2414-A10      | Desktop     | [ef1367a574](https://linux-hardware.org/?probe=ef1367a574) | Nov 29, 2022 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [6d835027fa](https://linux-hardware.org/?probe=6d835027fa) | Nov 29, 2022 |
| Dell          | Latitude E5520              | Notebook    | [1b3b69b19f](https://linux-hardware.org/?probe=1b3b69b19f) | Nov 28, 2022 |
| MSI           | MS-7817                     | Desktop     | [3a740dd46a](https://linux-hardware.org/?probe=3a740dd46a) | Nov 28, 2022 |
| MSI           | MS-7817                     | Desktop     | [48ae0e1997](https://linux-hardware.org/?probe=48ae0e1997) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c56c5e5a10](https://linux-hardware.org/?probe=c56c5e5a10) | Nov 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e853b09dfa](https://linux-hardware.org/?probe=e853b09dfa) | Nov 28, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [550b448753](https://linux-hardware.org/?probe=550b448753) | Nov 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [cd9478ab62](https://linux-hardware.org/?probe=cd9478ab62) | Nov 26, 2022 |
| Dell          | Latitude E5520              | Notebook    | [ce72f1c2a9](https://linux-hardware.org/?probe=ce72f1c2a9) | Nov 25, 2022 |
| HP            | 650                         | Notebook    | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| Dell          | Latitude E6540              | Notebook    | [5c474a2cdb](https://linux-hardware.org/?probe=5c474a2cdb) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [03d5c6e735](https://linux-hardware.org/?probe=03d5c6e735) | Nov 23, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [93dc021b03](https://linux-hardware.org/?probe=93dc021b03) | Nov 23, 2022 |
| HP            | Compaq 6720s                | Notebook    | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [ac5deb8230](https://linux-hardware.org/?probe=ac5deb8230) | Nov 22, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [ffc3ff8f31](https://linux-hardware.org/?probe=ffc3ff8f31) | Nov 22, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [fd41589a1a](https://linux-hardware.org/?probe=fd41589a1a) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [62b0cb4c94](https://linux-hardware.org/?probe=62b0cb4c94) | Nov 22, 2022 |
| ASUSTek       | Maximus VI GENE             | Desktop     | [26e7d04331](https://linux-hardware.org/?probe=26e7d04331) | Nov 22, 2022 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [f01dec11e4](https://linux-hardware.org/?probe=f01dec11e4) | Nov 21, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [855f11c57b](https://linux-hardware.org/?probe=855f11c57b) | Nov 21, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [be2c23e33c](https://linux-hardware.org/?probe=be2c23e33c) | Nov 21, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [b963fb74e2](https://linux-hardware.org/?probe=b963fb74e2) | Nov 21, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [34f72bd414](https://linux-hardware.org/?probe=34f72bd414) | Nov 20, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [4de72c5631](https://linux-hardware.org/?probe=4de72c5631) | Nov 20, 2022 |
| MSI           | MS-7817                     | Desktop     | [b2c48fde2c](https://linux-hardware.org/?probe=b2c48fde2c) | Nov 20, 2022 |
| MSI           | MS-7817                     | Desktop     | [ffc17a7303](https://linux-hardware.org/?probe=ffc17a7303) | Nov 20, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [4db9e36520](https://linux-hardware.org/?probe=4db9e36520) | Nov 20, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [716649aa59](https://linux-hardware.org/?probe=716649aa59) | Nov 20, 2022 |
| HP            | Pro x2 612 G2               | Tablet      | [6c49fe9d07](https://linux-hardware.org/?probe=6c49fe9d07) | Nov 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd6f589d44](https://linux-hardware.org/?probe=dd6f589d44) | Nov 20, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [fd460bcba6](https://linux-hardware.org/?probe=fd460bcba6) | Nov 18, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [943027284b](https://linux-hardware.org/?probe=943027284b) | Nov 17, 2022 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [3e906bb29a](https://linux-hardware.org/?probe=3e906bb29a) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [9fe9bc94a0](https://linux-hardware.org/?probe=9fe9bc94a0) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | Notebook    | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| HP            | Unknown                     | Notebook    | [f76118ac5f](https://linux-hardware.org/?probe=f76118ac5f) | Nov 13, 2022 |
| HP            | Unknown                     | Notebook    | [8cd95516d0](https://linux-hardware.org/?probe=8cd95516d0) | Nov 13, 2022 |
| HP            | 650                         | Notebook    | [100707d1eb](https://linux-hardware.org/?probe=100707d1eb) | Nov 13, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [e7820d3dfb](https://linux-hardware.org/?probe=e7820d3dfb) | Nov 13, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [be50b73bfe](https://linux-hardware.org/?probe=be50b73bfe) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [affbec4acb](https://linux-hardware.org/?probe=affbec4acb) | Nov 12, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [11bffbe5e4](https://linux-hardware.org/?probe=11bffbe5e4) | Nov 12, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [9ed32f5227](https://linux-hardware.org/?probe=9ed32f5227) | Nov 12, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [99a2e00654](https://linux-hardware.org/?probe=99a2e00654) | Nov 11, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [a697dc0e99](https://linux-hardware.org/?probe=a697dc0e99) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [718971a0f8](https://linux-hardware.org/?probe=718971a0f8) | Nov 11, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [b0f1fc9e0f](https://linux-hardware.org/?probe=b0f1fc9e0f) | Nov 11, 2022 |
| Lenovo        | ThinkCentre M58p 9728W47    | Desktop     | [48e81f1349](https://linux-hardware.org/?probe=48e81f1349) | Nov 10, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [1af38f67c6](https://linux-hardware.org/?probe=1af38f67c6) | Nov 10, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [7a41c26bea](https://linux-hardware.org/?probe=7a41c26bea) | Nov 09, 2022 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [36b3c3d634](https://linux-hardware.org/?probe=36b3c3d634) | Nov 09, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [8f4c16021c](https://linux-hardware.org/?probe=8f4c16021c) | Nov 09, 2022 |
| HP            | 625                         | Notebook    | [2d8090e61e](https://linux-hardware.org/?probe=2d8090e61e) | Nov 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [010a383efa](https://linux-hardware.org/?probe=010a383efa) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| ASUSTek       | F5V                         | Notebook    | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [a5492a9260](https://linux-hardware.org/?probe=a5492a9260) | Nov 07, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [e1a81edea7](https://linux-hardware.org/?probe=e1a81edea7) | Nov 05, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [52c7829518](https://linux-hardware.org/?probe=52c7829518) | Nov 05, 2022 |
| HP            | 650                         | Notebook    | [fd3b93e8fb](https://linux-hardware.org/?probe=fd3b93e8fb) | Nov 05, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [a9bb64111f](https://linux-hardware.org/?probe=a9bb64111f) | Nov 05, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [d5125861d0](https://linux-hardware.org/?probe=d5125861d0) | Nov 03, 2022 |
| Dell          | Latitude E7250              | Notebook    | [0c36cbc6ca](https://linux-hardware.org/?probe=0c36cbc6ca) | Nov 03, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [0a598dc332](https://linux-hardware.org/?probe=0a598dc332) | Nov 02, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [41707b16d1](https://linux-hardware.org/?probe=41707b16d1) | Nov 02, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| Dell          | G5 5587                     | Notebook    | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [cf394ed108](https://linux-hardware.org/?probe=cf394ed108) | Nov 01, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [446799aa8e](https://linux-hardware.org/?probe=446799aa8e) | Nov 01, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [183545ed4e](https://linux-hardware.org/?probe=183545ed4e) | Oct 31, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [e49d4af683](https://linux-hardware.org/?probe=e49d4af683) | Oct 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [416655ce7d](https://linux-hardware.org/?probe=416655ce7d) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [ae71fe1a19](https://linux-hardware.org/?probe=ae71fe1a19) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [52a6d45e82](https://linux-hardware.org/?probe=52a6d45e82) | Oct 29, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [f352df76ef](https://linux-hardware.org/?probe=f352df76ef) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | Notebook    | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [3b67700f14](https://linux-hardware.org/?probe=3b67700f14) | Oct 28, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [a80d2e7626](https://linux-hardware.org/?probe=a80d2e7626) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [7cb792e432](https://linux-hardware.org/?probe=7cb792e432) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0c33d71210](https://linux-hardware.org/?probe=0c33d71210) | Oct 27, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [4be40e9739](https://linux-hardware.org/?probe=4be40e9739) | Oct 27, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [fc26c82789](https://linux-hardware.org/?probe=fc26c82789) | Oct 27, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [acdfb9b02e](https://linux-hardware.org/?probe=acdfb9b02e) | Oct 26, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [eac363d110](https://linux-hardware.org/?probe=eac363d110) | Oct 25, 2022 |
| ALLDOCUBE     | i1402A                      | Notebook    | [22c255e8cd](https://linux-hardware.org/?probe=22c255e8cd) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [df16ec68c3](https://linux-hardware.org/?probe=df16ec68c3) | Oct 24, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [996a5a3b8d](https://linux-hardware.org/?probe=996a5a3b8d) | Oct 24, 2022 |
| HP            | Compaq 6910p (GH717AW#AB... | Notebook    | [02d31506a2](https://linux-hardware.org/?probe=02d31506a2) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Latitude E6230              | Notebook    | [73ee8be4e9](https://linux-hardware.org/?probe=73ee8be4e9) | Oct 23, 2022 |
| Dell          | Latitude E6230              | Notebook    | [52ee15a8f5](https://linux-hardware.org/?probe=52ee15a8f5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [1ad0ed065f](https://linux-hardware.org/?probe=1ad0ed065f) | Oct 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [238c40d2e4](https://linux-hardware.org/?probe=238c40d2e4) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | Notebook    | [eb7940e5a4](https://linux-hardware.org/?probe=eb7940e5a4) | Oct 19, 2022 |
| eMachines     | E725                        | Notebook    | [ea21ca2d78](https://linux-hardware.org/?probe=ea21ca2d78) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | Notebook    | [098e362854](https://linux-hardware.org/?probe=098e362854) | Oct 19, 2022 |
| eMachines     | E725                        | Notebook    | [6d5ddca6c9](https://linux-hardware.org/?probe=6d5ddca6c9) | Oct 18, 2022 |
| Lenovo        | ThinkPad T490 20N2S29E00    | Notebook    | [dd61a6ea26](https://linux-hardware.org/?probe=dd61a6ea26) | Oct 18, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Acer          | Aspire A717-71G             | Notebook    | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| eMachines     | E725                        | Notebook    | [f365f1eaa7](https://linux-hardware.org/?probe=f365f1eaa7) | Oct 17, 2022 |
| eMachines     | E725                        | Notebook    | [7003528b88](https://linux-hardware.org/?probe=7003528b88) | Oct 17, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [a49ebeea02](https://linux-hardware.org/?probe=a49ebeea02) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [4ab8d609e7](https://linux-hardware.org/?probe=4ab8d609e7) | Oct 16, 2022 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c1b258565](https://linux-hardware.org/?probe=8c1b258565) | Oct 16, 2022 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [bfbf006040](https://linux-hardware.org/?probe=bfbf006040) | Oct 16, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [8781d340f7](https://linux-hardware.org/?probe=8781d340f7) | Oct 16, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [a0c85cb9ab](https://linux-hardware.org/?probe=a0c85cb9ab) | Oct 15, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [365f1a9123](https://linux-hardware.org/?probe=365f1a9123) | Oct 15, 2022 |
| Fujitsu       | D3313-S4 S26361-D3313-S4    | Desktop     | [e92144b22a](https://linux-hardware.org/?probe=e92144b22a) | Oct 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [07a141abbb](https://linux-hardware.org/?probe=07a141abbb) | Oct 14, 2022 |
| eMachines     | E725                        | Notebook    | [77e7244d88](https://linux-hardware.org/?probe=77e7244d88) | Oct 14, 2022 |
| eMachines     | E725                        | Notebook    | [34538c32c5](https://linux-hardware.org/?probe=34538c32c5) | Oct 14, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [b36e579d37](https://linux-hardware.org/?probe=b36e579d37) | Oct 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [0d8c24c367](https://linux-hardware.org/?probe=0d8c24c367) | Oct 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [9743b0896c](https://linux-hardware.org/?probe=9743b0896c) | Oct 13, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [3ba623cebe](https://linux-hardware.org/?probe=3ba623cebe) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [ec470df515](https://linux-hardware.org/?probe=ec470df515) | Oct 11, 2022 |
| Dell          | Latitude 5410               | Notebook    | [e468acae5c](https://linux-hardware.org/?probe=e468acae5c) | Oct 11, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [e5720c01a5](https://linux-hardware.org/?probe=e5720c01a5) | Oct 10, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | Notebook    | [dc933df0a9](https://linux-hardware.org/?probe=dc933df0a9) | Oct 10, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [000e5389a8](https://linux-hardware.org/?probe=000e5389a8) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [63a8f1baa1](https://linux-hardware.org/?probe=63a8f1baa1) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [7f9e9ab40b](https://linux-hardware.org/?probe=7f9e9ab40b) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Dell          | 003KPJ A00                  | Desktop     | [e151f6645b](https://linux-hardware.org/?probe=e151f6645b) | Oct 08, 2022 |
| ASUSTek       | F3Sv                        | Notebook    | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [91163f885b](https://linux-hardware.org/?probe=91163f885b) | Oct 07, 2022 |
| HP            | 3047h                       | Desktop     | [b29b0b1ef4](https://linux-hardware.org/?probe=b29b0b1ef4) | Oct 07, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [c7ae238295](https://linux-hardware.org/?probe=c7ae238295) | Oct 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | Notebook    | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [7f186dfabd](https://linux-hardware.org/?probe=7f186dfabd) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [6bae0e4f18](https://linux-hardware.org/?probe=6bae0e4f18) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f19e278e43](https://linux-hardware.org/?probe=f19e278e43) | Oct 06, 2022 |
| eMachines     | E725                        | Notebook    | [9a77e04f3c](https://linux-hardware.org/?probe=9a77e04f3c) | Oct 05, 2022 |
| eMachines     | E725                        | Notebook    | [e413d82fa5](https://linux-hardware.org/?probe=e413d82fa5) | Oct 05, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [33e28ce993](https://linux-hardware.org/?probe=33e28ce993) | Oct 05, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [73c9f25932](https://linux-hardware.org/?probe=73c9f25932) | Oct 04, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [3a515cdda0](https://linux-hardware.org/?probe=3a515cdda0) | Oct 03, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Toshiba       | Satellite M50D-A            | Notebook    | [6eaada1ab0](https://linux-hardware.org/?probe=6eaada1ab0) | Oct 03, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | Notebook    | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7bb0235bd2](https://linux-hardware.org/?probe=7bb0235bd2) | Oct 03, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [1031dfcd50](https://linux-hardware.org/?probe=1031dfcd50) | Oct 03, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [0b1bf36485](https://linux-hardware.org/?probe=0b1bf36485) | Oct 02, 2022 |
| Dell          | Latitude D630               | Notebook    | [90dc2dddf8](https://linux-hardware.org/?probe=90dc2dddf8) | Oct 02, 2022 |
| AZW           | GTR V01                     | Mini pc     | [40c181376b](https://linux-hardware.org/?probe=40c181376b) | Oct 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [4638cc7f7b](https://linux-hardware.org/?probe=4638cc7f7b) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | Notebook    | [48dd8fb419](https://linux-hardware.org/?probe=48dd8fb419) | Oct 01, 2022 |
| Dell          | Latitude D630               | Notebook    | [d00c756052](https://linux-hardware.org/?probe=d00c756052) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | Notebook    | [75e6dbe3d2](https://linux-hardware.org/?probe=75e6dbe3d2) | Oct 01, 2022 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [e48bab666f](https://linux-hardware.org/?probe=e48bab666f) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | Notebook    | [0e0ca26d00](https://linux-hardware.org/?probe=0e0ca26d00) | Sep 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [1b2683c634](https://linux-hardware.org/?probe=1b2683c634) | Sep 30, 2022 |
| Sony          | SVS13118GBB                 | Notebook    | [12868cf90f](https://linux-hardware.org/?probe=12868cf90f) | Sep 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8762386a2b](https://linux-hardware.org/?probe=8762386a2b) | Sep 30, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [1ff8e037f4](https://linux-hardware.org/?probe=1ff8e037f4) | Sep 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a55d68e93c](https://linux-hardware.org/?probe=a55d68e93c) | Sep 30, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [8b7e129d4a](https://linux-hardware.org/?probe=8b7e129d4a) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65f56cc48b](https://linux-hardware.org/?probe=65f56cc48b) | Sep 29, 2022 |
| HP            | 3047h                       | Desktop     | [9426ee3f59](https://linux-hardware.org/?probe=9426ee3f59) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | Notebook    | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| eMachines     | E725                        | Notebook    | [04c9a24d86](https://linux-hardware.org/?probe=04c9a24d86) | Sep 28, 2022 |
| eMachines     | E725                        | Notebook    | [f99f2244c7](https://linux-hardware.org/?probe=f99f2244c7) | Sep 28, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [b7d37d0c6f](https://linux-hardware.org/?probe=b7d37d0c6f) | Sep 27, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [90856d2122](https://linux-hardware.org/?probe=90856d2122) | Sep 27, 2022 |
| ASUSTek       | 1015BX                      | Notebook    | [5190c360db](https://linux-hardware.org/?probe=5190c360db) | Sep 25, 2022 |
| HP            | 650                         | Notebook    | [f835e52a64](https://linux-hardware.org/?probe=f835e52a64) | Sep 25, 2022 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [9ff56b2438](https://linux-hardware.org/?probe=9ff56b2438) | Sep 24, 2022 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [3ba342d57a](https://linux-hardware.org/?probe=3ba342d57a) | Sep 24, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | Notebook    | [fc7831b371](https://linux-hardware.org/?probe=fc7831b371) | Sep 23, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | Notebook    | [15cffbb03b](https://linux-hardware.org/?probe=15cffbb03b) | Sep 23, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [b28077e806](https://linux-hardware.org/?probe=b28077e806) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0570d2318c](https://linux-hardware.org/?probe=0570d2318c) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [dbf0f3b1c8](https://linux-hardware.org/?probe=dbf0f3b1c8) | Sep 21, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [25fd2ae90c](https://linux-hardware.org/?probe=25fd2ae90c) | Sep 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d62d1ed9fd](https://linux-hardware.org/?probe=d62d1ed9fd) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [17945ad430](https://linux-hardware.org/?probe=17945ad430) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [49c7f8f204](https://linux-hardware.org/?probe=49c7f8f204) | Sep 21, 2022 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [5cf5ac2512](https://linux-hardware.org/?probe=5cf5ac2512) | Sep 21, 2022 |
| Toshiba       | Satellite L450              | Notebook    | [20b85987c4](https://linux-hardware.org/?probe=20b85987c4) | Sep 20, 2022 |
| Toshiba       | Satellite L450              | Notebook    | [9f694612d3](https://linux-hardware.org/?probe=9f694612d3) | Sep 20, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [16d313fefa](https://linux-hardware.org/?probe=16d313fefa) | Sep 20, 2022 |
| eMachines     | E725                        | Notebook    | [141723a3e2](https://linux-hardware.org/?probe=141723a3e2) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| eMachines     | E725                        | Notebook    | [bf27205286](https://linux-hardware.org/?probe=bf27205286) | Sep 15, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [15c9bd2a8a](https://linux-hardware.org/?probe=15c9bd2a8a) | Sep 15, 2022 |
| Acer          | Aspire 5310                 | Notebook    | [963a5bcade](https://linux-hardware.org/?probe=963a5bcade) | Sep 15, 2022 |
| Dell          | Latitude 7480               | Notebook    | [a9432965f4](https://linux-hardware.org/?probe=a9432965f4) | Sep 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [84bfb7d319](https://linux-hardware.org/?probe=84bfb7d319) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [9fcc670422](https://linux-hardware.org/?probe=9fcc670422) | Sep 15, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [10c83deaa9](https://linux-hardware.org/?probe=10c83deaa9) | Sep 15, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [4b6fca3ab4](https://linux-hardware.org/?probe=4b6fca3ab4) | Sep 15, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8366bd494c](https://linux-hardware.org/?probe=8366bd494c) | Sep 14, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [98422dda65](https://linux-hardware.org/?probe=98422dda65) | Sep 14, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [161958a208](https://linux-hardware.org/?probe=161958a208) | Sep 14, 2022 |
| HP            | 3648h                       | Desktop     | [8ed24fd9d4](https://linux-hardware.org/?probe=8ed24fd9d4) | Sep 13, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [4a7057f627](https://linux-hardware.org/?probe=4a7057f627) | Sep 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b251a95678](https://linux-hardware.org/?probe=b251a95678) | Sep 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b3c2018879](https://linux-hardware.org/?probe=b3c2018879) | Sep 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f10e559655](https://linux-hardware.org/?probe=f10e559655) | Sep 11, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [cf028f9b8c](https://linux-hardware.org/?probe=cf028f9b8c) | Sep 10, 2022 |
| HP            | 3396                        | Desktop     | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [eba0d1ad0c](https://linux-hardware.org/?probe=eba0d1ad0c) | Sep 09, 2022 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [080ffe37b9](https://linux-hardware.org/?probe=080ffe37b9) | Sep 08, 2022 |
| HP            | 18E4                        | Desktop     | [1e8addf905](https://linux-hardware.org/?probe=1e8addf905) | Sep 08, 2022 |
| Dell          | Latitude E6230              | Notebook    | [41c1130440](https://linux-hardware.org/?probe=41c1130440) | Sep 07, 2022 |
| Dell          | Latitude E6230              | Notebook    | [5e0436a64a](https://linux-hardware.org/?probe=5e0436a64a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [32715c6eb9](https://linux-hardware.org/?probe=32715c6eb9) | Sep 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [cbc35f08cb](https://linux-hardware.org/?probe=cbc35f08cb) | Sep 06, 2022 |
| HP            | 805D                        | Desktop     | [fdf50a9e36](https://linux-hardware.org/?probe=fdf50a9e36) | Sep 05, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [8c34a6ec8c](https://linux-hardware.org/?probe=8c34a6ec8c) | Sep 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Mediacom      | GTZS                        | Notebook    | [d62a43f91e](https://linux-hardware.org/?probe=d62a43f91e) | Sep 04, 2022 |
| HP            | 650                         | Notebook    | [526b86a559](https://linux-hardware.org/?probe=526b86a559) | Sep 04, 2022 |
| HP            | 650                         | Notebook    | [6f184e96df](https://linux-hardware.org/?probe=6f184e96df) | Sep 04, 2022 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [5b0da32c82](https://linux-hardware.org/?probe=5b0da32c82) | Sep 03, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cfd7da775](https://linux-hardware.org/?probe=7cfd7da775) | Sep 03, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2dbc615641](https://linux-hardware.org/?probe=2dbc615641) | Sep 02, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6552f796e2](https://linux-hardware.org/?probe=6552f796e2) | Sep 01, 2022 |
| HP            | 1589                        | Desktop     | [fce9004571](https://linux-hardware.org/?probe=fce9004571) | Sep 01, 2022 |
| ASUSTek       | V-M3N8200                   | Desktop     | [f593540c1c](https://linux-hardware.org/?probe=f593540c1c) | Sep 01, 2022 |
| ASUSTek       | V-M3N8200                   | Desktop     | [f3cc0c0bd5](https://linux-hardware.org/?probe=f3cc0c0bd5) | Sep 01, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [26d60edae6](https://linux-hardware.org/?probe=26d60edae6) | Aug 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e6d572c33](https://linux-hardware.org/?probe=2e6d572c33) | Aug 30, 2022 |
| eMachines     | E725                        | Notebook    | [3e5c01d133](https://linux-hardware.org/?probe=3e5c01d133) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [1dd156b433](https://linux-hardware.org/?probe=1dd156b433) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | Notebook    | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | Notebook    | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [aa28bc2c61](https://linux-hardware.org/?probe=aa28bc2c61) | Aug 26, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [aa633e1f74](https://linux-hardware.org/?probe=aa633e1f74) | Aug 26, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [34492f12b7](https://linux-hardware.org/?probe=34492f12b7) | Aug 26, 2022 |
| eMachines     | E725                        | Notebook    | [b73baa0850](https://linux-hardware.org/?probe=b73baa0850) | Aug 25, 2022 |
| ASUSTek       | A7N8X2.0                    | Desktop     | [f063b3e61a](https://linux-hardware.org/?probe=f063b3e61a) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [421ab76c43](https://linux-hardware.org/?probe=421ab76c43) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c7d603acb8](https://linux-hardware.org/?probe=c7d603acb8) | Aug 24, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | Notebook    | [be0227ed47](https://linux-hardware.org/?probe=be0227ed47) | Aug 23, 2022 |
| ASUSTek       | A7N8X2.0                    | Desktop     | [56416fa002](https://linux-hardware.org/?probe=56416fa002) | Aug 23, 2022 |
| Dell          | Latitude D630               | Notebook    | [be9c4025cb](https://linux-hardware.org/?probe=be9c4025cb) | Aug 23, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [88bb92c310](https://linux-hardware.org/?probe=88bb92c310) | Aug 22, 2022 |
| Shuttle       | FS81                        | Desktop     | [4c3be1b1a6](https://linux-hardware.org/?probe=4c3be1b1a6) | Aug 21, 2022 |
| ASUSTek       | 1015BX                      | Notebook    | [94f3284833](https://linux-hardware.org/?probe=94f3284833) | Aug 21, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| HP            | 620                         | Notebook    | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| Lenovo        | ThinkPad X220 4290L39       | Notebook    | [31a7893b95](https://linux-hardware.org/?probe=31a7893b95) | Aug 20, 2022 |
| HP            | 620                         | Notebook    | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| Dell          | Latitude 5580               | Notebook    | [5c9db9ff58](https://linux-hardware.org/?probe=5c9db9ff58) | Aug 18, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1a392021c7](https://linux-hardware.org/?probe=1a392021c7) | Aug 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3c18536e95](https://linux-hardware.org/?probe=3c18536e95) | Aug 18, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9003287b49](https://linux-hardware.org/?probe=9003287b49) | Aug 17, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [c51689de69](https://linux-hardware.org/?probe=c51689de69) | Aug 16, 2022 |
| Dell          | Latitude 5420               | Notebook    | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6649d66a82](https://linux-hardware.org/?probe=6649d66a82) | Aug 15, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [3bdf8d4582](https://linux-hardware.org/?probe=3bdf8d4582) | Aug 14, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [132a476896](https://linux-hardware.org/?probe=132a476896) | Aug 14, 2022 |
| eMachines     | E725                        | Notebook    | [928cfd8881](https://linux-hardware.org/?probe=928cfd8881) | Aug 13, 2022 |
| eMachines     | E725                        | Notebook    | [e1d0d38a1c](https://linux-hardware.org/?probe=e1d0d38a1c) | Aug 13, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [507fa4d8dc](https://linux-hardware.org/?probe=507fa4d8dc) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [1d7c1c5212](https://linux-hardware.org/?probe=1d7c1c5212) | Aug 13, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [bc105e1507](https://linux-hardware.org/?probe=bc105e1507) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [70b0d2bb45](https://linux-hardware.org/?probe=70b0d2bb45) | Aug 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| HP            | 1589                        | Desktop     | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| Intel         | NUC7JYB J67967-405          | Mini pc     | [06fdb19375](https://linux-hardware.org/?probe=06fdb19375) | Aug 08, 2022 |
| Dell          | Latitude E7450              | Notebook    | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7b8b4b5616](https://linux-hardware.org/?probe=7b8b4b5616) | Aug 08, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [e778ebd72b](https://linux-hardware.org/?probe=e778ebd72b) | Aug 08, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [01e6e21efb](https://linux-hardware.org/?probe=01e6e21efb) | Aug 06, 2022 |
| eMachines     | E520 V1.10                  | Notebook    | [a5c7ca58d9](https://linux-hardware.org/?probe=a5c7ca58d9) | Aug 06, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2ac3b9a2f1](https://linux-hardware.org/?probe=2ac3b9a2f1) | Aug 06, 2022 |
| Dell          | Precision 7530              | Notebook    | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [c6d5fcceee](https://linux-hardware.org/?probe=c6d5fcceee) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0e067ccc56](https://linux-hardware.org/?probe=0e067ccc56) | Aug 05, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [687f213628](https://linux-hardware.org/?probe=687f213628) | Aug 05, 2022 |
| eMachines     | E725                        | Notebook    | [8028786618](https://linux-hardware.org/?probe=8028786618) | Aug 04, 2022 |
| HP            | Notebook                    | Notebook    | [81b05860ab](https://linux-hardware.org/?probe=81b05860ab) | Aug 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [3e5f261f2a](https://linux-hardware.org/?probe=3e5f261f2a) | Aug 04, 2022 |
| HP            | 1589                        | Desktop     | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| HP            | 625                         | Notebook    | [1c59a9a3d3](https://linux-hardware.org/?probe=1c59a9a3d3) | Aug 03, 2022 |
| HP            | 625                         | Notebook    | [02db8f5852](https://linux-hardware.org/?probe=02db8f5852) | Aug 03, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [469c737a9b](https://linux-hardware.org/?probe=469c737a9b) | Aug 03, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [566648ca6d](https://linux-hardware.org/?probe=566648ca6d) | Aug 02, 2022 |
| eMachines     | E725                        | Notebook    | [fe35b6624b](https://linux-hardware.org/?probe=fe35b6624b) | Aug 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [77990d76cc](https://linux-hardware.org/?probe=77990d76cc) | Aug 02, 2022 |
| eMachines     | E725                        | Notebook    | [25d51b3945](https://linux-hardware.org/?probe=25d51b3945) | Aug 02, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [edf8c765aa](https://linux-hardware.org/?probe=edf8c765aa) | Aug 02, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [a446c446ae](https://linux-hardware.org/?probe=a446c446ae) | Aug 02, 2022 |
| eMachines     | E520 V1.10                  | Notebook    | [bb16305e18](https://linux-hardware.org/?probe=bb16305e18) | Aug 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [a1d5593420](https://linux-hardware.org/?probe=a1d5593420) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [5bb2e2b3e9](https://linux-hardware.org/?probe=5bb2e2b3e9) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0cecb854f4](https://linux-hardware.org/?probe=0cecb854f4) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [0645ed0b9e](https://linux-hardware.org/?probe=0645ed0b9e) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [f5e17ecf3d](https://linux-hardware.org/?probe=f5e17ecf3d) | Jul 31, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [a6889e4564](https://linux-hardware.org/?probe=a6889e4564) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [5e73e33a77](https://linux-hardware.org/?probe=5e73e33a77) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [43d1d3ae24](https://linux-hardware.org/?probe=43d1d3ae24) | Jul 30, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [9cb3ed38a5](https://linux-hardware.org/?probe=9cb3ed38a5) | Jul 30, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [0f83741c2e](https://linux-hardware.org/?probe=0f83741c2e) | Jul 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [aa6ae1c12f](https://linux-hardware.org/?probe=aa6ae1c12f) | Jul 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [6d72261de7](https://linux-hardware.org/?probe=6d72261de7) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [ea545ae9ed](https://linux-hardware.org/?probe=ea545ae9ed) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [44f505647d](https://linux-hardware.org/?probe=44f505647d) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | 8158 A01                    | Mini pc     | [56631cd6ac](https://linux-hardware.org/?probe=56631cd6ac) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [9194a07c08](https://linux-hardware.org/?probe=9194a07c08) | Jul 28, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [323db48d16](https://linux-hardware.org/?probe=323db48d16) | Jul 27, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [be2f2c9f98](https://linux-hardware.org/?probe=be2f2c9f98) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| eMachines     | E725                        | Notebook    | [ca033cf053](https://linux-hardware.org/?probe=ca033cf053) | Jul 26, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [1aa1f63a2d](https://linux-hardware.org/?probe=1aa1f63a2d) | Jul 25, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [06fd282e9d](https://linux-hardware.org/?probe=06fd282e9d) | Jul 25, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [81e755d9a1](https://linux-hardware.org/?probe=81e755d9a1) | Jul 25, 2022 |
| eMachines     | E725                        | Notebook    | [b975298e85](https://linux-hardware.org/?probe=b975298e85) | Jul 25, 2022 |
| Dell          | 054KM3 A00                  | Desktop     | [f84c50a2ae](https://linux-hardware.org/?probe=f84c50a2ae) | Jul 25, 2022 |
| Dell          | 054KM3 A00                  | Desktop     | [37fc6a278e](https://linux-hardware.org/?probe=37fc6a278e) | Jul 25, 2022 |
| Alcor         | Intel Education Tablet      | Notebook    | [a04ad41c5a](https://linux-hardware.org/?probe=a04ad41c5a) | Jul 24, 2022 |
| Alcor         | Intel Education Tablet      | Notebook    | [700f83a555](https://linux-hardware.org/?probe=700f83a555) | Jul 24, 2022 |
| Dell          | Latitude D630               | Notebook    | [a9fc5a41aa](https://linux-hardware.org/?probe=a9fc5a41aa) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [50e201ffd2](https://linux-hardware.org/?probe=50e201ffd2) | Jul 24, 2022 |
| Dell          | Latitude D630               | Notebook    | [7476af3363](https://linux-hardware.org/?probe=7476af3363) | Jul 23, 2022 |
| Dell          | Precision 3561              | Notebook    | [ca88539127](https://linux-hardware.org/?probe=ca88539127) | Jul 22, 2022 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [e543e58f00](https://linux-hardware.org/?probe=e543e58f00) | Jul 22, 2022 |
| MSI           | X58 Pro-E                   | Desktop     | [a448d7e654](https://linux-hardware.org/?probe=a448d7e654) | Jul 21, 2022 |
| MSI           | X58 Pro-E                   | Desktop     | [af97aaa970](https://linux-hardware.org/?probe=af97aaa970) | Jul 21, 2022 |
| Dell          | 054KM3 A00                  | Desktop     | [228194fb04](https://linux-hardware.org/?probe=228194fb04) | Jul 21, 2022 |
| Dell          | 054KM3 A00                  | Desktop     | [406a93be76](https://linux-hardware.org/?probe=406a93be76) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Dell          | Precision M4400             | Notebook    | [cf3bbe255a](https://linux-hardware.org/?probe=cf3bbe255a) | Jul 20, 2022 |
| ASUSTek       | 1215P                       | Notebook    | [3bb44d06d1](https://linux-hardware.org/?probe=3bb44d06d1) | Jul 20, 2022 |
| Dell          | Latitude E6420              | Notebook    | [77501652df](https://linux-hardware.org/?probe=77501652df) | Jul 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [09a3fc75e9](https://linux-hardware.org/?probe=09a3fc75e9) | Jul 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [27a7c25204](https://linux-hardware.org/?probe=27a7c25204) | Jul 17, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [fcbd85f698](https://linux-hardware.org/?probe=fcbd85f698) | Jul 17, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d04747e05b](https://linux-hardware.org/?probe=d04747e05b) | Jul 17, 2022 |
| Dell          | 054KM3 A00                  | Desktop     | [2c14be3e6c](https://linux-hardware.org/?probe=2c14be3e6c) | Jul 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [61b8fb7c41](https://linux-hardware.org/?probe=61b8fb7c41) | Jul 17, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [391df88f80](https://linux-hardware.org/?probe=391df88f80) | Jul 17, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| eMachines     | E725                        | Notebook    | [771942dd5e](https://linux-hardware.org/?probe=771942dd5e) | Jul 15, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [86b8dc8c6d](https://linux-hardware.org/?probe=86b8dc8c6d) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [23077c70b2](https://linux-hardware.org/?probe=23077c70b2) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10192c3d0b](https://linux-hardware.org/?probe=10192c3d0b) | Jul 14, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [fa6486dcd9](https://linux-hardware.org/?probe=fa6486dcd9) | Jul 13, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [d8edf66887](https://linux-hardware.org/?probe=d8edf66887) | Jul 13, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [5701f5019e](https://linux-hardware.org/?probe=5701f5019e) | Jul 13, 2022 |
| eMachines     | E725                        | Notebook    | [27fb6a6cab](https://linux-hardware.org/?probe=27fb6a6cab) | Jul 12, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [6998a6fb37](https://linux-hardware.org/?probe=6998a6fb37) | Jul 10, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0cdcc2c0e0](https://linux-hardware.org/?probe=0cdcc2c0e0) | Jul 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [5a009407d9](https://linux-hardware.org/?probe=5a009407d9) | Jul 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [9ae6c29438](https://linux-hardware.org/?probe=9ae6c29438) | Jul 08, 2022 |
| Dell          | Inspiron 1564               | Notebook    | [0fbabbb83d](https://linux-hardware.org/?probe=0fbabbb83d) | Jul 08, 2022 |
| Dell          | 0UT806                      | Desktop     | [7d63f287bc](https://linux-hardware.org/?probe=7d63f287bc) | Jul 08, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3672d4926e](https://linux-hardware.org/?probe=3672d4926e) | Jul 08, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [b7cc7cee98](https://linux-hardware.org/?probe=b7cc7cee98) | Jul 05, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| Lenovo        | ThinkPad W510 431924G       | Notebook    | [d65b149a5f](https://linux-hardware.org/?probe=d65b149a5f) | Jul 04, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | Desktop     | [64cb4f60fb](https://linux-hardware.org/?probe=64cb4f60fb) | Jul 04, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [bc4f34c375](https://linux-hardware.org/?probe=bc4f34c375) | Jul 04, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [03cd99ca9f](https://linux-hardware.org/?probe=03cd99ca9f) | Jul 04, 2022 |
| eMachines     | E725                        | Notebook    | [18d7561b19](https://linux-hardware.org/?probe=18d7561b19) | Jul 04, 2022 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [aeb0f9ca52](https://linux-hardware.org/?probe=aeb0f9ca52) | Jul 03, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [8b2e08891d](https://linux-hardware.org/?probe=8b2e08891d) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [a2df072a44](https://linux-hardware.org/?probe=a2df072a44) | Jul 03, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [577e49b87c](https://linux-hardware.org/?probe=577e49b87c) | Jul 03, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [38a248fedd](https://linux-hardware.org/?probe=38a248fedd) | Jul 03, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [98c7e055a3](https://linux-hardware.org/?probe=98c7e055a3) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ffde44eef6](https://linux-hardware.org/?probe=ffde44eef6) | Jul 02, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [a38b0e0209](https://linux-hardware.org/?probe=a38b0e0209) | Jul 02, 2022 |
| Biostar       | TZ77XE3                     | Desktop     | [7b597af136](https://linux-hardware.org/?probe=7b597af136) | Jul 02, 2022 |
| Dell          | 0R5KP9 A04                  | Server      | [2a9a66a9d9](https://linux-hardware.org/?probe=2a9a66a9d9) | Jul 01, 2022 |
| eMachines     | E725                        | Notebook    | [8ba1579921](https://linux-hardware.org/?probe=8ba1579921) | Jul 01, 2022 |
| eMachines     | E725                        | Notebook    | [874b6bd7de](https://linux-hardware.org/?probe=874b6bd7de) | Jul 01, 2022 |
| eMachines     | E725                        | Notebook    | [021bcca061](https://linux-hardware.org/?probe=021bcca061) | Jun 30, 2022 |
| eMachines     | E725                        | Notebook    | [b8b332e92f](https://linux-hardware.org/?probe=b8b332e92f) | Jun 30, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [0ecaca17cb](https://linux-hardware.org/?probe=0ecaca17cb) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [018b6945e1](https://linux-hardware.org/?probe=018b6945e1) | Jun 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [95db2f9536](https://linux-hardware.org/?probe=95db2f9536) | Jun 27, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [b63dffc595](https://linux-hardware.org/?probe=b63dffc595) | Jun 27, 2022 |
| eMachines     | E725                        | Notebook    | [3b272a4e25](https://linux-hardware.org/?probe=3b272a4e25) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| Dell          | 0YM158 A02                  | Server      | [ec0a133cdf](https://linux-hardware.org/?probe=ec0a133cdf) | Jun 26, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [4889364145](https://linux-hardware.org/?probe=4889364145) | Jun 26, 2022 |
| Dell          | Latitude E5500              | Notebook    | [8002c78586](https://linux-hardware.org/?probe=8002c78586) | Jun 25, 2022 |
| Dell          | 0TY915                      | Desktop     | [d6faa2c9f1](https://linux-hardware.org/?probe=d6faa2c9f1) | Jun 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [8f9e6e12b1](https://linux-hardware.org/?probe=8f9e6e12b1) | Jun 25, 2022 |
| Dell          | Latitude E7450              | Notebook    | [a03ea66786](https://linux-hardware.org/?probe=a03ea66786) | Jun 24, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [e68364c28e](https://linux-hardware.org/?probe=e68364c28e) | Jun 24, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [a26161ba2f](https://linux-hardware.org/?probe=a26161ba2f) | Jun 23, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [c37f67ba4b](https://linux-hardware.org/?probe=c37f67ba4b) | Jun 23, 2022 |
| Dell          | Latitude D630               | Notebook    | [60c9b1089c](https://linux-hardware.org/?probe=60c9b1089c) | Jun 23, 2022 |
| Xunlong       | Orange Pi Plus 2E           | Soc         | [e2beed8ee0](https://linux-hardware.org/?probe=e2beed8ee0) | Jun 23, 2022 |
| Dell          | Latitude E5500              | Notebook    | [ad849dbfe7](https://linux-hardware.org/?probe=ad849dbfe7) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f3ebefa03f](https://linux-hardware.org/?probe=f3ebefa03f) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [d230e8311a](https://linux-hardware.org/?probe=d230e8311a) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [7d1b0cfc99](https://linux-hardware.org/?probe=7d1b0cfc99) | Jun 21, 2022 |
| HP            | 339A                        | Desktop     | [4f244ada14](https://linux-hardware.org/?probe=4f244ada14) | Jun 19, 2022 |
| eMachines     | E725                        | Notebook    | [6e81be09d2](https://linux-hardware.org/?probe=6e81be09d2) | Jun 19, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [707f314c74](https://linux-hardware.org/?probe=707f314c74) | Jun 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7c094dc326](https://linux-hardware.org/?probe=7c094dc326) | Jun 19, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [42bf4b080d](https://linux-hardware.org/?probe=42bf4b080d) | Jun 19, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [3b5fb60639](https://linux-hardware.org/?probe=3b5fb60639) | Jun 19, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [fbd8e560b4](https://linux-hardware.org/?probe=fbd8e560b4) | Jun 18, 2022 |
| ASUSTek       | A7N8X2.0                    | Desktop     | [0078dfa592](https://linux-hardware.org/?probe=0078dfa592) | Jun 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [73f958fb35](https://linux-hardware.org/?probe=73f958fb35) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e9eb39efa4](https://linux-hardware.org/?probe=e9eb39efa4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [bffb7f61cb](https://linux-hardware.org/?probe=bffb7f61cb) | Jun 15, 2022 |
| HP            | x2 210                      | Notebook    | [8f6739cda0](https://linux-hardware.org/?probe=8f6739cda0) | Jun 15, 2022 |
| HP            | ProBook 4540s               | Notebook    | [934a74329f](https://linux-hardware.org/?probe=934a74329f) | Jun 14, 2022 |
| Dell          | 0VD5HY A07                  | Desktop     | [6a66d72bc1](https://linux-hardware.org/?probe=6a66d72bc1) | Jun 14, 2022 |
| Dell          | 0VD5HY A07                  | Desktop     | [5d7c3bee0c](https://linux-hardware.org/?probe=5d7c3bee0c) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ad093b7b31](https://linux-hardware.org/?probe=ad093b7b31) | Jun 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b1cc75656e](https://linux-hardware.org/?probe=b1cc75656e) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | Desktop     | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [eb4a496e95](https://linux-hardware.org/?probe=eb4a496e95) | Jun 09, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [24b293410c](https://linux-hardware.org/?probe=24b293410c) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| HP            | Compaq 6710b (KE121EA#AK... | Notebook    | [940eb51107](https://linux-hardware.org/?probe=940eb51107) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [f57b643831](https://linux-hardware.org/?probe=f57b643831) | Jun 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [fce3696537](https://linux-hardware.org/?probe=fce3696537) | Jun 08, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a2cb02217f](https://linux-hardware.org/?probe=a2cb02217f) | Jun 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [0c00fb9fe4](https://linux-hardware.org/?probe=0c00fb9fe4) | Jun 07, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4b8eab59e2](https://linux-hardware.org/?probe=4b8eab59e2) | Jun 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a989dee1a0](https://linux-hardware.org/?probe=a989dee1a0) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [d2efe762b7](https://linux-hardware.org/?probe=d2efe762b7) | Jun 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [5f64f824aa](https://linux-hardware.org/?probe=5f64f824aa) | Jun 05, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [63b4cd5c56](https://linux-hardware.org/?probe=63b4cd5c56) | Jun 05, 2022 |
| Medion        | P6630                       | Notebook    | [c1de1611b8](https://linux-hardware.org/?probe=c1de1611b8) | Jun 04, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [b563da5d39](https://linux-hardware.org/?probe=b563da5d39) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [15e4cca5bc](https://linux-hardware.org/?probe=15e4cca5bc) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [b99a9b1bce](https://linux-hardware.org/?probe=b99a9b1bce) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [96768b6e5c](https://linux-hardware.org/?probe=96768b6e5c) | Jun 02, 2022 |
| ASRock        | G41MH/USB3                  | Desktop     | [8cb0243666](https://linux-hardware.org/?probe=8cb0243666) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [d11a49f42b](https://linux-hardware.org/?probe=d11a49f42b) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [968decd1af](https://linux-hardware.org/?probe=968decd1af) | Jun 02, 2022 |
| Dell          | Latitude E6400              | Notebook    | [cea3337908](https://linux-hardware.org/?probe=cea3337908) | Jun 01, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a02283c272](https://linux-hardware.org/?probe=a02283c272) | Jun 01, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2bb0b663d7](https://linux-hardware.org/?probe=2bb0b663d7) | Jun 01, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [4ff7c85a84](https://linux-hardware.org/?probe=4ff7c85a84) | May 31, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [c65fb5ddb9](https://linux-hardware.org/?probe=c65fb5ddb9) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [6b22d31e8e](https://linux-hardware.org/?probe=6b22d31e8e) | May 31, 2022 |
| ASUSTek       | K53U                        | Notebook    | [efd067c3a8](https://linux-hardware.org/?probe=efd067c3a8) | May 30, 2022 |
| ASUSTek       | K53U                        | Notebook    | [a26756238b](https://linux-hardware.org/?probe=a26756238b) | May 30, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | Desktop     | [254fda14c1](https://linux-hardware.org/?probe=254fda14c1) | May 30, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [2f4ff624ba](https://linux-hardware.org/?probe=2f4ff624ba) | May 29, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [726cb8d22e](https://linux-hardware.org/?probe=726cb8d22e) | May 29, 2022 |
| Dell          | Latitude E6230              | Notebook    | [068d9b4143](https://linux-hardware.org/?probe=068d9b4143) | May 29, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b6d663fde6](https://linux-hardware.org/?probe=b6d663fde6) | May 29, 2022 |
| Dell          | Latitude E6230              | Notebook    | [c50bb14e9a](https://linux-hardware.org/?probe=c50bb14e9a) | May 29, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [444e61772c](https://linux-hardware.org/?probe=444e61772c) | May 29, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [09b39cf91e](https://linux-hardware.org/?probe=09b39cf91e) | May 29, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [143b8e7ea9](https://linux-hardware.org/?probe=143b8e7ea9) | May 29, 2022 |
| Medion        | P6630                       | Notebook    | [7f5b714dfc](https://linux-hardware.org/?probe=7f5b714dfc) | May 28, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [255d32d2b3](https://linux-hardware.org/?probe=255d32d2b3) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [672f924aec](https://linux-hardware.org/?probe=672f924aec) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [7f91291747](https://linux-hardware.org/?probe=7f91291747) | May 28, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [65bb3086df](https://linux-hardware.org/?probe=65bb3086df) | May 28, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [fcff479318](https://linux-hardware.org/?probe=fcff479318) | May 28, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [7e17227514](https://linux-hardware.org/?probe=7e17227514) | May 27, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [3db842adc9](https://linux-hardware.org/?probe=3db842adc9) | May 27, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [110903519d](https://linux-hardware.org/?probe=110903519d) | May 26, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [293f5586bd](https://linux-hardware.org/?probe=293f5586bd) | May 25, 2022 |
| Dell          | 0PU052                      | Desktop     | [4e3e3cc0fd](https://linux-hardware.org/?probe=4e3e3cc0fd) | May 24, 2022 |
| HP            | 620                         | Notebook    | [b5bf98b16a](https://linux-hardware.org/?probe=b5bf98b16a) | May 23, 2022 |
| HP            | 620                         | Notebook    | [8bf9517a97](https://linux-hardware.org/?probe=8bf9517a97) | May 23, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [1f8b067cca](https://linux-hardware.org/?probe=1f8b067cca) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [26d3a29dc1](https://linux-hardware.org/?probe=26d3a29dc1) | May 23, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [4cbbeda22c](https://linux-hardware.org/?probe=4cbbeda22c) | May 22, 2022 |
| HP            | Presario CQ58               | Notebook    | [bdf8b7e229](https://linux-hardware.org/?probe=bdf8b7e229) | May 22, 2022 |
| HP            | Presario CQ58               | Notebook    | [383a27dd29](https://linux-hardware.org/?probe=383a27dd29) | May 22, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [43d5dce3ee](https://linux-hardware.org/?probe=43d5dce3ee) | May 22, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [6efef2bd1e](https://linux-hardware.org/?probe=6efef2bd1e) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [b32a821a4c](https://linux-hardware.org/?probe=b32a821a4c) | May 21, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [3386aeef48](https://linux-hardware.org/?probe=3386aeef48) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [9003466ff8](https://linux-hardware.org/?probe=9003466ff8) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [2e05001696](https://linux-hardware.org/?probe=2e05001696) | May 21, 2022 |
| HP            | 620                         | Notebook    | [babb1f392a](https://linux-hardware.org/?probe=babb1f392a) | May 21, 2022 |
| ASRock        | A75M-ITX                    | Desktop     | [6287159bfa](https://linux-hardware.org/?probe=6287159bfa) | May 20, 2022 |
| JGINYUE       | X99M-PLUS V2 V2.0           | Desktop     | [de7a2328c3](https://linux-hardware.org/?probe=de7a2328c3) | May 20, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [0044468fc2](https://linux-hardware.org/?probe=0044468fc2) | May 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [ae6f7ab64b](https://linux-hardware.org/?probe=ae6f7ab64b) | May 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [d30a648e90](https://linux-hardware.org/?probe=d30a648e90) | May 19, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [cf5954d738](https://linux-hardware.org/?probe=cf5954d738) | May 18, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [5995dc5192](https://linux-hardware.org/?probe=5995dc5192) | May 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [26837853fd](https://linux-hardware.org/?probe=26837853fd) | May 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ac086e77c6](https://linux-hardware.org/?probe=ac086e77c6) | May 17, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [bfe6579a0e](https://linux-hardware.org/?probe=bfe6579a0e) | May 16, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [f4b9c3997d](https://linux-hardware.org/?probe=f4b9c3997d) | May 16, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [153c3cb471](https://linux-hardware.org/?probe=153c3cb471) | May 16, 2022 |
| Toshiba       | Satellite L775-18R          | Notebook    | [ec012c6b3d](https://linux-hardware.org/?probe=ec012c6b3d) | May 16, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [75f2c0ab4e](https://linux-hardware.org/?probe=75f2c0ab4e) | May 15, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [8d710ae7c3](https://linux-hardware.org/?probe=8d710ae7c3) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [758e2b869d](https://linux-hardware.org/?probe=758e2b869d) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [91c6da69a9](https://linux-hardware.org/?probe=91c6da69a9) | May 15, 2022 |
| HP            | 1589                        | Desktop     | [fb9e076bb8](https://linux-hardware.org/?probe=fb9e076bb8) | May 15, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [bde3f15809](https://linux-hardware.org/?probe=bde3f15809) | May 15, 2022 |
| Unknown       | NF-MCP78                    | Desktop     | [0265fc0430](https://linux-hardware.org/?probe=0265fc0430) | May 14, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e805d60a6b](https://linux-hardware.org/?probe=e805d60a6b) | May 14, 2022 |
| MSI           | B85M-P32                    | Desktop     | [9585181994](https://linux-hardware.org/?probe=9585181994) | May 14, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f784f7eb95](https://linux-hardware.org/?probe=f784f7eb95) | May 14, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [bfc1a518db](https://linux-hardware.org/?probe=bfc1a518db) | May 14, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| HP            | 620                         | Notebook    | [62369d924a](https://linux-hardware.org/?probe=62369d924a) | May 12, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [146d11b8f2](https://linux-hardware.org/?probe=146d11b8f2) | May 10, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [6c4bf376bd](https://linux-hardware.org/?probe=6c4bf376bd) | May 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [0099d17388](https://linux-hardware.org/?probe=0099d17388) | May 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [25787f8eb3](https://linux-hardware.org/?probe=25787f8eb3) | May 10, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [5a694d9de8](https://linux-hardware.org/?probe=5a694d9de8) | May 10, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [af7f41e61f](https://linux-hardware.org/?probe=af7f41e61f) | May 10, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [fdc78a778b](https://linux-hardware.org/?probe=fdc78a778b) | May 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [d9d1e38394](https://linux-hardware.org/?probe=d9d1e38394) | May 09, 2022 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [f1bdc60827](https://linux-hardware.org/?probe=f1bdc60827) | May 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [dd31ac3d4d](https://linux-hardware.org/?probe=dd31ac3d4d) | May 08, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [e4030c65d7](https://linux-hardware.org/?probe=e4030c65d7) | May 07, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4c4a006287](https://linux-hardware.org/?probe=4c4a006287) | May 07, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [ef54ce0eda](https://linux-hardware.org/?probe=ef54ce0eda) | May 06, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [94a92586e6](https://linux-hardware.org/?probe=94a92586e6) | May 06, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [87dd767f71](https://linux-hardware.org/?probe=87dd767f71) | May 05, 2022 |
| Gigabyte      | X48-DS5                     | Desktop     | [72a1aaf67d](https://linux-hardware.org/?probe=72a1aaf67d) | May 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS6LB00    | Notebook    | [3d7e88cdae](https://linux-hardware.org/?probe=3d7e88cdae) | May 03, 2022 |
| ASUSTek       | GL552JX                     | Notebook    | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [62f1d13e63](https://linux-hardware.org/?probe=62f1d13e63) | May 02, 2022 |
| Lenovo        | ThinkPad X240 20AL00FGMB    | Notebook    | [afba42bf24](https://linux-hardware.org/?probe=afba42bf24) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| HP            | 1850                        | Desktop     | [1a2271c939](https://linux-hardware.org/?probe=1a2271c939) | May 01, 2022 |
| Dell          | 0TY915                      | Desktop     | [7de07e1186](https://linux-hardware.org/?probe=7de07e1186) | May 01, 2022 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | Desktop     | [bb192229b3](https://linux-hardware.org/?probe=bb192229b3) | Apr 30, 2022 |
| Fujitsu Si... | D2660-A1 S26361-D2660-A1    | Desktop     | [a5ce52429c](https://linux-hardware.org/?probe=a5ce52429c) | Apr 30, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [af2b0de49b](https://linux-hardware.org/?probe=af2b0de49b) | Apr 29, 2022 |
| HP            | ProBook 645 G4              | Notebook    | [0a4b56ae27](https://linux-hardware.org/?probe=0a4b56ae27) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [54087491d8](https://linux-hardware.org/?probe=54087491d8) | Apr 28, 2022 |
| HP            | ProBook 645 G4              | Notebook    | [1546b59830](https://linux-hardware.org/?probe=1546b59830) | Apr 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [05896f4d55](https://linux-hardware.org/?probe=05896f4d55) | Apr 27, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [c4ccc166be](https://linux-hardware.org/?probe=c4ccc166be) | Apr 27, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [0fc510a45a](https://linux-hardware.org/?probe=0fc510a45a) | Apr 26, 2022 |
| Toshiba       | NB550D                      | Notebook    | [386409d233](https://linux-hardware.org/?probe=386409d233) | Apr 24, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [2ccbcae022](https://linux-hardware.org/?probe=2ccbcae022) | Apr 23, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [ec77795911](https://linux-hardware.org/?probe=ec77795911) | Apr 23, 2022 |
| ASUSTek       | GL552JX                     | Notebook    | [dae470212d](https://linux-hardware.org/?probe=dae470212d) | Apr 22, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [93239c624a](https://linux-hardware.org/?probe=93239c624a) | Apr 22, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [6c6203c7ff](https://linux-hardware.org/?probe=6c6203c7ff) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [5a855c522f](https://linux-hardware.org/?probe=5a855c522f) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [c1623a9f89](https://linux-hardware.org/?probe=c1623a9f89) | Apr 21, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [c34ed29ab2](https://linux-hardware.org/?probe=c34ed29ab2) | Apr 21, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [9b742eb785](https://linux-hardware.org/?probe=9b742eb785) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [f830e867e5](https://linux-hardware.org/?probe=f830e867e5) | Apr 20, 2022 |
| HP            | 339A                        | Desktop     | [229032eb98](https://linux-hardware.org/?probe=229032eb98) | Apr 19, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [36e5a2229d](https://linux-hardware.org/?probe=36e5a2229d) | Apr 18, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [af6b076e21](https://linux-hardware.org/?probe=af6b076e21) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [48b6f0e313](https://linux-hardware.org/?probe=48b6f0e313) | Apr 18, 2022 |
| Lenovo        | ThinkCentre A57 98517HG     | Desktop     | [d624a31b69](https://linux-hardware.org/?probe=d624a31b69) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | Notebook    | [cde65f88c1](https://linux-hardware.org/?probe=cde65f88c1) | Apr 17, 2022 |
| ASUSTek       | TP201SA                     | Notebook    | [2898b67bff](https://linux-hardware.org/?probe=2898b67bff) | Apr 16, 2022 |
| ASRock        | ConRoe1333-D667             | Desktop     | [d2bba273a0](https://linux-hardware.org/?probe=d2bba273a0) | Apr 15, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [4852dde595](https://linux-hardware.org/?probe=4852dde595) | Apr 15, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a89ca51e1b](https://linux-hardware.org/?probe=a89ca51e1b) | Apr 15, 2022 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [9ed3f59682](https://linux-hardware.org/?probe=9ed3f59682) | Apr 14, 2022 |
| Fujitsu       | LIFEBOOK E743               | Notebook    | [43ee1b9237](https://linux-hardware.org/?probe=43ee1b9237) | Apr 14, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0dddcf5626](https://linux-hardware.org/?probe=0dddcf5626) | Apr 13, 2022 |
| Dell          | G5 5587                     | Notebook    | [b3c44a59f0](https://linux-hardware.org/?probe=b3c44a59f0) | Apr 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0123ade8f7](https://linux-hardware.org/?probe=0123ade8f7) | Apr 13, 2022 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [5e30e0e56d](https://linux-hardware.org/?probe=5e30e0e56d) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [67175f0019](https://linux-hardware.org/?probe=67175f0019) | Apr 12, 2022 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [c11ab04912](https://linux-hardware.org/?probe=c11ab04912) | Apr 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [88655213a1](https://linux-hardware.org/?probe=88655213a1) | Apr 12, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ee1f05022a](https://linux-hardware.org/?probe=ee1f05022a) | Apr 10, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [a41b7fbf00](https://linux-hardware.org/?probe=a41b7fbf00) | Apr 10, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [00215e25c0](https://linux-hardware.org/?probe=00215e25c0) | Apr 10, 2022 |
| ASRock        | Z270 Professional Gaming... | Desktop     | [9129317f19](https://linux-hardware.org/?probe=9129317f19) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| Dell          | Latitude 7480               | Notebook    | [b235ce5f92](https://linux-hardware.org/?probe=b235ce5f92) | Apr 10, 2022 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3d91f855bc](https://linux-hardware.org/?probe=3d91f855bc) | Apr 09, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | Desktop     | [6130d7e1e6](https://linux-hardware.org/?probe=6130d7e1e6) | Apr 09, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [7dde5fefd1](https://linux-hardware.org/?probe=7dde5fefd1) | Apr 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b0840dd295](https://linux-hardware.org/?probe=b0840dd295) | Apr 09, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [9dc3653255](https://linux-hardware.org/?probe=9dc3653255) | Apr 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | Notebook    | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | Notebook    | [ae77218dcf](https://linux-hardware.org/?probe=ae77218dcf) | Apr 07, 2022 |
| Toshiba       | TECRA A10                   | Notebook    | [b062d23fb7](https://linux-hardware.org/?probe=b062d23fb7) | Apr 07, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a99419647f](https://linux-hardware.org/?probe=a99419647f) | Apr 07, 2022 |
| Lenovo        | ThinkPad T61 6458WK6        | Notebook    | [5303af9863](https://linux-hardware.org/?probe=5303af9863) | Apr 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c58e24cff5](https://linux-hardware.org/?probe=c58e24cff5) | Apr 07, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [5d73ae026b](https://linux-hardware.org/?probe=5d73ae026b) | Apr 05, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| Gigabyte      | H87M-HD3                    | Desktop     | [76eb57cf5e](https://linux-hardware.org/?probe=76eb57cf5e) | Apr 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [c081f43e18](https://linux-hardware.org/?probe=c081f43e18) | Apr 05, 2022 |
| ASRock        | B85M                        | Desktop     | [5e03e9532d](https://linux-hardware.org/?probe=5e03e9532d) | Apr 04, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [9d1398934f](https://linux-hardware.org/?probe=9d1398934f) | Apr 04, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [10ccb633ee](https://linux-hardware.org/?probe=10ccb633ee) | Apr 04, 2022 |
| Acer          | TravelMate P215-52          | Notebook    | [a5d16dc93e](https://linux-hardware.org/?probe=a5d16dc93e) | Apr 03, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [495e271511](https://linux-hardware.org/?probe=495e271511) | Apr 03, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [46775a18b0](https://linux-hardware.org/?probe=46775a18b0) | Apr 03, 2022 |
| Dell          | Latitude E5420              | Notebook    | [a60c1a4785](https://linux-hardware.org/?probe=a60c1a4785) | Apr 03, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [be1de1d236](https://linux-hardware.org/?probe=be1de1d236) | Apr 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [a7cad8a09a](https://linux-hardware.org/?probe=a7cad8a09a) | Apr 02, 2022 |
| HP            | Pavilion 15                 | Notebook    | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Acer          | TravelMate P215-52          | Notebook    | [752d283e54](https://linux-hardware.org/?probe=752d283e54) | Apr 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [666c8daa31](https://linux-hardware.org/?probe=666c8daa31) | Apr 01, 2022 |
| HP            | Unknown                     | Notebook    | [c6a02a2df5](https://linux-hardware.org/?probe=c6a02a2df5) | Apr 01, 2022 |
| HP            | Unknown                     | Notebook    | [71ae764e9f](https://linux-hardware.org/?probe=71ae764e9f) | Apr 01, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [01c8b92976](https://linux-hardware.org/?probe=01c8b92976) | Mar 31, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [1a946533b6](https://linux-hardware.org/?probe=1a946533b6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | Desktop     | [c338f4ffd4](https://linux-hardware.org/?probe=c338f4ffd4) | Mar 31, 2022 |
| HP            | 18E7                        | Desktop     | [4503b657fe](https://linux-hardware.org/?probe=4503b657fe) | Mar 30, 2022 |
| Dell          | Latitude E6420              | Notebook    | [2a0c2610ea](https://linux-hardware.org/?probe=2a0c2610ea) | Mar 30, 2022 |
| eMachines     | E725                        | Notebook    | [475f79831d](https://linux-hardware.org/?probe=475f79831d) | Mar 29, 2022 |
| eMachines     | E725                        | Notebook    | [f8e777c318](https://linux-hardware.org/?probe=f8e777c318) | Mar 29, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [60da33f3aa](https://linux-hardware.org/?probe=60da33f3aa) | Mar 28, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [6cff18109b](https://linux-hardware.org/?probe=6cff18109b) | Mar 28, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [b650c90413](https://linux-hardware.org/?probe=b650c90413) | Mar 28, 2022 |
| Dell          | System XPS 15Z              | Notebook    | [3e4b6f7b57](https://linux-hardware.org/?probe=3e4b6f7b57) | Mar 28, 2022 |
| Dell          | Latitude E5540              | Notebook    | [838350f357](https://linux-hardware.org/?probe=838350f357) | Mar 28, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | Notebook    | [8e8bd0aad5](https://linux-hardware.org/?probe=8e8bd0aad5) | Mar 28, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [2f7bece339](https://linux-hardware.org/?probe=2f7bece339) | Mar 27, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ec430f1afc](https://linux-hardware.org/?probe=ec430f1afc) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [a36af1ef0f](https://linux-hardware.org/?probe=a36af1ef0f) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [c3b9926b94](https://linux-hardware.org/?probe=c3b9926b94) | Mar 27, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5d62943116](https://linux-hardware.org/?probe=5d62943116) | Mar 27, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [a356a33d0a](https://linux-hardware.org/?probe=a356a33d0a) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e807733708](https://linux-hardware.org/?probe=e807733708) | Mar 26, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [59df12dc12](https://linux-hardware.org/?probe=59df12dc12) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M91p 4524AS3    | Desktop     | [7e1b536f6b](https://linux-hardware.org/?probe=7e1b536f6b) | Mar 26, 2022 |
| Lenovo        | ThinkCentre M70e 0832A26    | Desktop     | [fd041828d0](https://linux-hardware.org/?probe=fd041828d0) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c527847cd3](https://linux-hardware.org/?probe=c527847cd3) | Mar 25, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c3e549a376](https://linux-hardware.org/?probe=c3e549a376) | Mar 25, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [ed4ed6851f](https://linux-hardware.org/?probe=ed4ed6851f) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [57111f23b4](https://linux-hardware.org/?probe=57111f23b4) | Mar 23, 2022 |
| Dell          | Latitude E7450              | Notebook    | [ad41ea623a](https://linux-hardware.org/?probe=ad41ea623a) | Mar 23, 2022 |
| Lenovo        | G565 20071                  | Notebook    | [40cf723fac](https://linux-hardware.org/?probe=40cf723fac) | Mar 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [5b8c4678af](https://linux-hardware.org/?probe=5b8c4678af) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [d2e30b1d8b](https://linux-hardware.org/?probe=d2e30b1d8b) | Mar 22, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [72e8662f26](https://linux-hardware.org/?probe=72e8662f26) | Mar 22, 2022 |
| Acer          | TravelMate P238-G2-M        | Notebook    | [7aa968ca84](https://linux-hardware.org/?probe=7aa968ca84) | Mar 22, 2022 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [5611c90f20](https://linux-hardware.org/?probe=5611c90f20) | Mar 21, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [2a71c88e71](https://linux-hardware.org/?probe=2a71c88e71) | Mar 21, 2022 |
| MSI           | A320M BAZOOKA               | Desktop     | [0c12287476](https://linux-hardware.org/?probe=0c12287476) | Mar 21, 2022 |
| ASUSTek       | P5B                         | Desktop     | [0ec5966c98](https://linux-hardware.org/?probe=0ec5966c98) | Mar 21, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [85236d7863](https://linux-hardware.org/?probe=85236d7863) | Mar 20, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [2391a2db23](https://linux-hardware.org/?probe=2391a2db23) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [9f18cfb328](https://linux-hardware.org/?probe=9f18cfb328) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [399ab158b9](https://linux-hardware.org/?probe=399ab158b9) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [716d4ed3be](https://linux-hardware.org/?probe=716d4ed3be) | Mar 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | Desktop     | [661d9fcffa](https://linux-hardware.org/?probe=661d9fcffa) | Mar 18, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [46af9af40c](https://linux-hardware.org/?probe=46af9af40c) | Mar 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1b697ade27](https://linux-hardware.org/?probe=1b697ade27) | Mar 17, 2022 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [6533ff3270](https://linux-hardware.org/?probe=6533ff3270) | Mar 16, 2022 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [1e13431147](https://linux-hardware.org/?probe=1e13431147) | Mar 16, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [6ae5708fe3](https://linux-hardware.org/?probe=6ae5708fe3) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [e8e4e5d953](https://linux-hardware.org/?probe=e8e4e5d953) | Mar 15, 2022 |
| HP            | 1589                        | Desktop     | [41622b6b2d](https://linux-hardware.org/?probe=41622b6b2d) | Mar 14, 2022 |
| HP            | 650                         | Notebook    | [3266dba7df](https://linux-hardware.org/?probe=3266dba7df) | Mar 14, 2022 |
| HP            | 650                         | Notebook    | [54df12f572](https://linux-hardware.org/?probe=54df12f572) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [79a7c69b79](https://linux-hardware.org/?probe=79a7c69b79) | Mar 13, 2022 |
| HP            | 1589                        | Desktop     | [95af16db2e](https://linux-hardware.org/?probe=95af16db2e) | Mar 13, 2022 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [29c3688c05](https://linux-hardware.org/?probe=29c3688c05) | Mar 13, 2022 |
| Dell          | 0GM819                      | Desktop     | [e06d400f29](https://linux-hardware.org/?probe=e06d400f29) | Mar 13, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [74ba6d5353](https://linux-hardware.org/?probe=74ba6d5353) | Mar 12, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [912b670e0f](https://linux-hardware.org/?probe=912b670e0f) | Mar 12, 2022 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [64f83fa328](https://linux-hardware.org/?probe=64f83fa328) | Mar 12, 2022 |
| eMachines     | E725                        | Notebook    | [05b157a340](https://linux-hardware.org/?probe=05b157a340) | Mar 12, 2022 |
| Packard Be... | EasyNote TS13SB             | Notebook    | [9d702d33cb](https://linux-hardware.org/?probe=9d702d33cb) | Mar 12, 2022 |
| Acer          | Veriton M4610G              | Desktop     | [ec980460ed](https://linux-hardware.org/?probe=ec980460ed) | Mar 12, 2022 |
| Lenovo        | ThinkServer TS440           | Desktop     | [ec0e6e5114](https://linux-hardware.org/?probe=ec0e6e5114) | Mar 11, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f5ff2a8a14](https://linux-hardware.org/?probe=f5ff2a8a14) | Mar 10, 2022 |
| HP            | Pavilion 17                 | Notebook    | [b6bfe40827](https://linux-hardware.org/?probe=b6bfe40827) | Mar 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [299209635a](https://linux-hardware.org/?probe=299209635a) | Mar 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [20ca54a46c](https://linux-hardware.org/?probe=20ca54a46c) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [71e8b113b4](https://linux-hardware.org/?probe=71e8b113b4) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0148e15f51](https://linux-hardware.org/?probe=0148e15f51) | Mar 09, 2022 |
| ASUSTek       | BU401LA                     | Notebook    | [2df54ef02e](https://linux-hardware.org/?probe=2df54ef02e) | Mar 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 1904      | 51.09%  |
| Ubuntu 20.04                 | 268       | 7.19%   |
| BlackPanther 16.2            | 222       | 5.96%   |
| Ubuntu 18.04                 | 155       | 4.16%   |
| Ubuntu 22.04                 | 65        | 1.74%   |
| OpenMandriva 4.2             | 59        | 1.58%   |
| Debian 11                    | 40        | 1.07%   |
| OpenMandriva 4.3             | 35        | 0.94%   |
| Linux Mint 20.2              | 31        | 0.83%   |
| Arch                         | 25        | 0.67%   |
| Ubuntu 19.10                 | 23        | 0.62%   |
| Zorin 16                     | 22        | 0.59%   |
| Linux Mint 19.3              | 22        | 0.59%   |
| Debian 10                    | 21        | 0.56%   |
| Arch Rolling                 | 21        | 0.56%   |
| Linux Mint 20                | 20        | 0.54%   |
| Kubuntu 20.04                | 20        | 0.54%   |
| Xubuntu 20.04                | 19        | 0.51%   |
| Ubuntu 21.10                 | 19        | 0.51%   |
| Ubuntu 19.04                 | 19        | 0.51%   |
| Linux Mint 20.3              | 19        | 0.51%   |
| KDE neon 20.04               | 19        | 0.51%   |
| Fedora 36                    | 19        | 0.51%   |
| Ubuntu 21.04                 | 17        | 0.46%   |
| ArcoLinux Rolling            | 17        | 0.46%   |
| Xubuntu 18.04                | 16        | 0.43%   |
| Manjaro                      | 16        | 0.43%   |
| Linux Mint 20.1              | 15        | 0.4%    |
| Fedora 35                    | 15        | 0.4%    |
| OpenMandriva 4.50            | 14        | 0.38%   |
| Fedora 33                    | 14        | 0.38%   |
| Ubuntu 20.10                 | 13        | 0.35%   |
| Fedora 32                    | 13        | 0.35%   |
| Zorin 15                     | 12        | 0.32%   |
| Pop!_OS 22.04                | 12        | 0.32%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 0.32%   |
| Fedora 37                    | 12        | 0.32%   |
| OpenMandriva 23.01           | 11        | 0.3%    |
| Ubuntu Unity 16.04           | 9         | 0.24%   |
| Pop!_OS 21.04                | 9         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| BlackPanther  | 2086      | 58.32%  |
| Ubuntu        | 566       | 15.82%  |
| OpenMandriva  | 128       | 3.58%   |
| Linux Mint    | 123       | 3.44%   |
| Endless       | 78        | 2.18%   |
| Debian        | 74        | 2.07%   |
| Fedora        | 72        | 2.01%   |
| Arch          | 45        | 1.26%   |
| Xubuntu       | 43        | 1.2%    |
| Manjaro       | 43        | 1.2%    |
| Kubuntu       | 43        | 1.2%    |
| Pop!_OS       | 35        | 0.98%   |
| Zorin         | 34        | 0.95%   |
| KDE neon      | 24        | 0.67%   |
| ArcoLinux     | 21        | 0.59%   |
| ROSA          | 18        | 0.5%    |
| openSUSE      | 18        | 0.5%    |
| Ubuntu MATE   | 17        | 0.48%   |
| Ubuntu Unity  | 15        | 0.42%   |
| Lubuntu       | 14        | 0.39%   |
| Elementary    | 8         | 0.22%   |
| Gentoo        | 7         | 0.2%    |
| Kali          | 6         | 0.17%   |
| Ubuntu Budgie | 5         | 0.14%   |
| Raspbian      | 5         | 0.14%   |
| MX            | 4         | 0.11%   |
| LMDE          | 4         | 0.11%   |
| EndeavourOS   | 4         | 0.11%   |
| Clear Linux   | 4         | 0.11%   |
| Nobara        | 3         | 0.08%   |
| UbuntuDDE     | 2         | 0.06%   |
| SteamOS       | 2         | 0.06%   |
| Rocky Linux   | 2         | 0.06%   |
| Garuda Linux  | 2         | 0.06%   |
| Devuan        | 2         | 0.06%   |
| Xero          | 1         | 0.03%   |
| UHU           | 1         | 0.03%   |
| Ubuntu Studio | 1         | 0.03%   |
| Solus         | 1         | 0.03%   |
| risiOS        | 1         | 0.03%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 1446      | 35.35%  |
| 5.6.14-desktop-2bP       | 569       | 13.91%  |
| 4.9.20-desktop-pae-1bP   | 205       | 5.01%   |
| 5.1.15-desktop-1bP       | 84        | 2.05%   |
| 5.10.14-desktop-1omv4002 | 55        | 1.34%   |
| 5.4.0-42-generic         | 42        | 1.03%   |
| 5.16.7-desktop-1omv4003  | 34        | 0.83%   |
| 5.4.0-58-generic         | 27        | 0.66%   |
| 5.8.0-14-generic         | 23        | 0.56%   |
| 5.4.0-52-generic         | 21        | 0.51%   |
| 5.4.0-48-generic         | 19        | 0.46%   |
| 5.11.0-27-generic        | 18        | 0.44%   |
| 5.3.0-28-generic         | 14        | 0.34%   |
| 5.15.0-56-generic        | 14        | 0.34%   |
| 5.15.0-52-generic        | 14        | 0.34%   |
| 5.15.0-43-generic        | 14        | 0.34%   |
| 4.18.0-15-generic        | 14        | 0.34%   |
| 5.4.0-54-generic         | 13        | 0.32%   |
| 5.4.0-40-generic         | 13        | 0.32%   |
| 5.4.0-19-generic         | 13        | 0.32%   |
| 5.11.0-34-generic        | 13        | 0.32%   |
| 5.4.0-29-generic         | 12        | 0.29%   |
| 4.15.0-43-generic        | 12        | 0.29%   |
| 5.4.0-91-generic         | 11        | 0.27%   |
| 5.4.0-26-generic         | 11        | 0.27%   |
| 5.15.0-46-generic        | 11        | 0.27%   |
| 5.15.0-41-generic        | 11        | 0.27%   |
| 5.11.0-43-generic        | 11        | 0.27%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.24%   |
| 5.8.0-43-generic         | 10        | 0.24%   |
| 5.3.0-46-generic         | 10        | 0.24%   |
| 5.15.0-58-generic        | 10        | 0.24%   |
| 5.13.0-27-generic        | 10        | 0.24%   |
| 5.0.0-37-generic         | 10        | 0.24%   |
| 5.8.0-59-generic         | 9         | 0.22%   |
| 5.8.0-53-generic         | 9         | 0.22%   |
| 5.4.0-39-generic         | 9         | 0.22%   |
| 5.4.0-100-generic        | 9         | 0.22%   |
| 5.0.0-25-generic         | 9         | 0.22%   |
| 5.8.0-44-generic         | 8         | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.16 | 1446      | 36.39%  |
| 5.6.14  | 570       | 14.34%  |
| 5.4.0   | 333       | 8.38%   |
| 4.9.20  | 216       | 5.44%   |
| 5.15.0  | 118       | 2.97%   |
| 4.15.0  | 114       | 2.87%   |
| 5.8.0   | 101       | 2.54%   |
| 5.11.0  | 100       | 2.52%   |
| 5.1.15  | 85        | 2.14%   |
| 5.3.0   | 81        | 2.04%   |
| 5.13.0  | 78        | 1.96%   |
| 5.0.0   | 56        | 1.41%   |
| 5.10.14 | 55        | 1.38%   |
| 5.10.0  | 48        | 1.21%   |
| 4.18.0  | 39        | 0.98%   |
| 5.16.7  | 35        | 0.88%   |
| 4.19.0  | 22        | 0.55%   |
| 6.1.1   | 14        | 0.35%   |
| 5.19.0  | 9         | 0.23%   |
| 5.16.0  | 9         | 0.23%   |
| 5.12.4  | 9         | 0.23%   |
| 4.13.0  | 9         | 0.23%   |
| 5.18.12 | 8         | 0.2%    |
| 5.14.0  | 8         | 0.2%    |
| 4.4.0   | 8         | 0.2%    |
| 6.0.12  | 7         | 0.18%   |
| 5.13.13 | 7         | 0.18%   |
| 5.9.16  | 6         | 0.15%   |
| 5.9.0   | 6         | 0.15%   |
| 5.18.0  | 5         | 0.13%   |
| 5.17.1  | 5         | 0.13%   |
| 5.15.12 | 5         | 0.13%   |
| 5.12.9  | 5         | 0.13%   |
| 5.10.7  | 5         | 0.13%   |
| 4.9.60  | 5         | 0.13%   |
| 4.7.0   | 5         | 0.13%   |
| 6.0.9   | 4         | 0.1%    |
| 6.0.0   | 4         | 0.1%    |
| 5.9.1   | 4         | 0.1%    |
| 5.8.14  | 4         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 1484      | 37.56%  |
| 5.6     | 585       | 14.81%  |
| 5.4     | 355       | 8.99%   |
| 4.9     | 228       | 5.77%   |
| 5.15    | 153       | 3.87%   |
| 5.10    | 129       | 3.26%   |
| 5.11    | 120       | 3.04%   |
| 5.8     | 117       | 2.96%   |
| 4.15    | 114       | 2.89%   |
| 5.13    | 90        | 2.28%   |
| 5.1     | 88        | 2.23%   |
| 5.3     | 87        | 2.2%    |
| 5.16    | 62        | 1.57%   |
| 5.0     | 56        | 1.42%   |
| 5.19    | 31        | 0.78%   |
| 5.18    | 29        | 0.73%   |
| 6.0     | 27        | 0.68%   |
| 5.9     | 25        | 0.63%   |
| 6.1     | 24        | 0.61%   |
| 4.19    | 24        | 0.61%   |
| 5.14    | 23        | 0.58%   |
| 5.12    | 23        | 0.58%   |
| 5.17    | 17        | 0.43%   |
| 5.7     | 15        | 0.38%   |
| 4.13    | 9         | 0.23%   |
| 4.4     | 8         | 0.2%    |
| 5.5     | 7         | 0.18%   |
| 4.7     | 5         | 0.13%   |
| 4.16    | 4         | 0.1%    |
| 4.5     | 2         | 0.05%   |
| 4.20    | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 5.2     | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3220      | 91.84%  |
| i686    | 276       | 7.87%   |
| armv7l  | 4         | 0.11%   |
| aarch64 | 3         | 0.09%   |
| armv6l  | 2         | 0.06%   |
| unknow  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 2290      | 64.09%  |
| GNOME           | 627       | 17.55%  |
| Unknown         | 239       | 6.69%   |
| XFCE            | 115       | 3.22%   |
| X-Cinnamon      | 88        | 2.46%   |
| MATE            | 56        | 1.57%   |
| KDE             | 37        | 1.04%   |
| Cinnamon        | 29        | 0.81%   |
| LXQt            | 17        | 0.48%   |
| Unity           | 15        | 0.42%   |
| KDE4            | 14        | 0.39%   |
| i3              | 8         | 0.22%   |
| Pantheon        | 7         | 0.2%    |
| Deepin          | 7         | 0.2%    |
| Budgie          | 6         | 0.17%   |
| LXDE            | 5         | 0.14%   |
| GNOME Flashback | 5         | 0.14%   |
| GNOME Classic   | 2         | 0.06%   |
| Trinity         | 1         | 0.03%   |
| qtile           | 1         | 0.03%   |
| ICEWM           | 1         | 0.03%   |
| Enlightenment   | 1         | 0.03%   |
| bspwm           | 1         | 0.03%   |
| awesome         | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3181      | 90.42%  |
| Wayland | 170       | 4.83%   |
| Unknown | 138       | 3.92%   |
| Tty     | 29        | 0.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2279      | 64.05%  |
| Unknown | 763       | 21.44%  |
| GDM     | 158       | 4.44%   |
| GDM3    | 137       | 3.85%   |
| LightDM | 135       | 3.79%   |
| TDM     | 64        | 1.8%    |
| KDM     | 14        | 0.39%   |
| SLiM    | 5         | 0.14%   |
| XDM     | 3         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2252      | 63.26%  |
| hu_HU      | 796       | 22.36%  |
| en_US      | 415       | 11.66%  |
| en_GB      | 40        | 1.12%   |
| C          | 23        | 0.65%   |
| de_DE      | 14        | 0.39%   |
| ru_UA      | 3         | 0.08%   |
| ru_RU      | 2         | 0.06%   |
| POSIX      | 2         | 0.06%   |
| nl_NL      | 2         | 0.06%   |
| hu_HU.UTF8 | 2         | 0.06%   |
| en_AU      | 2         | 0.06%   |
| it_IT      | 1         | 0.03%   |
| fr_FR      | 1         | 0.03%   |
| fr_BE      | 1         | 0.03%   |
| en_ZA      | 1         | 0.03%   |
| en_AG      | 1         | 0.03%   |
| de_AT      | 1         | 0.03%   |
| C.UTF8     | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2308      | 63.93%  |
| EFI  | 1302      | 36.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2013      | 53.32%  |
| Overlay | 1552      | 41.11%  |
| Btrfs   | 93        | 2.46%   |
| Unknown | 79        | 2.09%   |
| Xfs     | 11        | 0.29%   |
| Ext2    | 9         | 0.24%   |
| Zfs     | 8         | 0.21%   |
| Ext3    | 7         | 0.19%   |
| F2fs    | 2         | 0.05%   |
| Tmpfs   | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 1665      | 45.86%  |
| GPT     | 1137      | 31.31%  |
| Unknown | 829       | 22.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2759      | 73.67%  |
| Yes       | 986       | 26.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1973      | 53.66%  |
| Yes       | 1704      | 46.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 578       | 16.68%  |
| Hewlett-Packard         | 527       | 15.21%  |
| Dell                    | 493       | 14.23%  |
| Lenovo                  | 478       | 13.8%   |
| Gigabyte Technology     | 293       | 8.46%   |
| ASRock                  | 246       | 7.1%    |
| Acer                    | 241       | 6.96%   |
| MSI                     | 106       | 3.06%   |
| Fujitsu                 | 72        | 2.08%   |
| Fujitsu Siemens         | 59        | 1.7%    |
| Toshiba                 | 53        | 1.53%   |
| Samsung Electronics     | 37        | 1.07%   |
| Packard Bell            | 29        | 0.84%   |
| Intel                   | 27        | 0.78%   |
| Medion                  | 22        | 0.63%   |
| eMachines               | 20        | 0.58%   |
| Apple                   | 18        | 0.52%   |
| Unknown                 | 18        | 0.52%   |
| Foxconn                 | 14        | 0.4%    |
| Sony                    | 13        | 0.38%   |
| Raspberry Pi Foundation | 7         | 0.2%    |
| Hungaro Flotta Kft      | 7         | 0.2%    |
| Alcor                   | 7         | 0.2%    |
| HUAWEI                  | 6         | 0.17%   |
| Pegatron                | 5         | 0.14%   |
| Supermicro              | 4         | 0.12%   |
| Biostar                 | 4         | 0.12%   |
| Timi                    | 3         | 0.09%   |
| Microsoft               | 3         | 0.09%   |
| Insyde                  | 3         | 0.09%   |
| Clevo                   | 3         | 0.09%   |
| AOpen                   | 3         | 0.09%   |
| AMI                     | 3         | 0.09%   |
| ABIT                    | 3         | 0.09%   |
| ZOTAC                   | 2         | 0.06%   |
| VXL                     | 2         | 0.06%   |
| Valve                   | 2         | 0.06%   |
| TUXEDO                  | 2         | 0.06%   |
| speedmaster             | 2         | 0.06%   |
| Shuttle                 | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 1.18%   |
| ASRock FM2A75M Pro4+                 | 33        | 0.95%   |
| ASUS All Series                      | 28        | 0.81%   |
| Unknown                              | 28        | 0.81%   |
| Dell OptiPlex 3020                   | 17        | 0.49%   |
| Dell Latitude E6410                  | 17        | 0.49%   |
| HP 650                               | 13        | 0.38%   |
| ASUS P5KPL-AM EPU                    | 12        | 0.35%   |
| Gigabyte G31M-ES2L                   | 11        | 0.32%   |
| Dell OptiPlex 755                    | 11        | 0.32%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 10        | 0.29%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 10        | 0.29%   |
| Lenovo G50-45 80E3                   | 10        | 0.29%   |
| HP Notebook                          | 10        | 0.29%   |
| HP 620                               | 10        | 0.29%   |
| Dell OptiPlex 780                    | 10        | 0.29%   |
| Dell OptiPlex 760                    | 9         | 0.26%   |
| Dell Latitude E6400                  | 9         | 0.26%   |
| Lenovo ThinkPad T400 2768WGB         | 8         | 0.23%   |
| HP Pavilion 15                       | 8         | 0.23%   |
| HP EliteBook 8460p                   | 8         | 0.23%   |
| Gigabyte H61M-S1                     | 8         | 0.23%   |
| Dell Precision WorkStation T3500     | 8         | 0.23%   |
| Dell OptiPlex 7010                   | 8         | 0.23%   |
| Dell Latitude E6530                  | 8         | 0.23%   |
| Dell Latitude E6420                  | 8         | 0.23%   |
| ASRock G41M-VS3                      | 8         | 0.23%   |
| Lenovo Z50-75 80EC                   | 7         | 0.2%    |
| Lenovo G550 20023                    | 7         | 0.2%    |
| HP ProDesk 600 G2 SFF                | 7         | 0.2%    |
| HP EliteBook 6930p                   | 7         | 0.2%    |
| Gigabyte 970A-DS3P                   | 7         | 0.2%    |
| Dell Inspiron 15-3567                | 7         | 0.2%    |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.2%    |
| ASRock N68C-S UCC                    | 7         | 0.2%    |
| Lenovo Z50-70 20354                  | 6         | 0.17%   |
| Lenovo G580 20150                    | 6         | 0.17%   |
| HP Pavilion g6                       | 6         | 0.17%   |
| HP EliteBook 8470p                   | 6         | 0.17%   |
| HP EliteBook 8440p                   | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 175       | 5.05%   |
| Dell Latitude           | 174       | 5.02%   |
| Acer Aspire             | 159       | 4.59%   |
| HP Compaq               | 123       | 3.55%   |
| Dell OptiPlex           | 114       | 3.29%   |
| Dell Inspiron           | 110       | 3.17%   |
| Lenovo IdeaPad          | 103       | 2.97%   |
| HP EliteBook            | 87        | 2.51%   |
| HP 250                  | 58        | 1.67%   |
| HP ProBook              | 56        | 1.62%   |
| ASUS VivoBook           | 56        | 1.62%   |
| Toshiba Satellite       | 47        | 1.36%   |
| Lenovo ThinkCentre      | 46        | 1.33%   |
| HP Pavilion             | 46        | 1.33%   |
| ASUS PRIME              | 39        | 1.13%   |
| Dell Vostro             | 33        | 0.95%   |
| ASRock FM2A75M          | 33        | 0.95%   |
| Fujitsu ESPRIMO         | 31        | 0.89%   |
| Packard Bell EasyNote   | 29        | 0.84%   |
| Fujitsu Siemens ESPRIMO | 28        | 0.81%   |
| ASUS All                | 28        | 0.81%   |
| Unknown                 | 28        | 0.81%   |
| Dell Precision          | 27        | 0.78%   |
| ASUS ROG                | 27        | 0.78%   |
| Fujitsu LIFEBOOK        | 26        | 0.75%   |
| Fujitsu Siemens AMILO   | 20        | 0.58%   |
| Acer TravelMate         | 19        | 0.55%   |
| ASUS TUF                | 17        | 0.49%   |
| ASUS P5KPL-AM           | 17        | 0.49%   |
| HP Laptop               | 16        | 0.46%   |
| Acer Veriton            | 16        | 0.46%   |
| Acer Swift              | 14        | 0.4%    |
| HP 650                  | 13        | 0.38%   |
| Gigabyte B450           | 13        | 0.38%   |
| Gigabyte G31M-ES2L      | 11        | 0.32%   |
| Lenovo G50-45           | 10        | 0.29%   |
| Lenovo 3000             | 10        | 0.29%   |
| HP ZBook                | 10        | 0.29%   |
| HP Notebook             | 10        | 0.29%   |
| HP 620                  | 10        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 327       | 9.44%   |
| 2011    | 326       | 9.41%   |
| 2012    | 305       | 8.8%    |
| 2010    | 304       | 8.77%   |
| 2018    | 266       | 7.68%   |
| 2014    | 252       | 7.27%   |
| 2009    | 246       | 7.1%    |
| 2008    | 245       | 7.07%   |
| 2015    | 191       | 5.51%   |
| 2017    | 181       | 5.22%   |
| 2016    | 179       | 5.17%   |
| 2007    | 179       | 5.17%   |
| 2019    | 143       | 4.13%   |
| 2020    | 115       | 3.32%   |
| 2006    | 77        | 2.22%   |
| 2021    | 61        | 1.76%   |
| 2005    | 28        | 0.81%   |
| 2022    | 21        | 0.61%   |
| Unknown | 12        | 0.35%   |
| 2004    | 4         | 0.12%   |
| 2003    | 3         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1946      | 56.16%  |
| Desktop        | 1422      | 41.04%  |
| Convertible    | 24        | 0.69%   |
| All in one     | 24        | 0.69%   |
| Mini pc        | 20        | 0.58%   |
| Server         | 11        | 0.32%   |
| System on chip | 9         | 0.26%   |
| Tablet         | 9         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3367      | 96.78%  |
| Enabled  | 112       | 3.22%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3465      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1134      | 31.72%  |
| 4.01-8.0    | 756       | 21.15%  |
| 8.01-16.0   | 620       | 17.34%  |
| 16.01-24.0  | 376       | 10.52%  |
| 1.01-2.0    | 346       | 9.68%   |
| 2.01-3.0    | 127       | 3.55%   |
| 32.01-64.0  | 122       | 3.41%   |
| 0.51-1.0    | 41        | 1.15%   |
| 24.01-32.0  | 26        | 0.73%   |
| 64.01-256.0 | 24        | 0.67%   |
| 0.01-0.5    | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 1284      | 31.7%   |
| 1.01-2.0    | 1205      | 29.75%  |
| 0.01-0.5    | 654       | 16.15%  |
| 2.01-3.0    | 444       | 10.96%  |
| 3.01-4.0    | 204       | 5.04%   |
| 4.01-8.0    | 193       | 4.77%   |
| 8.01-16.0   | 54        | 1.33%   |
| 16.01-24.0  | 9         | 0.22%   |
| 32.01-64.0  | 1         | 0.02%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2386      | 65.08%  |
| 2       | 815       | 22.23%  |
| 3       | 255       | 6.96%   |
| 4       | 94        | 2.56%   |
| 0       | 44        | 1.2%    |
| 5       | 43        | 1.17%   |
| 6       | 12        | 0.33%   |
| 8       | 5         | 0.14%   |
| 7       | 5         | 0.14%   |
| 9       | 3         | 0.08%   |
| 14      | 1         | 0.03%   |
| 11      | 1         | 0.03%   |
| 10      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1970      | 55.71%  |
| No        | 1566      | 44.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3232      | 93.11%  |
| No        | 239       | 6.89%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2370      | 67.75%  |
| No        | 1128      | 32.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1819      | 51.69%  |
| Yes       | 1700      | 48.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Hungary | 3465      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Budapest          | 1347      | 33.52%  |
| Pécs             | 87        | 2.17%   |
| Szeged            | 85        | 2.12%   |
| Miskolc           | 78        | 1.94%   |
| Debrecen          | 77        | 1.92%   |
| Győr             | 75        | 1.87%   |
| Tatabánya        | 65        | 1.62%   |
| Székesfehérvár | 54        | 1.34%   |
| Kecskemét        | 50        | 1.24%   |
| Szombathely       | 49        | 1.22%   |
| Érd              | 42        | 1.05%   |
| Nyiregyhaza       | 38        | 0.95%   |
| Szigetszentmiklos | 36        | 0.9%    |
| Veszprém         | 35        | 0.87%   |
| Szekszárd        | 35        | 0.87%   |
| Zalaegerszeg      | 32        | 0.8%    |
| Karcag            | 31        | 0.77%   |
| Dunaújváros     | 26        | 0.65%   |
| Szolnok           | 25        | 0.62%   |
| Oroshaza          | 25        | 0.62%   |
| Gödöllő        | 25        | 0.62%   |
| Eger              | 22        | 0.55%   |
| Nagykanizsa       | 21        | 0.52%   |
| Salgotarjan       | 20        | 0.5%    |
| Hodmezovasarhely  | 20        | 0.5%    |
| Toekoel           | 19        | 0.47%   |
| Sopron            | 19        | 0.47%   |
| Gyomro            | 19        | 0.47%   |
| Toeroekbalint     | 18        | 0.45%   |
| Hatvan            | 18        | 0.45%   |
| Esztergom         | 18        | 0.45%   |
| Ajka              | 18        | 0.45%   |
| Mosonmagyaróvár | 17        | 0.42%   |
| Berettyóújfalu  | 17        | 0.42%   |
| Siófok           | 16        | 0.4%    |
| Pomaz             | 16        | 0.4%    |
| Kazincbarcika     | 16        | 0.4%    |
| Szorgalmatos      | 15        | 0.37%   |
| Kaposvár         | 15        | 0.37%   |
| Veresegyhaz       | 14        | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 852       | 1471   | 16.98%  |
| Seagate             | 739       | 1138   | 14.73%  |
| Samsung Electronics | 690       | 1083   | 13.75%  |
| Kingston            | 593       | 948    | 11.82%  |
| Toshiba             | 451       | 707    | 8.99%   |
| Hitachi             | 246       | 335    | 4.9%    |
| HGST                | 151       | 225    | 3.01%   |
| SanDisk             | 131       | 196    | 2.61%   |
| Unknown             | 122       | 169    | 2.43%   |
| A-DATA Technology   | 110       | 165    | 2.19%   |
| Intel               | 83        | 125    | 1.65%   |
| SK hynix            | 77        | 112    | 1.53%   |
| Crucial             | 66        | 105    | 1.32%   |
| Fujitsu             | 60        | 72     | 1.2%    |
| SPCC                | 51        | 68     | 1.02%   |
| Maxtor              | 48        | 63     | 0.96%   |
| Micron Technology   | 46        | 59     | 0.92%   |
| Apacer              | 35        | 54     | 0.7%    |
| China               | 26        | 42     | 0.52%   |
| OCZ                 | 25        | 31     | 0.5%    |
| JMicron Technology  | 25        | 28     | 0.5%    |
| Intenso             | 21        | 32     | 0.42%   |
| Transcend           | 20        | 22     | 0.4%    |
| LITEON              | 20        | 25     | 0.4%    |
| Patriot             | 19        | 31     | 0.38%   |
| Kingmax             | 19        | 29     | 0.38%   |
| Gigabyte Technology | 19        | 41     | 0.38%   |
| PNY                 | 18        | 30     | 0.36%   |
| KingSpec            | 15        | 17     | 0.3%    |
| Hewlett-Packard     | 13        | 17     | 0.26%   |
| KIOXIA              | 12        | 13     | 0.24%   |
| Phison              | 11        | 15     | 0.22%   |
| Apple               | 11        | 15     | 0.22%   |
| Team                | 10        | 15     | 0.2%    |
| Corsair             | 9         | 11     | 0.18%   |
| Zheino              | 8         | 12     | 0.16%   |
| Verbatim            | 8         | 15     | 0.16%   |
| LITEONIT            | 8         | 10     | 0.16%   |
| ASMT                | 8         | 10     | 0.16%   |
| Silicon Motion      | 7         | 9      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 137       | 2.52%   |
| Kingston SA400S37120G 120GB SSD    | 121       | 2.22%   |
| Kingston SV300S37A120G 120GB SSD   | 89        | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB     | 55        | 1.01%   |
| Toshiba DT01ACA100 1TB             | 51        | 0.94%   |
| Kingston SA400S37480G 480GB SSD    | 49        | 0.9%    |
| Toshiba MQ01ABF050 500GB           | 47        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB    | 46        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 46        | 0.85%   |
| Toshiba MQ01ABD100 1TB             | 44        | 0.81%   |
| Seagate ST500LT012-1DG142 500GB    | 39        | 0.72%   |
| Kingston SUV400S37120G 120GB SSD   | 37        | 0.68%   |
| Samsung SSD 850 EVO 250GB          | 36        | 0.66%   |
| Toshiba DT01ACA050 500GB           | 33        | 0.61%   |
| HGST HTS545032A7E380 320GB         | 32        | 0.59%   |
| A-DATA SU630 240GB SSD             | 30        | 0.55%   |
| Toshiba MQ04ABF100 1TB             | 29        | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 28        | 0.51%   |
| HGST HTS545050A7E680 500GB         | 28        | 0.51%   |
| Samsung SSD 860 EVO 250GB          | 25        | 0.46%   |
| Seagate ST380815AS 80GB            | 24        | 0.44%   |
| Toshiba HDWD130 3TB                | 23        | 0.42%   |
| Samsung SSD 860 EVO 500GB          | 23        | 0.42%   |
| HGST HTS721010A9E630 1TB           | 23        | 0.42%   |
| Toshiba HDWD110 1TB                | 22        | 0.4%    |
| Seagate ST9320325AS 320GB          | 22        | 0.4%    |
| Samsung HD502HJ 500GB              | 22        | 0.4%    |
| A-DATA SU700 120GB SSD             | 22        | 0.4%    |
| Kingston SHFS37A120G 120GB SSD     | 21        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB           | 20        | 0.37%   |
| Samsung SSD 850 EVO 500GB          | 19        | 0.35%   |
| SPCC Solid State Disk 256GB        | 18        | 0.33%   |
| Seagate ST9500325AS 500GB          | 18        | 0.33%   |
| Toshiba DT01ACA200 2TB             | 17        | 0.31%   |
| Seagate ST9250315AS 250GB          | 17        | 0.31%   |
| Kingston SV300S37A240G 240GB SSD   | 17        | 0.31%   |
| JMicron Generic 500GB              | 17        | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 0.29%   |
| HGST HTS541010A9E680 1TB           | 16        | 0.29%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 15        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 755       | 1287   | 27.91%  |
| Seagate             | 725       | 1113   | 26.8%   |
| Toshiba             | 400       | 623    | 14.79%  |
| Samsung Electronics | 266       | 400    | 9.83%   |
| Hitachi             | 246       | 335    | 9.09%   |
| HGST                | 151       | 225    | 5.58%   |
| Fujitsu             | 60        | 72     | 2.22%   |
| Maxtor              | 48        | 63     | 1.77%   |
| Unknown             | 13        | 17     | 0.48%   |
| Hewlett-Packard     | 7         | 7      | 0.26%   |
| ASMT                | 7         | 9      | 0.26%   |
| HGST HTS            | 5         | 10     | 0.18%   |
| USB3.0              | 4         | 8      | 0.15%   |
| IBM/Hitachi         | 4         | 5      | 0.15%   |
| Quantum             | 3         | 3      | 0.11%   |
| Apple               | 3         | 5      | 0.11%   |
| WD MediaMax         | 2         | 4      | 0.07%   |
| ICY BOX             | 2         | 3      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 546       | 865    | 31.18%  |
| Samsung Electronics | 312       | 457    | 17.82%  |
| A-DATA Technology   | 104       | 155    | 5.94%   |
| SanDisk             | 93        | 131    | 5.31%   |
| WDC                 | 86        | 143    | 4.91%   |
| Crucial             | 62        | 99     | 3.54%   |
| Intel               | 56        | 85     | 3.2%    |
| SPCC                | 42        | 58     | 2.4%    |
| SK hynix            | 39        | 62     | 2.23%   |
| Micron Technology   | 34        | 42     | 1.94%   |
| Apacer              | 34        | 53     | 1.94%   |
| China               | 26        | 42     | 1.48%   |
| OCZ                 | 25        | 31     | 1.43%   |
| Toshiba             | 23        | 36     | 1.31%   |
| LITEON              | 20        | 25     | 1.14%   |
| Transcend           | 19        | 21     | 1.09%   |
| Kingmax             | 19        | 29     | 1.09%   |
| PNY                 | 18        | 30     | 1.03%   |
| Intenso             | 18        | 29     | 1.03%   |
| Patriot             | 17        | 28     | 0.97%   |
| JMicron Technology  | 17        | 19     | 0.97%   |
| Gigabyte Technology | 16        | 37     | 0.91%   |
| KingSpec            | 14        | 16     | 0.8%    |
| Team                | 9         | 14     | 0.51%   |
| Verbatim            | 8         | 15     | 0.46%   |
| LITEONIT            | 8         | 10     | 0.46%   |
| Corsair             | 8         | 10     | 0.46%   |
| GOODRAM             | 7         | 8      | 0.4%    |
| Apple               | 6         | 6      | 0.34%   |
| Netac               | 5         | 10     | 0.29%   |
| Hewlett-Packard     | 4         | 5      | 0.23%   |
| Unknown             | 3         | 6      | 0.17%   |
| SATAFIRM            | 3         | 3      | 0.17%   |
| Leven               | 3         | 3      | 0.17%   |
| KingDian            | 3         | 3      | 0.17%   |
| HS-SSD-C100         | 3         | 3      | 0.17%   |
| BHT                 | 3         | 3      | 0.17%   |
| AMD                 | 3         | 3      | 0.17%   |
| WDC WDS             | 2         | 2      | 0.11%   |
| TO Exter            | 2         | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2283      | 4193   | 51.45%  |
| SSD     | 1553      | 2646   | 35%     |
| NVMe    | 430       | 670    | 9.69%   |
| MMC     | 117       | 172    | 2.64%   |
| Unknown | 54        | 68     | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3126      | 6670   | 81.88%  |
| NVMe | 429       | 669    | 11.24%  |
| SAS  | 146       | 238    | 3.82%   |
| MMC  | 117       | 172    | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2712      | 4960   | 72.28%  |
| 0.51-1.0   | 782       | 1343   | 20.84%  |
| 1.01-2.0   | 151       | 247    | 4.02%   |
| 2.01-3.0   | 50        | 138    | 1.33%   |
| 3.01-4.0   | 35        | 84     | 0.93%   |
| 4.01-10.0  | 16        | 38     | 0.43%   |
| 10.01-20.0 | 6         | 29     | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1426      | 35.72%  |
| 101-250        | 860       | 21.54%  |
| 251-500        | 544       | 13.63%  |
| 51-100         | 298       | 7.46%   |
| 501-1000       | 259       | 6.49%   |
| 1-20           | 180       | 4.51%   |
| 21-50          | 164       | 4.11%   |
| 1001-2000      | 142       | 3.56%   |
| More than 3000 | 64        | 1.6%    |
| 2001-3000      | 55        | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1426      | 35.37%  |
| 1-20           | 1420      | 35.22%  |
| 21-50          | 356       | 8.83%   |
| 51-100         | 265       | 6.57%   |
| 101-250        | 235       | 5.83%   |
| 251-500        | 125       | 3.1%    |
| 501-1000       | 109       | 2.7%    |
| 1001-2000      | 62        | 1.54%   |
| More than 3000 | 22        | 0.55%   |
| 2001-3000      | 12        | 0.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB          | 30        | 41     | 2.97%   |
| Kingston SV300S37A120G 120GB SSD    | 19        | 22     | 1.88%   |
| HGST HTS545050A7E680 500GB          | 19        | 29     | 1.88%   |
| A-DATA Technology SU630 240GB SSD   | 18        | 21     | 1.78%   |
| Seagate ST500DM002-1BD142 500GB     | 16        | 30     | 1.58%   |
| Seagate ST9320325AS 320GB           | 11        | 23     | 1.09%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 13     | 1.09%   |
| Seagate ST500LT012-1DG142 500GB     | 11        | 14     | 1.09%   |
| Samsung Electronics HD103UJ 1TB     | 10        | 17     | 0.99%   |
| Toshiba MQ01ABF050 500GB            | 9         | 23     | 0.89%   |
| Seagate ST9250315AS 250GB           | 9         | 14     | 0.89%   |
| Toshiba DT01ACA050 500GB            | 8         | 9      | 0.79%   |
| Seagate ST9500325AS 500GB           | 8         | 13     | 0.79%   |
| Seagate ST9320423AS 320GB           | 8         | 9      | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8         | 12     | 0.79%   |
| HGST HTS541010A9E680 1TB            | 8         | 16     | 0.79%   |
| Toshiba MQ01ABD100 1TB              | 7         | 8      | 0.69%   |
| Samsung Electronics HM160HI 160GB   | 7         | 8      | 0.69%   |
| Hitachi HTS545050B9A300 500GB       | 7         | 8      | 0.69%   |
| WDC WD5000AAKX-001CA0 500GB         | 6         | 6      | 0.59%   |
| WDC WD5000AADS-00S9B0 500GB         | 6         | 7      | 0.59%   |
| Toshiba DT01ACA100 1TB              | 6         | 12     | 0.59%   |
| Toshiba MQ01ABD050 500GB            | 5         | 5      | 0.5%    |
| Seagate ST980811AS 80GB             | 5         | 5      | 0.5%    |
| Seagate ST3250318AS 249GB           | 5         | 8      | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 5      | 0.5%    |
| Samsung Electronics HD502HJ 500GB   | 5         | 8      | 0.5%    |
| Samsung Electronics HD321KJ 320GB   | 5         | 5      | 0.5%    |
| Samsung Electronics HD161HJ 160GB   | 5         | 5      | 0.5%    |
| Samsung Electronics HD103SI 1TB     | 5         | 5      | 0.5%    |
| Maxtor 6Y080M0 81GB                 | 5         | 6      | 0.5%    |
| Hitachi HTS547550A9E384 500GB       | 5         | 14     | 0.5%    |
| Hitachi HTS545050A7E380 500GB       | 5         | 7      | 0.5%    |
| Hitachi HTS545032B9A300 320GB       | 5         | 6      | 0.5%    |
| Hitachi HTS545016B9A300 160GB       | 5         | 5      | 0.5%    |
| Hitachi HTS541680J9SA00 80GB        | 5         | 5      | 0.5%    |
| HGST HTS545050A7E380 500GB          | 5         | 9      | 0.5%    |
| WDC WD5000AAKS-00UU3A0 500GB        | 4         | 7      | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB            | 4         | 7      | 0.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 6      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 216       | 304    | 21.95%  |
| WDC                 | 197       | 298    | 20.02%  |
| Samsung Electronics | 113       | 161    | 11.48%  |
| Hitachi             | 108       | 155    | 10.98%  |
| Toshiba             | 101       | 146    | 10.26%  |
| HGST                | 73        | 108    | 7.42%   |
| Kingston            | 46        | 58     | 4.67%   |
| Maxtor              | 26        | 40     | 2.64%   |
| A-DATA Technology   | 25        | 33     | 2.54%   |
| Fujitsu             | 20        | 27     | 2.03%   |
| Intel               | 14        | 21     | 1.42%   |
| SK hynix            | 9         | 13     | 0.91%   |
| SanDisk             | 4         | 5      | 0.41%   |
| IBM/Hitachi         | 3         | 3      | 0.3%    |
| Hewlett-Packard     | 3         | 3      | 0.3%    |
| WD MediaMax         | 2         | 4      | 0.2%    |
| LITEON              | 2         | 2      | 0.2%    |
| KingSpec            | 2         | 2      | 0.2%    |
| Kingmax             | 2         | 2      | 0.2%    |
| Intenso             | 2         | 2      | 0.2%    |
| Apacer              | 2         | 3      | 0.2%    |
| SPCC                | 1         | 1      | 0.1%    |
| SATAFIRM            | 1         | 1      | 0.1%    |
| R580                | 1         | 1      | 0.1%    |
| OCZ                 | 1         | 3      | 0.1%    |
| Micron Technology   | 1         | 1      | 0.1%    |
| Leven               | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| Initio              | 1         | 1      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| Crucial             | 1         | 1      | 0.1%    |
| China               | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |
| Apple               | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 216       | 304    | 25.5%   |
| WDC                 | 193       | 294    | 22.79%  |
| Hitachi             | 108       | 155    | 12.75%  |
| Samsung Electronics | 106       | 152    | 12.51%  |
| Toshiba             | 95        | 133    | 11.22%  |
| HGST                | 73        | 108    | 8.62%   |
| Maxtor              | 26        | 40     | 3.07%   |
| Fujitsu             | 20        | 27     | 2.36%   |
| IBM/Hitachi         | 3         | 3      | 0.35%   |
| WD MediaMax         | 2         | 4      | 0.24%   |
| Hewlett-Packard     | 2         | 2      | 0.24%   |
| ICY BOX             | 1         | 1      | 0.12%   |
| ExcelStor           | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 776       | 1225   | 85.18%  |
| SSD     | 129       | 174    | 14.16%  |
| NVMe    | 5         | 6      | 0.55%   |
| Unknown | 1         | 1      | 0.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB  | 2         | 2      | 9.09%   |
| Zheino CHN-NGFFNV2280-256 256GB    | 1         | 1      | 4.55%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.55%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.55%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.55%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.55%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.55%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.55%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 4.55%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.55%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 4.55%   |
| Seagate ST380815AS 80GB            | 1         | 3      | 4.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.55%   |
| Samsung Electronics SP0802N 80GB   | 1         | 1      | 4.55%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.55%   |
| Samsung Electronics HD204UI 2TB    | 1         | 1      | 4.55%   |
| Samsung Electronics HD103SJ 1TB    | 1         | 2      | 4.55%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 4.55%   |
| Hitachi HDS721075CLA332 752GB      | 1         | 1      | 4.55%   |
| Hewlett-Packard SSD EX900 250GB    | 1         | 1      | 4.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 12     | 27.27%  |
| Samsung Electronics | 6         | 7      | 27.27%  |
| Toshiba             | 3         | 3      | 13.64%  |
| Seagate             | 3         | 5      | 13.64%  |
| Hitachi             | 2         | 2      | 9.09%   |
| Zheino              | 1         | 1      | 4.55%   |
| Hewlett-Packard     | 1         | 1      | 4.55%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2049      | 4247   | 51.26%  |
| Detected | 1039      | 2065   | 25.99%  |
| Malfunc  | 887       | 1406   | 22.19%  |
| Failed   | 22        | 31     | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2612      | 65.4%   |
| AMD                              | 620       | 15.52%  |
| Samsung Electronics              | 156       | 3.91%   |
| JMicron Technology               | 79        | 1.98%   |
| Nvidia                           | 70        | 1.75%   |
| SanDisk                          | 63        | 1.58%   |
| ASMedia Technology               | 61        | 1.53%   |
| Kingston Technology Company      | 59        | 1.48%   |
| SK hynix                         | 35        | 0.88%   |
| Marvell Technology Group         | 35        | 0.88%   |
| Phison Electronics               | 28        | 0.7%    |
| Toshiba America Info Systems     | 26        | 0.65%   |
| VIA Technologies                 | 21        | 0.53%   |
| KIOXIA                           | 18        | 0.45%   |
| Silicon Motion                   | 17        | 0.43%   |
| Silicon Integrated Systems [SiS] | 14        | 0.35%   |
| Micron Technology                | 13        | 0.33%   |
| Silicon Image                    | 12        | 0.3%    |
| LSI Logic / Symbios Logic        | 11        | 0.28%   |
| ADATA Technology                 | 8         | 0.2%    |
| Micron/Crucial Technology        | 6         | 0.15%   |
| Solid State Storage Technology   | 5         | 0.13%   |
| Integrated Technology Express    | 4         | 0.1%    |
| Seagate Technology               | 3         | 0.08%   |
| Broadcom / LSI                   | 3         | 0.08%   |
| Realtek Semiconductor            | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Promise Technology               | 1         | 0.03%   |
| OCZ Technology Group             | 1         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.03%   |
| Lite-On Technology               | 1         | 0.03%   |
| Initio                           | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |
| 3ware                            | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 374       | 7.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 197       | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 172       | 3.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 170       | 3.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 170       | 3.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 165       | 3.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 138       | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 124       | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 115       | 2.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 104       | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 95        | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 88        | 1.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 86        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 85        | 1.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 83        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 78        | 1.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 73        | 1.45%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 72        | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 71        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 71        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 68        | 1.35%   |
| AMD FCH IDE Controller                                                                  | 68        | 1.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 61        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 57        | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 54        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 50        | 1%      |
| Intel 4 Series Chipset PT IDER Controller                                               | 49        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 47        | 0.94%   |
| Intel SATA Controller [RAID mode]                                                       | 46        | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 46        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 46        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 46        | 0.92%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 45        | 0.9%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 45        | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 44        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 37        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 37        | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 36        | 0.72%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 35        | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 35        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2608      | 61.15%  |
| IDE  | 981       | 23%     |
| NVMe | 436       | 10.22%  |
| RAID | 223       | 5.23%   |
| SAS  | 9         | 0.21%   |
| SCSI | 8         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2734      | 78.9%   |
| AMD          | 718       | 20.72%  |
| ARM          | 9         | 0.26%   |
| CentaurHauls | 4         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 46        | 1.32%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 1.21%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 38        | 1.09%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 36        | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 32        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 32        | 0.92%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27        | 0.78%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 25        | 0.72%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 25        | 0.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 22        | 0.63%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 20        | 0.58%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 20        | 0.58%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 20        | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 19        | 0.55%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 19        | 0.55%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 19        | 0.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 19        | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.52%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 18        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 17        | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 17        | 0.49%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 17        | 0.49%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 17        | 0.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 16        | 0.46%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 16        | 0.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 16        | 0.46%   |
| AMD FX-8350 Eight-Core Processor            | 16        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 15        | 0.43%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 15        | 0.43%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 15        | 0.43%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 15        | 0.43%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 15        | 0.43%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15        | 0.43%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 14        | 0.4%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 14        | 0.4%    |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 14        | 0.4%    |
| Intel Core i3-4160 CPU @ 3.60GHz            | 14        | 0.4%    |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 14        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 735       | 21.16%  |
| Intel Core i3           | 392       | 11.28%  |
| Intel Core i7           | 322       | 9.27%   |
| Intel Core 2 Duo        | 314       | 9.04%   |
| Intel Celeron           | 259       | 7.46%   |
| Intel Pentium           | 153       | 4.4%    |
| Intel Pentium Dual-Core | 95        | 2.73%   |
| AMD Ryzen 5             | 89        | 2.56%   |
| Intel Atom              | 88        | 2.53%   |
| AMD A8                  | 79        | 2.27%   |
| Intel Xeon              | 64        | 1.84%   |
| Other                   | 58        | 1.67%   |
| Intel Core 2 Quad       | 53        | 1.53%   |
| AMD FX                  | 53        | 1.53%   |
| AMD Ryzen 7             | 51        | 1.47%   |
| AMD A4                  | 48        | 1.38%   |
| Intel Core 2            | 45        | 1.3%    |
| Intel Pentium Dual      | 44        | 1.27%   |
| AMD Athlon II X2        | 37        | 1.07%   |
| AMD Ryzen 3             | 35        | 1.01%   |
| AMD Athlon 64 X2        | 31        | 0.89%   |
| AMD A6                  | 31        | 0.89%   |
| AMD A10                 | 24        | 0.69%   |
| Intel Genuine           | 21        | 0.6%    |
| Intel Pentium 4         | 19        | 0.55%   |
| AMD Phenom II X4        | 19        | 0.55%   |
| AMD E1                  | 17        | 0.49%   |
| AMD E                   | 17        | 0.49%   |
| Intel Pentium Silver    | 14        | 0.4%    |
| AMD E2                  | 14        | 0.4%    |
| Intel Celeron M         | 13        | 0.37%   |
| Intel Celeron Dual-Core | 13        | 0.37%   |
| Intel Pentium D         | 12        | 0.35%   |
| AMD Ryzen 9             | 12        | 0.35%   |
| AMD Sempron             | 11        | 0.32%   |
| AMD Athlon II X4        | 10        | 0.29%   |
| AMD Athlon Dual Core    | 10        | 0.29%   |
| AMD Athlon              | 10        | 0.29%   |
| Intel Pentium M         | 9         | 0.26%   |
| AMD Athlon X4           | 9         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2053      | 58.99%  |
| 4       | 907       | 26.06%  |
| 1       | 221       | 6.35%   |
| 6       | 172       | 4.94%   |
| 8       | 77        | 2.21%   |
| 3       | 26        | 0.75%   |
| 12      | 9         | 0.26%   |
| 16      | 7         | 0.2%    |
| 10      | 3         | 0.09%   |
| 14      | 2         | 0.06%   |
| 28      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3453      | 99.62%  |
| 2      | 13        | 0.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1775      | 50.98%  |
| 2       | 1706      | 48.99%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3367      | 96.86%  |
| 32-bit         | 62        | 1.78%   |
| Unknown        | 47        | 1.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 396       | 11.07%  |
| 0x1067a    | 308       | 8.61%   |
| 0x206a7    | 283       | 7.91%   |
| 0x306a9    | 264       | 7.38%   |
| 0x306c3    | 175       | 4.89%   |
| 0x20655    | 115       | 3.22%   |
| 0x6fd      | 100       | 2.8%    |
| 0x06001119 | 89        | 2.49%   |
| 0x40651    | 84        | 2.35%   |
| 0x10676    | 76        | 2.13%   |
| 0x306d4    | 74        | 2.07%   |
| 0x406e3    | 73        | 2.04%   |
| 0x506e3    | 67        | 1.87%   |
| 0x906ea    | 66        | 1.85%   |
| 0x806e9    | 57        | 1.59%   |
| 0x010000c8 | 56        | 1.57%   |
| 0x906e9    | 53        | 1.48%   |
| 0x806ea    | 52        | 1.45%   |
| 0x406c4    | 50        | 1.4%    |
| 0x6fb      | 48        | 1.34%   |
| 0x20652    | 39        | 1.09%   |
| 0x806ec    | 38        | 1.06%   |
| 0x106ca    | 36        | 1.01%   |
| 0x706a1    | 34        | 0.95%   |
| 0x30678    | 30        | 0.84%   |
| 0x0800820d | 29        | 0.81%   |
| 0x05000119 | 29        | 0.81%   |
| 0x506c9    | 28        | 0.78%   |
| 0x806c1    | 27        | 0.76%   |
| 0x6f2      | 26        | 0.73%   |
| 0x07030105 | 25        | 0.7%    |
| 0x6f6      | 24        | 0.67%   |
| 0x06000852 | 24        | 0.67%   |
| 0x106c2    | 23        | 0.64%   |
| 0x806eb    | 22        | 0.62%   |
| 0x406c3    | 22        | 0.62%   |
| 0x0700010f | 22        | 0.62%   |
| 0x06003106 | 22        | 0.62%   |
| 0x106e5    | 20        | 0.56%   |
| 0x706e5    | 19        | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 405       | 11.68%  |
| KabyLake         | 356       | 10.27%  |
| SandyBridge      | 306       | 8.83%   |
| Haswell          | 290       | 8.37%   |
| IvyBridge        | 278       | 8.02%   |
| Core             | 224       | 6.46%   |
| Westmere         | 171       | 4.93%   |
| Skylake          | 164       | 4.73%   |
| Piledriver       | 134       | 3.87%   |
| Silvermont       | 112       | 3.23%   |
| K10              | 111       | 3.2%    |
| Broadwell        | 85        | 2.45%   |
| K8 Hammer        | 66        | 1.9%    |
| Bonnell          | 65        | 1.88%   |
| Zen 2            | 57        | 1.64%   |
| Zen+             | 56        | 1.62%   |
| Goldmont plus    | 46        | 1.33%   |
| Zen              | 44        | 1.27%   |
| NetBurst         | 44        | 1.27%   |
| Bobcat           | 43        | 1.24%   |
| Puma             | 41        | 1.18%   |
| Steamroller      | 33        | 0.95%   |
| P6               | 33        | 0.95%   |
| Goldmont         | 33        | 0.95%   |
| Unknown          | 33        | 0.95%   |
| Excavator        | 32        | 0.92%   |
| Nehalem          | 31        | 0.89%   |
| Zen 3            | 28        | 0.81%   |
| TigerLake        | 28        | 0.81%   |
| Jaguar           | 27        | 0.78%   |
| IceLake          | 27        | 0.78%   |
| CometLake        | 22        | 0.63%   |
| K10 Llano        | 17        | 0.49%   |
| Bulldozer        | 9         | 0.26%   |
| Alderlake Hybrid | 8         | 0.23%   |
| K8 & K10 hybrid  | 5         | 0.14%   |
| Tremont          | 1         | 0.03%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2055      | 51.36%  |
| Nvidia                                       | 987       | 24.67%  |
| AMD                                          | 926       | 23.14%  |
| VIA Technologies                             | 13        | 0.32%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.17%   |
| ASPEED Technology                            | 5         | 0.12%   |
| Matrox Electronics Systems                   | 4         | 0.1%    |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.05%   |
| ATI Technologies                             | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 224       | 5.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 172       | 4.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 140       | 3.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 103       | 2.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 89        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 79        | 1.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 76        | 1.8%    |
| Intel HD Graphics 5500                                                                   | 74        | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 74        | 1.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 72        | 1.7%    |
| Intel HD Graphics 620                                                                    | 68        | 1.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 58        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 56        | 1.32%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.3%    |
| Intel HD Graphics 530                                                                    | 53        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 51        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 51        | 1.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 47        | 1.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 47        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 42        | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                               | 41        | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 39        | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 38        | 0.9%    |
| AMD Richland [Radeon HD 8570D]                                                           | 37        | 0.87%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 37        | 0.87%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 35        | 0.83%   |
| Intel HD Graphics 630                                                                    | 34        | 0.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 33        | 0.78%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 33        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 32        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 28        | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 28        | 0.66%   |
| AMD Renoir                                                                               | 28        | 0.66%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 27        | 0.64%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 26        | 0.61%   |
| Intel HD Graphics 500                                                                    | 26        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 26        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| 1 x Intel           | 1572      | 44.85%  |
| 1 x AMD             | 700       | 19.97%  |
| 1 x Nvidia          | 603       | 17.2%   |
| Intel + Nvidia      | 355       | 10.13%  |
| Intel + AMD         | 102       | 2.91%   |
| 2 x AMD             | 101       | 2.88%   |
| AMD + Nvidia        | 26        | 0.74%   |
| 1 x VIA             | 13        | 0.37%   |
| Other               | 10        | 0.29%   |
| 1 x SiS             | 7         | 0.2%    |
| 1 x Matrox          | 4         | 0.11%   |
| 1 x ASPEED          | 4         | 0.11%   |
| 2 x Nvidia          | 3         | 0.09%   |
| AMD + XGI           | 2         | 0.06%   |
| 1 x Intel + 3 x AMD | 1         | 0.03%   |
| Intel + 2 x Nvidia  | 1         | 0.03%   |
| AMD + ASPEED        | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3146      | 89.91%  |
| Proprietary | 252       | 7.2%    |
| Unknown     | 101       | 2.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1742      | 48.44%  |
| 0.01-0.5   | 630       | 17.52%  |
| 1.01-2.0   | 498       | 13.85%  |
| 0.51-1.0   | 421       | 11.71%  |
| 3.01-4.0   | 179       | 4.98%   |
| 7.01-8.0   | 55        | 1.53%   |
| 5.01-6.0   | 45        | 1.25%   |
| 2.01-3.0   | 21        | 0.58%   |
| 8.01-16.0  | 3         | 0.08%   |
| 16.01-24.0 | 2         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 638       | 17.71%  |
| LG Display              | 421       | 11.69%  |
| AU Optronics            | 413       | 11.47%  |
| Goldstar                | 297       | 8.25%   |
| Chimei Innolux          | 259       | 7.19%   |
| BOE                     | 216       | 6%      |
| Dell                    | 140       | 3.89%   |
| Chi Mei Optoelectronics | 100       | 2.78%   |
| Lenovo                  | 98        | 2.72%   |
| Philips                 | 93        | 2.58%   |
| Ancor Communications    | 92        | 2.55%   |
| BenQ                    | 85        | 2.36%   |
| Acer                    | 81        | 2.25%   |
| Hewlett-Packard         | 78        | 2.17%   |
| Fujitsu Siemens         | 45        | 1.25%   |
| LG Philips              | 37        | 1.03%   |
| AOC                     | 34        | 0.94%   |
| HannStar                | 29        | 0.81%   |
| Eizo                    | 25        | 0.69%   |
| Sony                    | 24        | 0.67%   |
| InfoVision              | 24        | 0.67%   |
| ASUSTek Computer        | 22        | 0.61%   |
| LG Electronics          | 20        | 0.56%   |
| HKC                     | 17        | 0.47%   |
| Vestel Elektronik       | 16        | 0.44%   |
| NEC Computers           | 16        | 0.44%   |
| Apple                   | 16        | 0.44%   |
| PANDA                   | 14        | 0.39%   |
| CPT                     | 14        | 0.39%   |
| ViewSonic               | 13        | 0.36%   |
| Toshiba                 | 13        | 0.36%   |
| IBM                     | 13        | 0.36%   |
| Medion                  | 12        | 0.33%   |
| Belinea                 | 11        | 0.31%   |
| Sharp                   | 10        | 0.28%   |
| Panasonic               | 10        | 0.28%   |
| Unknown                 | 9         | 0.25%   |
| Quanta Display          | 8         | 0.22%   |
| InnoLux Display         | 8         | 0.22%   |
| Arnos Instruments       | 8         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 49        | 1.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 37        | 1.01%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 0.93%   |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 31        | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 24        | 0.65%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.65%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.57%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 19        | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.49%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch    | 16        | 0.44%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 14        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 14        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.35%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 12        | 0.33%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 12        | 0.33%   |
| HKC Monitor HKC1850 1360x768 409x230mm 18.5-inch                         | 12        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.33%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.33%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 12        | 0.33%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 11        | 0.3%    |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.3%    |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 11        | 0.3%    |
| HannStar HannsG HS191D HSD0013 1280x1024 376x301mm 19.0-inch             | 11        | 0.3%    |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 11        | 0.3%    |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.3%    |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch          | 11        | 0.3%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 10        | 0.27%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 10        | 0.27%   |
| Goldstar 2D HD LG TV GSM59CA 1366x768 510x290mm 23.1-inch                | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.27%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 10        | 0.27%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 10        | 0.27%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 9         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1212      | 34.77%  |
| 1366x768 (WXGA)    | 899       | 25.79%  |
| 1280x1024 (SXGA)   | 266       | 7.63%   |
| 1280x800 (WXGA)    | 168       | 4.82%   |
| 1440x900 (WXGA+)   | 160       | 4.59%   |
| 1600x900 (HD+)     | 152       | 4.36%   |
| 1680x1050 (WSXGA+) | 144       | 4.13%   |
| 3840x2160 (4K)     | 109       | 3.13%   |
| 1920x1200 (WUXGA)  | 57        | 1.64%   |
| 2560x1440 (QHD)    | 48        | 1.38%   |
| 1024x600           | 39        | 1.12%   |
| 1360x768           | 38        | 1.09%   |
| 1024x768 (XGA)     | 37        | 1.06%   |
| 2560x1080          | 32        | 0.92%   |
| Unknown            | 19        | 0.55%   |
| 1920x540           | 17        | 0.49%   |
| 2880x1800          | 10        | 0.29%   |
| 1600x1200          | 10        | 0.29%   |
| 3840x1080          | 7         | 0.2%    |
| 1280x720 (HD)      | 7         | 0.2%    |
| 3440x1440          | 6         | 0.17%   |
| 2560x1600          | 6         | 0.17%   |
| 2288x1287          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 2160x1440          | 3         | 0.09%   |
| 1400x1050          | 3         | 0.09%   |
| 800x1280           | 2         | 0.06%   |
| 3840x1200          | 2         | 0.06%   |
| 3280x1080          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 2048x1152          | 2         | 0.06%   |
| 1280x960           | 2         | 0.06%   |
| 1280x768           | 2         | 0.06%   |
| 7680x2160          | 1         | 0.03%   |
| 4093x4093          | 1         | 0.03%   |
| 3840x2400          | 1         | 0.03%   |
| 3840x1920          | 1         | 0.03%   |
| 3600x1200          | 1         | 0.03%   |
| 3200x1080          | 1         | 0.03%   |
| 2880x1620          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1179      | 32.79%  |
| 14      | 253       | 7.04%   |
| 17      | 252       | 7.01%   |
| 21      | 244       | 6.79%   |
| 19      | 228       | 6.34%   |
| 23      | 193       | 5.37%   |
| 13      | 177       | 4.92%   |
| 24      | 169       | 4.7%    |
| 27      | 148       | 4.12%   |
| 22      | 104       | 2.89%   |
| Unknown | 104       | 2.89%   |
| 18      | 99        | 2.75%   |
| 12      | 83        | 2.31%   |
| 20      | 50        | 1.39%   |
| 10      | 49        | 1.36%   |
| 11      | 38        | 1.06%   |
| 34      | 37        | 1.03%   |
| 84      | 30        | 0.83%   |
| 31      | 27        | 0.75%   |
| 40      | 21        | 0.58%   |
| 72      | 19        | 0.53%   |
| 32      | 13        | 0.36%   |
| 65      | 10        | 0.28%   |
| 54      | 9         | 0.25%   |
| 52      | 7         | 0.19%   |
| 42      | 6         | 0.17%   |
| 60      | 5         | 0.14%   |
| 16      | 5         | 0.14%   |
| 58      | 4         | 0.11%   |
| 46      | 4         | 0.11%   |
| 64      | 3         | 0.08%   |
| 48      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |
| 8       | 3         | 0.08%   |
| 55      | 2         | 0.06%   |
| 47      | 2         | 0.06%   |
| 33      | 2         | 0.06%   |
| 142     | 1         | 0.03%   |
| 75      | 1         | 0.03%   |
| 63      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1614      | 45.34%  |
| 401-500        | 573       | 16.1%   |
| 501-600        | 489       | 13.74%  |
| 351-400        | 307       | 8.62%   |
| 201-300        | 246       | 6.91%   |
| Unknown        | 104       | 2.92%   |
| 1001-1500      | 52        | 1.46%   |
| 701-800        | 51        | 1.43%   |
| 1501-2000      | 50        | 1.4%    |
| 601-700        | 36        | 1.01%   |
| 801-900        | 25        | 0.7%    |
| 901-1000       | 7         | 0.2%    |
| 101-200        | 5         | 0.14%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2374      | 70.8%   |
| 16/10   | 515       | 15.36%  |
| 5/4     | 257       | 7.66%   |
| Unknown | 77        | 2.3%    |
| 4/3     | 66        | 1.97%   |
| 21/9    | 37        | 1.1%    |
| 3/2     | 19        | 0.57%   |
| 6/5     | 4         | 0.12%   |
| 0.62    | 2         | 0.06%   |
| 32/9    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1164      | 32.54%  |
| 201-250        | 586       | 16.38%  |
| 81-90          | 362       | 10.12%  |
| 151-200        | 349       | 9.76%   |
| 141-150        | 210       | 5.87%   |
| 301-350        | 148       | 4.14%   |
| Unknown        | 104       | 2.91%   |
| More than 1000 | 96        | 2.68%   |
| 121-130        | 93        | 2.6%    |
| 61-70          | 78        | 2.18%   |
| 351-500        | 78        | 2.18%   |
| 71-80          | 65        | 1.82%   |
| 251-300        | 59        | 1.65%   |
| 41-50          | 47        | 1.31%   |
| 51-60          | 40        | 1.12%   |
| 501-1000       | 38        | 1.06%   |
| 131-140        | 28        | 0.78%   |
| 111-120        | 15        | 0.42%   |
| 91-100         | 12        | 0.34%   |
| 1-40           | 5         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1380      | 39.58%  |
| 101-120       | 1100      | 31.55%  |
| 121-160       | 726       | 20.82%  |
| Unknown       | 104       | 2.98%   |
| 161-240       | 83        | 2.38%   |
| 1-50          | 73        | 2.09%   |
| More than 240 | 21        | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3091      | 87.09%  |
| 2     | 346       | 9.75%   |
| 0     | 87        | 2.45%   |
| 3     | 25        | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1821      | 35.51%  |
| Intel                             | 1342      | 26.17%  |
| Qualcomm Atheros                  | 764       | 14.9%   |
| Broadcom                          | 333       | 6.49%   |
| Broadcom Limited                  | 135       | 2.63%   |
| Ralink                            | 114       | 2.22%   |
| Marvell Technology Group          | 73        | 1.42%   |
| Qualcomm Atheros Communications   | 67        | 1.31%   |
| Ralink Technology                 | 59        | 1.15%   |
| TP-Link                           | 50        | 0.98%   |
| Nvidia                            | 46        | 0.9%    |
| MediaTek                          | 34        | 0.66%   |
| Dell                              | 26        | 0.51%   |
| Hewlett-Packard                   | 21        | 0.41%   |
| Samsung Electronics               | 20        | 0.39%   |
| Huawei Technologies               | 18        | 0.35%   |
| VIA Technologies                  | 17        | 0.33%   |
| Sierra Wireless                   | 15        | 0.29%   |
| Ericsson Business Mobile Networks | 15        | 0.29%   |
| Xiaomi                            | 14        | 0.27%   |
| ASUSTek Computer                  | 13        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.23%   |
| JMicron Technology                | 11        | 0.21%   |
| Attansic Technology               | 11        | 0.21%   |
| ASIX Electronics                  | 8         | 0.16%   |
| Aquantia                          | 8         | 0.16%   |
| Belkin Components                 | 7         | 0.14%   |
| D-Link System                     | 6         | 0.12%   |
| IMC Networks                      | 5         | 0.1%    |
| DisplayLink                       | 5         | 0.1%    |
| D-Link                            | 5         | 0.1%    |
| Edimax Technology                 | 4         | 0.08%   |
| Accton Technology                 | 4         | 0.08%   |
| Qualcomm                          | 3         | 0.06%   |
| Microchip Technology              | 3         | 0.06%   |
| Lenovo                            | 3         | 0.06%   |
| ZyDAS                             | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 2         | 0.04%   |
| NetGear                           | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1282      | 21.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 321       | 5.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 183       | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 107       | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 1.24%   |
| Intel Wireless 8265 / 8275                                              | 72        | 1.21%   |
| Intel Wireless 7260                                                     | 68        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 66        | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 66        | 1.11%   |
| Intel 82577LM Gigabit Network Connection                                | 62        | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 60        | 1.01%   |
| Intel Wireless 7265                                                     | 59        | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                         | 58        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 55        | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                | 53        | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 51        | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 51        | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 50        | 0.84%   |
| Intel Ethernet Connection I217-LM                                       | 48        | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 48        | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 46        | 0.77%   |
| Intel Wireless 3165                                                     | 46        | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                    | 42        | 0.71%   |
| Intel Wireless 3160                                                     | 37        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 36        | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 0.61%   |
| Intel Wireless 8260                                                     | 35        | 0.59%   |
| Intel Wi-Fi 6 AX200                                                     | 35        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 0.59%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 0.59%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 31        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 30        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 30        | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                              | 30        | 0.5%    |
| Intel WiFi Link 5100                                                    | 29        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 944       | 38.14%  |
| Qualcomm Atheros                  | 583       | 23.56%  |
| Realtek Semiconductor             | 324       | 13.09%  |
| Broadcom                          | 179       | 7.23%   |
| Ralink                            | 114       | 4.61%   |
| Qualcomm Atheros Communications   | 67        | 2.71%   |
| Ralink Technology                 | 59        | 2.38%   |
| TP-Link                           | 46        | 1.86%   |
| Broadcom Limited                  | 43        | 1.74%   |
| MediaTek                          | 31        | 1.25%   |
| Sierra Wireless                   | 15        | 0.61%   |
| Dell                              | 15        | 0.61%   |
| ASUSTek Computer                  | 13        | 0.53%   |
| Belkin Components                 | 7         | 0.28%   |
| IMC Networks                      | 5         | 0.2%    |
| Edimax Technology                 | 4         | 0.16%   |
| D-Link                            | 4         | 0.16%   |
| Hewlett-Packard                   | 3         | 0.12%   |
| Ericsson Business Mobile Networks | 3         | 0.12%   |
| ZyDAS                             | 2         | 0.08%   |
| NetGear                           | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| D-Link System                     | 2         | 0.08%   |
| VIA Technologies                  | 1         | 0.04%   |
| TRENDnet                          | 1         | 0.04%   |
| Texas Instruments                 | 1         | 0.04%   |
| Micro Star International          | 1         | 0.04%   |
| Mercucys                          | 1         | 0.04%   |
| Marvell Technology Group          | 1         | 0.04%   |
| Fujitsu Siemens Computers         | 1         | 0.04%   |
| Accton Technology                 | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 4.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 107       | 4.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 3.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 2.98%   |
| Intel Wireless 8265 / 8275                                              | 72        | 2.9%    |
| Intel Wireless 7260                                                     | 68        | 2.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 66        | 2.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 66        | 2.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 60        | 2.41%   |
| Intel Wireless 7265                                                     | 59        | 2.37%   |
| Qualcomm Atheros AR9271 802.11n                                         | 58        | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 55        | 2.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 51        | 2.05%   |
| Intel Centrino Advanced-N 6200                                          | 50        | 2.01%   |
| Intel Wireless 3165                                                     | 46        | 1.85%   |
| Intel Wireless 3160                                                     | 37        | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 36        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 1.45%   |
| Intel Wireless 8260                                                     | 35        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                     | 35        | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 1.41%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 1.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 1.25%   |
| Intel WiFi Link 5100                                                    | 29        | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 1.09%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.01%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 24        | 0.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 0.88%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 21        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 19        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 19        | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                         | 19        | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 19        | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 19        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1716      | 51.04%  |
| Intel                             | 829       | 24.66%  |
| Qualcomm Atheros                  | 263       | 7.82%   |
| Broadcom                          | 179       | 5.32%   |
| Broadcom Limited                  | 93        | 2.77%   |
| Marvell Technology Group          | 72        | 2.14%   |
| Nvidia                            | 46        | 1.37%   |
| Samsung Electronics               | 20        | 0.59%   |
| Huawei Technologies               | 16        | 0.48%   |
| VIA Technologies                  | 15        | 0.45%   |
| Xiaomi                            | 14        | 0.42%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.36%   |
| JMicron Technology                | 11        | 0.33%   |
| Attansic Technology               | 11        | 0.33%   |
| ASIX Electronics                  | 8         | 0.24%   |
| Aquantia                          | 8         | 0.24%   |
| DisplayLink                       | 5         | 0.15%   |
| TP-Link                           | 4         | 0.12%   |
| D-Link System                     | 4         | 0.12%   |
| Qualcomm                          | 3         | 0.09%   |
| Microchip Technology              | 3         | 0.09%   |
| MediaTek                          | 3         | 0.09%   |
| Lenovo                            | 3         | 0.09%   |
| Accton Technology                 | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Sundance Technology Inc / IC Plus | 2         | 0.06%   |
| Hewlett-Packard                   | 2         | 0.06%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| QLogic                            | 1         | 0.03%   |
| OPPO Electronics                  | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.03%   |
| Motorola PCS                      | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| HMD Global                        | 1         | 0.03%   |
| Hangzhou Silan Microelectronics   | 1         | 0.03%   |
| Google                            | 1         | 0.03%   |
| Davicom Semiconductor             | 1         | 0.03%   |
| D-Link                            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1282      | 37.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 321       | 9.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 183       | 5.38%   |
| Intel 82577LM Gigabit Network Connection                          | 62        | 1.82%   |
| Intel 82567LM Gigabit Network Connection                          | 53        | 1.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 51        | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 48        | 1.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 48        | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 46        | 1.35%   |
| Intel Ethernet Connection (2) I219-V                              | 42        | 1.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 31        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.88%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 30        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 30        | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 0.79%   |
| Nvidia MCP61 Ethernet                                             | 26        | 0.76%   |
| Intel I211 Gigabit Network Connection                             | 26        | 0.76%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 25        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 25        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 21        | 0.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 0.59%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20        | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 19        | 0.56%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.47%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 15        | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 15        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.44%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 15        | 0.44%   |
| Huawei ELS-NX9                                                    | 14        | 0.41%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 14        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3228      | 57.11%  |
| WiFi     | 2368      | 41.9%   |
| Modem    | 54        | 0.96%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1879      | 51.34%  |
| Ethernet | 1781      | 48.66%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1949      | 56.07%  |
| 1     | 1426      | 41.02%  |
| 0     | 60        | 1.73%   |
| 3     | 34        | 0.98%   |
| 4     | 6         | 0.17%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3059      | 85.28%  |
| Yes  | 528       | 14.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 570       | 33.31%  |
| Qualcomm Atheros Communications | 174       | 10.17%  |
| Broadcom                        | 150       | 8.77%   |
| Realtek Semiconductor           | 132       | 7.71%   |
| Cambridge Silicon Radio         | 117       | 6.84%   |
| Lite-On Technology              | 88        | 5.14%   |
| IMC Networks                    | 83        | 4.85%   |
| Dell                            | 78        | 4.56%   |
| Hewlett-Packard                 | 72        | 4.21%   |
| Ralink                          | 66        | 3.86%   |
| Foxconn / Hon Hai               | 61        | 3.57%   |
| ASUSTek Computer                | 21        | 1.23%   |
| Toshiba                         | 20        | 1.17%   |
| Apple                           | 15        | 0.88%   |
| Ralink Technology               | 9         | 0.53%   |
| Realtek                         | 8         | 0.47%   |
| Conwise Technology              | 6         | 0.35%   |
| Askey Computer                  | 6         | 0.35%   |
| Chicony Electronics             | 5         | 0.29%   |
| Taiyo Yuden                     | 4         | 0.23%   |
| Integrated System Solution      | 4         | 0.23%   |
| Foxconn International           | 4         | 0.23%   |
| Belkin Components               | 4         | 0.23%   |
| Micro Star International        | 3         | 0.18%   |
| MediaTek                        | 2         | 0.12%   |
| Logitech                        | 2         | 0.12%   |
| Edimax Technology               | 2         | 0.12%   |
| Alps Electric                   | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Fujitsu Siemens Computers       | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 321       | 18.73%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 117       | 6.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 84        | 4.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 73        | 4.26%   |
| Realtek Bluetooth Radio                             | 71        | 4.14%   |
| Ralink RT3290 Bluetooth                             | 66        | 3.85%   |
| Lite-On Bluetooth Device                            | 56        | 3.27%   |
| Intel Bluetooth Device                              | 53        | 3.09%   |
| Dell DW375 Bluetooth Module                         | 39        | 2.28%   |
| HP Broadcom 2070 Bluetooth Combo                    | 36        | 2.1%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 1.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 32        | 1.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 31        | 1.81%   |
| Intel AX200 Bluetooth                               | 31        | 1.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 30        | 1.75%   |
| IMC Networks Bluetooth Device                       | 26        | 1.52%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 1.34%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.34%   |
| Broadcom HP Portable SoftSailing                    | 22        | 1.28%   |
| Realtek RTL8723B Bluetooth                          | 20        | 1.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 1.17%   |
| Realtek RTL8821A Bluetooth                          | 19        | 1.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.11%   |
| IMC Networks Wireless_Device                        | 17        | 0.99%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 0.88%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.76%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.76%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.58%   |
| Foxconn / Hon Hai BCM20702A0                        | 10        | 0.58%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 10        | 0.58%   |
| Toshiba Bluetooth Device                            | 9         | 0.53%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 9         | 0.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.53%   |
| Realtek Bluetooth Radio                             | 8         | 0.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 0.47%   |
| Broadcom BCM2045 Bluetooth                          | 8         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2621      | 59.19%  |
| AMD                                  | 892       | 20.14%  |
| Nvidia                               | 635       | 14.34%  |
| C-Media Electronics                  | 77        | 1.74%   |
| Creative Labs                        | 33        | 0.75%   |
| Logitech                             | 17        | 0.38%   |
| VIA Technologies                     | 16        | 0.36%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.32%   |
| Texas Instruments                    | 13        | 0.29%   |
| ASUSTek Computer                     | 10        | 0.23%   |
| Generalplus Technology               | 9         | 0.2%    |
| JMTek                                | 7         | 0.16%   |
| Creative Technology                  | 7         | 0.16%   |
| Kingston Technology                  | 6         | 0.14%   |
| BEHRINGER International              | 6         | 0.14%   |
| Plantronics                          | 5         | 0.11%   |
| SteelSeries ApS                      | 4         | 0.09%   |
| GN Netcom                            | 4         | 0.09%   |
| Samson Technologies                  | 3         | 0.07%   |
| Lenovo                               | 3         | 0.07%   |
| Focusrite-Novation                   | 3         | 0.07%   |
| Tenx Technology                      | 2         | 0.05%   |
| Sennheiser Communications            | 2         | 0.05%   |
| Hewlett-Packard                      | 2         | 0.05%   |
| Ensoniq                              | 2         | 0.05%   |
| D&M Holdings (Denon/Marantz)         | 2         | 0.05%   |
| ATI Technologies                     | 2         | 0.05%   |
| Yamaha                               | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |
| TEAC                                 | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |
| Superlux digit                       | 1         | 0.02%   |
| Sunplus Technology                   | 1         | 0.02%   |
| SM950T Microphone                    | 1         | 0.02%   |
| Rotel                                | 1         | 0.02%   |
| Reloop                               | 1         | 0.02%   |
| Realtek Semiconductor                | 1         | 0.02%   |
| Promethean Limited                   | 1         | 0.02%   |
| PreSonus Audio Electronics           | 1         | 0.02%   |
| Numark                               | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 298       | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 267       | 5.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 257       | 4.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 235       | 4.46%   |
| AMD FCH Azalia Controller                                                                         | 229       | 4.34%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 210       | 3.98%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 185       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 179       | 3.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 174       | 3.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 132       | 2.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 108       | 2.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 108       | 2.05%   |
| Intel 8 Series HD Audio Controller                                                                | 92        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 91        | 1.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 88        | 1.67%   |
| Intel Broadwell-U Audio Controller                                                                | 85        | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 83        | 1.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 82        | 1.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 81        | 1.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 70        | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 64        | 1.21%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 61        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 57        | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 55        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 54        | 1.02%   |
| Intel 200 Series PCH HD Audio                                                                     | 53        | 1.01%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 53        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 52        | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 49        | 0.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 48        | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 47        | 0.89%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 47        | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 46        | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 45        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 42        | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 42        | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 42        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 0.8%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 36        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 649       | 19.67%  |
| SK hynix                   | 622       | 18.85%  |
| Unknown                    | 588       | 17.82%  |
| Kingston                   | 526       | 15.94%  |
| Micron Technology          | 260       | 7.88%   |
| Nanya Technology           | 106       | 3.21%   |
| Elpida                     | 81        | 2.45%   |
| Kingmax                    | 70        | 2.12%   |
| Crucial                    | 68        | 2.06%   |
| Corsair                    | 58        | 1.76%   |
| Ramaxel Technology         | 50        | 1.52%   |
| G.Skill                    | 44        | 1.33%   |
| A-DATA Technology          | 35        | 1.06%   |
| CSX                        | 18        | 0.55%   |
| Team                       | 12        | 0.36%   |
| Qimonda                    | 11        | 0.33%   |
| 48spaces                   | 10        | 0.3%    |
| Transcend                  | 9         | 0.27%   |
| ASint Technology           | 9         | 0.27%   |
| Patriot                    | 8         | 0.24%   |
| Unknown (ABCD)             | 7         | 0.21%   |
| Melco                      | 7         | 0.21%   |
| Kingmax Semiconductor      | 6         | 0.18%   |
| Apacer                     | 4         | 0.12%   |
| Toshiba                    | 3         | 0.09%   |
| OCZ                        | 3         | 0.09%   |
| GeIL                       | 3         | 0.09%   |
| Unknown                    | 3         | 0.09%   |
| Unknown (09D5)             | 2         | 0.06%   |
| Silicon Power              | 2         | 0.06%   |
| Intersil                   | 2         | 0.06%   |
| Infineon                   | 2         | 0.06%   |
| H                          | 2         | 0.06%   |
| Golden Empire              | 2         | 0.06%   |
| ZION                       | 1         | 0.03%   |
| Unknown (8A5B)             | 1         | 0.03%   |
| Unknown (7F7F7F7F7F970000) | 1         | 0.03%   |
| Unigen                     | 1         | 0.03%   |
| Toshiba-0098               | 1         | 0.03%   |
| Strontium                  | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s       | 42        | 1.15%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 40        | 1.09%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 33        | 0.9%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 33        | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 33        | 0.9%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 32        | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 29        | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 26        | 0.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 26        | 0.71%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 23        | 0.63%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 22        | 0.6%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s          | 22        | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 21        | 0.57%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3                | 21        | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 20        | 0.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 20        | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 19        | 0.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 19        | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 18        | 0.49%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 18        | 0.49%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 18        | 0.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s       | 18        | 0.49%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 17        | 0.46%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 17        | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.44%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 16        | 0.44%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 16        | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 16        | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 16        | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 16        | 0.44%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 16        | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 15        | 0.41%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 15        | 0.41%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.41%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 15        | 0.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 15        | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 13        | 0.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 12        | 0.33%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 12        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1330      | 47.05%  |
| DDR4    | 588       | 20.8%   |
| DDR2    | 377       | 13.34%  |
| SDRAM   | 222       | 7.85%   |
| Unknown | 174       | 6.15%   |
| DDR     | 55        | 1.95%   |
| LPDDR4  | 40        | 1.41%   |
| LPDDR3  | 19        | 0.67%   |
| DRAM    | 9         | 0.32%   |
| DDR5    | 9         | 0.32%   |
| LPDDR5  | 4         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1538      | 56.32%  |
| DIMM         | 1142      | 41.82%  |
| Row Of Chips | 41        | 1.5%    |
| Chip         | 7         | 0.26%   |
| RIMM         | 2         | 0.07%   |
| FB-DIMM      | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 1132      | 36.47%  |
| 2048    | 856       | 27.58%  |
| 8192    | 580       | 18.69%  |
| 1024    | 324       | 10.44%  |
| 16384   | 125       | 4.03%   |
| 512     | 53        | 1.71%   |
| 32768   | 28        | 0.9%    |
| 256     | 4         | 0.13%   |
| Unknown | 2         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 812       | 25.98%  |
| 1333    | 298       | 9.53%   |
| 2667    | 236       | 7.55%   |
| 800     | 207       | 6.62%   |
| 667     | 207       | 6.62%   |
| 1334    | 177       | 5.66%   |
| 2400    | 147       | 4.7%    |
| Unknown | 135       | 4.32%   |
| 3200    | 111       | 3.55%   |
| 2133    | 103       | 3.29%   |
| 1067    | 84        | 2.69%   |
| 1866    | 62        | 1.98%   |
| 1867    | 51        | 1.63%   |
| 533     | 49        | 1.57%   |
| 1066    | 48        | 1.54%   |
| 2048    | 43        | 1.38%   |
| 4199    | 42        | 1.34%   |
| 3600    | 38        | 1.22%   |
| 400     | 35        | 1.12%   |
| 975     | 19        | 0.61%   |
| 1639    | 18        | 0.58%   |
| 3266    | 15        | 0.48%   |
| 1800    | 14        | 0.45%   |
| 333     | 14        | 0.45%   |
| 3466    | 13        | 0.42%   |
| 3400    | 13        | 0.42%   |
| 3000    | 12        | 0.38%   |
| 2933    | 10        | 0.32%   |
| 2666    | 10        | 0.32%   |
| 2000    | 9         | 0.29%   |
| 49926   | 6         | 0.19%   |
| 4800    | 6         | 0.19%   |
| 4266    | 6         | 0.19%   |
| 3151    | 6         | 0.19%   |
| 4267    | 5         | 0.16%   |
| 3733    | 5         | 0.16%   |
| 6400    | 4         | 0.13%   |
| 5808    | 4         | 0.13%   |
| 2134    | 4         | 0.13%   |
| 1776    | 4         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 55        | 47.01%  |
| Samsung Electronics   | 24        | 20.51%  |
| Canon                 | 14        | 11.97%  |
| Brother Industries    | 9         | 7.69%   |
| Seiko Epson           | 6         | 5.13%   |
| QinHeng Electronics   | 2         | 1.71%   |
| Lexmark International | 2         | 1.71%   |
| Xerox                 | 1         | 0.85%   |
| STMicroelectronics    | 1         | 0.85%   |
| Ricoh                 | 1         | 0.85%   |
| Prolific Technology   | 1         | 0.85%   |
| Oki Data              | 1         | 0.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                                    | 8         | 6.72%   |
| HP LaserJet 1020                                          | 6         | 5.04%   |
| Samsung ML-2010P Mono Laser Printer                       | 5         | 4.2%    |
| Samsung M2020 Series                                      | 5         | 4.2%    |
| HP DeskJet 2130 series                                    | 4         | 3.36%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 2.52%   |
| HP LaserJet P1005                                         | 3         | 2.52%   |
| HP LaserJet 1018                                          | 3         | 2.52%   |
| HP Deskjet 2050 J510                                      | 3         | 2.52%   |
| Canon LiDE 400                                            | 3         | 2.52%   |
| Brother HL-1110 series                                    | 3         | 2.52%   |
| Samsung SCX-3400 Series                                   | 2         | 1.68%   |
| QinHeng CH340S                                            | 2         | 1.68%   |
| HP Officejet J4500 series                                 | 2         | 1.68%   |
| HP LaserJet P1102                                         | 2         | 1.68%   |
| HP LaserJet 1022                                          | 2         | 1.68%   |
| HP LaserJet 1010                                          | 2         | 1.68%   |
| HP LaserJet 1000                                          | 2         | 1.68%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.68%   |
| HP Deskjet F2280 series                                   | 2         | 1.68%   |
| HP DeskJet F2100 Printer series                           | 2         | 1.68%   |
| HP Deskjet 3520 series                                    | 2         | 1.68%   |
| Canon TS5100 series                                       | 2         | 1.68%   |
| Brother HL-L2300D series                                  | 2         | 1.68%   |
| Xerox WorkCentre 3119 Series                              | 1         | 0.84%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.84%   |
| Seiko Epson XP-243 245 247 Series                         | 1         | 0.84%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.84%   |
| Seiko Epson Printer                                       | 1         | 0.84%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.84%   |
| Seiko Epson L396 Series                                   | 1         | 0.84%   |
| Seiko Epson L120 Series                                   | 1         | 0.84%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 0.84%   |
| Samsung SCX-4650 4x21S Series                             | 1         | 0.84%   |
| Samsung SCX-4623 Series                                   | 1         | 0.84%   |
| Samsung SCX-4200 series                                   | 1         | 0.84%   |
| Samsung ML-1660 Series                                    | 1         | 0.84%   |
| Samsung ML-1630 Series                                    | 1         | 0.84%   |
| Samsung Composite Device                                  | 1         | 0.84%   |
| Samsung CLP-310 Color Laser Printer                       | 1         | 0.84%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 14        | 63.64%  |
| Hewlett-Packard                                | 3         | 13.64%  |
| Mustek Systems                                 | 2         | 9.09%   |
| UMAX                                           | 1         | 4.55%   |
| Siemens Information and Communication Products | 1         | 4.55%   |
| Seiko Epson                                    | 1         | 4.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                                              | 3         | 13.64%  |
| Canon CanoScan LIDE 25                                                          | 3         | 13.64%  |
| Canon CanoScan LiDE 110                                                         | 3         | 13.64%  |
| Mustek Systems SNAPSCAN e22                                                     | 2         | 9.09%   |
| HP Scanjet 300                                                                  | 2         | 9.09%   |
| Canon CanoScan LiDE 120                                                         | 2         | 9.09%   |
| UMAX Astra 4400/4450                                                            | 1         | 4.55%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 4.55%   |
| Seiko Epson Stylus Photo RX500/510                                              | 1         | 4.55%   |
| HP ScanJet 3770                                                                 | 1         | 4.55%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 4.55%   |
| Canon CanoScan LiDE 100                                                         | 1         | 4.55%   |
| Canon CanoScan 4200F                                                            | 1         | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 468       | 25.03%  |
| Microdia                               | 185       | 9.89%   |
| IMC Networks                           | 175       | 9.36%   |
| Realtek Semiconductor                  | 156       | 8.34%   |
| Sunplus Innovation Technology          | 123       | 6.58%   |
| Acer                                   | 116       | 6.2%    |
| Suyin                                  | 83        | 4.44%   |
| Quanta                                 | 63        | 3.37%   |
| Cheng Uei Precision Industry (Foxlink) | 62        | 3.32%   |
| Logitech                               | 54        | 2.89%   |
| Syntek                                 | 47        | 2.51%   |
| Silicon Motion                         | 33        | 1.76%   |
| Lite-On Technology                     | 33        | 1.76%   |
| Lenovo                                 | 30        | 1.6%    |
| Z-Star Microelectronics                | 22        | 1.18%   |
| Alcor Micro                            | 22        | 1.18%   |
| Primax Electronics                     | 20        | 1.07%   |
| Ricoh                                  | 16        | 0.86%   |
| KYE Systems (Mouse Systems)            | 16        | 0.86%   |
| Microsoft                              | 15        | 0.8%    |
| Apple                                  | 15        | 0.8%    |
| Samsung Electronics                    | 12        | 0.64%   |
| ALi                                    | 11        | 0.59%   |
| GEMBIRD                                | 9         | 0.48%   |
| Luxvisions Innotech Limited            | 8         | 0.43%   |
| Importek                               | 7         | 0.37%   |
| Trust                                  | 6         | 0.32%   |
| OmniVision Technologies                | 6         | 0.32%   |
| Arkmicro Technologies                  | 5         | 0.27%   |
| Sonix Technology                       | 4         | 0.21%   |
| LG Electronics                         | 4         | 0.21%   |
| Pixart Imaging                         | 3         | 0.16%   |
| MacroSilicon                           | 3         | 0.16%   |
| Jieli Technology                       | 3         | 0.16%   |
| Generalplus Technology                 | 3         | 0.16%   |
| DigiTech                               | 3         | 0.16%   |
| Cubeternet                             | 3         | 0.16%   |
| Creative Technology                    | 3         | 0.16%   |
| Aveo Technology                        | 3         | 0.16%   |
| Sunplus Technology                     | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam            | 53        | 2.82%   |
| Chicony Integrated Camera                     | 52        | 2.77%   |
| Chicony HD WebCam                             | 46        | 2.45%   |
| Acer Lenovo EasyCamera                        | 46        | 2.45%   |
| Microdia Integrated_Webcam_HD                 | 40        | 2.13%   |
| Chicony HP TrueVision HD                      | 39        | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam             | 37        | 1.97%   |
| Sunplus Integrated_Webcam_HD                  | 30        | 1.6%    |
| Chicony USB2.0 VGA UVC WebCam                 | 29        | 1.54%   |
| Realtek USB Camera                            | 27        | 1.44%   |
| Realtek Integrated_Webcam_HD                  | 26        | 1.38%   |
| Sunplus HP Truevision HD                      | 24        | 1.28%   |
| Microdia Integrated Webcam                    | 24        | 1.28%   |
| Chicony Lenovo EasyCamera                     | 23        | 1.22%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 21        | 1.12%   |
| Acer Integrated Camera                        | 21        | 1.12%   |
| Sunplus HD WebCam                             | 19        | 1.01%   |
| IMC Networks EasyCamera                       | 19        | 1.01%   |
| Logitech Webcam C270                          | 18        | 0.96%   |
| Chicony EasyCamera                            | 18        | 0.96%   |
| Chicony VGA WebCam                            | 17        | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                  | 17        | 0.91%   |
| Chicony Integrated HP HD Webcam               | 17        | 0.91%   |
| Chicony FJ Camera                             | 17        | 0.91%   |
| Quanta VGA WebCam                             | 16        | 0.85%   |
| Microdia Sonix USB 2.0 Camera                 | 16        | 0.85%   |
| Lenovo Integrated Webcam                      | 16        | 0.85%   |
| Realtek Integrated Webcam                     | 15        | 0.8%    |
| Primax HP HD Webcam [Fixed]                   | 14        | 0.75%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.75%   |
| Microdia Camera                               | 14        | 0.75%   |
| IMC Networks Integrated Camera                | 14        | 0.75%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.75%   |
| Syntek Integrated Camera                      | 13        | 0.69%   |
| Realtek Integrated Webcam HD                  | 13        | 0.69%   |
| Lenovo Integrated Webcam [R5U877]             | 13        | 0.69%   |
| Syntek Lenovo EasyCamera                      | 12        | 0.64%   |
| Realtek Lenovo EasyCamera                     | 12        | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 12        | 0.64%   |
| Syntek EasyCamera                             | 11        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 98        | 37.55%  |
| AuthenTec                          | 56        | 21.46%  |
| Synaptics                          | 33        | 12.64%  |
| Upek                               | 22        | 8.43%   |
| LighTuning Technology              | 17        | 6.51%   |
| Shenzhen Goodix Technology         | 15        | 5.75%   |
| STMicroelectronics                 | 10        | 3.83%   |
| Elan Microelectronics              | 9         | 3.45%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 9.58%   |
| AuthenTec AES2810                                                          | 23        | 8.81%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 8.43%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 7.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 4.6%    |
| Validity Sensors VFS491                                                    | 10        | 3.83%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 3.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.83%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 3.45%   |
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.3%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.3%    |
| LighTuning Fingerprint Reader                                              | 6         | 2.3%    |
| Elan ELAN:Fingerprint                                                      | 6         | 2.3%    |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.3%    |
| Unknown                                                                    | 6         | 2.3%    |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.92%   |
| Synaptics  WBDI                                                            | 5         | 1.92%   |
| AuthenTec AES1600                                                          | 5         | 1.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.15%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.77%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.38%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.38%   |
| Synaptics WBDI Device                                                      | 1         | 0.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.38%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.38%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.38%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.38%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 115       | 55.02%  |
| Alcor Micro               | 30        | 14.35%  |
| O2 Micro                  | 27        | 12.92%  |
| Lenovo                    | 27        | 12.92%  |
| Upek                      | 3         | 1.44%   |
| Gemalto (was Gemplus)     | 3         | 1.44%   |
| Yubico.com                | 1         | 0.48%   |
| Chicony Electronics       | 1         | 0.48%   |
| Aladdin Knowledge Systems | 1         | 0.48%   |
| Advanced Card Systems     | 1         | 0.48%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 61        | 29.19%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 14.35%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 12.92%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 12.44%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 11.48%  |
| Broadcom 5880                                                                | 15        | 7.18%   |
| Broadcom 58200                                                               | 15        | 7.18%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.44%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.48%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.48%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.48%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.48%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.48%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.48%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.48%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.48%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2633      | 73.98%  |
| 1     | 764       | 21.47%  |
| 2     | 142       | 3.99%   |
| 3     | 14        | 0.39%   |
| 4     | 4         | 0.11%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 261       | 24.46%  |
| Fingerprint reader       | 261       | 24.46%  |
| Chipcard                 | 194       | 18.18%  |
| Net/wireless             | 88        | 8.25%   |
| Bluetooth                | 76        | 7.12%   |
| Multimedia controller    | 43        | 4.03%   |
| Storage                  | 37        | 3.47%   |
| Communication controller | 34        | 3.19%   |
| Camera                   | 18        | 1.69%   |
| Flash memory             | 17        | 1.59%   |
| Unassigned class         | 10        | 0.94%   |
| Sound                    | 6         | 0.56%   |
| Card reader              | 6         | 0.56%   |
| Net/ethernet             | 4         | 0.37%   |
| Storage/raid             | 3         | 0.28%   |
| Dvb card                 | 3         | 0.28%   |
| Network                  | 2         | 0.19%   |
| Modem                    | 2         | 0.19%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

