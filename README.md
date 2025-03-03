# Chronic Kidney Failure Classification

## Project Overview
Chronic kidney failure is a serious disease that can lead to death if not detected and treated early. This study aims to predict the risk of death in hospitalized chronic kidney failure patients using ensemble machine learning  methods, specifically  hard-voting and soft-voting.  The voting  classifier is used to combine predictions from several classification models, where hard-voting makes decisions based on the  majority  vote,  and  soft-voting  considers  the  average  prediction  probability.  However,  with imbalanced data, classification models tend to be biased toward the majority class. To address this, the synthetic minority oversampling technique (SMOTE) is applied to balance the class distribution. The model's performance is evaluated using accuracy, precision, and specificity metrics.

## Project Goals
This study aims to establish the best machine learning ensemble model using Hard-Voting and Soft-Voting algorithms to predict the risk of death of chronic kidney failure patients on imbalanced data.

## Project Conclusions and Recommendations
Based on the results and discussion, it can be concluded that the soft-voting and hard-voting classification models are able to provide good results in predicting the discharge conditions of chronic renal failure patients.  Based on the three evaluation values, the precision value shows that soft-voting is better than hard-voting. However, on the other hand, the accuracy and specificity values show that the hard-voting model is superior to soft-voting in predicting the discharge condition of hospitalized patients with chronic kidney failure.  The best classification model generated from hard-voting is able to show the prediction results of the percentage of conditions of chronic kidney failure hospitalized patients who return home dead by 18.3%, while those who return home do not die by 81.7%. 

Suggestions that can be given for future research are that there are many ensemble machine learning methods such as random forest, C4.5 algorithm, and various other methods that can be developed to produce higher prediction accuracy.

## Publication Link
The full version of this project results can be read at: https://ojs.unud.ac.id/index.php/mtk/article/view/119039
