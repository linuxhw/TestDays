Linux in Italy - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 10480

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | 970 Pro3 R2.0               | Desktop     | [577b5e8f51](https://linux-hardware.org/?probe=577b5e8f51) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b2adc0ae5](https://linux-hardware.org/?probe=1b2adc0ae5) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [4ac55a6bbe](https://linux-hardware.org/?probe=4ac55a6bbe) | Apr 30, 2023 |
| HP            | Compaq 6720s                | Notebook    | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [77f87da085](https://linux-hardware.org/?probe=77f87da085) | Apr 29, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [e585f66f17](https://linux-hardware.org/?probe=e585f66f17) | Apr 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [4801547d54](https://linux-hardware.org/?probe=4801547d54) | Apr 29, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Intel         | NUC6i7KYB H90766-405        | Mini pc     | [19bb30e27a](https://linux-hardware.org/?probe=19bb30e27a) | Apr 29, 2023 |
| HP            | 1998                        | Desktop     | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| HP            | 339A                        | Desktop     | [4f9a0b2661](https://linux-hardware.org/?probe=4f9a0b2661) | Apr 28, 2023 |
| Rockchip      | Unknown                     | Soc         | [5236b9452c](https://linux-hardware.org/?probe=5236b9452c) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | Desktop     | [94f2408a63](https://linux-hardware.org/?probe=94f2408a63) | Apr 28, 2023 |
| Unknown       | RS780-SB700                 | Desktop     | [76c36882d9](https://linux-hardware.org/?probe=76c36882d9) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | Latitude E6400              | Notebook    | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [a5d42a7b78](https://linux-hardware.org/?probe=a5d42a7b78) | Apr 26, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | Notebook    | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| HP            | ENVY 15                     | Notebook    | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [98ed5e9a2e](https://linux-hardware.org/?probe=98ed5e9a2e) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b144f1aa54](https://linux-hardware.org/?probe=b144f1aa54) | Apr 24, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [7ca2bb8871](https://linux-hardware.org/?probe=7ca2bb8871) | Apr 24, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [34278ef67e](https://linux-hardware.org/?probe=34278ef67e) | Apr 24, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [2ea3950e19](https://linux-hardware.org/?probe=2ea3950e19) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| MSI           | B460M PRO-VDH               | Desktop     | [f7709c23a1](https://linux-hardware.org/?probe=f7709c23a1) | Apr 24, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [c59dbdea18](https://linux-hardware.org/?probe=c59dbdea18) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| AMI           | Intel                       | Desktop     | [62d06b215e](https://linux-hardware.org/?probe=62d06b215e) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Dell          | Inspiron MP061              | Notebook    | [2b25a48030](https://linux-hardware.org/?probe=2b25a48030) | Apr 23, 2023 |
| ASRock        | Z77 Pro3                    | Desktop     | [2f4b412834](https://linux-hardware.org/?probe=2f4b412834) | Apr 22, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| ASUSTek       | ET1602                      | Desktop     | [637fb8c9ce](https://linux-hardware.org/?probe=637fb8c9ce) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [8fd7aea5ea](https://linux-hardware.org/?probe=8fd7aea5ea) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [47ea666f74](https://linux-hardware.org/?probe=47ea666f74) | Apr 21, 2023 |
| HP            | Compaq 6735s                | Notebook    | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| HP            | Compaq 6735s                | Notebook    | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| ELSKY         | M219F-6C                    | Desktop     | [5f41223856](https://linux-hardware.org/?probe=5f41223856) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [aace924665](https://linux-hardware.org/?probe=aace924665) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f7ca0a552d](https://linux-hardware.org/?probe=f7ca0a552d) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [3f390ff38e](https://linux-hardware.org/?probe=3f390ff38e) | Apr 20, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a4f54ca55b](https://linux-hardware.org/?probe=a4f54ca55b) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [b830d8001e](https://linux-hardware.org/?probe=b830d8001e) | Apr 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [6aa9d32dda](https://linux-hardware.org/?probe=6aa9d32dda) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9db7166b25](https://linux-hardware.org/?probe=9db7166b25) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | Notebook    | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | Notebook    | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | Notebook    | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| Otazak        | iPC45                       | Convertible | [1775e826d8](https://linux-hardware.org/?probe=1775e826d8) | Apr 18, 2023 |
| Gigabyte      | Z68X-UD7-B3                 | Desktop     | [175cfb374b](https://linux-hardware.org/?probe=175cfb374b) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | Notebook    | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| HP            | 18E9                        | Desktop     | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [b274726abd](https://linux-hardware.org/?probe=b274726abd) | Apr 17, 2023 |
| ASRock        | N3700-ITX                   | Desktop     | [849679b442](https://linux-hardware.org/?probe=849679b442) | Apr 17, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9df377aaf2](https://linux-hardware.org/?probe=9df377aaf2) | Apr 17, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [317efe55c2](https://linux-hardware.org/?probe=317efe55c2) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0a544df503](https://linux-hardware.org/?probe=0a544df503) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Medion        | E16401                      | Notebook    | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5109f5c8d9](https://linux-hardware.org/?probe=5109f5c8d9) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [67ce5b3ab1](https://linux-hardware.org/?probe=67ce5b3ab1) | Apr 16, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [bff38bc725](https://linux-hardware.org/?probe=bff38bc725) | Apr 16, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4375bd0fb6](https://linux-hardware.org/?probe=4375bd0fb6) | Apr 16, 2023 |
| ASUSTek       | P5E Deluxe                  | Desktop     | [ce0a1adc22](https://linux-hardware.org/?probe=ce0a1adc22) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Google        | Dragonair                   | Notebook    | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | Notebook    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a51b096e12](https://linux-hardware.org/?probe=a51b096e12) | Apr 15, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1f524a54fc](https://linux-hardware.org/?probe=1f524a54fc) | Apr 15, 2023 |
| MSI           | 970A-G45                    | Desktop     | [8f62fd1fb1](https://linux-hardware.org/?probe=8f62fd1fb1) | Apr 15, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [91696fe0f2](https://linux-hardware.org/?probe=91696fe0f2) | Apr 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [9f6209111c](https://linux-hardware.org/?probe=9f6209111c) | Apr 14, 2023 |
| Dell          | Latitude 9420               | Notebook    | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [540a259700](https://linux-hardware.org/?probe=540a259700) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [fa2c48478a](https://linux-hardware.org/?probe=fa2c48478a) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| MAXDATA       | o.max_5xs                   | Notebook    | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3b24daf87d](https://linux-hardware.org/?probe=3b24daf87d) | Apr 13, 2023 |
| Chuwi         | UBook X                     | Tablet      | [2e70372d4b](https://linux-hardware.org/?probe=2e70372d4b) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ea50bc5d28](https://linux-hardware.org/?probe=ea50bc5d28) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [23371691ec](https://linux-hardware.org/?probe=23371691ec) | Apr 12, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [214038993e](https://linux-hardware.org/?probe=214038993e) | Apr 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9408f6348b](https://linux-hardware.org/?probe=9408f6348b) | Apr 12, 2023 |
| Dell          | XPS 9315                    | Notebook    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [695de52123](https://linux-hardware.org/?probe=695de52123) | Apr 12, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [54a72d7d55](https://linux-hardware.org/?probe=54a72d7d55) | Apr 12, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [46eba03bed](https://linux-hardware.org/?probe=46eba03bed) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| Packard Be... | EasyNote_MX45               | Notebook    | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| Acer          | H57M01                      | Desktop     | [c62231ca98](https://linux-hardware.org/?probe=c62231ca98) | Apr 11, 2023 |
| Lenovo        | ThinkPad L530 24783B3       | Notebook    | [9cb172cc6b](https://linux-hardware.org/?probe=9cb172cc6b) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [dae979ddc0](https://linux-hardware.org/?probe=dae979ddc0) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [e6e26b16f3](https://linux-hardware.org/?probe=e6e26b16f3) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [2e428c73dc](https://linux-hardware.org/?probe=2e428c73dc) | Apr 10, 2023 |
| ASUSTek       | ZN240IC                     | All in one  | [557e50987c](https://linux-hardware.org/?probe=557e50987c) | Apr 09, 2023 |
| ASRock        | Q1900M                      | Desktop     | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [1f8dc6aa3d](https://linux-hardware.org/?probe=1f8dc6aa3d) | Apr 09, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [ff595db737](https://linux-hardware.org/?probe=ff595db737) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [0e6d01e44d](https://linux-hardware.org/?probe=0e6d01e44d) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [621eb9522f](https://linux-hardware.org/?probe=621eb9522f) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [23a244aaf4](https://linux-hardware.org/?probe=23a244aaf4) | Apr 09, 2023 |
| AMI           | Intel                       | Notebook    | [f35d255c12](https://linux-hardware.org/?probe=f35d255c12) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [594a8d9a89](https://linux-hardware.org/?probe=594a8d9a89) | Apr 08, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [cb57237789](https://linux-hardware.org/?probe=cb57237789) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | Notebook    | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| Lenovo        | ThinkPad 10 20C1002PUK      | Tablet      | [1133b0413b](https://linux-hardware.org/?probe=1133b0413b) | Apr 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e657bedde3](https://linux-hardware.org/?probe=e657bedde3) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | Notebook    | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [bd1dc31213](https://linux-hardware.org/?probe=bd1dc31213) | Apr 07, 2023 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [fccb05fbef](https://linux-hardware.org/?probe=fccb05fbef) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [1e9120783f](https://linux-hardware.org/?probe=1e9120783f) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| HP            | G61                         | Notebook    | [8eec217a3a](https://linux-hardware.org/?probe=8eec217a3a) | Apr 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bf0c0bb982](https://linux-hardware.org/?probe=bf0c0bb982) | Apr 07, 2023 |
| HP            | G61                         | Notebook    | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [9f5a3611b8](https://linux-hardware.org/?probe=9f5a3611b8) | Apr 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [241572fcea](https://linux-hardware.org/?probe=241572fcea) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| Samsung       | 950QED                      | Convertible | [c691077d2f](https://linux-hardware.org/?probe=c691077d2f) | Apr 06, 2023 |
| System76      | Oryx Pro                    | Notebook    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | 250 G4                      | Notebook    | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bf0fc7e5d1](https://linux-hardware.org/?probe=bf0fc7e5d1) | Apr 06, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [58e0aa6707](https://linux-hardware.org/?probe=58e0aa6707) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| Quanta        | XV1                         | All in one  | [7cce1c6f6f](https://linux-hardware.org/?probe=7cce1c6f6f) | Apr 06, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [51d2c2c17d](https://linux-hardware.org/?probe=51d2c2c17d) | Apr 06, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [3fae5e4d5c](https://linux-hardware.org/?probe=3fae5e4d5c) | Apr 05, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | Notebook    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | Notebook    | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [caf5563d44](https://linux-hardware.org/?probe=caf5563d44) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0e7d453676](https://linux-hardware.org/?probe=0e7d453676) | Apr 05, 2023 |
| Fujitsu       | LIFEBOOK U759               | Notebook    | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| Dell          | Latitude 5591               | Notebook    | [aa2f4e4208](https://linux-hardware.org/?probe=aa2f4e4208) | Apr 05, 2023 |
| MSI           | 2A9C                        | Desktop     | [7a007c46d0](https://linux-hardware.org/?probe=7a007c46d0) | Apr 05, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | Desktop     | [9fc5c6f8a7](https://linux-hardware.org/?probe=9fc5c6f8a7) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [45bcedba86](https://linux-hardware.org/?probe=45bcedba86) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f08ea6ee04](https://linux-hardware.org/?probe=f08ea6ee04) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [250b63078d](https://linux-hardware.org/?probe=250b63078d) | Apr 04, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f637374c21](https://linux-hardware.org/?probe=f637374c21) | Apr 03, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [13a42307a4](https://linux-hardware.org/?probe=13a42307a4) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | Notebook    | [93fa18f474](https://linux-hardware.org/?probe=93fa18f474) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | Notebook    | [915c34d052](https://linux-hardware.org/?probe=915c34d052) | Apr 03, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [cef60ea315](https://linux-hardware.org/?probe=cef60ea315) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | Notebook    | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| MSI           | Boston                      | Desktop     | [5a875def3f](https://linux-hardware.org/?probe=5a875def3f) | Apr 02, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b4207e264f](https://linux-hardware.org/?probe=b4207e264f) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| ASUSTek       | B150M-K D3                  | Desktop     | [08df6b50be](https://linux-hardware.org/?probe=08df6b50be) | Apr 02, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [a971008720](https://linux-hardware.org/?probe=a971008720) | Apr 02, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [a55c39912f](https://linux-hardware.org/?probe=a55c39912f) | Apr 01, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [217bb72a30](https://linux-hardware.org/?probe=217bb72a30) | Apr 01, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [bbbfbb2dfc](https://linux-hardware.org/?probe=bbbfbb2dfc) | Apr 01, 2023 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [50d4a766a6](https://linux-hardware.org/?probe=50d4a766a6) | Apr 01, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [d5337ce0e3](https://linux-hardware.org/?probe=d5337ce0e3) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [702a241ca6](https://linux-hardware.org/?probe=702a241ca6) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| Acer          | WG43M                       | Desktop     | [77cb0bf517](https://linux-hardware.org/?probe=77cb0bf517) | Apr 01, 2023 |
| HP            | Notebook                    | Notebook    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [363d925d25](https://linux-hardware.org/?probe=363d925d25) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| ASUSTek       | X556UAK                     | Notebook    | [24f79c68f6](https://linux-hardware.org/?probe=24f79c68f6) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| Microtech     | ebookPro                    | Notebook    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Latitude E7440              | Notebook    | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Pavilion 15                 | Notebook    | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | Notebook    | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| ASUSTek       | ET2400E                     | All in one  | [eb1110a2f0](https://linux-hardware.org/?probe=eb1110a2f0) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | Notebook    | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [871b458080](https://linux-hardware.org/?probe=871b458080) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Gigabyte      | Z390 M-CF                   | Desktop     | [6bce2b9bc3](https://linux-hardware.org/?probe=6bce2b9bc3) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Valve         | Jupiter                     | Notebook    | [34766581f3](https://linux-hardware.org/?probe=34766581f3) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [cacf95c277](https://linux-hardware.org/?probe=cacf95c277) | Mar 30, 2023 |
| DFI           | LP UT X58                   | Desktop     | [cd706d90d3](https://linux-hardware.org/?probe=cd706d90d3) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| Packard Be... | FIH57                       | Desktop     | [f1336c6cc4](https://linux-hardware.org/?probe=f1336c6cc4) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [4ccaa78b43](https://linux-hardware.org/?probe=4ccaa78b43) | Mar 30, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [3c641024ba](https://linux-hardware.org/?probe=3c641024ba) | Mar 30, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e8fc7722ef](https://linux-hardware.org/?probe=e8fc7722ef) | Mar 30, 2023 |
| Dell          | Precision 3560              | Notebook    | [f6ef5c1a2c](https://linux-hardware.org/?probe=f6ef5c1a2c) | Mar 30, 2023 |
| Samsung       | 950QED                      | Convertible | [20b6d6f93d](https://linux-hardware.org/?probe=20b6d6f93d) | Mar 30, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [25c5c7ee2e](https://linux-hardware.org/?probe=25c5c7ee2e) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0e8950a217](https://linux-hardware.org/?probe=0e8950a217) | Mar 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | Desktop     | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | Desktop     | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [9a6102422f](https://linux-hardware.org/?probe=9a6102422f) | Mar 29, 2023 |
| HP            | 3646h                       | Desktop     | [b173e99a5a](https://linux-hardware.org/?probe=b173e99a5a) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | Notebook    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [23256b54cf](https://linux-hardware.org/?probe=23256b54cf) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [53bc341050](https://linux-hardware.org/?probe=53bc341050) | Mar 29, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a38bcb83b3](https://linux-hardware.org/?probe=a38bcb83b3) | Mar 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [889e4e5eef](https://linux-hardware.org/?probe=889e4e5eef) | Mar 29, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [4266c0287d](https://linux-hardware.org/?probe=4266c0287d) | Mar 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [c9ac2eb353](https://linux-hardware.org/?probe=c9ac2eb353) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [f3ebf80a3d](https://linux-hardware.org/?probe=f3ebf80a3d) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | One S1003                   | Tablet      | [89fa2c4ac3](https://linux-hardware.org/?probe=89fa2c4ac3) | Mar 28, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [5ac9dd16da](https://linux-hardware.org/?probe=5ac9dd16da) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | Notebook    | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [26d819f9fc](https://linux-hardware.org/?probe=26d819f9fc) | Mar 27, 2023 |
| HP            | 250 G1                      | Notebook    | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | 18E6                        | Desktop     | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| Acer          | Mammoth                     | Notebook    | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [da016d15c7](https://linux-hardware.org/?probe=da016d15c7) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | Notebook    | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [6f77d9be36](https://linux-hardware.org/?probe=6f77d9be36) | Mar 26, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | Notebook    | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [eddf5a759a](https://linux-hardware.org/?probe=eddf5a759a) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [0c2be4a34c](https://linux-hardware.org/?probe=0c2be4a34c) | Mar 26, 2023 |
| Intel         | NUC5i7RYB H73774-105        | Mini pc     | [584e5e014a](https://linux-hardware.org/?probe=584e5e014a) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4a4f12631a](https://linux-hardware.org/?probe=4a4f12631a) | Mar 26, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c7e347798a](https://linux-hardware.org/?probe=c7e347798a) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [3b8cd70b69](https://linux-hardware.org/?probe=3b8cd70b69) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | Notebook    | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | Notebook    | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [5b3d7995b2](https://linux-hardware.org/?probe=5b3d7995b2) | Mar 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [518cef7fe4](https://linux-hardware.org/?probe=518cef7fe4) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [dc56fbfedb](https://linux-hardware.org/?probe=dc56fbfedb) | Mar 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [67d60d55e4](https://linux-hardware.org/?probe=67d60d55e4) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [9fd6508caf](https://linux-hardware.org/?probe=9fd6508caf) | Mar 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [7ed577df49](https://linux-hardware.org/?probe=7ed577df49) | Mar 23, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [175f99ccdd](https://linux-hardware.org/?probe=175f99ccdd) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | Notebook    | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [ad6a144db9](https://linux-hardware.org/?probe=ad6a144db9) | Mar 23, 2023 |
| Lenovo        | SDK0F82993 WIN              | Desktop     | [fbff3ec47c](https://linux-hardware.org/?probe=fbff3ec47c) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [007a0b3bb7](https://linux-hardware.org/?probe=007a0b3bb7) | Mar 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | Notebook    | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [ac856abadc](https://linux-hardware.org/?probe=ac856abadc) | Mar 21, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [074de9621d](https://linux-hardware.org/?probe=074de9621d) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [de1c89d1b0](https://linux-hardware.org/?probe=de1c89d1b0) | Mar 21, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [926d18b722](https://linux-hardware.org/?probe=926d18b722) | Mar 20, 2023 |
| Acer          | Extensa 5235                | Notebook    | [270cd6ed83](https://linux-hardware.org/?probe=270cd6ed83) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [f320bc5964](https://linux-hardware.org/?probe=f320bc5964) | Mar 20, 2023 |
| Acer          | Veriton M4610G              | Desktop     | [fed7efcecb](https://linux-hardware.org/?probe=fed7efcecb) | Mar 20, 2023 |
| Acer          | Aspire C24-320              | All in one  | [21de7ff6d5](https://linux-hardware.org/?probe=21de7ff6d5) | Mar 20, 2023 |
| HP            | 872E                        | Mini pc     | [4be8ddc98e](https://linux-hardware.org/?probe=4be8ddc98e) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [42290142fb](https://linux-hardware.org/?probe=42290142fb) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3500d84a8e](https://linux-hardware.org/?probe=3500d84a8e) | Mar 19, 2023 |
| Notebook      | P15SM                       | Notebook    | [00d7786f9f](https://linux-hardware.org/?probe=00d7786f9f) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Microtech     | CoreBook                    | Notebook    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | Notebook    | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | Notebook    | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [727e5c46b7](https://linux-hardware.org/?probe=727e5c46b7) | Mar 18, 2023 |
| Quanta        | XV1                         | All in one  | [2bbbb73d41](https://linux-hardware.org/?probe=2bbbb73d41) | Mar 18, 2023 |
| MSI           | H55M-P31                    | Desktop     | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [63ecda6230](https://linux-hardware.org/?probe=63ecda6230) | Mar 18, 2023 |
| HP            | 18E7                        | Desktop     | [9f4d303ffa](https://linux-hardware.org/?probe=9f4d303ffa) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b346ffbe8e](https://linux-hardware.org/?probe=b346ffbe8e) | Mar 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [b21fb664f8](https://linux-hardware.org/?probe=b21fb664f8) | Mar 17, 2023 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [be6db6cc62](https://linux-hardware.org/?probe=be6db6cc62) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| AMI           | Intel                       | Desktop     | [491d2cca9d](https://linux-hardware.org/?probe=491d2cca9d) | Mar 17, 2023 |
| HP            | ProBook 6570b               | Notebook    | [f5c9cd8419](https://linux-hardware.org/?probe=f5c9cd8419) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| HP            | 255 G3                      | Notebook    | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [ef104e7202](https://linux-hardware.org/?probe=ef104e7202) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [045474725b](https://linux-hardware.org/?probe=045474725b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | Notebook    | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [730eec29f4](https://linux-hardware.org/?probe=730eec29f4) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [fc387a787e](https://linux-hardware.org/?probe=fc387a787e) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [b0b311216d](https://linux-hardware.org/?probe=b0b311216d) | Mar 14, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [37f8d341e3](https://linux-hardware.org/?probe=37f8d341e3) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ce69431d69](https://linux-hardware.org/?probe=ce69431d69) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| HP            | ProLiant DL380 G4           | Server      | [403a18bfff](https://linux-hardware.org/?probe=403a18bfff) | Mar 14, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ec3dcfdbc0](https://linux-hardware.org/?probe=ec3dcfdbc0) | Mar 14, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [64f7f16909](https://linux-hardware.org/?probe=64f7f16909) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [d9f9e09a41](https://linux-hardware.org/?probe=d9f9e09a41) | Mar 14, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [e186537a7e](https://linux-hardware.org/?probe=e186537a7e) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [af6b7e8138](https://linux-hardware.org/?probe=af6b7e8138) | Mar 13, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [be16fd4aab](https://linux-hardware.org/?probe=be16fd4aab) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [6ecc8f0bad](https://linux-hardware.org/?probe=6ecc8f0bad) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [ee01825196](https://linux-hardware.org/?probe=ee01825196) | Mar 13, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [13f42eb616](https://linux-hardware.org/?probe=13f42eb616) | Mar 13, 2023 |
| Quanta        | XV1                         | All in one  | [930e98f517](https://linux-hardware.org/?probe=930e98f517) | Mar 13, 2023 |
| HP            | 18E7                        | Desktop     | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Acer          | One S1003                   | Tablet      | [89fff0b13a](https://linux-hardware.org/?probe=89fff0b13a) | Mar 12, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [a7105953c2](https://linux-hardware.org/?probe=a7105953c2) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Acer          | aspire5740                  | Notebook    | [d5e64f31d4](https://linux-hardware.org/?probe=d5e64f31d4) | Mar 12, 2023 |
| MSI           | P55-CD53                    | Desktop     | [d492118b16](https://linux-hardware.org/?probe=d492118b16) | Mar 12, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [50e790583a](https://linux-hardware.org/?probe=50e790583a) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [ce0343a044](https://linux-hardware.org/?probe=ce0343a044) | Mar 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [17431ae177](https://linux-hardware.org/?probe=17431ae177) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Dell          | 0P03DX A04                  | Desktop     | [e1c38bafaa](https://linux-hardware.org/?probe=e1c38bafaa) | Mar 11, 2023 |
| Dell          | Latitude E6440              | Notebook    | [e5ba284442](https://linux-hardware.org/?probe=e5ba284442) | Mar 11, 2023 |
| HP            | G61                         | Notebook    | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [b7de8d093d](https://linux-hardware.org/?probe=b7de8d093d) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [278b9e10a7](https://linux-hardware.org/?probe=278b9e10a7) | Mar 11, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [caaa97e4ba](https://linux-hardware.org/?probe=caaa97e4ba) | Mar 11, 2023 |
| MSI           | Z590-A PRO                  | Desktop     | [c0c43b3296](https://linux-hardware.org/?probe=c0c43b3296) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5d7fdfa3ab](https://linux-hardware.org/?probe=5d7fdfa3ab) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| Acer          | Aspire TC-380               | Desktop     | [563bd52487](https://linux-hardware.org/?probe=563bd52487) | Mar 10, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [1315898b67](https://linux-hardware.org/?probe=1315898b67) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | Notebook    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [689186d7de](https://linux-hardware.org/?probe=689186d7de) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [420b463f4d](https://linux-hardware.org/?probe=420b463f4d) | Mar 10, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [493a2b9df6](https://linux-hardware.org/?probe=493a2b9df6) | Mar 10, 2023 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [0fb1309bff](https://linux-hardware.org/?probe=0fb1309bff) | Mar 10, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [de3c24e686](https://linux-hardware.org/?probe=de3c24e686) | Mar 10, 2023 |
| HP            | 2B35                        | Desktop     | [ddb4d051ab](https://linux-hardware.org/?probe=ddb4d051ab) | Mar 09, 2023 |
| HP            | 2B35                        | Desktop     | [83f9096b77](https://linux-hardware.org/?probe=83f9096b77) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [041ebfc8c6](https://linux-hardware.org/?probe=041ebfc8c6) | Mar 09, 2023 |
| MSI           | 970A-G46                    | Desktop     | [322eb2bdf0](https://linux-hardware.org/?probe=322eb2bdf0) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Acer          | Veriton M480                | Desktop     | [8cd45e8525](https://linux-hardware.org/?probe=8cd45e8525) | Mar 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | Desktop     | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | Notebook    | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Intel         | NUC10i3FNB K61362-303       | Mini pc     | [d19762a0e5](https://linux-hardware.org/?probe=d19762a0e5) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| HP            | 8433 11                     | Desktop     | [95f33803c0](https://linux-hardware.org/?probe=95f33803c0) | Mar 08, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [8faa1d14ca](https://linux-hardware.org/?probe=8faa1d14ca) | Mar 08, 2023 |
| ASRock        | 970 Performance             | Desktop     | [c018d98ddc](https://linux-hardware.org/?probe=c018d98ddc) | Mar 08, 2023 |
| Lenovo        | CRESCENTBAY 31900056 PRO... | All in one  | [4189f851d8](https://linux-hardware.org/?probe=4189f851d8) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | Notebook    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| ASUSTek       | H81T                        | Desktop     | [c17251dbd9](https://linux-hardware.org/?probe=c17251dbd9) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Timi          | TM1701                      | Notebook    | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [4630034dbc](https://linux-hardware.org/?probe=4630034dbc) | Mar 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a1631eb10b](https://linux-hardware.org/?probe=a1631eb10b) | Mar 07, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| Acer          | Veriton X4610G              | Desktop     | [7f5cb2ac6a](https://linux-hardware.org/?probe=7f5cb2ac6a) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [5a706c6543](https://linux-hardware.org/?probe=5a706c6543) | Mar 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0a85b4da67](https://linux-hardware.org/?probe=0a85b4da67) | Mar 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [fdc4f4d3c6](https://linux-hardware.org/?probe=fdc4f4d3c6) | Mar 07, 2023 |
| Dell          | Latitude 5330               | Notebook    | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [f56dc75b4e](https://linux-hardware.org/?probe=f56dc75b4e) | Mar 07, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [e4e709f69a](https://linux-hardware.org/?probe=e4e709f69a) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [ff1a57749f](https://linux-hardware.org/?probe=ff1a57749f) | Mar 07, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [37f7cabb58](https://linux-hardware.org/?probe=37f7cabb58) | Mar 07, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [fd8c378fda](https://linux-hardware.org/?probe=fd8c378fda) | Mar 07, 2023 |
| ASUSTek       | X556UAK                     | Notebook    | [51f2084195](https://linux-hardware.org/?probe=51f2084195) | Mar 06, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [745898b5de](https://linux-hardware.org/?probe=745898b5de) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [ad0dbd5503](https://linux-hardware.org/?probe=ad0dbd5503) | Mar 06, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [256a8abb58](https://linux-hardware.org/?probe=256a8abb58) | Mar 06, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [0f36c1b0f7](https://linux-hardware.org/?probe=0f36c1b0f7) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [dbe64de6bd](https://linux-hardware.org/?probe=dbe64de6bd) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [20fbc926fd](https://linux-hardware.org/?probe=20fbc926fd) | Mar 06, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [02dfdb807e](https://linux-hardware.org/?probe=02dfdb807e) | Mar 06, 2023 |
| HP            | G72                         | Notebook    | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Microtech     | ebookPro                    | Notebook    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| ASRock        | G31M-S                      | Desktop     | [69f88597a5](https://linux-hardware.org/?probe=69f88597a5) | Mar 05, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [88e6308c0a](https://linux-hardware.org/?probe=88e6308c0a) | Mar 05, 2023 |
| AZW           | U59                         | Desktop     | [7711289a77](https://linux-hardware.org/?probe=7711289a77) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [109fa85017](https://linux-hardware.org/?probe=109fa85017) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [0d99cfc372](https://linux-hardware.org/?probe=0d99cfc372) | Mar 05, 2023 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [4fbc244180](https://linux-hardware.org/?probe=4fbc244180) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [f8eea076e5](https://linux-hardware.org/?probe=f8eea076e5) | Mar 05, 2023 |
| HP            | 3397                        | Desktop     | [5250af801f](https://linux-hardware.org/?probe=5250af801f) | Mar 04, 2023 |
| HP            | 2B45 0100                   | All in one  | [2694ad74f3](https://linux-hardware.org/?probe=2694ad74f3) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Toshiba       | NB550D                      | Notebook    | [8ba5171640](https://linux-hardware.org/?probe=8ba5171640) | Mar 04, 2023 |
| HP            | G72                         | Notebook    | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [99008935e9](https://linux-hardware.org/?probe=99008935e9) | Mar 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [4816618219](https://linux-hardware.org/?probe=4816618219) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [3c681075fb](https://linux-hardware.org/?probe=3c681075fb) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| HP            | ENVY 15                     | Notebook    | [9ceefd9a22](https://linux-hardware.org/?probe=9ceefd9a22) | Mar 03, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [17f1328add](https://linux-hardware.org/?probe=17f1328add) | Mar 03, 2023 |
| HP            | ENVY dv6                    | Notebook    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [860f53436b](https://linux-hardware.org/?probe=860f53436b) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f791caa732](https://linux-hardware.org/?probe=f791caa732) | Mar 03, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [7e85150e30](https://linux-hardware.org/?probe=7e85150e30) | Mar 03, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [0b39498d52](https://linux-hardware.org/?probe=0b39498d52) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [bdfb7a4647](https://linux-hardware.org/?probe=bdfb7a4647) | Mar 03, 2023 |
| GMK           | NucBox2                     | Notebook    | [84af5a7d53](https://linux-hardware.org/?probe=84af5a7d53) | Mar 02, 2023 |
| AMI           | Intel                       | Desktop     | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [c34c6d8786](https://linux-hardware.org/?probe=c34c6d8786) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2a1515aaa3](https://linux-hardware.org/?probe=2a1515aaa3) | Mar 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [16875fc443](https://linux-hardware.org/?probe=16875fc443) | Mar 02, 2023 |
| Acer          | TravelMate P253             | Notebook    | [aa56b7749c](https://linux-hardware.org/?probe=aa56b7749c) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [c1594b1f9d](https://linux-hardware.org/?probe=c1594b1f9d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | Notebook    | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [14a44a0392](https://linux-hardware.org/?probe=14a44a0392) | Mar 02, 2023 |
| Acer          | FIH57                       | Desktop     | [3f9c79675c](https://linux-hardware.org/?probe=3f9c79675c) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [98e86d41d1](https://linux-hardware.org/?probe=98e86d41d1) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [61fe88e268](https://linux-hardware.org/?probe=61fe88e268) | Mar 01, 2023 |
| HP            | 3396                        | Desktop     | [2da0f889cb](https://linux-hardware.org/?probe=2da0f889cb) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [78f570552a](https://linux-hardware.org/?probe=78f570552a) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4e701d495f](https://linux-hardware.org/?probe=4e701d495f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db5b346bd5](https://linux-hardware.org/?probe=db5b346bd5) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [6f1de5f17c](https://linux-hardware.org/?probe=6f1de5f17c) | Feb 28, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [b518eb9925](https://linux-hardware.org/?probe=b518eb9925) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | Notebook    | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [34b5806bcf](https://linux-hardware.org/?probe=34b5806bcf) | Feb 28, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [051b66987e](https://linux-hardware.org/?probe=051b66987e) | Feb 27, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [a52b94c2d5](https://linux-hardware.org/?probe=a52b94c2d5) | Feb 27, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [64496d4ab7](https://linux-hardware.org/?probe=64496d4ab7) | Feb 27, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | TravelMate B113             | Notebook    | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [580db05e08](https://linux-hardware.org/?probe=580db05e08) | Feb 27, 2023 |
| Olimex        | A20-OLinuXino-LIME          | Soc         | [bcb9e7b9e7](https://linux-hardware.org/?probe=bcb9e7b9e7) | Feb 26, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [7923f1dc21](https://linux-hardware.org/?probe=7923f1dc21) | Feb 26, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [310a65baea](https://linux-hardware.org/?probe=310a65baea) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [2cea6ee649](https://linux-hardware.org/?probe=2cea6ee649) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [8bca0d4eb5](https://linux-hardware.org/?probe=8bca0d4eb5) | Feb 26, 2023 |
| Timi          | TM1612                      | Notebook    | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [aaa112feae](https://linux-hardware.org/?probe=aaa112feae) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [bde9736ffd](https://linux-hardware.org/?probe=bde9736ffd) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [84750f9d96](https://linux-hardware.org/?probe=84750f9d96) | Feb 25, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [e5f0a23afd](https://linux-hardware.org/?probe=e5f0a23afd) | Feb 25, 2023 |
| Quanta        | XV1                         | All in one  | [fa596130ae](https://linux-hardware.org/?probe=fa596130ae) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| HP            | 250 G3                      | Notebook    | [6a3d2238ba](https://linux-hardware.org/?probe=6a3d2238ba) | Feb 25, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [de180bd339](https://linux-hardware.org/?probe=de180bd339) | Feb 25, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [fd75fdb59f](https://linux-hardware.org/?probe=fd75fdb59f) | Feb 25, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [3f2e38e322](https://linux-hardware.org/?probe=3f2e38e322) | Feb 25, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [bfd1042a82](https://linux-hardware.org/?probe=bfd1042a82) | Feb 25, 2023 |
| ASUSTek       | X556URK                     | Notebook    | [fc80e01794](https://linux-hardware.org/?probe=fc80e01794) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [e1c05e0782](https://linux-hardware.org/?probe=e1c05e0782) | Feb 25, 2023 |
| HP            | ENVY 17                     | Notebook    | [08db7a8be2](https://linux-hardware.org/?probe=08db7a8be2) | Feb 25, 2023 |
| HP            | ENVY 17                     | Notebook    | [0ad15a7e01](https://linux-hardware.org/?probe=0ad15a7e01) | Feb 25, 2023 |
| Unknown       | 1.0                         | Desktop     | [69594c956a](https://linux-hardware.org/?probe=69594c956a) | Feb 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d8b9174fba](https://linux-hardware.org/?probe=d8b9174fba) | Feb 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [c6f84d1224](https://linux-hardware.org/?probe=c6f84d1224) | Feb 24, 2023 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [f24e6a55c4](https://linux-hardware.org/?probe=f24e6a55c4) | Feb 24, 2023 |
| Unknown       | 1.0                         | Desktop     | [bab30a1ac1](https://linux-hardware.org/?probe=bab30a1ac1) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK U749               | Notebook    | [ba7cdc6018](https://linux-hardware.org/?probe=ba7cdc6018) | Feb 24, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [502020fe52](https://linux-hardware.org/?probe=502020fe52) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [075081e4ad](https://linux-hardware.org/?probe=075081e4ad) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [4ed48d952c](https://linux-hardware.org/?probe=4ed48d952c) | Feb 24, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [874cbd6e13](https://linux-hardware.org/?probe=874cbd6e13) | Feb 24, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [6bf574175a](https://linux-hardware.org/?probe=6bf574175a) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [4526585d29](https://linux-hardware.org/?probe=4526585d29) | Feb 24, 2023 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [fdcb637c97](https://linux-hardware.org/?probe=fdcb637c97) | Feb 24, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| MSI           | X58 Pro                     | Desktop     | [22509b3e42](https://linux-hardware.org/?probe=22509b3e42) | Feb 23, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a8fbcbec0e](https://linux-hardware.org/?probe=a8fbcbec0e) | Feb 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [cddc383ff9](https://linux-hardware.org/?probe=cddc383ff9) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d93c7d5661](https://linux-hardware.org/?probe=d93c7d5661) | Feb 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7cdbd101a4](https://linux-hardware.org/?probe=7cdbd101a4) | Feb 23, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [771b90caaa](https://linux-hardware.org/?probe=771b90caaa) | Feb 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dbbcb7502c](https://linux-hardware.org/?probe=dbbcb7502c) | Feb 23, 2023 |
| Dell          | Latitude 5530               | Notebook    | [d620cdcce0](https://linux-hardware.org/?probe=d620cdcce0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| ASUSTek       | LEONITE                     | Desktop     | [2739b3325c](https://linux-hardware.org/?probe=2739b3325c) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| Dell          | Latitude 7300               | Notebook    | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| ASUSTek       | P5QL-E                      | Desktop     | [52c9ec67bf](https://linux-hardware.org/?probe=52c9ec67bf) | Feb 23, 2023 |
| Acer          | TravelMate P253             | Notebook    | [b99414b6de](https://linux-hardware.org/?probe=b99414b6de) | Feb 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c76844f9a1](https://linux-hardware.org/?probe=c76844f9a1) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | Notebook    | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| ASRock        | B660M Pro RS                | Desktop     | [13560ab66d](https://linux-hardware.org/?probe=13560ab66d) | Feb 22, 2023 |
| MSI           | MS-B1831                    | Mini pc     | [10e5b9530c](https://linux-hardware.org/?probe=10e5b9530c) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [99d4f0df73](https://linux-hardware.org/?probe=99d4f0df73) | Feb 22, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [71928c5a75](https://linux-hardware.org/?probe=71928c5a75) | Feb 22, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [2993295e62](https://linux-hardware.org/?probe=2993295e62) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [57e007d035](https://linux-hardware.org/?probe=57e007d035) | Feb 22, 2023 |
| HP            | ENVY 17                     | Notebook    | [f705060f1e](https://linux-hardware.org/?probe=f705060f1e) | Feb 22, 2023 |
| HP            | ENVY 17                     | Notebook    | [bf86e7904b](https://linux-hardware.org/?probe=bf86e7904b) | Feb 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [05f20bac2d](https://linux-hardware.org/?probe=05f20bac2d) | Feb 21, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [c23f2f53ed](https://linux-hardware.org/?probe=c23f2f53ed) | Feb 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d6ec8781f4](https://linux-hardware.org/?probe=d6ec8781f4) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| HP            | 85A2                        | All in one  | [c9f6d95fb2](https://linux-hardware.org/?probe=c9f6d95fb2) | Feb 21, 2023 |
| BESSTAR Te... | X400                        | Notebook    | [f7f9004058](https://linux-hardware.org/?probe=f7f9004058) | Feb 21, 2023 |
| Teclast       | F7                          | Notebook    | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| Acer          | FIH57                       | Desktop     | [294e04e054](https://linux-hardware.org/?probe=294e04e054) | Feb 21, 2023 |
| VXL           | M6V90AI-VL                  | Desktop     | [935d6b4b24](https://linux-hardware.org/?probe=935d6b4b24) | Feb 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [46d473b3e5](https://linux-hardware.org/?probe=46d473b3e5) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | Notebook    | [3a525ce932](https://linux-hardware.org/?probe=3a525ce932) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | Notebook    | [f845d181ec](https://linux-hardware.org/?probe=f845d181ec) | Feb 20, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [d81ff5358a](https://linux-hardware.org/?probe=d81ff5358a) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [656629ffba](https://linux-hardware.org/?probe=656629ffba) | Feb 20, 2023 |
| ASUSTek       | H170-PRO                    | Desktop     | [011dc701c1](https://linux-hardware.org/?probe=011dc701c1) | Feb 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e434f7f85a](https://linux-hardware.org/?probe=e434f7f85a) | Feb 20, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [796ba78b54](https://linux-hardware.org/?probe=796ba78b54) | Feb 20, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [accbe9322f](https://linux-hardware.org/?probe=accbe9322f) | Feb 20, 2023 |
| Packard Be... | IMEDIA S3810                | Desktop     | [472db03bf8](https://linux-hardware.org/?probe=472db03bf8) | Feb 20, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [ec529ac1bd](https://linux-hardware.org/?probe=ec529ac1bd) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [6f456ca669](https://linux-hardware.org/?probe=6f456ca669) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [72891de86c](https://linux-hardware.org/?probe=72891de86c) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | Notebook    | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [a6fd2ffc5b](https://linux-hardware.org/?probe=a6fd2ffc5b) | Feb 20, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [86f16da5e8](https://linux-hardware.org/?probe=86f16da5e8) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [51d702d217](https://linux-hardware.org/?probe=51d702d217) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2af589c6e9](https://linux-hardware.org/?probe=2af589c6e9) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [1489b9779a](https://linux-hardware.org/?probe=1489b9779a) | Feb 19, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [616e689b13](https://linux-hardware.org/?probe=616e689b13) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [84e519800c](https://linux-hardware.org/?probe=84e519800c) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [2ffc7c4a96](https://linux-hardware.org/?probe=2ffc7c4a96) | Feb 19, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [2c98b99901](https://linux-hardware.org/?probe=2c98b99901) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [1104c148d1](https://linux-hardware.org/?probe=1104c148d1) | Feb 19, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [537c2d1b64](https://linux-hardware.org/?probe=537c2d1b64) | Feb 18, 2023 |
| Dell          | Latitude 5480               | Notebook    | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [eb9f3822a0](https://linux-hardware.org/?probe=eb9f3822a0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | Desktop     | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [105ea39c82](https://linux-hardware.org/?probe=105ea39c82) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [cadd20aaff](https://linux-hardware.org/?probe=cadd20aaff) | Feb 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [355838f8b2](https://linux-hardware.org/?probe=355838f8b2) | Feb 18, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [27dcbbe1d7](https://linux-hardware.org/?probe=27dcbbe1d7) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [01a17523fa](https://linux-hardware.org/?probe=01a17523fa) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [6b59c75dec](https://linux-hardware.org/?probe=6b59c75dec) | Feb 18, 2023 |
| Jumper        | EZbook                      | Notebook    | [35f7c6a28a](https://linux-hardware.org/?probe=35f7c6a28a) | Feb 18, 2023 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [0428793835](https://linux-hardware.org/?probe=0428793835) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [7360e6e667](https://linux-hardware.org/?probe=7360e6e667) | Feb 17, 2023 |
| Dell          | Latitude E6440              | Notebook    | [96e9e43a2e](https://linux-hardware.org/?probe=96e9e43a2e) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [b29933336d](https://linux-hardware.org/?probe=b29933336d) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [d97ee3d7d1](https://linux-hardware.org/?probe=d97ee3d7d1) | Feb 17, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [7a47fab9f3](https://linux-hardware.org/?probe=7a47fab9f3) | Feb 17, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [e84edd71e7](https://linux-hardware.org/?probe=e84edd71e7) | Feb 17, 2023 |
| ASUSTek       | Rampage Formula             | Desktop     | [61fd1aefee](https://linux-hardware.org/?probe=61fd1aefee) | Feb 17, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [f8dca6a264](https://linux-hardware.org/?probe=f8dca6a264) | Feb 17, 2023 |
| HP            | Pavilion 15                 | Notebook    | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [f8b182d99b](https://linux-hardware.org/?probe=f8b182d99b) | Feb 17, 2023 |
| HP            | 2820h                       | Desktop     | [552bdc9930](https://linux-hardware.org/?probe=552bdc9930) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [85fd62f731](https://linux-hardware.org/?probe=85fd62f731) | Feb 17, 2023 |
| Jumper        | EZbook                      | Notebook    | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | Notebook    | [7d6dcd9cd1](https://linux-hardware.org/?probe=7d6dcd9cd1) | Feb 16, 2023 |
| BESSTAR Te... | VB9                         | All in one  | [deb1c6d3c8](https://linux-hardware.org/?probe=deb1c6d3c8) | Feb 16, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [4b6268364f](https://linux-hardware.org/?probe=4b6268364f) | Feb 16, 2023 |
| HP            | 1495                        | Desktop     | [6bc4b54027](https://linux-hardware.org/?probe=6bc4b54027) | Feb 16, 2023 |
| MSI           | Z97-G45 GAMING              | Desktop     | [c6a7d3a755](https://linux-hardware.org/?probe=c6a7d3a755) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [5f59be48e1](https://linux-hardware.org/?probe=5f59be48e1) | Feb 16, 2023 |
| Quanta        | XV1                         | All in one  | [6c4ea36dc2](https://linux-hardware.org/?probe=6c4ea36dc2) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [68effccd60](https://linux-hardware.org/?probe=68effccd60) | Feb 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| ASRock        | Q1900M                      | Desktop     | [2fc7d5968a](https://linux-hardware.org/?probe=2fc7d5968a) | Feb 16, 2023 |
| ASUSTek       | P5K                         | Desktop     | [7767ce777f](https://linux-hardware.org/?probe=7767ce777f) | Feb 16, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [fcf01071e5](https://linux-hardware.org/?probe=fcf01071e5) | Feb 15, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [7a58ceb644](https://linux-hardware.org/?probe=7a58ceb644) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | Notebook    | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Google        | Grunt                       | Notebook    | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [56ee76d678](https://linux-hardware.org/?probe=56ee76d678) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [1f8387dde4](https://linux-hardware.org/?probe=1f8387dde4) | Feb 15, 2023 |
| Acer          | Veriton X2610G              | Desktop     | [22c65bbb88](https://linux-hardware.org/?probe=22c65bbb88) | Feb 15, 2023 |
| ASUSTek       | F6A                         | Notebook    | [3660446fe5](https://linux-hardware.org/?probe=3660446fe5) | Feb 15, 2023 |
| Supermicro    | X10DRG-Q                    | Desktop     | [5af331bc84](https://linux-hardware.org/?probe=5af331bc84) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [28ac8fee12](https://linux-hardware.org/?probe=28ac8fee12) | Feb 14, 2023 |
| HP            | 3396                        | Desktop     | [fbff77d7cc](https://linux-hardware.org/?probe=fbff77d7cc) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4b0331863e](https://linux-hardware.org/?probe=4b0331863e) | Feb 14, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [49f47896e6](https://linux-hardware.org/?probe=49f47896e6) | Feb 14, 2023 |
| Acer          | Aspire 7250G                | Notebook    | [5f5cec8261](https://linux-hardware.org/?probe=5f5cec8261) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| HP            | 18E7                        | Desktop     | [b81cc64550](https://linux-hardware.org/?probe=b81cc64550) | Feb 14, 2023 |
| HP            | ENVY 17                     | Notebook    | [d07a7a99de](https://linux-hardware.org/?probe=d07a7a99de) | Feb 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| Acer          | Swift SF114-33              | Notebook    | [14cd72be0e](https://linux-hardware.org/?probe=14cd72be0e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [23a611650b](https://linux-hardware.org/?probe=23a611650b) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6fe888ea28](https://linux-hardware.org/?probe=6fe888ea28) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| HP            | ENVY 15                     | Notebook    | [efc0c8427a](https://linux-hardware.org/?probe=efc0c8427a) | Feb 12, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [6dfaa1ed56](https://linux-hardware.org/?probe=6dfaa1ed56) | Feb 12, 2023 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [01ab687841](https://linux-hardware.org/?probe=01ab687841) | Feb 12, 2023 |
| Lenovo        | ThinkPad L460 20FVS25H01    | Notebook    | [37383d8798](https://linux-hardware.org/?probe=37383d8798) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c798855263](https://linux-hardware.org/?probe=c798855263) | Feb 12, 2023 |
| HP            | Compaq 6720s                | Notebook    | [4b8e0e10e0](https://linux-hardware.org/?probe=4b8e0e10e0) | Feb 12, 2023 |
| HP            | Compaq 6720s                | Notebook    | [a23186bb63](https://linux-hardware.org/?probe=a23186bb63) | Feb 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | Notebook    | [404cac8b60](https://linux-hardware.org/?probe=404cac8b60) | Feb 11, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [8291db193a](https://linux-hardware.org/?probe=8291db193a) | Feb 11, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [86ca7a4821](https://linux-hardware.org/?probe=86ca7a4821) | Feb 11, 2023 |
| HP            | 3031h                       | Desktop     | [f9a0848388](https://linux-hardware.org/?probe=f9a0848388) | Feb 11, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [dec32b9b60](https://linux-hardware.org/?probe=dec32b9b60) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [f0dff8ed53](https://linux-hardware.org/?probe=f0dff8ed53) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | Desktop     | [6ada8eb627](https://linux-hardware.org/?probe=6ada8eb627) | Feb 10, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [a82372e461](https://linux-hardware.org/?probe=a82372e461) | Feb 10, 2023 |
| HP            | Notebook                    | Notebook    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [9b9b84473b](https://linux-hardware.org/?probe=9b9b84473b) | Feb 10, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [21a8928972](https://linux-hardware.org/?probe=21a8928972) | Feb 10, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [bd09c6036f](https://linux-hardware.org/?probe=bd09c6036f) | Feb 10, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5a876c1bb0](https://linux-hardware.org/?probe=5a876c1bb0) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | Desktop     | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | Notebook    | [7f4c6d1757](https://linux-hardware.org/?probe=7f4c6d1757) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| HP            | 255 G4                      | Notebook    | [00870a3da9](https://linux-hardware.org/?probe=00870a3da9) | Feb 09, 2023 |
| HP            | 843C                        | Desktop     | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| MSI           | 2A9C                        | Desktop     | [1332640fbd](https://linux-hardware.org/?probe=1332640fbd) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [08f3d3b7d8](https://linux-hardware.org/?probe=08f3d3b7d8) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [0cb6963914](https://linux-hardware.org/?probe=0cb6963914) | Feb 09, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [d32909e1a4](https://linux-hardware.org/?probe=d32909e1a4) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [69c30e6f7b](https://linux-hardware.org/?probe=69c30e6f7b) | Feb 08, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Google        | Grunt                       | Notebook    | [84ecb8aaf1](https://linux-hardware.org/?probe=84ecb8aaf1) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | Desktop     | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [641ce1347d](https://linux-hardware.org/?probe=641ce1347d) | Feb 08, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [faadf8b29c](https://linux-hardware.org/?probe=faadf8b29c) | Feb 08, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [5e951ad06d](https://linux-hardware.org/?probe=5e951ad06d) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [0713732442](https://linux-hardware.org/?probe=0713732442) | Feb 07, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [de25a58c23](https://linux-hardware.org/?probe=de25a58c23) | Feb 07, 2023 |
| Google        | Grunt                       | Notebook    | [1bbc4ae776](https://linux-hardware.org/?probe=1bbc4ae776) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2347G7G       | Notebook    | [925017105d](https://linux-hardware.org/?probe=925017105d) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [b7ab00ddb1](https://linux-hardware.org/?probe=b7ab00ddb1) | Feb 07, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [cc856dafad](https://linux-hardware.org/?probe=cc856dafad) | Feb 07, 2023 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [9a94af0f8a](https://linux-hardware.org/?probe=9a94af0f8a) | Feb 07, 2023 |
| MSI           | U90/U100                    | Notebook    | [f7dc915782](https://linux-hardware.org/?probe=f7dc915782) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | X550JF                      | Notebook    | [c8f1b71cfd](https://linux-hardware.org/?probe=c8f1b71cfd) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0edeee4ba6](https://linux-hardware.org/?probe=0edeee4ba6) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| Acer          | Extensa 5635                | Notebook    | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [762c097b3e](https://linux-hardware.org/?probe=762c097b3e) | Feb 06, 2023 |
| Intel         | Unknown                     | Notebook    | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [8a1998f130](https://linux-hardware.org/?probe=8a1998f130) | Feb 05, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [00006691a6](https://linux-hardware.org/?probe=00006691a6) | Feb 05, 2023 |
| Dell          | Latitude 7380               | Notebook    | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| ASUSTek       | N55SF                       | Notebook    | [5b81cbed5f](https://linux-hardware.org/?probe=5b81cbed5f) | Feb 05, 2023 |
| Acer          | One S1002                   | Notebook    | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| Acer          | WG43M                       | Desktop     | [e463181f54](https://linux-hardware.org/?probe=e463181f54) | Feb 05, 2023 |
| MSI           | MS-7309                     | Desktop     | [46995d58eb](https://linux-hardware.org/?probe=46995d58eb) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| Intel         | DH55TC AAE70932-301         | Desktop     | [350458a94e](https://linux-hardware.org/?probe=350458a94e) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [ea72001991](https://linux-hardware.org/?probe=ea72001991) | Feb 05, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [945a366595](https://linux-hardware.org/?probe=945a366595) | Feb 05, 2023 |
| HP            | 255 G3                      | Notebook    | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [b7760210a8](https://linux-hardware.org/?probe=b7760210a8) | Feb 05, 2023 |
| Notebook      | W25CSW                      | Notebook    | [b63184cd07](https://linux-hardware.org/?probe=b63184cd07) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | Notebook    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| Acer          | TravelMate P253             | Notebook    | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [944149e350](https://linux-hardware.org/?probe=944149e350) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | Notebook    | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Microtech     | CoreBook                    | Notebook    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [91a070c2aa](https://linux-hardware.org/?probe=91a070c2aa) | Feb 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7581d83856](https://linux-hardware.org/?probe=7581d83856) | Feb 03, 2023 |
| Intel         | H61                         | Desktop     | [21fd40e0a1](https://linux-hardware.org/?probe=21fd40e0a1) | Feb 03, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dc4a285d49](https://linux-hardware.org/?probe=dc4a285d49) | Feb 03, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [9274080d89](https://linux-hardware.org/?probe=9274080d89) | Feb 03, 2023 |
| ASUSTek       | P5GDC                       | Desktop     | [6dbac14e8b](https://linux-hardware.org/?probe=6dbac14e8b) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| Quanta        | XV1                         | All in one  | [8904f5e7fa](https://linux-hardware.org/?probe=8904f5e7fa) | Feb 03, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [0759c30dd9](https://linux-hardware.org/?probe=0759c30dd9) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [fd8c9d9ccf](https://linux-hardware.org/?probe=fd8c9d9ccf) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| HP            | 834F                        | Desktop     | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8c8021c54c](https://linux-hardware.org/?probe=8c8021c54c) | Feb 02, 2023 |
| Intel         | Unknown                     | Notebook    | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1ca0a608f9](https://linux-hardware.org/?probe=1ca0a608f9) | Feb 02, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a0b5d1c73c](https://linux-hardware.org/?probe=a0b5d1c73c) | Feb 02, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [28e1975b51](https://linux-hardware.org/?probe=28e1975b51) | Feb 02, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [09430385c6](https://linux-hardware.org/?probe=09430385c6) | Feb 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0a3273841f](https://linux-hardware.org/?probe=0a3273841f) | Feb 02, 2023 |
| ASUSTek       | K54L                        | Notebook    | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [f86eaa6db8](https://linux-hardware.org/?probe=f86eaa6db8) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [19a2c05804](https://linux-hardware.org/?probe=19a2c05804) | Feb 02, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4b6904f9b1](https://linux-hardware.org/?probe=4b6904f9b1) | Feb 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [b792043acd](https://linux-hardware.org/?probe=b792043acd) | Feb 01, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a8a3f37ad8](https://linux-hardware.org/?probe=a8a3f37ad8) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [48bccd4f38](https://linux-hardware.org/?probe=48bccd4f38) | Feb 01, 2023 |
| Pegatron      | 2A94                        | Desktop     | [58961a542f](https://linux-hardware.org/?probe=58961a542f) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [92f6e450b8](https://linux-hardware.org/?probe=92f6e450b8) | Jan 31, 2023 |
| HP            | ENVY 15                     | Notebook    | [c688eb85bb](https://linux-hardware.org/?probe=c688eb85bb) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [f4e30fc177](https://linux-hardware.org/?probe=f4e30fc177) | Jan 31, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [77cc2bd640](https://linux-hardware.org/?probe=77cc2bd640) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [656bb989e7](https://linux-hardware.org/?probe=656bb989e7) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [8e8ae85d60](https://linux-hardware.org/?probe=8e8ae85d60) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [0d254e85dd](https://linux-hardware.org/?probe=0d254e85dd) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [3c8b3f4e7d](https://linux-hardware.org/?probe=3c8b3f4e7d) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [3bdb934f29](https://linux-hardware.org/?probe=3bdb934f29) | Jan 30, 2023 |
| Dell          | Precision 3560              | Notebook    | [3d5432deef](https://linux-hardware.org/?probe=3d5432deef) | Jan 30, 2023 |
| Dell          | Precision 3560              | Notebook    | [c250c935bd](https://linux-hardware.org/?probe=c250c935bd) | Jan 30, 2023 |
| Dell          | Precision 3571              | Notebook    | [55f371f4ef](https://linux-hardware.org/?probe=55f371f4ef) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | Notebook    | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Intel         | B75                         | Desktop     | [6597bed6da](https://linux-hardware.org/?probe=6597bed6da) | Jan 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e5f6f546d4](https://linux-hardware.org/?probe=e5f6f546d4) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [8200b57a5b](https://linux-hardware.org/?probe=8200b57a5b) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [7af163f694](https://linux-hardware.org/?probe=7af163f694) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | Notebook    | [3ac195a476](https://linux-hardware.org/?probe=3ac195a476) | Jan 29, 2023 |
| MSI           | P55-CD53                    | Desktop     | [7c46f17179](https://linux-hardware.org/?probe=7c46f17179) | Jan 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e91c24c3f9](https://linux-hardware.org/?probe=e91c24c3f9) | Jan 29, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [f8ef554d85](https://linux-hardware.org/?probe=f8ef554d85) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [615e9f22e4](https://linux-hardware.org/?probe=615e9f22e4) | Jan 29, 2023 |
| ASRock        | H610M-HVS                   | Desktop     | [2774d547be](https://linux-hardware.org/?probe=2774d547be) | Jan 29, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [37c0fb77f5](https://linux-hardware.org/?probe=37c0fb77f5) | Jan 29, 2023 |
| ASUSTek       | F2A55-M LK2                 | Desktop     | [8bf2fa8d9b](https://linux-hardware.org/?probe=8bf2fa8d9b) | Jan 28, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [890cad48c3](https://linux-hardware.org/?probe=890cad48c3) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [5ea763da5f](https://linux-hardware.org/?probe=5ea763da5f) | Jan 28, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [17a8246044](https://linux-hardware.org/?probe=17a8246044) | Jan 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8f6ea9ffff](https://linux-hardware.org/?probe=8f6ea9ffff) | Jan 28, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [bbe5b30c42](https://linux-hardware.org/?probe=bbe5b30c42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [73b3f84699](https://linux-hardware.org/?probe=73b3f84699) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [292892acd3](https://linux-hardware.org/?probe=292892acd3) | Jan 28, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [312e07a824](https://linux-hardware.org/?probe=312e07a824) | Jan 28, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | Notebook    | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [23a84c76b8](https://linux-hardware.org/?probe=23a84c76b8) | Jan 27, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [4bf7b18ab1](https://linux-hardware.org/?probe=4bf7b18ab1) | Jan 27, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6f449734a9](https://linux-hardware.org/?probe=6f449734a9) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [01e47b07a8](https://linux-hardware.org/?probe=01e47b07a8) | Jan 26, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [4ae098906f](https://linux-hardware.org/?probe=4ae098906f) | Jan 26, 2023 |
| Toshiba       | Satellite Pro C50-A-1FD     | Notebook    | [7f7198cdcb](https://linux-hardware.org/?probe=7f7198cdcb) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [759ae65214](https://linux-hardware.org/?probe=759ae65214) | Jan 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8128876a22](https://linux-hardware.org/?probe=8128876a22) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [027f04536c](https://linux-hardware.org/?probe=027f04536c) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [bea1d8a9ce](https://linux-hardware.org/?probe=bea1d8a9ce) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [596316a81c](https://linux-hardware.org/?probe=596316a81c) | Jan 25, 2023 |
| ASUSTek       | B150M-A/M.2                 | Desktop     | [edb16eafc7](https://linux-hardware.org/?probe=edb16eafc7) | Jan 25, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [28c31b639b](https://linux-hardware.org/?probe=28c31b639b) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | Notebook    | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [3e1520340a](https://linux-hardware.org/?probe=3e1520340a) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [7b93d7477b](https://linux-hardware.org/?probe=7b93d7477b) | Jan 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [25c4dbbe9c](https://linux-hardware.org/?probe=25c4dbbe9c) | Jan 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 900       | 11.9%   |
| Ubuntu 18.04        | 559       | 7.39%   |
| Ubuntu 22.04        | 401       | 5.3%    |
| OpenMandriva 4.2    | 218       | 2.88%   |
| Arch Rolling        | 204       | 2.7%    |
| OpenMandriva 4.3    | 188       | 2.49%   |
| Debian 11           | 188       | 2.49%   |
| Fedora 36           | 148       | 1.96%   |
| Ubuntu 20.10        | 129       | 1.71%   |
| Arch                | 123       | 1.63%   |
| Ubuntu 22.10        | 121       | 1.6%    |
| Ubuntu 19.10        | 120       | 1.59%   |
| Linux Mint 21.1     | 110       | 1.45%   |
| Ubuntu 19.04        | 108       | 1.43%   |
| Xubuntu 18.04       | 107       | 1.41%   |
| Xubuntu 20.04       | 102       | 1.35%   |
| Pop!_OS 22.04       | 102       | 1.35%   |
| KDE neon 20.04      | 102       | 1.35%   |
| Linux Mint 20.3     | 99        | 1.31%   |
| Zorin 16            | 98        | 1.3%    |
| Ubuntu 21.10        | 96        | 1.27%   |
| Fedora 37           | 96        | 1.27%   |
| OpenMandriva 23.01  | 88        | 1.16%   |
| Linux Mint 21       | 87        | 1.15%   |
| Ubuntu 21.04        | 83        | 1.1%    |
| Debian 10           | 81        | 1.07%   |
| EndeavourOS Rolling | 72        | 0.95%   |
| Zorin 15            | 69        | 0.91%   |
| Ubuntu 18.10        | 68        | 0.9%    |
| Fedora 35           | 68        | 0.9%    |
| Linux Mint 19.3     | 66        | 0.87%   |
| Kubuntu 20.04       | 66        | 0.87%   |
| Manjaro             | 65        | 0.86%   |
| ROSA R10            | 62        | 0.82%   |
| OpenMandriva 23.03  | 62        | 0.82%   |
| Linux Mint 20.1     | 60        | 0.79%   |
| Kubuntu 22.04       | 60        | 0.79%   |
| Linux Mint 20.2     | 59        | 0.78%   |
| Linux Mint 20       | 58        | 0.77%   |
| Pop!_OS 20.10       | 57        | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2494      | 34.89%  |
| OpenMandriva  | 588       | 8.23%   |
| Linux Mint    | 547       | 7.65%   |
| Fedora        | 459       | 6.42%   |
| Debian        | 337       | 4.71%   |
| Arch          | 320       | 4.48%   |
| Xubuntu       | 296       | 4.14%   |
| Pop!_OS       | 252       | 3.53%   |
| Manjaro       | 211       | 2.95%   |
| Kubuntu       | 199       | 2.78%   |
| ROSA          | 184       | 2.57%   |
| Zorin         | 177       | 2.48%   |
| KDE neon      | 142       | 1.99%   |
| Lubuntu       | 93        | 1.3%    |
| EndeavourOS   | 78        | 1.09%   |
| Ubuntu MATE   | 73        | 1.02%   |
| openSUSE      | 73        | 1.02%   |
| Elementary    | 59        | 0.83%   |
| Endless       | 48        | 0.67%   |
| Ubuntu Unity  | 41        | 0.57%   |
| Clear Linux   | 38        | 0.53%   |
| BlackPanther  | 35        | 0.49%   |
| ArcoLinux     | 33        | 0.46%   |
| Gentoo        | 32        | 0.45%   |
| MX            | 31        | 0.43%   |
| LMDE          | 31        | 0.43%   |
| Kali          | 25        | 0.35%   |
| Ubuntu Budgie | 22        | 0.31%   |
| Peppermint    | 20        | 0.28%   |
| Garuda Linux  | 20        | 0.28%   |
| SteamOS       | 12        | 0.17%   |
| Nobara        | 12        | 0.17%   |
| LinuxFX       | 12        | 0.17%   |
| Parrot        | 11        | 0.15%   |
| Ubuntu Studio | 10        | 0.14%   |
| Slackware     | 8         | 0.11%   |
| Q4OS          | 8         | 0.11%   |
| CentOS        | 8         | 0.11%   |
| Raspbian      | 7         | 0.1%    |
| NixOS         | 7         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 211       | 2.52%   |
| 5.16.7-desktop-1omv4003  | 180       | 2.15%   |
| 5.15.0-52-generic        | 166       | 1.98%   |
| 5.4.0-42-generic         | 125       | 1.49%   |
| 5.15.0-56-generic        | 117       | 1.4%    |
| 5.4.0-52-generic         | 81        | 0.97%   |
| 6.1.1-desktop-1omv2290   | 73        | 0.87%   |
| 5.15.0-58-generic        | 73        | 0.87%   |
| 5.15.0-47-generic        | 71        | 0.85%   |
| 5.4.0-26-generic         | 66        | 0.79%   |
| 5.3.0-46-generic         | 66        | 0.79%   |
| 5.15.0-46-generic        | 65        | 0.78%   |
| 6.2.6-desktop-1omv2390   | 60        | 0.72%   |
| 5.4.0-58-generic         | 60        | 0.72%   |
| 5.4.0-29-generic         | 59        | 0.7%    |
| 5.3.0-40-generic         | 58        | 0.69%   |
| 5.4.0-48-generic         | 56        | 0.67%   |
| 5.15.0-43-generic        | 53        | 0.63%   |
| 5.3.0-42-generic         | 48        | 0.57%   |
| 5.4.0-54-generic         | 46        | 0.55%   |
| 5.10.0-19-amd64          | 42        | 0.5%    |
| 5.19.0-23-generic        | 41        | 0.49%   |
| 5.15.0-53-generic        | 41        | 0.49%   |
| 6.0.2-arch1-1            | 40        | 0.48%   |
| 5.4.0-28-generic         | 40        | 0.48%   |
| 5.19.0-35-generic        | 40        | 0.48%   |
| 5.15.0-60-generic        | 40        | 0.48%   |
| 5.0.0-37-generic         | 39        | 0.47%   |
| 5.4.0-56-generic         | 38        | 0.45%   |
| 5.4.0-37-generic         | 38        | 0.45%   |
| 5.4.0-33-generic         | 38        | 0.45%   |
| 5.15.0-41-generic        | 38        | 0.45%   |
| 5.4.0-47-generic         | 37        | 0.44%   |
| 5.15.0-48-generic        | 37        | 0.44%   |
| 5.11.0-38-generic        | 37        | 0.44%   |
| 5.4.0-40-generic         | 35        | 0.42%   |
| 5.13.0-28-generic        | 35        | 0.42%   |
| 5.15.0-50-generic        | 34        | 0.41%   |
| 5.13.0-39-generic        | 33        | 0.39%   |
| 5.10.0-21-amd64          | 33        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1255      | 16.04%  |
| 5.15.0  | 804       | 10.28%  |
| 4.15.0  | 468       | 5.98%   |
| 5.8.0   | 394       | 5.04%   |
| 5.3.0   | 384       | 4.91%   |
| 5.11.0  | 308       | 3.94%   |
| 5.13.0  | 299       | 3.82%   |
| 5.19.0  | 297       | 3.8%    |
| 5.0.0   | 224       | 2.86%   |
| 5.10.0  | 223       | 2.85%   |
| 5.10.14 | 212       | 2.71%   |
| 5.16.7  | 183       | 2.34%   |
| 4.18.0  | 158       | 2.02%   |
| 6.1.1   | 86        | 1.1%    |
| 6.0.2   | 83        | 1.06%   |
| 4.19.0  | 78        | 1%      |
| 6.2.6   | 75        | 0.96%   |
| 5.19.16 | 47        | 0.6%    |
| 6.0.0   | 36        | 0.46%   |
| 4.9.60  | 36        | 0.46%   |
| 4.9.20  | 36        | 0.46%   |
| 6.0.6   | 35        | 0.45%   |
| 6.0.12  | 34        | 0.43%   |
| 4.18.16 | 34        | 0.43%   |
| 5.17.5  | 32        | 0.41%   |
| 5.19.6  | 28        | 0.36%   |
| 4.4.0   | 28        | 0.36%   |
| 6.0.7   | 26        | 0.33%   |
| 6.1.0   | 25        | 0.32%   |
| 6.0.10  | 24        | 0.31%   |
| 6.0.5   | 21        | 0.27%   |
| 5.16.11 | 20        | 0.26%   |
| 6.0.9   | 19        | 0.24%   |
| 5.17.1  | 19        | 0.24%   |
| 6.1.8   | 18        | 0.23%   |
| 5.12.4  | 18        | 0.23%   |
| 5.18.0  | 17        | 0.22%   |
| 6.1.4   | 16        | 0.2%    |
| 5.19.4  | 16        | 0.2%    |
| 5.17.0  | 16        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1335      | 17.29%  |
| 5.15    | 969       | 12.55%  |
| 5.10    | 530       | 6.86%   |
| 5.19    | 483       | 6.25%   |
| 4.15    | 470       | 6.09%   |
| 5.8     | 464       | 6.01%   |
| 5.3     | 414       | 5.36%   |
| 5.11    | 370       | 4.79%   |
| 5.13    | 332       | 4.3%    |
| 6.0     | 326       | 4.22%   |
| 5.16    | 275       | 3.56%   |
| 6.1     | 235       | 3.04%   |
| 5.0     | 232       | 3%      |
| 4.18    | 199       | 2.58%   |
| 6.2     | 166       | 2.15%   |
| 4.9     | 124       | 1.61%   |
| 5.17    | 106       | 1.37%   |
| 4.19    | 103       | 1.33%   |
| 5.18    | 97        | 1.26%   |
| 5.9     | 82        | 1.06%   |
| 5.14    | 76        | 0.98%   |
| 5.6     | 64        | 0.83%   |
| 5.12    | 62        | 0.8%    |
| 5.7     | 50        | 0.65%   |
| 5.5     | 47        | 0.61%   |
| 4.4     | 30        | 0.39%   |
| 4.1     | 16        | 0.21%   |
| 5.2     | 13        | 0.17%   |
| 4.13    | 12        | 0.16%   |
| 5.1     | 7         | 0.09%   |
| 4.20    | 5         | 0.06%   |
| 4.17    | 5         | 0.06%   |
| 4.12    | 5         | 0.06%   |
| 4.14    | 4         | 0.05%   |
| 3.10    | 3         | 0.04%   |
| 4.16    | 2         | 0.03%   |
| 4.10    | 2         | 0.03%   |
| 6.3     | 1         | 0.01%   |
| 4.8     | 1         | 0.01%   |
| 4.7     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6540      | 94.74%  |
| i686    | 317       | 4.59%   |
| aarch64 | 35        | 0.51%   |
| armv7l  | 11        | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3044      | 42.22%  |
| KDE5              | 1369      | 18.99%  |
| Unknown           | 825       | 11.44%  |
| XFCE              | 596       | 8.27%   |
| X-Cinnamon        | 446       | 6.19%   |
| MATE              | 199       | 2.76%   |
| KDE               | 140       | 1.94%   |
| LXQt              | 111       | 1.54%   |
| KDE4              | 108       | 1.5%    |
| Pantheon          | 58        | 0.8%    |
| Cinnamon          | 51        | 0.71%   |
| LXDE              | 48        | 0.67%   |
| Unity             | 43        | 0.6%    |
| Budgie            | 32        | 0.44%   |
| GNOME Flashback   | 28        | 0.39%   |
| i3                | 21        | 0.29%   |
| GNOME Classic     | 13        | 0.18%   |
| Deepin            | 11        | 0.15%   |
| Hyprland          | 10        | 0.14%   |
| sway              | 9         | 0.12%   |
| Openbox           | 9         | 0.12%   |
| bspwm             | 6         | 0.08%   |
| Trinity           | 5         | 0.07%   |
| lightdm-xsession  | 5         | 0.07%   |
| DWM               | 4         | 0.06%   |
| xubuntu           | 2         | 0.03%   |
| qtile             | 2         | 0.03%   |
| icewm             | 2         | 0.03%   |
| Enlightenment     | 2         | 0.03%   |
| ubuntu:pika:GNOME | 1         | 0.01%   |
| ubuntu            | 1         | 0.01%   |
| pika:GNOME        | 1         | 0.01%   |
| none+i3           | 1         | 0.01%   |
| none+bspwm        | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| herbstluftwm      | 1         | 0.01%   |
| gamescope         | 1         | 0.01%   |
| FVWM              | 1         | 0.01%   |
| Cutefish          | 1         | 0.01%   |
| awesome           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5446      | 76.45%  |
| Wayland | 1151      | 16.16%  |
| Unknown | 424       | 5.95%   |
| Tty     | 103       | 1.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3291      | 45.7%   |
| SDDM    | 1290      | 17.91%  |
| GDM3    | 825       | 11.46%  |
| GDM     | 783       | 10.87%  |
| LightDM | 701       | 9.73%   |
| TDM     | 169       | 2.35%   |
| KDM     | 111       | 1.54%   |
| XDM     | 13        | 0.18%   |
| SLiM    | 6         | 0.08%   |
| LXDM    | 4         | 0.06%   |
| GREETD  | 3         | 0.04%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| SLIMSKI | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| it_IT        | 4399      | 62.01%  |
| en_US        | 1437      | 20.26%  |
| Unknown      | 858       | 12.09%  |
| en_GB        | 151       | 2.13%   |
| C            | 124       | 1.75%   |
| de_DE        | 22        | 0.31%   |
| fr_FR        | 15        | 0.21%   |
| es_ES        | 11        | 0.16%   |
| de_IT        | 10        | 0.14%   |
| ru_RU        | 8         | 0.11%   |
| it_CH        | 8         | 0.11%   |
| POSIX        | 7         | 0.1%    |
| en_IE        | 6         | 0.08%   |
| en_AG        | 5         | 0.07%   |
| de_AT        | 4         | 0.06%   |
| it_IT@euro   | 3         | 0.04%   |
| en_AU        | 3         | 0.04%   |
| en_US.UTF8   | 2         | 0.03%   |
| sc_IT        | 1         | 0.01%   |
| ro_RO        | 1         | 0.01%   |
| pt_BR        | 1         | 0.01%   |
| pl_PL        | 1         | 0.01%   |
| it_ITutf8    | 1         | 0.01%   |
| it_IT.UTF -8 | 1         | 0.01%   |
| it           | 1         | 0.01%   |
| hu_HU        | 1         | 0.01%   |
| fur_IT       | 1         | 0.01%   |
| fr_CH        | 1         | 0.01%   |
| fr_BE        | 1         | 0.01%   |
| es_US        | 1         | 0.01%   |
| es_MX        | 1         | 0.01%   |
| en_US@euro   | 1         | 0.01%   |
| en_US.utf-8  | 1         | 0.01%   |
| en_US.ASCII  | 1         | 0.01%   |
| en_IN        | 1         | 0.01%   |
| de_CH        | 1         | 0.01%   |
| Default      | 1         | 0.01%   |
| C.UTF8       | 1         | 0.01%   |
| bg_BG        | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3646      | 51.72%  |
| EFI  | 3404      | 48.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5400      | 76.39%  |
| Overlay  | 715       | 10.11%  |
| Btrfs    | 541       | 7.65%   |
| Unknown  | 230       | 3.25%   |
| Xfs      | 67        | 0.95%   |
| Zfs      | 37        | 0.52%   |
| Tmpfs    | 24        | 0.34%   |
| Ext2     | 18        | 0.25%   |
| Ext3     | 16        | 0.23%   |
| F2fs     | 13        | 0.18%   |
| Aufs     | 3         | 0.04%   |
| XXX4     | 2         | 0.03%   |
| XXXX     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3541      | 49.93%  |
| GPT     | 2711      | 38.23%  |
| MBR     | 840       | 11.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5927      | 84.2%   |
| Yes       | 1112      | 15.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4465      | 63.3%   |
| Yes       | 2589      | 36.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1453      | 21.07%  |
| Hewlett-Packard         | 1165      | 16.89%  |
| Lenovo                  | 794       | 11.51%  |
| Acer                    | 560       | 8.12%   |
| Dell                    | 553       | 8.02%   |
| MSI                     | 388       | 5.63%   |
| ASRock                  | 317       | 4.6%    |
| Gigabyte Technology     | 242       | 3.51%   |
| Apple                   | 147       | 2.13%   |
| Intel                   | 104       | 1.51%   |
| Toshiba                 | 102       | 1.48%   |
| HUAWEI                  | 93        | 1.35%   |
| Sony                    | 91        | 1.32%   |
| Fujitsu                 | 75        | 1.09%   |
| Samsung Electronics     | 71        | 1.03%   |
| Unknown                 | 69        | 1%      |
| Packard Bell            | 56        | 0.81%   |
| Pegatron                | 42        | 0.61%   |
| Raspberry Pi Foundation | 33        | 0.48%   |
| Fujitsu Siemens         | 30        | 0.44%   |
| Chuwi                   | 29        | 0.42%   |
| Mediacom                | 27        | 0.39%   |
| Teclast                 | 26        | 0.38%   |
| AMI                     | 24        | 0.35%   |
| Microsoft               | 23        | 0.33%   |
| Foxconn                 | 22        | 0.32%   |
| Notebook                | 21        | 0.3%    |
| Timi                    | 18        | 0.26%   |
| Microtech               | 17        | 0.25%   |
| BESSTAR Tech            | 17        | 0.25%   |
| TUXEDO                  | 13        | 0.19%   |
| Supermicro              | 12        | 0.17%   |
| PC Specialist           | 12        | 0.17%   |
| AZW                     | 12        | 0.17%   |
| Valve                   | 9         | 0.13%   |
| eMachines               | 9         | 0.13%   |
| TrekStor                | 8         | 0.12%   |
| SANTECH                 | 8         | 0.12%   |
| Google                  | 8         | 0.12%   |
| Biostar                 | 8         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 86        | 1.25%   |
| ASUS All Series                       | 73        | 1.06%   |
| HP Pavilion dv6                       | 52        | 0.75%   |
| HP Notebook                           | 38        | 0.55%   |
| HP Pavilion 15                        | 26        | 0.38%   |
| HP Pavilion g6                        | 22        | 0.32%   |
| HP 255 G8 Notebook PC                 | 19        | 0.28%   |
| HUAWEI NBLK-WAX9X                     | 17        | 0.25%   |
| ASUS PRIME A320M-K                    | 17        | 0.25%   |
| HP 15                                 | 15        | 0.22%   |
| Dell OptiPlex 7010                    | 15        | 0.22%   |
| MSI MS-7C37                           | 14        | 0.2%    |
| MSI MS-7C56                           | 13        | 0.19%   |
| MSI MS-7B86                           | 13        | 0.19%   |
| Dell XPS 15 7590                      | 13        | 0.19%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 12        | 0.17%   |
| HP Pavilion x2 Detachable             | 12        | 0.17%   |
| HP G62                                | 12        | 0.17%   |
| HP 255 G7 Notebook PC                 | 12        | 0.17%   |
| HP 250 G6 Notebook PC                 | 12        | 0.17%   |
| Apple MacBook4,1                      | 12        | 0.17%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 11        | 0.16%   |
| HUAWEI KLVL-WXX9                      | 11        | 0.16%   |
| HP ENVY 15                            | 11        | 0.16%   |
| HP 255 G6 Notebook PC                 | 11        | 0.16%   |
| ASUS T101HA                           | 11        | 0.16%   |
| RPi Raspberry Pi                      | 10        | 0.15%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 10        | 0.15%   |
| HP Compaq Elite 8300 SFF              | 10        | 0.15%   |
| AMI Intel                             | 10        | 0.15%   |
| Valve Jupiter                         | 9         | 0.13%   |
| MSI MS-7B79                           | 9         | 0.13%   |
| HP Pavilion dv7                       | 9         | 0.13%   |
| HP Laptop 15s-eq2xxx                  | 9         | 0.13%   |
| HP Compaq 6730s                       | 9         | 0.13%   |
| Gigabyte B450M DS3H                   | 9         | 0.13%   |
| Dell XPS 15 9570                      | 9         | 0.13%   |
| Dell XPS 15 9560                      | 9         | 0.13%   |
| Dell Inspiron 5570                    | 9         | 0.13%   |
| ASUS TUF Gaming X570-PLUS             | 9         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 352       | 5.1%    |
| Lenovo ThinkPad       | 322       | 4.67%   |
| HP Pavilion           | 268       | 3.89%   |
| Lenovo IdeaPad        | 157       | 2.28%   |
| Dell Latitude         | 157       | 2.28%   |
| HP Compaq             | 151       | 2.19%   |
| ASUS PRIME            | 116       | 1.68%   |
| HP EliteBook          | 110       | 1.6%    |
| Dell XPS              | 100       | 1.45%   |
| ASUS VivoBook         | 98        | 1.42%   |
| Dell Inspiron         | 93        | 1.35%   |
| Toshiba Satellite     | 88        | 1.28%   |
| Unknown               | 86        | 1.25%   |
| HP ProBook            | 85        | 1.23%   |
| HP Laptop             | 84        | 1.22%   |
| Dell OptiPlex         | 78        | 1.13%   |
| ASUS All              | 73        | 1.06%   |
| ASUS ROG              | 69        | 1%      |
| ASUS TUF              | 58        | 0.84%   |
| HP 255                | 57        | 0.83%   |
| Lenovo ThinkCentre    | 52        | 0.75%   |
| HP 250                | 52        | 0.75%   |
| Dell Precision        | 52        | 0.75%   |
| HP Notebook           | 38        | 0.55%   |
| Fujitsu LIFEBOOK      | 38        | 0.55%   |
| Dell Vostro           | 38        | 0.55%   |
| Acer TravelMate       | 36        | 0.52%   |
| Acer Swift            | 36        | 0.52%   |
| Acer Extensa          | 36        | 0.52%   |
| HP ENVY               | 35        | 0.51%   |
| Acer Veriton          | 34        | 0.49%   |
| RPi Raspberry         | 33        | 0.48%   |
| Fujitsu ESPRIMO       | 31        | 0.45%   |
| Lenovo Yoga           | 30        | 0.44%   |
| Lenovo ThinkBook      | 30        | 0.44%   |
| Packard Bell EasyNote | 23        | 0.33%   |
| Microsoft Surface     | 23        | 0.33%   |
| HP ProDesk            | 21        | 0.3%    |
| ASUS P8H61-M          | 20        | 0.29%   |
| Packard Bell IMEDIA   | 18        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 596       | 8.64%   |
| 2019    | 568       | 8.24%   |
| 2020    | 554       | 8.03%   |
| 2013    | 478       | 6.93%   |
| 2012    | 449       | 6.51%   |
| 2017    | 445       | 6.45%   |
| 2021    | 426       | 6.18%   |
| 2011    | 419       | 6.08%   |
| 2008    | 411       | 5.96%   |
| 2014    | 391       | 5.67%   |
| 2009    | 390       | 5.66%   |
| 2010    | 383       | 5.55%   |
| 2016    | 369       | 5.35%   |
| 2015    | 369       | 5.35%   |
| 2007    | 244       | 3.54%   |
| 2022    | 138       | 2%      |
| 2006    | 135       | 1.96%   |
| 2005    | 65        | 0.94%   |
| Unknown | 42        | 0.61%   |
| 2004    | 14        | 0.2%    |
| 2003    | 5         | 0.07%   |
| 2023    | 2         | 0.03%   |
| 2001    | 2         | 0.03%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3879      | 56.25%  |
| Desktop        | 2530      | 36.69%  |
| Convertible    | 150       | 2.18%   |
| Mini pc        | 98        | 1.42%   |
| All in one     | 93        | 1.35%   |
| Tablet         | 83        | 1.2%    |
| System on chip | 44        | 0.64%   |
| Server         | 18        | 0.26%   |
| Phone          | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6443      | 92.69%  |
| Enabled  | 508       | 7.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6880      | 99.77%  |
| Yes  | 16        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1663      | 23.78%  |
| 3.01-4.0        | 1597      | 22.84%  |
| 16.01-24.0      | 1257      | 17.98%  |
| 8.01-16.0       | 1220      | 17.45%  |
| 32.01-64.0      | 451       | 6.45%   |
| 1.01-2.0        | 421       | 6.02%   |
| 2.01-3.0        | 130       | 1.86%   |
| 64.01-256.0     | 90        | 1.29%   |
| 0.51-1.0        | 77        | 1.1%    |
| 24.01-32.0      | 74        | 1.06%   |
| 0.01-0.5        | 7         | 0.1%    |
| More than 256.0 | 5         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3011      | 39.34%  |
| 2.01-3.0   | 1858      | 24.28%  |
| 4.01-8.0   | 910       | 11.89%  |
| 3.01-4.0   | 872       | 11.39%  |
| 0.51-1.0   | 654       | 8.55%   |
| 8.01-16.0  | 220       | 2.87%   |
| 0.01-0.5   | 95        | 1.24%   |
| 16.01-24.0 | 21        | 0.27%   |
| 24.01-32.0 | 8         | 0.1%    |
| Unknown    | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4310      | 60.86%  |
| 2       | 1765      | 24.92%  |
| 3       | 526       | 7.43%   |
| 4       | 226       | 3.19%   |
| 5       | 104       | 1.47%   |
| 0       | 63        | 0.89%   |
| 6       | 45        | 0.64%   |
| 7       | 18        | 0.25%   |
| 8       | 12        | 0.17%   |
| 10      | 4         | 0.06%   |
| 12      | 3         | 0.04%   |
| 9       | 3         | 0.04%   |
| Unknown | 2         | 0.03%   |
| 13      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3647      | 52.5%   |
| Yes       | 3300      | 47.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5888      | 85.07%  |
| No        | 1033      | 14.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5286      | 76.24%  |
| No        | 1647      | 23.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3901      | 55.71%  |
| No        | 3101      | 44.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 6896      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 958       | 12.26%  |
| Rome                | 807       | 10.33%  |
| Turin               | 252       | 3.22%   |
| Bologna             | 167       | 2.14%   |
| Naples              | 150       | 1.92%   |
| Florence            | 139       | 1.78%   |
| Genoa               | 115       | 1.47%   |
| Rho                 | 102       | 1.31%   |
| Padova              | 91        | 1.16%   |
| Palermo             | 85        | 1.09%   |
| Verona              | 77        | 0.99%   |
| Catania             | 60        | 0.77%   |
| Milano              | 59        | 0.76%   |
| Bari                | 57        | 0.73%   |
| Brescia             | 56        | 0.72%   |
| Trieste             | 53        | 0.68%   |
| Bergamo             | 48        | 0.61%   |
| Venice              | 44        | 0.56%   |
| Parma               | 44        | 0.56%   |
| Modena              | 38        | 0.49%   |
| Pisa                | 36        | 0.46%   |
| Pescara             | 35        | 0.45%   |
| Trento              | 34        | 0.44%   |
| Sesto San Giovanni  | 34        | 0.44%   |
| Reggio Emilia       | 34        | 0.44%   |
| Casalecchio di Reno | 34        | 0.44%   |
| Cagliari            | 33        | 0.42%   |
| Monza               | 32        | 0.41%   |
| Bolzano             | 32        | 0.41%   |
| Perugia             | 30        | 0.38%   |
| Taranto             | 26        | 0.33%   |
| Udine               | 23        | 0.29%   |
| Mestre              | 23        | 0.29%   |
| Seregno             | 22        | 0.28%   |
| Reggio Calabria     | 22        | 0.28%   |
| Como                | 22        | 0.28%   |
| Vicenza             | 21        | 0.27%   |
| Salerno             | 20        | 0.26%   |
| Forlì              | 20        | 0.26%   |
| Legnano             | 19        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1617      | 2303   | 16.25%  |
| Seagate                     | 1422      | 2157   | 14.29%  |
| WDC                         | 1366      | 2070   | 13.73%  |
| Kingston                    | 645       | 847    | 6.48%   |
| Toshiba                     | 593       | 819    | 5.96%   |
| Crucial                     | 579       | 723    | 5.82%   |
| SanDisk                     | 495       | 671    | 4.97%   |
| Unknown                     | 476       | 649    | 4.78%   |
| Hitachi                     | 387       | 495    | 3.89%   |
| SK hynix                    | 219       | 264    | 2.2%    |
| HGST                        | 206       | 277    | 2.07%   |
| Maxtor                      | 184       | 248    | 1.85%   |
| Micron Technology           | 156       | 192    | 1.57%   |
| Intel                       | 150       | 198    | 1.51%   |
| Phison                      | 104       | 143    | 1.05%   |
| China                       | 81        | 90     | 0.81%   |
| KIOXIA                      | 69        | 92     | 0.69%   |
| SPCC                        | 60        | 74     | 0.6%    |
| Fujitsu                     | 53        | 62     | 0.53%   |
| Intenso                     | 50        | 61     | 0.5%    |
| Apple                       | 48        | 60     | 0.48%   |
| Transcend                   | 47        | 60     | 0.47%   |
| A-DATA Technology           | 40        | 55     | 0.4%    |
| Micron/Crucial Technology   | 39        | 53     | 0.39%   |
| Corsair                     | 37        | 54     | 0.37%   |
| Phison Electronics          | 34        | 40     | 0.34%   |
| KingDian                    | 33        | 39     | 0.33%   |
| JMicron Technology          | 33        | 37     | 0.33%   |
| PNY                         | 32        | 40     | 0.32%   |
| LITEON                      | 31        | 39     | 0.31%   |
| Silicon Motion              | 26        | 36     | 0.26%   |
| OCZ                         | 25        | 30     | 0.25%   |
| Netac                       | 25        | 27     | 0.25%   |
| Patriot                     | 24        | 32     | 0.24%   |
| Unknown                     | 24        | 30     | 0.24%   |
| Drevo                       | 22        | 24     | 0.22%   |
| Teclast                     | 21        | 27     | 0.21%   |
| SABRENT                     | 20        | 20     | 0.2%    |
| Kingston Technology Company | 20        | 25     | 0.2%    |
| ASMT                        | 18        | 21     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 176       | 1.62%   |
| Samsung SSD 860 EVO 500GB                         | 141       | 1.3%    |
| Crucial CT500MX500SSD1 500GB                      | 136       | 1.25%   |
| Samsung SSD 850 EVO 250GB                         | 122       | 1.12%   |
| Seagate ST500DM002-1BD142 500GB                   | 108       | 0.99%   |
| Unknown MMC Card  32GB                            | 88        | 0.81%   |
| Samsung SSD 850 EVO 500GB                         | 88        | 0.81%   |
| Kingston SA400S37480G 480GB SSD                   | 87        | 0.8%    |
| Crucial CT240BX500SSD1 240GB                      | 72        | 0.66%   |
| Unknown MMC Card  64GB                            | 70        | 0.64%   |
| Toshiba MQ01ABF050 500GB                          | 70        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                    | 69        | 0.63%   |
| Samsung SSD 860 EVO 250GB                         | 69        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 63        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 60        | 0.55%   |
| Toshiba DT01ACA100 1TB                            | 58        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                   | 58        | 0.53%   |
| Crucial CT480BX500SSD1 480GB                      | 55        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                       | 55        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                   | 53        | 0.49%   |
| HGST HTS545050A7E680 500GB                        | 53        | 0.49%   |
| Seagate ST1000LM035-1RK172 970GB                  | 52        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                    | 51        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                  | 49        | 0.45%   |
| Seagate ST3500418AS 500GB                         | 48        | 0.44%   |
| HGST HTS721010A9E630 1TB                          | 48        | 0.44%   |
| Seagate M3 Portable 4TB                           | 46        | 0.42%   |
| SanDisk SSD PLUS 240GB                            | 45        | 0.41%   |
| Samsung SSD 840 EVO 250GB                         | 43        | 0.39%   |
| Samsung NVMe SSD Drive 512GB                      | 43        | 0.39%   |
| Seagate ST9500325AS 500GB                         | 41        | 0.38%   |
| Samsung SSD 860 EVO 1TB                           | 41        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 40        | 0.37%   |
| Phison Sabrent 1TB                                | 40        | 0.37%   |
| Unknown SD/MMC/MS PRO 249GB                       | 39        | 0.36%   |
| Seagate Expansion 4TB                             | 39        | 0.36%   |
| Toshiba MQ01ABD100 1TB                            | 38        | 0.35%   |
| Seagate ST31000528AS 1TB                          | 38        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                    | 38        | 0.35%   |
| Unknown MMC Card  128GB                           | 36        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1378      | 2077   | 34%     |
| WDC                 | 1145      | 1745   | 28.25%  |
| Toshiba             | 437       | 601    | 10.78%  |
| Hitachi             | 387       | 495    | 9.55%   |
| HGST                | 205       | 276    | 5.06%   |
| Maxtor              | 182       | 246    | 4.49%   |
| Samsung Electronics | 138       | 174    | 3.4%    |
| Fujitsu             | 53        | 62     | 1.31%   |
| Unknown             | 52        | 62     | 1.28%   |
| JMicron Technology  | 15        | 17     | 0.37%   |
| Apple               | 13        | 15     | 0.32%   |
| ASMT                | 8         | 8      | 0.2%    |
| USB3.0              | 5         | 6      | 0.12%   |
| HGST HTS            | 5         | 5      | 0.12%   |
| IBM/Hitachi         | 4         | 5      | 0.1%    |
| Inateck             | 3         | 3      | 0.07%   |
| WD MediaMax         | 2         | 2      | 0.05%   |
| Intenso             | 2         | 4      | 0.05%   |
| Hewlett-Packard     | 2         | 3      | 0.05%   |
| ASMT109x            | 2         | 2      | 0.05%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| USB                 | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| Promise             | 1         | 1      | 0.02%   |
| PI-041              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| IBM-ESXS            | 1         | 2      | 0.02%   |
| IBM-207x            | 1         | 4      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| FC-1307             | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| Config              | 1         | 1      | 0.02%   |
| China               | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 911       | 1252   | 26.79%  |
| Kingston            | 548       | 722    | 16.12%  |
| Crucial             | 521       | 653    | 15.32%  |
| SanDisk             | 306       | 418    | 9%      |
| WDC                 | 116       | 158    | 3.41%   |
| China               | 79        | 88     | 2.32%   |
| Micron Technology   | 69        | 85     | 2.03%   |
| Toshiba             | 54        | 75     | 1.59%   |
| SPCC                | 50        | 61     | 1.47%   |
| SK hynix            | 49        | 57     | 1.44%   |
| Transcend           | 44        | 57     | 1.29%   |
| Intenso             | 43        | 51     | 1.26%   |
| Intel               | 36        | 49     | 1.06%   |
| KingDian            | 32        | 38     | 0.94%   |
| A-DATA Technology   | 32        | 45     | 0.94%   |
| Corsair             | 31        | 46     | 0.91%   |
| PNY                 | 30        | 37     | 0.88%   |
| Apple               | 29        | 31     | 0.85%   |
| LITEON              | 27        | 31     | 0.79%   |
| Patriot             | 24        | 32     | 0.71%   |
| OCZ                 | 24        | 29     | 0.71%   |
| Teclast             | 21        | 27     | 0.62%   |
| Netac               | 21        | 22     | 0.62%   |
| Drevo               | 17        | 18     | 0.5%    |
| LITEONIT            | 16        | 27     | 0.47%   |
| GOODRAM             | 16        | 23     | 0.47%   |
| Dogfish             | 16        | 20     | 0.47%   |
| TCSUNBOW            | 13        | 14     | 0.38%   |
| Team                | 11        | 18     | 0.32%   |
| Unknown             | 11        | 17     | 0.32%   |
| Verbatim            | 10        | 15     | 0.29%   |
| Unknown             | 10        | 11     | 0.29%   |
| FORESEE             | 10        | 12     | 0.29%   |
| External            | 10        | 11     | 0.29%   |
| ASMT                | 9         | 12     | 0.26%   |
| TO Exter            | 8         | 8      | 0.24%   |
| KingSpec            | 8         | 10     | 0.24%   |
| BAITITON            | 8         | 10     | 0.24%   |
| Microtech           | 7         | 17     | 0.21%   |
| Fanxiang            | 6         | 6      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3426      | 5833   | 38.42%  |
| SSD     | 3034      | 4459   | 34.02%  |
| NVMe    | 1847      | 2618   | 20.71%  |
| MMC     | 438       | 613    | 4.91%   |
| Unknown | 172       | 217    | 1.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5282      | 10033  | 66.56%  |
| NVMe | 1835      | 2589   | 23.12%  |
| MMC  | 438       | 613    | 5.52%   |
| SAS  | 381       | 505    | 4.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4348      | 6850   | 66.23%  |
| 0.51-1.0   | 1566      | 2321   | 23.85%  |
| 1.01-2.0   | 359       | 607    | 5.47%   |
| 3.01-4.0   | 134       | 223    | 2.04%   |
| 2.01-3.0   | 98        | 167    | 1.49%   |
| 4.01-10.0  | 48        | 107    | 0.73%   |
| 10.01-20.0 | 12        | 17     | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2008      | 27.36%  |
| 251-500        | 1610      | 21.93%  |
| 501-1000       | 865       | 11.78%  |
| 1-20           | 721       | 9.82%   |
| 51-100         | 590       | 8.04%   |
| 1001-2000      | 512       | 6.98%   |
| 21-50          | 355       | 4.84%   |
| More than 3000 | 263       | 3.58%   |
| 2001-3000      | 216       | 2.94%   |
| Unknown        | 200       | 2.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3149      | 41.4%   |
| 21-50          | 1159      | 15.24%  |
| 101-250        | 920       | 12.09%  |
| 51-100         | 848       | 11.15%  |
| 251-500        | 559       | 7.35%   |
| 501-1000       | 395       | 5.19%   |
| Unknown        | 200       | 2.63%   |
| 1001-2000      | 197       | 2.59%   |
| More than 3000 | 104       | 1.37%   |
| 2001-3000      | 76        | 1%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 18        | 20     | 2.83%   |
| HGST HTS545050A7E680 500GB                     | 16        | 18     | 2.52%   |
| Seagate ST9500325AS 500GB                      | 10        | 10     | 1.57%   |
| Seagate ST3500418AS 500GB                      | 10        | 14     | 1.57%   |
| Seagate ST1000LM035-1RK172 970GB               | 8         | 10     | 1.26%   |
| Maxtor STM3250310AS 250GB                      | 8         | 8      | 1.26%   |
| Hitachi HTS725050A9A364 500GB                  | 8         | 8      | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 7         | 9      | 1.1%    |
| Toshiba MQ01ABF050 500GB                       | 6         | 6      | 0.94%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 6      | 0.94%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 0.79%   |
| SanDisk SSD PLUS 480GB                         | 5         | 6      | 0.79%   |
| Maxtor STM3320820AS 320GB                      | 5         | 5      | 0.79%   |
| HGST HTS725050A7E630 500GB                     | 5         | 6      | 0.79%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 4         | 4      | 0.63%   |
| WDC WD40EFRX-68N32N0 4TB                       | 4         | 5      | 0.63%   |
| Unknown MM0500EANCR 500GB                      | 4         | 9      | 0.63%   |
| Toshiba MK5065GSX 500GB                        | 4         | 4      | 0.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 4         | 6      | 0.63%   |
| Seagate ST31500341AS 1TB                       | 4         | 4      | 0.63%   |
| Seagate ST31000528AS 1TB                       | 4         | 7      | 0.63%   |
| Kingston SA400S37240G 240GB SSD                | 4         | 4      | 0.63%   |
| Hitachi HTS545050A7E380 500GB                  | 4         | 4      | 0.63%   |
| Hitachi HTS543232A7A384 320GB                  | 4         | 5      | 0.63%   |
| WDC WD20EFRX-68EUZN0 2TB                       | 3         | 4      | 0.47%   |
| WDC WD10EZEX-60WN4A0 1TB                       | 3         | 4      | 0.47%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 0.47%   |
| Toshiba DT01ACA100 1TB                         | 3         | 3      | 0.47%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 0.47%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.47%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 0.47%   |
| Seagate ST3500413AS 500GB                      | 3         | 5      | 0.47%   |
| Seagate ST3500320AS 500GB                      | 3         | 3      | 0.47%   |
| Seagate ST3250310AS 250GB                      | 3         | 3      | 0.47%   |
| Seagate ST2000DM001-1ER164 2TB                 | 3         | 7      | 0.47%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 3      | 0.47%   |
| Samsung Electronics SSD 970 EVO 1TB            | 3         | 3      | 0.47%   |
| Samsung Electronics SSD 860 EVO 500GB          | 3         | 4      | 0.47%   |
| Samsung Electronics HD103UJ 1TB                | 3         | 3      | 0.47%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 3         | 3      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 169       | 218    | 27.3%   |
| WDC                         | 120       | 147    | 19.39%  |
| Hitachi                     | 71        | 75     | 11.47%  |
| Toshiba                     | 44        | 45     | 7.11%   |
| Maxtor                      | 38        | 42     | 6.14%   |
| Samsung Electronics         | 36        | 40     | 5.82%   |
| HGST                        | 32        | 39     | 5.17%   |
| Kingston                    | 16        | 16     | 2.58%   |
| Crucial                     | 15        | 15     | 2.42%   |
| SK hynix                    | 10        | 12     | 1.62%   |
| SanDisk                     | 10        | 11     | 1.62%   |
| Micron Technology           | 9         | 9      | 1.45%   |
| Unknown                     | 5         | 10     | 0.81%   |
| Intel                       | 5         | 8      | 0.81%   |
| Fujitsu                     | 5         | 5      | 0.81%   |
| OCZ                         | 3         | 3      | 0.48%   |
| Drevo                       | 3         | 3      | 0.48%   |
| ASMT                        | 3         | 3      | 0.48%   |
| TCSUNBOW                    | 2         | 2      | 0.32%   |
| Intenso                     | 2         | 3      | 0.32%   |
| Corsair                     | 2         | 3      | 0.32%   |
| BAITITON                    | 2         | 4      | 0.32%   |
| Yangtze Memory Technologies | 1         | 1      | 0.16%   |
| WINTEC                      | 1         | 1      | 0.16%   |
| WDC WDS2                    | 1         | 1      | 0.16%   |
| WD MediaMax                 | 1         | 1      | 0.16%   |
| USB3.0                      | 1         | 1      | 0.16%   |
| Transcend                   | 1         | 2      | 0.16%   |
| Teclast                     | 1         | 1      | 0.16%   |
| SSSTC                       | 1         | 1      | 0.16%   |
| NGFF                        | 1         | 1      | 0.16%   |
| LITEONIT                    | 1         | 1      | 0.16%   |
| LITEON                      | 1         | 1      | 0.16%   |
| KingSpec                    | 1         | 1      | 0.16%   |
| KingDian                    | 1         | 1      | 0.16%   |
| GSemi                       | 1         | 1      | 0.16%   |
| CT1000P1                    | 1         | 2      | 0.16%   |
| Apacer                      | 1         | 1      | 0.16%   |
| A-DATA Technology           | 1         | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 169       | 218    | 33.6%   |
| WDC                 | 117       | 141    | 23.26%  |
| Hitachi             | 71        | 75     | 14.12%  |
| Toshiba             | 42        | 43     | 8.35%   |
| Maxtor              | 38        | 42     | 7.55%   |
| HGST                | 32        | 39     | 6.36%   |
| Samsung Electronics | 20        | 22     | 3.98%   |
| Unknown             | 5         | 10     | 0.99%   |
| Fujitsu             | 5         | 5      | 0.99%   |
| ASMT                | 2         | 2      | 0.4%    |
| WD MediaMax         | 1         | 1      | 0.2%    |
| USB3.0              | 1         | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 473       | 599    | 80.17%  |
| SSD  | 103       | 114    | 17.46%  |
| NVMe | 14        | 19     | 2.37%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                        | 2         | 4      | 13.33%  |
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 13.33%  |
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 6.67%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 6.67%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 6.67%   |
| Seagate STM3250318AS 250GB                       | 1         | 1      | 6.67%   |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS543216L9A300 160GB                    | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 9      | 40%     |
| WDC                 | 4         | 4      | 26.67%  |
| Hitachi             | 3         | 3      | 20%     |
| Toshiba             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4139      | 8103   | 55.14%  |
| Works    | 2777      | 4887   | 36.99%  |
| Malfunc  | 576       | 732    | 7.67%   |
| Failed   | 15        | 18     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4656      | 55.32%  |
| AMD                              | 1149      | 13.65%  |
| Samsung Electronics              | 683       | 8.12%   |
| SanDisk                          | 275       | 3.27%   |
| Nvidia                           | 180       | 2.14%   |
| SK hynix                         | 158       | 1.88%   |
| Phison Electronics               | 146       | 1.73%   |
| JMicron Technology               | 134       | 1.59%   |
| ASMedia Technology               | 131       | 1.56%   |
| Marvell Technology Group         | 125       | 1.49%   |
| Kingston Technology Company      | 121       | 1.44%   |
| Toshiba America Info Systems     | 106       | 1.26%   |
| Micron/Crucial Technology        | 96        | 1.14%   |
| Micron Technology                | 92        | 1.09%   |
| KIOXIA                           | 78        | 0.93%   |
| VIA Technologies                 | 55        | 0.65%   |
| Silicon Motion                   | 37        | 0.44%   |
| Silicon Integrated Systems [SiS] | 32        | 0.38%   |
| ADATA Technology                 | 19        | 0.23%   |
| Adaptec                          | 15        | 0.18%   |
| Union Memory (Shenzhen)          | 14        | 0.17%   |
| Solid State Storage Technology   | 13        | 0.15%   |
| Silicon Image                    | 12        | 0.14%   |
| Broadcom / LSI                   | 9         | 0.11%   |
| Apple                            | 9         | 0.11%   |
| LSI Logic / Symbios Logic        | 8         | 0.1%    |
| Realtek Semiconductor            | 7         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.08%   |
| Lite-On Technology               | 7         | 0.08%   |
| Lenovo                           | 7         | 0.08%   |
| Seagate Technology               | 5         | 0.06%   |
| Shenzhen Longsys Electronics     | 4         | 0.05%   |
| Yangtze Memory Technologies      | 3         | 0.04%   |
| Promise Technology               | 3         | 0.04%   |
| Integrated Technology Express    | 3         | 0.04%   |
| Hewlett-Packard                  | 3         | 0.04%   |
| Broadcom                         | 3         | 0.04%   |
| ULi Electronics                  | 2         | 0.02%   |
| INNOGRIT                         | 2         | 0.02%   |
| HighPoint Technologies           | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 758       | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 371       | 3.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 349       | 3.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 282       | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 263       | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 240       | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 212       | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 190       | 1.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 169       | 1.71%   |
| Samsung NVMe SSD Controller 980                                                | 163       | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 161       | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 153       | 1.55%   |
| AMD 400 Series Chipset SATA Controller                                         | 149       | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 147       | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 139       | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 139       | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 136       | 1.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 132       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 129       | 1.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 128       | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 122       | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 113       | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 110       | 1.12%   |
| Intel SATA Controller [RAID mode]                                              | 108       | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 108       | 1.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 104       | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 102       | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 95        | 0.96%   |
| Phison E12 NVMe Controller                                                     | 94        | 0.95%   |
| Micron NVMe Storage Controller                                                 | 91        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 91        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 80        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 80        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 80        | 0.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 79        | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 75        | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                             | 71        | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 70        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 67        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 66        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 4780      | 56.06%  |
| NVMe | 1849      | 21.68%  |
| IDE  | 1293      | 15.16%  |
| RAID | 586       | 6.87%   |
| SAS  | 10        | 0.12%   |
| SCSI | 9         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 5348      | 77.55%  |
| AMD          | 1497      | 21.71%  |
| ARM          | 46        | 0.67%   |
| CentaurHauls | 4         | 0.06%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 95        | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 76        | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 74        | 1.07%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 72        | 1.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 67        | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 55        | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 54        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 50        | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 49        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 47        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 46        | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 46        | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 45        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 44        | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 41        | 0.59%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 39        | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 38        | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 37        | 0.54%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 37        | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 35        | 0.51%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 35        | 0.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 34        | 0.49%   |
| ARM Processor                                 | 33        | 0.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 0.48%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 31        | 0.45%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 31        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 30        | 0.43%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 30        | 0.43%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.43%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 29        | 0.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.41%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 28        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 27        | 0.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.38%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 26        | 0.38%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 0.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 25        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1375      | 19.9%   |
| Intel Core i5           | 1314      | 19.02%  |
| Intel Core i3           | 477       | 6.91%   |
| Intel Core 2 Duo        | 402       | 5.82%   |
| Other                   | 380       | 5.5%    |
| Intel Celeron           | 373       | 5.4%    |
| AMD Ryzen 5             | 330       | 4.78%   |
| AMD Ryzen 7             | 260       | 3.76%   |
| Intel Atom              | 248       | 3.59%   |
| Intel Pentium           | 132       | 1.91%   |
| Intel Pentium Dual-Core | 119       | 1.72%   |
| Intel Core 2 Quad       | 104       | 1.51%   |
| Intel Xeon              | 99        | 1.43%   |
| AMD FX                  | 73        | 1.06%   |
| Intel Core 2            | 72        | 1.04%   |
| AMD Ryzen 3             | 69        | 1%      |
| Intel Pentium Dual      | 67        | 0.97%   |
| AMD Ryzen 9             | 66        | 0.96%   |
| Intel Pentium 4         | 63        | 0.91%   |
| AMD A8                  | 57        | 0.83%   |
| AMD E1                  | 50        | 0.72%   |
| AMD Athlon 64 X2        | 49        | 0.71%   |
| AMD A4                  | 46        | 0.67%   |
| AMD A10                 | 46        | 0.67%   |
| Intel Core i9           | 45        | 0.65%   |
| AMD A6                  | 42        | 0.61%   |
| Intel Genuine           | 39        | 0.56%   |
| AMD Sempron             | 33        | 0.48%   |
| AMD Phenom II X4        | 30        | 0.43%   |
| AMD E2                  | 25        | 0.36%   |
| Intel Pentium D         | 24        | 0.35%   |
| Intel Pentium Silver    | 20        | 0.29%   |
| AMD Phenom II X6        | 20        | 0.29%   |
| AMD Athlon II X2        | 19        | 0.28%   |
| AMD Ryzen 5 PRO         | 18        | 0.26%   |
| Intel Pentium M         | 16        | 0.23%   |
| AMD Ryzen 7 PRO         | 16        | 0.23%   |
| AMD Phenom              | 16        | 0.23%   |
| AMD Athlon II X4        | 16        | 0.23%   |
| AMD Athlon              | 16        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2849      | 41.23%  |
| 4       | 2601      | 37.64%  |
| 6       | 546       | 7.9%    |
| 8       | 402       | 5.82%   |
| 1       | 299       | 4.33%   |
| 12      | 68        | 0.98%   |
| 10      | 37        | 0.54%   |
| 3       | 36        | 0.52%   |
| 14      | 30        | 0.43%   |
| 16      | 22        | 0.32%   |
| Unknown | 7         | 0.1%    |
| 24      | 5         | 0.07%   |
| 28      | 2         | 0.03%   |
| 20      | 2         | 0.03%   |
| 5       | 2         | 0.03%   |
| 64      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 6838      | 99.16%  |
| 2       | 50        | 0.73%   |
| Unknown | 5         | 0.07%   |
| 4       | 2         | 0.03%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4113      | 59.54%  |
| 1       | 2784      | 40.3%   |
| Unknown | 7         | 0.1%    |
| 4       | 4         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6697      | 96.95%  |
| 32-bit         | 122       | 1.77%   |
| Unknown        | 87        | 1.26%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1542      | 21.52%  |
| 0x206a7    | 362       | 5.05%   |
| 0x306a9    | 350       | 4.88%   |
| 0x1067a    | 294       | 4.1%    |
| 0x306c3    | 283       | 3.95%   |
| 0x806ea    | 176       | 2.46%   |
| 0x806ec    | 147       | 2.05%   |
| 0x40651    | 147       | 2.05%   |
| 0x906ea    | 146       | 2.04%   |
| 0x806e9    | 144       | 2.01%   |
| 0x806c1    | 144       | 2.01%   |
| 0x506e3    | 136       | 1.9%    |
| 0x406e3    | 132       | 1.84%   |
| 0x6fd      | 131       | 1.83%   |
| 0x906e9    | 120       | 1.67%   |
| 0x20655    | 112       | 1.56%   |
| 0x10676    | 103       | 1.44%   |
| 0x08108109 | 93        | 1.3%    |
| 0x306d4    | 89        | 1.24%   |
| 0x08701021 | 88        | 1.23%   |
| 0x406c4    | 80        | 1.12%   |
| 0x6fb      | 77        | 1.07%   |
| 0x30678    | 72        | 1%      |
| 0x406c3    | 68        | 0.95%   |
| 0x706e5    | 64        | 0.89%   |
| 0x20652    | 63        | 0.88%   |
| 0x0a50000c | 62        | 0.87%   |
| 0x706a1    | 61        | 0.85%   |
| 0x806eb    | 53        | 0.74%   |
| 0x706a8    | 52        | 0.73%   |
| 0x6f6      | 51        | 0.71%   |
| 0x010000c8 | 51        | 0.71%   |
| 0x506c9    | 49        | 0.68%   |
| 0x08608103 | 49        | 0.68%   |
| 0x106e5    | 48        | 0.67%   |
| 0x06006705 | 48        | 0.67%   |
| 0x106ca    | 44        | 0.61%   |
| 0x906ed    | 43        | 0.6%    |
| 0xa0652    | 42        | 0.59%   |
| 0x08600106 | 41        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1030      | 14.9%   |
| Haswell          | 556       | 8.05%   |
| Penryn           | 491       | 7.1%    |
| SandyBridge      | 456       | 6.6%    |
| IvyBridge        | 438       | 6.34%   |
| Skylake          | 346       | 5.01%   |
| Core             | 342       | 4.95%   |
| Silvermont       | 278       | 4.02%   |
| Zen 2            | 229       | 3.31%   |
| Westmere         | 221       | 3.2%    |
| Zen+             | 194       | 2.81%   |
| TigerLake        | 186       | 2.69%   |
| Unknown          | 185       | 2.68%   |
| K10              | 167       | 2.42%   |
| Zen 3            | 159       | 2.3%    |
| Goldmont plus    | 139       | 2.01%   |
| CometLake        | 135       | 1.95%   |
| Broadwell        | 115       | 1.66%   |
| Zen              | 112       | 1.62%   |
| K8 Hammer        | 111       | 1.61%   |
| Excavator        | 111       | 1.61%   |
| Icelake          | 105       | 1.52%   |
| Bonnell          | 97        | 1.4%    |
| Piledriver       | 96        | 1.39%   |
| NetBurst         | 95        | 1.37%   |
| Nehalem          | 93        | 1.35%   |
| Goldmont         | 67        | 0.97%   |
| Alderlake Hybrid | 61        | 0.88%   |
| P6               | 59        | 0.85%   |
| Jaguar           | 50        | 0.72%   |
| Puma             | 48        | 0.69%   |
| Bobcat           | 36        | 0.52%   |
| K10 Llano        | 34        | 0.49%   |
| Steamroller      | 31        | 0.45%   |
| K8 & K10 hybrid  | 17        | 0.25%   |
| Bulldozer        | 12        | 0.17%   |
| Tremont          | 8         | 0.12%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3876      | 47.96%  |
| Nvidia                                       | 2295      | 28.4%   |
| AMD                                          | 1847      | 22.86%  |
| Silicon Integrated Systems [SiS]             | 19        | 0.24%   |
| VIA Technologies                             | 16        | 0.2%    |
| Matrox Electronics Systems                   | 16        | 0.2%    |
| ASPEED Technology                            | 7         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.04%   |
| S3 Graphics                                  | 1         | 0.01%   |
| ATI Technologies                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 314       | 3.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 250       | 2.98%   |
| Intel UHD Graphics 620                                                                   | 198       | 2.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 180       | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 178       | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 171       | 2.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 151       | 1.8%    |
| Intel HD Graphics 620                                                                    | 143       | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 142       | 1.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 140       | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 126       | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 122       | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 119       | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 105       | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 105       | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 99        | 1.18%   |
| AMD Renoir                                                                               | 97        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 96        | 1.14%   |
| Intel HD Graphics 5500                                                                   | 92        | 1.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 92        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 82        | 0.98%   |
| Intel HD Graphics 530                                                                    | 81        | 0.96%   |
| Intel HD Graphics 630                                                                    | 78        | 0.93%   |
| AMD Lucienne                                                                             | 75        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 74        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 74        | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 72        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 70        | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 69        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 68        | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 62        | 0.74%   |
| Nvidia GT218 [GeForce 210]                                                               | 60        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 58        | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 58        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 57        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 56        | 0.67%   |
| Intel HD Graphics 500                                                                    | 56        | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 53        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 53        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2736      | 39.51%  |
| 1 x AMD                 | 1446      | 20.88%  |
| 1 x Nvidia              | 1311      | 18.93%  |
| Intel + Nvidia          | 894       | 12.91%  |
| Intel + AMD             | 184       | 2.66%   |
| 2 x AMD                 | 141       | 2.04%   |
| AMD + Nvidia            | 73        | 1.05%   |
| Other                   | 53        | 0.77%   |
| 1 x SiS                 | 19        | 0.27%   |
| 1 x VIA                 | 16        | 0.23%   |
| 2 x Intel               | 11        | 0.16%   |
| 2 x Nvidia              | 10        | 0.14%   |
| 1 x Matrox              | 9         | 0.13%   |
| Nvidia + Matrox         | 4         | 0.06%   |
| 1 x XGI                 | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| 1 x ASPEED              | 3         | 0.04%   |
| AMD + Matrox            | 2         | 0.03%   |
| 3 x AMD                 | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + ASPEED            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5655      | 80.71%  |
| Proprietary | 1102      | 15.73%  |
| Unknown     | 250       | 3.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3765      | 52.98%  |
| 0.01-0.5   | 984       | 13.85%  |
| 1.01-2.0   | 951       | 13.38%  |
| 0.51-1.0   | 636       | 8.95%   |
| 3.01-4.0   | 381       | 5.36%   |
| 7.01-8.0   | 174       | 2.45%   |
| 5.01-6.0   | 134       | 1.89%   |
| 2.01-3.0   | 46        | 0.65%   |
| 8.01-16.0  | 34        | 0.48%   |
| 4.01-5.0   | 1         | 0.01%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1072      | 14.88%  |
| AU Optronics            | 850       | 11.8%   |
| Chimei Innolux          | 651       | 9.03%   |
| LG Display              | 585       | 8.12%   |
| BOE                     | 572       | 7.94%   |
| Hewlett-Packard         | 358       | 4.97%   |
| Philips                 | 328       | 4.55%   |
| Goldstar                | 322       | 4.47%   |
| Ancor Communications    | 275       | 3.82%   |
| Acer                    | 237       | 3.29%   |
| Dell                    | 181       | 2.51%   |
| BenQ                    | 159       | 2.21%   |
| Chi Mei Optoelectronics | 135       | 1.87%   |
| Sharp                   | 131       | 1.82%   |
| Apple                   | 128       | 1.78%   |
| AOC                     | 124       | 1.72%   |
| Lenovo                  | 102       | 1.42%   |
| HannStar                | 73        | 1.01%   |
| Sony                    | 64        | 0.89%   |
| LG Philips              | 63        | 0.87%   |
| PANDA                   | 61        | 0.85%   |
| InfoVision              | 43        | 0.6%    |
| Unknown                 | 42        | 0.58%   |
| ASUSTek Computer        | 42        | 0.58%   |
| LG Electronics          | 37        | 0.51%   |
| MSI                     | 25        | 0.35%   |
| Eizo                    | 22        | 0.31%   |
| CPT                     | 22        | 0.31%   |
| CSO                     | 19        | 0.26%   |
| Fujitsu Siemens         | 18        | 0.25%   |
| Toshiba                 | 17        | 0.24%   |
| Packard Bell            | 14        | 0.19%   |
| Iiyama                  | 14        | 0.19%   |
| Vestel Elektronik       | 13        | 0.18%   |
| Quanta Display          | 13        | 0.18%   |
| LGD                     | 13        | 0.18%   |
| Panasonic               | 12        | 0.17%   |
| NEC Computers           | 12        | 0.17%   |
| Mi                      | 12        | 0.17%   |
| Belinea                 | 11        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 65        | 0.88%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 39        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 39        | 0.53%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 34        | 0.46%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 34        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 33        | 0.45%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 31        | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 30        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 29        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 28        | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 28        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 27        | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 26        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 25        | 0.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 24        | 0.32%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 24        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 23        | 0.31%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 21        | 0.28%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 20        | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 20        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 20        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 20        | 0.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 19        | 0.26%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 17        | 0.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 17        | 0.23%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 17        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 17        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 17        | 0.23%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 15        | 0.2%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 15        | 0.2%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.2%    |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch            | 15        | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 14        | 0.19%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.19%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 13        | 0.18%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 13        | 0.18%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 13        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3001      | 43.18%  |
| 1366x768 (WXGA)    | 1431      | 20.59%  |
| 3840x2160 (4K)     | 339       | 4.88%   |
| 1280x1024 (SXGA)   | 316       | 4.55%   |
| 1280x800 (WXGA)    | 291       | 4.19%   |
| 1440x900 (WXGA+)   | 226       | 3.25%   |
| 1680x1050 (WSXGA+) | 215       | 3.09%   |
| 2560x1440 (QHD)    | 211       | 3.04%   |
| 1600x900 (HD+)     | 184       | 2.65%   |
| 1920x1200 (WUXGA)  | 110       | 1.58%   |
| 1360x768           | 69        | 0.99%   |
| Unknown            | 60        | 0.86%   |
| 1024x600           | 59        | 0.85%   |
| 2560x1080          | 47        | 0.68%   |
| 1024x768 (XGA)     | 37        | 0.53%   |
| 2560x1600          | 36        | 0.52%   |
| 3440x1440          | 32        | 0.46%   |
| 3840x1080          | 31        | 0.45%   |
| 2160x1440          | 31        | 0.45%   |
| 2880x1800          | 23        | 0.33%   |
| 3840x2400          | 17        | 0.24%   |
| 1920x540           | 14        | 0.2%    |
| 1600x1200          | 14        | 0.2%    |
| 1280x720 (HD)      | 11        | 0.16%   |
| 3000x2000          | 9         | 0.13%   |
| 1920x1280          | 9         | 0.13%   |
| 3200x1800 (QHD+)   | 8         | 0.12%   |
| 2736x1824          | 8         | 0.12%   |
| 800x1280           | 7         | 0.1%    |
| 2880x1920          | 6         | 0.09%   |
| 3840x1600          | 5         | 0.07%   |
| 3072x1920          | 5         | 0.07%   |
| 2288x1287          | 5         | 0.07%   |
| 1800x1200          | 5         | 0.07%   |
| 1280x768           | 5         | 0.07%   |
| 4480x1440          | 4         | 0.06%   |
| 2520x1680          | 4         | 0.06%   |
| 2256x1504          | 4         | 0.06%   |
| 2240x1400          | 4         | 0.06%   |
| 1400x1050          | 4         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2212      | 30.63%  |
| 13      | 609       | 8.43%   |
| 24      | 482       | 6.67%   |
| 27      | 466       | 6.45%   |
| 21      | 453       | 6.27%   |
| 14      | 402       | 5.57%   |
| 23      | 393       | 5.44%   |
| Unknown | 381       | 5.28%   |
| 17      | 336       | 4.65%   |
| 19      | 274       | 3.79%   |
| 18      | 152       | 2.1%    |
| 12      | 131       | 1.81%   |
| 20      | 116       | 1.61%   |
| 22      | 113       | 1.56%   |
| 10      | 81        | 1.12%   |
| 31      | 80        | 1.11%   |
| 34      | 72        | 1%      |
| 11      | 69        | 0.96%   |
| 40      | 53        | 0.73%   |
| 16      | 47        | 0.65%   |
| 84      | 39        | 0.54%   |
| 54      | 32        | 0.44%   |
| 72      | 31        | 0.43%   |
| 32      | 23        | 0.32%   |
| 25      | 23        | 0.32%   |
| 52      | 12        | 0.17%   |
| 48      | 12        | 0.17%   |
| 28      | 10        | 0.14%   |
| 47      | 9         | 0.12%   |
| 42      | 9         | 0.12%   |
| 65      | 8         | 0.11%   |
| 37      | 8         | 0.11%   |
| 26      | 8         | 0.11%   |
| 46      | 7         | 0.1%    |
| 36      | 7         | 0.1%    |
| 8       | 6         | 0.08%   |
| 7       | 6         | 0.08%   |
| 142     | 5         | 0.07%   |
| 43      | 5         | 0.07%   |
| 39      | 5         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2991      | 41.9%   |
| 501-600        | 1261      | 17.66%  |
| 401-500        | 939       | 13.15%  |
| 201-300        | 635       | 8.89%   |
| 351-400        | 415       | 5.81%   |
| Unknown        | 381       | 5.34%   |
| 601-700        | 141       | 1.98%   |
| 701-800        | 105       | 1.47%   |
| 1001-1500      | 93        | 1.3%    |
| 1501-2000      | 74        | 1.04%   |
| 801-900        | 71        | 0.99%   |
| 901-1000       | 14        | 0.2%    |
| 101-200        | 8         | 0.11%   |
| 1-100          | 6         | 0.08%   |
| More than 2000 | 5         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4858      | 72.94%  |
| 16/10   | 902       | 13.54%  |
| Unknown | 318       | 4.77%   |
| 5/4     | 300       | 4.5%    |
| 3/2     | 90        | 1.35%   |
| 21/9    | 79        | 1.19%   |
| 4/3     | 77        | 1.16%   |
| 6/5     | 12        | 0.18%   |
| 32/9    | 10        | 0.15%   |
| 0.67    | 6         | 0.09%   |
| 1.00    | 5         | 0.08%   |
| 2.65    | 1         | 0.02%   |
| 2.21    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2211      | 30.88%  |
| 201-250        | 1168      | 16.31%  |
| 81-90          | 730       | 10.19%  |
| 151-200        | 552       | 7.71%   |
| 301-350        | 474       | 6.62%   |
| Unknown        | 381       | 5.32%   |
| 71-80          | 284       | 3.97%   |
| 141-150        | 240       | 3.35%   |
| 351-500        | 184       | 2.57%   |
| 121-130        | 158       | 2.21%   |
| 251-300        | 149       | 2.08%   |
| More than 1000 | 148       | 2.07%   |
| 61-70          | 119       | 1.66%   |
| 501-1000       | 116       | 1.62%   |
| 41-50          | 80        | 1.12%   |
| 51-60          | 71        | 0.99%   |
| 131-140        | 33        | 0.46%   |
| 111-120        | 33        | 0.46%   |
| 91-100         | 17        | 0.24%   |
| 1-40           | 13        | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2491      | 35.49%  |
| 101-120       | 1856      | 26.45%  |
| 121-160       | 1662      | 23.68%  |
| Unknown       | 381       | 5.43%   |
| 161-240       | 379       | 5.4%    |
| 1-50          | 131       | 1.87%   |
| More than 240 | 118       | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5818      | 82.68%  |
| 2     | 869       | 12.35%  |
| 0     | 273       | 3.88%   |
| 3     | 74        | 1.05%   |
| 4     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3764      | 36.14%  |
| Intel                             | 2981      | 28.62%  |
| Qualcomm Atheros                  | 1283      | 12.32%  |
| Broadcom                          | 619       | 5.94%   |
| Marvell Technology Group          | 204       | 1.96%   |
| TP-Link                           | 145       | 1.39%   |
| Broadcom Limited                  | 144       | 1.38%   |
| Nvidia                            | 138       | 1.32%   |
| Ralink Technology                 | 129       | 1.24%   |
| Ralink                            | 112       | 1.08%   |
| MediaTek                          | 93        | 0.89%   |
| Qualcomm Atheros Communications   | 52        | 0.5%    |
| Huawei Technologies               | 51        | 0.49%   |
| ASIX Electronics                  | 46        | 0.44%   |
| Xiaomi                            | 40        | 0.38%   |
| D-Link System                     | 40        | 0.38%   |
| Samsung Electronics               | 38        | 0.36%   |
| D-Link                            | 37        | 0.36%   |
| Sitecom Europe                    | 31        | 0.3%    |
| VIA Technologies                  | 30        | 0.29%   |
| Dell                              | 29        | 0.28%   |
| NetGear                           | 25        | 0.24%   |
| Silicon Integrated Systems [SiS]  | 23        | 0.22%   |
| ASUSTek Computer                  | 22        | 0.21%   |
| Sierra Wireless                   | 19        | 0.18%   |
| Microsoft                         | 19        | 0.18%   |
| Ericsson Business Mobile Networks | 19        | 0.18%   |
| JMicron Technology                | 18        | 0.17%   |
| Attansic Technology               | 17        | 0.16%   |
| Qualcomm                          | 15        | 0.14%   |
| Belkin Components                 | 13        | 0.12%   |
| Hewlett-Packard                   | 12        | 0.12%   |
| OPPO Electronics                  | 11        | 0.11%   |
| Microchip Technology              | 11        | 0.11%   |
| DisplayLink                       | 11        | 0.11%   |
| ZTE WCDMA Technologies MSM        | 9         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 9         | 0.09%   |
| Lenovo                            | 9         | 0.09%   |
| Gemtek                            | 9         | 0.09%   |
| Aquantia                          | 8         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2568      | 21.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 446       | 3.7%    |
| Intel Wi-Fi 6 AX200                                                     | 234       | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 217       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 213       | 1.77%   |
| Intel Wireless 8265 / 8275                                              | 193       | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 187       | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 181       | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 174       | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 168       | 1.4%    |
| Intel Wireless 7265                                                     | 162       | 1.35%   |
| Intel Wireless 3165                                                     | 151       | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 148       | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 142       | 1.18%   |
| Intel Wi-Fi 6 AX201                                                     | 132       | 1.1%    |
| Intel Ethernet Connection (2) I219-V                                    | 111       | 0.92%   |
| Intel I211 Gigabit Network Connection                                   | 106       | 0.88%   |
| Intel Wireless 7260                                                     | 103       | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 102       | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 88        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 88        | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 86        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 83        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 81        | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 79        | 0.66%   |
| Intel Wireless 8260                                                     | 78        | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                       | 77        | 0.64%   |
| Intel 82579V Gigabit Network Connection                                 | 77        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 75        | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 0.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 72        | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 71        | 0.59%   |
| Intel WiFi Link 5100                                                    | 67        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 64        | 0.53%   |
| Intel Ethernet Connection I217-LM                                       | 60        | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 60        | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 54        | 0.45%   |
| Intel Wireless-AC 9260                                                  | 54        | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 53        | 0.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 52        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2240      | 40.13%  |
| Qualcomm Atheros                      | 1076      | 19.28%  |
| Realtek Semiconductor                 | 996       | 17.84%  |
| Broadcom                              | 405       | 7.26%   |
| TP-Link                               | 132       | 2.36%   |
| Ralink Technology                     | 129       | 2.31%   |
| Ralink                                | 112       | 2.01%   |
| MediaTek                              | 84        | 1.5%    |
| Broadcom Limited                      | 83        | 1.49%   |
| Qualcomm Atheros Communications       | 52        | 0.93%   |
| D-Link                                | 36        | 0.64%   |
| D-Link System                         | 32        | 0.57%   |
| Sitecom Europe                        | 30        | 0.54%   |
| NetGear                               | 24        | 0.43%   |
| ASUSTek Computer                      | 21        | 0.38%   |
| Dell                                  | 18        | 0.32%   |
| Microsoft                             | 16        | 0.29%   |
| Sierra Wireless                       | 15        | 0.27%   |
| Marvell Technology Group              | 13        | 0.23%   |
| Belkin Components                     | 13        | 0.23%   |
| Gemtek                                | 9         | 0.16%   |
| Fibocom                               | 6         | 0.11%   |
| AVM                                   | 6         | 0.11%   |
| ZyDAS                                 | 5         | 0.09%   |
| Qualcomm                              | 5         | 0.09%   |
| Linksys                               | 5         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.04%   |
| U.S. Robotics                         | 2         | 0.04%   |
| Qcom                                  | 2         | 0.04%   |
| Hewlett-Packard                       | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 234       | 4.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 217       | 3.87%   |
| Intel Wireless 8265 / 8275                                              | 193       | 3.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 187       | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 181       | 3.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 174       | 3.1%    |
| Intel Wireless 7265                                                     | 162       | 2.89%   |
| Intel Wireless 3165                                                     | 151       | 2.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 148       | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 142       | 2.53%   |
| Intel Wi-Fi 6 AX201                                                     | 132       | 2.35%   |
| Intel Wireless 7260                                                     | 103       | 1.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 102       | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 88        | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 88        | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 83        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 81        | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 79        | 1.41%   |
| Intel Wireless 8260                                                     | 78        | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 75        | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 75        | 1.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 72        | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 71        | 1.26%   |
| Intel WiFi Link 5100                                                    | 67        | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 64        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                           | 60        | 1.07%   |
| Intel Wireless-AC 9260                                                  | 54        | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 53        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 52        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 51        | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                         | 48        | 0.86%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 47        | 0.84%   |
| Realtek 802.11ac NIC                                                    | 47        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 46        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 44        | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 43        | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 43        | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 39        | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 37        | 0.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 36        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3388      | 54.51%  |
| Intel                            | 1405      | 22.61%  |
| Qualcomm Atheros                 | 337       | 5.42%   |
| Broadcom                         | 287       | 4.62%   |
| Marvell Technology Group         | 191       | 3.07%   |
| Nvidia                           | 137       | 2.2%    |
| Broadcom Limited                 | 62        | 1%      |
| ASIX Electronics                 | 46        | 0.74%   |
| Huawei Technologies              | 42        | 0.68%   |
| Xiaomi                           | 40        | 0.64%   |
| VIA Technologies                 | 29        | 0.47%   |
| Samsung Electronics              | 27        | 0.43%   |
| Silicon Integrated Systems [SiS] | 21        | 0.34%   |
| JMicron Technology               | 18        | 0.29%   |
| Attansic Technology              | 17        | 0.27%   |
| TP-Link                          | 13        | 0.21%   |
| OPPO Electronics                 | 11        | 0.18%   |
| DisplayLink                      | 11        | 0.18%   |
| Qualcomm                         | 10        | 0.16%   |
| MediaTek                         | 9         | 0.14%   |
| Lenovo                           | 9         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 8         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.13%   |
| D-Link System                    | 8         | 0.13%   |
| Aquantia                         | 8         | 0.13%   |
| Microchip Technology             | 7         | 0.11%   |
| Apple                            | 7         | 0.11%   |
| HMD Global                       | 6         | 0.1%    |
| Motorola PCS                     | 5         | 0.08%   |
| ICS Advent                       | 5         | 0.08%   |
| 3Com                             | 5         | 0.08%   |
| T & A Mobile Phones              | 4         | 0.06%   |
| Sierra Wireless                  | 4         | 0.06%   |
| Google                           | 4         | 0.06%   |
| LG Electronics                   | 3         | 0.05%   |
| Hewlett-Packard                  | 3         | 0.05%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| Foxconn / Hon Hai                | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.02%   |
| SysKonnect                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2568      | 40.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 446       | 7.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 213       | 3.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 168       | 2.66%   |
| Intel Ethernet Connection (2) I219-V                              | 111       | 1.76%   |
| Intel I211 Gigabit Network Connection                             | 106       | 1.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 86        | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 77        | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 60        | 0.95%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 54        | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 49        | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 45        | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 45        | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 42        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 40        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 40        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 39        | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 39        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 36        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 36        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 35        | 0.56%   |
| Intel 82577LM Gigabit Network Connection                          | 35        | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32        | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 32        | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 31        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 31        | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 31        | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 29        | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 29        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 28        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 28        | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 27        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 26        | 0.41%   |
| Huawei ATU-L21                                                    | 25        | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5874      | 52.08%  |
| WiFi     | 5282      | 46.83%  |
| Modem    | 111       | 0.98%   |
| Unknown  | 12        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4128      | 58.58%  |
| Ethernet | 2915      | 41.37%  |
| Unknown  | 3         | 0.04%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3727      | 53.87%  |
| 1     | 2894      | 41.83%  |
| 0     | 170       | 2.46%   |
| 3     | 108       | 1.56%   |
| 4     | 13        | 0.19%   |
| 6     | 2         | 0.03%   |
| 5     | 2         | 0.03%   |
| 12    | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6533      | 93.93%  |
| Yes  | 422       | 6.07%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1728      | 43.81%  |
| Realtek Semiconductor           | 475       | 12.04%  |
| Cambridge Silicon Radio         | 244       | 6.19%   |
| Qualcomm Atheros Communications | 243       | 6.16%   |
| Broadcom                        | 209       | 5.3%    |
| IMC Networks                    | 203       | 5.15%   |
| Lite-On Technology              | 176       | 4.46%   |
| Apple                           | 140       | 3.55%   |
| Foxconn / Hon Hai               | 134       | 3.4%    |
| Hewlett-Packard                 | 64        | 1.62%   |
| ASUSTek Computer                | 63        | 1.6%    |
| Realtek                         | 54        | 1.37%   |
| Dell                            | 40        | 1.01%   |
| Ralink                          | 34        | 0.86%   |
| Toshiba                         | 33        | 0.84%   |
| Alps Electric                   | 15        | 0.38%   |
| Marvell Semiconductor           | 12        | 0.3%    |
| MediaTek                        | 11        | 0.28%   |
| Integrated System Solution      | 10        | 0.25%   |
| TP-Link                         | 9         | 0.23%   |
| Ralink Technology               | 7         | 0.18%   |
| Foxconn International           | 5         | 0.13%   |
| Sitecom Europe                  | 4         | 0.1%    |
| Chicony Electronics             | 4         | 0.1%    |
| Belkin Components               | 4         | 0.1%    |
| Askey Computer                  | 4         | 0.1%    |
| Conwise Technology              | 3         | 0.08%   |
| Taiyo Yuden                     | 2         | 0.05%   |
| D-Link System                   | 2         | 0.05%   |
| Accel Semiconductor             | 2         | 0.05%   |
| Unknown                         | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| HTC (High Tech Computer)        | 1         | 0.03%   |
| Fujitsu Siemens Computers       | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| 3Com                            | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 711       | 18.02%  |
| Realtek Bluetooth Radio                                                             | 315       | 7.98%   |
| Intel AX201 Bluetooth                                                               | 286       | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 251       | 6.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 244       | 6.19%   |
| Intel AX200 Bluetooth                                                               | 217       | 5.5%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 139       | 3.52%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 122       | 3.09%   |
| IMC Networks Bluetooth Device                                                       | 95        | 2.41%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 74        | 1.88%   |
| Apple Bluetooth Host Controller                                                     | 66        | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 57        | 1.44%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 52        | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 51        | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 50        | 1.27%   |
| IMC Networks Bluetooth Radio                                                        | 50        | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 46        | 1.17%   |
| Lite-On Bluetooth Device                                                            | 45        | 1.14%   |
| Realtek 802.11ac WLAN Adapter                                                       | 42        | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 42        | 1.06%   |
| Broadcom BCM2045 Bluetooth                                                          | 40        | 1.01%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 36        | 0.91%   |
| Intel Bluetooth Device                                                              | 36        | 0.91%   |
| Ralink RT3290 Bluetooth                                                             | 34        | 0.86%   |
| Intel AX210 Bluetooth                                                               | 33        | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 31        | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 30        | 0.76%   |
| Apple Bluetooth HCI                                                                 | 28        | 0.71%   |
| IMC Networks Wireless_Device                                                        | 25        | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 25        | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 23        | 0.58%   |
| Apple Bluetooth USB Host Controller                                                 | 22        | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 21        | 0.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 20        | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 19        | 0.48%   |
| Realtek RTL8723B Bluetooth                                                          | 18        | 0.46%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 16        | 0.41%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 16        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 16        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 5006      | 54.87%  |
| AMD                                  | 1830      | 20.06%  |
| Nvidia                               | 1466      | 16.07%  |
| C-Media Electronics                  | 160       | 1.75%   |
| Logitech                             | 55        | 0.6%    |
| Creative Labs                        | 53        | 0.58%   |
| VIA Technologies                     | 41        | 0.45%   |
| Silicon Integrated Systems [SiS]     | 32        | 0.35%   |
| JMTek                                | 31        | 0.34%   |
| GN Netcom                            | 25        | 0.27%   |
| Generalplus Technology               | 22        | 0.24%   |
| Texas Instruments                    | 21        | 0.23%   |
| Realtek Semiconductor                | 21        | 0.23%   |
| Creative Technology                  | 21        | 0.23%   |
| Razer USA                            | 19        | 0.21%   |
| M-Audio                              | 16        | 0.18%   |
| Focusrite-Novation                   | 15        | 0.16%   |
| ASUSTek Computer                     | 12        | 0.13%   |
| Kingston Technology                  | 11        | 0.12%   |
| Samson Technologies                  | 10        | 0.11%   |
| Dell                                 | 10        | 0.11%   |
| BEHRINGER International              | 10        | 0.11%   |
| Tenx Technology                      | 9         | 0.1%    |
| Plantronics                          | 9         | 0.1%    |
| Micro Star International             | 9         | 0.1%    |
| Hewlett-Packard                      | 9         | 0.1%    |
| Corsair                              | 8         | 0.09%   |
| Trust                                | 7         | 0.08%   |
| Microsoft                            | 7         | 0.08%   |
| Lenovo                               | 7         | 0.08%   |
| Ensoniq                              | 7         | 0.08%   |
| CMX Systems                          | 6         | 0.07%   |
| Apple                                | 6         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.05%   |
| Sony                                 | 5         | 0.05%   |
| SAVITECH                             | 5         | 0.05%   |
| Cambridge Silicon Radio              | 5         | 0.05%   |
| Yamaha                               | 4         | 0.04%   |
| XMOS                                 | 4         | 0.04%   |
| Huawei Technologies                  | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 539       | 5.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 472       | 4.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 433       | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 419       | 3.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 312       | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 310       | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 303       | 2.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 265       | 2.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 249       | 2.33%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 232       | 2.17%   |
| AMD FCH Azalia Controller                                                  | 214       | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 208       | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 203       | 1.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 191       | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 186       | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 186       | 1.74%   |
| AMD Starship/Matisse HD Audio Controller                                   | 185       | 1.73%   |
| Intel Haswell-ULT HD Audio Controller                                      | 180       | 1.68%   |
| Intel 8 Series HD Audio Controller                                         | 180       | 1.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 151       | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 140       | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 138       | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 135       | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                               | 133       | 1.24%   |
| AMD Kabini HDMI/DP Audio                                                   | 125       | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 119       | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                              | 115       | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 112       | 1.05%   |
| Nvidia High Definition Audio Controller                                    | 110       | 1.03%   |
| Intel 200 Series PCH HD Audio                                              | 110       | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 108       | 1.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 107       | 1%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 104       | 0.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 98        | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 95        | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 87        | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 83        | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 77        | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 75        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 70        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 960       | 22.17%  |
| SK hynix                     | 728       | 16.81%  |
| Kingston                     | 514       | 11.87%  |
| Unknown                      | 507       | 11.71%  |
| Micron Technology            | 440       | 10.16%  |
| Crucial                      | 294       | 6.79%   |
| Corsair                      | 258       | 5.96%   |
| G.Skill                      | 85        | 1.96%   |
| Unknown (ABCD)               | 81        | 1.87%   |
| Ramaxel Technology           | 80        | 1.85%   |
| Elpida                       | 74        | 1.71%   |
| A-DATA Technology            | 62        | 1.43%   |
| Nanya Technology             | 47        | 1.09%   |
| Team                         | 35        | 0.81%   |
| Unknown                      | 28        | 0.65%   |
| Patriot                      | 27        | 0.62%   |
| Transcend                    | 16        | 0.37%   |
| ASint Technology             | 10        | 0.23%   |
| Unifosa                      | 8         | 0.18%   |
| Toshiba                      | 6         | 0.14%   |
| Qimonda                      | 6         | 0.14%   |
| Timetec                      | 4         | 0.09%   |
| Patriot Memory (PDP Systems) | 4         | 0.09%   |
| Hewlett-Packard              | 4         | 0.09%   |
| 48spaces                     | 4         | 0.09%   |
| Unknown (AB)                 | 3         | 0.07%   |
| Silicon Power                | 3         | 0.07%   |
| GeIL                         | 3         | 0.07%   |
| PLEXHD                       | 2         | 0.05%   |
| GOODRAM                      | 2         | 0.05%   |
| Goldkey                      | 2         | 0.05%   |
| CSX                          | 2         | 0.05%   |
| A Force                      | 2         | 0.05%   |
| V-Color                      | 1         | 0.02%   |
| Unknown (D386)               | 1         | 0.02%   |
| Unknown (8A5D)               | 1         | 0.02%   |
| Unknown (8A02)               | 1         | 0.02%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.02%   |
| Unknown (0x8551)             | 1         | 0.02%   |
| Unknown (0x5846)             | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 57        | 1.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 43        | 0.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 36        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 34        | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 32        | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 32        | 0.68%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 32        | 0.68%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 29        | 0.62%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 29        | 0.62%   |
| Unknown                                                          | 28        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 27        | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 24        | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 23        | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8192MB DIMM DDR4 3200MT/s         | 21        | 0.45%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 20        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 20        | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 19        | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 18        | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 17        | 0.36%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 17        | 0.36%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 17        | 0.36%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 17        | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 16        | 0.34%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.34%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 15        | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 15        | 0.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 15        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1698      | 44.65%  |
| DDR3    | 1266      | 33.29%  |
| DDR2    | 259       | 6.81%   |
| LPDDR4  | 179       | 4.71%   |
| SDRAM   | 136       | 3.58%   |
| LPDDR3  | 104       | 2.73%   |
| Unknown | 84        | 2.21%   |
| DDR     | 32        | 0.84%   |
| DDR5    | 22        | 0.58%   |
| LPDDR5  | 13        | 0.34%   |
| DRAM    | 10        | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2196      | 58.16%  |
| DIMM         | 1271      | 33.66%  |
| Row Of Chips | 291       | 7.71%   |
| Chip         | 12        | 0.32%   |
| FB-DIMM      | 4         | 0.11%   |
| Unknown      | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1505      | 36.64%  |
| 4096  | 1234      | 30.04%  |
| 2048  | 626       | 15.24%  |
| 16384 | 475       | 11.56%  |
| 1024  | 161       | 3.92%   |
| 32768 | 65        | 1.58%   |
| 512   | 34        | 0.83%   |
| 256   | 5         | 0.12%   |
| 3072  | 2         | 0.05%   |
| 32    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 775       | 18.86%  |
| 2667    | 586       | 14.26%  |
| 3200    | 530       | 12.9%   |
| 2400    | 339       | 8.25%   |
| 1333    | 267       | 6.5%    |
| 2133    | 180       | 4.38%   |
| 1334    | 147       | 3.58%   |
| Unknown | 127       | 3.09%   |
| 667     | 116       | 2.82%   |
| 3600    | 110       | 2.68%   |
| 800     | 110       | 2.68%   |
| 1867    | 101       | 2.46%   |
| 4267    | 58        | 1.41%   |
| 1066    | 56        | 1.36%   |
| 3266    | 53        | 1.29%   |
| 1067    | 35        | 0.85%   |
| 3400    | 33        | 0.8%    |
| 3000    | 31        | 0.75%   |
| 2933    | 31        | 0.75%   |
| 3466    | 27        | 0.66%   |
| 3733    | 25        | 0.61%   |
| 1866    | 23        | 0.56%   |
| 533     | 23        | 0.56%   |
| 4800    | 21        | 0.51%   |
| 4199    | 20        | 0.49%   |
| 1800    | 19        | 0.46%   |
| 2048    | 18        | 0.44%   |
| 8400    | 17        | 0.41%   |
| 3666    | 16        | 0.39%   |
| 400     | 16        | 0.39%   |
| 266     | 15        | 0.36%   |
| 3800    | 14        | 0.34%   |
| 6400    | 13        | 0.32%   |
| 2666    | 12        | 0.29%   |
| 4266    | 10        | 0.24%   |
| 2800    | 10        | 0.24%   |
| 975     | 9         | 0.22%   |
| 333     | 9         | 0.22%   |
| 2000    | 7         | 0.17%   |
| 1639    | 7         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 108       | 36.86%  |
| Samsung Electronics   | 51        | 17.41%  |
| Canon                 | 42        | 14.33%  |
| Seiko Epson           | 31        | 10.58%  |
| Brother Industries    | 31        | 10.58%  |
| Xerox                 | 4         | 1.37%   |
| Lexmark International | 4         | 1.37%   |
| Dymo-CoStar           | 4         | 1.37%   |
| Pantum                | 3         | 1.02%   |
| Prolific Technology   | 2         | 0.68%   |
| Oki Data              | 2         | 0.68%   |
| Kyocera               | 2         | 0.68%   |
| Apple                 | 2         | 0.68%   |
| Toshiba TEC           | 1         | 0.34%   |
| STMicroelectronics    | 1         | 0.34%   |
| Sato                  | 1         | 0.34%   |
| Sagem                 | 1         | 0.34%   |
| Ricoh                 | 1         | 0.34%   |
| QinHeng Electronics   | 1         | 0.34%   |
| ICS Advent            | 1         | 0.34%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                                  | 9         | 3.06%   |
| Seiko Epson WF-2510 Series                                            | 8         | 2.72%   |
| HP OfficeJet 6950                                                     | 8         | 2.72%   |
| Samsung M267x 287x Series                                             | 7         | 2.38%   |
| HP Deskjet 2050 J510                                                  | 7         | 2.38%   |
| Seiko Epson Printer                                                   | 5         | 1.7%    |
| Samsung ML-216x Series Laser Printer                                  | 5         | 1.7%    |
| Samsung M2070 Series                                                  | 5         | 1.7%    |
| HP ENVY 4520 series                                                   | 5         | 1.7%    |
| Canon LiDE 400                                                        | 5         | 1.7%    |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 4         | 1.36%   |
| HP Officejet 2620 series                                              | 4         | 1.36%   |
| HP LaserJet P1102                                                     | 4         | 1.36%   |
| HP LaserJet 1018                                                      | 4         | 1.36%   |
| Canon PIXMA MG3600 Series                                             | 4         | 1.36%   |
| Samsung ML-1660 Series                                                | 3         | 1.02%   |
| Samsung ML-1640 Series Laser Printer                                  | 3         | 1.02%   |
| Samsung Composite Device                                              | 3         | 1.02%   |
| HP LaserJet Professional P 1102w                                      | 3         | 1.02%   |
| HP LaserJet P1005                                                     | 3         | 1.02%   |
| HP LaserJet 1200                                                      | 3         | 1.02%   |
| HP ENVY 5000 series                                                   | 3         | 1.02%   |
| HP Deskjet F4500 series                                               | 3         | 1.02%   |
| HP Deskjet 3520 series                                                | 3         | 1.02%   |
| HP Deskjet 3050A                                                      | 3         | 1.02%   |
| Dymo-CoStar LabelWriter 450                                           | 3         | 1.02%   |
| Canon PIXMA MG2500 Series                                             | 3         | 1.02%   |
| Brother MFC-L2700DW                                                   | 3         | 1.02%   |
| Brother HL-3140CW series                                              | 3         | 1.02%   |
| Brother DCP-1610W                                                     | 3         | 1.02%   |
| Seiko Epson ET-2820 Series                                            | 2         | 0.68%   |
| Samsung SCX-4623 Series                                               | 2         | 0.68%   |
| Samsung SCX-4300 Series                                               | 2         | 0.68%   |
| Prolific PL2305 Parallel Port                                         | 2         | 0.68%   |
| Oki Data USB Device                                                   | 2         | 0.68%   |
| Lexmark International InkJet Color Printer                            | 2         | 0.68%   |
| HP Officejet Pro 6230                                                 | 2         | 0.68%   |
| HP OfficeJet 5200 series                                              | 2         | 0.68%   |
| HP OfficeJet 4650 series                                              | 2         | 0.68%   |
| HP Officejet 4630 series                                              | 2         | 0.68%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 40        | 54.05%  |
| Seiko Epson        | 19        | 25.68%  |
| Hewlett-Packard    | 9         | 12.16%  |
| Mustek Systems     | 4         | 5.41%   |
| Ultima Electronics | 1         | 1.35%   |
| Plustek            | 1         | 1.35%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 10        | 13.33%  |
| Canon CanoScan LiDE 210                                                               | 6         | 8%      |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 4         | 5.33%   |
| Canon CanoScan LiDE 120                                                               | 4         | 5.33%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 4%      |
| Canon CanoScan LiDE 100                                                               | 3         | 4%      |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 2         | 2.67%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2         | 2.67%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.67%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 2.67%   |
| HP Scanjet 200                                                                        | 2         | 2.67%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.67%   |
| Canon CanoScan LiDE 60                                                                | 2         | 2.67%   |
| Canon CanoScan LIDE 25                                                                | 2         | 2.67%   |
| Canon CanoScan LiDE 220                                                               | 2         | 2.67%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.33%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 1.33%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 1.33%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 1.33%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.33%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.33%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.33%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1         | 1.33%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.33%   |
| Seiko Epson ES-D400 [GT-S80]                                                          | 1         | 1.33%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.33%   |
| Plustek 600DPI USB Scanner                                                            | 1         | 1.33%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.33%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 1.33%   |
| HP Scanjet G2710                                                                      | 1         | 1.33%   |
| HP ScanJet 3800c                                                                      | 1         | 1.33%   |
| HP ScanJet 3570c                                                                      | 1         | 1.33%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.33%   |
| HP ScanJet 2400c                                                                      | 1         | 1.33%   |
| HP PSC 1200                                                                           | 1         | 1.33%   |
| HP HP4470C                                                                            | 1         | 1.33%   |
| Canon CanoScan LiDE 90                                                                | 1         | 1.33%   |
| Canon CanoScan LiDE 700F                                                              | 1         | 1.33%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.33%   |
| Canon CanoScan 4400F                                                                  | 1         | 1.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 989       | 23.36%  |
| IMC Networks                           | 451       | 10.65%  |
| Microdia                               | 315       | 7.44%   |
| Realtek Semiconductor                  | 293       | 6.92%   |
| Logitech                               | 207       | 4.89%   |
| Quanta                                 | 191       | 4.51%   |
| Suyin                                  | 181       | 4.27%   |
| Sunplus Innovation Technology          | 174       | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 162       | 3.83%   |
| Bison Electronics                      | 162       | 3.83%   |
| Acer                                   | 141       | 3.33%   |
| Apple                                  | 118       | 2.79%   |
| Syntek                                 | 96        | 2.27%   |
| Alcor Micro                            | 95        | 2.24%   |
| Lite-On Technology                     | 90        | 2.13%   |
| Luxvisions Innotech Limited            | 66        | 1.56%   |
| Microsoft                              | 64        | 1.51%   |
| Ricoh                                  | 48        | 1.13%   |
| Silicon Motion                         | 47        | 1.11%   |
| Z-Star Microelectronics                | 27        | 0.64%   |
| Samsung Electronics                    | 24        | 0.57%   |
| ARC International                      | 23        | 0.54%   |
| Trust                                  | 17        | 0.4%    |
| ALi                                    | 16        | 0.38%   |
| Primax Electronics                     | 15        | 0.35%   |
| Generalplus Technology                 | 15        | 0.35%   |
| KYE Systems (Mouse Systems)            | 11        | 0.26%   |
| icSpring                               | 11        | 0.26%   |
| GEMBIRD                                | 10        | 0.24%   |
| SunplusIT                              | 9         | 0.21%   |
| Sunplus Technology                     | 9         | 0.21%   |
| Lenovo                                 | 9         | 0.21%   |
| Cubeternet                             | 9         | 0.21%   |
| WaveRider Communications               | 8         | 0.19%   |
| Sunplus IT                             | 8         | 0.19%   |
| Sonix Technology                       | 8         | 0.19%   |
| Genesys Logic                          | 8         | 0.19%   |
| Importek                               | 7         | 0.17%   |
| Huawei Technologies                    | 6         | 0.14%   |
| DigiTech                               | 6         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 154       | 3.61%   |
| Microdia Integrated_Webcam_HD                           | 106       | 2.48%   |
| Chicony HD WebCam                                       | 96        | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 88        | 2.06%   |
| IMC Networks Integrated Camera                          | 74        | 1.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 71        | 1.66%   |
| Realtek Integrated_Webcam_HD                            | 67        | 1.57%   |
| Logitech Webcam C270                                    | 62        | 1.45%   |
| Syntek Integrated Camera                                | 50        | 1.17%   |
| Realtek USB Camera                                      | 45        | 1.05%   |
| Alcor Micro SHUNCCM2MP                                  | 45        | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                           | 44        | 1.03%   |
| Chicony USB2.0 HD UVC WebCam                            | 44        | 1.03%   |
| Acer Integrated Camera                                  | 43        | 1.01%   |
| Chicony HP Truevision HD                                | 42        | 0.98%   |
| Apple Built-in iSight                                   | 39        | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 37        | 0.87%   |
| Sunplus Integrated_Webcam_HD                            | 36        | 0.84%   |
| Quanta HP TrueVision HD Camera                          | 36        | 0.84%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 34        | 0.8%    |
| Bison Integrated Camera                                 | 33        | 0.77%   |
| Microdia Webcam Vitade AF                               | 32        | 0.75%   |
| Chicony HP Wide Vision HD Camera                        | 31        | 0.73%   |
| Chicony HP Truevision HD camera                         | 31        | 0.73%   |
| Chicony HP HD Camera                                    | 31        | 0.73%   |
| Chicony FJ Camera                                       | 30        | 0.7%    |
| Microsoft LifeCam HD-3000                               | 28        | 0.66%   |
| Chicony HP Webcam                                       | 28        | 0.66%   |
| Bison HD Webcam                                         | 28        | 0.66%   |
| IMC Networks ov9734_azurewave_camera                    | 27        | 0.63%   |
| Sunplus HD WebCam                                       | 26        | 0.61%   |
| Quanta HP Webcam                                        | 26        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 26        | 0.61%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.59%   |
| Logitech HD Pro Webcam C920                             | 25        | 0.59%   |
| Acer Lenovo EasyCamera                                  | 25        | 0.59%   |
| Suyin HP Truevision HD                                  | 24        | 0.56%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 24        | 0.56%   |
| Microdia Sonix USB 2.0 Camera                           | 23        | 0.54%   |
| Logitech Webcam C170                                    | 23        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 214       | 29.04%  |
| Synaptics                          | 186       | 25.24%  |
| Shenzhen Goodix Technology         | 124       | 16.82%  |
| Elan Microelectronics              | 84        | 11.4%   |
| Upek                               | 41        | 5.56%   |
| AuthenTec                          | 38        | 5.16%   |
| LighTuning Technology              | 37        | 5.02%   |
| STMicroelectronics                 | 6         | 0.81%   |
| Focal-systems.Corp                 | 4         | 0.54%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.27%   |
| Microsoft                          | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 86        | 11.67%  |
| Elan ELAN:ARM-M4                                                           | 56        | 7.6%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 5.97%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 5.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 4.88%   |
| Elan ELAN:Fingerprint                                                      | 28        | 3.8%    |
| Shenzhen Goodix Fingerprint Reader                                         | 27        | 3.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 26        | 3.53%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 23        | 3.12%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 2.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 2.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.58%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 18        | 2.44%   |
| Synaptics  WBDI                                                            | 18        | 2.44%   |
| Synaptics UWP WBDI                                                         | 17        | 2.31%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 15        | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 1.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.63%   |
| Validity Sensors VFS491                                                    | 11        | 1.49%   |
| Synaptics WBDI                                                             | 11        | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.49%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 1.49%   |
| Unknown                                                                    | 10        | 1.36%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.22%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 1.09%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.95%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 0.95%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.95%   |
| AuthenTec AES1600                                                          | 7         | 0.95%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.81%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.68%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.68%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 107       | 33.97%  |
| Alcor Micro               | 91        | 28.89%  |
| O2 Micro                  | 27        | 8.57%   |
| Advanced Card Systems     | 22        | 6.98%   |
| Lenovo                    | 16        | 5.08%   |
| Upek                      | 11        | 3.49%   |
| Bit4id                    | 11        | 3.49%   |
| Gemalto (was Gemplus)     | 8         | 2.54%   |
| Realtek Semiconductor     | 7         | 2.22%   |
| SCM Microsystems          | 4         | 1.27%   |
| OmniKey                   | 3         | 0.95%   |
| Clay Logic                | 3         | 0.95%   |
| Reiner SCT Kartensysteme  | 2         | 0.63%   |
| Microchip Technology      | 1         | 0.32%   |
| In Focus Systems          | 1         | 0.32%   |
| Fujitsu Siemens Computers | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 27.22%  |
| Broadcom BCM5880 Secure Applications Processor                               | 32        | 10.13%  |
| Broadcom 58200                                                               | 32        | 10.13%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 7.28%   |
| Broadcom 5880                                                                | 21        | 6.65%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 6.33%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 17        | 5.38%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.06%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 3.48%   |
| Bit4id miniLector EVO                                                        | 10        | 3.16%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 7         | 2.22%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.58%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.58%   |
| Advanced Card Systems ACR122U                                                | 5         | 1.58%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.95%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.95%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 2         | 0.63%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.63%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.32%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.32%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.32%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.32%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.32%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.32%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.32%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.32%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.32%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5016      | 70.98%  |
| 1     | 1645      | 23.28%  |
| 2     | 351       | 4.97%   |
| 3     | 36        | 0.51%   |
| 4     | 12        | 0.17%   |
| 5     | 5         | 0.07%   |
| 6     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 729       | 29.96%  |
| Graphics card            | 601       | 24.7%   |
| Net/wireless             | 292       | 12%     |
| Chipcard                 | 263       | 10.81%  |
| Multimedia controller    | 114       | 4.69%   |
| Camera                   | 82        | 3.37%   |
| Communication controller | 76        | 3.12%   |
| Bluetooth                | 63        | 2.59%   |
| Sound                    | 34        | 1.4%    |
| Unassigned class         | 31        | 1.27%   |
| Storage                  | 30        | 1.23%   |
| Modem                    | 23        | 0.95%   |
| Card reader              | 23        | 0.95%   |
| Flash memory             | 18        | 0.74%   |
| Net/ethernet             | 17        | 0.7%    |
| Network                  | 10        | 0.41%   |
| Dvb card                 | 6         | 0.25%   |
| Storage/raid             | 5         | 0.21%   |
| Firewire controller      | 5         | 0.21%   |
| Storage/ide              | 4         | 0.16%   |
| Wireless                 | 2         | 0.08%   |
| Video                    | 2         | 0.08%   |
| Tv card                  | 2         | 0.08%   |
| Storage/nvme             | 1         | 0.04%   |

