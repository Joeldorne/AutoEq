# Sennheiser HD 800 S sample 1

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.9dB
GraphicEQ: 21 0.0; 23 3.9; 25 3.4; 28 2.9; 31 2.4; 34 2.0; 37 1.7; 41 1.4; 45 1.2; 49 1.1; 54 0.8; 60 0.6; 66 0.5; 72 0.3; 79 -0.3; 87 -1.0; 96 -1.7; 106 -2.1; 116 -2.4; 128 -2.7; 141 -3.0; 155 -3.2; 170 -3.1; 187 -3.4; 206 -3.4; 227 -3.4; 249 -3.4; 274 -3.2; 302 -3.2; 332 -3.0; 365 -2.8; 402 -2.6; 442 -2.4; 486 -2.3; 535 -2.1; 588 -1.6; 647 -1.4; 712 -1.3; 783 -0.8; 861 -0.6; 947 -0.3; 1042 0.3; 1146 0.5; 1261 1.1; 1387 1.6; 1526 2.1; 1678 1.9; 1846 1.7; 2031 2.0; 2234 1.9; 2457 2.1; 2703 2.3; 2973 1.9; 3270 1.8; 3597 1.5; 3957 0.7; 4353 0.1; 4788 0.1; 5267 -1.1; 5793 -1.1; 6373 -4.1; 7010 -3.9; 7711 -2.5; 8482 -1.3; 9330 -0.2; 10263 0.0; 11289 0.0; 12418 0.0; 13660 -0.0; 15026 -0.2; 16529 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.9dB` and instead set Global volume in the UI for both channels to **-48**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 800 S sample 1 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-3.8dB** and build filters manually
with these parameters. The first 4 filters can be used independently.
When using independent subset of filters, apply preamp of -3.8dB.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 12 Hz   | 0.26 | 4.2 dB  |
| Peaking | 222 Hz  | 0.38 | -3.7 dB |
| Peaking | 2080 Hz | 0.69 | 2.6 dB  |
| Peaking | 6770 Hz | 3.05 | -4.9 dB |
| Peaking | 40 Hz   | 2.22 | -0.5 dB |
| Peaking | 70 Hz   | 3.69 | 0.9 dB  |
| Peaking | 2142 Hz | 4.45 | -0.4 dB |
| Peaking | 3684 Hz | 2.03 | 0.7 dB  |
| Peaking | 4212 Hz | 3.71 | -1.0 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20800%20S%20sample%201/Sennheiser%20HD%20800%20S%20sample%201.png)