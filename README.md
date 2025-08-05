# Pseudo-Random Number Generator (PRNG) using External Entropy Sources
**Co-developed by Nicholas Iverson and three collaborators as part of an academic project.**

This project implements a custom pseudo-random number generator (PRNG) that draws entropy from unconventional sources, including cosmic ray detection data and outputs from AI language models (e.g., ChatGPT). It demonstrates how randomness can be enhanced using real-world, unpredictable data.

## 🔍 Features
- Uses external entropy (e.g., cosmic rays, ChatGPT outputs) as seed material.
- Visualizes entropy contribution and randomness quality.
- Offers reproducibility with optional local seeding.

## 📁 Project Structure
- `PRNGMultipleSources.ipynb` – Main Jupyter notebook demonstrating entropy collection, seeding, and random number generation.
- `requirements.txt` - states packages to be used in our notebook, required for notebook to work.
- `Cryptography_PRNG_Project_Final_Paper.pdf` - Co-authored final paper 'Exploring Digital Pseudorandom Number Generation'.
- `CSCI574 Presentation Slides.pptx` - Co-authored final class presentation with results and visualizations. Shows example output.

## 🚨 API Keys
This project may use APIs to fetch entropy. **API keys are NOT included for security reasons.**
To run the notebook:
1. Create a `.env` file or export your key as an environment variable:
2. Or manually replace `API_KEY = "YOUR_API_KEY_HERE"` in the notebook.
