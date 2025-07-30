🧠 DS310.P11 – Enhancing Target-based Hate Speech Detection on Vietnamese Social Media
This project aims to improve the performance of target-based hate speech detection on Vietnamese social media texts by addressing imbalanced data and enhancing text normalization using the ViLexNorm dataset.

🔍 Problem
Target-based hate speech detection requires identifying both:

Whether a comment contains hate speech

Which group or individual the hatred is targeted at

Vietnamese social media texts are often informal, noisy, and highly imbalanced across target labels.

⚙️ Methodology
🧩 Data Challenges
Multi-label imbalance: Some hate targets are underrepresented

Noisy informal language: Requires normalization to standard Vietnamese

🔧 Preprocessing
Normalization: Applied based on the ViLexNorm dataset (developed by UIT researchers)

Data Augmentation: Used techniques like synonym replacement and random insertion to expand underrepresented classes

🔬 Experimental Settings
We compared three different preprocessing strategies:

Normalization only

Augmentation → then Normalization

Normalization → then Augmentation

🤖 Models Evaluated
We applied 4 models,which were used in the original paper to compare such as Bi-GRU–LSTM–CNN, XLM-R, ViSoBERT, PhoBERT

For the result, you can check the file report.pdf for more infomation.
