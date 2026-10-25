# Craft Cataloger

Deep Learning Lab project, CBIT Hyderabad.
Authors: Leela Sai Charan Putti, Suneet Reddy

Identifies Indian handicrafts from a product photo by fine-tuning a pre-trained ResNet18, then generates a catalog card.

- Dataset: Indian Handicraft Products (Kaggle), 8 craft classes, 400 images each
- Model: ResNet18, two-stage fine-tuning (new classifier, then layer4)
- Result: 86.5% test accuracy (415/480), macro F1 0.86

## Files
- `batch2_131_116_code.ipynb`: code with saved outputs (run in Google Colab with a GPU)
- `batch2_131_116_report.pdf`: project report
- `batch2_131_116_presentation.pptx`: presentation slides
