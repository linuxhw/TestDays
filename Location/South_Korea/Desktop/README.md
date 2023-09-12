Linux in South Korea - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

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

Total: 235

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MAG Z790 TOMAHAWK WIFI      | [da16406c15](https://linux-hardware.org/?probe=da16406c15) | Sep 01, 2023 |
| Unknown       | Unknown                     | [269a4ac17d](https://linux-hardware.org/?probe=269a4ac17d) | Aug 28, 2023 |
| Gigabyte      | B75M-D3H                    | [215ff35620](https://linux-hardware.org/?probe=215ff35620) | Aug 27, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [2bb217b4df](https://linux-hardware.org/?probe=2bb217b4df) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| Unknown       | Unknown                     | [a9f30f8dd0](https://linux-hardware.org/?probe=a9f30f8dd0) | Aug 11, 2023 |
| Gigabyte      | TRX40 DESIGNARE             | [a71dc0067b](https://linux-hardware.org/?probe=a71dc0067b) | Aug 07, 2023 |
| ASUSTek       | Z170-A                      | [87a26e01e6](https://linux-hardware.org/?probe=87a26e01e6) | Jul 06, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [669754af36](https://linux-hardware.org/?probe=669754af36) | Jul 02, 2023 |
| Gigabyte      | A620M GAMING X              | [76238267ab](https://linux-hardware.org/?probe=76238267ab) | Jul 01, 2023 |
| ASUSTek       | PRIME A520M-K               | [2fe8080014](https://linux-hardware.org/?probe=2fe8080014) | Jun 11, 2023 |
| ASRock        | B150M Pro4                  | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASRock        | X670E Taichi                | [6616151cda](https://linux-hardware.org/?probe=6616151cda) | Jun 04, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [f4fce509ae](https://linux-hardware.org/?probe=f4fce509ae) | May 18, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [abb92fef7d](https://linux-hardware.org/?probe=abb92fef7d) | May 06, 2023 |
| MSI           | B450 TOMAHAWK               | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| ASRock        | Z370 Extreme4               | [0f126ade53](https://linux-hardware.org/?probe=0f126ade53) | Apr 29, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [dca43563dd](https://linux-hardware.org/?probe=dca43563dd) | Apr 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [658450824e](https://linux-hardware.org/?probe=658450824e) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bab80153bf](https://linux-hardware.org/?probe=bab80153bf) | Apr 22, 2023 |
| Dell          | 0MR5MV A00                  | [ed13b58a51](https://linux-hardware.org/?probe=ed13b58a51) | Apr 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [30fdc58d69](https://linux-hardware.org/?probe=30fdc58d69) | Apr 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [dfd9900ccf](https://linux-hardware.org/?probe=dfd9900ccf) | Mar 30, 2023 |
| MSI           | B450M MORTAR                | [7febdf82c0](https://linux-hardware.org/?probe=7febdf82c0) | Mar 28, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | [19a060d86d](https://linux-hardware.org/?probe=19a060d86d) | Mar 20, 2023 |
| ECS2          | EASTWOOD2 V1.0              | [822e4fa621](https://linux-hardware.org/?probe=822e4fa621) | Mar 11, 2023 |
| Dell          | 0TNXNR A01                  | [30fa0c9cb7](https://linux-hardware.org/?probe=30fa0c9cb7) | Mar 09, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | [484e0755de](https://linux-hardware.org/?probe=484e0755de) | Feb 26, 2023 |
| ASUSTek       | P8H67-M                     | [a3ea522d78](https://linux-hardware.org/?probe=a3ea522d78) | Feb 23, 2023 |
| Samsung       | DB400T7Y-Z202C SGL9325A0... | [b75c596e7f](https://linux-hardware.org/?probe=b75c596e7f) | Feb 21, 2023 |
| Gigabyte      | B85M-D3V-A-SI               | [5b452754c0](https://linux-hardware.org/?probe=5b452754c0) | Feb 19, 2023 |
| ASRock        | Z370 Pro4                   | [bafba5486b](https://linux-hardware.org/?probe=bafba5486b) | Feb 16, 2023 |
| ASRock        | Z790 Pro RS WiFi            | [c530bf4283](https://linux-hardware.org/?probe=c530bf4283) | Feb 11, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | [b9fb1c5111](https://linux-hardware.org/?probe=b9fb1c5111) | Feb 01, 2023 |
| ASUSTek       | GA35DX                      | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [bb5e9ccd98](https://linux-hardware.org/?probe=bb5e9ccd98) | Jan 27, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [d54e25d6fb](https://linux-hardware.org/?probe=d54e25d6fb) | Jan 27, 2023 |
| ASRock        | B560M Pro4                  | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| ASUSTek       | H110M-K                     | [8975ee2ce6](https://linux-hardware.org/?probe=8975ee2ce6) | Jan 14, 2023 |
| Unknown       | Unknown                     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| ELSKY         | M219FN-6C                   | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eda96539d7](https://linux-hardware.org/?probe=eda96539d7) | Dec 26, 2022 |
| ASRock        | H470M Pro4                  | [b69ccc3353](https://linux-hardware.org/?probe=b69ccc3353) | Dec 22, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | [7020686bc7](https://linux-hardware.org/?probe=7020686bc7) | Dec 19, 2022 |
| Huanan        | X58-RX3.0 V110              | [32e6a4d219](https://linux-hardware.org/?probe=32e6a4d219) | Dec 10, 2022 |
| Lenovo        | 370A NOK                    | [b06728a8bf](https://linux-hardware.org/?probe=b06728a8bf) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | [6047fbcb06](https://linux-hardware.org/?probe=6047fbcb06) | Dec 05, 2022 |
| Dell          | 00D7V6 A00                  | [9aebb424cc](https://linux-hardware.org/?probe=9aebb424cc) | Dec 05, 2022 |
| Gigabyte      | Z490 AORUS XTREME WF        | [6d4f229020](https://linux-hardware.org/?probe=6d4f229020) | Nov 29, 2022 |
| Gigabyte      | 990FXA-UD3                  | [d5c76baafa](https://linux-hardware.org/?probe=d5c76baafa) | Nov 18, 2022 |
| ASUSTek       | P8H67                       | [0ccbbf67e8](https://linux-hardware.org/?probe=0ccbbf67e8) | Nov 10, 2022 |
| ASUSTek       | PRIME B365M-K               | [e2e281d38d](https://linux-hardware.org/?probe=e2e281d38d) | Nov 03, 2022 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [bdc77dbc53](https://linux-hardware.org/?probe=bdc77dbc53) | Nov 03, 2022 |
| WTM           | W-N95 B0                    | [56611d3c8f](https://linux-hardware.org/?probe=56611d3c8f) | Oct 31, 2022 |
| HP            | 8425                        | [6d26af6597](https://linux-hardware.org/?probe=6d26af6597) | Oct 27, 2022 |
| Gigabyte      | B360M D3H-CF                | [ad1d808caa](https://linux-hardware.org/?probe=ad1d808caa) | Oct 14, 2022 |
| MSI           | A320M-A PRO                 | [40dd630e96](https://linux-hardware.org/?probe=40dd630e96) | Oct 05, 2022 |
| ASUSTek       | PRIME B550M-K               | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| Gigabyte      | MZBAYAP-00                  | [2fccc9ec66](https://linux-hardware.org/?probe=2fccc9ec66) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD3                  | [5c2eac6d83](https://linux-hardware.org/?probe=5c2eac6d83) | Sep 22, 2022 |
| Gigabyte      | 990FXA-UD3                  | [ea7d5b0424](https://linux-hardware.org/?probe=ea7d5b0424) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | [156da35e98](https://linux-hardware.org/?probe=156da35e98) | Aug 24, 2022 |
| MSI           | MAG B660M MORTAR WIFI       | [4e1b75908c](https://linux-hardware.org/?probe=4e1b75908c) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASRock        | B250M Pro4                  | [59704c823a](https://linux-hardware.org/?probe=59704c823a) | Jul 29, 2022 |
| PCPartner     | MILANO-P Rev.00             | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| HP            | 8906 SMVB                   | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| ASUSTek       | P8H67                       | [8971b67abc](https://linux-hardware.org/?probe=8971b67abc) | Jul 08, 2022 |
| Gigabyte      | B360M D3H-CF                | [251bc4d58d](https://linux-hardware.org/?probe=251bc4d58d) | Jul 04, 2022 |
| Gigabyte      | MQLP5AP-00                  | [8014a14842](https://linux-hardware.org/?probe=8014a14842) | Jun 30, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | [2d23125cd0](https://linux-hardware.org/?probe=2d23125cd0) | May 15, 2022 |
| Gigabyte      | X99-SLI-CF                  | [55f1cc4480](https://linux-hardware.org/?probe=55f1cc4480) | May 10, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| MSI           | H110M PRO-VD PLUS           | [80bdc044eb](https://linux-hardware.org/?probe=80bdc044eb) | May 01, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [9a15614b1e](https://linux-hardware.org/?probe=9a15614b1e) | Apr 13, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [90aa422ea2](https://linux-hardware.org/?probe=90aa422ea2) | Mar 31, 2022 |
| MSI           | X99A GAMING PRO CARBON      | [fa4526e9f3](https://linux-hardware.org/?probe=fa4526e9f3) | Mar 24, 2022 |
| ASUSTek       | P8H67                       | [05cdb119e9](https://linux-hardware.org/?probe=05cdb119e9) | Mar 07, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [14f8855baa](https://linux-hardware.org/?probe=14f8855baa) | Feb 03, 2022 |
| ASUSTek       | PRIME B350M-A               | [7843ddc3fb](https://linux-hardware.org/?probe=7843ddc3fb) | Dec 24, 2021 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | [151434ab61](https://linux-hardware.org/?probe=151434ab61) | Dec 21, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [4d11bd6b59](https://linux-hardware.org/?probe=4d11bd6b59) | Nov 20, 2021 |
| ASUSTek       | PRIME B350M-A               | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| ASRock        | M3A770DE                    | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| ASRock        | AB350M Pro4                 | [24de612862](https://linux-hardware.org/?probe=24de612862) | Aug 31, 2021 |
| ASUSTek       | Z170-A                      | [3abd60af90](https://linux-hardware.org/?probe=3abd60af90) | Aug 22, 2021 |
| ASUSTek       | Z170-A                      | [e523ad86d2](https://linux-hardware.org/?probe=e523ad86d2) | Aug 02, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | [1e96b02bf3](https://linux-hardware.org/?probe=1e96b02bf3) | Jul 28, 2021 |
| ASUSTek       | P5QL/EPU                    | [972c061d3c](https://linux-hardware.org/?probe=972c061d3c) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| ASUSTek       | Z87M-PLUS                   | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | 3397                        | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| ASRockRack    | WC621D8A-2T                 | [d9c47162dc](https://linux-hardware.org/?probe=d9c47162dc) | Jun 25, 2021 |
| ASRockRack    | WC621D8A-2T                 | [b568edaa5e](https://linux-hardware.org/?probe=b568edaa5e) | Jun 25, 2021 |
| Gigabyte      | B75M-D3V                    | [9aaad9b2d4](https://linux-hardware.org/?probe=9aaad9b2d4) | Jun 07, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [be07a70b2e](https://linux-hardware.org/?probe=be07a70b2e) | May 27, 2021 |
| ASUSTek       | P5QL/EPU                    | [965bc51c8d](https://linux-hardware.org/?probe=965bc51c8d) | May 06, 2021 |
| ASRock        | A75M-ITX                    | [1ad3e30eec](https://linux-hardware.org/?probe=1ad3e30eec) | May 03, 2021 |
| Gigabyte      | A320M-S2H-CF                | [72d14b2ed7](https://linux-hardware.org/?probe=72d14b2ed7) | Apr 23, 2021 |
| Gigabyte      | A320M-S2H-CF                | [2300013263](https://linux-hardware.org/?probe=2300013263) | Apr 18, 2021 |
| ASRock        | FM2A88M-HD+ R2.0            | [fdac2fa1fd](https://linux-hardware.org/?probe=fdac2fa1fd) | Apr 14, 2021 |
| ASUSTek       | P8H67                       | [b17bb9b31a](https://linux-hardware.org/?probe=b17bb9b31a) | Apr 12, 2021 |
| ASRock        | AB350 Pro4                  | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| Gigabyte      | 945GCMX-S2                  | [d4399ab9d0](https://linux-hardware.org/?probe=d4399ab9d0) | Apr 06, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | [b55dc75624](https://linux-hardware.org/?probe=b55dc75624) | Mar 20, 2021 |
| Gigabyte      | B360M DS3H                  | [f7740321e0](https://linux-hardware.org/?probe=f7740321e0) | Mar 18, 2021 |
| MSI           | B75MA-E33                   | [e459ded47c](https://linux-hardware.org/?probe=e459ded47c) | Mar 10, 2021 |
| ASUSTek       | PRIME Z490-A                | [15c42588c8](https://linux-hardware.org/?probe=15c42588c8) | Mar 04, 2021 |
| ASUSTek       | WS X299 SAGE                | [541a436664](https://linux-hardware.org/?probe=541a436664) | Mar 02, 2021 |
| ASRock        | H110M-HDVP2                 | [8e6128682d](https://linux-hardware.org/?probe=8e6128682d) | Feb 28, 2021 |
| ASRock        | H110M-HDVP2                 | [778fcc3093](https://linux-hardware.org/?probe=778fcc3093) | Feb 28, 2021 |
| Gigabyte      | B75M-D3H                    | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | [8dd1ebdfb8](https://linux-hardware.org/?probe=8dd1ebdfb8) | Feb 25, 2021 |
| MSI           | B450M MORTAR MAX            | [a222f11ebf](https://linux-hardware.org/?probe=a222f11ebf) | Feb 09, 2021 |
| ASUSTek       | PRIME B350M-A               | [0de61d3d11](https://linux-hardware.org/?probe=0de61d3d11) | Feb 06, 2021 |
| ASUSTek       | Z170-A                      | [65aa2efd23](https://linux-hardware.org/?probe=65aa2efd23) | Feb 05, 2021 |
| ASRock        | H110M-HDVP2                 | [27d324f7e1](https://linux-hardware.org/?probe=27d324f7e1) | Feb 04, 2021 |
| MSI           | B360M PRO-VDH               | [59b7bd58df](https://linux-hardware.org/?probe=59b7bd58df) | Jan 30, 2021 |
| MSI           | Z490-A PRO                  | [a29449d114](https://linux-hardware.org/?probe=a29449d114) | Jan 27, 2021 |
| MSI           | Z490-A PRO                  | [9595d4107b](https://linux-hardware.org/?probe=9595d4107b) | Jan 26, 2021 |
| ASRock        | B450M Steel Legend          | [a6226b7401](https://linux-hardware.org/?probe=a6226b7401) | Jan 20, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [ffa2d06213](https://linux-hardware.org/?probe=ffa2d06213) | Jan 05, 2021 |
| HP            | 18E7                        | [e9590ba71a](https://linux-hardware.org/?probe=e9590ba71a) | Jan 01, 2021 |
| ASUSTek       | PRIME B250M-A               | [77ad294d93](https://linux-hardware.org/?probe=77ad294d93) | Dec 20, 2020 |
| MSI           | B360M PRO-VDH               | [ae9a14bb34](https://linux-hardware.org/?probe=ae9a14bb34) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | [b1476b4c51](https://linux-hardware.org/?probe=b1476b4c51) | Dec 09, 2020 |
| ASRock        | H81M-DGS R2.0               | [a706242b44](https://linux-hardware.org/?probe=a706242b44) | Dec 05, 2020 |
| MSI           | B360M PRO-VDH               | [f16f5d30de](https://linux-hardware.org/?probe=f16f5d30de) | Dec 05, 2020 |
| ASUSTek       | PRIME B250M-A               | [425fda9034](https://linux-hardware.org/?probe=425fda9034) | Dec 04, 2020 |
| ASUSTek       | P8B75-M LX PLUS             | [e6f9b2cf07](https://linux-hardware.org/?probe=e6f9b2cf07) | Dec 04, 2020 |
| ASRock        | B85M Pro4                   | [0354f4d9bc](https://linux-hardware.org/?probe=0354f4d9bc) | Nov 25, 2020 |
| ASRock        | B85M Pro4                   | [8dcc7ce213](https://linux-hardware.org/?probe=8dcc7ce213) | Nov 22, 2020 |
| Gigabyte      | H97M-D3H                    | [f9b97f5918](https://linux-hardware.org/?probe=f9b97f5918) | Nov 22, 2020 |
| ECS           | G31T-M7                     | [f93ce4415e](https://linux-hardware.org/?probe=f93ce4415e) | Nov 12, 2020 |
| PC Partner... | A236 0A                     | [14030da2e5](https://linux-hardware.org/?probe=14030da2e5) | Nov 10, 2020 |
| PC Partner... | A236 0A                     | [fc118d784c](https://linux-hardware.org/?probe=fc118d784c) | Nov 10, 2020 |
| ASUSTek       | P7P55D                      | [11e315efbd](https://linux-hardware.org/?probe=11e315efbd) | Nov 07, 2020 |
| ASRock        | H81M-DGS R2.0               | [9b33944102](https://linux-hardware.org/?probe=9b33944102) | Nov 04, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [39cc53a5e3](https://linux-hardware.org/?probe=39cc53a5e3) | Oct 13, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [3aba059c2c](https://linux-hardware.org/?probe=3aba059c2c) | Sep 24, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [c535500f86](https://linux-hardware.org/?probe=c535500f86) | Sep 24, 2020 |
| ASRock        | H310M-STX/COM               | [5b22b538ee](https://linux-hardware.org/?probe=5b22b538ee) | Sep 23, 2020 |
| ASUSTek       | P5LD2                       | [56efa94b22](https://linux-hardware.org/?probe=56efa94b22) | Sep 09, 2020 |
| ASUSTek       | P5LD2                       | [00f5eba2ea](https://linux-hardware.org/?probe=00f5eba2ea) | Sep 09, 2020 |
| Gigabyte      | B75M-D3H                    | [934bb9c2ef](https://linux-hardware.org/?probe=934bb9c2ef) | Sep 09, 2020 |
| ASRock        | H310CM-HDV                  | [7acf41575b](https://linux-hardware.org/?probe=7acf41575b) | Sep 09, 2020 |
| ASRock        | H81M-HDS                    | [8b55873fbd](https://linux-hardware.org/?probe=8b55873fbd) | Sep 07, 2020 |
| Foxconn       | H61MXE                      | [7a31014e98](https://linux-hardware.org/?probe=7a31014e98) | Sep 04, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| Lenovo        | ThinkServer TS140           | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| ASRock        | H61M-HVGS                   | [36c19012ed](https://linux-hardware.org/?probe=36c19012ed) | Jul 25, 2020 |
| ASRock        | H61M-HVGS                   | [ea9287adc1](https://linux-hardware.org/?probe=ea9287adc1) | Jul 25, 2020 |
| ASRock        | Z390 Taichi                 | [ce94a11d8b](https://linux-hardware.org/?probe=ce94a11d8b) | Jun 26, 2020 |
| Huanan        | X99-F8                      | [74f9976527](https://linux-hardware.org/?probe=74f9976527) | Jun 25, 2020 |
| Gigabyte      | X570 GAMING X               | [cbd4390e56](https://linux-hardware.org/?probe=cbd4390e56) | Jun 23, 2020 |
| ASRock        | Z390 Taichi                 | [6989759d9c](https://linux-hardware.org/?probe=6989759d9c) | Jun 21, 2020 |
| ASRock        | Z390M Pro4                  | [eb53bb80ea](https://linux-hardware.org/?probe=eb53bb80ea) | Jun 20, 2020 |
| ECS           | H81H3-MV                    | [d39e7a605d](https://linux-hardware.org/?probe=d39e7a605d) | Jun 20, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [c05f965fec](https://linux-hardware.org/?probe=c05f965fec) | Jun 17, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | [835aa152dd](https://linux-hardware.org/?probe=835aa152dd) | Jun 16, 2020 |
| Unknown       | Unknown                     | [e6e0a356a2](https://linux-hardware.org/?probe=e6e0a356a2) | May 19, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [e526204afd](https://linux-hardware.org/?probe=e526204afd) | May 16, 2020 |
| ASUSTek       | P5B-Deluxe                  | [24ce1a41e9](https://linux-hardware.org/?probe=24ce1a41e9) | May 16, 2020 |
| HP            | 158A                        | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [d5b8f91a79](https://linux-hardware.org/?probe=d5b8f91a79) | May 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | [c259824b35](https://linux-hardware.org/?probe=c259824b35) | May 09, 2020 |
| ASRock        | X470 Taichi                 | [261241bb2f](https://linux-hardware.org/?probe=261241bb2f) | May 07, 2020 |
| Biostar       | H61MH                       | [aacc6bcb68](https://linux-hardware.org/?probe=aacc6bcb68) | May 07, 2020 |
| Gigabyte      | H81M-DS2V                   | [36cbf906a0](https://linux-hardware.org/?probe=36cbf906a0) | May 07, 2020 |
| Gigabyte      | B75M-D3V                    | [a4130d0549](https://linux-hardware.org/?probe=a4130d0549) | Apr 29, 2020 |
| ASRock        | G31M-S                      | [6a55997759](https://linux-hardware.org/?probe=6a55997759) | Apr 28, 2020 |
| ASUSTek       | B85M-G                      | [5d58ef4cec](https://linux-hardware.org/?probe=5d58ef4cec) | Apr 19, 2020 |
| ASUSTek       | Rampage V EXTREME           | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| MSI           | B250M PRO-VD                | [d797379451](https://linux-hardware.org/?probe=d797379451) | Apr 13, 2020 |
| Gigabyte      | TRX40 AORUS XTREME          | [0f078bd16f](https://linux-hardware.org/?probe=0f078bd16f) | Apr 11, 2020 |
| Dell          | 0Y2MRG A01                  | [053b33bcbc](https://linux-hardware.org/?probe=053b33bcbc) | Apr 05, 2020 |
| ASUSTek       | P5K                         | [8ec1f94a9f](https://linux-hardware.org/?probe=8ec1f94a9f) | Apr 05, 2020 |
| ASUSTek       | H110M-F                     | [c5861fb518](https://linux-hardware.org/?probe=c5861fb518) | Mar 31, 2020 |
| ASUSTek       | PRIME A320M-K               | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [c54c1dcc2f](https://linux-hardware.org/?probe=c54c1dcc2f) | Mar 18, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [de7d898371](https://linux-hardware.org/?probe=de7d898371) | Mar 16, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | [b5def2acfb](https://linux-hardware.org/?probe=b5def2acfb) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | [ca363a8ddc](https://linux-hardware.org/?probe=ca363a8ddc) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | [2b56d27ead](https://linux-hardware.org/?probe=2b56d27ead) | Mar 02, 2020 |
| ECS           | H61H2-MV                    | [8b42886c6f](https://linux-hardware.org/?probe=8b42886c6f) | Mar 02, 2020 |
| ASUSTek       | P8H61-MX R2.0               | [fd4e08618e](https://linux-hardware.org/?probe=fd4e08618e) | Feb 28, 2020 |
| MSI           | B350M MORTAR                | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| LattePanda    | Alpha                       | [eb27db2005](https://linux-hardware.org/?probe=eb27db2005) | Feb 01, 2020 |
| LattePanda    | Alpha                       | [72a1cd44a0](https://linux-hardware.org/?probe=72a1cd44a0) | Feb 01, 2020 |
| MSI           | B350M MORTAR                | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | [b0a90d8478](https://linux-hardware.org/?probe=b0a90d8478) | Jan 02, 2020 |
| ASUSTek       | PRIME A320M-K               | [2fb35125e3](https://linux-hardware.org/?probe=2fb35125e3) | Dec 22, 2019 |
| Gigabyte      | 945GM-S2                    | [c6b23ec021](https://linux-hardware.org/?probe=c6b23ec021) | Dec 07, 2019 |
| ECS           | H81H3-M4                    | [2a11653db0](https://linux-hardware.org/?probe=2a11653db0) | Oct 05, 2019 |
| ASUSTek       | PRIME H310M-R R2.0          | [37c348afcc](https://linux-hardware.org/?probe=37c348afcc) | Sep 11, 2019 |
| ECS           | G41T-M6                     | [91cafa3b5b](https://linux-hardware.org/?probe=91cafa3b5b) | Aug 30, 2019 |
| Gigabyte      | H81M-DS2V                   | [68069aeff1](https://linux-hardware.org/?probe=68069aeff1) | Aug 21, 2019 |
| ASRock        | Z390 Extreme4               | [8c8af8b557](https://linux-hardware.org/?probe=8c8af8b557) | Jul 13, 2019 |
| ASRock        | AB350M Pro4                 | [88354e515f](https://linux-hardware.org/?probe=88354e515f) | Jul 08, 2019 |
| ASRock        | AB350M Pro4                 | [7506cb2993](https://linux-hardware.org/?probe=7506cb2993) | Jul 08, 2019 |
| Gigabyte      | GA-MA790FX-DS5              | [727b2b7099](https://linux-hardware.org/?probe=727b2b7099) | Jun 27, 2019 |
| AMD           | R690A-M2T                   | [da36474b90](https://linux-hardware.org/?probe=da36474b90) | Jun 18, 2019 |
| Gigabyte      | AB350M-DS2-CF               | [553908ddb3](https://linux-hardware.org/?probe=553908ddb3) | Jun 09, 2019 |
| ASUSTek       | PRIME X399-A                | [ae94045380](https://linux-hardware.org/?probe=ae94045380) | May 29, 2019 |
| Lenovo        | NO DPK                      | [b89b8c9364](https://linux-hardware.org/?probe=b89b8c9364) | May 27, 2019 |
| ASRock        | H61M-DGS                    | [6dc8ccd0f6](https://linux-hardware.org/?probe=6dc8ccd0f6) | May 08, 2019 |
| Foxconn       | P35A01                      | [f2685edfa8](https://linux-hardware.org/?probe=f2685edfa8) | Apr 21, 2019 |
| ASUSTek       | Z170-A                      | [322d76fe62](https://linux-hardware.org/?probe=322d76fe62) | Apr 04, 2019 |
| ASUSTek       | Z170-A                      | [0fa2f9b10a](https://linux-hardware.org/?probe=0fa2f9b10a) | Apr 04, 2019 |
| ASUSTek       | PRIME B450M-A               | [45f363040f](https://linux-hardware.org/?probe=45f363040f) | Mar 30, 2019 |
| ASRock        | P55 Pro                     | [041e899a1b](https://linux-hardware.org/?probe=041e899a1b) | Jan 15, 2019 |
| Gigabyte      | H55M-S2V                    | [36d1703d67](https://linux-hardware.org/?probe=36d1703d67) | Dec 23, 2018 |
| LattePanda    | Alpha                       | [287f0d8110](https://linux-hardware.org/?probe=287f0d8110) | Nov 27, 2018 |
| LattePanda    | Alpha                       | [37c9db1d31](https://linux-hardware.org/?probe=37c9db1d31) | Nov 27, 2018 |
| Gigabyte      | P55-US3L                    | [e216d60f26](https://linux-hardware.org/?probe=e216d60f26) | Sep 19, 2018 |
| Gigabyte      | B75M-D3H                    | [08f9437e06](https://linux-hardware.org/?probe=08f9437e06) | Jul 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | [16f456428f](https://linux-hardware.org/?probe=16f456428f) | May 10, 2018 |
| ECS           | A55F2-M3                    | [e4af897158](https://linux-hardware.org/?probe=e4af897158) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | [f3036847e4](https://linux-hardware.org/?probe=f3036847e4) | May 10, 2018 |
| ECS           | A55F2-M3                    | [eb58cea516](https://linux-hardware.org/?probe=eb58cea516) | May 10, 2018 |
| ASRock        | G41M-VS3                    | [18d59d7ea8](https://linux-hardware.org/?probe=18d59d7ea8) | Apr 13, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 39       | 20.86%  |
| Ubuntu 18.04                 | 21       | 11.23%  |
| Ubuntu 22.04                 | 17       | 9.09%   |
| Ubuntu 20.10                 | 4        | 2.14%   |
| Arch                         | 4        | 2.14%   |
| Ubuntu 19.10                 | 3        | 1.6%    |
| Ubuntu 16.04                 | 3        | 1.6%    |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.6%    |
| Fedora 37                    | 3        | 1.6%    |
| Fedora 32                    | 3        | 1.6%    |
| CentOS 7                     | 3        | 1.6%    |
| ArcoLinux Rolling            | 3        | 1.6%    |
| Zorin 15                     | 2        | 1.07%   |
| Ubuntu Unity 16.04           | 2        | 1.07%   |
| Ubuntu 23.04                 | 2        | 1.07%   |
| Ubuntu 21.10                 | 2        | 1.07%   |
| TmaxOS 21.12.02              | 2        | 1.07%   |
| RHEL 8                       | 2        | 1.07%   |
| Pop!_OS 22.04                | 2        | 1.07%   |
| OpenMandriva 4.3             | 2        | 1.07%   |
| OpenMandriva 23.03           | 2        | 1.07%   |
| OpenMandriva 23.01           | 2        | 1.07%   |
| No1 2018                     | 2        | 1.07%   |
| Linux Mint 21.1              | 2        | 1.07%   |
| Linux Mint 20.2              | 2        | 1.07%   |
| Linux Mint 20.1              | 2        | 1.07%   |
| Linux Mint 20                | 2        | 1.07%   |
| Linux Mint 19.3              | 2        | 1.07%   |
| Fedora 36                    | 2        | 1.07%   |
| Fedora 34                    | 2        | 1.07%   |
| Debian 11                    | 2        | 1.07%   |
| Debian 10                    | 2        | 1.07%   |
| Chrome OS                    | 2        | 1.07%   |
| Arch Rolling                 | 2        | 1.07%   |
| Zorin 16                     | 1        | 0.53%   |
| Ubuntu 19.04                 | 1        | 0.53%   |
| Ubuntu 18.10                 | 1        | 0.53%   |
| Ubuntu 17.10                 | 1        | 0.53%   |
| Ubuntu                       | 1        | 0.53%   |
| ROSA R10                     | 1        | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 94       | 51.37%  |
| Fedora       | 12       | 6.56%   |
| Linux Mint   | 10       | 5.46%   |
| OpenMandriva | 8        | 4.37%   |
| Debian       | 6        | 3.28%   |
| Arch         | 6        | 3.28%   |
| CentOS       | 4        | 2.19%   |
| Zorin        | 3        | 1.64%   |
| Pop!_OS      | 3        | 1.64%   |
| openSUSE     | 3        | 1.64%   |
| No1 Linux    | 3        | 1.64%   |
| Kubuntu      | 3        | 1.64%   |
| HamoniKR     | 3        | 1.64%   |
| ArcoLinux    | 3        | 1.64%   |
| Ubuntu Unity | 2        | 1.09%   |
| TmaxOS       | 2        | 1.09%   |
| Rocky Linux  | 2        | 1.09%   |
| RHEL         | 2        | 1.09%   |
| Chrome OS    | 2        | 1.09%   |
| ROSA         | 1        | 0.55%   |
| Nobara       | 1        | 0.55%   |
| Manjaro      | 1        | 0.55%   |
| Lubuntu      | 1        | 0.55%   |
| KDE neon     | 1        | 0.55%   |
| Kali         | 1        | 0.55%   |
| Gooroom      | 1        | 0.55%   |
| Endless      | 1        | 0.55%   |
| EndeavourOS  | 1        | 0.55%   |
| Devuan       | 1        | 0.55%   |
| BlackPanther | 1        | 0.55%   |
| Alpine       | 1        | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 5.4.0-29-generic           | 4        | 2.01%   |
| 5.15.0-43-generic          | 4        | 2.01%   |
| 5.4.0-26-generic           | 3        | 1.51%   |
| 5.15.0-71-generic          | 3        | 1.51%   |
| 5.15.0-41-generic          | 3        | 1.51%   |
| 6.2.6-desktop-1omv2390     | 2        | 1.01%   |
| 6.1.1-desktop-1omv2290     | 2        | 1.01%   |
| 5.8.0-48-generic           | 2        | 1.01%   |
| 5.8.0-38-generic           | 2        | 1.01%   |
| 5.4.0-56-generic           | 2        | 1.01%   |
| 5.4.0-54-generic           | 2        | 1.01%   |
| 5.4.0-52-generic           | 2        | 1.01%   |
| 5.4.0-47-generic           | 2        | 1.01%   |
| 5.4.0-42-generic           | 2        | 1.01%   |
| 5.4.0-37-generic           | 2        | 1.01%   |
| 5.3.0-51-generic           | 2        | 1.01%   |
| 5.3.0-40-generic           | 2        | 1.01%   |
| 5.19.0-46-generic          | 2        | 1.01%   |
| 5.16.7-desktop-1omv4003    | 2        | 1.01%   |
| 5.15.0-58-generic          | 2        | 1.01%   |
| 5.15.0-53-generic          | 2        | 1.01%   |
| 5.15.0-52-generic          | 2        | 1.01%   |
| 5.15.0-50-generic          | 2        | 1.01%   |
| 5.14.0-0.bpo.2-amd64       | 2        | 1.01%   |
| 5.13.0-21-generic          | 2        | 1.01%   |
| 4.19.0-14-amd64            | 2        | 1.01%   |
| 4.18.0-25-generic          | 2        | 1.01%   |
| 4.15.0-91-generic          | 2        | 1.01%   |
| 6.2.8-200.fc37.x86_64      | 1        | 0.5%    |
| 6.2.2-arch2-1              | 1        | 0.5%    |
| 6.2.0-31-generic           | 1        | 0.5%    |
| 6.2.0-27-generic           | 1        | 0.5%    |
| 6.2.0-24-generic           | 1        | 0.5%    |
| 6.2.0-20-generic           | 1        | 0.5%    |
| 6.1.8-060108-generic       | 1        | 0.5%    |
| 6.1.6-1-default            | 1        | 0.5%    |
| 6.1.38-x64v1-xanmod1-1-lts | 1        | 0.5%    |
| 6.1.33-1-lts               | 1        | 0.5%    |
| 6.1.11-no1linux1           | 1        | 0.5%    |
| 6.1.10-200.fc37.x86_64     | 1        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 36       | 18.75%  |
| 5.15.0  | 23       | 11.98%  |
| 4.15.0  | 18       | 9.38%   |
| 5.8.0   | 13       | 6.77%   |
| 4.18.0  | 10       | 5.21%   |
| 5.3.0   | 9        | 4.69%   |
| 5.13.0  | 5        | 2.6%    |
| 5.19.0  | 4        | 2.08%   |
| 5.14.0  | 4        | 2.08%   |
| 6.2.0   | 3        | 1.56%   |
| 5.0.0   | 3        | 1.56%   |
| 4.19.0  | 3        | 1.56%   |
| 6.2.6   | 2        | 1.04%   |
| 6.1.1   | 2        | 1.04%   |
| 6.1.0   | 2        | 1.04%   |
| 5.16.7  | 2        | 1.04%   |
| 5.11.0  | 2        | 1.04%   |
| 5.10.0  | 2        | 1.04%   |
| 4.13.0  | 2        | 1.04%   |
| 3.10.0  | 2        | 1.04%   |
| 6.2.8   | 1        | 0.52%   |
| 6.2.2   | 1        | 0.52%   |
| 6.1.8   | 1        | 0.52%   |
| 6.1.6   | 1        | 0.52%   |
| 6.1.38  | 1        | 0.52%   |
| 6.1.33  | 1        | 0.52%   |
| 6.1.11  | 1        | 0.52%   |
| 6.1.10  | 1        | 0.52%   |
| 6.0.9   | 1        | 0.52%   |
| 6.0.15  | 1        | 0.52%   |
| 6.0.12  | 1        | 0.52%   |
| 6.0.1   | 1        | 0.52%   |
| 6.0.0   | 1        | 0.52%   |
| 5.9.0   | 1        | 0.52%   |
| 5.8.5   | 1        | 0.52%   |
| 5.8.16  | 1        | 0.52%   |
| 5.8.10  | 1        | 0.52%   |
| 5.7.16  | 1        | 0.52%   |
| 5.6.6   | 1        | 0.52%   |
| 5.6.12  | 1        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 38       | 19.9%   |
| 5.15    | 25       | 13.09%  |
| 4.15    | 19       | 9.95%   |
| 5.8     | 16       | 8.38%   |
| 4.18    | 11       | 5.76%   |
| 6.1     | 10       | 5.24%   |
| 5.3     | 9        | 4.71%   |
| 6.2     | 7        | 3.66%   |
| 5.14    | 6        | 3.14%   |
| 6.0     | 5        | 2.62%   |
| 5.19    | 5        | 2.62%   |
| 5.13    | 5        | 2.62%   |
| 5.10    | 5        | 2.62%   |
| 5.16    | 4        | 2.09%   |
| 5.11    | 4        | 2.09%   |
| 5.0     | 4        | 2.09%   |
| 4.19    | 4        | 2.09%   |
| 5.6     | 2        | 1.05%   |
| 5.18    | 2        | 1.05%   |
| 4.9     | 2        | 1.05%   |
| 4.13    | 2        | 1.05%   |
| 3.10    | 2        | 1.05%   |
| 5.9     | 1        | 0.52%   |
| 5.7     | 1        | 0.52%   |
| 5.12    | 1        | 0.52%   |
| 4.17    | 1        | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 179      | 99.44%  |
| i686   | 1        | 0.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 90       | 49.18%  |
| Unknown         | 38       | 20.77%  |
| KDE5            | 25       | 13.66%  |
| X-Cinnamon      | 9        | 4.92%   |
| XFCE            | 7        | 3.83%   |
| Unity           | 2        | 1.09%   |
| TOS:GNOME       | 2        | 1.09%   |
| KDE             | 2        | 1.09%   |
| Cinnamon        | 2        | 1.09%   |
| MATE            | 1        | 0.55%   |
| LXDE            | 1        | 0.55%   |
| KDE4            | 1        | 0.55%   |
| GNOME Flashback | 1        | 0.55%   |
| GNOME Classic   | 1        | 0.55%   |
| Deepin          | 1        | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 124      | 67.76%  |
| Wayland | 25       | 13.66%  |
| Unknown | 24       | 13.11%  |
| Tty     | 10       | 5.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 104      | 57.46%  |
| GDM3    | 22       | 12.15%  |
| GDM     | 21       | 11.6%   |
| SDDM    | 20       | 11.05%  |
| LightDM | 10       | 5.52%   |
| TDM     | 3        | 1.66%   |
| SLiM    | 1        | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ko_KR   | 73       | 40.33%  |
| en_US   | 69       | 38.12%  |
| Unknown | 29       | 16.02%  |
| C       | 4        | 2.21%   |
| ru_RU   | 1        | 0.55%   |
| id_ID   | 1        | 0.55%   |
| fr_FR   | 1        | 0.55%   |
| en_GB   | 1        | 0.55%   |
| en_CA   | 1        | 0.55%   |
| en_AU   | 1        | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 94       | 51.37%  |
| BIOS | 89       | 48.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 144      | 78.69%  |
| Btrfs   | 11       | 6.01%   |
| Unknown | 9        | 4.92%   |
| Xfs     | 7        | 3.83%   |
| Overlay | 6        | 3.28%   |
| Zfs     | 3        | 1.64%   |
| Tmpfs   | 2        | 1.09%   |
| Rootfs  | 1        | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 99       | 54.4%   |
| GPT     | 69       | 37.91%  |
| MBR     | 14       | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 148      | 81.32%  |
| Yes       | 34       | 18.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 125      | 69.06%  |
| Yes       | 56       | 30.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 43       | 23.89%  |
| Gigabyte Technology | 39       | 21.67%  |
| ASRock              | 33       | 18.33%  |
| MSI                 | 17       | 9.44%   |
| ECS                 | 7        | 3.89%   |
| Samsung Electronics | 6        | 3.33%   |
| Lenovo              | 6        | 3.33%   |
| Hewlett-Packard     | 5        | 2.78%   |
| Dell                | 4        | 2.22%   |
| Foxconn             | 3        | 1.67%   |
| Unknown             | 3        | 1.67%   |
| LattePanda          | 2        | 1.11%   |
| Huanan              | 2        | 1.11%   |
| WTM                 | 1        | 0.56%   |
| PCPartner           | 1        | 0.56%   |
| PC Partner Limited  | 1        | 0.56%   |
| Fujitsu             | 1        | 0.56%   |
| ELSKY               | 1        | 0.56%   |
| ECS2                | 1        | 0.56%   |
| Biostar             | 1        | 0.56%   |
| ASRockRack          | 1        | 0.56%   |
| AMD                 | 1        | 0.56%   |
| Alienware           | 1        | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung DeskTop System                 | 4        | 2.22%   |
| Gigabyte B75M-D3H                      | 3        | 1.67%   |
| ASUS PRIME B350M-A                     | 3        | 1.67%   |
| ASUS All Series                        | 3        | 1.67%   |
| Unknown                                | 3        | 1.67%   |
| MSI MS-7D91                            | 2        | 1.11%   |
| MSI MS-7D42                            | 2        | 1.11%   |
| MSI MS-7B89                            | 2        | 1.11%   |
| LattePanda Alpha                       | 2        | 1.11%   |
| Gigabyte TRX40 AORUS XTREME            | 2        | 1.11%   |
| Gigabyte H81M-DS2V                     | 2        | 1.11%   |
| Gigabyte B75M-D3V                      | 2        | 1.11%   |
| Gigabyte B360M-D3H                     | 2        | 1.11%   |
| ASUS Z170-A                            | 2        | 1.11%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4   | 2        | 1.11%   |
| ASUS PRIME A320M-K                     | 2        | 1.11%   |
| ASUS EX-A320M-GAMING                   | 2        | 1.11%   |
| ASRock H81M-DGS R2.0                   | 2        | 1.11%   |
| ASRock AB350M Pro4                     | 2        | 1.11%   |
| WTM W-N95                              | 1        | 0.56%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.56%   |
| Samsung 400T7A/400S7A                  | 1        | 0.56%   |
| PCPartner DREAMSYS                     | 1        | 0.56%   |
| PC Partner Limited S70BS.AH3511        | 1        | 0.56%   |
| MSI MS-7C94                            | 1        | 0.56%   |
| MSI MS-7C75                            | 1        | 0.56%   |
| MSI MS-7C51                            | 1        | 0.56%   |
| MSI MS-7C02                            | 1        | 0.56%   |
| MSI MS-7B85                            | 1        | 0.56%   |
| MSI MS-7B24                            | 1        | 0.56%   |
| MSI MS-7A74                            | 1        | 0.56%   |
| MSI MS-7A37                            | 1        | 0.56%   |
| MSI MS-7A20                            | 1        | 0.56%   |
| MSI MS-7A15                            | 1        | 0.56%   |
| MSI MS-7808                            | 1        | 0.56%   |
| Lenovo ThinkStation P900 30A4A03600    | 1        | 0.56%   |
| Lenovo ThinkStation P520c 30BXCTO1WW   | 1        | 0.56%   |
| Lenovo ThinkStation P500 30A6A3KSKR    | 1        | 0.56%   |
| Lenovo ThinkCentre M72e 4004H1U        | 1        | 0.56%   |
| Lenovo IdeaCentre 5 14IMB05 90NA0028KR | 1        | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME                      | 14       | 7.78%   |
| ASUS ROG                        | 6        | 3.33%   |
| Samsung DeskTop                 | 4        | 2.22%   |
| Lenovo ThinkStation             | 3        | 1.67%   |
| Gigabyte TRX40                  | 3        | 1.67%   |
| Gigabyte B75M-D3H               | 3        | 1.67%   |
| ASUS All                        | 3        | 1.67%   |
| Unknown                         | 3        | 1.67%   |
| MSI MS-7D91                     | 2        | 1.11%   |
| MSI MS-7D42                     | 2        | 1.11%   |
| MSI MS-7B89                     | 2        | 1.11%   |
| LattePanda Alpha                | 2        | 1.11%   |
| Gigabyte Z390                   | 2        | 1.11%   |
| Gigabyte X570                   | 2        | 1.11%   |
| Gigabyte H81M-DS2V              | 2        | 1.11%   |
| Gigabyte B75M-D3V               | 2        | 1.11%   |
| Gigabyte B360M-D3H              | 2        | 1.11%   |
| Dell Vostro                     | 2        | 1.11%   |
| Dell OptiPlex                   | 2        | 1.11%   |
| ASUS Z170-A                     | 2        | 1.11%   |
| ASUS TUF                        | 2        | 1.11%   |
| ASUS EX-A320M-GAMING            | 2        | 1.11%   |
| ASRock Z390                     | 2        | 1.11%   |
| ASRock Z370                     | 2        | 1.11%   |
| ASRock H81M-DGS                 | 2        | 1.11%   |
| ASRock FM2A88M-HD+              | 2        | 1.11%   |
| ASRock AB350M                   | 2        | 1.11%   |
| WTM W-N95                       | 1        | 0.56%   |
| Samsung 500T8A                  | 1        | 0.56%   |
| Samsung 400T7A                  | 1        | 0.56%   |
| PCPartner DREAMSYS              | 1        | 0.56%   |
| PC Partner Limited S70BS.AH3511 | 1        | 0.56%   |
| MSI MS-7C94                     | 1        | 0.56%   |
| MSI MS-7C75                     | 1        | 0.56%   |
| MSI MS-7C51                     | 1        | 0.56%   |
| MSI MS-7C02                     | 1        | 0.56%   |
| MSI MS-7B85                     | 1        | 0.56%   |
| MSI MS-7B24                     | 1        | 0.56%   |
| MSI MS-7A74                     | 1        | 0.56%   |
| MSI MS-7A37                     | 1        | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 22       | 12.22%  |
| 2012 | 20       | 11.11%  |
| 2017 | 18       | 10%     |
| 2020 | 15       | 8.33%   |
| 2019 | 14       | 7.78%   |
| 2021 | 12       | 6.67%   |
| 2013 | 11       | 6.11%   |
| 2022 | 10       | 5.56%   |
| 2015 | 10       | 5.56%   |
| 2014 | 9        | 5%      |
| 2016 | 8        | 4.44%   |
| 2009 | 7        | 3.89%   |
| 2010 | 6        | 3.33%   |
| 2008 | 5        | 2.78%   |
| 2007 | 5        | 2.78%   |
| 2011 | 3        | 1.67%   |
| 2023 | 2        | 1.11%   |
| 2006 | 2        | 1.11%   |
| 2005 | 1        | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 180      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 176      | 97.24%  |
| Enabled  | 5        | 2.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 180      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 36       | 19.78%  |
| 16.01-24.0      | 30       | 16.48%  |
| 64.01-256.0     | 29       | 15.93%  |
| 32.01-64.0      | 26       | 14.29%  |
| 4.01-8.0        | 24       | 13.19%  |
| 3.01-4.0        | 21       | 11.54%  |
| 24.01-32.0      | 7        | 3.85%   |
| 1.01-2.0        | 4        | 2.2%    |
| More than 256.0 | 3        | 1.65%   |
| 2.01-3.0        | 2        | 1.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 59       | 30.26%  |
| 2.01-3.0   | 40       | 20.51%  |
| 3.01-4.0   | 34       | 17.44%  |
| 4.01-8.0   | 31       | 15.9%   |
| 8.01-16.0  | 11       | 5.64%   |
| 0.51-1.0   | 11       | 5.64%   |
| 32.01-64.0 | 3        | 1.54%   |
| 16.01-24.0 | 3        | 1.54%   |
| 0.01-0.5   | 2        | 1.03%   |
| 24.01-32.0 | 1        | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 64       | 34.97%  |
| 2      | 58       | 31.69%  |
| 3      | 26       | 14.21%  |
| 4      | 15       | 8.2%    |
| 5      | 8        | 4.37%   |
| 6      | 6        | 3.28%   |
| 7      | 2        | 1.09%   |
| 10     | 1        | 0.55%   |
| 9      | 1        | 0.55%   |
| 8      | 1        | 0.55%   |
| 0      | 1        | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 69.61%  |
| Yes       | 55       | 30.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 179      | 99.44%  |
| No        | 1        | 0.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 114      | 62.98%  |
| Yes       | 67       | 37.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 59.78%  |
| Yes       | 74       | 40.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| South Korea | 180      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Seoul           | 14       | 7.29%   |
| Seongnam-si     | 13       | 6.77%   |
| Yongin-si       | 8        | 4.17%   |
| Suwon           | 8        | 4.17%   |
| Busan           | 6        | 3.13%   |
| Cheonan         | 5        | 2.6%    |
| Incheon         | 4        | 2.08%   |
| Hwaseong-si     | 4        | 2.08%   |
| Gwanak-gu       | 4        | 2.08%   |
| Gangseo-gu      | 4        | 2.08%   |
| Dongjak-gu      | 4        | 2.08%   |
| Bucheon-si      | 4        | 2.08%   |
| Yangcheon-gu    | 3        | 1.56%   |
| Seo-gu          | 3        | 1.56%   |
| Pyeongtaek-si   | 3        | 1.56%   |
| Nam-gu          | 3        | 1.56%   |
| Gyeonggi-do     | 3        | 1.56%   |
| Guri-si         | 3        | 1.56%   |
| Goyang-si       | 3        | 1.56%   |
| Gangnam-gu      | 3        | 1.56%   |
| Daejeon         | 3        | 1.56%   |
| Anyang-si       | 3        | 1.56%   |
| Ansan-si        | 3        | 1.56%   |
| Yongsan-gu      | 2        | 1.04%   |
| Yeongdeungpo-gu | 2        | 1.04%   |
| Uiwang          | 2        | 1.04%   |
| Uiseong-gun     | 2        | 1.04%   |
| Siheung-si      | 2        | 1.04%   |
| Seongdong-gu    | 2        | 1.04%   |
| Seongbuk-gu     | 2        | 1.04%   |
| Sejong          | 2        | 1.04%   |
| Osan            | 2        | 1.04%   |
| Jungnang-gu     | 2        | 1.04%   |
| Icheon-si       | 2        | 1.04%   |
| Gwangmyeong-si  | 2        | 1.04%   |
| Guro-gu         | 2        | 1.04%   |
| Geumcheon-gu    | 2        | 1.04%   |
| Gangdong-gu     | 2        | 1.04%   |
| Gangbuk-gu      | 2        | 1.04%   |
| Yuseong-gu      | 1        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 63       | 109    | 18.69%  |
| Samsung Electronics       | 58       | 83     | 17.21%  |
| Seagate                   | 51       | 82     | 15.13%  |
| Toshiba                   | 22       | 40     | 6.53%   |
| Sandisk                   | 21       | 26     | 6.23%   |
| Crucial                   | 21       | 26     | 6.23%   |
| Hitachi                   | 12       | 13     | 3.56%   |
| Unknown                   | 10       | 11     | 2.97%   |
| SK hynix                  | 9        | 12     | 2.67%   |
| HGST                      | 7        | 8      | 2.08%   |
| Transcend                 | 6        | 6      | 1.78%   |
| A-DATA Technology         | 6        | 6      | 1.78%   |
| Micron Technology         | 5        | 6      | 1.48%   |
| Plextor                   | 4        | 6      | 1.19%   |
| SPCC                      | 3        | 3      | 0.89%   |
| Silicon Motion            | 3        | 4      | 0.89%   |
| Intel                     | 3        | 3      | 0.89%   |
| TAMMUZ                    | 2        | 3      | 0.59%   |
| Seagate Technology        | 2        | 3      | 0.59%   |
| RevuAhn                   | 2        | 2      | 0.59%   |
| Micron/Crucial Technology | 2        | 2      | 0.59%   |
| LITEON                    | 2        | 2      | 0.59%   |
| China                     | 2        | 2      | 0.59%   |
| ZOTAC                     | 1        | 1      | 0.3%    |
| Team                      | 1        | 1      | 0.3%    |
| Realtek Semiconductor     | 1        | 1      | 0.3%    |
| QNIX                      | 1        | 1      | 0.3%    |
| Phison                    | 1        | 2      | 0.3%    |
| PHINOCOM                  | 1        | 1      | 0.3%    |
| OSCOO                     | 1        | 1      | 0.3%    |
| OCZ                       | 1        | 2      | 0.3%    |
| Netac                     | 1        | 1      | 0.3%    |
| MARVELL                   | 1        | 1      | 0.3%    |
| LaCie                     | 1        | 1      | 0.3%    |
| KIOXIA                    | 1        | 3      | 0.3%    |
| KingSpec                  | 1        | 1      | 0.3%    |
| JMicron Technology        | 1        | 1      | 0.3%    |
| Imation                   | 1        | 2      | 0.3%    |
| Hewlett-Packard           | 1        | 1      | 0.3%    |
| GLOWAY                    | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Toshiba DT01ACA300 3TB                 | 8        | 2.03%   |
| Seagate ST500DM002-1BD142 500GB        | 6        | 1.52%   |
| Crucial CT500MX500SSD1 500GB           | 6        | 1.52%   |
| Crucial CT240BX500SSD1 240GB           | 6        | 1.52%   |
| Toshiba DT01ACA200 2TB                 | 4        | 1.02%   |
| Seagate ST1000DM010-2EP102 1TB         | 4        | 1.02%   |
| SanDisk SD8SBAT128G1122 128GB SSD      | 4        | 1.02%   |
| Samsung SSD 850 EVO 120GB              | 4        | 1.02%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3        | 0.76%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 3        | 0.76%   |
| WDC WD40EZAZ-00SF3B0 4TB               | 3        | 0.76%   |
| WDC WD40EFRX-68WT0N0 4TB               | 3        | 0.76%   |
| WDC WD3200AAJS-00L7A0 320GB            | 3        | 0.76%   |
| WDC WD20EARX-00PASB0 2TB               | 3        | 0.76%   |
| WDC WD10EZEX-22MFCA0 1TB               | 3        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB               | 3        | 0.76%   |
| Unknown SD/MMC/MS PRO 1GB              | 3        | 0.76%   |
| Toshiba DT01ACA050 500GB               | 3        | 0.76%   |
| Seagate ST3500418AS 500GB              | 3        | 0.76%   |
| Seagate ST2000DM008-2FR102 2TB         | 3        | 0.76%   |
| Seagate ST1000DM003-1CH162 1TB         | 3        | 0.76%   |
| Samsung SSD 850 PRO 256GB              | 3        | 0.76%   |
| Samsung SSD 850 EVO 250GB              | 3        | 0.76%   |
| Crucial CT275MX300SSD4 275GB           | 3        | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2        | 0.51%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2        | 0.51%   |
| WDC WD10EZEX-00WN4A0 1TB               | 2        | 0.51%   |
| Unknown NVMe SSD Drive 512GB           | 2        | 0.51%   |
| Transcend TS240GSSD220S 240GB          | 2        | 0.51%   |
| Toshiba HDWD120 2TB                    | 2        | 0.51%   |
| TAMMUZ SSD 128GB                       | 2        | 0.51%   |
| SK hynix SHGP31-500GM 500GB            | 2        | 0.51%   |
| SK hynix SHGP31-2000GM 2TB             | 2        | 0.51%   |
| Seagate FireCuda 510 SSD 1TB           | 2        | 0.51%   |
| Seagate ST8000DM004-2CX188 8TB         | 2        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 0.51%   |
| SanDisk SD7SB6S128G1122 128GB SSD      | 2        | 0.51%   |
| Samsung SSD 860 EVO 250GB              | 2        | 0.51%   |
| Samsung SSD 850 EVO 500GB              | 2        | 0.51%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 55       | 93     | 34.81%  |
| Seagate             | 49       | 77     | 31.01%  |
| Toshiba             | 19       | 30     | 12.03%  |
| Hitachi             | 12       | 13     | 7.59%   |
| Samsung Electronics | 9        | 10     | 5.7%    |
| HGST                | 7        | 8      | 4.43%   |
| Unknown             | 3        | 4      | 1.9%    |
| MARVELL             | 1        | 1      | 0.63%   |
| LaCie               | 1        | 1      | 0.63%   |
| Hewlett-Packard     | 1        | 1      | 0.63%   |
| Fujitsu             | 1        | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 29       | 36     | 23.39%  |
| Crucial             | 21       | 26     | 16.94%  |
| SanDisk             | 18       | 21     | 14.52%  |
| WDC                 | 10       | 14     | 8.06%   |
| Transcend           | 6        | 6      | 4.84%   |
| A-DATA Technology   | 5        | 5      | 4.03%   |
| Toshiba             | 3        | 10     | 2.42%   |
| SPCC                | 3        | 3      | 2.42%   |
| Seagate             | 3        | 4      | 2.42%   |
| Plextor             | 3        | 5      | 2.42%   |
| TAMMUZ              | 2        | 3      | 1.61%   |
| SK hynix            | 2        | 4      | 1.61%   |
| RevuAhn             | 2        | 2      | 1.61%   |
| LITEON              | 2        | 2      | 1.61%   |
| Intel               | 2        | 2      | 1.61%   |
| China               | 2        | 2      | 1.61%   |
| QNIX                | 1        | 1      | 0.81%   |
| PHINOCOM            | 1        | 1      | 0.81%   |
| OSCOO               | 1        | 1      | 0.81%   |
| OCZ                 | 1        | 2      | 0.81%   |
| Netac               | 1        | 1      | 0.81%   |
| Micron Technology   | 1        | 1      | 0.81%   |
| KingSpec            | 1        | 1      | 0.81%   |
| JMicron Technology  | 1        | 1      | 0.81%   |
| Imation             | 1        | 2      | 0.81%   |
| GLOWAY              | 1        | 1      | 0.81%   |
| Unknown             | 1        | 1      | 0.81%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 120      | 239    | 41.81%  |
| SSD     | 106      | 158    | 36.93%  |
| NVMe    | 55       | 81     | 19.16%  |
| MMC     | 3        | 3      | 1.05%   |
| Unknown | 3        | 3      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 158      | 389    | 69.91%  |
| NVMe | 55       | 81     | 24.34%  |
| SAS  | 10       | 11     | 4.42%   |
| MMC  | 3        | 3      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 120      | 195    | 48.78%  |
| 0.51-1.0   | 50       | 75     | 20.33%  |
| 1.01-2.0   | 31       | 42     | 12.6%   |
| 3.01-4.0   | 21       | 40     | 8.54%   |
| 2.01-3.0   | 11       | 16     | 4.47%   |
| 4.01-10.0  | 10       | 20     | 4.07%   |
| 10.01-20.0 | 3        | 9      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 42       | 22.95%  |
| 251-500        | 34       | 18.58%  |
| 501-1000       | 28       | 15.3%   |
| More than 3000 | 21       | 11.48%  |
| 1001-2000      | 17       | 9.29%   |
| 2001-3000      | 15       | 8.2%    |
| 21-50          | 9        | 4.92%   |
| 51-100         | 7        | 3.83%   |
| 1-20           | 6        | 3.28%   |
| Unknown        | 4        | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 69       | 36.51%  |
| 21-50          | 25       | 13.23%  |
| 101-250        | 24       | 12.7%   |
| 51-100         | 19       | 10.05%  |
| 251-500        | 17       | 8.99%   |
| 501-1000       | 12       | 6.35%   |
| More than 3000 | 8        | 4.23%   |
| 2001-3000      | 7        | 3.7%    |
| 1001-2000      | 4        | 2.12%   |
| Unknown        | 4        | 2.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| WDC WD7500AACS-00D6B0 752GB                                     | 1        | 1      | 6.25%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 1        | 1      | 6.25%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1        | 1      | 6.25%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1        | 2      | 6.25%   |
| WDC WD1600BEVT-22A23T0 160GB                                    | 1        | 1      | 6.25%   |
| WDC WD1001FALS-00J7B1 1TB                                       | 1        | 1      | 6.25%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1        | 1      | 6.25%   |
| Seagate ST4000DM000-1F2168 4TB                                  | 1        | 1      | 6.25%   |
| Seagate ST3500418AS 500GB                                       | 1        | 1      | 6.25%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 1        | 1      | 6.25%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 1        | 1      | 6.25%   |
| Samsung Electronics HD160JJ 160GB                               | 1        | 1      | 6.25%   |
| LITEON LMH-128V2M 128GB SSD                                     | 1        | 1      | 6.25%   |
| Hitachi HTS543216L9A300 160GB                                   | 1        | 1      | 6.25%   |
| HGST HDN726060ALE610 6TB                                        | 1        | 1      | 6.25%   |
| A-DATA Technology SU650 240GB SSD                               | 1        | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 37.5%   |
| Seagate             | 4        | 4      | 25%     |
| Samsung Electronics | 2        | 2      | 12.5%   |
| LITEON              | 1        | 1      | 6.25%   |
| Hitachi             | 1        | 1      | 6.25%   |
| HGST                | 1        | 1      | 6.25%   |
| A-DATA Technology   | 1        | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 46.15%  |
| Seagate             | 4        | 4      | 30.77%  |
| Samsung Electronics | 1        | 1      | 7.69%   |
| Hitachi             | 1        | 1      | 7.69%   |
| HGST                | 1        | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 11       | 14     | 78.57%  |
| SSD  | 2        | 2      | 14.29%  |
| NVMe | 1        | 1      | 7.14%   |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 110      | 292    | 56.12%  |
| Works    | 72       | 175    | 36.73%  |
| Malfunc  | 14       | 17     | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 121      | 43.84%  |
| AMD                        | 54       | 19.57%  |
| Samsung Electronics        | 29       | 10.51%  |
| ASMedia Technology         | 19       | 6.88%   |
| JMicron Technology         | 11       | 3.99%   |
| SK hynix                   | 7        | 2.54%   |
| Silicon Motion             | 4        | 1.45%   |
| SanDisk                    | 4        | 1.45%   |
| Phison Electronics         | 4        | 1.45%   |
| Micron Technology          | 4        | 1.45%   |
| Marvell Technology Group   | 4        | 1.45%   |
| Seagate Technology         | 3        | 1.09%   |
| Micron/Crucial Technology  | 2        | 0.72%   |
| Broadcom / LSI             | 2        | 0.72%   |
| VIA Technologies           | 1        | 0.36%   |
| Realtek Semiconductor      | 1        | 0.36%   |
| Lite-On Technology         | 1        | 0.36%   |
| Lite-On IT Corp. / Plextor | 1        | 0.36%   |
| KIOXIA                     | 1        | 0.36%   |
| INNOGRIT                   | 1        | 0.36%   |
| Biwin Storage Technology   | 1        | 0.36%   |
| ADATA Technology           | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 39       | 11.3%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 18       | 5.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 4.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13       | 3.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12       | 3.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12       | 3.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.61%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 2.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.32%   |
| AMD FCH SATA Controller D                                                               | 8        | 2.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8        | 2.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 2.03%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 2.03%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.03%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 1.74%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6        | 1.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 5        | 1.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.45%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1.16%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 1.16%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 4        | 1.16%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.16%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.87%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 0.87%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 2        | 0.58%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.58%   |
| Seagate FireCuda/IronWolf 510 SSD                                                       | 2        | 0.58%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.58%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 2        | 0.58%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.58%   |
| JMicron JMB58x AHCI SATA controller                                                     | 2        | 0.58%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.58%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2        | 0.58%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 2        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 152      | 59.84%  |
| NVMe | 57       | 22.44%  |
| IDE  | 35       | 13.78%  |
| RAID | 8        | 3.15%   |
| SAS  | 2        | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 124      | 68.89%  |
| AMD    | 56       | 31.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz               | 8        | 4.44%   |
| Intel Core i5-8500 CPU @ 3.00GHz               | 5        | 2.78%   |
| AMD Ryzen 5 1600 Six-Core Processor            | 5        | 2.78%   |
| Intel Core i3-3220 CPU @ 3.30GHz               | 4        | 2.22%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics    | 4        | 2.22%   |
| Intel Pentium CPU G4400 @ 3.30GHz              | 3        | 1.67%   |
| Intel Core i9-9900K CPU @ 3.60GHz              | 3        | 1.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz               | 3        | 1.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz          | 3        | 1.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor         | 3        | 1.67%   |
| AMD Ryzen 5 5600X 6-Core Processor             | 3        | 1.67%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics    | 3        | 1.67%   |
| Intel Pentium 4 CPU 3.00GHz                    | 2        | 1.11%   |
| Intel Core i9-10900K CPU @ 3.70GHz             | 2        | 1.11%   |
| Intel Core i7-9700K CPU @ 3.60GHz              | 2        | 1.11%   |
| Intel Core i7-8700 CPU @ 3.20GHz               | 2        | 1.11%   |
| Intel Core i7-3770 CPU @ 3.40GHz               | 2        | 1.11%   |
| Intel Core i5-7500 CPU @ 3.40GHz               | 2        | 1.11%   |
| Intel Core i5-7400 CPU @ 3.00GHz               | 2        | 1.11%   |
| Intel Core i5-6600K CPU @ 3.50GHz              | 2        | 1.11%   |
| Intel Core i5-10400 CPU @ 2.90GHz              | 2        | 1.11%   |
| Intel Core i5 CPU 760 @ 2.80GHz                | 2        | 1.11%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz          | 2        | 1.11%   |
| Intel 13th Gen Core i9-13900K                  | 2        | 1.11%   |
| AMD Ryzen Threadripper 3970X 32-Core Processor | 2        | 1.11%   |
| AMD Ryzen 7 5800X 8-Core Processor             | 2        | 1.11%   |
| AMD Ryzen 5 2600 Six-Core Processor            | 2        | 1.11%   |
| Intel Xeon W-3275M CPU @ 2.50GHz               | 1        | 0.56%   |
| Intel Xeon W-2133 CPU @ 3.60GHz                | 1        | 0.56%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz             | 1        | 0.56%   |
| Intel Xeon CPU X5680 @ 3.33GHz                 | 1        | 0.56%   |
| Intel Xeon CPU X3430 @ 2.40GHz                 | 1        | 0.56%   |
| Intel Xeon CPU E5450 @ 3.00GHz                 | 1        | 0.56%   |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz            | 1        | 0.56%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz            | 1        | 0.56%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz            | 1        | 0.56%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz            | 1        | 0.56%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz            | 1        | 0.56%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz            | 1        | 0.56%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz            | 1        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 35       | 19.44%  |
| AMD Ryzen 5             | 18       | 10%     |
| Intel Core i7           | 17       | 9.44%   |
| Intel Xeon              | 12       | 6.67%   |
| Other                   | 11       | 6.11%   |
| Intel Core i3           | 11       | 6.11%   |
| AMD Ryzen 7             | 9        | 5%      |
| Intel Pentium           | 7        | 3.89%   |
| Intel Core i9           | 7        | 3.89%   |
| AMD Ryzen Threadripper  | 7        | 3.89%   |
| Intel Core 2 Quad       | 6        | 3.33%   |
| Intel Celeron           | 6        | 3.33%   |
| AMD Ryzen 9             | 5        | 2.78%   |
| AMD Ryzen 3             | 5        | 2.78%   |
| Intel Pentium Gold      | 2        | 1.11%   |
| Intel Pentium Dual-Core | 2        | 1.11%   |
| Intel Pentium 4         | 2        | 1.11%   |
| Intel Core m3           | 2        | 1.11%   |
| Intel Core 2 Duo        | 2        | 1.11%   |
| AMD A8                  | 2        | 1.11%   |
| AMD A10                 | 2        | 1.11%   |
| Intel Xeon Gold         | 1        | 0.56%   |
| Intel Core 2            | 1        | 0.56%   |
| AMD Ryzen Embedded      | 1        | 0.56%   |
| AMD Ryzen 7 PRO         | 1        | 0.56%   |
| AMD Ryzen 5 PRO         | 1        | 0.56%   |
| AMD Phenom II X6        | 1        | 0.56%   |
| AMD Phenom              | 1        | 0.56%   |
| AMD FX                  | 1        | 0.56%   |
| AMD Athlon II X2        | 1        | 0.56%   |
| AMD Athlon 64 X2        | 1        | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 62       | 34.44%  |
| 2      | 37       | 20.56%  |
| 6      | 34       | 18.89%  |
| 8      | 17       | 9.44%   |
| 16     | 8        | 4.44%   |
| 32     | 4        | 2.22%   |
| 12     | 4        | 2.22%   |
| 10     | 4        | 2.22%   |
| 24     | 2        | 1.11%   |
| 1      | 2        | 1.11%   |
| 64     | 1        | 0.56%   |
| 28     | 1        | 0.56%   |
| 22     | 1        | 0.56%   |
| 20     | 1        | 0.56%   |
| 18     | 1        | 0.56%   |
| 14     | 1        | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 178      | 98.89%  |
| 2      | 2        | 1.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 103      | 57.22%  |
| 1      | 77       | 42.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 177      | 97.79%  |
| Unknown        | 4        | 2.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 40       | 21.86%  |
| 0x306a9    | 17       | 9.29%   |
| 0x306c3    | 16       | 8.74%   |
| 0x906ea    | 8        | 4.37%   |
| 0x906e9    | 7        | 3.83%   |
| 0x506e3    | 6        | 3.28%   |
| 0x306f2    | 5        | 2.73%   |
| 0x1067a    | 5        | 2.73%   |
| 0x906ed    | 4        | 2.19%   |
| 0x206a7    | 4        | 2.19%   |
| 0x106e5    | 4        | 2.19%   |
| 0x0800820d | 4        | 2.19%   |
| 0x08001138 | 4        | 2.19%   |
| 0x08001137 | 4        | 2.19%   |
| 0xb0671    | 3        | 1.64%   |
| 0xa0655    | 3        | 1.64%   |
| 0x6fb      | 3        | 1.64%   |
| 0x0a20120a | 3        | 1.64%   |
| 0x08101016 | 3        | 1.64%   |
| 0x906ec    | 2        | 1.09%   |
| 0x90672    | 2        | 1.09%   |
| 0x806e9    | 2        | 1.09%   |
| 0x50654    | 2        | 1.09%   |
| 0x08701021 | 2        | 1.09%   |
| 0x08600106 | 2        | 1.09%   |
| 0x08108109 | 2        | 1.09%   |
| 0x0810100b | 2        | 1.09%   |
| 0xf49      | 1        | 0.55%   |
| 0xa0671    | 1        | 0.55%   |
| 0x906eb    | 1        | 0.55%   |
| 0x90675    | 1        | 0.55%   |
| 0x406f1    | 1        | 0.55%   |
| 0x306e4    | 1        | 0.55%   |
| 0x306d4    | 1        | 0.55%   |
| 0x30678    | 1        | 0.55%   |
| 0x0a601203 | 1        | 0.55%   |
| 0x0a601201 | 1        | 0.55%   |
| 0x0a50000d | 1        | 0.55%   |
| 0x0a50000c | 1        | 0.55%   |
| 0x0a201016 | 1        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 26       | 14.44%  |
| Haswell          | 22       | 12.22%  |
| IvyBridge        | 19       | 10.56%  |
| Zen              | 17       | 9.44%   |
| Skylake          | 13       | 7.22%   |
| Unknown          | 11       | 6.11%   |
| Zen 3            | 10       | 5.56%   |
| Zen+             | 8        | 4.44%   |
| Zen 2            | 8        | 4.44%   |
| Penryn           | 8        | 4.44%   |
| CometLake        | 5        | 2.78%   |
| SandyBridge      | 4        | 2.22%   |
| Nehalem          | 4        | 2.22%   |
| Core             | 4        | 2.22%   |
| Alderlake Hybrid | 4        | 2.22%   |
| K10              | 3        | 1.67%   |
| Steamroller      | 2        | 1.11%   |
| Silvermont       | 2        | 1.11%   |
| Piledriver       | 2        | 1.11%   |
| NetBurst         | 2        | 1.11%   |
| Broadwell        | 2        | 1.11%   |
| Westmere         | 1        | 0.56%   |
| K8 Hammer        | 1        | 0.56%   |
| K10 Llano        | 1        | 0.56%   |
| Icelake          | 1        | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 96       | 47.06%  |
| Intel                      | 63       | 30.88%  |
| AMD                        | 42       | 20.59%  |
| ASPEED Technology          | 2        | 0.98%   |
| Matrox Electronics Systems | 1        | 0.49%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 4.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 4.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 3.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 3.37%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 2.88%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.92%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 1.92%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 1.92%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.44%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.44%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 1.44%   |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 1.44%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 3        | 1.44%   |
| Intel HD Graphics 510                                                       | 3        | 1.44%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 3        | 1.44%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.44%   |
| AMD Raphael                                                                 | 3        | 1.44%   |
| Nvidia TU102 [TITAN RTX]                                                    | 2        | 0.96%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.96%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 0.96%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 0.96%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 0.96%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 0.96%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 0.96%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 2        | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 0.96%   |
| Nvidia G98 [GeForce 9300 GS]                                                | 2        | 0.96%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 2        | 0.96%   |
| Intel HD Graphics 530                                                       | 2        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 0.96%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 0.96%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2        | 0.96%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 0.96%   |
| AMD Renoir                                                                  | 2        | 0.96%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 85       | 46.7%   |
| 1 x Intel       | 47       | 25.82%  |
| 1 x AMD         | 35       | 19.23%  |
| AMD + Nvidia    | 5        | 2.75%   |
| Intel + Nvidia  | 3        | 1.65%   |
| 2 x AMD         | 2        | 1.1%    |
| 2 x Nvidia      | 1        | 0.55%   |
| Nvidia + Matrox | 1        | 0.55%   |
| Nvidia + ASPEED | 1        | 0.55%   |
| Intel + AMD     | 1        | 0.55%   |
| 1 x ASPEED      | 1        | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 117      | 64.29%  |
| Proprietary | 59       | 32.42%  |
| Unknown     | 6        | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 78       | 42.62%  |
| 0.51-1.0   | 24       | 13.11%  |
| 1.01-2.0   | 23       | 12.57%  |
| 7.01-8.0   | 13       | 7.1%    |
| 3.01-4.0   | 11       | 6.01%   |
| 0.01-0.5   | 11       | 6.01%   |
| 8.01-16.0  | 8        | 4.37%   |
| 5.01-6.0   | 5        | 2.73%   |
| 16.01-24.0 | 5        | 2.73%   |
| 2.01-3.0   | 4        | 2.19%   |
| 4.01-5.0   | 1        | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 39       | 22.41%  |
| Samsung Electronics  | 32       | 18.39%  |
| Unknown              | 10       | 5.75%   |
| Dell                 | 10       | 5.75%   |
| Philips              | 7        | 4.02%   |
| LG Electronics       | 7        | 4.02%   |
| Hewlett-Packard      | 6        | 3.45%   |
| PRISM+               | 5        | 2.87%   |
| OUT                  | 5        | 2.87%   |
| AOC                  | 5        | 2.87%   |
| BenQ                 | 4        | 2.3%    |
| Unknown (ADE)        | 2        | 1.15%   |
| RTK                  | 2        | 1.15%   |
| OOO                  | 2        | 1.15%   |
| MStar                | 2        | 1.15%   |
| Lenovo               | 2        | 1.15%   |
| JRY                  | 2        | 1.15%   |
| Ancor Communications | 2        | 1.15%   |
| Yamaha               | 1        | 0.57%   |
| Xiangye              | 1        | 0.57%   |
| UPV                  | 1        | 0.57%   |
| TopView              | 1        | 0.57%   |
| TGL                  | 1        | 0.57%   |
| SiS                  | 1        | 0.57%   |
| SGT                  | 1        | 0.57%   |
| SANYO                | 1        | 0.57%   |
| RAT                  | 1        | 0.57%   |
| PBK                  | 1        | 0.57%   |
| ORM                  | 1        | 0.57%   |
| NME                  | 1        | 0.57%   |
| MON                  | 1        | 0.57%   |
| MiTAC                | 1        | 0.57%   |
| Microstep            | 1        | 0.57%   |
| LYC                  | 1        | 0.57%   |
| KVM                  | 1        | 0.57%   |
| JCH                  | 1        | 0.57%   |
| ITE                  | 1        | 0.57%   |
| Hyundai ImageQuest   | 1        | 0.57%   |
| HXM                  | 1        | 0.57%   |
| HVT                  | 1        | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 5        | 2.75%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 4        | 2.2%    |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                          | 3        | 1.65%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1872x1053mm 84.6-inch | 2        | 1.1%    |
| PRISM+ ULTRON 3547UC INN0035 2560x1080 820x345mm 35.0-inch              | 2        | 1.1%    |
| PRISM+ ULTRON 2754C INN0027 1920x1080 598x337mm 27.0-inch               | 2        | 1.1%    |
| OOO 15.6' monitor OOO0001 1920x1080 409x230mm 18.5-inch                 | 2        | 1.1%    |
| JRY Digital JRY0215 1920x1080 368x207mm 16.6-inch                       | 2        | 1.1%    |
| Goldstar HDR QHD GSM5B96 2560x1440 698x392mm 31.5-inch                  | 2        | 1.1%    |
| Goldstar 2D FHD TV GSM59C6 1920x1080 476x268mm 21.5-inch                | 2        | 1.1%    |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                        | 2        | 1.1%    |
| Yamaha YSP-1600 YMH331A 1920x540                                        | 1        | 0.55%   |
| Xiangye N2408HZ XYE2700 1920x1080 597x336mm 27.0-inch                   | 1        | 0.55%   |
| UPV UP-M30W1 UPV0001 2560x1600 641x401mm 29.8-inch                      | 1        | 0.55%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                              | 1        | 0.55%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                      | 1        | 0.55%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                   | 1        | 0.55%   |
| Unknown LCD Monitor OUT Digital 3200x1080                               | 1        | 0.55%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                       | 1        | 0.55%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                           | 1        | 0.55%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                         | 1        | 0.55%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                            | 1        | 0.55%   |
| Unknown LCD Monitor Digital Projection Limited DP                       | 1        | 0.55%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                              | 1        | 0.55%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                          | 1        | 0.55%   |
| Unknown (ADE) TLED20DHS ADE2000 1600x900 443x249mm 20.0-inch            | 1        | 0.55%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch       | 1        | 0.55%   |
| TopView TOPSYNC TOP049B 2560x1440 597x336mm 27.0-inch                   | 1        | 0.55%   |
| TGL TGL A190 TGL0908 1280x1024 376x301mm 19.0-inch                      | 1        | 0.55%   |
| SiS DV 24 TV SIS0330 1920x1080 930x530mm 42.1-inch                      | 1        | 0.55%   |
| SGT LC156LF1L_03 SGT1560 1920x1080 345x194mm 15.6-inch                  | 1        | 0.55%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch                 | 1        | 0.55%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch       | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM04AE 1680x1050 459x296mm 21.5-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM03F3 1920x1200 518x324mm 24.1-inch    | 1        | 0.55%   |
| Samsung Electronics SyncMaster SAM0384 1280x1024 376x301mm 19.0-inch    | 1        | 0.55%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch       | 1        | 0.55%   |
| Samsung Electronics S32E511 SAM0D11 1920x1080 698x392mm 31.5-inch       | 1        | 0.55%   |
| Samsung Electronics S27D850 SAM0BC7 2560x1440 598x336mm 27.0-inch       | 1        | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 87       | 50.88%  |
| 3840x2160 (4K)     | 19       | 11.11%  |
| 2560x1440 (QHD)    | 16       | 9.36%   |
| 1280x1024 (SXGA)   | 11       | 6.43%   |
| 1920x1200 (WUXGA)  | 7        | 4.09%   |
| 1680x1050 (WSXGA+) | 6        | 3.51%   |
| 3440x1440          | 4        | 2.34%   |
| 2560x1080          | 4        | 2.34%   |
| Unknown            | 3        | 1.75%   |
| 3840x1080          | 2        | 1.17%   |
| 2560x1600          | 2        | 1.17%   |
| 1600x900 (HD+)     | 2        | 1.17%   |
| 1440x900 (WXGA+)   | 2        | 1.17%   |
| 4880x2560          | 1        | 0.58%   |
| 3840x1600          | 1        | 0.58%   |
| 3286x1080          | 1        | 0.58%   |
| 3200x1080          | 1        | 0.58%   |
| 1920x540           | 1        | 0.58%   |
| 1600x1200          | 1        | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 33       | 19.3%   |
| 27      | 29       | 16.96%  |
| 21      | 20       | 11.7%   |
| 23      | 16       | 9.36%   |
| 24      | 14       | 8.19%   |
| 16      | 9        | 5.26%   |
| 19      | 7        | 4.09%   |
| 31      | 6        | 3.51%   |
| 34      | 4        | 2.34%   |
| 20      | 4        | 2.34%   |
| 84      | 3        | 1.75%   |
| 22      | 3        | 1.75%   |
| 18      | 3        | 1.75%   |
| 42      | 2        | 1.17%   |
| 40      | 2        | 1.17%   |
| 35      | 2        | 1.17%   |
| 29      | 2        | 1.17%   |
| 25      | 2        | 1.17%   |
| 17      | 2        | 1.17%   |
| 52      | 1        | 0.58%   |
| 49      | 1        | 0.58%   |
| 48      | 1        | 0.58%   |
| 46      | 1        | 0.58%   |
| 39      | 1        | 0.58%   |
| 37      | 1        | 0.58%   |
| 33      | 1        | 0.58%   |
| 28      | 1        | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 55       | 33.13%  |
| Unknown     | 33       | 19.88%  |
| 401-500     | 29       | 17.47%  |
| 601-700     | 11       | 6.63%   |
| 351-400     | 10       | 6.02%   |
| 301-350     | 8        | 4.82%   |
| 801-900     | 6        | 3.61%   |
| 701-800     | 5        | 3.01%   |
| 1001-1500   | 4        | 2.41%   |
| 1501-2000   | 3        | 1.81%   |
| 901-1000    | 2        | 1.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 92       | 56.44%  |
| Unknown | 30       | 18.4%   |
| 16/10   | 12       | 7.36%   |
| 5/4     | 8        | 4.91%   |
| 4/3     | 8        | 4.91%   |
| 21/9    | 8        | 4.91%   |
| 32/9    | 3        | 1.84%   |
| 6/5     | 1        | 0.61%   |
| 3/2     | 1        | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 42       | 25%     |
| Unknown        | 33       | 19.64%  |
| 301-350        | 30       | 17.86%  |
| 351-500        | 16       | 9.52%   |
| 151-200        | 14       | 8.33%   |
| 251-300        | 9        | 5.36%   |
| 501-1000       | 8        | 4.76%   |
| 131-140        | 6        | 3.57%   |
| More than 1000 | 4        | 2.38%   |
| 141-150        | 3        | 1.79%   |
| 111-120        | 3        | 1.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 76       | 46.34%  |
| 101-120 | 36       | 21.95%  |
| Unknown | 33       | 20.12%  |
| 121-160 | 13       | 7.93%   |
| 1-50    | 3        | 1.83%   |
| 161-240 | 3        | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 143      | 79.44%  |
| 2     | 22       | 12.22%  |
| 0     | 15       | 8.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 127      | 54.98%  |
| Intel                    | 68       | 29.44%  |
| Qualcomm Atheros         | 7        | 3.03%   |
| Broadcom                 | 5        | 2.16%   |
| Ralink Technology        | 4        | 1.73%   |
| MediaTek                 | 4        | 1.73%   |
| Ralink                   | 3        | 1.3%    |
| Marvell Technology Group | 2        | 0.87%   |
| Exar                     | 2        | 0.87%   |
| ASIX Electronics         | 2        | 0.87%   |
| Wilocity                 | 1        | 0.43%   |
| PEAK-System Technik      | 1        | 0.43%   |
| Kinesis                  | 1        | 0.43%   |
| D-Link                   | 1        | 0.43%   |
| Broadcom Limited         | 1        | 0.43%   |
| Aquantia                 | 1        | 0.43%   |
| American Megatrends      | 1        | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 107      | 38.49%  |
| Intel Wi-Fi 6 AX200                                               | 11       | 3.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 3.24%   |
| Intel I211 Gigabit Network Connection                             | 8        | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 2.88%   |
| Intel Ethernet Controller I225-V                                  | 6        | 2.16%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.16%   |
| Intel I210 Gigabit Network Connection                             | 4        | 1.44%   |
| Intel Ethernet Controller X550                                    | 4        | 1.44%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 4        | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3        | 1.08%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.08%   |
| Realtek 802.11ac NIC                                              | 3        | 1.08%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.08%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.08%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.08%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.72%   |
| Realtek 802.11n NIC                                               | 2        | 0.72%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.72%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2        | 0.72%   |
| Intel Wireless 3165                                               | 2        | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2        | 0.72%   |
| Intel Ethernet Controller I226-V                                  | 2        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.72%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.72%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.72%   |
| Exar XR21V1410 USB-UART IC                                        | 2        | 0.72%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.72%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.36%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 32       | 45.71%  |
| Realtek Semiconductor | 21       | 30%     |
| Ralink Technology     | 4        | 5.71%   |
| MediaTek              | 4        | 5.71%   |
| Ralink                | 3        | 4.29%   |
| Qualcomm Atheros      | 2        | 2.86%   |
| Broadcom              | 2        | 2.86%   |
| Wilocity              | 1        | 1.43%   |
| D-Link                | 1        | 1.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 11       | 15.71%  |
| Intel 700 Series Chipset Family Wi-Fi                                  | 4        | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3        | 4.29%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 4.29%   |
| Realtek 802.11ac NIC                                                   | 3        | 4.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 4.29%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 4.29%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 2.86%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 2.86%   |
| Realtek 802.11n NIC                                                    | 2        | 2.86%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 2.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2        | 2.86%   |
| Intel Wireless 3165                                                    | 2        | 2.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 2        | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 2.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 2.86%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1        | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 1.43%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.43%   |
| Ralink RT5572 Wireless Adapter                                         | 1        | 1.43%   |
| Ralink RT5372 Wireless Adapter                                         | 1        | 1.43%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                              | 1        | 1.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.43%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                   | 1        | 1.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.43%   |
| MediaTek WiFi                                                          | 1        | 1.43%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.43%   |
| Intel Wireless-AC 9260                                                 | 1        | 1.43%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.43%   |
| Intel Wireless 7265                                                    | 1        | 1.43%   |
| Intel Wireless 3160                                                    | 1        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 1.43%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU] | 1        | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 123      | 63.73%  |
| Intel                    | 55       | 28.5%   |
| Qualcomm Atheros         | 5        | 2.59%   |
| Broadcom                 | 3        | 1.55%   |
| Marvell Technology Group | 2        | 1.04%   |
| ASIX Electronics         | 2        | 1.04%   |
| Broadcom Limited         | 1        | 0.52%   |
| Aquantia                 | 1        | 0.52%   |
| American Megatrends      | 1        | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 107      | 52.45%  |
| Realtek RTL8125 2.5GbE Controller                                 | 9        | 4.41%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.92%   |
| Intel Ethernet Connection (2) I219-V                              | 8        | 3.92%   |
| Intel Ethernet Controller I225-V                                  | 6        | 2.94%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.94%   |
| Intel I210 Gigabit Network Connection                             | 4        | 1.96%   |
| Intel Ethernet Controller X550                                    | 4        | 1.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.47%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.47%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.98%   |
| Intel Ethernet Controller I226-V                                  | 2        | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.98%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.98%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.98%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.98%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.49%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.49%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.49%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.49%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.49%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.49%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.49%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 0.49%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1        | 0.49%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1        | 0.49%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 179      | 71.6%   |
| WiFi     | 67       | 26.8%   |
| Modem    | 3        | 1.2%    |
| Unknown  | 1        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 158      | 84.04%  |
| WiFi     | 30       | 15.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 63.89%  |
| 2     | 54       | 30%     |
| 3     | 9        | 5%      |
| 5     | 1        | 0.56%   |
| 4     | 1        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 180      | 99.45%  |
| Yes  | 1        | 0.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 29       | 39.19%  |
| Cambridge Silicon Radio | 26       | 35.14%  |
| Realtek Semiconductor   | 8        | 10.81%  |
| Broadcom                | 3        | 4.05%   |
| ASUSTek Computer        | 3        | 4.05%   |
| IMC Networks            | 2        | 2.7%    |
| Foxconn / Hon Hai       | 2        | 2.7%    |
| TP-Link                 | 1        | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 26       | 35.14%  |
| Intel AX200 Bluetooth                                 | 9        | 12.16%  |
| Realtek Bluetooth Radio                               | 8        | 10.81%  |
| Intel Bluetooth Device                                | 8        | 10.81%  |
| Intel Bluetooth wireless interface                    | 5        | 6.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 4.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 2.7%    |
| Intel AX210 Bluetooth                                 | 2        | 2.7%    |
| Intel AX201 Bluetooth                                 | 2        | 2.7%    |
| TP-Link UB5A Adapter                                  | 1        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.35%   |
| IMC Networks Wireless_Device                          | 1        | 1.35%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.35%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.35%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1        | 1.35%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.35%   |
| ASUS Bluetooth Radio                                  | 1        | 1.35%   |
| ASUS Bluetooth Device                                 | 1        | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 119      | 39.02%  |
| Nvidia                               | 91       | 29.84%  |
| AMD                                  | 67       | 21.97%  |
| C-Media Electronics                  | 6        | 1.97%   |
| Giga-Byte Technology                 | 3        | 0.98%   |
| ASUSTek Computer                     | 3        | 0.98%   |
| Micro Star International             | 2        | 0.66%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.33%   |
| Texas Instruments                    | 1        | 0.33%   |
| Sony                                 | 1        | 0.33%   |
| Medeli Electronics                   | 1        | 0.33%   |
| Kingston Technology                  | 1        | 0.33%   |
| JMTek                                | 1        | 0.33%   |
| Generalplus Technology               | 1        | 0.33%   |
| Fry's Electronics                    | 1        | 0.33%   |
| EGO SYStems                          | 1        | 0.33%   |
| DigiTech                             | 1        | 0.33%   |
| Conexant Systems                     | 1        | 0.33%   |
| BEHRINGER International              | 1        | 0.33%   |
| Audient                              | 1        | 0.33%   |
| ASRock                               | 1        | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 4.31%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 4.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 4.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 14       | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 3.45%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 3.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12       | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 3.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10       | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 2.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.87%   |
| Nvidia GP106 High Definition Audio Controller                              | 8        | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8        | 2.3%    |
| Nvidia GA102 High Definition Audio Controller                              | 7        | 2.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 2.01%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 1.72%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 1.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.44%   |
| Nvidia TU102 High Definition Audio Controller                              | 4        | 1.15%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.15%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.15%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.15%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 4        | 1.15%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.15%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.86%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.86%   |
| Nvidia GF106 High Definition Audio Controller                              | 3        | 0.86%   |
| Nvidia Audio device                                                        | 3        | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.86%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 3        | 0.86%   |
| Giga-Byte Technology USB Audio                                             | 3        | 0.86%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                  | 3        | 0.86%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 62       | 68.13%  |
| Unknown             | 5        | 5.49%   |
| SK hynix            | 5        | 5.49%   |
| Team                | 4        | 4.4%    |
| Kingston            | 4        | 4.4%    |
| Crucial             | 3        | 3.3%    |
| KLEVV               | 2        | 2.2%    |
| G.Skill             | 2        | 2.2%    |
| Imation             | 1        | 1.1%    |
| GeIL                | 1        | 1.1%    |
| Corsair             | 1        | 1.1%    |
| A-DATA Technology   | 1        | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 7        | 6.73%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 6        | 5.77%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 3200MT/s | 5        | 4.81%   |
| Samsung RAM M378A5244CB0-CRC 4096MB DIMM DDR4 3066MT/s  | 4        | 3.85%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s     | 3        | 2.88%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 2.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 2.88%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s    | 3        | 2.88%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 2        | 1.92%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 2        | 1.92%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 2        | 1.92%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 1.92%   |
| Samsung RAM M378A2K43EB1-CWE 16GB DIMM DDR4 3200MT/s    | 2        | 1.92%   |
| Samsung RAM M378A2K43BB1-CRC 16GB DIMM DDR4 3200MT/s    | 2        | 1.92%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s    | 2        | 1.92%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3266MT/s  | 2        | 1.92%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s     | 2        | 1.92%   |
| Crucial RAM CT16G56C46U5.M8G1 16384MB DIMM 5600MT/s     | 2        | 1.92%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 0.96%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 1        | 0.96%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 0.96%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 1        | 0.96%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s      | 1        | 0.96%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s      | 1        | 0.96%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s      | 1        | 0.96%   |
| Team RAM TEAMGROUP-UD3-1600 8192MB DIMM DDR3 1600MT/s   | 1        | 0.96%   |
| SK hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s | 1        | 0.96%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 0.96%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 0.96%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 0.96%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s   | 1        | 0.96%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB DIMM DDR4 2133MT/s   | 1        | 0.96%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s              | 1        | 0.96%   |
| Samsung RAM Module 16GB DIMM DDR4 2400MT/s              | 1        | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.96%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 0.96%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s  | 1        | 0.96%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s   | 1        | 0.96%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 56       | 64.37%  |
| DDR3    | 23       | 26.44%  |
| DDR5    | 3        | 3.45%   |
| Unknown | 3        | 3.45%   |
| SDRAM   | 2        | 2.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 83       | 95.4%   |
| SODIMM | 4        | 4.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 30       | 31.58%  |
| 16384 | 25       | 26.32%  |
| 4096  | 21       | 22.11%  |
| 32768 | 14       | 14.74%  |
| 2048  | 3        | 3.16%   |
| 65536 | 1        | 1.05%   |
| 1024  | 1        | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 21       | 21.21%  |
| 1600    | 15       | 15.15%  |
| 3500    | 7        | 7.07%   |
| 2667    | 7        | 7.07%   |
| 2400    | 6        | 6.06%   |
| 2133    | 6        | 6.06%   |
| 3466    | 4        | 4.04%   |
| 3066    | 4        | 4.04%   |
| 1800    | 4        | 4.04%   |
| 2933    | 3        | 3.03%   |
| 1866    | 3        | 3.03%   |
| 5600    | 2        | 2.02%   |
| 4800    | 2        | 2.02%   |
| 3400    | 2        | 2.02%   |
| 3266    | 2        | 2.02%   |
| 2666    | 2        | 2.02%   |
| 1867    | 2        | 2.02%   |
| 1333    | 2        | 2.02%   |
| Unknown | 2        | 2.02%   |
| 4802    | 1        | 1.01%   |
| 3866    | 1        | 1.01%   |
| 3000    | 1        | 1.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 4        | 50%     |
| Seiko Epson         | 2        | 25%     |
| Samsung Electronics | 1        | 12.5%   |
| Brother Industries  | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| Seiko Epson L360 Series    | 1        | 12.5%   |
| Seiko Epson ET-4850 Series | 1        | 12.5%   |
| Samsung CLX-3180 Series    | 1        | 12.5%   |
| Canon PIXMA MP280          | 1        | 12.5%   |
| Canon MF4800 Series        | 1        | 12.5%   |
| Canon G4010 series         | 1        | 12.5%   |
| Canon E560 series          | 1        | 12.5%   |
| Brother DCP-T310           | 1        | 12.5%   |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Sunplus Innovation Technology | 4        | 25%     |
| Logitech                      | 4        | 25%     |
| Samsung Electronics           | 2        | 12.5%   |
| Microdia                      | 2        | 12.5%   |
| lihappe8                      | 2        | 12.5%   |
| Z-Star Microelectronics       | 1        | 6.25%   |
| LG Electronics                | 1        | 6.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Sunplus FHD Camera Microphone                         | 2        | 12.5%   |
| Samsung Galaxy series, misc. (MTP mode)               | 2        | 12.5%   |
| Logitech Webcam C110                                  | 2        | 12.5%   |
| lihappe8 USB 2.0 Camera                               | 2        | 12.5%   |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 6.25%   |
| Sunplus UHD4K                                         | 1        | 6.25%   |
| Sunplus Sandberg USB Webcam Pro                       | 1        | 6.25%   |
| Microdia USB DEVICE                                   | 1        | 6.25%   |
| Microdia Lenovo EasyCamera                            | 1        | 6.25%   |
| Logitech StreamCam                                    | 1        | 6.25%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 6.25%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 6.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

Zero info for selected period =(

Chipcard Model
--------------

Chipcard module models

Zero info for selected period =(

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 149      | 82.32%  |
| 1     | 25       | 13.81%  |
| 2     | 3        | 1.66%   |
| 3     | 2        | 1.1%    |
| 5     | 1        | 0.55%   |
| 4     | 1        | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 12       | 30.77%  |
| Unassigned class         | 8        | 20.51%  |
| Net/wireless             | 7        | 17.95%  |
| Net/ethernet             | 4        | 10.26%  |
| Communication controller | 4        | 10.26%  |
| Camera                   | 2        | 5.13%   |
| Sound                    | 1        | 2.56%   |
| Network                  | 1        | 2.56%   |

