# Research Paper Summary & Question Generator

**Suggested repo name:** `research-paper-analyzer`  
**Short description:** Automated summarization and question generation from research text with ROUGE and BLEU evaluation.

## Overview

This project implements an NLP pipeline that takes a research paper (or any technical text), generates a concise summary, produces comprehension questions, and evaluates the output quality using standard metrics (ROUGE for summarization and BLEU for question generation). It leverages Hugging Face transformer models.

## Features

- Text preprocessing (sentence tokenization)  
- Summary generation via `facebook/bart-large-cnn`  
- Question generation via `valhalla/t5-small-qg-prepend`  
- Evaluation using ROUGE and BLEU metrics  
- Example research paper embedded for demonstration
