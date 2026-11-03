# roulette: probe, then sweep

## Pilot

200 trials of the unmodified model. One trial costs 0.297 s of one core, so 3 workers run 10.1 trials a second. 0 invalid. Against the null, p = 0.6073.

## Probe

60 parameters, each at ±3 tolerance widths, 200 trials per case, paired trial by trial with the baseline. **Effect** is the strongest metric's mean change in units of its baseline spread. **Reached** is the share of trials the parameter changed at all.

| Parameter | Delta | Reached | Strongest metric | Effect | Paired z |
|---|---|---|---|---|---|
| material.mu | ±0.06 dimensionless | 100% | leaveSpeed | 100000 | 816 |
| surface.trackMu | ±30 % | 100% | leaveSpeed | 44900 | 1000 |
| bowl.upperTrackDeg | ±0.45 deg | 100% | leaveSpeed | 19600 | 204000 |
| bowl.ovalSin | ±0.45 mm | 100% | leaveSpeed | 17900 | 1.18 |
| bowl.ovalCos | ±0.45 mm | 100% | leaveSpeed | 15900 | 0.805 |
| ball.comOffset | ±0.06 mm | 100% | leaveSpeed | 11000 | 16 |
| ball.outOfRound | ±0.15 % | 100% | leaveSpeed | 7160 | 20.6 |
| bowl.trackR | ±0.9 mm | 100% | leaveSpeed | 1480 | 15400 |
| material.muS | ±0.07 dimensionless | 100% | leaveSpeed | 991 | 36.1 |
| bowl.wallLeanDeg | ±1.5 deg | 100% | leaveSpeed | 819 | 8470 |
| bowl.trefoilCos | ±0.24 mm | 100% | leaveSpeed | 394 | 2.52 |
| table.tiltY | ±0.15 deg | 100% | leaveSpeed | 330 | 1.15 |
| bowl.trefoilSin | ±0.24 mm | 100% | leaveSpeed | 315 | 2.05 |
| material.crr | ±0.004 dimensionless | 100% | leaveSpeed | 245 | 2110 |
| surface.trackCrr | ±45 % | 100% | leaveSpeed | 227 | 2080 |
| bowl.warpCos | ±0.45 mm | 100% | leaveSpeed | 196 | 2.66 |
| bowl.dentDepth | ±0.15 mm | 100% | leaveSpeed | 155 | 2.14 |
| bowl.warpSin | ±0.45 mm | 100% | leaveSpeed | 139 | 1.81 |
| ball.diameter | ±0.09 mm | 100% | leaveSpeed | 81.6 | 842 |
| table.tiltX | ±0.15 deg | 100% | leaveSpeed | 62.4 | 0.218 |
| air.draftY | ±0.15 m/s | 100% | leaveSpeed | 31.8 | 1.68 |
| air.draftX | ±0.15 m/s | 100% | leaveSpeed | 25.2 | 1.36 |
| material.density | ±75 kg/m**3 | 100% | leaveSpeed | 21 | 212 |
| ball.massPct | ±1.5 % | 100% | leaveSpeed | 9.54 | 92.4 |
| material.cor | ±0.225 dimensionless | 100% | settleTime | 1.54 | 15.7 |
| spindle.dragDelta | ±0.009 N m | 100% | scatter | 1.32 | 49.3 |
| material.muBrass | ±0.113 dimensionless | 100% | settleTime | 0.565 | 4.88 |
| material.corBrass | ±0.225 dimensionless | 100% | deflectorHits | 0.431 | 3.28 |
| surface.rotorCor | ±9 % | 100% | settleTime | 0.285 | 4.78 |
| bowl.lowerTrackDeg | ±0.6 deg | 100% | deflectorHits | 0.222 | 2.29 |
| surface.deflectorCor | ±9 % | 100% | fretHits | 0.207 | 2.26 |
| surface.trackCor | ±9 % | 100% | leaveSpeed | 0.169 | 1.68 |
| spindle.offsetX | ±0.3 mm | 100% | settleTime | 0.158 | 2.17 |
| surface.fretCor | ±9 % | 100% | settleTime | 0.132 | 1.76 |
| deflector.1.height | ±0.6 mm | 25% | fretHits | 0.12 | 1.55 |
| rotor.eccSin | ±0.15 mm | 100% | settleTime | 0.117 | 1.72 |
| spindle.height | ±0.6 mm | 100% | fretHits | 0.102 | 1.47 |
| rotor.wobbleCos | ±0.06 deg | 100% | settleTime | 0.0999 | 1.53 |
| spindle.offsetY | ±0.3 mm | 100% | fretHits | 0.0949 | 1.62 |
| material.crrBrass | ±0.003 dimensionless | 100% | fretHits | 0.0949 | 1.76 |
| spindle.tiltX | ±0.09 deg | 100% | settleTime | 0.0939 | 1.64 |
| rotor.wobbleSin | ±0.06 deg | 100% | settleTime | 0.092 | 1.36 |
| spindle.tiltY | ±0.09 deg | 100% | settleTime | 0.0751 | 1.2 |
| deflector.1.radius | ±1.2 mm | 41% | fretHits | 0.0703 | 1 |
| surface.floorCor | ±9 % | 100% | fretHits | 0.0598 | 1.72 |
| rotor.eccCos | ±0.15 mm | 100% | settleTime | 0.0586 | 0.966 |
| deflector.1.yaw | ±1.5 deg | 27% | fretHits | 0.0527 | 1.12 |
| deflector.2.az | ±0.45 deg | 28% | settleTime | 0.0423 | 1.6 |
| deflector.1.az | ±0.45 deg | 39% | totalTime | 0.0383 | 1.81 |
| fret.17.angle | ±0.09 deg | 4.0% | settleTime | 0.0316 | 1.32 |
| deflector.2.radius | ±1.2 mm | 29% | deflectorHits | 0.0308 | 1.21 |
| fret.17.cor | ±9 % | 4.0% | settleTime | 0.0302 | 1.75 |
| fret.17.height | ±0.3 mm | 3.0% | settleTime | 0.0201 | 1.47 |
| deflector.2.yaw | ±1.5 deg | 1.5% | deflectorHits | 0.0185 | 1 |
| deflector.2.height | ±0.6 mm | 0.5% | deflectorHits | 0.0123 | 1 |
| material.muSBrass | ±0.135 dimensionless | 68% | fretHits | 0.0105 | 0.831 |
| pocket.17.depth | ±0.3 mm | 1.5% | settleTime | 0.00212 | 0.938 |
| pocket.17.cor | ±9 % | 1.5% | settleTime | 0.00137 | 0.789 |
| rotor.imbalanceCos | ±0.6 g m | 0.0% | - | 0 | 0 |
| rotor.imbalanceSin | ±0.6 g m | 0.0% | - | 0 | 0 |

