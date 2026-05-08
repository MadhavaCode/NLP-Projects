# nlp-projects

Natural Language Processing with pre-trained models.

## 📓 Notebooks

| Notebook | Task | Model / Library |
|---|---|---|
| `SentimentAnalysis.ipynb` | Customer review sentiment (positive/negative) | `distilbert-base-uncased-finetuned-sst-2-english` |
| `LanguageTranslationProject.ipynb` | Multi-language translation | `googletrans==3.1.0a0` |

## 💬 Sentiment Analysis
Uses Hugging Face `pipeline("sentiment-analysis")` to classify 12 product/course reviews with confidence scores.
- `"This product is fantastic!"` → **POSITIVE** (99.99%)
- `"Terrible experience. I want a refund!"` → **NEGATIVE** (99.94%)
- `"Great content, but more examples would be helpful."` → **POSITIVE** (95.32%)

## 🌍 Language Translation
Translates between multiple languages using the `googletrans` library:
- English → Japanese: `"Thank you very much"` → `"ありがとうございます。"`
- French → English: `"merci beaucoup"` → `"Thanks a lot"`
- English → German: `"The world is beautiful."` → `"Die Welt ist wunderschön."`

## 🛠 Tech Stack
`Python` · `Transformers (HuggingFace)` · `PyTorch` · `googletrans`

## 👤 Author
**Madhava Narra** — [@MadhavaCode](https://github.com/MadhavaCode) · Built May 2025
