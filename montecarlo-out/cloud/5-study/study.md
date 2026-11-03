# roulette: probe, then sweep

## Pilot

200 trials of the unmodified model. One trial costs 0.325 s of one core, so 3 workers run 9.24 trials a second. 0 invalid. Against the null, p = 0.6073.

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

Shortlist of 20, 67 cases, 10000 trials each, about 20.1 h. Telling a 20% shift in one unnamed category would take 32,323 trials per arm.

What N buys, per case:

| Trials | Time per case | One known category, smallest shift | Any category, smallest shift | Whole pattern, Cohen w |
|---|---|---|---|---|
| 200 | 22 s | 244% | 401% | 0.514 |
| 1,000 | 2 min | 90% | 140% | 0.23 |
| 3,000 | 5 min | 48% | 73% | 0.133 |
| 10,000 | 18 min | 25% | 37% | 0.0727 |
| 30,000 | 54 min | 14% | 21% | 0.042 |
| 100,000 | 3.0 h | 7.7% | 11% | 0.023 |
| 300,000 | 9.0 h | 4.4% | 6.4% | 0.0133 |
| 1,000,000 | 30.1 h | 2.4% | 3.5% | 0.00727 |

## Sweep

10000 trials per case. Two clean baselines on different seeds gave p = 0.9447, which is what no change looks like here.

