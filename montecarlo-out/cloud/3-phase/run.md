# roulette: Monte Carlo run

### Level, launch and rotor phase known

100000 trials in 8748.2 s.

Outcome vs null: chi-square 42.62 on 36 df, **p = 0.2078**. 1 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.057x), 11 (1.037x), 20 (1.026x). Most under-represented: 31 (0.956x), 4 (0.966x), 27 (0.967x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.263, sd 0.122, 5-95% 8.07 to 8.46 |
| totalTime | 100000 | mean 12.25, sd 0.759, 5-95% 11.9 to 12.7 |
| settleTime | 99999 | mean 0.6725, sd 0.114, 5-95% 0.515 to 0.894 |
| leaveSpeed | 99999 | mean 0.8475, sd 7.23e-7, 5-95% 0.847 to 0.847 |
| fretHits | 99999 | mean 3.853, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 99999 | mean 1.454, sd 1.12, 5-95% 1 to 3 |
| leaveAz | 99999 | mean 153.6°, concentration R 0.736, Rayleigh p 0.0e+0 |
| rotorEntryAz | 99999 | mean 121°, concentration R 0.711, Rayleigh p 0.0e+0 |
| scatter | 99999 | mean 289.7°, concentration R 0.566, Rayleigh p 0.0e+0 |

### Tilted 0.2 deg, phase known

100000 trials in 10143.2 s.

Outcome vs null: chi-square 42.5 on 36 df, **p = 0.2112**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 14 (1.039x), 8 (1.037x), 16 (1.034x). Most under-represented: 29 (0.952x), 15 (0.972x), 21 (0.973x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.051, sd 0.184, 5-95% 7.92 to 8.5 |
| totalTime | 100000 | mean 11.94, sd 0.409, 5-95% 11.6 to 12.8 |
| settleTime | 100000 | mean 0.6694, sd 0.109, 5-95% 0.516 to 0.877 |
| leaveSpeed | 100000 | mean 0.8513, sd 0.00214, 5-95% 0.846 to 0.853 |
| fretHits | 100000 | mean 3.76, sd 1.56, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.347, sd 0.886, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 192.2°, concentration R 0.708, Rayleigh p 0.0e+0 |
| rotorEntryAz | 100000 | mean 188.5°, concentration R 0.586, Rayleigh p 0.0e+0 |
| scatter | 100000 | mean 320°, concentration R 0.501, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.1141, 98.1% of trials changed number, most changed 31 (gained 2718, lost 2538, corrected p 0.5010); rimTime -0.212 (p 0.0e+0); totalTime -0.313 (p 0.0e+0); settleTime -0.00312 (p 7.4e-10); leaveSpeed 0.00386 (p 0.0e+0); fretHits -0.093 (p 4.4e-45); deflectorHits -0.107 (p 1.9e-123); leaveAz mean 38.6° (p 0.0e+0); rotorEntryAz mean 67.5° (p 0.0e+0); scatter mean 30.4° (p 0.0e+0).

### Tilted 0.5 deg, phase known

100000 trials in 10560.6 s.

Outcome vs null: chi-square 30.97 on 36 df, **p = 0.7065**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 1 (1.034x), 24 (1.032x), 7 (1.031x). Most under-represented: 12 (0.975x), 9 (0.975x), 13 (0.975x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 9.275, sd 0.292, 5-95% 8.93 to 9.59 |
| totalTime | 100000 | mean 11.64, sd 0.274, 5-95% 11.4 to 12.3 |
| settleTime | 100000 | mean 0.6611, sd 0.0978, 5-95% 0.518 to 0.845 |
| leaveSpeed | 100000 | mean 0.805, sd 0.0196, 5-95% 0.776 to 0.84 |
| fretHits | 100000 | mean 3.514, sd 1.58, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.566, sd 1.41, 5-95% 1 to 5 |
| leaveAz | 100000 | mean 8.702°, concentration R 0.961, Rayleigh p 0.0e+0 |
| rotorEntryAz | 100000 | mean 203.4°, concentration R 0.949, Rayleigh p 0.0e+0 |
| scatter | 100000 | mean 5.65°, concentration R 0.65, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.0706, 99.2% of trials changed number, most changed 10 (gained 2637, lost 2828, corrected p 0.3759); rimTime 1.01 (p 0.0e+0); totalTime -0.617 (p 0.0e+0); settleTime -0.0114 (p 5.0e-128); leaveSpeed -0.0424 (p 0.0e+0); fretHits -0.339 (p 0.0e+0); deflectorHits 0.111 (p 1.2e-84); leaveAz mean -145° (p 0.0e+0); rotorEntryAz mean 82.5° (p 0.0e+0); scatter mean 76° (p 0.0e+0).

### Tilted 1 deg, phase known

100000 trials in 10147.7 s.

Outcome vs null: chi-square 57.48 on 36 df, **p = 0.0129**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 29 (1.043x), 33 (1.041x), 31 (1.041x). Most under-represented: 19 (0.954x), 35 (0.961x), 0 (0.961x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.375, sd 0.651, 5-95% 7.65 to 9.28 |
| totalTime | 100000 | mean 10.66, sd 0.569, 5-95% 9.89 to 11.4 |
| settleTime | 100000 | mean 0.6763, sd 0.104, 5-95% 0.522 to 0.871 |
| leaveSpeed | 100000 | mean 0.8276, sd 0.0525, 5-95% 0.692 to 0.855 |
| fretHits | 100000 | mean 3.581, sd 1.73, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.299, sd 0.771, 5-95% 1 to 2 |
| leaveAz | 100000 | mean 317.1°, concentration R 0.336, Rayleigh p 0.0e+0 |
| rotorEntryAz | 100000 | mean 148.1°, concentration R 0.386, Rayleigh p 0.0e+0 |
| scatter | 100000 | mean 353.7°, concentration R 0.522, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.0299, 98.7% of trials changed number, most changed 31 (gained 2794, lost 2565, corrected p 0.0681); rimTime 0.112 (p 0.0e+0); totalTime -1.6 (p 0.0e+0); settleTime 0.00373 (p 7.6e-225); leaveSpeed -0.0198 (p 0.0e+0); fretHits -0.272 (p 0.0e+0); deflectorHits -0.155 (p 5.8e-283); leaveAz mean 164° (p 0.0e+0); rotorEntryAz mean 27.2° (p 0.0e+0); scatter mean 64° (p 0.0e+0).
