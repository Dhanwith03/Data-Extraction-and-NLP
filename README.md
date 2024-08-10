##  Data analytics projects.

### Final Output Visualization
![Picture1](https://github.com/user-attachments/assets/3e531ac4-85e1-4924-8ff0-5c5975155067)

 ### **Extracting Article Headline and Processing**
   
  Using BeautifulSoup and Selenium libraries for Extracting and processing the articles and creating a DataFrame Output in Excel
  With the extracted information, we are Processing the article information with restrictions, Stopwords, Positive words Negative words, etc.

  * Our first task is to extract the article information with its headline. For that access to the web is required, with the help of library "request"  we get access and visit the URLs of the article pages
  * After accessing the pages we parse the data and save them in a dictionary, parsing is done with the help of beautiful Soup and Selenium.
  * Once we parse and save the data, We begin the processing part

  ### Preprocessing 

  **Steps for processing the data**
  * Cleaning- removing garbage chars
  * Tokenization- seperating to words
  * Normalization- changing all words to lower
  * Remove punctuation
  * Removing Stop WOrds- Removing all the stopwords which are given
  
  What are the **Stop Words**:
   * StopWords_Auditor
   * StopWords_Currencies
   * StopWords_DateandNumber
   * StopWords_Generic
   * StopWords_GenericLong
   * StopWords_Geographic
   * StopWords_Names
   Each of these txt files contains stop words

   **Variables**
   The output structure of the project required us to calculate a few variables, those are:
   * POSITIVE SCORE
   * POSITIVE SCORE
   * NEGATIVE SCORE
   * POLARITY SCORE
   * SUBJECTIVITY SCORE
   * AVG SENTENCE LENGTH
   * PERCENTAGE OF COMPLEX WORDS
   * FOG INDEX
   * AVG NUMBER OF WORDS PER SENTENCE
   * COMPLEX WORD COUNT
   * WORD COUNT
   * SYLLABLE PER WORD
   * PERSONAL PRONOUNS
   * AVG WORD LENGTH

   ### Output
   After removing the stopwords and calculating all the variables we save in a Excel sheet in the given order


   



  
   


