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

Total: 135

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [b8cb61c70a](https://linux-hardware.org/?probe=b8cb61c70a) | Dec 29, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [c8b4b6d3bc](https://linux-hardware.org/?probe=c8b4b6d3bc) | Dec 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7714ba77eb](https://linux-hardware.org/?probe=7714ba77eb) | Dec 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8c140bbafc](https://linux-hardware.org/?probe=8c140bbafc) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5981154034](https://linux-hardware.org/?probe=5981154034) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0361b1083f](https://linux-hardware.org/?probe=0361b1083f) | Dec 20, 2022 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [760fd1ae84](https://linux-hardware.org/?probe=760fd1ae84) | Dec 13, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cc309bb44c](https://linux-hardware.org/?probe=cc309bb44c) | Nov 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a0d94329a6](https://linux-hardware.org/?probe=a0d94329a6) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9f0e94860c](https://linux-hardware.org/?probe=9f0e94860c) | Nov 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [81f59ba6f5](https://linux-hardware.org/?probe=81f59ba6f5) | Nov 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3fe8b5fef3](https://linux-hardware.org/?probe=3fe8b5fef3) | Nov 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [012705552d](https://linux-hardware.org/?probe=012705552d) | Nov 04, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [34061efe0c](https://linux-hardware.org/?probe=34061efe0c) | Oct 25, 2022 |
| Radxa         | ROCK Pi 4B (DT)             | Soc         | [f05063925b](https://linux-hardware.org/?probe=f05063925b) | Oct 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7207f549c7](https://linux-hardware.org/?probe=7207f549c7) | Oct 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d18c649cb6](https://linux-hardware.org/?probe=d18c649cb6) | Oct 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f9dc4fff88](https://linux-hardware.org/?probe=f9dc4fff88) | Oct 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2f6a610d9](https://linux-hardware.org/?probe=d2f6a610d9) | Oct 06, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ac0705feae](https://linux-hardware.org/?probe=ac0705feae) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0c25e7e0a0](https://linux-hardware.org/?probe=0c25e7e0a0) | Oct 02, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc3501546b](https://linux-hardware.org/?probe=bc3501546b) | Sep 28, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [bc6ffac174](https://linux-hardware.org/?probe=bc6ffac174) | Sep 11, 2022 |
| Unknown       | Unknown                     | Soc         | [6e8246d8bc](https://linux-hardware.org/?probe=6e8246d8bc) | Sep 05, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [533e62b70d](https://linux-hardware.org/?probe=533e62b70d) | Aug 20, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [2b238b3dc7](https://linux-hardware.org/?probe=2b238b3dc7) | Aug 19, 2022 |
| PINE64        | Pinebook Pro                | Soc         | [5f5c134bd6](https://linux-hardware.org/?probe=5f5c134bd6) | Aug 14, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Manjaro-ARM       | 60        | 65.93%  |
| Manjaro-ARM 21.10 | 8         | 8.79%   |
| Manjaro-ARM 22.01 | 4         | 4.4%    |
| Manjaro-ARM 22.09 | 2         | 2.2%    |
| Manjaro-ARM 22.07 | 2         | 2.2%    |
| Manjaro-ARM 22.03 | 2         | 2.2%    |
| Manjaro-ARM 20.09 | 2         | 2.2%    |
| Manjaro-ARM 22.12 | 1         | 1.1%    |
| Manjaro-ARM 22.06 | 1         | 1.1%    |
| Manjaro-ARM 22.05 | 1         | 1.1%    |
| Manjaro-ARM 21.08 | 1         | 1.1%    |
| Manjaro-ARM 21.06 | 1         | 1.1%    |
| Manjaro-ARM 21.05 | 1         | 1.1%    |
| Manjaro-ARM 21.03 | 1         | 1.1%    |
| Manjaro-ARM 20.12 | 1         | 1.1%    |
| Manjaro-ARM 20.10 | 1         | 1.1%    |
| Manjaro-ARM 20.03 | 1         | 1.1%    |
| Manjaro-ARM 19.12 | 1         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Manjaro-ARM | 82        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.7-1-MANJARO-ARM        | 4         | 3.96%   |
| 5.10.74-1-MANJARO-ARM       | 4         | 3.96%   |
| 5.15.24-1-MANJARO-ARM-RPI   | 3         | 2.97%   |
| 5.9.1-3-MANJARO-ARM         | 2         | 1.98%   |
| 5.8.3-2-MANJARO-ARM         | 2         | 1.98%   |
| 5.4.61-1-MANJARO-ARM        | 2         | 1.98%   |
| 5.19.1-1-MANJARO-ARM        | 2         | 1.98%   |
| 5.18.9-1-MANJARO-ARM        | 2         | 1.98%   |
| 5.16.16-1-MANJARO-ARM       | 2         | 1.98%   |
| 5.15.70-1-MANJARO-ARM-RPI   | 2         | 1.98%   |
| 5.15.28-1-MANJARO-ARM-RPI   | 2         | 1.98%   |
| 5.11.6-2-MANJARO-ARM        | 2         | 1.98%   |
| 5.11.3-1-MANJARO-ARM        | 2         | 1.98%   |
| 5.11.17-1-MANJARO-ARM       | 2         | 1.98%   |
| 5.10.88-1-MANJARO-ARM-RPI   | 2         | 1.98%   |
| 5.10.36-1-MANJARO-ARM       | 2         | 1.98%   |
| 4.19.127-1-MANJARO-ARM      | 2         | 1.98%   |
| 6.1.0-rc8-1-MANJARO-ARM-RPI | 1         | 0.99%   |
| 6.1.0-rc8-1-MANJARO-ARM     | 1         | 0.99%   |
| 6.1.0-rc1-2-MANJARO-ARM-RPI | 1         | 0.99%   |
| 6.0.3-1-MANJARO-ARM         | 1         | 0.99%   |
| 6.0.12-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.9.12-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.9.0-rc7-1-MANJARO-ARM     | 1         | 0.99%   |
| 5.8.6-1-MANJARO-ARM         | 1         | 0.99%   |
| 5.8.5-1-MANJARO-ARM         | 1         | 0.99%   |
| 5.8.12-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.7.19-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.7.0-8-MANJARO-ARM         | 1         | 0.99%   |
| 5.7.0-3-MANJARO-ARM         | 1         | 0.99%   |
| 5.6.0-0.42-MANJARO-ARM      | 1         | 0.99%   |
| 5.5.0-1-MANJARO-ARM         | 1         | 0.99%   |
| 5.4.83-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.4.72-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.4.51-2-MANJARO-ARM        | 1         | 0.99%   |
| 5.19.8-1-MANJARO-ARM        | 1         | 0.99%   |
| 5.19.11-3-MANJARO-ARM       | 1         | 0.99%   |
| 5.19.0-rc7-1-MANJARO-ARM-RC | 1         | 0.99%   |
| 5.19.0-2-MANJARO-ARM-KHADAS | 1         | 0.99%   |
| 5.18.5-1-MANJARO-ARM-KHADAS | 1         | 0.99%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.7   | 4         | 4.08%   |
| 5.10.74  | 4         | 4.08%   |
| 5.15.24  | 3         | 3.06%   |
| 5.11.6   | 3         | 3.06%   |
| 6.1.0    | 2         | 2.04%   |
| 5.9.1    | 2         | 2.04%   |
| 5.8.3    | 2         | 2.04%   |
| 5.7.0    | 2         | 2.04%   |
| 5.4.61   | 2         | 2.04%   |
| 5.19.1   | 2         | 2.04%   |
| 5.19.0   | 2         | 2.04%   |
| 5.18.9   | 2         | 2.04%   |
| 5.16.16  | 2         | 2.04%   |
| 5.15.70  | 2         | 2.04%   |
| 5.15.28  | 2         | 2.04%   |
| 5.11.3   | 2         | 2.04%   |
| 5.11.17  | 2         | 2.04%   |
| 5.11.0   | 2         | 2.04%   |
| 5.10.88  | 2         | 2.04%   |
| 5.10.36  | 2         | 2.04%   |
| 4.19.127 | 2         | 2.04%   |
| 6.0.3    | 1         | 1.02%   |
| 6.0.12   | 1         | 1.02%   |
| 5.9.12   | 1         | 1.02%   |
| 5.9.0    | 1         | 1.02%   |
| 5.8.6    | 1         | 1.02%   |
| 5.8.5    | 1         | 1.02%   |
| 5.8.12   | 1         | 1.02%   |
| 5.7.19   | 1         | 1.02%   |
| 5.6.0    | 1         | 1.02%   |
| 5.5.0    | 1         | 1.02%   |
| 5.4.83   | 1         | 1.02%   |
| 5.4.72   | 1         | 1.02%   |
| 5.4.51   | 1         | 1.02%   |
| 5.19.8   | 1         | 1.02%   |
| 5.19.11  | 1         | 1.02%   |
| 5.18.5   | 1         | 1.02%   |
| 5.18.15  | 1         | 1.02%   |
| 5.18.14  | 1         | 1.02%   |
| 5.18.11  | 1         | 1.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 22.58%  |
| 5.15    | 12        | 12.9%   |
| 5.11    | 10        | 10.75%  |
| 5.18    | 7         | 7.53%   |
| 5.8     | 5         | 5.38%   |
| 5.4     | 5         | 5.38%   |
| 5.19    | 5         | 5.38%   |
| 5.9     | 4         | 4.3%    |
| 5.16    | 4         | 4.3%    |
| 5.7     | 3         | 3.23%   |
| 5.17    | 3         | 3.23%   |
| 5.12    | 3         | 3.23%   |
| 4.19    | 3         | 3.23%   |
| 6.1     | 2         | 2.15%   |
| 6.0     | 2         | 2.15%   |
| 5.14    | 2         | 2.15%   |
| 5.6     | 1         | 1.08%   |
| 5.5     | 1         | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| aarch64 | 82        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KDE5        | 27        | 31.76%  |
| KDE         | 22        | 25.88%  |
| XFCE        | 15        | 17.65%  |
| GNOME       | 8         | 9.41%   |
| Unknown     | 4         | 4.71%   |
| MATE        | 3         | 3.53%   |
| X-Cinnamon  | 2         | 2.35%   |
| Phosh:GNOME | 2         | 2.35%   |
| sway        | 1         | 1.18%   |
| LXQt        | 1         | 1.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 49        | 59.04%  |
| Wayland | 29        | 34.94%  |
| Tty     | 3         | 3.61%   |
| Unknown | 2         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 62        | 74.7%   |
| SDDM    | 11        | 13.25%  |
| LightDM | 6         | 7.23%   |
| TDM     | 2         | 2.41%   |
| GDM     | 2         | 2.41%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 49.41%  |
| fr_FR   | 7         | 8.24%   |
| C       | 7         | 8.24%   |
| en_GB   | 4         | 4.71%   |
| de_DE   | 4         | 4.71%   |
| en_CA   | 3         | 3.53%   |
| en_AU   | 2         | 2.35%   |
| Unknown | 2         | 2.35%   |
| ru_RU   | 1         | 1.18%   |
| pt_PT   | 1         | 1.18%   |
| pl_PL   | 1         | 1.18%   |
| nl_NL   | 1         | 1.18%   |
| lt_LT   | 1         | 1.18%   |
| it_IT   | 1         | 1.18%   |
| it_CH   | 1         | 1.18%   |
| es_PE   | 1         | 1.18%   |
| es_ES   | 1         | 1.18%   |
| en_ZA   | 1         | 1.18%   |
| de_CH   | 1         | 1.18%   |
| de_AT   | 1         | 1.18%   |
| da_DK   | 1         | 1.18%   |
| bg_BG   | 1         | 1.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 53        | 63.1%   |
| BIOS | 31        | 36.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 78        | 95.12%  |
| F2fs  | 2         | 2.44%   |
| Btrfs | 2         | 2.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 73.49%  |
| MBR     | 13        | 15.66%  |
| GPT     | 9         | 10.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 92.68%  |
| Yes       | 6         | 7.32%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 96.34%  |
| Yes       | 3         | 3.66%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Pine Microsystems              | 35        | 42.68%  |
| Raspberry Pi Foundation        | 34        | 41.46%  |
| Unknown                        | 6         | 7.32%   |
| Radxa                          | 2         | 2.44%   |
| Shenzhen Amediatech Technology | 1         | 1.22%   |
| PINE64                         | 1         | 1.22%   |
| Lenovo                         | 1         | 1.22%   |
| Khadas                         | 1         | 1.22%   |
| Hardkernel                     | 1         | 1.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 18        | 21.95%  |
| RPi Raspberry Pi 4 Model B Rev 1.4         | 16        | 19.51%  |
| Pine Microsystems Pine64 Pinebook Pro      | 11        | 13.41%  |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 7         | 8.54%   |
| Unknown                                    | 6         | 7.32%   |
| RPi Raspberry Pi 400 Rev 1.0               | 4         | 4.88%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 4         | 4.88%   |
| RPi Raspberry Pi                           | 3         | 3.66%   |
| Pine Microsystems Pine64 PinePhonePro      | 3         | 3.66%   |
| Shenzhen Amediatech X96 Max                | 1         | 1.22%   |
| Radxa ROCK Pi 4B (DT)                      | 1         | 1.22%   |
| Radxa ROCK Pi 4                            | 1         | 1.22%   |
| PINE64 Pinebook Pro                        | 1         | 1.22%   |
| Pine Microsystems PineTab                  | 1         | 1.22%   |
| Pine Microsystems Pine64 RK3566 Quartz64-A | 1         | 1.22%   |
| Pine Microsystems Pine64 PinePhonePro (DT) | 1         | 1.22%   |
| Lenovo Yoga C630-13Q50 81JL                | 1         | 1.22%   |
| Khadas VIM2                                | 1         | 1.22%   |
| Hardkernel ODROID-N2Plus                   | 1         | 1.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| RPi Raspberry             | 34        | 41.46%  |
| Pine Microsystems Pine64  | 34        | 41.46%  |
| Unknown                   | 6         | 7.32%   |
| Radxa ROCK                | 2         | 2.44%   |
| Shenzhen Amediatech X96   | 1         | 1.22%   |
| PINE64 Pinebook           | 1         | 1.22%   |
| Pine Microsystems PineTab | 1         | 1.22%   |
| Lenovo Yoga               | 1         | 1.22%   |
| Khadas VIM2               | 1         | 1.22%   |
| Hardkernel ODROID-N2Plus  | 1         | 1.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 70        | 85.37%  |
| 2020    | 10        | 12.2%   |
| 2021    | 1         | 1.22%   |
| 2019    | 1         | 1.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| System on chip | 48        | 58.54%  |
| Phone          | 22        | 26.83%  |
| Notebook       | 11        | 13.41%  |
| Tablet         | 1         | 1.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 82        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 82        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 52        | 63.41%  |
| 4.01-8.0   | 17        | 20.73%  |
| 1.01-2.0   | 7         | 8.54%   |
| 2.01-3.0   | 6         | 7.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 47        | 53.41%  |
| 2.01-3.0 | 19        | 21.59%  |
| 0.51-1.0 | 18        | 20.45%  |
| 0.01-0.5 | 3         | 3.41%   |
| 3.01-4.0 | 1         | 1.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 61.36%  |
| 2      | 29        | 32.95%  |
| 0      | 4         | 4.55%   |
| 3      | 1         | 1.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 98.78%  |
| Yes       | 1         | 1.22%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 73        | 87.95%  |
| Yes       | 10        | 12.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 64.71%  |
| Yes       | 30        | 35.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 81        | 97.59%  |
| Yes       | 2         | 2.41%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 30        | 36.59%  |
| France       | 8         | 9.76%   |
| Germany      | 6         | 7.32%   |
| UK           | 5         | 6.1%    |
| Australia    | 5         | 6.1%    |
| Canada       | 4         | 4.88%   |
| Netherlands  | 3         | 3.66%   |
| Switzerland  | 2         | 2.44%   |
| Spain        | 2         | 2.44%   |
| Russia       | 2         | 2.44%   |
| Portugal     | 2         | 2.44%   |
| Italy        | 2         | 2.44%   |
| Turkey       | 1         | 1.22%   |
| Sweden       | 1         | 1.22%   |
| South Africa | 1         | 1.22%   |
| Poland       | 1         | 1.22%   |
| Peru         | 1         | 1.22%   |
| Malta        | 1         | 1.22%   |
| Lithuania    | 1         | 1.22%   |
| Kuwait       | 1         | 1.22%   |
| India        | 1         | 1.22%   |
| Finland      | 1         | 1.22%   |
| Cyprus       | 1         | 1.22%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Greoux-les-Bains       | 5         | 5.75%   |
| London                 | 2         | 2.3%    |
| Denver                 | 2         | 2.3%    |
| Berlin                 | 2         | 2.3%    |
| Adelaide               | 2         | 2.3%    |
| Yaroslavl              | 1         | 1.15%   |
| Wooster                | 1         | 1.15%   |
| Woodville              | 1         | 1.15%   |
| Weinheim               | 1         | 1.15%   |
| Viseu                  | 1         | 1.15%   |
| Virginia Beach         | 1         | 1.15%   |
| Vallauris              | 1         | 1.15%   |
| Thun                   | 1         | 1.15%   |
| Sydney                 | 1         | 1.15%   |
| Strasbourg             | 1         | 1.15%   |
| Springboro             | 1         | 1.15%   |
| San Mateo              | 1         | 1.15%   |
| San Germano Vercellese | 1         | 1.15%   |
| San Francisco          | 1         | 1.15%   |
| San Diego              | 1         | 1.15%   |
| Rotterdam              | 1         | 1.15%   |
| Redding                | 1         | 1.15%   |
| Potomac                | 1         | 1.15%   |
| Portland               | 1         | 1.15%   |
| Pinetop-Lakeside       | 1         | 1.15%   |
| Perth                  | 1         | 1.15%   |
| Perm                   | 1         | 1.15%   |
| Pabianice              | 1         | 1.15%   |
| Nottingham             | 1         | 1.15%   |
| North Battleford       | 1         | 1.15%   |
| North Adams            | 1         | 1.15%   |
| New Delhi              | 1         | 1.15%   |
| Naxxar                 | 1         | 1.15%   |
| Moscow                 | 1         | 1.15%   |
| Montreal               | 1         | 1.15%   |
| Melbourne              | 1         | 1.15%   |
| Mannens                | 1         | 1.15%   |
| Manchester             | 1         | 1.15%   |
| Madrid                 | 1         | 1.15%   |
| Lusby                  | 1         | 1.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Unknown             | 72        | 104    | 76.6%   |
| SanDisk             | 4         | 5      | 4.26%   |
| Seagate             | 3         | 5      | 3.19%   |
| ASMT                | 3         | 3      | 3.19%   |
| Toshiba             | 2         | 2      | 2.13%   |
| Argon               | 2         | 3      | 2.13%   |
| USB3.0              | 1         | 1      | 1.06%   |
| SK hynix            | 1         | 2      | 1.06%   |
| Samsung Electronics | 1         | 5      | 1.06%   |
| PNY USB             | 1         | 1      | 1.06%   |
| Phison              | 1         | 1      | 1.06%   |
| LaCie               | 1         | 1      | 1.06%   |
| Kingston            | 1         | 1      | 1.06%   |
| Intel               | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown MMC Card  32GB         | 27        | 25%     |
| Unknown MMC Card  64GB         | 17        | 15.74%  |
| Unknown MMC Card  128GB        | 17        | 15.74%  |
| Unknown SLD32G  32GB           | 5         | 4.63%   |
| Unknown SE32G  32GB            | 5         | 4.63%   |
| Unknown DA4064  64GB           | 4         | 3.7%    |
| Unknown MMC Card  256GB        | 3         | 2.78%   |
| ASMT 2115 320GB                | 3         | 2.78%   |
| Unknown MMC Card  16GB         | 2         | 1.85%   |
| Seagate Expansion 4TB          | 2         | 1.85%   |
| Argon Forty 120GB              | 2         | 1.85%   |
| USB3.0 Disk 2TB                | 1         | 0.93%   |
| Unknown SN64G  64GB            | 1         | 0.93%   |
| Unknown SN128  128GB           | 1         | 0.93%   |
| Unknown SL64G  64GB            | 1         | 0.93%   |
| Unknown SC32G  32GB            | 1         | 0.93%   |
| Unknown MMC Card  249GB        | 1         | 0.93%   |
| Unknown CJTD4R  64GB           | 1         | 0.93%   |
| Toshiba NVMe SSD Drive 256GB   | 1         | 0.93%   |
| Toshiba HDWD240 4TB            | 1         | 0.93%   |
| SK hynix HBG4e  32GB           | 1         | 0.93%   |
| Seagate Expansion Desk 5TB     | 1         | 0.93%   |
| SanDisk SSD PLUS 240GB         | 1         | 0.93%   |
| SanDisk SL32G  32GB            | 1         | 0.93%   |
| SanDisk Portable SSD 1TB       | 1         | 0.93%   |
| SanDisk Extreme 55AE 1TB SSD   | 1         | 0.93%   |
| Samsung Portable SSD T5 500GB  | 1         | 0.93%   |
| PNY USB 3.0 TO SATA 1TB SSD    | 1         | 0.93%   |
| Phison NVMe SSD Drive 256GB    | 1         | 0.93%   |
| LaCie Rugged USB-C 2TB         | 1         | 0.93%   |
| Kingston SHFS37A120G 120GB SSD | 1         | 0.93%   |
| Intel NVMe SSD Drive 512GB     | 1         | 0.93%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 5      | 37.5%   |
| ASMT    | 3         | 3      | 37.5%   |
| USB3.0  | 1         | 1      | 12.5%   |
| Toshiba | 1         | 1      | 12.5%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 3         | 3      | 37.5%   |
| Argon               | 2         | 3      | 25%     |
| Samsung Electronics | 1         | 5      | 12.5%   |
| PNY USB             | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| MMC     | 72        | 108    | 79.12%  |
| SSD     | 8         | 13     | 8.79%   |
| HDD     | 7         | 10     | 7.69%   |
| NVMe    | 3         | 3      | 3.3%    |
| Unknown | 1         | 1      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| MMC  | 72        | 108    | 78.26%  |
| SAS  | 16        | 23     | 17.39%  |
| NVMe | 3         | 3      | 3.26%   |
| SATA | 1         | 1      | 1.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8         | 13     | 50%     |
| 3.01-4.0   | 3         | 5      | 18.75%  |
| 0.51-1.0   | 3         | 3      | 18.75%  |
| 1.01-2.0   | 1         | 1      | 6.25%   |
| 4.01-10.0  | 1         | 1      | 6.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 27        | 31.03%  |
| 101-250        | 21        | 24.14%  |
| 51-100         | 21        | 24.14%  |
| 251-500        | 10        | 11.49%  |
| 1001-2000      | 2         | 2.3%    |
| 1-20           | 2         | 2.3%    |
| 501-1000       | 2         | 2.3%    |
| More than 3000 | 1         | 1.15%   |
| Unknown        | 1         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 51        | 57.3%   |
| 21-50     | 22        | 24.72%  |
| 51-100    | 8         | 8.99%   |
| 251-500   | 3         | 3.37%   |
| 101-250   | 3         | 3.37%   |
| 1001-2000 | 1         | 1.12%   |
| Unknown   | 1         | 1.12%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 78        | 132    | 96.3%   |
| Works    | 3         | 3      | 3.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Toshiba America Info Systems | 1         | 33.33%  |
| Phison Electronics           | 1         | 33.33%  |
| Intel                        | 1         | 33.33%  |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba America Info Systems XG6 NVMe SSD Controller | 1         | 33.33%  |
| Phison E12 NVMe Controller                           | 1         | 33.33%  |
| Intel SSD 660P Series                                | 1         | 33.33%  |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 3         | 100%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| ARM      | 81        | 98.78%  |
| QUALCOMM | 1         | 1.22%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| ARM Processor      | 81        | 98.78%  |
| QUALCOMM Processor | 1         | 1.22%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model | Computers | Percent |
|-------|-----------|---------|
| Other | 82        | 100%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 40        | 48.19%  |
| Unknown | 22        | 26.51%  |
| 6       | 14        | 16.87%  |
| 2       | 7         | 8.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 47        | 56.63%  |
| Unknown | 22        | 26.51%  |
| 2       | 14        | 16.87%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 60        | 73.17%  |
| Unknown | 22        | 26.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 64-bit         | 46        | 54.76%  |
| 32-bit, 64-bit | 20        | 23.81%  |
| Unknown        | 18        | 21.43%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 100%    |

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

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Other | 82        | 100%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 100%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 100%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 12        | 25.53%  |
| Dell                 | 5         | 10.64%  |
| Iiyama               | 3         | 6.38%   |
| Hewlett-Packard      | 3         | 6.38%   |
| Ancor Communications | 3         | 6.38%   |
| Philips              | 2         | 4.26%   |
| BenQ                 | 2         | 4.26%   |
| ASUSTek Computer     | 2         | 4.26%   |
| AOC                  | 2         | 4.26%   |
| ViewSonic            | 1         | 2.13%   |
| Vestel Elektronik    | 1         | 2.13%   |
| Unknown (XXX)        | 1         | 2.13%   |
| Unknown (ADA)        | 1         | 2.13%   |
| Sceptre Tech         | 1         | 2.13%   |
| ONN                  | 1         | 2.13%   |
| InfoVision           | 1         | 2.13%   |
| HJW                  | 1         | 2.13%   |
| Grundig              | 1         | 2.13%   |
| Goldstar             | 1         | 2.13%   |
| GKK                  | 1         | 2.13%   |
| Eizo                 | 1         | 2.13%   |
| DMT                  | 1         | 2.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Iiyama PL4071UH IVM000A 3840x2160 880x490mm 39.7-inch                   | 3         | 6.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 2         | 4.26%   |
| Ancor Communications ASUS VH242 ACI24FA 1920x1080 521x293mm 23.5-inch   | 2         | 4.26%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch           | 1         | 2.13%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch    | 1         | 2.13%   |
| Unknown (XXX) HDMI     XXX0029 1920x1080 1150x650mm 52.0-inch           | 1         | 2.13%   |
| Unknown (ADA) MPI4008 ADA0004 480x800 150x100mm 7.1-inch                | 1         | 2.13%   |
| Sceptre Tech E20 SPT080D 1600x900 434x236mm 19.4-inch                   | 1         | 2.13%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch       | 1         | 2.13%   |
| Samsung Electronics SyncMaster SAM02FD 1680x1050 430x270mm 20.0-inch    | 1         | 2.13%   |
| Samsung Electronics SyncMaster SAM01D4 1440x900 410x260mm 19.1-inch     | 1         | 2.13%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch       | 1         | 2.13%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch       | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SAM0E35 1920x1080 1210x680mm 54.6-inch  | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1         | 2.13%   |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                        | 1         | 2.13%   |
| Philips PHL 252B9 PHL092C 1920x1200 540x340mm 25.1-inch                 | 1         | 2.13%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch                 | 1         | 2.13%   |
| ONN ONA18HO015 ONN0101 1920x1080 470x290mm 21.7-inch                    | 1         | 2.13%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch            | 1         | 2.13%   |
| HJW HDMI TO USB HJW0001 1920x1080 700x390mm 31.5-inch                   | 1         | 2.13%   |
| Hewlett-Packard LP2475w HWP26F8 1920x1200 546x352mm 25.6-inch           | 1         | 2.13%   |
| Hewlett-Packard f1523 HWP2607 1024x768 304x228mm 15.0-inch              | 1         | 2.13%   |
| Hewlett-Packard 22cw HWP3183 1920x1080 476x268mm 21.5-inch              | 1         | 2.13%   |
| Grundig WXGA GRU4448 1600x1200                                          | 1         | 2.13%   |
| Goldstar M228WA GSM563D 1680x1050 434x270mm 20.1-inch                   | 1         | 2.13%   |
| GKK MONITOR GKK3034 1920x1080                                           | 1         | 2.13%   |
| Eizo S1921 ENC1831 1280x1024 376x301mm 19.0-inch                        | 1         | 2.13%   |
| DMT CHHWJT* DMT0030 1440x900 710x400mm 32.1-inch                        | 1         | 2.13%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                      | 1         | 2.13%   |
| Dell P2815Q DELF05C 3840x2160 620x340mm 27.8-inch                       | 1         | 2.13%   |
| Dell P2421D DELD0FF 2560x1440 527x296mm 23.8-inch                       | 1         | 2.13%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                       | 1         | 2.13%   |
| Dell 1704FPT DEL4004 1280x1024 338x270mm 17.0-inch                      | 1         | 2.13%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                       | 1         | 2.13%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                       | 1         | 2.13%   |
| ASUSTek Computer VZ249 AUS24CC 1920x1080 527x296mm 23.8-inch            | 1         | 2.13%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch            | 1         | 2.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 20        | 45.45%  |
| 3840x2160 (4K)     | 10        | 22.73%  |
| 2560x1440 (QHD)    | 3         | 6.82%   |
| 1920x1200 (WUXGA)  | 2         | 4.55%   |
| 1680x1050 (WSXGA+) | 2         | 4.55%   |
| 1440x900 (WXGA+)   | 2         | 4.55%   |
| 1280x1024 (SXGA)   | 2         | 4.55%   |
| 1600x900 (HD+)     | 1         | 2.27%   |
| 1280x800 (WXGA)    | 1         | 2.27%   |
| 1024x768 (XGA)     | 1         | 2.27%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 27      | 9         | 19.15%  |
| 24      | 5         | 10.64%  |
| 23      | 5         | 10.64%  |
| 21      | 4         | 8.51%   |
| 84      | 3         | 6.38%   |
| 39      | 3         | 6.38%   |
| 19      | 3         | 6.38%   |
| 54      | 2         | 4.26%   |
| 25      | 2         | 4.26%   |
| 52      | 1         | 2.13%   |
| 47      | 1         | 2.13%   |
| 32      | 1         | 2.13%   |
| 31      | 1         | 2.13%   |
| 22      | 1         | 2.13%   |
| 20      | 1         | 2.13%   |
| 17      | 1         | 2.13%   |
| 15      | 1         | 2.13%   |
| 13      | 1         | 2.13%   |
| 7       | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 501-600     | 17        | 36.96%  |
| 401-500     | 7         | 15.22%  |
| 601-700     | 4         | 8.7%    |
| 1001-1500   | 4         | 8.7%    |
| 801-900     | 3         | 6.52%   |
| 1501-2000   | 3         | 6.52%   |
| 351-400     | 2         | 4.35%   |
| 301-350     | 2         | 4.35%   |
| 701-800     | 1         | 2.17%   |
| 201-300     | 1         | 2.17%   |
| 101-200     | 1         | 2.17%   |
| Unknown     | 1         | 2.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 32        | 74.42%  |
| 16/10 | 6         | 13.95%  |
| 5/4   | 3         | 6.98%   |
| 4/3   | 1         | 2.33%   |
| 3/2   | 1         | 2.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 12        | 26.67%  |
| 301-350        | 9         | 20%     |
| More than 1000 | 6         | 13.33%  |
| 151-200        | 4         | 8.89%   |
| 501-1000       | 4         | 8.89%   |
| 251-300        | 3         | 6.67%   |
| 351-500        | 2         | 4.44%   |
| 71-80          | 1         | 2.22%   |
| 1-40           | 1         | 2.22%   |
| 141-150        | 1         | 2.22%   |
| 111-120        | 1         | 2.22%   |
| Unknown        | 1         | 2.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 25        | 58.14%  |
| 101-120 | 7         | 16.28%  |
| 121-160 | 5         | 11.63%  |
| 1-50    | 3         | 6.98%   |
| 161-240 | 2         | 4.65%   |
| Unknown | 1         | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 73        | 86.9%   |
| 0     | 8         | 9.52%   |
| 2     | 3         | 3.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 6         | 28.57%  |
| TP-Link                         | 4         | 19.05%  |
| ICS Advent                      | 3         | 14.29%  |
| ASIX Electronics                | 2         | 9.52%   |
| Sigma Designs                   | 1         | 4.76%   |
| Qualcomm Atheros Communications | 1         | 4.76%   |
| Netchip Technology              | 1         | 4.76%   |
| Intel                           | 1         | 4.76%   |
| D-Link                          | 1         | 4.76%   |
| Arduino SA                      | 1         | 4.76%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| ICS Advent USB 10/100 LAN                                                            | 3         | 14.29%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                             | 2         | 9.52%   |
| ASIX AX88179 Gigabit Ethernet                                                        | 2         | 9.52%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                | 1         | 4.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 1         | 4.76%   |
| TP-Link Archer T4U ver.3                                                             | 1         | 4.76%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                  | 1         | 4.76%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                                      | 1         | 4.76%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                                  | 1         | 4.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                              | 1         | 4.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 1         | 4.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                                                | 1         | 4.76%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 1         | 4.76%   |
| Netchip Linux-USB Ethernet/RNDIS Gadget                                              | 1         | 4.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 1         | 4.76%   |
| D-Link 802.11ac NIC                                                                  | 1         | 4.76%   |
| Arduino SA Uno R3 (CDC ACM)                                                          | 1         | 4.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


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

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


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

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 3         | 33.33%  |
| ICS Advent            | 3         | 33.33%  |
| ASIX Electronics      | 2         | 22.22%  |
| Netchip Technology    | 1         | 11.11%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| ICS Advent USB 10/100 LAN                | 3         | 33.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter | 2         | 22.22%  |
| ASIX AX88179 Gigabit Ethernet            | 2         | 22.22%  |
| Realtek RTL8152 Fast Ethernet Adapter    | 1         | 11.11%  |
| Netchip Linux-USB Ethernet/RNDIS Gadget  | 1         | 11.11%  |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 9         | 50%     |
| WiFi     | 7         | 38.89%  |
| Modem    | 2         | 11.11%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3         | 60%     |
| Ethernet | 2         | 40%     |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 82        | 98.8%   |
| 1     | 1         | 1.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 70        | 82.35%  |
| Yes  | 15        | 17.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Realtek Semiconductor   | 1         | 50%     |
| Cambridge Silicon Radio | 1         | 50%     |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 1         | 50%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 50%     |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Texas Instruments         | 1         | 20%     |
| Sennheiser Communications | 1         | 20%     |
| Logitech                  | 1         | 20%     |
| Generalplus Technology    | 1         | 20%     |
| C-Media Electronics       | 1         | 20%     |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Texas Instruments PCM2902C Audio CODEC            | 1         | 20%     |
| Sennheiser Communications Sennheiser Main Audio   | 1         | 20%     |
| Logitech [G533 Wireless Headset Dongle]           | 1         | 20%     |
| Generalplus Technology USB Audio Device           | 1         | 20%     |
| C-Media Electronics Audio Adapter (Unitek Y-247A) | 1         | 20%     |

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

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Microdia                      | 9         | 69.23%  |
| OnePlus Technology (Shenzhen) | 1         | 7.69%   |
| MacroSilicon                  | 1         | 7.69%   |
| LG Electronics                | 1         | 7.69%   |
| Acer                          | 1         | 7.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Microdia USB 2.0 Camera                               | 9         | 69.23%  |
| OnePlus (Shenzhen) SM8150-MTP _SN:A05FE1A2            | 1         | 7.69%   |
| MacroSilicon USB Video                                | 1         | 7.69%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 7.69%   |
| Acer Integrated Camera                                | 1         | 7.69%   |

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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 81        | 97.59%  |
| 1     | 2         | 2.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type         | Computers | Percent |
|--------------|-----------|---------|
| Net/wireless | 2         | 100%    |

