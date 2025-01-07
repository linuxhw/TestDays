Linux in Chile - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Chile/Desktop/README.md) and [notebooks](/Location/Chile/Notebook/README.md).

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

Total: 1999

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [7373f056b3](https://linux-hardware.org/?probe=7373f056b3) | Jan 06, 2025 |
| HP            | 2215                        | Desktop     | [d4d1a7ad27](https://linux-hardware.org/?probe=d4d1a7ad27) | Jan 05, 2025 |
| Intel         | X99                         | Desktop     | [0179690cc0](https://linux-hardware.org/?probe=0179690cc0) | Jan 05, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [905b0da038](https://linux-hardware.org/?probe=905b0da038) | Jan 03, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [6781e260b0](https://linux-hardware.org/?probe=6781e260b0) | Jan 03, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [fd2f975353](https://linux-hardware.org/?probe=fd2f975353) | Jan 03, 2025 |
| Acer          | Aspire A114-32              | Notebook    | [3af2175d58](https://linux-hardware.org/?probe=3af2175d58) | Dec 31, 2024 |
| Samsung       | Galaxy Book 12              | Tablet      | [ebd4e47906](https://linux-hardware.org/?probe=ebd4e47906) | Dec 31, 2024 |
| Acer          | Aspire A114-32              | Notebook    | [d4aff4e66c](https://linux-hardware.org/?probe=d4aff4e66c) | Dec 30, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [784d69901d](https://linux-hardware.org/?probe=784d69901d) | Dec 28, 2024 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [0b30ad312b](https://linux-hardware.org/?probe=0b30ad312b) | Dec 25, 2024 |
| ASUSTek       | P8H61-MX                    | Desktop     | [b9f7d12796](https://linux-hardware.org/?probe=b9f7d12796) | Dec 24, 2024 |
| Intel         | X99                         | Desktop     | [d2e526949b](https://linux-hardware.org/?probe=d2e526949b) | Dec 23, 2024 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [6061ff7a43](https://linux-hardware.org/?probe=6061ff7a43) | Dec 21, 2024 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [aab1a2c43e](https://linux-hardware.org/?probe=aab1a2c43e) | Dec 21, 2024 |
| Intel         | X99                         | Desktop     | [380078a8ea](https://linux-hardware.org/?probe=380078a8ea) | Dec 20, 2024 |
| Lenovo        | ThinkPad L430 2466AE4       | Notebook    | [16fb7548fb](https://linux-hardware.org/?probe=16fb7548fb) | Dec 20, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [f28c3f8b25](https://linux-hardware.org/?probe=f28c3f8b25) | Dec 20, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [59d4ff9442](https://linux-hardware.org/?probe=59d4ff9442) | Dec 18, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [119fb952a9](https://linux-hardware.org/?probe=119fb952a9) | Dec 16, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [43c7b5ca99](https://linux-hardware.org/?probe=43c7b5ca99) | Dec 15, 2024 |
| Dell          | Latitude 7440               | Notebook    | [54c2b1737c](https://linux-hardware.org/?probe=54c2b1737c) | Dec 15, 2024 |
| Dell          | Latitude 7440               | Notebook    | [2072f1bec0](https://linux-hardware.org/?probe=2072f1bec0) | Dec 14, 2024 |
| Gigabyte      | X870 GAMING X WIFI7         | Desktop     | [bf3a0594a1](https://linux-hardware.org/?probe=bf3a0594a1) | Dec 14, 2024 |
| Acer          | Aspire VN7-571G             | Notebook    | [244938cec7](https://linux-hardware.org/?probe=244938cec7) | Dec 14, 2024 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [dcf3e70ee3](https://linux-hardware.org/?probe=dcf3e70ee3) | Dec 10, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [045fc5193c](https://linux-hardware.org/?probe=045fc5193c) | Dec 10, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [440089cb3c](https://linux-hardware.org/?probe=440089cb3c) | Dec 09, 2024 |
| HP            | 2820h                       | Desktop     | [b2bef4daf8](https://linux-hardware.org/?probe=b2bef4daf8) | Dec 08, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2646530c8b](https://linux-hardware.org/?probe=2646530c8b) | Dec 07, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1c12d211a2](https://linux-hardware.org/?probe=1c12d211a2) | Dec 07, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [fdfd2985ff](https://linux-hardware.org/?probe=fdfd2985ff) | Dec 07, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [2212d1af6e](https://linux-hardware.org/?probe=2212d1af6e) | Dec 06, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [edc5e493f0](https://linux-hardware.org/?probe=edc5e493f0) | Dec 05, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [c85a51cea1](https://linux-hardware.org/?probe=c85a51cea1) | Dec 05, 2024 |
| ASUSTek       | ROG Strix G512LI            | Notebook    | [2d4be2eb08](https://linux-hardware.org/?probe=2d4be2eb08) | Dec 05, 2024 |
| ASUSTek       | ROG Strix G512LI            | Notebook    | [779e5bad75](https://linux-hardware.org/?probe=779e5bad75) | Dec 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [f48a60ebd3](https://linux-hardware.org/?probe=f48a60ebd3) | Dec 04, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [3485dcd3fa](https://linux-hardware.org/?probe=3485dcd3fa) | Dec 04, 2024 |
| Lenovo        | IdeaPad Slim 5 14IMH9 83... | Notebook    | [07d1866bcc](https://linux-hardware.org/?probe=07d1866bcc) | Dec 02, 2024 |
| HP            | 8054                        | Desktop     | [aff3ac8a75](https://linux-hardware.org/?probe=aff3ac8a75) | Dec 02, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [687f99a0ed](https://linux-hardware.org/?probe=687f99a0ed) | Dec 01, 2024 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [3931bdd4b4](https://linux-hardware.org/?probe=3931bdd4b4) | Nov 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2c25bb8e66](https://linux-hardware.org/?probe=2c25bb8e66) | Nov 23, 2024 |
| Dell          | G5 5590                     | Notebook    | [4725f348b0](https://linux-hardware.org/?probe=4725f348b0) | Nov 22, 2024 |
| Toshiba       | Satellite C45-A             | Notebook    | [72e74a8746](https://linux-hardware.org/?probe=72e74a8746) | Nov 22, 2024 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [67630b5598](https://linux-hardware.org/?probe=67630b5598) | Nov 21, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d3dfd10c89](https://linux-hardware.org/?probe=d3dfd10c89) | Nov 20, 2024 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [2a64956b97](https://linux-hardware.org/?probe=2a64956b97) | Nov 19, 2024 |
| Dell          | Precision 5540              | Notebook    | [a230e980fb](https://linux-hardware.org/?probe=a230e980fb) | Nov 17, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [25cdd42a66](https://linux-hardware.org/?probe=25cdd42a66) | Nov 17, 2024 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [81a38efac3](https://linux-hardware.org/?probe=81a38efac3) | Nov 16, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [ae3c4f6ba3](https://linux-hardware.org/?probe=ae3c4f6ba3) | Nov 16, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [713cf8fabf](https://linux-hardware.org/?probe=713cf8fabf) | Nov 14, 2024 |
| HP            | 14                          | Notebook    | [049df52a18](https://linux-hardware.org/?probe=049df52a18) | Nov 14, 2024 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [168d2c565d](https://linux-hardware.org/?probe=168d2c565d) | Nov 14, 2024 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [58961eb604](https://linux-hardware.org/?probe=58961eb604) | Nov 14, 2024 |
| Dell          | Vostro 14-3468              | Notebook    | [64e1ab6cf2](https://linux-hardware.org/?probe=64e1ab6cf2) | Nov 14, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [73c8e352fe](https://linux-hardware.org/?probe=73c8e352fe) | Nov 12, 2024 |
| HP            | 1998                        | Desktop     | [369ca1dd47](https://linux-hardware.org/?probe=369ca1dd47) | Nov 12, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [33618bc34b](https://linux-hardware.org/?probe=33618bc34b) | Nov 09, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [1e9fb052dd](https://linux-hardware.org/?probe=1e9fb052dd) | Nov 08, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [c4579841cc](https://linux-hardware.org/?probe=c4579841cc) | Nov 06, 2024 |
| HP            | 430                         | Notebook    | [becd0ec6e1](https://linux-hardware.org/?probe=becd0ec6e1) | Nov 06, 2024 |
| HP            | 1998                        | Desktop     | [54437250d0](https://linux-hardware.org/?probe=54437250d0) | Nov 05, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [71caa9ae08](https://linux-hardware.org/?probe=71caa9ae08) | Nov 04, 2024 |
| Samsung       | 940XFG                      | Notebook    | [8d09e8db06](https://linux-hardware.org/?probe=8d09e8db06) | Nov 04, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [8ab293ac66](https://linux-hardware.org/?probe=8ab293ac66) | Nov 04, 2024 |
| HP            | 430                         | Notebook    | [d6af750d57](https://linux-hardware.org/?probe=d6af750d57) | Nov 04, 2024 |
| HP            | 550                         | Notebook    | [70807a2c26](https://linux-hardware.org/?probe=70807a2c26) | Nov 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [8fcf0c4937](https://linux-hardware.org/?probe=8fcf0c4937) | Nov 02, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [7b505da730](https://linux-hardware.org/?probe=7b505da730) | Nov 02, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [51667c2ae8](https://linux-hardware.org/?probe=51667c2ae8) | Oct 31, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [bcb0de8f92](https://linux-hardware.org/?probe=bcb0de8f92) | Oct 31, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ed70122fa1](https://linux-hardware.org/?probe=ed70122fa1) | Oct 31, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [0403c46fc9](https://linux-hardware.org/?probe=0403c46fc9) | Oct 29, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [29941bb47c](https://linux-hardware.org/?probe=29941bb47c) | Oct 29, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c8b803b5be](https://linux-hardware.org/?probe=c8b803b5be) | Oct 29, 2024 |
| Sony          | SVF14213CLB                 | Notebook    | [4f3d4c33ee](https://linux-hardware.org/?probe=4f3d4c33ee) | Oct 28, 2024 |
| Sony          | SVF14213CLB                 | Notebook    | [d896c7e63b](https://linux-hardware.org/?probe=d896c7e63b) | Oct 28, 2024 |
| Sony          | SVF14213CLB                 | Notebook    | [bb16b1fa39](https://linux-hardware.org/?probe=bb16b1fa39) | Oct 28, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [82a2dc3146](https://linux-hardware.org/?probe=82a2dc3146) | Oct 27, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [f3ec231fe2](https://linux-hardware.org/?probe=f3ec231fe2) | Oct 27, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [1a24faada8](https://linux-hardware.org/?probe=1a24faada8) | Oct 27, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [94075bd2fd](https://linux-hardware.org/?probe=94075bd2fd) | Oct 24, 2024 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [909d08958b](https://linux-hardware.org/?probe=909d08958b) | Oct 23, 2024 |
| Lenovo        | ThinkPad T490s 20NYS4200... | Notebook    | [c2b84c3eba](https://linux-hardware.org/?probe=c2b84c3eba) | Oct 21, 2024 |
| Lenovo        | ThinkPad T490s 20NYS4200... | Notebook    | [54dc21124b](https://linux-hardware.org/?probe=54dc21124b) | Oct 21, 2024 |
| MSI           | H81M-E33                    | Desktop     | [aeb4f8c680](https://linux-hardware.org/?probe=aeb4f8c680) | Oct 20, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [a76f83a58a](https://linux-hardware.org/?probe=a76f83a58a) | Oct 20, 2024 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [ba795881fe](https://linux-hardware.org/?probe=ba795881fe) | Oct 19, 2024 |
| HP            | G42                         | Notebook    | [72bf54ec1e](https://linux-hardware.org/?probe=72bf54ec1e) | Oct 18, 2024 |
| Toshiba       | TECRA M11                   | Notebook    | [aee424faeb](https://linux-hardware.org/?probe=aee424faeb) | Oct 18, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [63a9495ac8](https://linux-hardware.org/?probe=63a9495ac8) | Oct 17, 2024 |
| Samsung       | 940XFG                      | Notebook    | [741f7a6544](https://linux-hardware.org/?probe=741f7a6544) | Oct 17, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [6ae8586613](https://linux-hardware.org/?probe=6ae8586613) | Oct 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c30967267a](https://linux-hardware.org/?probe=c30967267a) | Oct 16, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [b83fb99eb1](https://linux-hardware.org/?probe=b83fb99eb1) | Oct 16, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [2131d0a645](https://linux-hardware.org/?probe=2131d0a645) | Oct 13, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8646abd860](https://linux-hardware.org/?probe=8646abd860) | Oct 13, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [4e90d6105f](https://linux-hardware.org/?probe=4e90d6105f) | Oct 11, 2024 |
| Acer          | Aspire A314-23P             | Notebook    | [4517a3a431](https://linux-hardware.org/?probe=4517a3a431) | Oct 10, 2024 |
| Samsung       | 940XFG                      | Notebook    | [a30f0716a0](https://linux-hardware.org/?probe=a30f0716a0) | Oct 08, 2024 |
| MSI           | H61M-P21                    | Desktop     | [1dbbce13c7](https://linux-hardware.org/?probe=1dbbce13c7) | Oct 08, 2024 |
| Lenovo        | ThinkPad T460s 20FAA0GUC... | Notebook    | [0c478e7ee9](https://linux-hardware.org/?probe=0c478e7ee9) | Oct 05, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [6a37860d48](https://linux-hardware.org/?probe=6a37860d48) | Oct 04, 2024 |
| Dell          | 0JWGHC A02                  | All in one  | [24f4fe0749](https://linux-hardware.org/?probe=24f4fe0749) | Oct 03, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [395b3fa9c6](https://linux-hardware.org/?probe=395b3fa9c6) | Oct 03, 2024 |
| HP            | G60                         | Notebook    | [b2cbfa9c26](https://linux-hardware.org/?probe=b2cbfa9c26) | Oct 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b501b5c003](https://linux-hardware.org/?probe=b501b5c003) | Oct 01, 2024 |
| Samsung       | 750XED                      | Notebook    | [4678fb79d7](https://linux-hardware.org/?probe=4678fb79d7) | Sep 30, 2024 |
| Toshiba       | Satellite L745              | Notebook    | [089e824e9e](https://linux-hardware.org/?probe=089e824e9e) | Sep 30, 2024 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [43f4d4163d](https://linux-hardware.org/?probe=43f4d4163d) | Sep 29, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [b06ebcfa91](https://linux-hardware.org/?probe=b06ebcfa91) | Sep 27, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [7e49febc40](https://linux-hardware.org/?probe=7e49febc40) | Sep 27, 2024 |
| Packard Be... | DOT SE                      | Notebook    | [838057e7da](https://linux-hardware.org/?probe=838057e7da) | Sep 26, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [86ed130e09](https://linux-hardware.org/?probe=86ed130e09) | Sep 23, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [76f114be0f](https://linux-hardware.org/?probe=76f114be0f) | Sep 23, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6db3471f5e](https://linux-hardware.org/?probe=6db3471f5e) | Sep 23, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [0a02c29530](https://linux-hardware.org/?probe=0a02c29530) | Sep 22, 2024 |
| MSI           | H81M-E33                    | Desktop     | [161e77e63f](https://linux-hardware.org/?probe=161e77e63f) | Sep 21, 2024 |
| VIT           | M2420                       | Notebook    | [0ab836dd8d](https://linux-hardware.org/?probe=0ab836dd8d) | Sep 19, 2024 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [3e8533679f](https://linux-hardware.org/?probe=3e8533679f) | Sep 18, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [a2f78f9d5a](https://linux-hardware.org/?probe=a2f78f9d5a) | Sep 17, 2024 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [6fdb9480fd](https://linux-hardware.org/?probe=6fdb9480fd) | Sep 16, 2024 |
| ASUSTek       | X556URK                     | Notebook    | [4b8f57e0d1](https://linux-hardware.org/?probe=4b8f57e0d1) | Sep 16, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [be1922c0f5](https://linux-hardware.org/?probe=be1922c0f5) | Sep 15, 2024 |
| MSI           | H81M-E33                    | Desktop     | [c34d12468d](https://linux-hardware.org/?probe=c34d12468d) | Sep 14, 2024 |
| Dell          | Latitude 5285               | Tablet      | [c39de3b4a0](https://linux-hardware.org/?probe=c39de3b4a0) | Sep 13, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [4c82b54925](https://linux-hardware.org/?probe=4c82b54925) | Sep 12, 2024 |
| HP            | G42                         | Notebook    | [ba7eaabeb2](https://linux-hardware.org/?probe=ba7eaabeb2) | Sep 12, 2024 |
| Dell          | 0JYH5J A00                  | All in one  | [b1a24dcb7c](https://linux-hardware.org/?probe=b1a24dcb7c) | Sep 11, 2024 |
| Lenovo        | 36E0 SDK0J40688 WIN 3424... | All in one  | [5a2693a415](https://linux-hardware.org/?probe=5a2693a415) | Sep 10, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [496a31fec4](https://linux-hardware.org/?probe=496a31fec4) | Sep 09, 2024 |
| Samsung       | 940XFG                      | Notebook    | [4afba7e537](https://linux-hardware.org/?probe=4afba7e537) | Sep 09, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [277183655d](https://linux-hardware.org/?probe=277183655d) | Sep 07, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [229145b0e7](https://linux-hardware.org/?probe=229145b0e7) | Sep 03, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c137c49524](https://linux-hardware.org/?probe=c137c49524) | Sep 02, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [a3720d80f0](https://linux-hardware.org/?probe=a3720d80f0) | Sep 01, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [2000ed4989](https://linux-hardware.org/?probe=2000ed4989) | Sep 01, 2024 |
| ASUSTek       | ProArt P16 H7606WI_H7606... | Notebook    | [f1c3ce98a5](https://linux-hardware.org/?probe=f1c3ce98a5) | Sep 01, 2024 |
| Unknown       | X79                         | Desktop     | [fb92bb7ecc](https://linux-hardware.org/?probe=fb92bb7ecc) | Aug 31, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [bfaf5d315d](https://linux-hardware.org/?probe=bfaf5d315d) | Aug 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ecb8c40d28](https://linux-hardware.org/?probe=ecb8c40d28) | Aug 30, 2024 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [52fb0884a3](https://linux-hardware.org/?probe=52fb0884a3) | Aug 28, 2024 |
| Acer          | Aspire ES1-431              | Notebook    | [7aa368e7d6](https://linux-hardware.org/?probe=7aa368e7d6) | Aug 27, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [bfdddf9760](https://linux-hardware.org/?probe=bfdddf9760) | Aug 26, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [a4ad90766e](https://linux-hardware.org/?probe=a4ad90766e) | Aug 26, 2024 |
| Sony          | VAIO                        | All in one  | [2ebadea317](https://linux-hardware.org/?probe=2ebadea317) | Aug 25, 2024 |
| Toshiba       | Satellite C845              | Notebook    | [e043e1d64a](https://linux-hardware.org/?probe=e043e1d64a) | Aug 25, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [712ad66747](https://linux-hardware.org/?probe=712ad66747) | Aug 25, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [26d502b9bc](https://linux-hardware.org/?probe=26d502b9bc) | Aug 24, 2024 |
| Olidata       | ALICON AI2S-A21 0.41        | Desktop     | [df62aa88dc](https://linux-hardware.org/?probe=df62aa88dc) | Aug 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a2229f95b](https://linux-hardware.org/?probe=2a2229f95b) | Aug 23, 2024 |
| Olidata       | ALICON AI2S-A21 0.41        | Desktop     | [07fa7b2207](https://linux-hardware.org/?probe=07fa7b2207) | Aug 23, 2024 |
| Acer          | Aspire A315-42              | Notebook    | [30b8ffa31d](https://linux-hardware.org/?probe=30b8ffa31d) | Aug 19, 2024 |
| Acer          | Aspire A315-42              | Notebook    | [7cd2e9d2f3](https://linux-hardware.org/?probe=7cd2e9d2f3) | Aug 19, 2024 |
| MSI           | H81M-E33                    | Desktop     | [fdf3a4566b](https://linux-hardware.org/?probe=fdf3a4566b) | Aug 19, 2024 |
| Apple         | MacBookPro15,1              | Notebook    | [e688cf6bf0](https://linux-hardware.org/?probe=e688cf6bf0) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X532... | Notebook    | [0c816ddf94](https://linux-hardware.org/?probe=0c816ddf94) | Aug 18, 2024 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [5191de9d88](https://linux-hardware.org/?probe=5191de9d88) | Aug 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [27a29cca1a](https://linux-hardware.org/?probe=27a29cca1a) | Aug 18, 2024 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [5ad0b4dc50](https://linux-hardware.org/?probe=5ad0b4dc50) | Aug 18, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [0544e9bb70](https://linux-hardware.org/?probe=0544e9bb70) | Aug 17, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [e5f8732d9e](https://linux-hardware.org/?probe=e5f8732d9e) | Aug 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [f255c7443d](https://linux-hardware.org/?probe=f255c7443d) | Aug 17, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [9fe31d4092](https://linux-hardware.org/?probe=9fe31d4092) | Aug 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [c2c96a7641](https://linux-hardware.org/?probe=c2c96a7641) | Aug 16, 2024 |
| Valve         | Jupiter                     | Notebook    | [10ab7a64bc](https://linux-hardware.org/?probe=10ab7a64bc) | Aug 14, 2024 |
| ASUSTek       | N53SM                       | Notebook    | [65111d0e17](https://linux-hardware.org/?probe=65111d0e17) | Aug 14, 2024 |
| Lenovo        | IdeaPad 1 14IJL7 82LV       | Notebook    | [50fc9f779b](https://linux-hardware.org/?probe=50fc9f779b) | Aug 14, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f9ac4e3525](https://linux-hardware.org/?probe=f9ac4e3525) | Aug 13, 2024 |
| Lenovo        | ThinkPad P53 20QQS1PT00     | Notebook    | [4dd35339c8](https://linux-hardware.org/?probe=4dd35339c8) | Aug 13, 2024 |
| Dell          | Latitude 7490               | Notebook    | [c46710a743](https://linux-hardware.org/?probe=c46710a743) | Aug 07, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [4b7aeff864](https://linux-hardware.org/?probe=4b7aeff864) | Aug 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [0c3a85253b](https://linux-hardware.org/?probe=0c3a85253b) | Aug 05, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5fa9b544f6](https://linux-hardware.org/?probe=5fa9b544f6) | Aug 04, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [0cf0f0de3f](https://linux-hardware.org/?probe=0cf0f0de3f) | Aug 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [0c5fababe4](https://linux-hardware.org/?probe=0c5fababe4) | Aug 04, 2024 |
| Samsung       | 960XFG                      | Notebook    | [611bdbdf95](https://linux-hardware.org/?probe=611bdbdf95) | Aug 02, 2024 |
| HP            | 425                         | Notebook    | [aa91584619](https://linux-hardware.org/?probe=aa91584619) | Aug 02, 2024 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [84799775ff](https://linux-hardware.org/?probe=84799775ff) | Aug 02, 2024 |
| Sony          | VPCF120FL                   | Notebook    | [ed9b23fa9d](https://linux-hardware.org/?probe=ed9b23fa9d) | Aug 01, 2024 |
| ECS           | H61H2-MV                    | Desktop     | [4158e740d0](https://linux-hardware.org/?probe=4158e740d0) | Aug 01, 2024 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [711db524cd](https://linux-hardware.org/?probe=711db524cd) | Aug 01, 2024 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [e364531174](https://linux-hardware.org/?probe=e364531174) | Jul 31, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [8abdd19040](https://linux-hardware.org/?probe=8abdd19040) | Jul 31, 2024 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [e9f6ba19fc](https://linux-hardware.org/?probe=e9f6ba19fc) | Jul 29, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1205e31e83](https://linux-hardware.org/?probe=1205e31e83) | Jul 28, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [30b8f841a4](https://linux-hardware.org/?probe=30b8f841a4) | Jul 28, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8333b31ce7](https://linux-hardware.org/?probe=8333b31ce7) | Jul 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [0ee0fc3367](https://linux-hardware.org/?probe=0ee0fc3367) | Jul 25, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [89ebbbea48](https://linux-hardware.org/?probe=89ebbbea48) | Jul 25, 2024 |
| AZW           | MINI S                      | Desktop     | [d8754c0201](https://linux-hardware.org/?probe=d8754c0201) | Jul 25, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [05c607b799](https://linux-hardware.org/?probe=05c607b799) | Jul 24, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [7217eafd23](https://linux-hardware.org/?probe=7217eafd23) | Jul 24, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d3dc54280d](https://linux-hardware.org/?probe=d3dc54280d) | Jul 22, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [23031969c6](https://linux-hardware.org/?probe=23031969c6) | Jul 22, 2024 |
| Acer          | Nitro AN515-45              | Notebook    | [19cb8f5e37](https://linux-hardware.org/?probe=19cb8f5e37) | Jul 21, 2024 |
| HP            | Pavilion dv6                | Notebook    | [dd341c91f8](https://linux-hardware.org/?probe=dd341c91f8) | Jul 21, 2024 |
| ASUSTek       | N53SM                       | Notebook    | [60ad818fc8](https://linux-hardware.org/?probe=60ad818fc8) | Jul 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [044a4fdad6](https://linux-hardware.org/?probe=044a4fdad6) | Jul 17, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [58de6beaf1](https://linux-hardware.org/?probe=58de6beaf1) | Jul 17, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [d20875079c](https://linux-hardware.org/?probe=d20875079c) | Jul 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [d40f3907f4](https://linux-hardware.org/?probe=d40f3907f4) | Jul 16, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [e73cf52cd5](https://linux-hardware.org/?probe=e73cf52cd5) | Jul 15, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [88aa7d03b9](https://linux-hardware.org/?probe=88aa7d03b9) | Jul 14, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [5ca6a9bef8](https://linux-hardware.org/?probe=5ca6a9bef8) | Jul 13, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [dabdfaf7bd](https://linux-hardware.org/?probe=dabdfaf7bd) | Jul 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4C... | Notebook    | [05c6d9255b](https://linux-hardware.org/?probe=05c6d9255b) | Jul 11, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [f07dd5ac4f](https://linux-hardware.org/?probe=f07dd5ac4f) | Jul 11, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [006338ddbc](https://linux-hardware.org/?probe=006338ddbc) | Jul 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [720f017e8c](https://linux-hardware.org/?probe=720f017e8c) | Jul 11, 2024 |
| Toshiba       | Satellite C45-A             | Notebook    | [c09c8ef326](https://linux-hardware.org/?probe=c09c8ef326) | Jul 11, 2024 |
| Pegatron      | 2A99                        | Desktop     | [6479f475f5](https://linux-hardware.org/?probe=6479f475f5) | Jul 10, 2024 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [3fd2ebf150](https://linux-hardware.org/?probe=3fd2ebf150) | Jul 10, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [003311a98c](https://linux-hardware.org/?probe=003311a98c) | Jul 10, 2024 |
| HP            | ENVY 15                     | Notebook    | [109ffad315](https://linux-hardware.org/?probe=109ffad315) | Jul 10, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [290973ae43](https://linux-hardware.org/?probe=290973ae43) | Jul 10, 2024 |
| Dell          | Latitude 5420               | Notebook    | [17b4168e8a](https://linux-hardware.org/?probe=17b4168e8a) | Jul 07, 2024 |
| Dell          | Latitude 5420               | Notebook    | [1242a62f30](https://linux-hardware.org/?probe=1242a62f30) | Jul 07, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [3ed2f04a8a](https://linux-hardware.org/?probe=3ed2f04a8a) | Jul 07, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [ae38969368](https://linux-hardware.org/?probe=ae38969368) | Jul 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [eb90d739f5](https://linux-hardware.org/?probe=eb90d739f5) | Jul 05, 2024 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [40aa0ad6dd](https://linux-hardware.org/?probe=40aa0ad6dd) | Jul 04, 2024 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [588a326e55](https://linux-hardware.org/?probe=588a326e55) | Jul 04, 2024 |
| Lenovo        | ThinkPad T495 20NJ0004US    | Notebook    | [1b75f0acb9](https://linux-hardware.org/?probe=1b75f0acb9) | Jul 04, 2024 |
| Gigabyte      | H610M H                     | Desktop     | [3f30142163](https://linux-hardware.org/?probe=3f30142163) | Jul 02, 2024 |
| HP            | 420                         | Notebook    | [6ada30790a](https://linux-hardware.org/?probe=6ada30790a) | Jul 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d028dd2318](https://linux-hardware.org/?probe=d028dd2318) | Jul 02, 2024 |
| HP            | 14                          | Notebook    | [f28a807a2e](https://linux-hardware.org/?probe=f28a807a2e) | Jul 01, 2024 |
| Unknown       | Unknown                     | Notebook    | [fddd3e9b10](https://linux-hardware.org/?probe=fddd3e9b10) | Jul 01, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [27e651550b](https://linux-hardware.org/?probe=27e651550b) | Jun 30, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [79478e2007](https://linux-hardware.org/?probe=79478e2007) | Jun 29, 2024 |
| HP            | Pavilion dv6                | Notebook    | [25259c90d4](https://linux-hardware.org/?probe=25259c90d4) | Jun 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [22240b5af3](https://linux-hardware.org/?probe=22240b5af3) | Jun 26, 2024 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [e7383572c6](https://linux-hardware.org/?probe=e7383572c6) | Jun 26, 2024 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [2022a910b7](https://linux-hardware.org/?probe=2022a910b7) | Jun 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [4bb1502dc7](https://linux-hardware.org/?probe=4bb1502dc7) | Jun 24, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7cbb22297f](https://linux-hardware.org/?probe=7cbb22297f) | Jun 24, 2024 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [fa847c686c](https://linux-hardware.org/?probe=fa847c686c) | Jun 23, 2024 |
| MSI           | B550-A PRO[CEC]             | Desktop     | [fc933dc2df](https://linux-hardware.org/?probe=fc933dc2df) | Jun 23, 2024 |
| Sony          | SVE14125CLB                 | Notebook    | [1d128bfde4](https://linux-hardware.org/?probe=1d128bfde4) | Jun 22, 2024 |
| Sony          | SVE14125CLB                 | Notebook    | [9ca981de07](https://linux-hardware.org/?probe=9ca981de07) | Jun 22, 2024 |
| VIT           | M2420                       | Notebook    | [9a65dd5dd1](https://linux-hardware.org/?probe=9a65dd5dd1) | Jun 21, 2024 |
| VIT           | M2420                       | Notebook    | [68fe58bac5](https://linux-hardware.org/?probe=68fe58bac5) | Jun 21, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ae60c915ff](https://linux-hardware.org/?probe=ae60c915ff) | Jun 20, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c141bd23d2](https://linux-hardware.org/?probe=c141bd23d2) | Jun 20, 2024 |
| HP            | 1998                        | Desktop     | [cccee42308](https://linux-hardware.org/?probe=cccee42308) | Jun 19, 2024 |
| HP            | 1998                        | Desktop     | [ee549aa7c5](https://linux-hardware.org/?probe=ee549aa7c5) | Jun 19, 2024 |
| Unknown       | Apple MacBook Air (M1, 2... | Notebook    | [0972bec8ac](https://linux-hardware.org/?probe=0972bec8ac) | Jun 18, 2024 |
| Toshiba       | Satellite L45-B             | Notebook    | [e54c28b406](https://linux-hardware.org/?probe=e54c28b406) | Jun 17, 2024 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [fade2029a5](https://linux-hardware.org/?probe=fade2029a5) | Jun 16, 2024 |
| Dell          | Latitude 7400               | Notebook    | [870e9ad53e](https://linux-hardware.org/?probe=870e9ad53e) | Jun 16, 2024 |
| HUAWEI        | BOHBZ-WAX9                  | Notebook    | [c8d74a04a0](https://linux-hardware.org/?probe=c8d74a04a0) | Jun 15, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [0b8e0d4884](https://linux-hardware.org/?probe=0b8e0d4884) | Jun 14, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [8d460943ce](https://linux-hardware.org/?probe=8d460943ce) | Jun 14, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [df9d105b1b](https://linux-hardware.org/?probe=df9d105b1b) | Jun 14, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [2fb9cc0441](https://linux-hardware.org/?probe=2fb9cc0441) | Jun 13, 2024 |
| Intel         | X99H                        | Desktop     | [bf88c6e5c7](https://linux-hardware.org/?probe=bf88c6e5c7) | Jun 13, 2024 |
| Packard Be... | EasyNote ENTE69SK           | Notebook    | [e3351f5a9c](https://linux-hardware.org/?probe=e3351f5a9c) | Jun 13, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [02fdcfb0f4](https://linux-hardware.org/?probe=02fdcfb0f4) | Jun 11, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [5281642282](https://linux-hardware.org/?probe=5281642282) | Jun 11, 2024 |
| Toshiba       | QOSMIO F755                 | Notebook    | [e2270849e9](https://linux-hardware.org/?probe=e2270849e9) | Jun 10, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc4d989cf2](https://linux-hardware.org/?probe=cc4d989cf2) | Jun 10, 2024 |
| Dell          | Inspiron 5548               | Notebook    | [25a63b5bbc](https://linux-hardware.org/?probe=25a63b5bbc) | Jun 09, 2024 |
| ASUSTek       | GL503VD                     | Notebook    | [2674cfcd2f](https://linux-hardware.org/?probe=2674cfcd2f) | Jun 09, 2024 |
| ASUSTek       | GL503VD                     | Notebook    | [2bd8f671fa](https://linux-hardware.org/?probe=2bd8f671fa) | Jun 09, 2024 |
| Lenovo        | ThinkPad T480 20L5S1QV00    | Notebook    | [fa6c6f9726](https://linux-hardware.org/?probe=fa6c6f9726) | Jun 09, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [a9b147099e](https://linux-hardware.org/?probe=a9b147099e) | Jun 07, 2024 |
| Toshiba       | Satellite L515              | Notebook    | [9586fde367](https://linux-hardware.org/?probe=9586fde367) | Jun 06, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [0fadeec498](https://linux-hardware.org/?probe=0fadeec498) | Jun 06, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [b91f3ef3c5](https://linux-hardware.org/?probe=b91f3ef3c5) | Jun 05, 2024 |
| Samsung       | 960XFG                      | Notebook    | [f4a1e3bf2c](https://linux-hardware.org/?probe=f4a1e3bf2c) | Jun 05, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d4dcdab86b](https://linux-hardware.org/?probe=d4dcdab86b) | Jun 03, 2024 |
| ASUSTek       | K501UW                      | Notebook    | [c39feab6fe](https://linux-hardware.org/?probe=c39feab6fe) | Jun 03, 2024 |
| Packard Be... | EasyNote ENTE69SK           | Notebook    | [bfe5481262](https://linux-hardware.org/?probe=bfe5481262) | Jun 02, 2024 |
| Sony          | VAIO                        | All in one  | [87ffe6492b](https://linux-hardware.org/?probe=87ffe6492b) | Jun 02, 2024 |
| Lenovo        | ThinkPad P16 Gen 2 21FBC... | Notebook    | [1e83665f05](https://linux-hardware.org/?probe=1e83665f05) | Jun 02, 2024 |
| Acer          | Aspire A315-42              | Notebook    | [21403456bf](https://linux-hardware.org/?probe=21403456bf) | Jun 01, 2024 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [990022b7bf](https://linux-hardware.org/?probe=990022b7bf) | Jun 01, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [df8e59b402](https://linux-hardware.org/?probe=df8e59b402) | May 30, 2024 |
| Sony          | VGN-CR260FE                 | Notebook    | [0265a64f9c](https://linux-hardware.org/?probe=0265a64f9c) | May 30, 2024 |
| Lenovo        | ThinkPad T480 20L6A0LHCL    | Notebook    | [3fdf6daa9a](https://linux-hardware.org/?probe=3fdf6daa9a) | May 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [409f8fc16d](https://linux-hardware.org/?probe=409f8fc16d) | May 28, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [ff69f93bc2](https://linux-hardware.org/?probe=ff69f93bc2) | May 27, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [fbfb9ee390](https://linux-hardware.org/?probe=fbfb9ee390) | May 24, 2024 |
| ASUSTek       | N53SV                       | Notebook    | [89435bcd50](https://linux-hardware.org/?probe=89435bcd50) | May 24, 2024 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [b3a468a604](https://linux-hardware.org/?probe=b3a468a604) | May 24, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [14170049ba](https://linux-hardware.org/?probe=14170049ba) | May 22, 2024 |
| Samsung       | 940XFG                      | Notebook    | [6fc322b7b3](https://linux-hardware.org/?probe=6fc322b7b3) | May 22, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f831dbd6f0](https://linux-hardware.org/?probe=f831dbd6f0) | May 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fcfb875664](https://linux-hardware.org/?probe=fcfb875664) | May 21, 2024 |
| Unknown       | Unknown                     | Notebook    | [5b2ca64802](https://linux-hardware.org/?probe=5b2ca64802) | May 20, 2024 |
| HP            | Presario CQ43               | Notebook    | [39b9f0db33](https://linux-hardware.org/?probe=39b9f0db33) | May 19, 2024 |
| HP            | Presario CQ43               | Notebook    | [58d4a04fb1](https://linux-hardware.org/?probe=58d4a04fb1) | May 19, 2024 |
| ANGXUN        | X79 (INTEL Xeon E5/Corei... | Desktop     | [3cb1b2bfec](https://linux-hardware.org/?probe=3cb1b2bfec) | May 19, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ff2e3c37b3](https://linux-hardware.org/?probe=ff2e3c37b3) | May 19, 2024 |
| HP            | x2 210 G2                   | Tablet      | [b406c5892e](https://linux-hardware.org/?probe=b406c5892e) | May 19, 2024 |
| ANGXUN        | X79 (INTEL Xeon E5/Corei... | Desktop     | [742d962e1c](https://linux-hardware.org/?probe=742d962e1c) | May 18, 2024 |
| Acer          | Nitro AN515-57              | Notebook    | [beb44a426c](https://linux-hardware.org/?probe=beb44a426c) | May 18, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [54908e5376](https://linux-hardware.org/?probe=54908e5376) | May 17, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [e37cfd54a0](https://linux-hardware.org/?probe=e37cfd54a0) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [b853bbc409](https://linux-hardware.org/?probe=b853bbc409) | May 16, 2024 |
| HP            | Notebook                    | Notebook    | [b99c732078](https://linux-hardware.org/?probe=b99c732078) | May 16, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [88e8009735](https://linux-hardware.org/?probe=88e8009735) | May 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [6e282ab8d7](https://linux-hardware.org/?probe=6e282ab8d7) | May 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [a49c5f8025](https://linux-hardware.org/?probe=a49c5f8025) | May 12, 2024 |
| Acer          | One S1003                   | Tablet      | [4b36e20081](https://linux-hardware.org/?probe=4b36e20081) | May 09, 2024 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [e49b5301ae](https://linux-hardware.org/?probe=e49b5301ae) | May 08, 2024 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [8acc6c69a3](https://linux-hardware.org/?probe=8acc6c69a3) | May 08, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [76e6f087bb](https://linux-hardware.org/?probe=76e6f087bb) | May 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3292b37df6](https://linux-hardware.org/?probe=3292b37df6) | May 08, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [f154c6f22e](https://linux-hardware.org/?probe=f154c6f22e) | May 07, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [9e6a5eb0e2](https://linux-hardware.org/?probe=9e6a5eb0e2) | May 07, 2024 |
| Dell          | Latitude 7480               | Notebook    | [124ec816c7](https://linux-hardware.org/?probe=124ec816c7) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [53c592f858](https://linux-hardware.org/?probe=53c592f858) | May 04, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [31db777b68](https://linux-hardware.org/?probe=31db777b68) | May 04, 2024 |
| Unknown       | Unknown                     | Notebook    | [3f7e899e58](https://linux-hardware.org/?probe=3f7e899e58) | May 04, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b76f2f11bd](https://linux-hardware.org/?probe=b76f2f11bd) | May 04, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [22cf049537](https://linux-hardware.org/?probe=22cf049537) | May 04, 2024 |
| HP            | 1000                        | Notebook    | [5cbdf4ea65](https://linux-hardware.org/?probe=5cbdf4ea65) | May 03, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [b3f2c851de](https://linux-hardware.org/?probe=b3f2c851de) | May 02, 2024 |
| Dell          | System XPS L502X            | Notebook    | [ba86210a01](https://linux-hardware.org/?probe=ba86210a01) | May 02, 2024 |
| HP            | 1000                        | Notebook    | [57f342d3ff](https://linux-hardware.org/?probe=57f342d3ff) | May 02, 2024 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ff4a31241b](https://linux-hardware.org/?probe=ff4a31241b) | May 02, 2024 |
| Intel         | NUC13SBBi5 M89887-303       | Mini pc     | [9ef1488e0b](https://linux-hardware.org/?probe=9ef1488e0b) | May 01, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8739bc2d60](https://linux-hardware.org/?probe=8739bc2d60) | May 01, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [67a23e48b6](https://linux-hardware.org/?probe=67a23e48b6) | May 01, 2024 |
| Pegatron      | 2A99                        | Desktop     | [fcd74433b3](https://linux-hardware.org/?probe=fcd74433b3) | Apr 30, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [060878050f](https://linux-hardware.org/?probe=060878050f) | Apr 30, 2024 |
| Samsung       | 750XED                      | Notebook    | [d4c8fa3bde](https://linux-hardware.org/?probe=d4c8fa3bde) | Apr 29, 2024 |
| EVGA          | NF66 2                      | Desktop     | [ef1a49773b](https://linux-hardware.org/?probe=ef1a49773b) | Apr 29, 2024 |
| Samsung       | 750XED                      | Notebook    | [37fcaff384](https://linux-hardware.org/?probe=37fcaff384) | Apr 29, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [b63833a7b2](https://linux-hardware.org/?probe=b63833a7b2) | Apr 28, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [814f4429a4](https://linux-hardware.org/?probe=814f4429a4) | Apr 27, 2024 |
| Dell          | Latitude 3420               | Notebook    | [c0bc583333](https://linux-hardware.org/?probe=c0bc583333) | Apr 26, 2024 |
| Dell          | Latitude 3420               | Notebook    | [522bdc6fd0](https://linux-hardware.org/?probe=522bdc6fd0) | Apr 26, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [537da6819a](https://linux-hardware.org/?probe=537da6819a) | Apr 25, 2024 |
| HP            | ENVY 15                     | Notebook    | [20cb7a828b](https://linux-hardware.org/?probe=20cb7a828b) | Apr 24, 2024 |
| Dell          | System XPS L502X            | Notebook    | [1546699c7b](https://linux-hardware.org/?probe=1546699c7b) | Apr 24, 2024 |
| Unknown       | Unknown                     | Notebook    | [def20611a4](https://linux-hardware.org/?probe=def20611a4) | Apr 23, 2024 |
| Acer          | Aspire A515-52G             | Notebook    | [9ee2e8d42a](https://linux-hardware.org/?probe=9ee2e8d42a) | Apr 23, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [cfba8255a3](https://linux-hardware.org/?probe=cfba8255a3) | Apr 22, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [d89b09df70](https://linux-hardware.org/?probe=d89b09df70) | Apr 19, 2024 |
| HP            | 2B02                        | Desktop     | [5272c37a4c](https://linux-hardware.org/?probe=5272c37a4c) | Apr 18, 2024 |
| Acer          | V5-131                      | Notebook    | [5ca622b910](https://linux-hardware.org/?probe=5ca622b910) | Apr 18, 2024 |
| Acer          | V5-131                      | Notebook    | [984da3beb5](https://linux-hardware.org/?probe=984da3beb5) | Apr 18, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [d7cf8c586e](https://linux-hardware.org/?probe=d7cf8c586e) | Apr 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [bcaf7cac1a](https://linux-hardware.org/?probe=bcaf7cac1a) | Apr 15, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [8ef5274513](https://linux-hardware.org/?probe=8ef5274513) | Apr 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [25a93e1b63](https://linux-hardware.org/?probe=25a93e1b63) | Apr 14, 2024 |
| HP            | Pavilion dv6000 (GM695LA... | Notebook    | [21796df3a5](https://linux-hardware.org/?probe=21796df3a5) | Apr 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [f6d12e0e88](https://linux-hardware.org/?probe=f6d12e0e88) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [31b430e45e](https://linux-hardware.org/?probe=31b430e45e) | Apr 13, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [550b5dcdc0](https://linux-hardware.org/?probe=550b5dcdc0) | Apr 12, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [d263334708](https://linux-hardware.org/?probe=d263334708) | Apr 12, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [65d523fbeb](https://linux-hardware.org/?probe=65d523fbeb) | Apr 10, 2024 |
| Dell          | Latitude 7290               | Notebook    | [b23f2a505a](https://linux-hardware.org/?probe=b23f2a505a) | Apr 10, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [5b676c4d65](https://linux-hardware.org/?probe=5b676c4d65) | Apr 09, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [00731ce19b](https://linux-hardware.org/?probe=00731ce19b) | Apr 07, 2024 |
| Dell          | Latitude 7480               | Notebook    | [60c813fedb](https://linux-hardware.org/?probe=60c813fedb) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [4e25522fd7](https://linux-hardware.org/?probe=4e25522fd7) | Apr 06, 2024 |
| HP            | 2ABA A01                    | Desktop     | [308a7c307f](https://linux-hardware.org/?probe=308a7c307f) | Apr 05, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [fb9702f65e](https://linux-hardware.org/?probe=fb9702f65e) | Apr 05, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [c29b99633c](https://linux-hardware.org/?probe=c29b99633c) | Apr 03, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [99296143a7](https://linux-hardware.org/?probe=99296143a7) | Apr 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [2bb5c3d295](https://linux-hardware.org/?probe=2bb5c3d295) | Apr 03, 2024 |
| Wings Mobi... | Wings Book 1                | Notebook    | [532ae4633c](https://linux-hardware.org/?probe=532ae4633c) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7f542aae1b](https://linux-hardware.org/?probe=7f542aae1b) | Apr 02, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0474c0e2a0](https://linux-hardware.org/?probe=0474c0e2a0) | Apr 02, 2024 |
| Dell          | System XPS L502X            | Notebook    | [e176a846de](https://linux-hardware.org/?probe=e176a846de) | Apr 01, 2024 |
| Dell          | System XPS L502X            | Notebook    | [ca3fdd569e](https://linux-hardware.org/?probe=ca3fdd569e) | Mar 31, 2024 |
| Sony          | SVF14221CLW                 | Notebook    | [a6a658aa9b](https://linux-hardware.org/?probe=a6a658aa9b) | Mar 30, 2024 |
| Sony          | SVF14221CLW                 | Notebook    | [1530abd2d4](https://linux-hardware.org/?probe=1530abd2d4) | Mar 30, 2024 |
| Dell          | 03KWTV A02                  | Desktop     | [f97822b63a](https://linux-hardware.org/?probe=f97822b63a) | Mar 29, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [b90fd9c218](https://linux-hardware.org/?probe=b90fd9c218) | Mar 28, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [17ddcfee74](https://linux-hardware.org/?probe=17ddcfee74) | Mar 27, 2024 |
| HP            | ENVY 15                     | Notebook    | [11821b80b7](https://linux-hardware.org/?probe=11821b80b7) | Mar 26, 2024 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [44cf5392ad](https://linux-hardware.org/?probe=44cf5392ad) | Mar 23, 2024 |
| HP            | 212B                        | Desktop     | [5ad874f74e](https://linux-hardware.org/?probe=5ad874f74e) | Mar 22, 2024 |
| HP            | 212B                        | Desktop     | [c82c46c22c](https://linux-hardware.org/?probe=c82c46c22c) | Mar 22, 2024 |
| Samsung       | N100                        | Notebook    | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Alienware     | 17 R2                       | Notebook    | [eb210f842b](https://linux-hardware.org/?probe=eb210f842b) | Mar 21, 2024 |
| Dell          | Latitude 7290               | Notebook    | [060d4f8054](https://linux-hardware.org/?probe=060d4f8054) | Mar 20, 2024 |
| Lenovo        | 0x36C4 SDK0J40679 WIN 32... | All in one  | [044c3275da](https://linux-hardware.org/?probe=044c3275da) | Mar 19, 2024 |
| ANGXUN        | X79 (INTEL Xeon E5/Corei... | Desktop     | [3ec8fc69b2](https://linux-hardware.org/?probe=3ec8fc69b2) | Mar 17, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | Notebook    | [304f0db93a](https://linux-hardware.org/?probe=304f0db93a) | Mar 16, 2024 |
| HP            | Pavilion g4                 | Notebook    | [f36a2c4d30](https://linux-hardware.org/?probe=f36a2c4d30) | Mar 15, 2024 |
| HP            | 805D                        | Desktop     | [7878b71cab](https://linux-hardware.org/?probe=7878b71cab) | Mar 15, 2024 |
| ASUSTek       | X580VD                      | Notebook    | [f33436ccfe](https://linux-hardware.org/?probe=f33436ccfe) | Mar 13, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [b3176660a1](https://linux-hardware.org/?probe=b3176660a1) | Mar 12, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [25e788b418](https://linux-hardware.org/?probe=25e788b418) | Mar 12, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [dc5ea071de](https://linux-hardware.org/?probe=dc5ea071de) | Mar 12, 2024 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [74f33723a8](https://linux-hardware.org/?probe=74f33723a8) | Mar 11, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [bf63e4ac63](https://linux-hardware.org/?probe=bf63e4ac63) | Mar 10, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [f3fc324ad6](https://linux-hardware.org/?probe=f3fc324ad6) | Mar 10, 2024 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [4b181b04ee](https://linux-hardware.org/?probe=4b181b04ee) | Mar 09, 2024 |
| HP            | Compaq 8510p                | Notebook    | [9a70629877](https://linux-hardware.org/?probe=9a70629877) | Mar 09, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [c7b2c1d469](https://linux-hardware.org/?probe=c7b2c1d469) | Mar 08, 2024 |
| Acer          | Aspire A114-33              | Notebook    | [5201890093](https://linux-hardware.org/?probe=5201890093) | Mar 07, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [d4f875966c](https://linux-hardware.org/?probe=d4f875966c) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| HP            | ENVY 15                     | Notebook    | [6f74377b0a](https://linux-hardware.org/?probe=6f74377b0a) | Mar 05, 2024 |
| HP            | ENVY 15                     | Notebook    | [86b5b9b7d7](https://linux-hardware.org/?probe=86b5b9b7d7) | Mar 04, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [ff01bc4e69](https://linux-hardware.org/?probe=ff01bc4e69) | Mar 03, 2024 |
| HP            | ENVY 15                     | Notebook    | [f8fc004a9c](https://linux-hardware.org/?probe=f8fc004a9c) | Mar 03, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [a33280c60d](https://linux-hardware.org/?probe=a33280c60d) | Feb 28, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [a358f29362](https://linux-hardware.org/?probe=a358f29362) | Feb 28, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c7441889f1](https://linux-hardware.org/?probe=c7441889f1) | Feb 26, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | Notebook    | [039aae7236](https://linux-hardware.org/?probe=039aae7236) | Feb 24, 2024 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | Notebook    | [474d7d9a50](https://linux-hardware.org/?probe=474d7d9a50) | Feb 24, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8fe4f0e76d](https://linux-hardware.org/?probe=8fe4f0e76d) | Feb 22, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [7a847ee2ac](https://linux-hardware.org/?probe=7a847ee2ac) | Feb 21, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [9dae96099a](https://linux-hardware.org/?probe=9dae96099a) | Feb 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [cdcf85f04c](https://linux-hardware.org/?probe=cdcf85f04c) | Feb 21, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [e843792ce5](https://linux-hardware.org/?probe=e843792ce5) | Feb 18, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [63eec59f69](https://linux-hardware.org/?probe=63eec59f69) | Feb 18, 2024 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [ced438a574](https://linux-hardware.org/?probe=ced438a574) | Feb 17, 2024 |
| Sony          | VPCEE37FL                   | Notebook    | [611371a88b](https://linux-hardware.org/?probe=611371a88b) | Feb 16, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [f8d949c6e1](https://linux-hardware.org/?probe=f8d949c6e1) | Feb 16, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [dcd36d6705](https://linux-hardware.org/?probe=dcd36d6705) | Feb 16, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [44eb92e9e8](https://linux-hardware.org/?probe=44eb92e9e8) | Feb 11, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27231005d1](https://linux-hardware.org/?probe=27231005d1) | Feb 11, 2024 |
| Dell          | Inspiron 5459               | Notebook    | [d40f482a25](https://linux-hardware.org/?probe=d40f482a25) | Feb 10, 2024 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | Notebook    | [17e2d4fc72](https://linux-hardware.org/?probe=17e2d4fc72) | Feb 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [2490245b2a](https://linux-hardware.org/?probe=2490245b2a) | Feb 10, 2024 |
| HP            | Pavilion g4                 | Notebook    | [ab845ec197](https://linux-hardware.org/?probe=ab845ec197) | Feb 06, 2024 |
| HP            | Pavilion m6                 | Notebook    | [f12679a936](https://linux-hardware.org/?probe=f12679a936) | Feb 03, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [d4c61a6527](https://linux-hardware.org/?probe=d4c61a6527) | Feb 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d743247f69](https://linux-hardware.org/?probe=d743247f69) | Jan 31, 2024 |
| ASUSTek       | X556UQK                     | Notebook    | [970dc5b87d](https://linux-hardware.org/?probe=970dc5b87d) | Jan 31, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [02a1844f63](https://linux-hardware.org/?probe=02a1844f63) | Jan 31, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [202a9720c4](https://linux-hardware.org/?probe=202a9720c4) | Jan 30, 2024 |
| Lenovo        | ThinkPad T495 20NKS1EP00    | Notebook    | [addeb3711c](https://linux-hardware.org/?probe=addeb3711c) | Jan 30, 2024 |
| Lenovo        | ThinkPad T490 20N3S8DK00    | Notebook    | [4e9cad214e](https://linux-hardware.org/?probe=4e9cad214e) | Jan 28, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [68364930e7](https://linux-hardware.org/?probe=68364930e7) | Jan 27, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [1d4943457c](https://linux-hardware.org/?probe=1d4943457c) | Jan 26, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [75379edae7](https://linux-hardware.org/?probe=75379edae7) | Jan 26, 2024 |
| HP            | 304Ah                       | Desktop     | [5e40a8acee](https://linux-hardware.org/?probe=5e40a8acee) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3bc0546f62](https://linux-hardware.org/?probe=3bc0546f62) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [95692e9f04](https://linux-hardware.org/?probe=95692e9f04) | Jan 23, 2024 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [efa155f365](https://linux-hardware.org/?probe=efa155f365) | Jan 22, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [2c5947d48c](https://linux-hardware.org/?probe=2c5947d48c) | Jan 22, 2024 |
| HP            | Pavilion g4                 | Notebook    | [ecddd3e100](https://linux-hardware.org/?probe=ecddd3e100) | Jan 21, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [de30e068d6](https://linux-hardware.org/?probe=de30e068d6) | Jan 21, 2024 |
| Lenovo        | ThinkPad X280 20KEA03YCL    | Notebook    | [6d4961e126](https://linux-hardware.org/?probe=6d4961e126) | Jan 21, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [1ad08b8198](https://linux-hardware.org/?probe=1ad08b8198) | Jan 21, 2024 |
| Acer          | Nitro AN517-54              | Notebook    | [e736d57544](https://linux-hardware.org/?probe=e736d57544) | Jan 18, 2024 |
| Sony          | VPCF120FL                   | Notebook    | [6ada0707e6](https://linux-hardware.org/?probe=6ada0707e6) | Jan 18, 2024 |
| Valve         | Jupiter                     | Notebook    | [5a872c599e](https://linux-hardware.org/?probe=5a872c599e) | Jan 15, 2024 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [2d802ba751](https://linux-hardware.org/?probe=2d802ba751) | Jan 13, 2024 |
| ECS           | G31T-M7                     | Desktop     | [254ece65d1](https://linux-hardware.org/?probe=254ece65d1) | Jan 12, 2024 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [13fd289ac7](https://linux-hardware.org/?probe=13fd289ac7) | Jan 11, 2024 |
| ASUSTek       | X542UQ                      | Notebook    | [80e9791b86](https://linux-hardware.org/?probe=80e9791b86) | Jan 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [68a601314f](https://linux-hardware.org/?probe=68a601314f) | Jan 10, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [d7c1f42897](https://linux-hardware.org/?probe=d7c1f42897) | Jan 10, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [80d405caee](https://linux-hardware.org/?probe=80d405caee) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | Notebook    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| ASUSTek       | X542UA                      | Notebook    | [028b7c4d83](https://linux-hardware.org/?probe=028b7c4d83) | Jan 08, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4285b072d7](https://linux-hardware.org/?probe=4285b072d7) | Jan 05, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [868c32afaa](https://linux-hardware.org/?probe=868c32afaa) | Jan 05, 2024 |
| ASUSTek       | X542UA                      | Notebook    | [5d7b076a1c](https://linux-hardware.org/?probe=5d7b076a1c) | Jan 05, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [65ef79e8a1](https://linux-hardware.org/?probe=65ef79e8a1) | Jan 04, 2024 |
| HP            | Notebook                    | Notebook    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [04753e77e0](https://linux-hardware.org/?probe=04753e77e0) | Jan 02, 2024 |
| ASUSTek       | PN53-G                      | Mini pc     | [63fd2a4477](https://linux-hardware.org/?probe=63fd2a4477) | Dec 31, 2023 |
| ANGXUN        | X79 (INTEL Xeon E5/Corei... | Desktop     | [92d3ce2ee5](https://linux-hardware.org/?probe=92d3ce2ee5) | Dec 30, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [12339778af](https://linux-hardware.org/?probe=12339778af) | Dec 30, 2023 |
| Dell          | Latitude 7390               | Notebook    | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [da4285cce4](https://linux-hardware.org/?probe=da4285cce4) | Dec 26, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [029b043cec](https://linux-hardware.org/?probe=029b043cec) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | Desktop     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [5397e7633e](https://linux-hardware.org/?probe=5397e7633e) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [ae01ab2ebe](https://linux-hardware.org/?probe=ae01ab2ebe) | Dec 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dbbab5f96b](https://linux-hardware.org/?probe=dbbab5f96b) | Dec 19, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [f6f623f0d8](https://linux-hardware.org/?probe=f6f623f0d8) | Dec 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [e8847d53ec](https://linux-hardware.org/?probe=e8847d53ec) | Dec 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5223e586fd](https://linux-hardware.org/?probe=5223e586fd) | Dec 15, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [165e16505d](https://linux-hardware.org/?probe=165e16505d) | Dec 14, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1d510c91de](https://linux-hardware.org/?probe=1d510c91de) | Dec 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2eeac061b2](https://linux-hardware.org/?probe=2eeac061b2) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [53ee047174](https://linux-hardware.org/?probe=53ee047174) | Dec 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [af38b45c59](https://linux-hardware.org/?probe=af38b45c59) | Dec 12, 2023 |
| Acer          | V5-171                      | Notebook    | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| SK hynix      | HyBook                      | Notebook    | [cf29911599](https://linux-hardware.org/?probe=cf29911599) | Dec 11, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [5121b6a20c](https://linux-hardware.org/?probe=5121b6a20c) | Dec 09, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [f6ed574e0d](https://linux-hardware.org/?probe=f6ed574e0d) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [8198e47786](https://linux-hardware.org/?probe=8198e47786) | Dec 08, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2a593d9294](https://linux-hardware.org/?probe=2a593d9294) | Dec 06, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [9b6c1bfbf2](https://linux-hardware.org/?probe=9b6c1bfbf2) | Dec 06, 2023 |
| HP            | 245 G5 Notebook PC          | Notebook    | [f3abc9d11d](https://linux-hardware.org/?probe=f3abc9d11d) | Dec 05, 2023 |
| HP            | Notebook                    | Notebook    | [8d58f80f77](https://linux-hardware.org/?probe=8d58f80f77) | Dec 03, 2023 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [707fd0c687](https://linux-hardware.org/?probe=707fd0c687) | Dec 02, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [80be39f0d4](https://linux-hardware.org/?probe=80be39f0d4) | Dec 01, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [bb2313602b](https://linux-hardware.org/?probe=bb2313602b) | Nov 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [933ce1aa7d](https://linux-hardware.org/?probe=933ce1aa7d) | Nov 27, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6005ac3fdd](https://linux-hardware.org/?probe=6005ac3fdd) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [5b41f73363](https://linux-hardware.org/?probe=5b41f73363) | Nov 25, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [4f1442fcc4](https://linux-hardware.org/?probe=4f1442fcc4) | Nov 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f17333cca3](https://linux-hardware.org/?probe=f17333cca3) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f3956e461c](https://linux-hardware.org/?probe=f3956e461c) | Nov 23, 2023 |
| ASUSTek       | X456UV                      | Notebook    | [f38105228e](https://linux-hardware.org/?probe=f38105228e) | Nov 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f8778aa9e9](https://linux-hardware.org/?probe=f8778aa9e9) | Nov 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [94962a7ceb](https://linux-hardware.org/?probe=94962a7ceb) | Nov 19, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [b05c08e4ab](https://linux-hardware.org/?probe=b05c08e4ab) | Nov 17, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5077cde917](https://linux-hardware.org/?probe=5077cde917) | Nov 16, 2023 |
| ECS           | H77H2-EM                    | Desktop     | [20c68c0667](https://linux-hardware.org/?probe=20c68c0667) | Nov 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4c653190f6](https://linux-hardware.org/?probe=4c653190f6) | Nov 14, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [707f319e17](https://linux-hardware.org/?probe=707f319e17) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X8... | Notebook    | [4bf49cfb42](https://linux-hardware.org/?probe=4bf49cfb42) | Nov 11, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [3f794fd46d](https://linux-hardware.org/?probe=3f794fd46d) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c921ede59](https://linux-hardware.org/?probe=2c921ede59) | Nov 08, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [54d6d39995](https://linux-hardware.org/?probe=54d6d39995) | Nov 07, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [7971055e99](https://linux-hardware.org/?probe=7971055e99) | Nov 06, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [fc242f51bf](https://linux-hardware.org/?probe=fc242f51bf) | Nov 05, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [70a66852db](https://linux-hardware.org/?probe=70a66852db) | Nov 05, 2023 |
| HP            | ENVY 15                     | Notebook    | [74dae44745](https://linux-hardware.org/?probe=74dae44745) | Nov 01, 2023 |
| Dell          | Latitude 7290               | Notebook    | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [98c2ece6fd](https://linux-hardware.org/?probe=98c2ece6fd) | Oct 28, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [8c6cbf3608](https://linux-hardware.org/?probe=8c6cbf3608) | Oct 27, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [354a804750](https://linux-hardware.org/?probe=354a804750) | Oct 27, 2023 |
| Foxconn       | P35A01                      | Desktop     | [e63e8acdaa](https://linux-hardware.org/?probe=e63e8acdaa) | Oct 27, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [e0534a1c2a](https://linux-hardware.org/?probe=e0534a1c2a) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c4b4502472](https://linux-hardware.org/?probe=c4b4502472) | Oct 20, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [464e218144](https://linux-hardware.org/?probe=464e218144) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [19d60d452f](https://linux-hardware.org/?probe=19d60d452f) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | Notebook    | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [1014c56a70](https://linux-hardware.org/?probe=1014c56a70) | Oct 10, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| MSI           | MS-7392                     | Desktop     | [5107ce50a1](https://linux-hardware.org/?probe=5107ce50a1) | Oct 09, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [8c4bcd5155](https://linux-hardware.org/?probe=8c4bcd5155) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [26247d8807](https://linux-hardware.org/?probe=26247d8807) | Oct 05, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [965f7580d3](https://linux-hardware.org/?probe=965f7580d3) | Oct 05, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [06c1e095a7](https://linux-hardware.org/?probe=06c1e095a7) | Oct 03, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [0babc8185b](https://linux-hardware.org/?probe=0babc8185b) | Oct 03, 2023 |
| Toshiba       | Satellite C845D             | Notebook    | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| HP            | 2ADE                        | Desktop     | [b701a5c589](https://linux-hardware.org/?probe=b701a5c589) | Sep 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [91e89424ef](https://linux-hardware.org/?probe=91e89424ef) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| Lenovo        | ThinkPad Edge E431 62778... | Notebook    | [31b0e8e9ce](https://linux-hardware.org/?probe=31b0e8e9ce) | Sep 24, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f4a96c9156](https://linux-hardware.org/?probe=f4a96c9156) | Sep 24, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b61b5cb7e3](https://linux-hardware.org/?probe=b61b5cb7e3) | Sep 23, 2023 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [05ef373ef0](https://linux-hardware.org/?probe=05ef373ef0) | Sep 23, 2023 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [a57b236842](https://linux-hardware.org/?probe=a57b236842) | Sep 23, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [50023a1d3a](https://linux-hardware.org/?probe=50023a1d3a) | Sep 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [68c0d7834d](https://linux-hardware.org/?probe=68c0d7834d) | Sep 18, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [a44de9f197](https://linux-hardware.org/?probe=a44de9f197) | Sep 15, 2023 |
| HP            | 0A60h                       | Desktop     | [107f849e6b](https://linux-hardware.org/?probe=107f849e6b) | Sep 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [62375851b3](https://linux-hardware.org/?probe=62375851b3) | Sep 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [c87b0b463c](https://linux-hardware.org/?probe=c87b0b463c) | Sep 13, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [f1cff1b2ac](https://linux-hardware.org/?probe=f1cff1b2ac) | Sep 11, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [f7eae2e7c4](https://linux-hardware.org/?probe=f7eae2e7c4) | Sep 09, 2023 |
| Dell          | 04Y8V0 A02                  | Desktop     | [aa2d2a4c29](https://linux-hardware.org/?probe=aa2d2a4c29) | Sep 08, 2023 |
| HP            | 2ADE                        | Desktop     | [f7b01f93c4](https://linux-hardware.org/?probe=f7b01f93c4) | Sep 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d075cbe2e0](https://linux-hardware.org/?probe=d075cbe2e0) | Sep 04, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c0af84c629](https://linux-hardware.org/?probe=c0af84c629) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ab39767c20](https://linux-hardware.org/?probe=ab39767c20) | Sep 02, 2023 |
| Lenovo        | ThinkPad X201 3680KS9       | Notebook    | [561d8c3891](https://linux-hardware.org/?probe=561d8c3891) | Sep 02, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [52e8a720ba](https://linux-hardware.org/?probe=52e8a720ba) | Sep 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [3e3433226b](https://linux-hardware.org/?probe=3e3433226b) | Sep 01, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [d354a59a67](https://linux-hardware.org/?probe=d354a59a67) | Aug 29, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [6554eecc36](https://linux-hardware.org/?probe=6554eecc36) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [0b3afd5dce](https://linux-hardware.org/?probe=0b3afd5dce) | Aug 24, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [4d1d53f6d8](https://linux-hardware.org/?probe=4d1d53f6d8) | Aug 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| ASUSTek       | ROG Strix G531GU_G531GU     | Notebook    | [627606b933](https://linux-hardware.org/?probe=627606b933) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1b985f59a1](https://linux-hardware.org/?probe=1b985f59a1) | Aug 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [272e3307fe](https://linux-hardware.org/?probe=272e3307fe) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [6f1a280aa5](https://linux-hardware.org/?probe=6f1a280aa5) | Aug 21, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [e84eba7c7d](https://linux-hardware.org/?probe=e84eba7c7d) | Aug 20, 2023 |
| Acer          | TravelMate P645-S           | Notebook    | [658d88e2a5](https://linux-hardware.org/?probe=658d88e2a5) | Aug 20, 2023 |
| HP            | Pavilion dv4                | Notebook    | [5f1e0c4484](https://linux-hardware.org/?probe=5f1e0c4484) | Aug 19, 2023 |
| HP            | 435                         | Notebook    | [cb02103775](https://linux-hardware.org/?probe=cb02103775) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [dbdb6ca163](https://linux-hardware.org/?probe=dbdb6ca163) | Aug 17, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [3151636f73](https://linux-hardware.org/?probe=3151636f73) | Aug 16, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [c27b841a97](https://linux-hardware.org/?probe=c27b841a97) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [5c55416a18](https://linux-hardware.org/?probe=5c55416a18) | Aug 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4404dc3287](https://linux-hardware.org/?probe=4404dc3287) | Aug 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [79889c3f89](https://linux-hardware.org/?probe=79889c3f89) | Aug 11, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b691f28c43](https://linux-hardware.org/?probe=b691f28c43) | Aug 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [84d6b99d2c](https://linux-hardware.org/?probe=84d6b99d2c) | Aug 10, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [26e60daa62](https://linux-hardware.org/?probe=26e60daa62) | Aug 10, 2023 |
| Lenovo        | G460 20041                  | Notebook    | [709445c691](https://linux-hardware.org/?probe=709445c691) | Aug 09, 2023 |
| HP            | Compaq 15                   | Notebook    | [387a3b8af2](https://linux-hardware.org/?probe=387a3b8af2) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ac7079fac9](https://linux-hardware.org/?probe=ac7079fac9) | Aug 05, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f8f4442b09](https://linux-hardware.org/?probe=f8f4442b09) | Aug 05, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [b8f1735d23](https://linux-hardware.org/?probe=b8f1735d23) | Aug 04, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6a6f453881](https://linux-hardware.org/?probe=6a6f453881) | Aug 02, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [fda8d0a543](https://linux-hardware.org/?probe=fda8d0a543) | Aug 02, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| Lenovo        | ThinkPad Edge E430 32543... | Notebook    | [b30651e46f](https://linux-hardware.org/?probe=b30651e46f) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680KS9       | Notebook    | [968bd5d46b](https://linux-hardware.org/?probe=968bd5d46b) | Jul 30, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [d9c029afa4](https://linux-hardware.org/?probe=d9c029afa4) | Jul 28, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [ba47e8e20f](https://linux-hardware.org/?probe=ba47e8e20f) | Jul 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2ca3c71f4a](https://linux-hardware.org/?probe=2ca3c71f4a) | Jul 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [19aa0d748d](https://linux-hardware.org/?probe=19aa0d748d) | Jul 24, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [5300c80b7e](https://linux-hardware.org/?probe=5300c80b7e) | Jul 24, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3d8ec4447b](https://linux-hardware.org/?probe=3d8ec4447b) | Jul 24, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [b754fb3410](https://linux-hardware.org/?probe=b754fb3410) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [35d1400354](https://linux-hardware.org/?probe=35d1400354) | Jul 20, 2023 |
| Dell          | Latitude E6410              | Notebook    | [2a09336b72](https://linux-hardware.org/?probe=2a09336b72) | Jul 20, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [64b51936ea](https://linux-hardware.org/?probe=64b51936ea) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [ab65cec6fe](https://linux-hardware.org/?probe=ab65cec6fe) | Jul 19, 2023 |
| Lenovo        | M490s 20215                 | Notebook    | [d029f6cf0b](https://linux-hardware.org/?probe=d029f6cf0b) | Jul 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e056c22283](https://linux-hardware.org/?probe=e056c22283) | Jul 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [48b3d62237](https://linux-hardware.org/?probe=48b3d62237) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3820e840f0](https://linux-hardware.org/?probe=3820e840f0) | Jul 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [5cfb9d33bd](https://linux-hardware.org/?probe=5cfb9d33bd) | Jul 14, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [d477369e7e](https://linux-hardware.org/?probe=d477369e7e) | Jul 14, 2023 |
| HP            | 83EB                        | All in one  | [9a1012bd0d](https://linux-hardware.org/?probe=9a1012bd0d) | Jul 14, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6c541c67b9](https://linux-hardware.org/?probe=6c541c67b9) | Jul 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [110622383d](https://linux-hardware.org/?probe=110622383d) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [eb024b5188](https://linux-hardware.org/?probe=eb024b5188) | Jul 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [52fafabf05](https://linux-hardware.org/?probe=52fafabf05) | Jul 10, 2023 |
| MSI           | H81M-E33                    | Desktop     | [804d078deb](https://linux-hardware.org/?probe=804d078deb) | Jul 10, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [275acaaa00](https://linux-hardware.org/?probe=275acaaa00) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 23254W5       | Notebook    | [5842896b76](https://linux-hardware.org/?probe=5842896b76) | Jul 03, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [48195d85f8](https://linux-hardware.org/?probe=48195d85f8) | Jul 02, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [189320a2cf](https://linux-hardware.org/?probe=189320a2cf) | Jul 01, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8a0d6c1825](https://linux-hardware.org/?probe=8a0d6c1825) | Jun 29, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f72fe64697](https://linux-hardware.org/?probe=f72fe64697) | Jun 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d2a1351f86](https://linux-hardware.org/?probe=d2a1351f86) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [7487f61ff1](https://linux-hardware.org/?probe=7487f61ff1) | Jun 26, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [dfeaf221e6](https://linux-hardware.org/?probe=dfeaf221e6) | Jun 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [172c84a53d](https://linux-hardware.org/?probe=172c84a53d) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS02V0... | Notebook    | [bed60c3010](https://linux-hardware.org/?probe=bed60c3010) | Jun 21, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [b3ce37b2cb](https://linux-hardware.org/?probe=b3ce37b2cb) | Jun 21, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| HP            | Compaq 15                   | Notebook    | [d89a75cb42](https://linux-hardware.org/?probe=d89a75cb42) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [34610e62fe](https://linux-hardware.org/?probe=34610e62fe) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [bd4abe1a68](https://linux-hardware.org/?probe=bd4abe1a68) | Jun 18, 2023 |
| HP            | Compaq 15                   | Notebook    | [a60f50ade5](https://linux-hardware.org/?probe=a60f50ade5) | Jun 18, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [6294c25695](https://linux-hardware.org/?probe=6294c25695) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [7e8ae5cb7a](https://linux-hardware.org/?probe=7e8ae5cb7a) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [176973d157](https://linux-hardware.org/?probe=176973d157) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [63ded73edb](https://linux-hardware.org/?probe=63ded73edb) | Jun 14, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [fb57cc3ed4](https://linux-hardware.org/?probe=fb57cc3ed4) | Jun 13, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [b00b3b8570](https://linux-hardware.org/?probe=b00b3b8570) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eb6dc5143e](https://linux-hardware.org/?probe=eb6dc5143e) | Jun 12, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [90bcfaba60](https://linux-hardware.org/?probe=90bcfaba60) | Jun 12, 2023 |
| Unknown       | Unknown                     | Tablet      | [f9d086b77c](https://linux-hardware.org/?probe=f9d086b77c) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [eda13b898c](https://linux-hardware.org/?probe=eda13b898c) | Jun 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [3776ac93b3](https://linux-hardware.org/?probe=3776ac93b3) | Jun 08, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9c9fb1b1a6](https://linux-hardware.org/?probe=9c9fb1b1a6) | Jun 08, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [92645b42ac](https://linux-hardware.org/?probe=92645b42ac) | Jun 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [829839a3b3](https://linux-hardware.org/?probe=829839a3b3) | Jun 07, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [beb59fa1d1](https://linux-hardware.org/?probe=beb59fa1d1) | Jun 07, 2023 |
| ASRock        | Z590 Phantom Gaming 4       | Desktop     | [1e9eef0102](https://linux-hardware.org/?probe=1e9eef0102) | Jun 03, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| SK hynix      | HyBook                      | Notebook    | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [259865e80e](https://linux-hardware.org/?probe=259865e80e) | Jun 01, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [f1e9073b3d](https://linux-hardware.org/?probe=f1e9073b3d) | May 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [2f61fcf47d](https://linux-hardware.org/?probe=2f61fcf47d) | May 31, 2023 |
| HP            | 2B07                        | All in one  | [19be50fbca](https://linux-hardware.org/?probe=19be50fbca) | May 30, 2023 |
| HP            | 2B07                        | All in one  | [a9392cd6cf](https://linux-hardware.org/?probe=a9392cd6cf) | May 30, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [882f43330b](https://linux-hardware.org/?probe=882f43330b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [5ee0afea25](https://linux-hardware.org/?probe=5ee0afea25) | May 25, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [3cb0dd251d](https://linux-hardware.org/?probe=3cb0dd251d) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f69b95b887](https://linux-hardware.org/?probe=f69b95b887) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [8aaec63d14](https://linux-hardware.org/?probe=8aaec63d14) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | Notebook    | [f3724cb7da](https://linux-hardware.org/?probe=f3724cb7da) | May 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ffa28e78e](https://linux-hardware.org/?probe=8ffa28e78e) | May 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33a9b42068](https://linux-hardware.org/?probe=33a9b42068) | May 15, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Intel         | H61                         | Desktop     | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | Desktop     | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Latitude 5480               | Notebook    | [eb671ee7d2](https://linux-hardware.org/?probe=eb671ee7d2) | May 11, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [76f23f434d](https://linux-hardware.org/?probe=76f23f434d) | May 10, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [ce0391bdee](https://linux-hardware.org/?probe=ce0391bdee) | May 09, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [ce04ace3b3](https://linux-hardware.org/?probe=ce04ace3b3) | May 09, 2023 |
| SK hynix      | HyBook Plus                 | Notebook    | [817a46f154](https://linux-hardware.org/?probe=817a46f154) | May 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [d0eb83c0af](https://linux-hardware.org/?probe=d0eb83c0af) | May 07, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0BB0... | Notebook    | [881068ac47](https://linux-hardware.org/?probe=881068ac47) | May 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e3dd9f70f6](https://linux-hardware.org/?probe=e3dd9f70f6) | May 04, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [29f68ce8d7](https://linux-hardware.org/?probe=29f68ce8d7) | May 03, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [c8b7ffa6dc](https://linux-hardware.org/?probe=c8b7ffa6dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8fea3db366](https://linux-hardware.org/?probe=8fea3db366) | May 02, 2023 |
| Toshiba       | Satellite L45               | Notebook    | [044db31897](https://linux-hardware.org/?probe=044db31897) | May 02, 2023 |
| Acer          | Aspire V5-471P              | Notebook    | [d44b4f12a5](https://linux-hardware.org/?probe=d44b4f12a5) | May 01, 2023 |
| Lenovo        | B490 20205                  | Notebook    | [c786307607](https://linux-hardware.org/?probe=c786307607) | May 01, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [611ed4a200](https://linux-hardware.org/?probe=611ed4a200) | May 01, 2023 |
| HP            | Compaq 15                   | Notebook    | [0c65bb3d3c](https://linux-hardware.org/?probe=0c65bb3d3c) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6A0LJCL    | Notebook    | [f67154866c](https://linux-hardware.org/?probe=f67154866c) | May 01, 2023 |
| Lenovo        | B490 20205                  | Notebook    | [bc1fdb2575](https://linux-hardware.org/?probe=bc1fdb2575) | May 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [bba2f8d1ad](https://linux-hardware.org/?probe=bba2f8d1ad) | Apr 30, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ed7c1abb38](https://linux-hardware.org/?probe=ed7c1abb38) | Apr 28, 2023 |
| HP            | ENVY 15                     | Notebook    | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [014215365a](https://linux-hardware.org/?probe=014215365a) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1287b17594](https://linux-hardware.org/?probe=1287b17594) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [37f98c9450](https://linux-hardware.org/?probe=37f98c9450) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [ebe7f36c99](https://linux-hardware.org/?probe=ebe7f36c99) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | Notebook    | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e72f221b5b](https://linux-hardware.org/?probe=e72f221b5b) | Apr 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1950979b24](https://linux-hardware.org/?probe=1950979b24) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| HP            | Notebook                    | Notebook    | [31d24dfe38](https://linux-hardware.org/?probe=31d24dfe38) | Apr 21, 2023 |
| Dell          | G15 5510                    | Notebook    | [43d4ce3c37](https://linux-hardware.org/?probe=43d4ce3c37) | Apr 21, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [a7b05c2528](https://linux-hardware.org/?probe=a7b05c2528) | Apr 20, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [5262a186b5](https://linux-hardware.org/?probe=5262a186b5) | Apr 20, 2023 |
| WZA300S2R1... | SA300-D4                    | Desktop     | [e2a6ae91b9](https://linux-hardware.org/?probe=e2a6ae91b9) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [5e67931961](https://linux-hardware.org/?probe=5e67931961) | Apr 17, 2023 |
| Gear          | Geranium                    | Notebook    | [fe70506e6c](https://linux-hardware.org/?probe=fe70506e6c) | Apr 17, 2023 |
| Lenovo        | G405 20239                  | Notebook    | [e79c183bde](https://linux-hardware.org/?probe=e79c183bde) | Apr 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [19b858e5f8](https://linux-hardware.org/?probe=19b858e5f8) | Apr 16, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [eb800f7d1b](https://linux-hardware.org/?probe=eb800f7d1b) | Apr 14, 2023 |
| HP            | 8433 11                     | Desktop     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MS-7360                     | Desktop     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [22da370a63](https://linux-hardware.org/?probe=22da370a63) | Apr 08, 2023 |
| ASRock        | B360M/OEM                   | Desktop     | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff65115a04](https://linux-hardware.org/?probe=ff65115a04) | Apr 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [771f3d8665](https://linux-hardware.org/?probe=771f3d8665) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [712e78de35](https://linux-hardware.org/?probe=712e78de35) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [a7cb3cf668](https://linux-hardware.org/?probe=a7cb3cf668) | Apr 05, 2023 |
| Unknown       | X99-GT                      | Desktop     | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [16f81f8254](https://linux-hardware.org/?probe=16f81f8254) | Apr 05, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [ad6e45cead](https://linux-hardware.org/?probe=ad6e45cead) | Apr 05, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [4710939159](https://linux-hardware.org/?probe=4710939159) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [4191279e7e](https://linux-hardware.org/?probe=4191279e7e) | Apr 01, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [27fbf62ba0](https://linux-hardware.org/?probe=27fbf62ba0) | Apr 01, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [5b087b11f5](https://linux-hardware.org/?probe=5b087b11f5) | Mar 30, 2023 |
| HP            | 8433 11                     | Desktop     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e9600e8bfe](https://linux-hardware.org/?probe=e9600e8bfe) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f7222bf293](https://linux-hardware.org/?probe=f7222bf293) | Mar 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [698b73783e](https://linux-hardware.org/?probe=698b73783e) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | Notebook    | [036c2c771c](https://linux-hardware.org/?probe=036c2c771c) | Mar 23, 2023 |
| MSI           | Z270 GAMING M3              | Desktop     | [2c25601c7c](https://linux-hardware.org/?probe=2c25601c7c) | Mar 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4cbcbc3025](https://linux-hardware.org/?probe=4cbcbc3025) | Mar 22, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| Dell          | G3 3590                     | Notebook    | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| HP            | 18E7                        | Desktop     | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [23c1be0005](https://linux-hardware.org/?probe=23c1be0005) | Mar 19, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9439371137](https://linux-hardware.org/?probe=9439371137) | Mar 18, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [c968526666](https://linux-hardware.org/?probe=c968526666) | Mar 18, 2023 |
| MSI           | MS-7360                     | Desktop     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8a802fa8fe](https://linux-hardware.org/?probe=8a802fa8fe) | Mar 16, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [679da48c41](https://linux-hardware.org/?probe=679da48c41) | Mar 16, 2023 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [11b2e17886](https://linux-hardware.org/?probe=11b2e17886) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| Gear          | Geranium                    | Notebook    | [8567411d91](https://linux-hardware.org/?probe=8567411d91) | Mar 13, 2023 |
| Gear          | Geranium                    | Notebook    | [1303244018](https://linux-hardware.org/?probe=1303244018) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [322b5bf476](https://linux-hardware.org/?probe=322b5bf476) | Mar 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [87779bfdea](https://linux-hardware.org/?probe=87779bfdea) | Mar 11, 2023 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [9a61fd62b3](https://linux-hardware.org/?probe=9a61fd62b3) | Mar 05, 2023 |
| HP            | 339A                        | Desktop     | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Dell          | Latitude 5410               | Notebook    | [6f55e8bbfe](https://linux-hardware.org/?probe=6f55e8bbfe) | Mar 05, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [daf95cc1e5](https://linux-hardware.org/?probe=daf95cc1e5) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [76645fa513](https://linux-hardware.org/?probe=76645fa513) | Feb 28, 2023 |
| HP            | 240 G4 Notebook PC          | Notebook    | [02744836e7](https://linux-hardware.org/?probe=02744836e7) | Feb 28, 2023 |
| Dell          | G3 3590                     | Notebook    | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b4485b65b3](https://linux-hardware.org/?probe=b4485b65b3) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [a52e16df32](https://linux-hardware.org/?probe=a52e16df32) | Feb 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6b712e555f](https://linux-hardware.org/?probe=6b712e555f) | Feb 26, 2023 |
| Dell          | System XPS L321X            | Notebook    | [4de5ba1c80](https://linux-hardware.org/?probe=4de5ba1c80) | Feb 25, 2023 |
| HP            | ProBook 4730s               | Notebook    | [6d563800a1](https://linux-hardware.org/?probe=6d563800a1) | Feb 24, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [969c2042b9](https://linux-hardware.org/?probe=969c2042b9) | Feb 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| HP            | 15                          | Notebook    | [470b07302a](https://linux-hardware.org/?probe=470b07302a) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Samsung       | R430/P430                   | Notebook    | [3bbea19ca4](https://linux-hardware.org/?probe=3bbea19ca4) | Feb 21, 2023 |
| HP            | Pavilion x360 14 G1         | Convertible | [77d9445484](https://linux-hardware.org/?probe=77d9445484) | Feb 20, 2023 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [51a7f0e66d](https://linux-hardware.org/?probe=51a7f0e66d) | Feb 19, 2023 |
| HP            | 15                          | Notebook    | [60ecad0be7](https://linux-hardware.org/?probe=60ecad0be7) | Feb 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [764c7eaffe](https://linux-hardware.org/?probe=764c7eaffe) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [6d64083839](https://linux-hardware.org/?probe=6d64083839) | Feb 17, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [7857666504](https://linux-hardware.org/?probe=7857666504) | Feb 16, 2023 |
| Dell          | Precision 7560              | Notebook    | [7ed10eebe9](https://linux-hardware.org/?probe=7ed10eebe9) | Feb 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [e78a97227a](https://linux-hardware.org/?probe=e78a97227a) | Feb 15, 2023 |
| ASUSTek       | K501UW                      | Notebook    | [45e719d7c0](https://linux-hardware.org/?probe=45e719d7c0) | Feb 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [247ab26b54](https://linux-hardware.org/?probe=247ab26b54) | Feb 14, 2023 |
| HP            | 14                          | Notebook    | [38554cf215](https://linux-hardware.org/?probe=38554cf215) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [c3f554a4bf](https://linux-hardware.org/?probe=c3f554a4bf) | Feb 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ba93ea14d](https://linux-hardware.org/?probe=4ba93ea14d) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [89f1272cd8](https://linux-hardware.org/?probe=89f1272cd8) | Feb 13, 2023 |
| HP            | 14                          | Notebook    | [610e26434d](https://linux-hardware.org/?probe=610e26434d) | Feb 12, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [a326374047](https://linux-hardware.org/?probe=a326374047) | Feb 12, 2023 |
| HP            | 1850                        | Desktop     | [54f5b16151](https://linux-hardware.org/?probe=54f5b16151) | Feb 11, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [3fce6d5f05](https://linux-hardware.org/?probe=3fce6d5f05) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [209a38d937](https://linux-hardware.org/?probe=209a38d937) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [1867884ede](https://linux-hardware.org/?probe=1867884ede) | Feb 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [104a086d29](https://linux-hardware.org/?probe=104a086d29) | Feb 05, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [578b166faa](https://linux-hardware.org/?probe=578b166faa) | Feb 05, 2023 |
| HP            | Presario CQ43               | Notebook    | [76bfeffd5f](https://linux-hardware.org/?probe=76bfeffd5f) | Feb 02, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [b3bb51473f](https://linux-hardware.org/?probe=b3bb51473f) | Feb 01, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MACHINIST     | X99Z V102 IENGINEER         | Desktop     | [d2cfaf56df](https://linux-hardware.org/?probe=d2cfaf56df) | Jan 31, 2023 |
| ViewSonic     | VOT132                      | Desktop     | [a8ecfadd53](https://linux-hardware.org/?probe=a8ecfadd53) | Jan 30, 2023 |
| HP            | Convertible x360 11-ab0X... | Convertible | [c56cc33809](https://linux-hardware.org/?probe=c56cc33809) | Jan 29, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [8a5423443a](https://linux-hardware.org/?probe=8a5423443a) | Jan 28, 2023 |
| Lenovo        | V14 G1 IML 82NA             | Notebook    | [c346600bdc](https://linux-hardware.org/?probe=c346600bdc) | Jan 25, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [cd487a22cd](https://linux-hardware.org/?probe=cd487a22cd) | Jan 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [30b373aafe](https://linux-hardware.org/?probe=30b373aafe) | Jan 25, 2023 |
| HP            | 2ADE                        | Desktop     | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Google        | Treeya                      | Notebook    | [27a381272a](https://linux-hardware.org/?probe=27a381272a) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [93db1bee75](https://linux-hardware.org/?probe=93db1bee75) | Jan 23, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [f872a64ba1](https://linux-hardware.org/?probe=f872a64ba1) | Jan 20, 2023 |
| MSI           | H81M-E33                    | Desktop     | [ddb1be1cc6](https://linux-hardware.org/?probe=ddb1be1cc6) | Jan 18, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [a9cad4d873](https://linux-hardware.org/?probe=a9cad4d873) | Jan 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| ASUSTek       | Q325UA                      | Convertible | [1862534df3](https://linux-hardware.org/?probe=1862534df3) | Jan 13, 2023 |
| Acer          | Aspire 2920                 | Notebook    | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [1a68bed616](https://linux-hardware.org/?probe=1a68bed616) | Jan 12, 2023 |
| HP            | 83F2                        | Desktop     | [7482186165](https://linux-hardware.org/?probe=7482186165) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [247bb9fe04](https://linux-hardware.org/?probe=247bb9fe04) | Jan 10, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [6c7f37297d](https://linux-hardware.org/?probe=6c7f37297d) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [5729420a54](https://linux-hardware.org/?probe=5729420a54) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [2923dcfe6f](https://linux-hardware.org/?probe=2923dcfe6f) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b345c4d626](https://linux-hardware.org/?probe=b345c4d626) | Jan 06, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3a3164f63f](https://linux-hardware.org/?probe=3a3164f63f) | Jan 04, 2023 |
| HP            | EliteBook 8740w (WH274UT... | Notebook    | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [68b3b51892](https://linux-hardware.org/?probe=68b3b51892) | Dec 30, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fdb827eff9](https://linux-hardware.org/?probe=fdb827eff9) | Dec 29, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [b593030fef](https://linux-hardware.org/?probe=b593030fef) | Dec 28, 2022 |
| HP            | 240 G6 Notebook PC          | Notebook    | [27e4ff648f](https://linux-hardware.org/?probe=27e4ff648f) | Dec 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [06d788f40a](https://linux-hardware.org/?probe=06d788f40a) | Dec 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6de981f1fc](https://linux-hardware.org/?probe=6de981f1fc) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [1397ed80b3](https://linux-hardware.org/?probe=1397ed80b3) | Dec 21, 2022 |
| HP            | 2B54 100                    | All in one  | [b47807a201](https://linux-hardware.org/?probe=b47807a201) | Dec 16, 2022 |
| HP            | 14                          | Notebook    | [4794938b36](https://linux-hardware.org/?probe=4794938b36) | Dec 14, 2022 |
| Dell          | Inspiron 7380               | Notebook    | [29d4feb456](https://linux-hardware.org/?probe=29d4feb456) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [d41bef1f84](https://linux-hardware.org/?probe=d41bef1f84) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [99e671f55f](https://linux-hardware.org/?probe=99e671f55f) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [9b714617c8](https://linux-hardware.org/?probe=9b714617c8) | Dec 04, 2022 |
| HP            | 14                          | Notebook    | [868daee488](https://linux-hardware.org/?probe=868daee488) | Dec 03, 2022 |
| ASUSTek       | K501UW                      | Notebook    | [1571941805](https://linux-hardware.org/?probe=1571941805) | Dec 03, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [aa9ad07031](https://linux-hardware.org/?probe=aa9ad07031) | Dec 01, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [703ef1c899](https://linux-hardware.org/?probe=703ef1c899) | Nov 30, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [f6745ce587](https://linux-hardware.org/?probe=f6745ce587) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [810ed5914a](https://linux-hardware.org/?probe=810ed5914a) | Nov 28, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [e479f87a66](https://linux-hardware.org/?probe=e479f87a66) | Nov 28, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [509dfbf1a4](https://linux-hardware.org/?probe=509dfbf1a4) | Nov 27, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [3413fb7947](https://linux-hardware.org/?probe=3413fb7947) | Nov 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| Alienware     | M17xR3                      | Notebook    | [438f3639aa](https://linux-hardware.org/?probe=438f3639aa) | Nov 24, 2022 |
| HP            | 8309                        | Desktop     | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [0627894c6b](https://linux-hardware.org/?probe=0627894c6b) | Nov 18, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [12073cb314](https://linux-hardware.org/?probe=12073cb314) | Nov 16, 2022 |
| Sony          | SVE1411EGXB                 | Notebook    | [dafea482eb](https://linux-hardware.org/?probe=dafea482eb) | Nov 14, 2022 |
| HP            | Pavilion g4                 | Notebook    | [44162d8878](https://linux-hardware.org/?probe=44162d8878) | Nov 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | Notebook    | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [7f498c5723](https://linux-hardware.org/?probe=7f498c5723) | Nov 08, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [cb1cecc5e1](https://linux-hardware.org/?probe=cb1cecc5e1) | Nov 05, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ece385acfe](https://linux-hardware.org/?probe=ece385acfe) | Nov 05, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7a183bdeb7](https://linux-hardware.org/?probe=7a183bdeb7) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [af85812864](https://linux-hardware.org/?probe=af85812864) | Nov 04, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3bd662e577](https://linux-hardware.org/?probe=3bd662e577) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [4a158afdfd](https://linux-hardware.org/?probe=4a158afdfd) | Nov 02, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [15690a2198](https://linux-hardware.org/?probe=15690a2198) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [2e4c04ada0](https://linux-hardware.org/?probe=2e4c04ada0) | Oct 27, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [cb31f9ab8b](https://linux-hardware.org/?probe=cb31f9ab8b) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [3d3ac2530c](https://linux-hardware.org/?probe=3d3ac2530c) | Oct 25, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| HP            | 225E                        | Desktop     | [7e246d254b](https://linux-hardware.org/?probe=7e246d254b) | Oct 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b6b5c1468c](https://linux-hardware.org/?probe=b6b5c1468c) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Google        | Treeya                      | Notebook    | [1a93d190b0](https://linux-hardware.org/?probe=1a93d190b0) | Oct 21, 2022 |
| Lenovo        | ThinkPad T470 20JNS01R01    | Notebook    | [abb8194196](https://linux-hardware.org/?probe=abb8194196) | Oct 21, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [c2f91318fe](https://linux-hardware.org/?probe=c2f91318fe) | Oct 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b3c91d2b0](https://linux-hardware.org/?probe=2b3c91d2b0) | Oct 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [e3dcca8113](https://linux-hardware.org/?probe=e3dcca8113) | Oct 11, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [593d28a4cf](https://linux-hardware.org/?probe=593d28a4cf) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [04e29685a6](https://linux-hardware.org/?probe=04e29685a6) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [2a8fd02f04](https://linux-hardware.org/?probe=2a8fd02f04) | Oct 07, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [6680cedc5e](https://linux-hardware.org/?probe=6680cedc5e) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55f843ecf6](https://linux-hardware.org/?probe=55f843ecf6) | Oct 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3bbd57ceea](https://linux-hardware.org/?probe=3bbd57ceea) | Oct 02, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5283dee456](https://linux-hardware.org/?probe=5283dee456) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | Notebook    | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [4684b672f6](https://linux-hardware.org/?probe=4684b672f6) | Sep 30, 2022 |
| SK hynix      | HyBook                      | Notebook    | [38b5f704a1](https://linux-hardware.org/?probe=38b5f704a1) | Sep 30, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [ce2d41ee99](https://linux-hardware.org/?probe=ce2d41ee99) | Sep 30, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [09795617ab](https://linux-hardware.org/?probe=09795617ab) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1570daf698](https://linux-hardware.org/?probe=1570daf698) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [58caf99a77](https://linux-hardware.org/?probe=58caf99a77) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [bd2dea6653](https://linux-hardware.org/?probe=bd2dea6653) | Sep 29, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [2d55b9b35e](https://linux-hardware.org/?probe=2d55b9b35e) | Sep 28, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [cf179c716e](https://linux-hardware.org/?probe=cf179c716e) | Sep 27, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [01cf3c6f99](https://linux-hardware.org/?probe=01cf3c6f99) | Sep 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [7dc3fbcf76](https://linux-hardware.org/?probe=7dc3fbcf76) | Sep 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Sony          | VAIO                        | All in one  | [0e3271f88f](https://linux-hardware.org/?probe=0e3271f88f) | Sep 19, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f6ccaeed5e](https://linux-hardware.org/?probe=f6ccaeed5e) | Sep 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [277daa8d6d](https://linux-hardware.org/?probe=277daa8d6d) | Sep 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [2ac6776181](https://linux-hardware.org/?probe=2ac6776181) | Sep 13, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [7ec64e9e08](https://linux-hardware.org/?probe=7ec64e9e08) | Sep 13, 2022 |
| Dell          | 060K5C A00                  | Desktop     | [a64a44387b](https://linux-hardware.org/?probe=a64a44387b) | Sep 13, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [6847632df3](https://linux-hardware.org/?probe=6847632df3) | Sep 12, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6f309073f2](https://linux-hardware.org/?probe=6f309073f2) | Sep 11, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [c1a16c7963](https://linux-hardware.org/?probe=c1a16c7963) | Sep 06, 2022 |
| Lenovo        | 14w 81MQ00AVCL              | Notebook    | [2ae4968612](https://linux-hardware.org/?probe=2ae4968612) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2176e4d70f](https://linux-hardware.org/?probe=2176e4d70f) | Sep 05, 2022 |
| ECS           | H61H-G11/7.0                | Desktop     | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [f1198508de](https://linux-hardware.org/?probe=f1198508de) | Sep 03, 2022 |
| Lenovo        | ThinkPad T480 20L6S80G00    | Notebook    | [bd599c876c](https://linux-hardware.org/?probe=bd599c876c) | Sep 02, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ec88b5b492](https://linux-hardware.org/?probe=ec88b5b492) | Sep 02, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Chile/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 108       | 7.65%   |
| Ubuntu 18.04                 | 75        | 5.31%   |
| Ubuntu 22.04                 | 68        | 4.82%   |
| Arch Rolling                 | 54        | 3.82%   |
| Fedora 40                    | 38        | 2.69%   |
| Pop!_OS 22.04                | 37        | 2.62%   |
| Fedora 38                    | 32        | 2.27%   |
| Ubuntu 24.04                 | 28        | 1.98%   |
| Manjaro                      | 27        | 1.91%   |
| Debian 12                    | 27        | 1.91%   |
| Zorin 16                     | 26        | 1.84%   |
| OpenMandriva 4.3             | 24        | 1.7%    |
| OpenMandriva 4.2             | 23        | 1.63%   |
| Arch                         | 23        | 1.63%   |
| Ubuntu 19.04                 | 22        | 1.56%   |
| Debian 11                    | 19        | 1.35%   |
| KDE neon 22.04               | 17        | 1.2%    |
| Fedora 39                    | 17        | 1.2%    |
| Debian 10                    | 17        | 1.2%    |
| Zorin 17                     | 16        | 1.13%   |
| Fedora 37                    | 16        | 1.13%   |
| Fedora 34                    | 16        | 1.13%   |
| Linux Mint 21.3              | 15        | 1.06%   |
| Linux Mint 21.1              | 15        | 1.06%   |
| Linux Mint 20.1              | 15        | 1.06%   |
| KDE neon 20.04               | 15        | 1.06%   |
| Fedora 35                    | 15        | 1.06%   |
| Zorin 15                     | 14        | 0.99%   |
| OpenMandriva 23.01           | 14        | 0.99%   |
| Pop!_OS 20.04                | 13        | 0.92%   |
| Ubuntu 22.10                 | 12        | 0.85%   |
| Ubuntu 19.10                 | 12        | 0.85%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 0.85%   |
| OpenMandriva 23.08           | 12        | 0.85%   |
| Ubuntu 23.04                 | 11        | 0.78%   |
| Ubuntu 21.10                 | 11        | 0.78%   |
| Ubuntu 20.10                 | 11        | 0.78%   |
| Linux Mint 21.2              | 11        | 0.78%   |
| Fedora 32                    | 11        | 0.78%   |
| EndeavourOS Rolling          | 11        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 375       | 28.09%  |
| Fedora        | 157       | 11.76%  |
| Linux Mint    | 99        | 7.42%   |
| OpenMandriva  | 94        | 7.04%   |
| Debian        | 75        | 5.62%   |
| Arch          | 72        | 5.39%   |
| Pop!_OS       | 64        | 4.79%   |
| Zorin         | 57        | 4.27%   |
| Manjaro       | 39        | 2.92%   |
| KDE neon      | 38        | 2.85%   |
| Kubuntu       | 28        | 2.1%    |
| Elementary    | 20        | 1.5%    |
| openSUSE      | 17        | 1.27%   |
| ROSA          | 16        | 1.2%    |
| Xubuntu       | 14        | 1.05%   |
| SteamOS       | 11        | 0.82%   |
| Lubuntu       | 11        | 0.82%   |
| EndeavourOS   | 11        | 0.82%   |
| ArcoLinux     | 11        | 0.82%   |
| Ubuntu MATE   | 10        | 0.75%   |
| Kali          | 9         | 0.67%   |
| Nobara        | 8         | 0.6%    |
| Loc OS        | 7         | 0.52%   |
| Endless       | 7         | 0.52%   |
| Ubuntu Budgie | 6         | 0.45%   |
| LMDE          | 6         | 0.45%   |
| Xero          | 5         | 0.37%   |
| MX            | 5         | 0.37%   |
| Gentoo        | 5         | 0.37%   |
| Clear Linux   | 5         | 0.37%   |
| Deepin        | 4         | 0.3%    |
| Ubuntu Unity  | 3         | 0.22%   |
| Solus         | 3         | 0.22%   |
| RHEL          | 3         | 0.22%   |
| Parrot        | 3         | 0.22%   |
| Cuerdos       | 3         | 0.22%   |
| Ultramarine   | 2         | 0.15%   |
| Slackware     | 2         | 0.15%   |
| LinuxFX       | 2         | 0.15%   |
| Linux Lite    | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003             | 24        | 1.53%   |
| 5.10.14-desktop-1omv4002            | 21        | 1.34%   |
| 6.1.1-desktop-1omv2290              | 13        | 0.83%   |
| 5.4.0-42-generic                    | 13        | 0.83%   |
| 6.9.3-76060903-generic              | 11        | 0.7%    |
| 6.4.11-desktop-1omv2390             | 9         | 0.57%   |
| 5.4.0-26-generic                    | 9         | 0.57%   |
| 5.15.0-56-generic                   | 9         | 0.57%   |
| 5.0.0-13-generic                    | 9         | 0.57%   |
| 6.8.0-40-generic                    | 8         | 0.51%   |
| 6.8.0-31-generic                    | 8         | 0.51%   |
| 6.2.6-desktop-1omv2390              | 8         | 0.51%   |
| 5.8.0-50-generic                    | 8         | 0.51%   |
| 5.8.0-48-generic                    | 8         | 0.51%   |
| 5.4.0-58-generic                    | 8         | 0.51%   |
| 6.8.0-47-generic                    | 7         | 0.45%   |
| 6.5.0-41-generic                    | 7         | 0.45%   |
| 5.4.0-48-generic                    | 7         | 0.45%   |
| 5.4.0-47-generic                    | 7         | 0.45%   |
| 5.15.0-58-generic                   | 7         | 0.45%   |
| 5.15.0-52-generic                   | 7         | 0.45%   |
| 5.15.0-48-generic                   | 7         | 0.45%   |
| 5.11.0-27-generic                   | 7         | 0.45%   |
| 5.0.0-23-generic                    | 7         | 0.45%   |
| 4.18.0-15-generic                   | 7         | 0.45%   |
| 6.8.0-76060800daily20240311-generic | 6         | 0.38%   |
| 6.8.0-51-generic                    | 6         | 0.38%   |
| 6.8.0-49-generic                    | 6         | 0.38%   |
| 6.2.6-76060206-generic              | 6         | 0.38%   |
| 6.2.0-39-generic                    | 6         | 0.38%   |
| 6.2.0-20-generic                    | 6         | 0.38%   |
| 5.4.0-56-generic                    | 6         | 0.38%   |
| 5.4.0-52-generic                    | 6         | 0.38%   |
| 5.4.0-29-generic                    | 6         | 0.38%   |
| 5.19.0-38-generic                   | 6         | 0.38%   |
| 5.19.0-35-generic                   | 6         | 0.38%   |
| 5.15.0-67-generic                   | 6         | 0.38%   |
| 5.15.0-60-generic                   | 6         | 0.38%   |
| 5.15.0-41-generic                   | 6         | 0.38%   |
| 5.11.0-37-generic                   | 6         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 154       | 10.26%  |
| 5.15.0  | 112       | 7.46%   |
| 6.8.0   | 59        | 3.93%   |
| 5.8.0   | 49        | 3.26%   |
| 5.11.0  | 49        | 3.26%   |
| 6.5.0   | 48        | 3.2%    |
| 5.0.0   | 45        | 3%      |
| 5.19.0  | 41        | 2.73%   |
| 4.15.0  | 41        | 2.73%   |
| 5.3.0   | 38        | 2.53%   |
| 6.2.0   | 37        | 2.47%   |
| 5.13.0  | 33        | 2.2%    |
| 4.18.0  | 28        | 1.87%   |
| 6.1.0   | 26        | 1.73%   |
| 5.16.7  | 24        | 1.6%    |
| 5.10.0  | 22        | 1.47%   |
| 5.10.14 | 21        | 1.4%    |
| 6.1.1   | 16        | 1.07%   |
| 6.2.6   | 15        | 1%      |
| 6.9.3   | 14        | 0.93%   |
| 5.14.0  | 13        | 0.87%   |
| 4.19.0  | 13        | 0.87%   |
| 6.4.11  | 10        | 0.67%   |
| 6.8.9   | 9         | 0.6%    |
| 6.0.0   | 9         | 0.6%    |
| 6.6.2   | 8         | 0.53%   |
| 6.10.10 | 8         | 0.53%   |
| 6.4.8   | 7         | 0.47%   |
| 6.11.0  | 7         | 0.47%   |
| 6.8.11  | 6         | 0.4%    |
| 5.9.16  | 6         | 0.4%    |
| 4.9.60  | 6         | 0.4%    |
| 6.9.5   | 5         | 0.33%   |
| 6.8.5   | 5         | 0.33%   |
| 6.6.6   | 5         | 0.33%   |
| 6.5.6   | 5         | 0.33%   |
| 6.3.8   | 5         | 0.33%   |
| 6.2.9   | 5         | 0.33%   |
| 6.11.3  | 5         | 0.33%   |
| 6.10.9  | 5         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 160       | 10.87%  |
| 5.15    | 124       | 8.42%   |
| 6.8     | 87        | 5.91%   |
| 6.1     | 75        | 5.1%    |
| 6.2     | 72        | 4.89%   |
| 5.10    | 71        | 4.82%   |
| 6.5     | 67        | 4.55%   |
| 5.11    | 66        | 4.48%   |
| 5.19    | 61        | 4.14%   |
| 5.8     | 54        | 3.67%   |
| 5.13    | 49        | 3.33%   |
| 5.0     | 48        | 3.26%   |
| 4.15    | 41        | 2.79%   |
| 5.3     | 40        | 2.72%   |
| 6.4     | 38        | 2.58%   |
| 6.10    | 38        | 2.58%   |
| 5.16    | 38        | 2.58%   |
| 6.9     | 37        | 2.51%   |
| 6.6     | 34        | 2.31%   |
| 4.18    | 29        | 1.97%   |
| 6.11    | 28        | 1.9%    |
| 6.3     | 24        | 1.63%   |
| 6.0     | 23        | 1.56%   |
| 6.7     | 22        | 1.49%   |
| 5.17    | 22        | 1.49%   |
| 5.14    | 21        | 1.43%   |
| 5.9     | 16        | 1.09%   |
| 5.12    | 16        | 1.09%   |
| 4.19    | 15        | 1.02%   |
| 5.18    | 13        | 0.88%   |
| 4.9     | 10        | 0.68%   |
| 5.6     | 7         | 0.48%   |
| 6.12    | 6         | 0.41%   |
| 5.5     | 6         | 0.41%   |
| 5.7     | 4         | 0.27%   |
| 4.4     | 4         | 0.27%   |
| 5.1     | 3         | 0.2%    |
| 4.13    | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1250      | 98.04%  |
| i686    | 21        | 1.65%   |
| aarch64 | 3         | 0.24%   |
| Unknown | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 610       | 45.56%  |
| KDE5             | 230       | 17.18%  |
| Unknown          | 125       | 9.34%   |
| XFCE             | 88        | 6.57%   |
| X-Cinnamon       | 82        | 6.12%   |
| KDE6             | 34        | 2.54%   |
| KDE              | 33        | 2.46%   |
| MATE             | 24        | 1.79%   |
| Pantheon         | 21        | 1.57%   |
| LXDE             | 14        | 1.05%   |
| KDE4             | 12        | 0.9%    |
| Budgie           | 11        | 0.82%   |
| LXQt             | 10        | 0.75%   |
| i3               | 10        | 0.75%   |
| Cinnamon         | 8         | 0.6%    |
| Deepin           | 6         | 0.45%   |
| Unity            | 3         | 0.22%   |
| GNOME Flashback  | 3         | 0.22%   |
| awesome          | 3         | 0.22%   |
| xmonad           | 2         | 0.15%   |
| qtile            | 2         | 0.15%   |
| Trinity          | 1         | 0.07%   |
| sway             | 1         | 0.07%   |
| lightdm-xsession | 1         | 0.07%   |
| icewm            | 1         | 0.07%   |
| Hyprland         | 1         | 0.07%   |
| Enlightenment    | 1         | 0.07%   |
| COSMIC           | 1         | 0.07%   |
| bspwm            | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 877       | 66.14%  |
| Wayland | 364       | 27.45%  |
| Unknown | 70        | 5.28%   |
| Tty     | 15        | 1.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 712       | 53.17%  |
| SDDM    | 197       | 14.71%  |
| GDM3    | 149       | 11.13%  |
| GDM     | 129       | 9.63%   |
| LightDM | 104       | 7.77%   |
| TDM     | 26        | 1.94%   |
| KDM     | 10        | 0.75%   |
| XDM     | 4         | 0.3%    |
| LXDM    | 4         | 0.3%    |
| LY-DM   | 2         | 0.15%   |
| SLIMSKI | 1         | 0.07%   |
| Ly      | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| es_CL      | 672       | 50.76%  |
| en_US      | 310       | 23.41%  |
| es_ES      | 115       | 8.69%   |
| Unknown    | 114       | 8.61%   |
| es_MX      | 37        | 2.79%   |
| en_GB      | 22        | 1.66%   |
| C          | 21        | 1.59%   |
| es_AR      | 9         | 0.68%   |
| es_VE      | 3         | 0.23%   |
| fr_FR      | 2         | 0.15%   |
| es_UY      | 2         | 0.15%   |
| es_BO      | 2         | 0.15%   |
| en_CA      | 2         | 0.15%   |
| de_DE      | 2         | 0.15%   |
| ru_RU      | 1         | 0.08%   |
| pt_BR      | 1         | 0.08%   |
| nl_NL      | 1         | 0.08%   |
| latam_IT   | 1         | 0.08%   |
| es_US      | 1         | 0.08%   |
| es_EC      | 1         | 0.08%   |
| es_CO      | 1         | 0.08%   |
| es_CL.UTF8 | 1         | 0.08%   |
| en_AU      | 1         | 0.08%   |
| en_AG      | 1         | 0.08%   |
| arn_CL     | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 653       | 50.08%  |
| BIOS | 651       | 49.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 903       | 67.84%  |
| Btrfs    | 215       | 16.15%  |
| Overlay  | 82        | 6.16%   |
| Tmpfs    | 64        | 4.81%   |
| Unknown  | 40        | 3.01%   |
| Xfs      | 15        | 1.13%   |
| Zfs      | 4         | 0.3%    |
| Ext2     | 4         | 0.3%    |
| Jfs      | 1         | 0.08%   |
| F2fs     | 1         | 0.08%   |
| Ext3     | 1         | 0.08%   |
| Bcachefs | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 727       | 54.91%  |
| GPT     | 504       | 38.07%  |
| MBR     | 93        | 7.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1168      | 89.5%   |
| Yes       | 137       | 10.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 953       | 72.58%  |
| Yes       | 360       | 27.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 285       | 22.37%  |
| ASUSTek Computer    | 217       | 17.03%  |
| Lenovo              | 195       | 15.31%  |
| Dell                | 105       | 8.24%   |
| Acer                | 84        | 6.59%   |
| MSI                 | 58        | 4.55%   |
| Samsung Electronics | 33        | 2.59%   |
| Gigabyte Technology | 32        | 2.51%   |
| Apple               | 29        | 2.28%   |
| Toshiba             | 27        | 2.12%   |
| Intel               | 26        | 2.04%   |
| Unknown             | 21        | 1.65%   |
| Sony                | 20        | 1.57%   |
| ECS                 | 15        | 1.18%   |
| HUAWEI              | 13        | 1.02%   |
| ASRock              | 11        | 0.86%   |
| Valve               | 10        | 0.78%   |
| Packard Bell        | 10        | 0.78%   |
| Huanan              | 6         | 0.47%   |
| Pegatron            | 5         | 0.39%   |
| SK hynix            | 4         | 0.31%   |
| Google              | 4         | 0.31%   |
| Chuwi               | 4         | 0.31%   |
| AZW                 | 4         | 0.31%   |
| AMI                 | 3         | 0.24%   |
| TPV-INVENTA         | 2         | 0.16%   |
| Olidata             | 2         | 0.16%   |
| MACHINIST           | 2         | 0.16%   |
| HONOR               | 2         | 0.16%   |
| HC                  | 2         | 0.16%   |
| Foxconn             | 2         | 0.16%   |
| eMachines           | 2         | 0.16%   |
| Alienware           | 2         | 0.16%   |
| ZOTAC               | 1         | 0.08%   |
| WZA300S2R120        | 1         | 0.08%   |
| Wings Mobile        | 1         | 0.08%   |
| VIT                 | 1         | 0.08%   |
| ViewSonic           | 1         | 0.08%   |
| TAGTech             | 1         | 0.08%   |
| SZMZ                | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                           | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Unknown                                        | 26        | 2.04%   |
| HP Notebook                                    | 13        | 1.02%   |
| HP 240 G6 Notebook PC                          | 12        | 0.94%   |
| Valve Jupiter                                  | 10        | 0.78%   |
| HP ENVY 15                                     | 9         | 0.71%   |
| ASUS All Series                                | 8         | 0.63%   |
| HP Pavilion Notebook                           | 7         | 0.55%   |
| MSI MS-7817                                    | 6         | 0.47%   |
| HP Pavilion g4                                 | 6         | 0.47%   |
| HP 14                                          | 6         | 0.47%   |
| ASUS ZenBook UX325EA_UX325EA                   | 6         | 0.47%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA       | 6         | 0.47%   |
| ASUS PRIME B450M-A                             | 6         | 0.47%   |
| HP Pavilion Laptop 15-eh0xxx                   | 5         | 0.39%   |
| HP Pavilion Laptop 15-cw1xxx                   | 5         | 0.39%   |
| HP Pavilion Gaming Laptop 15-ec1xxx            | 5         | 0.39%   |
| HP Pavilion 15                                 | 5         | 0.39%   |
| HP EliteBook 840 G6                            | 5         | 0.39%   |
| ASUS PRIME A320M-K                             | 5         | 0.39%   |
| Acer Aspire A315-42                            | 5         | 0.39%   |
| Lenovo Legion Y530-15ICH 81FV                  | 4         | 0.31%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK          | 4         | 0.31%   |
| HUAWEI BOHK-WAX9X                              | 4         | 0.31%   |
| HP 250 G6 Notebook PC                          | 4         | 0.31%   |
| HP 1000                                        | 4         | 0.31%   |
| Dell Inspiron 3501                             | 4         | 0.31%   |
| ASUS VivoBook_ASUSLaptop M3604YA_M3604YA       | 4         | 0.31%   |
| Apple MacBookPro9,2                            | 4         | 0.31%   |
| Acer Aspire ES1-111M                           | 4         | 0.31%   |
| Toshiba Satellite L745                         | 3         | 0.24%   |
| Toshiba Satellite C45-A                        | 3         | 0.24%   |
| SK hynix HyBook                                | 3         | 0.24%   |
| Samsung RF511/RF411/RF711                      | 3         | 0.24%   |
| Samsung 750XED                                 | 3         | 0.24%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 3         | 0.24%   |
| MSI MS-7A34                                    | 3         | 0.24%   |
| MSI MS-7A15                                    | 3         | 0.24%   |
| MSI MS-7788                                    | 3         | 0.24%   |
| Lenovo Y520-15IKBN 80WK                        | 3         | 0.24%   |
| Lenovo IdeaPad S540-15IWL 81NE                 | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 78        | 6.12%   |
| HP Pavilion           | 68        | 5.34%   |
| Acer Aspire           | 61        | 4.79%   |
| Lenovo IdeaPad        | 60        | 4.71%   |
| ASUS VivoBook         | 42        | 3.3%    |
| Dell Inspiron         | 37        | 2.9%    |
| Dell Latitude         | 30        | 2.35%   |
| ASUS PRIME            | 27        | 2.12%   |
| ASUS TUF              | 26        | 2.04%   |
| Unknown               | 26        | 2.04%   |
| HP ENVY               | 23        | 1.81%   |
| HP EliteBook          | 23        | 1.81%   |
| Toshiba Satellite     | 20        | 1.57%   |
| HP Laptop             | 20        | 1.57%   |
| HP 240                | 19        | 1.49%   |
| HP ProBook            | 17        | 1.33%   |
| ASUS ZenBook          | 16        | 1.26%   |
| HP Compaq             | 15        | 1.18%   |
| ASUS ROG              | 14        | 1.1%    |
| HP Notebook           | 13        | 1.02%   |
| ASUS ASUS             | 12        | 0.94%   |
| Valve Jupiter         | 10        | 0.78%   |
| Lenovo Legion         | 9         | 0.71%   |
| Dell OptiPlex         | 9         | 0.71%   |
| Lenovo ThinkCentre    | 8         | 0.63%   |
| Dell Precision        | 8         | 0.63%   |
| ASUS All              | 8         | 0.63%   |
| Acer Swift            | 8         | 0.63%   |
| Packard Bell EasyNote | 7         | 0.55%   |
| HP EliteDesk          | 7         | 0.55%   |
| HP 250                | 7         | 0.55%   |
| HP 245                | 7         | 0.55%   |
| Dell Vostro           | 7         | 0.55%   |
| Acer Nitro            | 7         | 0.55%   |
| MSI MS-7817           | 6         | 0.47%   |
| HP OMEN               | 6         | 0.47%   |
| HP 14                 | 6         | 0.47%   |
| Apple MacBookPro11    | 6         | 0.47%   |
| HP ProDesk            | 5         | 0.39%   |
| HP Presario           | 5         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 138       | 10.83%  |
| 2019    | 115       | 9.03%   |
| 2018    | 110       | 8.63%   |
| 2017    | 108       | 8.48%   |
| 2021    | 102       | 8.01%   |
| 2013    | 91        | 7.14%   |
| 2012    | 85        | 6.67%   |
| 2011    | 83        | 6.51%   |
| 2016    | 71        | 5.57%   |
| 2014    | 66        | 5.18%   |
| 2015    | 54        | 4.24%   |
| 2010    | 53        | 4.16%   |
| 2022    | 47        | 3.69%   |
| 2023    | 37        | 2.9%    |
| 2008    | 37        | 2.9%    |
| 2007    | 36        | 2.83%   |
| 2009    | 27        | 2.12%   |
| 2024    | 6         | 0.47%   |
| 2006    | 4         | 0.31%   |
| Unknown | 3         | 0.24%   |
| 2005    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 878       | 68.92%  |
| Desktop        | 320       | 25.12%  |
| Convertible    | 21        | 1.65%   |
| All in one     | 21        | 1.65%   |
| Mini pc        | 18        | 1.41%   |
| Tablet         | 12        | 0.94%   |
| Server         | 3         | 0.24%   |
| System on chip | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1175      | 91.23%  |
| Enabled  | 113       | 8.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1270      | 99.69%  |
| Yes  | 4         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 351       | 26.98%  |
| 8.01-16.0   | 267       | 20.52%  |
| 16.01-24.0  | 237       | 18.22%  |
| 3.01-4.0    | 236       | 18.14%  |
| 32.01-64.0  | 94        | 7.23%   |
| 1.01-2.0    | 50        | 3.84%   |
| 24.01-32.0  | 27        | 2.08%   |
| 2.01-3.0    | 18        | 1.38%   |
| 64.01-256.0 | 18        | 1.38%   |
| 0.51-1.0    | 2         | 0.15%   |
| Unknown     | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 418       | 29.33%  |
| 2.01-3.0   | 365       | 25.61%  |
| 3.01-4.0   | 260       | 18.25%  |
| 4.01-8.0   | 254       | 17.82%  |
| 0.51-1.0   | 61        | 4.28%   |
| 8.01-16.0  | 58        | 4.07%   |
| 0.01-0.5   | 5         | 0.35%   |
| 16.01-24.0 | 2         | 0.14%   |
| 24.01-32.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 849       | 64.32%  |
| 2      | 328       | 24.85%  |
| 3      | 80        | 6.06%   |
| 4      | 36        | 2.73%   |
| 5      | 13        | 0.98%   |
| 0      | 7         | 0.53%   |
| 7      | 3         | 0.23%   |
| 6      | 3         | 0.23%   |
| 8      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 931       | 72.28%  |
| Yes       | 357       | 27.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1075      | 84.12%  |
| No        | 203       | 15.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1079      | 84.3%   |
| No        | 201       | 15.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 898       | 69.56%  |
| No        | 393       | 30.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Chile   | 1274      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Santiago            | 525       | 38.6%   |
| Viña del Mar       | 66        | 4.85%   |
| Concepción         | 65        | 4.78%   |
| Las Condes          | 37        | 2.72%   |
| Temuco              | 36        | 2.65%   |
| Maipu               | 33        | 2.43%   |
| Puente Alto         | 31        | 2.28%   |
| Valdivia            | 27        | 1.99%   |
| Antofagasta         | 25        | 1.84%   |
| Nunoa               | 23        | 1.69%   |
| La Florida          | 23        | 1.69%   |
| Providencia         | 20        | 1.47%   |
| La Serena           | 19        | 1.4%    |
| Valparaíso         | 17        | 1.25%   |
| San Miguel          | 17        | 1.25%   |
| Port Montt          | 17        | 1.25%   |
| Rancagua            | 13        | 0.96%   |
| Quilpué            | 13        | 0.96%   |
| Iquique             | 12        | 0.88%   |
| Coronel             | 11        | 0.81%   |
| Talca               | 10        | 0.74%   |
| Osorno              | 10        | 0.74%   |
| Melipilla           | 10        | 0.74%   |
| Los Ángeles        | 10        | 0.74%   |
| Coquimbo            | 10        | 0.74%   |
| Talcahuano          | 9         | 0.66%   |
| San Pedro de la Paz | 8         | 0.59%   |
| Macul               | 8         | 0.59%   |
| Arica               | 8         | 0.59%   |
| San Bernardo        | 7         | 0.51%   |
| Quillota            | 7         | 0.51%   |
| Quilicura           | 7         | 0.51%   |
| Curicó             | 7         | 0.51%   |
| Colina              | 7         | 0.51%   |
| Chillan             | 7         | 0.51%   |
| Penalolen           | 6         | 0.44%   |
| La Reina            | 6         | 0.44%   |
| Hualpen             | 6         | 0.44%   |
| Central             | 6         | 0.44%   |
| Vitacura            | 5         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 308       | 457    | 17.23%  |
| Seagate                     | 212       | 296    | 11.86%  |
| Kingston                    | 152       | 235    | 8.5%    |
| Toshiba                     | 148       | 177    | 8.28%   |
| Samsung Electronics         | 147       | 207    | 8.22%   |
| Crucial                     | 110       | 139    | 6.15%   |
| SanDisk                     | 93        | 137    | 5.2%    |
| Unknown                     | 79        | 107    | 4.42%   |
| Hitachi                     | 52        | 66     | 2.91%   |
| SK hynix                    | 48        | 63     | 2.68%   |
| HGST                        | 43        | 49     | 2.4%    |
| Intel                       | 41        | 61     | 2.29%   |
| Micron Technology           | 35        | 56     | 1.96%   |
| China                       | 34        | 43     | 1.9%    |
| Kingston Technology Company | 28        | 38     | 1.57%   |
| Apple                       | 21        | 26     | 1.17%   |
| Silicon Motion              | 18        | 19     | 1.01%   |
| Micron/Crucial Technology   | 16        | 26     | 0.89%   |
| KIOXIA                      | 15        | 19     | 0.84%   |
| KingSpec                    | 13        | 23     | 0.73%   |
| JMicron Technology          | 13        | 15     | 0.73%   |
| A-DATA Technology           | 10        | 14     | 0.56%   |
| Lexar                       | 9         | 26     | 0.5%    |
| Phison Electronics          | 8         | 10     | 0.45%   |
| XrayDisk                    | 6         | 7      | 0.34%   |
| XPG                         | 6         | 18     | 0.34%   |
| MAXIO Technology (Hangzhou) | 6         | 8      | 0.34%   |
| Corsair                     | 6         | 11     | 0.34%   |
| Realtek                     | 5         | 6      | 0.28%   |
| Maxtor                      | 5         | 8      | 0.28%   |
| LITEON                      | 5         | 5      | 0.28%   |
| Unknown                     | 5         | 5      | 0.28%   |
| SSSTC                       | 4         | 5      | 0.22%   |
| Realtek Semiconductor       | 4         | 5      | 0.22%   |
| O2 Micro                    | 4         | 4      | 0.22%   |
| Netac                       | 4         | 5      | 0.22%   |
| WALRAM                      | 3         | 4      | 0.17%   |
| Phison                      | 3         | 3      | 0.17%   |
| Mass                        | 3         | 3      | 0.17%   |
| Gigabyte Technology         | 3         | 5      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 28        | 1.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 27        | 1.39%   |
| Kingston SA400S37480G 480GB SSD                     | 27        | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB                      | 24        | 1.24%   |
| Crucial CT240BX500SSD1 240GB                        | 24        | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 19        | 0.98%   |
| Toshiba DT01ACA100 1TB                              | 18        | 0.93%   |
| Toshiba MQ01ABF050 500GB                            | 17        | 0.88%   |
| Seagate ST500DM002-1BD142 500GB                     | 17        | 0.88%   |
| Seagate ST500LT012-1DG142 500GB                     | 16        | 0.83%   |
| Crucial CT480BX500SSD1 480GB                        | 16        | 0.83%   |
| Unknown MMC Card  64GB                              | 15        | 0.77%   |
| Toshiba MQ01ABD100 1TB                              | 15        | 0.77%   |
| Toshiba HDWD110 1TB                                 | 15        | 0.77%   |
| Crucial CT500MX500SSD1 500GB                        | 15        | 0.77%   |
| Toshiba MQ04ABF100 1TB                              | 14        | 0.72%   |
| Unknown MMC Card  32GB                              | 13        | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 12        | 0.62%   |
| Unknown MMC Card  128GB                             | 12        | 0.62%   |
| Seagate ST9500325AS 500GB                           | 12        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 12        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 11        | 0.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 11        | 0.57%   |
| Kingston Company SNV2S1000G 1TB                     | 11        | 0.57%   |
| Crucial CT1000MX500SSD1 1TB                         | 11        | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 10        | 0.52%   |
| WDC WD Green 2.5 240GB SSD                          | 10        | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 10        | 0.52%   |
| JMicron Generic 500GB                               | 10        | 0.52%   |
| Crucial CT120BX500SSD1 120GB                        | 10        | 0.52%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 9         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 9         | 0.46%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 9         | 0.46%   |
| Samsung NVMe SSD Drive 512GB                        | 9         | 0.46%   |
| Kingston SUV400S37120G 120GB SSD                    | 9         | 0.46%   |
| Intel SSDPEKNU512GZ 512GB                           | 9         | 0.46%   |
| HGST HTS545050A7E680 500GB                          | 9         | 0.46%   |
| HGST HTS541010A9E680 1TB                            | 9         | 0.46%   |
| WDC WD10SPZX-24Z10 1TB                              | 8         | 0.41%   |
| Seagate ST500LT012-9WS142 500GB                     | 8         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 210       | 291    | 30.13%  |
| WDC                 | 207       | 282    | 29.7%   |
| Toshiba             | 134       | 159    | 19.23%  |
| Hitachi             | 52        | 66     | 7.46%   |
| HGST                | 43        | 49     | 6.17%   |
| Samsung Electronics | 17        | 21     | 2.44%   |
| JMicron Technology  | 10        | 12     | 1.43%   |
| Apple               | 10        | 11     | 1.43%   |
| Unknown             | 4         | 4      | 0.57%   |
| Maxtor              | 4         | 6      | 0.57%   |
| ASMT                | 2         | 3      | 0.29%   |
| SAGE                | 1         | 1      | 0.14%   |
| SABRENT             | 1         | 1      | 0.14%   |
| Fujitsu             | 1         | 1      | 0.14%   |
| ASMedia             | 1         | 2      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 120       | 184    | 22.26%  |
| Crucial             | 106       | 134    | 19.67%  |
| WDC                 | 100       | 143    | 18.55%  |
| Samsung Electronics | 41        | 55     | 7.61%   |
| China               | 34        | 43     | 6.31%   |
| SanDisk             | 24        | 31     | 4.45%   |
| KingSpec            | 13        | 23     | 2.41%   |
| Lexar               | 8         | 24     | 1.48%   |
| Apple               | 8         | 8      | 1.48%   |
| A-DATA Technology   | 7         | 11     | 1.3%    |
| SK hynix            | 6         | 9      | 1.11%   |
| Micron Technology   | 6         | 6      | 1.11%   |
| Corsair             | 6         | 11     | 1.11%   |
| XrayDisk            | 4         | 5      | 0.74%   |
| Toshiba             | 3         | 7      | 0.56%   |
| LITEON              | 3         | 3      | 0.56%   |
| Intel               | 3         | 5      | 0.56%   |
| Gigabyte Technology | 3         | 5      | 0.56%   |
| FORESEE             | 3         | 4      | 0.56%   |
| Unknown             | 3         | 3      | 0.56%   |
| WALRAM              | 2         | 2      | 0.37%   |
| Unknown             | 2         | 2      | 0.37%   |
| StoreJet            | 2         | 2      | 0.37%   |
| SCY                 | 2         | 2      | 0.37%   |
| PNY                 | 2         | 2      | 0.37%   |
| Patriot             | 2         | 2      | 0.37%   |
| Netac               | 2         | 2      | 0.37%   |
| LITEONIT            | 2         | 2      | 0.37%   |
| HS-SSD-C100         | 2         | 2      | 0.37%   |
| ZOTAC               | 1         | 1      | 0.19%   |
| Wdxsky              | 1         | 1      | 0.19%   |
| Vaseky              | 1         | 1      | 0.19%   |
| USB3.0              | 1         | 1      | 0.19%   |
| SATA3 25            | 1         | 1      | 0.19%   |
| OWC                 | 1         | 1      | 0.19%   |
| OSCOO               | 1         | 1      | 0.19%   |
| OCZ                 | 1         | 2      | 0.19%   |
| NGFF                | 1         | 1      | 0.19%   |
| Min Yi U            | 1         | 1      | 0.19%   |
| MemoiresTek         | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 610       | 909    | 37.42%  |
| SSD     | 485       | 755    | 29.75%  |
| NVMe    | 441       | 701    | 27.06%  |
| MMC     | 69        | 92     | 4.23%   |
| Unknown | 25        | 29     | 1.53%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 932       | 1634   | 62.47%  |
| NVMe | 439       | 694    | 29.42%  |
| MMC  | 69        | 92     | 4.62%   |
| SAS  | 52        | 66     | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 680       | 1085   | 62.39%  |
| 0.51-1.0   | 336       | 459    | 30.83%  |
| 1.01-2.0   | 52        | 79     | 4.77%   |
| 3.01-4.0   | 12        | 16     | 1.1%    |
| 2.01-3.0   | 5         | 12     | 0.46%   |
| 4.01-10.0  | 5         | 13     | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 404       | 29.58%  |
| 101-250        | 327       | 23.94%  |
| 501-1000       | 216       | 15.81%  |
| 1001-2000      | 110       | 8.05%   |
| 1-20           | 86        | 6.3%    |
| 51-100         | 71        | 5.2%    |
| More than 3000 | 46        | 3.37%   |
| 21-50          | 40        | 2.93%   |
| 2001-3000      | 36        | 2.64%   |
| Unknown        | 30        | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 523       | 36.62%  |
| 21-50          | 269       | 18.84%  |
| 101-250        | 185       | 12.96%  |
| 51-100         | 172       | 12.04%  |
| 251-500        | 116       | 8.12%   |
| 501-1000       | 70        | 4.9%    |
| 1001-2000      | 36        | 2.52%   |
| Unknown        | 30        | 2.1%    |
| More than 3000 | 13        | 0.91%   |
| 2001-3000      | 13        | 0.91%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB     | 4         | 4      | 3.13%   |
| HGST HTS545050A7E680 500GB          | 4         | 4      | 3.13%   |
| Seagate ST9500325AS 500GB           | 3         | 4      | 2.34%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 2.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 9      | 2.34%   |
| HGST HTS545050A7E380 500GB          | 3         | 3      | 2.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 1.56%   |
| WDC WD1600BEVT-35VW9T0 160GB        | 2         | 2      | 1.56%   |
| WDC WD1600BB-00GUC0 160GB           | 2         | 2      | 1.56%   |
| WDC WD Green 2.5 240GB SSD          | 2         | 4      | 1.56%   |
| Toshiba MQ01ABD075 752GB            | 2         | 3      | 1.56%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 1.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 1.56%   |
| Seagate ST31000528AS 1TB            | 2         | 2      | 1.56%   |
| Kingston SKC400S371T 1024GB SSD     | 2         | 13     | 1.56%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 4      | 1.56%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 3      | 1.56%   |
| JMicron Technology Generic 500GB    | 2         | 2      | 1.56%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 3      | 1.56%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 3      | 1.56%   |
| Hitachi HTS545050A7E380 500GB       | 2         | 2      | 1.56%   |
| HGST HTS541010B7E610 1TB            | 2         | 3      | 1.56%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 1.56%   |
| XrayDisk SSD 256GB                  | 1         | 1      | 0.78%   |
| XPG SPECTRIX S40G 1TB               | 1         | 2      | 0.78%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 0.78%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD    | 1         | 1      | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 0.78%   |
| WDC WD5000LPLX-60ZNTT1 500GB        | 1         | 1      | 0.78%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 0.78%   |
| WDC WD5000AAKX-083CA1 500GB         | 1         | 1      | 0.78%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 2      | 0.78%   |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 0.78%   |
| WDC WD20EARX-00PASB0 2TB            | 1         | 1      | 0.78%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 1      | 0.78%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 0.78%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 0.78%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 0.78%   |
| WDC WD10EARS-003BB1 1TB             | 1         | 1      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 33     | 20.8%   |
| WDC                 | 24        | 28     | 19.2%   |
| Hitachi             | 16        | 21     | 12.8%   |
| HGST                | 15        | 17     | 12%     |
| Toshiba             | 12        | 14     | 9.6%    |
| Kingston            | 11        | 26     | 8.8%    |
| Samsung Electronics | 3         | 5      | 2.4%    |
| China               | 3         | 4      | 2.4%    |
| SK hynix            | 2         | 2      | 1.6%    |
| JMicron Technology  | 2         | 2      | 1.6%    |
| Crucial             | 2         | 2      | 1.6%    |
| XrayDisk            | 1         | 1      | 0.8%    |
| XPG                 | 1         | 2      | 0.8%    |
| Vaseky              | 1         | 1      | 0.8%    |
| Maxtor              | 1         | 1      | 0.8%    |
| LITEON              | 1         | 1      | 0.8%    |
| Intel               | 1         | 2      | 0.8%    |
| Faspeed             | 1         | 1      | 0.8%    |
| Apple               | 1         | 2      | 0.8%    |
| A-DATA Technology   | 1         | 1      | 0.8%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 33     | 28.26%  |
| WDC                 | 17        | 18     | 18.48%  |
| Hitachi             | 16        | 21     | 17.39%  |
| HGST                | 15        | 17     | 16.3%   |
| Toshiba             | 12        | 14     | 13.04%  |
| Samsung Electronics | 2         | 4      | 2.17%   |
| JMicron Technology  | 2         | 2      | 2.17%   |
| Maxtor              | 1         | 1      | 1.09%   |
| Apple               | 1         | 2      | 1.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 112    | 70.94%  |
| SSD  | 30        | 49     | 25.64%  |
| NVMe | 4         | 5      | 3.42%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB  | 1         | 1      | 50%     |
| Seagate ST9320325AS 320GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 840       | 1524   | 60.39%  |
| Works    | 439       | 794    | 31.56%  |
| Malfunc  | 110       | 166    | 7.91%   |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 803       | 51.05%  |
| AMD                                  | 273       | 17.36%  |
| Samsung Electronics                  | 100       | 6.36%   |
| SanDisk                              | 93        | 5.91%   |
| Kingston Technology Company          | 60        | 3.81%   |
| SK hynix                             | 42        | 2.67%   |
| Micron Technology                    | 29        | 1.84%   |
| Silicon Motion                       | 21        | 1.34%   |
| Micron/Crucial Technology            | 21        | 1.34%   |
| KIOXIA                               | 17        | 1.08%   |
| Nvidia                               | 14        | 0.89%   |
| Phison Electronics                   | 11        | 0.7%    |
| Toshiba America Info Systems         | 9         | 0.57%   |
| Realtek Semiconductor                | 9         | 0.57%   |
| MAXIO Technology (Hangzhou)          | 9         | 0.57%   |
| JMicron Technology                   | 9         | 0.57%   |
| Marvell Technology Group             | 8         | 0.51%   |
| ASMedia Technology                   | 8         | 0.51%   |
| ADATA Technology                     | 8         | 0.51%   |
| Solid State Storage Technology       | 4         | 0.25%   |
| Silicon Integrated Systems [SiS]     | 4         | 0.25%   |
| O2 Micro                             | 4         | 0.25%   |
| Union Memory (Shenzhen)              | 3         | 0.19%   |
| Shenzhen Longsys Electronics         | 2         | 0.13%   |
| Lite-On Technology                   | 2         | 0.13%   |
| VIA Technologies                     | 1         | 0.06%   |
| Solidigm                             | 1         | 0.06%   |
| Seagate Technology                   | 1         | 0.06%   |
| Ramaxel Technology(Shenzhen) Limited | 1         | 0.06%   |
| Netac Technology                     | 1         | 0.06%   |
| Lenovo                               | 1         | 0.06%   |
| INNOGRIT                             | 1         | 0.06%   |
| Hosin Global Electronics             | 1         | 0.06%   |
| Broadcom / LSI                       | 1         | 0.06%   |
| Apple                                | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 194       | 10.94%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 99        | 5.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 63        | 3.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 59        | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 43        | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43        | 2.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 40        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 35        | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 33        | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 31        | 1.75%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 24        | 1.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 24        | 1.35%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 24        | 1.35%   |
| AMD 400 Series Chipset SATA Controller                                                  | 23        | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 22        | 1.24%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 20        | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 20        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 19        | 1.07%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 17        | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17        | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 17        | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 16        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 16        | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 16        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 16        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 16        | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 16        | 0.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 15        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 15        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 14        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 13        | 0.73%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 13        | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 12        | 0.68%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 12        | 0.68%   |
| Intel SATA Controller [RAID mode]                                                       | 12        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 12        | 0.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 899       | 56.54%  |
| NVMe | 438       | 27.55%  |
| IDE  | 128       | 8.05%   |
| RAID | 125       | 7.86%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 919       | 72.14%  |
| AMD     | 352       | 27.63%  |
| Unknown | 2         | 0.16%   |
| ARM     | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 25        | 1.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 1.17%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 12        | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.86%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 10        | 0.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.78%   |
| AMD Custom APU 0405                           | 10        | 0.78%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 9         | 0.7%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 9         | 0.7%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 8         | 0.62%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 8         | 0.62%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 8         | 0.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 0.62%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 8         | 0.62%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 0.54%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 0.54%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.54%   |
| Intel 13th Gen Core i9-13900H                 | 7         | 0.54%   |
| AMD Ryzen 7 7730U with Radeon Graphics        | 7         | 0.54%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 7         | 0.54%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.47%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 6         | 0.47%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.47%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 6         | 0.47%   |
| Intel Celeron N4500 @ 1.10GHz                 | 6         | 0.47%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 0.47%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 6         | 0.47%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.47%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 0.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 261       | 20.36%  |
| Intel Core i7           | 186       | 14.51%  |
| Intel Core i3           | 106       | 8.27%   |
| Other                   | 101       | 7.88%   |
| AMD Ryzen 5             | 88        | 6.86%   |
| Intel Celeron           | 80        | 6.24%   |
| AMD Ryzen 7             | 58        | 4.52%   |
| Intel Pentium           | 42        | 3.28%   |
| Intel Xeon              | 39        | 3.04%   |
| Intel Core 2 Duo        | 35        | 2.73%   |
| Intel Atom              | 27        | 2.11%   |
| AMD Ryzen 3             | 24        | 1.87%   |
| AMD A6                  | 18        | 1.4%    |
| AMD A10                 | 18        | 1.4%    |
| AMD FX                  | 15        | 1.17%   |
| Intel Pentium Dual-Core | 14        | 1.09%   |
| AMD Ryzen 9             | 13        | 1.01%   |
| AMD A8                  | 13        | 1.01%   |
| AMD E1                  | 12        | 0.94%   |
| AMD E                   | 12        | 0.94%   |
| Intel Pentium Dual      | 11        | 0.86%   |
| AMD A4                  | 9         | 0.7%    |
| AMD E2                  | 7         | 0.55%   |
| AMD Athlon              | 7         | 0.55%   |
| Intel Core i9           | 6         | 0.47%   |
| AMD Ryzen 5 PRO         | 6         | 0.47%   |
| Intel Pentium Silver    | 4         | 0.31%   |
| Intel Genuine           | 4         | 0.31%   |
| Intel Core 2 Quad       | 4         | 0.31%   |
| Intel Core 2            | 4         | 0.31%   |
| AMD Turion II Dual-Core | 4         | 0.31%   |
| AMD Ryzen 7 PRO         | 4         | 0.31%   |
| AMD A12                 | 4         | 0.31%   |
| Intel Celeron Dual-Core | 3         | 0.23%   |
| AMD Phenom II X4        | 3         | 0.23%   |
| AMD Phenom              | 3         | 0.23%   |
| AMD Athlon II X2        | 3         | 0.23%   |
| AMD Athlon II           | 3         | 0.23%   |
| Intel Pentium Gold      | 2         | 0.16%   |
| Intel Pentium 4         | 2         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 547       | 42.6%   |
| 4       | 460       | 35.83%  |
| 6       | 99        | 7.71%   |
| 8       | 87        | 6.78%   |
| 1       | 21        | 1.64%   |
| 12      | 18        | 1.4%    |
| 10      | 15        | 1.17%   |
| 14      | 13        | 1.01%   |
| 3       | 9         | 0.7%    |
| 16      | 6         | 0.47%   |
| Unknown | 6         | 0.47%   |
| 24      | 2         | 0.16%   |
| 20      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1266      | 99.37%  |
| 2       | 6         | 0.47%   |
| 4       | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 858       | 67.03%  |
| 1       | 416       | 32.5%   |
| Unknown | 6         | 0.47%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1245      | 97.57%  |
| Unknown        | 15        | 1.18%   |
| 64-bit         | 8         | 0.63%   |
| 32-bit         | 8         | 0.63%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 562       | 42.16%  |
| 0x206a7    | 48        | 3.6%    |
| 0x306a9    | 40        | 3%      |
| 0x406e3    | 31        | 2.33%   |
| 0x806e9    | 27        | 2.03%   |
| 0x1067a    | 27        | 2.03%   |
| 0x306c3    | 25        | 1.88%   |
| 0x806ec    | 24        | 1.8%    |
| 0x40651    | 23        | 1.73%   |
| 0x906ea    | 20        | 1.5%    |
| 0x30678    | 20        | 1.5%    |
| 0x08108109 | 20        | 1.5%    |
| 0x806c1    | 17        | 1.28%   |
| 0x906e9    | 16        | 1.2%    |
| 0x806ea    | 16        | 1.2%    |
| 0x6fd      | 16        | 1.2%    |
| 0x20655    | 15        | 1.13%   |
| 0x08108102 | 15        | 1.13%   |
| 0x406c4    | 14        | 1.05%   |
| 0x08701021 | 13        | 0.98%   |
| 0x0810100b | 13        | 0.98%   |
| 0xa0652    | 12        | 0.9%    |
| 0x05000119 | 12        | 0.9%    |
| 0x306d4    | 11        | 0.83%   |
| 0x0a50000c | 11        | 0.83%   |
| 0x06000852 | 10        | 0.75%   |
| 0x506c9    | 9         | 0.68%   |
| 0x10676    | 9         | 0.68%   |
| 0x08600106 | 9         | 0.68%   |
| 0x0700010f | 9         | 0.68%   |
| 0x010000c8 | 9         | 0.68%   |
| 0x706a8    | 8         | 0.6%    |
| 0x07030105 | 8         | 0.6%    |
| 0x806eb    | 7         | 0.53%   |
| 0x706e5    | 7         | 0.53%   |
| 0x506e3    | 7         | 0.53%   |
| 0x406c3    | 7         | 0.53%   |
| 0x08608103 | 7         | 0.53%   |
| 0x06001119 | 7         | 0.53%   |
| 0x03000027 | 7         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 224       | 17.47%  |
| Haswell           | 96        | 7.49%   |
| SandyBridge       | 77        | 6.01%   |
| IvyBridge         | 76        | 5.93%   |
| Unknown           | 68        | 5.3%    |
| Skylake           | 57        | 4.45%   |
| Zen+              | 54        | 4.21%   |
| Silvermont        | 53        | 4.13%   |
| Penryn            | 53        | 4.13%   |
| Zen 2             | 48        | 3.74%   |
| TigerLake         | 43        | 3.35%   |
| Zen 3             | 41        | 3.2%    |
| CometLake         | 31        | 2.42%   |
| Westmere          | 28        | 2.18%   |
| Core              | 28        | 2.18%   |
| Zen               | 27        | 2.11%   |
| Piledriver        | 27        | 2.11%   |
| Broadwell         | 25        | 1.95%   |
| K10               | 23        | 1.79%   |
| Excavator         | 23        | 1.79%   |
| Icelake           | 22        | 1.72%   |
| Goldmont plus     | 22        | 1.72%   |
| Alderlake Hybrid  | 22        | 1.72%   |
| Bobcat            | 21        | 1.64%   |
| Puma              | 14        | 1.09%   |
| Jaguar            | 13        | 1.01%   |
| Goldmont          | 13        | 1.01%   |
| Bonnell           | 12        | 0.94%   |
| K10 Llano         | 8         | 0.62%   |
| Steamroller       | 6         | 0.47%   |
| K8 Hammer         | 6         | 0.47%   |
| Tremont           | 4         | 0.31%   |
| P6                | 4         | 0.31%   |
| Nehalem           | 4         | 0.31%   |
| Bulldozer         | 4         | 0.31%   |
| NetBurst          | 2         | 0.16%   |
| Meteorlake Hybrid | 1         | 0.08%   |
| K8 & K10 hybrid   | 1         | 0.08%   |
| Gracemont         | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 771       | 51.33%  |
| AMD                              | 387       | 25.77%  |
| Nvidia                           | 334       | 22.24%  |
| Silicon Integrated Systems [SiS] | 4         | 0.27%   |
| Matrox Electronics Systems       | 3         | 0.2%    |
| ATI Technologies                 | 2         | 0.13%   |
| VIA Technologies                 | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 63        | 4.02%   |
| Intel HD Graphics 620                                                                    | 52        | 3.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 2.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 44        | 2.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 35        | 2.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 35        | 2.23%   |
| Intel UHD Graphics 620                                                                   | 31        | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 30        | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 27        | 1.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 1.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 24        | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 1.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 1.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 1.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 20        | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 19        | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 1.21%   |
| Intel HD Graphics 630                                                                    | 18        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 1.15%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17        | 1.09%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 1.02%   |
| AMD Lucienne                                                                             | 14        | 0.89%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 13        | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 0.83%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 12        | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.77%   |
| Intel HD Graphics 530                                                                    | 12        | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 12        | 0.77%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 11        | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.64%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 10        | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 575       | 44.89%  |
| 1 x AMD        | 287       | 22.4%   |
| Intel + Nvidia | 157       | 12.26%  |
| 1 x Nvidia     | 146       | 11.4%   |
| 2 x AMD        | 41        | 3.2%    |
| AMD + Nvidia   | 32        | 2.5%    |
| Intel + AMD    | 29        | 2.26%   |
| 1 x SiS        | 4         | 0.31%   |
| Other          | 3         | 0.23%   |
| 2 x Intel      | 3         | 0.23%   |
| 1 x Matrox     | 2         | 0.16%   |
| 1 x VIA        | 1         | 0.08%   |
| AMD + Matrox   | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1052      | 81.42%  |
| Proprietary | 183       | 14.16%  |
| Unknown     | 57        | 4.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 821       | 62.62%  |
| 1.01-2.0   | 141       | 10.76%  |
| 0.01-0.5   | 141       | 10.76%  |
| 0.51-1.0   | 84        | 6.41%   |
| 3.01-4.0   | 61        | 4.65%   |
| 7.01-8.0   | 19        | 1.45%   |
| 5.01-6.0   | 19        | 1.45%   |
| 8.01-16.0  | 14        | 1.07%   |
| 2.01-3.0   | 10        | 0.76%   |
| 4.01-5.0   | 1         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 221       | 15.39%  |
| AU Optronics            | 194       | 13.51%  |
| BOE                     | 178       | 12.4%   |
| Chimei Innolux          | 173       | 12.05%  |
| LG Display              | 107       | 7.45%   |
| Goldstar                | 101       | 7.03%   |
| Hewlett-Packard         | 49        | 3.41%   |
| Dell                    | 34        | 2.37%   |
| AOC                     | 32        | 2.23%   |
| Lenovo                  | 31        | 2.16%   |
| ViewSonic               | 25        | 1.74%   |
| Apple                   | 22        | 1.53%   |
| PANDA                   | 16        | 1.11%   |
| Sony                    | 14        | 0.97%   |
| Sharp                   | 14        | 0.97%   |
| Unknown                 | 13        | 0.91%   |
| LG Electronics          | 12        | 0.84%   |
| ASUSTek Computer        | 12        | 0.84%   |
| SAC                     | 11        | 0.77%   |
| CSO                     | 11        | 0.77%   |
| Chi Mei Optoelectronics | 11        | 0.77%   |
| MSI                     | 10        | 0.7%    |
| Envision                | 10        | 0.7%    |
| Acer                    | 10        | 0.7%    |
| Valve                   | 9         | 0.63%   |
| InfoVision              | 9         | 0.63%   |
| HKC                     | 7         | 0.49%   |
| ___                     | 6         | 0.42%   |
| LG Philips              | 6         | 0.42%   |
| KTC                     | 6         | 0.42%   |
| Ancor Communications    | 6         | 0.42%   |
| Unknown (XXX)           | 5         | 0.35%   |
| Plain Tree Systems      | 4         | 0.28%   |
| Philips                 | 4         | 0.28%   |
| Packard Bell            | 4         | 0.28%   |
| Hitachi                 | 4         | 0.28%   |
| SLD                     | 3         | 0.21%   |
| RGT                     | 3         | 0.21%   |
| Mi                      | 3         | 0.21%   |
| InnoLux Display         | 3         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 12        | 0.81%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch              | 12        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 12        | 0.81%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 12        | 0.81%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 12        | 0.81%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 11        | 0.74%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 10        | 0.68%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 9         | 0.61%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 9         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 9         | 0.61%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 8         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 8         | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 8         | 0.54%   |
| SAC LED MONITOR SAC952D 1920x1080 443x249mm 20.0-inch                 | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 7         | 0.47%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 7         | 0.47%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 7         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 6         | 0.41%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 6         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 6         | 0.41%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 6         | 0.41%   |
| BOE LCD Monitor BOE0602 1366x768 344x193mm 15.5-inch                  | 6         | 0.41%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 5         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 5         | 0.34%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.34%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                  | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 5         | 0.34%   |
| ___ LCD TV ___9000 1360x768                                           | 4         | 0.27%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 4         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 513       | 37.45%  |
| 1366x768 (WXGA)    | 434       | 31.68%  |
| 3840x2160 (4K)     | 64        | 4.67%   |
| 1600x900 (HD+)     | 46        | 3.36%   |
| 1360x768           | 39        | 2.85%   |
| 1920x1200 (WUXGA)  | 34        | 2.48%   |
| 1280x800 (WXGA)    | 30        | 2.19%   |
| 1440x900 (WXGA+)   | 28        | 2.04%   |
| 2560x1440 (QHD)    | 27        | 1.97%   |
| 2560x1080          | 19        | 1.39%   |
| 1680x1050 (WSXGA+) | 19        | 1.39%   |
| 1280x1024 (SXGA)   | 19        | 1.39%   |
| 800x1280           | 10        | 0.73%   |
| 2880x1800          | 10        | 0.73%   |
| 2560x1600          | 10        | 0.73%   |
| 3440x1440          | 9         | 0.66%   |
| Unknown            | 8         | 0.58%   |
| 3840x1080          | 6         | 0.44%   |
| 1024x768 (XGA)     | 5         | 0.36%   |
| 1024x600           | 5         | 0.36%   |
| 3840x2400          | 4         | 0.29%   |
| 2160x1440          | 4         | 0.29%   |
| 3840x1100          | 3         | 0.22%   |
| 3000x2000          | 3         | 0.22%   |
| 2288x1287          | 3         | 0.22%   |
| 1920x540           | 3         | 0.22%   |
| 3286x1080          | 2         | 0.15%   |
| 1024x576           | 2         | 0.15%   |
| 5760x1080          | 1         | 0.07%   |
| 5440x1800          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1600x2560          | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |
| 1280x960           | 1         | 0.07%   |
| 1280x768           | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 329       | 22.77%  |
| 13      | 221       | 15.29%  |
| 14      | 207       | 14.33%  |
| 23      | 96        | 6.64%   |
| 21      | 79        | 5.47%   |
| 24      | 51        | 3.53%   |
| 27      | 48        | 3.32%   |
| 31      | 47        | 3.25%   |
| Unknown | 41        | 2.84%   |
| 18      | 36        | 2.49%   |
| 19      | 32        | 2.21%   |
| 17      | 32        | 2.21%   |
| 16      | 28        | 1.94%   |
| 34      | 27        | 1.87%   |
| 20      | 22        | 1.52%   |
| 12      | 21        | 1.45%   |
| 11      | 20        | 1.38%   |
| 84      | 12        | 0.83%   |
| 72      | 12        | 0.83%   |
| 32      | 11        | 0.76%   |
| 22      | 11        | 0.76%   |
| 10      | 10        | 0.69%   |
| 7       | 9         | 0.62%   |
| 54      | 8         | 0.55%   |
| 48      | 5         | 0.35%   |
| 40      | 5         | 0.35%   |
| 58      | 4         | 0.28%   |
| 142     | 3         | 0.21%   |
| 46      | 3         | 0.21%   |
| 28      | 3         | 0.21%   |
| 49      | 2         | 0.14%   |
| 37      | 2         | 0.14%   |
| 26      | 2         | 0.14%   |
| 86      | 1         | 0.07%   |
| 65      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 3       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 713       | 50.11%  |
| 501-600        | 177       | 12.44%  |
| 401-500        | 163       | 11.45%  |
| 201-300        | 117       | 8.22%   |
| 601-700        | 59        | 4.15%   |
| 351-400        | 44        | 3.09%   |
| Unknown        | 41        | 2.88%   |
| 701-800        | 38        | 2.67%   |
| 1001-1500      | 25        | 1.76%   |
| 1501-2000      | 24        | 1.69%   |
| 1-100          | 10        | 0.7%    |
| 801-900        | 7         | 0.49%   |
| More than 2000 | 3         | 0.21%   |
| 901-1000       | 2         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1000      | 79.55%  |
| 16/10   | 136       | 10.82%  |
| Unknown | 30        | 2.39%   |
| 21/9    | 28        | 2.23%   |
| 5/4     | 20        | 1.59%   |
| 4/3     | 10        | 0.8%    |
| 3/2     | 9         | 0.72%   |
| 0.67    | 9         | 0.72%   |
| 32/9    | 3         | 0.24%   |
| 3.40    | 3         | 0.24%   |
| 1.00    | 3         | 0.24%   |
| 6/5     | 2         | 0.16%   |
| 1.96    | 2         | 0.16%   |
| 3.73    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 371       | 25.93%  |
| 101-110        | 332       | 23.2%   |
| 201-250        | 191       | 13.35%  |
| 351-500        | 86        | 6.01%   |
| 151-200        | 76        | 5.31%   |
| 71-80          | 53        | 3.7%    |
| 301-350        | 49        | 3.42%   |
| More than 1000 | 43        | 3%      |
| 141-150        | 42        | 2.94%   |
| Unknown        | 41        | 2.87%   |
| 111-120        | 25        | 1.75%   |
| 51-60          | 23        | 1.61%   |
| 61-70          | 18        | 1.26%   |
| 501-1000       | 17        | 1.19%   |
| 251-300        | 16        | 1.12%   |
| 121-130        | 16        | 1.12%   |
| 41-50          | 10        | 0.7%    |
| 1-40           | 10        | 0.7%    |
| 131-140        | 7         | 0.49%   |
| 91-100         | 5         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 498       | 35.72%  |
| 51-100        | 361       | 25.9%   |
| 121-160       | 332       | 23.82%  |
| 161-240       | 81        | 5.81%   |
| 1-50          | 58        | 4.16%   |
| Unknown       | 41        | 2.94%   |
| More than 240 | 23        | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1000      | 75.99%  |
| 2     | 243       | 18.47%  |
| 0     | 47        | 3.57%   |
| 3     | 25        | 1.9%    |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 815       | 41.77%  |
| Intel                            | 499       | 25.58%  |
| Qualcomm Atheros                 | 220       | 11.28%  |
| Broadcom                         | 111       | 5.69%   |
| MediaTek                         | 39        | 2%      |
| Ralink                           | 34        | 1.74%   |
| Broadcom Limited                 | 26        | 1.33%   |
| TP-Link                          | 25        | 1.28%   |
| Ralink Technology                | 24        | 1.23%   |
| Xiaomi                           | 22        | 1.13%   |
| Marvell Technology Group         | 16        | 0.82%   |
| Huawei Technologies              | 16        | 0.82%   |
| Samsung Electronics              | 15        | 0.77%   |
| Nvidia                           | 11        | 0.56%   |
| Qualcomm Atheros Communications  | 8         | 0.41%   |
| D-Link System                    | 7         | 0.36%   |
| D-Link                           | 7         | 0.36%   |
| ASIX Electronics                 | 7         | 0.36%   |
| Microsoft                        | 5         | 0.26%   |
| ICS Advent                       | 5         | 0.26%   |
| Silicon Integrated Systems [SiS] | 4         | 0.21%   |
| Motorola PCS                     | 4         | 0.21%   |
| JMicron Technology               | 4         | 0.21%   |
| Lenovo                           | 3         | 0.15%   |
| DisplayLink                      | 3         | 0.15%   |
| VIA Technologies                 | 2         | 0.1%    |
| Qualcomm                         | 2         | 0.1%    |
| Spreadtrum Communications        | 1         | 0.05%   |
| QinHeng Electronics              | 1         | 0.05%   |
| Qcom                             | 1         | 0.05%   |
| Padix (Rockfire)                 | 1         | 0.05%   |
| Oculus VR                        | 1         | 0.05%   |
| Netchip Technology               | 1         | 0.05%   |
| Microchip Technology             | 1         | 0.05%   |
| Mercucys                         | 1         | 0.05%   |
| Manta                            | 1         | 0.05%   |
| Linksys                          | 1         | 0.05%   |
| HMD Global                       | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Bose                             | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 507       | 21.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 143       | 6.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 48        | 2.07%   |
| Intel Wi-Fi 6 AX200                                                    | 45        | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 43        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 42        | 1.81%   |
| Intel Wireless 8265 / 8275                                             | 42        | 1.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 39        | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 38        | 1.64%   |
| Intel Wi-Fi 6 AX201                                                    | 33        | 1.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 32        | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 30        | 1.29%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 27        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 26        | 1.12%   |
| Intel Wireless 7265                                                    | 24        | 1.03%   |
| Intel Wireless 7260                                                    | 24        | 1.03%   |
| Intel Wireless 8260                                                    | 23        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                          | 23        | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 23        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 19        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 18        | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 17        | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 16        | 0.69%   |
| Realtek 802.11ac NIC                                                   | 16        | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                   | 15        | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 15        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 14        | 0.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 14        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                        | 13        | 0.56%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 13        | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.56%   |
| Huawei FOA-LX9                                                         | 13        | 0.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 12        | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 12        | 0.52%   |
| Intel Wireless 3165                                                    | 12        | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 434       | 38.1%   |
| Realtek Semiconductor           | 271       | 23.79%  |
| Qualcomm Atheros                | 187       | 16.42%  |
| Broadcom                        | 88        | 7.73%   |
| Ralink                          | 34        | 2.99%   |
| MediaTek                        | 31        | 2.72%   |
| Ralink Technology               | 24        | 2.11%   |
| TP-Link                         | 23        | 2.02%   |
| Broadcom Limited                | 18        | 1.58%   |
| Qualcomm Atheros Communications | 8         | 0.7%    |
| D-Link                          | 6         | 0.53%   |
| Microsoft                       | 5         | 0.44%   |
| D-Link System                   | 4         | 0.35%   |
| Qualcomm                        | 2         | 0.18%   |
| Qcom                            | 1         | 0.09%   |
| Mercucys                        | 1         | 0.09%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| ASUSTek Computer                | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 48        | 4.19%   |
| Intel Wi-Fi 6 AX200                                                     | 45        | 3.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 43        | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 42        | 3.66%   |
| Intel Wireless 8265 / 8275                                              | 42        | 3.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 39        | 3.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 38        | 3.32%   |
| Intel Wi-Fi 6 AX201                                                     | 33        | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 32        | 2.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 30        | 2.62%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 27        | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 2.27%   |
| Intel Wireless 7265                                                     | 24        | 2.09%   |
| Intel Wireless 7260                                                     | 24        | 2.09%   |
| Intel Wireless 8260                                                     | 23        | 2.01%   |
| Broadcom BCM43142 802.11b/g/n                                           | 23        | 2.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 23        | 2.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 19        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 19        | 1.66%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 17        | 1.48%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 1.4%    |
| Realtek 802.11ac NIC                                                    | 16        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.22%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 1.13%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 13        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 1.05%   |
| Intel Wireless 3165                                                     | 12        | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 11        | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.79%   |
| Intel Wireless 3160                                                     | 8         | 0.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 8         | 0.7%    |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 8         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 714       | 62.3%   |
| Intel                            | 202       | 17.63%  |
| Qualcomm Atheros                 | 51        | 4.45%   |
| Broadcom                         | 42        | 3.66%   |
| Xiaomi                           | 22        | 1.92%   |
| Marvell Technology Group         | 16        | 1.4%    |
| Huawei Technologies              | 16        | 1.4%    |
| Samsung Electronics              | 11        | 0.96%   |
| Nvidia                           | 11        | 0.96%   |
| MediaTek                         | 8         | 0.7%    |
| Broadcom Limited                 | 8         | 0.7%    |
| ASIX Electronics                 | 7         | 0.61%   |
| ICS Advent                       | 5         | 0.44%   |
| Silicon Integrated Systems [SiS] | 4         | 0.35%   |
| Motorola PCS                     | 4         | 0.35%   |
| JMicron Technology               | 4         | 0.35%   |
| Lenovo                           | 3         | 0.26%   |
| DisplayLink                      | 3         | 0.26%   |
| D-Link System                    | 3         | 0.26%   |
| VIA Technologies                 | 2         | 0.17%   |
| TP-Link                          | 2         | 0.17%   |
| Spreadtrum Communications        | 1         | 0.09%   |
| Netchip Technology               | 1         | 0.09%   |
| Microchip Technology             | 1         | 0.09%   |
| Linksys                          | 1         | 0.09%   |
| HMD Global                       | 1         | 0.09%   |
| D-Link                           | 1         | 0.09%   |
| Aquantia                         | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 507       | 43.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 143       | 12.32%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 1.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 19        | 1.64%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 18        | 1.55%   |
| Intel Ethernet Connection (4) I219-V                                   | 15        | 1.29%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 1.12%   |
| Huawei FOA-LX9                                                         | 13        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 1.03%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.95%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 0.86%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 9         | 0.78%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.69%   |
| Intel Ethernet Connection (7) I219-V                                   | 8         | 0.69%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.52%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.52%   |
| Intel Ethernet Connection (13) I219-V                                  | 6         | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 6         | 0.52%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.43%   |
| Nvidia MCP61 Ethernet                                                  | 5         | 0.43%   |
| MediaTek Infinix SMART 5                                               | 5         | 0.43%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.43%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 0.43%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                  | 5         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.34%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 4         | 0.34%   |
| Intel Ethernet Connection (10) I219-LM                                 | 4         | 0.34%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1079      | 49.82%  |
| Ethernet | 1074      | 49.58%  |
| Modem    | 9         | 0.42%   |
| Unknown  | 4         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 840       | 63.21%  |
| Ethernet | 489       | 36.79%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 768       | 59.77%  |
| 1     | 470       | 36.58%  |
| 3     | 25        | 1.95%   |
| 0     | 18        | 1.4%    |
| 4     | 3         | 0.23%   |
| 6     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1098      | 84.66%  |
| Yes  | 199       | 15.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 376       | 41.09%  |
| Realtek Semiconductor           | 166       | 18.14%  |
| Qualcomm Atheros Communications | 63        | 6.89%   |
| IMC Networks                    | 56        | 6.12%   |
| Broadcom                        | 52        | 5.68%   |
| Lite-On Technology              | 44        | 4.81%   |
| Cambridge Silicon Radio         | 37        | 4.04%   |
| Foxconn / Hon Hai               | 30        | 3.28%   |
| Apple                           | 29        | 3.17%   |
| Ralink                          | 12        | 1.31%   |
| Dell                            | 8         | 0.87%   |
| Realtek                         | 7         | 0.77%   |
| Hewlett-Packard                 | 7         | 0.77%   |
| Toshiba                         | 5         | 0.55%   |
| Ralink Technology               | 4         | 0.44%   |
| ASUSTek Computer                | 4         | 0.44%   |
| Foxconn International           | 3         | 0.33%   |
| USI                             | 2         | 0.22%   |
| MediaTek                        | 2         | 0.22%   |
| Alps Electric                   | 2         | 0.22%   |
| Actions                         | 2         | 0.22%   |
| Unknown                         | 2         | 0.22%   |
| SINO WEALTH                     | 1         | 0.11%   |
| Integrated System Solution      | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 132       | 14.41%  |
| Realtek Bluetooth Radio                             | 82        | 8.95%   |
| Intel AX201 Bluetooth                               | 81        | 8.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 57        | 6.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 53        | 5.79%   |
| Intel AX200 Bluetooth                               | 45        | 4.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 37        | 4.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 3.06%   |
| IMC Networks Bluetooth Radio                        | 24        | 2.62%   |
| IMC Networks Wireless_Device                        | 18        | 1.97%   |
| Intel AX210 Bluetooth                               | 17        | 1.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.53%   |
| Apple Bluetooth USB Host Controller                 | 13        | 1.42%   |
| Apple Bluetooth Host Controller                     | 13        | 1.42%   |
| Ralink RT3290 Bluetooth                             | 12        | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.31%   |
| Realtek RTL8821A Bluetooth                          | 11        | 1.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 1.2%    |
| Intel AX211 Bluetooth                               | 11        | 1.2%    |
| IMC Networks Bluetooth Device                       | 11        | 1.2%    |
| Realtek 802.11ac WLAN Adapter                       | 10        | 1.09%   |
| Lite-On Bluetooth Device                            | 10        | 1.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 1.09%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 10        | 1.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 9         | 0.98%   |
| Realtek Bluetooth Radio                             | 7         | 0.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.76%   |
| Broadcom Bluetooth 3.0 Dongle                       | 7         | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.66%   |
| Toshiba Bluetooth Device                            | 5         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.55%   |
| Qualcomm Atheros Bluetooth                          | 5         | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 0.55%   |
| Broadcom BCM43142A0 Bluetooth Device                | 5         | 0.55%   |
| Broadcom BCM2070 Bluetooth Device                   | 5         | 0.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.55%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 4         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 888       | 53.3%   |
| AMD                                          | 395       | 23.71%  |
| Nvidia                                       | 225       | 13.51%  |
| Logitech                                     | 20        | 1.2%    |
| C-Media Electronics                          | 19        | 1.14%   |
| Kingston Technology                          | 9         | 0.54%   |
| JMTek                                        | 8         | 0.48%   |
| Creative Labs                                | 8         | 0.48%   |
| Generalplus Technology                       | 7         | 0.42%   |
| Creative Technology                          | 7         | 0.42%   |
| Texas Instruments                            | 5         | 0.3%    |
| Razer USA                                    | 5         | 0.3%    |
| Focusrite-Novation                           | 5         | 0.3%    |
| Silicon Integrated Systems [SiS]             | 4         | 0.24%   |
| Realtek Semiconductor                        | 4         | 0.24%   |
| Apple                                        | 4         | 0.24%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.18%   |
| Trust                                        | 3         | 0.18%   |
| Microsoft                                    | 3         | 0.18%   |
| Lenovo                                       | 3         | 0.18%   |
| Corsair                                      | 3         | 0.18%   |
| ASUSTek Computer                             | 3         | 0.18%   |
| VIA Technologies                             | 2         | 0.12%   |
| SAVITECH                                     | 2         | 0.12%   |
| Plantronics                                  | 2         | 0.12%   |
| KTMicro                                      | 2         | 0.12%   |
| GN Netcom                                    | 2         | 0.12%   |
| FIFINE Microphones                           | 2         | 0.12%   |
| Arturia                                      | 2         | 0.12%   |
| Unknown                                      | 1         | 0.06%   |
| Synaptics                                    | 1         | 0.06%   |
| Shenzhen Riitek Technology                   | 1         | 0.06%   |
| PreSonus Audio Electronics                   | 1         | 0.06%   |
| Pixart Imaging                               | 1         | 0.06%   |
| Native Instruments                           | 1         | 0.06%   |
| Micro Star International                     | 1         | 0.06%   |
| Medeli Electronics                           | 1         | 0.06%   |
| Huawei Technologies                          | 1         | 0.06%   |
| Hewlett-Packard                              | 1         | 0.06%   |
| GYROCOM C&C                                  | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 149       | 7.34%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 131       | 6.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 79        | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 64        | 3.15%   |
| AMD FCH Azalia Controller                                                                         | 64        | 3.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 60        | 2.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 54        | 2.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 51        | 2.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 47        | 2.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 43        | 2.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 38        | 1.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 37        | 1.82%   |
| AMD Kabini HDMI/DP Audio                                                                          | 37        | 1.82%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 36        | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 35        | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 34        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 31        | 1.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 28        | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 28        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 25        | 1.23%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 1.13%   |
| Intel Comet Lake PCH cAVS                                                                         | 22        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22        | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 21        | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 21        | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 0.94%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 19        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 17        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 16        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 14        | 0.69%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 14        | 0.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 13        | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 190       | 24.27%  |
| SK hynix            | 138       | 17.62%  |
| Kingston            | 102       | 13.03%  |
| Micron Technology   | 90        | 11.49%  |
| Crucial             | 88        | 11.24%  |
| Unknown             | 41        | 5.24%   |
| Ramaxel Technology  | 25        | 3.19%   |
| Corsair             | 24        | 3.07%   |
| A-DATA Technology   | 18        | 2.3%    |
| G.Skill             | 11        | 1.4%    |
| Avant               | 8         | 1.02%   |
| Unknown             | 7         | 0.89%   |
| Unknown (ABCD)      | 6         | 0.77%   |
| Elpida              | 4         | 0.51%   |
| Patriot             | 3         | 0.38%   |
| Nanya Technology    | 3         | 0.38%   |
| Kreton              | 2         | 0.26%   |
| Kllisre             | 2         | 0.26%   |
| Hikvision           | 2         | 0.26%   |
| Atermiter           | 2         | 0.26%   |
| Unknown (C289)      | 1         | 0.13%   |
| Unknown (0x0E9D)    | 1         | 0.13%   |
| Unknown (0x0080)    | 1         | 0.13%   |
| Unknown (0BF7)      | 1         | 0.13%   |
| Unknown (090E)      | 1         | 0.13%   |
| Unknown (08C8)      | 1         | 0.13%   |
| Team                | 1         | 0.13%   |
| Smart               | 1         | 0.13%   |
| PNY                 | 1         | 0.13%   |
| Lexar               | 1         | 0.13%   |
| KingSpec            | 1         | 0.13%   |
| Goldenmars          | 1         | 0.13%   |
| GLOWAY              | 1         | 0.13%   |
| ASint Technology    | 1         | 0.13%   |
| Apacer              | 1         | 0.13%   |
| Ankowall            | 1         | 0.13%   |
| 48spaces            | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 1.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 1.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.96%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 7         | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.84%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 7         | 0.84%   |
| Unknown                                                          | 7         | 0.84%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.72%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 0.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.72%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.72%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 5         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.6%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.6%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.6%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 5         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.6%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.6%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 4         | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.48%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.48%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 4         | 0.48%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 0.48%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.48%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 4         | 0.48%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8GB SODIMM DDR4 3200MT/s          | 4         | 0.48%   |
| Crucial RAM CT8G4SFRA32A.M4FF 8GB SODIMM DDR4 3200MT/s           | 4         | 0.48%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 4         | 0.48%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 321       | 52.62%  |
| DDR3    | 191       | 31.31%  |
| LPDDR4  | 26        | 4.26%   |
| DDR2    | 18        | 2.95%   |
| SDRAM   | 15        | 2.46%   |
| LPDDR3  | 14        | 2.3%    |
| DDR5    | 10        | 1.64%   |
| LPDDR5  | 8         | 1.31%   |
| Unknown | 3         | 0.49%   |
| DDR     | 2         | 0.33%   |
| RAM     | 1         | 0.16%   |
| DRAM    | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 415       | 68.48%  |
| DIMM         | 141       | 23.27%  |
| Row Of Chips | 47        | 7.76%   |
| Chip         | 2         | 0.33%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 298       | 42.63%  |
| 4096  | 215       | 30.76%  |
| 16384 | 91        | 13.02%  |
| 2048  | 64        | 9.16%   |
| 32768 | 22        | 3.15%   |
| 1024  | 8         | 1.14%   |
| 64    | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 135       | 19.18%  |
| 3200    | 128       | 18.18%  |
| 2667    | 117       | 16.62%  |
| 2400    | 60        | 8.52%   |
| 2133    | 40        | 5.68%   |
| 1333    | 36        | 5.11%   |
| 1334    | 18        | 2.56%   |
| Unknown | 17        | 2.41%   |
| 4267    | 13        | 1.85%   |
| 3600    | 13        | 1.85%   |
| 3266    | 12        | 1.7%    |
| 667     | 12        | 1.7%    |
| 800     | 9         | 1.28%   |
| 3466    | 7         | 0.99%   |
| 2666    | 7         | 0.99%   |
| 6400    | 5         | 0.71%   |
| 5600    | 5         | 0.71%   |
| 3733    | 5         | 0.71%   |
| 2933    | 5         | 0.71%   |
| 1867    | 5         | 0.71%   |
| 1067    | 5         | 0.71%   |
| 4199    | 4         | 0.57%   |
| 3000    | 4         | 0.57%   |
| 1866    | 4         | 0.57%   |
| 7500    | 3         | 0.43%   |
| 4800    | 3         | 0.43%   |
| 4266    | 3         | 0.43%   |
| 3800    | 3         | 0.43%   |
| 3400    | 3         | 0.43%   |
| 2048    | 3         | 0.43%   |
| 1066    | 3         | 0.43%   |
| 4000    | 2         | 0.28%   |
| 3666    | 2         | 0.28%   |
| 975     | 2         | 0.28%   |
| 8600    | 1         | 0.14%   |
| 8400    | 1         | 0.14%   |
| 5200    | 1         | 0.14%   |
| 3134    | 1         | 0.14%   |
| 3066    | 1         | 0.14%   |
| 2800    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 31.25%  |
| Canon               | 7         | 21.88%  |
| Brother Industries  | 7         | 21.88%  |
| Seiko Epson         | 6         | 18.75%  |
| QUIN                | 1         | 3.13%   |
| QinHeng Electronics | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Brother HL-1200 series     | 4         | 12.5%   |
| Canon MF110/910 Series     | 3         | 9.38%   |
| Brother DCP-1600           | 2         | 6.25%   |
| Seiko Epson XP-2100 Series | 1         | 3.13%   |
| Seiko Epson Printer        | 1         | 3.13%   |
| Seiko Epson L355 Series    | 1         | 3.13%   |
| Seiko Epson L3150 Series   | 1         | 3.13%   |
| Seiko Epson L3110 Series   | 1         | 3.13%   |
| Seiko Epson L210 Series    | 1         | 3.13%   |
| QUIN Label Printer         | 1         | 3.13%   |
| QinHeng CH340S             | 1         | 3.13%   |
| HP Smart Tank 510 series   | 1         | 3.13%   |
| HP Smart Tank 500 series   | 1         | 3.13%   |
| HP Officejet 4500 G510a-f  | 1         | 3.13%   |
| HP LaserJet P1005          | 1         | 3.13%   |
| HP Ink Tank 310 series     | 1         | 3.13%   |
| HP DeskJet 5820 series     | 1         | 3.13%   |
| HP Deskjet 4640 series     | 1         | 3.13%   |
| HP Deskjet 4620 series     | 1         | 3.13%   |
| HP DeskJet 2130 series     | 1         | 3.13%   |
| HP Deskjet 2050 J510       | 1         | 3.13%   |
| Canon PIXMA MP250          | 1         | 3.13%   |
| Canon LBP6000              | 1         | 3.13%   |
| Canon G2000 series         | 1         | 3.13%   |
| Canon G1000 series         | 1         | 3.13%   |
| Brother HL-1210W series    | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]   | 1         | 25%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 25%     |
| Canon CanoScan LiDE 110                       | 1         | 25%     |
| Canon CanoScan D1250U2                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 213       | 22.49%  |
| IMC Networks                           | 122       | 12.88%  |
| Realtek Semiconductor                  | 66        | 6.97%   |
| Microdia                               | 61        | 6.44%   |
| Cheng Uei Precision Industry (Foxlink) | 54        | 5.7%    |
| Quanta                                 | 51        | 5.39%   |
| Sunplus Innovation Technology          | 49        | 5.17%   |
| Bison Electronics                      | 44        | 4.65%   |
| Lite-On Technology                     | 29        | 3.06%   |
| Suyin                                  | 28        | 2.96%   |
| Apple                                  | 23        | 2.43%   |
| Syntek                                 | 21        | 2.22%   |
| Silicon Motion                         | 21        | 2.22%   |
| Luxvisions Innotech Limited            | 21        | 2.22%   |
| Logitech                               | 21        | 2.22%   |
| Generalplus Technology                 | 11        | 1.16%   |
| Ricoh                                  | 7         | 0.74%   |
| Microsoft                              | 7         | 0.74%   |
| Lenovo                                 | 7         | 0.74%   |
| Alcor Micro                            | 7         | 0.74%   |
| Z-Star Microelectronics                | 6         | 0.63%   |
| ShineTech                              | 6         | 0.63%   |
| Acer                                   | 6         | 0.63%   |
| Samsung Electronics                    | 5         | 0.53%   |
| Jieli Technology                       | 5         | 0.53%   |
| Sonix Technology                       | 4         | 0.42%   |
| Importek                               | 4         | 0.42%   |
| YGTek                                  | 3         | 0.32%   |
| USB Camera CS                          | 3         | 0.32%   |
| SunplusIT                              | 3         | 0.32%   |
| KYE Systems (Mouse Systems)            | 3         | 0.32%   |
| Unknown                                | 2         | 0.21%   |
| SN0002                                 | 2         | 0.21%   |
| OmniVision Technologies                | 2         | 0.21%   |
| Leap Motion                            | 2         | 0.21%   |
| Huawei Technologies                    | 2         | 0.21%   |
| GEMBIRD                                | 2         | 0.21%   |
| Foxconn / Hon Hai                      | 2         | 0.21%   |
| DigiTech                               | 2         | 0.21%   |
| ARC International                      | 2         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 50        | 5.24%   |
| Chicony Integrated Camera                                       | 34        | 3.56%   |
| IMC Networks Integrated Camera                                  | 30        | 3.14%   |
| Microdia Integrated_Webcam_HD                                   | 17        | 1.78%   |
| Syntek Integrated Camera                                        | 14        | 1.47%   |
| Chicony HP Wide Vision HD Camera                                | 14        | 1.47%   |
| Realtek Integrated_Webcam_HD                                    | 13        | 1.36%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 13        | 1.36%   |
| Chicony HD WebCam                                               | 13        | 1.36%   |
| Bison Integrated Camera                                         | 13        | 1.36%   |
| Lite-On Integrated Camera                                       | 12        | 1.26%   |
| Sunplus Integrated_Webcam_HD                                    | 11        | 1.15%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.15%   |
| Generalplus GENERAL WEBCAM                                      | 11        | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 11        | 1.15%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 10        | 1.05%   |
| Chicony HP Webcam                                               | 10        | 1.05%   |
| Chicony HP Truevision HD camera                                 | 10        | 1.05%   |
| Chicony HP Truevision HD                                        | 10        | 1.05%   |
| Chicony HD User Facing                                          | 10        | 1.05%   |
| Realtek HP Truevision HD                                        | 9         | 0.94%   |
| Chicony EasyCamera                                              | 9         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 9         | 0.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 9         | 0.94%   |
| Suyin HP TrueVision HD                                          | 8         | 0.84%   |
| Realtek USB Camera                                              | 8         | 0.84%   |
| Microdia Webcam Vitade AF                                       | 8         | 0.84%   |
| Chicony VGA WebCam                                              | 8         | 0.84%   |
| Sunplus HP TrueVision HD Camera                                 | 7         | 0.73%   |
| Quanta HD User Facing                                           | 7         | 0.73%   |
| Luxvisions Innotech Limited Integrated Camera                   | 7         | 0.73%   |
| Lite-On HP Wide Vision HD Camera                                | 7         | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD         | 7         | 0.73%   |
| Bison EasyCamera                                                | 7         | 0.73%   |
| Quanta VGA WebCam                                               | 6         | 0.63%   |
| Quanta USB2.0 HD UVC WebCam                                     | 6         | 0.63%   |
| Quanta HP Wide Vision HD Camera                                 | 6         | 0.63%   |
| Chicony HP HD Camera                                            | 6         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 6         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 6         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 48        | 35.29%  |
| Synaptics                  | 39        | 28.68%  |
| Shenzhen Goodix Technology | 15        | 11.03%  |
| Elan Microelectronics      | 12        | 8.82%   |
| Upek                       | 7         | 5.15%   |
| AuthenTec                  | 7         | 5.15%   |
| LighTuning Technology      | 4         | 2.94%   |
| STMicroelectronics         | 2         | 1.47%   |
| Focal-systems.Corp         | 2         | 1.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 9.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 8.82%   |
| Elan ELAN:ARM-M4                                                           | 10        | 7.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 5.88%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 5.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 5.15%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 5.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.68%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.68%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.94%   |
| Synaptics  WBDI                                                            | 4         | 2.94%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.94%   |
| AuthenTec AES2810                                                          | 4         | 2.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.47%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.47%   |
| Synaptics UWP WBDI                                                         | 2         | 1.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.47%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.47%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.47%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 1.47%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.74%   |
| Validity Sensors VFS491                                                    | 1         | 0.74%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.74%   |
| Synaptics WBDI                                                             | 1         | 0.74%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.74%   |
| AuthenTec AES1600                                                          | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 80%     |
| Upek        | 2         | 8%      |
| O2 Micro    | 2         | 8%      |
| Alcor Micro | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 8         | 32%     |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 24%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12%     |
| Broadcom 58200                                                               | 3         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 8%      |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4%      |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 924       | 71.41%  |
| 1     | 308       | 23.8%   |
| 2     | 53        | 4.1%    |
| 3     | 7         | 0.54%   |
| 5     | 1         | 0.08%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 136       | 32.15%  |
| Graphics card            | 90        | 21.28%  |
| Net/wireless             | 68        | 16.08%  |
| Multimedia controller    | 35        | 8.27%   |
| Chipcard                 | 23        | 5.44%   |
| Bluetooth                | 17        | 4.02%   |
| Unassigned class         | 11        | 2.6%    |
| Communication controller | 11        | 2.6%    |
| Camera                   | 10        | 2.36%   |
| Sound                    | 7         | 1.65%   |
| Network                  | 5         | 1.18%   |
| Storage                  | 4         | 0.95%   |
| Net/ethernet             | 3         | 0.71%   |
| Card reader              | 2         | 0.47%   |
| Firewire controller      | 1         | 0.24%   |

