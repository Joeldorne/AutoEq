# Sennheiser HD 218

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 5.7; 25 5.3; 28 4.5; 31 3.9; 34 3.3; 37 2.8; 41 2.1; 45 1.5; 49 0.9; 54 0.3; 60 -0.4; 66 -1.1; 72 -1.8; 79 -2.4; 87 -3.1; 96 -3.8; 106 -3.8; 116 -3.3; 128 -4.0; 141 -5.4; 155 -6.4; 170 -6.2; 187 -6.4; 206 -6.0; 227 -5.3; 249 -4.2; 274 -3.2; 302 -3.1; 332 -3.4; 365 -2.4; 402 -1.8; 442 -0.5; 486 -0.3; 535 -0.4; 588 0.8; 647 1.1; 712 0.9; 783 0.9; 861 0.4; 947 0.1; 1042 0.0; 1146 0.1; 1261 0.3; 1387 0.7; 1526 1.1; 1678 0.5; 1846 0.4; 2031 1.2; 2234 2.1; 2457 2.9; 2703 3.5; 2973 4.1; 3270 5.1; 3597 6.0; 3957 6.0; 4353 3.9; 4788 -1.5; 5267 0.9; 5793 0.5; 6373 2.2; 7010 2.4; 7711 0.3; 8482 0.0; 9330 0.0; 10263 0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 -0.3; 18182 -2.5; 20000 0.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 218 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.0dB.

| Type    | Fc       |     Q | Gain    |
|:--------|:---------|:------|:--------|
| Peaking | 21 Hz    |  0.81 | 6.0 dB  |
| Peaking | 87 Hz    |  1.78 | -2.4 dB |
| Peaking | 184 Hz   |  1.16 | -6.5 dB |
| Peaking | 3426 Hz  |  1.84 | 6.0 dB  |
| Peaking | 24000 Hz |  2.3  | 0.4 dB  |
| Peaking | 343 Hz   |  6.02 | -1.4 dB |
| Peaking | 663 Hz   |  2.44 | 1.5 dB  |
| Peaking | 4834 Hz  | 12.6  | -4.0 dB |
| Peaking | 6725 Hz  | 10.04 | 2.9 dB  |
| Peaking | 18082 Hz |  3.19 | -2.8 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Sennheiser%20HD%20218/Sennheiser%20HD%20218.png)