Linux in Hungary - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Hungary.

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

Total: 4064

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | K52JB                       | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| HP            | Notebook                    | [7b9f1f44c9](https://linux-hardware.org/?probe=7b9f1f44c9) | Mar 31, 2023 |
| HP            | Notebook                    | [ad90621225](https://linux-hardware.org/?probe=ad90621225) | Mar 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| Dell          | Inspiron 5558               | [796d0b6775](https://linux-hardware.org/?probe=796d0b6775) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [bc301a57a0](https://linux-hardware.org/?probe=bc301a57a0) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | [e31b586083](https://linux-hardware.org/?probe=e31b586083) | Mar 27, 2023 |
| Dell          | Inspiron 5558               | [fd675e2bf8](https://linux-hardware.org/?probe=fd675e2bf8) | Mar 27, 2023 |
| ASUSTek       | K56CA                       | [43f064cb46](https://linux-hardware.org/?probe=43f064cb46) | Mar 27, 2023 |
| Toshiba       | Satellite L650              | [5006536f60](https://linux-hardware.org/?probe=5006536f60) | Mar 27, 2023 |
| eMachines     | E725                        | [5212ab8375](https://linux-hardware.org/?probe=5212ab8375) | Mar 26, 2023 |
| eMachines     | E725                        | [8e1945a2c2](https://linux-hardware.org/?probe=8e1945a2c2) | Mar 26, 2023 |
| Dell          | Latitude 5480               | [a663d3bc84](https://linux-hardware.org/?probe=a663d3bc84) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bb1915d1c3](https://linux-hardware.org/?probe=bb1915d1c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [23df41ca86](https://linux-hardware.org/?probe=23df41ca86) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| Lenovo        | G570 20079                  | [ed6328937a](https://linux-hardware.org/?probe=ed6328937a) | Mar 24, 2023 |
| Dell          | Vostro 3500                 | [a375452089](https://linux-hardware.org/?probe=a375452089) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| eMachines     | E725                        | [a5d9ff191b](https://linux-hardware.org/?probe=a5d9ff191b) | Mar 23, 2023 |
| eMachines     | E725                        | [4204fbff83](https://linux-hardware.org/?probe=4204fbff83) | Mar 23, 2023 |
| Dell          | Latitude E6420              | [6da9274d93](https://linux-hardware.org/?probe=6da9274d93) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| THD           | PX1 01                      | [d210243a53](https://linux-hardware.org/?probe=d210243a53) | Mar 20, 2023 |
| THD           | PX1 01                      | [246c888564](https://linux-hardware.org/?probe=246c888564) | Mar 20, 2023 |
| Lenovo        | G50-30 80G0                 | [255de14ecc](https://linux-hardware.org/?probe=255de14ecc) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | [79324bb5ca](https://linux-hardware.org/?probe=79324bb5ca) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | [aad9ecc316](https://linux-hardware.org/?probe=aad9ecc316) | Mar 19, 2023 |
| Acer          | Swift SF113-31              | [f1db5ada96](https://linux-hardware.org/?probe=f1db5ada96) | Mar 18, 2023 |
| Toshiba       | Satellite C50-B             | [338da8730f](https://linux-hardware.org/?probe=338da8730f) | Mar 18, 2023 |
| HP            | Notebook                    | [aa27725a50](https://linux-hardware.org/?probe=aa27725a50) | Mar 18, 2023 |
| HP            | Notebook                    | [a3496c8509](https://linux-hardware.org/?probe=a3496c8509) | Mar 18, 2023 |
| HP            | Laptop 17-ak0xx             | [32fbf8242d](https://linux-hardware.org/?probe=32fbf8242d) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | [b0fa0d95b6](https://linux-hardware.org/?probe=b0fa0d95b6) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | [871677af38](https://linux-hardware.org/?probe=871677af38) | Mar 17, 2023 |
| eMachines     | E725                        | [0ea3d3a0ca](https://linux-hardware.org/?probe=0ea3d3a0ca) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| Dell          | Inspiron 14 5425            | [1128b14745](https://linux-hardware.org/?probe=1128b14745) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Inspiron 5559               | [966cfad104](https://linux-hardware.org/?probe=966cfad104) | Mar 15, 2023 |
| ASUSTek       | T100HAN                     | [b8585e81f9](https://linux-hardware.org/?probe=b8585e81f9) | Mar 15, 2023 |
| Dell          | Inspiron 5559               | [2aa85f401e](https://linux-hardware.org/?probe=2aa85f401e) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [d7fbdbbc9f](https://linux-hardware.org/?probe=d7fbdbbc9f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [34a0e74a78](https://linux-hardware.org/?probe=34a0e74a78) | Mar 15, 2023 |
| Sony          | VPCEB4L1E                   | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Lenovo        | G570 20079                  | [aad6765ba3](https://linux-hardware.org/?probe=aad6765ba3) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | [0acca6eb92](https://linux-hardware.org/?probe=0acca6eb92) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| HP            | ZBook Studio G4             | [2e04fad893](https://linux-hardware.org/?probe=2e04fad893) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| Insyde        | BayTrail                    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| eMachines     | E725                        | [9a49d6defc](https://linux-hardware.org/?probe=9a49d6defc) | Mar 12, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3f007adfc7](https://linux-hardware.org/?probe=3f007adfc7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [eca94a98c0](https://linux-hardware.org/?probe=eca94a98c0) | Mar 09, 2023 |
| eMachines     | E725                        | [a4a1665906](https://linux-hardware.org/?probe=a4a1665906) | Mar 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fc2ee93757](https://linux-hardware.org/?probe=fc2ee93757) | Mar 08, 2023 |
| HP            | Laptop 15s-eq1xxx           | [e1ce357347](https://linux-hardware.org/?probe=e1ce357347) | Mar 08, 2023 |
| eMachines     | E725                        | [8efce0fe6f](https://linux-hardware.org/?probe=8efce0fe6f) | Mar 08, 2023 |
| HP            | Laptop 17-ak0xx             | [cda5fafaf9](https://linux-hardware.org/?probe=cda5fafaf9) | Mar 07, 2023 |
| HP            | Laptop 17-ak0xx             | [c27eecca48](https://linux-hardware.org/?probe=c27eecca48) | Mar 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [85701c7290](https://linux-hardware.org/?probe=85701c7290) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [5f336adb00](https://linux-hardware.org/?probe=5f336adb00) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [ee9717cba3](https://linux-hardware.org/?probe=ee9717cba3) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [77f0d6b014](https://linux-hardware.org/?probe=77f0d6b014) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | [267c62f49a](https://linux-hardware.org/?probe=267c62f49a) | Mar 07, 2023 |
| MSI           | Katana GF66 11UD            | [f464d5be92](https://linux-hardware.org/?probe=f464d5be92) | Mar 07, 2023 |
| ASUSTek       | GL552JX                     | [c8cff8908f](https://linux-hardware.org/?probe=c8cff8908f) | Mar 07, 2023 |
| ASUSTek       | ASUS P1512CEA_P1512CEA      | [ef2488509b](https://linux-hardware.org/?probe=ef2488509b) | Mar 06, 2023 |
| Alcor         | SnugBook Q series           | [3b3c4fd9fd](https://linux-hardware.org/?probe=3b3c4fd9fd) | Mar 05, 2023 |
| Lenovo        | Y50-70 20378                | [c564adb32c](https://linux-hardware.org/?probe=c564adb32c) | Mar 04, 2023 |
| HP            | 650                         | [f595da7b8c](https://linux-hardware.org/?probe=f595da7b8c) | Mar 04, 2023 |
| HP            | 650                         | [9d0b38c967](https://linux-hardware.org/?probe=9d0b38c967) | Mar 04, 2023 |
| Dell          | Inspiron 3584               | [4b6e4a874b](https://linux-hardware.org/?probe=4b6e4a874b) | Mar 04, 2023 |
| HP            | Compaq 6720s                | [b422954b5a](https://linux-hardware.org/?probe=b422954b5a) | Mar 03, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [4bab3eb831](https://linux-hardware.org/?probe=4bab3eb831) | Mar 03, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Fujitsu Si... | AMILO Li3910                | [f29ead8551](https://linux-hardware.org/?probe=f29ead8551) | Mar 01, 2023 |
| TCL Commun... | 8090                        | [d1f86443c7](https://linux-hardware.org/?probe=d1f86443c7) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Nitro AN515-51              | [984b6e660d](https://linux-hardware.org/?probe=984b6e660d) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HP            | Notebook                    | [7e64e6bc1b](https://linux-hardware.org/?probe=7e64e6bc1b) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| Acer          | Nitro AN515-51              | [e5fa16c859](https://linux-hardware.org/?probe=e5fa16c859) | Feb 25, 2023 |
| HP            | Unknown                     | [18a8d556cb](https://linux-hardware.org/?probe=18a8d556cb) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| HP            | Unknown                     | [dc26b08a65](https://linux-hardware.org/?probe=dc26b08a65) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| Dell          | XPS 13 9310                 | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4d2d4ca208](https://linux-hardware.org/?probe=4d2d4ca208) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | Laptop 15-dw1xxx            | [bf47e38ec4](https://linux-hardware.org/?probe=bf47e38ec4) | Feb 22, 2023 |
| Acer          | Nitro AN515-51              | [c2be84fb6c](https://linux-hardware.org/?probe=c2be84fb6c) | Feb 21, 2023 |
| HP            | 250 G3                      | [638d8fa72b](https://linux-hardware.org/?probe=638d8fa72b) | Feb 21, 2023 |
| HP            | 250 G3                      | [eaf1a8a9ca](https://linux-hardware.org/?probe=eaf1a8a9ca) | Feb 21, 2023 |
| HP            | Laptop 17-ak0xx             | [d282ac975d](https://linux-hardware.org/?probe=d282ac975d) | Feb 21, 2023 |
| eMachines     | E725                        | [d982b1aa72](https://linux-hardware.org/?probe=d982b1aa72) | Feb 20, 2023 |
| Acer          | Nitro AN515-51              | [5df682e5d6](https://linux-hardware.org/?probe=5df682e5d6) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | K52F                        | [2cbb8f3f38](https://linux-hardware.org/?probe=2cbb8f3f38) | Feb 20, 2023 |
| ASUSTek       | X541NA                      | [b9ddd17e6c](https://linux-hardware.org/?probe=b9ddd17e6c) | Feb 19, 2023 |
| HP            | Laptop 15-dw1xxx            | [22dfb58516](https://linux-hardware.org/?probe=22dfb58516) | Feb 19, 2023 |
| Toshiba       | Satellite Pro L300          | [c2168db120](https://linux-hardware.org/?probe=c2168db120) | Feb 18, 2023 |
| Dell          | Inspiron 5558               | [40f71233c4](https://linux-hardware.org/?probe=40f71233c4) | Feb 17, 2023 |
| Dell          | Inspiron 5558               | [44e9817292](https://linux-hardware.org/?probe=44e9817292) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a4f7bc0d84](https://linux-hardware.org/?probe=a4f7bc0d84) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6bde6db60](https://linux-hardware.org/?probe=a6bde6db60) | Feb 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [6d7740ca9d](https://linux-hardware.org/?probe=6d7740ca9d) | Feb 17, 2023 |
| HP            | EliteBook 840 G5            | [fb9eb2345d](https://linux-hardware.org/?probe=fb9eb2345d) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | [4f0e88ce52](https://linux-hardware.org/?probe=4f0e88ce52) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | [eac8d6ab9d](https://linux-hardware.org/?probe=eac8d6ab9d) | Feb 16, 2023 |
| HP            | 250 G1                      | [a673746c67](https://linux-hardware.org/?probe=a673746c67) | Feb 16, 2023 |
| HP            | 250 G1                      | [cc5e272ca9](https://linux-hardware.org/?probe=cc5e272ca9) | Feb 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [33b1f65ec0](https://linux-hardware.org/?probe=33b1f65ec0) | Feb 15, 2023 |
| Lenovo        | Z710 20250                  | [7b40745c7f](https://linux-hardware.org/?probe=7b40745c7f) | Feb 14, 2023 |
| Lenovo        | Z710 20250                  | [903deba17a](https://linux-hardware.org/?probe=903deba17a) | Feb 14, 2023 |
| HP            | Pavilion dv5                | [fd6bd7275b](https://linux-hardware.org/?probe=fd6bd7275b) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Dell          | Inspiron 15-3567            | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| Dell          | Latitude 5420               | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| Acer          | TravelMate 8571             | [609cc404fb](https://linux-hardware.org/?probe=609cc404fb) | Feb 12, 2023 |
| HP            | Compaq 6910p                | [328acaf5ee](https://linux-hardware.org/?probe=328acaf5ee) | Feb 12, 2023 |
| ASUSTek       | K52F                        | [ee35b00a7e](https://linux-hardware.org/?probe=ee35b00a7e) | Feb 12, 2023 |
| ASUSTek       | X541UAK                     | [e27e733bc0](https://linux-hardware.org/?probe=e27e733bc0) | Feb 12, 2023 |
| ASUSTek       | K52F                        | [364c41f9aa](https://linux-hardware.org/?probe=364c41f9aa) | Feb 11, 2023 |
| HP            | Laptop 14s-fq0xxx           | [eb1f7dfd26](https://linux-hardware.org/?probe=eb1f7dfd26) | Feb 10, 2023 |
| Dell          | Latitude E6230              | [d0a04b130a](https://linux-hardware.org/?probe=d0a04b130a) | Feb 09, 2023 |
| Dell          | Latitude E6230              | [11a1ba46f3](https://linux-hardware.org/?probe=11a1ba46f3) | Feb 09, 2023 |
| MSI           | GX70 3CC                    | [c9abc5f038](https://linux-hardware.org/?probe=c9abc5f038) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | [dd6c2cbcc6](https://linux-hardware.org/?probe=dd6c2cbcc6) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | [470857588f](https://linux-hardware.org/?probe=470857588f) | Feb 07, 2023 |
| ASUSTek       | X541UAK                     | [62acbef04d](https://linux-hardware.org/?probe=62acbef04d) | Feb 07, 2023 |
| HP            | Unknown                     | [eb01c0393d](https://linux-hardware.org/?probe=eb01c0393d) | Feb 07, 2023 |
| HP            | Unknown                     | [db607a1e03](https://linux-hardware.org/?probe=db607a1e03) | Feb 07, 2023 |
| Lenovo        | ThinkPad T490 20N3S11B0V    | [3b35d51bfb](https://linux-hardware.org/?probe=3b35d51bfb) | Feb 06, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8b6fbfa8f5](https://linux-hardware.org/?probe=8b6fbfa8f5) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [2b37c84303](https://linux-hardware.org/?probe=2b37c84303) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Dell          | Latitude D630               | [a1ea4874cf](https://linux-hardware.org/?probe=a1ea4874cf) | Feb 03, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Dell          | Latitude D630               | [7f34868246](https://linux-hardware.org/?probe=7f34868246) | Feb 02, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Dell          | Inspiron 7737               | [fb42f48fbe](https://linux-hardware.org/?probe=fb42f48fbe) | Feb 01, 2023 |
| eMachines     | E725                        | [4b1805b3f6](https://linux-hardware.org/?probe=4b1805b3f6) | Feb 01, 2023 |
| HP            | EliteBook 8570p             | [2f7f3a5b93](https://linux-hardware.org/?probe=2f7f3a5b93) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | [8a90f64e68](https://linux-hardware.org/?probe=8a90f64e68) | Feb 01, 2023 |
| HP            | 250 G1                      | [41f3eccf2e](https://linux-hardware.org/?probe=41f3eccf2e) | Feb 01, 2023 |
| Apple         | MacBookAir5,2               | [2bdd007ce6](https://linux-hardware.org/?probe=2bdd007ce6) | Feb 01, 2023 |
| HP            | 250 G1                      | [345cb01bcc](https://linux-hardware.org/?probe=345cb01bcc) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | [1a3af834c9](https://linux-hardware.org/?probe=1a3af834c9) | Feb 01, 2023 |
| Acer          | Aspire A315-21G             | [78f5b5c42b](https://linux-hardware.org/?probe=78f5b5c42b) | Feb 01, 2023 |
| Lenovo        | Y50-70 20378                | [04c77927f5](https://linux-hardware.org/?probe=04c77927f5) | Jan 31, 2023 |
| Lenovo        | Y50-70 20378                | [5dc21f30b5](https://linux-hardware.org/?probe=5dc21f30b5) | Jan 31, 2023 |
| Lenovo        | G580 20150                  | [339aef175f](https://linux-hardware.org/?probe=339aef175f) | Jan 30, 2023 |
| Lenovo        | G580 20150                  | [e0b08d335b](https://linux-hardware.org/?probe=e0b08d335b) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 431924G       | [c899463c77](https://linux-hardware.org/?probe=c899463c77) | Jan 30, 2023 |
| HP            | ProBook 4520s               | [6a16110b08](https://linux-hardware.org/?probe=6a16110b08) | Jan 29, 2023 |
| HP            | ProBook 4520s               | [e973aeb114](https://linux-hardware.org/?probe=e973aeb114) | Jan 29, 2023 |
| Samsung       | N102S                       | [c23908cf42](https://linux-hardware.org/?probe=c23908cf42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T480 20L6SF8C00    | [4ab453f835](https://linux-hardware.org/?probe=4ab453f835) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| Lenovo        | G580 20150                  | [7597b19143](https://linux-hardware.org/?probe=7597b19143) | Jan 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4804425adc](https://linux-hardware.org/?probe=4804425adc) | Jan 25, 2023 |
| Acer          | Aspire A517-53G             | [2a1ad07cce](https://linux-hardware.org/?probe=2a1ad07cce) | Jan 25, 2023 |
| Acer          | Aspire A515-57G             | [2b83e8779f](https://linux-hardware.org/?probe=2b83e8779f) | Jan 25, 2023 |
| Acer          | Aspire A515-57G             | [cc3599afd2](https://linux-hardware.org/?probe=cc3599afd2) | Jan 24, 2023 |
| Dell          | Latitude 5480               | [0e21cc929a](https://linux-hardware.org/?probe=0e21cc929a) | Jan 24, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [16e64883d7](https://linux-hardware.org/?probe=16e64883d7) | Jan 24, 2023 |
| HP            | EliteBook Folio 9480m       | [39c54a5f09](https://linux-hardware.org/?probe=39c54a5f09) | Jan 24, 2023 |
| HP            | EliteBook Folio 9480m       | [ae139e78a0](https://linux-hardware.org/?probe=ae139e78a0) | Jan 22, 2023 |
| HP            | EliteBook Folio 9480m       | [d43d26ff9f](https://linux-hardware.org/?probe=d43d26ff9f) | Jan 22, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [53fb561c53](https://linux-hardware.org/?probe=53fb561c53) | Jan 21, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| Acer          | Nitro AN515-42              | [d6a24ede85](https://linux-hardware.org/?probe=d6a24ede85) | Jan 19, 2023 |
| Dell          | Latitude 5420               | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| Lenovo        | Yoga 500-14IHW 80N5         | [e233e8d6d2](https://linux-hardware.org/?probe=e233e8d6d2) | Jan 18, 2023 |
| Acer          | TravelMate 8571             | [2933c64a6d](https://linux-hardware.org/?probe=2933c64a6d) | Jan 15, 2023 |
| Acer          | TravelMate 8571             | [ad01651917](https://linux-hardware.org/?probe=ad01651917) | Jan 15, 2023 |
| HP            | EliteBook 745 G3            | [c20a339ddb](https://linux-hardware.org/?probe=c20a339ddb) | Jan 15, 2023 |
| Acer          | TravelMate B117-M           | [c760a021bf](https://linux-hardware.org/?probe=c760a021bf) | Jan 14, 2023 |
| Acer          | TravelMate B117-M           | [bee982f325](https://linux-hardware.org/?probe=bee982f325) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| Dell          | Inspiron 5558               | [798c78aaf7](https://linux-hardware.org/?probe=798c78aaf7) | Jan 14, 2023 |
| ASUSTek       | X550LN                      | [d412367e44](https://linux-hardware.org/?probe=d412367e44) | Jan 13, 2023 |
| ASUSTek       | X550LN                      | [196ba30ef7](https://linux-hardware.org/?probe=196ba30ef7) | Jan 13, 2023 |
| Fujitsu       | LIFEBOOK T730               | [f9ba03526e](https://linux-hardware.org/?probe=f9ba03526e) | Jan 13, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [61f80cd38a](https://linux-hardware.org/?probe=61f80cd38a) | Jan 13, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [10f4ae9765](https://linux-hardware.org/?probe=10f4ae9765) | Jan 12, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [48531d8e05](https://linux-hardware.org/?probe=48531d8e05) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [e3eb62db83](https://linux-hardware.org/?probe=e3eb62db83) | Jan 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [b36d8e79ea](https://linux-hardware.org/?probe=b36d8e79ea) | Jan 12, 2023 |
| HP            | ProBook 4535s               | [47cd489d8b](https://linux-hardware.org/?probe=47cd489d8b) | Jan 11, 2023 |
| Lenovo        | G50-45 80E3                 | [80f84b2854](https://linux-hardware.org/?probe=80f84b2854) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | [a941237bf3](https://linux-hardware.org/?probe=a941237bf3) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | [9eebe49454](https://linux-hardware.org/?probe=9eebe49454) | Jan 11, 2023 |
| HP            | EliteBook 2540p             | [106e3d9073](https://linux-hardware.org/?probe=106e3d9073) | Jan 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [1ebf7a4a09](https://linux-hardware.org/?probe=1ebf7a4a09) | Jan 11, 2023 |
| Lenovo        | G580 20150                  | [b1fb0a1f64](https://linux-hardware.org/?probe=b1fb0a1f64) | Jan 10, 2023 |
| ASUSTek       | Strix 15 GL503GE            | [07b77ef803](https://linux-hardware.org/?probe=07b77ef803) | Jan 09, 2023 |
| Acer          | A515-44G                    | [0589eb53fa](https://linux-hardware.org/?probe=0589eb53fa) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | [beef7a74d4](https://linux-hardware.org/?probe=beef7a74d4) | Jan 08, 2023 |
| HP            | ProBook 6570b               | [ac7eff1b5e](https://linux-hardware.org/?probe=ac7eff1b5e) | Jan 08, 2023 |
| HP            | ProBook 6570b               | [819a1c02df](https://linux-hardware.org/?probe=819a1c02df) | Jan 08, 2023 |
| HP            | Laptop 17-ak0xx             | [ffed123536](https://linux-hardware.org/?probe=ffed123536) | Jan 07, 2023 |
| HP            | Pavilion 15                 | [f946892969](https://linux-hardware.org/?probe=f946892969) | Jan 07, 2023 |
| Lenovo        | G580 20150                  | [daad153e9a](https://linux-hardware.org/?probe=daad153e9a) | Jan 06, 2023 |
| HP            | 255 G5 Notebook PC          | [7c62a0a238](https://linux-hardware.org/?probe=7c62a0a238) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | [1473e6f0d9](https://linux-hardware.org/?probe=1473e6f0d9) | Jan 06, 2023 |
| Dell          | Inspiron 5558               | [74f479bd3e](https://linux-hardware.org/?probe=74f479bd3e) | Jan 06, 2023 |
| Dell          | Latitude E6420              | [8b590c65fc](https://linux-hardware.org/?probe=8b590c65fc) | Jan 05, 2023 |
| Dell          | Latitude 5430               | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | [9a16949691](https://linux-hardware.org/?probe=9a16949691) | Jan 05, 2023 |
| Lenovo        | G580 20150                  | [b7119b52a7](https://linux-hardware.org/?probe=b7119b52a7) | Jan 05, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | [30195a4ca0](https://linux-hardware.org/?probe=30195a4ca0) | Jan 04, 2023 |
| Lenovo        | ThinkPad T410 2537BF9       | [2e29dd8142](https://linux-hardware.org/?probe=2e29dd8142) | Jan 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4247d8d8b0](https://linux-hardware.org/?probe=4247d8d8b0) | Jan 04, 2023 |
| HP            | 255 G5 Notebook PC          | [cdb140b891](https://linux-hardware.org/?probe=cdb140b891) | Jan 03, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ed9ddacdce](https://linux-hardware.org/?probe=ed9ddacdce) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc19d2cf24](https://linux-hardware.org/?probe=cc19d2cf24) | Dec 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e0f696a9b9](https://linux-hardware.org/?probe=e0f696a9b9) | Dec 31, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [f83ed1dd39](https://linux-hardware.org/?probe=f83ed1dd39) | Dec 30, 2022 |
| Dell          | G15 5520                    | [2e82f45fb6](https://linux-hardware.org/?probe=2e82f45fb6) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6c00206f7e](https://linux-hardware.org/?probe=6c00206f7e) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [e02be15b45](https://linux-hardware.org/?probe=e02be15b45) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [5afd8e73be](https://linux-hardware.org/?probe=5afd8e73be) | Dec 30, 2022 |
| HP            | EliteBook 2540p             | [279718a62f](https://linux-hardware.org/?probe=279718a62f) | Dec 30, 2022 |
| Dell          | Latitude 5480               | [64aa4b9161](https://linux-hardware.org/?probe=64aa4b9161) | Dec 30, 2022 |
| Dell          | Vostro 1015                 | [fd48487066](https://linux-hardware.org/?probe=fd48487066) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [c286883155](https://linux-hardware.org/?probe=c286883155) | Dec 29, 2022 |
| Dell          | Latitude 5480               | [b578e196dd](https://linux-hardware.org/?probe=b578e196dd) | Dec 29, 2022 |
| Dell          | Latitude E6230              | [a8df3d8262](https://linux-hardware.org/?probe=a8df3d8262) | Dec 29, 2022 |
| Dell          | Latitude E6230              | [a57d2f5ccb](https://linux-hardware.org/?probe=a57d2f5ccb) | Dec 29, 2022 |
| Dell          | Vostro 1015                 | [11e78b0f9b](https://linux-hardware.org/?probe=11e78b0f9b) | Dec 29, 2022 |
| Dell          | Latitude 5480               | [4b2fda33f4](https://linux-hardware.org/?probe=4b2fda33f4) | Dec 28, 2022 |
| Dell          | Latitude 5480               | [abcd3bea2f](https://linux-hardware.org/?probe=abcd3bea2f) | Dec 28, 2022 |
| Acer          | Aspire E5-573G              | [6e1255aa44](https://linux-hardware.org/?probe=6e1255aa44) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [5cbcee30c7](https://linux-hardware.org/?probe=5cbcee30c7) | Dec 28, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [743ed4d93a](https://linux-hardware.org/?probe=743ed4d93a) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [819f9be803](https://linux-hardware.org/?probe=819f9be803) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ad4d919e36](https://linux-hardware.org/?probe=ad4d919e36) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| Acer          | Aspire A515-51G             | [56ceb67978](https://linux-hardware.org/?probe=56ceb67978) | Dec 26, 2022 |
| Acer          | Aspire A515-51G             | [e44b069b44](https://linux-hardware.org/?probe=e44b069b44) | Dec 26, 2022 |
| HP            | Compaq 610                  | [198b4d0586](https://linux-hardware.org/?probe=198b4d0586) | Dec 25, 2022 |
| HP            | Compaq 610                  | [0e9ab46e66](https://linux-hardware.org/?probe=0e9ab46e66) | Dec 25, 2022 |
| ASUSTek       | X550LN                      | [207f82e19c](https://linux-hardware.org/?probe=207f82e19c) | Dec 25, 2022 |
| Dell          | Inspiron N5010              | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Dell          | Latitude 7490               | [d5223c073b](https://linux-hardware.org/?probe=d5223c073b) | Dec 23, 2022 |
| eMachines     | E725                        | [86939210d0](https://linux-hardware.org/?probe=86939210d0) | Dec 22, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [6db25ba5ca](https://linux-hardware.org/?probe=6db25ba5ca) | Dec 22, 2022 |
| HP            | Laptop 17-ak0xx             | [7e77870894](https://linux-hardware.org/?probe=7e77870894) | Dec 21, 2022 |
| HP            | Laptop 17-ak0xx             | [04c205c943](https://linux-hardware.org/?probe=04c205c943) | Dec 21, 2022 |
| Dell          | Latitude E6230              | [80012cb415](https://linux-hardware.org/?probe=80012cb415) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT02    | [439cd38614](https://linux-hardware.org/?probe=439cd38614) | Dec 18, 2022 |
| Acer          | Swift SF114-32              | [757b666913](https://linux-hardware.org/?probe=757b666913) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [56e75d70fa](https://linux-hardware.org/?probe=56e75d70fa) | Dec 18, 2022 |
| Dell          | Latitude E6230              | [ba7fa25841](https://linux-hardware.org/?probe=ba7fa25841) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [a481e4a590](https://linux-hardware.org/?probe=a481e4a590) | Dec 17, 2022 |
| Dell          | Inspiron M5030              | [265739601c](https://linux-hardware.org/?probe=265739601c) | Dec 16, 2022 |
| HP            | Laptop 17-ak0xx             | [0ed9c8a241](https://linux-hardware.org/?probe=0ed9c8a241) | Dec 16, 2022 |
| ASUSTek       | X550LN                      | [d09c34a000](https://linux-hardware.org/?probe=d09c34a000) | Dec 16, 2022 |
| HP            | EliteBook 850 G4            | [0a2fc94b9a](https://linux-hardware.org/?probe=0a2fc94b9a) | Dec 14, 2022 |
| Dell          | Inspiron 14 5401            | [0138a1b2d4](https://linux-hardware.org/?probe=0138a1b2d4) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | [9dc9070ae6](https://linux-hardware.org/?probe=9dc9070ae6) | Dec 13, 2022 |
| Lenovo        | E50-80 80J2                 | [cf9f4d4a79](https://linux-hardware.org/?probe=cf9f4d4a79) | Dec 13, 2022 |
| Acer          | Extensa 5630                | [ec4f446d23](https://linux-hardware.org/?probe=ec4f446d23) | Dec 11, 2022 |
| HP            | 255 G7 Notebook PC          | [b7a944c773](https://linux-hardware.org/?probe=b7a944c773) | Dec 11, 2022 |
| HP            | 650                         | [add4ca69e3](https://linux-hardware.org/?probe=add4ca69e3) | Dec 11, 2022 |
| HP            | 650                         | [9bb3729969](https://linux-hardware.org/?probe=9bb3729969) | Dec 11, 2022 |
| Acer          | TravelMate 8571             | [63aa77ba8d](https://linux-hardware.org/?probe=63aa77ba8d) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | [32870f2fa3](https://linux-hardware.org/?probe=32870f2fa3) | Dec 10, 2022 |
| ASUSTek       | K54HR                       | [fac8091847](https://linux-hardware.org/?probe=fac8091847) | Dec 10, 2022 |
| Dell          | Inspiron 3542               | [eb1d437253](https://linux-hardware.org/?probe=eb1d437253) | Dec 10, 2022 |
| Dell          | Inspiron 13-5378            | [2a7d96e2eb](https://linux-hardware.org/?probe=2a7d96e2eb) | Dec 10, 2022 |
| ASUSTek       | X200MA                      | [1cb00c612b](https://linux-hardware.org/?probe=1cb00c612b) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [9617825518](https://linux-hardware.org/?probe=9617825518) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [7b1075fd9b](https://linux-hardware.org/?probe=7b1075fd9b) | Dec 09, 2022 |
| Acer          | TravelMate 8571             | [89270d1f7c](https://linux-hardware.org/?probe=89270d1f7c) | Dec 08, 2022 |
| Acer          | Nitro AN515-51              | [177d3d8e16](https://linux-hardware.org/?probe=177d3d8e16) | Dec 08, 2022 |
| Dell          | Inspiron M5030              | [f73021e3c7](https://linux-hardware.org/?probe=f73021e3c7) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| ASUSTek       | K54HR                       | [66433bdc5e](https://linux-hardware.org/?probe=66433bdc5e) | Dec 07, 2022 |
| Acer          | TravelMate 8571             | [9e7f0672b2](https://linux-hardware.org/?probe=9e7f0672b2) | Dec 06, 2022 |
| Lenovo        | ThinkPad T470 20HES0E71M    | [85fc801717](https://linux-hardware.org/?probe=85fc801717) | Dec 05, 2022 |
| HP            | EliteBook 840 G6            | [f8e5635371](https://linux-hardware.org/?probe=f8e5635371) | Dec 04, 2022 |
| ASUSTek       | K54HR                       | [264d0d02bb](https://linux-hardware.org/?probe=264d0d02bb) | Dec 04, 2022 |
| Acer          | TravelMate 8571             | [df032cacb6](https://linux-hardware.org/?probe=df032cacb6) | Dec 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [32dbbbf380](https://linux-hardware.org/?probe=32dbbbf380) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Dell          | Latitude E5520              | [1b3b69b19f](https://linux-hardware.org/?probe=1b3b69b19f) | Nov 28, 2022 |
| Sony          | VPCYB3V1E                   | [8fc84889a5](https://linux-hardware.org/?probe=8fc84889a5) | Nov 28, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [83a97530e1](https://linux-hardware.org/?probe=83a97530e1) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cd9478ab62](https://linux-hardware.org/?probe=cd9478ab62) | Nov 26, 2022 |
| Dell          | Latitude E5520              | [ce72f1c2a9](https://linux-hardware.org/?probe=ce72f1c2a9) | Nov 25, 2022 |
| HP            | 650                         | [15c69c43ca](https://linux-hardware.org/?probe=15c69c43ca) | Nov 24, 2022 |
| Dell          | Latitude E6540              | [5c474a2cdb](https://linux-hardware.org/?probe=5c474a2cdb) | Nov 24, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [adcb4db30d](https://linux-hardware.org/?probe=adcb4db30d) | Nov 24, 2022 |
| Acer          | Aspire A315-57G             | [93dc021b03](https://linux-hardware.org/?probe=93dc021b03) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Acer          | Aspire A315-57G             | [fd41589a1a](https://linux-hardware.org/?probe=fd41589a1a) | Nov 22, 2022 |
| Lenovo        | Z50-70 20354                | [4de72c5631](https://linux-hardware.org/?probe=4de72c5631) | Nov 20, 2022 |
| Valve         | Jupiter                     | [dd6f589d44](https://linux-hardware.org/?probe=dd6f589d44) | Nov 20, 2022 |
| HP            | EliteBook 840 G4            | [943027284b](https://linux-hardware.org/?probe=943027284b) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| HP            | Unknown                     | [f76118ac5f](https://linux-hardware.org/?probe=f76118ac5f) | Nov 13, 2022 |
| HP            | Unknown                     | [8cd95516d0](https://linux-hardware.org/?probe=8cd95516d0) | Nov 13, 2022 |
| HP            | 650                         | [100707d1eb](https://linux-hardware.org/?probe=100707d1eb) | Nov 13, 2022 |
| Fujitsu       | LIFEBOOK E752               | [be50b73bfe](https://linux-hardware.org/?probe=be50b73bfe) | Nov 12, 2022 |
| Fujitsu       | LIFEBOOK E752               | [affbec4acb](https://linux-hardware.org/?probe=affbec4acb) | Nov 12, 2022 |
| Lenovo        | Y520-15IKBM 80YY            | [36b3c3d634](https://linux-hardware.org/?probe=36b3c3d634) | Nov 09, 2022 |
| Acer          | Aspire A315-42              | [8f4c16021c](https://linux-hardware.org/?probe=8f4c16021c) | Nov 09, 2022 |
| HP            | 625                         | [2d8090e61e](https://linux-hardware.org/?probe=2d8090e61e) | Nov 08, 2022 |
| Unknown       | Unknown                     | [010a383efa](https://linux-hardware.org/?probe=010a383efa) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| ASUSTek       | F5V                         | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 650                         | [fd3b93e8fb](https://linux-hardware.org/?probe=fd3b93e8fb) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Dell          | Latitude E7250              | [0c36cbc6ca](https://linux-hardware.org/?probe=0c36cbc6ca) | Nov 03, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [c83f37c114](https://linux-hardware.org/?probe=c83f37c114) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Dell          | Inspiron 5558               | [416655ce7d](https://linux-hardware.org/?probe=416655ce7d) | Oct 30, 2022 |
| Dell          | Inspiron 5558               | [ae71fe1a19](https://linux-hardware.org/?probe=ae71fe1a19) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Dell          | Inspiron 7737               | [f352df76ef](https://linux-hardware.org/?probe=f352df76ef) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | [3b67700f14](https://linux-hardware.org/?probe=3b67700f14) | Oct 28, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [a80d2e7626](https://linux-hardware.org/?probe=a80d2e7626) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [7cb792e432](https://linux-hardware.org/?probe=7cb792e432) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0c33d71210](https://linux-hardware.org/?probe=0c33d71210) | Oct 27, 2022 |
| ASUSTek       | K55VJ                       | [eac363d110](https://linux-hardware.org/?probe=eac363d110) | Oct 25, 2022 |
| ALLDOCUBE     | i1402A                      | [22c255e8cd](https://linux-hardware.org/?probe=22c255e8cd) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| Dell          | Vostro 3501                 | [df16ec68c3](https://linux-hardware.org/?probe=df16ec68c3) | Oct 24, 2022 |
| Dell          | Vostro 3501                 | [996a5a3b8d](https://linux-hardware.org/?probe=996a5a3b8d) | Oct 24, 2022 |
| HP            | Compaq 6910p (GH717AW#AB... | [02d31506a2](https://linux-hardware.org/?probe=02d31506a2) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [73ee8be4e9](https://linux-hardware.org/?probe=73ee8be4e9) | Oct 23, 2022 |
| Dell          | Latitude E6230              | [52ee15a8f5](https://linux-hardware.org/?probe=52ee15a8f5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [238c40d2e4](https://linux-hardware.org/?probe=238c40d2e4) | Oct 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [680823db07](https://linux-hardware.org/?probe=680823db07) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [eb7940e5a4](https://linux-hardware.org/?probe=eb7940e5a4) | Oct 19, 2022 |
| eMachines     | E725                        | [ea21ca2d78](https://linux-hardware.org/?probe=ea21ca2d78) | Oct 19, 2022 |
| Alcor Digi... | Snugbook N1431              | [098e362854](https://linux-hardware.org/?probe=098e362854) | Oct 19, 2022 |
| eMachines     | E725                        | [6d5ddca6c9](https://linux-hardware.org/?probe=6d5ddca6c9) | Oct 18, 2022 |
| Lenovo        | ThinkPad T490 20N2S29E00    | [dd61a6ea26](https://linux-hardware.org/?probe=dd61a6ea26) | Oct 18, 2022 |
| Dell          | Inspiron 3584               | [c80df2b63c](https://linux-hardware.org/?probe=c80df2b63c) | Oct 17, 2022 |
| Acer          | Aspire A717-71G             | [969c0ac771](https://linux-hardware.org/?probe=969c0ac771) | Oct 17, 2022 |
| eMachines     | E725                        | [f365f1eaa7](https://linux-hardware.org/?probe=f365f1eaa7) | Oct 17, 2022 |
| eMachines     | E725                        | [7003528b88](https://linux-hardware.org/?probe=7003528b88) | Oct 17, 2022 |
| ASUSTek       | GL552VW                     | [a49ebeea02](https://linux-hardware.org/?probe=a49ebeea02) | Oct 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [528fc3c5ec](https://linux-hardware.org/?probe=528fc3c5ec) | Oct 17, 2022 |
| Unknown       | Unknown                     | [07a141abbb](https://linux-hardware.org/?probe=07a141abbb) | Oct 14, 2022 |
| eMachines     | E725                        | [77e7244d88](https://linux-hardware.org/?probe=77e7244d88) | Oct 14, 2022 |
| eMachines     | E725                        | [34538c32c5](https://linux-hardware.org/?probe=34538c32c5) | Oct 14, 2022 |
| Lenovo        | Z50-75 80EC                 | [b36e579d37](https://linux-hardware.org/?probe=b36e579d37) | Oct 14, 2022 |
| Unknown       | Unknown                     | [0d8c24c367](https://linux-hardware.org/?probe=0d8c24c367) | Oct 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | Aspire A515-45              | [3ba623cebe](https://linux-hardware.org/?probe=3ba623cebe) | Oct 12, 2022 |
| Dell          | Latitude 5410               | [e468acae5c](https://linux-hardware.org/?probe=e468acae5c) | Oct 11, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [dc933df0a9](https://linux-hardware.org/?probe=dc933df0a9) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [63a8f1baa1](https://linux-hardware.org/?probe=63a8f1baa1) | Oct 10, 2022 |
| ASUSTek       | X550VX                      | [7f9e9ab40b](https://linux-hardware.org/?probe=7f9e9ab40b) | Oct 10, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| ASUSTek       | F3Sv                        | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Lenovo        | V145-15AST 81MT             | [91163f885b](https://linux-hardware.org/?probe=91163f885b) | Oct 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [7f186dfabd](https://linux-hardware.org/?probe=7f186dfabd) | Oct 07, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6bae0e4f18](https://linux-hardware.org/?probe=6bae0e4f18) | Oct 07, 2022 |
| eMachines     | E725                        | [9a77e04f3c](https://linux-hardware.org/?probe=9a77e04f3c) | Oct 05, 2022 |
| eMachines     | E725                        | [e413d82fa5](https://linux-hardware.org/?probe=e413d82fa5) | Oct 05, 2022 |
| Dell          | Inspiron 5593               | [33e28ce993](https://linux-hardware.org/?probe=33e28ce993) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| Toshiba       | Satellite M50D-A            | [6eaada1ab0](https://linux-hardware.org/?probe=6eaada1ab0) | Oct 03, 2022 |
| Lenovo        | ThinkPad X230 2325Y5L       | [7c5c62cc90](https://linux-hardware.org/?probe=7c5c62cc90) | Oct 03, 2022 |
| HP            | EliteBook 850 G1            | [7bb0235bd2](https://linux-hardware.org/?probe=7bb0235bd2) | Oct 03, 2022 |
| Dell          | Latitude D630               | [90dc2dddf8](https://linux-hardware.org/?probe=90dc2dddf8) | Oct 02, 2022 |
| Sony          | SVS13118GBB                 | [48dd8fb419](https://linux-hardware.org/?probe=48dd8fb419) | Oct 01, 2022 |
| Dell          | Latitude D630               | [d00c756052](https://linux-hardware.org/?probe=d00c756052) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [75e6dbe3d2](https://linux-hardware.org/?probe=75e6dbe3d2) | Oct 01, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e48bab666f](https://linux-hardware.org/?probe=e48bab666f) | Oct 01, 2022 |
| Sony          | SVS13118GBB                 | [0e0ca26d00](https://linux-hardware.org/?probe=0e0ca26d00) | Sep 30, 2022 |
| Sony          | SVS13118GBB                 | [12868cf90f](https://linux-hardware.org/?probe=12868cf90f) | Sep 30, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [1ff8e037f4](https://linux-hardware.org/?probe=1ff8e037f4) | Sep 30, 2022 |
| Acer          | Aspire E5-521               | [a55d68e93c](https://linux-hardware.org/?probe=a55d68e93c) | Sep 30, 2022 |
| Acer          | Aspire A715-72G             | [8b7e129d4a](https://linux-hardware.org/?probe=8b7e129d4a) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [65f56cc48b](https://linux-hardware.org/?probe=65f56cc48b) | Sep 29, 2022 |
| Lenovo        | IdeaPad 3 15ARE 81W4        | [b784552e84](https://linux-hardware.org/?probe=b784552e84) | Sep 28, 2022 |
| eMachines     | E725                        | [04c9a24d86](https://linux-hardware.org/?probe=04c9a24d86) | Sep 28, 2022 |
| eMachines     | E725                        | [f99f2244c7](https://linux-hardware.org/?probe=f99f2244c7) | Sep 28, 2022 |
| Acer          | Aspire E1-531               | [b7d37d0c6f](https://linux-hardware.org/?probe=b7d37d0c6f) | Sep 27, 2022 |
| Acer          | Aspire E1-531               | [90856d2122](https://linux-hardware.org/?probe=90856d2122) | Sep 27, 2022 |
| ASUSTek       | 1015BX                      | [5190c360db](https://linux-hardware.org/?probe=5190c360db) | Sep 25, 2022 |
| HP            | 650                         | [f835e52a64](https://linux-hardware.org/?probe=f835e52a64) | Sep 25, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [fc7831b371](https://linux-hardware.org/?probe=fc7831b371) | Sep 23, 2022 |
| HP            | Compaq 6710b (KE125ET#AB... | [15cffbb03b](https://linux-hardware.org/?probe=15cffbb03b) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0570d2318c](https://linux-hardware.org/?probe=0570d2318c) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4d47a6bfcf](https://linux-hardware.org/?probe=4d47a6bfcf) | Sep 22, 2022 |
| ASUSTek       | K54HR                       | [dbf0f3b1c8](https://linux-hardware.org/?probe=dbf0f3b1c8) | Sep 21, 2022 |
| ASUSTek       | K54HR                       | [25fd2ae90c](https://linux-hardware.org/?probe=25fd2ae90c) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [17945ad430](https://linux-hardware.org/?probe=17945ad430) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [49c7f8f204](https://linux-hardware.org/?probe=49c7f8f204) | Sep 21, 2022 |
| Toshiba       | Satellite L450              | [20b85987c4](https://linux-hardware.org/?probe=20b85987c4) | Sep 20, 2022 |
| Toshiba       | Satellite L450              | [9f694612d3](https://linux-hardware.org/?probe=9f694612d3) | Sep 20, 2022 |
| ASUSTek       | X550CL                      | [16d313fefa](https://linux-hardware.org/?probe=16d313fefa) | Sep 20, 2022 |
| eMachines     | E725                        | [141723a3e2](https://linux-hardware.org/?probe=141723a3e2) | Sep 16, 2022 |
| eMachines     | E725                        | [bf27205286](https://linux-hardware.org/?probe=bf27205286) | Sep 15, 2022 |
| Acer          | Aspire 5310                 | [963a5bcade](https://linux-hardware.org/?probe=963a5bcade) | Sep 15, 2022 |
| Dell          | Latitude 7480               | [a9432965f4](https://linux-hardware.org/?probe=a9432965f4) | Sep 15, 2022 |
| Timi          | RedmiBook Pro 15S           | [20b9167fee](https://linux-hardware.org/?probe=20b9167fee) | Sep 11, 2022 |
| HP            | EliteBook 860 16 inch G9... | [080ffe37b9](https://linux-hardware.org/?probe=080ffe37b9) | Sep 08, 2022 |
| Dell          | Latitude E6230              | [41c1130440](https://linux-hardware.org/?probe=41c1130440) | Sep 07, 2022 |
| Dell          | Latitude E6230              | [5e0436a64a](https://linux-hardware.org/?probe=5e0436a64a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [32715c6eb9](https://linux-hardware.org/?probe=32715c6eb9) | Sep 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [cbc35f08cb](https://linux-hardware.org/?probe=cbc35f08cb) | Sep 06, 2022 |
| Dell          | Latitude 7490               | [4a59725d2d](https://linux-hardware.org/?probe=4a59725d2d) | Sep 05, 2022 |
| Mediacom      | GTZS                        | [d62a43f91e](https://linux-hardware.org/?probe=d62a43f91e) | Sep 04, 2022 |
| HP            | 650                         | [526b86a559](https://linux-hardware.org/?probe=526b86a559) | Sep 04, 2022 |
| HP            | 650                         | [6f184e96df](https://linux-hardware.org/?probe=6f184e96df) | Sep 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| eMachines     | E725                        | [3e5c01d133](https://linux-hardware.org/?probe=3e5c01d133) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [1dd156b433](https://linux-hardware.org/?probe=1dd156b433) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| eMachines     | E725                        | [b73baa0850](https://linux-hardware.org/?probe=b73baa0850) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [421ab76c43](https://linux-hardware.org/?probe=421ab76c43) | Aug 24, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c7d603acb8](https://linux-hardware.org/?probe=c7d603acb8) | Aug 24, 2022 |
| Lenovo        | ThinkPad T410 2537BF9       | [be0227ed47](https://linux-hardware.org/?probe=be0227ed47) | Aug 23, 2022 |
| Dell          | Latitude D630               | [be9c4025cb](https://linux-hardware.org/?probe=be9c4025cb) | Aug 23, 2022 |
| Apple         | MacBookPro8,1               | [88bb92c310](https://linux-hardware.org/?probe=88bb92c310) | Aug 22, 2022 |
| ASUSTek       | 1015BX                      | [94f3284833](https://linux-hardware.org/?probe=94f3284833) | Aug 21, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| HP            | 620                         | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [0cef35b44a](https://linux-hardware.org/?probe=0cef35b44a) | Aug 20, 2022 |
| Lenovo        | ThinkPad X220 4290L39       | [31a7893b95](https://linux-hardware.org/?probe=31a7893b95) | Aug 20, 2022 |
| HP            | 620                         | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| Dell          | Latitude 5580               | [5c9db9ff58](https://linux-hardware.org/?probe=5c9db9ff58) | Aug 18, 2022 |
| Lenovo        | G50-80 80E5                 | [1a392021c7](https://linux-hardware.org/?probe=1a392021c7) | Aug 18, 2022 |
| Lenovo        | G580 20150                  | [3c18536e95](https://linux-hardware.org/?probe=3c18536e95) | Aug 18, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9003287b49](https://linux-hardware.org/?probe=9003287b49) | Aug 17, 2022 |
| Dell          | Latitude 5420               | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6649d66a82](https://linux-hardware.org/?probe=6649d66a82) | Aug 15, 2022 |
| Lenovo        | G50-80 80E5                 | [132a476896](https://linux-hardware.org/?probe=132a476896) | Aug 14, 2022 |
| eMachines     | E725                        | [928cfd8881](https://linux-hardware.org/?probe=928cfd8881) | Aug 13, 2022 |
| eMachines     | E725                        | [e1d0d38a1c](https://linux-hardware.org/?probe=e1d0d38a1c) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [1d7c1c5212](https://linux-hardware.org/?probe=1d7c1c5212) | Aug 13, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [70b0d2bb45](https://linux-hardware.org/?probe=70b0d2bb45) | Aug 13, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| Acer          | Nitro AN515-55              | [01e6e21efb](https://linux-hardware.org/?probe=01e6e21efb) | Aug 06, 2022 |
| eMachines     | E520 V1.10                  | [a5c7ca58d9](https://linux-hardware.org/?probe=a5c7ca58d9) | Aug 06, 2022 |
| Dell          | Inspiron 15-3567            | [2ac3b9a2f1](https://linux-hardware.org/?probe=2ac3b9a2f1) | Aug 06, 2022 |
| Dell          | Precision 7530              | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | [c6d5fcceee](https://linux-hardware.org/?probe=c6d5fcceee) | Aug 05, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0e067ccc56](https://linux-hardware.org/?probe=0e067ccc56) | Aug 05, 2022 |
| eMachines     | E725                        | [8028786618](https://linux-hardware.org/?probe=8028786618) | Aug 04, 2022 |
| HP            | Notebook                    | [81b05860ab](https://linux-hardware.org/?probe=81b05860ab) | Aug 04, 2022 |
| Apple         | MacBookAir7,2               | [3e5f261f2a](https://linux-hardware.org/?probe=3e5f261f2a) | Aug 04, 2022 |
| HP            | 625                         | [1c59a9a3d3](https://linux-hardware.org/?probe=1c59a9a3d3) | Aug 03, 2022 |
| HP            | 625                         | [02db8f5852](https://linux-hardware.org/?probe=02db8f5852) | Aug 03, 2022 |
| ASUSTek       | X550JX                      | [469c737a9b](https://linux-hardware.org/?probe=469c737a9b) | Aug 03, 2022 |
| eMachines     | E725                        | [fe35b6624b](https://linux-hardware.org/?probe=fe35b6624b) | Aug 02, 2022 |
| eMachines     | E725                        | [25d51b3945](https://linux-hardware.org/?probe=25d51b3945) | Aug 02, 2022 |
| ASUSTek       | X550JX                      | [edf8c765aa](https://linux-hardware.org/?probe=edf8c765aa) | Aug 02, 2022 |
| eMachines     | E520 V1.10                  | [bb16305e18](https://linux-hardware.org/?probe=bb16305e18) | Aug 01, 2022 |
| HP            | EliteBook 8470p             | [a1d5593420](https://linux-hardware.org/?probe=a1d5593420) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| Samsung       | RV415/RV515                 | [5bb2e2b3e9](https://linux-hardware.org/?probe=5bb2e2b3e9) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [0cecb854f4](https://linux-hardware.org/?probe=0cecb854f4) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [5e73e33a77](https://linux-hardware.org/?probe=5e73e33a77) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| HP            | 250 G2                      | [43d1d3ae24](https://linux-hardware.org/?probe=43d1d3ae24) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Lenovo        | Z50-75 80EC                 | [44f505647d](https://linux-hardware.org/?probe=44f505647d) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| MSI           | GF63 Thin 9SC               | [323db48d16](https://linux-hardware.org/?probe=323db48d16) | Jul 27, 2022 |
| Dell          | Vostro 5471                 | [be2f2c9f98](https://linux-hardware.org/?probe=be2f2c9f98) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| eMachines     | E725                        | [ca033cf053](https://linux-hardware.org/?probe=ca033cf053) | Jul 26, 2022 |
| Dell          | Inspiron 15-3567            | [06fd282e9d](https://linux-hardware.org/?probe=06fd282e9d) | Jul 25, 2022 |
| eMachines     | E725                        | [b975298e85](https://linux-hardware.org/?probe=b975298e85) | Jul 25, 2022 |
| Alcor         | Intel Education Tablet      | [a04ad41c5a](https://linux-hardware.org/?probe=a04ad41c5a) | Jul 24, 2022 |
| Alcor         | Intel Education Tablet      | [700f83a555](https://linux-hardware.org/?probe=700f83a555) | Jul 24, 2022 |
| Dell          | Latitude D630               | [a9fc5a41aa](https://linux-hardware.org/?probe=a9fc5a41aa) | Jul 24, 2022 |
| Toshiba       | Satellite C650D             | [50e201ffd2](https://linux-hardware.org/?probe=50e201ffd2) | Jul 24, 2022 |
| Dell          | Latitude D630               | [7476af3363](https://linux-hardware.org/?probe=7476af3363) | Jul 23, 2022 |
| Dell          | Precision 3561              | [ca88539127](https://linux-hardware.org/?probe=ca88539127) | Jul 22, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [e543e58f00](https://linux-hardware.org/?probe=e543e58f00) | Jul 22, 2022 |
| Dell          | Precision M4400             | [cf3bbe255a](https://linux-hardware.org/?probe=cf3bbe255a) | Jul 20, 2022 |
| ASUSTek       | 1215P                       | [3bb44d06d1](https://linux-hardware.org/?probe=3bb44d06d1) | Jul 20, 2022 |
| Dell          | Latitude E6420              | [77501652df](https://linux-hardware.org/?probe=77501652df) | Jul 18, 2022 |
| Dell          | Vostro 3500                 | [27a7c25204](https://linux-hardware.org/?probe=27a7c25204) | Jul 17, 2022 |
| Acer          | Swift SF314-43              | [61b8fb7c41](https://linux-hardware.org/?probe=61b8fb7c41) | Jul 17, 2022 |
| eMachines     | E725                        | [771942dd5e](https://linux-hardware.org/?probe=771942dd5e) | Jul 15, 2022 |
| HP            | 255 G5 Notebook PC          | [86b8dc8c6d](https://linux-hardware.org/?probe=86b8dc8c6d) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [23077c70b2](https://linux-hardware.org/?probe=23077c70b2) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [10192c3d0b](https://linux-hardware.org/?probe=10192c3d0b) | Jul 14, 2022 |
| HP            | 255 G5 Notebook PC          | [fa6486dcd9](https://linux-hardware.org/?probe=fa6486dcd9) | Jul 13, 2022 |
| eMachines     | E725                        | [27fb6a6cab](https://linux-hardware.org/?probe=27fb6a6cab) | Jul 12, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [6998a6fb37](https://linux-hardware.org/?probe=6998a6fb37) | Jul 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | [5a009407d9](https://linux-hardware.org/?probe=5a009407d9) | Jul 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9ae6c29438](https://linux-hardware.org/?probe=9ae6c29438) | Jul 08, 2022 |
| Dell          | Inspiron 1564               | [0fbabbb83d](https://linux-hardware.org/?probe=0fbabbb83d) | Jul 08, 2022 |
| Dell          | Inspiron 3593               | [d34d56c473](https://linux-hardware.org/?probe=d34d56c473) | Jul 05, 2022 |
| Lenovo        | ThinkPad W510 431924G       | [d65b149a5f](https://linux-hardware.org/?probe=d65b149a5f) | Jul 04, 2022 |
| eMachines     | E725                        | [18d7561b19](https://linux-hardware.org/?probe=18d7561b19) | Jul 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [a2df072a44](https://linux-hardware.org/?probe=a2df072a44) | Jul 03, 2022 |
| eMachines     | E725                        | [8ba1579921](https://linux-hardware.org/?probe=8ba1579921) | Jul 01, 2022 |
| eMachines     | E725                        | [874b6bd7de](https://linux-hardware.org/?probe=874b6bd7de) | Jul 01, 2022 |
| eMachines     | E725                        | [021bcca061](https://linux-hardware.org/?probe=021bcca061) | Jun 30, 2022 |
| eMachines     | E725                        | [b8b332e92f](https://linux-hardware.org/?probe=b8b332e92f) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| Dell          | Inspiron 5537               | [9758b4dcff](https://linux-hardware.org/?probe=9758b4dcff) | Jun 30, 2022 |
| HP            | EliteBook 840 G2            | [018b6945e1](https://linux-hardware.org/?probe=018b6945e1) | Jun 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [95db2f9536](https://linux-hardware.org/?probe=95db2f9536) | Jun 27, 2022 |
| eMachines     | E725                        | [3b272a4e25](https://linux-hardware.org/?probe=3b272a4e25) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| Dell          | Latitude E5500              | [8002c78586](https://linux-hardware.org/?probe=8002c78586) | Jun 25, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [8f9e6e12b1](https://linux-hardware.org/?probe=8f9e6e12b1) | Jun 25, 2022 |
| Dell          | Latitude E7450              | [a03ea66786](https://linux-hardware.org/?probe=a03ea66786) | Jun 24, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [a26161ba2f](https://linux-hardware.org/?probe=a26161ba2f) | Jun 23, 2022 |
| Dell          | Latitude D630               | [60c9b1089c](https://linux-hardware.org/?probe=60c9b1089c) | Jun 23, 2022 |
| Dell          | Latitude E5500              | [ad849dbfe7](https://linux-hardware.org/?probe=ad849dbfe7) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f3ebefa03f](https://linux-hardware.org/?probe=f3ebefa03f) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | [d230e8311a](https://linux-hardware.org/?probe=d230e8311a) | Jun 21, 2022 |
| HP            | 255 G5 Notebook PC          | [7d1b0cfc99](https://linux-hardware.org/?probe=7d1b0cfc99) | Jun 21, 2022 |
| eMachines     | E725                        | [6e81be09d2](https://linux-hardware.org/?probe=6e81be09d2) | Jun 19, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [73f958fb35](https://linux-hardware.org/?probe=73f958fb35) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e9eb39efa4](https://linux-hardware.org/?probe=e9eb39efa4) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [bffb7f61cb](https://linux-hardware.org/?probe=bffb7f61cb) | Jun 15, 2022 |
| HP            | x2 210                      | [8f6739cda0](https://linux-hardware.org/?probe=8f6739cda0) | Jun 15, 2022 |
| HP            | ProBook 4540s               | [934a74329f](https://linux-hardware.org/?probe=934a74329f) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | [ad093b7b31](https://linux-hardware.org/?probe=ad093b7b31) | Jun 11, 2022 |
| Dell          | Latitude E6540              | [b1cc75656e](https://linux-hardware.org/?probe=b1cc75656e) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [eb4a496e95](https://linux-hardware.org/?probe=eb4a496e95) | Jun 09, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24b293410c](https://linux-hardware.org/?probe=24b293410c) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| HP            | Compaq 6710b (KE121EA#AK... | [940eb51107](https://linux-hardware.org/?probe=940eb51107) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [fce3696537](https://linux-hardware.org/?probe=fce3696537) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [d2efe762b7](https://linux-hardware.org/?probe=d2efe762b7) | Jun 06, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [5f64f824aa](https://linux-hardware.org/?probe=5f64f824aa) | Jun 05, 2022 |
| Medion        | P6630                       | [c1de1611b8](https://linux-hardware.org/?probe=c1de1611b8) | Jun 04, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b563da5d39](https://linux-hardware.org/?probe=b563da5d39) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [15e4cca5bc](https://linux-hardware.org/?probe=15e4cca5bc) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [b99a9b1bce](https://linux-hardware.org/?probe=b99a9b1bce) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [96768b6e5c](https://linux-hardware.org/?probe=96768b6e5c) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [d11a49f42b](https://linux-hardware.org/?probe=d11a49f42b) | Jun 02, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | [968decd1af](https://linux-hardware.org/?probe=968decd1af) | Jun 02, 2022 |
| Dell          | Latitude E6400              | [cea3337908](https://linux-hardware.org/?probe=cea3337908) | Jun 01, 2022 |
| HP            | 255 G5 Notebook PC          | [4ff7c85a84](https://linux-hardware.org/?probe=4ff7c85a84) | May 31, 2022 |
| HP            | 255 G5 Notebook PC          | [c65fb5ddb9](https://linux-hardware.org/?probe=c65fb5ddb9) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | EliteBook 8470p             | [6b22d31e8e](https://linux-hardware.org/?probe=6b22d31e8e) | May 31, 2022 |
| ASUSTek       | K53U                        | [efd067c3a8](https://linux-hardware.org/?probe=efd067c3a8) | May 30, 2022 |
| ASUSTek       | K53U                        | [a26756238b](https://linux-hardware.org/?probe=a26756238b) | May 30, 2022 |
| Dell          | Latitude E6230              | [068d9b4143](https://linux-hardware.org/?probe=068d9b4143) | May 29, 2022 |
| Dell          | Latitude E6230              | [c50bb14e9a](https://linux-hardware.org/?probe=c50bb14e9a) | May 29, 2022 |
| Medion        | P6630                       | [7f5b714dfc](https://linux-hardware.org/?probe=7f5b714dfc) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | [672f924aec](https://linux-hardware.org/?probe=672f924aec) | May 28, 2022 |
| HP            | 255 G5 Notebook PC          | [7f91291747](https://linux-hardware.org/?probe=7f91291747) | May 28, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [110903519d](https://linux-hardware.org/?probe=110903519d) | May 26, 2022 |
| HP            | 620                         | [b5bf98b16a](https://linux-hardware.org/?probe=b5bf98b16a) | May 23, 2022 |
| HP            | 620                         | [8bf9517a97](https://linux-hardware.org/?probe=8bf9517a97) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [26d3a29dc1](https://linux-hardware.org/?probe=26d3a29dc1) | May 23, 2022 |
| HP            | Presario CQ58               | [bdf8b7e229](https://linux-hardware.org/?probe=bdf8b7e229) | May 22, 2022 |
| HP            | Presario CQ58               | [383a27dd29](https://linux-hardware.org/?probe=383a27dd29) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Lenovo        | B590 20208                  | [b32a821a4c](https://linux-hardware.org/?probe=b32a821a4c) | May 21, 2022 |
| Lenovo        | B590 20208                  | [3386aeef48](https://linux-hardware.org/?probe=3386aeef48) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | [9003466ff8](https://linux-hardware.org/?probe=9003466ff8) | May 21, 2022 |
| Fujitsu       | LIFEBOOK U745               | [2e05001696](https://linux-hardware.org/?probe=2e05001696) | May 21, 2022 |
| HP            | 620                         | [babb1f392a](https://linux-hardware.org/?probe=babb1f392a) | May 21, 2022 |
| Dell          | Vostro 3500                 | [d30a648e90](https://linux-hardware.org/?probe=d30a648e90) | May 19, 2022 |
| Dell          | Inspiron 5759               | [bfe6579a0e](https://linux-hardware.org/?probe=bfe6579a0e) | May 16, 2022 |
| Lenovo        | G570 20079                  | [f4b9c3997d](https://linux-hardware.org/?probe=f4b9c3997d) | May 16, 2022 |
| Toshiba       | Satellite L775-18R          | [ec012c6b3d](https://linux-hardware.org/?probe=ec012c6b3d) | May 16, 2022 |
| Lenovo        | G580 20150                  | [75f2c0ab4e](https://linux-hardware.org/?probe=75f2c0ab4e) | May 15, 2022 |
| Lenovo        | G580 20150                  | [8d710ae7c3](https://linux-hardware.org/?probe=8d710ae7c3) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [758e2b869d](https://linux-hardware.org/?probe=758e2b869d) | May 15, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [91c6da69a9](https://linux-hardware.org/?probe=91c6da69a9) | May 15, 2022 |
| Dell          | Latitude E6430              | [e805d60a6b](https://linux-hardware.org/?probe=e805d60a6b) | May 14, 2022 |
| Dell          | Vostro 3500                 | [f784f7eb95](https://linux-hardware.org/?probe=f784f7eb95) | May 14, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [bfc1a518db](https://linux-hardware.org/?probe=bfc1a518db) | May 14, 2022 |
| HP            | 620                         | [62369d924a](https://linux-hardware.org/?probe=62369d924a) | May 12, 2022 |
| Unknown       | Unknown                     | [0099d17388](https://linux-hardware.org/?probe=0099d17388) | May 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [25787f8eb3](https://linux-hardware.org/?probe=25787f8eb3) | May 10, 2022 |
| Dell          | Latitude E6230              | [d9d1e38394](https://linux-hardware.org/?probe=d9d1e38394) | May 09, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [dd31ac3d4d](https://linux-hardware.org/?probe=dd31ac3d4d) | May 08, 2022 |
| HP            | EliteBook 2560p             | [ef54ce0eda](https://linux-hardware.org/?probe=ef54ce0eda) | May 06, 2022 |
| HP            | EliteBook 2560p             | [94a92586e6](https://linux-hardware.org/?probe=94a92586e6) | May 06, 2022 |
| Lenovo        | ThinkPad T460 20FMS6LB00    | [3d7e88cdae](https://linux-hardware.org/?probe=3d7e88cdae) | May 03, 2022 |
| ASUSTek       | GL552JX                     | [c91f42212d](https://linux-hardware.org/?probe=c91f42212d) | May 03, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [62f1d13e63](https://linux-hardware.org/?probe=62f1d13e63) | May 02, 2022 |
| Lenovo        | ThinkPad X240 20AL00FGMB    | [afba42bf24](https://linux-hardware.org/?probe=afba42bf24) | May 02, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [02872ac9a8](https://linux-hardware.org/?probe=02872ac9a8) | May 02, 2022 |
| HP            | ProBook 645 G4              | [0a4b56ae27](https://linux-hardware.org/?probe=0a4b56ae27) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Dell          | Inspiron 3593               | [54087491d8](https://linux-hardware.org/?probe=54087491d8) | Apr 28, 2022 |
| HP            | ProBook 645 G4              | [1546b59830](https://linux-hardware.org/?probe=1546b59830) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Toshiba       | NB550D                      | [386409d233](https://linux-hardware.org/?probe=386409d233) | Apr 24, 2022 |
| ASUSTek       | GL552JX                     | [dae470212d](https://linux-hardware.org/?probe=dae470212d) | Apr 22, 2022 |
| Acer          | Swift SF114-33              | [93239c624a](https://linux-hardware.org/?probe=93239c624a) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [5a855c522f](https://linux-hardware.org/?probe=5a855c522f) | Apr 22, 2022 |
| HP            | EliteBook 8470p             | [c1623a9f89](https://linux-hardware.org/?probe=c1623a9f89) | Apr 21, 2022 |
| Dell          | Vostro 3580                 | [c34ed29ab2](https://linux-hardware.org/?probe=c34ed29ab2) | Apr 21, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [36e5a2229d](https://linux-hardware.org/?probe=36e5a2229d) | Apr 18, 2022 |
| Lenovo        | B590 20208                  | [af6b076e21](https://linux-hardware.org/?probe=af6b076e21) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | [48b6f0e313](https://linux-hardware.org/?probe=48b6f0e313) | Apr 18, 2022 |
| Hungaro Fl... | Navon Loop 360              | [cde65f88c1](https://linux-hardware.org/?probe=cde65f88c1) | Apr 17, 2022 |
| ASUSTek       | TP201SA                     | [2898b67bff](https://linux-hardware.org/?probe=2898b67bff) | Apr 16, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a89ca51e1b](https://linux-hardware.org/?probe=a89ca51e1b) | Apr 15, 2022 |
| Fujitsu       | LIFEBOOK E743               | [43ee1b9237](https://linux-hardware.org/?probe=43ee1b9237) | Apr 14, 2022 |
| Dell          | G5 5587                     | [b3c44a59f0](https://linux-hardware.org/?probe=b3c44a59f0) | Apr 13, 2022 |
| Dell          | Inspiron 3537               | [88655213a1](https://linux-hardware.org/?probe=88655213a1) | Apr 12, 2022 |
| HP            | ProBook 470 G1              | [ee1f05022a](https://linux-hardware.org/?probe=ee1f05022a) | Apr 10, 2022 |
| Lenovo        | G580 20150                  | [00215e25c0](https://linux-hardware.org/?probe=00215e25c0) | Apr 10, 2022 |
| Dell          | Latitude 7480               | [b235ce5f92](https://linux-hardware.org/?probe=b235ce5f92) | Apr 10, 2022 |
| Fujitsu       | LIFEBOOK U745               | [9dc3653255](https://linux-hardware.org/?probe=9dc3653255) | Apr 09, 2022 |
| Valve         | Jupiter                     | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | [ae77218dcf](https://linux-hardware.org/?probe=ae77218dcf) | Apr 07, 2022 |
| Toshiba       | TECRA A10                   | [b062d23fb7](https://linux-hardware.org/?probe=b062d23fb7) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [a99419647f](https://linux-hardware.org/?probe=a99419647f) | Apr 07, 2022 |
| Lenovo        | ThinkPad T61 6458WK6        | [5303af9863](https://linux-hardware.org/?probe=5303af9863) | Apr 07, 2022 |
| Fujitsu       | LIFEBOOK U745               | [5d73ae026b](https://linux-hardware.org/?probe=5d73ae026b) | Apr 05, 2022 |
| Acer          | Swift SF114-32              | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Acer          | TravelMate P215-52          | [a5d16dc93e](https://linux-hardware.org/?probe=a5d16dc93e) | Apr 03, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [495e271511](https://linux-hardware.org/?probe=495e271511) | Apr 03, 2022 |
| Lenovo        | G50-30 80G0                 | [46775a18b0](https://linux-hardware.org/?probe=46775a18b0) | Apr 03, 2022 |
| Dell          | Latitude E5420              | [a60c1a4785](https://linux-hardware.org/?probe=a60c1a4785) | Apr 03, 2022 |
| Lenovo        | G50-30 80G0                 | [be1de1d236](https://linux-hardware.org/?probe=be1de1d236) | Apr 03, 2022 |
| Lenovo        | G780 20138                  | [a7cad8a09a](https://linux-hardware.org/?probe=a7cad8a09a) | Apr 02, 2022 |
| HP            | Pavilion 15                 | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [8ae9fd4940](https://linux-hardware.org/?probe=8ae9fd4940) | Apr 02, 2022 |
| Acer          | TravelMate P215-52          | [752d283e54](https://linux-hardware.org/?probe=752d283e54) | Apr 01, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [666c8daa31](https://linux-hardware.org/?probe=666c8daa31) | Apr 01, 2022 |
| HP            | Unknown                     | [c6a02a2df5](https://linux-hardware.org/?probe=c6a02a2df5) | Apr 01, 2022 |
| HP            | Unknown                     | [71ae764e9f](https://linux-hardware.org/?probe=71ae764e9f) | Apr 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [1a946533b6](https://linux-hardware.org/?probe=1a946533b6) | Mar 31, 2022 |
| Dell          | Latitude E6420              | [2a0c2610ea](https://linux-hardware.org/?probe=2a0c2610ea) | Mar 30, 2022 |
| eMachines     | E725                        | [475f79831d](https://linux-hardware.org/?probe=475f79831d) | Mar 29, 2022 |
| eMachines     | E725                        | [f8e777c318](https://linux-hardware.org/?probe=f8e777c318) | Mar 29, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [60da33f3aa](https://linux-hardware.org/?probe=60da33f3aa) | Mar 28, 2022 |
| Dell          | System XPS 15Z              | [3e4b6f7b57](https://linux-hardware.org/?probe=3e4b6f7b57) | Mar 28, 2022 |
| Dell          | Latitude E5540              | [838350f357](https://linux-hardware.org/?probe=838350f357) | Mar 28, 2022 |
| Lenovo        | ThinkPad W530 2463A58       | [8e8bd0aad5](https://linux-hardware.org/?probe=8e8bd0aad5) | Mar 28, 2022 |
| Lenovo        | G580 20150                  | [ec430f1afc](https://linux-hardware.org/?probe=ec430f1afc) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [a36af1ef0f](https://linux-hardware.org/?probe=a36af1ef0f) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [c3b9926b94](https://linux-hardware.org/?probe=c3b9926b94) | Mar 27, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | [b557a2005c](https://linux-hardware.org/?probe=b557a2005c) | Mar 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [64606b8247](https://linux-hardware.org/?probe=64606b8247) | Mar 26, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [25ad4e35b9](https://linux-hardware.org/?probe=25ad4e35b9) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c527847cd3](https://linux-hardware.org/?probe=c527847cd3) | Mar 25, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [ed4ed6851f](https://linux-hardware.org/?probe=ed4ed6851f) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| Dell          | Latitude E7450              | [57111f23b4](https://linux-hardware.org/?probe=57111f23b4) | Mar 23, 2022 |
| Dell          | Latitude E7450              | [ad41ea623a](https://linux-hardware.org/?probe=ad41ea623a) | Mar 23, 2022 |
| Lenovo        | G565 20071                  | [40cf723fac](https://linux-hardware.org/?probe=40cf723fac) | Mar 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5b8c4678af](https://linux-hardware.org/?probe=5b8c4678af) | Mar 22, 2022 |
| Acer          | TravelMate P238-G2-M        | [7aa968ca84](https://linux-hardware.org/?probe=7aa968ca84) | Mar 22, 2022 |
| Apple         | MacBookPro6,2               | [5611c90f20](https://linux-hardware.org/?probe=5611c90f20) | Mar 21, 2022 |
| Apple         | MacBookPro6,2               | [2a71c88e71](https://linux-hardware.org/?probe=2a71c88e71) | Mar 21, 2022 |
| Lenovo        | Z50-70 20354                | [85236d7863](https://linux-hardware.org/?probe=85236d7863) | Mar 20, 2022 |
| Lenovo        | Z50-70 20354                | [2391a2db23](https://linux-hardware.org/?probe=2391a2db23) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| Lenovo        | G505s 20255                 | [9f18cfb328](https://linux-hardware.org/?probe=9f18cfb328) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | [716d4ed3be](https://linux-hardware.org/?probe=716d4ed3be) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [6ae5708fe3](https://linux-hardware.org/?probe=6ae5708fe3) | Mar 16, 2022 |
| Fujitsu       | LIFEBOOK U745               | [e8e4e5d953](https://linux-hardware.org/?probe=e8e4e5d953) | Mar 15, 2022 |
| HP            | 650                         | [3266dba7df](https://linux-hardware.org/?probe=3266dba7df) | Mar 14, 2022 |
| HP            | 650                         | [54df12f572](https://linux-hardware.org/?probe=54df12f572) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [79a7c69b79](https://linux-hardware.org/?probe=79a7c69b79) | Mar 13, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [29c3688c05](https://linux-hardware.org/?probe=29c3688c05) | Mar 13, 2022 |
| ASUSTek       | X541UVK                     | [74ba6d5353](https://linux-hardware.org/?probe=74ba6d5353) | Mar 12, 2022 |
| eMachines     | E725                        | [05b157a340](https://linux-hardware.org/?probe=05b157a340) | Mar 12, 2022 |
| Packard Be... | EasyNote TS13SB             | [9d702d33cb](https://linux-hardware.org/?probe=9d702d33cb) | Mar 12, 2022 |
| HP            | Pavilion 17                 | [f5ff2a8a14](https://linux-hardware.org/?probe=f5ff2a8a14) | Mar 10, 2022 |
| HP            | Pavilion 17                 | [b6bfe40827](https://linux-hardware.org/?probe=b6bfe40827) | Mar 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [299209635a](https://linux-hardware.org/?probe=299209635a) | Mar 09, 2022 |
| Dell          | Latitude E6230              | [20ca54a46c](https://linux-hardware.org/?probe=20ca54a46c) | Mar 09, 2022 |
| ASUSTek       | BU401LA                     | [2df54ef02e](https://linux-hardware.org/?probe=2df54ef02e) | Mar 08, 2022 |
| Sony          | SVS13118GBB                 | [64dc07d0af](https://linux-hardware.org/?probe=64dc07d0af) | Mar 08, 2022 |
| Sony          | SVS13118GBB                 | [76afe39f5e](https://linux-hardware.org/?probe=76afe39f5e) | Mar 08, 2022 |
| Dell          | Inspiron 5570               | [c2d75f15a4](https://linux-hardware.org/?probe=c2d75f15a4) | Mar 05, 2022 |
| Dell          | Inspiron 5570               | [8965098d65](https://linux-hardware.org/?probe=8965098d65) | Mar 05, 2022 |
| HP            | Compaq 6710b (GB890EA#AK... | [c313b8ee39](https://linux-hardware.org/?probe=c313b8ee39) | Mar 05, 2022 |
| HP            | Compaq 6720s                | [f83b83214e](https://linux-hardware.org/?probe=f83b83214e) | Mar 04, 2022 |
| HP            | Pavilion dv6700             | [4702dab234](https://linux-hardware.org/?probe=4702dab234) | Mar 04, 2022 |
| Acer          | Aspire A315-57G             | [83f0bbb366](https://linux-hardware.org/?probe=83f0bbb366) | Mar 04, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| Dell          | Latitude E5540              | [0e5ce3685b](https://linux-hardware.org/?probe=0e5ce3685b) | Mar 02, 2022 |
| HP            | Compaq 6720s                | [9d3882f4c5](https://linux-hardware.org/?probe=9d3882f4c5) | Mar 02, 2022 |
| Acer          | Aspire ES1-571              | [acc272ef5a](https://linux-hardware.org/?probe=acc272ef5a) | Feb 28, 2022 |
| Acer          | Aspire ES1-571              | [cf51003466](https://linux-hardware.org/?probe=cf51003466) | Feb 28, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [6875bd20ab](https://linux-hardware.org/?probe=6875bd20ab) | Feb 28, 2022 |
| Dell          | Latitude 5480               | [43ae797918](https://linux-hardware.org/?probe=43ae797918) | Feb 28, 2022 |
| ASUSTek       | K53U                        | [16c5ebe7c3](https://linux-hardware.org/?probe=16c5ebe7c3) | Feb 27, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [5f74ba2ea7](https://linux-hardware.org/?probe=5f74ba2ea7) | Feb 27, 2022 |
| Dell          | Inspiron 3583               | [83dec4f285](https://linux-hardware.org/?probe=83dec4f285) | Feb 26, 2022 |
| HP            | ProBook 6470b               | [76e9b5f896](https://linux-hardware.org/?probe=76e9b5f896) | Feb 26, 2022 |
| HP            | ProBook 6470b               | [3b86510929](https://linux-hardware.org/?probe=3b86510929) | Feb 26, 2022 |
| HP            | ProBook 430 G5              | [1cf6d56319](https://linux-hardware.org/?probe=1cf6d56319) | Feb 25, 2022 |
| HP            | Laptop 14s-fq0xxx           | [8e06c09393](https://linux-hardware.org/?probe=8e06c09393) | Feb 25, 2022 |
| HP            | Pavilion 17                 | [97c44abef4](https://linux-hardware.org/?probe=97c44abef4) | Feb 22, 2022 |
| Medion        | Erazer P7647 MD60803        | [e958bf729a](https://linux-hardware.org/?probe=e958bf729a) | Feb 22, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [80ceccfdc7](https://linux-hardware.org/?probe=80ceccfdc7) | Feb 22, 2022 |
| eMachines     | E725                        | [4aa5e2b180](https://linux-hardware.org/?probe=4aa5e2b180) | Feb 21, 2022 |
| Dell          | Latitude D630               | [067e57eab9](https://linux-hardware.org/?probe=067e57eab9) | Feb 20, 2022 |
| Packard Be... | EasyNote ENLG81BA           | [fb281e6c00](https://linux-hardware.org/?probe=fb281e6c00) | Feb 20, 2022 |
| Packard Be... | EasyNote ENLG81BA           | [58e5e2c95c](https://linux-hardware.org/?probe=58e5e2c95c) | Feb 20, 2022 |
| Dell          | Inspiron 7737               | [cc09141607](https://linux-hardware.org/?probe=cc09141607) | Feb 19, 2022 |
| Acer          | Aspire E5-571G              | [276c87bdc5](https://linux-hardware.org/?probe=276c87bdc5) | Feb 19, 2022 |
| ASUSTek       | X550VX                      | [2cf18df101](https://linux-hardware.org/?probe=2cf18df101) | Feb 19, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [ab91a058c0](https://linux-hardware.org/?probe=ab91a058c0) | Feb 19, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [70ab79b3b4](https://linux-hardware.org/?probe=70ab79b3b4) | Feb 19, 2022 |
| Lenovo        | ThinkPad T470 20HES18R2G    | [bb387d7a5a](https://linux-hardware.org/?probe=bb387d7a5a) | Feb 18, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [dc8d1eb5eb](https://linux-hardware.org/?probe=dc8d1eb5eb) | Feb 18, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [58b92a0176](https://linux-hardware.org/?probe=58b92a0176) | Feb 18, 2022 |
| HP            | ProBook 6470b               | [4c37154dc3](https://linux-hardware.org/?probe=4c37154dc3) | Feb 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [a7afdd9d95](https://linux-hardware.org/?probe=a7afdd9d95) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [c896752de0](https://linux-hardware.org/?probe=c896752de0) | Feb 17, 2022 |
| HP            | Pavilion 17                 | [166e1147d2](https://linux-hardware.org/?probe=166e1147d2) | Feb 17, 2022 |
| Dell          | XPS 13 7390                 | [5bca4c6855](https://linux-hardware.org/?probe=5bca4c6855) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c5eab4c7d9](https://linux-hardware.org/?probe=c5eab4c7d9) | Feb 16, 2022 |
| HP            | EliteBook 8570w             | [bdfcf410e6](https://linux-hardware.org/?probe=bdfcf410e6) | Feb 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [23e6094c83](https://linux-hardware.org/?probe=23e6094c83) | Feb 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a0a9cf96a8](https://linux-hardware.org/?probe=a0a9cf96a8) | Feb 15, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [357881c642](https://linux-hardware.org/?probe=357881c642) | Feb 15, 2022 |
| Acer          | Aspire 7750G                | [fa1880e655](https://linux-hardware.org/?probe=fa1880e655) | Feb 15, 2022 |
| Dell          | Latitude D630               | [17929b78ff](https://linux-hardware.org/?probe=17929b78ff) | Feb 15, 2022 |
| HP            | Presario CQ57               | [14148f0279](https://linux-hardware.org/?probe=14148f0279) | Feb 15, 2022 |
| HP            | 620                         | [bd89b469e4](https://linux-hardware.org/?probe=bd89b469e4) | Feb 14, 2022 |
| HP            | Compaq 6530b (NJ641UC#AB... | [1cfe8d6cc4](https://linux-hardware.org/?probe=1cfe8d6cc4) | Feb 14, 2022 |
| HP            | 250 G1                      | [0c35eb7e0c](https://linux-hardware.org/?probe=0c35eb7e0c) | Feb 14, 2022 |
| HP            | 250 G1                      | [0e47dcd6ff](https://linux-hardware.org/?probe=0e47dcd6ff) | Feb 14, 2022 |
| Lenovo        | ThinkPad T410 2537VFQ       | [004fd97714](https://linux-hardware.org/?probe=004fd97714) | Feb 13, 2022 |
| Lenovo        | 3000 N500 423332G           | [5f673420ca](https://linux-hardware.org/?probe=5f673420ca) | Feb 13, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | [a3f36901a2](https://linux-hardware.org/?probe=a3f36901a2) | Feb 13, 2022 |
| HP            | Pavilion 17                 | [7e4c073be5](https://linux-hardware.org/?probe=7e4c073be5) | Feb 13, 2022 |
| Lenovo        | ThinkPad W510 4876A46       | [d4b8bb3ed1](https://linux-hardware.org/?probe=d4b8bb3ed1) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | [a84f254fbc](https://linux-hardware.org/?probe=a84f254fbc) | Feb 12, 2022 |
| HP            | EliteBook 745 G3            | [26ed6eddae](https://linux-hardware.org/?probe=26ed6eddae) | Feb 12, 2022 |
| Lenovo        | G50-30 80G0                 | [a72bae3658](https://linux-hardware.org/?probe=a72bae3658) | Feb 12, 2022 |
| Lenovo        | 3000 N500 423332G           | [aa5079471b](https://linux-hardware.org/?probe=aa5079471b) | Feb 12, 2022 |
| Acer          | TravelMate 8571             | [df168b8134](https://linux-hardware.org/?probe=df168b8134) | Feb 11, 2022 |
| Acer          | TravelMate 8571             | [c8493474f0](https://linux-hardware.org/?probe=c8493474f0) | Feb 11, 2022 |
| Acer          | Swift SF314-43              | [fe2ff58a88](https://linux-hardware.org/?probe=fe2ff58a88) | Feb 10, 2022 |
| Acer          | Predator PH517-51           | [de32d3b86d](https://linux-hardware.org/?probe=de32d3b86d) | Feb 10, 2022 |
| Acer          | F                           | [a5dd4a459a](https://linux-hardware.org/?probe=a5dd4a459a) | Feb 10, 2022 |
| HP            | EliteBook 745 G3            | [21d3c81852](https://linux-hardware.org/?probe=21d3c81852) | Feb 10, 2022 |
| HP            | 620                         | [7648e2fd3d](https://linux-hardware.org/?probe=7648e2fd3d) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [4906efe7f4](https://linux-hardware.org/?probe=4906efe7f4) | Feb 09, 2022 |
| Acer          | Nitro AN515-42              | [52d6fa9b66](https://linux-hardware.org/?probe=52d6fa9b66) | Feb 09, 2022 |
| Sony          | VPCEB4M1E                   | [373127eb11](https://linux-hardware.org/?probe=373127eb11) | Feb 09, 2022 |
| ASUSTek       | X550VX                      | [8fd69ee74c](https://linux-hardware.org/?probe=8fd69ee74c) | Feb 09, 2022 |
| Dell          | Latitude 5480               | [0d2e568733](https://linux-hardware.org/?probe=0d2e568733) | Feb 09, 2022 |
| Lenovo        | G50-30 80G0                 | [b05f08f7d5](https://linux-hardware.org/?probe=b05f08f7d5) | Feb 08, 2022 |
| ASUSTek       | X541UVK                     | [c4556ed732](https://linux-hardware.org/?probe=c4556ed732) | Feb 08, 2022 |
| Dell          | Inspiron 5558               | [72501fb765](https://linux-hardware.org/?probe=72501fb765) | Feb 08, 2022 |
| Dell          | Latitude E5520m             | [0e5f84866b](https://linux-hardware.org/?probe=0e5f84866b) | Feb 07, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [136f9d4c89](https://linux-hardware.org/?probe=136f9d4c89) | Feb 07, 2022 |
| ASUSTek       | X541UVK                     | [f293b3a040](https://linux-hardware.org/?probe=f293b3a040) | Feb 07, 2022 |
| Dell          | Inspiron 15-3567            | [e897975636](https://linux-hardware.org/?probe=e897975636) | Feb 06, 2022 |
| Sony          | SVE1511A1EW                 | [74ce3aa5bf](https://linux-hardware.org/?probe=74ce3aa5bf) | Feb 06, 2022 |
| Dell          | Latitude D630               | [553512c6fa](https://linux-hardware.org/?probe=553512c6fa) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [14cfb63e15](https://linux-hardware.org/?probe=14cfb63e15) | Feb 06, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [9a75091962](https://linux-hardware.org/?probe=9a75091962) | Feb 04, 2022 |
| HP            | 650                         | [63c7a9f5bc](https://linux-hardware.org/?probe=63c7a9f5bc) | Feb 03, 2022 |
| Dell          | Vostro 3558                 | [de621c4916](https://linux-hardware.org/?probe=de621c4916) | Feb 02, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [42fa6dc2c1](https://linux-hardware.org/?probe=42fa6dc2c1) | Feb 02, 2022 |
| Dell          | Inspiron 3521               | [6a7e1e173a](https://linux-hardware.org/?probe=6a7e1e173a) | Feb 01, 2022 |
| Sony          | SVS13118GBB                 | [44ef5a252e](https://linux-hardware.org/?probe=44ef5a252e) | Feb 01, 2022 |
| HP            | Unknown                     | [6aa3eb854c](https://linux-hardware.org/?probe=6aa3eb854c) | Jan 31, 2022 |
| ASUSTek       | X541UVK                     | [e923d26564](https://linux-hardware.org/?probe=e923d26564) | Jan 30, 2022 |
| ASUSTek       | X541UVK                     | [01a2239429](https://linux-hardware.org/?probe=01a2239429) | Jan 30, 2022 |
| ASUSTek       | X541UVK                     | [d231ae37d8](https://linux-hardware.org/?probe=d231ae37d8) | Jan 29, 2022 |
| Dell          | System Vostro 3750          | [de27492af3](https://linux-hardware.org/?probe=de27492af3) | Jan 29, 2022 |
| Dell          | Latitude E6530              | [b47cc45b54](https://linux-hardware.org/?probe=b47cc45b54) | Jan 29, 2022 |
| Sony          | SVS13118GBB                 | [1e7063ddb5](https://linux-hardware.org/?probe=1e7063ddb5) | Jan 28, 2022 |
| HP            | 250 G6 Notebook PC          | [1168d4d65b](https://linux-hardware.org/?probe=1168d4d65b) | Jan 28, 2022 |
| HP            | 250 G6 Notebook PC          | [975facb986](https://linux-hardware.org/?probe=975facb986) | Jan 28, 2022 |
| Lenovo        | ThinkPad T61 6458Y56        | [4cef262fd4](https://linux-hardware.org/?probe=4cef262fd4) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | G3 3579                     | [c869de19b3](https://linux-hardware.org/?probe=c869de19b3) | Jan 27, 2022 |
| Apple         | MacBookPro6,2               | [a2475cad56](https://linux-hardware.org/?probe=a2475cad56) | Jan 27, 2022 |
| HP            | ProBook 6470b               | [81afdce4bb](https://linux-hardware.org/?probe=81afdce4bb) | Jan 27, 2022 |
| Acer          | Aspire F5-573G              | [83dcbe0d18](https://linux-hardware.org/?probe=83dcbe0d18) | Jan 27, 2022 |
| ASUSTek       | X550VX                      | [a92b98a4cf](https://linux-hardware.org/?probe=a92b98a4cf) | Jan 26, 2022 |
| Insyde        | Braswell                    | [0d8764b0d5](https://linux-hardware.org/?probe=0d8764b0d5) | Jan 26, 2022 |
| HP            | EliteBook 850 G5            | [a780b76d00](https://linux-hardware.org/?probe=a780b76d00) | Jan 25, 2022 |
| HP            | EliteBook 850 G5            | [47a78966be](https://linux-hardware.org/?probe=47a78966be) | Jan 25, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [242f7d0fec](https://linux-hardware.org/?probe=242f7d0fec) | Jan 25, 2022 |
| Insyde        | Braswell                    | [c082266f28](https://linux-hardware.org/?probe=c082266f28) | Jan 25, 2022 |
| Acer          | Aspire F5-573G              | [51f8947e68](https://linux-hardware.org/?probe=51f8947e68) | Jan 25, 2022 |
| HP            | ProBook 6470b               | [820d0a16ea](https://linux-hardware.org/?probe=820d0a16ea) | Jan 24, 2022 |
| ASUSTek       | GL553VW                     | [7713319e74](https://linux-hardware.org/?probe=7713319e74) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| HP            | ProBook 650 G3              | [32fcb78172](https://linux-hardware.org/?probe=32fcb78172) | Jan 23, 2022 |
| Dell          | Inspiron M5030              | [0918a672e0](https://linux-hardware.org/?probe=0918a672e0) | Jan 22, 2022 |
| Lenovo        | ThinkPad L420 78544UG       | [26c13c7d16](https://linux-hardware.org/?probe=26c13c7d16) | Jan 22, 2022 |
| Lenovo        | ThinkPad L420 78544UG       | [dc6c0d3559](https://linux-hardware.org/?probe=dc6c0d3559) | Jan 22, 2022 |
| ASUSTek       | K50IN                       | [64a1640588](https://linux-hardware.org/?probe=64a1640588) | Jan 21, 2022 |
| ASUSTek       | K50IN                       | [43c8a1b1ec](https://linux-hardware.org/?probe=43c8a1b1ec) | Jan 21, 2022 |
| Dell          | Inspiron 5558               | [fc8a233818](https://linux-hardware.org/?probe=fc8a233818) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [df25e2a6d4](https://linux-hardware.org/?probe=df25e2a6d4) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [7439a5647b](https://linux-hardware.org/?probe=7439a5647b) | Jan 21, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [cdda13eba7](https://linux-hardware.org/?probe=cdda13eba7) | Jan 20, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [88150d957e](https://linux-hardware.org/?probe=88150d957e) | Jan 20, 2022 |
| Acer          | Swift SF314-42              | [af81e6fd78](https://linux-hardware.org/?probe=af81e6fd78) | Jan 20, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [1d9c3b162d](https://linux-hardware.org/?probe=1d9c3b162d) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [87bd7d315f](https://linux-hardware.org/?probe=87bd7d315f) | Jan 18, 2022 |
| Lenovo        | ThinkPad L470 20J5S2RA00    | [81d06b1028](https://linux-hardware.org/?probe=81d06b1028) | Jan 18, 2022 |
| HP            | EliteBook 8440p             | [eea8c3a5c3](https://linux-hardware.org/?probe=eea8c3a5c3) | Jan 18, 2022 |
| Lenovo        | G40-45 80E1                 | [4bdc747bd4](https://linux-hardware.org/?probe=4bdc747bd4) | Jan 18, 2022 |
| HP            | EliteBook 8440p             | [a3133c9aab](https://linux-hardware.org/?probe=a3133c9aab) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | [42a841fb5b](https://linux-hardware.org/?probe=42a841fb5b) | Jan 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [10983d5883](https://linux-hardware.org/?probe=10983d5883) | Jan 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0bd3f0c6c1](https://linux-hardware.org/?probe=0bd3f0c6c1) | Jan 17, 2022 |
| HP            | EliteBook 745 G3            | [7e44b8f1f8](https://linux-hardware.org/?probe=7e44b8f1f8) | Jan 16, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [7b614a5d11](https://linux-hardware.org/?probe=7b614a5d11) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [30c367f8ca](https://linux-hardware.org/?probe=30c367f8ca) | Jan 15, 2022 |
| Packard Be... | EasyNote TK37               | [4b9de8a4a2](https://linux-hardware.org/?probe=4b9de8a4a2) | Jan 15, 2022 |
| Acer          | Aspire A315-51              | [841d415fa4](https://linux-hardware.org/?probe=841d415fa4) | Jan 15, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [0d267e1823](https://linux-hardware.org/?probe=0d267e1823) | Jan 15, 2022 |
| ASUSTek       | X542UN                      | [f27ec23965](https://linux-hardware.org/?probe=f27ec23965) | Jan 15, 2022 |
| Packard Be... | EasyNote TK37               | [b511ea2a93](https://linux-hardware.org/?probe=b511ea2a93) | Jan 14, 2022 |
| Packard Be... | EasyNote TK37               | [28b9c9ef8e](https://linux-hardware.org/?probe=28b9c9ef8e) | Jan 14, 2022 |
| HP            | 255 G5 Notebook PC          | [6f20015e15](https://linux-hardware.org/?probe=6f20015e15) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440 20B7S00H01    | [1bdc5dc298](https://linux-hardware.org/?probe=1bdc5dc298) | Jan 11, 2022 |
| MSI           | GF63 Thin 9SC               | [0914f76b4d](https://linux-hardware.org/?probe=0914f76b4d) | Jan 11, 2022 |
| Lenovo        | ThinkPad T500 2056CL8       | [ef244e06d3](https://linux-hardware.org/?probe=ef244e06d3) | Jan 10, 2022 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [81f7bfbced](https://linux-hardware.org/?probe=81f7bfbced) | Jan 10, 2022 |
| ASUSTek       | K53U                        | [d39f634e72](https://linux-hardware.org/?probe=d39f634e72) | Jan 10, 2022 |
| ASUSTek       | K53U                        | [a174ee5aa1](https://linux-hardware.org/?probe=a174ee5aa1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T420 42361P0       | [01499828ce](https://linux-hardware.org/?probe=01499828ce) | Jan 09, 2022 |
| Dell          | Latitude E6430              | [e25ec7e140](https://linux-hardware.org/?probe=e25ec7e140) | Jan 09, 2022 |
| Acer          | Aspire ES1-532G             | [7cecf04619](https://linux-hardware.org/?probe=7cecf04619) | Jan 09, 2022 |
| Acer          | Aspire ES1-532G             | [d2dfc8da4c](https://linux-hardware.org/?probe=d2dfc8da4c) | Jan 09, 2022 |
| Acer          | Aspire E1-571               | [c4d40f6344](https://linux-hardware.org/?probe=c4d40f6344) | Jan 08, 2022 |
| HP            | EliteBook 745 G3            | [5300368575](https://linux-hardware.org/?probe=5300368575) | Jan 08, 2022 |
| Acer          | Aspire F5-573G              | [719238f99c](https://linux-hardware.org/?probe=719238f99c) | Jan 08, 2022 |
| Acer          | Aspire F5-573G              | [3d833877a7](https://linux-hardware.org/?probe=3d833877a7) | Jan 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [8e4bf2cdb1](https://linux-hardware.org/?probe=8e4bf2cdb1) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e6501cd7df](https://linux-hardware.org/?probe=e6501cd7df) | Jan 08, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [ac0e3dfe29](https://linux-hardware.org/?probe=ac0e3dfe29) | Jan 07, 2022 |
| Dell          | Latitude 5480               | [8a88e72831](https://linux-hardware.org/?probe=8a88e72831) | Jan 05, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c1f08a0773](https://linux-hardware.org/?probe=c1f08a0773) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c52ca0986f](https://linux-hardware.org/?probe=c52ca0986f) | Jan 04, 2022 |
| ASUSTek       | X541UAK                     | [bd5145c8b1](https://linux-hardware.org/?probe=bd5145c8b1) | Jan 03, 2022 |
| ASUSTek       | GL552JX                     | [248ec86597](https://linux-hardware.org/?probe=248ec86597) | Jan 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [1c550c0bba](https://linux-hardware.org/?probe=1c550c0bba) | Jan 02, 2022 |
| Dell          | Inspiron 1525               | [11ecdbec1b](https://linux-hardware.org/?probe=11ecdbec1b) | Jan 02, 2022 |
| Dell          | Inspiron 1525               | [c1c0a04b87](https://linux-hardware.org/?probe=c1c0a04b87) | Jan 02, 2022 |
| HP            | EliteBook 820 G1            | [a474addf38](https://linux-hardware.org/?probe=a474addf38) | Jan 01, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Dell          | Vostro 3500                 | [5ec7cee601](https://linux-hardware.org/?probe=5ec7cee601) | Jan 01, 2022 |
| Lenovo        | ThinkPad W510 431924G       | [c0ef5f6b84](https://linux-hardware.org/?probe=c0ef5f6b84) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | [84ca821541](https://linux-hardware.org/?probe=84ca821541) | Dec 29, 2021 |
| ASUSTek       | GL503VD                     | [8918ebec98](https://linux-hardware.org/?probe=8918ebec98) | Dec 28, 2021 |
| ASUSTek       | GL503VD                     | [3ef04a0fe1](https://linux-hardware.org/?probe=3ef04a0fe1) | Dec 27, 2021 |
| HP            | 15                          | [76fef17b30](https://linux-hardware.org/?probe=76fef17b30) | Dec 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [988628f6b6](https://linux-hardware.org/?probe=988628f6b6) | Dec 25, 2021 |
| HP            | 650                         | [339ab3e2d2](https://linux-hardware.org/?probe=339ab3e2d2) | Dec 25, 2021 |
| Dell          | Latitude E6510              | [1fa89129c0](https://linux-hardware.org/?probe=1fa89129c0) | Dec 24, 2021 |
| Dell          | Latitude E6410              | [0588df88b2](https://linux-hardware.org/?probe=0588df88b2) | Dec 24, 2021 |
| Dell          | Latitude E6410              | [c30a066afc](https://linux-hardware.org/?probe=c30a066afc) | Dec 24, 2021 |
| Dell          | Inspiron 5502               | [020519cdfe](https://linux-hardware.org/?probe=020519cdfe) | Dec 24, 2021 |
| Acer          | Extensa 215-51K             | [eb7ebb463b](https://linux-hardware.org/?probe=eb7ebb463b) | Dec 23, 2021 |
| Mediacom      | GTZS                        | [d462097cdd](https://linux-hardware.org/?probe=d462097cdd) | Dec 23, 2021 |
| Dell          | Precision M6600             | [6be07fde65](https://linux-hardware.org/?probe=6be07fde65) | Dec 23, 2021 |
| Dell          | Precision M6600             | [a4f1415897](https://linux-hardware.org/?probe=a4f1415897) | Dec 23, 2021 |
| Medion        | E7218                       | [8d6ee5cd3e](https://linux-hardware.org/?probe=8d6ee5cd3e) | Dec 23, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [f34a512b46](https://linux-hardware.org/?probe=f34a512b46) | Dec 22, 2021 |
| Medion        | E7218                       | [6b930af32f](https://linux-hardware.org/?probe=6b930af32f) | Dec 22, 2021 |
| ASUSTek       | K53BY                       | [c699d6fcd9](https://linux-hardware.org/?probe=c699d6fcd9) | Dec 22, 2021 |
| HP            | EliteBook 8570w             | [3d19abb9a8](https://linux-hardware.org/?probe=3d19abb9a8) | Dec 22, 2021 |
| Acer          | Aspire 3050                 | [888f7795aa](https://linux-hardware.org/?probe=888f7795aa) | Dec 22, 2021 |
| Acer          | Aspire 3050                 | [cfec9fece6](https://linux-hardware.org/?probe=cfec9fece6) | Dec 21, 2021 |
| Mediacom      | GTZS                        | [3694d520f6](https://linux-hardware.org/?probe=3694d520f6) | Dec 20, 2021 |
| Acer          | TP-W701P-53334G1            | [674f2996b5](https://linux-hardware.org/?probe=674f2996b5) | Dec 19, 2021 |
| Acer          | Aspire ES1-532G             | [cf832b7bf6](https://linux-hardware.org/?probe=cf832b7bf6) | Dec 19, 2021 |
| Acer          | Aspire ES1-532G             | [23d3dd911d](https://linux-hardware.org/?probe=23d3dd911d) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| Dell          | Latitude E6430              | [5b026ea45f](https://linux-hardware.org/?probe=5b026ea45f) | Dec 19, 2021 |
| Dell          | Latitude E6430              | [ae951db282](https://linux-hardware.org/?probe=ae951db282) | Dec 18, 2021 |
| ASUSTek       | X550VX                      | [db3cd6403d](https://linux-hardware.org/?probe=db3cd6403d) | Dec 16, 2021 |
| Dell          | Precision M2800             | [0a3b99488f](https://linux-hardware.org/?probe=0a3b99488f) | Dec 11, 2021 |
| Lenovo        | ThinkPad W530 24475HG       | [00379f5e66](https://linux-hardware.org/?probe=00379f5e66) | Dec 10, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| Dell          | Latitude E6420              | [51073dcf26](https://linux-hardware.org/?probe=51073dcf26) | Dec 05, 2021 |
| Dell          | Latitude E6420              | [6826928218](https://linux-hardware.org/?probe=6826928218) | Dec 05, 2021 |
| MSI           | CX600                       | [38b84f0feb](https://linux-hardware.org/?probe=38b84f0feb) | Dec 05, 2021 |
| Acer          | Swift SF114-32              | [06324a46eb](https://linux-hardware.org/?probe=06324a46eb) | Dec 05, 2021 |
| Dell          | Latitude 5480               | [412919400e](https://linux-hardware.org/?probe=412919400e) | Dec 05, 2021 |
| Dell          | Inspiron 15-3567            | [26a01c28fa](https://linux-hardware.org/?probe=26a01c28fa) | Dec 05, 2021 |
| Dell          | Inspiron 15-3567            | [bb8b782ef0](https://linux-hardware.org/?probe=bb8b782ef0) | Dec 05, 2021 |
| Lenovo        | G500 20236                  | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| Dell          | Latitude 5410               | [af7b378137](https://linux-hardware.org/?probe=af7b378137) | Dec 05, 2021 |
| Dell          | Latitude 5410               | [0d992a9be7](https://linux-hardware.org/?probe=0d992a9be7) | Dec 05, 2021 |
| Dell          | Latitude D630               | [718e2268fa](https://linux-hardware.org/?probe=718e2268fa) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [496443510d](https://linux-hardware.org/?probe=496443510d) | Dec 04, 2021 |
| Lenovo        | ThinkPad T61 6458WK6        | [e24ba2f637](https://linux-hardware.org/?probe=e24ba2f637) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| Dell          | Latitude 5480               | [d1a9d603a9](https://linux-hardware.org/?probe=d1a9d603a9) | Nov 30, 2021 |
| Acer          | Swift SF314-43              | [01ce77a927](https://linux-hardware.org/?probe=01ce77a927) | Nov 30, 2021 |
| Apple         | MacBookPro5,5               | [c32c22a4b9](https://linux-hardware.org/?probe=c32c22a4b9) | Nov 30, 2021 |
| Apple         | MacBookPro5,5               | [01a1e9ffb0](https://linux-hardware.org/?probe=01a1e9ffb0) | Nov 30, 2021 |
| Acer          | Aspire 5930                 | [17eed17c54](https://linux-hardware.org/?probe=17eed17c54) | Nov 29, 2021 |
| Acer          | Aspire 5930                 | [9a4712d7ad](https://linux-hardware.org/?probe=9a4712d7ad) | Nov 29, 2021 |
| Dell          | Latitude E6430              | [39087042b7](https://linux-hardware.org/?probe=39087042b7) | Nov 28, 2021 |
| Dell          | Latitude 5480               | [70e231854b](https://linux-hardware.org/?probe=70e231854b) | Nov 28, 2021 |
| HP            | ZBook Studio G4             | [eb3da87330](https://linux-hardware.org/?probe=eb3da87330) | Nov 27, 2021 |
| HP            | EliteBook 8540p             | [38dd850a7c](https://linux-hardware.org/?probe=38dd850a7c) | Nov 26, 2021 |
| HP            | EliteBook 8540p             | [e6df5b59a8](https://linux-hardware.org/?probe=e6df5b59a8) | Nov 26, 2021 |
| BenQ          | Joybook A52                 | [f11e0f093f](https://linux-hardware.org/?probe=f11e0f093f) | Nov 26, 2021 |
| Lenovo        | G40-45 80E1                 | [0460c1b728](https://linux-hardware.org/?probe=0460c1b728) | Nov 25, 2021 |
| Dell          | Latitude 5480               | [c2079e6c03](https://linux-hardware.org/?probe=c2079e6c03) | Nov 23, 2021 |
| HP            | ProBook 4330s               | [74e6151748](https://linux-hardware.org/?probe=74e6151748) | Nov 23, 2021 |
| Dell          | Latitude E6230              | [5df4406c5b](https://linux-hardware.org/?probe=5df4406c5b) | Nov 23, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b8d8d8e85e](https://linux-hardware.org/?probe=b8d8d8e85e) | Nov 23, 2021 |
| Fujitsu       | STYLISTIC Q702              | [b874076152](https://linux-hardware.org/?probe=b874076152) | Nov 22, 2021 |
| Dell          | Latitude E6410              | [20e60e8531](https://linux-hardware.org/?probe=20e60e8531) | Nov 22, 2021 |
| Dell          | Latitude E6410              | [96a9008d41](https://linux-hardware.org/?probe=96a9008d41) | Nov 22, 2021 |
| Toshiba       | NB550D                      | [ff322fa9a1](https://linux-hardware.org/?probe=ff322fa9a1) | Nov 21, 2021 |
| Apple         | MacBookPro6,2               | [33f1433007](https://linux-hardware.org/?probe=33f1433007) | Nov 21, 2021 |
| Lenovo        | G550 20023                  | [531304bd76](https://linux-hardware.org/?probe=531304bd76) | Nov 20, 2021 |
| MSI           | CR610                       | [63411cafc4](https://linux-hardware.org/?probe=63411cafc4) | Nov 20, 2021 |
| MSI           | CR610                       | [6f2f218e21](https://linux-hardware.org/?probe=6f2f218e21) | Nov 20, 2021 |
| HP            | EliteBook 840 G3            | [1a5ca1d992](https://linux-hardware.org/?probe=1a5ca1d992) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| Lenovo        | G550 20023                  | [ce28fd38d4](https://linux-hardware.org/?probe=ce28fd38d4) | Nov 20, 2021 |
| Lenovo        | ThinkPad T530 2429NL6       | [44649d8cb3](https://linux-hardware.org/?probe=44649d8cb3) | Nov 19, 2021 |
| Lenovo        | ThinkPad T530 2429NL6       | [40e07deebb](https://linux-hardware.org/?probe=40e07deebb) | Nov 19, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [2f5c8e09bf](https://linux-hardware.org/?probe=2f5c8e09bf) | Nov 19, 2021 |
| Dell          | Latitude E6410              | [17e575c418](https://linux-hardware.org/?probe=17e575c418) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Dell          | Latitude E7470              | [9fb42a7a17](https://linux-hardware.org/?probe=9fb42a7a17) | Nov 19, 2021 |
| Apple         | MacBookPro6,2               | [0dd964d22b](https://linux-hardware.org/?probe=0dd964d22b) | Nov 18, 2021 |
| Lenovo        | ThinkPad A475 20KMS0EJ00    | [e029652647](https://linux-hardware.org/?probe=e029652647) | Nov 18, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | [855308b39c](https://linux-hardware.org/?probe=855308b39c) | Nov 18, 2021 |
| Fujitsu       | LIFEBOOK U745               | [647cd257ec](https://linux-hardware.org/?probe=647cd257ec) | Nov 18, 2021 |
| Apple         | MacBookPro5,5               | [e56e34b28a](https://linux-hardware.org/?probe=e56e34b28a) | Nov 18, 2021 |
| Apple         | MacBookPro5,5               | [35206eb5d3](https://linux-hardware.org/?probe=35206eb5d3) | Nov 18, 2021 |
| Dell          | Inspiron 5558               | [e86c8890fa](https://linux-hardware.org/?probe=e86c8890fa) | Nov 18, 2021 |
| Lenovo        | ThinkPad A475 20KMS0EJ00    | [26a144a0c7](https://linux-hardware.org/?probe=26a144a0c7) | Nov 17, 2021 |
| Lenovo        | Z50-75 80EC                 | [cbca714862](https://linux-hardware.org/?probe=cbca714862) | Nov 17, 2021 |
| Dell          | Latitude E5430 non-vPro     | [d4cf8a16f2](https://linux-hardware.org/?probe=d4cf8a16f2) | Nov 16, 2021 |
| Dell          | Latitude E5430 non-vPro     | [8d694f749f](https://linux-hardware.org/?probe=8d694f749f) | Nov 16, 2021 |
| Toshiba       | Satellite L750              | [f6ddfdb8ce](https://linux-hardware.org/?probe=f6ddfdb8ce) | Nov 16, 2021 |
| Toshiba       | Satellite L750              | [cc7c9dddca](https://linux-hardware.org/?probe=cc7c9dddca) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Lenovo        | B50-70 20384                | [da69364d7a](https://linux-hardware.org/?probe=da69364d7a) | Nov 16, 2021 |
| Lenovo        | B50-70 20384                | [ec91da9f30](https://linux-hardware.org/?probe=ec91da9f30) | Nov 16, 2021 |
| ASUSTek       | GL753VD                     | [8109914a61](https://linux-hardware.org/?probe=8109914a61) | Nov 16, 2021 |
| Lenovo        | G550 20023                  | [520ebfcf8a](https://linux-hardware.org/?probe=520ebfcf8a) | Nov 16, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Hungary/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| BlackPanther 18.1            | 1038      | 47.9%   |
| Ubuntu 20.04                 | 161       | 7.43%   |
| BlackPanther 16.2            | 158       | 7.29%   |
| Ubuntu 18.04                 | 95        | 4.38%   |
| Ubuntu 22.04                 | 58        | 2.68%   |
| Debian 11                    | 23        | 1.06%   |
| OpenMandriva 4.2             | 21        | 0.97%   |
| Linux Mint 20.2              | 18        | 0.83%   |
| OpenMandriva 4.3             | 17        | 0.78%   |
| Linux Mint 19.3              | 15        | 0.69%   |
| Linux Mint 20.3              | 13        | 0.6%    |
| KDE neon 20.04               | 13        | 0.6%    |
| Arch                         | 13        | 0.6%    |
| Kubuntu 20.04                | 12        | 0.55%   |
| Ubuntu 19.10                 | 11        | 0.51%   |
| ArcoLinux Rolling            | 11        | 0.51%   |
| Zorin 16                     | 10        | 0.46%   |
| Ubuntu 21.10                 | 10        | 0.46%   |
| Ubuntu 21.04                 | 10        | 0.46%   |
| Fedora 36                    | 10        | 0.46%   |
| Fedora 35                    | 10        | 0.46%   |
| Fedora 33                    | 10        | 0.46%   |
| Ubuntu 19.04                 | 9         | 0.42%   |
| Manjaro                      | 9         | 0.42%   |
| Linux Mint 21                | 9         | 0.42%   |
| Linux Mint 20                | 9         | 0.42%   |
| Kubuntu 22.04                | 9         | 0.42%   |
| Fedora 37                    | 9         | 0.42%   |
| Debian 10                    | 9         | 0.42%   |
| Arch Rolling                 | 9         | 0.42%   |
| Xubuntu 18.04                | 8         | 0.37%   |
| Pop!_OS 22.04                | 8         | 0.37%   |
| OpenMandriva 23.01           | 8         | 0.37%   |
| Linux Mint 20.1              | 8         | 0.37%   |
| Endless 3.9.5                | 8         | 0.37%   |
| Xubuntu 20.04                | 7         | 0.32%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.32%   |
| Linux Mint 21.1              | 7         | 0.32%   |
| Zorin 15                     | 6         | 0.28%   |
| Ubuntu Unity 16.04           | 6         | 0.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| BlackPanther  | 1172      | 56.7%   |
| Ubuntu        | 351       | 16.98%  |
| Linux Mint    | 78        | 3.77%   |
| Endless       | 72        | 3.48%   |
| OpenMandriva  | 51        | 2.47%   |
| Fedora        | 48        | 2.32%   |
| Debian        | 40        | 1.94%   |
| Manjaro       | 25        | 1.21%   |
| Kubuntu       | 24        | 1.16%   |
| Pop!_OS       | 22        | 1.06%   |
| Arch          | 21        | 1.02%   |
| Xubuntu       | 20        | 0.97%   |
| KDE neon      | 17        | 0.82%   |
| Zorin         | 16        | 0.77%   |
| ArcoLinux     | 13        | 0.63%   |
| ROSA          | 12        | 0.58%   |
| openSUSE      | 11        | 0.53%   |
| Ubuntu Unity  | 8         | 0.39%   |
| Lubuntu       | 8         | 0.39%   |
| Kali          | 8         | 0.39%   |
| Elementary    | 7         | 0.34%   |
| Ubuntu MATE   | 5         | 0.24%   |
| Ubuntu Budgie | 4         | 0.19%   |
| Gentoo        | 4         | 0.19%   |
| SteamOS       | 3         | 0.15%   |
| Clear Linux   | 3         | 0.15%   |
| UbuntuDDE     | 2         | 0.1%    |
| MX            | 2         | 0.1%    |
| LMDE          | 2         | 0.1%    |
| Devuan        | 2         | 0.1%    |
| Xero          | 1         | 0.05%   |
| UHU           | 1         | 0.05%   |
| Ubuntu Studio | 1         | 0.05%   |
| Solus         | 1         | 0.05%   |
| Rocky Linux   | 1         | 0.05%   |
| PCLinuxOS     | 1         | 0.05%   |
| Parrot        | 1         | 0.05%   |
| Oracle Linux  | 1         | 0.05%   |
| Nobara        | 1         | 0.05%   |
| Garuda Linux  | 1         | 0.05%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 4.18.16-desktop-1bP      | 774       | 32.55%  |
| 5.6.14-desktop-2bP       | 321       | 13.5%   |
| 4.9.20-desktop-pae-1bP   | 149       | 6.27%   |
| 5.1.15-desktop-1bP       | 56        | 2.35%   |
| 5.4.0-42-generic         | 28        | 1.18%   |
| 5.8.0-14-generic         | 22        | 0.93%   |
| 5.10.14-desktop-1omv4002 | 20        | 0.84%   |
| 5.16.7-desktop-1omv4003  | 16        | 0.67%   |
| 5.4.0-58-generic         | 14        | 0.59%   |
| 4.18.0-15-generic        | 14        | 0.59%   |
| 5.3.0-28-generic         | 12        | 0.5%    |
| 5.15.0-43-generic        | 12        | 0.5%    |
| 5.4.0-52-generic         | 11        | 0.46%   |
| 5.4.0-48-generic         | 11        | 0.46%   |
| 5.4.0-19-generic         | 11        | 0.46%   |
| 5.15.0-52-generic        | 11        | 0.46%   |
| 5.11.0-27-generic        | 11        | 0.46%   |
| 5.4.0-40-generic         | 9         | 0.38%   |
| 5.4.0-29-generic         | 9         | 0.38%   |
| 5.15.0-41-generic        | 9         | 0.38%   |
| 5.11.0-34-generic        | 9         | 0.38%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.34%   |
| 5.19.0-35-generic        | 8         | 0.34%   |
| 5.15.0-58-generic        | 8         | 0.34%   |
| 5.4.0-54-generic         | 7         | 0.29%   |
| 5.4.0-26-generic         | 7         | 0.29%   |
| 5.15.0-46-generic        | 7         | 0.29%   |
| 5.8.0-53-generic         | 6         | 0.25%   |
| 5.4.0-91-generic         | 6         | 0.25%   |
| 5.4.0-81-generic         | 6         | 0.25%   |
| 5.4.0-39-generic         | 6         | 0.25%   |
| 5.3.0-23-generic         | 6         | 0.25%   |
| 5.15.0-67-generic        | 6         | 0.25%   |
| 5.15.0-56-generic        | 6         | 0.25%   |
| 5.15.0-53-generic        | 6         | 0.25%   |
| 5.15.0-50-generic        | 6         | 0.25%   |
| 5.15.0-48-generic        | 6         | 0.25%   |
| 5.13.0-27-generic        | 6         | 0.25%   |
| 5.11.0-40-generic        | 6         | 0.25%   |
| 4.15.0-43-generic        | 6         | 0.25%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.16 | 774       | 33.55%  |
| 5.6.14  | 321       | 13.91%  |
| 5.4.0   | 198       | 8.58%   |
| 4.9.20  | 157       | 6.81%   |
| 5.15.0  | 94        | 4.07%   |
| 4.15.0  | 68        | 2.95%   |
| 5.8.0   | 60        | 2.6%    |
| 5.1.15  | 56        | 2.43%   |
| 5.11.0  | 54        | 2.34%   |
| 5.3.0   | 51        | 2.21%   |
| 5.13.0  | 47        | 2.04%   |
| 5.10.0  | 35        | 1.52%   |
| 5.0.0   | 33        | 1.43%   |
| 4.18.0  | 31        | 1.34%   |
| 5.10.14 | 20        | 0.87%   |
| 5.19.0  | 18        | 0.78%   |
| 5.16.7  | 17        | 0.74%   |
| 6.1.1   | 10        | 0.43%   |
| 4.19.0  | 9         | 0.39%   |
| 4.13.0  | 8         | 0.35%   |
| 5.9.0   | 6         | 0.26%   |
| 4.4.0   | 6         | 0.26%   |
| 5.16.0  | 5         | 0.22%   |
| 6.1.0   | 4         | 0.17%   |
| 5.15.12 | 4         | 0.17%   |
| 5.14.0  | 4         | 0.17%   |
| 5.12.9  | 4         | 0.17%   |
| 5.12.4  | 4         | 0.17%   |
| 5.10.7  | 4         | 0.17%   |
| 4.16.0  | 4         | 0.17%   |
| 6.1.12  | 3         | 0.13%   |
| 6.0.12  | 3         | 0.13%   |
| 6.0.0   | 3         | 0.13%   |
| 5.8.16  | 3         | 0.13%   |
| 5.8.14  | 3         | 0.13%   |
| 5.3.18  | 3         | 0.13%   |
| 5.18.13 | 3         | 0.13%   |
| 5.18.0  | 3         | 0.13%   |
| 5.17.1  | 3         | 0.13%   |
| 5.16.2  | 3         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 804       | 35.06%  |
| 5.6     | 331       | 14.44%  |
| 5.4     | 210       | 9.16%   |
| 4.9     | 164       | 7.15%   |
| 5.15    | 111       | 4.84%   |
| 5.8     | 70        | 3.05%   |
| 5.10    | 68        | 2.97%   |
| 4.15    | 68        | 2.97%   |
| 5.11    | 64        | 2.79%   |
| 5.3     | 56        | 2.44%   |
| 5.1     | 56        | 2.44%   |
| 5.13    | 51        | 2.22%   |
| 5.16    | 35        | 1.53%   |
| 5.0     | 33        | 1.44%   |
| 5.19    | 27        | 1.18%   |
| 6.1     | 25        | 1.09%   |
| 5.12    | 15        | 0.65%   |
| 5.9     | 13        | 0.57%   |
| 6.0     | 12        | 0.52%   |
| 5.18    | 12        | 0.52%   |
| 5.14    | 11        | 0.48%   |
| 4.19    | 10        | 0.44%   |
| 5.17    | 9         | 0.39%   |
| 4.13    | 8         | 0.35%   |
| 5.7     | 7         | 0.31%   |
| 4.4     | 6         | 0.26%   |
| 6.2     | 4         | 0.17%   |
| 5.5     | 4         | 0.17%   |
| 4.16    | 4         | 0.17%   |
| 4.7     | 2         | 0.09%   |
| 5.2     | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.1     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1833      | 90.43%  |
| i686   | 194       | 9.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 1281      | 61.76%  |
| GNOME           | 405       | 19.53%  |
| Unknown         | 142       | 6.85%   |
| XFCE            | 61        | 2.94%   |
| X-Cinnamon      | 58        | 2.8%    |
| MATE            | 30        | 1.45%   |
| KDE             | 25        | 1.21%   |
| Cinnamon        | 18        | 0.87%   |
| KDE4            | 9         | 0.43%   |
| Unity           | 8         | 0.39%   |
| Pantheon        | 7         | 0.34%   |
| LXQt            | 7         | 0.34%   |
| Budgie          | 5         | 0.24%   |
| GNOME Flashback | 4         | 0.19%   |
| Deepin          | 4         | 0.19%   |
| i3              | 3         | 0.14%   |
| LXDE            | 2         | 0.1%    |
| qtile           | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| GNOME Classic   | 1         | 0.05%   |
| bspwm           | 1         | 0.05%   |
| awesome         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1823      | 89.14%  |
| Wayland | 129       | 6.31%   |
| Unknown | 88        | 4.3%    |
| Tty     | 5         | 0.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1276      | 61.76%  |
| Unknown | 454       | 21.97%  |
| GDM     | 111       | 5.37%   |
| GDM3    | 96        | 4.65%   |
| LightDM | 81        | 3.92%   |
| TDM     | 34        | 1.65%   |
| KDM     | 9         | 0.44%   |
| SLiM    | 3         | 0.15%   |
| XDM     | 2         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1284      | 62.27%  |
| hu_HU   | 468       | 22.7%   |
| en_US   | 248       | 12.03%  |
| en_GB   | 23        | 1.12%   |
| C       | 15        | 0.73%   |
| de_DE   | 9         | 0.44%   |
| ru_UA   | 3         | 0.15%   |
| ru_RU   | 2         | 0.1%    |
| nl_NL   | 2         | 0.1%    |
| en_AU   | 2         | 0.1%    |
| POSIX   | 1         | 0.05%   |
| it_IT   | 1         | 0.05%   |
| fr_BE   | 1         | 0.05%   |
| en_ZA   | 1         | 0.05%   |
| de_AT   | 1         | 0.05%   |
| C.UTF8  | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1220      | 58.35%  |
| EFI  | 871       | 41.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1214      | 55.59%  |
| Overlay | 824       | 37.73%  |
| Btrfs   | 62        | 2.84%   |
| Unknown | 59        | 2.7%    |
| Xfs     | 6         | 0.27%   |
| Ext3    | 6         | 0.27%   |
| Ext2    | 6         | 0.27%   |
| Zfs     | 4         | 0.18%   |
| F2fs    | 2         | 0.09%   |
| XXXXXXX | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 923       | 43.79%  |
| GPT     | 699       | 33.16%  |
| Unknown | 486       | 23.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1657      | 76.89%  |
| Yes       | 498       | 23.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1220      | 57.49%  |
| Yes       | 902       | 42.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 413       | 20.63%  |
| Hewlett-Packard     | 397       | 19.83%  |
| Dell                | 352       | 17.58%  |
| ASUSTek Computer    | 290       | 14.49%  |
| Acer                | 217       | 10.84%  |
| Toshiba             | 57        | 2.85%   |
| Samsung Electronics | 37        | 1.85%   |
| Fujitsu Siemens     | 35        | 1.75%   |
| Packard Bell        | 29        | 1.45%   |
| Fujitsu             | 29        | 1.45%   |
| MSI                 | 19        | 0.95%   |
| eMachines           | 19        | 0.95%   |
| Sony                | 14        | 0.7%    |
| Medion              | 14        | 0.7%    |
| Apple               | 10        | 0.5%    |
| Alcor               | 8         | 0.4%    |
| Hungaro Flotta Kft  | 7         | 0.35%   |
| HUAWEI              | 6         | 0.3%    |
| Unknown             | 5         | 0.25%   |
| Insyde              | 4         | 0.2%    |
| Timi                | 3         | 0.15%   |
| Intel               | 3         | 0.15%   |
| Clevo               | 3         | 0.15%   |
| Valve               | 2         | 0.1%    |
| TUXEDO              | 2         | 0.1%    |
| speedmaster         | 2         | 0.1%    |
| Panasonic           | 2         | 0.1%    |
| Notebook            | 2         | 0.1%    |
| Gigabyte Technology | 2         | 0.1%    |
| UMAX                | 1         | 0.05%   |
| THD                 | 1         | 0.05%   |
| TCL Communication   | 1         | 0.05%   |
| Phoenix/SiS         | 1         | 0.05%   |
| ordissimo           | 1         | 0.05%   |
| NEC Computers       | 1         | 0.05%   |
| Minix               | 1         | 0.05%   |
| Mediacom            | 1         | 0.05%   |
| LG Electronics      | 1         | 0.05%   |
| IBM                 | 1         | 0.05%   |
| Chiligreen          | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 41        | 2.05%   |
| Dell Latitude E6410                  | 17        | 0.85%   |
| Unknown                              | 14        | 0.7%    |
| HP 650                               | 13        | 0.65%   |
| HP Notebook                          | 12        | 0.6%    |
| Lenovo IdeaPad 330-15IKB 81DE        | 10        | 0.5%    |
| Lenovo IdeaPad 100-15IBD 80QQ        | 10        | 0.5%    |
| Lenovo G50-45 80E3                   | 10        | 0.5%    |
| HP 620                               | 10        | 0.5%    |
| Dell Latitude E6400                  | 9         | 0.45%   |
| Lenovo ThinkPad T400 2768WGB         | 8         | 0.4%    |
| HP Pavilion 15                       | 8         | 0.4%    |
| HP EliteBook 8460p                   | 8         | 0.4%    |
| Dell Latitude E6530                  | 8         | 0.4%    |
| Dell Latitude E6420                  | 8         | 0.4%    |
| Lenovo Z50-75 80EC                   | 7         | 0.35%   |
| Lenovo G550 20023                    | 7         | 0.35%   |
| HP EliteBook 6930p                   | 7         | 0.35%   |
| Dell Inspiron 15-3567                | 7         | 0.35%   |
| ASUS X541NA                          | 7         | 0.35%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.35%   |
| Lenovo Z50-70 20354                  | 6         | 0.3%    |
| Lenovo G580 20150                    | 6         | 0.3%    |
| HP Pavilion g6                       | 6         | 0.3%    |
| HP EliteBook 8470p                   | 6         | 0.3%    |
| HP EliteBook 8440p                   | 6         | 0.3%    |
| HP EliteBook 2560p                   | 6         | 0.3%    |
| eMachines E525                       | 6         | 0.3%    |
| Dell Vostro 15-3568                  | 6         | 0.3%    |
| Dell Latitude E7450                  | 6         | 0.3%    |
| Dell Latitude E6430                  | 6         | 0.3%    |
| Dell Latitude E5420                  | 6         | 0.3%    |
| Dell Latitude D630                   | 6         | 0.3%    |
| Dell Latitude 5480                   | 6         | 0.3%    |
| Dell Inspiron N5110                  | 6         | 0.3%    |
| Dell Inspiron 5558                   | 6         | 0.3%    |
| Dell Inspiron 3542                   | 6         | 0.3%    |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 6         | 0.3%    |
| ASUS K50IJ                           | 6         | 0.3%    |
| ASUS 1011PX                          | 6         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 180       | 8.99%   |
| Dell Latitude            | 175       | 8.74%   |
| Acer Aspire              | 157       | 7.84%   |
| Dell Inspiron            | 110       | 5.49%   |
| Lenovo IdeaPad           | 103       | 5.14%   |
| HP EliteBook             | 89        | 4.45%   |
| HP 250                   | 59        | 2.95%   |
| ASUS VivoBook            | 58        | 2.9%    |
| HP ProBook               | 57        | 2.85%   |
| Toshiba Satellite        | 51        | 2.55%   |
| HP Pavilion              | 39        | 1.95%   |
| HP Compaq                | 36        | 1.8%    |
| Dell Vostro              | 30        | 1.5%    |
| Packard Bell EasyNote    | 29        | 1.45%   |
| Fujitsu LIFEBOOK         | 26        | 1.3%    |
| Fujitsu Siemens AMILO    | 20        | 1%      |
| HP Laptop                | 18        | 0.9%    |
| Acer TravelMate          | 18        | 0.9%    |
| Acer Swift               | 14        | 0.7%    |
| Unknown                  | 14        | 0.7%    |
| HP 650                   | 13        | 0.65%   |
| HP Notebook              | 12        | 0.6%    |
| Dell Precision           | 12        | 0.6%    |
| HP ZBook                 | 11        | 0.55%   |
| ASUS ROG                 | 11        | 0.55%   |
| Lenovo G50-45            | 10        | 0.5%    |
| HP 620                   | 10        | 0.5%    |
| Lenovo 3000              | 9         | 0.45%   |
| Fujitsu Siemens ESPRIMO  | 9         | 0.45%   |
| ASUS ASUS                | 9         | 0.45%   |
| Lenovo G580              | 8         | 0.4%    |
| HP 255                   | 8         | 0.4%    |
| ASUS ZenBook             | 8         | 0.4%    |
| Lenovo Z50-75            | 7         | 0.35%   |
| Lenovo G550              | 7         | 0.35%   |
| Hungaro Flotta Kft Navon | 7         | 0.35%   |
| HP Presario              | 7         | 0.35%   |
| ASUS X541NA              | 7         | 0.35%   |
| Acer Extensa             | 7         | 0.35%   |
| Lenovo Z50-70            | 6         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 206       | 10.29%  |
| 2010    | 181       | 9.04%   |
| 2013    | 178       | 8.89%   |
| 2018    | 162       | 8.09%   |
| 2012    | 146       | 7.29%   |
| 2015    | 134       | 6.69%   |
| 2014    | 128       | 6.39%   |
| 2016    | 127       | 6.34%   |
| 2008    | 126       | 6.29%   |
| 2017    | 123       | 6.14%   |
| 2009    | 116       | 5.79%   |
| 2019    | 95        | 4.75%   |
| 2007    | 95        | 4.75%   |
| 2020    | 71        | 3.55%   |
| 2021    | 44        | 2.2%    |
| 2006    | 37        | 1.85%   |
| 2022    | 19        | 0.95%   |
| 2005    | 11        | 0.55%   |
| Unknown | 3         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2002      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1914      | 95.03%  |
| Enabled  | 100       | 4.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2002      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 711       | 34.43%  |
| 4.01-8.0    | 494       | 23.92%  |
| 8.01-16.0   | 258       | 12.49%  |
| 1.01-2.0    | 241       | 11.67%  |
| 16.01-24.0  | 157       | 7.6%    |
| 2.01-3.0    | 93        | 4.5%    |
| 32.01-64.0  | 65        | 3.15%   |
| 0.51-1.0    | 31        | 1.5%    |
| 24.01-32.0  | 12        | 0.58%   |
| 64.01-256.0 | 2         | 0.1%    |
| 0.01-0.5    | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 821       | 34.92%  |
| 1.01-2.0   | 753       | 32.03%  |
| 2.01-3.0   | 277       | 11.78%  |
| 0.01-0.5   | 192       | 8.17%   |
| 3.01-4.0   | 136       | 5.78%   |
| 4.01-8.0   | 124       | 5.27%   |
| 8.01-16.0  | 43        | 1.83%   |
| 16.01-24.0 | 4         | 0.17%   |
| 32.01-64.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1623      | 77.95%  |
| 2      | 391       | 18.78%  |
| 3      | 42        | 2.02%   |
| 0      | 20        | 0.96%   |
| 4      | 5         | 0.24%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1108      | 54.77%  |
| No        | 915       | 45.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1810      | 90.14%  |
| No        | 198       | 9.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1975      | 98.65%  |
| No        | 27        | 1.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1489      | 73.42%  |
| No        | 539       | 26.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Hungary | 2002      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Budapest          | 832       | 35.53%  |
| Debrecen          | 51        | 2.18%   |
| Miskolc           | 49        | 2.09%   |
| Pécs             | 47        | 2.01%   |
| Szeged            | 46        | 1.96%   |
| Tatabánya        | 42        | 1.79%   |
| Győr             | 40        | 1.71%   |
| Székesfehérvár | 34        | 1.45%   |
| Veszprém         | 30        | 1.28%   |
| Szombathely       | 28        | 1.2%    |
| Kecskemét        | 27        | 1.15%   |
| Nyiregyhaza       | 25        | 1.07%   |
| Érd              | 22        | 0.94%   |
| Zalaegerszeg      | 21        | 0.9%    |
| Szolnok           | 21        | 0.9%    |
| Szigetszentmiklos | 19        | 0.81%   |
| Szekszárd        | 18        | 0.77%   |
| Dunaújváros     | 18        | 0.77%   |
| Toekoel           | 16        | 0.68%   |
| Salgotarjan       | 13        | 0.56%   |
| Szorgalmatos      | 12        | 0.51%   |
| Sopron            | 12        | 0.51%   |
| Pomaz             | 12        | 0.51%   |
| Nagykanizsa       | 12        | 0.51%   |
| Kazincbarcika     | 12        | 0.51%   |
| Kaposvár         | 11        | 0.47%   |
| Gyomro            | 11        | 0.47%   |
| Monor             | 10        | 0.43%   |
| Maglod            | 10        | 0.43%   |
| Kiskunfelegyhaza  | 10        | 0.43%   |
| Hodmezovasarhely  | 10        | 0.43%   |
| Gödöllő        | 10        | 0.43%   |
| Cegled            | 10        | 0.43%   |
| Ajka              | 10        | 0.43%   |
| Tata              | 9         | 0.38%   |
| Oroshaza          | 9         | 0.38%   |
| Karcag            | 9         | 0.38%   |
| Hatvan            | 9         | 0.38%   |
| Békéscsaba      | 9         | 0.38%   |
| Toeroekbalint     | 8         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 371       | 544    | 14.89%  |
| WDC                         | 331       | 468    | 13.28%  |
| Samsung Electronics         | 280       | 422    | 11.24%  |
| Kingston                    | 264       | 380    | 10.59%  |
| Toshiba                     | 253       | 369    | 10.15%  |
| Hitachi                     | 138       | 190    | 5.54%   |
| HGST                        | 133       | 188    | 5.34%   |
| Unknown                     | 94        | 131    | 3.77%   |
| SanDisk                     | 93        | 148    | 3.73%   |
| SK hynix                    | 68        | 99     | 2.73%   |
| Intel                       | 60        | 85     | 2.41%   |
| Fujitsu                     | 44        | 56     | 1.77%   |
| Micron Technology           | 40        | 54     | 1.61%   |
| Crucial                     | 35        | 55     | 1.4%    |
| A-DATA Technology           | 31        | 41     | 1.24%   |
| SPCC                        | 23        | 28     | 0.92%   |
| Apacer                      | 19        | 32     | 0.76%   |
| JMicron Technology          | 17        | 18     | 0.68%   |
| LITEON                      | 13        | 15     | 0.52%   |
| KIOXIA                      | 11        | 12     | 0.44%   |
| PNY                         | 10        | 15     | 0.4%    |
| Kingmax                     | 9         | 9      | 0.36%   |
| China                       | 9         | 18     | 0.36%   |
| Intenso                     | 8         | 18     | 0.32%   |
| Transcend                   | 7         | 7      | 0.28%   |
| Patriot                     | 7         | 9      | 0.28%   |
| LITEONIT                    | 7         | 9      | 0.28%   |
| KingSpec                    | 7         | 8      | 0.28%   |
| Gigabyte Technology         | 7         | 10     | 0.28%   |
| OCZ                         | 6         | 6      | 0.24%   |
| Apple                       | 6         | 7      | 0.24%   |
| Team                        | 5         | 8      | 0.2%    |
| Phison                      | 5         | 6      | 0.2%    |
| GOODRAM                     | 5         | 6      | 0.2%    |
| ASMT                        | 5         | 7      | 0.2%    |
| Verbatim                    | 4         | 9      | 0.16%   |
| Silicon Motion              | 4         | 5      | 0.16%   |
| Unknown                     | 4         | 5      | 0.16%   |
| SSSTC                       | 3         | 5      | 0.12%   |
| Kingston Technology Company | 3         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 60        | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB     | 54        | 2.09%   |
| Kingston SA400S37120G 120GB SSD    | 52        | 2.02%   |
| Toshiba MQ01ABF050 500GB           | 46        | 1.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 40        | 1.55%   |
| Toshiba MQ01ABD100 1TB             | 39        | 1.51%   |
| Seagate ST500LT012-1DG142 500GB    | 35        | 1.36%   |
| Kingston SV300S37A120G 120GB SSD   | 32        | 1.24%   |
| HGST HTS545032A7E380 320GB         | 32        | 1.24%   |
| Kingston SA400S37480G 480GB SSD    | 31        | 1.2%    |
| Toshiba MQ04ABF100 1TB             | 24        | 0.93%   |
| HGST HTS545050A7E680 500GB         | 24        | 0.93%   |
| Seagate ST9320325AS 320GB          | 22        | 0.85%   |
| Samsung SSD 850 EVO 250GB          | 20        | 0.78%   |
| HGST HTS721010A9E630 1TB           | 20        | 0.78%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 16        | 0.62%   |
| Seagate ST9500325AS 500GB          | 16        | 0.62%   |
| Seagate ST9250315AS 250GB          | 15        | 0.58%   |
| Kingston SUV400S37120G 120GB SSD   | 14        | 0.54%   |
| HGST HTS541010A9E680 1TB           | 14        | 0.54%   |
| WDC WD10JPVX-22JC3T0 1TB           | 13        | 0.5%    |
| Samsung SSD 860 EVO 500GB          | 13        | 0.5%    |
| WDC WD1600BEVT-22ZCT0 160GB        | 12        | 0.47%   |
| Seagate ST500LT012-9WS142 500GB    | 11        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB       | 11        | 0.43%   |
| Samsung NVMe SSD Drive 512GB       | 11        | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 10        | 0.39%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 10        | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB           | 10        | 0.39%   |
| Unknown MMC Card  32GB             | 10        | 0.39%   |
| Seagate M3 Portable 2TB            | 10        | 0.39%   |
| JMicron Generic 500GB              | 10        | 0.39%   |
| HGST HTS725050A7E630 500GB         | 10        | 0.39%   |
| WDC WD10JPVX-60JC3T0 1TB           | 9         | 0.35%   |
| Toshiba MQ01ABD050 500GB           | 9         | 0.35%   |
| SPCC Solid State Disk 128GB        | 9         | 0.35%   |
| Samsung SSD 850 EVO 500GB          | 9         | 0.35%   |
| HGST HTS545050A7E380 500GB         | 9         | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 8         | 0.31%   |
| WDC WD10SPZX-24Z10 1TB             | 8         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 362       | 528    | 29.99%  |
| WDC                 | 270       | 376    | 22.37%  |
| Toshiba             | 211       | 294    | 17.48%  |
| Hitachi             | 138       | 190    | 11.43%  |
| HGST                | 133       | 188    | 11.02%  |
| Fujitsu             | 44        | 56     | 3.65%   |
| Samsung Electronics | 31        | 38     | 2.57%   |
| Unknown             | 6         | 7      | 0.5%    |
| ASMT                | 4         | 6      | 0.33%   |
| IBM/Hitachi         | 3         | 4      | 0.25%   |
| HGST HTS            | 2         | 7      | 0.17%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| CSD                 | 1         | 1      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 240       | 347    | 27.84%  |
| Samsung Electronics | 162       | 238    | 18.79%  |
| SanDisk             | 60        | 95     | 6.96%   |
| Intel               | 40        | 57     | 4.64%   |
| WDC                 | 38        | 60     | 4.41%   |
| Crucial             | 34        | 54     | 3.94%   |
| SK hynix            | 32        | 50     | 3.71%   |
| Micron Technology   | 30        | 38     | 3.48%   |
| A-DATA Technology   | 29        | 39     | 3.36%   |
| SPCC                | 21        | 26     | 2.44%   |
| Apacer              | 17        | 30     | 1.97%   |
| Toshiba             | 16        | 29     | 1.86%   |
| LITEON              | 13        | 15     | 1.51%   |
| PNY                 | 10        | 15     | 1.16%   |
| JMicron Technology  | 10        | 10     | 1.16%   |
| Kingmax             | 9         | 9      | 1.04%   |
| China               | 9         | 18     | 1.04%   |
| Intenso             | 8         | 18     | 0.93%   |
| Transcend           | 7         | 7      | 0.81%   |
| LITEONIT            | 7         | 9      | 0.81%   |
| OCZ                 | 6         | 6      | 0.7%    |
| KingSpec            | 6         | 7      | 0.7%    |
| Gigabyte Technology | 6         | 9      | 0.7%    |
| Patriot             | 5         | 6      | 0.58%   |
| GOODRAM             | 5         | 6      | 0.58%   |
| Apple               | 5         | 5      | 0.58%   |
| Verbatim            | 4         | 9      | 0.46%   |
| Team                | 4         | 7      | 0.46%   |
| Corsair             | 3         | 4      | 0.35%   |
| BHT                 | 3         | 3      | 0.35%   |
| Unknown             | 2         | 4      | 0.23%   |
| Initio              | 2         | 2      | 0.23%   |
| HS-SSD-C100         | 2         | 2      | 0.23%   |
| Zheino              | 1         | 1      | 0.12%   |
| Union Memory        | 1         | 5      | 0.12%   |
| TO Exter            | 1         | 1      | 0.12%   |
| Solid               | 1         | 6      | 0.12%   |
| Seagate             | 1         | 1      | 0.12%   |
| SATAFIRM            | 1         | 1      | 0.12%   |
| R580                | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1155      | 1697   | 48.73%  |
| SSD     | 797       | 1261   | 33.63%  |
| NVMe    | 292       | 449    | 12.32%  |
| MMC     | 98        | 141    | 4.14%   |
| Unknown | 28        | 32     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1731      | 2883   | 78.9%   |
| NVMe | 292       | 449    | 13.31%  |
| MMC  | 98        | 141    | 4.47%   |
| SAS  | 73        | 107    | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1453      | 2291   | 77.29%  |
| 0.51-1.0   | 395       | 615    | 21.01%  |
| 1.01-2.0   | 24        | 42     | 1.28%   |
| 2.01-3.0   | 3         | 5      | 0.16%   |
| 4.01-10.0  | 3         | 3      | 0.16%   |
| 3.01-4.0   | 1         | 1      | 0.05%   |
| 10.01-20.0 | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 751       | 32.48%  |
| 101-250        | 554       | 23.96%  |
| 251-500        | 376       | 16.26%  |
| 51-100         | 177       | 7.66%   |
| 501-1000       | 162       | 7.01%   |
| 1-20           | 104       | 4.5%    |
| 21-50          | 90        | 3.89%   |
| 1001-2000      | 65        | 2.81%   |
| 2001-3000      | 20        | 0.87%   |
| More than 3000 | 13        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 871       | 37.05%  |
| Unknown        | 751       | 31.94%  |
| 21-50          | 237       | 10.08%  |
| 51-100         | 177       | 7.53%   |
| 101-250        | 157       | 6.68%   |
| 251-500        | 80        | 3.4%    |
| 501-1000       | 50        | 2.13%   |
| 1001-2000      | 25        | 1.06%   |
| More than 3000 | 2         | 0.09%   |
| 2001-3000      | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB              | 30        | 42     | 6.28%   |
| HGST HTS545050A7E680 500GB              | 17        | 26     | 3.56%   |
| Seagate ST9320325AS 320GB               | 11        | 23     | 2.3%    |
| Toshiba MQ01ABF050 500GB                | 10        | 25     | 2.09%   |
| Seagate ST500LT012-1DG142 500GB         | 10        | 13     | 2.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 8         | 12     | 1.67%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 8      | 1.46%   |
| Seagate ST9320423AS 320GB               | 7         | 7      | 1.46%   |
| Seagate ST9250315AS 250GB               | 7         | 9      | 1.46%   |
| Seagate ST500LT012-9WS142 500GB         | 7         | 8      | 1.46%   |
| Seagate ST9500325AS 500GB               | 6         | 10     | 1.26%   |
| Samsung Electronics HM160HI 160GB       | 6         | 7      | 1.26%   |
| Kingston SV300S37A120G 120GB SSD        | 6         | 9      | 1.26%   |
| Hitachi HTS545016B9A300 160GB           | 6         | 6      | 1.26%   |
| HGST HTS541010A9E680 1TB                | 6         | 14     | 1.26%   |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 1.05%   |
| Hitachi HTS547550A9E384 500GB           | 5         | 15     | 1.05%   |
| Hitachi HTS545032B9A300 320GB           | 5         | 6      | 1.05%   |
| HGST HTS545050A7E380 500GB              | 5         | 9      | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 7      | 0.84%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 4         | 6      | 0.84%   |
| Seagate ST500LM000-SSHD-8GB             | 4         | 5      | 0.84%   |
| Seagate ST320LT007-9ZV142 320GB         | 4         | 4      | 0.84%   |
| Seagate ST1000LX015-1U7172 1TB          | 4         | 12     | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB          | 4         | 5      | 0.84%   |
| Hitachi HTS723232A7A364 320GB           | 4         | 4      | 0.84%   |
| Hitachi HTS545050B9A300 500GB           | 4         | 5      | 0.84%   |
| Hitachi HTS545050A7E380 500GB           | 4         | 6      | 0.84%   |
| Hitachi HTS543216L9A300 160GB           | 4         | 4      | 0.84%   |
| Hitachi HTS542516K9SA00 160GB           | 4         | 4      | 0.84%   |
| Hitachi HTS541680J9SA00 80GB            | 4         | 4      | 0.84%   |
| Toshiba MQ01ABF032 320GB                | 3         | 3      | 0.63%   |
| Seagate ST980811AS 80GB                 | 3         | 3      | 0.63%   |
| Seagate ST9250410AS 250GB               | 3         | 3      | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB         | 3         | 3      | 0.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 3         | 4      | 0.63%   |
| Samsung Electronics HM321HI 320GB       | 3         | 5      | 0.63%   |
| Hitachi HTS545025B9A300 250GB           | 3         | 8      | 0.63%   |
| Hitachi HTS543232A7A384 320GB           | 3         | 5      | 0.63%   |
| Hitachi HTS541612J9SA00 120GB           | 3         | 3      | 0.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 117       | 161    | 24.58%  |
| Hitachi             | 77        | 111    | 16.18%  |
| Toshiba             | 73        | 109    | 15.34%  |
| HGST                | 65        | 100    | 13.66%  |
| WDC                 | 53        | 69     | 11.13%  |
| Samsung Electronics | 20        | 28     | 4.2%    |
| Kingston            | 18        | 27     | 3.78%   |
| Fujitsu             | 16        | 23     | 3.36%   |
| Intel               | 12        | 19     | 2.52%   |
| SK hynix            | 6         | 7      | 1.26%   |
| SanDisk             | 3         | 4      | 0.63%   |
| A-DATA Technology   | 3         | 3      | 0.63%   |
| IBM/Hitachi         | 2         | 2      | 0.42%   |
| SPCC                | 1         | 1      | 0.21%   |
| R580                | 1         | 1      | 0.21%   |
| LITEON              | 1         | 1      | 0.21%   |
| Kingmax             | 1         | 1      | 0.21%   |
| JMicron Technology  | 1         | 1      | 0.21%   |
| Intenso             | 1         | 1      | 0.21%   |
| Initio              | 1         | 1      | 0.21%   |
| CSD                 | 1         | 1      | 0.21%   |
| Crucial             | 1         | 1      | 0.21%   |
| Apple               | 1         | 1      | 0.21%   |
| Apacer              | 1         | 2      | 0.21%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 117       | 161    | 28.47%  |
| Hitachi             | 77        | 111    | 18.73%  |
| Toshiba             | 67        | 96     | 16.3%   |
| HGST                | 65        | 100    | 15.82%  |
| WDC                 | 51        | 67     | 12.41%  |
| Fujitsu             | 16        | 23     | 3.89%   |
| Samsung Electronics | 15        | 20     | 3.65%   |
| IBM/Hitachi         | 2         | 2      | 0.49%   |
| CSD                 | 1         | 1      | 0.24%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 401       | 581    | 86.05%  |
| SSD     | 61        | 89     | 13.09%  |
| NVMe    | 3         | 4      | 0.64%   |
| Unknown | 1         | 1      | 0.21%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 7.14%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 7.14%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 7.14%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 7.14%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 7.14%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 7.14%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 7.14%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 7.14%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 7.14%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 7.14%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 7.14%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 12     | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| Seagate             | 2         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1125      | 1888   | 50.93%  |
| Detected | 612       | 997    | 27.7%   |
| Malfunc  | 458       | 675    | 20.73%  |
| Failed   | 14        | 20     | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1628      | 74.44%  |
| AMD                              | 229       | 10.47%  |
| Samsung Electronics              | 96        | 4.39%   |
| SanDisk                          | 53        | 2.42%   |
| SK hynix                         | 33        | 1.51%   |
| Kingston Technology Company      | 28        | 1.28%   |
| Toshiba America Info Systems     | 25        | 1.14%   |
| KIOXIA                           | 14        | 0.64%   |
| Silicon Integrated Systems [SiS] | 13        | 0.59%   |
| Phison Electronics               | 10        | 0.46%   |
| Nvidia                           | 10        | 0.46%   |
| Micron Technology                | 10        | 0.46%   |
| VIA Technologies                 | 7         | 0.32%   |
| Solid State Storage Technology   | 5         | 0.23%   |
| Silicon Motion                   | 5         | 0.23%   |
| JMicron Technology               | 5         | 0.23%   |
| Micron/Crucial Technology        | 3         | 0.14%   |
| ADATA Technology                 | 3         | 0.14%   |
| Union Memory (Shenzhen)          | 2         | 0.09%   |
| Silicon Image                    | 2         | 0.09%   |
| Shenzhen Longsys Electronics     | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 191       | 7.72%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 165       | 6.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 164       | 6.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 139       | 5.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 123       | 4.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 111       | 4.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 87        | 3.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 83        | 3.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 71        | 2.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 70        | 2.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 63        | 2.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 61        | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 49        | 1.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 46        | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 45        | 1.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 42        | 1.7%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 37        | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 37        | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 35        | 1.41%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 34        | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 33        | 1.33%   |
| Samsung NVMe SSD Controller 980                                                        | 30        | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 29        | 1.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 29        | 1.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 28        | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 27        | 1.09%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 23        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 21        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 21        | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 19        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 18        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 16        | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 16        | 0.65%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 15        | 0.61%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 14        | 0.57%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 14        | 0.57%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 13        | 0.53%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 13        | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 13        | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 13        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1607      | 68.3%   |
| IDE  | 317       | 13.47%  |
| NVMe | 295       | 12.54%  |
| RAID | 134       | 5.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1731      | 86.46%  |
| AMD          | 269       | 13.44%  |
| CentaurHauls | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 46        | 2.29%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 2.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 30        | 1.49%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 29        | 1.44%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 1.35%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 25        | 1.25%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 25        | 1.25%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 23        | 1.15%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 20        | 1%      |
| Intel Core i3-7020U CPU @ 2.30GHz           | 20        | 1%      |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 20        | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz           | 19        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 18        | 0.9%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.9%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 17        | 0.85%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 17        | 0.85%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 17        | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 15        | 0.75%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 15        | 0.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 15        | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 15        | 0.75%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 14        | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 14        | 0.7%    |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 14        | 0.7%    |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 14        | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 13        | 0.65%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 13        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 13        | 0.65%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 13        | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 13        | 0.65%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 13        | 0.65%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 13        | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 12        | 0.6%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 12        | 0.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 12        | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz           | 12        | 0.6%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 12        | 0.6%    |
| Intel Atom CPU N455 @ 1.66GHz               | 12        | 0.6%    |
| Intel Atom CPU N450 @ 1.66GHz               | 12        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 480       | 23.93%  |
| Intel Core i3           | 257       | 12.81%  |
| Intel Core i7           | 255       | 12.71%  |
| Intel Celeron           | 186       | 9.27%   |
| Intel Core 2 Duo        | 177       | 8.82%   |
| Intel Pentium           | 87        | 4.34%   |
| Intel Atom              | 72        | 3.59%   |
| Other                   | 49        | 2.44%   |
| Intel Pentium Dual-Core | 39        | 1.94%   |
| AMD Ryzen 5             | 30        | 1.5%    |
| Intel Pentium Dual      | 29        | 1.45%   |
| AMD A4                  | 27        | 1.35%   |
| AMD Ryzen 7             | 25        | 1.25%   |
| AMD A8                  | 25        | 1.25%   |
| Intel Core 2            | 23        | 1.15%   |
| Intel Genuine           | 19        | 0.95%   |
| AMD A6                  | 17        | 0.85%   |
| AMD E1                  | 16        | 0.8%    |
| AMD E                   | 15        | 0.75%   |
| Intel Pentium Silver    | 14        | 0.7%    |
| AMD E2                  | 14        | 0.7%    |
| Intel Celeron M         | 13        | 0.65%   |
| Intel Celeron Dual-Core | 13        | 0.65%   |
| AMD A10                 | 11        | 0.55%   |
| AMD Ryzen 3             | 10        | 0.5%    |
| Intel Pentium M         | 9         | 0.45%   |
| Intel Core Duo          | 8         | 0.4%    |
| AMD Turion 64 X2 Mobile | 6         | 0.3%    |
| AMD FX                  | 6         | 0.3%    |
| AMD C-60                | 5         | 0.25%   |
| AMD Athlon II           | 5         | 0.25%   |
| AMD Ryzen 9             | 4         | 0.2%    |
| AMD Ryzen 7 PRO         | 4         | 0.2%    |
| AMD Mobile Sempron      | 4         | 0.2%    |
| AMD C-50                | 4         | 0.2%    |
| AMD Athlon X2           | 4         | 0.2%    |
| Intel Core i9           | 3         | 0.15%   |
| AMD Ryzen 5 PRO         | 3         | 0.15%   |
| AMD Athlon II Dual-Core | 3         | 0.15%   |
| AMD Athlon 64 X2        | 3         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1375      | 68.48%  |
| 4      | 398       | 19.82%  |
| 1      | 130       | 6.47%   |
| 6      | 62        | 3.09%   |
| 8      | 33        | 1.64%   |
| 10     | 5         | 0.25%   |
| 14     | 3         | 0.15%   |
| 12     | 2         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2002      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1163      | 57.75%  |
| 1      | 851       | 42.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1927      | 95.78%  |
| 32-bit         | 54        | 2.68%   |
| Unknown        | 31        | 1.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 223       | 10.78%  |
| 0x206a7    | 175       | 8.46%   |
| 0x306a9    | 168       | 8.12%   |
| 0x1067a    | 135       | 6.53%   |
| 0x20655    | 104       | 5.03%   |
| 0x40651    | 83        | 4.01%   |
| 0x6fd      | 74        | 3.58%   |
| 0x406e3    | 74        | 3.58%   |
| 0x306d4    | 74        | 3.58%   |
| 0x806e9    | 52        | 2.51%   |
| 0x806ea    | 47        | 2.27%   |
| 0x306c3    | 47        | 2.27%   |
| 0x406c4    | 41        | 1.98%   |
| 0x906ea    | 40        | 1.93%   |
| 0x806ec    | 37        | 1.79%   |
| 0x10676    | 37        | 1.79%   |
| 0x20652    | 34        | 1.64%   |
| 0x106ca    | 33        | 1.6%    |
| 0x30678    | 28        | 1.35%   |
| 0x806c1    | 27        | 1.31%   |
| 0x506c9    | 27        | 1.31%   |
| 0x05000119 | 26        | 1.26%   |
| 0x706a1    | 23        | 1.11%   |
| 0x07030105 | 23        | 1.11%   |
| 0x906e9    | 21        | 1.02%   |
| 0x406c3    | 20        | 0.97%   |
| 0x806eb    | 19        | 0.92%   |
| 0x6fb      | 19        | 0.92%   |
| 0x106c2    | 19        | 0.92%   |
| 0x506e3    | 18        | 0.87%   |
| 0x706e5    | 16        | 0.77%   |
| 0x6f6      | 16        | 0.77%   |
| 0x08600106 | 15        | 0.73%   |
| 0x0700010f | 15        | 0.73%   |
| 0x06001119 | 13        | 0.63%   |
| 0x6ec      | 12        | 0.58%   |
| 0x05000029 | 11        | 0.53%   |
| 0x6f2      | 10        | 0.48%   |
| 0x6d8      | 10        | 0.48%   |
| 0x06006705 | 10        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 256       | 12.78%  |
| SandyBridge      | 179       | 8.94%   |
| IvyBridge        | 176       | 8.79%   |
| Penryn           | 175       | 8.74%   |
| Westmere         | 144       | 7.19%   |
| Haswell          | 144       | 7.19%   |
| Core             | 139       | 6.94%   |
| Skylake          | 109       | 5.44%   |
| Silvermont       | 96        | 4.79%   |
| Broadwell        | 85        | 4.24%   |
| Bonnell          | 54        | 2.7%    |
| Bobcat           | 40        | 2%      |
| Puma             | 34        | 1.7%    |
| P6               | 33        | 1.65%   |
| Goldmont         | 33        | 1.65%   |
| Goldmont plus    | 31        | 1.55%   |
| TigerLake        | 28        | 1.4%    |
| Zen 2            | 26        | 1.3%    |
| Excavator        | 24        | 1.2%    |
| IceLake          | 22        | 1.1%    |
| Piledriver       | 18        | 0.9%    |
| Jaguar           | 18        | 0.9%    |
| K8 Hammer        | 16        | 0.8%    |
| Unknown          | 16        | 0.8%    |
| Zen 3            | 15        | 0.75%   |
| Zen              | 15        | 0.75%   |
| K10              | 15        | 0.75%   |
| Zen+             | 13        | 0.65%   |
| Steamroller      | 12        | 0.6%    |
| CometLake        | 9         | 0.45%   |
| Alderlake Hybrid | 9         | 0.45%   |
| K10 Llano        | 7         | 0.35%   |
| Nehalem          | 5         | 0.25%   |
| K8 & K10 hybrid  | 5         | 0.25%   |
| Tremont          | 1         | 0.05%   |
| NetBurst         | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1550      | 63.09%  |
| Nvidia                           | 462       | 18.8%   |
| AMD                              | 431       | 17.54%  |
| VIA Technologies                 | 7         | 0.28%   |
| Silicon Integrated Systems [SiS] | 7         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 170       | 6.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 168       | 6.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 141       | 5.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 102       | 3.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 88        | 3.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 78        | 2.97%   |
| Intel HD Graphics 5500                                                                   | 74        | 2.82%   |
| Intel HD Graphics 620                                                                    | 66        | 2.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 63        | 2.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 57        | 2.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 1.98%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 1.98%   |
| Intel UHD Graphics 620                                                                   | 51        | 1.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 47        | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 38        | 1.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.41%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33        | 1.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 32        | 1.22%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 29        | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 28        | 1.07%   |
| Intel HD Graphics 500                                                                    | 26        | 0.99%   |
| AMD Renoir                                                                               | 26        | 0.99%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 25        | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 23        | 0.88%   |
| Intel HD Graphics 530                                                                    | 22        | 0.84%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 22        | 0.84%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 21        | 0.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 0.8%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 20        | 0.76%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 19        | 0.72%   |
| Intel HD Graphics 630                                                                    | 19        | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 18        | 0.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 18        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.65%   |
| Nvidia GM108M [GeForce MX110]                                                            | 16        | 0.61%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 16        | 0.61%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 0.57%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 15        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1113      | 55.51%  |
| Intel + Nvidia | 340       | 16.96%  |
| 1 x AMD        | 259       | 12.92%  |
| 1 x Nvidia     | 104       | 5.19%   |
| Intel + AMD    | 96        | 4.79%   |
| 2 x AMD        | 58        | 2.89%   |
| AMD + Nvidia   | 19        | 0.95%   |
| 1 x VIA        | 7         | 0.35%   |
| 1 x SiS        | 7         | 0.35%   |
| Other          | 1         | 0.05%   |
| 2 x Intel      | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1875      | 92.87%  |
| Proprietary | 113       | 5.6%    |
| Unknown     | 31        | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1183      | 57.21%  |
| 0.01-0.5   | 365       | 17.65%  |
| 1.01-2.0   | 280       | 13.54%  |
| 0.51-1.0   | 122       | 5.9%    |
| 3.01-4.0   | 93        | 4.5%    |
| 5.01-6.0   | 16        | 0.77%   |
| 7.01-8.0   | 5         | 0.24%   |
| 2.01-3.0   | 3         | 0.15%   |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 425       | 19.84%  |
| AU Optronics            | 396       | 18.49%  |
| Samsung Electronics     | 313       | 14.61%  |
| Chimei Innolux          | 262       | 12.23%  |
| BOE                     | 218       | 10.18%  |
| Chi Mei Optoelectronics | 98        | 4.58%   |
| Lenovo                  | 76        | 3.55%   |
| Goldstar                | 43        | 2.01%   |
| LG Philips              | 38        | 1.77%   |
| Dell                    | 27        | 1.26%   |
| InfoVision              | 26        | 1.21%   |
| PANDA                   | 16        | 0.75%   |
| Philips                 | 15        | 0.7%    |
| CPT                     | 14        | 0.65%   |
| Acer                    | 12        | 0.56%   |
| BenQ                    | 11        | 0.51%   |
| Apple                   | 11        | 0.51%   |
| AOC                     | 11        | 0.51%   |
| Hewlett-Packard         | 10        | 0.47%   |
| HannStar                | 10        | 0.47%   |
| Sharp                   | 9         | 0.42%   |
| Sony                    | 8         | 0.37%   |
| Quanta Display          | 8         | 0.37%   |
| ASUSTek Computer        | 8         | 0.37%   |
| Toshiba                 | 7         | 0.33%   |
| InnoLux Display         | 6         | 0.28%   |
| Vestel Elektronik       | 5         | 0.23%   |
| Ancor Communications    | 5         | 0.23%   |
| Panasonic               | 4         | 0.19%   |
| IBM                     | 4         | 0.19%   |
| Fujitsu Siemens         | 4         | 0.19%   |
| NEC Computers           | 3         | 0.14%   |
| Eizo                    | 3         | 0.14%   |
| ViewSonic               | 2         | 0.09%   |
| TMX                     | 2         | 0.09%   |
| SKY                     | 2         | 0.09%   |
| Plain Tree Systems      | 2         | 0.09%   |
| OEM                     | 2         | 0.09%   |
| MSI                     | 2         | 0.09%   |
| MiTAC                   | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 49        | 2.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 37        | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 1.58%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 25        | 1.16%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 1.11%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.97%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 19        | 0.88%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.84%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 14        | 0.65%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 14        | 0.65%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.65%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 14        | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.65%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.56%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.56%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.56%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.51%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 11        | 0.51%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.46%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.46%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 9         | 0.42%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 9         | 0.42%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 8         | 0.37%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 8         | 0.37%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch              | 8         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 8         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 8         | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 8         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 7         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 7         | 0.32%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 7         | 0.32%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 7         | 0.32%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 849       | 41.13%  |
| 1920x1080 (FHD)    | 621       | 30.09%  |
| 1280x800 (WXGA)    | 170       | 8.24%   |
| 1600x900 (HD+)     | 133       | 6.44%   |
| 1440x900 (WXGA+)   | 57        | 2.76%   |
| 3840x2160 (4K)     | 40        | 1.94%   |
| 1024x600           | 39        | 1.89%   |
| 1920x1200 (WUXGA)  | 25        | 1.21%   |
| 1680x1050 (WSXGA+) | 23        | 1.11%   |
| 2560x1440 (QHD)    | 21        | 1.02%   |
| 1280x1024 (SXGA)   | 16        | 0.78%   |
| 1024x768 (XGA)     | 15        | 0.73%   |
| 2880x1800          | 9         | 0.44%   |
| 1920x540           | 6         | 0.29%   |
| 2560x1080          | 5         | 0.24%   |
| 1360x768           | 5         | 0.24%   |
| 2560x1600          | 4         | 0.19%   |
| 3440x1440          | 3         | 0.15%   |
| 3840x2400          | 2         | 0.1%    |
| 3200x2000          | 2         | 0.1%    |
| 2880x1620          | 2         | 0.1%    |
| 2160x1440          | 2         | 0.1%    |
| 1680x945           | 2         | 0.1%    |
| 1600x1200          | 2         | 0.1%    |
| 1400x1050          | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 800x1280           | 1         | 0.05%   |
| 4093x4093          | 1         | 0.05%   |
| 2304x1440          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 1920x1280          | 1         | 0.05%   |
| 1800x1440          | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1159      | 54.06%  |
| 14      | 247       | 11.52%  |
| 13      | 170       | 7.93%   |
| 17      | 131       | 6.11%   |
| 12      | 78        | 3.64%   |
| 10      | 47        | 2.19%   |
| 24      | 44        | 2.05%   |
| 23      | 40        | 1.87%   |
| 21      | 36        | 1.68%   |
| 11      | 36        | 1.68%   |
| 27      | 33        | 1.54%   |
| 18      | 19        | 0.89%   |
| 19      | 13        | 0.61%   |
| Unknown | 11        | 0.51%   |
| 22      | 10        | 0.47%   |
| 20      | 8         | 0.37%   |
| 34      | 7         | 0.33%   |
| 31      | 7         | 0.33%   |
| 84      | 6         | 0.28%   |
| 72      | 5         | 0.23%   |
| 32      | 5         | 0.23%   |
| 54      | 4         | 0.19%   |
| 40      | 4         | 0.19%   |
| 16      | 4         | 0.19%   |
| 8       | 3         | 0.14%   |
| 65      | 2         | 0.09%   |
| 33      | 2         | 0.09%   |
| 25      | 2         | 0.09%   |
| 60      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 52      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 41      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 29      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1472      | 68.95%  |
| 201-300     | 229       | 10.73%  |
| 351-400     | 175       | 8.2%    |
| 501-600     | 114       | 5.34%   |
| 401-500     | 75        | 3.51%   |
| 701-800     | 14        | 0.66%   |
| 601-700     | 11        | 0.52%   |
| 1501-2000   | 11        | 0.52%   |
| 1001-1500   | 11        | 0.52%   |
| Unknown     | 11        | 0.52%   |
| 801-900     | 5         | 0.23%   |
| 101-200     | 4         | 0.19%   |
| 901-1000    | 3         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1624      | 82.23%  |
| 16/10   | 291       | 14.73%  |
| 4/3     | 21        | 1.06%   |
| 5/4     | 16        | 0.81%   |
| 3/2     | 8         | 0.41%   |
| 21/9    | 7         | 0.35%   |
| Unknown | 7         | 0.35%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1155      | 53.9%   |
| 81-90          | 357       | 16.66%  |
| 201-250        | 105       | 4.9%    |
| 121-130        | 95        | 4.43%   |
| 61-70          | 76        | 3.55%   |
| 71-80          | 58        | 2.71%   |
| 41-50          | 47        | 2.19%   |
| 51-60          | 36        | 1.68%   |
| 301-350        | 33        | 1.54%   |
| 151-200        | 32        | 1.49%   |
| 131-140        | 29        | 1.35%   |
| 141-150        | 24        | 1.12%   |
| More than 1000 | 22        | 1.03%   |
| 351-500        | 21        | 0.98%   |
| 251-300        | 19        | 0.89%   |
| Unknown        | 11        | 0.51%   |
| 501-1000       | 8         | 0.37%   |
| 91-100         | 8         | 0.37%   |
| 1-40           | 4         | 0.19%   |
| 111-120        | 3         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 881       | 41.64%  |
| 121-160       | 702       | 33.18%  |
| 51-100        | 422       | 19.94%  |
| 161-240       | 63        | 2.98%   |
| More than 240 | 21        | 0.99%   |
| 1-50          | 16        | 0.76%   |
| Unknown       | 11        | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1787      | 86.83%  |
| 2     | 229       | 11.13%  |
| 0     | 25        | 1.21%   |
| 3     | 17        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 999       | 30.4%   |
| Intel                             | 941       | 28.64%  |
| Qualcomm Atheros                  | 604       | 18.38%  |
| Broadcom                          | 255       | 7.76%   |
| Ralink                            | 98        | 2.98%   |
| Broadcom Limited                  | 91        | 2.77%   |
| Marvell Technology Group          | 46        | 1.4%    |
| MediaTek                          | 30        | 0.91%   |
| Dell                              | 26        | 0.79%   |
| Hewlett-Packard                   | 21        | 0.64%   |
| Ericsson Business Mobile Networks | 16        | 0.49%   |
| TP-Link                           | 14        | 0.43%   |
| Sierra Wireless                   | 14        | 0.43%   |
| Samsung Electronics               | 13        | 0.4%    |
| Huawei Technologies               | 13        | 0.4%    |
| JMicron Technology                | 12        | 0.37%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.33%   |
| Attansic Technology               | 11        | 0.33%   |
| Xiaomi                            | 10        | 0.3%    |
| Ralink Technology                 | 10        | 0.3%    |
| Qualcomm Atheros Communications   | 7         | 0.21%   |
| ASIX Electronics                  | 6         | 0.18%   |
| VIA Technologies                  | 5         | 0.15%   |
| Nvidia                            | 4         | 0.12%   |
| DisplayLink                       | 4         | 0.12%   |
| Lenovo                            | 3         | 0.09%   |
| D-Link                            | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| Qualcomm                          | 1         | 0.03%   |
| OPPO Electronics                  | 1         | 0.03%   |
| NetGear                           | 1         | 0.03%   |
| Motorola PCS                      | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| Fujitsu Siemens Computers         | 1         | 0.03%   |
| Davicom Semiconductor             | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 593       | 14.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 296       | 7.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 2.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 109       | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 104       | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 74        | 1.86%   |
| Intel Wireless 8265 / 8275                                              | 72        | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 1.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 67        | 1.68%   |
| Intel Wireless 7260                                                     | 64        | 1.6%    |
| Intel 82577LM Gigabit Network Connection                                | 62        | 1.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 58        | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 56        | 1.4%    |
| Intel Wireless 7265                                                     | 55        | 1.38%   |
| Intel 82567LM Gigabit Network Connection                                | 53        | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 1.3%    |
| Intel Centrino Advanced-N 6200                                          | 50        | 1.25%   |
| Intel Wireless 3165                                                     | 39        | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 35        | 0.88%   |
| Intel Wireless 3160                                                     | 34        | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 0.83%   |
| Intel Wireless 8260                                                     | 32        | 0.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 29        | 0.73%   |
| Intel WiFi Link 5100                                                    | 29        | 0.73%   |
| Intel Wi-Fi 6 AX200                                                     | 27        | 0.68%   |
| Intel Ethernet Connection I218-LM                                       | 27        | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                                   | 27        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                   | 24        | 0.6%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 0.58%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 21        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 20        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 880       | 42.74%  |
| Qualcomm Atheros                | 535       | 25.98%  |
| Realtek Semiconductor           | 238       | 11.56%  |
| Broadcom                        | 170       | 8.26%   |
| Ralink                          | 98        | 4.76%   |
| Broadcom Limited                | 41        | 1.99%   |
| MediaTek                        | 28        | 1.36%   |
| Dell                            | 15        | 0.73%   |
| Sierra Wireless                 | 14        | 0.68%   |
| Ralink Technology               | 10        | 0.49%   |
| TP-Link                         | 9         | 0.44%   |
| Qualcomm Atheros Communications | 7         | 0.34%   |
| Hewlett-Packard                 | 3         | 0.15%   |
| D-Link                          | 3         | 0.15%   |
| Belkin Components               | 2         | 0.1%    |
| ASUSTek Computer                | 2         | 0.1%    |
| Qualcomm                        | 1         | 0.05%   |
| NetGear                         | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 5.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 107       | 5.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 104       | 5.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 3.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 74        | 3.58%   |
| Intel Wireless 8265 / 8275                                              | 72        | 3.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 3.24%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 67        | 3.24%   |
| Intel Wireless 7260                                                     | 64        | 3.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 58        | 2.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 56        | 2.71%   |
| Intel Wireless 7265                                                     | 55        | 2.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 2.51%   |
| Intel Centrino Advanced-N 6200                                          | 50        | 2.42%   |
| Intel Wireless 3165                                                     | 39        | 1.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 1.74%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 1.69%   |
| Intel Wireless 3160                                                     | 34        | 1.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 33        | 1.6%    |
| Intel Wireless 8260                                                     | 32        | 1.55%   |
| Intel WiFi Link 5100                                                    | 29        | 1.4%    |
| Intel Wi-Fi 6 AX200                                                     | 27        | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.16%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 1.16%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 23        | 1.11%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 20        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 0.92%   |
| Intel Ultimate N WiFi Link 5300                                         | 19        | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 19        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 18        | 0.87%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 18        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 17        | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 17        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 14        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 932       | 50.03%  |
| Intel                            | 469       | 25.17%  |
| Qualcomm Atheros                 | 148       | 7.94%   |
| Broadcom                         | 108       | 5.8%    |
| Broadcom Limited                 | 51        | 2.74%   |
| Marvell Technology Group         | 46        | 2.47%   |
| Samsung Electronics              | 13        | 0.7%    |
| JMicron Technology               | 12        | 0.64%   |
| Huawei Technologies              | 12        | 0.64%   |
| Silicon Integrated Systems [SiS] | 11        | 0.59%   |
| Attansic Technology              | 11        | 0.59%   |
| Xiaomi                           | 10        | 0.54%   |
| ASIX Electronics                 | 6         | 0.32%   |
| VIA Technologies                 | 5         | 0.27%   |
| TP-Link                          | 5         | 0.27%   |
| Nvidia                           | 4         | 0.21%   |
| DisplayLink                      | 4         | 0.21%   |
| Lenovo                           | 3         | 0.16%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.11%   |
| MediaTek                         | 2         | 0.11%   |
| Hewlett-Packard                  | 2         | 0.11%   |
| Spreadtrum Communications        | 1         | 0.05%   |
| OPPO Electronics                 | 1         | 0.05%   |
| Motorola PCS                     | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| Davicom Semiconductor            | 1         | 0.05%   |
| 3DSP                             | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 593       | 31.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 296       | 15.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 109       | 5.84%   |
| Intel 82577LM Gigabit Network Connection                          | 62        | 3.32%   |
| Intel 82567LM Gigabit Network Connection                          | 53        | 2.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 29        | 1.55%   |
| Intel Ethernet Connection I218-LM                                 | 27        | 1.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 1.07%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 1.07%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.86%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.8%    |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.8%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 15        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.75%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 14        | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12        | 0.64%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.64%   |
| Huawei ANA-NX9                                                    | 12        | 0.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 12        | 0.64%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 12        | 0.64%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.59%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 11        | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 10        | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.54%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 10        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 9         | 0.48%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 9         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 8         | 0.43%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1975      | 51.5%   |
| Ethernet | 1807      | 47.12%  |
| Modem    | 52        | 1.36%   |
| Unknown  | 1         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1631      | 74.65%  |
| Ethernet | 554       | 25.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1747      | 87.18%  |
| 1     | 221       | 11.03%  |
| 0     | 29        | 1.45%   |
| 3     | 7         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1762      | 84.71%  |
| Yes  | 318       | 15.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 506       | 33.73%  |
| Qualcomm Atheros Communications | 170       | 11.33%  |
| Broadcom                        | 138       | 9.2%    |
| Realtek Semiconductor           | 126       | 8.4%    |
| Lite-On Technology              | 90        | 6%      |
| Dell                            | 78        | 5.2%    |
| IMC Networks                    | 77        | 5.13%   |
| Hewlett-Packard                 | 71        | 4.73%   |
| Ralink                          | 67        | 4.47%   |
| Foxconn / Hon Hai               | 61        | 4.07%   |
| Cambridge Silicon Radio         | 26        | 1.73%   |
| Toshiba                         | 23        | 1.53%   |
| ASUSTek Computer                | 12        | 0.8%    |
| Ralink Technology               | 9         | 0.6%    |
| Apple                           | 9         | 0.6%    |
| Realtek                         | 8         | 0.53%   |
| Askey Computer                  | 7         | 0.47%   |
| Chicony Electronics             | 5         | 0.33%   |
| Taiyo Yuden                     | 4         | 0.27%   |
| Foxconn International           | 4         | 0.27%   |
| Micro Star International        | 3         | 0.2%    |
| Alps Electric                   | 2         | 0.13%   |
| TP-Link                         | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| MediaTek                        | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 302       | 20.09%  |
| Realtek Bluetooth Radio                             | 70        | 4.66%   |
| Qualcomm Atheros  Bluetooth Device                  | 70        | 4.66%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 70        | 4.66%   |
| Ralink RT3290 Bluetooth                             | 67        | 4.46%   |
| Intel AX201 Bluetooth                               | 48        | 3.19%   |
| Dell DW375 Bluetooth Module                         | 39        | 2.59%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 37        | 2.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 36        | 2.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 34        | 2.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 2.13%   |
| Broadcom BCM2045B (BDC-2.1)                         | 32        | 2.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 29        | 1.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.73%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.6%    |
| Intel AX200 Bluetooth                               | 23        | 1.53%   |
| IMC Networks Bluetooth Device                       | 22        | 1.46%   |
| Broadcom HP Portable SoftSailing                    | 22        | 1.46%   |
| Lite-On Bluetooth Device                            | 20        | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.33%   |
| Realtek RTL8723B Bluetooth                          | 19        | 1.26%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.26%   |
| Realtek RTL8821A Bluetooth                          | 18        | 1.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 1.13%   |
| IMC Networks Wireless_Device                        | 16        | 1.06%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 1%      |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 0.86%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.86%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.73%   |
| Toshiba Bluetooth Device                            | 10        | 0.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 10        | 0.67%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 9         | 0.6%    |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.6%    |
| Realtek Bluetooth Radio                             | 8         | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1687      | 75.65%  |
| AMD                              | 312       | 13.99%  |
| Nvidia                           | 162       | 7.26%   |
| Silicon Integrated Systems [SiS] | 13        | 0.58%   |
| VIA Technologies                 | 7         | 0.31%   |
| Logitech                         | 7         | 0.31%   |
| C-Media Electronics              | 7         | 0.31%   |
| ASUSTek Computer                 | 4         | 0.18%   |
| Texas Instruments                | 3         | 0.13%   |
| Plantronics                      | 3         | 0.13%   |
| Lenovo                           | 3         | 0.13%   |
| GN Netcom                        | 2         | 0.09%   |
| Generalplus Technology           | 2         | 0.09%   |
| Creative Technology              | 2         | 0.09%   |
| Tenx Technology                  | 1         | 0.04%   |
| TEAC                             | 1         | 0.04%   |
| Sony                             | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| Samson Technologies              | 1         | 0.04%   |
| Realtek Semiconductor            | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Numark                           | 1         | 0.04%   |
| Kingston Technology              | 1         | 0.04%   |
| Huawei Technologies              | 1         | 0.04%   |
| Hewlett-Packard                  | 1         | 0.04%   |
| Focusrite-Novation               | 1         | 0.04%   |
| Corsair                          | 1         | 0.04%   |
| Cooler Master                    | 1         | 0.04%   |
| AudioQuest                       | 1         | 0.04%   |
| AKAI Professional M.I.           | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 213       | 7.92%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 202       | 7.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 178       | 6.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 149       | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 142       | 5.28%   |
| AMD FCH Azalia Controller                                                                         | 107       | 3.98%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 97        | 3.6%    |
| Intel 8 Series HD Audio Controller                                                                | 91        | 3.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 90        | 3.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 89        | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                | 85        | 3.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 3.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 75        | 2.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 61        | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 53        | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 52        | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 51        | 1.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 49        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 45        | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 39        | 1.45%   |
| AMD Wrestler HDMI Audio                                                                           | 39        | 1.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 39        | 1.45%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 1.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 31        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 29        | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 28        | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 25        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 25        | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 24        | 0.89%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 19        | 0.71%   |
| AMD Trinity HDMI Audio Controller                                                                 | 18        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 17        | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.63%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 17        | 0.63%   |
| AMD High Definition Audio Controller                                                              | 15        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.52%   |
| Nvidia High Definition Audio Controller                                                           | 13        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 517       | 27.24%  |
| SK hynix              | 474       | 24.97%  |
| Kingston              | 207       | 10.91%  |
| Unknown               | 201       | 10.59%  |
| Micron Technology     | 193       | 10.17%  |
| Elpida                | 64        | 3.37%   |
| Nanya Technology      | 63        | 3.32%   |
| Ramaxel Technology    | 40        | 2.11%   |
| A-DATA Technology     | 30        | 1.58%   |
| Crucial               | 23        | 1.21%   |
| Kingmax               | 15        | 0.79%   |
| ASint Technology      | 9         | 0.47%   |
| Qimonda               | 8         | 0.42%   |
| Corsair               | 8         | 0.42%   |
| 48spaces              | 8         | 0.42%   |
| Unknown (ABCD)        | 5         | 0.26%   |
| Transcend             | 5         | 0.26%   |
| Patriot               | 5         | 0.26%   |
| Apacer                | 3         | 0.16%   |
| Toshiba               | 2         | 0.11%   |
| Team                  | 2         | 0.11%   |
| Melco                 | 2         | 0.11%   |
| Kingmax Semiconductor | 2         | 0.11%   |
| Infineon              | 2         | 0.11%   |
| CSX                   | 2         | 0.11%   |
| Unknown (8A5B)        | 1         | 0.05%   |
| Unknown (09D5)        | 1         | 0.05%   |
| Strontium             | 1         | 0.05%   |
| SHARETRONIC           | 1         | 0.05%   |
| Memory Solution       | 1         | 0.05%   |
| Hikvision             | 1         | 0.05%   |
| G.Skill               | 1         | 0.05%   |
| Unknown               | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 41        | 2.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 35        | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 32        | 1.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 31        | 1.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 28        | 1.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 27        | 1.32%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 1.23%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 24        | 1.18%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 22        | 1.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 21        | 1.03%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 20        | 0.98%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 20        | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 18        | 0.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 18        | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 18        | 0.88%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 17        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 17        | 0.83%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 17        | 0.83%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 17        | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 16        | 0.78%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 16        | 0.78%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 15        | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.74%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s    | 15        | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 14        | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 13        | 0.64%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 13        | 0.64%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s     | 12        | 0.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s     | 11        | 0.54%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 11        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 11        | 0.54%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s     | 11        | 0.54%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 10        | 0.49%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 10        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 10        | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 10        | 0.49%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s      | 10        | 0.49%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s      | 10        | 0.49%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                  | 9         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 857       | 53.56%  |
| DDR4    | 347       | 21.69%  |
| DDR2    | 208       | 13%     |
| SDRAM   | 83        | 5.19%   |
| LPDDR4  | 34        | 2.13%   |
| Unknown | 24        | 1.5%    |
| DDR     | 18        | 1.13%   |
| LPDDR3  | 16        | 1%      |
| DRAM    | 8         | 0.5%    |
| DDR5    | 3         | 0.19%   |
| LPDDR5  | 2         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1509      | 96.67%  |
| Row Of Chips | 31        | 1.99%   |
| DIMM         | 14        | 0.9%    |
| Chip         | 7         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 687       | 39.41%  |
| 2048    | 460       | 26.39%  |
| 8192    | 326       | 18.7%   |
| 1024    | 155       | 8.89%   |
| 16384   | 79        | 4.53%   |
| 512     | 21        | 1.2%    |
| 32768   | 13        | 0.75%   |
| Unknown | 2         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 569       | 32.51%  |
| 2667    | 205       | 11.71%  |
| 1334    | 171       | 9.77%   |
| 667     | 130       | 7.43%   |
| 1333    | 84        | 4.8%    |
| 3200    | 77        | 4.4%    |
| 2400    | 77        | 4.4%    |
| 1067    | 72        | 4.11%   |
| Unknown | 59        | 3.37%   |
| 800     | 50        | 2.86%   |
| 2133    | 44        | 2.51%   |
| 4199    | 42        | 2.4%    |
| 2048    | 31        | 1.77%   |
| 533     | 26        | 1.49%   |
| 1066    | 19        | 1.09%   |
| 975     | 19        | 1.09%   |
| 3266    | 14        | 0.8%    |
| 1867    | 11        | 0.63%   |
| 333     | 10        | 0.57%   |
| 1639    | 8         | 0.46%   |
| 4266    | 6         | 0.34%   |
| 4800    | 4         | 0.23%   |
| 1776    | 4         | 0.23%   |
| 8400    | 3         | 0.17%   |
| 4267    | 3         | 0.17%   |
| 6400    | 2         | 0.11%   |
| 2267    | 2         | 0.11%   |
| 1866    | 2         | 0.11%   |
| 400     | 2         | 0.11%   |
| 3733    | 1         | 0.06%   |
| 2134    | 1         | 0.06%   |
| 1400    | 1         | 0.06%   |
| 200     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 50%     |
| Samsung Electronics   | 3         | 13.64%  |
| Brother Industries    | 3         | 13.64%  |
| Seiko Epson           | 1         | 4.55%   |
| Ricoh                 | 1         | 4.55%   |
| Oki Data              | 1         | 4.55%   |
| Lexmark International | 1         | 4.55%   |
| Canon                 | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Officejet J4500 series               | 2         | 9.09%   |
| HP DeskJet 2130 series                  | 2         | 9.09%   |
| Seiko Epson XP-243 245 247 Series       | 1         | 4.55%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.55%   |
| Samsung SCX-4200 series                 | 1         | 4.55%   |
| Samsung Composite Device                | 1         | 4.55%   |
| Ricoh SP 112                            | 1         | 4.55%   |
| Oki Data USB Device                     | 1         | 4.55%   |
| Lexmark International Lexmark X203n     | 1         | 4.55%   |
| HP LaserJet P1102                       | 1         | 4.55%   |
| HP LaserJet P1005                       | 1         | 4.55%   |
| HP LaserJet 1022                        | 1         | 4.55%   |
| HP LaserJet 1020                        | 1         | 4.55%   |
| HP LaserJet 1018                        | 1         | 4.55%   |
| HP DeskJet 5550                         | 1         | 4.55%   |
| HP Deskjet 1510                         | 1         | 4.55%   |
| Canon LiDE 400                          | 1         | 4.55%   |
| Brother PTUSB Printing                  | 1         | 4.55%   |
| Brother HL-1110 series                  | 1         | 4.55%   |
| Brother DCP-1610W                       | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 2         | 50%     |
| Siemens Information and Communication Products | 1         | 25%     |
| Mustek Systems                                 | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 25%     |
| Mustek Systems SNAPSCAN e22                                                     | 1         | 25%     |
| Canon CanoScan LIDE 25                                                          | 1         | 25%     |
| Canon CanoScan 4200F                                                            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 473       | 27.82%  |
| IMC Networks                           | 177       | 10.41%  |
| Microdia                               | 160       | 9.41%   |
| Realtek Semiconductor                  | 151       | 8.88%   |
| Sunplus Innovation Technology          | 122       | 7.18%   |
| Acer                                   | 95        | 5.59%   |
| Suyin                                  | 86        | 5.06%   |
| Quanta                                 | 65        | 3.82%   |
| Cheng Uei Precision Industry (Foxlink) | 60        | 3.53%   |
| Syntek                                 | 45        | 2.65%   |
| Lite-On Technology                     | 32        | 1.88%   |
| Silicon Motion                         | 31        | 1.82%   |
| Lenovo                                 | 30        | 1.76%   |
| Alcor Micro                            | 21        | 1.24%   |
| Primax Electronics                     | 20        | 1.18%   |
| Ricoh                                  | 16        | 0.94%   |
| Bison Electronics                      | 15        | 0.88%   |
| Z-Star Microelectronics                | 11        | 0.65%   |
| ALi                                    | 11        | 0.65%   |
| Luxvisions Innotech Limited            | 10        | 0.59%   |
| Logitech                               | 10        | 0.59%   |
| Apple                                  | 10        | 0.59%   |
| Importek                               | 9         | 0.53%   |
| Samsung Electronics                    | 8         | 0.47%   |
| OmniVision Technologies                | 5         | 0.29%   |
| GEMBIRD                                | 5         | 0.29%   |
| Sonix Technology                       | 4         | 0.24%   |
| DigiTech                               | 3         | 0.18%   |
| USB Camera                             | 2         | 0.12%   |
| Sunplus Technology                     | 2         | 0.12%   |
| Genesys Logic                          | 2         | 0.12%   |
| Xiaomi                                 | 1         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.06%   |
| Speed Tech                             | 1         | 0.06%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.06%   |
| MacroSilicon                           | 1         | 0.06%   |
| Holitech                               | 1         | 0.06%   |
| GoPro                                  | 1         | 0.06%   |
| eMPIA Technology                       | 1         | 0.06%   |
| Alpha Imaging Technology               | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 58        | 3.4%    |
| IMC Networks USB2.0 VGA UVC WebCam            | 54        | 3.17%   |
| Chicony HD WebCam                             | 45        | 2.64%   |
| Microdia Integrated_Webcam_HD                 | 43        | 2.52%   |
| Chicony HP TrueVision HD                      | 40        | 2.35%   |
| IMC Networks USB2.0 HD UVC WebCam             | 39        | 2.29%   |
| Acer Lenovo EasyCamera                        | 33        | 1.94%   |
| Sunplus Integrated_Webcam_HD                  | 30        | 1.76%   |
| Chicony USB2.0 VGA UVC WebCam                 | 29        | 1.7%    |
| Realtek Integrated_Webcam_HD                  | 28        | 1.64%   |
| Sunplus HP Truevision HD                      | 24        | 1.41%   |
| Microdia Integrated Webcam                    | 24        | 1.41%   |
| Chicony Lenovo EasyCamera                     | 23        | 1.35%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 22        | 1.29%   |
| Realtek USB Camera                            | 20        | 1.17%   |
| Sunplus HD WebCam                             | 19        | 1.12%   |
| IMC Networks EasyCamera                       | 18        | 1.06%   |
| Chicony USB2.0 HD UVC WebCam                  | 18        | 1.06%   |
| Chicony EasyCamera                            | 18        | 1.06%   |
| Quanta VGA WebCam                             | 17        | 1%      |
| Chicony VGA WebCam                            | 17        | 1%      |
| Chicony Integrated HP HD Webcam               | 17        | 1%      |
| Chicony FJ Camera                             | 17        | 1%      |
| Lenovo Integrated Webcam                      | 16        | 0.94%   |
| Realtek Integrated Webcam                     | 15        | 0.88%   |
| Primax HP HD Webcam [Fixed]                   | 14        | 0.82%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.82%   |
| IMC Networks Integrated Camera                | 14        | 0.82%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 14        | 0.82%   |
| Lenovo Integrated Webcam [R5U877]             | 13        | 0.76%   |
| Acer Lenovo Integrated Webcam                 | 13        | 0.76%   |
| Syntek Lenovo EasyCamera                      | 12        | 0.7%    |
| Realtek Lenovo EasyCamera                     | 12        | 0.7%    |
| Syntek Integrated Camera                      | 11        | 0.65%   |
| Syntek EasyCamera                             | 11        | 0.65%   |
| Silicon Motion WebCam SC-0311139N             | 11        | 0.65%   |
| Realtek USB2.0 VGA UVC WebCam                 | 11        | 0.65%   |
| Chicony 2.0M UVC Webcam / CNF7129             | 11        | 0.65%   |
| Suyin Acer CrystalEye Webcam                  | 10        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 99        | 38.98%  |
| AuthenTec                          | 56        | 22.05%  |
| Synaptics                          | 28        | 11.02%  |
| Upek                               | 22        | 8.66%   |
| Shenzhen Goodix Technology         | 16        | 6.3%    |
| LighTuning Technology              | 16        | 6.3%    |
| STMicroelectronics                 | 10        | 3.94%   |
| Elan Microelectronics              | 6         | 2.36%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 10.24%  |
| AuthenTec AES2810                                                          | 23        | 9.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 8.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 7.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.72%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 4.72%   |
| Validity Sensors VFS491                                                    | 10        | 3.94%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 3.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 3.94%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 3.54%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.76%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.36%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.36%   |
| LighTuning Fingerprint Reader                                              | 6         | 2.36%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.36%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.36%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.97%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.97%   |
| AuthenTec AES1600                                                          | 5         | 1.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.57%   |
| Synaptics  WBDI                                                            | 4         | 1.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.57%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.18%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.79%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.79%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.79%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.79%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.39%   |
| Synaptics WBDI Device                                                      | 1         | 0.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.39%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.39%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.39%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 114       | 55.61%  |
| Alcor Micro           | 31        | 15.12%  |
| Lenovo                | 27        | 13.17%  |
| O2 Micro              | 26        | 12.68%  |
| Upek                  | 3         | 1.46%   |
| Gemalto (was Gemplus) | 2         | 0.98%   |
| Yubico.com            | 1         | 0.49%   |
| Chicony Electronics   | 1         | 0.49%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 61        | 29.76%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 15.12%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 13.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 25        | 12.2%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 11.71%  |
| Broadcom 5880                                                                | 15        | 7.32%   |
| Broadcom 58200                                                               | 14        | 6.83%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.46%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.49%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.49%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.49%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.49%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.49%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1307      | 63.51%  |
| 1     | 602       | 29.25%  |
| 2     | 136       | 6.61%   |
| 3     | 11        | 0.53%   |
| 7     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 254       | 28.77%  |
| Chipcard                 | 192       | 21.74%  |
| Graphics card            | 179       | 20.27%  |
| Bluetooth                | 75        | 8.49%   |
| Net/wireless             | 55        | 6.23%   |
| Storage                  | 36        | 4.08%   |
| Multimedia controller    | 30        | 3.4%    |
| Flash memory             | 17        | 1.93%   |
| Camera                   | 17        | 1.93%   |
| Communication controller | 15        | 1.7%    |
| Sound                    | 4         | 0.45%   |
| Card reader              | 3         | 0.34%   |
| Modem                    | 2         | 0.23%   |
| Network                  | 1         | 0.11%   |
| Net/ethernet             | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |

