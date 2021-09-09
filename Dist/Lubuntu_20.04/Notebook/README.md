Lubuntu 20.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=lubuntu-20.04

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Notebook      | NL40_50GU                   | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| Dell          | Latitude E5450              | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | RV415/RV515                 | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [e09b0ac6cf](https://linux-hardware.org/?probe=e09b0ac6cf) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [caa1dadc98](https://linux-hardware.org/?probe=caa1dadc98) | Jun 29, 2021 |
| Samsung       | RV415/RV515                 | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| Notebook      | NHxxRZQ                     | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Samsung       | RC512                       | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | Modern 15 A10M              | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| Dell          | Latitude D630               | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Acer          | Aspire 5715Z                | [aa3fceee37](https://linux-hardware.org/?probe=aa3fceee37) | May 17, 2021 |
| Toshiba       | Satellite L70-B             | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Sony          | VPCSB1V9E                   | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| HP            | Notebook                    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| LG Electro... | S425-L.BC22P1               | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| Lenovo        | G460 20041                  | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| Sony          | VGN-SZ670AN                 | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Inspiron N4020              | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Dell          | Inspiron N4020              | [f03d856fe1](https://linux-hardware.org/?probe=f03d856fe1) | Apr 20, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| LG Electro... | S425-L.BC22P1               | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Toshiba       | Satellite C70D-B            | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Toshiba       | Satellite L70-B             | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| Toshiba       | Satellite L70-B             | [e366c8c206](https://linux-hardware.org/?probe=e366c8c206) | Mar 24, 2021 |
| Toshiba       | Satellite L70-B             | [0baf745232](https://linux-hardware.org/?probe=0baf745232) | Mar 21, 2021 |
| Toshiba       | Satellite L70-B             | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Lenovo        | S10-3                       | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | XPS 15Z                     | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| ASUSTek       | P53E                        | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Toshiba       | Satellite A660              | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Itautec       | Infoway w7430               | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | ProBook 440 G6              | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [304fa83224](https://linux-hardware.org/?probe=304fa83224) | Jan 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [09c2da07b2](https://linux-hardware.org/?probe=09c2da07b2) | Jan 21, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | G50-45 80E3                 | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Toshiba       | Satellite C55D-A            | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| ASUSTek       | K53SD                       | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Gateway       | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Toshiba       | Satellite C55D-A            | [1c0400a8c0](https://linux-hardware.org/?probe=1c0400a8c0) | Dec 10, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Panasonic     | CF-52PGNBE2M                | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| HP            | Presario F700 (KA698EA#A... | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Positivo      | S14BW01                     | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| Gateway       | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Unknown       | Unknown                     | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Samsung       | R530/R730/P530              | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| Acer          | AOD257                      | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| ASUSTek       | E200HA                      | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Extensa 4620                | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| Acer          | Aspire E1-532P              | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion dv6                | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| HP            | Unknown                     | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| Dell          | Latitude D630               | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| ASUSTek       | X202EP                      | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Dell          | Inspiron 1440               | [c30f194de1](https://linux-hardware.org/?probe=c30f194de1) | Sep 22, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | X202EP                      | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| Acer          | Aspire 3050                 | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| Acer          | Aspire 3050                 | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Apple         | MacBookPro10,2              | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Google        | Gandof                      | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| Acer          | Aspire ES1-522              | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Dell          | XPS 13 9300                 | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5e37d8f34b](https://linux-hardware.org/?probe=5e37d8f34b) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [607ce70f10](https://linux-hardware.org/?probe=607ce70f10) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8dcd639b58](https://linux-hardware.org/?probe=8dcd639b58) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50f1173d1b](https://linux-hardware.org/?probe=50f1173d1b) | Aug 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [95dde54ab4](https://linux-hardware.org/?probe=95dde54ab4) | Aug 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1c32470733](https://linux-hardware.org/?probe=1c32470733) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| ASUSTek       | K50C                        | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| Apple         | MacBookPro10,2              | [29919d9aa9](https://linux-hardware.org/?probe=29919d9aa9) | Jul 30, 2020 |
| HP            | ProBook 445 G7              | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Acer          | V5-171                      | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| Positivo      | H14BT58                     | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| Apple         | MacBookPro10,2              | [a10d8d5d4f](https://linux-hardware.org/?probe=a10d8d5d4f) | Jul 22, 2020 |
| Apple         | MacBookPro10,2              | [d9470e64f2](https://linux-hardware.org/?probe=d9470e64f2) | Jul 22, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| Apple         | MacBookPro10,2              | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| Dell          | Studio 1555                 | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | Q302LA                      | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| Acer          | Swift SF314-52G             | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Dell          | XPS 13 7390                 | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| HP            | Compaq 615                  | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| Apple         | MacBookPro8,1               | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Acer          | Aspire A515-51G             | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| HP            | Compaq Presario C700        | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| Acer          | Aspire 5734Z                | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| HP            | Pavilion 15                 | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| HP            | Pavilion dv5                | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Positivo      | S14CT01                     | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| ASUSTek       | 1015B                       | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| ASUSTek       | 1015B                       | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| Acer          | Aspire E1-531               | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [acacfa8d27](https://linux-hardware.org/?probe=acacfa8d27) | May 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| Packard Be... | EN Butterfly s              | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| Dixonsxp      | Unknown                     | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| HP            | Notebook                    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Dixonsxp      | Unknown                     | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Apple         | MacBookPro9,2               | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [2e3821b18f](https://linux-hardware.org/?probe=2e3821b18f) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.4.0-42-generic           | 21        | 11.23%  |
| 5.4.0-52-generic           | 13        | 6.95%   |
| 5.4.0-26-generic           | 9         | 4.81%   |
| 5.4.0-48-generic           | 8         | 4.28%   |
| 5.4.0-47-generic           | 7         | 3.74%   |
| 5.4.0-40-generic           | 7         | 3.74%   |
| 5.4.0-65-generic           | 6         | 3.21%   |
| 5.4.0-29-generic           | 6         | 3.21%   |
| 5.4.0-51-generic           | 5         | 2.67%   |
| 5.4.0-33-generic           | 5         | 2.67%   |
| 5.8.0-53-generic           | 4         | 2.14%   |
| 5.4.0-72-generic           | 4         | 2.14%   |
| 5.4.0-58-generic           | 4         | 2.14%   |
| 5.4.0-56-generic           | 4         | 2.14%   |
| 5.4.0-54-generic           | 4         | 2.14%   |
| 5.4.0-45-generic           | 4         | 2.14%   |
| 5.4.0-37-generic           | 4         | 2.14%   |
| 5.8.0-49-generic           | 3         | 1.6%    |
| 5.8.0-45-generic           | 3         | 1.6%    |
| 5.8.0-41-generic           | 3         | 1.6%    |
| 5.4.0-74-generic           | 3         | 1.6%    |
| 5.4.0-73-generic           | 3         | 1.6%    |
| 5.4.0-62-generic           | 3         | 1.6%    |
| 5.4.0-60-generic           | 3         | 1.6%    |
| 5.4.0-59-generic           | 3         | 1.6%    |
| 5.4.0-31-generic           | 3         | 1.6%    |
| 5.11.0-25-generic          | 3         | 1.6%    |
| 5.8.0-63-generic           | 2         | 1.07%   |
| 5.8.0-59-generic           | 2         | 1.07%   |
| 5.8.0-55-generic           | 2         | 1.07%   |
| 5.8.0-48-generic           | 2         | 1.07%   |
| 5.8.0-43-generic           | 2         | 1.07%   |
| 5.4.0-80-generic           | 2         | 1.07%   |
| 5.4.0-70-generic           | 2         | 1.07%   |
| 5.4.0-67-generic           | 2         | 1.07%   |
| 5.4.0-66-generic           | 2         | 1.07%   |
| 5.4.0-39-generic           | 2         | 1.07%   |
| 5.11.0-27-generic          | 2         | 1.07%   |
| 5.9.0-050900rc6-lowlatency | 1         | 0.53%   |
| 5.8.0-50-generic           | 1         | 0.53%   |
| 5.8.0-44-generic           | 1         | 0.53%   |
| 5.8.0-29-generic           | 1         | 0.53%   |
| 5.8.0-050800-generic       | 1         | 0.53%   |
| 5.7.9-050709-generic       | 1         | 0.53%   |
| 5.6.0-kali2-amd64          | 1         | 0.53%   |
| 5.5.2-050502-generic       | 1         | 0.53%   |
| 5.4.0-81-generic           | 1         | 0.53%   |
| 5.4.0-77-generic           | 1         | 0.53%   |
| 5.4.0-71-generic           | 1         | 0.53%   |
| 5.4.0-65-lowlatency        | 1         | 0.53%   |
| 5.4.0-64-lowlatency        | 1         | 0.53%   |
| 5.4.0-64-generic           | 1         | 0.53%   |
| 5.4.0-52-lowlatency        | 1         | 0.53%   |
| 5.4.0-42-lowlatency        | 1         | 0.53%   |
| 5.4.0-28-lowlatency        | 1         | 0.53%   |
| 5.4.0-21-generic           | 1         | 0.53%   |
| 5.4.0-14-generic           | 1         | 0.53%   |
| 5.10.0-051000-generic      | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 132       | 78.57%  |
| 5.8.0   | 26        | 15.48%  |
| 5.11.0  | 5         | 2.98%   |
| 5.9.0   | 1         | 0.6%    |
| 5.7.9   | 1         | 0.6%    |
| 5.6.0   | 1         | 0.6%    |
| 5.5.2   | 1         | 0.6%    |
| 5.10.0  | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 132       | 78.57%  |
| 5.8     | 26        | 15.48%  |
| 5.11    | 5         | 2.98%   |
| 5.9     | 1         | 0.6%    |
| 5.7     | 1         | 0.6%    |
| 5.6     | 1         | 0.6%    |
| 5.5     | 1         | 0.6%    |
| 5.10    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 167       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| LXQt     | 160       | 95.81%  |
| LXDE     | 2         | 1.2%    |
| GNOME    | 2         | 1.2%    |
| MATE     | 1         | 0.6%    |
| KDE5     | 1         | 0.6%    |
| Cinnamon | 1         | 0.6%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 157       | 94.01%  |
| Tty     | 8         | 4.79%   |
| Wayland | 2         | 1.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 74        | 43.79%  |
| Unknown | 72        | 42.6%   |
| GDM     | 12        | 7.1%    |
| TDM     | 11        | 6.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 56        | 33.53%  |
| pt_BR | 18        | 10.78%  |
| fr_FR | 14        | 8.38%   |
| en_GB | 11        | 6.59%   |
| it_IT | 8         | 4.79%   |
| de_DE | 8         | 4.79%   |
| C     | 7         | 4.19%   |
| ru_RU | 6         | 3.59%   |
| es_ES | 5         | 2.99%   |
| pl_PL | 4         | 2.4%    |
| en_AU | 4         | 2.4%    |
| es_AR | 3         | 1.8%    |
| en_IE | 3         | 1.8%    |
| fr_CH | 2         | 1.2%    |
| en_IN | 2         | 1.2%    |
| ru_UA | 1         | 0.6%    |
| nl_NL | 1         | 0.6%    |
| nl_BE | 1         | 0.6%    |
| lt_LT | 1         | 0.6%    |
| ja_JP | 1         | 0.6%    |
| hu_HU | 1         | 0.6%    |
| fr_BE | 1         | 0.6%    |
| es_UY | 1         | 0.6%    |
| es_MX | 1         | 0.6%    |
| es_CL | 1         | 0.6%    |
| en_ZA | 1         | 0.6%    |
| en_SG | 1         | 0.6%    |
| en_PH | 1         | 0.6%    |
| en_DE | 1         | 0.6%    |
| en_CA | 1         | 0.6%    |
| el_GR | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 88        | 52.69%  |
| EFI  | 79        | 47.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 154       | 92.22%  |
| Overlay | 9         | 5.39%   |
| Btrfs   | 4         | 2.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 42.01%  |
| GPT     | 59        | 34.91%  |
| MBR     | 39        | 23.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 153       | 91.07%  |
| Yes       | 15        | 8.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 124       | 73.81%  |
| Yes       | 44        | 26.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 33        | 19.76%  |
| Hewlett-Packard     | 29        | 17.37%  |
| Dell                | 20        | 11.98%  |
| ASUSTek Computer    | 16        | 9.58%   |
| Acer                | 15        | 8.98%   |
| Toshiba             | 10        | 5.99%   |
| Samsung Electronics | 7         | 4.19%   |
| Notebook            | 5         | 2.99%   |
| Positivo            | 4         | 2.4%    |
| Apple               | 4         | 2.4%    |
| MSI                 | 3         | 1.8%    |
| Google              | 3         | 1.8%    |
| Fujitsu             | 3         | 1.8%    |
| Sony                | 2         | 1.2%    |
| Packard Bell        | 2         | 1.2%    |
| Timi                | 1         | 0.6%    |
| Panasonic           | 1         | 0.6%    |
| Mediacom            | 1         | 0.6%    |
| LAMINA              | 1         | 0.6%    |
| Itautec             | 1         | 0.6%    |
| HUAWEI              | 1         | 0.6%    |
| GTZS                | 1         | 0.6%    |
| Gateway             | 1         | 0.6%    |
| Dixonsxp            | 1         | 0.6%    |
| Digibras            | 1         | 0.6%    |
| Unknown             | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Notebook                           | 4         | 2.4%    |
| Unknown                               | 4         | 2.4%    |
| Positivo H14BT58                      | 2         | 1.2%    |
| Lenovo IdeaPad 320-15AST 80XV         | 2         | 1.2%    |
| Dell Latitude D630                    | 2         | 1.2%    |
| Toshiba Satellite Pro U400            | 1         | 0.6%    |
| Toshiba Satellite L840                | 1         | 0.6%    |
| Toshiba Satellite L70-B               | 1         | 0.6%    |
| Toshiba Satellite L305                | 1         | 0.6%    |
| Toshiba Satellite C855D               | 1         | 0.6%    |
| Toshiba Satellite C70D-B              | 1         | 0.6%    |
| Toshiba Satellite C55D-A              | 1         | 0.6%    |
| Toshiba Satellite A660                | 1         | 0.6%    |
| Toshiba Satellite A205                | 1         | 0.6%    |
| Toshiba NB510                         | 1         | 0.6%    |
| Timi TM1612                           | 1         | 0.6%    |
| Sony VPCSB1V9E                        | 1         | 0.6%    |
| Sony VGN-SZ670AN                      | 1         | 0.6%    |
| Samsung RV415/RV515                   | 1         | 0.6%    |
| Samsung RV410/RV510/S3510/E3510       | 1         | 0.6%    |
| Samsung RV408/RV508                   | 1         | 0.6%    |
| Samsung RC512                         | 1         | 0.6%    |
| Samsung R530/R730/P530                | 1         | 0.6%    |
| Samsung R520/R522/R620                | 1         | 0.6%    |
| Samsung 300E4M/300E4S/300E4L          | 1         | 0.6%    |
| Positivo S14CT01                      | 1         | 0.6%    |
| Positivo S14BW01                      | 1         | 0.6%    |
| Panasonic CF-52PGNBE2M                | 1         | 0.6%    |
| Packard Bell EN Butterfly s           | 1         | 0.6%    |
| Packard Bell EasyNote_ST85-M-010FR    | 1         | 0.6%    |
| Notebook W740SU                       | 1         | 0.6%    |
| Notebook W54_W94_W955TU,-T,-C         | 1         | 0.6%    |
| Notebook W54_55SU1,SUW                | 1         | 0.6%    |
| Notebook NL40_50GU                    | 1         | 0.6%    |
| Notebook NHxxRZQ                      | 1         | 0.6%    |
| MSI U180                              | 1         | 0.6%    |
| MSI Modern 15 A10M                    | 1         | 0.6%    |
| MSI GL65 9SDK                         | 1         | 0.6%    |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 0.6%    |
| Lenovo Z50-70 20354                   | 1         | 0.6%    |
| Lenovo Y50-70 20378                   | 1         | 0.6%    |
| Lenovo ThinkPad X220 Tablet 42982NM   | 1         | 0.6%    |
| Lenovo ThinkPad W500 406138U          | 1         | 0.6%    |
| Lenovo ThinkPad T540p 20BFS0WP00      | 1         | 0.6%    |
| Lenovo ThinkPad T460s 20FAS8CH00      | 1         | 0.6%    |
| Lenovo ThinkPad T460s 20FAA08600      | 1         | 0.6%    |
| Lenovo ThinkPad T430 2349G7G          | 1         | 0.6%    |
| Lenovo ThinkPad T410 2522DS2          | 1         | 0.6%    |
| Lenovo ThinkPad T400 2768AA6          | 1         | 0.6%    |
| Lenovo ThinkPad T14 Gen 1 20UDCTO1WW  | 1         | 0.6%    |
| Lenovo ThinkPad R400 2786W1L          | 1         | 0.6%    |
| Lenovo ThinkPad Mini10 3507A31        | 1         | 0.6%    |
| Lenovo ThinkPad L460 20FVS20700       | 1         | 0.6%    |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00  | 1         | 0.6%    |
| Lenovo ThinkBook 15-IML 20RW          | 1         | 0.6%    |
| Lenovo IdeaPad Y550 4186              | 1         | 0.6%    |
| Lenovo IdeaPad L340-17API 81LY        | 1         | 0.6%    |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 1         | 0.6%    |
| Lenovo IdeaPad C340-14API 81N6        | 1         | 0.6%    |
| Lenovo IdeaPad 5 15ARE05 81YQ         | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 7.78%   |
| Lenovo IdeaPad         | 13        | 7.78%   |
| Acer Aspire            | 11        | 6.59%   |
| Toshiba Satellite      | 9         | 5.39%   |
| HP ProBook             | 8         | 4.79%   |
| HP Pavilion            | 8         | 4.79%   |
| Dell Inspiron          | 8         | 4.79%   |
| HP Compaq              | 5         | 2.99%   |
| HP Notebook            | 4         | 2.4%    |
| Dell Latitude          | 4         | 2.4%    |
| ASUS VivoBook          | 4         | 2.4%    |
| Unknown                | 4         | 2.4%    |
| Dell XPS               | 3         | 1.8%    |
| Dell Vostro            | 3         | 1.8%    |
| Positivo H14BT58       | 2         | 1.2%    |
| Notebook W54           | 2         | 1.2%    |
| Toshiba NB510          | 1         | 0.6%    |
| Timi TM1612            | 1         | 0.6%    |
| Sony VPCSB1V9E         | 1         | 0.6%    |
| Sony VGN-SZ670AN       | 1         | 0.6%    |
| Samsung RV415          | 1         | 0.6%    |
| Samsung RV410          | 1         | 0.6%    |
| Samsung RV408          | 1         | 0.6%    |
| Samsung RC512          | 1         | 0.6%    |
| Samsung R530           | 1         | 0.6%    |
| Samsung R520           | 1         | 0.6%    |
| Samsung 300E4M         | 1         | 0.6%    |
| Positivo S14CT01       | 1         | 0.6%    |
| Positivo S14BW01       | 1         | 0.6%    |
| Panasonic CF-52PGNBE2M | 1         | 0.6%    |
| Packard Bell EN        | 1         | 0.6%    |
| Packard Bell EasyNote  | 1         | 0.6%    |
| Notebook W740SU        | 1         | 0.6%    |
| Notebook NL40          | 1         | 0.6%    |
| Notebook NHxxRZQ       | 1         | 0.6%    |
| MSI U180               | 1         | 0.6%    |
| MSI Modern             | 1         | 0.6%    |
| MSI GL65               | 1         | 0.6%    |
| Mediacom SmartBook     | 1         | 0.6%    |
| Lenovo Z50-70          | 1         | 0.6%    |
| Lenovo Y50-70          | 1         | 0.6%    |
| Lenovo ThinkBook       | 1         | 0.6%    |
| Lenovo G70-80          | 1         | 0.6%    |
| Lenovo G575            | 1         | 0.6%    |
| Lenovo G50-45          | 1         | 0.6%    |
| Lenovo G40-30          | 1         | 0.6%    |
| LAMINA T-1012B         | 1         | 0.6%    |
| Itautec Infoway        | 1         | 0.6%    |
| HUAWEI KPL-W0X         | 1         | 0.6%    |
| HP Presario            | 1         | 0.6%    |
| HP G42                 | 1         | 0.6%    |
| HP EliteBook           | 1         | 0.6%    |
| Google Wolf            | 1         | 0.6%    |
| Google Kohaku          | 1         | 0.6%    |
| Google Gandof          | 1         | 0.6%    |
| Gateway NE56R          | 1         | 0.6%    |
| Fujitsu LIFEBOOK       | 1         | 0.6%    |
| Fujitsu FMVNFA50       | 1         | 0.6%    |
| Fujitsu FMVA05008      | 1         | 0.6%    |
| Digibras NH4CU03       | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 14.97%  |
| 2012 | 18        | 10.78%  |
| 2010 | 16        | 9.58%   |
| 2020 | 14        | 8.38%   |
| 2014 | 13        | 7.78%   |
| 2008 | 12        | 7.19%   |
| 2016 | 11        | 6.59%   |
| 2015 | 11        | 6.59%   |
| 2011 | 10        | 5.99%   |
| 2017 | 7         | 4.19%   |
| 2009 | 7         | 4.19%   |
| 2007 | 7         | 4.19%   |
| 2018 | 6         | 3.59%   |
| 2013 | 6         | 3.59%   |
| 2021 | 2         | 1.2%    |
| 2006 | 2         | 1.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 167       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 153       | 91.07%  |
| Enabled  | 15        | 8.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 98.2%   |
| Yes  | 3         | 1.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 54        | 32.14%  |
| 4.01-8.0   | 43        | 25.6%   |
| 1.01-2.0   | 28        | 16.67%  |
| 8.01-16.0  | 20        | 11.9%   |
| 16.01-24.0 | 13        | 7.74%   |
| 2.01-3.0   | 6         | 3.57%   |
| 32.01-64.0 | 3         | 1.79%   |
| 0.51-1.0   | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 85        | 47.49%  |
| 0.51-1.0  | 31        | 17.32%  |
| 2.01-3.0  | 24        | 13.41%  |
| 4.01-8.0  | 19        | 10.61%  |
| 3.01-4.0  | 14        | 7.82%   |
| 0.01-0.5  | 4         | 2.23%   |
| 8.01-16.0 | 2         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 125       | 74.4%   |
| 2      | 39        | 23.21%  |
| 3      | 2         | 1.19%   |
| 4      | 1         | 0.6%    |
| 0      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 51.79%  |
| Yes       | 81        | 48.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 87.43%  |
| No        | 21        | 12.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 96.41%  |
| No        | 6         | 3.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 60.23%  |
| No        | 68        | 39.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 24        | 14.29%  |
| Brazil       | 23        | 13.69%  |
| France       | 15        | 8.93%   |
| Italy        | 13        | 7.74%   |
| Germany      | 11        | 6.55%   |
| Russia       | 10        | 5.95%   |
| UK           | 8         | 4.76%   |
| Poland       | 6         | 3.57%   |
| Spain        | 5         | 2.98%   |
| Ukraine      | 4         | 2.38%   |
| Australia    | 4         | 2.38%   |
| Netherlands  | 3         | 1.79%   |
| Ireland      | 3         | 1.79%   |
| Argentina    | 3         | 1.79%   |
| Switzerland  | 2         | 1.19%   |
| Mexico       | 2         | 1.19%   |
| India        | 2         | 1.19%   |
| Hungary      | 2         | 1.19%   |
| Finland      | 2         | 1.19%   |
| Belgium      | 2         | 1.19%   |
| Vietnam      | 1         | 0.6%    |
| Uruguay      | 1         | 0.6%    |
| Tunisia      | 1         | 0.6%    |
| South Africa | 1         | 0.6%    |
| Slovenia     | 1         | 0.6%    |
| Slovakia     | 1         | 0.6%    |
| Singapore    | 1         | 0.6%    |
| Serbia       | 1         | 0.6%    |
| Romania      | 1         | 0.6%    |
| Philippines  | 1         | 0.6%    |
| Norway       | 1         | 0.6%    |
| Martinique   | 1         | 0.6%    |
| Luxembourg   | 1         | 0.6%    |
| Lithuania    | 1         | 0.6%    |
| Lebanon      | 1         | 0.6%    |
| Japan        | 1         | 0.6%    |
| Indonesia    | 1         | 0.6%    |
| Greece       | 1         | 0.6%    |
| Ecuador      | 1         | 0.6%    |
| Czechia      | 1         | 0.6%    |
| Colombia     | 1         | 0.6%    |
| Chile        | 1         | 0.6%    |
| Canada       | 1         | 0.6%    |
| Bulgaria     | 1         | 0.6%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Milan                  | 4         | 2.27%   |
| Paris                  | 3         | 1.7%    |
| Warsaw                 | 2         | 1.14%   |
| Vicosa                 | 2         | 1.14%   |
| Stuttgart              | 2         | 1.14%   |
| Salvador               | 2         | 1.14%   |
| Rome                   | 2         | 1.14%   |
| Munich                 | 2         | 1.14%   |
| Moscow                 | 2         | 1.14%   |
| Krakow                 | 2         | 1.14%   |
| Houston                | 2         | 1.14%   |
| Helsinki               | 2         | 1.14%   |
| Fortaleza              | 2         | 1.14%   |
| Curitiba               | 2         | 1.14%   |
| Budapest               | 2         | 1.14%   |
| Brasília              | 2         | 1.14%   |
| Austin                 | 2         | 1.14%   |
| Zwanenburg             | 1         | 0.57%   |
| Zhovta Rika            | 1         | 0.57%   |
| Zabrze                 | 1         | 0.57%   |
| Wollongong             | 1         | 0.57%   |
| Wigan                  | 1         | 0.57%   |
| West Babylon           | 1         | 0.57%   |
| Wadsworth              | 1         | 0.57%   |
| Wadi Maliz             | 1         | 0.57%   |
| Vladivostok            | 1         | 0.57%   |
| Verdun                 | 1         | 0.57%   |
| Velilla de San Antonio | 1         | 0.57%   |
| Varna                  | 1         | 0.57%   |
| Uberlândia            | 1         | 0.57%   |
| Tunis                  | 1         | 0.57%   |
| Torres                 | 1         | 0.57%   |
| Taunton                | 1         | 0.57%   |
| Tanjil South           | 1         | 0.57%   |
| São Paulo             | 1         | 0.57%   |
| Surgut                 | 1         | 0.57%   |
| Strassen               | 1         | 0.57%   |
| Stavanger              | 1         | 0.57%   |
| Spay                   | 1         | 0.57%   |
| Southampton            | 1         | 0.57%   |
| Singapore              | 1         | 0.57%   |
| Saronno                | 1         | 0.57%   |
| Santa Maria            | 1         | 0.57%   |
| San Pietro a Maida     | 1         | 0.57%   |
| Samara                 | 1         | 0.57%   |
| Saint-Germain-en-Laye  | 1         | 0.57%   |
| Royal Tunbridge Wells  | 1         | 0.57%   |
| Roscommon              | 1         | 0.57%   |
| Pyatigorsk             | 1         | 0.57%   |
| Prato                  | 1         | 0.57%   |
| Poznan                 | 1         | 0.57%   |
| Powell River           | 1         | 0.57%   |
| Portland               | 1         | 0.57%   |
| Pont-a-Celles          | 1         | 0.57%   |
| Plymouth               | 1         | 0.57%   |
| Piraeus                | 1         | 0.57%   |
| Perth                  | 1         | 0.57%   |
| Patna                  | 1         | 0.57%   |
| Parkdale               | 1         | 0.57%   |
| Palmares               | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 45     | 19.7%   |
| WDC                 | 30        | 35     | 15.15%  |
| Toshiba             | 16        | 17     | 8.08%   |
| Samsung Electronics | 16        | 17     | 8.08%   |
| Unknown             | 13        | 15     | 6.57%   |
| Hitachi             | 13        | 16     | 6.57%   |
| Crucial             | 13        | 13     | 6.57%   |
| SanDisk             | 9         | 13     | 4.55%   |
| Kingston            | 8         | 8      | 4.04%   |
| Intel               | 5         | 6      | 2.53%   |
| SK Hynix            | 4         | 4      | 2.02%   |
| HGST                | 4         | 6      | 2.02%   |
| Fujitsu             | 3         | 3      | 1.52%   |
| Apacer              | 3         | 3      | 1.52%   |
| PNY                 | 2         | 2      | 1.01%   |
| Micron Technology   | 2         | 2      | 1.01%   |
| LITEONIT            | 2         | 2      | 1.01%   |
| China               | 2         | 2      | 1.01%   |
| A-DATA Technology   | 2         | 2      | 1.01%   |
| USB                 | 1         | 1      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| TCSUNBOW            | 1         | 1      | 0.51%   |
| Phison Electronics  | 1         | 1      | 0.51%   |
| LDLC                | 1         | 1      | 0.51%   |
| LaCie               | 1         | 2      | 0.51%   |
| KIOXIA              | 1         | 1      | 0.51%   |
| KingDian            | 1         | 1      | 0.51%   |
| Integral            | 1         | 1      | 0.51%   |
| Gigabyte Technology | 1         | 1      | 0.51%   |
| EMTEC               | 1         | 1      | 0.51%   |
| Apple               | 1         | 3      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 4         | 1.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 1.95%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 1.95%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.46%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.46%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.98%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.98%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 2         | 0.98%   |
| Unknown MMC Card  32GB               | 2         | 0.98%   |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.98%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.98%   |
| Seagate ST9500325AS 500GB            | 2         | 0.98%   |
| Seagate ST9250410AS 250GB            | 2         | 0.98%   |
| Seagate ST9160412AS 160GB            | 2         | 0.98%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.98%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.98%   |
| Seagate ST2000LX001-1RG174 2TB       | 2         | 0.98%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.98%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.98%   |
| Hitachi HTS541616J9SA00 160GB        | 2         | 0.98%   |
| Crucial CT480BX500SSD1 480GB         | 2         | 0.98%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.98%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.49%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.49%   |
| WDC WD800BEVS-60RST0 80GB            | 1         | 0.49%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.49%   |
| WDC WD6400BPVT-22HXZT1 640GB         | 1         | 0.49%   |
| WDC WD5000LPVX-55V0TT3 500GB         | 1         | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.49%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.49%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 1         | 0.49%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 0.49%   |
| WDC WD3200LPVX-16V0TT3 320GB         | 1         | 0.49%   |
| WDC WD3200BPVT-75ZEST0 320GB         | 1         | 0.49%   |
| WDC WD3200BPVT-24JJ5T0 320GB         | 1         | 0.49%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.49%   |
| WDC WD2500BEVT-80A23T0 250GB         | 1         | 0.49%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.49%   |
| WDC WD2500BEVT-00A23T0 250GB         | 1         | 0.49%   |
| WDC WD20SPZX-08UA7 2TB               | 1         | 0.49%   |
| WDC WD1600BEVT-08A23T1 160GB         | 1         | 0.49%   |
| WDC WD10SPZX-80Z10T2 1TB             | 1         | 0.49%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.49%   |
| WDC WD10SPZX-11Z10T0 1TB             | 1         | 0.49%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.49%   |
| USB 3.0 2TB                          | 1         | 0.49%   |
| Unknown SD04G  4GB                   | 1         | 0.49%   |
| Unknown SD01G  1GB                   | 1         | 0.49%   |
| Unknown NVMe SSD Drive 256GB         | 1         | 0.49%   |
| Unknown NCard  32GB                  | 1         | 0.49%   |
| Unknown MMC Card  982MB              | 1         | 0.49%   |
| Unknown MMC Card  64GB               | 1         | 0.49%   |
| Unknown MMC Card  2GB                | 1         | 0.49%   |
| Unknown MMC Card  16GB               | 1         | 0.49%   |
| Unknown M.2 2280-128GB SSD           | 1         | 0.49%   |
| Unknown G1J38E  64GB                 | 1         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 44     | 37.86%  |
| WDC                 | 25        | 30     | 24.27%  |
| Hitachi             | 13        | 16     | 12.62%  |
| Toshiba             | 12        | 13     | 11.65%  |
| Samsung Electronics | 5         | 5      | 4.85%   |
| HGST                | 4         | 6      | 3.88%   |
| Fujitsu             | 3         | 3      | 2.91%   |
| USB                 | 1         | 1      | 0.97%   |
| LaCie               | 1         | 1      | 0.97%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 13        | 13     | 21.31%  |
| Samsung Electronics | 8         | 9      | 13.11%  |
| Kingston            | 6         | 6      | 9.84%   |
| SanDisk             | 5         | 9      | 8.2%    |
| Intel               | 4         | 5      | 6.56%   |
| WDC                 | 3         | 3      | 4.92%   |
| Apacer              | 3         | 3      | 4.92%   |
| Toshiba             | 2         | 2      | 3.28%   |
| PNY                 | 2         | 2      | 3.28%   |
| LITEONIT            | 2         | 2      | 3.28%   |
| China               | 2         | 2      | 3.28%   |
| A-DATA Technology   | 2         | 2      | 3.28%   |
| Unknown             | 1         | 1      | 1.64%   |
| Transcend           | 1         | 1      | 1.64%   |
| TCSUNBOW            | 1         | 1      | 1.64%   |
| SK Hynix            | 1         | 1      | 1.64%   |
| Micron Technology   | 1         | 1      | 1.64%   |
| LDLC                | 1         | 1      | 1.64%   |
| KingDian            | 1         | 1      | 1.64%   |
| Integral            | 1         | 1      | 1.64%   |
| Apple               | 1         | 3      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 100       | 119    | 52.08%  |
| SSD     | 59        | 69     | 30.73%  |
| NVMe    | 18        | 19     | 9.38%   |
| MMC     | 13        | 16     | 6.77%   |
| Unknown | 2         | 3      | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 181    | 79.01%  |
| NVMe | 18        | 19     | 9.94%   |
| MMC  | 13        | 16     | 7.18%   |
| SAS  | 7         | 10     | 3.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 110       | 137    | 71.9%   |
| 0.51-1.0   | 34        | 39     | 22.22%  |
| 1.01-2.0   | 7         | 10     | 4.58%   |
| 3.01-4.0   | 1         | 1      | 0.65%   |
| 4.01-10.0  | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 47        | 27.65%  |
| 101-250        | 47        | 27.65%  |
| 501-1000       | 24        | 14.12%  |
| 51-100         | 14        | 8.24%   |
| 1-20           | 13        | 7.65%   |
| 21-50          | 11        | 6.47%   |
| 1001-2000      | 9         | 5.29%   |
| More than 3000 | 4         | 2.35%   |
| 2001-3000      | 1         | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 75        | 43.1%   |
| 21-50          | 33        | 18.97%  |
| 101-250        | 25        | 14.37%  |
| 51-100         | 15        | 8.62%   |
| 251-500        | 14        | 8.05%   |
| 501-1000       | 9         | 5.17%   |
| More than 3000 | 2         | 1.15%   |
| 2001-3000      | 1         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2      | 10%     |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 5%      |
| WDC WD800BEVS-60RST0 80GB                  | 1         | 1      | 5%      |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 2      | 5%      |
| TCSUNBOW X1 32GB SSD                       | 1         | 1      | 5%      |
| SK Hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 5%      |
| Seagate ST9320325AS 320GB                  | 1         | 1      | 5%      |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 5%      |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 5%      |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 5%      |
| Samsung Electronics HM160JI 160GB          | 1         | 1      | 5%      |
| Hitachi HTS722012K9SA00 120GB              | 1         | 1      | 5%      |
| Hitachi HTS541616J9SA00 160GB              | 1         | 1      | 5%      |
| HGST HTS541075A9E680 752GB                 | 1         | 1      | 5%      |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 5%      |
| Crucial CT960M500SSD1 960GB                | 1         | 1      | 5%      |
| Crucial CT120M500SSD3 120GB                | 1         | 1      | 5%      |
| Crucial CT120M500SSD1 120GB                | 1         | 1      | 5%      |
| A-DATA Technology IM2S3334-256GD 256GB SSD | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 30%     |
| WDC                 | 3         | 4      | 15%     |
| Crucial             | 3         | 3      | 15%     |
| Hitachi             | 2         | 2      | 10%     |
| HGST                | 2         | 2      | 10%     |
| TCSUNBOW            | 1         | 1      | 5%      |
| SK Hynix            | 1         | 1      | 5%      |
| Samsung Electronics | 1         | 1      | 5%      |
| A-DATA Technology   | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 46.15%  |
| WDC                 | 2         | 3      | 15.38%  |
| Hitachi             | 2         | 2      | 15.38%  |
| HGST                | 2         | 2      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 14     | 65%     |
| SSD  | 7         | 7      | 35%     |

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
| Detected | 81        | 119    | 46.02%  |
| Works    | 75        | 86     | 42.61%  |
| Malfunc  | 20        | 21     | 11.36%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 128       | 73.56%  |
| AMD                              | 26        | 14.94%  |
| Sandisk                          | 4         | 2.3%    |
| Samsung Electronics              | 3         | 1.72%   |
| SK Hynix                         | 2         | 1.15%   |
| Nvidia                           | 2         | 1.15%   |
| KIOXIA                           | 2         | 1.15%   |
| Kingston Technology Company      | 2         | 1.15%   |
| Toshiba America Info Systems     | 1         | 0.57%   |
| Solid State Storage Technology   | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Phison Electronics               | 1         | 0.57%   |
| Micron Technology                | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 8.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 16        | 7.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 7.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 5.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 5.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 9         | 4.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 3.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 3.48%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 4         | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4         | 1.99%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.49%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.49%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.49%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.49%   |
| Nvidia MCP51 Serial ATA Controller                                               | 2         | 1%      |
| Nvidia MCP51 IDE                                                                 | 2         | 1%      |
| KIOXIA Non-Volatile memory controller                                            | 2         | 1%      |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1%      |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1%      |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.5%    |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.5%    |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.5%    |
| SK Hynix BC511                                                                   | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.5%    |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.5%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.5%    |
| Micron Non-Volatile memory controller                                            | 1         | 0.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.5%    |
| Intel SSD 660P Series                                                            | 1         | 0.5%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.5%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1         | 0.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.5%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.5%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.5%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 0.5%    |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.5%    |
| AMD SB600 IDE                                                                    | 1         | 0.5%    |
| AMD IXP SB4x0 Serial ATA Controller                                              | 1         | 0.5%    |
| AMD IXP SB4x0 IDE Controller                                                     | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 138       | 72.63%  |
| IDE  | 27        | 14.21%  |
| NVMe | 17        | 8.95%   |
| RAID | 8         | 4.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 138       | 82.63%  |
| AMD    | 29        | 17.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz            | 5         | 2.99%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 5         | 2.99%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 4         | 2.4%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz  | 3         | 1.8%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 3         | 1.8%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 2         | 1.2%    |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 2         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz            | 2         | 1.2%    |
| Intel Core i7-6500U CPU @ 2.50GHz            | 2         | 1.2%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 1.2%    |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 2         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz            | 2         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz            | 2         | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz           | 2         | 1.2%    |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 2         | 1.2%    |
| Intel Core i3-2350M CPU @ 2.30GHz            | 2         | 1.2%    |
| Intel Core 2 CPU T5600 @ 1.83GHz             | 2         | 1.2%    |
| Intel Celeron Dual-Core CPU T3500 @ 2.10GHz  | 2         | 1.2%    |
| Intel Celeron CPU N2807 @ 1.58GHz            | 2         | 1.2%    |
| Intel Celeron CPU 847 @ 1.10GHz              | 2         | 1.2%    |
| Intel Atom CPU N450 @ 1.66GHz                | 2         | 1.2%    |
| Intel Atom CPU N2600 @ 1.60GHz               | 2         | 1.2%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics   | 2         | 1.2%    |
| AMD Ryzen 7 4700U with Radeon Graphics       | 2         | 1.2%    |
| AMD E-300 APU with Radeon HD Graphics        | 2         | 1.2%    |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.2%    |
| AMD A6-6310 APU with AMD Radeon R4 Graphics  | 2         | 1.2%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz  | 1         | 0.6%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz       | 1         | 0.6%    |
| Intel Pentium Dual CPU T2310 @ 1.46GHz       | 1         | 0.6%    |
| Intel Pentium CPU N3710 @ 1.60GHz            | 1         | 0.6%    |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.6%    |
| Intel Pentium CPU N3520 @ 2.16GHz            | 1         | 0.6%    |
| Intel Pentium CPU B960 @ 2.20GHz             | 1         | 0.6%    |
| Intel Pentium 3556U @ 1.70GHz                | 1         | 0.6%    |
| Intel Genuine CPU 585 @ 2.16GHz              | 1         | 0.6%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz             | 1         | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.6%    |
| Intel Core i7-5600U CPU @ 2.60GHz            | 1         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz            | 1         | 0.6%    |
| Intel Core i7-4750HQ CPU @ 2.00GHz           | 1         | 0.6%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz           | 1         | 0.6%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz           | 1         | 0.6%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz           | 1         | 0.6%    |
| Intel Core i7-4510U CPU @ 2.00GHz            | 1         | 0.6%    |
| Intel Core i7-3520M CPU @ 2.90GHz            | 1         | 0.6%    |
| Intel Core i7-2670QM CPU @ 2.20GHz           | 1         | 0.6%    |
| Intel Core i7-2640M CPU @ 2.80GHz            | 1         | 0.6%    |
| Intel Core i5-9300H CPU @ 2.40GHz            | 1         | 0.6%    |
| Intel Core i5-8365U CPU @ 1.60GHz            | 1         | 0.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz            | 1         | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz            | 1         | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz            | 1         | 0.6%    |
| Intel Core i5-4200M CPU @ 2.50GHz            | 1         | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz            | 1         | 0.6%    |
| Intel Core i5-2520M CPU @ 2.50GHz            | 1         | 0.6%    |
| Intel Core i5-2450M CPU @ 2.50GHz            | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 29        | 17.37%  |
| Intel Core i7                  | 21        | 12.57%  |
| Intel Core i3                  | 21        | 12.57%  |
| Intel Core 2 Duo               | 16        | 9.58%   |
| Intel Celeron                  | 15        | 8.98%   |
| Intel Atom                     | 11        | 6.59%   |
| Intel Pentium Dual-Core        | 6         | 3.59%   |
| Intel Pentium                  | 5         | 2.99%   |
| Other                          | 4         | 2.4%    |
| Intel Pentium Dual             | 4         | 2.4%    |
| Intel Core 2                   | 3         | 1.8%    |
| AMD E1                         | 3         | 1.8%    |
| AMD E                          | 3         | 1.8%    |
| Intel Celeron Dual-Core        | 2         | 1.2%    |
| AMD Turion 64 X2 Mobile        | 2         | 1.2%    |
| AMD Ryzen 7 PRO                | 2         | 1.2%    |
| AMD Ryzen 7                    | 2         | 1.2%    |
| AMD Ryzen 5                    | 2         | 1.2%    |
| AMD A6                         | 2         | 1.2%    |
| AMD A4                         | 2         | 1.2%    |
| Intel Pentium Silver           | 1         | 0.6%    |
| Intel Genuine                  | 1         | 0.6%    |
| Intel Core m3                  | 1         | 0.6%    |
| Intel Core 2 Solo              | 1         | 0.6%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.6%    |
| AMD Ryzen 3                    | 1         | 0.6%    |
| AMD Mobile Sempron             | 1         | 0.6%    |
| AMD C-60                       | 1         | 0.6%    |
| AMD C-50                       | 1         | 0.6%    |
| AMD Athlon X2                  | 1         | 0.6%    |
| AMD Athlon 64 X2               | 1         | 0.6%    |
| AMD A8                         | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 117       | 70.06%  |
| 4      | 37        | 22.16%  |
| 1      | 7         | 4.19%   |
| 8      | 4         | 2.4%    |
| 6      | 2         | 1.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 167       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 50.3%   |
| 2      | 83        | 49.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 167       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 15        | 8.88%   |
| 0x6fd      | 11        | 6.51%   |
| 0x406e3    | 10        | 5.92%   |
| 0x1067a    | 10        | 5.92%   |
| Unknown    | 10        | 5.92%   |
| 0x806ec    | 9         | 5.33%   |
| 0x40651    | 7         | 4.14%   |
| 0x306a9    | 6         | 3.55%   |
| 0x30678    | 6         | 3.55%   |
| 0x10676    | 6         | 3.55%   |
| 0x406c3    | 5         | 2.96%   |
| 0x306c3    | 5         | 2.96%   |
| 0x20655    | 5         | 2.96%   |
| 0x306d4    | 4         | 2.37%   |
| 0x20652    | 4         | 2.37%   |
| 0x06006705 | 4         | 2.37%   |
| 0x05000119 | 4         | 2.37%   |
| 0x806eb    | 3         | 1.78%   |
| 0x406c4    | 3         | 1.78%   |
| 0x106ca    | 3         | 1.78%   |
| 0x07030105 | 3         | 1.78%   |
| 0x906ea    | 2         | 1.18%   |
| 0x706e5    | 2         | 1.18%   |
| 0x706a1    | 2         | 1.18%   |
| 0x6f6      | 2         | 1.18%   |
| 0x30661    | 2         | 1.18%   |
| 0x10661    | 2         | 1.18%   |
| 0x08600106 | 2         | 1.18%   |
| 0x08600103 | 2         | 1.18%   |
| 0x08108102 | 2         | 1.18%   |
| 0x07030106 | 2         | 1.18%   |
| 0x906ed    | 1         | 0.59%   |
| 0x806ea    | 1         | 0.59%   |
| 0x806e9    | 1         | 0.59%   |
| 0x806c1    | 1         | 0.59%   |
| 0x706a8    | 1         | 0.59%   |
| 0x6fb      | 1         | 0.59%   |
| 0x6fa      | 1         | 0.59%   |
| 0x506ca    | 1         | 0.59%   |
| 0x40661    | 1         | 0.59%   |
| 0x30673    | 1         | 0.59%   |
| 0x08101007 | 1         | 0.59%   |
| 0x07030104 | 1         | 0.59%   |
| 0x0700010f | 1         | 0.59%   |
| 0x05000029 | 1         | 0.59%   |
| 0x02000057 | 1         | 0.59%   |
| 0x02000032 | 1         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Core            | 18        | 10.78%  |
| Penryn          | 17        | 10.18%  |
| KabyLake        | 17        | 10.18%  |
| Silvermont      | 15        | 8.98%   |
| SandyBridge     | 15        | 8.98%   |
| Haswell         | 13        | 7.78%   |
| Skylake         | 11        | 6.59%   |
| Westmere        | 10        | 5.99%   |
| Puma            | 6         | 3.59%   |
| IvyBridge       | 6         | 3.59%   |
| Bonnell         | 5         | 2.99%   |
| Bobcat          | 5         | 2.99%   |
| Zen 2           | 4         | 2.4%    |
| K8 Hammer       | 4         | 2.4%    |
| Excavator       | 4         | 2.4%    |
| Broadwell       | 4         | 2.4%    |
| Goldmont plus   | 3         | 1.8%    |
| Zen+            | 2         | 1.2%    |
| K8 & K10 hybrid | 2         | 1.2%    |
| IceLake         | 2         | 1.2%    |
| Zen             | 1         | 0.6%    |
| TigerLake       | 1         | 0.6%    |
| Jaguar          | 1         | 0.6%    |
| Goldmont        | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 128       | 67.02%  |
| AMD                              | 39        | 20.42%  |
| Nvidia                           | 23        | 12.04%  |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 7.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 6.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 5.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 5.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 3.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 3.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 3.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 2.9%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.42%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.93%   |
| AMD Renoir                                                                               | 4         | 1.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.45%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.45%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 1.45%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.45%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.97%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.97%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.97%   |
| Intel HD Graphics 520                                                                    | 2         | 0.97%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.97%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.97%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.97%   |
| AMD Picasso                                                                              | 2         | 0.97%   |
| AMD Mullins [Radeon R2 Graphics]                                                         | 2         | 0.97%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.48%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.48%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.48%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.48%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.48%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.48%   |
| Nvidia GF108M [NVS 5400M]                                                                | 1         | 0.48%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.48%   |
| Nvidia GF108M [GeForce 610M]                                                             | 1         | 0.48%   |
| Nvidia G92M [GeForce 8800M GTX]                                                          | 1         | 0.48%   |
| Nvidia G86M [Quadro NVS 135M]                                                            | 1         | 0.48%   |
| Nvidia C51 [GeForce Go 6150]                                                             | 1         | 0.48%   |
| Nvidia C51 [GeForce Go 6100]                                                             | 1         | 0.48%   |
| Intel UHD Graphics 620                                                                   | 1         | 0.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 1         | 0.48%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 0.48%   |
| Intel HD Graphics 620                                                                    | 1         | 0.48%   |
| Intel HD Graphics 515                                                                    | 1         | 0.48%   |
| Intel HD Graphics 500                                                                    | 1         | 0.48%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.48%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 104       | 62.28%  |
| 1 x AMD        | 30        | 17.96%  |
| Intel + Nvidia | 16        | 9.58%   |
| Intel + AMD    | 8         | 4.79%   |
| 1 x Nvidia     | 7         | 4.19%   |
| 2 x AMD        | 1         | 0.6%    |
| 1 x SiS        | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 155       | 92.26%  |
| Proprietary | 11        | 6.55%   |
| Unknown     | 2         | 1.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 66.07%  |
| 0.01-0.5   | 34        | 20.24%  |
| 1.01-2.0   | 11        | 6.55%   |
| 0.51-1.0   | 9         | 5.36%   |
| 2.01-3.0   | 2         | 1.19%   |
| 3.01-4.0   | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 19.43%  |
| Samsung Electronics     | 25        | 14.29%  |
| LG Display              | 23        | 13.14%  |
| Chimei Innolux          | 23        | 13.14%  |
| BOE                     | 20        | 11.43%  |
| Chi Mei Optoelectronics | 6         | 3.43%   |
| LG Philips              | 5         | 2.86%   |
| Lenovo                  | 5         | 2.86%   |
| Acer                    | 5         | 2.86%   |
| Apple                   | 4         | 2.29%   |
| InfoVision              | 3         | 1.71%   |
| Goldstar                | 3         | 1.71%   |
| Dell                    | 3         | 1.71%   |
| Sharp                   | 2         | 1.14%   |
| Hewlett-Packard         | 2         | 1.14%   |
| HannStar                | 2         | 1.14%   |
| Vizio                   | 1         | 0.57%   |
| Videoseven              | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| Philips                 | 1         | 0.57%   |
| PANDA                   | 1         | 0.57%   |
| NEC Computers           | 1         | 0.57%   |
| Lenovo Group Limited    | 1         | 0.57%   |
| KDC                     | 1         | 0.57%   |
| InnoLux Display         | 1         | 0.57%   |
| AOC                     | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 2.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 3         | 1.7%    |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch  | 2         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 2         | 1.14%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.14%   |
| Lenovo LCD Monitor LEN4031 1280x800 303x190mm 14.1-inch               | 2         | 1.14%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch          | 2         | 1.14%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 1.14%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                  | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.14%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                  | 2         | 1.14%   |
| Vizio E220MV VIZ0062 1920x1080 509x286mm 23.0-inch                    | 1         | 0.57%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.57%   |
| Sony TV SNYA401 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.57%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch               | 1         | 0.57%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 509x286mm 23.0-inch  | 1         | 0.57%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4449 1366x768 309x174mm 14.0-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3842 1366x768 309x174mm 14.0-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC374E 1024x600 223x125mm 10.1-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 340x190mm 15.3-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 0.57%   |
| Philips LCD Monitor PHLC054 1920x1080 480x270mm 21.7-inch             | 1         | 0.57%   |
| PANDA LCD Monitor NCP0032 1920x1080 344x194mm 15.5-inch               | 1         | 0.57%   |
| NEC Computers EA221WMe NEC6778 1680x1050 470x300mm 22.0-inch          | 1         | 0.57%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch         | 1         | 0.57%   |
| LG Philips LCD Monitor LPLDC00 1280x800 331x207mm 15.4-inch           | 1         | 0.57%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch           | 1         | 0.57%   |
| LG Philips LCD Monitor LPL2A00 1280x800 330x210mm 15.4-inch           | 1         | 0.57%   |
| LG Philips LCD Monitor LPL0032 1920x1200 370x230mm 17.2-inch          | 1         | 0.57%   |
| LG Display LCD Monitor LGD8C01 1366x768 344x194mm 15.5-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD05F1 1920x1080 309x174mm 14.0-inch          | 1         | 0.57%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.57%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.57%   |
| LG Display LCD Monitor LGD04FF 1920x1080 309x174mm 14.0-inch          | 1         | 0.57%   |
| LG Display LCD Monitor LGD0493 1366x768 344x194mm 15.5-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD0455 1366x768 310x170mm 13.9-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD042D 1920x1080 290x170mm 13.2-inch          | 1         | 0.57%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD0396 1600x900 382x215mm 17.3-inch           | 1         | 0.57%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 70        | 41.18%  |
| 1920x1080 (FHD)    | 42        | 24.71%  |
| 1280x800 (WXGA)    | 20        | 11.76%  |
| 1600x900 (HD+)     | 12        | 7.06%   |
| 1920x1200 (WUXGA)  | 6         | 3.53%   |
| 3840x2160 (4K)     | 4         | 2.35%   |
| 1680x1050 (WSXGA+) | 3         | 1.76%   |
| 1440x900 (WXGA+)   | 3         | 1.76%   |
| 1024x600           | 3         | 1.76%   |
| 2560x1440 (QHD)    | 2         | 1.18%   |
| 1280x1024 (SXGA)   | 2         | 1.18%   |
| 3840x2400          | 1         | 0.59%   |
| 2560x1600          | 1         | 0.59%   |
| 1280x720 (HD)      | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 72        | 41.14%  |
| 13      | 30        | 17.14%  |
| 14      | 26        | 14.86%  |
| 17      | 12        | 6.86%   |
| 11      | 6         | 3.43%   |
| 27      | 4         | 2.29%   |
| 24      | 4         | 2.29%   |
| 21      | 4         | 2.29%   |
| 12      | 4         | 2.29%   |
| 10      | 4         | 2.29%   |
| 22      | 3         | 1.71%   |
| 23      | 2         | 1.14%   |
| 72      | 1         | 0.57%   |
| 20      | 1         | 0.57%   |
| 19      | 1         | 0.57%   |
| Unknown | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 63.79%  |
| 201-300     | 26        | 14.94%  |
| 351-400     | 17        | 9.77%   |
| 501-600     | 10        | 5.75%   |
| 401-500     | 8         | 4.6%    |
| 1501-2000   | 1         | 0.57%   |
| Unknown     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 127       | 78.88%  |
| 16/10   | 31        | 19.25%  |
| 5/4     | 1         | 0.62%   |
| 4/3     | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 40.57%  |
| 81-90          | 47        | 26.86%  |
| 71-80          | 10        | 5.71%   |
| 201-250        | 10        | 5.71%   |
| 121-130        | 9         | 5.14%   |
| 51-60          | 6         | 3.43%   |
| 41-50          | 4         | 2.29%   |
| 301-350        | 4         | 2.29%   |
| 61-70          | 3         | 1.71%   |
| 251-300        | 3         | 1.71%   |
| 131-140        | 3         | 1.71%   |
| 151-200        | 2         | 1.14%   |
| More than 1000 | 1         | 0.57%   |
| 111-120        | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 86        | 50.29%  |
| 121-160       | 46        | 26.9%   |
| 51-100        | 30        | 17.54%  |
| 161-240       | 4         | 2.34%   |
| More than 240 | 3         | 1.75%   |
| 1-50          | 1         | 0.58%   |
| Unknown       | 1         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 144       | 85.21%  |
| 2     | 22        | 13.02%  |
| 0     | 2         | 1.18%   |
| 3     | 1         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 90        | 32.85%  |
| Intel                             | 68        | 24.82%  |
| Qualcomm Atheros                  | 52        | 18.98%  |
| Broadcom                          | 27        | 9.85%   |
| Marvell Technology Group          | 11        | 4.01%   |
| Broadcom Limited                  | 8         | 2.92%   |
| TP-Link                           | 3         | 1.09%   |
| Ralink Technology                 | 3         | 1.09%   |
| Ralink                            | 2         | 0.73%   |
| Nvidia                            | 2         | 0.73%   |
| Xiaomi                            | 1         | 0.36%   |
| Tenda                             | 1         | 0.36%   |
| Seeed                             | 1         | 0.36%   |
| Samsung Electronics               | 1         | 0.36%   |
| NetGear                           | 1         | 0.36%   |
| Ericsson Business Mobile Networks | 1         | 0.36%   |
| Attansic Technology               | 1         | 0.36%   |
| ASIX Electronics                  | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 45        | 13.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 29        | 9.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 3.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 3.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 3.11%   |
| Intel Wireless 7260                                                     | 8         | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 2.17%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 6         | 1.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 6         | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 1.55%   |
| Intel Wireless 3160                                                     | 5         | 1.55%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.24%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 1.24%   |
| Intel Wireless 8260                                                     | 4         | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 3         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.93%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.62%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.62%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.62%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.62%   |
| Nvidia MCP51 Ethernet Controller                                        | 2         | 0.62%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                    | 2         | 0.62%   |
| Intel Wireless 7265                                                     | 2         | 0.62%   |
| Intel WiFi Link 5100                                                    | 2         | 0.62%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.62%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.62%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.62%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.62%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 2         | 0.62%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.62%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                | 2         | 0.62%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 2         | 0.62%   |
| Broadcom Limited BCM4311 802.11a/b/g                                    | 2         | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.31%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                              | 1         | 0.31%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.31%   |
| Tenda U12                                                               | 1         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 39.41%  |
| Qualcomm Atheros      | 46        | 27.06%  |
| Realtek Semiconductor | 26        | 15.29%  |
| Broadcom              | 17        | 10%     |
| Broadcom Limited      | 4         | 2.35%   |
| TP-Link               | 3         | 1.76%   |
| Ralink Technology     | 3         | 1.76%   |
| Ralink                | 2         | 1.18%   |
| Tenda                 | 1         | 0.59%   |
| NetGear               | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Notebooks | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 11        | 6.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 11        | 6.47%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)                       | 10        | 5.88%   |
| Intel Wireless 7260                                                                           | 8         | 4.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 7         | 4.12%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 6         | 3.53%   |
| Intel Wi-Fi 6 AX200                                                                           | 6         | 3.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                           | 6         | 3.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5         | 2.94%   |
| Intel Wireless 3160                                                                           | 5         | 2.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                       | 5         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 4         | 2.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 4         | 2.35%   |
| Intel Wireless 8260                                                                           | 4         | 2.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                         | 4         | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 4         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 1.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                                 | 3         | 1.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 3         | 1.76%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 3         | 1.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                             | 3         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                      | 2         | 1.18%   |
| Realtek 802.11ac NIC                                                                          | 2         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                                               | 2         | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                                     | 2         | 1.18%   |
| Intel Wireless 7265                                                                           | 2         | 1.18%   |
| Intel WiFi Link 5100                                                                          | 2         | 1.18%   |
| Intel Ultimate N WiFi Link 5300                                                               | 2         | 1.18%   |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                             | 2         | 1.18%   |
| Intel Centrino Wireless-N 100                                                                 | 2         | 1.18%   |
| Intel Centrino Advanced-N 6200                                                                | 2         | 1.18%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                          | 2         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                                                 | 2         | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 1         | 0.59%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 0.59%   |
| Tenda U12                                                                                     | 1         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 1         | 0.59%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.59%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                             | 1         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                              | 1         | 0.59%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                | 1         | 0.59%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                                       | 1         | 0.59%   |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.59%   |
| Intel Wi-Fi 6 AX201                                                                           | 1         | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                               | 1         | 0.59%   |
| Intel Centrino Wireless-N 2200                                                                | 1         | 0.59%   |
| Intel Centrino Wireless-N 130                                                                 | 1         | 0.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                                  | 1         | 0.59%   |
| Intel Centrino Advanced-N 6235                                                                | 1         | 0.59%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                                                 | 1         | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 1         | 0.59%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                                       | 1         | 0.59%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                                   | 1         | 0.59%   |
| Broadcom BCM43225 802.11b/g/n                                                                 | 1         | 0.59%   |
| Broadcom BCM4321 802.11a/b/g/n                                                                | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 56%     |
| Intel                    | 17        | 11.33%  |
| Qualcomm Atheros         | 14        | 9.33%   |
| Broadcom                 | 14        | 9.33%   |
| Marvell Technology Group | 11        | 7.33%   |
| Broadcom Limited         | 4         | 2.67%   |
| Nvidia                   | 2         | 1.33%   |
| Xiaomi                   | 1         | 0.67%   |
| Samsung Electronics      | 1         | 0.67%   |
| Attansic Technology      | 1         | 0.67%   |
| ASIX Electronics         | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 45        | 30%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 19.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 4%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 3.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 2.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 2%      |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 2%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 2%      |
| Intel Ethernet Connection I219-V                                               | 3         | 2%      |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 2%      |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 2%      |
| Nvidia MCP51 Ethernet Controller                                               | 2         | 1.33%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 1.33%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.33%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 2         | 1.33%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 1.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.67%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.67%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.67%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.67%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.67%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.67%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.67%   |
| Broadcom NetXtreme BCM5754M Gigabit Ethernet PCI Express                       | 1         | 0.67%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.67%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 0.67%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 0.67%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 1         | 0.67%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 1         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 52.26%  |
| Ethernet | 146       | 47.1%   |
| Modem    | 2         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 149       | 64.5%   |
| Ethernet | 82        | 35.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 135       | 80.84%  |
| 1     | 25        | 14.97%  |
| 0     | 6         | 3.59%   |
| 3     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 154       | 90.59%  |
| Yes  | 16        | 9.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 39.62%  |
| Qualcomm Atheros Communications | 10        | 9.43%   |
| Realtek Semiconductor           | 9         | 8.49%   |
| Broadcom                        | 8         | 7.55%   |
| Lite-On Technology              | 7         | 6.6%    |
| Cambridge Silicon Radio         | 7         | 6.6%    |
| IMC Networks                    | 5         | 4.72%   |
| Apple                           | 4         | 3.77%   |
| Dell                            | 3         | 2.83%   |
| Ralink Technology               | 2         | 1.89%   |
| Hewlett-Packard                 | 2         | 1.89%   |
| ASUSTek Computer                | 2         | 1.89%   |
| Alps Electric                   | 2         | 1.89%   |
| Toshiba                         | 1         | 0.94%   |
| Foxconn / Hon Hai               | 1         | 0.94%   |
| Chicony Electronics             | 1         | 0.94%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 17        | 16.04%  |
| Intel Bluetooth wireless interface                                                  | 13        | 12.26%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 8.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 6.6%    |
| Realtek Bluetooth Radio                                                             | 6         | 5.66%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 5.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.83%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 2.83%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.89%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.89%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.89%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.89%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.89%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.89%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.94%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.94%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.94%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.94%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.94%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.94%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.94%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.94%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.94%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.94%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.94%   |
| Dell Wireless 350 Bluetooth                                                         | 1         | 0.94%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.94%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.94%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.94%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.94%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.94%   |
| Apple Bluetooth HCI                                                                 | 1         | 0.94%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.94%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 1         | 0.94%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 131       | 72.78%  |
| AMD                               | 32        | 17.78%  |
| Nvidia                            | 12        | 6.67%   |
| GN Netcom                         | 2         | 1.11%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.56%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.56%   |
| C-Media Electronics               | 1         | 0.56%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 7.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 6.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 13        | 5.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 4.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 3.65%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 3.2%    |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 3.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 3.2%    |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 7         | 3.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.83%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.83%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.37%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.37%   |
| Nvidia MCP51 High Definition Audio                                                                | 2         | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.91%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.91%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.91%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.91%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.46%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.46%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.46%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.46%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.46%   |
| GN Netcom Jabra UC VOICE 250a MS                                                                  | 1         | 0.46%   |
| GN Netcom Jabra EVOLVE LINK                                                                       | 1         | 0.46%   |
| Elitegroup Computer Systems (ECS) 32bit DAC                                                       | 1         | 0.46%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.46%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 1         | 0.46%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.46%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 1         | 0.46%   |
| AMD IXP SB4x0 High Definition Audio Controller                                                    | 1         | 0.46%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 30        | 23.44%  |
| Unknown             | 24        | 18.75%  |
| SK Hynix            | 20        | 15.63%  |
| Micron Technology   | 10        | 7.81%   |
| Kingston            | 6         | 4.69%   |
| A-DATA Technology   | 6         | 4.69%   |
| Crucial             | 5         | 3.91%   |
| Nanya Technology    | 4         | 3.13%   |
| Smart               | 3         | 2.34%   |
| Corsair             | 3         | 2.34%   |
| Team                | 2         | 1.56%   |
| Patriot             | 2         | 1.56%   |
| ELPIDA              | 2         | 1.56%   |
| Unknown (ABCD)      | 1         | 0.78%   |
| Teikon              | 1         | 0.78%   |
| Sesame              | 1         | 0.78%   |
| Qimonda             | 1         | 0.78%   |
| PNY                 | 1         | 0.78%   |
| Multilaser          | 1         | 0.78%   |
| Goldkey             | 1         | 0.78%   |
| G.Skill             | 1         | 0.78%   |
| DigiBoard           | 1         | 0.78%   |
| Avant               | 1         | 0.78%   |
| Apacer              | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s     | 4         | 2.94%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s         | 3         | 2.21%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s               | 2         | 1.47%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 2         | 1.47%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1600MT/s              | 2         | 1.47%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 1.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 1.47%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s     | 2         | 1.47%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 2         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s     | 2         | 1.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s        | 2         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s     | 2         | 1.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 2         | 1.47%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s         | 2         | 1.47%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                | 2         | 1.47%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s      | 2         | 1.47%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s      | 2         | 1.47%   |
| Unknown SODIMM 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.74%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.74%   |
| Unknown SODIMM 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.74%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 0.74%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s               | 1         | 0.74%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s               | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s               | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s               | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.74%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                 | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM LPDDR4 2400MT/s             | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s               | 1         | 0.74%   |
| Unknown RAM Module 2048MB DIMM LPDDR4 1600MT/s               | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2 2MT/s                  | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2 1MT/s                  | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s | 1         | 0.74%   |
| Teikon RAM TMT425S6CFR6A-PBNJ 2048MB SODIMM DDR3 1333MT/s    | 1         | 0.74%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s        | 1         | 0.74%   |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 2667MT/s      | 1         | 0.74%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s        | 1         | 0.74%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s        | 1         | 0.74%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR 800MT/s          | 1         | 0.74%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2667MT/s             | 1         | 0.74%   |
| SK Hynix RAM Module 1024MB SODIMM DDR2 667MT/s               | 1         | 0.74%   |
| SK Hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s        | 1         | 0.74%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s      | 1         | 0.74%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK Hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.74%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.74%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.74%   |
| SK Hynix RAM HMT112S6BFR6C-H9 1GB SODIMM DDR3 1333MT/s       | 1         | 0.74%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.74%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 52        | 47.71%  |
| DDR4    | 30        | 27.52%  |
| DDR2    | 16        | 14.68%  |
| LPDDR4  | 3         | 2.75%   |
| LPDDR3  | 3         | 2.75%   |
| SDRAM   | 2         | 1.83%   |
| DDR     | 2         | 1.83%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 101       | 93.52%  |
| Row Of Chips | 5         | 4.63%   |
| DIMM         | 1         | 0.93%   |
| Chip         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 45        | 35.43%  |
| 2048  | 35        | 27.56%  |
| 8192  | 29        | 22.83%  |
| 1024  | 10        | 7.87%   |
| 16384 | 7         | 5.51%   |
| 32768 | 1         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 29        | 23.97%  |
| 2667    | 16        | 13.22%  |
| 1334    | 13        | 10.74%  |
| 2400    | 10        | 8.26%   |
| 1333    | 10        | 8.26%   |
| 667     | 10        | 8.26%   |
| 3200    | 6         | 4.96%   |
| 800     | 6         | 4.96%   |
| 2133    | 4         | 3.31%   |
| 2048    | 2         | 1.65%   |
| 1867    | 2         | 1.65%   |
| 1067    | 2         | 1.65%   |
| 1066    | 2         | 1.65%   |
| 533     | 2         | 1.65%   |
| Unknown | 2         | 1.65%   |
| 4267    | 1         | 0.83%   |
| 1866    | 1         | 0.83%   |
| 1200    | 1         | 0.83%   |
| 2       | 1         | 0.83%   |
| 1       | 1         | 0.83%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 25%     |
| HP Deskjet 3520 series  | 1         | 25%     |
| Brother PTUSB Printing  | 1         | 25%     |
| Brother DCP-7055W       | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 29.71%  |
| Acer                                   | 14        | 10.14%  |
| Realtek Semiconductor                  | 10        | 7.25%   |
| Microdia                               | 10        | 7.25%   |
| IMC Networks                           | 10        | 7.25%   |
| Suyin                                  | 7         | 5.07%   |
| Quanta                                 | 7         | 5.07%   |
| Silicon Motion                         | 4         | 2.9%    |
| Alcor Micro                            | 4         | 2.9%    |
| Sunplus Innovation Technology          | 3         | 2.17%   |
| Ricoh                                  | 3         | 2.17%   |
| Lenovo                                 | 3         | 2.17%   |
| Importek                               | 3         | 2.17%   |
| Apple                                  | 3         | 2.17%   |
| Z-Star Microelectronics                | 2         | 1.45%   |
| Syntek                                 | 2         | 1.45%   |
| Samsung Electronics                    | 2         | 1.45%   |
| Lite-On Technology                     | 2         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.45%   |
| OmniVision Technologies                | 1         | 0.72%   |
| Nintendo                               | 1         | 0.72%   |
| Luxvisions Innotech Limited            | 1         | 0.72%   |
| GEMBIRD                                | 1         | 0.72%   |
| DigiTech                               | 1         | 0.72%   |
| ALi                                    | 1         | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 5.04%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.88%   |
| Chicony TOSHIBA Web Camera - HD                     | 4         | 2.88%   |
| Acer Lenovo EasyCamera                              | 4         | 2.88%   |
| Chicony EasyCamera                                  | 3         | 2.16%   |
| Alcor Micro Asus Integrated Webcam                  | 3         | 2.16%   |
| Sunplus HD WebCam                                   | 2         | 1.44%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 1.44%   |
| Realtek Integrated Webcam                           | 2         | 1.44%   |
| Quanta VGA WebCam                                   | 2         | 1.44%   |
| Quanta HP HD Camera                                 | 2         | 1.44%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 1.44%   |
| Importek TOSHIBA Web Camera - HD                    | 2         | 1.44%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.44%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 2         | 1.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.44%   |
| Chicony USB 2.0 Camera                              | 2         | 1.44%   |
| Chicony HP HD Camera                                | 2         | 1.44%   |
| Chicony HD WebCam                                   | 2         | 1.44%   |
| Apple FaceTime HD Camera                            | 2         | 1.44%   |
| Acer USB 2.0 Camera                                 | 2         | 1.44%   |
| Acer BisonCam,NB Pro                                | 2         | 1.44%   |
| Z-Star Webcam                                       | 1         | 0.72%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.72%   |
| Syntek Integrated Camera                            | 1         | 0.72%   |
| Syntek EasyCamera                                   | 1         | 0.72%   |
| Suyin WebCam                                        | 1         | 0.72%   |
| Suyin Lenovo Integrated Webcam                      | 1         | 0.72%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.72%   |
| Suyin HP Webcam-101                                 | 1         | 0.72%   |
| Suyin HP Webcam                                     | 1         | 0.72%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.72%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.72%   |
| Sunplus Laptop Integrated Webcam HD                 | 1         | 0.72%   |
| Silicon Motion WebCam SCB-0355N                     | 1         | 0.72%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.72%   |
| Silicon Motion Web Camera                           | 1         | 0.72%   |
| Silicon Motion Lenovo EasyCamera                    | 1         | 0.72%   |
| Ricoh Webcam 1000                                   | 1         | 0.72%   |
| Ricoh Visual Communication Camera VGP-VCC7 [R5U870] | 1         | 0.72%   |
| Ricoh Integrated_Webcam_1.3M                        | 1         | 0.72%   |
| Realtek USB2.0 VGA UVC WebCam                       | 1         | 0.72%   |
| Realtek USB Camera                                  | 1         | 0.72%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.72%   |
| Realtek FULL HD 1080P Webcam                        | 1         | 0.72%   |
| Quanta HP Webcam                                    | 1         | 0.72%   |
| Quanta hm1091_techfront                             | 1         | 0.72%   |
| Quanta HD Webcam                                    | 1         | 0.72%   |
| OmniVision OV2640 Webcam                            | 1         | 0.72%   |
| Nintendo USB Camera                                 | 1         | 0.72%   |
| Microdia Sonix USB 2.0 Camera                       | 1         | 0.72%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_2HDM              | 1         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 0.72%   |
| Microdia Integrated_Webcam_HD                       | 1         | 0.72%   |
| Microdia Integrated Webcam                          | 1         | 0.72%   |
| Microdia HP Webcam                                  | 1         | 0.72%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.72%   |
| Lite-On HP Wide Vision HD Camera                    | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 40%     |
| AuthenTec                  | 6         | 30%     |
| Shenzhen Goodix Technology | 3         | 15%     |
| Upek                       | 2         | 10%     |
| LighTuning Technology      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 10%     |
| AuthenTec AES2810                                      | 2         | 10%     |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS300 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 5%      |
| Validity Sensors VFS Fingerprint sensor                | 1         | 5%      |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5%      |
| Shenzhen Goodix FingerPrint                            | 1         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 5%      |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 5%      |
| AuthenTec AES1600                                      | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 42.86%  |
| O2 Micro    | 2         | 28.57%  |
| Upek        | 1         | 14.29%  |
| Broadcom    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 131       | 77.51%  |
| 1     | 29        | 17.16%  |
| 2     | 9         | 5.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 20        | 44.44%  |
| Chipcard           | 7         | 15.56%  |
| Graphics card      | 6         | 13.33%  |
| Net/wireless       | 5         | 11.11%  |
| Camera             | 3         | 6.67%   |
| Storage            | 2         | 4.44%   |
| Net/ethernet       | 1         | 2.22%   |
| Flash memory       | 1         | 2.22%   |

