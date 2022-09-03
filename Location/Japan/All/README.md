Linux in Japan - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Japan/Desktop/README.md) and [notebooks](/Location/Japan/Notebook/README.md).

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

Total: 1332

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | D34010WYB H14771-304        | Desktop     | [47d9609ba8](https://linux-hardware.org/?probe=47d9609ba8) | Sep 01, 2022 |
| Intel         | D34010WYB H14771-304        | Desktop     | [fd34481bf8](https://linux-hardware.org/?probe=fd34481bf8) | Sep 01, 2022 |
| HP            | 18E7                        | Desktop     | [613d55d0e9](https://linux-hardware.org/?probe=613d55d0e9) | Aug 27, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| Biostar       | B660MX-E                    | Desktop     | [4fa9d132c2](https://linux-hardware.org/?probe=4fa9d132c2) | Aug 26, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [05a337504b](https://linux-hardware.org/?probe=05a337504b) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | Notebook    | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| Sony          | VAIO                        | All in one  | [3ed1ad79e4](https://linux-hardware.org/?probe=3ed1ad79e4) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | Desktop     | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [f50babde6a](https://linux-hardware.org/?probe=f50babde6a) | Aug 23, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [7596762e80](https://linux-hardware.org/?probe=7596762e80) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [bbcdb246aa](https://linux-hardware.org/?probe=bbcdb246aa) | Aug 16, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [79b28d4c5f](https://linux-hardware.org/?probe=79b28d4c5f) | Aug 16, 2022 |
| Toshiba       | dynabook T75/RW             | Notebook    | [ff35aa835d](https://linux-hardware.org/?probe=ff35aa835d) | Aug 15, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [5106d4eda8](https://linux-hardware.org/?probe=5106d4eda8) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| Dell          | 0978PJ A03                  | Server      | [382f999542](https://linux-hardware.org/?probe=382f999542) | Aug 14, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [e59ee250ad](https://linux-hardware.org/?probe=e59ee250ad) | Aug 13, 2022 |
| System76      | Oryx Pro                    | Notebook    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [4ec9a5896d](https://linux-hardware.org/?probe=4ec9a5896d) | Aug 12, 2022 |
| Sony          | VAIO                        | All in one  | [2defaa2f88](https://linux-hardware.org/?probe=2defaa2f88) | Aug 10, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [b87492e7c7](https://linux-hardware.org/?probe=b87492e7c7) | Aug 08, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| Sony          | VAIO                        | All in one  | [dd9f2633fe](https://linux-hardware.org/?probe=dd9f2633fe) | Aug 07, 2022 |
| Toshiba       | dynabook R732/G             | Notebook    | [82ef8736b3](https://linux-hardware.org/?probe=82ef8736b3) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9be9a3e83b](https://linux-hardware.org/?probe=9be9a3e83b) | Aug 01, 2022 |
| Toshiba       | All In One PC MP            | All in one  | [4d493ab3df](https://linux-hardware.org/?probe=4d493ab3df) | Jul 31, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [ea8bb6486b](https://linux-hardware.org/?probe=ea8bb6486b) | Jul 30, 2022 |
| ASUSTek       | M4N78                       | Desktop     | [870702db59](https://linux-hardware.org/?probe=870702db59) | Jul 29, 2022 |
| Toshiba       | dynabook B350/22A           | Notebook    | [7a5344db19](https://linux-hardware.org/?probe=7a5344db19) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | Desktop     | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Toshiba       | dynabook R734/K             | Notebook    | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| NEC Comput... | U2                          | Notebook    | [22314f4475](https://linux-hardware.org/?probe=22314f4475) | Jul 25, 2022 |
| Dell          | Latitude 7320               | Notebook    | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| ASRock        | H470M Pro4                  | Desktop     | [5a709f059c](https://linux-hardware.org/?probe=5a709f059c) | Jul 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b63e85ff7e](https://linux-hardware.org/?probe=b63e85ff7e) | Jul 25, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | Desktop     | [36edefbce1](https://linux-hardware.org/?probe=36edefbce1) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [de6f28d0f7](https://linux-hardware.org/?probe=de6f28d0f7) | Jul 24, 2022 |
| ASRock        | J5005-ITX                   | Desktop     | [8fdd045c35](https://linux-hardware.org/?probe=8fdd045c35) | Jul 24, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [9a3ffce1a4](https://linux-hardware.org/?probe=9a3ffce1a4) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| GALAX         | H310M-A V2                  | Desktop     | [db46aaa3aa](https://linux-hardware.org/?probe=db46aaa3aa) | Jul 24, 2022 |
| Alienware     | m17                         | Notebook    | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [a09d9de883](https://linux-hardware.org/?probe=a09d9de883) | Jul 23, 2022 |
| NEC Comput... | PC-VJ24LLZCB                | Notebook    | [9b0955cfe2](https://linux-hardware.org/?probe=9b0955cfe2) | Jul 23, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [90878188d1](https://linux-hardware.org/?probe=90878188d1) | Jul 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| MouseCompu... | L140MU                      | Notebook    | [5206d679a2](https://linux-hardware.org/?probe=5206d679a2) | Jul 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [a81e48e206](https://linux-hardware.org/?probe=a81e48e206) | Jul 15, 2022 |
| Panasonic     | CF-S10EYADR                 | Notebook    | [1990cd2a08](https://linux-hardware.org/?probe=1990cd2a08) | Jul 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [08b3f5414e](https://linux-hardware.org/?probe=08b3f5414e) | Jul 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [42d81e0803](https://linux-hardware.org/?probe=42d81e0803) | Jul 13, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| ASRock        | AMCP7A-ION                  | Desktop     | [339f0e7944](https://linux-hardware.org/?probe=339f0e7944) | Jul 10, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [8cf2a64c6b](https://linux-hardware.org/?probe=8cf2a64c6b) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [85fe785be5](https://linux-hardware.org/?probe=85fe785be5) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [27c1dae829](https://linux-hardware.org/?probe=27c1dae829) | Jul 08, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [6d403c021c](https://linux-hardware.org/?probe=6d403c021c) | Jun 29, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [ba68b99167](https://linux-hardware.org/?probe=ba68b99167) | Jun 27, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [fc3e083086](https://linux-hardware.org/?probe=fc3e083086) | Jun 26, 2022 |
| MSI           | Creator X299                | Desktop     | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b841edf2b7](https://linux-hardware.org/?probe=b841edf2b7) | Jun 19, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [2f722cf462](https://linux-hardware.org/?probe=2f722cf462) | Jun 17, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [055ed7de1b](https://linux-hardware.org/?probe=055ed7de1b) | Jun 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [cbf5603095](https://linux-hardware.org/?probe=cbf5603095) | Jun 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [197482fd83](https://linux-hardware.org/?probe=197482fd83) | Jun 13, 2022 |
| Nvidia        | Tegra                       | Soc         | [1ae160fee2](https://linux-hardware.org/?probe=1ae160fee2) | Jun 13, 2022 |
| Intel         | DB75EN AAG39650-400         | Desktop     | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9de5875af1](https://linux-hardware.org/?probe=9de5875af1) | Jun 08, 2022 |
| Sony          | VGN-Z71JB                   | Notebook    | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [d4a2222ff7](https://linux-hardware.org/?probe=d4a2222ff7) | Jun 07, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [fa1a1d1431](https://linux-hardware.org/?probe=fa1a1d1431) | Jun 07, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| Alienware     | 13 R3                       | Notebook    | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [00e3c7f3c6](https://linux-hardware.org/?probe=00e3c7f3c6) | Jun 03, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [0d24b53837](https://linux-hardware.org/?probe=0d24b53837) | Jun 02, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [c40635b66e](https://linux-hardware.org/?probe=c40635b66e) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [ca67455f28](https://linux-hardware.org/?probe=ca67455f28) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [bcca466c5e](https://linux-hardware.org/?probe=bcca466c5e) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [b83d80f5d2](https://linux-hardware.org/?probe=b83d80f5d2) | May 29, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| Teclast       | X16                         | Tablet      | [f896e98656](https://linux-hardware.org/?probe=f896e98656) | May 28, 2022 |
| ASUSTek       | 900                         | Notebook    | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | Notebook    | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| Gateway       | NV57H                       | Notebook    | [75c484ec74](https://linux-hardware.org/?probe=75c484ec74) | May 26, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [515c374814](https://linux-hardware.org/?probe=515c374814) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [e38c676047](https://linux-hardware.org/?probe=e38c676047) | May 26, 2022 |
| MouseCompu... | B5-R5RENASW11               | Notebook    | [35eae81eca](https://linux-hardware.org/?probe=35eae81eca) | May 25, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [4f2f7e71db](https://linux-hardware.org/?probe=4f2f7e71db) | May 24, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [a700df310a](https://linux-hardware.org/?probe=a700df310a) | May 23, 2022 |
| ASUSTek       | 900                         | Notebook    | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| MouseCompu... | B360M-ITX                   | Desktop     | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [671279f960](https://linux-hardware.org/?probe=671279f960) | May 18, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [05d8136964](https://linux-hardware.org/?probe=05d8136964) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Alienware     | 17                          | Notebook    | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [95339de38e](https://linux-hardware.org/?probe=95339de38e) | May 13, 2022 |
| Unknown       | MSL01 Series                | Desktop     | [1c66319969](https://linux-hardware.org/?probe=1c66319969) | May 11, 2022 |
| MouseCompu... | X99-S01                     | Desktop     | [69ac1048e9](https://linux-hardware.org/?probe=69ac1048e9) | May 11, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [fff817aea6](https://linux-hardware.org/?probe=fff817aea6) | May 10, 2022 |
| Thirdwave     | DX-T7                       | Notebook    | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Fujitsu       | FMVNTCAKB                   | Notebook    | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| ASUSTek       | 900                         | Notebook    | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [78b1868a67](https://linux-hardware.org/?probe=78b1868a67) | May 08, 2022 |
| ASUSTek       | 900                         | Notebook    | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| Toshiba       | dynabook R731/37EK          | Notebook    | [10ed6c8741](https://linux-hardware.org/?probe=10ed6c8741) | May 06, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| ASRock        | QC5000-ITX/WiFi             | Desktop     | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| AZW           | GK mini                     | Mini pc     | [9d00f58b53](https://linux-hardware.org/?probe=9d00f58b53) | May 04, 2022 |
| AZW           | GK mini                     | Mini pc     | [d474b9b330](https://linux-hardware.org/?probe=d474b9b330) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | 900                         | Notebook    | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | Inspiron 15-3565            | Notebook    | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [b07e1c97aa](https://linux-hardware.org/?probe=b07e1c97aa) | Apr 29, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [5e6c23c3b5](https://linux-hardware.org/?probe=5e6c23c3b5) | Apr 28, 2022 |
| Dell          | Inspiron 15-3565            | Notebook    | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f6df392394](https://linux-hardware.org/?probe=f6df392394) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c9fb277b57](https://linux-hardware.org/?probe=c9fb277b57) | Apr 27, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [bbb524450f](https://linux-hardware.org/?probe=bbb524450f) | Apr 27, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| MouseCompu... | NH55Dx                      | Notebook    | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Dell          | 0NW73C A01                  | Desktop     | [430f7b0e3a](https://linux-hardware.org/?probe=430f7b0e3a) | Apr 23, 2022 |
| ASRock        | P5B-DE                      | Desktop     | [b9b6d17274](https://linux-hardware.org/?probe=b9b6d17274) | Apr 23, 2022 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [589bc2d17a](https://linux-hardware.org/?probe=589bc2d17a) | Apr 20, 2022 |
| Panasonic     | CF-S10EYADR                 | Notebook    | [efd3e5ce84](https://linux-hardware.org/?probe=efd3e5ce84) | Apr 18, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [a3996b5033](https://linux-hardware.org/?probe=a3996b5033) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Thirdwave     | DX-T7                       | Notebook    | [b03707283b](https://linux-hardware.org/?probe=b03707283b) | Apr 16, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0ad6471ecf](https://linux-hardware.org/?probe=0ad6471ecf) | Apr 16, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [973d2cc2f1](https://linux-hardware.org/?probe=973d2cc2f1) | Apr 15, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [fd8d5ab56a](https://linux-hardware.org/?probe=fd8d5ab56a) | Apr 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [3fade276ac](https://linux-hardware.org/?probe=3fade276ac) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c40cfcc7fe](https://linux-hardware.org/?probe=c40cfcc7fe) | Apr 12, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| MSI           | H170A PC MATE               | Desktop     | [404f32fc8a](https://linux-hardware.org/?probe=404f32fc8a) | Apr 11, 2022 |
| MSI           | B350I PRO AC                | Desktop     | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [5a344e20d6](https://linux-hardware.org/?probe=5a344e20d6) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | Notebook    | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [188a7794dd](https://linux-hardware.org/?probe=188a7794dd) | Apr 04, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [b7c7776f50](https://linux-hardware.org/?probe=b7c7776f50) | Apr 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [2759f18a1f](https://linux-hardware.org/?probe=2759f18a1f) | Apr 04, 2022 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [41cd5e79c8](https://linux-hardware.org/?probe=41cd5e79c8) | Apr 03, 2022 |
| MouseCompu... | MB-J370                     | Notebook    | [2c72ea9b17](https://linux-hardware.org/?probe=2c72ea9b17) | Apr 02, 2022 |
| ASUSTek       | PB50                        | Desktop     | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [d17d5e5310](https://linux-hardware.org/?probe=d17d5e5310) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [20aac26c6d](https://linux-hardware.org/?probe=20aac26c6d) | Mar 31, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | Desktop     | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| ASUSTek       | T103HAF                     | Tablet      | [fd9c463d07](https://linux-hardware.org/?probe=fd9c463d07) | Mar 28, 2022 |
| ASUSTek       | T103HAF                     | Tablet      | [a3ac6c88a7](https://linux-hardware.org/?probe=a3ac6c88a7) | Mar 27, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | Desktop     | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| System76      | Lemur Pro                   | Notebook    | [cd847b5e6a](https://linux-hardware.org/?probe=cd847b5e6a) | Mar 23, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [0e17f0194f](https://linux-hardware.org/?probe=0e17f0194f) | Mar 22, 2022 |
| Fujitsu       | FMVA05003                   | Notebook    | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [46f513206b](https://linux-hardware.org/?probe=46f513206b) | Mar 18, 2022 |
| Dell          | G3 3500                     | Notebook    | [9ca3e10f43](https://linux-hardware.org/?probe=9ca3e10f43) | Mar 14, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5c3993ef06](https://linux-hardware.org/?probe=5c3993ef06) | Mar 14, 2022 |
| R.W.C         | RM-A107-SR                  | Notebook    | [ab4bef6a90](https://linux-hardware.org/?probe=ab4bef6a90) | Mar 13, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b170ce8fbe](https://linux-hardware.org/?probe=b170ce8fbe) | Mar 11, 2022 |
| Dell          | Latitude E5470              | Notebook    | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [f1d0d25b44](https://linux-hardware.org/?probe=f1d0d25b44) | Mar 06, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | Notebook    | [2f2d99c83f](https://linux-hardware.org/?probe=2f2d99c83f) | Mar 03, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | Notebook    | [0d0a2bab7a](https://linux-hardware.org/?probe=0d0a2bab7a) | Mar 03, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| HP            | Notebook                    | Notebook    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| HP            | 18E7                        | Desktop     | [07d0861eff](https://linux-hardware.org/?probe=07d0861eff) | Feb 28, 2022 |
| ASRock        | H77M                        | Desktop     | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | Notebook    | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Fujitsu       | FMVA33LB2                   | Notebook    | [2dc30249b7](https://linux-hardware.org/?probe=2dc30249b7) | Feb 26, 2022 |
| Lenovo        | ThinkPad X220 4290LG4       | Notebook    | [bfb13999b0](https://linux-hardware.org/?probe=bfb13999b0) | Feb 26, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [0fadf2b0fa](https://linux-hardware.org/?probe=0fadf2b0fa) | Feb 23, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [ec10edeb39](https://linux-hardware.org/?probe=ec10edeb39) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | Notebook    | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [9483d7b48e](https://linux-hardware.org/?probe=9483d7b48e) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2c1109afb8](https://linux-hardware.org/?probe=2c1109afb8) | Feb 21, 2022 |
| Dell          | Vostro 3405                 | Notebook    | [f869338cb0](https://linux-hardware.org/?probe=f869338cb0) | Feb 20, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [4675d06ffb](https://linux-hardware.org/?probe=4675d06ffb) | Feb 19, 2022 |
| NEC Comput... | IH81M                       | Desktop     | [5e60991665](https://linux-hardware.org/?probe=5e60991665) | Feb 18, 2022 |
| Apple         | MacBookAir3,2               | Notebook    | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [15ae5870b9](https://linux-hardware.org/?probe=15ae5870b9) | Feb 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [e55e0df499](https://linux-hardware.org/?probe=e55e0df499) | Feb 16, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [041b4e9976](https://linux-hardware.org/?probe=041b4e9976) | Feb 16, 2022 |
| ASUSTek       | P7H55-M                     | Desktop     | [b2414fb6fc](https://linux-hardware.org/?probe=b2414fb6fc) | Feb 15, 2022 |
| Fujitsu       | FARQ02010                   | Notebook    | [04fbabcfd2](https://linux-hardware.org/?probe=04fbabcfd2) | Feb 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [efcb060233](https://linux-hardware.org/?probe=efcb060233) | Feb 14, 2022 |
| Toshiba       | dynabook QOSMIO V65/86LY... | Notebook    | [681aa0b345](https://linux-hardware.org/?probe=681aa0b345) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [1ee503a497](https://linux-hardware.org/?probe=1ee503a497) | Feb 13, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [976cefe591](https://linux-hardware.org/?probe=976cefe591) | Feb 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a5d02d3a03](https://linux-hardware.org/?probe=a5d02d3a03) | Feb 13, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [f5cef9fe9b](https://linux-hardware.org/?probe=f5cef9fe9b) | Feb 13, 2022 |
| Intel         | NUC8BEB J72692-305          | Mini pc     | [c39feb563d](https://linux-hardware.org/?probe=c39feb563d) | Feb 12, 2022 |
| MouseCompu... | B75H2-M2                    | Desktop     | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [bc3f44c0b9](https://linux-hardware.org/?probe=bc3f44c0b9) | Feb 10, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0c54ad1557](https://linux-hardware.org/?probe=0c54ad1557) | Feb 10, 2022 |
| ASUSTek       | U24A                        | Notebook    | [47e8fc096a](https://linux-hardware.org/?probe=47e8fc096a) | Feb 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [218f370835](https://linux-hardware.org/?probe=218f370835) | Feb 10, 2022 |
| Dell          | XPS L401X                   | Notebook    | [1db7a71e79](https://linux-hardware.org/?probe=1db7a71e79) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [76a7934681](https://linux-hardware.org/?probe=76a7934681) | Feb 09, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [ed806edbbb](https://linux-hardware.org/?probe=ed806edbbb) | Feb 09, 2022 |
| ASRock        | H55DE3                      | Desktop     | [7d4fb5775f](https://linux-hardware.org/?probe=7d4fb5775f) | Feb 09, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [fcaddfe60e](https://linux-hardware.org/?probe=fcaddfe60e) | Feb 09, 2022 |
| MCJ           | H67H2-M4                    | Desktop     | [3814208f36](https://linux-hardware.org/?probe=3814208f36) | Feb 08, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b9c77d9df2](https://linux-hardware.org/?probe=b9c77d9df2) | Feb 08, 2022 |
| Lenovo        | ThinkPad X240 20ALCTO1WW    | Notebook    | [1620a85467](https://linux-hardware.org/?probe=1620a85467) | Feb 08, 2022 |
| ASUSTek       | X541SA                      | Notebook    | [afafec99f9](https://linux-hardware.org/?probe=afafec99f9) | Feb 08, 2022 |
| Toshiba       | dynabook Satellite B453/... | Notebook    | [279ff9b0f0](https://linux-hardware.org/?probe=279ff9b0f0) | Feb 08, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [61cc7bdcc2](https://linux-hardware.org/?probe=61cc7bdcc2) | Feb 06, 2022 |
| ASUSTek       | S101                        | Notebook    | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [aa1c79ab75](https://linux-hardware.org/?probe=aa1c79ab75) | Feb 03, 2022 |
| Supermicro    | H8DG6/H8DGi                 | Server      | [7f27062e48](https://linux-hardware.org/?probe=7f27062e48) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek       | P8Z77-M                     | Desktop     | [cb5f618a4b](https://linux-hardware.org/?probe=cb5f618a4b) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | Desktop     | [0c1b8480b6](https://linux-hardware.org/?probe=0c1b8480b6) | Jan 31, 2022 |
| ASUSTek       | U24A                        | Notebook    | [c49e4b9513](https://linux-hardware.org/?probe=c49e4b9513) | Jan 31, 2022 |
| AMI           | Intel                       | Notebook    | [33011a4745](https://linux-hardware.org/?probe=33011a4745) | Jan 31, 2022 |
| AMI           | Intel                       | Notebook    | [f749123fdd](https://linux-hardware.org/?probe=f749123fdd) | Jan 31, 2022 |
| ASUSTek       | U24A                        | Notebook    | [cc19cff1a9](https://linux-hardware.org/?probe=cc19cff1a9) | Jan 30, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [ee9b2f44e9](https://linux-hardware.org/?probe=ee9b2f44e9) | Jan 29, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| ASUSTek       | UX303LA                     | Notebook    | [b5e498daf0](https://linux-hardware.org/?probe=b5e498daf0) | Jan 28, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [3d4087dc2a](https://linux-hardware.org/?probe=3d4087dc2a) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| HP            | 3048h                       | Desktop     | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | Desktop     | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Fujitsu       | FMVA42CW                    | Notebook    | [4ba92ab5ea](https://linux-hardware.org/?probe=4ba92ab5ea) | Jan 23, 2022 |
| Dell          | Latitude 3540               | Notebook    | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [9418716c6b](https://linux-hardware.org/?probe=9418716c6b) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [57fe150494](https://linux-hardware.org/?probe=57fe150494) | Jan 14, 2022 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [56b639daeb](https://linux-hardware.org/?probe=56b639daeb) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | Notebook    | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| ASUSTek       | N3150I-C                    | Desktop     | [ae91e3cc7b](https://linux-hardware.org/?probe=ae91e3cc7b) | Jan 13, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [8f0b1342b0](https://linux-hardware.org/?probe=8f0b1342b0) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [73ff2bcb33](https://linux-hardware.org/?probe=73ff2bcb33) | Jan 10, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [7539f3648f](https://linux-hardware.org/?probe=7539f3648f) | Jan 09, 2022 |
| ASUSTek       | P8H61-I                     | Desktop     | [261ea10bf8](https://linux-hardware.org/?probe=261ea10bf8) | Jan 08, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [7f928f794b](https://linux-hardware.org/?probe=7f928f794b) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | Notebook    | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9a29b00ea8](https://linux-hardware.org/?probe=9a29b00ea8) | Jan 01, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [618b37e477](https://linux-hardware.org/?probe=618b37e477) | Jan 01, 2022 |
| Dell          | Inspiron 5557               | Notebook    | [53d769eaf7](https://linux-hardware.org/?probe=53d769eaf7) | Dec 31, 2021 |
| System76      | Lemur Pro                   | Notebook    | [287aa601fe](https://linux-hardware.org/?probe=287aa601fe) | Dec 29, 2021 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | Notebook    | [0b20db823c](https://linux-hardware.org/?probe=0b20db823c) | Dec 29, 2021 |
| XFX           | nForce 780i 3-Way SLI 1     | Desktop     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| HP            | 83EE                        | Desktop     | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [68010a3af5](https://linux-hardware.org/?probe=68010a3af5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | Notebook    | [2d4a0a1823](https://linux-hardware.org/?probe=2d4a0a1823) | Dec 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | Notebook    | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| Intel         | NUC7JYB J67967-405          | Mini pc     | [d6850cd8f7](https://linux-hardware.org/?probe=d6850cd8f7) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [526e490544](https://linux-hardware.org/?probe=526e490544) | Dec 17, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [7d976b30fc](https://linux-hardware.org/?probe=7d976b30fc) | Dec 17, 2021 |
| ASRock        | B550 TW                     | Desktop     | [83c53ad524](https://linux-hardware.org/?probe=83c53ad524) | Dec 17, 2021 |
| Dell          | Inspiron 13 5310            | Notebook    | [bdad2f1618](https://linux-hardware.org/?probe=bdad2f1618) | Dec 14, 2021 |
| HP            | 8054                        | Desktop     | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [dac259cc34](https://linux-hardware.org/?probe=dac259cc34) | Dec 13, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [1b14f17a6e](https://linux-hardware.org/?probe=1b14f17a6e) | Dec 11, 2021 |
| NEC Comput... | PC-TW508CAS                 | Tablet      | [06fe78096e](https://linux-hardware.org/?probe=06fe78096e) | Dec 09, 2021 |
| NEC Comput... | PC-TW508CAS                 | Tablet      | [7e305e10d6](https://linux-hardware.org/?probe=7e305e10d6) | Dec 09, 2021 |
| sunxi         | FriendlyARM NanoPi NEO      | Soc         | [031d844c3a](https://linux-hardware.org/?probe=031d844c3a) | Dec 05, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [3e6b2c12f8](https://linux-hardware.org/?probe=3e6b2c12f8) | Dec 05, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [b3c78d548b](https://linux-hardware.org/?probe=b3c78d548b) | Dec 03, 2021 |
| Apple         | MacBookPro13,2              | Notebook    | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [d63f7874c8](https://linux-hardware.org/?probe=d63f7874c8) | Nov 29, 2021 |
| Dell          | G3 3779                     | Notebook    | [cd6dace549](https://linux-hardware.org/?probe=cd6dace549) | Nov 26, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [dca6d021bb](https://linux-hardware.org/?probe=dca6d021bb) | Nov 23, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| ASUSTek       | P8H61-I                     | Desktop     | [bb8c25b299](https://linux-hardware.org/?probe=bb8c25b299) | Nov 20, 2021 |
| MouseCompu... | B75M-D3V-JP                 | Desktop     | [161d355bcc](https://linux-hardware.org/?probe=161d355bcc) | Nov 18, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [268e60a948](https://linux-hardware.org/?probe=268e60a948) | Nov 17, 2021 |
| MouseCompu... | B360M                       | Desktop     | [cab585062a](https://linux-hardware.org/?probe=cab585062a) | Nov 13, 2021 |
| ASUSTek       | H97-PRO                     | Desktop     | [99f09523d8](https://linux-hardware.org/?probe=99f09523d8) | Nov 12, 2021 |
| ASUSTek       | H170-PRO                    | Desktop     | [f3a3f86928](https://linux-hardware.org/?probe=f3a3f86928) | Nov 12, 2021 |
| HP            | 3047h                       | Desktop     | [192742e5a6](https://linux-hardware.org/?probe=192742e5a6) | Nov 12, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | 3047h                       | Desktop     | [935aac64ef](https://linux-hardware.org/?probe=935aac64ef) | Nov 11, 2021 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [982fbc9995](https://linux-hardware.org/?probe=982fbc9995) | Nov 10, 2021 |
| Lenovo        | G580 26897JJ                | Notebook    | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| MouseCompu... | Z490M-S01                   | Desktop     | [bd810f8122](https://linux-hardware.org/?probe=bd810f8122) | Nov 10, 2021 |
| Dell          | Inspiron M5110              | Notebook    | [4a6d42444c](https://linux-hardware.org/?probe=4a6d42444c) | Nov 10, 2021 |
| System76      | Lemur Pro                   | Notebook    | [92a5e9c183](https://linux-hardware.org/?probe=92a5e9c183) | Nov 09, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [34e330ff50](https://linux-hardware.org/?probe=34e330ff50) | Nov 07, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | Notebook    | [0193f0b7a0](https://linux-hardware.org/?probe=0193f0b7a0) | Nov 06, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [80a8e89f7e](https://linux-hardware.org/?probe=80a8e89f7e) | Nov 06, 2021 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [470204d924](https://linux-hardware.org/?probe=470204d924) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [d62808ad60](https://linux-hardware.org/?probe=d62808ad60) | Nov 03, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6321f2a677](https://linux-hardware.org/?probe=6321f2a677) | Nov 03, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [834bf06329](https://linux-hardware.org/?probe=834bf06329) | Nov 03, 2021 |
| Dell          | 0P301D A02                  | Desktop     | [26462404f4](https://linux-hardware.org/?probe=26462404f4) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| HP            | 3047h                       | Desktop     | [afa4f5c1d0](https://linux-hardware.org/?probe=afa4f5c1d0) | Oct 28, 2021 |
| HP            | 3047h                       | Desktop     | [d5e5504f54](https://linux-hardware.org/?probe=d5e5504f54) | Oct 28, 2021 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Dell          | G5 5500                     | Notebook    | [cf10cd5b99](https://linux-hardware.org/?probe=cf10cd5b99) | Oct 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [a0bf764d45](https://linux-hardware.org/?probe=a0bf764d45) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | Desktop     | [1d14b9b944](https://linux-hardware.org/?probe=1d14b9b944) | Oct 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6aa4ae0da5](https://linux-hardware.org/?probe=6aa4ae0da5) | Oct 23, 2021 |
| HP            | ProBook 6550b               | Notebook    | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Dell          | G3 3779                     | Notebook    | [a84248c5d5](https://linux-hardware.org/?probe=a84248c5d5) | Oct 21, 2021 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| EPSON DIRE... | ST170E                      | Desktop     | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Jumper        | Ezbook X3                   | Notebook    | [fe510b821a](https://linux-hardware.org/?probe=fe510b821a) | Oct 17, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | Desktop     | [4efe80812c](https://linux-hardware.org/?probe=4efe80812c) | Oct 16, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [e7ab53c038](https://linux-hardware.org/?probe=e7ab53c038) | Oct 15, 2021 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [42b4e70ef9](https://linux-hardware.org/?probe=42b4e70ef9) | Oct 15, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| NEC Comput... | PC-LL550VG6R                | Notebook    | [5879ce1d61](https://linux-hardware.org/?probe=5879ce1d61) | Oct 13, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [5ed3b7e62d](https://linux-hardware.org/?probe=5ed3b7e62d) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| ASRock        | H67DE                       | Desktop     | [491ac17e42](https://linux-hardware.org/?probe=491ac17e42) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [e1543ea8f8](https://linux-hardware.org/?probe=e1543ea8f8) | Oct 09, 2021 |
| Toshiba       | dynabook R634/K             | Notebook    | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [6918b927d0](https://linux-hardware.org/?probe=6918b927d0) | Oct 07, 2021 |
| ASUSTek       | M51AC                       | Desktop     | [0d9722a373](https://linux-hardware.org/?probe=0d9722a373) | Oct 05, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [0b768f6fac](https://linux-hardware.org/?probe=0b768f6fac) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c920ce007](https://linux-hardware.org/?probe=1c920ce007) | Oct 03, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [0d05812341](https://linux-hardware.org/?probe=0d05812341) | Oct 02, 2021 |
| Fujitsu       | U9311                       | Notebook    | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | Desktop     | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| Panasonic     | CFSV9-2                     | Notebook    | [05b8edc925](https://linux-hardware.org/?probe=05b8edc925) | Sep 29, 2021 |
| ASRock        | H67DE                       | Desktop     | [296abe4896](https://linux-hardware.org/?probe=296abe4896) | Sep 28, 2021 |
| ASRock        | H67DE                       | Desktop     | [e663e151d6](https://linux-hardware.org/?probe=e663e151d6) | Sep 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [8b3dfbb8a4](https://linux-hardware.org/?probe=8b3dfbb8a4) | Sep 25, 2021 |
| NEC Comput... | PC-GN15B79AA                | Notebook    | [a1046b626e](https://linux-hardware.org/?probe=a1046b626e) | Sep 23, 2021 |
| NEC Comput... | PC-GN15B79AA                | Notebook    | [a1b9f1dc30](https://linux-hardware.org/?probe=a1b9f1dc30) | Sep 23, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | Notebook    | [b0289ef67d](https://linux-hardware.org/?probe=b0289ef67d) | Sep 22, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [5164ba24f6](https://linux-hardware.org/?probe=5164ba24f6) | Sep 21, 2021 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [b613f0c8a9](https://linux-hardware.org/?probe=b613f0c8a9) | Sep 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6f52a2ebed](https://linux-hardware.org/?probe=6f52a2ebed) | Sep 18, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [19173612af](https://linux-hardware.org/?probe=19173612af) | Sep 18, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [06d99f6a80](https://linux-hardware.org/?probe=06d99f6a80) | Sep 17, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [34aff1f974](https://linux-hardware.org/?probe=34aff1f974) | Sep 17, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [8c9476bcae](https://linux-hardware.org/?probe=8c9476bcae) | Sep 17, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [0ab25d0365](https://linux-hardware.org/?probe=0ab25d0365) | Sep 14, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3534d3e5f1](https://linux-hardware.org/?probe=3534d3e5f1) | Sep 13, 2021 |
| Panasonic     | CF-S10EYTDR                 | Notebook    | [a90d037dcf](https://linux-hardware.org/?probe=a90d037dcf) | Sep 10, 2021 |
| ASUSTek       | G551JM                      | Notebook    | [9f323164cd](https://linux-hardware.org/?probe=9f323164cd) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| Gigabyte      | B75M-D2P                    | Desktop     | [617e5dd237](https://linux-hardware.org/?probe=617e5dd237) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | Notebook    | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [f5d32061ec](https://linux-hardware.org/?probe=f5d32061ec) | Sep 08, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [2a289951de](https://linux-hardware.org/?probe=2a289951de) | Sep 07, 2021 |
| Toshiba       | dynabook T55/PW             | Notebook    | [1ce1b25ad5](https://linux-hardware.org/?probe=1ce1b25ad5) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 2306A44       | Notebook    | [8f97e284a7](https://linux-hardware.org/?probe=8f97e284a7) | Sep 03, 2021 |
| Toshiba       | dynabook R73/A              | Notebook    | [deb0351e19](https://linux-hardware.org/?probe=deb0351e19) | Sep 03, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [919b7c1304](https://linux-hardware.org/?probe=919b7c1304) | Sep 01, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [469dc0f2ef](https://linux-hardware.org/?probe=469dc0f2ef) | Aug 31, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [47f44e561f](https://linux-hardware.org/?probe=47f44e561f) | Aug 31, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | Desktop     | [22d7fff01c](https://linux-hardware.org/?probe=22d7fff01c) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | Desktop     | [5736465e27](https://linux-hardware.org/?probe=5736465e27) | Aug 27, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| EPSON DIRE... | ST150E                      | Desktop     | [797ec7ec81](https://linux-hardware.org/?probe=797ec7ec81) | Aug 24, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Sony          | VGN-S55B_S                  | Notebook    | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [85b8505955](https://linux-hardware.org/?probe=85b8505955) | Aug 20, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [68496a4cb7](https://linux-hardware.org/?probe=68496a4cb7) | Aug 18, 2021 |
| ASRock        | N3150M                      | Desktop     | [932c7baf1a](https://linux-hardware.org/?probe=932c7baf1a) | Aug 17, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| HP            | ProBook 6470b               | Notebook    | [4d338e7f16](https://linux-hardware.org/?probe=4d338e7f16) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [ab538f5af7](https://linux-hardware.org/?probe=ab538f5af7) | Aug 15, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | Notebook    | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS8E700    | Notebook    | [467f177df6](https://linux-hardware.org/?probe=467f177df6) | Aug 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [5b7a8411f5](https://linux-hardware.org/?probe=5b7a8411f5) | Aug 09, 2021 |
| THD           | RX2                         | Mini pc     | [f7f9324872](https://linux-hardware.org/?probe=f7f9324872) | Aug 09, 2021 |
| NEC Comput... | PC-GN246W3A5                | Notebook    | [dfc05750e3](https://linux-hardware.org/?probe=dfc05750e3) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Teclast       | X6 Pro                      | Tablet      | [ed972212e1](https://linux-hardware.org/?probe=ed972212e1) | Aug 07, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| Panasonic     | CF-S10EYTDR                 | Notebook    | [b965812f09](https://linux-hardware.org/?probe=b965812f09) | Aug 06, 2021 |
| NEC Comput... | MS-7770HH                   | Desktop     | [7ca677a33c](https://linux-hardware.org/?probe=7ca677a33c) | Aug 03, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [ff5bee5ff8](https://linux-hardware.org/?probe=ff5bee5ff8) | Aug 01, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [0401734340](https://linux-hardware.org/?probe=0401734340) | Jul 31, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [1e02007526](https://linux-hardware.org/?probe=1e02007526) | Jul 30, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [161a673775](https://linux-hardware.org/?probe=161a673775) | Jul 28, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [264959862d](https://linux-hardware.org/?probe=264959862d) | Jul 28, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [63b014e84e](https://linux-hardware.org/?probe=63b014e84e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [478d06f2df](https://linux-hardware.org/?probe=478d06f2df) | Jul 26, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [fbf1f240f4](https://linux-hardware.org/?probe=fbf1f240f4) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | Notebook    | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| HP            | 18E7                        | Desktop     | [c0cddf4243](https://linux-hardware.org/?probe=c0cddf4243) | Jul 23, 2021 |
| Unknown       | XH61X000.100                | Desktop     | [6604251e58](https://linux-hardware.org/?probe=6604251e58) | Jul 23, 2021 |
| HP            | 14                          | Notebook    | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [93a813bbba](https://linux-hardware.org/?probe=93a813bbba) | Jul 22, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| HP            | 1906                        | Desktop     | [6cd7c6ec7f](https://linux-hardware.org/?probe=6cd7c6ec7f) | Jul 20, 2021 |
| HP            | 14                          | Notebook    | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| ASRock        | 880GM-LE                    | Desktop     | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Fujitsu       | FMVS54CD1                   | Notebook    | [7e6aa1f514](https://linux-hardware.org/?probe=7e6aa1f514) | Jul 18, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [80b10e8187](https://linux-hardware.org/?probe=80b10e8187) | Jul 18, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| Fujitsu       | FMVS54CD1                   | Notebook    | [ad9e144c6a](https://linux-hardware.org/?probe=ad9e144c6a) | Jul 15, 2021 |
| HP            | 18E7                        | Desktop     | [03d84525e8](https://linux-hardware.org/?probe=03d84525e8) | Jul 13, 2021 |
| Dell          | Latitude E5510              | Notebook    | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| Toshiba       | dynabook T954/89L           | Notebook    | [176e4906db](https://linux-hardware.org/?probe=176e4906db) | Jul 12, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [d6410ac1a0](https://linux-hardware.org/?probe=d6410ac1a0) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | Notebook    | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [3df3921e13](https://linux-hardware.org/?probe=3df3921e13) | Jul 10, 2021 |
| HP            | 872E                        | Mini pc     | [b1de952c4e](https://linux-hardware.org/?probe=b1de952c4e) | Jul 09, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [1b63a19bd1](https://linux-hardware.org/?probe=1b63a19bd1) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [673b1c670f](https://linux-hardware.org/?probe=673b1c670f) | Jul 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [14789c0301](https://linux-hardware.org/?probe=14789c0301) | Jul 07, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| HP            | 872E                        | Mini pc     | [1cacfccdb9](https://linux-hardware.org/?probe=1cacfccdb9) | Jul 03, 2021 |
| Google        | Helios                      | Notebook    | [644f9f9062](https://linux-hardware.org/?probe=644f9f9062) | Jul 02, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | Desktop     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [db7536f5a7](https://linux-hardware.org/?probe=db7536f5a7) | Jun 29, 2021 |
| HP            | 1906                        | Desktop     | [95bfd2283b](https://linux-hardware.org/?probe=95bfd2283b) | Jun 29, 2021 |
| Dell          | Inspiron 5583               | Notebook    | [a1f0396c8e](https://linux-hardware.org/?probe=a1f0396c8e) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | Desktop     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [be23e213b9](https://linux-hardware.org/?probe=be23e213b9) | Jun 26, 2021 |
| ASRock        | Z390 Pro4                   | Desktop     | [6c86be2586](https://linux-hardware.org/?probe=6c86be2586) | Jun 24, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c2285d9014](https://linux-hardware.org/?probe=c2285d9014) | Jun 22, 2021 |
| Toshiba       | dynabook T954/89L           | Notebook    | [c4b1b8aabb](https://linux-hardware.org/?probe=c4b1b8aabb) | Jun 21, 2021 |
| Toshiba       | dynabook T954/89L           | Notebook    | [b6a5d80f8a](https://linux-hardware.org/?probe=b6a5d80f8a) | Jun 21, 2021 |
| Lenovo        | S10-3                       | Notebook    | [eb48df4717](https://linux-hardware.org/?probe=eb48df4717) | Jun 20, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [76096c0075](https://linux-hardware.org/?probe=76096c0075) | Jun 19, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [03b329894a](https://linux-hardware.org/?probe=03b329894a) | Jun 18, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [4c0e4ebaa4](https://linux-hardware.org/?probe=4c0e4ebaa4) | Jun 16, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [0b50c157fe](https://linux-hardware.org/?probe=0b50c157fe) | Jun 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [2da9390d91](https://linux-hardware.org/?probe=2da9390d91) | Jun 11, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [c33921449f](https://linux-hardware.org/?probe=c33921449f) | Jun 10, 2021 |
| Toshiba       | dynabook R73/BN             | Notebook    | [c9cdf2bc57](https://linux-hardware.org/?probe=c9cdf2bc57) | Jun 06, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| ECS           | G41T-M2                     | Desktop     | [3005be6650](https://linux-hardware.org/?probe=3005be6650) | Jun 04, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [0860242147](https://linux-hardware.org/?probe=0860242147) | Jun 04, 2021 |
| Sony          | VAIO                        | All in one  | [afa509714d](https://linux-hardware.org/?probe=afa509714d) | Jun 03, 2021 |
| Biostar       | B350GTN                     | Notebook    | [6ba7f458da](https://linux-hardware.org/?probe=6ba7f458da) | Jun 01, 2021 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [74057c8385](https://linux-hardware.org/?probe=74057c8385) | May 30, 2021 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [36fb4e2aba](https://linux-hardware.org/?probe=36fb4e2aba) | May 29, 2021 |
| Lenovo        | S10-3                       | Notebook    | [8dfadf5edb](https://linux-hardware.org/?probe=8dfadf5edb) | May 27, 2021 |
| NEC Comput... | PC-LL730TG                  | Notebook    | [e4172892e9](https://linux-hardware.org/?probe=e4172892e9) | May 26, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [4d1d4e61c3](https://linux-hardware.org/?probe=4d1d4e61c3) | May 25, 2021 |
| NEC Comput... | PC-VK22TGGCN                | Notebook    | [b6a2893c7e](https://linux-hardware.org/?probe=b6a2893c7e) | May 25, 2021 |
| Dell          | Latitude E6420              | Notebook    | [4ef6253092](https://linux-hardware.org/?probe=4ef6253092) | May 22, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [4ea4747cbf](https://linux-hardware.org/?probe=4ea4747cbf) | May 18, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [5d215fafdd](https://linux-hardware.org/?probe=5d215fafdd) | May 15, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [fdc8841fca](https://linux-hardware.org/?probe=fdc8841fca) | May 14, 2021 |
| ASUSTek       | PRIME X299-A                | Desktop     | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [6c767dc0df](https://linux-hardware.org/?probe=6c767dc0df) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [5ed8fb5a9f](https://linux-hardware.org/?probe=5ed8fb5a9f) | May 13, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [0e4daa1de2](https://linux-hardware.org/?probe=0e4daa1de2) | May 11, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [232c90ce25](https://linux-hardware.org/?probe=232c90ce25) | May 10, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [c796c57372](https://linux-hardware.org/?probe=c796c57372) | May 10, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [e7238c107c](https://linux-hardware.org/?probe=e7238c107c) | May 09, 2021 |
| Fujitsu       | FMVNF40UK                   | Notebook    | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [f416a7a6b3](https://linux-hardware.org/?probe=f416a7a6b3) | May 09, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aa1f42a8a9](https://linux-hardware.org/?probe=aa1f42a8a9) | May 08, 2021 |
| MouseCompu... | W150ERQ                     | Notebook    | [1ccfec5c8f](https://linux-hardware.org/?probe=1ccfec5c8f) | May 07, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [f001bddea6](https://linux-hardware.org/?probe=f001bddea6) | May 04, 2021 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| Fujitsu       | FMVWE3AB11                  | Notebook    | [65dce9cf99](https://linux-hardware.org/?probe=65dce9cf99) | May 03, 2021 |
| Dynabook      | P1-T6NP-EG                  | Notebook    | [887c9157d0](https://linux-hardware.org/?probe=887c9157d0) | May 03, 2021 |
| HP            | 3047h                       | Desktop     | [3de6f89fae](https://linux-hardware.org/?probe=3de6f89fae) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| Toshiba       | dynabook Satellite J61 1... | Notebook    | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Maibenben     | S431                        | Notebook    | [a4db49a83f](https://linux-hardware.org/?probe=a4db49a83f) | Apr 29, 2021 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [0f15e44442](https://linux-hardware.org/?probe=0f15e44442) | Apr 26, 2021 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [c64bf46d8b](https://linux-hardware.org/?probe=c64bf46d8b) | Apr 24, 2021 |
| ASRock        | P5B-DE                      | Desktop     | [04084bd0ef](https://linux-hardware.org/?probe=04084bd0ef) | Apr 24, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [7a4d236e06](https://linux-hardware.org/?probe=7a4d236e06) | Apr 24, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [dae1fdda5f](https://linux-hardware.org/?probe=dae1fdda5f) | Apr 23, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [fff82cb538](https://linux-hardware.org/?probe=fff82cb538) | Apr 22, 2021 |
| ASUSTek       | N3150I-C                    | Desktop     | [4cfbe212a4](https://linux-hardware.org/?probe=4cfbe212a4) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [af34567550](https://linux-hardware.org/?probe=af34567550) | Apr 17, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [4afc76cdbe](https://linux-hardware.org/?probe=4afc76cdbe) | Apr 17, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b7991a35ba](https://linux-hardware.org/?probe=b7991a35ba) | Apr 16, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [a7ed7cc477](https://linux-hardware.org/?probe=a7ed7cc477) | Apr 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Dell          | Precision M4800             | Notebook    | [7a2924ab2a](https://linux-hardware.org/?probe=7a2924ab2a) | Apr 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [c5ed691eb7](https://linux-hardware.org/?probe=c5ed691eb7) | Apr 13, 2021 |
| KOUZIRO       | KOUZIRONB                   | Notebook    | [18adf344fe](https://linux-hardware.org/?probe=18adf344fe) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| ASUSTek       | P4V800D-X                   | Desktop     | [c469d16946](https://linux-hardware.org/?probe=c469d16946) | Apr 09, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [122641cd7e](https://linux-hardware.org/?probe=122641cd7e) | Apr 08, 2021 |
| NEC Comput... | PC-VK25TXZCE                | Notebook    | [e6acc84298](https://linux-hardware.org/?probe=e6acc84298) | Apr 07, 2021 |
| Toshiba       | dynabook BX/33M             | Notebook    | [06580ff422](https://linux-hardware.org/?probe=06580ff422) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 23245Y1       | Notebook    | [83430b3adf](https://linux-hardware.org/?probe=83430b3adf) | Apr 06, 2021 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [a5b2555cc2](https://linux-hardware.org/?probe=a5b2555cc2) | Apr 06, 2021 |
| Dynabook      | P1-T6NP-EG                  | Notebook    | [3f0b2d7c1d](https://linux-hardware.org/?probe=3f0b2d7c1d) | Apr 05, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ba17a463a7](https://linux-hardware.org/?probe=ba17a463a7) | Apr 03, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [a579757204](https://linux-hardware.org/?probe=a579757204) | Apr 03, 2021 |
| Toshiba       | dynabook CX/48F             | Notebook    | [d32bf9dced](https://linux-hardware.org/?probe=d32bf9dced) | Apr 02, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [a82050e3ae](https://linux-hardware.org/?probe=a82050e3ae) | Apr 01, 2021 |
| NEC Comput... | MILO2-H 3A3B                | All in one  | [1494683bb9](https://linux-hardware.org/?probe=1494683bb9) | Apr 01, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [0a547ba59a](https://linux-hardware.org/?probe=0a547ba59a) | Mar 31, 2021 |
| Dell          | Latitude E6320              | Notebook    | [2c01829c5b](https://linux-hardware.org/?probe=2c01829c5b) | Mar 28, 2021 |
| Dell          | G3 3500                     | Notebook    | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [22b865b40a](https://linux-hardware.org/?probe=22b865b40a) | Mar 26, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [43c49d259d](https://linux-hardware.org/?probe=43c49d259d) | Mar 26, 2021 |
| HP            | G60                         | Notebook    | [a97ca105eb](https://linux-hardware.org/?probe=a97ca105eb) | Mar 25, 2021 |
| HP            | G60                         | Notebook    | [e8cc7247c7](https://linux-hardware.org/?probe=e8cc7247c7) | Mar 23, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [22b092fe80](https://linux-hardware.org/?probe=22b092fe80) | Mar 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [a4b57558c3](https://linux-hardware.org/?probe=a4b57558c3) | Mar 22, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [52b2fb4ebb](https://linux-hardware.org/?probe=52b2fb4ebb) | Mar 22, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [d5722fd82b](https://linux-hardware.org/?probe=d5722fd82b) | Mar 22, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [e5ce81269b](https://linux-hardware.org/?probe=e5ce81269b) | Mar 22, 2021 |
| HP            | ProBook 430 G7              | Notebook    | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| ASRock        | X370 Pro4                   | Desktop     | [6c6d145ad3](https://linux-hardware.org/?probe=6c6d145ad3) | Mar 20, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [56a39af725](https://linux-hardware.org/?probe=56a39af725) | Mar 20, 2021 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [64164ccce2](https://linux-hardware.org/?probe=64164ccce2) | Mar 19, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [2d9b9381bd](https://linux-hardware.org/?probe=2d9b9381bd) | Mar 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | Notebook    | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [b36b41329b](https://linux-hardware.org/?probe=b36b41329b) | Mar 14, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [cff1baf251](https://linux-hardware.org/?probe=cff1baf251) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| Lenovo        | ThinkPad X12 Detachable ... | Tablet      | [aac22af3a1](https://linux-hardware.org/?probe=aac22af3a1) | Mar 13, 2021 |
| HP            | 212B                        | Desktop     | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T3C... | Notebook    | [7cda624782](https://linux-hardware.org/?probe=7cda624782) | Mar 12, 2021 |
| Biostar       | Hi-Fi A88ZN                 | Desktop     | [72cff94e15](https://linux-hardware.org/?probe=72cff94e15) | Mar 12, 2021 |
| Dynabook      | GCX83/PLE                   | Notebook    | [2ef2ac3448](https://linux-hardware.org/?probe=2ef2ac3448) | Mar 12, 2021 |
| Fujitsu       | FMVS54EB                    | Notebook    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| HP            | 8446                        | All in one  | [2cdf1fd3be](https://linux-hardware.org/?probe=2cdf1fd3be) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bca1731a58](https://linux-hardware.org/?probe=bca1731a58) | Mar 08, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [3feff6616d](https://linux-hardware.org/?probe=3feff6616d) | Mar 07, 2021 |
| Dell          | Latitude 7280               | Notebook    | [64e390d0d6](https://linux-hardware.org/?probe=64e390d0d6) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [24088afc25](https://linux-hardware.org/?probe=24088afc25) | Mar 06, 2021 |
| HP            | 212B                        | Desktop     | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| Timi          | RedmiBook 16                | Notebook    | [7139d19a98](https://linux-hardware.org/?probe=7139d19a98) | Mar 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e840817785](https://linux-hardware.org/?probe=e840817785) | Mar 03, 2021 |
| MSI           | C236A WORKSTATION           | Desktop     | [dc9e6c2670](https://linux-hardware.org/?probe=dc9e6c2670) | Mar 03, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [3d2e576c95](https://linux-hardware.org/?probe=3d2e576c95) | Mar 03, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [aa41662477](https://linux-hardware.org/?probe=aa41662477) | Mar 02, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [c08f9a30dc](https://linux-hardware.org/?probe=c08f9a30dc) | Feb 28, 2021 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [16cf45ce16](https://linux-hardware.org/?probe=16cf45ce16) | Feb 28, 2021 |
| Dell          | 0T1D10 A01                  | Desktop     | [3577c78a56](https://linux-hardware.org/?probe=3577c78a56) | Feb 27, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [65a5a31ae8](https://linux-hardware.org/?probe=65a5a31ae8) | Feb 26, 2021 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [501d2317f9](https://linux-hardware.org/?probe=501d2317f9) | Feb 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5f5d47e737](https://linux-hardware.org/?probe=5f5d47e737) | Feb 26, 2021 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [b1a878b7d0](https://linux-hardware.org/?probe=b1a878b7d0) | Feb 26, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f4ea5b4b7e](https://linux-hardware.org/?probe=f4ea5b4b7e) | Feb 25, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [3e009dec2f](https://linux-hardware.org/?probe=3e009dec2f) | Feb 23, 2021 |
| NEC Comput... | PC-LL750FS6R                | Notebook    | [2708ba9972](https://linux-hardware.org/?probe=2708ba9972) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | Notebook    | [fa1eb2a97a](https://linux-hardware.org/?probe=fa1eb2a97a) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | Notebook    | [cf754cecc4](https://linux-hardware.org/?probe=cf754cecc4) | Feb 23, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7e4e426453](https://linux-hardware.org/?probe=7e4e426453) | Feb 22, 2021 |
| Biostar       | B450GT3                     | Desktop     | [18e0346ed0](https://linux-hardware.org/?probe=18e0346ed0) | Feb 22, 2021 |
| MSI           | C236A WORKSTATION           | Desktop     | [9e2effbe63](https://linux-hardware.org/?probe=9e2effbe63) | Feb 22, 2021 |
| Toshiba       | dynabook Satellite TXW/6... | Notebook    | [51128d9716](https://linux-hardware.org/?probe=51128d9716) | Feb 19, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [5c5b3ce155](https://linux-hardware.org/?probe=5c5b3ce155) | Feb 19, 2021 |
| Toshiba       | dynabook EX/35KWH           | Notebook    | [c52a95f06c](https://linux-hardware.org/?probe=c52a95f06c) | Feb 18, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [e8e114704d](https://linux-hardware.org/?probe=e8e114704d) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [977e293baa](https://linux-hardware.org/?probe=977e293baa) | Feb 16, 2021 |
| MSI           | A78M-E35 V2                 | Desktop     | [173e28a6b2](https://linux-hardware.org/?probe=173e28a6b2) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a2e399875d](https://linux-hardware.org/?probe=a2e399875d) | Feb 15, 2021 |
| Fujitsu       | FMVNFB40J                   | Notebook    | [8a3d6bcc89](https://linux-hardware.org/?probe=8a3d6bcc89) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [c364bd22bf](https://linux-hardware.org/?probe=c364bd22bf) | Feb 14, 2021 |
| Fujitsu       | FMVA05002                   | Notebook    | [a758e3201d](https://linux-hardware.org/?probe=a758e3201d) | Feb 14, 2021 |
| Biostar       | X470NH                      | Desktop     | [b4ae665275](https://linux-hardware.org/?probe=b4ae665275) | Feb 13, 2021 |
| ASRock        | B75M R2.0                   | Desktop     | [6b1142fdaa](https://linux-hardware.org/?probe=6b1142fdaa) | Feb 13, 2021 |
| Lenovo        | ThinkPad T61 7659D92        | Notebook    | [8d9f56460d](https://linux-hardware.org/?probe=8d9f56460d) | Feb 13, 2021 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [b384cb32dc](https://linux-hardware.org/?probe=b384cb32dc) | Feb 13, 2021 |
| MSI           | H270I GAMING PRO AC         | Desktop     | [dcae892f29](https://linux-hardware.org/?probe=dcae892f29) | Feb 13, 2021 |
| Fujitsu       | FMVA56GBX                   | Notebook    | [bdc337bd04](https://linux-hardware.org/?probe=bdc337bd04) | Feb 13, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a45a89930f](https://linux-hardware.org/?probe=a45a89930f) | Feb 13, 2021 |
| Fujitsu       | FMVA05002                   | Notebook    | [db95456803](https://linux-hardware.org/?probe=db95456803) | Feb 12, 2021 |
| Panasonic     | CF-SX3EDHCS                 | Notebook    | [3f7a156241](https://linux-hardware.org/?probe=3f7a156241) | Feb 11, 2021 |
| NEC Comput... | PC-VK19SGZDF                | Notebook    | [624a2eee47](https://linux-hardware.org/?probe=624a2eee47) | Feb 10, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [168dfeabe8](https://linux-hardware.org/?probe=168dfeabe8) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | Notebook    | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | Notebook    | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [256969ebac](https://linux-hardware.org/?probe=256969ebac) | Feb 07, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [72061bcca7](https://linux-hardware.org/?probe=72061bcca7) | Feb 06, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [1b421bc93c](https://linux-hardware.org/?probe=1b421bc93c) | Feb 05, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Biostar       | B450GT                      | Desktop     | [2cb5b97972](https://linux-hardware.org/?probe=2cb5b97972) | Feb 02, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [ebe6b1d494](https://linux-hardware.org/?probe=ebe6b1d494) | Feb 02, 2021 |
| Wistron       | J361Y                       | Desktop     | [347eb6b747](https://linux-hardware.org/?probe=347eb6b747) | Jan 31, 2021 |
| Dell          | 02P9X9 A05                  | Server      | [1205deb78e](https://linux-hardware.org/?probe=1205deb78e) | Jan 27, 2021 |
| NEC Comput... | IS8XM                       | Desktop     | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| HP            | 0A54h                       | Desktop     | [9f8677d69a](https://linux-hardware.org/?probe=9f8677d69a) | Jan 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| HP            | 0A54h                       | Desktop     | [6b91501381](https://linux-hardware.org/?probe=6b91501381) | Jan 21, 2021 |
| Microsoft     | Surface 3                   | Tablet      | [66a11d584d](https://linux-hardware.org/?probe=66a11d584d) | Jan 20, 2021 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a161a19f04](https://linux-hardware.org/?probe=a161a19f04) | Jan 20, 2021 |
| NEC Comput... | MILO2-H 3A3B                | All in one  | [198709ea08](https://linux-hardware.org/?probe=198709ea08) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| NEC Comput... | PC-LL750SG6R                | Notebook    | [7c9081a73a](https://linux-hardware.org/?probe=7c9081a73a) | Jan 16, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [e5c02d2922](https://linux-hardware.org/?probe=e5c02d2922) | Jan 15, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [8b4d24c14c](https://linux-hardware.org/?probe=8b4d24c14c) | Jan 14, 2021 |
| Gigabyte      | G33-DS3R                    | Desktop     | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | Notebook    | [735d00e026](https://linux-hardware.org/?probe=735d00e026) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | Notebook    | [5df5433a1c](https://linux-hardware.org/?probe=5df5433a1c) | Jan 13, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [1d6691dffe](https://linux-hardware.org/?probe=1d6691dffe) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c77878fdf4](https://linux-hardware.org/?probe=c77878fdf4) | Jan 12, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [5cea01c3c1](https://linux-hardware.org/?probe=5cea01c3c1) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3b66143d43](https://linux-hardware.org/?probe=3b66143d43) | Jan 11, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [293bb6fc26](https://linux-hardware.org/?probe=293bb6fc26) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [8c2793a502](https://linux-hardware.org/?probe=8c2793a502) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [44b1f16e92](https://linux-hardware.org/?probe=44b1f16e92) | Jan 10, 2021 |
| Dell          | 0R7935 A03                  | Desktop     | [1d936da792](https://linux-hardware.org/?probe=1d936da792) | Jan 09, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| HP            | 158A                        | Desktop     | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| MSI           | Creator X299                | Desktop     | [b66f2c1d16](https://linux-hardware.org/?probe=b66f2c1d16) | Jan 06, 2021 |
| ASRock        | J5005-ITX                   | Desktop     | [81bba5a535](https://linux-hardware.org/?probe=81bba5a535) | Jan 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [34d77cfa6e](https://linux-hardware.org/?probe=34d77cfa6e) | Jan 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [07fb95c682](https://linux-hardware.org/?probe=07fb95c682) | Jan 03, 2021 |
| Acer          | Aspire XC-602 V1.0          | Desktop     | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| HUAWEI        | MRC-WX0                     | Notebook    | [f650998a3d](https://linux-hardware.org/?probe=f650998a3d) | Jan 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [f56caad73c](https://linux-hardware.org/?probe=f56caad73c) | Jan 02, 2021 |
| NEC Comput... | MILO2-H 3A3B                | All in one  | [db058b1012](https://linux-hardware.org/?probe=db058b1012) | Jan 01, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [c6ea824e48](https://linux-hardware.org/?probe=c6ea824e48) | Dec 31, 2020 |
| Fujitsu       | FMVLCE50B                   | Notebook    | [03569af3cb](https://linux-hardware.org/?probe=03569af3cb) | Dec 31, 2020 |
| ASRock        | B360M-ITX/ac                | Desktop     | [8e0bce5edb](https://linux-hardware.org/?probe=8e0bce5edb) | Dec 30, 2020 |
| Gateway       | G33M05G1 MP                 | Desktop     | [460acf5c52](https://linux-hardware.org/?probe=460acf5c52) | Dec 30, 2020 |
| MSI           | Modern 14 B4MW              | Notebook    | [ec110ae347](https://linux-hardware.org/?probe=ec110ae347) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | Notebook    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2c76a9b0e9](https://linux-hardware.org/?probe=2c76a9b0e9) | Dec 28, 2020 |
| MSI           | FM2-A75IA-E53               | Desktop     | [ec03bb47a4](https://linux-hardware.org/?probe=ec03bb47a4) | Dec 28, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | Notebook    | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | Notebook    | [84b2b1cba7](https://linux-hardware.org/?probe=84b2b1cba7) | Dec 26, 2020 |
| Thirdwave     | Diginnos PC                 | Notebook    | [4573bf9eeb](https://linux-hardware.org/?probe=4573bf9eeb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | Notebook    | [f4fe782260](https://linux-hardware.org/?probe=f4fe782260) | Dec 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [fcc97d1fdb](https://linux-hardware.org/?probe=fcc97d1fdb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | Notebook    | [21e571b40f](https://linux-hardware.org/?probe=21e571b40f) | Dec 25, 2020 |
| Dynabook      | P1-T6NP-EG                  | Notebook    | [9f6b496aaf](https://linux-hardware.org/?probe=9f6b496aaf) | Dec 25, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [3ea410030c](https://linux-hardware.org/?probe=3ea410030c) | Dec 24, 2020 |
| ASRock        | FM2A85X-ITX                 | Desktop     | [5401d7dd29](https://linux-hardware.org/?probe=5401d7dd29) | Dec 23, 2020 |
| ASRock        | B360M-ITX/ac                | Desktop     | [39d7373b8e](https://linux-hardware.org/?probe=39d7373b8e) | Dec 23, 2020 |
| Fujitsu       | FMVNFA50                    | Notebook    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [d236c778e1](https://linux-hardware.org/?probe=d236c778e1) | Dec 21, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | Notebook    | [6a74695399](https://linux-hardware.org/?probe=6a74695399) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [ca0c3d2795](https://linux-hardware.org/?probe=ca0c3d2795) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [97e9570360](https://linux-hardware.org/?probe=97e9570360) | Dec 21, 2020 |
| HP            | 158A                        | Desktop     | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Dell          | Latitude E6230              | Notebook    | [c0f67befa0](https://linux-hardware.org/?probe=c0f67befa0) | Dec 18, 2020 |
| Dell          | Latitude E6230              | Notebook    | [9dd587de7a](https://linux-hardware.org/?probe=9dd587de7a) | Dec 18, 2020 |
| FIC           | PTM33 PCB                   | Desktop     | [0e1437dede](https://linux-hardware.org/?probe=0e1437dede) | Dec 18, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [52b0b77ef7](https://linux-hardware.org/?probe=52b0b77ef7) | Dec 17, 2020 |
| Supermicro    | X9DA7/E                     | Desktop     | [7d84e25468](https://linux-hardware.org/?probe=7d84e25468) | Dec 14, 2020 |
| NEC Comput... | PC-LL750SG6R                | Notebook    | [867c1b37b1](https://linux-hardware.org/?probe=867c1b37b1) | Dec 14, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [d988af7e73](https://linux-hardware.org/?probe=d988af7e73) | Dec 13, 2020 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [bf27b4bfee](https://linux-hardware.org/?probe=bf27b4bfee) | Dec 12, 2020 |
| NEC Comput... | MS9666 012                  | Desktop     | [9cc98a743f](https://linux-hardware.org/?probe=9cc98a743f) | Dec 11, 2020 |
| Dell          | Inspiron 5370               | Notebook    | [9cf5fbfe60](https://linux-hardware.org/?probe=9cf5fbfe60) | Dec 09, 2020 |
| Sony          | VAIO                        | All in one  | [68937cf6bb](https://linux-hardware.org/?probe=68937cf6bb) | Dec 08, 2020 |
| Dell          | 002KVM A01                  | Desktop     | [bee5c78b3b](https://linux-hardware.org/?probe=bee5c78b3b) | Dec 08, 2020 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [575c848b52](https://linux-hardware.org/?probe=575c848b52) | Dec 07, 2020 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [58cf889053](https://linux-hardware.org/?probe=58cf889053) | Dec 07, 2020 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [772f864f4e](https://linux-hardware.org/?probe=772f864f4e) | Dec 05, 2020 |
| MSI           | H270 PC MATE                | Desktop     | [35866ce8fb](https://linux-hardware.org/?probe=35866ce8fb) | Dec 02, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [1190e2392c](https://linux-hardware.org/?probe=1190e2392c) | Dec 02, 2020 |
| ASRock        | B550 Taichi                 | Desktop     | [dd9ebdf6b5](https://linux-hardware.org/?probe=dd9ebdf6b5) | Dec 02, 2020 |
| MSI           | H270 PC MATE                | Desktop     | [3151fefb19](https://linux-hardware.org/?probe=3151fefb19) | Dec 02, 2020 |
| Gateway       | G33M05G1 MP                 | Desktop     | [8ec0050494](https://linux-hardware.org/?probe=8ec0050494) | Dec 01, 2020 |
| HP            | G7000                       | Notebook    | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | Notebook    | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | Notebook    | [e8e9e6770b](https://linux-hardware.org/?probe=e8e9e6770b) | Nov 29, 2020 |
| Dell          | 0NW73C A01                  | Desktop     | [1ddf8958ef](https://linux-hardware.org/?probe=1ddf8958ef) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ca9077ede2](https://linux-hardware.org/?probe=ca9077ede2) | Nov 27, 2020 |
| ASRock        | B550 Taichi                 | Desktop     | [047af22dea](https://linux-hardware.org/?probe=047af22dea) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [9148a1a402](https://linux-hardware.org/?probe=9148a1a402) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [054642cdd4](https://linux-hardware.org/?probe=054642cdd4) | Nov 25, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [bf758d0821](https://linux-hardware.org/?probe=bf758d0821) | Nov 23, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [22ef67e9e2](https://linux-hardware.org/?probe=22ef67e9e2) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | Desktop     | [92a6a98f06](https://linux-hardware.org/?probe=92a6a98f06) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | Desktop     | [a826e1045e](https://linux-hardware.org/?probe=a826e1045e) | Nov 22, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [3a74151cb6](https://linux-hardware.org/?probe=3a74151cb6) | Nov 22, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [5fd1f62125](https://linux-hardware.org/?probe=5fd1f62125) | Nov 21, 2020 |
| Gateway       | IPISB-VR                    | Desktop     | [9a9f3b244c](https://linux-hardware.org/?probe=9a9f3b244c) | Nov 21, 2020 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [8d591fed02](https://linux-hardware.org/?probe=8d591fed02) | Nov 21, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [593013a504](https://linux-hardware.org/?probe=593013a504) | Nov 20, 2020 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [da70709a86](https://linux-hardware.org/?probe=da70709a86) | Nov 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | Notebook    | [f34c508c5a](https://linux-hardware.org/?probe=f34c508c5a) | Nov 19, 2020 |
| Gateway       | SX2370                      | Desktop     | [69a18194ba](https://linux-hardware.org/?probe=69a18194ba) | Nov 19, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [8d4468ec71](https://linux-hardware.org/?probe=8d4468ec71) | Nov 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | Notebook    | [f827ecc142](https://linux-hardware.org/?probe=f827ecc142) | Nov 16, 2020 |
| ASRock        | B460M Pro4                  | Desktop     | [ac90684a5f](https://linux-hardware.org/?probe=ac90684a5f) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | Desktop     | [300e280e8c](https://linux-hardware.org/?probe=300e280e8c) | Nov 15, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [adbf017e43](https://linux-hardware.org/?probe=adbf017e43) | Nov 13, 2020 |
| NEC Comput... | G1BJN A                     | Desktop     | [7344b2e1a1](https://linux-hardware.org/?probe=7344b2e1a1) | Nov 12, 2020 |
| Intel         | NUC10i5FNB K61361-304       | Mini pc     | [7518979765](https://linux-hardware.org/?probe=7518979765) | Nov 11, 2020 |
| Intel         | NUC10i5FNB K61361-304       | Mini pc     | [3d188297e0](https://linux-hardware.org/?probe=3d188297e0) | Nov 11, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [3d8a88a6dd](https://linux-hardware.org/?probe=3d8a88a6dd) | Nov 08, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [64fbbc3a2c](https://linux-hardware.org/?probe=64fbbc3a2c) | Nov 08, 2020 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [d746af6cfd](https://linux-hardware.org/?probe=d746af6cfd) | Nov 07, 2020 |
| ASRock        | H110 Pro BTC+               | Desktop     | [fa4cc0d2b6](https://linux-hardware.org/?probe=fa4cc0d2b6) | Nov 07, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [595b65bc4b](https://linux-hardware.org/?probe=595b65bc4b) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | Notebook    | [32a742ccd5](https://linux-hardware.org/?probe=32a742ccd5) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | Notebook    | [497c61e3d1](https://linux-hardware.org/?probe=497c61e3d1) | Nov 07, 2020 |
| Panasonic     | CF-SX1GDHYS                 | Notebook    | [e8f3a6867e](https://linux-hardware.org/?probe=e8f3a6867e) | Nov 06, 2020 |
| ECS           | H77H2-M4                    | Desktop     | [e2dc1539b4](https://linux-hardware.org/?probe=e2dc1539b4) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e14517c94a](https://linux-hardware.org/?probe=e14517c94a) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi                | Soc         | [4fa2fb6c5b](https://linux-hardware.org/?probe=4fa2fb6c5b) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [aedfc24e7e](https://linux-hardware.org/?probe=aedfc24e7e) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [6039056d5c](https://linux-hardware.org/?probe=6039056d5c) | Nov 05, 2020 |
| ASRock        | H110 Pro BTC+               | Desktop     | [38482fe4b4](https://linux-hardware.org/?probe=38482fe4b4) | Nov 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a2303d47d0](https://linux-hardware.org/?probe=a2303d47d0) | Nov 04, 2020 |
| NEC Comput... | IS8XM                       | Desktop     | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| HP            | 0AECh D                     | Desktop     | [84f95d0a66](https://linux-hardware.org/?probe=84f95d0a66) | Nov 04, 2020 |
| Apple         | MacBookAir6,1               | Notebook    | [102aa409db](https://linux-hardware.org/?probe=102aa409db) | Nov 03, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | Desktop     | [7b86aebf60](https://linux-hardware.org/?probe=7b86aebf60) | Nov 03, 2020 |
| MSI           | GS66 Stealth 10SF           | Notebook    | [c885924d12](https://linux-hardware.org/?probe=c885924d12) | Nov 02, 2020 |
| Dell          | 0F428D A00                  | Desktop     | [e70707332f](https://linux-hardware.org/?probe=e70707332f) | Nov 01, 2020 |
| Dell          | 0F428D A00                  | Desktop     | [86139a47f6](https://linux-hardware.org/?probe=86139a47f6) | Nov 01, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | Notebook    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [5621053db7](https://linux-hardware.org/?probe=5621053db7) | Nov 01, 2020 |
| HUAWEI        | MRC-WX0                     | Notebook    | [57608acdc4](https://linux-hardware.org/?probe=57608acdc4) | Oct 31, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [207aee1b3f](https://linux-hardware.org/?probe=207aee1b3f) | Oct 31, 2020 |
| Intel         | S1200BTL E98681-352         | Server      | [57162ca72c](https://linux-hardware.org/?probe=57162ca72c) | Oct 30, 2020 |
| ASRock        | 939A785GMH/128M             | Desktop     | [e5b7c1b0d3](https://linux-hardware.org/?probe=e5b7c1b0d3) | Oct 30, 2020 |
| Dell          | Vostro 2520                 | Notebook    | [196d3c6a8d](https://linux-hardware.org/?probe=196d3c6a8d) | Oct 30, 2020 |
| HP            | ENVY 15                     | Notebook    | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | Notebook    | [d4b681e245](https://linux-hardware.org/?probe=d4b681e245) | Oct 28, 2020 |
| Shuttle       | FS61                        | Desktop     | [c8b13a3e56](https://linux-hardware.org/?probe=c8b13a3e56) | Oct 25, 2020 |
| Shuttle       | FS61                        | Desktop     | [0e89874393](https://linux-hardware.org/?probe=0e89874393) | Oct 25, 2020 |
| Dell          | Vostro 2520                 | Notebook    | [b660b39908](https://linux-hardware.org/?probe=b660b39908) | Oct 25, 2020 |
| ASUSTek       | P5Q-EM                      | Desktop     | [2b7dc5564c](https://linux-hardware.org/?probe=2b7dc5564c) | Oct 24, 2020 |
| HP            | ProBook 4525s               | Notebook    | [157a86205d](https://linux-hardware.org/?probe=157a86205d) | Oct 24, 2020 |
| ASRock        | H110M-ITX                   | Desktop     | [c6e251789a](https://linux-hardware.org/?probe=c6e251789a) | Oct 24, 2020 |
| Unknown       | Unknown                     | Notebook    | [046bfed81f](https://linux-hardware.org/?probe=046bfed81f) | Oct 23, 2020 |
| Sony          | VPCEB49FJ                   | Notebook    | [a7b30aea08](https://linux-hardware.org/?probe=a7b30aea08) | Oct 21, 2020 |
| EPSON DIRE... | Endeavor NJ7000E            | Notebook    | [fd0992fec0](https://linux-hardware.org/?probe=fd0992fec0) | Oct 21, 2020 |
| ASUSTek       | PN50                        | Mini pc     | [004e2befa6](https://linux-hardware.org/?probe=004e2befa6) | Oct 20, 2020 |
| MouseCompu... | NG-N-i5730                  | Notebook    | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| ASUSTek       | E200HA                      | Notebook    | [01f02e3868](https://linux-hardware.org/?probe=01f02e3868) | Oct 19, 2020 |
| ASRock        | B460M Pro4                  | Desktop     | [40a43c769a](https://linux-hardware.org/?probe=40a43c769a) | Oct 18, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [af9ba22806](https://linux-hardware.org/?probe=af9ba22806) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [70b6395f2f](https://linux-hardware.org/?probe=70b6395f2f) | Oct 17, 2020 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [d7c4496b69](https://linux-hardware.org/?probe=d7c4496b69) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ba5634435e](https://linux-hardware.org/?probe=ba5634435e) | Oct 17, 2020 |
| HP            | ProBook 4525s               | Notebook    | [67efc6e80a](https://linux-hardware.org/?probe=67efc6e80a) | Oct 16, 2020 |
| UNITCOM       | W35_37ET                    | Notebook    | [13ddafa560](https://linux-hardware.org/?probe=13ddafa560) | Oct 16, 2020 |
| Supermicro    | C7B75                       | Desktop     | [34cb26f10c](https://linux-hardware.org/?probe=34cb26f10c) | Oct 14, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7925c419a6](https://linux-hardware.org/?probe=7925c419a6) | Oct 13, 2020 |
| Pegatron      | IPM41G                      | Desktop     | [fa3b72447f](https://linux-hardware.org/?probe=fa3b72447f) | Oct 12, 2020 |
| Pegatron      | IPM41G                      | Desktop     | [4d26fb41ea](https://linux-hardware.org/?probe=4d26fb41ea) | Oct 12, 2020 |
| NEC Comput... | PC-LL750F26C                | Notebook    | [7b9dc13b94](https://linux-hardware.org/?probe=7b9dc13b94) | Oct 10, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [467a3d55ed](https://linux-hardware.org/?probe=467a3d55ed) | Oct 09, 2020 |
| NEC Comput... | PC-LL750F26C                | Notebook    | [eb148db6e7](https://linux-hardware.org/?probe=eb148db6e7) | Oct 09, 2020 |
| ECS           | G43T-3L                     | Desktop     | [7cf090fb8f](https://linux-hardware.org/?probe=7cf090fb8f) | Oct 08, 2020 |
| ECS           | G43T-3L                     | Desktop     | [3533b87774](https://linux-hardware.org/?probe=3533b87774) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | Desktop     | [26497a27c8](https://linux-hardware.org/?probe=26497a27c8) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | Desktop     | [969cdedc18](https://linux-hardware.org/?probe=969cdedc18) | Oct 08, 2020 |
| Sony          | VPCS129FJ                   | Notebook    | [ababc3caff](https://linux-hardware.org/?probe=ababc3caff) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | Notebook    | [e4b06fc3af](https://linux-hardware.org/?probe=e4b06fc3af) | Oct 07, 2020 |
| HP            | ENVY 15                     | Notebook    | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Fujitsu       | FMVWW11W                    | Notebook    | [e1a03b47aa](https://linux-hardware.org/?probe=e1a03b47aa) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [ebe29c2e8c](https://linux-hardware.org/?probe=ebe29c2e8c) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [4c90a49a16](https://linux-hardware.org/?probe=4c90a49a16) | Oct 05, 2020 |
| HP            | ProBook 6560b               | Notebook    | [4f60a7aca9](https://linux-hardware.org/?probe=4f60a7aca9) | Oct 05, 2020 |
| Supermicro    | X11SPL-F                    | Server      | [4d0ed95e02](https://linux-hardware.org/?probe=4d0ed95e02) | Oct 05, 2020 |
| Unknown       | Unknown                     | Desktop     | [89eee20d80](https://linux-hardware.org/?probe=89eee20d80) | Oct 05, 2020 |
| ECS           | G43T-3L                     | Desktop     | [b97fcd2011](https://linux-hardware.org/?probe=b97fcd2011) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [117567ed8a](https://linux-hardware.org/?probe=117567ed8a) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | Notebook    | [c1729c7402](https://linux-hardware.org/?probe=c1729c7402) | Oct 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [51fb8f3cad](https://linux-hardware.org/?probe=51fb8f3cad) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | Desktop     | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| MSI           | H270 PC MATE                | Desktop     | [3c5eb42494](https://linux-hardware.org/?probe=3c5eb42494) | Sep 30, 2020 |
| Lenovo        | M4450 20302                 | Notebook    | [0614174763](https://linux-hardware.org/?probe=0614174763) | Sep 29, 2020 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [121f0b68c0](https://linux-hardware.org/?probe=121f0b68c0) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [84913584dc](https://linux-hardware.org/?probe=84913584dc) | Sep 27, 2020 |
| ASUSTek       | P8H77-V                     | Desktop     | [954984a1e5](https://linux-hardware.org/?probe=954984a1e5) | Sep 23, 2020 |
| Sharp         | PC-WE/WT Series             | Notebook    | [91e9663e3a](https://linux-hardware.org/?probe=91e9663e3a) | Sep 22, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [21822dbd0d](https://linux-hardware.org/?probe=21822dbd0d) | Sep 19, 2020 |
| HP            | ProBook 6550b               | Notebook    | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [692295c2b0](https://linux-hardware.org/?probe=692295c2b0) | Sep 19, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | Notebook    | [087fa4f531](https://linux-hardware.org/?probe=087fa4f531) | Sep 17, 2020 |
| HP            | ProBook 6570b               | Notebook    | [db08cfd499](https://linux-hardware.org/?probe=db08cfd499) | Sep 17, 2020 |
| Supermicro    | X11DPH-T                    | Server      | [a484f1a6e6](https://linux-hardware.org/?probe=a484f1a6e6) | Sep 16, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [988b8ec0f7](https://linux-hardware.org/?probe=988b8ec0f7) | Sep 14, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| Foxconn       | A7DA-S/A7DA                 | Desktop     | [7974b8af2f](https://linux-hardware.org/?probe=7974b8af2f) | Sep 11, 2020 |
| HP            | 0AECh D                     | Desktop     | [acc13196ef](https://linux-hardware.org/?probe=acc13196ef) | Sep 11, 2020 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [ea5edd6a1b](https://linux-hardware.org/?probe=ea5edd6a1b) | Sep 11, 2020 |
| Sony          | VGN-NW50JB                  | Notebook    | [f5115778c1](https://linux-hardware.org/?probe=f5115778c1) | Sep 11, 2020 |
| ASRock        | X79 Extreme4                | Desktop     | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ECS           | G31T-M                      | Desktop     | [5b10fa37b2](https://linux-hardware.org/?probe=5b10fa37b2) | Sep 09, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [37e43e92e5](https://linux-hardware.org/?probe=37e43e92e5) | Sep 07, 2020 |
| HP            | ENVY Notebook               | Notebook    | [4da75a6d49](https://linux-hardware.org/?probe=4da75a6d49) | Sep 07, 2020 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [d9a2738dd0](https://linux-hardware.org/?probe=d9a2738dd0) | Sep 07, 2020 |
| ASRock        | Z170 Extreme4               | Desktop     | [688b4a3ae6](https://linux-hardware.org/?probe=688b4a3ae6) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | Desktop     | [b9e6801288](https://linux-hardware.org/?probe=b9e6801288) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | Desktop     | [176ca21f28](https://linux-hardware.org/?probe=176ca21f28) | Sep 06, 2020 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [415e105225](https://linux-hardware.org/?probe=415e105225) | Sep 06, 2020 |
| Toshiba       | dynabook T554/56KW          | Notebook    | [03f3e6b816](https://linux-hardware.org/?probe=03f3e6b816) | Sep 04, 2020 |
| Samsung       | 940X3G/930X3G               | Notebook    | [d63abb12ee](https://linux-hardware.org/?probe=d63abb12ee) | Sep 03, 2020 |
| Toshiba       | dynabook SS MX/25AE         | Notebook    | [8d195475bf](https://linux-hardware.org/?probe=8d195475bf) | Sep 02, 2020 |
| Gigabyte      | H67A-D3H-B3                 | Desktop     | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [b782fe1564](https://linux-hardware.org/?probe=b782fe1564) | Aug 31, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [7451d691b9](https://linux-hardware.org/?probe=7451d691b9) | Aug 31, 2020 |
| Dell          | 0NW73C A01                  | Desktop     | [6d64ca0ffc](https://linux-hardware.org/?probe=6d64ca0ffc) | Aug 29, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a2c94f7fdd](https://linux-hardware.org/?probe=a2c94f7fdd) | Aug 29, 2020 |
| Intel         | S5000XVN                    | Server      | [03f09902c6](https://linux-hardware.org/?probe=03f09902c6) | Aug 25, 2020 |
| Acer          | Aspire V3-571               | Notebook    | [8b32c068dc](https://linux-hardware.org/?probe=8b32c068dc) | Aug 24, 2020 |
| UNITCOM       | W35_37ET                    | Notebook    | [221322a11d](https://linux-hardware.org/?probe=221322a11d) | Aug 18, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [28aacac404](https://linux-hardware.org/?probe=28aacac404) | Aug 16, 2020 |
| Unknown       | XH61X000.100                | Desktop     | [1173d1c86c](https://linux-hardware.org/?probe=1173d1c86c) | Aug 16, 2020 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [abd9798aa8](https://linux-hardware.org/?probe=abd9798aa8) | Aug 15, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [ea2752e5b3](https://linux-hardware.org/?probe=ea2752e5b3) | Aug 14, 2020 |
| Sony          | SVE14A18FJW                 | Notebook    | [0868a90d93](https://linux-hardware.org/?probe=0868a90d93) | Aug 11, 2020 |
| Sony          | SVE14A18FJW                 | Notebook    | [dcd00b5fdc](https://linux-hardware.org/?probe=dcd00b5fdc) | Aug 11, 2020 |
| Lenovo        | ThinkPad T400 6475F99       | Notebook    | [83366b7e92](https://linux-hardware.org/?probe=83366b7e92) | Aug 10, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | Desktop     | [729d1212fc](https://linux-hardware.org/?probe=729d1212fc) | Aug 09, 2020 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [58a4a2906c](https://linux-hardware.org/?probe=58a4a2906c) | Aug 09, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| Fujitsu       | D3523-Ax S26361-D3523-Ax    | Desktop     | [b5164ce426](https://linux-hardware.org/?probe=b5164ce426) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1ae67d880c](https://linux-hardware.org/?probe=1ae67d880c) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | Notebook    | [edad55d12d](https://linux-hardware.org/?probe=edad55d12d) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | Notebook    | [e1fd71a4b1](https://linux-hardware.org/?probe=e1fd71a4b1) | Aug 02, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [52e898a51b](https://linux-hardware.org/?probe=52e898a51b) | Aug 01, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3fbf2d2b95](https://linux-hardware.org/?probe=3fbf2d2b95) | Aug 01, 2020 |
| Panasonic     | CF-N9LYDKDS                 | Notebook    | [8f3337d6ad](https://linux-hardware.org/?probe=8f3337d6ad) | Jul 31, 2020 |
| Fujitsu       | FMVU2400AD                  | Notebook    | [3353544fa3](https://linux-hardware.org/?probe=3353544fa3) | Jul 31, 2020 |
| Unknown       | Unknown                     | Desktop     | [e94665aec0](https://linux-hardware.org/?probe=e94665aec0) | Jul 31, 2020 |
| Acer          | F690GVM                     | Desktop     | [71f0df745c](https://linux-hardware.org/?probe=71f0df745c) | Jul 30, 2020 |
| ASRock        | H55M-GE                     | Desktop     | [374978dac5](https://linux-hardware.org/?probe=374978dac5) | Jul 29, 2020 |
| ASRock        | H55M-GE                     | Desktop     | [235e00b675](https://linux-hardware.org/?probe=235e00b675) | Jul 29, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [7d3e5091ef](https://linux-hardware.org/?probe=7d3e5091ef) | Jul 29, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [bb8dec90c6](https://linux-hardware.org/?probe=bb8dec90c6) | Jul 27, 2020 |
| Dell          | 0Y7WYT A00                  | Desktop     | [efc2b837a2](https://linux-hardware.org/?probe=efc2b837a2) | Jul 26, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [d570d72a27](https://linux-hardware.org/?probe=d570d72a27) | Jul 26, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| Toshiba       | dynabook T554/56KW          | Notebook    | [a6edb6db3c](https://linux-hardware.org/?probe=a6edb6db3c) | Jul 23, 2020 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0eeeb834c1](https://linux-hardware.org/?probe=0eeeb834c1) | Jul 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [630641627d](https://linux-hardware.org/?probe=630641627d) | Jul 22, 2020 |
| Lenovo        | ThinkPad E520 1143RD9       | Notebook    | [8947a114a1](https://linux-hardware.org/?probe=8947a114a1) | Jul 20, 2020 |
| HP            | 158A                        | Desktop     | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | Desktop     | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| NEC Comput... | PC-GN246W3A5                | Notebook    | [b95df976ea](https://linux-hardware.org/?probe=b95df976ea) | Jul 19, 2020 |
| AOpen         | AX4SG-N 918AT10202          | Desktop     | [44e42d5468](https://linux-hardware.org/?probe=44e42d5468) | Jul 19, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [c21bfaa19a](https://linux-hardware.org/?probe=c21bfaa19a) | Jul 18, 2020 |
| Fujitsu       | FMVA705BW                   | Notebook    | [0985e32752](https://linux-hardware.org/?probe=0985e32752) | Jul 18, 2020 |
| Intel         | D510MO AAE76523-403         | Desktop     | [a8297ffb6c](https://linux-hardware.org/?probe=a8297ffb6c) | Jul 17, 2020 |
| Toshiba       | dynabook EX/66MRD           | Notebook    | [e3a6da6bcc](https://linux-hardware.org/?probe=e3a6da6bcc) | Jul 16, 2020 |
| Shuttle       | FG41 V20                    | Desktop     | [a714d062a3](https://linux-hardware.org/?probe=a714d062a3) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [faca3dbfa3](https://linux-hardware.org/?probe=faca3dbfa3) | Jul 15, 2020 |
| ASRock        | X470 Master SLI             | Desktop     | [efa706ee83](https://linux-hardware.org/?probe=efa706ee83) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4f60404fb3](https://linux-hardware.org/?probe=4f60404fb3) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| HP            | 0A54h                       | Desktop     | [944573af57](https://linux-hardware.org/?probe=944573af57) | Jul 13, 2020 |
| HP            | 158A                        | Desktop     | [f5c2d58594](https://linux-hardware.org/?probe=f5c2d58594) | Jul 13, 2020 |
| ASUSTek       | TUF Gaming FA506IU_TUF50... | Notebook    | [51c975b932](https://linux-hardware.org/?probe=51c975b932) | Jul 12, 2020 |
| NEC Comput... | PC-VJ19SGHDWLTF             | Notebook    | [b99df50393](https://linux-hardware.org/?probe=b99df50393) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | Notebook    | [bc217e9435](https://linux-hardware.org/?probe=bc217e9435) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | Notebook    | [9b2e49ccd8](https://linux-hardware.org/?probe=9b2e49ccd8) | Jul 12, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [7cf0424b3b](https://linux-hardware.org/?probe=7cf0424b3b) | Jul 10, 2020 |
| HP            | 158A                        | Desktop     | [52e8f357cc](https://linux-hardware.org/?probe=52e8f357cc) | Jul 10, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [004f2e3d8b](https://linux-hardware.org/?probe=004f2e3d8b) | Jul 10, 2020 |
| EPSON DIRE... | ST170E                      | Desktop     | [fa44f643d1](https://linux-hardware.org/?probe=fa44f643d1) | Jul 09, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [31285675c8](https://linux-hardware.org/?probe=31285675c8) | Jul 09, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [3348cccfcf](https://linux-hardware.org/?probe=3348cccfcf) | Jul 07, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | Notebook    | [439f2ff831](https://linux-hardware.org/?probe=439f2ff831) | Jul 07, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | Notebook    | [770f2f3b0b](https://linux-hardware.org/?probe=770f2f3b0b) | Jul 07, 2020 |
| HP            | ProBook 470 G1              | Notebook    | [7e2ba71d87](https://linux-hardware.org/?probe=7e2ba71d87) | Jul 06, 2020 |
| NEC Comput... | MS-7594VH                   | Desktop     | [7bb53810f4](https://linux-hardware.org/?probe=7bb53810f4) | Jul 04, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [f8d281db4b](https://linux-hardware.org/?probe=f8d281db4b) | Jul 04, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [96bbacdb7a](https://linux-hardware.org/?probe=96bbacdb7a) | Jul 04, 2020 |
| Dell          | 0MF252                      | Desktop     | [682081179d](https://linux-hardware.org/?probe=682081179d) | Jul 03, 2020 |
| MSI           | AM1I                        | Desktop     | [b67361f132](https://linux-hardware.org/?probe=b67361f132) | Jul 03, 2020 |
| MSI           | AM1I                        | Desktop     | [34352c7324](https://linux-hardware.org/?probe=34352c7324) | Jul 03, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [52981221fb](https://linux-hardware.org/?probe=52981221fb) | Jul 02, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [5b28cc735f](https://linux-hardware.org/?probe=5b28cc735f) | Jul 02, 2020 |
| Fujitsu       | FMVNF70W                    | Notebook    | [28307d3d6c](https://linux-hardware.org/?probe=28307d3d6c) | Jul 02, 2020 |
| ASUSTek       | K53SK                       | Notebook    | [2003676ccf](https://linux-hardware.org/?probe=2003676ccf) | Jul 01, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [13aec875c0](https://linux-hardware.org/?probe=13aec875c0) | Jun 28, 2020 |
| Gigabyte      | G33-DS3R                    | Desktop     | [ba90c2bc8a](https://linux-hardware.org/?probe=ba90c2bc8a) | Jun 28, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6457099b06](https://linux-hardware.org/?probe=6457099b06) | Jun 27, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [8754b0ae46](https://linux-hardware.org/?probe=8754b0ae46) | Jun 27, 2020 |
| MSI           | GS63 7RE                    | Notebook    | [31dfc658d7](https://linux-hardware.org/?probe=31dfc658d7) | Jun 26, 2020 |
| ASUSTek       | Rampage Formula             | Desktop     | [d6042911d7](https://linux-hardware.org/?probe=d6042911d7) | Jun 26, 2020 |
| ASUSTek       | Rampage Formula             | Desktop     | [0cef269aa8](https://linux-hardware.org/?probe=0cef269aa8) | Jun 26, 2020 |
| Intel         | DH61BE AAG14062-206         | Desktop     | [13043e1664](https://linux-hardware.org/?probe=13043e1664) | Jun 26, 2020 |
| Apple         | MacBookPro11,1              | Notebook    | [2a32b846c5](https://linux-hardware.org/?probe=2a32b846c5) | Jun 24, 2020 |
| ASRock        | Z87 Extreme4                | Desktop     | [78ee2fc419](https://linux-hardware.org/?probe=78ee2fc419) | Jun 24, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7d3ab72cf8](https://linux-hardware.org/?probe=7d3ab72cf8) | Jun 23, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [8aaaf9416e](https://linux-hardware.org/?probe=8aaaf9416e) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [e6d89dc95b](https://linux-hardware.org/?probe=e6d89dc95b) | Jun 22, 2020 |
| ASUSTek       | P5B-E Plus                  | Desktop     | [03c7fbadbe](https://linux-hardware.org/?probe=03c7fbadbe) | Jun 22, 2020 |
| Lenovo        | ThinkPad T500 208843J       | Notebook    | [a12d551827](https://linux-hardware.org/?probe=a12d551827) | Jun 21, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | Notebook    | [dca0b5baa2](https://linux-hardware.org/?probe=dca0b5baa2) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | Notebook    | [198cec29f3](https://linux-hardware.org/?probe=198cec29f3) | Jun 21, 2020 |
| Gigabyte      | Z390 UD                     | Desktop     | [637edc299c](https://linux-hardware.org/?probe=637edc299c) | Jun 20, 2020 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [acbdac722c](https://linux-hardware.org/?probe=acbdac722c) | Jun 19, 2020 |
| Fujitsu       | FJNB04F                     | Desktop     | [15202a6cae](https://linux-hardware.org/?probe=15202a6cae) | Jun 19, 2020 |
| Fujitsu       | FJNB04F                     | Desktop     | [199eca36a2](https://linux-hardware.org/?probe=199eca36a2) | Jun 19, 2020 |
| ASRock        | B460M Pro4                  | Desktop     | [9b0c21ddaf](https://linux-hardware.org/?probe=9b0c21ddaf) | Jun 19, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [216109b0bf](https://linux-hardware.org/?probe=216109b0bf) | Jun 19, 2020 |
| Pegatron      | IPMSB-H61                   | Desktop     | [6182092aa0](https://linux-hardware.org/?probe=6182092aa0) | Jun 18, 2020 |
| ASRock        | J4105M                      | Desktop     | [a1620f0637](https://linux-hardware.org/?probe=a1620f0637) | Jun 18, 2020 |
| MSI           | H67MA-E45                   | Desktop     | [e54c477ff4](https://linux-hardware.org/?probe=e54c477ff4) | Jun 17, 2020 |
| MSI           | H67MA-E45                   | Desktop     | [7ec2ad02d1](https://linux-hardware.org/?probe=7ec2ad02d1) | Jun 17, 2020 |
| Gigabyte      | G33-DS3R                    | Desktop     | [94cd0685d0](https://linux-hardware.org/?probe=94cd0685d0) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | Desktop     | [c713e8fe0a](https://linux-hardware.org/?probe=c713e8fe0a) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | Desktop     | [24ba426f14](https://linux-hardware.org/?probe=24ba426f14) | Jun 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a01cc45fc9](https://linux-hardware.org/?probe=a01cc45fc9) | Jun 15, 2020 |
| Dell          | Inspiron 15-3565            | Notebook    | [696dea86af](https://linux-hardware.org/?probe=696dea86af) | Jun 15, 2020 |
| Apple         | MacBookPro16,1              | Notebook    | [8b4c1f4506](https://linux-hardware.org/?probe=8b4c1f4506) | Jun 15, 2020 |
| Gigabyte      | G33-DS3R                    | Desktop     | [7608803f5f](https://linux-hardware.org/?probe=7608803f5f) | Jun 14, 2020 |
| ASRock        | H67DE3                      | Desktop     | [7a70672456](https://linux-hardware.org/?probe=7a70672456) | Jun 13, 2020 |
| ASRock        | H67DE3                      | Desktop     | [cc6d5aa5c4](https://linux-hardware.org/?probe=cc6d5aa5c4) | Jun 13, 2020 |
| ASUSTek       | VM42                        | Desktop     | [0e8e6fd4f6](https://linux-hardware.org/?probe=0e8e6fd4f6) | Jun 13, 2020 |
| Sony          | VAIO                        | All in one  | [cfdcac5734](https://linux-hardware.org/?probe=cfdcac5734) | Jun 13, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [5cedae8b83](https://linux-hardware.org/?probe=5cedae8b83) | Jun 12, 2020 |
| Gateway       | NE56R                       | Notebook    | [45934f9b2c](https://linux-hardware.org/?probe=45934f9b2c) | Jun 12, 2020 |
| ASUSTek       | K53SK                       | Notebook    | [ec6ff61a8c](https://linux-hardware.org/?probe=ec6ff61a8c) | Jun 12, 2020 |
| HP            | 18E7                        | Desktop     | [5d52f06e43](https://linux-hardware.org/?probe=5d52f06e43) | Jun 11, 2020 |
| Fujitsu       | FMVNFG60TC                  | Notebook    | [b6bad717fa](https://linux-hardware.org/?probe=b6bad717fa) | Jun 10, 2020 |
| Fujitsu       | FMVNFG60TC                  | Notebook    | [1b3a040711](https://linux-hardware.org/?probe=1b3a040711) | Jun 10, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [75f3ae6145](https://linux-hardware.org/?probe=75f3ae6145) | Jun 10, 2020 |
| Fujitsu       | FMVA77JW                    | Notebook    | [ce5b1dbbcb](https://linux-hardware.org/?probe=ce5b1dbbcb) | Jun 10, 2020 |
| Dell          | Inspiron 15-3565            | Notebook    | [91540b6b55](https://linux-hardware.org/?probe=91540b6b55) | Jun 10, 2020 |
| Foxconn       | A7DA-S/A7DA                 | Desktop     | [0811f5f8ff](https://linux-hardware.org/?probe=0811f5f8ff) | Jun 09, 2020 |
| Lenovo        | ThinkPad X230 232425J       | Notebook    | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| ASUSTek       | K8V-X SE                    | Desktop     | [8480b7d838](https://linux-hardware.org/?probe=8480b7d838) | Jun 06, 2020 |
| HP            | 805A                        | Desktop     | [ff57395238](https://linux-hardware.org/?probe=ff57395238) | Jun 05, 2020 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [09e6763a1e](https://linux-hardware.org/?probe=09e6763a1e) | Jun 04, 2020 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [ab62acd597](https://linux-hardware.org/?probe=ab62acd597) | Jun 04, 2020 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [b858785e6c](https://linux-hardware.org/?probe=b858785e6c) | Jun 04, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [c4d2595650](https://linux-hardware.org/?probe=c4d2595650) | Jun 04, 2020 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [be96228f7f](https://linux-hardware.org/?probe=be96228f7f) | Jun 03, 2020 |
| Dell          | 0CKCXH A04                  | Desktop     | [0b782c6457](https://linux-hardware.org/?probe=0b782c6457) | Jun 03, 2020 |
| HP            | 18E7                        | Desktop     | [98c9458523](https://linux-hardware.org/?probe=98c9458523) | Jun 02, 2020 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [b67c33afab](https://linux-hardware.org/?probe=b67c33afab) | Jun 01, 2020 |
| Gateway       | IPISB-VR                    | Desktop     | [9fcd287a96](https://linux-hardware.org/?probe=9fcd287a96) | May 31, 2020 |
| Gateway       | IPISB-VR                    | Desktop     | [fbb92a7b21](https://linux-hardware.org/?probe=fbb92a7b21) | May 31, 2020 |
| MSI           | H110M GAMING                | Desktop     | [58c02952ac](https://linux-hardware.org/?probe=58c02952ac) | May 31, 2020 |
| ASUSTek       | H87I-PLUS                   | Desktop     | [f830159e63](https://linux-hardware.org/?probe=f830159e63) | May 30, 2020 |
| HUAWEI        | HN-WX9X                     | Notebook    | [7c56c01092](https://linux-hardware.org/?probe=7c56c01092) | May 30, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [4cdd92c012](https://linux-hardware.org/?probe=4cdd92c012) | May 29, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [5cb214c156](https://linux-hardware.org/?probe=5cb214c156) | May 27, 2020 |
| Lenovo        | ThinkPad 20JDCTO1WW         | Convertible | [cfd2c087e7](https://linux-hardware.org/?probe=cfd2c087e7) | May 27, 2020 |
| Supermicro    | X9DA7/E                     | Desktop     | [c1586ca94e](https://linux-hardware.org/?probe=c1586ca94e) | May 27, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [18895b4469](https://linux-hardware.org/?probe=18895b4469) | May 27, 2020 |
| HP            | 18E7                        | Desktop     | [e85c8c8c1f](https://linux-hardware.org/?probe=e85c8c8c1f) | May 27, 2020 |
| Panasonic     | CF-195W1ACS                 | Notebook    | [5ee3c1d71e](https://linux-hardware.org/?probe=5ee3c1d71e) | May 27, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [e219e1df90](https://linux-hardware.org/?probe=e219e1df90) | May 25, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [46683fd696](https://linux-hardware.org/?probe=46683fd696) | May 25, 2020 |
| MouseCompu... | B360M                       | Desktop     | [33e415ae9c](https://linux-hardware.org/?probe=33e415ae9c) | May 25, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [208561b660](https://linux-hardware.org/?probe=208561b660) | May 25, 2020 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Onkyo         | ONKYOPC                     | Desktop     | [cc90a61c2f](https://linux-hardware.org/?probe=cc90a61c2f) | May 24, 2020 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [3a815cf994](https://linux-hardware.org/?probe=3a815cf994) | May 23, 2020 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [326f938ec3](https://linux-hardware.org/?probe=326f938ec3) | May 23, 2020 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [1052e1ae46](https://linux-hardware.org/?probe=1052e1ae46) | May 23, 2020 |
| Acer          | Aspire 8940G                | Notebook    | [186821b722](https://linux-hardware.org/?probe=186821b722) | May 23, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [7b5401d05e](https://linux-hardware.org/?probe=7b5401d05e) | May 22, 2020 |
| ASRock        | J5005-ITX                   | Desktop     | [e3f18b5738](https://linux-hardware.org/?probe=e3f18b5738) | May 21, 2020 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [b29724fa96](https://linux-hardware.org/?probe=b29724fa96) | May 21, 2020 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [ab3c4986e4](https://linux-hardware.org/?probe=ab3c4986e4) | May 21, 2020 |
| Fujitsu       | D2619 S26361-D2619-A14 W... | Server      | [28d7f4fa53](https://linux-hardware.org/?probe=28d7f4fa53) | May 20, 2020 |
| Unknown       | Unknown                     | Notebook    | [d163d86dcb](https://linux-hardware.org/?probe=d163d86dcb) | May 19, 2020 |
| Toshiba       | dynabook T45/VRS            | Notebook    | [ddae801625](https://linux-hardware.org/?probe=ddae801625) | May 18, 2020 |
| Toshiba       | dynabook T45/VRS            | Notebook    | [efafbf544b](https://linux-hardware.org/?probe=efafbf544b) | May 18, 2020 |
| Panasonic     | CFSX4-1L                    | Notebook    | [54b56291de](https://linux-hardware.org/?probe=54b56291de) | May 18, 2020 |
| NEC Comput... | MS-7777N1                   | Desktop     | [5cea911946](https://linux-hardware.org/?probe=5cea911946) | May 18, 2020 |
| NEC Comput... | MS-7777N1                   | Desktop     | [0afcb9ba8d](https://linux-hardware.org/?probe=0afcb9ba8d) | May 17, 2020 |
| ASUSTek       | P5E                         | Desktop     | [67df8c58c9](https://linux-hardware.org/?probe=67df8c58c9) | May 16, 2020 |
| ASUSTek       | P6T                         | Desktop     | [90b5a63736](https://linux-hardware.org/?probe=90b5a63736) | May 16, 2020 |
| HP            | ProBook 6560b               | Notebook    | [72808d19a6](https://linux-hardware.org/?probe=72808d19a6) | May 15, 2020 |
| HP            | ProBook 6560b               | Notebook    | [f88ec1bc1d](https://linux-hardware.org/?probe=f88ec1bc1d) | May 15, 2020 |
| ASUSTek       | P5E                         | Desktop     | [140c3b0db8](https://linux-hardware.org/?probe=140c3b0db8) | May 11, 2020 |
| Lenovo        | G570 4334                   | Notebook    | [54ff12939f](https://linux-hardware.org/?probe=54ff12939f) | May 11, 2020 |
| HP            | 158A                        | Desktop     | [5af55dbc63](https://linux-hardware.org/?probe=5af55dbc63) | May 09, 2020 |
| MSI           | MEG X570 ACE                | Desktop     | [dc7e369d45](https://linux-hardware.org/?probe=dc7e369d45) | May 08, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [01445b6224](https://linux-hardware.org/?probe=01445b6224) | May 07, 2020 |
| Toshiba       | dynabook CX/45J             | Notebook    | [98a1bae5fd](https://linux-hardware.org/?probe=98a1bae5fd) | May 06, 2020 |
| HP            | Pavilion dv4                | Notebook    | [ea93ee2d08](https://linux-hardware.org/?probe=ea93ee2d08) | May 06, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [593c0984df](https://linux-hardware.org/?probe=593c0984df) | May 05, 2020 |
| ASRock        | 970 Extreme3                | Desktop     | [5391547134](https://linux-hardware.org/?probe=5391547134) | May 05, 2020 |
| Apple         | MacBookPro9,2               | Notebook    | [02d47ceb31](https://linux-hardware.org/?probe=02d47ceb31) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | Desktop     | [a36a61fc42](https://linux-hardware.org/?probe=a36a61fc42) | May 05, 2020 |
| ASUSTek       | P8B75-M                     | Desktop     | [64b3255738](https://linux-hardware.org/?probe=64b3255738) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | Desktop     | [0e1b63c36e](https://linux-hardware.org/?probe=0e1b63c36e) | May 05, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [9b591e104f](https://linux-hardware.org/?probe=9b591e104f) | May 04, 2020 |
| Gateway       | NE56R                       | Notebook    | [6d4a0dd1b6](https://linux-hardware.org/?probe=6d4a0dd1b6) | May 04, 2020 |
| Gateway       | NE56R                       | Notebook    | [2910284c56](https://linux-hardware.org/?probe=2910284c56) | May 03, 2020 |
| Notebook      | N15_17RF                    | Notebook    | [3ec814dabd](https://linux-hardware.org/?probe=3ec814dabd) | May 01, 2020 |
| Toshiba       | dynabook Satellite B551/... | Notebook    | [b0ec3775c4](https://linux-hardware.org/?probe=b0ec3775c4) | Apr 29, 2020 |
| Lenovo        | ThinkPad Edge E130 3358C... | Notebook    | [2bc6ee441e](https://linux-hardware.org/?probe=2bc6ee441e) | Apr 29, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [8481b529ee](https://linux-hardware.org/?probe=8481b529ee) | Apr 28, 2020 |
| HP            | Pavilion dv7                | Notebook    | [12f72e240a](https://linux-hardware.org/?probe=12f72e240a) | Apr 28, 2020 |
| Toshiba       | dynabook BX/571KW           | Notebook    | [9ba95d923c](https://linux-hardware.org/?probe=9ba95d923c) | Apr 22, 2020 |
| ASUSTek       | X45U                        | Notebook    | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| ASUSTek       | P8B75-M                     | Desktop     | [38669e151b](https://linux-hardware.org/?probe=38669e151b) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | Desktop     | [7e39b26e35](https://linux-hardware.org/?probe=7e39b26e35) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | Desktop     | [a622ca867c](https://linux-hardware.org/?probe=a622ca867c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | Desktop     | [a258fe9d3c](https://linux-hardware.org/?probe=a258fe9d3c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | Desktop     | [5c757ca851](https://linux-hardware.org/?probe=5c757ca851) | Apr 17, 2020 |
| Acer          | Aspire A515-43              | Notebook    | [4eda844896](https://linux-hardware.org/?probe=4eda844896) | Apr 15, 2020 |
| MouseCompu... | Z170-S01                    | Desktop     | [48ca5fe277](https://linux-hardware.org/?probe=48ca5fe277) | Apr 15, 2020 |
| MouseCompu... | Z170-S01                    | Desktop     | [9157166443](https://linux-hardware.org/?probe=9157166443) | Apr 15, 2020 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [6169eb8c91](https://linux-hardware.org/?probe=6169eb8c91) | Apr 14, 2020 |
| Toshiba       | dynabook BX/571KW           | Notebook    | [b8dba9c83d](https://linux-hardware.org/?probe=b8dba9c83d) | Apr 13, 2020 |
| Intel         | CAPELL VALLEY CRB           | Notebook    | [2d21b4d154](https://linux-hardware.org/?probe=2d21b4d154) | Apr 12, 2020 |
| ASRock        | H310CM-HDV/M.2              | Desktop     | [253ee15233](https://linux-hardware.org/?probe=253ee15233) | Apr 12, 2020 |
| Dell          | Inspiron 3541               | Notebook    | [a1569c7977](https://linux-hardware.org/?probe=a1569c7977) | Apr 09, 2020 |
| Dell          | Inspiron 3541               | Notebook    | [6c900e8ddf](https://linux-hardware.org/?probe=6c900e8ddf) | Apr 09, 2020 |
| MCJ           | H55M-P33                    | Desktop     | [cb5e96a31a](https://linux-hardware.org/?probe=cb5e96a31a) | Apr 08, 2020 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [abe59477d7](https://linux-hardware.org/?probe=abe59477d7) | Apr 05, 2020 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [41eee8b868](https://linux-hardware.org/?probe=41eee8b868) | Apr 04, 2020 |
| ASRock        | H310M-STX                   | Desktop     | [5fbe6e4ee6](https://linux-hardware.org/?probe=5fbe6e4ee6) | Apr 01, 2020 |
| ASRock        | H310M-STX                   | Desktop     | [4a58d0cf1f](https://linux-hardware.org/?probe=4a58d0cf1f) | Apr 01, 2020 |
| NEC Comput... | PC-LL550KG6GN               | Notebook    | [bc1a12a76f](https://linux-hardware.org/?probe=bc1a12a76f) | Mar 26, 2020 |
| Fujitsu       | FARQ06012Z                  | Notebook    | [6d19311f7e](https://linux-hardware.org/?probe=6d19311f7e) | Mar 23, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [6fc123427e](https://linux-hardware.org/?probe=6fc123427e) | Mar 21, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [ec5fdd7cf2](https://linux-hardware.org/?probe=ec5fdd7cf2) | Mar 21, 2020 |
| Lenovo        | ThinkPad T500 208843J       | Notebook    | [f221fcd053](https://linux-hardware.org/?probe=f221fcd053) | Mar 19, 2020 |
| ASUSTek       | P5E-VM HDMI                 | Desktop     | [95d96a6705](https://linux-hardware.org/?probe=95d96a6705) | Mar 14, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [cd22cce33d](https://linux-hardware.org/?probe=cd22cce33d) | Mar 12, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [1cd8601a1e](https://linux-hardware.org/?probe=1cd8601a1e) | Mar 12, 2020 |
| HP            | ProBook 4320s               | Notebook    | [92478c20d5](https://linux-hardware.org/?probe=92478c20d5) | Mar 11, 2020 |
| Acer          | Aspire V3-571               | Notebook    | [82955eaaa3](https://linux-hardware.org/?probe=82955eaaa3) | Mar 10, 2020 |
| HP            | ProBook 4320s               | Notebook    | [96b40c5d0e](https://linux-hardware.org/?probe=96b40c5d0e) | Mar 05, 2020 |
| Acer          | Aspire V3-571               | Notebook    | [218d6c9bea](https://linux-hardware.org/?probe=218d6c9bea) | Mar 04, 2020 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [edda861710](https://linux-hardware.org/?probe=edda861710) | Mar 01, 2020 |
| HP            | Pavilion dv4                | Notebook    | [1e248b227a](https://linux-hardware.org/?probe=1e248b227a) | Feb 24, 2020 |
| Dell          | Inspiron 7380               | Notebook    | [2f37de4f3d](https://linux-hardware.org/?probe=2f37de4f3d) | Feb 23, 2020 |
| Dell          | Inspiron 7380               | Notebook    | [82f783a4d6](https://linux-hardware.org/?probe=82f783a4d6) | Feb 23, 2020 |
| ASUSTek       | 1005HA                      | Notebook    | [f668a6c2b8](https://linux-hardware.org/?probe=f668a6c2b8) | Feb 23, 2020 |
| Dell          | Inspiron 7380               | Notebook    | [a82beef9a1](https://linux-hardware.org/?probe=a82beef9a1) | Feb 23, 2020 |
| ASUSTek       | UX301LAA                    | Notebook    | [e994e96768](https://linux-hardware.org/?probe=e994e96768) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | Notebook    | [4babc87322](https://linux-hardware.org/?probe=4babc87322) | Feb 21, 2020 |
| ASUSTek       | UX301LAA                    | Notebook    | [da5b70c7c6](https://linux-hardware.org/?probe=da5b70c7c6) | Feb 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [45555d85c3](https://linux-hardware.org/?probe=45555d85c3) | Feb 20, 2020 |
| Toshiba       | dynabook EX/55LWH           | Notebook    | [8da363dbd2](https://linux-hardware.org/?probe=8da363dbd2) | Feb 20, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [d19eb25691](https://linux-hardware.org/?probe=d19eb25691) | Feb 15, 2020 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [87e4d3dd9a](https://linux-hardware.org/?probe=87e4d3dd9a) | Feb 14, 2020 |
| ECS           | G31T-M                      | Desktop     | [b765a7fa7f](https://linux-hardware.org/?probe=b765a7fa7f) | Feb 11, 2020 |
| Sharp         | PC-WE/WT Series             | Notebook    | [6d4ad9101d](https://linux-hardware.org/?probe=6d4ad9101d) | Feb 11, 2020 |
| ASRock        | H87M Pro4                   | Desktop     | [ca641865e0](https://linux-hardware.org/?probe=ca641865e0) | Feb 06, 2020 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [2e4119c423](https://linux-hardware.org/?probe=2e4119c423) | Jan 30, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [043ccd92f3](https://linux-hardware.org/?probe=043ccd92f3) | Jan 29, 2020 |
| ASRock        | A88M-G                      | Desktop     | [3949599c5d](https://linux-hardware.org/?probe=3949599c5d) | Jan 28, 2020 |
| HP            | 0A54h                       | Desktop     | [356168fec6](https://linux-hardware.org/?probe=356168fec6) | Jan 28, 2020 |
| ASRock        | A88M-G                      | Desktop     | [bb36145452](https://linux-hardware.org/?probe=bb36145452) | Jan 25, 2020 |
| ASRock        | A88M-G                      | Desktop     | [07e625051c](https://linux-hardware.org/?probe=07e625051c) | Jan 25, 2020 |
| Gateway       | RS780                       | Desktop     | [09cf381b3c](https://linux-hardware.org/?probe=09cf381b3c) | Jan 25, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [1ca6b6f436](https://linux-hardware.org/?probe=1ca6b6f436) | Jan 20, 2020 |
| Dell          | Inspiron 5485               | Notebook    | [fe8b986757](https://linux-hardware.org/?probe=fe8b986757) | Jan 19, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [b7f175312b](https://linux-hardware.org/?probe=b7f175312b) | Jan 15, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [430e5271de](https://linux-hardware.org/?probe=430e5271de) | Jan 15, 2020 |
| Toshiba       | dynabook CX/47H             | Notebook    | [f9cf94b130](https://linux-hardware.org/?probe=f9cf94b130) | Jan 14, 2020 |
| Toshiba       | dynabook CX/47H             | Notebook    | [15ce1a1178](https://linux-hardware.org/?probe=15ce1a1178) | Jan 14, 2020 |
| MSI           | GF72 8RE                    | Notebook    | [11ba6c28b8](https://linux-hardware.org/?probe=11ba6c28b8) | Jan 13, 2020 |
| Gateway       | RS780                       | Desktop     | [3fe382995a](https://linux-hardware.org/?probe=3fe382995a) | Jan 13, 2020 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [1a78f67963](https://linux-hardware.org/?probe=1a78f67963) | Jan 05, 2020 |
| ASUSTek       | X99-A                       | Desktop     | [67389da431](https://linux-hardware.org/?probe=67389da431) | Jan 04, 2020 |
| Gateway       | RS780                       | Desktop     | [3b7741a3a0](https://linux-hardware.org/?probe=3b7741a3a0) | Jan 04, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [14606a5426](https://linux-hardware.org/?probe=14606a5426) | Jan 02, 2020 |
| ASUSTek       | X99-A                       | Desktop     | [8893153b1b](https://linux-hardware.org/?probe=8893153b1b) | Jan 01, 2020 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [d8e43b34cc](https://linux-hardware.org/?probe=d8e43b34cc) | Jan 01, 2020 |
| Sony          | SVP1121A1J                  | Notebook    | [588b4f5ea9](https://linux-hardware.org/?probe=588b4f5ea9) | Dec 31, 2019 |
| Fujitsu       | FMVNFB40J                   | Notebook    | [0bfe715962](https://linux-hardware.org/?probe=0bfe715962) | Dec 30, 2019 |
| Gigabyte      | 965G-DS3                    | Desktop     | [a7a0b9ab30](https://linux-hardware.org/?probe=a7a0b9ab30) | Dec 28, 2019 |
| ASRock        | J3160DC-ITX                 | Desktop     | [b41206f2fd](https://linux-hardware.org/?probe=b41206f2fd) | Dec 22, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [ab555162c8](https://linux-hardware.org/?probe=ab555162c8) | Dec 22, 2019 |
| Fujitsu       | JIH61Y3                     | Desktop     | [5a7487a856](https://linux-hardware.org/?probe=5a7487a856) | Dec 21, 2019 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [a66e24484e](https://linux-hardware.org/?probe=a66e24484e) | Dec 19, 2019 |
| Wistron       | JIB65Y                      | Desktop     | [ed496b7bdf](https://linux-hardware.org/?probe=ed496b7bdf) | Dec 19, 2019 |
| ECS           | G31T-M                      | Desktop     | [7052a98f3b](https://linux-hardware.org/?probe=7052a98f3b) | Dec 19, 2019 |
| NEC Comput... | PC-VY25AACZ9                | Notebook    | [67db0cd3e1](https://linux-hardware.org/?probe=67db0cd3e1) | Dec 12, 2019 |
| HP            | ProBook 6570b               | Notebook    | [567e5e5444](https://linux-hardware.org/?probe=567e5e5444) | Dec 06, 2019 |
| HP            | ProBook 6570b               | Notebook    | [12e166c17a](https://linux-hardware.org/?probe=12e166c17a) | Dec 06, 2019 |
| HP            | ProBook 4310s               | Notebook    | [d67761b5c2](https://linux-hardware.org/?probe=d67761b5c2) | Dec 04, 2019 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [91947835b4](https://linux-hardware.org/?probe=91947835b4) | Dec 04, 2019 |
| Novastar      | KL55                        | Notebook    | [277007d50c](https://linux-hardware.org/?probe=277007d50c) | Dec 03, 2019 |
| Gigabyte      | 970A-D3P                    | Desktop     | [65bd7a0352](https://linux-hardware.org/?probe=65bd7a0352) | Nov 30, 2019 |
| ASRock        | H87M Pro4                   | Desktop     | [54341a6439](https://linux-hardware.org/?probe=54341a6439) | Nov 26, 2019 |
| Novastar      | KL55                        | Notebook    | [d390f7576c](https://linux-hardware.org/?probe=d390f7576c) | Nov 20, 2019 |
| Novastar      | KL55                        | Notebook    | [9d09caf5c5](https://linux-hardware.org/?probe=9d09caf5c5) | Nov 19, 2019 |
| Novastar      | KL55                        | Notebook    | [3a8b42421b](https://linux-hardware.org/?probe=3a8b42421b) | Nov 18, 2019 |
| Novastar      | KL55                        | Notebook    | [e293c143c1](https://linux-hardware.org/?probe=e293c143c1) | Nov 18, 2019 |
| MSI           | AM1I                        | Desktop     | [e6dcc8ef69](https://linux-hardware.org/?probe=e6dcc8ef69) | Nov 11, 2019 |
| HP            | Convertible x360 11-ab0X... | Convertible | [c74ed2487d](https://linux-hardware.org/?probe=c74ed2487d) | Nov 03, 2019 |
| ASUSTek       | E203NA                      | Notebook    | [103ca8741c](https://linux-hardware.org/?probe=103ca8741c) | Nov 03, 2019 |
| HP            | ProBook 4530s               | Notebook    | [d6f9cecdc5](https://linux-hardware.org/?probe=d6f9cecdc5) | Nov 03, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [91ed990d94](https://linux-hardware.org/?probe=91ed990d94) | Oct 28, 2019 |
| NEC Comput... | MS-7594VH                   | Desktop     | [9ddd905922](https://linux-hardware.org/?probe=9ddd905922) | Oct 27, 2019 |
| ECS           | G31T-M                      | Desktop     | [21dce1ded7](https://linux-hardware.org/?probe=21dce1ded7) | Oct 26, 2019 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [c38e15b8e9](https://linux-hardware.org/?probe=c38e15b8e9) | Oct 15, 2019 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7b0b66861a](https://linux-hardware.org/?probe=7b0b66861a) | Oct 12, 2019 |
| ASUSTek       | E203NA                      | Notebook    | [1e18143757](https://linux-hardware.org/?probe=1e18143757) | Oct 07, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [d41d8e1f91](https://linux-hardware.org/?probe=d41d8e1f91) | Oct 07, 2019 |
| HP            | 2ADE                        | Desktop     | [eba5a305b7](https://linux-hardware.org/?probe=eba5a305b7) | Oct 07, 2019 |
| ASUSTek       | PRIME X299-A                | Desktop     | [049af64f1e](https://linux-hardware.org/?probe=049af64f1e) | Oct 04, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [9db5f37aab](https://linux-hardware.org/?probe=9db5f37aab) | Oct 03, 2019 |
| HASEE Comp... | P65xRP                      | Notebook    | [343291949a](https://linux-hardware.org/?probe=343291949a) | Oct 03, 2019 |
| WinFast       | WS1000                      | Server      | [f99e449d8b](https://linux-hardware.org/?probe=f99e449d8b) | Sep 30, 2019 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [306e5b04f7](https://linux-hardware.org/?probe=306e5b04f7) | Sep 28, 2019 |
| Panasonic     | CF-J10YYBHR                 | Notebook    | [e00043a374](https://linux-hardware.org/?probe=e00043a374) | Sep 27, 2019 |
| Dell          | Inspiron 15-3565            | Notebook    | [6ebeac4bcd](https://linux-hardware.org/?probe=6ebeac4bcd) | Sep 27, 2019 |
| ASRock        | Z87 Killer                  | Desktop     | [ee533a4daf](https://linux-hardware.org/?probe=ee533a4daf) | Sep 26, 2019 |
| Dell          | Inspiron 15-3565            | Notebook    | [55ae5ff063](https://linux-hardware.org/?probe=55ae5ff063) | Sep 25, 2019 |
| Dell          | Inspiron 15-3565            | Notebook    | [90d49c8abd](https://linux-hardware.org/?probe=90d49c8abd) | Sep 25, 2019 |
| ECS           | G31T-M                      | Desktop     | [5cefc9e8d2](https://linux-hardware.org/?probe=5cefc9e8d2) | Sep 24, 2019 |
| Gigabyte      | H81M-DS2                    | Desktop     | [2d44575da5](https://linux-hardware.org/?probe=2d44575da5) | Sep 23, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [f9ce29fec6](https://linux-hardware.org/?probe=f9ce29fec6) | Sep 19, 2019 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [a9d1c2f51c](https://linux-hardware.org/?probe=a9d1c2f51c) | Sep 18, 2019 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [a6ed7aa983](https://linux-hardware.org/?probe=a6ed7aa983) | Sep 18, 2019 |
| ASUSTek       | M4A78-VM                    | Desktop     | [fc5bd8749b](https://linux-hardware.org/?probe=fc5bd8749b) | Sep 17, 2019 |
| ASRock        | Z87 Killer                  | Desktop     | [3918b7d23a](https://linux-hardware.org/?probe=3918b7d23a) | Sep 14, 2019 |
| Lenovo        | G570 4334                   | Notebook    | [eefedc7e75](https://linux-hardware.org/?probe=eefedc7e75) | Sep 06, 2019 |
| ECS           | A75F-M2                     | Desktop     | [f891e8f1d5](https://linux-hardware.org/?probe=f891e8f1d5) | Sep 06, 2019 |
| Lenovo        | G570 4334                   | Notebook    | [66750ab32f](https://linux-hardware.org/?probe=66750ab32f) | Sep 04, 2019 |
| Lenovo        | G570 4334                   | Notebook    | [4a4a5fe410](https://linux-hardware.org/?probe=4a4a5fe410) | Sep 04, 2019 |
| ASRock        | Z87 Killer                  | Desktop     | [a1d5416305](https://linux-hardware.org/?probe=a1d5416305) | Sep 01, 2019 |
| ECS           | G31T-M                      | Desktop     | [78a1016ee6](https://linux-hardware.org/?probe=78a1016ee6) | Aug 30, 2019 |
| ASUSTek       | PRIME X299-A                | Desktop     | [4ad9989703](https://linux-hardware.org/?probe=4ad9989703) | Aug 28, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [aec3d01ee9](https://linux-hardware.org/?probe=aec3d01ee9) | Aug 28, 2019 |
| ASUSTek       | E203NA                      | Notebook    | [187729d926](https://linux-hardware.org/?probe=187729d926) | Aug 27, 2019 |
| ASRock        | Z87 Killer                  | Desktop     | [16e84b9fb7](https://linux-hardware.org/?probe=16e84b9fb7) | Aug 24, 2019 |
| Panasonic     | CF-J10YYBHR                 | Notebook    | [0005e1a411](https://linux-hardware.org/?probe=0005e1a411) | Aug 21, 2019 |
| HP            | 1489                        | All in one  | [a6305ad3a0](https://linux-hardware.org/?probe=a6305ad3a0) | Aug 19, 2019 |
| ASUSTek       | GL12CP                      | Desktop     | [0b7ad9054f](https://linux-hardware.org/?probe=0b7ad9054f) | Aug 19, 2019 |
| HP            | 1489                        | All in one  | [ab11004070](https://linux-hardware.org/?probe=ab11004070) | Aug 16, 2019 |
| ASUSTek       | PRIME X299-A                | Desktop     | [1f914d8603](https://linux-hardware.org/?probe=1f914d8603) | Aug 15, 2019 |
| ASUSTek       | E203NA                      | Notebook    | [eb4b2d2e3e](https://linux-hardware.org/?probe=eb4b2d2e3e) | Aug 15, 2019 |
| Fujitsu       | JIH61Y3                     | Desktop     | [0bdef2ed89](https://linux-hardware.org/?probe=0bdef2ed89) | Aug 15, 2019 |
| ASUSTek       | GL12CP                      | Desktop     | [314f1278b8](https://linux-hardware.org/?probe=314f1278b8) | Aug 13, 2019 |
| ASUSTek       | GL12CP                      | Desktop     | [7e8a4409ab](https://linux-hardware.org/?probe=7e8a4409ab) | Aug 13, 2019 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53b6114671](https://linux-hardware.org/?probe=53b6114671) | Aug 13, 2019 |
| Dell          | Latitude E6500              | Notebook    | [cb9f268650](https://linux-hardware.org/?probe=cb9f268650) | Aug 12, 2019 |
| Fujitsu       | FMVNC6BE3                   | Notebook    | [24f8a2b045](https://linux-hardware.org/?probe=24f8a2b045) | Aug 10, 2019 |
| NEC Comput... | MS9666 012                  | Desktop     | [e0ccec3cb3](https://linux-hardware.org/?probe=e0ccec3cb3) | Aug 08, 2019 |
| HP            | 158B                        | Desktop     | [f588fb7831](https://linux-hardware.org/?probe=f588fb7831) | Aug 05, 2019 |
| Gigabyte      | G41M-Combo                  | Desktop     | [7a7a55bb9f](https://linux-hardware.org/?probe=7a7a55bb9f) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [63f518652d](https://linux-hardware.org/?probe=63f518652d) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [2985c7f780](https://linux-hardware.org/?probe=2985c7f780) | Jul 27, 2019 |
| Fujitsu       | FMVNC6BE3                   | Notebook    | [b2a7c69d92](https://linux-hardware.org/?probe=b2a7c69d92) | Jul 25, 2019 |
| Lenovo        | ThinkPad X121e 30456FJ      | Notebook    | [974cf0c5c6](https://linux-hardware.org/?probe=974cf0c5c6) | Jul 24, 2019 |
| Dell          | Inspiron 15-3552            | Notebook    | [ce847df44a](https://linux-hardware.org/?probe=ce847df44a) | Jul 21, 2019 |
| HP            | 1589                        | Desktop     | [2eeb0dcbef](https://linux-hardware.org/?probe=2eeb0dcbef) | Jul 18, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [8d70085277](https://linux-hardware.org/?probe=8d70085277) | Jul 16, 2019 |
| HP            | Compaq 6720s                | Notebook    | [48ee31d6e9](https://linux-hardware.org/?probe=48ee31d6e9) | Jul 16, 2019 |
| MCJ           | CO.,LTD                     | Desktop     | [0cca59b833](https://linux-hardware.org/?probe=0cca59b833) | Jul 13, 2019 |
| MCJ           | CO.,LTD                     | Desktop     | [262f82967e](https://linux-hardware.org/?probe=262f82967e) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c77e3987e8](https://linux-hardware.org/?probe=c77e3987e8) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [03894447bb](https://linux-hardware.org/?probe=03894447bb) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | Desktop     | [ef1765e325](https://linux-hardware.org/?probe=ef1765e325) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | Desktop     | [f457a91893](https://linux-hardware.org/?probe=f457a91893) | Jul 12, 2019 |
| ASUSTek       | M4A88T-I DELUXE             | Desktop     | [7011e7619b](https://linux-hardware.org/?probe=7011e7619b) | Jul 04, 2019 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [3ac82eca46](https://linux-hardware.org/?probe=3ac82eca46) | Jun 29, 2019 |
| NEC Comput... | MS-7594VH                   | Desktop     | [e61c26fd4c](https://linux-hardware.org/?probe=e61c26fd4c) | Jun 25, 2019 |
| Dell          | Latitude E6320              | Notebook    | [a45c07429f](https://linux-hardware.org/?probe=a45c07429f) | Jun 24, 2019 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [f7605b7f95](https://linux-hardware.org/?probe=f7605b7f95) | Jun 18, 2019 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [5d0ae356dd](https://linux-hardware.org/?probe=5d0ae356dd) | Jun 17, 2019 |
| SLIMBOOK      | PRO                         | Notebook    | [741aadd99e](https://linux-hardware.org/?probe=741aadd99e) | Jun 12, 2019 |
| Fujitsu       | D3521-A1 S26361-D3521-A1... | Server      | [0bd7d9fcea](https://linux-hardware.org/?probe=0bd7d9fcea) | Jun 04, 2019 |
| Alienware     | 17 R5                       | Notebook    | [8b270d4228](https://linux-hardware.org/?probe=8b270d4228) | May 30, 2019 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [6e8096d588](https://linux-hardware.org/?probe=6e8096d588) | May 28, 2019 |
| Lenovo        | ThinkPad Edge E530 32599... | Notebook    | [23f78cf853](https://linux-hardware.org/?probe=23f78cf853) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [4cf90e52e8](https://linux-hardware.org/?probe=4cf90e52e8) | May 28, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [e682a05a1f](https://linux-hardware.org/?probe=e682a05a1f) | May 27, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [167c038742](https://linux-hardware.org/?probe=167c038742) | May 27, 2019 |
| Fujitsu       | FMVWW11W                    | Notebook    | [2462f0f0bb](https://linux-hardware.org/?probe=2462f0f0bb) | May 25, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [279621d15c](https://linux-hardware.org/?probe=279621d15c) | May 20, 2019 |
| Toshiba       | Satellite A135              | Notebook    | [bc24647b76](https://linux-hardware.org/?probe=bc24647b76) | May 18, 2019 |
| Toshiba       | Satellite A135              | Notebook    | [fa5218ef36](https://linux-hardware.org/?probe=fa5218ef36) | May 16, 2019 |
| Dell          | 0XPDFK A01                  | Desktop     | [b545ad5544](https://linux-hardware.org/?probe=b545ad5544) | May 10, 2019 |
| Dell          | 0XPDFK A01                  | Desktop     | [d4c3d2990b](https://linux-hardware.org/?probe=d4c3d2990b) | May 09, 2019 |
| NEC Comput... | OA13 E3B                    | All in one  | [86771347fb](https://linux-hardware.org/?probe=86771347fb) | May 04, 2019 |
| Onkyo         | ONKYOPC 0A                  | Desktop     | [d298e61165](https://linux-hardware.org/?probe=d298e61165) | May 04, 2019 |
| ASRock        | X370 Gaming K4              | Desktop     | [f3883ffe3f](https://linux-hardware.org/?probe=f3883ffe3f) | May 03, 2019 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [d92d4f0666](https://linux-hardware.org/?probe=d92d4f0666) | May 02, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [e4d60349c2](https://linux-hardware.org/?probe=e4d60349c2) | May 01, 2019 |
| HP            | 3398                        | Desktop     | [915f8eec67](https://linux-hardware.org/?probe=915f8eec67) | Apr 30, 2019 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [740fc92339](https://linux-hardware.org/?probe=740fc92339) | Apr 26, 2019 |
| Lenovo        | 41872PU                     | Notebook    | [61cd8222cf](https://linux-hardware.org/?probe=61cd8222cf) | Apr 15, 2019 |
| Apple         | MacBookPro9,2               | Notebook    | [0c238b6751](https://linux-hardware.org/?probe=0c238b6751) | Apr 07, 2019 |
| Dell          | Inspiron 1210               | Notebook    | [7d4473a4a5](https://linux-hardware.org/?probe=7d4473a4a5) | Apr 07, 2019 |
| Dell          | 09KPNV A00                  | Desktop     | [ac628634d2](https://linux-hardware.org/?probe=ac628634d2) | Mar 30, 2019 |
| Dell          | G7 7588                     | Notebook    | [d38fee8e21](https://linux-hardware.org/?probe=d38fee8e21) | Mar 29, 2019 |
| NEC Comput... | PC-TW710EBS                 | Tablet      | [5af55e5191](https://linux-hardware.org/?probe=5af55e5191) | Mar 28, 2019 |
| HP            | Mini 5103                   | Notebook    | [266d78e723](https://linux-hardware.org/?probe=266d78e723) | Mar 25, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c5c58d8655](https://linux-hardware.org/?probe=c5c58d8655) | Mar 23, 2019 |
| MCJ           | H55-S01                     | Desktop     | [24d0907973](https://linux-hardware.org/?probe=24d0907973) | Mar 21, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4d37bac1a](https://linux-hardware.org/?probe=c4d37bac1a) | Mar 17, 2019 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3159028860](https://linux-hardware.org/?probe=3159028860) | Mar 17, 2019 |
| Teclast       | F6 Pro                      | Notebook    | [afaad4db96](https://linux-hardware.org/?probe=afaad4db96) | Mar 15, 2019 |
| Dell          | 0J584C A00                  | Desktop     | [7f79951f35](https://linux-hardware.org/?probe=7f79951f35) | Mar 10, 2019 |
| Lenovo        | ThinkPad SL410 2842CTO      | Notebook    | [f577d3875e](https://linux-hardware.org/?probe=f577d3875e) | Mar 04, 2019 |
| NEC Comput... | PC-LL750RG                  | Notebook    | [f3208d8466](https://linux-hardware.org/?probe=f3208d8466) | Mar 03, 2019 |
| Dell          | Latitude E6320              | Notebook    | [04f301dc20](https://linux-hardware.org/?probe=04f301dc20) | Feb 27, 2019 |
| Gigabyte      | M61P-S3                     | Desktop     | [b6505655d3](https://linux-hardware.org/?probe=b6505655d3) | Feb 22, 2019 |
| Gigabyte      | M61P-S3                     | Desktop     | [d1f1dd8c96](https://linux-hardware.org/?probe=d1f1dd8c96) | Feb 19, 2019 |
| Panasonic     | CF-S9JWECPS                 | Notebook    | [fd3dd464f1](https://linux-hardware.org/?probe=fd3dd464f1) | Feb 11, 2019 |
| ASUSTek       | M3A78-EM                    | Desktop     | [0120bc4801](https://linux-hardware.org/?probe=0120bc4801) | Feb 04, 2019 |
| Pegatron      | 2AB5                        | Desktop     | [c87217d642](https://linux-hardware.org/?probe=c87217d642) | Feb 03, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | Notebook    | [deac2364d1](https://linux-hardware.org/?probe=deac2364d1) | Jan 30, 2019 |
| Fujitsu       | FMVU93B3BZ                  | Notebook    | [974550aea3](https://linux-hardware.org/?probe=974550aea3) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | Notebook    | [1629601591](https://linux-hardware.org/?probe=1629601591) | Jan 30, 2019 |
| Intel         | DG965RY AAD41691-205        | Desktop     | [15252dcf05](https://linux-hardware.org/?probe=15252dcf05) | Jan 20, 2019 |
| MCJ           | H55-S01                     | Desktop     | [f694a85c3b](https://linux-hardware.org/?probe=f694a85c3b) | Jan 20, 2019 |
| MCJ           | H55-S01                     | Desktop     | [b72a8388df](https://linux-hardware.org/?probe=b72a8388df) | Jan 20, 2019 |
| Acer          | TravelMate 5730             | Notebook    | [3f204613cc](https://linux-hardware.org/?probe=3f204613cc) | Jan 13, 2019 |
| Fujitsu       | FMVNE4N1E                   | Notebook    | [8e2c99692b](https://linux-hardware.org/?probe=8e2c99692b) | Dec 29, 2018 |
| HP            | Notebook                    | Notebook    | [b73435f113](https://linux-hardware.org/?probe=b73435f113) | Dec 24, 2018 |
| HP            | Notebook                    | Notebook    | [5f943855ce](https://linux-hardware.org/?probe=5f943855ce) | Dec 24, 2018 |
| NEC Comput... | PC-LL550LG1K                | Notebook    | [004a3c19de](https://linux-hardware.org/?probe=004a3c19de) | Dec 09, 2018 |
| NEC Comput... | PC-LL550LG1K                | Notebook    | [80d5cca3f0](https://linux-hardware.org/?probe=80d5cca3f0) | Dec 09, 2018 |
| Sony          | VGN-FT31B                   | Notebook    | [7f0bb0cc92](https://linux-hardware.org/?probe=7f0bb0cc92) | Dec 06, 2018 |
| Sony          | VAIO                        | All in one  | [2628ebe1bb](https://linux-hardware.org/?probe=2628ebe1bb) | Dec 01, 2018 |
| Gigabyte      | B450 AORUS M                | Desktop     | [7d4741d740](https://linux-hardware.org/?probe=7d4741d740) | Nov 17, 2018 |
| MSI           | P67A-S40                    | Desktop     | [4104f2eabe](https://linux-hardware.org/?probe=4104f2eabe) | Nov 12, 2018 |
| Sony          | VGN-N50HB                   | Notebook    | [8938dd9a9e](https://linux-hardware.org/?probe=8938dd9a9e) | Nov 11, 2018 |
| ASUSTek       | X551MA                      | Notebook    | [5806ab1f9f](https://linux-hardware.org/?probe=5806ab1f9f) | Oct 24, 2018 |
| Dell          | Latitude E6500              | Notebook    | [d3c051f562](https://linux-hardware.org/?probe=d3c051f562) | Feb 26, 2018 |
| Dell          | 0WJ771                      | Desktop     | [1a6e39d574](https://linux-hardware.org/?probe=1a6e39d574) | Dec 07, 2017 |
| ASRock        | 990FX Extreme4              | Desktop     | [b1702d4023](https://linux-hardware.org/?probe=b1702d4023) | Apr 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 208       | 22.34%  |
| Ubuntu 18.04        | 112       | 12.03%  |
| OpenMandriva 4.3    | 42        | 4.51%   |
| OpenMandriva 4.2    | 35        | 3.76%   |
| Debian 11           | 26        | 2.79%   |
| Xubuntu 20.04       | 25        | 2.69%   |
| Ubuntu 22.04        | 21        | 2.26%   |
| Arch                | 20        | 2.15%   |
| BlackPanther 18.1   | 18        | 1.93%   |
| Xubuntu 18.04       | 17        | 1.83%   |
| Ubuntu 21.04        | 17        | 1.83%   |
| Ubuntu 20.10        | 17        | 1.83%   |
| Ubuntu 19.04        | 14        | 1.5%    |
| Ubuntu 21.10        | 13        | 1.4%    |
| Ubuntu 16.04        | 12        | 1.29%   |
| Linux Mint 19.3     | 12        | 1.29%   |
| Zorin 16            | 11        | 1.18%   |
| Arch Rolling        | 11        | 1.18%   |
| Zorin 15            | 10        | 1.07%   |
| Manjaro             | 10        | 1.07%   |
| Ubuntu 19.10        | 9         | 0.97%   |
| KDE neon 20.04      | 9         | 0.97%   |
| Fedora 34           | 9         | 0.97%   |
| Fedora 32           | 9         | 0.97%   |
| Pop!_OS 22.04       | 8         | 0.86%   |
| Pop!_OS 21.04       | 8         | 0.86%   |
| Pop!_OS 20.10       | 8         | 0.86%   |
| OpenMandriva 4.50   | 8         | 0.86%   |
| Linux Mint 20.3     | 8         | 0.86%   |
| Gentoo 2.7          | 7         | 0.75%   |
| Fedora 35           | 7         | 0.75%   |
| Fedora 33           | 7         | 0.75%   |
| ArcoLinux Rolling   | 7         | 0.75%   |
| Pop!_OS 21.10       | 6         | 0.64%   |
| Pop!_OS 20.04       | 6         | 0.64%   |
| OpenMandriva 4.90   | 6         | 0.64%   |
| Linux Mint 20.2     | 6         | 0.64%   |
| Linux Mint 20       | 6         | 0.64%   |
| Fedora 36           | 6         | 0.64%   |
| ROSA R11            | 5         | 0.54%   |
| Lubuntu 20.04       | 5         | 0.54%   |
| Kubuntu 20.04       | 5         | 0.54%   |
| Fedora 31           | 5         | 0.54%   |
| Debian 10           | 5         | 0.54%   |
| Ubuntu Budgie 20.04 | 4         | 0.43%   |
| ROSA R10            | 4         | 0.43%   |
| Elementary 6.1      | 4         | 0.43%   |
| Debian Unstable     | 4         | 0.43%   |
| Debian Testing      | 4         | 0.43%   |
| Ubuntu 18.10        | 3         | 0.32%   |
| Slackware 15.0      | 3         | 0.32%   |
| Peppermint 10       | 3         | 0.32%   |
| openSUSE Leap-15.2  | 3         | 0.32%   |
| Fedora 30           | 3         | 0.32%   |
| CentOS 7            | 3         | 0.32%   |
| Xubuntu 22.04       | 2         | 0.21%   |
| Ubuntu MATE 20.04   | 2         | 0.21%   |
| Ubuntu Budgie 21.04 | 2         | 0.21%   |
| Slackware 14.2+     | 2         | 0.21%   |
| ROSA R11.1          | 2         | 0.21%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 414       | 46.62%  |
| OpenMandriva  | 89        | 10.02%  |
| Xubuntu       | 41        | 4.62%   |
| Debian        | 38        | 4.28%   |
| Linux Mint    | 37        | 4.17%   |
| Fedora        | 37        | 4.17%   |
| Pop!_OS       | 33        | 3.72%   |
| Arch          | 31        | 3.49%   |
| Zorin         | 22        | 2.48%   |
| Manjaro       | 20        | 2.25%   |
| BlackPanther  | 18        | 2.03%   |
| ROSA          | 11        | 1.24%   |
| KDE neon      | 9         | 1.01%   |
| Gentoo        | 9         | 1.01%   |
| Kubuntu       | 7         | 0.79%   |
| ArcoLinux     | 7         | 0.79%   |
| openSUSE      | 6         | 0.68%   |
| Lubuntu       | 6         | 0.68%   |
| Ubuntu Budgie | 5         | 0.56%   |
| Slackware     | 5         | 0.56%   |
| Elementary    | 5         | 0.56%   |
| Kali          | 4         | 0.45%   |
| Endless       | 4         | 0.45%   |
| Ubuntu MATE   | 3         | 0.34%   |
| Peppermint    | 3         | 0.34%   |
| CentOS        | 3         | 0.34%   |
| antiX         | 3         | 0.34%   |
| RHEL          | 2         | 0.23%   |
| LMDE          | 2         | 0.23%   |
| Deepin        | 2         | 0.23%   |
| Clear Linux   | 2         | 0.23%   |
| SystemRescue  | 1         | 0.11%   |
| SteamOS       | 1         | 0.11%   |
| Sparky        | 1         | 0.11%   |
| Solus         | 1         | 0.11%   |
| Rocky Linux   | 1         | 0.11%   |
| Raspbian      | 1         | 0.11%   |
| Plamo         | 1         | 0.11%   |
| Linux Lite    | 1         | 0.11%   |
| Feren OS      | 1         | 0.11%   |
| Artix         | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 41        | 3.96%   |
| 5.10.14-desktop-1omv4002 | 33        | 3.19%   |
| 5.4.0-42-generic         | 24        | 2.32%   |
| 5.4.0-52-generic         | 18        | 1.74%   |
| 5.4.0-58-generic         | 17        | 1.64%   |
| 4.18.16-desktop-1bP      | 15        | 1.45%   |
| 5.4.0-40-generic         | 13        | 1.26%   |
| 5.4.0-33-generic         | 12        | 1.16%   |
| 5.4.0-48-generic         | 10        | 0.97%   |
| 5.4.0-37-generic         | 10        | 0.97%   |
| 5.8.0-48-generic         | 9         | 0.87%   |
| 5.8.0-43-generic         | 8         | 0.77%   |
| 5.4.0-54-generic         | 8         | 0.77%   |
| 5.4.0-31-generic         | 8         | 0.77%   |
| 5.11.0-38-generic        | 8         | 0.77%   |
| 5.8.0-50-generic         | 7         | 0.68%   |
| 5.4.0-29-generic         | 7         | 0.68%   |
| 5.13.0-40-generic        | 7         | 0.68%   |
| 5.13.0-30-generic        | 7         | 0.68%   |
| 5.12.4-desktop-1omv4050  | 7         | 0.68%   |
| 5.11.0-37-generic        | 7         | 0.68%   |
| 5.11.0-27-generic        | 7         | 0.68%   |
| 5.0.0-37-generic         | 7         | 0.68%   |
| 5.0.0-29-generic         | 7         | 0.68%   |
| 5.8.0-59-generic         | 6         | 0.58%   |
| 5.4.0-51-generic         | 6         | 0.58%   |
| 5.4.0-47-generic         | 6         | 0.58%   |
| 5.4.0-39-generic         | 6         | 0.58%   |
| 5.3.0-40-generic         | 6         | 0.58%   |
| 5.3.0-28-generic         | 6         | 0.58%   |
| 5.13.0-39-generic        | 6         | 0.58%   |
| 5.13.0-27-generic        | 6         | 0.58%   |
| 5.11.0-41-generic        | 6         | 0.58%   |
| 5.11.0-25-generic        | 6         | 0.58%   |
| 5.0.0-25-generic         | 6         | 0.58%   |
| 5.8.0-7642-generic       | 5         | 0.48%   |
| 5.8.0-41-generic         | 5         | 0.48%   |
| 5.4.0-72-generic         | 5         | 0.48%   |
| 5.4.0-66-generic         | 5         | 0.48%   |
| 5.3.0-51-generic         | 5         | 0.48%   |
| 5.13.0-28-generic        | 5         | 0.48%   |
| 5.10.0-8-amd64           | 5         | 0.48%   |
| 4.18.0-25-generic        | 5         | 0.48%   |
| 4.15.0-72-generic        | 5         | 0.48%   |
| 4.15.0-55-generic        | 5         | 0.48%   |
| 4.15.0-48-generic        | 5         | 0.48%   |
| 5.8.0-55-generic         | 4         | 0.39%   |
| 5.6.14-desktop-2bP       | 4         | 0.39%   |
| 5.4.0-65-generic         | 4         | 0.39%   |
| 5.4.0-56-generic         | 4         | 0.39%   |
| 5.4.0-45-generic         | 4         | 0.39%   |
| 5.4.0-26-generic         | 4         | 0.39%   |
| 5.15.0-46-generic        | 4         | 0.39%   |
| 5.15.0-41-generic        | 4         | 0.39%   |
| 5.15.0-27-generic        | 4         | 0.39%   |
| 5.13.0-7614-generic      | 4         | 0.39%   |
| 5.11.0-40-generic        | 4         | 0.39%   |
| 5.10.0-9-amd64           | 4         | 0.39%   |
| 5.10.0-16-amd64          | 4         | 0.39%   |
| 5.10.0-13-amd64          | 4         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 217       | 22.35%  |
| 4.15.0  | 87        | 8.96%   |
| 5.8.0   | 72        | 7.42%   |
| 5.11.0  | 61        | 6.28%   |
| 5.13.0  | 54        | 5.56%   |
| 5.16.7  | 42        | 4.33%   |
| 5.3.0   | 41        | 4.22%   |
| 5.0.0   | 36        | 3.71%   |
| 5.10.14 | 34        | 3.5%    |
| 5.15.0  | 29        | 2.99%   |
| 5.10.0  | 28        | 2.88%   |
| 4.18.16 | 15        | 1.54%   |
| 4.18.0  | 14        | 1.44%   |
| 5.12.4  | 8         | 0.82%   |
| 4.4.0   | 8         | 0.82%   |
| 4.19.0  | 7         | 0.72%   |
| 5.9.0   | 4         | 0.41%   |
| 5.6.14  | 4         | 0.41%   |
| 5.3.18  | 4         | 0.41%   |
| 5.18.0  | 4         | 0.41%   |
| 5.16.11 | 4         | 0.41%   |
| 5.14.0  | 4         | 0.41%   |
| 4.9.60  | 4         | 0.41%   |
| 5.8.13  | 3         | 0.31%   |
| 5.19.1  | 3         | 0.31%   |
| 5.19.0  | 3         | 0.31%   |
| 5.18.5  | 3         | 0.31%   |
| 5.18.13 | 3         | 0.31%   |
| 5.18.12 | 3         | 0.31%   |
| 5.16.19 | 3         | 0.31%   |
| 5.13.19 | 3         | 0.31%   |
| 5.9.16  | 2         | 0.21%   |
| 5.9.12  | 2         | 0.21%   |
| 5.8.16  | 2         | 0.21%   |
| 5.8.11  | 2         | 0.21%   |
| 5.7.9   | 2         | 0.21%   |
| 5.6.18  | 2         | 0.21%   |
| 5.6.13  | 2         | 0.21%   |
| 5.18.10 | 2         | 0.21%   |
| 5.17.5  | 2         | 0.21%   |
| 5.17.15 | 2         | 0.21%   |
| 5.17.13 | 2         | 0.21%   |
| 5.16.9  | 2         | 0.21%   |
| 5.16.18 | 2         | 0.21%   |
| 5.16.13 | 2         | 0.21%   |
| 5.16.0  | 2         | 0.21%   |
| 5.15.8  | 2         | 0.21%   |
| 5.15.59 | 2         | 0.21%   |
| 5.15.5  | 2         | 0.21%   |
| 5.15.2  | 2         | 0.21%   |
| 5.15.15 | 2         | 0.21%   |
| 5.15.10 | 2         | 0.21%   |
| 5.14.10 | 2         | 0.21%   |
| 5.13.6  | 2         | 0.21%   |
| 5.13.10 | 2         | 0.21%   |
| 5.12.12 | 2         | 0.21%   |
| 5.12.0  | 2         | 0.21%   |
| 5.11.17 | 2         | 0.21%   |
| 5.10.61 | 2         | 0.21%   |
| 5.10.4  | 2         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 225       | 23.39%  |
| 4.15    | 87        | 9.04%   |
| 5.8     | 83        | 8.63%   |
| 5.10    | 82        | 8.52%   |
| 5.13    | 69        | 7.17%   |
| 5.11    | 66        | 6.86%   |
| 5.16    | 60        | 6.24%   |
| 5.15    | 47        | 4.89%   |
| 5.3     | 45        | 4.68%   |
| 5.0     | 39        | 4.05%   |
| 4.18    | 29        | 3.01%   |
| 5.18    | 18        | 1.87%   |
| 5.12    | 16        | 1.66%   |
| 5.14    | 14        | 1.46%   |
| 5.9     | 12        | 1.25%   |
| 5.6     | 12        | 1.25%   |
| 5.17    | 10        | 1.04%   |
| 4.19    | 10        | 1.04%   |
| 4.9     | 8         | 0.83%   |
| 4.4     | 8         | 0.83%   |
| 5.19    | 7         | 0.73%   |
| 5.7     | 6         | 0.62%   |
| 5.5     | 4         | 0.42%   |
| 5.2     | 3         | 0.31%   |
| 3.10    | 2         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 821       | 94.37%  |
| i686    | 36        | 4.14%   |
| aarch64 | 11        | 1.26%   |
| armv7l  | 2         | 0.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 415       | 46.63%  |
| KDE5                     | 149       | 16.74%  |
| Unknown                  | 125       | 14.04%  |
| XFCE                     | 73        | 8.2%    |
| X-Cinnamon               | 30        | 3.37%   |
| KDE                      | 15        | 1.69%   |
| MATE                     | 14        | 1.57%   |
| LXDE                     | 9         | 1.01%   |
| Unity                    | 8         | 0.9%    |
| Budgie                   | 8         | 0.9%    |
| LXQt                     | 7         | 0.79%   |
| Cinnamon                 | 6         | 0.67%   |
| Pantheon                 | 5         | 0.56%   |
| KDE4                     | 5         | 0.56%   |
| Deepin                   | 4         | 0.45%   |
| awesome                  | 3         | 0.34%   |
| XSession                 | 2         | 0.22%   |
| sway                     | 2         | 0.22%   |
| icewm                    | 2         | 0.22%   |
| i3                       | 2         | 0.22%   |
| xmonad                   | 1         | 0.11%   |
| qtile                    | 1         | 0.11%   |
| Openbox                  | 1         | 0.11%   |
| GNOME Flashback          | 1         | 0.11%   |
| GNOME Classic            | 1         | 0.11%   |
| /usr/bin/openbox-session | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 696       | 78.64%  |
| Wayland | 96        | 10.85%  |
| Unknown | 73        | 8.25%   |
| Tty     | 20        | 2.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 501       | 55.79%  |
| SDDM    | 147       | 16.37%  |
| GDM     | 89        | 9.91%   |
| GDM3    | 75        | 8.35%   |
| LightDM | 48        | 5.35%   |
| TDM     | 23        | 2.56%   |
| XDM     | 4         | 0.45%   |
| KDM     | 4         | 0.45%   |
| LXDM    | 3         | 0.33%   |
| NODM    | 2         | 0.22%   |
| SLiM    | 1         | 0.11%   |
| GREETD  | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ja_JP       | 417       | 46.91%  |
| en_US       | 248       | 27.9%   |
| Unknown     | 133       | 14.96%  |
| pt_BR       | 25        | 2.81%   |
| en_GB       | 17        | 1.91%   |
| zh_CN       | 15        | 1.69%   |
| C           | 9         | 1.01%   |
| fr_FR       | 3         | 0.34%   |
| en_AU       | 3         | 0.34%   |
| zh_TW       | 2         | 0.22%   |
| sk_SK       | 2         | 0.22%   |
| ru_RU       | 2         | 0.22%   |
| sv_SE       | 1         | 0.11%   |
| pl_PL       | 1         | 0.11%   |
| nb_NO       | 1         | 0.11%   |
| ja_JP.utf-8 | 1         | 0.11%   |
| it_IT       | 1         | 0.11%   |
| fi_FI       | 1         | 0.11%   |
| es_ES       | 1         | 0.11%   |
| en_SG       | 1         | 0.11%   |
| en_PH       | 1         | 0.11%   |
| en_NL       | 1         | 0.11%   |
| en_AG       | 1         | 0.11%   |
| de_DE       | 1         | 0.11%   |
| af_ZA       | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 495       | 56.19%  |
| EFI  | 386       | 43.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 698       | 79.5%   |
| Overlay | 83        | 9.45%   |
| Btrfs   | 49        | 5.58%   |
| Unknown | 22        | 2.51%   |
| Xfs     | 14        | 1.59%   |
| Zfs     | 7         | 0.8%    |
| F2fs    | 2         | 0.23%   |
| Ntfs    | 1         | 0.11%   |
| Jfs     | 1         | 0.11%   |
| Ext3    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 548       | 62.41%  |
| GPT     | 251       | 28.59%  |
| MBR     | 79        | 9%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 708       | 79.64%  |
| Yes       | 181       | 20.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 628       | 71.12%  |
| Yes       | 255       | 28.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 128       | 14.76%  |
| Lenovo                  | 83        | 9.57%   |
| ASRock                  | 79        | 9.11%   |
| Dell                    | 71        | 8.19%   |
| Hewlett-Packard         | 70        | 8.07%   |
| Gigabyte Technology     | 51        | 5.88%   |
| Toshiba                 | 40        | 4.61%   |
| MSI                     | 38        | 4.38%   |
| Fujitsu                 | 36        | 4.15%   |
| NEC Computers           | 32        | 3.69%   |
| Apple                   | 25        | 2.88%   |
| Intel                   | 24        | 2.77%   |
| MouseComputer           | 17        | 1.96%   |
| Acer                    | 17        | 1.96%   |
| Sony                    | 16        | 1.85%   |
| Panasonic               | 12        | 1.38%   |
| Raspberry Pi Foundation | 11        | 1.27%   |
| Unknown                 | 10        | 1.15%   |
| Biostar                 | 8         | 0.92%   |
| Gateway                 | 7         | 0.81%   |
| ECS                     | 7         | 0.81%   |
| Supermicro              | 5         | 0.58%   |
| Novastar                | 4         | 0.46%   |
| MCJ                     | 4         | 0.46%   |
| Alienware               | 4         | 0.46%   |
| UNITCOM                 | 3         | 0.35%   |
| Teclast                 | 3         | 0.35%   |
| Shuttle                 | 3         | 0.35%   |
| Pegatron                | 3         | 0.35%   |
| HUAWEI                  | 3         | 0.35%   |
| Foxconn                 | 3         | 0.35%   |
| EPSON DIRECT            | 3         | 0.35%   |
| Dynabook                | 3         | 0.35%   |
| Wistron                 | 2         | 0.23%   |
| Timi                    | 2         | 0.23%   |
| Thirdwave               | 2         | 0.23%   |
| System76                | 2         | 0.23%   |
| SLIMBOOK                | 2         | 0.23%   |
| Samsung Electronics     | 2         | 0.23%   |
| Onkyo                   | 2         | 0.23%   |
| Notebook                | 2         | 0.23%   |
| Microsoft               | 2         | 0.23%   |
| XFX                     | 1         | 0.12%   |
| WinFast                 | 1         | 0.12%   |
| TUXEDO                  | 1         | 0.12%   |
| THD                     | 1         | 0.12%   |
| sunxi                   | 1         | 0.12%   |
| Sharp                   | 1         | 0.12%   |
| Razer                   | 1         | 0.12%   |
| R.W.C                   | 1         | 0.12%   |
| Purism                  | 1         | 0.12%   |
| Nvidia                  | 1         | 0.12%   |
| Maibenben               | 1         | 0.12%   |
| KOUZIRO                 | 1         | 0.12%   |
| Jumper                  | 1         | 0.12%   |
| IP3 Tech                | 1         | 0.12%   |
| IBM                     | 1         | 0.12%   |
| HASEE Computer          | 1         | 0.12%   |
| Hampoo                  | 1         | 0.12%   |
| Google                  | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 1.15%   |
| ASUS All Series                            | 9         | 1.04%   |
| RPi Raspberry Pi                           | 6         | 0.69%   |
| Toshiba dynabook Satellite B552/G          | 5         | 0.58%   |
| Novastar KL55                              | 4         | 0.46%   |
| ASRock Z87 Killer                          | 4         | 0.46%   |
| ASRock B450M Pro4                          | 4         | 0.46%   |
| Apple MacBookPro9,2                        | 4         | 0.46%   |
| Toshiba dynabook T653/46JR                 | 3         | 0.35%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 3         | 0.35%   |
| MSI MS-7A40                                | 3         | 0.35%   |
| Lenovo G570 4334                           | 3         | 0.35%   |
| Intel NUC10i7FNH                           | 3         | 0.35%   |
| Intel NUC10i5FNH                           | 3         | 0.35%   |
| HP ProDesk 600 G1 SFF                      | 3         | 0.35%   |
| ECS G31T-M                                 | 3         | 0.35%   |
| Dell Precision WorkStation T3500           | 3         | 0.35%   |
| ASUS P7H55-M                               | 3         | 0.35%   |
| ASRock Prime Series                        | 3         | 0.35%   |
| ASRock J5005-ITX                           | 3         | 0.35%   |
| ASRock A300M-STX                           | 3         | 0.35%   |
| Toshiba dynabook R73/BN                    | 2         | 0.23%   |
| Supermicro Super Server                    | 2         | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 2         | 0.23%   |
| Panasonic CF-S10EYADR                      | 2         | 0.23%   |
| Onkyo ONKYOPC                              | 2         | 0.23%   |
| NEC Computers Express5800/S70 [N8100-9021] | 2         | 0.23%   |
| MSI MS-7D16                                | 2         | 0.23%   |
| MSI MS-7C94                                | 2         | 0.23%   |
| MSI MS-7C37                                | 2         | 0.23%   |
| MSI MS-7C35                                | 2         | 0.23%   |
| MSI MS-7C02                                | 2         | 0.23%   |
| MSI MS-7A72                                | 2         | 0.23%   |
| MSI MS-7865                                | 2         | 0.23%   |
| MouseComputer B360M                        | 2         | 0.23%   |
| Lenovo ThinkPad X230 2325SSF               | 2         | 0.23%   |
| Intel NUC12DCMi9                           | 2         | 0.23%   |
| HP Z620 Workstation                        | 2         | 0.23%   |
| HP ProDesk 405 G6 Desktop Mini PC          | 2         | 0.23%   |
| HP ProBook 6570b                           | 2         | 0.23%   |
| HP ProBook 6560b                           | 2         | 0.23%   |
| HP ProBook 6550b                           | 2         | 0.23%   |
| HP Pavilion dv4                            | 2         | 0.23%   |
| HP Notebook                                | 2         | 0.23%   |
| HP Laptop 15-db0xxx                        | 2         | 0.23%   |
| HP Compaq dc7700p Small Form Factor        | 2         | 0.23%   |
| Gigabyte Z77X-UD3H                         | 2         | 0.23%   |
| Gigabyte Z170X-Gaming 3                    | 2         | 0.23%   |
| Gigabyte H67A-D3H-B3                       | 2         | 0.23%   |
| Gigabyte GA-MA69G-S3H                      | 2         | 0.23%   |
| Gigabyte G33-DS3R                          | 2         | 0.23%   |
| Gigabyte EP45-UD3R                         | 2         | 0.23%   |
| Gigabyte 970A-D3P                          | 2         | 0.23%   |
| Gateway NE56R                              | 2         | 0.23%   |
| Fujitsu PRIMERGY TX1310 M1                 | 2         | 0.23%   |
| Dell XPS 15 9500                           | 2         | 0.23%   |
| Dell XPS 13 9360                           | 2         | 0.23%   |
| Dell OptiPlex 3020                         | 2         | 0.23%   |
| Dell Latitude E6320                        | 2         | 0.23%   |
| Dell Inspiron 1545                         | 2         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 53        | 6.11%   |
| Toshiba dynabook          | 37        | 4.27%   |
| Dell Inspiron             | 21        | 2.42%   |
| ASUS PRIME                | 15        | 1.73%   |
| HP ProBook                | 14        | 1.61%   |
| ASUS ROG                  | 14        | 1.61%   |
| ASUS TUF                  | 13        | 1.5%    |
| Acer Aspire               | 12        | 1.38%   |
| RPi Raspberry             | 11        | 1.27%   |
| Dell XPS                  | 11        | 1.27%   |
| Dell Latitude             | 11        | 1.27%   |
| Unknown                   | 10        | 1.15%   |
| ASUS All                  | 9         | 1.04%   |
| HP Compaq                 | 8         | 0.92%   |
| HP Pavilion               | 7         | 0.81%   |
| Dell Vostro               | 7         | 0.81%   |
| HP ProDesk                | 6         | 0.69%   |
| Dell OptiPlex             | 6         | 0.69%   |
| HP ENVY                   | 5         | 0.58%   |
| HP EliteBook              | 5         | 0.58%   |
| Fujitsu PRIMERGY          | 5         | 0.58%   |
| Dell Precision            | 5         | 0.58%   |
| ASUS VivoBook             | 5         | 0.58%   |
| ASUS P8Z77-V              | 5         | 0.58%   |
| ASRock Z87                | 5         | 0.58%   |
| ASRock B450               | 5         | 0.58%   |
| Novastar KL55             | 4         | 0.46%   |
| Lenovo ThinkCentre        | 4         | 0.46%   |
| Lenovo ThinkBook          | 4         | 0.46%   |
| Lenovo IdeaPad            | 4         | 0.46%   |
| Gigabyte Z390             | 4         | 0.46%   |
| ASRock Prime              | 4         | 0.46%   |
| ASRock B450M              | 4         | 0.46%   |
| Apple MacBookPro9         | 4         | 0.46%   |
| MSI MS-7A40               | 3         | 0.35%   |
| Lenovo Yoga               | 3         | 0.35%   |
| Lenovo G570               | 3         | 0.35%   |
| Intel NUC10i7FNH          | 3         | 0.35%   |
| Intel NUC10i5FNH          | 3         | 0.35%   |
| HP Spectre                | 3         | 0.35%   |
| HP Laptop                 | 3         | 0.35%   |
| EPSON DIRECT Endeavor     | 3         | 0.35%   |
| ECS G31T-M                | 3         | 0.35%   |
| Dell G3                   | 3         | 0.35%   |
| ASUS P7H55-M              | 3         | 0.35%   |
| ASRock X370               | 3         | 0.35%   |
| ASRock J5005-ITX          | 3         | 0.35%   |
| ASRock A300M-STX          | 3         | 0.35%   |
| Toshiba PORTEGE           | 2         | 0.23%   |
| Timi RedmiBook            | 2         | 0.23%   |
| Supermicro Super          | 2         | 0.23%   |
| Panasonic CF-S10EYADR     | 2         | 0.23%   |
| Onkyo ONKYOPC             | 2         | 0.23%   |
| NEC Computers Express5800 | 2         | 0.23%   |
| MSI MS-7D16               | 2         | 0.23%   |
| MSI MS-7C94               | 2         | 0.23%   |
| MSI MS-7C37               | 2         | 0.23%   |
| MSI MS-7C35               | 2         | 0.23%   |
| MSI MS-7C02               | 2         | 0.23%   |
| MSI MS-7A72               | 2         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 98        | 11.3%   |
| 2018    | 94        | 10.84%  |
| 2020    | 78        | 9%      |
| 2019    | 62        | 7.15%   |
| 2013    | 62        | 7.15%   |
| 2011    | 59        | 6.81%   |
| 2010    | 53        | 6.11%   |
| 2009    | 51        | 5.88%   |
| 2016    | 47        | 5.42%   |
| 2021    | 45        | 5.19%   |
| 2015    | 40        | 4.61%   |
| 2014    | 35        | 4.04%   |
| 2008    | 35        | 4.04%   |
| 2017    | 34        | 3.92%   |
| 2007    | 33        | 3.81%   |
| 2006    | 14        | 1.61%   |
| Unknown | 11        | 1.27%   |
| 2022    | 9         | 1.04%   |
| 2005    | 6         | 0.69%   |
| 2003    | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 398       | 45.91%  |
| Desktop        | 389       | 44.87%  |
| Mini pc        | 21        | 2.42%   |
| All in one     | 15        | 1.73%   |
| System on chip | 13        | 1.5%    |
| Server         | 12        | 1.38%   |
| Convertible    | 10        | 1.15%   |
| Tablet         | 9         | 1.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 808       | 92.45%  |
| Enabled  | 66        | 7.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 863       | 99.54%  |
| Yes  | 4         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 183       | 20.75%  |
| 4.01-8.0        | 182       | 20.63%  |
| 8.01-16.0       | 160       | 18.14%  |
| 16.01-24.0      | 154       | 17.46%  |
| 32.01-64.0      | 83        | 9.41%   |
| 1.01-2.0        | 46        | 5.22%   |
| 64.01-256.0     | 31        | 3.51%   |
| 24.01-32.0      | 21        | 2.38%   |
| 2.01-3.0        | 14        | 1.59%   |
| 0.51-1.0        | 6         | 0.68%   |
| More than 256.0 | 1         | 0.11%   |
| 0.01-0.5        | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 400       | 41.67%  |
| 2.01-3.0   | 211       | 21.98%  |
| 0.51-1.0   | 104       | 10.83%  |
| 3.01-4.0   | 93        | 9.69%   |
| 4.01-8.0   | 90        | 9.38%   |
| 8.01-16.0  | 31        | 3.23%   |
| 0.01-0.5   | 18        | 1.88%   |
| 16.01-24.0 | 9         | 0.94%   |
| 24.01-32.0 | 3         | 0.31%   |
| 32.01-64.0 | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 529       | 59.3%   |
| 2      | 230       | 25.78%  |
| 3      | 65        | 7.29%   |
| 4      | 32        | 3.59%   |
| 5      | 14        | 1.57%   |
| 0      | 9         | 1.01%   |
| 6      | 6         | 0.67%   |
| 7      | 5         | 0.56%   |
| 11     | 1         | 0.11%   |
| 9      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 445       | 50.86%  |
| Yes       | 430       | 49.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 771       | 88.82%  |
| No        | 97        | 11.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 569       | 65.4%   |
| No        | 301       | 34.6%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 463       | 52.73%  |
| Yes       | 415       | 47.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Japan   | 867       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Computers | Percent |
|-------------|-----------|---------|
| Tokyo       | 69        | 7.48%   |
| Yokohama    | 54        | 5.85%   |
| Osaka       | 48        | 5.2%    |
| Nagoya      | 26        | 2.82%   |
| Shinjuku    | 23        | 2.49%   |
| Minato-ku   | 21        | 2.28%   |
| Saitama     | 18        | 1.95%   |
| Shibuya     | 16        | 1.73%   |
| Setagaya-ku | 14        | 1.52%   |
| Sapporo     | 14        | 1.52%   |
| Honcho      | 13        | 1.41%   |
| Niigata     | 12        | 1.3%    |
| Kobe        | 12        | 1.3%    |
| Fukuoka     | 11        | 1.19%   |
| Chiyoda     | 11        | 1.19%   |
| Kyoto       | 10        | 1.08%   |
| Tsukuba     | 9         | 0.98%   |
| Okayama     | 7         | 0.76%   |
| Nagasaki    | 7         | 0.76%   |
| Morioka     | 7         | 0.76%   |
| Miyazaki    | 7         | 0.76%   |
| Matsudo     | 7         | 0.76%   |
| Koto        | 7         | 0.76%   |
| Kitakyushu  | 7         | 0.76%   |
| Ichikawa    | 7         | 0.76%   |
| Himeji      | 7         | 0.76%   |
| Chiba       | 7         | 0.76%   |
| Shinagawa   | 6         | 0.65%   |
| Ōtsu       | 6         | 0.65%   |
| Kagoshima   | 6         | 0.65%   |
| Bunkyo-ku   | 6         | 0.65%   |
| Adachi      | 6         | 0.65%   |
| Utsunomiya  | 5         | 0.54%   |
| Takamatsu   | 5         | 0.54%   |
| Ōta-ku     | 5         | 0.54%   |
| Mito        | 5         | 0.54%   |
| Meguro-ku   | 5         | 0.54%   |
| Kumamoto    | 5         | 0.54%   |
| Kochi       | 5         | 0.54%   |
| Kawasaki    | 5         | 0.54%   |
| Kanazawa    | 5         | 0.54%   |
| Hiratsuka   | 5         | 0.54%   |
| Gifu City   | 5         | 0.54%   |
| Yamaguchi   | 4         | 0.43%   |
| Yamagata    | 4         | 0.43%   |
| Toyokawa    | 4         | 0.43%   |
| Toyama      | 4         | 0.43%   |
| Suginami-ku | 4         | 0.43%   |
| Soka Shi    | 4         | 0.43%   |
| Shizuoka    | 4         | 0.43%   |
| Sendai      | 4         | 0.43%   |
| Okinawa     | 4         | 0.43%   |
| Okazaki     | 4         | 0.43%   |
| Nakano      | 4         | 0.43%   |
| Naha        | 4         | 0.43%   |
| Nagano      | 4         | 0.43%   |
| Minatomirai | 4         | 0.43%   |
| Maebashi    | 4         | 0.43%   |
| Kawaguchi   | 4         | 0.43%   |
| Karasawa    | 4         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 192       | 289    | 15.25%  |
| WDC                         | 184       | 282    | 14.61%  |
| Samsung Electronics         | 128       | 181    | 10.17%  |
| Toshiba                     | 102       | 129    | 8.1%    |
| Hitachi                     | 73        | 90     | 5.8%    |
| Crucial                     | 70        | 87     | 5.56%   |
| Unknown                     | 59        | 75     | 4.69%   |
| SanDisk                     | 58        | 77     | 4.61%   |
| Intel                       | 46        | 63     | 3.65%   |
| Kingston                    | 27        | 31     | 2.14%   |
| A-DATA Technology           | 27        | 31     | 2.14%   |
| SPCC                        | 22        | 29     | 1.75%   |
| SK hynix                    | 18        | 18     | 1.43%   |
| HGST                        | 18        | 21     | 1.43%   |
| Apple                       | 16        | 19     | 1.27%   |
| Micron Technology           | 14        | 23     | 1.11%   |
| Phison                      | 13        | 18     | 1.03%   |
| Transcend                   | 12        | 16     | 0.95%   |
| Plextor                     | 11        | 15     | 0.87%   |
| China                       | 10        | 13     | 0.79%   |
| Fujitsu                     | 8         | 9      | 0.64%   |
| OCZ                         | 7         | 7      | 0.56%   |
| KIOXIA                      | 7         | 10     | 0.56%   |
| Zheino                      | 6         | 7      | 0.48%   |
| Silicon Motion              | 6         | 13     | 0.48%   |
| Micron/Crucial Technology   | 6         | 7      | 0.48%   |
| Green House                 | 6         | 8      | 0.48%   |
| SUNEAST                     | 5         | 6      | 0.4%    |
| Patriot                     | 5         | 6      | 0.4%    |
| KIOXIA-EXCERIA              | 5         | 6      | 0.4%    |
| Dogfish                     | 5         | 5      | 0.4%    |
| Unknown                     | 5         | 5      | 0.4%    |
| Teclast                     | 4         | 4      | 0.32%   |
| Maxtor                      | 4         | 6      | 0.32%   |
| JMicron Technology          | 4         | 4      | 0.32%   |
| Apacer                      | 4         | 6      | 0.32%   |
| Team                        | 3         | 4      | 0.24%   |
| KLEVV                       | 3         | 8      | 0.24%   |
| Hewlett-Packard             | 3         | 3      | 0.24%   |
| TCSUNBOW                    | 2         | 2      | 0.16%   |
| Ramaxel Technology          | 2         | 2      | 0.16%   |
| QC-FT-D                     | 2         | 2      | 0.16%   |
| PNY                         | 2         | 2      | 0.16%   |
| Netac                       | 2         | 2      | 0.16%   |
| MARVELL                     | 2         | 4      | 0.16%   |
| MARSHAL                     | 2         | 3      | 0.16%   |
| Lexar                       | 2         | 2      | 0.16%   |
| Kingmax                     | 2         | 2      | 0.16%   |
| BUFFALO                     | 2         | 2      | 0.16%   |
| Biostar                     | 2         | 2      | 0.16%   |
| ASMT                        | 2         | 3      | 0.16%   |
| AEGO                        | 2         | 2      | 0.16%   |
| Yangtze Memory Technologies | 1         | 1      | 0.08%   |
| XSTAR                       | 1         | 1      | 0.08%   |
| SATA3 51                    | 1         | 2      | 0.08%   |
| SABRENT                     | 1         | 2      | 0.08%   |
| Realtek Semiconductor       | 1         | 1      | 0.08%   |
| Quantum                     | 1         | 1      | 0.08%   |
| Palit                       | 1         | 1      | 0.08%   |
| Oyen                        | 1         | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Crucial CT500MX500SSD1 500GB         | 17        | 1.23%   |
| Toshiba DT01ACA100 1TB               | 16        | 1.16%   |
| Unknown MMC Card  64GB               | 14        | 1.01%   |
| Crucial CT240BX500SSD1 240GB         | 11        | 0.79%   |
| Unknown MMC Card  32GB               | 10        | 0.72%   |
| Seagate ST3500418AS 500GB            | 8         | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB       | 8         | 0.58%   |
| Toshiba DT01ACA200 2TB               | 7         | 0.51%   |
| SPCC Solid State Disk 256GB          | 7         | 0.51%   |
| Seagate ST9500325AS 500GB            | 7         | 0.51%   |
| Seagate ST4000DM004-2CV104 4TB       | 7         | 0.51%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 6         | 0.43%   |
| WDC WD20EZRX-00DC0B0 2TB             | 6         | 0.43%   |
| Unknown MMC Card  128GB              | 6         | 0.43%   |
| Toshiba MQ01ABD100 1TB               | 6         | 0.43%   |
| Seagate ST500DM002-1BD142 500GB      | 6         | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB       | 6         | 0.43%   |
| Seagate ST2000DM006-2DM164 2TB       | 6         | 0.43%   |
| Seagate ST2000DM005-2CW102 2TB       | 6         | 0.43%   |
| Intel NVMe SSD Drive 512GB           | 6         | 0.43%   |
| Crucial CT525MX300SSD1 528GB         | 6         | 0.43%   |
| Crucial CT120BX500SSD1 120GB         | 6         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 5         | 0.36%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.36%   |
| SPCC Solid State Disk 240GB          | 5         | 0.36%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB       | 5         | 0.36%   |
| Seagate Expansion 500GB              | 5         | 0.36%   |
| Samsung SSD 860 EVO 500GB            | 5         | 0.36%   |
| Samsung NVMe SSD Drive 256GB         | 5         | 0.36%   |
| Samsung NVMe SSD Drive 250GB         | 5         | 0.36%   |
| Samsung NVMe SSD Drive 1TB           | 5         | 0.36%   |
| Unknown                              | 5         | 0.36%   |
| WDC WD20EZAZ-00GGJB0 2TB             | 4         | 0.29%   |
| WDC WD10EZEX-00BN5A0 1TB             | 4         | 0.29%   |
| WDC WD10EADS-22M2B0 1TB              | 4         | 0.29%   |
| WDC WD10EADS-00L5B1 1TB              | 4         | 0.29%   |
| Seagate ST8000DM004-2CX188 8TB       | 4         | 0.29%   |
| Seagate ST2000DM001-1CH164 2TB       | 4         | 0.29%   |
| Seagate ST1000DM003-9YN162 1TB       | 4         | 0.29%   |
| SanDisk SD6SF1M128G1022I 128GB SSD   | 4         | 0.29%   |
| SanDisk Extreme SSD 500GB            | 4         | 0.29%   |
| Samsung SSD 970 EVO Plus 500GB       | 4         | 0.29%   |
| Samsung SSD 860 QVO 1TB              | 4         | 0.29%   |
| Samsung SSD 850 EVO 250GB            | 4         | 0.29%   |
| Samsung SSD 840 Series 120GB         | 4         | 0.29%   |
| Samsung SSD 750 EVO 250GB            | 4         | 0.29%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.29%   |
| Kingston SQ500S37240G 240GB SSD      | 4         | 0.29%   |
| Kingston RBUSNS4180S3256GJ 256GB SSD | 4         | 0.29%   |
| Hitachi HDS722020ALA330 2TB          | 4         | 0.29%   |
| Hitachi HDS721050CLA362 500GB        | 4         | 0.29%   |
| Hitachi HDS721010CLA332 1TB          | 4         | 0.29%   |
| HGST HTS545050A7E380 500GB           | 4         | 0.29%   |
| Crucial CT275MX300SSD1 275GB         | 4         | 0.29%   |
| Crucial CT250MX500SSD1 250GB         | 4         | 0.29%   |
| A-DATA SP900 256GB SSD               | 4         | 0.29%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 3         | 0.22%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 3         | 0.22%   |
| WDC WDS250G2B0A 250GB SSD            | 3         | 0.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 188       | 282    | 33.94%  |
| WDC                 | 147       | 215    | 26.53%  |
| Toshiba             | 84        | 104    | 15.16%  |
| Hitachi             | 72        | 89     | 13%     |
| HGST                | 18        | 21     | 3.25%   |
| Samsung Electronics | 17        | 20     | 3.07%   |
| Fujitsu             | 8         | 9      | 1.44%   |
| Maxtor              | 4         | 6      | 0.72%   |
| Unknown             | 3         | 3      | 0.54%   |
| QC-FT-D             | 2         | 2      | 0.36%   |
| MARVELL             | 2         | 4      | 0.36%   |
| ASMT                | 2         | 3      | 0.36%   |
| Apple               | 2         | 2      | 0.36%   |
| SABRENT             | 1         | 2      | 0.18%   |
| Quantum             | 1         | 1      | 0.18%   |
| MARSHAL             | 1         | 2      | 0.18%   |
| KESU                | 1         | 1      | 0.18%   |
| Hewlett-Packard     | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 68        | 84     | 15.35%  |
| Samsung Electronics | 67        | 90     | 15.12%  |
| SanDisk             | 39        | 50     | 8.8%    |
| WDC                 | 28        | 37     | 6.32%   |
| Intel               | 24        | 29     | 5.42%   |
| A-DATA Technology   | 24        | 28     | 5.42%   |
| SPCC                | 20        | 27     | 4.51%   |
| Kingston            | 20        | 23     | 4.51%   |
| Transcend           | 11        | 15     | 2.48%   |
| Toshiba             | 11        | 12     | 2.48%   |
| Plextor             | 11        | 15     | 2.48%   |
| China               | 10        | 13     | 2.26%   |
| Apple               | 8         | 10     | 1.81%   |
| OCZ                 | 7         | 7      | 1.58%   |
| Micron Technology   | 6         | 10     | 1.35%   |
| Green House         | 6         | 8      | 1.35%   |
| Unknown             | 5         | 5      | 1.13%   |
| SUNEAST             | 5         | 6      | 1.13%   |
| Dogfish             | 5         | 5      | 1.13%   |
| Apacer              | 4         | 6      | 0.9%    |
| Zheino              | 3         | 3      | 0.68%   |
| Teclast             | 3         | 3      | 0.68%   |
| Team                | 3         | 4      | 0.68%   |
| Seagate             | 3         | 5      | 0.68%   |
| Patriot             | 3         | 4      | 0.68%   |
| KLEVV               | 3         | 8      | 0.68%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.68%   |
| Unknown             | 3         | 3      | 0.68%   |
| TCSUNBOW            | 2         | 2      | 0.45%   |
| PNY                 | 2         | 2      | 0.45%   |
| Lexar               | 2         | 2      | 0.45%   |
| Kingmax             | 2         | 2      | 0.45%   |
| BUFFALO             | 2         | 2      | 0.45%   |
| Biostar             | 2         | 2      | 0.45%   |
| AEGO                | 2         | 2      | 0.45%   |
| XSTAR               | 1         | 1      | 0.23%   |
| SK hynix            | 1         | 1      | 0.23%   |
| SATA3 51            | 1         | 2      | 0.23%   |
| Ramaxel Technology  | 1         | 1      | 0.23%   |
| Palit               | 1         | 1      | 0.23%   |
| OASDX               | 1         | 2      | 0.23%   |
| Netac               | 1         | 1      | 0.23%   |
| MARSHAL             | 1         | 1      | 0.23%   |
| LuminouTek          | 1         | 1      | 0.23%   |
| LITEONIT            | 1         | 1      | 0.23%   |
| LITEON              | 1         | 2      | 0.23%   |
| KingDian            | 1         | 1      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |
| Integral            | 1         | 1      | 0.23%   |
| Hitachi             | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| FORESEE             | 1         | 1      | 0.23%   |
| FATTYDOVE           | 1         | 1      | 0.23%   |
| DIERYA              | 1         | 1      | 0.23%   |
| Corsair             | 1         | 1      | 0.23%   |
| Colorful            | 1         | 1      | 0.23%   |
| CFD                 | 1         | 1      | 0.23%   |
| ASUS-PHISON         | 1         | 1      | 0.23%   |
| ASUS-JM             | 1         | 1      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 466       | 767    | 41.39%  |
| SSD     | 397       | 557    | 35.26%  |
| NVMe    | 196       | 294    | 17.41%  |
| MMC     | 44        | 57     | 3.91%   |
| Unknown | 23        | 32     | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 705       | 1295   | 71.36%  |
| NVMe | 196       | 292    | 19.84%  |
| MMC  | 44        | 57     | 4.45%   |
| SAS  | 43        | 63     | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 551       | 832    | 61.5%   |
| 0.51-1.0   | 186       | 243    | 20.76%  |
| 1.01-2.0   | 86        | 125    | 9.6%    |
| 3.01-4.0   | 30        | 47     | 3.35%   |
| 4.01-10.0  | 22        | 44     | 2.46%   |
| 2.01-3.0   | 19        | 30     | 2.12%   |
| 10.01-20.0 | 2         | 3      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 284       | 31.17%  |
| 251-500        | 155       | 17.01%  |
| 501-1000       | 118       | 12.95%  |
| 51-100         | 70        | 7.68%   |
| 1-20           | 61        | 6.7%    |
| 1001-2000      | 57        | 6.26%   |
| More than 3000 | 48        | 5.27%   |
| Unknown        | 43        | 4.72%   |
| 21-50          | 41        | 4.5%    |
| 2001-3000      | 34        | 3.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 424       | 44.54%  |
| 21-50          | 170       | 17.86%  |
| 101-250        | 87        | 9.14%   |
| 51-100         | 78        | 8.19%   |
| 251-500        | 56        | 5.88%   |
| Unknown        | 43        | 4.52%   |
| 501-1000       | 41        | 4.31%   |
| 1001-2000      | 26        | 2.73%   |
| More than 3000 | 17        | 1.79%   |
| 2001-3000      | 10        | 1.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 5         | 5      | 8.33%   |
| WDC WD10EADS-22M2B0 1TB                   | 4         | 4      | 6.67%   |
| SanDisk SD6SF1M128G1022I 128GB SSD        | 4         | 4      | 6.67%   |
| Toshiba MQ01ABD075 752GB                  | 3         | 3      | 5%      |
| Seagate ST9160314AS 160GB                 | 2         | 2      | 3.33%   |
| WDC WD30EZRX-00DC0B0 3TB                  | 1         | 2      | 1.67%   |
| WDC WD25EZRX-00MMMB0 2TB                  | 1         | 1      | 1.67%   |
| WDC WD10JPCX-24UE4T0 1TB                  | 1         | 1      | 1.67%   |
| Transcend TS240GSSD220S 240GB             | 1         | 1      | 1.67%   |
| Toshiba MK5055GSX 500GB                   | 1         | 1      | 1.67%   |
| Toshiba MK1255GSX H 120GB                 | 1         | 1      | 1.67%   |
| SPCC Solid State DiskB28 128GB            | 1         | 1      | 1.67%   |
| SPCC Solid State Disk 512GB               | 1         | 2      | 1.67%   |
| Seagate ST9320320AS 320GB                 | 1         | 1      | 1.67%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1      | 1.67%   |
| Seagate ST3500418AS 500GB                 | 1         | 1      | 1.67%   |
| Seagate ST3250310AS 250GB                 | 1         | 2      | 1.67%   |
| Seagate ST3120026A 120GB                  | 1         | 1      | 1.67%   |
| Seagate ST31000528AS 1TB                  | 1         | 1      | 1.67%   |
| Seagate ST31000333AS 1TB                  | 1         | 1      | 1.67%   |
| Seagate ST3000VM002-1ET166 3TB            | 1         | 1      | 1.67%   |
| Seagate ST2000DX002-2DV164 2TB            | 1         | 1      | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1      | 1.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1      | 1.67%   |
| SanDisk SSD PLUS 1000GB                   | 1         | 2      | 1.67%   |
| SanDisk SSD P4 32GB                       | 1         | 1      | 1.67%   |
| Samsung Electronics HM641JI 640GB         | 1         | 2      | 1.67%   |
| MARSHAL MAL2020SA 80 20GB                 | 1         | 1      | 1.67%   |
| LITEON CV8-8E128-HP 128GB SSD             | 1         | 2      | 1.67%   |
| Intel SSDSCKKF180H6H 180GB                | 1         | 1      | 1.67%   |
| Hitachi HTS727575A9E364 752GB             | 1         | 1      | 1.67%   |
| Hitachi HTS723232A7A364 320GB             | 1         | 1      | 1.67%   |
| Hitachi HTS545050B9A300 500GB             | 1         | 1      | 1.67%   |
| Hitachi HTS545025B9SA02 250GB             | 1         | 1      | 1.67%   |
| Hitachi HDT725032VLA360 320GB             | 1         | 1      | 1.67%   |
| Hitachi HDT721032SLA360 320GB             | 1         | 1      | 1.67%   |
| Hitachi HDT721010SLA360 1TB               | 1         | 1      | 1.67%   |
| Hitachi HDS721010DLE630 1TB               | 1         | 1      | 1.67%   |
| Hitachi HDS721010CLA332 1TB               | 1         | 1      | 1.67%   |
| HGST HTS545050A7E380 500GB                | 1         | 1      | 1.67%   |
| HGST HTS541075A9E680 752GB                | 1         | 1      | 1.67%   |
| Crucial CT480M500SSD1 480GB               | 1         | 1      | 1.67%   |
| Crucial C300-CTFDDAC064MAG 64GB SSD       | 1         | 2      | 1.67%   |
| Corsair CSSD-F60GB2 64GB                  | 1         | 1      | 1.67%   |
| China M.2 SSD 128GB                       | 1         | 1      | 1.67%   |
| A-DATA Technology SP900 256GB SSD         | 1         | 1      | 1.67%   |
| A-DATA Technology AXM21S3-24GM-B 24GB SSD | 1         | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 19     | 29.31%  |
| Hitachi             | 8         | 9      | 13.79%  |
| WDC                 | 7         | 8      | 12.07%  |
| SanDisk             | 6         | 7      | 10.34%  |
| Toshiba             | 5         | 5      | 8.62%   |
| SPCC                | 2         | 3      | 3.45%   |
| HGST                | 2         | 2      | 3.45%   |
| Crucial             | 2         | 3      | 3.45%   |
| A-DATA Technology   | 2         | 2      | 3.45%   |
| Transcend           | 1         | 1      | 1.72%   |
| Samsung Electronics | 1         | 2      | 1.72%   |
| MARSHAL             | 1         | 1      | 1.72%   |
| LITEON              | 1         | 2      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| Corsair             | 1         | 1      | 1.72%   |
| China               | 1         | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 19     | 41.46%  |
| Hitachi             | 8         | 9      | 19.51%  |
| WDC                 | 7         | 8      | 17.07%  |
| Toshiba             | 5         | 5      | 12.2%   |
| HGST                | 2         | 2      | 4.88%   |
| Samsung Electronics | 1         | 2      | 2.44%   |
| MARSHAL             | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 39        | 46     | 69.64%  |
| SSD  | 17        | 21     | 30.36%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 575       | 1140   | 63.12%  |
| Works    | 285       | 500    | 31.28%  |
| Malfunc  | 51        | 67     | 5.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 608       | 56.45%  |
| AMD                              | 166       | 15.41%  |
| Samsung Electronics              | 60        | 5.57%   |
| ASMedia Technology               | 35        | 3.25%   |
| SanDisk                          | 32        | 2.97%   |
| Marvell Technology Group         | 19        | 1.76%   |
| SK hynix                         | 18        | 1.67%   |
| Phison Electronics               | 16        | 1.49%   |
| JMicron Technology               | 16        | 1.49%   |
| Silicon Motion                   | 12        | 1.11%   |
| Nvidia                           | 11        | 1.02%   |
| VIA Technologies                 | 9         | 0.84%   |
| KIOXIA                           | 9         | 0.84%   |
| Toshiba America Info Systems     | 8         | 0.74%   |
| Micron/Crucial Technology        | 8         | 0.74%   |
| Micron Technology                | 8         | 0.74%   |
| Kingston Technology Company      | 7         | 0.65%   |
| Broadcom / LSI                   | 6         | 0.56%   |
| Apple                            | 6         | 0.56%   |
| ADATA Technology                 | 5         | 0.46%   |
| Adaptec                          | 3         | 0.28%   |
| Silicon Image                    | 2         | 0.19%   |
| Seagate Technology               | 2         | 0.19%   |
| Realtek Semiconductor            | 2         | 0.19%   |
| LSI Logic / Symbios Logic        | 2         | 0.19%   |
| HighPoint Technologies           | 2         | 0.19%   |
| Yangtze Memory Technologies      | 1         | 0.09%   |
| ULi Electronics                  | 1         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.09%   |
| Promise Technology               | 1         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 105       | 8.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 58        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 36        | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 32        | 2.48%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 30        | 2.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 29        | 2.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 29        | 2.25%   |
| AMD 400 Series Chipset SATA Controller                                           | 27        | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 22        | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 21        | 1.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 21        | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 21        | 1.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 21        | 1.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 19        | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 19        | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 18        | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 16        | 1.24%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 16        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 16        | 1.24%   |
| AMD 500 Series Chipset SATA Controller                                           | 16        | 1.24%   |
| Intel SATA Controller [RAID mode]                                                | 14        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 14        | 1.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 13        | 1.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 12        | 0.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 0.93%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 11        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 11        | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 10        | 0.77%   |
| JMicron JMB363 SATA/IDE Controller                                               | 10        | 0.77%   |
| Intel SSD 660P Series                                                            | 10        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 9         | 0.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 9         | 0.7%    |
| AMD FCH IDE Controller                                                           | 9         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 0.62%   |
| Samsung NVMe SSD Controller 980                                                  | 8         | 0.62%   |
| Micron Non-Volatile memory controller                                            | 8         | 0.62%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 8         | 0.62%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 8         | 0.62%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 8         | 0.62%   |
| AMD SB600 IDE                                                                    | 8         | 0.62%   |
| AMD 300 Series Chipset SATA Controller                                           | 8         | 0.62%   |
| Phison E12 NVMe Controller                                                       | 7         | 0.54%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 7         | 0.54%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 0.54%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 7         | 0.54%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                | 7         | 0.54%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 7         | 0.54%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 0.46%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 6         | 0.46%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                     | 6         | 0.46%   |
| JMicron JMB368 IDE controller                                                    | 6         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 647       | 59.96%  |
| NVMe | 199       | 18.44%  |
| IDE  | 169       | 15.66%  |
| RAID | 54        | 5%      |
| SAS  | 6         | 0.56%   |
| SCSI | 4         | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 670       | 77.28%  |
| AMD    | 184       | 21.22%  |
| ARM    | 13        | 1.5%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 11        | 1.27%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 1.15%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 1.15%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 8         | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 0.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 7         | 0.81%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 6         | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 0.69%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 6         | 0.69%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 6         | 0.69%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.69%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 5         | 0.58%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 5         | 0.58%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 5         | 0.58%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 5         | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.58%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 5         | 0.58%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 5         | 0.58%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz          | 5         | 0.58%   |
| Intel Core 2 CPU 6600 @ 2.40GHz               | 5         | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.46%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 4         | 0.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 0.46%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.46%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 4         | 0.46%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 0.46%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.46%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.46%   |
| Intel Core i5-4570TE CPU @ 2.70GHz            | 4         | 0.46%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 4         | 0.46%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.46%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.46%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 4         | 0.46%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 4         | 0.46%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 4         | 0.46%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 4         | 0.46%   |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 4         | 0.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.46%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.46%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.46%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 4         | 0.46%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 0.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.46%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 4         | 0.46%   |
| AMD Athlon 200GE with Radeon Vega Graphics    | 4         | 0.46%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 3         | 0.35%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 3         | 0.35%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.35%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 186       | 21.43%  |
| Intel Core i7           | 160       | 18.43%  |
| Intel Core i3           | 57        | 6.57%   |
| Intel Celeron           | 56        | 6.45%   |
| Intel Core 2 Duo        | 55        | 6.34%   |
| AMD Ryzen 5             | 43        | 4.95%   |
| Other                   | 34        | 3.92%   |
| AMD Ryzen 7             | 33        | 3.8%    |
| Intel Xeon              | 29        | 3.34%   |
| Intel Atom              | 21        | 2.42%   |
| Intel Core 2            | 16        | 1.84%   |
| Intel Pentium           | 12        | 1.38%   |
| Intel Core i9           | 11        | 1.27%   |
| AMD Athlon              | 11        | 1.27%   |
| Intel Core 2 Quad       | 10        | 1.15%   |
| AMD Ryzen 3             | 9         | 1.04%   |
| AMD Ryzen 9             | 8         | 0.92%   |
| AMD Phenom II X4        | 6         | 0.69%   |
| AMD FX                  | 6         | 0.69%   |
| AMD Athlon 64 X2        | 6         | 0.69%   |
| AMD A10                 | 6         | 0.69%   |
| Intel Pentium Dual-Core | 5         | 0.58%   |
| Intel Pentium 4         | 5         | 0.58%   |
| AMD A8                  | 5         | 0.58%   |
| AMD A6                  | 5         | 0.58%   |
| Intel Pentium Gold      | 4         | 0.46%   |
| Intel Celeron M         | 4         | 0.46%   |
| Intel Pentium Silver    | 3         | 0.35%   |
| AMD Sempron             | 3         | 0.35%   |
| AMD Ryzen 7 PRO         | 3         | 0.35%   |
| AMD E2                  | 3         | 0.35%   |
| Intel Pentium M         | 2         | 0.23%   |
| Intel Genuine           | 2         | 0.23%   |
| Intel Core m3           | 2         | 0.23%   |
| Intel Core M            | 2         | 0.23%   |
| Intel Celeron Dual-Core | 2         | 0.23%   |
| AMD Turion 64 X2 Mobile | 2         | 0.23%   |
| AMD Ryzen Threadripper  | 2         | 0.23%   |
| AMD Ryzen 5 PRO         | 2         | 0.23%   |
| AMD Ryzen 3 PRO         | 2         | 0.23%   |
| AMD Phenom II X6        | 2         | 0.23%   |
| AMD Phenom              | 2         | 0.23%   |
| AMD Mobile Sempron      | 2         | 0.23%   |
| AMD E1                  | 2         | 0.23%   |
| AMD E                   | 2         | 0.23%   |
| AMD Athlon II X4        | 2         | 0.23%   |
| AMD Athlon Dual Core    | 2         | 0.23%   |
| AMD Athlon 64           | 2         | 0.23%   |
| AMD A4                  | 2         | 0.23%   |
| AMD A12                 | 2         | 0.23%   |
| Intel Xeon Gold         | 1         | 0.12%   |
| Intel Pentium Dual      | 1         | 0.12%   |
| Intel Pentium D         | 1         | 0.12%   |
| Intel Core m5           | 1         | 0.12%   |
| Intel Core 2 Extreme    | 1         | 0.12%   |
| ARM BCM                 | 1         | 0.12%   |
| ARM Allwinner           | 1         | 0.12%   |
| AMD V120                | 1         | 0.12%   |
| AMD Quad-Core           | 1         | 0.12%   |
| AMD Phenom II X2        | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 389       | 44.82%  |
| 4      | 271       | 31.22%  |
| 6      | 88        | 10.14%  |
| 8      | 55        | 6.34%   |
| 1      | 31        | 3.57%   |
| 16     | 13        | 1.5%    |
| 14     | 5         | 0.58%   |
| 12     | 4         | 0.46%   |
| 10     | 4         | 0.46%   |
| 3      | 4         | 0.46%   |
| 56     | 1         | 0.12%   |
| 32     | 1         | 0.12%   |
| 24     | 1         | 0.12%   |
| 20     | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 857       | 98.85%  |
| 2      | 9         | 1.04%   |
| 3      | 1         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 551       | 63.48%  |
| 1      | 317       | 36.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 830       | 95.51%  |
| Unknown        | 23        | 2.65%   |
| 32-bit         | 16        | 1.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 165       | 18.46%  |
| 0x306a9    | 78        | 8.72%   |
| 0x206a7    | 60        | 6.71%   |
| 0x1067a    | 48        | 5.37%   |
| 0x306c3    | 37        | 4.14%   |
| 0x906ea    | 21        | 2.35%   |
| 0x20655    | 20        | 2.24%   |
| 0x806ec    | 19        | 2.13%   |
| 0x306d4    | 19        | 2.13%   |
| 0x506e3    | 18        | 2.01%   |
| 0x08701021 | 18        | 2.01%   |
| 0x906e9    | 14        | 1.57%   |
| 0x10676    | 14        | 1.57%   |
| 0x806e9    | 13        | 1.45%   |
| 0x40651    | 12        | 1.34%   |
| 0x406c4    | 11        | 1.23%   |
| 0x806ea    | 10        | 1.12%   |
| 0x6f6      | 10        | 1.12%   |
| 0x406e3    | 10        | 1.12%   |
| 0x20652    | 10        | 1.12%   |
| 0xa0652    | 9         | 1.01%   |
| 0x806c1    | 9         | 1.01%   |
| 0x0a50000c | 9         | 1.01%   |
| 0x906ed    | 8         | 0.89%   |
| 0x08108102 | 8         | 0.89%   |
| 0x406c3    | 7         | 0.78%   |
| 0x106e5    | 7         | 0.78%   |
| 0x106c2    | 7         | 0.78%   |
| 0x08108109 | 7         | 0.78%   |
| 0x0810100b | 7         | 0.78%   |
| 0x806eb    | 6         | 0.67%   |
| 0x0800820d | 6         | 0.67%   |
| 0x06003106 | 6         | 0.67%   |
| 0x06001119 | 6         | 0.67%   |
| 0x010000db | 6         | 0.67%   |
| 0xa0655    | 5         | 0.56%   |
| 0x706a1    | 5         | 0.56%   |
| 0x6fb      | 5         | 0.56%   |
| 0x50654    | 5         | 0.56%   |
| 0x206d7    | 5         | 0.56%   |
| 0x0a201016 | 5         | 0.56%   |
| 0x010000c8 | 5         | 0.56%   |
| 0xa0660    | 4         | 0.45%   |
| 0xa0653    | 4         | 0.45%   |
| 0x906a3    | 4         | 0.45%   |
| 0x6fd      | 4         | 0.45%   |
| 0x506c9    | 4         | 0.45%   |
| 0x306f2    | 4         | 0.45%   |
| 0x306e4    | 4         | 0.45%   |
| 0x106ca    | 4         | 0.45%   |
| 0x08600106 | 4         | 0.45%   |
| 0x08600104 | 4         | 0.45%   |
| 0x0700010f | 4         | 0.45%   |
| 0x03000027 | 4         | 0.45%   |
| 0x906eb    | 3         | 0.34%   |
| 0x706a8    | 3         | 0.34%   |
| 0x6f2      | 3         | 0.34%   |
| 0x6e8      | 3         | 0.34%   |
| 0x6d8      | 3         | 0.34%   |
| 0x30678    | 3         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 119       | 13.71%  |
| IvyBridge        | 92        | 10.6%   |
| SandyBridge      | 76        | 8.76%   |
| Penryn           | 69        | 7.95%   |
| Haswell          | 62        | 7.14%   |
| Zen 2            | 42        | 4.84%   |
| Skylake          | 40        | 4.61%   |
| Westmere         | 36        | 4.15%   |
| CometLake        | 28        | 3.23%   |
| Zen+             | 27        | 3.11%   |
| Core             | 27        | 3.11%   |
| Silvermont       | 24        | 2.76%   |
| Zen              | 22        | 2.53%   |
| Broadwell        | 22        | 2.53%   |
| Unknown          | 22        | 2.53%   |
| Zen 3            | 19        | 2.19%   |
| K10              | 16        | 1.84%   |
| K8 Hammer        | 15        | 1.73%   |
| Nehalem          | 12        | 1.38%   |
| Bonnell          | 11        | 1.27%   |
| TigerLake        | 10        | 1.15%   |
| Goldmont plus    | 10        | 1.15%   |
| Piledriver       | 9         | 1.04%   |
| P6               | 7         | 0.81%   |
| NetBurst         | 7         | 0.81%   |
| Steamroller      | 6         | 0.69%   |
| Jaguar           | 6         | 0.69%   |
| IceLake          | 5         | 0.58%   |
| K10 Llano        | 4         | 0.46%   |
| Goldmont         | 4         | 0.46%   |
| Bulldozer        | 4         | 0.46%   |
| Alderlake Hybrid | 4         | 0.46%   |
| Puma             | 3         | 0.35%   |
| Excavator        | 3         | 0.35%   |
| Bobcat           | 3         | 0.35%   |
| K8 & K10 hybrid  | 2         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 499       | 52.8%   |
| Nvidia                     | 233       | 24.66%  |
| AMD                        | 206       | 21.8%   |
| Matrox Electronics Systems | 4         | 0.42%   |
| ASPEED Technology          | 2         | 0.21%   |
| VIA Technologies           | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 59        | 5.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 51        | 5.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 3.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 23        | 2.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16        | 1.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 1.52%   |
| Intel HD Graphics 5500                                                                   | 15        | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 1.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.42%   |
| Intel UHD Graphics 620                                                                   | 13        | 1.31%   |
| AMD Renoir                                                                               | 13        | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 1.21%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 12        | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 1.21%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 1.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 1.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 1.11%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 1.11%   |
| Intel HD Graphics 620                                                                    | 11        | 1.11%   |
| AMD Cezanne                                                                              | 11        | 1.11%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.01%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 9         | 0.91%   |
| Intel HD Graphics 530                                                                    | 9         | 0.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 0.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 0.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.81%   |
| Intel HD Graphics 630                                                                    | 8         | 0.81%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.71%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 7         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6         | 0.61%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 6         | 0.61%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6         | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6         | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 5         | 0.51%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.51%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 5         | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 5         | 0.51%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 5         | 0.51%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 5         | 0.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.51%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 0.51%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 5         | 0.51%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5         | 0.51%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 4         | 0.4%    |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.4%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.4%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 4         | 0.4%    |
| Intel HD Graphics 500                                                                    | 4         | 0.4%    |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 424       | 48.62%  |
| 1 x AMD                  | 176       | 20.18%  |
| 1 x Nvidia               | 163       | 18.69%  |
| Intel + Nvidia           | 49        | 5.62%   |
| Other                    | 15        | 1.72%   |
| Intel + AMD              | 10        | 1.15%   |
| AMD + Nvidia             | 9         | 1.03%   |
| 2 x AMD                  | 8         | 0.92%   |
| 2 x Nvidia               | 6         | 0.69%   |
| 1 x Matrox               | 3         | 0.34%   |
| Nvidia + ASPEED          | 2         | 0.23%   |
| Intel + 2 x Nvidia       | 2         | 0.23%   |
| 2 x Intel                | 1         | 0.11%   |
| 1 x VIA                  | 1         | 0.11%   |
| Intel + 2 x AMD          | 1         | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.11%   |
| AMD + Matrox             | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 711       | 81.07%  |
| Proprietary | 127       | 14.48%  |
| Unknown     | 39        | 4.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 487       | 54.72%  |
| 0.01-0.5   | 115       | 12.92%  |
| 1.01-2.0   | 101       | 11.35%  |
| 0.51-1.0   | 73        | 8.2%    |
| 3.01-4.0   | 47        | 5.28%   |
| 7.01-8.0   | 29        | 3.26%   |
| 5.01-6.0   | 19        | 2.13%   |
| 8.01-16.0  | 12        | 1.35%   |
| 16.01-24.0 | 5         | 0.56%   |
| 24.01-32.0 | 1         | 0.11%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 77        | 8.86%   |
| AU Optronics            | 73        | 8.4%    |
| Samsung Electronics     | 52        | 5.98%   |
| Dell                    | 52        | 5.98%   |
| Goldstar                | 50        | 5.75%   |
| IOD                     | 44        | 5.06%   |
| Sharp                   | 40        | 4.6%    |
| Chimei Innolux          | 38        | 4.37%   |
| Mitsubishi              | 31        | 3.57%   |
| BenQ                    | 31        | 3.57%   |
| Iiyama                  | 28        | 3.22%   |
| BOE                     | 25        | 2.88%   |
| Acer                    | 25        | 2.88%   |
| Hewlett-Packard         | 22        | 2.53%   |
| Eizo                    | 21        | 2.42%   |
| Apple                   | 20        | 2.3%    |
| Philips                 | 18        | 2.07%   |
| Lenovo                  | 18        | 2.07%   |
| Unknown                 | 16        | 1.84%   |
| Chi Mei Optoelectronics | 16        | 1.84%   |
| Ancor Communications    | 16        | 1.84%   |
| AOC                     | 13        | 1.5%    |
| Panasonic               | 10        | 1.15%   |
| NEC Computers           | 10        | 1.15%   |
| Toshiba                 | 9         | 1.04%   |
| Sony                    | 9         | 1.04%   |
| PANDA                   | 8         | 0.92%   |
| Idek Iiyama             | 7         | 0.81%   |
| ASUSTek Computer        | 7         | 0.81%   |
| LG Electronics          | 6         | 0.69%   |
| ViewSonic               | 4         | 0.46%   |
| NOV                     | 4         | 0.46%   |
| LG Philips              | 4         | 0.46%   |
| Unknown (XXX)           | 3         | 0.35%   |
| InfoVision              | 3         | 0.35%   |
| Hitachi                 | 3         | 0.35%   |
| Fujitsu                 | 3         | 0.35%   |
| CSO                     | 3         | 0.35%   |
| CPT                     | 3         | 0.35%   |
| ___                     | 2         | 0.23%   |
| YTH                     | 2         | 0.23%   |
| SKY                     | 2         | 0.23%   |
| PTF                     | 2         | 0.23%   |
| Orion                   | 2         | 0.23%   |
| OOO                     | 2         | 0.23%   |
| Onkyo                   | 2         | 0.23%   |
| LYC                     | 2         | 0.23%   |
| InnoLux Display         | 2         | 0.23%   |
| BUFFALO                 | 2         | 0.23%   |
| Unknown                 | 2         | 0.23%   |
| Yamaha                  | 1         | 0.12%   |
| VFV                     | 1         | 0.12%   |
| S2-Tek                  | 1         | 0.12%   |
| RTK                     | 1         | 0.12%   |
| Quanta Display          | 1         | 0.12%   |
| Pixio                   | 1         | 0.12%   |
| Novatek                 | 1         | 0.12%   |
| MPI                     | 1         | 0.12%   |
| Megavision              | 1         | 0.12%   |
| Lenovo Group Limited    | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 6         | 0.67%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                      | 5         | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.55%   |
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                         | 5         | 0.55%   |
| NOV NOVA HD CARD NOV0405 1920x1080 459x296mm 21.5-inch                   | 4         | 0.44%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch              | 4         | 0.44%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.44%   |
| LG Display LCD Monitor LGD02CB 1366x768 344x194mm 15.5-inch              | 4         | 0.44%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                  | 4         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.44%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                        | 4         | 0.44%   |
| Toshiba TV TSB020A 1920x1080                                             | 3         | 0.33%   |
| Sharp HDMI SHP0FDB 1360x768 820x460mm 37.0-inch                          | 3         | 0.33%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 3         | 0.33%   |
| Mitsubishi RDT1714VM MEL4764 1280x1024 338x270mm 17.0-inch               | 3         | 0.33%   |
| Mitsubishi MDT241WG MEL478E 1920x1200 518x291mm 23.4-inch                | 3         | 0.33%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.33%   |
| Iiyama PL3291 IVM7605 1920x1080 698x393mm 31.5-inch                      | 3         | 0.33%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 3         | 0.33%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch                | 3         | 0.33%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                         | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.33%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch         | 3         | 0.33%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                          | 3         | 0.33%   |
| ___ LCDTV16 ___9000 1360x768                                             | 2         | 0.22%   |
| YTH YTH156KC YTH1560 3840x2160 600x330mm 27.0-inch                       | 2         | 0.22%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch               | 2         | 0.22%   |
| Unknown LCD Monitor Mitsubishi RDT233WLM 1920x1080                       | 2         | 0.22%   |
| SKY TV-monitor SKY1901 3840x2160 1210x680mm 54.6-inch                    | 2         | 0.22%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                  | 2         | 0.22%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.22%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 2         | 0.22%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch     | 2         | 0.22%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5033 1280x800 331x207mm 15.4-inch     | 2         | 0.22%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch    | 2         | 0.22%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 2         | 0.22%   |
| Philips PHL 323E7 PHLC121 1920x1080 698x393mm 31.5-inch                  | 2         | 0.22%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                  | 2         | 0.22%   |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch                  | 2         | 0.22%   |
| PANDA LCD Monitor NCP0054 1920x1080 344x194mm 15.5-inch                  | 2         | 0.22%   |
| Panasonic PanasonicTV1 MEIC314 1920x540 698x392mm 31.5-inch              | 2         | 0.22%   |
| OOO 23.8' monitor OOO0001 1920x1080 409x230mm 18.5-inch                  | 2         | 0.22%   |
| Mitsubishi RDT234WLM MEL4887 1920x1080 509x286mm 23.0-inch               | 2         | 0.22%   |
| Mitsubishi RDT194S MEL4685 1280x1024 376x301mm 19.0-inch                 | 2         | 0.22%   |
| LYC L2106 LYC0001 1920x1080 480x260mm 21.5-inch                          | 2         | 0.22%   |
| LG Display LCD Monitor LGD6302 1366x768 344x194mm 15.5-inch              | 2         | 0.22%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.22%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.22%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.22%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 2         | 0.22%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch             | 2         | 0.22%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 2         | 0.22%   |
| LG Display LCD Monitor LGD0171 1366x768 344x194mm 15.5-inch              | 2         | 0.22%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 2         | 0.22%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch                  | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 355       | 41.57%  |
| 1366x768 (WXGA)    | 137       | 16.04%  |
| 3840x2160 (4K)     | 62        | 7.26%   |
| 1280x1024 (SXGA)   | 50        | 5.85%   |
| 2560x1440 (QHD)    | 38        | 4.45%   |
| 1920x1200 (WUXGA)  | 33        | 3.86%   |
| 1280x800 (WXGA)    | 23        | 2.69%   |
| 1680x1050 (WSXGA+) | 17        | 1.99%   |
| 1440x900 (WXGA+)   | 17        | 1.99%   |
| Unknown            | 14        | 1.64%   |
| 1600x900 (HD+)     | 12        | 1.41%   |
| 1920x540           | 10        | 1.17%   |
| 1360x768           | 9         | 1.05%   |
| 1600x1200          | 8         | 0.94%   |
| 2560x1080          | 7         | 0.82%   |
| 2560x1600          | 6         | 0.7%    |
| 1024x768 (XGA)     | 6         | 0.7%    |
| 2880x1800          | 5         | 0.59%   |
| 3440x1440          | 4         | 0.47%   |
| 3840x2400          | 3         | 0.35%   |
| 3840x1080          | 3         | 0.35%   |
| 3200x1800 (QHD+)   | 3         | 0.35%   |
| 1400x1050          | 3         | 0.35%   |
| 1024x600           | 3         | 0.35%   |
| 3200x1200          | 2         | 0.23%   |
| 3072x1920          | 2         | 0.23%   |
| 2160x1440          | 2         | 0.23%   |
| 1280x960           | 2         | 0.23%   |
| 800x480            | 1         | 0.12%   |
| 7680x2160          | 1         | 0.12%   |
| 640x480            | 1         | 0.12%   |
| 5760x1200          | 1         | 0.12%   |
| 4480x1080          | 1         | 0.12%   |
| 3520x1080          | 1         | 0.12%   |
| 3456x2160          | 1         | 0.12%   |
| 3200x2160          | 1         | 0.12%   |
| 3200x1080          | 1         | 0.12%   |
| 2880x1920          | 1         | 0.12%   |
| 2560x1024          | 1         | 0.12%   |
| 2240x1400          | 1         | 0.12%   |
| 2160x1350          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |
| 1920x1280          | 1         | 0.12%   |
| 1792x1344          | 1         | 0.12%   |
| 1360x765           | 1         | 0.12%   |
| 1024x576           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 157       | 18.21%  |
| 13      | 87        | 10.09%  |
| 23      | 70        | 8.12%   |
| 21      | 70        | 8.12%   |
| 27      | 69        | 8%      |
| Unknown | 69        | 8%      |
| 24      | 67        | 7.77%   |
| 17      | 42        | 4.87%   |
| 14      | 37        | 4.29%   |
| 19      | 33        | 3.83%   |
| 12      | 28        | 3.25%   |
| 31      | 23        | 2.67%   |
| 20      | 16        | 1.86%   |
| 11      | 12        | 1.39%   |
| 72      | 10        | 1.16%   |
| 34      | 9         | 1.04%   |
| 22      | 9         | 1.04%   |
| 18      | 9         | 1.04%   |
| 37      | 7         | 0.81%   |
| 10      | 7         | 0.81%   |
| 84      | 4         | 0.46%   |
| 54      | 4         | 0.46%   |
| 42      | 3         | 0.35%   |
| 16      | 3         | 0.35%   |
| 43      | 2         | 0.23%   |
| 40      | 2         | 0.23%   |
| 32      | 2         | 0.23%   |
| 25      | 2         | 0.23%   |
| 74      | 1         | 0.12%   |
| 64      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 49      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 39      | 1         | 0.12%   |
| 35      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 228       | 26.76%  |
| 501-600     | 197       | 23.12%  |
| 201-300     | 118       | 13.85%  |
| 401-500     | 110       | 12.91%  |
| Unknown     | 69        | 8.1%    |
| 351-400     | 51        | 5.99%   |
| 601-700     | 29        | 3.4%    |
| 1501-2000   | 15        | 1.76%   |
| 801-900     | 12        | 1.41%   |
| 701-800     | 10        | 1.17%   |
| 1001-1500   | 8         | 0.94%   |
| 901-1000    | 5         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 557       | 69.19%  |
| 16/10   | 106       | 13.17%  |
| Unknown | 57        | 7.08%   |
| 5/4     | 45        | 5.59%   |
| 4/3     | 16        | 1.99%   |
| 21/9    | 11        | 1.37%   |
| 3/2     | 6         | 0.75%   |
| 32/9    | 5         | 0.62%   |
| 6/5     | 1         | 0.12%   |
| 1.00    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 157       | 18.21%  |
| 201-250        | 156       | 18.1%   |
| 151-200        | 82        | 9.51%   |
| 301-350        | 69        | 8%      |
| Unknown        | 69        | 8%      |
| 71-80          | 62        | 7.19%   |
| 81-90          | 59        | 6.84%   |
| 351-500        | 35        | 4.06%   |
| 251-300        | 35        | 4.06%   |
| 141-150        | 30        | 3.48%   |
| 61-70          | 28        | 3.25%   |
| More than 1000 | 22        | 2.55%   |
| 501-1000       | 15        | 1.74%   |
| 121-130        | 14        | 1.62%   |
| 51-60          | 12        | 1.39%   |
| 41-50          | 7         | 0.81%   |
| 131-140        | 4         | 0.46%   |
| 111-120        | 3         | 0.35%   |
| 91-100         | 3         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 317       | 37.65%  |
| 101-120       | 198       | 23.52%  |
| 121-160       | 143       | 16.98%  |
| 161-240       | 76        | 9.03%   |
| Unknown       | 69        | 8.19%   |
| More than 240 | 20        | 2.38%   |
| 1-50          | 19        | 2.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 734       | 83.6%   |
| 2     | 97        | 11.05%  |
| 0     | 38        | 4.33%   |
| 3     | 7         | 0.8%    |
| 4     | 2         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 433       | 34.47%  |
| Realtek Semiconductor            | 403       | 32.09%  |
| Qualcomm Atheros                 | 143       | 11.39%  |
| Broadcom                         | 93        | 7.4%    |
| Marvell Technology Group         | 27        | 2.15%   |
| BUFFALO                          | 20        | 1.59%   |
| Broadcom Limited                 | 16        | 1.27%   |
| TP-Link                          | 14        | 1.11%   |
| ASIX Electronics                 | 14        | 1.11%   |
| PLANEX                           | 11        | 0.88%   |
| Nvidia                           | 9         | 0.72%   |
| MediaTek                         | 7         | 0.56%   |
| Huawei Technologies              | 7         | 0.56%   |
| Ralink                           | 6         | 0.48%   |
| Elecom                           | 6         | 0.48%   |
| Aquantia                         | 6         | 0.48%   |
| VIA Technologies                 | 3         | 0.24%   |
| Ralink Technology                | 3         | 0.24%   |
| Lenovo                           | 3         | 0.24%   |
| Apple                            | 3         | 0.24%   |
| Samsung Electronics              | 2         | 0.16%   |
| Qualcomm Atheros Communications  | 2         | 0.16%   |
| Prolific Technology              | 2         | 0.16%   |
| NEC Computers                    | 2         | 0.16%   |
| Logitec                          | 2         | 0.16%   |
| JMicron Technology               | 2         | 0.16%   |
| D-Link                           | 2         | 0.16%   |
| Xiaomi                           | 1         | 0.08%   |
| Wilocity                         | 1         | 0.08%   |
| ULi Electronics                  | 1         | 0.08%   |
| U-Blox                           | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| Padix (Rockfire)                 | 1         | 0.08%   |
| NetGear                          | 1         | 0.08%   |
| Netchip Technology               | 1         | 0.08%   |
| LSI                              | 1         | 0.08%   |
| Google                           | 1         | 0.08%   |
| Edimax Technology                | 1         | 0.08%   |
| DisplayLink                      | 1         | 0.08%   |
| Dell                             | 1         | 0.08%   |
| Corega K.K.                      | 1         | 0.08%   |
| ADMtek                           | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 280       | 18.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 37        | 2.51%   |
| Intel Wi-Fi 6 AX200                                                     | 32        | 2.17%   |
| Intel 82579V Gigabit Network Connection                                 | 29        | 1.97%   |
| Intel Ethernet Connection (2) I219-V                                    | 26        | 1.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 1.69%   |
| Intel I211 Gigabit Network Connection                                   | 23        | 1.56%   |
| Realtek RTL8125 2.5GbE Controller                                       | 21        | 1.42%   |
| Intel Wireless 7265                                                     | 20        | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 17        | 1.15%   |
| Intel Wireless 8265 / 8275                                              | 16        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                                    | 16        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.95%   |
| Intel Wireless 7260                                                     | 14        | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 0.88%   |
| Intel Wireless 3165                                                     | 13        | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                           | 12        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 11        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                   | 11        | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 0.68%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 0.68%   |
| Intel Ethernet Connection I217-V                                        | 10        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 9         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.61%   |
| Intel Wireless-AC 9260                                                  | 9         | 0.61%   |
| Intel Wireless 3160                                                     | 9         | 0.61%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 9         | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 8         | 0.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 0.54%   |
| Intel Wireless 8260                                                     | 8         | 0.54%   |
| Intel 82574L Gigabit Network Connection                                 | 8         | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 0.47%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7         | 0.47%   |
| Intel WiMAX Connection 2400m                                            | 7         | 0.47%   |
| Intel WiFi Link 5100                                                    | 7         | 0.47%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                                   | 7         | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.47%   |
| Huawei E353/E3131                                                       | 7         | 0.47%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 7         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 6         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 0.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.41%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 266       | 44.41%  |
| Qualcomm Atheros                | 102       | 17.03%  |
| Realtek Semiconductor           | 89        | 14.86%  |
| Broadcom                        | 51        | 8.51%   |
| BUFFALO                         | 20        | 3.34%   |
| TP-Link                         | 14        | 2.34%   |
| Broadcom Limited                | 13        | 2.17%   |
| PLANEX                          | 11        | 1.84%   |
| MediaTek                        | 7         | 1.17%   |
| Ralink                          | 6         | 1%      |
| Elecom                          | 5         | 0.83%   |
| Ralink Technology               | 3         | 0.5%    |
| Qualcomm Atheros Communications | 2         | 0.33%   |
| Logitec                         | 2         | 0.33%   |
| D-Link                          | 2         | 0.33%   |
| Wilocity                        | 1         | 0.17%   |
| NetGear                         | 1         | 0.17%   |
| NEC Computers                   | 1         | 0.17%   |
| Marvell Technology Group        | 1         | 0.17%   |
| Edimax Technology               | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 32        | 5.31%   |
| Intel Wireless 7265                                                     | 20        | 3.32%   |
| Intel Wireless 8265 / 8275                                              | 16        | 2.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 2.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 2.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 2.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 2.32%   |
| Intel Wireless 7260                                                     | 14        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.16%   |
| Intel Wireless 3165                                                     | 13        | 2.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 11        | 1.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 1.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 1.66%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 9         | 1.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 1.49%   |
| Intel Wireless-AC 9260                                                  | 9         | 1.49%   |
| Intel Wireless 3160                                                     | 9         | 1.49%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 9         | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.33%   |
| Intel Wireless 8260                                                     | 8         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.16%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 7         | 1.16%   |
| Intel WiFi Link 5100                                                    | 7         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 6         | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1%      |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1%      |
| BUFFALO 802.11ac WLAN Adapter                                           | 6         | 1%      |
| Broadcom BCM43228 802.11a/b/g/n                                         | 6         | 1%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.83%   |
| PLANEX GW-USNano2 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 5         | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 0.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 5         | 0.83%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 4         | 0.66%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.66%   |
| Elecom WDC-150SU2M                                                      | 4         | 0.66%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]                 | 4         | 0.66%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 4         | 0.66%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 4         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.5%    |
| PLANEX GW-USValue-EZ 802.11n Wireless Adapter [Realtek RTL8188CUS]      | 3         | 0.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 357       | 42.75%  |
| Intel                            | 287       | 34.37%  |
| Broadcom                         | 53        | 6.35%   |
| Qualcomm Atheros                 | 52        | 6.23%   |
| Marvell Technology Group         | 26        | 3.11%   |
| ASIX Electronics                 | 14        | 1.68%   |
| Nvidia                           | 9         | 1.08%   |
| Huawei Technologies              | 7         | 0.84%   |
| Aquantia                         | 6         | 0.72%   |
| VIA Technologies                 | 3         | 0.36%   |
| Lenovo                           | 3         | 0.36%   |
| Broadcom Limited                 | 3         | 0.36%   |
| Apple                            | 3         | 0.36%   |
| Samsung Electronics              | 2         | 0.24%   |
| JMicron Technology               | 2         | 0.24%   |
| Xiaomi                           | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| Netchip Technology               | 1         | 0.12%   |
| Google                           | 1         | 0.12%   |
| Elecom                           | 1         | 0.12%   |
| DisplayLink                      | 1         | 0.12%   |
| Corega K.K.                      | 1         | 0.12%   |
| ADMtek                           | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 280       | 32.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 37        | 4.3%    |
| Intel 82579V Gigabit Network Connection                                        | 29        | 3.37%   |
| Intel Ethernet Connection (2) I219-V                                           | 26        | 3.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 25        | 2.91%   |
| Intel I211 Gigabit Network Connection                                          | 23        | 2.67%   |
| Realtek RTL8125 2.5GbE Controller                                              | 21        | 2.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 17        | 1.98%   |
| Intel Ethernet Connection (7) I219-V                                           | 16        | 1.86%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12        | 1.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 11        | 1.28%   |
| Intel Ethernet Connection I217-V                                               | 10        | 1.16%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 8         | 0.93%   |
| Intel 82574L Gigabit Network Connection                                        | 8         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 0.81%   |
| Intel WiMAX Connection 2400m                                                   | 7         | 0.81%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 0.81%   |
| Huawei E353/E3131                                                              | 7         | 0.81%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 7         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 0.7%    |
| Intel 82577LC Gigabit Network Connection                                       | 6         | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.7%    |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                                | 6         | 0.7%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                                           | 5         | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.58%   |
| Intel Ethernet Connection (2) I218-V                                           | 5         | 0.58%   |
| Intel 82567V-2 Gigabit Network Connection                                      | 5         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.47%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 4         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 4         | 0.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 0.47%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 0.47%   |
| Intel Ethernet Controller I225-V                                               | 4         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                                          | 4         | 0.47%   |
| Intel Ethernet Connection (11) I219-V                                          | 4         | 0.47%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 4         | 0.47%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]              | 4         | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 3         | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3         | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 3         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.35%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.35%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.35%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.35%   |
| Intel Ethernet Connection I218-V                                               | 3         | 0.35%   |
| Intel Ethernet Connection (12) I219-V                                          | 3         | 0.35%   |
| Intel 82576 Gigabit Network Connection                                         | 3         | 0.35%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 771       | 56.94%  |
| WiFi     | 571       | 42.17%  |
| Modem    | 9         | 0.66%   |
| Unknown  | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 486       | 54.12%  |
| WiFi     | 412       | 45.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 429       | 49.42%  |
| 1     | 394       | 45.39%  |
| 3     | 21        | 2.42%   |
| 0     | 21        | 2.42%   |
| 4     | 3         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 707       | 79.17%  |
| Yes  | 186       | 20.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 194       | 46.19%  |
| Cambridge Silicon Radio         | 66        | 15.71%  |
| Realtek Semiconductor           | 27        | 6.43%   |
| Broadcom                        | 26        | 6.19%   |
| Qualcomm Atheros Communications | 21        | 5%      |
| Apple                           | 19        | 4.52%   |
| IMC Networks                    | 18        | 4.29%   |
| Foxconn / Hon Hai               | 8         | 1.9%    |
| Alps Electric                   | 8         | 1.9%    |
| ASUSTek Computer                | 6         | 1.43%   |
| Fujitsu                         | 5         | 1.19%   |
| Lite-On Technology              | 4         | 0.95%   |
| Realtek                         | 3         | 0.71%   |
| TP-Link                         | 2         | 0.48%   |
| Toshiba                         | 2         | 0.48%   |
| Ralink                          | 2         | 0.48%   |
| Marvell Semiconductor           | 2         | 0.48%   |
| Ralink Technology               | 1         | 0.24%   |
| Opticis                         | 1         | 0.24%   |
| MediaTek                        | 1         | 0.24%   |
| Hewlett-Packard                 | 1         | 0.24%   |
| Dell                            | 1         | 0.24%   |
| Creative Technology             | 1         | 0.24%   |
| Askey Computer                  | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 77        | 18.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 66        | 15.71%  |
| Intel AX201 Bluetooth                                                               | 36        | 8.57%   |
| Intel AX200 Bluetooth                                                               | 30        | 7.14%   |
| Realtek Bluetooth Radio                                                             | 19        | 4.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 17        | 4.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 10        | 2.38%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 2.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 2.14%   |
| Apple Bluetooth Host Controller                                                     | 9         | 2.14%   |
| IMC Networks Bluetooth Device                                                       | 8         | 1.9%    |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.9%    |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 7         | 1.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 1.43%   |
| Intel AX210 Bluetooth                                                               | 6         | 1.43%   |
| Intel Bluetooth Device                                                              | 5         | 1.19%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 5         | 1.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 0.95%   |
| Fujitsu Bluetooth Device                                                            | 4         | 0.95%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.71%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.71%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 3         | 0.71%   |
| TP-Link UB500 Adapter                                                               | 2         | 0.48%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 2         | 0.48%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.48%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.48%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.48%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.48%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.48%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.48%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 2         | 0.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.24%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.24%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.24%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.24%   |
| Opticis Bluetooth Radio                                                             | 1         | 0.24%   |
| MediaTek Wireless_Device                                                            | 1         | 0.24%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.24%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.24%   |
| Lite-On Wireless_Device                                                             | 1         | 0.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.24%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.24%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.24%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.24%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.24%   |
| Fujitsu Bluetooth Radio                                                             | 1         | 0.24%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.24%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.24%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.24%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.24%   |
| Dell BCM2046 Bluetooth Device                                                       | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 628       | 53.63%  |
| AMD                                             | 233       | 19.9%   |
| Nvidia                                          | 184       | 15.71%  |
| C-Media Electronics                             | 22        | 1.88%   |
| Creative Technology                             | 13        | 1.11%   |
| Texas Instruments                               | 11        | 0.94%   |
| VIA Technologies                                | 9         | 0.77%   |
| Harman                                          | 8         | 0.68%   |
| JMTek                                           | 6         | 0.51%   |
| Creative Labs                                   | 5         | 0.43%   |
| Apple                                           | 5         | 0.43%   |
| Yamaha                                          | 4         | 0.34%   |
| Elitegroup Computer Systems (ECS)               | 4         | 0.34%   |
| Realtek Semiconductor                           | 3         | 0.26%   |
| Lenovo                                          | 3         | 0.26%   |
| Generalplus Technology                          | 3         | 0.26%   |
| TOWA Electronics                                | 2         | 0.17%   |
| Sony                                            | 2         | 0.17%   |
| Onkyo                                           | 2         | 0.17%   |
| GN Netcom                                       | 2         | 0.17%   |
| ASUSTek Computer                                | 2         | 0.17%   |
| XMOS                                            | 1         | 0.09%   |
| ULi Electronics                                 | 1         | 0.09%   |
| Thesycon Systemsoftware & Consulting            | 1         | 0.09%   |
| SteelSeries ApS                                 | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.09%   |
| Roland                                          | 1         | 0.09%   |
| RME                                             | 1         | 0.09%   |
| RATOC System                                    | 1         | 0.09%   |
| Rasteme                                         | 1         | 0.09%   |
| Philips (or NXP)                                | 1         | 0.09%   |
| Medeli Electronics                              | 1         | 0.09%   |
| M2Tech                                          | 1         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.09%   |
| JAVS                                            | 1         | 0.09%   |
| iCreate Technologies                            | 1         | 0.09%   |
| Focusrite-Novation                              | 1         | 0.09%   |
| DSEA A/S                                        | 1         | 0.09%   |
| Corsair                                         | 1         | 0.09%   |
| CMX Systems                                     | 1         | 0.09%   |
| Cambridge Silicon Radio                         | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 92        | 6.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 61        | 4.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 59        | 4.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 3.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 39        | 2.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 36        | 2.64%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 35        | 2.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 2.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 33        | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 2.13%   |
| AMD FCH Azalia Controller                                                                         | 26        | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 25        | 1.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 25        | 1.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 24        | 1.76%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 1.54%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 1.54%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 1.47%   |
| Intel 200 Series PCH HD Audio                                                                     | 20        | 1.47%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 19        | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 1.32%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 18        | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 18        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 16        | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 1.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 15        | 1.1%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 12        | 0.88%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 0.81%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 10        | 0.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 0.73%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 10        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 10        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9         | 0.66%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 9         | 0.66%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.59%   |
| AMD Navi 10 HDMI Audio                                                                            | 8         | 0.59%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 7         | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 0.51%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 7         | 0.51%   |
| Harman JBL Pebbles                                                                                | 7         | 0.51%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7         | 0.51%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.44%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 0.44%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 5         | 0.37%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 5         | 0.37%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 5         | 0.37%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5         | 0.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.37%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.37%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 5         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 18.78%  |
| SK hynix            | 58        | 14.15%  |
| Unknown             | 51        | 12.44%  |
| Micron Technology   | 41        | 10%     |
| Kingston            | 32        | 7.8%    |
| Crucial             | 31        | 7.56%   |
| A-DATA Technology   | 16        | 3.9%    |
| Team                | 12        | 2.93%   |
| Corsair             | 12        | 2.93%   |
| Nanya Technology    | 11        | 2.68%   |
| G.Skill             | 9         | 2.2%    |
| Elpida              | 8         | 1.95%   |
| Silicon Power       | 7         | 1.71%   |
| SanMax              | 6         | 1.46%   |
| Unknown (ABCD)      | 5         | 1.22%   |
| Transcend           | 4         | 0.98%   |
| Ramaxel Technology  | 4         | 0.98%   |
| Panram              | 4         | 0.98%   |
| KLEVV               | 4         | 0.98%   |
| Unknown             | 4         | 0.98%   |
| CFD                 | 2         | 0.49%   |
| V-Color             | 1         | 0.24%   |
| Unknown (8AD3)      | 1         | 0.24%   |
| Unknown (0x09EE)    | 1         | 0.24%   |
| UMAX                | 1         | 0.24%   |
| Toshiba             | 1         | 0.24%   |
| Ramos Technology    | 1         | 0.24%   |
| Patriot             | 1         | 0.24%   |
| Neo Forza           | 1         | 0.24%   |
| Kingmax             | 1         | 0.24%   |
| EUDAR               | 1         | 0.24%   |
| Essencore           | 1         | 0.24%   |
| Century Micro       | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 1.16%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 5         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.93%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 4         | 0.93%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 0.93%   |
| Unknown                                                             | 4         | 0.93%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 3         | 0.7%    |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 3         | 0.7%    |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s        | 3         | 0.7%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 3         | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 0.7%    |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s                  | 3         | 0.7%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s                 | 3         | 0.7%    |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s               | 3         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 2         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                         | 2         | 0.47%   |
| Unknown RAM Module 1GB DIMM 800MT/s                                 | 2         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 0.47%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                  | 2         | 0.47%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s                  | 2         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.47%   |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s              | 2         | 0.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.47%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.47%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.47%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.47%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 2         | 0.47%   |
| Nanya RAM M2X4G64CB8HG9N-DG 4GB DIMM DDR3 1600MT/s                  | 2         | 0.47%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.47%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.47%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 0.47%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s              | 2         | 0.47%   |
| Kingston RAM CBD24D4S7S8ME-8 8192MB SODIMM DDR4 2400MT/s            | 2         | 0.47%   |
| Kingston RAM 9905622-057.A00G 4096MB DIMM DDR4 2133MT/s             | 2         | 0.47%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2667MT/s                  | 2         | 0.47%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s                  | 2         | 0.47%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s               | 2         | 0.47%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s               | 2         | 0.47%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s            | 2         | 0.47%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s              | 2         | 0.47%   |
| A-DATA RAM Module 8GB DIMM DDR4 3200MT/s                            | 2         | 0.47%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s                  | 1         | 0.23%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 0.23%   |
| Unknown RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.23%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.23%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.23%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                          | 1         | 0.23%   |
| Unknown RAM Module 4GB SODIMM 1066MT/s                              | 1         | 0.23%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.23%   |
| Unknown RAM Module 4GB LPDDR3 2133MT/s                              | 1         | 0.23%   |
| Unknown RAM Module 4GB DIMM SDRAM                                   | 1         | 0.23%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 0.23%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                           | 1         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 169       | 46.05%  |
| DDR3    | 122       | 33.24%  |
| DDR2    | 20        | 5.45%   |
| LPDDR3  | 18        | 4.9%    |
| SDRAM   | 13        | 3.54%   |
| LPDDR4  | 13        | 3.54%   |
| Unknown | 9         | 2.45%   |
| DDR     | 2         | 0.54%   |
| DDR5    | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 195       | 53.28%  |
| DIMM         | 139       | 37.98%  |
| Row Of Chips | 24        | 6.56%   |
| Unknown      | 5         | 1.37%   |
| Chip         | 2         | 0.55%   |
| RIMM         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 123       | 32.2%   |
| 4096  | 113       | 29.58%  |
| 16384 | 61        | 15.97%  |
| 2048  | 52        | 13.61%  |
| 1024  | 18        | 4.71%   |
| 32768 | 14        | 3.66%   |
| 256   | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 81        | 21.04%  |
| 3200    | 58        | 15.06%  |
| 2667    | 56        | 14.55%  |
| 2400    | 33        | 8.57%   |
| 2133    | 21        | 5.45%   |
| 1333    | 15        | 3.9%    |
| 1334    | 14        | 3.64%   |
| 1067    | 11        | 2.86%   |
| Unknown | 10        | 2.6%    |
| 3600    | 8         | 2.08%   |
| 2666    | 8         | 2.08%   |
| 800     | 8         | 2.08%   |
| 667     | 7         | 1.82%   |
| 1867    | 6         | 1.56%   |
| 1066    | 5         | 1.3%    |
| 4267    | 4         | 1.04%   |
| 4199    | 4         | 1.04%   |
| 1866    | 4         | 1.04%   |
| 3266    | 3         | 0.78%   |
| 2933    | 3         | 0.78%   |
| 1800    | 3         | 0.78%   |
| 533     | 3         | 0.78%   |
| 4800    | 2         | 0.52%   |
| 4266    | 2         | 0.52%   |
| 975     | 2         | 0.52%   |
| 400     | 2         | 0.52%   |
| 4133    | 1         | 0.26%   |
| 3800    | 1         | 0.26%   |
| 3733    | 1         | 0.26%   |
| 3400    | 1         | 0.26%   |
| 3100    | 1         | 0.26%   |
| 3067    | 1         | 0.26%   |
| 3007    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 2733    | 1         | 0.26%   |
| 333     | 1         | 0.26%   |
| 266     | 1         | 0.26%   |
| 100     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 3         | 27.27%  |
| Canon               | 3         | 27.27%  |
| Brother Industries  | 3         | 27.27%  |
| Samsung Electronics | 1         | 9.09%   |
| Hewlett-Packard     | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson WF-2010 Series    | 1         | 9.09%   |
| Seiko Epson PX-045A Series    | 1         | 9.09%   |
| Seiko Epson EP-306 Series     | 1         | 9.09%   |
| Samsung SCX-3200 Series       | 1         | 9.09%   |
| HP ENVY 5000 series           | 1         | 9.09%   |
| Canon PIXMA iX6850 Printer    | 1         | 9.09%   |
| Canon PIXMA iP4600 Printer    | 1         | 9.09%   |
| Canon iP2700 series           | 1         | 9.09%   |
| Brother HL-L2360D series      | 1         | 9.09%   |
| Brother HL-2130 series        | 1         | 9.09%   |
| Brother HL-1440 Laser Printer | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 71        | 21.58%  |
| Microdia                               | 30        | 9.12%   |
| Acer                                   | 28        | 8.51%   |
| IMC Networks                           | 27        | 8.21%   |
| Sunplus Innovation Technology          | 26        | 7.9%    |
| Apple                                  | 17        | 5.17%   |
| Realtek Semiconductor                  | 16        | 4.86%   |
| Logitech                               | 13        | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.65%   |
| Quanta                                 | 9         | 2.74%   |
| Suyin                                  | 8         | 2.43%   |
| Ricoh                                  | 7         | 2.13%   |
| Alcor Micro                            | 7         | 2.13%   |
| Syntek                                 | 6         | 1.82%   |
| Silicon Motion                         | 4         | 1.22%   |
| Microsoft                              | 4         | 1.22%   |
| Samsung Electronics                    | 3         | 0.91%   |
| Importek                               | 3         | 0.91%   |
| Generalplus Technology                 | 3         | 0.91%   |
| Elecom                                 | 3         | 0.91%   |
| Luxvisions Innotech Limited            | 2         | 0.61%   |
| Lite-On Technology                     | 2         | 0.61%   |
| Lenovo                                 | 2         | 0.61%   |
| Genesys Logic                          | 2         | 0.61%   |
| GEMBIRD                                | 2         | 0.61%   |
| Etron Technology                       | 2         | 0.61%   |
| Cubeternet                             | 2         | 0.61%   |
| BUFFALO                                | 2         | 0.61%   |
| Z-Star Microelectronics                | 1         | 0.3%    |
| webcam                                 | 1         | 0.3%    |
| WaveRider Communications               | 1         | 0.3%    |
| SJ-180517-N                            | 1         | 0.3%    |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.3%    |
| Ruision                                | 1         | 0.3%    |
| Primax Electronics                     | 1         | 0.3%    |
| OmniVision Technologies                | 1         | 0.3%    |
| Omnivision                             | 1         | 0.3%    |
| Oculus VR                              | 1         | 0.3%    |
| MacroSilicon                           | 1         | 0.3%    |
| Jieli Technology                       | 1         | 0.3%    |
| Intel                                  | 1         | 0.3%    |
| Huawei Technologies                    | 1         | 0.3%    |
| HD USB Camera                          | 1         | 0.3%    |
| ARC International                      | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 15        | 4.48%   |
| Chicony FJ Camera                                                          | 12        | 3.58%   |
| IMC Networks Integrated Camera                                             | 11        | 3.28%   |
| Chicony Integrated Camera                                                  | 8         | 2.39%   |
| Realtek Integrated_Webcam_HD                                               | 7         | 2.09%   |
| Chicony USB2.0 Camera                                                      | 6         | 1.79%   |
| Logitech Webcam C270                                                       | 5         | 1.49%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 1.49%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 1.49%   |
| Apple Built-in iSight                                                      | 5         | 1.49%   |
| Sunplus HD WebCam                                                          | 4         | 1.19%   |
| Microdia Webcam Vitade AF                                                  | 4         | 1.19%   |
| Chicony HD WebCam                                                          | 4         | 1.19%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 4         | 1.19%   |
| Apple FaceTime HD Camera (Built-in)                                        | 4         | 1.19%   |
| Apple FaceTime HD Camera                                                   | 4         | 1.19%   |
| Acer USB HD Webcam                                                         | 4         | 1.19%   |
| Acer BisonCam, NB Pro                                                      | 4         | 1.19%   |
| Syntek Integrated Camera                                                   | 3         | 0.9%    |
| Sunplus Integrated_Webcam_HD                                               | 3         | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 3         | 0.9%    |
| Ricoh Sony Visual Communication Camera                                     | 3         | 0.9%    |
| Ricoh Sony Vaio Integrated Webcam                                          | 3         | 0.9%    |
| Quanta HD User Facing                                                      | 3         | 0.9%    |
| Microdia Integrated Webcam HD                                              | 3         | 0.9%    |
| Chicony USB 2.0 Camera                                                     | 3         | 0.9%    |
| Chicony Lenovo EasyCamera                                                  | 3         | 0.9%    |
| Chicony HP Wide Vision HD Camera                                           | 3         | 0.9%    |
| Chicony HP HD Camera                                                       | 3         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 3         | 0.9%    |
| Acer Integrated Camera                                                     | 3         | 0.9%    |
| Acer HD Webcam                                                             | 3         | 0.9%    |
| Acer BisonCam,NB Pro                                                       | 3         | 0.9%    |
| Suyin NEC HD WebCam                                                        | 2         | 0.6%    |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.6%    |
| Sunplus Dell HD Webcam                                                     | 2         | 0.6%    |
| Sunplus ASUS USB2.0 Webcam                                                 | 2         | 0.6%    |
| Realtek USB2.0 VGA UVC WebCam                                              | 2         | 0.6%    |
| Realtek Lenovo EasyCamera                                                  | 2         | 0.6%    |
| Microdia USB 2.0 Camera                                                    | 2         | 0.6%    |
| Microdia Integrated Webcam                                                 | 2         | 0.6%    |
| Lite-On Integrated Camera                                                  | 2         | 0.6%    |
| Importek TOSHIBA Web Camera - HD                                           | 2         | 0.6%    |
| Generalplus 808 Camera #9 (web-cam mode)                                   | 2         | 0.6%    |
| Etron BUFFALO BSW32KM03 USB PC Camera                                      | 2         | 0.6%    |
| Elecom UCAM-DLE300T                                                        | 2         | 0.6%    |
| Chicony TOSHIBA Web Camera - FHD                                           | 2         | 0.6%    |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 2         | 0.6%    |
| Chicony Integrated HP HD Webcam                                            | 2         | 0.6%    |
| Chicony HP TrueVision HD Camera                                            | 2         | 0.6%    |
| Chicony HP HD Webcam                                                       | 2         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 0.6%    |
| BUFFALO USB 2.0 Camera                                                     | 2         | 0.6%    |
| Alcor Micro USB 2.0 PC Camera                                              | 2         | 0.6%    |
| Alcor Micro USB 2.0 Camera                                                 | 2         | 0.6%    |
| Acer ThinkPad Integrated Camera                                            | 2         | 0.6%    |
| Acer Lenovo Integrated Webcam                                              | 2         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 28.92%  |
| Synaptics                  | 13        | 15.66%  |
| AuthenTec                  | 13        | 15.66%  |
| Shenzhen Goodix Technology | 10        | 12.05%  |
| Upek                       | 6         | 7.23%   |
| STMicroelectronics         | 6         | 7.23%   |
| LighTuning Technology      | 5         | 6.02%   |
| Elan Microelectronics      | 5         | 6.02%   |
| Focal-systems.Corp         | 1         | 1.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 8         | 9.64%   |
| STMicroelectronics Fingerprint Reader                  | 6         | 7.23%   |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 6.02%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 5         | 6.02%   |
| Shenzhen Goodix Fingerprint Reader                     | 5         | 6.02%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 4         | 4.82%   |
| Validity Sensors Swipe Fingerprint Sensor              | 4         | 4.82%   |
| AuthenTec Fingerprint Sensor                           | 4         | 4.82%   |
| Validity Sensors VFS471 Fingerprint Reader             | 3         | 3.61%   |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 3.61%   |
| AuthenTec AES2810                                      | 3         | 3.61%   |
| AuthenTec AES1600                                      | 3         | 3.61%   |
| Unknown                                                | 3         | 3.61%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 2         | 2.41%   |
| Validity Sensors VFS491                                | 2         | 2.41%   |
| Shenzhen Goodix FingerPrint                            | 2         | 2.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 2         | 2.41%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 2.41%   |
| Elan fingerprint sensor [FeinTech FPS00200]            | 2         | 2.41%   |
| Elan ELAN:Fingerprint                                  | 2         | 2.41%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 2.41%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 1.2%    |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 1.2%    |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 1.2%    |
| Validity Sensors Synaptics WBDI                        | 1         | 1.2%    |
| Upek TCS5B Fingerprint sensor                          | 1         | 1.2%    |
| Synaptics WBDI Device                                  | 1         | 1.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 1.2%    |
| LighTuning Fingerprint Reader                          | 1         | 1.2%    |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 1.2%    |
| Elan ELAN:ARM-M4                                       | 1         | 1.2%    |
| AuthenTec AES2660 Fingerprint Sensor                   | 1         | 1.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Upek             | 7         | 30.43%  |
| Broadcom         | 7         | 30.43%  |
| O2 Micro         | 3         | 13.04%  |
| Alcor Micro      | 3         | 13.04%  |
| SCM Microsystems | 2         | 8.7%    |
| Yubico.com       | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 30.43%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 17.39%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 13.04%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 13.04%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 8.7%    |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 4.35%   |
| Broadcom 5880                                                                | 1         | 4.35%   |
| Broadcom 58200                                                               | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 635       | 72.24%  |
| 1     | 202       | 22.98%  |
| 2     | 31        | 3.53%   |
| 3     | 6         | 0.68%   |
| 6     | 2         | 0.23%   |
| 8     | 1         | 0.11%   |
| 5     | 1         | 0.11%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 81        | 27.18%  |
| Graphics card            | 44        | 14.77%  |
| Net/wireless             | 41        | 13.76%  |
| Multimedia controller    | 35        | 11.74%  |
| Chipcard                 | 21        | 7.05%   |
| Communication controller | 16        | 5.37%   |
| Storage                  | 12        | 4.03%   |
| Unassigned class         | 10        | 3.36%   |
| Bluetooth                | 9         | 3.02%   |
| Sound                    | 8         | 2.68%   |
| Camera                   | 6         | 2.01%   |
| Modem                    | 5         | 1.68%   |
| Storage/ata              | 3         | 1.01%   |
| Net/ethernet             | 3         | 1.01%   |
| Network                  | 2         | 0.67%   |
| Tv card                  | 1         | 0.34%   |
| Storage/nvme             | 1         | 0.34%   |

