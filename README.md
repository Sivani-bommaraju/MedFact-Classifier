🏥 Multilingual Health Misinformation Detection using BERT
📌 Project Overview

The rapid spread of health misinformation online poses a serious public health threat across different languages and cultures. False claims related to diseases, treatments, and vaccines can lead to harmful decisions and societal panic.

This project develops a Multilingual Transformer-based Machine Learning model to automatically detect health-related misinformation across multiple languages including:

English

Chinese

Arabic

Bulgarian

The system classifies health-related content as:

True (Factual Information)

False (Misinformation)

The model achieves:

✅ 83.8% Accuracy
✅ Strong F1-score performance
✅ Multilingual capability

🎯 Social Impact

This project is socially beneficial because:

Helps combat online health misinformation

Supports digital literacy and public awareness

Can assist fact-checking organizations

Can be integrated into social media monitoring tools

Encourages responsible AI usage in healthcare

Health misinformation during pandemics (e.g., COVID-19) can cause:

Vaccine hesitancy

Unsafe home remedies

Public panic

Delay in medical treatment

This AI system aims to reduce such risks.

🧠 Model Architecture

The project uses:

BERT Multilingual (bert-base-multilingual-cased)

Transformer-based deep learning model

Fine-tuned for binary classification

CrossEntropyLoss with class weights

Stratified train-test split (75% / 25%)

📊 Dataset Details

Final merged dataset:

Total samples: 2203

Languages:

Chinese – 1224

English – 435

Bulgarian – 348

Arabic – 196

Labels:

True – 1285

False – 918

Dataset was:

Cleaned

Merged

Balanced (language-wise)

Preprocessed

Tokenized using BERT tokenizer

⚙️ Technologies Used

Python

PyTorch

Transformers (HuggingFace)

Scikit-learn

Pandas

Matplotlib

Jupyter Notebook

⚠️ Limitations

Short isolated claims may reduce prediction accuracy

Performance depends on dataset diversity

Larger datasets can further improve accuracy

Not a replacement for professional medical advice

🔮 Future Improvements

Build web-based UI for real-time prediction

Increase dataset size

Use more advanced models like XLM-R

Deploy as API service

Integrate into fact-checking platforms

📚 References

BERT: Devlin et al., 2018

Multilingual Transformers – HuggingFace

Public health misinformation research papers