## Plan

Shortlist of 20, 67 cases, 6000 trials each, about 11.1 h. Telling a 20% shift in one unnamed category would take 32,323 trials per arm.

What N buys, per case:

| Trials | Time per case | One known category, smallest shift | Any category, smallest shift | Whole pattern, Cohen w |
|---|---|---|---|---|
| 200 | 20 s | 244% | 401% | 0.514 |
| 1,000 | 2 min | 90% | 140% | 0.23 |
| 3,000 | 5 min | 48% | 73% | 0.133 |
| 10,000 | 17 min | 25% | 37% | 0.0727 |
| 30,000 | 50 min | 14% | 21% | 0.042 |
| 100,000 | 2.8 h | 7.7% | 11% | 0.023 |
| 300,000 | 8.3 h | 4.4% | 6.4% | 0.0133 |
| 1,000,000 | 27.5 h | 2.4% | 3.5% | 0.00727 |

## Sweep

6000 trials per case. Two clean baselines on different seeds gave p = 0.8123, which is what no change looks like here.

| Parameter | Delta | Reached | Moved outcome | Paired p | q | Most changed category | Gained / lost | Its q | Against null p |
|---|---|---|---|---|---|---|---|---|---|
| material.mu | 0.06 dimensionless | 100% | 97% | 0.4680 | 0.7304 | 20 | 166 / 126 | 1.0000 | 0.2134 |
| material.mu | -0.06 dimensionless | 100% | 97% | 0.1654 | 0.7304 | 14 | 129 / 178 | 1.0000 | 0.0821 |
| surface.trackMu | 30 % | 100% | 100% | 0.3388 | 0.7304 | 1 | 138 / 174 | 1.0000 | 0.2427 |
| surface.trackMu | -30 % | 100% | 97% | 0.5706 | 0.7304 | 29 | 181 / 142 | 1.0000 | 0.4499 |
| bowl.upperTrackDeg | 0.45 deg | 100% | 74% | 0.3414 | 0.7304 | 28 | 94 / 131 | 1.0000 | 0.3073 |
| bowl.upperTrackDeg | -0.45 deg | 100% | 77% | 0.1334 | 0.7304 | 20 | 151 / 101 | 1.0000 | 0.2180 |
| bowl.ovalSin | 0.45 mm | 100% | 78% | 0.6209 | 0.7304 | 20 | 128 / 92 | 1.0000 | 0.4155 |
| bowl.ovalSin | -0.45 mm | 100% | 78% | 0.3752 | 0.7304 | 15 | 138 / 100 | 1.0000 | 0.3127 |
| bowl.ovalCos | 0.45 mm | 100% | 76% | 0.2156 | 0.7304 | 20 | 133 / 95 | 1.0000 | 0.7028 |
| bowl.ovalCos | -0.45 mm | 100% | 76% | 0.4044 | 0.7304 | 6 | 148 / 104 | 1.0000 | 0.4383 |
| ball.comOffset | 0.06 mm | 100% | 95% | 0.0674 | 0.7304 | 9 | 118 / 170 | 1.0000 | 0.2904 |
| ball.comOffset | -0.06 mm | 0.0% | 0.0% | 1.0000 | 1.0000 | 0 | 0 / 0 | 1.0000 | 0.4956 |
| ball.outOfRound | 0.15 % | 100% | 99% | 0.7434 | 0.7999 | 20 | 176 / 127 | 1.0000 | 0.8483 |
| ball.outOfRound | -0.15 % | 100% | 97% | 0.5409 | 0.7304 | 20 | 180 / 127 | 1.0000 | 0.8267 |
| material.muSBrass | 0.135 dimensionless | 56% | 0.1% | 0.4060 | 0.7304 | 0 | 0 / 0 | 1.0000 | 0.5109 |
| material.muSBrass | -0.135 dimensionless | 65% | 0.3% | 0.2491 | 0.7304 | 15 | 0 / 2 | 1.0000 | 0.4557 |
| deflector.1.radius | 1.2 mm | 39% | 16% | 0.8174 | 0.8383 | 17 | 21 / 35 | 1.0000 | 0.4851 |
| deflector.1.radius | -1.2 mm | 37% | 16% | 0.4384 | 0.7304 | 33 | 36 / 19 | 1.0000 | 0.5387 |
| deflector.1.az | 0.45 deg | 37% | 10% | 0.5709 | 0.7304 | 22 | 13 / 30 | 1.0000 | 0.4201 |
| deflector.1.az | -0.45 deg | 37% | 10% | 0.4449 | 0.7304 | 27 | 8 / 25 | 1.0000 | 0.5855 |
| deflector.2.radius | 1.2 mm | 27% | 1.4% | 0.5671 | 0.7304 | 23 | 0 / 6 | 1.0000 | 0.6536 |
| deflector.2.radius | -1.2 mm | 25% | 1.5% | 0.5501 | 0.7304 | 0 | 1 / 6 | 1.0000 | 0.4915 |
| deflector.2.az | 0.45 deg | 25% | 1.1% | 0.6736 | 0.7698 | 23 | 0 / 4 | 1.0000 | 0.5843 |
| deflector.2.az | -0.45 deg | 26% | 1.3% | 0.1881 | 0.7304 | 17 | 0 / 4 | 1.0000 | 0.5784 |
| deflector.1.yaw | 1.5 deg | 26% | 14% | 0.5939 | 0.7304 | 1 | 28 / 13 | 1.0000 | 0.0589 |
| deflector.1.yaw | -1.5 deg | 26% | 14% | 0.7599 | 0.7999 | 15 | 25 / 13 | 1.0000 | 0.4465 |
| deflector.1.height | 0.6 mm | 24% | 16% | 0.3401 | 0.7304 | 6 | 29 / 15 | 1.0000 | 0.3991 |
| deflector.1.height | -0.6 mm | 24% | 16% | 0.3761 | 0.7304 | 25 | 18 / 33 | 1.0000 | 0.4030 |
| fret.17.height | 0.3 mm | 5.0% | 0.5% | 0.4821 | 0.7304 | 26 | 5 / 0 | 1.0000 | 0.4758 |
| fret.17.height | -0.3 mm | 5.1% | 0.4% | 0.1959 | 0.7304 | 32 | 5 / 0 | 1.0000 | 0.5162 |
| fret.17.cor | 9 % | 5.6% | 0.4% | 0.3453 | 0.7304 | 17 | 2 / 6 | 1.0000 | 0.4840 |
| fret.17.cor | -9 % | 5.6% | 0.4% | 0.4013 | 0.7304 | 2 | 0 / 2 | 1.0000 | 0.5109 |
| pocket.17.cor | 9 % | 2.8% | 0.0% | 0.3173 | 0.7304 | 0 | 0 / 0 | 1.0000 | 0.4939 |
| pocket.17.cor | -9 % | 2.7% | 0.0% | 0.1573 | 0.7304 | 17 | 2 / 0 | 1.0000 | 0.4956 |
| pocket.17.depth | 0.3 mm | 2.8% | 0.0% | 0.1573 | 0.7304 | 17 | 2 / 0 | 1.0000 | 0.4956 |
| pocket.17.depth | -0.3 mm | 2.8% | 0.0% | 0.3173 | 0.7304 | 0 | 0 / 0 | 1.0000 | 0.4939 |
| table.tiltX | 0.15 deg | 100% | 92% | 0.6083 | 0.7304 | 14 | 127 / 171 | 1.0000 | 0.5068 |
| table.tiltX | -0.15 deg | 100% | 93% | 0.0439 | 0.7304 | 15 | 187 / 120 | 0.2316 | 0.0448 |
| rotor.wobbleCos | 0.06 deg | 100% | 14% | 0.7416 | 0.7999 | 36 | 21 / 36 | 1.0000 | 0.8838 |
| rotor.wobbleCos | -0.06 deg | 100% | 13% | 0.5471 | 0.7304 | 21 | 15 / 28 | 1.0000 | 0.5808 |

