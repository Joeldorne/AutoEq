# Sennheiser HD 598

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 5.8; 31 5.2; 34 4.4; 37 3.8; 41 3.0; 45 2.4; 49 1.9; 54 1.3; 60 0.8; 66 0.7; 72 0.2; 79 -0.5; 87 -1.0; 96 -2.1; 106 -2.6; 116 -3.0; 128 -3.5; 141 -3.8; 155 -3.9; 170 -3.8; 187 -3.8; 206 -3.8; 227 -3.6; 249 -3.5; 274 -3.3; 302 -3.2; 332 -2.9; 365 -2.6; 402 -2.4; 442 -1.9; 486 -2.0; 535 -1.8; 588 -0.2; 647 -0.7; 712 -0.6; 783 -0.4; 861 -0.4; 947 -0.3; 1042 -0.1; 1146 0.2; 1261 0.4; 1387 0.7; 1526 1.2; 1678 2.1; 1846 2.4; 2031 1.4; 2234 0.5; 2457 0.2; 2703 -0.1; 2973 0.5; 3270 -0.7; 3597 -0.9; 3957 -0.9; 4353 -3.3; 4788 -3.4; 5267 -1.3; 5793 0.6; 6373 1.3; 7010 1.6; 7711 0.3; 8482 -1.9; 9330 -3.1; 10263 -0.1; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 0.0; 18182 -1.0; 20000 -1.6
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 598 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.3dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.3dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 21 Hz    | 0.54 | 6.4 dB  |
| Peaking | 175 Hz   | 0.54 | -4.4 dB |
| Peaking | 1754 Hz  | 2.82 | 2.6 dB  |
| Peaking | 4546 Hz  | 5.37 | -4.1 dB |
| Peaking | 19500 Hz | 1.99 | -1.8 dB |
| Peaking | 72 Hz    | 4.71 | 0.5 dB  |
| Peaking | 546 Hz   | 4.17 | -0.9 dB |
| Peaking | 604 Hz   | 7.93 | 1.7 dB  |
| Peaking | 6768 Hz  | 4.24 | 2.2 dB  |
| Peaking | 9012 Hz  | 6.43 | -3.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20598/Sennheiser%20HD%20598.png)