| Parameter | Delta | Reached | Moved outcome | Paired p | q | Most changed category | Gained / lost | Its q | Against null p |
|---|---|---|---|---|---|---|---|---|---|
| material.mu | 0.06 dimensionless | 100% | 97% | 0.7169 | 0.8073 | 20 | 267 / 215 | 1.0000 | 0.3188 |
| material.mu | -0.06 dimensionless | 100% | 97% | 0.3146 | 0.8073 | 29 | 293 / 241 | 1.0000 | 0.1854 |
| surface.trackMu | 30 % | 100% | 100% | 0.4573 | 0.8073 | 20 | 273 / 222 | 1.0000 | 0.1907 |
| surface.trackMu | -30 % | 100% | 97% | 0.7468 | 0.8073 | 29 | 293 / 242 | 1.0000 | 0.6387 |
| bowl.upperTrackDeg | 0.45 deg | 100% | 74% | 0.7306 | 0.8073 | 20 | 205 / 162 | 1.0000 | 0.4945 |
| bowl.upperTrackDeg | -0.45 deg | 100% | 77% | 0.0829 | 0.5524 | 20 | 222 / 172 | 1.0000 | 0.3208 |
| bowl.ovalSin | 0.45 mm | 100% | 77% | 0.4696 | 0.8073 | 20 | 222 / 162 | 0.7578 | 0.4555 |
| bowl.ovalSin | -0.45 mm | 100% | 78% | 0.7031 | 0.8073 | 10 | 198 / 238 | 1.0000 | 0.3666 |
| bowl.ovalCos | 0.45 mm | 100% | 76% | 0.6938 | 0.8073 | 20 | 223 / 172 | 1.0000 | 0.9442 |
| bowl.ovalCos | -0.45 mm | 100% | 75% | 0.5277 | 0.8073 | 6 | 235 / 184 | 1.0000 | 0.2205 |
| ball.comOffset | 0.06 mm | 100% | 95% | 0.6492 | 0.8073 | 20 | 260 / 205 | 1.0000 | 0.7195 |
| ball.comOffset | -0.06 mm | 0.0% | 0.0% | 1.0000 | 1.0000 | 0 | 0 / 0 | 1.0000 | 0.9058 |
| ball.outOfRound | 0.15 % | 100% | 99% | 0.4985 | 0.8073 | 20 | 302 / 218 | 0.3927 | 0.3106 |
| ball.outOfRound | -0.15 % | 100% | 97% | 0.6079 | 0.8073 | 20 | 291 / 218 | 0.5153 | 0.7681 |
| material.muSBrass | 0.135 dimensionless | 56% | 0.1% | 0.4232 | 0.8073 | 0 | 0 / 0 | 1.0000 | 0.9111 |
| material.muSBrass | -0.135 dimensionless | 65% | 0.3% | 0.3405 | 0.8073 | 13 | 3 / 0 | 1.0000 | 0.8853 |
| deflector.1.radius | 1.2 mm | 40% | 16% | 0.4590 | 0.8073 | 33 | 55 / 33 | 1.0000 | 0.9223 |
| deflector.1.radius | -1.2 mm | 38% | 16% | 0.8287 | 0.8723 | 33 | 56 / 35 | 1.0000 | 0.8765 |
| deflector.1.az | 0.45 deg | 38% | 10% | 0.3938 | 0.8073 | 29 | 38 / 23 | 1.0000 | 0.9769 |
| deflector.1.az | -0.45 deg | 38% | 10% | 0.5140 | 0.8073 | 3 | 37 / 22 | 1.0000 | 0.9368 |
| deflector.2.radius | 1.2 mm | 27% | 1.3% | 0.3152 | 0.8073 | 20 | 8 / 1 | 1.0000 | 0.9256 |
| deflector.2.radius | -1.2 mm | 25% | 1.3% | 0.4666 | 0.8073 | 29 | 0 / 6 | 1.0000 | 0.8730 |
| deflector.2.az | 0.45 deg | 26% | 1.0% | 0.6116 | 0.8073 | 12 | 0 / 6 | 1.0000 | 0.9313 |
| deflector.2.az | -0.45 deg | 26% | 1.2% | 0.4559 | 0.8073 | 12 | 1 / 6 | 1.0000 | 0.9353 |
| deflector.1.yaw | 1.5 deg | 26% | 14% | 0.5219 | 0.8073 | 19 | 32 / 52 | 1.0000 | 0.5369 |
| deflector.1.yaw | -1.5 deg | 26% | 14% | 0.9065 | 0.9298 | 11 | 48 / 32 | 1.0000 | 0.7382 |
| deflector.1.height | 0.6 mm | 24% | 16% | 0.0774 | 0.5524 | 3 | 51 / 31 | 1.0000 | 0.9194 |
| deflector.1.height | -0.6 mm | 24% | 16% | 0.7068 | 0.8073 | 18 | 41 / 61 | 1.0000 | 0.8958 |
| fret.17.height | 0.3 mm | 5.3% | 0.5% | 0.4030 | 0.8073 | 26 | 5 / 0 | 1.0000 | 0.9007 |
| fret.17.height | -0.3 mm | 5.3% | 0.5% | 0.4949 | 0.8073 | 6 | 0 / 5 | 1.0000 | 0.8609 |
| fret.17.cor | 9 % | 5.7% | 0.4% | 0.2603 | 0.8073 | 17 | 3 / 8 | 1.0000 | 0.9067 |
| fret.17.cor | -9 % | 5.7% | 0.4% | 0.0113 | 0.4505 | 6 | 1 / 7 | 1.0000 | 0.8783 |
| pocket.17.cor | 9 % | 2.7% | 0.0% | 0.1573 | 0.7865 | 17 | 0 / 2 | 1.0000 | 0.8997 |
| pocket.17.cor | -9 % | 2.7% | 0.0% | 0.0455 | 0.4550 | 17 | 4 / 0 | 1.0000 | 0.9130 |
| pocket.17.depth | 0.3 mm | 2.7% | 0.0% | 0.0455 | 0.4550 | 17 | 4 / 0 | 1.0000 | 0.9130 |
| pocket.17.depth | -0.3 mm | 2.7% | 0.0% | 0.1573 | 0.7865 | 17 | 0 / 2 | 1.0000 | 0.8997 |
| table.tiltX | 0.15 deg | 100% | 92% | 0.5570 | 0.8073 | 20 | 280 / 206 | 0.4848 | 0.6699 |
| table.tiltX | -0.15 deg | 100% | 92% | 0.0372 | 0.4550 | 20 | 276 / 203 | 0.4848 | 0.0063 |
| rotor.wobbleCos | 0.06 deg | 100% | 13% | 0.5634 | 0.8073 | 3 | 57 / 34 | 1.0000 | 0.9874 |
| rotor.wobbleCos | -0.06 deg | 100% | 13% | 0.7340 | 0.8073 | 22 | 36 / 19 | 1.0000 | 0.7845 |

**Paired** compares the arms launch by launch, so only trials the change moved count. **Moved outcome** is the share of trials that ended in a different category.

Mean paired change in each metric:

