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

Total: 495

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Alienware     | 0H869M A00                  | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| Gigabyte      | H510M H                     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| Gigabyte      | H310M H                     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| HP            | 212B                        | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| ASUSTek       | Pro WS 565-ACE              | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| HP            | 18E7                        | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| Dell          | 0D881F A05                  | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| MSI           | B250M MORTAR                | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| ASRock        | Z77 Extreme4                | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| Dell          | 0D881F A05                  | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
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


| Version              | Desktops | Percent |
|----------------------|----------|---------|
| 5.15.0-56-generic    | 22       | 5.56%   |
| 5.15.0-52-generic    | 19       | 4.8%    |
| 5.15.0-43-generic    | 19       | 4.8%    |
| 5.15.0-48-generic    | 14       | 3.54%   |
| 5.15.0-67-generic    | 13       | 3.28%   |
| 5.15.0-46-generic    | 13       | 3.28%   |
| 5.19.0-35-generic    | 12       | 3.03%   |
| 5.15.0-47-generic    | 12       | 3.03%   |
| 5.15.0-27-generic    | 12       | 3.03%   |
| 5.15.0-58-generic    | 11       | 2.78%   |
| 5.15.0-40-generic    | 11       | 2.78%   |
| 5.15.0-41-generic    | 10       | 2.53%   |
| 5.19.0-38-generic    | 9        | 2.27%   |
| 5.15.0-75-generic    | 9        | 2.27%   |
| 5.15.0-69-generic    | 9        | 2.27%   |
| 5.15.0-53-generic    | 9        | 2.27%   |
| 5.15.0-25-generic    | 9        | 2.27%   |
| 6.2.0-26-generic     | 8        | 2.02%   |
| 5.15.0-78-generic    | 8        | 2.02%   |
| 5.15.0-60-generic    | 8        | 2.02%   |
| 5.19.0-46-generic    | 7        | 1.77%   |
| 5.19.0-41-generic    | 7        | 1.77%   |
| 5.15.0-73-generic    | 7        | 1.77%   |
| 5.15.0-50-generic    | 7        | 1.77%   |
| 5.15.0-72-generic    | 6        | 1.52%   |
| 5.15.0-71-generic    | 6        | 1.52%   |
| 5.15.0-30-generic    | 6        | 1.52%   |
| 5.19.0-42-generic    | 5        | 1.26%   |
| 5.15.0-79-generic    | 5        | 1.26%   |
| 5.15.0-48-lowlatency | 5        | 1.26%   |
| 5.19.0-43-generic    | 4        | 1.01%   |
| 5.15.0-76-generic    | 4        | 1.01%   |
| 5.15.0-56-lowlatency | 4        | 1.01%   |
| 5.15.0-37-generic    | 4        | 1.01%   |
| 5.15.0-33-generic    | 4        | 1.01%   |
| 5.19.0-40-generic    | 3        | 0.76%   |
| 5.19.0-32-generic    | 3        | 0.76%   |
| 5.15.0-57-generic    | 3        | 0.76%   |
| 5.15.0-27-lowlatency | 3        | 0.76%   |
| 5.19.0-50-generic    | 2        | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 277      | 75.89%  |
| 5.19.0  | 52       | 14.25%  |
| 6.2.0   | 11       | 3.01%   |
| 5.17.0  | 4        | 1.1%    |
| 6.1.5   | 2        | 0.55%   |
| 5.18.4  | 2        | 0.55%   |
| 5.13.0  | 2        | 0.55%   |
| 6.4.10  | 1        | 0.27%   |
| 6.4.0   | 1        | 0.27%   |
| 6.3.6   | 1        | 0.27%   |
| 6.1.1   | 1        | 0.27%   |
| 6.0.1   | 1        | 0.27%   |
| 6.0.0   | 1        | 0.27%   |
| 5.4.0   | 1        | 0.27%   |
| 5.19.12 | 1        | 0.27%   |
| 5.18.19 | 1        | 0.27%   |
| 5.18.12 | 1        | 0.27%   |
| 5.18.10 | 1        | 0.27%   |
| 5.17.6  | 1        | 0.27%   |
| 5.17.14 | 1        | 0.27%   |
| 5.16.0  | 1        | 0.27%   |
| 5.15.13 | 1        | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 278      | 76.16%  |
| 5.19    | 53       | 14.52%  |
| 6.2     | 11       | 3.01%   |
| 5.17    | 6        | 1.64%   |
| 5.18    | 5        | 1.37%   |
| 6.1     | 3        | 0.82%   |
| 6.4     | 2        | 0.55%   |
| 6.0     | 2        | 0.55%   |
| 5.13    | 2        | 0.55%   |
| 6.3     | 1        | 0.27%   |
| 5.4     | 1        | 0.27%   |
| 5.16    | 1        | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 357      | 99.72%  |
| riscv64 | 1        | 0.28%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| KDE5   | 354      | 98.88%  |
| GNOME  | 2        | 0.56%   |
| KDE    | 1        | 0.28%   |
| Budgie | 1        | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 341      | 95.25%  |
| Tty     | 9        | 2.51%   |
| Wayland | 7        | 1.96%   |
| Web     | 1        | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 244      | 67.59%  |
| Unknown | 82       | 22.71%  |
| GDM3    | 24       | 6.65%   |
| LightDM | 10       | 2.77%   |
| GDM     | 1        | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang                 | Desktops | Percent |
|----------------------|----------|---------|
| en_US                | 158      | 44.13%  |
| de_DE                | 32       | 8.94%   |
| fr_FR                | 27       | 7.54%   |
| ru_RU                | 19       | 5.31%   |
| en_GB                | 18       | 5.03%   |
| it_IT                | 17       | 4.75%   |
| pt_BR                | 13       | 3.63%   |
| en_AU                | 11       | 3.07%   |
| pl_PL                | 7        | 1.96%   |
| es_ES                | 6        | 1.68%   |
| nl_NL                | 4        | 1.12%   |
| en_CA                | 4        | 1.12%   |
| es_AR                | 3        | 0.84%   |
| en_PH                | 3        | 0.84%   |
| de_CH                | 3        | 0.84%   |
| C                    | 3        | 0.84%   |
| fi_FI                | 2        | 0.56%   |
| en_ZA                | 2        | 0.56%   |
| en_NZ                | 2        | 0.56%   |
| en_IN                | 2        | 0.56%   |
| el_GR                | 2        | 0.56%   |
| cs_CZ                | 2        | 0.56%   |
| الافتراضيّ | 1        | 0.28%   |
| zh_CN                | 1        | 0.28%   |
| sl_SI                | 1        | 0.28%   |
| pt_PT                | 1        | 0.28%   |
| osa_US               | 1        | 0.28%   |
| fr_CA                | 1        | 0.28%   |
| fr_BE                | 1        | 0.28%   |
| es_VE                | 1        | 0.28%   |
| es_PA                | 1        | 0.28%   |
| es_CO                | 1        | 0.28%   |
| en_IL                | 1        | 0.28%   |
| en_DE                | 1        | 0.28%   |
| en_CH                | 1        | 0.28%   |
| en_AG                | 1        | 0.28%   |
| de_LU                | 1        | 0.28%   |
| de_AT                | 1        | 0.28%   |
| da_DK                | 1        | 0.28%   |
| bg_BG                | 1        | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 205      | 57.1%   |
| EFI  | 154      | 42.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 312      | 86.19%  |
| Btrfs   | 18       | 4.97%   |
| Tmpfs   | 16       | 4.42%   |
| Overlay | 12       | 3.31%   |
| Xfs     | 3        | 0.83%   |
| Ext3    | 1        | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 214      | 58.95%  |
| Unknown | 112      | 30.85%  |
| MBR     | 37       | 10.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 300      | 82.42%  |
| Yes       | 64       | 17.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 222      | 62.01%  |
| Yes       | 136      | 37.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 101      | 28.21%  |
| Gigabyte Technology | 69       | 19.27%  |
| MSI                 | 52       | 14.53%  |
| ASRock              | 33       | 9.22%   |
| Dell                | 24       | 6.7%    |
| Lenovo              | 16       | 4.47%   |
| Hewlett-Packard     | 16       | 4.47%   |
| Supermicro          | 6        | 1.68%   |
| Acer                | 5        | 1.4%    |
| Intel               | 4        | 1.12%   |
| Fujitsu             | 4        | 1.12%   |
| Biostar             | 4        | 1.12%   |
| AZW                 | 3        | 0.84%   |
| Alienware           | 3        | 0.84%   |
| Unknown             | 3        | 0.84%   |
| Shuttle             | 2        | 0.56%   |
| Positivo            | 2        | 0.56%   |
| Apple               | 2        | 0.56%   |
| Seeed Studio        | 1        | 0.28%   |
| Pegatron            | 1        | 0.28%   |
| OEM                 | 1        | 0.28%   |
| Medion              | 1        | 0.28%   |
| JWIPC               | 1        | 0.28%   |
| Huanan              | 1        | 0.28%   |
| Foxconn             | 1        | 0.28%   |
| BESSTAR Tech        | 1        | 0.28%   |
| ABIT                | 1        | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| ASUS All Series                | 14       | 3.91%   |
| ASUS ROG STRIX B550-F GAMING   | 5        | 1.4%    |
| MSI MS-7B79                    | 4        | 1.12%   |
| Gigabyte B450M DS3H            | 3        | 0.84%   |
| Dell OptiPlex 7010             | 3        | 0.84%   |
| Unknown                        | 3        | 0.84%   |
| Supermicro SKAGIT09            | 2        | 0.56%   |
| MSI MS-7C95                    | 2        | 0.56%   |
| MSI MS-7C56                    | 2        | 0.56%   |
| MSI MS-7B86                    | 2        | 0.56%   |
| MSI MS-7B84                    | 2        | 0.56%   |
| MSI MS-7A40                    | 2        | 0.56%   |
| HP Compaq Elite 8300 SFF       | 2        | 0.56%   |
| Gigabyte X570 GAMING X         | 2        | 0.56%   |
| Gigabyte B450 I AORUS PRO WIFI | 2        | 0.56%   |
| Gigabyte 970-GAMING            | 2        | 0.56%   |
| Dell OptiPlex 7040             | 2        | 0.56%   |
| ASUS TUF Gaming Z590-PLUS WIFI | 2        | 0.56%   |
| ASUS TUF Gaming B550M-PLUS     | 2        | 0.56%   |
| ASUS STRIX Z270E GAMING        | 2        | 0.56%   |
| ASUS ROG ZENITH EXTREME        | 2        | 0.56%   |
| ASUS ROG STRIX Z390-E GAMING   | 2        | 0.56%   |
| ASUS ROG STRIX X570-E GAMING   | 2        | 0.56%   |
| ASUS ROG STRIX B550-I GAMING   | 2        | 0.56%   |
| ASUS ROG CROSSHAIR VII HERO    | 2        | 0.56%   |
| ASUS P9X79                     | 2        | 0.56%   |
| ASUS P8Z77-V LE                | 2        | 0.56%   |
| ASRock B450M Pro4              | 2        | 0.56%   |
| ASRock A320M-HDV R4.0          | 2        | 0.56%   |
| Supermicro X9DAL               | 1        | 0.28%   |
| Supermicro X8ST3               | 1        | 0.28%   |
| Supermicro PIO-1UDP10-01-AI036 | 1        | 0.28%   |
| Supermicro C7H61               | 1        | 0.28%   |
| Shuttle SH61R                  | 1        | 0.28%   |
| Shuttle NC01U                  | 1        | 0.28%   |
| Seeed Studio ODYSSEY-X86J4105  | 1        | 0.28%   |
| Positivo POS-PIH81DI           | 1        | 0.28%   |
| Positivo POS-PARS760GCD        | 1        | 0.28%   |
| Pegatron p6740la               | 1        | 0.28%   |
| OEM G41 775 ICH7 8712          | 1        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 20       | 5.59%   |
| ASUS PRIME             | 19       | 5.31%   |
| ASUS All               | 14       | 3.91%   |
| Dell OptiPlex          | 13       | 3.63%   |
| Lenovo ThinkCentre     | 11       | 3.07%   |
| ASUS TUF               | 11       | 3.07%   |
| Gigabyte X570          | 6        | 1.68%   |
| Dell Precision         | 5        | 1.4%    |
| MSI MS-7B79            | 4        | 1.12%   |
| Lenovo IdeaCentre      | 4        | 1.12%   |
| HP ProDesk             | 4        | 1.12%   |
| Gigabyte B450          | 4        | 1.12%   |
| Fujitsu ESPRIMO        | 4        | 1.12%   |
| Dell XPS               | 4        | 1.12%   |
| Acer Aspire            | 4        | 1.12%   |
| HP Compaq              | 3        | 0.84%   |
| Gigabyte H410M         | 3        | 0.84%   |
| Gigabyte B450M         | 3        | 0.84%   |
| ASUS STRIX             | 3        | 0.84%   |
| ASUS P9X79             | 3        | 0.84%   |
| ASUS M5A78L-M          | 3        | 0.84%   |
| ASRock B450M           | 3        | 0.84%   |
| ASRock A320M-HDV       | 3        | 0.84%   |
| Alienware Aurora       | 3        | 0.84%   |
| Unknown                | 3        | 0.84%   |
| Supermicro SKAGIT09    | 2        | 0.56%   |
| MSI MS-7C95            | 2        | 0.56%   |
| MSI MS-7C56            | 2        | 0.56%   |
| MSI MS-7B86            | 2        | 0.56%   |
| MSI MS-7B84            | 2        | 0.56%   |
| MSI MS-7A40            | 2        | 0.56%   |
| HP Pavilion            | 2        | 0.56%   |
| HP EliteDesk           | 2        | 0.56%   |
| Gigabyte Z390          | 2        | 0.56%   |
| Gigabyte GA-78LMT-USB3 | 2        | 0.56%   |
| Gigabyte B660M         | 2        | 0.56%   |
| Gigabyte B560M         | 2        | 0.56%   |
| Gigabyte B365M         | 2        | 0.56%   |
| Gigabyte 970-GAMING    | 2        | 0.56%   |
| Dell Inspiron          | 2        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 50       | 13.97%  |
| 2021 | 38       | 10.61%  |
| 2020 | 37       | 10.34%  |
| 2019 | 34       | 9.5%    |
| 2014 | 29       | 8.1%    |
| 2013 | 27       | 7.54%   |
| 2017 | 25       | 6.98%   |
| 2012 | 23       | 6.42%   |
| 2015 | 20       | 5.59%   |
| 2016 | 18       | 5.03%   |
| 2011 | 15       | 4.19%   |
| 2022 | 11       | 3.07%   |
| 2010 | 10       | 2.79%   |
| 2009 | 8        | 2.23%   |
| 2008 | 7        | 1.96%   |
| 2007 | 4        | 1.12%   |
| 2023 | 2        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 358      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 348      | 97.21%  |
| Enabled  | 10       | 2.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 358      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 109      | 30.28%  |
| 32.01-64.0      | 86       | 23.89%  |
| 8.01-16.0       | 57       | 15.83%  |
| 4.01-8.0        | 37       | 10.28%  |
| 64.01-256.0     | 36       | 10%     |
| 3.01-4.0        | 21       | 5.83%   |
| 24.01-32.0      | 13       | 3.61%   |
| More than 256.0 | 1        | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 2.01-3.0   | 98       | 25.99%  |
| 4.01-8.0   | 96       | 25.46%  |
| 3.01-4.0   | 66       | 17.51%  |
| 1.01-2.0   | 66       | 17.51%  |
| 8.01-16.0  | 30       | 7.96%   |
| 16.01-24.0 | 11       | 2.92%   |
| 0.51-1.0   | 4        | 1.06%   |
| 32.01-64.0 | 3        | 0.8%    |
| 24.01-32.0 | 2        | 0.53%   |
| 0.01-0.5   | 1        | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 112      | 30.94%  |
| 1      | 90       | 24.86%  |
| 3      | 74       | 20.44%  |
| 4      | 36       | 9.94%   |
| 5      | 23       | 6.35%   |
| 6      | 14       | 3.87%   |
| 7      | 8        | 2.21%   |
| 9      | 2        | 0.55%   |
| 8      | 2        | 0.55%   |
| 11     | 1        | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 215      | 59.89%  |
| Yes       | 144      | 40.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 354      | 98.88%  |
| No        | 4        | 1.12%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 189      | 52.5%   |
| No        | 171      | 47.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 203      | 56.55%  |
| Yes       | 156      | 43.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 82       | 22.91%  |
| Germany      | 41       | 11.45%  |
| France       | 26       | 7.26%   |
| UK           | 21       | 5.87%   |
| Italy        | 21       | 5.87%   |
| Russia       | 20       | 5.59%   |
| Brazil       | 19       | 5.31%   |
| Poland       | 12       | 3.35%   |
| Netherlands  | 11       | 3.07%   |
| Australia    | 10       | 2.79%   |
| Spain        | 9        | 2.51%   |
| Canada       | 8        | 2.23%   |
| Switzerland  | 6        | 1.68%   |
| Finland      | 6        | 1.68%   |
| Slovenia     | 4        | 1.12%   |
| Portugal     | 4        | 1.12%   |
| Bulgaria     | 4        | 1.12%   |
| Argentina    | 4        | 1.12%   |
| Philippines  | 3        | 0.84%   |
| New Zealand  | 3        | 0.84%   |
| India        | 3        | 0.84%   |
| Czechia      | 3        | 0.84%   |
| Belgium      | 3        | 0.84%   |
| Thailand     | 2        | 0.56%   |
| South Africa | 2        | 0.56%   |
| Serbia       | 2        | 0.56%   |
| Mexico       | 2        | 0.56%   |
| Iran         | 2        | 0.56%   |
| Greece       | 2        | 0.56%   |
| Austria      | 2        | 0.56%   |
| Vietnam      | 1        | 0.28%   |
| Venezuela    | 1        | 0.28%   |
| Ukraine      | 1        | 0.28%   |
| Turkey       | 1        | 0.28%   |
| Sweden       | 1        | 0.28%   |
| Romania      | 1        | 0.28%   |
| Panama       | 1        | 0.28%   |
| Norway       | 1        | 0.28%   |
| Malta        | 1        | 0.28%   |
| Malaysia     | 1        | 0.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Moscow            | 6        | 1.63%   |
| Munich            | 5        | 1.36%   |
| Berlin            | 5        | 1.36%   |
| Rio de Janeiro    | 4        | 1.09%   |
| Montreal          | 4        | 1.09%   |
| Melbourne         | 4        | 1.09%   |
| London            | 4        | 1.09%   |
| Sydney            | 3        | 0.82%   |
| Sao Paulo         | 3        | 0.82%   |
| Milan             | 3        | 0.82%   |
| Dallas            | 3        | 0.82%   |
| Wroclaw           | 2        | 0.54%   |
| Washington        | 2        | 0.54%   |
| Vladivostok       | 2        | 0.54%   |
| Vienna            | 2        | 0.54%   |
| Turku             | 2        | 0.54%   |
| Strasbourg        | 2        | 0.54%   |
| Prague            | 2        | 0.54%   |
| Pittsburgh        | 2        | 0.54%   |
| New York          | 2        | 0.54%   |
| Ljubljana         | 2        | 0.54%   |
| Indianapolis      | 2        | 0.54%   |
| Hamburg           | 2        | 0.54%   |
| Grenoble          | 2        | 0.54%   |
| Frankfurt am Main | 2        | 0.54%   |
| Curitiba          | 2        | 0.54%   |
| Columbus          | 2        | 0.54%   |
| Caruaru           | 2        | 0.54%   |
| Canberra          | 2        | 0.54%   |
| Brasília         | 2        | 0.54%   |
| Bougival          | 2        | 0.54%   |
| Belgrade          | 2        | 0.54%   |
| Auckland          | 2        | 0.54%   |
| Amsterdam         | 2        | 0.54%   |
| Zurich            | 1        | 0.27%   |
| Zaandam           | 1        | 0.27%   |
| Yerevan           | 1        | 0.27%   |
| Worcester Park    | 1        | 0.27%   |
| Wheaton           | 1        | 0.27%   |
| Whangarei         | 1        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 125      | 191    | 16.87%  |
| Samsung Electronics       | 120      | 216    | 16.19%  |
| Seagate                   | 115      | 204    | 15.52%  |
| Kingston                  | 46       | 58     | 6.21%   |
| Toshiba                   | 43       | 53     | 5.8%    |
| Sandisk                   | 37       | 50     | 4.99%   |
| Crucial                   | 33       | 39     | 4.45%   |
| Hitachi                   | 26       | 34     | 3.51%   |
| A-DATA Technology         | 19       | 21     | 2.56%   |
| Unknown                   | 10       | 15     | 1.35%   |
| Phison                    | 10       | 10     | 1.35%   |
| China                     | 10       | 11     | 1.35%   |
| PNY                       | 9        | 17     | 1.21%   |
| Patriot                   | 9        | 12     | 1.21%   |
| Intel                     | 9        | 12     | 1.21%   |
| HGST                      | 9        | 13     | 1.21%   |
| Phison Electronics        | 6        | 6      | 0.81%   |
| Maxtor                    | 6        | 7      | 0.81%   |
| OCZ                       | 5        | 5      | 0.67%   |
| SPCC                      | 4        | 4      | 0.54%   |
| Micron/Crucial Technology | 4        | 5      | 0.54%   |
| Lexar                     | 4        | 4      | 0.54%   |
| KIOXIA                    | 4        | 4      | 0.54%   |
| Intenso                   | 4        | 6      | 0.54%   |
| Transcend                 | 3        | 4      | 0.4%    |
| T-FORCE                   | 3        | 3      | 0.4%    |
| Realtek Semiconductor     | 3        | 3      | 0.4%    |
| Mushkin                   | 3        | 4      | 0.4%    |
| Micron Technology         | 3        | 3      | 0.4%    |
| Corsair                   | 3        | 4      | 0.4%    |
| Apple                     | 3        | 3      | 0.4%    |
| XPG                       | 2        | 2      | 0.27%   |
| Verbatim                  | 2        | 2      | 0.27%   |
| Team                      | 2        | 2      | 0.27%   |
| Smartbuy                  | 2        | 2      | 0.27%   |
| SK hynix                  | 2        | 4      | 0.27%   |
| SABRENT                   | 2        | 2      | 0.27%   |
| Plextor                   | 2        | 2      | 0.27%   |
| KODAK                     | 2        | 2      | 0.27%   |
| KIOXIA-EXCERIA            | 2        | 3      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 13       | 1.49%   |
| Seagate ST4000DM004-2CV104 4TB                      | 9        | 1.03%   |
| Samsung SSD 850 EVO 500GB                           | 9        | 1.03%   |
| Toshiba DT01ACA100 1TB                              | 8        | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 8        | 0.92%   |
| Samsung SSD 860 EVO 1TB                             | 7        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 6        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 6        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 6        | 0.69%   |
| Crucial CT240BX500SSD1 240GB                        | 6        | 0.69%   |
| Toshiba HDWD110 1TB                                 | 5        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5        | 0.57%   |
| SanDisk NVMe SSD Drive 500GB                        | 5        | 0.57%   |
| Toshiba DT01ACA200 2TB                              | 4        | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                     | 4        | 0.46%   |
| Seagate ST4000VN008-2DR166 4TB                      | 4        | 0.46%   |
| Seagate ST3500418AS 500GB                           | 4        | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB                      | 4        | 0.46%   |
| Seagate Expansion 2TB                               | 4        | 0.46%   |
| Samsung SSD 980 PRO 2TB                             | 4        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                        | 4        | 0.46%   |
| Samsung SSD 870 QVO 1TB                             | 4        | 0.46%   |
| Samsung SSD 870 EVO 1TB                             | 4        | 0.46%   |
| Samsung SSD 860 EVO 250GB                           | 4        | 0.46%   |
| Samsung SSD 850 EVO 250GB                           | 4        | 0.46%   |
| Samsung SSD 840 EVO 250GB                           | 4        | 0.46%   |
| Samsung NVMe SSD Drive 500GB                        | 4        | 0.46%   |
| Samsung HD103SI 1TB                                 | 4        | 0.46%   |
| Kingston SA2000M81000G 1TB                          | 4        | 0.46%   |
| Crucial CT1000BX500SSD1 1TB                         | 4        | 0.46%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 3        | 0.34%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3        | 0.34%   |
| WDC WD20EZRX-00D8PB0 2TB                            | 3        | 0.34%   |
| WDC WD20EARX-00PASB0 2TB                            | 3        | 0.34%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 3        | 0.34%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 3        | 0.34%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 3        | 0.34%   |
| Unknown SD/MMC 2GB                                  | 3        | 0.34%   |
| Unknown M.S./M.S.Pro/HG 16GB                        | 3        | 0.34%   |
| Toshiba HDWD130 3TB                                 | 3        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 110      | 156    | 33.95%  |
| Seagate             | 109      | 193    | 33.64%  |
| Toshiba             | 38       | 46     | 11.73%  |
| Hitachi             | 26       | 34     | 8.02%   |
| Samsung Electronics | 18       | 26     | 5.56%   |
| HGST                | 9        | 13     | 2.78%   |
| Maxtor              | 5        | 6      | 1.54%   |
| Unknown             | 2        | 2      | 0.62%   |
| SABRENT             | 2        | 2      | 0.62%   |
| Apple               | 2        | 2      | 0.62%   |
| USB3.0              | 1        | 1      | 0.31%   |
| JMicron Technology  | 1        | 1      | 0.31%   |
| IET                 | 1        | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 75       | 121    | 26.13%  |
| Kingston            | 37       | 43     | 12.89%  |
| Crucial             | 28       | 32     | 9.76%   |
| SanDisk             | 23       | 24     | 8.01%   |
| WDC                 | 17       | 26     | 5.92%   |
| A-DATA Technology   | 16       | 17     | 5.57%   |
| China               | 10       | 11     | 3.48%   |
| PNY                 | 9        | 17     | 3.14%   |
| Patriot             | 9        | 12     | 3.14%   |
| OCZ                 | 5        | 5      | 1.74%   |
| Intel               | 5        | 8      | 1.74%   |
| Lexar               | 4        | 4      | 1.39%   |
| Toshiba             | 3        | 3      | 1.05%   |
| SPCC                | 3        | 3      | 1.05%   |
| Mushkin             | 3        | 4      | 1.05%   |
| Micron Technology   | 3        | 3      | 1.05%   |
| Intenso             | 3        | 3      | 1.05%   |
| Verbatim            | 2        | 2      | 0.7%    |
| Transcend           | 2        | 2      | 0.7%    |
| Plextor             | 2        | 2      | 0.7%    |
| KODAK               | 2        | 2      | 0.7%    |
| KIOXIA-EXCERIA      | 2        | 3      | 0.7%    |
| Hewlett-Packard     | 2        | 2      | 0.7%    |
| GOODRAM             | 2        | 2      | 0.7%    |
| ValueTech           | 1        | 1      | 0.35%   |
| Team                | 1        | 1      | 0.35%   |
| T-FORCE             | 1        | 1      | 0.35%   |
| Smartbuy            | 1        | 1      | 0.35%   |
| Seagate             | 1        | 1      | 0.35%   |
| OCZ-VERTEX3         | 1        | 1      | 0.35%   |
| Maxtor              | 1        | 1      | 0.35%   |
| LITEONIT            | 1        | 1      | 0.35%   |
| KingFast            | 1        | 1      | 0.35%   |
| Integral            | 1        | 1      | 0.35%   |
| INNOVATION IT       | 1        | 1      | 0.35%   |
| INDMEM              | 1        | 1      | 0.35%   |
| Emtec               | 1        | 1      | 0.35%   |
| Drevo               | 1        | 1      | 0.35%   |
| DeLOCK              | 1        | 1      | 0.35%   |
| BlueRay             | 1        | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 245      | 483    | 39.14%  |
| SSD     | 232      | 371    | 37.06%  |
| NVMe    | 133      | 201    | 21.25%  |
| Unknown | 13       | 20     | 2.08%   |
| MMC     | 3        | 3      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 329      | 823    | 66.06%  |
| NVMe | 133      | 200    | 26.71%  |
| SAS  | 33       | 52     | 6.63%   |
| MMC  | 3        | 3      | 0.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 229      | 398    | 43.05%  |
| 0.51-1.0   | 148      | 213    | 27.82%  |
| 1.01-2.0   | 70       | 105    | 13.16%  |
| 3.01-4.0   | 43       | 76     | 8.08%   |
| 4.01-10.0  | 25       | 37     | 4.7%    |
| 2.01-3.0   | 13       | 17     | 2.44%   |
| 10.01-20.0 | 4        | 8      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 68       | 18.48%  |
| 501-1000       | 67       | 18.21%  |
| 1001-2000      | 61       | 16.58%  |
| 251-500        | 57       | 15.49%  |
| 101-250        | 50       | 13.59%  |
| 2001-3000      | 46       | 12.5%   |
| 1-20           | 11       | 2.99%   |
| 51-100         | 6        | 1.63%   |
| Unknown        | 2        | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 57       | 15.36%  |
| 501-1000       | 54       | 14.56%  |
| 251-500        | 53       | 14.29%  |
| 1-20           | 44       | 11.86%  |
| 51-100         | 43       | 11.59%  |
| 1001-2000      | 38       | 10.24%  |
| More than 3000 | 33       | 8.89%   |
| 21-50          | 31       | 8.36%   |
| 2001-3000      | 16       | 4.31%   |
| Unknown        | 2        | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB          | 2        | 2      | 3.39%   |
| Hitachi HDS721010CLA630 1TB              | 2        | 2      | 3.39%   |
| WDC WD7502ABYS-02A6B0 752GB              | 1        | 1      | 1.69%   |
| WDC WD5000AZRX-00A3KB0 500GB             | 1        | 1      | 1.69%   |
| WDC WD5000AVVS-63M8B0 500GB              | 1        | 1      | 1.69%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 1.69%   |
| WDC WD30EZRX-00MMMB0 3TB                 | 1        | 1      | 1.69%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1        | 2      | 1.69%   |
| WDC WD20EADS-14R6B0 2TB                  | 1        | 1      | 1.69%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1        | 1      | 1.69%   |
| WDC WD10EZEX-22MFCA0 1TB                 | 1        | 1      | 1.69%   |
| WDC WD10EZEX-08M2NA0 1TB                 | 1        | 1      | 1.69%   |
| WDC WD10EURX-73C57Y0 1TB                 | 1        | 1      | 1.69%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1        | 1      | 1.69%   |
| WDC WD10EADS-00L5B1 1TB                  | 1        | 1      | 1.69%   |
| WDC WD10EACS-65D6B0 1TB                  | 1        | 1      | 1.69%   |
| Toshiba MQ01ABF032 320GB                 | 1        | 1      | 1.69%   |
| T-FORCE SSD 512GB                        | 1        | 1      | 1.69%   |
| Seagate ST500LT012-9WS142 500GB          | 1        | 1      | 1.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 1        | 1      | 1.69%   |
| Seagate ST4000VN008-2DR166 4TB           | 1        | 2      | 1.69%   |
| Seagate ST3500630AS 500GB                | 1        | 1      | 1.69%   |
| Seagate ST3500418AS 500GB                | 1        | 1      | 1.69%   |
| Seagate ST3250310AS 250GB                | 1        | 1      | 1.69%   |
| Seagate ST3160827AS 160GB                | 1        | 1      | 1.69%   |
| Seagate ST3160023A 160GB                 | 1        | 1      | 1.69%   |
| Seagate ST31500341AS 1TB                 | 1        | 1      | 1.69%   |
| Seagate ST31000524AS 1TB                 | 1        | 2      | 1.69%   |
| Seagate ST2000DX001-1NS164 2TB           | 1        | 1      | 1.69%   |
| Seagate ST1000NM0011 1TB                 | 1        | 1      | 1.69%   |
| Seagate ST1000DM003-1SB102 1TB           | 1        | 1      | 1.69%   |
| Seagate ST1000DM003-1CH162 1TB           | 1        | 1      | 1.69%   |
| SanDisk SDSSDX240GG25 240GB              | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 870 EVO 500GB    | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 870 EVO 1TB      | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 840 Series 250GB | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 840 Series 120GB | 1        | 1      | 1.69%   |
| Samsung Electronics HM321HI 320GB        | 1        | 1      | 1.69%   |
| Samsung Electronics HD501LJ 500GB        | 1        | 6      | 1.69%   |
| Samsung Electronics HD103SI 1TB          | 1        | 1      | 1.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 18     | 25%     |
| WDC                 | 13       | 15     | 23.21%  |
| Samsung Electronics | 7        | 12     | 12.5%   |
| Hitachi             | 6        | 6      | 10.71%  |
| Crucial             | 3        | 3      | 5.36%   |
| Maxtor              | 2        | 2      | 3.57%   |
| Toshiba             | 1        | 1      | 1.79%   |
| T-FORCE             | 1        | 1      | 1.79%   |
| SanDisk             | 1        | 1      | 1.79%   |
| Phison Electronics  | 1        | 1      | 1.79%   |
| OCZ                 | 1        | 1      | 1.79%   |
| Micron Technology   | 1        | 1      | 1.79%   |
| LITEONIT            | 1        | 1      | 1.79%   |
| Kingston            | 1        | 1      | 1.79%   |
| Intenso             | 1        | 1      | 1.79%   |
| Intel               | 1        | 4      | 1.79%   |
| HGST                | 1        | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 14       | 18     | 35%     |
| WDC                 | 13       | 15     | 32.5%   |
| Hitachi             | 6        | 6      | 15%     |
| Samsung Electronics | 3        | 8      | 7.5%    |
| Maxtor              | 2        | 2      | 5%      |
| Toshiba             | 1        | 1      | 2.5%    |
| HGST                | 1        | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 37       | 51     | 69.81%  |
| SSD  | 15       | 18     | 28.3%   |
| NVMe | 1        | 1      | 1.89%   |

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
| Works    | 189      | 500    | 44.06%  |
| Detected | 188      | 506    | 43.82%  |
| Malfunc  | 51       | 70     | 11.89%  |
| Failed   | 1        | 2      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Intel                        | 216      | 39.06%  |
| AMD                          | 137      | 24.77%  |
| Samsung Electronics          | 48       | 8.68%   |
| ASMedia Technology           | 26       | 4.7%    |
| SanDisk                      | 24       | 4.34%   |
| Phison Electronics           | 20       | 3.62%   |
| Kingston Technology Company  | 13       | 2.35%   |
| Micron/Crucial Technology    | 10       | 1.81%   |
| JMicron Technology           | 9        | 1.63%   |
| Marvell Technology Group     | 7        | 1.27%   |
| Realtek Semiconductor        | 5        | 0.9%    |
| LSI Logic / Symbios Logic    | 5        | 0.9%    |
| KIOXIA                       | 5        | 0.9%    |
| ADATA Technology             | 5        | 0.9%    |
| Seagate Technology           | 4        | 0.72%   |
| Silicon Motion               | 3        | 0.54%   |
| Toshiba America Info Systems | 2        | 0.36%   |
| SK hynix                     | 2        | 0.36%   |
| Silicon Image                | 2        | 0.36%   |
| Nvidia                       | 2        | 0.36%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.36%   |
| VIA Technologies             | 1        | 0.18%   |
| OCZ Technology Group         | 1        | 0.18%   |
| O2 Micro                     | 1        | 0.18%   |
| Netac Technology             | 1        | 0.18%   |
| INNOGRIT                     | 1        | 0.18%   |
| Broadcom / LSI               | 1        | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 83       | 12.35%  |
| AMD 400 Series Chipset SATA Controller                                                  | 34       | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 3.87%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25       | 3.72%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25       | 3.72%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 24       | 3.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19       | 2.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 17       | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.38%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15       | 2.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 14       | 2.08%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 2.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 1.93%   |
| Intel SATA Controller [RAID mode]                                                       | 12       | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 1.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12       | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 1.79%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 10       | 1.49%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 9        | 1.34%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 9        | 1.34%   |
| AMD FCH SATA Controller D                                                               | 9        | 1.34%   |
| Phison E12 NVMe Controller                                                              | 8        | 1.19%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 7        | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7        | 1.04%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.04%   |
| Samsung NVMe SSD Controller 980                                                         | 6        | 0.89%   |
| Kingston Company A2000 NVMe SSD                                                         | 6        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6        | 0.89%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 6        | 0.89%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 0.89%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 5        | 0.74%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 0.74%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                                      | 4        | 0.6%    |
| SanDisk PC SN735 NVMe SSD (DRAM-less)                                                   | 4        | 0.6%    |
| Phison PS5013 E13 NVMe Controller                                                       | 4        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.6%    |
| Intel SSD 660P Series                                                                   | 4        | 0.6%    |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 324      | 61.36%  |
| NVMe | 132      | 25%     |
| IDE  | 43       | 8.14%   |
| RAID | 24       | 4.55%   |
| SAS  | 3        | 0.57%   |
| SCSI | 2        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Desktops | Percent |
|---------------|----------|---------|
| Intel         | 216      | 60.34%  |
| AMD           | 141      | 39.39%  |
| sifive,u74-mc | 1        | 0.28%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 2.51%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9        | 2.51%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 8        | 2.23%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 6        | 1.68%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 6        | 1.68%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 6        | 1.68%   |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 1.68%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 5        | 1.4%    |
| Intel Core i5-9600K CPU @ 3.70GHz           | 5        | 1.4%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 1.4%    |
| AMD Ryzen 9 5900X 12-Core Processor         | 5        | 1.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 1.4%    |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 1.4%    |
| Intel Core i3-10100F CPU @ 3.60GHz          | 4        | 1.12%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4        | 1.12%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 4        | 1.12%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.12%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.84%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 3        | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 3        | 0.84%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 3        | 0.84%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.84%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 3        | 0.84%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.84%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 3        | 0.84%   |
| Intel 12th Gen Core i9-12900K               | 3        | 0.84%   |
| Intel 12th Gen Core i7-12700K               | 3        | 0.84%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3        | 0.84%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics  | 3        | 0.84%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 3        | 0.84%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 0.84%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 3        | 0.84%   |
| AMD Ryzen 5 5600 6-Core Processor           | 3        | 0.84%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3        | 0.84%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 0.84%   |
| AMD FX-8350 Eight-Core Processor            | 3        | 0.84%   |
| Intel Pentium CPU G4600 @ 3.60GHz           | 2        | 0.56%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 2        | 0.56%   |
| Intel Pentium CPU G2020 @ 2.90GHz           | 2        | 0.56%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Desktops | Percent |
|------------------------|----------|---------|
| Intel Core i7          | 66       | 18.44%  |
| Intel Core i5          | 57       | 15.92%  |
| AMD Ryzen 5            | 42       | 11.73%  |
| AMD Ryzen 7            | 28       | 7.82%   |
| Intel Core i3          | 22       | 6.15%   |
| Other                  | 21       | 5.87%   |
| AMD Ryzen 9            | 20       | 5.59%   |
| Intel Xeon             | 17       | 4.75%   |
| AMD FX                 | 11       | 3.07%   |
| Intel Pentium          | 10       | 2.79%   |
| AMD Ryzen 3            | 8        | 2.23%   |
| Intel Celeron          | 7        | 1.96%   |
| Intel Core i9          | 6        | 1.68%   |
| Intel Core 2 Duo       | 6        | 1.68%   |
| Intel Core 2 Quad      | 4        | 1.12%   |
| AMD A6                 | 4        | 1.12%   |
| AMD Ryzen Threadripper | 3        | 0.84%   |
| AMD Ryzen 7 PRO        | 3        | 0.84%   |
| AMD Phenom II X4       | 3        | 0.84%   |
| AMD Athlon 64 X2       | 3        | 0.84%   |
| AMD A8                 | 3        | 0.84%   |
| Intel Pentium Gold     | 2        | 0.56%   |
| AMD Phenom II X2       | 2        | 0.56%   |
| AMD Opteron            | 2        | 0.56%   |
| AMD A10                | 2        | 0.56%   |
| AMD PRO A10            | 1        | 0.28%   |
| AMD Phenom II X6       | 1        | 0.28%   |
| AMD Phenom             | 1        | 0.28%   |
| AMD E1                 | 1        | 0.28%   |
| AMD Athlon II X2       | 1        | 0.28%   |
| AMD A4                 | 1        | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 131      | 36.59%  |
| 6       | 77       | 21.51%  |
| 2       | 59       | 16.48%  |
| 8       | 49       | 13.69%  |
| 16      | 15       | 4.19%   |
| 12      | 12       | 3.35%   |
| 10      | 4        | 1.12%   |
| 1       | 4        | 1.12%   |
| 24      | 2        | 0.56%   |
| 3       | 2        | 0.56%   |
| 36      | 1        | 0.28%   |
| 14      | 1        | 0.28%   |
| Unknown | 1        | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 354      | 98.88%  |
| 2       | 3        | 0.84%   |
| Unknown | 1        | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 250      | 69.64%  |
| 1       | 108      | 30.08%  |
| Unknown | 1        | 0.28%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 357      | 99.72%  |
| Unknown        | 1        | 0.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 167      | 46.01%  |
| 0x306c3    | 19       | 5.23%   |
| 0x08701021 | 13       | 3.58%   |
| 0x506e3    | 9        | 2.48%   |
| 0x906e9    | 8        | 2.2%    |
| 0x306a9    | 8        | 2.2%    |
| 0x0800820d | 8        | 2.2%    |
| 0xa0653    | 7        | 1.93%   |
| 0x906ed    | 6        | 1.65%   |
| 0x90672    | 6        | 1.65%   |
| 0x0a50000c | 6        | 1.65%   |
| 0xa0655    | 5        | 1.38%   |
| 0x906ea    | 5        | 1.38%   |
| 0x206a7    | 5        | 1.38%   |
| 0x1067a    | 5        | 1.38%   |
| 0x0a201205 | 5        | 1.38%   |
| 0x010000c8 | 5        | 1.38%   |
| 0x406f1    | 4        | 1.1%    |
| 0x0a201016 | 4        | 1.1%    |
| 0x306f2    | 3        | 0.83%   |
| 0x306e4    | 3        | 0.83%   |
| 0x206d7    | 3        | 0.83%   |
| 0x0a601203 | 3        | 0.83%   |
| 0x08001138 | 3        | 0.83%   |
| 0x08001137 | 3        | 0.83%   |
| 0x0600611a | 3        | 0.83%   |
| 0x06000852 | 3        | 0.83%   |
| 0xb0671    | 2        | 0.55%   |
| 0xa0671    | 2        | 0.55%   |
| 0x106e5    | 2        | 0.55%   |
| 0x106a5    | 2        | 0.55%   |
| 0x0a50000d | 2        | 0.55%   |
| 0x0a20120a | 2        | 0.55%   |
| 0x0a201204 | 2        | 0.55%   |
| 0x0a201009 | 2        | 0.55%   |
| 0x08600106 | 2        | 0.55%   |
| 0x08001126 | 2        | 0.55%   |
| 0x06001119 | 2        | 0.55%   |
| 0x06000822 | 2        | 0.55%   |
| 0x906ec    | 1        | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 48       | 13.37%  |
| KabyLake         | 38       | 10.58%  |
| Zen 3            | 36       | 10.03%  |
| IvyBridge        | 31       | 8.64%   |
| Zen 2            | 27       | 7.52%   |
| Zen+             | 19       | 5.29%   |
| Zen              | 18       | 5.01%   |
| CometLake        | 18       | 5.01%   |
| Unknown          | 16       | 4.46%   |
| Skylake          | 15       | 4.18%   |
| Piledriver       | 15       | 4.18%   |
| SandyBridge      | 14       | 3.9%    |
| Penryn           | 9        | 2.51%   |
| K10              | 9        | 2.51%   |
| Nehalem          | 8        | 2.23%   |
| Excavator        | 6        | 1.67%   |
| Broadwell        | 6        | 1.67%   |
| Alderlake Hybrid | 6        | 1.67%   |
| Icelake          | 4        | 1.11%   |
| Westmere         | 3        | 0.84%   |
| K8 Hammer        | 3        | 0.84%   |
| Core             | 3        | 0.84%   |
| Steamroller      | 1        | 0.28%   |
| Silvermont       | 1        | 0.28%   |
| Puma             | 1        | 0.28%   |
| K10 Llano        | 1        | 0.28%   |
| Goldmont plus    | 1        | 0.28%   |
| Goldmont         | 1        | 0.28%   |
| Bulldozer        | 1        | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 177      | 44.92%  |
| AMD                        | 123      | 31.22%  |
| Intel                      | 89       | 22.59%  |
| Matrox Electronics Systems | 3        | 0.76%   |
| ASPEED Technology          | 2        | 0.51%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 20       | 5%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 16       | 4%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 3.75%   |
| Nvidia GK208B [GeForce GT 710]                                              | 10       | 2.5%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 2.25%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 9        | 2.25%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 8        | 2%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 2%      |
| Nvidia GP104 [GeForce GTX 1070]                                             | 7        | 1.75%   |
| Intel HD Graphics 530                                                       | 7        | 1.75%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 7        | 1.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 6        | 1.5%    |
| Intel HD Graphics 630                                                       | 6        | 1.5%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 1.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 6        | 1.5%    |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 1.25%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 5        | 1.25%   |
| Nvidia GK208B [GeForce GT 730]                                              | 5        | 1.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5        | 1.25%   |
| AMD Renoir                                                                  | 5        | 1.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 4        | 1%      |
| Nvidia GP107 [GeForce GTX 1050]                                             | 4        | 1%      |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1%      |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1%      |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4        | 1%      |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4        | 1%      |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 4        | 1%      |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 4        | 1%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 1%      |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 3        | 0.75%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 3        | 0.75%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 0.75%   |
| Nvidia GM107 [GeForce GTX 745]                                              | 3        | 0.75%   |
| Nvidia GF108 [GeForce GT 630]                                               | 3        | 0.75%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 3        | 0.75%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 0.75%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 0.75%   |
| Intel AlderLake-S GT1                                                       | 3        | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 167      | 46.52%  |
| 1 x AMD                  | 110      | 30.64%  |
| 1 x Intel                | 59       | 16.43%  |
| 2 x AMD                  | 4        | 1.11%   |
| Intel + Nvidia           | 4        | 1.11%   |
| Intel + AMD              | 4        | 1.11%   |
| 2 x Nvidia               | 3        | 0.84%   |
| AMD + Matrox             | 2        | 0.56%   |
| Other                    | 1        | 0.28%   |
| Nvidia + Matrox          | 1        | 0.28%   |
| Nvidia + ASPEED          | 1        | 0.28%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.28%   |
| 1 x ASPEED               | 1        | 0.28%   |
| AMD + Nvidia             | 1        | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 213      | 59.17%  |
| Proprietary | 132      | 36.67%  |
| Unknown     | 15       | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 161      | 44.11%  |
| 1.01-2.0   | 46       | 12.6%   |
| 7.01-8.0   | 38       | 10.41%  |
| 3.01-4.0   | 36       | 9.86%   |
| 0.51-1.0   | 29       | 7.95%   |
| 5.01-6.0   | 19       | 5.21%   |
| 0.01-0.5   | 17       | 4.66%   |
| 8.01-16.0  | 13       | 3.56%   |
| 16.01-24.0 | 4        | 1.1%    |
| 4.01-5.0   | 1        | 0.27%   |
| 2.01-3.0   | 1        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 78       | 18.48%  |
| Dell                 | 50       | 11.85%  |
| Goldstar             | 47       | 11.14%  |
| Hewlett-Packard      | 31       | 7.35%   |
| Acer                 | 24       | 5.69%   |
| Philips              | 23       | 5.45%   |
| AOC                  | 22       | 5.21%   |
| BenQ                 | 21       | 4.98%   |
| Iiyama               | 15       | 3.55%   |
| Ancor Communications | 15       | 3.55%   |
| ASUSTek Computer     | 11       | 2.61%   |
| Sony                 | 7        | 1.66%   |
| ViewSonic            | 6        | 1.42%   |
| Vizio                | 3        | 0.71%   |
| NEC Computers        | 3        | 0.71%   |
| LG Electronics       | 3        | 0.71%   |
| Idek Iiyama          | 3        | 0.71%   |
| Eizo                 | 3        | 0.71%   |
| Xiaomi               | 2        | 0.47%   |
| Vestel Elektronik    | 2        | 0.47%   |
| Unknown              | 2        | 0.47%   |
| RTK                  | 2        | 0.47%   |
| Planar               | 2        | 0.47%   |
| Mi                   | 2        | 0.47%   |
| Lenovo               | 2        | 0.47%   |
| Gigabyte Technology  | 2        | 0.47%   |
| Fujitsu Siemens      | 2        | 0.47%   |
| DTV                  | 2        | 0.47%   |
| Denver               | 2        | 0.47%   |
| CHD                  | 2        | 0.47%   |
| Unknown              | 2        | 0.47%   |
| Vita                 | 1        | 0.24%   |
| TXD                  | 1        | 0.24%   |
| Sunplus              | 1        | 0.24%   |
| STD                  | 1        | 0.24%   |
| Sceptre Tech         | 1        | 0.24%   |
| QUS                  | 1        | 0.24%   |
| Pixio                | 1        | 0.24%   |
| PAR                  | 1        | 0.24%   |
| Panasonic            | 1        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 5        | 1.12%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 4        | 0.89%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 3        | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3        | 0.67%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                  | 3        | 0.67%   |
| Dell 2408WFP DELA02B 1920x1200 519x320mm 24.0-inch                      | 3        | 0.67%   |
| AOC 27G2WG3 AOC2702 1920x1080 598x336mm 27.0-inch                       | 3        | 0.67%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 2        | 0.45%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2        | 0.45%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch    | 2        | 0.45%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch     | 2        | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 2        | 0.45%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1872x1053mm 84.6-inch | 2        | 0.45%   |
| Samsung Electronics LC27G5xT SAM7079 2560x1440 597x336mm 27.0-inch      | 2        | 0.45%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                  | 2        | 0.45%   |
| Planar PLL2710W PLN2710 1920x1080 597x336mm 27.0-inch                   | 2        | 0.45%   |
| Philips PHL 247E6 PHLC0E7 1920x1080 521x293mm 23.5-inch                 | 2        | 0.45%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 2        | 0.45%   |
| Mi Redmi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                  | 2        | 0.45%   |
| Iiyama PLG2888UH IVM710B 3840x2160                                      | 2        | 0.45%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch               | 2        | 0.45%   |
| Hewlett-Packard 2311 HWP2939 1920x1080 509x286mm 23.0-inch              | 2        | 0.45%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 2        | 0.45%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 2        | 0.45%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2        | 0.45%   |
| Goldstar 2D HD LG TV GSM59CA 1366x768 510x290mm 23.1-inch               | 2        | 0.45%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                   | 2        | 0.45%   |
| Dell S3422DW DELD102 3440x1440 797x334mm 34.0-inch                      | 2        | 0.45%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                       | 2        | 0.45%   |
| Dell P2415Q DELA0BE 3840x2160 527x296mm 23.8-inch                       | 2        | 0.45%   |
| Dell P2214H DELA098 1920x1080 477x268mm 21.5-inch                       | 2        | 0.45%   |
| Dell 2007WFP DELA019 1680x1050 430x270mm 20.0-inch                      | 2        | 0.45%   |
| BenQ GW2480 BNQ78E7 1920x1080 530x300mm 24.0-inch                       | 2        | 0.45%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                      | 2        | 0.45%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                       | 2        | 0.45%   |
| AOC 32V1W AOC3201 1920x1080 698x393mm 31.5-inch                         | 2        | 0.45%   |
| AOC 2450W AOC2450 1920x1080 521x293mm 23.5-inch                         | 2        | 0.45%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                       | 2        | 0.45%   |
| Unknown                                                                 | 2        | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 189      | 47.73%  |
| 3840x2160 (4K)     | 48       | 12.12%  |
| 2560x1440 (QHD)    | 25       | 6.31%   |
| 1680x1050 (WSXGA+) | 24       | 6.06%   |
| 1920x1200 (WUXGA)  | 22       | 5.56%   |
| 1280x1024 (SXGA)   | 16       | 4.04%   |
| 1366x768 (WXGA)    | 13       | 3.28%   |
| 3440x1440          | 12       | 3.03%   |
| 2560x1080          | 7        | 1.77%   |
| 1600x900 (HD+)     | 6        | 1.52%   |
| 1440x900 (WXGA+)   | 5        | 1.26%   |
| 1360x768           | 5        | 1.26%   |
| Unknown            | 5        | 1.26%   |
| 3840x1080          | 4        | 1.01%   |
| 1280x720 (HD)      | 2        | 0.51%   |
| 6160x1440          | 1        | 0.25%   |
| 5760x2160          | 1        | 0.25%   |
| 5760x1080          | 1        | 0.25%   |
| 480x1920           | 1        | 0.25%   |
| 4800x1080          | 1        | 0.25%   |
| 3840x1600          | 1        | 0.25%   |
| 3840x1200          | 1        | 0.25%   |
| 3600x1200          | 1        | 0.25%   |
| 2288x1287          | 1        | 0.25%   |
| 1920x540           | 1        | 0.25%   |
| 1600x1200          | 1        | 0.25%   |
| 1280x768           | 1        | 0.25%   |
| 1024x768 (XGA)     | 1        | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 75       | 18.12%  |
| 23      | 60       | 14.49%  |
| 27      | 57       | 13.77%  |
| 21      | 48       | 11.59%  |
| 31      | 26       | 6.28%   |
| Unknown | 22       | 5.31%   |
| 34      | 17       | 4.11%   |
| 19      | 15       | 3.62%   |
| 22      | 14       | 3.38%   |
| 32      | 9        | 2.17%   |
| 18      | 9        | 2.17%   |
| 72      | 7        | 1.69%   |
| 20      | 6        | 1.45%   |
| 46      | 5        | 1.21%   |
| 17      | 5        | 1.21%   |
| 84      | 4        | 0.97%   |
| 54      | 4        | 0.97%   |
| 40      | 4        | 0.97%   |
| 65      | 3        | 0.72%   |
| 36      | 3        | 0.72%   |
| 25      | 3        | 0.72%   |
| 48      | 2        | 0.48%   |
| 28      | 2        | 0.48%   |
| 15      | 2        | 0.48%   |
| 142     | 1        | 0.24%   |
| 69      | 1        | 0.24%   |
| 60      | 1        | 0.24%   |
| 55      | 1        | 0.24%   |
| 49      | 1        | 0.24%   |
| 43      | 1        | 0.24%   |
| 42      | 1        | 0.24%   |
| 38      | 1        | 0.24%   |
| 37      | 1        | 0.24%   |
| 35      | 1        | 0.24%   |
| 33      | 1        | 0.24%   |
| 26      | 1        | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 163      | 41.27%  |
| 401-500        | 85       | 21.52%  |
| 601-700        | 41       | 10.38%  |
| 701-800        | 30       | 7.59%   |
| Unknown        | 22       | 5.57%   |
| 1001-1500      | 17       | 4.3%    |
| 1501-2000      | 12       | 3.04%   |
| 351-400        | 8        | 2.03%   |
| 801-900        | 7        | 1.77%   |
| 301-350        | 7        | 1.77%   |
| 901-1000       | 2        | 0.51%   |
| More than 2000 | 1        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 255      | 70.83%  |
| 16/10   | 47       | 13.06%  |
| 21/9    | 19       | 5.28%   |
| Unknown | 17       | 4.72%   |
| 5/4     | 13       | 3.61%   |
| 32/9    | 3        | 0.83%   |
| 3/2     | 3        | 0.83%   |
| 4/3     | 1        | 0.28%   |
| 1.00    | 1        | 0.28%   |
| 0.25    | 1        | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 142      | 35.59%  |
| 301-350        | 58       | 14.54%  |
| 351-500        | 55       | 13.78%  |
| 151-200        | 37       | 9.27%   |
| 251-300        | 29       | 7.27%   |
| More than 1000 | 22       | 5.51%   |
| Unknown        | 22       | 5.51%   |
| 501-1000       | 19       | 4.76%   |
| 141-150        | 13       | 3.26%   |
| 101-110        | 2        | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 223      | 60.11%  |
| 101-120 | 68       | 18.33%  |
| 1-50    | 28       | 7.55%   |
| 121-160 | 24       | 6.47%   |
| Unknown | 22       | 5.93%   |
| 161-240 | 6        | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 236      | 65.01%  |
| 2     | 99       | 27.27%  |
| 0     | 17       | 4.68%   |
| 3     | 8        | 2.2%    |
| 4     | 3        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 217      | 40.56%  |
| Intel                           | 176      | 32.9%   |
| Qualcomm Atheros                | 32       | 5.98%   |
| Broadcom                        | 18       | 3.36%   |
| Ralink Technology               | 14       | 2.62%   |
| Aquantia                        | 10       | 1.87%   |
| TP-Link                         | 9        | 1.68%   |
| Ralink                          | 6        | 1.12%   |
| MediaTek                        | 6        | 1.12%   |
| Huawei Technologies             | 5        | 0.93%   |
| Samsung Electronics             | 4        | 0.75%   |
| Qualcomm Atheros Communications | 3        | 0.56%   |
| D-Link                          | 3        | 0.56%   |
| ASIX Electronics                | 3        | 0.56%   |
| Xiaomi                          | 2        | 0.37%   |
| Wilocity                        | 2        | 0.37%   |
| VIA Technologies                | 2        | 0.37%   |
| Nvidia                          | 2        | 0.37%   |
| NetGear                         | 2        | 0.37%   |
| Edimax Technology               | 2        | 0.37%   |
| Belkin Components               | 2        | 0.37%   |
| ASUSTek Computer                | 2        | 0.37%   |
| ZyXEL Communications            | 1        | 0.19%   |
| U-Blox                          | 1        | 0.19%   |
| Solarflare Communications       | 1        | 0.19%   |
| Seeed Technology                | 1        | 0.19%   |
| Microsoft                       | 1        | 0.19%   |
| Mercucys                        | 1        | 0.19%   |
| LSI                             | 1        | 0.19%   |
| Linksys                         | 1        | 0.19%   |
| LG Electronics                  | 1        | 0.19%   |
| DisplayLink                     | 1        | 0.19%   |
| D-Link System                   | 1        | 0.19%   |
| Bose                            | 1        | 0.19%   |
| Arduino SA                      | 1        | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161      | 26.01%  |
| Intel I211 Gigabit Network Connection                             | 26       | 4.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 24       | 3.88%   |
| Intel Wi-Fi 6 AX200                                               | 22       | 3.55%   |
| Intel Ethernet Controller I225-V                                  | 22       | 3.55%   |
| Intel Ethernet Connection (2) I219-V                              | 13       | 2.1%    |
| Intel Ethernet Connection I217-LM                                 | 11       | 1.78%   |
| Intel Ethernet Connection (7) I219-V                              | 11       | 1.78%   |
| Intel Ethernet Connection (2) I218-V                              | 10       | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8        | 1.29%   |
| Realtek 802.11ac NIC                                              | 8        | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8        | 1.29%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7        | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.13%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.97%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 0.97%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6        | 0.97%   |
| Ralink RT5370 Wireless Adapter                                    | 5        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5        | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5        | 0.81%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4        | 0.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4        | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 4        | 0.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 0.65%   |
| Intel Wireless-AC 9260                                            | 4        | 0.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 4        | 0.65%   |
| Huawei MLA-L11                                                    | 4        | 0.65%   |
| TP-Link 802.11ac NIC                                              | 3        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.48%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 3        | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 68       | 33.66%  |
| Realtek Semiconductor           | 48       | 23.76%  |
| Qualcomm Atheros                | 17       | 8.42%   |
| Ralink Technology               | 14       | 6.93%   |
| Broadcom                        | 13       | 6.44%   |
| TP-Link                         | 9        | 4.46%   |
| Ralink                          | 6        | 2.97%   |
| MediaTek                        | 5        | 2.48%   |
| Qualcomm Atheros Communications | 3        | 1.49%   |
| D-Link                          | 3        | 1.49%   |
| Wilocity                        | 2        | 0.99%   |
| NetGear                         | 2        | 0.99%   |
| Edimax Technology               | 2        | 0.99%   |
| Belkin Components               | 2        | 0.99%   |
| ASUSTek Computer                | 2        | 0.99%   |
| ZyXEL Communications            | 1        | 0.5%    |
| Microsoft                       | 1        | 0.5%    |
| Mercucys                        | 1        | 0.5%    |
| Linksys                         | 1        | 0.5%    |
| LG Electronics                  | 1        | 0.5%    |
| D-Link System                   | 1        | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                        | 22       | 10.63%  |
| Realtek 802.11ac NIC                                       | 8        | 3.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 8        | 3.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 7        | 3.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 6        | 2.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 6        | 2.9%    |
| Ralink RT5370 Wireless Adapter                             | 5        | 2.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 5        | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 5        | 2.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 4        | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 4        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 4        | 1.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter           | 4        | 1.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 4        | 1.93%   |
| Intel Wireless-AC 9260                                     | 4        | 1.93%   |
| Intel Alder Lake-S PCH CNVi WiFi                           | 4        | 1.93%   |
| TP-Link 802.11ac NIC                                       | 3        | 1.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 3        | 1.45%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 3        | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                            | 3        | 1.45%   |
| Intel Wireless 7260                                        | 3        | 1.45%   |
| Intel Wireless 3165                                        | 3        | 1.45%   |
| Intel Comet Lake PCH CNVi WiFi                             | 3        | 1.45%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 2        | 0.97%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 2        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                         | 2        | 0.97%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter            | 2        | 0.97%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 2        | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 2        | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                      | 2        | 0.97%   |
| Ralink MT7601U Wireless Adapter                            | 2        | 0.97%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                  | 2        | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 2        | 0.97%   |
| Intel Wireless 8260                                        | 2        | 0.97%   |
| Intel Wireless 7265                                        | 2        | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                             | 2        | 0.97%   |
| Broadcom Network controller                                | 2        | 0.97%   |
| ZyXEL ZyAIR G-202 802.11bg                                 | 1        | 0.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 1        | 0.48%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                      | 1        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Realtek Semiconductor     | 196      | 49.37%  |
| Intel                     | 147      | 37.03%  |
| Qualcomm Atheros          | 16       | 4.03%   |
| Aquantia                  | 10       | 2.52%   |
| Broadcom                  | 7        | 1.76%   |
| Huawei Technologies       | 5        | 1.26%   |
| Samsung Electronics       | 4        | 1.01%   |
| ASIX Electronics          | 3        | 0.76%   |
| Xiaomi                    | 2        | 0.5%    |
| VIA Technologies          | 2        | 0.5%    |
| Nvidia                    | 2        | 0.5%    |
| Solarflare Communications | 1        | 0.25%   |
| MediaTek                  | 1        | 0.25%   |
| DisplayLink               | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161      | 39.56%  |
| Intel I211 Gigabit Network Connection                             | 26       | 6.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24       | 5.9%    |
| Intel Ethernet Controller I225-V                                  | 22       | 5.41%   |
| Intel Ethernet Connection (2) I219-V                              | 13       | 3.19%   |
| Intel Ethernet Connection I217-LM                                 | 11       | 2.7%    |
| Intel Ethernet Connection (7) I219-V                              | 11       | 2.7%    |
| Intel Ethernet Connection (2) I218-V                              | 10       | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10       | 2.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8        | 1.97%   |
| Intel 82579V Gigabit Network Connection                           | 8        | 1.97%   |
| Intel 82574L Gigabit Network Connection                           | 7        | 1.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7        | 1.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6        | 1.47%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 1.47%   |
| Intel I210 Gigabit Network Connection                             | 5        | 1.23%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4        | 0.98%   |
| Huawei MLA-L11                                                    | 4        | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 3        | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.49%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.49%   |
| Nvidia MCP61 Ethernet                                             | 2        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.49%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.49%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.49%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.49%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1        | 0.25%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.25%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.25%   |
| MediaTek moto g22                                                 | 1        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 354      | 64.72%  |
| WiFi     | 189      | 34.55%  |
| Modem    | 4        | 0.73%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 270      | 72.78%  |
| WiFi     | 101      | 27.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 209      | 58.38%  |
| 2     | 124      | 34.64%  |
| 3     | 19       | 5.31%   |
| 6     | 2        | 0.56%   |
| 4     | 2        | 0.56%   |
| 0     | 2        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 253      | 70.08%  |
| Yes  | 108      | 29.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 64       | 39.26%  |
| Cambridge Silicon Radio         | 40       | 24.54%  |
| Realtek Semiconductor           | 15       | 9.2%    |
| ASUSTek Computer                | 13       | 7.98%   |
| Broadcom                        | 7        | 4.29%   |
| MediaTek                        | 6        | 3.68%   |
| IMC Networks                    | 4        | 2.45%   |
| TP-Link                         | 3        | 1.84%   |
| Qualcomm Atheros Communications | 3        | 1.84%   |
| Edimax Technology               | 3        | 1.84%   |
| Ralink                          | 1        | 0.61%   |
| Dynex                           | 1        | 0.61%   |
| D-Link                          | 1        | 0.61%   |
| Conwise Technology              | 1        | 0.61%   |
| Apple                           | 1        | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 40       | 24.39%  |
| Intel AX200 Bluetooth                                    | 22       | 13.41%  |
| Realtek Bluetooth Radio                                  | 12       | 7.32%   |
| Intel Bluetooth Device                                   | 10       | 6.1%    |
| Intel Bluetooth wireless interface                       | 9        | 5.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8        | 4.88%   |
| MediaTek Wireless_Device                                 | 6        | 3.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 5        | 3.05%   |
| Intel AX210 Bluetooth                                    | 5        | 3.05%   |
| Intel AX201 Bluetooth                                    | 5        | 3.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 5        | 3.05%   |
| IMC Networks Bluetooth Radio                             | 4        | 2.44%   |
| ASUS ASUS USB-BT500                                      | 4        | 2.44%   |
| TP-Link UB5A Adapter                                     | 3        | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                           | 3        | 1.83%   |
| Qualcomm Atheros  Bluetooth Device                       | 3        | 1.83%   |
| ASUS Qualcomm Bluetooth 4.1                              | 2        | 1.22%   |
| ASUS Bluetooth Device                                    | 2        | 1.22%   |
| Ralink RT3290 Bluetooth                                  | 1        | 0.61%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.61%   |
| Edimax Wi-Fi AC600 Bluetooth4.0 USB Adapter              | 1        | 0.61%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter  | 1        | 0.61%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.61%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.61%   |
| D-Link DBT-122 Bluetooth adapter                         | 1        | 0.61%   |
| Conwise CW6622                                           | 1        | 0.61%   |
| Broadcom Bluetooth Controller                            | 1        | 0.61%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 1        | 0.61%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.61%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.61%   |
| ASUS Bluetooth Radio                                     | 1        | 0.61%   |
| ASUS Bluetooth Adapter                                   | 1        | 0.61%   |
| ASUS BCM20702A0                                          | 1        | 0.61%   |
| Apple Bluetooth Host Controller                          | 1        | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 207      | 30.53%  |
| AMD                      | 180      | 26.55%  |
| Nvidia                   | 173      | 25.52%  |
| C-Media Electronics      | 17       | 2.51%   |
| GN Netcom                | 9        | 1.33%   |
| JMTek                    | 6        | 0.88%   |
| Creative Labs            | 6        | 0.88%   |
| Generalplus Technology   | 5        | 0.74%   |
| VIA Technologies         | 4        | 0.59%   |
| Texas Instruments        | 4        | 0.59%   |
| Micro Star International | 4        | 0.59%   |
| Logitech                 | 4        | 0.59%   |
| Kingston Technology      | 4        | 0.59%   |
| Tenx Technology          | 3        | 0.44%   |
| Razer USA                | 3        | 0.44%   |
| Blue Microphones         | 3        | 0.44%   |
| SteelSeries ApS          | 2        | 0.29%   |
| M-Audio                  | 2        | 0.29%   |
| KORG                     | 2        | 0.29%   |
| HECATE G2 GAMING HEADSET | 2        | 0.29%   |
| Focusrite-Novation       | 2        | 0.29%   |
| Corsair                  | 2        | 0.29%   |
| ASUSTek Computer         | 2        | 0.29%   |
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
| KTMicro                  | 1        | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 46       | 5.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 29       | 3.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 3.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27       | 3.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22       | 2.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 20       | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20       | 2.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 19       | 2.42%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 2.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 17       | 2.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17       | 2.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 17       | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16       | 2.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 15       | 1.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15       | 1.91%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 1.78%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 14       | 1.78%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13       | 1.66%   |
| Nvidia TU116 High Definition Audio Controller                              | 12       | 1.53%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 12       | 1.53%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 11       | 1.4%    |
| Nvidia GP104 High Definition Audio Controller                              | 10       | 1.27%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 10       | 1.27%   |
| Intel Alder Lake-S HD Audio Controller                                     | 10       | 1.27%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9        | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8        | 1.02%   |
| Nvidia TU104 HD Audio Controller                                           | 8        | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 8        | 1.02%   |
| AMD FCH Azalia Controller                                                  | 8        | 1.02%   |
| Nvidia High Definition Audio Controller                                    | 7        | 0.89%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 7        | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                              | 6        | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6        | 0.76%   |
| Nvidia GF119 HDMI Audio Controller                                         | 6        | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 6        | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 6        | 0.76%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 6        | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 56       | 23.14%  |
| Corsair             | 40       | 16.53%  |
| G.Skill             | 28       | 11.57%  |
| Unknown             | 21       | 8.68%   |
| Samsung Electronics | 18       | 7.44%   |
| Crucial             | 18       | 7.44%   |
| Micron Technology   | 13       | 5.37%   |
| SK hynix            | 10       | 4.13%   |
| Team                | 6        | 2.48%   |
| Patriot             | 5        | 2.07%   |
| Ramaxel Technology  | 4        | 1.65%   |
| PNY                 | 3        | 1.24%   |
| AMD                 | 3        | 1.24%   |
| Unknown             | 3        | 1.24%   |
| Silicon Power       | 2        | 0.83%   |
| Unknown (ABCD)      | 1        | 0.41%   |
| Unifosa             | 1        | 0.41%   |
| Teikon              | 1        | 0.41%   |
| Smart               | 1        | 0.41%   |
| Qumo                | 1        | 0.41%   |
| Neo Forza           | 1        | 0.41%   |
| Nanya Technology    | 1        | 0.41%   |
| Lexar               | 1        | 0.41%   |
| Kingmax             | 1        | 0.41%   |
| Avant               | 1        | 0.41%   |
| Atermiter           | 1        | 0.41%   |
| A-DATA Technology   | 1        | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 5        | 1.85%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                    | 3        | 1.11%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s  | 3        | 1.11%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s  | 3        | 1.11%   |
| Unknown                                                 | 3        | 1.11%   |
| Unknown RAM Module 2GB DIMM 400MT/s                     | 2        | 0.74%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                    | 2        | 0.74%   |
| Unknown RAM 1866 CL10 Series 8192MB DIMM DDR3 933MT/s   | 2        | 0.74%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s      | 2        | 0.74%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2667MT/s   | 2        | 0.74%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 2        | 0.74%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 2        | 0.74%   |
| Samsung RAM M378A5244CB0-CRC 4096MB DIMM DDR4 3066MT/s  | 2        | 0.74%   |
| Ramaxel RAM RMR5040ED58E9W1600 4GB DIMM DDR3 1600MT/s   | 2        | 0.74%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8GB DIMM DDR4 3600MT/s     | 2        | 0.74%   |
| Patriot RAM PSD38G16002 8GB DIMM DDR3 1600MT/s          | 2        | 0.74%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8GB DIMM DDR4 2667MT/s      | 2        | 0.74%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s   | 2        | 0.74%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s   | 2        | 0.74%   |
| Kingston RAM 9905471-079.A00LF 8GB DIMM DDR3 1600MT/s   | 2        | 0.74%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s  | 2        | 0.74%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s      | 2        | 0.74%   |
| G.Skill RAM F4-3200C16-16GIS 16384MB DIMM DDR4 3600MT/s | 2        | 0.74%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s     | 2        | 0.74%   |
| G.Skill RAM F4-2133C15-8GVR 8GB DIMM DDR4 2133MT/s      | 2        | 0.74%   |
| G.Skill RAM F3-1600C9-8GXM 8GB DIMM DDR3 1867MT/s       | 2        | 0.74%   |
| Crucial RAM CT8G4DFRA266.C8FE 8GB DIMM DDR4 2933MT/s    | 2        | 0.74%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s   | 2        | 0.74%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s  | 2        | 0.74%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s   | 2        | 0.74%   |
| AMD RAM R9S48G3206U2S 8GB DIMM DDR4 3333MT/s            | 2        | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 800MT/s                | 1        | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s               | 1        | 0.37%   |
| Unknown RAM Module 8GB DIMM 400MT/s                     | 1        | 0.37%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                    | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s               | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR2 266MT/s                | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                | 1        | 0.37%   |
| Unknown RAM Module 4GB DIMM 667MT/s                     | 1        | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 130      | 59.63%  |
| DDR3    | 58       | 26.61%  |
| Unknown | 10       | 4.59%   |
| DDR5    | 8        | 3.67%   |
| SDRAM   | 5        | 2.29%   |
| DDR2    | 5        | 2.29%   |
| LPDDR4  | 1        | 0.46%   |
| DDR     | 1        | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 207      | 96.28%  |
| SODIMM | 7        | 3.26%   |
| RIMM   | 1        | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 99       | 41.77%  |
| 16384 | 55       | 23.21%  |
| 4096  | 41       | 17.3%   |
| 2048  | 22       | 9.28%   |
| 32768 | 19       | 8.02%   |
| 1024  | 1        | 0.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 1600  | 37       | 15.1%   |
| 3600  | 25       | 10.2%   |
| 3200  | 25       | 10.2%   |
| 1333  | 22       | 8.98%   |
| 2400  | 18       | 7.35%   |
| 2667  | 17       | 6.94%   |
| 2133  | 12       | 4.9%    |
| 3800  | 7        | 2.86%   |
| 3000  | 7        | 2.86%   |
| 2666  | 7        | 2.86%   |
| 1867  | 5        | 2.04%   |
| 3066  | 4        | 1.63%   |
| 2933  | 4        | 1.63%   |
| 2800  | 4        | 1.63%   |
| 1066  | 4        | 1.63%   |
| 4800  | 3        | 1.22%   |
| 3666  | 3        | 1.22%   |
| 3333  | 3        | 1.22%   |
| 1866  | 3        | 1.22%   |
| 800   | 3        | 1.22%   |
| 400   | 3        | 1.22%   |
| 6000  | 2        | 0.82%   |
| 3866  | 2        | 0.82%   |
| 3266  | 2        | 0.82%   |
| 1648  | 2        | 0.82%   |
| 52217 | 1        | 0.41%   |
| 5808  | 1        | 0.41%   |
| 5800  | 1        | 0.41%   |
| 5200  | 1        | 0.41%   |
| 4133  | 1        | 0.41%   |
| 4000  | 1        | 0.41%   |
| 3933  | 1        | 0.41%   |
| 3733  | 1        | 0.41%   |
| 3533  | 1        | 0.41%   |
| 3500  | 1        | 0.41%   |
| 3467  | 1        | 0.41%   |
| 3466  | 1        | 0.41%   |
| 3400  | 1        | 0.41%   |
| 3334  | 1        | 0.41%   |
| 2176  | 1        | 0.41%   |

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
| Logitech                      | 40       | 44.44%  |
| Microdia                      | 8        | 8.89%   |
| Generalplus Technology        | 5        | 5.56%   |
| Samsung Electronics           | 4        | 4.44%   |
| Sunplus Innovation Technology | 3        | 3.33%   |
| Microsoft                     | 3        | 3.33%   |
| KYE Systems (Mouse Systems)   | 3        | 3.33%   |
| Unknown                       | 2        | 2.22%   |
| Realtek Semiconductor         | 2        | 2.22%   |
| Jieli Technology              | 2        | 2.22%   |
| ARC International             | 2        | 2.22%   |
| Alcor Micro                   | 2        | 2.22%   |
| SunplusIT                     | 1        | 1.11%   |
| Sonix Technology              | 1        | 1.11%   |
| Silicon Motion                | 1        | 1.11%   |
| Razer USA                     | 1        | 1.11%   |
| MacroSilicon                  | 1        | 1.11%   |
| LG Electronics                | 1        | 1.11%   |
| IMC Networks                  | 1        | 1.11%   |
| Hewlett-Packard               | 1        | 1.11%   |
| Google                        | 1        | 1.11%   |
| GEMBIRD                       | 1        | 1.11%   |
| Fifine K420                   | 1        | 1.11%   |
| Cubeternet                    | 1        | 1.11%   |
| Creative Technology           | 1        | 1.11%   |
| Asuscom Network               | 1        | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920               | 14       | 15.56%  |
| Logitech Webcam C270                      | 8        | 8.89%   |
| Samsung Galaxy series, misc. (MTP mode)   | 4        | 4.44%   |
| Microdia Integrated Camera                | 3        | 3.33%   |
| Logitech HD Webcam C910                   | 3        | 3.33%   |
| Logitech C922 Pro Stream Webcam           | 3        | 3.33%   |
| Unknown HD camera                         | 2        | 2.22%   |
| Microdia Webcam Vitade AF                 | 2        | 2.22%   |
| Logitech Webcam C170                      | 2        | 2.22%   |
| Logitech HD Webcam C525                   | 2        | 2.22%   |
| KYE Systems (Mouse Systems) Genius Webcam | 2        | 2.22%   |
| Jieli USB PHY 2.0                         | 2        | 2.22%   |
| Generalplus WEB CAM                       | 2        | 2.22%   |
| Generalplus CAMERA - UVC                  | 2        | 2.22%   |
| ARC International Camera                  | 2        | 2.22%   |
| Alcor Micro USB 2.0 PC Camera             | 2        | 2.22%   |
| SunplusIT USB 2.0 Camera                  | 1        | 1.11%   |
| Sunplus UC40M Audio                       | 1        | 1.11%   |
| Sunplus SPCA2281 Web Camera               | 1        | 1.11%   |
| Sunplus ezcap U3 capture-04               | 1        | 1.11%   |
| Sonix USB 2.0 Camera                      | 1        | 1.11%   |
| Silicon Motion 300k Pixel Camera          | 1        | 1.11%   |
| Realtek USB Camera                        | 1        | 1.11%   |
| Realtek HK 2M CAM                         | 1        | 1.11%   |
| Razer USA Razer Kiyo Pro                  | 1        | 1.11%   |
| Microsoft MicrosoftÂ LifeCam Studio      | 1        | 1.11%   |
| Microsoft LifeCam HD-3000                 | 1        | 1.11%   |
| Microsoft LifeCam Cinema                  | 1        | 1.11%   |
| Microdia PC Microscope camera             | 1        | 1.11%   |
| Microdia GC02M2                           | 1        | 1.11%   |
| Microdia Camera                           | 1        | 1.11%   |
| MacroSilicon USB Video                    | 1        | 1.11%   |
| Logitech Webcam C600                      | 1        | 1.11%   |
| Logitech Webcam C310                      | 1        | 1.11%   |
| Logitech Webcam C300                      | 1        | 1.11%   |
| Logitech QuickCam Pro for Notebooks       | 1        | 1.11%   |
| Logitech QuickCam Pro 9000                | 1        | 1.11%   |
| Logitech QuickCam Communicate MP/S5500    | 1        | 1.11%   |
| Logitech HD Webcam C615                   | 1        | 1.11%   |
| Logitech BRIO Ultra HD Webcam             | 1        | 1.11%   |

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
| OmniKey               | 2        | 40%     |
| SCM Microsystems      | 1        | 20%     |
| Gemalto (was Gemplus) | 1        | 20%     |
| BIT4ID                | 1        | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| SCM Microsystems SCR331 SmartCard Reader          | 1        | 20%     |
| OmniKey CardMan 3021 / 3121                       | 1        | 20%     |
| OmniKey CardMan 1021                              | 1        | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 20%     |
| BIT4ID miniLector EVO                             | 1        | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 293      | 80.05%  |
| 1     | 61       | 16.67%  |
| 2     | 9        | 2.46%   |
| 3     | 3        | 0.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 24       | 28.92%  |
| Net/wireless             | 22       | 26.51%  |
| Unassigned class         | 12       | 14.46%  |
| Multimedia controller    | 4        | 4.82%   |
| Camera                   | 4        | 4.82%   |
| Bluetooth                | 4        | 4.82%   |
| Fingerprint reader       | 3        | 3.61%   |
| Communication controller | 3        | 3.61%   |
| Chipcard                 | 3        | 3.61%   |
| Sound                    | 2        | 2.41%   |
| Net/ethernet             | 1        | 1.2%    |
| Modem                    | 1        | 1.2%    |

