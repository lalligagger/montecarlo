# roulette: Monte Carlo run

### As designed, PTFE

100000 trials in 6694.1 s.

Outcome vs null: chi-square 40.94 on 36 df, **p = 0.2626**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 19 (1.029x). Most under-represented: 13 (0.957x), 33 (0.965x), 17 (0.973x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6737, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.818, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.571, Rayleigh p 0.0e+0 |

### Pocket floor restitution -9%, 3 widths (17)

100000 trials in 7394.5 s.

Outcome vs null: chi-square 40.66 on 36 df, **p = 0.2726**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 19 (1.029x). Most under-represented: 13 (0.957x), 33 (0.965x), 0 (0.974x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6735, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.818, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.571, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 7.7e-6, 0.0% of trials changed number, most changed 17 (gained 20, lost 0, corrected p 7.1e-5); rimTime 0 (p 1.0000); totalTime -0.000158 (p 1.0000); settleTime -0.000158 (p 1.0000); leaveSpeed 0 (p 1.0000); fretHits -0.00041 (p 1.0000); deflectorHits 0 (p 1.0000); leaveAz mean 0° (p 1.0000); rotorEntryAz mean 0° (p 1.0000); scatter mean -0.000688° (p 1.0000).
