# KEF M200

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -4.9dB
GraphicEQ: 21 -9.8; 23 -9.8; 25 -9.7; 28 -9.5; 31 -9.3; 34 -9.1; 37 -9.0; 41 -8.8; 45 -8.6; 49 -8.3; 54 -8.1; 60 -7.9; 66 -7.7; 72 -7.6; 79 -7.4; 87 -7.3; 96 -7.2; 106 -6.9; 116 -6.6; 128 -6.4; 141 -6.0; 155 -5.6; 170 -5.3; 187 -4.9; 206 -4.4; 227 -3.8; 249 -3.5; 274 -2.8; 302 -2.4; 332 -1.8; 365 -1.2; 402 -0.7; 442 -0.0; 486 0.1; 535 0.6; 588 1.2; 647 1.3; 712 1.3; 783 1.3; 861 0.9; 947 0.4; 1042 -0.2; 1146 -0.8; 1261 -1.8; 1387 -3.2; 1526 -4.8; 1678 -6.2; 1846 -7.1; 2031 -6.8; 2234 -5.4; 2457 -2.3; 2703 3.3; 2973 3.4; 3270 1.9; 3597 1.5; 3957 1.2; 4353 0.9; 4788 2.2; 5267 4.1; 5793 4.8; 6373 3.2; 7010 0.9; 7711 -2.4; 8482 -5.0; 9330 -3.5; 10263 -0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 -4.1; 16529 -5.5; 18182 -2.6; 20000 -3.8
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-4.9dB` and instead set Global volume in the UI for both channels to **-48**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `KEF M200 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.0dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -2.9dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 18 Hz    | 0.19 | -9.6 dB  |
| Peaking | 157 Hz   | 0.64 | -3.3 dB  |
| Peaking | 1861 Hz  | 1.16 | -17.8 dB |
| Peaking | 2403 Hz  | 0.39 | 11.4 dB  |
| Peaking | 14838 Hz | 0.17 | -3.8 dB  |
| Peaking | 2847 Hz  | 5.32 | 4.0 dB   |
| Peaking | 4611 Hz  | 0.97 | -3.5 dB  |
| Peaking | 5770 Hz  | 2.38 | 6.2 dB   |
| Peaking | 8510 Hz  | 3.8  | -5.7 dB  |
| Peaking | 11645 Hz | 2.09 | 3.1 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/KEF%20M200/KEF%20M200.png)