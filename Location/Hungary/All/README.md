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

Total: 7291

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | K52JB                       | Notebook    | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [da86fa8f75](https://linux-hardware.org/?probe=da86fa8f75) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [7b9f1f44c9](https://linux-hardware.org/?probe=7b9f1f44c9) | Mar 31, 2023 |
| HP            | Notebook                    | Notebook    | [ad90621225](https://linux-hardware.org/?probe=ad90621225) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [b055ccc048](https://linux-hardware.org/?probe=b055ccc048) | Mar 31, 2023 |
| ASRock        | H67DE3                      | Desktop     | [c82ba90d70](https://linux-hardware.org/?probe=c82ba90d70) | Mar 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [24b14fa9bb](https://linux-hardware.org/?probe=24b14fa9bb) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS07D0... | Notebook    | [7a8b075b23](https://linux-hardware.org/?probe=7a8b075b23) | Mar 29, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [ca97d61896](https://linux-hardware.org/?probe=ca97d61896) | Mar 29, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [4071aa0407](https://linux-hardware.org/?probe=4071aa0407) | Mar 29, 2023 |
| WinFast       | 6100M2MA FAB1.0             | Desktop     | [bed481b8ce](https://linux-hardware.org/?probe=bed481b8ce) | Mar 28, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [3f2f66842c](https://linux-hardware.org/?probe=3f2f66842c) | Mar 28, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [796d0b6775](https://linux-hardware.org/?probe=796d0b6775) | Mar 28, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [11c83c2356](https://linux-hardware.org/?probe=11c83c2356) | Mar 27, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ee7de6c56e](https://linux-hardware.org/?probe=ee7de6c56e) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [bc301a57a0](https://linux-hardware.org/?probe=bc301a57a0) | Mar 27, 2023 |
| Lenovo        | ThinkPad T420 4236W8L       | Notebook    | [e31b586083](https://linux-hardware.org/?probe=e31b586083) | Mar 27, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [fd675e2bf8](https://linux-hardware.org/?probe=fd675e2bf8) | Mar 27, 2023 |
| ASUSTek       | K56CA                       | Notebook    | [43f064cb46](https://linux-hardware.org/?probe=43f064cb46) | Mar 27, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [42f3323eed](https://linux-hardware.org/?probe=42f3323eed) | Mar 27, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [f24b69538d](https://linux-hardware.org/?probe=f24b69538d) | Mar 27, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [5006536f60](https://linux-hardware.org/?probe=5006536f60) | Mar 27, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2077f4f3ab](https://linux-hardware.org/?probe=2077f4f3ab) | Mar 27, 2023 |
| eMachines     | E725                        | Notebook    | [5212ab8375](https://linux-hardware.org/?probe=5212ab8375) | Mar 26, 2023 |
| eMachines     | E725                        | Notebook    | [8e1945a2c2](https://linux-hardware.org/?probe=8e1945a2c2) | Mar 26, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a663d3bc84](https://linux-hardware.org/?probe=a663d3bc84) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [bb1915d1c3](https://linux-hardware.org/?probe=bb1915d1c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [23df41ca86](https://linux-hardware.org/?probe=23df41ca86) | Mar 26, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8a92687be7](https://linux-hardware.org/?probe=8a92687be7) | Mar 26, 2023 |
| HP            | 8437                        | Desktop     | [cdc32d8d8b](https://linux-hardware.org/?probe=cdc32d8d8b) | Mar 25, 2023 |
| HP            | 8437                        | Desktop     | [6fbb459a03](https://linux-hardware.org/?probe=6fbb459a03) | Mar 25, 2023 |
| MSI           | G41M-P26                    | Desktop     | [b51977b3e0](https://linux-hardware.org/?probe=b51977b3e0) | Mar 24, 2023 |
| MSI           | G41M-P26                    | Desktop     | [a3f7279278](https://linux-hardware.org/?probe=a3f7279278) | Mar 24, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [ed6328937a](https://linux-hardware.org/?probe=ed6328937a) | Mar 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5d056a33d2](https://linux-hardware.org/?probe=5d056a33d2) | Mar 24, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [a375452089](https://linux-hardware.org/?probe=a375452089) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Notebook    | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| eMachines     | E725                        | Notebook    | [a5d9ff191b](https://linux-hardware.org/?probe=a5d9ff191b) | Mar 23, 2023 |
| eMachines     | E725                        | Notebook    | [4204fbff83](https://linux-hardware.org/?probe=4204fbff83) | Mar 23, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6da9274d93](https://linux-hardware.org/?probe=6da9274d93) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7000eb0f54](https://linux-hardware.org/?probe=7000eb0f54) | Mar 22, 2023 |
| THD           | PX1 01                      | Notebook    | [d210243a53](https://linux-hardware.org/?probe=d210243a53) | Mar 20, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [a5b4163b7b](https://linux-hardware.org/?probe=a5b4163b7b) | Mar 20, 2023 |
| THD           | PX1 01                      | Notebook    | [246c888564](https://linux-hardware.org/?probe=246c888564) | Mar 20, 2023 |
| HP            | 339A                        | Desktop     | [44b186c1a1](https://linux-hardware.org/?probe=44b186c1a1) | Mar 19, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [255de14ecc](https://linux-hardware.org/?probe=255de14ecc) | Mar 19, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [41d461b7c7](https://linux-hardware.org/?probe=41d461b7c7) | Mar 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [0b8157ef19](https://linux-hardware.org/?probe=0b8157ef19) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [79324bb5ca](https://linux-hardware.org/?probe=79324bb5ca) | Mar 19, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [aad9ecc316](https://linux-hardware.org/?probe=aad9ecc316) | Mar 19, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [f1db5ada96](https://linux-hardware.org/?probe=f1db5ada96) | Mar 18, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [338da8730f](https://linux-hardware.org/?probe=338da8730f) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | Desktop     | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [f955acfdcd](https://linux-hardware.org/?probe=f955acfdcd) | Mar 18, 2023 |
| HP            | Notebook                    | Notebook    | [aa27725a50](https://linux-hardware.org/?probe=aa27725a50) | Mar 18, 2023 |
| HP            | Notebook                    | Notebook    | [a3496c8509](https://linux-hardware.org/?probe=a3496c8509) | Mar 18, 2023 |
| MSI           | A55M-E33                    | Desktop     | [88511d02b5](https://linux-hardware.org/?probe=88511d02b5) | Mar 17, 2023 |
| MSI           | A55M-E33                    | Desktop     | [17422a4444](https://linux-hardware.org/?probe=17422a4444) | Mar 17, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [32fbf8242d](https://linux-hardware.org/?probe=32fbf8242d) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [b0fa0d95b6](https://linux-hardware.org/?probe=b0fa0d95b6) | Mar 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [871677af38](https://linux-hardware.org/?probe=871677af38) | Mar 17, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [a2fe86f9f4](https://linux-hardware.org/?probe=a2fe86f9f4) | Mar 17, 2023 |
| eMachines     | E725                        | Notebook    | [0ea3d3a0ca](https://linux-hardware.org/?probe=0ea3d3a0ca) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [afb256fb37](https://linux-hardware.org/?probe=afb256fb37) | Mar 16, 2023 |
| Dell          | Inspiron 14 5425            | Notebook    | [1128b14745](https://linux-hardware.org/?probe=1128b14745) | Mar 16, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [63015b2f93](https://linux-hardware.org/?probe=63015b2f93) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [966cfad104](https://linux-hardware.org/?probe=966cfad104) | Mar 15, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [b8585e81f9](https://linux-hardware.org/?probe=b8585e81f9) | Mar 15, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [c5b3c4f484](https://linux-hardware.org/?probe=c5b3c4f484) | Mar 15, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [809ad5e6ec](https://linux-hardware.org/?probe=809ad5e6ec) | Mar 15, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [0f5be9d999](https://linux-hardware.org/?probe=0f5be9d999) | Mar 15, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [2aa85f401e](https://linux-hardware.org/?probe=2aa85f401e) | Mar 15, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [cbb7c488cc](https://linux-hardware.org/?probe=cbb7c488cc) | Mar 15, 2023 |
| Gigabyte      | EG41MFT-US2H                | Desktop     | [992f5c7e77](https://linux-hardware.org/?probe=992f5c7e77) | Mar 15, 2023 |
| Gigabyte      | EG41MFT-US2H                | Desktop     | [fd4d8fac5f](https://linux-hardware.org/?probe=fd4d8fac5f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [d7fbdbbc9f](https://linux-hardware.org/?probe=d7fbdbbc9f) | Mar 15, 2023 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [34a0e74a78](https://linux-hardware.org/?probe=34a0e74a78) | Mar 15, 2023 |
| Sony          | VPCEB4L1E                   | Notebook    | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [aad6765ba3](https://linux-hardware.org/?probe=aad6765ba3) | Mar 14, 2023 |
| Acer          | Aspire C24-420              | All in one  | [04c483ee9b](https://linux-hardware.org/?probe=04c483ee9b) | Mar 14, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [0acca6eb92](https://linux-hardware.org/?probe=0acca6eb92) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [fbd3d08c57](https://linux-hardware.org/?probe=fbd3d08c57) | Mar 14, 2023 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [7f06c80526](https://linux-hardware.org/?probe=7f06c80526) | Mar 14, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [c628d02374](https://linux-hardware.org/?probe=c628d02374) | Mar 13, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [93effe5e22](https://linux-hardware.org/?probe=93effe5e22) | Mar 13, 2023 |
| HP            | ZBook Studio G4             | Notebook    | [2e04fad893](https://linux-hardware.org/?probe=2e04fad893) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| Insyde        | BayTrail                    | Notebook    | [8d0337a8ee](https://linux-hardware.org/?probe=8d0337a8ee) | Mar 12, 2023 |
| eMachines     | E725                        | Notebook    | [9a49d6defc](https://linux-hardware.org/?probe=9a49d6defc) | Mar 12, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [f3354208de](https://linux-hardware.org/?probe=f3354208de) | Mar 11, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [dfe2fe939b](https://linux-hardware.org/?probe=dfe2fe939b) | Mar 11, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [9a0daebfc5](https://linux-hardware.org/?probe=9a0daebfc5) | Mar 10, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [3f007adfc7](https://linux-hardware.org/?probe=3f007adfc7) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [447f2ec783](https://linux-hardware.org/?probe=447f2ec783) | Mar 09, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d8face90be](https://linux-hardware.org/?probe=d8face90be) | Mar 09, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [5bd46158a2](https://linux-hardware.org/?probe=5bd46158a2) | Mar 09, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [58123ca697](https://linux-hardware.org/?probe=58123ca697) | Mar 09, 2023 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [119aa3cec3](https://linux-hardware.org/?probe=119aa3cec3) | Mar 09, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [9d2a7db234](https://linux-hardware.org/?probe=9d2a7db234) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [eca94a98c0](https://linux-hardware.org/?probe=eca94a98c0) | Mar 09, 2023 |
| eMachines     | E725                        | Notebook    | [a4a1665906](https://linux-hardware.org/?probe=a4a1665906) | Mar 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [fc2ee93757](https://linux-hardware.org/?probe=fc2ee93757) | Mar 08, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [e1ce357347](https://linux-hardware.org/?probe=e1ce357347) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| eMachines     | E725                        | Notebook    | [8efce0fe6f](https://linux-hardware.org/?probe=8efce0fe6f) | Mar 08, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [cda5fafaf9](https://linux-hardware.org/?probe=cda5fafaf9) | Mar 07, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [c27eecca48](https://linux-hardware.org/?probe=c27eecca48) | Mar 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [85701c7290](https://linux-hardware.org/?probe=85701c7290) | Mar 07, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [5f336adb00](https://linux-hardware.org/?probe=5f336adb00) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [ee9717cba3](https://linux-hardware.org/?probe=ee9717cba3) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [77f0d6b014](https://linux-hardware.org/?probe=77f0d6b014) | Mar 07, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [267c62f49a](https://linux-hardware.org/?probe=267c62f49a) | Mar 07, 2023 |
| MSI           | Katana GF66 11UD            | Notebook    | [f464d5be92](https://linux-hardware.org/?probe=f464d5be92) | Mar 07, 2023 |
| ASUSTek       | GL552JX                     | Notebook    | [c8cff8908f](https://linux-hardware.org/?probe=c8cff8908f) | Mar 07, 2023 |
| ASUSTek       | ASUS P1512CEA_P1512CEA      | Notebook    | [ef2488509b](https://linux-hardware.org/?probe=ef2488509b) | Mar 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [57f7900a0d](https://linux-hardware.org/?probe=57f7900a0d) | Mar 06, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [f3cffe6df3](https://linux-hardware.org/?probe=f3cffe6df3) | Mar 06, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [da9dedfafa](https://linux-hardware.org/?probe=da9dedfafa) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [5d94a30450](https://linux-hardware.org/?probe=5d94a30450) | Mar 05, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [31d91c2f18](https://linux-hardware.org/?probe=31d91c2f18) | Mar 05, 2023 |
| Alcor         | SnugBook Q series           | Notebook    | [3b3c4fd9fd](https://linux-hardware.org/?probe=3b3c4fd9fd) | Mar 05, 2023 |
| HP            | 8597                        | Desktop     | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [3c4bf3c1bd](https://linux-hardware.org/?probe=3c4bf3c1bd) | Mar 05, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [c564adb32c](https://linux-hardware.org/?probe=c564adb32c) | Mar 04, 2023 |
| HP            | 650                         | Notebook    | [f595da7b8c](https://linux-hardware.org/?probe=f595da7b8c) | Mar 04, 2023 |
| HP            | 650                         | Notebook    | [9d0b38c967](https://linux-hardware.org/?probe=9d0b38c967) | Mar 04, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [4b6e4a874b](https://linux-hardware.org/?probe=4b6e4a874b) | Mar 04, 2023 |
| HP            | Compaq 6720s                | Notebook    | [b422954b5a](https://linux-hardware.org/?probe=b422954b5a) | Mar 03, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [4bab3eb831](https://linux-hardware.org/?probe=4bab3eb831) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [277d16fb2a](https://linux-hardware.org/?probe=277d16fb2a) | Mar 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ac82e74c8e](https://linux-hardware.org/?probe=ac82e74c8e) | Mar 02, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [f29ead8551](https://linux-hardware.org/?probe=f29ead8551) | Mar 01, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [9b0b5b79f0](https://linux-hardware.org/?probe=9b0b5b79f0) | Mar 01, 2023 |
| TCL Commun... | 8090                        | Notebook    | [d1f86443c7](https://linux-hardware.org/?probe=d1f86443c7) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [984b6e660d](https://linux-hardware.org/?probe=984b6e660d) | Feb 28, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [677c1ecc11](https://linux-hardware.org/?probe=677c1ecc11) | Feb 28, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [4f30a3b58d](https://linux-hardware.org/?probe=4f30a3b58d) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | Notebook    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [b4efb334ea](https://linux-hardware.org/?probe=b4efb334ea) | Feb 28, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [28e2b31136](https://linux-hardware.org/?probe=28e2b31136) | Feb 27, 2023 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [ad2f612788](https://linux-hardware.org/?probe=ad2f612788) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [7e64e6bc1b](https://linux-hardware.org/?probe=7e64e6bc1b) | Feb 27, 2023 |
| Dell          | Latitude 3510               | Notebook    | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [9548586341](https://linux-hardware.org/?probe=9548586341) | Feb 27, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [9cdb0f865a](https://linux-hardware.org/?probe=9cdb0f865a) | Feb 27, 2023 |
| Dell          | 0UP453                      | Desktop     | [e45bff8252](https://linux-hardware.org/?probe=e45bff8252) | Feb 26, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [e5fa16c859](https://linux-hardware.org/?probe=e5fa16c859) | Feb 25, 2023 |
| HP            | Unknown                     | Notebook    | [18a8d556cb](https://linux-hardware.org/?probe=18a8d556cb) | Feb 25, 2023 |
| Dell          | Vostro 14-5459              | Notebook    | [1f96898a48](https://linux-hardware.org/?probe=1f96898a48) | Feb 25, 2023 |
| HP            | Unknown                     | Notebook    | [dc26b08a65](https://linux-hardware.org/?probe=dc26b08a65) | Feb 25, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [5f15361f57](https://linux-hardware.org/?probe=5f15361f57) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1b60ef35ce](https://linux-hardware.org/?probe=1b60ef35ce) | Feb 24, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [3259617752](https://linux-hardware.org/?probe=3259617752) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [4d2d4ca208](https://linux-hardware.org/?probe=4d2d4ca208) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | Notebook    | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bf47e38ec4](https://linux-hardware.org/?probe=bf47e38ec4) | Feb 22, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [f2c76dc169](https://linux-hardware.org/?probe=f2c76dc169) | Feb 22, 2023 |
| Lenovo        | 7052-A9G                    | Desktop     | [fab92ac66f](https://linux-hardware.org/?probe=fab92ac66f) | Feb 22, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [c2be84fb6c](https://linux-hardware.org/?probe=c2be84fb6c) | Feb 21, 2023 |
| HP            | 250 G3                      | Notebook    | [638d8fa72b](https://linux-hardware.org/?probe=638d8fa72b) | Feb 21, 2023 |
| HP            | 250 G3                      | Notebook    | [eaf1a8a9ca](https://linux-hardware.org/?probe=eaf1a8a9ca) | Feb 21, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [d282ac975d](https://linux-hardware.org/?probe=d282ac975d) | Feb 21, 2023 |
| eMachines     | E725                        | Notebook    | [d982b1aa72](https://linux-hardware.org/?probe=d982b1aa72) | Feb 20, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [5df682e5d6](https://linux-hardware.org/?probe=5df682e5d6) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| ASUSTek       | K52F                        | Notebook    | [2cbb8f3f38](https://linux-hardware.org/?probe=2cbb8f3f38) | Feb 20, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f1b85863bc](https://linux-hardware.org/?probe=f1b85863bc) | Feb 20, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [3d8b32f453](https://linux-hardware.org/?probe=3d8b32f453) | Feb 20, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [b9ddd17e6c](https://linux-hardware.org/?probe=b9ddd17e6c) | Feb 19, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [22dfb58516](https://linux-hardware.org/?probe=22dfb58516) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [42099690a6](https://linux-hardware.org/?probe=42099690a6) | Feb 19, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [5fc896968e](https://linux-hardware.org/?probe=5fc896968e) | Feb 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c96027c178](https://linux-hardware.org/?probe=c96027c178) | Feb 19, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [54d3430de9](https://linux-hardware.org/?probe=54d3430de9) | Feb 19, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [c2168db120](https://linux-hardware.org/?probe=c2168db120) | Feb 18, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [40f71233c4](https://linux-hardware.org/?probe=40f71233c4) | Feb 17, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [44e9817292](https://linux-hardware.org/?probe=44e9817292) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4f7bc0d84](https://linux-hardware.org/?probe=a4f7bc0d84) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6bde6db60](https://linux-hardware.org/?probe=a6bde6db60) | Feb 17, 2023 |
| HP            | 3031h                       | Desktop     | [f3d2748999](https://linux-hardware.org/?probe=f3d2748999) | Feb 17, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [6d7740ca9d](https://linux-hardware.org/?probe=6d7740ca9d) | Feb 17, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [fb9eb2345d](https://linux-hardware.org/?probe=fb9eb2345d) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [4f0e88ce52](https://linux-hardware.org/?probe=4f0e88ce52) | Feb 16, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [eac8d6ab9d](https://linux-hardware.org/?probe=eac8d6ab9d) | Feb 16, 2023 |
| HP            | 250 G1                      | Notebook    | [a673746c67](https://linux-hardware.org/?probe=a673746c67) | Feb 16, 2023 |
| Dell          | 0UT806                      | Desktop     | [0d1cdcdbe9](https://linux-hardware.org/?probe=0d1cdcdbe9) | Feb 16, 2023 |
| HP            | 250 G1                      | Notebook    | [cc5e272ca9](https://linux-hardware.org/?probe=cc5e272ca9) | Feb 16, 2023 |
| Lenovo        | ThinkCentre M58p 9728W47    | Desktop     | [9d197fed1d](https://linux-hardware.org/?probe=9d197fed1d) | Feb 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [33b1f65ec0](https://linux-hardware.org/?probe=33b1f65ec0) | Feb 15, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [2ae439ec07](https://linux-hardware.org/?probe=2ae439ec07) | Feb 15, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [7b40745c7f](https://linux-hardware.org/?probe=7b40745c7f) | Feb 14, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [903deba17a](https://linux-hardware.org/?probe=903deba17a) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [fd6bd7275b](https://linux-hardware.org/?probe=fd6bd7275b) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | Notebook    | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| ZOTAC         | ZBOXNANO-AD12               | Mini pc     | [3a6297d90b](https://linux-hardware.org/?probe=3a6297d90b) | Feb 13, 2023 |
| ZOTAC         | ZBOXNANO-AD12               | Mini pc     | [fdc4af9146](https://linux-hardware.org/?probe=fdc4af9146) | Feb 13, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [9538925092](https://linux-hardware.org/?probe=9538925092) | Feb 13, 2023 |
| ASRock        | 4Core1600P35-WiFi+          | Desktop     | [7901a0c0ec](https://linux-hardware.org/?probe=7901a0c0ec) | Feb 13, 2023 |
| ASRock        | 4Core1600P35-WiFi+          | Desktop     | [fc5af11584](https://linux-hardware.org/?probe=fc5af11584) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [65815ad972](https://linux-hardware.org/?probe=65815ad972) | Feb 13, 2023 |
| Gigabyte      | H55-UD3H                    | Desktop     | [0d0c742e0e](https://linux-hardware.org/?probe=0d0c742e0e) | Feb 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| Acer          | TravelMate 8571             | Notebook    | [609cc404fb](https://linux-hardware.org/?probe=609cc404fb) | Feb 12, 2023 |
| HP            | Compaq 6910p                | Notebook    | [328acaf5ee](https://linux-hardware.org/?probe=328acaf5ee) | Feb 12, 2023 |
| ASUSTek       | K52F                        | Notebook    | [ee35b00a7e](https://linux-hardware.org/?probe=ee35b00a7e) | Feb 12, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [e27e733bc0](https://linux-hardware.org/?probe=e27e733bc0) | Feb 12, 2023 |
| ASUSTek       | K52F                        | Notebook    | [364c41f9aa](https://linux-hardware.org/?probe=364c41f9aa) | Feb 11, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [eb1f7dfd26](https://linux-hardware.org/?probe=eb1f7dfd26) | Feb 10, 2023 |
| GIADA         | SHARKBAY JHS60C             | Desktop     | [71ce3b4e41](https://linux-hardware.org/?probe=71ce3b4e41) | Feb 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [05a6c712af](https://linux-hardware.org/?probe=05a6c712af) | Feb 09, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [4c34dd05d8](https://linux-hardware.org/?probe=4c34dd05d8) | Feb 09, 2023 |
| Dell          | Latitude E6230              | Notebook    | [d0a04b130a](https://linux-hardware.org/?probe=d0a04b130a) | Feb 09, 2023 |
| Dell          | Latitude E6230              | Notebook    | [11a1ba46f3](https://linux-hardware.org/?probe=11a1ba46f3) | Feb 09, 2023 |
| GIADA         | SHARKBAY JHS60C             | Desktop     | [91ca210b25](https://linux-hardware.org/?probe=91ca210b25) | Feb 09, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| HP            | 2129                        | Desktop     | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| MSI           | GX70 3CC                    | Notebook    | [c9abc5f038](https://linux-hardware.org/?probe=c9abc5f038) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [dd6c2cbcc6](https://linux-hardware.org/?probe=dd6c2cbcc6) | Feb 07, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [470857588f](https://linux-hardware.org/?probe=470857588f) | Feb 07, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [62acbef04d](https://linux-hardware.org/?probe=62acbef04d) | Feb 07, 2023 |
| ASUSTek       | P5G41-M SI/DVI              | Desktop     | [d7568a0cef](https://linux-hardware.org/?probe=d7568a0cef) | Feb 07, 2023 |
| HP            | Unknown                     | Notebook    | [eb01c0393d](https://linux-hardware.org/?probe=eb01c0393d) | Feb 07, 2023 |
| HP            | Unknown                     | Notebook    | [db607a1e03](https://linux-hardware.org/?probe=db607a1e03) | Feb 07, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [560142c79d](https://linux-hardware.org/?probe=560142c79d) | Feb 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0374aed4ef](https://linux-hardware.org/?probe=0374aed4ef) | Feb 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [1031465bf3](https://linux-hardware.org/?probe=1031465bf3) | Feb 06, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [a1aa0cc1e1](https://linux-hardware.org/?probe=a1aa0cc1e1) | Feb 06, 2023 |
| Lenovo        | ThinkPad T490 20N3S11B0V    | Notebook    | [3b35d51bfb](https://linux-hardware.org/?probe=3b35d51bfb) | Feb 06, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [8884f6f6dd](https://linux-hardware.org/?probe=8884f6f6dd) | Feb 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [349dc10d17](https://linux-hardware.org/?probe=349dc10d17) | Feb 05, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [8b6fbfa8f5](https://linux-hardware.org/?probe=8b6fbfa8f5) | Feb 04, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [4fd635a0c1](https://linux-hardware.org/?probe=4fd635a0c1) | Feb 04, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [62e5203c26](https://linux-hardware.org/?probe=62e5203c26) | Feb 04, 2023 |
| MSI           | MS-7817                     | Desktop     | [8ce9e243df](https://linux-hardware.org/?probe=8ce9e243df) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [2b37c84303](https://linux-hardware.org/?probe=2b37c84303) | Feb 04, 2023 |
| MSI           | MS-7817                     | Desktop     | [bc7ccb9f9c](https://linux-hardware.org/?probe=bc7ccb9f9c) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [bb7b67d9ef](https://linux-hardware.org/?probe=bb7b67d9ef) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [a1ea4874cf](https://linux-hardware.org/?probe=a1ea4874cf) | Feb 03, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [b77d4e1211](https://linux-hardware.org/?probe=b77d4e1211) | Feb 02, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [0e7aba127e](https://linux-hardware.org/?probe=0e7aba127e) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Dell          | Latitude D630               | Notebook    | [7f34868246](https://linux-hardware.org/?probe=7f34868246) | Feb 02, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [fb42f48fbe](https://linux-hardware.org/?probe=fb42f48fbe) | Feb 01, 2023 |
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
| BlackPanther 18.1            | 1930      | 50.35%  |
| Ubuntu 20.04                 | 269       | 7.02%   |
| BlackPanther 16.2            | 222       | 5.79%   |
| Ubuntu 18.04                 | 155       | 4.04%   |
| Ubuntu 22.04                 | 80        | 2.09%   |
| OpenMandriva 4.2             | 59        | 1.54%   |
| Debian 11                    | 46        | 1.2%    |
| OpenMandriva 4.3             | 35        | 0.91%   |
| Linux Mint 20.2              | 31        | 0.81%   |
| Zorin 16                     | 25        | 0.65%   |
| Arch Rolling                 | 25        | 0.65%   |
| Arch                         | 25        | 0.65%   |
| Ubuntu 19.10                 | 23        | 0.6%    |
| Linux Mint 19.3              | 22        | 0.57%   |
| Debian 10                    | 21        | 0.55%   |
| Linux Mint 20.3              | 20        | 0.52%   |
| Linux Mint 20                | 20        | 0.52%   |
| Kubuntu 20.04                | 20        | 0.52%   |
| Xubuntu 20.04                | 19        | 0.5%    |
| Ubuntu 21.10                 | 19        | 0.5%    |
| Ubuntu 19.04                 | 19        | 0.5%    |
| KDE neon 20.04               | 19        | 0.5%    |
| Fedora 36                    | 19        | 0.5%    |
| Xubuntu 18.04                | 17        | 0.44%   |
| Ubuntu 21.04                 | 17        | 0.44%   |
| Manjaro                      | 17        | 0.44%   |
| ArcoLinux Rolling            | 17        | 0.44%   |
| Pop!_OS 22.04                | 15        | 0.39%   |
| OpenMandriva 4.50            | 15        | 0.39%   |
| Linux Mint 20.1              | 15        | 0.39%   |
| Fedora 35                    | 15        | 0.39%   |
| OpenMandriva 23.01           | 14        | 0.37%   |
| Fedora 37                    | 14        | 0.37%   |
| Fedora 33                    | 14        | 0.37%   |
| Ubuntu 20.10                 | 13        | 0.34%   |
| Fedora 32                    | 13        | 0.34%   |
| Zorin 15                     | 12        | 0.31%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 0.31%   |
| Linux Mint 21                | 11        | 0.29%   |
| Linux Mint 21.1              | 10        | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| BlackPanther  | 2112      | 57.44%  |
| Ubuntu        | 584       | 15.88%  |
| OpenMandriva  | 136       | 3.7%    |
| Linux Mint    | 132       | 3.59%   |
| Endless       | 81        | 2.2%    |
| Debian        | 80        | 2.18%   |
| Fedora        | 76        | 2.07%   |
| Arch          | 49        | 1.33%   |
| Manjaro       | 46        | 1.25%   |
| Xubuntu       | 44        | 1.2%    |
| Kubuntu       | 44        | 1.2%    |
| Pop!_OS       | 38        | 1.03%   |
| Zorin         | 37        | 1.01%   |
| KDE neon      | 24        | 0.65%   |
| ROSA          | 21        | 0.57%   |
| ArcoLinux     | 21        | 0.57%   |
| openSUSE      | 18        | 0.49%   |
| Ubuntu MATE   | 17        | 0.46%   |
| Ubuntu Unity  | 15        | 0.41%   |
| Lubuntu       | 15        | 0.41%   |
| Kali          | 9         | 0.24%   |
| Gentoo        | 8         | 0.22%   |
| Elementary    | 8         | 0.22%   |
| Ubuntu Budgie | 5         | 0.14%   |
| Raspbian      | 5         | 0.14%   |
| MX            | 4         | 0.11%   |
| LMDE          | 4         | 0.11%   |
| EndeavourOS   | 4         | 0.11%   |
| Clear Linux   | 4         | 0.11%   |
| SteamOS       | 3         | 0.08%   |
| Nobara        | 3         | 0.08%   |
| Xero          | 2         | 0.05%   |
| UbuntuDDE     | 2         | 0.05%   |
| Rocky Linux   | 2         | 0.05%   |
| Garuda Linux  | 2         | 0.05%   |
| Devuan        | 2         | 0.05%   |
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
| 4.18.16-desktop-1bP      | 1453      | 34.55%  |
| 5.6.14-desktop-2bP       | 591       | 14.05%  |
| 4.9.20-desktop-pae-1bP   | 205       | 4.87%   |
| 5.1.15-desktop-1bP       | 84        | 2%      |
| 5.10.14-desktop-1omv4002 | 55        | 1.31%   |
| 5.4.0-42-generic         | 42        | 1%      |
| 5.16.7-desktop-1omv4003  | 34        | 0.81%   |
| 5.4.0-58-generic         | 27        | 0.64%   |
| 5.8.0-14-generic         | 24        | 0.57%   |
| 5.4.0-52-generic         | 21        | 0.5%    |
| 5.4.0-48-generic         | 19        | 0.45%   |
| 5.11.0-27-generic        | 19        | 0.45%   |
| 5.15.0-56-generic        | 15        | 0.36%   |
| 6.1.1-desktop-1omv2290   | 14        | 0.33%   |
| 5.3.0-28-generic         | 14        | 0.33%   |
| 5.15.0-52-generic        | 14        | 0.33%   |
| 5.15.0-43-generic        | 14        | 0.33%   |
| 4.18.0-15-generic        | 14        | 0.33%   |
| 5.4.0-54-generic         | 13        | 0.31%   |
| 5.4.0-40-generic         | 13        | 0.31%   |
| 5.4.0-19-generic         | 13        | 0.31%   |
| 5.15.0-58-generic        | 13        | 0.31%   |
| 5.11.0-34-generic        | 13        | 0.31%   |
| 5.4.0-29-generic         | 12        | 0.29%   |
| 4.15.0-43-generic        | 12        | 0.29%   |
| 5.4.0-91-generic         | 11        | 0.26%   |
| 5.4.0-26-generic         | 11        | 0.26%   |
| 5.15.0-46-generic        | 11        | 0.26%   |
| 5.15.0-41-generic        | 11        | 0.26%   |
| 5.11.0-43-generic        | 11        | 0.26%   |
| 5.8.0-43-generic         | 10        | 0.24%   |
| 5.3.0-46-generic         | 10        | 0.24%   |
| 5.13.0-27-generic        | 10        | 0.24%   |
| 5.0.0-37-generic         | 10        | 0.24%   |
| 5.8.0-59-generic         | 9         | 0.21%   |
| 5.8.0-53-generic         | 9         | 0.21%   |
| 5.4.0-39-generic         | 9         | 0.21%   |
| 5.4.0-100-generic        | 9         | 0.21%   |
| 5.19.0-35-generic        | 9         | 0.21%   |
| 5.15.0-47-generic        | 9         | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.16 | 1453      | 35.56%  |
| 5.6.14  | 592       | 14.49%  |
| 5.4.0   | 335       | 8.2%    |
| 4.9.20  | 216       | 5.29%   |
| 5.15.0  | 136       | 3.33%   |
| 4.15.0  | 115       | 2.81%   |
| 5.8.0   | 102       | 2.5%    |
| 5.11.0  | 102       | 2.5%    |
| 5.1.15  | 85        | 2.08%   |
| 5.3.0   | 81        | 1.98%   |
| 5.13.0  | 79        | 1.93%   |
| 5.0.0   | 56        | 1.37%   |
| 5.10.14 | 55        | 1.35%   |
| 5.10.0  | 54        | 1.32%   |
| 4.18.0  | 39        | 0.95%   |
| 5.16.7  | 35        | 0.86%   |
| 5.19.0  | 24        | 0.59%   |
| 4.19.0  | 22        | 0.54%   |
| 6.1.1   | 18        | 0.44%   |
| 6.0.12  | 9         | 0.22%   |
| 5.16.0  | 9         | 0.22%   |
| 5.12.4  | 9         | 0.22%   |
| 4.13.0  | 9         | 0.22%   |
| 5.18.12 | 8         | 0.2%    |
| 5.14.0  | 8         | 0.2%    |
| 4.4.0   | 8         | 0.2%    |
| 5.13.13 | 7         | 0.17%   |
| 6.2.6   | 6         | 0.15%   |
| 5.9.16  | 6         | 0.15%   |
| 5.9.0   | 6         | 0.15%   |
| 6.1.0   | 5         | 0.12%   |
| 6.0.0   | 5         | 0.12%   |
| 5.19.12 | 5         | 0.12%   |
| 5.18.0  | 5         | 0.12%   |
| 5.17.1  | 5         | 0.12%   |
| 5.15.12 | 5         | 0.12%   |
| 5.12.9  | 5         | 0.12%   |
| 5.10.7  | 5         | 0.12%   |
| 4.9.60  | 5         | 0.12%   |
| 4.7.0   | 5         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 1491      | 36.71%  |
| 5.6     | 607       | 14.94%  |
| 5.4     | 358       | 8.81%   |
| 4.9     | 228       | 5.61%   |
| 5.15    | 174       | 4.28%   |
| 5.10    | 135       | 3.32%   |
| 5.11    | 122       | 3%      |
| 5.8     | 118       | 2.9%    |
| 4.15    | 115       | 2.83%   |
| 5.13    | 91        | 2.24%   |
| 5.1     | 88        | 2.17%   |
| 5.3     | 87        | 2.14%   |
| 5.16    | 62        | 1.53%   |
| 5.0     | 56        | 1.38%   |
| 5.19    | 47        | 1.16%   |
| 6.1     | 38        | 0.94%   |
| 6.0     | 30        | 0.74%   |
| 5.18    | 29        | 0.71%   |
| 5.9     | 25        | 0.62%   |
| 4.19    | 24        | 0.59%   |
| 5.14    | 23        | 0.57%   |
| 5.12    | 23        | 0.57%   |
| 5.17    | 17        | 0.42%   |
| 5.7     | 16        | 0.39%   |
| 6.2     | 13        | 0.32%   |
| 4.13    | 9         | 0.22%   |
| 4.4     | 8         | 0.2%    |
| 5.5     | 7         | 0.17%   |
| 4.7     | 5         | 0.12%   |
| 4.16    | 4         | 0.1%    |
| 4.5     | 2         | 0.05%   |
| 4.20    | 2         | 0.05%   |
| 4.14    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 5.2     | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3310      | 92.02%  |
| i686    | 277       | 7.7%    |
| armv7l  | 4         | 0.11%   |
| aarch64 | 3         | 0.08%   |
| armv6l  | 2         | 0.06%   |
| unknow  | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 2331      | 63.48%  |
| GNOME           | 663       | 18.06%  |
| Unknown         | 240       | 6.54%   |
| XFCE            | 121       | 3.3%    |
| X-Cinnamon      | 97        | 2.64%   |
| MATE            | 58        | 1.58%   |
| KDE             | 38        | 1.03%   |
| Cinnamon        | 29        | 0.79%   |
| LXQt            | 19        | 0.52%   |
| Unity           | 15        | 0.41%   |
| KDE4            | 14        | 0.38%   |
| i3              | 8         | 0.22%   |
| Pantheon        | 7         | 0.19%   |
| Deepin          | 7         | 0.19%   |
| LXDE            | 6         | 0.16%   |
| Budgie          | 6         | 0.16%   |
| GNOME Flashback | 5         | 0.14%   |
| GNOME Classic   | 2         | 0.05%   |
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
| X11     | 3250      | 89.9%   |
| Wayland | 195       | 5.39%   |
| Unknown | 140       | 3.87%   |
| Tty     | 29        | 0.8%    |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2320      | 63.39%  |
| Unknown | 784       | 21.42%  |
| GDM     | 165       | 4.51%   |
| GDM3    | 157       | 4.29%   |
| LightDM | 148       | 4.04%   |
| TDM     | 64        | 1.75%   |
| KDM     | 14        | 0.38%   |
| SLiM    | 5         | 0.14%   |
| XDM     | 3         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2279      | 62.39%  |
| hu_HU      | 829       | 22.69%  |
| en_US      | 439       | 12.02%  |
| en_GB      | 44        | 1.2%    |
| C          | 24        | 0.66%   |
| de_DE      | 16        | 0.44%   |
| ru_UA      | 3         | 0.08%   |
| ru_RU      | 3         | 0.08%   |
| POSIX      | 2         | 0.05%   |
| nl_NL      | 2         | 0.05%   |
| hu_HU.UTF8 | 2         | 0.05%   |
| en_AU      | 2         | 0.05%   |
| C.UTF8     | 2         | 0.05%   |
| it_IT      | 1         | 0.03%   |
| fr_FR      | 1         | 0.03%   |
| fr_BE      | 1         | 0.03%   |
| en_ZA      | 1         | 0.03%   |
| en_AG      | 1         | 0.03%   |
| de_AT      | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2356      | 63.59%  |
| EFI  | 1349      | 36.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2064      | 53.29%  |
| Overlay | 1585      | 40.92%  |
| Btrfs   | 103       | 2.66%   |
| Unknown | 79        | 2.04%   |
| Xfs     | 13        | 0.34%   |
| Zfs     | 9         | 0.23%   |
| Ext2    | 9         | 0.23%   |
| Ext3    | 7         | 0.18%   |
| F2fs    | 2         | 0.05%   |
| XXXXXXX | 1         | 0.03%   |
| Tmpfs   | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 1693      | 45.34%  |
| GPT     | 1191      | 31.9%   |
| Unknown | 850       | 22.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2832      | 73.69%  |
| Yes       | 1011      | 26.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2028      | 53.74%  |
| Yes       | 1746      | 46.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 599       | 16.84%  |
| Hewlett-Packard         | 545       | 15.33%  |
| Dell                    | 505       | 14.2%   |
| Lenovo                  | 488       | 13.72%  |
| Gigabyte Technology     | 296       | 8.32%   |
| ASRock                  | 249       | 7%      |
| Acer                    | 243       | 6.83%   |
| MSI                     | 112       | 3.15%   |
| Fujitsu                 | 73        | 2.05%   |
| Fujitsu Siemens         | 60        | 1.69%   |
| Toshiba                 | 57        | 1.6%    |
| Samsung Electronics     | 37        | 1.04%   |
| Packard Bell            | 29        | 0.82%   |
| Intel                   | 29        | 0.82%   |
| Medion                  | 22        | 0.62%   |
| eMachines               | 20        | 0.56%   |
| Apple                   | 18        | 0.51%   |
| Unknown                 | 18        | 0.51%   |
| Sony                    | 14        | 0.39%   |
| Foxconn                 | 14        | 0.39%   |
| Alcor                   | 8         | 0.22%   |
| Raspberry Pi Foundation | 7         | 0.2%    |
| Hungaro Flotta Kft      | 7         | 0.2%    |
| HUAWEI                  | 6         | 0.17%   |
| Pegatron                | 5         | 0.14%   |
| Supermicro              | 4         | 0.11%   |
| Insyde                  | 4         | 0.11%   |
| Biostar                 | 4         | 0.11%   |
| ZOTAC                   | 3         | 0.08%   |
| Timi                    | 3         | 0.08%   |
| Microsoft               | 3         | 0.08%   |
| Clevo                   | 3         | 0.08%   |
| AOpen                   | 3         | 0.08%   |
| AMI                     | 3         | 0.08%   |
| ABIT                    | 3         | 0.08%   |
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
| HP 250 G1                            | 41        | 1.15%   |
| ASRock FM2A75M Pro4+                 | 33        | 0.93%   |
| ASUS All Series                      | 28        | 0.79%   |
| Unknown                              | 28        | 0.79%   |
| Dell OptiPlex 3020                   | 17        | 0.48%   |
| Dell Latitude E6410                  | 17        | 0.48%   |
| HP 650                               | 13        | 0.37%   |
| HP Notebook                          | 12        | 0.34%   |
| ASUS P5KPL-AM EPU                    | 12        | 0.34%   |
| Gigabyte G31M-ES2L                   | 11        | 0.31%   |
| Dell OptiPlex 755                    | 11        | 0.31%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 10        | 0.28%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 10        | 0.28%   |
| Lenovo G50-45 80E3                   | 10        | 0.28%   |
| HP 620                               | 10        | 0.28%   |
| Dell OptiPlex 780                    | 10        | 0.28%   |
| Dell OptiPlex 760                    | 9         | 0.25%   |
| Dell Latitude E6400                  | 9         | 0.25%   |
| Lenovo ThinkPad T400 2768WGB         | 8         | 0.22%   |
| HP Pavilion 15                       | 8         | 0.22%   |
| HP EliteBook 8460p                   | 8         | 0.22%   |
| Gigabyte H61M-S1                     | 8         | 0.22%   |
| Dell Precision WorkStation T3500     | 8         | 0.22%   |
| Dell OptiPlex 7010                   | 8         | 0.22%   |
| Dell Latitude E6530                  | 8         | 0.22%   |
| Dell Latitude E6420                  | 8         | 0.22%   |
| ASRock G41M-VS3                      | 8         | 0.22%   |
| Lenovo Z50-75 80EC                   | 7         | 0.2%    |
| Lenovo G550 20023                    | 7         | 0.2%    |
| HP ProDesk 600 G2 SFF                | 7         | 0.2%    |
| HP EliteBook 6930p                   | 7         | 0.2%    |
| Gigabyte 970A-DS3P                   | 7         | 0.2%    |
| Dell Inspiron 15-3567                | 7         | 0.2%    |
| ASUS X541NA                          | 7         | 0.2%    |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.2%    |
| ASRock N68C-S UCC                    | 7         | 0.2%    |
| MSI MS-7592                          | 6         | 0.17%   |
| Lenovo Z50-70 20354                  | 6         | 0.17%   |
| Lenovo G580 20150                    | 6         | 0.17%   |
| HP Pavilion g6                       | 6         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 182       | 5.12%   |
| Dell Latitude           | 176       | 4.95%   |
| Acer Aspire             | 161       | 4.53%   |
| HP Compaq               | 126       | 3.54%   |
| Dell OptiPlex           | 117       | 3.29%   |
| Dell Inspiron           | 113       | 3.18%   |
| Lenovo IdeaPad          | 105       | 2.95%   |
| HP EliteBook            | 90        | 2.53%   |
| HP 250                  | 59        | 1.66%   |
| ASUS VivoBook           | 58        | 1.63%   |
| HP ProBook              | 57        | 1.6%    |
| Toshiba Satellite       | 51        | 1.43%   |
| HP Pavilion             | 48        | 1.35%   |
| Lenovo ThinkCentre      | 47        | 1.32%   |
| ASUS PRIME              | 41        | 1.15%   |
| Dell Vostro             | 35        | 0.98%   |
| ASRock FM2A75M          | 33        | 0.93%   |
| Fujitsu ESPRIMO         | 31        | 0.87%   |
| Packard Bell EasyNote   | 29        | 0.82%   |
| ASUS ROG                | 29        | 0.82%   |
| Fujitsu Siemens ESPRIMO | 28        | 0.79%   |
| Dell Precision          | 28        | 0.79%   |
| ASUS All                | 28        | 0.79%   |
| Unknown                 | 28        | 0.79%   |
| Fujitsu LIFEBOOK        | 27        | 0.76%   |
| Fujitsu Siemens AMILO   | 21        | 0.59%   |
| ASUS TUF                | 19        | 0.53%   |
| Acer TravelMate         | 19        | 0.53%   |
| HP Laptop               | 18        | 0.51%   |
| ASUS P5KPL-AM           | 17        | 0.48%   |
| Acer Veriton            | 16        | 0.45%   |
| Gigabyte B450           | 14        | 0.39%   |
| Acer Swift              | 14        | 0.39%   |
| HP 650                  | 13        | 0.37%   |
| HP Notebook             | 12        | 0.34%   |
| HP ZBook                | 11        | 0.31%   |
| Gigabyte G31M-ES2L      | 11        | 0.31%   |
| Lenovo G50-45           | 10        | 0.28%   |
| Lenovo 3000             | 10        | 0.28%   |
| HP ProDesk              | 10        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 333       | 9.36%   |
| 2011    | 330       | 9.28%   |
| 2010    | 313       | 8.8%    |
| 2012    | 309       | 8.69%   |
| 2018    | 272       | 7.65%   |
| 2014    | 258       | 7.26%   |
| 2008    | 250       | 7.03%   |
| 2009    | 248       | 6.97%   |
| 2015    | 200       | 5.62%   |
| 2017    | 188       | 5.29%   |
| 2007    | 180       | 5.06%   |
| 2016    | 179       | 5.03%   |
| 2019    | 152       | 4.27%   |
| 2020    | 121       | 3.4%    |
| 2006    | 81        | 2.28%   |
| 2021    | 68        | 1.91%   |
| 2005    | 28        | 0.79%   |
| 2022    | 27        | 0.76%   |
| Unknown | 12        | 0.34%   |
| 2004    | 4         | 0.11%   |
| 2003    | 3         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2002      | 56.3%   |
| Desktop        | 1454      | 40.89%  |
| Convertible    | 25        | 0.7%    |
| All in one     | 25        | 0.7%    |
| Mini pc        | 21        | 0.59%   |
| Server         | 11        | 0.31%   |
| System on chip | 9         | 0.25%   |
| Tablet         | 9         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3452      | 96.67%  |
| Enabled  | 119       | 3.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3556      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1157      | 31.52%  |
| 4.01-8.0    | 775       | 21.11%  |
| 8.01-16.0   | 628       | 17.11%  |
| 16.01-24.0  | 393       | 10.71%  |
| 1.01-2.0    | 360       | 9.81%   |
| 32.01-64.0  | 133       | 3.62%   |
| 2.01-3.0    | 127       | 3.46%   |
| 0.51-1.0    | 41        | 1.12%   |
| 24.01-32.0  | 28        | 0.76%   |
| 64.01-256.0 | 26        | 0.71%   |
| 0.01-0.5    | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 1306      | 31.41%  |
| 1.01-2.0    | 1232      | 29.63%  |
| 0.01-0.5    | 664       | 15.97%  |
| 2.01-3.0    | 465       | 11.18%  |
| 3.01-4.0    | 212       | 5.1%    |
| 4.01-8.0    | 205       | 4.93%   |
| 8.01-16.0   | 61        | 1.47%   |
| 16.01-24.0  | 10        | 0.24%   |
| 32.01-64.0  | 1         | 0.02%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2450      | 65.04%  |
| 2       | 834       | 22.14%  |
| 3       | 265       | 7.03%   |
| 4       | 99        | 2.63%   |
| 5       | 45        | 1.19%   |
| 0       | 45        | 1.19%   |
| 6       | 12        | 0.32%   |
| 8       | 5         | 0.13%   |
| 7       | 5         | 0.13%   |
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
| Yes       | 2003      | 55.21%  |
| No        | 1625      | 44.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3313      | 93.01%  |
| No        | 249       | 6.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2436      | 67.82%  |
| No        | 1156      | 32.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1854      | 51.34%  |
| Yes       | 1757      | 48.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Hungary | 3556      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Budapest          | 1384      | 33.53%  |
| Szeged            | 89        | 2.16%   |
| Pécs             | 87        | 2.11%   |
| Debrecen          | 82        | 1.99%   |
| Miskolc           | 80        | 1.94%   |
| Győr             | 79        | 1.91%   |
| Tatabánya        | 70        | 1.7%    |
| Székesfehérvár | 55        | 1.33%   |
| Kecskemét        | 51        | 1.24%   |
| Szombathely       | 50        | 1.21%   |
| Érd              | 42        | 1.02%   |
| Nyiregyhaza       | 39        | 0.94%   |
| Szigetszentmiklos | 37        | 0.9%    |
| Szekszárd        | 36        | 0.87%   |
| Veszprém         | 35        | 0.85%   |
| Zalaegerszeg      | 33        | 0.8%    |
| Karcag            | 31        | 0.75%   |
| Szolnok           | 28        | 0.68%   |
| Dunaújváros     | 26        | 0.63%   |
| Oroshaza          | 25        | 0.61%   |
| Gödöllő        | 25        | 0.61%   |
| Nagykanizsa       | 22        | 0.53%   |
| Eger              | 22        | 0.53%   |
| Hodmezovasarhely  | 21        | 0.51%   |
| Salgotarjan       | 20        | 0.48%   |
| Toekoel           | 19        | 0.46%   |
| Sopron            | 19        | 0.46%   |
| Gyomro            | 19        | 0.46%   |
| Ajka              | 19        | 0.46%   |
| Toeroekbalint     | 18        | 0.44%   |
| Hatvan            | 18        | 0.44%   |
| Esztergom         | 18        | 0.44%   |
| Mosonmagyaróvár | 17        | 0.41%   |
| Berettyóújfalu  | 17        | 0.41%   |
| Siófok           | 16        | 0.39%   |
| Pomaz             | 16        | 0.39%   |
| Kazincbarcika     | 16        | 0.39%   |
| Szorgalmatos      | 15        | 0.36%   |
| Kaposvár         | 15        | 0.36%   |
| Cegled            | 15        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 870       | 1514   | 16.87%  |
| Seagate                     | 750       | 1159   | 14.54%  |
| Samsung Electronics         | 713       | 1129   | 13.83%  |
| Kingston                    | 610       | 982    | 11.83%  |
| Toshiba                     | 465       | 730    | 9.02%   |
| Hitachi                     | 250       | 342    | 4.85%   |
| HGST                        | 153       | 236    | 2.97%   |
| SanDisk                     | 135       | 200    | 2.62%   |
| Unknown                     | 126       | 175    | 2.44%   |
| A-DATA Technology           | 112       | 167    | 2.17%   |
| Intel                       | 85        | 128    | 1.65%   |
| SK hynix                    | 79        | 115    | 1.53%   |
| Crucial                     | 70        | 112    | 1.36%   |
| Fujitsu                     | 62        | 74     | 1.2%    |
| SPCC                        | 52        | 69     | 1.01%   |
| Maxtor                      | 50        | 65     | 0.97%   |
| Micron Technology           | 49        | 64     | 0.95%   |
| Apacer                      | 36        | 55     | 0.7%    |
| OCZ                         | 26        | 32     | 0.5%    |
| China                       | 26        | 42     | 0.5%    |
| JMicron Technology          | 25        | 28     | 0.48%   |
| Intenso                     | 23        | 36     | 0.45%   |
| Patriot                     | 21        | 33     | 0.41%   |
| Transcend                   | 20        | 22     | 0.39%   |
| LITEON                      | 20        | 25     | 0.39%   |
| PNY                         | 19        | 31     | 0.37%   |
| Kingmax                     | 19        | 31     | 0.37%   |
| Gigabyte Technology         | 19        | 43     | 0.37%   |
| KIOXIA                      | 15        | 16     | 0.29%   |
| KingSpec                    | 15        | 17     | 0.29%   |
| Hewlett-Packard             | 13        | 17     | 0.25%   |
| Phison                      | 11        | 15     | 0.21%   |
| Apple                       | 11        | 15     | 0.21%   |
| Team                        | 10        | 15     | 0.19%   |
| Kingston Technology Company | 9         | 9      | 0.17%   |
| Corsair                     | 9         | 11     | 0.17%   |
| Zheino                      | 8         | 14     | 0.16%   |
| Verbatim                    | 8         | 17     | 0.16%   |
| Silicon Motion              | 8         | 10     | 0.16%   |
| LITEONIT                    | 8         | 10     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 140       | 2.5%    |
| Kingston SA400S37120G 120GB SSD    | 121       | 2.16%   |
| Kingston SV300S37A120G 120GB SSD   | 89        | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB     | 57        | 1.02%   |
| Kingston SA400S37480G 480GB SSD    | 52        | 0.93%   |
| Toshiba DT01ACA100 1TB             | 51        | 0.91%   |
| Toshiba MQ01ABF050 500GB           | 50        | 0.89%   |
| Seagate ST500DM002-1BD142 500GB    | 46        | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 46        | 0.82%   |
| Toshiba MQ01ABD100 1TB             | 44        | 0.79%   |
| Seagate ST500LT012-1DG142 500GB    | 40        | 0.71%   |
| Samsung SSD 850 EVO 250GB          | 37        | 0.66%   |
| Kingston SUV400S37120G 120GB SSD   | 37        | 0.66%   |
| Toshiba DT01ACA050 500GB           | 33        | 0.59%   |
| HGST HTS545032A7E380 320GB         | 33        | 0.59%   |
| Toshiba MQ04ABF100 1TB             | 30        | 0.54%   |
| A-DATA SU630 240GB SSD             | 30        | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 28        | 0.5%    |
| HGST HTS545050A7E680 500GB         | 28        | 0.5%    |
| Samsung SSD 860 EVO 250GB          | 26        | 0.46%   |
| Seagate ST380815AS 80GB            | 24        | 0.43%   |
| Samsung SSD 860 EVO 500GB          | 24        | 0.43%   |
| HGST HTS721010A9E630 1TB           | 24        | 0.43%   |
| Toshiba HDWD130 3TB                | 23        | 0.41%   |
| Toshiba HDWD110 1TB                | 22        | 0.39%   |
| Seagate ST9320325AS 320GB          | 22        | 0.39%   |
| Samsung HD502HJ 500GB              | 22        | 0.39%   |
| A-DATA SU700 120GB SSD             | 22        | 0.39%   |
| Kingston SHFS37A120G 120GB SSD     | 21        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB           | 20        | 0.36%   |
| Toshiba DT01ACA200 2TB             | 20        | 0.36%   |
| Samsung SSD 850 EVO 500GB          | 19        | 0.34%   |
| SPCC Solid State Disk 256GB        | 18        | 0.32%   |
| Seagate ST9500325AS 500GB          | 18        | 0.32%   |
| Seagate ST9250315AS 250GB          | 17        | 0.3%    |
| Kingston SV300S37A240G 240GB SSD   | 17        | 0.3%    |
| JMicron Generic 500GB              | 17        | 0.3%    |
| Unknown MMC Card  32GB             | 16        | 0.29%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 0.29%   |
| Samsung SSD 840 EVO 120GB          | 16        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 772       | 1326   | 27.98%  |
| Seagate             | 736       | 1134   | 26.68%  |
| Toshiba             | 409       | 640    | 14.82%  |
| Samsung Electronics | 269       | 406    | 9.75%   |
| Hitachi             | 250       | 342    | 9.06%   |
| HGST                | 153       | 236    | 5.55%   |
| Fujitsu             | 62        | 74     | 2.25%   |
| Maxtor              | 50        | 65     | 1.81%   |
| Unknown             | 14        | 18     | 0.51%   |
| Hewlett-Packard     | 7         | 7      | 0.25%   |
| ASMT                | 7         | 9      | 0.25%   |
| HGST HTS            | 6         | 11     | 0.22%   |
| USB3.0              | 4         | 8      | 0.14%   |
| Quantum             | 4         | 4      | 0.14%   |
| IBM/Hitachi         | 4         | 5      | 0.14%   |
| Apple               | 3         | 5      | 0.11%   |
| WD MediaMax         | 2         | 4      | 0.07%   |
| ICY BOX             | 2         | 3      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| CSD                 | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 560       | 892    | 31.18%  |
| Samsung Electronics | 323       | 478    | 17.98%  |
| A-DATA Technology   | 106       | 157    | 5.9%    |
| SanDisk             | 94        | 132    | 5.23%   |
| WDC                 | 88        | 147    | 4.9%    |
| Crucial             | 65        | 105    | 3.62%   |
| Intel               | 56        | 85     | 3.12%   |
| SPCC                | 43        | 59     | 2.39%   |
| SK hynix            | 39        | 62     | 2.17%   |
| Micron Technology   | 36        | 45     | 2%      |
| Apacer              | 34        | 53     | 1.89%   |
| Toshiba             | 26        | 39     | 1.45%   |
| OCZ                 | 26        | 32     | 1.45%   |
| China               | 26        | 42     | 1.45%   |
| LITEON              | 20        | 25     | 1.11%   |
| Intenso             | 20        | 32     | 1.11%   |
| Transcend           | 19        | 21     | 1.06%   |
| PNY                 | 19        | 31     | 1.06%   |
| Kingmax             | 19        | 31     | 1.06%   |
| Patriot             | 18        | 29     | 1%      |
| JMicron Technology  | 17        | 19     | 0.95%   |
| Gigabyte Technology | 16        | 39     | 0.89%   |
| KingSpec            | 14        | 16     | 0.78%   |
| Team                | 9         | 14     | 0.5%    |
| Verbatim            | 8         | 17     | 0.45%   |
| LITEONIT            | 8         | 10     | 0.45%   |
| Corsair             | 8         | 10     | 0.45%   |
| GOODRAM             | 7         | 8      | 0.39%   |
| Apple               | 6         | 6      | 0.33%   |
| Netac               | 5         | 10     | 0.28%   |
| Hewlett-Packard     | 4         | 5      | 0.22%   |
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
| HDD     | 2326      | 4302   | 51.04%  |
| SSD     | 1590      | 2727   | 34.89%  |
| NVMe    | 465       | 727    | 10.2%   |
| MMC     | 122       | 179    | 2.68%   |
| Unknown | 54        | 69     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3187      | 6857   | 81.24%  |
| NVMe | 464       | 726    | 11.83%  |
| SAS  | 150       | 242    | 3.82%   |
| MMC  | 122       | 179    | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2766      | 5092   | 72.16%  |
| 0.51-1.0   | 796       | 1368   | 20.77%  |
| 1.01-2.0   | 159       | 256    | 4.15%   |
| 2.01-3.0   | 52        | 152    | 1.36%   |
| 3.01-4.0   | 38        | 94     | 0.99%   |
| 4.01-10.0  | 16        | 38     | 0.42%   |
| 10.01-20.0 | 6         | 29     | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1453      | 35.44%  |
| 101-250        | 886       | 21.61%  |
| 251-500        | 562       | 13.71%  |
| 51-100         | 302       | 7.37%   |
| 501-1000       | 267       | 6.51%   |
| 1-20           | 191       | 4.66%   |
| 21-50          | 169       | 4.12%   |
| 1001-2000      | 146       | 3.56%   |
| More than 3000 | 67        | 1.63%   |
| 2001-3000      | 57        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 1453      | 35.13%  |
| 1-20           | 1452      | 35.11%  |
| 21-50          | 370       | 8.95%   |
| 51-100         | 269       | 6.5%    |
| 101-250        | 246       | 5.95%   |
| 251-500        | 135       | 3.26%   |
| 501-1000       | 112       | 2.71%   |
| 1001-2000      | 64        | 1.55%   |
| More than 3000 | 22        | 0.53%   |
| 2001-3000      | 13        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB              | 30        | 42     | 2.93%   |
| Kingston SV300S37A120G 120GB SSD        | 19        | 22     | 1.85%   |
| HGST HTS545050A7E680 500GB              | 19        | 29     | 1.85%   |
| A-DATA Technology SU630 240GB SSD       | 18        | 21     | 1.76%   |
| Seagate ST500DM002-1BD142 500GB         | 16        | 31     | 1.56%   |
| Seagate ST9320325AS 320GB               | 11        | 23     | 1.07%   |
| Seagate ST500LT012-9WS142 500GB         | 11        | 13     | 1.07%   |
| Seagate ST500LT012-1DG142 500GB         | 11        | 14     | 1.07%   |
| Toshiba MQ01ABF050 500GB                | 10        | 25     | 0.98%   |
| Samsung Electronics HD103UJ 1TB         | 10        | 17     | 0.98%   |
| Seagate ST9250315AS 250GB               | 9         | 14     | 0.88%   |
| Toshiba DT01ACA050 500GB                | 8         | 9      | 0.78%   |
| Seagate ST9500325AS 500GB               | 8         | 13     | 0.78%   |
| Seagate ST9320423AS 320GB               | 8         | 9      | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 8         | 12     | 0.78%   |
| HGST HTS541010A9E680 1TB                | 8         | 16     | 0.78%   |
| WDC WD5000AADS-00S9B0 500GB             | 7         | 8      | 0.68%   |
| Toshiba MQ01ABD100 1TB                  | 7         | 8      | 0.68%   |
| Samsung Electronics HM160HI 160GB       | 7         | 8      | 0.68%   |
| Hitachi HTS545050B9A300 500GB           | 7         | 8      | 0.68%   |
| WDC WD5000AAKX-001CA0 500GB             | 6         | 6      | 0.59%   |
| Toshiba DT01ACA100 1TB                  | 6         | 12     | 0.59%   |
| Hitachi HTS545016B9A300 160GB           | 6         | 6      | 0.59%   |
| Toshiba MQ01ABD050 500GB                | 5         | 5      | 0.49%   |
| Seagate ST980811AS 80GB                 | 5         | 5      | 0.49%   |
| Seagate ST3250318AS 250GB               | 5         | 8      | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 6      | 0.49%   |
| Samsung Electronics HD502HJ 500GB       | 5         | 8      | 0.49%   |
| Samsung Electronics HD321KJ 320GB       | 5         | 5      | 0.49%   |
| Samsung Electronics HD161HJ 160GB       | 5         | 5      | 0.49%   |
| Samsung Electronics HD103SI 1TB         | 5         | 5      | 0.49%   |
| Maxtor 6Y080M0 82GB                     | 5         | 6      | 0.49%   |
| Hitachi HTS547550A9E384 500GB           | 5         | 15     | 0.49%   |
| Hitachi HTS545050A7E380 500GB           | 5         | 7      | 0.49%   |
| Hitachi HTS545032B9A300 320GB           | 5         | 6      | 0.49%   |
| Hitachi HTS541680J9SA00 80GB            | 5         | 5      | 0.49%   |
| HGST HTS545050A7E380 500GB              | 5         | 9      | 0.49%   |
| WDC WD5000AAKS-00UU3A0 500GB            | 4         | 7      | 0.39%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 7      | 0.39%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 4         | 6      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 218       | 309    | 21.84%  |
| WDC                 | 200       | 301    | 20.04%  |
| Samsung Electronics | 114       | 164    | 11.42%  |
| Hitachi             | 110       | 158    | 11.02%  |
| Toshiba             | 104       | 151    | 10.42%  |
| HGST                | 73        | 109    | 7.31%   |
| Kingston            | 46        | 58     | 4.61%   |
| Maxtor              | 27        | 41     | 2.71%   |
| A-DATA Technology   | 25        | 33     | 2.51%   |
| Fujitsu             | 20        | 27     | 2%      |
| Intel               | 14        | 21     | 1.4%    |
| SK hynix            | 9         | 13     | 0.9%    |
| SanDisk             | 4         | 5      | 0.4%    |
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
| QUANTUM             | 1         | 1      | 0.1%    |
| OCZ                 | 1         | 3      | 0.1%    |
| Micron Technology   | 1         | 1      | 0.1%    |
| Leven               | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| Initio              | 1         | 1      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| CSD                 | 1         | 1      | 0.1%    |
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
| Seagate             | 218       | 309    | 25.41%  |
| WDC                 | 195       | 296    | 22.73%  |
| Hitachi             | 110       | 158    | 12.82%  |
| Samsung Electronics | 106       | 153    | 12.35%  |
| Toshiba             | 97        | 137    | 11.31%  |
| HGST                | 73        | 109    | 8.51%   |
| Maxtor              | 27        | 41     | 3.15%   |
| Fujitsu             | 20        | 27     | 2.33%   |
| IBM/Hitachi         | 3         | 3      | 0.35%   |
| WD MediaMax         | 2         | 4      | 0.23%   |
| Hewlett-Packard     | 2         | 2      | 0.23%   |
| QUANTUM             | 1         | 1      | 0.12%   |
| ICY BOX             | 1         | 1      | 0.12%   |
| ExcelStor           | 1         | 1      | 0.12%   |
| CSD                 | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 785       | 1244   | 85.05%  |
| SSD     | 132       | 178    | 14.3%   |
| NVMe    | 5         | 6      | 0.54%   |
| Unknown | 1         | 1      | 0.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Samsung Electronics HD502HJ 500GB  | 2         | 2      | 8.7%    |
| Zheino CHN-NGFFNV2280-256 256GB    | 1         | 1      | 4.35%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.35%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.35%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.35%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.35%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.35%   |
| Toshiba MK6475GSX 640GB            | 1         | 1      | 4.35%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.35%   |
| Seagate ST9160821AS 160GB          | 1         | 1      | 4.35%   |
| Seagate ST380815AS 80GB            | 1         | 3      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 4.35%   |
| Samsung Electronics SP0802N 80GB   | 1         | 1      | 4.35%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.35%   |
| Samsung Electronics HD204UI 2TB    | 1         | 1      | 4.35%   |
| Samsung Electronics HD103SJ 1TB    | 1         | 2      | 4.35%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB      | 1         | 1      | 4.35%   |
| Hitachi HDS721075CLA332 752GB      | 1         | 1      | 4.35%   |
| Hewlett-Packard SSD EX900 250GB    | 1         | 1      | 4.35%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 12     | 26.09%  |
| Samsung Electronics | 6         | 7      | 26.09%  |
| Toshiba             | 3         | 3      | 13.04%  |
| Seagate             | 3         | 5      | 13.04%  |
| Hitachi             | 2         | 2      | 8.7%    |
| Zheino              | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| Hewlett-Packard     | 1         | 1      | 4.35%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2103      | 4400   | 51.33%  |
| Detected | 1073      | 2143   | 26.19%  |
| Malfunc  | 898       | 1429   | 21.92%  |
| Failed   | 23        | 32     | 0.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2672      | 64.93%  |
| AMD                              | 637       | 15.48%  |
| Samsung Electronics              | 167       | 4.06%   |
| JMicron Technology               | 79        | 1.92%   |
| Nvidia                           | 71        | 1.73%   |
| Kingston Technology Company      | 67        | 1.63%   |
| SanDisk                          | 65        | 1.58%   |
| ASMedia Technology               | 61        | 1.48%   |
| SK hynix                         | 37        | 0.9%    |
| Marvell Technology Group         | 37        | 0.9%    |
| Phison Electronics               | 30        | 0.73%   |
| Toshiba America Info Systems     | 29        | 0.7%    |
| VIA Technologies                 | 21        | 0.51%   |
| KIOXIA                           | 20        | 0.49%   |
| Silicon Motion                   | 18        | 0.44%   |
| Silicon Integrated Systems [SiS] | 14        | 0.34%   |
| Micron Technology                | 14        | 0.34%   |
| Silicon Image                    | 12        | 0.29%   |
| LSI Logic / Symbios Logic        | 11        | 0.27%   |
| ADATA Technology                 | 10        | 0.24%   |
| Micron/Crucial Technology        | 7         | 0.17%   |
| Solid State Storage Technology   | 5         | 0.12%   |
| Integrated Technology Express    | 5         | 0.12%   |
| Broadcom / LSI                   | 4         | 0.1%    |
| Seagate Technology               | 3         | 0.07%   |
| Union Memory (Shenzhen)          | 2         | 0.05%   |
| Realtek Semiconductor            | 2         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.05%   |
| HighPoint Technologies           | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Lite-On Technology               | 1         | 0.02%   |
| Initio                           | 1         | 0.02%   |
| Apple                            | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 386       | 7.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 199       | 3.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 174       | 3.37%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 174       | 3.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 174       | 3.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 168       | 3.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 140       | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 125       | 2.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 119       | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 105       | 2.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 96        | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 90        | 1.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 89        | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 86        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 85        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 79        | 1.53%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 74        | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 73        | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 72        | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 71        | 1.37%   |
| AMD FCH IDE Controller                                                                  | 71        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 68        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 63        | 1.22%   |
| AMD 400 Series Chipset SATA Controller                                                  | 63        | 1.22%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 54        | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 51        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 50        | 0.97%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 50        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 47        | 0.91%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 47        | 0.91%   |
| Intel SATA Controller [RAID mode]                                                       | 46        | 0.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 46        | 0.89%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 46        | 0.89%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 45        | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 44        | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 39        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 39        | 0.75%   |
| Samsung NVMe SSD Controller 980                                                         | 36        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 36        | 0.7%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 36        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2657      | 60.62%  |
| IDE  | 1001      | 22.84%  |
| NVMe | 471       | 10.75%  |
| RAID | 236       | 5.38%   |
| SAS  | 10        | 0.23%   |
| SCSI | 8         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2806      | 78.91%  |
| AMD          | 737       | 20.73%  |
| ARM          | 9         | 0.25%   |
| CentaurHauls | 4         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 46        | 1.29%   |
| Intel Celeron CPU 1000M @ 1.80GHz           | 42        | 1.18%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 39        | 1.09%   |
| AMD A8-6600K APU with Radeon HD Graphics    | 36        | 1.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 33        | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 32        | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 27        | 0.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 27        | 0.76%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 25        | 0.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz           | 25        | 0.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz           | 24        | 0.67%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 21        | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 20        | 0.56%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 20        | 0.56%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 20        | 0.56%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 20        | 0.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 19        | 0.53%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 19        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 19        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 18        | 0.5%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 18        | 0.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 17        | 0.48%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 17        | 0.48%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 17        | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 17        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 16        | 0.45%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 16        | 0.45%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 16        | 0.45%   |
| AMD FX-8350 Eight-Core Processor            | 16        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 15        | 0.42%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 15        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 15        | 0.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 15        | 0.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 15        | 0.42%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 15        | 0.42%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 15        | 0.42%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 14        | 0.39%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 14        | 0.39%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 14        | 0.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 14        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 749       | 21%     |
| Intel Core i3           | 410       | 11.5%   |
| Intel Core i7           | 331       | 9.28%   |
| Intel Core 2 Duo        | 318       | 8.92%   |
| Intel Celeron           | 264       | 7.4%    |
| Intel Pentium           | 155       | 4.35%   |
| Intel Pentium Dual-Core | 96        | 2.69%   |
| AMD Ryzen 5             | 94        | 2.64%   |
| Intel Atom              | 92        | 2.58%   |
| AMD A8                  | 80        | 2.24%   |
| Other                   | 69        | 1.93%   |
| Intel Xeon              | 65        | 1.82%   |
| AMD Ryzen 7             | 55        | 1.54%   |
| Intel Core 2 Quad       | 53        | 1.49%   |
| AMD FX                  | 53        | 1.49%   |
| AMD A4                  | 49        | 1.37%   |
| Intel Core 2            | 46        | 1.29%   |
| Intel Pentium Dual      | 45        | 1.26%   |
| AMD Athlon II X2        | 37        | 1.04%   |
| AMD Ryzen 3             | 36        | 1.01%   |
| AMD Athlon 64 X2        | 32        | 0.9%    |
| AMD A6                  | 31        | 0.87%   |
| AMD A10                 | 25        | 0.7%    |
| Intel Genuine           | 22        | 0.62%   |
| Intel Pentium 4         | 20        | 0.56%   |
| AMD Phenom II X4        | 19        | 0.53%   |
| AMD E1                  | 17        | 0.48%   |
| AMD E                   | 17        | 0.48%   |
| AMD E2                  | 15        | 0.42%   |
| Intel Pentium Silver    | 14        | 0.39%   |
| Intel Celeron M         | 13        | 0.36%   |
| Intel Celeron Dual-Core | 13        | 0.36%   |
| AMD Ryzen 9             | 13        | 0.36%   |
| Intel Pentium D         | 12        | 0.34%   |
| AMD Sempron             | 11        | 0.31%   |
| AMD Athlon II X4        | 10        | 0.28%   |
| AMD Athlon Dual Core    | 10        | 0.28%   |
| AMD Athlon              | 10        | 0.28%   |
| Intel Pentium M         | 9         | 0.25%   |
| AMD Athlon X4           | 9         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2102      | 58.85%  |
| 4       | 926       | 25.92%  |
| 1       | 225       | 6.3%    |
| 6       | 181       | 5.07%   |
| 8       | 82        | 2.3%    |
| 3       | 26        | 0.73%   |
| 12      | 10        | 0.28%   |
| 16      | 7         | 0.2%    |
| 10      | 6         | 0.17%   |
| 14      | 3         | 0.08%   |
| 36      | 1         | 0.03%   |
| 28      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3543      | 99.61%  |
| 2      | 14        | 0.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1806      | 50.52%  |
| 2       | 1768      | 49.45%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3458      | 96.94%  |
| 32-bit         | 62        | 1.74%   |
| Unknown        | 47        | 1.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 423       | 11.52%  |
| 0x1067a    | 309       | 8.42%   |
| 0x206a7    | 285       | 7.76%   |
| 0x306a9    | 265       | 7.22%   |
| 0x306c3    | 177       | 4.82%   |
| 0x20655    | 118       | 3.21%   |
| 0x6fd      | 102       | 2.78%   |
| 0x06001119 | 90        | 2.45%   |
| 0x40651    | 86        | 2.34%   |
| 0x10676    | 77        | 2.1%    |
| 0x406e3    | 76        | 2.07%   |
| 0x306d4    | 74        | 2.02%   |
| 0x906ea    | 67        | 1.82%   |
| 0x506e3    | 67        | 1.82%   |
| 0x806e9    | 61        | 1.66%   |
| 0x010000c8 | 56        | 1.53%   |
| 0x906e9    | 55        | 1.5%    |
| 0x806ea    | 52        | 1.42%   |
| 0x406c4    | 51        | 1.39%   |
| 0x6fb      | 49        | 1.33%   |
| 0x20652    | 43        | 1.17%   |
| 0x806ec    | 42        | 1.14%   |
| 0x106ca    | 37        | 1.01%   |
| 0x706a1    | 34        | 0.93%   |
| 0x30678    | 34        | 0.93%   |
| 0x806c1    | 30        | 0.82%   |
| 0x05000119 | 30        | 0.82%   |
| 0x506c9    | 29        | 0.79%   |
| 0x0800820d | 29        | 0.79%   |
| 0x6f2      | 27        | 0.74%   |
| 0x07030105 | 25        | 0.68%   |
| 0x6f6      | 24        | 0.65%   |
| 0x06000852 | 24        | 0.65%   |
| 0x406c3    | 23        | 0.63%   |
| 0x106c2    | 23        | 0.63%   |
| 0x806eb    | 22        | 0.6%    |
| 0x0700010f | 22        | 0.6%    |
| 0x06003106 | 22        | 0.6%    |
| 0x106e5    | 20        | 0.54%   |
| 0x706e5    | 19        | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Penryn           | 408       | 11.47%  |
| KabyLake         | 371       | 10.43%  |
| SandyBridge      | 310       | 8.71%   |
| Haswell          | 296       | 8.32%   |
| IvyBridge        | 281       | 7.9%    |
| Core             | 229       | 6.44%   |
| Westmere         | 180       | 5.06%   |
| Skylake          | 170       | 4.78%   |
| Piledriver       | 136       | 3.82%   |
| Silvermont       | 118       | 3.32%   |
| K10              | 111       | 3.12%   |
| Broadwell        | 85        | 2.39%   |
| K8 Hammer        | 67        | 1.88%   |
| Bonnell          | 66        | 1.85%   |
| Zen 2            | 61        | 1.71%   |
| Zen+             | 58        | 1.63%   |
| Zen              | 47        | 1.32%   |
| Goldmont plus    | 46        | 1.29%   |
| NetBurst         | 45        | 1.26%   |
| Bobcat           | 44        | 1.24%   |
| Puma             | 41        | 1.15%   |
| Goldmont         | 35        | 0.98%   |
| Unknown          | 35        | 0.98%   |
| Steamroller      | 34        | 0.96%   |
| P6               | 33        | 0.93%   |
| Excavator        | 33        | 0.93%   |
| TigerLake        | 32        | 0.9%    |
| Nehalem          | 31        | 0.87%   |
| Zen 3            | 30        | 0.84%   |
| IceLake          | 28        | 0.79%   |
| Jaguar           | 27        | 0.76%   |
| CometLake        | 23        | 0.65%   |
| K10 Llano        | 17        | 0.48%   |
| Alderlake Hybrid | 13        | 0.37%   |
| Bulldozer        | 9         | 0.25%   |
| K8 & K10 hybrid  | 6         | 0.17%   |
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
| Intel                                        | 2121      | 51.66%  |
| Nvidia                                       | 1004      | 24.45%  |
| AMD                                          | 948       | 23.09%  |
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
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 228       | 5.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 174       | 4.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 142       | 3.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 111       | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 91        | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 80        | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 79        | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 76        | 1.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 75        | 1.73%   |
| Intel HD Graphics 5500                                                                   | 74        | 1.71%   |
| Intel HD Graphics 620                                                                    | 73        | 1.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 58        | 1.34%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 56        | 1.29%   |
| Intel UHD Graphics 620                                                                   | 55        | 1.27%   |
| Intel HD Graphics 530                                                                    | 55        | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 52        | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 52        | 1.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 50        | 1.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 48        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 47        | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 42        | 0.97%   |
| Nvidia GT218 [GeForce 210]                                                               | 41        | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 0.95%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 39        | 0.9%    |
| AMD Richland [Radeon HD 8570D]                                                           | 37        | 0.85%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 37        | 0.85%   |
| Intel HD Graphics 630                                                                    | 36        | 0.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 36        | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 33        | 0.76%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 33        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 32        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 30        | 0.69%   |
| AMD Renoir                                                                               | 30        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 29        | 0.67%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 28        | 0.65%   |
| Intel HD Graphics 500                                                                    | 28        | 0.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 28        | 0.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1625      | 45.18%  |
| 1 x AMD                  | 718       | 19.96%  |
| 1 x Nvidia               | 610       | 16.96%  |
| Intel + Nvidia           | 363       | 10.09%  |
| Intel + AMD              | 104       | 2.89%   |
| 2 x AMD                  | 102       | 2.84%   |
| AMD + Nvidia             | 26        | 0.72%   |
| 1 x VIA                  | 13        | 0.36%   |
| Other                    | 10        | 0.28%   |
| 1 x SiS                  | 7         | 0.19%   |
| 2 x Nvidia               | 4         | 0.11%   |
| 1 x Matrox               | 4         | 0.11%   |
| 1 x ASPEED               | 4         | 0.11%   |
| AMD + XGI                | 2         | 0.06%   |
| 2 x Intel                | 1         | 0.03%   |
| 1 x Intel + 3 x AMD      | 1         | 0.03%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + ASPEED             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3229      | 89.89%  |
| Proprietary | 260       | 7.24%   |
| Unknown     | 103       | 2.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1811      | 49.04%  |
| 0.01-0.5   | 637       | 17.25%  |
| 1.01-2.0   | 503       | 13.62%  |
| 0.51-1.0   | 424       | 11.48%  |
| 3.01-4.0   | 185       | 5.01%   |
| 7.01-8.0   | 59        | 1.6%    |
| 5.01-6.0   | 47        | 1.27%   |
| 2.01-3.0   | 21        | 0.57%   |
| 16.01-24.0 | 3         | 0.08%   |
| 8.01-16.0  | 3         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 655       | 17.78%  |
| LG Display              | 430       | 11.68%  |
| AU Optronics            | 407       | 11.05%  |
| Goldstar                | 304       | 8.25%   |
| Chimei Innolux          | 264       | 7.17%   |
| BOE                     | 226       | 6.14%   |
| Dell                    | 139       | 3.77%   |
| Chi Mei Optoelectronics | 102       | 2.77%   |
| Lenovo                  | 98        | 2.66%   |
| Philips                 | 97        | 2.63%   |
| Ancor Communications    | 92        | 2.5%    |
| BenQ                    | 89        | 2.42%   |
| Acer                    | 85        | 2.31%   |
| Hewlett-Packard         | 80        | 2.17%   |
| Fujitsu Siemens         | 46        | 1.25%   |
| LG Philips              | 38        | 1.03%   |
| AOC                     | 37        | 1%      |
| HannStar                | 29        | 0.79%   |
| InfoVision              | 28        | 0.76%   |
| Eizo                    | 25        | 0.68%   |
| Sony                    | 24        | 0.65%   |
| ASUSTek Computer        | 23        | 0.62%   |
| LG Electronics          | 21        | 0.57%   |
| Vestel Elektronik       | 17        | 0.46%   |
| HKC                     | 17        | 0.46%   |
| PANDA                   | 16        | 0.43%   |
| NEC Computers           | 16        | 0.43%   |
| Apple                   | 16        | 0.43%   |
| IBM                     | 14        | 0.38%   |
| CPT                     | 14        | 0.38%   |
| ViewSonic               | 13        | 0.35%   |
| Toshiba                 | 13        | 0.35%   |
| Medion                  | 13        | 0.35%   |
| Sharp                   | 11        | 0.3%    |
| Belinea                 | 11        | 0.3%    |
| Unknown                 | 10        | 0.27%   |
| Panasonic               | 10        | 0.27%   |
| Quanta Display          | 8         | 0.22%   |
| OEM                     | 8         | 0.22%   |
| InnoLux Display         | 8         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 49        | 1.31%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 37        | 0.99%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 34        | 0.91%   |
| BenQ EW277HDR BNQ7948 1920x1080 598x336mm 27.0-inch                      | 31        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 25        | 0.67%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.56%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 19        | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.48%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 17        | 0.45%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 14        | 0.37%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 14        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.35%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 12        | 0.32%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.32%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 12        | 0.32%   |
| HKC Monitor HKC1850 1360x768 409x230mm 18.5-inch                         | 12        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 12        | 0.32%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 12        | 0.32%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.32%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 11        | 0.29%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch         | 11        | 0.29%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 11        | 0.29%   |
| HannStar HannsG HS191D HSD0013 1280x1024 376x301mm 19.0-inch             | 11        | 0.29%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                      | 11        | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.29%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 11        | 0.29%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 11        | 0.29%   |
| Ancor Communications VW195 ACI19AB 1440x900 408x255mm 18.9-inch          | 11        | 0.29%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                   | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.27%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 10        | 0.27%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch              | 9         | 0.24%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 9         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1247      | 34.99%  |
| 1366x768 (WXGA)    | 912       | 25.59%  |
| 1280x1024 (SXGA)   | 274       | 7.69%   |
| 1280x800 (WXGA)    | 171       | 4.8%    |
| 1440x900 (WXGA+)   | 162       | 4.55%   |
| 1600x900 (HD+)     | 155       | 4.35%   |
| 1680x1050 (WSXGA+) | 147       | 4.12%   |
| 3840x2160 (4K)     | 109       | 3.06%   |
| 2560x1440 (QHD)    | 54        | 1.52%   |
| 1920x1200 (WUXGA)  | 54        | 1.52%   |
| 1024x600           | 39        | 1.09%   |
| 1360x768           | 38        | 1.07%   |
| 1024x768 (XGA)     | 37        | 1.04%   |
| 2560x1080          | 33        | 0.93%   |
| Unknown            | 20        | 0.56%   |
| 1920x540           | 18        | 0.51%   |
| 2880x1800          | 11        | 0.31%   |
| 1600x1200          | 10        | 0.28%   |
| 3840x1080          | 8         | 0.22%   |
| 3440x1440          | 7         | 0.2%    |
| 1280x720 (HD)      | 7         | 0.2%    |
| 2560x1600          | 6         | 0.17%   |
| 2288x1287          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 2160x1440          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 3840x2400          | 2         | 0.06%   |
| 3840x1200          | 2         | 0.06%   |
| 3280x1080          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2048x1152          | 2         | 0.06%   |
| 1680x945           | 2         | 0.06%   |
| 1280x960           | 2         | 0.06%   |
| 1280x768           | 2         | 0.06%   |
| 800x1280           | 1         | 0.03%   |
| 7680x2160          | 1         | 0.03%   |
| 4093x4093          | 1         | 0.03%   |
| 3840x1920          | 1         | 0.03%   |
| 3600x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1196      | 32.52%  |
| 14      | 262       | 7.12%   |
| 17      | 258       | 7.01%   |
| 21      | 248       | 6.74%   |
| 19      | 233       | 6.33%   |
| 23      | 198       | 5.38%   |
| 13      | 182       | 4.95%   |
| 24      | 176       | 4.79%   |
| 27      | 154       | 4.19%   |
| 22      | 105       | 2.85%   |
| Unknown | 105       | 2.85%   |
| 18      | 101       | 2.75%   |
| 12      | 86        | 2.34%   |
| 20      | 51        | 1.39%   |
| 10      | 49        | 1.33%   |
| 34      | 39        | 1.06%   |
| 11      | 38        | 1.03%   |
| 84      | 31        | 0.84%   |
| 31      | 29        | 0.79%   |
| 72      | 20        | 0.54%   |
| 40      | 20        | 0.54%   |
| 32      | 13        | 0.35%   |
| 65      | 10        | 0.27%   |
| 54      | 10        | 0.27%   |
| 52      | 7         | 0.19%   |
| 42      | 6         | 0.16%   |
| 60      | 5         | 0.14%   |
| 16      | 5         | 0.14%   |
| 58      | 4         | 0.11%   |
| 46      | 4         | 0.11%   |
| 64      | 3         | 0.08%   |
| 48      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |
| 25      | 3         | 0.08%   |
| 8       | 3         | 0.08%   |
| 55      | 2         | 0.05%   |
| 49      | 2         | 0.05%   |
| 47      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 142     | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1646      | 45.17%  |
| 401-500        | 583       | 16%     |
| 501-600        | 510       | 14%     |
| 351-400        | 314       | 8.62%   |
| 201-300        | 251       | 6.89%   |
| Unknown        | 105       | 2.88%   |
| 1001-1500      | 54        | 1.48%   |
| 701-800        | 53        | 1.45%   |
| 1501-2000      | 52        | 1.43%   |
| 601-700        | 38        | 1.04%   |
| 801-900        | 24        | 0.66%   |
| 901-1000       | 8         | 0.22%   |
| 101-200        | 5         | 0.14%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2425      | 70.78%  |
| 16/10   | 523       | 15.27%  |
| 5/4     | 264       | 7.71%   |
| Unknown | 79        | 2.31%   |
| 4/3     | 69        | 2.01%   |
| 21/9    | 39        | 1.14%   |
| 3/2     | 20        | 0.58%   |
| 6/5     | 4         | 0.12%   |
| 32/9    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1180      | 32.26%  |
| 201-250        | 603       | 16.48%  |
| 81-90          | 374       | 10.22%  |
| 151-200        | 355       | 9.7%    |
| 141-150        | 214       | 5.85%   |
| 301-350        | 154       | 4.21%   |
| Unknown        | 105       | 2.87%   |
| More than 1000 | 100       | 2.73%   |
| 121-130        | 95        | 2.6%    |
| 351-500        | 82        | 2.24%   |
| 61-70          | 79        | 2.16%   |
| 71-80          | 69        | 1.89%   |
| 251-300        | 61        | 1.67%   |
| 41-50          | 47        | 1.28%   |
| 51-60          | 40        | 1.09%   |
| 501-1000       | 38        | 1.04%   |
| 131-140        | 29        | 0.79%   |
| 111-120        | 16        | 0.44%   |
| 91-100         | 12        | 0.33%   |
| 1-40           | 5         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1417      | 39.74%  |
| 101-120       | 1123      | 31.49%  |
| 121-160       | 737       | 20.67%  |
| Unknown       | 105       | 2.94%   |
| 161-240       | 86        | 2.41%   |
| 1-50          | 75        | 2.1%    |
| More than 240 | 23        | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3163      | 86.78%  |
| 2     | 363       | 9.96%   |
| 0     | 90        | 2.47%   |
| 3     | 29        | 0.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1873      | 35.61%  |
| Intel                             | 1380      | 26.24%  |
| Qualcomm Atheros                  | 782       | 14.87%  |
| Broadcom                          | 336       | 6.39%   |
| Broadcom Limited                  | 136       | 2.59%   |
| Ralink                            | 117       | 2.22%   |
| Marvell Technology Group          | 74        | 1.41%   |
| Qualcomm Atheros Communications   | 68        | 1.29%   |
| Ralink Technology                 | 59        | 1.12%   |
| TP-Link                           | 51        | 0.97%   |
| Nvidia                            | 46        | 0.87%   |
| MediaTek                          | 37        | 0.7%    |
| Dell                              | 26        | 0.49%   |
| Samsung Electronics               | 22        | 0.42%   |
| Hewlett-Packard                   | 21        | 0.4%    |
| Huawei Technologies               | 18        | 0.34%   |
| VIA Technologies                  | 17        | 0.32%   |
| Xiaomi                            | 16        | 0.3%    |
| Sierra Wireless                   | 16        | 0.3%    |
| Ericsson Business Mobile Networks | 16        | 0.3%    |
| JMicron Technology                | 13        | 0.25%   |
| ASUSTek Computer                  | 13        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.23%   |
| Attansic Technology               | 11        | 0.21%   |
| ASIX Electronics                  | 8         | 0.15%   |
| Aquantia                          | 8         | 0.15%   |
| Belkin Components                 | 7         | 0.13%   |
| D-Link System                     | 6         | 0.11%   |
| IMC Networks                      | 5         | 0.1%    |
| DisplayLink                       | 5         | 0.1%    |
| D-Link                            | 5         | 0.1%    |
| Qualcomm                          | 4         | 0.08%   |
| Lenovo                            | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| Accton Technology                 | 4         | 0.08%   |
| Microsoft                         | 3         | 0.06%   |
| Microchip Technology              | 3         | 0.06%   |
| ZyDAS                             | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |
| Sundance Technology Inc / IC Plus | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1317      | 21.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 330       | 5.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 185       | 3.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 117       | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 1.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 109       | 1.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 1.41%   |
| Intel Wireless 8265 / 8275                                              | 78        | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 1.23%   |
| Intel Wireless 7260                                                     | 71        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 1.11%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 68        | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 62        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                | 62        | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                         | 59        | 0.97%   |
| Intel Wireless 7265                                                     | 59        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                | 53        | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 51        | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 50        | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 49        | 0.8%    |
| Intel Wireless 3165                                                     | 48        | 0.79%   |
| Intel Ethernet Connection I217-LM                                       | 48        | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 46        | 0.75%   |
| Intel Ethernet Connection (2) I219-V                                    | 44        | 0.72%   |
| Intel Wireless 3160                                                     | 38        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 36        | 0.59%   |
| Intel Wi-Fi 6 AX200                                                     | 36        | 0.59%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 0.59%   |
| Intel Wireless 8260                                                     | 35        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 0.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 32        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 30        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 30        | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                              | 30        | 0.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 973       | 38.29%  |
| Qualcomm Atheros                | 597       | 23.49%  |
| Realtek Semiconductor           | 338       | 13.3%   |
| Broadcom                        | 181       | 7.12%   |
| Ralink                          | 117       | 4.6%    |
| Qualcomm Atheros Communications | 68        | 2.68%   |
| Ralink Technology               | 59        | 2.32%   |
| TP-Link                         | 46        | 1.81%   |
| Broadcom Limited                | 43        | 1.69%   |
| MediaTek                        | 34        | 1.34%   |
| Sierra Wireless                 | 16        | 0.63%   |
| Dell                            | 15        | 0.59%   |
| ASUSTek Computer                | 13        | 0.51%   |
| Belkin Components               | 7         | 0.28%   |
| IMC Networks                    | 5         | 0.2%    |
| Edimax Technology               | 4         | 0.16%   |
| D-Link                          | 4         | 0.16%   |
| Microsoft                       | 3         | 0.12%   |
| Hewlett-Packard                 | 3         | 0.12%   |
| ZyDAS                           | 2         | 0.08%   |
| NetGear                         | 2         | 0.08%   |
| D-Link System                   | 2         | 0.08%   |
| VIA Technologies                | 1         | 0.04%   |
| TRENDnet                        | 1         | 0.04%   |
| Texas Instruments               | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Marvell Technology Group        | 1         | 0.04%   |
| Fujitsu Siemens Computers       | 1         | 0.04%   |
| Accton Technology               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 117       | 4.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 110       | 4.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 109       | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 3.37%   |
| Intel Wireless 8265 / 8275                                              | 78        | 3.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 2.94%   |
| Intel Wireless 7260                                                     | 71        | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 68        | 2.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 68        | 2.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 62        | 2.43%   |
| Qualcomm Atheros AR9271 802.11n                                         | 59        | 2.31%   |
| Intel Wireless 7265                                                     | 59        | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 2.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 52        | 2.04%   |
| Intel Centrino Advanced-N 6200                                          | 50        | 1.96%   |
| Intel Wireless 3165                                                     | 48        | 1.88%   |
| Intel Wireless 3160                                                     | 38        | 1.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 36        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                     | 36        | 1.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 36        | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 36        | 1.41%   |
| Intel Wireless 8260                                                     | 35        | 1.37%   |
| Intel Centrino Ultimate-N 6300                                          | 35        | 1.37%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.14%   |
| Intel WiFi Link 5100                                                    | 29        | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.06%   |
| Intel Wi-Fi 6 AX201                                                     | 27        | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                           | 27        | 1.06%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 24        | 0.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 24        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 21        | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 21        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 0.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 20        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 19        | 0.74%   |
| Intel Ultimate N WiFi Link 5300                                         | 19        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1765      | 51.2%   |
| Intel                             | 849       | 24.63%  |
| Qualcomm Atheros                  | 268       | 7.77%   |
| Broadcom                          | 180       | 5.22%   |
| Broadcom Limited                  | 94        | 2.73%   |
| Marvell Technology Group          | 73        | 2.12%   |
| Nvidia                            | 46        | 1.33%   |
| Samsung Electronics               | 22        | 0.64%   |
| Xiaomi                            | 16        | 0.46%   |
| Huawei Technologies               | 16        | 0.46%   |
| VIA Technologies                  | 15        | 0.44%   |
| JMicron Technology                | 13        | 0.38%   |
| Silicon Integrated Systems [SiS]  | 12        | 0.35%   |
| Attansic Technology               | 11        | 0.32%   |
| ASIX Electronics                  | 8         | 0.23%   |
| Aquantia                          | 8         | 0.23%   |
| TP-Link                           | 5         | 0.15%   |
| DisplayLink                       | 5         | 0.15%   |
| Lenovo                            | 4         | 0.12%   |
| D-Link System                     | 4         | 0.12%   |
| Qualcomm                          | 3         | 0.09%   |
| Microchip Technology              | 3         | 0.09%   |
| MediaTek                          | 3         | 0.09%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1317      | 37.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 330       | 9.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 185       | 5.3%    |
| Intel 82577LM Gigabit Network Connection                          | 62        | 1.78%   |
| Intel 82567LM Gigabit Network Connection                          | 53        | 1.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 51        | 1.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 49        | 1.4%    |
| Intel Ethernet Connection I217-LM                                 | 48        | 1.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 46        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                              | 44        | 1.26%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 32        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.86%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 30        | 0.86%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 30        | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 28        | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 28        | 0.8%    |
| Intel I211 Gigabit Network Connection                             | 27        | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.75%   |
| Nvidia MCP61 Ethernet                                             | 26        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 25        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 25        | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.6%    |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 20        | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 19        | 0.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.52%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 16        | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 15        | 0.43%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 15        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.43%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 15        | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14        | 0.4%    |
| Huawei ANA-NX9                                                    | 14        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3309      | 57.02%  |
| WiFi     | 2434      | 41.94%  |
| Modem    | 58        | 1%      |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1928      | 51.29%  |
| Ethernet | 1831      | 48.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2004      | 56.17%  |
| 1     | 1459      | 40.89%  |
| 0     | 64        | 1.79%   |
| 3     | 34        | 0.95%   |
| 4     | 6         | 0.17%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3125      | 84.76%  |
| Yes  | 562       | 15.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 595       | 33.63%  |
| Qualcomm Atheros Communications | 176       | 9.95%   |
| Broadcom                        | 150       | 8.48%   |
| Realtek Semiconductor           | 139       | 7.86%   |
| Cambridge Silicon Radio         | 121       | 6.84%   |
| Lite-On Technology              | 92        | 5.2%    |
| IMC Networks                    | 85        | 4.8%    |
| Dell                            | 78        | 4.41%   |
| Hewlett-Packard                 | 73        | 4.13%   |
| Ralink                          | 68        | 3.84%   |
| Foxconn / Hon Hai               | 63        | 3.56%   |
| Toshiba                         | 23        | 1.3%    |
| ASUSTek Computer                | 22        | 1.24%   |
| Apple                           | 15        | 0.85%   |
| Ralink Technology               | 9         | 0.51%   |
| Realtek                         | 8         | 0.45%   |
| Askey Computer                  | 7         | 0.4%    |
| Conwise Technology              | 6         | 0.34%   |
| Chicony Electronics             | 5         | 0.28%   |
| Belkin Components               | 5         | 0.28%   |
| Taiyo Yuden                     | 4         | 0.23%   |
| Integrated System Solution      | 4         | 0.23%   |
| Foxconn International           | 4         | 0.23%   |
| Micro Star International        | 3         | 0.17%   |
| MediaTek                        | 3         | 0.17%   |
| Logitech                        | 3         | 0.17%   |
| TP-Link                         | 2         | 0.11%   |
| Edimax Technology               | 2         | 0.11%   |
| Alps Electric                   | 2         | 0.11%   |
| Opticis                         | 1         | 0.06%   |
| Fujitsu Siemens Computers       | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 335       | 18.91%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 121       | 6.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 86        | 4.85%   |
| Realtek Bluetooth Radio                             | 77        | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 74        | 4.18%   |
| Ralink RT3290 Bluetooth                             | 68        | 3.84%   |
| Intel AX201 Bluetooth                               | 56        | 3.16%   |
| Dell DW375 Bluetooth Module                         | 39        | 2.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 38        | 2.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 36        | 2.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 34        | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 32        | 1.81%   |
| Intel AX200 Bluetooth                               | 32        | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 32        | 1.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 30        | 1.69%   |
| IMC Networks Bluetooth Device                       | 26        | 1.47%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.3%    |
| Broadcom HP Portable SoftSailing                    | 22        | 1.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.19%   |
| Lite-On Bluetooth Device                            | 21        | 1.19%   |
| Realtek RTL8723B Bluetooth                          | 20        | 1.13%   |
| Realtek RTL8821A Bluetooth                          | 19        | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.07%   |
| IMC Networks Wireless_Device                        | 18        | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 0.85%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.73%   |
| Broadcom BCM2070 Bluetooth Device                   | 11        | 0.62%   |
| Toshiba Bluetooth Device                            | 10        | 0.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 10        | 0.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 9         | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.51%   |
| Realtek Bluetooth Radio                             | 8         | 0.45%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2689      | 59.14%  |
| AMD                                  | 916       | 20.15%  |
| Nvidia                               | 644       | 14.16%  |
| C-Media Electronics                  | 79        | 1.74%   |
| Creative Labs                        | 37        | 0.81%   |
| Logitech                             | 19        | 0.42%   |
| VIA Technologies                     | 16        | 0.35%   |
| Texas Instruments                    | 14        | 0.31%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.31%   |
| ASUSTek Computer                     | 13        | 0.29%   |
| Generalplus Technology               | 11        | 0.24%   |
| Kingston Technology                  | 7         | 0.15%   |
| JMTek                                | 7         | 0.15%   |
| Creative Technology                  | 7         | 0.15%   |
| BEHRINGER International              | 6         | 0.13%   |
| Plantronics                          | 5         | 0.11%   |
| SteelSeries ApS                      | 4         | 0.09%   |
| GN Netcom                            | 4         | 0.09%   |
| Samson Technologies                  | 3         | 0.07%   |
| Lenovo                               | 3         | 0.07%   |
| Focusrite-Novation                   | 3         | 0.07%   |
| Tenx Technology                      | 2         | 0.04%   |
| Sennheiser Communications            | 2         | 0.04%   |
| Realtek Semiconductor                | 2         | 0.04%   |
| Hewlett-Packard                      | 2         | 0.04%   |
| Ensoniq                              | 2         | 0.04%   |
| D&M Holdings (Denon/Marantz)         | 2         | 0.04%   |
| ATI Technologies                     | 2         | 0.04%   |
| Yamaha                               | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |
| TEAC                                 | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |
| Superlux digit                       | 1         | 0.02%   |
| Sunplus Technology                   | 1         | 0.02%   |
| Sony                                 | 1         | 0.02%   |
| SM950T Microphone                    | 1         | 0.02%   |
| Rotel                                | 1         | 0.02%   |
| Reloop                               | 1         | 0.02%   |
| Promethean Limited                   | 1         | 0.02%   |
| PreSonus Audio Electronics           | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 301       | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 271       | 5.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 260       | 4.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 237       | 4.38%   |
| AMD FCH Azalia Controller                                                                         | 233       | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 219       | 4.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 187       | 3.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 183       | 3.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 181       | 3.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 134       | 2.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 114       | 2.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 110       | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 94        | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 93        | 1.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 88        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 85        | 1.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 84        | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 84        | 1.55%   |
| AMD Trinity HDMI Audio Controller                                                                 | 82        | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 82        | 1.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 72        | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 64        | 1.18%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 62        | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 58        | 1.07%   |
| Intel 200 Series PCH HD Audio                                                                     | 57        | 1.05%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 55        | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 54        | 1%      |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 53        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 52        | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 52        | 0.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 51        | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 50        | 0.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 48        | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 46        | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 46        | 0.85%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 44        | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 43        | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 43        | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 42        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 37        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 665       | 19.66%  |
| SK hynix                   | 637       | 18.84%  |
| Unknown                    | 602       | 17.8%   |
| Kingston                   | 538       | 15.91%  |
| Micron Technology          | 269       | 7.95%   |
| Nanya Technology           | 106       | 3.13%   |
| Elpida                     | 82        | 2.42%   |
| Kingmax                    | 73        | 2.16%   |
| Crucial                    | 72        | 2.13%   |
| Corsair                    | 58        | 1.71%   |
| Ramaxel Technology         | 50        | 1.48%   |
| G.Skill                    | 45        | 1.33%   |
| A-DATA Technology          | 36        | 1.06%   |
| CSX                        | 18        | 0.53%   |
| Team                       | 13        | 0.38%   |
| Qimonda                    | 12        | 0.35%   |
| Patriot                    | 10        | 0.3%    |
| 48spaces                   | 10        | 0.3%    |
| Transcend                  | 9         | 0.27%   |
| ASint Technology           | 9         | 0.27%   |
| Melco                      | 8         | 0.24%   |
| Unknown (ABCD)             | 7         | 0.21%   |
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
| Hikvision                  | 2         | 0.06%   |
| H                          | 2         | 0.06%   |
| Golden Empire              | 2         | 0.06%   |
| ZION                       | 1         | 0.03%   |
| Unknown (8A5B)             | 1         | 0.03%   |
| Unknown (7F7F7F7F7F970000) | 1         | 0.03%   |
| Unigen                     | 1         | 0.03%   |
| Toshiba-0098               | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s       | 42        | 1.12%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 41        | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 38        | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 34        | 0.91%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 33        | 0.88%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 33        | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 33        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 31        | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 27        | 0.72%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 0.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 24        | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 23        | 0.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 22        | 0.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 21        | 0.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s       | 21        | 0.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 20        | 0.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 20        | 0.53%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 20        | 0.53%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 19        | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 18        | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 18        | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 18        | 0.48%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s       | 18        | 0.48%   |
| Unknown RAM Module 1024MB DIMM SDRAM                      | 17        | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 17        | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 17        | 0.45%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 17        | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 16        | 0.43%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 16        | 0.43%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                    | 16        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 16        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 16        | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 16        | 0.43%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s     | 16        | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 15        | 0.4%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 15        | 0.4%    |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 15        | 0.4%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s    | 15        | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s | 13        | 0.35%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 13        | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1352      | 46.65%  |
| DDR4    | 618       | 21.33%  |
| DDR2    | 383       | 13.22%  |
| SDRAM   | 225       | 7.76%   |
| Unknown | 177       | 6.11%   |
| DDR     | 59        | 2.04%   |
| LPDDR4  | 41        | 1.41%   |
| LPDDR3  | 20        | 0.69%   |
| DDR5    | 10        | 0.35%   |
| DRAM    | 9         | 0.31%   |
| LPDDR5  | 4         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1582      | 56.48%  |
| DIMM         | 1166      | 41.63%  |
| Row Of Chips | 43        | 1.54%   |
| Chip         | 7         | 0.25%   |
| RIMM         | 2         | 0.07%   |
| FB-DIMM      | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 1151      | 36.19%  |
| 2048    | 873       | 27.45%  |
| 8192    | 599       | 18.84%  |
| 1024    | 331       | 10.41%  |
| 16384   | 137       | 4.31%   |
| 512     | 53        | 1.67%   |
| 32768   | 30        | 0.94%   |
| 256     | 4         | 0.13%   |
| Unknown | 2         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 826       | 25.81%  |
| 1333    | 304       | 9.5%    |
| 2667    | 241       | 7.53%   |
| 667     | 213       | 6.66%   |
| 800     | 208       | 6.5%    |
| 1334    | 178       | 5.56%   |
| 2400    | 156       | 4.88%   |
| Unknown | 137       | 4.28%   |
| 3200    | 122       | 3.81%   |
| 2133    | 105       | 3.28%   |
| 1067    | 86        | 2.69%   |
| 1866    | 63        | 1.97%   |
| 1867    | 52        | 1.63%   |
| 1066    | 50        | 1.56%   |
| 533     | 50        | 1.56%   |
| 2048    | 44        | 1.38%   |
| 4199    | 43        | 1.34%   |
| 3600    | 38        | 1.19%   |
| 400     | 35        | 1.09%   |
| 975     | 19        | 0.59%   |
| 3266    | 18        | 0.56%   |
| 1639    | 18        | 0.56%   |
| 1800    | 15        | 0.47%   |
| 333     | 14        | 0.44%   |
| 3466    | 13        | 0.41%   |
| 3400    | 13        | 0.41%   |
| 3000    | 12        | 0.38%   |
| 2933    | 10        | 0.31%   |
| 2666    | 10        | 0.31%   |
| 2000    | 9         | 0.28%   |
| 3151    | 7         | 0.22%   |
| 49926   | 6         | 0.19%   |
| 4800    | 6         | 0.19%   |
| 4267    | 6         | 0.19%   |
| 4266    | 6         | 0.19%   |
| 5808    | 5         | 0.16%   |
| 3733    | 5         | 0.16%   |
| 6400    | 4         | 0.13%   |
| 3333    | 4         | 0.13%   |
| 2134    | 4         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 56        | 47.46%  |
| Samsung Electronics   | 24        | 20.34%  |
| Canon                 | 14        | 11.86%  |
| Brother Industries    | 9         | 7.63%   |
| Seiko Epson           | 6         | 5.08%   |
| QinHeng Electronics   | 2         | 1.69%   |
| Lexmark International | 2         | 1.69%   |
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
| HP DeskJet 2600 series                                    | 8         | 6.67%   |
| HP LaserJet 1020                                          | 6         | 5%      |
| Samsung ML-2010P Mono Laser Printer                       | 5         | 4.17%   |
| Samsung M2020 Series                                      | 5         | 4.17%   |
| HP DeskJet 2130 series                                    | 4         | 3.33%   |
| Samsung ML-1640 Series Laser Printer                      | 3         | 2.5%    |
| HP LaserJet P1005                                         | 3         | 2.5%    |
| HP LaserJet 1018                                          | 3         | 2.5%    |
| HP Deskjet 2050 J510                                      | 3         | 2.5%    |
| Canon LiDE 400                                            | 3         | 2.5%    |
| Brother HL-1110 series                                    | 3         | 2.5%    |
| Samsung SCX-3400 Series                                   | 2         | 1.67%   |
| QinHeng CH340S                                            | 2         | 1.67%   |
| HP Officejet J4500 series                                 | 2         | 1.67%   |
| HP LaserJet P1102                                         | 2         | 1.67%   |
| HP LaserJet 1022                                          | 2         | 1.67%   |
| HP LaserJet 1010                                          | 2         | 1.67%   |
| HP LaserJet 1000                                          | 2         | 1.67%   |
| HP DeskJet F4100 Printer series                           | 2         | 1.67%   |
| HP Deskjet F2280 series                                   | 2         | 1.67%   |
| HP DeskJet F2100 Printer series                           | 2         | 1.67%   |
| HP DeskJet 840c                                           | 2         | 1.67%   |
| HP Deskjet 3520 series                                    | 2         | 1.67%   |
| Canon TS5100 series                                       | 2         | 1.67%   |
| Brother HL-L2300D series                                  | 2         | 1.67%   |
| Xerox WorkCentre 3119 Series                              | 1         | 0.83%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.83%   |
| Seiko Epson XP-243 245 247 Series                         | 1         | 0.83%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.83%   |
| Seiko Epson Printer                                       | 1         | 0.83%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.83%   |
| Seiko Epson L396 Series                                   | 1         | 0.83%   |
| Seiko Epson L120 Series                                   | 1         | 0.83%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 0.83%   |
| Samsung SCX-4650 4x21S Series                             | 1         | 0.83%   |
| Samsung SCX-4623 Series                                   | 1         | 0.83%   |
| Samsung SCX-4200 series                                   | 1         | 0.83%   |
| Samsung ML-1660 Series                                    | 1         | 0.83%   |
| Samsung ML-1630 Series                                    | 1         | 0.83%   |
| Samsung Composite Device                                  | 1         | 0.83%   |

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
| Chicony Electronics                    | 478       | 24.81%  |
| Microdia                               | 192       | 9.96%   |
| IMC Networks                           | 184       | 9.55%   |
| Realtek Semiconductor                  | 158       | 8.2%    |
| Sunplus Innovation Technology          | 125       | 6.49%   |
| Acer                                   | 101       | 5.24%   |
| Suyin                                  | 86        | 4.46%   |
| Quanta                                 | 68        | 3.53%   |
| Cheng Uei Precision Industry (Foxlink) | 65        | 3.37%   |
| Logitech                               | 56        | 2.91%   |
| Syntek                                 | 47        | 2.44%   |
| Lite-On Technology                     | 34        | 1.76%   |
| Silicon Motion                         | 33        | 1.71%   |
| Lenovo                                 | 30        | 1.56%   |
| Alcor Micro                            | 23        | 1.19%   |
| Z-Star Microelectronics                | 22        | 1.14%   |
| Primax Electronics                     | 20        | 1.04%   |
| KYE Systems (Mouse Systems)            | 17        | 0.88%   |
| Bison Electronics                      | 17        | 0.88%   |
| Ricoh                                  | 16        | 0.83%   |
| Microsoft                              | 16        | 0.83%   |
| Apple                                  | 16        | 0.83%   |
| Samsung Electronics                    | 13        | 0.67%   |
| Luxvisions Innotech Limited            | 11        | 0.57%   |
| ALi                                    | 11        | 0.57%   |
| Importek                               | 9         | 0.47%   |
| GEMBIRD                                | 9         | 0.47%   |
| Trust                                  | 6         | 0.31%   |
| OmniVision Technologies                | 6         | 0.31%   |
| Sonix Technology                       | 5         | 0.26%   |
| Arkmicro Technologies                  | 5         | 0.26%   |
| LG Electronics                         | 4         | 0.21%   |
| Pixart Imaging                         | 3         | 0.16%   |
| MacroSilicon                           | 3         | 0.16%   |
| Jieli Technology                       | 3         | 0.16%   |
| Generalplus Technology                 | 3         | 0.16%   |
| DigiTech                               | 3         | 0.16%   |
| Cubeternet                             | 3         | 0.16%   |
| Creative Technology                    | 3         | 0.16%   |
| Aveo Technology                        | 3         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 58        | 3%      |
| IMC Networks USB2.0 VGA UVC WebCam            | 54        | 2.79%   |
| Chicony HD WebCam                             | 45        | 2.33%   |
| Microdia Integrated_Webcam_HD                 | 44        | 2.27%   |
| IMC Networks USB2.0 HD UVC WebCam             | 41        | 2.12%   |
| Chicony HP TrueVision HD                      | 40        | 2.07%   |
| Acer Lenovo EasyCamera                        | 33        | 1.71%   |
| Sunplus Integrated_Webcam_HD                  | 31        | 1.6%    |
| Realtek Integrated_Webcam_HD                  | 29        | 1.5%    |
| Chicony USB2.0 VGA UVC WebCam                 | 29        | 1.5%    |
| Sunplus HP Truevision HD                      | 24        | 1.24%   |
| Microdia Integrated Webcam                    | 24        | 1.24%   |
| Chicony Lenovo EasyCamera                     | 23        | 1.19%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 22        | 1.14%   |
| Realtek USB Camera                            | 21        | 1.09%   |
| Sunplus HD WebCam                             | 19        | 0.98%   |
| Logitech Webcam C270                          | 19        | 0.98%   |
| IMC Networks EasyCamera                       | 19        | 0.98%   |
| Chicony USB2.0 HD UVC WebCam                  | 18        | 0.93%   |
| Chicony EasyCamera                            | 18        | 0.93%   |
| Quanta VGA WebCam                             | 17        | 0.88%   |
| Chicony VGA WebCam                            | 17        | 0.88%   |
| Chicony Integrated HP HD Webcam               | 17        | 0.88%   |
| Chicony FJ Camera                             | 17        | 0.88%   |
| Microdia Sonix USB 2.0 Camera                 | 16        | 0.83%   |
| Lenovo Integrated Webcam                      | 16        | 0.83%   |
| Realtek Integrated Webcam                     | 15        | 0.78%   |
| IMC Networks Integrated Camera                | 15        | 0.78%   |
| Primax HP HD Webcam [Fixed]                   | 14        | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD          | 14        | 0.72%   |
| Microdia Camera                               | 14        | 0.72%   |
| Chicony HP Webcam [2 MP Macro]                | 14        | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 14        | 0.72%   |
| Syntek Integrated Camera                      | 13        | 0.67%   |
| Lenovo Integrated Webcam [R5U877]             | 13        | 0.67%   |
| Acer Lenovo Integrated Webcam                 | 13        | 0.67%   |
| Syntek Lenovo EasyCamera                      | 12        | 0.62%   |
| Samsung Galaxy A5 (MTP)                       | 12        | 0.62%   |
| Realtek Lenovo EasyCamera                     | 12        | 0.62%   |
| Syntek EasyCamera                             | 11        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 102       | 37.92%  |
| AuthenTec                          | 56        | 20.82%  |
| Synaptics                          | 34        | 12.64%  |
| Upek                               | 23        | 8.55%   |
| Shenzhen Goodix Technology         | 17        | 6.32%   |
| LighTuning Technology              | 17        | 6.32%   |
| STMicroelectronics                 | 10        | 3.72%   |
| Elan Microelectronics              | 9         | 3.35%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 9.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 23        | 8.55%   |
| AuthenTec AES2810                                                          | 23        | 8.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 19        | 7.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 4.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 4.46%   |
| Validity Sensors VFS491                                                    | 10        | 3.72%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 3.72%   |
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 3.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 3.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 3.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.6%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.23%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 2.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.23%   |
| LighTuning Fingerprint Reader                                              | 6         | 2.23%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.23%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 2.23%   |
| Synaptics  WBDI                                                            | 5         | 1.86%   |
| AuthenTec AES1600                                                          | 5         | 1.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.49%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.49%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.12%   |
| Synaptics WBDI                                                             | 3         | 1.12%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.74%   |
| Synaptics UWP WBDI                                                         | 2         | 0.74%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.74%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.37%   |
| Synaptics WBDI Device                                                      | 1         | 0.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.37%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.37%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.37%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 115       | 54.5%   |
| Alcor Micro               | 31        | 14.69%  |
| O2 Micro                  | 27        | 12.8%   |
| Lenovo                    | 27        | 12.8%   |
| Upek                      | 3         | 1.42%   |
| Gemalto (was Gemplus)     | 3         | 1.42%   |
| Yubico.com                | 1         | 0.47%   |
| Reiner SCT Kartensysteme  | 1         | 0.47%   |
| Chicony Electronics       | 1         | 0.47%   |
| Aladdin Knowledge Systems | 1         | 0.47%   |
| Advanced Card Systems     | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 61        | 28.91%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 31        | 14.69%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 12.8%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 26        | 12.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 24        | 11.37%  |
| Broadcom 5880                                                                | 15        | 7.11%   |
| Broadcom 58200                                                               | 15        | 7.11%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 1.42%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.47%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.47%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.47%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.47%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.47%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2684      | 73.45%  |
| 1     | 795       | 21.76%  |
| 2     | 155       | 4.24%   |
| 3     | 14        | 0.38%   |
| 4     | 4         | 0.11%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 296       | 26.29%  |
| Fingerprint reader       | 269       | 23.89%  |
| Chipcard                 | 196       | 17.41%  |
| Net/wireless             | 91        | 8.08%   |
| Bluetooth                | 78        | 6.93%   |
| Multimedia controller    | 46        | 4.09%   |
| Storage                  | 37        | 3.29%   |
| Communication controller | 34        | 3.02%   |
| Camera                   | 22        | 1.95%   |
| Flash memory             | 17        | 1.51%   |
| Unassigned class         | 11        | 0.98%   |
| Sound                    | 6         | 0.53%   |
| Card reader              | 6         | 0.53%   |
| Storage/raid             | 4         | 0.36%   |
| Net/ethernet             | 4         | 0.36%   |
| Dvb card                 | 3         | 0.27%   |
| Network                  | 2         | 0.18%   |
| Modem                    | 2         | 0.18%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