| Parameter | Delta | rimTime | totalTime | settleTime | leaveSpeed | fretHits | deflectorHits | leaveAz | rotorEntryAz | scatter |
|---|---|---|---|---|---|---|---|---|---|---|
| material.mu | 0.06 | 4.8 * | 4.85 * | -0.0153 * | -0.000105 * | -0.274 * | 0.0602 * | -74.6 * | -73.9 * | 24.7 * |
| material.mu | -0.06 | -3.63 * | -5.41 * | 0.0781 * | 0.072 * | 0.248 * | -0.212 * | 8.57 * | -28.9 * | 41.3 * |
| surface.trackMu | 30 | 2.58 * | 2.66 * | 0.0214 * | -0.0000913 * | 0.085 * | 0.0412 | 80.4 * | 92.9 * | 12.9 * |
| surface.trackMu | -30 | -3.73 * | -3.69 * | 0.0367 * | 0.0323 * | 0.679 * | -0.0306 | -131 * | -89.7 * | -41 * |
| bowl.upperTrackDeg | 0.45 | -0.107 * | -0.0708 * | 0.000658 | 0.014 * | 0.186 * | 0.066 * | 5.34 * | -4.53 * | -14.2 * |
| bowl.upperTrackDeg | -0.45 | 0.113 * | 0.0814 * | 0.00209 | -0.0141 * | -0.0901 * | -0.0318 | -5.96 * | 2.46 * | 12.8 * |
| bowl.ovalSin | 0.45 | -0.0944 * | -0.12 * | 0.00495 | 0.0144 * | 0.0615 | 0.0696 * | 0.271 | -0.513 * | -0.885 |
| bowl.ovalSin | -0.45 | -0.0846 * | -0.112 * | 0.00201 | 0.00974 * | 0.0573 | 0.0608 * | 0.252 | -0.104 | -0.207 |
| bowl.ovalCos | 0.45 | -0.0632 * | -0.08 * | 0.00219 | 0.00684 * | 0.0206 | -0.0354 | 0.255 | -0.444 | -1.23 |
| bowl.ovalCos | -0.45 | -0.0598 * | -0.0784 * | 0.00069 | 0.00475 * | 0.00311 | -0.0622 * | 0.177 | -0.139 | -0.36 |
| ball.comOffset | 0.06 | -0.295 * | -0.15 * | 0.00161 | 0.00827 * | 0.0714 | 0.0273 | 43.4 * | 23.5 * | -36.2 * |
| ball.comOffset | -0.06 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| ball.outOfRound | 0.15 | -0.406 * | -0.321 * | -0.00174 | 0.00467 * | 0.002 | 0.0234 | 67.1 * | 55.3 * | -23.6 * |
| ball.outOfRound | -0.15 | -0.365 * | -0.275 * | -0.00274 | 0.00471 * | 0.0109 | 0.0279 | 60.1 * | 47.8 * | -25.3 * |
| material.muSBrass | 0.135 | 0 | -0.000171 | -0.000175 | 0 | 0.001 | 0.0002 | 0 | -0.0000551 | 4.55e-17 |
| material.muSBrass | -0.135 | 0 | 0.0000626 | 0.000111 | 0 | 0.0006 | 0.0002 | 0 | 0.0000169 | 0.00292 |
| deflector.1.radius | 1.2 | 0 | -0.00705 * | 0.000113 | 0 | 0.004 | 0.0591 * | 0 | 1.42 * | 1.78 * |
| deflector.1.radius | -1.2 | 0 | 0.00494 * | 0.000298 | 0 | -0.0201 | -0.0129 | 0 | -1.37 * | -1.97 * |
| deflector.1.az | 0.45 | 0 | -0.000531 | 0.000543 | 0 | -0.0032 | -0.002 | 0 | 0.0104 | 0.0126 |
| deflector.1.az | -0.45 | 0 | -0.00137 | -0.000175 | 0 | -0.0032 | -0.005 | 0 | 0.0144 | 0.164 |
| deflector.2.radius | 1.2 | 0 | -0.00033 | -0.000123 | 0 | -0.0001 | -0.0001 | 0 | -0.00679 | -0.0204 |
| deflector.2.radius | -1.2 | 0 | -0.000382 | 0.00022 | 0 | 0.0004 | 0.0019 | 0 | 0.00449 | 0.0701 |
| deflector.2.az | 0.45 | 0 | -0.0000412 | 0.000243 | 0 | 0.0036 | 0.0019 | 0 | 0.00738 | 0.0545 |
| deflector.2.az | -0.45 | 0 | -0.000224 | 0.000233 | 0 | 0.0034 | -0.0006 | 0 | -0.007 | 0.0282 |
| deflector.1.yaw | 1.5 | 0 | -0.00311 | 0.000686 | 0 | 0.0016 | 0.021 | 0 | 0.134 * | 0.53 * |
| deflector.1.yaw | -1.5 | 0 | 0.00271 | -0.0000552 | 0 | 0.0232 | -0.013 | 0 | -0.218 * | -0.503 * |
| deflector.1.height | 0.6 | 0 | -0.00525 * | -0.000904 | 0 | -0.0176 | 0.0799 * | 0 | 1.11 * | 1.29 * |
| deflector.1.height | -0.6 | 0 | 0.00362 | -0.000183 | 0 | 0.0159 | 0.0115 | 0 | -1.05 * | -1.35 * |
| fret.17.height | 0.3 | 0 | 0.00000845 | -0.000108 | 0 | 0.0075 | 0.0001 | 0 | 0 | -0.0195 |
| fret.17.height | -0.3 | 0 | 0.0000608 | -0.0000421 | 0 | 0.0044 | 0.0003 | 0 | 0 | -0.0234 |
| fret.17.cor | 9 | 0 | 0.000285 | 0.000079 | 0 | 0.0111 * | 0.0001 | 0 | 0 | 0.0107 |
| fret.17.cor | -9 | 0 | 0.0000344 | 0.000223 | 0 | -0.0011 | 0 | 0 | 0 | -0.0272 |
| pocket.17.cor | 9 | 0 | 0.000093 | 0.000093 | 0 | 0.001 | 0 | 0 | 0 | 0.00195 |
| pocket.17.cor | -9 | 0 | -0.000258 | -0.000258 | 0 | -0.0028 | 0 | 0 | 0 | -0.00389 |
| pocket.17.depth | 0.3 | 0 | 0.0000379 | 0.0000379 | 0 | -0.0014 | 0 | 0 | 0 | -0.00389 |
| pocket.17.depth | -0.3 | 0 | 0.0000923 | 0.0000923 | 0 | -0.0009 | 0 | 0 | 0 | 0.00195 |
| table.tiltX | 0.15 | -0.00371 | -0.0266 * | 0.00354 | 0.0000404 | -0.0381 | -0.0899 * | 0.477 | 0.599 | 3.35 * |
| table.tiltX | -0.15 | -0.007 * | -0.0358 * | 0.000409 | 0.000105 * | -0.0776 * | -0.0903 * | 0.927 * | 1.25 | 4.08 * |
| rotor.wobbleCos | 0.06 | 0 | 0.00167 | 0.00137 | 0 | 0.0105 | -0.0003 | 0 | 0 | -0.0136 |
| rotor.wobbleCos | -0.06 | 0 | 0.00117 | -0.000319 | 0 | 0.0202 | 0.0001 | 0 | 0 | -0.0574 |

