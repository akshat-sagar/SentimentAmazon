# SentimentAmazon

This repository contains a sentiment analysis project on Amazon reviews.

---

## How to Run

### Step 1: Clone the repository

```bash
git clone https://github.com/akshat-sagar/SentimentAmazon.git
cd SentimentAmazon

# Step 2: Create and activate Conda environment
conda create -n amazonreview python=3.10 -y
conda activate amazonreview

# Step 3: Install dependencies
pip install -r requirements.txt

# Step 4: Run the Flask app
flask --app api.py run
