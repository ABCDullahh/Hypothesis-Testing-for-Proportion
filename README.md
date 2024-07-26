# Z TEST

This Jupyter notebook provides an in-depth analysis of Z tests and Chi-squared tests, along with their applications in various statistical scenarios.

## Table of Contents

1. Analisis Data
2. Cek Proporsi dari Masing-Masing Kolom pada Populasi
3. Sampling
4. Z-Test Single Population Proportion
   - Proporsi customer Male = 63%
   - Proporsi customer tidak perokok = 59%
5. Chi-Squared
   - Hubungan antara Sex dan Tip_given
   - Hubungan antara time dan weekday-weekend
   - Hubungan antara gender dan smoker

   ### Z-Test Single Population Proportion

1. **Proporsi Customer Male = 63%**
   - **Hipotesis**:
     - H0: p = 63%
     - Ha: p > 63%
   - **Signifikansi**: α = 0.05
   - **Kesimpulan**: Berdasarkan p-value dibandingkan dengan α

2. **Proporsi Customer Tidak Perokok = 59%**
   - **Hipotesis**:
     - H0: p = 59%
     - Ha: p ≠ 59%
   - **Signifikansi**: α = 0.05
   - **Kesimpulan**: Berdasarkan p-value dibandingkan dengan α

## Chi-Squared Test

1. **Hubungan antara Sex dan Tip_given**
   - **Hipotesis**:
     - H0: `Sex` dan `Tip_given` independent
     - Ha: `Sex` dan `Tip_given` dependent
   - **Signifikansi**: α = 0.05
   - **Kesimpulan**: Berdasarkan p-value dibandingkan dengan α

2. **Hubungan antara Time dan Weekday-Weekend**
   - **Hipotesis**:
     - H0: `time` dan `weekday-weekend` independent
     - Ha: `time` dan `weekday-weekend` dependent
   - **Signifikansi**: α = 0.05
   - **Kesimpulan**: Berdasarkan p-value dibandingkan dengan α

3. **Hubungan antara Gender dan Smoker**
   - **Hipotesis**:
     - H0: `gender` dan `smoker` independent
     - Ha: `gender` dan `smoker` dependent
   - **Signifikansi**: α = 0.05
   - **Kesimpulan**: Berdasarkan p-value dibandingkan dengan α
