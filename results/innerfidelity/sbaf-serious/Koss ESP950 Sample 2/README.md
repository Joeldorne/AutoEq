# Koss ESP950 sample 2

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 5.9; 79 5.9; 87 5.6; 96 4.7; 106 3.7; 116 3.0; 128 2.9; 141 2.8; 155 2.7; 170 2.5; 187 2.2; 206 2.1; 227 2.2; 249 2.1; 274 2.1; 302 2.2; 332 2.1; 365 2.1; 402 1.9; 442 1.8; 486 1.5; 535 1.3; 588 1.5; 647 1.2; 712 1.0; 783 0.9; 861 0.4; 947 0.2; 1042 -0.0; 1146 -0.5; 1261 -1.1; 1387 -1.8; 1526 -1.7; 1678 -0.9; 1846 1.2; 2031 3.1; 2234 4.5; 2457 4.7; 2703 3.1; 2973 2.5; 3270 3.0; 3597 4.5; 3957 5.9; 4353 6.0; 4788 6.0; 5267 6.0; 5793 5.6; 6373 4.5; 7010 2.5; 7711 0.3; 8482 -0.5; 9330 -2.4; 10263 -0.3; 11289 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Koss ESP950 sample 2 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-7.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -7.0dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 39 Hz   | 0.35 | 6.5 dB  |
| Peaking | 419 Hz  | 0.82 | 1.5 dB  |
| Peaking | 1494 Hz | 2.21 | -3.1 dB |
| Peaking | 2262 Hz | 2.76 | 4.6 dB  |
| Peaking | 4756 Hz | 1.67 | 6.7 dB  |
| Peaking | 83 Hz   | 3.47 | 1.1 dB  |
| Peaking | 116 Hz  | 3.2  | -0.9 dB |
| Peaking | 6355 Hz | 5.73 | 2.0 dB  |
| Peaking | 9126 Hz | 3.81 | -3.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Koss%20ESP950%20sample%202/Koss%20ESP950%20sample%202.png)