# Shorts Generator

This project uses AI to generate short-form video content. The development is done locally while computation runs on Google Colab for GPU acceleration.

## Project Structure
```
.
├── ShortsGenFinal.ipynb    # Main notebook for video generation
├── requirements.txt        # Python dependencies
└── README.md              # This file
```

## Setup Instructions

### Local Development
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/shorts-generator.git
   cd shorts-generator
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Google Colab Setup
1. Open [Google Colab](https://colab.research.google.com)
2. Go to File → Open Notebook → GitHub
3. Enter the repository URL
4. Select `ShortsGenFinal.ipynb`

## Usage
1. Make changes locally in your preferred IDE
2. Commit and push changes to GitHub:
   ```bash
   git add .
   git commit -m "Your commit message"
   git push
   ```
3. In Colab, click "Runtime" → "Run all" to execute with GPU acceleration
4. Results will be saved back to GitHub

## Features
- GPU-accelerated video processing
- Automatic GitHub synchronization
- Local development with Colab execution

## Requirements
- Python 3.8+
- Git
- Google Account (for Colab)
- GitHub Account 