**Paired** compares the arms launch by launch, so only trials the change moved count. **Moved outcome** is the share of trials that ended in a different category.

Mean paired change in each metric:

| Parameter | Delta | rimTime | totalTime | settleTime | leaveSpeed | fretHits | deflectorHits | leaveAz | rotorEntryAz | scatter |
|---|---|---|---|---|---|---|---|---|---|---|
| material.mu | 0.06 | 4.8 * | 4.85 * | -0.0155 * | -0.000105 * | -0.254 * | 0.0715 | -74.9 * | -73.9 * | 24.7 * |
| material.mu | -0.06 | -3.63 * | -5.42 * | 0.0775 * | 0.072 * | 0.248 * | -0.204 * | 8.84 * | -29.3 * | 41.3 * |
| surface.trackMu | 30 | 2.58 * | 2.64 * | 0.0214 * | -0.0000913 * | 0.116 * | 0.0518 | 79.8 * | 92.7 * | 13 * |
| surface.trackMu | -30 | -3.73 * | -3.69 * | 0.0347 * | 0.0324 * | 0.708 * | -0.0242 | -131 * | -88.7 * | -41.1 * |
| bowl.upperTrackDeg | 0.45 | -0.107 * | -0.072 * | 0.000998 | 0.014 * | 0.197 * | 0.0685 | 5.34 * | -4.59 * | -14 * |
| bowl.upperTrackDeg | -0.45 | 0.113 * | 0.08 * | 0.000273 | -0.0141 * | -0.0947 * | -0.0357 | -5.96 * | 2.37 * | 12.8 * |
| bowl.ovalSin | 0.45 | -0.0931 * | -0.115 * | 0.00689 | 0.014 * | 0.0826 | 0.0793 * | 0.164 | -0.505 | -0.865 |
| bowl.ovalSin | -0.45 | -0.0968 * | -0.127 * | 0.000333 | 0.0112 * | 0.066 | 0.0712 | 0.448 * | 0.0401 | -0.247 |
| bowl.ovalCos | 0.45 | -0.0675 * | -0.0889 * | 0.000461 | 0.00457 | 0.04 | -0.043 | 0.377 | -0.376 | -0.821 |
| bowl.ovalCos | -0.45 | -0.0663 * | -0.0858 * | -0.000158 | 0.00557 | 0.0271 | -0.0496 | 0.249 | -0.213 | -0.493 |
| ball.comOffset | 0.06 | -0.295 * | -0.15 * | 0.00127 | 0.00829 * | 0.101 * | 0.0145 | 43.6 * | 23.5 * | -36.5 * |
| ball.comOffset | -0.06 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| ball.outOfRound | 0.15 | -0.405 * | -0.32 * | -0.00285 | 0.00461 * | 0.00583 | 0.0157 | 67.1 * | 55.3 * | -23.3 * |
| ball.outOfRound | -0.15 | -0.364 * | -0.275 * | -0.00285 | 0.00469 * | 0.0565 | 0.026 | 59.9 * | 47.6 * | -25.1 * |
| material.muSBrass | 0.135 | 0 | 0.00000941 | -0.0000183 | 0 | 0.000667 | 0.000333 | 0 | -0.0000632 | 0.00324 |
| material.muSBrass | -0.135 | 0 | 0.000361 | 0.000449 | 0 | -0.000333 | 0.000167 | 0 | 0.0000182 | 0.00486 |
| deflector.1.radius | 1.2 | 0 | -0.00546 | -0.00012 | 0 | 0.0197 | 0.0557 * | 0 | 1.43 * | 1.65 * |
| deflector.1.radius | -1.2 | 0 | 0.00471 | 0.000185 | 0 | -0.008 | -0.009 | 0 | -1.39 * | -1.96 * |
| deflector.1.az | 0.45 | 0 | -0.00127 | 0.00000337 | 0 | 0.0183 | 0.000833 | 0 | -0.0177 | 0.0373 |
| deflector.1.az | -0.45 | 0 | -0.00157 | -0.000113 | 0 | 0.0095 | -0.006 | 0 | -0.00483 | 0.12 |
| deflector.2.radius | 1.2 | 0 | -0.000396 | -0.000215 | 0 | -0.000167 | -0.0015 | 0 | -0.0068 | -0.0357 |
| deflector.2.radius | -1.2 | 0 | -0.000648 | -0.0000835 | 0 | 0.00583 | 0.00467 | 0 | 0.0108 | 0.0876 |
| deflector.2.az | 0.45 | 0 | -0.000235 | 0.000136 | 0 | 0.00383 | 0.004 | 0 | 0.0146 | 0.0422 |
| deflector.2.az | -0.45 | 0 | -0.000177 | 0.000198 | 0 | 0.0035 | -0.00183 | 0 | -0.0109 | 0.0146 |
| deflector.1.yaw | 1.5 | 0 | -0.00145 | 0.000427 | 0 | 0.0198 | 0.0133 | 0 | 0.121 * | 0.347 |
| deflector.1.yaw | -1.5 | 0 | 0.00343 | -0.000515 | 0 | 0.0532 * | -0.0105 | 0 | -0.217 * | -0.519 * |
| deflector.1.height | 0.6 | 0 | -0.00419 | -0.000945 | 0 | 0.006 | 0.0852 * | 0 | 1.09 * | 1.19 * |
| deflector.1.height | -0.6 | 0 | 0.00428 | -0.000966 | 0 | 0.0348 | 0.0102 | 0 | -1.09 * | -1.52 * |
| fret.17.height | 0.3 | 0 | 0.000124 | -0.0000368 | 0 | 0.00783 | 0.000167 | 0 | 0 | -0.0276 |
| fret.17.height | -0.3 | 0 | -0.0000267 | -0.0000671 | 0 | 0.00433 | 0 | 0 | 0 | -0.013 |
| fret.17.cor | 9 | 0 | -0.0000808 | -0.000203 | 0 | 0.00817 | 0 | 0 | 0 | 0.0146 |
| fret.17.cor | -9 | 0 | 0.000116 | 0.000134 | 0 | 0.00183 | 0 | 0 | 0 | -0.0259 |
| pocket.17.cor | 9 | 0 | 0.000153 | 0.000153 | 0 | 0.00133 | 0 | 0 | 0 | 0.00162 |
| pocket.17.cor | -9 | 0 | -0.000317 | -0.000317 | 0 | -0.0025 | 0 | 0 | 0 | -0.00324 |
| pocket.17.depth | 0.3 | 0 | 0.000017 | 0.000017 | 0 | -0.00167 | 0 | 0 | 0 | -0.00324 |
| pocket.17.depth | -0.3 | 0 | 0.0000433 | 0.0000433 | 0 | -0.001 | 0 | 0 | 0 | 0.00162 |
| table.tiltX | 0.15 | -0.00525 | -0.0282 * | 0.00444 | 0.0000697 | -0.041 | -0.0818 * | 0.697 | 0.951 | 3.84 * |
| table.tiltX | -0.15 | -0.00509 | -0.032 * | -0.00135 | 0.0000679 | -0.0482 | -0.0917 * | 0.657 | 0.703 | 4 * |
| rotor.wobbleCos | 0.06 | 0 | 0.00121 | 0.000839 | 0 | 0.0267 | -0.000667 | 0 | 0 | 0.0422 |
| rotor.wobbleCos | -0.06 | 0 | 0.000779 | 0.000112 | 0 | 0.0158 | 0 | 0 | 0 | 0.138 |

