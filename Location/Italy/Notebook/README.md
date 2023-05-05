Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 5881

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| HP            | Compaq 6720s                | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| MSI           | Modern 14 B11MOU            | [6b3fcf3fcc](https://linux-hardware.org/?probe=6b3fcf3fcc) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [25d0c90e31](https://linux-hardware.org/?probe=25d0c90e31) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b6bd42eb71](https://linux-hardware.org/?probe=b6bd42eb71) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | Latitude E6400              | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Acer          | TravelMate 6593             | [58dce8147e](https://linux-hardware.org/?probe=58dce8147e) | Apr 26, 2023 |
| HP            | ENVY 15                     | [1f50420c44](https://linux-hardware.org/?probe=1f50420c44) | Apr 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [82bd4b0d20](https://linux-hardware.org/?probe=82bd4b0d20) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [50930ebe57](https://linux-hardware.org/?probe=50930ebe57) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [288f3f709c](https://linux-hardware.org/?probe=288f3f709c) | Apr 24, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Onda TLC      | ONDA Oliver                 | [c59dbdea18](https://linux-hardware.org/?probe=c59dbdea18) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Acer          | Swift SF314-43              | [b18f893905](https://linux-hardware.org/?probe=b18f893905) | Apr 23, 2023 |
| Toshiba       | Satellite Pro S500          | [fcf8a7bdb4](https://linux-hardware.org/?probe=fcf8a7bdb4) | Apr 23, 2023 |
| Dell          | Inspiron MP061              | [2b25a48030](https://linux-hardware.org/?probe=2b25a48030) | Apr 23, 2023 |
| Sony          | SVE1713X1EB                 | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5cceab0ac3](https://linux-hardware.org/?probe=5cceab0ac3) | Apr 22, 2023 |
| Apple         | MacBook6,1                  | [47ea666f74](https://linux-hardware.org/?probe=47ea666f74) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [9a23d08368](https://linux-hardware.org/?probe=9a23d08368) | Apr 21, 2023 |
| HP            | Compaq 6735s                | [6b255d5f07](https://linux-hardware.org/?probe=6b255d5f07) | Apr 21, 2023 |
| HP            | Pavilion Sleekbook 15       | [644ea805a9](https://linux-hardware.org/?probe=644ea805a9) | Apr 21, 2023 |
| Acer          | Swift SF114-32              | [7641434e4d](https://linux-hardware.org/?probe=7641434e4d) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [aace924665](https://linux-hardware.org/?probe=aace924665) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Lenovo        | G50-45 80E3                 | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| ASUSTek       | 1011PX                      | [6aa9d32dda](https://linux-hardware.org/?probe=6aa9d32dda) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9df9b0d25d](https://linux-hardware.org/?probe=9df9b0d25d) | Apr 19, 2023 |
| HP            | Pavilion x2 Detachable      | [1c7cd2fe1d](https://linux-hardware.org/?probe=1c7cd2fe1d) | Apr 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [9db7166b25](https://linux-hardware.org/?probe=9db7166b25) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| PC Special... | PCx0Dx                      | [0f82987a84](https://linux-hardware.org/?probe=0f82987a84) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Toshiba       | Kronos 10CUG                | [228e28e6a8](https://linux-hardware.org/?probe=228e28e6a8) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Toshiba       | Satellite Pro C850-1J2      | [e5c63957a2](https://linux-hardware.org/?probe=e5c63957a2) | Apr 18, 2023 |
| HP            | Pavilion x2 Detachable      | [5d56d95ea5](https://linux-hardware.org/?probe=5d56d95ea5) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| Apple         | MacBookPro8,1               | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| HP            | EliteBook 8570w             | [317efe55c2](https://linux-hardware.org/?probe=317efe55c2) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [877464f534](https://linux-hardware.org/?probe=877464f534) | Apr 17, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [650deb855e](https://linux-hardware.org/?probe=650deb855e) | Apr 17, 2023 |
| Medion        | E16401                      | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Acer          | Swift SF314-41              | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [40ec2e0cba](https://linux-hardware.org/?probe=40ec2e0cba) | Apr 16, 2023 |
| MAXDATA       | o.max_5xs                   | [cb90c411ca](https://linux-hardware.org/?probe=cb90c411ca) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| Google        | Dragonair                   | [be10ee5035](https://linux-hardware.org/?probe=be10ee5035) | Apr 15, 2023 |
| Google        | Dragonair                   | [cb2aa57d07](https://linux-hardware.org/?probe=cb2aa57d07) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [8ca60a45fe](https://linux-hardware.org/?probe=8ca60a45fe) | Apr 15, 2023 |
| Dell          | Inspiron 5570               | [d582f92277](https://linux-hardware.org/?probe=d582f92277) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [a51b096e12](https://linux-hardware.org/?probe=a51b096e12) | Apr 15, 2023 |
| HP            | Pavilion 15                 | [1f524a54fc](https://linux-hardware.org/?probe=1f524a54fc) | Apr 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b60b4dbb07](https://linux-hardware.org/?probe=b60b4dbb07) | Apr 14, 2023 |
| Dell          | Latitude 9420               | [529aa83bbc](https://linux-hardware.org/?probe=529aa83bbc) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | [6522f4e2dc](https://linux-hardware.org/?probe=6522f4e2dc) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [6af1f492c4](https://linux-hardware.org/?probe=6af1f492c4) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| MAXDATA       | o.max_5xs                   | [81a407c1d5](https://linux-hardware.org/?probe=81a407c1d5) | Apr 13, 2023 |
| Lenovo        | V15-IGL 82C3                | [3b24daf87d](https://linux-hardware.org/?probe=3b24daf87d) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| Toshiba       | Satellite Pro S500          | [44dca3cd92](https://linux-hardware.org/?probe=44dca3cd92) | Apr 13, 2023 |
| Dell          | XPS 9315                    | [20fa2b86b9](https://linux-hardware.org/?probe=20fa2b86b9) | Apr 12, 2023 |
| Acer          | Aspire A715-42G             | [54a72d7d55](https://linux-hardware.org/?probe=54a72d7d55) | Apr 12, 2023 |
| Packard Be... | EasyNote_MX45               | [95935443c0](https://linux-hardware.org/?probe=95935443c0) | Apr 11, 2023 |
| Lenovo        | ThinkPad L530 24783B3       | [9cb172cc6b](https://linux-hardware.org/?probe=9cb172cc6b) | Apr 11, 2023 |
| HP            | ProBook 650 G1              | [1a09ecfcd1](https://linux-hardware.org/?probe=1a09ecfcd1) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [dae979ddc0](https://linux-hardware.org/?probe=dae979ddc0) | Apr 11, 2023 |
| BESSTAR Te... | X400                        | [6b1587e21d](https://linux-hardware.org/?probe=6b1587e21d) | Apr 11, 2023 |
| HP            | Pavilion Sleekbook 15       | [e6e26b16f3](https://linux-hardware.org/?probe=e6e26b16f3) | Apr 11, 2023 |
| ASUSTek       | X541UV                      | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [649a715fba](https://linux-hardware.org/?probe=649a715fba) | Apr 10, 2023 |
| HP            | Laptop 15s-fq5xxx           | [39c6b4afbe](https://linux-hardware.org/?probe=39c6b4afbe) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| Apple         | MacBookPro11,5              | [2e428c73dc](https://linux-hardware.org/?probe=2e428c73dc) | Apr 10, 2023 |
| ASUSTek       | K52Jc                       | [0e6d01e44d](https://linux-hardware.org/?probe=0e6d01e44d) | Apr 09, 2023 |
| Lenovo        | V14-ADA 82C6                | [23a244aaf4](https://linux-hardware.org/?probe=23a244aaf4) | Apr 09, 2023 |
| AMI           | Intel                       | [f35d255c12](https://linux-hardware.org/?probe=f35d255c12) | Apr 09, 2023 |
| ASUSTek       | K52Jc                       | [594a8d9a89](https://linux-hardware.org/?probe=594a8d9a89) | Apr 08, 2023 |
| HP            | EliteBook 2560p             | [a4b27a5659](https://linux-hardware.org/?probe=a4b27a5659) | Apr 08, 2023 |
| Sony          | VPCSE1V9E                   | [e6dd1647f3](https://linux-hardware.org/?probe=e6dd1647f3) | Apr 08, 2023 |
| Lenovo        | Z50-75 80EC                 | [1502ff1933](https://linux-hardware.org/?probe=1502ff1933) | Apr 08, 2023 |
| MSI           | Katana GF66 12UC            | [5d0c8cade6](https://linux-hardware.org/?probe=5d0c8cade6) | Apr 08, 2023 |
| Lenovo        | ThinkPad L430 24683NG       | [d5f226c56f](https://linux-hardware.org/?probe=d5f226c56f) | Apr 08, 2023 |
| HP            | Pavilion dv7                | [3a159264b1](https://linux-hardware.org/?probe=3a159264b1) | Apr 07, 2023 |
| HP            | Pavilion dv7                | [3ec1e98abd](https://linux-hardware.org/?probe=3ec1e98abd) | Apr 07, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [1e9120783f](https://linux-hardware.org/?probe=1e9120783f) | Apr 07, 2023 |
| HP            | 250 G6 Notebook PC          | [859f83bbfc](https://linux-hardware.org/?probe=859f83bbfc) | Apr 07, 2023 |
| HP            | G61                         | [8eec217a3a](https://linux-hardware.org/?probe=8eec217a3a) | Apr 07, 2023 |
| HP            | G61                         | [d00ad3f0fb](https://linux-hardware.org/?probe=d00ad3f0fb) | Apr 07, 2023 |
| Lenovo        | B51-80 80LM                 | [78e2e080ea](https://linux-hardware.org/?probe=78e2e080ea) | Apr 07, 2023 |
| System76      | Oryx Pro                    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| HP            | 250 G4                      | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [bf0fc7e5d1](https://linux-hardware.org/?probe=bf0fc7e5d1) | Apr 06, 2023 |
| Dell          | XPS 9320                    | [ff14e0074a](https://linux-hardware.org/?probe=ff14e0074a) | Apr 06, 2023 |
| Dell          | XPS 13 9380                 | [58e0aa6707](https://linux-hardware.org/?probe=58e0aa6707) | Apr 06, 2023 |
| Acer          | Aspire 5750G                | [3fa6f0de7a](https://linux-hardware.org/?probe=3fa6f0de7a) | Apr 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2X60S    | [b5b5fd68e9](https://linux-hardware.org/?probe=b5b5fd68e9) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| Lenovo        | ThinkPad X61s 7666WJ5       | [eb755a4a95](https://linux-hardware.org/?probe=eb755a4a95) | Apr 05, 2023 |
| Fujitsu       | LIFEBOOK U759               | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| Dell          | Latitude 5591               | [aa2f4e4208](https://linux-hardware.org/?probe=aa2f4e4208) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| ASUSTek       | S551LB                      | [cd1746937a](https://linux-hardware.org/?probe=cd1746937a) | Apr 04, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [93fa18f474](https://linux-hardware.org/?probe=93fa18f474) | Apr 03, 2023 |
| Lenovo        | ThinkPad L490 20Q6S90C00    | [915c34d052](https://linux-hardware.org/?probe=915c34d052) | Apr 03, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [cef60ea315](https://linux-hardware.org/?probe=cef60ea315) | Apr 03, 2023 |
| Lenovo        | ThinkPad X200 7459J74       | [d7f98c1ddb](https://linux-hardware.org/?probe=d7f98c1ddb) | Apr 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fc89f163b0](https://linux-hardware.org/?probe=fc89f163b0) | Apr 03, 2023 |
| Lenovo        | B50-30 80ES                 | [11da2097ba](https://linux-hardware.org/?probe=11da2097ba) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [f995b3a81f](https://linux-hardware.org/?probe=f995b3a81f) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Packard Be... | EasyNote TJ65               | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| ASUSTek       | X555LAB                     | [95f5025351](https://linux-hardware.org/?probe=95f5025351) | Apr 02, 2023 |
| Lenovo        | B50-30 80ES                 | [a971008720](https://linux-hardware.org/?probe=a971008720) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Acer          | Aspire A515-41G             | [f047e9361c](https://linux-hardware.org/?probe=f047e9361c) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [db058df07b](https://linux-hardware.org/?probe=db058df07b) | Apr 01, 2023 |
| Lenovo        | V110-15ISK 80TL             | [3691be13e8](https://linux-hardware.org/?probe=3691be13e8) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [70fb59cd4f](https://linux-hardware.org/?probe=70fb59cd4f) | Apr 01, 2023 |
| Unknown       | Unknown                     | [702a241ca6](https://linux-hardware.org/?probe=702a241ca6) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Notebook                    | [7cb279c8e0](https://linux-hardware.org/?probe=7cb279c8e0) | Apr 01, 2023 |
| HP            | Pavilion x2 Detachable      | [363d925d25](https://linux-hardware.org/?probe=363d925d25) | Apr 01, 2023 |
| ASUSTek       | X556UAK                     | [24f79c68f6](https://linux-hardware.org/?probe=24f79c68f6) | Mar 31, 2023 |
| Notebook      | W54_55SU1,SUW               | [74313ae73b](https://linux-hardware.org/?probe=74313ae73b) | Mar 31, 2023 |
| Microtech     | ebookPro                    | [ffe1da27cc](https://linux-hardware.org/?probe=ffe1da27cc) | Mar 31, 2023 |
| Acer          | Extensa 215-31              | [b1601e6747](https://linux-hardware.org/?probe=b1601e6747) | Mar 31, 2023 |
| Dell          | Latitude E7440              | [fdd9fda693](https://linux-hardware.org/?probe=fdd9fda693) | Mar 31, 2023 |
| HP            | Pavilion 15                 | [4dc2c9dfc1](https://linux-hardware.org/?probe=4dc2c9dfc1) | Mar 31, 2023 |
| Lenovo        | ThinkPad E14 20RA0016IX     | [685f18f5b3](https://linux-hardware.org/?probe=685f18f5b3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| Valve         | Jupiter                     | [34766581f3](https://linux-hardware.org/?probe=34766581f3) | Mar 31, 2023 |
| Toshiba       | Satellite Pro S500          | [b2e60d9170](https://linux-hardware.org/?probe=b2e60d9170) | Mar 31, 2023 |
| ASUSTek       | N552VX                      | [cacf95c277](https://linux-hardware.org/?probe=cacf95c277) | Mar 30, 2023 |
| Acer          | Aspire ES1-523              | [a800dab0ab](https://linux-hardware.org/?probe=a800dab0ab) | Mar 30, 2023 |
| Sony          | SVE1713X1EB                 | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [45f39402f0](https://linux-hardware.org/?probe=45f39402f0) | Mar 30, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| Dell          | Precision 3560              | [f6ef5c1a2c](https://linux-hardware.org/?probe=f6ef5c1a2c) | Mar 30, 2023 |
| Lenovo        | G505 20240                  | [25c5c7ee2e](https://linux-hardware.org/?probe=25c5c7ee2e) | Mar 30, 2023 |
| Toshiba       | Satellite L655              | [2e6ea8bf5c](https://linux-hardware.org/?probe=2e6ea8bf5c) | Mar 30, 2023 |
| Dell          | Latitude 5580               | [84157deda8](https://linux-hardware.org/?probe=84157deda8) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6f28f9e6ec](https://linux-hardware.org/?probe=6f28f9e6ec) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| Lenovo        | G50-45 80E3                 | [7bfed0aedd](https://linux-hardware.org/?probe=7bfed0aedd) | Mar 29, 2023 |
| HP            | Laptop 15-dw0xxx            | [53bc341050](https://linux-hardware.org/?probe=53bc341050) | Mar 29, 2023 |
| Valve         | Jupiter                     | [889e4e5eef](https://linux-hardware.org/?probe=889e4e5eef) | Mar 29, 2023 |
| HP            | ProBook 640 G1              | [c9ac2eb353](https://linux-hardware.org/?probe=c9ac2eb353) | Mar 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [5520b0fc5f](https://linux-hardware.org/?probe=5520b0fc5f) | Mar 28, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | [f44d26ed76](https://linux-hardware.org/?probe=f44d26ed76) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| HP            | ProBook 450 G7              | [8b27d78a17](https://linux-hardware.org/?probe=8b27d78a17) | Mar 28, 2023 |
| Dell          | Inspiron 16 5630            | [5838554410](https://linux-hardware.org/?probe=5838554410) | Mar 28, 2023 |
| ASUSTek       | N53SV                       | [77aa77b2a3](https://linux-hardware.org/?probe=77aa77b2a3) | Mar 28, 2023 |
| Unknown       | Unknown                     | [26d819f9fc](https://linux-hardware.org/?probe=26d819f9fc) | Mar 27, 2023 |
| HP            | 250 G1                      | [75cf798dde](https://linux-hardware.org/?probe=75cf798dde) | Mar 27, 2023 |
| Sony          | SVE1713X1EB                 | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [2f96abf16a](https://linux-hardware.org/?probe=2f96abf16a) | Mar 27, 2023 |
| Dell          | XPS 13 9305                 | [07caea9176](https://linux-hardware.org/?probe=07caea9176) | Mar 27, 2023 |
| Acer          | Mammoth                     | [d43ab9891b](https://linux-hardware.org/?probe=d43ab9891b) | Mar 27, 2023 |
| Sony          | VPCEH1S1E                   | [081294b14c](https://linux-hardware.org/?probe=081294b14c) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| ASUSTek       | X550LD                      | [6ac498fa82](https://linux-hardware.org/?probe=6ac498fa82) | Mar 26, 2023 |
| ASUSTek       | N552VW                      | [322426698a](https://linux-hardware.org/?probe=322426698a) | Mar 26, 2023 |
| Apple         | MacBookPro11,5              | [0c2be4a34c](https://linux-hardware.org/?probe=0c2be4a34c) | Mar 26, 2023 |
| Dell          | XPS 13 9305                 | [5b29fbd6ac](https://linux-hardware.org/?probe=5b29fbd6ac) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| HP            | Laptop 15-dw3xxx            | [3b8cd70b69](https://linux-hardware.org/?probe=3b8cd70b69) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Lenovo        | V130-15IKB 81HN             | [0bfaf1252f](https://linux-hardware.org/?probe=0bfaf1252f) | Mar 25, 2023 |
| Dell          | Latitude E6230              | [1a248bdc33](https://linux-hardware.org/?probe=1a248bdc33) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| ASUSTek       | GL503VS                     | [8e066fcf6e](https://linux-hardware.org/?probe=8e066fcf6e) | Mar 25, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | XPS 13 9305                 | [c7e354ffe3](https://linux-hardware.org/?probe=c7e354ffe3) | Mar 24, 2023 |
| Apple         | MacBookPro11,5              | [9fd6508caf](https://linux-hardware.org/?probe=9fd6508caf) | Mar 24, 2023 |
| Dell          | Latitude 5580               | [d4ad4c55a6](https://linux-hardware.org/?probe=d4ad4c55a6) | Mar 24, 2023 |
| ASUSTek       | K53SJ                       | [175f99ccdd](https://linux-hardware.org/?probe=175f99ccdd) | Mar 23, 2023 |
| Acer          | Aspire E3-112               | [721e804a03](https://linux-hardware.org/?probe=721e804a03) | Mar 23, 2023 |
| HUAWEI        | BOD-WXX9                    | [088494906d](https://linux-hardware.org/?probe=088494906d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Dell          | Inspiron 1750               | [007a0b3bb7](https://linux-hardware.org/?probe=007a0b3bb7) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Toshiba       | Satellite Pro S500          | [2bb2519c2c](https://linux-hardware.org/?probe=2bb2519c2c) | Mar 21, 2023 |
| Toshiba       | Satellite Pro S500          | [a45c7086e5](https://linux-hardware.org/?probe=a45c7086e5) | Mar 21, 2023 |
| Dell          | XPS 15 9570                 | [6fc76628d3](https://linux-hardware.org/?probe=6fc76628d3) | Mar 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [b4d5442d02](https://linux-hardware.org/?probe=b4d5442d02) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [6d96576431](https://linux-hardware.org/?probe=6d96576431) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| Acer          | Extensa 5235                | [270cd6ed83](https://linux-hardware.org/?probe=270cd6ed83) | Mar 20, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [762762da77](https://linux-hardware.org/?probe=762762da77) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Notebook      | P15SM                       | [00d7786f9f](https://linux-hardware.org/?probe=00d7786f9f) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | G62                         | [2cb4092da0](https://linux-hardware.org/?probe=2cb4092da0) | Mar 19, 2023 |
| HP            | G62                         | [76d7e36f21](https://linux-hardware.org/?probe=76d7e36f21) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cbad8c5f1e](https://linux-hardware.org/?probe=cbad8c5f1e) | Mar 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS6PN0... | [bb86a34180](https://linux-hardware.org/?probe=bb86a34180) | Mar 18, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| HP            | Laptop 15-dw1xxx            | [63ecda6230](https://linux-hardware.org/?probe=63ecda6230) | Mar 18, 2023 |
| HP            | ProBook 6570b               | [f5c9cd8419](https://linux-hardware.org/?probe=f5c9cd8419) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | K61IC                       | [045474725b](https://linux-hardware.org/?probe=045474725b) | Mar 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S88M0... | [2ad89b7995](https://linux-hardware.org/?probe=2ad89b7995) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [6a1e908693](https://linux-hardware.org/?probe=6a1e908693) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Dell          | Latitude E5470              | [cc4f08349d](https://linux-hardware.org/?probe=cc4f08349d) | Mar 16, 2023 |
| MSI           | Modern 14 B11MOL            | [33bbc272c0](https://linux-hardware.org/?probe=33bbc272c0) | Mar 15, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c454542aaa](https://linux-hardware.org/?probe=c454542aaa) | Mar 15, 2023 |
| Valve         | Jupiter                     | [fc387a787e](https://linux-hardware.org/?probe=fc387a787e) | Mar 15, 2023 |
| Toshiba       | Satellite Pro S500          | [0065669867](https://linux-hardware.org/?probe=0065669867) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b0b311216d](https://linux-hardware.org/?probe=b0b311216d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [0f6370d7f7](https://linux-hardware.org/?probe=0f6370d7f7) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [d9f9e09a41](https://linux-hardware.org/?probe=d9f9e09a41) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [be16fd4aab](https://linux-hardware.org/?probe=be16fd4aab) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| HP            | Pavilion dv6500             | [03097b6049](https://linux-hardware.org/?probe=03097b6049) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [ee01825196](https://linux-hardware.org/?probe=ee01825196) | Mar 13, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Acer          | aspire5740                  | [d5e64f31d4](https://linux-hardware.org/?probe=d5e64f31d4) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| Dell          | Latitude E6440              | [e5ba284442](https://linux-hardware.org/?probe=e5ba284442) | Mar 11, 2023 |
| HP            | G61                         | [2f5e9f6f43](https://linux-hardware.org/?probe=2f5e9f6f43) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| ASUSTek       | X556UQK                     | [e5c898a856](https://linux-hardware.org/?probe=e5c898a856) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4664479644](https://linux-hardware.org/?probe=4664479644) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| HP            | EliteBook 840 G1            | [1315898b67](https://linux-hardware.org/?probe=1315898b67) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [ffcc55bb14](https://linux-hardware.org/?probe=ffcc55bb14) | Mar 10, 2023 |
| Lenovo        | ThinkPad T460 20LPS3K002    | [c375b36f4a](https://linux-hardware.org/?probe=c375b36f4a) | Mar 10, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [420b463f4d](https://linux-hardware.org/?probe=420b463f4d) | Mar 10, 2023 |
| ASUSTek       | X540LA                      | [de3c24e686](https://linux-hardware.org/?probe=de3c24e686) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [041ebfc8c6](https://linux-hardware.org/?probe=041ebfc8c6) | Mar 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [780937bb9f](https://linux-hardware.org/?probe=780937bb9f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [ffbffb33ae](https://linux-hardware.org/?probe=ffbffb33ae) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [8faa1d14ca](https://linux-hardware.org/?probe=8faa1d14ca) | Mar 08, 2023 |
| Lenovo        | ThinkPad E490 20N9S21H00    | [0bb64aee2c](https://linux-hardware.org/?probe=0bb64aee2c) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Timi          | TM1701                      | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| HP            | Pavilion dv6                | [a1631eb10b](https://linux-hardware.org/?probe=a1631eb10b) | Mar 07, 2023 |
| Unknown       | Unknown                     | [fdc4f4d3c6](https://linux-hardware.org/?probe=fdc4f4d3c6) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | [f56dc75b4e](https://linux-hardware.org/?probe=f56dc75b4e) | Mar 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [16c33be9a3](https://linux-hardware.org/?probe=16c33be9a3) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| Acer          | Aspire E5-575G              | [fd8c378fda](https://linux-hardware.org/?probe=fd8c378fda) | Mar 07, 2023 |
| ASUSTek       | X556UAK                     | [51f2084195](https://linux-hardware.org/?probe=51f2084195) | Mar 06, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [745898b5de](https://linux-hardware.org/?probe=745898b5de) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [20fbc926fd](https://linux-hardware.org/?probe=20fbc926fd) | Mar 06, 2023 |
| Lenovo        | G50-45 80E3                 | [02dfdb807e](https://linux-hardware.org/?probe=02dfdb807e) | Mar 06, 2023 |
| HP            | G72                         | [64009d0874](https://linux-hardware.org/?probe=64009d0874) | Mar 06, 2023 |
| HP            | ProBook 430 G5              | [aaebada0ca](https://linux-hardware.org/?probe=aaebada0ca) | Mar 06, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Apple         | MacBookPro10,1              | [7b7aa513b8](https://linux-hardware.org/?probe=7b7aa513b8) | Mar 04, 2023 |
| Toshiba       | NB550D                      | [8ba5171640](https://linux-hardware.org/?probe=8ba5171640) | Mar 04, 2023 |
| HP            | G72                         | [a094ef43f1](https://linux-hardware.org/?probe=a094ef43f1) | Mar 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4816618219](https://linux-hardware.org/?probe=4816618219) | Mar 04, 2023 |
| Dell          | Inspiron 16 7610            | [1121d93a65](https://linux-hardware.org/?probe=1121d93a65) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [71f2f93645](https://linux-hardware.org/?probe=71f2f93645) | Mar 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [13fc723c9e](https://linux-hardware.org/?probe=13fc723c9e) | Mar 04, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [1a0011a745](https://linux-hardware.org/?probe=1a0011a745) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [bef62e57b0](https://linux-hardware.org/?probe=bef62e57b0) | Mar 03, 2023 |
| HUAWEI        | CREF-XX                     | [b42f1c3f6b](https://linux-hardware.org/?probe=b42f1c3f6b) | Mar 03, 2023 |
| HP            | ENVY 15                     | [9ceefd9a22](https://linux-hardware.org/?probe=9ceefd9a22) | Mar 03, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [17f1328add](https://linux-hardware.org/?probe=17f1328add) | Mar 03, 2023 |
| HP            | ENVY dv6                    | [357b5b3506](https://linux-hardware.org/?probe=357b5b3506) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [f791caa732](https://linux-hardware.org/?probe=f791caa732) | Mar 03, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | EliteBook 830 G5            | [cd6c75d08e](https://linux-hardware.org/?probe=cd6c75d08e) | Mar 03, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Apple         | MacBookAir6,2               | [0b39498d52](https://linux-hardware.org/?probe=0b39498d52) | Mar 03, 2023 |
| GMK           | NucBox2                     | [84af5a7d53](https://linux-hardware.org/?probe=84af5a7d53) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [c34c6d8786](https://linux-hardware.org/?probe=c34c6d8786) | Mar 02, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [2a1515aaa3](https://linux-hardware.org/?probe=2a1515aaa3) | Mar 02, 2023 |
| Acer          | TravelMate P253             | [aa56b7749c](https://linux-hardware.org/?probe=aa56b7749c) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| Acer          | Aspire 5755G                | [c1594b1f9d](https://linux-hardware.org/?probe=c1594b1f9d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [98e86d41d1](https://linux-hardware.org/?probe=98e86d41d1) | Mar 01, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [61fe88e268](https://linux-hardware.org/?probe=61fe88e268) | Mar 01, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [6a99428156](https://linux-hardware.org/?probe=6a99428156) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | Pavilion 15                 | [78f570552a](https://linux-hardware.org/?probe=78f570552a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [456504fe92](https://linux-hardware.org/?probe=456504fe92) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [b518eb9925](https://linux-hardware.org/?probe=b518eb9925) | Feb 28, 2023 |
| HUAWEI        | MRC-WX0                     | [e2776f99bf](https://linux-hardware.org/?probe=e2776f99bf) | Feb 28, 2023 |
| Acer          | Aspire 5750G                | [34b5806bcf](https://linux-hardware.org/?probe=34b5806bcf) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| Acer          | Aspire E1-531               | [a52b94c2d5](https://linux-hardware.org/?probe=a52b94c2d5) | Feb 27, 2023 |
| Getac         | V200-X                      | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [2cea6ee649](https://linux-hardware.org/?probe=2cea6ee649) | Feb 26, 2023 |
| ASUSTek       | X540NA                      | [8bca0d4eb5](https://linux-hardware.org/?probe=8bca0d4eb5) | Feb 26, 2023 |
| Timi          | TM1612                      | [eb4a3f330e](https://linux-hardware.org/?probe=eb4a3f330e) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| ASUSTek       | T100HAN                     | [bde9736ffd](https://linux-hardware.org/?probe=bde9736ffd) | Feb 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [84750f9d96](https://linux-hardware.org/?probe=84750f9d96) | Feb 25, 2023 |
| Acer          | Aspire A515-51G             | [432235c684](https://linux-hardware.org/?probe=432235c684) | Feb 25, 2023 |
| Acer          | Aspire ES1-521              | [e5f0a23afd](https://linux-hardware.org/?probe=e5f0a23afd) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| HP            | 250 G3                      | [6a3d2238ba](https://linux-hardware.org/?probe=6a3d2238ba) | Feb 25, 2023 |
| ASUSTek       | T100HAN                     | [fd75fdb59f](https://linux-hardware.org/?probe=fd75fdb59f) | Feb 25, 2023 |
| ASUSTek       | X556URK                     | [fc80e01794](https://linux-hardware.org/?probe=fc80e01794) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| BESSTAR Te... | X400                        | [e1c05e0782](https://linux-hardware.org/?probe=e1c05e0782) | Feb 25, 2023 |
| HP            | ENVY 17                     | [08db7a8be2](https://linux-hardware.org/?probe=08db7a8be2) | Feb 25, 2023 |
| HP            | ENVY 17                     | [0ad15a7e01](https://linux-hardware.org/?probe=0ad15a7e01) | Feb 25, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| HONOR         | HYM-WXX                     | [c6f84d1224](https://linux-hardware.org/?probe=c6f84d1224) | Feb 24, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [f24e6a55c4](https://linux-hardware.org/?probe=f24e6a55c4) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Fujitsu       | LIFEBOOK U749               | [ba7cdc6018](https://linux-hardware.org/?probe=ba7cdc6018) | Feb 24, 2023 |
| ASUSTek       | X555LA                      | [502020fe52](https://linux-hardware.org/?probe=502020fe52) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| ASUSTek       | X510UQR                     | [075081e4ad](https://linux-hardware.org/?probe=075081e4ad) | Feb 24, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [ac2d78d240](https://linux-hardware.org/?probe=ac2d78d240) | Feb 24, 2023 |
| Acer          | Aspire E1-531               | [4526585d29](https://linux-hardware.org/?probe=4526585d29) | Feb 24, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [a8fbcbec0e](https://linux-hardware.org/?probe=a8fbcbec0e) | Feb 23, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [cddc383ff9](https://linux-hardware.org/?probe=cddc383ff9) | Feb 23, 2023 |
| Acer          | Aspire SW3-013              | [771b90caaa](https://linux-hardware.org/?probe=771b90caaa) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [dbbcb7502c](https://linux-hardware.org/?probe=dbbcb7502c) | Feb 23, 2023 |
| Dell          | Latitude 5530               | [d620cdcce0](https://linux-hardware.org/?probe=d620cdcce0) | Feb 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [0f5352f94f](https://linux-hardware.org/?probe=0f5352f94f) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| Dell          | Latitude 7300               | [c4bb27e884](https://linux-hardware.org/?probe=c4bb27e884) | Feb 23, 2023 |
| Acer          | TravelMate P253             | [b99414b6de](https://linux-hardware.org/?probe=b99414b6de) | Feb 23, 2023 |
| HP            | Pavilion g6                 | [c76844f9a1](https://linux-hardware.org/?probe=c76844f9a1) | Feb 22, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [7d3442e2a7](https://linux-hardware.org/?probe=7d3442e2a7) | Feb 22, 2023 |
| ASUSTek       | X555DG                      | [5e7abe271f](https://linux-hardware.org/?probe=5e7abe271f) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [99d4f0df73](https://linux-hardware.org/?probe=99d4f0df73) | Feb 22, 2023 |
| ASUSTek       | X555LA                      | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [71928c5a75](https://linux-hardware.org/?probe=71928c5a75) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [57e007d035](https://linux-hardware.org/?probe=57e007d035) | Feb 22, 2023 |
| HP            | ENVY 17                     | [f705060f1e](https://linux-hardware.org/?probe=f705060f1e) | Feb 22, 2023 |
| HP            | ENVY 17                     | [bf86e7904b](https://linux-hardware.org/?probe=bf86e7904b) | Feb 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [05f20bac2d](https://linux-hardware.org/?probe=05f20bac2d) | Feb 21, 2023 |
| HP            | Pavilion dv6                | [526430f218](https://linux-hardware.org/?probe=526430f218) | Feb 21, 2023 |
| Acer          | Aspire SW3-013              | [f0111df214](https://linux-hardware.org/?probe=f0111df214) | Feb 21, 2023 |
| BESSTAR Te... | X400                        | [f7f9004058](https://linux-hardware.org/?probe=f7f9004058) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| Unknown       | Unknown                     | [46d473b3e5](https://linux-hardware.org/?probe=46d473b3e5) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [3a525ce932](https://linux-hardware.org/?probe=3a525ce932) | Feb 21, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [f845d181ec](https://linux-hardware.org/?probe=f845d181ec) | Feb 20, 2023 |
| ASUSTek       | X555LPB                     | [29eb95639c](https://linux-hardware.org/?probe=29eb95639c) | Feb 20, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [ec529ac1bd](https://linux-hardware.org/?probe=ec529ac1bd) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0BY0... | [56c81f1044](https://linux-hardware.org/?probe=56c81f1044) | Feb 20, 2023 |
| HP            | EliteBook 8570w             | [a6fd2ffc5b](https://linux-hardware.org/?probe=a6fd2ffc5b) | Feb 20, 2023 |
| HP            | ProBook 650 G1              | [4e6687829e](https://linux-hardware.org/?probe=4e6687829e) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [51d702d217](https://linux-hardware.org/?probe=51d702d217) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Dell          | Inspiron 7520               | [1489b9779a](https://linux-hardware.org/?probe=1489b9779a) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | [84e519800c](https://linux-hardware.org/?probe=84e519800c) | Feb 19, 2023 |
| ASUSTek       | X555LA                      | [2ffc7c4a96](https://linux-hardware.org/?probe=2ffc7c4a96) | Feb 19, 2023 |
| Packard Be... | EasyNote TJ65               | [2c98b99901](https://linux-hardware.org/?probe=2c98b99901) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1104c148d1](https://linux-hardware.org/?probe=1104c148d1) | Feb 19, 2023 |
| Dell          | Latitude 5480               | [e288a18f9d](https://linux-hardware.org/?probe=e288a18f9d) | Feb 18, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [eb9f3822a0](https://linux-hardware.org/?probe=eb9f3822a0) | Feb 18, 2023 |
| HP            | 255 G8 Notebook PC          | [ecf73f400b](https://linux-hardware.org/?probe=ecf73f400b) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [cadd20aaff](https://linux-hardware.org/?probe=cadd20aaff) | Feb 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [355838f8b2](https://linux-hardware.org/?probe=355838f8b2) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [01a17523fa](https://linux-hardware.org/?probe=01a17523fa) | Feb 18, 2023 |
| Acer          | Aspire A515-45              | [6b59c75dec](https://linux-hardware.org/?probe=6b59c75dec) | Feb 18, 2023 |
| Jumper        | EZbook                      | [35f7c6a28a](https://linux-hardware.org/?probe=35f7c6a28a) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [7360e6e667](https://linux-hardware.org/?probe=7360e6e667) | Feb 17, 2023 |
| Dell          | Latitude E6440              | [96e9e43a2e](https://linux-hardware.org/?probe=96e9e43a2e) | Feb 17, 2023 |
| Getac         | V200-X                      | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e4483255db](https://linux-hardware.org/?probe=e4483255db) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [b29933336d](https://linux-hardware.org/?probe=b29933336d) | Feb 17, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [d97ee3d7d1](https://linux-hardware.org/?probe=d97ee3d7d1) | Feb 17, 2023 |
| Acer          | Aspire E5-571G              | [7a47fab9f3](https://linux-hardware.org/?probe=7a47fab9f3) | Feb 17, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e84edd71e7](https://linux-hardware.org/?probe=e84edd71e7) | Feb 17, 2023 |
| HP            | Pavilion 15                 | [a48098f6fc](https://linux-hardware.org/?probe=a48098f6fc) | Feb 17, 2023 |
| HP            | EliteBook 840 G3            | [f8b182d99b](https://linux-hardware.org/?probe=f8b182d99b) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [85fd62f731](https://linux-hardware.org/?probe=85fd62f731) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [7d6dcd9cd1](https://linux-hardware.org/?probe=7d6dcd9cd1) | Feb 16, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [4b6268364f](https://linux-hardware.org/?probe=4b6268364f) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Acer          | Swift SF314-59              | [fcf01071e5](https://linux-hardware.org/?probe=fcf01071e5) | Feb 15, 2023 |
| HP            | Notebook                    | [21442c303e](https://linux-hardware.org/?probe=21442c303e) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [56ee76d678](https://linux-hardware.org/?probe=56ee76d678) | Feb 15, 2023 |
| ASUSTek       | X553MA                      | [1f8387dde4](https://linux-hardware.org/?probe=1f8387dde4) | Feb 15, 2023 |
| ASUSTek       | F6A                         | [3660446fe5](https://linux-hardware.org/?probe=3660446fe5) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [28ac8fee12](https://linux-hardware.org/?probe=28ac8fee12) | Feb 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dddbb2d135](https://linux-hardware.org/?probe=dddbb2d135) | Feb 14, 2023 |
| Acer          | Aspire 7250G                | [5f5cec8261](https://linux-hardware.org/?probe=5f5cec8261) | Feb 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a3eb6fde29](https://linux-hardware.org/?probe=a3eb6fde29) | Feb 14, 2023 |
| HP            | ENVY 17                     | [d07a7a99de](https://linux-hardware.org/?probe=d07a7a99de) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| HP            | Laptop 15s-fq4xxx           | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| Acer          | Swift SF114-33              | [14cd72be0e](https://linux-hardware.org/?probe=14cd72be0e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Unknown       | Unknown                     | [23a611650b](https://linux-hardware.org/?probe=23a611650b) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [3cccebc1ef](https://linux-hardware.org/?probe=3cccebc1ef) | Feb 12, 2023 |
| HP            | ENVY 15                     | [efc0c8427a](https://linux-hardware.org/?probe=efc0c8427a) | Feb 12, 2023 |
| Lenovo        | ThinkPad L460 20FVS25H01    | [37383d8798](https://linux-hardware.org/?probe=37383d8798) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [c798855263](https://linux-hardware.org/?probe=c798855263) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [4b8e0e10e0](https://linux-hardware.org/?probe=4b8e0e10e0) | Feb 12, 2023 |
| HP            | Compaq 6720s                | [a23186bb63](https://linux-hardware.org/?probe=a23186bb63) | Feb 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0XX0... | [404cac8b60](https://linux-hardware.org/?probe=404cac8b60) | Feb 11, 2023 |
| Dell          | Vostro 15 3510              | [8291db193a](https://linux-hardware.org/?probe=8291db193a) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| HP            | ZBook 17 G3                 | [f0dff8ed53](https://linux-hardware.org/?probe=f0dff8ed53) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Dell          | XPS 15 9500                 | [11222774d3](https://linux-hardware.org/?probe=11222774d3) | Feb 10, 2023 |
| MSI           | Prestige 15 A11SCX          | [a82372e461](https://linux-hardware.org/?probe=a82372e461) | Feb 10, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | ZBook 17 G3                 | [bd09c6036f](https://linux-hardware.org/?probe=bd09c6036f) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [fd8d478a5b](https://linux-hardware.org/?probe=fd8d478a5b) | Feb 10, 2023 |
| Lenovo        | Yoga Slim 7 13ITL5 82CU     | [7f4c6d1757](https://linux-hardware.org/?probe=7f4c6d1757) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| HP            | 255 G4                      | [00870a3da9](https://linux-hardware.org/?probe=00870a3da9) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08f3d3b7d8](https://linux-hardware.org/?probe=08f3d3b7d8) | Feb 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [0cb6963914](https://linux-hardware.org/?probe=0cb6963914) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ce86509b6](https://linux-hardware.org/?probe=5ce86509b6) | Feb 08, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Google        | Grunt                       | [84ecb8aaf1](https://linux-hardware.org/?probe=84ecb8aaf1) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| HP            | ENVY 15                     | [641ce1347d](https://linux-hardware.org/?probe=641ce1347d) | Feb 08, 2023 |
| Acer          | Aspire E5-553               | [5e951ad06d](https://linux-hardware.org/?probe=5e951ad06d) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [0713732442](https://linux-hardware.org/?probe=0713732442) | Feb 07, 2023 |
| Google        | Grunt                       | [1bbc4ae776](https://linux-hardware.org/?probe=1bbc4ae776) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2347G7G       | [925017105d](https://linux-hardware.org/?probe=925017105d) | Feb 07, 2023 |
| HUAWEI        | MACH-WX9                    | [263101d492](https://linux-hardware.org/?probe=263101d492) | Feb 07, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [b7ab00ddb1](https://linux-hardware.org/?probe=b7ab00ddb1) | Feb 07, 2023 |
| MSI           | U90/U100                    | [f7dc915782](https://linux-hardware.org/?probe=f7dc915782) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | X550JF                      | [c8f1b71cfd](https://linux-hardware.org/?probe=c8f1b71cfd) | Feb 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0edeee4ba6](https://linux-hardware.org/?probe=0edeee4ba6) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| Acer          | Extensa 5635                | [8f8f4d24f9](https://linux-hardware.org/?probe=8f8f4d24f9) | Feb 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [762c097b3e](https://linux-hardware.org/?probe=762c097b3e) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Valve         | Jupiter                     | [8a1998f130](https://linux-hardware.org/?probe=8a1998f130) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| ASUSTek       | N55SF                       | [5b81cbed5f](https://linux-hardware.org/?probe=5b81cbed5f) | Feb 05, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [30676c5e14](https://linux-hardware.org/?probe=30676c5e14) | Feb 05, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [08bf9ddbcf](https://linux-hardware.org/?probe=08bf9ddbcf) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Acer          | Aspire E5-573G              | [b7760210a8](https://linux-hardware.org/?probe=b7760210a8) | Feb 05, 2023 |
| Notebook      | W25CSW                      | [b63184cd07](https://linux-hardware.org/?probe=b63184cd07) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| Acer          | TravelMate P253             | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| SiComputer    | Nauta 01C                   | [1579a837f7](https://linux-hardware.org/?probe=1579a837f7) | Feb 04, 2023 |
| Microtech     | CoreBook                    | [2ee0649a6e](https://linux-hardware.org/?probe=2ee0649a6e) | Feb 03, 2023 |
| Toshiba       | Satellite Pro S500          | [9274080d89](https://linux-hardware.org/?probe=9274080d89) | Feb 03, 2023 |
| HP            | ProBook 440 G7              | [f9a4f80656](https://linux-hardware.org/?probe=f9a4f80656) | Feb 03, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Acer          | Aspire F5-573G              | [ba43497e32](https://linux-hardware.org/?probe=ba43497e32) | Feb 02, 2023 |
| HP            | 250 G6 Notebook PC          | [a0b5d1c73c](https://linux-hardware.org/?probe=a0b5d1c73c) | Feb 02, 2023 |
| ASUSTek       | K54L                        | [8568b17267](https://linux-hardware.org/?probe=8568b17267) | Feb 02, 2023 |
| Dell          | XPS 13 7390                 | [f86eaa6db8](https://linux-hardware.org/?probe=f86eaa6db8) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Toshiba       | Satellite Pro S500          | [19a2c05804](https://linux-hardware.org/?probe=19a2c05804) | Feb 02, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Acer          | Aspire 5750G                | [a8a3f37ad8](https://linux-hardware.org/?probe=a8a3f37ad8) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| HP            | ENVY 15                     | [c688eb85bb](https://linux-hardware.org/?probe=c688eb85bb) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [8e8ae85d60](https://linux-hardware.org/?probe=8e8ae85d60) | Jan 31, 2023 |
| Dell          | XPS 15 9570                 | [ee60c1c921](https://linux-hardware.org/?probe=ee60c1c921) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Acer          | Aspire ES1-512              | [0d254e85dd](https://linux-hardware.org/?probe=0d254e85dd) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| Dell          | Precision 3560              | [3d5432deef](https://linux-hardware.org/?probe=3d5432deef) | Jan 30, 2023 |
| Dell          | Precision 3560              | [c250c935bd](https://linux-hardware.org/?probe=c250c935bd) | Jan 30, 2023 |
| Dell          | Precision 3571              | [55f371f4ef](https://linux-hardware.org/?probe=55f371f4ef) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [519a211655](https://linux-hardware.org/?probe=519a211655) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Acer          | Aspire E5-553               | [8200b57a5b](https://linux-hardware.org/?probe=8200b57a5b) | Jan 29, 2023 |
| Acer          | Aspire E5-553               | [3ac195a476](https://linux-hardware.org/?probe=3ac195a476) | Jan 29, 2023 |
| Acer          | Aspire A315-41              | [f8ef554d85](https://linux-hardware.org/?probe=f8ef554d85) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Apple         | MacBookPro7,1               | [615e9f22e4](https://linux-hardware.org/?probe=615e9f22e4) | Jan 29, 2023 |
| Valve         | Jupiter                     | [5ea763da5f](https://linux-hardware.org/?probe=5ea763da5f) | Jan 28, 2023 |
| Dell          | Inspiron 5570               | [17a8246044](https://linux-hardware.org/?probe=17a8246044) | Jan 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [edd571ba94](https://linux-hardware.org/?probe=edd571ba94) | Jan 28, 2023 |
| Acer          | Aspire A315-41              | [bbe5b30c42](https://linux-hardware.org/?probe=bbe5b30c42) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [844e4e4b2a](https://linux-hardware.org/?probe=844e4e4b2a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Sony          | SVE1711C5E                  | [73977968f5](https://linux-hardware.org/?probe=73977968f5) | Jan 27, 2023 |
| Sony          | SVE1711C5E                  | [d526ae42aa](https://linux-hardware.org/?probe=d526ae42aa) | Jan 27, 2023 |
| HP            | 255 G8 Notebook PC          | [23a84c76b8](https://linux-hardware.org/?probe=23a84c76b8) | Jan 27, 2023 |
| Apple         | MacBook4,1                  | [e00443a9cc](https://linux-hardware.org/?probe=e00443a9cc) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [4bf7b18ab1](https://linux-hardware.org/?probe=4bf7b18ab1) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Toshiba       | Satellite Pro C50-A-1FD     | [7f7198cdcb](https://linux-hardware.org/?probe=7f7198cdcb) | Jan 26, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [8725d530e5](https://linux-hardware.org/?probe=8725d530e5) | Jan 26, 2023 |
| Dell          | XPS 17 9700                 | [759ae65214](https://linux-hardware.org/?probe=759ae65214) | Jan 26, 2023 |
| Chuwi         | GemiBook Pro                | [bea1d8a9ce](https://linux-hardware.org/?probe=bea1d8a9ce) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| HP            | EliteBook 820 G2            | [7b93d7477b](https://linux-hardware.org/?probe=7b93d7477b) | Jan 25, 2023 |
| HP            | ProBook 6440b               | [25c4dbbe9c](https://linux-hardware.org/?probe=25c4dbbe9c) | Jan 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [cfd65f9e9e](https://linux-hardware.org/?probe=cfd65f9e9e) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [5df97c3eb1](https://linux-hardware.org/?probe=5df97c3eb1) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [cbd812094c](https://linux-hardware.org/?probe=cbd812094c) | Jan 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a05bb7e519](https://linux-hardware.org/?probe=a05bb7e519) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | G75VW                       | [917f63e659](https://linux-hardware.org/?probe=917f63e659) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK A544               | [972194ff6e](https://linux-hardware.org/?probe=972194ff6e) | Jan 23, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5cd697d63d](https://linux-hardware.org/?probe=5cd697d63d) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| Sony          | SVE1513C5E                  | [bff960bae2](https://linux-hardware.org/?probe=bff960bae2) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [adcd91409c](https://linux-hardware.org/?probe=adcd91409c) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [e2fd85407d](https://linux-hardware.org/?probe=e2fd85407d) | Jan 23, 2023 |
| HP            | Laptop 15-dw0xxx            | [8460e3552a](https://linux-hardware.org/?probe=8460e3552a) | Jan 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [8941c8857e](https://linux-hardware.org/?probe=8941c8857e) | Jan 22, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [89c37ebdfa](https://linux-hardware.org/?probe=89c37ebdfa) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | ProBook 450 G3              | [a3ce3d4a23](https://linux-hardware.org/?probe=a3ce3d4a23) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [09650cf189](https://linux-hardware.org/?probe=09650cf189) | Jan 22, 2023 |
| Dell          | Vostro 15 3515              | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| HP            | ProBook 4520s               | [ab9f74eb2c](https://linux-hardware.org/?probe=ab9f74eb2c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Toshiba       | Satellite Pro C850-10L      | [c1de4d0e2b](https://linux-hardware.org/?probe=c1de4d0e2b) | Jan 21, 2023 |
| Acer          | Aspire E5-575G              | [d020dd93e4](https://linux-hardware.org/?probe=d020dd93e4) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Acer          | Aspire 7745G                | [98d6ab791c](https://linux-hardware.org/?probe=98d6ab791c) | Jan 21, 2023 |
| Acer          | Aspire A315-55G             | [b8660798ec](https://linux-hardware.org/?probe=b8660798ec) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| Acer          | Aspire E5-573G              | [c87740267f](https://linux-hardware.org/?probe=c87740267f) | Jan 20, 2023 |
| HP            | Pavilion dv7                | [0a4700fc75](https://linux-hardware.org/?probe=0a4700fc75) | Jan 20, 2023 |
| HUAWEI        | BOM-WXX9                    | [77ac7a6fc3](https://linux-hardware.org/?probe=77ac7a6fc3) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [712fdb1fa7](https://linux-hardware.org/?probe=712fdb1fa7) | Jan 20, 2023 |
| Acer          | TravelMate 5735Z            | [5b1b812b6e](https://linux-hardware.org/?probe=5b1b812b6e) | Jan 20, 2023 |
| Lenovo        | V15-IIL 82C5                | [8fc05186e7](https://linux-hardware.org/?probe=8fc05186e7) | Jan 20, 2023 |
| Dell          | XPS 13 9305                 | [5175eeeff4](https://linux-hardware.org/?probe=5175eeeff4) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [2f712e8614](https://linux-hardware.org/?probe=2f712e8614) | Jan 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| Apple         | MacBookPro11,1              | [67e4dd8f10](https://linux-hardware.org/?probe=67e4dd8f10) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [79ad95dada](https://linux-hardware.org/?probe=79ad95dada) | Jan 18, 2023 |
| HP            | Pavilion g6                 | [d1d3fadd60](https://linux-hardware.org/?probe=d1d3fadd60) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5a1bee99ee](https://linux-hardware.org/?probe=5a1bee99ee) | Jan 18, 2023 |
| ASUSTek       | TP301UJ                     | [4ee30e82ab](https://linux-hardware.org/?probe=4ee30e82ab) | Jan 18, 2023 |
| ASUSTek       | E200HA                      | [f17b69afa1](https://linux-hardware.org/?probe=f17b69afa1) | Jan 18, 2023 |
| ASUSTek       | X505BP                      | [ec4d653e2f](https://linux-hardware.org/?probe=ec4d653e2f) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [44bf2e2ced](https://linux-hardware.org/?probe=44bf2e2ced) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b39c4fc9b7](https://linux-hardware.org/?probe=b39c4fc9b7) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [1c81e8c322](https://linux-hardware.org/?probe=1c81e8c322) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| HP            | 15                          | [ae082994e2](https://linux-hardware.org/?probe=ae082994e2) | Jan 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [3891575263](https://linux-hardware.org/?probe=3891575263) | Jan 16, 2023 |
| Sony          | SVT1312M1ES                 | [9244e6ad96](https://linux-hardware.org/?probe=9244e6ad96) | Jan 16, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [b36eb94e80](https://linux-hardware.org/?probe=b36eb94e80) | Jan 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [360173820c](https://linux-hardware.org/?probe=360173820c) | Jan 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb168e741](https://linux-hardware.org/?probe=8fb168e741) | Jan 16, 2023 |
| Acer          | TravelMate P253             | [8f2246679e](https://linux-hardware.org/?probe=8f2246679e) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | [aa28cfacc3](https://linux-hardware.org/?probe=aa28cfacc3) | Jan 15, 2023 |
| HP            | Notebook                    | [be5a441ca6](https://linux-hardware.org/?probe=be5a441ca6) | Jan 15, 2023 |
| HP            | Pavilion x2 Detachable      | [5f9aaa4add](https://linux-hardware.org/?probe=5f9aaa4add) | Jan 15, 2023 |
| HP            | 15                          | [3faa6c9265](https://linux-hardware.org/?probe=3faa6c9265) | Jan 15, 2023 |
| HP            | Pavilion dv7                | [b3cbaccd13](https://linux-hardware.org/?probe=b3cbaccd13) | Jan 15, 2023 |
| HP            | Pavilion dv7                | [08bbff061e](https://linux-hardware.org/?probe=08bbff061e) | Jan 15, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [57d99b139f](https://linux-hardware.org/?probe=57d99b139f) | Jan 15, 2023 |
| Apple         | MacBook5,1                  | [51581940b0](https://linux-hardware.org/?probe=51581940b0) | Jan 15, 2023 |
| Acer          | TravelMate P253             | [15c26878b5](https://linux-hardware.org/?probe=15c26878b5) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| Kiano         | SlimNote 14,2               | [7596dc87b3](https://linux-hardware.org/?probe=7596dc87b3) | Jan 14, 2023 |
| ASUSTek       | N501VW                      | [5f9c2eebd4](https://linux-hardware.org/?probe=5f9c2eebd4) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e5c76bef74](https://linux-hardware.org/?probe=e5c76bef74) | Jan 14, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2a08ec8e9e](https://linux-hardware.org/?probe=2a08ec8e9e) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [fe5c9c2425](https://linux-hardware.org/?probe=fe5c9c2425) | Jan 14, 2023 |
| Olivetti      | Olibook P55-431W850-8G50... | [649546bc61](https://linux-hardware.org/?probe=649546bc61) | Jan 14, 2023 |
| HP            | Notebook                    | [4c9b4e3b67](https://linux-hardware.org/?probe=4c9b4e3b67) | Jan 14, 2023 |
| HP            | Stream Notebook PC 13       | [b31d60976b](https://linux-hardware.org/?probe=b31d60976b) | Jan 14, 2023 |
| Toshiba       | Satellite Pro C850-1HD      | [d9ecac6816](https://linux-hardware.org/?probe=d9ecac6816) | Jan 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [86fff559f5](https://linux-hardware.org/?probe=86fff559f5) | Jan 14, 2023 |
| MSI           | PS63 Modern 8RC             | [e55e0d9d0a](https://linux-hardware.org/?probe=e55e0d9d0a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b50127412](https://linux-hardware.org/?probe=1b50127412) | Jan 14, 2023 |
| HUAWEI        | KPL-W0X                     | [d1175d8dba](https://linux-hardware.org/?probe=d1175d8dba) | Jan 14, 2023 |
| HP            | 250 G4 Notebook PC          | [dda4a9ae38](https://linux-hardware.org/?probe=dda4a9ae38) | Jan 14, 2023 |
| ASUSTek       | X550LD                      | [60b21ee22f](https://linux-hardware.org/?probe=60b21ee22f) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Acer          | Aspire E1-572G              | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | XPS 9320                    | [b8de11c93d](https://linux-hardware.org/?probe=b8de11c93d) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [b3fed0d61d](https://linux-hardware.org/?probe=b3fed0d61d) | Jan 13, 2023 |
| Unknown       | Unknown                     | [d0391da5d8](https://linux-hardware.org/?probe=d0391da5d8) | Jan 13, 2023 |
| Dell          | Precision 3551              | [66d483ea58](https://linux-hardware.org/?probe=66d483ea58) | Jan 13, 2023 |
| Acer          | Swift SF514-52T             | [feb261f5f5](https://linux-hardware.org/?probe=feb261f5f5) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [033a92981f](https://linux-hardware.org/?probe=033a92981f) | Jan 13, 2023 |
| HP            | EliteBook 840 G6            | [0559975d13](https://linux-hardware.org/?probe=0559975d13) | Jan 13, 2023 |
| ASUSTek       | N501VW                      | [176a3488df](https://linux-hardware.org/?probe=176a3488df) | Jan 12, 2023 |
| Google        | Sasuke                      | [7241244512](https://linux-hardware.org/?probe=7241244512) | Jan 12, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [a8d6ad51af](https://linux-hardware.org/?probe=a8d6ad51af) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Acer          | Aspire V5-561G              | [1551c2b90c](https://linux-hardware.org/?probe=1551c2b90c) | Jan 12, 2023 |
| HP            | Pavilion dv6                | [43e7923f04](https://linux-hardware.org/?probe=43e7923f04) | Jan 11, 2023 |
| ASUSTek       | E200HA                      | [828a42310a](https://linux-hardware.org/?probe=828a42310a) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| Google        | Sasuke                      | [99ba2827e0](https://linux-hardware.org/?probe=99ba2827e0) | Jan 10, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| Toshiba       | Satellite Pro S500          | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| ASUSTek       | N501VW                      | [07d13b3b0b](https://linux-hardware.org/?probe=07d13b3b0b) | Jan 10, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| MSI           | Modern 15 A11M              | [5b55647c95](https://linux-hardware.org/?probe=5b55647c95) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9f1f002f51](https://linux-hardware.org/?probe=9f1f002f51) | Jan 09, 2023 |
| Dell          | Precision 7540              | [77b35e556c](https://linux-hardware.org/?probe=77b35e556c) | Jan 09, 2023 |
| ASUSTek       | K50IJ                       | [9d476dfade](https://linux-hardware.org/?probe=9d476dfade) | Jan 09, 2023 |
| HP            | Pavilion Power Laptop 15... | [4d7677f391](https://linux-hardware.org/?probe=4d7677f391) | Jan 09, 2023 |
| HP            | Pavilion dv7                | [d3177dc8b3](https://linux-hardware.org/?probe=d3177dc8b3) | Jan 09, 2023 |
| HP            | Pavilion dv7                | [77590fdff4](https://linux-hardware.org/?probe=77590fdff4) | Jan 09, 2023 |
| Dell          | XPS 9320                    | [a58b8a72b7](https://linux-hardware.org/?probe=a58b8a72b7) | Jan 09, 2023 |
| HP            | Notebook                    | [c4cc7fb9f6](https://linux-hardware.org/?probe=c4cc7fb9f6) | Jan 09, 2023 |
| Apple         | MacBookPro8,2               | [0a7899316d](https://linux-hardware.org/?probe=0a7899316d) | Jan 08, 2023 |
| Dell          | Latitude E6440              | [faeb2d5372](https://linux-hardware.org/?probe=faeb2d5372) | Jan 08, 2023 |
| Dell          | Latitude 3450               | [e4e8bee1cb](https://linux-hardware.org/?probe=e4e8bee1cb) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| HP            | Notebook                    | [1174de12fc](https://linux-hardware.org/?probe=1174de12fc) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| Notebook      | NL40_50CU                   | [953d771250](https://linux-hardware.org/?probe=953d771250) | Jan 08, 2023 |
| ASUSTek       | S500CA                      | [d742870a51](https://linux-hardware.org/?probe=d742870a51) | Jan 07, 2023 |
| Timi          | TM1701                      | [c011ef538e](https://linux-hardware.org/?probe=c011ef538e) | Jan 07, 2023 |
| HP            | Pavilion dv6                | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| HP            | Compaq CQ58                 | [fae1531801](https://linux-hardware.org/?probe=fae1531801) | Jan 07, 2023 |
| Dell          | Latitude E6230              | [7a7cd04af0](https://linux-hardware.org/?probe=7a7cd04af0) | Jan 07, 2023 |
| HP            | Stream Notebook PC 13       | [d39ec5e414](https://linux-hardware.org/?probe=d39ec5e414) | Jan 07, 2023 |
| HP            | 250 G3                      | [227b44bf7c](https://linux-hardware.org/?probe=227b44bf7c) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Lenovo        | ThinkPad T430 2349KB4       | [4546ecbe85](https://linux-hardware.org/?probe=4546ecbe85) | Jan 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| HP            | 350 G1                      | [09f234d211](https://linux-hardware.org/?probe=09f234d211) | Jan 05, 2023 |
| Valve         | Jupiter                     | [3ce1a1d086](https://linux-hardware.org/?probe=3ce1a1d086) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [4900ec9966](https://linux-hardware.org/?probe=4900ec9966) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Timi          | RedmiBook 16                | [dca6d06bf4](https://linux-hardware.org/?probe=dca6d06bf4) | Jan 05, 2023 |
| HUAWEI        | KPL-W0X                     | [591d1b0ea9](https://linux-hardware.org/?probe=591d1b0ea9) | Jan 04, 2023 |
| Dell          | XPS 9320                    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | 1005P                       | [7ccbcf9b28](https://linux-hardware.org/?probe=7ccbcf9b28) | Jan 04, 2023 |
| HP            | 15                          | [d0aae7c4b7](https://linux-hardware.org/?probe=d0aae7c4b7) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Dell          | XPS 15 9550                 | [72f8edfe5b](https://linux-hardware.org/?probe=72f8edfe5b) | Jan 04, 2023 |
| Acer          | Aspire E5-573               | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Unknown       | Unknown                     | [b363093f89](https://linux-hardware.org/?probe=b363093f89) | Jan 04, 2023 |
| HP            | ProBook 650 G1              | [9aadf12194](https://linux-hardware.org/?probe=9aadf12194) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| HP            | 350 G1                      | [0929eec44b](https://linux-hardware.org/?probe=0929eec44b) | Jan 03, 2023 |
| HP            | 250 G8 Notebook PC          | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| Lenovo        | G510 20238                  | [90c0016c38](https://linux-hardware.org/?probe=90c0016c38) | Jan 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [287840d797](https://linux-hardware.org/?probe=287840d797) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| Dell          | Latitude 7410               | [acb8ce902e](https://linux-hardware.org/?probe=acb8ce902e) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Acer          | TravelMate P253             | [a90b917fbe](https://linux-hardware.org/?probe=a90b917fbe) | Jan 01, 2023 |
| Acer          | TravelMate 5735Z            | [9fa5978af4](https://linux-hardware.org/?probe=9fa5978af4) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [08626b8d57](https://linux-hardware.org/?probe=08626b8d57) | Jan 01, 2023 |
| Google        | Blooglet                    | [711ca24e79](https://linux-hardware.org/?probe=711ca24e79) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Acer          | Aspire E5-573G              | [527a92f562](https://linux-hardware.org/?probe=527a92f562) | Dec 31, 2022 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| ASUSTek       | ProArt StudioBook H5600Q... | [07ca2ed63d](https://linux-hardware.org/?probe=07ca2ed63d) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Chuwi         | HeroBook                    | [1664994b07](https://linux-hardware.org/?probe=1664994b07) | Dec 30, 2022 |
| ASUSTek       | K55VD                       | [e4c90250df](https://linux-hardware.org/?probe=e4c90250df) | Dec 30, 2022 |
| MSI           | GP72MVR 7RFX                | [cefedef93c](https://linux-hardware.org/?probe=cefedef93c) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| ASUSTek       | X556UQK                     | [42a9dc760d](https://linux-hardware.org/?probe=42a9dc760d) | Dec 30, 2022 |
| Dell          | Inspiron 5593               | [bf0f36d69a](https://linux-hardware.org/?probe=bf0f36d69a) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Dell          | Latitude E6410              | [0ee655e2cc](https://linux-hardware.org/?probe=0ee655e2cc) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Compaq 6730s                | [9294bf57da](https://linux-hardware.org/?probe=9294bf57da) | Dec 28, 2022 |
| Lenovo        | ThinkPad E480 20KQS13M00    | [fb7e2874d3](https://linux-hardware.org/?probe=fb7e2874d3) | Dec 28, 2022 |
| Apple         | MacBookPro8,1               | [7b03f438db](https://linux-hardware.org/?probe=7b03f438db) | Dec 28, 2022 |
| Fujitsu       | LIFEBOOK A544               | [efdc6bb5cb](https://linux-hardware.org/?probe=efdc6bb5cb) | Dec 28, 2022 |
| Acer          | Aspire A315-55G             | [92155ba882](https://linux-hardware.org/?probe=92155ba882) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [6240bc3677](https://linux-hardware.org/?probe=6240bc3677) | Dec 28, 2022 |
| HP            | ProBook 440 G6              | [f5689c6edc](https://linux-hardware.org/?probe=f5689c6edc) | Dec 28, 2022 |
| HP            | EliteBook 850 G3            | [0dede5b37a](https://linux-hardware.org/?probe=0dede5b37a) | Dec 28, 2022 |
| System76      | Darter Pro                  | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| Teclast       | F15Plus 2                   | [71564a5900](https://linux-hardware.org/?probe=71564a5900) | Dec 27, 2022 |
| Teclast       | F15Plus 2                   | [4d10c4922e](https://linux-hardware.org/?probe=4d10c4922e) | Dec 27, 2022 |
| Packard Be... | EasyNote TJ65               | [57bfe7c99d](https://linux-hardware.org/?probe=57bfe7c99d) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [039600625a](https://linux-hardware.org/?probe=039600625a) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Dell          | Inspiron 15 3525            | [64a70af984](https://linux-hardware.org/?probe=64a70af984) | Dec 27, 2022 |
| System76      | Darter Pro                  | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1cf2ac2b8b](https://linux-hardware.org/?probe=1cf2ac2b8b) | Dec 27, 2022 |
| HP            | Pavilion 15                 | [9843ba5174](https://linux-hardware.org/?probe=9843ba5174) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| MSI           | GS76 Stealth 11UG           | [10e22b317f](https://linux-hardware.org/?probe=10e22b317f) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| HP            | EliteBook 820 G1            | [6a2c20cb74](https://linux-hardware.org/?probe=6a2c20cb74) | Dec 26, 2022 |
| HP            | 255 G8 Notebook PC          | [2df8b7768a](https://linux-hardware.org/?probe=2df8b7768a) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [ac1ae104e8](https://linux-hardware.org/?probe=ac1ae104e8) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| HP            | Compaq 6730s                | [0cc88159aa](https://linux-hardware.org/?probe=0cc88159aa) | Dec 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [dfb555f802](https://linux-hardware.org/?probe=dfb555f802) | Dec 26, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [4665d79293](https://linux-hardware.org/?probe=4665d79293) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| Toshiba       | Satellite Pro S500          | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ff90a6a029](https://linux-hardware.org/?probe=ff90a6a029) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [faba7b00c6](https://linux-hardware.org/?probe=faba7b00c6) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | [d53469cd41](https://linux-hardware.org/?probe=d53469cd41) | Dec 23, 2022 |
| Dell          | Inspiron 15 5510            | [9ddf91aa1b](https://linux-hardware.org/?probe=9ddf91aa1b) | Dec 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f114731a78](https://linux-hardware.org/?probe=f114731a78) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [756390ae0c](https://linux-hardware.org/?probe=756390ae0c) | Dec 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [c2dd56664a](https://linux-hardware.org/?probe=c2dd56664a) | Dec 23, 2022 |
| Timi          | TM1701                      | [2f28d7e2dc](https://linux-hardware.org/?probe=2f28d7e2dc) | Dec 23, 2022 |
| Timi          | TM1701                      | [dfb4f8774f](https://linux-hardware.org/?probe=dfb4f8774f) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [8c936284b0](https://linux-hardware.org/?probe=8c936284b0) | Dec 22, 2022 |
| Monster       | TULPAR T5 V20.1             | [23cb6e06f8](https://linux-hardware.org/?probe=23cb6e06f8) | Dec 22, 2022 |
| HP            | Pavilion dv9000 (RR329EA... | [6fc7281f2f](https://linux-hardware.org/?probe=6fc7281f2f) | Dec 22, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [a62d8c781d](https://linux-hardware.org/?probe=a62d8c781d) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| Packard Be... | DOT S                       | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [54273f1267](https://linux-hardware.org/?probe=54273f1267) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| Dell          | Latitude E7470              | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| ASUSTek       | S551LB                      | [5e48f71064](https://linux-hardware.org/?probe=5e48f71064) | Dec 20, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [9f5a91c628](https://linux-hardware.org/?probe=9f5a91c628) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [686a93a02a](https://linux-hardware.org/?probe=686a93a02a) | Dec 19, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8e10fc1464](https://linux-hardware.org/?probe=8e10fc1464) | Dec 18, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7dc7a80819](https://linux-hardware.org/?probe=7dc7a80819) | Dec 18, 2022 |
| Acer          | TravelMate P253             | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E7470              | [262849f0f6](https://linux-hardware.org/?probe=262849f0f6) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [ab6fd91b71](https://linux-hardware.org/?probe=ab6fd91b71) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [75126bccca](https://linux-hardware.org/?probe=75126bccca) | Dec 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [a54756ab6f](https://linux-hardware.org/?probe=a54756ab6f) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| HP            | EliteBook 820 G3            | [5e5909e93f](https://linux-hardware.org/?probe=5e5909e93f) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [feb5e321dc](https://linux-hardware.org/?probe=feb5e321dc) | Dec 16, 2022 |
| Acer          | TravelMate P253             | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| Dell          | XPS 15 9520                 | [dcf616e068](https://linux-hardware.org/?probe=dcf616e068) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [dd664077fe](https://linux-hardware.org/?probe=dd664077fe) | Dec 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [d9c3d0a5cd](https://linux-hardware.org/?probe=d9c3d0a5cd) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| Packard Be... | EasyNote TJ71               | [f722162e15](https://linux-hardware.org/?probe=f722162e15) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5e8318b8b8](https://linux-hardware.org/?probe=5e8318b8b8) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d5c9abda1e](https://linux-hardware.org/?probe=d5c9abda1e) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| HP            | Compaq 6735s                | [72d29aa11f](https://linux-hardware.org/?probe=72d29aa11f) | Dec 14, 2022 |
| Samsung       | 750XDA                      | [0120054e9f](https://linux-hardware.org/?probe=0120054e9f) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| PC Special... | Elimina Iv 17               | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [6fc042d213](https://linux-hardware.org/?probe=6fc042d213) | Dec 13, 2022 |
| HP            | EliteBook 820 G3            | [ff5b82cee3](https://linux-hardware.org/?probe=ff5b82cee3) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [d742af8997](https://linux-hardware.org/?probe=d742af8997) | Dec 13, 2022 |
| MSI           | GS65 Stealth Thin 8RF       | [074195107c](https://linux-hardware.org/?probe=074195107c) | Dec 12, 2022 |
| Packard Be... | EasyNote TJ71               | [45630329df](https://linux-hardware.org/?probe=45630329df) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | EliteBook 820 G3            | [1e0eec72b2](https://linux-hardware.org/?probe=1e0eec72b2) | Dec 12, 2022 |
| Apple         | MacBookPro14,3              | [7cefe54b56](https://linux-hardware.org/?probe=7cefe54b56) | Dec 12, 2022 |
| HP            | EliteBook 8570w             | [367579550b](https://linux-hardware.org/?probe=367579550b) | Dec 11, 2022 |
| SGIN          | laptop                      | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| Toshiba       | Satellite L455              | [e92985332e](https://linux-hardware.org/?probe=e92985332e) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| HP            | Laptop 15s-fq2xxx           | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| ASUSTek       | K50C                        | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Google        | Blooglet                    | [a9d65d2144](https://linux-hardware.org/?probe=a9d65d2144) | Dec 11, 2022 |
| Valve         | Jupiter                     | [26c1e67dff](https://linux-hardware.org/?probe=26c1e67dff) | Dec 11, 2022 |
| Valve         | Jupiter                     | [e143b181a1](https://linux-hardware.org/?probe=e143b181a1) | Dec 11, 2022 |
| HP            | Pavilion dv6000 (RY649EA... | [9deecc89f5](https://linux-hardware.org/?probe=9deecc89f5) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Acer          | Aspire ES1-512              | [c9313e3820](https://linux-hardware.org/?probe=c9313e3820) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Dell          | Inspiron 5570               | [4d78d14f00](https://linux-hardware.org/?probe=4d78d14f00) | Dec 10, 2022 |
| Toshiba       | Satellite C70-C-11L         | [8de407e526](https://linux-hardware.org/?probe=8de407e526) | Dec 09, 2022 |
| HP            | 250 G3                      | [7e7b65bb5f](https://linux-hardware.org/?probe=7e7b65bb5f) | Dec 09, 2022 |
| HP            | 250 G3                      | [170a8b35c6](https://linux-hardware.org/?probe=170a8b35c6) | Dec 09, 2022 |
| Packard Be... | EasyNote TJ71               | [4c0af21017](https://linux-hardware.org/?probe=4c0af21017) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| Google        | Blooglet                    | [241c0f4331](https://linux-hardware.org/?probe=241c0f4331) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | [970f8e990b](https://linux-hardware.org/?probe=970f8e990b) | Dec 08, 2022 |
| HP            | Pavilion Laptop 15-eg1xx... | [0e7da55713](https://linux-hardware.org/?probe=0e7da55713) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | [f470667df1](https://linux-hardware.org/?probe=f470667df1) | Dec 08, 2022 |
| Lenovo        | ThinkPad P52 20M9001KIX     | [2562e31e5a](https://linux-hardware.org/?probe=2562e31e5a) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [182678a056](https://linux-hardware.org/?probe=182678a056) | Dec 08, 2022 |
| Packard Be... | EasyNote TJ71               | [f4bf9ede5b](https://linux-hardware.org/?probe=f4bf9ede5b) | Dec 08, 2022 |
| HP            | ProBook 640 G1              | [c3bf44d032](https://linux-hardware.org/?probe=c3bf44d032) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| Google        | Sasuke                      | [527f49b0ae](https://linux-hardware.org/?probe=527f49b0ae) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| Google        | Sasuke                      | [5bd0b833cb](https://linux-hardware.org/?probe=5bd0b833cb) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [10fea00e5a](https://linux-hardware.org/?probe=10fea00e5a) | Dec 06, 2022 |
| Teclast       | F7 Plus                     | [5e155a318e](https://linux-hardware.org/?probe=5e155a318e) | Dec 06, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| Toshiba       | Satellite L50-B             | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [fd9114a304](https://linux-hardware.org/?probe=fd9114a304) | Dec 04, 2022 |
| ASUSTek       | X750JN                      | [af27460f17](https://linux-hardware.org/?probe=af27460f17) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ac92442dbc](https://linux-hardware.org/?probe=ac92442dbc) | Dec 04, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Acer          | Aspire A315-23              | [8c3beba1e1](https://linux-hardware.org/?probe=8c3beba1e1) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [f34caf87d5](https://linux-hardware.org/?probe=f34caf87d5) | Dec 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c00aab388c](https://linux-hardware.org/?probe=c00aab388c) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| HP            | Pavilion 15                 | [87de142ecd](https://linux-hardware.org/?probe=87de142ecd) | Dec 03, 2022 |
| Google        | Blooglet                    | [045f75ab43](https://linux-hardware.org/?probe=045f75ab43) | Dec 03, 2022 |
| HUAWEI        | MACHC-WAX9                  | [958e17ffc9](https://linux-hardware.org/?probe=958e17ffc9) | Dec 03, 2022 |
| Lenovo        | G580 2189                   | [80fe3f7171](https://linux-hardware.org/?probe=80fe3f7171) | Dec 03, 2022 |
| Samsung       | 530U3C/530U4C/532U3C        | [91edd3827d](https://linux-hardware.org/?probe=91edd3827d) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9d27bb4f90](https://linux-hardware.org/?probe=9d27bb4f90) | Dec 01, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [1df1f552ff](https://linux-hardware.org/?probe=1df1f552ff) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [a8236e24a5](https://linux-hardware.org/?probe=a8236e24a5) | Dec 01, 2022 |
| HP            | ProBook 440 G7              | [a54a325001](https://linux-hardware.org/?probe=a54a325001) | Dec 01, 2022 |
| Acer          | Aspire 5750G                | [198d7f2534](https://linux-hardware.org/?probe=198d7f2534) | Dec 01, 2022 |
| ASUSTek       | K52F                        | [63c08600c3](https://linux-hardware.org/?probe=63c08600c3) | Dec 01, 2022 |
| ASUSTek       | K52F                        | [4276cc2cb9](https://linux-hardware.org/?probe=4276cc2cb9) | Dec 01, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion g6                 | [c552ca011c](https://linux-hardware.org/?probe=c552ca011c) | Nov 30, 2022 |
| Apple         | MacBook4,1                  | [0866a64897](https://linux-hardware.org/?probe=0866a64897) | Nov 30, 2022 |
| Apple         | MacBookAir8,1               | [7581ef0e85](https://linux-hardware.org/?probe=7581ef0e85) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [cbb0c1dca7](https://linux-hardware.org/?probe=cbb0c1dca7) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Acer          | Aspire 5738                 | [a9697f1e7a](https://linux-hardware.org/?probe=a9697f1e7a) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [1620a1a2cb](https://linux-hardware.org/?probe=1620a1a2cb) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Unknown       | Unknown                     | [4f73de3788](https://linux-hardware.org/?probe=4f73de3788) | Nov 27, 2022 |
| Dell          | XPS 13 9305                 | [c306dcfa4f](https://linux-hardware.org/?probe=c306dcfa4f) | Nov 27, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [44a305db4d](https://linux-hardware.org/?probe=44a305db4d) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| Lenovo        | S20-30 Touch 20434          | [63d2134051](https://linux-hardware.org/?probe=63d2134051) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 473       | 11.1%   |
| Ubuntu 18.04        | 290       | 6.81%   |
| Ubuntu 22.04        | 241       | 5.66%   |
| Arch Rolling        | 128       | 3%      |
| OpenMandriva 4.2    | 107       | 2.51%   |
| OpenMandriva 4.3    | 101       | 2.37%   |
| Debian 11           | 100       | 2.35%   |
| Fedora 36           | 90        | 2.11%   |
| Arch                | 75        | 1.76%   |
| Xubuntu 18.04       | 69        | 1.62%   |
| Ubuntu 19.10        | 68        | 1.6%    |
| Ubuntu 22.10        | 67        | 1.57%   |
| Pop!_OS 22.04       | 67        | 1.57%   |
| Linux Mint 21.1     | 67        | 1.57%   |
| Fedora 37           | 67        | 1.57%   |
| Ubuntu 20.10        | 61        | 1.43%   |
| Xubuntu 20.04       | 60        | 1.41%   |
| Linux Mint 20.3     | 60        | 1.41%   |
| Ubuntu 21.10        | 58        | 1.36%   |
| Ubuntu 19.04        | 56        | 1.31%   |
| Zorin 16            | 55        | 1.29%   |
| KDE neon 20.04      | 54        | 1.27%   |
| Linux Mint 21       | 50        | 1.17%   |
| Zorin 15            | 49        | 1.15%   |
| EndeavourOS Rolling | 46        | 1.08%   |
| Debian 10           | 46        | 1.08%   |
| Fedora 35           | 42        | 0.99%   |
| Ubuntu 18.10        | 40        | 0.94%   |
| Ubuntu 21.04        | 39        | 0.92%   |
| Kubuntu 22.04       | 38        | 0.89%   |
| OpenMandriva 23.01  | 37        | 0.87%   |
| OpenMandriva 23.03  | 36        | 0.84%   |
| Linux Mint 20.1     | 36        | 0.84%   |
| Pop!_OS 20.10       | 35        | 0.82%   |
| Linux Mint 20       | 35        | 0.82%   |
| Linux Mint 19.3     | 35        | 0.82%   |
| Kubuntu 20.04       | 35        | 0.82%   |
| Fedora 33           | 35        | 0.82%   |
| Linux Mint 20.2     | 34        | 0.8%    |
| ROSA R10            | 29        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1342      | 33.31%  |
| Linux Mint    | 316       | 7.84%   |
| Fedora        | 294       | 7.3%    |
| OpenMandriva  | 292       | 7.25%   |
| Arch          | 197       | 4.89%   |
| Debian        | 180       | 4.47%   |
| Xubuntu       | 178       | 4.42%   |
| Pop!_OS       | 159       | 3.95%   |
| Manjaro       | 119       | 2.95%   |
| Kubuntu       | 116       | 2.88%   |
| Zorin         | 110       | 2.73%   |
| ROSA          | 88        | 2.18%   |
| KDE neon      | 72        | 1.79%   |
| Lubuntu       | 60        | 1.49%   |
| EndeavourOS   | 48        | 1.19%   |
| openSUSE      | 46        | 1.14%   |
| Elementary    | 40        | 0.99%   |
| Endless       | 38        | 0.94%   |
| Ubuntu MATE   | 37        | 0.92%   |
| ArcoLinux     | 23        | 0.57%   |
| Gentoo        | 21        | 0.52%   |
| BlackPanther  | 20        | 0.5%    |
| Ubuntu Unity  | 19        | 0.47%   |
| MX            | 19        | 0.47%   |
| LMDE          | 19        | 0.47%   |
| Kali          | 16        | 0.4%    |
| Clear Linux   | 16        | 0.4%    |
| Ubuntu Budgie | 15        | 0.37%   |
| SteamOS       | 11        | 0.27%   |
| Peppermint    | 11        | 0.27%   |
| Garuda Linux  | 11        | 0.27%   |
| Parrot        | 7         | 0.17%   |
| LinuxFX       | 7         | 0.17%   |
| Nobara        | 6         | 0.15%   |
| Chrome OS     | 5         | 0.12%   |
| Xero          | 4         | 0.1%    |
| Slackware     | 4         | 0.1%    |
| Linux Lite    | 4         | 0.1%    |
| CentOS        | 4         | 0.1%    |
| BunsenLabs    | 4         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 102       | 2.18%   |
| 5.16.7-desktop-1omv4003  | 96        | 2.05%   |
| 5.15.0-52-generic        | 96        | 2.05%   |
| 5.4.0-42-generic         | 68        | 1.45%   |
| 5.15.0-56-generic        | 62        | 1.32%   |
| 5.15.0-58-generic        | 43        | 0.92%   |
| 5.4.0-26-generic         | 41        | 0.88%   |
| 5.15.0-46-generic        | 41        | 0.88%   |
| 5.3.0-46-generic         | 40        | 0.85%   |
| 5.4.0-52-generic         | 36        | 0.77%   |
| 5.4.0-29-generic         | 36        | 0.77%   |
| 6.2.6-desktop-1omv2390   | 35        | 0.75%   |
| 5.15.0-47-generic        | 35        | 0.75%   |
| 5.4.0-58-generic         | 33        | 0.7%    |
| 5.15.0-43-generic        | 33        | 0.7%    |
| 5.3.0-40-generic         | 32        | 0.68%   |
| 6.1.1-desktop-1omv2290   | 31        | 0.66%   |
| 5.3.0-42-generic         | 31        | 0.66%   |
| 5.4.0-48-generic         | 30        | 0.64%   |
| 6.0.2-arch1-1            | 28        | 0.6%    |
| 5.15.0-41-generic        | 28        | 0.6%    |
| 5.15.0-53-generic        | 27        | 0.58%   |
| 5.13.0-28-generic        | 27        | 0.58%   |
| 5.0.0-37-generic         | 27        | 0.58%   |
| 5.15.0-48-generic        | 25        | 0.53%   |
| 5.10.0-19-amd64          | 24        | 0.51%   |
| 5.3.0-51-generic         | 23        | 0.49%   |
| 5.19.0-23-generic        | 23        | 0.49%   |
| 5.19.0-21-generic        | 23        | 0.49%   |
| 5.15.0-60-generic        | 23        | 0.49%   |
| 5.4.0-54-generic         | 22        | 0.47%   |
| 5.4.0-47-generic         | 22        | 0.47%   |
| 5.4.0-28-generic         | 22        | 0.47%   |
| 5.10.0-21-amd64          | 22        | 0.47%   |
| 5.19.0-32-generic        | 21        | 0.45%   |
| 5.15.0-50-generic        | 21        | 0.45%   |
| 4.18.0-15-generic        | 21        | 0.45%   |
| 5.4.0-33-generic         | 20        | 0.43%   |
| 5.19.0-76051900-generic  | 20        | 0.43%   |
| 5.4.0-37-generic         | 19        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 689       | 15.71%  |
| 5.15.0  | 474       | 10.8%   |
| 4.15.0  | 240       | 5.47%   |
| 5.3.0   | 223       | 5.08%   |
| 5.8.0   | 201       | 4.58%   |
| 5.13.0  | 195       | 4.44%   |
| 5.19.0  | 171       | 3.9%    |
| 5.11.0  | 167       | 3.81%   |
| 5.10.0  | 132       | 3.01%   |
| 5.0.0   | 113       | 2.58%   |
| 5.10.14 | 102       | 2.33%   |
| 5.16.7  | 98        | 2.23%   |
| 4.18.0  | 87        | 1.98%   |
| 6.0.2   | 53        | 1.21%   |
| 4.19.0  | 45        | 1.03%   |
| 6.2.6   | 44        | 1%      |
| 6.1.1   | 38        | 0.87%   |
| 5.19.16 | 29        | 0.66%   |
| 6.0.0   | 26        | 0.59%   |
| 6.0.12  | 22        | 0.5%    |
| 5.17.5  | 20        | 0.46%   |
| 4.18.16 | 19        | 0.43%   |
| 6.0.7   | 18        | 0.41%   |
| 6.0.6   | 18        | 0.41%   |
| 4.9.60  | 18        | 0.41%   |
| 4.9.20  | 17        | 0.39%   |
| 4.4.0   | 16        | 0.36%   |
| 5.17.1  | 14        | 0.32%   |
| 6.0.5   | 13        | 0.3%    |
| 6.1.0   | 12        | 0.27%   |
| 6.0.9   | 12        | 0.27%   |
| 5.18.0  | 12        | 0.27%   |
| 6.1.8   | 11        | 0.25%   |
| 6.0.10  | 11        | 0.25%   |
| 5.19.12 | 11        | 0.25%   |
| 5.14.0  | 11        | 0.25%   |
| 6.0.11  | 10        | 0.23%   |
| 5.19.6  | 10        | 0.23%   |
| 5.17.0  | 10        | 0.23%   |
| 5.16.11 | 10        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 735       | 16.95%  |
| 5.15    | 562       | 12.96%  |
| 5.10    | 291       | 6.71%   |
| 5.19    | 275       | 6.34%   |
| 5.3     | 248       | 5.72%   |
| 5.8     | 241       | 5.56%   |
| 4.15    | 241       | 5.56%   |
| 5.13    | 216       | 4.98%   |
| 6.0     | 205       | 4.73%   |
| 5.11    | 204       | 4.7%    |
| 5.16    | 150       | 3.46%   |
| 6.1     | 125       | 2.88%   |
| 5.0     | 116       | 2.67%   |
| 4.18    | 109       | 2.51%   |
| 6.2     | 93        | 2.14%   |
| 5.17    | 65        | 1.5%    |
| 4.9     | 62        | 1.43%   |
| 4.19    | 58        | 1.34%   |
| 5.14    | 55        | 1.27%   |
| 5.18    | 54        | 1.25%   |
| 5.9     | 46        | 1.06%   |
| 5.12    | 37        | 0.85%   |
| 5.6     | 34        | 0.78%   |
| 5.5     | 34        | 0.78%   |
| 5.7     | 23        | 0.53%   |
| 4.4     | 17        | 0.39%   |
| 5.2     | 9         | 0.21%   |
| 4.13    | 6         | 0.14%   |
| 4.1     | 6         | 0.14%   |
| 5.1     | 4         | 0.09%   |
| 4.12    | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.17    | 3         | 0.07%   |
| 4.16    | 2         | 0.05%   |
| 3.10    | 2         | 0.05%   |
| 4.14    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3673      | 94.59%  |
| i686   | 209       | 5.38%   |
| armv7l | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1776      | 43.72%  |
| KDE5              | 763       | 18.78%  |
| Unknown           | 402       | 9.9%    |
| XFCE              | 363       | 8.94%   |
| X-Cinnamon        | 250       | 6.15%   |
| MATE              | 108       | 2.66%   |
| KDE               | 69        | 1.7%    |
| LXQt              | 66        | 1.62%   |
| KDE4              | 50        | 1.23%   |
| Pantheon          | 40        | 0.98%   |
| LXDE              | 27        | 0.66%   |
| Cinnamon          | 27        | 0.66%   |
| Unity             | 21        | 0.52%   |
| Budgie            | 21        | 0.52%   |
| i3                | 15        | 0.37%   |
| GNOME Flashback   | 15        | 0.37%   |
| GNOME Classic     | 6         | 0.15%   |
| Deepin            | 6         | 0.15%   |
| sway              | 5         | 0.12%   |
| bspwm             | 5         | 0.12%   |
| Hyprland          | 4         | 0.1%    |
| DWM               | 4         | 0.1%    |
| xubuntu           | 2         | 0.05%   |
| qtile             | 2         | 0.05%   |
| Openbox           | 2         | 0.05%   |
| enlightenment     | 2         | 0.05%   |
| ubuntu:pika:GNOME | 1         | 0.02%   |
| ubuntu            | 1         | 0.02%   |
| Trinity           | 1         | 0.02%   |
| pika:GNOME        | 1         | 0.02%   |
| none+i3           | 1         | 0.02%   |
| none+bspwm        | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| gamescope         | 1         | 0.02%   |
| Cutefish          | 1         | 0.02%   |
| awesome           | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3036      | 75.69%  |
| Wayland | 729       | 18.18%  |
| Unknown | 208       | 5.19%   |
| Tty     | 38        | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1766      | 43.65%  |
| SDDM    | 718       | 17.75%  |
| GDM3    | 493       | 12.18%  |
| GDM     | 493       | 12.18%  |
| LightDM | 410       | 10.13%  |
| TDM     | 95        | 2.35%   |
| KDM     | 51        | 1.26%   |
| XDM     | 6         | 0.15%   |
| SLiM    | 6         | 0.15%   |
| LXDM    | 3         | 0.07%   |
| WDM     | 1         | 0.02%   |
| SLIMSKI | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| it_IT        | 2465      | 61.67%  |
| en_US        | 871       | 21.79%  |
| Unknown      | 432       | 10.81%  |
| en_GB        | 87        | 2.18%   |
| C            | 69        | 1.73%   |
| de_DE        | 12        | 0.3%    |
| fr_FR        | 9         | 0.23%   |
| es_ES        | 8         | 0.2%    |
| de_IT        | 7         | 0.18%   |
| ru_RU        | 5         | 0.13%   |
| POSIX        | 4         | 0.1%    |
| en_AG        | 4         | 0.1%    |
| en_AU        | 3         | 0.08%   |
| it_IT@euro   | 2         | 0.05%   |
| en_US.UTF8   | 2         | 0.05%   |
| en_IE        | 2         | 0.05%   |
| ro_RO        | 1         | 0.03%   |
| pt_BR        | 1         | 0.03%   |
| pl_PL        | 1         | 0.03%   |
| it_IT.UTF -8 | 1         | 0.03%   |
| it_CH        | 1         | 0.03%   |
| fur_IT       | 1         | 0.03%   |
| fr_BE        | 1         | 0.03%   |
| es_US        | 1         | 0.03%   |
| en_US@euro   | 1         | 0.03%   |
| en_US.utf-8  | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| de_CH        | 1         | 0.03%   |
| de_AT        | 1         | 0.03%   |
| C.UTF8       | 1         | 0.03%   |
| bg_BG        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2104      | 53.19%  |
| BIOS | 1852      | 46.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3051      | 76.83%  |
| Overlay  | 381       | 9.59%   |
| Btrfs    | 345       | 8.69%   |
| Unknown  | 103       | 2.59%   |
| Xfs      | 29        | 0.73%   |
| Zfs      | 25        | 0.63%   |
| Ext2     | 11        | 0.28%   |
| Tmpfs    | 9         | 0.23%   |
| F2fs     | 8         | 0.2%    |
| Ext3     | 5         | 0.13%   |
| XXX4     | 2         | 0.05%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1936      | 48.72%  |
| GPT     | 1624      | 40.87%  |
| MBR     | 414       | 10.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3456      | 87.65%  |
| Yes       | 487       | 12.35%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2625      | 66.32%  |
| Yes       | 1333      | 33.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 884       | 22.79%  |
| Lenovo              | 633       | 16.32%  |
| ASUSTek Computer    | 612       | 15.78%  |
| Acer                | 441       | 11.37%  |
| Dell                | 397       | 10.23%  |
| Toshiba             | 102       | 2.63%   |
| Apple               | 94        | 2.42%   |
| HUAWEI              | 92        | 2.37%   |
| Sony                | 87        | 2.24%   |
| MSI                 | 76        | 1.96%   |
| Samsung Electronics | 67        | 1.73%   |
| Fujitsu             | 40        | 1.03%   |
| Packard Bell        | 30        | 0.77%   |
| Unknown             | 30        | 0.77%   |
| Mediacom            | 26        | 0.67%   |
| Chuwi               | 22        | 0.57%   |
| Notebook            | 21        | 0.54%   |
| Teclast             | 20        | 0.52%   |
| Timi                | 18        | 0.46%   |
| Fujitsu Siemens     | 18        | 0.46%   |
| Microtech           | 15        | 0.39%   |
| TUXEDO              | 13        | 0.34%   |
| PC Specialist       | 12        | 0.31%   |
| Valve               | 9         | 0.23%   |
| SANTECH             | 8         | 0.21%   |
| TrekStor            | 7         | 0.18%   |
| Jumper              | 7         | 0.18%   |
| Google              | 7         | 0.18%   |
| eMachines           | 7         | 0.18%   |
| Olivetti            | 5         | 0.13%   |
| LG Electronics      | 5         | 0.13%   |
| Alienware           | 5         | 0.13%   |
| YASHI               | 3         | 0.08%   |
| System76            | 3         | 0.08%   |
| SiComputer          | 3         | 0.08%   |
| Razer               | 3         | 0.08%   |
| Intel               | 3         | 0.08%   |
| YJKC                | 2         | 0.05%   |
| TELECOMITALIA       | 2         | 0.05%   |
| Schenker            | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 52        | 1.34%   |
| Unknown                                | 45        | 1.16%   |
| HP Notebook                            | 38        | 0.98%   |
| HP Pavilion 15                         | 26        | 0.67%   |
| HP Pavilion g6                         | 22        | 0.57%   |
| HP 255 G8 Notebook PC                  | 19        | 0.49%   |
| HUAWEI NBLK-WAX9X                      | 17        | 0.44%   |
| HP 15                                  | 15        | 0.39%   |
| Dell XPS 15 7590                       | 13        | 0.34%   |
| Mediacom SmartBook 14 FullHD - SB14UC  | 12        | 0.31%   |
| HP G62                                 | 12        | 0.31%   |
| HP 255 G7 Notebook PC                  | 12        | 0.31%   |
| HP 250 G6 Notebook PC                  | 12        | 0.31%   |
| Apple MacBook4,1                       | 12        | 0.31%   |
| Lenovo IdeaPad 3 15ADA05 81W1          | 11        | 0.28%   |
| HUAWEI KLVL-WXX9                       | 11        | 0.28%   |
| HP Pavilion x2 Detachable              | 11        | 0.28%   |
| HP ENVY 15                             | 11        | 0.28%   |
| HP 255 G6 Notebook PC                  | 11        | 0.28%   |
| Lenovo IdeaPad 330S-15IKB 81F5         | 10        | 0.26%   |
| Valve Jupiter                          | 9         | 0.23%   |
| HP Pavilion dv7                        | 9         | 0.23%   |
| HP Laptop 15s-eq2xxx                   | 9         | 0.23%   |
| HP Compaq 6730s                        | 9         | 0.23%   |
| Dell XPS 15 9570                       | 9         | 0.23%   |
| Dell XPS 15 9560                       | 9         | 0.23%   |
| Dell Inspiron 5570                     | 9         | 0.23%   |
| Acer Aspire A515-51G                   | 9         | 0.23%   |
| Acer Aspire A515-45                    | 9         | 0.23%   |
| Acer Aspire 5750G                      | 9         | 0.23%   |
| Lenovo V145-15AST 81MT                 | 8         | 0.21%   |
| HP ProBook 450 G5                      | 8         | 0.21%   |
| HP EliteBook 8440p                     | 8         | 0.21%   |
| HP 250 G3                              | 8         | 0.21%   |
| Dell XPS 13 7390                       | 8         | 0.21%   |
| Dell Latitude E7440                    | 8         | 0.21%   |
| ASUS VivoBook_ASUSLaptop X580GD_N580GD | 8         | 0.21%   |
| ASUS N53SV                             | 8         | 0.21%   |
| ASUS K53SC                             | 8         | 0.21%   |
| Acer Swift SF114-32                    | 8         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 306       | 7.89%   |
| Acer Aspire           | 289       | 7.45%   |
| HP Pavilion           | 237       | 6.11%   |
| Lenovo IdeaPad        | 156       | 4.02%   |
| Dell Latitude         | 148       | 3.82%   |
| HP EliteBook          | 102       | 2.63%   |
| ASUS VivoBook         | 93        | 2.4%    |
| Dell XPS              | 91        | 2.35%   |
| Toshiba Satellite     | 88        | 2.27%   |
| HP Laptop             | 84        | 2.17%   |
| HP ProBook            | 83        | 2.14%   |
| Dell Inspiron         | 77        | 1.99%   |
| HP Compaq             | 65        | 1.68%   |
| HP 255                | 57        | 1.47%   |
| HP 250                | 52        | 1.34%   |
| Unknown               | 45        | 1.16%   |
| HP Notebook           | 38        | 0.98%   |
| Fujitsu LIFEBOOK      | 38        | 0.98%   |
| Acer Swift            | 36        | 0.93%   |
| Acer TravelMate       | 35        | 0.9%    |
| Acer Extensa          | 33        | 0.85%   |
| Dell Precision        | 31        | 0.8%    |
| Dell Vostro           | 30        | 0.77%   |
| Lenovo ThinkBook      | 29        | 0.75%   |
| Packard Bell EasyNote | 23        | 0.59%   |
| HP ENVY               | 22        | 0.57%   |
| ASUS ROG              | 18        | 0.46%   |
| Apple MacBookPro11    | 18        | 0.46%   |
| HUAWEI NBLK-WAX9X     | 17        | 0.44%   |
| HP 15                 | 15        | 0.39%   |
| MSI Modern            | 14        | 0.36%   |
| Mediacom SmartBook    | 14        | 0.36%   |
| HP ZBook              | 14        | 0.36%   |
| HP Presario           | 14        | 0.36%   |
| ASUS Zenbook          | 14        | 0.36%   |
| Acer Nitro            | 13        | 0.34%   |
| Lenovo Legion         | 12        | 0.31%   |
| HP OMEN               | 12        | 0.31%   |
| HP G62                | 12        | 0.31%   |
| Apple MacBook4        | 12        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 339       | 8.74%   |
| 2020    | 336       | 8.66%   |
| 2018    | 307       | 7.91%   |
| 2021    | 295       | 7.61%   |
| 2013    | 270       | 6.96%   |
| 2017    | 262       | 6.75%   |
| 2011    | 231       | 5.96%   |
| 2008    | 231       | 5.96%   |
| 2016    | 229       | 5.9%    |
| 2015    | 227       | 5.85%   |
| 2012    | 227       | 5.85%   |
| 2010    | 227       | 5.85%   |
| 2014    | 212       | 5.47%   |
| 2009    | 177       | 4.56%   |
| 2007    | 117       | 3.02%   |
| 2022    | 94        | 2.42%   |
| 2006    | 63        | 1.62%   |
| 2005    | 23        | 0.59%   |
| Unknown | 6         | 0.15%   |
| 2004    | 3         | 0.08%   |
| 2023    | 2         | 0.05%   |
| 2003    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3879      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3527      | 89.95%  |
| Enabled  | 394       | 10.05%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3864      | 99.61%  |
| Yes  | 15        | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1094      | 27.85%  |
| 3.01-4.0    | 979       | 24.92%  |
| 16.01-24.0  | 631       | 16.06%  |
| 8.01-16.0   | 608       | 15.48%  |
| 1.01-2.0    | 259       | 6.59%   |
| 32.01-64.0  | 176       | 4.48%   |
| 2.01-3.0    | 87        | 2.21%   |
| 0.51-1.0    | 45        | 1.15%   |
| 24.01-32.0  | 26        | 0.66%   |
| 64.01-256.0 | 20        | 0.51%   |
| 0.01-0.5    | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1657      | 38.49%  |
| 2.01-3.0   | 1047      | 24.32%  |
| 4.01-8.0   | 537       | 12.47%  |
| 3.01-4.0   | 511       | 11.87%  |
| 0.51-1.0   | 361       | 8.39%   |
| 8.01-16.0  | 135       | 3.14%   |
| 0.01-0.5   | 46        | 1.07%   |
| 16.01-24.0 | 8         | 0.19%   |
| 24.01-32.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2958      | 74.94%  |
| 2      | 857       | 21.71%  |
| 3      | 87        | 2.2%    |
| 0      | 30        | 0.76%   |
| 4      | 11        | 0.28%   |
| 6      | 2         | 0.05%   |
| 5      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2219      | 56.94%  |
| Yes       | 1678      | 43.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3102      | 79.6%   |
| No        | 795       | 20.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3802      | 97.91%  |
| No        | 81        | 2.09%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2847      | 72.41%  |
| No        | 1085      | 27.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 3879      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 593       | 13.5%   |
| Rome                | 449       | 10.22%  |
| Turin               | 146       | 3.32%   |
| Naples              | 82        | 1.87%   |
| Bologna             | 77        | 1.75%   |
| Florence            | 75        | 1.71%   |
| Rho                 | 69        | 1.57%   |
| Genoa               | 60        | 1.37%   |
| Padova              | 53        | 1.21%   |
| Palermo             | 49        | 1.12%   |
| Verona              | 46        | 1.05%   |
| Bari                | 39        | 0.89%   |
| Milano              | 37        | 0.84%   |
| Catania             | 35        | 0.8%    |
| Brescia             | 34        | 0.77%   |
| Bergamo             | 31        | 0.71%   |
| Trieste             | 30        | 0.68%   |
| Parma               | 27        | 0.61%   |
| Venice              | 23        | 0.52%   |
| Trento              | 22        | 0.5%    |
| Pisa                | 22        | 0.5%    |
| Bolzano             | 22        | 0.5%    |
| Casalecchio di Reno | 21        | 0.48%   |
| Modena              | 20        | 0.46%   |
| Sesto San Giovanni  | 18        | 0.41%   |
| Perugia             | 17        | 0.39%   |
| Cagliari            | 17        | 0.39%   |
| Seregno             | 16        | 0.36%   |
| Salerno             | 15        | 0.34%   |
| Reggio Emilia       | 15        | 0.34%   |
| Monza               | 15        | 0.34%   |
| Udine               | 14        | 0.32%   |
| Pescara             | 14        | 0.32%   |
| Taranto             | 13        | 0.3%    |
| Reggio Calabria     | 13        | 0.3%    |
| Novara              | 13        | 0.3%    |
| Mestre              | 12        | 0.27%   |
| Legnano             | 12        | 0.27%   |
| Forlì              | 12        | 0.27%   |
| Vicenza             | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 849       | 1121   | 17.84%  |
| WDC                         | 468       | 583    | 9.83%   |
| Seagate                     | 450       | 544    | 9.46%   |
| Toshiba                     | 327       | 414    | 6.87%   |
| SanDisk                     | 297       | 395    | 6.24%   |
| Unknown                     | 292       | 396    | 6.14%   |
| Kingston                    | 281       | 326    | 5.9%    |
| Crucial                     | 271       | 313    | 5.69%   |
| Hitachi                     | 218       | 264    | 4.58%   |
| SK hynix                    | 180       | 219    | 3.78%   |
| HGST                        | 169       | 219    | 3.55%   |
| Micron Technology           | 125       | 151    | 2.63%   |
| Intel                       | 111       | 140    | 2.33%   |
| KIOXIA                      | 56        | 68     | 1.18%   |
| Fujitsu                     | 44        | 52     | 0.92%   |
| Phison                      | 38        | 46     | 0.8%    |
| China                       | 38        | 43     | 0.8%    |
| Apple                       | 32        | 35     | 0.67%   |
| SPCC                        | 26        | 32     | 0.55%   |
| LITEON                      | 26        | 33     | 0.55%   |
| Transcend                   | 24        | 30     | 0.5%    |
| JMicron Technology          | 22        | 25     | 0.46%   |
| Intenso                     | 22        | 22     | 0.46%   |
| Netac                       | 18        | 19     | 0.38%   |
| Phison Electronics          | 17        | 19     | 0.36%   |
| A-DATA Technology           | 17        | 21     | 0.36%   |
| Teclast                     | 15        | 20     | 0.32%   |
| KingDian                    | 15        | 20     | 0.32%   |
| Unknown                     | 15        | 21     | 0.32%   |
| Kingston Technology Company | 14        | 16     | 0.29%   |
| Silicon Motion              | 11        | 15     | 0.23%   |
| SABRENT                     | 11        | 11     | 0.23%   |
| PNY                         | 11        | 13     | 0.23%   |
| Drevo                       | 11        | 12     | 0.23%   |
| Patriot                     | 9         | 12     | 0.19%   |
| LITEONIT                    | 9         | 20     | 0.19%   |
| Lenovo                      | 8         | 8      | 0.17%   |
| Corsair                     | 8         | 9      | 0.17%   |
| TCSUNBOW                    | 7         | 9      | 0.15%   |
| SSSTC                       | 7         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 79        | 1.6%    |
| Crucial CT500MX500SSD1 500GB                      | 66        | 1.34%   |
| Unknown MMC Card  32GB                            | 64        | 1.3%    |
| Toshiba MQ01ABF050 500GB                          | 60        | 1.22%   |
| Samsung SSD 860 EVO 500GB                         | 58        | 1.18%   |
| Seagate ST500LT012-1DG142 500GB                   | 49        | 0.99%   |
| Samsung SSD 850 EVO 250GB                         | 48        | 0.97%   |
| HGST HTS545050A7E680 500GB                        | 48        | 0.97%   |
| Seagate ST1000LM035-1RK172 970GB                  | 46        | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 45        | 0.91%   |
| HGST HTS721010A9E630 1TB                          | 43        | 0.87%   |
| Samsung SSD 850 EVO 500GB                         | 41        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 37        | 0.75%   |
| Unknown MMC Card  64GB                            | 35        | 0.71%   |
| Crucial CT240BX500SSD1 240GB                      | 35        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                   | 33        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                      | 32        | 0.65%   |
| Toshiba MQ01ABD100 1TB                            | 30        | 0.61%   |
| SanDisk NVMe SSD Drive 512GB                      | 28        | 0.57%   |
| Seagate ST9500325AS 500GB                         | 27        | 0.55%   |
| Crucial CT480BX500SSD1 480GB                      | 27        | 0.55%   |
| Toshiba MQ04ABF100 1TB                            | 26        | 0.53%   |
| SanDisk SSD PLUS 240GB                            | 25        | 0.51%   |
| Samsung SSD 860 EVO 250GB                         | 24        | 0.49%   |
| Samsung SSD 860 EVO 1TB                           | 23        | 0.47%   |
| Samsung NVMe SSD Drive 256GB                      | 22        | 0.45%   |
| SanDisk NVMe SSD Drive 256GB                      | 21        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                       | 21        | 0.43%   |
| Kingston SA400S37120G 120GB SSD                   | 20        | 0.41%   |
| Hitachi HTS545050A7E380 500GB                     | 20        | 0.41%   |
| SK hynix NVMe SSD Drive 512GB                     | 19        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                  | 19        | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 18        | 0.37%   |
| Seagate M3 Portable 4TB                           | 18        | 0.37%   |
| Samsung SSD 840 EVO 250GB                         | 18        | 0.37%   |
| Unknown MMC Card  16GB                            | 17        | 0.34%   |
| Unknown MMC Card  128GB                           | 17        | 0.34%   |
| Samsung MZVLQ512HALU-000H1 512GB                  | 17        | 0.34%   |
| Hitachi HTS545050B9A300 500GB                     | 17        | 0.34%   |
| HGST HTS541010A9E680 1TB                          | 17        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 429       | 513    | 28.62%  |
| WDC                 | 329       | 411    | 21.95%  |
| Toshiba             | 227       | 271    | 15.14%  |
| Hitachi             | 218       | 264    | 14.54%  |
| HGST                | 169       | 219    | 11.27%  |
| Fujitsu             | 44        | 52     | 2.94%   |
| Samsung Electronics | 40        | 51     | 2.67%   |
| Unknown             | 17        | 18     | 1.13%   |
| JMicron Technology  | 11        | 12     | 0.73%   |
| ASMT                | 3         | 3      | 0.2%    |
| IBM/Hitachi         | 2         | 3      | 0.13%   |
| HGST HTS            | 2         | 2      | 0.13%   |
| USB3.0              | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| Generic-            | 1         | 1      | 0.07%   |
| DAS                 | 1         | 4      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |
| Apple               | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 437       | 561    | 26.53%  |
| Crucial             | 253       | 295    | 15.36%  |
| Kingston            | 215       | 246    | 13.05%  |
| SanDisk             | 166       | 210    | 10.08%  |
| Micron Technology   | 54        | 69     | 3.28%   |
| WDC                 | 47        | 60     | 2.85%   |
| SK hynix            | 45        | 50     | 2.73%   |
| China               | 37        | 42     | 2.25%   |
| Toshiba             | 27        | 42     | 1.64%   |
| Transcend           | 24        | 30     | 1.46%   |
| Apple               | 24        | 26     | 1.46%   |
| SPCC                | 22        | 27     | 1.34%   |
| LITEON              | 22        | 25     | 1.34%   |
| Intel               | 22        | 27     | 1.34%   |
| Intenso             | 18        | 18     | 1.09%   |
| Netac               | 17        | 18     | 1.03%   |
| Teclast             | 15        | 20     | 0.91%   |
| KingDian            | 15        | 20     | 0.91%   |
| A-DATA Technology   | 13        | 15     | 0.79%   |
| PNY                 | 10        | 11     | 0.61%   |
| Drevo               | 10        | 11     | 0.61%   |
| Patriot             | 9         | 12     | 0.55%   |
| LITEONIT            | 9         | 20     | 0.55%   |
| Unknown             | 9         | 15     | 0.55%   |
| Corsair             | 8         | 9      | 0.49%   |
| Microtech           | 7         | 17     | 0.43%   |
| GOODRAM             | 7         | 8      | 0.43%   |
| Dogfish             | 7         | 8      | 0.43%   |
| Verbatim            | 5         | 10     | 0.3%    |
| TCSUNBOW            | 5         | 5      | 0.3%    |
| FORESEE             | 5         | 5      | 0.3%    |
| External            | 5         | 6      | 0.3%    |
| Leven               | 4         | 4      | 0.24%   |
| KingSpec            | 4         | 5      | 0.24%   |
| Hewlett-Packard     | 4         | 5      | 0.24%   |
| BAITITON            | 4         | 6      | 0.24%   |
| TO Exter            | 3         | 3      | 0.18%   |
| Team                | 3         | 3      | 0.18%   |
| Phison              | 3         | 4      | 0.18%   |
| OCZ                 | 3         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1554      | 2024   | 34.18%  |
| HDD     | 1453      | 1830   | 31.96%  |
| NVMe    | 1173      | 1608   | 25.8%   |
| MMC     | 292       | 407    | 6.42%   |
| Unknown | 74        | 89     | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2718      | 3750   | 62.51%  |
| NVMe | 1166      | 1594   | 26.82%  |
| MMC  | 292       | 407    | 6.72%   |
| SAS  | 172       | 207    | 3.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2236      | 2949   | 75.85%  |
| 0.51-1.0   | 646       | 826    | 21.91%  |
| 1.01-2.0   | 47        | 57     | 1.59%   |
| 3.01-4.0   | 16        | 19     | 0.54%   |
| 4.01-10.0  | 2         | 2      | 0.07%   |
| 10.01-20.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1228      | 29.98%  |
| 251-500        | 1054      | 25.73%  |
| 501-1000       | 450       | 10.99%  |
| 1-20           | 420       | 10.25%  |
| 51-100         | 340       | 8.3%    |
| 21-50          | 212       | 5.18%   |
| 1001-2000      | 190       | 4.64%   |
| Unknown        | 87        | 2.12%   |
| 2001-3000      | 62        | 1.51%   |
| More than 3000 | 53        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1861      | 43.72%  |
| 21-50          | 686       | 16.11%  |
| 101-250        | 575       | 13.51%  |
| 51-100         | 520       | 12.22%  |
| 251-500        | 302       | 7.09%   |
| 501-1000       | 149       | 3.5%    |
| Unknown        | 87        | 2.04%   |
| 1001-2000      | 45        | 1.06%   |
| More than 3000 | 16        | 0.38%   |
| 2001-3000      | 16        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 14        | 16     | 5.56%   |
| Seagate ST9500325AS 500GB                      | 7         | 7      | 2.78%   |
| Seagate ST1000LM035-1RK172 970GB               | 7         | 9      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 6      | 2.38%   |
| Hitachi HTS725050A9A364 500GB                  | 6         | 6      | 2.38%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 1.98%   |
| Toshiba MQ01ABF050 500GB                       | 5         | 5      | 1.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 1.98%   |
| Hitachi HTS545050A7E380 500GB                  | 4         | 4      | 1.59%   |
| HGST HTS725050A7E630 500GB                     | 4         | 5      | 1.59%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.19%   |
| Toshiba MK5065GSX 500GB                        | 3         | 3      | 1.19%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 3         | 3      | 1.19%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.19%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 1.19%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 3         | 3      | 1.19%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 3         | 3      | 1.19%   |
| Hitachi HTS547550A9E384 500GB                  | 3         | 3      | 1.19%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 1.19%   |
| HGST HTS721010A9E630 1TB                       | 3         | 3      | 1.19%   |
| HGST HTS541075A9E680 752GB                     | 3         | 6      | 1.19%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 2         | 2      | 0.79%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.79%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 2         | 2      | 0.79%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 2         | 2      | 0.79%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.79%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.79%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.79%   |
| Seagate ST500LM021-1KJ152 500GB                | 2         | 2      | 0.79%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.79%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 0.79%   |
| Kingston SA400S37240G 240GB SSD                | 2         | 2      | 0.79%   |
| Hitachi HTS547575A9E384 752GB                  | 2         | 2      | 0.79%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.79%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.79%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.79%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 0.79%   |
| Yangtze Memory Technologies YMTC PC005 256GB   | 1         | 1      | 0.4%    |
| WINTEC 240GB SATA3 SF2281 SSD                  | 1         | 1      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 57        | 60     | 22.62%  |
| Hitachi                     | 42        | 43     | 16.67%  |
| WDC                         | 30        | 35     | 11.9%   |
| Toshiba                     | 30        | 31     | 11.9%   |
| HGST                        | 28        | 34     | 11.11%  |
| SK hynix                    | 9         | 11     | 3.57%   |
| Samsung Electronics         | 9         | 9      | 3.57%   |
| Crucial                     | 8         | 8      | 3.17%   |
| Micron Technology           | 7         | 7      | 2.78%   |
| Kingston                    | 5         | 5      | 1.98%   |
| Intel                       | 4         | 6      | 1.59%   |
| Fujitsu                     | 4         | 4      | 1.59%   |
| SanDisk                     | 3         | 3      | 1.19%   |
| Drevo                       | 2         | 2      | 0.79%   |
| Yangtze Memory Technologies | 1         | 1      | 0.4%    |
| WINTEC                      | 1         | 1      | 0.4%    |
| WDC WDS2                    | 1         | 1      | 0.4%    |
| Unknown                     | 1         | 1      | 0.4%    |
| Transcend                   | 1         | 2      | 0.4%    |
| Teclast                     | 1         | 1      | 0.4%    |
| TCSUNBOW                    | 1         | 1      | 0.4%    |
| SSSTC                       | 1         | 1      | 0.4%    |
| NGFF                        | 1         | 1      | 0.4%    |
| LITEON                      | 1         | 1      | 0.4%    |
| KingSpec                    | 1         | 1      | 0.4%    |
| KingDian                    | 1         | 1      | 0.4%    |
| BAITITON                    | 1         | 3      | 0.4%    |
| A-DATA Technology           | 1         | 1      | 0.4%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 60     | 29.69%  |
| Hitachi             | 42        | 43     | 21.88%  |
| WDC                 | 29        | 34     | 15.1%   |
| Toshiba             | 28        | 29     | 14.58%  |
| HGST                | 28        | 34     | 14.58%  |
| Fujitsu             | 4         | 4      | 2.08%   |
| Samsung Electronics | 3         | 3      | 1.56%   |
| Unknown             | 1         | 1      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 191       | 208    | 76.1%   |
| SSD  | 54        | 57     | 21.51%  |
| NVMe | 6         | 10     | 2.39%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 11.11%  |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 11.11%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 11.11%  |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 11.11%  |
| Seagate ST9500420AS 500GB                        | 1         | 3      | 11.11%  |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 11.11%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 11.11%  |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 44.44%  |
| Seagate             | 2         | 4      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 1      | 11.11%  |
| Hitachi             | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2283      | 3510   | 55.37%  |
| Works    | 1580      | 2162   | 38.32%  |
| Malfunc  | 251       | 275    | 6.09%   |
| Failed   | 9         | 11     | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2749      | 61.72%  |
| AMD                              | 446       | 10.01%  |
| Samsung Electronics              | 411       | 9.23%   |
| SanDisk                          | 198       | 4.45%   |
| SK hynix                         | 125       | 2.81%   |
| Kingston Technology Company      | 79        | 1.77%   |
| Micron Technology                | 73        | 1.64%   |
| Toshiba America Info Systems     | 72        | 1.62%   |
| KIOXIA                           | 62        | 1.39%   |
| Phison Electronics               | 53        | 1.19%   |
| Nvidia                           | 47        | 1.06%   |
| Silicon Integrated Systems [SiS] | 24        | 0.54%   |
| Micron/Crucial Technology        | 23        | 0.52%   |
| Silicon Motion                   | 13        | 0.29%   |
| Union Memory (Shenzhen)          | 11        | 0.25%   |
| Solid State Storage Technology   | 11        | 0.25%   |
| VIA Technologies                 | 7         | 0.16%   |
| Lite-On Technology               | 7         | 0.16%   |
| Lenovo                           | 7         | 0.16%   |
| Apple                            | 7         | 0.16%   |
| ADATA Technology                 | 7         | 0.16%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| Silicon Image                    | 3         | 0.07%   |
| Seagate Technology               | 3         | 0.07%   |
| ASMedia Technology               | 3         | 0.07%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| Realtek Semiconductor            | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| JMicron Technology               | 2         | 0.04%   |
| O2 Micro                         | 1         | 0.02%   |
| Marvell Technology Group         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 362       | 7.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 328       | 6.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 255       | 5.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 229       | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 209       | 4.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 206       | 4.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 188       | 3.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 155       | 3.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 122       | 2.53%   |
| Samsung NVMe SSD Controller 980                                                  | 113       | 2.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 108       | 2.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 105       | 2.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 105       | 2.18%   |
| Intel Volume Management Device NVMe RAID Controller                              | 103       | 2.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 95        | 1.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 87        | 1.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 79        | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 74        | 1.54%   |
| Micron NVMe Storage Controller                                                   | 72        | 1.5%    |
| Intel Comet Lake SATA AHCI Controller                                            | 59        | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 55        | 1.14%   |
| Intel SSD 660P Series                                                            | 52        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 52        | 1.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 50        | 1.04%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 48        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 46        | 0.96%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 44        | 0.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 44        | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 42        | 0.87%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 40        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 40        | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 40        | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 39        | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 39        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 36        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 35        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 34        | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 33        | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 32        | 0.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 30        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2747      | 59.15%  |
| NVMe | 1174      | 25.28%  |
| IDE  | 383       | 8.25%   |
| RAID | 340       | 7.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3208      | 82.7%   |
| AMD          | 667       | 17.2%   |
| CentaurHauls | 2         | 0.05%   |
| ARM          | 1         | 0.03%   |
| Unknown      | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 85        | 2.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 64        | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 59        | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 53        | 1.37%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 52        | 1.34%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 1.24%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 46        | 1.19%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 46        | 1.19%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 45        | 1.16%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 44        | 1.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 42        | 1.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 41        | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 39        | 1%      |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 37        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 35        | 0.9%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 35        | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 34        | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 34        | 0.88%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 34        | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 27        | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 27        | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 27        | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 26        | 0.67%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 24        | 0.62%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 0.62%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 23        | 0.59%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 23        | 0.59%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 23        | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 23        | 0.59%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 23        | 0.59%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 23        | 0.59%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 22        | 0.57%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 21        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 972       | 25.05%  |
| Intel Core i5           | 749       | 19.3%   |
| Intel Core 2 Duo        | 278       | 7.16%   |
| Intel Core i3           | 273       | 7.04%   |
| Other                   | 272       | 7.01%   |
| Intel Celeron           | 238       | 6.13%   |
| Intel Atom              | 163       | 4.2%    |
| AMD Ryzen 5             | 137       | 3.53%   |
| AMD Ryzen 7             | 134       | 3.45%   |
| Intel Pentium           | 50        | 1.29%   |
| AMD E1                  | 45        | 1.16%   |
| Intel Pentium Dual-Core | 42        | 1.08%   |
| Intel Pentium Dual      | 36        | 0.93%   |
| Intel Genuine           | 35        | 0.9%    |
| Intel Core 2            | 32        | 0.82%   |
| AMD A4                  | 32        | 0.82%   |
| AMD A8                  | 30        | 0.77%   |
| AMD A10                 | 29        | 0.75%   |
| AMD A6                  | 27        | 0.7%    |
| AMD Ryzen 3             | 24        | 0.62%   |
| AMD E2                  | 22        | 0.57%   |
| AMD Ryzen 9             | 20        | 0.52%   |
| Intel Core i9           | 19        | 0.49%   |
| Intel Pentium M         | 16        | 0.41%   |
| Intel Pentium Silver    | 15        | 0.39%   |
| AMD Turion 64 X2 Mobile | 15        | 0.39%   |
| AMD Ryzen 7 PRO         | 14        | 0.36%   |
| Intel Celeron M         | 13        | 0.34%   |
| AMD Sempron             | 13        | 0.34%   |
| AMD Ryzen 5 PRO         | 11        | 0.28%   |
| AMD E                   | 10        | 0.26%   |
| AMD Mobile Sempron      | 9         | 0.23%   |
| Intel Core m3           | 8         | 0.21%   |
| Intel Celeron Dual-Core | 8         | 0.21%   |
| AMD A12                 | 8         | 0.21%   |
| AMD Athlon II           | 7         | 0.18%   |
| Intel Core M            | 6         | 0.15%   |
| Intel Core Duo          | 4         | 0.1%    |
| AMD Turion 64 Mobile    | 4         | 0.1%    |
| AMD C-60                | 4         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1983      | 51.07%  |
| 4       | 1278      | 32.91%  |
| 6       | 207       | 5.33%   |
| 8       | 189       | 4.87%   |
| 1       | 167       | 4.3%    |
| 14      | 29        | 0.75%   |
| 10      | 19        | 0.49%   |
| 12      | 9         | 0.23%   |
| 5       | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3879      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2694      | 69.33%  |
| 1       | 1189      | 30.6%   |
| 4       | 2         | 0.05%   |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3756      | 96.7%   |
| 32-bit         | 99        | 2.55%   |
| Unknown        | 29        | 0.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 831       | 20.68%  |
| 0x306a9    | 209       | 5.2%    |
| 0x206a7    | 202       | 5.03%   |
| 0x40651    | 141       | 3.51%   |
| 0x1067a    | 141       | 3.51%   |
| 0x806ea    | 140       | 3.48%   |
| 0x806ec    | 131       | 3.26%   |
| 0x806c1    | 122       | 3.04%   |
| 0x406e3    | 121       | 3.01%   |
| 0x806e9    | 102       | 2.54%   |
| 0x6fd      | 95        | 2.36%   |
| 0x20655    | 90        | 2.24%   |
| 0x906ea    | 87        | 2.16%   |
| 0x306c3    | 86        | 2.14%   |
| 0x306d4    | 81        | 2.02%   |
| 0x10676    | 71        | 1.77%   |
| 0x08108109 | 64        | 1.59%   |
| 0x706e5    | 57        | 1.42%   |
| 0x406c3    | 51        | 1.27%   |
| 0x806eb    | 49        | 1.22%   |
| 0x30678    | 47        | 1.17%   |
| 0x906e9    | 46        | 1.14%   |
| 0x20652    | 44        | 1.09%   |
| 0x08608103 | 43        | 1.07%   |
| 0xa0652    | 42        | 1.05%   |
| 0x06006705 | 42        | 1.05%   |
| 0x106ca    | 40        | 1%      |
| 0x0a50000c | 40        | 1%      |
| 0x406c4    | 39        | 0.97%   |
| 0x706a8    | 38        | 0.95%   |
| 0x706a1    | 36        | 0.9%    |
| 0x506e3    | 32        | 0.8%    |
| 0x506c9    | 32        | 0.8%    |
| 0x08600106 | 29        | 0.72%   |
| 0x07030105 | 29        | 0.72%   |
| 0x08108102 | 27        | 0.67%   |
| 0x906a3    | 26        | 0.65%   |
| 0x106c2    | 26        | 0.65%   |
| 0x08600104 | 25        | 0.62%   |
| 0x6f6      | 23        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 687       | 17.7%   |
| Haswell          | 296       | 7.62%   |
| IvyBridge        | 259       | 6.67%   |
| Penryn           | 250       | 6.44%   |
| SandyBridge      | 243       | 6.26%   |
| Skylake          | 196       | 5.05%   |
| Core             | 187       | 4.82%   |
| Silvermont       | 168       | 4.33%   |
| TigerLake        | 159       | 4.1%    |
| Westmere         | 156       | 4.02%   |
| Unknown          | 118       | 3.04%   |
| Zen+             | 106       | 2.73%   |
| Broadwell        | 103       | 2.65%   |
| Excavator        | 91        | 2.34%   |
| Goldmont plus    | 90        | 2.32%   |
| IceLake          | 82        | 2.11%   |
| Bonnell          | 81        | 2.09%   |
| Zen 2            | 76        | 1.96%   |
| Zen 3            | 62        | 1.6%    |
| CometLake        | 61        | 1.57%   |
| P6               | 58        | 1.49%   |
| Puma             | 41        | 1.06%   |
| Alderlake Hybrid | 41        | 1.06%   |
| Goldmont         | 40        | 1.03%   |
| Jaguar           | 39        | 1%      |
| K8 Hammer        | 38        | 0.98%   |
| Bobcat           | 30        | 0.77%   |
| Zen              | 24        | 0.62%   |
| K10              | 21        | 0.54%   |
| Nehalem          | 20        | 0.52%   |
| K8 & K10 hybrid  | 17        | 0.44%   |
| K10 Llano        | 14        | 0.36%   |
| Steamroller      | 12        | 0.31%   |
| Piledriver       | 9         | 0.23%   |
| Tremont          | 4         | 0.1%    |
| NetBurst         | 3         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2818      | 56.87%  |
| Nvidia                           | 1143      | 23.07%  |
| AMD                              | 974       | 19.66%  |
| Silicon Integrated Systems [SiS] | 14        | 0.28%   |
| VIA Technologies                 | 5         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 242       | 4.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 214       | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 172       | 3.31%   |
| Intel UHD Graphics 620                                                                   | 169       | 3.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 148       | 2.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 139       | 2.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 137       | 2.64%   |
| Intel HD Graphics 620                                                                    | 116       | 2.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 113       | 2.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 109       | 2.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 108       | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 106       | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 103       | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 92        | 1.77%   |
| Intel HD Graphics 5500                                                                   | 88        | 1.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 75        | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 74        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 74        | 1.43%   |
| AMD Renoir                                                                               | 74        | 1.43%   |
| AMD Lucienne                                                                             | 69        | 1.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 66        | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 62        | 1.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 62        | 1.19%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 60        | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 55        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 53        | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 53        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 0.98%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 48        | 0.92%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 44        | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 42        | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                            | 41        | 0.79%   |
| Intel HD Graphics 630                                                                    | 41        | 0.79%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 40        | 0.77%   |
| Intel HD Graphics 530                                                                    | 39        | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                                            | 36        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 36        | 0.69%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 35        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1786      | 45.94%  |
| Intel + Nvidia  | 850       | 21.86%  |
| 1 x AMD         | 662       | 17.03%  |
| 1 x Nvidia      | 237       | 6.1%    |
| Intel + AMD     | 171       | 4.4%    |
| 2 x AMD         | 90        | 2.31%   |
| AMD + Nvidia    | 54        | 1.39%   |
| 1 x SiS         | 14        | 0.36%   |
| 2 x Intel       | 9         | 0.23%   |
| Other           | 5         | 0.13%   |
| 1 x VIA         | 5         | 0.13%   |
| 2 x Nvidia      | 4         | 0.1%    |
| 1 x S3 Graphics | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3312      | 84.34%  |
| Proprietary | 512       | 13.04%  |
| Unknown     | 103       | 2.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2399      | 60.26%  |
| 0.01-0.5   | 560       | 14.07%  |
| 1.01-2.0   | 524       | 13.16%  |
| 0.51-1.0   | 269       | 6.76%   |
| 3.01-4.0   | 165       | 4.14%   |
| 5.01-6.0   | 36        | 0.9%    |
| 7.01-8.0   | 18        | 0.45%   |
| 2.01-3.0   | 9         | 0.23%   |
| 8.01-16.0  | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 807       | 19.19%  |
| Chimei Innolux          | 618       | 14.7%   |
| LG Display              | 556       | 13.22%  |
| BOE                     | 538       | 12.79%  |
| Samsung Electronics     | 487       | 11.58%  |
| Chi Mei Optoelectronics | 130       | 3.09%   |
| Sharp                   | 105       | 2.5%    |
| Apple                   | 92        | 2.19%   |
| Goldstar                | 76        | 1.81%   |
| Philips                 | 67        | 1.59%   |
| Hewlett-Packard         | 66        | 1.57%   |
| LG Philips              | 63        | 1.5%    |
| PANDA                   | 56        | 1.33%   |
| Lenovo                  | 53        | 1.26%   |
| Dell                    | 47        | 1.12%   |
| Ancor Communications    | 47        | 1.12%   |
| Acer                    | 35        | 0.83%   |
| HannStar                | 34        | 0.81%   |
| InfoVision              | 32        | 0.76%   |
| BenQ                    | 30        | 0.71%   |
| Sony                    | 25        | 0.59%   |
| AOC                     | 22        | 0.52%   |
| CPT                     | 21        | 0.5%    |
| CSO                     | 19        | 0.45%   |
| Toshiba                 | 14        | 0.33%   |
| Quanta Display          | 13        | 0.31%   |
| LGD                     | 13        | 0.31%   |
| ASUSTek Computer        | 9         | 0.21%   |
| Seiko/Epson             | 8         | 0.19%   |
| MSI                     | 8         | 0.19%   |
| TMX                     | 7         | 0.17%   |
| Valve                   | 6         | 0.14%   |
| InnoLux Display         | 6         | 0.14%   |
| Vestel Elektronik       | 5         | 0.12%   |
| Eizo                    | 5         | 0.12%   |
| Nvidia                  | 4         | 0.1%    |
| Iiyama                  | 4         | 0.1%    |
| Unknown                 | 3         | 0.07%   |
| Tianma XM               | 3         | 0.07%   |
| Panasonic               | 3         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 64        | 1.51%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 34        | 0.8%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 33        | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 31        | 0.73%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 30        | 0.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 30        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 29        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 28        | 0.66%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 28        | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 26        | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 25        | 0.59%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 24        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 23        | 0.54%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 21        | 0.49%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 20        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 20        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.45%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 19        | 0.45%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 17        | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 16        | 0.38%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.35%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.33%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 13        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 13        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 13        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.31%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 12        | 0.28%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 12        | 0.28%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 12        | 0.28%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 11        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1568      | 39.22%  |
| 1366x768 (WXGA)    | 1353      | 33.84%  |
| 1280x800 (WXGA)    | 283       | 7.08%   |
| 1600x900 (HD+)     | 137       | 3.43%   |
| 3840x2160 (4K)     | 128       | 3.2%    |
| 1440x900 (WXGA+)   | 67        | 1.68%   |
| 2560x1440 (QHD)    | 65        | 1.63%   |
| 1920x1200 (WUXGA)  | 61        | 1.53%   |
| 1024x600           | 59        | 1.48%   |
| 1680x1050 (WSXGA+) | 35        | 0.88%   |
| 2560x1600          | 30        | 0.75%   |
| 2160x1440          | 30        | 0.75%   |
| 2880x1800          | 23        | 0.58%   |
| 1280x1024 (SXGA)   | 23        | 0.58%   |
| 3840x2400          | 15        | 0.38%   |
| 1360x768           | 14        | 0.35%   |
| 2560x1080          | 13        | 0.33%   |
| 800x1280           | 7         | 0.18%   |
| 3440x1440          | 7         | 0.18%   |
| 3200x1800 (QHD+)   | 7         | 0.18%   |
| 3000x2000          | 7         | 0.18%   |
| 1024x768 (XGA)     | 7         | 0.18%   |
| 3072x1920          | 5         | 0.13%   |
| 2520x1680          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 1920x540           | 4         | 0.1%    |
| 1920x1280          | 4         | 0.1%    |
| Unknown            | 4         | 0.1%    |
| 3840x1080          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 3840x1600          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2880x1620          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 1680x945           | 2         | 0.05%   |
| 1600x1200          | 2         | 0.05%   |
| 1280x960           | 2         | 0.05%   |
| 1280x720 (HD)      | 2         | 0.05%   |
| 3840x1200          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2151      | 51.19%  |
| 13      | 514       | 12.23%  |
| 14      | 367       | 8.73%   |
| 17      | 194       | 4.62%   |
| 24      | 126       | 3%      |
| 27      | 114       | 2.71%   |
| 12      | 112       | 2.67%   |
| 23      | 99        | 2.36%   |
| 21      | 77        | 1.83%   |
| 10      | 66        | 1.57%   |
| 11      | 64        | 1.52%   |
| Unknown | 61        | 1.45%   |
| 16      | 45        | 1.07%   |
| 19      | 27        | 0.64%   |
| 18      | 26        | 0.62%   |
| 22      | 17        | 0.4%    |
| 31      | 15        | 0.36%   |
| 40      | 14        | 0.33%   |
| 34      | 14        | 0.33%   |
| 20      | 14        | 0.33%   |
| 84      | 11        | 0.26%   |
| 54      | 10        | 0.24%   |
| 32      | 7         | 0.17%   |
| 25      | 7         | 0.17%   |
| 8       | 6         | 0.14%   |
| 7       | 6         | 0.14%   |
| 72      | 5         | 0.12%   |
| 65      | 4         | 0.1%    |
| 52      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 26      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 58      | 2         | 0.05%   |
| 47      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 37      | 2         | 0.05%   |
| 49      | 1         | 0.02%   |
| 42      | 1         | 0.02%   |
| 39      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2742      | 65.65%  |
| 201-300        | 523       | 12.52%  |
| 501-600        | 320       | 7.66%   |
| 351-400        | 255       | 6.1%    |
| 401-500        | 146       | 3.5%    |
| Unknown        | 61        | 1.46%   |
| 601-700        | 30        | 0.72%   |
| 1001-1500      | 26        | 0.62%   |
| 701-800        | 22        | 0.53%   |
| 801-900        | 20        | 0.48%   |
| 1501-2000      | 16        | 0.38%   |
| 101-200        | 7         | 0.17%   |
| 1-100          | 6         | 0.14%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3107      | 81.83%  |
| 16/10   | 512       | 13.48%  |
| 3/2     | 54        | 1.42%   |
| Unknown | 46        | 1.21%   |
| 5/4     | 24        | 0.63%   |
| 21/9    | 21        | 0.55%   |
| 4/3     | 17        | 0.45%   |
| 0.67    | 6         | 0.16%   |
| 32/9    | 4         | 0.11%   |
| 6/5     | 2         | 0.05%   |
| 1.00    | 2         | 0.05%   |
| 2.21    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2154      | 51.38%  |
| 81-90          | 669       | 15.96%  |
| 201-250        | 268       | 6.39%   |
| 71-80          | 210       | 5.01%   |
| 121-130        | 152       | 3.63%   |
| 301-350        | 117       | 2.79%   |
| 61-70          | 108       | 2.58%   |
| 41-50          | 67        | 1.6%    |
| 51-60          | 64        | 1.53%   |
| Unknown        | 61        | 1.46%   |
| 151-200        | 54        | 1.29%   |
| 251-300        | 42        | 1%      |
| 351-500        | 39        | 0.93%   |
| More than 1000 | 37        | 0.88%   |
| 141-150        | 36        | 0.86%   |
| 111-120        | 32        | 0.76%   |
| 131-140        | 30        | 0.72%   |
| 501-1000       | 26        | 0.62%   |
| 91-100         | 14        | 0.33%   |
| 1-40           | 12        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1519      | 36.81%  |
| 101-120       | 1350      | 32.71%  |
| 51-100        | 812       | 19.68%  |
| 161-240       | 261       | 6.32%   |
| More than 240 | 96        | 2.33%   |
| Unknown       | 61        | 1.48%   |
| 1-50          | 28        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3272      | 82.34%  |
| 2     | 539       | 13.56%  |
| 0     | 117       | 2.94%   |
| 3     | 43        | 1.08%   |
| 4     | 3         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2086      | 33.52%  |
| Intel                             | 1834      | 29.47%  |
| Qualcomm Atheros                  | 976       | 15.68%  |
| Broadcom                          | 467       | 7.5%    |
| Marvell Technology Group          | 120       | 1.93%   |
| Broadcom Limited                  | 102       | 1.64%   |
| MediaTek                          | 72        | 1.16%   |
| Ralink                            | 68        | 1.09%   |
| TP-Link                           | 52        | 0.84%   |
| Ralink Technology                 | 44        | 0.71%   |
| Nvidia                            | 32        | 0.51%   |
| ASIX Electronics                  | 30        | 0.48%   |
| Dell                              | 27        | 0.43%   |
| Huawei Technologies               | 23        | 0.37%   |
| Ericsson Business Mobile Networks | 19        | 0.31%   |
| Samsung Electronics               | 18        | 0.29%   |
| Xiaomi                            | 17        | 0.27%   |
| Silicon Integrated Systems [SiS]  | 17        | 0.27%   |
| JMicron Technology                | 17        | 0.27%   |
| Attansic Technology               | 17        | 0.27%   |
| Sierra Wireless                   | 16        | 0.26%   |
| Qualcomm Atheros Communications   | 13        | 0.21%   |
| Qualcomm                          | 12        | 0.19%   |
| Hewlett-Packard                   | 11        | 0.18%   |
| Lenovo                            | 9         | 0.14%   |
| Sitecom Europe                    | 8         | 0.13%   |
| Apple                             | 7         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.1%    |
| T & A Mobile Phones               | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 6         | 0.1%    |
| DisplayLink                       | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| AMD                               | 6         | 0.1%    |
| NetGear                           | 5         | 0.08%   |
| ICS Advent                        | 5         | 0.08%   |
| Fibocom                           | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| OPPO Electronics                  | 4         | 0.06%   |
| D-Link                            | 4         | 0.06%   |
| ZyDAS                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1257      | 17.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 393       | 5.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 175       | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 170       | 2.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 168       | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 151       | 2.06%   |
| Intel Wireless 8265 / 8275                                              | 148       | 2.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 138       | 1.88%   |
| Intel Wi-Fi 6 AX200                                                     | 135       | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 128       | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 126       | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 115       | 1.57%   |
| Intel Wireless 7265                                                     | 113       | 1.54%   |
| Intel Wi-Fi 6 AX201                                                     | 110       | 1.5%    |
| Intel Wireless 3165                                                     | 107       | 1.46%   |
| Intel Wireless 7260                                                     | 90        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 84        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 82        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 79        | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 67        | 0.91%   |
| Intel WiFi Link 5100                                                    | 67        | 0.91%   |
| Intel Wireless 8260                                                     | 66        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 63        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 56        | 0.76%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 51        | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 47        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 42        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 41        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                   | 39        | 0.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 38        | 0.52%   |
| Intel Ethernet Connection I218-LM                                       | 36        | 0.49%   |
| Intel Centrino Advanced-N 6200                                          | 36        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 36        | 0.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 36        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 35        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1762      | 44.08%  |
| Qualcomm Atheros                      | 889       | 22.24%  |
| Realtek Semiconductor                 | 620       | 15.51%  |
| Broadcom                              | 336       | 8.41%   |
| MediaTek                              | 70        | 1.75%   |
| Broadcom Limited                      | 70        | 1.75%   |
| Ralink                                | 68        | 1.7%    |
| Ralink Technology                     | 44        | 1.1%    |
| TP-Link                               | 42        | 1.05%   |
| Dell                                  | 16        | 0.4%    |
| Sierra Wireless                       | 14        | 0.35%   |
| Qualcomm Atheros Communications       | 13        | 0.33%   |
| Sitecom Europe                        | 7         | 0.18%   |
| D-Link System                         | 6         | 0.15%   |
| Qualcomm                              | 5         | 0.13%   |
| NetGear                               | 5         | 0.13%   |
| FIBOCOM                               | 5         | 0.13%   |
| Belkin Components                     | 5         | 0.13%   |
| ZyDAS                                 | 3         | 0.08%   |
| D-Link                                | 3         | 0.08%   |
| ASUSTek Computer                      | 3         | 0.08%   |
| U.S. Robotics                         | 2         | 0.05%   |
| Qcom                                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| Hewlett-Packard                       | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| AVM                                   | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 175       | 4.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 170       | 4.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 168       | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 151       | 3.76%   |
| Intel Wireless 8265 / 8275                                              | 148       | 3.69%   |
| Intel Wi-Fi 6 AX200                                                     | 135       | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 128       | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 126       | 3.14%   |
| Intel Wireless 7265                                                     | 113       | 2.82%   |
| Intel Wi-Fi 6 AX201                                                     | 110       | 2.74%   |
| Intel Wireless 3165                                                     | 107       | 2.67%   |
| Intel Wireless 7260                                                     | 90        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 84        | 2.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 82        | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 1.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 79        | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 74        | 1.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 69        | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 67        | 1.67%   |
| Intel WiFi Link 5100                                                    | 67        | 1.67%   |
| Intel Wireless 8260                                                     | 66        | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 63        | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                           | 59        | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 56        | 1.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 51        | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 47        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 42        | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 38        | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 36        | 0.9%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 36        | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 35        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 34        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 32        | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 31        | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 30        | 0.75%   |
| Intel Wireless-AC 9260                                                  | 30        | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 30        | 0.75%   |
| Intel Wireless 3160                                                     | 29        | 0.72%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 29        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1855      | 57.97%  |
| Intel                            | 561       | 17.53%  |
| Qualcomm Atheros                 | 197       | 6.16%   |
| Broadcom                         | 187       | 5.84%   |
| Marvell Technology Group         | 120       | 3.75%   |
| Broadcom Limited                 | 33        | 1.03%   |
| Nvidia                           | 31        | 0.97%   |
| ASIX Electronics                 | 30        | 0.94%   |
| Huawei Technologies              | 18        | 0.56%   |
| Xiaomi                           | 17        | 0.53%   |
| JMicron Technology               | 17        | 0.53%   |
| Attansic Technology              | 17        | 0.53%   |
| Silicon Integrated Systems [SiS] | 15        | 0.47%   |
| Samsung Electronics              | 11        | 0.34%   |
| TP-Link                          | 10        | 0.31%   |
| Lenovo                           | 9         | 0.28%   |
| Qualcomm                         | 7         | 0.22%   |
| Apple                            | 7         | 0.22%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 6         | 0.19%   |
| DisplayLink                      | 6         | 0.19%   |
| ICS Advent                       | 5         | 0.16%   |
| T & A Mobile Phones              | 4         | 0.13%   |
| OPPO Electronics                 | 4         | 0.13%   |
| VIA Technologies                 | 3         | 0.09%   |
| Motorola PCS                     | 3         | 0.09%   |
| HMD Global                       | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| Sierra Wireless                  | 2         | 0.06%   |
| MediaTek                         | 2         | 0.06%   |
| LG Electronics                   | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| Google                           | 2         | 0.06%   |
| Sitecom Europe                   | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Microchip Technology             | 1         | 0.03%   |
| D-Link                           | 1         | 0.03%   |
| ADMtek                           | 1         | 0.03%   |
| Accton Technology                | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1257      | 38.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 393       | 12.19%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 138       | 4.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 115       | 3.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 41        | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                          | 39        | 1.21%   |
| Intel Ethernet Connection I218-LM                                              | 36        | 1.12%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 36        | 1.12%   |
| Intel 82577LM Gigabit Network Connection                                       | 34        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 32        | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                       | 32        | 0.99%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 31        | 0.96%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 28        | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 28        | 0.87%   |
| Intel Ethernet Connection I219-LM                                              | 27        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 26        | 0.81%   |
| Intel Ethernet Connection I217-LM                                              | 24        | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 23        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 23        | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 21        | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 21        | 0.65%   |
| Intel Ethernet Connection I219-V                                               | 20        | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 19        | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 18        | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 18        | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 17        | 0.53%   |
| Nvidia MCP79 Ethernet                                                          | 17        | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 17        | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 17        | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 17        | 0.53%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 17        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 16        | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 16        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 15        | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 15        | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 15        | 0.47%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 15        | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 14        | 0.43%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 14        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                                          | 14        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3802      | 54.49%  |
| Ethernet | 3092      | 44.31%  |
| Modem    | 77        | 1.1%    |
| Unknown  | 7         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3198      | 79.49%  |
| Ethernet | 822       | 20.43%  |
| Unknown  | 2         | 0.05%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2834      | 72.95%  |
| 1     | 940       | 24.2%   |
| 0     | 88        | 2.27%   |
| 3     | 23        | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3661      | 93.54%  |
| Yes  | 253       | 6.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1284      | 44.68%  |
| Realtek Semiconductor           | 355       | 12.35%  |
| Qualcomm Atheros Communications | 205       | 7.13%   |
| Lite-On Technology              | 167       | 5.81%   |
| IMC Networks                    | 167       | 5.81%   |
| Broadcom                        | 158       | 5.5%    |
| Foxconn / Hon Hai               | 130       | 4.52%   |
| Apple                           | 83        | 2.89%   |
| Hewlett-Packard                 | 63        | 2.19%   |
| Realtek                         | 52        | 1.81%   |
| Cambridge Silicon Radio         | 40        | 1.39%   |
| Dell                            | 39        | 1.36%   |
| Ralink                          | 34        | 1.18%   |
| Toshiba                         | 33        | 1.15%   |
| ASUSTek Computer                | 18        | 0.63%   |
| Alps Electric                   | 14        | 0.49%   |
| Ralink Technology               | 7         | 0.24%   |
| Foxconn International           | 5         | 0.17%   |
| MediaTek                        | 4         | 0.14%   |
| Chicony Electronics             | 4         | 0.14%   |
| Askey Computer                  | 4         | 0.14%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Integrated System Solution      | 2         | 0.07%   |
| Unknown                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 552       | 19.21%  |
| Realtek Bluetooth Radio                                                             | 234       | 8.14%   |
| Intel AX201 Bluetooth                                                               | 220       | 7.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 194       | 6.75%   |
| Intel AX200 Bluetooth                                                               | 130       | 4.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 121       | 4.21%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 91        | 3.17%   |
| IMC Networks Bluetooth Device                                                       | 71        | 2.47%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 55        | 1.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 48        | 1.67%   |
| Apple Bluetooth Host Controller                                                     | 45        | 1.57%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 43        | 1.5%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 43        | 1.5%    |
| Realtek 802.11ac WLAN Adapter                                                       | 42        | 1.46%   |
| IMC Networks Bluetooth Radio                                                        | 42        | 1.46%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 42        | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 40        | 1.39%   |
| Lite-On Bluetooth Device                                                            | 38        | 1.32%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 37        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 36        | 1.25%   |
| Ralink RT3290 Bluetooth                                                             | 34        | 1.18%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 31        | 1.08%   |
| Intel Bluetooth Device                                                              | 30        | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 29        | 1.01%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 29        | 1.01%   |
| Broadcom BCM2045 Bluetooth                                                          | 25        | 0.87%   |
| IMC Networks Wireless_Device                                                        | 22        | 0.77%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 22        | 0.77%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 19        | 0.66%   |
| Intel AX210 Bluetooth                                                               | 19        | 0.66%   |
| Apple Bluetooth HCI                                                                 | 19        | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 17        | 0.59%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 16        | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 16        | 0.56%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 16        | 0.56%   |
| Lite-On Wireless_Device                                                             | 15        | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 15        | 0.52%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 15        | 0.52%   |
| Apple Bluetooth USB Host Controller                                                 | 15        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3069      | 67.67%  |
| AMD                                          | 786       | 17.33%  |
| Nvidia                                       | 441       | 9.72%   |
| C-Media Electronics                          | 27        | 0.6%    |
| Silicon Integrated Systems [SiS]             | 24        | 0.53%   |
| Logitech                                     | 18        | 0.4%    |
| GN Netcom                                    | 16        | 0.35%   |
| JMTek                                        | 15        | 0.33%   |
| Realtek Semiconductor                        | 13        | 0.29%   |
| Generalplus Technology                       | 12        | 0.26%   |
| VIA Technologies                             | 7         | 0.15%   |
| Lenovo                                       | 7         | 0.15%   |
| Texas Instruments                            | 6         | 0.13%   |
| CMX Systems                                  | 6         | 0.13%   |
| Plantronics                                  | 5         | 0.11%   |
| Hewlett-Packard                              | 5         | 0.11%   |
| Apple                                        | 5         | 0.11%   |
| Huawei Technologies                          | 4         | 0.09%   |
| Fujitsu                                      | 4         | 0.09%   |
| Creative Technology                          | 4         | 0.09%   |
| BEHRINGER International                      | 4         | 0.09%   |
| Sony                                         | 3         | 0.07%   |
| Samson Technologies                          | 3         | 0.07%   |
| M-Audio                                      | 3         | 0.07%   |
| Syntek                                       | 2         | 0.04%   |
| Razer USA                                    | 2         | 0.04%   |
| Medeli Electronics                           | 2         | 0.04%   |
| Focusrite-Novation                           | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| ASUSTek Computer                             | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| TEAC                                         | 1         | 0.02%   |
| SmartlinkTechnology                          | 1         | 0.02%   |
| Schiit Audio                                 | 1         | 0.02%   |
| RODE Microphones                             | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.02%   |
| Numark                                       | 1         | 0.02%   |
| MosArt Semiconductor                         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 445       | 8.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 335       | 6.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 288       | 5.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 224       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 214       | 3.89%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 183       | 3.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 176       | 3.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 174       | 3.16%   |
| Intel 8 Series HD Audio Controller                                                                | 174       | 3.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 159       | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 140       | 2.54%   |
| AMD FCH Azalia Controller                                                                         | 129       | 2.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 125       | 2.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 124       | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 122       | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 115       | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 114       | 2.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 113       | 2.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 109       | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 104       | 1.89%   |
| Intel Broadwell-U Audio Controller                                                                | 103       | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 99        | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 90        | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 89        | 1.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 65        | 1.18%   |
| AMD High Definition Audio Controller                                                              | 62        | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 59        | 1.07%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 58        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 56        | 1.02%   |
| Intel CM238 HD Audio Controller                                                                   | 53        | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 51        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 47        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 44        | 0.8%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 44        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 40        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 38        | 0.69%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 32        | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 31        | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 31        | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 750       | 29.49%  |
| SK hynix                     | 558       | 21.94%  |
| Micron Technology            | 329       | 12.94%  |
| Unknown                      | 226       | 8.89%   |
| Kingston                     | 214       | 8.42%   |
| Crucial                      | 110       | 4.33%   |
| Ramaxel Technology           | 64        | 2.52%   |
| Elpida                       | 59        | 2.32%   |
| Unknown (ABCD)               | 52        | 2.04%   |
| A-DATA Technology            | 40        | 1.57%   |
| Corsair                      | 33        | 1.3%    |
| Nanya Technology             | 32        | 1.26%   |
| Unknown                      | 13        | 0.51%   |
| Team                         | 9         | 0.35%   |
| Transcend                    | 8         | 0.31%   |
| ASint Technology             | 6         | 0.24%   |
| Toshiba                      | 5         | 0.2%    |
| G.Skill                      | 5         | 0.2%    |
| Qimonda                      | 4         | 0.16%   |
| 48spaces                     | 4         | 0.16%   |
| Timetec                      | 3         | 0.12%   |
| Patriot                      | 2         | 0.08%   |
| Unknown (8A5D)               | 1         | 0.04%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.04%   |
| Unknown (0x5846)             | 1         | 0.04%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.04%   |
| Unigen                       | 1         | 0.04%   |
| Unifosa                      | 1         | 0.04%   |
| Smart Brazil                 | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Sesame                       | 1         | 0.04%   |
| Neo Forza                    | 1         | 0.04%   |
| Infineon                     | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Essencore Limited            | 1         | 0.04%   |
| ChangXin Memory              | 1         | 0.04%   |
| Avant                        | 1         | 0.04%   |
| Apacer                       | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 48        | 1.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 38        | 1.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 1.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 28        | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 28        | 1.03%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 28        | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.92%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 22        | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 21        | 0.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 20        | 0.74%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.7%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 19        | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 18        | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 16        | 0.59%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 16        | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 15        | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 15        | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 15        | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 15        | 0.55%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 14        | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 14        | 0.52%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 14        | 0.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 14        | 0.52%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.52%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 13        | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.48%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 13        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1012      | 46.19%  |
| DDR3    | 753       | 34.37%  |
| LPDDR4  | 133       | 6.07%   |
| DDR2    | 124       | 5.66%   |
| LPDDR3  | 62        | 2.83%   |
| SDRAM   | 47        | 2.15%   |
| Unknown | 17        | 0.78%   |
| DDR5    | 15        | 0.68%   |
| LPDDR5  | 10        | 0.46%   |
| DRAM    | 10        | 0.46%   |
| DDR     | 8         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1964      | 88.91%  |
| Row Of Chips | 223       | 10.1%   |
| DIMM         | 10        | 0.45%   |
| Chip         | 10        | 0.45%   |
| Unknown      | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 880       | 37.15%  |
| 4096  | 775       | 32.71%  |
| 2048  | 322       | 13.59%  |
| 16384 | 278       | 11.73%  |
| 1024  | 69        | 2.91%   |
| 32768 | 29        | 1.22%   |
| 512   | 15        | 0.63%   |
| 256   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 483       | 20.42%  |
| 2667    | 481       | 20.34%  |
| 3200    | 380       | 16.07%  |
| 2400    | 208       | 8.79%   |
| 1334    | 134       | 5.67%   |
| 2133    | 117       | 4.95%   |
| 1333    | 83        | 3.51%   |
| Unknown | 77        | 3.26%   |
| 667     | 72        | 3.04%   |
| 4267    | 46        | 1.95%   |
| 3266    | 38        | 1.61%   |
| 1066    | 36        | 1.52%   |
| 800     | 31        | 1.31%   |
| 1067    | 24        | 1.01%   |
| 1867    | 23        | 0.97%   |
| 4199    | 20        | 0.85%   |
| 8400    | 16        | 0.68%   |
| 4800    | 16        | 0.68%   |
| 533     | 14        | 0.59%   |
| 2048    | 12        | 0.51%   |
| 6400    | 10        | 0.42%   |
| 975     | 9         | 0.38%   |
| 4266    | 8         | 0.34%   |
| 2933    | 6         | 0.25%   |
| 3733    | 3         | 0.13%   |
| 3400    | 2         | 0.08%   |
| 1866    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 333     | 2         | 0.08%   |
| 2800    | 1         | 0.04%   |
| 2267    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 2000    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 21        | 34.43%  |
| Samsung Electronics | 15        | 24.59%  |
| Canon               | 11        | 18.03%  |
| Brother Industries  | 5         | 8.2%    |
| Seiko Epson         | 3         | 4.92%   |
| Pantum              | 2         | 3.28%   |
| Xerox               | 1         | 1.64%   |
| Sagem               | 1         | 1.64%   |
| ICS Advent          | 1         | 1.64%   |
| Apple               | 1         | 1.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 3.23%   |
| Samsung M267x 287x Series            | 2         | 3.23%   |
| Samsung M2070 Series                 | 2         | 3.23%   |
| HP OfficeJet 3830 series             | 2         | 3.23%   |
| HP Officejet 2620 series             | 2         | 3.23%   |
| Xerox B215                           | 1         | 1.61%   |
| Seiko Epson WF-2510 Series           | 1         | 1.61%   |
| Seiko Epson Printer                  | 1         | 1.61%   |
| Seiko Epson L355 Series              | 1         | 1.61%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.61%   |
| Samsung SCX-4623 Series              | 1         | 1.61%   |
| Samsung SCX-4300 Series              | 1         | 1.61%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.61%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.61%   |
| Samsung ML-1865W Series              | 1         | 1.61%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.61%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.61%   |
| Samsung C3060 Series                 | 1         | 1.61%   |
| Sagem Laser Pro LL                   | 1         | 1.61%   |
| Pantum P2500W series                 | 1         | 1.61%   |
| Pantum M6500W series                 | 1         | 1.61%   |
| ICS Advent Parallel Adapter          | 1         | 1.61%   |
| HP Officejet Pro 6230                | 1         | 1.61%   |
| HP OfficeJet 6950                    | 1         | 1.61%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.61%   |
| HP LaserJet P3005                    | 1         | 1.61%   |
| HP LaserJet P2055 series             | 1         | 1.61%   |
| HP LaserJet P1102                    | 1         | 1.61%   |
| HP LaserJet 1200                     | 1         | 1.61%   |
| HP LaserJet 1020                     | 1         | 1.61%   |
| HP LaserJet 1015                     | 1         | 1.61%   |
| HP LaserJet 1010                     | 1         | 1.61%   |
| HP ENVY 5000 series                  | 1         | 1.61%   |
| HP ENVY 4520 series                  | 1         | 1.61%   |
| HP DeskJet 940c                      | 1         | 1.61%   |
| HP DeskJet 840c                      | 1         | 1.61%   |
| HP Deskjet 3520 series               | 1         | 1.61%   |
| HP DeskJet 2700 series               | 1         | 1.61%   |
| HP Deskjet 2050 J510                 | 1         | 1.61%   |
| HP Deskjet 1510                      | 1         | 1.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 46.15%  |
| Seiko Epson     | 5         | 38.46%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.14%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.14%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.14%   |
| HP Scanjet G2710                                         | 1         | 7.14%   |
| HP ScanJet 3570c                                         | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.14%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.14%   |
| Canon CanoScan 4400F                                     | 1         | 7.14%   |
| Canon CanoScan 1220U                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 923       | 26.71%  |
| IMC Networks                           | 428       | 12.38%  |
| Realtek Semiconductor                  | 258       | 7.47%   |
| Microdia                               | 242       | 7%      |
| Quanta                                 | 181       | 5.24%   |
| Suyin                                  | 173       | 5.01%   |
| Bison Electronics                      | 150       | 4.34%   |
| Cheng Uei Precision Industry (Foxlink) | 147       | 4.25%   |
| Sunplus Innovation Technology          | 142       | 4.11%   |
| Acer                                   | 132       | 3.82%   |
| Alcor Micro                            | 90        | 2.6%    |
| Lite-On Technology                     | 85        | 2.46%   |
| Syntek                                 | 84        | 2.43%   |
| Apple                                  | 75        | 2.17%   |
| Luxvisions Innotech Limited            | 62        | 1.79%   |
| Ricoh                                  | 44        | 1.27%   |
| Silicon Motion                         | 42        | 1.22%   |
| Logitech                               | 25        | 0.72%   |
| Z-Star Microelectronics                | 19        | 0.55%   |
| ALi                                    | 16        | 0.46%   |
| Primax Electronics                     | 15        | 0.43%   |
| Samsung Electronics                    | 12        | 0.35%   |
| icSpring                               | 11        | 0.32%   |
| Lenovo                                 | 9         | 0.26%   |
| Sunplus Technology                     | 7         | 0.2%    |
| Sonix Technology                       | 7         | 0.2%    |
| Importek                               | 7         | 0.2%    |
| DigiTech                               | 6         | 0.17%   |
| ARC International                      | 6         | 0.17%   |
| Genesys Logic                          | 5         | 0.14%   |
| SunplusIT                              | 4         | 0.12%   |
| GEMBIRD                                | 4         | 0.12%   |
| Microsoft                              | 3         | 0.09%   |
| Generalplus Technology                 | 3         | 0.09%   |
| WaveRider Communications               | 2         | 0.06%   |
| USB Camera CS                          | 2         | 0.06%   |
| Pixart Imaging                         | 2         | 0.06%   |
| OmniVision Technologies                | 2         | 0.06%   |
| Nebraska Furniture Mart                | 2         | 0.06%   |
| Mustek Systems                         | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 141       | 4.06%   |
| Microdia Integrated_Webcam_HD                           | 101       | 2.91%   |
| Chicony HD WebCam                                       | 92        | 2.65%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 79        | 2.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 70        | 2.02%   |
| IMC Networks Integrated Camera                          | 68        | 1.96%   |
| Realtek Integrated_Webcam_HD                            | 53        | 1.53%   |
| Chicony USB2.0 VGA UVC WebCam                           | 43        | 1.24%   |
| Syntek Integrated Camera                                | 42        | 1.21%   |
| Realtek USB Camera                                      | 42        | 1.21%   |
| Alcor Micro SHUNCCM2MP                                  | 42        | 1.21%   |
| Chicony USB2.0 HD UVC WebCam                            | 41        | 1.18%   |
| Chicony HP Truevision HD                                | 39        | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 37        | 1.07%   |
| Acer Integrated Camera                                  | 37        | 1.07%   |
| Sunplus Integrated_Webcam_HD                            | 36        | 1.04%   |
| Quanta HP TrueVision HD Camera                          | 36        | 1.04%   |
| Chicony HP Truevision HD camera                         | 31        | 0.89%   |
| Chicony FJ Camera                                       | 30        | 0.86%   |
| Chicony HP Webcam                                       | 28        | 0.81%   |
| IMC Networks ov9734_azurewave_camera                    | 27        | 0.78%   |
| Bison HD Webcam                                         | 27        | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 27        | 0.78%   |
| Sunplus HD WebCam                                       | 26        | 0.75%   |
| Quanta HP Webcam                                        | 26        | 0.75%   |
| Chicony HP HD Camera                                    | 26        | 0.75%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.72%   |
| Acer Lenovo EasyCamera                                  | 25        | 0.72%   |
| Suyin HP Truevision HD                                  | 23        | 0.66%   |
| IMC Networks HD Camera                                  | 23        | 0.66%   |
| Chicony USB2.0 Camera                                   | 23        | 0.66%   |
| Chicony HP Wide Vision HD Camera                        | 23        | 0.66%   |
| Bison SunplusIT Integrated Camera                       | 23        | 0.66%   |
| Alcor Micro Asus Integrated Webcam                      | 23        | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 22        | 0.63%   |
| Microdia Integrated Webcam                              | 22        | 0.63%   |
| Lite-On HP HD Camera                                    | 22        | 0.63%   |
| IMC Networks UVC VGA Webcam                             | 22        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 22        | 0.63%   |
| Bison Integrated Camera                                 | 22        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 197       | 29.89%  |
| Synaptics                          | 144       | 21.85%  |
| Shenzhen Goodix Technology         | 112       | 17%     |
| Elan Microelectronics              | 77        | 11.68%  |
| Upek                               | 41        | 6.22%   |
| AuthenTec                          | 38        | 5.77%   |
| LighTuning Technology              | 37        | 5.61%   |
| STMicroelectronics                 | 6         | 0.91%   |
| Focal-systems.Corp                 | 4         | 0.61%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.3%    |
| Microsoft                          | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 86        | 13.05%  |
| Elan ELAN:ARM-M4                                                           | 52        | 7.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 42        | 6.37%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 39        | 5.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 5.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 26        | 3.95%   |
| Elan ELAN:Fingerprint                                                      | 25        | 3.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 23        | 3.49%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 21        | 3.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 2.88%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 18        | 2.73%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 2.43%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 15        | 2.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 2.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 2.12%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 13        | 1.97%   |
| Validity Sensors VFS491                                                    | 11        | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.67%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 1.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.52%   |
| Unknown                                                                    | 10        | 1.52%   |
| Synaptics  WBDI                                                            | 9         | 1.37%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 1.21%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.21%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 1.06%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.06%   |
| AuthenTec AES1600                                                          | 7         | 1.06%   |
| Synaptics UWP WBDI                                                         | 6         | 0.91%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.91%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.91%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.91%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.91%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 0.76%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.76%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.76%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.76%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.61%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.61%   |
| AuthenTec AES2810                                                          | 4         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 103       | 39.77%  |
| Alcor Micro              | 85        | 32.82%  |
| O2 Micro                 | 27        | 10.42%  |
| Lenovo                   | 16        | 6.18%   |
| Upek                     | 11        | 4.25%   |
| Gemalto (was Gemplus)    | 4         | 1.54%   |
| Advanced Card Systems    | 4         | 1.54%   |
| Bit4id                   | 3         | 1.16%   |
| Realtek Semiconductor    | 2         | 0.77%   |
| SCM Microsystems         | 1         | 0.39%   |
| Reiner SCT Kartensysteme | 1         | 0.39%   |
| OmniKey                  | 1         | 0.39%   |
| In Focus Systems         | 1         | 0.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 82        | 31.66%  |
| Broadcom BCM5880 Secure Applications Processor                               | 32        | 12.36%  |
| Broadcom 58200                                                               | 28        | 10.81%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 8.88%   |
| Broadcom 5880                                                                | 21        | 8.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 7.72%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.18%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 4.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.54%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.16%   |
| Bit4id miniLector EVO                                                        | 3         | 1.16%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.16%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.16%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.77%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.39%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.39%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.39%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.39%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.39%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2447      | 61.39%  |
| 1     | 1203      | 30.18%  |
| 2     | 295       | 7.4%    |
| 3     | 28        | 0.7%    |
| 4     | 10        | 0.25%   |
| 5     | 2         | 0.05%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 651       | 34.96%  |
| Graphics card            | 452       | 24.27%  |
| Chipcard                 | 227       | 12.19%  |
| Net/wireless             | 169       | 9.08%   |
| Multimedia controller    | 88        | 4.73%   |
| Camera                   | 66        | 3.54%   |
| Bluetooth                | 59        | 3.17%   |
| Storage                  | 30        | 1.61%   |
| Communication controller | 27        | 1.45%   |
| Sound                    | 19        | 1.02%   |
| Flash memory             | 18        | 0.97%   |
| Modem                    | 17        | 0.91%   |
| Net/ethernet             | 13        | 0.7%    |
| Card reader              | 13        | 0.7%    |
| Network                  | 6         | 0.32%   |
| Storage/ide              | 2         | 0.11%   |
| Dvb card                 | 2         | 0.11%   |
| Wireless                 | 1         | 0.05%   |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |

