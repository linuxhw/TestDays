Xubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_20.04/Notebook/README.md).

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

Total: 2997

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| INP           | i1000BTS                    | Desktop     | [3148738295](https://linux-hardware.org/?probe=3148738295) | Feb 02, 2024 |
| HP            | Pavilion g6                 | Notebook    | [7f9863aaa2](https://linux-hardware.org/?probe=7f9863aaa2) | Jan 31, 2024 |
| HP            | 859C                        | Desktop     | [866ac7f0ed](https://linux-hardware.org/?probe=866ac7f0ed) | Jan 30, 2024 |
| Dell          | Latitude 5510               | Notebook    | [4abbee3451](https://linux-hardware.org/?probe=4abbee3451) | Jan 30, 2024 |
| Packard Be... | IXTREME M5800               | Desktop     | [f31eaf65b4](https://linux-hardware.org/?probe=f31eaf65b4) | Jan 29, 2024 |
| Dell          | Latitude 5511               | Notebook    | [40fad497db](https://linux-hardware.org/?probe=40fad497db) | Jan 29, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [72dee51fa2](https://linux-hardware.org/?probe=72dee51fa2) | Jan 29, 2024 |
| Packard Be... | IXTREME M5800               | Desktop     | [8d8f99feb9](https://linux-hardware.org/?probe=8d8f99feb9) | Jan 28, 2024 |
| Lenovo        | V560                        | Notebook    | [a0dbd66d53](https://linux-hardware.org/?probe=a0dbd66d53) | Jan 28, 2024 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [0948177334](https://linux-hardware.org/?probe=0948177334) | Jan 26, 2024 |
| Gigabyte      | C1037UN                     | Desktop     | [7d3a3e3ca9](https://linux-hardware.org/?probe=7d3a3e3ca9) | Jan 26, 2024 |
| Gigabyte      | C1037UN                     | Desktop     | [344699bbb2](https://linux-hardware.org/?probe=344699bbb2) | Jan 23, 2024 |
| Lenovo        | 1037 NO DPK                 | Server      | [da53a6a2c0](https://linux-hardware.org/?probe=da53a6a2c0) | Jan 20, 2024 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [22c44fb878](https://linux-hardware.org/?probe=22c44fb878) | Jan 19, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [c7872b9640](https://linux-hardware.org/?probe=c7872b9640) | Jan 18, 2024 |
| ASUSTek       | PN40                        | Mini pc     | [f7cb91c837](https://linux-hardware.org/?probe=f7cb91c837) | Jan 17, 2024 |
| ASRock        | N68-S3 FX                   | Desktop     | [ce413f7140](https://linux-hardware.org/?probe=ce413f7140) | Jan 09, 2024 |
| Dell          | Precision M6800             | Notebook    | [5049c54004](https://linux-hardware.org/?probe=5049c54004) | Jan 04, 2024 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6bf30b2ec5](https://linux-hardware.org/?probe=6bf30b2ec5) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [14d453985d](https://linux-hardware.org/?probe=14d453985d) | Dec 25, 2023 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [6b0274e802](https://linux-hardware.org/?probe=6b0274e802) | Dec 20, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [c7aaf87bcd](https://linux-hardware.org/?probe=c7aaf87bcd) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK AH531/GFO          | Notebook    | [dfc6e4c96b](https://linux-hardware.org/?probe=dfc6e4c96b) | Dec 05, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [7d88a4ceef](https://linux-hardware.org/?probe=7d88a4ceef) | Dec 01, 2023 |
| Sony          | VGN-NS12M_W                 | Notebook    | [c1400d8699](https://linux-hardware.org/?probe=c1400d8699) | Nov 27, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [7130842b5a](https://linux-hardware.org/?probe=7130842b5a) | Nov 26, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a59b920838](https://linux-hardware.org/?probe=a59b920838) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [17c2f68bc7](https://linux-hardware.org/?probe=17c2f68bc7) | Nov 19, 2023 |
| Acer          | EG43LMK                     | Desktop     | [bc1ab38f8f](https://linux-hardware.org/?probe=bc1ab38f8f) | Nov 18, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [6560a26a12](https://linux-hardware.org/?probe=6560a26a12) | Nov 15, 2023 |
| Lenovo        | ThinkPad E470 20H1006NHV    | Notebook    | [a43db58ab7](https://linux-hardware.org/?probe=a43db58ab7) | Nov 10, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [941b37816d](https://linux-hardware.org/?probe=941b37816d) | Nov 10, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [4caad7b0d1](https://linux-hardware.org/?probe=4caad7b0d1) | Nov 07, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [1d0638865e](https://linux-hardware.org/?probe=1d0638865e) | Nov 07, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [80fb26e63a](https://linux-hardware.org/?probe=80fb26e63a) | Nov 03, 2023 |
| HP            | Presario CQ57               | Notebook    | [4874030c75](https://linux-hardware.org/?probe=4874030c75) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [a2a8295797](https://linux-hardware.org/?probe=a2a8295797) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [0d49a75fe1](https://linux-hardware.org/?probe=0d49a75fe1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [cbe947aefc](https://linux-hardware.org/?probe=cbe947aefc) | Nov 01, 2023 |
| ASUSTek       | K53E                        | Notebook    | [8b7c83e9d7](https://linux-hardware.org/?probe=8b7c83e9d7) | Oct 31, 2023 |
| HP            | Presario CQ57               | Notebook    | [a3f31b427e](https://linux-hardware.org/?probe=a3f31b427e) | Oct 26, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | Notebook    | [7be90734f6](https://linux-hardware.org/?probe=7be90734f6) | Oct 19, 2023 |
| Intel         | DB75EN                      | Desktop     | [3d5c90093d](https://linux-hardware.org/?probe=3d5c90093d) | Oct 13, 2023 |
| Intel         | DB75EN                      | Desktop     | [30be24215f](https://linux-hardware.org/?probe=30be24215f) | Oct 13, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [99587baa3d](https://linux-hardware.org/?probe=99587baa3d) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [39fd38bc98](https://linux-hardware.org/?probe=39fd38bc98) | Sep 28, 2023 |
| ASUSTek       | N550JV                      | Notebook    | [ac27d821ae](https://linux-hardware.org/?probe=ac27d821ae) | Sep 27, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [e4b8175a36](https://linux-hardware.org/?probe=e4b8175a36) | Sep 21, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [d8f04cd109](https://linux-hardware.org/?probe=d8f04cd109) | Sep 19, 2023 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [c043df4efb](https://linux-hardware.org/?probe=c043df4efb) | Sep 09, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [841d189992](https://linux-hardware.org/?probe=841d189992) | Sep 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [d8a6683747](https://linux-hardware.org/?probe=d8a6683747) | Aug 21, 2023 |
| Supermicro    | H12DSG-O-CPUA               | Server      | [b4efbfe41e](https://linux-hardware.org/?probe=b4efbfe41e) | Aug 16, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [3ab135e657](https://linux-hardware.org/?probe=3ab135e657) | Aug 11, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [5796ca55ef](https://linux-hardware.org/?probe=5796ca55ef) | Aug 06, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| Unknown       | Unknown                     | Soc         | [b89f7f59c6](https://linux-hardware.org/?probe=b89f7f59c6) | Aug 01, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [14b58ac305](https://linux-hardware.org/?probe=14b58ac305) | Jul 27, 2023 |
| HP            | 158A                        | Desktop     | [a2a4176353](https://linux-hardware.org/?probe=a2a4176353) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | Notebook    | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [5bf3142c39](https://linux-hardware.org/?probe=5bf3142c39) | Jul 21, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [014e4a907f](https://linux-hardware.org/?probe=014e4a907f) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [39742015a1](https://linux-hardware.org/?probe=39742015a1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [e69885810c](https://linux-hardware.org/?probe=e69885810c) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02958438e7](https://linux-hardware.org/?probe=02958438e7) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [28850b9e94](https://linux-hardware.org/?probe=28850b9e94) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [35c4f96184](https://linux-hardware.org/?probe=35c4f96184) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [3b0be53d2b](https://linux-hardware.org/?probe=3b0be53d2b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f35f948278](https://linux-hardware.org/?probe=f35f948278) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [cb12281aa1](https://linux-hardware.org/?probe=cb12281aa1) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [3bfca8e034](https://linux-hardware.org/?probe=3bfca8e034) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [667a30309b](https://linux-hardware.org/?probe=667a30309b) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [08cca00ba4](https://linux-hardware.org/?probe=08cca00ba4) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [646ef2c43e](https://linux-hardware.org/?probe=646ef2c43e) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d1f453b1cf](https://linux-hardware.org/?probe=d1f453b1cf) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [0525e36038](https://linux-hardware.org/?probe=0525e36038) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [56571f9682](https://linux-hardware.org/?probe=56571f9682) | Jul 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [b4516f6d51](https://linux-hardware.org/?probe=b4516f6d51) | Jul 19, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [cc05c0d021](https://linux-hardware.org/?probe=cc05c0d021) | Jul 09, 2023 |
| Olidata       | Stainer 8050                | Notebook    | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [4fbf0f4e5d](https://linux-hardware.org/?probe=4fbf0f4e5d) | Jul 04, 2023 |
| Chuwi         | CoreBox                     | Mini pc     | [7a2a217b46](https://linux-hardware.org/?probe=7a2a217b46) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Alienware     | 18                          | Notebook    | [047bc74541](https://linux-hardware.org/?probe=047bc74541) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| HP            | 18E7                        | Desktop     | [3b872d2a88](https://linux-hardware.org/?probe=3b872d2a88) | Jun 20, 2023 |
| TUXEDO        | P65xRP                      | Notebook    | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Standard      | Unknown                     | Desktop     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Dell          | Latitude E5270              | Notebook    | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| Unknown       | Unknown                     | Other       | [00ad49fe2f](https://linux-hardware.org/?probe=00ad49fe2f) | Jun 12, 2023 |
| TYAN Compu... | S7010                       | Server      | [a8b96e89f2](https://linux-hardware.org/?probe=a8b96e89f2) | Jun 10, 2023 |
| Lenovo        | V560                        | Notebook    | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| Acer          | Aspire E5-772G              | Notebook    | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | Notebook    | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [3191d9fca4](https://linux-hardware.org/?probe=3191d9fca4) | May 11, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7ac436d763](https://linux-hardware.org/?probe=7ac436d763) | May 08, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f5f0edbac8](https://linux-hardware.org/?probe=f5f0edbac8) | May 05, 2023 |
| Dell          | Latitude E7270              | Notebook    | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| HP            | 158A                        | Desktop     | [fb7aef7883](https://linux-hardware.org/?probe=fb7aef7883) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| HP            | 158A                        | Desktop     | [c3189bccb1](https://linux-hardware.org/?probe=c3189bccb1) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [704778a577](https://linux-hardware.org/?probe=704778a577) | Apr 19, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [9539ccfd4d](https://linux-hardware.org/?probe=9539ccfd4d) | Apr 18, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [4cb39d1136](https://linux-hardware.org/?probe=4cb39d1136) | Apr 15, 2023 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [ae144ff4c8](https://linux-hardware.org/?probe=ae144ff4c8) | Apr 12, 2023 |
| Dell          | 060K5C A04                  | Server      | [962b265260](https://linux-hardware.org/?probe=962b265260) | Apr 11, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [7f718ab68f](https://linux-hardware.org/?probe=7f718ab68f) | Apr 10, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [9f0d854259](https://linux-hardware.org/?probe=9f0d854259) | Apr 03, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [1b8983e24d](https://linux-hardware.org/?probe=1b8983e24d) | Apr 03, 2023 |
| Nvidia        | Tegra                       | Soc         | [d57318f254](https://linux-hardware.org/?probe=d57318f254) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [25c3fdc9f7](https://linux-hardware.org/?probe=25c3fdc9f7) | Apr 02, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8b4f79808a](https://linux-hardware.org/?probe=8b4f79808a) | Apr 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [deedee079c](https://linux-hardware.org/?probe=deedee079c) | Mar 31, 2023 |
| Gateway       | LT27                        | Notebook    | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| HP            | 158A                        | Desktop     | [9ed0f8f65f](https://linux-hardware.org/?probe=9ed0f8f65f) | Mar 25, 2023 |
| Biostar       | TZ77A                       | Desktop     | [9484c73494](https://linux-hardware.org/?probe=9484c73494) | Mar 21, 2023 |
| HP            | 158A                        | Desktop     | [033f7a5abd](https://linux-hardware.org/?probe=033f7a5abd) | Mar 21, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [62d90f07ba](https://linux-hardware.org/?probe=62d90f07ba) | Mar 20, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [653b1820fe](https://linux-hardware.org/?probe=653b1820fe) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [4efa1b8600](https://linux-hardware.org/?probe=4efa1b8600) | Mar 16, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [406ea57f9c](https://linux-hardware.org/?probe=406ea57f9c) | Mar 13, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [66f6a0491e](https://linux-hardware.org/?probe=66f6a0491e) | Mar 07, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [c0f8008427](https://linux-hardware.org/?probe=c0f8008427) | Mar 07, 2023 |
| Microtech     | ebookPro                    | Notebook    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [aeb7d7a9f4](https://linux-hardware.org/?probe=aeb7d7a9f4) | Feb 27, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [83e6da010b](https://linux-hardware.org/?probe=83e6da010b) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [2645328f34](https://linux-hardware.org/?probe=2645328f34) | Feb 23, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [43b2cca281](https://linux-hardware.org/?probe=43b2cca281) | Feb 23, 2023 |
| HP            | 158A                        | Desktop     | [ce217224ba](https://linux-hardware.org/?probe=ce217224ba) | Feb 19, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [e85ff6e5c3](https://linux-hardware.org/?probe=e85ff6e5c3) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | Notebook    | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Pegatron      | EVE                         | Desktop     | [0bde64bb64](https://linux-hardware.org/?probe=0bde64bb64) | Feb 15, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [6e1d13cecb](https://linux-hardware.org/?probe=6e1d13cecb) | Feb 14, 2023 |
| Packard Be... | IXTREME M5800               | Desktop     | [33e3d93b19](https://linux-hardware.org/?probe=33e3d93b19) | Feb 14, 2023 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [dd2d87798a](https://linux-hardware.org/?probe=dd2d87798a) | Feb 13, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | Notebook    | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [feeed093c0](https://linux-hardware.org/?probe=feeed093c0) | Feb 07, 2023 |
| ASUSTek       | P5V-VM DH                   | Desktop     | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [163991dfae](https://linux-hardware.org/?probe=163991dfae) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [a08e60bb31](https://linux-hardware.org/?probe=a08e60bb31) | Feb 03, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [d6829621d7](https://linux-hardware.org/?probe=d6829621d7) | Feb 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [e9d671848c](https://linux-hardware.org/?probe=e9d671848c) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | Notebook    | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [28effc69e6](https://linux-hardware.org/?probe=28effc69e6) | Jan 25, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [4867533043](https://linux-hardware.org/?probe=4867533043) | Jan 25, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [ec7d450cb0](https://linux-hardware.org/?probe=ec7d450cb0) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [d55b2b9507](https://linux-hardware.org/?probe=d55b2b9507) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [8716ca07da](https://linux-hardware.org/?probe=8716ca07da) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [21e1d557cc](https://linux-hardware.org/?probe=21e1d557cc) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [33c845f3a4](https://linux-hardware.org/?probe=33c845f3a4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [24d2721a00](https://linux-hardware.org/?probe=24d2721a00) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [1e1066bd8b](https://linux-hardware.org/?probe=1e1066bd8b) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [7e636906b9](https://linux-hardware.org/?probe=7e636906b9) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [5aa076d0a5](https://linux-hardware.org/?probe=5aa076d0a5) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | Notebook    | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [c32c7f2d35](https://linux-hardware.org/?probe=c32c7f2d35) | Jan 17, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [2b7ce8a40b](https://linux-hardware.org/?probe=2b7ce8a40b) | Jan 17, 2023 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [22c3999607](https://linux-hardware.org/?probe=22c3999607) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f2d7914ecc](https://linux-hardware.org/?probe=f2d7914ecc) | Jan 11, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [f0b4df8849](https://linux-hardware.org/?probe=f0b4df8849) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [23dc9112a8](https://linux-hardware.org/?probe=23dc9112a8) | Dec 27, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [2041ed5cba](https://linux-hardware.org/?probe=2041ed5cba) | Dec 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [01466a6701](https://linux-hardware.org/?probe=01466a6701) | Dec 25, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Clevo         | P170EM                      | Notebook    | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [82687103ac](https://linux-hardware.org/?probe=82687103ac) | Dec 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8862992776](https://linux-hardware.org/?probe=8862992776) | Dec 20, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [6ea891850f](https://linux-hardware.org/?probe=6ea891850f) | Dec 18, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [0679db84af](https://linux-hardware.org/?probe=0679db84af) | Dec 14, 2022 |
| HP            | 350 G1                      | Notebook    | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| HP            | 2B34                        | Desktop     | [18ec4a2e66](https://linux-hardware.org/?probe=18ec4a2e66) | Dec 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| HP            | 8540w                       | Notebook    | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Dell          | Latitude 5490               | Notebook    | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [27af8e61c5](https://linux-hardware.org/?probe=27af8e61c5) | Nov 10, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| MSI           | CSM-H87M-G43                | Desktop     | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| eMachines     | EL1358G                     | Desktop     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | Desktop     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fc4e415fe4](https://linux-hardware.org/?probe=fc4e415fe4) | Oct 02, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | Desktop     | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| HP            | 844C                        | Desktop     | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | Notebook    | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| Dell          | 0RY007                      | Desktop     | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| Dell          | 0RY007                      | Desktop     | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Dell          | 0RY007                      | Desktop     | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | Notebook    | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | 1496                        | Desktop     | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | Notebook    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [89d99d840f](https://linux-hardware.org/?probe=89d99d840f) | Jun 17, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | Desktop     | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | Notebook    | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [5eaef9db5a](https://linux-hardware.org/?probe=5eaef9db5a) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [0ce0f27bac](https://linux-hardware.org/?probe=0ce0f27bac) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Unknown       | Unknown                     | Soc         | [0c5a37efd2](https://linux-hardware.org/?probe=0c5a37efd2) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | Notebook    | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| HP            | 3397                        | Desktop     | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | Notebook    | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| Medion        | E15407                      | Notebook    | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | Notebook    | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| HP            | 2B29                        | Desktop     | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| ASUSTek       | X510UA                      | Notebook    | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | Notebook    | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | Notebook    | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| HP            | Compaq 6820s                | Notebook    | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| HP            | 18E5                        | Desktop     | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [521cf503e2](https://linux-hardware.org/?probe=521cf503e2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| HP            | Compaq 6730s                | Notebook    | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | Notebook    | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | Notebook    | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0123ade8f7](https://linux-hardware.org/?probe=0123ade8f7) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [6280e20fbe](https://linux-hardware.org/?probe=6280e20fbe) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | OptiPlex 9020               | Notebook    | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Toshiba       | NB505                       | Notebook    | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Dell          | Latitude 5521               | Notebook    | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [c081f43e18](https://linux-hardware.org/?probe=c081f43e18) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | Notebook    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | Desktop     | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| Dell          | 0WM839 A00                  | All in one  | [b5edf6760d](https://linux-hardware.org/?probe=b5edf6760d) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| HP            | 21B4 A01                    | Desktop     | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Lenovo        | 36FD SDK0J40709 WIN 3259... | All in one  | [75410d5871](https://linux-hardware.org/?probe=75410d5871) | Mar 27, 2022 |
| Toshiba       | NB505                       | Notebook    | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| Pegatron      | Benicia                     | Desktop     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | Notebook    | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| ASUSTek       | X501A                       | Notebook    | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | Desktop     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | Notebook    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | Notebook    | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Acer          | Aspire X1920                | Desktop     | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| Dell          | 0RW199                      | Desktop     | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [aa341bdff4](https://linux-hardware.org/?probe=aa341bdff4) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | Notebook    | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | Notebook    | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| LG Electro... | 22V240 FAB3                 | All in one  | [23b20c26f2](https://linux-hardware.org/?probe=23b20c26f2) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| MSI           | G41M-P25                    | Desktop     | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | Notebook    | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | Notebook    | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| Gateway       | M-6307                      | Notebook    | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| Sony          | VPCEB3E1E                   | Notebook    | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | 3031h                       | Desktop     | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| HP            | ProBook 650 G3              | Notebook    | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| HP            | 872E                        | Mini pc     | [8366a84cdb](https://linux-hardware.org/?probe=8366a84cdb) | Feb 02, 2022 |
| HP            | 872E                        | Mini pc     | [533e06f8ac](https://linux-hardware.org/?probe=533e06f8ac) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [172fc399f5](https://linux-hardware.org/?probe=172fc399f5) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Dell          | Studio 1450                 | Notebook    | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| ASRock        | M3A UCC                     | Desktop     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| HP            | G42                         | Notebook    | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | Notebook    | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | Notebook    | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b6de24e7df](https://linux-hardware.org/?probe=b6de24e7df) | Jan 20, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [452df44e84](https://linux-hardware.org/?probe=452df44e84) | Jan 20, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | Notebook    | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | Notebook    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [d735255913](https://linux-hardware.org/?probe=d735255913) | Jan 15, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [368d168909](https://linux-hardware.org/?probe=368d168909) | Jan 15, 2022 |
| Insyde        | Braswell                    | Notebook    | [a5bca1e5e8](https://linux-hardware.org/?probe=a5bca1e5e8) | Jan 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | Desktop     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| HP            | 829A                        | Mini pc     | [9526ea61c6](https://linux-hardware.org/?probe=9526ea61c6) | Jan 13, 2022 |
| ASUSTek       | M4A78L-M                    | Desktop     | [dfb87ada40](https://linux-hardware.org/?probe=dfb87ada40) | Jan 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Lenovo        | IdeaPad S415 Touch 20319    | Notebook    | [d59706fc52](https://linux-hardware.org/?probe=d59706fc52) | Jan 11, 2022 |
| HP            | 3031h                       | Desktop     | [46b02ff904](https://linux-hardware.org/?probe=46b02ff904) | Jan 11, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [b01004055c](https://linux-hardware.org/?probe=b01004055c) | Jan 11, 2022 |
| MOTION        | KEX00                       | Notebook    | [8e36590e72](https://linux-hardware.org/?probe=8e36590e72) | Jan 10, 2022 |
| HP            | 3031h                       | Desktop     | [2e78e6c7f8](https://linux-hardware.org/?probe=2e78e6c7f8) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Alienware     | m15 R3                      | Notebook    | [8cff8c6d3f](https://linux-hardware.org/?probe=8cff8c6d3f) | Jan 09, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [7f20d8ac9a](https://linux-hardware.org/?probe=7f20d8ac9a) | Jan 09, 2022 |
| Acer          | Extensa 5620                | Notebook    | [41a1c7001c](https://linux-hardware.org/?probe=41a1c7001c) | Jan 08, 2022 |
| MSI           | H61M-P23                    | Desktop     | [14690b4128](https://linux-hardware.org/?probe=14690b4128) | Jan 08, 2022 |
| Sony          | SVF15A190X                  | Notebook    | [6d729a76af](https://linux-hardware.org/?probe=6d729a76af) | Jan 08, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [65c164f304](https://linux-hardware.org/?probe=65c164f304) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [ef69bbfd12](https://linux-hardware.org/?probe=ef69bbfd12) | Jan 07, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| Gateway       | NV53A                       | Notebook    | [2e67e3a86e](https://linux-hardware.org/?probe=2e67e3a86e) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| HP            | 0AA8h                       | Desktop     | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [aefb321446](https://linux-hardware.org/?probe=aefb321446) | Jan 04, 2022 |
| HP            | 0AA8h                       | Desktop     | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Intel         | DP35DP AAD81073-209         | Desktop     | [f6ec40d0f8](https://linux-hardware.org/?probe=f6ec40d0f8) | Jan 01, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| HP            | G60                         | Notebook    | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Dell          | Inspiron 5765               | Notebook    | [c3a91857b3](https://linux-hardware.org/?probe=c3a91857b3) | Jan 01, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| ECS           | G41T-M2                     | Desktop     | [6b4159a357](https://linux-hardware.org/?probe=6b4159a357) | Dec 29, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [2ab97853e3](https://linux-hardware.org/?probe=2ab97853e3) | Dec 29, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [bc14137c9c](https://linux-hardware.org/?probe=bc14137c9c) | Dec 29, 2021 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| HP            | EliteBook 8440p (VD484AV... | Notebook    | [ba4cf422e7](https://linux-hardware.org/?probe=ba4cf422e7) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [6a61931dde](https://linux-hardware.org/?probe=6a61931dde) | Dec 26, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [00c1f1b6df](https://linux-hardware.org/?probe=00c1f1b6df) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASRock        | A75M-ITX                    | Desktop     | [1070ea74d9](https://linux-hardware.org/?probe=1070ea74d9) | Dec 25, 2021 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [2ef30c62b5](https://linux-hardware.org/?probe=2ef30c62b5) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [602d3e0afd](https://linux-hardware.org/?probe=602d3e0afd) | Dec 23, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3b47550de1](https://linux-hardware.org/?probe=3b47550de1) | Dec 23, 2021 |
| HP            | 3398                        | Desktop     | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [c26a2c5c03](https://linux-hardware.org/?probe=c26a2c5c03) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| Google        | Nami                        | Notebook    | [045f17f15d](https://linux-hardware.org/?probe=045f17f15d) | Dec 22, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [d29b59a855](https://linux-hardware.org/?probe=d29b59a855) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a94bf3ef84](https://linux-hardware.org/?probe=a94bf3ef84) | Dec 19, 2021 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [e3c5530718](https://linux-hardware.org/?probe=e3c5530718) | Dec 19, 2021 |
| Dell          | 0VD5HY A04                  | Desktop     | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| ASUSTek       | P5GC-MX                     | Desktop     | [499a024e97](https://linux-hardware.org/?probe=499a024e97) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [7c3c9b5cdd](https://linux-hardware.org/?probe=7c3c9b5cdd) | Dec 17, 2021 |
| Dell          | System XPS L502X            | Notebook    | [4588c107ed](https://linux-hardware.org/?probe=4588c107ed) | Dec 16, 2021 |
| Biostar       | H110MHC                     | Desktop     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| Toshiba       | Satellite A105              | Notebook    | [4bddc587d8](https://linux-hardware.org/?probe=4bddc587d8) | Dec 15, 2021 |
| MSI           | MS-B0501 100                | Desktop     | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [aa8da2e23c](https://linux-hardware.org/?probe=aa8da2e23c) | Dec 14, 2021 |
| Gateway       | NV53A                       | Notebook    | [1912b6b8c5](https://linux-hardware.org/?probe=1912b6b8c5) | Dec 14, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Dell          | 073MMW A00                  | Desktop     | [c5c064c84f](https://linux-hardware.org/?probe=c5c064c84f) | Dec 13, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [1617abd2f4](https://linux-hardware.org/?probe=1617abd2f4) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [22b04adc28](https://linux-hardware.org/?probe=22b04adc28) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [11ff47f723](https://linux-hardware.org/?probe=11ff47f723) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [0dd637c0b8](https://linux-hardware.org/?probe=0dd637c0b8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b7f8b1fb9](https://linux-hardware.org/?probe=1b7f8b1fb9) | Dec 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8684f34a9e](https://linux-hardware.org/?probe=8684f34a9e) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | Notebook    | [f0c57ccd03](https://linux-hardware.org/?probe=f0c57ccd03) | Dec 10, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [c505dc1521](https://linux-hardware.org/?probe=c505dc1521) | Dec 09, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [a4f61b0f15](https://linux-hardware.org/?probe=a4f61b0f15) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| Acer          | Veriton E430 v1.0           | Desktop     | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ECS           | Nettle2                     | Desktop     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| Dell          | 01W26N A00                  | Desktop     | [7c3e61ec94](https://linux-hardware.org/?probe=7c3e61ec94) | Dec 06, 2021 |
| Acer          | Aspire 5336                 | Notebook    | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Gigabyte      | EP35-DS4                    | Desktop     | [570104ad1e](https://linux-hardware.org/?probe=570104ad1e) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2e34a3a698](https://linux-hardware.org/?probe=2e34a3a698) | Dec 04, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [9f1502866b](https://linux-hardware.org/?probe=9f1502866b) | Dec 03, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [093fef7eaa](https://linux-hardware.org/?probe=093fef7eaa) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [674712f2a1](https://linux-hardware.org/?probe=674712f2a1) | Dec 03, 2021 |
| Toshiba       | Satellite L870-196          | Notebook    | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| Medion        | H81M-P33                    | Desktop     | [29b3a27675](https://linux-hardware.org/?probe=29b3a27675) | Dec 02, 2021 |
| Dell          | Latitude 5401               | Notebook    | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| HP            | 2000                        | Notebook    | [f16b490828](https://linux-hardware.org/?probe=f16b490828) | Dec 01, 2021 |
| HP            | 0AA4h                       | Desktop     | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [190d1b6a29](https://linux-hardware.org/?probe=190d1b6a29) | Dec 01, 2021 |
| ASUSTek       | E203NAS                     | Notebook    | [c400f4df81](https://linux-hardware.org/?probe=c400f4df81) | Nov 30, 2021 |
| Shuttle       | NC03U                       | Desktop     | [2453ada3ba](https://linux-hardware.org/?probe=2453ada3ba) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [29e9d64420](https://linux-hardware.org/?probe=29e9d64420) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| Samsung       | R530/R730/P590              | Notebook    | [0bbf67316b](https://linux-hardware.org/?probe=0bbf67316b) | Nov 28, 2021 |
| Acer          | EG43LMK                     | Desktop     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [d0170808b3](https://linux-hardware.org/?probe=d0170808b3) | Nov 27, 2021 |
| HP            | 0AA8h                       | Desktop     | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [71d58a102c](https://linux-hardware.org/?probe=71d58a102c) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [d9b3bd7851](https://linux-hardware.org/?probe=d9b3bd7851) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [311cb04cc5](https://linux-hardware.org/?probe=311cb04cc5) | Nov 25, 2021 |
| HP            | Pavilion 17                 | Notebook    | [43944b4f78](https://linux-hardware.org/?probe=43944b4f78) | Nov 24, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [5a583ec569](https://linux-hardware.org/?probe=5a583ec569) | Nov 24, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [76361c26c6](https://linux-hardware.org/?probe=76361c26c6) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [fe8ad04ad3](https://linux-hardware.org/?probe=fe8ad04ad3) | Nov 23, 2021 |
| TrekStor      | Primetab T13B               | Tablet      | [19b9435dff](https://linux-hardware.org/?probe=19b9435dff) | Nov 23, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Alienware     | M17x                        | Notebook    | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | Notebook    | [65a59cf71c](https://linux-hardware.org/?probe=65a59cf71c) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | Notebook    | [55d87b9d59](https://linux-hardware.org/?probe=55d87b9d59) | Nov 22, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [b358f07f1d](https://linux-hardware.org/?probe=b358f07f1d) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [930c018424](https://linux-hardware.org/?probe=930c018424) | Nov 20, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [53462f848a](https://linux-hardware.org/?probe=53462f848a) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | Desktop     | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b75a64f96a](https://linux-hardware.org/?probe=b75a64f96a) | Nov 19, 2021 |
| ASUSTek       | B150-PLUS                   | Desktop     | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | Notebook    | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | ProBook 650 G3              | Notebook    | [def83e3614](https://linux-hardware.org/?probe=def83e3614) | Nov 19, 2021 |
| MSI           | 3666h                       | Desktop     | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | GT75VR 7RE                  | Notebook    | [02a0e2b5c8](https://linux-hardware.org/?probe=02a0e2b5c8) | Nov 19, 2021 |
| ONE-NETBOO... | A1                          | Notebook    | [aff2f60770](https://linux-hardware.org/?probe=aff2f60770) | Nov 19, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [fc86b0fc2e](https://linux-hardware.org/?probe=fc86b0fc2e) | Nov 18, 2021 |
| MSI           | 3666h                       | Desktop     | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [befbf7345c](https://linux-hardware.org/?probe=befbf7345c) | Nov 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dfba89a8f0](https://linux-hardware.org/?probe=dfba89a8f0) | Nov 17, 2021 |
| HP            | 0AA8h                       | Desktop     | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| ASRock        | H470 Phantom Gaming 4       | Desktop     | [07ef26c830](https://linux-hardware.org/?probe=07ef26c830) | Nov 16, 2021 |
| Dell          | Latitude 7370               | Notebook    | [b43fadb11c](https://linux-hardware.org/?probe=b43fadb11c) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Apple         | Mac-F2218EC8                | All in one  | [93af642a5d](https://linux-hardware.org/?probe=93af642a5d) | Nov 15, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [dad15363d9](https://linux-hardware.org/?probe=dad15363d9) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | Desktop     | [a8398f9036](https://linux-hardware.org/?probe=a8398f9036) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [746f0808f4](https://linux-hardware.org/?probe=746f0808f4) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [51d1a5ac24](https://linux-hardware.org/?probe=51d1a5ac24) | Nov 12, 2021 |
| ASUSTek       | X501A                       | Notebook    | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Lenovo        | ThinkPad T410 2537MT3       | Notebook    | [76965c829b](https://linux-hardware.org/?probe=76965c829b) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | Notebook    | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | Notebook    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f40b389872](https://linux-hardware.org/?probe=f40b389872) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [425b956614](https://linux-hardware.org/?probe=425b956614) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [39d1d14e62](https://linux-hardware.org/?probe=39d1d14e62) | Nov 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ed14748445](https://linux-hardware.org/?probe=ed14748445) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| Dell          | G3 3500                     | Notebook    | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d864187bdc](https://linux-hardware.org/?probe=d864187bdc) | Nov 06, 2021 |
| Dell          | Precision M4600             | Notebook    | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | Notebook    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [305cca4bc8](https://linux-hardware.org/?probe=305cca4bc8) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8c0647646](https://linux-hardware.org/?probe=f8c0647646) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Toshiba       | Satellite P745              | Notebook    | [59b3468fb9](https://linux-hardware.org/?probe=59b3468fb9) | Nov 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [603fac0b2e](https://linux-hardware.org/?probe=603fac0b2e) | Nov 04, 2021 |
| Dell          | Latitude D630               | Notebook    | [f212896c99](https://linux-hardware.org/?probe=f212896c99) | Nov 04, 2021 |
| Dell          | Precision M4600             | Notebook    | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| Medion        | MS-7366                     | Desktop     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [9fd353eaff](https://linux-hardware.org/?probe=9fd353eaff) | Nov 04, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [86dd6331fc](https://linux-hardware.org/?probe=86dd6331fc) | Nov 02, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [29af280c0e](https://linux-hardware.org/?probe=29af280c0e) | Nov 01, 2021 |
| ASUSTek       | P2540UA                     | Notebook    | [f10ce209c4](https://linux-hardware.org/?probe=f10ce209c4) | Nov 01, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | Notebook    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | Notebook    | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| Khadas        | VIM3                        | Soc         | [14bc5c234d](https://linux-hardware.org/?probe=14bc5c234d) | Oct 30, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Acer          | Aspire X3990                | Desktop     | [967427d98c](https://linux-hardware.org/?probe=967427d98c) | Oct 29, 2021 |
| Acer          | Aspire X3990                | Desktop     | [7ccc4b3004](https://linux-hardware.org/?probe=7ccc4b3004) | Oct 29, 2021 |
| sunxi         | Libre Computer Board ALL... | Soc         | [8f5ad2889e](https://linux-hardware.org/?probe=8f5ad2889e) | Oct 29, 2021 |
| HP            | 8433 11                     | Desktop     | [6183f8775b](https://linux-hardware.org/?probe=6183f8775b) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [5ce9661292](https://linux-hardware.org/?probe=5ce9661292) | Oct 28, 2021 |
| HP            | Compaq 6730s                | Notebook    | [8bc4483616](https://linux-hardware.org/?probe=8bc4483616) | Oct 27, 2021 |
| Khadas        | VIM3                        | Soc         | [ef5d046e03](https://linux-hardware.org/?probe=ef5d046e03) | Oct 27, 2021 |
| HP            | Pavilion g4                 | Notebook    | [90f6743fbd](https://linux-hardware.org/?probe=90f6743fbd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | Notebook    | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Alienware     | m17 R4                      | Notebook    | [5c569c3982](https://linux-hardware.org/?probe=5c569c3982) | Oct 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| HP            | Compaq 6730s                | Notebook    | [587b440ce4](https://linux-hardware.org/?probe=587b440ce4) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [68f1525bef](https://linux-hardware.org/?probe=68f1525bef) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [1146299277](https://linux-hardware.org/?probe=1146299277) | Oct 23, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [cb8b850048](https://linux-hardware.org/?probe=cb8b850048) | Oct 23, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [f76ae4b159](https://linux-hardware.org/?probe=f76ae4b159) | Oct 22, 2021 |
| HP            | kip                         | Notebook    | [18f48f3a5b](https://linux-hardware.org/?probe=18f48f3a5b) | Oct 22, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| HP            | Notebook                    | Notebook    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [6be3808b94](https://linux-hardware.org/?probe=6be3808b94) | Oct 21, 2021 |
| HP            | 1998                        | Desktop     | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Lenovo        | IdeaPad U550 20034,3749     | Notebook    | [3bbec8b8fd](https://linux-hardware.org/?probe=3bbec8b8fd) | Oct 21, 2021 |
| Dell          | 0PU052                      | Desktop     | [7e7d0bc489](https://linux-hardware.org/?probe=7e7d0bc489) | Oct 21, 2021 |
| ASUSTek       | PRIME H310T                 | Desktop     | [b0e10a4766](https://linux-hardware.org/?probe=b0e10a4766) | Oct 20, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | Notebook    | [8ad9f2f898](https://linux-hardware.org/?probe=8ad9f2f898) | Oct 20, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [7fb2681427](https://linux-hardware.org/?probe=7fb2681427) | Oct 20, 2021 |
| Lenovo        | B5400 s20278Q               | Notebook    | [c71ca98310](https://linux-hardware.org/?probe=c71ca98310) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| Dell          | 0KX11M A04                  | Server      | [df26c4e8c4](https://linux-hardware.org/?probe=df26c4e8c4) | Oct 19, 2021 |
| Samsung       | R530/R730/P590              | Notebook    | [e76e147759](https://linux-hardware.org/?probe=e76e147759) | Oct 19, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [555bb7179c](https://linux-hardware.org/?probe=555bb7179c) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [63cab5e07f](https://linux-hardware.org/?probe=63cab5e07f) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [355e464f7f](https://linux-hardware.org/?probe=355e464f7f) | Oct 19, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [235b6e8d1a](https://linux-hardware.org/?probe=235b6e8d1a) | Oct 18, 2021 |
| Acer          | Extensa 5630                | Notebook    | [4823b348aa](https://linux-hardware.org/?probe=4823b348aa) | Oct 18, 2021 |
| HP            | 8717                        | Desktop     | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Latitude E6440              | Notebook    | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [9debdd654c](https://linux-hardware.org/?probe=9debdd654c) | Oct 15, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b9218a0347](https://linux-hardware.org/?probe=b9218a0347) | Oct 15, 2021 |
| Supermicro    | X8DTH                       | Server      | [ad4abe60cd](https://linux-hardware.org/?probe=ad4abe60cd) | Oct 13, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [ef126ad790](https://linux-hardware.org/?probe=ef126ad790) | Oct 13, 2021 |
| Clientron     | Pineview-D                  | Desktop     | [59bf0b789c](https://linux-hardware.org/?probe=59bf0b789c) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [6163de66f1](https://linux-hardware.org/?probe=6163de66f1) | Oct 12, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e922eda008](https://linux-hardware.org/?probe=e922eda008) | Oct 12, 2021 |
| eMachines     | G730                        | Notebook    | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | Desktop     | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | Notebook    | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| Dell          | Latitude 7370               | Notebook    | [348b718b2b](https://linux-hardware.org/?probe=348b718b2b) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [56135a7fa6](https://linux-hardware.org/?probe=56135a7fa6) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [d7676eeb32](https://linux-hardware.org/?probe=d7676eeb32) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [c49cbf2f7a](https://linux-hardware.org/?probe=c49cbf2f7a) | Oct 11, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [6d2f43a452](https://linux-hardware.org/?probe=6d2f43a452) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| Dell          | Precision 5540              | Notebook    | [b59369e8e7](https://linux-hardware.org/?probe=b59369e8e7) | Oct 08, 2021 |
| Multilaser    | UB32X                       | Notebook    | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | Desktop     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [248c508eb0](https://linux-hardware.org/?probe=248c508eb0) | Oct 07, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [0735063fbe](https://linux-hardware.org/?probe=0735063fbe) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [399430cdbe](https://linux-hardware.org/?probe=399430cdbe) | Oct 06, 2021 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [d09fddd2b5](https://linux-hardware.org/?probe=d09fddd2b5) | Oct 06, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | Desktop     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Acer          | Aspire X1430                | Desktop     | [0864e39368](https://linux-hardware.org/?probe=0864e39368) | Oct 05, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [697843fefc](https://linux-hardware.org/?probe=697843fefc) | Oct 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [9ba5143844](https://linux-hardware.org/?probe=9ba5143844) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [37caf69047](https://linux-hardware.org/?probe=37caf69047) | Oct 02, 2021 |
| Sony          | VGN-NR38E_S                 | Notebook    | [8cb5fc39c1](https://linux-hardware.org/?probe=8cb5fc39c1) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [5cccf30dd4](https://linux-hardware.org/?probe=5cccf30dd4) | Oct 01, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 97        | 4.14%   |
| 5.4.0-48-generic    | 54        | 2.3%    |
| 5.11.0-27-generic   | 50        | 2.13%   |
| 5.4.0-52-generic    | 47        | 2.01%   |
| 5.4.0-29-generic    | 46        | 1.96%   |
| 5.4.0-58-generic    | 45        | 1.92%   |
| 5.4.0-65-generic    | 43        | 1.84%   |
| 5.4.0-54-generic    | 40        | 1.71%   |
| 5.4.0-42-lowlatency | 40        | 1.71%   |
| 5.4.0-26-generic    | 38        | 1.62%   |
| 5.4.0-40-generic    | 35        | 1.49%   |
| 5.4.0-47-generic    | 33        | 1.41%   |
| 5.4.0-37-generic    | 33        | 1.41%   |
| 5.4.0-31-generic    | 30        | 1.28%   |
| 5.4.0-29-lowlatency | 27        | 1.15%   |
| 5.4.0-66-generic    | 26        | 1.11%   |
| 5.4.0-33-generic    | 25        | 1.07%   |
| 5.4.0-89-generic    | 23        | 0.98%   |
| 5.8.0-53-generic    | 22        | 0.94%   |
| 5.4.0-72-generic    | 21        | 0.9%    |
| 5.4.0-70-generic    | 21        | 0.9%    |
| 5.4.0-40-lowlatency | 21        | 0.9%    |
| 5.13.0-30-generic   | 21        | 0.9%    |
| 5.8.0-43-generic    | 20        | 0.85%   |
| 5.4.0-91-generic    | 20        | 0.85%   |
| 5.11.0-37-generic   | 20        | 0.85%   |
| 5.4.0-58-lowlatency | 19        | 0.81%   |
| 5.4.0-56-generic    | 19        | 0.81%   |
| 5.4.0-77-generic    | 18        | 0.77%   |
| 5.4.0-65-lowlatency | 18        | 0.77%   |
| 5.4.0-45-generic    | 18        | 0.77%   |
| 5.4.0-37-lowlatency | 18        | 0.77%   |
| 5.4.0-125-generic   | 18        | 0.77%   |
| 5.4.0-67-generic    | 17        | 0.73%   |
| 5.4.0-53-generic    | 17        | 0.73%   |
| 5.4.0-52-lowlatency | 17        | 0.73%   |
| 5.4.0-126-generic   | 17        | 0.73%   |
| 5.4.0-81-generic    | 16        | 0.68%   |
| 5.4.0-74-generic    | 16        | 0.68%   |
| 5.13.0-39-generic   | 16        | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1372      | 66.47%  |
| 5.11.0  | 202       | 9.79%   |
| 5.8.0   | 170       | 8.24%   |
| 5.13.0  | 133       | 6.44%   |
| 5.15.0  | 104       | 5.04%   |
| 5.10.0  | 5         | 0.24%   |
| 5.9.0   | 3         | 0.15%   |
| 5.6.0   | 3         | 0.15%   |
| 5.14.0  | 3         | 0.15%   |
| 4.4.194 | 3         | 0.15%   |
| 5.9.8   | 2         | 0.1%    |
| 5.7.7   | 2         | 0.1%    |
| 5.7.6   | 2         | 0.1%    |
| 5.7.0   | 2         | 0.1%    |
| 5.3.0   | 2         | 0.1%    |
| 5.18.0  | 2         | 0.1%    |
| 5.16.0  | 2         | 0.1%    |
| 5.12.12 | 2         | 0.1%    |
| 5.12.10 | 2         | 0.1%    |
| 4.9.140 | 2         | 0.1%    |
| 4.4.254 | 2         | 0.1%    |
| 4.15.0  | 2         | 0.1%    |
| 5.9.6   | 1         | 0.05%   |
| 5.9.16  | 1         | 0.05%   |
| 5.9.14  | 1         | 0.05%   |
| 5.9.1   | 1         | 0.05%   |
| 5.8.5   | 1         | 0.05%   |
| 5.8.18  | 1         | 0.05%   |
| 5.8.16  | 1         | 0.05%   |
| 5.8.13  | 1         | 0.05%   |
| 5.8.1   | 1         | 0.05%   |
| 5.7.17  | 1         | 0.05%   |
| 5.7.1   | 1         | 0.05%   |
| 5.6.6   | 1         | 0.05%   |
| 5.6.19  | 1         | 0.05%   |
| 5.6.14  | 1         | 0.05%   |
| 5.4.67  | 1         | 0.05%   |
| 5.4.65  | 1         | 0.05%   |
| 5.4.64  | 1         | 0.05%   |
| 5.4.209 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1377      | 66.78%  |
| 5.11    | 203       | 9.84%   |
| 5.8     | 175       | 8.49%   |
| 5.13    | 133       | 6.45%   |
| 5.15    | 108       | 5.24%   |
| 5.10    | 11        | 0.53%   |
| 5.9     | 9         | 0.44%   |
| 5.7     | 8         | 0.39%   |
| 5.6     | 6         | 0.29%   |
| 5.14    | 6         | 0.29%   |
| 4.4     | 6         | 0.29%   |
| 5.12    | 5         | 0.24%   |
| 4.9     | 5         | 0.24%   |
| 5.3     | 2         | 0.1%    |
| 5.18    | 2         | 0.1%    |
| 5.16    | 2         | 0.1%    |
| 4.15    | 2         | 0.1%    |
| 5.17    | 1         | 0.05%   |
| 4.19    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1986      | 98.51%  |
| aarch64 | 23        | 1.14%   |
| armv7l  | 7         | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 1923      | 95.39%  |
| GNOME           | 64        | 3.17%   |
| KDE5            | 6         | 0.3%    |
| i3              | 5         | 0.25%   |
| Unity           | 3         | 0.15%   |
| MATE            | 3         | 0.15%   |
| Cinnamon        | 3         | 0.15%   |
| LXQt            | 2         | 0.1%    |
| GNUstep         | 2         | 0.1%    |
| GNOME Flashback | 2         | 0.1%    |
| xmonad          | 1         | 0.05%   |
| X-Cinnamon      | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1963      | 97.32%  |
| Tty     | 41        | 2.03%   |
| Wayland | 9         | 0.45%   |
| Web     | 3         | 0.15%   |
| Unknown | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 949       | 45.8%   |
| LightDM | 720       | 34.75%  |
| TDM     | 339       | 16.36%  |
| GDM     | 36        | 1.74%   |
| GDM3    | 19        | 0.92%   |
| SDDM    | 5         | 0.24%   |
| XDM     | 3         | 0.14%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 689       | 34.11%  |
| de_DE | 218       | 10.79%  |
| fr_FR | 195       | 9.65%   |
| ru_RU | 117       | 5.79%   |
| pt_BR | 109       | 5.4%    |
| it_IT | 91        | 4.5%    |
| C     | 89        | 4.41%   |
| en_GB | 81        | 4.01%   |
| en_CA | 52        | 2.57%   |
| es_ES | 42        | 2.08%   |
| pl_PL | 34        | 1.68%   |
| en_AU | 27        | 1.34%   |
| ja_JP | 22        | 1.09%   |
| nl_NL | 21        | 1.04%   |
| es_AR | 20        | 0.99%   |
| hu_HU | 18        | 0.89%   |
| en_IN | 15        | 0.74%   |
| cs_CZ | 12        | 0.59%   |
| de_AT | 11        | 0.54%   |
| fr_BE | 10        | 0.5%    |
| es_MX | 10        | 0.5%    |
| sv_SE | 9         | 0.45%   |
| fi_FI | 9         | 0.45%   |
| de_CH | 9         | 0.45%   |
| fr_CA | 8         | 0.4%    |
| es_CO | 7         | 0.35%   |
| ru_UA | 6         | 0.3%    |
| zh_CN | 5         | 0.25%   |
| pt_PT | 5         | 0.25%   |
| es_PE | 5         | 0.25%   |
| zh_TW | 4         | 0.2%    |
| ro_RO | 4         | 0.2%    |
| es_UY | 4         | 0.2%    |
| en_ZA | 4         | 0.2%    |
| en_NZ | 4         | 0.2%    |
| el_GR | 4         | 0.2%    |
| uk_UA | 3         | 0.15%   |
| tr_TR | 3         | 0.15%   |
| sl_SI | 3         | 0.15%   |
| nl_BE | 3         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1225      | 60.34%  |
| EFI  | 805       | 39.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1847      | 90.9%   |
| Overlay | 87        | 4.28%   |
| Tmpfs   | 32        | 1.57%   |
| Btrfs   | 31        | 1.53%   |
| Zfs     | 18        | 0.89%   |
| Xfs     | 8         | 0.39%   |
| Ext2    | 4         | 0.2%    |
| Ext3    | 3         | 0.15%   |
| Unknown | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1158      | 56.85%  |
| GPT     | 495       | 24.3%   |
| MBR     | 384       | 18.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1688      | 82.26%  |
| Yes       | 364       | 17.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1324      | 64.81%  |
| Yes       | 719       | 35.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 317       | 15.72%  |
| ASUSTek Computer        | 310       | 15.38%  |
| Dell                    | 261       | 12.95%  |
| Lenovo                  | 241       | 11.95%  |
| Gigabyte Technology     | 136       | 6.75%   |
| Acer                    | 114       | 5.65%   |
| MSI                     | 85        | 4.22%   |
| ASRock                  | 80        | 3.97%   |
| Toshiba                 | 51        | 2.53%   |
| Apple                   | 41        | 2.03%   |
| Intel                   | 35        | 1.74%   |
| Medion                  | 27        | 1.34%   |
| Samsung Electronics     | 24        | 1.19%   |
| Fujitsu                 | 23        | 1.14%   |
| Unknown                 | 21        | 1.04%   |
| ECS                     | 19        | 0.94%   |
| Sony                    | 17        | 0.84%   |
| Packard Bell            | 14        | 0.69%   |
| Notebook                | 12        | 0.6%    |
| Fujitsu Siemens         | 11        | 0.55%   |
| Raspberry Pi Foundation | 10        | 0.5%    |
| Positivo                | 8         | 0.4%    |
| Pegatron                | 8         | 0.4%    |
| Clevo                   | 8         | 0.4%    |
| Foxconn                 | 7         | 0.35%   |
| eMachines               | 6         | 0.3%    |
| TUXEDO                  | 5         | 0.25%   |
| Gateway                 | 5         | 0.25%   |
| Biostar                 | 5         | 0.25%   |
| AMI                     | 5         | 0.25%   |
| Nvidia                  | 4         | 0.2%    |
| HUAWEI                  | 4         | 0.2%    |
| Google                  | 4         | 0.2%    |
| Alienware               | 4         | 0.2%    |
| Supermicro              | 3         | 0.15%   |
| Schenker                | 3         | 0.15%   |
| LG Electronics          | 3         | 0.15%   |
| Itautec                 | 3         | 0.15%   |
| GPU Company             | 3         | 0.15%   |
| Dynabook                | 3         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 30        | 1.49%   |
| ASUS All Series                        | 26        | 1.29%   |
| Gigabyte H410M S2H                     | 15        | 0.74%   |
| HP Notebook                            | 11        | 0.55%   |
| Gigabyte H81M-S2V                      | 9         | 0.45%   |
| ECS G31T-M9                            | 9         | 0.45%   |
| Dell OptiPlex 7010                     | 8         | 0.4%    |
| Dell Latitude D630                     | 8         | 0.4%    |
| HP Pavilion dv6                        | 6         | 0.3%    |
| Dell Latitude E6430                    | 6         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.3%    |
| HP Pavilion dv7                        | 5         | 0.25%   |
| HP 15                                  | 5         | 0.25%   |
| Dell OptiPlex 780                      | 5         | 0.25%   |
| Dell OptiPlex 755                      | 5         | 0.25%   |
| Dell OptiPlex 390                      | 5         | 0.25%   |
| ASUS TUF Gaming X570-PLUS              | 5         | 0.25%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 4         | 0.2%    |
| MSI MS-7B79                            | 4         | 0.2%    |
| MSI MS-7721                            | 4         | 0.2%    |
| Intel H61                              | 4         | 0.2%    |
| HP ProDesk 600 G1 SFF                  | 4         | 0.2%    |
| HP ProDesk 405 G6 Desktop Mini PC      | 4         | 0.2%    |
| HP Pavilion g6                         | 4         | 0.2%    |
| HP EliteBook 8560p                     | 4         | 0.2%    |
| HP Compaq Elite 8300 SFF               | 4         | 0.2%    |
| Gigabyte B450M DS3H                    | 4         | 0.2%    |
| Dell OptiPlex 9020                     | 4         | 0.2%    |
| Dell OptiPlex 760                      | 4         | 0.2%    |
| Dell Latitude E6330                    | 4         | 0.2%    |
| ASUS K53SC                             | 4         | 0.2%    |
| ASRock N68C-S UCC                      | 4         | 0.2%    |
| Apple Macmini4,1                       | 4         | 0.2%    |
| Toshiba Satellite A100                 | 3         | 0.15%   |
| Toshiba PORTEGE R930                   | 3         | 0.15%   |
| RPi Raspberry Pi 4 Model B Rev 1.1     | 3         | 0.15%   |
| Nvidia Tegra                           | 3         | 0.15%   |
| MSI MS-7A34                            | 3         | 0.15%   |
| MSI MS-7693                            | 3         | 0.15%   |
| HP Z620 Workstation                    | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 126       | 6.25%   |
| Acer Aspire           | 75        | 3.72%   |
| Dell Latitude         | 70        | 3.47%   |
| Dell Inspiron         | 67        | 3.32%   |
| HP Pavilion           | 55        | 2.73%   |
| Dell OptiPlex         | 54        | 2.68%   |
| HP Compaq             | 53        | 2.63%   |
| Toshiba Satellite     | 41        | 2.03%   |
| Lenovo IdeaPad        | 35        | 1.74%   |
| HP EliteBook          | 34        | 1.69%   |
| Unknown               | 30        | 1.49%   |
| ASUS PRIME            | 26        | 1.29%   |
| ASUS All              | 26        | 1.29%   |
| HP ProBook            | 23        | 1.14%   |
| ASUS VivoBook         | 23        | 1.14%   |
| HP Laptop             | 22        | 1.09%   |
| Lenovo ThinkCentre    | 20        | 0.99%   |
| Dell Precision        | 19        | 0.94%   |
| Dell Vostro           | 16        | 0.79%   |
| Gigabyte H410M        | 15        | 0.74%   |
| ASUS TUF              | 15        | 0.74%   |
| HP ProDesk            | 14        | 0.69%   |
| HP Notebook           | 12        | 0.6%    |
| Acer Extensa          | 12        | 0.6%    |
| RPi Raspberry         | 10        | 0.5%    |
| Fujitsu ESPRIMO       | 10        | 0.5%    |
| Gigabyte H81M-S2V     | 9         | 0.45%   |
| ECS G31T-M9           | 9         | 0.45%   |
| ASUS ROG              | 9         | 0.45%   |
| Dell Studio           | 8         | 0.4%    |
| Packard Bell EasyNote | 7         | 0.35%   |
| HP ENVY               | 7         | 0.35%   |
| Fujitsu LIFEBOOK      | 7         | 0.35%   |
| Dell XPS              | 7         | 0.35%   |
| Dell PowerEdge        | 7         | 0.35%   |
| ASUS M5A78L-M         | 7         | 0.35%   |
| Lenovo IdeaCentre     | 6         | 0.3%    |
| HP ProLiant           | 6         | 0.3%    |
| HP Presario           | 6         | 0.3%    |
| HP EliteDesk          | 6         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 195       | 9.67%   |
| 2012    | 186       | 9.23%   |
| 2013    | 167       | 8.28%   |
| 2010    | 154       | 7.64%   |
| 2019    | 142       | 7.04%   |
| 2014    | 142       | 7.04%   |
| 2009    | 131       | 6.5%    |
| 2020    | 128       | 6.35%   |
| 2018    | 127       | 6.3%    |
| 2008    | 125       | 6.2%    |
| 2017    | 114       | 5.65%   |
| 2007    | 101       | 5.01%   |
| 2015    | 92        | 4.56%   |
| 2016    | 80        | 3.97%   |
| 2021    | 59        | 2.93%   |
| 2006    | 31        | 1.54%   |
| Unknown | 25        | 1.24%   |
| 2005    | 10        | 0.5%    |
| 2022    | 7         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1039      | 51.54%  |
| Desktop        | 860       | 42.66%  |
| Mini pc        | 28        | 1.39%   |
| System on chip | 26        | 1.29%   |
| All in one     | 24        | 1.19%   |
| Convertible    | 20        | 0.99%   |
| Server         | 14        | 0.69%   |
| Tablet         | 4         | 0.2%    |
| Other          | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1901      | 94.06%  |
| Enabled  | 120       | 5.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2011      | 99.75%  |
| Yes  | 5         | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 555       | 27.19%  |
| 4.01-8.0        | 432       | 21.17%  |
| 16.01-24.0      | 314       | 15.38%  |
| 8.01-16.0       | 312       | 15.29%  |
| 1.01-2.0        | 158       | 7.74%   |
| 32.01-64.0      | 126       | 6.17%   |
| 64.01-256.0     | 46        | 2.25%   |
| 2.01-3.0        | 42        | 2.06%   |
| 0.51-1.0        | 28        | 1.37%   |
| 24.01-32.0      | 25        | 1.22%   |
| More than 256.0 | 2         | 0.1%    |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 992       | 44.83%  |
| 2.01-3.0   | 470       | 21.24%  |
| 0.51-1.0   | 284       | 12.83%  |
| 4.01-8.0   | 219       | 9.9%    |
| 3.01-4.0   | 165       | 7.46%   |
| 8.01-16.0  | 58        | 2.62%   |
| 16.01-24.0 | 11        | 0.5%    |
| 0.01-0.5   | 9         | 0.41%   |
| 24.01-32.0 | 5         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1215      | 58.78%  |
| 2      | 519       | 25.11%  |
| 3      | 180       | 8.71%   |
| 4      | 68        | 3.29%   |
| 5      | 33        | 1.6%    |
| 0      | 25        | 1.21%   |
| 6      | 11        | 0.53%   |
| 7      | 8         | 0.39%   |
| 10     | 3         | 0.15%   |
| 9      | 2         | 0.1%    |
| 8      | 2         | 0.1%    |
| 11     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1050      | 51.85%  |
| No        | 975       | 48.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1841      | 91.27%  |
| No        | 176       | 8.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1415      | 69.67%  |
| No        | 616       | 30.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1144      | 56.02%  |
| Yes       | 898       | 43.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 366       | 18.07%  |
| Germany      | 265       | 13.09%  |
| France       | 201       | 9.93%   |
| Russia       | 141       | 6.96%   |
| Brazil       | 121       | 5.98%   |
| Italy        | 104       | 5.14%   |
| Canada       | 98        | 4.84%   |
| UK           | 77        | 3.8%    |
| Spain        | 62        | 3.06%   |
| Netherlands  | 56        | 2.77%   |
| Poland       | 38        | 1.88%   |
| Australia    | 29        | 1.43%   |
| Japan        | 26        | 1.28%   |
| Belgium      | 26        | 1.28%   |
| Argentina    | 26        | 1.28%   |
| Ukraine      | 22        | 1.09%   |
| Sweden       | 20        | 0.99%   |
| Hungary      | 20        | 0.99%   |
| Finland      | 18        | 0.89%   |
| Mexico       | 17        | 0.84%   |
| Austria      | 17        | 0.84%   |
| Portugal     | 16        | 0.79%   |
| Czechia      | 16        | 0.79%   |
| India        | 15        | 0.74%   |
| Indonesia    | 13        | 0.64%   |
| Romania      | 12        | 0.59%   |
| Greece       | 12        | 0.59%   |
| Switzerland  | 11        | 0.54%   |
| Bulgaria     | 10        | 0.49%   |
| Turkey       | 9         | 0.44%   |
| Norway       | 8         | 0.4%    |
| Colombia     | 8         | 0.4%    |
| Slovenia     | 7         | 0.35%   |
| Iran         | 6         | 0.3%    |
| Denmark      | 6         | 0.3%    |
| Uruguay      | 5         | 0.25%   |
| Thailand     | 5         | 0.25%   |
| Taiwan       | 5         | 0.25%   |
| South Africa | 5         | 0.25%   |
| Serbia       | 5         | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 44        | 2.07%   |
| Paris             | 26        | 1.22%   |
| Moscow            | 23        | 1.08%   |
| Berlin            | 22        | 1.04%   |
| Québec           | 19        | 0.89%   |
| Hamburg           | 16        | 0.75%   |
| Sydney            | 14        | 0.66%   |
| Warsaw            | 13        | 0.61%   |
| Rome              | 13        | 0.61%   |
| Munich            | 13        | 0.61%   |
| Milan             | 13        | 0.61%   |
| Budapest          | 13        | 0.61%   |
| Sao Paulo         | 12        | 0.57%   |
| Amsterdam         | 12        | 0.57%   |
| St Petersburg     | 11        | 0.52%   |
| Madrid            | 11        | 0.52%   |
| Vancouver         | 10        | 0.47%   |
| Rio de Janeiro    | 10        | 0.47%   |
| Montreal          | 9         | 0.42%   |
| Frankfurt am Main | 9         | 0.42%   |
| Athens            | 9         | 0.42%   |
| Vienna            | 8         | 0.38%   |
| Toronto           | 8         | 0.38%   |
| Cologne           | 8         | 0.38%   |
| Chicago           | 8         | 0.38%   |
| Barcelona         | 8         | 0.38%   |
| Kyiv              | 7         | 0.33%   |
| Helsinki          | 7         | 0.33%   |
| Belo Horizonte    | 7         | 0.33%   |
| Seattle           | 6         | 0.28%   |
| Lisbon            | 6         | 0.28%   |
| Leipzig           | 6         | 0.28%   |
| Karlsruhe         | 6         | 0.28%   |
| Genoa             | 6         | 0.28%   |
| Denver            | 6         | 0.28%   |
| Springfield       | 5         | 0.24%   |
| Sofia             | 5         | 0.24%   |
| Salvador          | 5         | 0.24%   |
| Saint Paul        | 5         | 0.24%   |
| Riga              | 5         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 521       | 779    | 18.17%  |
| WDC                 | 497       | 713    | 17.34%  |
| Samsung Electronics | 401       | 555    | 13.99%  |
| Toshiba             | 195       | 243    | 6.8%    |
| Unknown             | 142       | 174    | 4.95%   |
| Kingston            | 138       | 168    | 4.81%   |
| Hitachi             | 131       | 176    | 4.57%   |
| SanDisk             | 101       | 133    | 3.52%   |
| Crucial             | 89        | 114    | 3.1%    |
| Intel               | 56        | 84     | 1.95%   |
| HGST                | 56        | 69     | 1.95%   |
| SK hynix            | 46        | 54     | 1.6%    |
| A-DATA Technology   | 41        | 50     | 1.43%   |
| Fujitsu             | 29        | 36     | 1.01%   |
| Micron Technology   | 26        | 28     | 0.91%   |
| China               | 24        | 25     | 0.84%   |
| Maxtor              | 21        | 28     | 0.73%   |
| Intenso             | 21        | 28     | 0.73%   |
| PNY                 | 19        | 25     | 0.66%   |
| Patriot             | 18        | 21     | 0.63%   |
| OCZ                 | 14        | 19     | 0.49%   |
| Transcend           | 13        | 14     | 0.45%   |
| Phison              | 13        | 17     | 0.45%   |
| KIOXIA              | 12        | 19     | 0.42%   |
| Apple               | 12        | 16     | 0.42%   |
| Apacer              | 11        | 13     | 0.38%   |
| SPCC                | 10        | 20     | 0.35%   |
| LITEON              | 10        | 12     | 0.35%   |
| Silicon Motion      | 8         | 8      | 0.28%   |
| Hewlett-Packard     | 8         | 14     | 0.28%   |
| LITEONIT            | 7         | 9      | 0.24%   |
| JMicron Technology  | 7         | 7      | 0.24%   |
| ASMT                | 6         | 8      | 0.21%   |
| KingSpec            | 5         | 6      | 0.17%   |
| GOODRAM             | 5         | 6      | 0.17%   |
| Corsair             | 5         | 5      | 0.17%   |
| Unknown             | 5         | 5      | 0.17%   |
| USB3.0              | 4         | 5      | 0.14%   |
| Smartbuy            | 4         | 4      | 0.14%   |
| SABRENT             | 4         | 4      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 43        | 1.35%   |
| Unknown MMC Card  32GB              | 31        | 0.98%   |
| Samsung SSD 860 EVO 500GB           | 24        | 0.75%   |
| Seagate ST500DM002-1BD142 500GB     | 23        | 0.72%   |
| Samsung SSD 850 EVO 250GB           | 23        | 0.72%   |
| Kingston SA400S37480G 480GB SSD     | 23        | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB      | 20        | 0.63%   |
| Unknown MMC Card  64GB              | 19        | 0.6%    |
| Seagate ST500LT012-1DG142 500GB     | 19        | 0.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 18        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 18        | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB      | 17        | 0.53%   |
| Samsung SSD 860 EVO 1TB             | 17        | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB      | 16        | 0.5%    |
| Seagate Expansion 1TB               | 15        | 0.47%   |
| Seagate ST2000DM001-1CH164 2TB      | 14        | 0.44%   |
| Unknown SD/MMC/MS PRO 256GB         | 13        | 0.41%   |
| Seagate ST3500418AS 500GB           | 13        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB      | 13        | 0.41%   |
| HGST HTS721010A9E630 1TB            | 13        | 0.41%   |
| Crucial CT500MX500SSD1 500GB        | 13        | 0.41%   |
| Unknown MMC Card  128GB             | 12        | 0.38%   |
| Toshiba MQ01ABF050 500GB            | 12        | 0.38%   |
| Samsung SSD 850 EVO 500GB           | 12        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD    | 12        | 0.38%   |
| Kingston SA400S37120G 120GB SSD     | 12        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB         | 12        | 0.38%   |
| Toshiba MQ01ABD100 1TB              | 11        | 0.35%   |
| Seagate ST31000524AS 1TB            | 11        | 0.35%   |
| Samsung HM321HI 320GB               | 11        | 0.35%   |
| Unknown MMC Card  16GB              | 10        | 0.31%   |
| Toshiba DT01ACA100 1TB              | 10        | 0.31%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 0.31%   |
| Seagate ST4000DM004-2CV104 4TB      | 10        | 0.31%   |
| Seagate ST31000528AS 1TB            | 10        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB      | 10        | 0.31%   |
| Samsung SSD 860 EVO 250GB           | 10        | 0.31%   |
| Samsung NVMe SSD Drive 512GB        | 10        | 0.31%   |
| WDC WD5000AZLX-07K2TA0 500GB        | 9         | 0.28%   |
| SanDisk SSD PLUS 240GB              | 9         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 512       | 767    | 34.48%  |
| WDC                 | 429       | 620    | 28.89%  |
| Toshiba             | 163       | 206    | 10.98%  |
| Hitachi             | 131       | 176    | 8.82%   |
| Samsung Electronics | 97        | 126    | 6.53%   |
| HGST                | 56        | 69     | 3.77%   |
| Fujitsu             | 28        | 35     | 1.89%   |
| Maxtor              | 20        | 27     | 1.35%   |
| Unknown             | 14        | 17     | 0.94%   |
| Intenso             | 5         | 6      | 0.34%   |
| JMicron Technology  | 4         | 4      | 0.27%   |
| SSK                 | 3         | 3      | 0.2%    |
| Hewlett-Packard     | 3         | 8      | 0.2%    |
| ASMT                | 3         | 5      | 0.2%    |
| WD MediaMax         | 2         | 2      | 0.13%   |
| TO Exter            | 2         | 2      | 0.13%   |
| Apple               | 2         | 3      | 0.13%   |
| USB3.0              | 1         | 2      | 0.07%   |
| SAGE                | 1         | 1      | 0.07%   |
| LaCie               | 1         | 4      | 0.07%   |
| ICY BOX             | 1         | 1      | 0.07%   |
| HPE                 | 1         | 4      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| ExcelStor           | 1         | 1      | 0.07%   |
| CLOVER              | 1         | 1      | 0.07%   |
| Apricorn            | 1         | 1      | 0.07%   |
| ACASIS              | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 216       | 287    | 23.5%   |
| Kingston            | 127       | 154    | 13.82%  |
| Crucial             | 82        | 107    | 8.92%   |
| SanDisk             | 79        | 107    | 8.6%    |
| WDC                 | 46        | 54     | 5.01%   |
| A-DATA Technology   | 35        | 43     | 3.81%   |
| Intel               | 27        | 39     | 2.94%   |
| China               | 24        | 25     | 2.61%   |
| PNY                 | 19        | 25     | 2.07%   |
| Patriot             | 18        | 21     | 1.96%   |
| Micron Technology   | 17        | 18     | 1.85%   |
| Toshiba             | 15        | 18     | 1.63%   |
| SK hynix            | 14        | 14     | 1.52%   |
| Intenso             | 14        | 16     | 1.52%   |
| OCZ                 | 13        | 17     | 1.41%   |
| Transcend           | 12        | 12     | 1.31%   |
| Apacer              | 11        | 13     | 1.2%    |
| SPCC                | 10        | 20     | 1.09%   |
| LITEON              | 10        | 12     | 1.09%   |
| LITEONIT            | 7         | 9      | 0.76%   |
| Unknown             | 6         | 7      | 0.65%   |
| Apple               | 6         | 7      | 0.65%   |
| GOODRAM             | 5         | 6      | 0.54%   |
| Corsair             | 5         | 5      | 0.54%   |
| Smartbuy            | 4         | 4      | 0.44%   |
| SABRENT             | 4         | 4      | 0.44%   |
| Mushkin             | 4         | 4      | 0.44%   |
| KingSpec            | 4         | 5      | 0.44%   |
| KingDian            | 4         | 4      | 0.44%   |
| Hewlett-Packard     | 4         | 6      | 0.44%   |
| USB3.0              | 3         | 3      | 0.33%   |
| Team                | 3         | 4      | 0.33%   |
| Seagate             | 3         | 3      | 0.33%   |
| Netac               | 3         | 3      | 0.33%   |
| Lexar               | 3         | 3      | 0.33%   |
| Kingmax             | 3         | 3      | 0.33%   |
| Gigabyte Technology | 3         | 5      | 0.33%   |
| Emtec               | 3         | 3      | 0.33%   |
| Drevo               | 3         | 3      | 0.33%   |
| Dogfish             | 3         | 4      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1228      | 2094   | 48.27%  |
| SSD     | 826       | 1150   | 32.47%  |
| NVMe    | 327       | 432    | 12.85%  |
| MMC     | 125       | 152    | 4.91%   |
| Unknown | 38        | 46     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1708      | 3124   | 74.68%  |
| NVMe | 327       | 431    | 14.3%   |
| SAS  | 127       | 167    | 5.55%   |
| MMC  | 125       | 152    | 5.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1343      | 2010   | 62.32%  |
| 0.51-1.0        | 540       | 791    | 25.06%  |
| 1.01-2.0        | 147       | 231    | 6.82%   |
| 2.01-3.0        | 43        | 72     | 2%      |
| 3.01-4.0        | 39        | 72     | 1.81%   |
| 4.01-10.0       | 39        | 64     | 1.81%   |
| 10.01-20.0      | 2         | 2      | 0.09%   |
| More than 100.0 | 1         | 1      | 0.05%   |
| 0               | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 643       | 30.88%  |
| 251-500        | 489       | 23.49%  |
| 501-1000       | 296       | 14.22%  |
| 51-100         | 151       | 7.25%   |
| 1001-2000      | 146       | 7.01%   |
| 21-50          | 107       | 5.14%   |
| More than 3000 | 95        | 4.56%   |
| 1-20           | 83        | 3.99%   |
| 2001-3000      | 58        | 2.79%   |
| Unknown        | 14        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 773       | 35.72%  |
| 21-50          | 389       | 17.98%  |
| 101-250        | 313       | 14.46%  |
| 51-100         | 280       | 12.94%  |
| 251-500        | 152       | 7.02%   |
| 501-1000       | 113       | 5.22%   |
| 1001-2000      | 68        | 3.14%   |
| More than 3000 | 37        | 1.71%   |
| 2001-3000      | 25        | 1.16%   |
| Unknown        | 14        | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 2.2%    |
| Seagate ST500LT012-9WS142 500GB    | 3         | 3      | 1.65%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 3      | 1.65%   |
| Hitachi HDS721050CLA362 500GB      | 3         | 3      | 1.65%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 2         | 2      | 1.1%    |
| WDC WD4000FYYZ-01UL1B1 4TB         | 2         | 3      | 1.1%    |
| WDC WD1002FAEX-00Z3A0 1TB          | 2         | 2      | 1.1%    |
| Toshiba MQ01ABD100 1TB             | 2         | 3      | 1.1%    |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 1.1%    |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.1%    |
| Seagate ST3250318AS 250GB          | 2         | 2      | 1.1%    |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 3      | 1.1%    |
| Seagate ST1000DL002-9TT153 1TB     | 2         | 2      | 1.1%    |
| Samsung Electronics HM321HI 320GB  | 2         | 2      | 1.1%    |
| Samsung Electronics HD103SI 1TB    | 2         | 2      | 1.1%    |
| Samsung Electronics HD081GJ 80GB   | 2         | 2      | 1.1%    |
| Kingston SA400S37240G 240GB SSD    | 2         | 2      | 1.1%    |
| Hitachi HTS725032A9A364 320GB      | 2         | 2      | 1.1%    |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.1%    |
| HGST HTS545050A7E680 500GB         | 2         | 2      | 1.1%    |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 1      | 0.55%   |
| WDC WD6400AAKS-22A7B2 640GB        | 1         | 1      | 0.55%   |
| WDC WD6400AAKS-22A7B0 640GB        | 1         | 1      | 0.55%   |
| WDC WD5000LPVX-08V0TT5 500GB       | 1         | 1      | 0.55%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 1      | 0.55%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 1         | 1      | 0.55%   |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 1      | 0.55%   |
| WDC WD5000AAKX-60U6AA0 500GB       | 1         | 1      | 0.55%   |
| WDC WD5000AAKX-08U6AA0 500GB       | 1         | 1      | 0.55%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 1      | 0.55%   |
| WDC WD5000AAKS-22V1A0 500GB        | 1         | 1      | 0.55%   |
| WDC WD5000AAKS-00A7B0 500GB        | 1         | 1      | 0.55%   |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.55%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.55%   |
| WDC WD3200BEVT-75ZCT1 320GB        | 1         | 1      | 0.55%   |
| WDC WD3200AVJS-63TBA0 320GB        | 1         | 1      | 0.55%   |
| WDC WD3200AAKS-00L9A0 320GB        | 1         | 1      | 0.55%   |
| WDC WD3200AAJS-60Z0A0 320GB        | 1         | 1      | 0.55%   |
| WDC WD3200AAJS-08L7A0 320GB        | 1         | 1      | 0.55%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 1      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 55     | 27.68%  |
| WDC                 | 39        | 45     | 22.03%  |
| Toshiba             | 19        | 23     | 10.73%  |
| Samsung Electronics | 14        | 17     | 7.91%   |
| Hitachi             | 14        | 14     | 7.91%   |
| SK hynix            | 5         | 5      | 2.82%   |
| HGST                | 5         | 6      | 2.82%   |
| Kingston            | 4         | 4      | 2.26%   |
| Fujitsu             | 4         | 5      | 2.26%   |
| Maxtor              | 3         | 3      | 1.69%   |
| Intel               | 3         | 3      | 1.69%   |
| A-DATA Technology   | 3         | 4      | 1.69%   |
| OCZ                 | 2         | 2      | 1.13%   |
| Micron Technology   | 2         | 2      | 1.13%   |
| Unknown             | 1         | 1      | 0.56%   |
| SanDisk             | 1         | 1      | 0.56%   |
| Mushkin             | 1         | 1      | 0.56%   |
| LDLC                | 1         | 1      | 0.56%   |
| ICY BOX             | 1         | 1      | 0.56%   |
| FORESEE             | 1         | 1      | 0.56%   |
| Crucial             | 1         | 1      | 0.56%   |
| China               | 1         | 1      | 0.56%   |
| Avant               | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |
| Apacer              | 1         | 1      | 0.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 55     | 33.79%  |
| WDC                 | 39        | 45     | 26.9%   |
| Toshiba             | 19        | 23     | 13.1%   |
| Hitachi             | 14        | 14     | 9.66%   |
| Samsung Electronics | 11        | 13     | 7.59%   |
| HGST                | 5         | 6      | 3.45%   |
| Fujitsu             | 4         | 5      | 2.76%   |
| Maxtor              | 3         | 3      | 2.07%   |
| ICY BOX             | 1         | 1      | 0.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 137       | 165    | 81.07%  |
| SSD  | 30        | 32     | 17.75%  |
| NVMe | 2         | 2      | 1.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB           | 1         | 1      | 33.33%  |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 33.33%  |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 1         | 1      | 33.33%  |
| Seagate           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1282      | 2588   | 60.05%  |
| Works    | 683       | 1084   | 31.99%  |
| Malfunc  | 167       | 199    | 7.82%   |
| Failed   | 3         | 3      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1409      | 61.29%  |
| AMD                              | 363       | 15.79%  |
| Samsung Electronics              | 113       | 4.92%   |
| Nvidia                           | 61        | 2.65%   |
| SanDisk                          | 52        | 2.26%   |
| ASMedia Technology               | 39        | 1.7%    |
| JMicron Technology               | 35        | 1.52%   |
| Marvell Technology Group         | 30        | 1.3%    |
| SK hynix                         | 27        | 1.17%   |
| VIA Technologies                 | 17        | 0.74%   |
| Toshiba America Info Systems     | 14        | 0.61%   |
| Phison Electronics               | 14        | 0.61%   |
| KIOXIA                           | 14        | 0.61%   |
| Kingston Technology Company      | 13        | 0.57%   |
| Micron Technology                | 10        | 0.43%   |
| Silicon Motion                   | 9         | 0.39%   |
| Micron/Crucial Technology        | 9         | 0.39%   |
| LSI Logic / Symbios Logic        | 9         | 0.39%   |
| ADATA Technology                 | 9         | 0.39%   |
| Realtek Semiconductor            | 8         | 0.35%   |
| Silicon Integrated Systems [SiS] | 7         | 0.3%    |
| Broadcom / LSI                   | 6         | 0.26%   |
| Silicon Image                    | 5         | 0.22%   |
| Hewlett-Packard                  | 4         | 0.17%   |
| Apple                            | 4         | 0.17%   |
| Union Memory (Shenzhen)          | 3         | 0.13%   |
| Integrated Technology Express    | 3         | 0.13%   |
| Seagate Technology               | 2         | 0.09%   |
| Promise Technology               | 2         | 0.09%   |
| Lite-On Technology               | 2         | 0.09%   |
| Adaptec                          | 2         | 0.09%   |
| Solid State Storage Technology   | 1         | 0.04%   |
| OCZ Technology Group             | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 225       | 7.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 104       | 3.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 98        | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 74        | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 72        | 2.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 72        | 2.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 64        | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 64        | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 63        | 2.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 62        | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 60        | 2.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 59        | 2.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 55        | 1.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 53        | 1.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 53        | 1.86%   |
| Intel SATA Controller [RAID mode]                                                       | 43        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 43        | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 41        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 40        | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                                  | 39        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 38        | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 37        | 1.3%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 37        | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 36        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34        | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 28        | 0.98%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 25        | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 24        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 24        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 24        | 0.84%   |
| Nvidia MCP61 SATA Controller                                                            | 23        | 0.81%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 23        | 0.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 22        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 20        | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 19        | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 19        | 0.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 19        | 0.67%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 19        | 0.67%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 19        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1447      | 59.67%  |
| IDE  | 488       | 20.12%  |
| NVMe | 320       | 13.2%   |
| RAID | 153       | 6.31%   |
| SAS  | 10        | 0.41%   |
| SCSI | 7         | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1542      | 76.49%  |
| AMD          | 442       | 21.92%  |
| ARM          | 30        | 1.49%   |
| CentaurHauls | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| ARM Processor                           | 23        | 1.14%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 19        | 0.94%   |
| Intel Core i3-10100 CPU @ 3.60GHz       | 17        | 0.84%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 15        | 0.74%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 14        | 0.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 14        | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 13        | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 12        | 0.59%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 12        | 0.59%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 12        | 0.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 11        | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 11        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 11        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 10        | 0.49%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 10        | 0.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 10        | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 10        | 0.49%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.49%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 10        | 0.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.49%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 10        | 0.49%   |
| AMD FX-8350 Eight-Core Processor        | 10        | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 9         | 0.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 0.44%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 9         | 0.44%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 9         | 0.44%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 9         | 0.44%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz    | 9         | 0.44%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 9         | 0.44%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 9         | 0.44%   |
| Intel Celeron CPU J1800 @ 2.41GHz       | 9         | 0.44%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 9         | 0.44%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 8         | 0.4%    |
| Intel Core i7-2600K CPU @ 3.40GHz       | 8         | 0.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 8         | 0.4%    |
| Intel Core i5-6400 CPU @ 2.70GHz        | 8         | 0.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 8         | 0.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz        | 8         | 0.4%    |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 0.4%    |
| Intel Core i5-2410M CPU @ 2.30GHz       | 8         | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 384       | 18.99%  |
| Intel Core i7           | 318       | 15.73%  |
| Intel Core i3           | 184       | 9.1%    |
| Intel Core 2 Duo        | 153       | 7.57%   |
| Intel Celeron           | 127       | 6.28%   |
| Other                   | 74        | 3.66%   |
| Intel Pentium           | 68        | 3.36%   |
| AMD Ryzen 5             | 64        | 3.17%   |
| Intel Xeon              | 55        | 2.72%   |
| Intel Pentium Dual-Core | 48        | 2.37%   |
| Intel Atom              | 48        | 2.37%   |
| AMD Ryzen 7             | 46        | 2.27%   |
| AMD FX                  | 30        | 1.48%   |
| Intel Core 2 Quad       | 28        | 1.38%   |
| Intel Core 2            | 23        | 1.14%   |
| AMD A8                  | 23        | 1.14%   |
| Intel Pentium Dual      | 22        | 1.09%   |
| AMD A6                  | 19        | 0.94%   |
| AMD Athlon II X2        | 18        | 0.89%   |
| AMD Ryzen 3             | 17        | 0.84%   |
| AMD E1                  | 17        | 0.84%   |
| AMD Phenom II X4        | 16        | 0.79%   |
| AMD Ryzen 9             | 14        | 0.69%   |
| AMD Athlon 64 X2        | 14        | 0.69%   |
| AMD A10                 | 14        | 0.69%   |
| AMD E                   | 13        | 0.64%   |
| AMD A4                  | 12        | 0.59%   |
| AMD Ryzen 7 PRO         | 11        | 0.54%   |
| Intel Core i9           | 9         | 0.45%   |
| AMD Turion 64 X2 Mobile | 9         | 0.45%   |
| AMD Athlon              | 9         | 0.45%   |
| Intel Pentium Silver    | 8         | 0.4%    |
| AMD E2                  | 8         | 0.4%    |
| Intel Genuine           | 7         | 0.35%   |
| AMD Athlon II X4        | 7         | 0.35%   |
| AMD Ryzen 5 PRO         | 6         | 0.3%    |
| AMD Phenom II X6        | 6         | 0.3%    |
| Intel Pentium D         | 5         | 0.25%   |
| Intel Pentium 4         | 5         | 0.25%   |
| AMD Sempron             | 5         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 975       | 48.22%  |
| 4       | 729       | 36.05%  |
| 6       | 118       | 5.84%   |
| 8       | 87        | 4.3%    |
| 1       | 63        | 3.12%   |
| 12      | 20        | 0.99%   |
| 3       | 11        | 0.54%   |
| 16      | 7         | 0.35%   |
| 10      | 4         | 0.2%    |
| 20      | 3         | 0.15%   |
| 24      | 2         | 0.1%    |
| 64      | 1         | 0.05%   |
| 14      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1989      | 98.66%  |
| 2       | 26        | 1.29%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1066      | 52.8%   |
| 1       | 952       | 47.15%  |
| Unknown | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1994      | 98.91%  |
| Unknown        | 20        | 0.99%   |
| 64-bit         | 2         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 239       | 11.63%  |
| 0x206a7    | 172       | 8.37%   |
| 0x306a9    | 152       | 7.4%    |
| 0x1067a    | 128       | 6.23%   |
| 0x306c3    | 110       | 5.35%   |
| 0x6fd      | 62        | 3.02%   |
| 0x20655    | 48        | 2.34%   |
| 0x506e3    | 41        | 2%      |
| 0x10676    | 40        | 1.95%   |
| 0x40651    | 38        | 1.85%   |
| 0x906ea    | 35        | 1.7%    |
| 0x010000c8 | 34        | 1.65%   |
| 0x806ea    | 33        | 1.61%   |
| 0x406e3    | 33        | 1.61%   |
| 0x30678    | 32        | 1.56%   |
| 0x906e9    | 30        | 1.46%   |
| 0x806ec    | 29        | 1.41%   |
| 0x08108109 | 29        | 1.41%   |
| 0x20652    | 27        | 1.31%   |
| 0x6fb      | 26        | 1.27%   |
| 0x806e9    | 25        | 1.22%   |
| 0x06000852 | 25        | 1.22%   |
| 0x306d4    | 24        | 1.17%   |
| 0x406c4    | 23        | 1.12%   |
| 0x05000119 | 23        | 1.12%   |
| 0x806c1    | 21        | 1.02%   |
| 0x08701021 | 21        | 1.02%   |
| 0x0800820d | 21        | 1.02%   |
| 0xa0653    | 20        | 0.97%   |
| 0x6f6      | 20        | 0.97%   |
| 0x106e5    | 19        | 0.92%   |
| 0x07030105 | 19        | 0.92%   |
| 0xa0652    | 17        | 0.83%   |
| 0x406c3    | 17        | 0.83%   |
| 0x0700010f | 17        | 0.83%   |
| 0x706a1    | 16        | 0.78%   |
| 0x106ca    | 16        | 0.78%   |
| 0x706e5    | 14        | 0.68%   |
| 0x06001119 | 14        | 0.68%   |
| 0x906ed    | 13        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 196       | 9.7%    |
| SandyBridge      | 194       | 9.6%    |
| Penryn           | 181       | 8.96%   |
| Haswell          | 174       | 8.61%   |
| IvyBridge        | 168       | 8.31%   |
| Core             | 130       | 6.43%   |
| Westmere         | 90        | 4.45%   |
| Skylake          | 88        | 4.35%   |
| Silvermont       | 88        | 4.35%   |
| K10              | 67        | 3.32%   |
| Zen+             | 62        | 3.07%   |
| Zen 2            | 53        | 2.62%   |
| CometLake        | 44        | 2.18%   |
| Unknown          | 44        | 2.18%   |
| Piledriver       | 43        | 2.13%   |
| K8 Hammer        | 39        | 1.93%   |
| Zen              | 33        | 1.63%   |
| Nehalem          | 31        | 1.53%   |
| Bobcat           | 31        | 1.53%   |
| Broadwell        | 29        | 1.43%   |
| TigerLake        | 25        | 1.24%   |
| Goldmont plus    | 25        | 1.24%   |
| Puma             | 24        | 1.19%   |
| Bonnell          | 23        | 1.14%   |
| IceLake          | 21        | 1.04%   |
| Excavator        | 19        | 0.94%   |
| Zen 3            | 18        | 0.89%   |
| Jaguar           | 18        | 0.89%   |
| Goldmont         | 17        | 0.84%   |
| K10 Llano        | 12        | 0.59%   |
| NetBurst         | 11        | 0.54%   |
| K8 & K10 hybrid  | 8         | 0.4%    |
| Steamroller      | 6         | 0.3%    |
| Bulldozer        | 5         | 0.25%   |
| Alderlake Hybrid | 4         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1132      | 49.69%  |
| Nvidia                           | 628       | 27.57%  |
| AMD                              | 494       | 21.69%  |
| Matrox Electronics Systems       | 10        | 0.44%   |
| VIA Technologies                 | 6         | 0.26%   |
| Silicon Integrated Systems [SiS] | 4         | 0.18%   |
| ASPEED Technology                | 4         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 140       | 5.91%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 94        | 3.97%   |
| Intel Core Processor Integrated Graphics Controller                                      | 58        | 2.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 54        | 2.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 48        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 43        | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 43        | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 42        | 1.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 40        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 40        | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 39        | 1.65%   |
| Intel UHD Graphics 620                                                                   | 35        | 1.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 32        | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 28        | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 27        | 1.14%   |
| Intel HD Graphics 620                                                                    | 26        | 1.1%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 25        | 1.06%   |
| Intel HD Graphics 530                                                                    | 24        | 1.01%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 24        | 1.01%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 0.84%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 20        | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 19        | 0.8%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 19        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 0.72%   |
| Intel HD Graphics 630                                                                    | 17        | 0.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.72%   |
| Intel HD Graphics 5500                                                                   | 16        | 0.68%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 0.63%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 15        | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                               | 14        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.59%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 14        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 878       | 43.34%  |
| 1 x Nvidia               | 419       | 20.68%  |
| 1 x AMD                  | 394       | 19.45%  |
| Intel + Nvidia           | 179       | 8.84%   |
| Intel + AMD              | 52        | 2.57%   |
| Other                    | 32        | 1.58%   |
| 2 x AMD                  | 25        | 1.23%   |
| AMD + Nvidia             | 17        | 0.84%   |
| 1 x Matrox               | 7         | 0.35%   |
| 1 x VIA                  | 6         | 0.3%    |
| 2 x Nvidia               | 4         | 0.2%    |
| 1 x SiS                  | 4         | 0.2%    |
| Nvidia + ASPEED          | 3         | 0.15%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.05%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + Matrox             | 1         | 0.05%   |
| AMD + ASPEED             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1573      | 77.41%  |
| Proprietary | 364       | 17.91%  |
| Unknown     | 95        | 4.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1063      | 51.96%  |
| 0.01-0.5   | 306       | 14.96%  |
| 1.01-2.0   | 237       | 11.58%  |
| 0.51-1.0   | 221       | 10.8%   |
| 3.01-4.0   | 120       | 5.87%   |
| 7.01-8.0   | 46        | 2.25%   |
| 5.01-6.0   | 28        | 1.37%   |
| 2.01-3.0   | 11        | 0.54%   |
| 8.01-16.0  | 11        | 0.54%   |
| 4.01-5.0   | 2         | 0.1%    |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 295       | 13.86%  |
| AU Optronics            | 213       | 10%     |
| LG Display              | 197       | 9.25%   |
| Dell                    | 132       | 6.2%    |
| Chimei Innolux          | 130       | 6.11%   |
| BOE                     | 117       | 5.5%    |
| Goldstar                | 89        | 4.18%   |
| Hewlett-Packard         | 88        | 4.13%   |
| Acer                    | 76        | 3.57%   |
| AOC                     | 53        | 2.49%   |
| Philips                 | 52        | 2.44%   |
| Lenovo                  | 51        | 2.4%    |
| Chi Mei Optoelectronics | 51        | 2.4%    |
| Ancor Communications    | 49        | 2.3%    |
| BenQ                    | 35        | 1.64%   |
| Apple                   | 33        | 1.55%   |
| ViewSonic               | 25        | 1.17%   |
| LG Philips              | 24        | 1.13%   |
| LG Electronics          | 24        | 1.13%   |
| Iiyama                  | 24        | 1.13%   |
| Unknown                 | 22        | 1.03%   |
| Sony                    | 22        | 1.03%   |
| HannStar                | 22        | 1.03%   |
| Fujitsu Siemens         | 19        | 0.89%   |
| Sharp                   | 18        | 0.85%   |
| Panasonic               | 16        | 0.75%   |
| InfoVision              | 15        | 0.7%    |
| NEC Computers           | 12        | 0.56%   |
| Eizo                    | 11        | 0.52%   |
| Packard Bell            | 10        | 0.47%   |
| PKB                     | 9         | 0.42%   |
| Medion                  | 9         | 0.42%   |
| Toshiba                 | 8         | 0.38%   |
| PANDA                   | 8         | 0.38%   |
| ASUSTek Computer        | 8         | 0.38%   |
| Vizio                   | 7         | 0.33%   |
| Vestel Elektronik       | 6         | 0.28%   |
| MStar                   | 6         | 0.28%   |
| Lenovo Group Limited    | 6         | 0.28%   |
| IBM                     | 5         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 15        | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 13        | 0.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 12        | 0.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 11        | 0.5%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.46%   |
| PKB LCD Monitor Viseo223DX 1920x1080                                     | 9         | 0.41%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 8         | 0.36%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 477x268mm 21.5-inch            | 8         | 0.36%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 8         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.36%   |
| Ancor Communications ASUS VS197 ACI19F2 1366x768 410x230mm 18.5-inch     | 8         | 0.36%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.32%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 6         | 0.27%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                           | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.27%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 5         | 0.23%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 5         | 0.23%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 5         | 0.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 4         | 0.18%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 4         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 4         | 0.18%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 4         | 0.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 4         | 0.18%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.18%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.18%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 4         | 0.18%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x173mm 13.9-inch                  | 4         | 0.18%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 4         | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.18%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 4         | 0.18%   |
| Dell S2721DS DELA19D 2560x1440 597x336mm 27.0-inch                       | 4         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 4         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 749       | 36.2%   |
| 1366x768 (WXGA)    | 459       | 22.18%  |
| 1600x900 (HD+)     | 105       | 5.07%   |
| 1280x1024 (SXGA)   | 101       | 4.88%   |
| 1440x900 (WXGA+)   | 94        | 4.54%   |
| 3840x2160 (4K)     | 92        | 4.45%   |
| 1280x800 (WXGA)    | 90        | 4.35%   |
| 1680x1050 (WSXGA+) | 71        | 3.43%   |
| 2560x1440 (QHD)    | 64        | 3.09%   |
| 1920x1200 (WUXGA)  | 51        | 2.46%   |
| Unknown            | 37        | 1.79%   |
| 1360x768           | 23        | 1.11%   |
| 1024x600           | 15        | 0.72%   |
| 1600x1200          | 14        | 0.68%   |
| 3840x1080          | 12        | 0.58%   |
| 1024x768 (XGA)     | 12        | 0.58%   |
| 1920x540           | 8         | 0.39%   |
| 2560x1600          | 7         | 0.34%   |
| 1280x720 (HD)      | 7         | 0.34%   |
| 3440x1440          | 6         | 0.29%   |
| 2560x1080          | 6         | 0.29%   |
| 5120x1440          | 4         | 0.19%   |
| 3840x1200          | 3         | 0.14%   |
| 3200x1800 (QHD+)   | 3         | 0.14%   |
| 3200x1080          | 3         | 0.14%   |
| 2880x1800          | 3         | 0.14%   |
| 2288x1287          | 3         | 0.14%   |
| 3840x2400          | 2         | 0.1%    |
| 3286x1080          | 2         | 0.1%    |
| 3200x900           | 2         | 0.1%    |
| 2960x1050          | 2         | 0.1%    |
| 7680x1080          | 1         | 0.05%   |
| 7360x1200          | 1         | 0.05%   |
| 6400x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5760x1200          | 1         | 0.05%   |
| 5440x1200          | 1         | 0.05%   |
| 5280x2160          | 1         | 0.05%   |
| 4480x1440          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 463       | 21.93%  |
| Unknown | 183       | 8.67%   |
| 14      | 170       | 8.05%   |
| 13      | 151       | 7.15%   |
| 17      | 147       | 6.96%   |
| 24      | 130       | 6.16%   |
| 23      | 130       | 6.16%   |
| 21      | 120       | 5.68%   |
| 19      | 98        | 4.64%   |
| 27      | 92        | 4.36%   |
| 18      | 68        | 3.22%   |
| 20      | 50        | 2.37%   |
| 31      | 41        | 1.94%   |
| 22      | 39        | 1.85%   |
| 12      | 39        | 1.85%   |
| 11      | 28        | 1.33%   |
| 84      | 20        | 0.95%   |
| 10      | 19        | 0.9%    |
| 16      | 12        | 0.57%   |
| 72      | 10        | 0.47%   |
| 54      | 10        | 0.47%   |
| 34      | 10        | 0.47%   |
| 52      | 9         | 0.43%   |
| 32      | 9         | 0.43%   |
| 25      | 9         | 0.43%   |
| 40      | 8         | 0.38%   |
| 26      | 8         | 0.38%   |
| 48      | 5         | 0.24%   |
| 28      | 5         | 0.24%   |
| 37      | 4         | 0.19%   |
| 46      | 3         | 0.14%   |
| 57      | 2         | 0.09%   |
| 42      | 2         | 0.09%   |
| 39      | 2         | 0.09%   |
| 29      | 2         | 0.09%   |
| 142     | 1         | 0.05%   |
| 86      | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 69      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 748       | 35.84%  |
| 501-600        | 342       | 16.39%  |
| 401-500        | 312       | 14.95%  |
| Unknown        | 183       | 8.77%   |
| 351-400        | 176       | 8.43%   |
| 201-300        | 159       | 7.62%   |
| 601-700        | 61        | 2.92%   |
| 1001-1500      | 34        | 1.63%   |
| 1501-2000      | 32        | 1.53%   |
| 701-800        | 20        | 0.96%   |
| 801-900        | 15        | 0.72%   |
| 901-1000       | 3         | 0.14%   |
| More than 2000 | 1         | 0.05%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1324      | 67.86%  |
| 16/10   | 302       | 15.48%  |
| Unknown | 170       | 8.71%   |
| 5/4     | 97        | 4.97%   |
| 4/3     | 30        | 1.54%   |
| 21/9    | 10        | 0.51%   |
| 3/2     | 8         | 0.41%   |
| 6/5     | 3         | 0.15%   |
| 1.00    | 2         | 0.1%    |
| 32/9    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 1.96    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 466       | 22.23%  |
| 201-250        | 336       | 16.03%  |
| 81-90          | 261       | 12.45%  |
| 151-200        | 184       | 8.78%   |
| Unknown        | 183       | 8.73%   |
| 141-150        | 99        | 4.72%   |
| 301-350        | 96        | 4.58%   |
| 121-130        | 83        | 3.96%   |
| 351-500        | 65        | 3.1%    |
| More than 1000 | 62        | 2.96%   |
| 251-300        | 61        | 2.91%   |
| 71-80          | 54        | 2.58%   |
| 61-70          | 37        | 1.77%   |
| 51-60          | 28        | 1.34%   |
| 501-1000       | 25        | 1.19%   |
| 131-140        | 24        | 1.15%   |
| 41-50          | 19        | 0.91%   |
| 91-100         | 7         | 0.33%   |
| 111-120        | 5         | 0.24%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 759       | 37.32%  |
| 101-120       | 573       | 28.17%  |
| 121-160       | 396       | 19.47%  |
| Unknown       | 183       | 9%      |
| 161-240       | 56        | 2.75%   |
| 1-50          | 53        | 2.61%   |
| More than 240 | 14        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1665      | 81.18%  |
| 2     | 273       | 13.31%  |
| 0     | 88        | 4.29%   |
| 3     | 22        | 1.07%   |
| 4     | 3         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1094      | 36%     |
| Intel                             | 852       | 28.04%  |
| Qualcomm Atheros                  | 363       | 11.94%  |
| Broadcom                          | 218       | 7.17%   |
| Marvell Technology Group          | 53        | 1.74%   |
| Nvidia                            | 50        | 1.65%   |
| TP-Link                           | 41        | 1.35%   |
| Ralink Technology                 | 40        | 1.32%   |
| Broadcom Limited                  | 40        | 1.32%   |
| Ralink                            | 36        | 1.18%   |
| Qualcomm Atheros Communications   | 18        | 0.59%   |
| Samsung Electronics               | 16        | 0.53%   |
| NetGear                           | 13        | 0.43%   |
| Huawei Technologies               | 13        | 0.43%   |
| JMicron Technology                | 12        | 0.39%   |
| D-Link System                     | 12        | 0.39%   |
| D-Link                            | 12        | 0.39%   |
| MediaTek                          | 10        | 0.33%   |
| VIA Technologies                  | 9         | 0.3%    |
| Sierra Wireless                   | 9         | 0.3%    |
| Xiaomi                            | 7         | 0.23%   |
| Ericsson Business Mobile Networks | 7         | 0.23%   |
| Edimax Technology                 | 7         | 0.23%   |
| DisplayLink                       | 7         | 0.23%   |
| Belkin Components                 | 7         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 6         | 0.2%    |
| Dell                              | 6         | 0.2%    |
| ASUSTek Computer                  | 6         | 0.2%    |
| Linksys                           | 5         | 0.16%   |
| Lenovo                            | 5         | 0.16%   |
| Qualcomm                          | 4         | 0.13%   |
| Microsoft                         | 4         | 0.13%   |
| AVM                               | 4         | 0.13%   |
| Attansic Technology               | 4         | 0.13%   |
| ASIX Electronics                  | 4         | 0.13%   |
| Aquantia                          | 4         | 0.13%   |
| TRENDnet                          | 3         | 0.1%    |
| Hewlett-Packard                   | 3         | 0.1%    |
| Fibocom                           | 3         | 0.1%    |
| Motorola PCS                      | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 742       | 21.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 170       | 4.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 104       | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 54        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 50        | 1.42%   |
| Intel Wi-Fi 6 AX200                                                     | 48        | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 1.33%   |
| Intel Ethernet Connection I217-LM                                       | 42        | 1.19%   |
| Intel Wireless 8265 / 8275                                              | 39        | 1.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 35        | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 0.99%   |
| Intel Wireless 7260                                                     | 34        | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 33        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 0.91%   |
| Intel Wireless 7265                                                     | 29        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 0.77%   |
| Intel Wireless 8260                                                     | 26        | 0.74%   |
| Intel I211 Gigabit Network Connection                                   | 26        | 0.74%   |
| Intel 82579V Gigabit Network Connection                                 | 25        | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 24        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                    | 24        | 0.68%   |
| Nvidia MCP61 Ethernet                                                   | 22        | 0.62%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 22        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 21        | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 20        | 0.57%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 20        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 19        | 0.54%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                                | 19        | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 0.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 17        | 0.48%   |
| Intel Wireless 3165                                                     | 17        | 0.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 17        | 0.48%   |
| Intel Centrino Ultimate-N 6300                                          | 17        | 0.48%   |
| Intel Centrino Advanced-N 6200                                          | 17        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 561       | 37.25%  |
| Qualcomm Atheros                      | 292       | 19.39%  |
| Realtek Semiconductor                 | 263       | 17.46%  |
| Broadcom                              | 135       | 8.96%   |
| Ralink Technology                     | 40        | 2.66%   |
| TP-Link                               | 39        | 2.59%   |
| Ralink                                | 36        | 2.39%   |
| Broadcom Limited                      | 21        | 1.39%   |
| Qualcomm Atheros Communications       | 18        | 1.2%    |
| NetGear                               | 13        | 0.86%   |
| D-Link                                | 12        | 0.8%    |
| Sierra Wireless                       | 9         | 0.6%    |
| D-Link System                         | 8         | 0.53%   |
| Edimax Technology                     | 7         | 0.46%   |
| Belkin Components                     | 7         | 0.46%   |
| ASUSTek Computer                      | 6         | 0.4%    |
| Linksys                               | 5         | 0.33%   |
| Microsoft                             | 4         | 0.27%   |
| MediaTek                              | 4         | 0.27%   |
| Dell                                  | 4         | 0.27%   |
| AVM                                   | 4         | 0.27%   |
| TRENDnet                              | 3         | 0.2%    |
| Fibocom                               | 3         | 0.2%    |
| IMC Networks                          | 2         | 0.13%   |
| Hewlett-Packard                       | 2         | 0.13%   |
| Ericsson Business Mobile Networks     | 2         | 0.13%   |
| ZyXEL Communications                  | 1         | 0.07%   |
| ZyDAS                                 | 1         | 0.07%   |
| Qualcomm                              | 1         | 0.07%   |
| Philips (or NXP)                      | 1         | 0.07%   |
| Marvell Technology Group              | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 54        | 3.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 50        | 3.29%   |
| Intel Wi-Fi 6 AX200                                                     | 48        | 3.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 3.09%   |
| Intel Wireless 8265 / 8275                                              | 39        | 2.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 35        | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 2.3%    |
| Intel Wireless 7260                                                     | 34        | 2.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 33        | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 32        | 2.1%    |
| Intel Wireless 7265                                                     | 29        | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.77%   |
| Intel Wireless 8260                                                     | 26        | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 1.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 20        | 1.31%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 20        | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 19        | 1.25%   |
| Intel Wi-Fi 6 AX201                                                     | 19        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.18%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 18        | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 17        | 1.12%   |
| Intel Wireless 3165                                                     | 17        | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 17        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 17        | 1.12%   |
| Intel Centrino Advanced-N 6200                                          | 17        | 1.12%   |
| Ralink MT7601U Wireless Adapter                                         | 16        | 1.05%   |
| Qualcomm Atheros AR9271 802.11n                                         | 16        | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 15        | 0.99%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 0.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 13        | 0.85%   |
| Intel Wireless 3160                                                     | 13        | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 13        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 12        | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 982       | 50.46%  |
| Intel                            | 515       | 26.46%  |
| Qualcomm Atheros                 | 110       | 5.65%   |
| Broadcom                         | 105       | 5.4%    |
| Marvell Technology Group         | 52        | 2.67%   |
| Nvidia                           | 50        | 2.57%   |
| Broadcom Limited                 | 19        | 0.98%   |
| Samsung Electronics              | 16        | 0.82%   |
| JMicron Technology               | 12        | 0.62%   |
| VIA Technologies                 | 9         | 0.46%   |
| Huawei Technologies              | 8         | 0.41%   |
| Xiaomi                           | 7         | 0.36%   |
| MediaTek                         | 7         | 0.36%   |
| DisplayLink                      | 7         | 0.36%   |
| Silicon Integrated Systems [SiS] | 6         | 0.31%   |
| Lenovo                           | 5         | 0.26%   |
| D-Link System                    | 4         | 0.21%   |
| Attansic Technology              | 4         | 0.21%   |
| ASIX Electronics                 | 4         | 0.21%   |
| Aquantia                         | 4         | 0.21%   |
| Qualcomm                         | 3         | 0.15%   |
| TP-Link                          | 2         | 0.1%    |
| Motorola PCS                     | 2         | 0.1%    |
| LG Electronics                   | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| 3Com                             | 2         | 0.1%    |
| Spreadtrum Communications        | 1         | 0.05%   |
| Mellanox Technologies            | 1         | 0.05%   |
| Insyde Software                  | 1         | 0.05%   |
| IBM                              | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Accton Technology                | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 742       | 37.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 170       | 8.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 104       | 5.25%   |
| Intel Ethernet Connection I217-LM                                      | 42        | 2.12%   |
| Intel I211 Gigabit Network Connection                                  | 26        | 1.31%   |
| Intel 82579V Gigabit Network Connection                                | 25        | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 24        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 24        | 1.21%   |
| Nvidia MCP61 Ethernet                                                  | 22        | 1.11%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 22        | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 21        | 1.06%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 0.96%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 16        | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 15        | 0.76%   |
| Intel Ethernet Connection I219-LM                                      | 14        | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 14        | 0.71%   |
| Intel 82574L Gigabit Network Connection                                | 14        | 0.71%   |
| Intel 82567LM Gigabit Network Connection                               | 14        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                   | 13        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 12        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 11        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 11        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 11        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 10        | 0.5%    |
| Nvidia MCP77 Ethernet                                                  | 10        | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 10        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 10        | 0.5%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 9         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 9         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 9         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 9         | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                   | 9         | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 9         | 0.45%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 8         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 8         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1840      | 56.1%   |
| WiFi     | 1414      | 43.11%  |
| Modem    | 24        | 0.73%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1110      | 53.26%  |
| Ethernet | 974       | 46.74%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1089      | 53.83%  |
| 1     | 824       | 40.73%  |
| 0     | 62        | 3.06%   |
| 3     | 33        | 1.63%   |
| 4     | 12        | 0.59%   |
| 5     | 2         | 0.1%    |
| 10    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1701      | 82.94%  |
| Yes  | 350       | 17.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 366       | 40.26%  |
| Qualcomm Atheros Communications | 90        | 9.9%    |
| Realtek Semiconductor           | 86        | 9.46%   |
| Broadcom                        | 82        | 9.02%   |
| Cambridge Silicon Radio         | 60        | 6.6%    |
| Apple                           | 36        | 3.96%   |
| IMC Networks                    | 31        | 3.41%   |
| Lite-On Technology              | 30        | 3.3%    |
| Dell                            | 26        | 2.86%   |
| Foxconn / Hon Hai               | 20        | 2.2%    |
| Hewlett-Packard                 | 19        | 2.09%   |
| ASUSTek Computer                | 13        | 1.43%   |
| Ralink                          | 12        | 1.32%   |
| Toshiba                         | 9         | 0.99%   |
| Integrated System Solution      | 6         | 0.66%   |
| Alps Electric                   | 4         | 0.44%   |
| TP-Link                         | 3         | 0.33%   |
| Chicony Electronics             | 3         | 0.33%   |
| Realtek                         | 2         | 0.22%   |
| Edimax Technology               | 2         | 0.22%   |
| Taiyo Yuden                     | 1         | 0.11%   |
| Sitecom Europe                  | 1         | 0.11%   |
| Ralink Technology               | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| MediaTek                        | 1         | 0.11%   |
| Fujitsu                         | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |
| Unknown                         | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 149       | 16.37%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 60        | 6.59%   |
| Intel AX201 Bluetooth                               | 53        | 5.82%   |
| Realtek Bluetooth Radio                             | 52        | 5.71%   |
| Intel AX200 Bluetooth                               | 49        | 5.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 40        | 4.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 4.18%   |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 2.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 2.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.76%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 1.76%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 1.43%   |
| Intel Bluetooth Device                              | 13        | 1.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 13        | 1.43%   |
| Apple Bluetooth Host Controller                     | 13        | 1.43%   |
| Ralink RT3290 Bluetooth                             | 12        | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 11        | 1.21%   |
| Lite-On Bluetooth Device                            | 11        | 1.21%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.1%    |
| IMC Networks Bluetooth Device                       | 10        | 1.1%    |
| Realtek RTL8723B Bluetooth                          | 9         | 0.99%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.88%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.88%   |
| Apple Bluetooth HCI                                 | 8         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 7         | 0.77%   |
| IMC Networks Bluetooth Radio                        | 6         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.66%   |
| Dell Wireless 365 Bluetooth                         | 6         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.66%   |
| Broadcom BCM2045 Bluetooth                          | 6         | 0.66%   |
| Intel AX210 Bluetooth                               | 5         | 0.55%   |
| Foxconn / Hon Hai BCM20702A0                        | 5         | 0.55%   |
| Broadcom BCM2070 Bluetooth Device                   | 5         | 0.55%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1457      | 53.51%  |
| AMD                              | 501       | 18.4%   |
| Nvidia                           | 474       | 17.41%  |
| C-Media Electronics              | 46        | 1.69%   |
| Creative Labs                    | 33        | 1.21%   |
| Logitech                         | 21        | 0.77%   |
| VIA Technologies                 | 18        | 0.66%   |
| Texas Instruments                | 16        | 0.59%   |
| GN Netcom                        | 12        | 0.44%   |
| Focusrite-Novation               | 11        | 0.4%    |
| Yamaha                           | 9         | 0.33%   |
| Silicon Integrated Systems [SiS] | 7         | 0.26%   |
| Lenovo                           | 7         | 0.26%   |
| Generalplus Technology           | 6         | 0.22%   |
| Realtek Semiconductor            | 5         | 0.18%   |
| Plantronics                      | 5         | 0.18%   |
| M-Audio                          | 5         | 0.18%   |
| Creative Technology              | 4         | 0.15%   |
| TEAC                             | 3         | 0.11%   |
| Sennheiser Communications        | 3         | 0.11%   |
| JMTek                            | 3         | 0.11%   |
| EGO SYStems                      | 3         | 0.11%   |
| Corsair                          | 3         | 0.11%   |
| BEHRINGER International          | 3         | 0.11%   |
| AKAI Professional M.I.           | 3         | 0.11%   |
| ZOOM                             | 2         | 0.07%   |
| Textech International            | 2         | 0.07%   |
| TerraTec Electronic              | 2         | 0.07%   |
| SAVITECH                         | 2         | 0.07%   |
| Samson Technologies              | 2         | 0.07%   |
| Razer USA                        | 2         | 0.07%   |
| PreSonus Audio Electronics       | 2         | 0.07%   |
| Philips (or NXP)                 | 2         | 0.07%   |
| KORG                             | 2         | 0.07%   |
| Kingston Technology              | 2         | 0.07%   |
| ESI Audiotechnik                 | 2         | 0.07%   |
| DSEA A/S                         | 2         | 0.07%   |
| Dell                             | 2         | 0.07%   |
| Cambridge Silicon Radio          | 2         | 0.07%   |
| Blue Microphones                 | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 171       | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 166       | 5.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 107       | 3.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 105       | 3.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 102       | 3.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 101       | 3.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 98        | 3.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 95        | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 91        | 2.87%   |
| AMD FCH Azalia Controller                                                                         | 89        | 2.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 88        | 2.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 70        | 2.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 57        | 1.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 52        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 47        | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 47        | 1.48%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 44        | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 43        | 1.35%   |
| Intel 8 Series HD Audio Controller                                                                | 43        | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 42        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 39        | 1.23%   |
| Nvidia High Definition Audio Controller                                                           | 38        | 1.2%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 37        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 35        | 1.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 33        | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 33        | 1.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 32        | 1.01%   |
| Intel 200 Series PCH HD Audio                                                                     | 31        | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 30        | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 25        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 25        | 0.79%   |
| Intel Broadwell-U Audio Controller                                                                | 25        | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 25        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 25        | 0.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 0.76%   |
| Nvidia MCP61 High Definition Audio                                                                | 23        | 0.72%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.72%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 23        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 234       | 20.93%  |
| SK hynix                                         | 195       | 17.44%  |
| Unknown                                          | 171       | 15.3%   |
| Kingston                                         | 136       | 12.16%  |
| Micron Technology                                | 93        | 8.32%   |
| Crucial                                          | 66        | 5.9%    |
| Corsair                                          | 42        | 3.76%   |
| G.Skill                                          | 27        | 2.42%   |
| Elpida                                           | 27        | 2.42%   |
| Ramaxel Technology                               | 20        | 1.79%   |
| Nanya Technology                                 | 13        | 1.16%   |
| A-DATA Technology                                | 13        | 1.16%   |
| Smart                                            | 9         | 0.81%   |
| Unknown (ABCD)                                   | 8         | 0.72%   |
| Patriot                                          | 8         | 0.72%   |
| Transcend                                        | 7         | 0.63%   |
| Team                                             | 6         | 0.54%   |
| GOODRAM                                          | 6         | 0.54%   |
| Unifosa                                          | 3         | 0.27%   |
| GeIL                                             | 3         | 0.27%   |
| Apacer                                           | 3         | 0.27%   |
| Timetec                                          | 2         | 0.18%   |
| Teikon                                           | 2         | 0.18%   |
| CSX                                              | 2         | 0.18%   |
| Avant                                            | 2         | 0.18%   |
| Unknown                                          | 2         | 0.18%   |
| Walton Chaintech                                 | 1         | 0.09%   |
| V-GeN                                            | 1         | 0.09%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.09%   |
| Unknown (0x053E)                                 | 1         | 0.09%   |
| Unknown (0x0043415455000000)                     | 1         | 0.09%   |
| Toshiba                                          | 1         | 0.09%   |
| Smart Brazil                                     | 1         | 0.09%   |
| SHARETRONIC                                      | 1         | 0.09%   |
| Sesame                                           | 1         | 0.09%   |
| Qimonda                                          | 1         | 0.09%   |
| Positivo                                         | 1         | 0.09%   |
| PNY                                              | 1         | 0.09%   |
| OCZ                                              | 1         | 0.09%   |
| Memox                                            | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s               | 15        | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 10        | 0.82%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 9         | 0.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 9         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 9         | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 8         | 0.66%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 8         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 8         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 8         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 7         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 7         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 7         | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 7         | 0.57%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 6         | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 6         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 6         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 6         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 6         | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 6         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 6         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 6         | 0.49%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 0.49%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 6         | 0.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 6         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 5         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                         | 5         | 0.41%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 5         | 0.41%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 5         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 5         | 0.41%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 5         | 0.41%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 5         | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.41%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 5         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 5         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 4         | 0.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 4         | 0.33%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                | 4         | 0.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 4         | 0.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 4         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 402       | 40.57%  |
| DDR4    | 366       | 36.93%  |
| DDR2    | 88        | 8.88%   |
| SDRAM   | 50        | 5.05%   |
| Unknown | 33        | 3.33%   |
| LPDDR4  | 21        | 2.12%   |
| LPDDR3  | 17        | 1.72%   |
| DDR     | 10        | 1.01%   |
| DRAM    | 3         | 0.3%    |
| EEPROM  | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 547       | 56.28%  |
| DIMM         | 385       | 39.61%  |
| Row Of Chips | 33        | 3.4%    |
| Chip         | 5         | 0.51%   |
| FB-DIMM      | 1         | 0.1%    |
| Unknown      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 330       | 30.56%  |
| 8192  | 324       | 30%     |
| 2048  | 205       | 18.98%  |
| 16384 | 137       | 12.69%  |
| 1024  | 58        | 5.37%   |
| 32768 | 19        | 1.76%   |
| 512   | 5         | 0.46%   |
| 1536  | 1         | 0.09%   |
| 1     | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 233       | 21.98%  |
| 2667    | 157       | 14.81%  |
| 1333    | 100       | 9.43%   |
| 3200    | 98        | 9.25%   |
| 2400    | 70        | 6.6%    |
| 667     | 47        | 4.43%   |
| 1334    | 40        | 3.77%   |
| 800     | 40        | 3.77%   |
| Unknown | 39        | 3.68%   |
| 2133    | 34        | 3.21%   |
| 1866    | 17        | 1.6%    |
| 1066    | 17        | 1.6%    |
| 1867    | 15        | 1.42%   |
| 3600    | 14        | 1.32%   |
| 1067    | 14        | 1.32%   |
| 1800    | 13        | 1.23%   |
| 4199    | 12        | 1.13%   |
| 3266    | 12        | 1.13%   |
| 2666    | 9         | 0.85%   |
| 3000    | 8         | 0.75%   |
| 4267    | 7         | 0.66%   |
| 533     | 7         | 0.66%   |
| 3800    | 6         | 0.57%   |
| 2048    | 6         | 0.57%   |
| 2733    | 4         | 0.38%   |
| 400     | 4         | 0.38%   |
| 3733    | 3         | 0.28%   |
| 975     | 3         | 0.28%   |
| 49926   | 2         | 0.19%   |
| 8400    | 2         | 0.19%   |
| 2933    | 2         | 0.19%   |
| 2448    | 2         | 0.19%   |
| 2200    | 2         | 0.19%   |
| 2000    | 2         | 0.19%   |
| 1639    | 2         | 0.19%   |
| 4333    | 1         | 0.09%   |
| 4000    | 1         | 0.09%   |
| 3866    | 1         | 0.09%   |
| 3666    | 1         | 0.09%   |
| 3533    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 33        | 39.29%  |
| Brother Industries    | 18        | 21.43%  |
| Canon                 | 14        | 16.67%  |
| Samsung Electronics   | 5         | 5.95%   |
| Zebra                 | 4         | 4.76%   |
| Seiko Epson           | 3         | 3.57%   |
| STMicroelectronics    | 1         | 1.19%   |
| QinHeng Electronics   | 1         | 1.19%   |
| Prolific Technology   | 1         | 1.19%   |
| Pantum                | 1         | 1.19%   |
| Lexmark International | 1         | 1.19%   |
| Kyocera               | 1         | 1.19%   |
| Dymo-CoStar           | 1         | 1.19%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 400 M401dn                                                | 4         | 4.76%   |
| Zebra ZP 450 Printer                                                  | 3         | 3.57%   |
| HP LaserJet P1005                                                     | 3         | 3.57%   |
| Brother HL-5370DW series                                              | 3         | 3.57%   |
| Seiko Epson L360 Series                                               | 2         | 2.38%   |
| HP OfficeJet Pro 7730 series                                          | 2         | 2.38%   |
| HP LaserJet 1320                                                      | 2         | 2.38%   |
| HP ENVY 4520 series                                                   | 2         | 2.38%   |
| HP DeskJet 3700 series                                                | 2         | 2.38%   |
| Brother HL-L2320D series                                              | 2         | 2.38%   |
| Brother HL-5340 series                                                | 2         | 2.38%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 1.19%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 1.19%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 1.19%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 1.19%   |
| Samsung SCX-4200 series                                               | 1         | 1.19%   |
| Samsung ML-2525W Series                                               | 1         | 1.19%   |
| Samsung M2070 Series                                                  | 1         | 1.19%   |
| Samsung M2020 Series                                                  | 1         | 1.19%   |
| QinHeng CH340S                                                        | 1         | 1.19%   |
| Prolific PL2305 Parallel Port                                         | 1         | 1.19%   |
| Pantum P2000                                                          | 1         | 1.19%   |
| Lexmark International E360d                                           | 1         | 1.19%   |
| Kyocera Mita FS-920                                                   | 1         | 1.19%   |
| HP OfficeJet Pro 9010 series                                          | 1         | 1.19%   |
| HP Officejet Pro 6230                                                 | 1         | 1.19%   |
| HP LaserJet P2055 series                                              | 1         | 1.19%   |
| HP LaserJet P2015 series                                              | 1         | 1.19%   |
| HP LaserJet P1006                                                     | 1         | 1.19%   |
| HP LaserJet CP 1025nw                                                 | 1         | 1.19%   |
| HP LaserJet 1020                                                      | 1         | 1.19%   |
| HP LaserJet 1018                                                      | 1         | 1.19%   |
| HP LaserJet 1015                                                      | 1         | 1.19%   |
| HP HP LaserJet M14-M17                                                | 1         | 1.19%   |
| HP ENVY 6400 series                                                   | 1         | 1.19%   |
| HP Deskjet F4400 series                                               | 1         | 1.19%   |
| HP DeskJet F300 series                                                | 1         | 1.19%   |
| HP DeskJet F2100 Printer series                                       | 1         | 1.19%   |
| HP DeskJet 5850c                                                      | 1         | 1.19%   |
| HP DeskJet 3630 series                                                | 1         | 1.19%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 65%     |
| Seiko Epson     | 4         | 20%     |
| Hewlett-Packard | 3         | 15%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 15%     |
| Canon CanoScan LiDE 110                                     | 2         | 10%     |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5%      |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 5%      |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5%      |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 5%      |
| HP ScanJet 82x0C                                            | 1         | 5%      |
| HP ScanJet 5590                                             | 1         | 5%      |
| HP ScanJet 3570c                                            | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 5%      |
| Canon CanoScan LiDE 90                                      | 1         | 5%      |
| Canon CanoScan LIDE 25                                      | 1         | 5%      |
| Canon CanoScan LiDE 220                                     | 1         | 5%      |
| Canon CanoScan LiDE 210                                     | 1         | 5%      |
| Canon CanoScan LiDE 200                                     | 1         | 5%      |
| Canon CanoScan LiDE 120                                     | 1         | 5%      |
| Canon CanoScan LiDE 100                                     | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 264       | 24.58%  |
| Microdia                               | 80        | 7.45%   |
| Realtek Semiconductor                  | 73        | 6.8%    |
| IMC Networks                           | 68        | 6.33%   |
| Logitech                               | 61        | 5.68%   |
| Sunplus Innovation Technology          | 56        | 5.21%   |
| Suyin                                  | 50        | 4.66%   |
| Bison Electronics                      | 48        | 4.47%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 3.35%   |
| Quanta                                 | 33        | 3.07%   |
| Apple                                  | 33        | 3.07%   |
| Lite-On Technology                     | 26        | 2.42%   |
| Syntek                                 | 24        | 2.23%   |
| Acer                                   | 22        | 2.05%   |
| Alcor Micro                            | 21        | 1.96%   |
| Silicon Motion                         | 20        | 1.86%   |
| Ricoh                                  | 19        | 1.77%   |
| Samsung Electronics                    | 12        | 1.12%   |
| Microsoft                              | 12        | 1.12%   |
| Lenovo                                 | 8         | 0.74%   |
| Z-Star Microelectronics                | 7         | 0.65%   |
| Luxvisions Innotech Limited            | 7         | 0.65%   |
| Importek                               | 6         | 0.56%   |
| Generalplus Technology                 | 6         | 0.56%   |
| ALi                                    | 6         | 0.56%   |
| MacroSilicon                           | 5         | 0.47%   |
| Jieli Technology                       | 5         | 0.47%   |
| GEMBIRD                                | 5         | 0.47%   |
| OmniVision Technologies                | 4         | 0.37%   |
| DigiTech                               | 4         | 0.37%   |
| Cubeternet                             | 4         | 0.37%   |
| ARC International                      | 4         | 0.37%   |
| Trust                                  | 3         | 0.28%   |
| Sunplus Technology                     | 3         | 0.28%   |
| Primax Electronics                     | 3         | 0.28%   |
| Creative Technology                    | 3         | 0.28%   |
| webcamvendor                           | 2         | 0.19%   |
| USB Camera                             | 2         | 0.19%   |
| Razer USA                              | 2         | 0.19%   |
| Linux Foundation                       | 2         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 40        | 3.71%   |
| Realtek Integrated_Webcam_HD                                   | 22        | 2.04%   |
| Chicony USB 2.0 Camera                                         | 18        | 1.67%   |
| Microdia Integrated_Webcam_HD                                  | 17        | 1.58%   |
| Logitech Webcam C270                                           | 16        | 1.48%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 1.39%   |
| IMC Networks Integrated Camera                                 | 13        | 1.2%    |
| Chicony HP Truevision HD                                       | 13        | 1.2%    |
| Alcor Micro USB 2.0 Camera                                     | 13        | 1.2%    |
| Sunplus Integrated_Webcam_HD                                   | 12        | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 12        | 1.11%   |
| Chicony TOSHIBA Web Camera - HD                                | 12        | 1.11%   |
| Chicony HD WebCam                                              | 12        | 1.11%   |
| Logitech HD Pro Webcam C920                                    | 11        | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 11        | 1.02%   |
| Bison Lenovo EasyCamera                                        | 11        | 1.02%   |
| Microdia Integrated Webcam                                     | 10        | 0.93%   |
| Lite-On Integrated Camera                                      | 10        | 0.93%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 10        | 0.93%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 10        | 0.93%   |
| Apple Built-in iSight                                          | 10        | 0.93%   |
| Syntek Lenovo EasyCamera                                       | 9         | 0.83%   |
| Syntek Integrated Camera                                       | 9         | 0.83%   |
| Lite-On HP HD Camera                                           | 9         | 0.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 9         | 0.83%   |
| Suyin HP TrueVision HD                                         | 8         | 0.74%   |
| Realtek USB Camera                                             | 8         | 0.74%   |
| Chicony Lenovo EasyCamera                                      | 8         | 0.74%   |
| Quanta HP TrueVision HD Camera                                 | 7         | 0.65%   |
| IMC Networks UVC VGA Webcam                                    | 7         | 0.65%   |
| Chicony USB2.0 Camera                                          | 7         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)                        | 7         | 0.65%   |
| Bison Integrated Camera                                        | 7         | 0.65%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 6         | 0.56%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 6         | 0.56%   |
| Chicony HP HD Webcam                                           | 6         | 0.56%   |
| Chicony FJ Camera                                              | 6         | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 6         | 0.56%   |
| Apple FaceTime HD Camera (Built-in)                            | 6         | 0.56%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 5         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 78        | 40.41%  |
| Synaptics                  | 41        | 21.24%  |
| AuthenTec                  | 29        | 15.03%  |
| Upek                       | 14        | 7.25%   |
| Shenzhen Goodix Technology | 9         | 4.66%   |
| LighTuning Technology      | 9         | 4.66%   |
| STMicroelectronics         | 8         | 4.15%   |
| Elan Microelectronics      | 4         | 2.07%   |
| Samsung Electronics        | 1         | 0.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 9.84%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 8.81%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 6.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 5.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 4.66%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 4.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 4.66%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 4.15%   |
| AuthenTec AES2810                                                          | 8         | 4.15%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 3.63%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 3.63%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 3.63%   |
| Validity Sensors VFS491                                                    | 6         | 3.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.11%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 3.11%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.07%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.07%   |
| AuthenTec AES1600                                                          | 4         | 2.07%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.55%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.04%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.04%   |
| Synaptics WBDI                                                             | 2         | 1.04%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.04%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.04%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.04%   |
| Unknown                                                                    | 2         | 1.04%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.52%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.52%   |
| Synaptics WBDI Device                                                      | 1         | 0.52%   |
| Synaptics UWP WBDI                                                         | 1         | 0.52%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.52%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.52%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 41        | 37.27%  |
| Alcor Micro               | 27        | 24.55%  |
| O2 Micro                  | 15        | 13.64%  |
| Upek                      | 9         | 8.18%   |
| Lenovo                    | 9         | 8.18%   |
| OmniKey                   | 3         | 2.73%   |
| Yubico.com                | 1         | 0.91%   |
| Reiner SCT Kartensysteme  | 1         | 0.91%   |
| Gemalto (was Gemplus)     | 1         | 0.91%   |
| Fujitsu Siemens Computers | 1         | 0.91%   |
| Cherry                    | 1         | 0.91%   |
| C3PO                      | 1         | 0.91%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 24.55%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 14.55%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 12.73%  |
| Broadcom 5880                                                                | 12        | 10.91%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 8.18%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 7.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.36%   |
| Broadcom 58200                                                               | 6         | 5.45%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.82%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.91%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.91%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.91%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.91%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.91%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.91%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.91%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.91%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1506      | 73.72%  |
| 1     | 429       | 21%     |
| 2     | 85        | 4.16%   |
| 3     | 11        | 0.54%   |
| 4     | 6         | 0.29%   |
| 5     | 3         | 0.15%   |
| 6     | 2         | 0.1%    |
| 10    | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 193       | 29.69%  |
| Graphics card            | 140       | 21.54%  |
| Chipcard                 | 104       | 16%     |
| Net/wireless             | 70        | 10.77%  |
| Communication controller | 24        | 3.69%   |
| Unassigned class         | 18        | 2.77%   |
| Camera                   | 16        | 2.46%   |
| Bluetooth                | 15        | 2.31%   |
| Sound                    | 14        | 2.15%   |
| Multimedia controller    | 12        | 1.85%   |
| Card reader              | 12        | 1.85%   |
| Storage                  | 11        | 1.69%   |
| Net/ethernet             | 5         | 0.77%   |
| Flash memory             | 5         | 0.77%   |
| Network                  | 3         | 0.46%   |
| Modem                    | 3         | 0.46%   |
| Storage/ide              | 2         | 0.31%   |
| Storage/raid             | 1         | 0.15%   |
| Storage/nvme             | 1         | 0.15%   |
| Dvb card                 | 1         | 0.15%   |