`*` marks a paired |z| above 3.5.

## Beyond tolerance

| Parameter | Delta | Reached | Moved outcome | Paired p | q | Most changed category | Gained / lost | Its q | Against null p |
|---|---|---|---|---|---|---|---|---|---|
| fret.17.height | 1 mm (10 widths) | 5.0% | 0.8% | 0.6038 | 0.6440 | 26 | 3 / 0 | 1.0000 | 0.4307 |
| fret.17.height | -1 mm (10 widths) | 5.2% | 0.7% | 0.7991 | 0.7991 | 19 | 1 / 5 | 1.0000 | 0.5215 |
| fret.17.height | 3 mm (30 widths) | 5.2% | 1.1% | 0.5093 | 0.5912 | 25 | 8 / 16 | 1.0000 | 0.4488 |
| fret.17.height | -3 mm (30 widths) | 5.6% | 1.1% | 0.5173 | 0.5912 | 17 | 13 / 24 | 1.0000 | 0.5121 |
| fret.17.cor | 30 % (10 widths) | 5.6% | 0.7% | 0.0283 | 0.0565 | 6 | 11 / 1 | 0.7516 | 0.4677 |
| fret.17.cor | -30 % (10 widths) | 5.5% | 0.8% | 0.0062 | 0.0199 | 17 | 16 / 4 | 1.0000 | 0.4834 |
| fret.17.cor | 90 % (30 widths) | 5.6% | 1.4% | 0.0001 | 0.0007 | 17 | 8 / 30 | 0.0699 | 0.2250 |
| fret.17.cor | -90 % (30 widths) | 5.6% | 0.8% | 0.0019 | 0.0078 | 34 | 1 / 16 | 0.0542 | 0.4597 |
| pocket.17.cor | 30 % (10 widths) | 2.8% | 0.1% | 0.0183 | 0.0419 | 17 | 0 / 7 | 1.0000 | 0.4741 |
| pocket.17.cor | -30 % (10 widths) | 2.7% | 0.0% | 0.1573 | 0.2097 | 17 | 2 / 0 | 1.0000 | 0.4956 |
| pocket.17.cor | 90 % (30 widths) | 2.8% | 0.8% | 1.5e-8 | 2.3e-7 | 17 | 0 / 45 | 3.4e-11 | 0.0722 |
| pocket.17.cor | -90 % (30 widths) | 2.8% | 0.0% | 0.1573 | 0.2097 | 17 | 2 / 0 | 1.0000 | 0.4956 |
| pocket.17.depth | 1 mm (10 widths) | 2.8% | 0.0% | 0.1573 | 0.2097 | 17 | 2 / 0 | 1.0000 | 0.4956 |
| pocket.17.depth | -1 mm (10 widths) | 2.8% | 0.1% | 0.0143 | 0.0381 | 17 | 0 / 6 | 1.0000 | 0.4677 |
| pocket.17.depth | 3 mm (30 widths) | 2.8% | 0.0% | 0.1573 | 0.2097 | 17 | 2 / 0 | 1.0000 | 0.4956 |
| pocket.17.depth | -3 mm (30 widths) | 2.8% | 0.3% | 2.2e-5 | 0.0002 | 17 | 0 / 18 | 0.0023 | 0.3021 |

