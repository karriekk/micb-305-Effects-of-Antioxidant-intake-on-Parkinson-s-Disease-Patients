## Beta Diversity Analysis using Jaccard

### Notes:
1. Because we will be controlling for entacapone in downstream analyses and it contains NA values, they will be removed from the filtered metadata.
   - 10 PD patients are removed because they do not have entacapone intakes recorded.
2. When running beta-diversity analysis, age, sex, and entacapone are accounted for as confounding variables.
3. A sampling depth of 6515 is used when doing the analysis. At this sampling depth, only 14 samples are excluded from the analysis and we have retained 1,192,428 (50.04%) features in 183 (92.89%) samples.

### Beta diversity analysis of Beta Carotene
<img width="1440" height="900" alt="Screenshot 2026-03-28 at 07 36 48" src="https://github.com/user-attachments/assets/7bf50d57-8502-45b3-9e37-80909f5c6438" />

- BC low vs BC high: p-value = 0.004
- BC low vs BC medium: p-value = 0.023
- BC medium vs BC high: p-value = 0.002

### Beta diversity analysis of Alpha Carotene
<img width="1440" height="884" alt="Screenshot 2026-03-28 at 07 42 11" src="https://github.com/user-attachments/assets/085fb714-ff50-493b-a279-735496570c7e" />

- AC low vs AC high: p-value = 0.042
- AC low vs AC medium: p-value = 0.006
- AC medium vs AC high: p-value = 0.008

### Beta diversity analysis of Vitamin C
<img width="1440" height="900" alt="Screenshot 2026-03-28 at 07 45 03" src="https://github.com/user-attachments/assets/e66716b5-65c9-4753-bfb5-fc99ea54fd1f" />

- VC low vs VC high: p-value = 0.003
- VC low vs VC medium: p-value = 0.066
- VC medium vs VC high: p-value = 0.001

### Beta diversity analysis of Vitamin A
<img width="1440" height="900" alt="Screenshot 2026-03-28 at 07 46 57" src="https://github.com/user-attachments/assets/4639be93-d150-4df6-a764-8bbbe58c101f" />
  
- VA low vs VA high: p-value = 0.039
- VA low vs VA medium: p-value = 0.001
- VA medium vs VA high: p-value = 0.038

### Beta diversity analysis of Vitamin E
<img width="1440" height="900" alt="Screenshot 2026-03-28 at 07 49 55" src="https://github.com/user-attachments/assets/4d1ff90b-2395-4869-bfff-145f42b9d233" />

- VE low vs VE high: p-value = 0.001
- VE low vs VE medium: p-value = 0.002
- VE medium vs VE high: p-value = 0.01

### Beta diversity analysis on combined dietary antioxidants
<img width="1440" height="900" alt="Screenshot 2026-03-28 at 07 51 34" src="https://github.com/user-attachments/assets/73fa31dd-e054-4439-9d87-8b7515b0b988" />

- Combined low vs Combined high: p-value = 0.007
- Combined low vs Combined medium: p-value = 0.007
- Combined medium vs Combined high: p-value = 0.002
