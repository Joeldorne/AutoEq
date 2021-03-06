# Sony DR-Z7

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 6.0; 79 6.0; 87 6.0; 96 6.0; 106 6.0; 116 5.9; 128 5.1; 141 4.2; 155 4.1; 170 4.3; 187 3.6; 206 3.1; 227 3.1; 249 3.1; 274 3.1; 302 3.1; 332 3.2; 365 3.3; 402 3.3; 442 3.5; 486 3.0; 535 2.8; 588 3.1; 647 2.5; 712 1.7; 783 1.4; 861 0.8; 947 0.3; 1042 -0.2; 1146 -0.8; 1261 -1.5; 1387 -2.8; 1526 -3.9; 1678 -5.3; 1846 -6.1; 2031 -6.1; 2234 -5.2; 2457 -3.0; 2703 -1.0; 2973 1.1; 3270 2.3; 3597 2.6; 3957 2.6; 4353 1.3; 4788 2.0; 5267 5.3; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony DR-Z7 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 45 Hz   | 0.23 | 6.3 dB  |
| Peaking | 527 Hz  | 0.95 | 2.6 dB  |
| Peaking | 1961 Hz | 1.48 | -7.4 dB |
| Peaking | 3300 Hz | 2.2  | 4.2 dB  |
| Peaking | 5825 Hz | 3.35 | 6.7 dB  |
| Peaking | 13 Hz   | 0.87 | 1.0 dB  |
| Peaking | 40 Hz   | 0.99 | -0.6 dB |
| Peaking | 114 Hz  | 2.55 | 1.6 dB  |
| Peaking | 135 Hz  | 2.06 | -1.1 dB |
| Peaking | 8118 Hz | 5.34 | -0.9 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sony%20DR-Z7/Sony%20DR-Z7.png)