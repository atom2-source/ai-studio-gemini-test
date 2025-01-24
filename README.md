# Gemini Model Tester

A PyQt5-based application for testing Google's Gemini models with built-in rate limiting.

## Features

- Model selection for different Gemini variants
- Rate limiting with RPM and daily request tracking
- File input/output support
- Real-time logging
- Response saving capabilities

## Requirements

- Python 3.8+
- PyQt5
- google.generativeai
- GEMINI_API_KEY environment variable

## Setup

1. Clone repository
2. Install dependencies:
```bash
pip install PyQt5 google-generativeai
```
3. Set GEMINI_API_KEY environment variable
4. Run:
```bash
python geminimodeltest.py
```