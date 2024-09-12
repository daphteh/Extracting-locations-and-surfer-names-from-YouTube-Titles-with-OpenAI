# Extracting locations and surfer names from YouTube Titles leveraging OpenAI API
In this project, I extracted the locations and pro-surfers mentioned in the titles of YouTube videos I had previously [scrapped](https://github.com/daphteh/Scraping_Cleaning_EDA_Surfing_Videos/tree/a621dd743177ec2882fe509c1c138b4a9298a6c6).
The purpose of this exercise is to engage in feature engineering and to produce variables / features that can be later used to examine if mentioning specific locations and people result in more views. 

#### Methods and Tools Used ####
* OpenAI API
* Regular expressions and NLP

#### Data ####
39,287 titles of YouTube videos from 40 channels. Note that due to the size of the file, I only uploaded a sample. 


# Methodology
<details>
<summary> Step 0: Set up </summary>
      <br>
      <p>   Get your OpenAI API key</p>
      <p>   Install the necessary packages so OpenAI can run and also to clean the text </p>
</details>

<details>   
<summary> Step 1: Write a function to prompt OpenAI to extract locations and surfers' names </summary>  
  <br>
  <p>  ... </p>
</details>

<details>
<summary> Step 2: Set up the data from which the locations and surfers' names need to be extracted </summary>
  <br>
  <p>   Load the scrapped and cleaned [data](https://github.com/daphteh/Scraping_Cleaning_EDA_Surfing_Videos/tree/a621dd743177ec2882fe509c1c138b4a9298a6c6) </p>
</details>

<details>
<summary> Step 3:  </summary>  
 <br>
  <p>   Develop a high level understanding of what is going on </p>
  <img width="1274" alt="Posting over the course of the year" src="https://github.com/daphteh/Scraping_Cleaning_EDA_Surfing_Videos/blob/2caa6cf1c2d43bb3196158b45f50a7f871cf979f/Report_Images/Posting_Patterns.png">
</details>
 
<details>
<summary> Step 4: Get the data into a time series format to discern how the channels' behavior changed over time</summary>
   <br>
   <p>   </p>
</details>


# Final Results
Nathan Florence's YouTube channel's performance is unique. Although his channel is one of the youngest, he has one of the most viewed, liked and commented on channels. Notably, he has the most viewed video in this sample. Notably, unlike most of the other channels, his posting behavior is remarkably consistent. 
Key takeaway: Consistency is key.

<br>
<br>
<img width="1274" alt="Time Series Data" src="https://github.com/daphteh/Scraping_Cleaning_EDA_Surfing_Videos/blob/2caa6cf1c2d43bb3196158b45f50a7f871cf979f/Report_Images/Posting_Patterns_OverTime.jpeg">
