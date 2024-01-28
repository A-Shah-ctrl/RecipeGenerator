# RecipeGenerator

Whether it is seeking inspiration for culinary pursuits or trying to make a satisfying meal
with some leftover ingredients in the refrigerator, deciding what to cook is a common dilemma. With
technology’s growing impact on our daily life, deep learning models can serve as a practical solution
to our recurrent confusion of what to cook.
The project aims to unravel the mystery behind recipe creation, helping individuals in their culinary
pursuits by making the cooking process both efficient and enjoyable. We aim to develop an Encoder Decoder based 
Recurrent Neural Network that can suggest recipes based on ingredients provided.

# Dataset credits
All the credits for this dataset go to Ryan Lee. https://www.linkedin.com/in/ryan-t-lee/

# Instructions on running the code
To run the code please follow these steps:

1) Sign into Google Collab
2) Create a folder called "recipes_raw" in your Google Drive (in the parent directory)
3) Create a folder named "recipes_processed"
4) Visit this website: https://eightportions.com/datasets/Recipes/
5) Scroll down all the way. Click on the button that says "Download recipes"
6) It will download a zip folder. When you unzip it you will see four files
	i) recipes_raw_nosource_ar.json
	ii) recipes_raw_nosource_epi.json
	iii) recipes_raw_nosource_fn.json
	iv) LICENSE
7) Upload all these files to the 'raw_recipes' folder in your Google Drive
4) Open Processing.ipynb and run all the cells. This will create pickle files that will haev the processed data you can use to run the model.
5) Open Model.ipynb and run all the cells one by to build, run and view the model performance.
