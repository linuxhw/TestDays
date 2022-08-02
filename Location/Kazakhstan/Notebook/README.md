Linux in Kazakhstan - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kazakhstan.

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

Total: 316

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E470 20H1006HRT    | [ff4adb2f7d](https://linux-hardware.org/?probe=ff4adb2f7d) | Jul 20, 2022 |
| Sony          | VPCEA3M1R                   | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Acer          | Aspire A315-55KG            | [223d853d4e](https://linux-hardware.org/?probe=223d853d4e) | Jun 29, 2022 |
| HP            | ProBook 430 G4              | [4b4944017c](https://linux-hardware.org/?probe=4b4944017c) | Jun 25, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [83c0821672](https://linux-hardware.org/?probe=83c0821672) | Jun 25, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [822554f0be](https://linux-hardware.org/?probe=822554f0be) | Jun 23, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [3ddae75872](https://linux-hardware.org/?probe=3ddae75872) | Jun 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [47b04cd99f](https://linux-hardware.org/?probe=47b04cd99f) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430 2349NM8       | [44e08ed5c6](https://linux-hardware.org/?probe=44e08ed5c6) | Jun 04, 2022 |
| Dell          | Inspiron 7577               | [3709bf11a9](https://linux-hardware.org/?probe=3709bf11a9) | Jun 01, 2022 |
| Acer          | Aspire 5750G                | [e04f02de57](https://linux-hardware.org/?probe=e04f02de57) | May 23, 2022 |
| Acer          | Aspire 5750G                | [eb1685b47e](https://linux-hardware.org/?probe=eb1685b47e) | May 22, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Acer          | Aspire 5750G                | [910cae5e1e](https://linux-hardware.org/?probe=910cae5e1e) | May 21, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Lenovo        | V14-ADA 82C6                | [5f3fea62ab](https://linux-hardware.org/?probe=5f3fea62ab) | May 16, 2022 |
| Acer          | Aspire 5750G                | [d60d62217c](https://linux-hardware.org/?probe=d60d62217c) | May 10, 2022 |
| Acer          | Aspire 5750G                | [1c49000609](https://linux-hardware.org/?probe=1c49000609) | May 09, 2022 |
| Acer          | Aspire 5750G                | [7e229f1bb3](https://linux-hardware.org/?probe=7e229f1bb3) | May 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f0f822fa1b](https://linux-hardware.org/?probe=f0f822fa1b) | Apr 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [0324fe4cc6](https://linux-hardware.org/?probe=0324fe4cc6) | Apr 23, 2022 |
| Acer          | Aspire 5750G                | [37a57a968f](https://linux-hardware.org/?probe=37a57a968f) | Apr 19, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Dell          | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| HP            | Pavilion 17                 | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| Acer          | Aspire A315-34              | [6f53445c9d](https://linux-hardware.org/?probe=6f53445c9d) | Mar 05, 2022 |
| Acer          | Aspire A315-41G             | [565ef5309f](https://linux-hardware.org/?probe=565ef5309f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | [21e91da000](https://linux-hardware.org/?probe=21e91da000) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS2TG0D    | [f51933de6d](https://linux-hardware.org/?probe=f51933de6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a6a7106d83](https://linux-hardware.org/?probe=a6a7106d83) | Jan 26, 2022 |
| Samsung       | N100SP                      | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [b294d0719f](https://linux-hardware.org/?probe=b294d0719f) | Dec 14, 2021 |
| Dell          | XPS 13 9310                 | [38cf5730b3](https://linux-hardware.org/?probe=38cf5730b3) | Dec 08, 2021 |
| Dell          | XPS 13 9310                 | [4501078e9a](https://linux-hardware.org/?probe=4501078e9a) | Dec 08, 2021 |
| ASUSTek       | K50IE                       | [985ed9e52c](https://linux-hardware.org/?probe=985ed9e52c) | Dec 05, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| HP            | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| ASUSTek       | N56DP                       | [7332da68ec](https://linux-hardware.org/?probe=7332da68ec) | Oct 25, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [10a67c9e23](https://linux-hardware.org/?probe=10a67c9e23) | Oct 16, 2021 |
| Acer          | Aspire A315-55KG            | [79534f4c8c](https://linux-hardware.org/?probe=79534f4c8c) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1103bd0a01](https://linux-hardware.org/?probe=1103bd0a01) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [008072f061](https://linux-hardware.org/?probe=008072f061) | Oct 05, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Lenovo        | ThinkPad T480 20L6SBGK00    | [fc6636e0b5](https://linux-hardware.org/?probe=fc6636e0b5) | Sep 09, 2021 |
| HP            | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| HP            | Pavilion dm1                | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | 635                         | [06f1ff97b5](https://linux-hardware.org/?probe=06f1ff97b5) | Jul 24, 2021 |
| Elenberg      | EL_T1011                    | [c2e05805b1](https://linux-hardware.org/?probe=c2e05805b1) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| HP            | 15                          | [fcc367258f](https://linux-hardware.org/?probe=fcc367258f) | Jul 17, 2021 |
| Unknown       | Unknown                     | [b7fe3d0d08](https://linux-hardware.org/?probe=b7fe3d0d08) | Jul 16, 2021 |
| Lenovo        | ThinkPad T580 20L9S0D100    | [e7f9397916](https://linux-hardware.org/?probe=e7f9397916) | Jul 02, 2021 |
| Acer          | Aspire A715-75G             | [1d185733d4](https://linux-hardware.org/?probe=1d185733d4) | Jun 24, 2021 |
| Acer          | Mandolin                    | [c5a4b06851](https://linux-hardware.org/?probe=c5a4b06851) | Jun 13, 2021 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [6b37e8a34b](https://linux-hardware.org/?probe=6b37e8a34b) | May 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e74c6f6436](https://linux-hardware.org/?probe=e74c6f6436) | May 16, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | [b79dcdb648](https://linux-hardware.org/?probe=b79dcdb648) | May 03, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | [b02527f8e5](https://linux-hardware.org/?probe=b02527f8e5) | May 03, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [1a6e48b6a6](https://linux-hardware.org/?probe=1a6e48b6a6) | Apr 29, 2021 |
| ASUSTek       | GL553VE                     | [b4f123b6df](https://linux-hardware.org/?probe=b4f123b6df) | Apr 20, 2021 |
| Acer          | AO722                       | [6d09f4a364](https://linux-hardware.org/?probe=6d09f4a364) | Apr 20, 2021 |
| ASUSTek       | X550LA                      | [69647941af](https://linux-hardware.org/?probe=69647941af) | Apr 20, 2021 |
| Acer          | AOHAPPY2                    | [1ab9a823ac](https://linux-hardware.org/?probe=1ab9a823ac) | Apr 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [895cfbdea8](https://linux-hardware.org/?probe=895cfbdea8) | Mar 31, 2021 |
| HP            | ENVY m6                     | [1f794c0fc3](https://linux-hardware.org/?probe=1f794c0fc3) | Mar 29, 2021 |
| Dell          | Inspiron 3793               | [324235179d](https://linux-hardware.org/?probe=324235179d) | Mar 19, 2021 |
| ASUSTek       | S301LA                      | [c8c4934145](https://linux-hardware.org/?probe=c8c4934145) | Mar 17, 2021 |
| Acer          | Predator PH317-54           | [0e97801264](https://linux-hardware.org/?probe=0e97801264) | Mar 12, 2021 |
| Acer          | Nitro AN515-44              | [c58e02d129](https://linux-hardware.org/?probe=c58e02d129) | Mar 07, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| Acer          | Aspire A715-75G             | [4e22c88014](https://linux-hardware.org/?probe=4e22c88014) | Feb 18, 2021 |
| Sony          | VGN-NR430E                  | [62beb0a340](https://linux-hardware.org/?probe=62beb0a340) | Feb 04, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e5c078c0d7](https://linux-hardware.org/?probe=e5c078c0d7) | Jan 23, 2021 |
| Acer          | Aspire A315-55KG            | [c62e2ea4ae](https://linux-hardware.org/?probe=c62e2ea4ae) | Jan 22, 2021 |
| Acer          | Aspire V3-551G              | [16932ea052](https://linux-hardware.org/?probe=16932ea052) | Jan 13, 2021 |
| Acer          | Aspire V3-551G              | [b697976568](https://linux-hardware.org/?probe=b697976568) | Jan 13, 2021 |
| Acer          | Extensa 2519                | [bc19a19f7c](https://linux-hardware.org/?probe=bc19a19f7c) | Dec 22, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cd5bccf387](https://linux-hardware.org/?probe=cd5bccf387) | Dec 13, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f6edf147c0](https://linux-hardware.org/?probe=f6edf147c0) | Dec 13, 2020 |
| Acer          | Nitro AN515-52              | [7041c80e3b](https://linux-hardware.org/?probe=7041c80e3b) | Nov 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d081baf21f](https://linux-hardware.org/?probe=d081baf21f) | Nov 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f149c45438](https://linux-hardware.org/?probe=f149c45438) | Nov 21, 2020 |
| Dell          | G3 3500                     | [d6386ecea5](https://linux-hardware.org/?probe=d6386ecea5) | Nov 07, 2020 |
| Lenovo        | G580 20157                  | [29bf11dd7c](https://linux-hardware.org/?probe=29bf11dd7c) | Nov 03, 2020 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fec4f6d683](https://linux-hardware.org/?probe=fec4f6d683) | Oct 31, 2020 |
| Acer          | Nitro AN515-52              | [f6e1215c02](https://linux-hardware.org/?probe=f6e1215c02) | Oct 22, 2020 |
| ASUSTek       | U47A                        | [b7c3bb57cf](https://linux-hardware.org/?probe=b7c3bb57cf) | Oct 20, 2020 |
| HP            | Pavilion 17                 | [d016742bce](https://linux-hardware.org/?probe=d016742bce) | Oct 20, 2020 |
| HP            | 250 G3                      | [100536aea2](https://linux-hardware.org/?probe=100536aea2) | Oct 17, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [3ec85a9391](https://linux-hardware.org/?probe=3ec85a9391) | Oct 15, 2020 |
| ASUSTek       | X540SA                      | [1f6a3f87d7](https://linux-hardware.org/?probe=1f6a3f87d7) | Sep 29, 2020 |
| Dell          | Inspiron 3521               | [e9482aee87](https://linux-hardware.org/?probe=e9482aee87) | Sep 28, 2020 |
| HP            | 250 G3                      | [c0207d3878](https://linux-hardware.org/?probe=c0207d3878) | Sep 24, 2020 |
| HP            | 250 G6 Notebook PC          | [71b1302861](https://linux-hardware.org/?probe=71b1302861) | Sep 24, 2020 |
| Dell          | Inspiron 1420               | [4b713d932f](https://linux-hardware.org/?probe=4b713d932f) | Sep 10, 2020 |
| Lenovo        | ThinkPad E580 20KS004GRK    | [0a7dbcc4b4](https://linux-hardware.org/?probe=0a7dbcc4b4) | Sep 09, 2020 |
| HP            | Pavilion 17                 | [994f18c32f](https://linux-hardware.org/?probe=994f18c32f) | Sep 09, 2020 |
| Acer          | Aspire ES1-523              | [e335200dd8](https://linux-hardware.org/?probe=e335200dd8) | Sep 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9968af0598](https://linux-hardware.org/?probe=9968af0598) | Aug 25, 2020 |
| ASUSTek       | 1001HA                      | [7935f0bc4a](https://linux-hardware.org/?probe=7935f0bc4a) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | [b6c1db4e4f](https://linux-hardware.org/?probe=b6c1db4e4f) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | [5b434b68bf](https://linux-hardware.org/?probe=5b434b68bf) | Aug 23, 2020 |
| Lenovo        | G580 20157                  | [db44f2aca3](https://linux-hardware.org/?probe=db44f2aca3) | Aug 22, 2020 |
| Packard Be... | EasyNote TE11HC             | [81c427fc6a](https://linux-hardware.org/?probe=81c427fc6a) | Aug 09, 2020 |
| Dell          | Latitude E6440              | [a023894374](https://linux-hardware.org/?probe=a023894374) | Aug 01, 2020 |
| MSI           | Prestige 14 A10SC           | [790a29d708](https://linux-hardware.org/?probe=790a29d708) | Jul 28, 2020 |
| HP            | ProBook 450 G7              | [10566660a8](https://linux-hardware.org/?probe=10566660a8) | Jul 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b762726155](https://linux-hardware.org/?probe=b762726155) | Jul 08, 2020 |
| Dell          | Inspiron 5567               | [812155ca3b](https://linux-hardware.org/?probe=812155ca3b) | Jun 29, 2020 |
| Acer          | Aspire A315-51              | [61c053a60a](https://linux-hardware.org/?probe=61c053a60a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [1509883885](https://linux-hardware.org/?probe=1509883885) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5d042bc26a](https://linux-hardware.org/?probe=5d042bc26a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5c70b2f02d](https://linux-hardware.org/?probe=5c70b2f02d) | May 31, 2020 |
| Dell          | Inspiron N5110              | [d2c4164b1c](https://linux-hardware.org/?probe=d2c4164b1c) | May 24, 2020 |
| HP            | Pavilion g6                 | [470074b671](https://linux-hardware.org/?probe=470074b671) | May 14, 2020 |
| Acer          | TravelMate 5742G            | [3b5409d855](https://linux-hardware.org/?probe=3b5409d855) | May 08, 2020 |
| HP            | Pavilion g6                 | [c2f0ff23ad](https://linux-hardware.org/?probe=c2f0ff23ad) | May 02, 2020 |
| ASUSTek       | U47A                        | [3b85d1aeb4](https://linux-hardware.org/?probe=3b85d1aeb4) | Apr 20, 2020 |
| HP            | Compaq 6510b (GB867EA#AC... | [ebb74b0be7](https://linux-hardware.org/?probe=ebb74b0be7) | Apr 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [b44935169f](https://linux-hardware.org/?probe=b44935169f) | Mar 31, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [57ade58668](https://linux-hardware.org/?probe=57ade58668) | Mar 22, 2020 |
| Lenovo        | V330-14IKB 81B0             | [7ad6b7b58b](https://linux-hardware.org/?probe=7ad6b7b58b) | Mar 22, 2020 |
| HP            | Laptop 15-da0xxx            | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| HP            | Laptop 15-bs0xx             | [c219a39d00](https://linux-hardware.org/?probe=c219a39d00) | Mar 05, 2020 |
| HP            | Laptop 15-bs0xx             | [6f409ce91c](https://linux-hardware.org/?probe=6f409ce91c) | Mar 05, 2020 |
| Dell          | Inspiron 5770               | [fd882c0a0a](https://linux-hardware.org/?probe=fd882c0a0a) | Mar 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a796221](https://linux-hardware.org/?probe=dc2a796221) | Mar 01, 2020 |
| HP            | Presario CQ57               | [3de9f386b3](https://linux-hardware.org/?probe=3de9f386b3) | Feb 19, 2020 |
| Acer          | Aspire V5-572P              | [e87893d9ae](https://linux-hardware.org/?probe=e87893d9ae) | Feb 17, 2020 |
| HP            | ProBook 430 G5              | [1a22c7e1bd](https://linux-hardware.org/?probe=1a22c7e1bd) | Feb 16, 2020 |
| HP            | Presario CQ57               | [e89b7e8846](https://linux-hardware.org/?probe=e89b7e8846) | Feb 14, 2020 |
| Acer          | Aspire XXXX                 | [ce7f974b21](https://linux-hardware.org/?probe=ce7f974b21) | Feb 11, 2020 |
| Packard Be... | EasyNote TE11HC             | [fc9249082d](https://linux-hardware.org/?probe=fc9249082d) | Feb 08, 2020 |
| HP            | Laptop 15-bw0xx             | [52e1f3b9aa](https://linux-hardware.org/?probe=52e1f3b9aa) | Feb 07, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [d48f36b5c1](https://linux-hardware.org/?probe=d48f36b5c1) | Jan 28, 2020 |
| HP            | Mini 110-3500               | [70d6715873](https://linux-hardware.org/?probe=70d6715873) | Jan 28, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [76fd2a40e6](https://linux-hardware.org/?probe=76fd2a40e6) | Jan 10, 2020 |
| ASUSTek       | G46VW                       | [17b6106770](https://linux-hardware.org/?probe=17b6106770) | Dec 27, 2019 |
| ASUSTek       | G46VW                       | [d589eb2b88](https://linux-hardware.org/?probe=d589eb2b88) | Dec 27, 2019 |
| Dell          | Inspiron 3521               | [a0554a7e66](https://linux-hardware.org/?probe=a0554a7e66) | Dec 25, 2019 |
| HP            | Pavilion g6                 | [2b1a415af5](https://linux-hardware.org/?probe=2b1a415af5) | Dec 12, 2019 |
| Lenovo        | V580c 20160                 | [a90c5bff19](https://linux-hardware.org/?probe=a90c5bff19) | Dec 11, 2019 |
| Acer          | Aspire A517-51G             | [73dafbb15e](https://linux-hardware.org/?probe=73dafbb15e) | Nov 25, 2019 |
| Acer          | Aspire A517-51G             | [73d25e486f](https://linux-hardware.org/?probe=73d25e486f) | Nov 25, 2019 |
| Lenovo        | G505s 20255                 | [f50938f6b5](https://linux-hardware.org/?probe=f50938f6b5) | Nov 24, 2019 |
| Dell          | Latitude 7280               | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| Lenovo        | G505s 20255                 | [d93b73ac97](https://linux-hardware.org/?probe=d93b73ac97) | Nov 22, 2019 |
| Acer          | TravelMate 7750G            | [51f6c04c3c](https://linux-hardware.org/?probe=51f6c04c3c) | Oct 30, 2019 |
| Sony          | VPCEH2M1R                   | [7f2ba2a282](https://linux-hardware.org/?probe=7f2ba2a282) | Oct 22, 2019 |
| HP            | Presario CQ57               | [fee13f8ed2](https://linux-hardware.org/?probe=fee13f8ed2) | Oct 08, 2019 |
| Fujitsu       | LIFEBOOK AH531              | [0aea361308](https://linux-hardware.org/?probe=0aea361308) | Sep 09, 2019 |
| Fujitsu       | LIFEBOOK AH531              | [65b6a535e2](https://linux-hardware.org/?probe=65b6a535e2) | Sep 09, 2019 |
| ASUSTek       | X540SA                      | [90108d8974](https://linux-hardware.org/?probe=90108d8974) | Sep 08, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [60161c7891](https://linux-hardware.org/?probe=60161c7891) | Aug 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e79b69efe5](https://linux-hardware.org/?probe=e79b69efe5) | Aug 20, 2019 |
| ASUSTek       | X541SC                      | [6458c4f07b](https://linux-hardware.org/?probe=6458c4f07b) | Jul 22, 2019 |
| HP            | Compaq nc6320 (ES479EA#A... | [cf41ab5f1a](https://linux-hardware.org/?probe=cf41ab5f1a) | Jul 15, 2019 |
| Acer          | Aspire E5-575G              | [e4b342382f](https://linux-hardware.org/?probe=e4b342382f) | Jul 06, 2019 |
| Lenovo        | G500 20236                  | [166081ce08](https://linux-hardware.org/?probe=166081ce08) | Jul 04, 2019 |
| Acer          | Aspire E5-575G              | [0446579039](https://linux-hardware.org/?probe=0446579039) | Jun 26, 2019 |
| Dell          | Inspiron 3521               | [03073baad2](https://linux-hardware.org/?probe=03073baad2) | Jun 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [13304c8b21](https://linux-hardware.org/?probe=13304c8b21) | Jun 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [78913150c4](https://linux-hardware.org/?probe=78913150c4) | Jun 20, 2019 |
| ASUSTek       | X541SC                      | [021030c4a5](https://linux-hardware.org/?probe=021030c4a5) | May 26, 2019 |
| HP            | Pavilion dv6                | [7a702bbcca](https://linux-hardware.org/?probe=7a702bbcca) | May 18, 2019 |
| Acer          | Aspire E5-575G              | [933bd023a3](https://linux-hardware.org/?probe=933bd023a3) | May 07, 2019 |
| ASUSTek       | X550CA                      | [bee231aa07](https://linux-hardware.org/?probe=bee231aa07) | May 07, 2019 |
| Lenovo        | G500 20236                  | [780fb49d18](https://linux-hardware.org/?probe=780fb49d18) | May 04, 2019 |
| ASUSTek       | X102BA                      | [a7f7276e3d](https://linux-hardware.org/?probe=a7f7276e3d) | May 02, 2019 |
| Dell          | Inspiron 3521               | [d8da30496e](https://linux-hardware.org/?probe=d8da30496e) | May 01, 2019 |
| Dell          | Inspiron 3521               | [4030941deb](https://linux-hardware.org/?probe=4030941deb) | Apr 29, 2019 |
| ASUSTek       | X751LN                      | [9cf06d20fa](https://linux-hardware.org/?probe=9cf06d20fa) | Apr 24, 2019 |
| ASUSTek       | X541SC                      | [0837a78e1f](https://linux-hardware.org/?probe=0837a78e1f) | Apr 24, 2019 |
| Dell          | Inspiron 3521               | [5c7abc670f](https://linux-hardware.org/?probe=5c7abc670f) | Apr 22, 2019 |
| ASUSTek       | X751LN                      | [5ca452f41e](https://linux-hardware.org/?probe=5ca452f41e) | Apr 22, 2019 |
| HP            | ProBook 470 G4              | [5e83946400](https://linux-hardware.org/?probe=5e83946400) | Apr 12, 2019 |
| Fujitsu Si... | AMILO Li 1818               | [9a3017958a](https://linux-hardware.org/?probe=9a3017958a) | Apr 03, 2019 |
| Toshiba       | Satellite P105              | [fed8975477](https://linux-hardware.org/?probe=fed8975477) | Mar 04, 2019 |
| Lenovo        | IdeaPad Z500 20202          | [f100f0f205](https://linux-hardware.org/?probe=f100f0f205) | Feb 24, 2019 |
| Toshiba       | Satellite C660              | [6badaf723c](https://linux-hardware.org/?probe=6badaf723c) | Jan 20, 2019 |
| Toshiba       | Satellite C660              | [aa10ea857e](https://linux-hardware.org/?probe=aa10ea857e) | Jan 15, 2019 |
| ASUSTek       | K50IE                       | [82bb70f126](https://linux-hardware.org/?probe=82bb70f126) | Jan 02, 2019 |
| HP            | Pavilion g6                 | [dfee480fdd](https://linux-hardware.org/?probe=dfee480fdd) | Jan 01, 2019 |
| HP            | Pavilion g6                 | [00e7757462](https://linux-hardware.org/?probe=00e7757462) | Jan 01, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [88c4e3862d](https://linux-hardware.org/?probe=88c4e3862d) | Dec 27, 2018 |
| Acer          | Aspire E5-575G              | [7d028bb762](https://linux-hardware.org/?probe=7d028bb762) | Dec 25, 2018 |
| Acer          | Aspire E5-575G              | [14806ac400](https://linux-hardware.org/?probe=14806ac400) | Dec 14, 2018 |
| Packard Be... | DOT S                       | [a0fe87d229](https://linux-hardware.org/?probe=a0fe87d229) | Nov 24, 2018 |
| Packard Be... | DOT S                       | [6267c7c58d](https://linux-hardware.org/?probe=6267c7c58d) | Nov 24, 2018 |
| ASUSTek       | X540SA                      | [9f31b05c88](https://linux-hardware.org/?probe=9f31b05c88) | Nov 23, 2018 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d07d21914f](https://linux-hardware.org/?probe=d07d21914f) | Oct 27, 2018 |
| ASUSTek       | U47A                        | [0d064a18d0](https://linux-hardware.org/?probe=0d064a18d0) | Oct 24, 2018 |
| ASUSTek       | U47A                        | [5171edd107](https://linux-hardware.org/?probe=5171edd107) | Oct 24, 2018 |
| HP            | EliteBook 6930p             | [3a9c8124dd](https://linux-hardware.org/?probe=3a9c8124dd) | Oct 23, 2018 |
| HP            | EliteBook 8530p             | [51ba7cee66](https://linux-hardware.org/?probe=51ba7cee66) | Oct 17, 2018 |
| HP            | Pavilion g6                 | [ffb346f134](https://linux-hardware.org/?probe=ffb346f134) | Sep 24, 2018 |
| HP            | Pavilion dv6                | [884d5eb5ec](https://linux-hardware.org/?probe=884d5eb5ec) | Sep 16, 2018 |
| HP            | Pavilion dv6                | [622662ba7d](https://linux-hardware.org/?probe=622662ba7d) | Sep 14, 2018 |
| Unknown       | Unknown                     | [f45f9ee7ff](https://linux-hardware.org/?probe=f45f9ee7ff) | Sep 05, 2018 |
| Unknown       | Unknown                     | [07345cdc85](https://linux-hardware.org/?probe=07345cdc85) | Aug 29, 2018 |
| Lenovo        | B50-70 20384                | [b89c577552](https://linux-hardware.org/?probe=b89c577552) | Aug 26, 2018 |
| HP            | ProBook 450 G5              | [8252f20153](https://linux-hardware.org/?probe=8252f20153) | Aug 18, 2018 |
| Dell          | Inspiron 3520               | [84a1a01ff9](https://linux-hardware.org/?probe=84a1a01ff9) | Aug 12, 2018 |
| Lenovo        | G580 20157                  | [b70545cbac](https://linux-hardware.org/?probe=b70545cbac) | Aug 02, 2018 |
| Toshiba       | Portable PC                 | [3f35fe94d9](https://linux-hardware.org/?probe=3f35fe94d9) | Jul 30, 2018 |
| Lenovo        | G510 20238                  | [71278987a9](https://linux-hardware.org/?probe=71278987a9) | Jul 20, 2018 |
| HP            | Compaq CQ58                 | [19369b35ae](https://linux-hardware.org/?probe=19369b35ae) | Jul 20, 2018 |
| Lenovo        | Y50-70 20378                | [62a23cd320](https://linux-hardware.org/?probe=62a23cd320) | Jul 11, 2018 |
| HP            | Compaq CQ58                 | [99fa20eba0](https://linux-hardware.org/?probe=99fa20eba0) | Jun 21, 2018 |
| Lenovo        | G580 20157                  | [a202b59883](https://linux-hardware.org/?probe=a202b59883) | Jun 19, 2018 |
| HP            | Compaq CQ58                 | [cb1791cebb](https://linux-hardware.org/?probe=cb1791cebb) | Jun 16, 2018 |
| Sony          | VPCEB1E1R                   | [a75927fc48](https://linux-hardware.org/?probe=a75927fc48) | Jun 03, 2018 |
| Sony          | VPCEB1E1R                   | [37813189cc](https://linux-hardware.org/?probe=37813189cc) | Jun 02, 2018 |
| Sony          | VPCEB1E1R                   | [408dcf71ce](https://linux-hardware.org/?probe=408dcf71ce) | May 25, 2018 |
| Lenovo        | B50-70 20384                | [c35dc55ced](https://linux-hardware.org/?probe=c35dc55ced) | May 22, 2018 |
| Samsung       | R518                        | [0e9bb77f12](https://linux-hardware.org/?probe=0e9bb77f12) | May 17, 2018 |
| Acer          | TravelMate 7750G            | [0d5442243c](https://linux-hardware.org/?probe=0d5442243c) | Apr 13, 2018 |
| HP            | EliteBook 2560p             | [2674660d30](https://linux-hardware.org/?probe=2674660d30) | Mar 18, 2018 |
| Acer          | Predator G3-572             | [c888fc259c](https://linux-hardware.org/?probe=c888fc259c) | Feb 28, 2018 |
| Acer          | Aspire E1-571G              | [ff7067b051](https://linux-hardware.org/?probe=ff7067b051) | Feb 24, 2018 |
| ASUSTek       | X550LA                      | [f416c6d195](https://linux-hardware.org/?probe=f416c6d195) | Feb 11, 2018 |
| Lenovo        | IdeaPad Y580                | [e648c1db32](https://linux-hardware.org/?probe=e648c1db32) | Feb 10, 2018 |
| Sony          | VGN-NW320F                  | [5b4a5cecc3](https://linux-hardware.org/?probe=5b4a5cecc3) | Jan 24, 2018 |
| Sony          | VGN-NW320F                  | [8d00903b16](https://linux-hardware.org/?probe=8d00903b16) | Jan 24, 2018 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d9f6c2c974](https://linux-hardware.org/?probe=d9f6c2c974) | Jan 21, 2018 |
| HP            | EliteBook 8440p             | [0358601780](https://linux-hardware.org/?probe=0358601780) | Jan 18, 2018 |
| Lenovo        | V580c 20160                 | [4bc6c74b55](https://linux-hardware.org/?probe=4bc6c74b55) | Jan 13, 2018 |
| Acer          | Aspire E1-571G              | [b60cd6ffc3](https://linux-hardware.org/?probe=b60cd6ffc3) | Jan 12, 2018 |
| Dell          | Inspiron M5110              | [bbf43310e5](https://linux-hardware.org/?probe=bbf43310e5) | Jan 05, 2018 |
| Lenovo        | G510 20238                  | [e84d800dfe](https://linux-hardware.org/?probe=e84d800dfe) | Jan 03, 2018 |
| Lenovo        | G510 20238                  | [b322595c10](https://linux-hardware.org/?probe=b322595c10) | Jan 03, 2018 |
| Lenovo        | B590 20208                  | [519ce95e23](https://linux-hardware.org/?probe=519ce95e23) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | [ae0972b81d](https://linux-hardware.org/?probe=ae0972b81d) | Dec 27, 2017 |
| Lenovo        | V580c 20160                 | [973d383d71](https://linux-hardware.org/?probe=973d383d71) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | [ee5e52dede](https://linux-hardware.org/?probe=ee5e52dede) | Dec 26, 2017 |
| Dell          | Inspiron N5110              | [2045f82e75](https://linux-hardware.org/?probe=2045f82e75) | Dec 24, 2017 |
| Lenovo        | V580c 20160                 | [8b68d694a7](https://linux-hardware.org/?probe=8b68d694a7) | Dec 21, 2017 |
| HP            | ProBook 4720s               | [ab0b647716](https://linux-hardware.org/?probe=ab0b647716) | Dec 09, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [f2eec3b185](https://linux-hardware.org/?probe=f2eec3b185) | Dec 03, 2017 |
| ASUSTek       | X51RL                       | [701211da24](https://linux-hardware.org/?probe=701211da24) | Dec 02, 2017 |
| Dell          | Inspiron M5110              | [ee88f09ebb](https://linux-hardware.org/?probe=ee88f09ebb) | Nov 30, 2017 |
| Acer          | Aspire 5750G                | [9d18d205df](https://linux-hardware.org/?probe=9d18d205df) | Nov 11, 2017 |
| ASUSTek       | X58L                        | [de2da19087](https://linux-hardware.org/?probe=de2da19087) | Oct 20, 2017 |
| ASUSTek       | K55VD                       | [295b4e18de](https://linux-hardware.org/?probe=295b4e18de) | Sep 24, 2017 |
| Dell          | Inspiron N5050              | [072cf329f6](https://linux-hardware.org/?probe=072cf329f6) | Sep 22, 2017 |
| HP            | Pavilion 17                 | [5226a4b68c](https://linux-hardware.org/?probe=5226a4b68c) | Sep 12, 2017 |
| Dell          | Inspiron 3558               | [a10105f81f](https://linux-hardware.org/?probe=a10105f81f) | Sep 12, 2017 |
| ASUSTek       | K52JV                       | [786ab76c2d](https://linux-hardware.org/?probe=786ab76c2d) | Aug 09, 2017 |
| Sony          | VPCCB2S1R                   | [b5723ad5f5](https://linux-hardware.org/?probe=b5723ad5f5) | Aug 08, 2017 |
| Lenovo        | G580 20157                  | [a1a09287ab](https://linux-hardware.org/?probe=a1a09287ab) | Aug 06, 2017 |
| Lenovo        | IdeaPad Y580                | [258ed6aea6](https://linux-hardware.org/?probe=258ed6aea6) | Jul 27, 2017 |
| Lenovo        | IdeaPad Y580                | [493ba2eb0c](https://linux-hardware.org/?probe=493ba2eb0c) | Jul 27, 2017 |
| Lenovo        | G510 20238                  | [2613154d7e](https://linux-hardware.org/?probe=2613154d7e) | Jul 24, 2017 |
| eMachines     | E725                        | [05bce34fc0](https://linux-hardware.org/?probe=05bce34fc0) | Jul 23, 2017 |
| Acer          | Aspire V3-551G              | [92da3895dc](https://linux-hardware.org/?probe=92da3895dc) | Jul 18, 2017 |
| Dell          | Inspiron 5559               | [3753d1a422](https://linux-hardware.org/?probe=3753d1a422) | Jul 18, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [a62f8e0f39](https://linux-hardware.org/?probe=a62f8e0f39) | Jul 15, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [0a1ff9ae9c](https://linux-hardware.org/?probe=0a1ff9ae9c) | Jul 14, 2017 |
| Dell          | Inspiron 5759               | [40852e37a5](https://linux-hardware.org/?probe=40852e37a5) | Jul 12, 2017 |
| HP            | Pavilion dm3                | [008097ceb1](https://linux-hardware.org/?probe=008097ceb1) | May 30, 2017 |
| Dell          | Inspiron 3558               | [c7a96bfff1](https://linux-hardware.org/?probe=c7a96bfff1) | May 28, 2017 |
| Dell          | Inspiron 3558               | [11b4a60b6b](https://linux-hardware.org/?probe=11b4a60b6b) | May 28, 2017 |
| Lenovo        | G500 20236                  | [60a1eab059](https://linux-hardware.org/?probe=60a1eab059) | May 26, 2017 |
| HP            | Compaq 6710b (KE120EA#AC... | [278110b61f](https://linux-hardware.org/?probe=278110b61f) | May 22, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | [e8829d83b4](https://linux-hardware.org/?probe=e8829d83b4) | May 05, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | [dd2f72474b](https://linux-hardware.org/?probe=dd2f72474b) | May 02, 2017 |
| Acer          | Aspire E5-511G              | [0110e34364](https://linux-hardware.org/?probe=0110e34364) | May 01, 2017 |
| HP            | ENVY TS 17                  | [74e650e784](https://linux-hardware.org/?probe=74e650e784) | Apr 30, 2017 |
| Unknown       | Unknown                     | [f5351462b1](https://linux-hardware.org/?probe=f5351462b1) | Apr 28, 2017 |
| Dell          | Inspiron 5521               | [92a991bcec](https://linux-hardware.org/?probe=92a991bcec) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | [534d340a7a](https://linux-hardware.org/?probe=534d340a7a) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | [add5384359](https://linux-hardware.org/?probe=add5384359) | Apr 16, 2017 |
| Dell          | Inspiron M5110              | [331bda6305](https://linux-hardware.org/?probe=331bda6305) | Apr 01, 2017 |
| Dell          | Inspiron M5110              | [6d2fc341c7](https://linux-hardware.org/?probe=6d2fc341c7) | Apr 01, 2017 |
| ASUSTek       | N56DP                       | [c4a63674e5](https://linux-hardware.org/?probe=c4a63674e5) | Feb 18, 2017 |
| Fujitsu       | LIFEBOOK A530               | [a03d8130fe](https://linux-hardware.org/?probe=a03d8130fe) | Feb 06, 2017 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [c288b514d5](https://linux-hardware.org/?probe=c288b514d5) | Jan 22, 2017 |
| ASUSTek       | N53SM                       | [26849207d6](https://linux-hardware.org/?probe=26849207d6) | Jan 19, 2017 |
| Dell          | Inspiron 7720               | [7dff83e247](https://linux-hardware.org/?probe=7dff83e247) | Jan 04, 2017 |
| Lenovo        | ThinkPad Edge E530 3259C... | [58cb3c3ef1](https://linux-hardware.org/?probe=58cb3c3ef1) | Dec 23, 2016 |
| Lenovo        | ThinkPad Edge E530 3259C... | [8af0bb111e](https://linux-hardware.org/?probe=8af0bb111e) | Dec 20, 2016 |
| Lenovo        | G565 20071                  | [e6972d050f](https://linux-hardware.org/?probe=e6972d050f) | Dec 16, 2016 |
| Toshiba       | TECRA M5                    | [b4743ce437](https://linux-hardware.org/?probe=b4743ce437) | Dec 12, 2016 |
| Packard Be... | DOT S                       | [815f65352b](https://linux-hardware.org/?probe=815f65352b) | Dec 01, 2016 |
| Toshiba       | Satellite C650              | [06c50a161c](https://linux-hardware.org/?probe=06c50a161c) | Nov 29, 2016 |
| ASUSTek       | 1225C                       | [57787e36c2](https://linux-hardware.org/?probe=57787e36c2) | Nov 28, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [1ed00b7813](https://linux-hardware.org/?probe=1ed00b7813) | Nov 27, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [45b5c7374e](https://linux-hardware.org/?probe=45b5c7374e) | Nov 27, 2016 |
| Lenovo        | ThinkPad X201 3626MJ5       | [e13b0d2ee7](https://linux-hardware.org/?probe=e13b0d2ee7) | Nov 25, 2016 |
| HP            | 530                         | [b4ade385fd](https://linux-hardware.org/?probe=b4ade385fd) | Nov 24, 2016 |
| Toshiba       | Satellite 5200              | [a79789524b](https://linux-hardware.org/?probe=a79789524b) | Nov 02, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ROSA R11                     | 27        | 11.74%  |
| ROSA R10                     | 25        | 10.87%  |
| ROSA R8.1                    | 24        | 10.43%  |
| ROSA R9                      | 16        | 6.96%   |
| Ubuntu 20.04                 | 14        | 6.09%   |
| ROSA R8                      | 14        | 6.09%   |
| KDE neon 20.04               | 9         | 3.91%   |
| Ubuntu 18.04                 | 7         | 3.04%   |
| ROSA R11.1                   | 6         | 2.61%   |
| OpenMandriva 4.2             | 5         | 2.17%   |
| Debian 11                    | 5         | 2.17%   |
| Slackware 15.0               | 3         | 1.3%    |
| Arch                         | 3         | 1.3%    |
| Ubuntu 22.04                 | 2         | 0.87%   |
| Ubuntu 18.10                 | 2         | 0.87%   |
| ROSA 12.2                    | 2         | 0.87%   |
| Linux Mint 20.3              | 2         | 0.87%   |
| Linux Mint 20.1              | 2         | 0.87%   |
| KDE neon 18.04               | 2         | 0.87%   |
| Fedora 36                    | 2         | 0.87%   |
| Fedora 35                    | 2         | 0.87%   |
| Fedora 34                    | 2         | 0.87%   |
| Debian 10                    | 2         | 0.87%   |
| Arch Rolling                 | 2         | 0.87%   |
| Zorin 15                     | 1         | 0.43%   |
| Xubuntu 18.04                | 1         | 0.43%   |
| Ubuntu 21.04                 | 1         | 0.43%   |
| Ubuntu 20.10                 | 1         | 0.43%   |
| Ubuntu 18.08.34              | 1         | 0.43%   |
| Ubuntu 16.04                 | 1         | 0.43%   |
| ROSA R4-R8                   | 1         | 0.43%   |
| ROSA 12.1                    | 1         | 0.43%   |
| ROSA 12                      | 1         | 0.43%   |
| Rocky Linux 8.4              | 1         | 0.43%   |
| Pop!_OS 20.10                | 1         | 0.43%   |
| Pop!_OS 20.04                | 1         | 0.43%   |
| Peppermint 10                | 1         | 0.43%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.43%   |
| OpenMandriva 4.3             | 1         | 0.43%   |
| Manjaro 21.0.4               | 1         | 0.43%   |
| Manjaro 20.2                 | 1         | 0.43%   |
| Manjaro 20.1.1               | 1         | 0.43%   |
| Manjaro 20.0.3               | 1         | 0.43%   |
| Manjaro 18.0.0-rc            | 1         | 0.43%   |
| Manjaro                      | 1         | 0.43%   |
| Kubuntu 20.04                | 1         | 0.43%   |
| Kubuntu 19.10                | 1         | 0.43%   |
| Gentoo 2.6                   | 1         | 0.43%   |
| Finnix 121                   | 1         | 0.43%   |
| Fedora 31                    | 1         | 0.43%   |
| Endless 4.0.2                | 1         | 0.43%   |
| Endless 4.0.0                | 1         | 0.43%   |
| Endless 3.9.5                | 1         | 0.43%   |
| Endless 3.9.3-nexthw1        | 1         | 0.43%   |
| Endless 3.9.3                | 1         | 0.43%   |
| Endless 3.9.1-nexthw2        | 1         | 0.43%   |
| Endless 3.8.5                | 1         | 0.43%   |
| Endless 3.7.7                | 1         | 0.43%   |
| Endless 3.7.5-nexthw1        | 1         | 0.43%   |
| Endless 3.6.2                | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| ROSA         | 107       | 49.08%  |
| Ubuntu       | 29        | 13.3%   |
| Endless      | 17        | 7.8%    |
| KDE neon     | 11        | 5.05%   |
| Fedora       | 7         | 3.21%   |
| Debian       | 7         | 3.21%   |
| OpenMandriva | 6         | 2.75%   |
| Manjaro      | 6         | 2.75%   |
| Linux Mint   | 4         | 1.83%   |
| Slackware    | 3         | 1.38%   |
| Arch         | 3         | 1.38%   |
| Pop!_OS      | 2         | 0.92%   |
| Kubuntu      | 2         | 0.92%   |
| Elementary   | 2         | 0.92%   |
| CentOS       | 2         | 0.92%   |
| Zorin        | 1         | 0.46%   |
| Xubuntu      | 1         | 0.46%   |
| Rocky Linux  | 1         | 0.46%   |
| Peppermint   | 1         | 0.46%   |
| openSUSE     | 1         | 0.46%   |
| Gentoo       | 1         | 0.46%   |
| Finnix       | 1         | 0.46%   |
| Ctlos        | 1         | 0.46%   |
| Clear Linux  | 1         | 0.46%   |
| antiX        | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 4.15.0-desktop-45.1rosa-x86_64     | 17        | 7%      |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 16        | 6.58%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 15        | 6.17%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 7         | 2.88%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 6         | 2.47%   |
| 5.10.14-desktop-1omv4002           | 5         | 2.06%   |
| 4.1.38-nrj-desktop-2rosa-x86_64    | 5         | 2.06%   |
| 4.1.34-nrj-desktop-2rosa-i586      | 5         | 2.06%   |
| 5.10.0-8-amd64                     | 4         | 1.65%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 4         | 1.65%   |
| 4.9.9-nrj-desktop-1rosa-x86_64     | 4         | 1.65%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 4         | 1.65%   |
| 4.9.20-nrj-desktop-1rosa-i586      | 4         | 1.65%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 4         | 1.65%   |
| 4.9.9-nrj-desktop-1rosa-i586       | 3         | 1.23%   |
| 4.9.111-nrj-desktop-2rosa-x86_64   | 3         | 1.23%   |
| 4.15.0-desktop-47.2rosa-x86_64     | 3         | 1.23%   |
| 5.8.0-44-generic                   | 2         | 0.82%   |
| 5.8.0-14-generic                   | 2         | 0.82%   |
| 5.4.83-generic-2rosa-x86_64        | 2         | 0.82%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.82%   |
| 5.4.0-42-generic                   | 2         | 0.82%   |
| 5.4.0-39-generic                   | 2         | 0.82%   |
| 5.15.19                            | 2         | 0.82%   |
| 5.11.0-35-generic                  | 2         | 0.82%   |
| 5.11.0-34-generic                  | 2         | 0.82%   |
| 5.0.0-37-generic                   | 2         | 0.82%   |
| 4.9.34-nrj-desktop-1rosa-x86_64    | 2         | 0.82%   |
| 4.16.0-4-generic                   | 2         | 0.82%   |
| 4.15.0-desktop-45.1rosa-i586       | 2         | 0.82%   |
| 5.9.8-050908-generic               | 1         | 0.41%   |
| 5.9.6-050906-generic               | 1         | 0.41%   |
| 5.9.1-zen1-1-zen                   | 1         | 0.41%   |
| 5.8.6-1-MANJARO                    | 1         | 0.41%   |
| 5.8.18-1-MANJARO                   | 1         | 0.41%   |
| 5.8.11-1-MANJARO                   | 1         | 0.41%   |
| 5.8.10-987.native                  | 1         | 0.41%   |
| 5.8.0-43-generic                   | 1         | 0.41%   |
| 5.7.0-2-amd64                      | 1         | 0.41%   |
| 5.6.4-arch1-1                      | 1         | 0.41%   |
| 5.6.15-1-MANJARO                   | 1         | 0.41%   |
| 5.4.5-300.fc31.x86_64              | 1         | 0.41%   |
| 5.4.32-generic-2rosa-i586          | 1         | 0.41%   |
| 5.4.157-1.el8.elrepo.x86_64        | 1         | 0.41%   |
| 5.4.150-generic-1rosa2021.1-x86_64 | 1         | 0.41%   |
| 5.4.0-7625-generic                 | 1         | 0.41%   |
| 5.4.0-73-generic                   | 1         | 0.41%   |
| 5.4.0-66-generic                   | 1         | 0.41%   |
| 5.4.0-64-generic                   | 1         | 0.41%   |
| 5.4.0-60-generic                   | 1         | 0.41%   |
| 5.4.0-52-generic                   | 1         | 0.41%   |
| 5.4.0-48-generic                   | 1         | 0.41%   |
| 5.4.0-47-generic                   | 1         | 0.41%   |
| 5.4.0-40-generic                   | 1         | 0.41%   |
| 5.4.0-28-generic                   | 1         | 0.41%   |
| 5.4.0-26-generic                   | 1         | 0.41%   |
| 5.4.0-120-generic                  | 1         | 0.41%   |
| 5.4.0-113-generic                  | 1         | 0.41%   |
| 5.4.0-110-generic                  | 1         | 0.41%   |
| 5.3.0-53-generic                   | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 28        | 11.67%  |
| 4.9.20   | 19        | 7.92%   |
| 5.4.0    | 18        | 7.5%    |
| 4.9.60   | 17        | 7.08%   |
| 4.1.34   | 12        | 5%      |
| 5.11.0   | 10        | 4.17%   |
| 5.3.0    | 7         | 2.92%   |
| 5.0.0    | 7         | 2.92%   |
| 4.9.9    | 6         | 2.5%    |
| 4.9.124  | 6         | 2.5%    |
| 4.1.38   | 6         | 2.5%    |
| 5.8.0    | 5         | 2.08%   |
| 5.10.14  | 5         | 2.08%   |
| 5.10.0   | 5         | 2.08%   |
| 4.9.155  | 5         | 2.08%   |
| 4.18.0   | 5         | 2.08%   |
| 4.9.95   | 4         | 1.67%   |
| 4.9.41   | 4         | 1.67%   |
| 4.9.111  | 4         | 1.67%   |
| 5.4.32   | 3         | 1.25%   |
| 5.13.0   | 3         | 1.25%   |
| 4.19.0   | 3         | 1.25%   |
| 4.13.0   | 3         | 1.25%   |
| 5.4.83   | 2         | 0.83%   |
| 5.16.7   | 2         | 0.83%   |
| 5.15.19  | 2         | 0.83%   |
| 5.15.0   | 2         | 0.83%   |
| 4.9.34   | 2         | 0.83%   |
| 4.16.0   | 2         | 0.83%   |
| 5.9.8    | 1         | 0.42%   |
| 5.9.6    | 1         | 0.42%   |
| 5.9.1    | 1         | 0.42%   |
| 5.8.6    | 1         | 0.42%   |
| 5.8.18   | 1         | 0.42%   |
| 5.8.11   | 1         | 0.42%   |
| 5.8.10   | 1         | 0.42%   |
| 5.7.0    | 1         | 0.42%   |
| 5.6.4    | 1         | 0.42%   |
| 5.6.15   | 1         | 0.42%   |
| 5.4.5    | 1         | 0.42%   |
| 5.4.157  | 1         | 0.42%   |
| 5.4.150  | 1         | 0.42%   |
| 5.18.9   | 1         | 0.42%   |
| 5.17.5   | 1         | 0.42%   |
| 5.17.2   | 1         | 0.42%   |
| 5.17.12  | 1         | 0.42%   |
| 5.17.0   | 1         | 0.42%   |
| 5.15.8   | 1         | 0.42%   |
| 5.15.6   | 1         | 0.42%   |
| 5.15.16  | 1         | 0.42%   |
| 5.14.17  | 1         | 0.42%   |
| 5.14.11  | 1         | 0.42%   |
| 5.13.8   | 1         | 0.42%   |
| 5.12.12  | 1         | 0.42%   |
| 5.12.0   | 1         | 0.42%   |
| 5.10.9   | 1         | 0.42%   |
| 5.10.74  | 1         | 0.42%   |
| 5.10.71  | 1         | 0.42%   |
| 5.10.34  | 1         | 0.42%   |
| 5.10.118 | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 58        | 25.44%  |
| 4.15    | 28        | 12.28%  |
| 5.4     | 26        | 11.4%   |
| 4.1     | 19        | 8.33%   |
| 5.10    | 14        | 6.14%   |
| 5.11    | 10        | 4.39%   |
| 5.8     | 9         | 3.95%   |
| 5.3     | 7         | 3.07%   |
| 5.15    | 7         | 3.07%   |
| 5.0     | 7         | 3.07%   |
| 4.18    | 6         | 2.63%   |
| 5.17    | 4         | 1.75%   |
| 5.13    | 4         | 1.75%   |
| 4.19    | 4         | 1.75%   |
| 5.9     | 3         | 1.32%   |
| 4.13    | 3         | 1.32%   |
| 5.6     | 2         | 0.88%   |
| 5.16    | 2         | 0.88%   |
| 5.14    | 2         | 0.88%   |
| 5.12    | 2         | 0.88%   |
| 4.16    | 2         | 0.88%   |
| 5.7     | 1         | 0.44%   |
| 5.18    | 1         | 0.44%   |
| 5.1     | 1         | 0.44%   |
| 4.4     | 1         | 0.44%   |
| 4.20    | 1         | 0.44%   |
| 3.14    | 1         | 0.44%   |
| 3.10    | 1         | 0.44%   |
| 2.6     | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 189       | 88.32%  |
| i686    | 24        | 11.21%  |
| Unknown | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE4            | 86        | 38.22%  |
| GNOME           | 48        | 21.33%  |
| KDE5            | 37        | 16.44%  |
| Unknown         | 18        | 8%      |
| KDE             | 12        | 5.33%   |
| XFCE            | 7         | 3.11%   |
| X-Cinnamon      | 4         | 1.78%   |
| LXQt            | 3         | 1.33%   |
| Unity           | 2         | 0.89%   |
| sway            | 1         | 0.44%   |
| Pantheon        | 1         | 0.44%   |
| MATE            | 1         | 0.44%   |
| LXDE            | 1         | 0.44%   |
| i3              | 1         | 0.44%   |
| GNOME Flashback | 1         | 0.44%   |
| Cinnamon        | 1         | 0.44%   |
| awesome         | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 190       | 87.16%  |
| Wayland | 17        | 7.8%    |
| Unknown | 8         | 3.67%   |
| Tty     | 3         | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 86        | 38.57%  |
| Unknown | 65        | 29.15%  |
| SDDM    | 39        | 17.49%  |
| GDM     | 19        | 8.52%   |
| LightDM | 7         | 3.14%   |
| TDM     | 4         | 1.79%   |
| GDM3    | 2         | 0.9%    |
| SLiM    | 1         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 115       | 52.51%  |
| ru_RU       | 57        | 26.03%  |
| en_US       | 37        | 16.89%  |
| ru_RU.UTF_8 | 4         | 1.83%   |
| C           | 3         | 1.37%   |
| en_GB       | 2         | 0.91%   |
| en_IL       | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 123       | 55.41%  |
| EFI  | 99        | 44.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 132       | 58.93%  |
| Unknown | 74        | 33.04%  |
| Overlay | 9         | 4.02%   |
| Btrfs   | 8         | 3.57%   |
| Xfs     | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 94        | 41.96%  |
| MBR     | 73        | 32.59%  |
| GPT     | 57        | 25.45%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 195       | 88.24%  |
| Yes       | 26        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 169       | 76.47%  |
| Yes       | 52        | 23.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 49        | 23%     |
| Lenovo              | 44        | 20.66%  |
| ASUSTek Computer    | 36        | 16.9%   |
| Acer                | 30        | 14.08%  |
| Dell                | 21        | 9.86%   |
| Toshiba             | 6         | 2.82%   |
| Sony                | 6         | 2.82%   |
| Fujitsu             | 5         | 2.35%   |
| Samsung Electronics | 3         | 1.41%   |
| Packard Bell        | 3         | 1.41%   |
| Fujitsu Siemens     | 3         | 1.41%   |
| Unknown             | 3         | 1.41%   |
| MSI                 | 1         | 0.47%   |
| IBM                 | 1         | 0.47%   |
| eMachines           | 1         | 0.47%   |
| Elenberg            | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| HP Pavilion g6                                                                           | 5         | 2.35%   |
| Lenovo G510 20238                                                                        | 3         | 1.41%   |
| Lenovo G500 20236                                                                        | 3         | 1.41%   |
| Fujitsu LIFEBOOK AH531                                                                   | 3         | 1.41%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR                                                     | 3         | 1.41%   |
| Acer Aspire E5-575G                                                                      | 3         | 1.41%   |
| Unknown                                                                                  | 3         | 1.41%   |
| Packard Bell DOT S                                                                       | 2         | 0.94%   |
| Lenovo ThinkPad Edge E530 3259CEG                                                        | 2         | 0.94%   |
| Lenovo ThinkBook 14 G2 ITL 20VD                                                          | 2         | 0.94%   |
| Lenovo Legion Y540-15IRH-PG0 81SY                                                        | 2         | 0.94%   |
| HP Presario CQ57                                                                         | 2         | 0.94%   |
| HP Pavilion dv6                                                                          | 2         | 0.94%   |
| HP Compaq CQ58                                                                           | 2         | 0.94%   |
| Dell Inspiron N5110                                                                      | 2         | 0.94%   |
| ASUS X51RL                                                                               | 2         | 0.94%   |
| Acer Aspire V3-551G                                                                      | 2         | 0.94%   |
| Acer Aspire A715-75G                                                                     | 2         | 0.94%   |
| Acer Aspire 5750G                                                                        | 2         | 0.94%   |
| Toshiba TECRA M5                                                                         | 1         | 0.47%   |
| Toshiba Satellite P105                                                                   | 1         | 0.47%   |
| Toshiba Satellite C660                                                                   | 1         | 0.47%   |
| Toshiba Satellite C650                                                                   | 1         | 0.47%   |
| Toshiba Satellite 5200                                                                   | 1         | 0.47%   |
| Toshiba Portable PC                                                                      | 1         | 0.47%   |
| Sony VPCEH2M1R                                                                           | 1         | 0.47%   |
| Sony VPCEB1E1R                                                                           | 1         | 0.47%   |
| Sony VPCEA3M1R                                                                           | 1         | 0.47%   |
| Sony VPCCB2S1R                                                                           | 1         | 0.47%   |
| Sony VGN-NW320F                                                                          | 1         | 0.47%   |
| Sony VGN-NR430E                                                                          | 1         | 0.47%   |
| Samsung R518                                                                             | 1         | 0.47%   |
| Samsung N100SP                                                                           | 1         | 0.47%   |
| Samsung 350V5C/350V5X/350V4C/350V4X/351V5C/351V5X/351V4C/351V4X/3540VC/3540VX/3440VC/344 | 1         | 0.47%   |
| Packard Bell EasyNote TE11HC                                                             | 1         | 0.47%   |
| MSI Prestige 14 A10SC                                                                    | 1         | 0.47%   |
| Lenovo Yoga 300-11IBR 80M1                                                               | 1         | 0.47%   |
| Lenovo Y720-15IKB 80VR                                                                   | 1         | 0.47%   |
| Lenovo Y520-15IKBN 80WK                                                                  | 1         | 0.47%   |
| Lenovo Y50-70 20378                                                                      | 1         | 0.47%   |
| Lenovo V580c 20160                                                                       | 1         | 0.47%   |
| Lenovo V330-14IKB 81B0                                                                   | 1         | 0.47%   |
| Lenovo V14-ADA 82C6                                                                      | 1         | 0.47%   |
| Lenovo ThinkPad X201 3626MJ5                                                             | 1         | 0.47%   |
| Lenovo ThinkPad T580 20L9S0D100                                                          | 1         | 0.47%   |
| Lenovo ThinkPad T490 20N20009RT                                                          | 1         | 0.47%   |
| Lenovo ThinkPad T480 20L6SBGK00                                                          | 1         | 0.47%   |
| Lenovo ThinkPad T460 20FMS2TG0D                                                          | 1         | 0.47%   |
| Lenovo ThinkPad T430 2349NM8                                                             | 1         | 0.47%   |
| Lenovo ThinkPad E580 20KS004GRK                                                          | 1         | 0.47%   |
| Lenovo ThinkPad E470 20H1006HRT                                                          | 1         | 0.47%   |
| Lenovo Legion 7 15IMH05 81YT                                                             | 1         | 0.47%   |
| Lenovo IdeaPad Z570 HuronRiver Platform                                                  | 1         | 0.47%   |
| Lenovo IdeaPad Z500 20202                                                                | 1         | 0.47%   |
| Lenovo IdeaPad Y580                                                                      | 1         | 0.47%   |
| Lenovo IdeaPad S510p 20298                                                               | 1         | 0.47%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL                                                    | 1         | 0.47%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY                                                     | 1         | 0.47%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2                                                      | 1         | 0.47%   |
| Lenovo IdeaPad 330-15ARR 81D2                                                            | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 20        | 9.39%   |
| Dell Inspiron           | 16        | 7.51%   |
| ASUS VivoBook           | 14        | 6.57%   |
| HP Pavilion             | 13        | 6.1%    |
| Lenovo IdeaPad          | 11        | 5.16%   |
| Lenovo ThinkPad         | 10        | 4.69%   |
| HP ProBook              | 10        | 4.69%   |
| HP Compaq               | 6         | 2.82%   |
| HP Laptop               | 5         | 2.35%   |
| HP EliteBook            | 5         | 2.35%   |
| Fujitsu LIFEBOOK        | 5         | 2.35%   |
| Toshiba Satellite       | 4         | 1.88%   |
| Lenovo Legion           | 3         | 1.41%   |
| Lenovo G510             | 3         | 1.41%   |
| Lenovo G500             | 3         | 1.41%   |
| Dell Latitude           | 3         | 1.41%   |
| Unknown                 | 3         | 1.41%   |
| Packard Bell DOT        | 2         | 0.94%   |
| Lenovo ThinkBook        | 2         | 0.94%   |
| HP Presario             | 2         | 0.94%   |
| HP ENVY                 | 2         | 0.94%   |
| HP 250                  | 2         | 0.94%   |
| Fujitsu Siemens AMILO   | 2         | 0.94%   |
| ASUS X51RL              | 2         | 0.94%   |
| Acer TravelMate         | 2         | 0.94%   |
| Acer Predator           | 2         | 0.94%   |
| Acer Nitro              | 2         | 0.94%   |
| Toshiba TECRA           | 1         | 0.47%   |
| Toshiba Portable        | 1         | 0.47%   |
| Sony VPCEH2M1R          | 1         | 0.47%   |
| Sony VPCEB1E1R          | 1         | 0.47%   |
| Sony VPCEA3M1R          | 1         | 0.47%   |
| Sony VPCCB2S1R          | 1         | 0.47%   |
| Sony VGN-NW320F         | 1         | 0.47%   |
| Sony VGN-NR430E         | 1         | 0.47%   |
| Samsung R518            | 1         | 0.47%   |
| Samsung N100SP          | 1         | 0.47%   |
| Samsung 350V5C          | 1         | 0.47%   |
| Packard Bell EasyNote   | 1         | 0.47%   |
| MSI Prestige            | 1         | 0.47%   |
| Lenovo Yoga             | 1         | 0.47%   |
| Lenovo Y720-15IKB       | 1         | 0.47%   |
| Lenovo Y520-15IKBN      | 1         | 0.47%   |
| Lenovo Y50-70           | 1         | 0.47%   |
| Lenovo V580c            | 1         | 0.47%   |
| Lenovo V330-14IKB       | 1         | 0.47%   |
| Lenovo V14-ADA          | 1         | 0.47%   |
| Lenovo G580             | 1         | 0.47%   |
| Lenovo G565             | 1         | 0.47%   |
| Lenovo G505s            | 1         | 0.47%   |
| Lenovo B590             | 1         | 0.47%   |
| Lenovo B50-70           | 1         | 0.47%   |
| IBM ThinkPad            | 1         | 0.47%   |
| HP Mini                 | 1         | 0.47%   |
| HP 635                  | 1         | 0.47%   |
| HP 530                  | 1         | 0.47%   |
| HP 15                   | 1         | 0.47%   |
| Fujitsu Siemens ESPRIMO | 1         | 0.47%   |
| eMachines E725          | 1         | 0.47%   |
| Elenberg EL             | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 30        | 14.08%  |
| 2011    | 28        | 13.15%  |
| 2013    | 19        | 8.92%   |
| 2020    | 18        | 8.45%   |
| 2018    | 16        | 7.51%   |
| 2017    | 16        | 7.51%   |
| 2019    | 13        | 6.1%    |
| 2010    | 13        | 6.1%    |
| 2016    | 12        | 5.63%   |
| 2008    | 11        | 5.16%   |
| 2015    | 10        | 4.69%   |
| 2007    | 7         | 3.29%   |
| 2009    | 6         | 2.82%   |
| 2021    | 5         | 2.35%   |
| 2014    | 5         | 2.35%   |
| 2006    | 1         | 0.47%   |
| 2005    | 1         | 0.47%   |
| 2003    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 213       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 200       | 93.02%  |
| Enabled  | 15        | 6.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 213       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 67        | 30.88%  |
| 3.01-4.0   | 63        | 29.03%  |
| 8.01-16.0  | 27        | 12.44%  |
| 16.01-24.0 | 21        | 9.68%   |
| 2.01-3.0   | 15        | 6.91%   |
| 1.01-2.0   | 13        | 5.99%   |
| 0.51-1.0   | 5         | 2.3%    |
| 32.01-64.0 | 3         | 1.38%   |
| 24.01-32.0 | 2         | 0.92%   |
| Unknown    | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 94        | 40.34%  |
| 0.51-1.0   | 53        | 22.75%  |
| 2.01-3.0   | 38        | 16.31%  |
| 3.01-4.0   | 24        | 10.3%   |
| 4.01-8.0   | 13        | 5.58%   |
| 8.01-16.0  | 4         | 1.72%   |
| 0.01-0.5   | 4         | 1.72%   |
| Unknown    | 2         | 0.86%   |
| 16.01-24.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 171       | 78.8%   |
| 2      | 44        | 20.28%  |
| 3      | 2         | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 50.7%   |
| Yes       | 105       | 49.3%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 90.61%  |
| No        | 20        | 9.39%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 99.06%  |
| No        | 2         | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 75.58%  |
| No        | 53        | 24.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Kazakhstan | 213       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Almaty          | 67        | 28.51%  |
| Nur-Sultan      | 45        | 19.15%  |
| Ust-Kamenogorsk | 13        | 5.53%   |
| Kostanay        | 13        | 5.53%   |
| Karaganda       | 13        | 5.53%   |
| Aktobe          | 12        | 5.11%   |
| Pavlodar        | 9         | 3.83%   |
| Taraz           | 8         | 3.4%    |
| Petropavl       | 6         | 2.55%   |
| Semey           | 5         | 2.13%   |
| Aktau           | 5         | 2.13%   |
| Shymkent        | 4         | 1.7%    |
| Rudnyy          | 4         | 1.7%    |
| Kyzylorda       | 4         | 1.7%    |
| Ridder          | 3         | 1.28%   |
| Oral            | 3         | 1.28%   |
| Atyrau          | 3         | 1.28%   |
| Temirtau        | 2         | 0.85%   |
| Taiynsha        | 2         | 0.85%   |
| Soran           | 2         | 0.85%   |
| Shchūchīnsk   | 2         | 0.85%   |
| Balqash         | 2         | 0.85%   |
| Stepnogorsk     | 1         | 0.43%   |
| Līsakovsk      | 1         | 0.43%   |
| Kaskelen        | 1         | 0.43%   |
| Karagandy       | 1         | 0.43%   |
| Kapshagay       | 1         | 0.43%   |
| GГјlshat      | 1         | 0.43%   |
| Ekibastuz       | 1         | 0.43%   |
| Chiili          | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 71     | 19.69%  |
| WDC                 | 45        | 54     | 17.37%  |
| Toshiba             | 27        | 34     | 10.42%  |
| Samsung Electronics | 19        | 20     | 7.34%   |
| Hitachi             | 18        | 20     | 6.95%   |
| Kingston            | 15        | 15     | 5.79%   |
| Unknown             | 12        | 15     | 4.63%   |
| HGST                | 12        | 14     | 4.63%   |
| Transcend           | 8         | 8      | 3.09%   |
| SanDisk             | 7         | 8      | 2.7%    |
| SK hynix            | 6         | 6      | 2.32%   |
| Plextor             | 4         | 4      | 1.54%   |
| KIOXIA              | 4         | 6      | 1.54%   |
| Intel               | 4         | 4      | 1.54%   |
| Fujitsu             | 4         | 5      | 1.54%   |
| A-DATA Technology   | 4         | 5      | 1.54%   |
| Micron Technology   | 3         | 4      | 1.16%   |
| GeIL                | 3         | 3      | 1.16%   |
| China               | 3         | 3      | 1.16%   |
| Crucial             | 2         | 2      | 0.77%   |
| Apacer              | 2         | 2      | 0.77%   |
| Team                | 1         | 1      | 0.39%   |
| Phison              | 1         | 1      | 0.39%   |
| Kingchuxing         | 1         | 2      | 0.39%   |
| JMicron Technology  | 1         | 1      | 0.39%   |
| HUAWEI              | 1         | 1      | 0.39%   |
| Gigabyte Technology | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 6.08%   |
| Seagate ST1000LM035-1RK172 1TB      | 10        | 3.8%    |
| Toshiba MQ04ABF100 1TB              | 6         | 2.28%   |
| Toshiba MQ01ABD100 1TB              | 5         | 1.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 1.9%    |
| WDC WD10SPZX-21Z10T0 1TB            | 4         | 1.52%   |
| Toshiba MQ01ABF050 500GB            | 4         | 1.52%   |
| Seagate ST9320325AS 320GB           | 4         | 1.52%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 1.52%   |
| HGST HTS541010A9E680 1TB            | 4         | 1.52%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 1.14%   |
| Transcend TS120GSSD220S 120GB       | 3         | 1.14%   |
| SK hynix NVMe SSD Drive 512GB       | 3         | 1.14%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 1.14%   |
| Kingston SA400S37120G 120GB SSD     | 3         | 1.14%   |
| Intel NVMe SSD Drive 512GB          | 3         | 1.14%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 1.14%   |
| WDC WD7500BPVT-22HXZT3 752GB        | 2         | 0.76%   |
| WDC WD7500BPVT-08HXZT3 752GB        | 2         | 0.76%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.76%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 0.76%   |
| Unknown MMC Card  4GB               | 2         | 0.76%   |
| Unknown MMC Card  16GB              | 2         | 0.76%   |
| Toshiba MK5059GSXP 500GB            | 2         | 0.76%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.76%   |
| SanDisk NVMe SSD Drive 512GB        | 2         | 0.76%   |
| Samsung NVMe SSD Drive 256GB        | 2         | 0.76%   |
| Samsung MZVLB512HAJQ-000L7 512GB    | 2         | 0.76%   |
| Samsung MZALQ512HALU-000L2 512GB    | 2         | 0.76%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 0.76%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.76%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.76%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 0.76%   |
| Hitachi HTS547550A9E384 500GB       | 2         | 0.76%   |
| HGST HTS545050A7E380 500GB          | 2         | 0.76%   |
| China SSD 120GB                     | 2         | 0.76%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD    | 1         | 0.38%   |
| WDC WD6400BPVT-35HXZT1 640GB        | 1         | 0.38%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 0.38%   |
| WDC WD5000LPVT-08G33T1 500GB        | 1         | 0.38%   |
| WDC WD5000LPLX-00ZNTT0 500GB        | 1         | 0.38%   |
| WDC WD5000LPCX-80VHAT1 500GB        | 1         | 0.38%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 0.38%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 0.38%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 1         | 0.38%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 1         | 0.38%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 0.38%   |
| WDC WD5000BEVT-24A0RT0 500GB        | 1         | 0.38%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 0.38%   |
| WDC WD5000BEKT-80KA9T0 500GB        | 1         | 0.38%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 1         | 0.38%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 1         | 0.38%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 0.38%   |
| WDC WD2500BEKT-60PVMT0 250GB        | 1         | 0.38%   |
| WDC WD1600BEVS-07RST0 160GB         | 1         | 0.38%   |
| WDC WD1200BEVS-75RST0 120GB         | 1         | 0.38%   |
| WDC WD10SPZX-80Z10T2 1TB            | 1         | 0.38%   |
| WDC WD10SPZX-24Z10T0 1TB            | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 71     | 32.69%  |
| WDC                 | 41        | 50     | 26.28%  |
| Toshiba             | 26        | 33     | 16.67%  |
| Hitachi             | 18        | 20     | 11.54%  |
| HGST                | 12        | 14     | 7.69%   |
| Samsung Electronics | 4         | 4      | 2.56%   |
| Fujitsu             | 4         | 5      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 12     | 22.64%  |
| Transcend           | 8         | 8      | 15.09%  |
| SanDisk             | 4         | 4      | 7.55%   |
| Samsung Electronics | 4         | 5      | 7.55%   |
| Plextor             | 4         | 4      | 7.55%   |
| China               | 3         | 3      | 5.66%   |
| A-DATA Technology   | 3         | 4      | 5.66%   |
| SK hynix            | 2         | 2      | 3.77%   |
| Micron Technology   | 2         | 2      | 3.77%   |
| GeIL                | 2         | 2      | 3.77%   |
| Crucial             | 2         | 2      | 3.77%   |
| WDC                 | 1         | 1      | 1.89%   |
| Unknown             | 1         | 1      | 1.89%   |
| Team                | 1         | 1      | 1.89%   |
| Kingchuxing         | 1         | 2      | 1.89%   |
| Intel               | 1         | 1      | 1.89%   |
| Gigabyte Technology | 1         | 1      | 1.89%   |
| Apacer              | 1         | 1      | 1.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 151       | 197    | 61.13%  |
| SSD     | 48        | 56     | 19.43%  |
| NVMe    | 35        | 41     | 14.17%  |
| MMC     | 11        | 14     | 4.45%   |
| Unknown | 2         | 2      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 183       | 251    | 78.54%  |
| NVMe | 35        | 40     | 15.02%  |
| MMC  | 11        | 14     | 4.72%   |
| SAS  | 4         | 5      | 1.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 127       | 165    | 64.47%  |
| 0.51-1.0   | 70        | 88     | 35.53%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 66        | 28.45%  |
| 101-250    | 54        | 23.28%  |
| 501-1000   | 44        | 18.97%  |
| 1-20       | 26        | 11.21%  |
| 51-100     | 21        | 9.05%   |
| 1001-2000  | 10        | 4.31%   |
| 21-50      | 9         | 3.88%   |
| Unknown    | 2         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 116       | 50.66%  |
| 21-50     | 41        | 17.9%   |
| 101-250   | 26        | 11.35%  |
| 51-100    | 18        | 7.86%   |
| 251-500   | 15        | 6.55%   |
| 501-1000  | 10        | 4.37%   |
| Unknown   | 2         | 0.87%   |
| 1001-2000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 6.82%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 3      | 6.82%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 4.55%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 9      | 4.55%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 4      | 4.55%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 4.55%   |
| WDC WD7500BPVT-08HXZT3 752GB        | 1         | 1      | 2.27%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 1         | 1      | 2.27%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1         | 1      | 2.27%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 2.27%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 2.27%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 2.27%   |
| Toshiba MK3263GSX 320GB             | 1         | 1      | 2.27%   |
| Toshiba MK2552GSX 250GB             | 1         | 1      | 2.27%   |
| Toshiba MK1637GSX 160GB             | 1         | 1      | 2.27%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 2.27%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 2.27%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 2.27%   |
| Seagate ST9120822AS 120GB           | 1         | 1      | 2.27%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 2      | 2.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 2.27%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 2.27%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 2.27%   |
| Hitachi HTS725050A9A364 500GB       | 1         | 1      | 2.27%   |
| Hitachi HTS722020K9SA00 200GB       | 1         | 1      | 2.27%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.27%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 2      | 2.27%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 2.27%   |
| Hitachi HTS543216L9SA00 160GB       | 1         | 1      | 2.27%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 2.27%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 2.27%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.27%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 2.27%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 23     | 29.55%  |
| Hitachi             | 11        | 12     | 25%     |
| Toshiba             | 8         | 9      | 18.18%  |
| WDC                 | 5         | 5      | 11.36%  |
| HGST                | 5         | 6      | 11.36%  |
| Samsung Electronics | 1         | 1      | 2.27%   |
| Plextor             | 1         | 1      | 2.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 23     | 30.23%  |
| Hitachi             | 11        | 12     | 25.58%  |
| Toshiba             | 8         | 9      | 18.6%   |
| WDC                 | 5         | 5      | 11.63%  |
| HGST                | 5         | 6      | 11.63%  |
| Samsung Electronics | 1         | 1      | 2.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 56     | 97.62%  |
| SSD  | 1         | 1      | 2.38%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 115       | 154    | 49.78%  |
| Detected | 74        | 99     | 32.03%  |
| Malfunc  | 42        | 57     | 18.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 171       | 73.08%  |
| AMD                          | 29        | 12.39%  |
| Samsung Electronics          | 11        | 4.7%    |
| SanDisk                      | 5         | 2.14%   |
| SK hynix                     | 4         | 1.71%   |
| KIOXIA                       | 3         | 1.28%   |
| Kingston Technology Company  | 3         | 1.28%   |
| Toshiba America Info Systems | 2         | 0.85%   |
| Phison Electronics           | 2         | 0.85%   |
| Union Memory (Shenzhen)      | 1         | 0.43%   |
| Nvidia                       | 1         | 0.43%   |
| Micron Technology            | 1         | 0.43%   |
| ADATA Technology             | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 9.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 23        | 8.81%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 8.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 16        | 6.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 4.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 8         | 3.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.68%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.3%    |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 2.3%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 2.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.3%    |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.92%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 1.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 1.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.53%   |
| SK hynix BC511                                                                   | 3         | 1.15%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 1.15%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.77%   |
| Intel SSD 660P Series                                                            | 2         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.77%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.77%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 2         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 2         | 0.77%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.77%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 2         | 0.77%   |
| AMD SB600 IDE                                                                    | 2         | 0.77%   |
| AMD FCH IDE Controller                                                           | 2         | 0.77%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.38%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.38%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.38%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.38%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.38%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.38%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.38%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.38%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.38%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.38%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.38%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.38%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.38%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.38%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 1         | 0.38%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.38%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.38%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 175       | 68.36%  |
| NVMe | 36        | 14.06%  |
| IDE  | 27        | 10.55%  |
| RAID | 18        | 7.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 183       | 85.92%  |
| AMD    | 30        | 14.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 2.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 2.35%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.88%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.41%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.41%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.41%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.41%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 1.41%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 3         | 1.41%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 3         | 1.41%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.94%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 2         | 0.94%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.94%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.94%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.94%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.94%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.94%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.94%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.94%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.94%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.94%   |
| Intel Core i3-2348M CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 0.94%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 2         | 0.94%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.94%   |
| Intel Celeron CPU 540 @ 1.86GHz               | 2         | 0.94%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 2         | 0.94%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.94%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.47%   |
| Intel Pentium M processor 1.86GHz             | 1         | 0.47%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.47%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.47%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.47%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.47%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.47%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.47%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.47%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.47%   |
| Intel Pentium CPU 2127U @ 1.90GHz             | 1         | 0.47%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.47%   |
| Intel Mobile Pentium 4 - M CPU 2.00GHz        | 1         | 0.47%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 60        | 28.17%  |
| Intel Core i7           | 30        | 14.08%  |
| Intel Core i3           | 30        | 14.08%  |
| Intel Celeron           | 15        | 7.04%   |
| Intel Atom              | 9         | 4.23%   |
| Intel Pentium           | 8         | 3.76%   |
| Intel Core 2 Duo        | 8         | 3.76%   |
| Other                   | 7         | 3.29%   |
| Intel Genuine           | 4         | 1.88%   |
| AMD Ryzen 5             | 4         | 1.88%   |
| AMD E                   | 4         | 1.88%   |
| AMD A8                  | 4         | 1.88%   |
| AMD A10                 | 4         | 1.88%   |
| Intel Pentium Dual-Core | 3         | 1.41%   |
| AMD Ryzen 3             | 3         | 1.41%   |
| AMD A4                  | 3         | 1.41%   |
| Intel Pentium Dual      | 2         | 0.94%   |
| Intel Core 2            | 2         | 0.94%   |
| Intel Pentium Silver    | 1         | 0.47%   |
| Intel Pentium M         | 1         | 0.47%   |
| Intel Pentium Gold      | 1         | 0.47%   |
| Intel Mobile Pentium 4  | 1         | 0.47%   |
| Intel Core Duo          | 1         | 0.47%   |
| AMD Ryzen 7             | 1         | 0.47%   |
| AMD PRO A8              | 1         | 0.47%   |
| AMD E1                  | 1         | 0.47%   |
| AMD C-60                | 1         | 0.47%   |
| AMD Athlon II           | 1         | 0.47%   |
| AMD Athlon              | 1         | 0.47%   |
| AMD A6                  | 1         | 0.47%   |
| AMD A12                 | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 136       | 63.85%  |
| 4       | 56        | 26.29%  |
| 1       | 11        | 5.16%   |
| 6       | 7         | 3.29%   |
| Unknown | 3         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 212       | 99.53%  |
| Unknown | 1         | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 149       | 69.95%  |
| 1       | 61        | 28.64%  |
| Unknown | 3         | 1.41%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 198       | 92.96%  |
| 32-bit         | 8         | 3.76%   |
| Unknown        | 7         | 3.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 11.47%  |
| 0x306a9    | 23        | 10.55%  |
| 0x206a7    | 22        | 10.09%  |
| 0x806e9    | 11        | 5.05%   |
| 0x806ea    | 9         | 4.13%   |
| 0x20655    | 8         | 3.67%   |
| 0x06001119 | 8         | 3.67%   |
| 0x906ea    | 7         | 3.21%   |
| 0x806c1    | 7         | 3.21%   |
| 0x40651    | 7         | 3.21%   |
| 0x306c3    | 7         | 3.21%   |
| 0x406e3    | 6         | 2.75%   |
| 0x1067a    | 6         | 2.75%   |
| 0x30661    | 4         | 1.83%   |
| 0xa0652    | 3         | 1.38%   |
| 0x806ec    | 3         | 1.38%   |
| 0x706a1    | 3         | 1.38%   |
| 0x6fd      | 3         | 1.38%   |
| 0x6e8      | 3         | 1.38%   |
| 0x406c4    | 3         | 1.38%   |
| 0x30678    | 3         | 1.38%   |
| 0x20652    | 3         | 1.38%   |
| 0x10676    | 3         | 1.38%   |
| 0x08108102 | 3         | 1.38%   |
| 0x906e9    | 2         | 0.92%   |
| 0x806eb    | 2         | 0.92%   |
| 0x706e5    | 2         | 0.92%   |
| 0x6ec      | 2         | 0.92%   |
| 0x306d4    | 2         | 0.92%   |
| 0x106ca    | 2         | 0.92%   |
| 0x10661    | 2         | 0.92%   |
| 0x08108109 | 2         | 0.92%   |
| 0x0700010f | 2         | 0.92%   |
| 0x05000119 | 2         | 0.92%   |
| 0x05000029 | 2         | 0.92%   |
| 0x03000027 | 2         | 0.92%   |
| 0xf27      | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x6fa      | 1         | 0.46%   |
| 0x6f6      | 1         | 0.46%   |
| 0x6d8      | 1         | 0.46%   |
| 0x406c3    | 1         | 0.46%   |
| 0x106c2    | 1         | 0.46%   |
| 0x0a50000c | 1         | 0.46%   |
| 0x08600104 | 1         | 0.46%   |
| 0x0810100b | 1         | 0.46%   |
| 0x07030105 | 1         | 0.46%   |
| 0x0600611a | 1         | 0.46%   |
| 0x06006118 | 1         | 0.46%   |
| 0x010000c8 | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 40        | 18.78%  |
| IvyBridge     | 24        | 11.27%  |
| SandyBridge   | 23        | 10.8%   |
| Haswell       | 14        | 6.57%   |
| Westmere      | 11        | 5.16%   |
| Penryn        | 10        | 4.69%   |
| Silvermont    | 9         | 4.23%   |
| Core          | 9         | 4.23%   |
| TigerLake     | 8         | 3.76%   |
| Piledriver    | 8         | 3.76%   |
| Skylake       | 7         | 3.29%   |
| Bonnell       | 7         | 3.29%   |
| P6            | 6         | 2.82%   |
| Zen+          | 5         | 2.35%   |
| Bobcat        | 5         | 2.35%   |
| IceLake       | 4         | 1.88%   |
| Goldmont plus | 4         | 1.88%   |
| CometLake     | 4         | 1.88%   |
| Zen 2         | 2         | 0.94%   |
| K10 Llano     | 2         | 0.94%   |
| Jaguar        | 2         | 0.94%   |
| Excavator     | 2         | 0.94%   |
| Broadwell     | 2         | 0.94%   |
| Zen           | 1         | 0.47%   |
| Puma          | 1         | 0.47%   |
| NetBurst      | 1         | 0.47%   |
| K10           | 1         | 0.47%   |
| Unknown       | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 164       | 56.16%  |
| Nvidia | 70        | 23.97%  |
| AMD    | 58        | 19.86%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 7.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 6.69%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.87%   |
| Intel HD Graphics 620                                                                    | 9         | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 2.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.91%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 1.91%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.59%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.59%   |
| Nvidia TU117M                                                                            | 4         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.27%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 1.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.27%   |
| Intel HD Graphics 630                                                                    | 4         | 1.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.27%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.27%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.96%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.96%   |
| Nvidia GF119M [GeForce 610M]                                                             | 3         | 0.96%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 0.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.96%   |
| Intel Kaby Lake-U GT2f HD 620 Graphics Controller                                        | 3         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.96%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 3         | 0.96%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 3         | 0.96%   |
| AMD Trinity [Radeon HD 7640G]                                                            | 3         | 0.96%   |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 3         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.64%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.64%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 2         | 0.64%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 2         | 0.64%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.64%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.64%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.64%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.64%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.64%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.64%   |
| AMD Renoir                                                                               | 2         | 0.64%   |
| AMD RC410M [Mobility Radeon Xpress 200M]                                                 | 2         | 0.64%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.32%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 41.4%   |
| Intel + Nvidia | 58        | 26.98%  |
| 1 x AMD        | 26        | 12.09%  |
| Intel + AMD    | 18        | 8.37%   |
| 2 x AMD        | 11        | 5.12%   |
| 1 x Nvidia     | 10        | 4.65%   |
| AMD + Nvidia   | 3         | 1.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 189       | 87.5%   |
| Proprietary | 23        | 10.65%  |
| Unknown     | 4         | 1.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 77        | 35.16%  |
| Unknown    | 74        | 33.79%  |
| 0.01-0.5   | 38        | 17.35%  |
| 3.01-4.0   | 17        | 7.76%   |
| 0.51-1.0   | 10        | 4.57%   |
| 5.01-6.0   | 3         | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 25.23%  |
| LG Display              | 43        | 19.37%  |
| Samsung Electronics     | 27        | 12.16%  |
| BOE                     | 25        | 11.26%  |
| Chimei Innolux          | 24        | 10.81%  |
| Chi Mei Optoelectronics | 13        | 5.86%   |
| LG Philips              | 3         | 1.35%   |
| Lenovo                  | 3         | 1.35%   |
| Goldstar                | 3         | 1.35%   |
| Acer                    | 3         | 1.35%   |
| Toshiba                 | 2         | 0.9%    |
| Sony                    | 2         | 0.9%    |
| Quanta Display          | 2         | 0.9%    |
| PANDA                   | 2         | 0.9%    |
| Hewlett-Packard         | 2         | 0.9%    |
| HannStar                | 2         | 0.9%    |
| CPT                     | 2         | 0.9%    |
| Unknown (XXX)           | 1         | 0.45%   |
| Sharp                   | 1         | 0.45%   |
| Seiko/Epson             | 1         | 0.45%   |
| Philips                 | 1         | 0.45%   |
| KDC                     | 1         | 0.45%   |
| InfoVision              | 1         | 0.45%   |
| Dell                    | 1         | 0.45%   |
| BenQ                    | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 2.68%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 4         | 1.79%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 1.34%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.34%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 1.34%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                        | 2         | 0.89%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.89%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.89%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 2         | 0.89%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 2         | 0.89%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.89%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.89%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 340x190mm 15.3-inch          | 2         | 0.89%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.89%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.89%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.89%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 2         | 0.89%   |
| AU Optronics LCD Monitor AUO1E3D 1920x1080 309x173mm 13.9-inch           | 2         | 0.89%   |
| Unknown (XXX) LCDTV XXX0180 1440x900 884x663mm 43.5-inch                 | 1         | 0.45%   |
| Toshiba Monitor LCD1701 1280x1024                                        | 1         | 0.45%   |
| Toshiba Inte TOS5086 1400x1050 290x220mm 14.3-inch                       | 1         | 0.45%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 1         | 0.45%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch     | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch      | 1         | 0.45%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch        | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3253 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 340x190mm 15.3-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0A7E 1920x1080 1060x626mm 48.5-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0A7C 1366x768 698x393mm 31.5-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM07BF 1920x1080 886x498mm 40.0-inch    | 1         | 0.45%   |
| Quanta Display LCD Monitor QDS0053 1280x800 304x190mm 14.1-inch          | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 103       | 47.69%  |
| 1920x1080 (FHD)    | 70        | 32.41%  |
| 1600x900 (HD+)     | 12        | 5.56%   |
| 1280x800 (WXGA)    | 11        | 5.09%   |
| 1024x600           | 5         | 2.31%   |
| 1680x1050 (WSXGA+) | 3         | 1.39%   |
| 1440x900 (WXGA+)   | 3         | 1.39%   |
| 2560x1440 (QHD)    | 2         | 0.93%   |
| 1400x1050          | 2         | 0.93%   |
| 1280x1024 (SXGA)   | 2         | 0.93%   |
| 3840x2160 (4K)     | 1         | 0.46%   |
| 1920x1200 (WUXGA)  | 1         | 0.46%   |
| 1024x768 (XGA)     | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 144       | 64.29%  |
| 17      | 17        | 7.59%   |
| 14      | 15        | 6.7%    |
| 13      | 13        | 5.8%    |
| 10      | 6         | 2.68%   |
| 27      | 4         | 1.79%   |
| 21      | 4         | 1.79%   |
| 11      | 4         | 1.79%   |
| 24      | 3         | 1.34%   |
| Unknown | 3         | 1.34%   |
| 19      | 2         | 0.89%   |
| 18      | 2         | 0.89%   |
| 12      | 2         | 0.89%   |
| 54      | 1         | 0.45%   |
| 43      | 1         | 0.45%   |
| 40      | 1         | 0.45%   |
| 31      | 1         | 0.45%   |
| 22      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 73.21%  |
| 351-400     | 20        | 8.93%   |
| 201-300     | 19        | 8.48%   |
| 501-600     | 7         | 3.13%   |
| 401-500     | 7         | 3.13%   |
| Unknown     | 3         | 1.34%   |
| 801-900     | 2         | 0.89%   |
| 601-700     | 1         | 0.45%   |
| 1001-1500   | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 187       | 89.05%  |
| 16/10   | 15        | 7.14%   |
| 4/3     | 4         | 1.9%    |
| 6/5     | 1         | 0.48%   |
| 5/4     | 1         | 0.48%   |
| 3/2     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 142       | 63.39%  |
| 81-90          | 21        | 9.38%   |
| 121-130        | 15        | 6.7%    |
| 71-80          | 7         | 3.13%   |
| 201-250        | 7         | 3.13%   |
| 41-50          | 6         | 2.68%   |
| 51-60          | 4         | 1.79%   |
| 301-350        | 4         | 1.79%   |
| 151-200        | 4         | 1.79%   |
| 91-100         | 3         | 1.34%   |
| Unknown        | 3         | 1.34%   |
| 131-140        | 2         | 0.89%   |
| 501-1000       | 2         | 0.89%   |
| More than 1000 | 1         | 0.45%   |
| 61-70          | 1         | 0.45%   |
| 351-500        | 1         | 0.45%   |
| 141-150        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 107       | 47.98%  |
| 121-160 | 73        | 32.74%  |
| 51-100  | 32        | 14.35%  |
| 161-240 | 5         | 2.24%   |
| 1-50    | 3         | 1.35%   |
| Unknown | 3         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 192       | 89.3%   |
| 2     | 21        | 9.77%   |
| 0     | 2         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 145       | 38.77%  |
| Intel                           | 82        | 21.93%  |
| Qualcomm Atheros                | 77        | 20.59%  |
| Broadcom                        | 26        | 6.95%   |
| Broadcom Limited                | 10        | 2.67%   |
| Ralink                          | 9         | 2.41%   |
| Marvell Technology Group        | 5         | 1.34%   |
| MediaTek                        | 4         | 1.07%   |
| Huawei Technologies             | 3         | 0.8%    |
| Hewlett-Packard                 | 3         | 0.8%    |
| Xiaomi                          | 2         | 0.53%   |
| JMicron Technology              | 2         | 0.53%   |
| Ralink Technology               | 1         | 0.27%   |
| Qualcomm Atheros Communications | 1         | 0.27%   |
| ICS Advent                      | 1         | 0.27%   |
| HTC (High Tech Computer)        | 1         | 0.27%   |
| Fujitsu Siemens Computers       | 1         | 0.27%   |
| Android                         | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 84        | 19.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 43        | 10.19%  |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 18        | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 16        | 3.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 14        | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 13        | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 12        | 2.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 10        | 2.37%   |
| Intel Wireless 8265 / 8275                                                     | 10        | 2.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 8         | 1.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 8         | 1.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 1.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 1.42%   |
| Intel Wi-Fi 6 AX201                                                            | 6         | 1.42%   |
| Intel Centrino Wireless-N 2230                                                 | 5         | 1.18%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 4         | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 4         | 0.95%   |
| Intel Wireless 3160                                                            | 4         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 4         | 0.95%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 4         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 4         | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 4         | 0.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 0.95%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 0.95%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.95%   |
| Broadcom BCM43227 802.11b/g/n                                                  | 4         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 3         | 0.71%   |
| Intel Wireless 7265                                                            | 3         | 0.71%   |
| Intel WiFi Link 5100                                                           | 3         | 0.71%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 0.71%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 3         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2         | 0.47%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 0.47%   |
| MediaTek moto e(6) plus                                                        | 2         | 0.47%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.47%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.47%   |
| Intel Wireless 7260                                                            | 2         | 0.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 2         | 0.47%   |
| Intel Centrino Wireless-N 100                                                  | 2         | 0.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 0.47%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.47%   |
| Huawei E353/E3131                                                              | 2         | 0.47%   |
| HP hs2350 HSPA+ MobileBroadband                                                | 2         | 0.47%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.24%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 1         | 0.24%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.24%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 37.38%  |
| Qualcomm Atheros                | 67        | 31.31%  |
| Realtek Semiconductor           | 25        | 11.68%  |
| Broadcom                        | 23        | 10.75%  |
| Ralink                          | 9         | 4.21%   |
| Broadcom Limited                | 5         | 2.34%   |
| MediaTek                        | 2         | 0.93%   |
| Ralink Technology               | 1         | 0.47%   |
| Qualcomm Atheros Communications | 1         | 0.47%   |
| Fujitsu Siemens Computers       | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 18        | 8.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 16        | 7.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                          | 14        | 6.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                   | 13        | 6.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 12        | 5.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                   | 10        | 4.67%   |
| Intel Wireless 8265 / 8275                                                   | 10        | 4.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                    | 8         | 3.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                        | 8         | 3.74%   |
| Intel Wi-Fi 6 AX201                                                          | 6         | 2.8%    |
| Intel Centrino Wireless-N 2230                                               | 5         | 2.34%   |
| Realtek RTL8723DE Wireless Network Adapter                                   | 4         | 1.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)      | 4         | 1.87%   |
| Intel Wireless 3160                                                          | 4         | 1.87%   |
| Intel Comet Lake PCH CNVi WiFi                                               | 4         | 1.87%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                | 4         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                 | 4         | 1.87%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 4         | 1.87%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 1.87%   |
| Broadcom BCM43227 802.11b/g/n                                                | 4         | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                   | 3         | 1.4%    |
| Intel Wireless 7265                                                          | 3         | 1.4%    |
| Intel WiFi Link 5100                                                         | 3         | 1.4%    |
| Intel Wi-Fi 6 AX200                                                          | 3         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                                | 3         | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                              | 2         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                             | 2         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                | 2         | 0.93%   |
| Intel Wireless 7260                                                          | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                              | 2         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                            | 2         | 0.93%   |
| Intel Centrino Wireless-N 100                                                | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                     | 2         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                     | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                              | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                     | 1         | 0.47%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                              | 1         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                          | 1         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                   | 1         | 0.47%   |
| Realtek 802.11ac NIC                                                         | 1         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                              | 1         | 0.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                    | 1         | 0.47%   |
| Qualcomm Atheros AR5523                                                      | 1         | 0.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)               | 1         | 0.47%   |
| Intel Wireless 8260                                                          | 1         | 0.47%   |
| Intel Wireless 3165                                                          | 1         | 0.47%   |
| Intel WiMAX/WiFi Link 5150                                                   | 1         | 0.47%   |
| Intel Ultimate N WiFi Link 5300                                              | 1         | 0.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                | 1         | 0.47%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                    | 1         | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                              | 1         | 0.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                              | 1         | 0.47%   |
| Intel Centrino Wireless-N 135                                                | 1         | 0.47%   |
| Intel Centrino Wireless-N 105                                                | 1         | 0.47%   |
| Intel Centrino Advanced-N 6235                                               | 1         | 0.47%   |
| Intel Centrino Advanced-N 6200                                               | 1         | 0.47%   |
| Fujitsu Siemens Computers miniCard D2301 802.11bg Wireless Module [SiS 163U] | 1         | 0.47%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                      | 1         | 0.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                            | 1         | 0.47%   |
| Broadcom BCM4311 802.11b/g WLAN                                              | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 132       | 66%     |
| Qualcomm Atheros         | 22        | 11%     |
| Intel                    | 19        | 9.5%    |
| Broadcom                 | 6         | 3%      |
| Marvell Technology Group | 5         | 2.5%    |
| Broadcom Limited         | 5         | 2.5%    |
| Xiaomi                   | 2         | 1%      |
| MediaTek                 | 2         | 1%      |
| JMicron Technology       | 2         | 1%      |
| Huawei Technologies      | 2         | 1%      |
| ICS Advent               | 1         | 0.5%    |
| HTC (High Tech Computer) | 1         | 0.5%    |
| Android                  | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 84        | 41.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 43        | 21.29%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 3.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 2.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 1.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.98%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.49%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 1.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.99%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.99%   |
| MediaTek moto e(6) plus                                                        | 2         | 0.99%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.99%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.99%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.99%   |
| Huawei E353/E3131                                                              | 2         | 0.99%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.5%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.5%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.5%    |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.5%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.5%    |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.5%    |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller                     | 1         | 0.5%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 1         | 0.5%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.5%    |
| HTC (High Tech Computer) MEDIACOM PhonePad G501                                | 1         | 0.5%    |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 1         | 0.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.5%    |
| Broadcom Limited NetXtreme BCM5788 Gigabit Ethernet                            | 1         | 0.5%    |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.5%    |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 1         | 0.5%    |
| Android Android                                                                | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 211       | 51.46%  |
| Ethernet | 193       | 47.07%  |
| Modem    | 6         | 1.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 177       | 79.02%  |
| Ethernet | 47        | 20.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 189       | 88.73%  |
| 1     | 22        | 10.33%  |
| 0     | 2         | 0.94%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 212       | 99.53%  |
| Yes  | 1         | 0.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 32.32%  |
| Qualcomm Atheros Communications | 18        | 10.98%  |
| IMC Networks                    | 16        | 9.76%   |
| Broadcom                        | 15        | 9.15%   |
| Realtek Semiconductor           | 14        | 8.54%   |
| Lite-On Technology              | 14        | 8.54%   |
| Ralink                          | 8         | 4.88%   |
| Hewlett-Packard                 | 7         | 4.27%   |
| Foxconn / Hon Hai               | 6         | 3.66%   |
| Toshiba                         | 5         | 3.05%   |
| Foxconn International           | 3         | 1.83%   |
| ASUSTek Computer                | 2         | 1.22%   |
| Ralink Technology               | 1         | 0.61%   |
| Cambridge Silicon Radio         | 1         | 0.61%   |
| Askey Computer                  | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 23        | 14.02%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 6.1%    |
| Realtek Bluetooth Radio                                                             | 8         | 4.88%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 4.88%   |
| Intel AX201 Bluetooth                                                               | 8         | 4.88%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 4.27%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 3.66%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 6         | 3.66%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.05%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 3.05%   |
| Broadcom HP Portable Valentine                                                      | 5         | 3.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.44%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 2.44%   |
| Intel Bluetooth Device                                                              | 3         | 1.83%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.83%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.83%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 1.83%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 1.22%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 1.22%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.22%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.22%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.22%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.22%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 1.22%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.61%   |
| Toshiba Integrated Bluetooth                                                        | 1         | 0.61%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.61%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.61%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.61%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.61%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.61%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.61%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.61%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.61%   |
| Broadcom IBM Integrated Bluetooth IV                                                | 1         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.61%   |
| Askey Bluetooth Device                                                              | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 178       | 72.36%  |
| AMD                 | 40        | 16.26%  |
| Nvidia              | 22        | 8.94%   |
| Pixart Imaging      | 1         | 0.41%   |
| Huawei Technologies | 1         | 0.41%   |
| GYROCOM C&C         | 1         | 0.41%   |
| Focusrite-Novation  | 1         | 0.41%   |
| ELMCU               | 1         | 0.41%   |
| C-Media Electronics | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 10.76%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 10.07%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 4.86%   |
| AMD FCH Azalia Controller                                                                         | 13        | 4.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 3.13%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.78%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 2.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.78%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 2.43%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.43%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.39%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.39%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.04%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.04%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 1.04%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.69%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.69%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.69%   |
| Pixart Imaging Multimedia audio controller                                                        | 1         | 0.35%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.35%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.35%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.35%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.35%   |
| Huawei Technologies USB-C HEADSET                                                                 | 1         | 0.35%   |
| GYROCOM C&C Audiotrak ProDigy CUBE                                                                | 1         | 0.35%   |
| Focusrite-Novation Scarlett Solo (3rd Gen.)                                                       | 1         | 0.35%   |
| ELMCU SG Control Mic                                                                              | 1         | 0.35%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.35%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1         | 0.35%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.35%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| SK hynix             | 49        | 25.39%  |
| Samsung Electronics  | 44        | 22.8%   |
| Unknown              | 20        | 10.36%  |
| Micron Technology    | 18        | 9.33%   |
| Kingston             | 16        | 8.29%   |
| Ramaxel Technology   | 10        | 5.18%   |
| A-DATA Technology    | 8         | 4.15%   |
| Nanya Technology     | 5         | 2.59%   |
| Transcend            | 3         | 1.55%   |
| Elpida               | 3         | 1.55%   |
| Crucial              | 3         | 1.55%   |
| Qimonda              | 2         | 1.04%   |
| GeIL                 | 2         | 1.04%   |
| ASint Technology     | 2         | 1.04%   |
| V-Color              | 1         | 0.52%   |
| Unknown (ABCD)       | 1         | 0.52%   |
| Toshiba              | 1         | 0.52%   |
| Team                 | 1         | 0.52%   |
| SHARETRONIC          | 1         | 0.52%   |
| Qumo                 | 1         | 0.52%   |
| ProMos/Mosel Vitelic | 1         | 0.52%   |
| Apacer               | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.43%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 2.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.94%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 4         | 1.94%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 4         | 1.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.46%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 3         | 1.46%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.46%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 3         | 1.46%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s        | 3         | 1.46%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 1.46%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                | 3         | 1.46%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.97%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.97%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 2         | 0.97%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.97%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.97%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.97%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.97%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.97%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.97%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.97%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.97%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s         | 2         | 0.97%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 0.97%   |
| V-Color RAM TN416G24D817 16384MB SODIMM DDR4 2400MT/s            | 1         | 0.49%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 666MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.49%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 975MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM DDR3 1333MT/s                     | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.49%   |
| Transcend RAM TS256MSQ64V5U 2048MB SODIMM DDR2 533MT/s           | 1         | 0.49%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 0.49%   |
| Transcend RAM JM1333KSU-2G 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.49%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 0.49%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.49%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 0.49%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2400MT/s                  | 1         | 0.49%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 1         | 0.49%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.49%   |
| SK hynix RAM HMT451S6MFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 93        | 60%     |
| DDR4   | 36        | 23.23%  |
| DDR2   | 14        | 9.03%   |
| SDRAM  | 7         | 4.52%   |
| LPDDR4 | 2         | 1.29%   |
| DDR    | 2         | 1.29%   |
| LPDDR3 | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 150       | 96.15%  |
| Row Of Chips | 5         | 3.21%   |
| DIMM         | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 80        | 43.72%  |
| 2048  | 43        | 23.5%   |
| 8192  | 34        | 18.58%  |
| 1024  | 17        | 9.29%   |
| 16384 | 8         | 4.37%   |
| 512   | 1         | 0.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 64        | 34.97%  |
| 1334    | 22        | 12.02%  |
| 2667    | 20        | 10.93%  |
| 1333    | 14        | 7.65%   |
| Unknown | 12        | 6.56%   |
| 2400    | 10        | 5.46%   |
| 3200    | 8         | 4.37%   |
| 667     | 7         | 3.83%   |
| 2133    | 4         | 2.19%   |
| 3266    | 3         | 1.64%   |
| 2048    | 3         | 1.64%   |
| 1067    | 3         | 1.64%   |
| 800     | 3         | 1.64%   |
| 4199    | 2         | 1.09%   |
| 975     | 2         | 1.09%   |
| 533     | 2         | 1.09%   |
| 8400    | 1         | 0.55%   |
| 4267    | 1         | 0.55%   |
| 1066    | 1         | 0.55%   |
| 666     | 1         | 0.55%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 2         | 28.57%  |
| Hewlett-Packard        | 2         | 28.57%  |
| Xerox                  | 1         | 14.29%  |
| Seiko Epson            | 1         | 14.29%  |
| Panasonic (Matsushita) | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xerox WorkCentre 6015B               | 1         | 14.29%  |
| Seiko Epson L805 Series              | 1         | 14.29%  |
| Samsung ML-1640 Series Laser Printer | 1         | 14.29%  |
| Samsung M2020 Series                 | 1         | 14.29%  |
| Panasonic (Matsushita) KX-MB1500RU   | 1         | 14.29%  |
| HP LaserJet 1020                     | 1         | 14.29%  |
| HP LaserJet 1018                     | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| HP Scanjet 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 45        | 24.86%  |
| IMC Networks                           | 23        | 12.71%  |
| Quanta                                 | 20        | 11.05%  |
| Realtek Semiconductor                  | 18        | 9.94%   |
| Acer                                   | 13        | 7.18%   |
| Suyin                                  | 11        | 6.08%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 5.52%   |
| Sunplus Innovation Technology          | 9         | 4.97%   |
| Microdia                               | 8         | 4.42%   |
| Syntek                                 | 4         | 2.21%   |
| Lite-On Technology                     | 3         | 1.66%   |
| Silicon Motion                         | 2         | 1.1%    |
| Samsung Electronics                    | 2         | 1.1%    |
| Ricoh                                  | 2         | 1.1%    |
| Primax Electronics                     | 2         | 1.1%    |
| ALi                                    | 2         | 1.1%    |
| Z-Star Microelectronics                | 1         | 0.55%   |
| SiGma Micro                            | 1         | 0.55%   |
| Nebraska Furniture Mart                | 1         | 0.55%   |
| Lenovo                                 | 1         | 0.55%   |
| Importek                               | 1         | 0.55%   |
| DJJHNA29IE70D3                         | 1         | 0.55%   |
| Alcor Micro                            | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                      | 10        | 5.49%   |
| Quanta HD Webcam                                        | 5         | 2.75%   |
| Quanta VGA WebCam                                       | 4         | 2.2%    |
| Quanta HD User Facing                                   | 4         | 2.2%    |
| Chicony Integrated Camera (1280x720@30)                 | 4         | 2.2%    |
| Chicony HD WebCam                                       | 4         | 2.2%    |
| Chicony Fujitsu Integrated Camera                       | 4         | 2.2%    |
| Acer Lenovo Integrated Webcam                           | 4         | 2.2%    |
| Suyin HP Truevision HD                                  | 3         | 1.65%   |
| Suyin 1.3M HD WebCam                                    | 3         | 1.65%   |
| Sunplus HD Webcam                                       | 3         | 1.65%   |
| Realtek Lenovo EasyCamera                               | 3         | 1.65%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 3         | 1.65%   |
| Microdia Integrated_Webcam_HD                           | 3         | 1.65%   |
| IMC Networks Integrated Camera                          | 3         | 1.65%   |
| Chicony USB2.0 0.3M UVC WebCam                          | 3         | 1.65%   |
| Chicony Integrated Camera                               | 3         | 1.65%   |
| Chicony HP Truevision HD                                | 3         | 1.65%   |
| Acer Lenovo EasyCamera                                  | 3         | 1.65%   |
| Syntek Lenovo EasyCamera                                | 2         | 1.1%    |
| Suyin Integrated_Webcam_HD                              | 2         | 1.1%    |
| Sunplus Dell HD Webcam                                  | 2         | 1.1%    |
| Samsung Galaxy A5 (MTP)                                 | 2         | 1.1%    |
| Realtek USB Camera                                      | 2         | 1.1%    |
| Realtek Integrated Webcam                               | 2         | 1.1%    |
| Realtek Acer 640 x 480 laptop camera                    | 2         | 1.1%    |
| Quanta HP Webcam                                        | 2         | 1.1%    |
| Lite-On Integrated Camera                               | 2         | 1.1%    |
| IMC Networks USB2.0 UVC HD Webcam                       | 2         | 1.1%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 2         | 1.1%    |
| IMC Networks Lenovo EasyCamera                          | 2         | 1.1%    |
| Chicony VGA WebCam                                      | 2         | 1.1%    |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.1%    |
| Chicony USB2.0 HD UVC WebCam                            | 2         | 1.1%    |
| Chicony Lenovo EasyCamera                               | 2         | 1.1%    |
| Chicony HP HD Camera                                    | 2         | 1.1%    |
| Chicony EasyCamera                                      | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 2         | 1.1%    |
| Acer Integrated Camera                                  | 2         | 1.1%    |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 0.55%   |
| Syntek Integrated Camera                                | 1         | 0.55%   |
| Syntek EasyCamera                                       | 1         | 0.55%   |
| Suyin HP Webcam                                         | 1         | 0.55%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.55%   |
| Suyin HD WebCam                                         | 1         | 0.55%   |
| Sunplus Integrated Webcam                               | 1         | 0.55%   |
| Sunplus HP Universal Camera                             | 1         | 0.55%   |
| Sunplus ASUS Webcam                                     | 1         | 0.55%   |
| Sunplus ASUS USB2.0 Webcam                              | 1         | 0.55%   |
| Silicon Motion WebCam SC-0311139N                       | 1         | 0.55%   |
| Silicon Motion Lenovo EasyCamera                        | 1         | 0.55%   |
| SiGma Micro WebCam SiGma Micro                          | 1         | 0.55%   |
| Ricoh USB2.0 Camera                                     | 1         | 0.55%   |
| Ricoh Sony Vaio Integrated Webcam                       | 1         | 0.55%   |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 0.55%   |
| Realtek Laptop_Integrated_Webcam_HD                     | 1         | 0.55%   |
| Realtek Integrated_Webcam_HD                            | 1         | 0.55%   |
| Realtek Integrated Webcam_HD                            | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 32.43%  |
| Synaptics                  | 7         | 18.92%  |
| Upek                       | 5         | 13.51%  |
| AuthenTec                  | 5         | 13.51%  |
| STMicroelectronics         | 4         | 10.81%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| Elan Microelectronics      | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 5         | 13.51%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 5         | 13.51%  |
| STMicroelectronics Fingerprint Reader                     | 4         | 10.81%  |
| AuthenTec AES2501 Fingerprint Sensor                      | 3         | 8.11%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 5.41%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 2         | 5.41%   |
| Validity Sensors Fingerprint scanner                      | 2         | 5.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 5.41%   |
| AuthenTec AES2810                                         | 2         | 5.41%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 2.7%    |
| Synaptics  WBDI                                           | 1         | 2.7%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 2.7%    |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 2.7%    |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 2.7%    |
| Shenzhen Goodix FingerPrint                               | 1         | 2.7%    |
| Elan ELAN:Fingerprint                                     | 1         | 2.7%    |
| Unknown                                                   | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 66.67%  |
| Lenovo      | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 2         | 66.67%  |
| Lenovo Integrated Smart Card Reader | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 145       | 65.61%  |
| 1     | 64        | 28.96%  |
| 2     | 10        | 4.52%   |
| 4     | 1         | 0.45%   |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 42.53%  |
| Graphics card            | 21        | 24.14%  |
| Net/wireless             | 11        | 12.64%  |
| Bluetooth                | 9         | 10.34%  |
| Communication controller | 2         | 2.3%    |
| Chipcard                 | 2         | 2.3%    |
| Camera                   | 2         | 2.3%    |
| Multimedia controller    | 1         | 1.15%   |
| Modem                    | 1         | 1.15%   |
| Card reader              | 1         | 1.15%   |

