# Koss KDE250

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 6.0; 79 6.0; 87 6.0; 96 6.0; 106 6.0; 116 6.0; 128 6.0; 141 6.0; 155 5.6; 170 4.9; 187 4.3; 206 3.8; 227 3.2; 249 2.5; 274 2.0; 302 1.7; 332 1.4; 365 1.2; 402 1.4; 442 1.2; 486 1.5; 535 1.5; 588 1.5; 647 1.5; 712 1.4; 783 1.3; 861 1.0; 947 0.5; 1042 -0.2; 1146 -0.8; 1261 -1.8; 1387 -3.4; 1526 -5.6; 1678 -7.4; 1846 -8.8; 2031 -11.1; 2234 -14.4; 2457 -16.1; 2703 -14.2; 2973 -12.3; 3270 -7.1; 3597 -1.4; 3957 1.7; 4353 5.6; 4788 5.3; 5267 2.7; 5793 2.7; 6373 0.9; 7010 -3.8; 7711 -7.8; 8482 -8.3; 9330 -6.3; 10263 -5.0; 11289 -5.5; 12418 -5.5; 13660 -1.7; 15026 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss KDE250 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 53 Hz    | 0.23 | 6.5 dB   |
| Peaking | 983 Hz   | 0.96 | 4.8 dB   |
| Peaking | 2564 Hz  | 1.03 | -23.3 dB |
| Peaking | 4564 Hz  | 1.06 | 17.4 dB  |
| Peaking | 8564 Hz  | 1.24 | -10.2 dB |
| Peaking | 18 Hz    | 1.87 | 1.2 dB   |
| Peaking | 9898 Hz  | 5.66 | 2.2 dB   |
| Peaking | 12534 Hz | 2.59 | -4.3 dB  |
| Peaking | 14226 Hz | 2.01 | 3.0 dB   |
| Peaking | 23800 Hz | 3.03 | -0.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/headphonecom/sbaf-serious/Koss%20KDE250/Koss%20KDE250.png)