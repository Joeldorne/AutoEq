# Focal Elear sn1BEBG004809

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 3.7; 25 3.4; 28 3.0; 31 2.8; 34 2.5; 37 2.4; 41 2.2; 45 2.0; 49 1.8; 54 1.5; 60 1.1; 66 0.7; 72 0.4; 79 0.1; 87 -0.2; 96 -0.6; 106 -0.8; 116 -0.9; 128 -1.2; 141 -1.2; 155 -1.3; 170 -1.3; 187 -1.4; 206 -1.3; 227 -1.2; 249 -1.1; 274 -0.9; 302 -0.9; 332 -0.7; 365 -0.5; 402 -0.4; 442 -0.2; 486 -0.2; 535 -0.1; 588 0.3; 647 0.5; 712 0.4; 783 0.6; 861 0.4; 947 0.1; 1042 -0.0; 1146 -0.5; 1261 -0.7; 1387 -1.0; 1526 -1.6; 1678 -2.4; 1846 -2.2; 2031 -2.3; 2234 -2.0; 2457 -1.9; 2703 -1.5; 2973 -0.3; 3270 0.7; 3597 1.3; 3957 4.7; 4353 5.4; 4788 5.9; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.2; 8482 -2.2; 9330 -1.4; 10263 0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 0.0; 18182 -0.5; 20000 -1.2
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Focal Elear sn1BEBG004809 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.5dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 14 Hz   |  0.35 | 4.2 dB  |
| Peaking | 152 Hz  |  0.83 | -1.7 dB |
| Peaking | 2338 Hz |  1.21 | -3.8 dB |
| Peaking | 5291 Hz |  1.09 | 7.7 dB  |
| Peaking | 8460 Hz |  2.66 | -5.1 dB |
| Peaking | 770 Hz  |  2.08 | 0.9 dB  |
| Peaking | 1658 Hz |  7.65 | -0.9 dB |
| Peaking | 3998 Hz |  3.09 | -1.9 dB |
| Peaking | 4102 Hz |  7.92 | 3.6 dB  |
| Peaking | 6398 Hz | 10.2  | 1.0 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Focal%20Elear%20sn1BEBG004809/Focal%20Elear%20sn1BEBG004809.png)