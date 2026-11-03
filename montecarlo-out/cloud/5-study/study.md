# roulette: probe, then sweep

## Pilot

200 trials of the unmodified model. One trial costs 0.336 s of one core, so 3 workers run 8.93 trials a second. 0 invalid. Against the null, p = 0.6073.

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

Shortlist of 20, 67 cases, 10000 trials each, about 20.8 h. Telling a 20% shift in one unnamed category would take 32,323 trials per arm.

What N buys, per case:

| Trials | Time per case | One known category, smallest shift | Any category, smallest shift | Whole pattern, Cohen w |
|---|---|---|---|---|
| 200 | 22 s | 244% | 401% | 0.514 |
| 1,000 | 2 min | 90% | 140% | 0.23 |
| 3,000 | 6 min | 48% | 73% | 0.133 |
| 10,000 | 19 min | 25% | 37% | 0.0727 |
| 30,000 | 56 min | 14% | 21% | 0.042 |
| 100,000 | 3.1 h | 7.7% | 11% | 0.023 |
| 300,000 | 9.3 h | 4.4% | 6.4% | 0.0133 |
| 1,000,000 | 31.1 h | 2.4% | 3.5% | 0.00727 |
