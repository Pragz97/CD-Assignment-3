# Web-Scraping Recipes
## Description
The corpus for this assignment consists of two recipes off of the website _Southern Living_ - Shrimp Étouffée and Chicken and Sausage Gumbo, both Cajun/Creole dishes I enjoy making and eating. 
## Scraped Data
The recipes pages contain large amounts of personal anecdotes and further details regarding ingredient purposes and substitutions as well as images. To extract the most relevant information, I scraped and processed the ingredients list and the instructions for how to prepare the dishes. 
## Processing/ Data Cleaning steps
I used regex and other string operations to remove non text elements (like \n) and text that shared the same HTML elements as the recipe method but were not strictly part of the instructions themselves.
## Files and Formats
In this GitHub, excluding this README file, are the Jupyter Notebook in .ipynb format and the output of the webscraping saved as the CSV file - Extracted_Recipes.csv
## Terms and Conditions for scraping _Southern Living_
The parent company _Dotdashmeredith_ states their terms and conditions for Users of their websites. The most relevant to my usage is in Section 2.3 which includes the following - "Note that other Users may search for, see, use, modify, and reproduce any of Your Content that you submit to any "public" area of the Services." <br> 
The full terms and conditions can be found at https://www.dotdashmeredith.com/brands-termsofservice.
