# Week 1 Assignment

Based on Content of Week 1, there are **5 assignments** to be completed.

## Instructions:
1. **Download** the provided `.ipynb` files.
2. Solve them using **Jupyter Notebook** or **Google Colab**.
3. Save your completed `.ipynb` files.  
4. Make sure your notebook includes the outputs for all cells.
5. Upload your solutions to a GitHub repository (see steps below).

## How to Submit

You are required to upload your solutions to a **GitHub repository**. Follow the steps below:

### Step 1: Create a GitHub Repository

1. Go to [https://github.com](https://github.com).
2. Log in to your account (or sign up if you don’t have one).
3. Click the **“+”** icon in the top-right corner and select **“New repository”**.
4. Name your repository.
5. Add a description (Optional).
6. Keep the repository **public**.
7. Click **“Create repository”**.


### Step 2: Upload Your Files

#### Option A: Upload via GitHub Website

1. Open your newly created repository.
2. Click **“Add file” → “Upload files”**.
3. Drag and drop or browse to select your completed `.ipynb` files.
4. Click **“Commit changes”** to upload.

#### Option B: Upload via Git Command Line

1. Open your terminal (Git Bash or command prompt).
2. Run the following commands (replace `<your-repo-url>` with your actual repository URL):

```bash
git clone <your-repo-url>
cd <your-repo-name>
# Copy your .ipynb files into this folder
git add .
git commit -m "Add Week 1 assignment solutions"
git push origin main