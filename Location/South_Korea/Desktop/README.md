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

Total: 173

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Chuwi         | LarkBox Pro                 | [4c15433f48](https://linux-hardware.org/?probe=4c15433f48) | Jul 21, 2021 |
| ASUSTek       | P5QL/EPU                    | [6dcf33d186](https://linux-hardware.org/?probe=6dcf33d186) | Jul 14, 2021 |
| HP            | 3397                        | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| ASRockRack    | WC621D8A-2T                 | [d9c47162dc](https://linux-hardware.org/?probe=d9c47162dc) | Jun 25, 2021 |
| ASRockRack    | WC621D8A-2T                 | [b568edaa5e](https://linux-hardware.org/?probe=b568edaa5e) | Jun 25, 2021 |
| WB            | J3160                       | [88c472d69e](https://linux-hardware.org/?probe=88c472d69e) | Jun 18, 2021 |
| WB            | J3160                       | [b889890a54](https://linux-hardware.org/?probe=b889890a54) | Jun 11, 2021 |
| Gigabyte      | B75M-D3V                    | [9aaad9b2d4](https://linux-hardware.org/?probe=9aaad9b2d4) | Jun 07, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | [be07a70b2e](https://linux-hardware.org/?probe=be07a70b2e) | May 27, 2021 |
| Chuwi         | LarkBox Pro                 | [3d6a52dd8e](https://linux-hardware.org/?probe=3d6a52dd8e) | May 11, 2021 |
| Chuwi         | LarkBox Pro                 | [c77a0ae517](https://linux-hardware.org/?probe=c77a0ae517) | May 11, 2021 |
| ASUSTek       | P5QL/EPU                    | [965bc51c8d](https://linux-hardware.org/?probe=965bc51c8d) | May 06, 2021 |
| ASRock        | A75M-ITX                    | [1ad3e30eec](https://linux-hardware.org/?probe=1ad3e30eec) | May 03, 2021 |
| Chuwi         | LarkBox Pro                 | [167aa11de4](https://linux-hardware.org/?probe=167aa11de4) | Apr 26, 2021 |
| Chuwi         | LarkBox Pro                 | [7de0a8dd63](https://linux-hardware.org/?probe=7de0a8dd63) | Apr 24, 2021 |
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
| Chuwi         | LarkBox Pro                 | [ff50ed3542](https://linux-hardware.org/?probe=ff50ed3542) | Feb 01, 2021 |
| MSI           | B360M PRO-VDH               | [59b7bd58df](https://linux-hardware.org/?probe=59b7bd58df) | Jan 30, 2021 |
| MSI           | Z490-A PRO                  | [a29449d114](https://linux-hardware.org/?probe=a29449d114) | Jan 27, 2021 |
| MSI           | Z490-A PRO                  | [9595d4107b](https://linux-hardware.org/?probe=9595d4107b) | Jan 26, 2021 |
| ASRock        | B450M Steel Legend          | [a6226b7401](https://linux-hardware.org/?probe=a6226b7401) | Jan 20, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [ffa2d06213](https://linux-hardware.org/?probe=ffa2d06213) | Jan 05, 2021 |
| HP            | 18E7                        | [e9590ba71a](https://linux-hardware.org/?probe=e9590ba71a) | Jan 01, 2021 |
| Chuwi         | LarkBox Pro                 | [deb549d3e1](https://linux-hardware.org/?probe=deb549d3e1) | Dec 21, 2020 |
| Chuwi         | LarkBox Pro                 | [4245e53af4](https://linux-hardware.org/?probe=4245e53af4) | Dec 20, 2020 |
| ASUSTek       | PRIME B250M-A               | [77ad294d93](https://linux-hardware.org/?probe=77ad294d93) | Dec 20, 2020 |
| MSI           | B360M PRO-VDH               | [ae9a14bb34](https://linux-hardware.org/?probe=ae9a14bb34) | Dec 11, 2020 |
| MSI           | B360M PRO-VDH               | [1fd0be2128](https://linux-hardware.org/?probe=1fd0be2128) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-A               | [befbda84f5](https://linux-hardware.org/?probe=befbda84f5) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | [b1476b4c51](https://linux-hardware.org/?probe=b1476b4c51) | Dec 09, 2020 |
| ASUSTek       | PRIME B250M-A               | [a8b824f9f6](https://linux-hardware.org/?probe=a8b824f9f6) | Dec 09, 2020 |
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
| Gigabyte      | H110-D3A-CF                 | [2afffa7e4e](https://linux-hardware.org/?probe=2afffa7e4e) | May 10, 2018 |
| ECS           | A55F2-M3                    | [e4af897158](https://linux-hardware.org/?probe=e4af897158) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | [66b0fe56e5](https://linux-hardware.org/?probe=66b0fe56e5) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | [f3036847e4](https://linux-hardware.org/?probe=f3036847e4) | May 10, 2018 |
| ECS           | A55F2-M3                    | [5a5647b388](https://linux-hardware.org/?probe=5a5647b388) | May 10, 2018 |
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
| Ubuntu 20.04                 | 33       | 26.19%  |
| Ubuntu 18.04                 | 19       | 15.08%  |
| Ubuntu 16.04                 | 5        | 3.97%   |
| Ubuntu 20.10                 | 4        | 3.17%   |
| Ubuntu 19.10                 | 3        | 2.38%   |
| Fedora 32                    | 3        | 2.38%   |
| CentOS 7                     | 3        | 2.38%   |
| Arch                         | 3        | 2.38%   |
| Zorin 15                     | 2        | 1.59%   |
| Ubuntu 21.10                 | 2        | 1.59%   |
| RHEL 8                       | 2        | 1.59%   |
| No1 2018                     | 2        | 1.59%   |
| Linux Mint 20.2              | 2        | 1.59%   |
| Linux Mint 20.1              | 2        | 1.59%   |
| Linux Mint 20                | 2        | 1.59%   |
| Linux Mint 19.3              | 2        | 1.59%   |
| Gooroom                      | 2        | 1.59%   |
| Fedora 34                    | 2        | 1.59%   |
| Debian 10                    | 2        | 1.59%   |
| Chrome OS                    | 2        | 1.59%   |
| Ubuntu 22.04                 | 1        | 0.79%   |
| Ubuntu 19.04                 | 1        | 0.79%   |
| Ubuntu 18.10                 | 1        | 0.79%   |
| Ubuntu 17.10                 | 1        | 0.79%   |
| Ubuntu                       | 1        | 0.79%   |
| ROSA R10                     | 1        | 0.79%   |
| Pop!_OS 22.04                | 1        | 0.79%   |
| Pop!_OS 20.04                | 1        | 0.79%   |
| openSUSE Tumbleweed-20210929 | 1        | 0.79%   |
| openSUSE 20210916            | 1        | 0.79%   |
| OpenMandriva 4.50            | 1        | 0.79%   |
| OpenMandriva 4.2             | 1        | 0.79%   |
| No1 2020 te                  | 1        | 0.79%   |
| Manjaro 20.2.1               | 1        | 0.79%   |
| Lubuntu 18.04                | 1        | 0.79%   |
| Kubuntu 20.10                | 1        | 0.79%   |
| Kubuntu 19.10                | 1        | 0.79%   |
| KDE neon 18.04               | 1        | 0.79%   |
| HamoniKR 5.0                 | 1        | 0.79%   |
| HamoniKR 4.0                 | 1        | 0.79%   |
| HamoniKR                     | 1        | 0.79%   |
| Fedora 33                    | 1        | 0.79%   |
| Fedora 29                    | 1        | 0.79%   |
| Endless 3.6.2                | 1        | 0.79%   |
| EndeavourOS Rolling          | 1        | 0.79%   |
| Devuan 3                     | 1        | 0.79%   |
| Debian 9                     | 1        | 0.79%   |
| CentOS 8                     | 1        | 0.79%   |
| BlackPanther 18.1            | 1        | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 71       | 57.26%  |
| Linux Mint   | 7        | 5.65%   |
| Fedora       | 7        | 5.65%   |
| CentOS       | 4        | 3.23%   |
| HamoniKR     | 3        | 2.42%   |
| Debian       | 3        | 2.42%   |
| Arch         | 3        | 2.42%   |
| Zorin        | 2        | 1.61%   |
| RHEL         | 2        | 1.61%   |
| Pop!_OS      | 2        | 1.61%   |
| openSUSE     | 2        | 1.61%   |
| OpenMandriva | 2        | 1.61%   |
| No1          | 2        | 1.61%   |
| Kubuntu      | 2        | 1.61%   |
| Gooroom      | 2        | 1.61%   |
| Chrome OS    | 2        | 1.61%   |
| ROSA         | 1        | 0.81%   |
| Manjaro      | 1        | 0.81%   |
| Lubuntu      | 1        | 0.81%   |
| KDE neon     | 1        | 0.81%   |
| Endless      | 1        | 0.81%   |
| EndeavourOS  | 1        | 0.81%   |
| Devuan       | 1        | 0.81%   |
| BlackPanther | 1        | 0.81%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.4.0-29-generic          | 4        | 3.01%   |
| 5.4.0-26-generic          | 3        | 2.26%   |
| 5.8.0-48-generic          | 2        | 1.5%    |
| 5.8.0-41-generic          | 2        | 1.5%    |
| 5.8.0-38-generic          | 2        | 1.5%    |
| 5.4.0-58-generic          | 2        | 1.5%    |
| 5.4.0-56-generic          | 2        | 1.5%    |
| 5.4.0-54-generic          | 2        | 1.5%    |
| 5.4.0-52-generic          | 2        | 1.5%    |
| 5.4.0-47-generic          | 2        | 1.5%    |
| 5.4.0-42-generic          | 2        | 1.5%    |
| 5.4.0-37-generic          | 2        | 1.5%    |
| 5.3.0-51-generic          | 2        | 1.5%    |
| 5.3.0-40-generic          | 2        | 1.5%    |
| 5.13.0-21-generic         | 2        | 1.5%    |
| 4.19.0-12-amd64           | 2        | 1.5%    |
| 4.18.0-25-generic         | 2        | 1.5%    |
| 4.15.0-91-generic         | 2        | 1.5%    |
| 5.9.0-12.1-liquorix-amd64 | 1        | 0.75%   |
| 5.8.5-no1linux1           | 1        | 0.75%   |
| 5.8.16-300.fc33.x86_64    | 1        | 0.75%   |
| 5.8.10-200.fc32.x86_64    | 1        | 0.75%   |
| 5.8.0-59-generic          | 1        | 0.75%   |
| 5.8.0-55-generic          | 1        | 0.75%   |
| 5.8.0-50-generic          | 1        | 0.75%   |
| 5.8.0-44-generic          | 1        | 0.75%   |
| 5.8.0-33-generic          | 1        | 0.75%   |
| 5.8.0-32-generic          | 1        | 0.75%   |
| 5.8.0-26-generic          | 1        | 0.75%   |
| 5.8.0-1.el7.elrepo.x86_64 | 1        | 0.75%   |
| 5.7.16-200.fc32.x86_64    | 1        | 0.75%   |
| 5.6.6-arch1-1             | 1        | 0.75%   |
| 5.6.12-300.fc32.x86_64    | 1        | 0.75%   |
| 5.4.25+                   | 1        | 0.75%   |
| 5.4.2-arch1-1             | 1        | 0.75%   |
| 5.4.0-81-generic          | 1        | 0.75%   |
| 5.4.0-80-lowlatency       | 1        | 0.75%   |
| 5.4.0-79-generic          | 1        | 0.75%   |
| 5.4.0-7642-generic        | 1        | 0.75%   |
| 5.4.0-74-generic          | 1        | 0.75%   |
| 5.4.0-73-generic          | 1        | 0.75%   |
| 5.4.0-72-generic          | 1        | 0.75%   |
| 5.4.0-71-generic          | 1        | 0.75%   |
| 5.4.0-66-generic          | 1        | 0.75%   |
| 5.4.0-65-lowlatency       | 1        | 0.75%   |
| 5.4.0-65-generic          | 1        | 0.75%   |
| 5.4.0-33-generic          | 1        | 0.75%   |
| 5.4.0-21-generic          | 1        | 0.75%   |
| 5.4.0-105-generic         | 1        | 0.75%   |
| 5.4.0-104-generic         | 1        | 0.75%   |
| 5.3.0-59-generic          | 1        | 0.75%   |
| 5.3.0-46-generic          | 1        | 0.75%   |
| 5.3.0-45-generic          | 1        | 0.75%   |
| 5.3.0-28-generic          | 1        | 0.75%   |
| 5.3.0-24-generic          | 1        | 0.75%   |
| 5.16.19-76051619-generic  | 1        | 0.75%   |
| 5.16.1-051601-generic     | 1        | 0.75%   |
| 5.15.8-100.fc34.x86_64    | 1        | 0.75%   |
| 5.15.0-23-generic         | 1        | 0.75%   |
| 5.14.6-1-default          | 1        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 32       | 25%     |
| 4.15.0  | 18       | 14.06%  |
| 5.8.0   | 14       | 10.94%  |
| 5.3.0   | 9        | 7.03%   |
| 4.18.0  | 9        | 7.03%   |
| 5.13.0  | 4        | 3.13%   |
| 4.19.0  | 4        | 3.13%   |
| 5.0.0   | 3        | 2.34%   |
| 5.11.0  | 2        | 1.56%   |
| 4.13.0  | 2        | 1.56%   |
| 3.10.0  | 2        | 1.56%   |
| 5.9.0   | 1        | 0.78%   |
| 5.8.5   | 1        | 0.78%   |
| 5.8.16  | 1        | 0.78%   |
| 5.8.10  | 1        | 0.78%   |
| 5.7.16  | 1        | 0.78%   |
| 5.6.6   | 1        | 0.78%   |
| 5.6.12  | 1        | 0.78%   |
| 5.4.25  | 1        | 0.78%   |
| 5.4.2   | 1        | 0.78%   |
| 5.16.19 | 1        | 0.78%   |
| 5.16.1  | 1        | 0.78%   |
| 5.15.8  | 1        | 0.78%   |
| 5.15.0  | 1        | 0.78%   |
| 5.14.6  | 1        | 0.78%   |
| 5.14.2  | 1        | 0.78%   |
| 5.12.4  | 1        | 0.78%   |
| 5.11.8  | 1        | 0.78%   |
| 5.11.12 | 1        | 0.78%   |
| 5.10.4  | 1        | 0.78%   |
| 5.10.15 | 1        | 0.78%   |
| 5.10.14 | 1        | 0.78%   |
| 5.10.0  | 1        | 0.78%   |
| 5.0.4   | 1        | 0.78%   |
| 4.9.60  | 1        | 0.78%   |
| 4.9.0   | 1        | 0.78%   |
| 4.19.65 | 1        | 0.78%   |
| 4.18.16 | 1        | 0.78%   |
| 4.17.2  | 1        | 0.78%   |
| 4.15.8  | 1        | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 34       | 26.56%  |
| 4.15    | 19       | 14.84%  |
| 5.8     | 17       | 13.28%  |
| 4.18    | 10       | 7.81%   |
| 5.3     | 9        | 7.03%   |
| 4.19    | 5        | 3.91%   |
| 5.13    | 4        | 3.13%   |
| 5.11    | 4        | 3.13%   |
| 5.10    | 4        | 3.13%   |
| 5.0     | 4        | 3.13%   |
| 5.6     | 2        | 1.56%   |
| 5.16    | 2        | 1.56%   |
| 5.15    | 2        | 1.56%   |
| 5.14    | 2        | 1.56%   |
| 4.9     | 2        | 1.56%   |
| 4.13    | 2        | 1.56%   |
| 3.10    | 2        | 1.56%   |
| 5.9     | 1        | 0.78%   |
| 5.7     | 1        | 0.78%   |
| 5.12    | 1        | 0.78%   |
| 4.17    | 1        | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 121      | 99.18%  |
| i686   | 1        | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 60       | 48.78%  |
| Unknown         | 31       | 25.2%   |
| KDE5            | 10       | 8.13%   |
| X-Cinnamon      | 7        | 5.69%   |
| XFCE            | 4        | 3.25%   |
| Unity           | 2        | 1.63%   |
| KDE             | 2        | 1.63%   |
| GNOME Flashback | 2        | 1.63%   |
| Cinnamon        | 2        | 1.63%   |
| LXDE            | 1        | 0.81%   |
| KDE4            | 1        | 0.81%   |
| GNOME Classic   | 1        | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 90       | 73.77%  |
| Unknown | 18       | 14.75%  |
| Wayland | 9        | 7.38%   |
| Tty     | 5        | 4.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 89       | 72.36%  |
| GDM     | 12       | 9.76%   |
| SDDM    | 10       | 8.13%   |
| LightDM | 5        | 4.07%   |
| TDM     | 3        | 2.44%   |
| GDM3    | 3        | 2.44%   |
| SLiM    | 1        | 0.81%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| ko_KR   | 50       | 40.65%  |
| en_US   | 40       | 32.52%  |
| Unknown | 28       | 22.76%  |
| ru_RU   | 1        | 0.81%   |
| id_ID   | 1        | 0.81%   |
| fr_FR   | 1        | 0.81%   |
| en_GB   | 1        | 0.81%   |
| en_AU   | 1        | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 63       | 51.22%  |
| EFI  | 60       | 48.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 104      | 83.87%  |
| Unknown | 9        | 7.26%   |
| Xfs     | 5        | 4.03%   |
| Btrfs   | 4        | 3.23%   |
| Zfs     | 1        | 0.81%   |
| Overlay | 1        | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 70.49%  |
| GPT     | 26       | 21.31%  |
| MBR     | 10       | 8.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 83.74%  |
| Yes       | 20       | 16.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 82       | 66.67%  |
| Yes       | 41       | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 30       | 24.59%  |
| ASRock              | 25       | 20.49%  |
| Gigabyte Technology | 24       | 19.67%  |
| MSI                 | 10       | 8.2%    |
| ECS                 | 7        | 5.74%   |
| Samsung Electronics | 5        | 4.1%    |
| Lenovo              | 3        | 2.46%   |
| Hewlett-Packard     | 3        | 2.46%   |
| Foxconn             | 3        | 2.46%   |
| LattePanda          | 2        | 1.64%   |
| WB                  | 1        | 0.82%   |
| PC Partner Limited  | 1        | 0.82%   |
| Huanan              | 1        | 0.82%   |
| Dell                | 1        | 0.82%   |
| Chuwi               | 1        | 0.82%   |
| Biostar             | 1        | 0.82%   |
| ASRockRack          | 1        | 0.82%   |
| AMD                 | 1        | 0.82%   |
| Alienware           | 1        | 0.82%   |
| Unknown             | 1        | 0.82%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUS PRIME B350M-A                   | 3        | 2.46%   |
| Samsung Samsung DeskTop System       | 2        | 1.64%   |
| Samsung DeskTop System               | 2        | 1.64%   |
| LattePanda Alpha                     | 2        | 1.64%   |
| Gigabyte H81M-DS2V                   | 2        | 1.64%   |
| Gigabyte B75M-D3V                    | 2        | 1.64%   |
| Gigabyte B75M-D3H                    | 2        | 1.64%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4 | 2        | 1.64%   |
| ASUS PRIME A320M-K                   | 2        | 1.64%   |
| ASUS EX-A320M-GAMING                 | 2        | 1.64%   |
| ASUS All Series                      | 2        | 1.64%   |
| ASRock H81M-DGS R2.0                 | 2        | 1.64%   |
| ASRock AB350M Pro4                   | 2        | 1.64%   |
| WB AIO                               | 1        | 0.82%   |
| Samsung 500T8A/500S8A/500T9A/500S9A  | 1        | 0.82%   |
| PC Partner Limited S70BS.AH3511      | 1        | 0.82%   |
| MSI MS-7D42                          | 1        | 0.82%   |
| MSI MS-7C75                          | 1        | 0.82%   |
| MSI MS-7B89                          | 1        | 0.82%   |
| MSI MS-7B85                          | 1        | 0.82%   |
| MSI MS-7B24                          | 1        | 0.82%   |
| MSI MS-7A74                          | 1        | 0.82%   |
| MSI MS-7A37                          | 1        | 0.82%   |
| MSI MS-7A20                          | 1        | 0.82%   |
| MSI MS-7A15                          | 1        | 0.82%   |
| MSI MS-7808                          | 1        | 0.82%   |
| Lenovo ThinkStation P900 30A4A03600  | 1        | 0.82%   |
| Lenovo ThinkStation P520c 30BXCTO1WW | 1        | 0.82%   |
| Lenovo 70A4000FUX ThinkServer TS140  | 1        | 0.82%   |
| Huanan X99-F8                        | 1        | 0.82%   |
| HP Z620 Workstation                  | 1        | 0.82%   |
| HP ProDesk 600 G1 TWR                | 1        | 0.82%   |
| HP Compaq Elite 8300 MT              | 1        | 0.82%   |
| Gigabyte Z390 D                      | 1        | 0.82%   |
| Gigabyte Z390 AORUS PRO WIFI         | 1        | 0.82%   |
| Gigabyte X570 I AORUS PRO WIFI       | 1        | 0.82%   |
| Gigabyte X570 GAMING X               | 1        | 0.82%   |
| Gigabyte TRX40 AORUS XTREME          | 1        | 0.82%   |
| Gigabyte P55-US3L                    | 1        | 0.82%   |
| Gigabyte H97M-D3H                    | 1        | 0.82%   |
| Gigabyte H55M-S2V                    | 1        | 0.82%   |
| Gigabyte H110-D3A                    | 1        | 0.82%   |
| Gigabyte GA-MA790FX-DS5              | 1        | 0.82%   |
| Gigabyte GA-MA785GT-UD3H             | 1        | 0.82%   |
| Gigabyte B360M-DS3H                  | 1        | 0.82%   |
| Gigabyte B150M-D3H                   | 1        | 0.82%   |
| Gigabyte AB350M-DS2                  | 1        | 0.82%   |
| Gigabyte AB350-Gaming 3              | 1        | 0.82%   |
| Gigabyte A320M-S2H                   | 1        | 0.82%   |
| Gigabyte 945GM-S2                    | 1        | 0.82%   |
| Gigabyte 945GCMX-S2                  | 1        | 0.82%   |
| Foxconn P35                          | 1        | 0.82%   |
| Foxconn H61MXE                       | 1        | 0.82%   |
| Foxconn G41MXE/G41MXE-K              | 1        | 0.82%   |
| ECS H81H3-MV                         | 1        | 0.82%   |
| ECS H81H3-M4                         | 1        | 0.82%   |
| ECS H61H2-MV                         | 1        | 0.82%   |
| ECS G41T-M6                          | 1        | 0.82%   |
| ECS G31T-M7                          | 1        | 0.82%   |
| ECS A55F2-M3                         | 1        | 0.82%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Desktops | Percent |
|---------------------------------|----------|---------|
| ASUS PRIME                      | 11       | 9.02%   |
| ASUS ROG                        | 3        | 2.46%   |
| Samsung Samsung                 | 2        | 1.64%   |
| Samsung DeskTop                 | 2        | 1.64%   |
| Lenovo ThinkStation             | 2        | 1.64%   |
| LattePanda Alpha                | 2        | 1.64%   |
| Gigabyte Z390                   | 2        | 1.64%   |
| Gigabyte X570                   | 2        | 1.64%   |
| Gigabyte H81M-DS2V              | 2        | 1.64%   |
| Gigabyte B75M-D3V               | 2        | 1.64%   |
| Gigabyte B75M-D3H               | 2        | 1.64%   |
| ASUS EX-A320M-GAMING            | 2        | 1.64%   |
| ASUS All                        | 2        | 1.64%   |
| ASRock Z390                     | 2        | 1.64%   |
| ASRock H81M-DGS                 | 2        | 1.64%   |
| ASRock FM2A88M-HD+              | 2        | 1.64%   |
| ASRock AB350M                   | 2        | 1.64%   |
| WB AIO                          | 1        | 0.82%   |
| Samsung 500T8A                  | 1        | 0.82%   |
| PC Partner Limited S70BS.AH3511 | 1        | 0.82%   |
| MSI MS-7D42                     | 1        | 0.82%   |
| MSI MS-7C75                     | 1        | 0.82%   |
| MSI MS-7B89                     | 1        | 0.82%   |
| MSI MS-7B85                     | 1        | 0.82%   |
| MSI MS-7B24                     | 1        | 0.82%   |
| MSI MS-7A74                     | 1        | 0.82%   |
| MSI MS-7A37                     | 1        | 0.82%   |
| MSI MS-7A20                     | 1        | 0.82%   |
| MSI MS-7A15                     | 1        | 0.82%   |
| MSI MS-7808                     | 1        | 0.82%   |
| Lenovo 70A4000FUX               | 1        | 0.82%   |
| Huanan X99-F8                   | 1        | 0.82%   |
| HP Z620                         | 1        | 0.82%   |
| HP ProDesk                      | 1        | 0.82%   |
| HP Compaq                       | 1        | 0.82%   |
| Gigabyte TRX40                  | 1        | 0.82%   |
| Gigabyte P55-US3L               | 1        | 0.82%   |
| Gigabyte H97M-D3H               | 1        | 0.82%   |
| Gigabyte H55M-S2V               | 1        | 0.82%   |
| Gigabyte H110-D3A               | 1        | 0.82%   |
| Gigabyte GA-MA790FX-DS5         | 1        | 0.82%   |
| Gigabyte GA-MA785GT-UD3H        | 1        | 0.82%   |
| Gigabyte B360M-DS3H             | 1        | 0.82%   |
| Gigabyte B150M-D3H              | 1        | 0.82%   |
| Gigabyte AB350M-DS2             | 1        | 0.82%   |
| Gigabyte AB350-Gaming           | 1        | 0.82%   |
| Gigabyte A320M-S2H              | 1        | 0.82%   |
| Gigabyte 945GM-S2               | 1        | 0.82%   |
| Gigabyte 945GCMX-S2             | 1        | 0.82%   |
| Foxconn P35                     | 1        | 0.82%   |
| Foxconn H61MXE                  | 1        | 0.82%   |
| Foxconn G41MXE                  | 1        | 0.82%   |
| ECS H81H3-MV                    | 1        | 0.82%   |
| ECS H81H3-M4                    | 1        | 0.82%   |
| ECS H61H2-MV                    | 1        | 0.82%   |
| ECS G41T-M6                     | 1        | 0.82%   |
| ECS G31T-M7                     | 1        | 0.82%   |
| ECS A55F2-M3                    | 1        | 0.82%   |
| ECS A320AM4-M3D                 | 1        | 0.82%   |
| Dell Vostro                     | 1        | 0.82%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 16       | 13.11%  |
| 2012 | 16       | 13.11%  |
| 2017 | 15       | 12.3%   |
| 2019 | 11       | 9.02%   |
| 2013 | 10       | 8.2%    |
| 2020 | 7        | 5.74%   |
| 2009 | 7        | 5.74%   |
| 2016 | 6        | 4.92%   |
| 2014 | 6        | 4.92%   |
| 2021 | 5        | 4.1%    |
| 2015 | 5        | 4.1%    |
| 2007 | 5        | 4.1%    |
| 2010 | 4        | 3.28%   |
| 2008 | 4        | 3.28%   |
| 2011 | 3        | 2.46%   |
| 2006 | 1        | 0.82%   |
| 2005 | 1        | 0.82%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 122      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 120      | 98.36%  |
| Enabled  | 2        | 1.64%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 30       | 24.39%  |
| 16.01-24.0      | 20       | 16.26%  |
| 64.01-256.0     | 19       | 15.45%  |
| 3.01-4.0        | 17       | 13.82%  |
| 4.01-8.0        | 14       | 11.38%  |
| 32.01-64.0      | 13       | 10.57%  |
| 1.01-2.0        | 4        | 3.25%   |
| 24.01-32.0      | 3        | 2.44%   |
| 2.01-3.0        | 2        | 1.63%   |
| More than 256.0 | 1        | 0.81%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 45       | 35.16%  |
| 2.01-3.0   | 26       | 20.31%  |
| 3.01-4.0   | 19       | 14.84%  |
| 4.01-8.0   | 18       | 14.06%  |
| 0.51-1.0   | 8        | 6.25%   |
| 8.01-16.0  | 6        | 4.69%   |
| 16.01-24.0 | 3        | 2.34%   |
| 32.01-64.0 | 2        | 1.56%   |
| 0.01-0.5   | 1        | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 45       | 36.29%  |
| 2      | 35       | 28.23%  |
| 3      | 20       | 16.13%  |
| 4      | 11       | 8.87%   |
| 5      | 6        | 4.84%   |
| 6      | 2        | 1.61%   |
| 10     | 1        | 0.81%   |
| 9      | 1        | 0.81%   |
| 8      | 1        | 0.81%   |
| 7      | 1        | 0.81%   |
| 0      | 1        | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 83       | 67.48%  |
| Yes       | 40       | 32.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 122      | 99.19%  |
| No        | 1        | 0.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 84       | 68.29%  |
| Yes       | 39       | 31.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 77       | 62.1%   |
| Yes       | 47       | 37.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| South Korea | 122      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Desktops | Percent |
|-----------------|----------|---------|
| Seoul           | 18       | 13.95%  |
| Busan           | 9        | 6.98%   |
| Seongnam-si     | 6        | 4.65%   |
| Yongin-si       | 5        | 3.88%   |
| Cheonan         | 5        | 3.88%   |
| Suwon           | 4        | 3.1%    |
| Mapo-gu         | 4        | 3.1%    |
| Gwangju         | 4        | 3.1%    |
| Goyang-si       | 4        | 3.1%    |
| Bucheon-si      | 4        | 3.1%    |
| Ansan-si        | 4        | 3.1%    |
| Ulsan           | 3        | 2.33%   |
| Seongbuk-gu     | 3        | 2.33%   |
| Incheon         | 3        | 2.33%   |
| Hwaseong-si     | 3        | 2.33%   |
| Gangseo-gu      | 3        | 2.33%   |
| Daegu           | 3        | 2.33%   |
| Yeongdeungpo-gu | 2        | 1.55%   |
| Seongdong-gu    | 2        | 1.55%   |
| Namyangju       | 2        | 1.55%   |
| Jeonju          | 2        | 1.55%   |
| Gyeonggi-do     | 2        | 1.55%   |
| Dongjak-gu      | 2        | 1.55%   |
| Daejeon         | 2        | 1.55%   |
| Anyang-si       | 2        | 1.55%   |
| Yangp'yong      | 1        | 0.78%   |
| Yangcheon-gu    | 1        | 0.78%   |
| Siheung-si      | 1        | 0.78%   |
| Seosan City     | 1        | 0.78%   |
| Seocho-gu       | 1        | 0.78%   |
| Seo-gu          | 1        | 0.78%   |
| Pyeongtaek-si   | 1        | 0.78%   |
| Osan            | 1        | 0.78%   |
| Mokpo           | 1        | 0.78%   |
| Kwangmyong      | 1        | 0.78%   |
| Jung-gu         | 1        | 0.78%   |
| Jowon-dong      | 1        | 0.78%   |
| Jongno-gu       | 1        | 0.78%   |
| Jeju City       | 1        | 0.78%   |
| Haenam-gun      | 1        | 0.78%   |
| Gwanak-gu       | 1        | 0.78%   |
| Gunpo           | 1        | 0.78%   |
| Gumi            | 1        | 0.78%   |
| Gimpo-si        | 1        | 0.78%   |
| Gangnam-gu      | 1        | 0.78%   |
| Dongducheon-si  | 1        | 0.78%   |
| Damyang         | 1        | 0.78%   |
| Cheongju-si     | 1        | 0.78%   |
| Cheonan-si      | 1        | 0.78%   |
| Bundang-gu      | 1        | 0.78%   |
| Boryeong        | 1        | 0.78%   |
| Anseong         | 1        | 0.78%   |
| Andong          | 1        | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 51       | 88     | 22.37%  |
| Seagate                   | 39       | 56     | 17.11%  |
| Samsung Electronics       | 35       | 48     | 15.35%  |
| Sandisk                   | 15       | 17     | 6.58%   |
| Toshiba                   | 14       | 24     | 6.14%   |
| Crucial                   | 14       | 18     | 6.14%   |
| Unknown                   | 7        | 12     | 3.07%   |
| Hitachi                   | 7        | 7      | 3.07%   |
| Transcend                 | 4        | 4      | 1.75%   |
| A-DATA Technology         | 4        | 4      | 1.75%   |
| SPCC                      | 3        | 3      | 1.32%   |
| SK Hynix                  | 3        | 4      | 1.32%   |
| PLEXTOR                   | 3        | 5      | 1.32%   |
| TAMMUZ                    | 2        | 3      | 0.88%   |
| Silicon Motion            | 2        | 2      | 0.88%   |
| Micron Technology         | 2        | 2      | 0.88%   |
| Intel                     | 2        | 2      | 0.88%   |
| HGST                      | 2        | 2      | 0.88%   |
| China                     | 2        | 2      | 0.88%   |
| ZOTAC                     | 1        | 1      | 0.44%   |
| VIEW                      | 1        | 1      | 0.44%   |
| Realtek Semiconductor     | 1        | 1      | 0.44%   |
| QNIX                      | 1        | 1      | 0.44%   |
| Phison                    | 1        | 2      | 0.44%   |
| PHINOCOM                  | 1        | 1      | 0.44%   |
| OCZ                       | 1        | 2      | 0.44%   |
| Micron/Crucial Technology | 1        | 1      | 0.44%   |
| MARVELL                   | 1        | 1      | 0.44%   |
| LITEON                    | 1        | 1      | 0.44%   |
| LaCie                     | 1        | 1      | 0.44%   |
| KingSpec                  | 1        | 1      | 0.44%   |
| JMicron                   | 1        | 1      | 0.44%   |
| imation                   | 1        | 2      | 0.44%   |
| Hewlett-Packard           | 1        | 1      | 0.44%   |
| GLOWAY                    | 1        | 1      | 0.44%   |
| Fujitsu                   | 1        | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| Toshiba DT01ACA300 3TB            | 6        | 2.18%   |
| Seagate ST500DM002-1BD142 500GB   | 6        | 2.18%   |
| Samsung SSD 850 EVO 120GB         | 4        | 1.45%   |
| Crucial CT500MX500SSD1 500GB      | 4        | 1.45%   |
| Crucial CT240BX500SSD1 240GB      | 4        | 1.45%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 1.09%   |
| WDC WD40EZRZ-00GXCB0 4TB          | 3        | 1.09%   |
| Toshiba DT01ACA200 2TB            | 3        | 1.09%   |
| Toshiba DT01ACA050 500GB          | 3        | 1.09%   |
| Seagate ST3500418AS 500GB         | 3        | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB    | 3        | 1.09%   |
| Seagate ST1000DM010-2EP102 1TB    | 3        | 1.09%   |
| SanDisk SD8SBAT128G1122 128GB SSD | 3        | 1.09%   |
| Crucial CT275MX300SSD4 275GB      | 3        | 1.09%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 2        | 0.73%   |
| WDC WDS120G2G0A-00JH30 120GB SSD  | 2        | 0.73%   |
| WDC WD40EFRX-68WT0N0 4TB          | 2        | 0.73%   |
| WDC WD3200AAJS-00L7A0 320GB       | 2        | 0.73%   |
| WDC WD20EARX-00PASB0 2TB          | 2        | 0.73%   |
| WDC WD10EZEX-22MFCA0 1TB          | 2        | 0.73%   |
| WDC WD10EZEX-08WN4A0 1TB          | 2        | 0.73%   |
| WDC WD10EZEX-00WN4A0 1TB          | 2        | 0.73%   |
| Transcend TS240GSSD220S 240GB     | 2        | 0.73%   |
| TAMMUZ SSD 128GB                  | 2        | 0.73%   |
| Seagate ST2000DM001-1ER164 2TB    | 2        | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB    | 2        | 0.73%   |
| Samsung NVMe SSD Drive 256GB      | 2        | 0.73%   |
| Samsung NVMe SSD Drive 1TB        | 2        | 0.73%   |
| Samsung HD502IJ 500GB             | 2        | 0.73%   |
| Samsung HD322HJ 320GB             | 2        | 0.73%   |
| Crucial CT275MX300SSD1 275GB      | 2        | 0.73%   |
| A-DATA SP900 256GB SSD            | 2        | 0.73%   |
| ZOTAC ZTSSDPG3-480G-GE 480GB      | 1        | 0.36%   |
| WDC WUH721414ALE6L4 14TB          | 1        | 0.36%   |
| WDC WDS500G2B0B 500GB SSD         | 1        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD  | 1        | 0.36%   |
| WDC WDS200T2B0B-00YS70 2TB SSD    | 1        | 0.36%   |
| WDC WDS120G1G0A-00SS50 120GB SSD  | 1        | 0.36%   |
| WDC WDS100T3X0C-00SJG0 1TB        | 1        | 0.36%   |
| WDC WDS100T2X0C-00L350 1TB        | 1        | 0.36%   |
| WDC WDS100T2B0B-00YS70 1TB SSD    | 1        | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD    | 1        | 0.36%   |
| WDC WD80EMAZ-00WJTA0 8TB          | 1        | 0.36%   |
| WDC WD7500BPKT-00PK4T0 752GB      | 1        | 0.36%   |
| WDC WD7500AACS-00D6B0 752GB       | 1        | 0.36%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 1        | 0.36%   |
| WDC WD5000AAKX-60U6AA0 500GB      | 1        | 0.36%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 1        | 0.36%   |
| WDC WD5000AAKX-08U6AA0 500GB      | 1        | 0.36%   |
| WDC WD5000AAKS-55A7B2 500GB       | 1        | 0.36%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 1        | 0.36%   |
| WDC WD5000AAKS-00A7B2 500GB       | 1        | 0.36%   |
| WDC WD40EZRZ-22GXCB0 4TB          | 1        | 0.36%   |
| WDC WD40EZAZ-00SF3B0 4TB          | 1        | 0.36%   |
| WDC WD40EFAX-68JH4N1 4TB          | 1        | 0.36%   |
| WDC WD4004FZWX-00GBGB0 4TB        | 1        | 0.36%   |
| WDC WD4003FFBX-68MU3N0 4TB        | 1        | 0.36%   |
| WDC WD4000AAKS-00TMA0 400GB       | 1        | 0.36%   |
| WDC WD3200AAJS-60B4A0 320GB       | 1        | 0.36%   |
| WDC WD30EZRX-00DC0B0 3TB          | 1        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 45       | 74     | 38.46%  |
| Seagate             | 37       | 51     | 31.62%  |
| Toshiba             | 13       | 20     | 11.11%  |
| Samsung Electronics | 8        | 9      | 6.84%   |
| Hitachi             | 7        | 7      | 5.98%   |
| HGST                | 2        | 2      | 1.71%   |
| Unknown             | 1        | 2      | 0.85%   |
| MARVELL             | 1        | 1      | 0.85%   |
| LaCie               | 1        | 1      | 0.85%   |
| Hewlett-Packard     | 1        | 1      | 0.85%   |
| Fujitsu             | 1        | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 20       | 24     | 22.47%  |
| Crucial             | 14       | 18     | 15.73%  |
| SanDisk             | 13       | 13     | 14.61%  |
| WDC                 | 8        | 12     | 8.99%   |
| Transcend           | 4        | 4      | 4.49%   |
| SPCC                | 3        | 3      | 3.37%   |
| Seagate             | 3        | 4      | 3.37%   |
| A-DATA Technology   | 3        | 3      | 3.37%   |
| TAMMUZ              | 2        | 3      | 2.25%   |
| SK Hynix            | 2        | 3      | 2.25%   |
| PLEXTOR             | 2        | 4      | 2.25%   |
| Intel               | 2        | 2      | 2.25%   |
| China               | 2        | 2      | 2.25%   |
| VIEW                | 1        | 1      | 1.12%   |
| Toshiba             | 1        | 4      | 1.12%   |
| QNIX                | 1        | 1      | 1.12%   |
| PHINOCOM            | 1        | 1      | 1.12%   |
| OCZ                 | 1        | 2      | 1.12%   |
| Micron Technology   | 1        | 1      | 1.12%   |
| LITEON              | 1        | 1      | 1.12%   |
| KingSpec            | 1        | 1      | 1.12%   |
| JMicron             | 1        | 1      | 1.12%   |
| imation             | 1        | 2      | 1.12%   |
| GLOWAY              | 1        | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 89       | 169    | 46.11%  |
| SSD     | 73       | 111    | 37.82%  |
| NVMe    | 25       | 33     | 12.95%  |
| MMC     | 4        | 8      | 2.07%   |
| Unknown | 2        | 2      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 111      | 276    | 76.55%  |
| NVMe | 25       | 33     | 17.24%  |
| SAS  | 5        | 6      | 3.45%   |
| MMC  | 4        | 8      | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 85       | 144    | 48.57%  |
| 0.51-1.0   | 39       | 55     | 22.29%  |
| 1.01-2.0   | 23       | 28     | 13.14%  |
| 3.01-4.0   | 12       | 25     | 6.86%   |
| 2.01-3.0   | 8        | 11     | 4.57%   |
| 4.01-10.0  | 6        | 10     | 3.43%   |
| 10.01-20.0 | 2        | 7      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 27       | 21.6%   |
| 251-500        | 24       | 19.2%   |
| 501-1000       | 20       | 16%     |
| More than 3000 | 12       | 9.6%    |
| 2001-3000      | 12       | 9.6%    |
| 1001-2000      | 12       | 9.6%    |
| 21-50          | 7        | 5.6%    |
| 51-100         | 5        | 4%      |
| 1-20           | 3        | 2.4%    |
| Unknown        | 3        | 2.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 45       | 35.71%  |
| 21-50          | 22       | 17.46%  |
| 101-250        | 13       | 10.32%  |
| 51-100         | 11       | 8.73%   |
| 251-500        | 9        | 7.14%   |
| 501-1000       | 9        | 7.14%   |
| More than 3000 | 6        | 4.76%   |
| 2001-3000      | 6        | 4.76%   |
| Unknown        | 3        | 2.38%   |
| 1001-2000      | 2        | 1.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Desktops | Drives | Percent |
|--------------------------------|----------|--------|---------|
| WDC WD7500AACS-00D6B0 752GB    | 1        | 1      | 11.11%  |
| WDC WD5000AAKX-75U6AA0 500GB   | 1        | 1      | 11.11%  |
| WDC WD1600BEVT-22A23T0 160GB   | 1        | 1      | 11.11%  |
| WDC WD1001FALS-00J7B1 1TB      | 1        | 1      | 11.11%  |
| Seagate ST4000DM000-1F2168 4TB | 1        | 1      | 11.11%  |
| Seagate ST3500418AS 500GB      | 1        | 1      | 11.11%  |
| Seagate ST1000DM003-1CH162 1TB | 1        | 1      | 11.11%  |
| LITEON LMH-128V2M 128GB SSD    | 1        | 1      | 11.11%  |
| HGST HDN726060ALE610 6TB       | 1        | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 44.44%  |
| Seagate | 3        | 3      | 33.33%  |
| LITEON  | 1        | 1      | 11.11%  |
| HGST    | 1        | 1      | 11.11%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 4        | 4      | 50%     |
| Seagate | 3        | 3      | 37.5%   |
| HGST    | 1        | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 6        | 8      | 85.71%  |
| SSD  | 1        | 1      | 14.29%  |

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
| Detected | 87       | 220    | 67.44%  |
| Works    | 35       | 94     | 27.13%  |
| Malfunc  | 7        | 9      | 5.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 84       | 48.28%  |
| AMD                        | 35       | 20.11%  |
| Samsung Electronics        | 16       | 9.2%    |
| ASMedia Technology         | 11       | 6.32%   |
| JMicron Technology         | 9        | 5.17%   |
| Silicon Motion             | 3        | 1.72%   |
| Sandisk                    | 3        | 1.72%   |
| Marvell Technology Group   | 3        | 1.72%   |
| Phison Electronics         | 2        | 1.15%   |
| SK Hynix                   | 1        | 0.57%   |
| Seagate Technology         | 1        | 0.57%   |
| Realtek Semiconductor      | 1        | 0.57%   |
| Micron/Crucial Technology  | 1        | 0.57%   |
| Micron Technology          | 1        | 0.57%   |
| Lite-On Technology         | 1        | 0.57%   |
| Lite-On IT Corp. / Plextor | 1        | 0.57%   |
| ADATA Technology           | 1        | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27       | 11.74%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 5.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10       | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 3.91%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9        | 3.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8        | 3.48%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 3.48%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7        | 3.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7        | 3.04%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7        | 3.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 3.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6        | 2.61%   |
| AMD FCH SATA Controller D                                                               | 6        | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4        | 1.74%   |
| AMD FCH IDE Controller                                                                  | 4        | 1.74%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 1.3%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 1.3%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2        | 0.87%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2        | 0.87%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2        | 0.87%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2        | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2        | 0.87%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 2        | 0.87%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 2        | 0.87%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2        | 0.87%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2        | 0.87%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 2        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 2        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 2        | 0.87%   |
| AMD X399 Series Chipset SATA Controller                                                 | 2        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2        | 0.87%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 2        | 0.87%   |
| AMD SB600 IDE                                                                           | 2        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 0.87%   |
| SK Hynix Gold P31 SSD                                                                   | 1        | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.43%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1        | 0.43%   |
| Silicon Motion Non-Volatile memory controller                                           | 1        | 0.43%   |
| Seagate FireCuda 530 SSD                                                                | 1        | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1        | 0.43%   |
| Samsung XP941 PCIe SSD                                                                  | 1        | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1        | 0.43%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.43%   |
| Samsung NVMe SSD Controller 172Xa/172Xb                                                 | 1        | 0.43%   |
| Samsung Electronics SATA controller                                                     | 1        | 0.43%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.43%   |
| Phison E7 NVMe Controller                                                               | 1        | 0.43%   |
| Phison E12 NVMe Controller                                                              | 1        | 0.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1        | 0.43%   |
| Micron Non-Volatile memory controller                                                   | 1        | 0.43%   |
| Marvell Group 88SE9230 PCIe 2.0 x2 4-port SATA 6 Gb/s RAID Controller                   | 1        | 0.43%   |
| Lite-On Non-Volatile memory controller                                                  | 1        | 0.43%   |
| Lite-On IT Corp. / Plextor M6e PCI Express SSD [Marvell 88SS9183]                       | 1        | 0.43%   |
| JMicron JMB368 IDE controller                                                           | 1        | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 97       | 59.88%  |
| IDE  | 31       | 19.14%  |
| NVMe | 27       | 16.67%  |
| RAID | 6        | 3.7%    |
| SAS  | 1        | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 87       | 71.31%  |
| AMD    | 35       | 28.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz            | 8        | 6.56%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 5        | 4.1%    |
| Intel Core i3-3220 CPU @ 3.30GHz            | 4        | 3.28%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 2.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3        | 2.46%   |
| Intel Core i5-8500 CPU @ 3.00GHz            | 3        | 2.46%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3        | 2.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 2.46%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3        | 2.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 3        | 2.46%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2        | 1.64%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2        | 1.64%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2        | 1.64%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2        | 1.64%   |
| Intel Core i5 CPU 760 @ 2.80GHz             | 2        | 1.64%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 2        | 1.64%   |
| Intel Xeon W-3275M CPU @ 2.50GHz            | 1        | 0.82%   |
| Intel Xeon W-2133 CPU @ 3.60GHz             | 1        | 0.82%   |
| Intel Xeon CPU X3430 @ 2.40GHz              | 1        | 0.82%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1        | 0.82%   |
| Intel Xeon CPU E5-2699 v3 @ 2.30GHz         | 1        | 0.82%   |
| Intel Xeon CPU E5-2696 v4 @ 2.20GHz         | 1        | 0.82%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz         | 1        | 0.82%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 0.82%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1        | 0.82%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz      | 1        | 0.82%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1        | 0.82%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1        | 0.82%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 1        | 0.82%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1        | 0.82%   |
| Intel Pentium CPU G3240 @ 3.10GHz           | 1        | 0.82%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 1        | 0.82%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1        | 0.82%   |
| Intel Core i9-7940X CPU @ 3.10GHz           | 1        | 0.82%   |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1        | 0.82%   |
| Intel Core i9-10900 CPU @ 2.80GHz           | 1        | 0.82%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1        | 0.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1        | 0.82%   |
| Intel Core i7-5960X CPU @ 3.00GHz           | 1        | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1        | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1        | 0.82%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 1        | 0.82%   |
| Intel Core i5-7600 CPU @ 3.50GHz            | 1        | 0.82%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1        | 0.82%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1        | 0.82%   |
| Intel Core i5-4670 CPU @ 3.40GHz            | 1        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1        | 0.82%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 1        | 0.82%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1        | 0.82%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1        | 0.82%   |
| Intel Core i5 CPU 750 @ 2.67GHz             | 1        | 0.82%   |
| Intel Core i3-4330 CPU @ 3.50GHz            | 1        | 0.82%   |
| Intel Core i3-4170 CPU @ 3.70GHz            | 1        | 0.82%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 1        | 0.82%   |
| Intel Core i3-4150 CPU @ 3.50GHz            | 1        | 0.82%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz       | 1        | 0.82%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 1        | 0.82%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1        | 0.82%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 1        | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 28       | 22.95%  |
| AMD Ryzen 5             | 12       | 9.84%   |
| Intel Core i7           | 10       | 8.2%    |
| Intel Xeon              | 9        | 7.38%   |
| Intel Core i3           | 8        | 6.56%   |
| Intel Core i9           | 6        | 4.92%   |
| Intel Core 2 Quad       | 6        | 4.92%   |
| Intel Celeron           | 5        | 4.1%    |
| AMD Ryzen 7             | 5        | 4.1%    |
| AMD Ryzen 3             | 4        | 3.28%   |
| Other                   | 3        | 2.46%   |
| Intel Pentium           | 3        | 2.46%   |
| AMD Ryzen Threadripper  | 3        | 2.46%   |
| Intel Pentium Dual-Core | 2        | 1.64%   |
| Intel Pentium 4         | 2        | 1.64%   |
| Intel Core m3           | 2        | 1.64%   |
| AMD Ryzen 9             | 2        | 1.64%   |
| AMD A8                  | 2        | 1.64%   |
| AMD A10                 | 2        | 1.64%   |
| Intel Pentium Gold      | 1        | 0.82%   |
| Intel Core 2 Duo        | 1        | 0.82%   |
| Intel Core 2            | 1        | 0.82%   |
| AMD Ryzen 5 PRO         | 1        | 0.82%   |
| AMD Phenom II X6        | 1        | 0.82%   |
| AMD Phenom              | 1        | 0.82%   |
| AMD Athlon II X2        | 1        | 0.82%   |
| AMD Athlon 64 X2        | 1        | 0.82%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 51       | 41.8%   |
| 2      | 26       | 21.31%  |
| 6      | 16       | 13.11%  |
| 8      | 12       | 9.84%   |
| 16     | 3        | 2.46%   |
| 12     | 3        | 2.46%   |
| 10     | 3        | 2.46%   |
| 1      | 2        | 1.64%   |
| 32     | 1        | 0.82%   |
| 28     | 1        | 0.82%   |
| 22     | 1        | 0.82%   |
| 20     | 1        | 0.82%   |
| 18     | 1        | 0.82%   |
| 14     | 1        | 0.82%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 99.18%  |
| 2      | 1        | 0.82%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 63       | 51.64%  |
| 2      | 59       | 48.36%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 120      | 97.56%  |
| Unknown        | 3        | 2.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 19       | 15.45%  |
| 0x306a9    | 15       | 12.2%   |
| 0x306c3    | 13       | 10.57%  |
| 0x906ea    | 6        | 4.88%   |
| 0x906e9    | 6        | 4.88%   |
| 0x106e5    | 4        | 3.25%   |
| 0x1067a    | 4        | 3.25%   |
| 0x0800820d | 4        | 3.25%   |
| 0x08001138 | 4        | 3.25%   |
| 0x08001137 | 4        | 3.25%   |
| 0x906ed    | 3        | 2.44%   |
| 0x6fb      | 3        | 2.44%   |
| 0x306f2    | 3        | 2.44%   |
| 0x206a7    | 3        | 2.44%   |
| 0xa0655    | 2        | 1.63%   |
| 0x906ec    | 2        | 1.63%   |
| 0x90672    | 2        | 1.63%   |
| 0x806e9    | 2        | 1.63%   |
| 0x506e3    | 2        | 1.63%   |
| 0x50654    | 2        | 1.63%   |
| 0x08701021 | 2        | 1.63%   |
| 0x0810100b | 2        | 1.63%   |
| 0xf49      | 1        | 0.81%   |
| 0x706a8    | 1        | 0.81%   |
| 0x406f1    | 1        | 0.81%   |
| 0x306e4    | 1        | 0.81%   |
| 0x0a201009 | 1        | 0.81%   |
| 0x08701013 | 1        | 0.81%   |
| 0x08600106 | 1        | 0.81%   |
| 0x08301025 | 1        | 0.81%   |
| 0x08108109 | 1        | 0.81%   |
| 0x08101016 | 1        | 0.81%   |
| 0x08001126 | 1        | 0.81%   |
| 0x06003106 | 1        | 0.81%   |
| 0x06001119 | 1        | 0.81%   |
| 0x03000027 | 1        | 0.81%   |
| 0x010000c8 | 1        | 0.81%   |
| 0x01000095 | 1        | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| KabyLake         | 19       | 15.57%  |
| IvyBridge        | 17       | 13.93%  |
| Haswell          | 17       | 13.93%  |
| Zen              | 15       | 12.3%   |
| Penryn           | 7        | 5.74%   |
| Skylake          | 6        | 4.92%   |
| Zen+             | 5        | 4.1%    |
| Zen 2            | 5        | 4.1%    |
| Nehalem          | 4        | 3.28%   |
| Core             | 4        | 3.28%   |
| SandyBridge      | 3        | 2.46%   |
| K10              | 3        | 2.46%   |
| Zen 3            | 2        | 1.64%   |
| Steamroller      | 2        | 1.64%   |
| NetBurst         | 2        | 1.64%   |
| CometLake        | 2        | 1.64%   |
| Unknown          | 2        | 1.64%   |
| Silvermont       | 1        | 0.82%   |
| Piledriver       | 1        | 0.82%   |
| K8 Hammer        | 1        | 0.82%   |
| K10 Llano        | 1        | 0.82%   |
| Goldmont plus    | 1        | 0.82%   |
| Broadwell        | 1        | 0.82%   |
| Alderlake Hybrid | 1        | 0.82%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Desktops | Percent |
|-------------------|----------|---------|
| Nvidia            | 68       | 50%     |
| Intel             | 40       | 29.41%  |
| AMD               | 27       | 19.85%  |
| ASPEED Technology | 1        | 0.74%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9        | 6.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 8        | 5.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 5.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 6        | 4.41%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 3.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 4        | 2.94%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 4        | 2.94%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 3        | 2.21%   |
| Nvidia GF108 [GeForce GT 440]                                               | 3        | 2.21%   |
| Nvidia GT218 [GeForce 210]                                                  | 2        | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2        | 1.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 1.47%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.47%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2        | 1.47%   |
| Nvidia GM107 [GeForce GTX 750]                                              | 2        | 1.47%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2        | 1.47%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 2        | 1.47%   |
| Nvidia GF104 [GeForce GTX 460]                                              | 2        | 1.47%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 1.47%   |
| Nvidia G98 [GeForce 9300 GS]                                                | 2        | 1.47%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 1.47%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 2        | 1.47%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 2        | 1.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.74%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2080]                                             | 1        | 0.74%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1        | 0.74%   |
| Nvidia TU102 [TITAN RTX]                                                    | 1        | 0.74%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 1        | 0.74%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 1        | 0.74%   |
| Nvidia NV43 [GeForce 6600]                                                  | 1        | 0.74%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1        | 0.74%   |
| Nvidia GT200b [GeForce GTX 275]                                             | 1        | 0.74%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.74%   |
| Nvidia GP107GL [Quadro P400]                                                | 1        | 0.74%   |
| Nvidia GP106GL [Quadro P2200]                                               | 1        | 0.74%   |
| Nvidia GP106GL [Quadro P2000]                                               | 1        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1060 6GB]                                         | 1        | 0.74%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1        | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1        | 0.74%   |
| Nvidia GM200 [GeForce GTX TITAN X]                                          | 1        | 0.74%   |
| Nvidia GK106GL [Quadro K4000]                                               | 1        | 0.74%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 1        | 0.74%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 1        | 0.74%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 1        | 0.74%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1        | 0.74%   |
| Nvidia GF106GL [Quadro 2000]                                                | 1        | 0.74%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 1        | 0.74%   |
| Nvidia GA106 [Geforce RTX 3050]                                             | 1        | 0.74%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1        | 0.74%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1        | 0.74%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 0.74%   |
| Nvidia G98 [GeForce 8400 GS Rev. 2]                                         | 1        | 0.74%   |
| Intel UHD Graphics 615                                                      | 1        | 0.74%   |
| Intel HD Graphics 630                                                       | 1        | 0.74%   |
| Intel HD Graphics 615                                                       | 1        | 0.74%   |
| Intel HD Graphics 610                                                       | 1        | 0.74%   |
| Intel HD Graphics 530                                                       | 1        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 65       | 52.85%  |
| 1 x Intel      | 29       | 23.58%  |
| 1 x AMD        | 23       | 18.7%   |
| AMD + Nvidia   | 2        | 1.63%   |
| 2 x AMD        | 1        | 0.81%   |
| Intel + Nvidia | 1        | 0.81%   |
| Intel + AMD    | 1        | 0.81%   |
| 1 x ASPEED     | 1        | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 77       | 62.6%   |
| Proprietary | 42       | 34.15%  |
| Unknown     | 4        | 3.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 45       | 36.59%  |
| 0.51-1.0   | 20       | 16.26%  |
| 1.01-2.0   | 17       | 13.82%  |
| 7.01-8.0   | 9        | 7.32%   |
| 0.01-0.5   | 9        | 7.32%   |
| 3.01-4.0   | 7        | 5.69%   |
| 8.01-16.0  | 6        | 4.88%   |
| 2.01-3.0   | 4        | 3.25%   |
| 5.01-6.0   | 3        | 2.44%   |
| 16.01-24.0 | 2        | 1.63%   |
| 4.01-5.0   | 1        | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 23       | 19.66%  |
| Goldstar             | 23       | 19.66%  |
| Unknown              | 10       | 8.55%   |
| Philips              | 6        | 5.13%   |
| LG Electronics       | 6        | 5.13%   |
| OUT                  | 5        | 4.27%   |
| AOC                  | 5        | 4.27%   |
| Hewlett-Packard      | 4        | 3.42%   |
| BenQ                 | 3        | 2.56%   |
| PRISM+               | 2        | 1.71%   |
| MStar                | 2        | 1.71%   |
| JRY                  | 2        | 1.71%   |
| Dell                 | 2        | 1.71%   |
| Ancor Communications | 2        | 1.71%   |
| Unknown (ADE)        | 1        | 0.85%   |
| TopView              | 1        | 0.85%   |
| TGL                  | 1        | 0.85%   |
| SIS                  | 1        | 0.85%   |
| Sanyo                | 1        | 0.85%   |
| RTK                  | 1        | 0.85%   |
| RAT                  | 1        | 0.85%   |
| PBK                  | 1        | 0.85%   |
| ORM                  | 1        | 0.85%   |
| OOO                  | 1        | 0.85%   |
| NME                  | 1        | 0.85%   |
| MON                  | 1        | 0.85%   |
| LYC                  | 1        | 0.85%   |
| Lenovo               | 1        | 0.85%   |
| JCH                  | 1        | 0.85%   |
| HVT                  | 1        | 0.85%   |
| Denver               | 1        | 0.85%   |
| CVT                  | 1        | 0.85%   |
| CND                  | 1        | 0.85%   |
| CHR                  | 1        | 0.85%   |
| ALP                  | 1        | 0.85%   |
| ADP                  | 1        | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 4        | 3.28%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                          | 3        | 2.46%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 3        | 2.46%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1872x1053mm 84.6-inch | 2        | 1.64%   |
| JRY Digital JRY0215 1920x1080 340x255mm 16.7-inch                       | 2        | 1.64%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                              | 1        | 0.82%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                      | 1        | 0.82%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                   | 1        | 0.82%   |
| Unknown LCD Monitor OUT Digital 3200x1080                               | 1        | 0.82%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                       | 1        | 0.82%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                           | 1        | 0.82%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                         | 1        | 0.82%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                            | 1        | 0.82%   |
| Unknown LCD Monitor Digital Projection Limited DP                       | 1        | 0.82%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                              | 1        | 0.82%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                          | 1        | 0.82%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch       | 1        | 0.82%   |
| TopView TOPSYNC TOP049B 2560x1440 597x336mm 27.0-inch                   | 1        | 0.82%   |
| TGL TGL A190 TGL0908 1280x1024 376x301mm 19.0-inch                      | 1        | 0.82%   |
| SIS DV 24 TV SIS0330 1920x1080 930x530mm 42.1-inch                      | 1        | 0.82%   |
| Sanyo LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch                 | 1        | 0.82%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1        | 0.82%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 700x390mm 31.5-inch       | 1        | 0.82%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch    | 1        | 0.82%   |
| Samsung Electronics SyncMaster SAM03F3 1920x1200 518x324mm 24.1-inch    | 1        | 0.82%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 800x330mm 34.1-inch       | 1        | 0.82%   |
| Samsung Electronics S32E511 SAM0D11 1920x1080 698x392mm 31.5-inch       | 1        | 0.82%   |
| Samsung Electronics S27D850 SAM0BC7 2560x1440 598x336mm 27.0-inch       | 1        | 0.82%   |
| Samsung Electronics S27B240 SAM08EA 1920x1080 598x336mm 27.0-inch       | 1        | 0.82%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1        | 0.82%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                    | 1        | 0.82%   |
| Samsung Electronics LCD Monitor SMBX2440 1920x1080                      | 1        | 0.82%   |
| Samsung Electronics LCD Monitor SAM0910 1920x1080                       | 1        | 0.82%   |
| Samsung Electronics LCD Monitor S24E510C 1920x1080                      | 1        | 0.82%   |
| Samsung Electronics LCD Monitor S24D300 1680x1050                       | 1        | 0.82%   |
| Samsung Electronics LCD Monitor LS32A70 3840x2160                       | 1        | 0.82%   |
| Samsung Electronics LCD Monitor C32JG5x 2560x1440                       | 1        | 0.82%   |
| Samsung Electronics LCD Monitor C27F591 1440x900                        | 1        | 0.82%   |
| Samsung Electronics LC32G5xT SAM7089 2560x1440 700x400mm 31.7-inch      | 1        | 0.82%   |
| Samsung Electronics C49J89x SAM0F20 3840x1080 1196x336mm 48.9-inch      | 1        | 0.82%   |
| Samsung Electronics C32JG5x SAM0FE0 2560x1440 700x390mm 31.5-inch       | 1        | 0.82%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch       | 1        | 0.82%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 1        | 0.82%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                  | 1        | 0.82%   |
| RAT VGA RAT0215 1920x1080 368x207mm 16.6-inch                           | 1        | 0.82%   |
| PRISM+ ULTRON 2754C INN0027 1920x1080 598x337mm 27.0-inch               | 1        | 0.82%   |
| PRISM+ ULTRON 2435V INN2380 1920x1080 530x300mm 24.0-inch               | 1        | 0.82%   |
| Philips PHL 277E7 PHLC0FE 1920x1080 600x340mm 27.2-inch                 | 1        | 0.82%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 1        | 0.82%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 600x340mm 27.2-inch                 | 1        | 0.82%   |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch                 | 1        | 0.82%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch                 | 1        | 0.82%   |
| Philips LCD Monitor PHL 271E9 1920x1080                                 | 1        | 0.82%   |
| Philips LCD Monitor PHL 224E5 1920x1080                                 | 1        | 0.82%   |
| PBK PBM-2130DP PBK6161 1600x1200 432x324mm 21.3-inch                    | 1        | 0.82%   |
| OUT HDMI OUT0215 1920x1080 426x239mm 19.2-inch                          | 1        | 0.82%   |
| OUT Analog OUT0270 1920x1080 368x207mm 16.6-inch                        | 1        | 0.82%   |
| ORM Monitor ORM1601 1280x1024                                           | 1        | 0.82%   |
| OOO 15.6' monitor OOO0001 1920x1080 409x230mm 18.5-inch                 | 1        | 0.82%   |
| NME 202M NME1021 1680x1050 380x290mm 18.8-inch                          | 1        | 0.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 59       | 50.43%  |
| 2560x1440 (QHD)    | 13       | 11.11%  |
| 3840x2160 (4K)     | 12       | 10.26%  |
| 1280x1024 (SXGA)   | 8        | 6.84%   |
| 1920x1200 (WUXGA)  | 5        | 4.27%   |
| 1680x1050 (WSXGA+) | 5        | 4.27%   |
| Unknown            | 3        | 2.56%   |
| 3440x1440          | 2        | 1.71%   |
| 1440x900 (WXGA+)   | 2        | 1.71%   |
| 4880x2560          | 1        | 0.85%   |
| 3840x1600          | 1        | 0.85%   |
| 3840x1080          | 1        | 0.85%   |
| 3286x1080          | 1        | 0.85%   |
| 3200x1080          | 1        | 0.85%   |
| 2560x1080          | 1        | 0.85%   |
| 1600x900 (HD+)     | 1        | 0.85%   |
| 1600x1200          | 1        | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 28       | 24.35%  |
| 27      | 16       | 13.91%  |
| 21      | 15       | 13.04%  |
| 23      | 11       | 9.57%   |
| 16      | 8        | 6.96%   |
| 24      | 6        | 5.22%   |
| 31      | 5        | 4.35%   |
| 19      | 5        | 4.35%   |
| 34      | 3        | 2.61%   |
| 84      | 2        | 1.74%   |
| 25      | 2        | 1.74%   |
| 22      | 2        | 1.74%   |
| 20      | 2        | 1.74%   |
| 18      | 2        | 1.74%   |
| 17      | 2        | 1.74%   |
| 49      | 1        | 0.87%   |
| 46      | 1        | 0.87%   |
| 42      | 1        | 0.87%   |
| 39      | 1        | 0.87%   |
| 37      | 1        | 0.87%   |
| 33      | 1        | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 31       | 27.68%  |
| Unknown     | 28       | 25%     |
| 401-500     | 22       | 19.64%  |
| 301-350     | 8        | 7.14%   |
| 601-700     | 6        | 5.36%   |
| 351-400     | 6        | 5.36%   |
| 701-800     | 4        | 3.57%   |
| 801-900     | 2        | 1.79%   |
| 1501-2000   | 2        | 1.79%   |
| 1001-1500   | 2        | 1.79%   |
| 901-1000    | 1        | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 62       | 54.87%  |
| Unknown | 26       | 23.01%  |
| 4/3     | 8        | 7.08%   |
| 5/4     | 6        | 5.31%   |
| 16/10   | 5        | 4.42%   |
| 21/9    | 4        | 3.54%   |
| 32/9    | 1        | 0.88%   |
| 3/2     | 1        | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 30       | 26.55%  |
| Unknown        | 28       | 24.78%  |
| 301-350        | 16       | 14.16%  |
| 351-500        | 10       | 8.85%   |
| 151-200        | 8        | 7.08%   |
| 131-140        | 6        | 5.31%   |
| 251-300        | 4        | 3.54%   |
| 501-1000       | 4        | 3.54%   |
| 141-150        | 3        | 2.65%   |
| More than 1000 | 2        | 1.77%   |
| 111-120        | 2        | 1.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 44       | 38.94%  |
| Unknown | 28       | 24.78%  |
| 101-120 | 27       | 23.89%  |
| 121-160 | 11       | 9.73%   |
| 1-50    | 2        | 1.77%   |
| 161-240 | 1        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 103      | 84.43%  |
| 2     | 13       | 10.66%  |
| 0     | 6        | 4.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 91       | 57.59%  |
| Intel                    | 39       | 24.68%  |
| Qualcomm Atheros         | 6        | 3.8%    |
| Ralink Technology        | 4        | 2.53%   |
| Ralink                   | 3        | 1.9%    |
| Broadcom                 | 3        | 1.9%    |
| MEDIATEK                 | 2        | 1.27%   |
| Marvell Technology Group | 2        | 1.27%   |
| Exar                     | 2        | 1.27%   |
| U-Blox                   | 1        | 0.63%   |
| PEAK-System Technik      | 1        | 0.63%   |
| D-Link                   | 1        | 0.63%   |
| Broadcom Limited         | 1        | 0.63%   |
| ASIX Electronics         | 1        | 0.63%   |
| American Megatrends      | 1        | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79       | 42.02%  |
| Intel I211 Gigabit Network Connection                             | 6        | 3.19%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 2.66%   |
| Intel Wi-Fi 6 AX200                                               | 4        | 2.13%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3        | 1.6%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 1.6%    |
| Intel Ethernet Controller I225-V                                  | 3        | 1.6%    |
| Intel Ethernet Connection (2) I219-V                              | 3        | 1.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 1.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2        | 1.06%   |
| Realtek 802.11n NIC                                               | 2        | 1.06%   |
| Realtek 802.11ac NIC                                              | 2        | 1.06%   |
| Ralink MT7601U Wireless Adapter                                   | 2        | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 1.06%   |
| Intel Wireless 3165                                               | 2        | 1.06%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.06%   |
| Intel Ethernet Controller X550                                    | 2        | 1.06%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.06%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2        | 1.06%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 2        | 1.06%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.06%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.06%   |
| Exar XR21V1410 USB-UART IC                                        | 2        | 1.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2        | 1.06%   |
| U-Blox [u-blox 7]                                                 | 1        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1        | 0.53%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 1        | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1        | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.53%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.53%   |
| Ralink RT5572 Wireless Adapter                                    | 1        | 0.53%   |
| Ralink RT5372 Wireless Adapter                                    | 1        | 0.53%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                         | 1        | 0.53%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 1        | 0.53%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 1        | 0.53%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1        | 0.53%   |
| PEAK-System Technik Network controller                            | 1        | 0.53%   |
| MediaTek WiFi                                                     | 1        | 0.53%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 1        | 0.53%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.53%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.53%   |
| Intel Wireless-AC 9260                                            | 1        | 0.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1        | 0.53%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 1        | 0.53%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.53%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.53%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.53%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.53%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 15       | 34.88%  |
| Intel                 | 15       | 34.88%  |
| Ralink Technology     | 4        | 9.3%    |
| Ralink                | 3        | 6.98%   |
| MEDIATEK              | 2        | 4.65%   |
| Broadcom              | 2        | 4.65%   |
| Qualcomm Atheros      | 1        | 2.33%   |
| D-Link                | 1        | 2.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                    | 4        | 9.09%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 3        | 6.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3        | 6.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 2        | 4.55%   |
| Realtek 802.11n NIC                                                    | 2        | 4.55%   |
| Realtek 802.11ac NIC                                                   | 2        | 4.55%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 4.55%   |
| Intel Wireless 3165                                                    | 2        | 4.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 4.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2        | 4.55%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 2        | 4.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                     | 2        | 4.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1        | 2.27%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 1        | 2.27%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 1        | 2.27%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 1        | 2.27%   |
| Ralink RT5572 Wireless Adapter                                         | 1        | 2.27%   |
| Ralink RT5372 Wireless Adapter                                         | 1        | 2.27%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                              | 1        | 2.27%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                              | 1        | 2.27%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                   | 1        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 1        | 2.27%   |
| MediaTek WiFi                                                          | 1        | 2.27%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter          | 1        | 2.27%   |
| Intel Wireless-AC 9260                                                 | 1        | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                 | 1        | 2.27%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 1        | 2.27%   |
| D-Link DWA-182 Wireless AC Dualband Adapter(rev.C) [Realtek RTL8812AU] | 1        | 2.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 88       | 66.17%  |
| Intel                    | 34       | 25.56%  |
| Qualcomm Atheros         | 5        | 3.76%   |
| Marvell Technology Group | 2        | 1.5%    |
| Broadcom Limited         | 1        | 0.75%   |
| Broadcom                 | 1        | 0.75%   |
| ASIX Electronics         | 1        | 0.75%   |
| American Megatrends      | 1        | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79       | 56.43%  |
| Intel I211 Gigabit Network Connection                             | 6        | 4.29%   |
| Intel Ethernet Connection (7) I219-V                              | 5        | 3.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 2.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3        | 2.14%   |
| Intel Ethernet Controller I225-V                                  | 3        | 2.14%   |
| Intel Ethernet Connection (2) I219-V                              | 3        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3        | 2.14%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2        | 1.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2        | 1.43%   |
| Intel I210 Gigabit Network Connection                             | 2        | 1.43%   |
| Intel Ethernet Controller X550                                    | 2        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 2        | 1.43%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 1.43%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 1.43%   |
| Intel 82579V Gigabit Network Connection                           | 2        | 1.43%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 1.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1        | 0.71%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.71%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1        | 0.71%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1        | 0.71%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.71%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1        | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.71%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.71%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 1        | 0.71%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.71%   |
| Intel 82575EB Gigabit Network Connection                          | 1        | 0.71%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.71%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express   | 1        | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.71%   |
| American Megatrends Virtual Ethernet                              | 1        | 0.71%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 122      | 73.94%  |
| WiFi     | 39       | 23.64%  |
| Modem    | 3        | 1.82%   |
| Unknown  | 1        | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 112      | 84.21%  |
| WiFi     | 21       | 15.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 88       | 72.13%  |
| 2     | 28       | 22.95%  |
| 3     | 4        | 3.28%   |
| 5     | 1        | 0.82%   |
| 4     | 1        | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 122      | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Cambridge Silicon Radio | 25       | 53.19%  |
| Intel                   | 14       | 29.79%  |
| Broadcom                | 3        | 6.38%   |
| Realtek Semiconductor   | 2        | 4.26%   |
| ASUSTek Computer        | 2        | 4.26%   |
| Foxconn / Hon Hai       | 1        | 2.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 25       | 53.19%  |
| Intel AX200 Bluetooth                                 | 4        | 8.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3        | 6.38%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 6.38%   |
| Realtek Bluetooth Radio                               | 2        | 4.26%   |
| Intel Wireless-AC 3168 Bluetooth                      | 2        | 4.26%   |
| Intel Bluetooth wireless interface                    | 2        | 4.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1        | 2.13%   |
| Intel AX210 Bluetooth                                 | 1        | 2.13%   |
| Intel AX201 Bluetooth                                 | 1        | 2.13%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 2.13%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1        | 2.13%   |
| ASUS Bluetooth Radio                                  | 1        | 2.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Intel                | 86       | 42.57%  |
| Nvidia               | 63       | 31.19%  |
| AMD                  | 45       | 22.28%  |
| C-Media Electronics  | 2        | 0.99%   |
| ASUSTek Computer     | 2        | 0.99%   |
| Medeli Electronics   | 1        | 0.5%    |
| JMTek                | 1        | 0.5%    |
| Giga-Byte Technology | 1        | 0.5%    |
| Fry's Electronics    | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13       | 5.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 13       | 5.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10       | 4.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10       | 4.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9        | 3.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9        | 3.95%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8        | 3.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7        | 3.07%   |
| Intel 200 Series PCH HD Audio                                                                     | 7        | 3.07%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7        | 3.07%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6        | 2.63%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6        | 2.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6        | 2.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4        | 1.75%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4        | 1.75%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 4        | 1.75%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4        | 1.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4        | 1.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4        | 1.75%   |
| AMD FCH Azalia Controller                                                                         | 4        | 1.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4        | 1.75%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 3        | 1.32%   |
| Nvidia High Definition Audio Controller                                                           | 3        | 1.32%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 3        | 1.32%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3        | 1.32%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3        | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3        | 1.32%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3        | 1.32%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2        | 0.88%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2        | 0.88%   |
| Nvidia GF104 High Definition Audio Controller                                                     | 2        | 0.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2        | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 2        | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2        | 0.88%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2        | 0.88%   |
| ASUSTek Computer USB Audio                                                                        | 2        | 0.88%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2        | 0.88%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2        | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1        | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1        | 0.44%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1        | 0.44%   |
| Nvidia GM200 High Definition Audio                                                                | 1        | 0.44%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1        | 0.44%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1        | 0.44%   |
| Nvidia Audio device                                                                               | 1        | 0.44%   |
| Medeli Electronics USB Audio Device                                                               | 1        | 0.44%   |
| JMTek GS3                                                                                         | 1        | 0.44%   |
| Intel Lewisburg MROM 0                                                                            | 1        | 0.44%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1        | 0.44%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 1        | 0.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1        | 0.44%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 1        | 0.44%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 1        | 0.44%   |
| Giga-Byte Technology USB Audio                                                                    | 1        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 35       | 71.43%  |
| Unknown             | 4        | 8.16%   |
| Kingston            | 3        | 6.12%   |
| Team                | 2        | 4.08%   |
| SK Hynix            | 2        | 4.08%   |
| Klevv               | 1        | 2.04%   |
| imation             | 1        | 2.04%   |
| Crucial             | 1        | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Desktops | Percent |
|------------------------------------------------------------|----------|---------|
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s     | 5        | 8.47%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s        | 3        | 5.08%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s        | 3        | 5.08%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s       | 3        | 5.08%   |
| Samsung RAM M378B5273CH0-CH9 4096MB DIMM DDR3 1867MT/s     | 2        | 3.39%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s        | 2        | 3.39%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s        | 2        | 3.39%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s        | 2        | 3.39%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s       | 2        | 3.39%   |
| Samsung RAM M378A2K43CB1-CTD 16GB DIMM DDR4 2667MT/s       | 2        | 3.39%   |
| Samsung RAM M378A2K43BB1-CRC 16384MB DIMM DDR4 3200MT/s    | 2        | 3.39%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s        | 2        | 3.39%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s        | 2        | 3.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s               | 1        | 1.69%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 1        | 1.69%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1        | 1.69%   |
| Unknown RAM Module 1024MB DIMM SDRAM                       | 1        | 1.69%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s         | 1        | 1.69%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s      | 1        | 1.69%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s         | 1        | 1.69%   |
| SK Hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s    | 1        | 1.69%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s       | 1        | 1.69%   |
| Samsung RAM Module 32GB DIMM DDR4 2933MT/s                 | 1        | 1.69%   |
| Samsung RAM Module 16GB DIMM DDR4 2400MT/s                 | 1        | 1.69%   |
| Samsung RAM M386A8K40CM2-CTD 64GB DIMM DDR4 2666MT/s       | 1        | 1.69%   |
| Samsung RAM M378B5673GB0-CH9 2GB DIMM 1333MT/s             | 1        | 1.69%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s        | 1        | 1.69%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s        | 1        | 1.69%   |
| Samsung RAM M378B1G73EB0-CK0 8GB DIMM DDR3 1600MT/s        | 1        | 1.69%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 2400MT/s        | 1        | 1.69%   |
| Samsung RAM M378A5143EB1-CPB 4GB DIMM DDR4 2400MT/s        | 1        | 1.69%   |
| Samsung RAM M378A4G43AB2-CVF 32GB DIMM DDR4 2933MT/s       | 1        | 1.69%   |
| Samsung RAM M378A2G43MX3-CTD 16GB DIMM DDR4 3466MT/s       | 1        | 1.69%   |
| Samsung RAM M378A1G43EB1-CRC 8192MB DIMM DDR4 2400MT/s     | 1        | 1.69%   |
| Klevv RAM KD48GU88C-26N1900 8GB DIMM DDR4 2667MT/s         | 1        | 1.69%   |
| Kingston RAM CL16-18-18 D4-3200 16GB DIMM DDR4 3200MT/s    | 1        | 1.69%   |
| Kingston RAM 9905678-027.A00G 8GB DIMM DDR4 2133MT/s       | 1        | 1.69%   |
| Kingston RAM 9905625-066.A00G 16GB DIMM DDR4 2667MT/s      | 1        | 1.69%   |
| imation RAM Module 16384MB DIMM DDR4 2667MT/s              | 1        | 1.69%   |
| Crucial RAM CT16G4DFD8266.M16FD 16384MB DIMM DDR4 2667MT/s | 1        | 1.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 63.04%  |
| DDR3    | 14       | 30.43%  |
| SDRAM   | 2        | 4.35%   |
| Unknown | 1        | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| DIMM | 46       | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 16       | 30.77%  |
| 4096  | 13       | 25%     |
| 16384 | 12       | 23.08%  |
| 32768 | 6        | 11.54%  |
| 2048  | 3        | 5.77%   |
| 65536 | 1        | 1.92%   |
| 1024  | 1        | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3200    | 8        | 14.04%  |
| 2667    | 8        | 14.04%  |
| 1600    | 7        | 12.28%  |
| 3500    | 5        | 8.77%   |
| 2400    | 4        | 7.02%   |
| 2133    | 4        | 7.02%   |
| 3466    | 3        | 5.26%   |
| 1866    | 3        | 5.26%   |
| 1800    | 3        | 5.26%   |
| 3400    | 2        | 3.51%   |
| 2933    | 2        | 3.51%   |
| 2666    | 2        | 3.51%   |
| 1867    | 2        | 3.51%   |
| 1333    | 2        | 3.51%   |
| Unknown | 2        | 3.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Canon               | 3        | 50%     |
| Seiko Epson         | 1        | 16.67%  |
| Samsung Electronics | 1        | 16.67%  |
| Brother Industries  | 1        | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Seiko Epson L222 Series | 1        | 16.67%  |
| Samsung CLX-3180 Series | 1        | 16.67%  |
| Canon PIXMA MP280       | 1        | 16.67%  |
| Canon G4010 series      | 1        | 16.67%  |
| Canon E560 series       | 1        | 16.67%  |
| Brother DCP-T310        | 1        | 16.67%  |

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
| Sunplus Innovation Technology | 3        | 25%     |
| Samsung Electronics           | 2        | 16.67%  |
| Logitech                      | 2        | 16.67%  |
| lihappe8                      | 2        | 16.67%  |
| Z-Star Microelectronics       | 1        | 8.33%   |
| LG Electronics                | 1        | 8.33%   |
| Canon                         | 1        | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung Galaxy A5 (MTP)                               | 2        | 16.67%  |
| lihappe8 USB 2.0 Camera                               | 2        | 16.67%  |
| Z-Star Vimicro USB Camera (Altair)                    | 1        | 8.33%   |
| Sunplus UHD4K                                         | 1        | 8.33%   |
| Sunplus Integrated_Webcam_HD                          | 1        | 8.33%   |
| Sunplus ABKO APC930 QHD WEBCAM                        | 1        | 8.33%   |
| Logitech Webcam C110                                  | 1        | 8.33%   |
| Logitech C922 Pro Stream Webcam                       | 1        | 8.33%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 8.33%   |
| Canon Digital Camera                                  | 1        | 8.33%   |

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
| 0     | 101      | 81.45%  |
| 1     | 17       | 13.71%  |
| 2     | 4        | 3.23%   |
| 5     | 1        | 0.81%   |
| 3     | 1        | 0.81%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 29.63%  |
| Graphics card            | 6        | 22.22%  |
| Unassigned class         | 5        | 18.52%  |
| Camera                   | 3        | 11.11%  |
| Net/ethernet             | 2        | 7.41%   |
| Communication controller | 2        | 7.41%   |
| Network                  | 1        | 3.7%    |

