# Beats Powerbeats2 Bluetooth

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 -0.6; 23 -0.7; 25 -0.8; 28 -0.9; 31 -1.0; 34 -1.1; 37 -1.2; 41 -1.4; 45 -1.5; 49 -1.6; 54 -1.7; 60 -1.9; 66 -2.0; 72 -2.3; 79 -2.5; 87 -2.9; 96 -3.2; 106 -3.5; 116 -3.6; 128 -3.9; 141 -4.2; 155 -4.4; 170 -4.3; 187 -4.4; 206 -4.5; 227 -4.3; 249 -4.3; 274 -4.1; 302 -4.0; 332 -3.8; 365 -3.6; 402 -3.3; 442 -2.9; 486 -2.8; 535 -2.3; 588 -1.7; 647 -1.3; 712 -1.0; 783 -0.4; 861 -0.2; 947 -0.0; 1042 -0.0; 1146 0.2; 1261 0.4; 1387 0.3; 1526 0.3; 1678 0.3; 1846 0.7; 2031 1.3; 2234 2.2; 2457 3.7; 2703 5.2; 2973 6.0; 3270 6.0; 3597 6.0; 3957 6.0; 4353 4.8; 4788 3.3; 5267 3.3; 5793 3.3; 6373 2.2; 7010 0.4; 7711 -1.5; 8482 -2.5; 9330 -1.7; 10263 -0.1; 11289 0.0; 12418 0.0; 13660 -0.2; 15026 -3.0; 16529 -3.9; 18182 -3.3; 20000 -4.0
```

### HeSuVi
In case of using HeSuVi, replace `C:\Program Files\EqualizerAPO\config\HeSuVi\eq.txt` and omit `Preamp:
-6.1dB` and instead set Global volume in the UI for both channels to **-60**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Beats Powerbeats2 Bluetooth ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.8dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of -6.8dB.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 77 Hz    | 0.33 | -1.1 dB |
| Peaking | 161 Hz   | 0.73 | -2.9 dB |
| Peaking | 357 Hz   | 0.91 | -2.3 dB |
| Peaking | 3493 Hz  | 1.33 | 6.8 dB  |
| Peaking | 18864 Hz | 0.54 | -3.8 dB |
| Peaking | 1864 Hz  | 3.09 | -0.9 dB |
| Peaking | 2709 Hz  | 6.82 | 1.2 dB  |
| Peaking | 5979 Hz  | 4.45 | 1.8 dB  |
| Peaking | 8358 Hz  | 3.36 | -3.1 dB |
| Peaking | 12274 Hz | 2.56 | 1.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Beats%20Powerbeats2%20Bluetooth/Beats%20Powerbeats2%20Bluetooth.png)