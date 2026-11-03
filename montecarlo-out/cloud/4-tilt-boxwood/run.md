# roulette: Monte Carlo run

### Boxwood, level

40000 trials in 15275.6 s.

Outcome vs null: chi-square 36.92 on 36 df, **p = 0.4262**. 0 invalid trials.
At this sample size one category would have to shift by about 8.4% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 27 (1.075x), 0 (1.045x), 29 (1.042x). Most under-represented: 34 (0.928x), 13 (0.943x), 36 (0.954x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 40000 | mean 16.74, sd 1.88, 5-95% 14.3 to 20.1 |
| totalTime | 40000 | mean 21.23, sd 1.9, 5-95% 18.7 to 24.7 |
| settleTime | 40000 | mean 0.6813, sd 0.111, 5-95% 0.501 to 0.865 |
| leaveSpeed | 40000 | mean 0.8454, sd 2.72e-7, 5-95% 0.845 to 0.845 |
| fretHits | 40000 | mean 4.58, sd 1.83, 5-95% 2 to 7 |
| deflectorHits | 40000 | mean 1.258, sd 0.746, 5-95% 1 to 2 |
| leaveAz | 40000 | mean 2.958°, concentration R 0.000649, Rayleigh p 0.9833 |
| rotorEntryAz | 40000 | mean 190.2°, concentration R 0.0018, Rayleigh p 0.8786 |
| scatter | 40000 | mean 266.9°, concentration R 0.442, Rayleigh p 0.0e+0 |

### Boxwood, tilted 0.2 deg

40000 trials in 15726.4 s.

Outcome vs null: chi-square 36.8 on 36 df, **p = 0.4316**. 8 invalid trials.
At this sample size one category would have to shift by about 8.4% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 16 (1.080x), 7 (1.057x), 24 (1.051x). Most under-represented: 14 (0.944x), 33 (0.945x), 29 (0.957x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 40000 | mean 16.73, sd 1.89, 5-95% 14.3 to 20.1 |
| totalTime | 40000 | mean 21.08, sd 3.65, 5-95% 18.5 to 24.6 |
| settleTime | 39992 | mean 0.6615, sd 0.126, 5-95% 0.483 to 0.89 |
| leaveSpeed | 39992 | mean 0.8454, sd 0.00385, 5-95% 0.84 to 0.851 |
| fretHits | 39992 | mean 3.744, sd 2.33, 5-95% 1 to 6 |
| deflectorHits | 39992 | mean 2.232, sd 2.23, 5-95% 1 to 6 |
| leaveAz | 39992 | mean 270.7°, concentration R 0.359, Rayleigh p 0.0e+0 |
| rotorEntryAz | 39992 | mean 249.6°, concentration R 0.578, Rayleigh p 0.0e+0 |
| scatter | 39992 | mean 322.2°, concentration R 0.34, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.5914, 96.6% of trials changed number, most changed 34 (gained 1060, lost 967, corrected p 1.0000); rimTime -0.00501 (p 0.3715); totalTime -0.159 (p 8.6e-71); settleTime -0.0198 (p 5.8e-253); leaveSpeed -0.0000266 (p 0.0e+0); fretHits -0.836 (p 0.0e+0); deflectorHits 0.973 (p 0.0e+0); leaveAz mean -92.2° (p 5.9e-236); rotorEntryAz mean 59.4° (p 0.0e+0); scatter mean 55.4° (p 0.0e+0).
