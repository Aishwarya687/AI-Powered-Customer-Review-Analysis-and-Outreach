# AI-Powered-Customer-Review-Analysis-and-Outreach
Analyze women's clothing e-commerce reviews using Python, identify critical feedback and common complaints, and generate personalized, empathetic customer-support emails using Google's Gemini Generative AI.
# AI-Powered Customer Review Analysis and Outreach

## Overview
This project analyzes customer reviews from a women's clothing e-commerce dataset to identify critical feedback, discover common complaint patterns, and generate personalized customer-support apology emails using Google's Gemini Generative AI.

## Objectives
- Explore and analyze customer review data.
- Identify critical reviews using star ratings.
- Find common complaint keywords.
- Select low-rated reviews for customer outreach.
- Generate personalized, empathetic apology emails with Generative AI.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Regular Expressions
- Google Gemini API
- Jupyter Notebook / Google Colab

## Workflow
1. Load and explore the dataset.
2. Clean review text and handle missing or duplicate data.
3. Analyze rating distributions.
4. Identify critical reviews.
5. Examine predefined complaint keywords.
6. Select long 1-star reviews for outreach.
7. Generate personalized apology email drafts using Gemini.

## Dataset
The project uses the Women's Clothing E-Commerce Reviews dataset. It includes customer ratings, review text, product-related information, and other review attributes.

## Setup and Usage
1. Clone or download this repository.
2. Install the required Python packages:
   ```bash
   pip install pandas numpy matplotlib google-genai
   ```
3. Open `ecommerce_customer_reviewmail.ipynb` in Google Colab or Jupyter Notebook.
4. Make sure the CSV dataset is available at the file path specified in the notebook, or update the path.
5. Configure your Gemini API key securely using Colab Secrets or an environment variable.
6. Run the notebook cells in order.

## Notes
- Critical reviews are identified using rating-based rules and predefined keywords.
- Selecting the longest reviews does not necessarily identify the most severe complaints.
- AI-generated emails are drafts and should be reviewed before use.
- The notebook does not automatically send emails.
- Never commit API keys or other secrets to GitHub.

## Future Improvements
- Add sentiment analysis and topic modeling.
- Create interactive visualizations.
- Evaluate generated email quality.
- Build a dashboard for exploring customer feedback.

## Author
Aishwarya Sindhuri

GitHub: https://github.com/Aishwarya687
