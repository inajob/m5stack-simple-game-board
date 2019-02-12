# M5Stack Simple Game Board

Proposal of very Simple Game Board

<img src="imgs/photo1.jpg">
<img src="imgs/photo2.jpg">

## Left side

|GPIO No|Button|
|:------|:-----|
|GPIO 3 |Down  |
|GPIO 1 |Left  |
|GPIO 16|Up    |
|GPIO 17|Right |

```
GPIO 3  ---- SW ---- GND
GPIO 1  ---- SW ---- GND
GPIO 16 ---- SW ---- GND
GPIO 17 ---- SW ---- GND
```

## Right Side

|GPIO No|Button  |Memo      |
|:------|:-------|:---------|
|GPIO 35|Button A|10k pullup|
|GPIO 36|Button B|10k pullup|

```
         3.3V
          |
         10kOhm
          |
GPIO 35  -+-- SW ---- GND

         3.3V
          |
         10kOhm
          |
GPIO 36  -+-- SW ---- GND
```
