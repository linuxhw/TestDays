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

Total: 224

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | BOHK-WAX9X                  | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Acer          | Aspire A315-55G             | [70559c048c](https://linux-hardware.org/?probe=70559c048c) | Jan 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HP            | Unknown                     | [fedf225852](https://linux-hardware.org/?probe=fedf225852) | Jan 17, 2023 |
| HP            | Unknown                     | [8b89da1da5](https://linux-hardware.org/?probe=8b89da1da5) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Valve         | Jupiter                     | [b927a3e937](https://linux-hardware.org/?probe=b927a3e937) | Jan 16, 2023 |
| Valve         | Jupiter                     | [2b476ca470](https://linux-hardware.org/?probe=2b476ca470) | Jan 16, 2023 |
| MSI           | GF63 Thin 10SC              | [26379f8b8d](https://linux-hardware.org/?probe=26379f8b8d) | Jan 11, 2023 |
| HUAWEI        | KLVD-WXX9                   | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2c6b6c2558](https://linux-hardware.org/?probe=2c6b6c2558) | Jan 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| Toshiba       | Satellite L635              | [be223c0ff1](https://linux-hardware.org/?probe=be223c0ff1) | Dec 03, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| Dell          | Venue 8 Pro 5830            | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| Apple         | MacBookPro13,2              | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Dell          | Inspiron 5558               | [61f05a7c32](https://linux-hardware.org/?probe=61f05a7c32) | Oct 10, 2022 |
| Sony          | SVF15A13SAB                 | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [de59de7b14](https://linux-hardware.org/?probe=de59de7b14) | Oct 04, 2022 |
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
| Ubuntu 20.04           | 23        | 15.65%  |
| Ubuntu 18.04           | 11        | 7.48%   |
| OpenMandriva 4.2       | 7         | 4.76%   |
| Fedora 35              | 5         | 3.4%    |
| Zorin 16               | 4         | 2.72%   |
| Ubuntu 20.10           | 4         | 2.72%   |
| OpenMandriva 4.3       | 4         | 2.72%   |
| Ubuntu 22.04           | 3         | 2.04%   |
| Ubuntu 21.04           | 3         | 2.04%   |
| Pop!_OS 22.04          | 3         | 2.04%   |
| Pop!_OS 20.04          | 3         | 2.04%   |
| Endless 3.3.20-nexthw1 | 3         | 2.04%   |
| Debian Testing         | 3         | 2.04%   |
| Arch                   | 3         | 2.04%   |
| Ubuntu 19.04           | 2         | 1.36%   |
| Pop!_OS 20.10          | 2         | 1.36%   |
| Manjaro 20.0.3         | 2         | 1.36%   |
| Linux Mint 21          | 2         | 1.36%   |
| Linux Mint 20.1        | 2         | 1.36%   |
| Linux Mint 20          | 2         | 1.36%   |
| Kubuntu 20.04          | 2         | 1.36%   |
| Kali 2021.2            | 2         | 1.36%   |
| Fedora 36              | 2         | 1.36%   |
| Endless 3.7.8          | 2         | 1.36%   |
| Xubuntu 20.10          | 1         | 0.68%   |
| Xubuntu 20.04          | 1         | 0.68%   |
| Xubuntu 18.04          | 1         | 0.68%   |
| Ubuntu Unity 16.04     | 1         | 0.68%   |
| Ubuntu 19.10           | 1         | 0.68%   |
| SteamOS 3.4.4          | 1         | 0.68%   |
| Solus 4.1              | 1         | 0.68%   |
| Solus 3.9999           | 1         | 0.68%   |
| ROSA R8.1              | 1         | 0.68%   |
| Rocky Linux 9.1        | 1         | 0.68%   |
| RHEL 8                 | 1         | 0.68%   |
| Q4OS 4                 | 1         | 0.68%   |
| Pop!_OS 21.10          | 1         | 0.68%   |
| Pop!_OS 21.04          | 1         | 0.68%   |
| Parrot 5.1             | 1         | 0.68%   |
| OpenMandriva 4.50      | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 47        | 33.81%  |
| Endless      | 13        | 9.35%   |
| OpenMandriva | 12        | 8.63%   |
| Linux Mint   | 8         | 5.76%   |
| Fedora       | 8         | 5.76%   |
| Pop!_OS      | 6         | 4.32%   |
| Manjaro      | 5         | 3.6%    |
| Debian       | 5         | 3.6%    |
| Zorin        | 4         | 2.88%   |
| Arch         | 4         | 2.88%   |
| Xubuntu      | 3         | 2.16%   |
| Kubuntu      | 3         | 2.16%   |
| KDE neon     | 3         | 2.16%   |
| Kali         | 3         | 2.16%   |
| Elementary   | 2         | 1.44%   |
| Clear Linux  | 2         | 1.44%   |
| Ubuntu Unity | 1         | 0.72%   |
| SteamOS      | 1         | 0.72%   |
| Solus        | 1         | 0.72%   |
| ROSA         | 1         | 0.72%   |
| Rocky Linux  | 1         | 0.72%   |
| RHEL         | 1         | 0.72%   |
| Q4OS         | 1         | 0.72%   |
| Parrot       | 1         | 0.72%   |
| Liberty OS   | 1         | 0.72%   |
| Gentoo       | 1         | 0.72%   |
| ArcoLinux    | 1         | 0.72%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 6         | 3.87%   |
| 5.4.0-42-generic         | 4         | 2.58%   |
| 5.16.7-desktop-1omv4003  | 4         | 2.58%   |
| 5.15.0-48-generic        | 4         | 2.58%   |
| 4.15.0-15-generic        | 4         | 2.58%   |
| 5.4.0-19-generic         | 3         | 1.94%   |
| 5.11.0-43-generic        | 3         | 1.94%   |
| 5.8.0-53-generic         | 2         | 1.29%   |
| 5.8.0-41-generic         | 2         | 1.29%   |
| 5.8.0-38-generic         | 2         | 1.29%   |
| 5.8.0-36-generic         | 2         | 1.29%   |
| 5.4.0-58-generic         | 2         | 1.29%   |
| 5.4.0-37-generic         | 2         | 1.29%   |
| 5.3.0-28-generic         | 2         | 1.29%   |
| 5.3.0-2-amd64            | 2         | 1.29%   |
| 5.15.0-58-generic        | 2         | 1.29%   |
| 5.15.0-56-generic        | 2         | 1.29%   |
| 5.11.0-41-generic        | 2         | 1.29%   |
| 5.11.0-40-generic        | 2         | 1.29%   |
| 5.11.0-37-generic        | 2         | 1.29%   |
| 5.11.0-31-generic        | 2         | 1.29%   |
| 5.0.0-20-generic         | 2         | 1.29%   |
| 4.15.0-29-generic        | 2         | 1.29%   |
| 6.1.8-arch1-1            | 1         | 0.65%   |
| 6.0.6-76060006-generic   | 1         | 0.65%   |
| 6.0.5-200.fc36.x86_64    | 1         | 0.65%   |
| 5.9.0-kali1-amd64        | 1         | 0.65%   |
| 5.8.18-xanmod1           | 1         | 0.65%   |
| 5.8.0-7630-generic       | 1         | 0.65%   |
| 5.8.0-57-generic         | 1         | 0.65%   |
| 5.8.0-48-generic         | 1         | 0.65%   |
| 5.8.0-45-generic         | 1         | 0.65%   |
| 5.8.0-44-generic         | 1         | 0.65%   |
| 5.8.0-43-generic         | 1         | 0.65%   |
| 5.8.0-26-generic         | 1         | 0.65%   |
| 5.8.0-25-generic         | 1         | 0.65%   |
| 5.8.0-14-generic         | 1         | 0.65%   |
| 5.7.9-1-MANJARO          | 1         | 0.65%   |
| 5.7.0-3-MANJARO          | 1         | 0.65%   |
| 5.6.4-152.current        | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 12.84%  |
| 5.8.0   | 17        | 11.49%  |
| 5.11.0  | 15        | 10.14%  |
| 5.15.0  | 11        | 7.43%   |
| 5.3.0   | 10        | 6.76%   |
| 4.15.0  | 9         | 6.08%   |
| 5.10.14 | 6         | 4.05%   |
| 5.16.7  | 4         | 2.7%    |
| 5.0.0   | 4         | 2.7%    |
| 4.18.0  | 4         | 2.7%    |
| 5.19.0  | 3         | 2.03%   |
| 5.13.0  | 3         | 2.03%   |
| 5.10.0  | 3         | 2.03%   |
| 6.1.8   | 1         | 0.68%   |
| 6.0.6   | 1         | 0.68%   |
| 6.0.5   | 1         | 0.68%   |
| 5.9.0   | 1         | 0.68%   |
| 5.8.18  | 1         | 0.68%   |
| 5.7.9   | 1         | 0.68%   |
| 5.7.0   | 1         | 0.68%   |
| 5.6.4   | 1         | 0.68%   |
| 5.6.15  | 1         | 0.68%   |
| 5.6.14  | 1         | 0.68%   |
| 5.5.7   | 1         | 0.68%   |
| 5.4.123 | 1         | 0.68%   |
| 5.4.12  | 1         | 0.68%   |
| 5.19.5  | 1         | 0.68%   |
| 5.19.12 | 1         | 0.68%   |
| 5.19.1  | 1         | 0.68%   |
| 5.18.10 | 1         | 0.68%   |
| 5.18.0  | 1         | 0.68%   |
| 5.17.0  | 1         | 0.68%   |
| 5.16.5  | 1         | 0.68%   |
| 5.16.19 | 1         | 0.68%   |
| 5.16.16 | 1         | 0.68%   |
| 5.16.15 | 1         | 0.68%   |
| 5.15.85 | 1         | 0.68%   |
| 5.15.6  | 1         | 0.68%   |
| 5.15.57 | 1         | 0.68%   |
| 5.15.5  | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 14.48%  |
| 5.8     | 18        | 12.41%  |
| 5.11    | 17        | 11.72%  |
| 5.15    | 15        | 10.34%  |
| 5.3     | 10        | 6.9%    |
| 5.10    | 10        | 6.9%    |
| 4.15    | 9         | 6.21%   |
| 5.16    | 8         | 5.52%   |
| 5.19    | 6         | 4.14%   |
| 4.18    | 5         | 3.45%   |
| 5.13    | 4         | 2.76%   |
| 5.0     | 4         | 2.76%   |
| 5.6     | 3         | 2.07%   |
| 6.0     | 2         | 1.38%   |
| 5.7     | 2         | 1.38%   |
| 5.18    | 2         | 1.38%   |
| 5.14    | 2         | 1.38%   |
| 4.9     | 2         | 1.38%   |
| 6.1     | 1         | 0.69%   |
| 5.9     | 1         | 0.69%   |
| 5.5     | 1         | 0.69%   |
| 5.17    | 1         | 0.69%   |
| 4.13    | 1         | 0.69%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 129       | 96.99%  |
| i686   | 4         | 3.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 73        | 52.52%  |
| KDE5       | 24        | 17.27%  |
| Unknown    | 15        | 10.79%  |
| X-Cinnamon | 7         | 5.04%   |
| XFCE       | 6         | 4.32%   |
| Cinnamon   | 3         | 2.16%   |
| Pantheon   | 2         | 1.44%   |
| KDE        | 2         | 1.44%   |
| Unity      | 1         | 0.72%   |
| trinity    | 1         | 0.72%   |
| openbox    | 1         | 0.72%   |
| MATE       | 1         | 0.72%   |
| KDE4       | 1         | 0.72%   |
| i3         | 1         | 0.72%   |
| Budgie     | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 105       | 78.36%  |
| Wayland | 16        | 11.94%  |
| Unknown | 10        | 7.46%   |
| Tty     | 3         | 2.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 78        | 57.78%  |
| SDDM    | 20        | 14.81%  |
| GDM     | 17        | 12.59%  |
| GDM3    | 11        | 8.15%   |
| TDM     | 4         | 2.96%   |
| LightDM | 4         | 2.96%   |
| KDM     | 1         | 0.74%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 96        | 70.59%  |
| Unknown | 13        | 9.56%   |
| en_GB   | 7         | 5.15%   |
| ar_EG   | 7         | 5.15%   |
| ar_SA   | 6         | 4.41%   |
| C       | 3         | 2.21%   |
| en_IN   | 1         | 0.74%   |
| en_AG   | 1         | 0.74%   |
| Default | 1         | 0.74%   |
| ar_AE   | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 69        | 51.49%  |
| EFI  | 65        | 48.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 78.52%  |
| Btrfs   | 9         | 6.67%   |
| Overlay | 8         | 5.93%   |
| Unknown | 6         | 4.44%   |
| Xfs     | 3         | 2.22%   |
| Zfs     | 1         | 0.74%   |
| Tmpfs   | 1         | 0.74%   |
| Ext2    | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 64.93%  |
| GPT     | 34        | 25.37%  |
| MBR     | 13        | 9.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 88.24%  |
| Yes       | 16        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 75.37%  |
| Yes       | 33        | 24.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Dell                        | 25        | 18.8%   |
| ASUSTek Computer            | 25        | 18.8%   |
| Lenovo                      | 20        | 15.04%  |
| Hewlett-Packard             | 18        | 13.53%  |
| Acer                        | 11        | 8.27%   |
| Toshiba                     | 7         | 5.26%   |
| Sony                        | 6         | 4.51%   |
| HUAWEI                      | 6         | 4.51%   |
| MSI                         | 3         | 2.26%   |
| Notebook                    | 2         | 1.5%    |
| Apple                       | 2         | 1.5%    |
| Valve                       | 1         | 0.75%   |
| Samsung Electronics         | 1         | 0.75%   |
| Packard Bell                | 1         | 0.75%   |
| LG Electronics              | 1         | 0.75%   |
| I-Life Digital Technologies | 1         | 0.75%   |
| GPD                         | 1         | 0.75%   |
| eMachines                   | 1         | 0.75%   |
| Clevo                       | 1         | 0.75%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 3.01%   |
| HP 15                                      | 3         | 2.26%   |
| Dell G3 3590                               | 3         | 2.26%   |
| HP Pavilion g6                             | 2         | 1.5%    |
| HP Notebook                                | 2         | 1.5%    |
| Dell Inspiron 3542                         | 2         | 1.5%    |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 2         | 1.5%    |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 1.5%    |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 1.5%    |
| Acer Aspire 4752                           | 2         | 1.5%    |
| Unknown                                    | 2         | 1.5%    |
| Valve Jupiter                              | 1         | 0.75%   |
| Toshiba Satellite S55t-A                   | 1         | 0.75%   |
| Toshiba Satellite L635                     | 1         | 0.75%   |
| Toshiba Satellite L500                     | 1         | 0.75%   |
| Toshiba Satellite C855D                    | 1         | 0.75%   |
| Toshiba Satellite C850-B561                | 1         | 0.75%   |
| Toshiba Satellite C55-B                    | 1         | 0.75%   |
| Toshiba QOSMIO X875                        | 1         | 0.75%   |
| Sony VPCEA36FA                             | 1         | 0.75%   |
| Sony VPCCA35FA                             | 1         | 0.75%   |
| Sony VGN-FZ250E                            | 1         | 0.75%   |
| Sony SVF15A13SAB                           | 1         | 0.75%   |
| Sony SVF153290X                            | 1         | 0.75%   |
| Sony SVF14N13CXB                           | 1         | 0.75%   |
| Samsung 870Z5E/880Z5E/680Z5E               | 1         | 0.75%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.75%   |
| Notebook PD5x_7xPNP_PNN_PNT                | 1         | 0.75%   |
| Notebook NH5xAx                            | 1         | 0.75%   |
| MSI MS-1454                                | 1         | 0.75%   |
| MSI GF63 Thin 8RCS                         | 1         | 0.75%   |
| MSI GF63 Thin 10SC                         | 1         | 0.75%   |
| LG R490-G.ARL5RE2                          | 1         | 0.75%   |
| Lenovo V570 1066AJU                        | 1         | 0.75%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.75%   |
| Lenovo ThinkPad X230 2325OA3               | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003LAD   | 1         | 0.75%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002JUS   | 1         | 0.75%   |
| Lenovo ThinkPad S1 Yoga 12 20DL0079US      | 1         | 0.75%   |
| Lenovo ThinkPad P52s 20LBS0JC00            | 1         | 0.75%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11        | 8.27%   |
| Dell Inspiron         | 11        | 8.27%   |
| ASUS VivoBook         | 10        | 7.52%   |
| Acer Aspire           | 8         | 6.02%   |
| Toshiba Satellite     | 6         | 4.51%   |
| HP Pavilion           | 5         | 3.76%   |
| HP Laptop             | 5         | 3.76%   |
| Dell Latitude         | 4         | 3.01%   |
| Lenovo IdeaPad        | 3         | 2.26%   |
| HP 15                 | 3         | 2.26%   |
| Dell Vostro           | 3         | 2.26%   |
| Dell G3               | 3         | 2.26%   |
| MSI GF63              | 2         | 1.5%    |
| HP Notebook           | 2         | 1.5%    |
| Dell XPS              | 2         | 1.5%    |
| ASUS ROG              | 2         | 1.5%    |
| Unknown               | 2         | 1.5%    |
| Valve Jupiter         | 1         | 0.75%   |
| Toshiba QOSMIO        | 1         | 0.75%   |
| Sony VPCEA36FA        | 1         | 0.75%   |
| Sony VPCCA35FA        | 1         | 0.75%   |
| Sony VGN-FZ250E       | 1         | 0.75%   |
| Sony SVF15A13SAB      | 1         | 0.75%   |
| Sony SVF153290X       | 1         | 0.75%   |
| Sony SVF14N13CXB      | 1         | 0.75%   |
| Samsung 870Z5E        | 1         | 0.75%   |
| Packard Bell EasyNote | 1         | 0.75%   |
| Notebook PD5x         | 1         | 0.75%   |
| Notebook NH5xAx       | 1         | 0.75%   |
| MSI MS-1454           | 1         | 0.75%   |
| LG R490-G.ARL5RE2     | 1         | 0.75%   |
| Lenovo V570           | 1         | 0.75%   |
| Lenovo V15-IIL        | 1         | 0.75%   |
| Lenovo ThinkBook      | 1         | 0.75%   |
| Lenovo Legion         | 1         | 0.75%   |
| Lenovo Flex           | 1         | 0.75%   |
| Lenovo B590           | 1         | 0.75%   |
| I-Life Digital ZED    | 1         | 0.75%   |
| HUAWEI RLEF-XX        | 1         | 0.75%   |
| HUAWEI MateBook       | 1         | 0.75%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 21        | 15.79%  |
| 2019 | 17        | 12.78%  |
| 2020 | 11        | 8.27%   |
| 2012 | 10        | 7.52%   |
| 2011 | 10        | 7.52%   |
| 2021 | 9         | 6.77%   |
| 2014 | 9         | 6.77%   |
| 2013 | 9         | 6.77%   |
| 2017 | 8         | 6.02%   |
| 2010 | 8         | 6.02%   |
| 2016 | 7         | 5.26%   |
| 2015 | 5         | 3.76%   |
| 2022 | 3         | 2.26%   |
| 2009 | 3         | 2.26%   |
| 2008 | 1         | 0.75%   |
| 2007 | 1         | 0.75%   |
| 2002 | 1         | 0.75%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 133       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 120       | 89.55%  |
| Enabled  | 14        | 10.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 133       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 40        | 29.63%  |
| 4.01-8.0    | 34        | 25.19%  |
| 8.01-16.0   | 22        | 16.3%   |
| 16.01-24.0  | 20        | 14.81%  |
| 32.01-64.0  | 7         | 5.19%   |
| 1.01-2.0    | 7         | 5.19%   |
| 2.01-3.0    | 4         | 2.96%   |
| 64.01-256.0 | 1         | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 57        | 39.31%  |
| 2.01-3.0  | 41        | 28.28%  |
| 3.01-4.0  | 20        | 13.79%  |
| 4.01-8.0  | 18        | 12.41%  |
| 0.51-1.0  | 7         | 4.83%   |
| 8.01-16.0 | 2         | 1.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 103       | 75.18%  |
| 2      | 27        | 19.71%  |
| 3      | 6         | 4.38%   |
| 0      | 1         | 0.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 57.78%  |
| Yes       | 57        | 42.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 76.12%  |
| No        | 32        | 23.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 98.5%   |
| No        | 2         | 1.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 84.21%  |
| No        | 21        | 15.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 133       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Riyadh               | 51        | 37.23%  |
| Jeddah               | 39        | 28.47%  |
| Makkah               | 13        | 9.49%   |
| Medina               | 9         | 6.57%   |
| Dammam               | 6         | 4.38%   |
| Khobar               | 4         | 2.92%   |
| Thuwal               | 3         | 2.19%   |
| Dhahran              | 3         | 2.19%   |
| Al Qatif             | 3         | 2.19%   |
| Ta'if                | 1         | 0.73%   |
| Sayhat               | 1         | 0.73%   |
| Buraidah             | 1         | 0.73%   |
| Baq`a' ash Sharqiyah | 1         | 0.73%   |
| Al Hufuf             | 1         | 0.73%   |
| Al Faruq             | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 30        | 37     | 18.52%  |
| Toshiba                   | 24        | 30     | 14.81%  |
| WDC                       | 20        | 25     | 12.35%  |
| Samsung Electronics       | 19        | 24     | 11.73%  |
| Kingston                  | 14        | 16     | 8.64%   |
| SanDisk                   | 9         | 9      | 5.56%   |
| Unknown                   | 7         | 8      | 4.32%   |
| SK hynix                  | 5         | 7      | 3.09%   |
| Intel                     | 4         | 9      | 2.47%   |
| Crucial                   | 3         | 4      | 1.85%   |
| Micron/Crucial Technology | 2         | 2      | 1.23%   |
| KingSpec                  | 2         | 2      | 1.23%   |
| JMicron Technology        | 2         | 2      | 1.23%   |
| Hitachi                   | 2         | 2      | 1.23%   |
| Hewlett-Packard           | 2         | 2      | 1.23%   |
| Fujitsu                   | 2         | 2      | 1.23%   |
| YMTC                      | 1         | 1      | 0.62%   |
| XrayDisk                  | 1         | 1      | 0.62%   |
| SPCC                      | 1         | 1      | 0.62%   |
| Silicon Motion            | 1         | 1      | 0.62%   |
| PNY                       | 1         | 1      | 0.62%   |
| Phison                    | 1         | 1      | 0.62%   |
| OYUNKEY                   | 1         | 1      | 0.62%   |
| Micron Technology         | 1         | 1      | 0.62%   |
| Lexar                     | 1         | 1      | 0.62%   |
| KIOXIA                    | 1         | 1      | 0.62%   |
| G-DRIVE                   | 1         | 1      | 0.62%   |
| China                     | 1         | 1      | 0.62%   |
| Biostar                   | 1         | 1      | 0.62%   |
| Apple                     | 1         | 2      | 0.62%   |
| A-DATA Technology         | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 12        | 7.14%   |
| Toshiba MQ04ABF100 1TB                              | 9         | 5.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 2.98%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.98%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 2.38%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 1.79%   |
| SanDisk NVMe SSD Drive 128GB                        | 3         | 1.79%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.19%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 1.19%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 1.19%   |
| SK hynix NVMe SSD Drive 1024GB                      | 2         | 1.19%   |
| Seagate ST9500325AS 500GB                           | 2         | 1.19%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 1.19%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 1.19%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 1.19%   |
| JMicron Tech 250GB                                  | 2         | 1.19%   |
| Intel SSDPEKNW512G8 512GB                           | 2         | 1.19%   |
| Intel NVMe SSD Drive 1024GB                         | 2         | 1.19%   |
| HP SSD S700 1TB                                     | 2         | 1.19%   |
| YMTC PC005 256GB                                    | 1         | 0.6%    |
| XrayDisk SSD 1TB                                    | 1         | 0.6%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.6%    |
| WDC WDS100T3X0C-00SJG0 1TB                          | 1         | 0.6%    |
| WDC WD5000LPVX-08V0TT6 500GB                        | 1         | 0.6%    |
| WDC WD5000LPCX-00VHAT0 500GB                        | 1         | 0.6%    |
| WDC WD5000BEVT-08A0RT1 500GB                        | 1         | 0.6%    |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 0.6%    |
| WDC WD3200BEVT-00ZCT0 320GB                         | 1         | 0.6%    |
| WDC WD1600BEVT-22ZCT0 160GB                         | 1         | 0.6%    |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 0.6%    |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.6%    |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 0.6%    |
| WDC WD10SPZX-08Z10 1TB                              | 1         | 0.6%    |
| WDC WD10SPZX-00Z10T0 1TB                            | 1         | 0.6%    |
| WDC WD10JPVX-55JC3T3 1TB                            | 1         | 0.6%    |
| WDC WD10JPVX-00JC3T0 1TB                            | 1         | 0.6%    |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.6%    |
| WDC PC SN520 SDAPNUW-256G-1002 256GB                | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 30        | 37     | 41.67%  |
| Toshiba | 23        | 25     | 31.94%  |
| WDC     | 15        | 19     | 20.83%  |
| Hitachi | 2         | 2      | 2.78%   |
| Fujitsu | 2         | 2      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 13     | 28.21%  |
| SanDisk             | 5         | 5      | 12.82%  |
| Samsung Electronics | 5         | 5      | 12.82%  |
| Crucial             | 3         | 3      | 7.69%   |
| WDC                 | 2         | 2      | 5.13%   |
| SK hynix            | 2         | 3      | 5.13%   |
| KingSpec            | 2         | 2      | 5.13%   |
| Hewlett-Packard     | 2         | 2      | 5.13%   |
| XrayDisk            | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| OYUNKEY             | 1         | 1      | 2.56%   |
| Lexar               | 1         | 1      | 2.56%   |
| G-DRIVE             | 1         | 1      | 2.56%   |
| China               | 1         | 1      | 2.56%   |
| A-DATA Technology   | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 70        | 85     | 44.3%   |
| NVMe    | 40        | 59     | 25.32%  |
| SSD     | 39        | 42     | 24.68%  |
| MMC     | 7         | 9      | 4.43%   |
| Unknown | 2         | 2      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 125    | 65.77%  |
| NVMe | 40        | 59     | 26.85%  |
| MMC  | 7         | 9      | 4.7%    |
| SAS  | 4         | 4      | 2.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 52        | 63     | 49.06%  |
| 0.01-0.5   | 51        | 61     | 48.11%  |
| 1.01-2.0   | 3         | 3      | 2.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 35        | 25%     |
| 251-500        | 33        | 23.57%  |
| 101-250        | 33        | 23.57%  |
| 51-100         | 12        | 8.57%   |
| 1-20           | 8         | 5.71%   |
| 21-50          | 7         | 5%      |
| More than 3000 | 4         | 2.86%   |
| 1001-2000      | 4         | 2.86%   |
| 2001-3000      | 2         | 1.43%   |
| Unknown        | 2         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 62        | 42.47%  |
| 21-50          | 38        | 26.03%  |
| 51-100         | 15        | 10.27%  |
| 101-250        | 14        | 9.59%   |
| 251-500        | 10        | 6.85%   |
| 501-1000       | 3         | 2.05%   |
| Unknown        | 2         | 1.37%   |
| More than 3000 | 1         | 0.68%   |
| 1001-2000      | 1         | 0.68%   |

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
| Detected | 92        | 128    | 65.25%  |
| Works    | 44        | 64     | 31.21%  |
| Malfunc  | 5         | 5      | 3.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 103       | 67.76%  |
| Samsung Electronics              | 13        | 8.55%   |
| AMD                              | 10        | 6.58%   |
| SanDisk                          | 7         | 4.61%   |
| SK hynix                         | 3         | 1.97%   |
| Micron/Crucial Technology        | 3         | 1.97%   |
| Kingston Technology Company      | 3         | 1.97%   |
| Toshiba America Info Systems     | 2         | 1.32%   |
| Silicon Motion                   | 2         | 1.32%   |
| Yangtze Memory Technologies      | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Realtek Semiconductor            | 1         | 0.66%   |
| Phison Electronics               | 1         | 0.66%   |
| Micron Technology                | 1         | 0.66%   |
| Apple                            | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 15        | 9.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 12        | 7.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 10        | 6.29%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 10        | 6.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 8         | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 8         | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 8         | 5.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 7         | 4.4%    |
| Samsung NVMe SSD Controller 980                                              | 6         | 3.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 6         | 3.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 5         | 3.14%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 5         | 3.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 4         | 2.52%   |
| SanDisk PC SN520 NVMe SSD                                                    | 3         | 1.89%   |
| Intel SSD 660P Series                                                        | 3         | 1.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 2         | 1.26%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 2         | 1.26%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 2         | 1.26%   |
| Micron/Crucial P1 NVMe PCIe SSD                                              | 2         | 1.26%   |
| Kingston Company Company Non-Volatile memory controller                      | 2         | 1.26%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.26%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.26%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 1.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.26%   |
| Yangtze Memory Non-Volatile memory controller                                | 1         | 0.63%   |
| SK hynix PC300 NVMe Solid State Drive 1TB                                    | 1         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 0.63%   |
| Silicon Motion Non-Volatile memory controller                                | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.63%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.63%   |
| Realtek Realtek Non-Volatile memory controller                               | 1         | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 0.63%   |
| Micron/Crucial Non-Volatile memory controller                                | 1         | 0.63%   |
| Micron Non-Volatile memory controller                                        | 1         | 0.63%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                          | 1         | 0.63%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                   | 1         | 0.63%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                      | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 97        | 63.82%  |
| NVMe | 40        | 26.32%  |
| RAID | 9         | 5.92%   |
| IDE  | 6         | 3.95%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 87.97%  |
| AMD    | 16        | 12.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 5.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 3.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 3.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.26%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.26%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.26%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 2.26%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.26%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 2.26%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 2.26%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 2.26%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.5%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.5%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.5%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.5%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1.5%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.5%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.5%    |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 1.5%    |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.5%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.75%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.75%   |
| Intel Pentium CPU N3510 @ 1.99GHz             | 1         | 0.75%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.75%   |
| Intel Mobile Pentium 4 - M CPU 2.20GHz        | 1         | 0.75%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 41        | 30.83%  |
| Intel Core i7           | 35        | 26.32%  |
| Intel Core i3           | 12        | 9.02%   |
| Intel Celeron           | 11        | 8.27%   |
| Other                   | 8         | 6.02%   |
| AMD Ryzen 5             | 8         | 6.02%   |
| Intel Core 2 Duo        | 3         | 2.26%   |
| Intel Atom              | 3         | 2.26%   |
| AMD Ryzen 7             | 3         | 2.26%   |
| Intel Pentium Dual-Core | 2         | 1.5%    |
| Intel Pentium           | 2         | 1.5%    |
| AMD Ryzen 9             | 2         | 1.5%    |
| Intel Mobile Pentium 4  | 1         | 0.75%   |
| AMD E2                  | 1         | 0.75%   |
| AMD A12                 | 1         | 0.75%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 55.64%  |
| 4      | 38        | 28.57%  |
| 6      | 10        | 7.52%   |
| 8      | 5         | 3.76%   |
| 1      | 4         | 3.01%   |
| 14     | 2         | 1.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 133       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 105       | 78.95%  |
| 1      | 27        | 20.3%   |
| 8      | 1         | 0.75%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 128       | 95.52%  |
| Unknown        | 4         | 2.99%   |
| 32-bit         | 2         | 1.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 26.62%  |
| 0x40651    | 11        | 7.91%   |
| 0x306a9    | 11        | 7.91%   |
| 0x206a7    | 9         | 6.47%   |
| 0x806ec    | 6         | 4.32%   |
| 0x406e3    | 6         | 4.32%   |
| 0x806ea    | 5         | 3.6%    |
| 0x806c1    | 5         | 3.6%    |
| 0x706a1    | 5         | 3.6%    |
| 0x1067a    | 5         | 3.6%    |
| 0x806e9    | 4         | 2.88%   |
| 0x20655    | 4         | 2.88%   |
| 0x906ea    | 3         | 2.16%   |
| 0x706e5    | 3         | 2.16%   |
| 0x306d4    | 3         | 2.16%   |
| 0x30673    | 3         | 2.16%   |
| 0x20652    | 3         | 2.16%   |
| 0x08108109 | 3         | 2.16%   |
| 0x906a3    | 2         | 1.44%   |
| 0xf27      | 1         | 0.72%   |
| 0xa0652    | 1         | 0.72%   |
| 0x906e9    | 1         | 0.72%   |
| 0x806eb    | 1         | 0.72%   |
| 0x6fa      | 1         | 0.72%   |
| 0x306c3    | 1         | 0.72%   |
| 0x08701013 | 1         | 0.72%   |
| 0x08600106 | 1         | 0.72%   |
| 0x08600104 | 1         | 0.72%   |
| 0x0810100b | 1         | 0.72%   |
| 0x0600611a | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 23.31%  |
| IvyBridge        | 12        | 9.02%   |
| Haswell          | 12        | 9.02%   |
| SandyBridge      | 10        | 7.52%   |
| Westmere         | 8         | 6.02%   |
| Skylake          | 8         | 6.02%   |
| Goldmont plus    | 8         | 6.02%   |
| Zen+             | 5         | 3.76%   |
| TigerLake        | 5         | 3.76%   |
| Penryn           | 5         | 3.76%   |
| Zen 3            | 4         | 3.01%   |
| Broadwell        | 4         | 3.01%   |
| Zen 2            | 3         | 2.26%   |
| Silvermont       | 3         | 2.26%   |
| IceLake          | 3         | 2.26%   |
| CometLake        | 2         | 1.5%    |
| Alderlake Hybrid | 2         | 1.5%    |
| Zen              | 1         | 0.75%   |
| NetBurst         | 1         | 0.75%   |
| Goldmont         | 1         | 0.75%   |
| Excavator        | 1         | 0.75%   |
| Core             | 1         | 0.75%   |
| Bonnell          | 1         | 0.75%   |
| Bobcat           | 1         | 0.75%   |
| Unknown          | 1         | 0.75%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 111       | 61.67%  |
| Nvidia                           | 38        | 21.11%  |
| AMD                              | 30        | 16.67%  |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 6.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 6.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 9         | 4.97%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 4.42%   |
| Intel UHD Graphics 620                                                        | 7         | 3.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 3.87%   |
| Intel HD Graphics 620                                                         | 7         | 3.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 3.87%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 3.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 2.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 2.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 2.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 2.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 2.21%   |
| Intel HD Graphics 5500                                                        | 4         | 2.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 2.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 2.21%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 1.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 1.66%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                  | 3         | 1.66%   |
| Nvidia GP108M [GeForce MX230]                                                 | 2         | 1.1%    |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 1.1%    |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 1.1%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.1%    |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 1.1%    |
| AMD Renoir                                                                    | 2         | 1.1%    |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter     | 1         | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 0.55%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                        | 1         | 0.55%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                         | 1         | 0.55%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                          | 1         | 0.55%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.55%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 1         | 0.55%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                  | 1         | 0.55%   |
| Nvidia GM108M [GeForce MX130]                                                 | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 51.49%  |
| Intel + Nvidia | 31        | 23.13%  |
| 1 x AMD        | 16        | 11.94%  |
| Intel + AMD    | 11        | 8.21%   |
| 1 x Nvidia     | 3         | 2.24%   |
| AMD + Nvidia   | 3         | 2.24%   |
| 1 x SiS        | 1         | 0.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 116       | 84.67%  |
| Proprietary | 20        | 14.6%   |
| Unknown     | 1         | 0.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 68.66%  |
| 1.01-2.0   | 20        | 14.93%  |
| 0.51-1.0   | 7         | 5.22%   |
| 3.01-4.0   | 6         | 4.48%   |
| 0.01-0.5   | 4         | 2.99%   |
| 2.01-3.0   | 3         | 2.24%   |
| 7.01-8.0   | 2         | 1.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 40        | 28.17%  |
| LG Display              | 25        | 17.61%  |
| AU Optronics            | 21        | 14.79%  |
| Chimei Innolux          | 18        | 12.68%  |
| Samsung Electronics     | 8         | 5.63%   |
| Lenovo                  | 4         | 2.82%   |
| Dell                    | 4         | 2.82%   |
| Sharp                   | 3         | 2.11%   |
| PANDA                   | 3         | 2.11%   |
| Unknown                 | 2         | 1.41%   |
| Sony                    | 2         | 1.41%   |
| Apple                   | 2         | 1.41%   |
| ___                     | 1         | 0.7%    |
| ViewSonic               | 1         | 0.7%    |
| Valve                   | 1         | 0.7%    |
| SKY                     | 1         | 0.7%    |
| InnoLux Display         | 1         | 0.7%    |
| InfoVision              | 1         | 0.7%    |
| Goldstar                | 1         | 0.7%    |
| Chi Mei Optoelectronics | 1         | 0.7%    |
| ASUSTek Computer        | 1         | 0.7%    |
| Ancor Communications    | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 4         | 2.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 2.1%    |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                 | 3         | 2.1%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.1%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 1.4%    |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 1.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.4%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.4%    |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                 | 2         | 1.4%    |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.4%    |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.7%    |
| ViewSonic VA712-2SERIES VSC941C 1280x1024 338x270mm 17.0-inch         | 1         | 0.7%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.7%    |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                  | 1         | 0.7%    |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.7%    |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.7%    |
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch  | 1         | 0.7%    |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                    | 1         | 0.7%    |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4147 3840x2160 294x165mm 13.3-inch | 1         | 0.7%    |
| Samsung Electronics CF791 SAM0DC3 3440x1440 797x333mm 34.0-inch       | 1         | 0.7%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.7%    |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05E8 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD04B6 1366x768 309x174mm 14.0-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 0.7%    |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 63        | 45.99%  |
| 1920x1080 (FHD)   | 53        | 38.69%  |
| 3840x2160 (4K)    | 4         | 2.92%   |
| 2560x1440 (QHD)   | 2         | 1.46%   |
| 2160x1440         | 2         | 1.46%   |
| 1920x1200 (WUXGA) | 2         | 1.46%   |
| 1360x768          | 2         | 1.46%   |
| 800x1280          | 1         | 0.73%   |
| 3840x2400         | 1         | 0.73%   |
| 3440x1440         | 1         | 0.73%   |
| 2880x1800         | 1         | 0.73%   |
| 2560x1600         | 1         | 0.73%   |
| 1600x900 (HD+)    | 1         | 0.73%   |
| 1440x900 (WXGA+)  | 1         | 0.73%   |
| 1280x800 (WXGA)   | 1         | 0.73%   |
| 1280x1024 (SXGA)  | 1         | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 55.24%  |
| 13      | 23        | 16.08%  |
| 14      | 16        | 11.19%  |
| 24      | 5         | 3.5%    |
| 12      | 4         | 2.8%    |
| 17      | 3         | 2.1%    |
| 72      | 2         | 1.4%    |
| 27      | 2         | 1.4%    |
| 16      | 2         | 1.4%    |
| 54      | 1         | 0.7%    |
| 40      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 31      | 1         | 0.7%    |
| 23      | 1         | 0.7%    |
| 7       | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 80%     |
| 201-300     | 10        | 7.14%   |
| 501-600     | 6         | 4.29%   |
| 351-400     | 4         | 2.86%   |
| 1501-2000   | 2         | 1.43%   |
| 801-900     | 1         | 0.71%   |
| 701-800     | 1         | 0.71%   |
| 601-700     | 1         | 0.71%   |
| 1001-1500   | 1         | 0.71%   |
| 1-100       | 1         | 0.71%   |
| Unknown     | 1         | 0.71%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 117       | 91.41%  |
| 16/10 | 6         | 4.69%   |
| 3/2   | 2         | 1.56%   |
| 5/4   | 1         | 0.78%   |
| 21/9  | 1         | 0.78%   |
| 0.67  | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 54.55%  |
| 81-90          | 35        | 24.48%  |
| 71-80          | 4         | 2.8%    |
| 61-70          | 4         | 2.8%    |
| 201-250        | 4         | 2.8%    |
| More than 1000 | 3         | 2.1%    |
| 351-500        | 2         | 1.4%    |
| 301-350        | 2         | 1.4%    |
| 251-300        | 2         | 1.4%    |
| 121-130        | 2         | 1.4%    |
| 111-120        | 2         | 1.4%    |
| 1-40           | 1         | 0.7%    |
| 141-150        | 1         | 0.7%    |
| 501-1000       | 1         | 0.7%    |
| 91-100         | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 62        | 44.6%   |
| 121-160       | 50        | 35.97%  |
| 51-100        | 12        | 8.63%   |
| 161-240       | 7         | 5.04%   |
| More than 240 | 4         | 2.88%   |
| 1-50          | 3         | 2.16%   |
| Unknown       | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 118       | 86.76%  |
| 2     | 11        | 8.09%   |
| 3     | 3         | 2.21%   |
| 0     | 3         | 2.21%   |
| 4     | 1         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 86        | 40.57%  |
| Intel                            | 48        | 22.64%  |
| Qualcomm Atheros                 | 41        | 19.34%  |
| Broadcom                         | 14        | 6.6%    |
| Ralink                           | 5         | 2.36%   |
| Samsung Electronics              | 3         | 1.42%   |
| Ralink Technology                | 2         | 0.94%   |
| MediaTek                         | 2         | 0.94%   |
| Marvell Technology Group         | 2         | 0.94%   |
| Silicon Integrated Systems [SiS] | 1         | 0.47%   |
| Qualcomm                         | 1         | 0.47%   |
| OPPO Electronics                 | 1         | 0.47%   |
| Microsoft                        | 1         | 0.47%   |
| ICS Advent                       | 1         | 0.47%   |
| Dell                             | 1         | 0.47%   |
| Broadcom Limited                 | 1         | 0.47%   |
| ASIX Electronics                 | 1         | 0.47%   |
| Apple                            | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 19.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 10.2%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 5.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 4.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 3.27%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.04%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.63%   |
| Intel Wireless 8260                                               | 4         | 1.63%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.22%   |
| Intel Wireless 7265                                               | 3         | 1.22%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.22%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.82%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.82%   |
| Intel Wireless 7260                                               | 2         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.82%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller           | 1         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.41%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.41%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.41%   |
| Realtek RTL8187B Wireless Adapter                                 | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 34.56%  |
| Qualcomm Atheros      | 36        | 26.47%  |
| Realtek Semiconductor | 31        | 22.79%  |
| Broadcom              | 10        | 7.35%   |
| Ralink                | 5         | 3.68%   |
| Ralink Technology     | 2         | 1.47%   |
| MediaTek              | 2         | 1.47%   |
| Qualcomm              | 1         | 0.74%   |
| Dell                  | 1         | 0.74%   |
| Broadcom Limited      | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 9.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 8.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.88%   |
| Intel Wireless 8265 / 8275                                     | 6         | 4.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 3.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.68%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 3.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.94%   |
| Intel Wireless 8260                                            | 4         | 2.94%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 2.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.21%   |
| Intel Wireless 7265                                            | 3         | 2.21%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.21%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.21%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.47%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.47%   |
| Intel Wireless 7260                                            | 2         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.74%   |
| Realtek RTL8187B Wireless Adapter                              | 1         | 0.74%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.74%   |
| Ralink RT2070 Wireless Adapter                                 | 1         | 0.74%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.74%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 73        | 67.59%  |
| Intel                            | 11        | 10.19%  |
| Qualcomm Atheros                 | 7         | 6.48%   |
| Broadcom                         | 6         | 5.56%   |
| Samsung Electronics              | 3         | 2.78%   |
| Marvell Technology Group         | 2         | 1.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.93%   |
| OPPO Electronics                 | 1         | 0.93%   |
| Microsoft                        | 1         | 0.93%   |
| ICS Advent                       | 1         | 0.93%   |
| ASIX Electronics                 | 1         | 0.93%   |
| Apple                            | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 47        | 43.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 23.15%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 2.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 2.78%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.85%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.93%   |
| OPPO SDM710-MTP _SN:2396E2D4                                                   | 1         | 0.93%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.93%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.93%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.93%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.93%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.93%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.93%   |
| Apple iPad 4/Mini1                                                             | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 55.98%  |
| Ethernet | 102       | 43.59%  |
| Modem    | 1         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 81.02%  |
| Ethernet | 26        | 18.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 96        | 72.18%  |
| 1     | 35        | 26.32%  |
| 0     | 2         | 1.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 79.26%  |
| Yes  | 28        | 20.74%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 32.74%  |
| Qualcomm Atheros Communications | 18        | 15.93%  |
| Realtek Semiconductor           | 14        | 12.39%  |
| IMC Networks                    | 10        | 8.85%   |
| Foxconn / Hon Hai               | 10        | 8.85%   |
| Lite-On Technology              | 6         | 5.31%   |
| Toshiba                         | 4         | 3.54%   |
| Broadcom                        | 4         | 3.54%   |
| Ralink                          | 3         | 2.65%   |
| Realtek                         | 2         | 1.77%   |
| Dell                            | 2         | 1.77%   |
| Ralink Technology               | 1         | 0.88%   |
| Qcom                            | 1         | 0.88%   |
| Apple                           | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 17        | 15.04%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 7.96%   |
| Realtek Bluetooth Radio                                                             | 8         | 7.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 6.19%   |
| Intel Bluetooth Device                                                              | 6         | 5.31%   |
| IMC Networks Bluetooth Device                                                       | 6         | 5.31%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.42%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 3.54%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 2.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.65%   |
| Intel AX200 Bluetooth                                                               | 3         | 2.65%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 2.65%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.77%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.77%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.77%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.77%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.77%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.88%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.88%   |
| Toshiba Askey for                                                                   | 1         | 0.88%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.88%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.88%   |
| Ralink CSR BS8510                                                                   | 1         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.88%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.88%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.88%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.88%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.88%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.88%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.88%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.88%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.88%   |
| Broadcom Bluetooth                                                                  | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 114       | 73.55%  |
| AMD                              | 19        | 12.26%  |
| Nvidia                           | 18        | 11.61%  |
| Silicon Integrated Systems [SiS] | 1         | 0.65%   |
| Samson Technologies              | 1         | 0.65%   |
| Nreal                            | 1         | 0.65%   |
| Cooler Master                    | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 22        | 11.96%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 7.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 6.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 5.98%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 4.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 4.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.72%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 2.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.17%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.63%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.09%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.09%   |
| Nvidia Audio device                                                        | 2         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.09%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.09%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 0.54%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.54%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.54%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.54%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.54%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.54%   |
| Nreal Air                                                                  | 1         | 0.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.54%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 1         | 0.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 19        | 26.76%  |
| SK hynix                             | 13        | 18.31%  |
| Micron Technology                    | 10        | 14.08%  |
| Crucial                              | 6         | 8.45%   |
| Unknown                              | 5         | 7.04%   |
| Kingston                             | 5         | 7.04%   |
| Elpida                               | 2         | 2.82%   |
| Unknown (ABCD)                       | 1         | 1.41%   |
| Toshiba                              | 1         | 1.41%   |
| Team                                 | 1         | 1.41%   |
| Silicon Power                        | 1         | 1.41%   |
| Ramaxel Technology                   | 1         | 1.41%   |
| Patriot Memory (PDP Systems)         | 1         | 1.41%   |
| Nanya Technology                     | 1         | 1.41%   |
| KLEVV                                | 1         | 1.41%   |
| Hikvision                            | 1         | 1.41%   |
| Chun Well Technology Holding Limited | 1         | 1.41%   |
| ASint Technology                     | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 4%      |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 2.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.67%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 2.67%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.33%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 1.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.33%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.33%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.33%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.33%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.33%   |
| SK hynix RAM HMT112S6TFR8C-G7 1GB SODIMM DDR3 1067MT/s           | 1         | 1.33%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.33%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| Silicon Power RAM DBST8GN128S 8GB SODIMM DDR3 1333MT/s           | 1         | 1.33%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 1         | 1.33%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.33%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471B1G73CB0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.33%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 25        | 43.86%  |
| DDR3    | 22        | 38.6%   |
| LPDDR4  | 3         | 5.26%   |
| DDR2    | 3         | 5.26%   |
| LPDDR3  | 2         | 3.51%   |
| SDRAM   | 1         | 1.75%   |
| Unknown | 1         | 1.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 91.07%  |
| Row Of Chips | 5         | 8.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 34.92%  |
| 4096  | 22        | 34.92%  |
| 2048  | 9         | 14.29%  |
| 16384 | 7         | 11.11%  |
| 1024  | 2         | 3.17%   |
| 32768 | 1         | 1.59%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 13        | 19.4%   |
| 1600    | 13        | 19.4%   |
| 3200    | 9         | 13.43%  |
| 1334    | 7         | 10.45%  |
| 2400    | 4         | 5.97%   |
| 2133    | 4         | 5.97%   |
| 1333    | 4         | 5.97%   |
| 3266    | 3         | 4.48%   |
| 4267    | 2         | 2.99%   |
| 1067    | 2         | 2.99%   |
| 800     | 2         | 2.99%   |
| 4199    | 1         | 1.49%   |
| 1066    | 1         | 1.49%   |
| 975     | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

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
| Chicony Electronics                    | 23        | 20.18%  |
| IMC Networks                           | 21        | 18.42%  |
| Microdia                               | 13        | 11.4%   |
| Realtek Semiconductor                  | 9         | 7.89%   |
| Acer                                   | 8         | 7.02%   |
| Suyin                                  | 6         | 5.26%   |
| Sunplus Innovation Technology          | 6         | 5.26%   |
| Lite-On Technology                     | 6         | 5.26%   |
| Quanta                                 | 5         | 4.39%   |
| Importek                               | 3         | 2.63%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.63%   |
| Ricoh                                  | 2         | 1.75%   |
| Apple                                  | 2         | 1.75%   |
| Alcor Micro                            | 2         | 1.75%   |
| Silicon Motion                         | 1         | 0.88%   |
| Samsung Electronics                    | 1         | 0.88%   |
| Luxvisions Innotech Limited            | 1         | 0.88%   |
| Logitech                               | 1         | 0.88%   |
| Lenovo                                 | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 10.53%  |
| Chicony Integrated Camera                           | 8         | 7.02%   |
| Microdia Integrated_Webcam_HD                       | 7         | 6.14%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 4.39%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.63%   |
| Lite-On HP TrueVision HD Camera                     | 3         | 2.63%   |
| Suyin 1.3M HD WebCam                                | 2         | 1.75%   |
| Sunplus HD WebCam                                   | 2         | 1.75%   |
| Realtek Integrated Webcam HD                        | 2         | 1.75%   |
| Realtek Integrated Webcam                           | 2         | 1.75%   |
| Realtek HP Truevision HD integrated webcam          | 2         | 1.75%   |
| Microdia HP Integrated Webcam                       | 2         | 1.75%   |
| IMC Networks HD Camera                              | 2         | 1.75%   |
| Chicony HD WebCam                                   | 2         | 1.75%   |
| Chicony Front Camera                                | 2         | 1.75%   |
| Alcor Micro Asus Integrated Webcam                  | 2         | 1.75%   |
| Acer Integrated Camera                              | 2         | 1.75%   |
| Suyin USB 2.0 Camera                                | 1         | 0.88%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.88%   |
| Suyin HP TrueVision HD                              | 1         | 0.88%   |
| Suyin HP Integrated Webcam                          | 1         | 0.88%   |
| Sunplus HP Universal Camera                         | 1         | 0.88%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.88%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.88%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 1         | 0.88%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.88%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.88%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.88%   |
| Realtek HP Truevision HD                            | 1         | 0.88%   |
| Quanta VGA WebCam                                   | 1         | 0.88%   |
| Quanta ov9734_techfront_camera                      | 1         | 0.88%   |
| Quanta LG Webcam                                    | 1         | 0.88%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.88%   |
| Quanta FHD Camera                                   | 1         | 0.88%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.88%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.88%   |
| Microdia Integrated Webcam HD                       | 1         | 0.88%   |
| Microdia Integrated Webcam                          | 1         | 0.88%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 0.88%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 29.41%  |
| Shenzhen Goodix Technology | 4         | 23.53%  |
| Validity Sensors           | 2         | 11.76%  |
| Upek                       | 2         | 11.76%  |
| LighTuning Technology      | 2         | 11.76%  |
| Elan Microelectronics      | 2         | 11.76%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 11.76%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 11.76%  |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 11.76%  |
| Validity Sensors VFS471 Fingerprint Reader             | 1         | 5.88%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 5.88%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 5.88%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.88%   |
| Shenzhen Goodix FingerPrint                            | 1         | 5.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 5.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5.88%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.88%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.88%   |

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
| 0     | 94        | 69.12%  |
| 1     | 36        | 26.47%  |
| 2     | 4         | 2.94%   |
| 4     | 1         | 0.74%   |
| 3     | 1         | 0.74%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 35.42%  |
| Graphics card            | 11        | 22.92%  |
| Net/wireless             | 7         | 14.58%  |
| Chipcard                 | 4         | 8.33%   |
| Multimedia controller    | 3         | 6.25%   |
| Bluetooth                | 3         | 6.25%   |
| Modem                    | 1         | 2.08%   |
| Communication controller | 1         | 2.08%   |
| Camera                   | 1         | 2.08%   |

