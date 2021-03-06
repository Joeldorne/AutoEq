# Audio Technica ATH-AD700

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 6.0; 79 5.8; 87 4.9; 96 4.2; 106 3.8; 116 3.4; 128 2.9; 141 2.5; 155 2.3; 170 2.1; 187 1.9; 206 1.7; 227 1.6; 249 1.5; 274 1.6; 302 1.6; 332 1.7; 365 1.6; 402 1.7; 442 1.8; 486 1.6; 535 1.5; 588 1.7; 647 1.6; 712 1.3; 783 1.3; 861 0.7; 947 0.3; 1042 -0.1; 1146 -0.3; 1261 -0.6; 1387 -1.0; 1526 -1.0; 1678 -0.6; 1846 -0.6; 2031 -0.3; 2234 0.3; 2457 1.1; 2703 1.1; 2973 1.3; 3270 0.9; 3597 3.8; 3957 4.3; 4353 0.5; 4788 1.1; 5267 4.9; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0; 9330 -0.5; 10263 -0.5; 11289 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio Technica ATH-AD700 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.9dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 44 Hz   |  0.23 | 6.4 dB  |
| Peaking | 149 Hz  |  1.04 | -1.9 dB |
| Peaking | 554 Hz  |  1.8  | 1.2 dB  |
| Peaking | 3750 Hz |  7.16 | 4.8 dB  |
| Peaking | 5913 Hz |  3.87 | 6.7 dB  |
| Peaking | 1496 Hz |  2.26 | -1.3 dB |
| Peaking | 2637 Hz |  4.62 | 1.2 dB  |
| Peaking | 4558 Hz | 12.78 | -1.8 dB |
| Peaking | 9658 Hz |  4.98 | -1.3 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Audio%20Technica%20ATH-AD700/Audio%20Technica%20ATH-AD700.png)