# Extending-XNLI

**Extending the XNLI Dataset: Translating into Additional African Languages**

This project builds upon the original Cross-lingual Natural Language Inference (XNLI) dataset, which itself is a subset of a few thousand examples from the Multi-Genre Natural Language Inference (MNLI) dataset. XNLI originally includes translations into 14 languages, aimed at predicting textual entailment—whether one sentence implies, contradicts, or is neutral relative to another sentence.

The original XNLI dataset details can be found here:  
[XNLI 1.0 Dataset](https://github.com/facebookresearch/XNLI)

## Goal

- To extend the XNLI dataset by translating its English validation (dev) and test sets into additional African languages, thus facilitating broader benchmarking of Large Language Models (LLMs) and supporting NLP research for low-resource languages such as evaluating machine translation models.

## Approach

The following methodology is adopted:

1. **Initial Translation:** We translate the English dev and test sets from the XNLI dataset into selected African languages using pretrained machine translation models.

2. **Expert Review:** Translations are reviewed and validated by bilingual language experts to ensure linguistic accuracy and contextual relevance.

3. **Benchmarking Utility:** The translated datasets are particularly aimed at enabling comprehensive benchmarking of Large Language Models (LLMs) performance across these languages.

4. **Public Availability:** Validated translations are published on HuggingFace for easy and open access.

## Disclaimer

- Initial translations available in this repository are machine-generated and have **not yet been fully validated by language experts**.
- For finalized, validated datasets suitable for benchmarking, please refer to our HuggingFace repository:

[Tonative's HuggingFace Page](https://huggingface.co/Tonative)
