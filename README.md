   # Project URL:
https://mental-health-score-predictor-3-bbxy.onrender.com/




# Mental Health Predictor

A deep learning project that analyzes a piece of text and predicts a mental health category (for example: normal, anxiety, depression, stress). It uses a **Bidirectional GRU (BiGRU)** model built with TensorFlow/Keras and a **FastAPI** backend for real-time predictions.

> **Disclaimer:** This project is for education and research only. It is **not** a medical or diagnostic tool and must not replace advice from a qualified mental health professional. If you or someone you know is struggling, please contact a doctor, a counselor, or a local helpline.

## Features
- Predicts mental health categories:
- BiGRU model trained on <dataset name and source>
- Fast REST API with FastAPI
- Interactive testing through Swagger UI (`/docs`)
- Simple web interface served as static files

## Tech Stack
- Python
- HTML,CSS JavaScript
- TensorFlow 
- FastAPI and Uvicorn
- NumPy, Pandas, scikit-learn
- jupyter notebook

## Project Structure
```
MentalHealthPredictor/
├── Artifacts/        # Trained model and tokenizer files
├── static/           # Frontend files
├── main.py           # FastAPI application
└── requirements.txt


## How It Works
1. The input text is cleaned and converted to numbers with a saved tokenizer.
2. The sequence is padded to a fixed length.
3. The BiGRU model outputs a probability for each category.
4. The category with the highest probability is returned.



## Limitations and Ethics
- The model learns patterns from text and can be wrong. It cannot understand a person's full situation.
- Results may be biased by the training data (language style, region, platform).
- Do not use the output to label, judge, or make decisions about a real person.
- User text should not be stored or shared without clear consent.

## Future Improvements
- Compare with LSTM, CNN, and transformer models (BERT)
- Add confidence thresholds and a "seek professional help" message for high-risk results
- Deploy online (Render or Hugging Face Spaces)

## Author
**Your Name**
