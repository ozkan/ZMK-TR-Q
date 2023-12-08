# ZMK Turkish-Q Language-specific Keycodes


> [!WARNING]
> When you use this package, you must select the computer keyboard input language Turkish-Q (Türkçe Q) 

Download [keys_tr.h](keys_tr.h) to the directory where your *.keymap file is located           
<br>

Add the following to your *.keymap 

```c
#include "keys_tr.h"
``` 
<br>

#include <dt-bindings/zmk/keys.h>` into comment line 

```c
//#include <dt-bindings/zmk/keys.h>
```
<br>
<br>

### Turkish-Q Language-specific Keycodes

|        Names            |   Description |   W   |   L   |   A   |   m   |   i   |
|:------------------------|:-------------:|:-----:|:-----:|:-----:|:-----:|:-----:|
|       `TR_C`            |   ç and Ç     |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `TR_O`            |   ö and Ö     |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `TR_U`            |   ü and Ü     |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `TR_G`            |   ğ and Ğ     |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `TR_I`            |   ı and I     |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `TR_I_DOT`        |      İ        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `TR_S`            |   ş and Ş     |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|  `TL` `TURKISH_LIRA`    |      ₺        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|       `EURO`            |      €        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|     `POUND_SIGN`        |      £        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|      `ACUTE`            |      ´        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|        `AE`             |      æ        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|  `ONE_HALF` `FRAC_1_2`  |      ½        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|  `SZ`  `SHARP_S`        |      ß        |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|  `ESCAPE_CHARACTER`     |               |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|  `FILE_SEPARATOR`       |               |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |
|  `GROUP_SEPARATOR`      |               |   ⭐  |   ⭐  |   ⭐  |   ⭐  |   ⭐ |




The rest of the codes are the same as in [https://zmk.dev/docs/codes](https://zmk.dev/docs/codes)

