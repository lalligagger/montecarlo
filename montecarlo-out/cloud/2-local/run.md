# roulette: Monte Carlo run

### As designed, PTFE

100000 trials in 8565.2 s.

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

### Fret restitution -9%, 3 widths (next to 17)

100000 trials in 10203.8 s.

Outcome vs null: chi-square 39.66 on 36 df, **p = 0.3100**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 19 (1.031x). Most under-represented: 13 (0.957x), 33 (0.965x), 0 (0.976x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6736, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.814, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.571, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 1.2e-17, 0.3% of trials changed number, most changed 6 (gained 1, lost 43, corrected p 1.9e-10); rimTime 0 (p 1.0000); totalTime -0.000256 (p 1.0000); settleTime -0.0000841 (p 1.0000); leaveSpeed 0 (p 1.0000); fretHits -0.00413 (p 1.0000); deflectorHits 0.00001 (p 1.0000); leaveAz mean 0° (p 1.0000); rotorEntryAz mean 0° (p 1.0000); scatter mean -0.0134° (p 1.0000).

### Fret restitution +9%, 3 widths (next to 17)

100000 trials in 10759.5 s.

Outcome vs null: chi-square 46.24 on 36 df, **p = 0.1180**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 19 (1.029x). Most under-represented: 17 (0.953x), 13 (0.957x), 33 (0.965x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6737, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.824, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.57, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 8.2e-24, 0.4% of trials changed number, most changed 6 (gained 76, lost 13, corrected p 2.0e-10); rimTime 0 (p 1.0000); totalTime 0.000275 (p 1.0000); settleTime 0.0000359 (p 1.0000); leaveSpeed 0 (p 1.0000); fretHits 0.0052 (p 0.8988); deflectorHits -0.00001 (p 1.0000); leaveAz mean 0° (p 1.0000); rotorEntryAz mean 0° (p 1.0000); scatter mean 0.0136° (p 1.0000).

### Fret moved 0.09 deg, 3 widths (next to 17)

100000 trials in 10882.1 s.

Outcome vs null: chi-square 43.68 on 36 df, **p = 0.1774**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 19 (1.031x). Most under-represented: 13 (0.957x), 17 (0.958x), 33 (0.965x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6737, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.819, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.57, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.0002, 0.4% of trials changed number, most changed 17 (gained 31, lost 71, corrected p 0.0034); rimTime 0 (p 1.0000); totalTime -0.0000554 (p 1.0000); settleTime 0.00000117 (p 1.0000); leaveSpeed 0 (p 1.0000); fretHits 0.00078 (p 1.0000); deflectorHits 0.00002 (p 1.0000); leaveAz mean 0° (p 1.0000); rotorEntryAz mean 0° (p 1.0000); scatter mean 0.00269° (p 1.0000).

### Fret moved -0.09 deg, 3 widths (next to 17)

100000 trials in 10847.6 s.

Outcome vs null: chi-square 38.9 on 36 df, **p = 0.3405**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 19 (1.029x). Most under-represented: 13 (0.957x), 33 (0.965x), 5 (0.977x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6738, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.819, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.57, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.0001, 0.4% of trials changed number, most changed 25 (gained 31, lost 73, corrected p 0.0017); rimTime 0 (p 1.0000); totalTime 0.000108 (p 1.0000); settleTime 0.000103 (p 1.0000); leaveSpeed 0 (p 1.0000); fretHits 0.00029 (p 1.0000); deflectorHits 0 (p 1.0000); leaveAz mean 0° (p 1.0000); rotorEntryAz mean 0° (p 1.0000); scatter mean 0.00104° (p 1.0000).

### Fret 0.3 mm high, 3 widths (next to 17)

100000 trials in 10375.1 s.

Outcome vs null: chi-square 38.67 on 36 df, **p = 0.3498**. 0 invalid trials.
At this sample size one category would have to shift by about 5.3% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 10 (1.042x), 14 (1.036x), 15 (1.028x). Most under-represented: 13 (0.957x), 33 (0.965x), 0 (0.976x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 100000 | mean 8.262, sd 0.312, 5-95% 7.77 to 8.76 |
| totalTime | 100000 | mean 12.25, sd 0.371, 5-95% 11.7 to 12.9 |
| settleTime | 100000 | mean 0.6737, sd 0.114, 5-95% 0.516 to 0.897 |
| leaveSpeed | 100000 | mean 0.8475, sd 7.22e-7, 5-95% 0.847 to 0.847 |
| fretHits | 100000 | mean 3.819, sd 1.54, 5-95% 1 to 6 |
| deflectorHits | 100000 | mean 1.47, sd 1.14, 5-95% 1 to 3 |
| leaveAz | 100000 | mean 187.6°, concentration R 0.00255, Rayleigh p 0.5214 |
| rotorEntryAz | 100000 | mean 163.4°, concentration R 0.00287, Rayleigh p 0.4390 |
| scatter | 100000 | mean 289.5°, concentration R 0.571, Rayleigh p 0.0e+0 |

Against baseline: paired outcome p = 0.1370, 0.5% of trials changed number, most changed 25 (gained 53, lost 81, corrected p 0.7155); rimTime 0 (p 1.0000); totalTime 0.0000372 (p 1.0000); settleTime 0.0000154 (p 1.0000); leaveSpeed 0 (p 1.0000); fretHits 0.00052 (p 1.0000); deflectorHits 0.00002 (p 1.0000); leaveAz mean 0° (p 1.0000); rotorEntryAz mean 0° (p 1.0000); scatter mean -0.00368° (p 1.0000).
