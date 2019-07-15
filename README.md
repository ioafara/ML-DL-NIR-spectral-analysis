## Near infrared (NIR) spectral analysis using machine & deep learning

### :wrench: Note: still under construction  :nut_and_bolt: :sunglasses:

### Summary

NIR spectroscopy is a vibrational spectroscopic technique that is sensitive to specific molecular species containing
CH, NH, OH and SH bonds, which constitute the fundamental chemical structure of biological tissues. NIR spectroscopy is sensitive to micro- and macroscopic properties of cartilage (_10,11,19,20_), and a typical spectrum incorporates latent information on structural, compositional and morphological properties of the tissue. In addition, this optical modality penetrates deep into soft tissues (_21_), permitting full-depth cartilage probing (_22, 23_). The potential of NIR spectroscopy for non-destructive probing of articular cartilage is currently gaining research attention (_7–14, 19, 24, 25_), and its capacity for evaluation of engineered cartilage has been demonstrated (_26, 27_).

In this study, we evaluated the capacity of NIR spectroscopy, combined with machine and deep learning techniques, to classify cartilage integrity in rabbit (_n_=14) knee joints with artificial injury, induced via unilateral anterior cruciate ligament transection (ACLT), and the corresponding contra-lateral (CL) joints, including joints from separate non-operated control (CNTRL) animals (_n_=16). We compared the performance of traditional machine learning techniques, including support vector machines (SVM) and logistic regression (LR), with deep learning methods, particularly deep neural networks (DNN), for classification of cartilage integrity based on NIR spectral data. SVM is a supervised learning algorithm that uses the maximum margin principle to find a hyperplane that best separates two or multiple classes, while LR uses the logit (sigmoid) function to model the relationship between independent (predictors) and response (classes) variables based on maximum likelihood estimation. Unlike traditional analytical approach that is problem-defined, neural 114 networks are universal approximators. They can discover features in large datasets by using the backpropagation algorithm to indicate how a model should change its internal parameters that are used to compute the representation in each layer from the representation in the previous layer (_28_). We hypothesized that machine learning techniques can harness sample-related information embedded in the NIR spectrum for classification and holistic assessment of the tissue integrity.

Check out the notebooks on Google's Colaboratory

- NIRS multi-class classification analysis [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1msPHAviwc64HIsq9eZGcrzR7MDdlZtuw#scrollTo=rCGsYlc15xdU&uniqifier=1)

- NIRS binary classification analysis: ACLT vs CNTRL [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1msPHAviwc64HIsq9eZGcrzR7MDdlZtuw#scrollTo=rCGsYlc15xdU&uniqifier=1)

- NIRS binary classification analysis: CL vs CNTRL [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1msPHAviwc64HIsq9eZGcrzR7MDdlZtuw#scrollTo=rCGsYlc15xdU&uniqifier=1)


### References
###### 7. Afara, I. et al. Osteoarthritis Cartilage 20, 1367–1373 (2012)
###### 8. Spahn, G. et al. Med. Eng. Phys. 30, 285–92 (2008).
###### 9. Afara, I. O. et al. Arthroscopy, https://doi.org/10.1016/j.arthro.2014.04.097 (2014).
###### 10. Afara, I. O. et al. Physiol. Meas. 36, 1913–1928 (2015).
###### 11. Marticke, J. K. et al. Clin. Biomech. (Bristol, Avon) 25, 332–40 (2010).
###### 12. Padalkar, M. V. et al. Ann. Biomed. Eng. 41, 2426–36 (2013).
###### 13. Palukuru, U. P. et al. Matrix Biol. 38, 3–11 (2014).
###### 14. Stumpfe, S. T. et al. Muscles. Ligaments Tendons J. 3, 157–165 (2013).
###### 15. Hanifi, A. et al. PLoS One 8, e64822 (2013).
###### 16. Hanifi, A. et al. Am. J. Sports Med. 40, 2853–2861 (2014).
###### 17. Puhakka, P. H. et al. Osteoarthritis Cartilage, https://doi.org/10.1016/j.joca.2015.05.034 (2015).
###### 18. te Moller, N. C. R. et al. Vet. J. 197, 589–95 (2013).
###### 19. Afara, I. O. et al. Biomed. Opt. Express 6, 144–154 (2015)
###### 20. Afara, I. O. et al. J. Mech. Behav. Biomed. Mater. 20, 249–258 (2013).
###### 21. Faris, F. et al. Clin. Phys. Physiol. Meas. 12, 353–358 (1991).
###### 22. Afara, I. et al. Med. Eng. Phys. 35, 88–95 (2012).
###### 23. Sarin, J. K. et al. Ann. Biomed. Eng. 44, 3335–3345 (2016).
###### 24. Spahn, G. et al. Am. J. Sports Med. 38, 2516–2521 (2010).
###### 25. McGoverin, C. M. et al. Appl. Spectrosc. 68, 1168–1175 (2014).
###### 26. Baykal, D. et al. Appl. Spectrosc. 64, 1160–1166 (2010).
###### 27. Hanifi, A. et al. Analyst 142, 1320–1332 (2017).
###### 28. LeCun YA, Bengio Y, Hinton GE. Nature. 521(7553):436-444. doi:10.1038/nature14539 (2015).
