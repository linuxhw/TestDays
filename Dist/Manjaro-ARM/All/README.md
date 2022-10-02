Manjaro-ARM - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Manjaro-ARM.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro-ARM/Desktop/README.md) and [notebooks](/Dist/Manjaro-ARM/Notebook/README.md).

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

Total: 114

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc3501546b](https://linux-hardware.org/?probe=bc3501546b) | Sep 28, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc6ffac174](https://linux-hardware.org/?probe=bc6ffac174) | Sep 11, 2022 |
| Unknown       | Unknown                     | Soc         | [6e8246d8bc](https://linux-hardware.org/?probe=6e8246d8bc) | Sep 05, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [533e62b70d](https://linux-hardware.org/?probe=533e62b70d) | Aug 20, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2b238b3dc7](https://linux-hardware.org/?probe=2b238b3dc7) | Aug 19, 2022 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [5f5c134bd6](https://linux-hardware.org/?probe=5f5c134bd6) | Aug 14, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [54465a49f5](https://linux-hardware.org/?probe=54465a49f5) | Aug 09, 2022 |
| Pine Micro... | Pine64 PinePhonePro (DT)    | Phone       | [7b62ba2ec4](https://linux-hardware.org/?probe=7b62ba2ec4) | Jul 31, 2022 |
| Unknown       | Beelink GT1                 | Soc         | [2e00352c95](https://linux-hardware.org/?probe=2e00352c95) | Jul 25, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8e2855140c](https://linux-hardware.org/?probe=8e2855140c) | Jul 24, 2022 |
| Unknown       | Unknown                     | Soc         | [ec9eb5536d](https://linux-hardware.org/?probe=ec9eb5536d) | Jul 18, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [03fca40d38](https://linux-hardware.org/?probe=03fca40d38) | Jul 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a9a3470242](https://linux-hardware.org/?probe=a9a3470242) | Jun 19, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8226efcb30](https://linux-hardware.org/?probe=8226efcb30) | Jun 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f2e5a856f4](https://linux-hardware.org/?probe=f2e5a856f4) | May 25, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [b31235961f](https://linux-hardware.org/?probe=b31235961f) | May 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [37f92aa173](https://linux-hardware.org/?probe=37f92aa173) | May 21, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [5a75c038d2](https://linux-hardware.org/?probe=5a75c038d2) | Apr 19, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [8ff8aa816f](https://linux-hardware.org/?probe=8ff8aa816f) | Apr 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [93d20b6e00](https://linux-hardware.org/?probe=93d20b6e00) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [0e115f2126](https://linux-hardware.org/?probe=0e115f2126) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5c31fd2838](https://linux-hardware.org/?probe=5c31fd2838) | Apr 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b929783867](https://linux-hardware.org/?probe=b929783867) | Apr 08, 2022 |
| Unknown       | Unknown                     | Soc         | [509d960112](https://linux-hardware.org/?probe=509d960112) | Mar 30, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [235c763f19](https://linux-hardware.org/?probe=235c763f19) | Mar 28, 2022 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [f3c11793ee](https://linux-hardware.org/?probe=f3c11793ee) | Mar 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6b82f2f5f8](https://linux-hardware.org/?probe=6b82f2f5f8) | Mar 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bd24a29894](https://linux-hardware.org/?probe=bd24a29894) | Mar 11, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [6218135a7c](https://linux-hardware.org/?probe=6218135a7c) | Mar 06, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d2b091c26b](https://linux-hardware.org/?probe=d2b091c26b) | Feb 22, 2022 |
| Shenzhen A... | X96 Max                     | Soc         | [440ca2b84f](https://linux-hardware.org/?probe=440ca2b84f) | Feb 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da8754f5d5](https://linux-hardware.org/?probe=da8754f5d5) | Jan 30, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d40ebefd39](https://linux-hardware.org/?probe=d40ebefd39) | Jan 28, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e21b25bba](https://linux-hardware.org/?probe=1e21b25bba) | Jan 12, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6d8df9807e](https://linux-hardware.org/?probe=6d8df9807e) | Jan 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6583550f14](https://linux-hardware.org/?probe=6583550f14) | Jan 11, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e6147adb9d](https://linux-hardware.org/?probe=e6147adb9d) | Dec 25, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [138b3d17bc](https://linux-hardware.org/?probe=138b3d17bc) | Dec 25, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2cfa03ec21](https://linux-hardware.org/?probe=2cfa03ec21) | Dec 23, 2021 |
| Unknown       | Beelink GT1                 | Soc         | [a8749745a4](https://linux-hardware.org/?probe=a8749745a4) | Dec 21, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [94f3848f94](https://linux-hardware.org/?probe=94f3848f94) | Dec 18, 2021 |
| Unknown       | Beelink GT1                 | Soc         | [51e764f297](https://linux-hardware.org/?probe=51e764f297) | Dec 17, 2021 |
| Unknown       | Beelink GT1                 | Soc         | [c5f5fd7e8f](https://linux-hardware.org/?probe=c5f5fd7e8f) | Dec 16, 2021 |
| Khadas        | VIM2                        | Soc         | [77b3e7305b](https://linux-hardware.org/?probe=77b3e7305b) | Dec 16, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [50d5c7e182](https://linux-hardware.org/?probe=50d5c7e182) | Dec 06, 2021 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [4239296e76](https://linux-hardware.org/?probe=4239296e76) | Dec 01, 2021 |
| Pine Micro... | Pine64 RK3566 Quartz64-A    | Soc         | [965f364f1d](https://linux-hardware.org/?probe=965f364f1d) | Nov 30, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c79ad4a8db](https://linux-hardware.org/?probe=c79ad4a8db) | Nov 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [077a2863fd](https://linux-hardware.org/?probe=077a2863fd) | Nov 05, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [20c4658fbc](https://linux-hardware.org/?probe=20c4658fbc) | Nov 04, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ac4e15828b](https://linux-hardware.org/?probe=ac4e15828b) | Nov 02, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b785cdc0bb](https://linux-hardware.org/?probe=b785cdc0bb) | Oct 30, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [df99169555](https://linux-hardware.org/?probe=df99169555) | Oct 30, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [4a5e673fe5](https://linux-hardware.org/?probe=4a5e673fe5) | Oct 14, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [52c09b147c](https://linux-hardware.org/?probe=52c09b147c) | Sep 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c189148518](https://linux-hardware.org/?probe=c189148518) | Sep 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ef99e18e2](https://linux-hardware.org/?probe=9ef99e18e2) | Aug 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f7a1b3b0e4](https://linux-hardware.org/?probe=f7a1b3b0e4) | Aug 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bff99d5a7c](https://linux-hardware.org/?probe=bff99d5a7c) | Jul 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [f003dd4906](https://linux-hardware.org/?probe=f003dd4906) | Jul 23, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [ca01402661](https://linux-hardware.org/?probe=ca01402661) | Jul 03, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [64603b3562](https://linux-hardware.org/?probe=64603b3562) | Jul 02, 2021 |
| Lenovo        | Yoga C630-13Q50 81JL        | Tablet      | [805ea3b3c5](https://linux-hardware.org/?probe=805ea3b3c5) | Jul 01, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4020e881a1](https://linux-hardware.org/?probe=4020e881a1) | Jun 16, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [f1bc769db9](https://linux-hardware.org/?probe=f1bc769db9) | Jun 15, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7fa170e5ca](https://linux-hardware.org/?probe=7fa170e5ca) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [dc7b014ec9](https://linux-hardware.org/?probe=dc7b014ec9) | May 26, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [896bd98421](https://linux-hardware.org/?probe=896bd98421) | May 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [368044e19e](https://linux-hardware.org/?probe=368044e19e) | May 18, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [e436e57831](https://linux-hardware.org/?probe=e436e57831) | May 17, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [07d8401514](https://linux-hardware.org/?probe=07d8401514) | May 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [321b9f409a](https://linux-hardware.org/?probe=321b9f409a) | May 14, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2aee3702e9](https://linux-hardware.org/?probe=2aee3702e9) | May 08, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf555f92bc](https://linux-hardware.org/?probe=cf555f92bc) | May 02, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [1f32cfa090](https://linux-hardware.org/?probe=1f32cfa090) | May 01, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [7d7e3bfc9f](https://linux-hardware.org/?probe=7d7e3bfc9f) | Apr 06, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [d97055c68d](https://linux-hardware.org/?probe=d97055c68d) | Apr 04, 2021 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [861c7906fa](https://linux-hardware.org/?probe=861c7906fa) | Mar 29, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [543a85726b](https://linux-hardware.org/?probe=543a85726b) | Mar 22, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [105dc78331](https://linux-hardware.org/?probe=105dc78331) | Mar 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae40e5f830](https://linux-hardware.org/?probe=ae40e5f830) | Mar 19, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2ad000987e](https://linux-hardware.org/?probe=2ad000987e) | Mar 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6c54a4db87](https://linux-hardware.org/?probe=6c54a4db87) | Feb 13, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [7b691e6c3a](https://linux-hardware.org/?probe=7b691e6c3a) | Feb 04, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [7f2e3317b5](https://linux-hardware.org/?probe=7f2e3317b5) | Jan 30, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [24c4a691d7](https://linux-hardware.org/?probe=24c4a691d7) | Jan 30, 2021 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [d9070da088](https://linux-hardware.org/?probe=d9070da088) | Dec 20, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [947451c5ef](https://linux-hardware.org/?probe=947451c5ef) | Nov 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7b35e5e525](https://linux-hardware.org/?probe=7b35e5e525) | Nov 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c4e2010c1b](https://linux-hardware.org/?probe=c4e2010c1b) | Nov 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [169238c060](https://linux-hardware.org/?probe=169238c060) | Nov 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fb24852769](https://linux-hardware.org/?probe=fb24852769) | Nov 01, 2020 |
| Pine Micro... | PineTab                     | Soc         | [d3736a7d1f](https://linux-hardware.org/?probe=d3736a7d1f) | Sep 29, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [dabd07ba39](https://linux-hardware.org/?probe=dabd07ba39) | Sep 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [199d9ad3ff](https://linux-hardware.org/?probe=199d9ad3ff) | Sep 18, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6831742863](https://linux-hardware.org/?probe=6831742863) | Sep 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [b7a5bf61e7](https://linux-hardware.org/?probe=b7a5bf61e7) | Sep 16, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [903bc538dd](https://linux-hardware.org/?probe=903bc538dd) | Sep 16, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [0ccf4e6f67](https://linux-hardware.org/?probe=0ccf4e6f67) | Sep 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ec849f00fc](https://linux-hardware.org/?probe=ec849f00fc) | Sep 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [1ef25f0a09](https://linux-hardware.org/?probe=1ef25f0a09) | Sep 03, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [0f15ee91d5](https://linux-hardware.org/?probe=0f15ee91d5) | Aug 25, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [e7ac0707cd](https://linux-hardware.org/?probe=e7ac0707cd) | Aug 25, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2098b09526](https://linux-hardware.org/?probe=2098b09526) | Aug 17, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [b0d04bed01](https://linux-hardware.org/?probe=b0d04bed01) | Aug 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [454d02d902](https://linux-hardware.org/?probe=454d02d902) | Jul 22, 2020 |
| Unknown       | Unknown                     | Soc         | [4fa39ff4f7](https://linux-hardware.org/?probe=4fa39ff4f7) | Jul 14, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bccab0e704](https://linux-hardware.org/?probe=bccab0e704) | Jul 04, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [edb48aa099](https://linux-hardware.org/?probe=edb48aa099) | Jun 03, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1c8aa5a7be](https://linux-hardware.org/?probe=1c8aa5a7be) | Jun 03, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [543099b0fa](https://linux-hardware.org/?probe=543099b0fa) | Mar 29, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [74359d777e](https://linux-hardware.org/?probe=74359d777e) | Mar 16, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [688046c3d7](https://linux-hardware.org/?probe=688046c3d7) | Feb 01, 2020 |
| Radxa         | ROCK Pi 4                   | Soc         | [3d67546a89](https://linux-hardware.org/?probe=3d67546a89) | Jan 29, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Manjaro-ARM       | 57        | 67.06%  |
| Manjaro-ARM 21.10 | 8         | 9.41%   |
| Manjaro-ARM 22.01 | 4         | 4.71%   |
| Manjaro-ARM 22.07 | 2         | 2.35%   |
| Manjaro-ARM 22.03 | 2         | 2.35%   |
| Manjaro-ARM 20.09 | 2         | 2.35%   |
| Manjaro-ARM 22.06 | 1         | 1.18%   |
| Manjaro-ARM 22.05 | 1         | 1.18%   |
| Manjaro-ARM 21.08 | 1         | 1.18%   |
| Manjaro-ARM 21.06 | 1         | 1.18%   |
| Manjaro-ARM 21.05 | 1         | 1.18%   |
| Manjaro-ARM 21.03 | 1         | 1.18%   |
| Manjaro-ARM 20.12 | 1         | 1.18%   |
| Manjaro-ARM 20.10 | 1         | 1.18%   |
| Manjaro-ARM 20.03 | 1         | 1.18%   |
| Manjaro-ARM 19.12 | 1         | 1.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Manjaro-ARM | 77        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.7-1-MANJARO-ARM        | 4         | 4.35%   |
| 5.10.74-1-MANJARO-ARM       | 4         | 4.35%   |
| 5.15.24-1-MANJARO-ARM-RPI   | 3         | 3.26%   |
| 5.9.1-3-MANJARO-ARM         | 2         | 2.17%   |
| 5.8.3-2-MANJARO-ARM         | 2         | 2.17%   |
| 5.4.61-1-MANJARO-ARM        | 2         | 2.17%   |
| 5.19.1-1-MANJARO-ARM        | 2         | 2.17%   |
| 5.18.9-1-MANJARO-ARM        | 2         | 2.17%   |
| 5.16.16-1-MANJARO-ARM       | 2         | 2.17%   |
| 5.15.28-1-MANJARO-ARM-RPI   | 2         | 2.17%   |
| 5.11.6-2-MANJARO-ARM        | 2         | 2.17%   |
| 5.11.3-1-MANJARO-ARM        | 2         | 2.17%   |
| 5.11.17-1-MANJARO-ARM       | 2         | 2.17%   |
| 5.10.88-1-MANJARO-ARM-RPI   | 2         | 2.17%   |
| 5.10.36-1-MANJARO-ARM       | 2         | 2.17%   |
| 4.19.127-1-MANJARO-ARM      | 2         | 2.17%   |
| 5.9.12-1-MANJARO-ARM        | 1         | 1.09%   |
| 5.9.0-rc7-1-MANJARO-ARM     | 1         | 1.09%   |
| 5.8.6-1-MANJARO-ARM         | 1         | 1.09%   |
| 5.8.5-1-MANJARO-ARM         | 1         | 1.09%   |
| 5.8.12-1-MANJARO-ARM        | 1         | 1.09%   |
| 5.7.19-1-MANJARO-ARM        | 1         | 1.09%   |
| 5.7.0-8-MANJARO-ARM         | 1         | 1.09%   |
| 5.7.0-3-MANJARO-ARM         | 1         | 1.09%   |
| 5.6.0-0.42-MANJARO-ARM      | 1         | 1.09%   |
| 5.5.0-1-MANJARO-ARM         | 1         | 1.09%   |
| 5.4.83-1-MANJARO-ARM        | 1         | 1.09%   |
| 5.4.72-1-MANJARO-ARM        | 1         | 1.09%   |
| 5.4.51-2-MANJARO-ARM        | 1         | 1.09%   |
| 5.19.0-rc7-1-MANJARO-ARM-RC | 1         | 1.09%   |
| 5.19.0-2-MANJARO-ARM-KHADAS | 1         | 1.09%   |
| 5.18.5-1-MANJARO-ARM-KHADAS | 1         | 1.09%   |
| 5.18.15-1-MANJARO-ARM       | 1         | 1.09%   |
| 5.18.14-1-MANJARO-ARM       | 1         | 1.09%   |
| 5.18.11-1-MANJARO-ARM       | 1         | 1.09%   |
| 5.18.0-rc7-7-MANJARO-ARM-RC | 1         | 1.09%   |
| 5.18.0-rc7-4-MANJARO-ARM-RC | 1         | 1.09%   |
| 5.18.0-rc2-2-MANJARO-ARM-RC | 1         | 1.09%   |
| 5.17.5-1-MANJARO-ARM        | 1         | 1.09%   |
| 5.17.1-2-MANJARO-ARM        | 1         | 1.09%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.7   | 4         | 4.44%   |
| 5.10.74  | 4         | 4.44%   |
| 5.15.24  | 3         | 3.33%   |
| 5.11.6   | 3         | 3.33%   |
| 5.9.1    | 2         | 2.22%   |
| 5.8.3    | 2         | 2.22%   |
| 5.7.0    | 2         | 2.22%   |
| 5.4.61   | 2         | 2.22%   |
| 5.19.1   | 2         | 2.22%   |
| 5.19.0   | 2         | 2.22%   |
| 5.18.9   | 2         | 2.22%   |
| 5.16.16  | 2         | 2.22%   |
| 5.15.28  | 2         | 2.22%   |
| 5.11.3   | 2         | 2.22%   |
| 5.11.17  | 2         | 2.22%   |
| 5.11.0   | 2         | 2.22%   |
| 5.10.88  | 2         | 2.22%   |
| 5.10.36  | 2         | 2.22%   |
| 4.19.127 | 2         | 2.22%   |
| 5.9.12   | 1         | 1.11%   |
| 5.9.0    | 1         | 1.11%   |
| 5.8.6    | 1         | 1.11%   |
| 5.8.5    | 1         | 1.11%   |
| 5.8.12   | 1         | 1.11%   |
| 5.7.19   | 1         | 1.11%   |
| 5.6.0    | 1         | 1.11%   |
| 5.5.0    | 1         | 1.11%   |
| 5.4.83   | 1         | 1.11%   |
| 5.4.72   | 1         | 1.11%   |
| 5.4.51   | 1         | 1.11%   |
| 5.18.5   | 1         | 1.11%   |
| 5.18.15  | 1         | 1.11%   |
| 5.18.14  | 1         | 1.11%   |
| 5.18.11  | 1         | 1.11%   |
| 5.18.0   | 1         | 1.11%   |
| 5.17.5   | 1         | 1.11%   |
| 5.17.1   | 1         | 1.11%   |
| 5.17.0   | 1         | 1.11%   |
| 5.16.11  | 1         | 1.11%   |
| 5.16.0   | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 24.14%  |
| 5.15    | 11        | 12.64%  |
| 5.11    | 10        | 11.49%  |
| 5.18    | 7         | 8.05%   |
| 5.8     | 5         | 5.75%   |
| 5.4     | 5         | 5.75%   |
| 5.9     | 4         | 4.6%    |
| 5.19    | 4         | 4.6%    |
| 5.16    | 4         | 4.6%    |
| 5.7     | 3         | 3.45%   |
| 5.17    | 3         | 3.45%   |
| 5.12    | 3         | 3.45%   |
| 4.19    | 3         | 3.45%   |
| 5.14    | 2         | 2.3%    |
| 5.6     | 1         | 1.15%   |
| 5.5     | 1         | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| aarch64 | 77        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KDE5        | 24        | 30.38%  |
| KDE         | 22        | 27.85%  |
| XFCE        | 14        | 17.72%  |
| GNOME       | 7         | 8.86%   |
| MATE        | 3         | 3.8%    |
| Unknown     | 3         | 3.8%    |
| X-Cinnamon  | 2         | 2.53%   |
| Phosh:GNOME | 2         | 2.53%   |
| sway        | 1         | 1.27%   |
| LXQt        | 1         | 1.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 48        | 62.34%  |
| Wayland | 25        | 32.47%  |
| Tty     | 3         | 3.9%    |
| Unknown | 1         | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 74.36%  |
| SDDM    | 10        | 12.82%  |
| LightDM | 6         | 7.69%   |
| TDM     | 2         | 2.56%   |
| GDM     | 2         | 2.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 37        | 46.84%  |
| fr_FR   | 7         | 8.86%   |
| C       | 7         | 8.86%   |
| de_DE   | 4         | 5.06%   |
| en_GB   | 3         | 3.8%    |
| en_CA   | 3         | 3.8%    |
| en_AU   | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| ru_RU   | 1         | 1.27%   |
| pt_PT   | 1         | 1.27%   |
| pl_PL   | 1         | 1.27%   |
| nl_NL   | 1         | 1.27%   |
| lt_LT   | 1         | 1.27%   |
| it_IT   | 1         | 1.27%   |
| it_CH   | 1         | 1.27%   |
| es_PE   | 1         | 1.27%   |
| es_ES   | 1         | 1.27%   |
| en_ZA   | 1         | 1.27%   |
| de_CH   | 1         | 1.27%   |
| de_AT   | 1         | 1.27%   |
| da_DK   | 1         | 1.27%   |
| bg_BG   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 51        | 64.56%  |
| BIOS | 28        | 35.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 73        | 94.81%  |
| F2fs  | 2         | 2.6%    |
| Btrfs | 2         | 2.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 74.36%  |
| MBR     | 13        | 16.67%  |
| GPT     | 7         | 8.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 92.21%  |
| Yes       | 6         | 7.79%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 96.1%   |
| Yes       | 3         | 3.9%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Raspberry Pi Foundation        | 33        | 42.86%  |
| Pine Microsystems              | 33        | 42.86%  |
| Unknown                        | 6         | 7.79%   |
| Shenzhen Amediatech Technology | 1         | 1.3%    |
| Radxa                          | 1         | 1.3%    |
| Lenovo                         | 1         | 1.3%    |
| Khadas                         | 1         | 1.3%    |
| Hardkernel                     | 1         | 1.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| RPi Raspberry Pi 4 Model B Rev 1.4         | 16        | 20.78%  |
| Pine Microsystems Pine64 PinePhone (1.2)   | 16        | 20.78%  |
| Pine Microsystems Pine64 Pinebook Pro      | 11        | 14.29%  |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 6         | 7.79%   |
| Unknown                                    | 6         | 7.79%   |
| RPi Raspberry Pi 400 Rev 1.0               | 4         | 5.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 4         | 5.19%   |
| RPi Raspberry Pi                           | 3         | 3.9%    |
| Pine Microsystems Pine64 PinePhonePro      | 3         | 3.9%    |
| Shenzhen Amediatech X96 Max                | 1         | 1.3%    |
| Radxa ROCK Pi 4                            | 1         | 1.3%    |
| Pine Microsystems PineTab                  | 1         | 1.3%    |
| Pine Microsystems Pine64 RK3566 Quartz64-A | 1         | 1.3%    |
| Pine Microsystems Pine64 PinePhonePro (DT) | 1         | 1.3%    |
| Lenovo Yoga C630-13Q50 81JL                | 1         | 1.3%    |
| Khadas VIM2                                | 1         | 1.3%    |
| Hardkernel ODROID-N2Plus                   | 1         | 1.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| RPi Raspberry             | 33        | 42.86%  |
| Pine Microsystems Pine64  | 32        | 41.56%  |
| Unknown                   | 6         | 7.79%   |
| Shenzhen Amediatech X96   | 1         | 1.3%    |
| Radxa ROCK                | 1         | 1.3%    |
| Pine Microsystems PineTab | 1         | 1.3%    |
| Lenovo Yoga               | 1         | 1.3%    |
| Khadas VIM2               | 1         | 1.3%    |
| Hardkernel ODROID-N2Plus  | 1         | 1.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 85.71%  |
| 2020    | 10        | 12.99%  |
| 2019    | 1         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| System on chip | 45        | 58.44%  |
| Phone          | 20        | 25.97%  |
| Notebook       | 11        | 14.29%  |
| Tablet         | 1         | 1.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 77        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 77        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 47        | 61.04%  |
| 4.01-8.0   | 17        | 22.08%  |
| 1.01-2.0   | 7         | 9.09%   |
| 2.01-3.0   | 6         | 7.79%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 43        | 53.09%  |
| 2.01-3.0 | 17        | 20.99%  |
| 0.51-1.0 | 17        | 20.99%  |
| 0.01-0.5 | 3         | 3.7%    |
| 3.01-4.0 | 1         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 51        | 62.2%   |
| 2      | 27        | 32.93%  |
| 0      | 3         | 3.66%   |
| 3      | 1         | 1.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 98.7%   |
| Yes       | 1         | 1.3%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 88.46%  |
| Yes       | 9         | 11.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 65%     |
| Yes       | 28        | 35%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 97.44%  |
| Yes       | 2         | 2.56%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 28        | 36.36%  |
| France       | 8         | 10.39%  |
| UK           | 5         | 6.49%   |
| Germany      | 5         | 6.49%   |
| Australia    | 5         | 6.49%   |
| Canada       | 4         | 5.19%   |
| Switzerland  | 2         | 2.6%    |
| Spain        | 2         | 2.6%    |
| Russia       | 2         | 2.6%    |
| Portugal     | 2         | 2.6%    |
| Netherlands  | 2         | 2.6%    |
| Italy        | 2         | 2.6%    |
| Turkey       | 1         | 1.3%    |
| Sweden       | 1         | 1.3%    |
| South Africa | 1         | 1.3%    |
| Poland       | 1         | 1.3%    |
| Peru         | 1         | 1.3%    |
| Malta        | 1         | 1.3%    |
| Lithuania    | 1         | 1.3%    |
| Kuwait       | 1         | 1.3%    |
| India        | 1         | 1.3%    |
| Cyprus       | 1         | 1.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Greoux-les-Bains       | 5         | 6.17%   |
| London                 | 2         | 2.47%   |
| Denver                 | 2         | 2.47%   |
| Adelaide               | 2         | 2.47%   |
| Yaroslavl              | 1         | 1.23%   |
| Wooster                | 1         | 1.23%   |
| Woodville              | 1         | 1.23%   |
| Weinheim               | 1         | 1.23%   |
| Viseu                  | 1         | 1.23%   |
| Vallauris              | 1         | 1.23%   |
| Thun                   | 1         | 1.23%   |
| Sydney                 | 1         | 1.23%   |
| Strasbourg             | 1         | 1.23%   |
| Springboro             | 1         | 1.23%   |
| San Mateo              | 1         | 1.23%   |
| San Germano Vercellese | 1         | 1.23%   |
| San Francisco          | 1         | 1.23%   |
| San Diego              | 1         | 1.23%   |
| Redding                | 1         | 1.23%   |
| Potomac                | 1         | 1.23%   |
| Portland               | 1         | 1.23%   |
| Pinetop-Lakeside       | 1         | 1.23%   |
| Perth                  | 1         | 1.23%   |
| Perm                   | 1         | 1.23%   |
| Pabianice              | 1         | 1.23%   |
| Nottingham             | 1         | 1.23%   |
| North Battleford       | 1         | 1.23%   |
| North Adams            | 1         | 1.23%   |
| New Delhi              | 1         | 1.23%   |
| Moscow                 | 1         | 1.23%   |
| Montreal               | 1         | 1.23%   |
| Melbourne              | 1         | 1.23%   |
| Mannens                | 1         | 1.23%   |
| Manchester             | 1         | 1.23%   |
| Madrid                 | 1         | 1.23%   |
| Lusby                  | 1         | 1.23%   |
| Los Angeles            | 1         | 1.23%   |
| Lodz                   | 1         | 1.23%   |
| Livonia                | 1         | 1.23%   |
| Lisbon                 | 1         | 1.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 67        | 95     | 76.14%  |
| Seagate             | 3         | 5      | 3.41%   |
| SanDisk             | 3         | 4      | 3.41%   |
| ASMT                | 3         | 3      | 3.41%   |
| Toshiba             | 2         | 2      | 2.27%   |
| Argon               | 2         | 3      | 2.27%   |
| USB3.0              | 1         | 1      | 1.14%   |
| SK hynix            | 1         | 2      | 1.14%   |
| Samsung Electronics | 1         | 4      | 1.14%   |
| PNY USB             | 1         | 1      | 1.14%   |
| Phison              | 1         | 1      | 1.14%   |
| LaCie               | 1         | 1      | 1.14%   |
| Kingston            | 1         | 1      | 1.14%   |
| Intel               | 1         | 1      | 1.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown MMC Card  32GB         | 25        | 24.75%  |
| Unknown MMC Card  64GB         | 16        | 15.84%  |
| Unknown MMC Card  128GB        | 14        | 13.86%  |
| Unknown SLD32G  32GB           | 5         | 4.95%   |
| Unknown SE32G  32GB            | 5         | 4.95%   |
| Unknown DA4064  64GB           | 4         | 3.96%   |
| Unknown MMC Card  256GB        | 3         | 2.97%   |
| ASMT 2115 1TB                  | 3         | 2.97%   |
| Unknown MMC Card  16GB         | 2         | 1.98%   |
| Seagate Expansion 1TB          | 2         | 1.98%   |
| Argon Forty 120GB              | 2         | 1.98%   |
| USB3.0 Disk 480GB              | 1         | 0.99%   |
| Unknown SN64G  64GB            | 1         | 0.99%   |
| Unknown SN128  128GB           | 1         | 0.99%   |
| Unknown SL64G  64GB            | 1         | 0.99%   |
| Unknown SC32G  32GB            | 1         | 0.99%   |
| Unknown MMC Card  249GB        | 1         | 0.99%   |
| Unknown CJTD4R  64GB           | 1         | 0.99%   |
| Toshiba NVMe SSD Drive 256GB   | 1         | 0.99%   |
| Toshiba HDWD240 4TB            | 1         | 0.99%   |
| SK hynix HBG4e  32GB           | 1         | 0.99%   |
| Seagate Expansion Desk 2TB     | 1         | 0.99%   |
| SanDisk SSD PLUS 240GB         | 1         | 0.99%   |
| SanDisk SL32G  32GB            | 1         | 0.99%   |
| SanDisk Extreme 55AE 500GB SSD | 1         | 0.99%   |
| Samsung Portable SSD T5 500GB  | 1         | 0.99%   |
| PNY USB 3.0 to SATA 256GB SSD  | 1         | 0.99%   |
| Phison NVMe SSD Drive 256GB    | 1         | 0.99%   |
| LaCie Rugged USB-C 4TB         | 1         | 0.99%   |
| Kingston SHFS37A120G 120GB SSD | 1         | 0.99%   |
| Intel NVMe SSD Drive 512GB     | 1         | 0.99%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 5      | 60%     |
| USB3.0  | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| ASMT                | 3         | 3      | 30%     |
| SanDisk             | 2         | 2      | 20%     |
| Argon               | 2         | 3      | 20%     |
| Samsung Electronics | 1         | 4      | 10%     |
| PNY USB             | 1         | 1      | 10%     |
| Kingston            | 1         | 1      | 10%     |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| MMC     | 67        | 99     | 78.82%  |
| SSD     | 10        | 14     | 11.76%  |
| HDD     | 4         | 7      | 4.71%   |
| NVMe    | 3         | 3      | 3.53%   |
| Unknown | 1         | 1      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| MMC  | 67        | 99     | 77.91%  |
| SAS  | 15        | 21     | 17.44%  |
| NVMe | 3         | 3      | 3.49%   |
| SATA | 1         | 1      | 1.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 12     | 53.33%  |
| 0.51-1.0   | 5         | 7      | 33.33%  |
| 3.01-4.0   | 1         | 1      | 6.67%   |
| 1.01-2.0   | 1         | 1      | 6.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 26        | 32.1%   |
| 101-250        | 20        | 24.69%  |
| 51-100         | 19        | 23.46%  |
| 251-500        | 9         | 11.11%  |
| 1-20           | 2         | 2.47%   |
| 501-1000       | 2         | 2.47%   |
| More than 3000 | 1         | 1.23%   |
| 1001-2000      | 1         | 1.23%   |
| Unknown        | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 48        | 57.83%  |
| 21-50     | 22        | 26.51%  |
| 51-100    | 7         | 8.43%   |
| 251-500   | 3         | 3.61%   |
| 101-250   | 1         | 1.2%    |
| 1001-2000 | 1         | 1.2%    |
| Unknown   | 1         | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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
| Detected | 73        | 121    | 96.05%  |
| Works    | 3         | 3      | 3.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Toshiba America Info Systems | 1         | 33.33%  |
| Phison Electronics           | 1         | 33.33%  |
| Intel                        | 1         | 33.33%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba America Info Systems XG6 NVMe SSD Controller | 1         | 33.33%  |
| Phison E12 NVMe Controller                           | 1         | 33.33%  |
| Intel SSD 660P Series                                | 1         | 33.33%  |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 3         | 100%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| ARM      | 76        | 98.7%   |
| QUALCOMM | 1         | 1.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| ARM Processor      | 76        | 98.7%   |
| QUALCOMM Processor | 1         | 1.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model | Computers | Percent |
|-------|-----------|---------|
| Other | 77        | 100%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 40        | 51.28%  |
| Unknown | 19        | 24.36%  |
| 6       | 14        | 17.95%  |
| 2       | 5         | 6.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 45        | 57.69%  |
| Unknown | 19        | 24.36%  |
| 2       | 14        | 17.95%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 58        | 75.32%  |
| Unknown | 19        | 24.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 64-bit         | 43        | 54.43%  |
| 32-bit, 64-bit | 18        | 22.78%  |
| Unknown        | 18        | 22.78%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 100%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

Zero info for selected period =(

GPU Model
---------

Graphics card models

Zero info for selected period =(

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Other | 77        | 100%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 12        | 26.09%  |
| Dell                 | 4         | 8.7%    |
| Iiyama               | 3         | 6.52%   |
| Hewlett-Packard      | 3         | 6.52%   |
| Ancor Communications | 3         | 6.52%   |
| Philips              | 2         | 4.35%   |
| BenQ                 | 2         | 4.35%   |
| ASUSTek Computer     | 2         | 4.35%   |
| AOC                  | 2         | 4.35%   |
| ViewSonic            | 1         | 2.17%   |
| Vestel Elektronik    | 1         | 2.17%   |
| Unknown (XXX)        | 1         | 2.17%   |
| Unknown (ADA)        | 1         | 2.17%   |
| Sceptre Tech         | 1         | 2.17%   |
| ONN                  | 1         | 2.17%   |
| InfoVision           | 1         | 2.17%   |
| HJW                  | 1         | 2.17%   |
| Grundig              | 1         | 2.17%   |
| Goldstar             | 1         | 2.17%   |
| GKK                  | 1         | 2.17%   |
| Eizo                 | 1         | 2.17%   |
| DMT                  | 1         | 2.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                  | 3         | 6.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 4.35%   |
| Ancor Communications ASUS VH242 ACI24FA 1920x1080 521x293mm 23.5-inch  | 2         | 4.35%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch          | 1         | 2.17%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch     | 1         | 2.17%   |
| Unknown (XXX) HDMI     XXX0029 1920x1080 1150x650mm 52.0-inch          | 1         | 2.17%   |
| Unknown (ADA) MPI4008 ADA0004 480x800 150x100mm 7.1-inch               | 1         | 2.17%   |
| Sceptre Tech E20 SPT080D 1600x900 410x280mm 19.5-inch                  | 1         | 2.17%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch      | 1         | 2.17%   |
| Samsung Electronics SyncMaster SAM02FD 1680x1050 430x270mm 20.0-inch   | 1         | 2.17%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 410x260mm 19.1-inch    | 1         | 2.17%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch      | 1         | 2.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch  | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch  | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 2.17%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                       | 1         | 2.17%   |
| Philips PHL 252B9 PHL092C 1920x1200 540x340mm 25.1-inch                | 1         | 2.17%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                | 1         | 2.17%   |
| ONN 100002480 ONN0101 1920x1080 470x290mm 21.7-inch                    | 1         | 2.17%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch           | 1         | 2.17%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                  | 1         | 2.17%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 540x350mm 25.3-inch          | 1         | 2.17%   |
| Hewlett-Packard f1523 HWP2607 1024x768 304x228mm 15.0-inch             | 1         | 2.17%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch            | 1         | 2.17%   |
| Grundig TV GRU4448 1920x1080 1210x680mm 54.6-inch                      | 1         | 2.17%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                  | 1         | 2.17%   |
| GKK MONITOR GKK3034 1920x1080                                          | 1         | 2.17%   |
| Eizo S1921 ENC1831 1280x1024 380x300mm 19.1-inch                       | 1         | 2.17%   |
| DMT CHHWJT* DMT0030 1440x900 710x400mm 32.1-inch                       | 1         | 2.17%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                     | 1         | 2.17%   |
| Dell P2421D DELD0FF 2560x1440 530x300mm 24.0-inch                      | 1         | 2.17%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                      | 1         | 2.17%   |
| Dell 1704FPT DEL4004 1280x1024 340x270mm 17.1-inch                     | 1         | 2.17%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                      | 1         | 2.17%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                      | 1         | 2.17%   |
| ASUSTek Computer VZ249 AUS24CC 1920x1080 530x300mm 24.0-inch           | 1         | 2.17%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch           | 1         | 2.17%   |
| AOC Q27P1B AOC2701 2560x1440 600x340mm 27.2-inch                       | 1         | 2.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 46.51%  |
| 3840x2160 (4K)     | 9         | 20.93%  |
| 2560x1440 (QHD)    | 3         | 6.98%   |
| 1920x1200 (WUXGA)  | 2         | 4.65%   |
| 1680x1050 (WSXGA+) | 2         | 4.65%   |
| 1440x900 (WXGA+)   | 2         | 4.65%   |
| 1280x1024 (SXGA)   | 2         | 4.65%   |
| 1600x900 (HD+)     | 1         | 2.33%   |
| 1280x800 (WXGA)    | 1         | 2.33%   |
| 1024x768 (XGA)     | 1         | 2.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 8         | 17.39%  |
| 24      | 5         | 10.87%  |
| 23      | 5         | 10.87%  |
| 21      | 4         | 8.7%    |
| 84      | 3         | 6.52%   |
| 39      | 3         | 6.52%   |
| 19      | 3         | 6.52%   |
| 54      | 2         | 4.35%   |
| 25      | 2         | 4.35%   |
| 52      | 1         | 2.17%   |
| 47      | 1         | 2.17%   |
| 32      | 1         | 2.17%   |
| 31      | 1         | 2.17%   |
| 22      | 1         | 2.17%   |
| 20      | 1         | 2.17%   |
| 17      | 1         | 2.17%   |
| 15      | 1         | 2.17%   |
| 13      | 1         | 2.17%   |
| 7       | 1         | 2.17%   |
| Unknown | 1         | 2.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 17        | 37.78%  |
| 401-500     | 7         | 15.56%  |
| 1001-1500   | 4         | 8.89%   |
| 801-900     | 3         | 6.67%   |
| 601-700     | 3         | 6.67%   |
| 1501-2000   | 3         | 6.67%   |
| 351-400     | 2         | 4.44%   |
| 301-350     | 2         | 4.44%   |
| 701-800     | 1         | 2.22%   |
| 201-300     | 1         | 2.22%   |
| 101-200     | 1         | 2.22%   |
| Unknown     | 1         | 2.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 31        | 73.81%  |
| 16/10 | 6         | 14.29%  |
| 5/4   | 3         | 7.14%   |
| 4/3   | 1         | 2.38%   |
| 3/2   | 1         | 2.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 12        | 27.27%  |
| 301-350        | 8         | 18.18%  |
| More than 1000 | 6         | 13.64%  |
| 151-200        | 4         | 9.09%   |
| 501-1000       | 4         | 9.09%   |
| 251-300        | 3         | 6.82%   |
| 351-500        | 2         | 4.55%   |
| 71-80          | 1         | 2.27%   |
| 1-40           | 1         | 2.27%   |
| 141-150        | 1         | 2.27%   |
| 111-120        | 1         | 2.27%   |
| Unknown        | 1         | 2.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 25        | 59.52%  |
| 101-120 | 7         | 16.67%  |
| 121-160 | 4         | 9.52%   |
| 1-50    | 3         | 7.14%   |
| 161-240 | 2         | 4.76%   |
| Unknown | 1         | 2.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 69        | 87.34%  |
| 0     | 7         | 8.86%   |
| 2     | 3         | 3.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 6         | 30%     |
| TP-Link                         | 4         | 20%     |
| ICS Advent                      | 3         | 15%     |
| Sigma Designs                   | 1         | 5%      |
| Qualcomm Atheros Communications | 1         | 5%      |
| Netchip Technology              | 1         | 5%      |
| Intel                           | 1         | 5%      |
| D-Link                          | 1         | 5%      |
| ASIX Electronics                | 1         | 5%      |
| Arduino SA                      | 1         | 5%      |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| ICS Advent 10/100M LAN                                                               | 3         | 15%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2         | 10%     |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1         | 5%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1         | 5%      |
| TP-Link Archer T4U ver.3                                                             | 1         | 5%      |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1         | 5%      |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                      | 1         | 5%      |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1         | 5%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1         | 5%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 5%      |
| Realtek RTL8152 Fast Ethernet Adapter                                                | 1         | 5%      |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 5%      |
| Netchip Linux-USB Ethernet/RNDIS Gadget                                              | 1         | 5%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1         | 5%      |
| D-Link 802.11ac NIC                                                                  | 1         | 5%      |
| ASIX AX88179 Gigabit Ethernet                                                        | 1         | 5%      |
| Arduino SA Uno R3 (CDC ACM)                                                          | 1         | 5%      |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| TP-Link                         | 4         | 40%     |
| Realtek Semiconductor           | 3         | 30%     |
| Qualcomm Atheros Communications | 1         | 10%     |
| Intel                           | 1         | 10%     |
| D-Link                          | 1         | 10%     |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1         | 10%     |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1         | 10%     |
| TP-Link Archer T4U ver.3                                                             | 1         | 10%     |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1         | 10%     |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1         | 10%     |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1         | 10%     |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 10%     |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 10%     |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1         | 10%     |
| D-Link 802.11ac NIC                                                                  | 1         | 10%     |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 3         | 37.5%   |
| ICS Advent            | 3         | 37.5%   |
| Netchip Technology    | 1         | 12.5%   |
| ASIX Electronics      | 1         | 12.5%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| ICS Advent 10/100M LAN                   | 3         | 37.5%   |
| Realtek RTL8153 Gigabit Ethernet Adapter | 2         | 25%     |
| Realtek RTL8152 Fast Ethernet Adapter    | 1         | 12.5%   |
| Netchip Linux-USB Ethernet/RNDIS Gadget  | 1         | 12.5%   |
| ASIX AX88179 Gigabit Ethernet            | 1         | 12.5%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8         | 47.06%  |
| WiFi     | 7         | 41.18%  |
| Modem    | 2         | 11.76%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3         | 60%     |
| Ethernet | 2         | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 77        | 98.72%  |
| 1     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 66        | 82.5%   |
| Yes  | 14        | 17.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Realtek Semiconductor   | 1         | 50%     |
| Cambridge Silicon Radio | 1         | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 1         | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Sennheiser Communications | 1         | 25%     |
| Logitech                  | 1         | 25%     |
| Generalplus Technology    | 1         | 25%     |
| C-Media Electronics       | 1         | 25%     |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Sennheiser Communications Sennheiser Main Audio   | 1         | 25%     |
| Logitech [G533 Wireless Headset Dongle]           | 1         | 25%     |
| Generalplus Technology Usb Audio Device           | 1         | 25%     |
| C-Media Electronics Audio Adapter (Unitek Y-247A) | 1         | 25%     |

Memory
------

Memory Vendor
-------------

Memory module vendors

Zero info for selected period =(

Memory Model
------------

Memory module models

Zero info for selected period =(

Memory Kind
-----------

Memory module kinds

Zero info for selected period =(

Memory Form Factor
------------------

Physical design of the memory module

Zero info for selected period =(

Memory Size
-----------

Memory module size

Zero info for selected period =(

Memory Speed
------------

Memory module speed

Zero info for selected period =(

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4600 Series | 1         | 100%    |

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


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Microdia                      | 8         | 66.67%  |
| OnePlus Technology (Shenzhen) | 1         | 8.33%   |
| MacroSilicon                  | 1         | 8.33%   |
| LG Electronics                | 1         | 8.33%   |
| Acer                          | 1         | 8.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Microdia HP Integrated Webcam                         | 8         | 66.67%  |
| OnePlus (Shenzhen) SM8150-MTP _SN:A05FE1A2            | 1         | 8.33%   |
| MacroSilicon USB Video                                | 1         | 8.33%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 8.33%   |
| Acer Integrated Camera                                | 1         | 8.33%   |

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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 97.44%  |
| 1     | 2         | 2.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type         | Computers | Percent |
|--------------|-----------|---------|
| Net/wireless | 2         | 100%    |

