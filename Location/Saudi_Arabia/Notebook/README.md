Linux in Saudi Arabia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

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

Total: 196

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 13s-IML 20RR      | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| Dell          | G15 5515                    | [ae769dae75](https://linux-hardware.org/?probe=ae769dae75) | Sep 24, 2022 |
| Dell          | G15 5515                    | [893c248dec](https://linux-hardware.org/?probe=893c248dec) | Sep 24, 2022 |
| Dell          | G15 5515                    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a934e23e1f](https://linux-hardware.org/?probe=a934e23e1f) | Sep 16, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Notebook      | NH5xAx                      | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| Dell          | Vostro 15 3515              | [4ecdbb8b4b](https://linux-hardware.org/?probe=4ecdbb8b4b) | Aug 15, 2022 |
| Acer          | Aspire 4752                 | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| eMachines     | Unknown                     | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Lenovo        | B590 20206                  | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| MSI           | GF63 Thin 8RCS              | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| Dell          | Inspiron 3580               | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| Acer          | Aspire V3-571               | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Dell          | Inspiron 3580               | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | Inspiron 3542               | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [45548a6fe5](https://linux-hardware.org/?probe=45548a6fe5) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Dell          | Inspiron 14-3467            | [50131c5da4](https://linux-hardware.org/?probe=50131c5da4) | Mar 21, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| Acer          | AO751h                      | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| ASUSTek       | K53SC                       | [43b019326c](https://linux-hardware.org/?probe=43b019326c) | Feb 12, 2022 |
| ASUSTek       | K53SC                       | [70f23c3da0](https://linux-hardware.org/?probe=70f23c3da0) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [261fe8bda7](https://linux-hardware.org/?probe=261fe8bda7) | Jan 07, 2022 |
| Sony          | VPCCA35FA                   | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Packard Be... | EasyNote TJ65               | [b98b9252fa](https://linux-hardware.org/?probe=b98b9252fa) | Dec 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| Lenovo        | V15-IIL 82C5                | [2a151de62b](https://linux-hardware.org/?probe=2a151de62b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| Toshiba       | Satellite L500              | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 20RA008CAD     | [35fab17b69](https://linux-hardware.org/?probe=35fab17b69) | Dec 01, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Toshiba       | Satellite L500              | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| Lenovo        | V15-IIL 82C5                | [e37587fbac](https://linux-hardware.org/?probe=e37587fbac) | Nov 23, 2021 |
| Lenovo        | V15-IIL 82C5                | [b050debd0a](https://linux-hardware.org/?probe=b050debd0a) | Nov 22, 2021 |
| Dell          | G3 3590                     | [605f0870d0](https://linux-hardware.org/?probe=605f0870d0) | Nov 16, 2021 |
| Dell          | G3 3590                     | [5bfafc889c](https://linux-hardware.org/?probe=5bfafc889c) | Nov 16, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | V570 1066AJU                | [ffb36aac10](https://linux-hardware.org/?probe=ffb36aac10) | Nov 05, 2021 |
| Dell          | Inspiron 3593               | [5233ea30c6](https://linux-hardware.org/?probe=5233ea30c6) | Oct 09, 2021 |
| Lenovo        | ThinkPad P52s 20LBS0JC00    | [4c8c63da2f](https://linux-hardware.org/?probe=4c8c63da2f) | Oct 05, 2021 |
| HP            | Laptop 15-da2xxx            | [2e99b047ff](https://linux-hardware.org/?probe=2e99b047ff) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de6b4e47d4](https://linux-hardware.org/?probe=de6b4e47d4) | Oct 01, 2021 |
| HP            | Laptop 15-da2xxx            | [28332170d1](https://linux-hardware.org/?probe=28332170d1) | Sep 28, 2021 |
| Dell          | Inspiron N5110              | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Acer          | Aspire V3-571               | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Toshiba       | Satellite C55-B             | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Toshiba       | Satellite C55-B             | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| Dell          | Latitude E7440              | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Dell          | Latitude E5470              | [f91acefb07](https://linux-hardware.org/?probe=f91acefb07) | Aug 14, 2021 |
| Dell          | XPS 15 9560                 | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| ASUSTek       | K43SJ                       | [f4702e95b4](https://linux-hardware.org/?probe=f4702e95b4) | Jul 05, 2021 |
| Dell          | XPS 15 9560                 | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | G3 3590                     | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Dell          | Inspiron 5437               | [06f25de7e3](https://linux-hardware.org/?probe=06f25de7e3) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | [3fcbd5cd4f](https://linux-hardware.org/?probe=3fcbd5cd4f) | Jun 18, 2021 |
| Dell          | G3 3590                     | [877018f0d3](https://linux-hardware.org/?probe=877018f0d3) | Jun 18, 2021 |
| Dell          | G3 3590                     | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| HP            | ProBook 445 G7              | [88e51bfd39](https://linux-hardware.org/?probe=88e51bfd39) | May 23, 2021 |
| ASUSTek       | GL502VMK                    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| HP            | ProBook 445 G7              | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1d4c05756f](https://linux-hardware.org/?probe=1d4c05756f) | May 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9b03874730](https://linux-hardware.org/?probe=9b03874730) | Apr 27, 2021 |
| Dell          | Latitude E7470              | [1058573f86](https://linux-hardware.org/?probe=1058573f86) | Apr 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [14fd40d980](https://linux-hardware.org/?probe=14fd40d980) | Apr 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b31da2d02](https://linux-hardware.org/?probe=0b31da2d02) | Apr 16, 2021 |
| HP            | Pavilion Laptop 15t-eg00... | [cd64675ac7](https://linux-hardware.org/?probe=cd64675ac7) | Mar 30, 2021 |
| Toshiba       | Satellite S55t-A            | [9ede240e19](https://linux-hardware.org/?probe=9ede240e19) | Mar 20, 2021 |
| Apple         | MacBookPro9,2               | [7d8acdd5b6](https://linux-hardware.org/?probe=7d8acdd5b6) | Mar 19, 2021 |
| Toshiba       | Satellite S55t-A            | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| Acer          | Nitro AN515-52              | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | X555UB                      | [260d78f7c8](https://linux-hardware.org/?probe=260d78f7c8) | Feb 20, 2021 |
| HP            | Pavilion g6                 | [30bcebb4be](https://linux-hardware.org/?probe=30bcebb4be) | Feb 16, 2021 |
| Lenovo        | ThinkPad E460 20ET000MAD    | [cd000b8e6b](https://linux-hardware.org/?probe=cd000b8e6b) | Feb 11, 2021 |
| Dell          | Inspiron 3593               | [5407a15ab7](https://linux-hardware.org/?probe=5407a15ab7) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | [0802cedb25](https://linux-hardware.org/?probe=0802cedb25) | Feb 09, 2021 |
| Dell          | Latitude E4310              | [9c6781e592](https://linux-hardware.org/?probe=9c6781e592) | Feb 08, 2021 |
| ASUSTek       | ROG Strix G512LWS_G512LW... | [d4d3110510](https://linux-hardware.org/?probe=d4d3110510) | Jan 29, 2021 |
| Toshiba       | Satellite C855D             | [46d5bf62c7](https://linux-hardware.org/?probe=46d5bf62c7) | Jan 19, 2021 |
| Dell          | Inspiron 3576               | [99f1a1ac09](https://linux-hardware.org/?probe=99f1a1ac09) | Jan 16, 2021 |
| Sony          | VGN-FZ250E                  | [d0d77ffe81](https://linux-hardware.org/?probe=d0d77ffe81) | Jan 15, 2021 |
| HP            | Laptop 14-ck0xxx            | [92ea4004af](https://linux-hardware.org/?probe=92ea4004af) | Jan 15, 2021 |
| Sony          | VGN-FZ250E                  | [68ddc53941](https://linux-hardware.org/?probe=68ddc53941) | Jan 14, 2021 |
| Dell          | Inspiron 3576               | [b21e44d0c4](https://linux-hardware.org/?probe=b21e44d0c4) | Jan 11, 2021 |
| Dell          | Vostro 5470                 | [216df384d8](https://linux-hardware.org/?probe=216df384d8) | Dec 22, 2020 |
| Dell          | Vostro 5470                 | [bec1b16786](https://linux-hardware.org/?probe=bec1b16786) | Dec 22, 2020 |
| LG Electro... | R490-G.ARL5RE2              | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [239675db8d](https://linux-hardware.org/?probe=239675db8d) | Nov 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dfcc723611](https://linux-hardware.org/?probe=dfcc723611) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b164be6cfc](https://linux-hardware.org/?probe=b164be6cfc) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [cce5403051](https://linux-hardware.org/?probe=cce5403051) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| I-Life Dig... | ZED Air Plus                | [b1a43bf9f2](https://linux-hardware.org/?probe=b1a43bf9f2) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e9ca4c8d42](https://linux-hardware.org/?probe=e9ca4c8d42) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Acer          | Aspire E1-532P              | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c45580b2f3](https://linux-hardware.org/?probe=c45580b2f3) | Oct 28, 2020 |
| MSI           | MS-1454                     | [0accbf6c77](https://linux-hardware.org/?probe=0accbf6c77) | Oct 14, 2020 |
| Acer          | Swift SF314-52              | [a1665a6de1](https://linux-hardware.org/?probe=a1665a6de1) | Sep 26, 2020 |
| Acer          | Aspire E5-571G              | [d52f9c5bc7](https://linux-hardware.org/?probe=d52f9c5bc7) | Sep 18, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [6963343ed4](https://linux-hardware.org/?probe=6963343ed4) | Sep 17, 2020 |
| Clevo         | P15xEMx                     | [83d0f6aae6](https://linux-hardware.org/?probe=83d0f6aae6) | Aug 28, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| HP            | Pavilion g6                 | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| ASUSTek       | T100TA                      | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Acer          | Swift SF314-52              | [c5f91bc1ff](https://linux-hardware.org/?probe=c5f91bc1ff) | Jun 16, 2020 |
| Dell          | Inspiron N5030              | [5641d9b86e](https://linux-hardware.org/?probe=5641d9b86e) | Jun 14, 2020 |
| ASUSTek       | UX390UAK                    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Sony          | SVF153290X                  | [e19f1c716f](https://linux-hardware.org/?probe=e19f1c716f) | May 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [117bc7af0e](https://linux-hardware.org/?probe=117bc7af0e) | May 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0444dd48d1](https://linux-hardware.org/?probe=0444dd48d1) | May 09, 2020 |
| Acer          | Aspire E1-532P              | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | [8ee1846a65](https://linux-hardware.org/?probe=8ee1846a65) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [bff527c13e](https://linux-hardware.org/?probe=bff527c13e) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8b02fac19f](https://linux-hardware.org/?probe=8b02fac19f) | Apr 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [640431a321](https://linux-hardware.org/?probe=640431a321) | Apr 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [095b8a5cdc](https://linux-hardware.org/?probe=095b8a5cdc) | Apr 16, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [874b42a4b7](https://linux-hardware.org/?probe=874b42a4b7) | Apr 16, 2020 |
| HP            | 15                          | [68b0d776a9](https://linux-hardware.org/?probe=68b0d776a9) | Apr 08, 2020 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [784de80b54](https://linux-hardware.org/?probe=784de80b54) | Apr 08, 2020 |
| HP            | Notebook                    | [f22cd145c5](https://linux-hardware.org/?probe=f22cd145c5) | Apr 07, 2020 |
| HP            | 15                          | [27ef1499e3](https://linux-hardware.org/?probe=27ef1499e3) | Apr 06, 2020 |
| HP            | 15                          | [0c2b7adf55](https://linux-hardware.org/?probe=0c2b7adf55) | Apr 06, 2020 |
| HP            | 15                          | [ee5fd88936](https://linux-hardware.org/?probe=ee5fd88936) | Apr 03, 2020 |
| HP            | 15                          | [bfd4fe41b3](https://linux-hardware.org/?probe=bfd4fe41b3) | Apr 03, 2020 |
| HP            | Laptop 15-bs1xx             | [cdce411ba5](https://linux-hardware.org/?probe=cdce411ba5) | Mar 13, 2020 |
| HP            | Laptop 15-bs1xx             | [6e7a1c3bc6](https://linux-hardware.org/?probe=6e7a1c3bc6) | Mar 13, 2020 |
| HP            | Laptop 15-da0xxx            | [d3d2a3b89f](https://linux-hardware.org/?probe=d3d2a3b89f) | Mar 05, 2020 |
| ASUSTek       | X555QA                      | [2f0a038eaf](https://linux-hardware.org/?probe=2f0a038eaf) | Feb 11, 2020 |
| ASUSTek       | X555QA                      | [e8062aced5](https://linux-hardware.org/?probe=e8062aced5) | Feb 10, 2020 |
| Dell          | Vostro 1440                 | [203e61a7c9](https://linux-hardware.org/?probe=203e61a7c9) | Feb 01, 2020 |
| HP            | Notebook                    | [86dc2687ad](https://linux-hardware.org/?probe=86dc2687ad) | Jan 29, 2020 |
| HP            | Notebook                    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | [953a43ae80](https://linux-hardware.org/?probe=953a43ae80) | Jan 02, 2020 |
| Lenovo        | ThinkPad X230 2325OA3       | [ad8913bb6b](https://linux-hardware.org/?probe=ad8913bb6b) | Dec 09, 2019 |
| GPD           | MicroPC                     | [37bfeee080](https://linux-hardware.org/?probe=37bfeee080) | Dec 09, 2019 |
| ASUSTek       | X555LDB                     | [fffe9c8500](https://linux-hardware.org/?probe=fffe9c8500) | Sep 04, 2019 |
| ASUSTek       | X555LDB                     | [60bc2f13a4](https://linux-hardware.org/?probe=60bc2f13a4) | Sep 04, 2019 |
| Acer          | Aspire 4752                 | [4b1cbc26db](https://linux-hardware.org/?probe=4b1cbc26db) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | [5670d72491](https://linux-hardware.org/?probe=5670d72491) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | [81bd1c9f07](https://linux-hardware.org/?probe=81bd1c9f07) | Aug 13, 2019 |
| Sony          | VPCEA36FA                   | [069db5e1d5](https://linux-hardware.org/?probe=069db5e1d5) | Jul 11, 2019 |
| HUAWEI        | MateBook D                  | [0c82ca3724](https://linux-hardware.org/?probe=0c82ca3724) | Jul 06, 2019 |
| ASUSTek       | X540UA                      | [b66944b7d8](https://linux-hardware.org/?probe=b66944b7d8) | Jun 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [630f59eb30](https://linux-hardware.org/?probe=630f59eb30) | Jun 12, 2019 |
| ASUSTek       | X540UA                      | [3d424bc8d3](https://linux-hardware.org/?probe=3d424bc8d3) | Jun 07, 2019 |
| ASUSTek       | X540UA                      | [8b98fb721c](https://linux-hardware.org/?probe=8b98fb721c) | Jun 07, 2019 |
| ASUSTek       | X540NA                      | [ced21dc1f3](https://linux-hardware.org/?probe=ced21dc1f3) | May 21, 2019 |
| Sony          | SVF14N13CXB                 | [37e231ce84](https://linux-hardware.org/?probe=37e231ce84) | Apr 07, 2019 |
| HP            | 15                          | [e900ad9cfc](https://linux-hardware.org/?probe=e900ad9cfc) | Mar 15, 2019 |
| Lenovo        | Flex 2-15 20405             | [d44c9b123d](https://linux-hardware.org/?probe=d44c9b123d) | Dec 19, 2018 |
| Lenovo        | Flex 2-15 20405             | [b0c7903cb1](https://linux-hardware.org/?probe=b0c7903cb1) | Dec 19, 2018 |
| Acer          | Aspire E1-532P              | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Ubuntu 20.04           | 23        | 17.69%  |
| Ubuntu 18.04           | 11        | 8.46%   |
| OpenMandriva 4.2       | 6         | 4.62%   |
| Fedora 35              | 5         | 3.85%   |
| Ubuntu 20.10           | 4         | 3.08%   |
| Zorin 16               | 3         | 2.31%   |
| Ubuntu 21.04           | 3         | 2.31%   |
| Pop!_OS 20.04          | 3         | 2.31%   |
| OpenMandriva 4.3       | 3         | 2.31%   |
| Endless 3.3.20-nexthw1 | 3         | 2.31%   |
| Debian Testing         | 3         | 2.31%   |
| Arch                   | 3         | 2.31%   |
| Ubuntu 19.04           | 2         | 1.54%   |
| Pop!_OS 22.04          | 2         | 1.54%   |
| Pop!_OS 20.10          | 2         | 1.54%   |
| Manjaro 20.0.3         | 2         | 1.54%   |
| Linux Mint 20.1        | 2         | 1.54%   |
| Linux Mint 20          | 2         | 1.54%   |
| Kubuntu 20.04          | 2         | 1.54%   |
| Kali 2021.2            | 2         | 1.54%   |
| Endless 3.7.8          | 2         | 1.54%   |
| Xubuntu 20.10          | 1         | 0.77%   |
| Xubuntu 20.04          | 1         | 0.77%   |
| Xubuntu 18.04          | 1         | 0.77%   |
| Ubuntu Unity 16.04     | 1         | 0.77%   |
| Ubuntu 22.04           | 1         | 0.77%   |
| Ubuntu 19.10           | 1         | 0.77%   |
| Solus 4.1              | 1         | 0.77%   |
| Solus 3.9999           | 1         | 0.77%   |
| ROSA R8.1              | 1         | 0.77%   |
| RHEL 8                 | 1         | 0.77%   |
| Q4OS 4                 | 1         | 0.77%   |
| Pop!_OS 21.10          | 1         | 0.77%   |
| Pop!_OS 21.04          | 1         | 0.77%   |
| Parrot 5.1             | 1         | 0.77%   |
| Manjaro 21.2.6         | 1         | 0.77%   |
| Manjaro 21.2.5         | 1         | 0.77%   |
| Manjaro 21.2.0         | 1         | 0.77%   |
| Manjaro                | 1         | 0.77%   |
| Linux Mint 19.1        | 1         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 45        | 36.59%  |
| Endless      | 13        | 10.57%  |
| OpenMandriva | 9         | 7.32%   |
| Fedora       | 7         | 5.69%   |
| Pop!_OS      | 6         | 4.88%   |
| Manjaro      | 5         | 4.07%   |
| Linux Mint   | 5         | 4.07%   |
| Debian       | 5         | 4.07%   |
| Zorin        | 3         | 2.44%   |
| Xubuntu      | 3         | 2.44%   |
| Kali         | 3         | 2.44%   |
| Arch         | 3         | 2.44%   |
| Kubuntu      | 2         | 1.63%   |
| KDE neon     | 2         | 1.63%   |
| Clear Linux  | 2         | 1.63%   |
| Ubuntu Unity | 1         | 0.81%   |
| Solus        | 1         | 0.81%   |
| ROSA         | 1         | 0.81%   |
| RHEL         | 1         | 0.81%   |
| Q4OS         | 1         | 0.81%   |
| Parrot       | 1         | 0.81%   |
| Liberty OS   | 1         | 0.81%   |
| Gentoo       | 1         | 0.81%   |
| Elementary   | 1         | 0.81%   |
| ArcoLinux    | 1         | 0.81%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 5         | 3.68%   |
| 5.4.0-42-generic         | 4         | 2.94%   |
| 4.15.0-15-generic        | 4         | 2.94%   |
| 5.4.0-19-generic         | 3         | 2.21%   |
| 5.16.7-desktop-1omv4003  | 3         | 2.21%   |
| 5.11.0-43-generic        | 3         | 2.21%   |
| 5.8.0-53-generic         | 2         | 1.47%   |
| 5.8.0-41-generic         | 2         | 1.47%   |
| 5.8.0-38-generic         | 2         | 1.47%   |
| 5.8.0-36-generic         | 2         | 1.47%   |
| 5.4.0-58-generic         | 2         | 1.47%   |
| 5.4.0-37-generic         | 2         | 1.47%   |
| 5.3.0-28-generic         | 2         | 1.47%   |
| 5.3.0-2-amd64            | 2         | 1.47%   |
| 5.11.0-41-generic        | 2         | 1.47%   |
| 5.11.0-40-generic        | 2         | 1.47%   |
| 5.11.0-37-generic        | 2         | 1.47%   |
| 5.11.0-31-generic        | 2         | 1.47%   |
| 5.0.0-20-generic         | 2         | 1.47%   |
| 4.15.0-29-generic        | 2         | 1.47%   |
| 5.9.0-kali1-amd64        | 1         | 0.74%   |
| 5.8.18-xanmod1           | 1         | 0.74%   |
| 5.8.0-7630-generic       | 1         | 0.74%   |
| 5.8.0-57-generic         | 1         | 0.74%   |
| 5.8.0-48-generic         | 1         | 0.74%   |
| 5.8.0-45-generic         | 1         | 0.74%   |
| 5.8.0-44-generic         | 1         | 0.74%   |
| 5.8.0-43-generic         | 1         | 0.74%   |
| 5.8.0-26-generic         | 1         | 0.74%   |
| 5.8.0-25-generic         | 1         | 0.74%   |
| 5.8.0-14-generic         | 1         | 0.74%   |
| 5.7.9-1-MANJARO          | 1         | 0.74%   |
| 5.7.0-3-MANJARO          | 1         | 0.74%   |
| 5.6.4-152.current        | 1         | 0.74%   |
| 5.6.15-arch1-1           | 1         | 0.74%   |
| 5.6.14-955.native        | 1         | 0.74%   |
| 5.5.7-arch1-1            | 1         | 0.74%   |
| 5.4.123-116.lts2019      | 1         | 0.74%   |
| 5.4.12-200.fc31.x86_64   | 1         | 0.74%   |
| 5.4.0-92-generic         | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 14.62%  |
| 5.8.0   | 17        | 13.08%  |
| 5.11.0  | 15        | 11.54%  |
| 5.3.0   | 10        | 7.69%   |
| 4.15.0  | 9         | 6.92%   |
| 5.10.14 | 5         | 3.85%   |
| 5.0.0   | 4         | 3.08%   |
| 4.18.0  | 4         | 3.08%   |
| 5.16.7  | 3         | 2.31%   |
| 5.15.0  | 3         | 2.31%   |
| 5.10.0  | 3         | 2.31%   |
| 5.19.0  | 2         | 1.54%   |
| 5.13.0  | 2         | 1.54%   |
| 5.9.0   | 1         | 0.77%   |
| 5.8.18  | 1         | 0.77%   |
| 5.7.9   | 1         | 0.77%   |
| 5.7.0   | 1         | 0.77%   |
| 5.6.4   | 1         | 0.77%   |
| 5.6.15  | 1         | 0.77%   |
| 5.6.14  | 1         | 0.77%   |
| 5.5.7   | 1         | 0.77%   |
| 5.4.123 | 1         | 0.77%   |
| 5.4.12  | 1         | 0.77%   |
| 5.19.5  | 1         | 0.77%   |
| 5.19.1  | 1         | 0.77%   |
| 5.18.10 | 1         | 0.77%   |
| 5.18.0  | 1         | 0.77%   |
| 5.17.0  | 1         | 0.77%   |
| 5.16.5  | 1         | 0.77%   |
| 5.16.19 | 1         | 0.77%   |
| 5.16.16 | 1         | 0.77%   |
| 5.16.15 | 1         | 0.77%   |
| 5.15.6  | 1         | 0.77%   |
| 5.15.57 | 1         | 0.77%   |
| 5.15.5  | 1         | 0.77%   |
| 5.15.48 | 1         | 0.77%   |
| 5.15.11 | 1         | 0.77%   |
| 5.14.10 | 1         | 0.77%   |
| 5.13.19 | 1         | 0.77%   |
| 5.11.19 | 1         | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 16.41%  |
| 5.8     | 18        | 14.06%  |
| 5.11    | 17        | 13.28%  |
| 5.3     | 10        | 7.81%   |
| 5.10    | 9         | 7.03%   |
| 4.15    | 9         | 7.03%   |
| 5.16    | 7         | 5.47%   |
| 5.15    | 7         | 5.47%   |
| 4.18    | 5         | 3.91%   |
| 5.19    | 4         | 3.13%   |
| 5.0     | 4         | 3.13%   |
| 5.6     | 3         | 2.34%   |
| 5.13    | 3         | 2.34%   |
| 5.7     | 2         | 1.56%   |
| 5.18    | 2         | 1.56%   |
| 4.9     | 2         | 1.56%   |
| 5.9     | 1         | 0.78%   |
| 5.5     | 1         | 0.78%   |
| 5.17    | 1         | 0.78%   |
| 5.14    | 1         | 0.78%   |
| 4.13    | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 96.58%  |
| i686   | 4         | 3.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 68        | 55.28%  |
| KDE5       | 17        | 13.82%  |
| Unknown    | 15        | 12.2%   |
| XFCE       | 6         | 4.88%   |
| X-Cinnamon | 4         | 3.25%   |
| Cinnamon   | 3         | 2.44%   |
| KDE        | 2         | 1.63%   |
| Unity      | 1         | 0.81%   |
| trinity    | 1         | 0.81%   |
| Pantheon   | 1         | 0.81%   |
| openbox    | 1         | 0.81%   |
| MATE       | 1         | 0.81%   |
| KDE4       | 1         | 0.81%   |
| i3         | 1         | 0.81%   |
| Budgie     | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 92        | 77.97%  |
| Wayland | 13        | 11.02%  |
| Unknown | 10        | 8.47%   |
| Tty     | 3         | 2.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 68        | 57.14%  |
| SDDM    | 16        | 13.45%  |
| GDM     | 16        | 13.45%  |
| GDM3    | 10        | 8.4%    |
| TDM     | 4         | 3.36%   |
| LightDM | 4         | 3.36%   |
| KDM     | 1         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 85        | 70.83%  |
| Unknown | 13        | 10.83%  |
| ar_EG   | 7         | 5.83%   |
| en_GB   | 6         | 5%      |
| ar_SA   | 4         | 3.33%   |
| C       | 2         | 1.67%   |
| en_IN   | 1         | 0.83%   |
| Default | 1         | 0.83%   |
| ar_AE   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 61        | 51.69%  |
| EFI  | 57        | 48.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 96        | 80.67%  |
| Btrfs   | 7         | 5.88%   |
| Unknown | 6         | 5.04%   |
| Overlay | 5         | 4.2%    |
| Xfs     | 2         | 1.68%   |
| Zfs     | 1         | 0.84%   |
| Tmpfs   | 1         | 0.84%   |
| Ext2    | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 65.25%  |
| GPT     | 30        | 25.42%  |
| MBR     | 11        | 9.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 86.67%  |
| Yes       | 16        | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 74.58%  |
| Yes       | 30        | 25.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 24        | 20.51%  |
| Dell                        | 23        | 19.66%  |
| Lenovo                      | 17        | 14.53%  |
| Hewlett-Packard             | 17        | 14.53%  |
| Acer                        | 10        | 8.55%   |
| Toshiba                     | 5         | 4.27%   |
| Sony                        | 5         | 4.27%   |
| HUAWEI                      | 4         | 3.42%   |
| Notebook                    | 2         | 1.71%   |
| MSI                         | 2         | 1.71%   |
| Samsung Electronics         | 1         | 0.85%   |
| Packard Bell                | 1         | 0.85%   |
| LG Electronics              | 1         | 0.85%   |
| I-Life Digital Technologies | 1         | 0.85%   |
| GPD                         | 1         | 0.85%   |
| eMachines                   | 1         | 0.85%   |
| Clevo                       | 1         | 0.85%   |
| Apple                       | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 3.42%   |
| HP 15                                      | 3         | 2.56%   |
| Dell G3 3590                               | 3         | 2.56%   |
| HP Pavilion g6                             | 2         | 1.71%   |
| HP Notebook                                | 2         | 1.71%   |
| Dell Inspiron 3542                         | 2         | 1.71%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 1.71%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 1.71%   |
| Acer Aspire 4752                           | 2         | 1.71%   |
| Toshiba Satellite S55t-A                   | 1         | 0.85%   |
| Toshiba Satellite L500                     | 1         | 0.85%   |
| Toshiba Satellite C855D                    | 1         | 0.85%   |
| Toshiba Satellite C55-B                    | 1         | 0.85%   |
| Toshiba QOSMIO X875                        | 1         | 0.85%   |
| Sony VPCEA36FA                             | 1         | 0.85%   |
| Sony VPCCA35FA                             | 1         | 0.85%   |
| Sony VGN-FZ250E                            | 1         | 0.85%   |
| Sony SVF153290X                            | 1         | 0.85%   |
| Sony SVF14N13CXB                           | 1         | 0.85%   |
| Samsung 870Z5E/880Z5E/680Z5E               | 1         | 0.85%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.85%   |
| Notebook PD5x_7xPNP_PNN_PNT                | 1         | 0.85%   |
| Notebook NH5xAx                            | 1         | 0.85%   |
| MSI MS-1454                                | 1         | 0.85%   |
| MSI GF63 Thin 8RCS                         | 1         | 0.85%   |
| LG R490-G.ARL5RE2                          | 1         | 0.85%   |
| Lenovo V570 1066AJU                        | 1         | 0.85%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.85%   |
| Lenovo ThinkPad X230 2325OA3               | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003LAD   | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002JUS   | 1         | 0.85%   |
| Lenovo ThinkPad P52s 20LBS0JC00            | 1         | 0.85%   |
| Lenovo ThinkPad L14 Gen 2 20X10044EQ       | 1         | 0.85%   |
| Lenovo ThinkPad Edge 0301FFG               | 1         | 0.85%   |
| Lenovo ThinkPad E490 20N8000JAD            | 1         | 0.85%   |
| Lenovo ThinkPad E460 20ET000MAD            | 1         | 0.85%   |
| Lenovo ThinkPad E14 20RA008CAD             | 1         | 0.85%   |
| Lenovo ThinkBook 13s-IML 20RR              | 1         | 0.85%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 1         | 0.85%   |
| Lenovo IdeaPad 5 14IIL05 81YH              | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 10        | 8.55%   |
| Lenovo ThinkPad       | 9         | 7.69%   |
| ASUS VivoBook         | 9         | 7.69%   |
| Acer Aspire           | 7         | 5.98%   |
| HP Pavilion           | 5         | 4.27%   |
| HP Laptop             | 5         | 4.27%   |
| Toshiba Satellite     | 4         | 3.42%   |
| Dell Latitude         | 4         | 3.42%   |
| Lenovo IdeaPad        | 3         | 2.56%   |
| HP 15                 | 3         | 2.56%   |
| Dell Vostro           | 3         | 2.56%   |
| Dell G3               | 3         | 2.56%   |
| HP Notebook           | 2         | 1.71%   |
| Dell XPS              | 2         | 1.71%   |
| ASUS ROG              | 2         | 1.71%   |
| Toshiba QOSMIO        | 1         | 0.85%   |
| Sony VPCEA36FA        | 1         | 0.85%   |
| Sony VPCCA35FA        | 1         | 0.85%   |
| Sony VGN-FZ250E       | 1         | 0.85%   |
| Sony SVF153290X       | 1         | 0.85%   |
| Sony SVF14N13CXB      | 1         | 0.85%   |
| Samsung 870Z5E        | 1         | 0.85%   |
| Packard Bell EasyNote | 1         | 0.85%   |
| Notebook PD5x         | 1         | 0.85%   |
| Notebook NH5xAx       | 1         | 0.85%   |
| MSI MS-1454           | 1         | 0.85%   |
| MSI GF63              | 1         | 0.85%   |
| LG R490-G.ARL5RE2     | 1         | 0.85%   |
| Lenovo V570           | 1         | 0.85%   |
| Lenovo V15-IIL        | 1         | 0.85%   |
| Lenovo ThinkBook      | 1         | 0.85%   |
| Lenovo Flex           | 1         | 0.85%   |
| Lenovo B590           | 1         | 0.85%   |
| I-Life Digital ZED    | 1         | 0.85%   |
| HUAWEI RLEF-XX        | 1         | 0.85%   |
| HUAWEI MateBook       | 1         | 0.85%   |
| HUAWEI HN-WX9X        | 1         | 0.85%   |
| HUAWEI BOHB-WAX9      | 1         | 0.85%   |
| HP ProBook            | 1         | 0.85%   |
| HP EliteBook          | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 20        | 17.09%  |
| 2019 | 14        | 11.97%  |
| 2011 | 10        | 8.55%   |
| 2020 | 9         | 7.69%   |
| 2013 | 9         | 7.69%   |
| 2012 | 9         | 7.69%   |
| 2017 | 8         | 6.84%   |
| 2014 | 8         | 6.84%   |
| 2010 | 7         | 5.98%   |
| 2021 | 6         | 5.13%   |
| 2016 | 5         | 4.27%   |
| 2015 | 4         | 3.42%   |
| 2009 | 3         | 2.56%   |
| 2022 | 2         | 1.71%   |
| 2008 | 1         | 0.85%   |
| 2007 | 1         | 0.85%   |
| 2002 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 117       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 107       | 90.68%  |
| Enabled  | 11        | 9.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 39        | 32.77%  |
| 4.01-8.0    | 27        | 22.69%  |
| 16.01-24.0  | 20        | 16.81%  |
| 8.01-16.0   | 17        | 14.29%  |
| 32.01-64.0  | 6         | 5.04%   |
| 1.01-2.0    | 6         | 5.04%   |
| 2.01-3.0    | 3         | 2.52%   |
| 64.01-256.0 | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 50        | 39.06%  |
| 2.01-3.0  | 36        | 28.13%  |
| 3.01-4.0  | 18        | 14.06%  |
| 4.01-8.0  | 15        | 11.72%  |
| 0.51-1.0  | 7         | 5.47%   |
| 8.01-16.0 | 2         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 75.83%  |
| 2      | 22        | 18.33%  |
| 3      | 6         | 5%      |
| 0      | 1         | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 66        | 55.46%  |
| Yes       | 53        | 44.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 77.97%  |
| No        | 26        | 22.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 98.29%  |
| No        | 2         | 1.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 83.76%  |
| No        | 19        | 16.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 117       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Riyadh   | 44        | 36.36%  |
| Jeddah   | 34        | 28.1%   |
| Makkah   | 12        | 9.92%   |
| Medina   | 9         | 7.44%   |
| Dammam   | 6         | 4.96%   |
| Khobar   | 4         | 3.31%   |
| Thuwal   | 3         | 2.48%   |
| Dhahran  | 3         | 2.48%   |
| Al Qatif | 3         | 2.48%   |
| Ta'if    | 1         | 0.83%   |
| Al Hufuf | 1         | 0.83%   |
| Al Faruq | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 29        | 36     | 20.28%  |
| Toshiba                   | 22        | 28     | 15.38%  |
| WDC                       | 20        | 25     | 13.99%  |
| Samsung Electronics       | 15        | 19     | 10.49%  |
| Kingston                  | 11        | 12     | 7.69%   |
| SanDisk                   | 9         | 9      | 6.29%   |
| Unknown                   | 5         | 6      | 3.5%    |
| SK hynix                  | 4         | 5      | 2.8%    |
| Intel                     | 4         | 9      | 2.8%    |
| Micron/Crucial Technology | 2         | 2      | 1.4%    |
| KingSpec                  | 2         | 2      | 1.4%    |
| Hitachi                   | 2         | 2      | 1.4%    |
| Fujitsu                   | 2         | 2      | 1.4%    |
| Crucial                   | 2         | 3      | 1.4%    |
| YMTC                      | 1         | 1      | 0.7%    |
| XrayDisk                  | 1         | 1      | 0.7%    |
| SPCC                      | 1         | 1      | 0.7%    |
| Silicon Motion            | 1         | 1      | 0.7%    |
| OYUNKEY                   | 1         | 1      | 0.7%    |
| Micron Technology         | 1         | 1      | 0.7%    |
| Lexar                     | 1         | 1      | 0.7%    |
| KIOXIA                    | 1         | 1      | 0.7%    |
| JMicron Technology        | 1         | 1      | 0.7%    |
| Hewlett-Packard           | 1         | 1      | 0.7%    |
| G-DRIVE                   | 1         | 1      | 0.7%    |
| China                     | 1         | 1      | 0.7%    |
| Biostar                   | 1         | 1      | 0.7%    |
| A-DATA Technology         | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 12        | 8.11%   |
| Toshiba MQ04ABF100 1TB               | 8         | 5.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 2.7%    |
| Kingston SA400S37480G 480GB SSD      | 4         | 2.7%    |
| Toshiba MQ01ABD100 1TB               | 3         | 2.03%   |
| SanDisk NVMe SSD Drive 128GB         | 3         | 2.03%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.03%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 1.35%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.35%   |
| Toshiba MQ01ABD075 752GB             | 2         | 1.35%   |
| SK hynix NVMe SSD Drive 1024GB       | 2         | 1.35%   |
| Seagate ST9500325AS 500GB            | 2         | 1.35%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.35%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 1.35%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 1.35%   |
| Intel SSDPEKNW512G8 512GB            | 2         | 1.35%   |
| Intel NVMe SSD Drive 1024GB          | 2         | 1.35%   |
| YMTC PC005 256GB                     | 1         | 0.68%   |
| XrayDisk SSD 1TB                     | 1         | 0.68%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.68%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.68%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.68%   |
| WDC WD5000LPVX-08V0TT6 500GB         | 1         | 0.68%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 0.68%   |
| WDC WD5000BEVT-08A0RT1 500GB         | 1         | 0.68%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 0.68%   |
| WDC WD3200BEVT-00ZCT0 320GB          | 1         | 0.68%   |
| WDC WD1600BEVT-22ZCT0 160GB          | 1         | 0.68%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 0.68%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.68%   |
| WDC WD10SPZX-22Z10T0 1TB             | 1         | 0.68%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.68%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.68%   |
| WDC WD10JPVX-55JC3T3 1TB             | 1         | 0.68%   |
| WDC WD10JPVX-00JC3T0 1TB             | 1         | 0.68%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 1         | 0.68%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 1         | 0.68%   |
| Unknown SM32G  32GB                  | 1         | 0.68%   |
| Unknown SD64G  64GB                  | 1         | 0.68%   |
| Unknown MMC Card  64GB               | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 29        | 36     | 42.03%  |
| Toshiba | 21        | 23     | 30.43%  |
| WDC     | 15        | 19     | 21.74%  |
| Hitachi | 2         | 2      | 2.9%    |
| Fujitsu | 2         | 2      | 2.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 10     | 26.47%  |
| SanDisk             | 5         | 5      | 14.71%  |
| Samsung Electronics | 5         | 5      | 14.71%  |
| WDC                 | 2         | 2      | 5.88%   |
| SK hynix            | 2         | 3      | 5.88%   |
| KingSpec            | 2         | 2      | 5.88%   |
| Crucial             | 2         | 2      | 5.88%   |
| XrayDisk            | 1         | 1      | 2.94%   |
| OYUNKEY             | 1         | 1      | 2.94%   |
| Lexar               | 1         | 1      | 2.94%   |
| Hewlett-Packard     | 1         | 1      | 2.94%   |
| G-DRIVE             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| A-DATA Technology   | 1         | 1      | 2.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 67        | 82     | 47.86%  |
| SSD     | 34        | 36     | 24.29%  |
| NVMe    | 33        | 49     | 23.57%  |
| MMC     | 5         | 6      | 3.57%   |
| Unknown | 1         | 1      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 116    | 68.7%   |
| NVMe | 33        | 49     | 25.19%  |
| MMC  | 5         | 6      | 3.82%   |
| SAS  | 3         | 3      | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 48        | 59     | 48.98%  |
| 0.01-0.5   | 47        | 56     | 47.96%  |
| 1.01-2.0   | 3         | 3      | 3.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 32        | 26.23%  |
| 251-500        | 31        | 25.41%  |
| 101-250        | 25        | 20.49%  |
| 51-100         | 11        | 9.02%   |
| 1-20           | 7         | 5.74%   |
| 21-50          | 5         | 4.1%    |
| 1001-2000      | 4         | 3.28%   |
| More than 3000 | 3         | 2.46%   |
| 2001-3000      | 2         | 1.64%   |
| Unknown        | 2         | 1.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 52        | 40.63%  |
| 21-50     | 35        | 27.34%  |
| 51-100    | 15        | 11.72%  |
| 101-250   | 11        | 8.59%   |
| 251-500   | 9         | 7.03%   |
| 501-1000  | 3         | 2.34%   |
| Unknown   | 2         | 1.56%   |
| 1001-2000 | 1         | 0.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 20%     |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 20%     |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 20%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 20%     |
| OYUNKEY SSD 120GB                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| OYUNKEY | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 80        | 111    | 64%     |
| Works    | 40        | 58     | 32%     |
| Malfunc  | 5         | 5      | 4%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 95        | 70.37%  |
| Samsung Electronics              | 10        | 7.41%   |
| AMD                              | 8         | 5.93%   |
| SanDisk                          | 7         | 5.19%   |
| Micron/Crucial Technology        | 3         | 2.22%   |
| Toshiba America Info Systems     | 2         | 1.48%   |
| SK hynix                         | 2         | 1.48%   |
| Silicon Motion                   | 2         | 1.48%   |
| Kingston Technology Company      | 2         | 1.48%   |
| Yangtze Memory Technologies      | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |
| Realtek Semiconductor            | 1         | 0.74%   |
| Micron Technology                | 1         | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 15        | 10.56%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 10        | 7.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 10        | 7.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 8         | 5.63%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 8         | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 7         | 4.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 7         | 4.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 6         | 4.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 6         | 4.23%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 5         | 3.52%   |
| Samsung NVMe SSD Controller 980                                              | 4         | 2.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 4         | 2.82%   |
| SanDisk PC SN520 NVMe SSD                                                    | 3         | 2.11%   |
| Intel SSD 660P Series                                                        | 3         | 2.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 2         | 1.41%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 2         | 1.41%   |
| Micron/Crucial P1 NVMe PCIe SSD                                              | 2         | 1.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 2         | 1.41%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.41%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.41%   |
| Yangtze Memory Non-Volatile memory controller                                | 1         | 0.7%    |
| SK hynix PC300 NVMe Solid State Drive 1TB                                    | 1         | 0.7%    |
| SK hynix Gold P31 SSD                                                        | 1         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 0.7%    |
| Silicon Motion Non-Volatile memory controller                                | 1         | 0.7%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.7%    |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 0.7%    |
| Micron/Crucial Non-Volatile memory controller                                | 1         | 0.7%    |
| Micron Non-Volatile memory controller                                        | 1         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.7%    |
| Kingston Company Company Non-Volatile memory controller                      | 1         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 0.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 88        | 65.19%  |
| NVMe | 33        | 24.44%  |
| RAID | 8         | 5.93%   |
| IDE  | 6         | 4.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 89.74%  |
| AMD    | 12        | 10.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 5.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 3.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.56%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.56%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 2.56%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 2.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.71%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.71%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.71%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.71%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1.71%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.71%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.71%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.71%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 1.71%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.71%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.85%   |
| Intel Pentium CPU N3510 @ 1.99GHz             | 1         | 0.85%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.85%   |
| Intel Mobile Pentium 4 - M CPU 2.20GHz        | 1         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.85%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.85%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 1         | 0.85%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 35        | 29.91%  |
| Intel Core i5           | 34        | 29.06%  |
| Intel Celeron           | 11        | 9.4%    |
| Intel Core i3           | 10        | 8.55%   |
| AMD Ryzen 5             | 6         | 5.13%   |
| Other                   | 5         | 4.27%   |
| Intel Core 2 Duo        | 3         | 2.56%   |
| Intel Pentium Dual-Core | 2         | 1.71%   |
| Intel Pentium           | 2         | 1.71%   |
| Intel Atom              | 2         | 1.71%   |
| AMD Ryzen 9             | 2         | 1.71%   |
| AMD Ryzen 7             | 2         | 1.71%   |
| Intel Mobile Pentium 4  | 1         | 0.85%   |
| AMD E2                  | 1         | 0.85%   |
| AMD A12                 | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 57.26%  |
| 4      | 31        | 26.5%   |
| 6      | 9         | 7.69%   |
| 8      | 4         | 3.42%   |
| 1      | 4         | 3.42%   |
| 14     | 2         | 1.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 76.92%  |
| 1      | 26        | 22.22%  |
| 8      | 1         | 0.85%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 112       | 94.92%  |
| Unknown        | 4         | 3.39%   |
| 32-bit         | 2         | 1.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 25.2%   |
| 0x40651    | 11        | 8.94%   |
| 0x306a9    | 10        | 8.13%   |
| 0x206a7    | 8         | 6.5%    |
| 0x806ec    | 5         | 4.07%   |
| 0x806ea    | 5         | 4.07%   |
| 0x706a1    | 5         | 4.07%   |
| 0x406e3    | 5         | 4.07%   |
| 0x1067a    | 5         | 4.07%   |
| 0x806e9    | 4         | 3.25%   |
| 0x906ea    | 3         | 2.44%   |
| 0x806c1    | 3         | 2.44%   |
| 0x706e5    | 3         | 2.44%   |
| 0x20655    | 3         | 2.44%   |
| 0x20652    | 3         | 2.44%   |
| 0x906a3    | 2         | 1.63%   |
| 0x306d4    | 2         | 1.63%   |
| 0x30673    | 2         | 1.63%   |
| 0x08108109 | 2         | 1.63%   |
| 0xf27      | 1         | 0.81%   |
| 0xa0652    | 1         | 0.81%   |
| 0x906e9    | 1         | 0.81%   |
| 0x806eb    | 1         | 0.81%   |
| 0x6fa      | 1         | 0.81%   |
| 0x306c3    | 1         | 0.81%   |
| 0x08701013 | 1         | 0.81%   |
| 0x08600106 | 1         | 0.81%   |
| 0x08600104 | 1         | 0.81%   |
| 0x0810100b | 1         | 0.81%   |
| 0x0600611a | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 30        | 25.64%  |
| Haswell          | 12        | 10.26%  |
| IvyBridge        | 11        | 9.4%    |
| SandyBridge      | 8         | 6.84%   |
| Goldmont plus    | 8         | 6.84%   |
| Westmere         | 7         | 5.98%   |
| Skylake          | 7         | 5.98%   |
| Penryn           | 5         | 4.27%   |
| Zen+             | 3         | 2.56%   |
| Zen 3            | 3         | 2.56%   |
| Zen 2            | 3         | 2.56%   |
| TigerLake        | 3         | 2.56%   |
| IceLake          | 3         | 2.56%   |
| Silvermont       | 2         | 1.71%   |
| Broadwell        | 2         | 1.71%   |
| Alderlake Hybrid | 2         | 1.71%   |
| Zen              | 1         | 0.85%   |
| NetBurst         | 1         | 0.85%   |
| Goldmont         | 1         | 0.85%   |
| Excavator        | 1         | 0.85%   |
| Core             | 1         | 0.85%   |
| CometLake        | 1         | 0.85%   |
| Bonnell          | 1         | 0.85%   |
| Bobcat           | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 100       | 63.29%  |
| Nvidia                           | 33        | 20.89%  |
| AMD                              | 24        | 15.19%  |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 6.92%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 6.92%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 5.03%   |
| Intel UHD Graphics 620                                                        | 7         | 4.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 4.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 4.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 7         | 4.4%    |
| Intel HD Graphics 620                                                         | 6         | 3.77%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 3.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 2.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 2.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 4         | 2.52%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 2.52%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 1.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 1.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 3         | 1.89%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 3         | 1.89%   |
| AMD Cezanne                                                                   | 3         | 1.89%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 1.26%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 1.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.26%   |
| Intel HD Graphics 5500                                                        | 2         | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.26%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 1.26%   |
| AMD Renoir                                                                    | 2         | 1.26%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter     | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                        | 1         | 0.63%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                         | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.63%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                          | 1         | 0.63%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.63%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                  | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.63%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 52.54%  |
| Intel + Nvidia | 27        | 22.88%  |
| Intel + AMD    | 11        | 9.32%   |
| 1 x AMD        | 11        | 9.32%   |
| 1 x Nvidia     | 3         | 2.54%   |
| AMD + Nvidia   | 3         | 2.54%   |
| 1 x SiS        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 101       | 84.17%  |
| Proprietary | 18        | 15%     |
| Unknown     | 1         | 0.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 67.8%   |
| 1.01-2.0   | 17        | 14.41%  |
| 0.51-1.0   | 7         | 5.93%   |
| 3.01-4.0   | 6         | 5.08%   |
| 2.01-3.0   | 3         | 2.54%   |
| 0.01-0.5   | 3         | 2.54%   |
| 7.01-8.0   | 2         | 1.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 37        | 29.13%  |
| LG Display           | 23        | 18.11%  |
| AU Optronics         | 20        | 15.75%  |
| Chimei Innolux       | 14        | 11.02%  |
| Samsung Electronics  | 6         | 4.72%   |
| Lenovo               | 4         | 3.15%   |
| Dell                 | 4         | 3.15%   |
| Sharp                | 3         | 2.36%   |
| PANDA                | 3         | 2.36%   |
| Unknown              | 2         | 1.57%   |
| Sony                 | 2         | 1.57%   |
| ___                  | 1         | 0.79%   |
| ViewSonic            | 1         | 0.79%   |
| SKY                  | 1         | 0.79%   |
| InnoLux Display      | 1         | 0.79%   |
| InfoVision           | 1         | 0.79%   |
| Goldstar             | 1         | 0.79%   |
| ASUSTek Computer     | 1         | 0.79%   |
| Apple                | 1         | 0.79%   |
| Ancor Communications | 1         | 0.79%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 4         | 3.13%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                | 3         | 2.34%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 2.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 2.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 2         | 1.56%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch | 2         | 1.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 1.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.56%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 2         | 1.56%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                | 2         | 1.56%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 2         | 1.56%   |
| ___ TV ___9000 1360x768                                              | 1         | 0.78%   |
| ViewSonic VA712-2SERIES VSC941C 1280x1024 338x270mm 17.0-inch        | 1         | 0.78%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                 | 1         | 0.78%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.78%   |
| Sony TV SNYAC03 1360x768                                             | 1         | 0.78%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                | 1         | 0.78%   |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                   | 1         | 0.78%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch              | 1         | 0.78%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 0.78%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch | 1         | 0.78%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch              | 1         | 0.78%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 0.78%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch              | 1         | 0.78%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 1         | 0.78%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD05E8 1920x1080 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD04B6 1366x768 309x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD03FF 1920x1080 309x175mm 14.0-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 60        | 49.18%  |
| 1920x1080 (FHD)   | 46        | 37.7%   |
| 3840x2160 (4K)    | 4         | 3.28%   |
| 2560x1440 (QHD)   | 2         | 1.64%   |
| 1920x1200 (WUXGA) | 2         | 1.64%   |
| 1360x768          | 2         | 1.64%   |
| 3840x2400         | 1         | 0.82%   |
| 2160x1440         | 1         | 0.82%   |
| 1600x900 (HD+)    | 1         | 0.82%   |
| 1440x900 (WXGA+)  | 1         | 0.82%   |
| 1280x800 (WXGA)   | 1         | 0.82%   |
| 1280x1024 (SXGA)  | 1         | 0.82%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 71        | 55.47%  |
| 13      | 21        | 16.41%  |
| 14      | 15        | 11.72%  |
| 24      | 5         | 3.91%   |
| 17      | 3         | 2.34%   |
| 12      | 3         | 2.34%   |
| 72      | 2         | 1.56%   |
| 27      | 2         | 1.56%   |
| 54      | 1         | 0.78%   |
| 40      | 1         | 0.78%   |
| 31      | 1         | 0.78%   |
| 23      | 1         | 0.78%   |
| 16      | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 102       | 81.6%   |
| 201-300     | 7         | 5.6%    |
| 501-600     | 6         | 4.8%    |
| 351-400     | 4         | 3.2%    |
| 1501-2000   | 2         | 1.6%    |
| 801-900     | 1         | 0.8%    |
| 601-700     | 1         | 0.8%    |
| 1001-1500   | 1         | 0.8%    |
| Unknown     | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 107       | 94.69%  |
| 16/10 | 4         | 3.54%   |
| 5/4   | 1         | 0.88%   |
| 3/2   | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 54.69%  |
| 81-90          | 33        | 25.78%  |
| 201-250        | 4         | 3.13%   |
| More than 1000 | 3         | 2.34%   |
| 71-80          | 3         | 2.34%   |
| 61-70          | 3         | 2.34%   |
| 301-350        | 2         | 1.56%   |
| 251-300        | 2         | 1.56%   |
| 121-130        | 2         | 1.56%   |
| 351-500        | 1         | 0.78%   |
| 141-150        | 1         | 0.78%   |
| 111-120        | 1         | 0.78%   |
| 501-1000       | 1         | 0.78%   |
| 91-100         | 1         | 0.78%   |
| Unknown        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 59        | 47.58%  |
| 121-160       | 44        | 35.48%  |
| 51-100        | 11        | 8.87%   |
| More than 240 | 3         | 2.42%   |
| 1-50          | 3         | 2.42%   |
| 161-240       | 3         | 2.42%   |
| Unknown       | 1         | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 103       | 86.55%  |
| 2     | 10        | 8.4%    |
| 0     | 3         | 2.52%   |
| 3     | 2         | 1.68%   |
| 4     | 1         | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 76        | 40.43%  |
| Intel                            | 43        | 22.87%  |
| Qualcomm Atheros                 | 38        | 20.21%  |
| Broadcom                         | 11        | 5.85%   |
| Ralink                           | 4         | 2.13%   |
| Samsung Electronics              | 2         | 1.06%   |
| Ralink Technology                | 2         | 1.06%   |
| MediaTek                         | 2         | 1.06%   |
| Marvell Technology Group         | 2         | 1.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Qualcomm                         | 1         | 0.53%   |
| OPPO Electronics                 | 1         | 0.53%   |
| Microsoft                        | 1         | 0.53%   |
| ICS Advent                       | 1         | 0.53%   |
| Broadcom Limited                 | 1         | 0.53%   |
| ASIX Electronics                 | 1         | 0.53%   |
| Apple                            | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 18.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 10.5%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 5.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 4.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 3.65%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.28%   |
| Intel Wireless 8260                                               | 4         | 1.83%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.91%   |
| Intel Wireless 7265                                               | 2         | 0.91%   |
| Intel Wireless 7260                                               | 2         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.91%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller           | 1         | 0.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.46%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.46%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.46%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.46%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 0.46%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.46%   |
| Realtek 802.11ac NIC                                              | 1         | 0.46%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.46%   |
| Ralink RT2070 Wireless Adapter                                    | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 35%     |
| Qualcomm Atheros      | 34        | 28.33%  |
| Realtek Semiconductor | 27        | 22.5%   |
| Broadcom              | 7         | 5.83%   |
| Ralink                | 4         | 3.33%   |
| Ralink Technology     | 2         | 1.67%   |
| MediaTek              | 2         | 1.67%   |
| Qualcomm              | 1         | 0.83%   |
| Broadcom Limited      | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 10.83%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 8.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 6.67%   |
| Intel Wireless 8265 / 8275                                              | 6         | 5%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 4.17%   |
| Intel Wireless 8260                                                     | 4         | 3.33%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 3.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.5%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.67%   |
| Intel Wireless 7265                                                     | 2         | 1.67%   |
| Intel Wireless 7260                                                     | 2         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.83%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.83%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.83%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.83%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.83%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.83%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.83%   |
| Intel Wireless 3165                                                     | 1         | 0.83%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 65        | 66.33%  |
| Intel                            | 11        | 11.22%  |
| Qualcomm Atheros                 | 6         | 6.12%   |
| Broadcom                         | 6         | 6.12%   |
| Samsung Electronics              | 2         | 2.04%   |
| Marvell Technology Group         | 2         | 2.04%   |
| Silicon Integrated Systems [SiS] | 1         | 1.02%   |
| OPPO Electronics                 | 1         | 1.02%   |
| Microsoft                        | 1         | 1.02%   |
| ICS Advent                       | 1         | 1.02%   |
| ASIX Electronics                 | 1         | 1.02%   |
| Apple                            | 1         | 1.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 41.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 23.47%  |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 3.06%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.04%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.04%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.04%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.02%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.02%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.02%   |
| OPPO RMX2117                                                                   | 1         | 1.02%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.02%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.02%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.02%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.02%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.02%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.02%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.02%   |
| Apple iPad 4/Mini1                                                             | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 115       | 55.29%  |
| Ethernet | 92        | 44.23%  |
| Modem    | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 79.51%  |
| Ethernet | 25        | 20.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 74.36%  |
| 1     | 29        | 24.79%  |
| 0     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 97        | 82.2%   |
| Yes  | 21        | 17.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 32.32%  |
| Qualcomm Atheros Communications | 18        | 18.18%  |
| Realtek Semiconductor           | 13        | 13.13%  |
| Foxconn / Hon Hai               | 9         | 9.09%   |
| IMC Networks                    | 8         | 8.08%   |
| Lite-On Technology              | 5         | 5.05%   |
| Broadcom                        | 4         | 4.04%   |
| Ralink                          | 3         | 3.03%   |
| Toshiba                         | 2         | 2.02%   |
| Dell                            | 2         | 2.02%   |
| Realtek                         | 1         | 1.01%   |
| Qcom                            | 1         | 1.01%   |
| Apple                           | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 15.15%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 9.09%   |
| Realtek Bluetooth Radio                                                             | 7         | 7.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 7.07%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 5.05%   |
| IMC Networks Bluetooth Device                                                       | 5         | 5.05%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 3.03%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 3.03%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 3.03%   |
| Intel AX201 Bluetooth                                                               | 3         | 3.03%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.03%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.03%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.02%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 2.02%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 2.02%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 2.02%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 2.02%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.01%   |
| Toshiba Askey for                                                                   | 1         | 1.01%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 1.01%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.01%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.01%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 1.01%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 1.01%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 1.01%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.01%   |
| Lite-On BCM43142A0                                                                  | 1         | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.01%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.01%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 1.01%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.01%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.01%   |
| Broadcom Bluetooth                                                                  | 1         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.01%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.01%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.01%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 75.18%  |
| Nvidia                           | 17        | 12.41%  |
| AMD                              | 14        | 10.22%  |
| Silicon Integrated Systems [SiS] | 1         | 0.73%   |
| Samson Technologies              | 1         | 0.73%   |
| Cooler Master                    | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 12.96%  |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 6.79%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 6.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 6.79%   |
| AMD Family 17h/19h HD Audio Controller                                     | 9         | 5.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 4.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 4.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 4.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 4.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 3.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 3.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.09%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 1.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.85%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.23%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.23%   |
| Nvidia Audio device                                                        | 2         | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.23%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.23%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.23%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 0.62%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.62%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.62%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.62%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.62%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.62%   |
| Cooler Master MH752                                                        | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 17        | 26.15%  |
| SK hynix                             | 12        | 18.46%  |
| Micron Technology                    | 9         | 13.85%  |
| Crucial                              | 6         | 9.23%   |
| Unknown                              | 4         | 6.15%   |
| Kingston                             | 4         | 6.15%   |
| Elpida                               | 2         | 3.08%   |
| Unknown (ABCD)                       | 1         | 1.54%   |
| Toshiba                              | 1         | 1.54%   |
| Team                                 | 1         | 1.54%   |
| Silicon Power                        | 1         | 1.54%   |
| Ramaxel Technology                   | 1         | 1.54%   |
| Patriot Memory (PDP Systems)         | 1         | 1.54%   |
| Nanya Technology                     | 1         | 1.54%   |
| KLEVV                                | 1         | 1.54%   |
| Hikvision                            | 1         | 1.54%   |
| Chun Well Technology Holding Limited | 1         | 1.54%   |
| ASint Technology                     | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                    | 3         | 4.41%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s                   | 2         | 2.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 2         | 2.94%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 2         | 2.94%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s                    | 2         | 2.94%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                           | 1         | 1.47%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                      | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM DDR2                                       | 1         | 1.47%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                                    | 1         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                    | 1         | 1.47%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s         | 1         | 1.47%   |
| Toshiba RAM 8HTF12864HDY-800G1 1024MB SODIMM 1066MT/s                    | 1         | 1.47%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s                     | 1         | 1.47%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                             | 1         | 1.47%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s                    | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                | 1         | 1.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.47%   |
| SK hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s                 | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                   | 1         | 1.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                   | 1         | 1.47%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                  | 1         | 1.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                   | 1         | 1.47%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s                | 1         | 1.47%   |
| Silicon Power RAM DBST8GN128S 8GB SODIMM DDR3 1333MT/s                   | 1         | 1.47%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                    | 1         | 1.47%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s                 | 1         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| Samsung RAM M471B1G73CB0-CK0 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s              | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.47%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s                     | 1         | 1.47%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 1.47%   |
| Patriot Memory (PDP Systems) RAM PSD432G32002S 32GB SODIMM DDR4 3200MT/s | 1         | 1.47%   |
| Nanya RAM NT1GC64BH4B0PS-CG 1GB SODIMM DDR3 1333MT/s                     | 1         | 1.47%   |
| Micron RAM MT53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s            | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 24        | 46.15%  |
| DDR3    | 19        | 36.54%  |
| LPDDR4  | 3         | 5.77%   |
| DDR2    | 3         | 5.77%   |
| SDRAM   | 1         | 1.92%   |
| LPDDR3  | 1         | 1.92%   |
| Unknown | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 92.16%  |
| Row Of Chips | 4         | 7.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 36.84%  |
| 8192  | 20        | 35.09%  |
| 16384 | 7         | 12.28%  |
| 2048  | 7         | 12.28%  |
| 32768 | 1         | 1.75%   |
| 1024  | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 13        | 21.31%  |
| 1600    | 12        | 19.67%  |
| 3200    | 8         | 13.11%  |
| 1334    | 6         | 9.84%   |
| 2400    | 4         | 6.56%   |
| 3266    | 3         | 4.92%   |
| 2133    | 3         | 4.92%   |
| 1333    | 3         | 4.92%   |
| 4267    | 2         | 3.28%   |
| 800     | 2         | 3.28%   |
| 4199    | 1         | 1.64%   |
| 1067    | 1         | 1.64%   |
| 1066    | 1         | 1.64%   |
| 975     | 1         | 1.64%   |
| Unknown | 1         | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 21        | 20.59%  |
| IMC Networks                           | 19        | 18.63%  |
| Microdia                               | 12        | 11.76%  |
| Realtek Semiconductor                  | 9         | 8.82%   |
| Acer                                   | 7         | 6.86%   |
| Suyin                                  | 6         | 5.88%   |
| Lite-On Technology                     | 6         | 5.88%   |
| Sunplus Innovation Technology          | 5         | 4.9%    |
| Quanta                                 | 3         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.94%   |
| Ricoh                                  | 2         | 1.96%   |
| Importek                               | 2         | 1.96%   |
| Alcor Micro                            | 2         | 1.96%   |
| Silicon Motion                         | 1         | 0.98%   |
| Samsung Electronics                    | 1         | 0.98%   |
| Logitech                               | 1         | 0.98%   |
| Lenovo                                 | 1         | 0.98%   |
| Apple                                  | 1         | 0.98%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 11.76%  |
| Microdia Integrated_Webcam_HD                       | 7         | 6.86%   |
| Chicony Integrated Camera                           | 7         | 6.86%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 3.92%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.94%   |
| Lite-On HP TrueVision HD Camera                     | 3         | 2.94%   |
| Suyin 1.3M HD WebCam                                | 2         | 1.96%   |
| Sunplus HD WebCam                                   | 2         | 1.96%   |
| Realtek Integrated Webcam HD                        | 2         | 1.96%   |
| Realtek Integrated Webcam                           | 2         | 1.96%   |
| Realtek HP Truevision HD integrated webcam          | 2         | 1.96%   |
| Microdia HP Integrated Webcam                       | 2         | 1.96%   |
| Chicony HD WebCam                                   | 2         | 1.96%   |
| Alcor Micro Asus Integrated Webcam                  | 2         | 1.96%   |
| Acer Integrated Camera                              | 2         | 1.96%   |
| Suyin USB 2.0 Camera                                | 1         | 0.98%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.98%   |
| Suyin HP TrueVision HD                              | 1         | 0.98%   |
| Suyin HP Integrated Webcam                          | 1         | 0.98%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.98%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.98%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 1         | 0.98%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.98%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.98%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.98%   |
| Realtek HP Truevision HD                            | 1         | 0.98%   |
| Quanta LG Webcam                                    | 1         | 0.98%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.98%   |
| Quanta FHD Camera                                   | 1         | 0.98%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.98%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.98%   |
| Microdia Integrated Webcam                          | 1         | 0.98%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.98%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 0.98%   |
| Lite-On HP Webcam                                   | 1         | 0.98%   |
| Lite-On HP HD Camera                                | 1         | 0.98%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 0.98%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 0.98%   |
| Importek TOSHIBA Web Camera - FHD                   | 1         | 0.98%   |
| IMC Networks TOSHIBA Web Camera - HD                | 1         | 0.98%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 35.71%  |
| Upek                       | 2         | 14.29%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| LighTuning Technology      | 2         | 14.29%  |
| Elan Microelectronics      | 2         | 14.29%  |
| Validity Sensors           | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 14.29%  |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 7.14%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                            | 1         | 7.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                       | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 75%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 50%     |
| Broadcom 5880                                                                | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 84        | 70%     |
| 1     | 32        | 26.67%  |
| 2     | 2         | 1.67%   |
| 4     | 1         | 0.83%   |
| 3     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 35%     |
| Graphics card            | 8         | 20%     |
| Net/wireless             | 6         | 15%     |
| Chipcard                 | 4         | 10%     |
| Bluetooth                | 3         | 7.5%    |
| Multimedia controller    | 2         | 5%      |
| Modem                    | 1         | 2.5%    |
| Communication controller | 1         | 2.5%    |
| Camera                   | 1         | 2.5%    |