`*` marks a paired |z| above 3.5.

## Beyond tolerance

| Parameter | Delta | Reached | Moved outcome | Paired p | q | Most changed category | Gained / lost | Its q | Against null p |
|---|---|---|---|---|---|---|---|---|---|
| fret.17.height | 1 mm (10 widths) | 5.3% | 0.9% | 0.2199 | 0.3664 | 25 | 10 / 20 | 1.0000 | 0.8513 |
| fret.17.height | -1 mm (10 widths) | 5.5% | 0.8% | 0.4789 | 0.5874 | 26 | 4 / 0 | 1.0000 | 0.8698 |
| fret.17.height | 3 mm (30 widths) | 5.4% | 1.3% | 0.0537 | 0.1344 | 25 | 14 / 41 | 0.0657 | 0.8021 |
| fret.17.height | -3 mm (30 widths) | 5.7% | 1.3% | 0.5874 | 0.5874 | 34 | 33 / 18 | 1.0000 | 0.8130 |
| fret.17.cor | 30 % (10 widths) | 5.7% | 0.8% | 0.0004 | 0.0018 | 6 | 21 / 4 | 0.0842 | 0.8648 |

**Paired** compares the arms launch by launch, so only trials the change moved count. **Moved outcome** is the share of trials that ended in a different category.

| Parameter | Delta | rimTime | totalTime | settleTime | leaveSpeed | fretHits | deflectorHits | leaveAz | rotorEntryAz | scatter |
|---|---|---|---|---|---|---|---|---|---|---|
| fret.17.height | 1 | 0 | 0.00022 | -0.0000357 | 0 | 0.005 | 0 | 0 | 0 | -0.00973 |
| fret.17.height | -1 | 0 | -0.000295 | -0.000244 | 0 | -0.0017 | 0 | 0 | 0 | 0.0175 |
| fret.17.height | 3 | 0 | 0.000194 | 0.000425 | 0 | 0.006 | 0 | 0 | 0 | 0.0243 |
| fret.17.height | -3 | 0 | 0.000247 | -0.00419 * | 0 | -0.0019 | 0.0001 | 0 | 0 | 0.0234 |
| fret.17.cor | 30 | 0 | 0.000584 | -0.000125 | 0 | 0.0164 * | 0.0001 | 0 | 0 | 0.0418 |

`*` marks a paired |z| above 3.5.
