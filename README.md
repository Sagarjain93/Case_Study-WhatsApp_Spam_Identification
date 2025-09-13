**WhatsApp Spam Detection – Case Study**
![a-digital-illustration-of-a-stylized-sma_oMChRmpOTDOSW-mJbJyrlg_ahnkl6E9TcebDyIW3XJIJw](https://github.com/user-attachments/assets/a7e99743-43ff-4ff8-a82f-b92a5e1e4039)

![1757684725813](https://github.com/user-attachments/assets/b57767ab-3ca8-4e91-b4b0-849f89f8c842)


**Project Overview**

This project explores how WhatsApp detects spam messages using a combination of Artificial Intelligence (AI), Machine Learning (ML), and Behavioral Analysis. With over 2 billion users globally, WhatsApp faces a massive challenge in combating spam, phishing, and fraudulent messages while maintaining end-to-end encryption (E2EE) and user privacy.

Our study demonstrates a data science approach to spam detection, covering data collection, preprocessing, feature engineering, and classification models.

**Problem Statement**

Spam messages on WhatsApp:

1. Lower the platform’s brand image

2. Compromise user experience & privacy

3. Lead to phishing attacks, scams, and malware

4. Increase unsubscriptions & negative word of mouth

![applsci-14-11804-g008-550](https://github.com/user-attachments/assets/6fccc930-ab7a-490f-9967-6a75f94111d8)

**WhatsApp’s Shield Against Spam**

WhatsApp deploys multi-layered detection techniques, including:

1.Behavioral Analysis → Message frequency, recipient patterns, timing, and account creation patterns

2.Machine Learning Models → Logistic Regression, Random Forest, Gradient Boosting, and anomaly detection

3.Metadata Analysis → Non-content-based signals under E2EE (time, frequency, group size, delivery rates)

4.User Reports & Feedback Loops → Community-driven detection & continuous retraining of models

5.Pattern Recognition → Identifying hidden URLs, promotional offers, phishing attempts, and adult content

**Methodology & System Architecture**

1. Data Collection – Public SMS spam datasets + synthetic WhatsApp-like dataset

2. Preprocessing – Tokenization, case-folding, stop-word removal, stemming/lemmatization

3. Feature Engineering – TF-IDF, word embeddings, metadata signals

4. Classification – Supervised ML (Logistic Regression, RF, XGBoost) + anomaly detection models

5. Behavioral Analysis – Spotting suspicious usage patterns vs. normal activity

6. Layered Detection Pipeline – Rules → ML Classifier → Graph/Anomaly Detection → Enforcement

**Key Findings**

Spam Categories:

1. Clickbait (28%)

2. Adult Content (24%)

3. Hidden URLs (20%)

4. Promotional Offers (15%)

5. Phishing Attempts (8%)

**WhatsApp’s Multi-Checkpoint Detection:**

*  Registration Stage – 20% spam blocked

*  Messaging Stage – 45% spam detected

*  User Reporting – 25% spam handled

**Scale of Enforcement:**

*  2022 → 28M accounts banned

*  2023 → 76M accounts banned

*  2024 → 92.4M accounts banned

<img width="600" height="400" alt="dad78db7-ac70-4da9-a211-52824e5df2d2" src="https://github.com/user-attachments/assets/415b166d-089f-4f5e-90fb-43ff7e4bd0bd" />


**Dashboard Insights**

*  High-volume spammers identified

*  Category breakdowns: phishing, fraud, promotions, malware

* Detection pipeline improves accuracy while minimizing false positives

**Ethics, Privacy & Safety**

1.  E2EE preserved (only metadata + user-reported samples used)

2.  Minimization of false positives (appeals & review process)

3.  Fairness across regions, devices, and demographics

4.  Limited data retention (only for abuse prevention)

**Future Recommendations**

1. Transformer-based Models → Better context & multilingual detection

2. Federated Learning → Privacy-preserving ML training

3. Cross-Platform Intelligence → Unified threat sharing across messaging apps

4. Behavioral Biometrics → Typing & interaction patterns

**Team – Fantastic 5**

1.  Neha Reddy

2.  Sagar Jain

3.  Harshit Sharma

4.  KalaiArasi Arumugam

5.  Daud Khan

**References**

1.  WhatsApp Official FAQ

2.  How WhatsApp fights spam

3.  IJRPR Spam Detection Paper

4.  Economic Times – Spam Blocking

**Acknowledgement**

Special thanks to **Almabetter** for providing the platform to carry out this project and to **Mr. Murtaza Porbunderwala** for his invaluable mentorship,encouragement, and feedback throughout.

**LinkedIn** 

https://www.linkedin.com/posts/almabetter_almabetter-datasciencecourses-softwarengineering-activity-7372264079287185408-c_zS?utm_source=share&utm_medium=member_desktop&rcm=ACoAACbSs5QBrM2QFreC_45eyqLLZ9An12235XQ


✨ This repository documents our journey in understanding and modeling how spam detection works on WhatsApp using a data science perspective.
