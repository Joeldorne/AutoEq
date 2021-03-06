# Beyerdynamic DT 770 600 Ohm

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.2dB
GraphicEQ: 21 -1.3; 23 -1.8; 25 -2.3; 28 -2.9; 31 -3.4; 34 -3.8; 37 -4.0; 41 -4.3; 45 -4.5; 49 -4.5; 54 -4.3; 60 -3.5; 66 -1.8; 72 0.5; 79 0.8; 87 -2.3; 96 -5.1; 106 -5.9; 116 -5.9; 128 -5.4; 141 -4.5; 155 -2.6; 170 -2.3; 187 -1.2; 206 -0.5; 227 -0.4; 249 -1.0; 274 -1.4; 302 -1.8; 332 -1.9; 365 -2.0; 402 -2.0; 442 -1.7; 486 -1.7; 535 -1.5; 588 -0.9; 647 -0.6; 712 -0.5; 783 -0.1; 861 -0.2; 947 -0.1; 1042 0.1; 1146 0.2; 1261 -0.1; 1387 -0.7; 1526 -1.1; 1678 -1.6; 1846 -1.9; 2031 -1.3; 2234 -1.8; 2457 -1.9; 2703 -1.0; 2973 0.7; 3270 2.2; 3597 4.1; 3957 4.4; 4353 4.4; 4788 5.2; 5267 -5.0; 5793 -7.1; 6373 -7.6; 7010 -5.7; 7711 -7.3; 8482 -10.1; 9330 -8.8; 10263 -3.2; 11289 -0.9; 12418 -4.1; 13660 -5.6; 15026 -3.2; 16529 -4.1; 18182 -8.0; 20000 -6.2
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.2dB` and instead set Global volume in the UI for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beyerdynamic DT 770 600 Ohm ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.6dB.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 116 Hz   | 1.36 | -5.6 dB  |
| Peaking | 4602 Hz  | 1.75 | 22.3 dB  |
| Peaking | 5442 Hz  | 1.08 | -19.8 dB |
| Peaking | 8743 Hz  | 5.82 | -6.6 dB  |
| Peaking | 18898 Hz | 1.2  | -8.1 dB  |
| Peaking | 42 Hz    | 1.09 | -4.4 dB  |
| Peaking | 77 Hz    | 4.74 | 5.5 dB   |
| Peaking | 415 Hz   | 2.18 | -1.8 dB  |
| Peaking | 3583 Hz  | 7.78 | 2.8 dB   |
| Peaking | 13465 Hz | 8.36 | -3.0 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beyerdynamic%20DT%20770%20600%20Ohm/Beyerdynamic%20DT%20770%20600%20Ohm.png)