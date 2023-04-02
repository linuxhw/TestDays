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

Total: 233

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Sony          | VGN-FZ250E                  | [ca7937209b](https://linux-hardware.org/?probe=ca7937209b) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| HP            | Laptop 15-da2xxx            | [76cbc7df6d](https://linux-hardware.org/?probe=76cbc7df6d) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [e70b65f78d](https://linux-hardware.org/?probe=e70b65f78d) | Feb 20, 2023 |
| Dell          | Latitude E6520              | [b04c6e8984](https://linux-hardware.org/?probe=b04c6e8984) | Feb 18, 2023 |
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
| Ubuntu 20.04           | 23        | 14.84%  |
| Ubuntu 18.04           | 11        | 7.1%    |
| OpenMandriva 4.2       | 7         | 4.52%   |
| OpenMandriva 4.3       | 6         | 3.87%   |
| Ubuntu 22.04           | 5         | 3.23%   |
| Fedora 35              | 5         | 3.23%   |
| Zorin 16               | 4         | 2.58%   |
| Ubuntu 20.10           | 4         | 2.58%   |
| Ubuntu 21.04           | 3         | 1.94%   |
| Pop!_OS 22.04          | 3         | 1.94%   |
| Pop!_OS 20.04          | 3         | 1.94%   |
| Endless 3.3.20-nexthw1 | 3         | 1.94%   |
| Debian Testing         | 3         | 1.94%   |
| Arch                   | 3         | 1.94%   |
| Ubuntu 19.04           | 2         | 1.29%   |
| Pop!_OS 20.10          | 2         | 1.29%   |
| Manjaro 20.0.3         | 2         | 1.29%   |
| Linux Mint 21          | 2         | 1.29%   |
| Linux Mint 20.1        | 2         | 1.29%   |
| Linux Mint 20          | 2         | 1.29%   |
| Kubuntu 20.04          | 2         | 1.29%   |
| KDE neon 22.04         | 2         | 1.29%   |
| Kali 2021.2            | 2         | 1.29%   |
| Fedora 36              | 2         | 1.29%   |
| Endless 3.7.8          | 2         | 1.29%   |
| Debian 11              | 2         | 1.29%   |
| Xubuntu 20.10          | 1         | 0.65%   |
| Xubuntu 20.04          | 1         | 0.65%   |
| Xubuntu 18.04          | 1         | 0.65%   |
| Ubuntu Unity 16.04     | 1         | 0.65%   |
| Ubuntu 19.10           | 1         | 0.65%   |
| SteamOS 3.4.4          | 1         | 0.65%   |
| Solus 4.1              | 1         | 0.65%   |
| Solus 3.9999           | 1         | 0.65%   |
| ROSA R8.1              | 1         | 0.65%   |
| Rocky Linux 9.1        | 1         | 0.65%   |
| RHEL 8                 | 1         | 0.65%   |
| Q4OS 4                 | 1         | 0.65%   |
| Pop!_OS 21.10          | 1         | 0.65%   |
| Pop!_OS 21.04          | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 48        | 32.88%  |
| OpenMandriva | 14        | 9.59%   |
| Endless      | 13        | 8.9%    |
| Linux Mint   | 8         | 5.48%   |
| Fedora       | 8         | 5.48%   |
| Pop!_OS      | 6         | 4.11%   |
| Debian       | 6         | 4.11%   |
| Manjaro      | 5         | 3.42%   |
| Zorin        | 4         | 2.74%   |
| KDE neon     | 4         | 2.74%   |
| Kali         | 4         | 2.74%   |
| Arch         | 4         | 2.74%   |
| Xubuntu      | 3         | 2.05%   |
| Kubuntu      | 3         | 2.05%   |
| Elementary   | 2         | 1.37%   |
| Clear Linux  | 2         | 1.37%   |
| Ubuntu Unity | 1         | 0.68%   |
| SteamOS      | 1         | 0.68%   |
| Solus        | 1         | 0.68%   |
| ROSA         | 1         | 0.68%   |
| Rocky Linux  | 1         | 0.68%   |
| RHEL         | 1         | 0.68%   |
| Q4OS         | 1         | 0.68%   |
| Parrot       | 1         | 0.68%   |
| Liberty OS   | 1         | 0.68%   |
| Gentoo       | 1         | 0.68%   |
| ChimeraOS    | 1         | 0.68%   |
| ArcoLinux    | 1         | 0.68%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 6         | 3.68%   |
| 5.10.14-desktop-1omv4002 | 6         | 3.68%   |
| 5.4.0-42-generic         | 4         | 2.45%   |
| 5.15.0-48-generic        | 4         | 2.45%   |
| 4.15.0-15-generic        | 4         | 2.45%   |
| 5.4.0-19-generic         | 3         | 1.84%   |
| 5.19.0-32-generic        | 3         | 1.84%   |
| 5.11.0-43-generic        | 3         | 1.84%   |
| 5.8.0-53-generic         | 2         | 1.23%   |
| 5.8.0-41-generic         | 2         | 1.23%   |
| 5.8.0-38-generic         | 2         | 1.23%   |
| 5.8.0-36-generic         | 2         | 1.23%   |
| 5.4.0-58-generic         | 2         | 1.23%   |
| 5.4.0-37-generic         | 2         | 1.23%   |
| 5.3.0-28-generic         | 2         | 1.23%   |
| 5.3.0-2-amd64            | 2         | 1.23%   |
| 5.15.0-58-generic        | 2         | 1.23%   |
| 5.15.0-56-generic        | 2         | 1.23%   |
| 5.11.0-41-generic        | 2         | 1.23%   |
| 5.11.0-40-generic        | 2         | 1.23%   |
| 5.11.0-37-generic        | 2         | 1.23%   |
| 5.11.0-31-generic        | 2         | 1.23%   |
| 5.0.0-20-generic         | 2         | 1.23%   |
| 4.15.0-29-generic        | 2         | 1.23%   |
| 6.1.8-arch1-1            | 1         | 0.61%   |
| 6.1.11-arch1-1           | 1         | 0.61%   |
| 6.1.0-kali5-amd64        | 1         | 0.61%   |
| 6.0.6-76060006-generic   | 1         | 0.61%   |
| 6.0.5-200.fc36.x86_64    | 1         | 0.61%   |
| 5.9.0-kali1-amd64        | 1         | 0.61%   |
| 5.8.18-xanmod1           | 1         | 0.61%   |
| 5.8.0-7630-generic       | 1         | 0.61%   |
| 5.8.0-57-generic         | 1         | 0.61%   |
| 5.8.0-48-generic         | 1         | 0.61%   |
| 5.8.0-45-generic         | 1         | 0.61%   |
| 5.8.0-44-generic         | 1         | 0.61%   |
| 5.8.0-43-generic         | 1         | 0.61%   |
| 5.8.0-26-generic         | 1         | 0.61%   |
| 5.8.0-25-generic         | 1         | 0.61%   |
| 5.8.0-14-generic         | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 12.18%  |
| 5.8.0   | 17        | 10.9%   |
| 5.11.0  | 15        | 9.62%   |
| 5.15.0  | 11        | 7.05%   |
| 5.3.0   | 10        | 6.41%   |
| 4.15.0  | 9         | 5.77%   |
| 5.19.0  | 6         | 3.85%   |
| 5.16.7  | 6         | 3.85%   |
| 5.10.14 | 6         | 3.85%   |
| 5.10.0  | 4         | 2.56%   |
| 5.0.0   | 4         | 2.56%   |
| 4.18.0  | 4         | 2.56%   |
| 5.13.0  | 3         | 1.92%   |
| 6.1.8   | 1         | 0.64%   |
| 6.1.11  | 1         | 0.64%   |
| 6.1.0   | 1         | 0.64%   |
| 6.0.6   | 1         | 0.64%   |
| 6.0.5   | 1         | 0.64%   |
| 5.9.0   | 1         | 0.64%   |
| 5.8.18  | 1         | 0.64%   |
| 5.7.9   | 1         | 0.64%   |
| 5.7.0   | 1         | 0.64%   |
| 5.6.4   | 1         | 0.64%   |
| 5.6.15  | 1         | 0.64%   |
| 5.6.14  | 1         | 0.64%   |
| 5.5.7   | 1         | 0.64%   |
| 5.4.123 | 1         | 0.64%   |
| 5.4.12  | 1         | 0.64%   |
| 5.19.5  | 1         | 0.64%   |
| 5.19.12 | 1         | 0.64%   |
| 5.19.1  | 1         | 0.64%   |
| 5.18.10 | 1         | 0.64%   |
| 5.18.0  | 1         | 0.64%   |
| 5.17.0  | 1         | 0.64%   |
| 5.16.5  | 1         | 0.64%   |
| 5.16.19 | 1         | 0.64%   |
| 5.16.16 | 1         | 0.64%   |
| 5.16.15 | 1         | 0.64%   |
| 5.15.85 | 1         | 0.64%   |
| 5.15.6  | 1         | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 21        | 13.73%  |
| 5.8     | 18        | 11.76%  |
| 5.11    | 17        | 11.11%  |
| 5.15    | 15        | 9.8%    |
| 5.10    | 11        | 7.19%   |
| 5.3     | 10        | 6.54%   |
| 5.16    | 10        | 6.54%   |
| 5.19    | 9         | 5.88%   |
| 4.15    | 9         | 5.88%   |
| 4.18    | 5         | 3.27%   |
| 5.13    | 4         | 2.61%   |
| 5.0     | 4         | 2.61%   |
| 6.1     | 3         | 1.96%   |
| 5.6     | 3         | 1.96%   |
| 6.0     | 2         | 1.31%   |
| 5.7     | 2         | 1.31%   |
| 5.18    | 2         | 1.31%   |
| 5.14    | 2         | 1.31%   |
| 4.9     | 2         | 1.31%   |
| 5.9     | 1         | 0.65%   |
| 5.5     | 1         | 0.65%   |
| 5.17    | 1         | 0.65%   |
| 4.13    | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 135       | 97.12%  |
| i686   | 4         | 2.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 76        | 52.05%  |
| KDE5       | 27        | 18.49%  |
| Unknown    | 15        | 10.27%  |
| XFCE       | 7         | 4.79%   |
| X-Cinnamon | 7         | 4.79%   |
| Cinnamon   | 3         | 2.05%   |
| Pantheon   | 2         | 1.37%   |
| KDE        | 2         | 1.37%   |
| Unity      | 1         | 0.68%   |
| trinity    | 1         | 0.68%   |
| openbox    | 1         | 0.68%   |
| MATE       | 1         | 0.68%   |
| KDE4       | 1         | 0.68%   |
| i3         | 1         | 0.68%   |
| Budgie     | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 108       | 76.6%   |
| Wayland | 20        | 14.18%  |
| Unknown | 10        | 7.09%   |
| Tty     | 3         | 2.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 56.34%  |
| SDDM    | 22        | 15.49%  |
| GDM     | 18        | 12.68%  |
| GDM3    | 13        | 9.15%   |
| TDM     | 4         | 2.82%   |
| LightDM | 4         | 2.82%   |
| KDM     | 1         | 0.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 100       | 70.42%  |
| Unknown | 13        | 9.15%   |
| en_GB   | 7         | 4.93%   |
| ar_EG   | 7         | 4.93%   |
| ar_SA   | 6         | 4.23%   |
| C       | 4         | 2.82%   |
| fr_FR   | 1         | 0.7%    |
| en_IN   | 1         | 0.7%    |
| en_AG   | 1         | 0.7%    |
| Default | 1         | 0.7%    |
| ar_AE   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 73        | 52.14%  |
| EFI  | 67        | 47.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 110       | 78.01%  |
| Btrfs   | 10        | 7.09%   |
| Overlay | 9         | 6.38%   |
| Unknown | 6         | 4.26%   |
| Xfs     | 3         | 2.13%   |
| Zfs     | 1         | 0.71%   |
| Tmpfs   | 1         | 0.71%   |
| Ext2    | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 63.57%  |
| GPT     | 36        | 25.71%  |
| MBR     | 15        | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 87.32%  |
| Yes       | 18        | 12.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 107       | 75.89%  |
| Yes       | 34        | 24.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 27        | 19.42%  |
| Dell                        | 26        | 18.71%  |
| Lenovo                      | 21        | 15.11%  |
| Hewlett-Packard             | 18        | 12.95%  |
| Acer                        | 11        | 7.91%   |
| Toshiba                     | 7         | 5.04%   |
| Sony                        | 6         | 4.32%   |
| HUAWEI                      | 6         | 4.32%   |
| MSI                         | 3         | 2.16%   |
| Apple                       | 3         | 2.16%   |
| Notebook                    | 2         | 1.44%   |
| Valve                       | 1         | 0.72%   |
| Samsung Electronics         | 1         | 0.72%   |
| Packard Bell                | 1         | 0.72%   |
| LG Electronics              | 1         | 0.72%   |
| I-Life Digital Technologies | 1         | 0.72%   |
| GPD                         | 1         | 0.72%   |
| eMachines                   | 1         | 0.72%   |
| Clevo                       | 1         | 0.72%   |
| Unknown                     | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 2.88%   |
| HP 15                                      | 3         | 2.16%   |
| Dell G3 3590                               | 3         | 2.16%   |
| Unknown                                    | 3         | 2.16%   |
| HP Pavilion g6                             | 2         | 1.44%   |
| HP Notebook                                | 2         | 1.44%   |
| Dell Inspiron 3542                         | 2         | 1.44%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 2         | 1.44%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 1.44%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 1.44%   |
| Acer Aspire 4752                           | 2         | 1.44%   |
| Valve Jupiter                              | 1         | 0.72%   |
| Toshiba Satellite S55t-A                   | 1         | 0.72%   |
| Toshiba Satellite L635                     | 1         | 0.72%   |
| Toshiba Satellite L500                     | 1         | 0.72%   |
| Toshiba Satellite C855D                    | 1         | 0.72%   |
| Toshiba Satellite C850-B561                | 1         | 0.72%   |
| Toshiba Satellite C55-B                    | 1         | 0.72%   |
| Toshiba QOSMIO X875                        | 1         | 0.72%   |
| Sony VPCEA36FA                             | 1         | 0.72%   |
| Sony VPCCA35FA                             | 1         | 0.72%   |
| Sony VGN-FZ250E                            | 1         | 0.72%   |
| Sony SVF15A13SAB                           | 1         | 0.72%   |
| Sony SVF153290X                            | 1         | 0.72%   |
| Sony SVF14N13CXB                           | 1         | 0.72%   |
| Samsung 870Z5E/880Z5E/680Z5E               | 1         | 0.72%   |
| Packard Bell EasyNote TJ65                 | 1         | 0.72%   |
| Notebook PD5x_7xPNP_PNN_PNT                | 1         | 0.72%   |
| Notebook NH5xAx                            | 1         | 0.72%   |
| MSI MS-1454                                | 1         | 0.72%   |
| MSI GF63 Thin 8RCS                         | 1         | 0.72%   |
| MSI GF63 Thin 10SC                         | 1         | 0.72%   |
| LG R490-G.ARL5RE2                          | 1         | 0.72%   |
| Lenovo V570 1066AJU                        | 1         | 0.72%   |
| Lenovo V15-IIL 82C5                        | 1         | 0.72%   |
| Lenovo ThinkPad X230 2325OA3               | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003LAD   | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH002JUS   | 1         | 0.72%   |
| Lenovo ThinkPad S1 Yoga 12 20DL0079US      | 1         | 0.72%   |
| Lenovo ThinkPad P52s 20LBS0JC00            | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11        | 7.91%   |
| Dell Inspiron         | 11        | 7.91%   |
| ASUS VivoBook         | 10        | 7.19%   |
| Acer Aspire           | 8         | 5.76%   |
| Toshiba Satellite     | 6         | 4.32%   |
| HP Pavilion           | 5         | 3.6%    |
| HP Laptop             | 5         | 3.6%    |
| Dell Latitude         | 5         | 3.6%    |
| Lenovo IdeaPad        | 4         | 2.88%   |
| HP 15                 | 3         | 2.16%   |
| Dell Vostro           | 3         | 2.16%   |
| Dell G3               | 3         | 2.16%   |
| ASUS ROG              | 3         | 2.16%   |
| Unknown               | 3         | 2.16%   |
| MSI GF63              | 2         | 1.44%   |
| HP Notebook           | 2         | 1.44%   |
| Dell XPS              | 2         | 1.44%   |
| ASUS TUF              | 2         | 1.44%   |
| Valve Jupiter         | 1         | 0.72%   |
| Toshiba QOSMIO        | 1         | 0.72%   |
| Sony VPCEA36FA        | 1         | 0.72%   |
| Sony VPCCA35FA        | 1         | 0.72%   |
| Sony VGN-FZ250E       | 1         | 0.72%   |
| Sony SVF15A13SAB      | 1         | 0.72%   |
| Sony SVF153290X       | 1         | 0.72%   |
| Sony SVF14N13CXB      | 1         | 0.72%   |
| Samsung 870Z5E        | 1         | 0.72%   |
| Packard Bell EasyNote | 1         | 0.72%   |
| Notebook PD5x         | 1         | 0.72%   |
| Notebook NH5xAx       | 1         | 0.72%   |
| MSI MS-1454           | 1         | 0.72%   |
| LG R490-G.ARL5RE2     | 1         | 0.72%   |
| Lenovo V570           | 1         | 0.72%   |
| Lenovo V15-IIL        | 1         | 0.72%   |
| Lenovo ThinkBook      | 1         | 0.72%   |
| Lenovo Legion         | 1         | 0.72%   |
| Lenovo Flex           | 1         | 0.72%   |
| Lenovo B590           | 1         | 0.72%   |
| I-Life Digital ZED    | 1         | 0.72%   |
| HUAWEI RLEF-XX        | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 21        | 15.11%  |
| 2019 | 18        | 12.95%  |
| 2020 | 12        | 8.63%   |
| 2011 | 11        | 7.91%   |
| 2021 | 10        | 7.19%   |
| 2012 | 10        | 7.19%   |
| 2014 | 9         | 6.47%   |
| 2013 | 9         | 6.47%   |
| 2017 | 8         | 5.76%   |
| 2010 | 8         | 5.76%   |
| 2016 | 7         | 5.04%   |
| 2015 | 6         | 4.32%   |
| 2022 | 4         | 2.88%   |
| 2009 | 3         | 2.16%   |
| 2008 | 1         | 0.72%   |
| 2007 | 1         | 0.72%   |
| 2002 | 1         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 139       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 125       | 89.29%  |
| Enabled  | 15        | 10.71%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 139       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 40        | 28.37%  |
| 4.01-8.0    | 36        | 25.53%  |
| 8.01-16.0   | 23        | 16.31%  |
| 16.01-24.0  | 22        | 15.6%   |
| 32.01-64.0  | 8         | 5.67%   |
| 1.01-2.0    | 7         | 4.96%   |
| 2.01-3.0    | 4         | 2.84%   |
| 64.01-256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 59        | 38.82%  |
| 2.01-3.0  | 43        | 28.29%  |
| 3.01-4.0  | 22        | 14.47%  |
| 4.01-8.0  | 19        | 12.5%   |
| 0.51-1.0  | 7         | 4.61%   |
| 8.01-16.0 | 2         | 1.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 74.13%  |
| 2      | 30        | 20.98%  |
| 3      | 6         | 4.2%    |
| 0      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 82        | 58.16%  |
| Yes       | 59        | 41.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 76.43%  |
| No        | 33        | 23.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 98.56%  |
| No        | 2         | 1.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 84.17%  |
| No        | 22        | 15.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 139       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Riyadh               | 53        | 36.81%  |
| Jeddah               | 41        | 28.47%  |
| Makkah               | 14        | 9.72%   |
| Medina               | 10        | 6.94%   |
| Dammam               | 7         | 4.86%   |
| Khobar               | 4         | 2.78%   |
| Thuwal               | 3         | 2.08%   |
| Dhahran              | 3         | 2.08%   |
| Al Qatif             | 3         | 2.08%   |
| Ta'if                | 1         | 0.69%   |
| Sayhat               | 1         | 0.69%   |
| Buraidah             | 1         | 0.69%   |
| Baq`a' ash Sharqiyah | 1         | 0.69%   |
| Al Hufuf             | 1         | 0.69%   |
| Al Faruq             | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 32        | 39     | 18.71%  |
| Toshiba                   | 25        | 31     | 14.62%  |
| WDC                       | 20        | 26     | 11.7%   |
| Samsung Electronics       | 20        | 25     | 11.7%   |
| Kingston                  | 14        | 16     | 8.19%   |
| SanDisk                   | 9         | 9      | 5.26%   |
| Unknown                   | 8         | 9      | 4.68%   |
| SK hynix                  | 6         | 8      | 3.51%   |
| Intel                     | 5         | 10     | 2.92%   |
| Crucial                   | 3         | 4      | 1.75%   |
| Micron/Crucial Technology | 2         | 2      | 1.17%   |
| KingSpec                  | 2         | 2      | 1.17%   |
| JMicron Technology        | 2         | 2      | 1.17%   |
| Hitachi                   | 2         | 2      | 1.17%   |
| Hewlett-Packard           | 2         | 2      | 1.17%   |
| Fujitsu                   | 2         | 3      | 1.17%   |
| Apple                     | 2         | 3      | 1.17%   |
| YMTC                      | 1         | 1      | 0.58%   |
| XrayDisk                  | 1         | 1      | 0.58%   |
| SPCC                      | 1         | 1      | 0.58%   |
| Silicon Motion            | 1         | 1      | 0.58%   |
| PNY                       | 1         | 1      | 0.58%   |
| Phison                    | 1         | 1      | 0.58%   |
| OYUNKEY                   | 1         | 1      | 0.58%   |
| Micron Technology         | 1         | 1      | 0.58%   |
| Lexar                     | 1         | 1      | 0.58%   |
| KIOXIA                    | 1         | 1      | 0.58%   |
| G-DRIVE                   | 1         | 1      | 0.58%   |
| Fanxiang                  | 1         | 1      | 0.58%   |
| China                     | 1         | 1      | 0.58%   |
| Biostar                   | 1         | 1      | 0.58%   |
| A-DATA Technology         | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 13        | 7.34%   |
| Toshiba MQ04ABF100 1TB                              | 10        | 5.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 2.82%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.82%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 2.26%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 1.69%   |
| SanDisk NVMe SSD Drive 128GB                        | 3         | 1.69%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.13%   |
| Unknown MMC Card  16GB                              | 2         | 1.13%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 1.13%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 1.13%   |
| SK hynix NVMe SSD Drive 1024GB                      | 2         | 1.13%   |
| Seagate ST9500325AS 500GB                           | 2         | 1.13%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 1.13%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 1.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 1.13%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 1.13%   |
| JMicron Tech 250GB                                  | 2         | 1.13%   |
| Intel SSDPEKNW512G8 512GB                           | 2         | 1.13%   |
| Intel NVMe SSD Drive 1024GB                         | 2         | 1.13%   |
| HP SSD S700 1TB                                     | 2         | 1.13%   |
| YMTC PC005 256GB                                    | 1         | 0.56%   |
| XrayDisk SSD 1TB                                    | 1         | 0.56%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.56%   |
| WDC WDS100T3X0C-00SJG0 1TB                          | 1         | 0.56%   |
| WDC WD5000LPVX-08V0TT6 500GB                        | 1         | 0.56%   |
| WDC WD5000LPCX-00VHAT0 500GB                        | 1         | 0.56%   |
| WDC WD5000BEVT-08A0RT1 500GB                        | 1         | 0.56%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 0.56%   |
| WDC WD3200BEVT-00ZCT0 320GB                         | 1         | 0.56%   |
| WDC WD1600BEVT-22ZCT0 160GB                         | 1         | 0.56%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.56%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 0.56%   |
| WDC WD10SPZX-08Z10 1TB                              | 1         | 0.56%   |
| WDC WD10SPZX-00Z10T0 1TB                            | 1         | 0.56%   |
| WDC WD10JPVX-55JC3T3 1TB                            | 1         | 0.56%   |
| WDC WD10JPVX-00JC3T0 1TB                            | 1         | 0.56%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 32        | 39     | 42.67%  |
| Toshiba | 24        | 26     | 32%     |
| WDC     | 15        | 20     | 20%     |
| Hitachi | 2         | 2      | 2.67%   |
| Fujitsu | 2         | 3      | 2.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 11        | 13     | 27.5%   |
| SanDisk             | 5         | 5      | 12.5%   |
| Samsung Electronics | 5         | 5      | 12.5%   |
| Crucial             | 3         | 3      | 7.5%    |
| WDC                 | 2         | 2      | 5%      |
| SK hynix            | 2         | 3      | 5%      |
| KingSpec            | 2         | 2      | 5%      |
| Hewlett-Packard     | 2         | 2      | 5%      |
| XrayDisk            | 1         | 1      | 2.5%    |
| PNY                 | 1         | 1      | 2.5%    |
| OYUNKEY             | 1         | 1      | 2.5%    |
| Lexar               | 1         | 1      | 2.5%    |
| G-DRIVE             | 1         | 1      | 2.5%    |
| China               | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 73        | 90     | 43.71%  |
| NVMe    | 44        | 63     | 26.35%  |
| SSD     | 40        | 43     | 23.95%  |
| MMC     | 8         | 10     | 4.79%   |
| Unknown | 2         | 2      | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 131    | 64.56%  |
| NVMe | 44        | 63     | 27.85%  |
| MMC  | 8         | 10     | 5.06%   |
| SAS  | 4         | 4      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.51-1.0   | 54        | 66     | 49.09%  |
| 0.01-0.5   | 53        | 64     | 48.18%  |
| 1.01-2.0   | 3         | 3      | 2.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 35        | 23.97%  |
| 251-500        | 34        | 23.29%  |
| 101-250        | 34        | 23.29%  |
| 51-100         | 12        | 8.22%   |
| 1-20           | 9         | 6.16%   |
| 21-50          | 7         | 4.79%   |
| 1001-2000      | 7         | 4.79%   |
| More than 3000 | 4         | 2.74%   |
| 2001-3000      | 2         | 1.37%   |
| Unknown        | 2         | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 42.21%  |
| 21-50          | 40        | 25.97%  |
| 101-250        | 16        | 10.39%  |
| 51-100         | 15        | 9.74%   |
| 251-500        | 11        | 7.14%   |
| 501-1000       | 3         | 1.95%   |
| Unknown        | 2         | 1.3%    |
| More than 3000 | 1         | 0.65%   |
| 1001-2000      | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 16.67%  |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 16.67%  |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 16.67%  |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 16.67%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| OYUNKEY SSD 120GB                  | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 50%     |
| Toshiba | 1         | 1      | 16.67%  |
| Seagate | 1         | 1      | 16.67%  |
| OYUNKEY | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Detected | 95        | 134    | 64.19%  |
| Works    | 47        | 68     | 31.76%  |
| Malfunc  | 6         | 6      | 4.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 107       | 66.46%  |
| Samsung Electronics              | 15        | 9.32%   |
| AMD                              | 11        | 6.83%   |
| SanDisk                          | 7         | 4.35%   |
| SK hynix                         | 4         | 2.48%   |
| Micron/Crucial Technology        | 3         | 1.86%   |
| Kingston Technology Company      | 3         | 1.86%   |
| Toshiba America Info Systems     | 2         | 1.24%   |
| Silicon Motion                   | 2         | 1.24%   |
| Yangtze Memory Technologies      | 1         | 0.62%   |
| Silicon Integrated Systems [SiS] | 1         | 0.62%   |
| Realtek Semiconductor            | 1         | 0.62%   |
| Phison Electronics               | 1         | 0.62%   |
| Micron Technology                | 1         | 0.62%   |
| INNOGRIT                         | 1         | 0.62%   |
| Apple                            | 1         | 0.62%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 15        | 8.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 12        | 7.14%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 11        | 6.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 10        | 5.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 9         | 5.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 8         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 8         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 7         | 4.17%   |
| Samsung NVMe SSD Controller 980                                              | 7         | 4.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 6         | 3.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 5         | 2.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 5         | 2.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 4         | 2.38%   |
| SanDisk PC SN520 NVMe SSD                                                    | 3         | 1.79%   |
| Intel SSD 660P Series                                                        | 3         | 1.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 3         | 1.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 2         | 1.19%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 2         | 1.19%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                              | 2         | 1.19%   |
| Micron/Crucial P1 NVMe PCIe SSD                                              | 2         | 1.19%   |
| Kingston Company Company Non-Volatile memory controller                      | 2         | 1.19%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 2         | 1.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 2         | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                        | 2         | 1.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 2         | 1.19%   |
| Yangtze Memory Non-Volatile memory controller                                | 1         | 0.6%    |
| SK hynix PC300 NVMe Solid State Drive 1TB                                    | 1         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 0.6%    |
| Silicon Motion Non-Volatile memory controller                                | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                         | 1         | 0.6%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                   | 1         | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.6%    |
| Samsung Electronics SATA controller                                          | 1         | 0.6%    |
| Realtek NVMe Controller                                                      | 1         | 0.6%    |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 0.6%    |
| Micron/Crucial NVMe Storage Controller                                       | 1         | 0.6%    |
| Micron NVMe Storage Controller                                               | 1         | 0.6%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 102       | 63.35%  |
| NVMe | 44        | 27.33%  |
| RAID | 9         | 5.59%   |
| IDE  | 6         | 3.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 87.05%  |
| AMD    | 18        | 12.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 5.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 2.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 2.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.16%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 2.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.16%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 2.16%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 2.16%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 2.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.16%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.44%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 2         | 1.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.44%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.44%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.44%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.44%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.44%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1.44%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.44%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.44%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.44%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 1.44%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.44%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.72%   |
| Intel Pentium CPU N3510 @ 1.99GHz             | 1         | 0.72%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.72%   |
| Intel Mobile Pentium 4 - M CPU 2.20GHz        | 1         | 0.72%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.72%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 30.22%  |
| Intel Core i7           | 37        | 26.62%  |
| Intel Core i3           | 12        | 8.63%   |
| Intel Celeron           | 11        | 7.91%   |
| Other                   | 8         | 5.76%   |
| AMD Ryzen 5             | 8         | 5.76%   |
| AMD Ryzen 7             | 4         | 2.88%   |
| Intel Core 2 Duo        | 3         | 2.16%   |
| Intel Atom              | 3         | 2.16%   |
| AMD Ryzen 9             | 3         | 2.16%   |
| Intel Pentium Dual-Core | 2         | 1.44%   |
| Intel Pentium           | 2         | 1.44%   |
| Intel Mobile Pentium 4  | 1         | 0.72%   |
| Intel Core i9           | 1         | 0.72%   |
| AMD E2                  | 1         | 0.72%   |
| AMD A12                 | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 76        | 54.68%  |
| 4      | 39        | 28.06%  |
| 6      | 11        | 7.91%   |
| 8      | 7         | 5.04%   |
| 1      | 4         | 2.88%   |
| 14     | 2         | 1.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 139       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 111       | 79.86%  |
| 1      | 27        | 19.42%  |
| 8      | 1         | 0.72%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 134       | 95.71%  |
| Unknown        | 4         | 2.86%   |
| 32-bit         | 2         | 1.43%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 27.59%  |
| 0x40651    | 11        | 7.59%   |
| 0x306a9    | 11        | 7.59%   |
| 0x206a7    | 9         | 6.21%   |
| 0x806ec    | 6         | 4.14%   |
| 0x406e3    | 6         | 4.14%   |
| 0x806ea    | 5         | 3.45%   |
| 0x806c1    | 5         | 3.45%   |
| 0x706a1    | 5         | 3.45%   |
| 0x1067a    | 5         | 3.45%   |
| 0x806e9    | 4         | 2.76%   |
| 0x306d4    | 4         | 2.76%   |
| 0x20655    | 4         | 2.76%   |
| 0xa0652    | 3         | 2.07%   |
| 0x906ea    | 3         | 2.07%   |
| 0x706e5    | 3         | 2.07%   |
| 0x30673    | 3         | 2.07%   |
| 0x20652    | 3         | 2.07%   |
| 0x08108109 | 3         | 2.07%   |
| 0x906a3    | 2         | 1.38%   |
| 0xf27      | 1         | 0.69%   |
| 0x906e9    | 1         | 0.69%   |
| 0x806eb    | 1         | 0.69%   |
| 0x6fa      | 1         | 0.69%   |
| 0x306c3    | 1         | 0.69%   |
| 0x08701013 | 1         | 0.69%   |
| 0x08600106 | 1         | 0.69%   |
| 0x08600104 | 1         | 0.69%   |
| 0x0810100b | 1         | 0.69%   |
| 0x0600611a | 1         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 22.3%   |
| IvyBridge        | 12        | 8.63%   |
| Haswell          | 12        | 8.63%   |
| SandyBridge      | 11        | 7.91%   |
| Westmere         | 8         | 5.76%   |
| Skylake          | 8         | 5.76%   |
| Goldmont plus    | 8         | 5.76%   |
| Zen+             | 6         | 4.32%   |
| Zen 3            | 5         | 3.6%    |
| TigerLake        | 5         | 3.6%    |
| Penryn           | 5         | 3.6%    |
| Broadwell        | 5         | 3.6%    |
| CometLake        | 4         | 2.88%   |
| Zen 2            | 3         | 2.16%   |
| Silvermont       | 3         | 2.16%   |
| IceLake          | 3         | 2.16%   |
| Alderlake Hybrid | 2         | 1.44%   |
| Zen              | 1         | 0.72%   |
| NetBurst         | 1         | 0.72%   |
| Goldmont         | 1         | 0.72%   |
| Excavator        | 1         | 0.72%   |
| Core             | 1         | 0.72%   |
| Bonnell          | 1         | 0.72%   |
| Bobcat           | 1         | 0.72%   |
| Unknown          | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 115       | 60.53%  |
| Nvidia                           | 42        | 22.11%  |
| AMD                              | 32        | 16.84%  |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 12        | 6.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 5.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 10        | 5.24%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 8         | 4.19%   |
| Intel UHD Graphics 620                                                        | 7         | 3.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 3.66%   |
| Intel HD Graphics 620                                                         | 7         | 3.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 3.66%   |
| Intel Core Processor Integrated Graphics Controller                           | 6         | 3.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6         | 3.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 5         | 2.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 2.62%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 2.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 2.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 4         | 2.09%   |
| Intel HD Graphics 5500                                                        | 4         | 2.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 2.09%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 4         | 2.09%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 1.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 3         | 1.57%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 3         | 1.57%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]              | 3         | 1.57%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 1.05%   |
| Nvidia GP108M [GeForce MX230]                                                 | 2         | 1.05%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 2         | 1.05%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 2         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 2         | 1.05%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 2         | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 2         | 1.05%   |
| AMD Renoir                                                                    | 2         | 1.05%   |
| Silicon Integrated Systems [SiS] 65x/M650/740 PCI/AGP VGA Display Adapter     | 1         | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.52%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                       | 1         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                        | 1         | 0.52%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                         | 1         | 0.52%   |
| Nvidia GP108GLM [Quadro P500 Mobile]                                          | 1         | 0.52%   |
| Nvidia GP107M [GeForce MX350]                                                 | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 50.71%  |
| Intel + Nvidia | 33        | 23.57%  |
| 1 x AMD        | 16        | 11.43%  |
| Intel + AMD    | 11        | 7.86%   |
| AMD + Nvidia   | 5         | 3.57%   |
| 1 x Nvidia     | 3         | 2.14%   |
| 1 x SiS        | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 121       | 84.62%  |
| Proprietary | 21        | 14.69%  |
| Unknown     | 1         | 0.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 68.57%  |
| 1.01-2.0   | 20        | 14.29%  |
| 3.01-4.0   | 8         | 5.71%   |
| 0.51-1.0   | 7         | 5%      |
| 0.01-0.5   | 4         | 2.86%   |
| 2.01-3.0   | 3         | 2.14%   |
| 7.01-8.0   | 2         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 41        | 27.7%   |
| LG Display              | 25        | 16.89%  |
| AU Optronics            | 23        | 15.54%  |
| Chimei Innolux          | 19        | 12.84%  |
| Samsung Electronics     | 9         | 6.08%   |
| Lenovo                  | 4         | 2.7%    |
| Dell                    | 4         | 2.7%    |
| Sharp                   | 3         | 2.03%   |
| PANDA                   | 3         | 2.03%   |
| Apple                   | 3         | 2.03%   |
| Unknown                 | 2         | 1.35%   |
| Sony                    | 2         | 1.35%   |
| ___                     | 1         | 0.68%   |
| ViewSonic               | 1         | 0.68%   |
| Valve                   | 1         | 0.68%   |
| SKY                     | 1         | 0.68%   |
| InnoLux Display         | 1         | 0.68%   |
| InfoVision              | 1         | 0.68%   |
| Goldstar                | 1         | 0.68%   |
| Chi Mei Optoelectronics | 1         | 0.68%   |
| ASUSTek Computer        | 1         | 0.68%   |
| Ancor Communications    | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 4         | 2.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 2.01%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.01%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 2.01%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                 | 3         | 2.01%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 2.01%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.01%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 1.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.34%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.34%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                 | 2         | 1.34%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.34%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 2         | 1.34%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.67%   |
| ViewSonic VA712-2SERIES VSC941C 1280x1024 338x270mm 17.0-inch         | 1         | 0.67%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.67%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                  | 1         | 0.67%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.67%   |
| Sony TV SNYAC03 1360x768                                              | 1         | 0.67%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.67%   |
| SKY LCDTV SKY0001 1920x540 708x398mm 32.0-inch                        | 1         | 0.67%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4147 3840x2160 294x165mm 13.3-inch | 1         | 0.67%   |
| Samsung Electronics CF791 SAM0DC3 3440x1440 797x333mm 34.0-inch       | 1         | 0.67%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.67%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.67%   |
| LG Display LCD Monitor LGD065B 1920x1080 382x215mm 17.3-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD05E8 1920x1080 344x194mm 15.5-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD04B6 1366x768 309x174mm 14.0-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 64        | 44.76%  |
| 1920x1080 (FHD)   | 56        | 39.16%  |
| 3840x2160 (4K)    | 4         | 2.8%    |
| 2560x1440 (QHD)   | 3         | 2.1%    |
| 2160x1440         | 2         | 1.4%    |
| 1920x1200 (WUXGA) | 2         | 1.4%    |
| 1440x900 (WXGA+)  | 2         | 1.4%    |
| 1360x768          | 2         | 1.4%    |
| 800x1280          | 1         | 0.7%    |
| 3840x2400         | 1         | 0.7%    |
| 3440x1440         | 1         | 0.7%    |
| 2880x1800         | 1         | 0.7%    |
| 2560x1600         | 1         | 0.7%    |
| 1600x900 (HD+)    | 1         | 0.7%    |
| 1280x800 (WXGA)   | 1         | 0.7%    |
| 1280x1024 (SXGA)  | 1         | 0.7%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 83        | 55.7%   |
| 13      | 24        | 16.11%  |
| 14      | 16        | 10.74%  |
| 24      | 5         | 3.36%   |
| 12      | 4         | 2.68%   |
| 17      | 3         | 2.01%   |
| 16      | 3         | 2.01%   |
| 72      | 2         | 1.34%   |
| 27      | 2         | 1.34%   |
| 54      | 1         | 0.67%   |
| 40      | 1         | 0.67%   |
| 34      | 1         | 0.67%   |
| 31      | 1         | 0.67%   |
| 23      | 1         | 0.67%   |
| 7       | 1         | 0.67%   |
| Unknown | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 115       | 78.77%  |
| 201-300     | 11        | 7.53%   |
| 501-600     | 6         | 4.11%   |
| 351-400     | 6         | 4.11%   |
| 1501-2000   | 2         | 1.37%   |
| 801-900     | 1         | 0.68%   |
| 701-800     | 1         | 0.68%   |
| 601-700     | 1         | 0.68%   |
| 1001-1500   | 1         | 0.68%   |
| 1-100       | 1         | 0.68%   |
| Unknown     | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 122       | 91.04%  |
| 16/10 | 7         | 5.22%   |
| 3/2   | 2         | 1.49%   |
| 5/4   | 1         | 0.75%   |
| 21/9  | 1         | 0.75%   |
| 0.67  | 1         | 0.75%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 83        | 55.7%   |
| 81-90          | 36        | 24.16%  |
| 71-80          | 4         | 2.68%   |
| 61-70          | 4         | 2.68%   |
| 201-250        | 4         | 2.68%   |
| More than 1000 | 3         | 2.01%   |
| 351-500        | 2         | 1.34%   |
| 301-350        | 2         | 1.34%   |
| 251-300        | 2         | 1.34%   |
| 121-130        | 2         | 1.34%   |
| 111-120        | 2         | 1.34%   |
| 1-40           | 1         | 0.67%   |
| 141-150        | 1         | 0.67%   |
| 501-1000       | 1         | 0.67%   |
| 91-100         | 1         | 0.67%   |
| Unknown        | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 62        | 42.76%  |
| 121-160       | 54        | 37.24%  |
| 51-100        | 13        | 8.97%   |
| 161-240       | 8         | 5.52%   |
| More than 240 | 4         | 2.76%   |
| 1-50          | 3         | 2.07%   |
| Unknown       | 1         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 124       | 87.32%  |
| 2     | 11        | 7.75%   |
| 3     | 3         | 2.11%   |
| 0     | 3         | 2.11%   |
| 4     | 1         | 0.7%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 91        | 40.99%  |
| Intel                            | 51        | 22.97%  |
| Qualcomm Atheros                 | 41        | 18.47%  |
| Broadcom                         | 14        | 6.31%   |
| Ralink                           | 5         | 2.25%   |
| Samsung Electronics              | 3         | 1.35%   |
| MediaTek                         | 3         | 1.35%   |
| Ralink Technology                | 2         | 0.9%    |
| Marvell Technology Group         | 2         | 0.9%    |
| Broadcom Limited                 | 2         | 0.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.45%   |
| Qualcomm                         | 1         | 0.45%   |
| OPPO Electronics                 | 1         | 0.45%   |
| Microsoft                        | 1         | 0.45%   |
| ICS Advent                       | 1         | 0.45%   |
| Dell                             | 1         | 0.45%   |
| ASIX Electronics                 | 1         | 0.45%   |
| Apple                            | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 19.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 9.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 5.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 4.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 3.11%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.95%   |
| Intel Wireless 8260                                               | 4         | 1.56%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.17%   |
| Intel Wireless 7265                                               | 3         | 1.17%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 1.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.17%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.17%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.78%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 2         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.78%   |
| Intel Wireless 7260                                               | 2         | 0.78%   |
| Intel Wireless 3165                                               | 2         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.78%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller           | 1         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.39%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.39%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 1         | 0.39%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 34.97%  |
| Qualcomm Atheros      | 36        | 25.17%  |
| Realtek Semiconductor | 33        | 23.08%  |
| Broadcom              | 10        | 6.99%   |
| Ralink                | 5         | 3.5%    |
| MediaTek              | 3         | 2.1%    |
| Ralink Technology     | 2         | 1.4%    |
| Broadcom Limited      | 2         | 1.4%    |
| Qualcomm              | 1         | 0.7%    |
| Dell                  | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 9.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 8.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 5.59%   |
| Intel Wireless 8265 / 8275                                     | 6         | 4.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 3.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 3.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.5%    |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 3.5%    |
| Intel Wireless 8260                                            | 4         | 2.8%    |
| Intel Wi-Fi 6 AX200                                            | 4         | 2.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 2.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.1%    |
| Intel Wireless 7265                                            | 3         | 2.1%    |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 2.1%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 3         | 2.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.1%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 1.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 1.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.4%    |
| Intel Wireless 7260                                            | 2         | 1.4%    |
| Intel Wireless 3165                                            | 2         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.7%    |
| Realtek RTL8187B Wireless Adapter                              | 1         | 0.7%    |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.7%    |
| Ralink RT2070 Wireless Adapter                                 | 1         | 0.7%    |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                   | 1         | 0.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.7%    |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 77        | 68.14%  |
| Intel                            | 12        | 10.62%  |
| Qualcomm Atheros                 | 7         | 6.19%   |
| Broadcom                         | 6         | 5.31%   |
| Samsung Electronics              | 3         | 2.65%   |
| Marvell Technology Group         | 2         | 1.77%   |
| Silicon Integrated Systems [SiS] | 1         | 0.88%   |
| OPPO Electronics                 | 1         | 0.88%   |
| Microsoft                        | 1         | 0.88%   |
| ICS Advent                       | 1         | 0.88%   |
| ASIX Electronics                 | 1         | 0.88%   |
| Apple                            | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 50        | 44.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 22.12%  |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 2.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 2.65%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.77%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.77%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.88%   |
| Realtek PCIe GbE Family Controller                                             | 1         | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.88%   |
| OPPO RMX3263                                                                   | 1         | 0.88%   |
| Microsoft RTL8153B GigE [Surface Ethernet Adapter]                             | 1         | 0.88%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.88%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.88%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.88%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.88%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.88%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.88%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.88%   |
| Apple iPad 4/Mini1                                                             | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 55.92%  |
| Ethernet | 107       | 43.67%  |
| Modem    | 1         | 0.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 117       | 81.25%  |
| Ethernet | 27        | 18.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 72.66%  |
| 1     | 36        | 25.9%   |
| 0     | 2         | 1.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 76.06%  |
| Yes  | 34        | 23.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 33.05%  |
| Qualcomm Atheros Communications | 18        | 15.25%  |
| Realtek Semiconductor           | 14        | 11.86%  |
| IMC Networks                    | 12        | 10.17%  |
| Foxconn / Hon Hai               | 10        | 8.47%   |
| Lite-On Technology              | 6         | 5.08%   |
| Toshiba                         | 4         | 3.39%   |
| Broadcom                        | 4         | 3.39%   |
| Ralink                          | 3         | 2.54%   |
| Realtek                         | 2         | 1.69%   |
| Dell                            | 2         | 1.69%   |
| Apple                           | 2         | 1.69%   |
| Ralink Technology               | 1         | 0.85%   |
| Qcom                            | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 15.25%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 7.63%   |
| Realtek Bluetooth Radio                                                             | 8         | 6.78%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 5.93%   |
| Intel AX201 Bluetooth                                                               | 7         | 5.93%   |
| IMC Networks Bluetooth Device                                                       | 6         | 5.08%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.24%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 4.24%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 2.54%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 2.54%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.54%   |
| Intel AX200 Bluetooth                                                               | 3         | 2.54%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 2.54%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.69%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.69%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.69%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.69%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.85%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.85%   |
| Toshiba Askey for                                                                   | 1         | 0.85%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.85%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.85%   |
| Ralink CSR BS8510                                                                   | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.85%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.85%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.85%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.85%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.85%   |
| Lite-On BCM43142A0                                                                  | 1         | 0.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.85%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.85%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.85%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 118       | 71.95%  |
| Nvidia                           | 21        | 12.8%   |
| AMD                              | 21        | 12.8%   |
| Silicon Integrated Systems [SiS] | 1         | 0.61%   |
| Samson Technologies              | 1         | 0.61%   |
| Nreal                            | 1         | 0.61%   |
| Cooler Master                    | 1         | 0.61%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 22        | 11.28%  |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 7.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 6.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 5.64%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 5.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 5.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 4.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 4.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.59%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.56%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.56%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 1.03%   |
| Nvidia Audio device                                                        | 2         | 1.03%   |
| Intel CM238 HD Audio Controller                                            | 2         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.03%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller            | 1         | 0.51%   |
| Samson Technologies GoMic compact condenser mic                            | 1         | 0.51%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.51%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.51%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.51%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.51%   |
| Nreal Air                                                                  | 1         | 0.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.51%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller            | 1         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 20        | 27.03%  |
| SK hynix                             | 15        | 20.27%  |
| Micron Technology                    | 10        | 13.51%  |
| Crucial                              | 6         | 8.11%   |
| Unknown                              | 5         | 6.76%   |
| Kingston                             | 5         | 6.76%   |
| Elpida                               | 2         | 2.7%    |
| Unknown (ABCD)                       | 1         | 1.35%   |
| Toshiba                              | 1         | 1.35%   |
| Team                                 | 1         | 1.35%   |
| Silicon Power                        | 1         | 1.35%   |
| Ramaxel Technology                   | 1         | 1.35%   |
| Patriot Memory (PDP Systems)         | 1         | 1.35%   |
| Nanya Technology                     | 1         | 1.35%   |
| KLEVV                                | 1         | 1.35%   |
| Hikvision                            | 1         | 1.35%   |
| Chun Well Technology Holding Limited | 1         | 1.35%   |
| ASint Technology                     | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 3.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 2.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.56%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 2.56%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 1.28%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.28%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 1.28%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 1.28%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.28%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 1.28%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.28%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.28%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 1.28%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 1         | 1.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.28%   |
| SK hynix RAM HMT112S6TFR8C-G7 1GB SODIMM DDR3 1067MT/s           | 1         | 1.28%   |
| SK hynix RAM HMP125S6EFR8C-S6 2GB SODIMM DDR2 800MT/s            | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.28%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.28%   |
| Silicon Power RAM DBST8GN128S 8GB SODIMM DDR3 1333MT/s           | 1         | 1.28%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471B1G73CB0-CK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.28%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 27        | 45%     |
| DDR3    | 23        | 38.33%  |
| LPDDR4  | 3         | 5%      |
| DDR2    | 3         | 5%      |
| LPDDR3  | 2         | 3.33%   |
| SDRAM   | 1         | 1.67%   |
| Unknown | 1         | 1.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 91.53%  |
| Row Of Chips | 5         | 8.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 34.85%  |
| 4096  | 23        | 34.85%  |
| 2048  | 9         | 13.64%  |
| 16384 | 8         | 12.12%  |
| 1024  | 2         | 3.03%   |
| 32768 | 1         | 1.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 14        | 20%     |
| 2667    | 13        | 18.57%  |
| 3200    | 11        | 15.71%  |
| 1334    | 7         | 10%     |
| 2400    | 4         | 5.71%   |
| 2133    | 4         | 5.71%   |
| 1333    | 4         | 5.71%   |
| 3266    | 3         | 4.29%   |
| 4267    | 2         | 2.86%   |
| 1067    | 2         | 2.86%   |
| 800     | 2         | 2.86%   |
| 4199    | 1         | 1.43%   |
| 1066    | 1         | 1.43%   |
| 975     | 1         | 1.43%   |
| Unknown | 1         | 1.43%   |

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
| Chicony Electronics                    | 23        | 19.49%  |
| IMC Networks                           | 22        | 18.64%  |
| Microdia                               | 13        | 11.02%  |
| Realtek Semiconductor                  | 9         | 7.63%   |
| Acer                                   | 9         | 7.63%   |
| Sunplus Innovation Technology          | 8         | 6.78%   |
| Suyin                                  | 6         | 5.08%   |
| Lite-On Technology                     | 6         | 5.08%   |
| Quanta                                 | 5         | 4.24%   |
| Importek                               | 3         | 2.54%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.54%   |
| Ricoh                                  | 2         | 1.69%   |
| Apple                                  | 2         | 1.69%   |
| Alcor Micro                            | 2         | 1.69%   |
| Silicon Motion                         | 1         | 0.85%   |
| Samsung Electronics                    | 1         | 0.85%   |
| Luxvisions Innotech Limited            | 1         | 0.85%   |
| Logitech                               | 1         | 0.85%   |
| Lenovo                                 | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 12        | 10.17%  |
| Chicony Integrated Camera                           | 8         | 6.78%   |
| Microdia Integrated_Webcam_HD                       | 7         | 5.93%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 5.08%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 3.39%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.54%   |
| Lite-On HP TrueVision HD Camera                     | 3         | 2.54%   |
| Acer Integrated Camera                              | 3         | 2.54%   |
| Suyin 1.3M HD WebCam                                | 2         | 1.69%   |
| Sunplus HD WebCam                                   | 2         | 1.69%   |
| Realtek Integrated Webcam                           | 2         | 1.69%   |
| Realtek HP Truevision HD integrated webcam          | 2         | 1.69%   |
| Microdia HP Integrated Webcam                       | 2         | 1.69%   |
| IMC Networks HD Camera                              | 2         | 1.69%   |
| Chicony HD WebCam                                   | 2         | 1.69%   |
| Chicony Front Camera                                | 2         | 1.69%   |
| Alcor Micro Asus Integrated Webcam                  | 2         | 1.69%   |
| Suyin USB 2.0 Camera                                | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.85%   |
| Suyin HP TrueVision HD                              | 1         | 0.85%   |
| Suyin HP Integrated Webcam                          | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.85%   |
| Sunplus HP Universal Camera                         | 1         | 0.85%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.85%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.85%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 1         | 0.85%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.85%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.85%   |
| Realtek HP Truevision HD                            | 1         | 0.85%   |
| Quanta VGA WebCam                                   | 1         | 0.85%   |
| Quanta ov9734_techfront_camera                      | 1         | 0.85%   |
| Quanta LG Webcam                                    | 1         | 0.85%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.85%   |
| Quanta FHD Camera                                   | 1         | 0.85%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.85%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.85%   |
| Microdia Integrated Webcam HD                       | 1         | 0.85%   |
| Microdia Integrated Webcam                          | 1         | 0.85%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 0.85%   |
| Logitech C922 Pro Stream Webcam                     | 1         | 0.85%   |

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
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 96        | 67.13%  |
| 1     | 40        | 27.97%  |
| 2     | 5         | 3.5%    |
| 4     | 1         | 0.7%    |
| 3     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 31.48%  |
| Graphics card            | 12        | 22.22%  |
| Net/wireless             | 7         | 12.96%  |
| Multimedia controller    | 5         | 9.26%   |
| Chipcard                 | 5         | 9.26%   |
| Bluetooth                | 3         | 5.56%   |
| Camera                   | 2         | 3.7%    |
| Storage                  | 1         | 1.85%   |
| Modem                    | 1         | 1.85%   |
| Communication controller | 1         | 1.85%   |

