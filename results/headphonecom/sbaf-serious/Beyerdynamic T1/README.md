# Beyerdynamic T1

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.6dB
GraphicEQ: 21 0.0; 23 2.8; 25 2.4; 28 1.9; 31 1.5; 34 1.2; 37 0.9; 41 0.6; 45 0.3; 49 -0.0; 54 -0.2; 60 -0.3; 66 0.3; 72 -0.4; 79 -1.3; 87 -2.0; 96 -2.3; 106 -2.7; 116 -2.9; 128 -3.1; 141 -3.5; 155 -3.7; 170 -3.6; 187 -3.7; 206 -3.7; 227 -3.8; 249 -3.9; 274 -3.6; 302 -3.5; 332 -3.4; 365 -3.0; 402 -2.8; 442 -2.7; 486 -2.4; 535 -1.8; 588 -1.8; 647 -1.4; 712 -0.9; 783 -0.5; 861 -0.4; 947 -0.2; 1042 0.2; 1146 0.7; 1261 1.3; 1387 1.3; 1526 0.3; 1678 -1.2; 1846 -1.8; 2031 -1.9; 2234 -0.4; 2457 0.4; 2703 0.3; 2973 -0.7; 3270 0.2; 3597 0.5; 3957 -0.4; 4353 -0.2; 4788 1.9; 5267 1.4; 5793 0.8; 6373 3.0; 7010 1.3; 7711 -3.7; 8482 -8.7; 9330 -8.2; 10263 -1.9; 11289 0.0; 12418 0.0; 13660 -1.5; 15026 -1.6; 16529 -0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-3.6dB` and instead set Global volume in the UI for both channels to **-35**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic T1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -3.5dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 12 Hz    | 0.53 | 4.8 dB   |
| Peaking | 208 Hz   | 0.55 | -4.1 dB  |
| Peaking | 1942 Hz  | 7.41 | -2.2 dB  |
| Peaking | 6636 Hz  | 2.23 | 4.3 dB   |
| Peaking | 8689 Hz  | 3.61 | -11.5 dB |
| Peaking | 1281 Hz  | 4.02 | 1.9 dB   |
| Peaking | 11620 Hz | 2.61 | 3.2 dB   |
| Peaking | 14167 Hz | 0.98 | -2.7 dB  |
| Peaking | 16930 Hz | 1.62 | 1.6 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Beyerdynamic%20T1/Beyerdynamic%20T1.png)