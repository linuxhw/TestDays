Linux in Japan - Tested Hardware & Statistics (Desktops)
--------------------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

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

Total: 570

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| ASUSTek       | PRO H410M-C                 | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| MSI           | Creator X299                | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b841edf2b7](https://linux-hardware.org/?probe=b841edf2b7) | Jun 19, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| ASUSTek       | X99-A                       | [2f722cf462](https://linux-hardware.org/?probe=2f722cf462) | Jun 17, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | PRO H410M-C                 | [055ed7de1b](https://linux-hardware.org/?probe=055ed7de1b) | Jun 13, 2022 |
| Intel         | DB75EN AAG39650-400         | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| Gigabyte      | GA-MA69GM-S2H               | [a382b54934](https://linux-hardware.org/?probe=a382b54934) | Jun 11, 2022 |
| ASUSTek       | PRO H410M-C                 | [fa1a1d1431](https://linux-hardware.org/?probe=fa1a1d1431) | Jun 07, 2022 |
| MSI           | H510I PRO WIFI              | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| ASRock        | A520M-HDV                   | [a8ade4e46f](https://linux-hardware.org/?probe=a8ade4e46f) | Jun 06, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [0d24b53837](https://linux-hardware.org/?probe=0d24b53837) | Jun 02, 2022 |
| ASUSTek       | PRO H410M-C                 | [c40635b66e](https://linux-hardware.org/?probe=c40635b66e) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [386a88c2b6](https://linux-hardware.org/?probe=386a88c2b6) | May 30, 2022 |
| ASUSTek       | P5Q SE                      | [5a51cc8767](https://linux-hardware.org/?probe=5a51cc8767) | May 30, 2022 |
| ASUSTek       | VM60                        | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [ca67455f28](https://linux-hardware.org/?probe=ca67455f28) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [bcca466c5e](https://linux-hardware.org/?probe=bcca466c5e) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [b83d80f5d2](https://linux-hardware.org/?probe=b83d80f5d2) | May 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| ASUSTek       | PRO H410M-C                 | [e38c676047](https://linux-hardware.org/?probe=e38c676047) | May 26, 2022 |
| ASUSTek       | PRO H410M-C                 | [a700df310a](https://linux-hardware.org/?probe=a700df310a) | May 23, 2022 |
| Gigabyte      | Z77X-UP7                    | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| MouseCompu... | B360M-ITX                   | [bee48ca0b0](https://linux-hardware.org/?probe=bee48ca0b0) | May 18, 2022 |
| HP            | 158A                        | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | PRO H410M-C                 | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Unknown       | MSL01 Series                | [1c66319969](https://linux-hardware.org/?probe=1c66319969) | May 11, 2022 |
| MouseCompu... | X99-S01                     | [69ac1048e9](https://linux-hardware.org/?probe=69ac1048e9) | May 11, 2022 |
| Gigabyte      | G31M-S2L                    | [78b1868a67](https://linux-hardware.org/?probe=78b1868a67) | May 08, 2022 |
| ASUSTek       | PRIME B365M-A               | [a281b3c075](https://linux-hardware.org/?probe=a281b3c075) | May 07, 2022 |
| ASRock        | QC5000-ITX/WiFi             | [ec48bca283](https://linux-hardware.org/?probe=ec48bca283) | May 05, 2022 |
| HP            | 158A                        | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [5498c8b84f](https://linux-hardware.org/?probe=5498c8b84f) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| ASUSTek       | P8Z77-V                     | [b3506ef75d](https://linux-hardware.org/?probe=b3506ef75d) | Apr 29, 2022 |
| Gigabyte      | Z77X-UD3H                   | [b07e1c97aa](https://linux-hardware.org/?probe=b07e1c97aa) | Apr 29, 2022 |
| MSI           | H510I PRO WIFI              | [5e6c23c3b5](https://linux-hardware.org/?probe=5e6c23c3b5) | Apr 28, 2022 |
| MSI           | H510I PRO WIFI              | [f6df392394](https://linux-hardware.org/?probe=f6df392394) | Apr 27, 2022 |
| Dell          | 0NW73C A01                  | [430f7b0e3a](https://linux-hardware.org/?probe=430f7b0e3a) | Apr 23, 2022 |
| ASRock        | P5B-DE                      | [b9b6d17274](https://linux-hardware.org/?probe=b9b6d17274) | Apr 23, 2022 |
| Dell          | 0KV62T A01                  | [0c6e50ed20](https://linux-hardware.org/?probe=0c6e50ed20) | Apr 17, 2022 |
| Dell          | 0KV62T A01                  | [7bed7782c4](https://linux-hardware.org/?probe=7bed7782c4) | Apr 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [0ad6471ecf](https://linux-hardware.org/?probe=0ad6471ecf) | Apr 16, 2022 |
| Gigabyte      | EP45-UD3P                   | [973d2cc2f1](https://linux-hardware.org/?probe=973d2cc2f1) | Apr 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [3fade276ac](https://linux-hardware.org/?probe=3fade276ac) | Apr 13, 2022 |
| MSI           | H170A PC MATE               | [404f32fc8a](https://linux-hardware.org/?probe=404f32fc8a) | Apr 11, 2022 |
| MSI           | B350I PRO AC                | [8065d41c05](https://linux-hardware.org/?probe=8065d41c05) | Apr 10, 2022 |
| ASUSTek       | H170 PRO GAMING             | [88d231a24a](https://linux-hardware.org/?probe=88d231a24a) | Apr 08, 2022 |
| Gigabyte      | AX370-Gaming K7             | [2759f18a1f](https://linux-hardware.org/?probe=2759f18a1f) | Apr 04, 2022 |
| ASUSTek       | H170 PRO GAMING             | [f7bc6dd5a3](https://linux-hardware.org/?probe=f7bc6dd5a3) | Apr 03, 2022 |
| ASUSTek       | PB50                        | [32ab9e7da2](https://linux-hardware.org/?probe=32ab9e7da2) | Apr 02, 2022 |
| Gigabyte      | AX370-Gaming K7             | [20aac26c6d](https://linux-hardware.org/?probe=20aac26c6d) | Mar 31, 2022 |
| ASRock        | FM2A88X-ITX+                | [edf21d564c](https://linux-hardware.org/?probe=edf21d564c) | Mar 30, 2022 |
| MouseCompu... | B85H3-M4/2.0                | [3b58b2a122](https://linux-hardware.org/?probe=3b58b2a122) | Mar 30, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| ASRock        | FM2A88X-ITX+                | [dc35b742d2](https://linux-hardware.org/?probe=dc35b742d2) | Mar 26, 2022 |
| MSI           | B350I PRO AC                | [9d5ead8832](https://linux-hardware.org/?probe=9d5ead8832) | Mar 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | [5c3993ef06](https://linux-hardware.org/?probe=5c3993ef06) | Mar 14, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b170ce8fbe](https://linux-hardware.org/?probe=b170ce8fbe) | Mar 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| HP            | 18E7                        | [07d0861eff](https://linux-hardware.org/?probe=07d0861eff) | Feb 28, 2022 |
| ASRock        | H77M                        | [e49dce2077](https://linux-hardware.org/?probe=e49dce2077) | Feb 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | [ac9099b0e4](https://linux-hardware.org/?probe=ac9099b0e4) | Feb 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [9483d7b48e](https://linux-hardware.org/?probe=9483d7b48e) | Feb 21, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2c1109afb8](https://linux-hardware.org/?probe=2c1109afb8) | Feb 21, 2022 |
| ASRock        | AB350M-HDV                  | [4675d06ffb](https://linux-hardware.org/?probe=4675d06ffb) | Feb 19, 2022 |
| NEC Comput... | IH81M                       | [5e60991665](https://linux-hardware.org/?probe=5e60991665) | Feb 18, 2022 |
| Unknown       | Unknown                     | [15ae5870b9](https://linux-hardware.org/?probe=15ae5870b9) | Feb 16, 2022 |
| Unknown       | Unknown                     | [e55e0df499](https://linux-hardware.org/?probe=e55e0df499) | Feb 16, 2022 |
| ASUSTek       | M4A87TD/USB3                | [041b4e9976](https://linux-hardware.org/?probe=041b4e9976) | Feb 16, 2022 |
| ASUSTek       | P7H55-M                     | [b2414fb6fc](https://linux-hardware.org/?probe=b2414fb6fc) | Feb 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [efcb060233](https://linux-hardware.org/?probe=efcb060233) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [1ee503a497](https://linux-hardware.org/?probe=1ee503a497) | Feb 13, 2022 |
| MSI           | X570-A PRO                  | [976cefe591](https://linux-hardware.org/?probe=976cefe591) | Feb 13, 2022 |
| ASRock        | A320M-HDV R4.0              | [a5d02d3a03](https://linux-hardware.org/?probe=a5d02d3a03) | Feb 13, 2022 |
| MouseCompu... | B75H2-M2                    | [f0199da02b](https://linux-hardware.org/?probe=f0199da02b) | Feb 11, 2022 |
| ASUSTek       | M4A87TD/USB3                | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASUSTek       | P5Q                         | [bc3f44c0b9](https://linux-hardware.org/?probe=bc3f44c0b9) | Feb 10, 2022 |
| ASRock        | B550M Steel Legend          | [0c54ad1557](https://linux-hardware.org/?probe=0c54ad1557) | Feb 10, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [218f370835](https://linux-hardware.org/?probe=218f370835) | Feb 10, 2022 |
| ASRock        | H55DE3                      | [7d4fb5775f](https://linux-hardware.org/?probe=7d4fb5775f) | Feb 09, 2022 |
| ASRock        | B250M-HDV                   | [fcaddfe60e](https://linux-hardware.org/?probe=fcaddfe60e) | Feb 09, 2022 |
| MCJ           | H67H2-M4                    | [3814208f36](https://linux-hardware.org/?probe=3814208f36) | Feb 08, 2022 |
| MSI           | H510I PRO WIFI              | [b9c77d9df2](https://linux-hardware.org/?probe=b9c77d9df2) | Feb 08, 2022 |
| Dell          | 04YP6J A01                  | [61cc7bdcc2](https://linux-hardware.org/?probe=61cc7bdcc2) | Feb 06, 2022 |
| HP            | ProLiant ML110 G7           | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| ASUSTek       | P8Z77-M                     | [cb5f618a4b](https://linux-hardware.org/?probe=cb5f618a4b) | Jan 31, 2022 |
| ASUSTek       | P8Z77-M                     | [0c1b8480b6](https://linux-hardware.org/?probe=0c1b8480b6) | Jan 31, 2022 |
| Gigabyte      | GA-MA790GP-DS4H             | [ef8894e69d](https://linux-hardware.org/?probe=ef8894e69d) | Jan 28, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| ASRock        | B450M Pro4                  | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| Gigabyte      | H81M-S                      | [9418716c6b](https://linux-hardware.org/?probe=9418716c6b) | Jan 14, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [57fe150494](https://linux-hardware.org/?probe=57fe150494) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [85543358d3](https://linux-hardware.org/?probe=85543358d3) | Jan 14, 2022 |
| MSI           | H510I PRO WIFI              | [efc8b1b1ff](https://linux-hardware.org/?probe=efc8b1b1ff) | Jan 13, 2022 |
| ASUSTek       | N3150I-C                    | [ae91e3cc7b](https://linux-hardware.org/?probe=ae91e3cc7b) | Jan 13, 2022 |
| Gigabyte      | GA-970A-D3                  | [7539f3648f](https://linux-hardware.org/?probe=7539f3648f) | Jan 09, 2022 |
| ASUSTek       | P8H61-I                     | [261ea10bf8](https://linux-hardware.org/?probe=261ea10bf8) | Jan 08, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [b56f576ff8](https://linux-hardware.org/?probe=b56f576ff8) | Jan 05, 2022 |
| XFX           | nForce 780i 3-Way SLI 1     | [36da2e6d4e](https://linux-hardware.org/?probe=36da2e6d4e) | Dec 26, 2021 |
| HP            | 83EE                        | [225f3c4b8d](https://linux-hardware.org/?probe=225f3c4b8d) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [526e490544](https://linux-hardware.org/?probe=526e490544) | Dec 17, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | [7d976b30fc](https://linux-hardware.org/?probe=7d976b30fc) | Dec 17, 2021 |
| ASRock        | B550 TW                     | [83c53ad524](https://linux-hardware.org/?probe=83c53ad524) | Dec 17, 2021 |
| HP            | 8054                        | [454fd4c8c7](https://linux-hardware.org/?probe=454fd4c8c7) | Dec 13, 2021 |
| ASUSTek       | P5Q                         | [dac259cc34](https://linux-hardware.org/?probe=dac259cc34) | Dec 13, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [3e6b2c12f8](https://linux-hardware.org/?probe=3e6b2c12f8) | Dec 05, 2021 |
| MSI           | X470 GAMING PLUS            | [289027e0cf](https://linux-hardware.org/?probe=289027e0cf) | Nov 26, 2021 |
| MSI           | H510I PRO WIFI              | [1abf510439](https://linux-hardware.org/?probe=1abf510439) | Nov 24, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [2879c07a24](https://linux-hardware.org/?probe=2879c07a24) | Nov 23, 2021 |
| ASUSTek       | P8H61-I                     | [bb8c25b299](https://linux-hardware.org/?probe=bb8c25b299) | Nov 20, 2021 |
| MouseCompu... | B75M-D3V-JP                 | [161d355bcc](https://linux-hardware.org/?probe=161d355bcc) | Nov 18, 2021 |
| MouseCompu... | B360M                       | [cab585062a](https://linux-hardware.org/?probe=cab585062a) | Nov 13, 2021 |
| ASUSTek       | H97-PRO                     | [99f09523d8](https://linux-hardware.org/?probe=99f09523d8) | Nov 12, 2021 |
| ASUSTek       | H170-PRO                    | [f3a3f86928](https://linux-hardware.org/?probe=f3a3f86928) | Nov 12, 2021 |
| HP            | 3047h                       | [192742e5a6](https://linux-hardware.org/?probe=192742e5a6) | Nov 12, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| HP            | 3047h                       | [935aac64ef](https://linux-hardware.org/?probe=935aac64ef) | Nov 11, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [982fbc9995](https://linux-hardware.org/?probe=982fbc9995) | Nov 10, 2021 |
| MouseCompu... | Z490M-S01                   | [bd810f8122](https://linux-hardware.org/?probe=bd810f8122) | Nov 10, 2021 |
| Gigabyte      | B85M-HD3                    | [80a8e89f7e](https://linux-hardware.org/?probe=80a8e89f7e) | Nov 06, 2021 |
| Gigabyte      | B85M-HD3                    | [834bf06329](https://linux-hardware.org/?probe=834bf06329) | Nov 03, 2021 |
| Dell          | 0P301D A02                  | [26462404f4](https://linux-hardware.org/?probe=26462404f4) | Oct 30, 2021 |
| HP            | 3047h                       | [afa4f5c1d0](https://linux-hardware.org/?probe=afa4f5c1d0) | Oct 28, 2021 |
| HP            | 3047h                       | [d5e5504f54](https://linux-hardware.org/?probe=d5e5504f54) | Oct 28, 2021 |
| Unknown       | Unknown                     | [a0bf764d45](https://linux-hardware.org/?probe=a0bf764d45) | Oct 25, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | [1d14b9b944](https://linux-hardware.org/?probe=1d14b9b944) | Oct 24, 2021 |
| Gigabyte      | H87N-WIFI                   | [fb7beb9612](https://linux-hardware.org/?probe=fb7beb9612) | Oct 20, 2021 |
| EPSON DIRE... | ST170E                      | [dfa0ed56ab](https://linux-hardware.org/?probe=dfa0ed56ab) | Oct 18, 2021 |
| Lenovo        | 36E7 SDK0R32862 WIN 3258... | [4efe80812c](https://linux-hardware.org/?probe=4efe80812c) | Oct 16, 2021 |
| ASRock        | B450M Pro4                  | [5ed3b7e62d](https://linux-hardware.org/?probe=5ed3b7e62d) | Oct 13, 2021 |
| ASRock        | H67DE                       | [491ac17e42](https://linux-hardware.org/?probe=491ac17e42) | Oct 10, 2021 |
| ASRock        | FM2A88X-ITX+                | [f6a1aece80](https://linux-hardware.org/?probe=f6a1aece80) | Oct 10, 2021 |
| Gigabyte      | Z77X-UD5H                   | [e1543ea8f8](https://linux-hardware.org/?probe=e1543ea8f8) | Oct 09, 2021 |
| ASUSTek       | M51AC                       | [0d9722a373](https://linux-hardware.org/?probe=0d9722a373) | Oct 05, 2021 |
| ASUSTek       | B85M-G                      | [0d05812341](https://linux-hardware.org/?probe=0d05812341) | Oct 02, 2021 |
| Gigabyte      | GA-MA69GM-S2H               | [b1f14324be](https://linux-hardware.org/?probe=b1f14324be) | Sep 29, 2021 |
| ASRock        | H67DE                       | [296abe4896](https://linux-hardware.org/?probe=296abe4896) | Sep 28, 2021 |
| ASRock        | H67DE                       | [e663e151d6](https://linux-hardware.org/?probe=e663e151d6) | Sep 28, 2021 |
| MSI           | B450I GAMING PLUS AC        | [8b3dfbb8a4](https://linux-hardware.org/?probe=8b3dfbb8a4) | Sep 25, 2021 |
| Gigabyte      | Z77X-UD5H                   | [b613f0c8a9](https://linux-hardware.org/?probe=b613f0c8a9) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [2f9b27ad89](https://linux-hardware.org/?probe=2f9b27ad89) | Sep 16, 2021 |
| Gigabyte      | B75M-D2P                    | [617e5dd237](https://linux-hardware.org/?probe=617e5dd237) | Sep 08, 2021 |
| EPSON DIRE... | ST150E                      | [22d7fff01c](https://linux-hardware.org/?probe=22d7fff01c) | Aug 27, 2021 |
| EPSON DIRE... | ST150E                      | [5736465e27](https://linux-hardware.org/?probe=5736465e27) | Aug 27, 2021 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | [f26ade88cd](https://linux-hardware.org/?probe=f26ade88cd) | Aug 26, 2021 |
| Biostar       | Hi-Fi A85W                  | [ffb66dafd4](https://linux-hardware.org/?probe=ffb66dafd4) | Aug 25, 2021 |
| EPSON DIRE... | ST150E                      | [797ec7ec81](https://linux-hardware.org/?probe=797ec7ec81) | Aug 24, 2021 |
| ASRock        | B450 Steel Legend           | [8fdfffdbac](https://linux-hardware.org/?probe=8fdfffdbac) | Aug 20, 2021 |
| ASRock        | B550M Steel Legend          | [68496a4cb7](https://linux-hardware.org/?probe=68496a4cb7) | Aug 18, 2021 |
| ASRock        | N3150M                      | [932c7baf1a](https://linux-hardware.org/?probe=932c7baf1a) | Aug 17, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| MSI           | Z170A GAMING PRO CARBON     | [ab538f5af7](https://linux-hardware.org/?probe=ab538f5af7) | Aug 15, 2021 |
| ASUSTek       | SABERTOOTH X79              | [5d6732e14c](https://linux-hardware.org/?probe=5d6732e14c) | Aug 09, 2021 |
| Unknown       | Unknown                     | [5b7a8411f5](https://linux-hardware.org/?probe=5b7a8411f5) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [2f7d7bbb1d](https://linux-hardware.org/?probe=2f7d7bbb1d) | Aug 06, 2021 |
| NEC Comput... | MS-7770HH                   | [7ca677a33c](https://linux-hardware.org/?probe=7ca677a33c) | Aug 03, 2021 |
| Gigabyte      | B450M S2H                   | [0401734340](https://linux-hardware.org/?probe=0401734340) | Jul 31, 2021 |
| ASRock        | B550M Steel Legend          | [1e02007526](https://linux-hardware.org/?probe=1e02007526) | Jul 30, 2021 |
| MSI           | H510I PRO WIFI              | [e896a37f1d](https://linux-hardware.org/?probe=e896a37f1d) | Jul 29, 2021 |
| ASRock        | A300M-STX                   | [161a673775](https://linux-hardware.org/?probe=161a673775) | Jul 28, 2021 |
| ASRock        | A300M-STX                   | [264959862d](https://linux-hardware.org/?probe=264959862d) | Jul 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [20fd03515f](https://linux-hardware.org/?probe=20fd03515f) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c824226d1e](https://linux-hardware.org/?probe=c824226d1e) | Jul 26, 2021 |
| HP            | 18E7                        | [c0cddf4243](https://linux-hardware.org/?probe=c0cddf4243) | Jul 23, 2021 |
| Unknown       | XH61X000.100                | [6604251e58](https://linux-hardware.org/?probe=6604251e58) | Jul 23, 2021 |
| ASRock        | FM2A88X-ITX+                | [93a813bbba](https://linux-hardware.org/?probe=93a813bbba) | Jul 22, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [b7a612e4ec](https://linux-hardware.org/?probe=b7a612e4ec) | Jul 20, 2021 |
| HP            | 1906                        | [6cd7c6ec7f](https://linux-hardware.org/?probe=6cd7c6ec7f) | Jul 20, 2021 |
| ASRock        | 880GM-LE                    | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| ASRock        | X300M-STX                   | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| HP            | 18E7                        | [03d84525e8](https://linux-hardware.org/?probe=03d84525e8) | Jul 13, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [d6410ac1a0](https://linux-hardware.org/?probe=d6410ac1a0) | Jul 11, 2021 |
| ASUSTek       | P8Z77-V PRO                 | [1b63a19bd1](https://linux-hardware.org/?probe=1b63a19bd1) | Jul 08, 2021 |
| Unknown       | Unknown                     | [673b1c670f](https://linux-hardware.org/?probe=673b1c670f) | Jul 08, 2021 |
| Unknown       | Unknown                     | [14789c0301](https://linux-hardware.org/?probe=14789c0301) | Jul 07, 2021 |
| Gigabyte      | GA-990FXA-UD3               | [cb030b0e9f](https://linux-hardware.org/?probe=cb030b0e9f) | Jul 04, 2021 |
| Intel         | DZ77BH-55K AAG39008-400     | [04692a4293](https://linux-hardware.org/?probe=04692a4293) | Jul 02, 2021 |
| HP            | 1906                        | [95bfd2283b](https://linux-hardware.org/?probe=95bfd2283b) | Jun 29, 2021 |
| Lenovo        | ThinkCentre M57 6062A25     | [e5a404d35c](https://linux-hardware.org/?probe=e5a404d35c) | Jun 29, 2021 |
| ASUSTek       | PRIME H570-PLUS             | [be23e213b9](https://linux-hardware.org/?probe=be23e213b9) | Jun 26, 2021 |
| ASRock        | Z390 Pro4                   | [6c86be2586](https://linux-hardware.org/?probe=6c86be2586) | Jun 24, 2021 |
| MSI           | H510I PRO WIFI              | [06e8d9bce7](https://linux-hardware.org/?probe=06e8d9bce7) | Jun 23, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c2285d9014](https://linux-hardware.org/?probe=c2285d9014) | Jun 22, 2021 |
| ASRock        | X470 Master SLI             | [76096c0075](https://linux-hardware.org/?probe=76096c0075) | Jun 19, 2021 |
| MSI           | H510I PRO WIFI              | [b2c184af4f](https://linux-hardware.org/?probe=b2c184af4f) | Jun 18, 2021 |
| ASRock        | X470 Master SLI             | [03b329894a](https://linux-hardware.org/?probe=03b329894a) | Jun 18, 2021 |
| ASRock        | X570 Steel Legend           | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| ASUSTek       | M4A87TD/USB3                | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| ASUSTek       | Z170M-PLUS                  | [4c0e4ebaa4](https://linux-hardware.org/?probe=4c0e4ebaa4) | Jun 16, 2021 |
| ASUSTek       | PRIME Z370-A                | [0b50c157fe](https://linux-hardware.org/?probe=0b50c157fe) | Jun 14, 2021 |
| ASRock        | X300M-STX                   | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| MSI           | B450 GAMING PLUS MAX        | [1fe01a8a37](https://linux-hardware.org/?probe=1fe01a8a37) | Jun 05, 2021 |
| ECS           | G41T-M2                     | [3005be6650](https://linux-hardware.org/?probe=3005be6650) | Jun 04, 2021 |
| Intel         | D945GNT AAC96315-402        | [36fb4e2aba](https://linux-hardware.org/?probe=36fb4e2aba) | May 29, 2021 |
| ASRock        | FM2A88X-ITX+                | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| ASUSTek       | PRIME X299-A                | [d5cdc97c3b](https://linux-hardware.org/?probe=d5cdc97c3b) | May 13, 2021 |
| Gigabyte      | EP45-UD3R                   | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Gigabyte      | EG41MF-US2H                 | [f416a7a6b3](https://linux-hardware.org/?probe=f416a7a6b3) | May 09, 2021 |
| Gigabyte      | B75M-D3H                    | [aa1f42a8a9](https://linux-hardware.org/?probe=aa1f42a8a9) | May 08, 2021 |
| ASRock        | H310CM-HDV/M.2              | [af0ec6cab7](https://linux-hardware.org/?probe=af0ec6cab7) | May 04, 2021 |
| HP            | 3047h                       | [3de6f89fae](https://linux-hardware.org/?probe=3de6f89fae) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| ASRock        | X300M-STX                   | [0f15e44442](https://linux-hardware.org/?probe=0f15e44442) | Apr 26, 2021 |
| ASRock        | P5B-DE                      | [04084bd0ef](https://linux-hardware.org/?probe=04084bd0ef) | Apr 24, 2021 |
| ASUSTek       | N3150I-C                    | [4cfbe212a4](https://linux-hardware.org/?probe=4cfbe212a4) | Apr 22, 2021 |
| Gigabyte      | B75M-D3H                    | [af34567550](https://linux-hardware.org/?probe=af34567550) | Apr 17, 2021 |
| MSI           | MAG B550M MORTAR            | [b7991a35ba](https://linux-hardware.org/?probe=b7991a35ba) | Apr 16, 2021 |
| ASUSTek       | P5Q-EM                      | [a7ed7cc477](https://linux-hardware.org/?probe=a7ed7cc477) | Apr 14, 2021 |
| ASUSTek       | P4V800D-X                   | [c469d16946](https://linux-hardware.org/?probe=c469d16946) | Apr 09, 2021 |
| ASUSTek       | PRO H410M-C                 | [a5b2555cc2](https://linux-hardware.org/?probe=a5b2555cc2) | Apr 06, 2021 |
| ASRock        | AB350 Pro4                  | [ba17a463a7](https://linux-hardware.org/?probe=ba17a463a7) | Apr 03, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [a579757204](https://linux-hardware.org/?probe=a579757204) | Apr 03, 2021 |
| ASUSTek       | P7P55D-E                    | [52b2fb4ebb](https://linux-hardware.org/?probe=52b2fb4ebb) | Mar 22, 2021 |
| ASRock        | X300M-STX                   | [d5722fd82b](https://linux-hardware.org/?probe=d5722fd82b) | Mar 22, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | [e5ce81269b](https://linux-hardware.org/?probe=e5ce81269b) | Mar 22, 2021 |
| ASRock        | X370 Pro4                   | [6c6d145ad3](https://linux-hardware.org/?probe=6c6d145ad3) | Mar 20, 2021 |
| ASRock        | FM2A88X+ Killer             | [64164ccce2](https://linux-hardware.org/?probe=64164ccce2) | Mar 19, 2021 |
| ASRock        | X300M-STX                   | [b36b41329b](https://linux-hardware.org/?probe=b36b41329b) | Mar 14, 2021 |
| ASUSTek       | P7H55-M                     | [cff1baf251](https://linux-hardware.org/?probe=cff1baf251) | Mar 14, 2021 |
| ASRock        | FM2A88X-ITX+                | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| HP            | 212B                        | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Biostar       | Hi-Fi A88ZN                 | [72cff94e15](https://linux-hardware.org/?probe=72cff94e15) | Mar 12, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [bca1731a58](https://linux-hardware.org/?probe=bca1731a58) | Mar 08, 2021 |
| HP            | 212B                        | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| MSI           | C236A WORKSTATION           | [dc9e6c2670](https://linux-hardware.org/?probe=dc9e6c2670) | Mar 03, 2021 |
| MSI           | MEG X570 GODLIKE            | [3d2e576c95](https://linux-hardware.org/?probe=3d2e576c95) | Mar 03, 2021 |
| MSI           | B450I GAMING PLUS AC        | [aa41662477](https://linux-hardware.org/?probe=aa41662477) | Mar 02, 2021 |
| ASUSTek       | M3A78-EM                    | [c08f9a30dc](https://linux-hardware.org/?probe=c08f9a30dc) | Feb 28, 2021 |
| ASUSTek       | Rampage IV GENE             | [16cf45ce16](https://linux-hardware.org/?probe=16cf45ce16) | Feb 28, 2021 |
| Dell          | 0T1D10 A01                  | [3577c78a56](https://linux-hardware.org/?probe=3577c78a56) | Feb 27, 2021 |
| Gigabyte      | H110M-S2PH-CF               | [501d2317f9](https://linux-hardware.org/?probe=501d2317f9) | Feb 26, 2021 |
| ASUSTek       | PRIME X570-P                | [7e4e426453](https://linux-hardware.org/?probe=7e4e426453) | Feb 22, 2021 |
| Biostar       | B450GT3                     | [18e0346ed0](https://linux-hardware.org/?probe=18e0346ed0) | Feb 22, 2021 |
| MSI           | C236A WORKSTATION           | [9e2effbe63](https://linux-hardware.org/?probe=9e2effbe63) | Feb 22, 2021 |
| ASRock        | A300M-STX                   | [5c5b3ce155](https://linux-hardware.org/?probe=5c5b3ce155) | Feb 19, 2021 |
| MSI           | A78M-E35 V2                 | [173e28a6b2](https://linux-hardware.org/?probe=173e28a6b2) | Feb 15, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a2e399875d](https://linux-hardware.org/?probe=a2e399875d) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | [c364bd22bf](https://linux-hardware.org/?probe=c364bd22bf) | Feb 14, 2021 |
| Biostar       | X470NH                      | [b4ae665275](https://linux-hardware.org/?probe=b4ae665275) | Feb 13, 2021 |
| ASRock        | B75M R2.0                   | [6b1142fdaa](https://linux-hardware.org/?probe=6b1142fdaa) | Feb 13, 2021 |
| Gigabyte      | H67A-D3H-B3                 | [b384cb32dc](https://linux-hardware.org/?probe=b384cb32dc) | Feb 13, 2021 |
| MSI           | H270I GAMING PRO AC         | [dcae892f29](https://linux-hardware.org/?probe=dcae892f29) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [168dfeabe8](https://linux-hardware.org/?probe=168dfeabe8) | Feb 08, 2021 |
| ASRock        | X570 Taichi Razer Editio... | [256969ebac](https://linux-hardware.org/?probe=256969ebac) | Feb 07, 2021 |
| ASRock        | A300M-STX                   | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Biostar       | B450GT                      | [2cb5b97972](https://linux-hardware.org/?probe=2cb5b97972) | Feb 02, 2021 |
| ASRock        | B450 Pro4                   | [ebe6b1d494](https://linux-hardware.org/?probe=ebe6b1d494) | Feb 02, 2021 |
| Wistron       | J361Y                       | [347eb6b747](https://linux-hardware.org/?probe=347eb6b747) | Jan 31, 2021 |
| NEC Comput... | IS8XM                       | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| HP            | 0A54h                       | [9f8677d69a](https://linux-hardware.org/?probe=9f8677d69a) | Jan 23, 2021 |
| ASRock        | A300M-STX                   | [4f8794ed64](https://linux-hardware.org/?probe=4f8794ed64) | Jan 21, 2021 |
| HP            | 0A54h                       | [6b91501381](https://linux-hardware.org/?probe=6b91501381) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [4d2fb6eb87](https://linux-hardware.org/?probe=4d2fb6eb87) | Jan 19, 2021 |
| Acer          | Aspire XC-602 V1.0          | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| Gigabyte      | G33-DS3R                    | [490a799d8b](https://linux-hardware.org/?probe=490a799d8b) | Jan 13, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [c77878fdf4](https://linux-hardware.org/?probe=c77878fdf4) | Jan 12, 2021 |
| Gigabyte      | 970A-D3P                    | [5cea01c3c1](https://linux-hardware.org/?probe=5cea01c3c1) | Jan 12, 2021 |
| MSI           | MPG B550 GAMING PLUS        | [3b66143d43](https://linux-hardware.org/?probe=3b66143d43) | Jan 11, 2021 |
| ASUSTek       | SABERTOOTH Z77              | [293bb6fc26](https://linux-hardware.org/?probe=293bb6fc26) | Jan 10, 2021 |
| Dell          | 0R7935 A03                  | [1d936da792](https://linux-hardware.org/?probe=1d936da792) | Jan 09, 2021 |
| Acer          | Aspire XC-602 V1.0          | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| HP            | 158A                        | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d67af2066](https://linux-hardware.org/?probe=6d67af2066) | Jan 06, 2021 |
| MSI           | Creator X299                | [b66f2c1d16](https://linux-hardware.org/?probe=b66f2c1d16) | Jan 06, 2021 |
| ASRock        | J5005-ITX                   | [81bba5a535](https://linux-hardware.org/?probe=81bba5a535) | Jan 04, 2021 |
| Unknown       | Unknown                     | [34d77cfa6e](https://linux-hardware.org/?probe=34d77cfa6e) | Jan 03, 2021 |
| Unknown       | Unknown                     | [07fb95c682](https://linux-hardware.org/?probe=07fb95c682) | Jan 03, 2021 |
| Acer          | Aspire XC-602 V1.0          | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| ASRock        | H110 Pro BTC+               | [f56caad73c](https://linux-hardware.org/?probe=f56caad73c) | Jan 02, 2021 |
| ASRock        | A300M-STX                   | [bd23fb61ad](https://linux-hardware.org/?probe=bd23fb61ad) | Jan 01, 2021 |
| ASRock        | H470M-ITX/ac                | [c6ea824e48](https://linux-hardware.org/?probe=c6ea824e48) | Dec 31, 2020 |
| ASRock        | B360M-ITX/ac                | [8e0bce5edb](https://linux-hardware.org/?probe=8e0bce5edb) | Dec 30, 2020 |
| Gateway       | G33M05G1 MP                 | [460acf5c52](https://linux-hardware.org/?probe=460acf5c52) | Dec 30, 2020 |
| MSI           | FM2-A75IA-E53               | [ec03bb47a4](https://linux-hardware.org/?probe=ec03bb47a4) | Dec 28, 2020 |
| ASRock        | FM2A85X-ITX                 | [5401d7dd29](https://linux-hardware.org/?probe=5401d7dd29) | Dec 23, 2020 |
| ASRock        | B360M-ITX/ac                | [39d7373b8e](https://linux-hardware.org/?probe=39d7373b8e) | Dec 23, 2020 |
| ASUSTek       | Maximus VIII GENE           | [ca0c3d2795](https://linux-hardware.org/?probe=ca0c3d2795) | Dec 21, 2020 |
| ASUSTek       | Maximus VIII GENE           | [97e9570360](https://linux-hardware.org/?probe=97e9570360) | Dec 21, 2020 |
| HP            | 158A                        | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| FIC           | PTM33 PCB                   | [0e1437dede](https://linux-hardware.org/?probe=0e1437dede) | Dec 18, 2020 |
| Supermicro    | X9DA7/E                     | [7d84e25468](https://linux-hardware.org/?probe=7d84e25468) | Dec 14, 2020 |
| ASRock        | Z390 Pro4                   | [d988af7e73](https://linux-hardware.org/?probe=d988af7e73) | Dec 13, 2020 |
| Intel         | D945GNT AAC96315-402        | [bf27b4bfee](https://linux-hardware.org/?probe=bf27b4bfee) | Dec 12, 2020 |
| NEC Comput... | MS9666 012                  | [9cc98a743f](https://linux-hardware.org/?probe=9cc98a743f) | Dec 11, 2020 |
| Dell          | 002KVM A01                  | [bee5c78b3b](https://linux-hardware.org/?probe=bee5c78b3b) | Dec 08, 2020 |
| Gigabyte      | Z77X-UD3H                   | [772f864f4e](https://linux-hardware.org/?probe=772f864f4e) | Dec 05, 2020 |
| MSI           | H270 PC MATE                | [35866ce8fb](https://linux-hardware.org/?probe=35866ce8fb) | Dec 02, 2020 |
| ASRock        | B550 Taichi                 | [dd9ebdf6b5](https://linux-hardware.org/?probe=dd9ebdf6b5) | Dec 02, 2020 |
| MSI           | H270 PC MATE                | [3151fefb19](https://linux-hardware.org/?probe=3151fefb19) | Dec 02, 2020 |
| Gateway       | G33M05G1 MP                 | [8ec0050494](https://linux-hardware.org/?probe=8ec0050494) | Dec 01, 2020 |
| Dell          | 0NW73C A01                  | [1ddf8958ef](https://linux-hardware.org/?probe=1ddf8958ef) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | [ca9077ede2](https://linux-hardware.org/?probe=ca9077ede2) | Nov 27, 2020 |
| ASRock        | B550 Taichi                 | [047af22dea](https://linux-hardware.org/?probe=047af22dea) | Nov 27, 2020 |
| ASUSTek       | P5KPL-CM                    | [9148a1a402](https://linux-hardware.org/?probe=9148a1a402) | Nov 25, 2020 |
| ASUSTek       | P5KPL-CM                    | [054642cdd4](https://linux-hardware.org/?probe=054642cdd4) | Nov 25, 2020 |
| Dell          | 0R7935 A03                  | [92a6a98f06](https://linux-hardware.org/?probe=92a6a98f06) | Nov 23, 2020 |
| Dell          | 0R7935 A03                  | [a826e1045e](https://linux-hardware.org/?probe=a826e1045e) | Nov 22, 2020 |
| ASUSTek       | B85M-E                      | [3a74151cb6](https://linux-hardware.org/?probe=3a74151cb6) | Nov 22, 2020 |
| Gateway       | IPISB-VR                    | [9a9f3b244c](https://linux-hardware.org/?probe=9a9f3b244c) | Nov 21, 2020 |
| Gigabyte      | GA-880GM-USB3               | [8d591fed02](https://linux-hardware.org/?probe=8d591fed02) | Nov 21, 2020 |
| ASRock        | H310CM-HDV/M.2              | [da70709a86](https://linux-hardware.org/?probe=da70709a86) | Nov 20, 2020 |
| Gateway       | SX2370                      | [69a18194ba](https://linux-hardware.org/?probe=69a18194ba) | Nov 19, 2020 |
| ASRock        | B460M Pro4                  | [ac90684a5f](https://linux-hardware.org/?probe=ac90684a5f) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | [300e280e8c](https://linux-hardware.org/?probe=300e280e8c) | Nov 15, 2020 |
| NEC Comput... | G1BJN A                     | [7344b2e1a1](https://linux-hardware.org/?probe=7344b2e1a1) | Nov 12, 2020 |
| HP            | 0B4Ch D                     | [64fbbc3a2c](https://linux-hardware.org/?probe=64fbbc3a2c) | Nov 08, 2020 |
| ASRock        | H110 Pro BTC+               | [fa4cc0d2b6](https://linux-hardware.org/?probe=fa4cc0d2b6) | Nov 07, 2020 |
| HP            | 0B4Ch D                     | [595b65bc4b](https://linux-hardware.org/?probe=595b65bc4b) | Nov 07, 2020 |
| ECS           | H77H2-M4                    | [e2dc1539b4](https://linux-hardware.org/?probe=e2dc1539b4) | Nov 06, 2020 |
| ASRock        | H110 Pro BTC+               | [38482fe4b4](https://linux-hardware.org/?probe=38482fe4b4) | Nov 04, 2020 |
| NEC Comput... | IS8XM                       | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| HP            | 0AECh D                     | [84f95d0a66](https://linux-hardware.org/?probe=84f95d0a66) | Nov 04, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | [7b86aebf60](https://linux-hardware.org/?probe=7b86aebf60) | Nov 03, 2020 |
| Dell          | 0F428D A00                  | [e70707332f](https://linux-hardware.org/?probe=e70707332f) | Nov 01, 2020 |
| Dell          | 0F428D A00                  | [86139a47f6](https://linux-hardware.org/?probe=86139a47f6) | Nov 01, 2020 |
| HP            | 0B4Ch D                     | [5621053db7](https://linux-hardware.org/?probe=5621053db7) | Nov 01, 2020 |
| ASRock        | 939A785GMH/128M             | [e5b7c1b0d3](https://linux-hardware.org/?probe=e5b7c1b0d3) | Oct 30, 2020 |
| Shuttle       | FS61                        | [c8b13a3e56](https://linux-hardware.org/?probe=c8b13a3e56) | Oct 25, 2020 |
| Shuttle       | FS61                        | [0e89874393](https://linux-hardware.org/?probe=0e89874393) | Oct 25, 2020 |
| ASUSTek       | P5Q-EM                      | [2b7dc5564c](https://linux-hardware.org/?probe=2b7dc5564c) | Oct 24, 2020 |
| ASRock        | H110M-ITX                   | [c6e251789a](https://linux-hardware.org/?probe=c6e251789a) | Oct 24, 2020 |
| ASRock        | B460M Pro4                  | [40a43c769a](https://linux-hardware.org/?probe=40a43c769a) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [70b6395f2f](https://linux-hardware.org/?probe=70b6395f2f) | Oct 17, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ba5634435e](https://linux-hardware.org/?probe=ba5634435e) | Oct 17, 2020 |
| Supermicro    | C7B75                       | [34cb26f10c](https://linux-hardware.org/?probe=34cb26f10c) | Oct 14, 2020 |
| Pegatron      | IPM41G                      | [fa3b72447f](https://linux-hardware.org/?probe=fa3b72447f) | Oct 12, 2020 |
| Pegatron      | IPM41G                      | [4d26fb41ea](https://linux-hardware.org/?probe=4d26fb41ea) | Oct 12, 2020 |
| Lenovo        | MAHOBAY                     | [467a3d55ed](https://linux-hardware.org/?probe=467a3d55ed) | Oct 09, 2020 |
| ECS           | G43T-3L                     | [7cf090fb8f](https://linux-hardware.org/?probe=7cf090fb8f) | Oct 08, 2020 |
| ECS           | G43T-3L                     | [3533b87774](https://linux-hardware.org/?probe=3533b87774) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | [26497a27c8](https://linux-hardware.org/?probe=26497a27c8) | Oct 08, 2020 |
| MouseCompu... | Z370-S01                    | [969cdedc18](https://linux-hardware.org/?probe=969cdedc18) | Oct 08, 2020 |
| Unknown       | Unknown                     | [89eee20d80](https://linux-hardware.org/?probe=89eee20d80) | Oct 05, 2020 |
| ECS           | G43T-3L                     | [b97fcd2011](https://linux-hardware.org/?probe=b97fcd2011) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| MSI           | H270 PC MATE                | [3c5eb42494](https://linux-hardware.org/?probe=3c5eb42494) | Sep 30, 2020 |
| Gigabyte      | H97-D3H-CF                  | [121f0b68c0](https://linux-hardware.org/?probe=121f0b68c0) | Sep 29, 2020 |
| ASUSTek       | P8H77-V                     | [954984a1e5](https://linux-hardware.org/?probe=954984a1e5) | Sep 23, 2020 |
| MSI           | B450 TOMAHAWK               | [21822dbd0d](https://linux-hardware.org/?probe=21822dbd0d) | Sep 19, 2020 |
| MSI           | B450 TOMAHAWK               | [692295c2b0](https://linux-hardware.org/?probe=692295c2b0) | Sep 19, 2020 |
| ASUSTek       | ROG ZENITH EXTREME          | [988b8ec0f7](https://linux-hardware.org/?probe=988b8ec0f7) | Sep 14, 2020 |
| Foxconn       | A7DA-S/A7DA                 | [7974b8af2f](https://linux-hardware.org/?probe=7974b8af2f) | Sep 11, 2020 |
| HP            | 0AECh D                     | [acc13196ef](https://linux-hardware.org/?probe=acc13196ef) | Sep 11, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [e50977ee7b](https://linux-hardware.org/?probe=e50977ee7b) | Sep 11, 2020 |
| ASRock        | X79 Extreme4                | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ECS           | G31T-M                      | [5b10fa37b2](https://linux-hardware.org/?probe=5b10fa37b2) | Sep 09, 2020 |
| ASRock        | Z170 Extreme4               | [688b4a3ae6](https://linux-hardware.org/?probe=688b4a3ae6) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | [b9e6801288](https://linux-hardware.org/?probe=b9e6801288) | Sep 06, 2020 |
| Shuttle       | B10IE01                     | [176ca21f28](https://linux-hardware.org/?probe=176ca21f28) | Sep 06, 2020 |
| Gigabyte      | H67A-D3H-B3                 | [1bc05191d3](https://linux-hardware.org/?probe=1bc05191d3) | Sep 01, 2020 |
| Dell          | 0NW73C A01                  | [6d64ca0ffc](https://linux-hardware.org/?probe=6d64ca0ffc) | Aug 29, 2020 |
| Unknown       | XH61X000.100                | [1173d1c86c](https://linux-hardware.org/?probe=1173d1c86c) | Aug 16, 2020 |
| MSI           | B450M BAZOOKA PLUS          | [abd9798aa8](https://linux-hardware.org/?probe=abd9798aa8) | Aug 15, 2020 |
| Lenovo        | 30C9 SDK0J40700 WIN 3258... | [729d1212fc](https://linux-hardware.org/?probe=729d1212fc) | Aug 09, 2020 |
| Intel         | D945GNT AAC96315-402        | [58a4a2906c](https://linux-hardware.org/?probe=58a4a2906c) | Aug 09, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [cc14f627f3](https://linux-hardware.org/?probe=cc14f627f3) | Aug 07, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d76a630eb2](https://linux-hardware.org/?probe=d76a630eb2) | Aug 07, 2020 |
| Fujitsu       | D3523-Ax S26361-D3523-Ax    | [b5164ce426](https://linux-hardware.org/?probe=b5164ce426) | Aug 06, 2020 |
| Unknown       | Unknown                     | [e94665aec0](https://linux-hardware.org/?probe=e94665aec0) | Jul 31, 2020 |
| Acer          | F690GVM                     | [71f0df745c](https://linux-hardware.org/?probe=71f0df745c) | Jul 30, 2020 |
| ASRock        | H55M-GE                     | [374978dac5](https://linux-hardware.org/?probe=374978dac5) | Jul 29, 2020 |
| ASRock        | H55M-GE                     | [235e00b675](https://linux-hardware.org/?probe=235e00b675) | Jul 29, 2020 |
| Gigabyte      | Z390 AORUS MASTER-CF        | [bb8dec90c6](https://linux-hardware.org/?probe=bb8dec90c6) | Jul 27, 2020 |
| Dell          | 0Y7WYT A00                  | [efc2b837a2](https://linux-hardware.org/?probe=efc2b837a2) | Jul 26, 2020 |
| Dell          | 0WMJ54 A01                  | [0eeeb834c1](https://linux-hardware.org/?probe=0eeeb834c1) | Jul 23, 2020 |
| HP            | 158A                        | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| AOpen         | AX4SG-N 918AT10202          | [44e42d5468](https://linux-hardware.org/?probe=44e42d5468) | Jul 19, 2020 |
| ASUSTek       | M3A78-EM                    | [c21bfaa19a](https://linux-hardware.org/?probe=c21bfaa19a) | Jul 18, 2020 |
| Intel         | D510MO AAE76523-403         | [a8297ffb6c](https://linux-hardware.org/?probe=a8297ffb6c) | Jul 17, 2020 |
| Shuttle       | FG41 V20                    | [a714d062a3](https://linux-hardware.org/?probe=a714d062a3) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [faca3dbfa3](https://linux-hardware.org/?probe=faca3dbfa3) | Jul 15, 2020 |
| ASRock        | X470 Master SLI             | [efa706ee83](https://linux-hardware.org/?probe=efa706ee83) | Jul 15, 2020 |
| Lenovo        | SHARKBAY NOK                | [4f60404fb3](https://linux-hardware.org/?probe=4f60404fb3) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| HP            | 0A54h                       | [944573af57](https://linux-hardware.org/?probe=944573af57) | Jul 13, 2020 |
| HP            | 158A                        | [f5c2d58594](https://linux-hardware.org/?probe=f5c2d58594) | Jul 13, 2020 |
| HP            | 158A                        | [52e8f357cc](https://linux-hardware.org/?probe=52e8f357cc) | Jul 10, 2020 |
| Foxconn       | 2ADA                        | [004f2e3d8b](https://linux-hardware.org/?probe=004f2e3d8b) | Jul 10, 2020 |
| EPSON DIRE... | ST170E                      | [fa44f643d1](https://linux-hardware.org/?probe=fa44f643d1) | Jul 09, 2020 |
| Lenovo        | SHARKBAY NOK                | [31285675c8](https://linux-hardware.org/?probe=31285675c8) | Jul 09, 2020 |
| ASUSTek       | K8V-X SE                    | [3348cccfcf](https://linux-hardware.org/?probe=3348cccfcf) | Jul 07, 2020 |
| NEC Comput... | MS-7594VH                   | [7bb53810f4](https://linux-hardware.org/?probe=7bb53810f4) | Jul 04, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [f8d281db4b](https://linux-hardware.org/?probe=f8d281db4b) | Jul 04, 2020 |
| ASRock        | B450M Pro4                  | [96bbacdb7a](https://linux-hardware.org/?probe=96bbacdb7a) | Jul 04, 2020 |
| Dell          | 0MF252                      | [682081179d](https://linux-hardware.org/?probe=682081179d) | Jul 03, 2020 |
| MSI           | AM1I                        | [b67361f132](https://linux-hardware.org/?probe=b67361f132) | Jul 03, 2020 |
| MSI           | AM1I                        | [34352c7324](https://linux-hardware.org/?probe=34352c7324) | Jul 03, 2020 |
| Gigabyte      | Z390 UD                     | [52981221fb](https://linux-hardware.org/?probe=52981221fb) | Jul 02, 2020 |
| ASUSTek       | P8Z77-V DELUXE              | [13aec875c0](https://linux-hardware.org/?probe=13aec875c0) | Jun 28, 2020 |
| Gigabyte      | G33-DS3R                    | [ba90c2bc8a](https://linux-hardware.org/?probe=ba90c2bc8a) | Jun 28, 2020 |
| ASUSTek       | Rampage Formula             | [d6042911d7](https://linux-hardware.org/?probe=d6042911d7) | Jun 26, 2020 |
| ASUSTek       | Rampage Formula             | [0cef269aa8](https://linux-hardware.org/?probe=0cef269aa8) | Jun 26, 2020 |
| Intel         | DH61BE AAG14062-206         | [13043e1664](https://linux-hardware.org/?probe=13043e1664) | Jun 26, 2020 |
| ASRock        | Z87 Extreme4                | [78ee2fc419](https://linux-hardware.org/?probe=78ee2fc419) | Jun 24, 2020 |
| Gigabyte      | 970A-DS3P                   | [7d3ab72cf8](https://linux-hardware.org/?probe=7d3ab72cf8) | Jun 23, 2020 |
| ASUSTek       | P5B-E Plus                  | [03c7fbadbe](https://linux-hardware.org/?probe=03c7fbadbe) | Jun 22, 2020 |
| Gigabyte      | Z390 UD                     | [637edc299c](https://linux-hardware.org/?probe=637edc299c) | Jun 20, 2020 |
| Fujitsu       | FJNB04F                     | [15202a6cae](https://linux-hardware.org/?probe=15202a6cae) | Jun 19, 2020 |
| Fujitsu       | FJNB04F                     | [199eca36a2](https://linux-hardware.org/?probe=199eca36a2) | Jun 19, 2020 |
| ASRock        | B460M Pro4                  | [9b0c21ddaf](https://linux-hardware.org/?probe=9b0c21ddaf) | Jun 19, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [216109b0bf](https://linux-hardware.org/?probe=216109b0bf) | Jun 19, 2020 |
| Pegatron      | IPMSB-H61                   | [6182092aa0](https://linux-hardware.org/?probe=6182092aa0) | Jun 18, 2020 |
| ASRock        | J4105M                      | [a1620f0637](https://linux-hardware.org/?probe=a1620f0637) | Jun 18, 2020 |
| MSI           | H67MA-E45                   | [e54c477ff4](https://linux-hardware.org/?probe=e54c477ff4) | Jun 17, 2020 |
| MSI           | H67MA-E45                   | [7ec2ad02d1](https://linux-hardware.org/?probe=7ec2ad02d1) | Jun 17, 2020 |
| Gigabyte      | G33-DS3R                    | [94cd0685d0](https://linux-hardware.org/?probe=94cd0685d0) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | [c713e8fe0a](https://linux-hardware.org/?probe=c713e8fe0a) | Jun 16, 2020 |
| Dell          | 0T10XW A01                  | [24ba426f14](https://linux-hardware.org/?probe=24ba426f14) | Jun 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [a01cc45fc9](https://linux-hardware.org/?probe=a01cc45fc9) | Jun 15, 2020 |
| Gigabyte      | G33-DS3R                    | [7608803f5f](https://linux-hardware.org/?probe=7608803f5f) | Jun 14, 2020 |
| ASRock        | H67DE3                      | [7a70672456](https://linux-hardware.org/?probe=7a70672456) | Jun 13, 2020 |
| ASRock        | H67DE3                      | [cc6d5aa5c4](https://linux-hardware.org/?probe=cc6d5aa5c4) | Jun 13, 2020 |
| ASUSTek       | VM42                        | [0e8e6fd4f6](https://linux-hardware.org/?probe=0e8e6fd4f6) | Jun 13, 2020 |
| HP            | 18E7                        | [5d52f06e43](https://linux-hardware.org/?probe=5d52f06e43) | Jun 11, 2020 |
| ASRock        | X370 Gaming K4              | [75f3ae6145](https://linux-hardware.org/?probe=75f3ae6145) | Jun 10, 2020 |
| Foxconn       | A7DA-S/A7DA                 | [0811f5f8ff](https://linux-hardware.org/?probe=0811f5f8ff) | Jun 09, 2020 |
| ASUSTek       | K8V-X SE                    | [8480b7d838](https://linux-hardware.org/?probe=8480b7d838) | Jun 06, 2020 |
| HP            | 805A                        | [ff57395238](https://linux-hardware.org/?probe=ff57395238) | Jun 05, 2020 |
| Gigabyte      | GA-MA69G-S3H                | [09e6763a1e](https://linux-hardware.org/?probe=09e6763a1e) | Jun 04, 2020 |
| Dell          | 0CKCXH A04                  | [0b782c6457](https://linux-hardware.org/?probe=0b782c6457) | Jun 03, 2020 |
| HP            | 18E7                        | [98c9458523](https://linux-hardware.org/?probe=98c9458523) | Jun 02, 2020 |
| Gigabyte      | GA-MA69G-S3H                | [b67c33afab](https://linux-hardware.org/?probe=b67c33afab) | Jun 01, 2020 |
| Gateway       | IPISB-VR                    | [9fcd287a96](https://linux-hardware.org/?probe=9fcd287a96) | May 31, 2020 |
| Gateway       | IPISB-VR                    | [fbb92a7b21](https://linux-hardware.org/?probe=fbb92a7b21) | May 31, 2020 |
| MSI           | H110M GAMING                | [58c02952ac](https://linux-hardware.org/?probe=58c02952ac) | May 31, 2020 |
| ASUSTek       | H87I-PLUS                   | [f830159e63](https://linux-hardware.org/?probe=f830159e63) | May 30, 2020 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [4cdd92c012](https://linux-hardware.org/?probe=4cdd92c012) | May 29, 2020 |
| Supermicro    | X9DA7/E                     | [c1586ca94e](https://linux-hardware.org/?probe=c1586ca94e) | May 27, 2020 |
| HP            | 18E7                        | [e85c8c8c1f](https://linux-hardware.org/?probe=e85c8c8c1f) | May 27, 2020 |
| MouseCompu... | B360M                       | [33e415ae9c](https://linux-hardware.org/?probe=33e415ae9c) | May 25, 2020 |
| Onkyo         | ONKYOPC                     | [cc90a61c2f](https://linux-hardware.org/?probe=cc90a61c2f) | May 24, 2020 |
| ASUSTek       | P8H77-V LE                  | [7b5401d05e](https://linux-hardware.org/?probe=7b5401d05e) | May 22, 2020 |
| ASRock        | J5005-ITX                   | [e3f18b5738](https://linux-hardware.org/?probe=e3f18b5738) | May 21, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [ab3c4986e4](https://linux-hardware.org/?probe=ab3c4986e4) | May 21, 2020 |
| NEC Comput... | MS-7777N1                   | [5cea911946](https://linux-hardware.org/?probe=5cea911946) | May 18, 2020 |
| NEC Comput... | MS-7777N1                   | [0afcb9ba8d](https://linux-hardware.org/?probe=0afcb9ba8d) | May 17, 2020 |
| ASUSTek       | P5E                         | [67df8c58c9](https://linux-hardware.org/?probe=67df8c58c9) | May 16, 2020 |
| ASUSTek       | P6T                         | [90b5a63736](https://linux-hardware.org/?probe=90b5a63736) | May 16, 2020 |
| ASUSTek       | P5E                         | [140c3b0db8](https://linux-hardware.org/?probe=140c3b0db8) | May 11, 2020 |
| HP            | 158A                        | [5af55dbc63](https://linux-hardware.org/?probe=5af55dbc63) | May 09, 2020 |
| MSI           | MEG X570 ACE                | [dc7e369d45](https://linux-hardware.org/?probe=dc7e369d45) | May 08, 2020 |
| ASRock        | B450M Pro4                  | [01445b6224](https://linux-hardware.org/?probe=01445b6224) | May 07, 2020 |
| ASRock        | 970 Extreme3                | [5391547134](https://linux-hardware.org/?probe=5391547134) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | [a36a61fc42](https://linux-hardware.org/?probe=a36a61fc42) | May 05, 2020 |
| ASUSTek       | P8B75-M                     | [64b3255738](https://linux-hardware.org/?probe=64b3255738) | May 05, 2020 |
| Supermicro    | X9DA7/E                     | [0e1b63c36e](https://linux-hardware.org/?probe=0e1b63c36e) | May 05, 2020 |
| ASRock        | X370 Gaming K4              | [9b591e104f](https://linux-hardware.org/?probe=9b591e104f) | May 04, 2020 |
| ASUSTek       | P8B75-M                     | [38669e151b](https://linux-hardware.org/?probe=38669e151b) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | [7e39b26e35](https://linux-hardware.org/?probe=7e39b26e35) | Apr 17, 2020 |
| UNITCOM       | B85H3-M4/2.0                | [a622ca867c](https://linux-hardware.org/?probe=a622ca867c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | [a258fe9d3c](https://linux-hardware.org/?probe=a258fe9d3c) | Apr 17, 2020 |
| FIC           | PTM33 PCB                   | [5c757ca851](https://linux-hardware.org/?probe=5c757ca851) | Apr 17, 2020 |
| MouseCompu... | Z170-S01                    | [48ca5fe277](https://linux-hardware.org/?probe=48ca5fe277) | Apr 15, 2020 |
| MouseCompu... | Z170-S01                    | [9157166443](https://linux-hardware.org/?probe=9157166443) | Apr 15, 2020 |
| Gigabyte      | GA-990FXA-UD3               | [6169eb8c91](https://linux-hardware.org/?probe=6169eb8c91) | Apr 14, 2020 |
| ASRock        | H310CM-HDV/M.2              | [253ee15233](https://linux-hardware.org/?probe=253ee15233) | Apr 12, 2020 |
| MCJ           | H55M-P33                    | [cb5e96a31a](https://linux-hardware.org/?probe=cb5e96a31a) | Apr 08, 2020 |
| ASUSTek       | F1A75-V PRO                 | [abe59477d7](https://linux-hardware.org/?probe=abe59477d7) | Apr 05, 2020 |
| ASUSTek       | F1A75-V PRO                 | [41eee8b868](https://linux-hardware.org/?probe=41eee8b868) | Apr 04, 2020 |
| ASRock        | H310M-STX                   | [5fbe6e4ee6](https://linux-hardware.org/?probe=5fbe6e4ee6) | Apr 01, 2020 |
| ASRock        | H310M-STX                   | [4a58d0cf1f](https://linux-hardware.org/?probe=4a58d0cf1f) | Apr 01, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [6fc123427e](https://linux-hardware.org/?probe=6fc123427e) | Mar 21, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [ec5fdd7cf2](https://linux-hardware.org/?probe=ec5fdd7cf2) | Mar 21, 2020 |
| ASUSTek       | P5E-VM HDMI                 | [95d96a6705](https://linux-hardware.org/?probe=95d96a6705) | Mar 14, 2020 |
| ASUSTek       | P8Z77-V LX                  | [edda861710](https://linux-hardware.org/?probe=edda861710) | Mar 01, 2020 |
| ECS           | G31T-M                      | [b765a7fa7f](https://linux-hardware.org/?probe=b765a7fa7f) | Feb 11, 2020 |
| ASRock        | H87M Pro4                   | [ca641865e0](https://linux-hardware.org/?probe=ca641865e0) | Feb 06, 2020 |
| ASUSTek       | PRIME H310M-A               | [2e4119c423](https://linux-hardware.org/?probe=2e4119c423) | Jan 30, 2020 |
| Gigabyte      | Z170X-Gaming 3              | [043ccd92f3](https://linux-hardware.org/?probe=043ccd92f3) | Jan 29, 2020 |
| ASRock        | A88M-G                      | [3949599c5d](https://linux-hardware.org/?probe=3949599c5d) | Jan 28, 2020 |
| HP            | 0A54h                       | [356168fec6](https://linux-hardware.org/?probe=356168fec6) | Jan 28, 2020 |
| ASRock        | A88M-G                      | [bb36145452](https://linux-hardware.org/?probe=bb36145452) | Jan 25, 2020 |
| ASRock        | A88M-G                      | [07e625051c](https://linux-hardware.org/?probe=07e625051c) | Jan 25, 2020 |
| Gateway       | RS780                       | [09cf381b3c](https://linux-hardware.org/?probe=09cf381b3c) | Jan 25, 2020 |
| Gateway       | RS780                       | [3fe382995a](https://linux-hardware.org/?probe=3fe382995a) | Jan 13, 2020 |
| ASUSTek       | X99-A                       | [67389da431](https://linux-hardware.org/?probe=67389da431) | Jan 04, 2020 |
| Gateway       | RS780                       | [3b7741a3a0](https://linux-hardware.org/?probe=3b7741a3a0) | Jan 04, 2020 |
| ASUSTek       | X99-A                       | [8893153b1b](https://linux-hardware.org/?probe=8893153b1b) | Jan 01, 2020 |
| Gigabyte      | 965G-DS3                    | [a7a0b9ab30](https://linux-hardware.org/?probe=a7a0b9ab30) | Dec 28, 2019 |
| ASRock        | J3160DC-ITX                 | [b41206f2fd](https://linux-hardware.org/?probe=b41206f2fd) | Dec 22, 2019 |
| Fujitsu       | JIH61Y3                     | [5a7487a856](https://linux-hardware.org/?probe=5a7487a856) | Dec 21, 2019 |
| Gigabyte      | Z97X-UD3H-CF                | [a66e24484e](https://linux-hardware.org/?probe=a66e24484e) | Dec 19, 2019 |
| Wistron       | JIB65Y                      | [ed496b7bdf](https://linux-hardware.org/?probe=ed496b7bdf) | Dec 19, 2019 |
| ECS           | G31T-M                      | [7052a98f3b](https://linux-hardware.org/?probe=7052a98f3b) | Dec 19, 2019 |
| ASUSTek       | PRIME Z390-A                | [91947835b4](https://linux-hardware.org/?probe=91947835b4) | Dec 04, 2019 |
| Gigabyte      | 970A-D3P                    | [65bd7a0352](https://linux-hardware.org/?probe=65bd7a0352) | Nov 30, 2019 |
| ASRock        | H87M Pro4                   | [54341a6439](https://linux-hardware.org/?probe=54341a6439) | Nov 26, 2019 |
| MSI           | AM1I                        | [e6dcc8ef69](https://linux-hardware.org/?probe=e6dcc8ef69) | Nov 11, 2019 |
| Gigabyte      | Z390 M GAMING-CF            | [91ed990d94](https://linux-hardware.org/?probe=91ed990d94) | Oct 28, 2019 |
| NEC Comput... | MS-7594VH                   | [9ddd905922](https://linux-hardware.org/?probe=9ddd905922) | Oct 27, 2019 |
| ECS           | G31T-M                      | [21dce1ded7](https://linux-hardware.org/?probe=21dce1ded7) | Oct 26, 2019 |
| ASUSTek       | PRIME H370-A                | [7b0b66861a](https://linux-hardware.org/?probe=7b0b66861a) | Oct 12, 2019 |
| HP            | 2ADE                        | [eba5a305b7](https://linux-hardware.org/?probe=eba5a305b7) | Oct 07, 2019 |
| ASUSTek       | PRIME X299-A                | [049af64f1e](https://linux-hardware.org/?probe=049af64f1e) | Oct 04, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [9db5f37aab](https://linux-hardware.org/?probe=9db5f37aab) | Oct 03, 2019 |
| ASRock        | H77 Pro4/MVP                | [306e5b04f7](https://linux-hardware.org/?probe=306e5b04f7) | Sep 28, 2019 |
| ASRock        | Z87 Killer                  | [ee533a4daf](https://linux-hardware.org/?probe=ee533a4daf) | Sep 26, 2019 |
| ECS           | G31T-M                      | [5cefc9e8d2](https://linux-hardware.org/?probe=5cefc9e8d2) | Sep 24, 2019 |
| Gigabyte      | H81M-DS2                    | [2d44575da5](https://linux-hardware.org/?probe=2d44575da5) | Sep 23, 2019 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [f9ce29fec6](https://linux-hardware.org/?probe=f9ce29fec6) | Sep 19, 2019 |
| ASUSTek       | PRIME Z390-A                | [a9d1c2f51c](https://linux-hardware.org/?probe=a9d1c2f51c) | Sep 18, 2019 |
| ASUSTek       | PRIME Z390-A                | [a6ed7aa983](https://linux-hardware.org/?probe=a6ed7aa983) | Sep 18, 2019 |
| ASUSTek       | M4A78-VM                    | [fc5bd8749b](https://linux-hardware.org/?probe=fc5bd8749b) | Sep 17, 2019 |
| ASRock        | Z87 Killer                  | [3918b7d23a](https://linux-hardware.org/?probe=3918b7d23a) | Sep 14, 2019 |
| ECS           | A75F-M2                     | [f891e8f1d5](https://linux-hardware.org/?probe=f891e8f1d5) | Sep 06, 2019 |
| ASRock        | Z87 Killer                  | [a1d5416305](https://linux-hardware.org/?probe=a1d5416305) | Sep 01, 2019 |
| ECS           | G31T-M                      | [78a1016ee6](https://linux-hardware.org/?probe=78a1016ee6) | Aug 30, 2019 |
| ASUSTek       | PRIME X299-A                | [4ad9989703](https://linux-hardware.org/?probe=4ad9989703) | Aug 28, 2019 |
| ASRock        | Z87 Killer                  | [16e84b9fb7](https://linux-hardware.org/?probe=16e84b9fb7) | Aug 24, 2019 |
| ASUSTek       | GL12CP                      | [0b7ad9054f](https://linux-hardware.org/?probe=0b7ad9054f) | Aug 19, 2019 |
| ASUSTek       | PRIME X299-A                | [1f914d8603](https://linux-hardware.org/?probe=1f914d8603) | Aug 15, 2019 |
| Fujitsu       | JIH61Y3                     | [0bdef2ed89](https://linux-hardware.org/?probe=0bdef2ed89) | Aug 15, 2019 |
| ASUSTek       | GL12CP                      | [314f1278b8](https://linux-hardware.org/?probe=314f1278b8) | Aug 13, 2019 |
| ASUSTek       | GL12CP                      | [7e8a4409ab](https://linux-hardware.org/?probe=7e8a4409ab) | Aug 13, 2019 |
| NEC Comput... | MS9666 012                  | [e0ccec3cb3](https://linux-hardware.org/?probe=e0ccec3cb3) | Aug 08, 2019 |
| HP            | 158B                        | [f588fb7831](https://linux-hardware.org/?probe=f588fb7831) | Aug 05, 2019 |
| Gigabyte      | G41M-Combo                  | [7a7a55bb9f](https://linux-hardware.org/?probe=7a7a55bb9f) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | [63f518652d](https://linux-hardware.org/?probe=63f518652d) | Aug 01, 2019 |
| ASUSTek       | P5SD2-VM                    | [2985c7f780](https://linux-hardware.org/?probe=2985c7f780) | Jul 27, 2019 |
| HP            | 1589                        | [2eeb0dcbef](https://linux-hardware.org/?probe=2eeb0dcbef) | Jul 18, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8d70085277](https://linux-hardware.org/?probe=8d70085277) | Jul 16, 2019 |
| MCJ           | CO.,LTD                     | [0cca59b833](https://linux-hardware.org/?probe=0cca59b833) | Jul 13, 2019 |
| MCJ           | CO.,LTD                     | [262f82967e](https://linux-hardware.org/?probe=262f82967e) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [c77e3987e8](https://linux-hardware.org/?probe=c77e3987e8) | Jul 12, 2019 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [03894447bb](https://linux-hardware.org/?probe=03894447bb) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | [ef1765e325](https://linux-hardware.org/?probe=ef1765e325) | Jul 12, 2019 |
| Fujitsu       | JIH61Y3                     | [f457a91893](https://linux-hardware.org/?probe=f457a91893) | Jul 12, 2019 |
| ASUSTek       | M4A88T-I DELUXE             | [7011e7619b](https://linux-hardware.org/?probe=7011e7619b) | Jul 04, 2019 |
| ASRock        | H77 Pro4/MVP                | [3ac82eca46](https://linux-hardware.org/?probe=3ac82eca46) | Jun 29, 2019 |
| NEC Comput... | MS-7594VH                   | [e61c26fd4c](https://linux-hardware.org/?probe=e61c26fd4c) | Jun 25, 2019 |
| ASUSTek       | X99-E-10G WS                | [f7605b7f95](https://linux-hardware.org/?probe=f7605b7f95) | Jun 18, 2019 |
| ASUSTek       | H110M-A/M.2                 | [6e8096d588](https://linux-hardware.org/?probe=6e8096d588) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [4cf90e52e8](https://linux-hardware.org/?probe=4cf90e52e8) | May 28, 2019 |
| Biostar       | P4M900-M7 FE Ver:1.0        | [279621d15c](https://linux-hardware.org/?probe=279621d15c) | May 20, 2019 |
| Dell          | 0XPDFK A01                  | [b545ad5544](https://linux-hardware.org/?probe=b545ad5544) | May 10, 2019 |
| Dell          | 0XPDFK A01                  | [d4c3d2990b](https://linux-hardware.org/?probe=d4c3d2990b) | May 09, 2019 |
| Onkyo         | ONKYOPC 0A                  | [d298e61165](https://linux-hardware.org/?probe=d298e61165) | May 04, 2019 |
| ASRock        | X370 Gaming K4              | [f3883ffe3f](https://linux-hardware.org/?probe=f3883ffe3f) | May 03, 2019 |
| ASUSTek       | PRIME H370M-PLUS            | [d92d4f0666](https://linux-hardware.org/?probe=d92d4f0666) | May 02, 2019 |
| HP            | 3398                        | [915f8eec67](https://linux-hardware.org/?probe=915f8eec67) | Apr 30, 2019 |
| Gigabyte      | A320M-HD2-CF                | [740fc92339](https://linux-hardware.org/?probe=740fc92339) | Apr 26, 2019 |
| Dell          | 09KPNV A00                  | [ac628634d2](https://linux-hardware.org/?probe=ac628634d2) | Mar 30, 2019 |
| MCJ           | H55-S01                     | [24d0907973](https://linux-hardware.org/?probe=24d0907973) | Mar 21, 2019 |
| Dell          | 0J584C A00                  | [7f79951f35](https://linux-hardware.org/?probe=7f79951f35) | Mar 10, 2019 |
| Gigabyte      | M61P-S3                     | [b6505655d3](https://linux-hardware.org/?probe=b6505655d3) | Feb 22, 2019 |
| Gigabyte      | M61P-S3                     | [d1f1dd8c96](https://linux-hardware.org/?probe=d1f1dd8c96) | Feb 19, 2019 |
| ASUSTek       | M3A78-EM                    | [0120bc4801](https://linux-hardware.org/?probe=0120bc4801) | Feb 04, 2019 |
| Pegatron      | 2AB5                        | [c87217d642](https://linux-hardware.org/?probe=c87217d642) | Feb 03, 2019 |
| Intel         | DG965RY AAD41691-205        | [15252dcf05](https://linux-hardware.org/?probe=15252dcf05) | Jan 20, 2019 |
| MCJ           | H55-S01                     | [f694a85c3b](https://linux-hardware.org/?probe=f694a85c3b) | Jan 20, 2019 |
| MCJ           | H55-S01                     | [b72a8388df](https://linux-hardware.org/?probe=b72a8388df) | Jan 20, 2019 |
| Gigabyte      | B450 AORUS M                | [7d4741d740](https://linux-hardware.org/?probe=7d4741d740) | Nov 17, 2018 |
| MSI           | P67A-S40                    | [4104f2eabe](https://linux-hardware.org/?probe=4104f2eabe) | Nov 12, 2018 |
| Dell          | 0WJ771                      | [1a6e39d574](https://linux-hardware.org/?probe=1a6e39d574) | Dec 07, 2017 |
| ASRock        | 990FX Extreme4              | [b1702d4023](https://linux-hardware.org/?probe=b1702d4023) | Apr 21, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Ubuntu 20.04        | 98       | 24.56%  |
| Ubuntu 18.04        | 55       | 13.78%  |
| OpenMandriva 4.2    | 17       | 4.26%   |
| Xubuntu 20.04       | 15       | 3.76%   |
| OpenMandriva 4.3    | 14       | 3.51%   |
| Xubuntu 18.04       | 10       | 2.51%   |
| Ubuntu 21.10        | 9        | 2.26%   |
| Ubuntu 22.04        | 8        | 2.01%   |
| Ubuntu 20.10        | 8        | 2.01%   |
| Ubuntu 19.04        | 7        | 1.75%   |
| Debian 11           | 7        | 1.75%   |
| BlackPanther 18.1   | 7        | 1.75%   |
| Ubuntu 21.04        | 6        | 1.5%    |
| Fedora 34           | 6        | 1.5%    |
| Pop!_OS 21.04       | 5        | 1.25%   |
| Linux Mint 20.3     | 5        | 1.25%   |
| Linux Mint 19.3     | 5        | 1.25%   |
| Arch                | 5        | 1.25%   |
| Ubuntu 16.04        | 4        | 1%      |
| ROSA R11            | 4        | 1%      |
| OpenMandriva 4.50   | 4        | 1%      |
| Lubuntu 20.04       | 4        | 1%      |
| Linux Mint 20       | 4        | 1%      |
| KDE neon 20.04      | 4        | 1%      |
| Fedora 33           | 4        | 1%      |
| Fedora 32           | 4        | 1%      |
| Zorin 16            | 3        | 0.75%   |
| Zorin 15            | 3        | 0.75%   |
| Ubuntu 19.10        | 3        | 0.75%   |
| Pop!_OS 22.04       | 3        | 0.75%   |
| Manjaro             | 3        | 0.75%   |
| Kubuntu 20.04       | 3        | 0.75%   |
| Gentoo 2.7          | 3        | 0.75%   |
| Fedora 30           | 3        | 0.75%   |
| Elementary 6.1      | 3        | 0.75%   |
| Arch Rolling        | 3        | 0.75%   |
| Ubuntu MATE 20.04   | 2        | 0.5%    |
| Ubuntu 18.10        | 2        | 0.5%    |
| ROSA R11.1          | 2        | 0.5%    |
| ROSA R10            | 2        | 0.5%    |
| Pop!_OS 21.10       | 2        | 0.5%    |
| Pop!_OS 20.04       | 2        | 0.5%    |
| openSUSE Leap-15.3  | 2        | 0.5%    |
| openSUSE Leap-15.2  | 2        | 0.5%    |
| Fedora 36           | 2        | 0.5%    |
| Fedora 31           | 2        | 0.5%    |
| Debian Unstable     | 2        | 0.5%    |
| Debian 10           | 2        | 0.5%    |
| Zorin 12            | 1        | 0.25%   |
| Xubuntu 20.10       | 1        | 0.25%   |
| Ubuntu Budgie 21.04 | 1        | 0.25%   |
| Ubuntu Budgie 20.04 | 1        | 0.25%   |
| Ubuntu              | 1        | 0.25%   |
| Slackware 15.0      | 1        | 0.25%   |
| Slackware 14.2+     | 1        | 0.25%   |
| ROSA R9             | 1        | 0.25%   |
| Rocky Linux 8.5     | 1        | 0.25%   |
| Manjaro 21.2.0      | 1        | 0.25%   |
| Manjaro 21.1.0      | 1        | 0.25%   |
| Manjaro 20.1.1      | 1        | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 191      | 51.21%  |
| OpenMandriva  | 34       | 9.12%   |
| Xubuntu       | 23       | 6.17%   |
| Linux Mint    | 16       | 4.29%   |
| Fedora        | 16       | 4.29%   |
| Debian        | 12       | 3.22%   |
| Pop!_OS       | 11       | 2.95%   |
| ROSA          | 8        | 2.14%   |
| Arch          | 8        | 2.14%   |
| Zorin         | 7        | 1.88%   |
| BlackPanther  | 7        | 1.88%   |
| Manjaro       | 6        | 1.61%   |
| Lubuntu       | 4        | 1.07%   |
| KDE neon      | 4        | 1.07%   |
| openSUSE      | 3        | 0.8%    |
| Kubuntu       | 3        | 0.8%    |
| Gentoo        | 3        | 0.8%    |
| Elementary    | 3        | 0.8%    |
| Ubuntu MATE   | 2        | 0.54%   |
| Slackware     | 2        | 0.54%   |
| Endless       | 2        | 0.54%   |
| Clear Linux   | 2        | 0.54%   |
| Ubuntu Budgie | 1        | 0.27%   |
| Rocky Linux   | 1        | 0.27%   |
| Kali          | 1        | 0.27%   |
| CentOS        | 1        | 0.27%   |
| Artix         | 1        | 0.27%   |
| ArcoLinux     | 1        | 0.27%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 16       | 3.6%    |
| 5.16.7-desktop-1omv4003  | 14       | 3.15%   |
| 5.4.0-42-generic         | 10       | 2.25%   |
| 5.4.0-40-generic         | 9        | 2.02%   |
| 5.4.0-33-generic         | 9        | 2.02%   |
| 5.4.0-58-generic         | 8        | 1.8%    |
| 5.4.0-37-generic         | 8        | 1.8%    |
| 5.4.0-52-generic         | 7        | 1.57%   |
| 4.18.16-desktop-1bP      | 7        | 1.57%   |
| 5.4.0-54-generic         | 6        | 1.35%   |
| 5.4.0-29-generic         | 5        | 1.12%   |
| 5.13.0-40-generic        | 5        | 1.12%   |
| 5.13.0-30-generic        | 5        | 1.12%   |
| 5.11.0-38-generic        | 5        | 1.12%   |
| 5.4.0-66-generic         | 4        | 0.9%    |
| 5.13.0-39-generic        | 4        | 0.9%    |
| 5.0.0-29-generic         | 4        | 0.9%    |
| 4.15.0-72-generic        | 4        | 0.9%    |
| 4.15.0-48-generic        | 4        | 0.9%    |
| 5.8.0-59-generic         | 3        | 0.67%   |
| 5.8.0-55-generic         | 3        | 0.67%   |
| 5.8.0-50-generic         | 3        | 0.67%   |
| 5.8.0-43-generic         | 3        | 0.67%   |
| 5.4.0-99-generic         | 3        | 0.67%   |
| 5.4.0-67-generic         | 3        | 0.67%   |
| 5.4.0-39-generic         | 3        | 0.67%   |
| 5.4.0-31-generic         | 3        | 0.67%   |
| 5.3.0-28-generic         | 3        | 0.67%   |
| 5.3.0-26-generic         | 3        | 0.67%   |
| 5.13.0-28-generic        | 3        | 0.67%   |
| 5.12.4-desktop-1omv4050  | 3        | 0.67%   |
| 5.11.0-7620-generic      | 3        | 0.67%   |
| 5.11.0-41-generic        | 3        | 0.67%   |
| 5.11.0-37-generic        | 3        | 0.67%   |
| 5.11.0-18-generic        | 3        | 0.67%   |
| 5.10.0-8-amd64           | 3        | 0.67%   |
| 4.15.0-54-generic        | 3        | 0.67%   |
| 5.8.0-49-generic         | 2        | 0.45%   |
| 5.8.0-48-generic         | 2        | 0.45%   |
| 5.8.0-36-generic         | 2        | 0.45%   |
| 5.4.0-96-generic         | 2        | 0.45%   |
| 5.4.0-92-generic         | 2        | 0.45%   |
| 5.4.0-72-generic         | 2        | 0.45%   |
| 5.4.0-56-generic         | 2        | 0.45%   |
| 5.4.0-52-lowlatency      | 2        | 0.45%   |
| 5.4.0-51-generic         | 2        | 0.45%   |
| 5.4.0-48-generic         | 2        | 0.45%   |
| 5.4.0-47-generic         | 2        | 0.45%   |
| 5.4.0-40-lowlatency      | 2        | 0.45%   |
| 5.4.0-26-generic         | 2        | 0.45%   |
| 5.4.0-110-generic        | 2        | 0.45%   |
| 5.4.0-109-generic        | 2        | 0.45%   |
| 5.3.18-lp152.63-default  | 2        | 0.45%   |
| 5.3.0-51-generic         | 2        | 0.45%   |
| 5.3.0-46-generic         | 2        | 0.45%   |
| 5.15.15-76051515-generic | 2        | 0.45%   |
| 5.15.0-35-generic        | 2        | 0.45%   |
| 5.15.0-33-generic        | 2        | 0.45%   |
| 5.15.0-30-generic        | 2        | 0.45%   |
| 5.13.0-22-generic        | 2        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 108      | 26.34%  |
| 4.15.0  | 47       | 11.46%  |
| 5.8.0   | 27       | 6.59%   |
| 5.13.0  | 27       | 6.59%   |
| 5.11.0  | 27       | 6.59%   |
| 5.10.14 | 17       | 4.15%   |
| 5.3.0   | 16       | 3.9%    |
| 5.0.0   | 16       | 3.9%    |
| 5.16.7  | 14       | 3.41%   |
| 5.15.0  | 9        | 2.2%    |
| 5.10.0  | 9        | 2.2%    |
| 4.18.16 | 7        | 1.71%   |
| 4.18.0  | 5        | 1.22%   |
| 5.3.18  | 3        | 0.73%   |
| 5.12.4  | 3        | 0.73%   |
| 4.4.0   | 3        | 0.73%   |
| 5.9.0   | 2        | 0.49%   |
| 5.7.9   | 2        | 0.49%   |
| 5.15.2  | 2        | 0.49%   |
| 5.15.15 | 2        | 0.49%   |
| 4.9.60  | 2        | 0.49%   |
| 4.19.0  | 2        | 0.49%   |
| 5.9.8   | 1        | 0.24%   |
| 5.9.15  | 1        | 0.24%   |
| 5.9.14  | 1        | 0.24%   |
| 5.9.12  | 1        | 0.24%   |
| 5.9.11  | 1        | 0.24%   |
| 5.8.5   | 1        | 0.24%   |
| 5.8.16  | 1        | 0.24%   |
| 5.8.15  | 1        | 0.24%   |
| 5.8.11  | 1        | 0.24%   |
| 5.7.6   | 1        | 0.24%   |
| 5.7.2   | 1        | 0.24%   |
| 5.6.7   | 1        | 0.24%   |
| 5.6.18  | 1        | 0.24%   |
| 5.6.13  | 1        | 0.24%   |
| 5.6.0   | 1        | 0.24%   |
| 5.5.6   | 1        | 0.24%   |
| 5.5.2   | 1        | 0.24%   |
| 5.5.15  | 1        | 0.24%   |
| 5.4.32  | 1        | 0.24%   |
| 5.2.6   | 1        | 0.24%   |
| 5.2.16  | 1        | 0.24%   |
| 5.2.11  | 1        | 0.24%   |
| 5.18.5  | 1        | 0.24%   |
| 5.18.0  | 1        | 0.24%   |
| 5.17.5  | 1        | 0.24%   |
| 5.17.15 | 1        | 0.24%   |
| 5.17.13 | 1        | 0.24%   |
| 5.17.11 | 1        | 0.24%   |
| 5.16.19 | 1        | 0.24%   |
| 5.16.13 | 1        | 0.24%   |
| 5.15.5  | 1        | 0.24%   |
| 5.15.14 | 1        | 0.24%   |
| 5.15.12 | 1        | 0.24%   |
| 5.15.11 | 1        | 0.24%   |
| 5.14.7  | 1        | 0.24%   |
| 5.14.16 | 1        | 0.24%   |
| 5.13.9  | 1        | 0.24%   |
| 5.13.6  | 1        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 109      | 26.91%  |
| 4.15    | 47       | 11.6%   |
| 5.13    | 32       | 7.9%    |
| 5.10    | 32       | 7.9%    |
| 5.8     | 31       | 7.65%   |
| 5.11    | 29       | 7.16%   |
| 5.3     | 19       | 4.69%   |
| 5.0     | 18       | 4.44%   |
| 5.16    | 16       | 3.95%   |
| 5.15    | 16       | 3.95%   |
| 4.18    | 12       | 2.96%   |
| 5.9     | 7        | 1.73%   |
| 5.12    | 6        | 1.48%   |
| 5.7     | 4        | 0.99%   |
| 5.6     | 4        | 0.99%   |
| 5.17    | 4        | 0.99%   |
| 5.5     | 3        | 0.74%   |
| 5.2     | 3        | 0.74%   |
| 4.9     | 3        | 0.74%   |
| 4.4     | 3        | 0.74%   |
| 4.19    | 3        | 0.74%   |
| 5.14    | 2        | 0.49%   |
| 5.18    | 1        | 0.25%   |
| 3.10    | 1        | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 356      | 97.27%  |
| i686   | 10       | 2.73%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 180      | 47.87%  |
| KDE5                     | 56       | 14.89%  |
| Unknown                  | 55       | 14.63%  |
| XFCE                     | 29       | 7.71%   |
| X-Cinnamon               | 16       | 4.26%   |
| KDE                      | 9        | 2.39%   |
| MATE                     | 5        | 1.33%   |
| LXQt                     | 5        | 1.33%   |
| KDE4                     | 4        | 1.06%   |
| Pantheon                 | 3        | 0.8%    |
| Budgie                   | 3        | 0.8%    |
| LXDE                     | 2        | 0.53%   |
| Cinnamon                 | 2        | 0.53%   |
| XSession                 | 1        | 0.27%   |
| Unity                    | 1        | 0.27%   |
| Openbox                  | 1        | 0.27%   |
| GNOME Classic            | 1        | 0.27%   |
| Deepin                   | 1        | 0.27%   |
| awesome                  | 1        | 0.27%   |
| /usr/bin/openbox-session | 1        | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 298      | 79.89%  |
| Unknown | 35       | 9.38%   |
| Wayland | 31       | 8.31%   |
| Tty     | 9        | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 232      | 61.05%  |
| SDDM    | 55       | 14.47%  |
| GDM3    | 32       | 8.42%   |
| GDM     | 28       | 7.37%   |
| LightDM | 16       | 4.21%   |
| TDM     | 8        | 2.11%   |
| KDM     | 3        | 0.79%   |
| NODM    | 2        | 0.53%   |
| LXDM    | 2        | 0.53%   |
| XDM     | 1        | 0.26%   |
| SLiM    | 1        | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| ja_JP       | 200      | 54.2%   |
| en_US       | 80       | 21.68%  |
| Unknown     | 60       | 16.26%  |
| pt_BR       | 12       | 3.25%   |
| zh_CN       | 5        | 1.36%   |
| en_GB       | 4        | 1.08%   |
| C           | 2        | 0.54%   |
| sk_SK       | 1        | 0.27%   |
| ja_JP.utf-8 | 1        | 0.27%   |
| it_IT       | 1        | 0.27%   |
| fr_FR       | 1        | 0.27%   |
| en_AU       | 1        | 0.27%   |
| en_AG       | 1        | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 242      | 65.41%  |
| EFI  | 128      | 34.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 302      | 81.84%  |
| Overlay | 32       | 8.67%   |
| Btrfs   | 13       | 3.52%   |
| Unknown | 12       | 3.25%   |
| Xfs     | 5        | 1.36%   |
| Zfs     | 4        | 1.08%   |
| Ext3    | 1        | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 256      | 70.33%  |
| GPT     | 80       | 21.98%  |
| MBR     | 28       | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 287      | 76.74%  |
| Yes       | 87       | 23.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 245      | 65.33%  |
| Yes       | 130      | 34.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 88       | 24.24%  |
| ASRock              | 72       | 19.83%  |
| Gigabyte Technology | 46       | 12.67%  |
| MSI                 | 31       | 8.54%   |
| Hewlett-Packard     | 20       | 5.51%   |
| Dell                | 18       | 4.96%   |
| MouseComputer       | 10       | 2.75%   |
| NEC Computers       | 8        | 2.2%    |
| Intel               | 7        | 1.93%   |
| ECS                 | 7        | 1.93%   |
| Lenovo              | 6        | 1.65%   |
| Biostar             | 6        | 1.65%   |
| Unknown             | 6        | 1.65%   |
| Fujitsu             | 5        | 1.38%   |
| MCJ                 | 4        | 1.1%    |
| Gateway             | 4        | 1.1%    |
| Shuttle             | 3        | 0.83%   |
| Pegatron            | 3        | 0.83%   |
| Foxconn             | 3        | 0.83%   |
| Wistron             | 2        | 0.55%   |
| Supermicro          | 2        | 0.55%   |
| Onkyo               | 2        | 0.55%   |
| EPSON DIRECT        | 2        | 0.55%   |
| Acer                | 2        | 0.55%   |
| XFX                 | 1        | 0.28%   |
| UNITCOM             | 1        | 0.28%   |
| IBM                 | 1        | 0.28%   |
| FIC                 | 1        | 0.28%   |
| Apple               | 1        | 0.28%   |
| AOpen               | 1        | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 9        | 2.48%   |
| Unknown                                    | 6        | 1.65%   |
| ASRock Z87 Killer                          | 4        | 1.1%    |
| ASRock B450M Pro4                          | 4        | 1.1%    |
| MSI MS-7A40                                | 3        | 0.83%   |
| ECS G31T-M                                 | 3        | 0.83%   |
| Dell Precision WorkStation T3500           | 3        | 0.83%   |
| ASRock Prime Series                        | 3        | 0.83%   |
| Onkyo ONKYOPC                              | 2        | 0.55%   |
| NEC Computers Express5800/S70 [N8100-9021] | 2        | 0.55%   |
| MSI MS-7D16                                | 2        | 0.55%   |
| MSI MS-7C94                                | 2        | 0.55%   |
| MSI MS-7C37                                | 2        | 0.55%   |
| MSI MS-7C02                                | 2        | 0.55%   |
| MSI MS-7A72                                | 2        | 0.55%   |
| MSI MS-7865                                | 2        | 0.55%   |
| MouseComputer B360M                        | 2        | 0.55%   |
| HP Z620 Workstation                        | 2        | 0.55%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.55%   |
| HP Compaq dc7700p Small Form Factor        | 2        | 0.55%   |
| Gigabyte Z77X-UD3H                         | 2        | 0.55%   |
| Gigabyte Z170X-Gaming 3                    | 2        | 0.55%   |
| Gigabyte H67A-D3H-B3                       | 2        | 0.55%   |
| Gigabyte GA-MA69G-S3H                      | 2        | 0.55%   |
| Gigabyte G33-DS3R                          | 2        | 0.55%   |
| Gigabyte 970A-D3P                          | 2        | 0.55%   |
| Dell OptiPlex 3020                         | 2        | 0.55%   |
| ASUS TUF Gaming B550M-PLUS                 | 2        | 0.55%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 0.55%   |
| ASUS PRO H410M-C                           | 2        | 0.55%   |
| ASUS PRIME X299-A                          | 2        | 0.55%   |
| ASUS PRIME H370M-PLUS                      | 2        | 0.55%   |
| ASUS PRIME H270M-PLUS                      | 2        | 0.55%   |
| ASUS P8Z77-V PRO                           | 2        | 0.55%   |
| ASUS P7H55-M                               | 2        | 0.55%   |
| ASUS M3A78-EM                              | 2        | 0.55%   |
| ASRock Z390 Pro4                           | 2        | 0.55%   |
| ASRock X470 Master SLI                     | 2        | 0.55%   |
| ASRock X370 Gaming K4                      | 2        | 0.55%   |
| ASRock J5005-ITX                           | 2        | 0.55%   |
| ASRock H310CM-HDV/M.2                      | 2        | 0.55%   |
| ASRock H110 Pro BTC+                       | 2        | 0.55%   |
| ASRock FM2A88X-ITX+                        | 2        | 0.55%   |
| ASRock B460M Pro4                          | 2        | 0.55%   |
| ASRock B450 Gaming-ITX/ac                  | 2        | 0.55%   |
| ASRock A300M-STX                           | 2        | 0.55%   |
| XFX nForce 780i 3-Way SLI                  | 1        | 0.28%   |
| Wistron FMVXDBTL2Z                         | 1        | 0.28%   |
| Wistron FMVCE50M7                          | 1        | 0.28%   |
| UNITCOM B85H3-M4                           | 1        | 0.28%   |
| Supermicro X9DA7/E                         | 1        | 0.28%   |
| Supermicro C7B75                           | 1        | 0.28%   |
| Shuttle XS35                               | 1        | 0.28%   |
| Shuttle SG41                               | 1        | 0.28%   |
| Shuttle DS61                               | 1        | 0.28%   |
| Pegatron Prime Series                      | 1        | 0.28%   |
| Pegatron KOUZIRODT                         | 1        | 0.28%   |
| Pegatron h8-1280jp                         | 1        | 0.28%   |
| NEC Computers PC-VL590CD                   | 1        | 0.28%   |
| NEC Computers PC-VL300TG                   | 1        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Desktops | Percent |
|---------------------------|----------|---------|
| ASUS PRIME                | 13       | 3.58%   |
| ASUS ROG                  | 9        | 2.48%   |
| ASUS All                  | 9        | 2.48%   |
| ASUS TUF                  | 8        | 2.2%    |
| HP Compaq                 | 6        | 1.65%   |
| Dell OptiPlex             | 6        | 1.65%   |
| Unknown                   | 6        | 1.65%   |
| Dell Vostro               | 5        | 1.38%   |
| ASUS P8Z77-V              | 5        | 1.38%   |
| ASRock Z87                | 5        | 1.38%   |
| Lenovo ThinkCentre        | 4        | 1.1%    |
| Dell Precision            | 4        | 1.1%    |
| ASRock Prime              | 4        | 1.1%    |
| ASRock B450M              | 4        | 1.1%    |
| ASRock B450               | 4        | 1.1%    |
| MSI MS-7A40               | 3        | 0.83%   |
| HP ProDesk                | 3        | 0.83%   |
| Gigabyte Z390             | 3        | 0.83%   |
| ECS G31T-M                | 3        | 0.83%   |
| ASRock X370               | 3        | 0.83%   |
| Onkyo ONKYOPC             | 2        | 0.55%   |
| NEC Computers Express5800 | 2        | 0.55%   |
| MSI MS-7D16               | 2        | 0.55%   |
| MSI MS-7C94               | 2        | 0.55%   |
| MSI MS-7C37               | 2        | 0.55%   |
| MSI MS-7C02               | 2        | 0.55%   |
| MSI MS-7A72               | 2        | 0.55%   |
| MSI MS-7865               | 2        | 0.55%   |
| MouseComputer B360M       | 2        | 0.55%   |
| HP Z620                   | 2        | 0.55%   |
| HP EliteDesk              | 2        | 0.55%   |
| Gigabyte Z77X-UD3H        | 2        | 0.55%   |
| Gigabyte Z170X-Gaming     | 2        | 0.55%   |
| Gigabyte H67A-D3H-B3      | 2        | 0.55%   |
| Gigabyte GA-MA69G-S3H     | 2        | 0.55%   |
| Gigabyte G33-DS3R         | 2        | 0.55%   |
| Gigabyte 970A-D3P         | 2        | 0.55%   |
| EPSON DIRECT Endeavor     | 2        | 0.55%   |
| Biostar Hi-Fi             | 2        | 0.55%   |
| ASUS SABERTOOTH           | 2        | 0.55%   |
| ASUS Rampage              | 2        | 0.55%   |
| ASUS PRO                  | 2        | 0.55%   |
| ASUS P8H77-V              | 2        | 0.55%   |
| ASUS P7H55-M              | 2        | 0.55%   |
| ASUS P5Q                  | 2        | 0.55%   |
| ASUS M3A78-EM             | 2        | 0.55%   |
| ASRock Z390               | 2        | 0.55%   |
| ASRock X570               | 2        | 0.55%   |
| ASRock X470               | 2        | 0.55%   |
| ASRock J5005-ITX          | 2        | 0.55%   |
| ASRock H310CM-HDV         | 2        | 0.55%   |
| ASRock H110               | 2        | 0.55%   |
| ASRock FM2A88X-ITX+       | 2        | 0.55%   |
| ASRock B460M              | 2        | 0.55%   |
| ASRock AB350              | 2        | 0.55%   |
| ASRock A300M-STX          | 2        | 0.55%   |
| Acer Aspire               | 2        | 0.55%   |
| XFX nForce                | 1        | 0.28%   |
| Wistron FMVXDBTL2Z        | 1        | 0.28%   |
| Wistron FMVCE50M7         | 1        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 48       | 13.22%  |
| 2012 | 46       | 12.67%  |
| 2013 | 39       | 10.74%  |
| 2020 | 25       | 6.89%   |
| 2010 | 24       | 6.61%   |
| 2019 | 22       | 6.06%   |
| 2011 | 20       | 5.51%   |
| 2009 | 20       | 5.51%   |
| 2016 | 19       | 5.23%   |
| 2007 | 17       | 4.68%   |
| 2014 | 16       | 4.41%   |
| 2017 | 15       | 4.13%   |
| 2015 | 15       | 4.13%   |
| 2008 | 14       | 3.86%   |
| 2021 | 9        | 2.48%   |
| 2006 | 8        | 2.2%    |
| 2005 | 5        | 1.38%   |
| 2003 | 1        | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 363      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 352      | 96.7%   |
| Enabled  | 12       | 3.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 363      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 84       | 22.34%  |
| 8.01-16.0       | 81       | 21.54%  |
| 3.01-4.0        | 61       | 16.22%  |
| 4.01-8.0        | 49       | 13.03%  |
| 32.01-64.0      | 49       | 13.03%  |
| 64.01-256.0     | 20       | 5.32%   |
| 1.01-2.0        | 14       | 3.72%   |
| 24.01-32.0      | 11       | 2.93%   |
| 2.01-3.0        | 5        | 1.33%   |
| More than 256.0 | 1        | 0.27%   |
| 0.51-1.0        | 1        | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 178      | 43.2%   |
| 2.01-3.0   | 81       | 19.66%  |
| 3.01-4.0   | 44       | 10.68%  |
| 0.51-1.0   | 40       | 9.71%   |
| 4.01-8.0   | 37       | 8.98%   |
| 8.01-16.0  | 15       | 3.64%   |
| 16.01-24.0 | 8        | 1.94%   |
| 0.01-0.5   | 6        | 1.46%   |
| 24.01-32.0 | 2        | 0.49%   |
| 32.01-64.0 | 1        | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 160      | 42.33%  |
| 2      | 114      | 30.16%  |
| 3      | 50       | 13.23%  |
| 4      | 27       | 7.14%   |
| 5      | 14       | 3.7%    |
| 7      | 5        | 1.32%   |
| 6      | 4        | 1.06%   |
| 0      | 2        | 0.53%   |
| 11     | 1        | 0.26%   |
| 9      | 1        | 0.26%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 223      | 60.6%   |
| No        | 145      | 39.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 363      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 245      | 66.94%  |
| Yes       | 121      | 33.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 263      | 71.08%  |
| Yes       | 107      | 28.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Japan   | 363      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Desktops | Percent |
|-------------|----------|---------|
| Tokyo       | 25       | 6.49%   |
| Yokohama    | 22       | 5.71%   |
| Osaka       | 15       | 3.9%    |
| Shinjuku    | 11       | 2.86%   |
| Nagoya      | 11       | 2.86%   |
| Fukuoka     | 8        | 2.08%   |
| Sapporo     | 7        | 1.82%   |
| Minato-ku   | 6        | 1.56%   |
| Okayama     | 5        | 1.3%    |
| Niigata     | 5        | 1.3%    |
| Miyazaki    | 5        | 1.3%    |
| Kawasaki    | 5        | 1.3%    |
| Tsukuba     | 4        | 1.04%   |
| Toyokawa    | 4        | 1.04%   |
| Saitama     | 4        | 1.04%   |
| Minatomirai | 4        | 1.04%   |
| Matsudo     | 4        | 1.04%   |
| Maebashi    | 4        | 1.04%   |
| Koto        | 4        | 1.04%   |
| Kochi       | 4        | 1.04%   |
| Kobe        | 4        | 1.04%   |
| Honcho      | 4        | 1.04%   |
| Chiba       | 4        | 1.04%   |
| Tokushima   | 3        | 0.78%   |
| Shibuya     | 3        | 0.78%   |
| Setagaya-ku | 3        | 0.78%   |
| Ōta-ku     | 3        | 0.78%   |
| Nagasaki    | 3        | 0.78%   |
| Nagano      | 3        | 0.78%   |
| Morioka     | 3        | 0.78%   |
| Mito        | 3        | 0.78%   |
| Kumamoto    | 3        | 0.78%   |
| Kitakyushu  | 3        | 0.78%   |
| Kanazawa    | 3        | 0.78%   |
| Hiroshima   | 3        | 0.78%   |
| Gifu City   | 3        | 0.78%   |
| Yamaguchi   | 2        | 0.52%   |
| Utsunomiya  | 2        | 0.52%   |
| Ushiku      | 2        | 0.52%   |
| Toyama      | 2        | 0.52%   |
| Tokorozawa  | 2        | 0.52%   |
| Tochigi     | 2        | 0.52%   |
| Takamatsu   | 2        | 0.52%   |
| Taito       | 2        | 0.52%   |
| Suzuka      | 2        | 0.52%   |
| Suita       | 2        | 0.52%   |
| Suginami-ku | 2        | 0.52%   |
| Soka Shi    | 2        | 0.52%   |
| Saku        | 2        | 0.52%   |
| Ōtsu       | 2        | 0.52%   |
| Okazaki     | 2        | 0.52%   |
| Neyagawa    | 2        | 0.52%   |
| Naha        | 2        | 0.52%   |
| Matsuyama   | 2        | 0.52%   |
| Machida     | 2        | 0.52%   |
| Kyoto       | 2        | 0.52%   |
| Koshigaya   | 2        | 0.52%   |
| Kohoku-ku   | 2        | 0.52%   |
| Kofu        | 2        | 0.52%   |
| Kakogawa    | 2        | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 136      | 216    | 21.32%  |
| WDC                         | 113      | 195    | 17.71%  |
| Samsung Electronics         | 53       | 74     | 8.31%   |
| Hitachi                     | 45       | 60     | 7.05%   |
| Toshiba                     | 40       | 54     | 6.27%   |
| Crucial                     | 37       | 48     | 5.8%    |
| SanDisk                     | 27       | 39     | 4.23%   |
| Intel                       | 26       | 37     | 4.08%   |
| A-DATA Technology           | 17       | 19     | 2.66%   |
| SPCC                        | 14       | 18     | 2.19%   |
| Unknown                     | 10       | 13     | 1.57%   |
| Phison                      | 10       | 15     | 1.57%   |
| HGST                        | 9        | 11     | 1.41%   |
| Kingston                    | 8        | 10     | 1.25%   |
| Plextor                     | 6        | 8      | 0.94%   |
| Transcend                   | 4        | 6      | 0.63%   |
| OCZ                         | 4        | 4      | 0.63%   |
| Micron/Crucial Technology   | 4        | 5      | 0.63%   |
| Maxtor                      | 4        | 6      | 0.63%   |
| Green House                 | 4        | 4      | 0.63%   |
| China                       | 4        | 5      | 0.63%   |
| Silicon Motion              | 3        | 10     | 0.47%   |
| Patriot                     | 3        | 3      | 0.47%   |
| Micron Technology           | 3        | 4      | 0.47%   |
| KLEVV                       | 3        | 8      | 0.47%   |
| Dogfish                     | 3        | 3      | 0.47%   |
| Zheino                      | 2        | 2      | 0.31%   |
| Teclast                     | 2        | 2      | 0.31%   |
| MARVELL                     | 2        | 4      | 0.31%   |
| Lexar                       | 2        | 2      | 0.31%   |
| KIOXIA-EXCERIA              | 2        | 2      | 0.31%   |
| JMicron Technology          | 2        | 2      | 0.31%   |
| Apple                       | 2        | 2      | 0.31%   |
| Apacer                      | 2        | 2      | 0.31%   |
| AEGO                        | 2        | 2      | 0.31%   |
| Yangtze Memory Technologies | 1        | 1      | 0.16%   |
| XSTAR                       | 1        | 1      | 0.16%   |
| Team                        | 1        | 1      | 0.16%   |
| TCSUNBOW                    | 1        | 1      | 0.16%   |
| SK hynix                    | 1        | 1      | 0.16%   |
| SATA3 51                    | 1        | 2      | 0.16%   |
| Realtek Semiconductor       | 1        | 1      | 0.16%   |
| Quantum                     | 1        | 1      | 0.16%   |
| Palit                       | 1        | 1      | 0.16%   |
| Netac                       | 1        | 1      | 0.16%   |
| MIRACLE                     | 1        | 1      | 0.16%   |
| MARSHAL                     | 1        | 1      | 0.16%   |
| LuminouTek                  | 1        | 1      | 0.16%   |
| Lite-On                     | 1        | 1      | 0.16%   |
| Kingmax                     | 1        | 1      | 0.16%   |
| KingDian                    | 1        | 1      | 0.16%   |
| KESU                        | 1        | 1      | 0.16%   |
| Integral                    | 1        | 1      | 0.16%   |
| HPT                         | 1        | 6      | 0.16%   |
| Hewlett-Packard             | 1        | 1      | 0.16%   |
| Fujitsu                     | 1        | 1      | 0.16%   |
| External                    | 1        | 1      | 0.16%   |
| DIERYA                      | 1        | 1      | 0.16%   |
| Corsair                     | 1        | 1      | 0.16%   |
| CIS                         | 1        | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Toshiba DT01ACA100 1TB                 | 15       | 2.04%   |
| Crucial CT500MX500SSD1 500GB           | 9        | 1.22%   |
| Toshiba DT01ACA200 2TB                 | 7        | 0.95%   |
| Seagate ST4000DM004-2CV104 4TB         | 7        | 0.95%   |
| WDC WD40EZRZ-00GXCB0 4TB               | 6        | 0.82%   |
| Seagate ST500DM002-1BD142 500GB        | 6        | 0.82%   |
| Seagate ST3500418AS 500GB              | 6        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB         | 6        | 0.82%   |
| Seagate ST1000DM010-2EP102 1TB         | 6        | 0.82%   |
| Crucial CT240BX500SSD1 240GB           | 6        | 0.82%   |
| WDC WD20EZRX-00DC0B0 2TB               | 5        | 0.68%   |
| SPCC Solid State Disk 256GB            | 5        | 0.68%   |
| Seagate ST2000DM006-2DM164 2TB         | 5        | 0.68%   |
| Seagate ST2000DM005-2CW102 2TB         | 5        | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB         | 5        | 0.68%   |
| Crucial CT120BX500SSD1 120GB           | 5        | 0.68%   |
| WDC WD20EZAZ-00GGJB0 2TB               | 4        | 0.54%   |
| WDC WD10EADS-22M2B0 1TB                | 4        | 0.54%   |
| WDC WD10EADS-00L5B1 1TB                | 4        | 0.54%   |
| Seagate ST9500325AS 500GB              | 4        | 0.54%   |
| Seagate ST8000DM004-2CX188 8TB         | 4        | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB         | 4        | 0.54%   |
| Seagate Expansion 1TB                  | 4        | 0.54%   |
| SanDisk SD6SF1M128G1022I 128GB SSD     | 4        | 0.54%   |
| Hitachi HDS722020ALA330 2TB            | 4        | 0.54%   |
| Hitachi HDS721050CLA362 500GB          | 4        | 0.54%   |
| Hitachi HDS721010CLA332 1TB            | 4        | 0.54%   |
| Crucial CT525MX300SSD1 528GB           | 4        | 0.54%   |
| WDC WD82PURZ-85TEUY0 8TB               | 3        | 0.41%   |
| WDC WD20EFRX-68EUZN0 2TB               | 3        | 0.41%   |
| WDC WD10EZEX-00BN5A0 1TB               | 3        | 0.41%   |
| WDC WD10EADS-00M2B0 1TB                | 3        | 0.41%   |
| Unknown SD/MMC 16GB                    | 3        | 0.41%   |
| SPCC Solid State Disk 512GB            | 3        | 0.41%   |
| SPCC Solid State Disk 240GB            | 3        | 0.41%   |
| Seagate ST500DM002-1SB10A 500GB        | 3        | 0.41%   |
| Seagate ST3500413AS 500GB              | 3        | 0.41%   |
| Seagate ST3160815AS 160GB              | 3        | 0.41%   |
| Seagate ST3160318AS 160GB              | 3        | 0.41%   |
| Seagate ST31000528AS 1TB               | 3        | 0.41%   |
| Seagate ST250DM000-1BD141 250GB        | 3        | 0.41%   |
| Seagate ST2000DM001-9YN164 2TB         | 3        | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB         | 3        | 0.41%   |
| Seagate ST2000DL003-9VT166 2TB         | 3        | 0.41%   |
| Seagate ST1000DM003-9YN162 1TB         | 3        | 0.41%   |
| Seagate ST1000DM003-1ER162 1TB         | 3        | 0.41%   |
| SanDisk SDSSDH3 500G                   | 3        | 0.41%   |
| SanDisk NVMe SSD Drive 500GB           | 3        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB         | 3        | 0.41%   |
| Samsung SSD 860 EVO 500GB              | 3        | 0.41%   |
| Samsung SSD 850 EVO 250GB              | 3        | 0.41%   |
| Samsung SSD 840 Series 120GB           | 3        | 0.41%   |
| Samsung SSD 750 EVO 120GB              | 3        | 0.41%   |
| Samsung SM963 2.5" NVMe PCIe SSD 500GB | 3        | 0.41%   |
| Micron/Crucial NVMe SSD Drive 500GB    | 3        | 0.41%   |
| Kingston SV300S37A120G 120GB SSD       | 3        | 0.41%   |
| Intel SSDPEKNW010T8 1TB                | 3        | 0.41%   |
| Intel NVMe SSD Drive 512GB             | 3        | 0.41%   |
| Hitachi HDT725025VLA380 250GB          | 3        | 0.41%   |
| Hitachi HDP725050GLA360 500GB          | 3        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 133      | 210    | 37.89%  |
| WDC                 | 102      | 162    | 29.06%  |
| Hitachi             | 45       | 60     | 12.82%  |
| Toshiba             | 36       | 49     | 10.26%  |
| Samsung Electronics | 14       | 15     | 3.99%   |
| HGST                | 9        | 11     | 2.56%   |
| Maxtor              | 4        | 6      | 1.14%   |
| MARVELL             | 2        | 4      | 0.57%   |
| Quantum             | 1        | 1      | 0.28%   |
| KESU                | 1        | 1      | 0.28%   |
| JMicron Technology  | 1        | 1      | 0.28%   |
| Hewlett-Packard     | 1        | 1      | 0.28%   |
| Fujitsu             | 1        | 1      | 0.28%   |
| ASMT                | 1        | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Crucial             | 36       | 46     | 16.29%  |
| Samsung Electronics | 32       | 39     | 14.48%  |
| SanDisk             | 21       | 26     | 9.5%    |
| Intel               | 15       | 20     | 6.79%   |
| A-DATA Technology   | 15       | 17     | 6.79%   |
| WDC                 | 14       | 20     | 6.33%   |
| SPCC                | 14       | 18     | 6.33%   |
| Kingston            | 8        | 10     | 3.62%   |
| Plextor             | 6        | 8      | 2.71%   |
| Transcend           | 4        | 6      | 1.81%   |
| Toshiba             | 4        | 4      | 1.81%   |
| OCZ                 | 4        | 4      | 1.81%   |
| Green House         | 4        | 4      | 1.81%   |
| China               | 4        | 5      | 1.81%   |
| Unknown             | 3        | 3      | 1.36%   |
| KLEVV               | 3        | 8      | 1.36%   |
| Dogfish             | 3        | 3      | 1.36%   |
| Seagate             | 2        | 4      | 0.9%    |
| Micron Technology   | 2        | 3      | 0.9%    |
| Lexar               | 2        | 2      | 0.9%    |
| Apple               | 2        | 2      | 0.9%    |
| Apacer              | 2        | 2      | 0.9%    |
| AEGO                | 2        | 2      | 0.9%    |
| Zheino              | 1        | 1      | 0.45%   |
| XSTAR               | 1        | 1      | 0.45%   |
| Teclast             | 1        | 1      | 0.45%   |
| Team                | 1        | 1      | 0.45%   |
| TCSUNBOW            | 1        | 1      | 0.45%   |
| SATA3 51            | 1        | 2      | 0.45%   |
| Patriot             | 1        | 1      | 0.45%   |
| Palit               | 1        | 1      | 0.45%   |
| MARSHAL             | 1        | 1      | 0.45%   |
| LuminouTek          | 1        | 1      | 0.45%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.45%   |
| Kingmax             | 1        | 1      | 0.45%   |
| KingDian            | 1        | 1      | 0.45%   |
| Integral            | 1        | 1      | 0.45%   |
| DIERYA              | 1        | 1      | 0.45%   |
| Corsair             | 1        | 1      | 0.45%   |
| CFD                 | 1        | 1      | 0.45%   |
| BUFFALO             | 1        | 1      | 0.45%   |
| Biostar             | 1        | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 272      | 523    | 50.65%  |
| SSD     | 192      | 276    | 35.75%  |
| NVMe    | 62       | 112    | 11.55%  |
| Unknown | 10       | 19     | 1.86%   |
| MMC     | 1        | 1      | 0.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 343      | 784    | 80.52%  |
| NVMe | 62       | 111    | 14.55%  |
| SAS  | 20       | 35     | 4.69%   |
| MMC  | 1        | 1      | 0.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 263      | 441    | 52.6%   |
| 0.51-1.0   | 103      | 143    | 20.6%   |
| 1.01-2.0   | 72       | 109    | 14.4%   |
| 3.01-4.0   | 26       | 39     | 5.2%    |
| 4.01-10.0  | 18       | 40     | 3.6%    |
| 2.01-3.0   | 17       | 26     | 3.4%    |
| 10.01-20.0 | 1        | 1      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 109      | 28.24%  |
| 251-500        | 65       | 16.84%  |
| 501-1000       | 50       | 12.95%  |
| 1001-2000      | 38       | 9.84%   |
| More than 3000 | 34       | 8.81%   |
| 2001-3000      | 23       | 5.96%   |
| 51-100         | 22       | 5.7%    |
| Unknown        | 20       | 5.18%   |
| 1-20           | 18       | 4.66%   |
| 21-50          | 7        | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 153      | 37.97%  |
| 21-50          | 64       | 15.88%  |
| 101-250        | 43       | 10.67%  |
| 51-100         | 35       | 8.68%   |
| 251-500        | 28       | 6.95%   |
| 501-1000       | 24       | 5.96%   |
| Unknown        | 20       | 4.96%   |
| 1001-2000      | 19       | 4.71%   |
| More than 3000 | 9        | 2.23%   |
| 2001-3000      | 8        | 1.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB            | 4        | 4      | 13.33%  |
| SanDisk SD6SF1M128G1022I 128GB SSD | 4        | 4      | 13.33%  |
| Seagate ST9500325AS 500GB          | 3        | 3      | 10%     |
| WDC WD30EZRX-00DC0B0 3TB           | 1        | 2      | 3.33%   |
| WDC WD25EZRX-00MMMB0 2TB           | 1        | 1      | 3.33%   |
| Transcend TS240GSSD220S 240GB      | 1        | 1      | 3.33%   |
| SPCC Solid State DiskB28 128GB     | 1        | 1      | 3.33%   |
| SPCC Solid State Disk 512GB        | 1        | 2      | 3.33%   |
| Seagate ST3500418AS 500GB          | 1        | 1      | 3.33%   |
| Seagate ST3250310AS 250GB          | 1        | 2      | 3.33%   |
| Seagate ST3120026A 120GB           | 1        | 1      | 3.33%   |
| Seagate ST31000528AS 1TB           | 1        | 1      | 3.33%   |
| Seagate ST31000333AS 1TB           | 1        | 1      | 3.33%   |
| Seagate ST3000VM002-1ET166 3TB     | 1        | 1      | 3.33%   |
| Seagate ST2000DX002-2DV164 2TB     | 1        | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1        | 1      | 3.33%   |
| Hitachi HTS727575A9E364 752GB      | 1        | 1      | 3.33%   |
| Hitachi HDT721032SLA360 320GB      | 1        | 1      | 3.33%   |
| Hitachi HDS721010CLA332 1TB        | 1        | 1      | 3.33%   |
| Crucial CT480M500SSD1 480GB        | 1        | 1      | 3.33%   |
| Corsair CSSD-F60GB2 64GB           | 1        | 1      | 3.33%   |
| A-DATA Technology SP900 256GB SSD  | 1        | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Seagate           | 10       | 12     | 34.48%  |
| WDC               | 6        | 7      | 20.69%  |
| SanDisk           | 4        | 4      | 13.79%  |
| Hitachi           | 3        | 3      | 10.34%  |
| SPCC              | 2        | 3      | 6.9%    |
| Transcend         | 1        | 1      | 3.45%   |
| Crucial           | 1        | 1      | 3.45%   |
| Corsair           | 1        | 1      | 3.45%   |
| A-DATA Technology | 1        | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 10       | 12     | 52.63%  |
| WDC     | 6        | 7      | 31.58%  |
| Hitachi | 3        | 3      | 15.79%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 17       | 22     | 62.96%  |
| SSD  | 10       | 11     | 37.04%  |

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
| Detected | 263      | 680    | 68.49%  |
| Works    | 98       | 218    | 25.52%  |
| Malfunc  | 23       | 33     | 5.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 248      | 48.72%  |
| AMD                              | 108      | 21.22%  |
| ASMedia Technology               | 33       | 6.48%   |
| Marvell Technology Group         | 19       | 3.73%   |
| Samsung Electronics              | 15       | 2.95%   |
| JMicron Technology               | 15       | 2.95%   |
| Phison Electronics               | 12       | 2.36%   |
| SanDisk                          | 11       | 2.16%   |
| VIA Technologies                 | 8        | 1.57%   |
| Micron/Crucial Technology        | 6        | 1.18%   |
| Silicon Motion                   | 5        | 0.98%   |
| Nvidia                           | 4        | 0.79%   |
| Broadcom / LSI                   | 3        | 0.59%   |
| ADATA Technology                 | 3        | 0.59%   |
| Adaptec                          | 3        | 0.59%   |
| Silicon Image                    | 2        | 0.39%   |
| Seagate Technology               | 2        | 0.39%   |
| Realtek Semiconductor            | 2        | 0.39%   |
| Yangtze Memory Technologies      | 1        | 0.2%    |
| ULi Electronics                  | 1        | 0.2%    |
| Toshiba America Info Systems     | 1        | 0.2%    |
| SK hynix                         | 1        | 0.2%    |
| Silicon Integrated Systems [SiS] | 1        | 0.2%    |
| Promise Technology               | 1        | 0.2%    |
| Micron Technology                | 1        | 0.2%    |
| LSI Logic / Symbios Logic        | 1        | 0.2%    |
| KIOXIA                           | 1        | 0.2%    |
| HighPoint Technologies           | 1        | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 63       | 9.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 29       | 4.35%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 28       | 4.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 26       | 3.9%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24       | 3.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 20       | 3%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 19       | 2.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 16       | 2.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 16       | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 15       | 2.25%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 14       | 2.1%    |
| AMD 500 Series Chipset SATA Controller                                                  | 12       | 1.8%    |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.65%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11       | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10       | 1.5%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 9        | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 8        | 1.2%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 8        | 1.2%    |
| AMD FCH IDE Controller                                                                  | 8        | 1.2%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 7        | 1.05%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7        | 1.05%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 6        | 0.9%    |
| JMicron JMB368 IDE controller                                                           | 6        | 0.9%    |
| Intel SSD 660P Series                                                                   | 6        | 0.9%    |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 6        | 0.9%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 6        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6        | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 6        | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                                  | 6        | 0.9%    |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 5        | 0.75%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 5        | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4        | 0.6%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 4        | 0.6%    |
| Phison E12 NVMe Controller                                                              | 4        | 0.6%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 4        | 0.6%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 4        | 0.6%    |
| Intel C600/X79 series chipset IDE-r Controller                                          | 4        | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4        | 0.6%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 0.6%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 4        | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 4        | 0.6%    |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 4        | 0.6%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.6%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4        | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.6%    |
| AMD X370 Series Chipset SATA Controller                                                 | 4        | 0.6%    |
| AMD SB600 Non-Raid-5 SATA                                                               | 4        | 0.6%    |
| AMD SB600 IDE                                                                           | 4        | 0.6%    |
| AMD FCH SATA Controller [IDE mode]                                                      | 4        | 0.6%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 3        | 0.45%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 3        | 0.45%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 3        | 0.45%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 3        | 0.45%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3        | 0.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 285      | 57.81%  |
| IDE  | 109      | 22.11%  |
| NVMe | 64       | 12.98%  |
| RAID | 26       | 5.27%   |
| SAS  | 5        | 1.01%   |
| SCSI | 4        | 0.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 250      | 68.87%  |
| AMD    | 113      | 31.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel Core i7-3770 CPU @ 3.40GHz                | 10       | 2.74%   |
| AMD Ryzen 5 3600 6-Core Processor               | 10       | 2.74%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 8        | 2.19%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 6        | 1.64%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 6        | 1.64%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 6        | 1.64%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 5        | 1.37%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 5        | 1.37%   |
| Intel Core i7-8700 CPU @ 3.20GHz                | 4        | 1.1%    |
| Intel Core i7-3770K CPU @ 3.50GHz               | 4        | 1.1%    |
| Intel Core i5-4570TE CPU @ 2.70GHz              | 4        | 1.1%    |
| Intel Core i5-3570K CPU @ 3.40GHz               | 4        | 1.1%    |
| Intel Core i3-3220 CPU @ 3.30GHz                | 4        | 1.1%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 4        | 1.1%    |
| Intel Core 2 CPU 6600 @ 2.40GHz                 | 4        | 1.1%    |
| Intel Core 2 CPU 6400 @ 2.13GHz                 | 4        | 1.1%    |
| AMD Ryzen 9 3950X 16-Core Processor             | 4        | 1.1%    |
| AMD Ryzen 5 5600X 6-Core Processor              | 4        | 1.1%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics     | 4        | 1.1%    |
| Intel Core i9-9900K CPU @ 3.60GHz               | 3        | 0.82%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 3        | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 3        | 0.82%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 3        | 0.82%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz           | 3        | 0.82%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz            | 3        | 0.82%   |
| AMD Ryzen 7 2700X Eight-Core Processor          | 3        | 0.82%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 3        | 0.82%   |
| AMD Athlon 200GE with Radeon Vega Graphics      | 3        | 0.82%   |
| AMD A10-7870K Radeon R7, 12 Compute Cores 4C+8G | 3        | 0.82%   |
| Intel Xeon CPU W3520 @ 2.67GHz                  | 2        | 0.55%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz        | 2        | 0.55%   |
| Intel Pentium CPU G6950 @ 2.80GHz               | 2        | 0.55%   |
| Intel Pentium CPU G4560 @ 3.50GHz               | 2        | 0.55%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 2        | 0.55%   |
| Intel Pentium 4 CPU 3.40GHz                     | 2        | 0.55%   |
| Intel Pentium 4 CPU 2.80GHz                     | 2        | 0.55%   |
| Intel Core i9-10900 CPU @ 2.80GHz               | 2        | 0.55%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 2        | 0.55%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 2        | 0.55%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 2        | 0.55%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 2        | 0.55%   |
| Intel Core i7-3820 CPU @ 3.60GHz                | 2        | 0.55%   |
| Intel Core i5-9600K CPU @ 3.70GHz               | 2        | 0.55%   |
| Intel Core i5-8500 CPU @ 3.00GHz                | 2        | 0.55%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 2        | 0.55%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 2        | 0.55%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 2        | 0.55%   |
| Intel Core i5-4430 CPU @ 3.00GHz                | 2        | 0.55%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 2        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2        | 0.55%   |
| Intel Core i5 CPU 750 @ 2.67GHz                 | 2        | 0.55%   |
| Intel Core i3-7100 CPU @ 3.90GHz                | 2        | 0.55%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 2        | 0.55%   |
| Intel Core i3-3225 CPU @ 3.30GHz                | 2        | 0.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 2        | 0.55%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 2        | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz           | 2        | 0.55%   |
| Intel Celeron G5905 CPU @ 3.50GHz               | 2        | 0.55%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 2        | 0.55%   |
| Intel Atom CPU D510 @ 1.66GHz                   | 2        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 68       | 18.68%  |
| Intel Core i5           | 52       | 14.29%  |
| AMD Ryzen 5             | 26       | 7.14%   |
| Intel Core i3           | 25       | 6.87%   |
| Intel Xeon              | 22       | 6.04%   |
| AMD Ryzen 7             | 20       | 5.49%   |
| Intel Core 2 Duo        | 19       | 5.22%   |
| Intel Celeron           | 14       | 3.85%   |
| Intel Core 2 Quad       | 10       | 2.75%   |
| Intel Pentium           | 8        | 2.2%    |
| Intel Core 2            | 8        | 2.2%    |
| Intel Core i9           | 7        | 1.92%   |
| AMD Athlon              | 7        | 1.92%   |
| AMD Ryzen 9             | 6        | 1.65%   |
| AMD Phenom II X4        | 6        | 1.65%   |
| AMD FX                  | 6        | 1.65%   |
| Intel Pentium 4         | 5        | 1.37%   |
| AMD Athlon 64 X2        | 5        | 1.37%   |
| AMD A10                 | 5        | 1.37%   |
| AMD Ryzen 3             | 4        | 1.1%    |
| AMD A8                  | 4        | 1.1%    |
| Intel Pentium Dual-Core | 3        | 0.82%   |
| Intel Pentium Silver    | 2        | 0.55%   |
| Intel Pentium Gold      | 2        | 0.55%   |
| Intel Atom              | 2        | 0.55%   |
| AMD Sempron             | 2        | 0.55%   |
| AMD Ryzen Threadripper  | 2        | 0.55%   |
| AMD Phenom II X6        | 2        | 0.55%   |
| AMD Phenom              | 2        | 0.55%   |
| AMD Athlon Dual Core    | 2        | 0.55%   |
| AMD Athlon 64           | 2        | 0.55%   |
| AMD A6                  | 2        | 0.55%   |
| AMD A4                  | 2        | 0.55%   |
| AMD A12                 | 2        | 0.55%   |
| Other                   | 1        | 0.27%   |
| Intel Pentium Dual      | 1        | 0.27%   |
| Intel Pentium D         | 1        | 0.27%   |
| Intel Core 2 Extreme    | 1        | 0.27%   |
| AMD Ryzen 5 PRO         | 1        | 0.27%   |
| AMD Phenom II X2        | 1        | 0.27%   |
| AMD E2                  | 1        | 0.27%   |
| AMD E                   | 1        | 0.27%   |
| AMD Athlon II X4        | 1        | 0.27%   |
| AMD Athlon II X2        | 1        | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 140      | 38.46%  |
| 2      | 110      | 30.22%  |
| 6      | 52       | 14.29%  |
| 8      | 29       | 7.97%   |
| 1      | 11       | 3.02%   |
| 16     | 9        | 2.47%   |
| 3      | 4        | 1.1%    |
| 12     | 3        | 0.82%   |
| 10     | 3        | 0.82%   |
| 32     | 1        | 0.27%   |
| 20     | 1        | 0.27%   |
| 14     | 1        | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 358      | 98.62%  |
| 2      | 5        | 1.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 214      | 58.79%  |
| 1      | 150      | 41.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 358      | 98.08%  |
| Unknown        | 4        | 1.1%    |
| 32-bit         | 3        | 0.82%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 72       | 18.9%   |
| 0x306a9    | 31       | 8.14%   |
| 0x306c3    | 26       | 6.82%   |
| 0x1067a    | 22       | 5.77%   |
| 0x206a7    | 19       | 4.99%   |
| 0x08701021 | 16       | 4.2%    |
| 0x906ea    | 15       | 3.94%   |
| 0x506e3    | 14       | 3.67%   |
| 0x906e9    | 10       | 2.62%   |
| 0x906ed    | 6        | 1.57%   |
| 0x0800820d | 6        | 1.57%   |
| 0x206d7    | 5        | 1.31%   |
| 0x106e5    | 5        | 1.31%   |
| 0x06003106 | 5        | 1.31%   |
| 0x06001119 | 5        | 1.31%   |
| 0x010000db | 5        | 1.31%   |
| 0xa0655    | 4        | 1.05%   |
| 0x6fb      | 4        | 1.05%   |
| 0x50654    | 4        | 1.05%   |
| 0x306f2    | 4        | 1.05%   |
| 0x10676    | 4        | 1.05%   |
| 0x0a201016 | 4        | 1.05%   |
| 0x010000c8 | 4        | 1.05%   |
| 0x706a1    | 3        | 0.79%   |
| 0x6f6      | 3        | 0.79%   |
| 0x306e4    | 3        | 0.79%   |
| 0x20655    | 3        | 0.79%   |
| 0x08701013 | 3        | 0.79%   |
| 0x08108109 | 3        | 0.79%   |
| 0x08101016 | 3        | 0.79%   |
| 0x0810100b | 3        | 0.79%   |
| 0x0600063e | 3        | 0.79%   |
| 0x03000027 | 3        | 0.79%   |
| 0xf43      | 2        | 0.52%   |
| 0xf41      | 2        | 0.52%   |
| 0xa0653    | 2        | 0.52%   |
| 0x906ec    | 2        | 0.52%   |
| 0x6f2      | 2        | 0.52%   |
| 0x406c4    | 2        | 0.52%   |
| 0x406c3    | 2        | 0.52%   |
| 0x206c2    | 2        | 0.52%   |
| 0x20652    | 2        | 0.52%   |
| 0x106ca    | 2        | 0.52%   |
| 0x106a5    | 2        | 0.52%   |
| 0x10677    | 2        | 0.52%   |
| 0x08108102 | 2        | 0.52%   |
| 0x08001138 | 2        | 0.52%   |
| 0x0700010f | 2        | 0.52%   |
| 0x0600611a | 2        | 0.52%   |
| 0x010000dc | 2        | 0.52%   |
| 0x01000083 | 2        | 0.52%   |
| 0xf65      | 1        | 0.26%   |
| 0xf47      | 1        | 0.26%   |
| 0xf33      | 1        | 0.26%   |
| 0xa0671    | 1        | 0.26%   |
| 0x906eb    | 1        | 0.26%   |
| 0x806ec    | 1        | 0.26%   |
| 0x6fd      | 1        | 0.26%   |
| 0x406f1    | 1        | 0.26%   |
| 0x40651    | 1        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| KabyLake      | 40       | 10.99%  |
| IvyBridge     | 40       | 10.99%  |
| Haswell       | 35       | 9.62%   |
| Penryn        | 30       | 8.24%   |
| Zen 2         | 27       | 7.42%   |
| SandyBridge   | 27       | 7.42%   |
| Skylake       | 20       | 5.49%   |
| Zen+          | 15       | 4.12%   |
| Zen           | 15       | 4.12%   |
| K10           | 14       | 3.85%   |
| Core          | 13       | 3.57%   |
| K8 Hammer     | 10       | 2.75%   |
| CometLake     | 10       | 2.75%   |
| Nehalem       | 9        | 2.47%   |
| Zen 3         | 8        | 2.2%    |
| Westmere      | 8        | 2.2%    |
| Piledriver    | 7        | 1.92%   |
| NetBurst      | 7        | 1.92%   |
| Steamroller   | 5        | 1.37%   |
| Silvermont    | 4        | 1.1%    |
| Bulldozer     | 4        | 1.1%    |
| K10 Llano     | 3        | 0.82%   |
| Jaguar        | 3        | 0.82%   |
| Goldmont plus | 3        | 0.82%   |
| Excavator     | 2        | 0.55%   |
| Bonnell       | 2        | 0.55%   |
| Icelake       | 1        | 0.27%   |
| Broadwell     | 1        | 0.27%   |
| Bobcat        | 1        | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Nvidia           | 152      | 39.18%  |
| AMD              | 121      | 31.19%  |
| Intel            | 114      | 29.38%  |
| VIA Technologies | 1        | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16       | 3.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11       | 2.72%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11       | 2.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11       | 2.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11       | 2.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11       | 2.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11       | 2.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10       | 2.48%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8        | 1.98%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 7        | 1.73%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 7        | 1.73%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 7        | 1.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7        | 1.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 6        | 1.49%   |
| Intel HD Graphics 530                                                                    | 6        | 1.49%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6        | 1.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 6        | 1.49%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 5        | 1.24%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 5        | 1.24%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 5        | 1.24%   |
| Intel HD Graphics 630                                                                    | 5        | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5        | 1.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5        | 1.24%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 5        | 1.24%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 4        | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 4        | 0.99%   |
| Nvidia GT218 [GeForce 210]                                                               | 4        | 0.99%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4        | 0.99%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4        | 0.99%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 4        | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4        | 0.99%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4        | 0.99%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 4        | 0.99%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 4        | 0.99%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 3        | 0.74%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                                | 3        | 0.74%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 3        | 0.74%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3        | 0.74%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 3        | 0.74%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3        | 0.74%   |
| Intel 82915G/GV/910GL Integrated Graphics Controller                                     | 3        | 0.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 0.74%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 3        | 0.74%   |
| AMD RS780 [Radeon HD 3200]                                                               | 3        | 0.74%   |
| AMD Barts PRO [Radeon HD 6850]                                                           | 3        | 0.74%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2        | 0.5%    |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 2        | 0.5%    |
| Nvidia GT200 [GeForce GTX 260]                                                           | 2        | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 2        | 0.5%    |
| Nvidia GM200 [GeForce GTX TITAN X]                                                       | 2        | 0.5%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                                        | 2        | 0.5%    |
| Nvidia GM107GL [Quadro K620]                                                             | 2        | 0.5%    |
| Nvidia GK107GL [Quadro K600]                                                             | 2        | 0.5%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 2        | 0.5%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 2        | 0.5%    |
| Nvidia GF108GL [Quadro 600]                                                              | 2        | 0.5%    |
| Nvidia GF108 [GeForce GT 430]                                                            | 2        | 0.5%    |
| Nvidia G96C [GeForce 9400 GT]                                                            | 2        | 0.5%    |
| Nvidia G86 [GeForce 8400 GS]                                                             | 2        | 0.5%    |
| Nvidia G73 [GeForce 7600 GS]                                                             | 2        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 136      | 37.06%  |
| 1 x AMD                  | 109      | 29.7%   |
| 1 x Intel                | 98       | 26.7%   |
| 2 x Nvidia               | 5        | 1.36%   |
| 2 x AMD                  | 5        | 1.36%   |
| AMD + Nvidia             | 4        | 1.09%   |
| Intel + Nvidia           | 3        | 0.82%   |
| Intel + 2 x Nvidia       | 2        | 0.54%   |
| Other                    | 1        | 0.27%   |
| 1 x VIA                  | 1        | 0.27%   |
| Intel + 2 x AMD          | 1        | 0.27%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.27%   |
| Intel + AMD              | 1        | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 276      | 74.19%  |
| Proprietary | 86       | 23.12%  |
| Unknown     | 10       | 2.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 131      | 34.75%  |
| 0.01-0.5   | 61       | 16.18%  |
| 0.51-1.0   | 55       | 14.59%  |
| 1.01-2.0   | 52       | 13.79%  |
| 3.01-4.0   | 29       | 7.69%   |
| 7.01-8.0   | 21       | 5.57%   |
| 5.01-6.0   | 13       | 3.45%   |
| 8.01-16.0  | 9        | 2.39%   |
| 16.01-24.0 | 5        | 1.33%   |
| 2.01-3.0   | 1        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| IOD                  | 37       | 9.44%   |
| Dell                 | 36       | 9.18%   |
| Goldstar             | 32       | 8.16%   |
| BenQ                 | 25       | 6.38%   |
| Mitsubishi           | 23       | 5.87%   |
| Iiyama               | 23       | 5.87%   |
| Acer                 | 22       | 5.61%   |
| Eizo                 | 17       | 4.34%   |
| Unknown              | 15       | 3.83%   |
| Philips              | 14       | 3.57%   |
| Hewlett-Packard      | 14       | 3.57%   |
| Samsung Electronics  | 12       | 3.06%   |
| AOC                  | 12       | 3.06%   |
| Ancor Communications | 12       | 3.06%   |
| Sharp                | 11       | 2.81%   |
| NEC Computers        | 10       | 2.55%   |
| Idek Iiyama          | 7        | 1.79%   |
| Sony                 | 6        | 1.53%   |
| Panasonic            | 6        | 1.53%   |
| Toshiba              | 5        | 1.28%   |
| LG Electronics       | 5        | 1.28%   |
| Lenovo               | 5        | 1.28%   |
| ASUSTek Computer     | 4        | 1.02%   |
| Unknown (XXX)        | 3        | 0.77%   |
| Fujitsu              | 3        | 0.77%   |
| SKY                  | 2        | 0.51%   |
| PTF                  | 2        | 0.51%   |
| Onkyo                | 2        | 0.51%   |
| LYC                  | 2        | 0.51%   |
| Hitachi              | 2        | 0.51%   |
| BUFFALO              | 2        | 0.51%   |
| Unknown              | 2        | 0.51%   |
| ___                  | 1        | 0.26%   |
| ViewSonic            | 1        | 0.26%   |
| VFV                  | 1        | 0.26%   |
| S2-Tek               | 1        | 0.26%   |
| Pixio                | 1        | 0.26%   |
| OOO                  | 1        | 0.26%   |
| Novatek              | 1        | 0.26%   |
| MPI                  | 1        | 0.26%   |
| Megavision           | 1        | 0.26%   |
| Lenovo Group Limited | 1        | 0.26%   |
| LED                  | 1        | 0.26%   |
| KAT                  | 1        | 0.26%   |
| InnoLux Display      | 1        | 0.26%   |
| HYO                  | 1        | 0.26%   |
| HPN                  | 1        | 0.26%   |
| Gigabyte Technology  | 1        | 0.26%   |
| Epson                | 1        | 0.26%   |
| Dinner               | 1        | 0.26%   |
| DENON                | 1        | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| AOC 28E850 AOC0CCD 2560x1600 480x270mm 21.7-inch                     | 5        | 1.19%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch          | 4        | 0.95%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 3        | 0.71%   |
| Mitsubishi MDT241WG MEL478E 1920x1200 518x291mm 23.4-inch            | 3        | 0.71%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 3        | 0.71%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                     | 3        | 0.71%   |
| Ancor Communications VE248 ACI2494 1920x1080 530x300mm 24.0-inch     | 3        | 0.71%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                      | 3        | 0.71%   |
| Unknown LCD Monitor Mitsubishi RDT233WLM 1920x1080                   | 2        | 0.48%   |
| SKY TV-monitor SKY1901 3840x2160 1210x680mm 54.6-inch                | 2        | 0.48%   |
| Samsung Electronics SyncMaster SAM01AE 1600x1200 408x306mm 20.1-inch | 2        | 0.48%   |
| Samsung Electronics SyncMaster SAM01AD 1600x1200 408x306mm 20.1-inch | 2        | 0.48%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch              | 2        | 0.48%   |
| Mitsubishi RDT234WLM MEL4887 1920x1080 509x286mm 23.0-inch           | 2        | 0.48%   |
| Mitsubishi RDT194S MEL4685 1280x1024 376x301mm 19.0-inch             | 2        | 0.48%   |
| LYC L2106 LYC0001 1920x1080 480x260mm 21.5-inch                      | 2        | 0.48%   |
| IOD LCD-RDT242XP IOD1891 1920x1080 527x296mm 23.8-inch               | 2        | 0.48%   |
| IOD KH2750V-UHD IOD1B2A 3840x2160 598x336mm 27.0-inch                | 2        | 0.48%   |
| IOD EX-LD2071T IOD150D 1920x1080 458x258mm 20.7-inch                 | 2        | 0.48%   |
| Iiyama PL3291 IVM7605 1920x1080 698x393mm 31.5-inch                  | 2        | 0.48%   |
| Iiyama PL2875UH IVM710F 3840x2160 621x341mm 27.9-inch                | 2        | 0.48%   |
| Iiyama PL2390 IVM562D 1920x1080 510x290mm 23.1-inch                  | 2        | 0.48%   |
| Iiyama PL2290 IVM562C 1920x1080 476x268mm 21.5-inch                  | 2        | 0.48%   |
| Hewlett-Packard P223 HPN3392 1920x1080 477x268mm 21.5-inch           | 2        | 0.48%   |
| Goldstar W2753 GSM56F7 1920x1080 598x336mm 27.0-inch                 | 2        | 0.48%   |
| Goldstar W2261 GSM56CE 1920x1080 477x268mm 21.5-inch                 | 2        | 0.48%   |
| Goldstar ULTRAWIDE GSM76FE 2560x1080 798x334mm 34.1-inch             | 2        | 0.48%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 2        | 0.48%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 2        | 0.48%   |
| Eizo SX2262W ENC2161 1920x1200 519x324mm 24.1-inch                   | 2        | 0.48%   |
| Eizo EV2736W ENC2382 2560x1440 597x336mm 27.0-inch                   | 2        | 0.48%   |
| Dell U2711 DELA055 2560x1440 597x336mm 27.0-inch                     | 2        | 0.48%   |
| Dell 2209WA DELF011 1680x1050 474x296mm 22.0-inch                    | 2        | 0.48%   |
| BUFFALO FTD-G722AS2 BUF1719 1280x1024 337x270mm 17.0-inch            | 2        | 0.48%   |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                     | 2        | 0.48%   |
| BenQ FP71V+ BNQ76A2 1280x1024 376x301mm 19.0-inch                    | 2        | 0.48%   |
| BenQ FP71V+ BNQ76A1 1280x1024 376x301mm 19.0-inch                    | 2        | 0.48%   |
| ASUSTek Computer VZ239 AUS23CC 1920x1080 509x286mm 23.0-inch         | 2        | 0.48%   |
| AOC LCD Monitor 28E850 1920x1080                                     | 2        | 0.48%   |
| Acer KA270H ACR0522 1920x1080 598x336mm 27.0-inch                    | 2        | 0.48%   |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                   | 2        | 0.48%   |
| Acer H233H ACR00A0 1920x1080 510x287mm 23.0-inch                     | 2        | 0.48%   |
| Unknown                                                              | 2        | 0.48%   |
| ___ LCDTV16 ___9000 1360x768                                         | 1        | 0.24%   |
| ViewSonic VX2363 Series VSC6B2F 1920x1080 509x286mm 23.0-inch        | 1        | 0.24%   |
| VFV VFV VFVBC32 1920x1080 344x193mm 15.5-inch                        | 1        | 0.24%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                   | 1        | 0.24%   |
| Unknown LCD Monitor XXX TV-monitor 1920x1080                         | 1        | 0.24%   |
| Unknown LCD Monitor XXX GH-JEF223SH 1680x1050                        | 1        | 0.24%   |
| Unknown LCD Monitor XXX AAA 1920x1080                                | 1        | 0.24%   |
| Unknown LCD Monitor XMI Redmi Monitor 1920x1080                      | 1        | 0.24%   |
| Unknown LCD Monitor Sony SDM-HS94P 1280x1024                         | 1        | 0.24%   |
| Unknown LCD Monitor Mitsubishi RDT272WX 1920x1080                    | 1        | 0.24%   |
| Unknown LCD Monitor Mitsubishi RDT1713VM 3200x1200                   | 1        | 0.24%   |
| Unknown LCD Monitor KVM Monitor 1280x1024                            | 1        | 0.24%   |
| Unknown LCD Monitor IODATA LCD-AD222X 1280x1024                      | 1        | 0.24%   |
| Unknown LCD Monitor IODATA LCD-A174G 1280x1024                       | 1        | 0.24%   |
| Unknown LCD Monitor IODATA EX-LD4K271D 2048x1152                     | 1        | 0.24%   |
| Unknown LCD Monitor IODATA EX-LD321D 1920x1080                       | 1        | 0.24%   |
| Unknown LCD Monitor IODATA EX-LD2381D 1920x1080                      | 1        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 176      | 45.13%  |
| 1280x1024 (SXGA)   | 43       | 11.03%  |
| 3840x2160 (4K)     | 36       | 9.23%   |
| 2560x1440 (QHD)    | 25       | 6.41%   |
| 1920x1200 (WUXGA)  | 24       | 6.15%   |
| 1680x1050 (WSXGA+) | 15       | 3.85%   |
| Unknown            | 13       | 3.33%   |
| 1440x900 (WXGA+)   | 8        | 2.05%   |
| 1600x1200          | 7        | 1.79%   |
| 1920x540           | 5        | 1.28%   |
| 1360x768           | 5        | 1.28%   |
| 1024x768 (XGA)     | 5        | 1.28%   |
| 3840x1080          | 3        | 0.77%   |
| 2560x1080          | 3        | 0.77%   |
| 1366x768 (WXGA)    | 3        | 0.77%   |
| 3200x1200          | 2        | 0.51%   |
| 1400x1050          | 2        | 0.51%   |
| 800x480            | 1        | 0.26%   |
| 7680x2160          | 1        | 0.26%   |
| 640x480            | 1        | 0.26%   |
| 5760x1200          | 1        | 0.26%   |
| 4480x1080          | 1        | 0.26%   |
| 3520x1080          | 1        | 0.26%   |
| 3440x1440          | 1        | 0.26%   |
| 3200x2160          | 1        | 0.26%   |
| 3200x1080          | 1        | 0.26%   |
| 2560x1024          | 1        | 0.26%   |
| 2048x1152          | 1        | 0.26%   |
| 1792x1344          | 1        | 0.26%   |
| 1600x900 (HD+)     | 1        | 0.26%   |
| 1360x765           | 1        | 0.26%   |
| 1280x960           | 1        | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 61       | 15.93%  |
| 24      | 50       | 13.05%  |
| 23      | 50       | 13.05%  |
| 21      | 48       | 12.53%  |
| 27      | 46       | 12.01%  |
| 19      | 30       | 7.83%   |
| 17      | 20       | 5.22%   |
| 20      | 14       | 3.66%   |
| 31      | 12       | 3.13%   |
| 22      | 9        | 2.35%   |
| 18      | 6        | 1.57%   |
| 15      | 5        | 1.31%   |
| 72      | 4        | 1.04%   |
| 84      | 3        | 0.78%   |
| 54      | 3        | 0.78%   |
| 42      | 3        | 0.78%   |
| 37      | 3        | 0.78%   |
| 34      | 3        | 0.78%   |
| 43      | 2        | 0.52%   |
| 40      | 2        | 0.52%   |
| 14      | 2        | 0.52%   |
| 74      | 1        | 0.26%   |
| 64      | 1        | 0.26%   |
| 49      | 1        | 0.26%   |
| 39      | 1        | 0.26%   |
| 35      | 1        | 0.26%   |
| 32      | 1        | 0.26%   |
| 25      | 1        | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 138      | 36.7%   |
| 401-500     | 82       | 21.81%  |
| Unknown     | 61       | 16.22%  |
| 351-400     | 25       | 6.65%   |
| 301-350     | 23       | 6.12%   |
| 601-700     | 16       | 4.26%   |
| 1501-2000   | 8        | 2.13%   |
| 801-900     | 7        | 1.86%   |
| 1001-1500   | 5        | 1.33%   |
| 901-1000    | 5        | 1.33%   |
| 701-800     | 4        | 1.06%   |
| 201-300     | 2        | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 211      | 57.03%  |
| Unknown | 53       | 14.32%  |
| 16/10   | 45       | 12.16%  |
| 5/4     | 38       | 10.27%  |
| 4/3     | 13       | 3.51%   |
| 21/9    | 4        | 1.08%   |
| 32/9    | 3        | 0.81%   |
| 6/5     | 1        | 0.27%   |
| 3/2     | 1        | 0.27%   |
| 1.00    | 1        | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 111      | 28.83%  |
| 151-200        | 68       | 17.66%  |
| Unknown        | 61       | 15.84%  |
| 301-350        | 46       | 11.95%  |
| 251-300        | 28       | 7.27%   |
| 141-150        | 23       | 5.97%   |
| 351-500        | 17       | 4.42%   |
| More than 1000 | 13       | 3.38%   |
| 501-1000       | 10       | 2.6%    |
| 101-110        | 6        | 1.56%   |
| 131-140        | 1        | 0.26%   |
| 91-100         | 1        | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 205      | 54.81%  |
| 101-120 | 74       | 19.79%  |
| Unknown | 61       | 16.31%  |
| 121-160 | 19       | 5.08%   |
| 161-240 | 8        | 2.14%   |
| 1-50    | 7        | 1.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 308      | 83.24%  |
| 2     | 44       | 11.89%  |
| 0     | 13       | 3.51%   |
| 3     | 3        | 0.81%   |
| 4     | 2        | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 210      | 42%     |
| Intel                            | 157      | 31.4%   |
| Qualcomm Atheros                 | 34       | 6.8%    |
| Broadcom                         | 23       | 4.6%    |
| BUFFALO                          | 13       | 2.6%    |
| PLANEX                           | 9        | 1.8%    |
| TP-Link                          | 8        | 1.6%    |
| Marvell Technology Group         | 7        | 1.4%    |
| Elecom                           | 4        | 0.8%    |
| ASIX Electronics                 | 4        | 0.8%    |
| VIA Technologies                 | 3        | 0.6%    |
| Nvidia                           | 3        | 0.6%    |
| Aquantia                         | 3        | 0.6%    |
| Logitec                          | 2        | 0.4%    |
| Huawei Technologies              | 2        | 0.4%    |
| Wilocity                         | 1        | 0.2%    |
| ULi Electronics                  | 1        | 0.2%    |
| U-Blox                           | 1        | 0.2%    |
| Silicon Integrated Systems [SiS] | 1        | 0.2%    |
| Samsung Electronics              | 1        | 0.2%    |
| Ralink Technology                | 1        | 0.2%    |
| Qualcomm Atheros Communications  | 1        | 0.2%    |
| Padix (Rockfire)                 | 1        | 0.2%    |
| NetGear                          | 1        | 0.2%    |
| Netchip Technology               | 1        | 0.2%    |
| NEC Computers                    | 1        | 0.2%    |
| MediaTek                         | 1        | 0.2%    |
| LSI                              | 1        | 0.2%    |
| JMicron Technology               | 1        | 0.2%    |
| Edimax Technology                | 1        | 0.2%    |
| Corega K.K.                      | 1        | 0.2%    |
| Broadcom Limited                 | 1        | 0.2%    |
| ADMtek                           | 1        | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 172      | 30.99%  |
| Intel Ethernet Connection (2) I219-V                               | 24       | 4.32%   |
| Intel I211 Gigabit Network Connection                              | 18       | 3.24%   |
| Intel Wi-Fi 6 AX200                                                | 15       | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                  | 14       | 2.52%   |
| Intel Ethernet Connection (7) I219-V                               | 14       | 2.52%   |
| Intel 82579V Gigabit Network Connection                            | 14       | 2.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 9        | 1.62%   |
| Intel Ethernet Connection I217-V                                   | 8        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8        | 1.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller          | 7        | 1.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 6        | 1.08%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 6        | 1.08%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 5        | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 5        | 0.9%    |
| Intel Ethernet Connection (2) I218-V                               | 5        | 0.9%    |
| Intel 82574L Gigabit Network Connection                            | 5        | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter              | 4        | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 4        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 4        | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller            | 4        | 0.72%   |
| Intel Ethernet Controller I225-V                                   | 4        | 0.72%   |
| Intel Ethernet Connection I217-LM                                  | 4        | 0.72%   |
| BUFFALO 802.11ac WLAN Adapter                                      | 4        | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                   | 4        | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                      | 4        | 0.72%   |
| VIA VT6102/VT6103 [Rhine-II]                                       | 3        | 0.54%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 3        | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 3        | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                    | 3        | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                         | 3        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 3        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                      | 3        | 0.54%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet     | 3        | 0.54%   |
| PLANEX GW-USValue-EZ 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3        | 0.54%   |
| PLANEX GW-USNano2 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 3        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 3        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                              | 3        | 0.54%   |
| Intel Ethernet Connection (12) I219-V                              | 3        | 0.54%   |
| Intel Ethernet Connection (11) I219-V                              | 3        | 0.54%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                    | 3        | 0.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 3        | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]  | 3        | 0.54%   |
| VIA AC'97 Modem Controller                                         | 2        | 0.36%   |
| Realtek Killer E3000 2.5GbE Controller                             | 2        | 0.36%   |
| Realtek 802.11ac NIC                                               | 2        | 0.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2        | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                          | 2        | 0.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2        | 0.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 2        | 0.36%   |
| Nvidia MCP55 Ethernet                                              | 2        | 0.36%   |
| Intel Wireless-AC 9260                                             | 2        | 0.36%   |
| Intel Wireless 7260                                                | 2        | 0.36%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 2        | 0.36%   |
| Intel NM10/ICH7 Family LAN Controller                              | 2        | 0.36%   |
| Intel I210 Gigabit Network Connection                              | 2        | 0.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 2        | 0.36%   |
| Intel 82578DM Gigabit Network Connection                           | 2        | 0.36%   |
| Intel 82576 Gigabit Network Connection                             | 2        | 0.36%   |
| Intel 82567LM-3 Gigabit Network Connection                         | 2        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 40       | 30.77%  |
| Realtek Semiconductor           | 26       | 20%     |
| Qualcomm Atheros                | 16       | 12.31%  |
| BUFFALO                         | 13       | 10%     |
| PLANEX                          | 9        | 6.92%   |
| TP-Link                         | 8        | 6.15%   |
| Broadcom                        | 6        | 4.62%   |
| Elecom                          | 3        | 2.31%   |
| Logitec                         | 2        | 1.54%   |
| Wilocity                        | 1        | 0.77%   |
| Ralink Technology               | 1        | 0.77%   |
| Qualcomm Atheros Communications | 1        | 0.77%   |
| NetGear                         | 1        | 0.77%   |
| NEC Computers                   | 1        | 0.77%   |
| MediaTek                        | 1        | 0.77%   |
| Edimax Technology               | 1        | 0.77%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Desktops | Percent |
|--------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                | 15       | 11.36%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                   | 9        | 6.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 6        | 4.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 6        | 4.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]         | 5        | 3.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 4        | 3.03%   |
| BUFFALO 802.11ac WLAN Adapter                                      | 4        | 3.03%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                             | 3        | 2.27%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                            | 3        | 2.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 3        | 2.27%   |
| PLANEX GW-USValue-EZ 802.11n Wireless Adapter [Realtek RTL8188CUS] | 3        | 2.27%   |
| PLANEX GW-USNano2 802.11n Wireless Adapter [Realtek RTL8188CUS]    | 3        | 2.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 3        | 2.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                 | 3        | 2.27%   |
| Realtek 802.11ac NIC                                               | 2        | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2        | 1.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)     | 2        | 1.52%   |
| Intel Wireless-AC 9260                                             | 2        | 1.52%   |
| Intel Wireless 7260                                                | 2        | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                     | 2        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 2        | 1.52%   |
| Elecom WDC-150SU2M                                                 | 2        | 1.52%   |
| BUFFALO WLI-UC-GNM Wireless LAN Adapter [Ralink RT8070]            | 2        | 1.52%   |
| BUFFALO 802.11 n WLAN                                              | 2        | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                    | 2        | 1.52%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter                 | 1        | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 1        | 0.76%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                              | 1        | 0.76%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                | 1        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1        | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter           | 1        | 0.76%   |
| Realtek RTL8191SEvA Wireless LAN Controller                        | 1        | 0.76%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter            | 1        | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 1        | 0.76%   |
| Realtek RTL8187SE Wireless LAN Controller                          | 1        | 0.76%   |
| Ralink RT5370 Wireless Adapter                                     | 1        | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                    | 1        | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)     | 1        | 0.76%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter         | 1        | 0.76%   |
| PLANEX GW-USNano                                                   | 1        | 0.76%   |
| PLANEX GW-900D                                                     | 1        | 0.76%   |
| PLANEX 802.11n WLAN Adapter                                        | 1        | 0.76%   |
| NetGear WNDA4100 802.11abgn 3x3:3 [Ralink RT3573]                  | 1        | 0.76%   |
| NEC Computers Aterm WL300NU-G                                      | 1        | 0.76%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.76%   |
| Logitec LAN-W150N/U2 Wireless LAN Adapter                          | 1        | 0.76%   |
| Logitec 802.11 n WLAN                                              | 1        | 0.76%   |
| Intel Wireless Gigabit 17265                                       | 1        | 0.76%   |
| Intel Wireless 8265 / 8275                                         | 1        | 0.76%   |
| Intel Wireless 8260                                                | 1        | 0.76%   |
| Intel Centrino Wireless-N 2230                                     | 1        | 0.76%   |
| Intel Centrino Wireless-N 2200                                     | 1        | 0.76%   |
| Elecom 802.11ac WLAN                                               | 1        | 0.76%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]           | 1        | 0.76%   |
| BUFFALO WLI-UC-GNM2 Wireless LAN Adapter [Ralink RT3070]           | 1        | 0.76%   |
| BUFFALO WLI-UC-GN Wireless LAN Adapter [Ralink RT3070]             | 1        | 0.76%   |
| BUFFALO WLI-UC-G301N Wireless LAN Adapter [Ralink RT3072]          | 1        | 0.76%   |
| BUFFALO WLI-UC-G300HP Wireless LAN Adapter                         | 1        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 198      | 49.13%  |
| Intel                            | 136      | 33.75%  |
| Qualcomm Atheros                 | 21       | 5.21%   |
| Broadcom                         | 18       | 4.47%   |
| Marvell Technology Group         | 7        | 1.74%   |
| ASIX Electronics                 | 4        | 0.99%   |
| VIA Technologies                 | 3        | 0.74%   |
| Nvidia                           | 3        | 0.74%   |
| Aquantia                         | 3        | 0.74%   |
| Huawei Technologies              | 2        | 0.5%    |
| Silicon Integrated Systems [SiS] | 1        | 0.25%   |
| Samsung Electronics              | 1        | 0.25%   |
| Netchip Technology               | 1        | 0.25%   |
| JMicron Technology               | 1        | 0.25%   |
| Elecom                           | 1        | 0.25%   |
| Corega K.K.                      | 1        | 0.25%   |
| Broadcom Limited                 | 1        | 0.25%   |
| ADMtek                           | 1        | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 172      | 41.35%  |
| Intel Ethernet Connection (2) I219-V                              | 24       | 5.77%   |
| Intel I211 Gigabit Network Connection                             | 18       | 4.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14       | 3.37%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 3.37%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 3.37%   |
| Intel Ethernet Connection I217-V                                  | 8        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8        | 1.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 5        | 1.2%    |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4        | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4        | 0.96%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 4        | 0.96%   |
| Intel Ethernet Controller I225-V                                  | 4        | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 4        | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4        | 0.96%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 3        | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.72%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 3        | 0.72%   |
| Intel Ethernet Connection (12) I219-V                             | 3        | 0.72%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.72%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 3        | 0.72%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.48%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.48%   |
| Intel NM10/ICH7 Family LAN Controller                             | 2        | 0.48%   |
| Intel I210 Gigabit Network Connection                             | 2        | 0.48%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.48%   |
| Intel 82576 Gigabit Network Connection                            | 2        | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2        | 0.48%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.48%   |
| Intel 82566DM Gigabit Network Connection                          | 2        | 0.48%   |
| Huawei E353/E3131                                                 | 2        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2        | 0.48%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2        | 0.48%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2        | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1        | 0.24%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.24%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.24%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.24%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1        | 0.24%   |
| Nvidia MCP61 Ethernet                                             | 1        | 0.24%   |
| Netchip Linux-USB Ethernet/RNDIS Gadget                           | 1        | 0.24%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1        | 0.24%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1        | 0.24%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1        | 0.24%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 1        | 0.24%   |
| Intel I350 Gigabit Network Connection                             | 1        | 0.24%   |
| Intel Ethernet Controller X550                                    | 1        | 0.24%   |
| Intel Ethernet Connection (7) I219-LM                             | 1        | 0.24%   |
| Intel Ethernet Connection (6) I219-LM                             | 1        | 0.24%   |
| Intel Ethernet Connection (5) I219-LM                             | 1        | 0.24%   |
| Intel Ethernet Connection (2) I218-LM                             | 1        | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 363      | 73.78%  |
| WiFi     | 122      | 24.8%   |
| Modem    | 6        | 1.22%   |
| Unknown  | 1        | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 316      | 81.87%  |
| WiFi     | 70       | 18.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 262      | 71.98%  |
| 2     | 86       | 23.63%  |
| 3     | 13       | 3.57%   |
| 4     | 3        | 0.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 299      | 80.59%  |
| Yes  | 72       | 19.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 48       | 43.64%  |
| Intel                           | 37       | 33.64%  |
| Realtek Semiconductor           | 7        | 6.36%   |
| Qualcomm Atheros Communications | 5        | 4.55%   |
| ASUSTek Computer                | 3        | 2.73%   |
| IMC Networks                    | 2        | 1.82%   |
| Broadcom                        | 2        | 1.82%   |
| Apple                           | 2        | 1.82%   |
| TP-Link                         | 1        | 0.91%   |
| Lite-On Technology              | 1        | 0.91%   |
| Foxconn / Hon Hai               | 1        | 0.91%   |
| Creative Technology             | 1        | 0.91%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 48       | 43.64%  |
| Intel AX200 Bluetooth                               | 14       | 12.73%  |
| Intel Wireless-AC 3168 Bluetooth                    | 9        | 8.18%   |
| Realtek Bluetooth Radio                             | 6        | 5.45%   |
| Intel Bluetooth wireless interface                  | 4        | 3.64%   |
| Intel AX210 Bluetooth                               | 3        | 2.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2        | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2        | 1.82%   |
| Intel Bluetooth Device                              | 2        | 1.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2        | 1.82%   |
| IMC Networks Bluetooth Device                       | 2        | 1.82%   |
| TP-Link UB500 Adapter                               | 1        | 0.91%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1        | 0.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 1        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1        | 0.91%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1        | 0.91%   |
| Lite-On Bluetooth Device                            | 1        | 0.91%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1        | 0.91%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1        | 0.91%   |
| Creative Bluetooth Audio W2                         | 1        | 0.91%   |
| Broadcom HP Portable Bumble Bee                     | 1        | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1        | 0.91%   |
| ASUS Bluetooth Radio                                | 1        | 0.91%   |
| ASUS Bluetooth Device                               | 1        | 0.91%   |
| ASUS BCM20702A0                                     | 1        | 0.91%   |
| Apple Bluetooth USB Host Controller                 | 1        | 0.91%   |
| Apple Bluetooth Host Controller                     | 1        | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 238      | 39.6%   |
| AMD                                             | 151      | 25.12%  |
| Nvidia                                          | 130      | 21.63%  |
| C-Media Electronics                             | 15       | 2.5%    |
| VIA Technologies                                | 9        | 1.5%    |
| Creative Technology                             | 9        | 1.5%    |
| Harman                                          | 7        | 1.16%   |
| Texas Instruments                               | 6        | 1%      |
| JMTek                                           | 4        | 0.67%   |
| Creative Labs                                   | 4        | 0.67%   |
| Yamaha                                          | 3        | 0.5%    |
| Generalplus Technology                          | 3        | 0.5%    |
| TOWA Electronics                                | 2        | 0.33%   |
| Onkyo                                           | 2        | 0.33%   |
| Elitegroup Computer Systems (ECS)               | 2        | 0.33%   |
| ASUSTek Computer                                | 2        | 0.33%   |
| XMOS                                            | 1        | 0.17%   |
| ULi Electronics                                 | 1        | 0.17%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.17%   |
| SteelSeries ApS                                 | 1        | 0.17%   |
| Silicon Integrated Systems [SiS]                | 1        | 0.17%   |
| Sennheiser Communications                       | 1        | 0.17%   |
| Roland                                          | 1        | 0.17%   |
| RME                                             | 1        | 0.17%   |
| Realtek Semiconductor                           | 1        | 0.17%   |
| Philips (or NXP)                                | 1        | 0.17%   |
| Medeli Electronics                              | 1        | 0.17%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.17%   |
| GN Netcom                                       | 1        | 0.17%   |
| Focusrite-Novation                              | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33       | 4.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 32       | 4.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 25       | 3.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22       | 3.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20       | 2.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19       | 2.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 19       | 2.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 18       | 2.6%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 17       | 2.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 16       | 2.31%   |
| AMD FCH Azalia Controller                                                                         | 16       | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15       | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 15       | 2.17%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 15       | 2.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15       | 2.17%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 15       | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14       | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12       | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11       | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10       | 1.45%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 9        | 1.3%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 9        | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 8        | 1.16%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8        | 1.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 7        | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 7        | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7        | 1.01%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 6        | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6        | 0.87%   |
| Harman JBL Pebbles                                                                                | 6        | 0.87%   |
| AMD Navi 10 HDMI Audio                                                                            | 6        | 0.87%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6        | 0.87%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 6        | 0.87%   |
| VIA Technologies VT1720/24 [Envy24PT/HT] PCI Multi-Channel Audio Controller                       | 5        | 0.72%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 5        | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 5        | 0.72%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 5        | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 5        | 0.72%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4        | 0.58%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 4        | 0.58%   |
| Nvidia GM200 High Definition Audio                                                                | 4        | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4        | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4        | 0.58%   |
| JMTek USB PnP Audio Device                                                                        | 4        | 0.58%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 4        | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4        | 0.58%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4        | 0.58%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 4        | 0.58%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4        | 0.58%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 4        | 0.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4        | 0.58%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 3        | 0.43%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3        | 0.43%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3        | 0.43%   |
| Intel Comet Lake PCH cAVS                                                                         | 3        | 0.43%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3        | 0.43%   |
| Intel Audio device                                                                                | 3        | 0.43%   |
| Generalplus Technology IMYB 7.1 Channel                                                           | 3        | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 19       | 14.29%  |
| Crucial             | 19       | 14.29%  |
| Unknown             | 18       | 13.53%  |
| Corsair             | 10       | 7.52%   |
| G.Skill             | 9        | 6.77%   |
| Team                | 8        | 6.02%   |
| A-DATA Technology   | 8        | 6.02%   |
| Samsung Electronics | 7        | 5.26%   |
| Micron Technology   | 6        | 4.51%   |
| SK hynix            | 5        | 3.76%   |
| Silicon Power       | 4        | 3.01%   |
| Panram              | 4        | 3.01%   |
| Nanya Technology    | 4        | 3.01%   |
| KLEVV               | 3        | 2.26%   |
| Transcend           | 2        | 1.5%    |
| SanMax              | 2        | 1.5%    |
| V-Color             | 1        | 0.75%   |
| Unknown (8AD3)      | 1        | 0.75%   |
| Kingmax             | 1        | 0.75%   |
| Elpida              | 1        | 0.75%   |
| Century Micro       | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM SDRAM                         | 3        | 2.21%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 3        | 2.21%   |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s     | 3        | 2.21%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 2667MT/s        | 2        | 1.47%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s           | 2        | 1.47%   |
| Nanya RAM M2X4G64CB8HG9N-DG 4GB DIMM DDR3 1600MT/s           | 2        | 1.47%   |
| KLEVV RAM KD48GU881-26N190A 8GB DIMM DDR4 2667MT/s           | 2        | 1.47%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s       | 2        | 1.47%   |
| Kingston RAM 9905622-057.A00G 4GB DIMM DDR4 2133MT/s         | 2        | 1.47%   |
| G.Skill RAM F4-2666C19-8GNT 8GB DIMM DDR4 2667MT/s           | 2        | 1.47%   |
| G.Skill RAM F3-2400C10-4GTX 4GB DIMM DDR3 2400MT/s           | 2        | 1.47%   |
| Crucial RAM CT16G4DFD8266.C16FD1 16GB DIMM DDR4 2667MT/s     | 2        | 1.47%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s       | 2        | 1.47%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s           | 1        | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                    | 1        | 0.74%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1        | 0.74%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                 | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                 | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 1        | 0.74%   |
| Unknown RAM Module 2048MB DIMM DDR2                          | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM SDRAM 533MT/s                    | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM 800MT/s                          | 1        | 0.74%   |
| Unknown RAM Module 16384MB DIMM DDR3 1866MT/s                | 1        | 0.74%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                  | 1        | 0.74%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s                   | 1        | 0.74%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                       | 1        | 0.74%   |
| Unknown (8AD3) RAM CIR-S4DUSW2616G 16GB DIMM DDR4 2667MT/s   | 1        | 0.74%   |
| Transcend RAM JM2666HLH-4G 4096MB DIMM DDR4 2666MT/s         | 1        | 0.74%   |
| Transcend RAM JM1600KSN-4G 4096MB SODIMM DDR3 1600MT/s       | 1        | 0.74%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s           | 1        | 0.74%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s           | 1        | 0.74%   |
| Team RAM Module 2048MB DIMM DDR2 800MT/s                     | 1        | 0.74%   |
| Team RAM Elite-2400 8192MB DIMM DDR4 2400MT/s                | 1        | 0.74%   |
| SK hynix RAM HMT41GU7BFR8A-PB 8GB DIMM DDR3 1600MT/s         | 1        | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 0.74%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s         | 1        | 0.74%   |
| SK hynix RAM HMA81GU6DJR8N-XN 8192MB DIMM DDR4 3200MT/s      | 1        | 0.74%   |
| SK hynix RAM HMA81GR7CJR8N-VK 8192MB DIMM DDR4 2666MT/s      | 1        | 0.74%   |
| Silicon Power RAM SP016GBSFU320F02 16GB SODIMM DDR4 3200MT/s | 1        | 0.74%   |
| Silicon Power RAM SP008GBLFU240B02 8GB DIMM DDR4 2400MT/s    | 1        | 0.74%   |
| Silicon Power RAM Module 8GB DIMM DDR4 2400MT/s              | 1        | 0.74%   |
| Silicon Power RAM DCLT8GN128S 8GB DIMM DDR3 1600MT/s         | 1        | 0.74%   |
| Silicon Power RAM DBLT4GN568S 4GB DIMM 1333MT/s              | 1        | 0.74%   |
| SanMax RAM SMD-4G68H1P-16K 4GB DIMM DDR3 1600MT/s            | 1        | 0.74%   |
| SanMax RAM Module 8192MB DIMM DDR4 2667MT/s                  | 1        | 0.74%   |
| Samsung RAM Module 8GB DIMM DDR4 2667MT/s                    | 1        | 0.74%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1        | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 1        | 0.74%   |
| Samsung RAM M391B5773DH0-CK0 2048MB DIMM DDR3 1600MT/s       | 1        | 0.74%   |
| Samsung RAM M391B5173QH0-YK0 4GB DIMM DDR3 1600MT/s          | 1        | 0.74%   |
| Samsung RAM M378B5773CH0-CK0 2GB DIMM DDR3 1600MT/s          | 1        | 0.74%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1866MT/s       | 1        | 0.74%   |
| Panram RAM W4U2666PS-8GC19 8GB DIMM DDR4 2666MT/s            | 1        | 0.74%   |
| Panram RAM PUD32133C104G2PSB 4GB DIMM DDR3 1600MT/s          | 1        | 0.74%   |
| Panram RAM PUD31333C94GVS 4096MB DIMM DDR3 667MT/s           | 1        | 0.74%   |
| Panram RAM PUD31333C92G2VS 2GB DIMM DDR3 1333MT/s            | 1        | 0.74%   |
| Nanya RAM M2X8G64CB8HD9N-DG 8192MB DIMM DDR3 800MT/s         | 1        | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 72       | 57.6%   |
| DDR3    | 38       | 30.4%   |
| SDRAM   | 7        | 5.6%    |
| DDR2    | 4        | 3.2%    |
| Unknown | 3        | 2.4%    |
| DDR     | 1        | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 119      | 95.97%  |
| SODIMM | 4        | 3.23%   |
| RIMM   | 1        | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 46       | 36.22%  |
| 16384 | 30       | 23.62%  |
| 4096  | 28       | 22.05%  |
| 2048  | 11       | 8.66%   |
| 32768 | 7        | 5.51%   |
| 1024  | 5        | 3.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 2667    | 21       | 16.15%  |
| 1600    | 21       | 16.15%  |
| 3200    | 15       | 11.54%  |
| 2400    | 11       | 8.46%   |
| 3600    | 8        | 6.15%   |
| 2133    | 8        | 6.15%   |
| 1333    | 7        | 5.38%   |
| 2666    | 6        | 4.62%   |
| 800     | 6        | 4.62%   |
| Unknown | 5        | 3.85%   |
| 2933    | 3        | 2.31%   |
| 1800    | 3        | 2.31%   |
| 1866    | 2        | 1.54%   |
| 667     | 2        | 1.54%   |
| 533     | 2        | 1.54%   |
| 4133    | 1        | 0.77%   |
| 3800    | 1        | 0.77%   |
| 3400    | 1        | 0.77%   |
| 3100    | 1        | 0.77%   |
| 3067    | 1        | 0.77%   |
| 3007    | 1        | 0.77%   |
| 3000    | 1        | 0.77%   |
| 2733    | 1        | 0.77%   |
| 1867    | 1        | 0.77%   |
| 1066    | 1        | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 3        | 37.5%   |
| Seiko Epson        | 2        | 25%     |
| Brother Industries | 2        | 25%     |
| Hewlett-Packard    | 1        | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Desktops | Percent |
|-------------------------------|----------|---------|
| Seiko Epson PX-045A Series    | 1        | 12.5%   |
| Seiko Epson EP-306 Series     | 1        | 12.5%   |
| HP ENVY 5000 series           | 1        | 12.5%   |
| Canon PIXMA iX6850 Printer    | 1        | 12.5%   |
| Canon PIXMA iP4600 Printer    | 1        | 12.5%   |
| Canon iP2700 series           | 1        | 12.5%   |
| Brother HL-L2360D series      | 1        | 12.5%   |
| Brother HL-1440 Laser Printer | 1        | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Seiko Epson | 1        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 9        | 23.08%  |
| Sunplus Innovation Technology | 3        | 7.69%   |
| Microsoft                     | 3        | 7.69%   |
| Elecom                        | 3        | 7.69%   |
| Microdia                      | 2        | 5.13%   |
| Generalplus Technology        | 2        | 5.13%   |
| WaveRider Communications      | 1        | 2.56%   |
| Syntek                        | 1        | 2.56%   |
| SHENZHEN EMEET TECHNOLOGY     | 1        | 2.56%   |
| Samsung Electronics           | 1        | 2.56%   |
| Ruision                       | 1        | 2.56%   |
| OmniVision Technologies       | 1        | 2.56%   |
| MacroSilicon                  | 1        | 2.56%   |
| Jieli Technology              | 1        | 2.56%   |
| Huawei Technologies           | 1        | 2.56%   |
| HD USB Camera                 | 1        | 2.56%   |
| GEMBIRD                       | 1        | 2.56%   |
| Etron Technology              | 1        | 2.56%   |
| Cubeternet                    | 1        | 2.56%   |
| Chicony Electronics           | 1        | 2.56%   |
| BUFFALO                       | 1        | 2.56%   |
| Apple                         | 1        | 2.56%   |
| Alcor Micro                   | 1        | 2.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Logitech Webcam C270                           | 3        | 7.5%    |
| Microdia Webcam Vitade AF                      | 2        | 5%      |
| Generalplus 808 Camera                         | 2        | 5%      |
| Elecom UCAM-DLE300T                            | 2        | 5%      |
| WaveRider USB 2.0 Camera                       | 1        | 2.5%    |
| Syntek BUFFALO BSW20K06H USB PC Camera         | 1        | 2.5%    |
| Sunplus SPCA2281 Web Camera                    | 1        | 2.5%    |
| Sunplus FHD Camera Microphone                  | 1        | 2.5%    |
| Sunplus FHD Camera                             | 1        | 2.5%    |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960 | 1        | 2.5%    |
| Samsung Galaxy series, misc. (MTP mode)        | 1        | 2.5%    |
| Ruision UVC Camera                             | 1        | 2.5%    |
| OmniVision OV511+ Webcam                       | 1        | 2.5%    |
| Microsoft MicrosoftÂ LifeCam Studio           | 1        | 2.5%    |
| Microsoft LifeCam HD-3000                      | 1        | 2.5%    |
| Microsoft LifeCam Cinema                       | 1        | 2.5%    |
| MacroSilicon MiraBox Capture                   | 1        | 2.5%    |
| Logitech Webcam C310                           | 1        | 2.5%    |
| Logitech QuickCam Orbit/Sphere AF              | 1        | 2.5%    |
| Logitech HD Webcam C910                        | 1        | 2.5%    |
| Logitech HD Webcam C615                        | 1        | 2.5%    |
| Logitech C922 Pro Stream Webcam                | 1        | 2.5%    |
| Logitech BRIO Ultra HD Webcam                  | 1        | 2.5%    |
| Jieli USB PHY 2.0                              | 1        | 2.5%    |
| Huawei UVC Camera                              | 1        | 2.5%    |
| HD USB Camera HD USB Camera                    | 1        | 2.5%    |
| GEMBIRD USB2.0 PC CAMERA                       | 1        | 2.5%    |
| Etron BUFFALO BSW32KM03 USB PC Camera          | 1        | 2.5%    |
| Elecom UCAM-DLB200TA                           | 1        | 2.5%    |
| Cubeternet WebCam                              | 1        | 2.5%    |
| Chicony FJ Camera                              | 1        | 2.5%    |
| BUFFALO USB 2.0 Camera                         | 1        | 2.5%    |
| BUFFALO BUFFALO BSWHD06M USB Camera            | 1        | 2.5%    |
| Apple iPhone 5/5C/5S/6/SE                      | 1        | 2.5%    |
| Alcor Micro USB 2.0 PC Camera                  | 1        | 2.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 2        | 50%     |
| Elan Microelectronics | 2        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                 | Desktops | Percent |
|---------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader | 2        | 50%     |
| Elan ELAN:Fingerprint                 | 2        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| SCM Microsystems | 2        | 66.67%  |
| Alcor Micro      | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 2        | 66.67%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 309      | 83.74%  |
| 1     | 53       | 14.36%  |
| 2     | 6        | 1.63%   |
| 8     | 1        | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 17       | 24.29%  |
| Graphics card            | 13       | 18.57%  |
| Multimedia controller    | 9        | 12.86%  |
| Unassigned class         | 6        | 8.57%   |
| Communication controller | 6        | 8.57%   |
| Fingerprint reader       | 4        | 5.71%   |
| Sound                    | 3        | 4.29%   |
| Modem                    | 3        | 4.29%   |
| Chipcard                 | 2        | 2.86%   |
| Bluetooth                | 2        | 2.86%   |
| Storage/nvme             | 1        | 1.43%   |
| Storage/ata              | 1        | 1.43%   |
| Network                  | 1        | 1.43%   |
| Net/ethernet             | 1        | 1.43%   |
| Camera                   | 1        | 1.43%   |

