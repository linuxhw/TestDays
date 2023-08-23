Kubuntu 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 469

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | CM1630                      | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| ASRock        | N68C-S UCC                  | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| MSI           | B450M-A PRO MAX             | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| HP            | 2AF7                        | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Unknown       | Unknown                     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| MSI           | X99S SLI PLUS               | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Supermicro    | C7H61                       | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Gigabyte      | P67A-UD3-B3                 | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| Medion        | H110H4-EM2                  | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Intel         | DQ57TM AAE70931-402         | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Dell          | 0D881F A05                  | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Unknown       | Unknown                     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| ASRock        | B85M Pro4                   | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| ASUSTek       | Q87M-E                      | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| Dell          | 0D881F A05                  | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| ASUSTek       | P8Z77-V LE                  | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| MSI           | H81M-P33                    | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Gigabyte      | C246-WU4-CF                 | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Supermicro    | C7H61                       | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| MSI           | 2AE0                        | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Biostar       | B350GT3                     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Biostar       | A10N-8800E                  | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| ASRock        | AB350M Pro4                 | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| ASUSTek       | P7P55-M                     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Acer          | Aspire M3920                | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| ASUSTek       | Z170-PRO                    | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| MSI           | X370 GAMING PLUS            | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| Gigabyte      | B365M DS3H                  | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Gigabyte      | A320M-H-CF                  | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | 0WR7PY A02                  | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | B75M-D3H                    | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Acer          | Aspire M3920                | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| ASRock        | FM2A88X Extreme6+           | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| Intel         | H81                         | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Gigabyte      | B365M DS3H                  | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| Alienware     | Aurora R15 AMD              | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Gigabyte      | EX58-UD5                    | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| HP            | 82F2 A01                    | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| Supermicro    | C7H61                       | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| ASUSTek       | Z170-PRO                    | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| Dell          | 0D881F A05                  | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| ASRock        | Z170 Extreme4               | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| ASUSTek       | Z97-A                       | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| Dell          | 0RW199                      | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| Dell          | 0F373D A00                  | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Gigabyte      | M61SME-S2                   | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| HP            | 0A9Ch                       | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | EB1036                      | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| MSI           | B85-G43                     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| ASUSTek       | PRIME Z590-A                | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| Lenovo        | SHARKBAY NOK                | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| HP            | 21F5                        | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| Intel         | DH67BL AAG10189-208         | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| HP            | 8266                        | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Supermicro    | X9DRD-C/iT+                 | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| ASUSTek       | PRIME Z590-P                | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| MSI           | B85-G43                     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| MSI           | B85-G43                     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Gigabyte      | B560M DS3H V2               | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | B85-G43                     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Gigabyte      | B365M DS3H                  | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| Gigabyte      | EX58-UD5                    | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| ASUSTek       | P9X79                       | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| ASRock        | B550M Steel Legend          | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-K               | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| ASRock        | H97 Pro4                    | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| ASRock        | M3A770DE                    | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | B85-G43                     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| HP            | 3397                        | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| Gigabyte      | B560 HD3                    | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| ASUSTek       | PRIME Z490-P                | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| ASRock        | X300M-STX                   | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| Lenovo        | NO DPK                      | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Gigabyte      | X570S AORUS MASTER          | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| ASUSTek       | PRIME B450M-A II            | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| HP            | 8399                        | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| Gigabyte      | Z97M-DS3H                   | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| MSI           | X470 GAMING PLUS            | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| Dell          | 084J0R A00                  | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| Lenovo        | NOK                         | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| ASUSTek       | H170-PRO                    | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| ASRock        | B450M Pro4                  | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| Dell          | 084J0R A00                  | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Gigabyte      | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Gigabyte      | H110M-S2H-CF                | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Unknown       | Unknown                     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| Gigabyte      | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| Supermicro    | X9DAL                       | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASRock        | X99 Extreme4                | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | 0773VG A00                  | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| Gigabyte      | B660M D3H DDR4              | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Shuttle       | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock        | H61M-VS                     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 844C                        | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-P                | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| Gigabyte      | B365M D2V                   | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| MSI           | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| MSI           | H110M PRO-D                 | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| JWIPC         | A320I S1                    | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Gigabyte      | P55-US3L                    | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| Acer          | Aspire G7750                | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| Apple         | Mac-F221BEC8                | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Acer          | Aspire G7750                | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| ASUSTek       | Z97-K                       | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| ASRock        | H470M-HVS                   | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | B450-A PRO MAX              | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Pegatron      | 2AB6                        | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| ASRock        | B450M/ac R2.0               | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| MSI           | B350 PC MATE                | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| MSI           | B350 PC MATE                | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Dell          | 0C2XKD A01                  | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| HP            | 8459                        | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | P8H67                       | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| ASUSTek       | PRIME X370-PRO              | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| ASUSTek       | P9X79 PRO                   | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 8459                        | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| ASRock        | A320M Pro4                  | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| ASUSTek       | P8P67 LE                    | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| ASRock        | X570M Pro4                  | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| ASUSTek       | X99-A/USB                   | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | 0KC9NP A01                  | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| AZW           | Gemini J45                  | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| ASUSTek       | M5A78L LE                   | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | B85M-D2V                    | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| ASRock        | B560M Pro4                  | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| Dell          | 0KJCC5 A00                  | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | SHARKBAY NOK                | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Gigabyte      | X570 GAMING X               | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| ASUSTek       | PRIME B550M-K               | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Biostar       | A68N-2100K                  | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 0AACh                       | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Gigabyte      | B550M DS3H                  | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.15.0-56-generic      | 22       | 5.85%   |
| 5.15.0-52-generic      | 19       | 5.05%   |
| 5.15.0-43-generic      | 19       | 5.05%   |
| 5.15.0-48-generic      | 14       | 3.72%   |
| 5.15.0-67-generic      | 13       | 3.46%   |
| 5.15.0-46-generic      | 13       | 3.46%   |
| 5.19.0-35-generic      | 12       | 3.19%   |
| 5.15.0-47-generic      | 12       | 3.19%   |
| 5.15.0-27-generic      | 12       | 3.19%   |
| 5.15.0-58-generic      | 11       | 2.93%   |
| 5.15.0-40-generic      | 11       | 2.93%   |
| 5.15.0-41-generic      | 10       | 2.66%   |
| 5.19.0-38-generic      | 9        | 2.39%   |
| 5.15.0-69-generic      | 9        | 2.39%   |
| 5.15.0-53-generic      | 9        | 2.39%   |
| 5.15.0-25-generic      | 9        | 2.39%   |
| 5.15.0-75-generic      | 8        | 2.13%   |
| 5.15.0-60-generic      | 8        | 2.13%   |
| 5.19.0-46-generic      | 7        | 1.86%   |
| 5.19.0-41-generic      | 7        | 1.86%   |
| 5.15.0-78-generic      | 7        | 1.86%   |
| 5.15.0-73-generic      | 7        | 1.86%   |
| 5.15.0-50-generic      | 7        | 1.86%   |
| 5.15.0-72-generic      | 6        | 1.6%    |
| 5.15.0-71-generic      | 6        | 1.6%    |
| 5.15.0-30-generic      | 6        | 1.6%    |
| 5.19.0-42-generic      | 5        | 1.33%   |
| 5.15.0-48-lowlatency   | 5        | 1.33%   |
| 5.19.0-43-generic      | 4        | 1.06%   |
| 5.15.0-76-generic      | 4        | 1.06%   |
| 5.15.0-56-lowlatency   | 4        | 1.06%   |
| 5.15.0-37-generic      | 4        | 1.06%   |
| 5.15.0-33-generic      | 4        | 1.06%   |
| 5.19.0-40-generic      | 3        | 0.8%    |
| 5.19.0-32-generic      | 3        | 0.8%    |
| 5.15.0-57-generic      | 3        | 0.8%    |
| 5.15.0-27-lowlatency   | 3        | 0.8%    |
| 5.19.0-50-generic      | 2        | 0.53%   |
| 5.19.0-1025-lowlatency | 2        | 0.53%   |
| 5.15.0-71-lowlatency   | 2        | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 270      | 77.81%  |
| 5.19.0  | 52       | 14.99%  |
| 5.17.0  | 4        | 1.15%   |
| 6.1.5   | 2        | 0.58%   |
| 5.18.4  | 2        | 0.58%   |
| 5.13.0  | 2        | 0.58%   |
| 6.4.0   | 1        | 0.29%   |
| 6.3.6   | 1        | 0.29%   |
| 6.2.0   | 1        | 0.29%   |
| 6.1.1   | 1        | 0.29%   |
| 6.0.1   | 1        | 0.29%   |
| 6.0.0   | 1        | 0.29%   |
| 5.4.0   | 1        | 0.29%   |
| 5.19.12 | 1        | 0.29%   |
| 5.18.19 | 1        | 0.29%   |
| 5.18.12 | 1        | 0.29%   |
| 5.18.10 | 1        | 0.29%   |
| 5.17.6  | 1        | 0.29%   |
| 5.17.14 | 1        | 0.29%   |
| 5.16.0  | 1        | 0.29%   |
| 5.15.13 | 1        | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 271      | 78.1%   |
| 5.19    | 53       | 15.27%  |
| 5.17    | 6        | 1.73%   |
| 5.18    | 5        | 1.44%   |
| 6.1     | 3        | 0.86%   |
| 6.0     | 2        | 0.58%   |
| 5.13    | 2        | 0.58%   |
| 6.4     | 1        | 0.29%   |
| 6.3     | 1        | 0.29%   |
| 6.2     | 1        | 0.29%   |
| 5.4     | 1        | 0.29%   |
| 5.16    | 1        | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 339      | 99.71%  |
| riscv64 | 1        | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| KDE5   | 336      | 98.82%  |
| GNOME  | 2        | 0.59%   |
| KDE    | 1        | 0.29%   |
| Budgie | 1        | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 323      | 95%     |
| Tty     | 9        | 2.65%   |
| Wayland | 7        | 2.06%   |
| Web     | 1        | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 232      | 67.64%  |
| Unknown | 75       | 21.87%  |
| GDM3    | 25       | 7.29%   |
| LightDM | 10       | 2.92%   |
| GDM     | 1        | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang   | Desktops | Percent |
|--------|----------|---------|
| en_US  | 150      | 44.12%  |
| de_DE  | 30       | 8.82%   |
| fr_FR  | 27       | 7.94%   |
| ru_RU  | 18       | 5.29%   |
| it_IT  | 17       | 5%      |
| en_GB  | 17       | 5%      |
| pt_BR  | 13       | 3.82%   |
| en_AU  | 10       | 2.94%   |
| pl_PL  | 7        | 2.06%   |
| es_ES  | 5        | 1.47%   |
| nl_NL  | 4        | 1.18%   |
| en_CA  | 4        | 1.18%   |
| es_AR  | 3        | 0.88%   |
| en_PH  | 3        | 0.88%   |
| de_CH  | 3        | 0.88%   |
| C      | 3        | 0.88%   |
| fi_FI  | 2        | 0.59%   |
| en_ZA  | 2        | 0.59%   |
| en_NZ  | 2        | 0.59%   |
| en_IN  | 2        | 0.59%   |
| el_GR  | 2        | 0.59%   |
| cs_CZ  | 2        | 0.59%   |
| sl_SI  | 1        | 0.29%   |
| pt_PT  | 1        | 0.29%   |
| osa_US | 1        | 0.29%   |
| fr_CA  | 1        | 0.29%   |
| fr_BE  | 1        | 0.29%   |
| es_VE  | 1        | 0.29%   |
| es_CO  | 1        | 0.29%   |
| en_IL  | 1        | 0.29%   |
| en_DE  | 1        | 0.29%   |
| en_AG  | 1        | 0.29%   |
| de_LU  | 1        | 0.29%   |
| de_AT  | 1        | 0.29%   |
| da_DK  | 1        | 0.29%   |
| bg_BG  | 1        | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 193      | 56.6%   |
| EFI  | 148      | 43.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 298      | 86.63%  |
| Btrfs   | 18       | 5.23%   |
| Tmpfs   | 13       | 3.78%   |
| Overlay | 12       | 3.49%   |
| Xfs     | 2        | 0.58%   |
| Ext3    | 1        | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 204      | 59.13%  |
| Unknown | 105      | 30.43%  |
| MBR     | 36       | 10.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 286      | 82.66%  |
| Yes       | 60       | 17.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 209      | 61.47%  |
| Yes       | 131      | 38.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 97       | 28.53%  |
| Gigabyte Technology | 66       | 19.41%  |
| MSI                 | 49       | 14.41%  |
| ASRock              | 32       | 9.41%   |
| Dell                | 23       | 6.76%   |
| Lenovo              | 16       | 4.71%   |
| Hewlett-Packard     | 14       | 4.12%   |
| Supermicro          | 6        | 1.76%   |
| Acer                | 5        | 1.47%   |
| Biostar             | 4        | 1.18%   |
| Intel               | 3        | 0.88%   |
| Fujitsu             | 3        | 0.88%   |
| Unknown             | 3        | 0.88%   |
| Shuttle             | 2        | 0.59%   |
| Positivo            | 2        | 0.59%   |
| AZW                 | 2        | 0.59%   |
| Apple               | 2        | 0.59%   |
| Alienware           | 2        | 0.59%   |
| Seeed Studio        | 1        | 0.29%   |
| Pegatron            | 1        | 0.29%   |
| OEM                 | 1        | 0.29%   |
| Medion              | 1        | 0.29%   |
| JWIPC               | 1        | 0.29%   |
| Huanan              | 1        | 0.29%   |
| Foxconn             | 1        | 0.29%   |
| BESSTAR Tech        | 1        | 0.29%   |
| ABIT                | 1        | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 14       | 4.12%   |
| ASUS ROG STRIX B550-F GAMING   | 5        | 1.47%   |
| MSI MS-7B79                    | 4        | 1.18%   |
| Gigabyte B450M DS3H            | 3        | 0.88%   |
| Dell OptiPlex 7010             | 3        | 0.88%   |
| Unknown                        | 3        | 0.88%   |
| Supermicro SKAGIT09            | 2        | 0.59%   |
| MSI MS-7C95                    | 2        | 0.59%   |
| MSI MS-7C56                    | 2        | 0.59%   |
| MSI MS-7B86                    | 2        | 0.59%   |
| MSI MS-7B84                    | 2        | 0.59%   |
| MSI MS-7A40                    | 2        | 0.59%   |
| HP Compaq Elite 8300 SFF       | 2        | 0.59%   |
| Gigabyte X570 GAMING X         | 2        | 0.59%   |
| Gigabyte B450 I AORUS PRO WIFI | 2        | 0.59%   |
| Gigabyte 970-GAMING            | 2        | 0.59%   |
| Dell OptiPlex 7040             | 2        | 0.59%   |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.59%   |
| ASUS STRIX Z270E GAMING        | 2        | 0.59%   |
| ASUS ROG ZENITH EXTREME        | 2        | 0.59%   |
| ASUS ROG STRIX Z390-E GAMING   | 2        | 0.59%   |
| ASUS ROG STRIX X570-E GAMING   | 2        | 0.59%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.59%   |
| ASUS ROG CROSSHAIR VII HERO    | 2        | 0.59%   |
| ASUS P9X79                     | 2        | 0.59%   |
| ASUS P8Z77-V LE                | 2        | 0.59%   |
| ASRock B450M Pro4              | 2        | 0.59%   |
| ASRock A320M-HDV R4.0          | 2        | 0.59%   |
| Supermicro X9DAL               | 1        | 0.29%   |
| Supermicro X8ST3               | 1        | 0.29%   |
| Supermicro PIO-1UDP10-01-AI036 | 1        | 0.29%   |
| Supermicro C7H61               | 1        | 0.29%   |
| Shuttle SH61R                  | 1        | 0.29%   |
| Shuttle NC01U                  | 1        | 0.29%   |
| Seeed Studio ODYSSEY-X86J4105  | 1        | 0.29%   |
| Positivo POS-PIH81DI           | 1        | 0.29%   |
| Positivo POS-PARS760GCD        | 1        | 0.29%   |
| Pegatron p6740la               | 1        | 0.29%   |
| OEM G41 775 ICH7 8712          | 1        | 0.29%   |
| MSI MS-7D91                    | 1        | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 20       | 5.88%   |
| ASUS PRIME             | 17       | 5%      |
| ASUS All               | 14       | 4.12%   |
| Dell OptiPlex          | 12       | 3.53%   |
| Lenovo ThinkCentre     | 11       | 3.24%   |
| ASUS TUF               | 9        | 2.65%   |
| Gigabyte X570          | 5        | 1.47%   |
| Dell Precision         | 5        | 1.47%   |
| MSI MS-7B79            | 4        | 1.18%   |
| Lenovo IdeaCentre      | 4        | 1.18%   |
| Gigabyte B450          | 4        | 1.18%   |
| Dell XPS               | 4        | 1.18%   |
| Acer Aspire            | 4        | 1.18%   |
| HP ProDesk             | 3        | 0.88%   |
| HP Compaq              | 3        | 0.88%   |
| Gigabyte H410M         | 3        | 0.88%   |
| Gigabyte B450M         | 3        | 0.88%   |
| Fujitsu ESPRIMO        | 3        | 0.88%   |
| ASUS STRIX             | 3        | 0.88%   |
| ASUS P9X79             | 3        | 0.88%   |
| ASUS M5A78L-M          | 3        | 0.88%   |
| ASRock B450M           | 3        | 0.88%   |
| ASRock A320M-HDV       | 3        | 0.88%   |
| Unknown                | 3        | 0.88%   |
| Supermicro SKAGIT09    | 2        | 0.59%   |
| MSI MS-7C95            | 2        | 0.59%   |
| MSI MS-7C56            | 2        | 0.59%   |
| MSI MS-7B86            | 2        | 0.59%   |
| MSI MS-7B84            | 2        | 0.59%   |
| MSI MS-7A40            | 2        | 0.59%   |
| HP Pavilion            | 2        | 0.59%   |
| HP EliteDesk           | 2        | 0.59%   |
| Gigabyte Z390          | 2        | 0.59%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.59%   |
| Gigabyte B660M         | 2        | 0.59%   |
| Gigabyte B560M         | 2        | 0.59%   |
| Gigabyte B365M         | 2        | 0.59%   |
| Gigabyte 970-GAMING    | 2        | 0.59%   |
| Dell Inspiron          | 2        | 0.59%   |
| ASUS P8Z77-V           | 2        | 0.59%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 47       | 13.82%  |
| 2020 | 37       | 10.88%  |
| 2021 | 33       | 9.71%   |
| 2019 | 33       | 9.71%   |
| 2014 | 29       | 8.53%   |
| 2017 | 25       | 7.35%   |
| 2013 | 25       | 7.35%   |
| 2012 | 22       | 6.47%   |
| 2015 | 18       | 5.29%   |
| 2016 | 16       | 4.71%   |
| 2011 | 15       | 4.41%   |
| 2010 | 11       | 3.24%   |
| 2022 | 9        | 2.65%   |
| 2009 | 7        | 2.06%   |
| 2008 | 7        | 2.06%   |
| 2007 | 4        | 1.18%   |
| 2023 | 2        | 0.59%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 340      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 330      | 97.06%  |
| Enabled  | 10       | 2.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 340      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 101      | 29.62%  |
| 32.01-64.0      | 82       | 24.05%  |
| 8.01-16.0       | 54       | 15.84%  |
| 4.01-8.0        | 37       | 10.85%  |
| 64.01-256.0     | 32       | 9.38%   |
| 3.01-4.0        | 21       | 6.16%   |
| 24.01-32.0      | 13       | 3.81%   |
| More than 256.0 | 1        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 94       | 26.26%  |
| 4.01-8.0   | 89       | 24.86%  |
| 1.01-2.0   | 66       | 18.44%  |
| 3.01-4.0   | 61       | 17.04%  |
| 8.01-16.0  | 29       | 8.1%    |
| 16.01-24.0 | 10       | 2.79%   |
| 0.51-1.0   | 4        | 1.12%   |
| 32.01-64.0 | 2        | 0.56%   |
| 24.01-32.0 | 2        | 0.56%   |
| 0.01-0.5   | 1        | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 106      | 30.9%   |
| 1      | 85       | 24.78%  |
| 3      | 71       | 20.7%   |
| 4      | 33       | 9.62%   |
| 5      | 23       | 6.71%   |
| 6      | 14       | 4.08%   |
| 7      | 7        | 2.04%   |
| 9      | 2        | 0.58%   |
| 11     | 1        | 0.29%   |
| 8      | 1        | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 202      | 59.24%  |
| Yes       | 139      | 40.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 337      | 99.12%  |
| No        | 3        | 0.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 180      | 52.63%  |
| No        | 162      | 47.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 194      | 57.06%  |
| Yes       | 146      | 42.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 77       | 22.65%  |
| Germany      | 39       | 11.47%  |
| France       | 25       | 7.35%   |
| Italy        | 21       | 6.18%   |
| UK           | 20       | 5.88%   |
| Russia       | 19       | 5.59%   |
| Brazil       | 19       | 5.59%   |
| Poland       | 12       | 3.53%   |
| Netherlands  | 11       | 3.24%   |
| Australia    | 9        | 2.65%   |
| Spain        | 8        | 2.35%   |
| Canada       | 8        | 2.35%   |
| Switzerland  | 5        | 1.47%   |
| Finland      | 5        | 1.47%   |
| Slovenia     | 4        | 1.18%   |
| Portugal     | 4        | 1.18%   |
| Bulgaria     | 4        | 1.18%   |
| Argentina    | 4        | 1.18%   |
| Philippines  | 3        | 0.88%   |
| New Zealand  | 3        | 0.88%   |
| India        | 3        | 0.88%   |
| Belgium      | 3        | 0.88%   |
| Thailand     | 2        | 0.59%   |
| South Africa | 2        | 0.59%   |
| Serbia       | 2        | 0.59%   |
| Mexico       | 2        | 0.59%   |
| Iran         | 2        | 0.59%   |
| Greece       | 2        | 0.59%   |
| Czechia      | 2        | 0.59%   |
| Austria      | 2        | 0.59%   |
| Vietnam      | 1        | 0.29%   |
| Venezuela    | 1        | 0.29%   |
| Ukraine      | 1        | 0.29%   |
| Turkey       | 1        | 0.29%   |
| Sweden       | 1        | 0.29%   |
| Romania      | 1        | 0.29%   |
| Norway       | 1        | 0.29%   |
| Malta        | 1        | 0.29%   |
| Malaysia     | 1        | 0.29%   |
| Luxembourg   | 1        | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 6        | 1.72%   |
| Munich            | 5        | 1.43%   |
| Berlin            | 5        | 1.43%   |
| Rio de Janeiro    | 4        | 1.15%   |
| Montreal          | 4        | 1.15%   |
| London            | 4        | 1.15%   |
| Sydney            | 3        | 0.86%   |
| Sao Paulo         | 3        | 0.86%   |
| Milan             | 3        | 0.86%   |
| Melbourne         | 3        | 0.86%   |
| Dallas            | 3        | 0.86%   |
| Wroclaw           | 2        | 0.57%   |
| Washington        | 2        | 0.57%   |
| Vladivostok       | 2        | 0.57%   |
| Vienna            | 2        | 0.57%   |
| Turku             | 2        | 0.57%   |
| Strasbourg        | 2        | 0.57%   |
| Prague            | 2        | 0.57%   |
| Pittsburgh        | 2        | 0.57%   |
| New York          | 2        | 0.57%   |
| Ljubljana         | 2        | 0.57%   |
| Hamburg           | 2        | 0.57%   |
| Grenoble          | 2        | 0.57%   |
| Frankfurt am Main | 2        | 0.57%   |
| Curitiba          | 2        | 0.57%   |
| Columbus          | 2        | 0.57%   |
| Caruaru           | 2        | 0.57%   |
| Canberra          | 2        | 0.57%   |
| Brasília         | 2        | 0.57%   |
| Bougival          | 2        | 0.57%   |
| Belgrade          | 2        | 0.57%   |
| Auckland          | 2        | 0.57%   |
| Amsterdam         | 2        | 0.57%   |
| Zurich            | 1        | 0.29%   |
| Zaandam           | 1        | 0.29%   |
| Yerevan           | 1        | 0.29%   |
| Wheaton           | 1        | 0.29%   |
| Whangarei         | 1        | 0.29%   |
| Wembley           | 1        | 0.29%   |
| Waukee            | 1        | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 118      | 175    | 16.81%  |
| Samsung Electronics         | 115      | 203    | 16.38%  |
| Seagate                     | 111      | 196    | 15.81%  |
| Kingston                    | 45       | 57     | 6.41%   |
| Toshiba                     | 40       | 50     | 5.7%    |
| SanDisk                     | 36       | 48     | 5.13%   |
| Crucial                     | 31       | 37     | 4.42%   |
| Hitachi                     | 26       | 34     | 3.7%    |
| A-DATA Technology           | 17       | 18     | 2.42%   |
| Unknown                     | 10       | 15     | 1.42%   |
| PNY                         | 9        | 16     | 1.28%   |
| Patriot                     | 9        | 12     | 1.28%   |
| Intel                       | 9        | 12     | 1.28%   |
| HGST                        | 9        | 13     | 1.28%   |
| Phison                      | 8        | 8      | 1.14%   |
| China                       | 8        | 9      | 1.14%   |
| Phison Electronics          | 6        | 6      | 0.85%   |
| Maxtor                      | 6        | 7      | 0.85%   |
| OCZ                         | 5        | 5      | 0.71%   |
| Micron/Crucial Technology   | 4        | 5      | 0.57%   |
| Lexar                       | 4        | 4      | 0.57%   |
| Intenso                     | 4        | 6      | 0.57%   |
| Transcend                   | 3        | 4      | 0.43%   |
| T-FORCE                     | 3        | 3      | 0.43%   |
| SPCC                        | 3        | 3      | 0.43%   |
| Mushkin                     | 3        | 4      | 0.43%   |
| Micron Technology           | 3        | 3      | 0.43%   |
| Corsair                     | 3        | 4      | 0.43%   |
| Apple                       | 3        | 3      | 0.43%   |
| XPG                         | 2        | 2      | 0.28%   |
| Verbatim                    | 2        | 2      | 0.28%   |
| Smartbuy                    | 2        | 2      | 0.28%   |
| SK hynix                    | 2        | 4      | 0.28%   |
| SABRENT                     | 2        | 2      | 0.28%   |
| Realtek Semiconductor       | 2        | 2      | 0.28%   |
| KODAK                       | 2        | 2      | 0.28%   |
| KIOXIA                      | 2        | 2      | 0.28%   |
| Kingston Technology Company | 2        | 3      | 0.28%   |
| Hewlett-Packard             | 2        | 2      | 0.28%   |
| GOODRAM                     | 2        | 2      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 13       | 1.57%   |
| Toshiba DT01ACA100 1TB                              | 8        | 0.97%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8        | 0.97%   |
| Samsung SSD 850 EVO 500GB                           | 8        | 0.97%   |
| Samsung SSD 860 EVO 1TB                             | 7        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7        | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 6        | 0.73%   |
| Samsung SSD 860 EVO 500GB                           | 6        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                     | 6        | 0.73%   |
| Crucial CT240BX500SSD1 240GB                        | 6        | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5        | 0.6%    |
| Seagate ST1000DM003-1CH162 1TB                      | 5        | 0.6%    |
| SanDisk NVMe SSD Drive 500GB                        | 5        | 0.6%    |
| Toshiba HDWD110 1TB                                 | 4        | 0.48%   |
| Seagate ST4000VN008-2DR166 4TB                      | 4        | 0.48%   |
| Seagate ST3500418AS 500GB                           | 4        | 0.48%   |
| Seagate Expansion 1TB                               | 4        | 0.48%   |
| Samsung SSD 980 PRO 2TB                             | 4        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                        | 4        | 0.48%   |
| Samsung SSD 870 QVO 1TB                             | 4        | 0.48%   |
| Samsung SSD 870 EVO 1TB                             | 4        | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 4        | 0.48%   |
| Samsung SSD 840 EVO 250GB                           | 4        | 0.48%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.48%   |
| Samsung HD103SI 1TB                                 | 4        | 0.48%   |
| Kingston SA2000M81000G 1TB                          | 4        | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 3        | 0.36%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3        | 0.36%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 3        | 0.36%   |
| WDC WD20EARX-00PASB0 2TB                            | 3        | 0.36%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.36%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 3        | 0.36%   |
| Unknown SD/MMC 2GB                                  | 3        | 0.36%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 0.36%   |
| Toshiba HDWD130 3TB                                 | 3        | 0.36%   |
| Toshiba DT01ACA200 2TB                              | 3        | 0.36%   |
| Seagate ST500DM002-1BD142 500GB                     | 3        | 0.36%   |
| Seagate ST31000524AS 1TB                            | 3        | 0.36%   |
| Seagate ST2000DX001-1CM164 2TB                      | 3        | 0.36%   |
| Seagate ST2000DM008-2UB102 2TB                      | 3        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 105      | 185    | 34.09%  |
| WDC                 | 103      | 141    | 33.44%  |
| Toshiba             | 35       | 43     | 11.36%  |
| Hitachi             | 26       | 34     | 8.44%   |
| Samsung Electronics | 18       | 25     | 5.84%   |
| HGST                | 9        | 13     | 2.92%   |
| Maxtor              | 5        | 6      | 1.62%   |
| Unknown             | 2        | 2      | 0.65%   |
| Apple               | 2        | 2      | 0.65%   |
| USB3.0              | 1        | 1      | 0.32%   |
| JMicron Technology  | 1        | 1      | 0.32%   |
| IET                 | 1        | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 72       | 115    | 26.47%  |
| Kingston            | 36       | 42     | 13.24%  |
| Crucial             | 26       | 30     | 9.56%   |
| SanDisk             | 22       | 22     | 8.09%   |
| WDC                 | 17       | 25     | 6.25%   |
| A-DATA Technology   | 14       | 15     | 5.15%   |
| PNY                 | 9        | 16     | 3.31%   |
| Patriot             | 9        | 12     | 3.31%   |
| China               | 8        | 9      | 2.94%   |
| OCZ                 | 5        | 5      | 1.84%   |
| Intel               | 5        | 8      | 1.84%   |
| Lexar               | 4        | 4      | 1.47%   |
| Toshiba             | 3        | 3      | 1.1%    |
| Mushkin             | 3        | 4      | 1.1%    |
| Micron Technology   | 3        | 3      | 1.1%    |
| Intenso             | 3        | 3      | 1.1%    |
| Verbatim            | 2        | 2      | 0.74%   |
| Transcend           | 2        | 2      | 0.74%   |
| SPCC                | 2        | 2      | 0.74%   |
| KODAK               | 2        | 2      | 0.74%   |
| Hewlett-Packard     | 2        | 2      | 0.74%   |
| GOODRAM             | 2        | 2      | 0.74%   |
| ValueTech           | 1        | 1      | 0.37%   |
| Team                | 1        | 1      | 0.37%   |
| T-FORCE             | 1        | 1      | 0.37%   |
| Smartbuy            | 1        | 1      | 0.37%   |
| Seagate             | 1        | 1      | 0.37%   |
| Plextor             | 1        | 1      | 0.37%   |
| OCZ-VERTEX3         | 1        | 1      | 0.37%   |
| Maxtor              | 1        | 1      | 0.37%   |
| LITEONIT            | 1        | 1      | 0.37%   |
| KIOXIA-EXCERIA      | 1        | 2      | 0.37%   |
| KingFast            | 1        | 1      | 0.37%   |
| INNOVATION IT       | 1        | 1      | 0.37%   |
| INDMEM              | 1        | 1      | 0.37%   |
| Emtec               | 1        | 1      | 0.37%   |
| Drevo               | 1        | 1      | 0.37%   |
| DeLOCK              | 1        | 1      | 0.37%   |
| BlueRay             | 1        | 1      | 0.37%   |
| Apple               | 1        | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 231      | 454    | 39.02%  |
| SSD     | 220      | 350    | 37.16%  |
| NVMe    | 125      | 188    | 21.11%  |
| Unknown | 13       | 20     | 2.2%    |
| MMC     | 3        | 3      | 0.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 312      | 778    | 66.38%  |
| NVMe | 123      | 185    | 26.17%  |
| SAS  | 32       | 49     | 6.81%   |
| MMC  | 3        | 3      | 0.64%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 219      | 378    | 43.8%   |
| 0.51-1.0   | 140      | 204    | 28%     |
| 1.01-2.0   | 65       | 94     | 13%     |
| 3.01-4.0   | 40       | 72     | 8%      |
| 4.01-10.0  | 20       | 32     | 4%      |
| 2.01-3.0   | 12       | 16     | 2.4%    |
| 10.01-20.0 | 4        | 8      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 65       | 18.57%  |
| 1001-2000      | 61       | 17.43%  |
| 501-1000       | 60       | 17.14%  |
| 251-500        | 54       | 15.43%  |
| 101-250        | 47       | 13.43%  |
| 2001-3000      | 45       | 12.86%  |
| 1-20           | 11       | 3.14%   |
| 51-100         | 6        | 1.71%   |
| Unknown        | 1        | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 53       | 15.01%  |
| 101-250        | 52       | 14.73%  |
| 251-500        | 49       | 13.88%  |
| 1-20           | 42       | 11.9%   |
| 51-100         | 41       | 11.61%  |
| 1001-2000      | 38       | 10.76%  |
| More than 3000 | 31       | 8.78%   |
| 21-50          | 30       | 8.5%    |
| 2001-3000      | 16       | 4.53%   |
| Unknown        | 1        | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB          | 2        | 2      | 3.51%   |
| Hitachi HDS721010CLA630 1TB              | 2        | 2      | 3.51%   |
| WDC WD5000AZRX-00A3KB0 500GB             | 1        | 1      | 1.75%   |
| WDC WD5000AVVS-63M8B0 500GB              | 1        | 1      | 1.75%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 1.75%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 2      | 1.75%   |
| WDC WD20EADS-14R6B0 2TB                  | 1        | 1      | 1.75%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD10EURX-73C57Y0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1        | 1      | 1.75%   |
| WDC WD10EADS-00L5B1 1TB                  | 1        | 1      | 1.75%   |
| WDC WD10EACS-65D6B0 1TB                  | 1        | 1      | 1.75%   |
| Toshiba MQ01ABF032 320GB                 | 1        | 1      | 1.75%   |
| T-FORCE SSD 512GB                        | 1        | 1      | 1.75%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 1.75%   |
| Seagate ST4000VN008-2DR166 4TB           | 1        | 2      | 1.75%   |
| Seagate ST3500630AS 500GB                | 1        | 1      | 1.75%   |
| Seagate ST3500418AS 500GB                | 1        | 1      | 1.75%   |
| Seagate ST3250310AS 250GB                | 1        | 1      | 1.75%   |
| Seagate ST3160827AS 160GB                | 1        | 1      | 1.75%   |
| Seagate ST3160023A 160GB                 | 1        | 1      | 1.75%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 1.75%   |
| Seagate ST31000524AS 1TB                 | 1        | 2      | 1.75%   |
| Seagate ST2000DX001-1NS164 2TB           | 1        | 1      | 1.75%   |
| Seagate ST1000NM0011 1TB                 | 1        | 1      | 1.75%   |
| Seagate ST1000DM003-1SB102 1TB           | 1        | 1      | 1.75%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1      | 1.75%   |
| SanDisk SDSSDX240GG25 240GB              | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 870 EVO 1TB      | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 840 Series 250GB | 1        | 1      | 1.75%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 1.75%   |
| Samsung Electronics HM321HI 320GB        | 1        | 1      | 1.75%   |
| Samsung Electronics HD501LJ 500GB        | 1        | 5      | 1.75%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 1.75%   |
| Phison Electronics PCIe SSD 2TB          | 1        | 1      | 1.75%   |
| OCZ VERTEX3 120GB SSD                    | 1        | 1      | 1.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 18     | 25.93%  |
| WDC                 | 11       | 13     | 20.37%  |
| Samsung Electronics | 7        | 11     | 12.96%  |
| Hitachi             | 6        | 6      | 11.11%  |
| Crucial             | 3        | 3      | 5.56%   |
| Maxtor              | 2        | 2      | 3.7%    |
| Toshiba             | 1        | 1      | 1.85%   |
| T-FORCE             | 1        | 1      | 1.85%   |
| SanDisk             | 1        | 1      | 1.85%   |
| Phison Electronics  | 1        | 1      | 1.85%   |
| OCZ                 | 1        | 1      | 1.85%   |
| Micron Technology   | 1        | 1      | 1.85%   |
| LITEONIT            | 1        | 1      | 1.85%   |
| Kingston            | 1        | 1      | 1.85%   |
| Intenso             | 1        | 1      | 1.85%   |
| Intel               | 1        | 4      | 1.85%   |
| HGST                | 1        | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 18     | 36.84%  |
| WDC                 | 11       | 13     | 28.95%  |
| Hitachi             | 6        | 6      | 15.79%  |
| Samsung Electronics | 3        | 7      | 7.89%   |
| Maxtor              | 2        | 2      | 5.26%   |
| Toshiba             | 1        | 1      | 2.63%   |
| HGST                | 1        | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 35       | 48     | 68.63%  |
| SSD  | 15       | 18     | 29.41%  |
| NVMe | 1        | 1      | 1.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1        | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1        | 1      | 50%     |
| Hitachi             | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 181      | 476    | 44.36%  |
| Detected | 177      | 470    | 43.38%  |
| Malfunc  | 49       | 67     | 12.01%  |
| Failed   | 1        | 2      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 201      | 38.65%  |
| AMD                          | 134      | 25.77%  |
| Samsung Electronics          | 46       | 8.85%   |
| ASMedia Technology           | 25       | 4.81%   |
| SanDisk                      | 24       | 4.62%   |
| Phison Electronics           | 18       | 3.46%   |
| Kingston Technology Company  | 13       | 2.5%    |
| Micron/Crucial Technology    | 10       | 1.92%   |
| JMicron Technology           | 9        | 1.73%   |
| Marvell Technology Group     | 6        | 1.15%   |
| ADATA Technology             | 5        | 0.96%   |
| Seagate Technology           | 4        | 0.77%   |
| LSI Logic / Symbios Logic    | 4        | 0.77%   |
| Realtek Semiconductor        | 3        | 0.58%   |
| KIOXIA                       | 3        | 0.58%   |
| Toshiba America Info Systems | 2        | 0.38%   |
| SK hynix                     | 2        | 0.38%   |
| Silicon Motion               | 2        | 0.38%   |
| Nvidia                       | 2        | 0.38%   |
| VIA Technologies             | 1        | 0.19%   |
| Silicon Image                | 1        | 0.19%   |
| OCZ Technology Group         | 1        | 0.19%   |
| O2 Micro                     | 1        | 0.19%   |
| Netac Technology             | 1        | 0.19%   |
| INNOGRIT                     | 1        | 0.19%   |
| Broadcom / LSI               | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 82       | 12.85%  |
| AMD 400 Series Chipset SATA Controller                                                  | 34       | 5.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 25       | 3.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24       | 3.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 23       | 3.61%   |
| AMD 500 Series Chipset SATA Controller                                                  | 23       | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 2.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 14       | 2.19%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 14       | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 13       | 2.04%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13       | 2.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 12       | 1.88%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 1.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 9        | 1.41%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.41%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 8        | 1.25%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 8        | 1.25%   |
| Phison E12 NVMe Controller                                                              | 7        | 1.1%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7        | 1.1%    |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.1%    |
| Samsung NVMe SSD Controller 980                                                         | 6        | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                         | 6        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.94%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 0.94%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.78%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 4        | 0.63%   |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 4        | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4        | 0.63%   |
| Intel SSD 660P Series                                                                   | 4        | 0.63%   |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 306      | 61.45%  |
| NVMe | 122      | 24.5%   |
| IDE  | 44       | 8.84%   |
| RAID | 22       | 4.42%   |
| SAS  | 2        | 0.4%    |
| SCSI | 2        | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 201      | 59.12%  |
| AMD           | 138      | 40.59%  |
| sifive,u74-mc | 1        | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 2.65%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 2.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 2.35%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.76%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 1.76%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 1.47%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 5        | 1.47%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 5        | 1.47%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 1.47%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5        | 1.47%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 1.47%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4        | 1.18%   |
| Intel Core i3-10100F CPU @ 3.60GHz          | 4        | 1.18%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.18%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.18%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.18%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.88%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.88%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.88%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 3        | 0.88%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.88%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.88%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 0.88%   |
| Intel 12th Gen Core i7-12700K               | 3        | 0.88%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.88%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 3        | 0.88%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3        | 0.88%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.88%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 0.88%   |
| AMD Ryzen 5 5600 6-Core Processor           | 3        | 0.88%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.88%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 0.88%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.88%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 0.59%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 0.59%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.59%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.59%   |
| Intel Core i7-4790S CPU @ 3.20GHz           | 2        | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 65       | 19.12%  |
| Intel Core i5          | 51       | 15%     |
| AMD Ryzen 5            | 40       | 11.76%  |
| AMD Ryzen 7            | 27       | 7.94%   |
| Intel Core i3          | 22       | 6.47%   |
| AMD Ryzen 9            | 20       | 5.88%   |
| Other                  | 18       | 5.29%   |
| Intel Xeon             | 16       | 4.71%   |
| AMD FX                 | 10       | 2.94%   |
| Intel Pentium          | 9        | 2.65%   |
| AMD Ryzen 3            | 8        | 2.35%   |
| Intel Core 2 Duo       | 6        | 1.76%   |
| Intel Core i9          | 5        | 1.47%   |
| Intel Celeron          | 5        | 1.47%   |
| Intel Core 2 Quad      | 4        | 1.18%   |
| AMD A6                 | 4        | 1.18%   |
| AMD Ryzen Threadripper | 3        | 0.88%   |
| AMD Ryzen 7 PRO        | 3        | 0.88%   |
| AMD Phenom II X4       | 3        | 0.88%   |
| AMD Athlon 64 X2       | 3        | 0.88%   |
| AMD A8                 | 3        | 0.88%   |
| Intel Pentium Gold     | 2        | 0.59%   |
| AMD Phenom II X2       | 2        | 0.59%   |
| AMD Opteron            | 2        | 0.59%   |
| AMD Athlon II X2       | 2        | 0.59%   |
| AMD A10                | 2        | 0.59%   |
| AMD PRO A10            | 1        | 0.29%   |
| AMD Phenom II X6       | 1        | 0.29%   |
| AMD Phenom             | 1        | 0.29%   |
| AMD E1                 | 1        | 0.29%   |
| AMD A4                 | 1        | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 126      | 37.06%  |
| 6       | 71       | 20.88%  |
| 2       | 57       | 16.76%  |
| 8       | 46       | 13.53%  |
| 16      | 14       | 4.12%   |
| 12      | 12       | 3.53%   |
| 1       | 4        | 1.18%   |
| 10      | 3        | 0.88%   |
| 24      | 2        | 0.59%   |
| 3       | 2        | 0.59%   |
| 36      | 1        | 0.29%   |
| 14      | 1        | 0.29%   |
| Unknown | 1        | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 336      | 98.82%  |
| 2       | 3        | 0.88%   |
| Unknown | 1        | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 239      | 70.09%  |
| 1       | 101      | 29.62%  |
| Unknown | 1        | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 339      | 99.71%  |
| Unknown        | 1        | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 151      | 43.77%  |
| 0x306c3    | 19       | 5.51%   |
| 0x08701021 | 13       | 3.77%   |
| 0x506e3    | 9        | 2.61%   |
| 0x306a9    | 8        | 2.32%   |
| 0x0800820d | 8        | 2.32%   |
| 0xa0653    | 7        | 2.03%   |
| 0x906e9    | 7        | 2.03%   |
| 0x906ed    | 6        | 1.74%   |
| 0x90672    | 6        | 1.74%   |
| 0x0a50000c | 6        | 1.74%   |
| 0xa0655    | 5        | 1.45%   |
| 0x906ea    | 5        | 1.45%   |
| 0x206a7    | 5        | 1.45%   |
| 0x1067a    | 5        | 1.45%   |
| 0x0a201205 | 5        | 1.45%   |
| 0x010000c8 | 5        | 1.45%   |
| 0x406f1    | 4        | 1.16%   |
| 0x0a201016 | 4        | 1.16%   |
| 0x306f2    | 3        | 0.87%   |
| 0x306e4    | 3        | 0.87%   |
| 0x206d7    | 3        | 0.87%   |
| 0x0a601203 | 3        | 0.87%   |
| 0x08001138 | 3        | 0.87%   |
| 0x08001137 | 3        | 0.87%   |
| 0x0600611a | 3        | 0.87%   |
| 0x06000852 | 3        | 0.87%   |
| 0xb0671    | 2        | 0.58%   |
| 0xa0671    | 2        | 0.58%   |
| 0x106e5    | 2        | 0.58%   |
| 0x106a5    | 2        | 0.58%   |
| 0x0a50000d | 2        | 0.58%   |
| 0x0a20120a | 2        | 0.58%   |
| 0x0a201204 | 2        | 0.58%   |
| 0x0a201009 | 2        | 0.58%   |
| 0x08600106 | 2        | 0.58%   |
| 0x08001126 | 2        | 0.58%   |
| 0x06001119 | 2        | 0.58%   |
| 0x06000822 | 2        | 0.58%   |
| 0x906ec    | 1        | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 47       | 13.78%  |
| Zen 3            | 36       | 10.56%  |
| KabyLake         | 34       | 9.97%   |
| IvyBridge        | 29       | 8.5%    |
| Zen 2            | 24       | 7.04%   |
| Zen+             | 19       | 5.57%   |
| Zen              | 18       | 5.28%   |
| CometLake        | 17       | 4.99%   |
| Piledriver       | 15       | 4.4%    |
| Skylake          | 14       | 4.11%   |
| SandyBridge      | 14       | 4.11%   |
| Unknown          | 14       | 4.11%   |
| K10              | 10       | 2.93%   |
| Penryn           | 9        | 2.64%   |
| Nehalem          | 7        | 2.05%   |
| Excavator        | 6        | 1.76%   |
| Alderlake Hybrid | 6        | 1.76%   |
| Broadwell        | 5        | 1.47%   |
| Westmere         | 3        | 0.88%   |
| K8 Hammer        | 3        | 0.88%   |
| Core             | 3        | 0.88%   |
| Icelake          | 2        | 0.59%   |
| Steamroller      | 1        | 0.29%   |
| Silvermont       | 1        | 0.29%   |
| Puma             | 1        | 0.29%   |
| K10 Llano        | 1        | 0.29%   |
| Goldmont plus    | 1        | 0.29%   |
| Goldmont         | 1        | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 166      | 44.5%   |
| AMD                        | 122      | 32.71%  |
| Intel                      | 81       | 21.72%  |
| Matrox Electronics Systems | 3        | 0.8%    |
| ASPEED Technology          | 1        | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 19       | 5.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 15       | 3.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 3.97%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 2.65%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 8        | 2.12%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 8        | 2.12%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 7        | 1.85%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.85%   |
| Intel HD Graphics 530                                                       | 7        | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7        | 1.85%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 1.85%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.59%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.32%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 1.32%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.32%   |
| Intel HD Graphics 630                                                       | 5        | 1.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.32%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1.06%   |
| AMD RS780L [Radeon 3000]                                                    | 4        | 1.06%   |
| AMD Renoir                                                                  | 4        | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.06%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1.06%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1.06%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1.06%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 4        | 1.06%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 1.06%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.79%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 3        | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.79%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.79%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 0.79%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3        | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 0.79%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 0.79%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.79%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 3        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 158      | 46.33%  |
| 1 x AMD                  | 110      | 32.26%  |
| 1 x Intel                | 54       | 15.84%  |
| 2 x AMD                  | 4        | 1.17%   |
| Intel + Nvidia           | 3        | 0.88%   |
| Intel + AMD              | 3        | 0.88%   |
| 2 x Nvidia               | 2        | 0.59%   |
| AMD + Matrox             | 2        | 0.59%   |
| Other                    | 1        | 0.29%   |
| Nvidia + Matrox          | 1        | 0.29%   |
| Nvidia + ASPEED          | 1        | 0.29%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.29%   |
| AMD + Nvidia             | 1        | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 204      | 59.65%  |
| Proprietary | 124      | 36.26%  |
| Unknown     | 14       | 4.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 150      | 43.23%  |
| 1.01-2.0   | 45       | 12.97%  |
| 7.01-8.0   | 36       | 10.37%  |
| 3.01-4.0   | 35       | 10.09%  |
| 0.51-1.0   | 27       | 7.78%   |
| 5.01-6.0   | 18       | 5.19%   |
| 0.01-0.5   | 18       | 5.19%   |
| 8.01-16.0  | 13       | 3.75%   |
| 16.01-24.0 | 3        | 0.86%   |
| 4.01-5.0   | 1        | 0.29%   |
| 2.01-3.0   | 1        | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 76       | 19%     |
| Dell                 | 48       | 12%     |
| Goldstar             | 46       | 11.5%   |
| Hewlett-Packard      | 28       | 7%      |
| Acer                 | 24       | 6%      |
| Philips              | 22       | 5.5%    |
| BenQ                 | 20       | 5%      |
| AOC                  | 20       | 5%      |
| Iiyama               | 14       | 3.5%    |
| Ancor Communications | 14       | 3.5%    |
| ASUSTek Computer     | 11       | 2.75%   |
| Sony                 | 7        | 1.75%   |
| ViewSonic            | 5        | 1.25%   |
| Vizio                | 3        | 0.75%   |
| NEC Computers        | 3        | 0.75%   |
| LG Electronics       | 3        | 0.75%   |
| Idek Iiyama          | 3        | 0.75%   |
| Eizo                 | 3        | 0.75%   |
| Xiaomi               | 2        | 0.5%    |
| Vestel Elektronik    | 2        | 0.5%    |
| Planar               | 2        | 0.5%    |
| Mi                   | 2        | 0.5%    |
| Gigabyte Technology  | 2        | 0.5%    |
| Fujitsu Siemens      | 2        | 0.5%    |
| DTV                  | 2        | 0.5%    |
| Denver               | 2        | 0.5%    |
| Unknown              | 2        | 0.5%    |
| Vita                 | 1        | 0.25%   |
| Unknown              | 1        | 0.25%   |
| TXD                  | 1        | 0.25%   |
| Sunplus              | 1        | 0.25%   |
| STD                  | 1        | 0.25%   |
| Sceptre Tech         | 1        | 0.25%   |
| RTK                  | 1        | 0.25%   |
| QUS                  | 1        | 0.25%   |
| Pixio                | 1        | 0.25%   |
| PAR                  | 1        | 0.25%   |
| Panasonic            | 1        | 0.25%   |
| ONKYO                | 1        | 0.25%   |
| MVD                  | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 4        | 0.94%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4        | 0.94%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3        | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3        | 0.71%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                | 3        | 0.71%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 3        | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2        | 0.47%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch  | 2        | 0.47%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 2        | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 0.47%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 950x540mm 43.0-inch | 2        | 0.47%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch    | 2        | 0.47%   |
| Planar PLL2710W PLN2710 1920x1080 597x336mm 27.0-inch                 | 2        | 0.47%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 521x293mm 23.5-inch               | 2        | 0.47%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 2        | 0.47%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                | 2        | 0.47%   |
| Iiyama PLG2888UH IVM710B 3840x2160                                    | 2        | 0.47%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch             | 2        | 0.47%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch            | 2        | 0.47%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 2        | 0.47%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 2        | 0.47%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 2        | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2        | 0.47%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch                | 2        | 0.47%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                 | 2        | 0.47%   |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                    | 2        | 0.47%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                     | 2        | 0.47%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                     | 2        | 0.47%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                     | 2        | 0.47%   |
| Dell 2408WFP DELA02B 1920x1200 519x320mm 24.0-inch                    | 2        | 0.47%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 2        | 0.47%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 2        | 0.47%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                     | 2        | 0.47%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                     | 2        | 0.47%   |
| Unknown                                                               | 2        | 0.47%   |
| Xiaomi Mi TV XMD00E2 3840x2160 800x450mm 36.1-inch                    | 1        | 0.24%   |
| Xiaomi Mi TV XMD009A 3440x1440 480x270mm 21.7-inch                    | 1        | 0.24%   |
| Vizio VX32L HDTV10A VIZ0021 1366x768 700x390mm 31.5-inch              | 1        | 0.24%   |
| Vizio M50Q7-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                  | 1        | 0.24%   |
| Vizio D32hn-E0 VIZ1007 1366x768 698x392mm 31.5-inch                   | 1        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 179      | 47.61%  |
| 3840x2160 (4K)     | 44       | 11.7%   |
| 2560x1440 (QHD)    | 24       | 6.38%   |
| 1680x1050 (WSXGA+) | 23       | 6.12%   |
| 1920x1200 (WUXGA)  | 21       | 5.59%   |
| 1280x1024 (SXGA)   | 15       | 3.99%   |
| 1366x768 (WXGA)    | 13       | 3.46%   |
| 3440x1440          | 12       | 3.19%   |
| 2560x1080          | 6        | 1.6%    |
| 1600x900 (HD+)     | 5        | 1.33%   |
| 1440x900 (WXGA+)   | 5        | 1.33%   |
| 1360x768           | 5        | 1.33%   |
| Unknown            | 5        | 1.33%   |
| 3840x1080          | 4        | 1.06%   |
| 1280x720 (HD)      | 2        | 0.53%   |
| 6160x1440          | 1        | 0.27%   |
| 5760x2160          | 1        | 0.27%   |
| 5760x1080          | 1        | 0.27%   |
| 480x1920           | 1        | 0.27%   |
| 4800x1080          | 1        | 0.27%   |
| 3840x1600          | 1        | 0.27%   |
| 3840x1200          | 1        | 0.27%   |
| 3600x1200          | 1        | 0.27%   |
| 2288x1287          | 1        | 0.27%   |
| 1920x540           | 1        | 0.27%   |
| 1600x1200          | 1        | 0.27%   |
| 1280x768           | 1        | 0.27%   |
| 1024x768 (XGA)     | 1        | 0.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 71       | 18.07%  |
| 23      | 58       | 14.76%  |
| 27      | 55       | 13.99%  |
| 21      | 46       | 11.7%   |
| 31      | 23       | 5.85%   |
| Unknown | 21       | 5.34%   |
| 34      | 16       | 4.07%   |
| 19      | 15       | 3.82%   |
| 22      | 14       | 3.56%   |
| 32      | 9        | 2.29%   |
| 18      | 9        | 2.29%   |
| 72      | 6        | 1.53%   |
| 84      | 4        | 1.02%   |
| 54      | 4        | 1.02%   |
| 46      | 4        | 1.02%   |
| 40      | 4        | 1.02%   |
| 20      | 4        | 1.02%   |
| 17      | 4        | 1.02%   |
| 36      | 3        | 0.76%   |
| 25      | 3        | 0.76%   |
| 65      | 2        | 0.51%   |
| 48      | 2        | 0.51%   |
| 28      | 2        | 0.51%   |
| 15      | 2        | 0.51%   |
| 142     | 1        | 0.25%   |
| 69      | 1        | 0.25%   |
| 60      | 1        | 0.25%   |
| 55      | 1        | 0.25%   |
| 49      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 42      | 1        | 0.25%   |
| 38      | 1        | 0.25%   |
| 37      | 1        | 0.25%   |
| 35      | 1        | 0.25%   |
| 33      | 1        | 0.25%   |
| 26      | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 156      | 41.71%  |
| 401-500        | 81       | 21.66%  |
| 601-700        | 37       | 9.89%   |
| 701-800        | 29       | 7.75%   |
| Unknown        | 21       | 5.61%   |
| 1001-1500      | 15       | 4.01%   |
| 1501-2000      | 11       | 2.94%   |
| 351-400        | 8        | 2.14%   |
| 801-900        | 7        | 1.87%   |
| 301-350        | 6        | 1.6%    |
| 901-1000       | 2        | 0.53%   |
| More than 2000 | 1        | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 242      | 70.76%  |
| 16/10   | 45       | 13.16%  |
| 21/9    | 18       | 5.26%   |
| Unknown | 16       | 4.68%   |
| 5/4     | 12       | 3.51%   |
| 32/9    | 3        | 0.88%   |
| 3/2     | 3        | 0.88%   |
| 4/3     | 1        | 0.29%   |
| 1.00    | 1        | 0.29%   |
| 0.25    | 1        | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 137      | 36.15%  |
| 301-350        | 56       | 14.78%  |
| 351-500        | 51       | 13.46%  |
| 151-200        | 34       | 8.97%   |
| 251-300        | 28       | 7.39%   |
| Unknown        | 21       | 5.54%   |
| More than 1000 | 20       | 5.28%   |
| 501-1000       | 18       | 4.75%   |
| 141-150        | 12       | 3.17%   |
| 101-110        | 2        | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 211      | 59.94%  |
| 101-120 | 66       | 18.75%  |
| 1-50    | 25       | 7.1%    |
| 121-160 | 23       | 6.53%   |
| Unknown | 21       | 5.97%   |
| 161-240 | 6        | 1.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 225      | 65.22%  |
| 2     | 93       | 26.96%  |
| 0     | 16       | 4.64%   |
| 3     | 8        | 2.32%   |
| 4     | 3        | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 207      | 40.75%  |
| Intel                           | 164      | 32.28%  |
| Qualcomm Atheros                | 31       | 6.1%    |
| Broadcom                        | 17       | 3.35%   |
| Ralink Technology               | 13       | 2.56%   |
| Aquantia                        | 10       | 1.97%   |
| TP-Link                         | 8        | 1.57%   |
| Ralink                          | 7        | 1.38%   |
| MediaTek                        | 6        | 1.18%   |
| Samsung Electronics             | 4        | 0.79%   |
| Huawei Technologies             | 4        | 0.79%   |
| Qualcomm Atheros Communications | 3        | 0.59%   |
| D-Link                          | 3        | 0.59%   |
| ASIX Electronics                | 3        | 0.59%   |
| Xiaomi                          | 2        | 0.39%   |
| VIA Technologies                | 2        | 0.39%   |
| Nvidia                          | 2        | 0.39%   |
| NetGear                         | 2        | 0.39%   |
| Edimax Technology               | 2        | 0.39%   |
| Belkin Components               | 2        | 0.39%   |
| ASUSTek Computer                | 2        | 0.39%   |
| ZyXEL Communications            | 1        | 0.2%    |
| Wilocity                        | 1        | 0.2%    |
| U-Blox                          | 1        | 0.2%    |
| Seeed Technology                | 1        | 0.2%    |
| Qualcomm                        | 1        | 0.2%    |
| Microsoft                       | 1        | 0.2%    |
| Mercucys                        | 1        | 0.2%    |
| LSI                             | 1        | 0.2%    |
| Linksys                         | 1        | 0.2%    |
| LG Electronics                  | 1        | 0.2%    |
| DisplayLink                     | 1        | 0.2%    |
| D-Link System                   | 1        | 0.2%    |
| Bose                            | 1        | 0.2%    |
| Arduino SA                      | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 156      | 26.58%  |
| Intel I211 Gigabit Network Connection                             | 24       | 4.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21       | 3.58%   |
| Intel Wi-Fi 6 AX200                                               | 21       | 3.58%   |
| Intel Ethernet Controller I225-V                                  | 21       | 3.58%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.87%   |
| Intel Ethernet Connection (2) I219-V                              | 11       | 1.87%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 1.7%    |
| Intel Ethernet Connection (2) I218-V                              | 10       | 1.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 1.53%   |
| Realtek 802.11ac NIC                                              | 8        | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8        | 1.36%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.19%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.19%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 1.02%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 1.02%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6        | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.68%   |
| Ralink RT5370 Wireless Adapter                                    | 4        | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 0.68%   |
| Intel Wireless-AC 9260                                            | 4        | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 4        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3        | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3        | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.51%   |
| Intel Wireless 7260                                               | 3        | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 64       | 33.33%  |
| Realtek Semiconductor           | 45       | 23.44%  |
| Qualcomm Atheros                | 16       | 8.33%   |
| Ralink Technology               | 13       | 6.77%   |
| Broadcom                        | 13       | 6.77%   |
| TP-Link                         | 8        | 4.17%   |
| Ralink                          | 7        | 3.65%   |
| MediaTek                        | 5        | 2.6%    |
| Qualcomm Atheros Communications | 3        | 1.56%   |
| D-Link                          | 3        | 1.56%   |
| NetGear                         | 2        | 1.04%   |
| Edimax Technology               | 2        | 1.04%   |
| Belkin Components               | 2        | 1.04%   |
| ASUSTek Computer                | 2        | 1.04%   |
| ZyXEL Communications            | 1        | 0.52%   |
| Wilocity                        | 1        | 0.52%   |
| Microsoft                       | 1        | 0.52%   |
| Mercucys                        | 1        | 0.52%   |
| Linksys                         | 1        | 0.52%   |
| LG Electronics                  | 1        | 0.52%   |
| D-Link System                   | 1        | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 21       | 10.66%  |
| Realtek 802.11ac NIC                                       | 8        | 4.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 8        | 4.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 6        | 3.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 6        | 3.05%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 6        | 3.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 5        | 2.54%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 5        | 2.54%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 4        | 2.03%   |
| Ralink RT5370 Wireless Adapter                             | 4        | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 4        | 2.03%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 4        | 2.03%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 4        | 2.03%   |
| Intel Wireless-AC 9260                                     | 4        | 2.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 3        | 1.52%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 3        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3        | 1.52%   |
| Qualcomm Atheros AR9271 802.11n                            | 3        | 1.52%   |
| Intel Wireless 7260                                        | 3        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                             | 3        | 1.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 3        | 1.52%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 1.02%   |
| TP-Link 802.11ac NIC                                       | 2        | 1.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 2        | 1.02%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 2        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 2        | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2        | 1.02%   |
| Ralink MT7601U Wireless Adapter                            | 2        | 1.02%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 2        | 1.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2        | 1.02%   |
| Intel Wireless 8260                                        | 2        | 1.02%   |
| Intel Wireless 7265                                        | 2        | 1.02%   |
| Intel Wireless 3165                                        | 2        | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2        | 1.02%   |
| Broadcom Network controller                                | 2        | 1.02%   |
| ZyXEL ZyAIR G-202 802.11bg                                 | 1        | 0.51%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1        | 0.51%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1        | 0.51%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                 | 1        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 187      | 49.87%  |
| Intel                 | 137      | 36.53%  |
| Qualcomm Atheros      | 16       | 4.27%   |
| Aquantia              | 10       | 2.67%   |
| Broadcom              | 6        | 1.6%    |
| Huawei Technologies   | 4        | 1.07%   |
| Samsung Electronics   | 3        | 0.8%    |
| ASIX Electronics      | 3        | 0.8%    |
| Xiaomi                | 2        | 0.53%   |
| VIA Technologies      | 2        | 0.53%   |
| Nvidia                | 2        | 0.53%   |
| Qualcomm              | 1        | 0.27%   |
| MediaTek              | 1        | 0.27%   |
| DisplayLink           | 1        | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 156      | 40.63%  |
| Intel I211 Gigabit Network Connection                             | 24       | 6.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21       | 5.47%   |
| Intel Ethernet Controller I225-V                                  | 21       | 5.47%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 2.86%   |
| Intel Ethernet Connection (2) I219-V                              | 11       | 2.86%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.6%    |
| Intel Ethernet Connection (2) I218-V                              | 10       | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9        | 2.34%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7        | 1.82%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 1.56%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 1.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 1.04%   |
| Intel I210 Gigabit Network Connection                             | 4        | 1.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.78%   |
| Huawei WLZ-AN00                                                   | 3        | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.52%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.52%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.52%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.52%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.26%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.26%   |
| Qualcomm MDM9207-MTP _SN:A962C7E3                                 | 1        | 0.26%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.26%   |
| MediaTek Titan pocket                                             | 1        | 0.26%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 337      | 64.56%  |
| WiFi     | 180      | 34.48%  |
| Modem    | 5        | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 256      | 72.52%  |
| WiFi     | 97       | 27.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 198      | 58.24%  |
| 2     | 120      | 35.29%  |
| 3     | 18       | 5.29%   |
| 4     | 2        | 0.59%   |
| 6     | 1        | 0.29%   |
| 0     | 1        | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 238      | 69.39%  |
| Yes  | 105      | 30.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 60       | 39.22%  |
| Cambridge Silicon Radio         | 38       | 24.84%  |
| Realtek Semiconductor           | 15       | 9.8%    |
| ASUSTek Computer                | 12       | 7.84%   |
| MediaTek                        | 6        | 3.92%   |
| Broadcom                        | 6        | 3.92%   |
| Qualcomm Atheros Communications | 3        | 1.96%   |
| IMC Networks                    | 3        | 1.96%   |
| Edimax Technology               | 3        | 1.96%   |
| TP-Link                         | 2        | 1.31%   |
| Ralink                          | 1        | 0.65%   |
| Dynex                           | 1        | 0.65%   |
| D-Link                          | 1        | 0.65%   |
| Conwise Technology              | 1        | 0.65%   |
| Apple                           | 1        | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 38       | 24.68%  |
| Intel AX200 Bluetooth                                    | 21       | 13.64%  |
| Realtek Bluetooth Radio                                  | 12       | 7.79%   |
| Intel Bluetooth wireless interface                       | 8        | 5.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8        | 5.19%   |
| Intel Wireless-AC 3168 Bluetooth                         | 7        | 4.55%   |
| MediaTek Wireless_Device                                 | 6        | 3.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 5        | 3.25%   |
| Intel AX210 Bluetooth                                    | 5        | 3.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 5        | 3.25%   |
| Intel AX201 Bluetooth                                    | 4        | 2.6%    |
| ASUS ASUS USB-BT500                                      | 4        | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 1.95%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 1.95%   |
| Intel Bluetooth Device                                   | 3        | 1.95%   |
| IMC Networks Bluetooth Radio                             | 3        | 1.95%   |
| TP-Link UB500 Adapter                                    | 2        | 1.3%    |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 1.3%    |
| Ralink RT3290 Bluetooth                                  | 1        | 0.65%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter              | 1        | 0.65%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 1        | 0.65%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.65%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.65%   |
| D-Link DBT-122 Bluetooth adapter                         | 1        | 0.65%   |
| Conwise CW6622                                           | 1        | 0.65%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1        | 0.65%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.65%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.65%   |
| ASUS Bluetooth Radio                                     | 1        | 0.65%   |
| ASUS Bluetooth Device                                    | 1        | 0.65%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.65%   |
| ASUS BCM20702A0                                          | 1        | 0.65%   |
| Apple Bluetooth USB Host Controller                      | 1        | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 194      | 29.89%  |
| AMD                      | 177      | 27.27%  |
| Nvidia                   | 163      | 25.12%  |
| C-Media Electronics      | 17       | 2.62%   |
| GN Netcom                | 9        | 1.39%   |
| JMTek                    | 6        | 0.92%   |
| Creative Labs            | 6        | 0.92%   |
| Generalplus Technology   | 5        | 0.77%   |
| VIA Technologies         | 4        | 0.62%   |
| Micro Star International | 4        | 0.62%   |
| Logitech                 | 4        | 0.62%   |
| Kingston Technology      | 4        | 0.62%   |
| Texas Instruments        | 3        | 0.46%   |
| Tenx Technology          | 3        | 0.46%   |
| Razer USA                | 3        | 0.46%   |
| Blue Microphones         | 3        | 0.46%   |
| SteelSeries ApS          | 2        | 0.31%   |
| M-Audio                  | 2        | 0.31%   |
| KORG                     | 2        | 0.31%   |
| Focusrite-Novation       | 2        | 0.31%   |
| Corsair                  | 2        | 0.31%   |
| BY EDIFIER               | 2        | 0.31%   |
| ASUSTek Computer         | 2        | 0.31%   |
| ZOOM                     | 1        | 0.15%   |
| Yamaha                   | 1        | 0.15%   |
| Veho                     | 1        | 0.15%   |
| Unknown                  | 1        | 0.15%   |
| TerraTec Electronic      | 1        | 0.15%   |
| Samson Technologies      | 1        | 0.15%   |
| Roland                   | 1        | 0.15%   |
| RME                      | 1        | 0.15%   |
| QinHeng Electronics      | 1        | 0.15%   |
| Philips (or NXP)         | 1        | 0.15%   |
| Nordic Semiconductor ASA | 1        | 0.15%   |
| Microsoft                | 1        | 0.15%   |
| Microdia                 | 1        | 0.15%   |
| Medeli Electronics       | 1        | 0.15%   |
| Mark of the Unicorn      | 1        | 0.15%   |
| Lenovo                   | 1        | 0.15%   |
| Jieli Technology         | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 45       | 5.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 28       | 3.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27       | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26       | 3.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21       | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20       | 2.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 2.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18       | 2.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17       | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 2.25%   |
| Intel 200 Series PCH HD Audio                                              | 16       | 2.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15       | 1.99%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15       | 1.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15       | 1.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 1.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 1.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13       | 1.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 12       | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 11       | 1.46%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10       | 1.32%   |
| Nvidia GP104 High Definition Audio Controller                              | 9        | 1.19%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 1.19%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 9        | 1.19%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9        | 1.19%   |
| Nvidia GP108 High Definition Audio Controller                              | 8        | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 1.06%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7        | 0.93%   |
| Nvidia TU104 HD Audio Controller                                           | 7        | 0.93%   |
| Nvidia High Definition Audio Controller                                    | 7        | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 0.93%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6        | 0.79%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 0.79%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                     | 6        | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 5        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 54       | 23.68%  |
| Corsair             | 38       | 16.67%  |
| G.Skill             | 28       | 12.28%  |
| Unknown             | 20       | 8.77%   |
| Crucial             | 17       | 7.46%   |
| Samsung Electronics | 16       | 7.02%   |
| Micron Technology   | 10       | 4.39%   |
| SK hynix            | 9        | 3.95%   |
| Team                | 6        | 2.63%   |
| Ramaxel Technology  | 4        | 1.75%   |
| Patriot             | 4        | 1.75%   |
| PNY                 | 3        | 1.32%   |
| AMD                 | 3        | 1.32%   |
| Unknown             | 3        | 1.32%   |
| Unknown (ABCD)      | 1        | 0.44%   |
| Unifosa             | 1        | 0.44%   |
| Teikon              | 1        | 0.44%   |
| Smart               | 1        | 0.44%   |
| Silicon Power       | 1        | 0.44%   |
| Qumo                | 1        | 0.44%   |
| Neo Forza           | 1        | 0.44%   |
| Nanya Technology    | 1        | 0.44%   |
| Lexar               | 1        | 0.44%   |
| Kingmax             | 1        | 0.44%   |
| Avant               | 1        | 0.44%   |
| Atermiter           | 1        | 0.44%   |
| A-DATA Technology   | 1        | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 5        | 1.95%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 3        | 1.17%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s | 3        | 1.17%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s | 3        | 1.17%   |
| Unknown                                                | 3        | 1.17%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 2        | 0.78%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s  | 2        | 0.78%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s     | 2        | 0.78%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2667MT/s  | 2        | 0.78%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 2        | 0.78%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 2        | 0.78%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s    | 2        | 0.78%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s  | 2        | 0.78%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s    | 2        | 0.78%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s         | 2        | 0.78%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s     | 2        | 0.78%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.78%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.78%   |
| Kingston RAM 9905471-079.A00LF 8GB DIMM DDR3 1600MT/s  | 2        | 0.78%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 2        | 0.78%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 0.78%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s   | 2        | 0.78%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s    | 2        | 0.78%   |
| G.Skill RAM F4-2133C15-8GVR 8GB DIMM DDR4 2133MT/s     | 2        | 0.78%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1867MT/s      | 2        | 0.78%   |
| Crucial RAM CT8G4DFRA266.C8FE 8GB DIMM DDR4 2933MT/s   | 2        | 0.78%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s  | 2        | 0.78%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s | 2        | 0.78%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s  | 2        | 0.78%   |
| AMD RAM R9S48G3206U2S 8GB DIMM DDR4 3333MT/s           | 2        | 0.78%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM 400MT/s                    | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s              | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR2 266MT/s               | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s               | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM 667MT/s                    | 1        | 0.39%   |
| Unknown RAM Module 4GB DIMM 400MT/s                    | 1        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 124      | 59.33%  |
| DDR3    | 55       | 26.32%  |
| Unknown | 10       | 4.78%   |
| DDR5    | 8        | 3.83%   |
| SDRAM   | 5        | 2.39%   |
| DDR2    | 5        | 2.39%   |
| LPDDR4  | 1        | 0.48%   |
| DDR     | 1        | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 198      | 96.12%  |
| SODIMM | 7        | 3.4%    |
| RIMM   | 1        | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 94       | 41.59%  |
| 16384 | 54       | 23.89%  |
| 4096  | 39       | 17.26%  |
| 2048  | 21       | 9.29%   |
| 32768 | 17       | 7.52%   |
| 1024  | 1        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 37       | 15.88%  |
| 3600  | 25       | 10.73%  |
| 3200  | 22       | 9.44%   |
| 1333  | 20       | 8.58%   |
| 2667  | 17       | 7.3%    |
| 2400  | 16       | 6.87%   |
| 2133  | 12       | 5.15%   |
| 3800  | 7        | 3%      |
| 3000  | 6        | 2.58%   |
| 2666  | 6        | 2.58%   |
| 1867  | 5        | 2.15%   |
| 3066  | 4        | 1.72%   |
| 2933  | 4        | 1.72%   |
| 1066  | 4        | 1.72%   |
| 4800  | 3        | 1.29%   |
| 3666  | 3        | 1.29%   |
| 3333  | 3        | 1.29%   |
| 2800  | 3        | 1.29%   |
| 1866  | 3        | 1.29%   |
| 400   | 3        | 1.29%   |
| 6000  | 2        | 0.86%   |
| 3866  | 2        | 0.86%   |
| 3266  | 2        | 0.86%   |
| 800   | 2        | 0.86%   |
| 52217 | 1        | 0.43%   |
| 5808  | 1        | 0.43%   |
| 5800  | 1        | 0.43%   |
| 5200  | 1        | 0.43%   |
| 4133  | 1        | 0.43%   |
| 4000  | 1        | 0.43%   |
| 3933  | 1        | 0.43%   |
| 3733  | 1        | 0.43%   |
| 3533  | 1        | 0.43%   |
| 3500  | 1        | 0.43%   |
| 3467  | 1        | 0.43%   |
| 3466  | 1        | 0.43%   |
| 3400  | 1        | 0.43%   |
| 3334  | 1        | 0.43%   |
| 2448  | 1        | 0.43%   |
| 2176  | 1        | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 8        | 33.33%  |
| Seiko Epson         | 4        | 16.67%  |
| Brother Industries  | 3        | 12.5%   |
| Samsung Electronics | 2        | 8.33%   |
| Canon               | 2        | 8.33%   |
| Xerox               | 1        | 4.17%   |
| Prolific Technology | 1        | 4.17%   |
| Kyocera             | 1        | 4.17%   |
| Dymo-CoStar         | 1        | 4.17%   |
| Datamax-O'Neil      | 1        | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| Seiko Epson L360 Series               | 2        | 8.33%   |
| Samsung M2070 Series                  | 2        | 8.33%   |
| Brother MFC-J460DW                    | 2        | 8.33%   |
| Xerox Phaser 3140 and 3155            | 1        | 4.17%   |
| Seiko Epson XP-3100 Series            | 1        | 4.17%   |
| Seiko Epson L3110 Series              | 1        | 4.17%   |
| Prolific PL2305 Parallel Port         | 1        | 4.17%   |
| Kyocera Mita FS-820                   | 1        | 4.17%   |
| HP OfficeJet 5500 series              | 1        | 4.17%   |
| HP LaserJet P2015 series              | 1        | 4.17%   |
| HP LaserJet 1022                      | 1        | 4.17%   |
| HP LaserJet 1012                      | 1        | 4.17%   |
| HP ENVY 4500 series                   | 1        | 4.17%   |
| HP DeskJet D2300                      | 1        | 4.17%   |
| HP DeskJet 3630 series                | 1        | 4.17%   |
| HP ColorLaserJet M253-M254            | 1        | 4.17%   |
| Dymo-CoStar LabelWriter 450           | 1        | 4.17%   |
| Datamax-O'Neil Datamax E-4304         | 1        | 4.17%   |
| Canon PIXMA MX470 Series              | 1        | 4.17%   |
| Canon LaserShot LBP-1120 Printer      | 1        | 4.17%   |
| Brother PT-P700 P-touch Label Printer | 1        | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 5        | 71.43%  |
| Seiko Epson    | 1        | 14.29%  |
| Mustek Systems | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2        | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1        | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1        | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 210                     | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 37       | 43.53%  |
| Microdia                      | 8        | 9.41%   |
| Generalplus Technology        | 5        | 5.88%   |
| Samsung Electronics           | 4        | 4.71%   |
| Sunplus Innovation Technology | 3        | 3.53%   |
| Microsoft                     | 3        | 3.53%   |
| KYE Systems (Mouse Systems)   | 3        | 3.53%   |
| Unknown                       | 2        | 2.35%   |
| Realtek Semiconductor         | 2        | 2.35%   |
| Jieli Technology              | 2        | 2.35%   |
| ARC International             | 2        | 2.35%   |
| Alcor Micro                   | 2        | 2.35%   |
| YGTek                         | 1        | 1.18%   |
| Sunplus IT                    | 1        | 1.18%   |
| Sonix Technology              | 1        | 1.18%   |
| Silicon Motion                | 1        | 1.18%   |
| Razer USA                     | 1        | 1.18%   |
| LG Electronics                | 1        | 1.18%   |
| IMC Networks                  | 1        | 1.18%   |
| Hewlett-Packard               | 1        | 1.18%   |
| Google                        | 1        | 1.18%   |
| Cubeternet                    | 1        | 1.18%   |
| Creative Technology           | 1        | 1.18%   |
| Asuscom Network               | 1        | 1.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 8        | 9.3%    |
| Logitech HD Pro Webcam C920                | 8        | 9.3%    |
| Samsung Galaxy series, misc. (MTP mode)    | 4        | 4.65%   |
| Logitech C920 PRO HD Webcam                | 4        | 4.65%   |
| Microdia Integrated Camera                 | 3        | 3.49%   |
| Logitech C922 Pro Stream Webcam            | 3        | 3.49%   |
| Unknown HD camera                          | 2        | 2.33%   |
| Microdia Webcam Vitade AF                  | 2        | 2.33%   |
| Logitech Webcam C170                       | 2        | 2.33%   |
| Logitech HD Webcam C910                    | 2        | 2.33%   |
| Logitech HD Webcam C525                    | 2        | 2.33%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera | 2        | 2.33%   |
| Jieli USB PHY 2.0                          | 2        | 2.33%   |
| Generalplus WEB CAM                        | 2        | 2.33%   |
| Generalplus GENERAL WEBCAM                 | 2        | 2.33%   |
| ARC International Camera                   | 2        | 2.33%   |
| Alcor Micro USB 2.0 PC Camera              | 2        | 2.33%   |
| YGTek Webcam                               | 1        | 1.16%   |
| Sunplus IT 1080P Webcam                    | 1        | 1.16%   |
| Sunplus UC40M Audio                        | 1        | 1.16%   |
| Sunplus SPCA2281 Web Camera                | 1        | 1.16%   |
| Sunplus ezcap U3 capture-04                | 1        | 1.16%   |
| Sonix USB 2.0 Camera                       | 1        | 1.16%   |
| Silicon Motion 300k Pixel Camera           | 1        | 1.16%   |
| Realtek USB Camera                         | 1        | 1.16%   |
| Realtek Realtek USB MIC                    | 1        | 1.16%   |
| Realtek HK 2M CAM                          | 1        | 1.16%   |
| Razer USA Razer Kiyo Pro                   | 1        | 1.16%   |
| Microsoft MicrosoftÂ LifeCam Studio       | 1        | 1.16%   |
| Microsoft LifeCam HD-3000                  | 1        | 1.16%   |
| Microsoft LifeCam Cinema                   | 1        | 1.16%   |
| Microdia USB 2.0 Camera                    | 1        | 1.16%   |
| Microdia PC Microscope camera              | 1        | 1.16%   |
| Microdia Camera                            | 1        | 1.16%   |
| Logitech Webcam C600                       | 1        | 1.16%   |
| Logitech Webcam C310                       | 1        | 1.16%   |
| Logitech Webcam C300                       | 1        | 1.16%   |
| Logitech QuickCam Pro for Notebooks        | 1        | 1.16%   |
| Logitech QuickCam Pro 9000                 | 1        | 1.16%   |
| Logitech QuickCam Communicate MP/S5500     | 1        | 1.16%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Synaptics             | 2        | 66.67%  |
| LighTuning Technology | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 2        | 66.67%  |
| LighTuning Fingerprint Sensor                | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 25%     |
| OmniKey               | 1        | 25%     |
| Gemalto (was Gemplus) | 1        | 25%     |
| BIT4ID                | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 25%     |
| OmniKey CardMan 1021                              | 1        | 25%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 25%     |
| BIT4ID miniLector EVO                             | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 279      | 80.17%  |
| 1     | 58       | 16.67%  |
| 2     | 8        | 2.3%    |
| 3     | 3        | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 22       | 27.85%  |
| Net/wireless             | 21       | 26.58%  |
| Unassigned class         | 11       | 13.92%  |
| Multimedia controller    | 4        | 5.06%   |
| Camera                   | 4        | 5.06%   |
| Bluetooth                | 4        | 5.06%   |
| Fingerprint reader       | 3        | 3.8%    |
| Communication controller | 3        | 3.8%    |
| Chipcard                 | 3        | 3.8%    |
| Sound                    | 2        | 2.53%   |
| Net/ethernet             | 1        | 1.27%   |
| Modem                    | 1        | 1.27%   |

