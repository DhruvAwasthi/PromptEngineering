# Prompts - Inferring

This documents lists all the prompt samples used during the lecture on   
`Inferring`.   
<br>
You can find the corresponding jupyter notebook [here](../notebooks/4%20-%20Inferring.ipynb) and 
transcript [here](../transcripts/4%20-%20Inferring.txt).

--- 

**Sample 1:**
<br>
What is the sentiment of the following product review,  
which is delimited with triple backticks?  

Review text: &#96;&#96;&#96;{lamp_review}&#96;&#96;&#96;  

---

**Sample 2:**
<br>
What is the sentiment of the following product review,  
which is delimited with triple backticks?  
  
Give your answer as a single word, either "positive" \  
or "negative".  
  
Review text: &#96;&#96;&#96;{lamp_review}&#96;&#96;&#96;  

---

**Sample 3:**
<br>
Identify a list of emotions that the writer of the \  
following review is expressing. Include no more than \  
five items in the list. Format your answer as a list of \  
lower-case words separated by commas.  
  
Review text: &#96;&#96;&#96;{lamp_review}&#96;&#96;&#96;  

---

**Sample 4:**
<br>
Is the writer of the following review expressing anger?\  
The review is delimited with triple backticks. \  
Give your answer as either yes or no.  
  
Review text: &#96;&#96;&#96;{lamp_review}&#96;&#96;&#96;  
  
---

**Sample 5:**
<br>
Identify the following items from the review text:  
- Item purchased by reviewer  
- Company that made the item  
  
The review is delimited with triple backticks. \  
Format your response as a JSON object with \  
"Item" and "Brand" as the keys.  
If the information isn't present, use "unknown" \  
as the value.  
Make your response as short as possible.  
  
Review text: &#96;&#96;&#96;{lamp_review}&#96;&#96;&#96;  

--- 

**Sample 6:**
<br>
Identify the following items from the review text:  
- Sentiment (positive or negative)  
- Is the reviewer expressing anger? (true or false)  
- Item purchased by reviewer  
- Company that made the item

The review is delimited with triple backticks. \  
Format your response as a JSON object with \  
"Sentiment", "Anger", "Item" and "Brand" as the keys.  
If the information isn't present, use "unknown" \  
as the value.  
Make your response as short as possible.  
Format the Anger value as a boolean.  
  
Review text: &#96;&#96;&#96;{lamp_review}&#96;&#96;&#96;  

---

**Sample 7:**
<br>
Determine five topics that are being discussed in the \  
following text, which is delimited by triple backticks.  
  
Make each item one or two words long.  
  
Format your response as a list of items separated by commas.  
  
Text sample: &#96;&#96;&#96;{story}&#96;&#96;&#96;  

---

**Sample 8:**
<br>
Determine whether each item in the following list of \  
topics is a topic in the text below, which  
is delimited with triple backticks.  
  
Give your answer as list with 0 or 1 for each topic.\  
  
List of topics: &#96;&#96;&#96;{list_of_topics}&#96;&#96;&#96;  
  
Text sample: &#96;&#96;&#96;{story}&#96;&#96;&#96;  
