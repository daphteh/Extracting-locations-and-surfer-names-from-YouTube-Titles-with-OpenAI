# Extracting locations and surfer names from YouTube Titles leveraging OpenAI API
In this project, I extracted the locations and pro-surfers mentioned in the titles of YouTube videos I had previously [scrapped](https://github.com/daphteh/Scraping_Cleaning_EDA_Surfing_Videos/tree/a621dd743177ec2882fe509c1c138b4a9298a6c6).
The purpose of this exercise is to engage in feature engineering and to produce variables / features that can be later used to examine questions such as what drives views.



#### Methods and Tools Used ####
* OpenAI API
* Regular expressions and NLP



#### Data ####
39,287 titles of YouTube videos from 40 channels. Note that due to the size of the file, I only uploaded a sample. 


## Methodology
<details>
<summary> Step 0: Set up </summary>
      <br>
      <p>   Get your OpenAI API key</p>
      <p>   Install the necessary packages so OpenAI can run and also to clean the text </p>
      <br>
</details>

<details>   
<summary> Step 1: Write a function to prompt OpenAI to extract locations and surfers' names </summary>  
  <br>
</details>

<details>
<summary> Step 2: Set up the data from which the locations and surfers' names need to be extracted </summary>
  <br>
  <p>   Load the scrapped and cleaned data </p>
  <br>
</details>

<details>
<summary> Step 3: Apply the function to the data </summary>  
 <br>
</details>
 
<details>
<summary> Step 4: Clean the output from OpenAI API </summary>
   <br>
   <p>  Find patterns in the output produced by OpenAI </p>
   <p>  Remove stopwords and phrases </p>
   <p>  Address spelling errors and colloquialisms (e.g. Jeffrey's Bay = J-Bay) </p>
   <p>  Consider aggregating locations (e.g. Bingin, Padang Padang, Canggu and Uluwatu are all in Bali) </p>
   <p>  Consider creating an indicator variable for whether or not a location is even mentioned </p>
   <br>
</details>


## Final Results
Additional features to supplement the original dataset. 

<img width="1274" alt="openai_extraction_progression" src="https://github.com/daphteh/Extracting-locations-and-surfer-names-from-YouTube-Titles-with-OpenAI/blob/769bf16e8e90d7ff74635457e62542115d22d3d2/Images/openai_extraction_progression.png">


This analysis can pertain to questions such as:
- Does mentioning locations / pro surfers increase viewership? (spoiler alert: only certain places and people matter)
- Does mentioning locations and pro-surfers in the titles increase views (***spoiler alert: Only specific locations and certain pros matter***)?
- Do these channels (or pro surfers) feature specific locations more than others?
- Which surfers are mentioned more on YouTube channels that are not their own? (indicator of their presence in the inddustry

<br>
