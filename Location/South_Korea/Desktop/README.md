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

Total: 213

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Dell          | 0J1C3P A00                  | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
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
| Ubuntu 20.04                 | 37       | 21.76%  |
| Ubuntu 18.04                 | 21       | 12.35%  |
| Ubuntu 22.04                 | 13       | 7.65%   |
| Ubuntu 20.10                 | 4        | 2.35%   |
| Arch                         | 4        | 2.35%   |
| Ubuntu 19.10                 | 3        | 1.76%   |
| Ubuntu 16.04                 | 3        | 1.76%   |
| openSUSE Tumbleweed-XXXXXXXX | 3        | 1.76%   |
| Fedora 37                    | 3        | 1.76%   |
| Fedora 32                    | 3        | 1.76%   |
| CentOS 7                     | 3        | 1.76%   |
| Zorin 15                     | 2        | 1.18%   |
| Ubuntu Unity 16.04           | 2        | 1.18%   |
| Ubuntu 21.10                 | 2        | 1.18%   |
| TmaxOS 21.12.02              | 2        | 1.18%   |
| RHEL 8                       | 2        | 1.18%   |
| Pop!_OS 22.04                | 2        | 1.18%   |
| OpenMandriva 4.3             | 2        | 1.18%   |
| OpenMandriva 23.01           | 2        | 1.18%   |
| No1 2018                     | 2        | 1.18%   |
| Linux Mint 20.2              | 2        | 1.18%   |
| Linux Mint 20.1              | 2        | 1.18%   |
| Linux Mint 20                | 2        | 1.18%   |
| Linux Mint 19.3              | 2        | 1.18%   |
| Fedora 36                    | 2        | 1.18%   |
| Fedora 34                    | 2        | 1.18%   |
| Debian 11                    | 2        | 1.18%   |
| Debian 10                    | 2        | 1.18%   |
| Chrome OS                    | 2        | 1.18%   |
| Arch Rolling                 | 2        | 1.18%   |
| Zorin 16                     | 1        | 0.59%   |
| Ubuntu 19.04                 | 1        | 0.59%   |
| Ubuntu 18.10                 | 1        | 0.59%   |
| Ubuntu 17.10                 | 1        | 0.59%   |
| Ubuntu                       | 1        | 0.59%   |
| ROSA R10                     | 1        | 0.59%   |
| Rocky Linux 9.1              | 1        | 0.59%   |
| Rocky Linux 8.6              | 1        | 0.59%   |
| Pop!_OS 20.04                | 1        | 0.59%   |
| OpenMandriva 4.50            | 1        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 87       | 51.79%  |
| Fedora       | 12       | 7.14%   |
| Linux Mint   | 8        | 4.76%   |
| OpenMandriva | 7        | 4.17%   |
| Arch         | 6        | 3.57%   |
| Debian       | 5        | 2.98%   |
| CentOS       | 4        | 2.38%   |
| Zorin        | 3        | 1.79%   |
| Pop!_OS      | 3        | 1.79%   |
| openSUSE     | 3        | 1.79%   |
| No1          | 3        | 1.79%   |
| HamoniKR     | 3        | 1.79%   |
| Ubuntu Unity | 2        | 1.19%   |
| TmaxOS       | 2        | 1.19%   |
| Rocky Linux  | 2        | 1.19%   |
| RHEL         | 2        | 1.19%   |
| Kubuntu      | 2        | 1.19%   |
| Chrome OS    | 2        | 1.19%   |
| ROSA         | 1        | 0.6%    |
| Nobara       | 1        | 0.6%    |
| Manjaro      | 1        | 0.6%    |
| Lubuntu      | 1        | 0.6%    |
| KDE neon     | 1        | 0.6%    |
| Gooroom      | 1        | 0.6%    |
| Endless      | 1        | 0.6%    |
| EndeavourOS  | 1        | 0.6%    |
| Devuan       | 1        | 0.6%    |
| BlackPanther | 1        | 0.6%    |
| ArcoLinux    | 1        | 0.6%    |
| Alpine       | 1        | 0.6%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.0-29-generic          | 4        | 2.22%   |
| 5.15.0-43-generic         | 4        | 2.22%   |
| 5.4.0-26-generic          | 3        | 1.67%   |
| 5.15.0-41-generic         | 3        | 1.67%   |
| 6.1.1-desktop-1omv2290    | 2        | 1.11%   |
| 5.8.0-48-generic          | 2        | 1.11%   |
| 5.8.0-38-generic          | 2        | 1.11%   |
| 5.4.0-56-generic          | 2        | 1.11%   |
| 5.4.0-54-generic          | 2        | 1.11%   |
| 5.4.0-52-generic          | 2        | 1.11%   |
| 5.4.0-47-generic          | 2        | 1.11%   |
| 5.4.0-42-generic          | 2        | 1.11%   |
| 5.4.0-37-generic          | 2        | 1.11%   |
| 5.3.0-51-generic          | 2        | 1.11%   |
| 5.3.0-40-generic          | 2        | 1.11%   |
| 5.16.7-desktop-1omv4003   | 2        | 1.11%   |
| 5.15.0-53-generic         | 2        | 1.11%   |
| 5.15.0-52-generic         | 2        | 1.11%   |
| 5.15.0-50-generic         | 2        | 1.11%   |
| 5.14.0-0.bpo.2-amd64      | 2        | 1.11%   |
| 5.13.0-21-generic         | 2        | 1.11%   |
| 4.19.0-14-amd64           | 2        | 1.11%   |
| 4.18.0-25-generic         | 2        | 1.11%   |
| 4.15.0-91-generic         | 2        | 1.11%   |
| 6.2.8-200.fc37.x86_64     | 1        | 0.56%   |
| 6.2.6-desktop-1omv2390    | 1        | 0.56%   |
| 6.2.2-arch2-1             | 1        | 0.56%   |
| 6.1.8-060108-generic      | 1        | 0.56%   |
| 6.1.6-1-default           | 1        | 0.56%   |
| 6.1.11-no1linux1          | 1        | 0.56%   |
| 6.1.10-200.fc37.x86_64    | 1        | 0.56%   |
| 6.0.9-arch1-1             | 1        | 0.56%   |
| 6.0.15-200.fc36.x86_64    | 1        | 0.56%   |
| 6.0.12-300.fc37.x86_64    | 1        | 0.56%   |
| 6.0.1-arch1-1             | 1        | 0.56%   |
| 6.0.0-0.deb11.6-amd64     | 1        | 0.56%   |
| 5.9.0-12.1-liquorix-amd64 | 1        | 0.56%   |
| 5.8.5-no1linux1           | 1        | 0.56%   |
| 5.8.16-300.fc33.x86_64    | 1        | 0.56%   |
| 5.8.10-200.fc32.x86_64    | 1        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 35       | 20.11%  |
| 4.15.0  | 18       | 10.34%  |
| 5.15.0  | 17       | 9.77%   |
| 5.8.0   | 13       | 7.47%   |
| 4.18.0  | 10       | 5.75%   |
| 5.3.0   | 9        | 5.17%   |
| 5.13.0  | 5        | 2.87%   |
| 5.14.0  | 4        | 2.3%    |
| 5.0.0   | 3        | 1.72%   |
| 4.19.0  | 3        | 1.72%   |
| 6.1.1   | 2        | 1.15%   |
| 5.16.7  | 2        | 1.15%   |
| 5.11.0  | 2        | 1.15%   |
| 5.10.0  | 2        | 1.15%   |
| 4.13.0  | 2        | 1.15%   |
| 3.10.0  | 2        | 1.15%   |
| 6.2.8   | 1        | 0.57%   |
| 6.2.6   | 1        | 0.57%   |
| 6.2.2   | 1        | 0.57%   |
| 6.1.8   | 1        | 0.57%   |
| 6.1.6   | 1        | 0.57%   |
| 6.1.11  | 1        | 0.57%   |
| 6.1.10  | 1        | 0.57%   |
| 6.0.9   | 1        | 0.57%   |
| 6.0.15  | 1        | 0.57%   |
| 6.0.12  | 1        | 0.57%   |
| 6.0.1   | 1        | 0.57%   |
| 6.0.0   | 1        | 0.57%   |
| 5.9.0   | 1        | 0.57%   |
| 5.8.5   | 1        | 0.57%   |
| 5.8.16  | 1        | 0.57%   |
| 5.8.10  | 1        | 0.57%   |
| 5.7.16  | 1        | 0.57%   |
| 5.6.6   | 1        | 0.57%   |
| 5.6.12  | 1        | 0.57%   |
| 5.4.25  | 1        | 0.57%   |
| 5.4.2   | 1        | 0.57%   |
| 5.19.3  | 1        | 0.57%   |
| 5.19.0  | 1        | 0.57%   |
| 5.18.9  | 1        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 37       | 21.39%  |
| 5.15    | 19       | 10.98%  |
| 4.15    | 19       | 10.98%  |
| 5.8     | 16       | 9.25%   |
| 4.18    | 11       | 6.36%   |
| 5.3     | 9        | 5.2%    |
| 6.1     | 6        | 3.47%   |
| 5.14    | 6        | 3.47%   |
| 6.0     | 5        | 2.89%   |
| 5.13    | 5        | 2.89%   |
| 5.10    | 5        | 2.89%   |
| 5.16    | 4        | 2.31%   |
| 5.11    | 4        | 2.31%   |
| 5.0     | 4        | 2.31%   |
| 4.19    | 4        | 2.31%   |
| 6.2     | 3        | 1.73%   |
| 5.6     | 2        | 1.16%   |
| 5.19    | 2        | 1.16%   |
| 5.18    | 2        | 1.16%   |
| 4.9     | 2        | 1.16%   |
| 4.13    | 2        | 1.16%   |
| 3.10    | 2        | 1.16%   |
| 5.9     | 1        | 0.58%   |
| 5.7     | 1        | 0.58%   |
| 5.12    | 1        | 0.58%   |
| 4.17    | 1        | 0.58%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 164      | 99.39%  |
| i686   | 1        | 0.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 82       | 49.1%   |
| Unknown         | 37       | 22.16%  |
| KDE5            | 21       | 12.57%  |
| X-Cinnamon      | 8        | 4.79%   |
| XFCE            | 7        | 4.19%   |
| Unity           | 2        | 1.2%    |
| TOS:GNOME       | 2        | 1.2%    |
| KDE             | 2        | 1.2%    |
| Cinnamon        | 2        | 1.2%    |
| LXDE            | 1        | 0.6%    |
| KDE4            | 1        | 0.6%    |
| GNOME Flashback | 1        | 0.6%    |
| GNOME Classic   | 1        | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 111      | 66.87%  |
| Wayland | 23       | 13.86%  |
| Unknown | 23       | 13.86%  |
| Tty     | 9        | 5.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 101      | 60.84%  |
| GDM     | 20       | 12.05%  |
| SDDM    | 18       | 10.84%  |
| GDM3    | 17       | 10.24%  |
| LightDM | 6        | 3.61%   |
| TDM     | 3        | 1.81%   |
| SLiM    | 1        | 0.6%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ko_KR   | 69       | 41.57%  |
| en_US   | 59       | 35.54%  |
| Unknown | 29       | 17.47%  |
| C       | 3        | 1.81%   |
| ru_RU   | 1        | 0.6%    |
| id_ID   | 1        | 0.6%    |
| fr_FR   | 1        | 0.6%    |
| en_GB   | 1        | 0.6%    |
| en_CA   | 1        | 0.6%    |
| en_AU   | 1        | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 85       | 50.9%   |
| BIOS | 82       | 49.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 132      | 79.04%  |
| Btrfs   | 10       | 5.99%   |
| Unknown | 9        | 5.39%   |
| Xfs     | 6        | 3.59%   |
| Overlay | 6        | 3.59%   |
| Zfs     | 3        | 1.8%    |
| Rootfs  | 1        | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 97       | 58.08%  |
| GPT     | 57       | 34.13%  |
| MBR     | 13       | 7.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 137      | 82.53%  |
| Yes       | 29       | 17.47%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 115      | 69.7%   |
| Yes       | 50       | 30.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 37       | 22.42%  |
| Gigabyte Technology | 36       | 21.82%  |
| ASRock              | 30       | 18.18%  |
| MSI                 | 15       | 9.09%   |
| ECS                 | 7        | 4.24%   |
| Samsung Electronics | 6        | 3.64%   |
| Lenovo              | 6        | 3.64%   |
| Hewlett-Packard     | 5        | 3.03%   |
| Dell                | 4        | 2.42%   |
| Foxconn             | 3        | 1.82%   |
| LattePanda          | 2        | 1.21%   |
| Huanan              | 2        | 1.21%   |
| Unknown             | 2        | 1.21%   |
| WTM                 | 1        | 0.61%   |
| PCPartner           | 1        | 0.61%   |
| PC Partner Limited  | 1        | 0.61%   |
| Fujitsu             | 1        | 0.61%   |
| ELSKY               | 1        | 0.61%   |
| ECS2                | 1        | 0.61%   |
| Biostar             | 1        | 0.61%   |
| ASRockRack          | 1        | 0.61%   |
| AMD                 | 1        | 0.61%   |
| Alienware           | 1        | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung DeskTop System                 | 4        | 2.42%   |
| ASUS PRIME B350M-A                     | 3        | 1.82%   |
| MSI MS-7D42                            | 2        | 1.21%   |
| MSI MS-7B89                            | 2        | 1.21%   |
| LattePanda Alpha                       | 2        | 1.21%   |
| Gigabyte TRX40 AORUS XTREME            | 2        | 1.21%   |
| Gigabyte H81M-DS2V                     | 2        | 1.21%   |
| Gigabyte B75M-D3V                      | 2        | 1.21%   |
| Gigabyte B75M-D3H                      | 2        | 1.21%   |
| Gigabyte B360M-D3H                     | 2        | 1.21%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4   | 2        | 1.21%   |
| ASUS PRIME A320M-K                     | 2        | 1.21%   |
| ASUS EX-A320M-GAMING                   | 2        | 1.21%   |
| ASUS All Series                        | 2        | 1.21%   |
| ASRock H81M-DGS R2.0                   | 2        | 1.21%   |
| ASRock AB350M Pro4                     | 2        | 1.21%   |
| Unknown                                | 2        | 1.21%   |
| WTM W-N95                              | 1        | 0.61%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.61%   |
| Samsung 400T7A/400S7A                  | 1        | 0.61%   |
| PCPartner DREAMSYS                     | 1        | 0.61%   |
| PC Partner Limited S70BS.AH3511        | 1        | 0.61%   |
| MSI MS-7D91                            | 1        | 0.61%   |
| MSI MS-7C94                            | 1        | 0.61%   |
| MSI MS-7C75                            | 1        | 0.61%   |
| MSI MS-7C51                            | 1        | 0.61%   |
| MSI MS-7B85                            | 1        | 0.61%   |
| MSI MS-7B24                            | 1        | 0.61%   |
| MSI MS-7A74                            | 1        | 0.61%   |
| MSI MS-7A37                            | 1        | 0.61%   |
| MSI MS-7A20                            | 1        | 0.61%   |
| MSI MS-7A15                            | 1        | 0.61%   |
| MSI MS-7808                            | 1        | 0.61%   |
| Lenovo ThinkStation P900 30A4A03600    | 1        | 0.61%   |
| Lenovo ThinkStation P520c 30BXCTO1WW   | 1        | 0.61%   |
| Lenovo ThinkStation P500 30A6A3KSKR    | 1        | 0.61%   |
| Lenovo ThinkCentre M72e 4004H1U        | 1        | 0.61%   |
| Lenovo IdeaCentre 5 14IMB05 90NA0028KR | 1        | 0.61%   |
| Lenovo 70A4000FUX ThinkServer TS140    | 1        | 0.61%   |
| Huanan X99-F8                          | 1        | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME                      | 13       | 7.88%   |
| ASUS ROG                        | 5        | 3.03%   |
| Samsung DeskTop                 | 4        | 2.42%   |
| Lenovo ThinkStation             | 3        | 1.82%   |
| MSI MS-7D42                     | 2        | 1.21%   |
| MSI MS-7B89                     | 2        | 1.21%   |
| LattePanda Alpha                | 2        | 1.21%   |
| Gigabyte Z390                   | 2        | 1.21%   |
| Gigabyte X570                   | 2        | 1.21%   |
| Gigabyte TRX40                  | 2        | 1.21%   |
| Gigabyte H81M-DS2V              | 2        | 1.21%   |
| Gigabyte B75M-D3V               | 2        | 1.21%   |
| Gigabyte B75M-D3H               | 2        | 1.21%   |
| Gigabyte B360M-D3H              | 2        | 1.21%   |
| Dell Vostro                     | 2        | 1.21%   |
| ASUS EX-A320M-GAMING            | 2        | 1.21%   |
| ASUS All                        | 2        | 1.21%   |
| ASRock Z390                     | 2        | 1.21%   |
| ASRock H81M-DGS                 | 2        | 1.21%   |
| ASRock FM2A88M-HD+              | 2        | 1.21%   |
| ASRock AB350M                   | 2        | 1.21%   |
| Unknown                         | 2        | 1.21%   |
| WTM W-N95                       | 1        | 0.61%   |
| Samsung 500T8A                  | 1        | 0.61%   |
| Samsung 400T7A                  | 1        | 0.61%   |
| PCPartner DREAMSYS              | 1        | 0.61%   |
| PC Partner Limited S70BS.AH3511 | 1        | 0.61%   |
| MSI MS-7D91                     | 1        | 0.61%   |
| MSI MS-7C94                     | 1        | 0.61%   |
| MSI MS-7C75                     | 1        | 0.61%   |
| MSI MS-7C51                     | 1        | 0.61%   |
| MSI MS-7B85                     | 1        | 0.61%   |
| MSI MS-7B24                     | 1        | 0.61%   |
| MSI MS-7A74                     | 1        | 0.61%   |
| MSI MS-7A37                     | 1        | 0.61%   |
| MSI MS-7A20                     | 1        | 0.61%   |
| MSI MS-7A15                     | 1        | 0.61%   |
| MSI MS-7808                     | 1        | 0.61%   |
| Lenovo ThinkCentre              | 1        | 0.61%   |
| Lenovo IdeaCentre               | 1        | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 21       | 12.73%  |
| 2012 | 19       | 11.52%  |
| 2017 | 17       | 10.3%   |
| 2019 | 14       | 8.48%   |
| 2020 | 12       | 7.27%   |
| 2021 | 11       | 6.67%   |
| 2013 | 11       | 6.67%   |
| 2014 | 9        | 5.45%   |
| 2015 | 8        | 4.85%   |
| 2022 | 7        | 4.24%   |
| 2016 | 7        | 4.24%   |
| 2009 | 7        | 4.24%   |
| 2010 | 6        | 3.64%   |
| 2008 | 5        | 3.03%   |
| 2007 | 5        | 3.03%   |
| 2011 | 3        | 1.82%   |
| 2006 | 2        | 1.21%   |
| 2005 | 1        | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 165      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 161      | 97.58%  |
| Enabled  | 4        | 2.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 165      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 34       | 20.36%  |
| 16.01-24.0      | 29       | 17.37%  |
| 64.01-256.0     | 26       | 15.57%  |
| 4.01-8.0        | 22       | 13.17%  |
| 32.01-64.0      | 21       | 12.57%  |
| 3.01-4.0        | 21       | 12.57%  |
| 24.01-32.0      | 5        | 2.99%   |
| 1.01-2.0        | 4        | 2.4%    |
| More than 256.0 | 3        | 1.8%    |
| 2.01-3.0        | 2        | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 56       | 31.64%  |
| 2.01-3.0   | 36       | 20.34%  |
| 3.01-4.0   | 31       | 17.51%  |
| 4.01-8.0   | 24       | 13.56%  |
| 8.01-16.0  | 11       | 6.21%   |
| 0.51-1.0   | 11       | 6.21%   |
| 32.01-64.0 | 3        | 1.69%   |
| 16.01-24.0 | 3        | 1.69%   |
| 0.01-0.5   | 2        | 1.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 60       | 35.93%  |
| 2      | 53       | 31.74%  |
| 3      | 22       | 13.17%  |
| 4      | 12       | 7.19%   |
| 5      | 8        | 4.79%   |
| 6      | 6        | 3.59%   |
| 7      | 2        | 1.2%    |
| 10     | 1        | 0.6%    |
| 9      | 1        | 0.6%    |
| 8      | 1        | 0.6%    |
| 0      | 1        | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 113      | 68.07%  |
| Yes       | 53       | 31.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 164      | 99.39%  |
| No        | 1        | 0.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 107      | 64.46%  |
| Yes       | 59       | 35.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 60.71%  |
| Yes       | 66       | 39.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| South Korea | 165      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Seoul           | 15       | 8.62%   |
| Seongnam-si     | 13       | 7.47%   |
| Yongin-si       | 8        | 4.6%    |
| Suwon           | 7        | 4.02%   |
| Busan           | 6        | 3.45%   |
| Goyang-si       | 5        | 2.87%   |
| Cheonan         | 5        | 2.87%   |
| Incheon         | 4        | 2.3%    |
| Hwaseong-si     | 4        | 2.3%    |
| Gwanak-gu       | 4        | 2.3%    |
| Bucheon-si      | 4        | 2.3%    |
| Seo-gu          | 3        | 1.72%   |
| Pyeongtaek-si   | 3        | 1.72%   |
| Nam-gu          | 3        | 1.72%   |
| Guri-si         | 3        | 1.72%   |
| Gangseo-gu      | 3        | 1.72%   |
| Gangnam-gu      | 3        | 1.72%   |
| Anyang-si       | 3        | 1.72%   |
| Ansan-si        | 3        | 1.72%   |
| Yongsan-gu      | 2        | 1.15%   |
| Yangcheon-gu    | 2        | 1.15%   |
| Uiwang          | 2        | 1.15%   |
| Uiseong-gun     | 2        | 1.15%   |
| Siheung-si      | 2        | 1.15%   |
| Seongdong-gu    | 2        | 1.15%   |
| Seongbuk-gu     | 2        | 1.15%   |
| Sejong          | 2        | 1.15%   |
| Osan            | 2        | 1.15%   |
| Gyeonggi-do     | 2        | 1.15%   |
| Gwangmyeong-si  | 2        | 1.15%   |
| Dongjak-gu      | 2        | 1.15%   |
| Daejeon         | 2        | 1.15%   |
| Yuseong-gu      | 1        | 0.57%   |
| Yuseong         | 1        | 0.57%   |
| Yeonsu-gu       | 1        | 0.57%   |
| Yeongdeungpo-gu | 1        | 0.57%   |
| Yangp'yong      | 1        | 0.57%   |
| Wonju           | 1        | 0.57%   |
| Ulsan           | 1        | 0.57%   |
| Ulju-gun        | 1        | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 60       | 105    | 19.87%  |
| Samsung Electronics       | 49       | 72     | 16.23%  |
| Seagate                   | 47       | 78     | 15.56%  |
| Toshiba                   | 20       | 36     | 6.62%   |
| SanDisk                   | 20       | 25     | 6.62%   |
| Crucial                   | 19       | 23     | 6.29%   |
| Hitachi                   | 11       | 12     | 3.64%   |
| Unknown                   | 9        | 10     | 2.98%   |
| SK hynix                  | 7        | 9      | 2.32%   |
| Transcend                 | 6        | 6      | 1.99%   |
| A-DATA Technology         | 6        | 6      | 1.99%   |
| HGST                      | 5        | 5      | 1.66%   |
| Micron Technology         | 4        | 5      | 1.32%   |
| SPCC                      | 3        | 3      | 0.99%   |
| Silicon Motion            | 3        | 4      | 0.99%   |
| Plextor                   | 3        | 5      | 0.99%   |
| Intel                     | 3        | 3      | 0.99%   |
| TAMMUZ                    | 2        | 3      | 0.66%   |
| China                     | 2        | 2      | 0.66%   |
| ZOTAC                     | 1        | 1      | 0.33%   |
| Team                      | 1        | 1      | 0.33%   |
| Seagate Technology        | 1        | 1      | 0.33%   |
| Realtek Semiconductor     | 1        | 1      | 0.33%   |
| QNIX                      | 1        | 1      | 0.33%   |
| Phison                    | 1        | 2      | 0.33%   |
| PHINOCOM                  | 1        | 1      | 0.33%   |
| OSCOO                     | 1        | 1      | 0.33%   |
| OCZ                       | 1        | 2      | 0.33%   |
| Netac                     | 1        | 1      | 0.33%   |
| Micron/Crucial Technology | 1        | 1      | 0.33%   |
| MARVELL                   | 1        | 1      | 0.33%   |
| LITEON                    | 1        | 1      | 0.33%   |
| LaCie                     | 1        | 1      | 0.33%   |
| KIOXIA                    | 1        | 3      | 0.33%   |
| KingSpec                  | 1        | 1      | 0.33%   |
| JMicron Technology        | 1        | 1      | 0.33%   |
| Imation                   | 1        | 2      | 0.33%   |
| Hewlett-Packard           | 1        | 1      | 0.33%   |
| GLOWAY                    | 1        | 1      | 0.33%   |
| Fujitsu                   | 1        | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Toshiba DT01ACA300 3TB                 | 7        | 1.96%   |
| Seagate ST500DM002-1BD142 500GB        | 6        | 1.68%   |
| Crucial CT240BX500SSD1 240GB           | 6        | 1.68%   |
| Crucial CT500MX500SSD1 500GB           | 5        | 1.4%    |
| Toshiba DT01ACA200 2TB                 | 4        | 1.12%   |
| SanDisk SD8SBAT128G1122 128GB SSD      | 4        | 1.12%   |
| Samsung SSD 850 EVO 120GB              | 4        | 1.12%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3        | 0.84%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 3        | 0.84%   |
| WDC WD40EZAZ-00SF3B0 4TB               | 3        | 0.84%   |
| WDC WD40EFRX-68WT0N0 4TB               | 3        | 0.84%   |
| WDC WD3200AAJS-00L7A0 320GB            | 3        | 0.84%   |
| WDC WD10EZEX-22MFCA0 1TB               | 3        | 0.84%   |
| WDC WD10EZEX-08WN4A0 1TB               | 3        | 0.84%   |
| Unknown SD/MMC/MS PRO 64GB             | 3        | 0.84%   |
| Toshiba DT01ACA050 500GB               | 3        | 0.84%   |
| Seagate ST3500418AS 500GB              | 3        | 0.84%   |
| Seagate ST2000DM008-2FR102 2TB         | 3        | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB         | 3        | 0.84%   |
| Seagate ST1000DM003-1CH162 1TB         | 3        | 0.84%   |
| Samsung SSD 850 PRO 256GB              | 3        | 0.84%   |
| Samsung SSD 850 EVO 250GB              | 3        | 0.84%   |
| Crucial CT275MX300SSD4 275GB           | 3        | 0.84%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2        | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2        | 0.56%   |
| WDC WD20EARX-00PASB0 2TB               | 2        | 0.56%   |
| WDC WD10EZEX-00WN4A0 1TB               | 2        | 0.56%   |
| Transcend TS240GSSD220S 240GB          | 2        | 0.56%   |
| Toshiba HDWD120 2TB                    | 2        | 0.56%   |
| TAMMUZ SSD 128GB                       | 2        | 0.56%   |
| SK hynix SHGP31-500GM 500GB            | 2        | 0.56%   |
| SK hynix SHGP31-2000GM 2TB             | 2        | 0.56%   |
| Seagate ST8000DM004-2CX188 8TB         | 2        | 0.56%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 0.56%   |
| SanDisk SD7SB6S128G1122 128GB SSD      | 2        | 0.56%   |
| Samsung SSD 860 EVO 250GB              | 2        | 0.56%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2        | 0.56%   |
| Samsung NVMe SSD Drive 1TB             | 2        | 0.56%   |
| Samsung MZVL21T0HCLR-00B00 1TB         | 2        | 0.56%   |
| Samsung HD502IJ 500GB                  | 2        | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 52       | 89     | 35.86%  |
| Seagate             | 45       | 73     | 31.03%  |
| Toshiba             | 17       | 26     | 11.72%  |
| Hitachi             | 11       | 12     | 7.59%   |
| Samsung Electronics | 8        | 9      | 5.52%   |
| HGST                | 5        | 5      | 3.45%   |
| Unknown             | 3        | 4      | 2.07%   |
| MARVELL             | 1        | 1      | 0.69%   |
| LaCie               | 1        | 1      | 0.69%   |
| Hewlett-Packard     | 1        | 1      | 0.69%   |
| Fujitsu             | 1        | 1      | 0.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 26       | 33     | 22.81%  |
| Crucial             | 19       | 23     | 16.67%  |
| SanDisk             | 17       | 20     | 14.91%  |
| WDC                 | 10       | 14     | 8.77%   |
| Transcend           | 6        | 6      | 5.26%   |
| A-DATA Technology   | 5        | 5      | 4.39%   |
| Toshiba             | 3        | 10     | 2.63%   |
| SPCC                | 3        | 3      | 2.63%   |
| Seagate             | 3        | 4      | 2.63%   |
| TAMMUZ              | 2        | 3      | 1.75%   |
| SK hynix            | 2        | 3      | 1.75%   |
| Plextor             | 2        | 4      | 1.75%   |
| Intel               | 2        | 2      | 1.75%   |
| China               | 2        | 2      | 1.75%   |
| QNIX                | 1        | 1      | 0.88%   |
| PHINOCOM            | 1        | 1      | 0.88%   |
| OSCOO               | 1        | 1      | 0.88%   |
| OCZ                 | 1        | 2      | 0.88%   |
| Netac               | 1        | 1      | 0.88%   |
| Micron Technology   | 1        | 1      | 0.88%   |
| LITEON              | 1        | 1      | 0.88%   |
| KingSpec            | 1        | 1      | 0.88%   |
| JMicron Technology  | 1        | 1      | 0.88%   |
| Imation             | 1        | 2      | 0.88%   |
| GLOWAY              | 1        | 1      | 0.88%   |
| Unknown             | 1        | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 111      | 222    | 43.02%  |
| SSD     | 97       | 146    | 37.6%   |
| NVMe    | 44       | 66     | 17.05%  |
| MMC     | 3        | 3      | 1.16%   |
| Unknown | 3        | 3      | 1.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 147      | 362    | 72.77%  |
| NVMe | 44       | 66     | 21.78%  |
| SAS  | 8        | 9      | 3.96%   |
| MMC  | 3        | 3      | 1.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 113      | 184    | 50%     |
| 0.51-1.0   | 45       | 69     | 19.91%  |
| 1.01-2.0   | 27       | 37     | 11.95%  |
| 3.01-4.0   | 18       | 36     | 7.96%   |
| 2.01-3.0   | 10       | 14     | 4.42%   |
| 4.01-10.0  | 10       | 19     | 4.42%   |
| 10.01-20.0 | 3        | 9      | 1.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 40       | 23.81%  |
| 251-500        | 33       | 19.64%  |
| 501-1000       | 23       | 13.69%  |
| More than 3000 | 18       | 10.71%  |
| 1001-2000      | 16       | 9.52%   |
| 2001-3000      | 15       | 8.93%   |
| 21-50          | 7        | 4.17%   |
| 1-20           | 6        | 3.57%   |
| 51-100         | 6        | 3.57%   |
| Unknown        | 4        | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 64       | 37.43%  |
| 21-50          | 24       | 14.04%  |
| 101-250        | 20       | 11.7%   |
| 51-100         | 16       | 9.36%   |
| 251-500        | 14       | 8.19%   |
| 501-1000       | 12       | 7.02%   |
| More than 3000 | 7        | 4.09%   |
| 2001-3000      | 7        | 4.09%   |
| Unknown        | 4        | 2.34%   |
| 1001-2000      | 3        | 1.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| WDC WD7500AACS-00D6B0 752GB                                     | 1        | 1      | 7.14%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 1        | 1      | 7.14%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1        | 1      | 7.14%   |
| WDC WD3200AAJS-00L7A0 320GB                                     | 1        | 2      | 7.14%   |
| WDC WD1600BEVT-22A23T0 160GB                                    | 1        | 1      | 7.14%   |
| WDC WD1001FALS-00J7B1 1TB                                       | 1        | 1      | 7.14%   |
| Seagate ST500DM009-2F110A 500GB                                 | 1        | 1      | 7.14%   |
| Seagate ST4000DM000-1F2168 4TB                                  | 1        | 1      | 7.14%   |
| Seagate ST3500418AS 500GB                                       | 1        | 1      | 7.14%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 1        | 1      | 7.14%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 1        | 1      | 7.14%   |
| LITEON LMH-128V2M 128GB SSD                                     | 1        | 1      | 7.14%   |
| HGST HDN726060ALE610 6TB                                        | 1        | 1      | 7.14%   |
| A-DATA Technology SU650 240GB SSD                               | 1        | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 6        | 7      | 42.86%  |
| Seagate             | 4        | 4      | 28.57%  |
| Samsung Electronics | 1        | 1      | 7.14%   |
| LITEON              | 1        | 1      | 7.14%   |
| HGST                | 1        | 1      | 7.14%   |
| A-DATA Technology   | 1        | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 6        | 7      | 54.55%  |
| Seagate | 4        | 4      | 36.36%  |
| HGST    | 1        | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 9        | 12     | 75%     |
| SSD  | 2        | 2      | 16.67%  |
| NVMe | 1        | 1      | 8.33%   |

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
| Detected | 104      | 274    | 58.43%  |
| Works    | 62       | 151    | 34.83%  |
| Malfunc  | 12       | 15     | 6.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 115      | 46.94%  |
| AMD                        | 47       | 19.18%  |
| Samsung Electronics        | 24       | 9.8%    |
| ASMedia Technology         | 14       | 5.71%   |
| JMicron Technology         | 11       | 4.49%   |
| SK hynix                   | 5        | 2.04%   |
| Silicon Motion             | 4        | 1.63%   |
| SanDisk                    | 4        | 1.63%   |
| Marvell Technology Group   | 4        | 1.63%   |
| Phison Electronics         | 3        | 1.22%   |
| Micron Technology          | 3        | 1.22%   |
| Seagate Technology         | 2        | 0.82%   |
| VIA Technologies           | 1        | 0.41%   |
| Realtek Semiconductor      | 1        | 0.41%   |
| Micron/Crucial Technology  | 1        | 0.41%   |
| Lite-On Technology         | 1        | 0.41%   |
| Lite-On IT Corp. / Plextor | 1        | 0.41%   |
| KIOXIA                     | 1        | 0.41%   |
| Broadcom / LSI             | 1        | 0.41%   |
| Biwin Storage Technology   | 1        | 0.41%   |
| ADATA Technology           | 1        | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 35       | 11.18%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 5.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 4.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12       | 3.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11       | 3.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9        | 2.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 2.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.56%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.56%   |
| AMD FCH SATA Controller D                                                               | 8        | 2.56%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 2.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.24%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7        | 2.24%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6        | 1.92%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 5        | 1.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 1.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5        | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5        | 1.6%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1.28%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4        | 1.28%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4        | 1.28%   |
| Samsung NVMe SSD Controller 980                                                         | 3        | 0.96%   |
| Micron NVMe Storage Controller                                                          | 3        | 0.96%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.96%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                                    | 3        | 0.96%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 0.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.64%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.64%   |
| JMicron JMB58x AHCI SATA controller                                                     | 2        | 0.64%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.64%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2        | 0.64%   |
| Intel C610/X99 series chipset IDE-r Controller                                          | 2        | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2        | 0.64%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 139      | 60.96%  |
| NVMe | 46       | 20.18%  |
| IDE  | 34       | 14.91%  |
| RAID | 8        | 3.51%   |
| SAS  | 1        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 118      | 71.52%  |
| AMD    | 47       | 28.48%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz            | 8        | 4.85%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 5        | 3.03%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.03%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 2.42%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 2.42%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 3        | 1.82%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 1.82%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 1.82%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 1.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.82%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 1.82%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.21%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 2        | 1.21%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 1.21%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2        | 1.21%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 1.21%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.21%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.21%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.21%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.21%   |
| Intel 13th Gen Core i9-13900K               | 2        | 1.21%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.21%   |
| Intel Xeon W-3275M CPU @ 2.50GHz            | 1        | 0.61%   |
| Intel Xeon W-2133 CPU @ 3.60GHz             | 1        | 0.61%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz          | 1        | 0.61%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.61%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.61%   |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 0.61%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 1        | 0.61%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.61%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.61%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.61%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.61%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 34       | 20.61%  |
| Intel Core i7           | 15       | 9.09%   |
| AMD Ryzen 5             | 15       | 9.09%   |
| Intel Xeon              | 12       | 7.27%   |
| Other                   | 10       | 6.06%   |
| Intel Core i3           | 10       | 6.06%   |
| Intel Pentium           | 7        | 4.24%   |
| Intel Core i9           | 7        | 4.24%   |
| AMD Ryzen 7             | 7        | 4.24%   |
| Intel Core 2 Quad       | 6        | 3.64%   |
| Intel Celeron           | 5        | 3.03%   |
| AMD Ryzen Threadripper  | 5        | 3.03%   |
| AMD Ryzen 3             | 5        | 3.03%   |
| AMD Ryzen 9             | 3        | 1.82%   |
| Intel Pentium Gold      | 2        | 1.21%   |
| Intel Pentium Dual-Core | 2        | 1.21%   |
| Intel Pentium 4         | 2        | 1.21%   |
| Intel Core m3           | 2        | 1.21%   |
| Intel Core 2 Duo        | 2        | 1.21%   |
| AMD A8                  | 2        | 1.21%   |
| AMD A10                 | 2        | 1.21%   |
| Intel Xeon Gold         | 1        | 0.61%   |
| Intel Core 2            | 1        | 0.61%   |
| AMD Ryzen Embedded      | 1        | 0.61%   |
| AMD Ryzen 7 PRO         | 1        | 0.61%   |
| AMD Ryzen 5 PRO         | 1        | 0.61%   |
| AMD Phenom II X6        | 1        | 0.61%   |
| AMD Phenom              | 1        | 0.61%   |
| AMD FX                  | 1        | 0.61%   |
| AMD Athlon II X2        | 1        | 0.61%   |
| AMD Athlon 64 X2        | 1        | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 58       | 35.15%  |
| 2      | 35       | 21.21%  |
| 6      | 31       | 18.79%  |
| 8      | 16       | 9.7%    |
| 16     | 5        | 3.03%   |
| 10     | 4        | 2.42%   |
| 32     | 3        | 1.82%   |
| 12     | 3        | 1.82%   |
| 24     | 2        | 1.21%   |
| 1      | 2        | 1.21%   |
| 64     | 1        | 0.61%   |
| 28     | 1        | 0.61%   |
| 22     | 1        | 0.61%   |
| 20     | 1        | 0.61%   |
| 18     | 1        | 0.61%   |
| 14     | 1        | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 163      | 98.79%  |
| 2      | 2        | 1.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 91       | 55.15%  |
| 1      | 74       | 44.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 162      | 97.59%  |
| Unknown        | 4        | 2.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 35       | 20.96%  |
| 0x306c3    | 16       | 9.58%   |
| 0x306a9    | 16       | 9.58%   |
| 0x906ea    | 8        | 4.79%   |
| 0x906e9    | 7        | 4.19%   |
| 0x306f2    | 5        | 2.99%   |
| 0x1067a    | 5        | 2.99%   |
| 0x906ed    | 4        | 2.4%    |
| 0x506e3    | 4        | 2.4%    |
| 0x206a7    | 4        | 2.4%    |
| 0x106e5    | 4        | 2.4%    |
| 0x0800820d | 4        | 2.4%    |
| 0x08001138 | 4        | 2.4%    |
| 0x08001137 | 4        | 2.4%    |
| 0xa0655    | 3        | 1.8%    |
| 0x6fb      | 3        | 1.8%    |
| 0x08101016 | 3        | 1.8%    |
| 0xb0671    | 2        | 1.2%    |
| 0x906ec    | 2        | 1.2%    |
| 0x90672    | 2        | 1.2%    |
| 0x806e9    | 2        | 1.2%    |
| 0x50654    | 2        | 1.2%    |
| 0x08701021 | 2        | 1.2%    |
| 0x08600106 | 2        | 1.2%    |
| 0x0810100b | 2        | 1.2%    |
| 0xf49      | 1        | 0.6%    |
| 0xa0671    | 1        | 0.6%    |
| 0x90675    | 1        | 0.6%    |
| 0x406f1    | 1        | 0.6%    |
| 0x306e4    | 1        | 0.6%    |
| 0x306d4    | 1        | 0.6%    |
| 0x30678    | 1        | 0.6%    |
| 0x0a50000d | 1        | 0.6%    |
| 0x0a50000c | 1        | 0.6%    |
| 0x0a20120a | 1        | 0.6%    |
| 0x0a201016 | 1        | 0.6%    |
| 0x0a201009 | 1        | 0.6%    |
| 0x08701013 | 1        | 0.6%    |
| 0x08301055 | 1        | 0.6%    |
| 0x08301025 | 1        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 25       | 15.15%  |
| Haswell          | 22       | 13.33%  |
| IvyBridge        | 18       | 10.91%  |
| Zen              | 17       | 10.3%   |
| Skylake          | 10       | 6.06%   |
| Penryn           | 8        | 4.85%   |
| Zen+             | 7        | 4.24%   |
| Zen 3            | 7        | 4.24%   |
| Zen 2            | 7        | 4.24%   |
| Unknown          | 6        | 3.64%   |
| CometLake        | 5        | 3.03%   |
| SandyBridge      | 4        | 2.42%   |
| Nehalem          | 4        | 2.42%   |
| Core             | 4        | 2.42%   |
| Alderlake Hybrid | 4        | 2.42%   |
| K10              | 3        | 1.82%   |
| Steamroller      | 2        | 1.21%   |
| Silvermont       | 2        | 1.21%   |
| Piledriver       | 2        | 1.21%   |
| NetBurst         | 2        | 1.21%   |
| Broadwell        | 2        | 1.21%   |
| Westmere         | 1        | 0.61%   |
| K8 Hammer        | 1        | 0.61%   |
| K10 Llano        | 1        | 0.61%   |
| Icelake          | 1        | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 86       | 46.99%  |
| Intel                      | 59       | 32.24%  |
| AMD                        | 36       | 19.67%  |
| Matrox Electronics Systems | 1        | 0.55%   |
| ASPEED Technology          | 1        | 0.55%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 5.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 5.35%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 4.28%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 3.74%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 3.21%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.14%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 2.14%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.14%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.6%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3        | 1.6%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.6%    |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 1.6%    |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 1.6%    |
| Intel HD Graphics 510                                                       | 3        | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 3        | 1.6%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 1.07%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.07%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.07%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 1.07%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 1.07%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.07%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 1.07%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 1.07%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 2        | 1.07%   |
| Nvidia G98 [GeForce 9300 GS]                                                | 2        | 1.07%   |
| Intel Raptor Lake-S GT1 [UHD Graphics 770]                                  | 2        | 1.07%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2        | 1.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.07%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 1.07%   |
| AMD Renoir                                                                  | 2        | 1.07%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 2        | 1.07%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.07%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.53%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| 1 x Nvidia      | 79       | 47.59%  |
| 1 x Intel       | 45       | 27.11%  |
| 1 x AMD         | 31       | 18.67%  |
| Intel + Nvidia  | 3        | 1.81%   |
| 2 x AMD         | 2        | 1.2%    |
| AMD + Nvidia    | 2        | 1.2%    |
| 2 x Nvidia      | 1        | 0.6%    |
| Nvidia + Matrox | 1        | 0.6%    |
| Intel + AMD     | 1        | 0.6%    |
| 1 x ASPEED      | 1        | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 110      | 66.27%  |
| Proprietary | 51       | 30.72%  |
| Unknown     | 5        | 3.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 71       | 42.26%  |
| 0.51-1.0   | 24       | 14.29%  |
| 1.01-2.0   | 22       | 13.1%   |
| 0.01-0.5   | 11       | 6.55%   |
| 7.01-8.0   | 10       | 5.95%   |
| 3.01-4.0   | 9        | 5.36%   |
| 8.01-16.0  | 7        | 4.17%   |
| 5.01-6.0   | 5        | 2.98%   |
| 2.01-3.0   | 4        | 2.38%   |
| 16.01-24.0 | 4        | 2.38%   |
| 4.01-5.0   | 1        | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 34       | 21.94%  |
| Samsung Electronics  | 30       | 19.35%  |
| Unknown              | 10       | 6.45%   |
| Dell                 | 8        | 5.16%   |
| Philips              | 6        | 3.87%   |
| LG Electronics       | 6        | 3.87%   |
| OUT                  | 5        | 3.23%   |
| Hewlett-Packard      | 5        | 3.23%   |
| AOC                  | 5        | 3.23%   |
| PRISM+               | 4        | 2.58%   |
| BenQ                 | 3        | 1.94%   |
| Unknown (ADE)        | 2        | 1.29%   |
| OOO                  | 2        | 1.29%   |
| MStar                | 2        | 1.29%   |
| Lenovo               | 2        | 1.29%   |
| JRY                  | 2        | 1.29%   |
| Ancor Communications | 2        | 1.29%   |
| Yamaha               | 1        | 0.65%   |
| UPV                  | 1        | 0.65%   |
| TopView              | 1        | 0.65%   |
| TGL                  | 1        | 0.65%   |
| SiS                  | 1        | 0.65%   |
| SGT                  | 1        | 0.65%   |
| SANYO                | 1        | 0.65%   |
| RTK                  | 1        | 0.65%   |
| RAT                  | 1        | 0.65%   |
| PBK                  | 1        | 0.65%   |
| ORM                  | 1        | 0.65%   |
| NME                  | 1        | 0.65%   |
| MON                  | 1        | 0.65%   |
| Microstep            | 1        | 0.65%   |
| LYC                  | 1        | 0.65%   |
| KVM                  | 1        | 0.65%   |
| JCH                  | 1        | 0.65%   |
| ITE                  | 1        | 0.65%   |
| HXM                  | 1        | 0.65%   |
| HVT                  | 1        | 0.65%   |
| DPL                  | 1        | 0.65%   |
| Denver               | 1        | 0.65%   |
| CVT                  | 1        | 0.65%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 5        | 3.07%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                          | 3        | 1.84%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 1.84%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1872x1053mm 84.6-inch | 2        | 1.23%   |
| PRISM+ ULTRON 3547UC INN0035 2560x1080 820x345mm 35.0-inch              | 2        | 1.23%   |
| OOO 15.6' monitor OOO0001 1920x1080 409x230mm 18.5-inch                 | 2        | 1.23%   |
| JRY Digital JRY0215 1920x1080 368x207mm 16.6-inch                       | 2        | 1.23%   |
| Yamaha YSP-1600 YMH331A 1920x540                                        | 1        | 0.61%   |
| UPV UP-M30W1 UPV0001 2560x1600 641x401mm 29.8-inch                      | 1        | 0.61%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                              | 1        | 0.61%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                      | 1        | 0.61%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                   | 1        | 0.61%   |
| Unknown LCD Monitor OUT Digital 3200x1080                               | 1        | 0.61%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                       | 1        | 0.61%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                           | 1        | 0.61%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                         | 1        | 0.61%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                            | 1        | 0.61%   |
| Unknown LCD Monitor Digital Projection Limited DP                       | 1        | 0.61%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                              | 1        | 0.61%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                          | 1        | 0.61%   |
| Unknown (ADE) TLED20DHS ADE2000 1600x900 443x249mm 20.0-inch            | 1        | 0.61%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch       | 1        | 0.61%   |
| TopView TOPSYNC TOP049B 2560x1440 597x336mm 27.0-inch                   | 1        | 0.61%   |
| TGL TGL A190 TGL0908 1280x1024 376x301mm 19.0-inch                      | 1        | 0.61%   |
| SiS DV 24 TV SIS0330 1920x1080 930x530mm 42.1-inch                      | 1        | 0.61%   |
| SGT HS156PC SGT1560 1920x1080 345x194mm 15.6-inch                       | 1        | 0.61%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch                 | 1        | 0.61%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch    | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM04AE 1680x1050 459x296mm 21.5-inch    | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM03F3 1920x1200 518x324mm 24.1-inch    | 1        | 0.61%   |
| Samsung Electronics SyncMaster SAM0384 1280x1024 376x301mm 19.0-inch    | 1        | 0.61%   |
| Samsung Electronics SMART TV SAM7129 3840x2160 1210x680mm 54.6-inch     | 1        | 0.61%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch       | 1        | 0.61%   |
| Samsung Electronics S32E511 SAM0D11 1920x1080 698x392mm 31.5-inch       | 1        | 0.61%   |
| Samsung Electronics S27D850 SAM0BC7 2560x1440 598x336mm 27.0-inch       | 1        | 0.61%   |
| Samsung Electronics S27B240 SAM08EA 1920x1080 598x336mm 27.0-inch       | 1        | 0.61%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1        | 0.61%   |
| Samsung Electronics S24D300 SAM0B44 1920x1080 521x293mm 23.5-inch       | 1        | 0.61%   |
| Samsung Electronics S24B300 SAM08CC 1920x1080 521x293mm 23.5-inch       | 1        | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 79       | 50.64%  |
| 3840x2160 (4K)     | 16       | 10.26%  |
| 2560x1440 (QHD)    | 13       | 8.33%   |
| 1280x1024 (SXGA)   | 11       | 7.05%   |
| 1920x1200 (WUXGA)  | 7        | 4.49%   |
| 1680x1050 (WSXGA+) | 6        | 3.85%   |
| 3440x1440          | 4        | 2.56%   |
| 2560x1080          | 4        | 2.56%   |
| Unknown            | 3        | 1.92%   |
| 3840x1080          | 2        | 1.28%   |
| 1600x900 (HD+)     | 2        | 1.28%   |
| 1440x900 (WXGA+)   | 2        | 1.28%   |
| 4880x2560          | 1        | 0.64%   |
| 3840x1600          | 1        | 0.64%   |
| 3286x1080          | 1        | 0.64%   |
| 3200x1080          | 1        | 0.64%   |
| 2560x1600          | 1        | 0.64%   |
| 1920x540           | 1        | 0.64%   |
| 1600x1200          | 1        | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 31       | 20.26%  |
| 27      | 24       | 15.69%  |
| 21      | 18       | 11.76%  |
| 23      | 15       | 9.8%    |
| 24      | 11       | 7.19%   |
| 16      | 9        | 5.88%   |
| 19      | 7        | 4.58%   |
| 31      | 5        | 3.27%   |
| 34      | 4        | 2.61%   |
| 20      | 4        | 2.61%   |
| 84      | 3        | 1.96%   |
| 18      | 3        | 1.96%   |
| 40      | 2        | 1.31%   |
| 35      | 2        | 1.31%   |
| 29      | 2        | 1.31%   |
| 25      | 2        | 1.31%   |
| 22      | 2        | 1.31%   |
| 17      | 2        | 1.31%   |
| 49      | 1        | 0.65%   |
| 48      | 1        | 0.65%   |
| 46      | 1        | 0.65%   |
| 42      | 1        | 0.65%   |
| 39      | 1        | 0.65%   |
| 37      | 1        | 0.65%   |
| 33      | 1        | 0.65%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 48       | 32%     |
| Unknown     | 31       | 20.67%  |
| 401-500     | 27       | 18%     |
| 351-400     | 10       | 6.67%   |
| 601-700     | 8        | 5.33%   |
| 301-350     | 8        | 5.33%   |
| 801-900     | 6        | 4%      |
| 701-800     | 5        | 3.33%   |
| 1501-2000   | 3        | 2%      |
| 1001-1500   | 3        | 2%      |
| 901-1000    | 1        | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 83       | 54.97%  |
| Unknown | 28       | 18.54%  |
| 16/10   | 11       | 7.28%   |
| 5/4     | 8        | 5.3%    |
| 4/3     | 8        | 5.3%    |
| 21/9    | 8        | 5.3%    |
| 32/9    | 3        | 1.99%   |
| 6/5     | 1        | 0.66%   |
| 3/2     | 1        | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 39       | 25.83%  |
| Unknown        | 31       | 20.53%  |
| 301-350        | 25       | 16.56%  |
| 351-500        | 14       | 9.27%   |
| 151-200        | 13       | 8.61%   |
| 251-300        | 7        | 4.64%   |
| 501-1000       | 7        | 4.64%   |
| 131-140        | 6        | 3.97%   |
| More than 1000 | 3        | 1.99%   |
| 141-150        | 3        | 1.99%   |
| 111-120        | 3        | 1.99%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 69       | 46.31%  |
| 101-120 | 33       | 22.15%  |
| Unknown | 31       | 20.81%  |
| 121-160 | 12       | 8.05%   |
| 1-50    | 2        | 1.34%   |
| 161-240 | 2        | 1.34%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 136      | 82.42%  |
| 2     | 17       | 10.3%   |
| 0     | 12       | 7.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 118      | 55.92%  |
| Intel                    | 59       | 27.96%  |
| Qualcomm Atheros         | 7        | 3.32%   |
| Broadcom                 | 5        | 2.37%   |
| Ralink Technology        | 4        | 1.9%    |
| Ralink                   | 3        | 1.42%   |
| MediaTek                 | 2        | 0.95%   |
| Marvell Technology Group | 2        | 0.95%   |
| Exar                     | 2        | 0.95%   |
| ASIX Electronics         | 2        | 0.95%   |
| Wilocity                 | 1        | 0.47%   |
| PEAK-System Technik      | 1        | 0.47%   |
| Kinesis                  | 1        | 0.47%   |
| D-Link                   | 1        | 0.47%   |
| Broadcom Limited         | 1        | 0.47%   |
| Aquantia                 | 1        | 0.47%   |
| American Megatrends      | 1        | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101      | 39.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 8        | 3.16%   |
| Intel Wi-Fi 6 AX200                                               | 8        | 3.16%   |
| Intel I211 Gigabit Network Connection                             | 8        | 3.16%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.37%   |
| Intel Ethernet Controller I225-V                                  | 5        | 1.98%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 1.98%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 1.19%   |
| Realtek 802.11ac NIC                                              | 3        | 1.19%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.19%   |
| Intel Ethernet Controller X550                                    | 3        | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.19%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3        | 1.19%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.19%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 3        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.79%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.79%   |
| Realtek 802.11n NIC                                               | 2        | 0.79%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.79%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.79%   |
| Intel Wireless 3165                                               | 2        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.79%   |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.79%   |
| Intel Ethernet Connection (11) I219-V                             | 2        | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.79%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.79%   |
| Exar XR21V1410 USB-UART IC                                        | 2        | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2        | 0.79%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 27       | 43.55%  |
| Realtek Semiconductor | 20       | 32.26%  |
| Ralink Technology     | 4        | 6.45%   |
| Ralink                | 3        | 4.84%   |
| Qualcomm Atheros      | 2        | 3.23%   |
| MediaTek              | 2        | 3.23%   |
| Broadcom              | 2        | 3.23%   |
| Wilocity              | 1        | 1.61%   |
| D-Link                | 1        | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 8        | 12.9%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 4.84%   |
| Realtek 802.11ac NIC                                                   | 3        | 4.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 3        | 4.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 4.84%   |
| Intel 700 Series Chipset Family Wi-Fi                                  | 3        | 4.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 3.23%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 3.23%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 3.23%   |
| Realtek 802.11n NIC                                                    | 2        | 3.23%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 3.23%   |
| Intel Wireless 3165                                                    | 2        | 3.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 3.23%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 3.23%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1        | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.61%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.61%   |
| Ralink RT5572 Wireless Adapter                                         | 1        | 1.61%   |
| Ralink RT5372 Wireless Adapter                                         | 1        | 1.61%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                              | 1        | 1.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.61%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                   | 1        | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.61%   |
| MediaTek WiFi                                                          | 1        | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.61%   |
| Intel Wireless-AC 9260                                                 | 1        | 1.61%   |
| Intel Wireless 8265 / 8275                                             | 1        | 1.61%   |
| Intel Wireless 7265                                                    | 1        | 1.61%   |
| Intel Wireless 3160                                                    | 1        | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 1.61%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU] | 1        | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 114      | 64.41%  |
| Intel                    | 48       | 27.12%  |
| Qualcomm Atheros         | 5        | 2.82%   |
| Broadcom                 | 3        | 1.69%   |
| Marvell Technology Group | 2        | 1.13%   |
| ASIX Electronics         | 2        | 1.13%   |
| Broadcom Limited         | 1        | 0.56%   |
| Aquantia                 | 1        | 0.56%   |
| American Megatrends      | 1        | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller     | 101      | 54.01%  |
| Realtek RTL8125 2.5GbE Controller                                     | 8        | 4.28%   |
| Intel I211 Gigabit Network Connection                                 | 8        | 4.28%   |
| Intel Ethernet Connection (7) I219-V                                  | 6        | 3.21%   |
| Intel Ethernet Controller I225-V                                      | 5        | 2.67%   |
| Intel Ethernet Connection (2) I219-V                                  | 5        | 2.67%   |
| Intel I210 Gigabit Network Connection                                 | 3        | 1.6%    |
| Intel Ethernet Controller X550                                        | 3        | 1.6%    |
| Intel Ethernet Connection I217-LM                                     | 3        | 1.6%    |
| Intel Ethernet Connection (2) I218-V                                  | 3        | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                 | 3        | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                              | 2        | 1.07%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                         | 2        | 1.07%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                 | 2        | 1.07%   |
| Intel Ethernet Connection (2) I219-LM                                 | 2        | 1.07%   |
| Intel Ethernet Connection (2) I218-LM                                 | 2        | 1.07%   |
| Intel Ethernet Connection (11) I219-V                                 | 2        | 1.07%   |
| Intel 82579V Gigabit Network Connection                               | 2        | 1.07%   |
| Intel 82574L Gigabit Network Connection                               | 2        | 1.07%   |
| ASIX AX88179 Gigabit Ethernet                                         | 2        | 1.07%   |
| Realtek RTL8152 Fast Ethernet Adapter                                 | 1        | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                 | 1        | 0.53%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                            | 1        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                 | 1        | 0.53%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                            | 1        | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller               | 1        | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller               | 1        | 0.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                     | 1        | 0.53%   |
| Intel Ethernet Controller I226-V                                      | 1        | 0.53%   |
| Intel Ethernet Connection I217-V                                      | 1        | 0.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                  | 1        | 0.53%   |
| Intel 82576 Gigabit Network Connection                                | 1        | 0.53%   |
| Intel 82575EB Gigabit Network Connection                              | 1        | 0.53%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                  | 1        | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                      | 1        | 0.53%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                       | 1        | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                       | 1        | 0.53%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express       | 1        | 0.53%   |
| Broadcom BCM57416 NetXtreme-E Dual-Media 10G RDMA Ethernet Controller | 1        | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]     | 1        | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 164      | 72.25%  |
| WiFi     | 59       | 25.99%  |
| Modem    | 3        | 1.32%   |
| Unknown  | 1        | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 84.3%   |
| WiFi     | 27       | 15.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 108      | 65.45%  |
| 2     | 48       | 29.09%  |
| 3     | 7        | 4.24%   |
| 5     | 1        | 0.61%   |
| 4     | 1        | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 165      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 26       | 39.39%  |
| Intel                   | 25       | 37.88%  |
| Realtek Semiconductor   | 6        | 9.09%   |
| Broadcom                | 3        | 4.55%   |
| ASUSTek Computer        | 3        | 4.55%   |
| TP-Link                 | 1        | 1.52%   |
| IMC Networks            | 1        | 1.52%   |
| Foxconn / Hon Hai       | 1        | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 26       | 39.39%  |
| Intel AX200 Bluetooth                                 | 7        | 10.61%  |
| Realtek Bluetooth Radio                               | 6        | 9.09%   |
| Intel Bluetooth wireless interface                    | 5        | 7.58%   |
| Intel Bluetooth Device                                | 4        | 6.06%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 4.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 4.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 3.03%   |
| Intel AX201 Bluetooth                                 | 2        | 3.03%   |
| TP-Link UB500 Adapter                                 | 1        | 1.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.52%   |
| Intel AX210 Bluetooth                                 | 1        | 1.52%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.52%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.52%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.52%   |
| ASUS Bluetooth Radio                                  | 1        | 1.52%   |
| ASUS Bluetooth Device                                 | 1        | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 113      | 41.54%  |
| Nvidia                               | 81       | 29.78%  |
| AMD                                  | 58       | 21.32%  |
| C-Media Electronics                  | 5        | 1.84%   |
| Giga-Byte Technology                 | 2        | 0.74%   |
| ASUSTek Computer                     | 2        | 0.74%   |
| Thesycon Systemsoftware & Consulting | 1        | 0.37%   |
| Texas Instruments                    | 1        | 0.37%   |
| Sony                                 | 1        | 0.37%   |
| Micro Star International             | 1        | 0.37%   |
| Medeli Electronics                   | 1        | 0.37%   |
| JMTek                                | 1        | 0.37%   |
| Generalplus Technology               | 1        | 0.37%   |
| Fry's Electronics                    | 1        | 0.37%   |
| EGO SYStems                          | 1        | 0.37%   |
| DigiTech                             | 1        | 0.37%   |
| BEHRINGER International              | 1        | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15       | 4.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 3.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12       | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 3.54%   |
| Intel 200 Series PCH HD Audio                                              | 11       | 3.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10       | 3.22%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 3.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 3.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 2.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9        | 2.89%   |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 2.25%   |
| Nvidia GA102 High Definition Audio Controller                              | 7        | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.25%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 6        | 1.93%   |
| Intel Alder Lake-S HD Audio Controller                                     | 6        | 1.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.61%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.29%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.29%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 4        | 1.29%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.29%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 0.96%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 0.96%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 0.96%   |
| Nvidia GF106 High Definition Audio Controller                              | 3        | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 2        | 0.64%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.64%   |
| Nvidia GP108 High Definition Audio Controller                              | 2        | 0.64%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.64%   |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 54       | 69.23%  |
| Unknown             | 5        | 6.41%   |
| SK hynix            | 5        | 6.41%   |
| Team                | 3        | 3.85%   |
| Kingston            | 3        | 3.85%   |
| KLEVV               | 2        | 2.56%   |
| G.Skill             | 2        | 2.56%   |
| Imation             | 1        | 1.28%   |
| GeIL                | 1        | 1.28%   |
| Crucial             | 1        | 1.28%   |
| Corsair             | 1        | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 6        | 6.67%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 5        | 5.56%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 3200MT/s    | 5        | 5.56%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s     | 4        | 4.44%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s     | 3        | 3.33%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 3.33%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 3.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 2        | 2.22%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 2        | 2.22%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 2        | 2.22%   |
| Samsung RAM M378B1G73DB0-CK0 8192MB DIMM DDR3 2133MT/s  | 2        | 2.22%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s    | 2        | 2.22%   |
| Samsung RAM M378A2K43BB1-CRC 16GB DIMM DDR4 3200MT/s    | 2        | 2.22%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s     | 2        | 2.22%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s     | 2        | 2.22%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 1.11%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 1        | 1.11%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s      | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2933MT/s   | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s      | 1        | 1.11%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s      | 1        | 1.11%   |
| SK hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s | 1        | 1.11%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s    | 1        | 1.11%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 1.11%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s | 1        | 1.11%   |
| SK hynix RAM HMA42GR7MFR4N-TF 16GB DIMM DDR4 2133MT/s   | 1        | 1.11%   |
| SK hynix RAM HMA42GR7AFR4N-TF 16GB DIMM DDR4 2133MT/s   | 1        | 1.11%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s              | 1        | 1.11%   |
| Samsung RAM Module 16GB DIMM DDR4 2400MT/s              | 1        | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.11%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s  | 1        | 1.11%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |
| Samsung RAM M386A8K40CM2-CTD 64GB DIMM DDR4 2666MT/s    | 1        | 1.11%   |
| Samsung RAM M378B5673GB0-CH9 2GB DIMM 1333MT/s          | 1        | 1.11%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 1        | 1.11%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 1.11%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2400MT/s     | 1        | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 48       | 64%     |
| DDR3    | 21       | 28%     |
| Unknown | 3        | 4%      |
| SDRAM   | 2        | 2.67%   |
| DDR5    | 1        | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 73       | 97.33%  |
| SODIMM | 2        | 2.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 28.05%  |
| 4096  | 22       | 26.83%  |
| 16384 | 21       | 25.61%  |
| 32768 | 11       | 13.41%  |
| 2048  | 3        | 3.66%   |
| 65536 | 1        | 1.22%   |
| 1024  | 1        | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 17       | 19.77%  |
| 1600    | 14       | 16.28%  |
| 3500    | 6        | 6.98%   |
| 2133    | 6        | 6.98%   |
| 2667    | 5        | 5.81%   |
| 2400    | 5        | 5.81%   |
| 3066    | 4        | 4.65%   |
| 3466    | 3        | 3.49%   |
| 2933    | 3        | 3.49%   |
| 1866    | 3        | 3.49%   |
| 1800    | 3        | 3.49%   |
| 4800    | 2        | 2.33%   |
| 3400    | 2        | 2.33%   |
| 3266    | 2        | 2.33%   |
| 2666    | 2        | 2.33%   |
| 1867    | 2        | 2.33%   |
| 1333    | 2        | 2.33%   |
| Unknown | 2        | 2.33%   |
| 4802    | 1        | 1.16%   |
| 3866    | 1        | 1.16%   |
| 3000    | 1        | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 4        | 57.14%  |
| Seiko Epson         | 1        | 14.29%  |
| Samsung Electronics | 1        | 14.29%  |
| Brother Industries  | 1        | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Seiko Epson L220 Series | 1        | 14.29%  |
| Samsung CLX-3180 Series | 1        | 14.29%  |
| Canon PIXMA MP280       | 1        | 14.29%  |
| Canon MF4800 Series     | 1        | 14.29%  |
| Canon G4010 series      | 1        | 14.29%  |
| Canon E560 series       | 1        | 14.29%  |
| Brother DCP-T310        | 1        | 14.29%  |

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
| Sunplus Innovation Technology | 4        | 28.57%  |
| Logitech                      | 3        | 21.43%  |
| Samsung Electronics           | 2        | 14.29%  |
| lihappe8                      | 2        | 14.29%  |
| Z-Star Microelectronics       | 1        | 7.14%   |
| Microdia                      | 1        | 7.14%   |
| LG Electronics                | 1        | 7.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Sunplus WEMISS CM-A1                                  | 2        | 14.29%  |
| Samsung Galaxy A5 (MTP)                               | 2        | 14.29%  |
| lihappe8 USB 2.0 Camera                               | 2        | 14.29%  |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 7.14%   |
| Sunplus UHD4K                                         | 1        | 7.14%   |
| Sunplus ABKO APC930 QHD WEBCAM                        | 1        | 7.14%   |
| Microdia Lenovo EasyCamera                            | 1        | 7.14%   |
| Logitech Webcam C110                                  | 1        | 7.14%   |
| Logitech StreamCam                                    | 1        | 7.14%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 7.14%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 7.14%   |

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
| 0     | 137      | 83.03%  |
| 1     | 22       | 13.33%  |
| 3     | 3        | 1.82%   |
| 2     | 2        | 1.21%   |
| 5     | 1        | 0.61%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 10       | 29.41%  |
| Unassigned class         | 8        | 23.53%  |
| Net/wireless             | 7        | 20.59%  |
| Net/ethernet             | 3        | 8.82%   |
| Communication controller | 3        | 8.82%   |
| Camera                   | 2        | 5.88%   |
| Network                  | 1        | 2.94%   |

