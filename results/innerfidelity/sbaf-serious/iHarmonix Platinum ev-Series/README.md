# iHarmonix Platinum ev-Series

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.4dB
GraphicEQ: 21 -10.0; 23 -10.0; 25 -10.0; 28 -10.0; 31 -10.0; 34 -10.0; 37 -10.0; 41 -10.0; 45 -10.1; 49 -10.1; 54 -10.2; 60 -10.2; 66 -10.3; 72 -10.4; 79 -10.6; 87 -10.6; 96 -10.7; 106 -10.7; 116 -10.6; 128 -10.5; 141 -10.4; 155 -10.1; 170 -9.8; 187 -9.5; 206 -9.1; 227 -8.6; 249 -8.2; 274 -7.6; 302 -6.9; 332 -6.5; 365 -5.7; 402 -5.2; 442 -4.2; 486 -3.6; 535 -3.1; 588 -2.1; 647 -1.6; 712 -1.2; 783 -0.4; 861 -0.3; 947 -0.2; 1042 -0.3; 1146 -0.6; 1261 -0.7; 1387 -1.1; 1526 -1.5; 1678 -1.8; 1846 -1.9; 2031 -2.0; 2234 -2.2; 2457 -2.1; 2703 -2.0; 2973 0.4; 3270 3.3; 3597 4.3; 3957 2.8; 4353 -1.2; 4788 -5.8; 5267 -6.9; 5793 -0.9; 6373 2.2; 7010 2.3; 7711 0.1; 8482 -2.0; 9330 -0.1; 10263 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.4dB` and instead set Global volume in the UI for both channels to **-44**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `iHarmonix Platinum ev-Series ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-4.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -3.9dB.

| Type    | Fc      |    Q | Gain     |
|:--------|:--------|:-----|:---------|
| Peaking | 30 Hz   | 0.16 | -9.8 dB  |
| Peaking | 198 Hz  | 0.58 | -4.7 dB  |
| Peaking | 2670 Hz | 1.33 | -9.8 dB  |
| Peaking | 3375 Hz | 1.13 | 11.4 dB  |
| Peaking | 4952 Hz | 4.26 | -11.7 dB |
| Peaking | 394 Hz  | 2.55 | -0.7 dB  |
| Peaking | 839 Hz  | 1.87 | 1.1 dB   |
| Peaking | 1615 Hz | 3.58 | -0.9 dB  |
| Peaking | 6643 Hz | 6.64 | 3.2 dB   |
| Peaking | 8424 Hz | 5.38 | -2.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/iHarmonix%20Platinum%20ev-Series/iHarmonix%20Platinum%20ev-Series.png)