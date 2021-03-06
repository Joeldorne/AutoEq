# Dunu DN900

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -2.6; 23 -2.4; 25 -2.2; 28 -1.9; 31 -1.7; 34 -1.5; 37 -1.3; 41 -1.1; 45 -0.9; 49 -0.8; 54 -0.7; 60 -0.6; 66 -0.6; 72 -0.7; 79 -0.8; 87 -1.0; 96 -1.2; 106 -1.3; 116 -1.3; 128 -1.5; 141 -1.7; 155 -1.8; 170 -1.8; 187 -1.8; 206 -1.9; 227 -1.7; 249 -1.7; 274 -1.6; 302 -1.6; 332 -1.4; 365 -1.3; 402 -1.1; 442 -0.9; 486 -0.9; 535 -0.7; 588 -0.2; 647 -0.2; 712 -0.1; 783 0.0; 861 -0.2; 947 -0.1; 1042 -0.1; 1146 -0.4; 1261 -0.8; 1387 -1.3; 1526 -1.8; 1678 -1.9; 1846 -1.4; 2031 -0.3; 2234 1.0; 2457 3.2; 2703 5.2; 2973 6.0; 3270 6.0; 3597 6.0; 3957 6.0; 4353 6.0; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Dunu DN900 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.2dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 21 Hz   | 0.91 | -2.5 dB |
| Peaking | 152 Hz  | 0.85 | -1.3 dB |
| Peaking | 299 Hz  | 0.97 | -1.1 dB |
| Peaking | 1732 Hz | 1.87 | -4.3 dB |
| Peaking | 3742 Hz | 0.86 | 7.2 dB  |
| Peaking | 2238 Hz | 5.46 | -0.8 dB |
| Peaking | 2775 Hz | 3.58 | 1.5 dB  |
| Peaking | 3749 Hz | 2.87 | -1.2 dB |
| Peaking | 6261 Hz | 2.44 | 5.2 dB  |
| Peaking | 7411 Hz | 1.51 | -4.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Dunu%20DN900/Dunu%20DN900.png)