**Paired** compares the arms launch by launch, so only trials the change moved count. **Moved outcome** is the share of trials that ended in a different category.

| Parameter | Delta | rimTime | totalTime | settleTime | leaveSpeed | fretHits | deflectorHits | leaveAz | rotorEntryAz | scatter |
|---|---|---|---|---|---|---|---|---|---|---|
| fret.17.height | 1 | 0 | -0.0000217 | 7.25e-7 | 0 | 0.00283 | 0 | 0 | 0 | 0.00162 |
| fret.17.height | -1 | 0 | -0.000474 | -0.000535 | 0 | 0.001 | 0 | 0 | 0 | 0.0227 |
| fret.17.height | 3 | 0 | 0.0000191 | 0.000409 | 0 | 0.01 | 0 | 0 | 0 | 0.0178 |
| fret.17.height | -3 | 0 | 0.000369 | -0.00424 * | 0 | -0.00283 | 0.000167 | 0 | 0 | 0.0178 |
| fret.17.cor | 30 | 0 | 0.000552 | -0.000224 | 0 | 0.0147 * | 0.000167 | 0 | 0 | 0.0162 |
| fret.17.cor | -30 | 0 | -0.000861 | -0.00039 | 0 | -0.00617 | 0.000167 | 0 | 0 | -0.0405 |
| fret.17.cor | 90 | 0 | 0.00349 * | 0.000692 | 0 | 0.0387 * | 0.0015 | 0 | 0 | 0.0146 |
| fret.17.cor | -90 | 0 | -0.000465 | 0.000829 | 0 | -0.001 | 0 | 0 | 0 | -0.0341 |
| pocket.17.cor | 30 | 0 | 0.0000264 | 0.0000264 | 0 | 0.003 | 0 | 0 | 0 | 0.013 |
| pocket.17.cor | -30 | 0 | -0.0002 | -0.0002 | 0 | -0.00217 | 0 | 0 | 0 | -0.00324 |
| pocket.17.cor | 90 | 0 | 0.0032 * | 0.0032 * | 0 | 0.0132 | 0 | 0 | 0 | -0.00486 |
| pocket.17.cor | -90 | 0 | -0.000481 | -0.000481 | 0 | -0.001 | 0 | 0 | 0 | -0.00324 |
| pocket.17.depth | 1 | 0 | -0.0000176 | -0.0000176 | 0 | 0.000167 | 0 | 0 | 0 | -0.00324 |
| pocket.17.depth | -1 | 0 | 0.000237 | 0.000237 | 0 | 0 | 0 | 0 | 0 | 0.00973 |
| pocket.17.depth | 3 | 0 | -0.0000536 | -0.0000536 | 0 | 0.0025 | 0 | 0 | 0 | -0.00324 |
| pocket.17.depth | -3 | 0 | 0.000656 | -0.00402 * | 0 | -0.007 | 0 | 0 | 0 | 0.0292 * |

`*` marks a paired |z| above 3.5.

## Cross-coupling

Mean of ab - a - b + baseline, trial by trial. Zero means the pair just adds. `*` marks |z| above 3.5.

| Pair | rimTime | totalTime | settleTime | leaveSpeed | fretHits | deflectorHits | leaveAz | rotorEntryAz | scatter | Outcome p |
|---|---|---|---|---|---|---|---|---|---|---|
| table.tiltX 0.15 x spindle.tiltX 0.09 | 0 | -0.00296 | -0.00222 | 0 | -0.0245 | 0.000833 | 0 | 0 | -0.219 | 0.7617 |
| table.tiltX 0.15 x spindle.tiltX -0.09 | 0 | 0.00102 | -0.00221 | 0 | -0.00583 | 0 | 0 | 0 | -0.308 | 0.4545 |
