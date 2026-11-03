# roulette: Monte Carlo run

### Acetal, level

40000 trials in 9703.9 s.

Outcome vs null: chi-square 39.57 on 36 df, **p = 0.3135**. 0 invalid trials.
At this sample size one category would have to shift by about 8.4% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 11 (1.045x), 16 (1.042x), 0 (1.038x). Most under-represented: 26 (0.918x), 28 (0.946x), 35 (0.953x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 40000 | mean 21.8, sd 1.64, 5-95% 19.2 to 25 |
| totalTime | 40000 | mean 27.98, sd 1.67, 5-95% 25.3 to 31.2 |
| settleTime | 40000 | mean 0.8987, sd 0.178, 5-95% 0.638 to 1.24 |
| leaveSpeed | 40000 | mean 0.8468, sd 0.00953, 5-95% 0.847 to 0.847 |
| fretHits | 40000 | mean 5.061, sd 1.79, 5-95% 2 to 7 |
| deflectorHits | 40000 | mean 1.252, sd 0.672, 5-95% 1 to 2 |
| leaveAz | 40000 | mean 231.7°, concentration R 0.00385, Rayleigh p 0.5529 |
| rotorEntryAz | 40000 | mean 281.5°, concentration R 0.00408, Rayleigh p 0.5145 |
| scatter | 40000 | mean 333.1°, concentration R 0.305, Rayleigh p 0.0e+0 |

### Acetal, tilted 0.2 deg

40000 trials in 11113.9 s.

Outcome vs null: chi-square 43.99 on 36 df, **p = 0.1693**. 0 invalid trials.
At this sample size one category would have to shift by about 8.4% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 22 (1.074x), 7 (1.060x), 9 (1.054x). Most under-represented: 4 (0.930x), 29 (0.935x), 27 (0.943x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 40000 | mean 21.8, sd 1.67, 5-95% 19.1 to 25 |
| totalTime | 40000 | mean 28.07, sd 1.68, 5-95% 25.4 to 31.3 |
| settleTime | 40000 | mean 0.8773, sd 0.161, 5-95% 0.618 to 1.14 |
| leaveSpeed | 40000 | mean 0.8469, sd 0.0102, 5-95% 0.842 to 0.852 |
| fretHits | 40000 | mean 4.569, sd 2.01, 5-95% 2 to 7 |
| deflectorHits | 40000 | mean 1.795, sd 2.15, 5-95% 1 to 3 |
| leaveAz | 40000 | mean 269.6°, concentration R 0.502, Rayleigh p 0.0e+0 |
| rotorEntryAz | 40000 | mean 202°, concentration R 0.328, Rayleigh p 0.0e+0 |
| scatter | 40000 | mean 168.4°, concentration R 0.0523, Rayleigh p 3.2e-48 |

Against baseline: paired outcome p = 0.3656, 95.6% of trials changed number, most changed 26 (gained 1080, lost 955, corrected p 0.2208); rimTime -0.00564 (p 1.4e-10); totalTime 0.0946 (p 1.5e-20); settleTime -0.0214 (p 6.5e-71); leaveSpeed 0.0000208 (p 0.0e+0); fretHits -0.492 (p 3.4e-292); deflectorHits 0.544 (p 0.0e+0); leaveAz mean 37.8° (p 0.0e+0); rotorEntryAz mean -79.6° (p 0.0e+0); scatter mean -165° (p 1.9e-267).
