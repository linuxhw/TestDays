Linux in France - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 6566

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 17-ca1xxx            | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| HUAWEI        | CREM-WXX9                   | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude 5400               | [00cd14a724](https://linux-hardware.org/?probe=00cd14a724) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Timi          | TM1701                      | [ab658664bb](https://linux-hardware.org/?probe=ab658664bb) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S23... | [3cd99ed8f4](https://linux-hardware.org/?probe=3cd99ed8f4) | Feb 28, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [594ff7091b](https://linux-hardware.org/?probe=594ff7091b) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [05d3c9f96c](https://linux-hardware.org/?probe=05d3c9f96c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f70d3317a2](https://linux-hardware.org/?probe=f70d3317a2) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| HP            | Pavilion m6                 | [1e9d802ab6](https://linux-hardware.org/?probe=1e9d802ab6) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | [c49b50f583](https://linux-hardware.org/?probe=c49b50f583) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | [4083a9232f](https://linux-hardware.org/?probe=4083a9232f) | Feb 27, 2023 |
| HP            | Pavilion m6                 | [0d35b0b080](https://linux-hardware.org/?probe=0d35b0b080) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G50-80 80L0                 | [19727a16be](https://linux-hardware.org/?probe=19727a16be) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e763fc25e7](https://linux-hardware.org/?probe=e763fc25e7) | Feb 26, 2023 |
| HONOR         | BBR-WAX9                    | [3fe348fb3f](https://linux-hardware.org/?probe=3fe348fb3f) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Dell          | Latitude E5450              | [62ce48db27](https://linux-hardware.org/?probe=62ce48db27) | Feb 26, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [d0b043c11b](https://linux-hardware.org/?probe=d0b043c11b) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [08d12e1049](https://linux-hardware.org/?probe=08d12e1049) | Feb 26, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5634c4795c](https://linux-hardware.org/?probe=5634c4795c) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | ENVY 17                     | [dea1551bf3](https://linux-hardware.org/?probe=dea1551bf3) | Feb 26, 2023 |
| Valve         | Jupiter                     | [1b7321e88d](https://linux-hardware.org/?probe=1b7321e88d) | Feb 26, 2023 |
| HP            | ENVY 17                     | [0f347a1b6c](https://linux-hardware.org/?probe=0f347a1b6c) | Feb 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3142c6a90c](https://linux-hardware.org/?probe=3142c6a90c) | Feb 25, 2023 |
| Chuwi         | GemiBook Pro                | [9894743527](https://linux-hardware.org/?probe=9894743527) | Feb 25, 2023 |
| Dell          | XPS 9315                    | [86fea0e08a](https://linux-hardware.org/?probe=86fea0e08a) | Feb 25, 2023 |
| Sony          | SVE1513B1EW                 | [c99ef001e4](https://linux-hardware.org/?probe=c99ef001e4) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Chuwi         | GemiBook Pro                | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [8fde9cab5c](https://linux-hardware.org/?probe=8fde9cab5c) | Feb 22, 2023 |
| Toshiba       | Satellite L655              | [2b16b06c7f](https://linux-hardware.org/?probe=2b16b06c7f) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | [51b83f1e27](https://linux-hardware.org/?probe=51b83f1e27) | Feb 22, 2023 |
| Lenovo        | V130-15IGM 81HL             | [40205862f6](https://linux-hardware.org/?probe=40205862f6) | Feb 22, 2023 |
| Notebook      | N8xEJEK                     | [1548ea7cab](https://linux-hardware.org/?probe=1548ea7cab) | Feb 21, 2023 |
| Notebook      | N8xEJEK                     | [a8a28d6f2b](https://linux-hardware.org/?probe=a8a28d6f2b) | Feb 21, 2023 |
| ASUSTek       | X55VD                       | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9978852d07](https://linux-hardware.org/?probe=9978852d07) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| Dell          | Vostro 15 7510              | [df764baed8](https://linux-hardware.org/?probe=df764baed8) | Feb 21, 2023 |
| HP            | Pavilion 15                 | [9aee694156](https://linux-hardware.org/?probe=9aee694156) | Feb 21, 2023 |
| ASUSTek       | K70IC                       | [e5aad61a1b](https://linux-hardware.org/?probe=e5aad61a1b) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| ASUSTek       | UX410UQK                    | [0a23974b1b](https://linux-hardware.org/?probe=0a23974b1b) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| Toshiba       | TECRA R850                  | [082f5559c7](https://linux-hardware.org/?probe=082f5559c7) | Feb 20, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [e26b379150](https://linux-hardware.org/?probe=e26b379150) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Toshiba       | Satellite L655              | [a5124a64e6](https://linux-hardware.org/?probe=a5124a64e6) | Feb 19, 2023 |
| ASUSTek       | P553UA                      | [b999af6719](https://linux-hardware.org/?probe=b999af6719) | Feb 19, 2023 |
| HP            | EliteBook 8440p             | [24e71c037b](https://linux-hardware.org/?probe=24e71c037b) | Feb 18, 2023 |
| Sony          | VGN-NW21MF_W                | [e46cfcff64](https://linux-hardware.org/?probe=e46cfcff64) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| eMachines     | eMachiens G443              | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Dell          | Latitude 7330               | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| Dell          | Vostro 1510                 | [a9e4d33e06](https://linux-hardware.org/?probe=a9e4d33e06) | Feb 16, 2023 |
| Dell          | Precision 5750              | [7b814aee7c](https://linux-hardware.org/?probe=7b814aee7c) | Feb 16, 2023 |
| ASUSTek       | S551LN                      | [676c244c1d](https://linux-hardware.org/?probe=676c244c1d) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| HP            | 250 G6 Notebook PC          | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [542f27e209](https://linux-hardware.org/?probe=542f27e209) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS4AN00    | [ec8fbb6350](https://linux-hardware.org/?probe=ec8fbb6350) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| Google        | Lulu                        | [15fa093522](https://linux-hardware.org/?probe=15fa093522) | Feb 14, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Thomson       | N17V3C4WH128                | [57eacd1a37](https://linux-hardware.org/?probe=57eacd1a37) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 13 9370                 | [36bf8af789](https://linux-hardware.org/?probe=36bf8af789) | Feb 13, 2023 |
| Dell          | Latitude E6320              | [32ad32fb45](https://linux-hardware.org/?probe=32ad32fb45) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| ASUSTek       | G771JM                      | [af72d8c72f](https://linux-hardware.org/?probe=af72d8c72f) | Feb 12, 2023 |
| MSI           | GF65 Thin 9SEXR             | [7d57fccbf0](https://linux-hardware.org/?probe=7d57fccbf0) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| Acer          | Aspire E5-574G              | [cdbd2ad757](https://linux-hardware.org/?probe=cdbd2ad757) | Feb 12, 2023 |
| Dell          | Vostro 15 3515              | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Notebook                    | [523c719e5b](https://linux-hardware.org/?probe=523c719e5b) | Feb 11, 2023 |
| HP            | Notebook                    | [d4e29128dd](https://linux-hardware.org/?probe=d4e29128dd) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Dell          | Precision 5570              | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7001PF... | [f6d2fc27d1](https://linux-hardware.org/?probe=f6d2fc27d1) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [9da08e5265](https://linux-hardware.org/?probe=9da08e5265) | Feb 10, 2023 |
| Acer          | Aspire E1-570               | [df85a15b13](https://linux-hardware.org/?probe=df85a15b13) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [077853b2db](https://linux-hardware.org/?probe=077853b2db) | Feb 09, 2023 |
| Acer          | Swift SF314-54              | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a77dd320a8](https://linux-hardware.org/?probe=a77dd320a8) | Feb 09, 2023 |
| Dell          | Precision 5570              | [52cd3af211](https://linux-hardware.org/?probe=52cd3af211) | Feb 09, 2023 |
| Sony          | SVE1513U1ESI                | [77dafc35f5](https://linux-hardware.org/?probe=77dafc35f5) | Feb 09, 2023 |
| Lenovo        | ThinkPad L512 2550WC7       | [8b8efe2813](https://linux-hardware.org/?probe=8b8efe2813) | Feb 09, 2023 |
| Dell          | Precision M6500             | [dcabcd8d63](https://linux-hardware.org/?probe=dcabcd8d63) | Feb 09, 2023 |
| Sony          | VGN-NS38E_S                 | [891c180950](https://linux-hardware.org/?probe=891c180950) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| EXTRA Comp... | A9100                       | [67278c37d9](https://linux-hardware.org/?probe=67278c37d9) | Feb 08, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [fcd6a27cd6](https://linux-hardware.org/?probe=fcd6a27cd6) | Feb 08, 2023 |
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [b07e05a4ed](https://linux-hardware.org/?probe=b07e05a4ed) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Notebook      | NL5xNU                      | [b7fb43ba75](https://linux-hardware.org/?probe=b7fb43ba75) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [cd59ace4d1](https://linux-hardware.org/?probe=cd59ace4d1) | Feb 07, 2023 |
| Toshiba       | Satellite C870-196          | [85ded7d8d0](https://linux-hardware.org/?probe=85ded7d8d0) | Feb 06, 2023 |
| ASUSTek       | K72JT                       | [9620d41f62](https://linux-hardware.org/?probe=9620d41f62) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
| Dell          | Latitude 5520               | [e9782f4262](https://linux-hardware.org/?probe=e9782f4262) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Notebook      | NLx0MU                      | [9a05c88c59](https://linux-hardware.org/?probe=9a05c88c59) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pro x2 612 G1 Tablet        | [6e00c72683](https://linux-hardware.org/?probe=6e00c72683) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Sony          | VPCEH1E1E                   | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Google        | Rabbid                      | [e309afd2d9](https://linux-hardware.org/?probe=e309afd2d9) | Feb 05, 2023 |
| Sony          | VGN-Z31MN_B                 | [bfb9a55ce9](https://linux-hardware.org/?probe=bfb9a55ce9) | Feb 05, 2023 |
| Acer          | Nitro AN517-52              | [e409f042e2](https://linux-hardware.org/?probe=e409f042e2) | Feb 05, 2023 |
| Google        | Rabbid                      | [3afddd7ab1](https://linux-hardware.org/?probe=3afddd7ab1) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F5S65B0J    | [cca484a94e](https://linux-hardware.org/?probe=cca484a94e) | Feb 04, 2023 |
| ASUSTek       | UX331UA                     | [4b5a781cb4](https://linux-hardware.org/?probe=4b5a781cb4) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Apple         | MacBookPro8,1               | [9765b77a43](https://linux-hardware.org/?probe=9765b77a43) | Feb 04, 2023 |
| Dell          | Precision 5570              | [11d65e48fa](https://linux-hardware.org/?probe=11d65e48fa) | Feb 04, 2023 |
| MSI           | GF63 Thin 11UD              | [8b60b63594](https://linux-hardware.org/?probe=8b60b63594) | Feb 04, 2023 |
| Dell          | Precision 5570              | [5378f40d0d](https://linux-hardware.org/?probe=5378f40d0d) | Feb 04, 2023 |
| Dell          | G3 3500                     | [a25e0c9862](https://linux-hardware.org/?probe=a25e0c9862) | Feb 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [001a819e3d](https://linux-hardware.org/?probe=001a819e3d) | Feb 03, 2023 |
| HP            | Laptop 14s-fq2xxx           | [f63797ea26](https://linux-hardware.org/?probe=f63797ea26) | Feb 03, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [cc7e8a75d3](https://linux-hardware.org/?probe=cc7e8a75d3) | Feb 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b453ade5b](https://linux-hardware.org/?probe=9b453ade5b) | Feb 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [2d0b0d4330](https://linux-hardware.org/?probe=2d0b0d4330) | Feb 02, 2023 |
| HUAWEI        | CREM-WXX9                   | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [e477495ef6](https://linux-hardware.org/?probe=e477495ef6) | Feb 01, 2023 |
| Lenovo        | ThinkPad T400 6473PMG       | [07cba1c44b](https://linux-hardware.org/?probe=07cba1c44b) | Feb 01, 2023 |
| ASUSTek       | S551LN                      | [b7361dbc53](https://linux-hardware.org/?probe=b7361dbc53) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Dell          | G3 3500                     | [4b519ab8a8](https://linux-hardware.org/?probe=4b519ab8a8) | Jan 31, 2023 |
| Acer          | Aspire E5-575G              | [463b7f859f](https://linux-hardware.org/?probe=463b7f859f) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| Dell          | Latitude 7410               | [fd07971a70](https://linux-hardware.org/?probe=fd07971a70) | Jan 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HUAWEI        | WRTB-WXX9                   | [60967eaaaf](https://linux-hardware.org/?probe=60967eaaaf) | Jan 31, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | [1086813401](https://linux-hardware.org/?probe=1086813401) | Jan 30, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | [0b43f40c2a](https://linux-hardware.org/?probe=0b43f40c2a) | Jan 30, 2023 |
| Acer          | Aspire E5-575G              | [532f5a8dbe](https://linux-hardware.org/?probe=532f5a8dbe) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | [970a402846](https://linux-hardware.org/?probe=970a402846) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | [c2d425d254](https://linux-hardware.org/?probe=c2d425d254) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Dell          | Latitude 7390               | [b154892be4](https://linux-hardware.org/?probe=b154892be4) | Jan 30, 2023 |
| HP            | ENVY Laptop 13-ah1xxx       | [360756b46a](https://linux-hardware.org/?probe=360756b46a) | Jan 30, 2023 |
| HUAWEI        | MACHD-WXX9                  | [cac5b8faa5](https://linux-hardware.org/?probe=cac5b8faa5) | Jan 29, 2023 |
| HP            | ZBook 14 G2                 | [4b1e1bc7e1](https://linux-hardware.org/?probe=4b1e1bc7e1) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| MSI           | CR700                       | [35d1ff1eac](https://linux-hardware.org/?probe=35d1ff1eac) | Jan 29, 2023 |
| Intel         | Unknown                     | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| HP            | ProBook 650 G1              | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [90644628b4](https://linux-hardware.org/?probe=90644628b4) | Jan 29, 2023 |
| ASUSTek       | X550LB                      | [9590dd2f30](https://linux-hardware.org/?probe=9590dd2f30) | Jan 28, 2023 |
| Dell          | Latitude 7280               | [358f4c431f](https://linux-hardware.org/?probe=358f4c431f) | Jan 28, 2023 |
| Dell          | Latitude 7280               | [903e0489c4](https://linux-hardware.org/?probe=903e0489c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Valve         | Jupiter                     | [be17d6fd70](https://linux-hardware.org/?probe=be17d6fd70) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| ASUSTek       | K73E                        | [66e0036452](https://linux-hardware.org/?probe=66e0036452) | Jan 27, 2023 |
| ASUSTek       | K73E                        | [91f049a01d](https://linux-hardware.org/?probe=91f049a01d) | Jan 27, 2023 |
| Dell          | Latitude E6420              | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [117d80ff4d](https://linux-hardware.org/?probe=117d80ff4d) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [7996de313e](https://linux-hardware.org/?probe=7996de313e) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [3f4e15d14a](https://linux-hardware.org/?probe=3f4e15d14a) | Jan 25, 2023 |
| Toshiba       | Satellite Pro R50-B         | [d08118920b](https://linux-hardware.org/?probe=d08118920b) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [148b797f1a](https://linux-hardware.org/?probe=148b797f1a) | Jan 25, 2023 |
| ASUSTek       | X301A1                      | [f9ea8894f0](https://linux-hardware.org/?probe=f9ea8894f0) | Jan 25, 2023 |
| Sony          | VGN-NW21MF_W                | [dd4ac0a026](https://linux-hardware.org/?probe=dd4ac0a026) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | [41c91fdc7b](https://linux-hardware.org/?probe=41c91fdc7b) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | [199569e288](https://linux-hardware.org/?probe=199569e288) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| HP            | EliteBook 2560p             | [f57750e125](https://linux-hardware.org/?probe=f57750e125) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| MSI           | Stealth GS66 12UH           | [9e79dca70b](https://linux-hardware.org/?probe=9e79dca70b) | Jan 23, 2023 |
| Dell          | Inspiron 7537               | [9181895f24](https://linux-hardware.org/?probe=9181895f24) | Jan 23, 2023 |
| Dell          | Latitude E4310              | [c32e006e62](https://linux-hardware.org/?probe=c32e006e62) | Jan 23, 2023 |
| Dell          | Latitude E4310              | [5045d5e911](https://linux-hardware.org/?probe=5045d5e911) | Jan 23, 2023 |
| Lenovo        | G50-70 20351                | [e0da886a95](https://linux-hardware.org/?probe=e0da886a95) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad X200 7458VL3       | [3a91fa2c72](https://linux-hardware.org/?probe=3a91fa2c72) | Jan 23, 2023 |
| MSI           | PX60 6QE                    | [d820232c9c](https://linux-hardware.org/?probe=d820232c9c) | Jan 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Acer          | Aspire E1-570               | [30b3f2f346](https://linux-hardware.org/?probe=30b3f2f346) | Jan 22, 2023 |
| HP            | ProBook 4330s               | [f96c2452d3](https://linux-hardware.org/?probe=f96c2452d3) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Dell          | XPS 15 9520                 | [893ebdd842](https://linux-hardware.org/?probe=893ebdd842) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| ASUSTek       | G750JM                      | [8cb76e0d6d](https://linux-hardware.org/?probe=8cb76e0d6d) | Jan 22, 2023 |
| Dell          | G15 5510                    | [7cee6347e3](https://linux-hardware.org/?probe=7cee6347e3) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | [dfb621ce10](https://linux-hardware.org/?probe=dfb621ce10) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | [e1d7b236d3](https://linux-hardware.org/?probe=e1d7b236d3) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Dell          | G3 3500                     | [941c11250c](https://linux-hardware.org/?probe=941c11250c) | Jan 21, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| Acer          | Aspire E1-570               | [9a0a65b69a](https://linux-hardware.org/?probe=9a0a65b69a) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| MSI           | GP75 Leopard 9SD            | [5b41a33a67](https://linux-hardware.org/?probe=5b41a33a67) | Jan 21, 2023 |
| Acer          | Predator PH315-52           | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [5b271fa3eb](https://linux-hardware.org/?probe=5b271fa3eb) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| MSI           | CR650                       | [3d3a46f5c6](https://linux-hardware.org/?probe=3d3a46f5c6) | Jan 20, 2023 |
| MSI           | CR650                       | [7d3b1f25c4](https://linux-hardware.org/?probe=7d3b1f25c4) | Jan 20, 2023 |
| Dell          | Inspiron 5391               | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Latitude 7410               | [488f794ad5](https://linux-hardware.org/?probe=488f794ad5) | Jan 20, 2023 |
| Acer          | Aspire A515-57              | [3041b852df](https://linux-hardware.org/?probe=3041b852df) | Jan 20, 2023 |
| Dell          | Inspiron 14 5410            | [beaa2fdddb](https://linux-hardware.org/?probe=beaa2fdddb) | Jan 20, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ccf1934924](https://linux-hardware.org/?probe=ccf1934924) | Jan 20, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [105b2daa8e](https://linux-hardware.org/?probe=105b2daa8e) | Jan 20, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| Apple         | MacBookPro8,1               | [b7f8407c8f](https://linux-hardware.org/?probe=b7f8407c8f) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [ae0457cc50](https://linux-hardware.org/?probe=ae0457cc50) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| Toshiba       | Satellite C70-A             | [ffaa715bdd](https://linux-hardware.org/?probe=ffaa715bdd) | Jan 19, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | [39f2ca64d4](https://linux-hardware.org/?probe=39f2ca64d4) | Jan 19, 2023 |
| Dell          | Vostro 1720                 | [1d06cb4ad8](https://linux-hardware.org/?probe=1d06cb4ad8) | Jan 18, 2023 |
| ASUSTek       | UX32VD                      | [7851952137](https://linux-hardware.org/?probe=7851952137) | Jan 18, 2023 |
| ASUSTek       | X411UN                      | [fad0f7ce44](https://linux-hardware.org/?probe=fad0f7ce44) | Jan 18, 2023 |
| Apple         | MacBookPro5,5               | [3dba9611d3](https://linux-hardware.org/?probe=3dba9611d3) | Jan 18, 2023 |
| Gigabyte      | P15FV5                      | [5a03ba32c0](https://linux-hardware.org/?probe=5a03ba32c0) | Jan 18, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [04d0c02d29](https://linux-hardware.org/?probe=04d0c02d29) | Jan 18, 2023 |
| Dell          | Inspiron 7537               | [95cc108754](https://linux-hardware.org/?probe=95cc108754) | Jan 18, 2023 |
| Packard Be... | EasyNote LE69KB             | [b1caf1d323](https://linux-hardware.org/?probe=b1caf1d323) | Jan 17, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Toshiba       | Satellite L655D             | [38b26485d3](https://linux-hardware.org/?probe=38b26485d3) | Jan 17, 2023 |
| Lenovo        | ThinkPad T61 766112G        | [fb772cc0cf](https://linux-hardware.org/?probe=fb772cc0cf) | Jan 17, 2023 |
| Dell          | Latitude E5540              | [e8e30eb563](https://linux-hardware.org/?probe=e8e30eb563) | Jan 17, 2023 |
| Dell          | Vostro 1720                 | [d02dee9ab2](https://linux-hardware.org/?probe=d02dee9ab2) | Jan 17, 2023 |
| Dell          | Inspiron 14 5418            | [e3bfdaa6a4](https://linux-hardware.org/?probe=e3bfdaa6a4) | Jan 17, 2023 |
| Dell          | Latitude 5410               | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| MSI           | GP70 2OD                    | [7405037963](https://linux-hardware.org/?probe=7405037963) | Jan 17, 2023 |
| HP            | ZBook 14 G2                 | [d501532972](https://linux-hardware.org/?probe=d501532972) | Jan 17, 2023 |
| Toshiba       | Satellite A200              | [68ae2ab1d0](https://linux-hardware.org/?probe=68ae2ab1d0) | Jan 17, 2023 |
| HP            | EliteBook 820 G3            | [4abc3c8796](https://linux-hardware.org/?probe=4abc3c8796) | Jan 17, 2023 |
| Dell          | Studio 1735                 | [96d3df9639](https://linux-hardware.org/?probe=96d3df9639) | Jan 17, 2023 |
| Google        | Lulu                        | [b0e2a5a9b3](https://linux-hardware.org/?probe=b0e2a5a9b3) | Jan 16, 2023 |
| Samsung       | R530/R730/P530              | [e6752958eb](https://linux-hardware.org/?probe=e6752958eb) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7100a33e7e](https://linux-hardware.org/?probe=7100a33e7e) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | Compaq 15                   | [ddfd4fd188](https://linux-hardware.org/?probe=ddfd4fd188) | Jan 15, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Toshiba       | TECRA A11                   | [3d58fc9423](https://linux-hardware.org/?probe=3d58fc9423) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| Acer          | Nitro AN515-44              | [f1e7eba4ca](https://linux-hardware.org/?probe=f1e7eba4ca) | Jan 15, 2023 |
| HP            | ZBook 14 G2                 | [239512c0c1](https://linux-hardware.org/?probe=239512c0c1) | Jan 15, 2023 |
| Acer          | Aspire 7250                 | [bcb2916be8](https://linux-hardware.org/?probe=bcb2916be8) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Dell          | Inspiron 5749               | [445264f815](https://linux-hardware.org/?probe=445264f815) | Jan 15, 2023 |
| Packard Be... | EasyNote ML65               | [e3599cb723](https://linux-hardware.org/?probe=e3599cb723) | Jan 15, 2023 |
| Dell          | Inspiron 5370               | [78b4039791](https://linux-hardware.org/?probe=78b4039791) | Jan 15, 2023 |
| Acer          | Aspire 7551                 | [b3e5df94f4](https://linux-hardware.org/?probe=b3e5df94f4) | Jan 15, 2023 |
| Apple         | MacBookPro9,2               | [2265827caa](https://linux-hardware.org/?probe=2265827caa) | Jan 14, 2023 |
| Lenovo        | G50-45 80E3                 | [ab05084e01](https://linux-hardware.org/?probe=ab05084e01) | Jan 14, 2023 |
| Toshiba       | TECRA A11                   | [758daba5e5](https://linux-hardware.org/?probe=758daba5e5) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | ThinkPad T420 42363C4       | [089518e186](https://linux-hardware.org/?probe=089518e186) | Jan 14, 2023 |
| Toshiba       | PORTEGE Z30-B               | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Samsung       | N150/N210/N220              | [5d2c7b7ded](https://linux-hardware.org/?probe=5d2c7b7ded) | Jan 14, 2023 |
| Lenovo        | G500 20236                  | [d92542c9e8](https://linux-hardware.org/?probe=d92542c9e8) | Jan 14, 2023 |
| Lenovo        | ThinkPad L510 2873A17       | [13f5fd23e5](https://linux-hardware.org/?probe=13f5fd23e5) | Jan 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [56c9afafb4](https://linux-hardware.org/?probe=56c9afafb4) | Jan 14, 2023 |
| Acer          | Aspire 5935                 | [40a8c82828](https://linux-hardware.org/?probe=40a8c82828) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| HP            | EliteBook 820 G3            | [3a330d3173](https://linux-hardware.org/?probe=3a330d3173) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [3df12b0c9c](https://linux-hardware.org/?probe=3df12b0c9c) | Jan 13, 2023 |
| HP            | ProBook 4540s               | [9b33dc4291](https://linux-hardware.org/?probe=9b33dc4291) | Jan 13, 2023 |
| Acer          | Nitro AN515-42              | [940dcb54ef](https://linux-hardware.org/?probe=940dcb54ef) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| ASUSTek       | A7K                         | [5307ba44c0](https://linux-hardware.org/?probe=5307ba44c0) | Jan 13, 2023 |
| ASUSTek       | X751LJ                      | [2cbaf315da](https://linux-hardware.org/?probe=2cbaf315da) | Jan 13, 2023 |
| ASUSTek       | A7K                         | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Teclast       | F6 Plus                     | [27cd155156](https://linux-hardware.org/?probe=27cd155156) | Jan 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [73ca27df51](https://linux-hardware.org/?probe=73ca27df51) | Jan 13, 2023 |
| HP            | Notebook                    | [1baf122d48](https://linux-hardware.org/?probe=1baf122d48) | Jan 13, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [22749c467f](https://linux-hardware.org/?probe=22749c467f) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | [ece6bd7a3c](https://linux-hardware.org/?probe=ece6bd7a3c) | Jan 13, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | [343813c285](https://linux-hardware.org/?probe=343813c285) | Jan 13, 2023 |
| Dell          | System Vostro 3750          | [91b0444e5e](https://linux-hardware.org/?probe=91b0444e5e) | Jan 12, 2023 |
| HP            | 15                          | [b06a589496](https://linux-hardware.org/?probe=b06a589496) | Jan 12, 2023 |
| Acer          | Swift SF314-54G             | [4272389a24](https://linux-hardware.org/?probe=4272389a24) | Jan 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [219ffa8cfd](https://linux-hardware.org/?probe=219ffa8cfd) | Jan 12, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [552d9fd542](https://linux-hardware.org/?probe=552d9fd542) | Jan 12, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [22bd8d5315](https://linux-hardware.org/?probe=22bd8d5315) | Jan 12, 2023 |
| ASUSTek       | T100HAN                     | [7df180ed97](https://linux-hardware.org/?probe=7df180ed97) | Jan 12, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | [4128f195f0](https://linux-hardware.org/?probe=4128f195f0) | Jan 11, 2023 |
| ASUSTek       | N751JK                      | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| HP            | Notebook                    | [3ece4717c4](https://linux-hardware.org/?probe=3ece4717c4) | Jan 11, 2023 |
| HP            | EliteBook 640 14 inch G9... | [a3dacf19d0](https://linux-hardware.org/?probe=a3dacf19d0) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | [47d808cdc7](https://linux-hardware.org/?probe=47d808cdc7) | Jan 10, 2023 |
| Lenovo        | ThinkPad X270 20HN0015FR    | [e303c543ba](https://linux-hardware.org/?probe=e303c543ba) | Jan 10, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [28df55cca2](https://linux-hardware.org/?probe=28df55cca2) | Jan 10, 2023 |
| HP            | EliteBook 8460p             | [27ab381a1d](https://linux-hardware.org/?probe=27ab381a1d) | Jan 10, 2023 |
| Lenovo        | ThinkPad X201 3680AQ1       | [4a65277a98](https://linux-hardware.org/?probe=4a65277a98) | Jan 10, 2023 |
| HP            | Pavilion Notebook           | [f70bd958b7](https://linux-hardware.org/?probe=f70bd958b7) | Jan 10, 2023 |
| HP            | Pavilion Notebook           | [937414941b](https://linux-hardware.org/?probe=937414941b) | Jan 10, 2023 |
| Acer          | Aspire E5-575G              | [21bfdfce4b](https://linux-hardware.org/?probe=21bfdfce4b) | Jan 10, 2023 |
| Dell          | Inspiron 5502               | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| ASUSTek       | X301A1                      | [c98ae98676](https://linux-hardware.org/?probe=c98ae98676) | Jan 09, 2023 |
| Thomson       | N14C4WH64                   | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Dell          | Precision 5560              | [cb05d14e97](https://linux-hardware.org/?probe=cb05d14e97) | Jan 09, 2023 |
| ASUSTek       | K50C                        | [266dd917fe](https://linux-hardware.org/?probe=266dd917fe) | Jan 08, 2023 |
| ASUSTek       | S301LA                      | [9745e5ae33](https://linux-hardware.org/?probe=9745e5ae33) | Jan 08, 2023 |
| Dell          | Inspiron 5593               | [7ada807633](https://linux-hardware.org/?probe=7ada807633) | Jan 08, 2023 |
| Framework     | Laptop                      | [0c13e3ab8d](https://linux-hardware.org/?probe=0c13e3ab8d) | Jan 08, 2023 |
| Lenovo        | G505 20240                  | [e8611b7b9b](https://linux-hardware.org/?probe=e8611b7b9b) | Jan 08, 2023 |
| ASUSTek       | N73SV                       | [4cf1c4b702](https://linux-hardware.org/?probe=4cf1c4b702) | Jan 08, 2023 |
| ASUSTek       | G750JX                      | [128fe1567d](https://linux-hardware.org/?probe=128fe1567d) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| HP            | Compaq 6910p                | [8ba65cb6b5](https://linux-hardware.org/?probe=8ba65cb6b5) | Jan 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| HP            | Laptop 15-db0xxx            | [ff51bb2dd9](https://linux-hardware.org/?probe=ff51bb2dd9) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4291T4Y       | [b1c7c505b2](https://linux-hardware.org/?probe=b1c7c505b2) | Jan 07, 2023 |
| HP            | EliteBook 850 G6            | [595e6fa89a](https://linux-hardware.org/?probe=595e6fa89a) | Jan 07, 2023 |
| Dell          | Latitude E6410              | [f664cab1c4](https://linux-hardware.org/?probe=f664cab1c4) | Jan 07, 2023 |
| Acer          | Aspire E5-772G              | [c840cf9ca5](https://linux-hardware.org/?probe=c840cf9ca5) | Jan 07, 2023 |
| Lenovo        | G505 20240                  | [a2910be7b2](https://linux-hardware.org/?probe=a2910be7b2) | Jan 07, 2023 |
| Lenovo        | ThinkPad T530 2392CTO       | [8c1cf48875](https://linux-hardware.org/?probe=8c1cf48875) | Jan 07, 2023 |
| Framework     | Laptop                      | [cfabfdec3c](https://linux-hardware.org/?probe=cfabfdec3c) | Jan 07, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [8f013ca042](https://linux-hardware.org/?probe=8f013ca042) | Jan 07, 2023 |
| Lenovo        | IdeaPad S300 9803           | [1f31e39066](https://linux-hardware.org/?probe=1f31e39066) | Jan 07, 2023 |
| HP            | ZBook Studio G5             | [dfd35ce9ca](https://linux-hardware.org/?probe=dfd35ce9ca) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [41e6bde836](https://linux-hardware.org/?probe=41e6bde836) | Jan 06, 2023 |
| Lenovo        | ThinkPad X200s 7469A98      | [475d16af35](https://linux-hardware.org/?probe=475d16af35) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | [cd1fc92879](https://linux-hardware.org/?probe=cd1fc92879) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Valve         | Jupiter                     | [aa4288024c](https://linux-hardware.org/?probe=aa4288024c) | Jan 05, 2023 |
| HP            | Notebook                    | [e63dc1a81a](https://linux-hardware.org/?probe=e63dc1a81a) | Jan 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [892ada8934](https://linux-hardware.org/?probe=892ada8934) | Jan 05, 2023 |
| ASUSTek       | F50SV                       | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| Dell          | Precision 7520              | [10c791a9f5](https://linux-hardware.org/?probe=10c791a9f5) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| ASUSTek       | N73SV                       | [4ed6689d7c](https://linux-hardware.org/?probe=4ed6689d7c) | Jan 05, 2023 |
| HP            | ProBook 470 G2              | [1f62ff6417](https://linux-hardware.org/?probe=1f62ff6417) | Jan 04, 2023 |
| UNOWHY        | Y13G011S4EI                 | [1e25e7059a](https://linux-hardware.org/?probe=1e25e7059a) | Jan 04, 2023 |
| ASUSTek       | N73SV                       | [2cba5c99c4](https://linux-hardware.org/?probe=2cba5c99c4) | Jan 04, 2023 |
| HP            | ProBook 6570b               | [875054c6d7](https://linux-hardware.org/?probe=875054c6d7) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [028f9b0434](https://linux-hardware.org/?probe=028f9b0434) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire V3-772G              | [fac5053200](https://linux-hardware.org/?probe=fac5053200) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | Stream Notebook             | [0cacfea12c](https://linux-hardware.org/?probe=0cacfea12c) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| HP            | ZBook 15 G3                 | [7ef67aea7b](https://linux-hardware.org/?probe=7ef67aea7b) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| Dell          | System Inspiron N411Z       | [21f279751c](https://linux-hardware.org/?probe=21f279751c) | Jan 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [aba076d86d](https://linux-hardware.org/?probe=aba076d86d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Acer          | Aspire SW3-013              | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1E70... | [c13c5e3d0d](https://linux-hardware.org/?probe=c13c5e3d0d) | Jan 01, 2023 |
| ASUSTek       | S551LN                      | [12629ba25d](https://linux-hardware.org/?probe=12629ba25d) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [f438866c0d](https://linux-hardware.org/?probe=f438866c0d) | Jan 01, 2023 |
| HP            | Pavilion dv6                | [30ec83dbd4](https://linux-hardware.org/?probe=30ec83dbd4) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Laptop 17-cn1xxx            | [dde4bcd574](https://linux-hardware.org/?probe=dde4bcd574) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [d44828a455](https://linux-hardware.org/?probe=d44828a455) | Dec 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [afa28ba4f3](https://linux-hardware.org/?probe=afa28ba4f3) | Dec 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [80abf89bc6](https://linux-hardware.org/?probe=80abf89bc6) | Dec 30, 2022 |
| Acer          | Nitro AN515-57              | [b0bfa9530a](https://linux-hardware.org/?probe=b0bfa9530a) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| ASUSTek       | G1                          | [1f8e426f96](https://linux-hardware.org/?probe=1f8e426f96) | Dec 29, 2022 |
| Toshiba       | Satellite C870-13V          | [5ad370d470](https://linux-hardware.org/?probe=5ad370d470) | Dec 29, 2022 |
| Acer          | Aspire 4820TG               | [77721c13c4](https://linux-hardware.org/?probe=77721c13c4) | Dec 29, 2022 |
| ASUSTek       | GL553VD                     | [9c4eab8774](https://linux-hardware.org/?probe=9c4eab8774) | Dec 29, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Shenzhen W... | TANK56                      | [4cd3e6c8e4](https://linux-hardware.org/?probe=4cd3e6c8e4) | Dec 29, 2022 |
| Lenovo        | G50-70 20351                | [6ece20ec58](https://linux-hardware.org/?probe=6ece20ec58) | Dec 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [499c91958a](https://linux-hardware.org/?probe=499c91958a) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [b915fc0d47](https://linux-hardware.org/?probe=b915fc0d47) | Dec 28, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [74c1f3a4c2](https://linux-hardware.org/?probe=74c1f3a4c2) | Dec 28, 2022 |
| ASUSTek       | X555BP                      | [6ddc84aa0d](https://linux-hardware.org/?probe=6ddc84aa0d) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | [2966924363](https://linux-hardware.org/?probe=2966924363) | Dec 28, 2022 |
| Toshiba       | Satellite C55-C             | [f3e27d230f](https://linux-hardware.org/?probe=f3e27d230f) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30T-A              | [cab72e8a11](https://linux-hardware.org/?probe=cab72e8a11) | Dec 28, 2022 |
| Dell          | G3 3500                     | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | G56JR                       | [3acee33976](https://linux-hardware.org/?probe=3acee33976) | Dec 27, 2022 |
| Acer          | Aspire SW3-013              | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | [6fbb0cbd09](https://linux-hardware.org/?probe=6fbb0cbd09) | Dec 27, 2022 |
| Dell          | Inspiron 5579               | [838cda532a](https://linux-hardware.org/?probe=838cda532a) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Acer          | Nitro AN515-57              | [8ecb7e11b3](https://linux-hardware.org/?probe=8ecb7e11b3) | Dec 26, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Acer          | Swift SF314-43              | [f7c9b3538e](https://linux-hardware.org/?probe=f7c9b3538e) | Dec 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [6703f01cfc](https://linux-hardware.org/?probe=6703f01cfc) | Dec 26, 2022 |
| ASUSTek       | K61IC                       | [4c34b8d5a1](https://linux-hardware.org/?probe=4c34b8d5a1) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [e47f890444](https://linux-hardware.org/?probe=e47f890444) | Dec 26, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [c288ade12d](https://linux-hardware.org/?probe=c288ade12d) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| MSI           | CR700                       | [92b97fec48](https://linux-hardware.org/?probe=92b97fec48) | Dec 25, 2022 |
| MSI           | CR700                       | [df25c10894](https://linux-hardware.org/?probe=df25c10894) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | [5497596ef1](https://linux-hardware.org/?probe=5497596ef1) | Dec 25, 2022 |
| HONOR         | BOD-WXX9                    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| HP            | ProBook 450 G1              | [26c346f0ab](https://linux-hardware.org/?probe=26c346f0ab) | Dec 25, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [08af6df0dd](https://linux-hardware.org/?probe=08af6df0dd) | Dec 25, 2022 |
| HP            | ENVY 17                     | [f3458ee7d5](https://linux-hardware.org/?probe=f3458ee7d5) | Dec 25, 2022 |
| HP            | ENVY Notebook               | [16af8b4da3](https://linux-hardware.org/?probe=16af8b4da3) | Dec 25, 2022 |
| Lenovo        | ThinkPad L530 24781P9       | [fd8de03405](https://linux-hardware.org/?probe=fd8de03405) | Dec 25, 2022 |
| Lenovo        | Yoga 2 13 20344             | [9d8bce4c41](https://linux-hardware.org/?probe=9d8bce4c41) | Dec 25, 2022 |
| Lenovo        | ThinkPad X220 4291UUC       | [6307be520e](https://linux-hardware.org/?probe=6307be520e) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a1f4999c28](https://linux-hardware.org/?probe=a1f4999c28) | Dec 25, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Dell          | XPS 15 9510                 | [6c809c224c](https://linux-hardware.org/?probe=6c809c224c) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2b71327126](https://linux-hardware.org/?probe=2b71327126) | Dec 24, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0AY0... | [28e67f37bc](https://linux-hardware.org/?probe=28e67f37bc) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [dab48b870c](https://linux-hardware.org/?probe=dab48b870c) | Dec 23, 2022 |
| HP            | Pavilion 17                 | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0d1532282f](https://linux-hardware.org/?probe=0d1532282f) | Dec 23, 2022 |
| Acer          | E1-510                      | [463c668d4e](https://linux-hardware.org/?probe=463c668d4e) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| Acer          | TravelMate 7730             | [8d166266b9](https://linux-hardware.org/?probe=8d166266b9) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Acer          | Aspire E5-575G              | [bc197d71d8](https://linux-hardware.org/?probe=bc197d71d8) | Dec 23, 2022 |
| Danew         | Dbook 131                   | [25dbe464cd](https://linux-hardware.org/?probe=25dbe464cd) | Dec 23, 2022 |
| HP            | ProBook 440 G7              | [33a03f23cc](https://linux-hardware.org/?probe=33a03f23cc) | Dec 23, 2022 |
| Dell          | Inspiron 1546               | [7812af7998](https://linux-hardware.org/?probe=7812af7998) | Dec 23, 2022 |
| Unknown       | Unknown                     | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion 17                 | [65dcf1eead](https://linux-hardware.org/?probe=65dcf1eead) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | 1015BXO                     | [7cce9a65ec](https://linux-hardware.org/?probe=7cce9a65ec) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [47ac3ac319](https://linux-hardware.org/?probe=47ac3ac319) | Dec 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | [fd0cb86f82](https://linux-hardware.org/?probe=fd0cb86f82) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c0f4dfeb74](https://linux-hardware.org/?probe=c0f4dfeb74) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Acer          | TravelMate 7730             | [8078925015](https://linux-hardware.org/?probe=8078925015) | Dec 20, 2022 |
| LG Electro... | 17Z90P-G.AA56F              | [fa43417151](https://linux-hardware.org/?probe=fa43417151) | Dec 19, 2022 |
| ASUSTek       | S551LN                      | [df4a754b5d](https://linux-hardware.org/?probe=df4a754b5d) | Dec 19, 2022 |
| ASUSTek       | X75VC                       | [a16ed79c3d](https://linux-hardware.org/?probe=a16ed79c3d) | Dec 19, 2022 |
| ASUSTek       | X550MD                      | [16f09c5918](https://linux-hardware.org/?probe=16f09c5918) | Dec 19, 2022 |
| Dell          | Inspiron 7720               | [f29071b4a8](https://linux-hardware.org/?probe=f29071b4a8) | Dec 18, 2022 |
| HP            | ProBook 4720s               | [cd684d5dbe](https://linux-hardware.org/?probe=cd684d5dbe) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| HP            | EliteBook 850 G3            | [72eccc0663](https://linux-hardware.org/?probe=72eccc0663) | Dec 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [83887c3224](https://linux-hardware.org/?probe=83887c3224) | Dec 18, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| Toshiba       | Satellite C50D-A-12M        | [fa522940dd](https://linux-hardware.org/?probe=fa522940dd) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Notebook      | W65_67SZ                    | [770c00f7d9](https://linux-hardware.org/?probe=770c00f7d9) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| HP            | EliteBook 840 G4            | [25b640f2ed](https://linux-hardware.org/?probe=25b640f2ed) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Dell          | XPS 13 9380                 | [719f489e01](https://linux-hardware.org/?probe=719f489e01) | Dec 15, 2022 |
| Fujitsu       | LIFEBOOK E734               | [ff5206e8e0](https://linux-hardware.org/?probe=ff5206e8e0) | Dec 15, 2022 |
| Dell          | Latitude E6430              | [1da4bd3e02](https://linux-hardware.org/?probe=1da4bd3e02) | Dec 15, 2022 |
| HP            | Presario CQ62               | [fce21eae2c](https://linux-hardware.org/?probe=fce21eae2c) | Dec 15, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [31bf14c8d8](https://linux-hardware.org/?probe=31bf14c8d8) | Dec 15, 2022 |
| Toshiba       | Satellite Pro L300          | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| Apple         | MacBookPro5,4               | [902c809015](https://linux-hardware.org/?probe=902c809015) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| Toshiba       | PORTEGE R830                | [0d5af64ca4](https://linux-hardware.org/?probe=0d5af64ca4) | Dec 14, 2022 |
| Dell          | Latitude E7450              | [196b96ea5e](https://linux-hardware.org/?probe=196b96ea5e) | Dec 14, 2022 |
| ASUSTek       | X705UAP                     | [8080afc7d4](https://linux-hardware.org/?probe=8080afc7d4) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| HP            | ProBook 6570b               | [a6b67497a1](https://linux-hardware.org/?probe=a6b67497a1) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [257e692fa4](https://linux-hardware.org/?probe=257e692fa4) | Dec 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [f803c32eae](https://linux-hardware.org/?probe=f803c32eae) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [5cdd66c849](https://linux-hardware.org/?probe=5cdd66c849) | Dec 11, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [474f4f4c43](https://linux-hardware.org/?probe=474f4f4c43) | Dec 11, 2022 |
| ASUSTek       | X75VD                       | [624ea43f9d](https://linux-hardware.org/?probe=624ea43f9d) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [591f0ad589](https://linux-hardware.org/?probe=591f0ad589) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Alienware     | m17 R2                      | [76a2c6b1ca](https://linux-hardware.org/?probe=76a2c6b1ca) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| Acer          | Aspire E5-573G              | [ec1e8e146a](https://linux-hardware.org/?probe=ec1e8e146a) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | [350102190e](https://linux-hardware.org/?probe=350102190e) | Dec 10, 2022 |
| HP            | EliteBook 840 G1            | [688e981eee](https://linux-hardware.org/?probe=688e981eee) | Dec 10, 2022 |
| Dell          | Precision 5550              | [ad172b99ad](https://linux-hardware.org/?probe=ad172b99ad) | Dec 10, 2022 |
| Dell          | XPS 17 9700                 | [0426545e91](https://linux-hardware.org/?probe=0426545e91) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [26e2759694](https://linux-hardware.org/?probe=26e2759694) | Dec 10, 2022 |
| Valve         | Jupiter                     | [1e314d59ee](https://linux-hardware.org/?probe=1e314d59ee) | Dec 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [91b65d2fa1](https://linux-hardware.org/?probe=91b65d2fa1) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| Toshiba       | Satellite L500              | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HP            | Pavilion Notebook           | [8cc721f649](https://linux-hardware.org/?probe=8cc721f649) | Dec 08, 2022 |
| Dell          | Precision 7720              | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| HP            | x360 310 G1 PC              | [297806eac9](https://linux-hardware.org/?probe=297806eac9) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | K55VD                       | [469f0a1d1f](https://linux-hardware.org/?probe=469f0a1d1f) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [bf8647ecdc](https://linux-hardware.org/?probe=bf8647ecdc) | Dec 07, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [dfc7911df2](https://linux-hardware.org/?probe=dfc7911df2) | Dec 07, 2022 |
| HP            | ZBook 15 G6                 | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [82d49749a2](https://linux-hardware.org/?probe=82d49749a2) | Dec 07, 2022 |
| Dell          | Latitude E6410              | [0c768fd820](https://linux-hardware.org/?probe=0c768fd820) | Dec 07, 2022 |
| BESSTAR Te... | U820                        | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | Compaq 6910p                | [10b301f77e](https://linux-hardware.org/?probe=10b301f77e) | Dec 07, 2022 |
| Dell          | Inspiron 7720               | [180d05d4c1](https://linux-hardware.org/?probe=180d05d4c1) | Dec 06, 2022 |
| Acer          | Aspire E5-772               | [35c8c05d6c](https://linux-hardware.org/?probe=35c8c05d6c) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [fccbb1fcec](https://linux-hardware.org/?probe=fccbb1fcec) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [1f1c509e41](https://linux-hardware.org/?probe=1f1c509e41) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [eaf904a47a](https://linux-hardware.org/?probe=eaf904a47a) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| Apple         | MacBookPro5,4               | [bd98ec1bcb](https://linux-hardware.org/?probe=bd98ec1bcb) | Dec 05, 2022 |
| Dell          | Inspiron 5502               | [311215d00b](https://linux-hardware.org/?probe=311215d00b) | Dec 05, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [f90956a720](https://linux-hardware.org/?probe=f90956a720) | Dec 05, 2022 |
| eMachines     | E520 V1.06                  | [0ef424fa9b](https://linux-hardware.org/?probe=0ef424fa9b) | Dec 05, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [3dfd18754f](https://linux-hardware.org/?probe=3dfd18754f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| HP            | x360 310 G1 PC              | [b15b39727b](https://linux-hardware.org/?probe=b15b39727b) | Dec 04, 2022 |
| Sony          | VPCEL2S1E                   | [0c98b9d570](https://linux-hardware.org/?probe=0c98b9d570) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Dell          | Latitude E5510              | [6027856ab6](https://linux-hardware.org/?probe=6027856ab6) | Dec 03, 2022 |
| HP            | Laptop 15s-fr2xxx           | [623e794238](https://linux-hardware.org/?probe=623e794238) | Dec 03, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [716a6802ca](https://linux-hardware.org/?probe=716a6802ca) | Dec 03, 2022 |
| Fujitsu       | CELSIUS H720                | [a7eacb37c5](https://linux-hardware.org/?probe=a7eacb37c5) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| HP            | Stream Notebook             | [dc16cc5c95](https://linux-hardware.org/?probe=dc16cc5c95) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [78f2f440eb](https://linux-hardware.org/?probe=78f2f440eb) | Dec 02, 2022 |
| Valve         | Jupiter                     | [f54147a5ba](https://linux-hardware.org/?probe=f54147a5ba) | Dec 02, 2022 |
| HP            | EliteBook 865 16 inch G9... | [33b77409e5](https://linux-hardware.org/?probe=33b77409e5) | Dec 02, 2022 |
| HP            | Notebook                    | [c42eef153d](https://linux-hardware.org/?probe=c42eef153d) | Dec 02, 2022 |
| Dell          | Inspiron 16 5625            | [6e1523c2e8](https://linux-hardware.org/?probe=6e1523c2e8) | Dec 02, 2022 |
| Valve         | Jupiter                     | [4f32d4f1c2](https://linux-hardware.org/?probe=4f32d4f1c2) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [be8f757095](https://linux-hardware.org/?probe=be8f757095) | Dec 02, 2022 |
| HP            | ProBook 6570b               | [1e40d6a94b](https://linux-hardware.org/?probe=1e40d6a94b) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c19e5b9f4b](https://linux-hardware.org/?probe=c19e5b9f4b) | Dec 02, 2022 |
| HP            | 250 G8 Notebook PC          | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Lenovo        | ThinkPad T61 6463WAP        | [e11baa0e49](https://linux-hardware.org/?probe=e11baa0e49) | Dec 02, 2022 |
| AZW           | SEi                         | [3cd2f7f657](https://linux-hardware.org/?probe=3cd2f7f657) | Dec 01, 2022 |
| Samsung       | R540/R538/SA41/E452         | [afad3c8828](https://linux-hardware.org/?probe=afad3c8828) | Dec 01, 2022 |
| HP            | 250 G7 Notebook PC          | [1002df8858](https://linux-hardware.org/?probe=1002df8858) | Dec 01, 2022 |
| Samsung       | 930XED                      | [38584fa129](https://linux-hardware.org/?probe=38584fa129) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| ASUSTek       | S551LN                      | [b21b106fdf](https://linux-hardware.org/?probe=b21b106fdf) | Dec 01, 2022 |
| HP            | EliteBook 840 G3            | [e17d8c1694](https://linux-hardware.org/?probe=e17d8c1694) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Packard Be... | EasyNote TE69CXP            | [919275eb73](https://linux-hardware.org/?probe=919275eb73) | Nov 30, 2022 |
| HP            | ZBook 15v G5                | [aabc35ae2a](https://linux-hardware.org/?probe=aabc35ae2a) | Nov 30, 2022 |
| ASUSTek       | E403SA                      | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Lenovo        | G70-80 80FF                 | [022ce8e2c8](https://linux-hardware.org/?probe=022ce8e2c8) | Nov 29, 2022 |
| HP            | Pavilion 17                 | [431ce9bd18](https://linux-hardware.org/?probe=431ce9bd18) | Nov 29, 2022 |
| Dell          | Latitude E6410              | [d7abefea4b](https://linux-hardware.org/?probe=d7abefea4b) | Nov 29, 2022 |
| Dell          | Latitude E6410              | [bac3e8c250](https://linux-hardware.org/?probe=bac3e8c250) | Nov 29, 2022 |
| Dell          | Latitude 5330               | [b8d907f2e8](https://linux-hardware.org/?probe=b8d907f2e8) | Nov 29, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Dell          | Inspiron 16 5625            | [50912d5fa9](https://linux-hardware.org/?probe=50912d5fa9) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Dell          | System Vostro 3750          | [ed88e2ae0c](https://linux-hardware.org/?probe=ed88e2ae0c) | Nov 29, 2022 |
| Thomson       | N17V3C8WH512                | [b89cd0328a](https://linux-hardware.org/?probe=b89cd0328a) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| ASUSTek       | K70IO                       | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Dell          | Inspiron 16 5625            | [22da2f8729](https://linux-hardware.org/?probe=22da2f8729) | Nov 28, 2022 |
| ASUSTek       | X756UVK                     | [4745940cf9](https://linux-hardware.org/?probe=4745940cf9) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2d1a576ee6](https://linux-hardware.org/?probe=2d1a576ee6) | Nov 27, 2022 |
| HP            | Compaq Presario CQ60        | [1f521f98cb](https://linux-hardware.org/?probe=1f521f98cb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Jumper        | EZbook                      | [a93aa75e5f](https://linux-hardware.org/?probe=a93aa75e5f) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude 7310               | [46ed677d40](https://linux-hardware.org/?probe=46ed677d40) | Nov 26, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [694d1d5e96](https://linux-hardware.org/?probe=694d1d5e96) | Nov 26, 2022 |
| MSI           | GL62M 7RDX                  | [1aa67b30d4](https://linux-hardware.org/?probe=1aa67b30d4) | Nov 26, 2022 |
| Dell          | Inspiron MP061              | [d70d7496df](https://linux-hardware.org/?probe=d70d7496df) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion 15                 | [b294971fc6](https://linux-hardware.org/?probe=b294971fc6) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| Dell          | Latitude 7310               | [0f9c2a5623](https://linux-hardware.org/?probe=0f9c2a5623) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [ce586530e4](https://linux-hardware.org/?probe=ce586530e4) | Nov 24, 2022 |
| Dell          | Latitude 7310               | [d7448aaff8](https://linux-hardware.org/?probe=d7448aaff8) | Nov 24, 2022 |
| Acer          | Aspire ES1-523              | [333d3583b1](https://linux-hardware.org/?probe=333d3583b1) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [4b6212908f](https://linux-hardware.org/?probe=4b6212908f) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [69c89370b7](https://linux-hardware.org/?probe=69c89370b7) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| Dell          | Latitude 7310               | [836fbd119c](https://linux-hardware.org/?probe=836fbd119c) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [9e1f0c4898](https://linux-hardware.org/?probe=9e1f0c4898) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| ASUSTek       | K70IJ                       | [8df764e624](https://linux-hardware.org/?probe=8df764e624) | Nov 23, 2022 |
| MSI           | Modern 14 C12M              | [51088606f5](https://linux-hardware.org/?probe=51088606f5) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f1d8974d71](https://linux-hardware.org/?probe=f1d8974d71) | Nov 23, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| HP            | ENVY dv6                    | [0d28d09c70](https://linux-hardware.org/?probe=0d28d09c70) | Nov 22, 2022 |
| Dell          | Latitude E6520              | [1801edca03](https://linux-hardware.org/?probe=1801edca03) | Nov 22, 2022 |
| HP            | ProBook 450 G1              | [c8d71bb807](https://linux-hardware.org/?probe=c8d71bb807) | Nov 22, 2022 |
| Timi          | TM1612                      | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| Dell          | Precision 5510              | [63c0b8aa0c](https://linux-hardware.org/?probe=63c0b8aa0c) | Nov 21, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [c3048ea26d](https://linux-hardware.org/?probe=c3048ea26d) | Nov 21, 2022 |
| HP            | Pavilion Notebook           | [9599fd68a9](https://linux-hardware.org/?probe=9599fd68a9) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [eb43c3d5c0](https://linux-hardware.org/?probe=eb43c3d5c0) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [6a51b20cd4](https://linux-hardware.org/?probe=6a51b20cd4) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion g7                 | [fae1d08109](https://linux-hardware.org/?probe=fae1d08109) | Nov 19, 2022 |
| Google        | Rammus                      | [23ed7badd5](https://linux-hardware.org/?probe=23ed7badd5) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| HP            | EliteBook 840 G3            | [a5151a0db4](https://linux-hardware.org/?probe=a5151a0db4) | Nov 18, 2022 |
| Dell          | Latitude 7300               | [5ff7502b3e](https://linux-hardware.org/?probe=5ff7502b3e) | Nov 18, 2022 |
| Dell          | Latitude 7310               | [525543a3dc](https://linux-hardware.org/?probe=525543a3dc) | Nov 18, 2022 |
| Dell          | Latitude 7300               | [5c7f8f6d8c](https://linux-hardware.org/?probe=5c7f8f6d8c) | Nov 18, 2022 |
| HP            | Pavilion 17                 | [ab34ec642d](https://linux-hardware.org/?probe=ab34ec642d) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [94bd888b25](https://linux-hardware.org/?probe=94bd888b25) | Nov 18, 2022 |
| Acer          | Aspire S5-371               | [6274604555](https://linux-hardware.org/?probe=6274604555) | Nov 18, 2022 |
| Acer          | Swift SF314-42              | [12e2119f1c](https://linux-hardware.org/?probe=12e2119f1c) | Nov 18, 2022 |
| Dell          | Latitude 5520               | [72bcc12409](https://linux-hardware.org/?probe=72bcc12409) | Nov 18, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [88336d65e7](https://linux-hardware.org/?probe=88336d65e7) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | [17a064a3c3](https://linux-hardware.org/?probe=17a064a3c3) | Nov 17, 2022 |
| MSI           | Prestige 14 A12SC           | [008c444627](https://linux-hardware.org/?probe=008c444627) | Nov 17, 2022 |
| HP            | EliteBook 840 G3            | [cd753ace10](https://linux-hardware.org/?probe=cd753ace10) | Nov 17, 2022 |
| Apple         | MacBookAir7,2               | [6901439af7](https://linux-hardware.org/?probe=6901439af7) | Nov 17, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Dell          | Latitude 7300               | [462f090e8c](https://linux-hardware.org/?probe=462f090e8c) | Nov 17, 2022 |
| Dell          | Latitude 7380               | [c34f569e5a](https://linux-hardware.org/?probe=c34f569e5a) | Nov 17, 2022 |
| Dell          | Latitude 7380               | [ff8bc9f174](https://linux-hardware.org/?probe=ff8bc9f174) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | [c084bd4b99](https://linux-hardware.org/?probe=c084bd4b99) | Nov 17, 2022 |
| HP            | ZBook 14 G2                 | [e687234452](https://linux-hardware.org/?probe=e687234452) | Nov 17, 2022 |
| Dynabook E... | PORTABLECD2021              | [5d138b93b6](https://linux-hardware.org/?probe=5d138b93b6) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| MSI           | Katana GF76 11UC            | [24ba2f8b12](https://linux-hardware.org/?probe=24ba2f8b12) | Nov 16, 2022 |
| ASUSTek       | T100TA                      | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| HUAWEI        | HLYL-WXX9                   | [f863546b0f](https://linux-hardware.org/?probe=f863546b0f) | Nov 16, 2022 |
| Google        | Rammus                      | [ef0f440314](https://linux-hardware.org/?probe=ef0f440314) | Nov 16, 2022 |
| AMI           | Intel                       | [36327e3aca](https://linux-hardware.org/?probe=36327e3aca) | Nov 16, 2022 |
| HP            | Notebook                    | [d40f2df5a8](https://linux-hardware.org/?probe=d40f2df5a8) | Nov 16, 2022 |
| HP            | 250 G6 Notebook PC          | [439fe62e2e](https://linux-hardware.org/?probe=439fe62e2e) | Nov 15, 2022 |
| LDLC          | SPC-N                       | [acec489419](https://linux-hardware.org/?probe=acec489419) | Nov 15, 2022 |
| HP            | Pavilion 17                 | [de4e2c6446](https://linux-hardware.org/?probe=de4e2c6446) | Nov 15, 2022 |
| Acer          | Aspire E5-722               | [7e26ae7fe8](https://linux-hardware.org/?probe=7e26ae7fe8) | Nov 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [298f1bd357](https://linux-hardware.org/?probe=298f1bd357) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [d8e3815f50](https://linux-hardware.org/?probe=d8e3815f50) | Nov 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f532c6bdb1](https://linux-hardware.org/?probe=f532c6bdb1) | Nov 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2dddaa52cd](https://linux-hardware.org/?probe=2dddaa52cd) | Nov 13, 2022 |
| Dell          | Vostro 3578                 | [1fa1c16736](https://linux-hardware.org/?probe=1fa1c16736) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | [9a214b41ec](https://linux-hardware.org/?probe=9a214b41ec) | Nov 13, 2022 |
| Alienware     | M17xR4                      | [9dbd88c02e](https://linux-hardware.org/?probe=9dbd88c02e) | Nov 13, 2022 |
| UNOWHY        | Y13G012S4EI                 | [51a7b4fca7](https://linux-hardware.org/?probe=51a7b4fca7) | Nov 12, 2022 |
| Lenovo        | Yoga 2 13 20344             | [deb10be02b](https://linux-hardware.org/?probe=deb10be02b) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0e3e3c885a](https://linux-hardware.org/?probe=0e3e3c885a) | Nov 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2421b6c5a4](https://linux-hardware.org/?probe=2421b6c5a4) | Nov 11, 2022 |
| Dell          | Inspiron 3543               | [227f62cdb9](https://linux-hardware.org/?probe=227f62cdb9) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| SHENZHEN Y... | A8S PRO                     | [354471ab24](https://linux-hardware.org/?probe=354471ab24) | Nov 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [1fa4637d27](https://linux-hardware.org/?probe=1fa4637d27) | Nov 10, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [cd4796484a](https://linux-hardware.org/?probe=cd4796484a) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [e77f7ce44e](https://linux-hardware.org/?probe=e77f7ce44e) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| SHENZHEN Y... | A8S PRO                     | [e6b195843f](https://linux-hardware.org/?probe=e6b195843f) | Nov 09, 2022 |
| Dell          | Precision 5540              | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Dell          | Latitude 5420               | [2eba4932bf](https://linux-hardware.org/?probe=2eba4932bf) | Nov 09, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [97ed2f1140](https://linux-hardware.org/?probe=97ed2f1140) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [1cca3aa247](https://linux-hardware.org/?probe=1cca3aa247) | Nov 08, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [9fe97ad66f](https://linux-hardware.org/?probe=9fe97ad66f) | Nov 08, 2022 |
| HP            | Laptop 14s-dq2xxx           | [6c277d54f9](https://linux-hardware.org/?probe=6c277d54f9) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [f0c2157642](https://linux-hardware.org/?probe=f0c2157642) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| HP            | EliteBook 8470p             | [e94c6ad334](https://linux-hardware.org/?probe=e94c6ad334) | Nov 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | [29fd694ada](https://linux-hardware.org/?probe=29fd694ada) | Nov 07, 2022 |
| Dell          | G3 3500                     | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Acer          | Nitro AN515-52              | [cbfa344eaa](https://linux-hardware.org/?probe=cbfa344eaa) | Nov 07, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [08c701b06d](https://linux-hardware.org/?probe=08c701b06d) | Nov 06, 2022 |
| Dell          | Latitude E7470              | [1bd39e96d2](https://linux-hardware.org/?probe=1bd39e96d2) | Nov 06, 2022 |
| HP            | Unknown                     | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [d1bcd9dd18](https://linux-hardware.org/?probe=d1bcd9dd18) | Nov 06, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [2c0e88be3e](https://linux-hardware.org/?probe=2c0e88be3e) | Nov 06, 2022 |
| Thomson       | N17V3C8WH512                | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7e97bace0c](https://linux-hardware.org/?probe=7e97bace0c) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [d793aac21d](https://linux-hardware.org/?probe=d793aac21d) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| Thomson       | NEO14A-4SL128               | [5f6993914c](https://linux-hardware.org/?probe=5f6993914c) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | [0df719375b](https://linux-hardware.org/?probe=0df719375b) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| ASUSTek       | UX303UA                     | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Lenovo        | ThinkPad E570 20H50078FR    | [156f337a82](https://linux-hardware.org/?probe=156f337a82) | Nov 05, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | [94abd977de](https://linux-hardware.org/?probe=94abd977de) | Nov 04, 2022 |
| ASUSTek       | X556URK                     | [c26a3705d3](https://linux-hardware.org/?probe=c26a3705d3) | Nov 04, 2022 |
| HP            | ProBook 6470b               | [78aa59a89a](https://linux-hardware.org/?probe=78aa59a89a) | Nov 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [8fdaec6b5a](https://linux-hardware.org/?probe=8fdaec6b5a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [17bac11f6f](https://linux-hardware.org/?probe=17bac11f6f) | Nov 04, 2022 |
| HP            | 470 G7 Notebook PC          | [ae68dc3b2d](https://linux-hardware.org/?probe=ae68dc3b2d) | Nov 04, 2022 |
| UNOWHY        | Y13G011S4EI                 | [da784a5c82](https://linux-hardware.org/?probe=da784a5c82) | Nov 04, 2022 |
| Notebook      | NL40_50GU                   | [c74ffe668a](https://linux-hardware.org/?probe=c74ffe668a) | Nov 03, 2022 |
| Notebook      | NL40_50GU                   | [b3001401db](https://linux-hardware.org/?probe=b3001401db) | Nov 03, 2022 |
| HP            | ProBook 6470b               | [ea7c42479d](https://linux-hardware.org/?probe=ea7c42479d) | Nov 03, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [7e09b1e9bd](https://linux-hardware.org/?probe=7e09b1e9bd) | Nov 03, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ce4f615c70](https://linux-hardware.org/?probe=ce4f615c70) | Nov 03, 2022 |
| HP            | EliteBook 840 G2            | [a189602082](https://linux-hardware.org/?probe=a189602082) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fe4a007f99](https://linux-hardware.org/?probe=fe4a007f99) | Nov 03, 2022 |
| HP            | EliteBook 8470p             | [d754cc7217](https://linux-hardware.org/?probe=d754cc7217) | Nov 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [dfe209bf08](https://linux-hardware.org/?probe=dfe209bf08) | Nov 03, 2022 |
| Dell          | G15 5511                    | [6965880757](https://linux-hardware.org/?probe=6965880757) | Nov 02, 2022 |
| HP            | Laptop 15-db0xxx            | [14184ac3d9](https://linux-hardware.org/?probe=14184ac3d9) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | [7a421ed810](https://linux-hardware.org/?probe=7a421ed810) | Nov 02, 2022 |
| Toshiba       | Satellite C70D-A            | [d82227846b](https://linux-hardware.org/?probe=d82227846b) | Nov 02, 2022 |
| Dell          | G3 3500                     | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| Dell          | Latitude 5420               | [679fbcb14f](https://linux-hardware.org/?probe=679fbcb14f) | Nov 02, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [9fa0489d64](https://linux-hardware.org/?probe=9fa0489d64) | Nov 01, 2022 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [411a5da53c](https://linux-hardware.org/?probe=411a5da53c) | Nov 01, 2022 |
| Acer          | Swift SF314-42              | [6a0d7d5f39](https://linux-hardware.org/?probe=6a0d7d5f39) | Nov 01, 2022 |
| HP            | Pavilion dv5                | [fb23cec1a6](https://linux-hardware.org/?probe=fb23cec1a6) | Nov 01, 2022 |
| Toshiba       | Satellite C70D-B            | [ccf4e200fb](https://linux-hardware.org/?probe=ccf4e200fb) | Nov 01, 2022 |
| Valve         | Jupiter                     | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| ASUSTek       | S551LN                      | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| Valve         | Jupiter                     | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Acer          | Swift SF314-54              | [71cf98e6e8](https://linux-hardware.org/?probe=71cf98e6e8) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| Dell          | Latitude E5500              | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| HP            | Compaq Presario CQ71        | [ea057ea9b9](https://linux-hardware.org/?probe=ea057ea9b9) | Oct 31, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [ce59648f62](https://linux-hardware.org/?probe=ce59648f62) | Oct 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e993af2670](https://linux-hardware.org/?probe=e993af2670) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Lenovo        | ThinkPad X270 20HN0014FR    | [d6fc7c48a1](https://linux-hardware.org/?probe=d6fc7c48a1) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| ASUSTek       | G74Sx                       | [c24c24ab27](https://linux-hardware.org/?probe=c24c24ab27) | Oct 30, 2022 |
| Dell          | XPS L322X                   | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d4552d84d5](https://linux-hardware.org/?probe=d4552d84d5) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | [6873e5b579](https://linux-hardware.org/?probe=6873e5b579) | Oct 30, 2022 |
| Valve         | Jupiter                     | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Acer          | Swift SF314-42              | [da1b668449](https://linux-hardware.org/?probe=da1b668449) | Oct 30, 2022 |
| ASUSTek       | E200HA                      | [18ca81370b](https://linux-hardware.org/?probe=18ca81370b) | Oct 29, 2022 |
| ASUSTek       | E200HA                      | [0a95698cb6](https://linux-hardware.org/?probe=0a95698cb6) | Oct 29, 2022 |
| HP            | Compaq 615                  | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| ASUSTek       | X751NV                      | [9ef2717db0](https://linux-hardware.org/?probe=9ef2717db0) | Oct 29, 2022 |
| IP3 Tech      | AP1                         | [0562a6a46d](https://linux-hardware.org/?probe=0562a6a46d) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| IP3 Tech      | AP1                         | [2a9c0ff1c5](https://linux-hardware.org/?probe=2a9c0ff1c5) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [05ff2d32fa](https://linux-hardware.org/?probe=05ff2d32fa) | Oct 28, 2022 |
| Lenovo        | ThinkPad T560 20FHCTO1WW    | [403a99d8b2](https://linux-hardware.org/?probe=403a99d8b2) | Oct 28, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [0c6a68368c](https://linux-hardware.org/?probe=0c6a68368c) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| Acer          | Extensa 2509                | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Alienware     | m17 R4                      | [14770101cf](https://linux-hardware.org/?probe=14770101cf) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | [8c9d6eb128](https://linux-hardware.org/?probe=8c9d6eb128) | Oct 27, 2022 |
| Dell          | Latitude 5310               | [10b8371dbd](https://linux-hardware.org/?probe=10b8371dbd) | Oct 27, 2022 |
| Acer          | Swift SF314-42              | [6aaeaf667c](https://linux-hardware.org/?probe=6aaeaf667c) | Oct 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [9564d50ef8](https://linux-hardware.org/?probe=9564d50ef8) | Oct 27, 2022 |
| Acer          | Swift SF314-512             | [951c734c1b](https://linux-hardware.org/?probe=951c734c1b) | Oct 27, 2022 |
| Valve         | Jupiter                     | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Dell          | Precision 7560              | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| Dell          | XPS 13 9305                 | [6062baa35c](https://linux-hardware.org/?probe=6062baa35c) | Oct 26, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [34be38a48b](https://linux-hardware.org/?probe=34be38a48b) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| ASUSTek       | GL753VD                     | [08b067d2cf](https://linux-hardware.org/?probe=08b067d2cf) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a128f79c0a](https://linux-hardware.org/?probe=a128f79c0a) | Oct 25, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [eadb224c05](https://linux-hardware.org/?probe=eadb224c05) | Oct 25, 2022 |
| Dell          | Inspiron 7737               | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [8f246bccb1](https://linux-hardware.org/?probe=8f246bccb1) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [bc5adf7f4b](https://linux-hardware.org/?probe=bc5adf7f4b) | Oct 25, 2022 |
| Valve         | Jupiter                     | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ec7f3834d1](https://linux-hardware.org/?probe=ec7f3834d1) | Oct 25, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [814da05eec](https://linux-hardware.org/?probe=814da05eec) | Oct 25, 2022 |
| Lenovo        | G50-45 80MQ                 | [1c6d041ce2](https://linux-hardware.org/?probe=1c6d041ce2) | Oct 25, 2022 |
| Valve         | Jupiter                     | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Dell          | Studio 1737                 | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Sony          | VGN-SZ3XP_C                 | [72f83141a0](https://linux-hardware.org/?probe=72f83141a0) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| Dell          | Latitude E6510              | [73cd1082f8](https://linux-hardware.org/?probe=73cd1082f8) | Oct 22, 2022 |
| Dell          | Latitude 5420               | [dd9b95a216](https://linux-hardware.org/?probe=dd9b95a216) | Oct 22, 2022 |
| Acer          | TravelMate P256-M           | [7ca952de68](https://linux-hardware.org/?probe=7ca952de68) | Oct 22, 2022 |
| ASUSTek       | ZenBook UX534FAC_UX534FA    | [928997f65c](https://linux-hardware.org/?probe=928997f65c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [57bfd1e0e9](https://linux-hardware.org/?probe=57bfd1e0e9) | Oct 22, 2022 |
| HP            | ProBook 6550b               | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [c7e03dae2f](https://linux-hardware.org/?probe=c7e03dae2f) | Oct 21, 2022 |
| Radxa         | ROCK Pi X v1.4              | [133d713246](https://linux-hardware.org/?probe=133d713246) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [47ca27793e](https://linux-hardware.org/?probe=47ca27793e) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| MAXDATA       | obook2-1                    | [0f73d884ff](https://linux-hardware.org/?probe=0f73d884ff) | Oct 21, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Valve         | Jupiter                     | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Gigabyte      | X7X7                        | [f2c35e3917](https://linux-hardware.org/?probe=f2c35e3917) | Oct 20, 2022 |
| HP            | ProBook 6550b               | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [ef1acaa7da](https://linux-hardware.org/?probe=ef1acaa7da) | Oct 20, 2022 |
| HP            | EliteBook 840 G5            | [3ec2887574](https://linux-hardware.org/?probe=3ec2887574) | Oct 20, 2022 |
| Dell          | Precision 5510              | [bb7788ce01](https://linux-hardware.org/?probe=bb7788ce01) | Oct 20, 2022 |
| Alienware     | x15 R2                      | [39d9f7988a](https://linux-hardware.org/?probe=39d9f7988a) | Oct 20, 2022 |
| Dell          | Latitude 5420               | [a6ef44d08a](https://linux-hardware.org/?probe=a6ef44d08a) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| Dell          | Latitude 7300               | [5674456b5d](https://linux-hardware.org/?probe=5674456b5d) | Oct 19, 2022 |
| HP            | 620                         | [263e2a0ba9](https://linux-hardware.org/?probe=263e2a0ba9) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | [2df95e6892](https://linux-hardware.org/?probe=2df95e6892) | Oct 19, 2022 |
| HP            | 620                         | [ad17206515](https://linux-hardware.org/?probe=ad17206515) | Oct 18, 2022 |
| Dell          | Precision 7750              | [93dcf0527b](https://linux-hardware.org/?probe=93dcf0527b) | Oct 18, 2022 |
| Dell          | Precision 7750              | [d32782f149](https://linux-hardware.org/?probe=d32782f149) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| Insyde        | WindTab89                   | [8eb81874bb](https://linux-hardware.org/?probe=8eb81874bb) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Dell          | Latitude 7300               | [c9bc03da26](https://linux-hardware.org/?probe=c9bc03da26) | Oct 18, 2022 |
| HP            | ZBook 14 G2                 | [fde830d956](https://linux-hardware.org/?probe=fde830d956) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| HP            | Pavilion dv7                | [bb650e8400](https://linux-hardware.org/?probe=bb650e8400) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| ASUSTek       | F9S                         | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bbff53957f](https://linux-hardware.org/?probe=bbff53957f) | Oct 17, 2022 |
| Dell          | G3 3500                     | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| UNOWHY        | Y13G010S4EI                 | [fca234fc49](https://linux-hardware.org/?probe=fca234fc49) | Oct 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a4ebad3748](https://linux-hardware.org/?probe=a4ebad3748) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| ASUSTek       | M70Vn                       | [e9301bdee2](https://linux-hardware.org/?probe=e9301bdee2) | Oct 16, 2022 |
| Dell          | Latitude 3500               | [d578b45420](https://linux-hardware.org/?probe=d578b45420) | Oct 16, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| UNOWHY        | Y13G011S4EI                 | [c210cda35b](https://linux-hardware.org/?probe=c210cda35b) | Oct 16, 2022 |
| Lenovo        | V145-15AST 81MT             | [d73a82b798](https://linux-hardware.org/?probe=d73a82b798) | Oct 15, 2022 |
| Valve         | Jupiter                     | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| ASUSTek       | X751NV                      | [174ee8f3e7](https://linux-hardware.org/?probe=174ee8f3e7) | Oct 15, 2022 |
| Dell          | Latitude 5400               | [645c7a01da](https://linux-hardware.org/?probe=645c7a01da) | Oct 15, 2022 |
| Acer          | AOD257                      | [41a717913c](https://linux-hardware.org/?probe=41a717913c) | Oct 15, 2022 |
| Acer          | Aspire 7730ZG               | [4796b36078](https://linux-hardware.org/?probe=4796b36078) | Oct 15, 2022 |
| Acer          | Aspire 7740                 | [a68780a6fd](https://linux-hardware.org/?probe=a68780a6fd) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | [fd260f87a9](https://linux-hardware.org/?probe=fd260f87a9) | Oct 14, 2022 |
| Dell          | G3 3500                     | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| HP            | EliteBook 840 G1            | [fe9dde997d](https://linux-hardware.org/?probe=fe9dde997d) | Oct 13, 2022 |
| MSI           | GE70 2QE                    | [2825343a52](https://linux-hardware.org/?probe=2825343a52) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [d1c1c4adea](https://linux-hardware.org/?probe=d1c1c4adea) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34481... | [adce18affa](https://linux-hardware.org/?probe=adce18affa) | Oct 13, 2022 |
| UNOWHY        | Y13G011S4EI                 | [2be4dc3fc2](https://linux-hardware.org/?probe=2be4dc3fc2) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Dell          | Latitude E5550              | [fc1fa79f81](https://linux-hardware.org/?probe=fc1fa79f81) | Oct 13, 2022 |
| Dell          | Inspiron 5759               | [2656af4553](https://linux-hardware.org/?probe=2656af4553) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| ASUSTek       | M70Vn                       | [62cb9744e6](https://linux-hardware.org/?probe=62cb9744e6) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | [e0c71d09bb](https://linux-hardware.org/?probe=e0c71d09bb) | Oct 11, 2022 |
| Acer          | Aspire 7750G                | [4eacf977db](https://linux-hardware.org/?probe=4eacf977db) | Oct 11, 2022 |
| Lenovo        | G50-30 80G0                 | [f96c4889db](https://linux-hardware.org/?probe=f96c4889db) | Oct 10, 2022 |
| Letni         | Z156                        | [994c588906](https://linux-hardware.org/?probe=994c588906) | Oct 10, 2022 |
| Dell          | Latitude 5400               | [ff8eb160c9](https://linux-hardware.org/?probe=ff8eb160c9) | Oct 10, 2022 |
| HP            | Notebook                    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Chuwi         | GemiBook Pro                | [02170aab85](https://linux-hardware.org/?probe=02170aab85) | Oct 09, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 947       | 19.43%  |
| Ubuntu 18.04       | 309       | 6.34%   |
| Ubuntu 22.04       | 266       | 5.46%   |
| Debian 11          | 175       | 3.59%   |
| OpenMandriva 4.2   | 171       | 3.51%   |
| OpenMandriva 4.3   | 139       | 2.85%   |
| Linux Mint 20.3    | 116       | 2.38%   |
| Xubuntu 20.04      | 108       | 2.22%   |
| Arch               | 80        | 1.64%   |
| Ubuntu 21.10       | 71        | 1.46%   |
| Debian 10          | 69        | 1.42%   |
| Arch Rolling       | 64        | 1.31%   |
| Linux Mint 20.2    | 63        | 1.29%   |
| Ubuntu 19.10       | 59        | 1.21%   |
| OpenMandriva 23.01 | 59        | 1.21%   |
| Ubuntu 21.04       | 57        | 1.17%   |
| Ubuntu 20.10       | 53        | 1.09%   |
| Manjaro            | 51        | 1.05%   |
| Zorin 16           | 50        | 1.03%   |
| Linux Mint 19.3    | 49        | 1.01%   |
| Xubuntu 18.04      | 48        | 0.98%   |
| Fedora 33          | 48        | 0.98%   |
| Fedora 34          | 44        | 0.9%    |
| Linux Mint 20.1    | 43        | 0.88%   |
| Kubuntu 20.04      | 41        | 0.84%   |
| Linux Mint 21      | 40        | 0.82%   |
| Fedora 32          | 40        | 0.82%   |
| Ubuntu 19.04       | 39        | 0.8%    |
| Fedora 36          | 38        | 0.78%   |
| Linux Mint 20      | 37        | 0.76%   |
| KDE neon 20.04     | 37        | 0.76%   |
| Pop!_OS 20.04      | 36        | 0.74%   |
| Pop!_OS 22.04      | 35        | 0.72%   |
| Fedora 37          | 35        | 0.72%   |
| Ubuntu MATE 20.04  | 34        | 0.7%    |
| Fedora 35          | 34        | 0.7%    |
| Lubuntu 20.04      | 32        | 0.66%   |
| Ubuntu 22.10       | 29        | 0.59%   |
| Pop!_OS 20.10      | 29        | 0.59%   |
| Pop!_OS 21.04      | 28        | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1772      | 38.3%   |
| OpenMandriva  | 402       | 8.69%   |
| Linux Mint    | 383       | 8.28%   |
| Debian        | 304       | 6.57%   |
| Fedora        | 238       | 5.14%   |
| Xubuntu       | 197       | 4.26%   |
| Arch          | 142       | 3.07%   |
| Pop!_OS       | 138       | 2.98%   |
| Manjaro       | 133       | 2.87%   |
| Kubuntu       | 110       | 2.38%   |
| Zorin         | 77        | 1.66%   |
| ROSA          | 73        | 1.58%   |
| Ubuntu MATE   | 64        | 1.38%   |
| Lubuntu       | 58        | 1.25%   |
| KDE neon      | 50        | 1.08%   |
| openSUSE      | 42        | 0.91%   |
| Endless       | 42        | 0.91%   |
| Kali          | 36        | 0.78%   |
| Gentoo        | 32        | 0.69%   |
| Elementary    | 29        | 0.63%   |
| ArcoLinux     | 27        | 0.58%   |
| Ubuntu Budgie | 25        | 0.54%   |
| Ubuntu Unity  | 22        | 0.48%   |
| BlackPanther  | 19        | 0.41%   |
| SteamOS       | 18        | 0.39%   |
| Parrot        | 18        | 0.39%   |
| EndeavourOS   | 18        | 0.39%   |
| LMDE          | 15        | 0.32%   |
| Ubuntu Studio | 11        | 0.24%   |
| CentOS        | 11        | 0.24%   |
| Kaisen        | 9         | 0.19%   |
| MX            | 8         | 0.17%   |
| NixOS         | 7         | 0.15%   |
| Clear Linux   | 7         | 0.15%   |
| Peppermint    | 6         | 0.13%   |
| RHEL          | 5         | 0.11%   |
| Mageia        | 5         | 0.11%   |
| Linux Lite    | 5         | 0.11%   |
| Xero          | 4         | 0.09%   |
| LinuxFX       | 4         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 161       | 3.03%   |
| 5.16.7-desktop-1omv4003  | 132       | 2.49%   |
| 5.15.0-56-generic        | 74        | 1.39%   |
| 5.4.0-42-generic         | 73        | 1.38%   |
| 5.15.0-58-generic        | 58        | 1.09%   |
| 5.15.0-52-generic        | 52        | 0.98%   |
| 6.1.1-desktop-1omv2290   | 51        | 0.96%   |
| 5.11.0-38-generic        | 50        | 0.94%   |
| 5.4.0-58-generic         | 44        | 0.83%   |
| 5.4.0-52-generic         | 44        | 0.83%   |
| 5.15.0-48-generic        | 44        | 0.83%   |
| 5.11.0-27-generic        | 42        | 0.79%   |
| 5.4.0-26-generic         | 39        | 0.74%   |
| 5.4.0-48-generic         | 36        | 0.68%   |
| 5.8.0-50-generic         | 35        | 0.66%   |
| 5.15.0-46-generic        | 35        | 0.66%   |
| 5.11.0-37-generic        | 35        | 0.66%   |
| 5.8.0-43-generic         | 33        | 0.62%   |
| 5.4.0-65-generic         | 33        | 0.62%   |
| 5.8.0-44-generic         | 32        | 0.6%    |
| 5.4.0-91-generic         | 32        | 0.6%    |
| 5.11.0-43-generic        | 32        | 0.6%    |
| 5.4.0-37-generic         | 31        | 0.58%   |
| 5.13.0-30-generic        | 31        | 0.58%   |
| 5.11.0-40-generic        | 31        | 0.58%   |
| 5.15.0-43-generic        | 30        | 0.57%   |
| 5.13.0-40-generic        | 30        | 0.57%   |
| 5.15.0-47-generic        | 29        | 0.55%   |
| 5.11.0-34-generic        | 29        | 0.55%   |
| 5.8.0-59-generic         | 28        | 0.53%   |
| 5.8.0-48-generic         | 28        | 0.53%   |
| 5.15.0-53-generic        | 28        | 0.53%   |
| 5.4.0-54-generic         | 27        | 0.51%   |
| 5.15.0-41-generic        | 27        | 0.51%   |
| 5.13.0-28-generic        | 27        | 0.51%   |
| 5.4.0-31-generic         | 26        | 0.49%   |
| 5.4.0-81-generic         | 25        | 0.47%   |
| 5.13.0-39-generic        | 25        | 0.47%   |
| 5.8.0-55-generic         | 24        | 0.45%   |
| 5.8.0-53-generic         | 24        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 942       | 18.85%  |
| 5.15.0  | 502       | 10.04%  |
| 5.11.0  | 355       | 7.1%    |
| 5.8.0   | 350       | 7%      |
| 5.13.0  | 306       | 6.12%   |
| 4.15.0  | 223       | 4.46%   |
| 5.10.0  | 208       | 4.16%   |
| 5.3.0   | 176       | 3.52%   |
| 5.10.14 | 162       | 3.24%   |
| 5.16.7  | 132       | 2.64%   |
| 5.0.0   | 99        | 1.98%   |
| 5.19.0  | 73        | 1.46%   |
| 4.18.0  | 66        | 1.32%   |
| 4.19.0  | 64        | 1.28%   |
| 6.1.1   | 61        | 1.22%   |
| 5.14.0  | 31        | 0.62%   |
| 6.0.0   | 24        | 0.48%   |
| 5.17.5  | 20        | 0.4%    |
| 5.16.0  | 19        | 0.38%   |
| 5.11.12 | 19        | 0.38%   |
| 4.18.16 | 18        | 0.36%   |
| 5.18.12 | 15        | 0.3%    |
| 4.9.20  | 15        | 0.3%    |
| 5.9.0   | 14        | 0.28%   |
| 5.6.0   | 14        | 0.28%   |
| 5.18.0  | 14        | 0.28%   |
| 5.9.11  | 13        | 0.26%   |
| 5.17.0  | 12        | 0.24%   |
| 4.4.0   | 12        | 0.24%   |
| 6.0.9   | 11        | 0.22%   |
| 5.19.12 | 11        | 0.22%   |
| 5.14.9  | 11        | 0.22%   |
| 4.9.0   | 11        | 0.22%   |
| 5.9.16  | 10        | 0.2%    |
| 5.7.0   | 10        | 0.2%    |
| 5.17.1  | 10        | 0.2%    |
| 5.12.4  | 10        | 0.2%    |
| 6.1.0   | 9         | 0.18%   |
| 6.0.12  | 9         | 0.18%   |
| 5.8.18  | 9         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 991       | 20.09%  |
| 5.15    | 608       | 12.32%  |
| 5.10    | 450       | 9.12%   |
| 5.11    | 406       | 8.23%   |
| 5.8     | 391       | 7.92%   |
| 5.13    | 343       | 6.95%   |
| 4.15    | 223       | 4.52%   |
| 5.3     | 201       | 4.07%   |
| 5.16    | 198       | 4.01%   |
| 5.19    | 124       | 2.51%   |
| 6.1     | 106       | 2.15%   |
| 5.0     | 103       | 2.09%   |
| 5.14    | 88        | 1.78%   |
| 6.0     | 86        | 1.74%   |
| 4.18    | 86        | 1.74%   |
| 5.9     | 71        | 1.44%   |
| 4.19    | 70        | 1.42%   |
| 5.18    | 63        | 1.28%   |
| 5.17    | 60        | 1.22%   |
| 5.6     | 50        | 1.01%   |
| 4.9     | 47        | 0.95%   |
| 5.7     | 42        | 0.85%   |
| 5.12    | 38        | 0.77%   |
| 5.5     | 23        | 0.47%   |
| 4.4     | 14        | 0.28%   |
| 4.1     | 11        | 0.22%   |
| 4.14    | 8         | 0.16%   |
| 5.2     | 7         | 0.14%   |
| 4.13    | 5         | 0.1%    |
| 4.12    | 5         | 0.1%    |
| 4.10    | 4         | 0.08%   |
| 3.10    | 3         | 0.06%   |
| 6.2     | 2         | 0.04%   |
| 5.1     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.8     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4397      | 97.39%  |
| i686    | 115       | 2.55%   |
| aarch64 | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2189      | 46.81%  |
| KDE5              | 759       | 16.23%  |
| XFCE              | 432       | 9.24%   |
| Unknown           | 412       | 8.81%   |
| X-Cinnamon        | 251       | 5.37%   |
| MATE              | 176       | 3.76%   |
| Cinnamon          | 78        | 1.67%   |
| LXQt              | 62        | 1.33%   |
| KDE               | 61        | 1.3%    |
| i3                | 52        | 1.11%   |
| KDE4              | 50        | 1.07%   |
| Budgie            | 30        | 0.64%   |
| Pantheon          | 29        | 0.62%   |
| Unity             | 23        | 0.49%   |
| LXDE              | 20        | 0.43%   |
| GNOME Flashback   | 15        | 0.32%   |
| Deepin            | 8         | 0.17%   |
| GNOME Classic     | 6         | 0.13%   |
| sway              | 3         | 0.06%   |
| i3-with-shmlog    | 3         | 0.06%   |
| Trinity           | 2         | 0.04%   |
| bspwm             | 2         | 0.04%   |
| awesome           | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| openbox           | 1         | 0.02%   |
| Lubuntu           | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| ICEWM             | 1         | 0.02%   |
| Hyprland          | 1         | 0.02%   |
| Enlightenment     | 1         | 0.02%   |
| dwm-sc            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3655      | 78.62%  |
| Wayland | 712       | 15.32%  |
| Unknown | 214       | 4.6%    |
| Tty     | 68        | 1.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1786      | 38.16%  |
| GDM     | 877       | 18.74%  |
| SDDM    | 753       | 16.09%  |
| LightDM | 525       | 11.22%  |
| GDM3    | 491       | 10.49%  |
| TDM     | 182       | 3.89%   |
| KDM     | 48        | 1.03%   |
| XDM     | 9         | 0.19%   |
| SLiM    | 3         | 0.06%   |
| NODM    | 2         | 0.04%   |
| Ly      | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| fr_FR      | 3122      | 67.99%  |
| en_US      | 839       | 18.27%  |
| Unknown    | 393       | 8.56%   |
| en_GB      | 76        | 1.66%   |
| C          | 41        | 0.89%   |
| ru_RU      | 13        | 0.28%   |
| de_DE      | 11        | 0.24%   |
| pl_PL      | 10        | 0.22%   |
| it_IT      | 10        | 0.22%   |
| es_ES      | 9         | 0.2%    |
| fr_CH      | 7         | 0.15%   |
| POSIX      | 5         | 0.11%   |
| nl_NL      | 5         | 0.11%   |
| fr_CA      | 5         | 0.11%   |
| fr_BE      | 4         | 0.09%   |
| ru_UA      | 3         | 0.07%   |
| pt_PT      | 3         | 0.07%   |
| pt_BR      | 3         | 0.07%   |
| en_IN      | 3         | 0.07%   |
| en_AU      | 3         | 0.07%   |
| hu_HU      | 2         | 0.04%   |
| en_IE      | 2         | 0.04%   |
| en_CA      | 2         | 0.04%   |
| cs_CZ      | 2         | 0.04%   |
| tr_TR      | 1         | 0.02%   |
| sv_SE      | 1         | 0.02%   |
| sk_SK      | 1         | 0.02%   |
| ro_RO      | 1         | 0.02%   |
| nb_NO      | 1         | 0.02%   |
| fr_LU      | 1         | 0.02%   |
| fr_FR.UTF8 | 1         | 0.02%   |
| es_VE      | 1         | 0.02%   |
| es_UY      | 1         | 0.02%   |
| es_AR      | 1         | 0.02%   |
| en_ZA      | 1         | 0.02%   |
| en_FR      | 1         | 0.02%   |
| en_AG      | 1         | 0.02%   |
| de_CH      | 1         | 0.02%   |
| de_BE      | 1         | 0.02%   |
| de_AT      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2615      | 56.86%  |
| BIOS | 1984      | 43.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3725      | 81.19%  |
| Overlay  | 381       | 8.3%    |
| Btrfs    | 290       | 6.32%   |
| Unknown  | 109       | 2.38%   |
| Xfs      | 34        | 0.74%   |
| Zfs      | 21        | 0.46%   |
| F2fs     | 9         | 0.2%    |
| Ext3     | 8         | 0.17%   |
| Ext2     | 8         | 0.17%   |
| Tmpfs    | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2049      | 44.42%  |
| Unknown | 1950      | 42.27%  |
| MBR     | 614       | 13.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3951      | 86.08%  |
| Yes       | 639       | 13.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3183      | 69.6%   |
| Yes       | 1390      | 30.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 809       | 17.92%  |
| Lenovo              | 753       | 16.68%  |
| Hewlett-Packard     | 753       | 16.68%  |
| ASUSTek Computer    | 738       | 16.35%  |
| Acer                | 333       | 7.38%   |
| MSI                 | 167       | 3.7%    |
| Toshiba             | 149       | 3.3%    |
| Apple               | 97        | 2.15%   |
| Notebook            | 83        | 1.84%   |
| HUAWEI              | 69        | 1.53%   |
| Samsung Electronics | 62        | 1.37%   |
| Sony                | 55        | 1.22%   |
| Packard Bell        | 55        | 1.22%   |
| TUXEDO              | 27        | 0.6%    |
| Timi                | 22        | 0.49%   |
| Clevo               | 20        | 0.44%   |
| Valve               | 19        | 0.42%   |
| Thomson             | 19        | 0.42%   |
| Unknown             | 19        | 0.42%   |
| UNOWHY              | 18        | 0.4%    |
| Gigabyte Technology | 18        | 0.4%    |
| eMachines           | 18        | 0.4%    |
| Fujitsu             | 16        | 0.35%   |
| Fujitsu Siemens     | 15        | 0.33%   |
| Alienware           | 15        | 0.33%   |
| PC Specialist       | 13        | 0.29%   |
| Razer               | 12        | 0.27%   |
| Google              | 12        | 0.27%   |
| Chuwi               | 11        | 0.24%   |
| Medion              | 10        | 0.22%   |
| Teclast             | 9         | 0.2%    |
| Intel               | 7         | 0.16%   |
| HONOR               | 5         | 0.11%   |
| BESSTAR Tech        | 5         | 0.11%   |
| Panasonic           | 4         | 0.09%   |
| AZW                 | 4         | 0.09%   |
| System76            | 3         | 0.07%   |
| SCHNEIDER           | 3         | 0.07%   |
| Schenker            | 3         | 0.07%   |
| NEC Computers       | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Notebook                     | 37        | 0.82%   |
| Unknown                         | 35        | 0.78%   |
| HP Pavilion dv6                 | 25        | 0.55%   |
| HP Pavilion 17                  | 23        | 0.51%   |
| HP Pavilion dv7                 | 22        | 0.49%   |
| Valve Jupiter                   | 19        | 0.42%   |
| HP Pavilion g7                  | 17        | 0.38%   |
| Dell XPS 13 9310                | 17        | 0.38%   |
| ASUS S551LN                     | 16        | 0.35%   |
| HP Pavilion Notebook            | 15        | 0.33%   |
| Dell XPS 13 9380                | 15        | 0.33%   |
| Dell XPS 13 7390                | 15        | 0.33%   |
| Dell Latitude E6420             | 14        | 0.31%   |
| HP EliteBook 840 G2             | 13        | 0.29%   |
| Dell XPS 15 7590                | 13        | 0.29%   |
| HP Pavilion 15                  | 12        | 0.27%   |
| HP EliteBook 840 G3             | 12        | 0.27%   |
| Dell XPS 15 9570                | 12        | 0.27%   |
| Dell Latitude 5420              | 12        | 0.27%   |
| HUAWEI NBLK-WAX9X               | 11        | 0.24%   |
| HUAWEI HVY-WXX9                 | 11        | 0.24%   |
| HP ProBook 650 G1               | 11        | 0.24%   |
| HP Pavilion g6                  | 11        | 0.24%   |
| Dell Latitude 5400              | 11        | 0.24%   |
| Lenovo G50-30 80G0              | 10        | 0.22%   |
| HP OMEN by Laptop               | 10        | 0.22%   |
| Dell XPS 15 9500                | 10        | 0.22%   |
| Dell Latitude E6400             | 10        | 0.22%   |
| Lenovo G50-45 80E3              | 9         | 0.2%    |
| Dell XPS 13 9370                | 9         | 0.2%    |
| Dell Latitude 7490              | 9         | 0.2%    |
| Acer Aspire ES1-523             | 9         | 0.2%    |
| UNOWHY Y13G010S4EI              | 8         | 0.18%   |
| Toshiba Satellite C660          | 8         | 0.18%   |
| HP ProBook 640 G1               | 8         | 0.18%   |
| HP Laptop 15-db0xxx             | 8         | 0.18%   |
| HP EliteBook 840 G8 Notebook PC | 8         | 0.18%   |
| HP EliteBook 840 G1             | 8         | 0.18%   |
| Dell Precision 5540             | 8         | 0.18%   |
| Dell Latitude E6520             | 8         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 440       | 9.75%   |
| Dell Latitude         | 326       | 7.22%   |
| Acer Aspire           | 226       | 5.01%   |
| HP Pavilion           | 203       | 4.5%    |
| HP EliteBook          | 145       | 3.21%   |
| Dell XPS              | 145       | 3.21%   |
| Lenovo IdeaPad        | 139       | 3.08%   |
| Toshiba Satellite     | 125       | 2.77%   |
| Dell Inspiron         | 121       | 2.68%   |
| HP ProBook            | 118       | 2.61%   |
| Dell Precision        | 117       | 2.59%   |
| ASUS VivoBook         | 105       | 2.33%   |
| HP Laptop             | 67        | 1.48%   |
| Packard Bell EasyNote | 48        | 1.06%   |
| ASUS ZenBook          | 45        | 1%      |
| Acer Swift            | 42        | 0.93%   |
| Dell Vostro           | 39        | 0.86%   |
| HP Notebook           | 37        | 0.82%   |
| ASUS ROG              | 37        | 0.82%   |
| Lenovo Legion         | 35        | 0.78%   |
| Unknown               | 35        | 0.78%   |
| HP Compaq             | 34        | 0.75%   |
| HP ZBook              | 31        | 0.69%   |
| ASUS ASUS             | 24        | 0.53%   |
| Acer Nitro            | 24        | 0.53%   |
| HP ENVY               | 21        | 0.47%   |
| HP OMEN               | 20        | 0.44%   |
| Valve Jupiter         | 19        | 0.42%   |
| ASUS TUF              | 18        | 0.4%    |
| Lenovo ThinkBook      | 17        | 0.38%   |
| Dell G5               | 17        | 0.38%   |
| MSI Modern            | 16        | 0.35%   |
| Lenovo Yoga           | 16        | 0.35%   |
| ASUS S551LN           | 16        | 0.35%   |
| Acer TravelMate       | 16        | 0.35%   |
| Dell G3               | 15        | 0.33%   |
| Fujitsu LIFEBOOK      | 14        | 0.31%   |
| Razer Blade           | 12        | 0.27%   |
| Apple MacBookPro5     | 12        | 0.27%   |
| Toshiba PORTEGE       | 11        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 480       | 10.63%  |
| 2019    | 464       | 10.28%  |
| 2018    | 398       | 8.82%   |
| 2012    | 336       | 7.44%   |
| 2021    | 331       | 7.33%   |
| 2013    | 312       | 6.91%   |
| 2015    | 302       | 6.69%   |
| 2011    | 294       | 6.51%   |
| 2017    | 260       | 5.76%   |
| 2016    | 242       | 5.36%   |
| 2014    | 235       | 5.21%   |
| 2010    | 227       | 5.03%   |
| 2008    | 204       | 4.52%   |
| 2009    | 163       | 3.61%   |
| 2022    | 117       | 2.59%   |
| 2007    | 93        | 2.06%   |
| 2006    | 31        | 0.69%   |
| 2005    | 15        | 0.33%   |
| Unknown | 4         | 0.09%   |
| 2004    | 3         | 0.07%   |
| 2023    | 1         | 0.02%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4514      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4017      | 88.27%  |
| Enabled  | 534       | 11.73%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4497      | 99.6%   |
| Yes  | 18        | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1246      | 27.35%  |
| 3.01-4.0    | 1126      | 24.72%  |
| 16.01-24.0  | 803       | 17.63%  |
| 8.01-16.0   | 689       | 15.13%  |
| 32.01-64.0  | 283       | 6.21%   |
| 1.01-2.0    | 194       | 4.26%   |
| 2.01-3.0    | 86        | 1.89%   |
| 64.01-256.0 | 47        | 1.03%   |
| 24.01-32.0  | 40        | 0.88%   |
| 0.51-1.0    | 33        | 0.72%   |
| 0.01-0.5    | 6         | 0.13%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1767      | 35.9%   |
| 2.01-3.0   | 1268      | 25.76%  |
| 4.01-8.0   | 678       | 13.77%  |
| 3.01-4.0   | 622       | 12.64%  |
| 0.51-1.0   | 315       | 6.4%    |
| 8.01-16.0  | 201       | 4.08%   |
| 0.01-0.5   | 47        | 0.95%   |
| 16.01-24.0 | 15        | 0.3%    |
| 24.01-32.0 | 6         | 0.12%   |
| Unknown    | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3364      | 73.45%  |
| 2      | 1049      | 22.9%   |
| 3      | 103       | 2.25%   |
| 0      | 42        | 0.92%   |
| 4      | 14        | 0.31%   |
| 5      | 5         | 0.11%   |
| 6      | 2         | 0.04%   |
| 7      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2753      | 60.69%  |
| Yes       | 1783      | 39.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3707      | 81.87%  |
| No        | 821       | 18.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4422      | 97.85%  |
| No        | 97        | 2.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3453      | 75.57%  |
| No        | 1116      | 24.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 4514      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 771       | 15.8%   |
| Lyon             | 104       | 2.13%   |
| Toulouse         | 85        | 1.74%   |
| Marseille        | 83        | 1.7%    |
| Nantes           | 60        | 1.23%   |
| Montpellier      | 53        | 1.09%   |
| Lille            | 46        | 0.94%   |
| Bordeaux         | 43        | 0.88%   |
| Strasbourg       | 40        | 0.82%   |
| Rennes           | 40        | 0.82%   |
| Grenoble         | 35        | 0.72%   |
| Clichy-sous-Bois | 28        | 0.57%   |
| Brest            | 28        | 0.57%   |
| Roubaix          | 27        | 0.55%   |
| Villeurbanne     | 26        | 0.53%   |
| Nice             | 25        | 0.51%   |
| Rouen            | 21        | 0.43%   |
| Caen             | 20        | 0.41%   |
| Cergy            | 19        | 0.39%   |
| Poitiers         | 17        | 0.35%   |
| Metz             | 17        | 0.35%   |
| Aix-en-Provence  | 17        | 0.35%   |
| Versailles       | 16        | 0.33%   |
| Tours            | 16        | 0.33%   |
| Toulon           | 16        | 0.33%   |
| Nancy            | 16        | 0.33%   |
| La Rochelle      | 16        | 0.33%   |
| Limoges          | 15        | 0.31%   |
| Clermont-Ferrand | 15        | 0.31%   |
| Besançon        | 15        | 0.31%   |
| Argenteuil       | 15        | 0.31%   |
| Saint-Denis      | 14        | 0.29%   |
| Palaiseau        | 14        | 0.29%   |
| Villejuif        | 13        | 0.27%   |
| Pau              | 13        | 0.27%   |
| Orléans         | 13        | 0.27%   |
| Le Mans          | 13        | 0.27%   |
| Colmar           | 13        | 0.27%   |
| Valenciennes     | 12        | 0.25%   |
| Perpignan        | 12        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 837       | 1126   | 15.12%  |
| WDC                         | 614       | 760    | 11.09%  |
| Seagate                     | 601       | 765    | 10.86%  |
| Toshiba                     | 473       | 592    | 8.54%   |
| SanDisk                     | 341       | 420    | 6.16%   |
| Crucial                     | 336       | 422    | 6.07%   |
| SK hynix                    | 279       | 336    | 5.04%   |
| Unknown                     | 270       | 355    | 4.88%   |
| Kingston                    | 260       | 304    | 4.7%    |
| HGST                        | 239       | 289    | 4.32%   |
| Hitachi                     | 174       | 196    | 3.14%   |
| Micron Technology           | 162       | 190    | 2.93%   |
| Intel                       | 158       | 190    | 2.85%   |
| KIOXIA                      | 76        | 85     | 1.37%   |
| PNY                         | 48        | 52     | 0.87%   |
| Apple                       | 44        | 58     | 0.79%   |
| LDLC                        | 43        | 59     | 0.78%   |
| Fujitsu                     | 38        | 46     | 0.69%   |
| LITEON                      | 36        | 41     | 0.65%   |
| Transcend                   | 33        | 37     | 0.6%    |
| China                       | 29        | 33     | 0.52%   |
| Phison                      | 26        | 28     | 0.47%   |
| JMicron Technology          | 25        | 28     | 0.45%   |
| LITEONIT                    | 22        | 24     | 0.4%    |
| SPCC                        | 21        | 24     | 0.38%   |
| Corsair                     | 17        | 21     | 0.31%   |
| Micron/Crucial Technology   | 16        | 17     | 0.29%   |
| A-DATA Technology           | 14        | 19     | 0.25%   |
| Unknown                     | 14        | 15     | 0.25%   |
| Kingston Technology Company | 13        | 14     | 0.23%   |
| SSSTC                       | 10        | 13     | 0.18%   |
| Silicon Motion              | 10        | 12     | 0.18%   |
| BHT                         | 10        | 13     | 0.18%   |
| Netac                       | 9         | 10     | 0.16%   |
| Lite-On                     | 9         | 13     | 0.16%   |
| KingSpec                    | 8         | 9      | 0.14%   |
| YMTC                        | 7         | 8      | 0.13%   |
| Phison Electronics          | 7         | 7      | 0.13%   |
| Patriot                     | 7         | 8      | 0.13%   |
| OCZ                         | 7         | 11     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 94        | 1.64%   |
| Seagate ST1000LM035-1RK172 1TB         | 92        | 1.61%   |
| Toshiba MQ01ABD100 1TB                 | 82        | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 79        | 1.38%   |
| Crucial CT240BX500SSD1 240GB           | 64        | 1.12%   |
| Crucial CT500MX500SSD1 500GB           | 62        | 1.08%   |
| Unknown MMC Card  32GB                 | 53        | 0.92%   |
| Toshiba MQ04ABF100 1TB                 | 53        | 0.92%   |
| Samsung SSD 860 EVO 500GB              | 51        | 0.89%   |
| HGST HTS541010A9E680 1TB               | 46        | 0.8%    |
| Kingston SA400S37240G 240GB SSD        | 40        | 0.7%    |
| Unknown MMC Card  64GB                 | 39        | 0.68%   |
| SanDisk NVMe SSD Drive 512GB           | 38        | 0.66%   |
| Samsung NVMe SSD Drive 512GB           | 37        | 0.65%   |
| Seagate ST500LT012-1DG142 500GB        | 36        | 0.63%   |
| Seagate ST9500325AS 500GB              | 33        | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB         | 30        | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB               | 27        | 0.47%   |
| Toshiba MQ01ABF050 500GB               | 27        | 0.47%   |
| KIOXIA KBG40ZNS512G NVMe 512GB         | 27        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB            | 27        | 0.47%   |
| HGST HTS725050A7E630 500GB             | 26        | 0.45%   |
| Toshiba NVMe SSD Drive 512GB           | 25        | 0.44%   |
| Samsung SSD 850 EVO 500GB              | 25        | 0.44%   |
| Crucial CT120BX500SSD1 120GB           | 25        | 0.44%   |
| Samsung SSD 870 QVO 1TB                | 24        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 24        | 0.42%   |
| Intel NVMe SSD Drive 512GB             | 23        | 0.4%    |
| SK hynix NVMe SSD Drive 512GB          | 22        | 0.38%   |
| Seagate ST1000LM049-2GH172 1TB         | 22        | 0.38%   |
| Samsung SSD 860 EVO 1TB                | 22        | 0.38%   |
| Samsung SSD 850 EVO 250GB              | 22        | 0.38%   |
| Crucial CT480BX500SSD1 480GB           | 22        | 0.38%   |
| Samsung NVMe SSD Drive 1TB             | 20        | 0.35%   |
| Kingston SA400S37480G 480GB SSD        | 20        | 0.35%   |
| Unknown MMC Card  128GB                | 19        | 0.33%   |
| Seagate ST500LM021-1KJ152 500GB        | 19        | 0.33%   |
| SanDisk NVMe SSD Drive 256GB           | 19        | 0.33%   |
| Seagate Expansion 1TB                  | 18        | 0.31%   |
| Kingston SA400S37120G 120GB SSD        | 18        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 593       | 751    | 31.66%  |
| WDC                 | 414       | 517    | 22.1%   |
| Toshiba             | 327       | 395    | 17.46%  |
| HGST                | 239       | 289    | 12.76%  |
| Hitachi             | 174       | 196    | 9.29%   |
| Samsung Electronics | 37        | 56     | 1.98%   |
| Fujitsu             | 37        | 45     | 1.98%   |
| Unknown             | 12        | 13     | 0.64%   |
| JMicron Technology  | 8         | 9      | 0.43%   |
| Apple               | 7         | 7      | 0.37%   |
| SABRENT             | 5         | 5      | 0.27%   |
| IBM/Hitachi         | 5         | 6      | 0.27%   |
| HGST HTS            | 3         | 4      | 0.16%   |
| ASMT                | 3         | 4      | 0.16%   |
| ASMedia             | 2         | 2      | 0.11%   |
| SILICONMOTION       | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| Generic-            | 1         | 1      | 0.05%   |
| APPLE HD            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 405       | 529    | 22.64%  |
| Crucial             | 312       | 395    | 17.44%  |
| SanDisk             | 216       | 266    | 12.07%  |
| Kingston            | 195       | 230    | 10.9%   |
| Micron Technology   | 65        | 85     | 3.63%   |
| SK hynix            | 62        | 76     | 3.47%   |
| WDC                 | 47        | 53     | 2.63%   |
| Intel               | 43        | 44     | 2.4%    |
| PNY                 | 42        | 46     | 2.35%   |
| LDLC                | 36        | 50     | 2.01%   |
| Apple               | 33        | 45     | 1.84%   |
| Transcend           | 31        | 35     | 1.73%   |
| LITEON              | 31        | 34     | 1.73%   |
| Toshiba             | 30        | 37     | 1.68%   |
| China               | 28        | 32     | 1.57%   |
| LITEONIT            | 22        | 24     | 1.23%   |
| SPCC                | 18        | 21     | 1.01%   |
| A-DATA Technology   | 11        | 16     | 0.61%   |
| BHT                 | 10        | 13     | 0.56%   |
| KingSpec            | 8         | 9      | 0.45%   |
| Corsair             | 8         | 11     | 0.45%   |
| OCZ                 | 7         | 11     | 0.39%   |
| Netac               | 7         | 8      | 0.39%   |
| Emtec               | 7         | 7      | 0.39%   |
| Dogfish             | 7         | 10     | 0.39%   |
| Patriot             | 6         | 6      | 0.34%   |
| JMicron Technology  | 6         | 7      | 0.34%   |
| Plextor             | 5         | 7      | 0.28%   |
| Teclast             | 4         | 6      | 0.22%   |
| KingDian            | 4         | 5      | 0.22%   |
| ASMT                | 4         | 4      | 0.22%   |
| Unknown             | 4         | 4      | 0.22%   |
| Unknown             | 3         | 4      | 0.17%   |
| TCSUNBOW            | 3         | 4      | 0.17%   |
| Intenso             | 3         | 3      | 0.17%   |
| BAITITON            | 3         | 3      | 0.17%   |
| Verbatim            | 2         | 2      | 0.11%   |
| Union Memory        | 2         | 2      | 0.11%   |
| Seagate             | 2         | 2      | 0.11%   |
| ORICO               | 2         | 2      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1815      | 2306   | 34.19%  |
| SSD     | 1655      | 2211   | 31.18%  |
| NVMe    | 1501      | 1914   | 28.28%  |
| MMC     | 270       | 365    | 5.09%   |
| Unknown | 67        | 74     | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3089      | 4380   | 61.41%  |
| NVMe | 1500      | 1912   | 29.82%  |
| MMC  | 270       | 365    | 5.37%   |
| SAS  | 171       | 213    | 3.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2216      | 2937   | 64.06%  |
| 0.51-1.0   | 1142      | 1443   | 33.02%  |
| 1.01-2.0   | 85        | 115    | 2.46%   |
| 4.01-10.0  | 8         | 10     | 0.23%   |
| 3.01-4.0   | 4         | 6      | 0.12%   |
| 2.01-3.0   | 2         | 3      | 0.06%   |
| 10.01-20.0 | 2         | 3      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1322      | 28.04%  |
| 251-500        | 1243      | 26.36%  |
| 501-1000       | 794       | 16.84%  |
| 1-20           | 371       | 7.87%   |
| 51-100         | 292       | 6.19%   |
| 1001-2000      | 242       | 5.13%   |
| 21-50          | 203       | 4.31%   |
| Unknown        | 120       | 2.55%   |
| More than 3000 | 66        | 1.4%    |
| 2001-3000      | 62        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1922      | 39.25%  |
| 21-50          | 865       | 17.66%  |
| 101-250        | 693       | 14.15%  |
| 51-100         | 624       | 12.74%  |
| 251-500        | 368       | 7.51%   |
| 501-1000       | 202       | 4.12%   |
| Unknown        | 120       | 2.45%   |
| 1001-2000      | 58        | 1.18%   |
| 2001-3000      | 30        | 0.61%   |
| More than 3000 | 13        | 0.27%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 18        | 21     | 4.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 12        | 12     | 2.88%   |
| HGST HTS541010A9E680 1TB                         | 11        | 12     | 2.64%   |
| Seagate ST9500325AS 500GB                        | 10        | 11     | 2.4%    |
| Toshiba MQ01ABD100 1TB                           | 9         | 11     | 2.16%   |
| Seagate ST500LM021-1KJ152 500GB                  | 8         | 10     | 1.92%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 7         | 7      | 1.68%   |
| Seagate ST500LT012-1DG142 500GB                  | 7         | 7      | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB                   | 7         | 7      | 1.68%   |
| Toshiba MQ01ABD050 500GB                         | 5         | 5      | 1.2%    |
| Seagate ST320LT007-9ZV142 320GB                  | 5         | 6      | 1.2%    |
| Hitachi HTS547575A9E384 752GB                    | 5         | 5      | 1.2%    |
| Toshiba MQ01ABF050 500GB                         | 4         | 4      | 0.96%   |
| Toshiba MK3265GSX 320GB                          | 4         | 5      | 0.96%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 4         | 4      | 0.96%   |
| Hitachi HTS727575A9E364 752GB                    | 4         | 4      | 0.96%   |
| Hitachi HTS545050B9A300 500GB                    | 4         | 4      | 0.96%   |
| Hitachi HTS545050A7E380 500GB                    | 4         | 4      | 0.96%   |
| Hitachi HTS543232A7A384 320GB                    | 4         | 6      | 0.96%   |
| HGST HTS725050A7E630 500GB                       | 4         | 4      | 0.96%   |
| HGST HTS545050A7E680 500GB                       | 4         | 4      | 0.96%   |
| Crucial CT525MX300SSD1 528GB                     | 4         | 4      | 0.96%   |
| Toshiba MK7575GSX 752GB                          | 3         | 3      | 0.72%   |
| Toshiba MK5055GSX 500GB                          | 3         | 3      | 0.72%   |
| Toshiba MK3261GSYN 320GB                         | 3         | 3      | 0.72%   |
| SK hynix PC711 HFS512GDE9X073N 512GB             | 3         | 3      | 0.72%   |
| Seagate ST9250827AS 250GB                        | 3         | 3      | 0.72%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 3      | 0.72%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 3         | 3      | 0.72%   |
| Hitachi HTS547550A9E384 500GB                    | 3         | 3      | 0.72%   |
| HGST HTS545050A7E380 500GB                       | 3         | 3      | 0.72%   |
| HGST HTS541075A9E680 752GB                       | 3         | 3      | 0.72%   |
| WDC WD5000BEKT-75KA9T0 500GB                     | 2         | 2      | 0.48%   |
| WDC WD3200BPVT-80ZEST0 320GB                     | 2         | 2      | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 2         | 2      | 0.48%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 2         | 2      | 0.48%   |
| Toshiba MQ04ABF100 1TB                           | 2         | 2      | 0.48%   |
| Toshiba MQ01ACF050 500GB                         | 2         | 2      | 0.48%   |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 0.48%   |
| Toshiba MK8052GSX 80GB                           | 2         | 2      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 100    | 21.63%  |
| Toshiba             | 56        | 60     | 13.46%  |
| WDC                 | 49        | 52     | 11.78%  |
| Hitachi             | 49        | 51     | 11.78%  |
| HGST                | 46        | 50     | 11.06%  |
| Samsung Electronics | 22        | 25     | 5.29%   |
| SK hynix            | 17        | 19     | 4.09%   |
| Crucial             | 16        | 16     | 3.85%   |
| SanDisk             | 15        | 16     | 3.61%   |
| Intel               | 13        | 13     | 3.13%   |
| Kingston            | 9         | 9      | 2.16%   |
| Fujitsu             | 6         | 6      | 1.44%   |
| Micron Technology   | 3         | 3      | 0.72%   |
| LITEONIT            | 2         | 2      | 0.48%   |
| LITEON              | 2         | 2      | 0.48%   |
| LDLC                | 2         | 4      | 0.48%   |
| Dogfish             | 2         | 2      | 0.48%   |
| Corsair             | 2         | 3      | 0.48%   |
| Unknown             | 1         | 1      | 0.24%   |
| TakeMS              | 1         | 1      | 0.24%   |
| Phison              | 1         | 1      | 0.24%   |
| OCZ                 | 1         | 1      | 0.24%   |
| Netac               | 1         | 1      | 0.24%   |
| Magnetic Data       | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |
| JMicron Technology  | 1         | 1      | 0.24%   |
| Intenso             | 1         | 1      | 0.24%   |
| IBM/Hitachi         | 1         | 1      | 0.24%   |
| China               | 1         | 1      | 0.24%   |
| ASENNO              | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |
| Apacer              | 1         | 1      | 0.24%   |
| A-DATA Technology   | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 100    | 29.9%   |
| Toshiba             | 52        | 56     | 17.28%  |
| Hitachi             | 49        | 51     | 16.28%  |
| WDC                 | 47        | 50     | 15.61%  |
| HGST                | 46        | 50     | 15.28%  |
| Samsung Electronics | 8         | 8      | 2.66%   |
| Fujitsu             | 6         | 6      | 1.99%   |
| Unknown             | 1         | 1      | 0.33%   |
| Magnetic Data       | 1         | 1      | 0.33%   |
| IBM/Hitachi         | 1         | 1      | 0.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 298       | 324    | 72.33%  |
| SSD     | 100       | 107    | 24.27%  |
| NVMe    | 13        | 16     | 3.16%   |
| Unknown | 1         | 1      | 0.24%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 3      | 12.5%   |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 12.5%   |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 6.25%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 6.25%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 6.25%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 6.25%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 6.25%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 6.25%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 6.25%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 37.5%   |
| Toshiba             | 5         | 6      | 31.25%  |
| HGST                | 2         | 2      | 12.5%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2236      | 3527   | 46.25%  |
| Works    | 2178      | 2876   | 45.05%  |
| Malfunc  | 404       | 448    | 8.36%   |
| Failed   | 16        | 18     | 0.33%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3215      | 60.9%   |
| AMD                                     | 507       | 9.6%    |
| Samsung Electronics                     | 436       | 8.26%   |
| SanDisk                                 | 264       | 5%      |
| SK hynix                                | 211       | 4%      |
| Toshiba America Info Systems            | 133       | 2.52%   |
| Micron Technology                       | 98        | 1.86%   |
| Kingston Technology Company             | 78        | 1.48%   |
| KIOXIA                                  | 71        | 1.34%   |
| Nvidia                                  | 50        | 0.95%   |
| Phison Electronics                      | 48        | 0.91%   |
| Micron/Crucial Technology               | 40        | 0.76%   |
| Lite-On Technology                      | 15        | 0.28%   |
| Silicon Motion                          | 14        | 0.27%   |
| Union Memory (Shenzhen)                 | 13        | 0.25%   |
| Silicon Integrated Systems [SiS]        | 13        | 0.25%   |
| Solid State Storage Technology          | 11        | 0.21%   |
| Marvell Technology Group                | 11        | 0.21%   |
| JMicron Technology                      | 10        | 0.19%   |
| Yangtze Memory Technologies             | 8         | 0.15%   |
| Lenovo                                  | 6         | 0.11%   |
| Apple                                   | 4         | 0.08%   |
| ADATA Technology                        | 4         | 0.08%   |
| VIA Technologies                        | 3         | 0.06%   |
| Silicon Image                           | 3         | 0.06%   |
| Seagate Technology                      | 3         | 0.06%   |
| O2 Micro                                | 3         | 0.06%   |
| ASMedia Technology                      | 3         | 0.06%   |
| Realtek Semiconductor                   | 2         | 0.04%   |
| ULi Electronics                         | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 414       | 7.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 328       | 5.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 320       | 5.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 269       | 4.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 204       | 3.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 190       | 3.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 185       | 3.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 184       | 3.26%   |
| Intel Volume Management Device NVMe RAID Controller                              | 165       | 2.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 162       | 2.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 152       | 2.7%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 146       | 2.59%   |
| Samsung NVMe SSD Controller 980                                                  | 132       | 2.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 119       | 2.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 113       | 2%      |
| Micron Non-Volatile memory controller                                            | 98        | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 95        | 1.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 84        | 1.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 78        | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 73        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 70        | 1.24%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 66        | 1.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 64        | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 63        | 1.12%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 60        | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 55        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                            | 55        | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 55        | 0.98%   |
| SK hynix Non-Volatile memory controller                                          | 54        | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 51        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 49        | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                              | 49        | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 47        | 0.83%   |
| SanDisk Non-Volatile memory controller                                           | 44        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 43        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 43        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 43        | 0.76%   |
| Intel SSD 660P Series                                                            | 42        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 42        | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 39        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3181      | 58.23%  |
| NVMe | 1517      | 27.77%  |
| RAID | 451       | 8.26%   |
| IDE  | 314       | 5.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3786      | 83.87%  |
| AMD    | 726       | 16.08%  |
| ARM    | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 94        | 2.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 66        | 1.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 66        | 1.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 65        | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 64        | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 57        | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 56        | 1.24%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 53        | 1.17%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 52        | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 1.06%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 47        | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 47        | 1.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 47        | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 44        | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 42        | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 42        | 0.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 40        | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 40        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.8%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 36        | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 36        | 0.8%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 32        | 0.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 31        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 30        | 0.66%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 0.66%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 29        | 0.64%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 29        | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 28        | 0.62%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 28        | 0.62%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 28        | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 27        | 0.6%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 26        | 0.58%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.58%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 25        | 0.55%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 25        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.53%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.51%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 22        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1108      | 24.53%  |
| Intel Core i7           | 985       | 21.81%  |
| Other                   | 387       | 8.57%   |
| Intel Core i3           | 386       | 8.55%   |
| Intel Celeron           | 256       | 5.67%   |
| Intel Core 2 Duo        | 247       | 5.47%   |
| AMD Ryzen 5             | 160       | 3.54%   |
| Intel Pentium           | 132       | 2.92%   |
| AMD Ryzen 7             | 128       | 2.83%   |
| Intel Atom              | 95        | 2.1%    |
| Intel Pentium Dual-Core | 52        | 1.15%   |
| AMD E1                  | 52        | 1.15%   |
| AMD A4                  | 37        | 0.82%   |
| AMD E2                  | 35        | 0.77%   |
| AMD Ryzen 7 PRO         | 34        | 0.75%   |
| AMD A6                  | 32        | 0.71%   |
| Intel Pentium Dual      | 31        | 0.69%   |
| Intel Core 2            | 26        | 0.58%   |
| AMD Ryzen 9             | 26        | 0.58%   |
| Intel Core i9           | 25        | 0.55%   |
| AMD E                   | 25        | 0.55%   |
| Intel Genuine           | 21        | 0.46%   |
| AMD A8                  | 19        | 0.42%   |
| AMD Ryzen 3             | 16        | 0.35%   |
| AMD Ryzen 5 PRO         | 15        | 0.33%   |
| AMD Athlon              | 15        | 0.33%   |
| Intel Xeon              | 13        | 0.29%   |
| Intel Pentium Silver    | 13        | 0.29%   |
| Intel Celeron Dual-Core | 11        | 0.24%   |
| AMD Athlon II           | 11        | 0.24%   |
| Intel Pentium M         | 10        | 0.22%   |
| Intel Core m3           | 9         | 0.2%    |
| AMD Turion 64 X2 Mobile | 9         | 0.2%    |
| AMD Athlon X2           | 9         | 0.2%    |
| Intel Celeron M         | 8         | 0.18%   |
| AMD Athlon II Dual-Core | 8         | 0.18%   |
| AMD Athlon 64 X2        | 7         | 0.15%   |
| AMD A12                 | 7         | 0.15%   |
| AMD C-60                | 6         | 0.13%   |
| AMD A10                 | 6         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2241      | 49.62%  |
| 4       | 1538      | 34.06%  |
| 6       | 318       | 7.04%   |
| 8       | 237       | 5.25%   |
| 1       | 110       | 2.44%   |
| 12      | 24        | 0.53%   |
| 14      | 23        | 0.51%   |
| 10      | 15        | 0.33%   |
| Unknown | 9         | 0.2%    |
| 3       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4512      | 99.93%  |
| 2      | 3         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3234      | 71.52%  |
| 1       | 1278      | 28.26%  |
| Unknown | 9         | 0.2%    |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4431      | 97.99%  |
| Unknown        | 48        | 1.06%   |
| 32-bit         | 41        | 0.91%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 832       | 17.9%   |
| 0x306a9    | 279       | 6%      |
| 0x206a7    | 270       | 5.81%   |
| 0x806c1    | 188       | 4.04%   |
| 0x806ec    | 181       | 3.89%   |
| 0x1067a    | 169       | 3.64%   |
| 0x906ea    | 167       | 3.59%   |
| 0x40651    | 145       | 3.12%   |
| 0x306d4    | 142       | 3.06%   |
| 0x806ea    | 140       | 3.01%   |
| 0x406e3    | 140       | 3.01%   |
| 0x306c3    | 138       | 2.97%   |
| 0x806e9    | 118       | 2.54%   |
| 0x20655    | 115       | 2.47%   |
| 0x6fd      | 83        | 1.79%   |
| 0x506e3    | 77        | 1.66%   |
| 0xa0652    | 76        | 1.64%   |
| 0x906e9    | 67        | 1.44%   |
| 0x08600106 | 64        | 1.38%   |
| 0x08108109 | 61        | 1.31%   |
| 0x30678    | 54        | 1.16%   |
| 0x10676    | 53        | 1.14%   |
| 0x806d1    | 48        | 1.03%   |
| 0x706e5    | 48        | 1.03%   |
| 0x406c4    | 47        | 1.01%   |
| 0x07030105 | 41        | 0.88%   |
| 0x406c3    | 40        | 0.86%   |
| 0x0a50000c | 40        | 0.86%   |
| 0x906a3    | 39        | 0.84%   |
| 0x806eb    | 39        | 0.84%   |
| 0x706a1    | 39        | 0.84%   |
| 0x08108102 | 39        | 0.84%   |
| 0x506c9    | 37        | 0.8%    |
| 0x20652    | 34        | 0.73%   |
| 0x906ed    | 32        | 0.69%   |
| 0x06006705 | 32        | 0.69%   |
| 0x05000119 | 32        | 0.69%   |
| 0x0700010f | 26        | 0.56%   |
| 0x706a8    | 24        | 0.52%   |
| 0x08608103 | 24        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 907       | 20.08%  |
| Haswell          | 351       | 7.77%   |
| IvyBridge        | 326       | 7.22%   |
| SandyBridge      | 302       | 6.69%   |
| Skylake          | 265       | 5.87%   |
| Penryn           | 252       | 5.58%   |
| TigerLake        | 225       | 4.98%   |
| Silvermont       | 176       | 3.9%    |
| Westmere         | 173       | 3.83%   |
| Broadwell        | 166       | 3.68%   |
| Core             | 157       | 3.48%   |
| Zen 2            | 130       | 2.88%   |
| Zen+             | 112       | 2.48%   |
| IceLake          | 105       | 2.32%   |
| Unknown          | 101       | 2.24%   |
| CometLake        | 99        | 2.19%   |
| Goldmont plus    | 73        | 1.62%   |
| Zen 3            | 69        | 1.53%   |
| Puma             | 64        | 1.42%   |
| Bobcat           | 60        | 1.33%   |
| Excavator        | 54        | 1.2%    |
| Alderlake Hybrid | 47        | 1.04%   |
| Goldmont         | 46        | 1.02%   |
| Bonnell          | 40        | 0.89%   |
| Jaguar           | 39        | 0.86%   |
| Zen              | 33        | 0.73%   |
| K10              | 28        | 0.62%   |
| K8 Hammer        | 26        | 0.58%   |
| P6               | 22        | 0.49%   |
| Nehalem          | 19        | 0.42%   |
| Piledriver       | 15        | 0.33%   |
| K8 & K10 hybrid  | 12        | 0.27%   |
| K10 Llano        | 12        | 0.27%   |
| Tremont          | 5         | 0.11%   |
| NetBurst         | 3         | 0.07%   |
| Steamroller      | 2         | 0.04%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3397      | 58.23%  |
| Nvidia                           | 1417      | 24.29%  |
| AMD                              | 1010      | 17.31%  |
| Silicon Integrated Systems [SiS] | 8         | 0.14%   |
| VIA Technologies                 | 2         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 301       | 5.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 269       | 4.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 214       | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 213       | 3.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 170       | 2.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 155       | 2.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 153       | 2.55%   |
| Intel UHD Graphics 620                                                                   | 152       | 2.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 151       | 2.52%   |
| Intel HD Graphics 5500                                                                   | 147       | 2.45%   |
| Intel HD Graphics 620                                                                    | 142       | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 138       | 2.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 129       | 2.15%   |
| AMD Renoir                                                                               | 126       | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 113       | 1.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 1.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 91        | 1.52%   |
| Intel HD Graphics 530                                                                    | 83        | 1.38%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 82        | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 81        | 1.35%   |
| Intel HD Graphics 630                                                                    | 73        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 64        | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 64        | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 61        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 59        | 0.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 57        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 50        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 0.83%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 47        | 0.78%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 44        | 0.73%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 44        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 43        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 43        | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 41        | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 38        | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 38        | 0.63%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 36        | 0.6%    |
| Intel HD Graphics 500                                                                    | 35        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2157      | 47.65%  |
| Intel + Nvidia     | 1062      | 23.46%  |
| 1 x AMD            | 684       | 15.11%  |
| 1 x Nvidia         | 266       | 5.88%   |
| Intel + AMD        | 169       | 3.73%   |
| AMD + Nvidia       | 84        | 1.86%   |
| 2 x AMD            | 74        | 1.63%   |
| 2 x Intel          | 9         | 0.2%    |
| 1 x SiS            | 8         | 0.18%   |
| 2 x Nvidia         | 6         | 0.13%   |
| Other              | 5         | 0.11%   |
| 1 x VIA            | 2         | 0.04%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3850      | 84.49%  |
| Proprietary | 593       | 13.01%  |
| Unknown     | 114       | 2.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2806      | 60.92%  |
| 0.01-0.5   | 613       | 13.31%  |
| 1.01-2.0   | 522       | 11.33%  |
| 0.51-1.0   | 273       | 5.93%   |
| 3.01-4.0   | 258       | 5.6%    |
| 5.01-6.0   | 72        | 1.56%   |
| 7.01-8.0   | 38        | 0.83%   |
| 2.01-3.0   | 22        | 0.48%   |
| 8.01-16.0  | 2         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1061      | 20.66%  |
| Chimei Innolux          | 678       | 13.2%   |
| LG Display              | 675       | 13.15%  |
| BOE                     | 612       | 11.92%  |
| Samsung Electronics     | 539       | 10.5%   |
| Sharp                   | 169       | 3.29%   |
| Chi Mei Optoelectronics | 138       | 2.69%   |
| Dell                    | 136       | 2.65%   |
| Iiyama                  | 101       | 1.97%   |
| Apple                   | 96        | 1.87%   |
| Lenovo                  | 91        | 1.77%   |
| PANDA                   | 70        | 1.36%   |
| Acer                    | 66        | 1.29%   |
| Hewlett-Packard         | 65        | 1.27%   |
| LG Philips              | 63        | 1.23%   |
| InfoVision              | 56        | 1.09%   |
| Goldstar                | 53        | 1.03%   |
| BenQ                    | 42        | 0.82%   |
| Ancor Communications    | 42        | 0.82%   |
| AOC                     | 38        | 0.74%   |
| Philips                 | 36        | 0.7%    |
| ViewSonic               | 28        | 0.55%   |
| CSO                     | 20        | 0.39%   |
| CPT                     | 18        | 0.35%   |
| ASUSTek Computer        | 17        | 0.33%   |
| HannStar                | 14        | 0.27%   |
| Sony                    | 13        | 0.25%   |
| Fujitsu Siemens         | 13        | 0.25%   |
| Vestel Elektronik       | 10        | 0.19%   |
| Toshiba                 | 9         | 0.18%   |
| Seiko/Epson             | 9         | 0.18%   |
| Analogix                | 9         | 0.18%   |
| LGD                     | 8         | 0.16%   |
| ANX                     | 7         | 0.14%   |
| Unknown                 | 6         | 0.12%   |
| TMX                     | 5         | 0.1%    |
| Quanta Display          | 5         | 0.1%    |
| Panasonic               | 5         | 0.1%    |
| LPL                     | 5         | 0.1%    |
| Packard Bell            | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 45        | 0.87%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 34        | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 33        | 0.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 29        | 0.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 26        | 0.5%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.5%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 25        | 0.48%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 24        | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 24        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 23        | 0.44%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 23        | 0.44%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 22        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 21        | 0.4%    |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 20        | 0.39%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 20        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 19        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 19        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 18        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 17        | 0.33%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 16        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 15        | 0.29%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 15        | 0.29%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 14        | 0.27%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 14        | 0.27%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 14        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 14        | 0.27%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 13        | 0.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 13        | 0.25%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 13        | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 13        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2077      | 43.57%  |
| 1366x768 (WXGA)    | 1179      | 24.73%  |
| 1600x900 (HD+)     | 460       | 9.65%   |
| 1280x800 (WXGA)    | 183       | 3.84%   |
| 3840x2160 (4K)     | 150       | 3.15%   |
| 1920x1200 (WUXGA)  | 118       | 2.48%   |
| 1440x900 (WXGA+)   | 118       | 2.48%   |
| 2560x1440 (QHD)    | 104       | 2.18%   |
| 1680x1050 (WSXGA+) | 55        | 1.15%   |
| 1024x600           | 32        | 0.67%   |
| 1280x1024 (SXGA)   | 30        | 0.63%   |
| 2560x1600          | 26        | 0.55%   |
| 3440x1440          | 24        | 0.5%    |
| 2880x1800          | 23        | 0.48%   |
| 3840x2400          | 20        | 0.42%   |
| 800x1280           | 19        | 0.4%    |
| 2160x1440          | 19        | 0.4%    |
| 2560x1080          | 14        | 0.29%   |
| 3200x1800 (QHD+)   | 11        | 0.23%   |
| Unknown            | 11        | 0.23%   |
| 1360x768           | 10        | 0.21%   |
| 3840x1080          | 7         | 0.15%   |
| 3000x2000          | 7         | 0.15%   |
| 1920x540           | 7         | 0.15%   |
| 1600x1200          | 7         | 0.15%   |
| 1680x945           | 6         | 0.13%   |
| 1024x768 (XGA)     | 6         | 0.13%   |
| 3840x1200          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 1920x515           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 3072x1920          | 3         | 0.06%   |
| 2256x1504          | 3         | 0.06%   |
| 5760x2160          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3286x1080          | 2         | 0.04%   |
| 2520x1680          | 2         | 0.04%   |
| 2048x1152          | 2         | 0.04%   |
| 720x1280           | 1         | 0.02%   |
| 4480x1600          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1913      | 37.3%   |
| 13      | 718       | 14%     |
| 17      | 711       | 13.86%  |
| 14      | 504       | 9.83%   |
| 24      | 216       | 4.21%   |
| 23      | 158       | 3.08%   |
| 12      | 144       | 2.81%   |
| 27      | 141       | 2.75%   |
| 21      | 101       | 1.97%   |
| Unknown | 85        | 1.66%   |
| 11      | 64        | 1.25%   |
| 16      | 52        | 1.01%   |
| 18      | 43        | 0.84%   |
| 10      | 43        | 0.84%   |
| 34      | 35        | 0.68%   |
| 19      | 35        | 0.68%   |
| 22      | 34        | 0.66%   |
| 20      | 19        | 0.37%   |
| 31      | 17        | 0.33%   |
| 84      | 15        | 0.29%   |
| 72      | 13        | 0.25%   |
| 25      | 9         | 0.18%   |
| 40      | 7         | 0.14%   |
| 54      | 6         | 0.12%   |
| 32      | 6         | 0.12%   |
| 52      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 26      | 4         | 0.08%   |
| 49      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 7       | 3         | 0.06%   |
| 142     | 2         | 0.04%   |
| 48      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |
| 74      | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 50      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2716      | 53.48%  |
| 351-400        | 803       | 15.81%  |
| 201-300        | 640       | 12.6%   |
| 501-600        | 474       | 9.33%   |
| 401-500        | 213       | 4.19%   |
| Unknown        | 85        | 1.67%   |
| 701-800        | 44        | 0.87%   |
| 601-700        | 33        | 0.65%   |
| 1501-2000      | 29        | 0.57%   |
| 1001-1500      | 22        | 0.43%   |
| 801-900        | 12        | 0.24%   |
| 1-100          | 3         | 0.06%   |
| More than 2000 | 2         | 0.04%   |
| 101-200        | 2         | 0.04%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3762      | 83.36%  |
| 16/10   | 536       | 11.88%  |
| Unknown | 43        | 0.95%   |
| 3/2     | 42        | 0.93%   |
| 21/9    | 40        | 0.89%   |
| 5/4     | 30        | 0.66%   |
| 4/3     | 23        | 0.51%   |
| 0.62    | 17        | 0.38%   |
| 32/9    | 6         | 0.13%   |
| 3.20    | 4         | 0.09%   |
| 3.73    | 3         | 0.07%   |
| 0.67    | 3         | 0.07%   |
| 1.00    | 2         | 0.04%   |
| 3.88    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1927      | 37.66%  |
| 81-90          | 894       | 17.47%  |
| 121-130        | 594       | 11.61%  |
| 201-250        | 409       | 7.99%   |
| 71-80          | 331       | 6.47%   |
| 301-350        | 144       | 2.81%   |
| 61-70          | 134       | 2.62%   |
| 131-140        | 106       | 2.07%   |
| 151-200        | 86        | 1.68%   |
| Unknown        | 85        | 1.66%   |
| 251-300        | 72        | 1.41%   |
| 351-500        | 65        | 1.27%   |
| 51-60          | 64        | 1.25%   |
| 141-150        | 48        | 0.94%   |
| 41-50          | 44        | 0.86%   |
| More than 1000 | 43        | 0.84%   |
| 111-120        | 33        | 0.64%   |
| 501-1000       | 20        | 0.39%   |
| 91-100         | 13        | 0.25%   |
| 1-40           | 5         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1974      | 39.25%  |
| 101-120       | 1560      | 31.02%  |
| 51-100        | 899       | 17.88%  |
| 161-240       | 351       | 6.98%   |
| More than 240 | 127       | 2.53%   |
| Unknown       | 85        | 1.69%   |
| 1-50          | 33        | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3683      | 79.79%  |
| 2     | 716       | 15.51%  |
| 0     | 123       | 2.66%   |
| 3     | 87        | 1.88%   |
| 4     | 5         | 0.11%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2453      | 34.12%  |
| Realtek Semiconductor             | 2316      | 32.22%  |
| Qualcomm Atheros                  | 1103      | 15.34%  |
| Broadcom                          | 479       | 6.66%   |
| Broadcom Limited                  | 98        | 1.36%   |
| Marvell Technology Group          | 88        | 1.22%   |
| MediaTek                          | 81        | 1.13%   |
| Ralink                            | 76        | 1.06%   |
| Dell                              | 42        | 0.58%   |
| ASIX Electronics                  | 41        | 0.57%   |
| Nvidia                            | 33        | 0.46%   |
| Samsung Electronics               | 31        | 0.43%   |
| Ericsson Business Mobile Networks | 26        | 0.36%   |
| Xiaomi                            | 24        | 0.33%   |
| DisplayLink                       | 24        | 0.33%   |
| Sierra Wireless                   | 22        | 0.31%   |
| TP-Link                           | 21        | 0.29%   |
| Qualcomm                          | 18        | 0.25%   |
| Lenovo                            | 18        | 0.25%   |
| Huawei Technologies               | 18        | 0.25%   |
| JMicron Technology                | 17        | 0.24%   |
| NetGear                           | 16        | 0.22%   |
| Ralink Technology                 | 15        | 0.21%   |
| Attansic Technology               | 14        | 0.19%   |
| Hewlett-Packard                   | 12        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 10        | 0.14%   |
| Google                            | 7         | 0.1%    |
| OPPO                              | 6         | 0.08%   |
| D-Link                            | 6         | 0.08%   |
| Toshiba                           | 5         | 0.07%   |
| Fibocom                           | 5         | 0.07%   |
| Apple                             | 5         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.06%   |
| ICS Advent                        | 4         | 0.06%   |
| D-Link System                     | 4         | 0.06%   |
| Arduino SA                        | 4         | 0.06%   |
| VIA Technologies                  | 3         | 0.04%   |
| U-Blox                            | 3         | 0.04%   |
| Belkin Components                 | 3         | 0.04%   |
| Texas Instruments                 | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1383      | 15.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 376       | 4.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 247       | 2.85%   |
| Intel Wi-Fi 6 AX200                                               | 214       | 2.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 184       | 2.13%   |
| Intel Wireless 8265 / 8275                                        | 184       | 2.13%   |
| Intel Wi-Fi 6 AX201                                               | 172       | 1.99%   |
| Intel Wireless 7265                                               | 166       | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 161       | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 159       | 1.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 144       | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 139       | 1.61%   |
| Intel Wireless 8260                                               | 136       | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 136       | 1.57%   |
| Intel Wireless 7260                                               | 135       | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 111       | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 110       | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 108       | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 103       | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 100       | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 91        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 90        | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 85        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 81        | 0.94%   |
| Intel Wireless 3165                                               | 70        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 67        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 67        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 62        | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 59        | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 58        | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 56        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 55        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 55        | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 53        | 0.61%   |
| Intel WiFi Link 5100                                              | 52        | 0.6%    |
| Intel Wireless 3160                                               | 51        | 0.59%   |
| Intel Wireless-AC 9260                                            | 50        | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 49        | 0.57%   |
| Intel Centrino Wireless-N 2230                                    | 46        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2331      | 50.71%  |
| Qualcomm Atheros                      | 906       | 19.71%  |
| Realtek Semiconductor                 | 666       | 14.49%  |
| Broadcom                              | 348       | 7.57%   |
| Ralink                                | 76        | 1.65%   |
| Broadcom Limited                      | 66        | 1.44%   |
| MediaTek                              | 60        | 1.31%   |
| Sierra Wireless                       | 22        | 0.48%   |
| Dell                                  | 21        | 0.46%   |
| TP-Link                               | 17        | 0.37%   |
| Ralink Technology                     | 15        | 0.33%   |
| Qualcomm                              | 13        | 0.28%   |
| NetGear                               | 13        | 0.28%   |
| Ericsson Business Mobile Networks     | 7         | 0.15%   |
| Hewlett-Packard                       | 6         | 0.13%   |
| Fibocom                               | 5         | 0.11%   |
| D-Link                                | 5         | 0.11%   |
| D-Link System                         | 4         | 0.09%   |
| Belkin Components                     | 3         | 0.07%   |
| Qualcomm Atheros Communications       | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| ASUSTek Computer                      | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 214       | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 184       | 3.98%   |
| Intel Wireless 8265 / 8275                                              | 184       | 3.98%   |
| Intel Wi-Fi 6 AX201                                                     | 172       | 3.72%   |
| Intel Wireless 7265                                                     | 166       | 3.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 161       | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 144       | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 139       | 3.01%   |
| Intel Wireless 8260                                                     | 136       | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 136       | 2.94%   |
| Intel Wireless 7260                                                     | 135       | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 111       | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 110       | 2.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 108       | 2.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 103       | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 100       | 2.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 91        | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 90        | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 85        | 1.84%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 81        | 1.75%   |
| Intel Wireless 3165                                                     | 70        | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 67        | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                           | 67        | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 58        | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 56        | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 53        | 1.15%   |
| Intel WiFi Link 5100                                                    | 52        | 1.13%   |
| Intel Wireless 3160                                                     | 51        | 1.1%    |
| Intel Wireless-AC 9260                                                  | 50        | 1.08%   |
| Intel Centrino Wireless-N 2230                                          | 46        | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 42        | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 39        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 39        | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 38        | 0.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 37        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 34        | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 33        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 32        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2078      | 53.17%  |
| Intel                            | 880       | 22.52%  |
| Qualcomm Atheros                 | 345       | 8.83%   |
| Broadcom                         | 185       | 4.73%   |
| Marvell Technology Group         | 88        | 2.25%   |
| ASIX Electronics                 | 41        | 1.05%   |
| Broadcom Limited                 | 35        | 0.9%    |
| Nvidia                           | 33        | 0.84%   |
| Samsung Electronics              | 30        | 0.77%   |
| Xiaomi                           | 24        | 0.61%   |
| DisplayLink                      | 24        | 0.61%   |
| MediaTek                         | 20        | 0.51%   |
| Lenovo                           | 18        | 0.46%   |
| JMicron Technology               | 17        | 0.44%   |
| Attansic Technology              | 14        | 0.36%   |
| Huawei Technologies              | 12        | 0.31%   |
| Silicon Integrated Systems [SiS] | 10        | 0.26%   |
| Google                           | 7         | 0.18%   |
| OPPO                             | 6         | 0.15%   |
| Qualcomm                         | 5         | 0.13%   |
| Apple                            | 5         | 0.13%   |
| TP-Link                          | 4         | 0.1%    |
| ICS Advent                       | 4         | 0.1%    |
| NetGear                          | 3         | 0.08%   |
| VIA Technologies                 | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| Linksys                          | 2         | 0.05%   |
| Cypress Semiconductor            | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| ULi Electronics                  | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Motorola PCS                     | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| Hisense                          | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| Archos                           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1383      | 35.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 376       | 9.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 247       | 6.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 159       | 4.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 62        | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 1.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 59        | 1.5%    |
| Intel Ethernet Connection I219-LM                                 | 55        | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 55        | 1.39%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 43        | 1.09%   |
| Intel 82577LM Gigabit Network Connection                          | 40        | 1.01%   |
| Intel 82567LM Gigabit Network Connection                          | 37        | 0.94%   |
| ASIX AX88179 Gigabit Ethernet                                     | 37        | 0.94%   |
| Intel Ethernet Connection (6) I219-V                              | 32        | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 31        | 0.79%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 31        | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 31        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.71%   |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 27        | 0.68%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 0.68%   |
| Intel Ethernet Connection I217-V                                  | 26        | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 26        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 24        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 23        | 0.58%   |
| Intel Ethernet Connection (13) I219-V                             | 23        | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 21        | 0.53%   |
| Nvidia MCP79 Ethernet                                             | 21        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 21        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.51%   |
| Intel Ethernet Connection (13) I219-LM                            | 19        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 18        | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 17        | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 17        | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 17        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4422      | 53.83%  |
| Ethernet | 3701      | 45.06%  |
| Modem    | 85        | 1.03%   |
| Unknown  | 6         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3548      | 74.12%  |
| Ethernet | 1239      | 25.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3325      | 73.56%  |
| 1     | 1088      | 24.07%  |
| 0     | 65        | 1.44%   |
| 3     | 42        | 0.93%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3031      | 65.34%  |
| Yes  | 1608      | 34.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1803      | 51.86%  |
| Realtek Semiconductor           | 281       | 8.08%   |
| IMC Networks                    | 266       | 7.65%   |
| Qualcomm Atheros Communications | 235       | 6.76%   |
| Broadcom                        | 183       | 5.26%   |
| Lite-On Technology              | 129       | 3.71%   |
| Foxconn / Hon Hai               | 119       | 3.42%   |
| Apple                           | 94        | 2.7%    |
| Dell                            | 80        | 2.3%    |
| Cambridge Silicon Radio         | 55        | 1.58%   |
| Realtek                         | 41        | 1.18%   |
| Hewlett-Packard                 | 37        | 1.06%   |
| Toshiba                         | 36        | 1.04%   |
| Ralink                          | 32        | 0.92%   |
| ASUSTek Computer                | 21        | 0.6%    |
| Ralink Technology               | 19        | 0.55%   |
| Foxconn International           | 13        | 0.37%   |
| Alps Electric                   | 13        | 0.37%   |
| USI                             | 5         | 0.14%   |
| MediaTek                        | 5         | 0.14%   |
| Chicony Electronics             | 5         | 0.14%   |
| TP-Link                         | 1         | 0.03%   |
| Syntek                          | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 708       | 20.35%  |
| Intel AX201 Bluetooth                               | 387       | 11.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 282       | 8.11%   |
| Intel AX200 Bluetooth                               | 203       | 5.84%   |
| Realtek Bluetooth Radio                             | 174       | 5%      |
| IMC Networks Bluetooth Device                       | 104       | 2.99%   |
| Qualcomm Atheros  Bluetooth Device                  | 95        | 2.73%   |
| IMC Networks Bluetooth Radio                        | 75        | 2.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 72        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 66        | 1.9%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 55        | 1.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 54        | 1.55%   |
| Apple Bluetooth Host Controller                     | 49        | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 47        | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.26%   |
| Intel Bluetooth Device                              | 43        | 1.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 42        | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 38        | 1.09%   |
| Lite-On Bluetooth Device                            | 37        | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 36        | 1.03%   |
| Dell DW375 Bluetooth Module                         | 36        | 1.03%   |
| Realtek 802.11ac WLAN Adapter                       | 34        | 0.98%   |
| Ralink RT3290 Bluetooth                             | 32        | 0.92%   |
| IMC Networks Wireless_Device                        | 29        | 0.83%   |
| Broadcom BCM2045B (BDC-2.1)                         | 29        | 0.83%   |
| Apple Bluetooth USB Host Controller                 | 29        | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 28        | 0.8%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 25        | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.72%   |
| Intel AX210 Bluetooth                               | 24        | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                   | 24        | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 18        | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 17        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                | 17        | 0.49%   |
| IMC Networks Bluetooth                              | 15        | 0.43%   |
| Broadcom HP Portable SoftSailing                    | 15        | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3676      | 65.73%  |
| AMD                                          | 852       | 15.23%  |
| Nvidia                                       | 692       | 12.37%  |
| Realtek Semiconductor                        | 57        | 1.02%   |
| GN Netcom                                    | 32        | 0.57%   |
| Logitech                                     | 30        | 0.54%   |
| C-Media Electronics                          | 30        | 0.54%   |
| Plantronics                                  | 23        | 0.41%   |
| JMTek                                        | 19        | 0.34%   |
| Kingston Technology                          | 18        | 0.32%   |
| Lenovo                                       | 16        | 0.29%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.21%   |
| Hewlett-Packard                              | 12        | 0.21%   |
| Corsair                                      | 12        | 0.21%   |
| SteelSeries ApS                              | 7         | 0.13%   |
| Texas Instruments                            | 5         | 0.09%   |
| Focusrite-Novation                           | 5         | 0.09%   |
| DSEA A/S                                     | 4         | 0.07%   |
| Apple                                        | 4         | 0.07%   |
| VIA Technologies                             | 3         | 0.05%   |
| Razer USA                                    | 3         | 0.05%   |
| No brand                                     | 3         | 0.05%   |
| M-Audio                                      | 3         | 0.05%   |
| Elitegroup Computer Systems (ECS)            | 3         | 0.05%   |
| Conexant Systems                             | 3         | 0.05%   |
| Blue Microphones                             | 3         | 0.05%   |
| ZOOM                                         | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |
| RODE Microphones                             | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.04%   |
| Jieli Technology                             | 2         | 0.04%   |
| Generalplus Technology                       | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Cambridge Audio                              | 2         | 0.04%   |
| Barco Display Systems                        | 2         | 0.04%   |
| Avid Technology                              | 2         | 0.04%   |
| Alesis                                       | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| Yealink Network Technology                   | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 481       | 7.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 384       | 5.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 373       | 5.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 244       | 3.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 238       | 3.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 228       | 3.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 224       | 3.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 197       | 2.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 192       | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 180       | 2.68%   |
| Intel 8 Series HD Audio Controller                                                                | 172       | 2.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 170       | 2.53%   |
| Intel Broadwell-U Audio Controller                                                                | 166       | 2.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 165       | 2.45%   |
| AMD FCH Azalia Controller                                                                         | 158       | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 153       | 2.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 141       | 2.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 136       | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 134       | 1.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 114       | 1.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 105       | 1.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 91        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 91        | 1.35%   |
| Intel CM238 HD Audio Controller                                                                   | 87        | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 83        | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 76        | 1.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 73        | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 72        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 68        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 68        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 66        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 62        | 0.92%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 60        | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 58        | 0.86%   |
| Realtek Semiconductor USB Audio                                                                   | 56        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 56        | 0.83%   |
| AMD Wrestler HDMI Audio                                                                           | 56        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 55        | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 54        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 46        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 1018      | 29.88%  |
| SK hynix                                         | 895       | 26.27%  |
| Micron Technology                                | 414       | 12.15%  |
| Kingston                                         | 241       | 7.07%   |
| Unknown                                          | 238       | 6.99%   |
| Crucial                                          | 161       | 4.73%   |
| Elpida                                           | 67        | 1.97%   |
| Ramaxel Technology                               | 63        | 1.85%   |
| Corsair                                          | 54        | 1.58%   |
| Nanya Technology                                 | 45        | 1.32%   |
| A-DATA Technology                                | 45        | 1.32%   |
| G.Skill                                          | 40        | 1.17%   |
| Unknown (ABCD)                                   | 37        | 1.09%   |
| Transcend                                        | 10        | 0.29%   |
| Unknown                                          | 9         | 0.26%   |
| Patriot                                          | 5         | 0.15%   |
| ASint Technology                                 | 5         | 0.15%   |
| Apacer                                           | 4         | 0.12%   |
| V-Color                                          | 3         | 0.09%   |
| Toshiba                                          | 3         | 0.09%   |
| Timetec                                          | 3         | 0.09%   |
| Team                                             | 3         | 0.09%   |
| SHARETRONIC                                      | 3         | 0.09%   |
| PNY                                              | 3         | 0.09%   |
| TEXTORM                                          | 2         | 0.06%   |
| Goldkey                                          | 2         | 0.06%   |
| ChangXin Memory                                  | 2         | 0.06%   |
| 48spaces                                         | 2         | 0.06%   |
| Unknown (F301)                                   | 1         | 0.03%   |
| Unknown (0x8634)                                 | 1         | 0.03%   |
| Unknown (0x7301)                                 | 1         | 0.03%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.03%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.03%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.03%   |
| Unknown (0x0C97)                                 | 1         | 0.03%   |
| Unknown (07FB)                                   | 1         | 0.03%   |
| Unknown (01F3)                                   | 1         | 0.03%   |
| Unknown (000000008A91)                           | 1         | 0.03%   |
| Teikon                                           | 1         | 0.03%   |
| Silicon Power                                    | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 50        | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 49        | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 48        | 1.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 47        | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 1.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 43        | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 38        | 1.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 37        | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 36        | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 35        | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 35        | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 35        | 0.98%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 34        | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 32        | 0.89%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 29        | 0.81%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 28        | 0.78%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 24        | 0.67%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 21        | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 18        | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.5%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 17        | 0.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 16        | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.45%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 16        | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.45%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 16        | 0.45%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 16        | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.42%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 15        | 0.42%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 15        | 0.42%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 14        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1340      | 45.89%  |
| DDR3    | 1051      | 35.99%  |
| DDR2    | 146       | 5%      |
| LPDDR4  | 132       | 4.52%   |
| LPDDR3  | 102       | 3.49%   |
| SDRAM   | 67        | 2.29%   |
| Unknown | 24        | 0.82%   |
| LPDDR5  | 20        | 0.68%   |
| DDR5    | 20        | 0.68%   |
| DDR     | 12        | 0.41%   |
| DRAM    | 6         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2615      | 89.68%  |
| Row Of Chips | 265       | 9.09%   |
| Chip         | 16        | 0.55%   |
| DIMM         | 11        | 0.38%   |
| Unknown      | 9         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1146      | 36.29%  |
| 4096  | 1030      | 32.62%  |
| 2048  | 419       | 13.27%  |
| 16384 | 394       | 12.48%  |
| 1024  | 100       | 3.17%   |
| 32768 | 60        | 1.9%    |
| 512   | 8         | 0.25%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 756       | 24.17%  |
| 2667    | 621       | 19.85%  |
| 3200    | 528       | 16.88%  |
| 2400    | 214       | 6.84%   |
| 1334    | 165       | 5.27%   |
| 2133    | 162       | 5.18%   |
| 1333    | 107       | 3.42%   |
| 667     | 84        | 2.69%   |
| 4267    | 60        | 1.92%   |
| Unknown | 52        | 1.66%   |
| 3266    | 50        | 1.6%    |
| 1067    | 47        | 1.5%    |
| 1867    | 39        | 1.25%   |
| 4199    | 33        | 1.05%   |
| 800     | 33        | 1.05%   |
| 2048    | 28        | 0.9%    |
| 4800    | 26        | 0.83%   |
| 1066    | 22        | 0.7%    |
| 6400    | 20        | 0.64%   |
| 975     | 19        | 0.61%   |
| 533     | 14        | 0.45%   |
| 4266    | 11        | 0.35%   |
| 8400    | 8         | 0.26%   |
| 2933    | 6         | 0.19%   |
| 1866    | 5         | 0.16%   |
| 3000    | 4         | 0.13%   |
| 333     | 4         | 0.13%   |
| 3733    | 3         | 0.1%    |
| 1639    | 3         | 0.1%    |
| 400     | 2         | 0.06%   |
| 933     | 1         | 0.03%   |
| 266     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 37.5%   |
| Canon               | 10        | 25%     |
| Seiko Epson         | 4         | 10%     |
| Samsung Electronics | 4         | 10%     |
| Brother Industries  | 4         | 10%     |
| Xiaomi              | 1         | 2.5%    |
| STMicroelectronics  | 1         | 2.5%    |
| QinHeng Electronics | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 10%     |
| HP DeskJet 3630 series                                    | 3         | 7.5%    |
| Canon PIXMA MG2500 Series                                 | 3         | 7.5%    |
| Seiko Epson WF-2830 Series                                | 2         | 5%      |
| Canon PIXMA MG3600 Series                                 | 2         | 5%      |
| Xiaomi MiMouse 2                                          | 1         | 2.5%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.5%    |
| Seiko Epson XP-255 257 Series                             | 1         | 2.5%    |
| Seiko Epson XP-2150 Series                                | 1         | 2.5%    |
| Samsung SCX-3200 Series                                   | 1         | 2.5%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.5%    |
| Samsung M2070 Series                                      | 1         | 2.5%    |
| Samsung M2020 Series                                      | 1         | 2.5%    |
| QinHeng CH340S                                            | 1         | 2.5%    |
| HP Photosmart B010 series                                 | 1         | 2.5%    |
| HP OfficeJet Pro 69                                       | 1         | 2.5%    |
| HP OfficeJet 3830 series                                  | 1         | 2.5%    |
| HP ENVY Photo 6200 series                                 | 1         | 2.5%    |
| HP ENVY 5540 series                                       | 1         | 2.5%    |
| HP ENVY 4500 series                                       | 1         | 2.5%    |
| HP Deskjet F4500 series                                   | 1         | 2.5%    |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2.5%    |
| Canon TS6100 series                                       | 1         | 2.5%    |
| Canon PIXMA MP495                                         | 1         | 2.5%    |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.5%    |
| Canon PIXMA MG3500 Series                                 | 1         | 2.5%    |
| Canon MG2100 series                                       | 1         | 2.5%    |
| Brother MFC-L8690CDW series                               | 1         | 2.5%    |
| Brother MFC-L2710DW series                                | 1         | 2.5%    |
| Brother MFC-1810                                          | 1         | 2.5%    |
| Brother DCP-L3550CDW series                               | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 54.55%  |
| Seiko Epson     | 4         | 36.36%  |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 3         | 27.27%  |
| Seiko Epson Scanner                           | 1         | 9.09%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 9.09%   |
| HP ScanJet 3570c                              | 1         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 9.09%   |
| Canon CanoScan N650U/N656U                    | 1         | 9.09%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 994       | 24.68%  |
| IMC Networks                           | 469       | 11.65%  |
| Microdia                               | 398       | 9.88%   |
| Realtek Semiconductor                  | 387       | 9.61%   |
| Acer                                   | 333       | 8.27%   |
| Sunplus Innovation Technology          | 250       | 6.21%   |
| Suyin                                  | 167       | 4.15%   |
| Cheng Uei Precision Industry (Foxlink) | 167       | 4.15%   |
| Quanta                                 | 139       | 3.45%   |
| Lite-On Technology                     | 105       | 2.61%   |
| Apple                                  | 92        | 2.28%   |
| Syntek                                 | 80        | 1.99%   |
| Alcor Micro                            | 54        | 1.34%   |
| Logitech                               | 46        | 1.14%   |
| Ricoh                                  | 45        | 1.12%   |
| Luxvisions Innotech Limited            | 44        | 1.09%   |
| Silicon Motion                         | 40        | 0.99%   |
| Samsung Electronics                    | 23        | 0.57%   |
| Lenovo                                 | 21        | 0.52%   |
| Primax Electronics                     | 18        | 0.45%   |
| Importek                               | 15        | 0.37%   |
| Sonix Technology                       | 14        | 0.35%   |
| DigiTech                               | 14        | 0.35%   |
| Z-Star Microelectronics                | 12        | 0.3%    |
| ALi                                    | 11        | 0.27%   |
| GEMBIRD                                | 7         | 0.17%   |
| Bison Electronics                      | 7         | 0.17%   |
| OmniVision Technologies                | 6         | 0.15%   |
| icSpring                               | 6         | 0.15%   |
| Y Media                                | 5         | 0.12%   |
| Denron                                 | 4         | 0.1%    |
| Xiaomi                                 | 3         | 0.07%   |
| Pixart Imaging                         | 3         | 0.07%   |
| Microsoft                              | 3         | 0.07%   |
| Intel                                  | 3         | 0.07%   |
| Generalplus Technology                 | 3         | 0.07%   |
| ARC International                      | 3         | 0.07%   |
| SunplusIT                              | 2         | 0.05%   |
| Sunplus Technology                     | 2         | 0.05%   |
| ShineTech                              | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 214       | 5.29%   |
| Realtek Integrated_Webcam_HD             | 169       | 4.18%   |
| Chicony Integrated Camera                | 153       | 3.78%   |
| IMC Networks USB2.0 HD UVC WebCam        | 107       | 2.65%   |
| Chicony HD Webcam                        | 102       | 2.52%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 84        | 2.08%   |
| IMC Networks Integrated Camera           | 83        | 2.05%   |
| Acer Integrated Camera                   | 71        | 1.76%   |
| Sunplus Integrated_Webcam_HD             | 65        | 1.61%   |
| Acer HD Webcam                           | 49        | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam            | 47        | 1.16%   |
| Realtek USB Camera                       | 46        | 1.14%   |
| Chicony USB2.0 Camera                    | 46        | 1.14%   |
| Sunplus Asus Webcam                      | 40        | 0.99%   |
| Chicony USB2.0 HD UVC WebCam             | 40        | 0.99%   |
| Chicony TOSHIBA Web Camera - HD          | 40        | 0.99%   |
| Microdia Integrated Webcam               | 39        | 0.96%   |
| Chicony HP HD Camera                     | 39        | 0.96%   |
| Acer BisonCam,NB Pro                     | 38        | 0.94%   |
| Chicony HP HD Webcam                     | 35        | 0.87%   |
| Syntek Integrated Camera                 | 34        | 0.84%   |
| Chicony USB 2.0 Camera                   | 34        | 0.84%   |
| Chicony HP Truevision HD                 | 34        | 0.84%   |
| Realtek USB2.0 HD UVC WebCam             | 32        | 0.79%   |
| Chicony HP Truevision HD camera          | 32        | 0.79%   |
| Acer BisonCam, NB Pro                    | 32        | 0.79%   |
| Lite-On Integrated Camera                | 31        | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE                | 30        | 0.74%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 29        | 0.72%   |
| Apple Built-in iSight                    | 29        | 0.72%   |
| Sunplus HD WebCam                        | 27        | 0.67%   |
| Acer Lenovo EasyCamera                   | 27        | 0.67%   |
| Chicony VGA Webcam                       | 26        | 0.64%   |
| IMC Networks UVC VGA Webcam              | 25        | 0.62%   |
| Samsung Galaxy A5 (MTP)                  | 23        | 0.57%   |
| Quanta HP HD Camera                      | 23        | 0.57%   |
| IMC Networks ov9734_azurewave_camera     | 23        | 0.57%   |
| Apple FaceTime HD Camera                 | 22        | 0.54%   |
| Lite-On HP HD Webcam                     | 21        | 0.52%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 21        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 271       | 36.47%  |
| Synaptics                  | 153       | 20.59%  |
| Shenzhen Goodix Technology | 140       | 18.84%  |
| AuthenTec                  | 61        | 8.21%   |
| LighTuning Technology      | 38        | 5.11%   |
| Elan Microelectronics      | 38        | 5.11%   |
| Upek                       | 30        | 4.04%   |
| STMicroelectronics         | 11        | 1.48%   |
| Focal-systems.Corp         | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 77        | 10.36%  |
| Shenzhen Goodix  Fingerprint Device                                        | 74        | 9.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 63        | 8.48%   |
| Unknown                                                                    | 41        | 5.52%   |
| Shenzhen Goodix FingerPrint                                                | 39        | 5.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 30        | 4.04%   |
| Elan ELAN:Fingerprint                                                      | 28        | 3.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 3.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 26        | 3.5%    |
| Validity Sensors VFS491                                                    | 23        | 3.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 3.1%    |
| AuthenTec AES2810                                                          | 22        | 2.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.42%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 2.29%   |
| Validity Sensors Fingerprint scanner                                       | 17        | 2.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 2.15%   |
| AuthenTec AES1600                                                          | 14        | 1.88%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.75%   |
| AuthenTec Fingerprint Sensor                                               | 13        | 1.75%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 1.62%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.48%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.48%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 1.35%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 1.21%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.21%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 1.08%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.81%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.67%   |
| Synaptics WBDI Device                                                      | 5         | 0.67%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.54%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.4%    |
| Synaptics  WBDI                                                            | 3         | 0.4%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.4%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.27%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 216       | 56.69%  |
| Alcor Micro               | 81        | 21.26%  |
| O2 Micro                  | 33        | 8.66%   |
| Upek                      | 17        | 4.46%   |
| Lenovo                    | 16        | 4.2%    |
| Hewlett-Packard           | 5         | 1.31%   |
| Gemalto (was Gemplus)     | 4         | 1.05%   |
| Yubico.com                | 2         | 0.52%   |
| Clay Logic                | 2         | 0.52%   |
| Aladdin Knowledge Systems | 2         | 0.52%   |
| SpringCard                | 1         | 0.26%   |
| OmniKey                   | 1         | 0.26%   |
| Chicony Electronics       | 1         | 0.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 21.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 74        | 19.42%  |
| Broadcom 58200                                                               | 63        | 16.54%  |
| Broadcom 5880                                                                | 45        | 11.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 33        | 8.66%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 30        | 7.87%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 4.46%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 4.2%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.31%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.79%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 0.52%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.52%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.52%   |
| SpringCard Two                                                               | 1         | 0.26%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.26%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.26%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.26%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.26%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2873      | 61.93%  |
| 1     | 1400      | 30.18%  |
| 2     | 293       | 6.32%   |
| 3     | 54        | 1.16%   |
| 4     | 8         | 0.17%   |
| 5     | 5         | 0.11%   |
| 6     | 3         | 0.06%   |
| 7     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 734       | 34.11%  |
| Graphics card            | 457       | 21.24%  |
| Chipcard                 | 355       | 16.5%   |
| Net/wireless             | 187       | 8.69%   |
| Multimedia controller    | 80        | 3.72%   |
| Camera                   | 76        | 3.53%   |
| Bluetooth                | 66        | 3.07%   |
| Storage                  | 53        | 2.46%   |
| Communication controller | 41        | 1.91%   |
| Card reader              | 33        | 1.53%   |
| Sound                    | 22        | 1.02%   |
| Modem                    | 16        | 0.74%   |
| Net/ethernet             | 15        | 0.7%    |
| Network                  | 6         | 0.28%   |
| Flash memory             | 3         | 0.14%   |
| Unclassified device      | 2         | 0.09%   |
| Wireless                 | 1         | 0.05%   |
| Unassigned class         | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ata              | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

