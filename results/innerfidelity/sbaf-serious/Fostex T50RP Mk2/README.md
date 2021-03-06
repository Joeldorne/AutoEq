# Fostex T50RP Mk2

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 5.8; 31 5.2; 34 4.6; 37 4.2; 41 3.8; 45 3.5; 49 3.3; 54 3.2; 60 3.1; 66 3.0; 72 2.8; 79 2.7; 87 2.5; 96 2.3; 106 2.1; 116 1.8; 128 1.1; 141 0.7; 155 0.6; 170 0.8; 187 0.3; 206 0.2; 227 0.3; 249 0.4; 274 0.5; 302 0.6; 332 0.8; 365 1.0; 402 1.0; 442 1.1; 486 0.8; 535 0.8; 588 0.2; 647 0.9; 712 3.2; 783 2.5; 861 1.6; 947 0.6; 1042 -0.7; 1146 -1.5; 1261 -1.5; 1387 -1.1; 1526 -0.6; 1678 -1.2; 1846 -0.0; 2031 3.0; 2234 5.2; 2457 6.0; 2703 6.0; 2973 6.0; 3270 6.0; 3597 6.0; 3957 6.0; 4353 6.0; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Fostex T50RP Mk2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 23 Hz   | 0.76 | 5.9 dB  |
| Peaking | 78 Hz   | 0.98 | 1.8 dB  |
| Peaking | 752 Hz  | 3.7  | 3.1 dB  |
| Peaking | 1493 Hz | 1.3  | -5.2 dB |
| Peaking | 3112 Hz | 0.66 | 7.7 dB  |
| Peaking | 1828 Hz | 5.3  | -2.9 dB |
| Peaking | 2140 Hz | 1.86 | 2.3 dB  |
| Peaking | 3159 Hz | 2.01 | -1.5 dB |
| Peaking | 6239 Hz | 2.06 | 5.8 dB  |
| Peaking | 7399 Hz | 1.43 | -4.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Fostex%20T50RP%20Mk2/Fostex%20T50RP%20Mk2.png)