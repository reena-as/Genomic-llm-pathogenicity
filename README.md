# Comparative Genomic LLM Analysis for Variant Pathogenicity

This repository contains the accompanying paper for a machine learning study
investigating the behavior of large genomic language models when fine-tuned
for supervised variant classification.

The project focuses on fine-tuning DT-GPT (a Mistral-7B–based genomic LLM)
using LoRA adapters on ClinVar GRCh38 variant-centered genomic windows and
analyzing training dynamics, bias, and decision-boundary collapse.

The study includes custom dataset construction, model fine-tuning, and
evaluation pipelines for mapping generative outputs to binary predictions
and computing standard classification metrics.
