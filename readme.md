# Dell Latitude E7450 i5-5300U/8GB/HD 5500

## Benchmark

![Geekbench4](https://imgur.com/a/SUyco0C)

### Full spec:

* *CPU* : Intel Core i5-5300U (base 1.6GHz, boost 3.6GHz, syntetic load stable 2.4GHz, cinebench 1200pts)

* *RAM* : 8 GB 1600 MHz DDR3

* *GPU* : Intel HD Graphics 5500 2048 MB

* *SSD* : 240GB KINGSTON SA400S37240G

* *WIFI* : TP LINK ARCHER T2U AC600 NANO (Both 2.4ghz and 5ghz working)
  
  ### ⛔️ what is not working:
1. Default Wi-Fi card, need to replace with a compatible one or use dongle.
2. ComboJack only **audio working**, not microphone
* ### Installation
  
  This EFI has been tested on Mac OS 10.15.5.

Make sure to connect **USB keyboard and mouse** as PS2 is **NOT** supported (yet) during instalation.

### Post installation

If you are using an SSD make sure to enable the TRIM support:

```
$ sudo trimforce enable
```

### Credits:

[Clover EFI Bootloader](https://github.com/Clover-EFI-Bootloader/clover)
[Lilu.kext](https://github.com/acidanthera/Lilu/releases)
[VoodooPS2](https://github.com/RehabMan/OS-X-Voodoo-PS2-Controller)
