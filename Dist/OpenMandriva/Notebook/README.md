OpenMandriva - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 7945

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | X751MA                      | [d5e1758d4e](https://linux-hardware.org/?probe=d5e1758d4e) | Nov 06, 2023 |
| Toshiba       | Satellite C855-10N          | [7afd607141](https://linux-hardware.org/?probe=7afd607141) | Nov 06, 2023 |
| HP            | 255 G7 Notebook PC          | [216faa6f5d](https://linux-hardware.org/?probe=216faa6f5d) | Nov 06, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [37d32a1fd5](https://linux-hardware.org/?probe=37d32a1fd5) | Nov 06, 2023 |
| Dell          | Inspiron 15-3567            | [b42102e397](https://linux-hardware.org/?probe=b42102e397) | Nov 06, 2023 |
| GPU Compan... | GWNR71517                   | [7676ff267d](https://linux-hardware.org/?probe=7676ff267d) | Nov 06, 2023 |
| Dell          | Latitude E6410              | [b6ac4a50b7](https://linux-hardware.org/?probe=b6ac4a50b7) | Nov 06, 2023 |
| HP            | ProBook 640 G1              | [1cc495d15b](https://linux-hardware.org/?probe=1cc495d15b) | Nov 05, 2023 |
| HP            | Compaq 6710b                | [7a0b2fd29b](https://linux-hardware.org/?probe=7a0b2fd29b) | Nov 05, 2023 |
| Apple         | MacBookPro9,2               | [1801a9c841](https://linux-hardware.org/?probe=1801a9c841) | Nov 05, 2023 |
| HP            | ProBook 4330s               | [b22a07c92b](https://linux-hardware.org/?probe=b22a07c92b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | [c74051abb7](https://linux-hardware.org/?probe=c74051abb7) | Nov 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [b0487db7bf](https://linux-hardware.org/?probe=b0487db7bf) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| MSI           | MS-1759                     | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Dell          | Latitude E7450              | [e7effc42ed](https://linux-hardware.org/?probe=e7effc42ed) | Nov 04, 2023 |
| Dell          | Latitude E5450              | [1f23c5fd7c](https://linux-hardware.org/?probe=1f23c5fd7c) | Nov 04, 2023 |
| Toshiba       | TECRA W50-A                 | [ad6c61de24](https://linux-hardware.org/?probe=ad6c61de24) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| HP            | EliteBook 6930p             | [300c72bf93](https://linux-hardware.org/?probe=300c72bf93) | Nov 03, 2023 |
| Dell          | Latitude 3420               | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Unknown       | Unknown                     | [d27cd12013](https://linux-hardware.org/?probe=d27cd12013) | Nov 03, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| ASUSTek       | X550VQ                      | [b6d6ff10aa](https://linux-hardware.org/?probe=b6d6ff10aa) | Nov 03, 2023 |
| Toshiba       | Satellite C650              | [6844fc4fcf](https://linux-hardware.org/?probe=6844fc4fcf) | Nov 03, 2023 |
| HP            | ProBook 6450b               | [a63f28d2be](https://linux-hardware.org/?probe=a63f28d2be) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X411... | [8ac5fd2789](https://linux-hardware.org/?probe=8ac5fd2789) | Nov 02, 2023 |
| Intel         | powered classmate PC        | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e5b852ff3e](https://linux-hardware.org/?probe=e5b852ff3e) | Nov 02, 2023 |
| Google        | Falco                       | [0ea6d932bf](https://linux-hardware.org/?probe=0ea6d932bf) | Nov 01, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [11c06a97d7](https://linux-hardware.org/?probe=11c06a97d7) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | [165be504bf](https://linux-hardware.org/?probe=165be504bf) | Nov 01, 2023 |
| Lenovo        | ThinkPad T430 23493V2       | [0d5b87b380](https://linux-hardware.org/?probe=0d5b87b380) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| Framework     | Laptop                      | [eb0a6abacc](https://linux-hardware.org/?probe=eb0a6abacc) | Nov 01, 2023 |
| Dell          | Inspiron 3542               | [87ec116ea6](https://linux-hardware.org/?probe=87ec116ea6) | Nov 01, 2023 |
| Acer          | Predator PH18-71            | [a0393f21c9](https://linux-hardware.org/?probe=a0393f21c9) | Nov 01, 2023 |
| HP            | EliteBook 840 G3            | [a09d649781](https://linux-hardware.org/?probe=a09d649781) | Nov 01, 2023 |
| Acer          | Aspire E5-576G              | [c0626d553b](https://linux-hardware.org/?probe=c0626d553b) | Oct 30, 2023 |
| Dell          | Latitude 7480               | [fcae1c21f4](https://linux-hardware.org/?probe=fcae1c21f4) | Oct 30, 2023 |
| ASUSTek       | X555LD                      | [2c79650ee2](https://linux-hardware.org/?probe=2c79650ee2) | Oct 29, 2023 |
| Samsung       | RC410/RC510/RC710           | [3cc0feaa4e](https://linux-hardware.org/?probe=3cc0feaa4e) | Oct 29, 2023 |
| Acer          | AOD270                      | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS5E018    | [98c446abbd](https://linux-hardware.org/?probe=98c446abbd) | Oct 29, 2023 |
| Dell          | XPS 15 9570                 | [17de10e607](https://linux-hardware.org/?probe=17de10e607) | Oct 29, 2023 |
| HP            | Laptop 15-da0xxx            | [39d06d7acf](https://linux-hardware.org/?probe=39d06d7acf) | Oct 28, 2023 |
| Dell          | Inspiron MM061              | [7545369484](https://linux-hardware.org/?probe=7545369484) | Oct 28, 2023 |
| HP            | Pavilion g6                 | [ecc6e8d906](https://linux-hardware.org/?probe=ecc6e8d906) | Oct 28, 2023 |
| Samsung       | 370E4K                      | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [e3154e94cf](https://linux-hardware.org/?probe=e3154e94cf) | Oct 28, 2023 |
| ASUSTek       | X101                        | [dab1a6368d](https://linux-hardware.org/?probe=dab1a6368d) | Oct 27, 2023 |
| Fujitsu       | LIFEBOOK S792               | [5eaa7922e7](https://linux-hardware.org/?probe=5eaa7922e7) | Oct 27, 2023 |
| Dell          | Precision M6800             | [e8fd7cce51](https://linux-hardware.org/?probe=e8fd7cce51) | Oct 27, 2023 |
| Toshiba       | dynabook T350/56ARK         | [802dacc8cc](https://linux-hardware.org/?probe=802dacc8cc) | Oct 27, 2023 |
| MSI           | GL73 8RD                    | [62d3ea64dd](https://linux-hardware.org/?probe=62d3ea64dd) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [3a2901251b](https://linux-hardware.org/?probe=3a2901251b) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| Apple         | MacBookPro6,2               | [af9b5b05e9](https://linux-hardware.org/?probe=af9b5b05e9) | Oct 26, 2023 |
| Apple         | MacBookPro7,1               | [cb27a04bd5](https://linux-hardware.org/?probe=cb27a04bd5) | Oct 26, 2023 |
| HP            | Pavilion g6                 | [00e978bda2](https://linux-hardware.org/?probe=00e978bda2) | Oct 26, 2023 |
| HP            | 650                         | [0625bd022d](https://linux-hardware.org/?probe=0625bd022d) | Oct 26, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | [39250155c4](https://linux-hardware.org/?probe=39250155c4) | Oct 26, 2023 |
| Toshiba       | Satellite C670D-126         | [b117860daf](https://linux-hardware.org/?probe=b117860daf) | Oct 25, 2023 |
| NEC Comput... | PC-VJ22LFWZHSRF             | [b229c83a28](https://linux-hardware.org/?probe=b229c83a28) | Oct 25, 2023 |
| ASUSTek       | X551CAP                     | [bff9909d9b](https://linux-hardware.org/?probe=bff9909d9b) | Oct 24, 2023 |
| HP            | Laptop 17-by2xxx            | [9f728690ee](https://linux-hardware.org/?probe=9f728690ee) | Oct 24, 2023 |
| HP            | EliteBook 8770w             | [50cab103c8](https://linux-hardware.org/?probe=50cab103c8) | Oct 24, 2023 |
| ASUSTek       | UX303LB                     | [1fdfa51ddc](https://linux-hardware.org/?probe=1fdfa51ddc) | Oct 24, 2023 |
| Lenovo        | G580 2189                   | [18dc8e53d9](https://linux-hardware.org/?probe=18dc8e53d9) | Oct 24, 2023 |
| Dell          | Inspiron 15 3511            | [8d2894b3d1](https://linux-hardware.org/?probe=8d2894b3d1) | Oct 24, 2023 |
| HP            | ProBook 450 G6              | [17c7c26cd0](https://linux-hardware.org/?probe=17c7c26cd0) | Oct 24, 2023 |
| LG Electro... | 17ZT90P-G.AX33U1            | [0d53262cff](https://linux-hardware.org/?probe=0d53262cff) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dc730f5631](https://linux-hardware.org/?probe=dc730f5631) | Oct 23, 2023 |
| Dell          | Inspiron 11 - 3147          | [7be979fc66](https://linux-hardware.org/?probe=7be979fc66) | Oct 23, 2023 |
| Samsung       | RF511/RF411/RF711           | [6a62fa5cb6](https://linux-hardware.org/?probe=6a62fa5cb6) | Oct 23, 2023 |
| Toshiba       | Satellite P55W-C            | [60911595dc](https://linux-hardware.org/?probe=60911595dc) | Oct 23, 2023 |
| Lenovo        | Unknown                     | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| ASUSTek       | UL80VT                      | [7991ecc4ee](https://linux-hardware.org/?probe=7991ecc4ee) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| ASUSTek       | X550LA                      | [10e4a414fd](https://linux-hardware.org/?probe=10e4a414fd) | Oct 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [a02e93f0a5](https://linux-hardware.org/?probe=a02e93f0a5) | Oct 21, 2023 |
| Sony          | VGN-FZ21M                   | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Acer          | Aspire 5742                 | [f30dc155bd](https://linux-hardware.org/?probe=f30dc155bd) | Oct 21, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | [ad7ca8e192](https://linux-hardware.org/?probe=ad7ca8e192) | Oct 21, 2023 |
| HP            | Laptop 15s-eq1xxx           | [5795100325](https://linux-hardware.org/?probe=5795100325) | Oct 21, 2023 |
| Gateway       | NV55C                       | [bb0eb9e5dd](https://linux-hardware.org/?probe=bb0eb9e5dd) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [d3b1d639f5](https://linux-hardware.org/?probe=d3b1d639f5) | Oct 21, 2023 |
| HP            | Pavilion dm1                | [74c8fce8f0](https://linux-hardware.org/?probe=74c8fce8f0) | Oct 21, 2023 |
| Lenovo        | G510 20238                  | [d6bd0eda6d](https://linux-hardware.org/?probe=d6bd0eda6d) | Oct 21, 2023 |
| HP            | TouchSmart tm2              | [a79b82edd3](https://linux-hardware.org/?probe=a79b82edd3) | Oct 21, 2023 |
| Compaq        | 434                         | [094bba21f8](https://linux-hardware.org/?probe=094bba21f8) | Oct 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [314c39b6d1](https://linux-hardware.org/?probe=314c39b6d1) | Oct 21, 2023 |
| Dell          | Inspiron 5559               | [83811b2a84](https://linux-hardware.org/?probe=83811b2a84) | Oct 21, 2023 |
| Toshiba       | Satellite A660              | [a5e343d353](https://linux-hardware.org/?probe=a5e343d353) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| Dell          | G15 5510                    | [5e7232a684](https://linux-hardware.org/?probe=5e7232a684) | Oct 21, 2023 |
| Samsung       | R530/R730/P590              | [6a774fbae7](https://linux-hardware.org/?probe=6a774fbae7) | Oct 21, 2023 |
| Lenovo        | ThinkPad X201 3680V5T       | [b30e261022](https://linux-hardware.org/?probe=b30e261022) | Oct 20, 2023 |
| HP            | Compaq 15                   | [992044ca80](https://linux-hardware.org/?probe=992044ca80) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| Lenovo        | ThinkPad L540 20AUA044FR    | [70d42f0667](https://linux-hardware.org/?probe=70d42f0667) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| Lenovo        | G505s 20255                 | [71bfa98c37](https://linux-hardware.org/?probe=71bfa98c37) | Oct 20, 2023 |
| Acer          | Aspire A114-33              | [34ffce7f83](https://linux-hardware.org/?probe=34ffce7f83) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | [2593407253](https://linux-hardware.org/?probe=2593407253) | Oct 20, 2023 |
| Toshiba       | Satellite P50t-B-118        | [5237c0866e](https://linux-hardware.org/?probe=5237c0866e) | Oct 19, 2023 |
| Acer          | AOD270                      | [b8c4966af7](https://linux-hardware.org/?probe=b8c4966af7) | Oct 19, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [b8ee9cff90](https://linux-hardware.org/?probe=b8ee9cff90) | Oct 19, 2023 |
| Dell          | Vostro 3560                 | [aa95d1c178](https://linux-hardware.org/?probe=aa95d1c178) | Oct 19, 2023 |
| HP            | TouchSmart tm2              | [f72f6a43b5](https://linux-hardware.org/?probe=f72f6a43b5) | Oct 19, 2023 |
| ASUSTek       | X542UR                      | [72390695fd](https://linux-hardware.org/?probe=72390695fd) | Oct 19, 2023 |
| ASUSTek       | X540LJ                      | [a0c126c4ce](https://linux-hardware.org/?probe=a0c126c4ce) | Oct 19, 2023 |
| Dell          | Inspiron 5547               | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| HP            | EliteBook 8570p             | [5cea3b7124](https://linux-hardware.org/?probe=5cea3b7124) | Oct 18, 2023 |
| Dell          | Latitude E6320              | [91e5128fd5](https://linux-hardware.org/?probe=91e5128fd5) | Oct 18, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d8ab8a8fc8](https://linux-hardware.org/?probe=d8ab8a8fc8) | Oct 18, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [501f7abc3b](https://linux-hardware.org/?probe=501f7abc3b) | Oct 18, 2023 |
| Unknown       | Unknown                     | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| HP            | EliteBook 830 G6            | [c9ab502087](https://linux-hardware.org/?probe=c9ab502087) | Oct 17, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | [7e446027c0](https://linux-hardware.org/?probe=7e446027c0) | Oct 17, 2023 |
| HP            | Pavilion Notebook           | [5981bba0dd](https://linux-hardware.org/?probe=5981bba0dd) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [f3bd5c6632](https://linux-hardware.org/?probe=f3bd5c6632) | Oct 17, 2023 |
| Dell          | Vostro 1510                 | [cf920dcf20](https://linux-hardware.org/?probe=cf920dcf20) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| HP            | Folio 13 - 2000             | [c541a1603c](https://linux-hardware.org/?probe=c541a1603c) | Oct 17, 2023 |
| ASUSTek       | N61Jv                       | [cb8a1ca22a](https://linux-hardware.org/?probe=cb8a1ca22a) | Oct 17, 2023 |
| HP            | EliteBook 2760p             | [3d62b547f3](https://linux-hardware.org/?probe=3d62b547f3) | Oct 16, 2023 |
| HP            | 2000                        | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| HP            | 630                         | [db6efff83b](https://linux-hardware.org/?probe=db6efff83b) | Oct 16, 2023 |
| Dell          | Inspiron 1545               | [03670e3e53](https://linux-hardware.org/?probe=03670e3e53) | Oct 16, 2023 |
| Lenovo        | ThinkPad R61 8935AC7        | [fc4f024a54](https://linux-hardware.org/?probe=fc4f024a54) | Oct 16, 2023 |
| Dell          | Latitude E5470              | [0c6b7d2953](https://linux-hardware.org/?probe=0c6b7d2953) | Oct 16, 2023 |
| Sony          | VPCEF2S1E                   | [e4be1dd0e0](https://linux-hardware.org/?probe=e4be1dd0e0) | Oct 16, 2023 |
| MSI           | GT70 0NC/GT70 0NC           | [24e93d9411](https://linux-hardware.org/?probe=24e93d9411) | Oct 15, 2023 |
| Toshiba       | Satellite L655              | [9bda720e30](https://linux-hardware.org/?probe=9bda720e30) | Oct 15, 2023 |
| Dell          | Inspiron 3576               | [28b33e764d](https://linux-hardware.org/?probe=28b33e764d) | Oct 15, 2023 |
| Samsung       | 550XCJ/550XCR               | [579dc4dabc](https://linux-hardware.org/?probe=579dc4dabc) | Oct 15, 2023 |
| HP            | Unknown                     | [cae9b0ba31](https://linux-hardware.org/?probe=cae9b0ba31) | Oct 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [36327d381a](https://linux-hardware.org/?probe=36327d381a) | Oct 14, 2023 |
| Valve         | Jupiter                     | [94366b8682](https://linux-hardware.org/?probe=94366b8682) | Oct 14, 2023 |
| Dell          | Precision 7720              | [574a292adb](https://linux-hardware.org/?probe=574a292adb) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| Notebook      | NJ50_70CU                   | [885120121b](https://linux-hardware.org/?probe=885120121b) | Oct 13, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [d14e3ec320](https://linux-hardware.org/?probe=d14e3ec320) | Oct 13, 2023 |
| Fujitsu       | FMVNS7HE                    | [2408a69be7](https://linux-hardware.org/?probe=2408a69be7) | Oct 13, 2023 |
| Acer          | Aspire A515-45              | [f5e57e4558](https://linux-hardware.org/?probe=f5e57e4558) | Oct 13, 2023 |
| Toshiba       | Satellite L755              | [04b09d7164](https://linux-hardware.org/?probe=04b09d7164) | Oct 12, 2023 |
| Dell          | XPS 13 9360                 | [d227c42e18](https://linux-hardware.org/?probe=d227c42e18) | Oct 12, 2023 |
| HP            | 14                          | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| Lenovo        | IdeaPad P500 20210          | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| Dell          | Latitude E6430              | [802b70a3c0](https://linux-hardware.org/?probe=802b70a3c0) | Oct 11, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [b18b8f45a4](https://linux-hardware.org/?probe=b18b8f45a4) | Oct 11, 2023 |
| Toshiba       | Satellite C870-D7K          | [150f57bc3d](https://linux-hardware.org/?probe=150f57bc3d) | Oct 11, 2023 |
| MSI           | GL75 9SE                    | [bffc7bdfe6](https://linux-hardware.org/?probe=bffc7bdfe6) | Oct 11, 2023 |
| Acer          | Aspire A317-53              | [cfcd99cc4f](https://linux-hardware.org/?probe=cfcd99cc4f) | Oct 10, 2023 |
| Dell          | Latitude E6440              | [7471faa299](https://linux-hardware.org/?probe=7471faa299) | Oct 10, 2023 |
| Dell          | Inspiron 3521               | [290872884b](https://linux-hardware.org/?probe=290872884b) | Oct 10, 2023 |
| Toshiba       | Satellite A665              | [b80211d14f](https://linux-hardware.org/?probe=b80211d14f) | Oct 10, 2023 |
| Medion        | E11201                      | [25afe8c1be](https://linux-hardware.org/?probe=25afe8c1be) | Oct 09, 2023 |
| HP            | 15 TS                       | [a57405a3be](https://linux-hardware.org/?probe=a57405a3be) | Oct 09, 2023 |
| Dell          | Latitude E5440              | [a039ff25ef](https://linux-hardware.org/?probe=a039ff25ef) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| Lenovo        | G580 20150                  | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| HP            | Laptop 15-dw0xxx            | [c6da0d1963](https://linux-hardware.org/?probe=c6da0d1963) | Oct 08, 2023 |
| Acer          | Aspire ES1-572              | [ac5943ef0c](https://linux-hardware.org/?probe=ac5943ef0c) | Oct 08, 2023 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [0f32aa1d9d](https://linux-hardware.org/?probe=0f32aa1d9d) | Oct 08, 2023 |
| HUAWEI        | HLYL-WXX9                   | [89674f77b2](https://linux-hardware.org/?probe=89674f77b2) | Oct 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3EJ0... | [f39067b962](https://linux-hardware.org/?probe=f39067b962) | Oct 07, 2023 |
| Dell          | Precision M2800             | [75b0ab2562](https://linux-hardware.org/?probe=75b0ab2562) | Oct 07, 2023 |
| Toshiba       | Satellite A305D             | [d2fc1d1762](https://linux-hardware.org/?probe=d2fc1d1762) | Oct 07, 2023 |
| HP            | Compaq Presario C768        | [7b364bd566](https://linux-hardware.org/?probe=7b364bd566) | Oct 07, 2023 |
| Acer          | Aspire E1-571G              | [205a84adc9](https://linux-hardware.org/?probe=205a84adc9) | Oct 07, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| Thomson       | WWN15I5-8BK1T               | [10ca155743](https://linux-hardware.org/?probe=10ca155743) | Oct 06, 2023 |
| HP            | Laptop 15s-fq3xxx           | [3cbdc1eb94](https://linux-hardware.org/?probe=3cbdc1eb94) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | [e627afd34e](https://linux-hardware.org/?probe=e627afd34e) | Oct 05, 2023 |
| HP            | ProBook 6450b               | [f597cfe9d1](https://linux-hardware.org/?probe=f597cfe9d1) | Oct 05, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1729f3bfbe](https://linux-hardware.org/?probe=1729f3bfbe) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | [ce99edd92c](https://linux-hardware.org/?probe=ce99edd92c) | Oct 05, 2023 |
| Lenovo        | B50-80 80LT                 | [74b54d0f3f](https://linux-hardware.org/?probe=74b54d0f3f) | Oct 05, 2023 |
| Apple         | MacBookPro13,3              | [171a2ad768](https://linux-hardware.org/?probe=171a2ad768) | Oct 04, 2023 |
| HP            | Pavilion Notebook           | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Apple         | MacBookPro8,2               | [4749aba038](https://linux-hardware.org/?probe=4749aba038) | Oct 04, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [f10db8b926](https://linux-hardware.org/?probe=f10db8b926) | Oct 04, 2023 |
| Dell          | Latitude E6410              | [0b58de80dd](https://linux-hardware.org/?probe=0b58de80dd) | Oct 04, 2023 |
| ASUSTek       | UL80VT                      | [fc4a10d945](https://linux-hardware.org/?probe=fc4a10d945) | Oct 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c40f80d33a](https://linux-hardware.org/?probe=c40f80d33a) | Oct 03, 2023 |
| MSI           | CR620                       | [be490381a9](https://linux-hardware.org/?probe=be490381a9) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3657d65cec](https://linux-hardware.org/?probe=3657d65cec) | Oct 03, 2023 |
| ASUSTek       | X550CL                      | [fc47e59598](https://linux-hardware.org/?probe=fc47e59598) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| HP            | Pavilion g6                 | [7fadaa78cd](https://linux-hardware.org/?probe=7fadaa78cd) | Oct 02, 2023 |
| Apple         | MacBookAir6,2               | [25d2225829](https://linux-hardware.org/?probe=25d2225829) | Oct 02, 2023 |
| Acer          | Nitro AN515-55              | [9bebc42b46](https://linux-hardware.org/?probe=9bebc42b46) | Oct 02, 2023 |
| Lenovo        | G500 20236                  | [fcef55efdf](https://linux-hardware.org/?probe=fcef55efdf) | Oct 01, 2023 |
| Toshiba       | Satellite L775              | [c659fe6fba](https://linux-hardware.org/?probe=c659fe6fba) | Oct 01, 2023 |
| Acer          | Aspire V3-772               | [6e0e08c45e](https://linux-hardware.org/?probe=6e0e08c45e) | Oct 01, 2023 |
| HP            | Laptop 17-cn0xxx            | [aa4b869750](https://linux-hardware.org/?probe=aa4b869750) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2127748080](https://linux-hardware.org/?probe=2127748080) | Oct 01, 2023 |
| Acer          | Aspire A315-58              | [bbab99a4f7](https://linux-hardware.org/?probe=bbab99a4f7) | Sep 30, 2023 |
| Medion        | Deputy P40                  | [7e0fc5b52d](https://linux-hardware.org/?probe=7e0fc5b52d) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Acer          | Aspire 5560                 | [252d19e4f5](https://linux-hardware.org/?probe=252d19e4f5) | Sep 30, 2023 |
| Toshiba       | Satellite L500              | [9c1b258088](https://linux-hardware.org/?probe=9c1b258088) | Sep 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [2edc7ab56b](https://linux-hardware.org/?probe=2edc7ab56b) | Sep 30, 2023 |
| Toshiba       | Satellite C845D             | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Lenovo        | 300s-15ARR 81FB             | [4f7e627fd2](https://linux-hardware.org/?probe=4f7e627fd2) | Sep 30, 2023 |
| Lenovo        | Z50-70 20354                | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| HP            | ENVY TS Sleekbook 4         | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| OEGStone      | C4100/C5100                 | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6348992a72](https://linux-hardware.org/?probe=6348992a72) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| SKIKK         | Sindri 14                   | [9766c80aa9](https://linux-hardware.org/?probe=9766c80aa9) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [902918fb1d](https://linux-hardware.org/?probe=902918fb1d) | Sep 29, 2023 |
| HP            | EliteBook 2760p             | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| HP            | Compaq Presario CQ70        | [8913bbd459](https://linux-hardware.org/?probe=8913bbd459) | Sep 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| HP            | Laptop 17-bs0xx             | [85548f2790](https://linux-hardware.org/?probe=85548f2790) | Sep 28, 2023 |
| HP            | ElitePad 1000 G2            | [9c4b30a15c](https://linux-hardware.org/?probe=9c4b30a15c) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | [ee4b3f2b76](https://linux-hardware.org/?probe=ee4b3f2b76) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Samsung       | R519/R719                   | [15ae7c9603](https://linux-hardware.org/?probe=15ae7c9603) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| ASUSTek       | UL80VT                      | [1d3c36ccf4](https://linux-hardware.org/?probe=1d3c36ccf4) | Sep 25, 2023 |
| Dell          | Vostro 1000                 | [38499a1a0f](https://linux-hardware.org/?probe=38499a1a0f) | Sep 25, 2023 |
| Toshiba       | Satellite C50-B             | [92a5c3605c](https://linux-hardware.org/?probe=92a5c3605c) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B350/... | [2b241af774](https://linux-hardware.org/?probe=2b241af774) | Sep 25, 2023 |
| HP            | Laptop 17-cn0xxx            | [10ec627bad](https://linux-hardware.org/?probe=10ec627bad) | Sep 25, 2023 |
| Acer          | Aspire F5-573G              | [a2f6814940](https://linux-hardware.org/?probe=a2f6814940) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | [e74a87d3f4](https://linux-hardware.org/?probe=e74a87d3f4) | Sep 25, 2023 |
| Acer          | Nitro AN515-51              | [6d6d719f30](https://linux-hardware.org/?probe=6d6d719f30) | Sep 25, 2023 |
| HP            | ElitePad 1000 G2            | [5cfbe2e7e0](https://linux-hardware.org/?probe=5cfbe2e7e0) | Sep 24, 2023 |
| Acer          | Aspire 7730G                | [e21c91c34c](https://linux-hardware.org/?probe=e21c91c34c) | Sep 24, 2023 |
| Toshiba       | Satellite L45-B             | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Lenovo        | G580 20150                  | [f55e42a884](https://linux-hardware.org/?probe=f55e42a884) | Sep 24, 2023 |
| Toshiba       | Satellite S50t-B            | [a574ee83ff](https://linux-hardware.org/?probe=a574ee83ff) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| Acer          | Aspire 5734Z                | [d5219dbfbe](https://linux-hardware.org/?probe=d5219dbfbe) | Sep 24, 2023 |
| Unknown       | Unknown                     | [940b1d1eeb](https://linux-hardware.org/?probe=940b1d1eeb) | Sep 23, 2023 |
| HP            | Dev One Notebook PC         | [1cc979900b](https://linux-hardware.org/?probe=1cc979900b) | Sep 23, 2023 |
| Acer          | Aspire 5732Z                | [c86094eac8](https://linux-hardware.org/?probe=c86094eac8) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [683cbd037a](https://linux-hardware.org/?probe=683cbd037a) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| HP            | Laptop 15-dw1xxx            | [be4a46768b](https://linux-hardware.org/?probe=be4a46768b) | Sep 23, 2023 |
| HP            | EliteBook 840 G6            | [10cd0244af](https://linux-hardware.org/?probe=10cd0244af) | Sep 23, 2023 |
| Samsung       | 935XDB                      | [a0672b9726](https://linux-hardware.org/?probe=a0672b9726) | Sep 23, 2023 |
| ASUSTek       | X750JB                      | [b9db8f6f02](https://linux-hardware.org/?probe=b9db8f6f02) | Sep 23, 2023 |
| HP            | ProBook 4515s               | [0b755bf978](https://linux-hardware.org/?probe=0b755bf978) | Sep 22, 2023 |
| LG Electro... | 16Z90P-K.AAS9U1             | [5e60864354](https://linux-hardware.org/?probe=5e60864354) | Sep 22, 2023 |
| Acer          | Aspire A515-47              | [2676f29c41](https://linux-hardware.org/?probe=2676f29c41) | Sep 22, 2023 |
| Dell          | Latitude E7440              | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| Apple         | MacBookPro12,1              | [b8b562cc39](https://linux-hardware.org/?probe=b8b562cc39) | Sep 22, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [57c3bb43f5](https://linux-hardware.org/?probe=57c3bb43f5) | Sep 22, 2023 |
| HP            | Pavilion g6                 | [c5833405a5](https://linux-hardware.org/?probe=c5833405a5) | Sep 22, 2023 |
| HP            | EliteBook 840 G5            | [03d461d3af](https://linux-hardware.org/?probe=03d461d3af) | Sep 22, 2023 |
| Acer          | Aspire VN7-571G             | [0314ce541e](https://linux-hardware.org/?probe=0314ce541e) | Sep 22, 2023 |
| Acer          | Nitro AN515-57              | [05c9cbc8e5](https://linux-hardware.org/?probe=05c9cbc8e5) | Sep 22, 2023 |
| Acer          | Extensa 5635ZG              | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| Lenovo        | ThinkPad X220 4286BB2       | [a3b217a707](https://linux-hardware.org/?probe=a3b217a707) | Sep 21, 2023 |
| Acer          | Aspire A114-33              | [4b581786a8](https://linux-hardware.org/?probe=4b581786a8) | Sep 21, 2023 |
| Acer          | Aspire F5-571               | [21bcc4a506](https://linux-hardware.org/?probe=21bcc4a506) | Sep 21, 2023 |
| ASUSTek       | TP550LAB                    | [3e07304aa5](https://linux-hardware.org/?probe=3e07304aa5) | Sep 20, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [5a74bb7dde](https://linux-hardware.org/?probe=5a74bb7dde) | Sep 20, 2023 |
| HP            | EliteBook 845 14 inch G9... | [35d24c31cf](https://linux-hardware.org/?probe=35d24c31cf) | Sep 20, 2023 |
| Dell          | Latitude 3540               | [3f1c99de44](https://linux-hardware.org/?probe=3f1c99de44) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| Dell          | Inspiron 3442               | [1f6ca2e4f7](https://linux-hardware.org/?probe=1f6ca2e4f7) | Sep 19, 2023 |
| Acer          | Nitro AN517-52              | [32f2e74fe3](https://linux-hardware.org/?probe=32f2e74fe3) | Sep 19, 2023 |
| Acer          | Aspire A315-22G             | [0c047cb731](https://linux-hardware.org/?probe=0c047cb731) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1180346586](https://linux-hardware.org/?probe=1180346586) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA1S702    | [5be3b8fc11](https://linux-hardware.org/?probe=5be3b8fc11) | Sep 19, 2023 |
| Acer          | Aspire 5742                 | [430ed1fe6c](https://linux-hardware.org/?probe=430ed1fe6c) | Sep 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [53549e3b08](https://linux-hardware.org/?probe=53549e3b08) | Sep 18, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | [54aa39a845](https://linux-hardware.org/?probe=54aa39a845) | Sep 18, 2023 |
| Acer          | Swift SF314-42              | [1519801016](https://linux-hardware.org/?probe=1519801016) | Sep 18, 2023 |
| HP            | Notebook                    | [0c80a5c83f](https://linux-hardware.org/?probe=0c80a5c83f) | Sep 18, 2023 |
| MSI           | Modern 14 C11M              | [4c6156df05](https://linux-hardware.org/?probe=4c6156df05) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cad09f007e](https://linux-hardware.org/?probe=cad09f007e) | Sep 18, 2023 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [612bda7c21](https://linux-hardware.org/?probe=612bda7c21) | Sep 17, 2023 |
| ASUSTek       | P52F                        | [6be70b4b24](https://linux-hardware.org/?probe=6be70b4b24) | Sep 17, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [20d35c7482](https://linux-hardware.org/?probe=20d35c7482) | Sep 17, 2023 |
| Toshiba       | Satellite Pro R50-B         | [e3a895eaa7](https://linux-hardware.org/?probe=e3a895eaa7) | Sep 17, 2023 |
| Notebook      | NP5x_6x_7x_SNx              | [83be57b9aa](https://linux-hardware.org/?probe=83be57b9aa) | Sep 17, 2023 |
| Dell          | System XPS L502X            | [d3154f94d7](https://linux-hardware.org/?probe=d3154f94d7) | Sep 17, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1a5acc2c10](https://linux-hardware.org/?probe=1a5acc2c10) | Sep 17, 2023 |
| NEC Comput... | PC-VK15EBZDG                | [83d74c1e9d](https://linux-hardware.org/?probe=83d74c1e9d) | Sep 17, 2023 |
| ASUSTek       | K52JT                       | [5cf28fa81f](https://linux-hardware.org/?probe=5cf28fa81f) | Sep 16, 2023 |
| HP            | EliteBook 725 G3            | [6086fd0180](https://linux-hardware.org/?probe=6086fd0180) | Sep 16, 2023 |
| Lenovo        | ThinkPad T420 4236B27       | [8cd0ed072f](https://linux-hardware.org/?probe=8cd0ed072f) | Sep 16, 2023 |
| Compaq        | 420                         | [a0ce747ff2](https://linux-hardware.org/?probe=a0ce747ff2) | Sep 16, 2023 |
| HP            | 15                          | [636b9a80a1](https://linux-hardware.org/?probe=636b9a80a1) | Sep 15, 2023 |
| Fujitsu       | LIFEBOOK E733               | [0613157456](https://linux-hardware.org/?probe=0613157456) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [e1ac878fa3](https://linux-hardware.org/?probe=e1ac878fa3) | Sep 15, 2023 |
| Lenovo        | ThinkPad T430 2349CV8       | [80e76d50db](https://linux-hardware.org/?probe=80e76d50db) | Sep 15, 2023 |
| HP            | Compaq 615                  | [f2f7659e5b](https://linux-hardware.org/?probe=f2f7659e5b) | Sep 15, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [3959de124c](https://linux-hardware.org/?probe=3959de124c) | Sep 14, 2023 |
| HP            | Laptop 15-bw0xx             | [c0bcb5b2c6](https://linux-hardware.org/?probe=c0bcb5b2c6) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Dell          | Latitude 3420               | [e78cbe0564](https://linux-hardware.org/?probe=e78cbe0564) | Sep 13, 2023 |
| HP            | Notebook                    | [1f0357e569](https://linux-hardware.org/?probe=1f0357e569) | Sep 13, 2023 |
| Positivo      | C14CR21                     | [9d48466eab](https://linux-hardware.org/?probe=9d48466eab) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [1b8a46fc57](https://linux-hardware.org/?probe=1b8a46fc57) | Sep 13, 2023 |
| Acer          | Aspire ES1-311              | [d191439979](https://linux-hardware.org/?probe=d191439979) | Sep 13, 2023 |
| ASUSTek       | G74Sx                       | [aad78d1633](https://linux-hardware.org/?probe=aad78d1633) | Sep 12, 2023 |
| Lenovo        | ThinkPad T61 7659VKF        | [1f07dfc17a](https://linux-hardware.org/?probe=1f07dfc17a) | Sep 12, 2023 |
| LG Electro... | C400-G.BC22P1               | [caef8df1be](https://linux-hardware.org/?probe=caef8df1be) | Sep 12, 2023 |
| Dell          | Latitude E4200              | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Acer          | Aspire A315-21              | [a7fca90eab](https://linux-hardware.org/?probe=a7fca90eab) | Sep 12, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | [68f0df2a6c](https://linux-hardware.org/?probe=68f0df2a6c) | Sep 12, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | [a1f824e885](https://linux-hardware.org/?probe=a1f824e885) | Sep 12, 2023 |
| Dell          | Inspiron 5458               | [ab3824f3d0](https://linux-hardware.org/?probe=ab3824f3d0) | Sep 11, 2023 |
| Acer          | Aspire A315-23              | [ecdef7173c](https://linux-hardware.org/?probe=ecdef7173c) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [825795d0df](https://linux-hardware.org/?probe=825795d0df) | Sep 11, 2023 |
| LIVEFAN       | Unknown                     | [102a13c2c5](https://linux-hardware.org/?probe=102a13c2c5) | Sep 11, 2023 |
| Acer          | AOD270                      | [d7d4474d69](https://linux-hardware.org/?probe=d7d4474d69) | Sep 11, 2023 |
| Dell          | Latitude E7440              | [7813372525](https://linux-hardware.org/?probe=7813372525) | Sep 11, 2023 |
| Lenovo        | Z710 20250                  | [9f1aed2560](https://linux-hardware.org/?probe=9f1aed2560) | Sep 10, 2023 |
| Dell          | Vostro 3550                 | [4f0a6ec78c](https://linux-hardware.org/?probe=4f0a6ec78c) | Sep 10, 2023 |
| HP            | 255 G7 Notebook PC          | [c5be1f9523](https://linux-hardware.org/?probe=c5be1f9523) | Sep 10, 2023 |
| Dell          | Inspiron 11-3162            | [600d8479fe](https://linux-hardware.org/?probe=600d8479fe) | Sep 10, 2023 |
| Dell          | Latitude E6430              | [699eae450e](https://linux-hardware.org/?probe=699eae450e) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK S752               | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| Dell          | Inspiron 3501               | [f7eae2e7c4](https://linux-hardware.org/?probe=f7eae2e7c4) | Sep 09, 2023 |
| ASUSTek       | X541UVK                     | [1a943fda98](https://linux-hardware.org/?probe=1a943fda98) | Sep 09, 2023 |
| Dell          | Latitude E6400              | [e42cf159af](https://linux-hardware.org/?probe=e42cf159af) | Sep 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c320e0c618](https://linux-hardware.org/?probe=c320e0c618) | Sep 09, 2023 |
| ASUSTek       | X201EP                      | [a714c5a35a](https://linux-hardware.org/?probe=a714c5a35a) | Sep 09, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [218489cc3f](https://linux-hardware.org/?probe=218489cc3f) | Sep 09, 2023 |
| HP            | ProBook 640 G1              | [75c6651a69](https://linux-hardware.org/?probe=75c6651a69) | Sep 09, 2023 |
| HP            | Pavilion m6                 | [2fb7dbd455](https://linux-hardware.org/?probe=2fb7dbd455) | Sep 09, 2023 |
| Dell          | Latitude E6410              | [9b57eaa1eb](https://linux-hardware.org/?probe=9b57eaa1eb) | Sep 09, 2023 |
| HP            | ProBook 6470b               | [1c8817d025](https://linux-hardware.org/?probe=1c8817d025) | Sep 09, 2023 |
| Dell          | Latitude 7390               | [3644f0b002](https://linux-hardware.org/?probe=3644f0b002) | Sep 08, 2023 |
| HP            | Notebook                    | [5a36d2a3bf](https://linux-hardware.org/?probe=5a36d2a3bf) | Sep 08, 2023 |
| Apple         | MacBookPro10,1              | [81aab795b5](https://linux-hardware.org/?probe=81aab795b5) | Sep 08, 2023 |
| Acer          | Nitro AN515-44              | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| Lenovo        | V15-ADA 82C7                | [d98be8d71c](https://linux-hardware.org/?probe=d98be8d71c) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ecef237a9c](https://linux-hardware.org/?probe=ecef237a9c) | Sep 07, 2023 |
| ASUSTek       | UL80VT                      | [daa7101bf4](https://linux-hardware.org/?probe=daa7101bf4) | Sep 07, 2023 |
| Samsung       | 300E5M/300E5L               | [8274cbca33](https://linux-hardware.org/?probe=8274cbca33) | Sep 07, 2023 |
| Acer          | AO722                       | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Lenovo        | V15-IGL 82C3                | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| Apple         | MacBookPro9,2               | [f3bdad3061](https://linux-hardware.org/?probe=f3bdad3061) | Sep 07, 2023 |
| Dell          | Latitude 5480               | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| Google        | Blooguard                   | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5254176a5a](https://linux-hardware.org/?probe=5254176a5a) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| HP            | EliteBook 2740p             | [0bada236bc](https://linux-hardware.org/?probe=0bada236bc) | Sep 07, 2023 |
| Clevo         | M1100M                      | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Acer          | Swift SF314-51              | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| MSI           | Bravo 15 C7VF               | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| MSI           | GS60 2PC Ghost              | [0b971b067a](https://linux-hardware.org/?probe=0b971b067a) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Google        | Pirika                      | [e05149e1de](https://linux-hardware.org/?probe=e05149e1de) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| HP            | Notebook                    | [ad9bafda30](https://linux-hardware.org/?probe=ad9bafda30) | Sep 06, 2023 |
| HP            | Pavilion dv4                | [0b01aaddd6](https://linux-hardware.org/?probe=0b01aaddd6) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| Purism        | Librem 15 v3                | [d3a66abc8b](https://linux-hardware.org/?probe=d3a66abc8b) | Sep 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | [cb8de94658](https://linux-hardware.org/?probe=cb8de94658) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| HP            | Laptop 15s-eq2xxx           | [344c861540](https://linux-hardware.org/?probe=344c861540) | Sep 05, 2023 |
| ASUSTek       | UL80VT                      | [aec41416ac](https://linux-hardware.org/?probe=aec41416ac) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| Toshiba       | Satellite C850-1DZ          | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| HP            | mt40                        | [c3a4682e40](https://linux-hardware.org/?probe=c3a4682e40) | Sep 04, 2023 |
| HP            | Notebook                    | [3a7a5608af](https://linux-hardware.org/?probe=3a7a5608af) | Sep 04, 2023 |
| Dell          | Inspiron 5567               | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T470 20HD000RUS    | [f7250cb3ae](https://linux-hardware.org/?probe=f7250cb3ae) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [08e7b606c8](https://linux-hardware.org/?probe=08e7b606c8) | Sep 04, 2023 |
| ASUSTek       | N73SV                       | [1e0b979775](https://linux-hardware.org/?probe=1e0b979775) | Sep 04, 2023 |
| Lenovo        | ThinkPad SL510 28473QB      | [e1ff8baa87](https://linux-hardware.org/?probe=e1ff8baa87) | Sep 04, 2023 |
| Acer          | Aspire 4741                 | [2f2b673625](https://linux-hardware.org/?probe=2f2b673625) | Sep 04, 2023 |
| Dell          | Precision M4800             | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Dell          | Vostro 5590                 | [24ee101fee](https://linux-hardware.org/?probe=24ee101fee) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| ASUSTek       | K53TA                       | [b173b156f9](https://linux-hardware.org/?probe=b173b156f9) | Sep 04, 2023 |
| Apple         | MacBookPro11,1              | [d8efe50ca5](https://linux-hardware.org/?probe=d8efe50ca5) | Sep 04, 2023 |
| HP            | Laptop 17-by0xxx            | [7c149b5f95](https://linux-hardware.org/?probe=7c149b5f95) | Sep 04, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [b3e23f1718](https://linux-hardware.org/?probe=b3e23f1718) | Sep 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [02c4374b47](https://linux-hardware.org/?probe=02c4374b47) | Sep 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5f9e18ee26](https://linux-hardware.org/?probe=5f9e18ee26) | Sep 04, 2023 |
| HP            | ProBook 650 G2              | [64026d5e6d](https://linux-hardware.org/?probe=64026d5e6d) | Sep 04, 2023 |
| Lenovo        | V130-15IKB 81HN             | [760698ac8a](https://linux-hardware.org/?probe=760698ac8a) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [85cc15f8ea](https://linux-hardware.org/?probe=85cc15f8ea) | Sep 04, 2023 |
| HP            | EliteBook 840 G1            | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [40c832efb9](https://linux-hardware.org/?probe=40c832efb9) | Sep 04, 2023 |
| ASUSTek       | X75A1                       | [d8be6d6952](https://linux-hardware.org/?probe=d8be6d6952) | Sep 04, 2023 |
| Compaq        | 430                         | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| AXIOO         | Mybook 14E                  | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| ASUSTek       | N56JN                       | [eb9458de08](https://linux-hardware.org/?probe=eb9458de08) | Sep 04, 2023 |
| HP            | 1000                        | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| Dell          | Latitude 5480               | [3a25585a10](https://linux-hardware.org/?probe=3a25585a10) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [49d36f6acc](https://linux-hardware.org/?probe=49d36f6acc) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| VIT           | P2400                       | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| Lenovo        | ThinkPad T430 2349MPS       | [183e5c528c](https://linux-hardware.org/?probe=183e5c528c) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK E734               | [1b89968327](https://linux-hardware.org/?probe=1b89968327) | Sep 03, 2023 |
| Acer          | Nitro AN515-57              | [95b036ac9a](https://linux-hardware.org/?probe=95b036ac9a) | Sep 03, 2023 |
| ALLDOCUBE     | i1402A                      | [d5d2c60681](https://linux-hardware.org/?probe=d5d2c60681) | Sep 03, 2023 |
| ASUSTek       | X555LJ                      | [c13b1a693d](https://linux-hardware.org/?probe=c13b1a693d) | Sep 03, 2023 |
| Acer          | Nitro AN515-41              | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [f92734bf2b](https://linux-hardware.org/?probe=f92734bf2b) | Sep 03, 2023 |
| Toshiba       | Satellite C850              | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| Lenovo        | Z50-75 80EC                 | [12894bacfb](https://linux-hardware.org/?probe=12894bacfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [7b776b30bd](https://linux-hardware.org/?probe=7b776b30bd) | Sep 03, 2023 |
| Dell          | Latitude E6410              | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| Acer          | Aspire ES1-711              | [36b5fac615](https://linux-hardware.org/?probe=36b5fac615) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Acer          | Aspire 7745G                | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| HP            | ENVY m6                     | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| Dell          | Latitude E6400              | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| Acer          | Aspire A515-55              | [71305b0cca](https://linux-hardware.org/?probe=71305b0cca) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| Acer          | Aspire 5741G                | [b49fa94760](https://linux-hardware.org/?probe=b49fa94760) | Sep 03, 2023 |
| Packard Be... | EasyNote TJ65               | [55bb236bde](https://linux-hardware.org/?probe=55bb236bde) | Sep 03, 2023 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [a785a4e9bb](https://linux-hardware.org/?probe=a785a4e9bb) | Sep 03, 2023 |
| Apple         | MacBookPro14,1              | [8e63bb873b](https://linux-hardware.org/?probe=8e63bb873b) | Sep 03, 2023 |
| Toshiba       | dynabook R73/J              | [c63c97e4a8](https://linux-hardware.org/?probe=c63c97e4a8) | Sep 03, 2023 |
| Google        | Lick                        | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Acer          | Nitro AN515-52              | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| HP            | Laptop 14-fq0xxx            | [d68ec21cac](https://linux-hardware.org/?probe=d68ec21cac) | Sep 03, 2023 |
| Acer          | Aspire E5-471G              | [b1332205f3](https://linux-hardware.org/?probe=b1332205f3) | Sep 03, 2023 |
| HP            | ProBook 440 G7              | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| HP            | Laptop 15-rb0xx             | [0f08b5b0ad](https://linux-hardware.org/?probe=0f08b5b0ad) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Dell          | Inspiron N4010              | [78f4fd9711](https://linux-hardware.org/?probe=78f4fd9711) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| Chuwi         | GemiBook XPro               | [a76e69489c](https://linux-hardware.org/?probe=a76e69489c) | Sep 02, 2023 |
| Alienware     | m15 R3                      | [c2e00a5341](https://linux-hardware.org/?probe=c2e00a5341) | Sep 02, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Lenovo        | B590 20206                  | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| Lenovo        | ThinkPad A485 20MVS16C00    | [4d39e78f8f](https://linux-hardware.org/?probe=4d39e78f8f) | Sep 02, 2023 |
| HP            | EliteBook 850 G1            | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| Lenovo        | G565 20071                  | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| Lenovo        | ThinkPad T460s 20F9003CU... | [8c94711a27](https://linux-hardware.org/?probe=8c94711a27) | Sep 02, 2023 |
| UMAX          | 13Wr                        | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Acer          | TravelMate 8372             | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| Microtech     | ebookPro                    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| Lenovo        | ThinkPad T540p 20BFCTO      | [6c4bd340bc](https://linux-hardware.org/?probe=6c4bd340bc) | Sep 02, 2023 |
| MSI           | MS-1688                     | [30cd2d6e9a](https://linux-hardware.org/?probe=30cd2d6e9a) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| MSI           | GP70 2OD                    | [4bc109f9a0](https://linux-hardware.org/?probe=4bc109f9a0) | Sep 02, 2023 |
| HP            | 1000                        | [aedfad957a](https://linux-hardware.org/?probe=aedfad957a) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | [dd49edce58](https://linux-hardware.org/?probe=dd49edce58) | Sep 02, 2023 |
| Dell          | Inspiron 3585               | [a8bdd5bcca](https://linux-hardware.org/?probe=a8bdd5bcca) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Dell          | Latitude 2120               | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Chuwi         | LapBook Pro                 | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Lenovo        | G570 4334                   | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Lenovo        | V145-15AST 81MT             | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [f7e029febe](https://linux-hardware.org/?probe=f7e029febe) | Sep 01, 2023 |
| Lenovo        | G70-70 80HW                 | [f8ac18ebd1](https://linux-hardware.org/?probe=f8ac18ebd1) | Sep 01, 2023 |
| GPU Compan... | GWTC116-2                   | [455a21dde9](https://linux-hardware.org/?probe=455a21dde9) | Sep 01, 2023 |
| HP            | Laptop 17-bs0xx             | [c4727ff179](https://linux-hardware.org/?probe=c4727ff179) | Sep 01, 2023 |
| HP            | Pavilion g6                 | [0f0960322d](https://linux-hardware.org/?probe=0f0960322d) | Sep 01, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [28fc3470c8](https://linux-hardware.org/?probe=28fc3470c8) | Sep 01, 2023 |
| Medion        | A17                         | [31b4226638](https://linux-hardware.org/?probe=31b4226638) | Sep 01, 2023 |
| Dell          | Vostro 3590                 | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| Lenovo        | ThinkPad L450 20DSS1DT00    | [89ca82b3af](https://linux-hardware.org/?probe=89ca82b3af) | Sep 01, 2023 |
| Sony          | SVS1512DCXB                 | [b712723d6c](https://linux-hardware.org/?probe=b712723d6c) | Sep 01, 2023 |
| Lenovo        | ThinkPad X250 20CL001DGE    | [f6bc603569](https://linux-hardware.org/?probe=f6bc603569) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| ASUSTek       | K55VD                       | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| HP            | Compaq 15                   | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| Packard Be... | EasyNote TE11HC             | [2a11f6be15](https://linux-hardware.org/?probe=2a11f6be15) | Sep 01, 2023 |
| HP            | EliteBook 8440p             | [2107ba0ad7](https://linux-hardware.org/?probe=2107ba0ad7) | Sep 01, 2023 |
| Acer          | Extensa 5635Z               | [da70c2acd8](https://linux-hardware.org/?probe=da70c2acd8) | Sep 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c37cbe9bd9](https://linux-hardware.org/?probe=c37cbe9bd9) | Sep 01, 2023 |
| Positivo      | Mobile                      | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Acer          | TravelMate 5760G            | [1a0a1749fc](https://linux-hardware.org/?probe=1a0a1749fc) | Sep 01, 2023 |
| ASUSTek       | K53SD                       | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| Lenovo        | V15-IGL 82C3                | [4ab20a426a](https://linux-hardware.org/?probe=4ab20a426a) | Sep 01, 2023 |
| Lenovo        | IdeaPad Z370                | [5c21431c9d](https://linux-hardware.org/?probe=5c21431c9d) | Sep 01, 2023 |
| BGH           | C46G                        | [c56474510e](https://linux-hardware.org/?probe=c56474510e) | Sep 01, 2023 |
| Dell          | Inspiron 13-7353            | [021bbea0d4](https://linux-hardware.org/?probe=021bbea0d4) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| HP            | EliteBook 6930p             | [f40d8bbc73](https://linux-hardware.org/?probe=f40d8bbc73) | Sep 01, 2023 |
| Acer          | Aspire E5-571               | [04f5152e0c](https://linux-hardware.org/?probe=04f5152e0c) | Sep 01, 2023 |
| Lenovo        | ThinkPad X61 76753BJ        | [f90ed18892](https://linux-hardware.org/?probe=f90ed18892) | Sep 01, 2023 |
| Lenovo        | G550 2958                   | [033a5ccf76](https://linux-hardware.org/?probe=033a5ccf76) | Sep 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [499b5c3b2f](https://linux-hardware.org/?probe=499b5c3b2f) | Sep 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [0dbf80863b](https://linux-hardware.org/?probe=0dbf80863b) | Sep 01, 2023 |
| Apple         | MacBookPro11,4              | [406d9fd5fc](https://linux-hardware.org/?probe=406d9fd5fc) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [082d8a2ebf](https://linux-hardware.org/?probe=082d8a2ebf) | Sep 01, 2023 |
| Dell          | Latitude 3320               | [7c40b4eb0d](https://linux-hardware.org/?probe=7c40b4eb0d) | Sep 01, 2023 |
| ASUSTek       | K43SJ                       | [ab5c104bef](https://linux-hardware.org/?probe=ab5c104bef) | Aug 31, 2023 |
| ASUSTek       | S301LP                      | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [a45654cfd8](https://linux-hardware.org/?probe=a45654cfd8) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5720a360fb](https://linux-hardware.org/?probe=5720a360fb) | Aug 31, 2023 |
| Acer          | Aspire A317-33              | [8e27446a62](https://linux-hardware.org/?probe=8e27446a62) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| Lenovo        | Z50-70 20354                | [305133ce29](https://linux-hardware.org/?probe=305133ce29) | Aug 31, 2023 |
| Acer          | Extensa 5230                | [e4877c4cd7](https://linux-hardware.org/?probe=e4877c4cd7) | Aug 31, 2023 |
| Acer          | Aspire A315-58              | [ee8a1b4fb5](https://linux-hardware.org/?probe=ee8a1b4fb5) | Aug 31, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [a5847ee104](https://linux-hardware.org/?probe=a5847ee104) | Aug 31, 2023 |
| Medion        | Akoya E6239                 | [ec5460d846](https://linux-hardware.org/?probe=ec5460d846) | Aug 31, 2023 |
| Toshiba       | Satellite C50-B             | [9d05ea660f](https://linux-hardware.org/?probe=9d05ea660f) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| ASUSTek       | X75VC                       | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6cd62bfac4](https://linux-hardware.org/?probe=6cd62bfac4) | Aug 31, 2023 |
| ASUSTek       | GL753VD                     | [649fb869a6](https://linux-hardware.org/?probe=649fb869a6) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Dell          | System Inspiron N7110       | [c222da255e](https://linux-hardware.org/?probe=c222da255e) | Aug 31, 2023 |
| Acer          | Aspire 5755G                | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| Lenovo        | ThinkPad T480s 20L70025U... | [917664de79](https://linux-hardware.org/?probe=917664de79) | Aug 31, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fab320d1d5](https://linux-hardware.org/?probe=fab320d1d5) | Aug 31, 2023 |
| HP            | Laptop 14-bs1xx             | [335b828114](https://linux-hardware.org/?probe=335b828114) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [ba81140205](https://linux-hardware.org/?probe=ba81140205) | Aug 31, 2023 |
| Acer          | Aspire E1-571               | [62b0ee9c60](https://linux-hardware.org/?probe=62b0ee9c60) | Aug 31, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | [6af4b49ea2](https://linux-hardware.org/?probe=6af4b49ea2) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| ASUSTek       | K53SV                       | [17802d53e7](https://linux-hardware.org/?probe=17802d53e7) | Aug 30, 2023 |
| Medion        | P7818                       | [b2e6745157](https://linux-hardware.org/?probe=b2e6745157) | Aug 30, 2023 |
| ASUSTek       | K501LX                      | [ca56f1b803](https://linux-hardware.org/?probe=ca56f1b803) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| Lenovo        | G40-70 20369                | [f3cef329f6](https://linux-hardware.org/?probe=f3cef329f6) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470 20HES0ET0R    | [65d003a7a0](https://linux-hardware.org/?probe=65d003a7a0) | Aug 30, 2023 |
| Dell          | Latitude 3510               | [220b298103](https://linux-hardware.org/?probe=220b298103) | Aug 30, 2023 |
| HP            | ProBook 6360b               | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Dell          | Inspiron 7520               | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| HUAWEI        | KLVF-XX                     | [747a685cc1](https://linux-hardware.org/?probe=747a685cc1) | Aug 30, 2023 |
| Acer          | Aspire E1-530               | [39c2df1a0b](https://linux-hardware.org/?probe=39c2df1a0b) | Aug 30, 2023 |
| Dell          | Inspiron 3585               | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| HP            | Laptop 15-db0xxx            | [76eb125a56](https://linux-hardware.org/?probe=76eb125a56) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Dell          | Inspiron 7548               | [6b6a2e7632](https://linux-hardware.org/?probe=6b6a2e7632) | Aug 30, 2023 |
| Dell          | Inspiron 16 7610            | [57c65a2bc8](https://linux-hardware.org/?probe=57c65a2bc8) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a452d9eadf](https://linux-hardware.org/?probe=a452d9eadf) | Aug 30, 2023 |
| Lenovo        | V15-IGL 82C3                | [3a0999b4a7](https://linux-hardware.org/?probe=3a0999b4a7) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ef1b605965](https://linux-hardware.org/?probe=ef1b605965) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | [ac9c55fcb3](https://linux-hardware.org/?probe=ac9c55fcb3) | Aug 30, 2023 |
| Dell          | Inspiron 3576               | [f69425a68d](https://linux-hardware.org/?probe=f69425a68d) | Aug 30, 2023 |
| MSI           | GP72 7RDX                   | [071785ab97](https://linux-hardware.org/?probe=071785ab97) | Aug 30, 2023 |
| Lenovo        | ThinkPad X230 2325AJG       | [fa550a5ea1](https://linux-hardware.org/?probe=fa550a5ea1) | Aug 30, 2023 |
| HP            | Compaq Presario CQ60        | [12b48399ac](https://linux-hardware.org/?probe=12b48399ac) | Aug 30, 2023 |
| Acer          | Nitro AN515-52              | [efee17a022](https://linux-hardware.org/?probe=efee17a022) | Aug 30, 2023 |
| Acer          | Swift SF314-52              | [4f6b648f42](https://linux-hardware.org/?probe=4f6b648f42) | Aug 30, 2023 |
| Dell          | Precision 7730              | [11c494a20e](https://linux-hardware.org/?probe=11c494a20e) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Dell          | Latitude E6440              | [0b63ef8851](https://linux-hardware.org/?probe=0b63ef8851) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Alurin        | Go Notebook                 | [d07fd99df0](https://linux-hardware.org/?probe=d07fd99df0) | Aug 30, 2023 |
| MSI           | Katana GF76 11UC            | [dd25d90357](https://linux-hardware.org/?probe=dd25d90357) | Aug 30, 2023 |
| Chuwi         | CoreBook X                  | [c1a4e5d47f](https://linux-hardware.org/?probe=c1a4e5d47f) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ded378b5da](https://linux-hardware.org/?probe=ded378b5da) | Aug 30, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [6f5bafed6c](https://linux-hardware.org/?probe=6f5bafed6c) | Aug 30, 2023 |
| HUAWEI        | BOHB-WAX9                   | [dda651a1c4](https://linux-hardware.org/?probe=dda651a1c4) | Aug 30, 2023 |
| Acer          | TMP645-M                    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [958ecd81e5](https://linux-hardware.org/?probe=958ecd81e5) | Aug 30, 2023 |
| Apple         | MacBookPro11,1              | [b3caa97382](https://linux-hardware.org/?probe=b3caa97382) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| Dell          | Latitude 3350               | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| Dell          | Latitude 5290               | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Apple         | MacBook4,1                  | [04424409ef](https://linux-hardware.org/?probe=04424409ef) | Aug 29, 2023 |
| Lenovo        | G500 20236                  | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| Lenovo        | 3000 G410                   | [26c592ddd6](https://linux-hardware.org/?probe=26c592ddd6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK S792               | [7547ab7e8e](https://linux-hardware.org/?probe=7547ab7e8e) | Aug 29, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fe431ea565](https://linux-hardware.org/?probe=fe431ea565) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| Dell          | Latitude D630               | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [9ed16c423b](https://linux-hardware.org/?probe=9ed16c423b) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Lenovo        | ThinkPad T430 2349H86       | [6ed258911c](https://linux-hardware.org/?probe=6ed258911c) | Aug 29, 2023 |
| Toshiba       | PORTEGE Z930                | [b4acaedb21](https://linux-hardware.org/?probe=b4acaedb21) | Aug 29, 2023 |
| Dell          | Inspiron N4050              | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| System76      | Galago Pro                  | [31330746e6](https://linux-hardware.org/?probe=31330746e6) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [338a8026f3](https://linux-hardware.org/?probe=338a8026f3) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Panasonic     | CF-54-2                     | [7d2f4f34c9](https://linux-hardware.org/?probe=7d2f4f34c9) | Aug 28, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [54930549e6](https://linux-hardware.org/?probe=54930549e6) | Aug 28, 2023 |
| HP            | ProBook 430 G4 NOTEBOOK ... | [6ee102c046](https://linux-hardware.org/?probe=6ee102c046) | Aug 28, 2023 |
| ASUSTek       | K53E                        | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| Acer          | Aspire 7560                 | [4cb158cafc](https://linux-hardware.org/?probe=4cb158cafc) | Aug 28, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V805    | [ec4b2fa095](https://linux-hardware.org/?probe=ec4b2fa095) | Aug 28, 2023 |
| Lenovo        | ThinkPad X201 36809D4       | [1e4311af0b](https://linux-hardware.org/?probe=1e4311af0b) | Aug 28, 2023 |
| Lenovo        | ThinkPad L512 259766G       | [4b92af4aba](https://linux-hardware.org/?probe=4b92af4aba) | Aug 28, 2023 |
| Acer          | Aspire V5-573G              | [1afaed6ffa](https://linux-hardware.org/?probe=1afaed6ffa) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [12f61ffe4a](https://linux-hardware.org/?probe=12f61ffe4a) | Aug 28, 2023 |
| Dell          | Latitude 5580               | [eb2a994e98](https://linux-hardware.org/?probe=eb2a994e98) | Aug 28, 2023 |
| HP            | ProBook 6550b               | [2906ded48c](https://linux-hardware.org/?probe=2906ded48c) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Sony          | VPCEB43FG                   | [99812c6c56](https://linux-hardware.org/?probe=99812c6c56) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| Fujitsu       | FMVU14003                   | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| HP            | ProBook 4540s               | [a477892896](https://linux-hardware.org/?probe=a477892896) | Aug 27, 2023 |
| HP            | Laptop 15-db0xxx            | [2c0f5739a3](https://linux-hardware.org/?probe=2c0f5739a3) | Aug 27, 2023 |
| System76      | Gazelle                     | [83bc87f8fc](https://linux-hardware.org/?probe=83bc87f8fc) | Aug 27, 2023 |
| Toshiba       | Satellite C55-A             | [20dc6d4044](https://linux-hardware.org/?probe=20dc6d4044) | Aug 27, 2023 |
| Acer          | Aspire E5-774G              | [6e40336ff6](https://linux-hardware.org/?probe=6e40336ff6) | Aug 27, 2023 |
| Dell          | Latitude E6410              | [451d5477e5](https://linux-hardware.org/?probe=451d5477e5) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [79c52635ec](https://linux-hardware.org/?probe=79c52635ec) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| Dell          | Inspiron 5570               | [0baf10cd76](https://linux-hardware.org/?probe=0baf10cd76) | Aug 27, 2023 |
| HP            | EliteBook 835 G7 Noteboo... | [fec29a37b2](https://linux-hardware.org/?probe=fec29a37b2) | Aug 27, 2023 |
| Dell          | XPS M1330                   | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c54b2881a](https://linux-hardware.org/?probe=6c54b2881a) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Acer          | Aspire 4810T                | [4e72e77dc6](https://linux-hardware.org/?probe=4e72e77dc6) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [97caef0e98](https://linux-hardware.org/?probe=97caef0e98) | Aug 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4112e03a31](https://linux-hardware.org/?probe=4112e03a31) | Aug 27, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [cfbb311c97](https://linux-hardware.org/?probe=cfbb311c97) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [cc91bf6584](https://linux-hardware.org/?probe=cc91bf6584) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [8586d608af](https://linux-hardware.org/?probe=8586d608af) | Aug 26, 2023 |
| HP            | EliteBook 840 G3            | [25b5ca25b8](https://linux-hardware.org/?probe=25b5ca25b8) | Aug 26, 2023 |
| Lenovo        | ThinkPad T420 4236AK9       | [46a647db9b](https://linux-hardware.org/?probe=46a647db9b) | Aug 26, 2023 |
| Dell          | Precision M4600             | [fcc3763c08](https://linux-hardware.org/?probe=fcc3763c08) | Aug 26, 2023 |
| Dell          | Precision 7720              | [2281163932](https://linux-hardware.org/?probe=2281163932) | Aug 26, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Acer          | Aspire A515-45G             | [c0480c060a](https://linux-hardware.org/?probe=c0480c060a) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 25222AU       | [fdc78cf5a0](https://linux-hardware.org/?probe=fdc78cf5a0) | Aug 26, 2023 |
| ASUSTek       | UL80VT                      | [858a6c3ea1](https://linux-hardware.org/?probe=858a6c3ea1) | Aug 26, 2023 |
| VALE          | Notebook Classic C140       | [c5cae456b6](https://linux-hardware.org/?probe=c5cae456b6) | Aug 26, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [2ee2c8dd6c](https://linux-hardware.org/?probe=2ee2c8dd6c) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| HP            | ProBook 430 G1              | [aa3b7fe20f](https://linux-hardware.org/?probe=aa3b7fe20f) | Aug 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3c528e98c6](https://linux-hardware.org/?probe=3c528e98c6) | Aug 26, 2023 |
| Dell          | Inspiron 7375               | [32e62fd188](https://linux-hardware.org/?probe=32e62fd188) | Aug 26, 2023 |
| Unknown       | Unknown                     | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| ASUSTek       | UX330CAK                    | [35aa466ca4](https://linux-hardware.org/?probe=35aa466ca4) | Aug 26, 2023 |
| Lenovo        | IdeaPad Z480                | [e0989b8f9e](https://linux-hardware.org/?probe=e0989b8f9e) | Aug 25, 2023 |
| HP            | ProBook 440 G3              | [0f16274ad6](https://linux-hardware.org/?probe=0f16274ad6) | Aug 25, 2023 |
| HP            | EliteBook 850 G5            | [2d3a15b432](https://linux-hardware.org/?probe=2d3a15b432) | Aug 25, 2023 |
| Dell          | Latitude E6440              | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| Dell          | Latitude E6400              | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| HUAWEI        | RLEF-XX                     | [b5c86f44b7](https://linux-hardware.org/?probe=b5c86f44b7) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| HP            | Laptop 15-dy1xxx            | [03fbbf3d84](https://linux-hardware.org/?probe=03fbbf3d84) | Aug 25, 2023 |
| Dell          | Studio 1747                 | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| Dell          | Studio 1735                 | [5932ab2004](https://linux-hardware.org/?probe=5932ab2004) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | EliteBook 840 G3            | [d3c6faac81](https://linux-hardware.org/?probe=d3c6faac81) | Aug 25, 2023 |
| HP            | Laptop 17-by3xxx            | [081372c3c4](https://linux-hardware.org/?probe=081372c3c4) | Aug 25, 2023 |
| HP            | Laptop                      | [94fd1a7af2](https://linux-hardware.org/?probe=94fd1a7af2) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| ASUSTek       | K54HR                       | [5f24b13b35](https://linux-hardware.org/?probe=5f24b13b35) | Aug 25, 2023 |
| HP            | Compaq Presario CQ60        | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| Star Labs     | Lite                        | [0d0821a7dd](https://linux-hardware.org/?probe=0d0821a7dd) | Aug 25, 2023 |
| Dell          | G5 5590                     | [c13a60889c](https://linux-hardware.org/?probe=c13a60889c) | Aug 25, 2023 |
| HUAWEI        | KPL-W0X                     | [0cb8d58c01](https://linux-hardware.org/?probe=0cb8d58c01) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Toshiba       | PORTEGE R705                | [cae49b36a8](https://linux-hardware.org/?probe=cae49b36a8) | Aug 24, 2023 |
| Lenovo        | ThinkPad T450s 20BWS2M30... | [052c7eaa90](https://linux-hardware.org/?probe=052c7eaa90) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| Dell          | Inspiron 5379               | [df7d53dd55](https://linux-hardware.org/?probe=df7d53dd55) | Aug 24, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [2431197665](https://linux-hardware.org/?probe=2431197665) | Aug 24, 2023 |
| Dell          | Inspiron N5050              | [4d282e98b2](https://linux-hardware.org/?probe=4d282e98b2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| HP            | ProBook 450 G1              | [1bb6f8d738](https://linux-hardware.org/?probe=1bb6f8d738) | Aug 24, 2023 |
| HP            | Laptop 17-cn0xxx            | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| Thomson       | GENEO14C-4WH128             | [b145cbea54](https://linux-hardware.org/?probe=b145cbea54) | Aug 23, 2023 |
| ASUSTek       | X541SA                      | [109de7a1ae](https://linux-hardware.org/?probe=109de7a1ae) | Aug 23, 2023 |
| HP            | Pavilion 15                 | [0228bd6d42](https://linux-hardware.org/?probe=0228bd6d42) | Aug 23, 2023 |
| ASUSTek       | Q550LF                      | [f6531bb92a](https://linux-hardware.org/?probe=f6531bb92a) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | [d0f87a58ec](https://linux-hardware.org/?probe=d0f87a58ec) | Aug 23, 2023 |
| Dell          | Latitude 7480               | [50bcada7d4](https://linux-hardware.org/?probe=50bcada7d4) | Aug 23, 2023 |
| Positivo      | M7X0S Bottom                | [f78713080f](https://linux-hardware.org/?probe=f78713080f) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Positivo      | C14CU51                     | [b8c9fbc7b7](https://linux-hardware.org/?probe=b8c9fbc7b7) | Aug 23, 2023 |
| Dell          | Latitude E5420              | [102bee1da1](https://linux-hardware.org/?probe=102bee1da1) | Aug 23, 2023 |
| Unknown       | Unknown                     | [176f1e45e9](https://linux-hardware.org/?probe=176f1e45e9) | Aug 22, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [be00a84105](https://linux-hardware.org/?probe=be00a84105) | Aug 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [65747a7530](https://linux-hardware.org/?probe=65747a7530) | Aug 22, 2023 |
| Chuwi         | GemiBook Pro                | [62b31c86bb](https://linux-hardware.org/?probe=62b31c86bb) | Aug 22, 2023 |
| MSI           | CR610M                      | [e2432b72a5](https://linux-hardware.org/?probe=e2432b72a5) | Aug 22, 2023 |
| Dell          | Inspiron 1720               | [577e8e228f](https://linux-hardware.org/?probe=577e8e228f) | Aug 22, 2023 |
| Acer          | Aspire ES1-512              | [cb2839d263](https://linux-hardware.org/?probe=cb2839d263) | Aug 22, 2023 |
| HP            | Presario CQ57               | [bfc59ff9cd](https://linux-hardware.org/?probe=bfc59ff9cd) | Aug 22, 2023 |
| HP            | Pavilion dv6                | [10badbd20d](https://linux-hardware.org/?probe=10badbd20d) | Aug 22, 2023 |
| Acer          | Aspire E5-553G              | [d5350f0d1c](https://linux-hardware.org/?probe=d5350f0d1c) | Aug 22, 2023 |
| Acer          | Aspire A315-23              | [9b3a3cd47b](https://linux-hardware.org/?probe=9b3a3cd47b) | Aug 22, 2023 |
| ASUSTek       | Z450UAK                     | [68fb2ce5ec](https://linux-hardware.org/?probe=68fb2ce5ec) | Aug 22, 2023 |
| Samsung       | 270E5J/2570EJ               | [04a07b8fa6](https://linux-hardware.org/?probe=04a07b8fa6) | Aug 22, 2023 |
| Lenovo        | ThinkPad T530 23945ZS       | [07f7243392](https://linux-hardware.org/?probe=07f7243392) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| HP            | EliteBook 2170p             | [0bba785aee](https://linux-hardware.org/?probe=0bba785aee) | Aug 21, 2023 |
| Toshiba       | dynabook B350/22A           | [80ad4cd1ff](https://linux-hardware.org/?probe=80ad4cd1ff) | Aug 21, 2023 |
| Clevo         | W240HU/W250HUQ              | [4590ebf626](https://linux-hardware.org/?probe=4590ebf626) | Aug 21, 2023 |
| Sony          | VPCEG15FB                   | [e3b2126509](https://linux-hardware.org/?probe=e3b2126509) | Aug 20, 2023 |
| Dell          | Latitude 7490               | [e28046c842](https://linux-hardware.org/?probe=e28046c842) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [97ed27473e](https://linux-hardware.org/?probe=97ed27473e) | Aug 20, 2023 |
| Acer          | Aspire A315-42              | [e84eba7c7d](https://linux-hardware.org/?probe=e84eba7c7d) | Aug 20, 2023 |
| eMachines     | E520 V1.06                  | [bd63874856](https://linux-hardware.org/?probe=bd63874856) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d355f1941a](https://linux-hardware.org/?probe=d355f1941a) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [e5512efda4](https://linux-hardware.org/?probe=e5512efda4) | Aug 20, 2023 |
| HP            | 15 TouchSmart               | [d756b77e06](https://linux-hardware.org/?probe=d756b77e06) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [398280327e](https://linux-hardware.org/?probe=398280327e) | Aug 19, 2023 |
| Chuwi         | GemiBook                    | [64a2767d60](https://linux-hardware.org/?probe=64a2767d60) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [f75baa8a07](https://linux-hardware.org/?probe=f75baa8a07) | Aug 19, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [344dab6e5e](https://linux-hardware.org/?probe=344dab6e5e) | Aug 19, 2023 |
| Dell          | Latitude E5520              | [35f02a2ea2](https://linux-hardware.org/?probe=35f02a2ea2) | Aug 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c19ed9405c](https://linux-hardware.org/?probe=c19ed9405c) | Aug 19, 2023 |
| Danew         | Dbook 131                   | [35ea124809](https://linux-hardware.org/?probe=35ea124809) | Aug 19, 2023 |
| HP            | G62                         | [778c1c04b9](https://linux-hardware.org/?probe=778c1c04b9) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | [76dda9cde6](https://linux-hardware.org/?probe=76dda9cde6) | Aug 19, 2023 |
| HP            | Pavilion g6                 | [8e7844a79d](https://linux-hardware.org/?probe=8e7844a79d) | Aug 19, 2023 |
| Lenovo        | ThinkPad X230 23253B3       | [8da8bfe394](https://linux-hardware.org/?probe=8da8bfe394) | Aug 18, 2023 |
| Acer          | Aspire A315-59              | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Toshiba       | IS 1422                     | [2ad1bbf471](https://linux-hardware.org/?probe=2ad1bbf471) | Aug 18, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [b5e6b20270](https://linux-hardware.org/?probe=b5e6b20270) | Aug 18, 2023 |
| Dell          | Latitude E6500              | [5d1f16198a](https://linux-hardware.org/?probe=5d1f16198a) | Aug 18, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7add4465a9](https://linux-hardware.org/?probe=7add4465a9) | Aug 18, 2023 |
| Acer          | Aspire E1-421               | [bab5968f80](https://linux-hardware.org/?probe=bab5968f80) | Aug 18, 2023 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [41b00dc8b3](https://linux-hardware.org/?probe=41b00dc8b3) | Aug 18, 2023 |
| Lenovo        | ThinkPad T420 418063G       | [f8e7a666cc](https://linux-hardware.org/?probe=f8e7a666cc) | Aug 18, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [590ac28f26](https://linux-hardware.org/?probe=590ac28f26) | Aug 18, 2023 |
| HP            | ProBook 450 G3              | [c156f586f5](https://linux-hardware.org/?probe=c156f586f5) | Aug 18, 2023 |
| Chuwi         | GemiBook XPro               | [41b34e60fd](https://linux-hardware.org/?probe=41b34e60fd) | Aug 18, 2023 |
| Panasonic     | CF-31AQAAA1M                | [64416dbba5](https://linux-hardware.org/?probe=64416dbba5) | Aug 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7da49ac1c3](https://linux-hardware.org/?probe=7da49ac1c3) | Aug 17, 2023 |
| Apple         | MacBookPro9,2               | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Sony          | VGN-NW2SRF_S                | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| Dell          | Inspiron 1545               | [29c2bc1929](https://linux-hardware.org/?probe=29c2bc1929) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [1f416788fa](https://linux-hardware.org/?probe=1f416788fa) | Aug 17, 2023 |
| Acer          | Aspire ES1-311              | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| Toshiba       | Satellite L670              | [915e37b55d](https://linux-hardware.org/?probe=915e37b55d) | Aug 17, 2023 |
| Dell          | Latitude E6520              | [15420bd102](https://linux-hardware.org/?probe=15420bd102) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dbdb6ca163](https://linux-hardware.org/?probe=dbdb6ca163) | Aug 17, 2023 |
| Dell          | XPS 9320                    | [cb112d9f03](https://linux-hardware.org/?probe=cb112d9f03) | Aug 17, 2023 |
| GPU Compan... | GWTN141-1                   | [97416e9fda](https://linux-hardware.org/?probe=97416e9fda) | Aug 16, 2023 |
| HP            | Laptop 15s-fq5xxx           | [d3926b324c](https://linux-hardware.org/?probe=d3926b324c) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [080867b516](https://linux-hardware.org/?probe=080867b516) | Aug 16, 2023 |
| Dell          | Latitude E6430              | [87849c0e6c](https://linux-hardware.org/?probe=87849c0e6c) | Aug 16, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [6026ba6c8a](https://linux-hardware.org/?probe=6026ba6c8a) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Toshiba       | Satellite L510              | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [140af1f27b](https://linux-hardware.org/?probe=140af1f27b) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [8b4200849d](https://linux-hardware.org/?probe=8b4200849d) | Aug 15, 2023 |
| Packard Be... | EasyNote TSX66HR            | [f1b16023fd](https://linux-hardware.org/?probe=f1b16023fd) | Aug 15, 2023 |
| Dell          | Latitude E5470              | [f09173281d](https://linux-hardware.org/?probe=f09173281d) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| Acer          | Aspire V5-573G              | [f53da0a40d](https://linux-hardware.org/?probe=f53da0a40d) | Aug 15, 2023 |
| Samsung       | 755XDA                      | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| HP            | EliteBook Folio 9470m       | [d7f0d8e9cd](https://linux-hardware.org/?probe=d7f0d8e9cd) | Aug 15, 2023 |
| ASUSTek       | X553MA                      | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| Acer          | Aspire 5742                 | [ebc3e37c86](https://linux-hardware.org/?probe=ebc3e37c86) | Aug 13, 2023 |
| Lenovo        | ThinkPad E595 20NF0006GE    | [c9c068e82b](https://linux-hardware.org/?probe=c9c068e82b) | Aug 13, 2023 |
| Packard Be... | EasyNote LE69KB             | [42772eba76](https://linux-hardware.org/?probe=42772eba76) | Aug 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [e934dcd506](https://linux-hardware.org/?probe=e934dcd506) | Aug 13, 2023 |
| Sony          | SVE1112M1EW                 | [353fb8c6ff](https://linux-hardware.org/?probe=353fb8c6ff) | Aug 13, 2023 |
| Samsung       | 960XFH                      | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| Dell          | Inspiron 1720               | [1cb123d894](https://linux-hardware.org/?probe=1cb123d894) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [67f821bd4d](https://linux-hardware.org/?probe=67f821bd4d) | Aug 12, 2023 |
| HP            | Compaq nx9420 (RH457EA#A... | [1b7c441369](https://linux-hardware.org/?probe=1b7c441369) | Aug 12, 2023 |
| Lenovo        | V310-14ISK 80SX             | [edd47d65b6](https://linux-hardware.org/?probe=edd47d65b6) | Aug 12, 2023 |
| Lenovo        | V130-15IKB 81HN             | [88a9c5764d](https://linux-hardware.org/?probe=88a9c5764d) | Aug 11, 2023 |
| Acer          | Aspire A515-51              | [4856b9b32f](https://linux-hardware.org/?probe=4856b9b32f) | Aug 11, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [fad80ecff3](https://linux-hardware.org/?probe=fad80ecff3) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | [171fd219cc](https://linux-hardware.org/?probe=171fd219cc) | Aug 10, 2023 |
| Google        | Kip                         | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| Acer          | Aspire ES1-431              | [6802a19338](https://linux-hardware.org/?probe=6802a19338) | Aug 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Acer          | Extensa 5630                | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Chuwi         | GemiBook Pro                | [b5685bdafc](https://linux-hardware.org/?probe=b5685bdafc) | Aug 10, 2023 |
| HP            | EliteBook 8570p             | [73c1dd0c14](https://linux-hardware.org/?probe=73c1dd0c14) | Aug 10, 2023 |
| ASUSTek       | F3L                         | [b97c082eff](https://linux-hardware.org/?probe=b97c082eff) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290C37       | [125ac0cbd3](https://linux-hardware.org/?probe=125ac0cbd3) | Aug 08, 2023 |
| ASUSTek       | G750JW                      | [fe527d6231](https://linux-hardware.org/?probe=fe527d6231) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [187ac2792a](https://linux-hardware.org/?probe=187ac2792a) | Aug 08, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [b00519fee7](https://linux-hardware.org/?probe=b00519fee7) | Aug 08, 2023 |
| HP            | Laptop 17-cn1xxx            | [711a5fc7ce](https://linux-hardware.org/?probe=711a5fc7ce) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| HP            | Laptop 14-dq3xxx            | [c547f01fbb](https://linux-hardware.org/?probe=c547f01fbb) | Aug 08, 2023 |
| Acer          | AO756                       | [1ea1658ac0](https://linux-hardware.org/?probe=1ea1658ac0) | Aug 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [a1b9b9fc2c](https://linux-hardware.org/?probe=a1b9b9fc2c) | Aug 07, 2023 |
| MSI           | GL72 7QF                    | [73f4a3b852](https://linux-hardware.org/?probe=73f4a3b852) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Unknown       | Unknown                     | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| GPD           | G1618-03                    | [070d548515](https://linux-hardware.org/?probe=070d548515) | Aug 06, 2023 |
| Dell          | Inspiron N4050              | [af35c9ce49](https://linux-hardware.org/?probe=af35c9ce49) | Aug 05, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| Dell          | Precision M2800             | [7d1afe9d42](https://linux-hardware.org/?probe=7d1afe9d42) | Aug 05, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | [9db6bfdcfa](https://linux-hardware.org/?probe=9db6bfdcfa) | Aug 05, 2023 |
| HP            | Pavilion g4                 | [2094186715](https://linux-hardware.org/?probe=2094186715) | Aug 05, 2023 |
| MSI           | GE70 0NC                    | [c9fd935b80](https://linux-hardware.org/?probe=c9fd935b80) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Acer          | Aspire 5738                 | [f5df04e0e6](https://linux-hardware.org/?probe=f5df04e0e6) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S9R500    | [3624b5e366](https://linux-hardware.org/?probe=3624b5e366) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| GFAST         | N150                        | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| Acer          | Nitro AN517-54              | [aee5a21c76](https://linux-hardware.org/?probe=aee5a21c76) | Aug 04, 2023 |
| MSI           | Titan GT77HX 13VH           | [3acda608a1](https://linux-hardware.org/?probe=3acda608a1) | Aug 03, 2023 |
| HP            | ProBook 6540b               | [6ae3405ec5](https://linux-hardware.org/?probe=6ae3405ec5) | Aug 03, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [a3401e5a4b](https://linux-hardware.org/?probe=a3401e5a4b) | Aug 03, 2023 |
| Toshiba       | Satellite C855D             | [4835e837bd](https://linux-hardware.org/?probe=4835e837bd) | Aug 03, 2023 |
| Dell          | Latitude E6330              | [75d54a8988](https://linux-hardware.org/?probe=75d54a8988) | Aug 03, 2023 |
| TUXEDO        | Book XA15 / XA17 Gen10      | [18e29b97ac](https://linux-hardware.org/?probe=18e29b97ac) | Aug 02, 2023 |
| Toshiba       | Satellite C850-B239         | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Dell          | Precision M4500             | [b425204301](https://linux-hardware.org/?probe=b425204301) | Aug 02, 2023 |
| Dell          | Inspiron 1545               | [97d2508df2](https://linux-hardware.org/?probe=97d2508df2) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Dell          | Vostro 3700                 | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| Apple         | MacBookAir9,1               | [2e59618067](https://linux-hardware.org/?probe=2e59618067) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [483fbca861](https://linux-hardware.org/?probe=483fbca861) | Jul 31, 2023 |
| Dell          | Latitude E6430              | [9dcf92cce9](https://linux-hardware.org/?probe=9dcf92cce9) | Jul 31, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [7cb3479a69](https://linux-hardware.org/?probe=7cb3479a69) | Jul 31, 2023 |
| Dell          | Inspiron 5558               | [de55f350ab](https://linux-hardware.org/?probe=de55f350ab) | Jul 30, 2023 |
| Toshiba       | Satellite A135              | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Chuwi         | HeroBook Pro                | [eb332b024d](https://linux-hardware.org/?probe=eb332b024d) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| ASUSTek       | X540NA                      | [68b0d7d1fb](https://linux-hardware.org/?probe=68b0d7d1fb) | Jul 30, 2023 |
| Chuwi         | GemiBook                    | [f892a3970c](https://linux-hardware.org/?probe=f892a3970c) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [5da413f349](https://linux-hardware.org/?probe=5da413f349) | Jul 30, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [22f4bc0b5e](https://linux-hardware.org/?probe=22f4bc0b5e) | Jul 29, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Acer          | Aspire E5-511               | [aef96d4eb8](https://linux-hardware.org/?probe=aef96d4eb8) | Jul 29, 2023 |
| ASUSTek       | UX31E                       | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Dell          | Latitude E6420              | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 20HES2C000    | [6cb5b31808](https://linux-hardware.org/?probe=6cb5b31808) | Jul 29, 2023 |
| ASUSTek       | X102BA                      | [488aa4c5b4](https://linux-hardware.org/?probe=488aa4c5b4) | Jul 29, 2023 |
| Acer          | Aspire 4810T                | [4d3abb525e](https://linux-hardware.org/?probe=4d3abb525e) | Jul 28, 2023 |
| HP            | g14                         | [39d4ce09a1](https://linux-hardware.org/?probe=39d4ce09a1) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [49b28d270b](https://linux-hardware.org/?probe=49b28d270b) | Jul 27, 2023 |
| ASUSTek       | X550CC                      | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| Toshiba       | Satellite C50D-A-11G        | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| A14CR         | Unknown                     | [4ceb4f6761](https://linux-hardware.org/?probe=4ceb4f6761) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| GPU Compan... | GWNR71517                   | [ca3906a6c7](https://linux-hardware.org/?probe=ca3906a6c7) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [c7b69782db](https://linux-hardware.org/?probe=c7b69782db) | Jul 26, 2023 |
| Lenovo        | ThinkPad E555 20DH0027UK    | [b7bf821032](https://linux-hardware.org/?probe=b7bf821032) | Jul 26, 2023 |
| Positivo      | G800                        | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| ASUSTek       | P50IJ                       | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | [47d5775197](https://linux-hardware.org/?probe=47d5775197) | Jul 25, 2023 |
| Acer          | Extensa 2530                | [6691e96edf](https://linux-hardware.org/?probe=6691e96edf) | Jul 25, 2023 |
| Dell          | Latitude 5530               | [cccd0bf0b8](https://linux-hardware.org/?probe=cccd0bf0b8) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| Acer          | Aspire E5-571G              | [3f39162908](https://linux-hardware.org/?probe=3f39162908) | Jul 25, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [1cf27b8466](https://linux-hardware.org/?probe=1cf27b8466) | Jul 25, 2023 |
| HP            | 250 G5 Notebook PC          | [007f2e5957](https://linux-hardware.org/?probe=007f2e5957) | Jul 25, 2023 |
| HP            | Laptop 15s-du3xxx           | [e14cb2c24e](https://linux-hardware.org/?probe=e14cb2c24e) | Jul 25, 2023 |
| Toshiba       | IS 1442                     | [3a66df4c2d](https://linux-hardware.org/?probe=3a66df4c2d) | Jul 25, 2023 |
| Acer          | Aspire A114-33              | [a8c1a06e1a](https://linux-hardware.org/?probe=a8c1a06e1a) | Jul 25, 2023 |
| Lenovo        | ThinkPad L560 20F2S32Q00    | [0f437b5e3c](https://linux-hardware.org/?probe=0f437b5e3c) | Jul 25, 2023 |
| Dell          | Latitude 7490               | [066e3b9518](https://linux-hardware.org/?probe=066e3b9518) | Jul 25, 2023 |
| Chuwi         | CoreBook Pro                | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Apple         | MacBookPro13,3              | [ae23c3b0d3](https://linux-hardware.org/?probe=ae23c3b0d3) | Jul 24, 2023 |
| Intel         | powered classmate PC        | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| ASUSTek       | F7E                         | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [78560cbf59](https://linux-hardware.org/?probe=78560cbf59) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| Dell          | Inspiron 13-5378            | [7f6b8fc2db](https://linux-hardware.org/?probe=7f6b8fc2db) | Jul 23, 2023 |
| HP            | Laptop 17-ak0xx             | [e9b5ae3c4d](https://linux-hardware.org/?probe=e9b5ae3c4d) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [92c6b0de0c](https://linux-hardware.org/?probe=92c6b0de0c) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Lenovo        | ThinkPad L460 20FVS01J00    | [96fe0142cd](https://linux-hardware.org/?probe=96fe0142cd) | Jul 23, 2023 |
| Dell          | Inspiron N5110              | [8d94c58c16](https://linux-hardware.org/?probe=8d94c58c16) | Jul 23, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [4824895fac](https://linux-hardware.org/?probe=4824895fac) | Jul 23, 2023 |
| Dell          | Latitude E7270              | [9d14027d6c](https://linux-hardware.org/?probe=9d14027d6c) | Jul 23, 2023 |
| HP            | Compaq Presario C700        | [71ca83faee](https://linux-hardware.org/?probe=71ca83faee) | Jul 23, 2023 |
| HP            | Notebook                    | [1a4ba0be2f](https://linux-hardware.org/?probe=1a4ba0be2f) | Jul 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S6FY01    | [deaede763c](https://linux-hardware.org/?probe=deaede763c) | Jul 23, 2023 |
| HP            | Pavilion dv2500             | [6e86c0a75b](https://linux-hardware.org/?probe=6e86c0a75b) | Jul 23, 2023 |
| Lenovo        | V145-15AST 81MT             | [ecce500445](https://linux-hardware.org/?probe=ecce500445) | Jul 22, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| HP            | Laptop 17-by3xxx            | [b5fe1f6fca](https://linux-hardware.org/?probe=b5fe1f6fca) | Jul 22, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | [4ec1a5c6fe](https://linux-hardware.org/?probe=4ec1a5c6fe) | Jul 22, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [33ee51ddc5](https://linux-hardware.org/?probe=33ee51ddc5) | Jul 22, 2023 |
| Gigabyte      | AERO 15-X9                  | [2849a149b9](https://linux-hardware.org/?probe=2849a149b9) | Jul 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a9af1efc27](https://linux-hardware.org/?probe=a9af1efc27) | Jul 22, 2023 |
| HP            | Pavilion dv6700             | [aed45c2e40](https://linux-hardware.org/?probe=aed45c2e40) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| Standard      | Unknown                     | [74acf0f707](https://linux-hardware.org/?probe=74acf0f707) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | [61837fa4da](https://linux-hardware.org/?probe=61837fa4da) | Jul 21, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [2269e1f3d7](https://linux-hardware.org/?probe=2269e1f3d7) | Jul 21, 2023 |
| ASUSTek       | UX303LB                     | [901f80bb60](https://linux-hardware.org/?probe=901f80bb60) | Jul 20, 2023 |
| HP            | ProBook 6540b               | [ec232bc3fa](https://linux-hardware.org/?probe=ec232bc3fa) | Jul 20, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [61fa9a2c91](https://linux-hardware.org/?probe=61fa9a2c91) | Jul 20, 2023 |
| Acer          | Aspire A515-56              | [3e0e8609c8](https://linux-hardware.org/?probe=3e0e8609c8) | Jul 19, 2023 |
| Dell          | Latitude E6400              | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | [7d94a6effc](https://linux-hardware.org/?probe=7d94a6effc) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV002JUS    | [afc31702be](https://linux-hardware.org/?probe=afc31702be) | Jul 18, 2023 |
| Acer          | Predator PH317-56           | [248af0e35c](https://linux-hardware.org/?probe=248af0e35c) | Jul 18, 2023 |
| LG Electro... | P420-G.BE42P1               | [9dea573574](https://linux-hardware.org/?probe=9dea573574) | Jul 18, 2023 |
| Fujitsu       | LIFEBOOK A557               | [96f08b7598](https://linux-hardware.org/?probe=96f08b7598) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| Acer          | Nitro AN515-57              | [9853a8cf46](https://linux-hardware.org/?probe=9853a8cf46) | Jul 18, 2023 |
| ASUSTek       | K46CB                       | [144d523bf1](https://linux-hardware.org/?probe=144d523bf1) | Jul 18, 2023 |
| HP            | Pavilion Notebook           | [babb224527](https://linux-hardware.org/?probe=babb224527) | Jul 18, 2023 |
| HP            | G42                         | [d42b44461e](https://linux-hardware.org/?probe=d42b44461e) | Jul 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | [574cd2e0f8](https://linux-hardware.org/?probe=574cd2e0f8) | Jul 17, 2023 |
| ASUSTek       | G551JM                      | [393e57db0c](https://linux-hardware.org/?probe=393e57db0c) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480 20L5004HUS    | [6d453b900a](https://linux-hardware.org/?probe=6d453b900a) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [afb16ac821](https://linux-hardware.org/?probe=afb16ac821) | Jul 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [e2075c4a1e](https://linux-hardware.org/?probe=e2075c4a1e) | Jul 17, 2023 |
| HP            | Laptop 14s-dk0xxx           | [3cf00d1f89](https://linux-hardware.org/?probe=3cf00d1f89) | Jul 16, 2023 |
| Acer          | Aspire E5-573G              | [3cc36162b8](https://linux-hardware.org/?probe=3cc36162b8) | Jul 16, 2023 |
| Toshiba       | TECRA A10                   | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| ASUSTek       | K53SJ                       | [eb5e64c657](https://linux-hardware.org/?probe=eb5e64c657) | Jul 16, 2023 |
| Acer          | Swift SFE16-43              | [ebdd4b753c](https://linux-hardware.org/?probe=ebdd4b753c) | Jul 16, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46cfd28279](https://linux-hardware.org/?probe=46cfd28279) | Jul 16, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad T400 6474C53       | [e9db1ea8a6](https://linux-hardware.org/?probe=e9db1ea8a6) | Jul 15, 2023 |
| Acer          | Aspire E5-773G              | [a4a4102548](https://linux-hardware.org/?probe=a4a4102548) | Jul 15, 2023 |
| Positivo      | Mobile                      | [fdc2d91a25](https://linux-hardware.org/?probe=fdc2d91a25) | Jul 15, 2023 |
| Dell          | Inspiron MP061              | [0a26ffe33b](https://linux-hardware.org/?probe=0a26ffe33b) | Jul 15, 2023 |
| Toshiba       | Satellite C650              | [252f8adf16](https://linux-hardware.org/?probe=252f8adf16) | Jul 15, 2023 |
| Lenovo        | Legion 5 15IMH05H 82CF      | [804b227bff](https://linux-hardware.org/?probe=804b227bff) | Jul 15, 2023 |
| Packard Be... | EasyNote LM85               | [3efd87a0d8](https://linux-hardware.org/?probe=3efd87a0d8) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| Dell          | Inspiron 1545               | [0e9916f3e3](https://linux-hardware.org/?probe=0e9916f3e3) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| Acer          | Nitro AN515-45              | [2e11b53615](https://linux-hardware.org/?probe=2e11b53615) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| Acer          | Aspire E5-471G              | [c958efdb37](https://linux-hardware.org/?probe=c958efdb37) | Jul 12, 2023 |
| Apple         | MacBookPro12,1              | [dd19bc7fee](https://linux-hardware.org/?probe=dd19bc7fee) | Jul 12, 2023 |
| Dell          | Inspiron 5748               | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Dell          | Inspiron 5749               | [0421d22945](https://linux-hardware.org/?probe=0421d22945) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 23501B3       | [8f1d64206e](https://linux-hardware.org/?probe=8f1d64206e) | Jul 11, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 2210      | 28.59%  |
| OpenMandriva 4.3    | 2165      | 28%     |
| OpenMandriva 23.01  | 956       | 12.37%  |
| OpenMandriva 23.03  | 948       | 12.26%  |
| OpenMandriva 23.08  | 511       | 6.61%   |
| OpenMandriva 4.50   | 421       | 5.45%   |
| OpenMandriva 4.90   | 168       | 2.17%   |
| OpenMandriva 23.09  | 85        | 1.1%    |
| OpenMandriva 23.07  | 65        | 0.84%   |
| OpenMandriva 23.06  | 60        | 0.78%   |
| OpenMandriva 23.90  | 49        | 0.63%   |
| OpenMandriva 23.10  | 44        | 0.57%   |
| OpenMandriva 22.12  | 31        | 0.4%    |
| OpenMandriva 23.11  | 5         | 0.06%   |
| OpenMandriva 4.1    | 4         | 0.05%   |
| OpenMandriva 22.90  | 4         | 0.05%   |
| OpenMandriva 3.0    | 3         | 0.04%   |
| OpenMandriva 22.11  | 1         | 0.01%   |
| OpenMandriva 2014.0 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| OpenMandriva | 7267      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 2124      | 27.24%  |
| 5.16.7-desktop-1omv4003       | 2033      | 26.07%  |
| 6.2.6-desktop-1omv2390        | 915       | 11.73%  |
| 6.1.1-desktop-1omv2290        | 883       | 11.32%  |
| 6.4.11-desktop-1omv2390       | 391       | 5.01%   |
| 5.12.4-desktop-1omv4050       | 149       | 1.91%   |
| 5.16.13-desktop-1omv4003      | 146       | 1.87%   |
| 5.18.12-desktop-3omv4090      | 133       | 1.71%   |
| 6.4.8-desktop-2omv2390        | 129       | 1.65%   |
| 6.3.5-desktop-3omv2390        | 118       | 1.51%   |
| 5.11.12-desktop-1omv4002      | 102       | 1.31%   |
| 5.14.7-desktop-1omv4050       | 83        | 1.06%   |
| 5.19.5-desktop-1omv4090       | 77        | 0.99%   |
| 5.19.12-desktop-2omv4090      | 63        | 0.81%   |
| 6.1.4-desktop-1omv2301        | 62        | 0.8%    |
| 6.5.5-desktop-1omv2390        | 56        | 0.72%   |
| 6.5.0-desktop-1omv2390        | 38        | 0.49%   |
| 6.0.10-desktop-2omv22090      | 33        | 0.42%   |
| 6.5.3-desktop-1omv2390        | 25        | 0.32%   |
| 6.2.2-desktop-1omv2390        | 23        | 0.29%   |
| 5.14.14-desktop-1omv4050      | 18        | 0.23%   |
| 6.0.2-desktop-1omv4090        | 15        | 0.19%   |
| 5.17.1-desktop-2omv4050       | 15        | 0.19%   |
| 6.5.1-desktop-1omv2390        | 13        | 0.17%   |
| 5.12.7-desktop-1omv4003       | 11        | 0.14%   |
| 6.2.1-desktop-1omv2390        | 9         | 0.12%   |
| 6.5.2-desktop-1omv2390        | 8         | 0.1%    |
| 6.0.2-desktop-1omv4050        | 6         | 0.08%   |
| 5.19.11-desktop-2omv4090      | 6         | 0.08%   |
| 6.6.0-desktop-1omv2390        | 5         | 0.06%   |
| 5.19.1-desktop-1omv4090       | 5         | 0.06%   |
| 5.11.0-desktop-clang-1omv4002 | 5         | 0.06%   |
| 6.4.3-desktop-2omv2390        | 4         | 0.05%   |
| 6.4.0-desktop-0.rc3.1omv2390  | 4         | 0.05%   |
| 6.1.2-desktop-1omv2301        | 4         | 0.05%   |
| 6.2.8-desktop-1omv2390        | 3         | 0.04%   |
| 6.2.7-desktop-1omv2390        | 3         | 0.04%   |
| 5.5.12-desktop-1omv4001       | 3         | 0.04%   |
| 5.16.9-desktop-1omv4003       | 3         | 0.04%   |
| 5.16.5-desktop-2omv4003       | 3         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.14 | 2124      | 27.24%  |
| 5.16.7  | 2034      | 26.09%  |
| 6.2.6   | 915       | 11.74%  |
| 6.1.1   | 883       | 11.32%  |
| 6.4.11  | 391       | 5.01%   |
| 5.12.4  | 149       | 1.91%   |
| 5.16.13 | 147       | 1.89%   |
| 5.18.12 | 133       | 1.71%   |
| 6.4.8   | 129       | 1.65%   |
| 6.3.5   | 118       | 1.51%   |
| 5.11.12 | 102       | 1.31%   |
| 5.14.7  | 83        | 1.06%   |
| 5.19.5  | 77        | 0.99%   |
| 6.1.4   | 63        | 0.81%   |
| 5.19.12 | 63        | 0.81%   |
| 6.5.5   | 56        | 0.72%   |
| 6.5.0   | 40        | 0.51%   |
| 6.0.10  | 33        | 0.42%   |
| 6.5.3   | 25        | 0.32%   |
| 6.2.2   | 23        | 0.29%   |
| 6.0.2   | 21        | 0.27%   |
| 5.14.14 | 18        | 0.23%   |
| 5.17.1  | 17        | 0.22%   |
| 6.5.1   | 13        | 0.17%   |
| 5.12.7  | 12        | 0.15%   |
| 6.2.1   | 9         | 0.12%   |
| 6.5.2   | 8         | 0.1%    |
| 6.6.0   | 7         | 0.09%   |
| 5.11.0  | 7         | 0.09%   |
| 5.19.11 | 6         | 0.08%   |
| 5.19.1  | 5         | 0.06%   |
| 6.4.3   | 4         | 0.05%   |
| 6.4.0   | 4         | 0.05%   |
| 6.1.2   | 4         | 0.05%   |
| 5.16.9  | 4         | 0.05%   |
| 6.2.8   | 3         | 0.04%   |
| 6.2.7   | 3         | 0.04%   |
| 6.2.0   | 3         | 0.04%   |
| 5.5.12  | 3         | 0.04%   |
| 5.16.5  | 3         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.16    | 2159      | 27.81%  |
| 5.10    | 2126      | 27.39%  |
| 6.2     | 957       | 12.33%  |
| 6.1     | 955       | 12.3%   |
| 6.4     | 531       | 6.84%   |
| 5.12    | 161       | 2.07%   |
| 5.19    | 156       | 2.01%   |
| 6.5     | 142       | 1.83%   |
| 5.18    | 139       | 1.79%   |
| 6.3     | 122       | 1.57%   |
| 5.11    | 113       | 1.46%   |
| 5.14    | 101       | 1.3%    |
| 6.0     | 61        | 0.79%   |
| 5.17    | 17        | 0.22%   |
| 6.6     | 7         | 0.09%   |
| 5.5     | 4         | 0.05%   |
| 5.9     | 2         | 0.03%   |
| 5.15    | 2         | 0.03%   |
| 4.19    | 2         | 0.03%   |
| 5.8     | 1         | 0.01%   |
| 5.13    | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |
| 4.1     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7266      | 99.99%  |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 6898      | 93.94%  |
| GNOME    | 254       | 3.46%   |
| LXQt     | 132       | 1.8%    |
| Unknown  | 32        | 0.44%   |
| Cinnamon | 11        | 0.15%   |
| Budgie   | 9         | 0.12%   |
| XFCE     | 5         | 0.07%   |
| KDE4     | 1         | 0.01%   |
| DWM      | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 6573      | 88.7%   |
| Wayland | 836       | 11.28%  |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 7045      | 96.27%  |
| GDM     | 254       | 3.47%   |
| LightDM | 15        | 0.2%    |
| Unknown | 3         | 0.04%   |
| KDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 3874      | 52.12%  |
| de_DE   | 545       | 7.33%   |
| fr_FR   | 459       | 6.18%   |
| pt_BR   | 321       | 4.32%   |
| pl_PL   | 315       | 4.24%   |
| ru_RU   | 312       | 4.2%    |
| en_GB   | 236       | 3.18%   |
| it_IT   | 231       | 3.11%   |
| cs_CZ   | 182       | 2.45%   |
| es_ES   | 165       | 2.22%   |
| es_MX   | 87        | 1.17%   |
| es_AR   | 47        | 0.63%   |
| hu_HU   | 40        | 0.54%   |
| de_AT   | 40        | 0.54%   |
| en_CA   | 39        | 0.52%   |
| en_IN   | 36        | 0.48%   |
| nl_NL   | 35        | 0.47%   |
| pt_PT   | 30        | 0.4%    |
| en_AU   | 30        | 0.4%    |
| es_CL   | 29        | 0.39%   |
| tr_TR   | 27        | 0.36%   |
| es_CO   | 26        | 0.35%   |
| fr_BE   | 25        | 0.34%   |
| de_CH   | 22        | 0.3%    |
| fr_CA   | 21        | 0.28%   |
| nl_BE   | 20        | 0.27%   |
| fr_CH   | 19        | 0.26%   |
| da_DK   | 19        | 0.26%   |
| ro_RO   | 16        | 0.22%   |
| es_PE   | 16        | 0.22%   |
| es_VE   | 13        | 0.17%   |
| en_NZ   | 13        | 0.17%   |
| Unknown | 11        | 0.15%   |
| ru_UA   | 10        | 0.13%   |
| nb_NO   | 9         | 0.12%   |
| es_UY   | 9         | 0.12%   |
| es_CR   | 7         | 0.09%   |
| en_AG   | 7         | 0.09%   |
| es_EC   | 6         | 0.08%   |
| en_IE   | 6         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 3864      | 52.84%  |
| BIOS | 3448      | 47.16%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Overlay  | 5021      | 66.35%  |
| Ext4     | 2306      | 30.47%  |
| Btrfs    | 155       | 2.05%   |
| F2fs     | 36        | 0.48%   |
| Xfs      | 34        | 0.45%   |
| Ext2     | 7         | 0.09%   |
| Unknown  | 4         | 0.05%   |
| Ext3     | 2         | 0.03%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 4997      | 68%     |
| MBR     | 2342      | 31.87%  |
| Unknown | 9         | 0.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3837      | 51.54%  |
| Yes       | 3608      | 48.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4347      | 59.26%  |
| Yes       | 2989      | 40.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 1437      | 19.77%  |
| Hewlett-Packard       | 1262      | 17.37%  |
| Dell                  | 1061      | 14.6%   |
| ASUSTek Computer      | 891       | 12.26%  |
| Acer                  | 803       | 11.05%  |
| Toshiba               | 355       | 4.89%   |
| Samsung Electronics   | 164       | 2.26%   |
| Sony                  | 156       | 2.15%   |
| Apple                 | 133       | 1.83%   |
| MSI                   | 117       | 1.61%   |
| Fujitsu               | 93        | 1.28%   |
| Packard Bell          | 60        | 0.83%   |
| Positivo              | 58        | 0.8%    |
| Medion                | 53        | 0.73%   |
| HUAWEI                | 42        | 0.58%   |
| Unknown               | 36        | 0.5%    |
| Notebook              | 33        | 0.45%   |
| eMachines             | 30        | 0.41%   |
| Chuwi                 | 28        | 0.39%   |
| TUXEDO                | 27        | 0.37%   |
| Fujitsu Siemens       | 24        | 0.33%   |
| Philco                | 22        | 0.3%    |
| LG Electronics        | 21        | 0.29%   |
| Google                | 21        | 0.29%   |
| Gateway               | 14        | 0.19%   |
| Compaq                | 14        | 0.19%   |
| Clevo                 | 13        | 0.18%   |
| NEC Computers         | 12        | 0.17%   |
| Intel                 | 12        | 0.17%   |
| Alienware             | 12        | 0.17%   |
| System76              | 11        | 0.15%   |
| Panasonic             | 11        | 0.15%   |
| Gigabyte Technology   | 11        | 0.15%   |
| Timi                  | 10        | 0.14%   |
| GPU Company           | 10        | 0.14%   |
| Positivo Bahia - VAIO | 8         | 0.11%   |
| UMAX                  | 7         | 0.1%    |
| Wortmann AG           | 6         | 0.08%   |
| Teclast               | 6         | 0.08%   |
| Star Labs             | 5         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUS UX31E                     | 126       | 1.73%   |
| Unknown                        | 76        | 1.05%   |
| HP Notebook                    | 70        | 0.96%   |
| HP Pavilion g6                 | 35        | 0.48%   |
| Dell Inspiron 3451             | 32        | 0.44%   |
| Dell Latitude 3310             | 29        | 0.4%    |
| HP Pavilion dv6                | 26        | 0.36%   |
| Dell Latitude E6430            | 25        | 0.34%   |
| Toshiba dynabook T653/46JR     | 24        | 0.33%   |
| Dell Latitude E6410            | 22        | 0.3%    |
| Sony VGN-FZ31Z                 | 21        | 0.29%   |
| HP Pavilion 15                 | 20        | 0.28%   |
| Dell Latitude E6400            | 19        | 0.26%   |
| Dell Inspiron 15-3567          | 19        | 0.26%   |
| Lenovo IdeaPad 3 15ADA05 81W1  | 18        | 0.25%   |
| HP 15                          | 18        | 0.25%   |
| Dell Inspiron 1545             | 18        | 0.25%   |
| Lenovo IdeaPad S145-15AST 81N3 | 17        | 0.23%   |
| HP Pavilion Notebook           | 17        | 0.23%   |
| Dell Latitude E6420            | 17        | 0.23%   |
| Dell Latitude D630             | 17        | 0.23%   |
| Apple MacBookPro9,2            | 17        | 0.23%   |
| Positivo Mobile                | 16        | 0.22%   |
| Lenovo IdeaPad 1 14ADA05 82GW  | 16        | 0.22%   |
| ASUS S551LN                    | 15        | 0.21%   |
| Apple MacBookPro8,1            | 15        | 0.21%   |
| Dell Latitude E7450            | 14        | 0.19%   |
| HP Laptop 15-db0xxx            | 13        | 0.18%   |
| Dell Latitude E7440            | 13        | 0.18%   |
| Dell Latitude E6440            | 13        | 0.18%   |
| Dell Latitude 7490             | 13        | 0.18%   |
| Lenovo IdeaPad 330-15IKB 81DE  | 12        | 0.17%   |
| HP EliteBook 8440p             | 12        | 0.17%   |
| HP EliteBook 840 G3            | 12        | 0.17%   |
| HP Compaq Presario CQ60        | 12        | 0.17%   |
| Dell Latitude E5470            | 12        | 0.17%   |
| Lenovo V15-ADA 82C7            | 11        | 0.15%   |
| Lenovo IdeaPad 330S-15IKB 81F5 | 11        | 0.15%   |
| HP Pavilion dv7                | 11        | 0.15%   |
| HP Laptop 15s-eq2xxx           | 11        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 611       | 8.41%   |
| Acer Aspire           | 586       | 8.06%   |
| Dell Latitude         | 506       | 6.96%   |
| Lenovo IdeaPad        | 440       | 6.05%   |
| Dell Inspiron         | 331       | 4.55%   |
| Toshiba Satellite     | 272       | 3.74%   |
| HP Pavilion           | 258       | 3.55%   |
| HP Laptop             | 199       | 2.74%   |
| HP EliteBook          | 163       | 2.24%   |
| ASUS VivoBook         | 155       | 2.13%   |
| HP ProBook            | 147       | 2.02%   |
| ASUS UX31E            | 126       | 1.73%   |
| HP Compaq             | 101       | 1.39%   |
| Unknown               | 76        | 1.05%   |
| Fujitsu LIFEBOOK      | 71        | 0.98%   |
| HP Notebook           | 70        | 0.96%   |
| Dell Vostro           | 53        | 0.73%   |
| Dell Precision        | 53        | 0.73%   |
| Packard Bell EasyNote | 51        | 0.7%    |
| Dell XPS              | 49        | 0.67%   |
| Acer Nitro            | 47        | 0.65%   |
| Toshiba dynabook      | 46        | 0.63%   |
| Acer TravelMate       | 42        | 0.58%   |
| Acer Extensa          | 40        | 0.55%   |
| HP 250                | 34        | 0.47%   |
| Acer Swift            | 32        | 0.44%   |
| Lenovo Legion         | 30        | 0.41%   |
| Lenovo Yoga           | 29        | 0.4%    |
| HP 255                | 29        | 0.4%    |
| HP 15                 | 25        | 0.34%   |
| Dell Studio           | 25        | 0.34%   |
| HP Stream             | 24        | 0.33%   |
| HP ENVY               | 24        | 0.33%   |
| Dell System           | 22        | 0.3%    |
| ASUS ZenBook          | 22        | 0.3%    |
| Sony VGN-FZ31Z        | 21        | 0.29%   |
| ASUS ROG              | 21        | 0.29%   |
| HP OMEN               | 20        | 0.28%   |
| Apple MacBookPro9     | 20        | 0.28%   |
| Apple MacBookPro8     | 19        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 849       | 11.68%  |
| 2012    | 693       | 9.54%   |
| 2013    | 560       | 7.71%   |
| 2014    | 506       | 6.96%   |
| 2010    | 506       | 6.96%   |
| 2019    | 503       | 6.92%   |
| 2020    | 478       | 6.58%   |
| 2021    | 421       | 5.79%   |
| 2015    | 420       | 5.78%   |
| 2018    | 412       | 5.67%   |
| 2016    | 404       | 5.56%   |
| 2008    | 393       | 5.41%   |
| 2017    | 380       | 5.23%   |
| 2009    | 302       | 4.16%   |
| 2007    | 238       | 3.28%   |
| 2022    | 133       | 1.83%   |
| 2006    | 35        | 0.48%   |
| 2023    | 20        | 0.28%   |
| Unknown | 8         | 0.11%   |
| 2005    | 3         | 0.04%   |
| 2004    | 3         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7267      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 7267      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7230      | 99.48%  |
| Yes  | 38        | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 2484      | 33.92%  |
| 4.01-8.0    | 2381      | 32.51%  |
| 8.01-16.0   | 1022      | 13.96%  |
| 16.01-24.0  | 714       | 9.75%   |
| 1.01-2.0    | 308       | 4.21%   |
| 32.01-64.0  | 184       | 2.51%   |
| 2.01-3.0    | 146       | 1.99%   |
| 24.01-32.0  | 36        | 0.49%   |
| 64.01-256.0 | 32        | 0.44%   |
| 0.51-1.0    | 15        | 0.2%    |
| Unknown     | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 5632      | 74.88%  |
| 2.01-3.0  | 975       | 12.96%  |
| 0.51-1.0  | 690       | 9.17%   |
| 3.01-4.0  | 128       | 1.7%    |
| 0.01-0.5  | 58        | 0.77%   |
| 4.01-8.0  | 34        | 0.45%   |
| 8.01-16.0 | 3         | 0.04%   |
| Unknown   | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5360      | 73.08%  |
| 2      | 1636      | 22.31%  |
| 3      | 207       | 2.82%   |
| 0      | 105       | 1.43%   |
| 4      | 23        | 0.31%   |
| 5      | 2         | 0.03%   |
| 7      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3798      | 52.06%  |
| Yes       | 3498      | 47.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6238      | 85.83%  |
| No        | 1030      | 14.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7202      | 99.06%  |
| No        | 68        | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5225      | 71.61%  |
| No        | 2071      | 28.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 811       | 11.14%  |
| Germany     | 779       | 10.7%   |
| France      | 533       | 7.32%   |
| Brazil      | 515       | 7.07%   |
| Poland      | 441       | 6.06%   |
| Russia      | 395       | 5.42%   |
| Italy       | 350       | 4.81%   |
| UK          | 266       | 3.65%   |
| Spain       | 234       | 3.21%   |
| Czechia     | 215       | 2.95%   |
| Canada      | 182       | 2.5%    |
| Netherlands | 156       | 2.14%   |
| Mexico      | 139       | 1.91%   |
| Japan       | 130       | 1.78%   |
| India       | 121       | 1.66%   |
| Indonesia   | 91        | 1.25%   |
| Australia   | 88        | 1.21%   |
| Portugal    | 84        | 1.15%   |
| Romania     | 83        | 1.14%   |
| Belgium     | 81        | 1.11%   |
| Finland     | 73        | 1%      |
| Switzerland | 70        | 0.96%   |
| Hungary     | 66        | 0.91%   |
| Sweden      | 63        | 0.87%   |
| Turkey      | 62        | 0.85%   |
| Argentina   | 61        | 0.84%   |
| Austria     | 56        | 0.77%   |
| Ukraine     | 55        | 0.76%   |
| Colombia    | 52        | 0.71%   |
| Greece      | 49        | 0.67%   |
| Bulgaria    | 45        | 0.62%   |
| Slovakia    | 43        | 0.59%   |
| Chile       | 43        | 0.59%   |
| China       | 37        | 0.51%   |
| Norway      | 33        | 0.45%   |
| New Zealand | 32        | 0.44%   |
| Peru        | 31        | 0.43%   |
| Denmark     | 31        | 0.43%   |
| Serbia      | 30        | 0.41%   |
| Belarus     | 26        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Prague         | 131       | 1.73%   |
| Warsaw         | 80        | 1.06%   |
| Moscow         | 78        | 1.03%   |
| Paris          | 70        | 0.92%   |
| Schagen        | 56        | 0.74%   |
| Milan          | 55        | 0.73%   |
| Berlin         | 55        | 0.73%   |
| Krakow         | 51        | 0.67%   |
| Sao Paulo      | 42        | 0.55%   |
| Munich         | 39        | 0.51%   |
| St Petersburg  | 37        | 0.49%   |
| Rome           | 35        | 0.46%   |
| Vienna         | 32        | 0.42%   |
| Mexico City    | 30        | 0.4%    |
| Rio de Janeiro | 29        | 0.38%   |
| Helsinki       | 28        | 0.37%   |
| Hamburg        | 27        | 0.36%   |
| Madrid         | 26        | 0.34%   |
| Cologne        | 23        | 0.3%    |
| Athens         | 23        | 0.3%    |
| Sydney         | 22        | 0.29%   |
| Bucharest      | 22        | 0.29%   |
| Bengaluru      | 22        | 0.29%   |
| Wroclaw        | 21        | 0.28%   |
| Funchal        | 21        | 0.28%   |
| Budapest       | 21        | 0.28%   |
| Barcelona      | 21        | 0.28%   |
| Poznan         | 20        | 0.26%   |
| Krasnodar      | 20        | 0.26%   |
| Jakarta        | 20        | 0.26%   |
| Stuttgart      | 18        | 0.24%   |
| London         | 18        | 0.24%   |
| Lima           | 18        | 0.24%   |
| Istanbul       | 18        | 0.24%   |
| Brisbane       | 18        | 0.24%   |
| Bogotá        | 18        | 0.24%   |
| Melbourne      | 17        | 0.22%   |
| Buenos Aires   | 17        | 0.22%   |
| Gdansk         | 16        | 0.21%   |
| Curitiba       | 16        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1236      | 1363   | 14.15%  |
| Seagate             | 1025      | 1128   | 11.74%  |
| Samsung Electronics | 1020      | 1174   | 11.68%  |
| Toshiba             | 794       | 869    | 9.09%   |
| Kingston            | 526       | 564    | 6.02%   |
| SanDisk             | 482       | 515    | 5.52%   |
| Hitachi             | 397       | 425    | 4.55%   |
| Unknown             | 347       | 374    | 3.97%   |
| Crucial             | 328       | 369    | 3.76%   |
| HGST                | 266       | 291    | 3.05%   |
| SK hynix            | 241       | 263    | 2.76%   |
| Intel               | 166       | 195    | 1.9%    |
| A-DATA Technology   | 156       | 169    | 1.79%   |
| Micron Technology   | 137       | 149    | 1.57%   |
| China               | 99        | 103    | 1.13%   |
| GOODRAM             | 68        | 74     | 0.78%   |
| Apple               | 67        | 73     | 0.77%   |
| Fujitsu             | 66        | 70     | 0.76%   |
| PNY                 | 64        | 72     | 0.73%   |
| Unknown             | 64        | 69     | 0.73%   |
| KIOXIA              | 61        | 66     | 0.7%    |
| SPCC                | 60        | 63     | 0.69%   |
| Intenso             | 57        | 59     | 0.65%   |
| JMicron Technology  | 56        | 58     | 0.64%   |
| LITEON              | 55        | 56     | 0.63%   |
| Patriot             | 47        | 51     | 0.54%   |
| Transcend           | 45        | 46     | 0.52%   |
| Phison              | 37        | 40     | 0.42%   |
| KingSpec            | 29        | 29     | 0.33%   |
| Netac               | 28        | 33     | 0.32%   |
| SSSTC               | 27        | 32     | 0.31%   |
| UMIS                | 26        | 26     | 0.3%    |
| Silicon Motion      | 26        | 31     | 0.3%    |
| Apacer              | 24        | 24     | 0.27%   |
| Gigabyte Technology | 23        | 23     | 0.26%   |
| OCZ                 | 22        | 22     | 0.25%   |
| LITEONIT            | 22        | 26     | 0.25%   |
| ASMT                | 22        | 23     | 0.25%   |
| SABRENT             | 18        | 23     | 0.21%   |
| Hewlett-Packard     | 18        | 20     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB     | 139       | 1.56%   |
| SanDisk SSD U100 256GB              | 126       | 1.41%   |
| Kingston SA400S37240G 240GB SSD     | 114       | 1.28%   |
| Toshiba MQ01ABF050 500GB            | 113       | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 108       | 1.21%   |
| Toshiba MQ01ABD100 1TB              | 100       | 1.12%   |
| Seagate ST1000LM035-1RK172 1TB      | 99        | 1.11%   |
| Toshiba MQ04ABF100 1TB              | 81        | 0.91%   |
| Kingston SA400S37480G 480GB SSD     | 73        | 0.82%   |
| Seagate ST9500325AS 500GB           | 71        | 0.8%    |
| Unknown                             | 64        | 0.72%   |
| HGST HTS545050A7E680 500GB          | 59        | 0.66%   |
| Crucial CT240BX500SSD1 240GB        | 53        | 0.59%   |
| Samsung SSD 860 EVO 500GB           | 52        | 0.58%   |
| Kingston SA400S37120G 120GB SSD     | 52        | 0.58%   |
| HGST HTS721010A9E630 1TB            | 52        | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB            | 49        | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 46        | 0.52%   |
| HGST HTS541010A9E680 1TB            | 46        | 0.52%   |
| Toshiba MQ01ABD075 752GB            | 45        | 0.5%    |
| Crucial CT500MX500SSD1 500GB        | 39        | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 38        | 0.43%   |
| Unknown SD/MMC/MS PRO 16GB          | 37        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD    | 37        | 0.42%   |
| Seagate ST500LT012-9WS142 500GB     | 35        | 0.39%   |
| Samsung SSD 850 EVO 250GB           | 32        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 31        | 0.35%   |
| Samsung SSD 850 EVO 500GB           | 31        | 0.35%   |
| Hitachi HTS543232A7A384 320GB       | 31        | 0.35%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 30        | 0.34%   |
| WDC WD10SPZX-21Z10T0 1TB            | 30        | 0.34%   |
| HGST HTS545050A7E380 500GB          | 30        | 0.34%   |
| Seagate ST9320325AS 320GB           | 29        | 0.33%   |
| Hitachi HTS547550A9E384 500GB       | 29        | 0.33%   |
| Crucial CT1000MX500SSD1 1TB         | 29        | 0.33%   |
| Toshiba MQ01ABD050 500GB            | 28        | 0.31%   |
| Seagate ST1000LM048-2E7172 1TB      | 27        | 0.3%    |
| SanDisk DF4032  32GB                | 27        | 0.3%    |
| JMicron Generic 256GB               | 27        | 0.3%    |
| Hitachi HTS547575A9E384 752GB       | 27        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1004      | 1096   | 29.15%  |
| WDC                 | 863       | 936    | 25.06%  |
| Toshiba             | 681       | 741    | 19.77%  |
| Hitachi             | 397       | 425    | 11.53%  |
| HGST                | 266       | 291    | 7.72%   |
| Samsung Electronics | 75        | 78     | 2.18%   |
| Fujitsu             | 66        | 70     | 1.92%   |
| Unknown             | 37        | 37     | 1.07%   |
| Apple               | 15        | 15     | 0.44%   |
| External            | 7         | 7      | 0.2%    |
| USB                 | 5         | 5      | 0.15%   |
| SAGE                | 5         | 5      | 0.15%   |
| USB3.0              | 4         | 4      | 0.12%   |
| HGST HTS            | 3         | 3      | 0.09%   |
| SSK                 | 2         | 3      | 0.06%   |
| SABRENT             | 2         | 3      | 0.06%   |
| Intenso             | 2         | 2      | 0.06%   |
| Hewlett-Packard     | 2         | 2      | 0.06%   |
| ASMT                | 2         | 3      | 0.06%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| QC-FT-D             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ASMedia             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 588       | 652    | 17.34%  |
| Kingston            | 432       | 463    | 12.74%  |
| SanDisk             | 408       | 432    | 12.03%  |
| Crucial             | 292       | 326    | 8.61%   |
| WDC                 | 175       | 182    | 5.16%   |
| A-DATA Technology   | 122       | 130    | 3.6%    |
| China               | 99        | 103    | 2.92%   |
| SK hynix            | 81        | 87     | 2.39%   |
| Micron Technology   | 74        | 81     | 2.18%   |
| Toshiba             | 72        | 79     | 2.12%   |
| GOODRAM             | 67        | 73     | 1.98%   |
| Intel               | 63        | 69     | 1.86%   |
| PNY                 | 55        | 60     | 1.62%   |
| SPCC                | 54        | 55     | 1.59%   |
| LITEON              | 51        | 52     | 1.5%    |
| Intenso             | 50        | 52     | 1.47%   |
| Patriot             | 46        | 50     | 1.36%   |
| Transcend           | 42        | 43     | 1.24%   |
| Apple               | 38        | 39     | 1.12%   |
| Netac               | 27        | 32     | 0.8%    |
| KingSpec            | 27        | 27     | 0.8%    |
| OCZ                 | 22        | 22     | 0.65%   |
| LITEONIT            | 22        | 26     | 0.65%   |
| Apacer              | 22        | 22     | 0.65%   |
| Unknown             | 21        | 21     | 0.62%   |
| ASMT                | 16        | 16     | 0.47%   |
| Gigabyte Technology | 14        | 14     | 0.41%   |
| Verbatim            | 13        | 16     | 0.38%   |
| Seagate             | 13        | 16     | 0.38%   |
| SABRENT             | 13        | 16     | 0.38%   |
| Lexar               | 13        | 15     | 0.38%   |
| Hewlett-Packard     | 13        | 14     | 0.38%   |
| Plextor             | 11        | 11     | 0.32%   |
| JMicron Technology  | 11        | 12     | 0.32%   |
| Unknown             | 10        | 10     | 0.29%   |
| KingDian            | 10        | 11     | 0.29%   |
| Team                | 9         | 9      | 0.27%   |
| KIOXIA-EXCERIA      | 9         | 9      | 0.27%   |
| Corsair             | 9         | 11     | 0.27%   |
| Acer                | 9         | 10     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3321      | 3732   | 39.97%  |
| SSD     | 3137      | 3649   | 37.75%  |
| NVMe    | 1382      | 1666   | 16.63%  |
| MMC     | 382       | 427    | 4.6%    |
| Unknown | 87        | 91     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5871      | 7077   | 73.46%  |
| NVMe | 1360      | 1620   | 17.02%  |
| MMC  | 382       | 427    | 4.78%   |
| SAS  | 379       | 441    | 4.74%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4670      | 5453   | 73.37%  |
| 0.51-1.0   | 1543      | 1755   | 24.24%  |
| 1.01-2.0   | 121       | 140    | 1.9%    |
| 4.01-10.0  | 13        | 14     | 0.2%    |
| 3.01-4.0   | 11        | 12     | 0.17%   |
| 10.01-20.0 | 4         | 4      | 0.06%   |
| 2.01-3.0   | 3         | 3      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 3684      | 48.44%  |
| 101-250        | 1378      | 18.12%  |
| 251-500        | 909       | 11.95%  |
| 501-1000       | 462       | 6.07%   |
| 51-100         | 415       | 5.46%   |
| 21-50          | 328       | 4.31%   |
| Unknown        | 278       | 3.66%   |
| 1001-2000      | 105       | 1.38%   |
| 2001-3000      | 30        | 0.39%   |
| More than 3000 | 17        | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 6350      | 84.87%  |
| 21-50          | 299       | 4%      |
| Unknown        | 278       | 3.72%   |
| 51-100         | 198       | 2.65%   |
| 101-250        | 187       | 2.5%    |
| 251-500        | 101       | 1.35%   |
| 501-1000       | 42        | 0.56%   |
| 1001-2000      | 20        | 0.27%   |
| More than 3000 | 4         | 0.05%   |
| 2001-3000      | 2         | 0.03%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 126       | 127    | 6.96%   |
| Seagate ST9500325AS 500GB           | 52        | 55     | 2.87%   |
| Seagate ST500LT012-1DG142 500GB     | 43        | 47     | 2.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 41        | 47     | 2.26%   |
| HGST HTS545050A7E680 500GB          | 39        | 41     | 2.15%   |
| Seagate ST500LT012-9WS142 500GB     | 33        | 34     | 1.82%   |
| Toshiba MQ01ABF050 500GB            | 32        | 33     | 1.77%   |
| Toshiba MQ01ABD075 752GB            | 32        | 33     | 1.77%   |
| HGST HTS541010A9E680 1TB            | 29        | 31     | 1.6%    |
| Seagate ST9320325AS 320GB           | 25        | 25     | 1.38%   |
| Toshiba MQ01ABD100 1TB              | 22        | 23     | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB      | 21        | 22     | 1.16%   |
| Hitachi HTS543232A7A384 320GB       | 21        | 22     | 1.16%   |
| Toshiba MQ01ABD050 500GB            | 19        | 19     | 1.05%   |
| Hitachi HTS545050A7E380 500GB       | 18        | 20     | 0.99%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 16        | 16     | 0.88%   |
| HGST HTS721010A9E630 1TB            | 16        | 17     | 0.88%   |
| HGST HTS545050A7E380 500GB          | 16        | 17     | 0.88%   |
| Crucial CT240M500SSD1 240GB         | 15        | 16     | 0.83%   |
| Hitachi HTS547550A9E384 500GB       | 14        | 15     | 0.77%   |
| Kingston SV300S37A120G 120GB SSD    | 13        | 13     | 0.72%   |
| Hitachi HTS547575A9E384 752GB       | 13        | 14     | 0.72%   |
| HGST HTS725050A7E630 500GB          | 13        | 13     | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB            | 12        | 12     | 0.66%   |
| Seagate ST500LM021-1KJ152 500GB     | 12        | 12     | 0.66%   |
| Toshiba MK3265GSX 320GB             | 11        | 12     | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 10        | 11     | 0.55%   |
| Seagate ST9500420AS 500GB           | 10        | 10     | 0.55%   |
| Seagate ST9250827AS 250GB           | 10        | 13     | 0.55%   |
| Hitachi HTS545050B9A300 500GB       | 10        | 12     | 0.55%   |
| HGST HTS541075A9E680 752GB          | 10        | 12     | 0.55%   |
| Toshiba MK2555GSX 250GB             | 9         | 9      | 0.5%    |
| Seagate ST500LM000-1EJ162 500GB     | 9         | 10     | 0.5%    |
| Seagate ST320LT007-9ZV142 320GB     | 9         | 9      | 0.5%    |
| Hitachi HTS547564A9E384 640GB       | 9         | 10     | 0.5%    |
| Hitachi HTS542516K9SA00 160GB       | 9         | 9      | 0.5%    |
| Seagate ST9250410AS 250GB           | 8         | 9      | 0.44%   |
| Seagate ST9250315AS 250GB           | 8         | 9      | 0.44%   |
| Samsung Electronics HM641JI 640GB   | 8         | 10     | 0.44%   |
| Samsung Electronics HM160HI 160GB   | 8         | 8      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 413       | 442    | 22.88%  |
| Toshiba             | 287       | 300    | 15.9%   |
| WDC                 | 239       | 253    | 13.24%  |
| Hitachi             | 228       | 245    | 12.63%  |
| SanDisk             | 155       | 156    | 8.59%   |
| HGST                | 139       | 149    | 7.7%    |
| Samsung Electronics | 61        | 66     | 3.38%   |
| Kingston            | 40        | 42     | 2.22%   |
| Crucial             | 36        | 38     | 1.99%   |
| SK hynix            | 29        | 31     | 1.61%   |
| Fujitsu             | 25        | 28     | 1.39%   |
| Intel               | 23        | 26     | 1.27%   |
| A-DATA Technology   | 18        | 21     | 1%      |
| China               | 15        | 15     | 0.83%   |
| Micron Technology   | 14        | 15     | 0.78%   |
| LITEON              | 8         | 8      | 0.44%   |
| Apple               | 7         | 7      | 0.39%   |
| OCZ                 | 6         | 6      | 0.33%   |
| SPCC                | 5         | 5      | 0.28%   |
| KingSpec            | 5         | 5      | 0.28%   |
| Plextor             | 3         | 3      | 0.17%   |
| Netac               | 3         | 3      | 0.17%   |
| Intenso             | 3         | 3      | 0.17%   |
| Transcend           | 2         | 3      | 0.11%   |
| Teclast             | 2         | 2      | 0.11%   |
| PNY                 | 2         | 3      | 0.11%   |
| Hewlett-Packard     | 2         | 2      | 0.11%   |
| Dogfish             | 2         | 2      | 0.11%   |
| Corsair             | 2         | 3      | 0.11%   |
| ASMT                | 2         | 2      | 0.11%   |
| ASMedia             | 2         | 2      | 0.11%   |
| XrayDisk            | 1         | 1      | 0.06%   |
| Vaseky              | 1         | 1      | 0.06%   |
| USB                 | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |
| Union Memory        | 1         | 1      | 0.06%   |
| TakeMS              | 1         | 1      | 0.06%   |
| SSSTC               | 1         | 2      | 0.06%   |
| Smartbuy            | 1         | 1      | 0.06%   |
| RDM-II              | 1         | 1      | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 412       | 441    | 30.54%  |
| Toshiba             | 281       | 294    | 20.83%  |
| Hitachi             | 228       | 245    | 16.9%   |
| WDC                 | 218       | 231    | 16.16%  |
| HGST                | 139       | 149    | 10.3%   |
| Samsung Electronics | 39        | 41     | 2.89%   |
| Fujitsu             | 25        | 28     | 1.85%   |
| Apple               | 3         | 3      | 0.22%   |
| USB                 | 1         | 1      | 0.07%   |
| Magnetic Data       | 1         | 1      | 0.07%   |
| IBM/Hitachi         | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1333      | 1436   | 74.64%  |
| SSD     | 431       | 454    | 24.13%  |
| NVMe    | 21        | 24     | 1.18%   |
| Unknown | 1         | 1      | 0.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 4.44%   |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 4.44%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 4.44%   |
| Hitachi HTS723232A7A364 320GB         | 2         | 2      | 4.44%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 4.44%   |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 4.44%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 2.22%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 2.22%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 2.22%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 2.22%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 2.22%   |
| WDC WD3200BUCT-63TWBY0 320GB          | 1         | 1      | 2.22%   |
| WDC WD3200BEKT-60KA9T0 320GB          | 1         | 1      | 2.22%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 2.22%   |
| WDC WD2500BEVT-35A23T0 250GB          | 1         | 1      | 2.22%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 2.22%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 2.22%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.22%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 2.22%   |
| Toshiba MK3261GSYN 320GB              | 1         | 1      | 2.22%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 2.22%   |
| Toshiba MK2575GSX 250GB               | 1         | 1      | 2.22%   |
| Toshiba MK1234GSX 120GB               | 1         | 1      | 2.22%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 2.22%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 2.22%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.22%   |
| Samsung Electronics SSD PM800 TM 64GB | 1         | 1      | 2.22%   |
| Samsung Electronics HM500JI 500GB     | 1         | 1      | 2.22%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 2.22%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 2.22%   |
| Samsung Electronics HM250HI 250GB     | 1         | 1      | 2.22%   |
| Intel SSDSA2BW160G3 160GB             | 1         | 1      | 2.22%   |
| Hitachi HTS545050B9SA00 500GB         | 1         | 1      | 2.22%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 2.22%   |
| Hitachi HTS545016B9A300 160GB         | 1         | 1      | 2.22%   |
| Hitachi HTS543232A7A384 320GB         | 1         | 1      | 2.22%   |
| HGST HTS545050B7E660 500GB            | 1         | 1      | 2.22%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 2.22%   |
| Apple HDD HTS545050A7E362 500GB       | 1         | 1      | 2.22%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 15     | 33.33%  |
| Toshiba             | 8         | 9      | 17.78%  |
| Hitachi             | 8         | 8      | 17.78%  |
| Samsung Electronics | 5         | 5      | 11.11%  |
| Seagate             | 2         | 2      | 4.44%   |
| HGST                | 2         | 2      | 4.44%   |
| Crucial             | 2         | 2      | 4.44%   |
| SK hynix            | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| Apple               | 1         | 1      | 2.22%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5414      | 6749   | 68.16%  |
| Malfunc  | 1767      | 1915   | 22.25%  |
| Detected | 717       | 855    | 9.03%   |
| Failed   | 45        | 46     | 0.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 5543      | 69.18%  |
| AMD                                     | 1018      | 12.71%  |
| Samsung Electronics                     | 406       | 5.07%   |
| SanDisk                                 | 248       | 3.1%    |
| SK hynix                                | 145       | 1.81%   |
| Kingston Technology Company             | 98        | 1.22%   |
| Phison Electronics                      | 70        | 0.87%   |
| Micron Technology                       | 64        | 0.8%    |
| Nvidia                                  | 63        | 0.79%   |
| KIOXIA                                  | 63        | 0.79%   |
| Toshiba America Info Systems            | 45        | 0.56%   |
| Silicon Motion                          | 42        | 0.52%   |
| Micron/Crucial Technology               | 36        | 0.45%   |
| Union Memory (Shenzhen)                 | 29        | 0.36%   |
| ADATA Technology                        | 29        | 0.36%   |
| Solid State Storage Technology          | 26        | 0.32%   |
| Realtek Semiconductor                   | 17        | 0.21%   |
| Apple                                   | 10        | 0.12%   |
| Silicon Integrated Systems [SiS]        | 9         | 0.11%   |
| JMicron Technology                      | 9         | 0.11%   |
| Lenovo                                  | 6         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.06%   |
| ASMedia Technology                      | 5         | 0.06%   |
| Shenzhen Longsys Electronics            | 4         | 0.05%   |
| Seagate Technology                      | 4         | 0.05%   |
| Marvell Technology Group                | 4         | 0.05%   |
| Lite-On Technology                      | 4         | 0.05%   |
| Biwin Storage Technology                | 4         | 0.05%   |
| Silicon Image                           | 3         | 0.04%   |
| Yangtze Memory Technologies             | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 791       | 9.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 723       | 8.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 628       | 7.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 592       | 6.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 433       | 4.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 398       | 4.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 289       | 3.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 286       | 3.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 264       | 3.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 234       | 2.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 229       | 2.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 179       | 2.06%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 168       | 1.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 159       | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 155       | 1.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 151       | 1.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 144       | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 130       | 1.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 123       | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 101       | 1.16%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 98        | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                              | 93        | 1.07%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 86        | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 81        | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 74        | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 62        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 56        | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 55        | 0.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 54        | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 50        | 0.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 48        | 0.55%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 46        | 0.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 46        | 0.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 45        | 0.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 43        | 0.49%   |
| Intel SSD 660P Series                                                            | 42        | 0.48%   |
| SK hynix BC511 NVMe SSD                                                          | 40        | 0.46%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 39        | 0.45%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 38        | 0.44%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 35        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 5888      | 69.98%  |
| NVMe | 1356      | 16.12%  |
| IDE  | 627       | 7.45%   |
| RAID | 543       | 6.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 5954      | 81.93%  |
| AMD    | 1313      | 18.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 126       | 1.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 108       | 1.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 91        | 1.25%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 90        | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 85        | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 85        | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 84        | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 78        | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 74        | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 74        | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 64        | 0.88%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 63        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 63        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 61        | 0.84%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 60        | 0.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 60        | 0.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 59        | 0.81%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 58        | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 58        | 0.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 58        | 0.8%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 58        | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 54        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 51        | 0.7%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 51        | 0.7%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 50        | 0.69%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 50        | 0.69%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 50        | 0.69%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 49        | 0.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 49        | 0.67%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 48        | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 46        | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 45        | 0.62%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 44        | 0.6%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 44        | 0.6%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 43        | 0.59%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 40        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 39        | 0.54%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 38        | 0.52%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 38        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 37        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1789      | 24.61%  |
| Intel Core i7           | 1068      | 14.69%  |
| Intel Core i3           | 867       | 11.93%  |
| Intel Celeron           | 682       | 9.38%   |
| Intel Core 2 Duo        | 553       | 7.61%   |
| Other                   | 327       | 4.5%    |
| Intel Pentium           | 299       | 4.11%   |
| AMD Ryzen 5             | 230       | 3.16%   |
| AMD Ryzen 7             | 176       | 2.42%   |
| Intel Pentium Dual-Core | 122       | 1.68%   |
| AMD A6                  | 96        | 1.32%   |
| AMD Ryzen 3             | 86        | 1.18%   |
| AMD E                   | 79        | 1.09%   |
| AMD E1                  | 75        | 1.03%   |
| Intel Atom              | 70        | 0.96%   |
| Intel Pentium Dual      | 68        | 0.94%   |
| AMD A4                  | 66        | 0.91%   |
| AMD A8                  | 60        | 0.83%   |
| AMD A10                 | 45        | 0.62%   |
| Intel Pentium Silver    | 43        | 0.59%   |
| AMD E2                  | 42        | 0.58%   |
| AMD Athlon              | 38        | 0.52%   |
| Intel Core 2            | 36        | 0.5%    |
| Intel Genuine           | 33        | 0.45%   |
| AMD C-60                | 30        | 0.41%   |
| Intel Celeron Dual-Core | 26        | 0.36%   |
| AMD Ryzen 9             | 24        | 0.33%   |
| AMD Turion 64 X2 Mobile | 16        | 0.22%   |
| AMD Athlon II           | 16        | 0.22%   |
| AMD Athlon X2           | 15        | 0.21%   |
| AMD Phenom II           | 14        | 0.19%   |
| AMD Ryzen 5 PRO         | 13        | 0.18%   |
| AMD A12                 | 12        | 0.17%   |
| AMD Ryzen 7 PRO         | 11        | 0.15%   |
| AMD C-70                | 11        | 0.15%   |
| AMD Sempron             | 9         | 0.12%   |
| AMD Athlon 64 X2        | 9         | 0.12%   |
| Intel Core m3           | 8         | 0.11%   |
| AMD FX                  | 8         | 0.11%   |
| Intel Pentium Gold      | 7         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 5078      | 69.82%  |
| 4      | 1552      | 21.34%  |
| 6      | 222       | 3.05%   |
| 8      | 208       | 2.86%   |
| 1      | 163       | 2.24%   |
| 14     | 24        | 0.33%   |
| 10     | 9         | 0.12%   |
| 12     | 7         | 0.1%    |
| 3      | 5         | 0.07%   |
| 24     | 3         | 0.04%   |
| 16     | 1         | 0.01%   |
| 5      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7267      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4603      | 63.26%  |
| 1      | 2638      | 36.26%  |
| 4      | 18        | 0.25%   |
| 8      | 14        | 0.19%   |
| 12     | 2         | 0.03%   |
| 16     | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7264      | 99.96%  |
| Unknown        | 3         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1612      | 21.44%  |
| 0x206a7    | 714       | 9.5%    |
| 0x306a9    | 526       | 7%      |
| 0x1067a    | 346       | 4.6%    |
| 0x20655    | 279       | 3.71%   |
| 0x40651    | 256       | 3.41%   |
| 0x406e3    | 224       | 2.98%   |
| 0x306d4    | 215       | 2.86%   |
| 0x806e9    | 181       | 2.41%   |
| 0x6fd      | 172       | 2.29%   |
| 0x306c3    | 156       | 2.08%   |
| 0x08108109 | 146       | 1.94%   |
| 0x806ea    | 145       | 1.93%   |
| 0x30678    | 142       | 1.89%   |
| 0x806ec    | 128       | 1.7%    |
| 0x10676    | 125       | 1.66%   |
| 0x06006705 | 95        | 1.26%   |
| 0x806c1    | 92        | 1.22%   |
| 0x406c4    | 85        | 1.13%   |
| 0x20652    | 82        | 1.09%   |
| 0x706e5    | 76        | 1.01%   |
| 0x0500010d | 75        | 1%      |
| 0x906ea    | 72        | 0.96%   |
| 0x08608103 | 72        | 0.96%   |
| 0x506e3    | 69        | 0.92%   |
| 0x07030105 | 69        | 0.92%   |
| 0x506c9    | 68        | 0.9%    |
| 0x08108102 | 66        | 0.88%   |
| 0x706a1    | 63        | 0.84%   |
| 0x0a50000c | 61        | 0.81%   |
| 0x706a8    | 57        | 0.76%   |
| 0x08600106 | 44        | 0.59%   |
| 0x906e9    | 43        | 0.57%   |
| 0x406c3    | 39        | 0.52%   |
| 0x05000101 | 39        | 0.52%   |
| 0xa0652    | 37        | 0.49%   |
| 0x6fb      | 37        | 0.49%   |
| 0x08200103 | 33        | 0.44%   |
| 0x0600611a | 33        | 0.44%   |
| 0x0700010b | 32        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| SandyBridge      | 849       | 11.68%  |
| KabyLake         | 791       | 10.88%  |
| IvyBridge        | 645       | 8.87%   |
| Penryn           | 564       | 7.76%   |
| Haswell          | 517       | 7.11%   |
| Westmere         | 444       | 6.11%   |
| Skylake          | 407       | 5.6%    |
| Silvermont       | 344       | 4.73%   |
| Core             | 329       | 4.52%   |
| Broadwell        | 281       | 3.86%   |
| Zen+             | 222       | 3.05%   |
| Goldmont plus    | 172       | 2.37%   |
| TigerLake        | 168       | 2.31%   |
| Bobcat           | 167       | 2.3%    |
| Excavator        | 157       | 2.16%   |
| Unknown          | 139       | 1.91%   |
| IceLake          | 117       | 1.61%   |
| Puma             | 103       | 1.42%   |
| Zen 2            | 102       | 1.4%    |
| Zen 3            | 95        | 1.31%   |
| Goldmont         | 83        | 1.14%   |
| Zen              | 79        | 1.09%   |
| CometLake        | 62        | 0.85%   |
| Jaguar           | 54        | 0.74%   |
| K10              | 53        | 0.73%   |
| Piledriver       | 51        | 0.7%    |
| Bonnell          | 51        | 0.7%    |
| Alderlake Hybrid | 47        | 0.65%   |
| K8 Hammer        | 43        | 0.59%   |
| K8 & K10 hybrid  | 32        | 0.44%   |
| K10 Llano        | 31        | 0.43%   |
| Nehalem          | 29        | 0.4%    |
| Tremont          | 26        | 0.36%   |
| Steamroller      | 14        | 0.19%   |
| Gracemont        | 3         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5337      | 62%     |
| AMD                              | 1756      | 20.4%   |
| Nvidia                           | 1507      | 17.51%  |
| Silicon Integrated Systems [SiS] | 8         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 788       | 8.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 603       | 6.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 390       | 4.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 323       | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 313       | 3.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 271       | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 254       | 2.84%   |
| Intel HD Graphics 5500                                                                   | 240       | 2.68%   |
| Intel HD Graphics 620                                                                    | 237       | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 194       | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 179       | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 179       | 2%      |
| Intel UHD Graphics 620                                                                   | 168       | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 167       | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 150       | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 142       | 1.59%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 116       | 1.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 113       | 1.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 100       | 1.12%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 97        | 1.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 92        | 1.03%   |
| AMD Lucienne                                                                             | 85        | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 83        | 0.93%   |
| Intel HD Graphics 530                                                                    | 78        | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 77        | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 73        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 72        | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 71        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 71        | 0.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 68        | 0.76%   |
| Intel HD Graphics 500                                                                    | 61        | 0.68%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 58        | 0.65%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 53        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 50        | 0.56%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 50        | 0.56%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 50        | 0.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 49        | 0.55%   |
| Intel HD Graphics 630                                                                    | 48        | 0.54%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 48        | 0.54%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 44        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 3893      | 53.36%  |
| 1 x AMD        | 1295      | 17.75%  |
| Intel + Nvidia | 1011      | 13.86%  |
| 1 x Nvidia     | 403       | 5.52%   |
| Intel + AMD    | 241       | 3.3%    |
| 2 x Intel      | 216       | 2.96%   |
| 2 x AMD        | 135       | 1.85%   |
| AMD + Nvidia   | 87        | 1.19%   |
| 1 x SiS        | 8         | 0.11%   |
| 2 x Nvidia     | 7         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 7179      | 98.5%   |
| Unknown     | 70        | 0.96%   |
| Proprietary | 39        | 0.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4273      | 58.59%  |
| 0.01-0.5   | 1173      | 16.08%  |
| 1.01-2.0   | 829       | 11.37%  |
| 0.51-1.0   | 582       | 7.98%   |
| 3.01-4.0   | 281       | 3.85%   |
| 5.01-6.0   | 78        | 1.07%   |
| 7.01-8.0   | 50        | 0.69%   |
| 2.01-3.0   | 20        | 0.27%   |
| 8.01-16.0  | 7         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1572      | 20.88%  |
| LG Display              | 1270      | 16.87%  |
| Chimei Innolux          | 1038      | 13.79%  |
| BOE                     | 1008      | 13.39%  |
| Samsung Electronics     | 879       | 11.67%  |
| Chi Mei Optoelectronics | 267       | 3.55%   |
| Lenovo                  | 183       | 2.43%   |
| CPT                     | 148       | 1.97%   |
| Apple                   | 134       | 1.78%   |
| LG Philips              | 112       | 1.49%   |
| Sharp                   | 89        | 1.18%   |
| PANDA                   | 72        | 0.96%   |
| InfoVision              | 69        | 0.92%   |
| Dell                    | 67        | 0.89%   |
| Goldstar                | 63        | 0.84%   |
| Eizo                    | 61        | 0.81%   |
| Acer                    | 49        | 0.65%   |
| Hewlett-Packard         | 44        | 0.58%   |
| Sony                    | 32        | 0.43%   |
| AOC                     | 31        | 0.41%   |
| Philips                 | 30        | 0.4%    |
| BenQ                    | 20        | 0.27%   |
| Toshiba                 | 18        | 0.24%   |
| InnoLux Display         | 17        | 0.23%   |
| CSO                     | 17        | 0.23%   |
| HannStar                | 16        | 0.21%   |
| Panasonic               | 15        | 0.2%    |
| Iiyama                  | 14        | 0.19%   |
| ASUSTek Computer        | 14        | 0.19%   |
| Ancor Communications    | 14        | 0.19%   |
| ViewSonic               | 13        | 0.17%   |
| Unknown                 | 10        | 0.13%   |
| KDC                     | 8         | 0.11%   |
| Quanta Display          | 7         | 0.09%   |
| HKC                     | 7         | 0.09%   |
| Vizio                   | 6         | 0.08%   |
| Hitachi                 | 6         | 0.08%   |
| Fujitsu Siemens         | 6         | 0.08%   |
| Vestel Elektronik       | 5         | 0.07%   |
| IBM                     | 5         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 126       | 1.67%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 77        | 1.02%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 75        | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 71        | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 64        | 0.85%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 62        | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 59        | 0.78%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 57        | 0.75%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 52        | 0.69%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 51        | 0.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 40        | 0.53%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 39        | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 39        | 0.52%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 38        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 33        | 0.44%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 33        | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 32        | 0.42%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 31        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 31        | 0.41%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 30        | 0.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 29        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 28        | 0.37%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 27        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 26        | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 26        | 0.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 26        | 0.34%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 26        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 25        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 25        | 0.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 25        | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 24        | 0.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 24        | 0.32%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 24        | 0.32%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 23        | 0.3%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 23        | 0.3%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 22        | 0.29%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 22        | 0.29%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 22        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 21        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 3244      | 43.88%  |
| 1920x1080 (FHD)    | 2232      | 30.19%  |
| 1600x900 (HD+)     | 634       | 8.58%   |
| 1280x800 (WXGA)    | 419       | 5.67%   |
| 1440x900 (WXGA+)   | 185       | 2.5%    |
| 3840x2160 (4K)     | 180       | 2.43%   |
| 1920x1200 (WUXGA)  | 80        | 1.08%   |
| 2560x1440 (QHD)    | 71        | 0.96%   |
| 2560x1600          | 63        | 0.85%   |
| 1680x1050 (WSXGA+) | 55        | 0.74%   |
| 1024x600           | 26        | 0.35%   |
| 2880x1800          | 25        | 0.34%   |
| 3200x1800 (QHD+)   | 20        | 0.27%   |
| 1280x1024 (SXGA)   | 19        | 0.26%   |
| 2160x1440          | 15        | 0.2%    |
| 1360x768           | 14        | 0.19%   |
| 1024x768 (XGA)     | 12        | 0.16%   |
| 1680x945           | 11        | 0.15%   |
| 1920x540           | 10        | 0.14%   |
| 2288x1287          | 9         | 0.12%   |
| 3840x2400          | 8         | 0.11%   |
| 2560x1080          | 8         | 0.11%   |
| 3440x1440          | 7         | 0.09%   |
| 2256x1504          | 7         | 0.09%   |
| 1920x1280          | 6         | 0.08%   |
| 800x1280           | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |
| 3456x2160          | 3         | 0.04%   |
| 2240x1400          | 3         | 0.04%   |
| 3200x2000          | 2         | 0.03%   |
| 1280x720 (HD)      | 2         | 0.03%   |
| 1152x864           | 2         | 0.03%   |
| 3840x1100          | 1         | 0.01%   |
| 3840x1080          | 1         | 0.01%   |
| 3300x2200          | 1         | 0.01%   |
| 3072x1920          | 1         | 0.01%   |
| 3000x2000          | 1         | 0.01%   |
| 2880x1920          | 1         | 0.01%   |
| 2560x1700          | 1         | 0.01%   |
| 2304x1440          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3492      | 46.32%  |
| 13      | 1163      | 15.43%  |
| 14      | 885       | 11.74%  |
| 17      | 720       | 9.55%   |
| 12      | 248       | 3.29%   |
| 11      | 176       | 2.33%   |
| 23      | 107       | 1.42%   |
| 31      | 93        | 1.23%   |
| 27      | 93        | 1.23%   |
| 18      | 73        | 0.97%   |
| 24      | 71        | 0.94%   |
| 16      | 67        | 0.89%   |
| 21      | 66        | 0.88%   |
| 10      | 42        | 0.56%   |
| 19      | 32        | 0.42%   |
| 20      | 28        | 0.37%   |
| 54      | 17        | 0.23%   |
| 22      | 16        | 0.21%   |
| 84      | 15        | 0.2%    |
| 26      | 14        | 0.19%   |
| Unknown | 14        | 0.19%   |
| 72      | 12        | 0.16%   |
| 34      | 12        | 0.16%   |
| 32      | 11        | 0.15%   |
| 40      | 10        | 0.13%   |
| 142     | 7         | 0.09%   |
| 65      | 7         | 0.09%   |
| 39      | 5         | 0.07%   |
| 25      | 5         | 0.07%   |
| 52      | 4         | 0.05%   |
| 48      | 4         | 0.05%   |
| 46      | 4         | 0.05%   |
| 7       | 4         | 0.05%   |
| 37      | 3         | 0.04%   |
| 74      | 2         | 0.03%   |
| 55      | 2         | 0.03%   |
| 42      | 2         | 0.03%   |
| 36      | 2         | 0.03%   |
| 86      | 1         | 0.01%   |
| 85      | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 4887      | 65%     |
| 201-300        | 1037      | 13.79%  |
| 351-400        | 878       | 11.68%  |
| 501-600        | 267       | 3.55%   |
| 401-500        | 201       | 2.67%   |
| 601-700        | 104       | 1.38%   |
| 1001-1500      | 42        | 0.56%   |
| 1501-2000      | 30        | 0.4%    |
| 701-800        | 26        | 0.35%   |
| 801-900        | 19        | 0.25%   |
| Unknown        | 14        | 0.19%   |
| More than 2000 | 7         | 0.09%   |
| 1-100          | 4         | 0.05%   |
| 901-1000       | 2         | 0.03%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6112      | 86.35%  |
| 16/10   | 834       | 11.78%  |
| 3/2     | 55        | 0.78%   |
| 5/4     | 22        | 0.31%   |
| 4/3     | 21        | 0.3%    |
| 21/9    | 13        | 0.18%   |
| 1.00    | 7         | 0.1%    |
| 32/9    | 4         | 0.06%   |
| 0.67    | 4         | 0.06%   |
| Unknown | 2         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3493      | 46.34%  |
| 81-90          | 1558      | 20.67%  |
| 121-130        | 599       | 7.95%   |
| 71-80          | 488       | 6.47%   |
| 61-70          | 240       | 3.18%   |
| 201-250        | 225       | 2.98%   |
| 51-60          | 178       | 2.36%   |
| 351-500        | 120       | 1.59%   |
| 131-140        | 120       | 1.59%   |
| 301-350        | 99        | 1.31%   |
| 151-200        | 78        | 1.03%   |
| 141-150        | 76        | 1.01%   |
| More than 1000 | 73        | 0.97%   |
| 111-120        | 46        | 0.61%   |
| 41-50          | 42        | 0.56%   |
| 251-300        | 33        | 0.44%   |
| 501-1000       | 28        | 0.37%   |
| 91-100         | 23        | 0.31%   |
| Unknown        | 14        | 0.19%   |
| 1-40           | 5         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 3295      | 44.42%  |
| 121-160       | 2526      | 34.05%  |
| 51-100        | 1082      | 14.59%  |
| 161-240       | 354       | 4.77%   |
| More than 240 | 82        | 1.11%   |
| 1-50          | 65        | 0.88%   |
| Unknown       | 14        | 0.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6639      | 90.83%  |
| 2     | 619       | 8.47%   |
| 0     | 40        | 0.55%   |
| 3     | 9         | 0.12%   |
| 4     | 2         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3908      | 33.19%  |
| Intel                             | 3232      | 27.45%  |
| Qualcomm Atheros                  | 2335      | 19.83%  |
| Broadcom                          | 803       | 6.82%   |
| Broadcom Limited                  | 205       | 1.74%   |
| Marvell Technology Group          | 188       | 1.6%    |
| Samsung Electronics               | 152       | 1.29%   |
| Ralink                            | 141       | 1.2%    |
| MediaTek                          | 99        | 0.84%   |
| JMicron Technology                | 71        | 0.6%    |
| Dell                              | 68        | 0.58%   |
| TP-Link                           | 56        | 0.48%   |
| Huawei Technologies               | 52        | 0.44%   |
| Ericsson Business Mobile Networks | 51        | 0.43%   |
| Ralink Technology                 | 48        | 0.41%   |
| Nvidia                            | 41        | 0.35%   |
| ASIX Electronics                  | 39        | 0.33%   |
| Sierra Wireless                   | 37        | 0.31%   |
| Hewlett-Packard                   | 22        | 0.19%   |
| Xiaomi                            | 18        | 0.15%   |
| Qualcomm Atheros Communications   | 16        | 0.14%   |
| DisplayLink                       | 14        | 0.12%   |
| D-Link                            | 13        | 0.11%   |
| NetGear                           | 11        | 0.09%   |
| Qualcomm                          | 10        | 0.08%   |
| Motorola PCS                      | 10        | 0.08%   |
| Linksys                           | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.08%   |
| OPPO Electronics                  | 9         | 0.08%   |
| ASUSTek Computer                  | 8         | 0.07%   |
| ICS Advent                        | 7         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.05%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.05%   |
| D-Link System                     | 6         | 0.05%   |
| Belkin Components                 | 6         | 0.05%   |
| Lenovo                            | 5         | 0.04%   |
| Edimax Technology                 | 5         | 0.04%   |
| Apple                             | 5         | 0.04%   |
| Attansic Technology               | 4         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2177      | 15.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 968       | 6.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 428       | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 415       | 2.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 369       | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 351       | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 328       | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 250       | 1.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 238       | 1.69%   |
| Intel Wireless 7265                                                     | 229       | 1.63%   |
| Intel Wireless 7260                                                     | 187       | 1.33%   |
| Intel Wireless 8265 / 8275                                              | 185       | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 170       | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 165       | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 165       | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 161       | 1.15%   |
| Intel Wireless 8260                                                     | 159       | 1.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 157       | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 143       | 1.02%   |
| Intel Wi-Fi 6 AX200                                                     | 140       | 1%      |
| Intel Wireless 3165                                                     | 133       | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 127       | 0.9%    |
| Intel Wireless 3160                                                     | 117       | 0.83%   |
| Intel WiFi Link 5100                                                    | 115       | 0.82%   |
| Intel Wi-Fi 6 AX201                                                     | 113       | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 111       | 0.79%   |
| Intel 82577LM Gigabit Network Connection                                | 110       | 0.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 107       | 0.76%   |
| Intel 82567LM Gigabit Network Connection                                | 99        | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 96        | 0.68%   |
| Intel Centrino Advanced-N 6200                                          | 93        | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 90        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                          | 87        | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 85        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 83        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 83        | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 78        | 0.55%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 78        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                   | 77        | 0.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 76        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3069      | 41.05%  |
| Qualcomm Atheros                      | 2038      | 27.26%  |
| Realtek Semiconductor                 | 1268      | 16.96%  |
| Broadcom                              | 540       | 7.22%   |
| Ralink                                | 141       | 1.89%   |
| Broadcom Limited                      | 96        | 1.28%   |
| MediaTek                              | 88        | 1.18%   |
| Ralink Technology                     | 48        | 0.64%   |
| Sierra Wireless                       | 37        | 0.49%   |
| Dell                                  | 35        | 0.47%   |
| TP-Link                               | 23        | 0.31%   |
| Qualcomm Atheros Communications       | 16        | 0.21%   |
| Ericsson Business Mobile Networks     | 9         | 0.12%   |
| D-Link                                | 9         | 0.12%   |
| Linksys                               | 8         | 0.11%   |
| NetGear                               | 6         | 0.08%   |
| Hewlett-Packard                       | 6         | 0.08%   |
| D-Link System                         | 6         | 0.08%   |
| ASUSTek Computer                      | 6         | 0.08%   |
| Edimax Technology                     | 5         | 0.07%   |
| Belkin Components                     | 5         | 0.07%   |
| Qualcomm                              | 3         | 0.04%   |
| Qcom                                  | 3         | 0.04%   |
| AVM                                   | 3         | 0.04%   |
| Fibocom                               | 2         | 0.03%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Senao                                 | 1         | 0.01%   |
| PLANEX                                | 1         | 0.01%   |
| Microsoft                             | 1         | 0.01%   |
| Mercucys                              | 1         | 0.01%   |
| Elecom                                | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 428       | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 415       | 5.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 369       | 4.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 351       | 4.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 250       | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 238       | 3.17%   |
| Intel Wireless 7265                                                     | 229       | 3.05%   |
| Intel Wireless 7260                                                     | 187       | 2.49%   |
| Intel Wireless 8265 / 8275                                              | 185       | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 170       | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 165       | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 165       | 2.2%    |
| Intel Wireless 8260                                                     | 159       | 2.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 157       | 2.09%   |
| Intel Wi-Fi 6 AX200                                                     | 140       | 1.87%   |
| Intel Wireless 3165                                                     | 133       | 1.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 127       | 1.69%   |
| Intel Wireless 3160                                                     | 117       | 1.56%   |
| Intel WiFi Link 5100                                                    | 115       | 1.53%   |
| Intel Wi-Fi 6 AX201                                                     | 113       | 1.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 107       | 1.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 96        | 1.28%   |
| Intel Centrino Advanced-N 6200                                          | 93        | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 90        | 1.2%    |
| Intel Centrino Ultimate-N 6300                                          | 87        | 1.16%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 85        | 1.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 83        | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 83        | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 78        | 1.04%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 78        | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 76        | 1.01%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 74        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 69        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 67        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 66        | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 66        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 65        | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 63        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 59        | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 56        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3387      | 52.96%  |
| Intel                            | 1210      | 18.92%  |
| Qualcomm Atheros                 | 592       | 9.26%   |
| Broadcom                         | 380       | 5.94%   |
| Marvell Technology Group         | 188       | 2.94%   |
| Samsung Electronics              | 152       | 2.38%   |
| Broadcom Limited                 | 113       | 1.77%   |
| JMicron Technology               | 71        | 1.11%   |
| Huawei Technologies              | 44        | 0.69%   |
| Nvidia                           | 40        | 0.63%   |
| ASIX Electronics                 | 39        | 0.61%   |
| TP-Link                          | 33        | 0.52%   |
| Xiaomi                           | 18        | 0.28%   |
| DisplayLink                      | 14        | 0.22%   |
| MediaTek                         | 11        | 0.17%   |
| Silicon Integrated Systems [SiS] | 9         | 0.14%   |
| OPPO Electronics                 | 9         | 0.14%   |
| Motorola PCS                     | 8         | 0.13%   |
| Qualcomm                         | 7         | 0.11%   |
| ICS Advent                       | 7         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.09%   |
| OnePlus Technology (Shenzhen)    | 6         | 0.09%   |
| NetGear                          | 5         | 0.08%   |
| Lenovo                           | 5         | 0.08%   |
| Hewlett-Packard                  | 5         | 0.08%   |
| Apple                            | 5         | 0.08%   |
| D-Link                           | 4         | 0.06%   |
| Attansic Technology              | 4         | 0.06%   |
| Microchip Technology             | 3         | 0.05%   |
| Google                           | 3         | 0.05%   |
| vivo                             | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| Linksys                          | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| Sitecom Europe                   | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| HMD Global                       | 1         | 0.02%   |
| Belkin Components                | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2177      | 33.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 968       | 15.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 328       | 5.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 161       | 2.5%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 143       | 2.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 111       | 1.72%   |
| Intel 82577LM Gigabit Network Connection                                       | 110       | 1.71%   |
| Intel 82567LM Gigabit Network Connection                                       | 99        | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                                          | 77        | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 74        | 1.15%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 73        | 1.13%   |
| Intel Ethernet Connection I219-LM                                              | 71        | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                          | 67        | 1.04%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 66        | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 61        | 0.95%   |
| Intel Ethernet Connection I217-LM                                              | 61        | 0.95%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 59        | 0.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 57        | 0.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 53        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 48        | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 47        | 0.73%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 43        | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 41        | 0.64%   |
| Intel 82566MM Gigabit Network Connection                                       | 39        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 39        | 0.61%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 37        | 0.57%   |
| Intel 82579V Gigabit Network Connection                                        | 36        | 0.56%   |
| Huawei E353/E3131                                                              | 36        | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 35        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 35        | 0.54%   |
| Intel Ethernet Connection I219-V                                               | 33        | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 32        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 31        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 30        | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 30        | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 29        | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 29        | 0.45%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 29        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                           | 27        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 27        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7203      | 53.13%  |
| Ethernet | 6234      | 45.98%  |
| Modem    | 106       | 0.78%   |
| Unknown  | 14        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5037      | 70.2%   |
| Ethernet | 2137      | 29.78%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5694      | 78.33%  |
| 1     | 1467      | 20.18%  |
| 0     | 85        | 1.17%   |
| 3     | 23        | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5199      | 70.51%  |
| Yes  | 2174      | 29.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2005      | 38.18%  |
| Qualcomm Atheros Communications | 622       | 11.84%  |
| Realtek Semiconductor           | 612       | 11.65%  |
| Broadcom                        | 385       | 7.33%   |
| Lite-On Technology              | 340       | 6.47%   |
| IMC Networks                    | 275       | 5.24%   |
| Foxconn / Hon Hai               | 230       | 4.38%   |
| Dell                            | 137       | 2.61%   |
| Apple                           | 119       | 2.27%   |
| Toshiba                         | 114       | 2.17%   |
| Hewlett-Packard                 | 106       | 2.02%   |
| Cambridge Silicon Radio         | 68        | 1.29%   |
| Ralink                          | 59        | 1.12%   |
| Realtek                         | 28        | 0.53%   |
| ASUSTek Computer                | 26        | 0.5%    |
| Foxconn International           | 23        | 0.44%   |
| Alps Electric                   | 21        | 0.4%    |
| Ralink Technology               | 14        | 0.27%   |
| Chicony Electronics             | 13        | 0.25%   |
| Askey Computer                  | 12        | 0.23%   |
| Fujitsu                         | 7         | 0.13%   |
| Taiyo Yuden                     | 6         | 0.11%   |
| MediaTek                        | 6         | 0.11%   |
| Micro Star International        | 4         | 0.08%   |
| Unknown                         | 4         | 0.08%   |
| USI                             | 3         | 0.06%   |
| TP-Link                         | 3         | 0.06%   |
| Smart Modular Technologies      | 2         | 0.04%   |
| Edimax Technology               | 2         | 0.04%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Integrated System Solution      | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1039      | 19.78%  |
| Realtek Bluetooth Radio                                                             | 390       | 7.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 278       | 5.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 276       | 5.25%   |
| Intel AX201 Bluetooth                                                               | 212       | 4.04%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 144       | 2.74%   |
| Intel AX200 Bluetooth                                                               | 138       | 2.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 123       | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 117       | 2.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 110       | 2.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 109       | 2.08%   |
| IMC Networks Bluetooth Radio                                                        | 97        | 1.85%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 92        | 1.75%   |
| Intel Bluetooth Device                                                              | 87        | 1.66%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 84        | 1.6%    |
| IMC Networks Bluetooth Device                                                       | 83        | 1.58%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 80        | 1.52%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 71        | 1.35%   |
| Lite-On Bluetooth Device                                                            | 70        | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 68        | 1.29%   |
| Apple Bluetooth Host Controller                                                     | 66        | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 65        | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 62        | 1.18%   |
| Dell DW375 Bluetooth Module                                                         | 61        | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 60        | 1.14%   |
| Ralink RT3290 Bluetooth                                                             | 59        | 1.12%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 45        | 0.86%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 43        | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 42        | 0.8%    |
| Toshiba Bluetooth Device                                                            | 37        | 0.7%    |
| Apple Bluetooth USB Host Controller                                                 | 37        | 0.7%    |
| Realtek RTL8723B Bluetooth                                                          | 36        | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 34        | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 33        | 0.63%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 33        | 0.63%   |
| Intel AX210 Bluetooth                                                               | 32        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 32        | 0.61%   |
| Broadcom HP Portable SoftSailing                                                    | 30        | 0.57%   |
| Realtek Bluetooth Radio                                                             | 28        | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 28        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 5886      | 70.41%  |
| AMD                                          | 1496      | 17.89%  |
| Nvidia                                       | 812       | 9.71%   |
| C-Media Electronics                          | 21        | 0.25%   |
| Realtek Semiconductor                        | 12        | 0.14%   |
| Logitech                                     | 12        | 0.14%   |
| Generalplus Technology                       | 12        | 0.14%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.11%   |
| JMTek                                        | 8         | 0.1%    |
| Creative Technology                          | 8         | 0.1%    |
| Apple                                        | 8         | 0.1%    |
| Lenovo                                       | 7         | 0.08%   |
| GN Netcom                                    | 7         | 0.08%   |
| Texas Instruments                            | 6         | 0.07%   |
| Plantronics                                  | 5         | 0.06%   |
| ASUSTek Computer                             | 4         | 0.05%   |
| Focusrite-Novation                           | 3         | 0.04%   |
| Corsair                                      | 3         | 0.04%   |
| Conexant Systems                             | 3         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.02%   |
| Razer USA                                    | 2         | 0.02%   |
| PreSonus Audio Electronics                   | 2         | 0.02%   |
| No brand                                     | 2         | 0.02%   |
| M-Audio                                      | 2         | 0.02%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.01%   |
| Yamaha                                       | 1         | 0.01%   |
| XMOS                                         | 1         | 0.01%   |
| VIA Technologies                             | 1         | 0.01%   |
| TTGK Technology                              | 1         | 0.01%   |
| THX                                          | 1         | 0.01%   |
| TerraTec Electronic                          | 1         | 0.01%   |
| Tenx Technology                              | 1         | 0.01%   |
| TEAC                                         | 1         | 0.01%   |
| Schiit Audio                                 | 1         | 0.01%   |
| SAVITECH                                     | 1         | 0.01%   |
| Samsung Electronics                          | 1         | 0.01%   |
| Samson Technologies                          | 1         | 0.01%   |
| RODE Microphones                             | 1         | 0.01%   |
| Phison Electronics                           | 1         | 0.01%   |
| Nordic Semiconductor ASA                     | 1         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 812       | 7.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 743       | 7.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 682       | 6.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 596       | 5.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 518       | 5.02%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 473       | 4.59%   |
| Intel 8 Series HD Audio Controller                                                                | 318       | 3.08%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 315       | 3.06%   |
| AMD FCH Azalia Controller                                                                         | 315       | 3.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 285       | 2.76%   |
| Intel Broadwell-U Audio Controller                                                                | 281       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 281       | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 280       | 2.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 236       | 2.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 207       | 2.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 201       | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 200       | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 190       | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 172       | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 171       | 1.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 168       | 1.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 157       | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 150       | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 140       | 1.36%   |
| AMD Wrestler HDMI Audio                                                                           | 139       | 1.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 114       | 1.11%   |
| AMD High Definition Audio Controller                                                              | 113       | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 101       | 0.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 96        | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 93        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 90        | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 89        | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 83        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 76        | 0.74%   |
| Intel CM238 HD Audio Controller                                                                   | 61        | 0.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 61        | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 59        | 0.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 53        | 0.51%   |
| AMD Trinity HDMI Audio Controller                                                                 | 51        | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 50        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2334      | 26.41%  |
| SK hynix            | 1856      | 21%     |
| Micron Technology   | 893       | 10.1%   |
| Kingston            | 781       | 8.84%   |
| Unknown             | 740       | 8.37%   |
| Elpida              | 362       | 4.1%    |
| Crucial             | 290       | 3.28%   |
| Ramaxel Technology  | 231       | 2.61%   |
| A-DATA Technology   | 206       | 2.33%   |
| Nanya Technology    | 184       | 2.08%   |
| Smart               | 145       | 1.64%   |
| Unknown (ABCD)      | 94        | 1.06%   |
| Corsair             | 84        | 0.95%   |
| Unknown             | 55        | 0.62%   |
| G.Skill             | 44        | 0.5%    |
| Teikon              | 39        | 0.44%   |
| Transcend           | 33        | 0.37%   |
| ASint Technology    | 32        | 0.36%   |
| Patriot             | 30        | 0.34%   |
| Team                | 29        | 0.33%   |
| Apacer              | 25        | 0.28%   |
| High Bridge         | 24        | 0.27%   |
| GOODRAM             | 22        | 0.25%   |
| AMD                 | 20        | 0.23%   |
| Toshiba             | 19        | 0.21%   |
| Smart Brazil        | 19        | 0.21%   |
| Qimonda             | 15        | 0.17%   |
| 48spaces            | 13        | 0.15%   |
| Avant               | 12        | 0.14%   |
| PNY                 | 10        | 0.11%   |
| CSX                 | 10        | 0.11%   |
| Timetec             | 8         | 0.09%   |
| Silicon Power       | 8         | 0.09%   |
| SHARETRONIC         | 8         | 0.09%   |
| Multilaser          | 8         | 0.09%   |
| Neo Forza           | 7         | 0.08%   |
| Kingmax             | 7         | 0.08%   |
| Goldkey             | 7         | 0.08%   |
| V-GeN               | 6         | 0.07%   |
| Sesame              | 5         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 163       | 1.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 144       | 1.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 144       | 1.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 139       | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 129       | 1.36%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 129       | 1.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 122       | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 122       | 1.29%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 119       | 1.26%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 109       | 1.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 87        | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 86        | 0.91%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 85        | 0.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 74        | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 67        | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 65        | 0.69%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 65        | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 60        | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 59        | 0.62%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 58        | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 56        | 0.59%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 56        | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 55        | 0.58%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 55        | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 55        | 0.58%   |
| Unknown                                                          | 55        | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 54        | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 51        | 0.54%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 49        | 0.52%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 49        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 48        | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 46        | 0.49%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 44        | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 44        | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 44        | 0.46%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 40        | 0.42%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 39        | 0.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 37        | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 37        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 3742      | 51.14%  |
| DDR4    | 2136      | 29.19%  |
| DDR2    | 664       | 9.07%   |
| LPDDR4  | 261       | 3.57%   |
| SDRAM   | 249       | 3.4%    |
| Unknown | 86        | 1.18%   |
| LPDDR3  | 74        | 1.01%   |
| DRAM    | 30        | 0.41%   |
| DDR5    | 30        | 0.41%   |
| DDR     | 24        | 0.33%   |
| LPDDR5  | 21        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 6842      | 94.35%  |
| Row Of Chips | 324       | 4.47%   |
| DIMM         | 31        | 0.43%   |
| Chip         | 28        | 0.39%   |
| Unknown      | 27        | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 3319      | 40.17%  |
| 8192  | 2263      | 27.39%  |
| 2048  | 1808      | 21.88%  |
| 16384 | 424       | 5.13%   |
| 1024  | 309       | 3.74%   |
| 32768 | 124       | 1.5%    |
| 512   | 15        | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 2398      | 29.44%  |
| 2667    | 1047      | 12.86%  |
| 3200    | 777       | 9.54%   |
| 1334    | 749       | 9.2%    |
| 1333    | 557       | 6.84%   |
| 2400    | 501       | 6.15%   |
| 667     | 357       | 4.38%   |
| 1067    | 245       | 3.01%   |
| 2133    | 227       | 2.79%   |
| Unknown | 204       | 2.5%    |
| 800     | 196       | 2.41%   |
| 4199    | 142       | 1.74%   |
| 3266    | 122       | 1.5%    |
| 2048    | 93        | 1.14%   |
| 975     | 92        | 1.13%   |
| 1066    | 81        | 0.99%   |
| 1867    | 77        | 0.95%   |
| 533     | 57        | 0.7%    |
| 4267    | 50        | 0.61%   |
| 4800    | 30        | 0.37%   |
| 4266    | 28        | 0.34%   |
| 8400    | 18        | 0.22%   |
| 1866    | 18        | 0.22%   |
| 6400    | 17        | 0.21%   |
| 3733    | 14        | 0.17%   |
| 333     | 12        | 0.15%   |
| 1639    | 10        | 0.12%   |
| 2933    | 5         | 0.06%   |
| 3000    | 3         | 0.04%   |
| 400     | 3         | 0.04%   |
| 5500    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 266     | 2         | 0.02%   |
| 7467    | 1         | 0.01%   |
| 5600    | 1         | 0.01%   |
| 1776    | 1         | 0.01%   |
| 1596    | 1         | 0.01%   |
| 1200    | 1         | 0.01%   |
| 933     | 1         | 0.01%   |
| 666     | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 32        | 40%     |
| Canon                 | 18        | 22.5%   |
| Brother Industries    | 11        | 13.75%  |
| Samsung Electronics   | 8         | 10%     |
| Seiko Epson           | 6         | 7.5%    |
| Xerox                 | 2         | 2.5%    |
| Prolific Technology   | 2         | 2.5%    |
| Lexmark International | 1         | 1.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Brother DCP-7055W                       | 4         | 4.94%   |
| Samsung ML-1640 Series Laser Printer    | 3         | 3.7%    |
| HP Deskjet 2050 J510                    | 3         | 3.7%    |
| Prolific PL2305 Parallel Port           | 2         | 2.47%   |
| HP LaserJet 1020                        | 2         | 2.47%   |
| HP ENVY Photo 6200 series               | 2         | 2.47%   |
| HP DeskJet 3630 series                  | 2         | 2.47%   |
| HP DeskJet 2600 series                  | 2         | 2.47%   |
| Canon TR8500 series                     | 2         | 2.47%   |
| Canon PIXMA MG3600 Series               | 2         | 2.47%   |
| Canon PIXMA MG2500 Series               | 2         | 2.47%   |
| Canon LBP2900                           | 2         | 2.47%   |
| Xerox WorkCentre 6025                   | 1         | 1.23%   |
| Xerox Phaser 6000B                      | 1         | 1.23%   |
| Seiko Epson L360 Series                 | 1         | 1.23%   |
| Seiko Epson L355 Series                 | 1         | 1.23%   |
| Seiko Epson L310 Series                 | 1         | 1.23%   |
| Seiko Epson L210 Series                 | 1         | 1.23%   |
| Seiko Epson L120 Series                 | 1         | 1.23%   |
| Seiko Epson ET-2710 Series              | 1         | 1.23%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 1.23%   |
| Samsung SCX-3400 Series                 | 1         | 1.23%   |
| Samsung ML-2010P Mono Laser Printer     | 1         | 1.23%   |
| Samsung M2070 Series                    | 1         | 1.23%   |
| Samsung CLP-325 Color Laser Printer     | 1         | 1.23%   |
| Lexmark International E360d             | 1         | 1.23%   |
| HP PSC 1400                             | 1         | 1.23%   |
| HP OfficeJet Pro 69                     | 1         | 1.23%   |
| HP OfficeJet 6950                       | 1         | 1.23%   |
| HP OfficeJet 4300                       | 1         | 1.23%   |
| HP LaserJet P1102                       | 1         | 1.23%   |
| HP LaserJet M14-M17                     | 1         | 1.23%   |
| HP LaserJet 3055                        | 1         | 1.23%   |
| HP LaserJet 200 colorMFP M275nw         | 1         | 1.23%   |
| HP LaserJet 1018                        | 1         | 1.23%   |
| HP ENVY 6000 series                     | 1         | 1.23%   |
| HP ENVY 4520 series                     | 1         | 1.23%   |
| HP DeskJet Plus 6400 series             | 1         | 1.23%   |
| HP Deskjet F4500 series                 | 1         | 1.23%   |
| HP DeskJet D1360                        | 1         | 1.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Hewlett-Packard | 2         | 22.22%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| HP ScanJet 5590                                          | 2         | 22.22%  |
| Canon CanoScan LiDE 110                                  | 2         | 22.22%  |
| Seiko Epson Scanner                                      | 1         | 11.11%  |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 11.11%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 11.11%  |
| Canon CanoScan LiDE 600F                                 | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1678      | 27.36%  |
| Realtek Semiconductor                  | 526       | 8.58%   |
| IMC Networks                           | 513       | 8.36%   |
| Microdia                               | 493       | 8.04%   |
| Suyin                                  | 389       | 6.34%   |
| Bison Electronics                      | 348       | 5.67%   |
| Sunplus Innovation Technology          | 300       | 4.89%   |
| Quanta                                 | 274       | 4.47%   |
| Cheng Uei Precision Industry (Foxlink) | 248       | 4.04%   |
| Syntek                                 | 204       | 3.33%   |
| Silicon Motion                         | 131       | 2.14%   |
| Acer                                   | 124       | 2.02%   |
| Lite-On Technology                     | 122       | 1.99%   |
| Ricoh                                  | 109       | 1.78%   |
| Alcor Micro                            | 102       | 1.66%   |
| Apple                                  | 101       | 1.65%   |
| Lenovo                                 | 63        | 1.03%   |
| Luxvisions Innotech Limited            | 58        | 0.95%   |
| Importek                               | 51        | 0.83%   |
| ALi                                    | 42        | 0.68%   |
| Primax Electronics                     | 39        | 0.64%   |
| Sonix Technology                       | 22        | 0.36%   |
| Z-Star Microelectronics                | 21        | 0.34%   |
| DigiTech                               | 21        | 0.34%   |
| OmniVision Technologies                | 20        | 0.33%   |
| Logitech                               | 17        | 0.28%   |
| Samsung Electronics                    | 13        | 0.21%   |
| Sunplus Technology                     | 9         | 0.15%   |
| icSpring                               | 8         | 0.13%   |
| Intel                                  | 7         | 0.11%   |
| Genesys Logic                          | 7         | 0.11%   |
| SunplusIT                              | 6         | 0.1%    |
| HRY                                    | 6         | 0.1%    |
| Y Media                                | 5         | 0.08%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.08%   |
| Foxconn / Hon Hai                      | 4         | 0.07%   |
| Cubeternet                             | 4         | 0.07%   |
| Tripath Technology                     | 3         | 0.05%   |
| Nebraska Furniture Mart                | 3         | 0.05%   |
| Microsoft                              | 3         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 226       | 3.68%   |
| Chicony HD WebCam                                       | 150       | 2.44%   |
| Microdia Integrated_Webcam_HD                           | 141       | 2.3%    |
| Realtek Integrated_Webcam_HD                            | 116       | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 109       | 1.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 99        | 1.61%   |
| IMC Networks Integrated Camera                          | 89        | 1.45%   |
| Syntek Integrated Camera                                | 88        | 1.43%   |
| Sunplus Integrated_Webcam_HD                            | 83        | 1.35%   |
| Microdia Integrated Webcam                              | 83        | 1.35%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 74        | 1.21%   |
| Chicony USB 2.0 Camera                                  | 69        | 1.12%   |
| Chicony VGA WebCam                                      | 68        | 1.11%   |
| Realtek USB Camera                                      | 66        | 1.07%   |
| Bison Integrated Camera                                 | 61        | 0.99%   |
| Bison Lenovo EasyCamera                                 | 59        | 0.96%   |
| Sunplus HD WebCam                                       | 58        | 0.94%   |
| Chicony TOSHIBA Web Camera - HD                         | 58        | 0.94%   |
| Chicony Lenovo EasyCamera                               | 57        | 0.93%   |
| Chicony HP Truevision HD                                | 56        | 0.91%   |
| Chicony HP TrueVision HD Camera                         | 55        | 0.9%    |
| Quanta HD User Facing                                   | 52        | 0.85%   |
| Syntek Lenovo EasyCamera                                | 51        | 0.83%   |
| Chicony USB2.0 HD UVC WebCam                            | 51        | 0.83%   |
| Acer Integrated Camera                                  | 49        | 0.8%    |
| Quanta VGA WebCam                                       | 48        | 0.78%   |
| Chicony FJ Camera                                       | 47        | 0.77%   |
| Bison Lenovo Integrated Webcam                          | 47        | 0.77%   |
| Lite-On Integrated Camera                               | 45        | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                           | 45        | 0.73%   |
| Chicony HD User Facing                                  | 44        | 0.72%   |
| Chicony EasyCamera                                      | 44        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 44        | 0.72%   |
| Suyin Integrated_Webcam_HD                              | 41        | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 40        | 0.65%   |
| Apple FaceTime HD Camera                                | 39        | 0.64%   |
| IMC Networks UVC VGA Webcam                             | 38        | 0.62%   |
| Chicony HP Webcam                                       | 38        | 0.62%   |
| Quanta HP Webcam                                        | 37        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 36        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 341       | 39.88%  |
| AuthenTec                          | 134       | 15.67%  |
| Upek                               | 88        | 10.29%  |
| Synaptics                          | 81        | 9.47%   |
| Shenzhen Goodix Technology         | 65        | 7.6%    |
| Elan Microelectronics              | 63        | 7.37%   |
| LighTuning Technology              | 37        | 4.33%   |
| STMicroelectronics                 | 32        | 3.74%   |
| Focal-systems.Corp                 | 8         | 0.94%   |
| Samsung Electronics                | 4         | 0.47%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.12%   |
| HOLTEK                             | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 81        | 9.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 64        | 7.49%   |
| AuthenTec AES2810                                                          | 51        | 5.96%   |
| Shenzhen Goodix  FingerPrint Device                                        | 48        | 5.61%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 46        | 5.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 36        | 4.21%   |
| Elan ELAN:Fingerprint                                                      | 36        | 4.21%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 35        | 4.09%   |
| Validity Sensors VFS491                                                    | 34        | 3.98%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 32        | 3.74%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 3.74%   |
| Elan ELAN:ARM-M4                                                           | 27        | 3.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 25        | 2.92%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.46%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 2.46%   |
| AuthenTec Fingerprint Sensor                                               | 18        | 2.11%   |
| AuthenTec AES1600                                                          | 17        | 1.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 16        | 1.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 1.87%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 1.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 1.52%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 10        | 1.17%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.05%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.94%   |
| LighTuning Fingerprint Reader                                              | 8         | 0.94%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 8         | 0.94%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.82%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 0.82%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.82%   |
| Synaptics  WBDI                                                            | 7         | 0.82%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.82%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 0.58%   |
| Synaptics TouchPad                                                         | 5         | 0.58%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 0.58%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 4         | 0.47%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 256       | 52.35%  |
| Alcor Micro           | 82        | 16.77%  |
| O2 Micro              | 62        | 12.68%  |
| Upek                  | 38        | 7.77%   |
| Lenovo                | 37        | 7.57%   |
| SCM Microsystems      | 3         | 0.61%   |
| Gemalto (was Gemplus) | 3         | 0.61%   |
| Yubico.com            | 2         | 0.41%   |
| Realtek Semiconductor | 1         | 0.2%    |
| OmniKey               | 1         | 0.2%    |
| Microchip Technology  | 1         | 0.2%    |
| Hewlett-Packard       | 1         | 0.2%    |
| Cherry                | 1         | 0.2%    |
| Advanced Card Systems | 1         | 0.2%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 127       | 25.97%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 16.56%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 61        | 12.47%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 60        | 12.27%  |
| Broadcom 5880                                                                | 56        | 11.45%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 38        | 7.77%   |
| Lenovo Integrated Smart Card Reader                                          | 37        | 7.57%   |
| Broadcom 58200                                                               | 12        | 2.45%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.61%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.61%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.41%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.2%    |
| OmniKey CardMan 4321                                                         | 1         | 0.2%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.2%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.2%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.2%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.2%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.2%    |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.2%    |
| Advanced Card Systems ACR122U                                                | 1         | 0.2%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5480      | 74.88%  |
| 1     | 1557      | 21.28%  |
| 2     | 261       | 3.57%   |
| 3     | 19        | 0.26%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 855       | 40.89%  |
| Chipcard                 | 477       | 22.81%  |
| Graphics card            | 318       | 15.21%  |
| Net/wireless             | 119       | 5.69%   |
| Bluetooth                | 93        | 4.45%   |
| Storage                  | 84        | 4.02%   |
| Multimedia controller    | 57        | 2.73%   |
| Camera                   | 42        | 2.01%   |
| Communication controller | 19        | 0.91%   |
| Sound                    | 8         | 0.38%   |
| Flash memory             | 6         | 0.29%   |
| Network                  | 5         | 0.24%   |
| Net/ethernet             | 3         | 0.14%   |
| Card reader              | 3         | 0.14%   |
| Modem                    | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

