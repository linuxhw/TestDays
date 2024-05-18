Linux in Bulgaria - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bulgaria/Desktop/README.md) and [notebooks](/Location/Bulgaria/Notebook/README.md).

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

Total: 1884

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G6            | Notebook    | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0cd34decca](https://linux-hardware.org/?probe=0cd34decca) | May 08, 2024 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [0c39b2e745](https://linux-hardware.org/?probe=0c39b2e745) | May 05, 2024 |
| Dell          | Inspiron 11-3162            | Notebook    | [ccf99ca586](https://linux-hardware.org/?probe=ccf99ca586) | May 05, 2024 |
| Lenovo        | ThinkPad X270 20HMS34L00    | Notebook    | [dcc424b27d](https://linux-hardware.org/?probe=dcc424b27d) | May 04, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [a698a1991c](https://linux-hardware.org/?probe=a698a1991c) | May 03, 2024 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c03d3e0508](https://linux-hardware.org/?probe=c03d3e0508) | May 03, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [e52fd6543b](https://linux-hardware.org/?probe=e52fd6543b) | May 03, 2024 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [58453faaf6](https://linux-hardware.org/?probe=58453faaf6) | May 03, 2024 |
| Toshiba       | Satellite P200              | Notebook    | [f9f88ee996](https://linux-hardware.org/?probe=f9f88ee996) | May 03, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [3b1c4174da](https://linux-hardware.org/?probe=3b1c4174da) | May 02, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f3681e3ab6](https://linux-hardware.org/?probe=f3681e3ab6) | May 02, 2024 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | Desktop     | [135b6c8c4e](https://linux-hardware.org/?probe=135b6c8c4e) | Apr 30, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [e9acc27fce](https://linux-hardware.org/?probe=e9acc27fce) | Apr 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [01432a3384](https://linux-hardware.org/?probe=01432a3384) | Apr 23, 2024 |
| Allview       | Allbook J                   | Notebook    | [77d90c2a69](https://linux-hardware.org/?probe=77d90c2a69) | Apr 23, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [b0d7f30c2c](https://linux-hardware.org/?probe=b0d7f30c2c) | Apr 23, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [a04aab72d2](https://linux-hardware.org/?probe=a04aab72d2) | Apr 23, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [aa9d8113e9](https://linux-hardware.org/?probe=aa9d8113e9) | Apr 23, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [aa0595d186](https://linux-hardware.org/?probe=aa0595d186) | Apr 22, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [34d0d4f469](https://linux-hardware.org/?probe=34d0d4f469) | Apr 22, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [e0c405894c](https://linux-hardware.org/?probe=e0c405894c) | Apr 21, 2024 |
| ASUSTek       | P5K Premium                 | Desktop     | [5ff3e52237](https://linux-hardware.org/?probe=5ff3e52237) | Apr 21, 2024 |
| Toshiba       | Satellite C850-124          | Notebook    | [b580358635](https://linux-hardware.org/?probe=b580358635) | Apr 20, 2024 |
| Unknown       | Unknown                     | Notebook    | [7ee99946ca](https://linux-hardware.org/?probe=7ee99946ca) | Apr 19, 2024 |
| Acer          | Aspire 7738                 | Notebook    | [dc56784ca7](https://linux-hardware.org/?probe=dc56784ca7) | Apr 19, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [a5d4162d2f](https://linux-hardware.org/?probe=a5d4162d2f) | Apr 19, 2024 |
| Allview       | Allbook J                   | Notebook    | [a106195c34](https://linux-hardware.org/?probe=a106195c34) | Apr 18, 2024 |
| HP            | 1998                        | Desktop     | [d16f45d089](https://linux-hardware.org/?probe=d16f45d089) | Apr 18, 2024 |
| Pegatron      | 2AC3                        | Desktop     | [db5312ea90](https://linux-hardware.org/?probe=db5312ea90) | Apr 18, 2024 |
| Dell          | 0K240Y A03                  | Desktop     | [1642fe3a09](https://linux-hardware.org/?probe=1642fe3a09) | Apr 14, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [2d02eae5ec](https://linux-hardware.org/?probe=2d02eae5ec) | Apr 13, 2024 |
| Lenovo        | ThinkPad T440 20B7A0MN04    | Notebook    | [2244374672](https://linux-hardware.org/?probe=2244374672) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [2304feb790](https://linux-hardware.org/?probe=2304feb790) | Apr 13, 2024 |
| ASRock        | G31M-S                      | Desktop     | [d9694d3f33](https://linux-hardware.org/?probe=d9694d3f33) | Apr 12, 2024 |
| HP            | Pavilion dv8                | Notebook    | [24eb3d99a9](https://linux-hardware.org/?probe=24eb3d99a9) | Apr 11, 2024 |
| HP            | 1998                        | Desktop     | [4e592f29d7](https://linux-hardware.org/?probe=4e592f29d7) | Apr 11, 2024 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e5830d8754](https://linux-hardware.org/?probe=e5830d8754) | Apr 07, 2024 |
| Acer          | Predator PH315-53           | Notebook    | [4c8bbd0426](https://linux-hardware.org/?probe=4c8bbd0426) | Apr 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [18961ee7a8](https://linux-hardware.org/?probe=18961ee7a8) | Apr 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [d74a81067e](https://linux-hardware.org/?probe=d74a81067e) | Apr 07, 2024 |
| HP            | 1905                        | Desktop     | [d55405d144](https://linux-hardware.org/?probe=d55405d144) | Apr 06, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e121ce9511](https://linux-hardware.org/?probe=e121ce9511) | Apr 06, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6496d4176b](https://linux-hardware.org/?probe=6496d4176b) | Apr 05, 2024 |
| Acer          | Aspire V5-572G              | Notebook    | [ca5e1f767e](https://linux-hardware.org/?probe=ca5e1f767e) | Apr 04, 2024 |
| ASUSTek       | X55VD                       | Notebook    | [bc22ba01de](https://linux-hardware.org/?probe=bc22ba01de) | Apr 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [708291ee28](https://linux-hardware.org/?probe=708291ee28) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [449d0ad45b](https://linux-hardware.org/?probe=449d0ad45b) | Mar 31, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [431002bc2d](https://linux-hardware.org/?probe=431002bc2d) | Mar 30, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [3d2abf7e0d](https://linux-hardware.org/?probe=3d2abf7e0d) | Mar 30, 2024 |
| Dell          | Latitude 5580               | Notebook    | [db427c180d](https://linux-hardware.org/?probe=db427c180d) | Mar 28, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [deae5b6cdf](https://linux-hardware.org/?probe=deae5b6cdf) | Mar 27, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [602d79d663](https://linux-hardware.org/?probe=602d79d663) | Mar 27, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [bfe7fd8a2e](https://linux-hardware.org/?probe=bfe7fd8a2e) | Mar 26, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [806d659258](https://linux-hardware.org/?probe=806d659258) | Mar 26, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [99983f8fbf](https://linux-hardware.org/?probe=99983f8fbf) | Mar 25, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d402ccab08](https://linux-hardware.org/?probe=d402ccab08) | Mar 23, 2024 |
| Dell          | 06D7TR A00                  | Desktop     | [3c6718eb19](https://linux-hardware.org/?probe=3c6718eb19) | Mar 23, 2024 |
| Dell          | Precision M4700             | Notebook    | [212d29f26d](https://linux-hardware.org/?probe=212d29f26d) | Mar 21, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [f8fa83eaf5](https://linux-hardware.org/?probe=f8fa83eaf5) | Mar 20, 2024 |
| Fujitsu       | D3531-A1 S26361-D3531-A1    | Desktop     | [80d82ca19d](https://linux-hardware.org/?probe=80d82ca19d) | Mar 19, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [e85fec8591](https://linux-hardware.org/?probe=e85fec8591) | Mar 18, 2024 |
| Acer          | Predator PT516-52s          | Notebook    | [86614957f2](https://linux-hardware.org/?probe=86614957f2) | Mar 17, 2024 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [9bde6bc531](https://linux-hardware.org/?probe=9bde6bc531) | Mar 17, 2024 |
| ASUSTek       | X55VD                       | Notebook    | [a959f1dfec](https://linux-hardware.org/?probe=a959f1dfec) | Mar 17, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3ec06d0273](https://linux-hardware.org/?probe=3ec06d0273) | Mar 16, 2024 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [311809b062](https://linux-hardware.org/?probe=311809b062) | Mar 16, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [75bc4f3af5](https://linux-hardware.org/?probe=75bc4f3af5) | Mar 13, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | Notebook    | [fbc1335ccc](https://linux-hardware.org/?probe=fbc1335ccc) | Mar 12, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [edf84e43ee](https://linux-hardware.org/?probe=edf84e43ee) | Mar 11, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ca3f8b06ab](https://linux-hardware.org/?probe=ca3f8b06ab) | Mar 10, 2024 |
| Allview       | Allbook J                   | Notebook    | [58b6452c8f](https://linux-hardware.org/?probe=58b6452c8f) | Mar 08, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [f7f7bcc5ec](https://linux-hardware.org/?probe=f7f7bcc5ec) | Mar 07, 2024 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [1719342e74](https://linux-hardware.org/?probe=1719342e74) | Mar 07, 2024 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [d261ab3479](https://linux-hardware.org/?probe=d261ab3479) | Mar 06, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [898154cbf9](https://linux-hardware.org/?probe=898154cbf9) | Mar 05, 2024 |
| HP            | ZBook Studio G5             | Notebook    | [208ce1e5fd](https://linux-hardware.org/?probe=208ce1e5fd) | Mar 04, 2024 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b957a4b5d8](https://linux-hardware.org/?probe=b957a4b5d8) | Mar 03, 2024 |
| Allview       | Allbook J                   | Notebook    | [dd1b4469c1](https://linux-hardware.org/?probe=dd1b4469c1) | Mar 01, 2024 |
| Lenovo        | Yoga Pro 7 14IMH9 83E2      | Notebook    | [935b64ed30](https://linux-hardware.org/?probe=935b64ed30) | Feb 29, 2024 |
| MSI           | Thin GF63 12UDX             | Notebook    | [648c7d0aa4](https://linux-hardware.org/?probe=648c7d0aa4) | Feb 28, 2024 |
| Lenovo        | YB1-X91F                    | Convertible | [dcb774f0e8](https://linux-hardware.org/?probe=dcb774f0e8) | Feb 27, 2024 |
| HP            | 1497                        | Desktop     | [58e91b7bbc](https://linux-hardware.org/?probe=58e91b7bbc) | Feb 26, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [47c8a22aea](https://linux-hardware.org/?probe=47c8a22aea) | Feb 26, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [5edfd90f55](https://linux-hardware.org/?probe=5edfd90f55) | Feb 26, 2024 |
| ASRock        | N68C-S UCC                  | Desktop     | [4aff653920](https://linux-hardware.org/?probe=4aff653920) | Feb 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [27c2f0156e](https://linux-hardware.org/?probe=27c2f0156e) | Feb 25, 2024 |
| MSI           | Modern 14 B11MO             | Notebook    | [6f5a4e6e1e](https://linux-hardware.org/?probe=6f5a4e6e1e) | Feb 23, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4e50b74dd4](https://linux-hardware.org/?probe=4e50b74dd4) | Feb 22, 2024 |
| Gigabyte      | Z590 VISION D               | Desktop     | [8070df1f8e](https://linux-hardware.org/?probe=8070df1f8e) | Feb 21, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [e2780e976f](https://linux-hardware.org/?probe=e2780e976f) | Feb 18, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [95978292b2](https://linux-hardware.org/?probe=95978292b2) | Feb 18, 2024 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [fe0255bc9f](https://linux-hardware.org/?probe=fe0255bc9f) | Feb 15, 2024 |
| Dell          | Latitude E5470              | Notebook    | [4f6f03415f](https://linux-hardware.org/?probe=4f6f03415f) | Feb 12, 2024 |
| Acer          | Predator PT516-52s          | Notebook    | [d271f4b0ca](https://linux-hardware.org/?probe=d271f4b0ca) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | Notebook    | [a3255728e7](https://linux-hardware.org/?probe=a3255728e7) | Feb 12, 2024 |
| MSI           | Modern 15 A11M              | Notebook    | [aa78cf8909](https://linux-hardware.org/?probe=aa78cf8909) | Feb 12, 2024 |
| Foxconn       | A76GMV                      | Desktop     | [b15858bfd0](https://linux-hardware.org/?probe=b15858bfd0) | Feb 10, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [1d2758029b](https://linux-hardware.org/?probe=1d2758029b) | Feb 08, 2024 |
| Dell          | Vostro 3580                 | Notebook    | [0b028612c5](https://linux-hardware.org/?probe=0b028612c5) | Feb 08, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [d01b52dd20](https://linux-hardware.org/?probe=d01b52dd20) | Feb 05, 2024 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [1e6645fdc9](https://linux-hardware.org/?probe=1e6645fdc9) | Feb 05, 2024 |
| HP            | 18E7                        | Desktop     | [84caef4dde](https://linux-hardware.org/?probe=84caef4dde) | Feb 02, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [e87efb031b](https://linux-hardware.org/?probe=e87efb031b) | Feb 02, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [62254b1636](https://linux-hardware.org/?probe=62254b1636) | Jan 31, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [a78d79030e](https://linux-hardware.org/?probe=a78d79030e) | Jan 30, 2024 |
| Dell          | Studio 1747                 | Notebook    | [b43d9b4a13](https://linux-hardware.org/?probe=b43d9b4a13) | Jan 29, 2024 |
| Dell          | Studio 1747                 | Notebook    | [9fe0b059bc](https://linux-hardware.org/?probe=9fe0b059bc) | Jan 29, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [49e891b67d](https://linux-hardware.org/?probe=49e891b67d) | Jan 28, 2024 |
| Dell          | 01W23F A05                  | Server      | [93f017d8b0](https://linux-hardware.org/?probe=93f017d8b0) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b55015259](https://linux-hardware.org/?probe=9b55015259) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3cecdef02f](https://linux-hardware.org/?probe=3cecdef02f) | Jan 26, 2024 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [32d1dff107](https://linux-hardware.org/?probe=32d1dff107) | Jan 26, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [44539fb8b1](https://linux-hardware.org/?probe=44539fb8b1) | Jan 25, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [dc93e0097a](https://linux-hardware.org/?probe=dc93e0097a) | Jan 25, 2024 |
| HP            | 3648h                       | Desktop     | [3905de5f4f](https://linux-hardware.org/?probe=3905de5f4f) | Jan 24, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [be74f076bd](https://linux-hardware.org/?probe=be74f076bd) | Jan 23, 2024 |
| Dell          | Latitude 7280               | Notebook    | [21e6e4a581](https://linux-hardware.org/?probe=21e6e4a581) | Jan 22, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0b0db0e2ef](https://linux-hardware.org/?probe=0b0db0e2ef) | Jan 22, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [36cb9057d7](https://linux-hardware.org/?probe=36cb9057d7) | Jan 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [f6204361d0](https://linux-hardware.org/?probe=f6204361d0) | Jan 19, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [12539bda5e](https://linux-hardware.org/?probe=12539bda5e) | Jan 19, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [667df4a998](https://linux-hardware.org/?probe=667df4a998) | Jan 17, 2024 |
| HP            | 255 G3                      | Notebook    | [7f8af802a0](https://linux-hardware.org/?probe=7f8af802a0) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [82f1c7e4f3](https://linux-hardware.org/?probe=82f1c7e4f3) | Jan 14, 2024 |
| HP            | EliteBook 745 G5            | Notebook    | [64314a5149](https://linux-hardware.org/?probe=64314a5149) | Jan 13, 2024 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [b37b59525e](https://linux-hardware.org/?probe=b37b59525e) | Jan 12, 2024 |
| Dell          | Latitude 5431               | Notebook    | [45d7b96fb3](https://linux-hardware.org/?probe=45d7b96fb3) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Dell          | Latitude E7470              | Notebook    | [2d36d1a363](https://linux-hardware.org/?probe=2d36d1a363) | Jan 11, 2024 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [f46fcb5ee9](https://linux-hardware.org/?probe=f46fcb5ee9) | Jan 10, 2024 |
| MSI           | Katana GF66 12UG            | Notebook    | [d4affacb08](https://linux-hardware.org/?probe=d4affacb08) | Jan 08, 2024 |
| Dell          | Latitude 7280               | Notebook    | [9557a37753](https://linux-hardware.org/?probe=9557a37753) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [26ec173956](https://linux-hardware.org/?probe=26ec173956) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [514f7e46c3](https://linux-hardware.org/?probe=514f7e46c3) | Jan 04, 2024 |
| Dell          | Latitude D630               | Notebook    | [e48315d3aa](https://linux-hardware.org/?probe=e48315d3aa) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [88f364d196](https://linux-hardware.org/?probe=88f364d196) | Jan 03, 2024 |
| ASRock        | Z87 Extreme4                | Desktop     | [eb75366525](https://linux-hardware.org/?probe=eb75366525) | Jan 03, 2024 |
| ASRock        | Z87 Extreme4                | Desktop     | [2b8d61b50d](https://linux-hardware.org/?probe=2b8d61b50d) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [15ae58d88c](https://linux-hardware.org/?probe=15ae58d88c) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [c9312cc676](https://linux-hardware.org/?probe=c9312cc676) | Jan 03, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Sony          | VGN-CS21Z_Q                 | Notebook    | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [8651fcb2dc](https://linux-hardware.org/?probe=8651fcb2dc) | Dec 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Dell          | Precision 5560              | Notebook    | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c8430d442b](https://linux-hardware.org/?probe=c8430d442b) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d412fe88ac](https://linux-hardware.org/?probe=d412fe88ac) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5aae59ec96](https://linux-hardware.org/?probe=5aae59ec96) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [217704dcb3](https://linux-hardware.org/?probe=217704dcb3) | Dec 27, 2023 |
| Biostar       | H61MHV3                     | Desktop     | [f03f05706c](https://linux-hardware.org/?probe=f03f05706c) | Dec 26, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [1ef527f93a](https://linux-hardware.org/?probe=1ef527f93a) | Dec 24, 2023 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [acee62fb75](https://linux-hardware.org/?probe=acee62fb75) | Dec 13, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [c6c8d22a8e](https://linux-hardware.org/?probe=c6c8d22a8e) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [ce858f7f7c](https://linux-hardware.org/?probe=ce858f7f7c) | Dec 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [c71041fa59](https://linux-hardware.org/?probe=c71041fa59) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [fc475e4cd3](https://linux-hardware.org/?probe=fc475e4cd3) | Dec 11, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [0841e29863](https://linux-hardware.org/?probe=0841e29863) | Dec 10, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| Dell          | 0GM819                      | Desktop     | [8ff7ec90b2](https://linux-hardware.org/?probe=8ff7ec90b2) | Dec 05, 2023 |
| Lenovo        | 3000 G410                   | Notebook    | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4cbc340e7c](https://linux-hardware.org/?probe=4cbc340e7c) | Dec 01, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [80e09b727b](https://linux-hardware.org/?probe=80e09b727b) | Nov 30, 2023 |
| HP            | EliteBook 8530p             | Notebook    | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [e3473e64c5](https://linux-hardware.org/?probe=e3473e64c5) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [c9b79740d2](https://linux-hardware.org/?probe=c9b79740d2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DV0Y    | Notebook    | [c68289cf4c](https://linux-hardware.org/?probe=c68289cf4c) | Nov 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [d979c6298f](https://linux-hardware.org/?probe=d979c6298f) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ab4754aa8](https://linux-hardware.org/?probe=2ab4754aa8) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [576d311bde](https://linux-hardware.org/?probe=576d311bde) | Nov 18, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a8cc099fb1](https://linux-hardware.org/?probe=a8cc099fb1) | Nov 18, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Lenovo        | ThinkPad X270 20HMS76D02    | Notebook    | [7da50d5ad3](https://linux-hardware.org/?probe=7da50d5ad3) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASRock        | J3455M                      | Desktop     | [6a3463b7e9](https://linux-hardware.org/?probe=6a3463b7e9) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [4a2561319d](https://linux-hardware.org/?probe=4a2561319d) | Nov 08, 2023 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [143a351fe0](https://linux-hardware.org/?probe=143a351fe0) | Nov 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [25ab11fca1](https://linux-hardware.org/?probe=25ab11fca1) | Nov 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| HP            | Spectre Pro x360 G2         | Convertible | [de099b29d0](https://linux-hardware.org/?probe=de099b29d0) | Nov 06, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | Notebook    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | Notebook    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ebfb135726](https://linux-hardware.org/?probe=ebfb135726) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c06d2e60fc](https://linux-hardware.org/?probe=c06d2e60fc) | Nov 01, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [09b312b58c](https://linux-hardware.org/?probe=09b312b58c) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [9b65c56faa](https://linux-hardware.org/?probe=9b65c56faa) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | Notebook    | [3b8803286b](https://linux-hardware.org/?probe=3b8803286b) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | Notebook    | [63963cbe04](https://linux-hardware.org/?probe=63963cbe04) | Oct 25, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [e0591a946d](https://linux-hardware.org/?probe=e0591a946d) | Oct 25, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [9c136d661d](https://linux-hardware.org/?probe=9c136d661d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | Notebook    | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [102735d7e5](https://linux-hardware.org/?probe=102735d7e5) | Oct 21, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [6c4a10bf6e](https://linux-hardware.org/?probe=6c4a10bf6e) | Oct 18, 2023 |
| Gigabyte      | Z590 VISION D               | Desktop     | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| Dell          | Latitude E5410              | Notebook    | [b1559718de](https://linux-hardware.org/?probe=b1559718de) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [63341aa786](https://linux-hardware.org/?probe=63341aa786) | Oct 13, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [c699787ab8](https://linux-hardware.org/?probe=c699787ab8) | Oct 11, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [a3b9e5b40c](https://linux-hardware.org/?probe=a3b9e5b40c) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ec7aee0455](https://linux-hardware.org/?probe=ec7aee0455) | Oct 10, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [e06a9dcd7d](https://linux-hardware.org/?probe=e06a9dcd7d) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | Notebook    | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| HP            | 635                         | Notebook    | [ef474a26d0](https://linux-hardware.org/?probe=ef474a26d0) | Oct 07, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [93e298660d](https://linux-hardware.org/?probe=93e298660d) | Oct 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [233fe08ffd](https://linux-hardware.org/?probe=233fe08ffd) | Oct 07, 2023 |
| AWOW          | AL34                        | Desktop     | [8933a81f53](https://linux-hardware.org/?probe=8933a81f53) | Oct 07, 2023 |
| ONDA          | V80 PLUS                    | Notebook    | [8651e33f83](https://linux-hardware.org/?probe=8651e33f83) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5584c834bc](https://linux-hardware.org/?probe=5584c834bc) | Oct 04, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [56a4c9aa55](https://linux-hardware.org/?probe=56a4c9aa55) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [efd92c3198](https://linux-hardware.org/?probe=efd92c3198) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Dell          | Precision 5510              | Notebook    | [34ddd03339](https://linux-hardware.org/?probe=34ddd03339) | Sep 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [03aa0d1366](https://linux-hardware.org/?probe=03aa0d1366) | Sep 25, 2023 |
| HP            | 3047h                       | Desktop     | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6c75af44c4](https://linux-hardware.org/?probe=6c75af44c4) | Sep 21, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Timi          | A30                         | Notebook    | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [744362d446](https://linux-hardware.org/?probe=744362d446) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [82d4f51421](https://linux-hardware.org/?probe=82d4f51421) | Sep 12, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ae29792d70](https://linux-hardware.org/?probe=ae29792d70) | Sep 11, 2023 |
| ASRock        | H81 Pro BTC                 | Desktop     | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| Dell          | Latitude 5431               | Notebook    | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [0405093009](https://linux-hardware.org/?probe=0405093009) | Sep 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [2e5644f065](https://linux-hardware.org/?probe=2e5644f065) | Sep 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| MSI           | Bravo 15 C7VF               | Notebook    | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [19d11f7098](https://linux-hardware.org/?probe=19d11f7098) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [245964564e](https://linux-hardware.org/?probe=245964564e) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| HP            | 1497                        | Desktop     | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f21550a5b3](https://linux-hardware.org/?probe=f21550a5b3) | Sep 02, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6dc701c67d](https://linux-hardware.org/?probe=6dc701c67d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | Notebook    | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| Dell          | Studio 1747                 | Notebook    | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [74ff13d301](https://linux-hardware.org/?probe=74ff13d301) | Aug 23, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [66691707c9](https://linux-hardware.org/?probe=66691707c9) | Aug 16, 2023 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [3dacfd8a02](https://linux-hardware.org/?probe=3dacfd8a02) | Aug 16, 2023 |
| Dell          | Latitude E4300              | Notebook    | [7c153c96f5](https://linux-hardware.org/?probe=7c153c96f5) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [ec4bac7b02](https://linux-hardware.org/?probe=ec4bac7b02) | Aug 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| Dell          | Precision M4600             | Notebook    | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [7723e84488](https://linux-hardware.org/?probe=7723e84488) | Aug 09, 2023 |
| Dell          | Latitude E4300              | Notebook    | [9ae3d19a62](https://linux-hardware.org/?probe=9ae3d19a62) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | Notebook    | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| Dell          | Precision 7750              | Notebook    | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| HP            | 198E                        | Desktop     | [34023c0d62](https://linux-hardware.org/?probe=34023c0d62) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [5a9a1e320d](https://linux-hardware.org/?probe=5a9a1e320d) | Jul 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | 635                         | Notebook    | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Latitude 7275               | Tablet      | [fdeba04a06](https://linux-hardware.org/?probe=fdeba04a06) | Jul 19, 2023 |
| HP            | ProBook 6570b               | Notebook    | [0a74371e23](https://linux-hardware.org/?probe=0a74371e23) | Jul 18, 2023 |
| Dell          | Inspiron 3551               | Notebook    | [543382ea16](https://linux-hardware.org/?probe=543382ea16) | Jul 16, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [cd17b6716c](https://linux-hardware.org/?probe=cd17b6716c) | Jul 16, 2023 |
| Dell          | Inspiron 3551               | Notebook    | [74050e892f](https://linux-hardware.org/?probe=74050e892f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [639eb4733c](https://linux-hardware.org/?probe=639eb4733c) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Dell          | G15 5511                    | Notebook    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| HP            | Notebook                    | Notebook    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | Notebook    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [5b561a0e00](https://linux-hardware.org/?probe=5b561a0e00) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [b2b20dd3f1](https://linux-hardware.org/?probe=b2b20dd3f1) | Jun 26, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Dell          | Latitude 3180               | Notebook    | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | Desktop     | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [3c0316ef92](https://linux-hardware.org/?probe=3c0316ef92) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a6fb35a2d8](https://linux-hardware.org/?probe=a6fb35a2d8) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [3d694e1b9a](https://linux-hardware.org/?probe=3d694e1b9a) | Jun 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Dell          | Precision 7710              | Notebook    | [f1b57ded18](https://linux-hardware.org/?probe=f1b57ded18) | Jun 08, 2023 |
| Dell          | Latitude 3350               | Notebook    | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Cube          | i16-L                       | Notebook    | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| HP            | 3047h                       | Desktop     | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | Notebook    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [aeb6fa2258](https://linux-hardware.org/?probe=aeb6fa2258) | May 26, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f0e96b17d7](https://linux-hardware.org/?probe=f0e96b17d7) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02d5fa9cc3](https://linux-hardware.org/?probe=02d5fa9cc3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0eec4b5bbe](https://linux-hardware.org/?probe=0eec4b5bbe) | May 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4280ce2bd4](https://linux-hardware.org/?probe=4280ce2bd4) | May 15, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [92c052d9b4](https://linux-hardware.org/?probe=92c052d9b4) | May 14, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Beelink       | BT3 PRO                     | Notebook    | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [dc317ab270](https://linux-hardware.org/?probe=dc317ab270) | May 06, 2023 |
| ASRock        | H370 Pro4                   | Desktop     | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | Notebook    | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [01c8d89ab9](https://linux-hardware.org/?probe=01c8d89ab9) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5d0819f25c](https://linux-hardware.org/?probe=5d0819f25c) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [3d73e4cd7e](https://linux-hardware.org/?probe=3d73e4cd7e) | Apr 27, 2023 |
| Dell          | Latitude E4300              | Notebook    | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | Notebook    | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | Notebook    | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| HP            | 8056                        | Desktop     | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| Dell          | Latitude E4300              | Notebook    | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Dell          | Latitude E4300              | Notebook    | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| HP            | ProBook 4540s               | Notebook    | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| ASRock        | Z97X Killer                 | Desktop     | [d258d06b23](https://linux-hardware.org/?probe=d258d06b23) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [3b0ab63643](https://linux-hardware.org/?probe=3b0ab63643) | Apr 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [f05e3341d3](https://linux-hardware.org/?probe=f05e3341d3) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [1f19b2c0dc](https://linux-hardware.org/?probe=1f19b2c0dc) | Apr 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| ASUSTek       | P5K                         | Desktop     | [ea3489709c](https://linux-hardware.org/?probe=ea3489709c) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [3fdeb525d1](https://linux-hardware.org/?probe=3fdeb525d1) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [90b9eaf3fe](https://linux-hardware.org/?probe=90b9eaf3fe) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [88caf7c0d1](https://linux-hardware.org/?probe=88caf7c0d1) | Mar 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53cd93c3f5](https://linux-hardware.org/?probe=53cd93c3f5) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 8954                        | Desktop     | [e7a2f29df5](https://linux-hardware.org/?probe=e7a2f29df5) | Mar 27, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [ec1dd7f3ab](https://linux-hardware.org/?probe=ec1dd7f3ab) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | Notebook    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [f5a9d12043](https://linux-hardware.org/?probe=f5a9d12043) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41289d94bf](https://linux-hardware.org/?probe=41289d94bf) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [1ccaab03c4](https://linux-hardware.org/?probe=1ccaab03c4) | Mar 25, 2023 |
| Toshiba       | Satellite C850-140          | Notebook    | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Gigabyte      | M52S-S3P                    | Desktop     | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [3c4c536325](https://linux-hardware.org/?probe=3c4c536325) | Mar 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [abd4bb0963](https://linux-hardware.org/?probe=abd4bb0963) | Mar 21, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4dcebf6a41](https://linux-hardware.org/?probe=4dcebf6a41) | Mar 21, 2023 |
| HP            | ProBook 6475b               | Notebook    | [1b7a5f385c](https://linux-hardware.org/?probe=1b7a5f385c) | Mar 18, 2023 |
| HP            | ProBook 6475b               | Notebook    | [0fd12da29b](https://linux-hardware.org/?probe=0fd12da29b) | Mar 18, 2023 |
| HP            | ProBook 6475b               | Notebook    | [701aca7f61](https://linux-hardware.org/?probe=701aca7f61) | Mar 18, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [2a6ded1018](https://linux-hardware.org/?probe=2a6ded1018) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [47df31e0fb](https://linux-hardware.org/?probe=47df31e0fb) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [c14956dd2d](https://linux-hardware.org/?probe=c14956dd2d) | Mar 12, 2023 |
| Acer          | Aspire 5333                 | Notebook    | [214db069e4](https://linux-hardware.org/?probe=214db069e4) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [65c2aab8aa](https://linux-hardware.org/?probe=65c2aab8aa) | Mar 11, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [95da35c192](https://linux-hardware.org/?probe=95da35c192) | Mar 11, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | Desktop     | [0d5c00b6fa](https://linux-hardware.org/?probe=0d5c00b6fa) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [e03e243c84](https://linux-hardware.org/?probe=e03e243c84) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Dell          | Latitude E4300              | Notebook    | [3c777f1c07](https://linux-hardware.org/?probe=3c777f1c07) | Mar 10, 2023 |
| HP            | ProBook 6475b               | Notebook    | [be06cdc105](https://linux-hardware.org/?probe=be06cdc105) | Mar 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [f4b107fbf3](https://linux-hardware.org/?probe=f4b107fbf3) | Mar 02, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [c068117b39](https://linux-hardware.org/?probe=c068117b39) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c3d0c5da79](https://linux-hardware.org/?probe=c3d0c5da79) | Mar 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [df09052bac](https://linux-hardware.org/?probe=df09052bac) | Mar 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f9cae700c7](https://linux-hardware.org/?probe=f9cae700c7) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [4f7bbbdd28](https://linux-hardware.org/?probe=4f7bbbdd28) | Feb 24, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| Google        | Astronaut                   | Notebook    | [71e8582f54](https://linux-hardware.org/?probe=71e8582f54) | Feb 22, 2023 |
| Google        | Astronaut                   | Notebook    | [4949e50dad](https://linux-hardware.org/?probe=4949e50dad) | Feb 22, 2023 |
| HP            | Notebook                    | Notebook    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [74b6676de3](https://linux-hardware.org/?probe=74b6676de3) | Feb 19, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5ebabab1c5](https://linux-hardware.org/?probe=5ebabab1c5) | Feb 14, 2023 |
| HP            | ProBook 6460b               | Notebook    | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [1df562d2d8](https://linux-hardware.org/?probe=1df562d2d8) | Feb 13, 2023 |
| Dell          | Precision M4700             | Notebook    | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9b58106fd6](https://linux-hardware.org/?probe=9b58106fd6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [65ebc31f26](https://linux-hardware.org/?probe=65ebc31f26) | Feb 08, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f2664ae2a](https://linux-hardware.org/?probe=9f2664ae2a) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [7037d37121](https://linux-hardware.org/?probe=7037d37121) | Feb 05, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
| Dell          | Precision 5540              | Notebook    | [de6a1c523e](https://linux-hardware.org/?probe=de6a1c523e) | Jan 28, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c34bc63cb0](https://linux-hardware.org/?probe=c34bc63cb0) | Jan 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a9a199e6f7](https://linux-hardware.org/?probe=a9a199e6f7) | Jan 24, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [e4b2eae84b](https://linux-hardware.org/?probe=e4b2eae84b) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| ASRock        | H81M-ITX                    | Desktop     | [036832c7d1](https://linux-hardware.org/?probe=036832c7d1) | Jan 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [ca332b4905](https://linux-hardware.org/?probe=ca332b4905) | Jan 13, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [30b776e4e8](https://linux-hardware.org/?probe=30b776e4e8) | Jan 11, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [7cd86f1bf1](https://linux-hardware.org/?probe=7cd86f1bf1) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [183b311eb2](https://linux-hardware.org/?probe=183b311eb2) | Jan 09, 2023 |
| Google        | Kled                        | Notebook    | [6380ae012e](https://linux-hardware.org/?probe=6380ae012e) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| System76      | Gazelle                     | Notebook    | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Fujitsu       | D3076-S1 S26361-D3076-S1    | Desktop     | [10b0d01482](https://linux-hardware.org/?probe=10b0d01482) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| Dell          | Precision M6400             | Notebook    | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [be5212ebcc](https://linux-hardware.org/?probe=be5212ebcc) | Jan 03, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [c51bc128e2](https://linux-hardware.org/?probe=c51bc128e2) | Dec 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Dell          | Latitude E5410              | Notebook    | [969f85bfc3](https://linux-hardware.org/?probe=969f85bfc3) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a4aed5865b](https://linux-hardware.org/?probe=a4aed5865b) | Dec 18, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [532dc55c4b](https://linux-hardware.org/?probe=532dc55c4b) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| Acer          | AO756                       | Notebook    | [ebc4d7cfcb](https://linux-hardware.org/?probe=ebc4d7cfcb) | Dec 16, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [936608196d](https://linux-hardware.org/?probe=936608196d) | Dec 14, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [6987aeacd5](https://linux-hardware.org/?probe=6987aeacd5) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [f464385b16](https://linux-hardware.org/?probe=f464385b16) | Dec 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [f4188b30c9](https://linux-hardware.org/?probe=f4188b30c9) | Dec 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [7ea67f4c69](https://linux-hardware.org/?probe=7ea67f4c69) | Dec 11, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9158c39614](https://linux-hardware.org/?probe=9158c39614) | Dec 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Acer          | Aspire ES1-731G             | Notebook    | [589cce31c8](https://linux-hardware.org/?probe=589cce31c8) | Dec 09, 2022 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [ff0997b72a](https://linux-hardware.org/?probe=ff0997b72a) | Dec 09, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [aae285b0ea](https://linux-hardware.org/?probe=aae285b0ea) | Dec 09, 2022 |
| HP            | 3047h                       | Desktop     | [223495dbab](https://linux-hardware.org/?probe=223495dbab) | Dec 08, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [01e7f95a23](https://linux-hardware.org/?probe=01e7f95a23) | Dec 07, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [c3b6c86431](https://linux-hardware.org/?probe=c3b6c86431) | Dec 07, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5ff0fd5395](https://linux-hardware.org/?probe=5ff0fd5395) | Dec 06, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [e2ffdfc5a8](https://linux-hardware.org/?probe=e2ffdfc5a8) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [50acc3b3b8](https://linux-hardware.org/?probe=50acc3b3b8) | Dec 04, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [9da9a87b5b](https://linux-hardware.org/?probe=9da9a87b5b) | Dec 03, 2022 |
| Acer          | Aspire ES1-731G             | Notebook    | [06918f4cc5](https://linux-hardware.org/?probe=06918f4cc5) | Dec 03, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [3e9458fd24](https://linux-hardware.org/?probe=3e9458fd24) | Dec 02, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | Notebook    | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [1424a94eb0](https://linux-hardware.org/?probe=1424a94eb0) | Nov 29, 2022 |
| Acer          | AO756                       | Notebook    | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | Notebook    | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| HP            | 1589                        | Desktop     | [4e67735055](https://linux-hardware.org/?probe=4e67735055) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d480b7ef56](https://linux-hardware.org/?probe=d480b7ef56) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d3b2f8aaf7](https://linux-hardware.org/?probe=d3b2f8aaf7) | Nov 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [faa15c49ae](https://linux-hardware.org/?probe=faa15c49ae) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [5468f11c01](https://linux-hardware.org/?probe=5468f11c01) | Nov 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [519c833f31](https://linux-hardware.org/?probe=519c833f31) | Nov 06, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | Notebook    | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | Notebook    | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| HP            | 8061                        | Desktop     | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| Acer          | Aspire 5830T                | Notebook    | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | Notebook    | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [b50165d9c9](https://linux-hardware.org/?probe=b50165d9c9) | Oct 11, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8f41682975](https://linux-hardware.org/?probe=8f41682975) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Samsung       | Galaxy TabPro S             | Tablet      | [25deda3e27](https://linux-hardware.org/?probe=25deda3e27) | Oct 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| HP            | 3047h                       | Desktop     | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3438959476](https://linux-hardware.org/?probe=3438959476) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | Notebook    | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [8047eeecb4](https://linux-hardware.org/?probe=8047eeecb4) | Aug 20, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | Notebook    | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c92d457cd6](https://linux-hardware.org/?probe=c92d457cd6) | Aug 13, 2022 |
| ASUSTek       | M2VTVM-VM890                | Desktop     | [8a822a57e8](https://linux-hardware.org/?probe=8a822a57e8) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [747ba68b28](https://linux-hardware.org/?probe=747ba68b28) | Aug 10, 2022 |
| Apple         | MacBookPro16,4              | Notebook    | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| Lenovo        | Unknown                     | Notebook    | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [616c57c367](https://linux-hardware.org/?probe=616c57c367) | Aug 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [e0129903ae](https://linux-hardware.org/?probe=e0129903ae) | Aug 04, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [69bd504820](https://linux-hardware.org/?probe=69bd504820) | Jul 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | Notebook    | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | Desktop     | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [2c0dd875b3](https://linux-hardware.org/?probe=2c0dd875b3) | Jun 21, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | Desktop     | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | Notebook    | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| Acer          | Predator G3-605             | Desktop     | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| Gigabyte      | H97N                        | Desktop     | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| MSI           | PRO B660-A DDR4             | Desktop     | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | Notebook    | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Dell          | Precision M6800             | Notebook    | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | Notebook    | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | Notebook    | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | Notebook    | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| ASUSTek       | N551VW                      | Notebook    | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88a943ec80](https://linux-hardware.org/?probe=88a943ec80) | Feb 16, 2022 |
| Dell          | Latitude E6330              | Notebook    | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | Notebook    | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| Dell          | Inspiron 5482               | Convertible | [17584ae0e4](https://linux-hardware.org/?probe=17584ae0e4) | Feb 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | Desktop     | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | Desktop     | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | Notebook    | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| ASUSTek       | P5E                         | Desktop     | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | Notebook    | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | Notebook    | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | Notebook    | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | Notebook    | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | Notebook    | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | Notebook    | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 117       | 8.8%    |
| Ubuntu 22.04                 | 93        | 6.99%   |
| Ubuntu 18.04                 | 80        | 6.02%   |
| Debian 11                    | 36        | 2.71%   |
| OpenMandriva 4.2             | 30        | 2.26%   |
| Manjaro                      | 24        | 1.8%    |
| Arch Rolling                 | 23        | 1.73%   |
| OpenMandriva 4.3             | 22        | 1.65%   |
| Fedora 38                    | 22        | 1.65%   |
| Pop!_OS 22.04                | 21        | 1.58%   |
| Fedora 39                    | 20        | 1.5%    |
| ArcoLinux Rolling            | 19        | 1.43%   |
| ROSA R11                     | 18        | 1.35%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 1.35%   |
| Linux Mint 20.1              | 17        | 1.28%   |
| KDE neon 20.04               | 17        | 1.28%   |
| Zorin 16                     | 16        | 1.2%    |
| Ubuntu 22.10                 | 16        | 1.2%    |
| ROSA R10                     | 16        | 1.2%    |
| OpenMandriva 23.08           | 16        | 1.2%    |
| Arch                         | 16        | 1.2%    |
| Linux Mint 20.3              | 15        | 1.13%   |
| Linux Mint 19.3              | 14        | 1.05%   |
| Ubuntu 19.04                 | 13        | 0.98%   |
| Linux Mint 21.1              | 13        | 0.98%   |
| Linux Mint 20.2              | 13        | 0.98%   |
| Linux Mint 20                | 13        | 0.98%   |
| Kubuntu 20.04                | 13        | 0.98%   |
| Zorin 15                     | 12        | 0.9%    |
| Xubuntu 18.04                | 12        | 0.9%    |
| OpenMandriva 23.03           | 12        | 0.9%    |
| Xubuntu 20.04                | 11        | 0.83%   |
| Ubuntu 23.10                 | 11        | 0.83%   |
| Ubuntu 19.10                 | 11        | 0.83%   |
| Linux Mint 21.2              | 11        | 0.83%   |
| Ubuntu 20.10                 | 10        | 0.75%   |
| Pop!_OS 20.10                | 10        | 0.75%   |
| Kubuntu 22.04                | 10        | 0.75%   |
| Fedora 33                    | 10        | 0.75%   |
| LMDE 4                       | 9         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 360       | 29.65%  |
| Linux Mint    | 98        | 8.07%   |
| OpenMandriva  | 91        | 7.5%    |
| Fedora        | 79        | 6.51%   |
| Manjaro       | 55        | 4.53%   |
| Debian        | 55        | 4.53%   |
| ROSA          | 52        | 4.28%   |
| Pop!_OS       | 49        | 4.04%   |
| Arch          | 37        | 3.05%   |
| Zorin         | 31        | 2.55%   |
| Kubuntu       | 30        | 2.47%   |
| Xubuntu       | 28        | 2.31%   |
| Endless       | 28        | 2.31%   |
| KDE neon      | 27        | 2.22%   |
| openSUSE      | 23        | 1.89%   |
| Kali          | 21        | 1.73%   |
| ArcoLinux     | 21        | 1.73%   |
| Ubuntu Unity  | 12        | 0.99%   |
| Clear Linux   | 12        | 0.99%   |
| LMDE          | 9         | 0.74%   |
| CentOS        | 8         | 0.66%   |
| Lubuntu       | 7         | 0.58%   |
| Gentoo        | 7         | 0.58%   |
| Elementary    | 6         | 0.49%   |
| EndeavourOS   | 5         | 0.41%   |
| Artix         | 5         | 0.41%   |
| Ubuntu MATE   | 4         | 0.33%   |
| SteamOS       | 4         | 0.33%   |
| Void Linux    | 3         | 0.25%   |
| Ubuntu Budgie | 3         | 0.25%   |
| Parrot        | 3         | 0.25%   |
| MX            | 3         | 0.25%   |
| Xero          | 2         | 0.16%   |
| Ubuntu Studio | 2         | 0.16%   |
| Novos         | 2         | 0.16%   |
| NixOS         | 2         | 0.16%   |
| Mageia        | 2         | 0.16%   |
| Garuda Linux  | 2         | 0.16%   |
| Deepin        | 2         | 0.16%   |
| BunsenLabs    | 2         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 30        | 2.04%   |
| 5.16.7-desktop-1omv4003         | 21        | 1.43%   |
| 5.4.0-42-generic                | 17        | 1.16%   |
| 6.4.11-desktop-1omv2390         | 13        | 0.89%   |
| 5.4.0-58-generic                | 13        | 0.89%   |
| 5.15.0-56-generic               | 13        | 0.89%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 13        | 0.89%   |
| 6.2.6-desktop-1omv2390          | 11        | 0.75%   |
| 5.3.0-40-generic                | 10        | 0.68%   |
| 5.9.16-1-MANJARO                | 8         | 0.54%   |
| 5.4.0-26-generic                | 8         | 0.54%   |
| 6.2.0-39-generic                | 7         | 0.48%   |
| 6.2.0-26-generic                | 7         | 0.48%   |
| 5.4.0-48-generic                | 7         | 0.48%   |
| 5.4.0-29-generic                | 7         | 0.48%   |
| 5.3.0-28-generic                | 7         | 0.48%   |
| 5.10.0-8-amd64                  | 7         | 0.48%   |
| 5.0.0-37-generic                | 7         | 0.48%   |
| 6.5.0-27-generic                | 6         | 0.41%   |
| 6.2.6-76060206-generic          | 6         | 0.41%   |
| 5.8.0-14-generic                | 6         | 0.41%   |
| 5.4.0-65-generic                | 6         | 0.41%   |
| 5.4.0-56-generic                | 6         | 0.41%   |
| 5.4.0-40-generic                | 6         | 0.41%   |
| 5.3.0-46-generic                | 6         | 0.41%   |
| 5.3.0-42-generic                | 6         | 0.41%   |
| 5.19.0-35-generic               | 6         | 0.41%   |
| 5.11.0-37-generic               | 6         | 0.41%   |
| 5.11.0-27-generic               | 6         | 0.41%   |
| 5.0.0-23-generic                | 6         | 0.41%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 6         | 0.41%   |
| 4.15.0-20-generic               | 6         | 0.41%   |
| 6.5.0-14-generic                | 5         | 0.34%   |
| 6.1.1-desktop-1omv2290          | 5         | 0.34%   |
| 5.8.0-7642-generic              | 5         | 0.34%   |
| 5.8.0-43-generic                | 5         | 0.34%   |
| 5.4.0-91-generic                | 5         | 0.34%   |
| 5.4.0-90-generic                | 5         | 0.34%   |
| 5.4.0-77-generic                | 5         | 0.34%   |
| 5.4.0-67-generic                | 5         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 170       | 12.22%  |
| 5.15.0  | 105       | 7.55%   |
| 4.15.0  | 80        | 5.75%   |
| 5.8.0   | 54        | 3.88%   |
| 5.3.0   | 49        | 3.52%   |
| 6.5.0   | 41        | 2.95%   |
| 6.2.0   | 41        | 2.95%   |
| 5.19.0  | 40        | 2.88%   |
| 5.11.0  | 39        | 2.8%    |
| 5.10.0  | 38        | 2.73%   |
| 5.13.0  | 37        | 2.66%   |
| 5.0.0   | 37        | 2.66%   |
| 5.10.14 | 31        | 2.23%   |
| 4.18.0  | 23        | 1.65%   |
| 5.16.7  | 21        | 1.51%   |
| 6.2.6   | 18        | 1.29%   |
| 6.4.11  | 14        | 1.01%   |
| 6.1.0   | 14        | 1.01%   |
| 4.19.0  | 13        | 0.93%   |
| 5.9.16  | 11        | 0.79%   |
| 4.9.20  | 9         | 0.65%   |
| 6.1.1   | 8         | 0.58%   |
| 5.17.5  | 8         | 0.58%   |
| 6.6.10  | 7         | 0.5%    |
| 5.14.0  | 7         | 0.5%    |
| 6.6.8   | 6         | 0.43%   |
| 6.0.0   | 6         | 0.43%   |
| 5.18.0  | 6         | 0.43%   |
| 4.9.60  | 6         | 0.43%   |
| 4.4.0   | 6         | 0.43%   |
| 6.8.0   | 5         | 0.36%   |
| 6.5.5   | 5         | 0.36%   |
| 5.8.18  | 5         | 0.36%   |
| 4.9.124 | 5         | 0.36%   |
| 6.7.4   | 4         | 0.29%   |
| 6.6.2   | 4         | 0.29%   |
| 6.5.7   | 4         | 0.29%   |
| 6.4.8   | 4         | 0.29%   |
| 6.2.9   | 4         | 0.29%   |
| 6.0.12  | 4         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 181       | 13.31%  |
| 5.15    | 137       | 10.07%  |
| 5.10    | 96        | 7.06%   |
| 4.15    | 80        | 5.88%   |
| 6.2     | 76        | 5.59%   |
| 5.8     | 67        | 4.93%   |
| 6.5     | 64        | 4.71%   |
| 5.3     | 58        | 4.26%   |
| 5.11    | 51        | 3.75%   |
| 5.19    | 49        | 3.6%    |
| 5.13    | 43        | 3.16%   |
| 6.1     | 42        | 3.09%   |
| 5.16    | 40        | 2.94%   |
| 5.0     | 40        | 2.94%   |
| 6.6     | 37        | 2.72%   |
| 6.4     | 32        | 2.35%   |
| 4.9     | 26        | 1.91%   |
| 4.18    | 24        | 1.76%   |
| 5.17    | 20        | 1.47%   |
| 6.0     | 18        | 1.32%   |
| 4.19    | 18        | 1.32%   |
| 5.9     | 17        | 1.25%   |
| 5.14    | 17        | 1.25%   |
| 5.6     | 16        | 1.18%   |
| 6.7     | 15        | 1.1%    |
| 6.3     | 14        | 1.03%   |
| 5.18    | 13        | 0.96%   |
| 5.7     | 12        | 0.88%   |
| 5.12    | 12        | 0.88%   |
| 6.8     | 11        | 0.81%   |
| 5.5     | 7         | 0.51%   |
| 4.4     | 6         | 0.44%   |
| 5.2     | 5         | 0.37%   |
| 4.1     | 4         | 0.29%   |
| 5.1     | 3         | 0.22%   |
| 3.10    | 3         | 0.22%   |
| 4.7     | 1         | 0.07%   |
| 4.20    | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 4.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1130      | 97.16%  |
| i686    | 30        | 2.58%   |
| aarch64 | 3         | 0.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 493       | 39.57%  |
| KDE5             | 238       | 19.1%   |
| Unknown          | 136       | 10.91%  |
| XFCE             | 111       | 8.91%   |
| X-Cinnamon       | 81        | 6.5%    |
| KDE4             | 33        | 2.65%   |
| KDE              | 29        | 2.33%   |
| MATE             | 28        | 2.25%   |
| Cinnamon         | 20        | 1.61%   |
| LXQt             | 13        | 1.04%   |
| Unity            | 12        | 0.96%   |
| i3               | 7         | 0.56%   |
| Budgie           | 7         | 0.56%   |
| Pantheon         | 6         | 0.48%   |
| GNOME Flashback  | 5         | 0.4%    |
| GNOME Classic    | 4         | 0.32%   |
| Deepin           | 4         | 0.32%   |
| bspwm            | 3         | 0.24%   |
| xmonad           | 2         | 0.16%   |
| qtile            | 2         | 0.16%   |
| LXDE             | 2         | 0.16%   |
| lightdm-xsession | 2         | 0.16%   |
| KDE6             | 2         | 0.16%   |
| trinity          | 1         | 0.08%   |
| sway             | 1         | 0.08%   |
| openbox          | 1         | 0.08%   |
| icewm            | 1         | 0.08%   |
| DWM              | 1         | 0.08%   |
| awesome          | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 908       | 74.98%  |
| Wayland | 212       | 17.51%  |
| Unknown | 70        | 5.78%   |
| Tty     | 21        | 1.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 556       | 45.5%   |
| SDDM    | 214       | 17.51%  |
| GDM3    | 154       | 12.6%   |
| LightDM | 131       | 10.72%  |
| GDM     | 99        | 8.1%    |
| TDM     | 33        | 2.7%    |
| KDM     | 32        | 2.62%   |
| XDM     | 2         | 0.16%   |
| MDM     | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 759       | 62.99%  |
| bg_BG   | 211       | 17.51%  |
| Unknown | 143       | 11.87%  |
| C       | 27        | 2.24%   |
| en_GB   | 25        | 2.07%   |
| ru_RU   | 10        | 0.83%   |
| de_DE   | 8         | 0.66%   |
| POSIX   | 3         | 0.25%   |
| it_IT   | 2         | 0.17%   |
| en_DK   | 2         | 0.17%   |
| C.UTF8  | 2         | 0.17%   |
| uk_UA   | 1         | 0.08%   |
| tr_TR   | 1         | 0.08%   |
| sv_SE   | 1         | 0.08%   |
| ru_UA   | 1         | 0.08%   |
| ia_FR   | 1         | 0.08%   |
| hu_HU   | 1         | 0.08%   |
| fr_FR   | 1         | 0.08%   |
| es_ES   | 1         | 0.08%   |
| en_NZ   | 1         | 0.08%   |
| en_CA   | 1         | 0.08%   |
| en_AU   | 1         | 0.08%   |
| en_AG   | 1         | 0.08%   |
| Default | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 662       | 55.44%  |
| EFI  | 532       | 44.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 860       | 71.37%  |
| Btrfs   | 103       | 8.55%   |
| Overlay | 91        | 7.55%   |
| Unknown | 56        | 4.65%   |
| Tmpfs   | 54        | 4.48%   |
| Xfs     | 23        | 1.91%   |
| Zfs     | 9         | 0.75%   |
| Ext3    | 4         | 0.33%   |
| Ext2    | 3         | 0.25%   |
| Jfs     | 1         | 0.08%   |
| F2fs    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 576       | 47.96%  |
| GPT     | 457       | 38.05%  |
| MBR     | 168       | 13.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1012      | 85.04%  |
| Yes       | 178       | 14.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 814       | 68.75%  |
| Yes       | 370       | 31.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 231       | 19.9%   |
| ASUSTek Computer                     | 193       | 16.62%  |
| Hewlett-Packard                      | 167       | 14.38%  |
| Dell                                 | 141       | 12.14%  |
| ASRock                               | 82        | 7.06%   |
| Acer                                 | 78        | 6.72%   |
| Gigabyte Technology                  | 68        | 5.86%   |
| MSI                                  | 42        | 3.62%   |
| Toshiba                              | 34        | 2.93%   |
| Fujitsu                              | 18        | 1.55%   |
| Apple                                | 13        | 1.12%   |
| Intel                                | 10        | 0.86%   |
| Foxconn                              | 9         | 0.78%   |
| Fujitsu Siemens                      | 6         | 0.52%   |
| Unknown                              | 6         | 0.52%   |
| AMI                                  | 5         | 0.43%   |
| Valve                                | 4         | 0.34%   |
| Sony                                 | 4         | 0.34%   |
| Samsung Electronics                  | 4         | 0.34%   |
| Pegatron                             | 4         | 0.34%   |
| TUXEDO                               | 3         | 0.26%   |
| Packard Bell                         | 3         | 0.26%   |
| HUAWEI                               | 3         | 0.26%   |
| Wibtek                               | 2         | 0.17%   |
| Medion                               | 2         | 0.17%   |
| Google                               | 2         | 0.17%   |
| ECS                                  | 2         | 0.17%   |
| Timi                                 | 1         | 0.09%   |
| Thecus                               | 1         | 0.09%   |
| System76                             | 1         | 0.09%   |
| Supermicro                           | 1         | 0.09%   |
| Shuttle                              | 1         | 0.09%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.09%   |
| Seco                                 | 1         | 0.09%   |
| Razer                                | 1         | 0.09%   |
| Raspberry Pi Foundation              | 1         | 0.09%   |
| Radxa                                | 1         | 0.09%   |
| Pine Microsystems                    | 1         | 0.09%   |
| ONDA                                 | 1         | 0.09%   |
| Notebook                             | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 10        | 0.86%   |
| ASUS All Series                            | 7         | 0.6%    |
| Lenovo G500 20236                          | 5         | 0.43%   |
| Dell Inspiron N5110                        | 5         | 0.43%   |
| ASUS X541NA                                | 5         | 0.43%   |
| Valve Jupiter                              | 4         | 0.34%   |
| Lenovo H520S 2561                          | 4         | 0.34%   |
| HP ProBook 4540s                           | 4         | 0.34%   |
| HP ProBook 450 G8 Notebook PC              | 4         | 0.34%   |
| MSI MS-7C56                                | 3         | 0.26%   |
| MSI MS-7C37                                | 3         | 0.26%   |
| Lenovo Y520-15IKBN 80WK                    | 3         | 0.26%   |
| HP ProBook 450 G0                          | 3         | 0.26%   |
| HP Pavilion 15                             | 3         | 0.26%   |
| HP Notebook                                | 3         | 0.26%   |
| HP 255 G8 Notebook PC                      | 3         | 0.26%   |
| Gigabyte B550 GAMING X V2                  | 3         | 0.26%   |
| Dell Precision Tower 5810                  | 3         | 0.26%   |
| Dell Precision M4600                       | 3         | 0.26%   |
| Dell OptiPlex 780                          | 3         | 0.26%   |
| Dell Latitude E6410                        | 3         | 0.26%   |
| Dell Latitude E4300                        | 3         | 0.26%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA   | 3         | 0.26%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.26%   |
| ASUS N551VW                                | 3         | 0.26%   |
| ASRock Z97 Anniversary                     | 3         | 0.26%   |
| ASRock B450M Steel Legend                  | 3         | 0.26%   |
| Acer Aspire 5738                           | 3         | 0.26%   |
| Wibtek H61-M HDMI2                         | 2         | 0.17%   |
| Toshiba Satellite L300                     | 2         | 0.17%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.17%   |
| Toshiba Satellite A300                     | 2         | 0.17%   |
| Toshiba Satellite A200                     | 2         | 0.17%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.17%   |
| MSI Modern 15 A5M                          | 2         | 0.17%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.17%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.17%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.17%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.17%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 103       | 8.87%   |
| Acer Aspire        | 54        | 4.65%   |
| Lenovo IdeaPad     | 44        | 3.79%   |
| Dell Latitude      | 42        | 3.62%   |
| HP ProBook         | 34        | 2.93%   |
| Dell Inspiron      | 32        | 2.76%   |
| Toshiba Satellite  | 28        | 2.41%   |
| HP Compaq          | 27        | 2.33%   |
| HP Pavilion        | 26        | 2.24%   |
| HP EliteBook       | 26        | 2.24%   |
| ASUS VivoBook      | 24        | 2.07%   |
| ASUS ROG           | 20        | 1.72%   |
| Dell Precision     | 19        | 1.64%   |
| Dell OptiPlex      | 16        | 1.38%   |
| Dell Vostro        | 15        | 1.29%   |
| Lenovo Legion      | 14        | 1.21%   |
| ASUS PRIME         | 13        | 1.12%   |
| Lenovo ThinkCentre | 10        | 0.86%   |
| Fujitsu ESPRIMO    | 10        | 0.86%   |
| Unknown            | 10        | 0.86%   |
| Lenovo Yoga        | 9         | 0.78%   |
| ASUS TUF           | 8         | 0.69%   |
| HP 255             | 7         | 0.6%    |
| Dell XPS           | 7         | 0.6%    |
| ASUS All           | 7         | 0.6%    |
| MSI Modern         | 6         | 0.52%   |
| Lenovo ThinkBook   | 6         | 0.52%   |
| HP Laptop          | 6         | 0.52%   |
| ASUS P5K           | 6         | 0.52%   |
| Acer Nitro         | 6         | 0.52%   |
| Lenovo G500        | 5         | 0.43%   |
| ASUS X541NA        | 5         | 0.43%   |
| ASUS ASUS          | 5         | 0.43%   |
| Acer Predator      | 5         | 0.43%   |
| Valve Jupiter      | 4         | 0.34%   |
| Lenovo V15         | 4         | 0.34%   |
| Lenovo H520S       | 4         | 0.34%   |
| HP ZBook           | 4         | 0.34%   |
| HP ProDesk         | 4         | 0.34%   |
| HP EliteDesk       | 4         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 95        | 8.18%   |
| 2019    | 94        | 8.1%    |
| 2020    | 92        | 7.92%   |
| 2012    | 92        | 7.92%   |
| 2017    | 87        | 7.49%   |
| 2013    | 87        | 7.49%   |
| 2018    | 82        | 7.06%   |
| 2021    | 69        | 5.94%   |
| 2014    | 69        | 5.94%   |
| 2015    | 59        | 5.08%   |
| 2008    | 59        | 5.08%   |
| 2010    | 58        | 5%      |
| 2022    | 52        | 4.48%   |
| 2009    | 48        | 4.13%   |
| 2007    | 38        | 3.27%   |
| 2016    | 37        | 3.19%   |
| 2023    | 19        | 1.64%   |
| 2006    | 16        | 1.38%   |
| 2005    | 3         | 0.26%   |
| Unknown | 3         | 0.26%   |
| 2004    | 2         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 710       | 61.15%  |
| Desktop        | 413       | 35.57%  |
| Convertible    | 14        | 1.21%   |
| Mini pc        | 9         | 0.78%   |
| All in one     | 6         | 0.52%   |
| Tablet         | 4         | 0.34%   |
| System on chip | 2         | 0.17%   |
| Server         | 2         | 0.17%   |
| Phone          | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1105      | 94.69%  |
| Enabled  | 62        | 5.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1157      | 99.66%  |
| Yes  | 4         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 302       | 25.36%  |
| 8.01-16.0       | 230       | 19.31%  |
| 3.01-4.0        | 228       | 19.14%  |
| 16.01-24.0      | 198       | 16.62%  |
| 32.01-64.0      | 110       | 9.24%   |
| 1.01-2.0        | 35        | 2.94%   |
| 24.01-32.0      | 34        | 2.85%   |
| 2.01-3.0        | 25        | 2.1%    |
| 64.01-256.0     | 23        | 1.93%   |
| 0.51-1.0        | 4         | 0.34%   |
| More than 256.0 | 2         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 401       | 30.04%  |
| 2.01-3.0   | 364       | 27.27%  |
| 4.01-8.0   | 200       | 14.98%  |
| 3.01-4.0   | 200       | 14.98%  |
| 0.51-1.0   | 88        | 6.59%   |
| 8.01-16.0  | 61        | 4.57%   |
| 16.01-24.0 | 9         | 0.67%   |
| 0.01-0.5   | 8         | 0.6%    |
| 24.01-32.0 | 2         | 0.15%   |
| 32.01-64.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 738       | 61.35%  |
| 2      | 309       | 25.69%  |
| 3      | 81        | 6.73%   |
| 4      | 28        | 2.33%   |
| 5      | 20        | 1.66%   |
| 6      | 11        | 0.91%   |
| 0      | 8         | 0.67%   |
| 8      | 3         | 0.25%   |
| 7      | 3         | 0.25%   |
| 11     | 1         | 0.08%   |
| 9      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 714       | 60.66%  |
| Yes       | 463       | 39.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1041      | 89.36%  |
| No        | 124       | 10.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 861       | 73.72%  |
| No        | 307       | 26.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 697       | 59.17%  |
| No        | 481       | 40.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Bulgaria | 1161      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Sofia               | 602       | 49.02%  |
| Varna               | 98        | 7.98%   |
| Plovdiv             | 79        | 6.43%   |
| Burgas              | 53        | 4.32%   |
| Stara Zagora        | 26        | 2.12%   |
| Rousse              | 18        | 1.47%   |
| Pernik              | 17        | 1.38%   |
| Pleven              | 16        | 1.3%    |
| Yambol              | 13        | 1.06%   |
| Veliko Tarnovo      | 13        | 1.06%   |
| Shumen              | 12        | 0.98%   |
| Dobrich             | 12        | 0.98%   |
| Montana             | 11        | 0.9%    |
| Haskovo             | 11        | 0.9%    |
| Pazardzhik          | 10        | 0.81%   |
| Gabrovo             | 10        | 0.81%   |
| Sliven              | 8         | 0.65%   |
| Kazanlak            | 8         | 0.65%   |
| Asenovgrad          | 8         | 0.65%   |
| Blagoevgrad         | 7         | 0.57%   |
| Vratsa              | 6         | 0.49%   |
| Svilengrad          | 6         | 0.49%   |
| Razgrad             | 6         | 0.49%   |
| Vidin               | 5         | 0.41%   |
| Kyustendil          | 5         | 0.41%   |
| Gorna Oryahovitsa   | 5         | 0.41%   |
| Sistov              | 4         | 0.33%   |
| Silistra            | 4         | 0.33%   |
| Nesebar             | 4         | 0.33%   |
| Karlovo             | 4         | 0.33%   |
| Svoge               | 3         | 0.24%   |
| Smolyan             | 3         | 0.24%   |
| Petrich             | 3         | 0.24%   |
| Kardzhali           | 3         | 0.24%   |
| Dimitrovgrad        | 3         | 0.24%   |
| Botevgrad           | 3         | 0.24%   |
| Velingrad           | 2         | 0.16%   |
| Troyan Municipality | 2         | 0.16%   |
| Teteven             | 2         | 0.16%   |
| Targovishte         | 2         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 253       | 386    | 14.99%  |
| Seagate                     | 237       | 360    | 14.04%  |
| WDC                         | 223       | 335    | 13.21%  |
| Toshiba                     | 125       | 168    | 7.41%   |
| Kingston                    | 98        | 149    | 5.81%   |
| Hitachi                     | 84        | 112    | 4.98%   |
| SanDisk                     | 64        | 80     | 3.79%   |
| A-DATA Technology           | 58        | 78     | 3.44%   |
| Unknown                     | 51        | 66     | 3.02%   |
| Intel                       | 50        | 69     | 2.96%   |
| HGST                        | 41        | 62     | 2.43%   |
| SK hynix                    | 37        | 48     | 2.19%   |
| Micron Technology           | 34        | 40     | 2.01%   |
| Crucial                     | 31        | 47     | 1.84%   |
| SPCC                        | 24        | 29     | 1.42%   |
| Team                        | 21        | 22     | 1.24%   |
| KIOXIA                      | 17        | 18     | 1.01%   |
| China                       | 16        | 20     | 0.95%   |
| Transcend                   | 15        | 16     | 0.89%   |
| Phison Electronics          | 12        | 18     | 0.71%   |
| Kingston Technology Company | 11        | 13     | 0.65%   |
| KingSpec                    | 11        | 13     | 0.65%   |
| Fujitsu                     | 10        | 13     | 0.59%   |
| Silicon Motion              | 9         | 12     | 0.53%   |
| Phison                      | 9         | 10     | 0.53%   |
| Patriot                     | 9         | 11     | 0.53%   |
| Realtek Semiconductor       | 7         | 11     | 0.41%   |
| Maxtor                      | 7         | 13     | 0.41%   |
| LITEON                      | 7         | 10     | 0.41%   |
| PNY                         | 6         | 7      | 0.36%   |
| JMicron Technology          | 6         | 9      | 0.36%   |
| Apple                       | 6         | 8      | 0.36%   |
| XPG                         | 5         | 7      | 0.3%    |
| Intenso                     | 5         | 5      | 0.3%    |
| ADATA Technology            | 5         | 5      | 0.3%    |
| TO Exter                    | 4         | 4      | 0.24%   |
| Teclast                     | 4         | 4      | 0.24%   |
| LITEONIT                    | 4         | 4      | 0.24%   |
| Hewlett-Packard             | 4         | 8      | 0.24%   |
| GOODRAM                     | 4         | 4      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 19        | 1.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 19        | 1.03%   |
| Seagate ST500DM002-1BD142 500GB                    | 18        | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 18        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                    | 18        | 0.98%   |
| Kingston SA400S37120G 120GB SSD                    | 18        | 0.98%   |
| Toshiba MQ01ABF050 500GB                           | 15        | 0.82%   |
| Toshiba MQ01ABD100 1TB                             | 15        | 0.82%   |
| Samsung SSD 860 EVO 250GB                          | 15        | 0.82%   |
| Samsung SSD 850 EVO 250GB                          | 15        | 0.82%   |
| HGST HTS721010A9E630 1TB                           | 15        | 0.82%   |
| Samsung SSD 860 EVO 500GB                          | 14        | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB                     | 13        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                       | 12        | 0.65%   |
| Kingston SA400S37480G 480GB SSD                    | 12        | 0.65%   |
| Toshiba DT01ACA100 1TB                             | 10        | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB                     | 10        | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 9         | 0.49%   |
| Unknown MMC Card  64GB                             | 9         | 0.49%   |
| Unknown MMC Card  32GB                             | 9         | 0.49%   |
| SPCC Solid State Disk 512GB                        | 9         | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 9         | 0.49%   |
| Toshiba DT01ACA050 500GB                           | 8         | 0.43%   |
| Seagate ST500LT012-1DG142 500GB                    | 8         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                       | 8         | 0.43%   |
| Samsung SSD 850 PRO 256GB                          | 8         | 0.43%   |
| Hitachi HDP725050GLA360 500GB                      | 8         | 0.43%   |
| HGST HTS541010A9E680 1TB                           | 8         | 0.43%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 7         | 0.38%   |
| Samsung SSD 850 EVO 500GB                          | 7         | 0.38%   |
| Samsung NVMe SSD Drive 500GB                       | 7         | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                   | 7         | 0.38%   |
| Intel SSDSC2CW120A3 120GB                          | 7         | 0.38%   |
| A-DATA SU650 240GB SSD                             | 7         | 0.38%   |
| Toshiba MQ04ABF100 1TB                             | 6         | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB                     | 6         | 0.33%   |
| Samsung SSD 970 EVO 250GB                          | 6         | 0.33%   |
| Hitachi HDS721050CLA362 500GB                      | 6         | 0.33%   |
| A-DATA SU650 120GB SSD                             | 6         | 0.33%   |
| WDC WD2003FZEX-00SRLA0 2TB                         | 5         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 234       | 355    | 33.19%  |
| WDC                 | 196       | 289    | 27.8%   |
| Toshiba             | 99        | 132    | 14.04%  |
| Hitachi             | 84        | 112    | 11.91%  |
| HGST                | 41        | 62     | 5.82%   |
| Samsung Electronics | 12        | 15     | 1.7%    |
| Fujitsu             | 10        | 13     | 1.42%   |
| Maxtor              | 7         | 13     | 0.99%   |
| JMicron Technology  | 5         | 6      | 0.71%   |
| TO Exter            | 4         | 4      | 0.57%   |
| Unknown             | 3         | 4      | 0.43%   |
| Hewlett-Packard     | 3         | 8      | 0.43%   |
| ExcelStor           | 3         | 7      | 0.43%   |
| IBM/Hitachi         | 1         | 2      | 0.14%   |
| HGST HTS            | 1         | 1      | 0.14%   |
| ASMedia             | 1         | 1      | 0.14%   |
| Apple               | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 121       | 160    | 22.79%  |
| Kingston            | 72        | 96     | 13.56%  |
| A-DATA Technology   | 50        | 68     | 9.42%   |
| SanDisk             | 33        | 39     | 6.21%   |
| Crucial             | 27        | 41     | 5.08%   |
| SPCC                | 22        | 27     | 4.14%   |
| WDC                 | 21        | 31     | 3.95%   |
| Intel               | 21        | 29     | 3.95%   |
| Team                | 20        | 21     | 3.77%   |
| China               | 16        | 20     | 3.01%   |
| Transcend           | 13        | 14     | 2.45%   |
| KingSpec            | 11        | 13     | 2.07%   |
| Micron Technology   | 10        | 11     | 1.88%   |
| Patriot             | 9         | 11     | 1.69%   |
| Toshiba             | 8         | 9      | 1.51%   |
| LITEON              | 7         | 10     | 1.32%   |
| PNY                 | 6         | 7      | 1.13%   |
| Intenso             | 5         | 5      | 0.94%   |
| Teclast             | 4         | 4      | 0.75%   |
| LITEONIT            | 4         | 4      | 0.75%   |
| GOODRAM             | 4         | 4      | 0.75%   |
| Apple               | 4         | 6      | 0.75%   |
| AMD                 | 4         | 6      | 0.75%   |
| Verbatim            | 3         | 3      | 0.56%   |
| SK hynix            | 3         | 3      | 0.56%   |
| OCZ                 | 3         | 3      | 0.56%   |
| Lexar               | 3         | 3      | 0.56%   |
| Seagate             | 2         | 3      | 0.38%   |
| Innodisk            | 2         | 2      | 0.38%   |
| XrayDisk            | 1         | 1      | 0.19%   |
| XPG                 | 1         | 1      | 0.19%   |
| Wibtek              | 1         | 2      | 0.19%   |
| VT                  | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |
| StoreJet            | 1         | 1      | 0.19%   |
| SSK                 | 1         | 1      | 0.19%   |
| Origin              | 1         | 3      | 0.19%   |
| OCZ-VERTEX3         | 1         | 1      | 0.19%   |
| Netac               | 1         | 4      | 0.19%   |
| Indilinx            | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 613       | 1025   | 40.12%  |
| SSD     | 474       | 693    | 31.02%  |
| NVMe    | 386       | 599    | 25.26%  |
| MMC     | 44        | 54     | 2.88%   |
| Unknown | 11        | 15     | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 874       | 1671   | 64.6%   |
| NVMe | 385       | 597    | 28.46%  |
| SAS  | 50        | 64     | 3.7%    |
| MMC  | 44        | 54     | 3.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 679       | 1055   | 61.73%  |
| 0.51-1.0   | 319       | 492    | 29%     |
| 1.01-2.0   | 51        | 71     | 4.64%   |
| 3.01-4.0   | 24        | 46     | 2.18%   |
| 2.01-3.0   | 12        | 19     | 1.09%   |
| 4.01-10.0  | 10        | 16     | 0.91%   |
| 10.01-20.0 | 5         | 19     | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 314       | 25.34%  |
| 251-500        | 287       | 23.16%  |
| 501-1000       | 195       | 15.74%  |
| 1001-2000      | 111       | 8.96%   |
| 1-20           | 99        | 7.99%   |
| 51-100         | 85        | 6.86%   |
| 21-50          | 49        | 3.95%   |
| More than 3000 | 43        | 3.47%   |
| Unknown        | 31        | 2.5%    |
| 2001-3000      | 25        | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 483       | 36.56%  |
| 21-50          | 228       | 17.26%  |
| 101-250        | 171       | 12.94%  |
| 51-100         | 155       | 11.73%  |
| 251-500        | 103       | 7.8%    |
| 501-1000       | 86        | 6.51%   |
| 1001-2000      | 38        | 2.88%   |
| Unknown        | 31        | 2.35%   |
| More than 3000 | 15        | 1.14%   |
| 2001-3000      | 11        | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD6000HLHX-01JJPV0 600GB        | 3         | 5      | 2.29%   |
| Seagate ST9500325AS 500GB           | 3         | 3      | 2.29%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 2.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 2.29%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 3      | 2.29%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 2         | 2      | 1.53%   |
| WDC WD5000LPVX-55V0TT0 500GB        | 2         | 2      | 1.53%   |
| WDC WD5000AAKX-603CA0 500GB         | 2         | 6      | 1.53%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 1.53%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 1.53%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 2      | 1.53%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 2      | 1.53%   |
| KingSpec P3-128 128GB SSD           | 2         | 3      | 1.53%   |
| Intel SSDSC2CW120A3 120GB           | 2         | 2      | 1.53%   |
| Hitachi HDP725050GLA360 500GB       | 2         | 3      | 1.53%   |
| HGST HTS721010A9E630 1TB            | 2         | 2      | 1.53%   |
| China SSD 120GB                     | 2         | 2      | 1.53%   |
| A-DATA Technology SU900 256GB SSD   | 2         | 2      | 1.53%   |
| A-DATA Technology SU650 120GB SSD   | 2         | 2      | 1.53%   |
| WDC WDS100T2B0B-00YS70 1TB SSD      | 1         | 1      | 0.76%   |
| WDC WD5000BEVT-75A0RT0 500GB        | 1         | 1      | 0.76%   |
| WDC WD5000AZLX-60K2TA0 500GB        | 1         | 1      | 0.76%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 2      | 0.76%   |
| WDC WD5000AACS-00G8B1 500GB         | 1         | 1      | 0.76%   |
| WDC WD40PURX-64GVNY0 4TB            | 1         | 1      | 0.76%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 0.76%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1         | 2      | 0.76%   |
| WDC WD2500JS-00MHB0 250GB           | 1         | 1      | 0.76%   |
| WDC WD2500AAKX-753CA1 250GB         | 1         | 1      | 0.76%   |
| WDC WD1600BEVT-80A23T0 160GB        | 1         | 1      | 0.76%   |
| WDC WD15EARS-00S8B1 1TB             | 1         | 1      | 0.76%   |
| WDC WD10EFRX-68PJCN0 1TB            | 1         | 2      | 0.76%   |
| WDC WD10EARS-00MVWB0 1TB            | 1         | 1      | 0.76%   |
| WDC WD1003FZEX-00K3CA0 1TB          | 1         | 1      | 0.76%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 0.76%   |
| Toshiba MK3252GSX 320GB             | 1         | 1      | 0.76%   |
| Toshiba MK2552GSX 250GB             | 1         | 3      | 0.76%   |
| Toshiba MK2035GSS 200GB             | 1         | 1      | 0.76%   |
| Toshiba MK1637GSX 160GB             | 1         | 1      | 0.76%   |
| Toshiba HDWD120 2TB                 | 1         | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 30     | 21.37%  |
| WDC                 | 24        | 33     | 18.32%  |
| Hitachi             | 14        | 16     | 10.69%  |
| Toshiba             | 12        | 14     | 9.16%   |
| A-DATA Technology   | 10        | 10     | 7.63%   |
| Samsung Electronics | 8         | 10     | 6.11%   |
| Intel               | 7         | 9      | 5.34%   |
| Kingston            | 5         | 5      | 3.82%   |
| SPCC                | 3         | 3      | 2.29%   |
| Maxtor              | 3         | 4      | 2.29%   |
| KingSpec            | 3         | 4      | 2.29%   |
| SK hynix            | 2         | 2      | 1.53%   |
| SanDisk             | 2         | 2      | 1.53%   |
| HGST                | 2         | 2      | 1.53%   |
| ExcelStor           | 2         | 3      | 1.53%   |
| China               | 2         | 2      | 1.53%   |
| Patriot             | 1         | 1      | 0.76%   |
| OCZ                 | 1         | 1      | 0.76%   |
| Lenovo              | 1         | 1      | 0.76%   |
| Fujitsu             | 1         | 2      | 0.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 28        | 30     | 32.94%  |
| WDC       | 23        | 32     | 27.06%  |
| Hitachi   | 14        | 16     | 16.47%  |
| Toshiba   | 12        | 14     | 14.12%  |
| Maxtor    | 3         | 4      | 3.53%   |
| HGST      | 2         | 2      | 2.35%   |
| ExcelStor | 2         | 3      | 2.35%   |
| Fujitsu   | 1         | 2      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 103    | 65.6%   |
| SSD  | 36        | 43     | 28.8%   |
| NVMe | 7         | 8      | 5.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT3 752GB | 1         | 1      | 33.33%  |
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 66.67%  |
| HGST   | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 693       | 1386   | 54.14%  |
| Works    | 465       | 843    | 36.33%  |
| Malfunc  | 119       | 154    | 9.3%    |
| Failed   | 3         | 3      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 801       | 54.31%  |
| AMD                              | 195       | 13.22%  |
| Samsung Electronics              | 145       | 9.83%   |
| SanDisk                          | 44        | 2.98%   |
| Kingston Technology Company      | 36        | 2.44%   |
| SK hynix                         | 34        | 2.31%   |
| Micron Technology                | 25        | 1.69%   |
| Phison Electronics               | 22        | 1.49%   |
| Nvidia                           | 21        | 1.42%   |
| JMicron Technology               | 20        | 1.36%   |
| KIOXIA                           | 19        | 1.29%   |
| ASMedia Technology               | 18        | 1.22%   |
| Toshiba America Info Systems     | 17        | 1.15%   |
| Realtek Semiconductor            | 14        | 0.95%   |
| ADATA Technology                 | 14        | 0.95%   |
| Silicon Motion                   | 11        | 0.75%   |
| Marvell Technology Group         | 11        | 0.75%   |
| Micron/Crucial Technology        | 5         | 0.34%   |
| Union Memory (Shenzhen)          | 4         | 0.27%   |
| Lenovo                           | 3         | 0.2%    |
| VIA Technologies                 | 2         | 0.14%   |
| Transcend                        | 2         | 0.14%   |
| Shenzhen Longsys Electronics     | 2         | 0.14%   |
| Hewlett-Packard                  | 2         | 0.14%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| O2 Micro                         | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| LSI Logic / Symbios Logic        | 1         | 0.07%   |
| Integrated Technology Express    | 1         | 0.07%   |
| Chelsio Communications           | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 124       | 7.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 73        | 4.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 69        | 4.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 57        | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 43        | 2.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 36        | 2.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 35        | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 32        | 1.87%   |
| Intel Volume Management Device NVMe RAID Controller                            | 30        | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 26        | 1.52%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 25        | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 23        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 23        | 1.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 21        | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 20        | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 19        | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 19        | 1.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 18        | 1.05%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 18        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 18        | 1.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 16        | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 16        | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 16        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 16        | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 16        | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 15        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                         | 14        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13        | 0.76%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 13        | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13        | 0.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.7%    |
| Nvidia MCP61 SATA Controller                                                   | 12        | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 0.7%    |
| Intel SSD 660P Series                                                          | 12        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 12        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 12        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 822       | 55.2%   |
| NVMe | 390       | 26.19%  |
| IDE  | 186       | 12.49%  |
| RAID | 88        | 5.91%   |
| SAS  | 2         | 0.13%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 879       | 75.71%  |
| AMD          | 278       | 23.94%  |
| ARM          | 3         | 0.26%   |
| CentaurHauls | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 13        | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 12        | 1.03%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 12        | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 11        | 0.95%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 10        | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 0.77%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 9         | 0.77%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 8         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 8         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 8         | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 8         | 0.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 8         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 7         | 0.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 7         | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 7         | 0.6%    |
| Intel Core i5-4590 CPU @ 3.30GHz         | 7         | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz        | 7         | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz        | 7         | 0.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 7         | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics   | 7         | 0.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics   | 7         | 0.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 6         | 0.52%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 6         | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 6         | 0.52%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 6         | 0.52%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 6         | 0.52%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 6         | 0.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.52%   |
| Intel Celeron CPU N3050 @ 1.60GHz        | 6         | 0.52%   |
| Intel 12th Gen Core i5-1235U             | 6         | 0.52%   |
| AMD Ryzen 5 5600X 6-Core Processor       | 6         | 0.52%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 6         | 0.52%   |
| AMD Ryzen 5 3600 6-Core Processor        | 6         | 0.52%   |
| AMD Ryzen 5 1600 Six-Core Processor      | 6         | 0.52%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 6         | 0.52%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.43%   |
| Intel Pentium CPU G645 @ 2.90GHz         | 5         | 0.43%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.43%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 5         | 0.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 5         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 236       | 20.27%  |
| Intel Core i7           | 208       | 17.87%  |
| Intel Core i3           | 81        | 6.96%   |
| Other                   | 78        | 6.7%    |
| AMD Ryzen 5             | 61        | 5.24%   |
| Intel Core 2 Duo        | 60        | 5.15%   |
| AMD Ryzen 7             | 57        | 4.9%    |
| Intel Celeron           | 55        | 4.73%   |
| Intel Pentium           | 49        | 4.21%   |
| Intel Xeon              | 26        | 2.23%   |
| AMD Ryzen 3             | 19        | 1.63%   |
| AMD Ryzen 9             | 18        | 1.55%   |
| Intel Core 2 Quad       | 17        | 1.46%   |
| Intel Pentium Dual-Core | 15        | 1.29%   |
| Intel Atom              | 14        | 1.2%    |
| AMD Athlon 64 X2        | 12        | 1.03%   |
| AMD Ryzen 7 PRO         | 11        | 0.95%   |
| AMD FX                  | 11        | 0.95%   |
| Intel Pentium Dual      | 10        | 0.86%   |
| Intel Core i9           | 8         | 0.69%   |
| AMD Ryzen 5 PRO         | 8         | 0.69%   |
| Intel Core 2            | 7         | 0.6%    |
| AMD Phenom II X4        | 7         | 0.6%    |
| AMD Athlon II X2        | 7         | 0.6%    |
| AMD A8                  | 7         | 0.6%    |
| Intel Pentium Silver    | 6         | 0.52%   |
| AMD A6                  | 6         | 0.52%   |
| AMD E1                  | 5         | 0.43%   |
| AMD Athlon 64           | 5         | 0.43%   |
| AMD Athlon II X4        | 4         | 0.34%   |
| AMD A10                 | 4         | 0.34%   |
| Intel Genuine           | 3         | 0.26%   |
| AMD Sempron             | 3         | 0.26%   |
| AMD E                   | 3         | 0.26%   |
| Intel Pentium M         | 2         | 0.17%   |
| Intel Pentium Gold      | 2         | 0.17%   |
| Intel Core m3           | 2         | 0.17%   |
| Intel Celeron Dual-Core | 2         | 0.17%   |
| AMD Turion 64 X2 Mobile | 2         | 0.17%   |
| AMD Phenom II X6        | 2         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 479       | 41.12%  |
| 4       | 383       | 32.88%  |
| 6       | 118       | 10.13%  |
| 8       | 89        | 7.64%   |
| 1       | 28        | 2.4%    |
| 12      | 19        | 1.63%   |
| 10      | 15        | 1.29%   |
| 3       | 11        | 0.94%   |
| 16      | 8         | 0.69%   |
| 14      | 7         | 0.6%    |
| Unknown | 3         | 0.26%   |
| 24      | 2         | 0.17%   |
| 18      | 2         | 0.17%   |
| 40      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1155      | 99.48%  |
| 2       | 4         | 0.34%   |
| 4       | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 736       | 63.18%  |
| 1       | 425       | 36.48%  |
| Unknown | 3         | 0.26%   |
| 4       | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1131      | 96.75%  |
| Unknown        | 26        | 2.22%   |
| 32-bit         | 11        | 0.94%   |
| 64-bit         | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 414       | 33.63%  |
| 0x306a9    | 68        | 5.52%   |
| 0x206a7    | 68        | 5.52%   |
| 0x306c3    | 51        | 4.14%   |
| 0x1067a    | 44        | 3.57%   |
| 0x806ec    | 27        | 2.19%   |
| 0x906ea    | 26        | 2.11%   |
| 0x506e3    | 24        | 1.95%   |
| 0x306d4    | 23        | 1.87%   |
| 0x906e9    | 20        | 1.62%   |
| 0x20655    | 20        | 1.62%   |
| 0x6fd      | 19        | 1.54%   |
| 0x406e3    | 19        | 1.54%   |
| 0x40651    | 19        | 1.54%   |
| 0x806ea    | 16        | 1.3%    |
| 0x806c1    | 16        | 1.3%    |
| 0x10676    | 15        | 1.22%   |
| 0x0a50000c | 13        | 1.06%   |
| 0x010000c8 | 13        | 1.06%   |
| 0x706a1    | 12        | 0.97%   |
| 0x506c9    | 12        | 0.97%   |
| 0x08108109 | 11        | 0.89%   |
| 0x08608103 | 10        | 0.81%   |
| 0x6fb      | 9         | 0.73%   |
| 0x806e9    | 8         | 0.65%   |
| 0xa0652    | 7         | 0.57%   |
| 0x406c3    | 7         | 0.57%   |
| 0x0a50000d | 7         | 0.57%   |
| 0x08600106 | 7         | 0.57%   |
| 0x08108102 | 7         | 0.57%   |
| 0x806eb    | 6         | 0.49%   |
| 0x6f6      | 6         | 0.49%   |
| 0x306f2    | 6         | 0.49%   |
| 0x0a404102 | 6         | 0.49%   |
| 0x08701021 | 6         | 0.49%   |
| 0x08600104 | 6         | 0.49%   |
| 0x0800820d | 6         | 0.49%   |
| 0x906a4    | 5         | 0.41%   |
| 0x706e5    | 5         | 0.41%   |
| 0x0a201009 | 5         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 156       | 13.41%  |
| Haswell          | 109       | 9.37%   |
| IvyBridge        | 101       | 8.68%   |
| SandyBridge      | 92        | 7.91%   |
| Penryn           | 77        | 6.62%   |
| Unknown          | 61        | 5.25%   |
| Skylake          | 59        | 5.07%   |
| Zen 3            | 52        | 4.47%   |
| Core             | 43        | 3.7%    |
| Zen 2            | 39        | 3.35%   |
| Westmere         | 34        | 2.92%   |
| Zen+             | 31        | 2.67%   |
| K10              | 30        | 2.58%   |
| TigerLake        | 29        | 2.49%   |
| Broadwell        | 28        | 2.41%   |
| Silvermont       | 25        | 2.15%   |
| Alderlake Hybrid | 23        | 1.98%   |
| K8 Hammer        | 21        | 1.81%   |
| CometLake        | 20        | 1.72%   |
| Zen              | 17        | 1.46%   |
| Goldmont plus    | 16        | 1.38%   |
| Goldmont         | 16        | 1.38%   |
| Piledriver       | 15        | 1.29%   |
| IceLake          | 14        | 1.2%    |
| Nehalem          | 8         | 0.69%   |
| Excavator        | 7         | 0.6%    |
| Bonnell          | 7         | 0.6%    |
| Steamroller      | 5         | 0.43%   |
| P6               | 5         | 0.43%   |
| Jaguar           | 5         | 0.43%   |
| Bobcat           | 5         | 0.43%   |
| Puma             | 3         | 0.26%   |
| K10 Llano        | 3         | 0.26%   |
| Bulldozer        | 3         | 0.26%   |
| NetBurst         | 2         | 0.17%   |
| Tremont          | 1         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 683       | 47.46%  |
| Nvidia                           | 409       | 28.42%  |
| AMD                              | 343       | 23.84%  |
| VIA Technologies                 | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Matrox Electronics Systems       | 1         | 0.07%   |
| ASPEED Technology                | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 71        | 4.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 65        | 4.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 26        | 1.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 26        | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 26        | 1.76%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 26        | 1.76%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 1.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 1.49%   |
| Intel HD Graphics 630                                                                    | 22        | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.42%   |
| Intel HD Graphics 530                                                                    | 18        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 18        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.22%   |
| Intel UHD Graphics 620                                                                   | 17        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.01%   |
| AMD Lucienne                                                                             | 15        | 1.01%   |
| Intel HD Graphics 620                                                                    | 14        | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 0.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.81%   |
| AMD Rembrandt [Radeon 680M]                                                              | 12        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 9         | 0.61%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.61%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 9         | 0.61%   |
| AMD Barcelo                                                                              | 9         | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 8         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 438       | 37.15%  |
| 1 x AMD        | 260       | 22.05%  |
| 1 x Nvidia     | 191       | 16.2%   |
| Intel + Nvidia | 191       | 16.2%   |
| Intel + AMD    | 42        | 3.56%   |
| AMD + Nvidia   | 28        | 2.37%   |
| 2 x AMD        | 17        | 1.44%   |
| Other          | 4         | 0.34%   |
| 2 x Nvidia     | 2         | 0.17%   |
| 2 x Intel      | 2         | 0.17%   |
| 1 x VIA        | 1         | 0.08%   |
| 1 x SiS        | 1         | 0.08%   |
| 1 x Matrox     | 1         | 0.08%   |
| 1 x ASPEED     | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 918       | 77.14%  |
| Proprietary | 221       | 18.57%  |
| Unknown     | 51        | 4.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 654       | 54%     |
| 1.01-2.0   | 159       | 13.13%  |
| 0.01-0.5   | 128       | 10.57%  |
| 3.01-4.0   | 91        | 7.51%   |
| 0.51-1.0   | 89        | 7.35%   |
| 7.01-8.0   | 42        | 3.47%   |
| 5.01-6.0   | 27        | 2.23%   |
| 8.01-16.0  | 11        | 0.91%   |
| 2.01-3.0   | 6         | 0.5%    |
| 16.01-24.0 | 4         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 181       | 14.51%  |
| AU Optronics            | 128       | 10.26%  |
| Samsung Electronics     | 122       | 9.78%   |
| BOE                     | 97        | 7.78%   |
| Chimei Innolux          | 95        | 7.62%   |
| Dell                    | 89        | 7.14%   |
| Goldstar                | 52        | 4.17%   |
| Philips                 | 51        | 4.09%   |
| Acer                    | 41        | 3.29%   |
| Hewlett-Packard         | 34        | 2.73%   |
| Lenovo                  | 32        | 2.57%   |
| AOC                     | 31        | 2.49%   |
| Ancor Communications    | 27        | 2.17%   |
| Chi Mei Optoelectronics | 23        | 1.84%   |
| BenQ                    | 21        | 1.68%   |
| Sharp                   | 15        | 1.2%    |
| PANDA                   | 15        | 1.2%    |
| LG Philips              | 12        | 0.96%   |
| Fujitsu Siemens         | 11        | 0.88%   |
| Apple                   | 10        | 0.8%    |
| Panasonic               | 9         | 0.72%   |
| LG Electronics          | 9         | 0.72%   |
| Sony                    | 8         | 0.64%   |
| ASUSTek Computer        | 8         | 0.64%   |
| Vestel Elektronik       | 7         | 0.56%   |
| MSI                     | 7         | 0.56%   |
| CSO                     | 7         | 0.56%   |
| NEC Computers           | 6         | 0.48%   |
| HannStar                | 6         | 0.48%   |
| Eizo                    | 6         | 0.48%   |
| ViewSonic               | 4         | 0.32%   |
| Unknown                 | 4         | 0.32%   |
| Toshiba                 | 4         | 0.32%   |
| InfoVision              | 4         | 0.32%   |
| Iiyama                  | 4         | 0.32%   |
| CPT                     | 4         | 0.32%   |
| Vestel                  | 3         | 0.24%   |
| Valve                   | 3         | 0.24%   |
| Gigabyte Technology     | 3         | 0.24%   |
| Belinea                 | 3         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 1.01%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.62%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 7         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 6         | 0.46%   |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                         | 6         | 0.46%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 5         | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.39%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 5         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.31%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 4         | 0.31%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 4         | 0.31%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 4         | 0.31%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.31%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 4         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.31%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 4         | 0.31%   |
| AOC G2460PG AOC2460 1920x1080 531x299mm 24.0-inch                        | 4         | 0.31%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.23%   |
| Samsung Electronics SMXL2270HD SAM072B 1920x1080 476x268mm 21.5-inch     | 3         | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 3         | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 3         | 0.23%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                       | 3         | 0.23%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.23%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 3         | 0.23%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.23%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 537       | 44.64%  |
| 1366x768 (WXGA)    | 207       | 17.21%  |
| 3840x2160 (4K)     | 61        | 5.07%   |
| 2560x1440 (QHD)    | 53        | 4.41%   |
| 1280x1024 (SXGA)   | 51        | 4.24%   |
| 1600x900 (HD+)     | 43        | 3.57%   |
| 1680x1050 (WSXGA+) | 40        | 3.33%   |
| 1920x1200 (WUXGA)  | 38        | 3.16%   |
| 1280x800 (WXGA)    | 36        | 2.99%   |
| 1440x900 (WXGA+)   | 24        | 2%      |
| Unknown            | 15        | 1.25%   |
| 2560x1600          | 13        | 1.08%   |
| 2560x1080          | 12        | 1%      |
| 3440x1440          | 8         | 0.67%   |
| 3840x1080          | 5         | 0.42%   |
| 1024x600           | 5         | 0.42%   |
| 800x1280           | 4         | 0.33%   |
| 2880x1800          | 4         | 0.33%   |
| 1360x768           | 4         | 0.33%   |
| 1024x768 (XGA)     | 4         | 0.33%   |
| 3840x2400          | 3         | 0.25%   |
| 3840x1200          | 3         | 0.25%   |
| 1600x1200          | 3         | 0.25%   |
| 1400x1050          | 3         | 0.25%   |
| 1280x720 (HD)      | 3         | 0.25%   |
| 3200x1080          | 2         | 0.17%   |
| 2288x1287          | 2         | 0.17%   |
| 2256x1504          | 2         | 0.17%   |
| 2160x1440          | 2         | 0.17%   |
| 1280x960           | 2         | 0.17%   |
| 800x480            | 1         | 0.08%   |
| 6784x2160          | 1         | 0.08%   |
| 6400x1080          | 1         | 0.08%   |
| 5120x1080          | 1         | 0.08%   |
| 4240x1440          | 1         | 0.08%   |
| 3600x1200          | 1         | 0.08%   |
| 3456x2160          | 1         | 0.08%   |
| 3200x1800 (QHD+)   | 1         | 0.08%   |
| 3072x1920          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 393       | 31.41%  |
| 24      | 97        | 7.75%   |
| 14      | 80        | 6.39%   |
| 13      | 78        | 6.24%   |
| 17      | 76        | 6.08%   |
| 23      | 71        | 5.68%   |
| 21      | 70        | 5.6%    |
| 27      | 62        | 4.96%   |
| Unknown | 54        | 4.32%   |
| 19      | 38        | 3.04%   |
| 12      | 35        | 2.8%    |
| 22      | 26        | 2.08%   |
| 16      | 22        | 1.76%   |
| 84      | 18        | 1.44%   |
| 20      | 18        | 1.44%   |
| 34      | 16        | 1.28%   |
| 18      | 16        | 1.28%   |
| 31      | 13        | 1.04%   |
| 11      | 9         | 0.72%   |
| 54      | 7         | 0.56%   |
| 25      | 6         | 0.48%   |
| 10      | 6         | 0.48%   |
| 40      | 5         | 0.4%    |
| 72      | 4         | 0.32%   |
| 65      | 4         | 0.32%   |
| 32      | 4         | 0.32%   |
| 29      | 3         | 0.24%   |
| 28      | 3         | 0.24%   |
| 7       | 3         | 0.24%   |
| 33      | 2         | 0.16%   |
| 26      | 2         | 0.16%   |
| 142     | 1         | 0.08%   |
| 75      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 42      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 30      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 550       | 44.35%  |
| 501-600        | 217       | 17.5%   |
| 401-500        | 144       | 11.61%  |
| 201-300        | 90        | 7.26%   |
| 351-400        | 83        | 6.69%   |
| Unknown        | 54        | 4.35%   |
| 601-700        | 30        | 2.42%   |
| 1501-2000      | 23        | 1.85%   |
| 701-800        | 22        | 1.77%   |
| 1001-1500      | 15        | 1.21%   |
| 801-900        | 6         | 0.48%   |
| 1-100          | 4         | 0.32%   |
| More than 2000 | 1         | 0.08%   |
| 901-1000       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 820       | 72.25%  |
| 16/10   | 167       | 14.71%  |
| 5/4     | 51        | 4.49%   |
| Unknown | 48        | 4.23%   |
| 21/9    | 20        | 1.76%   |
| 4/3     | 13        | 1.15%   |
| 3/2     | 7         | 0.62%   |
| 0.67    | 3         | 0.26%   |
| 6/5     | 2         | 0.18%   |
| 32/9    | 2         | 0.18%   |
| 1.00    | 2         | 0.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 391       | 31.63%  |
| 201-250        | 194       | 15.7%   |
| 81-90          | 125       | 10.11%  |
| 151-200        | 78        | 6.31%   |
| 301-350        | 67        | 5.42%   |
| Unknown        | 54        | 4.37%   |
| 251-300        | 47        | 3.8%    |
| 121-130        | 43        | 3.48%   |
| 141-150        | 40        | 3.24%   |
| 351-500        | 38        | 3.07%   |
| More than 1000 | 35        | 2.83%   |
| 71-80          | 34        | 2.75%   |
| 61-70          | 32        | 2.59%   |
| 111-120        | 21        | 1.7%    |
| 51-60          | 9         | 0.73%   |
| 501-1000       | 9         | 0.73%   |
| 131-140        | 7         | 0.57%   |
| 41-50          | 6         | 0.49%   |
| 1-40           | 4         | 0.32%   |
| 91-100         | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 394       | 32.56%  |
| 121-160       | 366       | 30.25%  |
| 101-120       | 292       | 24.13%  |
| 161-240       | 61        | 5.04%   |
| Unknown       | 54        | 4.46%   |
| More than 240 | 23        | 1.9%    |
| 1-50          | 20        | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 950       | 79.3%   |
| 2     | 169       | 14.11%  |
| 0     | 58        | 4.84%   |
| 3     | 20        | 1.67%   |
| 4     | 1         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 620       | 34.52%  |
| Intel                             | 563       | 31.35%  |
| Qualcomm Atheros                  | 187       | 10.41%  |
| Broadcom                          | 92        | 5.12%   |
| MediaTek                          | 40        | 2.23%   |
| TP-Link                           | 39        | 2.17%   |
| Broadcom Limited                  | 34        | 1.89%   |
| Ralink                            | 26        | 1.45%   |
| Nvidia                            | 21        | 1.17%   |
| Ralink Technology                 | 18        | 1%      |
| Marvell Technology Group          | 18        | 1%      |
| Qualcomm Atheros Communications   | 17        | 0.95%   |
| Ericsson Business Mobile Networks | 15        | 0.84%   |
| Sierra Wireless                   | 12        | 0.67%   |
| D-Link                            | 7         | 0.39%   |
| Dell                              | 6         | 0.33%   |
| Xiaomi                            | 5         | 0.28%   |
| Samsung Electronics               | 5         | 0.28%   |
| Lenovo                            | 5         | 0.28%   |
| Huawei Technologies               | 5         | 0.28%   |
| Hewlett-Packard                   | 5         | 0.28%   |
| Sundance Technology Inc / IC Plus | 4         | 0.22%   |
| Motorola PCS                      | 4         | 0.22%   |
| Microsoft                         | 4         | 0.22%   |
| DisplayLink                       | 4         | 0.22%   |
| ASIX Electronics                  | 4         | 0.22%   |
| Aquantia                          | 3         | 0.17%   |
| AMD                               | 3         | 0.17%   |
| Toshiba                           | 2         | 0.11%   |
| Qualcomm                          | 2         | 0.11%   |
| Google                            | 2         | 0.11%   |
| Davicom Semiconductor             | 2         | 0.11%   |
| D-Link System                     | 2         | 0.11%   |
| Chelsio Communications            | 2         | 0.11%   |
| ASUSTek Computer                  | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| Razer USA                         | 1         | 0.06%   |
| Raspberry Pi                      | 1         | 0.06%   |
| Quectel Wireless Solutions        | 1         | 0.06%   |
| NetXen Incorporated               | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 406       | 19.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 80        | 3.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 60        | 2.86%   |
| Intel Wireless 8265 / 8275                                             | 33        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 33        | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 32        | 1.52%   |
| Intel Wi-Fi 6 AX200                                                    | 31        | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 27        | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 25        | 1.19%   |
| Intel Wireless 7265                                                    | 24        | 1.14%   |
| Intel Wireless 7260                                                    | 24        | 1.14%   |
| Intel Wi-Fi 6 AX201                                                    | 24        | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 1.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 23        | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 21        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                        | 21        | 1%      |
| Intel Ethernet Connection (2) I219-V                                   | 20        | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 20        | 0.95%   |
| Intel Ethernet Connection I217-LM                                      | 18        | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 17        | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 17        | 0.81%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 16        | 0.76%   |
| Intel Wireless 8260                                                    | 16        | 0.76%   |
| Intel I211 Gigabit Network Connection                                  | 16        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 16        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 15        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                        | 15        | 0.71%   |
| Intel Wireless 3160                                                    | 15        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 14        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                          | 14        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 13        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 13        | 0.62%   |
| Intel WiFi Link 5100                                                   | 13        | 0.62%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 12        | 0.57%   |
| Nvidia MCP61 Ethernet                                                  | 12        | 0.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 12        | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 0.57%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 422       | 45.77%  |
| Qualcomm Atheros                      | 137       | 14.86%  |
| Realtek Semiconductor                 | 128       | 13.88%  |
| Broadcom                              | 56        | 6.07%   |
| MediaTek                              | 39        | 4.23%   |
| TP-Link                               | 33        | 3.58%   |
| Ralink                                | 26        | 2.82%   |
| Ralink Technology                     | 18        | 1.95%   |
| Qualcomm Atheros Communications       | 17        | 1.84%   |
| Sierra Wireless                       | 12        | 1.3%    |
| Broadcom Limited                      | 12        | 1.3%    |
| Microsoft                             | 4         | 0.43%   |
| D-Link                                | 4         | 0.43%   |
| Dell                                  | 3         | 0.33%   |
| Qualcomm                              | 2         | 0.22%   |
| ASUSTek Computer                      | 2         | 0.22%   |
| Quectel Wireless Solutions            | 1         | 0.11%   |
| NetGear                               | 1         | 0.11%   |
| Micro Star International              | 1         | 0.11%   |
| Hewlett-Packard                       | 1         | 0.11%   |
| Gemtek                                | 1         | 0.11%   |
| FIBOCOM                               | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 33        | 3.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 3.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 32        | 3.45%   |
| Intel Wi-Fi 6 AX200                                            | 31        | 3.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 27        | 2.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 2.7%    |
| Intel Wireless 7265                                            | 24        | 2.59%   |
| Intel Wireless 7260                                            | 24        | 2.59%   |
| Intel Wi-Fi 6 AX201                                            | 24        | 2.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 21        | 2.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 20        | 2.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 17        | 1.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 1.83%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 16        | 1.73%   |
| Intel Wireless 8260                                            | 16        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 1.62%   |
| Qualcomm Atheros AR9271 802.11n                                | 15        | 1.62%   |
| Intel Wireless 3160                                            | 15        | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 1.4%    |
| Intel WiFi Link 5100                                           | 13        | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 12        | 1.29%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 12        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 11        | 1.19%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 10        | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 10        | 1.08%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 0.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 9         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.97%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 0.86%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 8         | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 562       | 50.54%  |
| Intel                             | 314       | 28.24%  |
| Qualcomm Atheros                  | 68        | 6.12%   |
| Broadcom                          | 44        | 3.96%   |
| Broadcom Limited                  | 22        | 1.98%   |
| Nvidia                            | 21        | 1.89%   |
| Marvell Technology Group          | 18        | 1.62%   |
| TP-Link                           | 6         | 0.54%   |
| Xiaomi                            | 5         | 0.45%   |
| Samsung Electronics               | 5         | 0.45%   |
| Sundance Technology Inc / IC Plus | 4         | 0.36%   |
| Lenovo                            | 4         | 0.36%   |
| Huawei Technologies               | 4         | 0.36%   |
| DisplayLink                       | 4         | 0.36%   |
| ASIX Electronics                  | 4         | 0.36%   |
| Motorola PCS                      | 3         | 0.27%   |
| D-Link                            | 3         | 0.27%   |
| Aquantia                          | 3         | 0.27%   |
| Google                            | 2         | 0.18%   |
| Davicom Semiconductor             | 2         | 0.18%   |
| D-Link System                     | 2         | 0.18%   |
| Chelsio Communications            | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| Raspberry Pi                      | 1         | 0.09%   |
| NetXen Incorporated               | 1         | 0.09%   |
| MediaTek                          | 1         | 0.09%   |
| JMicron Technology                | 1         | 0.09%   |
| ICS Advent                        | 1         | 0.09%   |
| Cypress Semiconductor             | 1         | 0.09%   |
| Attansic Technology               | 1         | 0.09%   |
| Apple                             | 1         | 0.09%   |
| 3Com                              | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 406       | 35.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 80        | 7.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 60        | 5.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 27        | 2.37%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23        | 2.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 23        | 2.02%   |
| Intel Ethernet Connection (2) I219-V                                   | 20        | 1.76%   |
| Intel Ethernet Connection I217-LM                                      | 18        | 1.58%   |
| Intel I211 Gigabit Network Connection                                  | 16        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 1.14%   |
| Nvidia MCP61 Ethernet                                                  | 12        | 1.05%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 11        | 0.97%   |
| Intel Ethernet Controller I225-V                                       | 11        | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.97%   |
| Intel Ethernet Connection I217-V                                       | 10        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                                   | 10        | 0.88%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 0.88%   |
| Intel Ethernet Connection I219-LM                                      | 9         | 0.79%   |
| Intel Ethernet Connection I218-LM                                      | 9         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                                  | 9         | 0.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 9         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.7%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 0.7%    |
| Realtek Killer E2600 GbE Controller                                    | 7         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 7         | 0.62%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7         | 0.62%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 6         | 0.53%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 6         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5         | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 5         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.44%   |
| Intel Ethernet Connection (16) I219-V                                  | 5         | 0.44%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 5         | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 5         | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 5         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1041      | 53.8%   |
| WiFi     | 860       | 44.44%  |
| Modem    | 33        | 1.71%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 680       | 55.78%  |
| Ethernet | 539       | 44.22%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 679       | 58.13%  |
| 1     | 451       | 38.61%  |
| 3     | 21        | 1.8%    |
| 0     | 10        | 0.86%   |
| 4     | 4         | 0.34%   |
| 7     | 2         | 0.17%   |
| 5     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1129      | 95.52%  |
| Yes  | 53        | 4.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 302       | 42.42%  |
| Realtek Semiconductor           | 67        | 9.41%   |
| Qualcomm Atheros Communications | 46        | 6.46%   |
| Broadcom                        | 42        | 5.9%    |
| IMC Networks                    | 41        | 5.76%   |
| Cambridge Silicon Radio         | 38        | 5.34%   |
| Foxconn / Hon Hai               | 31        | 4.35%   |
| Lite-On Technology              | 29        | 4.07%   |
| Toshiba                         | 17        | 2.39%   |
| Hewlett-Packard                 | 16        | 2.25%   |
| Dell                            | 15        | 2.11%   |
| Apple                           | 14        | 1.97%   |
| Ralink                          | 12        | 1.69%   |
| ASUSTek Computer                | 11        | 1.54%   |
| MediaTek                        | 8         | 1.12%   |
| Integrated System Solution      | 7         | 0.98%   |
| Foxconn International           | 6         | 0.84%   |
| TP-Link                         | 2         | 0.28%   |
| Realtek                         | 2         | 0.28%   |
| Ralink Technology               | 2         | 0.28%   |
| USI                             | 1         | 0.14%   |
| Logitech                        | 1         | 0.14%   |
| Belkin Components               | 1         | 0.14%   |
| Unknown                         | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 66        | 9.27%   |
| Intel AX201 Bluetooth                                 | 64        | 8.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 49        | 6.88%   |
| Realtek Bluetooth Radio                               | 48        | 6.74%   |
| Intel Bluetooth Device                                | 47        | 6.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 38        | 5.34%   |
| Intel AX200 Bluetooth                                 | 30        | 4.21%   |
| Qualcomm Atheros  Bluetooth Device                    | 26        | 3.65%   |
| IMC Networks Bluetooth Radio                          | 18        | 2.53%   |
| IMC Networks Wireless_Device                          | 13        | 1.83%   |
| Ralink RT3290 Bluetooth                               | 12        | 1.69%   |
| Lite-On Bluetooth Device                              | 10        | 1.4%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 9         | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 9         | 1.26%   |
| Intel AX211 Bluetooth                                 | 9         | 1.26%   |
| Intel AX210 Bluetooth                                 | 9         | 1.26%   |
| IMC Networks Bluetooth Device                         | 9         | 1.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 9         | 1.26%   |
| Realtek 802.11ac WLAN Adapter                         | 8         | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 8         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                      | 8         | 1.12%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 8         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                     | 8         | 1.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 8         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                    | 8         | 1.12%   |
| Toshiba Integrated Bluetooth HCI                      | 7         | 0.98%   |
| MediaTek Wireless_Device                              | 7         | 0.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 7         | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 7         | 0.98%   |
| Broadcom BCM2045B (BDC-2.1)                           | 7         | 0.98%   |
| Intel Wireless-AC 3168 Bluetooth                      | 6         | 0.84%   |
| Foxconn International BCM43142A0 Bluetooth module     | 6         | 0.84%   |
| Apple Bluetooth Host Controller                       | 6         | 0.84%   |
| Dell DW375 Bluetooth Module                           | 5         | 0.7%    |
| Realtek RTL8723B Bluetooth                            | 4         | 0.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 4         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                      | 4         | 0.56%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4         | 0.56%   |
| Dell BCM20702A0 Bluetooth Module                      | 4         | 0.56%   |
| ASUS ASUS USB-BT500                                   | 4         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 853       | 52.78%  |
| AMD                                          | 337       | 20.85%  |
| Nvidia                                       | 279       | 17.26%  |
| C-Media Electronics                          | 26        | 1.61%   |
| Creative Labs                                | 13        | 0.8%    |
| GN Netcom                                    | 8         | 0.5%    |
| Texas Instruments                            | 7         | 0.43%   |
| Razer USA                                    | 7         | 0.43%   |
| Lenovo                                       | 7         | 0.43%   |
| Plantronics                                  | 6         | 0.37%   |
| Logitech                                     | 6         | 0.37%   |
| Creative Technology                          | 6         | 0.37%   |
| ASUSTek Computer                             | 5         | 0.31%   |
| Trust                                        | 4         | 0.25%   |
| JMTek                                        | 4         | 0.25%   |
| VIA Technologies                             | 3         | 0.19%   |
| Tenx Technology                              | 3         | 0.19%   |
| Realtek Semiconductor                        | 3         | 0.19%   |
| Generalplus Technology                       | 3         | 0.19%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.12%   |
| Sony                                         | 2         | 0.12%   |
| Micro Star International                     | 2         | 0.12%   |
| Hewlett-Packard                              | 2         | 0.12%   |
| Dell                                         | 2         | 0.12%   |
| Corsair                                      | 2         | 0.12%   |
| BEHRINGER International                      | 2         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| ZOOM                                         | 1         | 0.06%   |
| SteelSeries ApS                              | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.06%   |
| Samson Technologies                          | 1         | 0.06%   |
| Roland                                       | 1         | 0.06%   |
| Ploytec                                      | 1         | 0.06%   |
| OPPO Electronics                             | 1         | 0.06%   |
| No brand                                     | 1         | 0.06%   |
| Native Instruments                           | 1         | 0.06%   |
| NAD Electronics                              | 1         | 0.06%   |
| M-Audio                                      | 1         | 0.06%   |
| Kingston Technology                          | 1         | 0.06%   |
| GYROCOM C&C                                  | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 123       | 6.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 93        | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 91        | 4.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 64        | 3.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 62        | 3.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 62        | 3.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 61        | 3.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 2.95%   |
| Intel Cannon Lake PCH cAVS                                                 | 40        | 2.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 40        | 2.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35        | 1.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 33        | 1.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 29        | 1.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 29        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 29        | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 28        | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 28        | 1.45%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 28        | 1.45%   |
| AMD FCH Azalia Controller                                                  | 26        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 25        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 23        | 1.19%   |
| Intel 200 Series PCH HD Audio                                              | 23        | 1.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 22        | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 20        | 1.04%   |
| Intel CM238 HD Audio Controller                                            | 18        | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 18        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 16        | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 16        | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 15        | 0.78%   |
| Nvidia Audio device                                                        | 14        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 159       | 20.76%  |
| SK hynix                                | 127       | 16.58%  |
| Kingston                                | 119       | 15.54%  |
| Micron Technology                       | 75        | 9.79%   |
| Unknown                                 | 69        | 9.01%   |
| Corsair                                 | 42        | 5.48%   |
| A-DATA Technology                       | 38        | 4.96%   |
| Ramaxel Technology                      | 23        | 3%      |
| Team                                    | 16        | 2.09%   |
| Nanya Technology                        | 14        | 1.83%   |
| Transcend                               | 12        | 1.57%   |
| Crucial                                 | 12        | 1.57%   |
| Elpida                                  | 11        | 1.44%   |
| G.Skill                                 | 10        | 1.31%   |
| Apacer                                  | 7         | 0.91%   |
| Unknown                                 | 7         | 0.91%   |
| Silicon Power                           | 3         | 0.39%   |
| GOODRAM                                 | 3         | 0.39%   |
| Unknown (ABCD)                          | 2         | 0.26%   |
| Silicon Power Computer & Communications | 2         | 0.26%   |
| pqi                                     | 2         | 0.26%   |
| Atermiter                               | 2         | 0.26%   |
| ASint Technology                        | 2         | 0.26%   |
| Unifosa                                 | 1         | 0.13%   |
| Thermaltake                             | 1         | 0.13%   |
| Qimonda                                 | 1         | 0.13%   |
| Patriot                                 | 1         | 0.13%   |
| Neo Forza                               | 1         | 0.13%   |
| HBS                                     | 1         | 0.13%   |
| fef5                                    | 1         | 0.13%   |
| CSX                                     | 1         | 0.13%   |
| A Force                                 | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 10        | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 8         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s | 7         | 0.84%   |
| Unknown                                                  | 7         | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s    | 6         | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 6         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 6         | 0.72%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s    | 6         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 5         | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 5         | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s    | 5         | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s    | 5         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s     | 5         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s     | 5         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 4         | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 4         | 0.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 0.48%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s   | 4         | 0.48%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 4         | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s | 4         | 0.48%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s    | 4         | 0.48%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s  | 4         | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s     | 4         | 0.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s     | 4         | 0.48%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 4         | 0.48%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s               | 4         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 3         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 3         | 0.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 3         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 3         | 0.36%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s   | 3         | 0.36%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 3         | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 3         | 0.36%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 3         | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 3         | 0.36%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s | 3         | 0.36%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 3         | 0.36%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s    | 3         | 0.36%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s    | 3         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 274       | 43.22%  |
| DDR3    | 237       | 37.38%  |
| DDR2    | 30        | 4.73%   |
| SDRAM   | 21        | 3.31%   |
| Unknown | 20        | 3.15%   |
| DDR5    | 17        | 2.68%   |
| LPDDR4  | 9         | 1.42%   |
| LPDDR5  | 8         | 1.26%   |
| DDR     | 7         | 1.1%    |
| LPDDR3  | 6         | 0.95%   |
| DRAM    | 5         | 0.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 378       | 60.58%  |
| DIMM         | 218       | 34.94%  |
| Row Of Chips | 19        | 3.04%   |
| Chip         | 4         | 0.64%   |
| RIMM         | 2         | 0.32%   |
| FB-DIMM      | 2         | 0.32%   |
| Unknown      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 235       | 34.16%  |
| 4096    | 196       | 28.49%  |
| 16384   | 105       | 15.26%  |
| 2048    | 89        | 12.94%  |
| 32768   | 30        | 4.36%   |
| 1024    | 27        | 3.92%   |
| 512     | 3         | 0.44%   |
| 49152   | 1         | 0.15%   |
| 256     | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 150       | 21.65%  |
| 3200    | 112       | 16.16%  |
| 2667    | 86        | 12.41%  |
| 1333    | 52        | 7.5%    |
| 2400    | 35        | 5.05%   |
| 1334    | 31        | 4.47%   |
| 2133    | 21        | 3.03%   |
| 3600    | 20        | 2.89%   |
| 667     | 19        | 2.74%   |
| 800     | 17        | 2.45%   |
| Unknown | 17        | 2.45%   |
| 4800    | 10        | 1.44%   |
| 1867    | 10        | 1.44%   |
| 1067    | 8         | 1.15%   |
| 6400    | 7         | 1.01%   |
| 3266    | 7         | 1.01%   |
| 1066    | 7         | 1.01%   |
| 5600    | 6         | 0.87%   |
| 4199    | 5         | 0.72%   |
| 3800    | 4         | 0.58%   |
| 3733    | 4         | 0.58%   |
| 3466    | 4         | 0.58%   |
| 3000    | 4         | 0.58%   |
| 2666    | 4         | 0.58%   |
| 2048    | 4         | 0.58%   |
| 1866    | 4         | 0.58%   |
| 1800    | 4         | 0.58%   |
| 333     | 4         | 0.58%   |
| 2933    | 3         | 0.43%   |
| 400     | 3         | 0.43%   |
| 4266    | 2         | 0.29%   |
| 3400    | 2         | 0.29%   |
| 3333    | 2         | 0.29%   |
| 2800    | 2         | 0.29%   |
| 2200    | 2         | 0.29%   |
| 975     | 2         | 0.29%   |
| 57535   | 1         | 0.14%   |
| 50410   | 1         | 0.14%   |
| 7500    | 1         | 0.14%   |
| 6000    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 25.93%  |
| Samsung Electronics | 4         | 14.81%  |
| Brother Industries  | 4         | 14.81%  |
| Xerox               | 3         | 11.11%  |
| Seiko Epson         | 2         | 7.41%   |
| Canon               | 2         | 7.41%   |
| STMicroelectronics  | 1         | 3.7%    |
| Prolific Technology | 1         | 3.7%    |
| Kyocera             | 1         | 3.7%    |
| Citizen             | 1         | 3.7%    |
| ATEN International  | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 2         | 7.41%   |
| Xerox Phaser 3140 and 3155                                | 1         | 3.7%    |
| Xerox Phaser 3020                                         | 1         | 3.7%    |
| Xerox Phaser 3010                                         | 1         | 3.7%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.7%    |
| Seiko Epson ET-2820 Series                                | 1         | 3.7%    |
| Seiko Epson ET-2710 Series                                | 1         | 3.7%    |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 3.7%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.7%    |
| Samsung M332x 382x 402x Series                            | 1         | 3.7%    |
| Samsung M267x 287x Series                                 | 1         | 3.7%    |
| Prolific PL2305 Parallel Port                             | 1         | 3.7%    |
| Kyocera ECOSYS P2040dn                                    | 1         | 3.7%    |
| HP LaserJet Professional P1566                            | 1         | 3.7%    |
| HP LaserJet P1102                                         | 1         | 3.7%    |
| HP LaserJet 4350                                          | 1         | 3.7%    |
| HP LaserJet 1018                                          | 1         | 3.7%    |
| HP DeskJet 4530 series                                    | 1         | 3.7%    |
| Citizen Barcode Printer                                   | 1         | 3.7%    |
| Canon PIXMA MP240                                         | 1         | 3.7%    |
| Canon MF3200 series                                       | 1         | 3.7%    |
| Brother Printer                                           | 1         | 3.7%    |
| Brother MFC-B7715DW series                                | 1         | 3.7%    |
| Brother DCP-T300                                          | 1         | 3.7%    |
| Brother DCP-7055 scanner/printer                          | 1         | 3.7%    |
| ATEN International UC-1284B Printer Port                  | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Mustek Systems  | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22        | 1         | 25%     |
| HP Scanjet G2710                   | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan LiDE 110            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 168       | 23.76%  |
| IMC Networks                           | 78        | 11.03%  |
| Microdia                               | 60        | 8.49%   |
| Realtek Semiconductor                  | 52        | 7.36%   |
| Bison Electronics                      | 48        | 6.79%   |
| Quanta                                 | 46        | 6.51%   |
| Sunplus Innovation Technology          | 43        | 6.08%   |
| Syntek                                 | 20        | 2.83%   |
| Suyin                                  | 19        | 2.69%   |
| Logitech                               | 18        | 2.55%   |
| Acer                                   | 18        | 2.55%   |
| Lite-On Technology                     | 17        | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) | 16        | 2.26%   |
| Luxvisions Innotech Limited            | 15        | 2.12%   |
| Z-Star Microelectronics                | 10        | 1.41%   |
| Apple                                  | 10        | 1.41%   |
| Alcor Micro                            | 9         | 1.27%   |
| Microsoft                              | 7         | 0.99%   |
| Silicon Motion                         | 6         | 0.85%   |
| Sonix Technology                       | 5         | 0.71%   |
| Lenovo                                 | 5         | 0.71%   |
| Samsung Electronics                    | 3         | 0.42%   |
| Ricoh                                  | 3         | 0.42%   |
| Creative Technology                    | 3         | 0.42%   |
| Unknown                                | 2         | 0.28%   |
| Primax Electronics                     | 2         | 0.28%   |
| Importek                               | 2         | 0.28%   |
| Hewlett-Packard                        | 2         | 0.28%   |
| Generalplus Technology                 | 2         | 0.28%   |
| Aveo Technology                        | 2         | 0.28%   |
| Alpha Imaging Technology               | 2         | 0.28%   |
| ALi                                    | 2         | 0.28%   |
| Xiongmai                               | 1         | 0.14%   |
| Sunplus Technology                     | 1         | 0.14%   |
| Razer USA                              | 1         | 0.14%   |
| Pixart Imaging                         | 1         | 0.14%   |
| OmniVision Technologies                | 1         | 0.14%   |
| Novatek Microelectronics               | 1         | 0.14%   |
| MacroSilicon                           | 1         | 0.14%   |
| Google                                 | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 39        | 5.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 24        | 3.39%   |
| IMC Networks Integrated Camera                      | 24        | 3.39%   |
| Microdia Integrated_Webcam_HD                       | 17        | 2.4%    |
| Chicony HD WebCam                                   | 16        | 2.26%   |
| Bison Integrated Camera                             | 16        | 2.26%   |
| Realtek Integrated_Webcam_HD                        | 14        | 1.98%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 1.84%   |
| Syntek Integrated Camera                            | 12        | 1.7%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 1.7%    |
| Quanta HP HD Camera                                 | 11        | 1.56%   |
| Realtek Lenovo EasyCamera                           | 9         | 1.27%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 1.27%   |
| Bison SunplusIT Integrated Camera                   | 8         | 1.13%   |
| Bison HD Webcam                                     | 8         | 1.13%   |
| Quanta HD User Facing                               | 7         | 0.99%   |
| Chicony USB 2.0 Camera                              | 7         | 0.99%   |
| Microdia Integrated Webcam                          | 6         | 0.85%   |
| Microdia Camera                                     | 6         | 0.85%   |
| Z-Star A4 TECH HD PC Camera                         | 5         | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 5         | 0.71%   |
| Quanta VGA WebCam                                   | 5         | 0.71%   |
| Quanta ACER HD User Facing                          | 5         | 0.71%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.71%   |
| Logitech Webcam C270                                | 5         | 0.71%   |
| Lite-On Integrated Camera                           | 5         | 0.71%   |
| Lite-On HP HD Webcam                                | 5         | 0.71%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 0.71%   |
| Chicony Lenovo EasyCamera                           | 5         | 0.71%   |
| Chicony HP HD Camera                                | 5         | 0.71%   |
| Chicony HD WebCam (Asus N-series)                   | 5         | 0.71%   |
| Bison Lenovo EasyCamera                             | 5         | 0.71%   |
| Sunplus Laptop Integrated Webcam HD                 | 4         | 0.57%   |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.57%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.57%   |
| Quanta HD Webcam                                    | 4         | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.57%   |
| IMC Networks UVC VGA Webcam                         | 4         | 0.57%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.57%   |
| Chicony HP Webcam [2 MP Macro]                      | 4         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 47        | 37.6%   |
| Synaptics                          | 38        | 30.4%   |
| AuthenTec                          | 15        | 12%     |
| Shenzhen Goodix Technology         | 8         | 6.4%    |
| Upek                               | 6         | 4.8%    |
| Elan Microelectronics              | 5         | 4%      |
| LighTuning Technology              | 4         | 3.2%    |
| STMicroelectronics                 | 1         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.8%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 12.8%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 9.6%    |
| Validity Sensors Synaptics WBDI                                            | 8         | 6.4%    |
| AuthenTec AES2810                                                          | 8         | 6.4%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.8%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 4.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.2%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 3.2%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 3.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.4%    |
| Elan ELAN:ARM-M4                                                           | 3         | 2.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.6%    |
| Validity Sensors VFS491                                                    | 2         | 1.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.6%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.6%    |
| Synaptics WBDI                                                             | 2         | 1.6%    |
| Synaptics  WBDI                                                            | 2         | 1.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 1.6%    |
| LighTuning Fingerprint Reader                                              | 2         | 1.6%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.6%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.6%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.8%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.8%    |
| Synaptics TouchPad                                                         | 1         | 0.8%    |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.8%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.8%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.8%    |
| AuthenTec AES1600                                                          | 1         | 0.8%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 31        | 34.83%  |
| Alcor Micro           | 30        | 33.71%  |
| Upek                  | 8         | 8.99%   |
| O2 Micro              | 6         | 6.74%   |
| Advanced Card Systems | 5         | 5.62%   |
| Lenovo                | 4         | 4.49%   |
| SCM Microsystems      | 2         | 2.25%   |
| OmniKey               | 2         | 2.25%   |
| Clay Logic            | 1         | 1.12%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 14.44%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 8.89%   |
| Broadcom 5880                                                                | 8         | 8.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 6.67%   |
| Broadcom 58200                                                               | 6         | 6.67%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.44%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.22%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 2.22%   |
| Advanced Card Systems ACR39U                                                 | 2         | 2.22%   |
| Advanced Card Systems ACR122U                                                | 2         | 2.22%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.11%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.11%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 809       | 66.86%  |
| 1     | 321       | 26.53%  |
| 2     | 71        | 5.87%   |
| 3     | 5         | 0.41%   |
| 4     | 2         | 0.17%   |
| 7     | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 125       | 26.94%  |
| Graphics card            | 108       | 23.28%  |
| Chipcard                 | 73        | 15.73%  |
| Net/wireless             | 46        | 9.91%   |
| Multimedia controller    | 24        | 5.17%   |
| Bluetooth                | 19        | 4.09%   |
| Communication controller | 12        | 2.59%   |
| Camera                   | 12        | 2.59%   |
| Unassigned class         | 10        | 2.16%   |
| Storage                  | 10        | 2.16%   |
| Net/ethernet             | 6         | 1.29%   |
| Card reader              | 6         | 1.29%   |
| Sound                    | 4         | 0.86%   |
| Firewire controller      | 3         | 0.65%   |
| Network                  | 2         | 0.43%   |
| Modem                    | 2         | 0.43%   |
| Storage/ata              | 1         | 0.22%   |
| Flash memory             | 1         | 0.22%   |

