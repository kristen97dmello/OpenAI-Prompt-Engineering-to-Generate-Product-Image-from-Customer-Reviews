# OpenAI Prompt Engineering to Generating Product Image from Customer Reviews

This project delves into the intersection of text and image generation. The goal is to use a LLM to extract valuable information from the textual content of the product customer reviews, followed by leveraging a diffusion model to re-create product images based on the customer reviews. This task not only tests the generative capabilities of AI in its understanding and interpretative abilities in extracting visual cues from texts, but also its ability in producing relevant visual content based on these visual cues.

# PART 1: Product Selection, Customer Review Data Collection and Sentiment Analysis
- Selected 3 different products from different categories on Amazon marketplace
- Collected the corresponding product descriptions (textual content) and customer reviews (textual content) for each product.
- Performed sentiment analysis for each review using prompt engineering and assigned a score for each product

  Reference File: ReviewSentimentAnalysis.ipynb

# PART 2: Image Generation with Diffusion Model
- For each product, based on the information extracted from the product description and customer reviews, crafting prompts to guide the image generation process effectively.
- Using the OpenAI’s DALLE 2 to generation of 3~5 images for each product based on your crafted prompts. Experimenting with different prompts and settings to best visualize what a good illustration of the product is based on product description and customer reviews.

  Reference File: FeatureExtraction.ipynb
