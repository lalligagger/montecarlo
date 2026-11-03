# roulette: Monte Carlo run

### pilot

3000 trials in 260.6 s.

Outcome vs null: chi-square 29.58 on 36 df, **p = 0.7662**. 0 invalid trials.
At this sample size one category would have to shift by about 30.7% of its probability to be seen reliably (80% power, uncorrected).
Most over-represented: 17 (1.147x), 0 (1.122x), 8 (1.122x). Most under-represented: 30 (0.715x), 32 (0.777x), 14 (0.839x).

| Metric | n | Summary |
|---|---|---|
| rimTime | 3000 | mean 8.271, sd 0.308, 5-95% 7.78 to 8.76 |
| totalTime | 3000 | mean 12.26, sd 0.368, 5-95% 11.7 to 12.9 |
| settleTime | 3000 | mean 0.6737, sd 0.112, 5-95% 0.517 to 0.89 |
| leaveSpeed | 3000 | mean 0.8475, sd 7.18e-7, 5-95% 0.847 to 0.847 |
| fretHits | 3000 | mean 3.829, sd 1.5, 5-95% 1 to 6 |
| deflectorHits | 3000 | mean 1.469, sd 1.1, 5-95% 1 to 3 |
| leaveAz | 3000 | mean 214.8°, concentration R 0.0157, Rayleigh p 0.4792 |
| rotorEntryAz | 3000 | mean 182.1°, concentration R 0.0185, Rayleigh p 0.3569 |
| scatter | 3000 | mean 288.1°, concentration R 0.562, Rayleigh p 0.0e+0 |
