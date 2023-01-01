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

Total: 191

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 36       | 23.84%  |
| Ubuntu 18.04                 | 20       | 13.25%  |
| Ubuntu 22.04                 | 11       | 7.28%   |
| Ubuntu 20.10                 | 4        | 2.65%   |
| Arch                         | 4        | 2.65%   |
| Ubuntu 19.10                 | 3        | 1.99%   |
| Ubuntu 16.04                 | 3        | 1.99%   |
| Fedora 32                    | 3        | 1.99%   |
| CentOS 7                     | 3        | 1.99%   |
| Zorin 15                     | 2        | 1.32%   |
| Ubuntu Unity 16.04           | 2        | 1.32%   |
| Ubuntu 21.10                 | 2        | 1.32%   |
| RHEL 8                       | 2        | 1.32%   |
| openSUSE Tumbleweed-XXXXXXXX | 2        | 1.32%   |
| OpenMandriva 4.3             | 2        | 1.32%   |
| No1 2018                     | 2        | 1.32%   |
| Linux Mint 20.2              | 2        | 1.32%   |
| Linux Mint 20.1              | 2        | 1.32%   |
| Linux Mint 20                | 2        | 1.32%   |
| Linux Mint 19.3              | 2        | 1.32%   |
| Fedora 34                    | 2        | 1.32%   |
| Debian 10                    | 2        | 1.32%   |
| Chrome OS                    | 2        | 1.32%   |
| Zorin 16                     | 1        | 0.66%   |
| Ubuntu 19.04                 | 1        | 0.66%   |
| Ubuntu 18.10                 | 1        | 0.66%   |
| Ubuntu 17.10                 | 1        | 0.66%   |
| Ubuntu                       | 1        | 0.66%   |
| TmaxOS 21.12.02              | 1        | 0.66%   |
| ROSA R10                     | 1        | 0.66%   |
| Rocky Linux 8.6              | 1        | 0.66%   |
| Pop!_OS 22.04                | 1        | 0.66%   |
| Pop!_OS 20.04                | 1        | 0.66%   |
| OpenMandriva 4.50            | 1        | 0.66%   |
| OpenMandriva 4.2             | 1        | 0.66%   |
| Nobara 36                    | 1        | 0.66%   |
| No1 2020 te                  | 1        | 0.66%   |
| Manjaro 20.2.1               | 1        | 0.66%   |
| Lubuntu 18.04                | 1        | 0.66%   |
| Linux Mint 21                | 1        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 83       | 55.7%   |
| Fedora       | 9        | 6.04%   |
| Linux Mint   | 8        | 5.37%   |
| Arch         | 5        | 3.36%   |
| OpenMandriva | 4        | 2.68%   |
| CentOS       | 4        | 2.68%   |
| Zorin        | 3        | 2.01%   |
| HamoniKR     | 3        | 2.01%   |
| Debian       | 3        | 2.01%   |
| Ubuntu Unity | 2        | 1.34%   |
| RHEL         | 2        | 1.34%   |
| Pop!_OS      | 2        | 1.34%   |
| openSUSE     | 2        | 1.34%   |
| No1          | 2        | 1.34%   |
| Kubuntu      | 2        | 1.34%   |
| Chrome OS    | 2        | 1.34%   |
| TmaxOS       | 1        | 0.67%   |
| ROSA         | 1        | 0.67%   |
| Rocky Linux  | 1        | 0.67%   |
| Nobara       | 1        | 0.67%   |
| Manjaro      | 1        | 0.67%   |
| Lubuntu      | 1        | 0.67%   |
| KDE neon     | 1        | 0.67%   |
| Gooroom      | 1        | 0.67%   |
| Endless      | 1        | 0.67%   |
| EndeavourOS  | 1        | 0.67%   |
| Devuan       | 1        | 0.67%   |
| BlackPanther | 1        | 0.67%   |
| ArcoLinux    | 1        | 0.67%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.0-29-generic          | 4        | 2.5%    |
| 5.4.0-26-generic          | 3        | 1.88%   |
| 5.15.0-43-generic         | 3        | 1.88%   |
| 5.15.0-41-generic         | 3        | 1.88%   |
| 5.8.0-48-generic          | 2        | 1.25%   |
| 5.8.0-38-generic          | 2        | 1.25%   |
| 5.4.0-56-generic          | 2        | 1.25%   |
| 5.4.0-54-generic          | 2        | 1.25%   |
| 5.4.0-52-generic          | 2        | 1.25%   |
| 5.4.0-47-generic          | 2        | 1.25%   |
| 5.4.0-42-generic          | 2        | 1.25%   |
| 5.4.0-37-generic          | 2        | 1.25%   |
| 5.3.0-51-generic          | 2        | 1.25%   |
| 5.3.0-40-generic          | 2        | 1.25%   |
| 5.16.7-desktop-1omv4003   | 2        | 1.25%   |
| 5.15.0-53-generic         | 2        | 1.25%   |
| 5.15.0-52-generic         | 2        | 1.25%   |
| 5.15.0-50-generic         | 2        | 1.25%   |
| 5.13.0-21-generic         | 2        | 1.25%   |
| 4.19.0-14-amd64           | 2        | 1.25%   |
| 4.18.0-25-generic         | 2        | 1.25%   |
| 4.15.0-91-generic         | 2        | 1.25%   |
| 6.0.12-300.fc37.x86_64    | 1        | 0.63%   |
| 6.0.1-arch1-1             | 1        | 0.63%   |
| 5.9.0-12.1-liquorix-amd64 | 1        | 0.63%   |
| 5.8.5-no1linux1           | 1        | 0.63%   |
| 5.8.16-300.fc33.x86_64    | 1        | 0.63%   |
| 5.8.10-200.fc32.x86_64    | 1        | 0.63%   |
| 5.8.0-59-generic          | 1        | 0.63%   |
| 5.8.0-55-generic          | 1        | 0.63%   |
| 5.8.0-50-generic          | 1        | 0.63%   |
| 5.8.0-44-generic          | 1        | 0.63%   |
| 5.8.0-41-generic          | 1        | 0.63%   |
| 5.8.0-33-generic          | 1        | 0.63%   |
| 5.8.0-32-generic          | 1        | 0.63%   |
| 5.8.0-26-generic          | 1        | 0.63%   |
| 5.8.0-1.el7.elrepo.x86_64 | 1        | 0.63%   |
| 5.7.16-200.fc32.x86_64    | 1        | 0.63%   |
| 5.6.6-arch1-1             | 1        | 0.63%   |
| 5.6.12-300.fc32.x86_64    | 1        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 33       | 21.43%  |
| 4.15.0  | 18       | 11.69%  |
| 5.15.0  | 15       | 9.74%   |
| 5.8.0   | 13       | 8.44%   |
| 4.18.0  | 10       | 6.49%   |
| 5.3.0   | 9        | 5.84%   |
| 5.13.0  | 5        | 3.25%   |
| 5.0.0   | 3        | 1.95%   |
| 4.19.0  | 3        | 1.95%   |
| 5.16.7  | 2        | 1.3%    |
| 5.14.0  | 2        | 1.3%    |
| 5.11.0  | 2        | 1.3%    |
| 4.13.0  | 2        | 1.3%    |
| 3.10.0  | 2        | 1.3%    |
| 6.0.12  | 1        | 0.65%   |
| 6.0.1   | 1        | 0.65%   |
| 5.9.0   | 1        | 0.65%   |
| 5.8.5   | 1        | 0.65%   |
| 5.8.16  | 1        | 0.65%   |
| 5.8.10  | 1        | 0.65%   |
| 5.7.16  | 1        | 0.65%   |
| 5.6.6   | 1        | 0.65%   |
| 5.6.12  | 1        | 0.65%   |
| 5.4.25  | 1        | 0.65%   |
| 5.4.2   | 1        | 0.65%   |
| 5.19.3  | 1        | 0.65%   |
| 5.18.9  | 1        | 0.65%   |
| 5.18.13 | 1        | 0.65%   |
| 5.18.10 | 1        | 0.65%   |
| 5.16.19 | 1        | 0.65%   |
| 5.16.1  | 1        | 0.65%   |
| 5.15.8  | 1        | 0.65%   |
| 5.15.38 | 1        | 0.65%   |
| 5.14.6  | 1        | 0.65%   |
| 5.14.2  | 1        | 0.65%   |
| 5.12.4  | 1        | 0.65%   |
| 5.11.8  | 1        | 0.65%   |
| 5.11.12 | 1        | 0.65%   |
| 5.10.4  | 1        | 0.65%   |
| 5.10.15 | 1        | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 35       | 22.88%  |
| 4.15    | 19       | 12.42%  |
| 5.15    | 17       | 11.11%  |
| 5.8     | 16       | 10.46%  |
| 4.18    | 11       | 7.19%   |
| 5.3     | 9        | 5.88%   |
| 5.13    | 5        | 3.27%   |
| 5.16    | 4        | 2.61%   |
| 5.14    | 4        | 2.61%   |
| 5.11    | 4        | 2.61%   |
| 5.10    | 4        | 2.61%   |
| 5.0     | 4        | 2.61%   |
| 4.19    | 4        | 2.61%   |
| 6.0     | 2        | 1.31%   |
| 5.6     | 2        | 1.31%   |
| 5.18    | 2        | 1.31%   |
| 4.9     | 2        | 1.31%   |
| 4.13    | 2        | 1.31%   |
| 3.10    | 2        | 1.31%   |
| 5.9     | 1        | 0.65%   |
| 5.7     | 1        | 0.65%   |
| 5.19    | 1        | 0.65%   |
| 5.12    | 1        | 0.65%   |
| 4.17    | 1        | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 145      | 99.32%  |
| i686   | 1        | 0.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 74       | 50.34%  |
| Unknown         | 33       | 22.45%  |
| KDE5            | 15       | 10.2%   |
| X-Cinnamon      | 8        | 5.44%   |
| XFCE            | 6        | 4.08%   |
| Unity           | 2        | 1.36%   |
| KDE             | 2        | 1.36%   |
| Cinnamon        | 2        | 1.36%   |
| TOS:GNOME       | 1        | 0.68%   |
| LXDE            | 1        | 0.68%   |
| KDE4            | 1        | 0.68%   |
| GNOME Flashback | 1        | 0.68%   |
| GNOME Classic   | 1        | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 102      | 69.86%  |
| Unknown | 20       | 13.7%   |
| Wayland | 17       | 11.64%  |
| Tty     | 7        | 4.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 93       | 63.27%  |
| GDM     | 16       | 10.88%  |
| SDDM    | 15       | 10.2%   |
| GDM3    | 14       | 9.52%   |
| LightDM | 5        | 3.4%    |
| TDM     | 3        | 2.04%   |
| SLiM    | 1        | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ko_KR   | 60       | 40.82%  |
| en_US   | 53       | 36.05%  |
| Unknown | 28       | 19.05%  |
| ru_RU   | 1        | 0.68%   |
| id_ID   | 1        | 0.68%   |
| fr_FR   | 1        | 0.68%   |
| en_GB   | 1        | 0.68%   |
| en_AU   | 1        | 0.68%   |
| C       | 1        | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 74       | 50.34%  |
| EFI  | 73       | 49.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 121      | 81.76%  |
| Unknown | 9        | 6.08%   |
| Btrfs   | 7        | 4.73%   |
| Xfs     | 5        | 3.38%   |
| Zfs     | 3        | 2.03%   |
| Overlay | 3        | 2.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 92       | 62.16%  |
| GPT     | 45       | 30.41%  |
| MBR     | 11       | 7.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 120      | 81.63%  |
| Yes       | 27       | 18.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 67.81%  |
| Yes       | 47       | 32.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 34       | 23.29%  |
| Gigabyte Technology | 33       | 22.6%   |
| ASRock              | 27       | 18.49%  |
| MSI                 | 12       | 8.22%   |
| ECS                 | 7        | 4.79%   |
| Samsung Electronics | 5        | 3.42%   |
| Lenovo              | 5        | 3.42%   |
| Hewlett-Packard     | 5        | 3.42%   |
| Foxconn             | 3        | 2.05%   |
| LattePanda          | 2        | 1.37%   |
| Huanan              | 2        | 1.37%   |
| Dell                | 2        | 1.37%   |
| WTM                 | 1        | 0.68%   |
| PCPartner           | 1        | 0.68%   |
| PC Partner Limited  | 1        | 0.68%   |
| Fujitsu             | 1        | 0.68%   |
| Biostar             | 1        | 0.68%   |
| ASRockRack          | 1        | 0.68%   |
| AMD                 | 1        | 0.68%   |
| Alienware           | 1        | 0.68%   |
| Unknown             | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung DeskTop System                 | 4        | 2.74%   |
| ASUS PRIME B350M-A                     | 3        | 2.05%   |
| MSI MS-7D42                            | 2        | 1.37%   |
| LattePanda Alpha                       | 2        | 1.37%   |
| Gigabyte TRX40 AORUS XTREME            | 2        | 1.37%   |
| Gigabyte H81M-DS2V                     | 2        | 1.37%   |
| Gigabyte B75M-D3V                      | 2        | 1.37%   |
| Gigabyte B75M-D3H                      | 2        | 1.37%   |
| Gigabyte B360M-D3H                     | 2        | 1.37%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4   | 2        | 1.37%   |
| ASUS PRIME A320M-K                     | 2        | 1.37%   |
| ASUS EX-A320M-GAMING                   | 2        | 1.37%   |
| ASUS All Series                        | 2        | 1.37%   |
| ASRock H81M-DGS R2.0                   | 2        | 1.37%   |
| ASRock AB350M Pro4                     | 2        | 1.37%   |
| WTM W-N95                              | 1        | 0.68%   |
| Samsung 500T8A/500S8A/500T9A/500S9A    | 1        | 0.68%   |
| PCPartner DREAMSYS                     | 1        | 0.68%   |
| PC Partner Limited S70BS.AH3511        | 1        | 0.68%   |
| MSI MS-7C75                            | 1        | 0.68%   |
| MSI MS-7C51                            | 1        | 0.68%   |
| MSI MS-7B89                            | 1        | 0.68%   |
| MSI MS-7B85                            | 1        | 0.68%   |
| MSI MS-7B24                            | 1        | 0.68%   |
| MSI MS-7A74                            | 1        | 0.68%   |
| MSI MS-7A37                            | 1        | 0.68%   |
| MSI MS-7A20                            | 1        | 0.68%   |
| MSI MS-7A15                            | 1        | 0.68%   |
| MSI MS-7808                            | 1        | 0.68%   |
| Lenovo ThinkStation P900 30A4A03600    | 1        | 0.68%   |
| Lenovo ThinkStation P520c 30BXCTO1WW   | 1        | 0.68%   |
| Lenovo ThinkCentre M72e 4004H1U        | 1        | 0.68%   |
| Lenovo IdeaCentre 5 14IMB05 90NA0028KR | 1        | 0.68%   |
| Lenovo 70A4000FUX ThinkServer TS140    | 1        | 0.68%   |
| Huanan X99-F8                          | 1        | 0.68%   |
| Huanan Thurley                         | 1        | 0.68%   |
| HP Z620 Workstation                    | 1        | 0.68%   |
| HP ProDesk 600 G1 TWR                  | 1        | 0.68%   |
| HP Pavilion Desktop TP01-2xxx          | 1        | 0.68%   |
| HP Compaq Elite 8300 MT                | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME                      | 13       | 8.9%    |
| Samsung DeskTop                 | 4        | 2.74%   |
| ASUS ROG                        | 4        | 2.74%   |
| MSI MS-7D42                     | 2        | 1.37%   |
| Lenovo ThinkStation             | 2        | 1.37%   |
| LattePanda Alpha                | 2        | 1.37%   |
| Gigabyte Z390                   | 2        | 1.37%   |
| Gigabyte X570                   | 2        | 1.37%   |
| Gigabyte TRX40                  | 2        | 1.37%   |
| Gigabyte H81M-DS2V              | 2        | 1.37%   |
| Gigabyte B75M-D3V               | 2        | 1.37%   |
| Gigabyte B75M-D3H               | 2        | 1.37%   |
| Gigabyte B360M-D3H              | 2        | 1.37%   |
| Dell Vostro                     | 2        | 1.37%   |
| ASUS EX-A320M-GAMING            | 2        | 1.37%   |
| ASUS All                        | 2        | 1.37%   |
| ASRock Z390                     | 2        | 1.37%   |
| ASRock H81M-DGS                 | 2        | 1.37%   |
| ASRock FM2A88M-HD+              | 2        | 1.37%   |
| ASRock AB350M                   | 2        | 1.37%   |
| WTM W-N95                       | 1        | 0.68%   |
| Samsung 500T8A                  | 1        | 0.68%   |
| PCPartner DREAMSYS              | 1        | 0.68%   |
| PC Partner Limited S70BS.AH3511 | 1        | 0.68%   |
| MSI MS-7C75                     | 1        | 0.68%   |
| MSI MS-7C51                     | 1        | 0.68%   |
| MSI MS-7B89                     | 1        | 0.68%   |
| MSI MS-7B85                     | 1        | 0.68%   |
| MSI MS-7B24                     | 1        | 0.68%   |
| MSI MS-7A74                     | 1        | 0.68%   |
| MSI MS-7A37                     | 1        | 0.68%   |
| MSI MS-7A20                     | 1        | 0.68%   |
| MSI MS-7A15                     | 1        | 0.68%   |
| MSI MS-7808                     | 1        | 0.68%   |
| Lenovo ThinkCentre              | 1        | 0.68%   |
| Lenovo IdeaCentre               | 1        | 0.68%   |
| Lenovo 70A4000FUX               | 1        | 0.68%   |
| Huanan X99-F8                   | 1        | 0.68%   |
| Huanan Thurley                  | 1        | 0.68%   |
| HP Z620                         | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 19       | 13.01%  |
| 2012 | 18       | 12.33%  |
| 2017 | 16       | 10.96%  |
| 2019 | 14       | 9.59%   |
| 2013 | 11       | 7.53%   |
| 2020 | 9        | 6.16%   |
| 2014 | 9        | 6.16%   |
| 2021 | 8        | 5.48%   |
| 2016 | 7        | 4.79%   |
| 2009 | 7        | 4.79%   |
| 2015 | 6        | 4.11%   |
| 2007 | 5        | 3.42%   |
| 2022 | 4        | 2.74%   |
| 2010 | 4        | 2.74%   |
| 2011 | 3        | 2.05%   |
| 2008 | 3        | 2.05%   |
| 2006 | 2        | 1.37%   |
| 2005 | 1        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 146      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 143      | 97.95%  |
| Enabled  | 3        | 2.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 146      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 33       | 22.3%   |
| 16.01-24.0      | 28       | 18.92%  |
| 64.01-256.0     | 22       | 14.86%  |
| 4.01-8.0        | 20       | 13.51%  |
| 3.01-4.0        | 18       | 12.16%  |
| 32.01-64.0      | 15       | 10.14%  |
| 24.01-32.0      | 4        | 2.7%    |
| 1.01-2.0        | 4        | 2.7%    |
| More than 256.0 | 2        | 1.35%   |
| 2.01-3.0        | 2        | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 51       | 32.48%  |
| 2.01-3.0   | 31       | 19.75%  |
| 3.01-4.0   | 29       | 18.47%  |
| 4.01-8.0   | 21       | 13.38%  |
| 8.01-16.0  | 9        | 5.73%   |
| 0.51-1.0   | 9        | 5.73%   |
| 32.01-64.0 | 3        | 1.91%   |
| 16.01-24.0 | 3        | 1.91%   |
| 0.01-0.5   | 1        | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 55       | 37.16%  |
| 2      | 45       | 30.41%  |
| 3      | 20       | 13.51%  |
| 4      | 11       | 7.43%   |
| 5      | 7        | 4.73%   |
| 6      | 4        | 2.7%    |
| 7      | 2        | 1.35%   |
| 10     | 1        | 0.68%   |
| 9      | 1        | 0.68%   |
| 8      | 1        | 0.68%   |
| 0      | 1        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 67.35%  |
| Yes       | 48       | 32.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 145      | 99.32%  |
| No        | 1        | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 96       | 65.31%  |
| Yes       | 51       | 34.69%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 92       | 61.74%  |
| Yes       | 57       | 38.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| South Korea | 146      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Seoul          | 15       | 9.68%   |
| Seongnam-si    | 12       | 7.74%   |
| Yongin-si      | 6        | 3.87%   |
| Suwon          | 6        | 3.87%   |
| Busan          | 6        | 3.87%   |
| Cheonan        | 5        | 3.23%   |
| Hwaseong-si    | 4        | 2.58%   |
| Gwanak-gu      | 4        | 2.58%   |
| Seo-gu         | 3        | 1.94%   |
| Nam-gu         | 3        | 1.94%   |
| Guri-si        | 3        | 1.94%   |
| Goyang-si      | 3        | 1.94%   |
| Gangseo-gu     | 3        | 1.94%   |
| Bucheon-si     | 3        | 1.94%   |
| Anyang-si      | 3        | 1.94%   |
| Yongsan-gu     | 2        | 1.29%   |
| Yangcheon-gu   | 2        | 1.29%   |
| Uiwang         | 2        | 1.29%   |
| Uiseong-gun    | 2        | 1.29%   |
| Siheung-si     | 2        | 1.29%   |
| Seongdong-gu   | 2        | 1.29%   |
| Seongbuk-gu    | 2        | 1.29%   |
| Sejong         | 2        | 1.29%   |
| Pyeongtaek-si  | 2        | 1.29%   |
| Osan           | 2        | 1.29%   |
| Incheon        | 2        | 1.29%   |
| Gwangmyeong-si | 2        | 1.29%   |
| Gangnam-gu     | 2        | 1.29%   |
| Dongjak-gu     | 2        | 1.29%   |
| Daejeon        | 2        | 1.29%   |
| Ansan-si       | 2        | 1.29%   |
| Yuseong-gu     | 1        | 0.65%   |
| Yeonsu-gu      | 1        | 0.65%   |
| Ulsan          | 1        | 0.65%   |
| Ulju-gun       | 1        | 0.65%   |
| Taean-gun      | 1        | 0.65%   |
| Seosan City    | 1        | 0.65%   |
| Seodaemun-gu   | 1        | 0.65%   |
| Seocheon-gun   | 1        | 0.65%   |
| Pohang         | 1        | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 56       | 97     | 20.9%   |
| Seagate                   | 43       | 70     | 16.04%  |
| Samsung Electronics       | 42       | 62     | 15.67%  |
| Toshiba                   | 19       | 35     | 7.09%   |
| Crucial                   | 17       | 21     | 6.34%   |
| SanDisk                   | 16       | 21     | 5.97%   |
| Hitachi                   | 11       | 12     | 4.1%    |
| Unknown                   | 7        | 8      | 2.61%   |
| A-DATA Technology         | 6        | 6      | 2.24%   |
| SK hynix                  | 5        | 7      | 1.87%   |
| Transcend                 | 4        | 4      | 1.49%   |
| SPCC                      | 3        | 3      | 1.12%   |
| Silicon Motion            | 3        | 4      | 1.12%   |
| Plextor                   | 3        | 5      | 1.12%   |
| Micron Technology         | 3        | 4      | 1.12%   |
| HGST                      | 3        | 3      | 1.12%   |
| TAMMUZ                    | 2        | 3      | 0.75%   |
| Intel                     | 2        | 2      | 0.75%   |
| China                     | 2        | 2      | 0.75%   |
| ZOTAC                     | 1        | 1      | 0.37%   |
| Team                      | 1        | 1      | 0.37%   |
| Seagate Technology        | 1        | 1      | 0.37%   |
| Realtek Semiconductor     | 1        | 1      | 0.37%   |
| QNIX                      | 1        | 1      | 0.37%   |
| Phison                    | 1        | 2      | 0.37%   |
| PHINOCOM                  | 1        | 1      | 0.37%   |
| OSCOO                     | 1        | 1      | 0.37%   |
| OCZ                       | 1        | 2      | 0.37%   |
| Netac                     | 1        | 1      | 0.37%   |
| Micron/Crucial Technology | 1        | 1      | 0.37%   |
| MARVELL                   | 1        | 1      | 0.37%   |
| LITEON                    | 1        | 1      | 0.37%   |
| LaCie                     | 1        | 1      | 0.37%   |
| KIOXIA                    | 1        | 3      | 0.37%   |
| KingSpec                  | 1        | 1      | 0.37%   |
| JMicron Technology        | 1        | 1      | 0.37%   |
| Imation                   | 1        | 2      | 0.37%   |
| Hewlett-Packard           | 1        | 1      | 0.37%   |
| GLOWAY                    | 1        | 1      | 0.37%   |
| Fujitsu                   | 1        | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Toshiba DT01ACA300 3TB                 | 7        | 2.18%   |
| Seagate ST500DM002-1BD142 500GB        | 6        | 1.87%   |
| Crucial CT240BX500SSD1 240GB           | 6        | 1.87%   |
| Samsung SSD 850 EVO 120GB              | 4        | 1.25%   |
| Crucial CT500MX500SSD1 500GB           | 4        | 1.25%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 3        | 0.93%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 3        | 0.93%   |
| WDC WD10EZEX-22MFCA0 1TB               | 3        | 0.93%   |
| Toshiba DT01ACA200 2TB                 | 3        | 0.93%   |
| Toshiba DT01ACA050 500GB               | 3        | 0.93%   |
| Seagate ST3500418AS 500GB              | 3        | 0.93%   |
| Seagate ST2000DM008-2FR102 2TB         | 3        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB         | 3        | 0.93%   |
| SanDisk SD8SBAT128G1122 128GB SSD      | 3        | 0.93%   |
| Samsung SSD 850 EVO 250GB              | 3        | 0.93%   |
| Crucial CT275MX300SSD4 275GB           | 3        | 0.93%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2        | 0.62%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2        | 0.62%   |
| WDC WD40EFRX-68WT0N0 4TB               | 2        | 0.62%   |
| WDC WD3200AAJS-00L7A0 320GB            | 2        | 0.62%   |
| WDC WD20EARX-00PASB0 2TB               | 2        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2        | 0.62%   |
| WDC WD10EZEX-00WN4A0 1TB               | 2        | 0.62%   |
| Unknown SD/MMC/MS PRO 64GB             | 2        | 0.62%   |
| Transcend TS240GSSD220S 240GB          | 2        | 0.62%   |
| Toshiba HDWD120 2TB                    | 2        | 0.62%   |
| TAMMUZ SSD 128GB                       | 2        | 0.62%   |
| SK hynix SHGP31-500GM 500GB            | 2        | 0.62%   |
| Seagate ST8000DM004-2CX188 8TB         | 2        | 0.62%   |
| Seagate ST2000DM001-1ER164 2TB         | 2        | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB         | 2        | 0.62%   |
| Samsung SSD 850 PRO 256GB              | 2        | 0.62%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2        | 0.62%   |
| Samsung NVMe SSD Drive 1TB             | 2        | 0.62%   |
| Samsung HD502IJ 500GB                  | 2        | 0.62%   |
| Samsung HD322HJ 320GB                  | 2        | 0.62%   |
| Hitachi HTS545050B9A300 500GB          | 2        | 0.62%   |
| Crucial CT275MX300SSD1 275GB           | 2        | 0.62%   |
| A-DATA SU800 256GB SSD                 | 2        | 0.62%   |
| A-DATA SP900 256GB SSD                 | 2        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 48       | 81     | 36.09%  |
| Seagate             | 41       | 65     | 30.83%  |
| Toshiba             | 16       | 25     | 12.03%  |
| Hitachi             | 11       | 12     | 8.27%   |
| Samsung Electronics | 8        | 9      | 6.02%   |
| HGST                | 3        | 3      | 2.26%   |
| Unknown             | 2        | 3      | 1.5%    |
| MARVELL             | 1        | 1      | 0.75%   |
| LaCie               | 1        | 1      | 0.75%   |
| Hewlett-Packard     | 1        | 1      | 0.75%   |
| Fujitsu             | 1        | 1      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 30     | 22.33%  |
| Crucial             | 17       | 21     | 16.5%   |
| SanDisk             | 14       | 17     | 13.59%  |
| WDC                 | 10       | 14     | 9.71%   |
| A-DATA Technology   | 5        | 5      | 4.85%   |
| Transcend           | 4        | 4      | 3.88%   |
| Toshiba             | 3        | 10     | 2.91%   |
| SPCC                | 3        | 3      | 2.91%   |
| Seagate             | 3        | 4      | 2.91%   |
| TAMMUZ              | 2        | 3      | 1.94%   |
| SK hynix            | 2        | 3      | 1.94%   |
| Plextor             | 2        | 4      | 1.94%   |
| Intel               | 2        | 2      | 1.94%   |
| China               | 2        | 2      | 1.94%   |
| QNIX                | 1        | 1      | 0.97%   |
| PHINOCOM            | 1        | 1      | 0.97%   |
| OSCOO               | 1        | 1      | 0.97%   |
| OCZ                 | 1        | 2      | 0.97%   |
| Netac               | 1        | 1      | 0.97%   |
| Micron Technology   | 1        | 1      | 0.97%   |
| LITEON              | 1        | 1      | 0.97%   |
| KingSpec            | 1        | 1      | 0.97%   |
| JMicron Technology  | 1        | 1      | 0.97%   |
| Imation             | 1        | 2      | 0.97%   |
| GLOWAY              | 1        | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 101      | 202    | 44.1%   |
| SSD     | 87       | 135    | 37.99%  |
| NVMe    | 36       | 53     | 15.72%  |
| MMC     | 3        | 3      | 1.31%   |
| Unknown | 2        | 2      | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 131      | 332    | 74.43%  |
| NVMe | 36       | 53     | 20.45%  |
| SAS  | 6        | 7      | 3.41%   |
| MMC  | 3        | 3      | 1.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 102      | 169    | 50%     |
| 0.51-1.0   | 40       | 64     | 19.61%  |
| 1.01-2.0   | 26       | 36     | 12.75%  |
| 3.01-4.0   | 14       | 27     | 6.86%   |
| 2.01-3.0   | 10       | 14     | 4.9%    |
| 4.01-10.0  | 8        | 17     | 3.92%   |
| 10.01-20.0 | 4        | 10     | 1.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 36       | 24.16%  |
| 251-500        | 29       | 19.46%  |
| 501-1000       | 21       | 14.09%  |
| More than 3000 | 16       | 10.74%  |
| 1001-2000      | 14       | 9.4%    |
| 2001-3000      | 13       | 8.72%   |
| 21-50          | 7        | 4.7%    |
| 1-20           | 5        | 3.36%   |
| 51-100         | 5        | 3.36%   |
| Unknown        | 3        | 2.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 56       | 37.09%  |
| 21-50          | 23       | 15.23%  |
| 101-250        | 17       | 11.26%  |
| 51-100         | 13       | 8.61%   |
| 251-500        | 12       | 7.95%   |
| 501-1000       | 11       | 7.28%   |
| More than 3000 | 7        | 4.64%   |
| 2001-3000      | 7        | 4.64%   |
| Unknown        | 3        | 1.99%   |
| 1001-2000      | 2        | 1.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Desktops | Drives | Percent |
|-----------------------------------------------------------------|----------|--------|---------|
| WDC WD7500AACS-00D6B0 752GB                                     | 1        | 1      | 8.33%   |
| WDC WD5000AAKX-75U6AA0 500GB                                    | 1        | 1      | 8.33%   |
| WDC WD40EZRZ-00WN9B0 4TB                                        | 1        | 1      | 8.33%   |
| WDC WD1600BEVT-22A23T0 160GB                                    | 1        | 1      | 8.33%   |
| WDC WD1001FALS-00J7B1 1TB                                       | 1        | 1      | 8.33%   |
| Seagate ST4000DM000-1F2168 4TB                                  | 1        | 1      | 8.33%   |
| Seagate ST3500418AS 500GB                                       | 1        | 1      | 8.33%   |
| Seagate ST1000DM003-1CH162 1TB                                  | 1        | 1      | 8.33%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 1        | 1      | 8.33%   |
| LITEON LMH-128V2M 128GB SSD                                     | 1        | 1      | 8.33%   |
| HGST HDN726060ALE610 6TB                                        | 1        | 1      | 8.33%   |
| A-DATA Technology SU650 240GB SSD                               | 1        | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 5      | 41.67%  |
| Seagate             | 3        | 3      | 25%     |
| Samsung Electronics | 1        | 1      | 8.33%   |
| LITEON              | 1        | 1      | 8.33%   |
| HGST                | 1        | 1      | 8.33%   |
| A-DATA Technology   | 1        | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 5        | 5      | 55.56%  |
| Seagate | 3        | 3      | 33.33%  |
| HGST    | 1        | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 7        | 9      | 70%     |
| SSD  | 2        | 2      | 20%     |
| NVMe | 1        | 1      | 10%     |

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
| Detected | 97       | 261    | 61.78%  |
| Works    | 50       | 122    | 31.85%  |
| Malfunc  | 10       | 12     | 6.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 100      | 46.95%  |
| AMD                        | 43       | 20.19%  |
| Samsung Electronics        | 20       | 9.39%   |
| ASMedia Technology         | 13       | 6.1%    |
| JMicron Technology         | 10       | 4.69%   |
| Silicon Motion             | 4        | 1.88%   |
| Marvell Technology Group   | 4        | 1.88%   |
| SK hynix                   | 3        | 1.41%   |
| SanDisk                    | 3        | 1.41%   |
| Phison Electronics         | 3        | 1.41%   |
| Seagate Technology         | 2        | 0.94%   |
| Micron Technology          | 2        | 0.94%   |
| Realtek Semiconductor      | 1        | 0.47%   |
| Micron/Crucial Technology  | 1        | 0.47%   |
| Lite-On Technology         | 1        | 0.47%   |
| Lite-On IT Corp. / Plextor | 1        | 0.47%   |
| KIOXIA                     | 1        | 0.47%   |
| ADATA Technology           | 1        | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 32       | 11.64%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15       | 5.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 12       | 4.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 4%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 3.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 3.27%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 3.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 2.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.91%   |
| AMD FCH SATA Controller D                                                               | 8        | 2.91%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 2.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 2.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7        | 2.55%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6        | 2.18%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4        | 1.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.45%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.45%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 3        | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3        | 1.09%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 1.09%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3        | 1.09%   |
| AMD X399 Series Chipset SATA Controller                                                 | 3        | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3        | 1.09%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3        | 1.09%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2        | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.73%   |
| Samsung NVMe SSD Controller 980                                                         | 2        | 0.73%   |
| Micron Non-Volatile memory controller                                                   | 2        | 0.73%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.73%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.73%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.73%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.73%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 121      | 60.8%   |
| NVMe | 38       | 19.1%   |
| IDE  | 32       | 16.08%  |
| RAID | 7        | 3.52%   |
| SAS  | 1        | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 103      | 70.55%  |
| AMD    | 43       | 29.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz            | 8        | 5.48%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 5        | 3.42%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 3.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 2.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 4        | 2.74%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 2.05%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.05%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.05%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.05%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 2.05%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.37%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 2        | 1.37%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 1.37%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 1.37%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.37%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 2        | 1.37%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.37%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.37%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 2        | 1.37%   |
| Intel Xeon W-3275M CPU @ 2.50GHz            | 1        | 0.68%   |
| Intel Xeon W-2133 CPU @ 3.60GHz             | 1        | 0.68%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1        | 0.68%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.68%   |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz         | 1        | 0.68%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz         | 1        | 0.68%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz         | 1        | 0.68%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 0.68%   |
| Intel Xeon CPU E3-1231 v3 @ 3.40GHz         | 1        | 0.68%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.68%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1        | 0.68%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.68%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.68%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.68%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 1        | 0.68%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.68%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.68%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.68%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 33       | 22.6%   |
| Intel Core i7           | 13       | 8.9%    |
| AMD Ryzen 5             | 13       | 8.9%    |
| Intel Xeon              | 11       | 7.53%   |
| Intel Core i3           | 9        | 6.16%   |
| Intel Core i9           | 7        | 4.79%   |
| Intel Core 2 Quad       | 6        | 4.11%   |
| AMD Ryzen 7             | 6        | 4.11%   |
| Other                   | 5        | 3.42%   |
| Intel Celeron           | 5        | 3.42%   |
| AMD Ryzen Threadripper  | 5        | 3.42%   |
| AMD Ryzen 3             | 5        | 3.42%   |
| Intel Pentium           | 4        | 2.74%   |
| AMD Ryzen 9             | 3        | 2.05%   |
| Intel Pentium Gold      | 2        | 1.37%   |
| Intel Pentium Dual-Core | 2        | 1.37%   |
| Intel Pentium 4         | 2        | 1.37%   |
| Intel Core m3           | 2        | 1.37%   |
| AMD A8                  | 2        | 1.37%   |
| AMD A10                 | 2        | 1.37%   |
| Intel Core 2 Duo        | 1        | 0.68%   |
| Intel Core 2            | 1        | 0.68%   |
| AMD Ryzen 7 PRO         | 1        | 0.68%   |
| AMD Ryzen 5 PRO         | 1        | 0.68%   |
| AMD Phenom II X6        | 1        | 0.68%   |
| AMD Phenom              | 1        | 0.68%   |
| AMD FX                  | 1        | 0.68%   |
| AMD Athlon II X2        | 1        | 0.68%   |
| AMD Athlon 64 X2        | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 55       | 37.67%  |
| 2      | 31       | 21.23%  |
| 6      | 25       | 17.12%  |
| 8      | 14       | 9.59%   |
| 16     | 4        | 2.74%   |
| 10     | 4        | 2.74%   |
| 12     | 3        | 2.05%   |
| 32     | 2        | 1.37%   |
| 1      | 2        | 1.37%   |
| 64     | 1        | 0.68%   |
| 28     | 1        | 0.68%   |
| 22     | 1        | 0.68%   |
| 20     | 1        | 0.68%   |
| 18     | 1        | 0.68%   |
| 14     | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 145      | 99.32%  |
| 2      | 1        | 0.68%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 79       | 54.11%  |
| 1      | 67       | 45.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 144      | 97.96%  |
| Unknown        | 3        | 2.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 29       | 19.73%  |
| 0x306a9    | 16       | 10.88%  |
| 0x306c3    | 15       | 10.2%   |
| 0x906ea    | 8        | 5.44%   |
| 0x906e9    | 7        | 4.76%   |
| 0x306f2    | 4        | 2.72%   |
| 0x106e5    | 4        | 2.72%   |
| 0x1067a    | 4        | 2.72%   |
| 0x0800820d | 4        | 2.72%   |
| 0x08001138 | 4        | 2.72%   |
| 0x08001137 | 4        | 2.72%   |
| 0xa0655    | 3        | 2.04%   |
| 0x906ed    | 3        | 2.04%   |
| 0x6fb      | 3        | 2.04%   |
| 0x206a7    | 3        | 2.04%   |
| 0x906ec    | 2        | 1.36%   |
| 0x90672    | 2        | 1.36%   |
| 0x806e9    | 2        | 1.36%   |
| 0x506e3    | 2        | 1.36%   |
| 0x50654    | 2        | 1.36%   |
| 0x08701021 | 2        | 1.36%   |
| 0x08600106 | 2        | 1.36%   |
| 0x08101016 | 2        | 1.36%   |
| 0x0810100b | 2        | 1.36%   |
| 0xf49      | 1        | 0.68%   |
| 0x90675    | 1        | 0.68%   |
| 0x406f1    | 1        | 0.68%   |
| 0x306e4    | 1        | 0.68%   |
| 0x306d4    | 1        | 0.68%   |
| 0x0a50000c | 1        | 0.68%   |
| 0x0a20120a | 1        | 0.68%   |
| 0x0a201009 | 1        | 0.68%   |
| 0x08701013 | 1        | 0.68%   |
| 0x08301055 | 1        | 0.68%   |
| 0x08301025 | 1        | 0.68%   |
| 0x08108109 | 1        | 0.68%   |
| 0x08001126 | 1        | 0.68%   |
| 0x06003106 | 1        | 0.68%   |
| 0x06001119 | 1        | 0.68%   |
| 0x03000027 | 1        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 23       | 15.75%  |
| Haswell          | 20       | 13.7%   |
| IvyBridge        | 18       | 12.33%  |
| Zen              | 16       | 10.96%  |
| Zen+             | 7        | 4.79%   |
| Zen 2            | 7        | 4.79%   |
| Skylake          | 7        | 4.79%   |
| Penryn           | 7        | 4.79%   |
| CometLake        | 5        | 3.42%   |
| Zen 3            | 4        | 2.74%   |
| Nehalem          | 4        | 2.74%   |
| Core             | 4        | 2.74%   |
| Unknown          | 4        | 2.74%   |
| SandyBridge      | 3        | 2.05%   |
| K10              | 3        | 2.05%   |
| Steamroller      | 2        | 1.37%   |
| Piledriver       | 2        | 1.37%   |
| NetBurst         | 2        | 1.37%   |
| Broadwell        | 2        | 1.37%   |
| Alderlake Hybrid | 2        | 1.37%   |
| Westmere         | 1        | 0.68%   |
| Silvermont       | 1        | 0.68%   |
| K8 Hammer        | 1        | 0.68%   |
| K10 Llano        | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 76       | 47.5%   |
| Intel             | 49       | 30.63%  |
| AMD               | 34       | 21.25%  |
| ASPEED Technology | 1        | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 10       | 6.1%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 9        | 5.49%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 4.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 4.27%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 6        | 3.66%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.44%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4        | 2.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 3        | 1.83%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 1.83%   |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 1.83%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 3        | 1.83%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.22%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.22%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.22%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2        | 1.22%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.22%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 1.22%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.22%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 1.22%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 1.22%   |
| Nvidia G98 [GeForce 9300 GS]                                                | 2        | 1.22%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 2        | 1.22%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.22%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 2        | 1.22%   |
| AMD Renoir                                                                  | 2        | 1.22%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.22%   |
| AMD Bonaire XTX [Radeon R7 260X/360]                                        | 2        | 1.22%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.61%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.61%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.61%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.61%   |
| Nvidia TU102 [TITAN RTX]                                                    | 1        | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.61%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.61%   |
| Nvidia NV43 [GeForce 6600]                                                  | 1        | 0.61%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.61%   |
| Nvidia GT200b [GeForce GTX 275]                                             | 1        | 0.61%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 72       | 48.98%  |
| 1 x Intel      | 38       | 25.85%  |
| 1 x AMD        | 29       | 19.73%  |
| 2 x AMD        | 2        | 1.36%   |
| AMD + Nvidia   | 2        | 1.36%   |
| 2 x Nvidia     | 1        | 0.68%   |
| Intel + Nvidia | 1        | 0.68%   |
| Intel + AMD    | 1        | 0.68%   |
| 1 x ASPEED     | 1        | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 96       | 65.31%  |
| Proprietary | 47       | 31.97%  |
| Unknown     | 4        | 2.72%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 60       | 40.54%  |
| 0.51-1.0   | 22       | 14.86%  |
| 1.01-2.0   | 21       | 14.19%  |
| 0.01-0.5   | 11       | 7.43%   |
| 7.01-8.0   | 9        | 6.08%   |
| 3.01-4.0   | 7        | 4.73%   |
| 8.01-16.0  | 6        | 4.05%   |
| 5.01-6.0   | 4        | 2.7%    |
| 2.01-3.0   | 4        | 2.7%    |
| 16.01-24.0 | 3        | 2.03%   |
| 4.01-5.0   | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 30       | 21.43%  |
| Samsung Electronics  | 28       | 20%     |
| Unknown              | 10       | 7.14%   |
| Philips              | 6        | 4.29%   |
| LG Electronics       | 6        | 4.29%   |
| Dell                 | 6        | 4.29%   |
| OUT                  | 5        | 3.57%   |
| Hewlett-Packard      | 5        | 3.57%   |
| AOC                  | 5        | 3.57%   |
| PRISM+               | 4        | 2.86%   |
| BenQ                 | 3        | 2.14%   |
| OOO                  | 2        | 1.43%   |
| MStar                | 2        | 1.43%   |
| Lenovo               | 2        | 1.43%   |
| JRY                  | 2        | 1.43%   |
| Ancor Communications | 2        | 1.43%   |
| Unknown (ADE)        | 1        | 0.71%   |
| TopView              | 1        | 0.71%   |
| TGL                  | 1        | 0.71%   |
| SiS                  | 1        | 0.71%   |
| SANYO                | 1        | 0.71%   |
| RTK                  | 1        | 0.71%   |
| RAT                  | 1        | 0.71%   |
| PBK                  | 1        | 0.71%   |
| ORM                  | 1        | 0.71%   |
| NME                  | 1        | 0.71%   |
| MON                  | 1        | 0.71%   |
| LYC                  | 1        | 0.71%   |
| JCH                  | 1        | 0.71%   |
| ITE                  | 1        | 0.71%   |
| HVT                  | 1        | 0.71%   |
| DPL                  | 1        | 0.71%   |
| Denver               | 1        | 0.71%   |
| CVT                  | 1        | 0.71%   |
| CND                  | 1        | 0.71%   |
| ALP                  | 1        | 0.71%   |
| Albatron             | 1        | 0.71%   |
| ADP                  | 1        | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 5        | 3.38%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                          | 3        | 2.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 2.03%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1872x1053mm 84.6-inch | 2        | 1.35%   |
| PRISM+ ULTRON 3547UC INN0035 2560x1080 820x345mm 35.0-inch              | 2        | 1.35%   |
| OOO 23.8' monitor OOO0001 1920x1080 409x230mm 18.5-inch                 | 2        | 1.35%   |
| JRY Digital JRY0215 1920x1080 368x207mm 16.6-inch                       | 2        | 1.35%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                              | 1        | 0.68%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                      | 1        | 0.68%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                   | 1        | 0.68%   |
| Unknown LCD Monitor OUT Digital 3200x1080                               | 1        | 0.68%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                       | 1        | 0.68%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                           | 1        | 0.68%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                         | 1        | 0.68%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                            | 1        | 0.68%   |
| Unknown LCD Monitor Digital Projection Limited DP                       | 1        | 0.68%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                              | 1        | 0.68%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                          | 1        | 0.68%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch       | 1        | 0.68%   |
| TopView TOPSYNC TOP049B 2560x1440 597x336mm 27.0-inch                   | 1        | 0.68%   |
| TGL TGL A190 TGL0908 1280x1024 376x301mm 19.0-inch                      | 1        | 0.68%   |
| SiS DV 24 TV SIS0330 1920x1080 930x530mm 42.1-inch                      | 1        | 0.68%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch                 | 1        | 0.68%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch       | 1        | 0.68%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch       | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch    | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM04AE 1680x1050 459x296mm 21.5-inch    | 1        | 0.68%   |
| Samsung Electronics SyncMaster SAM03F3 1920x1200 518x324mm 24.1-inch    | 1        | 0.68%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch       | 1        | 0.68%   |
| Samsung Electronics S32E511 SAM0D11 1920x1080 698x392mm 31.5-inch       | 1        | 0.68%   |
| Samsung Electronics S27D850 SAM0BC7 2560x1440 598x336mm 27.0-inch       | 1        | 0.68%   |
| Samsung Electronics S27B240 SAM08EA 1920x1080 598x336mm 27.0-inch       | 1        | 0.68%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                    | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SMBX2440 1920x1080                      | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM7129 3840x2160 1020x570mm 46.0-inch  | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0D49 1920x1080 885x498mm 40.0-inch   | 1        | 0.68%   |
| Samsung Electronics LCD Monitor SAM0910 1920x1080                       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor S27E500 1920x1080                       | 1        | 0.68%   |
| Samsung Electronics LCD Monitor S24E510C 1920x1080                      | 1        | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 73       | 51.77%  |
| 3840x2160 (4K)     | 15       | 10.64%  |
| 2560x1440 (QHD)    | 13       | 9.22%   |
| 1280x1024 (SXGA)   | 9        | 6.38%   |
| 1920x1200 (WUXGA)  | 6        | 4.26%   |
| 1680x1050 (WSXGA+) | 6        | 4.26%   |
| 2560x1080          | 4        | 2.84%   |
| Unknown            | 3        | 2.13%   |
| 3840x1080          | 2        | 1.42%   |
| 3440x1440          | 2        | 1.42%   |
| 1440x900 (WXGA+)   | 2        | 1.42%   |
| 4880x2560          | 1        | 0.71%   |
| 3840x1600          | 1        | 0.71%   |
| 3286x1080          | 1        | 0.71%   |
| 3200x1080          | 1        | 0.71%   |
| 1600x900 (HD+)     | 1        | 0.71%   |
| 1600x1200          | 1        | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 29       | 21.01%  |
| 27      | 23       | 16.67%  |
| 21      | 18       | 13.04%  |
| 23      | 13       | 9.42%   |
| 24      | 9        | 6.52%   |
| 16      | 8        | 5.8%    |
| 31      | 5        | 3.62%   |
| 19      | 5        | 3.62%   |
| 84      | 3        | 2.17%   |
| 34      | 3        | 2.17%   |
| 18      | 3        | 2.17%   |
| 35      | 2        | 1.45%   |
| 25      | 2        | 1.45%   |
| 22      | 2        | 1.45%   |
| 20      | 2        | 1.45%   |
| 17      | 2        | 1.45%   |
| 49      | 1        | 0.72%   |
| 48      | 1        | 0.72%   |
| 46      | 1        | 0.72%   |
| 42      | 1        | 0.72%   |
| 40      | 1        | 0.72%   |
| 39      | 1        | 0.72%   |
| 37      | 1        | 0.72%   |
| 33      | 1        | 0.72%   |
| 29      | 1        | 0.72%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 43       | 31.85%  |
| Unknown     | 29       | 21.48%  |
| 401-500     | 25       | 18.52%  |
| 301-350     | 8        | 5.93%   |
| 601-700     | 7        | 5.19%   |
| 351-400     | 7        | 5.19%   |
| 801-900     | 5        | 3.7%    |
| 701-800     | 4        | 2.96%   |
| 1501-2000   | 3        | 2.22%   |
| 1001-1500   | 3        | 2.22%   |
| 901-1000    | 1        | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 77       | 56.62%  |
| Unknown | 27       | 19.85%  |
| 4/3     | 8        | 5.88%   |
| 21/9    | 7        | 5.15%   |
| 16/10   | 7        | 5.15%   |
| 5/4     | 6        | 4.41%   |
| 32/9    | 2        | 1.47%   |
| 6/5     | 1        | 0.74%   |
| 3/2     | 1        | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 37       | 27.21%  |
| Unknown        | 29       | 21.32%  |
| 301-350        | 24       | 17.65%  |
| 351-500        | 12       | 8.82%   |
| 151-200        | 9        | 6.62%   |
| 131-140        | 6        | 4.41%   |
| 501-1000       | 6        | 4.41%   |
| 251-300        | 5        | 3.68%   |
| More than 1000 | 3        | 2.21%   |
| 141-150        | 3        | 2.21%   |
| 111-120        | 2        | 1.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 59       | 44.03%  |
| 101-120 | 31       | 23.13%  |
| Unknown | 29       | 21.64%  |
| 121-160 | 11       | 8.21%   |
| 1-50    | 2        | 1.49%   |
| 161-240 | 2        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 121      | 82.88%  |
| 2     | 16       | 10.96%  |
| 0     | 9        | 6.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 107      | 57.53%  |
| Intel                    | 49       | 26.34%  |
| Qualcomm Atheros         | 7        | 3.76%   |
| Ralink Technology        | 4        | 2.15%   |
| Ralink                   | 3        | 1.61%   |
| Broadcom                 | 3        | 1.61%   |
| MediaTek                 | 2        | 1.08%   |
| Marvell Technology Group | 2        | 1.08%   |
| Exar                     | 2        | 1.08%   |
| Wilocity                 | 1        | 0.54%   |
| PEAK-System Technik      | 1        | 0.54%   |
| D-Link                   | 1        | 0.54%   |
| Broadcom Limited         | 1        | 0.54%   |
| ASIX Electronics         | 1        | 0.54%   |
| Aquantia                 | 1        | 0.54%   |
| American Megatrends      | 1        | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94       | 42.15%  |
| Intel I211 Gigabit Network Connection                             | 7        | 3.14%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 2.69%   |
| Intel Wi-Fi 6 AX200                                               | 5        | 2.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 1.79%   |
| Intel Ethernet Controller I225-V                                  | 4        | 1.79%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 1.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 1.35%   |
| Realtek 802.11ac NIC                                              | 3        | 1.35%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.35%   |
| Intel Ethernet Controller X550                                    | 3        | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.35%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.35%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 3        | 1.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.9%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 2        | 0.9%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2        | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.9%    |
| Realtek 802.11n NIC                                               | 2        | 0.9%    |
| Ralink MT7601U Wireless Adapter                                   | 2        | 0.9%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 0.9%    |
| Intel Wireless 3165                                               | 2        | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 0.9%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.9%    |
| Exar XR21V1410 USB-UART IC                                        | 2        | 0.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 0.9%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                | 1        | 0.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1        | 0.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1        | 0.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.45%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1        | 0.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 1        | 0.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 20       | 37.04%  |
| Intel                 | 19       | 35.19%  |
| Ralink Technology     | 4        | 7.41%   |
| Ralink                | 3        | 5.56%   |
| Qualcomm Atheros      | 2        | 3.7%    |
| MediaTek              | 2        | 3.7%    |
| Broadcom              | 2        | 3.7%    |
| Wilocity              | 1        | 1.85%   |
| D-Link                | 1        | 1.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 5        | 9.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 5.56%   |
| Realtek 802.11ac NIC                                                   | 3        | 5.56%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 3        | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 3.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 2        | 3.7%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 2        | 3.7%    |
| Realtek 802.11n NIC                                                    | 2        | 3.7%    |
| Ralink MT7601U Wireless Adapter                                        | 2        | 3.7%    |
| Intel Wireless 3165                                                    | 2        | 3.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 3.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 3.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 3.7%    |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                     | 1        | 1.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1        | 1.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 1        | 1.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1        | 1.85%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                        | 1        | 1.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 1.85%   |
| Ralink RT5572 Wireless Adapter                                         | 1        | 1.85%   |
| Ralink RT5372 Wireless Adapter                                         | 1        | 1.85%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                              | 1        | 1.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 1.85%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                   | 1        | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 1        | 1.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 1.85%   |
| MediaTek WiFi                                                          | 1        | 1.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 1.85%   |
| Intel Wireless-AC 9260                                                 | 1        | 1.85%   |
| Intel Wireless 7265                                                    | 1        | 1.85%   |
| Intel Wireless 3160                                                    | 1        | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 1        | 1.85%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU] | 1        | 1.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 103      | 65.61%  |
| Intel                    | 42       | 26.75%  |
| Qualcomm Atheros         | 5        | 3.18%   |
| Marvell Technology Group | 2        | 1.27%   |
| Broadcom Limited         | 1        | 0.64%   |
| Broadcom                 | 1        | 0.64%   |
| ASIX Electronics         | 1        | 0.64%   |
| Aquantia                 | 1        | 0.64%   |
| American Megatrends      | 1        | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94       | 56.63%  |
| Intel I211 Gigabit Network Connection                             | 7        | 4.22%   |
| Intel Ethernet Connection (7) I219-V                              | 6        | 3.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4        | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 4        | 2.41%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 2.41%   |
| Intel I210 Gigabit Network Connection                             | 3        | 1.81%   |
| Intel Ethernet Controller X550                                    | 3        | 1.81%   |
| Intel Ethernet Connection I217-LM                                 | 3        | 1.81%   |
| Intel Ethernet Connection (2) I218-V                              | 3        | 1.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 1.2%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 1.2%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.2%    |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.6%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.6%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.6%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.6%    |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 1        | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.6%    |
| Intel Ethernet Connection (11) I219-V                             | 1        | 0.6%    |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.6%    |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.6%    |
| Intel 82575EB Gigabit Network Connection                          | 1        | 0.6%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 1        | 0.6%    |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.6%    |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.6%    |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1        | 0.6%    |
| American Megatrends Virtual Ethernet                              | 1        | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 72.86%  |
| WiFi     | 51       | 25.63%  |
| Modem    | 2        | 1.01%   |
| Unknown  | 1        | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 127      | 83.55%  |
| WiFi     | 25       | 16.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 100      | 68.49%  |
| 2     | 37       | 25.34%  |
| 3     | 7        | 4.79%   |
| 5     | 1        | 0.68%   |
| 4     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 146      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 25       | 43.86%  |
| Intel                   | 18       | 31.58%  |
| Realtek Semiconductor   | 6        | 10.53%  |
| Broadcom                | 3        | 5.26%   |
| ASUSTek Computer        | 3        | 5.26%   |
| IMC Networks            | 1        | 1.75%   |
| Foxconn / Hon Hai       | 1        | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 25       | 43.86%  |
| Realtek Bluetooth Radio                               | 6        | 10.53%  |
| Intel AX200 Bluetooth                                 | 5        | 8.77%   |
| Intel Bluetooth wireless interface                    | 4        | 7.02%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 5.26%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 3.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 3.51%   |
| Intel AX201 Bluetooth                                 | 2        | 3.51%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 1.75%   |
| Intel Bluetooth Device                                | 1        | 1.75%   |
| Intel AX210 Bluetooth                                 | 1        | 1.75%   |
| IMC Networks Bluetooth Radio                          | 1        | 1.75%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 1.75%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 1.75%   |
| ASUS Bluetooth Radio                                  | 1        | 1.75%   |
| ASUS Bluetooth Device                                 | 1        | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Intel                   | 100      | 41.84%  |
| Nvidia                  | 71       | 29.71%  |
| AMD                     | 54       | 22.59%  |
| Giga-Byte Technology    | 2        | 0.84%   |
| C-Media Electronics     | 2        | 0.84%   |
| ASUSTek Computer        | 2        | 0.84%   |
| Texas Instruments       | 1        | 0.42%   |
| Sony                    | 1        | 0.42%   |
| Medeli Electronics      | 1        | 0.42%   |
| JMTek                   | 1        | 0.42%   |
| Fry's Electronics       | 1        | 0.42%   |
| EGO SYStems             | 1        | 0.42%   |
| DigiTech                | 1        | 0.42%   |
| BEHRINGER International | 1        | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15       | 5.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 5.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11       | 3.99%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11       | 3.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 10       | 3.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10       | 3.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9        | 3.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9        | 3.26%   |
| Intel 200 Series PCH HD Audio                                              | 9        | 3.26%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8        | 2.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 7        | 2.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 7        | 2.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7        | 2.54%   |
| Nvidia GA102 High Definition Audio Controller                              | 5        | 1.81%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5        | 1.81%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5        | 1.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 4        | 1.45%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4        | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 4        | 1.45%   |
| Intel Comet Lake PCH cAVS                                                  | 4        | 1.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4        | 1.45%   |
| AMD FCH Azalia Controller                                                  | 4        | 1.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4        | 1.45%   |
| Nvidia TU102 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia High Definition Audio Controller                                    | 3        | 1.09%   |
| Nvidia GM206 High Definition Audio Controller                              | 3        | 1.09%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3        | 1.09%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3        | 1.09%   |
| Nvidia GF106 High Definition Audio Controller                              | 3        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3        | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 1.09%   |
| Nvidia TU104 HD Audio Controller                                           | 2        | 0.72%   |
| Nvidia GP102 HDMI Audio Controller                                         | 2        | 0.72%   |
| Nvidia GF104 High Definition Audio Controller                              | 2        | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 2        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 2        | 0.72%   |
| Intel Sunrise Point-LP HD Audio                                            | 2        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 45       | 69.23%  |
| Unknown             | 5        | 7.69%   |
| SK hynix            | 4        | 6.15%   |
| Team                | 3        | 4.62%   |
| Kingston            | 3        | 4.62%   |
| G.Skill             | 2        | 3.08%   |
| KLEVV               | 1        | 1.54%   |
| Imation             | 1        | 1.54%   |
| Crucial             | 1        | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s     | 6        | 8%      |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s    | 4        | 5.33%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s     | 3        | 4%      |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 4%      |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 3        | 4%      |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s     | 3        | 4%      |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 2        | 2.67%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s     | 2        | 2.67%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s     | 2        | 2.67%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 2.67%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s    | 2        | 2.67%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s    | 2        | 2.67%   |
| Samsung RAM M378A2K43BB1-CRC 16GB DIMM DDR4 3200MT/s    | 2        | 2.67%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s     | 2        | 2.67%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s     | 2        | 2.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 1        | 1.33%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 1        | 1.33%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s      | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-2666 32GB DIMM DDR4 3000MT/s     | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-2400 4GB DIMM DDR4 2400MT/s      | 1        | 1.33%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s      | 1        | 1.33%   |
| SK hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s | 1        | 1.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 1        | 1.33%   |
| SK hynix RAM HMA82GU6DJR8N-XN 16GB DIMM DDR4 3200MT/s   | 1        | 1.33%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8GB DIMM DDR4 3200MT/s    | 1        | 1.33%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s              | 1        | 1.33%   |
| Samsung RAM Module 16GB DIMM DDR4 2400MT/s              | 1        | 1.33%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s   | 1        | 1.33%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Samsung RAM M386A8K40CM2-CTD 64GB DIMM DDR4 2666MT/s    | 1        | 1.33%   |
| Samsung RAM M378B5673GB0-CH9 2GB DIMM 1333MT/s          | 1        | 1.33%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s  | 1        | 1.33%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s     | 1        | 1.33%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2400MT/s     | 1        | 1.33%   |
| Samsung RAM M378A4G43AB2-CVF 32GB DIMM DDR4 2933MT/s    | 1        | 1.33%   |
| Samsung RAM M378A2K43BB1-CPB 16GB DIMM DDR4 2400MT/s    | 1        | 1.33%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s    | 1        | 1.33%   |
| Samsung RAM M378A1K43EB2-CWE 8GB DIMM DDR4 3200MT/s     | 1        | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 40       | 64.52%  |
| DDR3    | 18       | 29.03%  |
| SDRAM   | 2        | 3.23%   |
| Unknown | 2        | 3.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 61       | 98.39%  |
| SODIMM | 1        | 1.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 22       | 32.35%  |
| 4096  | 18       | 26.47%  |
| 16384 | 14       | 20.59%  |
| 32768 | 9        | 13.24%  |
| 2048  | 3        | 4.41%   |
| 65536 | 1        | 1.47%   |
| 1024  | 1        | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 13       | 17.81%  |
| 1600    | 11       | 15.07%  |
| 2667    | 7        | 9.59%   |
| 3500    | 6        | 8.22%   |
| 2400    | 5        | 6.85%   |
| 2133    | 4        | 5.48%   |
| 3466    | 3        | 4.11%   |
| 3066    | 3        | 4.11%   |
| 1866    | 3        | 4.11%   |
| 1800    | 3        | 4.11%   |
| 3400    | 2        | 2.74%   |
| 2933    | 2        | 2.74%   |
| 2666    | 2        | 2.74%   |
| 1867    | 2        | 2.74%   |
| 1333    | 2        | 2.74%   |
| Unknown | 2        | 2.74%   |
| 4800    | 1        | 1.37%   |
| 3866    | 1        | 1.37%   |
| 3000    | 1        | 1.37%   |

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
| Sunplus Innovation Technology | 4        | 33.33%  |
| Samsung Electronics           | 2        | 16.67%  |
| Logitech                      | 2        | 16.67%  |
| lihappe8                      | 2        | 16.67%  |
| Z-Star Microelectronics       | 1        | 8.33%   |
| LG Electronics                | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Sunplus SPCA2650 AV Camera                            | 2        | 16.67%  |
| Samsung Galaxy A5 (MTP)                               | 2        | 16.67%  |
| lihappe8 USB 2.0 Camera                               | 2        | 16.67%  |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 8.33%   |
| Sunplus UHD4K                                         | 1        | 8.33%   |
| Sunplus ABKO APC930 QHD WEBCAM                        | 1        | 8.33%   |
| Logitech Webcam C110                                  | 1        | 8.33%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 8.33%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 8.33%   |

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
| 0     | 124      | 84.93%  |
| 1     | 17       | 11.64%  |
| 2     | 3        | 2.05%   |
| 5     | 1        | 0.68%   |
| 3     | 1        | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 7        | 26.92%  |
| Unassigned class         | 6        | 23.08%  |
| Graphics card            | 5        | 19.23%  |
| Net/ethernet             | 3        | 11.54%  |
| Communication controller | 2        | 7.69%   |
| Camera                   | 2        | 7.69%   |
| Network                  | 1        | 3.85%   |

