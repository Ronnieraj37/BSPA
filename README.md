# BSPA

## Results

- In our study, we explored multiple preprocessing techniques for our waveform dataset. Among these, we experimented with both the moving average and Butterworth filter methods.
- The moving average filter yielded lower accuracy compared to the Butterworth filter. So, we proceeded with the Butterworth filter.
- Initially, when we solely employimlemented a Deep Neural Network (DNN) without any preprocessing, our mean accuracy at around 56%.
- Through constant testing of various filtering methods and prediction techniques, we achieved a notable improvement, with the mean accuracy of 95%. The most efficient one emerged as Support Vector Machines (SVM) coupled with KFold validation, utilizing the Butterworth filter.
  This combination proved to be very effective, delivering a mean accuracy of 95%.

## CONCLUSION

- In summary, our study into EHG signals analysis through data preprocessing and prediction methods has yielded significant findings.
- We found that the Butterworth filter outperformed the moving average filter, leading to a substantial increase in accuracy from 56% to 95%.
- Among the techniques explored, combining Support Vector Machines (SVM) with KFold validation, utilizing the Butterworth filter, proved to be the most effective, consistently achieving a mean accuracy of 95%.
- These results can help hospitals predict how likely is it for a pregnant woman to go into preterm labor, by recording her EHG signals.

## Individual Contribution

- Sidharth: Provided insights by studying research papers. Additionally, guided the methodology and coding process.
- Roshan Raj Singh: Executed the coding tasks, translating research insights into practical implementation. Recorded detailed observations for analysis and interpretation.
- Ankush Sinha: Supported in methodology and coding tasks. Additionally, played role in preparing visually engaging slides for effective communication of findings.
