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

Total: 192

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Acer          | Aspire V3-571               | [3d2d313cc3](https://linux-hardware.org/?probe=3d2d313cc3) | Mar 25, 2022 |
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
| HP            | EliteBook 8440p             | [6eab2c603a](https://linux-hardware.org/?probe=6eab2c603a) | Dec 19, 2021 |
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
| Dell          | Inspiron 3576               | [079007ce7c](https://linux-hardware.org/?probe=079007ce7c) | Jan 16, 2021 |
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
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [650cf712bb](https://linux-hardware.org/?probe=650cf712bb) | Nov 08, 2020 |
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
| Acer          | Swift SF314-52              | [0617efa99f](https://linux-hardware.org/?probe=0617efa99f) | Aug 31, 2020 |
| Acer          | Swift SF314-52              | [735949d5ba](https://linux-hardware.org/?probe=735949d5ba) | Aug 31, 2020 |
| Acer          | Swift SF314-52              | [b24d77b955](https://linux-hardware.org/?probe=b24d77b955) | Aug 30, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| HP            | Pavilion g6                 | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| Acer          | Swift SF314-52              | [c2959f9a32](https://linux-hardware.org/?probe=c2959f9a32) | Jul 09, 2020 |
| ASUSTek       | T100TA                      | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Acer          | Swift SF314-52              | [2720c7c291](https://linux-hardware.org/?probe=2720c7c291) | Jun 16, 2020 |
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
| HP            | 15                          | [fe612bef49](https://linux-hardware.org/?probe=fe612bef49) | Apr 06, 2020 |
| HP            | 15                          | [be4fd9280c](https://linux-hardware.org/?probe=be4fd9280c) | Apr 06, 2020 |
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
| HP            | Notebook                    | [4c3fdd0651](https://linux-hardware.org/?probe=4c3fdd0651) | Jan 29, 2020 |
| HP            | Notebook                    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | [99268d7e56](https://linux-hardware.org/?probe=99268d7e56) | Jan 02, 2020 |
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
| Ubuntu 20.04           | 23        | 19.83%  |
| Ubuntu 18.04           | 10        | 8.62%   |
| OpenMandriva 4.2       | 6         | 5.17%   |
| Fedora 35              | 5         | 4.31%   |
| Ubuntu 20.10           | 4         | 3.45%   |
| Zorin 16               | 3         | 2.59%   |
| Ubuntu 21.04           | 3         | 2.59%   |
| Pop!_OS 20.04          | 3         | 2.59%   |
| Endless 3.3.20-nexthw1 | 3         | 2.59%   |
| Debian Testing         | 3         | 2.59%   |
| Ubuntu 19.04           | 2         | 1.72%   |
| Pop!_OS 20.10          | 2         | 1.72%   |
| Manjaro 20.0.3         | 2         | 1.72%   |
| Linux Mint 20.1        | 2         | 1.72%   |
| Kubuntu 20.04          | 2         | 1.72%   |
| Kali 2021.2            | 2         | 1.72%   |
| Endless 3.7.8          | 2         | 1.72%   |
| Xubuntu 20.10          | 1         | 0.86%   |
| Xubuntu 20.04          | 1         | 0.86%   |
| Xubuntu 18.04          | 1         | 0.86%   |
| Ubuntu 19.10           | 1         | 0.86%   |
| Ubuntu 16.04           | 1         | 0.86%   |
| Solus 4.1              | 1         | 0.86%   |
| Solus 3.9999           | 1         | 0.86%   |
| ROSA R8.1              | 1         | 0.86%   |
| RHEL 8                 | 1         | 0.86%   |
| Q4OS 4                 | 1         | 0.86%   |
| Pop!_OS 22.04          | 1         | 0.86%   |
| Pop!_OS 21.10          | 1         | 0.86%   |
| Pop!_OS 21.04          | 1         | 0.86%   |
| Manjaro 21.2.6         | 1         | 0.86%   |
| Manjaro 21.2.5         | 1         | 0.86%   |
| Manjaro 21.2.0         | 1         | 0.86%   |
| Linux Mint 20          | 1         | 0.86%   |
| Linux Mint 19.1        | 1         | 0.86%   |
| LibertyOS              | 1         | 0.86%   |
| KDE neon 18.04         | 1         | 0.86%   |
| Kali 2020.4            | 1         | 0.86%   |
| Gentoo 2.7             | 1         | 0.86%   |
| Fedora 36              | 1         | 0.86%   |
| Fedora 34              | 1         | 0.86%   |
| Fedora 31              | 1         | 0.86%   |
| Endless 3.9.1          | 1         | 0.86%   |
| Endless 3.8.7          | 1         | 0.86%   |
| Endless 3.8.4          | 1         | 0.86%   |
| Endless 3.8.3          | 1         | 0.86%   |
| Endless 3.8.0          | 1         | 0.86%   |
| Endless 3.7.6          | 1         | 0.86%   |
| Endless 3.5.8          | 1         | 0.86%   |
| Endless 3.3.19-nexthw1 | 1         | 0.86%   |
| Endless 3.3.19         | 1         | 0.86%   |
| Elementary 5.1.7       | 1         | 0.86%   |
| Debian 9               | 1         | 0.86%   |
| Clear Linux 34820      | 1         | 0.86%   |
| Clear Linux 33190      | 1         | 0.86%   |
| Arch                   | 1         | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 44        | 40.37%  |
| Endless      | 13        | 11.93%  |
| Fedora       | 7         | 6.42%   |
| OpenMandriva | 6         | 5.5%    |
| Pop!_OS      | 5         | 4.59%   |
| Manjaro      | 4         | 3.67%   |
| Linux Mint   | 4         | 3.67%   |
| Debian       | 4         | 3.67%   |
| Zorin        | 3         | 2.75%   |
| Xubuntu      | 3         | 2.75%   |
| Kali         | 3         | 2.75%   |
| Kubuntu      | 2         | 1.83%   |
| Clear Linux  | 2         | 1.83%   |
| Solus        | 1         | 0.92%   |
| ROSA         | 1         | 0.92%   |
| RHEL         | 1         | 0.92%   |
| Q4OS         | 1         | 0.92%   |
| LibertyOS    | 1         | 0.92%   |
| KDE neon     | 1         | 0.92%   |
| Gentoo       | 1         | 0.92%   |
| Elementary   | 1         | 0.92%   |
| Arch         | 1         | 0.92%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002     | 5         | 4%      |
| 5.4.0-42-generic             | 4         | 3.2%    |
| 4.15.0-15-generic            | 4         | 3.2%    |
| 5.4.0-19-generic             | 3         | 2.4%    |
| 5.11.0-43-generic            | 3         | 2.4%    |
| 5.8.0-53-generic             | 2         | 1.6%    |
| 5.8.0-41-generic             | 2         | 1.6%    |
| 5.8.0-38-generic             | 2         | 1.6%    |
| 5.8.0-36-generic             | 2         | 1.6%    |
| 5.4.0-58-generic             | 2         | 1.6%    |
| 5.4.0-37-generic             | 2         | 1.6%    |
| 5.3.0-28-generic             | 2         | 1.6%    |
| 5.3.0-2-amd64                | 2         | 1.6%    |
| 5.11.0-41-generic            | 2         | 1.6%    |
| 5.11.0-40-generic            | 2         | 1.6%    |
| 5.11.0-37-generic            | 2         | 1.6%    |
| 5.11.0-31-generic            | 2         | 1.6%    |
| 5.0.0-20-generic             | 2         | 1.6%    |
| 4.15.0-29-generic            | 2         | 1.6%    |
| 5.9.0-kali1-amd64            | 1         | 0.8%    |
| 5.8.18-xanmod1               | 1         | 0.8%    |
| 5.8.0-7630-generic           | 1         | 0.8%    |
| 5.8.0-57-generic             | 1         | 0.8%    |
| 5.8.0-48-generic             | 1         | 0.8%    |
| 5.8.0-45-generic             | 1         | 0.8%    |
| 5.8.0-44-generic             | 1         | 0.8%    |
| 5.8.0-43-generic             | 1         | 0.8%    |
| 5.8.0-26-generic             | 1         | 0.8%    |
| 5.8.0-25-generic             | 1         | 0.8%    |
| 5.8.0-14-generic             | 1         | 0.8%    |
| 5.7.9-1-MANJARO              | 1         | 0.8%    |
| 5.7.0-3-MANJARO              | 1         | 0.8%    |
| 5.6.4-152.current            | 1         | 0.8%    |
| 5.6.15-arch1-1               | 1         | 0.8%    |
| 5.6.14-955.native            | 1         | 0.8%    |
| 5.5.7-arch1-1                | 1         | 0.8%    |
| 5.4.123-116.lts2019          | 1         | 0.8%    |
| 5.4.12-200.fc31.x86_64       | 1         | 0.8%    |
| 5.4.0-92-generic             | 1         | 0.8%    |
| 5.4.0-90-generic             | 1         | 0.8%    |
| 5.4.0-7642-generic           | 1         | 0.8%    |
| 5.4.0-72-generic             | 1         | 0.8%    |
| 5.4.0-52-generic             | 1         | 0.8%    |
| 5.4.0-51-generic             | 1         | 0.8%    |
| 5.4.0-48-generic             | 1         | 0.8%    |
| 5.4.0-47-generic             | 1         | 0.8%    |
| 5.4.0-40-generic             | 1         | 0.8%    |
| 5.4.0-31-generic             | 1         | 0.8%    |
| 5.4.0-105-generic            | 1         | 0.8%    |
| 5.3.0-51-generic             | 1         | 0.8%    |
| 5.3.0-46-generic             | 1         | 0.8%    |
| 5.3.0-45-generic             | 1         | 0.8%    |
| 5.3.0-40-generic             | 1         | 0.8%    |
| 5.3.0-24-generic             | 1         | 0.8%    |
| 5.3.0-23-generic             | 1         | 0.8%    |
| 5.17.0-0.rc7.116.fc36.x86_64 | 1         | 0.8%    |
| 5.16.5-200.fc35.x86_64       | 1         | 0.8%    |
| 5.16.19-76051619-generic     | 1         | 0.8%    |
| 5.16.16-200.fc35.x86_64      | 1         | 0.8%    |
| 5.16.15-76051615-generic     | 1         | 0.8%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 18        | 15.52%  |
| 5.8.0    | 17        | 14.66%  |
| 5.11.0   | 15        | 12.93%  |
| 5.3.0    | 10        | 8.62%   |
| 4.15.0   | 9         | 7.76%   |
| 5.10.14  | 5         | 4.31%   |
| 5.0.0    | 4         | 3.45%   |
| 4.18.0   | 4         | 3.45%   |
| 5.10.0   | 3         | 2.59%   |
| 5.13.0   | 2         | 1.72%   |
| 5.9.0    | 1         | 0.86%   |
| 5.8.18   | 1         | 0.86%   |
| 5.7.9    | 1         | 0.86%   |
| 5.7.0    | 1         | 0.86%   |
| 5.6.4    | 1         | 0.86%   |
| 5.6.15   | 1         | 0.86%   |
| 5.6.14   | 1         | 0.86%   |
| 5.5.7    | 1         | 0.86%   |
| 5.4.123  | 1         | 0.86%   |
| 5.4.12   | 1         | 0.86%   |
| 5.17.0   | 1         | 0.86%   |
| 5.16.5   | 1         | 0.86%   |
| 5.16.19  | 1         | 0.86%   |
| 5.16.16  | 1         | 0.86%   |
| 5.16.15  | 1         | 0.86%   |
| 5.15.6   | 1         | 0.86%   |
| 5.15.5   | 1         | 0.86%   |
| 5.15.11  | 1         | 0.86%   |
| 5.15.0   | 1         | 0.86%   |
| 5.14.10  | 1         | 0.86%   |
| 5.13.19  | 1         | 0.86%   |
| 5.11.19  | 1         | 0.86%   |
| 5.11.12  | 1         | 0.86%   |
| 5.10.109 | 1         | 0.86%   |
| 5.10.105 | 1         | 0.86%   |
| 4.9.9    | 1         | 0.86%   |
| 4.9.0    | 1         | 0.86%   |
| 4.18.16  | 1         | 0.86%   |
| 4.13.0   | 1         | 0.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 17.54%  |
| 5.8     | 18        | 15.79%  |
| 5.11    | 17        | 14.91%  |
| 5.3     | 10        | 8.77%   |
| 5.10    | 9         | 7.89%   |
| 4.15    | 9         | 7.89%   |
| 4.18    | 5         | 4.39%   |
| 5.16    | 4         | 3.51%   |
| 5.0     | 4         | 3.51%   |
| 5.6     | 3         | 2.63%   |
| 5.15    | 3         | 2.63%   |
| 5.13    | 3         | 2.63%   |
| 5.7     | 2         | 1.75%   |
| 4.9     | 2         | 1.75%   |
| 5.9     | 1         | 0.88%   |
| 5.5     | 1         | 0.88%   |
| 5.17    | 1         | 0.88%   |
| 5.14    | 1         | 0.88%   |
| 4.13    | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 96.15%  |
| i686   | 4         | 3.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 65        | 59.63%  |
| Unknown    | 14        | 12.84%  |
| KDE5       | 10        | 9.17%   |
| XFCE       | 5         | 4.59%   |
| X-Cinnamon | 4         | 3.67%   |
| KDE        | 2         | 1.83%   |
| Cinnamon   | 2         | 1.83%   |
| Unity      | 1         | 0.92%   |
| trinity    | 1         | 0.92%   |
| Pantheon   | 1         | 0.92%   |
| openbox    | 1         | 0.92%   |
| KDE4       | 1         | 0.92%   |
| i3         | 1         | 0.92%   |
| Budgie     | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 82        | 78.1%   |
| Wayland | 11        | 10.48%  |
| Unknown | 10        | 9.52%   |
| Tty     | 2         | 1.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 66        | 62.26%  |
| GDM     | 16        | 15.09%  |
| SDDM    | 10        | 9.43%   |
| GDM3    | 7         | 6.6%    |
| TDM     | 3         | 2.83%   |
| LightDM | 3         | 2.83%   |
| KDM     | 1         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 77        | 72.64%  |
| Unknown | 13        | 12.26%  |
| ar_EG   | 7         | 6.6%    |
| ar_SA   | 4         | 3.77%   |
| en_GB   | 2         | 1.89%   |
| C       | 2         | 1.89%   |
| ar_AE   | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 55        | 52.38%  |
| EFI  | 50        | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 87        | 82.08%  |
| Unknown | 6         | 5.66%   |
| Overlay | 4         | 3.77%   |
| Btrfs   | 4         | 3.77%   |
| Xfs     | 2         | 1.89%   |
| Zfs     | 1         | 0.94%   |
| Tmpfs   | 1         | 0.94%   |
| Ext2    | 1         | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 75        | 71.43%  |
| GPT     | 24        | 22.86%  |
| MBR     | 6         | 5.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 86.92%  |
| Yes       | 14        | 13.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 74.29%  |
| Yes       | 27        | 25.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 24        | 23.08%  |
| Dell                        | 21        | 20.19%  |
| Hewlett-Packard             | 17        | 16.35%  |
| Lenovo                      | 14        | 13.46%  |
| Acer                        | 9         | 8.65%   |
| Toshiba                     | 5         | 4.81%   |
| Sony                        | 5         | 4.81%   |
| HUAWEI                      | 2         | 1.92%   |
| Samsung Electronics         | 1         | 0.96%   |
| Packard Bell                | 1         | 0.96%   |
| MSI                         | 1         | 0.96%   |
| LG Electronics              | 1         | 0.96%   |
| I-Life Digital Technologies | 1         | 0.96%   |
| GPD                         | 1         | 0.96%   |
| Apple                       | 1         | 0.96%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 3.85%   |
| HP 15                                      | 3         | 2.88%   |
| Dell G3 3590                               | 3         | 2.88%   |
| HP Pavilion g6                             | 2         | 1.92%   |
| HP Notebook                                | 2         | 1.92%   |
| Dell Inspiron 3542                         | 2         | 1.92%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 1.92%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 1.92%   |
| Toshiba Satellite S55t-A                   | 1         | 0.96%   |
| Toshiba Satellite L500                     | 1         | 0.96%   |
| Toshiba Satellite C855D                    | 1         | 0.96%   |
| Toshiba Satellite C55-B                    | 1         | 0.96%   |
| Toshiba QOSMIO X875                        | 1         | 0.96%   |
| Sony VPCEA36FA                             | 1         | 0.96%   |
| Sony VPCCA35FA                             | 1         | 0.96%   |
| Sony VGN-FZ250E                            | 1         | 0.96%   |
| Sony SVF153290X                            | 1         | 0.96%   |
| Sony SVF14N13CXB                           | 1         | 0.96%   |
| Samsung 870Z5E/880Z5E/680Z5E               | 1         | 0.96%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.96%   |
| MSI MS-1454                                | 1         | 0.96%   |
| LG R490-G.ARL5RE2                          | 1         | 0.96%   |
| Lenovo V570 1066AJU                        | 1         | 0.96%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.96%   |
| Lenovo ThinkPad X230 2325OA3               | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003LAD   | 1         | 0.96%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002JUS   | 1         | 0.96%   |
| Lenovo ThinkPad P52s 20LBS0JC00            | 1         | 0.96%   |
| Lenovo ThinkPad L14 Gen 2 20X10044EQ       | 1         | 0.96%   |
| Lenovo ThinkPad Edge 0301FFG               | 1         | 0.96%   |
| Lenovo ThinkPad E490 20N8000JAD            | 1         | 0.96%   |
| Lenovo ThinkPad E460 20ET000MAD            | 1         | 0.96%   |
| Lenovo ThinkPad E14 20RA008CAD             | 1         | 0.96%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 1         | 0.96%   |
| Lenovo IdeaPad 5 14IIL05 81YH              | 1         | 0.96%   |
| Lenovo Flex 2-15 20405                     | 1         | 0.96%   |
| I-Life Digital ZED Air Plus                | 1         | 0.96%   |
| HUAWEI MateBook D                          | 1         | 0.96%   |
| HUAWEI HN-WX9X                             | 1         | 0.96%   |
| HP ProBook 445 G7                          | 1         | 0.96%   |
| HP Pavilion Laptop 15t-eg000               | 1         | 0.96%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 1         | 0.96%   |
| HP Pavilion dv6                            | 1         | 0.96%   |
| HP Laptop 15-db0xxx                        | 1         | 0.96%   |
| HP Laptop 15-da2xxx                        | 1         | 0.96%   |
| HP Laptop 15-da0xxx                        | 1         | 0.96%   |
| HP Laptop 15-bs1xx                         | 1         | 0.96%   |
| HP Laptop 14-ck0xxx                        | 1         | 0.96%   |
| HP EliteBook 8440p                         | 1         | 0.96%   |
| GPD MicroPC                                | 1         | 0.96%   |
| Dell XPS 15 9560                           | 1         | 0.96%   |
| Dell XPS 13 9310                           | 1         | 0.96%   |
| Dell Vostro 5470                           | 1         | 0.96%   |
| Dell Vostro 1440                           | 1         | 0.96%   |
| Dell Latitude E7470                        | 1         | 0.96%   |
| Dell Latitude E7440                        | 1         | 0.96%   |
| Dell Latitude E5470                        | 1         | 0.96%   |
| Dell Latitude E4310                        | 1         | 0.96%   |
| Dell Inspiron N5110                        | 1         | 0.96%   |
| Dell Inspiron N5030                        | 1         | 0.96%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 10        | 9.62%   |
| Lenovo ThinkPad       | 9         | 8.65%   |
| ASUS VivoBook         | 9         | 8.65%   |
| Acer Aspire           | 6         | 5.77%   |
| HP Pavilion           | 5         | 4.81%   |
| HP Laptop             | 5         | 4.81%   |
| Toshiba Satellite     | 4         | 3.85%   |
| Dell Latitude         | 4         | 3.85%   |
| HP 15                 | 3         | 2.88%   |
| Dell G3               | 3         | 2.88%   |
| Lenovo IdeaPad        | 2         | 1.92%   |
| HP Notebook           | 2         | 1.92%   |
| Dell XPS              | 2         | 1.92%   |
| Dell Vostro           | 2         | 1.92%   |
| ASUS ROG              | 2         | 1.92%   |
| Toshiba QOSMIO        | 1         | 0.96%   |
| Sony VPCEA36FA        | 1         | 0.96%   |
| Sony VPCCA35FA        | 1         | 0.96%   |
| Sony VGN-FZ250E       | 1         | 0.96%   |
| Sony SVF153290X       | 1         | 0.96%   |
| Sony SVF14N13CXB      | 1         | 0.96%   |
| Samsung 870Z5E        | 1         | 0.96%   |
| Packard Bell EasyNote | 1         | 0.96%   |
| MSI MS-1454           | 1         | 0.96%   |
| LG R490-G.ARL5RE2     | 1         | 0.96%   |
| Lenovo V570           | 1         | 0.96%   |
| Lenovo V15-IIL        | 1         | 0.96%   |
| Lenovo Flex           | 1         | 0.96%   |
| I-Life Digital ZED    | 1         | 0.96%   |
| HUAWEI MateBook       | 1         | 0.96%   |
| HUAWEI HN-WX9X        | 1         | 0.96%   |
| HP ProBook            | 1         | 0.96%   |
| HP EliteBook          | 1         | 0.96%   |
| GPD MicroPC           | 1         | 0.96%   |
| ASUS ZenBook          | 1         | 0.96%   |
| ASUS X555UB           | 1         | 0.96%   |
| ASUS X555QA           | 1         | 0.96%   |
| ASUS X555LDB          | 1         | 0.96%   |
| ASUS X540UA           | 1         | 0.96%   |
| ASUS X540NA           | 1         | 0.96%   |
| ASUS UX390UAK         | 1         | 0.96%   |
| ASUS TUF              | 1         | 0.96%   |
| ASUS T100TA           | 1         | 0.96%   |
| ASUS L4000H           | 1         | 0.96%   |
| ASUS K53SC            | 1         | 0.96%   |
| ASUS K43SJ            | 1         | 0.96%   |
| ASUS GL502VMK         | 1         | 0.96%   |
| Apple MacBookPro9     | 1         | 0.96%   |
| Acer Swift            | 1         | 0.96%   |
| Acer Nitro            | 1         | 0.96%   |
| Acer AO751h           | 1         | 0.96%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 19        | 18.27%  |
| 2019 | 13        | 12.5%   |
| 2014 | 10        | 9.62%   |
| 2017 | 8         | 7.69%   |
| 2011 | 8         | 7.69%   |
| 2020 | 7         | 6.73%   |
| 2013 | 7         | 6.73%   |
| 2012 | 7         | 6.73%   |
| 2010 | 7         | 6.73%   |
| 2016 | 5         | 4.81%   |
| 2015 | 4         | 3.85%   |
| 2021 | 3         | 2.88%   |
| 2009 | 3         | 2.88%   |
| 2008 | 1         | 0.96%   |
| 2007 | 1         | 0.96%   |
| 2002 | 1         | 0.96%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 104       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 95        | 90.48%  |
| Enabled  | 10        | 9.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 104       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 36        | 33.96%  |
| 4.01-8.0   | 23        | 21.7%   |
| 16.01-24.0 | 16        | 15.09%  |
| 8.01-16.0  | 16        | 15.09%  |
| 32.01-64.0 | 6         | 5.66%   |
| 1.01-2.0   | 6         | 5.66%   |
| 2.01-3.0   | 3         | 2.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 45        | 39.47%  |
| 2.01-3.0  | 31        | 27.19%  |
| 3.01-4.0  | 16        | 14.04%  |
| 4.01-8.0  | 13        | 11.4%   |
| 0.51-1.0  | 7         | 6.14%   |
| 8.01-16.0 | 2         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 82        | 77.36%  |
| 2      | 19        | 17.92%  |
| 3      | 4         | 3.77%   |
| 0      | 1         | 0.94%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 53.77%  |
| Yes       | 49        | 46.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 78.1%   |
| No        | 23        | 21.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 98.08%  |
| No        | 2         | 1.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 83.65%  |
| No        | 17        | 16.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 104       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City     | Notebooks | Percent |
|----------|-----------|---------|
| Riyadh   | 43        | 39.09%  |
| Jeddah   | 34        | 30.91%  |
| Medina   | 7         | 6.36%   |
| Dammam   | 6         | 5.45%   |
| Thuwal   | 3         | 2.73%   |
| Khobar   | 3         | 2.73%   |
| Dhahran  | 3         | 2.73%   |
| Tabuk    | 2         | 1.82%   |
| Makkah   | 2         | 1.82%   |
| Buraidah | 2         | 1.82%   |
| Ta'if    | 1         | 0.91%   |
| Jubail   | 1         | 0.91%   |
| Ha'il    | 1         | 0.91%   |
| Al Qatif | 1         | 0.91%   |
| Al Faruq | 1         | 0.91%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 28        | 36     | 22.4%   |
| WDC                       | 20        | 25     | 16%     |
| Toshiba                   | 20        | 26     | 16%     |
| Samsung Electronics       | 11        | 13     | 8.8%    |
| Kingston                  | 10        | 11     | 8%      |
| SanDisk                   | 8         | 8      | 6.4%    |
| Unknown                   | 4         | 5      | 3.2%    |
| SK Hynix                  | 4         | 7      | 3.2%    |
| Intel                     | 4         | 9      | 3.2%    |
| Micron/Crucial Technology | 2         | 2      | 1.6%    |
| KingSpec                  | 2         | 2      | 1.6%    |
| Hitachi                   | 2         | 2      | 1.6%    |
| Fujitsu                   | 2         | 2      | 1.6%    |
| SPCC                      | 1         | 1      | 0.8%    |
| oyunkey                   | 1         | 1      | 0.8%    |
| Lexar                     | 1         | 1      | 0.8%    |
| KIOXIA                    | 1         | 1      | 0.8%    |
| JMicron                   | 1         | 1      | 0.8%    |
| Hewlett-Packard           | 1         | 1      | 0.8%    |
| China                     | 1         | 1      | 0.8%    |
| A-DATA Technology         | 1         | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 12        | 9.38%   |
| Toshiba MQ04ABF100 1TB                | 7         | 5.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 3.13%   |
| Kingston SA400S37480G 480GB SSD       | 4         | 3.13%   |
| Sandisk NVMe SSD Drive 128GB          | 3         | 2.34%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 2.34%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 1.56%   |
| Toshiba MQ01ABF050 500GB              | 2         | 1.56%   |
| Toshiba MQ01ABD100 1TB                | 2         | 1.56%   |
| Toshiba MQ01ABD075 752GB              | 2         | 1.56%   |
| SK Hynix NVMe SSD Drive 1024GB        | 2         | 1.56%   |
| Seagate ST9500325AS 500GB             | 2         | 1.56%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 1.56%   |
| Samsung NVMe SSD Drive 1024GB         | 2         | 1.56%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 1.56%   |
| Intel SSDPEKNW512G8 512GB             | 2         | 1.56%   |
| Intel NVMe SSD Drive 1024GB           | 2         | 1.56%   |
| WDC WDS500G2B0B-00YS70 500GB SSD      | 1         | 0.78%   |
| WDC WDS500G2B0A-00SM50 500GB SSD      | 1         | 0.78%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1         | 0.78%   |
| WDC WD5000LPVX-08V0TT6 500GB          | 1         | 0.78%   |
| WDC WD5000LPCX-00VHAT0 500GB          | 1         | 0.78%   |
| WDC WD5000BEVT-08A0RT1 500GB          | 1         | 0.78%   |
| WDC WD3200BPVT-75ZEST0 320GB          | 1         | 0.78%   |
| WDC WD3200BEVT-00ZCT0 320GB           | 1         | 0.78%   |
| WDC WD1600BEVT-22ZCT0 160GB           | 1         | 0.78%   |
| WDC WD10SPZX-75Z10T2 1TB              | 1         | 0.78%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.78%   |
| WDC WD10SPZX-22Z10T0 1TB              | 1         | 0.78%   |
| WDC WD10SPZX-08Z10 1TB                | 1         | 0.78%   |
| WDC WD10SPZX-00Z10T0 1TB              | 1         | 0.78%   |
| WDC WD10JPVX-55JC3T3 1TB              | 1         | 0.78%   |
| WDC WD10JPVX-00JC3T0 1TB              | 1         | 0.78%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB  | 1         | 0.78%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB  | 1         | 0.78%   |
| Unknown SM32G  32GB                   | 1         | 0.78%   |
| Unknown SD64G  64GB                   | 1         | 0.78%   |
| Unknown MMC Card  64GB                | 1         | 0.78%   |
| Unknown MMC Card  16GB                | 1         | 0.78%   |
| Toshiba NVMe SSD Drive 512GB          | 1         | 0.78%   |
| Toshiba MQ01ABD050 500GB              | 1         | 0.78%   |
| Toshiba MK7559GSXF 752GB              | 1         | 0.78%   |
| Toshiba MK5075GSX 500GB               | 1         | 0.78%   |
| Toshiba MK5061GSYN 500GB              | 1         | 0.78%   |
| Toshiba MK3265GSX 320GB               | 1         | 0.78%   |
| Toshiba MK1234GAX 120GB               | 1         | 0.78%   |
| Toshiba KXG6AZNV512G 512GB            | 1         | 0.78%   |
| SPCC M.2 PCIe SSD 256GB               | 1         | 0.78%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD | 1         | 0.78%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 0.78%   |
| Seagate ST9320423AS 320GB             | 1         | 0.78%   |
| Seagate ST9160418ASG 160GB            | 1         | 0.78%   |
| Seagate ST500LM030-1RK17D 500GB       | 1         | 0.78%   |
| Seagate ST500LM000-SSHD-8GB           | 1         | 0.78%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 0.78%   |
| Seagate ST2000LM015-2E8174 2TB        | 1         | 0.78%   |
| Seagate ST2000LM007-1R8174 2TB        | 1         | 0.78%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 0.78%   |
| SanDisk X110 MSATA 256GB SSD          | 1         | 0.78%   |
| SanDisk SSD PLUS 120GB                | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 36     | 42.42%  |
| Toshiba | 19        | 21     | 28.79%  |
| WDC     | 15        | 19     | 22.73%  |
| Hitachi | 2         | 2      | 3.03%   |
| Fujitsu | 2         | 2      | 3.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 10     | 32.14%  |
| SanDisk             | 4         | 4      | 14.29%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| WDC                 | 2         | 2      | 7.14%   |
| SK Hynix            | 2         | 5      | 7.14%   |
| KingSpec            | 2         | 2      | 7.14%   |
| oyunkey             | 1         | 1      | 3.57%   |
| Lexar               | 1         | 1      | 3.57%   |
| Hewlett-Packard     | 1         | 1      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 80     | 52.46%  |
| SSD     | 28        | 32     | 22.95%  |
| NVMe    | 25        | 38     | 20.49%  |
| MMC     | 4         | 5      | 3.28%   |
| Unknown | 1         | 1      | 0.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 83        | 112    | 73.45%  |
| NVMe | 25        | 38     | 22.12%  |
| MMC  | 4         | 5      | 3.54%   |
| SAS  | 1         | 1      | 0.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 44        | 56     | 49.44%  |
| 0.51-1.0   | 42        | 53     | 47.19%  |
| 1.01-2.0   | 3         | 3      | 3.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 30        | 27.52%  |
| 251-500        | 28        | 25.69%  |
| 101-250        | 23        | 21.1%   |
| 51-100         | 11        | 10.09%  |
| 1-20           | 6         | 5.5%    |
| 1001-2000      | 4         | 3.67%   |
| 21-50          | 3         | 2.75%   |
| Unknown        | 2         | 1.83%   |
| More than 3000 | 1         | 0.92%   |
| 2001-3000      | 1         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 44        | 38.6%   |
| 21-50    | 32        | 28.07%  |
| 51-100   | 15        | 13.16%  |
| 251-500  | 9         | 7.89%   |
| 101-250  | 9         | 7.89%   |
| 501-1000 | 3         | 2.63%   |
| Unknown  | 2         | 1.75%   |

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
| oyunkey SSD 120GB                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 40%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |
| oyunkey | 1         | 1      | 20%     |

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
| Detected | 76        | 108    | 69.09%  |
| Works    | 29        | 43     | 26.36%  |
| Malfunc  | 5         | 5      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 88        | 75.21%  |
| Sandisk                          | 7         | 5.98%   |
| Samsung Electronics              | 7         | 5.98%   |
| AMD                              | 6         | 5.13%   |
| Toshiba America Info Systems     | 2         | 1.71%   |
| SK Hynix                         | 2         | 1.71%   |
| Micron/Crucial Technology        | 2         | 1.71%   |
| Silicon Integrated Systems [SiS] | 1         | 0.85%   |
| Realtek Semiconductor            | 1         | 0.85%   |
| Kingston Technology Company      | 1         | 0.85%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 14        | 11.48%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 8.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 6.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 8         | 6.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 7         | 5.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 6         | 4.92%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 6         | 4.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 4.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 4         | 3.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 4         | 3.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 3.28%   |
| Sandisk PC SN520 NVMe SSD                                                              | 3         | 2.46%   |
| Intel SSD 660P Series                                                                  | 3         | 2.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1.64%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 1.64%   |
| Samsung NVMe SSD Controller 980                                                        | 2         | 1.64%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 2         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 2         | 1.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 1.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 1.64%   |
| SK Hynix PC300 NVMe Solid State Drive 1TB                                              | 1         | 0.82%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 0.82%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 1         | 0.82%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.82%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 1         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.82%   |
| Realtek Realtek Non-Volatile memory controller                                         | 1         | 0.82%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.82%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 1         | 0.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 1         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 1         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 1         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 1         | 0.82%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.82%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 79        | 66.95%  |
| NVMe | 25        | 21.19%  |
| RAID | 8         | 6.78%   |
| IDE  | 6         | 5.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 95        | 91.35%  |
| AMD    | 9         | 8.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 6.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 3.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.88%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 2.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 2.88%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 2.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.92%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.92%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.92%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.92%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 1.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.92%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.96%   |
| Intel Pentium CPU N3510 @ 1.99GHz             | 1         | 0.96%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.96%   |
| Intel Mobile Pentium 4 - M CPU 2.20GHz        | 1         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.96%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.96%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.96%   |
| Intel Core i7-3635QM CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.96%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 1         | 0.96%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.96%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.96%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.96%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.96%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1         | 0.96%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 1         | 0.96%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.96%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 0.96%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 1         | 0.96%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 0.96%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 0.96%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 1         | 0.96%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 0.96%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 0.96%   |
| Intel Celeron CPU 925 @ 2.30GHz               | 1         | 0.96%   |
| Intel Atom CPU Z520 @ 1.33GHz                 | 1         | 0.96%   |
| Intel Atom CPU Z3740 @ 1.33GHz                | 1         | 0.96%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 31.73%  |
| Intel Core i7           | 31        | 29.81%  |
| Intel Celeron           | 10        | 9.62%   |
| Intel Core i3           | 9         | 8.65%   |
| AMD Ryzen 5             | 5         | 4.81%   |
| Other                   | 3         | 2.88%   |
| Intel Core 2 Duo        | 3         | 2.88%   |
| Intel Pentium           | 2         | 1.92%   |
| Intel Atom              | 2         | 1.92%   |
| AMD Ryzen 9             | 2         | 1.92%   |
| Intel Pentium Dual-Core | 1         | 0.96%   |
| Intel Mobile Pentium 4  | 1         | 0.96%   |
| AMD E2                  | 1         | 0.96%   |
| AMD A12                 | 1         | 0.96%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 60.58%  |
| 4      | 28        | 26.92%  |
| 6      | 8         | 7.69%   |
| 1      | 3         | 2.88%   |
| 8      | 2         | 1.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 82        | 78.85%  |
| 1      | 22        | 21.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 99        | 94.29%  |
| Unknown        | 4         | 3.81%   |
| 32-bit         | 2         | 1.9%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 25.45%  |
| 0x40651    | 11        | 10%     |
| 0x306a9    | 8         | 7.27%   |
| 0x206a7    | 7         | 6.36%   |
| 0x806ea    | 5         | 4.55%   |
| 0x706a1    | 5         | 4.55%   |
| 0x406e3    | 5         | 4.55%   |
| 0x806ec    | 4         | 3.64%   |
| 0x806e9    | 4         | 3.64%   |
| 0x1067a    | 4         | 3.64%   |
| 0x806c1    | 3         | 2.73%   |
| 0x706e5    | 3         | 2.73%   |
| 0x20655    | 3         | 2.73%   |
| 0x20652    | 3         | 2.73%   |
| 0x906ea    | 2         | 1.82%   |
| 0x306d4    | 2         | 1.82%   |
| 0x30673    | 2         | 1.82%   |
| 0xf27      | 1         | 0.91%   |
| 0xa0652    | 1         | 0.91%   |
| 0x906e9    | 1         | 0.91%   |
| 0x806eb    | 1         | 0.91%   |
| 0x6fa      | 1         | 0.91%   |
| 0x306c3    | 1         | 0.91%   |
| 0x08600106 | 1         | 0.91%   |
| 0x08600104 | 1         | 0.91%   |
| 0x08108109 | 1         | 0.91%   |
| 0x0810100b | 1         | 0.91%   |
| 0x0600611a | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 25%     |
| Haswell       | 12        | 11.54%  |
| IvyBridge     | 9         | 8.65%   |
| Goldmont plus | 8         | 7.69%   |
| Westmere      | 7         | 6.73%   |
| Skylake       | 7         | 6.73%   |
| SandyBridge   | 7         | 6.73%   |
| Penryn        | 4         | 3.85%   |
| TigerLake     | 3         | 2.88%   |
| IceLake       | 3         | 2.88%   |
| Zen+          | 2         | 1.92%   |
| Zen 3         | 2         | 1.92%   |
| Zen 2         | 2         | 1.92%   |
| Silvermont    | 2         | 1.92%   |
| Broadwell     | 2         | 1.92%   |
| Zen           | 1         | 0.96%   |
| NetBurst      | 1         | 0.96%   |
| Goldmont      | 1         | 0.96%   |
| Excavator     | 1         | 0.96%   |
| Core          | 1         | 0.96%   |
| CometLake     | 1         | 0.96%   |
| Bonnell       | 1         | 0.96%   |
| Bobcat        | 1         | 0.96%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 90        | 64.29%  |
| Nvidia                           | 28        | 20%     |
| AMD                              | 21        | 15%     |
| Silicon Integrated Systems [SiS] | 1         | 0.71%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 7.8%    |
| Intel 3rd Gen Core processor Graphics Controller                              | 9         | 6.38%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 5.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 4.96%   |
| Intel UHD Graphics 620                                                        | 6         | 4.26%   |
| Intel HD Graphics 620                                                         | 6         | 4.26%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 4.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 6         | 4.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 4.26%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 2.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 2.13%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 2.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 2.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 2.13%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 3         | 2.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 3         | 2.13%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 3         | 2.13%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 1.42%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.42%   |
| Intel HD Graphics 5500                                                        | 2         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.42%   |
| AMD Renoir                                                                    | 2         | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.42%   |
| AMD Cezanne                                                                   | 2         | 1.42%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter     | 1         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                        | 1         | 0.71%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                         | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.71%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                          | 1         | 0.71%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.71%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.71%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                  | 1         | 0.71%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940M]                                                  | 1         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                  | 1         | 0.71%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.71%   |
| Nvidia GK107M [GeForce GT 750M]                                               | 1         | 0.71%   |
| Nvidia GF119M [GeForce GT 520M]                                               | 1         | 0.71%   |
| Nvidia GF119M [GeForce GT 520MX]                                              | 1         | 0.71%   |
| Nvidia GF114M [GeForce GTX 670M]                                              | 1         | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 1         | 0.71%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                           | 1         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 1         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 1         | 0.71%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                             | 1         | 0.71%   |
| Intel Iris Plus Graphics G7                                                   | 1         | 0.71%   |
| Intel HD Graphics 630                                                         | 1         | 0.71%   |
| Intel HD Graphics 500                                                         | 1         | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 1         | 0.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 0.71%   |
| AMD Wrestler [Radeon HD 7340]                                                 | 1         | 0.71%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                        | 1         | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 1         | 0.71%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                     | 1         | 0.71%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                             | 1         | 0.71%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 1         | 0.71%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                      | 1         | 0.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                    | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 53.33%  |
| Intel + Nvidia | 24        | 22.86%  |
| Intel + AMD    | 10        | 9.52%   |
| 1 x AMD        | 10        | 9.52%   |
| 1 x Nvidia     | 2         | 1.9%    |
| AMD + Nvidia   | 2         | 1.9%    |
| 1 x SiS        | 1         | 0.95%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 92        | 86.79%  |
| Proprietary | 13        | 12.26%  |
| Unknown     | 1         | 0.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 71        | 67.62%  |
| 1.01-2.0   | 16        | 15.24%  |
| 0.51-1.0   | 7         | 6.67%   |
| 3.01-4.0   | 5         | 4.76%   |
| 0.01-0.5   | 3         | 2.86%   |
| 2.01-3.0   | 2         | 1.9%    |
| 7.01-8.0   | 1         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 32        | 28.57%  |
| LG Display           | 21        | 18.75%  |
| AU Optronics         | 16        | 14.29%  |
| Chimei Innolux       | 13        | 11.61%  |
| Samsung Electronics  | 6         | 5.36%   |
| Dell                 | 4         | 3.57%   |
| Sharp                | 3         | 2.68%   |
| Lenovo               | 3         | 2.68%   |
| Unknown              | 2         | 1.79%   |
| Sony                 | 2         | 1.79%   |
| PANDA                | 2         | 1.79%   |
| ___                  | 1         | 0.89%   |
| ViewSonic            | 1         | 0.89%   |
| SKY                  | 1         | 0.89%   |
| InnoLux Display      | 1         | 0.89%   |
| InfoVision           | 1         | 0.89%   |
| Goldstar             | 1         | 0.89%   |
| Apple                | 1         | 0.89%   |
| Ancor Communications | 1         | 0.89%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 4         | 3.54%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                | 3         | 2.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 2.65%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 2.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 2         | 1.77%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch | 2         | 1.77%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 1.77%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 1.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 1.77%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                | 2         | 1.77%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                | 2         | 1.77%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1         | 0.88%   |
| ViewSonic VA712-2SERIES VSC941C 1280x1024 338x270mm 17.0-inch        | 1         | 0.88%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                 | 1         | 0.88%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1         | 0.88%   |
| Sony TV SNYAC03 1360x768                                             | 1         | 0.88%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch              | 1         | 0.88%   |
| SKY TV Monitor SKY0001 1920x1080 885x498mm 40.0-inch                 | 1         | 0.88%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch              | 1         | 0.88%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch | 1         | 0.88%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD05E8 1920x1080 344x194mm 15.5-inch         | 1         | 0.88%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch         | 1         | 0.88%   |
| LG Display LCD Monitor LGD04B6 1366x768 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch         | 1         | 0.88%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 1         | 0.88%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD03FF 1920x1080 309x175mm 14.0-inch         | 1         | 0.88%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD01E1 1366x768 310x174mm 14.0-inch          | 1         | 0.88%   |
| Lenovo LEN Q27h-10 LEN66A7 2560x1440 598x336mm 27.0-inch             | 1         | 0.88%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 1         | 0.88%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch              | 1         | 0.88%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch     | 1         | 0.88%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch         | 1         | 0.88%   |
| Goldstar ULTRAGEAR GSM5B80 2560x1440 597x336mm 27.0-inch             | 1         | 0.88%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                    | 1         | 0.88%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                    | 1         | 0.88%   |
| Dell U2413 DELF047 1920x1200 518x324mm 24.1-inch                     | 1         | 0.88%   |
| Dell SE2416H DELD082 1920x1080 530x300mm 24.0-inch                   | 1         | 0.88%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                    | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15C0 1920x1080 344x194mm 15.5-inch     | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 1         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch      | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 57        | 52.29%  |
| 1920x1080 (FHD)   | 37        | 33.94%  |
| 3840x2160 (4K)    | 4         | 3.67%   |
| 2560x1440 (QHD)   | 2         | 1.83%   |
| 1360x768          | 2         | 1.83%   |
| 3840x2400         | 1         | 0.92%   |
| 2160x1440         | 1         | 0.92%   |
| 1920x1200 (WUXGA) | 1         | 0.92%   |
| 1600x900 (HD+)    | 1         | 0.92%   |
| 1440x900 (WXGA+)  | 1         | 0.92%   |
| 1280x800 (WXGA)   | 1         | 0.92%   |
| 1280x1024 (SXGA)  | 1         | 0.92%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 61        | 53.98%  |
| 13      | 19        | 16.81%  |
| 14      | 15        | 13.27%  |
| 24      | 4         | 3.54%   |
| 12      | 3         | 2.65%   |
| 72      | 2         | 1.77%   |
| 27      | 2         | 1.77%   |
| 17      | 2         | 1.77%   |
| 54      | 1         | 0.88%   |
| 40      | 1         | 0.88%   |
| 31      | 1         | 0.88%   |
| 23      | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 90        | 81.82%  |
| 201-300     | 6         | 5.45%   |
| 501-600     | 5         | 4.55%   |
| 351-400     | 3         | 2.73%   |
| 1501-2000   | 2         | 1.82%   |
| 801-900     | 1         | 0.91%   |
| 601-700     | 1         | 0.91%   |
| 1001-1500   | 1         | 0.91%   |
| Unknown     | 1         | 0.91%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 95        | 95%     |
| 16/10 | 3         | 3%      |
| 5/4   | 1         | 1%      |
| 3/2   | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 60        | 53.1%   |
| 81-90          | 32        | 28.32%  |
| 201-250        | 4         | 3.54%   |
| More than 1000 | 3         | 2.65%   |
| 61-70          | 3         | 2.65%   |
| 71-80          | 2         | 1.77%   |
| 301-350        | 2         | 1.77%   |
| 351-500        | 1         | 0.88%   |
| 251-300        | 1         | 0.88%   |
| 141-150        | 1         | 0.88%   |
| 121-130        | 1         | 0.88%   |
| 501-1000       | 1         | 0.88%   |
| 91-100         | 1         | 0.88%   |
| Unknown        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 56        | 50.91%  |
| 121-160       | 35        | 31.82%  |
| 51-100        | 10        | 9.09%   |
| More than 240 | 3         | 2.73%   |
| 1-50          | 3         | 2.73%   |
| 161-240       | 2         | 1.82%   |
| Unknown       | 1         | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 92        | 86.79%  |
| 2     | 8         | 7.55%   |
| 0     | 3         | 2.83%   |
| 3     | 2         | 1.89%   |
| 4     | 1         | 0.94%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 68        | 40.48%  |
| Intel                            | 36        | 21.43%  |
| Qualcomm Atheros                 | 35        | 20.83%  |
| Broadcom                         | 9         | 5.36%   |
| Ralink                           | 4         | 2.38%   |
| Samsung Electronics              | 2         | 1.19%   |
| Ralink Technology                | 2         | 1.19%   |
| MEDIATEK                         | 2         | 1.19%   |
| Marvell Technology Group         | 2         | 1.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Qualcomm                         | 1         | 0.6%    |
| OPPO Electronics                 | 1         | 0.6%    |
| Microsoft                        | 1         | 0.6%    |
| ICS Advent                       | 1         | 0.6%    |
| Broadcom Limited                 | 1         | 0.6%    |
| ASIX Electronics                 | 1         | 0.6%    |
| Apple                            | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 34        | 17.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 11.73%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 13        | 6.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 9         | 4.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 7         | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 5         | 2.55%   |
| Intel Wireless 8265 / 8275                                                     | 5         | 2.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 4         | 2.04%   |
| Intel Wireless 8260                                                            | 4         | 2.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                   | 3         | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 1.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 2         | 1.02%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.02%   |
| Intel Wireless 7265                                                            | 2         | 1.02%   |
| Intel Wireless 7260                                                            | 2         | 1.02%   |
| Intel Wi-Fi 6 AX200                                                            | 2         | 1.02%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 2         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.02%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                        | 1         | 0.51%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.51%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                     | 1         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 1         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 1         | 0.51%   |
| Realtek RTL8187B Wireless Adapter                                              | 1         | 0.51%   |
| Realtek RTL8187 Wireless Adapter                                               | 1         | 0.51%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 1         | 0.51%   |
| Ralink RT2070 Wireless Adapter                                                 | 1         | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.51%   |
| Qualcomm QCA6390 Wireless Network Adapter                                      | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 1         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 1         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 1         | 0.51%   |
| OPPO SDM665-IDP _SN:18689828                                                   | 1         | 0.51%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.51%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.51%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.51%   |
| Intel Wireless 3165                                                            | 1         | 0.51%   |
| Intel Wi-Fi 6 AX201                                                            | 1         | 0.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 1         | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.51%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.51%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 35        | 32.71%  |
| Qualcomm Atheros      | 31        | 28.97%  |
| Realtek Semiconductor | 25        | 23.36%  |
| Broadcom              | 6         | 5.61%   |
| Ralink                | 4         | 3.74%   |
| Ralink Technology     | 2         | 1.87%   |
| MEDIATEK              | 2         | 1.87%   |
| Qualcomm              | 1         | 0.93%   |
| Broadcom Limited      | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 12.15%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 8.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 6.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 4.67%   |
| Intel Wireless 8265 / 8275                                              | 5         | 4.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 3.74%   |
| Intel Wireless 8260                                                     | 4         | 3.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 2.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 2.8%    |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.87%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.87%   |
| Intel Wireless 7265                                                     | 2         | 1.87%   |
| Intel Wireless 7260                                                     | 2         | 1.87%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.87%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.93%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.93%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.93%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.93%   |
| Ralink RT2070 Wireless Adapter                                          | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.93%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.93%   |
| Intel Wireless 3165                                                     | 1         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.93%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.93%   |
| Intel Centrino Wireless-N + WiMAX 6150                                  | 1         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.93%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 0.93%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 1         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 1         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 57        | 64.77%  |
| Intel                            | 11        | 12.5%   |
| Qualcomm Atheros                 | 5         | 5.68%   |
| Broadcom                         | 5         | 5.68%   |
| Samsung Electronics              | 2         | 2.27%   |
| Marvell Technology Group         | 2         | 2.27%   |
| Silicon Integrated Systems [SiS] | 1         | 1.14%   |
| OPPO Electronics                 | 1         | 1.14%   |
| Microsoft                        | 1         | 1.14%   |
| ICS Advent                       | 1         | 1.14%   |
| ASIX Electronics                 | 1         | 1.14%   |
| Apple                            | 1         | 1.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 34        | 38.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 26.14%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 2.27%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.27%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 1.14%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.14%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 1.14%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.14%   |
| OPPO SDM665-IDP _SN:18689828                                                   | 1         | 1.14%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 1.14%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.14%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 1.14%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.14%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.14%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.14%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.14%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.14%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 1.14%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.14%   |
| Apple iPad 4/Mini1                                                             | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 55.14%  |
| Ethernet | 82        | 44.32%  |
| Modem    | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 67.41%  |
| Ethernet | 44        | 32.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 74.04%  |
| 1     | 26        | 25%     |
| 0     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 90        | 85.71%  |
| Yes  | 15        | 14.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 29.55%  |
| Qualcomm Atheros Communications | 17        | 19.32%  |
| Realtek Semiconductor           | 11        | 12.5%   |
| IMC Networks                    | 8         | 9.09%   |
| Foxconn / Hon Hai               | 8         | 9.09%   |
| Lite-On Technology              | 4         | 4.55%   |
| Broadcom                        | 4         | 4.55%   |
| Ralink                          | 3         | 3.41%   |
| Toshiba                         | 2         | 2.27%   |
| Dell                            | 2         | 2.27%   |
| Realtek                         | 1         | 1.14%   |
| Qcom                            | 1         | 1.14%   |
| Apple                           | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 15.91%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 9.09%   |
| Realtek Bluetooth Radio                                                             | 6         | 6.82%   |
| IMC Networks Bluetooth Device                                                       | 5         | 5.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 4.55%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 3.41%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 3.41%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 3.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 3.41%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.41%   |
| Realtek 802.11n WLAN Adapter                                                        | 2         | 2.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 2.27%   |
| Intel AX201 Bluetooth                                                               | 2         | 2.27%   |
| Intel AX200 Bluetooth                                                               | 2         | 2.27%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 2.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 2.27%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 2.27%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.14%   |
| Toshiba Askey for                                                                   | 1         | 1.14%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.14%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.14%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 1.14%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 1.14%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.14%   |
| Lite-On BCM43142A0                                                                  | 1         | 1.14%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.14%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.14%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.14%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 1.14%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.14%   |
| Broadcom HP Portable Valentine                                                      | 1         | 1.14%   |
| Broadcom Bluetooth                                                                  | 1         | 1.14%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 1.14%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 1.14%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 93        | 78.15%  |
| Nvidia                           | 13        | 10.92%  |
| AMD                              | 11        | 9.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.84%   |
| Samson Technologies              | 1         | 0.84%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 14.08%  |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 7.75%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 7.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 6.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 5.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 4.93%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 4.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 4.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 3.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 2.82%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.11%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.41%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 1.41%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 0.7%    |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.7%    |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.7%    |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.7%    |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.7%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.7%    |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.7%    |
| AMD Wrestler HDMI Audio                                                    | 1         | 0.7%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 1         | 0.7%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 1         | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.7%    |
| AMD FCH Azalia Controller                                                  | 1         | 0.7%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 1         | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| SK Hynix                             | 12        | 23.08%  |
| Samsung Electronics                  | 11        | 21.15%  |
| Micron Technology                    | 8         | 15.38%  |
| Crucial                              | 5         | 9.62%   |
| Unknown                              | 3         | 5.77%   |
| Kingston                             | 2         | 3.85%   |
| ELPIDA                               | 2         | 3.85%   |
| Unknown (ABCD)                       | 1         | 1.92%   |
| Toshiba                              | 1         | 1.92%   |
| Team                                 | 1         | 1.92%   |
| Silicon Power                        | 1         | 1.92%   |
| Ramaxel Technology                   | 1         | 1.92%   |
| Nanya Technology                     | 1         | 1.92%   |
| Hikvision                            | 1         | 1.92%   |
| Chun Well Technology Holding Limited | 1         | 1.92%   |
| ASint Technology                     | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                         | 3         | 5.45%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s                        | 2         | 3.64%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s                      | 2         | 3.64%   |
| ELPIDA RAM EBJ21UE8BDS0-DJ-F 2048MB SODIMM DDR3 1334MT/s                      | 2         | 3.64%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                                | 1         | 1.82%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                           | 1         | 1.82%   |
| Unknown RAM Module 2GB SODIMM DDR2                                            | 1         | 1.82%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                         | 1         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s           | 1         | 1.82%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s                            | 1         | 1.82%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s                             | 1         | 1.82%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                                  | 1         | 1.82%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s                          | 1         | 1.82%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.82%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.82%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.82%   |
| SK Hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s                      | 1         | 1.82%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 4096MB SODIMM DDR4 3200MT/s                     | 1         | 1.82%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                        | 1         | 1.82%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                        | 1         | 1.82%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s                       | 1         | 1.82%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.82%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.82%   |
| Silicon Power RAM DBST8GN128S 8GB SODIMM DDR3 1333MT/s                        | 1         | 1.82%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                         | 1         | 1.82%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                         | 1         | 1.82%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s                         | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s                   | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                         | 1         | 1.82%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                     | 1         | 1.82%   |
| Nanya RAM NT1GC64BH4B0PS-CG 1GB SODIMM DDR3 1333MT/s                          | 1         | 1.82%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s                 | 1         | 1.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.82%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s                        | 1         | 1.82%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s                         | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s                       | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s                         | 1         | 1.82%   |
| Micron RAM 16KTF51264HZ-1G4M1 4096MB SODIMM DDR3 1333MT/s                     | 1         | 1.82%   |
| Micron RAM 16ATF1G64HZ-2G1A2 8GB SODIMM DDR4 2133MT/s                         | 1         | 1.82%   |
| Kingston RAM KNWMX1-ETB 4GB SODIMM DDR3 1600MT/s                              | 1         | 1.82%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s                    | 1         | 1.82%   |
| Hikvision RAM HKED4162DAA1D0MA1 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.82%   |
| Crucial RAM CT8G4SFS8266.M8FE 8192MB SODIMM DDR4 2667MT/s                     | 1         | 1.82%   |
| Crucial RAM CT8G4SFS824A.C8FJ 8GB SODIMM DDR4 2400MT/s                        | 1         | 1.82%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s                      | 1         | 1.82%   |
| Crucial RAM CB8GS2400.C8JT 8GB SODIMM DDR4 2400MT/s                           | 1         | 1.82%   |
| Crucial RAM BL16G32C16S4B.M16FE1 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.82%   |
| Chun Well Holding Limited RAM CL19-19-19 D4-2666 16384MB SODIMM DDR4 2667MT/s | 1         | 1.82%   |
| ASint RAM SSA302G08-GDJEC 4GB SODIMM DDR3 1334MT/s                            | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 18        | 43.9%   |
| DDR3   | 16        | 39.02%  |
| DDR2   | 3         | 7.32%   |
| LPDDR4 | 2         | 4.88%   |
| SDRAM  | 1         | 2.44%   |
| LPDDR3 | 1         | 2.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 92.5%   |
| Row Of Chips | 3         | 7.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 17        | 37.78%  |
| 8192  | 16        | 35.56%  |
| 2048  | 6         | 13.33%  |
| 16384 | 5         | 11.11%  |
| 1024  | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 20.83%  |
| 2667    | 9         | 18.75%  |
| 3200    | 6         | 12.5%   |
| 2400    | 4         | 8.33%   |
| 1334    | 4         | 8.33%   |
| 3266    | 3         | 6.25%   |
| 1333    | 3         | 6.25%   |
| 2133    | 2         | 4.17%   |
| 4267    | 1         | 2.08%   |
| 4199    | 1         | 2.08%   |
| 1067    | 1         | 2.08%   |
| 1066    | 1         | 2.08%   |
| 975     | 1         | 2.08%   |
| 800     | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

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
| IMC Networks                           | 18        | 19.78%  |
| Chicony Electronics                    | 18        | 19.78%  |
| Microdia                               | 10        | 10.99%  |
| Realtek Semiconductor                  | 9         | 9.89%   |
| Lite-On Technology                     | 6         | 6.59%   |
| Suyin                                  | 5         | 5.49%   |
| Sunplus Innovation Technology          | 5         | 5.49%   |
| Acer                                   | 4         | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.3%    |
| Ricoh                                  | 2         | 2.2%    |
| Quanta                                 | 2         | 2.2%    |
| Importek                               | 2         | 2.2%    |
| Alcor Micro                            | 2         | 2.2%    |
| Silicon Motion                         | 1         | 1.1%    |
| Samsung Electronics                    | 1         | 1.1%    |
| Logitech                               | 1         | 1.1%    |
| Lenovo                                 | 1         | 1.1%    |
| Apple                                  | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                      | 12        | 13.19%  |
| Chicony Integrated Camera                               | 6         | 6.59%   |
| Microdia Integrated_Webcam_HD                           | 5         | 5.49%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 4.4%    |
| Sunplus Integrated_Webcam_HD                            | 3         | 3.3%    |
| Realtek HP Truevision HD                                | 3         | 3.3%    |
| Lite-On HP TrueVision HD Camera                         | 3         | 3.3%    |
| Sunplus HD Webcam                                       | 2         | 2.2%    |
| Realtek Integrated Webcam HD                            | 2         | 2.2%    |
| Realtek Integrated Webcam                               | 2         | 2.2%    |
| Microdia HP Integrated Webcam                           | 2         | 2.2%    |
| Chicony HD WebCam                                       | 2         | 2.2%    |
| Alcor Micro Asus Integrated Webcam                      | 2         | 2.2%    |
| Suyin USB 2.0 Camera                                    | 1         | 1.1%    |
| Suyin Integrated_Webcam_HD                              | 1         | 1.1%    |
| Suyin HP TrueVision HD                                  | 1         | 1.1%    |
| Suyin HP Integrated Webcam                              | 1         | 1.1%    |
| Suyin 1.3M HD WebCam                                    | 1         | 1.1%    |
| Silicon Motion WebCam SC-10HDP12631N                    | 1         | 1.1%    |
| Samsung Galaxy A5 (MTP)                                 | 1         | 1.1%    |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870]     | 1         | 1.1%    |
| Ricoh USB2.0 Camera                                     | 1         | 1.1%    |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 1.1%    |
| Realtek Integrated_Webcam_HD                            | 1         | 1.1%    |
| Quanta LG Webcam                                        | 1         | 1.1%    |
| Quanta HP Wide Vision HD Camera                         | 1         | 1.1%    |
| Microdia Sonix USB 2.0 Camera                           | 1         | 1.1%    |
| Microdia Lenovo EasyCamera                              | 1         | 1.1%    |
| Microdia Integrated Webcam                              | 1         | 1.1%    |
| Logitech C922 Pro Stream Webcam                         | 1         | 1.1%    |
| Lite-On TOSHIBA Web Camera - HD                         | 1         | 1.1%    |
| Lite-On HP Webcam                                       | 1         | 1.1%    |
| Lite-On HP HD Camera                                    | 1         | 1.1%    |
| Lenovo Integrated Webcam [R5U877]                       | 1         | 1.1%    |
| Importek TOSHIBA Web Camera - HD                        | 1         | 1.1%    |
| Importek TOSHIBA Web Camera - FHD                       | 1         | 1.1%    |
| IMC Networks TOSHIBA Web Camera - HD                    | 1         | 1.1%    |
| IMC Networks imx188_azurewave(p)                        | 1         | 1.1%    |
| Chicony USB2.0 VGA UVC WebCam                           | 1         | 1.1%    |
| Chicony USB2.0 UVC WebCam                               | 1         | 1.1%    |
| Chicony Integrated Camera (1280x720@30)                 | 1         | 1.1%    |
| Chicony HP Wide Vision HD Camera                        | 1         | 1.1%    |
| Chicony HP Webcam [2 MP Macro]                          | 1         | 1.1%    |
| Chicony HP Truevision HD                                | 1         | 1.1%    |
| Chicony HD WebCam (Acer)                                | 1         | 1.1%    |
| Chicony HD User Facing                                  | 1         | 1.1%    |
| Chicony Front Camera                                    | 1         | 1.1%    |
| Chicony Acer CrystalEye Webcam                          | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera        | 1         | 1.1%    |
| Apple FaceTime HD Camera                                | 1         | 1.1%    |
| Acer SunplusIT Integrated Camera                        | 1         | 1.1%    |
| Acer Lenovo EasyCamera                                  | 1         | 1.1%    |
| Acer Integrated Camera                                  | 1         | 1.1%    |
| Acer Front Camera                                       | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 38.46%  |
| Shenzhen Goodix Technology | 2         | 15.38%  |
| LighTuning Technology      | 2         | 15.38%  |
| Elan Microelectronics      | 2         | 15.38%  |
| Validity Sensors           | 1         | 7.69%   |
| Upek                       | 1         | 7.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 15.38%  |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 2         | 15.38%  |
| Validity Sensors VFS101 Fingerprint Reader        | 1         | 7.69%   |
| Upek TCS5B Fingerprint sensor                     | 1         | 7.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader  | 1         | 7.69%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 7.69%   |
| Shenzhen Goodix FingerPrint                       | 1         | 7.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 7.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 7.69%   |
| Elan ELAN:Fingerprint                             | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                  | 1         | 7.69%   |

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
| 0     | 72        | 67.92%  |
| 1     | 30        | 28.3%   |
| 2     | 2         | 1.89%   |
| 4     | 1         | 0.94%   |
| 3     | 1         | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 34.21%  |
| Graphics card            | 7         | 18.42%  |
| Net/wireless             | 6         | 15.79%  |
| Chipcard                 | 4         | 10.53%  |
| Bluetooth                | 3         | 7.89%   |
| Multimedia controller    | 2         | 5.26%   |
| Modem                    | 1         | 2.63%   |
| Communication controller | 1         | 2.63%   |
| Camera                   | 1         | 2.63%   |

