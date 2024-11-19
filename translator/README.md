# Translation Testing Notebook

This Notebook is a tool for conducting translation tests. It allows testing translation quality using different translators and evaluation metrics.

## Features

- Supports multiple translators, including `Azure OpenAI Translator`.
- Provides various translation evaluation metrics, such as `BLEU` score.
- Can read local `CSV` files as test datasets.
- Automatically saves translation results to a CSV file.

## Usage

1. **Environment Setup**: Ensure the required Python packages are installed and environment variables are configured.
2. **Read Data**: Read the test dataset from a local CSV file.
3. **Perform Translation**: Use the specified translator to perform translations.
4. **Evaluate Translation**: Use the specified evaluation metrics to assess the translation results.
5. **Save Results**: Save the translation results to a CSV file.
