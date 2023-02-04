# Data anonymization on Tabluar data using k-Anonymity and texual data using presidio steps
## TEXT Anonymization
- Manually label enron email dataset for NER fine-tuning
- Performs Regular expression extraction for emails and password
- Fine-tunes Pretrained NER model to extract entities of interest such as person, dates, money etc.
- Replaces appropriate entities with their placeholders

## Tabular Anonymization
- Applys k-anonymity algorithm (modrian) on tabular data



## 📖 Reports
- Report link: [link]()
- Slide link: [link]()

## References
- Text https://github.com/microsoft/presidio-research
- Tabular https://github.com/glassonion1/anonypy
