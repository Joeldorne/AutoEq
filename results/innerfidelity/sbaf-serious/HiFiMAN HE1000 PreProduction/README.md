# HiFiMAN HE1000 PreProduction

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -3.9dB
GraphicEQ: 21 0.0; 23 3.1; 25 2.9; 28 2.7; 31 2.6; 34 2.5; 37 2.4; 41 2.3; 45 2.3; 49 2.1; 54 2.0; 60 1.7; 66 1.5; 72 1.4; 79 1.2; 87 0.8; 96 0.5; 106 0.2; 116 0.1; 128 -0.2; 141 -0.4; 155 -0.8; 170 -1.1; 187 -1.0; 206 -0.5; 227 -0.2; 249 -0.6; 274 -1.1; 302 -1.8; 332 -1.6; 365 -0.3; 402 -0.3; 442 0.6; 486 -0.7; 535 -0.4; 588 0.3; 647 -0.1; 712 -0.3; 783 0.3; 861 -0.2; 947 -0.4; 1042 0.9; 1146 0.7; 1261 2.2; 1387 2.0; 1526 2.2; 1678 1.8; 1846 2.8; 2031 3.6; 2234 3.1; 2457 3.6; 2703 3.5; 2973 1.8; 3270 0.8; 3597 1.8; 3957 0.9; 4353 -2.0; 4788 -2.3; 5267 -1.8; 5793 0.3; 6373 -3.4; 7010 -4.2; 7711 -2.9; 8482 -2.8; 9330 -0.9; 10263 0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 0.0; 18182 -0.9; 20000 -6.2
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-3.9dB` and instead set Global volume in the UI for both channels to **-38**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `HiFiMAN HE1000 PreProduction ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -3.8dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 27 Hz   |  0.7  | 3.1 dB  |
| Peaking | 1337 Hz |  5.66 | 1.6 dB  |
| Peaking | 2322 Hz |  1.5  | 3.8 dB  |
| Peaking | 4621 Hz |  6.02 | -2.9 dB |
| Peaking | 7171 Hz |  2.95 | -4.4 dB |
| Peaking | 67 Hz   |  1.97 | 0.6 dB  |
| Peaking | 166 Hz  |  2.43 | -1.2 dB |
| Peaking | 311 Hz  |  4.35 | -1.9 dB |
| Peaking | 915 Hz  |  7.87 | -0.9 dB |
| Peaking | 3736 Hz | 10.52 | 1.2 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/HiFiMAN%20HE1000%20PreProduction/HiFiMAN%20HE1000%20PreProduction.png)