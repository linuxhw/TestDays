Linux in Saudi Arabia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Saudi Arabia.

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

Total: 478

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [e561e361ec](https://linux-hardware.org/?probe=e561e361ec) | Dec 30, 2025 |
| Dell          | Inspiron 5502               | [15831e2be1](https://linux-hardware.org/?probe=15831e2be1) | Dec 19, 2025 |
| HP            | Laptop 15-dw3xxx            | [e2823eeadf](https://linux-hardware.org/?probe=e2823eeadf) | Dec 18, 2025 |
| Lenovo        | B590 20208                  | [bac5762ee0](https://linux-hardware.org/?probe=bac5762ee0) | Dec 16, 2025 |
| Chuwi         | CoreBook X                  | [282e58959b](https://linux-hardware.org/?probe=282e58959b) | Nov 28, 2025 |
| Acer          | Aspire 5720                 | [1f2e40a1b7](https://linux-hardware.org/?probe=1f2e40a1b7) | Nov 24, 2025 |
| Lenovo        | ThinkPad E16 Gen 3 21SR0... | [e691ddb170](https://linux-hardware.org/?probe=e691ddb170) | Nov 23, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | [673ef1ec1f](https://linux-hardware.org/?probe=673ef1ec1f) | Nov 20, 2025 |
| Lenovo        | B590 20208                  | [d07a89a846](https://linux-hardware.org/?probe=d07a89a846) | Nov 18, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | [50eec0b73e](https://linux-hardware.org/?probe=50eec0b73e) | Nov 14, 2025 |
| Samsung       | RC420/RC520/RC720           | [023ffb5068](https://linux-hardware.org/?probe=023ffb5068) | Nov 08, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | [ed18f9234f](https://linux-hardware.org/?probe=ed18f9234f) | Nov 06, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | [0f47b7de62](https://linux-hardware.org/?probe=0f47b7de62) | Nov 06, 2025 |
| Dell          | Precision 7530              | [20eaac1694](https://linux-hardware.org/?probe=20eaac1694) | Oct 20, 2025 |
| Alienware     | 17                          | [41c377766a](https://linux-hardware.org/?probe=41c377766a) | Oct 16, 2025 |
| Alienware     | 17                          | [85acbdc168](https://linux-hardware.org/?probe=85acbdc168) | Oct 16, 2025 |
| Alienware     | 17                          | [e304588bee](https://linux-hardware.org/?probe=e304588bee) | Oct 15, 2025 |
| Acer          | Aspire A514-54G             | [f1938fe030](https://linux-hardware.org/?probe=f1938fe030) | Oct 13, 2025 |
| HP            | ProBook 440 14 inch G9 N... | [b7fdc100e3](https://linux-hardware.org/?probe=b7fdc100e3) | Oct 13, 2025 |
| Dell          | Inspiron N5010              | [8a0914b2ef](https://linux-hardware.org/?probe=8a0914b2ef) | Oct 10, 2025 |
| Dell          | Inspiron N5010              | [db9fc8e121](https://linux-hardware.org/?probe=db9fc8e121) | Oct 10, 2025 |
| Lenovo        | ThinkBook 16 G8 IAL 21SK    | [9f556131d6](https://linux-hardware.org/?probe=9f556131d6) | Sep 22, 2025 |
| Lenovo        | ThinkPad E590 20NB000JAD    | [9556c5e3c2](https://linux-hardware.org/?probe=9556c5e3c2) | Sep 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [bcc527075b](https://linux-hardware.org/?probe=bcc527075b) | Sep 19, 2025 |
| Dell          | Inspiron 3542               | [aa5b87ace8](https://linux-hardware.org/?probe=aa5b87ace8) | Sep 14, 2025 |
| HP            | Pavilion 15                 | [5513973630](https://linux-hardware.org/?probe=5513973630) | Sep 13, 2025 |
| MSI           | GS65 Stealth 9SF            | [1c5e8b3995](https://linux-hardware.org/?probe=1c5e8b3995) | Sep 06, 2025 |
| Lenovo        | B50-70 20384                | [e7fdb2b489](https://linux-hardware.org/?probe=e7fdb2b489) | Sep 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5cf11399ec](https://linux-hardware.org/?probe=5cf11399ec) | Sep 02, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [493b8cc21f](https://linux-hardware.org/?probe=493b8cc21f) | Sep 01, 2025 |
| Lenovo        | LOQ 16IRH8 82XW             | [ebf8932e28](https://linux-hardware.org/?probe=ebf8932e28) | Sep 01, 2025 |
| Google        | Kip                         | [87dcf77bce](https://linux-hardware.org/?probe=87dcf77bce) | Aug 28, 2025 |
| Valve         | Jupiter                     | [a41a595678](https://linux-hardware.org/?probe=a41a595678) | Aug 23, 2025 |
| Dell          | Inspiron 3542               | [951264a489](https://linux-hardware.org/?probe=951264a489) | Aug 17, 2025 |
| Dell          | Inspiron 3542               | [0be9c5498a](https://linux-hardware.org/?probe=0be9c5498a) | Aug 12, 2025 |
| Dell          | XPS 9320                    | [e0d00d14a6](https://linux-hardware.org/?probe=e0d00d14a6) | Aug 12, 2025 |
| Dell          | XPS 9320                    | [498cc6cd71](https://linux-hardware.org/?probe=498cc6cd71) | Aug 11, 2025 |
| Lenovo        | ThinkPad E590 20NB0004AD    | [0393c8e3e2](https://linux-hardware.org/?probe=0393c8e3e2) | Aug 11, 2025 |
| Lenovo        | ThinkPad E590 20NB0004AD    | [638208dd77](https://linux-hardware.org/?probe=638208dd77) | Aug 11, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [a7b501c083](https://linux-hardware.org/?probe=a7b501c083) | Aug 10, 2025 |
| Dell          | Inspiron 3542               | [48afb96d3e](https://linux-hardware.org/?probe=48afb96d3e) | Aug 08, 2025 |
| Valve         | Jupiter                     | [80ed3c3f44](https://linux-hardware.org/?probe=80ed3c3f44) | Aug 08, 2025 |
| Apple         | MacBookAir7,2               | [4009991bb8](https://linux-hardware.org/?probe=4009991bb8) | Aug 05, 2025 |
| Apple         | MacBookAir7,2               | [aeff5dd520](https://linux-hardware.org/?probe=aeff5dd520) | Aug 05, 2025 |
| HP            | Pavilion Plus Laptop 14-... | [41d7fdff87](https://linux-hardware.org/?probe=41d7fdff87) | Aug 04, 2025 |
| SDZ           | X133                        | [e81d516062](https://linux-hardware.org/?probe=e81d516062) | Jul 31, 2025 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [d4a42ee7be](https://linux-hardware.org/?probe=d4a42ee7be) | Jul 20, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | [41494d21b1](https://linux-hardware.org/?probe=41494d21b1) | Jul 19, 2025 |
| HP            | Laptop 15-da2xxx            | [93317be9bc](https://linux-hardware.org/?probe=93317be9bc) | Jul 16, 2025 |
| HP            | Laptop 15-da2xxx            | [0fed100f19](https://linux-hardware.org/?probe=0fed100f19) | Jul 15, 2025 |
| HP            | OMEN by Laptop 15-dc1xxx    | [ed35501bf1](https://linux-hardware.org/?probe=ed35501bf1) | Jun 27, 2025 |
| HP            | Pavilion dv6                | [5702da4077](https://linux-hardware.org/?probe=5702da4077) | Jun 26, 2025 |
| Valve         | Jupiter                     | [713e7d12b5](https://linux-hardware.org/?probe=713e7d12b5) | Jun 24, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [68054ca49f](https://linux-hardware.org/?probe=68054ca49f) | Jun 23, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5e8b522b86](https://linux-hardware.org/?probe=5e8b522b86) | Jun 22, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [b2a37a1a7a](https://linux-hardware.org/?probe=b2a37a1a7a) | Jun 15, 2025 |
| Dell          | Precision 5520              | [b191cdb6c9](https://linux-hardware.org/?probe=b191cdb6c9) | Jun 13, 2025 |
| MSI           | Cyborg 15 A13VF             | [ce6f30d3fd](https://linux-hardware.org/?probe=ce6f30d3fd) | Jun 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [5211a5ca4d](https://linux-hardware.org/?probe=5211a5ca4d) | Jun 02, 2025 |
| Toshiba       | Satellite C55t-A            | [f65e2fefd1](https://linux-hardware.org/?probe=f65e2fefd1) | May 31, 2025 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [e8011c461c](https://linux-hardware.org/?probe=e8011c461c) | May 30, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | [375b82e46e](https://linux-hardware.org/?probe=375b82e46e) | May 27, 2025 |
| MSI           | GS66 Stealth 10SE           | [945b4c0478](https://linux-hardware.org/?probe=945b4c0478) | May 21, 2025 |
| Dell          | Inspiron 5521               | [ce7def4c08](https://linux-hardware.org/?probe=ce7def4c08) | May 21, 2025 |
| MSI           | GS66 Stealth 10SE           | [9244e162d4](https://linux-hardware.org/?probe=9244e162d4) | May 18, 2025 |
| HP            | Pavilion Laptop 14-dv2xx... | [075a0d49f0](https://linux-hardware.org/?probe=075a0d49f0) | May 08, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [bad6dbb459](https://linux-hardware.org/?probe=bad6dbb459) | May 07, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [40b8e0a08b](https://linux-hardware.org/?probe=40b8e0a08b) | May 07, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [afdcc4778d](https://linux-hardware.org/?probe=afdcc4778d) | May 07, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [08f098a164](https://linux-hardware.org/?probe=08f098a164) | May 07, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [d368236e4b](https://linux-hardware.org/?probe=d368236e4b) | May 02, 2025 |
| Dell          | Inspiron 1525               | [1d1cdbe295](https://linux-hardware.org/?probe=1d1cdbe295) | May 01, 2025 |
| Lenovo        | ThinkPad T480s 20L8SAWM0... | [eff24ac691](https://linux-hardware.org/?probe=eff24ac691) | May 01, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [58f0e59411](https://linux-hardware.org/?probe=58f0e59411) | Apr 28, 2025 |
| MSI           | GS66 Stealth 10UG           | [dab6be5281](https://linux-hardware.org/?probe=dab6be5281) | Apr 24, 2025 |
| Dell          | XPS 9320                    | [bd8b33fce4](https://linux-hardware.org/?probe=bd8b33fce4) | Apr 18, 2025 |
| Lenovo        | IdeaPad Yoga 13 20175       | [e604c5aa4e](https://linux-hardware.org/?probe=e604c5aa4e) | Apr 13, 2025 |
| HP            | Notebook                    | [4410242318](https://linux-hardware.org/?probe=4410242318) | Apr 12, 2025 |
| Valve         | Jupiter                     | [723f7ca000](https://linux-hardware.org/?probe=723f7ca000) | Apr 08, 2025 |
| Lenovo        | ThinkPad E15 20RD006BUS     | [73c9d22864](https://linux-hardware.org/?probe=73c9d22864) | Apr 05, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [0b06ba73f3](https://linux-hardware.org/?probe=0b06ba73f3) | Apr 05, 2025 |
| Dell          | Inspiron 3542               | [4e95173a4f](https://linux-hardware.org/?probe=4e95173a4f) | Apr 04, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [572d7825a8](https://linux-hardware.org/?probe=572d7825a8) | Apr 03, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [df8c1a2ef1](https://linux-hardware.org/?probe=df8c1a2ef1) | Apr 02, 2025 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [63ee0ec5ca](https://linux-hardware.org/?probe=63ee0ec5ca) | Mar 25, 2025 |
| Dell          | Latitude 3420               | [4bbff0abc1](https://linux-hardware.org/?probe=4bbff0abc1) | Mar 24, 2025 |
| HUAWEI        | BoDE-WXX9                   | [01e1603835](https://linux-hardware.org/?probe=01e1603835) | Mar 24, 2025 |
| HUAWEI        | BoDE-WXX9                   | [a3cc7256a5](https://linux-hardware.org/?probe=a3cc7256a5) | Mar 24, 2025 |
| Valve         | Jupiter                     | [b05593e6d5](https://linux-hardware.org/?probe=b05593e6d5) | Mar 23, 2025 |
| Apple         | MacBookPro8,1               | [9214c6ae38](https://linux-hardware.org/?probe=9214c6ae38) | Mar 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [6709bee986](https://linux-hardware.org/?probe=6709bee986) | Mar 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b17c6df945](https://linux-hardware.org/?probe=b17c6df945) | Mar 03, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [c54ac48db7](https://linux-hardware.org/?probe=c54ac48db7) | Mar 02, 2025 |
| HP            | Pavilion Laptop 15-eh0xx... | [21289ee77c](https://linux-hardware.org/?probe=21289ee77c) | Feb 27, 2025 |
| HP            | Victus by Gaming Laptop ... | [4c8865e3fa](https://linux-hardware.org/?probe=4c8865e3fa) | Feb 18, 2025 |
| HONOR         | MRA-XXX                     | [8d5d94f630](https://linux-hardware.org/?probe=8d5d94f630) | Feb 16, 2025 |
| HONOR         | MRA-XXX                     | [3de579a6e2](https://linux-hardware.org/?probe=3de579a6e2) | Feb 16, 2025 |
| Valve         | Jupiter                     | [21a54b2a07](https://linux-hardware.org/?probe=21a54b2a07) | Feb 13, 2025 |
| Dell          | Latitude E5450              | [d460f3428d](https://linux-hardware.org/?probe=d460f3428d) | Feb 12, 2025 |
| Toshiba       | Satellite P55W-C            | [4cdab63f23](https://linux-hardware.org/?probe=4cdab63f23) | Feb 09, 2025 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [dc7da8be63](https://linux-hardware.org/?probe=dc7da8be63) | Jan 28, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [88879d2d45](https://linux-hardware.org/?probe=88879d2d45) | Jan 17, 2025 |
| ASUSTek       | Zenbook UX3402ZA            | [c39c41567b](https://linux-hardware.org/?probe=c39c41567b) | Jan 12, 2025 |
| Toshiba       | Satellite C40-A             | [5c3bd5d9ed](https://linux-hardware.org/?probe=5c3bd5d9ed) | Jan 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [e2e6a6d2fd](https://linux-hardware.org/?probe=e2e6a6d2fd) | Jan 09, 2025 |
| Lenovo        | ThinkPad Edge 0301FFG       | [526994e0a4](https://linux-hardware.org/?probe=526994e0a4) | Dec 31, 2024 |
| ASUSTek       | Zenbook UX3402ZA            | [be06529f29](https://linux-hardware.org/?probe=be06529f29) | Dec 28, 2024 |
| Lenovo        | ThinkPad T440s 20ARA000A... | [606caa4eb0](https://linux-hardware.org/?probe=606caa4eb0) | Dec 22, 2024 |
| Lenovo        | ThinkPad T440s 20ARA000A... | [813d572708](https://linux-hardware.org/?probe=813d572708) | Dec 22, 2024 |
| HUAWEI        | KLVD-WXX9                   | [a5df0d3fd9](https://linux-hardware.org/?probe=a5df0d3fd9) | Dec 22, 2024 |
| Apple         | MacBookPro12,1              | [e4de3821da](https://linux-hardware.org/?probe=e4de3821da) | Dec 20, 2024 |
| Dell          | Inspiron 3542               | [f75f271653](https://linux-hardware.org/?probe=f75f271653) | Dec 03, 2024 |
| Dell          | Inspiron 3542               | [841b30c302](https://linux-hardware.org/?probe=841b30c302) | Dec 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [c56cdb7a5f](https://linux-hardware.org/?probe=c56cdb7a5f) | Nov 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [eaca726e51](https://linux-hardware.org/?probe=eaca726e51) | Nov 30, 2024 |
| Apple         | MacBookPro11,3              | [3d753784a0](https://linux-hardware.org/?probe=3d753784a0) | Nov 28, 2024 |
| HP            | Laptop 15g-br1xx            | [f51b7c2e9d](https://linux-hardware.org/?probe=f51b7c2e9d) | Nov 20, 2024 |
| Valve         | Jupiter                     | [f811772f91](https://linux-hardware.org/?probe=f811772f91) | Nov 09, 2024 |
| Valve         | Jupiter                     | [44366fc1ea](https://linux-hardware.org/?probe=44366fc1ea) | Nov 06, 2024 |
| Toshiba       | Satellite P55W-C            | [84c58de68f](https://linux-hardware.org/?probe=84c58de68f) | Oct 23, 2024 |
| Toshiba       | Satellite P55W-C            | [2fbe7927f9](https://linux-hardware.org/?probe=2fbe7927f9) | Oct 23, 2024 |
| HP            | Laptop 15-da2xxx            | [2993fbf2fd](https://linux-hardware.org/?probe=2993fbf2fd) | Oct 23, 2024 |
| Valve         | Jupiter                     | [2cc13c14ff](https://linux-hardware.org/?probe=2cc13c14ff) | Oct 11, 2024 |
| Dell          | Inspiron 7577               | [42d1b5a375](https://linux-hardware.org/?probe=42d1b5a375) | Oct 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [f497c7ae2d](https://linux-hardware.org/?probe=f497c7ae2d) | Sep 30, 2024 |
| Acer          | Swift SFX14-41G             | [ec357b358b](https://linux-hardware.org/?probe=ec357b358b) | Sep 24, 2024 |
| Dell          | Inspiron 7577               | [ebda65fac2](https://linux-hardware.org/?probe=ebda65fac2) | Sep 23, 2024 |
| Lenovo        | ThinkPad P1 20MD001WUS      | [946c8f41c7](https://linux-hardware.org/?probe=946c8f41c7) | Sep 21, 2024 |
| MSI           | Modern 14 B5M               | [9978e53d19](https://linux-hardware.org/?probe=9978e53d19) | Sep 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [483fb4e9e2](https://linux-hardware.org/?probe=483fb4e9e2) | Sep 07, 2024 |
| MSI           | Modern 14 B5M               | [3d4ad593f5](https://linux-hardware.org/?probe=3d4ad593f5) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5977adeb69](https://linux-hardware.org/?probe=5977adeb69) | Aug 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [affe4b35c6](https://linux-hardware.org/?probe=affe4b35c6) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [7a840c3125](https://linux-hardware.org/?probe=7a840c3125) | Aug 18, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d55a76a395](https://linux-hardware.org/?probe=d55a76a395) | Aug 17, 2024 |
| MSI           | GP73 Leopard 8RE            | [ece6c56479](https://linux-hardware.org/?probe=ece6c56479) | Aug 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [752156b44a](https://linux-hardware.org/?probe=752156b44a) | Aug 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [8a69009d48](https://linux-hardware.org/?probe=8a69009d48) | Aug 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [fc2c81e0a1](https://linux-hardware.org/?probe=fc2c81e0a1) | Aug 11, 2024 |
| Lenovo        | ThinkPad P16v Gen 1 21FD... | [ad6eb57434](https://linux-hardware.org/?probe=ad6eb57434) | Aug 09, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [9f1f1cd1fe](https://linux-hardware.org/?probe=9f1f1cd1fe) | Aug 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [637a30175e](https://linux-hardware.org/?probe=637a30175e) | Jul 28, 2024 |
| Apple         | MacBookPro11,3              | [2cb98cd569](https://linux-hardware.org/?probe=2cb98cd569) | Jul 27, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [ba13a043f7](https://linux-hardware.org/?probe=ba13a043f7) | Jul 25, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [6e210dbe32](https://linux-hardware.org/?probe=6e210dbe32) | Jul 24, 2024 |
| Fujitsu       | CELSIUS H730                | [0882a15af4](https://linux-hardware.org/?probe=0882a15af4) | Jul 23, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [78050f4878](https://linux-hardware.org/?probe=78050f4878) | Jul 20, 2024 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [1d6f70595c](https://linux-hardware.org/?probe=1d6f70595c) | Jul 19, 2024 |
| ASUSTek       | S550CM                      | [effe093e11](https://linux-hardware.org/?probe=effe093e11) | Jul 17, 2024 |
| Valve         | Galileo                     | [c81b1ef308](https://linux-hardware.org/?probe=c81b1ef308) | Jul 14, 2024 |
| Dell          | G3 3590                     | [df288cdcaf](https://linux-hardware.org/?probe=df288cdcaf) | Jul 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7eb520a49](https://linux-hardware.org/?probe=a7eb520a49) | Jul 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [05aecfd062](https://linux-hardware.org/?probe=05aecfd062) | Jul 12, 2024 |
| Lenovo        | G580 20150                  | [5137ace569](https://linux-hardware.org/?probe=5137ace569) | Jul 08, 2024 |
| Lenovo        | G580 20150                  | [c4c28daaee](https://linux-hardware.org/?probe=c4c28daaee) | Jul 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [48b56d8828](https://linux-hardware.org/?probe=48b56d8828) | Jul 02, 2024 |
| Apple         | MacBookPro11,3              | [6aa7f99b04](https://linux-hardware.org/?probe=6aa7f99b04) | Jun 26, 2024 |
| Razer         | Blade Pro                   | [4e48c6dcde](https://linux-hardware.org/?probe=4e48c6dcde) | Jun 26, 2024 |
| I-Life Dig... | ZED AIR                     | [3d4f3140df](https://linux-hardware.org/?probe=3d4f3140df) | Jun 16, 2024 |
| I-Life Dig... | ZED AIR                     | [c62f439782](https://linux-hardware.org/?probe=c62f439782) | Jun 16, 2024 |
| HUAWEI        | KLVG-XX                     | [b1f7ffbf4a](https://linux-hardware.org/?probe=b1f7ffbf4a) | Jun 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e570948d49](https://linux-hardware.org/?probe=e570948d49) | Jun 10, 2024 |
| MSI           | Modern 14 B4MW              | [ed6e21156a](https://linux-hardware.org/?probe=ed6e21156a) | Jun 10, 2024 |
| HP            | Laptop 15-da2xxx            | [bcf8969f1e](https://linux-hardware.org/?probe=bcf8969f1e) | May 31, 2024 |
| Valve         | Jupiter                     | [44a1aa1433](https://linux-hardware.org/?probe=44a1aa1433) | May 27, 2024 |
| Valve         | Jupiter                     | [1ddb224c47](https://linux-hardware.org/?probe=1ddb224c47) | May 27, 2024 |
| Lenovo        | ThinkPad P50 20EQS3X10C     | [cfccc1ca5a](https://linux-hardware.org/?probe=cfccc1ca5a) | May 27, 2024 |
| Lenovo        | ThinkPad P50 20EQS3X10C     | [2859984d97](https://linux-hardware.org/?probe=2859984d97) | May 19, 2024 |
| Valve         | Galileo                     | [1c500922b5](https://linux-hardware.org/?probe=1c500922b5) | May 19, 2024 |
| Valve         | Galileo                     | [9549cb7d85](https://linux-hardware.org/?probe=9549cb7d85) | May 19, 2024 |
| Valve         | Galileo                     | [a85c23cf18](https://linux-hardware.org/?probe=a85c23cf18) | May 19, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [c12c2839cb](https://linux-hardware.org/?probe=c12c2839cb) | May 19, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [73bdf58ea3](https://linux-hardware.org/?probe=73bdf58ea3) | May 15, 2024 |
| HP            | Laptop 15-da2xxx            | [d553213278](https://linux-hardware.org/?probe=d553213278) | May 10, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [cf6fc980de](https://linux-hardware.org/?probe=cf6fc980de) | May 07, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | [3380a14ae9](https://linux-hardware.org/?probe=3380a14ae9) | May 02, 2024 |
| MSI           | GL75 Leopard 10SFK          | [2cde0c8054](https://linux-hardware.org/?probe=2cde0c8054) | Apr 28, 2024 |
| Valve         | Jupiter                     | [8cd7c7653a](https://linux-hardware.org/?probe=8cd7c7653a) | Apr 07, 2024 |
| Lenovo        | B50-70 20384                | [f78c6087ac](https://linux-hardware.org/?probe=f78c6087ac) | Mar 31, 2024 |
| HUAWEI        | BOD-WXX9                    | [f07c7e7a17](https://linux-hardware.org/?probe=f07c7e7a17) | Mar 23, 2024 |
| ASUSTek       | X541SA                      | [4f1901506d](https://linux-hardware.org/?probe=4f1901506d) | Mar 22, 2024 |
| MSI           | GF63 Thin 8SC               | [bbc6edbc2d](https://linux-hardware.org/?probe=bbc6edbc2d) | Mar 09, 2024 |
| ASUSTek       | GL552VX                     | [01ea0912c3](https://linux-hardware.org/?probe=01ea0912c3) | Mar 03, 2024 |
| Dell          | Inspiron 3581               | [62a3c2b526](https://linux-hardware.org/?probe=62a3c2b526) | Feb 11, 2024 |
| Lenovo        | Unknown                     | [46ccd12f05](https://linux-hardware.org/?probe=46ccd12f05) | Feb 04, 2024 |
| Dell          | Inspiron 3581               | [7a5cfbd8d3](https://linux-hardware.org/?probe=7a5cfbd8d3) | Jan 25, 2024 |
| Dell          | Inspiron 3581               | [dbf2745f1f](https://linux-hardware.org/?probe=dbf2745f1f) | Jan 25, 2024 |
| Dell          | Latitude E5540              | [2e1716a6aa](https://linux-hardware.org/?probe=2e1716a6aa) | Jan 22, 2024 |
| HP            | ENVY TS 15                  | [4d83b8cef9](https://linux-hardware.org/?probe=4d83b8cef9) | Jan 19, 2024 |
| Toshiba       | Satellite C850-B820         | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| HP            | Pavilion Notebook           | [a4afc8bb1f](https://linux-hardware.org/?probe=a4afc8bb1f) | Jan 12, 2024 |
| Dell          | Inspiron 1525               | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| Dell          | G3 3590                     | [681f15e9c0](https://linux-hardware.org/?probe=681f15e9c0) | Dec 27, 2023 |
| Dell          | G3 3590                     | [f009abd381](https://linux-hardware.org/?probe=f009abd381) | Nov 25, 2023 |
| Dell          | Inspiron N5110              | [78992043bf](https://linux-hardware.org/?probe=78992043bf) | Nov 20, 2023 |
| Valve         | Jupiter                     | [97695463df](https://linux-hardware.org/?probe=97695463df) | Nov 17, 2023 |
| Valve         | Jupiter                     | [8734420ff1](https://linux-hardware.org/?probe=8734420ff1) | Nov 17, 2023 |
| HUAWEI        | KLVL-WXX9                   | [e45cab7f2c](https://linux-hardware.org/?probe=e45cab7f2c) | Nov 12, 2023 |
| Acer          | Aspire 5920                 | [02fa7cf5bb](https://linux-hardware.org/?probe=02fa7cf5bb) | Nov 03, 2023 |
| Dell          | XPS 15 9520                 | [6b6da0ca4a](https://linux-hardware.org/?probe=6b6da0ca4a) | Nov 01, 2023 |
| Toshiba       | Satellite C650              | [5236a2eca3](https://linux-hardware.org/?probe=5236a2eca3) | Oct 26, 2023 |
| HP            | Laptop 15-da2xxx            | [6f746b3af3](https://linux-hardware.org/?probe=6f746b3af3) | Oct 23, 2023 |
| Dell          | Latitude E6520              | [e29f6e9ba8](https://linux-hardware.org/?probe=e29f6e9ba8) | Oct 11, 2023 |
| Apple         | MacBookPro11,5              | [98784d1e51](https://linux-hardware.org/?probe=98784d1e51) | Oct 08, 2023 |
| HP            | ProBook 6560b               | [c4710bf9c2](https://linux-hardware.org/?probe=c4710bf9c2) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [683cbd037a](https://linux-hardware.org/?probe=683cbd037a) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | [8064cec888](https://linux-hardware.org/?probe=8064cec888) | Sep 17, 2023 |
| Apple         | MacBook5,2                  | [7cdaac7be4](https://linux-hardware.org/?probe=7cdaac7be4) | Sep 16, 2023 |
| Apple         | MacBook5,2                  | [192e02b434](https://linux-hardware.org/?probe=192e02b434) | Sep 15, 2023 |
| Dell          | Inspiron 5537               | [b06966adc5](https://linux-hardware.org/?probe=b06966adc5) | Sep 14, 2023 |
| Dell          | Inspiron 5537               | [9f459c45cc](https://linux-hardware.org/?probe=9f459c45cc) | Sep 14, 2023 |
| Apple         | MacBookPro8,1               | [f913de368f](https://linux-hardware.org/?probe=f913de368f) | Sep 07, 2023 |
| Apple         | MacBookPro8,1               | [423b8d7135](https://linux-hardware.org/?probe=423b8d7135) | Sep 07, 2023 |
| Lenovo        | B40-70 20392                | [ebf45c27f4](https://linux-hardware.org/?probe=ebf45c27f4) | Aug 07, 2023 |
| Lenovo        | B40-70 20392                | [221f9de00a](https://linux-hardware.org/?probe=221f9de00a) | Aug 06, 2023 |
| GIADA         | Unknown                     | [cd8b23468a](https://linux-hardware.org/?probe=cd8b23468a) | Aug 03, 2023 |
| Toshiba       | Satellite C850-B239         | [a075f60c70](https://linux-hardware.org/?probe=a075f60c70) | Aug 02, 2023 |
| Unknown       | Unknown                     | [570c98e6ab](https://linux-hardware.org/?probe=570c98e6ab) | Aug 01, 2023 |
| Unknown       | Unknown                     | [f54f3f3a4b](https://linux-hardware.org/?probe=f54f3f3a4b) | Aug 01, 2023 |
| Valve         | Jupiter                     | [fc294ac015](https://linux-hardware.org/?probe=fc294ac015) | Jul 27, 2023 |
| HP            | EliteBook 840 G5            | [f371e0efe5](https://linux-hardware.org/?probe=f371e0efe5) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [55639a6416](https://linux-hardware.org/?probe=55639a6416) | Jul 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8b2077101c](https://linux-hardware.org/?probe=8b2077101c) | Jul 21, 2023 |
| Acer          | Aspire A715-42G             | [ac10700edb](https://linux-hardware.org/?probe=ac10700edb) | Jul 13, 2023 |
| Dell          | G3 3590                     | [adf89d2bba](https://linux-hardware.org/?probe=adf89d2bba) | Jul 12, 2023 |
| Lenovo        | B40-70 20392                | [02a31c9704](https://linux-hardware.org/?probe=02a31c9704) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | [45739a208c](https://linux-hardware.org/?probe=45739a208c) | Jul 01, 2023 |
| Dell          | Latitude 3520               | [6e996e08f9](https://linux-hardware.org/?probe=6e996e08f9) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [39ec9cf6c4](https://linux-hardware.org/?probe=39ec9cf6c4) | Jun 27, 2023 |
| Dell          | Inspiron 3576               | [c756e98d81](https://linux-hardware.org/?probe=c756e98d81) | Jun 24, 2023 |
| Dell          | Inspiron 3576               | [874b84ce94](https://linux-hardware.org/?probe=874b84ce94) | Jun 24, 2023 |
| HP            | Laptop 15-da0xxx            | [7da8691a87](https://linux-hardware.org/?probe=7da8691a87) | Jun 17, 2023 |
| HP            | Laptop 15-da1xxx            | [5bc14dc937](https://linux-hardware.org/?probe=5bc14dc937) | Jun 12, 2023 |
| Valve         | Jupiter                     | [8c9765a31c](https://linux-hardware.org/?probe=8c9765a31c) | Jun 11, 2023 |
| Toshiba       | Satellite L635              | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Valve         | Jupiter                     | [d21eb9432c](https://linux-hardware.org/?probe=d21eb9432c) | Jun 03, 2023 |
| Dell          | Latitude E6520              | [bb8bc9b8ae](https://linux-hardware.org/?probe=bb8bc9b8ae) | May 24, 2023 |
| Google        | Akemi                       | [595f8b1a24](https://linux-hardware.org/?probe=595f8b1a24) | May 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [93979d632e](https://linux-hardware.org/?probe=93979d632e) | May 15, 2023 |
| Lenovo        | IdeaPad Z470                | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [4b338ba7f9](https://linux-hardware.org/?probe=4b338ba7f9) | Apr 15, 2023 |
| HP            | Laptop 15-da1xxx            | [84c8a107d4](https://linux-hardware.org/?probe=84c8a107d4) | Apr 06, 2023 |
| Acer          | Aspire ES1-572              | [39e1087c79](https://linux-hardware.org/?probe=39e1087c79) | Apr 04, 2023 |
| Apple         | MacBookAir7,2               | [9509c77e2b](https://linux-hardware.org/?probe=9509c77e2b) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [b8ea458df5](https://linux-hardware.org/?probe=b8ea458df5) | Mar 08, 2023 |
| Sony          | VGN-FZ250E                  | [ca7937209b](https://linux-hardware.org/?probe=ca7937209b) | Mar 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d488fc0d9a](https://linux-hardware.org/?probe=d488fc0d9a) | Feb 22, 2023 |
| HP            | Laptop 15-da2xxx            | [76cbc7df6d](https://linux-hardware.org/?probe=76cbc7df6d) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [e70b65f78d](https://linux-hardware.org/?probe=e70b65f78d) | Feb 20, 2023 |
| Dell          | Latitude E6520              | [b04c6e8984](https://linux-hardware.org/?probe=b04c6e8984) | Feb 18, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Acer          | Aspire A315-55G             | [70559c048c](https://linux-hardware.org/?probe=70559c048c) | Jan 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HP            | Unknown                     | [fedf225852](https://linux-hardware.org/?probe=fedf225852) | Jan 17, 2023 |
| HP            | Unknown                     | [8b89da1da5](https://linux-hardware.org/?probe=8b89da1da5) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Valve         | Jupiter                     | [b927a3e937](https://linux-hardware.org/?probe=b927a3e937) | Jan 16, 2023 |
| Valve         | Jupiter                     | [2b476ca470](https://linux-hardware.org/?probe=2b476ca470) | Jan 16, 2023 |
| MSI           | GF63 Thin 10SC              | [26379f8b8d](https://linux-hardware.org/?probe=26379f8b8d) | Jan 11, 2023 |
| HUAWEI        | KLVD-WXX9                   | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Toshiba       | Satellite C850-B561         | [562d6cde14](https://linux-hardware.org/?probe=562d6cde14) | Jan 11, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2c6b6c2558](https://linux-hardware.org/?probe=2c6b6c2558) | Jan 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| Toshiba       | Satellite L635              | [be223c0ff1](https://linux-hardware.org/?probe=be223c0ff1) | Dec 03, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| Dell          | Venue 8 Pro 5830            | [8890410dfc](https://linux-hardware.org/?probe=8890410dfc) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4c0e49ae2b](https://linux-hardware.org/?probe=4c0e49ae2b) | Oct 23, 2022 |
| Apple         | MacBookPro13,2              | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f7f3439df7](https://linux-hardware.org/?probe=f7f3439df7) | Oct 11, 2022 |
| Dell          | Inspiron 5558               | [61f05a7c32](https://linux-hardware.org/?probe=61f05a7c32) | Oct 10, 2022 |
| Sony          | SVF15A13SAB                 | [7c39add556](https://linux-hardware.org/?probe=7c39add556) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [de59de7b14](https://linux-hardware.org/?probe=de59de7b14) | Oct 04, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| Dell          | G15 5515                    | [ae769dae75](https://linux-hardware.org/?probe=ae769dae75) | Sep 24, 2022 |
| Dell          | G15 5515                    | [893c248dec](https://linux-hardware.org/?probe=893c248dec) | Sep 24, 2022 |
| Dell          | G15 5515                    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a934e23e1f](https://linux-hardware.org/?probe=a934e23e1f) | Sep 16, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Notebook      | NH5xAx                      | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| Dell          | Vostro 15 3515              | [4ecdbb8b4b](https://linux-hardware.org/?probe=4ecdbb8b4b) | Aug 15, 2022 |
| Acer          | Aspire 4752                 | [9854c38629](https://linux-hardware.org/?probe=9854c38629) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ed6b6ce93e](https://linux-hardware.org/?probe=ed6b6ce93e) | Aug 03, 2022 |
| eMachines     | Unknown                     | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Lenovo        | B590 20206                  | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| MSI           | GF63 Thin 8RCS              | [8cd1ebfa12](https://linux-hardware.org/?probe=8cd1ebfa12) | May 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c34e9b0da7](https://linux-hardware.org/?probe=c34e9b0da7) | May 05, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [b6dc8a3fc8](https://linux-hardware.org/?probe=b6dc8a3fc8) | May 05, 2022 |
| Dell          | Inspiron 3580               | [51d4e9a2e2](https://linux-hardware.org/?probe=51d4e9a2e2) | May 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [720d11c11f](https://linux-hardware.org/?probe=720d11c11f) | May 04, 2022 |
| Acer          | Aspire V3-571               | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Dell          | Inspiron 3580               | [794ab7ba41](https://linux-hardware.org/?probe=794ab7ba41) | Apr 28, 2022 |
| Dell          | Inspiron 3542               | [196f849315](https://linux-hardware.org/?probe=196f849315) | Apr 18, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [45548a6fe5](https://linux-hardware.org/?probe=45548a6fe5) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10c6384de8](https://linux-hardware.org/?probe=10c6384de8) | Mar 25, 2022 |
| Dell          | Inspiron 14-3467            | [50131c5da4](https://linux-hardware.org/?probe=50131c5da4) | Mar 21, 2022 |
| Acer          | AO751h                      | [23737182d1](https://linux-hardware.org/?probe=23737182d1) | Mar 21, 2022 |
| Acer          | AO751h                      | [edea28357c](https://linux-hardware.org/?probe=edea28357c) | Mar 18, 2022 |
| ASUSTek       | K53SC                       | [43b019326c](https://linux-hardware.org/?probe=43b019326c) | Feb 12, 2022 |
| ASUSTek       | K53SC                       | [70f23c3da0](https://linux-hardware.org/?probe=70f23c3da0) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | [40c74584ee](https://linux-hardware.org/?probe=40c74584ee) | Feb 03, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [261fe8bda7](https://linux-hardware.org/?probe=261fe8bda7) | Jan 07, 2022 |
| Sony          | VPCCA35FA                   | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Packard Be... | EasyNote TJ65               | [b98b9252fa](https://linux-hardware.org/?probe=b98b9252fa) | Dec 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| Lenovo        | V15-IIL 82C5                | [2a151de62b](https://linux-hardware.org/?probe=2a151de62b) | Dec 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [830882c4e6](https://linux-hardware.org/?probe=830882c4e6) | Dec 07, 2021 |
| Toshiba       | Satellite L500              | [5cc2fbfef5](https://linux-hardware.org/?probe=5cc2fbfef5) | Dec 04, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [e3acd70236](https://linux-hardware.org/?probe=e3acd70236) | Dec 02, 2021 |
| Lenovo        | ThinkPad E14 20RA008CAD     | [35fab17b69](https://linux-hardware.org/?probe=35fab17b69) | Dec 01, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Toshiba       | Satellite L500              | [46d5208475](https://linux-hardware.org/?probe=46d5208475) | Nov 28, 2021 |
| Lenovo        | V15-IIL 82C5                | [e37587fbac](https://linux-hardware.org/?probe=e37587fbac) | Nov 23, 2021 |
| Lenovo        | V15-IIL 82C5                | [b050debd0a](https://linux-hardware.org/?probe=b050debd0a) | Nov 22, 2021 |
| Dell          | G3 3590                     | [605f0870d0](https://linux-hardware.org/?probe=605f0870d0) | Nov 16, 2021 |
| Dell          | G3 3590                     | [5bfafc889c](https://linux-hardware.org/?probe=5bfafc889c) | Nov 16, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [997e24e5c9](https://linux-hardware.org/?probe=997e24e5c9) | Nov 06, 2021 |
| Lenovo        | ThinkPad E490 20N8000JAD    | [9d70a71c88](https://linux-hardware.org/?probe=9d70a71c88) | Nov 06, 2021 |
| Lenovo        | V570 1066AJU                | [ffb36aac10](https://linux-hardware.org/?probe=ffb36aac10) | Nov 05, 2021 |
| Dell          | Inspiron 3593               | [5233ea30c6](https://linux-hardware.org/?probe=5233ea30c6) | Oct 09, 2021 |
| Lenovo        | ThinkPad P52s 20LBS0JC00    | [4c8c63da2f](https://linux-hardware.org/?probe=4c8c63da2f) | Oct 05, 2021 |
| HP            | Laptop 15-da2xxx            | [2e99b047ff](https://linux-hardware.org/?probe=2e99b047ff) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [de6b4e47d4](https://linux-hardware.org/?probe=de6b4e47d4) | Oct 01, 2021 |
| HP            | Laptop 15-da2xxx            | [28332170d1](https://linux-hardware.org/?probe=28332170d1) | Sep 28, 2021 |
| Dell          | Inspiron N5110              | [8c04a9e8df](https://linux-hardware.org/?probe=8c04a9e8df) | Sep 22, 2021 |
| Acer          | Aspire E5-573G              | [19374f68da](https://linux-hardware.org/?probe=19374f68da) | Sep 21, 2021 |
| Acer          | Aspire V3-571               | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Toshiba       | Satellite C55-B             | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Toshiba       | Satellite C55-B             | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| Dell          | Latitude E7440              | [b87783b728](https://linux-hardware.org/?probe=b87783b728) | Aug 18, 2021 |
| Dell          | Latitude E5470              | [f91acefb07](https://linux-hardware.org/?probe=f91acefb07) | Aug 14, 2021 |
| Dell          | XPS 15 9560                 | [9bae1ef315](https://linux-hardware.org/?probe=9bae1ef315) | Jul 07, 2021 |
| ASUSTek       | K43SJ                       | [f4702e95b4](https://linux-hardware.org/?probe=f4702e95b4) | Jul 05, 2021 |
| Dell          | XPS 15 9560                 | [08fad9a114](https://linux-hardware.org/?probe=08fad9a114) | Jul 03, 2021 |
| Dell          | G3 3590                     | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| Dell          | Inspiron 5437               | [06f25de7e3](https://linux-hardware.org/?probe=06f25de7e3) | Jun 19, 2021 |
| Dell          | Inspiron 5437               | [3fcbd5cd4f](https://linux-hardware.org/?probe=3fcbd5cd4f) | Jun 18, 2021 |
| Dell          | G3 3590                     | [877018f0d3](https://linux-hardware.org/?probe=877018f0d3) | Jun 18, 2021 |
| Dell          | G3 3590                     | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| HP            | ProBook 445 G7              | [88e51bfd39](https://linux-hardware.org/?probe=88e51bfd39) | May 23, 2021 |
| ASUSTek       | GL502VMK                    | [0d9f5609e7](https://linux-hardware.org/?probe=0d9f5609e7) | May 20, 2021 |
| HP            | ProBook 445 G7              | [ed8c410826](https://linux-hardware.org/?probe=ed8c410826) | May 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1d4c05756f](https://linux-hardware.org/?probe=1d4c05756f) | May 01, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9b03874730](https://linux-hardware.org/?probe=9b03874730) | Apr 27, 2021 |
| Dell          | Latitude E7470              | [1058573f86](https://linux-hardware.org/?probe=1058573f86) | Apr 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [14fd40d980](https://linux-hardware.org/?probe=14fd40d980) | Apr 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0b31da2d02](https://linux-hardware.org/?probe=0b31da2d02) | Apr 16, 2021 |
| HP            | Pavilion Laptop 15t-eg00... | [cd64675ac7](https://linux-hardware.org/?probe=cd64675ac7) | Mar 30, 2021 |
| Toshiba       | Satellite S55t-A            | [9ede240e19](https://linux-hardware.org/?probe=9ede240e19) | Mar 20, 2021 |
| Apple         | MacBookPro9,2               | [7d8acdd5b6](https://linux-hardware.org/?probe=7d8acdd5b6) | Mar 19, 2021 |
| Toshiba       | Satellite S55t-A            | [5aa53770bf](https://linux-hardware.org/?probe=5aa53770bf) | Mar 06, 2021 |
| Toshiba       | Satellite S55t-A            | [5ed863271a](https://linux-hardware.org/?probe=5ed863271a) | Mar 06, 2021 |
| Acer          | Nitro AN515-52              | [99ee0e5718](https://linux-hardware.org/?probe=99ee0e5718) | Feb 24, 2021 |
| Acer          | Nitro AN515-52              | [89497c0f27](https://linux-hardware.org/?probe=89497c0f27) | Feb 23, 2021 |
| ASUSTek       | X555UB                      | [260d78f7c8](https://linux-hardware.org/?probe=260d78f7c8) | Feb 20, 2021 |
| HP            | Pavilion g6                 | [30bcebb4be](https://linux-hardware.org/?probe=30bcebb4be) | Feb 16, 2021 |
| Lenovo        | ThinkPad E460 20ET000MAD    | [cd000b8e6b](https://linux-hardware.org/?probe=cd000b8e6b) | Feb 11, 2021 |
| Dell          | Inspiron 3593               | [5407a15ab7](https://linux-hardware.org/?probe=5407a15ab7) | Feb 09, 2021 |
| Dell          | Inspiron 3593               | [0802cedb25](https://linux-hardware.org/?probe=0802cedb25) | Feb 09, 2021 |
| Dell          | Latitude E4310              | [9c6781e592](https://linux-hardware.org/?probe=9c6781e592) | Feb 08, 2021 |
| ASUSTek       | ROG Strix G512LWS_G512LW... | [d4d3110510](https://linux-hardware.org/?probe=d4d3110510) | Jan 29, 2021 |
| Toshiba       | Satellite C855D             | [46d5bf62c7](https://linux-hardware.org/?probe=46d5bf62c7) | Jan 19, 2021 |
| Dell          | Inspiron 3576               | [99f1a1ac09](https://linux-hardware.org/?probe=99f1a1ac09) | Jan 16, 2021 |
| Sony          | VGN-FZ250E                  | [d0d77ffe81](https://linux-hardware.org/?probe=d0d77ffe81) | Jan 15, 2021 |
| HP            | Laptop 14-ck0xxx            | [92ea4004af](https://linux-hardware.org/?probe=92ea4004af) | Jan 15, 2021 |
| Sony          | VGN-FZ250E                  | [68ddc53941](https://linux-hardware.org/?probe=68ddc53941) | Jan 14, 2021 |
| Dell          | Inspiron 3576               | [b21e44d0c4](https://linux-hardware.org/?probe=b21e44d0c4) | Jan 11, 2021 |
| Dell          | Vostro 5470                 | [216df384d8](https://linux-hardware.org/?probe=216df384d8) | Dec 22, 2020 |
| Dell          | Vostro 5470                 | [bec1b16786](https://linux-hardware.org/?probe=bec1b16786) | Dec 22, 2020 |
| LG Electro... | R490-G.ARL5RE2              | [58f0c96534](https://linux-hardware.org/?probe=58f0c96534) | Dec 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [239675db8d](https://linux-hardware.org/?probe=239675db8d) | Nov 25, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dfcc723611](https://linux-hardware.org/?probe=dfcc723611) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b164be6cfc](https://linux-hardware.org/?probe=b164be6cfc) | Nov 21, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [a3ffdab533](https://linux-hardware.org/?probe=a3ffdab533) | Nov 16, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | [cce5403051](https://linux-hardware.org/?probe=cce5403051) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| I-Life Dig... | ZED Air Plus                | [b1a43bf9f2](https://linux-hardware.org/?probe=b1a43bf9f2) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [c0ad42acb0](https://linux-hardware.org/?probe=c0ad42acb0) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b5e6f52433](https://linux-hardware.org/?probe=b5e6f52433) | Nov 04, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e9ca4c8d42](https://linux-hardware.org/?probe=e9ca4c8d42) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| Acer          | Aspire E1-532P              | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c45580b2f3](https://linux-hardware.org/?probe=c45580b2f3) | Oct 28, 2020 |
| MSI           | MS-1454                     | [0accbf6c77](https://linux-hardware.org/?probe=0accbf6c77) | Oct 14, 2020 |
| Acer          | Swift SF314-52              | [a1665a6de1](https://linux-hardware.org/?probe=a1665a6de1) | Sep 26, 2020 |
| Acer          | Aspire E5-571G              | [d52f9c5bc7](https://linux-hardware.org/?probe=d52f9c5bc7) | Sep 18, 2020 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [6963343ed4](https://linux-hardware.org/?probe=6963343ed4) | Sep 17, 2020 |
| Clevo         | P15xEMx                     | [83d0f6aae6](https://linux-hardware.org/?probe=83d0f6aae6) | Aug 28, 2020 |
| Lenovo        | ThinkPad Edge 0301FFG       | [60d3a68581](https://linux-hardware.org/?probe=60d3a68581) | Aug 10, 2020 |
| HP            | Pavilion g6                 | [98d75162cc](https://linux-hardware.org/?probe=98d75162cc) | Aug 06, 2020 |
| HUAWEI        | HN-WX9X                     | [41a4a29b16](https://linux-hardware.org/?probe=41a4a29b16) | Aug 02, 2020 |
| Dell          | Inspiron 3542               | [9138a15fe4](https://linux-hardware.org/?probe=9138a15fe4) | Aug 01, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fe429f7077](https://linux-hardware.org/?probe=fe429f7077) | Jul 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f9c494b96b](https://linux-hardware.org/?probe=f9c494b96b) | Jul 22, 2020 |
| ASUSTek       | T100TA                      | [f6884bd3db](https://linux-hardware.org/?probe=f6884bd3db) | Jun 26, 2020 |
| ASUSTek       | T100TA                      | [1a288de2c5](https://linux-hardware.org/?probe=1a288de2c5) | Jun 24, 2020 |
| ASUSTek       | T100TA                      | [aa1c1587d1](https://linux-hardware.org/?probe=aa1c1587d1) | Jun 23, 2020 |
| Acer          | Aspire ES1-572              | [a166c179ea](https://linux-hardware.org/?probe=a166c179ea) | Jun 22, 2020 |
| ASUSTek       | L4000H                      | [d385784b22](https://linux-hardware.org/?probe=d385784b22) | Jun 22, 2020 |
| Acer          | Swift SF314-52              | [c5f91bc1ff](https://linux-hardware.org/?probe=c5f91bc1ff) | Jun 16, 2020 |
| Dell          | Inspiron N5030              | [5641d9b86e](https://linux-hardware.org/?probe=5641d9b86e) | Jun 14, 2020 |
| ASUSTek       | UX390UAK                    | [0857b4df77](https://linux-hardware.org/?probe=0857b4df77) | May 27, 2020 |
| Sony          | SVF153290X                  | [e19f1c716f](https://linux-hardware.org/?probe=e19f1c716f) | May 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [117bc7af0e](https://linux-hardware.org/?probe=117bc7af0e) | May 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0444dd48d1](https://linux-hardware.org/?probe=0444dd48d1) | May 09, 2020 |
| Acer          | Aspire E1-532P              | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | [8ee1846a65](https://linux-hardware.org/?probe=8ee1846a65) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [bff527c13e](https://linux-hardware.org/?probe=bff527c13e) | Apr 29, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8b02fac19f](https://linux-hardware.org/?probe=8b02fac19f) | Apr 26, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [640431a321](https://linux-hardware.org/?probe=640431a321) | Apr 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [095b8a5cdc](https://linux-hardware.org/?probe=095b8a5cdc) | Apr 16, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [874b42a4b7](https://linux-hardware.org/?probe=874b42a4b7) | Apr 16, 2020 |
| HP            | 15                          | [68b0d776a9](https://linux-hardware.org/?probe=68b0d776a9) | Apr 08, 2020 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [784de80b54](https://linux-hardware.org/?probe=784de80b54) | Apr 08, 2020 |
| HP            | Notebook                    | [f22cd145c5](https://linux-hardware.org/?probe=f22cd145c5) | Apr 07, 2020 |
| HP            | 15                          | [27ef1499e3](https://linux-hardware.org/?probe=27ef1499e3) | Apr 06, 2020 |
| HP            | 15                          | [0c2b7adf55](https://linux-hardware.org/?probe=0c2b7adf55) | Apr 06, 2020 |
| HP            | 15                          | [ee5fd88936](https://linux-hardware.org/?probe=ee5fd88936) | Apr 03, 2020 |
| HP            | 15                          | [bfd4fe41b3](https://linux-hardware.org/?probe=bfd4fe41b3) | Apr 03, 2020 |
| HP            | Laptop 15-bs1xx             | [cdce411ba5](https://linux-hardware.org/?probe=cdce411ba5) | Mar 13, 2020 |
| HP            | Laptop 15-bs1xx             | [6e7a1c3bc6](https://linux-hardware.org/?probe=6e7a1c3bc6) | Mar 13, 2020 |
| HP            | Laptop 15-da0xxx            | [d3d2a3b89f](https://linux-hardware.org/?probe=d3d2a3b89f) | Mar 05, 2020 |
| ASUSTek       | X555QA                      | [2f0a038eaf](https://linux-hardware.org/?probe=2f0a038eaf) | Feb 11, 2020 |
| ASUSTek       | X555QA                      | [e8062aced5](https://linux-hardware.org/?probe=e8062aced5) | Feb 10, 2020 |
| Dell          | Vostro 1440                 | [203e61a7c9](https://linux-hardware.org/?probe=203e61a7c9) | Feb 01, 2020 |
| HP            | Notebook                    | [86dc2687ad](https://linux-hardware.org/?probe=86dc2687ad) | Jan 29, 2020 |
| HP            | Notebook                    | [d3e2e18fa2](https://linux-hardware.org/?probe=d3e2e18fa2) | Jan 29, 2020 |
| HP            | Laptop 15-db0xxx            | [9c01b939ce](https://linux-hardware.org/?probe=9c01b939ce) | Jan 27, 2020 |
| HP            | Laptop 15-db0xxx            | [916d1cb7c0](https://linux-hardware.org/?probe=916d1cb7c0) | Jan 27, 2020 |
| Toshiba       | QOSMIO X875                 | [a20b2a7dd7](https://linux-hardware.org/?probe=a20b2a7dd7) | Jan 02, 2020 |
| Toshiba       | QOSMIO X875                 | [953a43ae80](https://linux-hardware.org/?probe=953a43ae80) | Jan 02, 2020 |
| Lenovo        | ThinkPad X230 2325OA3       | [ad8913bb6b](https://linux-hardware.org/?probe=ad8913bb6b) | Dec 09, 2019 |
| GPD           | MicroPC                     | [37bfeee080](https://linux-hardware.org/?probe=37bfeee080) | Dec 09, 2019 |
| ASUSTek       | X555LDB                     | [fffe9c8500](https://linux-hardware.org/?probe=fffe9c8500) | Sep 04, 2019 |
| ASUSTek       | X555LDB                     | [60bc2f13a4](https://linux-hardware.org/?probe=60bc2f13a4) | Sep 04, 2019 |
| Acer          | Aspire 4752                 | [4b1cbc26db](https://linux-hardware.org/?probe=4b1cbc26db) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | [5670d72491](https://linux-hardware.org/?probe=5670d72491) | Aug 13, 2019 |
| Acer          | Aspire 4752                 | [81bd1c9f07](https://linux-hardware.org/?probe=81bd1c9f07) | Aug 13, 2019 |
| Sony          | VPCEA36FA                   | [069db5e1d5](https://linux-hardware.org/?probe=069db5e1d5) | Jul 11, 2019 |
| HUAWEI        | MateBook D                  | [0c82ca3724](https://linux-hardware.org/?probe=0c82ca3724) | Jul 06, 2019 |
| ASUSTek       | X540UA                      | [b66944b7d8](https://linux-hardware.org/?probe=b66944b7d8) | Jun 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [630f59eb30](https://linux-hardware.org/?probe=630f59eb30) | Jun 12, 2019 |
| ASUSTek       | X540UA                      | [3d424bc8d3](https://linux-hardware.org/?probe=3d424bc8d3) | Jun 07, 2019 |
| ASUSTek       | X540UA                      | [8b98fb721c](https://linux-hardware.org/?probe=8b98fb721c) | Jun 07, 2019 |
| ASUSTek       | X540NA                      | [ced21dc1f3](https://linux-hardware.org/?probe=ced21dc1f3) | May 21, 2019 |
| Sony          | SVF14N13CXB                 | [37e231ce84](https://linux-hardware.org/?probe=37e231ce84) | Apr 07, 2019 |
| HP            | 15                          | [e900ad9cfc](https://linux-hardware.org/?probe=e900ad9cfc) | Mar 15, 2019 |
| Lenovo        | Flex 2-15 20405             | [d44c9b123d](https://linux-hardware.org/?probe=d44c9b123d) | Dec 19, 2018 |
| Lenovo        | Flex 2-15 20405             | [b0c7903cb1](https://linux-hardware.org/?probe=b0c7903cb1) | Dec 19, 2018 |
| Acer          | Aspire E1-532P              | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Ubuntu 20.04           | 24        | 7.25%   |
| Ubuntu 22.04           | 21        | 6.34%   |
| Ubuntu 24.04           | 11        | 3.32%   |
| Ubuntu 18.04           | 11        | 3.32%   |
| Pop!_OS 22.04          | 11        | 3.32%   |
| Fedora 42              | 9         | 2.72%   |
| Debian 12              | 9         | 2.72%   |
| Arch Rolling           | 9         | 2.72%   |
| OpenMandriva 4.3       | 8         | 2.42%   |
| Zorin 16               | 7         | 2.11%   |
| OpenMandriva 4.2       | 7         | 2.11%   |
| Zorin 17               | 6         | 1.81%   |
| Ubuntu 25.04           | 4         | 1.21%   |
| Ubuntu 20.10           | 4         | 1.21%   |
| SteamOS 3.5.19         | 4         | 1.21%   |
| Fedora 35              | 4         | 1.21%   |
| Ubuntu 21.04           | 3         | 0.91%   |
| Pop!_OS 20.04          | 3         | 0.91%   |
| OpenMandriva 25.90     | 3         | 0.91%   |
| OpenMandriva 23.08     | 3         | 0.91%   |
| LMDE 6                 | 3         | 0.91%   |
| Linux Mint 22.1        | 3         | 0.91%   |
| Linux Mint 22          | 3         | 0.91%   |
| Linux Mint 21.2        | 3         | 0.91%   |
| Kubuntu 24.04          | 3         | 0.91%   |
| KDE neon 24.04         | 3         | 0.91%   |
| KDE neon 22.04         | 3         | 0.91%   |
| Fedora 38              | 3         | 0.91%   |
| Endless 3.3.20-nexthw1 | 3         | 0.91%   |
| Debian Testing         | 3         | 0.91%   |
| Arch                   | 3         | 0.91%   |
| Ubuntu 24.10           | 2         | 0.6%    |
| Ubuntu 23.04           | 2         | 0.6%    |
| Ubuntu 19.04           | 2         | 0.6%    |
| SteamOS 3.4.8          | 2         | 0.6%    |
| Pop!_OS 20.10          | 2         | 0.6%    |
| OpenMandriva 25.06     | 2         | 0.6%    |
| OpenMandriva 25.01     | 2         | 0.6%    |
| OpenMandriva 24.12     | 2         | 0.6%    |
| NixOS 24.11            | 2         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 84        | 27.18%  |
| OpenMandriva  | 32        | 10.36%  |
| Fedora        | 26        | 8.41%   |
| Linux Mint    | 19        | 6.15%   |
| Zorin         | 14        | 4.53%   |
| Pop!_OS       | 14        | 4.53%   |
| Debian        | 14        | 4.53%   |
| Endless       | 13        | 4.21%   |
| SteamOS       | 12        | 3.88%   |
| Arch          | 12        | 3.88%   |
| Manjaro       | 7         | 2.27%   |
| Kubuntu       | 7         | 2.27%   |
| KDE neon      | 7         | 2.27%   |
| Kali          | 7         | 2.27%   |
| Elementary    | 5         | 1.62%   |
| NixOS         | 4         | 1.29%   |
| Xubuntu       | 3         | 0.97%   |
| LMDE          | 3         | 0.97%   |
| Parrot        | 2         | 0.65%   |
| Clear Linux   | 2         | 0.65%   |
| ChimeraOS     | 2         | 0.65%   |
| ArcoLinux     | 2         | 0.65%   |
| Void Linux    | 1         | 0.32%   |
| Ubuntu Unity  | 1         | 0.32%   |
| Ubuntu Kylin  | 1         | 0.32%   |
| Ubuntu Budgie | 1         | 0.32%   |
| Solus         | 1         | 0.32%   |
| ROSA          | 1         | 0.32%   |
| Rocky Linux   | 1         | 0.32%   |
| RHEL          | 1         | 0.32%   |
| Q4OS          | 1         | 0.32%   |
| PostmarketOS  | 1         | 0.32%   |
| Lubuntu       | 1         | 0.32%   |
| Liberty OS    | 1         | 0.32%   |
| Gentoo        | 1         | 0.32%   |
| Garuda Linux  | 1         | 0.32%   |
| Bluefin       | 1         | 0.32%   |
| BigLinux      | 1         | 0.32%   |
| Bazzite       | 1         | 0.32%   |
| Artix         | 1         | 0.32%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003     | 7         | 1.98%   |
| 5.10.14-desktop-1omv4002    | 6         | 1.69%   |
| 6.1.52-valve16-1-neptune-61 | 5         | 1.41%   |
| 6.14.2-desktop-3omv2590     | 4         | 1.13%   |
| 5.4.0-42-generic            | 4         | 1.13%   |
| 5.19.0-32-generic           | 4         | 1.13%   |
| 5.15.0-48-generic           | 4         | 1.13%   |
| 4.15.0-15-generic           | 4         | 1.13%   |
| 6.9.3-76060903-generic      | 3         | 0.85%   |
| 6.8.0-51-generic            | 3         | 0.85%   |
| 6.8.0-49-generic            | 3         | 0.85%   |
| 6.8.0-40-generic            | 3         | 0.85%   |
| 6.4.11-desktop-1omv2390     | 3         | 0.85%   |
| 6.2.0-32-generic            | 3         | 0.85%   |
| 6.14.0-27-generic           | 3         | 0.85%   |
| 5.4.0-19-generic            | 3         | 0.85%   |
| 5.13.0-valve36-1-neptune    | 3         | 0.85%   |
| 5.11.0-43-generic           | 3         | 0.85%   |
| 6.8.0-65-generic            | 2         | 0.56%   |
| 6.8.0-52-generic            | 2         | 0.56%   |
| 6.8.0-38-generic            | 2         | 0.56%   |
| 6.8.0-35-generic            | 2         | 0.56%   |
| 6.5.0-26-generic            | 2         | 0.56%   |
| 6.3.8-200.fc38.x86_64       | 2         | 0.56%   |
| 6.2.0-39-generic            | 2         | 0.56%   |
| 6.14.0-63.fc42.x86_64       | 2         | 0.56%   |
| 6.14.0-35-generic           | 2         | 0.56%   |
| 6.14.0-33-generic           | 2         | 0.56%   |
| 6.14.0-29-generic           | 2         | 0.56%   |
| 6.14.0-15-generic           | 2         | 0.56%   |
| 6.12.9-desktop-1omv2490     | 2         | 0.56%   |
| 6.12.10-76061203-generic    | 2         | 0.56%   |
| 6.11.0-26-generic           | 2         | 0.56%   |
| 6.11.0-19-generic           | 2         | 0.56%   |
| 6.1.0-34-amd64              | 2         | 0.56%   |
| 6.1.0-32-amd64              | 2         | 0.56%   |
| 6.1.0-28-amd64              | 2         | 0.56%   |
| 6.1.0-23-amd64              | 2         | 0.56%   |
| 6.1.0-13-amd64              | 2         | 0.56%   |
| 5.8.0-53-generic            | 2         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.8.0   | 24        | 7.16%   |
| 5.4.0   | 20        | 5.97%   |
| 5.15.0  | 20        | 5.97%   |
| 5.8.0   | 17        | 5.07%   |
| 5.11.0  | 15        | 4.48%   |
| 6.14.0  | 14        | 4.18%   |
| 6.1.0   | 12        | 3.58%   |
| 6.2.0   | 11        | 3.28%   |
| 5.19.0  | 11        | 3.28%   |
| 6.11.0  | 10        | 2.99%   |
| 5.3.0   | 10        | 2.99%   |
| 4.15.0  | 9         | 2.69%   |
| 6.5.0   | 8         | 2.39%   |
| 5.16.7  | 7         | 2.09%   |
| 6.14.2  | 6         | 1.79%   |
| 6.1.52  | 6         | 1.79%   |
| 5.13.0  | 6         | 1.79%   |
| 5.10.14 | 6         | 1.79%   |
| 6.9.3   | 4         | 1.19%   |
| 5.10.0  | 4         | 1.19%   |
| 5.0.0   | 4         | 1.19%   |
| 4.18.0  | 4         | 1.19%   |
| 6.4.11  | 3         | 0.9%    |
| 6.12.9  | 3         | 0.9%    |
| 6.9.9   | 2         | 0.6%    |
| 6.8.11  | 2         | 0.6%    |
| 6.5.3   | 2         | 0.6%    |
| 6.3.8   | 2         | 0.6%    |
| 6.15.3  | 2         | 0.6%    |
| 6.12.10 | 2         | 0.6%    |
| 6.9.2   | 1         | 0.3%    |
| 6.9.12  | 1         | 0.3%    |
| 6.6.6   | 1         | 0.3%    |
| 6.6.2   | 1         | 0.3%    |
| 6.6.19  | 1         | 0.3%    |
| 6.6.10  | 1         | 0.3%    |
| 6.5.6   | 1         | 0.3%    |
| 6.4.4   | 1         | 0.3%    |
| 6.4.0   | 1         | 0.3%    |
| 6.3.9   | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.8     | 26        | 7.93%   |
| 5.15    | 24        | 7.32%   |
| 5.4     | 22        | 6.71%   |
| 6.14    | 21        | 6.4%    |
| 6.1     | 20        | 6.1%    |
| 5.8     | 18        | 5.49%   |
| 5.11    | 17        | 5.18%   |
| 6.2     | 14        | 4.27%   |
| 5.19    | 14        | 4.27%   |
| 6.12    | 12        | 3.66%   |
| 6.11    | 12        | 3.66%   |
| 5.16    | 12        | 3.66%   |
| 6.5     | 11        | 3.35%   |
| 5.10    | 11        | 3.35%   |
| 5.3     | 10        | 3.05%   |
| 4.15    | 9         | 2.74%   |
| 6.9     | 7         | 2.13%   |
| 6.10    | 7         | 2.13%   |
| 5.13    | 7         | 2.13%   |
| 6.4     | 5         | 1.52%   |
| 4.18    | 5         | 1.52%   |
| 6.6     | 4         | 1.22%   |
| 6.3     | 4         | 1.22%   |
| 6.16    | 4         | 1.22%   |
| 5.0     | 4         | 1.22%   |
| 6.17    | 3         | 0.91%   |
| 6.15    | 3         | 0.91%   |
| 6.0     | 3         | 0.91%   |
| 5.6     | 3         | 0.91%   |
| 5.18    | 3         | 0.91%   |
| 5.7     | 2         | 0.61%   |
| 5.14    | 2         | 0.61%   |
| 4.9     | 2         | 0.61%   |
| 6.18    | 1         | 0.3%    |
| 6.13    | 1         | 0.3%    |
| 5.9     | 1         | 0.3%    |
| 5.5     | 1         | 0.3%    |
| 5.17    | 1         | 0.3%    |
| 4.13    | 1         | 0.3%    |
| 3.10    | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 285       | 98.28%  |
| i686   | 4         | 1.38%   |
| armv7l | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 149       | 48.38%  |
| KDE5             | 49        | 15.91%  |
| KDE6             | 22        | 7.14%   |
| Unknown          | 22        | 7.14%   |
| X-Cinnamon       | 21        | 6.82%   |
| XFCE             | 16        | 5.19%   |
| Pantheon         | 5         | 1.62%   |
| KDE              | 5         | 1.62%   |
| Cinnamon         | 4         | 1.3%    |
| MATE             | 3         | 0.97%   |
| LXQt             | 3         | 0.97%   |
| Budgie           | 2         | 0.65%   |
| Unity            | 1         | 0.32%   |
| UKUI             | 1         | 0.32%   |
| trinity          | 1         | 0.32%   |
| openbox          | 1         | 0.32%   |
| lightdm-xsession | 1         | 0.32%   |
| KDE4             | 1         | 0.32%   |
| i3               | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 180       | 60.2%   |
| Wayland | 101       | 33.78%  |
| Unknown | 11        | 3.68%   |
| Tty     | 7         | 2.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 145       | 48.01%  |
| GDM3    | 51        | 16.89%  |
| SDDM    | 49        | 16.23%  |
| GDM     | 32        | 10.6%   |
| LightDM | 20        | 6.62%   |
| TDM     | 4         | 1.32%   |
| KDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 235       | 79.66%  |
| Unknown | 14        | 4.75%   |
| ar_SA   | 12        | 4.07%   |
| ar_EG   | 12        | 4.07%   |
| en_GB   | 10        | 3.39%   |
| C       | 6         | 2.03%   |
| fr_FR   | 1         | 0.34%   |
| en_IN   | 1         | 0.34%   |
| en_AG   | 1         | 0.34%   |
| Default | 1         | 0.34%   |
| ar_SY   | 1         | 0.34%   |
| ar_AE   | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 159       | 53.54%  |
| EFI  | 138       | 46.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 196       | 65.77%  |
| Btrfs   | 49        | 16.44%  |
| Tmpfs   | 24        | 8.05%   |
| Overlay | 16        | 5.37%   |
| Unknown | 6         | 2.01%   |
| Xfs     | 5         | 1.68%   |
| Zfs     | 1         | 0.34%   |
| Ext2    | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 149       | 50%     |
| GPT     | 128       | 42.95%  |
| MBR     | 21        | 7.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 259       | 87.5%   |
| Yes       | 37        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 227       | 75.92%  |
| Yes       | 72        | 24.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo                      | 54        | 18.62%  |
| Dell                        | 49        | 16.9%   |
| ASUSTek Computer            | 42        | 14.48%  |
| Hewlett-Packard             | 38        | 13.1%   |
| Acer                        | 17        | 5.86%   |
| Toshiba                     | 13        | 4.48%   |
| MSI                         | 13        | 4.48%   |
| Valve                       | 12        | 4.14%   |
| Apple                       | 12        | 4.14%   |
| HUAWEI                      | 11        | 3.79%   |
| Sony                        | 6         | 2.07%   |
| Samsung Electronics         | 3         | 1.03%   |
| Notebook                    | 2         | 0.69%   |
| I-Life Digital Technologies | 2         | 0.69%   |
| Google                      | 2         | 0.69%   |
| SDZ                         | 1         | 0.34%   |
| Razer                       | 1         | 0.34%   |
| Packard Bell                | 1         | 0.34%   |
| LG Electronics              | 1         | 0.34%   |
| HONOR                       | 1         | 0.34%   |
| GPD                         | 1         | 0.34%   |
| GIADA                       | 1         | 0.34%   |
| Fujitsu                     | 1         | 0.34%   |
| Framework                   | 1         | 0.34%   |
| eMachines                   | 1         | 0.34%   |
| Clevo                       | 1         | 0.34%   |
| Chuwi                       | 1         | 0.34%   |
| Alienware                   | 1         | 0.34%   |
| Unknown                     | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Valve Jupiter                              | 10        | 3.45%   |
| Dell G3 3590                               | 5         | 1.72%   |
| Unknown                                    | 5         | 1.72%   |
| Dell Inspiron 3542                         | 4         | 1.38%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 4         | 1.38%   |
| HP Notebook                                | 3         | 1.03%   |
| HP Laptop 15-da2xxx                        | 3         | 1.03%   |
| HP 15                                      | 3         | 1.03%   |
| Valve Galileo                              | 2         | 0.69%   |
| MSI Modern 14 B5M                          | 2         | 0.69%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 2         | 0.69%   |
| Lenovo IdeaPad 3 14IIL05 81WD              | 2         | 0.69%   |
| HUAWEI KLVD-WXX9                           | 2         | 0.69%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.69%   |
| HP Pavilion g6                             | 2         | 0.69%   |
| HP Laptop 15-da0xxx                        | 2         | 0.69%   |
| Dell XPS 9320                              | 2         | 0.69%   |
| Dell Inspiron N5110                        | 2         | 0.69%   |
| Dell Inspiron 3581                         | 2         | 0.69%   |
| Dell Inspiron 1525                         | 2         | 0.69%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 2         | 0.69%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 2         | 0.69%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 2         | 0.69%   |
| Apple MacBookPro9,2                        | 2         | 0.69%   |
| Apple MacBookPro8,1                        | 2         | 0.69%   |
| Apple MacBookPro11,3                       | 2         | 0.69%   |
| Apple MacBookAir7,2                        | 2         | 0.69%   |
| Acer Aspire ES1-572                        | 2         | 0.69%   |
| Acer Aspire 4752                           | 2         | 0.69%   |
| Toshiba Satellite S55t-A                   | 1         | 0.34%   |
| Toshiba Satellite P55W-C                   | 1         | 0.34%   |
| Toshiba Satellite L635                     | 1         | 0.34%   |
| Toshiba Satellite L500                     | 1         | 0.34%   |
| Toshiba Satellite C855D                    | 1         | 0.34%   |
| Toshiba Satellite C850-B820                | 1         | 0.34%   |
| Toshiba Satellite C850-B561                | 1         | 0.34%   |
| Toshiba Satellite C850-B239                | 1         | 0.34%   |
| Toshiba Satellite C650                     | 1         | 0.34%   |
| Toshiba Satellite C55t-A                   | 1         | 0.34%   |
| Toshiba Satellite C55-B                    | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 26        | 8.97%   |
| Dell Inspiron      | 23        | 7.93%   |
| ASUS VivoBook      | 15        | 5.17%   |
| Lenovo IdeaPad     | 14        | 4.83%   |
| Acer Aspire        | 13        | 4.48%   |
| Toshiba Satellite  | 12        | 4.14%   |
| HP Pavilion        | 12        | 4.14%   |
| HP Laptop          | 11        | 3.79%   |
| Valve Jupiter      | 10        | 3.45%   |
| Dell Latitude      | 9         | 3.1%    |
| Dell XPS           | 5         | 1.72%   |
| Dell G3            | 5         | 1.72%   |
| ASUS ROG           | 5         | 1.72%   |
| Unknown            | 5         | 1.72%   |
| ASUS TUF           | 4         | 1.38%   |
| MSI Modern         | 3         | 1.03%   |
| MSI GF63           | 3         | 1.03%   |
| HP ProBook         | 3         | 1.03%   |
| HP Notebook        | 3         | 1.03%   |
| HP 15              | 3         | 1.03%   |
| Dell Vostro        | 3         | 1.03%   |
| ASUS Zenbook       | 3         | 1.03%   |
| Apple MacBookPro11 | 3         | 1.03%   |
| Valve Galileo      | 2         | 0.69%   |
| MSI GS66           | 2         | 0.69%   |
| Lenovo ThinkBook   | 2         | 0.69%   |
| Lenovo Legion      | 2         | 0.69%   |
| Lenovo B590        | 2         | 0.69%   |
| I-Life Digital ZED | 2         | 0.69%   |
| HUAWEI KLVD-WXX9   | 2         | 0.69%   |
| HP EliteBook       | 2         | 0.69%   |
| Dell Precision     | 2         | 0.69%   |
| Apple MacBookPro9  | 2         | 0.69%   |
| Apple MacBookPro8  | 2         | 0.69%   |
| Apple MacBookAir7  | 2         | 0.69%   |
| Acer Swift         | 2         | 0.69%   |
| Toshiba QOSMIO     | 1         | 0.34%   |
| Sony VPCEA36FA     | 1         | 0.34%   |
| Sony VPCCA35FA     | 1         | 0.34%   |
| Sony VGN-FZ250E    | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 32        | 11.03%  |
| 2018    | 32        | 11.03%  |
| 2019    | 28        | 9.66%   |
| 2021    | 23        | 7.93%   |
| 2013    | 20        | 6.9%    |
| 2012    | 19        | 6.55%   |
| 2011    | 18        | 6.21%   |
| 2022    | 16        | 5.52%   |
| 2016    | 16        | 5.52%   |
| 2014    | 14        | 4.83%   |
| 2023    | 13        | 4.48%   |
| 2017    | 12        | 4.14%   |
| 2024    | 10        | 3.45%   |
| 2015    | 9         | 3.1%    |
| 2010    | 9         | 3.1%    |
| 2009    | 5         | 1.72%   |
| 2008    | 4         | 1.38%   |
| 2025    | 3         | 1.03%   |
| 2007    | 3         | 1.03%   |
| 2006    | 2         | 0.69%   |
| 2002    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 290       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 275       | 93.86%  |
| Enabled  | 18        | 6.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 288       | 99.31%  |
| Yes  | 2         | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 77        | 25.75%  |
| 8.01-16.0   | 60        | 20.07%  |
| 3.01-4.0    | 54        | 18.06%  |
| 16.01-24.0  | 54        | 18.06%  |
| 32.01-64.0  | 27        | 9.03%   |
| 1.01-2.0    | 13        | 4.35%   |
| 24.01-32.0  | 6         | 2.01%   |
| 2.01-3.0    | 5         | 1.67%   |
| 64.01-256.0 | 3         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 92        | 28.57%  |
| 2.01-3.0  | 91        | 28.26%  |
| 4.01-8.0  | 60        | 18.63%  |
| 3.01-4.0  | 55        | 17.08%  |
| 0.51-1.0  | 13        | 4.04%   |
| 8.01-16.0 | 9         | 2.8%    |
| 0.01-0.5  | 1         | 0.31%   |
| Unknown   | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 212       | 71.14%  |
| 2      | 73        | 24.5%   |
| 3      | 11        | 3.69%   |
| 4      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 199       | 67.92%  |
| Yes       | 94        | 32.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 211       | 72.26%  |
| No        | 81        | 27.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 281       | 96.9%   |
| No        | 9         | 3.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 86.69%  |
| No        | 39        | 13.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Saudi Arabia | 290       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Riyadh               | 108       | 34.73%  |
| Jeddah               | 76        | 24.44%  |
| Makkah               | 31        | 9.97%   |
| Dammam               | 25        | 8.04%   |
| Medina               | 21        | 6.75%   |
| Al Qatif             | 10        | 3.22%   |
| Khobar               | 8         | 2.57%   |
| Baq`a' ash Sharqiyah | 6         | 1.93%   |
| Ta'if                | 4         | 1.29%   |
| Dhahran              | 4         | 1.29%   |
| Buraidah             | 4         | 1.29%   |
| Thuwal               | 3         | 0.96%   |
| Abha                 | 3         | 0.96%   |
| Yanbu                | 1         | 0.32%   |
| Sayhat               | 1         | 0.32%   |
| Najran               | 1         | 0.32%   |
| Jubail               | 1         | 0.32%   |
| Jizan                | 1         | 0.32%   |
| Al Kharj             | 1         | 0.32%   |
| Al Hufuf             | 1         | 0.32%   |
| Al Faruq             | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 50        | 56     | 13.44%  |
| Seagate                     | 40        | 51     | 10.75%  |
| Toshiba                     | 38        | 53     | 10.22%  |
| WDC                         | 35        | 41     | 9.41%   |
| Kingston                    | 34        | 47     | 9.14%   |
| Sandisk                     | 27        | 27     | 7.26%   |
| Unknown                     | 21        | 27     | 5.65%   |
| SK hynix                    | 15        | 21     | 4.03%   |
| Micron Technology           | 12        | 12     | 3.23%   |
| Intel                       | 11        | 19     | 2.96%   |
| Apple                       | 7         | 9      | 1.88%   |
| Phison Electronics          | 6         | 9      | 1.61%   |
| Micron/Crucial Technology   | 6         | 8      | 1.61%   |
| KIOXIA                      | 6         | 10     | 1.61%   |
| Hitachi                     | 5         | 5      | 1.34%   |
| Crucial                     | 5         | 7      | 1.34%   |
| China                       | 5         | 7      | 1.34%   |
| JMicron Technology          | 4         | 4      | 1.08%   |
| Lexar                       | 3         | 3      | 0.81%   |
| HGST                        | 3         | 3      | 0.81%   |
| XrayDisk                    | 2         | 3      | 0.54%   |
| Silicon Motion              | 2         | 2      | 0.54%   |
| Phison                      | 2         | 3      | 0.54%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.54%   |
| Kingston Technology Company | 2         | 2      | 0.54%   |
| KingSpec                    | 2         | 2      | 0.54%   |
| Hewlett-Packard             | 2         | 2      | 0.54%   |
| Fujitsu                     | 2         | 3      | 0.54%   |
| Unknown                     | 2         | 2      | 0.54%   |
| YS                          | 1         | 2      | 0.27%   |
| YMTC                        | 1         | 1      | 0.27%   |
| Yangtze Memory Technologies | 1         | 1      | 0.27%   |
| Union Memory                | 1         | 1      | 0.27%   |
| SPCC                        | 1         | 1      | 0.27%   |
| RPFTJ256                    | 1         | 1      | 0.27%   |
| Realtek Semiconductor       | 1         | 1      | 0.27%   |
| PNY                         | 1         | 1      | 0.27%   |
| OYUNKEY                     | 1         | 1      | 0.27%   |
| MTFDDAV5                    | 1         | 1      | 0.27%   |
| Lite-On Technology          | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                             | 15        | 3.91%   |
| Seagate ST1000LM035-1RK172 1TB                     | 14        | 3.65%   |
| Kingston SA400S37240G 240GB SSD                    | 14        | 3.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 8         | 2.08%   |
| Kingston SA400S37480G 480GB SSD                    | 8         | 2.08%   |
| Toshiba MQ01ABD100 1TB                             | 5         | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5         | 1.3%    |
| Phison PS5013 E13 NVMe Controller 500GB            | 4         | 1.04%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 4         | 1.04%   |
| WDC WD10SPZX-08Z10 1TB                             | 3         | 0.78%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 3         | 0.78%   |
| Unknown MMC Card  512GB                            | 3         | 0.78%   |
| Unknown MMC Card  32GB                             | 3         | 0.78%   |
| Unknown MMC Card  16GB                             | 3         | 0.78%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.78%   |
| SanDisk NVMe SSD Drive 128GB                       | 3         | 0.78%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                   | 3         | 0.78%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                   | 3         | 0.78%   |
| Kingston SA400S37120G 120GB SSD                    | 3         | 0.78%   |
| JMicron Tech 250GB                                 | 3         | 0.78%   |
| Intel SSD 660P Series 512GB                        | 3         | 0.78%   |
| XrayDisk SSD 1TB                                   | 2         | 0.52%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 2         | 0.52%   |
| Unknown MMC Card  256GB                            | 2         | 0.52%   |
| Unknown MMC Card  128GB                            | 2         | 0.52%   |
| Toshiba MQ01ABD075 752GB                           | 2         | 0.52%   |
| Toshiba MK7559GSXF 752GB                           | 2         | 0.52%   |
| Toshiba KBG40ZNS256G NVMe 256GB                    | 2         | 0.52%   |
| SK hynix PC401 NVMe Solid State Drive 256GB        | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 1024GB                     | 2         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive 512GB        | 2         | 0.52%   |
| Silicon Motion PCIe-8 SSD 512GB                    | 2         | 0.52%   |
| Seagate ST9500325AS 500GB                          | 2         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 2         | 0.52%   |
| Samsung SSD 860 EVO 1TB                            | 2         | 0.52%   |
| Samsung NVMe SSD Drive 1024GB                      | 2         | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 2         | 0.52%   |
| Samsung HM321HI 320GB                              | 2         | 0.52%   |
| Phison 311CD0512GB                                 | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 50     | 34.82%  |
| Toshiba             | 36        | 43     | 32.14%  |
| WDC                 | 22        | 27     | 19.64%  |
| Hitachi             | 5         | 5      | 4.46%   |
| HGST                | 3         | 3      | 2.68%   |
| Samsung Electronics | 2         | 2      | 1.79%   |
| Fujitsu             | 2         | 3      | 1.79%   |
| KESU                | 1         | 1      | 0.89%   |
| JMicron Technology  | 1         | 1      | 0.89%   |
| ASMT                | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 27        | 35     | 27.55%  |
| SanDisk             | 15        | 15     | 15.31%  |
| Samsung Electronics | 13        | 13     | 13.27%  |
| WDC                 | 8         | 8      | 8.16%   |
| Apple               | 6         | 7      | 6.12%   |
| China               | 5         | 7      | 5.1%    |
| Crucial             | 4         | 4      | 4.08%   |
| SK hynix            | 3         | 5      | 3.06%   |
| XrayDisk            | 2         | 3      | 2.04%   |
| Micron Technology   | 2         | 2      | 2.04%   |
| Lexar               | 2         | 2      | 2.04%   |
| KingSpec            | 2         | 2      | 2.04%   |
| Hewlett-Packard     | 2         | 2      | 2.04%   |
| YS                  | 1         | 2      | 1.02%   |
| PNY                 | 1         | 1      | 1.02%   |
| OYUNKEY             | 1         | 1      | 1.02%   |
| GLOWAY              | 1         | 2      | 1.02%   |
| G-DRIVE             | 1         | 1      | 1.02%   |
| A-DATA Technology   | 1         | 1      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 130       | 177    | 36.21%  |
| HDD     | 108       | 136    | 30.08%  |
| SSD     | 92        | 114    | 25.63%  |
| MMC     | 20        | 27     | 5.57%   |
| Unknown | 9         | 12     | 2.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 178       | 248    | 52.2%   |
| NVMe | 130       | 176    | 38.12%  |
| MMC  | 20        | 27     | 5.87%   |
| SAS  | 13        | 15     | 3.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 130    | 51.5%   |
| 0.51-1.0   | 89        | 112    | 44.5%   |
| 1.01-2.0   | 8         | 8      | 4%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 75        | 24.04%  |
| 251-500        | 73        | 23.4%   |
| 501-1000       | 66        | 21.15%  |
| 1001-2000      | 25        | 8.01%   |
| 51-100         | 22        | 7.05%   |
| 1-20           | 17        | 5.45%   |
| 21-50          | 15        | 4.81%   |
| More than 3000 | 8         | 2.56%   |
| 2001-3000      | 7         | 2.24%   |
| Unknown        | 4         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 132       | 40.37%  |
| 21-50          | 70        | 21.41%  |
| 101-250        | 38        | 11.62%  |
| 51-100         | 38        | 11.62%  |
| 251-500        | 26        | 7.95%   |
| 501-1000       | 13        | 3.98%   |
| 1001-2000      | 4         | 1.22%   |
| Unknown        | 4         | 1.22%   |
| More than 3000 | 1         | 0.31%   |
| 2001-3000      | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| YS SSD 240GB                       | 1         | 1      | 7.69%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 7.69%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 1      | 7.69%   |
| WDC WD10SPZX-08Z10 1TB             | 1         | 1      | 7.69%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 7.69%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 7.69%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 7.69%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB     | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 7.69%   |
| OYUNKEY SSD 120GB                  | 1         | 1      | 7.69%   |
| HGST HTS541075A9E680 752GB         | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 38.46%  |
| Seagate | 3         | 3      | 23.08%  |
| Toshiba | 2         | 2      | 15.38%  |
| YS      | 1         | 1      | 7.69%   |
| OYUNKEY | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 5         | 5      | 45.45%  |
| Seagate | 3         | 3      | 27.27%  |
| Toshiba | 2         | 2      | 18.18%  |
| HGST    | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 84.62%  |
| SSD  | 2         | 2      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                      | Notebooks | Drives | Percent |
|----------------------------|-----------|--------|---------|
| HGST HTS545050A7E380 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 184       | 288    | 59.35%  |
| Works    | 112       | 164    | 36.13%  |
| Malfunc  | 13        | 13     | 4.19%   |
| Failed   | 1         | 1      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 196       | 56.81%  |
| Samsung Electronics              | 40        | 11.59%  |
| AMD                              | 18        | 5.22%   |
| SanDisk                          | 17        | 4.93%   |
| SK hynix                         | 12        | 3.48%   |
| Micron Technology                | 10        | 2.9%    |
| Kingston Technology Company      | 9         | 2.61%   |
| Phison Electronics               | 8         | 2.32%   |
| Micron/Crucial Technology        | 8         | 2.32%   |
| KIOXIA                           | 7         | 2.03%   |
| Toshiba America Info Systems     | 3         | 0.87%   |
| Silicon Motion                   | 3         | 0.87%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.87%   |
| Yangtze Memory Technologies      | 2         | 0.58%   |
| Realtek Semiconductor            | 2         | 0.58%   |
| Union Memory (Shenzhen)          | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Shenzhen Wodposit Electronics    | 1         | 0.29%   |
| Seagate Technology               | 1         | 0.29%   |
| Nvidia                           | 1         | 0.29%   |
| Lite-On Technology               | 1         | 0.29%   |
| Apple                            | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 24        | 6.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 21        | 5.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 5.19%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 4.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 16        | 4.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 4.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 4.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 3.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 11        | 3.01%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 2.73%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 2.19%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 1.91%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 1.91%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 6         | 1.64%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 6         | 1.64%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 1.37%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 1.37%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 5         | 1.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.37%   |
| Intel SSD 660P Series                                                          | 5         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 5         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.37%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 1.09%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 4         | 1.09%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.09%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 1.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.09%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 0.82%   |
| SanDisk PC SN520 x2 M.2 2230 NVMe SSD                                          | 3         | 0.82%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 3         | 0.82%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 3         | 0.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.82%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 3         | 0.82%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 3         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.82%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.55%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 180       | 50.99%  |
| NVMe | 130       | 36.83%  |
| RAID | 30        | 8.5%    |
| IDE  | 13        | 3.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 243       | 83.79%  |
| AMD    | 46        | 15.86%  |
| ARM    | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 3.78%   |
| AMD Custom APU 0405                           | 10        | 3.44%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 2.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 2.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.72%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.37%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.37%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 4         | 1.37%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 1.37%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.37%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.03%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 3         | 1.03%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.03%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 3         | 1.03%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 1.03%   |
| Intel 12th Gen Core i7-12700H                 | 3         | 1.03%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 1.03%   |
| Intel 12th Gen Core i5-1235U                  | 3         | 1.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.03%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 1.03%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 1.03%   |
| Intel Core Ultra 7 255H                       | 2         | 0.69%   |
| Intel Core Ultra 7 155H                       | 2         | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.69%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 76        | 26.12%  |
| Intel Core i5           | 66        | 22.68%  |
| Other                   | 47        | 16.15%  |
| Intel Core i3           | 24        | 8.25%   |
| Intel Celeron           | 17        | 5.84%   |
| AMD Ryzen 5             | 15        | 5.15%   |
| AMD Ryzen 7             | 12        | 4.12%   |
| Intel Core 2 Duo        | 7         | 2.41%   |
| Intel Core              | 6         | 2.06%   |
| AMD Ryzen 9             | 5         | 1.72%   |
| Intel Pentium Dual-Core | 4         | 1.37%   |
| Intel Atom              | 4         | 1.37%   |
| Intel Pentium           | 2         | 0.69%   |
| Intel Pentium Dual      | 1         | 0.34%   |
| Intel Mobile Pentium 4  | 1         | 0.34%   |
| Intel Genuine           | 1         | 0.34%   |
| ARM ARMv7               | 1         | 0.34%   |
| AMD E2                  | 1         | 0.34%   |
| AMD A12                 | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 126       | 43.45%  |
| 4      | 95        | 32.76%  |
| 6      | 25        | 8.62%   |
| 8      | 19        | 6.55%   |
| 14     | 6         | 2.07%   |
| 16     | 5         | 1.72%   |
| 12     | 5         | 1.72%   |
| 10     | 5         | 1.72%   |
| 1      | 4         | 1.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 289       | 99.66%  |
| 16     | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 238       | 82.07%  |
| 1      | 51        | 17.59%  |
| 8      | 1         | 0.34%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 284       | 97.59%  |
| Unknown        | 5         | 1.72%   |
| 32-bit         | 2         | 0.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 57.57%  |
| 0x40651    | 12        | 3.95%   |
| 0x306a9    | 12        | 3.95%   |
| 0x206a7    | 12        | 3.95%   |
| 0x1067a    | 8         | 2.63%   |
| 0x806c1    | 7         | 2.3%    |
| 0x406e3    | 7         | 2.3%    |
| 0x806ec    | 6         | 1.97%   |
| 0x806ea    | 6         | 1.97%   |
| 0x706a1    | 5         | 1.64%   |
| 0x906ea    | 4         | 1.32%   |
| 0x806e9    | 4         | 1.32%   |
| 0x306d4    | 4         | 1.32%   |
| 0x20655    | 4         | 1.32%   |
| 0xa0652    | 3         | 0.99%   |
| 0x906a3    | 3         | 0.99%   |
| 0x706e5    | 3         | 0.99%   |
| 0x30673    | 3         | 0.99%   |
| 0x20652    | 3         | 0.99%   |
| 0x08108109 | 3         | 0.99%   |
| 0x08600106 | 2         | 0.66%   |
| 0xf27      | 1         | 0.33%   |
| 0xb06a2    | 1         | 0.33%   |
| 0x906e9    | 1         | 0.33%   |
| 0x806eb    | 1         | 0.33%   |
| 0x706a8    | 1         | 0.33%   |
| 0x6fd      | 1         | 0.33%   |
| 0x6fa      | 1         | 0.33%   |
| 0x306c3    | 1         | 0.33%   |
| 0x106f1    | 1         | 0.33%   |
| 0x0a50000d | 1         | 0.33%   |
| 0x0a50000c | 1         | 0.33%   |
| 0x08901003 | 1         | 0.33%   |
| 0x08701013 | 1         | 0.33%   |
| 0x08600109 | 1         | 0.33%   |
| 0x08600104 | 1         | 0.33%   |
| 0x08108102 | 1         | 0.33%   |
| 0x0810100b | 1         | 0.33%   |
| 0x0600611a | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 58        | 19.93%  |
| Unknown           | 30        | 10.31%  |
| Haswell           | 25        | 8.59%   |
| IvyBridge         | 22        | 7.56%   |
| TigerLake         | 19        | 6.53%   |
| SandyBridge       | 19        | 6.53%   |
| Skylake           | 14        | 4.81%   |
| Alderlake Hybrid  | 11        | 3.78%   |
| Zen 3             | 10        | 3.44%   |
| Goldmont plus     | 10        | 3.44%   |
| Westmere          | 9         | 3.09%   |
| Penryn            | 9         | 3.09%   |
| Broadwell         | 9         | 3.09%   |
| Zen 2             | 8         | 2.75%   |
| CometLake         | 8         | 2.75%   |
| Zen+              | 7         | 2.41%   |
| Silvermont        | 6         | 2.06%   |
| IceLake           | 6         | 2.06%   |
| Core              | 4         | 1.37%   |
| Zen               | 1         | 0.34%   |
| NetBurst          | 1         | 0.34%   |
| Meteorlake Hybrid | 1         | 0.34%   |
| Goldmont          | 1         | 0.34%   |
| Excavator         | 1         | 0.34%   |
| Bonnell           | 1         | 0.34%   |
| Bobcat            | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 228       | 58.31%  |
| Nvidia                           | 93        | 23.79%  |
| AMD                              | 69        | 17.65%  |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 21        | 5.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 19        | 4.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 18        | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 18        | 4.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 14        | 3.54%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                         | 10        | 2.53%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                       | 10        | 2.53%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                      | 10        | 2.53%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 10        | 2.53%   |
| AMD VanGogh [AMD Custom GPU 0405]                                             | 10        | 2.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 2.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 9         | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 7         | 1.77%   |
| Intel Core Processor Integrated Graphics Controller                           | 7         | 1.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 7         | 1.77%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                     | 7         | 1.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 7         | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 7         | 1.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 6         | 1.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 6         | 1.52%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                      | 6         | 1.52%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                   | 6         | 1.52%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 5         | 1.26%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 1.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 5         | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 5         | 1.26%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 1.01%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 4         | 1.01%   |
| Intel Raptor Lake-P [UHD Graphics]                                            | 4         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 4         | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 4         | 1.01%   |
| AMD Lucienne                                                                  | 4         | 1.01%   |
| Nvidia TU117M [GeForce MX450]                                                 | 3         | 0.76%   |
| Nvidia GP107M [GeForce MX350]                                                 | 3         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                   | 3         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                       | 3         | 0.76%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 3         | 0.76%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                               | 3         | 0.76%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                         | 3         | 0.76%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                      | 3         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 137       | 46.92%  |
| Intel + Nvidia | 70        | 23.97%  |
| 1 x AMD        | 38        | 13.01%  |
| Intel + AMD    | 19        | 6.51%   |
| AMD + Nvidia   | 12        | 4.11%   |
| 1 x Nvidia     | 11        | 3.77%   |
| 2 x Intel      | 2         | 0.68%   |
| Other          | 1         | 0.34%   |
| 2 x AMD        | 1         | 0.34%   |
| 1 x SiS        | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 245       | 83.05%  |
| Proprietary | 38        | 12.88%  |
| Unknown     | 12        | 4.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 216       | 73.47%  |
| 1.01-2.0   | 29        | 9.86%   |
| 0.01-0.5   | 15        | 5.1%    |
| 3.01-4.0   | 14        | 4.76%   |
| 0.51-1.0   | 11        | 3.74%   |
| 7.01-8.0   | 6         | 2.04%   |
| 2.01-3.0   | 3         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 69        | 22.04%  |
| AU Optronics            | 51        | 16.29%  |
| Chimei Innolux          | 41        | 13.1%   |
| LG Display              | 40        | 12.78%  |
| Samsung Electronics     | 22        | 7.03%   |
| Valve                   | 12        | 3.83%   |
| Apple                   | 12        | 3.83%   |
| Sharp                   | 8         | 2.56%   |
| Lenovo                  | 7         | 2.24%   |
| Dell                    | 6         | 1.92%   |
| PANDA                   | 5         | 1.6%    |
| BenQ                    | 5         | 1.6%    |
| Chi Mei Optoelectronics | 4         | 1.28%   |
| Unknown                 | 3         | 0.96%   |
| Goldstar                | 3         | 0.96%   |
| Sony                    | 2         | 0.64%   |
| InnoLux Display         | 2         | 0.64%   |
| Ancor Communications    | 2         | 0.64%   |
| ___                     | 1         | 0.32%   |
| Xiaomi                  | 1         | 0.32%   |
| ViewSonic               | 1         | 0.32%   |
| Unknown (XXX)           | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| TMX                     | 1         | 0.32%   |
| SKY                     | 1         | 0.32%   |
| SKG                     | 1         | 0.32%   |
| RTK                     | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| KGS                     | 1         | 0.32%   |
| InfoVision              | 1         | 0.32%   |
| Huion                   | 1         | 0.32%   |
| Hewlett-Packard         | 1         | 0.32%   |
| EDO                     | 1         | 0.32%   |
| CHO                     | 1         | 0.32%   |
| ASUSTek Computer        | 1         | 0.32%   |
| Aosiman                 | 1         | 0.32%   |
| Acer                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 10        | 3.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 2.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 1.27%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 4         | 1.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 4         | 1.27%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 1.27%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 1.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 1.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.27%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 0.96%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 3         | 0.96%   |
| BOE LCD Monitor BOE094A 1920x1080 344x194mm 15.5-inch                    | 3         | 0.96%   |
| BOE LCD Monitor BOE0819 1920x1080 344x194mm 15.5-inch                    | 3         | 0.96%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.96%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.96%   |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                       | 3         | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.96%   |
| Valve ANX7530 U VLV3003 800x1280 100x160mm 7.4-inch                      | 2         | 0.64%   |
| Unknown SMART TV 6488 3840x2160 1209x680mm 54.6-inch                     | 2         | 0.64%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch                  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.64%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.64%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.64%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.64%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.64%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.64%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch         | 2         | 0.64%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15BB 1920x1080 344x194mm 15.5-inch         | 2         | 0.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.64%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 2         | 0.64%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 2         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 122       | 40.67%  |
| 1366x768 (WXGA)    | 99        | 33%     |
| 800x1280           | 12        | 4%      |
| 3840x2160 (4K)     | 11        | 3.67%   |
| 2880x1800          | 8         | 2.67%   |
| 1920x1200 (WUXGA)  | 8         | 2.67%   |
| 1280x800 (WXGA)    | 8         | 2.67%   |
| 2560x1440 (QHD)    | 6         | 2%      |
| 2160x1440          | 6         | 2%      |
| 2560x1600          | 4         | 1.33%   |
| 3840x2400          | 3         | 1%      |
| 1600x900 (HD+)     | 3         | 1%      |
| 1680x1050 (WSXGA+) | 2         | 0.67%   |
| 1440x900 (WXGA+)   | 2         | 0.67%   |
| 3456x2160          | 1         | 0.33%   |
| 3440x1440          | 1         | 0.33%   |
| 2256x1504          | 1         | 0.33%   |
| 1360x768           | 1         | 0.33%   |
| 1280x1024 (SXGA)   | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 154       | 49.2%   |
| 14      | 46        | 14.7%   |
| 13      | 43        | 13.74%  |
| 7       | 12        | 3.83%   |
| 16      | 8         | 2.56%   |
| 27      | 7         | 2.24%   |
| 21      | 6         | 1.92%   |
| 17      | 6         | 1.92%   |
| 24      | 5         | 1.6%    |
| 12      | 5         | 1.6%    |
| 31      | 4         | 1.28%   |
| 72      | 2         | 0.64%   |
| 63      | 2         | 0.64%   |
| 54      | 2         | 0.64%   |
| 11      | 2         | 0.64%   |
| Unknown | 2         | 0.64%   |
| 86      | 1         | 0.32%   |
| 82      | 1         | 0.32%   |
| 42      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 34      | 1         | 0.32%   |
| 23      | 1         | 0.32%   |
| 18      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 223       | 71.94%  |
| 201-300     | 31        | 10%     |
| 1-100       | 12        | 3.87%   |
| 501-600     | 11        | 3.55%   |
| 351-400     | 9         | 2.9%    |
| 401-500     | 7         | 2.26%   |
| 1001-1500   | 5         | 1.61%   |
| 601-700     | 4         | 1.29%   |
| 1501-2000   | 3         | 0.97%   |
| Unknown     | 2         | 0.65%   |
| 801-900     | 1         | 0.32%   |
| 701-800     | 1         | 0.32%   |
| 901-1000    | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 230       | 80.14%  |
| 16/10   | 34        | 11.85%  |
| 0.67    | 10        | 3.48%   |
| 3/2     | 7         | 2.44%   |
| 0.62    | 2         | 0.7%    |
| 5/4     | 1         | 0.35%   |
| 21/9    | 1         | 0.35%   |
| 0.56    | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 153       | 48.88%  |
| 81-90          | 78        | 24.92%  |
| 1-40           | 12        | 3.83%   |
| 71-80          | 11        | 3.51%   |
| 201-250        | 9         | 2.88%   |
| More than 1000 | 8         | 2.56%   |
| 111-120        | 8         | 2.56%   |
| 301-350        | 7         | 2.24%   |
| 61-70          | 5         | 1.6%    |
| 351-500        | 5         | 1.6%    |
| 121-130        | 5         | 1.6%    |
| 51-60          | 2         | 0.64%   |
| 251-300        | 2         | 0.64%   |
| 141-150        | 2         | 0.64%   |
| 501-1000       | 2         | 0.64%   |
| Unknown        | 2         | 0.64%   |
| 151-200        | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 124       | 40.26%  |
| 101-120       | 102       | 33.12%  |
| 161-240       | 33        | 10.71%  |
| 51-100        | 32        | 10.39%  |
| More than 240 | 11        | 3.57%   |
| 1-50          | 4         | 1.3%    |
| Unknown       | 2         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 258       | 86.87%  |
| 2     | 29        | 9.76%   |
| 0     | 5         | 1.68%   |
| 3     | 4         | 1.35%   |
| 4     | 1         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 167       | 37.53%  |
| Intel                            | 123       | 27.64%  |
| Qualcomm Atheros                 | 60        | 13.48%  |
| Broadcom                         | 32        | 7.19%   |
| MediaTek                         | 13        | 2.92%   |
| Samsung Electronics              | 7         | 1.57%   |
| Ralink                           | 6         | 1.35%   |
| Broadcom Limited                 | 5         | 1.12%   |
| Ralink Technology                | 4         | 0.9%    |
| Marvell Technology Group         | 4         | 0.9%    |
| ASIX Electronics                 | 4         | 0.9%    |
| Qualcomm                         | 3         | 0.67%   |
| TP-Link                          | 2         | 0.45%   |
| Novatel Wireless                 | 2         | 0.45%   |
| Huawei Technologies              | 2         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Shenzhen Goodix Technology       | 1         | 0.22%   |
| Qualcomm Atheros Communications  | 1         | 0.22%   |
| OPPO Electronics                 | 1         | 0.22%   |
| Nvidia                           | 1         | 0.22%   |
| Microsoft                        | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| ICS Advent                       | 1         | 0.22%   |
| Dell                             | 1         | 0.22%   |
| BillBoard                        | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 85        | 16.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 7.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 3.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 17        | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 2.66%   |
| Intel Wi-Fi 6 AX201                                                    | 14        | 2.66%   |
| Intel Wireless 8265 / 8275                                             | 11        | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 8         | 1.52%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 8         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 8         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.14%   |
| Intel Wireless 8260                                                    | 6         | 1.14%   |
| Intel Wireless 7260                                                    | 6         | 1.14%   |
| Intel Wireless 7265                                                    | 5         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 5         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 0.95%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                        | 4         | 0.76%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 0.76%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 4         | 0.76%   |
| Intel Meteor Lake PCH CNVi WiFi                                        | 4         | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 4         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 4         | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 3         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 3         | 0.57%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.57%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 116       | 39.32%  |
| Realtek Semiconductor           | 68        | 23.05%  |
| Qualcomm Atheros                | 50        | 16.95%  |
| Broadcom                        | 26        | 8.81%   |
| MediaTek                        | 13        | 4.41%   |
| Ralink                          | 6         | 2.03%   |
| Broadcom Limited                | 5         | 1.69%   |
| Ralink Technology               | 4         | 1.36%   |
| Qualcomm                        | 3         | 1.02%   |
| TP-Link                         | 2         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.34%   |
| Dell                            | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 20        | 6.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 17        | 5.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 17        | 5.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 14        | 4.73%   |
| Intel Wi-Fi 6 AX201                                                  | 14        | 4.73%   |
| Intel Wireless 8265 / 8275                                           | 11        | 3.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 8         | 2.7%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 8         | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 8         | 2.7%    |
| Intel Wi-Fi 6 AX200                                                  | 7         | 2.36%   |
| Broadcom BCM43142 802.11b/g/n                                        | 7         | 2.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 2.03%   |
| Intel Wireless 8260                                                  | 6         | 2.03%   |
| Intel Wireless 7260                                                  | 6         | 2.03%   |
| Intel Wireless 7265                                                  | 5         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 5         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 5         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 5         | 1.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 5         | 1.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 4         | 1.35%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 4         | 1.35%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 4         | 1.35%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 4         | 1.35%   |
| Intel Meteor Lake PCH CNVi WiFi                                      | 4         | 1.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 4         | 1.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 3         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 3         | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 3         | 1.01%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.01%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 3         | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 2         | 0.68%   |
| Realtek 802.11ac NIC                                                 | 2         | 0.68%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 2         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 2         | 0.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 0.68%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 138       | 61.33%  |
| Intel                            | 35        | 15.56%  |
| Qualcomm Atheros                 | 15        | 6.67%   |
| Broadcom                         | 11        | 4.89%   |
| Samsung Electronics              | 7         | 3.11%   |
| Marvell Technology Group         | 4         | 1.78%   |
| ASIX Electronics                 | 4         | 1.78%   |
| Novatel Wireless                 | 2         | 0.89%   |
| Huawei Technologies              | 2         | 0.89%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| OPPO Electronics                 | 1         | 0.44%   |
| Nvidia                           | 1         | 0.44%   |
| Microsoft                        | 1         | 0.44%   |
| Lenovo                           | 1         | 0.44%   |
| ICS Advent                       | 1         | 0.44%   |
| Apple                            | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 85        | 37.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 39        | 17.11%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 3.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 2.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 1.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 1.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.32%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.32%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.32%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.88%   |
| Novatel Wireless USB800                                                | 2         | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.88%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller                    | 2         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.88%   |
| Intel Ethernet Connection (18) I219-LM                                 | 2         | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 2         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.88%   |
| Huawei FOA-LX9                                                         | 2         | 0.88%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.88%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet              | 1         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.44%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 1         | 0.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.44%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 56.77%  |
| Ethernet | 211       | 42.63%  |
| Modem    | 3         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 240       | 81.91%  |
| Ethernet | 53        | 18.09%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 186       | 63.92%  |
| 1     | 100       | 34.36%  |
| 0     | 5         | 1.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 59.87%  |
| Yes  | 122       | 40.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 39.61%  |
| Realtek Semiconductor           | 29        | 11.37%  |
| Qualcomm Atheros Communications | 29        | 11.37%  |
| IMC Networks                    | 29        | 11.37%  |
| Foxconn / Hon Hai               | 14        | 5.49%   |
| Apple                           | 11        | 4.31%   |
| Lite-On Technology              | 9         | 3.53%   |
| Broadcom                        | 9         | 3.53%   |
| Toshiba                         | 5         | 1.96%   |
| Dell                            | 5         | 1.96%   |
| Ralink                          | 4         | 1.57%   |
| Realtek                         | 3         | 1.18%   |
| MediaTek                        | 3         | 1.18%   |
| Hewlett-Packard                 | 2         | 0.78%   |
| Ralink Technology               | 1         | 0.39%   |
| Qcom                            | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 31        | 12.16%  |
| Intel AX201 Bluetooth                                                               | 23        | 9.02%   |
| Realtek Bluetooth Radio                                                             | 19        | 7.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 7.06%   |
| IMC Networks Bluetooth Radio                                                        | 17        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 5.49%   |
| Intel Bluetooth Device                                                              | 12        | 4.71%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 8         | 3.14%   |
| IMC Networks Bluetooth Device                                                       | 7         | 2.75%   |
| Intel AX200 Bluetooth                                                               | 6         | 2.35%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.35%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 1.96%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.57%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.57%   |
| IMC Networks Wireless_Device                                                        | 4         | 1.57%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.57%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.18%   |
| MediaTek Wireless_Device                                                            | 3         | 1.18%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 3         | 1.18%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 1.18%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.78%   |
| Lite-On Wireless_Device                                                             | 2         | 0.78%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.78%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.78%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.78%   |
| Dell Wireless 355 Bluetooth                                                         | 2         | 0.78%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.39%   |
| Toshiba Askey for Toshiba                                                           | 1         | 0.39%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.39%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.39%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.39%   |
| Ralink CSR BS8510                                                                   | 1         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 238       | 68.39%  |
| AMD                              | 51        | 14.66%  |
| Nvidia                           | 44        | 12.64%  |
| Sony                             | 2         | 0.57%   |
| Realtek Semiconductor            | 2         | 0.57%   |
| Kingston Technology              | 2         | 0.57%   |
| TTGK Technology                  | 1         | 0.29%   |
| Silicon Motion                   | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Samson Technologies              | 1         | 0.29%   |
| Nreal                            | 1         | 0.29%   |
| Jieli Technology                 | 1         | 0.29%   |
| Focusrite-Novation               | 1         | 0.29%   |
| Efun-SILICON                     | 1         | 0.29%   |
| Cooler Master                    | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 34        | 8.35%   |
| AMD Ryzen HD Audio Controller                                              | 30        | 7.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24        | 5.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 4.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 4.42%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 4.42%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 18        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 4.18%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 3.69%   |
| AMD Radeon High Definition Audio Controller                                | 14        | 3.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 2.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 2.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 2.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 2.21%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 2.21%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 1.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 1.47%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.47%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.98%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 4         | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.74%   |
| Nvidia AD107 High Definition Audio Controller                              | 3         | 0.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.74%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.49%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.49%   |
| Nvidia GA107 High Definition Audio Controller                              | 2         | 0.49%   |
| Nvidia Audio device                                                        | 2         | 0.49%   |
| Kingston Technology HyperX 7.1 Audio                                       | 2         | 0.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.49%   |
| Intel Arrow Lake cAVS                                                      | 2         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung Electronics                  | 53        | 32.32%  |
| SK hynix                             | 34        | 20.73%  |
| Micron Technology                    | 24        | 14.63%  |
| Kingston                             | 12        | 7.32%   |
| Crucial                              | 10        | 6.1%    |
| Unknown                              | 8         | 4.88%   |
| Elpida                               | 3         | 1.83%   |
| Nanya Technology                     | 2         | 1.22%   |
| A-DATA Technology                    | 2         | 1.22%   |
| Unknown                              | 2         | 1.22%   |
| Unknown (ABCD)                       | 1         | 0.61%   |
| Unknown (0x0BBA)                     | 1         | 0.61%   |
| Unknown (0x00FFFFFFFFFFFFFF)         | 1         | 0.61%   |
| Transcend                            | 1         | 0.61%   |
| Toshiba                              | 1         | 0.61%   |
| Team                                 | 1         | 0.61%   |
| Silicon Power                        | 1         | 0.61%   |
| Ramaxel Technology                   | 1         | 0.61%   |
| Patriot Memory (PDP Systems)         | 1         | 0.61%   |
| KLEVV                                | 1         | 0.61%   |
| Hikvision                            | 1         | 0.61%   |
| G.Skill                              | 1         | 0.61%   |
| Chun Well Technology Holding Limited | 1         | 0.61%   |
| ASint Technology                     | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 2.29%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.71%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.71%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 1.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 2         | 1.14%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.14%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 1.14%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.14%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.14%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 2         | 1.14%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.14%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.14%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 1.14%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 2         | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.14%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 1.14%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.14%   |
| Unknown                                                          | 2         | 1.14%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.57%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 1         | 0.57%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.57%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.57%   |
| Unknown (0x0BBA) RAM Module 8GB SODIMM DDR3 1600MT/s             | 1         | 0.57%   |
| Unknown (0x00FFFFFFFFFFFFFF) RAM Module 4GB SODIMM DDR2 667MT/s  | 1         | 0.57%   |
| Transcend RAM JM4800ASE-32G 32GB SODIMM DDR5 4800MT/s            | 1         | 0.57%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s               | 1         | 0.57%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 0.57%   |
| Team RAM Elite-1600 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 47.83%  |
| DDR3    | 45        | 32.61%  |
| LPDDR4  | 6         | 4.35%   |
| DDR5    | 6         | 4.35%   |
| LPDDR5  | 4         | 2.9%    |
| LPDDR3  | 4         | 2.9%    |
| DDR2    | 4         | 2.9%    |
| SDRAM   | 1         | 0.72%   |
| DDR     | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 117       | 84.78%  |
| Row Of Chips | 20        | 14.49%  |
| Chip         | 1         | 0.72%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 69        | 44.81%  |
| 4096  | 43        | 27.92%  |
| 16384 | 19        | 12.34%  |
| 2048  | 14        | 9.09%   |
| 32768 | 7         | 4.55%   |
| 1024  | 2         | 1.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 33        | 21.29%  |
| 1600    | 33        | 21.29%  |
| 2667    | 32        | 20.65%  |
| 1334    | 11        | 7.1%    |
| 2400    | 7         | 4.52%   |
| 2133    | 6         | 3.87%   |
| 5600    | 4         | 2.58%   |
| 4267    | 4         | 2.58%   |
| 3266    | 3         | 1.94%   |
| 1333    | 3         | 1.94%   |
| 8400    | 2         | 1.29%   |
| 4800    | 2         | 1.29%   |
| 4266    | 2         | 1.29%   |
| 1067    | 2         | 1.29%   |
| 800     | 2         | 1.29%   |
| 667     | 2         | 1.29%   |
| 7500    | 1         | 0.65%   |
| 7467    | 1         | 0.65%   |
| 6400    | 1         | 0.65%   |
| 4199    | 1         | 0.65%   |
| 1066    | 1         | 0.65%   |
| 975     | 1         | 0.65%   |
| Unknown | 1         | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Brother DCP-T300 | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 49        | 21.21%  |
| IMC Networks                           | 33        | 14.29%  |
| Microdia                               | 25        | 10.82%  |
| Bison Electronics                      | 25        | 10.82%  |
| Realtek Semiconductor                  | 14        | 6.06%   |
| Quanta                                 | 14        | 6.06%   |
| Sunplus Innovation Technology          | 12        | 5.19%   |
| Suyin                                  | 8         | 3.46%   |
| Lite-On Technology                     | 8         | 3.46%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.03%   |
| Apple                                  | 7         | 3.03%   |
| Importek                               | 5         | 2.16%   |
| Luxvisions Innotech Limited            | 4         | 1.73%   |
| Alcor Micro                            | 3         | 1.3%    |
| Sonix Technology                       | 2         | 0.87%   |
| Silicon Motion                         | 2         | 0.87%   |
| ShineTech                              | 2         | 0.87%   |
| Ricoh                                  | 2         | 0.87%   |
| OmniVision Technologies                | 2         | 0.87%   |
| Lenovo                                 | 2         | 0.87%   |
| TXD                                    | 1         | 0.43%   |
| Samsung Electronics                    | 1         | 0.43%   |
| Logitech                               | 1         | 0.43%   |
| HYGD-XH--241023                        | 1         | 0.43%   |
| DigiTech                               | 1         | 0.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 18        | 7.76%   |
| Microdia Integrated_Webcam_HD                        | 13        | 5.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 12        | 5.17%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 12        | 5.17%   |
| Bison Integrated Camera                              | 8         | 3.45%   |
| Sunplus Integrated_Webcam_HD                         | 4         | 1.72%   |
| Apple FaceTime HD Camera                             | 4         | 1.72%   |
| Lite-On HP TrueVision HD Camera                      | 3         | 1.29%   |
| IMC Networks Integrated Camera                       | 3         | 1.29%   |
| IMC Networks HD Camera                               | 3         | 1.29%   |
| Chicony HP Wide Vision HD Camera                     | 3         | 1.29%   |
| Bison SunplusIT Integrated Camera                    | 3         | 1.29%   |
| Bison Lenovo EasyCamera                              | 3         | 1.29%   |
| Bison HD Webcam                                      | 3         | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 3         | 1.29%   |
| Suyin Integrated_Webcam_HD                           | 2         | 0.86%   |
| Suyin 1.3M HD WebCam                                 | 2         | 0.86%   |
| Sunplus HD WebCam                                    | 2         | 0.86%   |
| Sonix USB2.0 FHD UVC WebCam                          | 2         | 0.86%   |
| Realtek Integrated Webcam HD                         | 2         | 0.86%   |
| Realtek Integrated Webcam                            | 2         | 0.86%   |
| Realtek HP Truevision HD integrated webcam           | 2         | 0.86%   |
| Realtek HP Truevision HD                             | 2         | 0.86%   |
| Quanta ov9734_techfront_camera                       | 2         | 0.86%   |
| Quanta HP Wide Vision HD Camera                      | 2         | 0.86%   |
| Quanta HD User Facing                                | 2         | 0.86%   |
| Quanta HD Camera                                     | 2         | 0.86%   |
| OmniVision OV2640 Webcam                             | 2         | 0.86%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 0.86%   |
| Microdia HP Integrated Webcam                        | 2         | 0.86%   |
| Microdia Dell Laptop Integrated Webcam HD            | 2         | 0.86%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.86%   |
| Lite-On TOSHIBA Web Camera - HD                      | 2         | 0.86%   |
| Importek TOSHIBA Web Camera - HD                     | 2         | 0.86%   |
| Importek Laptop Integrated Webcam                    | 2         | 0.86%   |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 0.86%   |
| Chicony Lenovo EasyCamera                            | 2         | 0.86%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 0.86%   |
| Chicony HP TrueVision HD Camera                      | 2         | 0.86%   |
| Chicony HP Truevision HD                             | 2         | 0.86%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 13        | 29.55%  |
| Shenzhen Goodix Technology | 12        | 27.27%  |
| Validity Sensors           | 8         | 18.18%  |
| Elan Microelectronics      | 6         | 13.64%  |
| Upek                       | 2         | 4.55%   |
| LighTuning Technology      | 2         | 4.55%   |
| AuthenTec                  | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 22.73%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 11.36%  |
| Elan ELAN:ARM-M4                                                           | 5         | 11.36%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 6.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.27%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.27%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 2.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.27%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.27%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.27%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.27%   |
| Elan ELAN:Fingerprint                                                      | 1         | 2.27%   |
| AuthenTec AES2810                                                          | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 55.56%  |
| Alcor Micro | 3         | 33.33%  |
| O2 Micro    | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Broadcom 5880                                                                | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 193       | 64.55%  |
| 1     | 91        | 30.43%  |
| 2     | 12        | 4.01%   |
| 3     | 2         | 0.67%   |
| 4     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 36.07%  |
| Graphics card            | 30        | 24.59%  |
| Multimedia controller    | 14        | 11.48%  |
| Net/wireless             | 12        | 9.84%   |
| Chipcard                 | 8         | 6.56%   |
| Camera                   | 4         | 3.28%   |
| Bluetooth                | 4         | 3.28%   |
| Communication controller | 3         | 2.46%   |
| Modem                    | 2         | 1.64%   |
| Storage                  | 1         | 0.82%   |

