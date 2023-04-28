# Prompts - Summarizing

This documents lists all the prompt samples used during the lecture on   
`Summarizing`.   
<br>
You can find the corresponding jupyter notebook [here](../notebooks/3%20-%20Summarizing.ipynb) and 
transcript [here](../transcripts/3%20-%20Summarizing.txt).

--- 

**Sample 1:**
<br>
Your task is to generate a short summary of a product \  
review from an ecommerce site.  
  
Summarize the review below, delimited by triple  
backticks, in at most 30 words.  
  
Review: &#96;&#96;&#96;{prod_review}&#96;&#96;&#96;  

--- 

**Sample 2:**
<br>
Your task is to generate a short summary of a product \  
review from an ecommerce site to give feedback to the \  
Shipping deparmtment.  
  
Summarize the review below, delimited by triple  
backticks, in at most 30 words, and focusing on any aspects \  
that mention shipping and delivery of the product.  
  
Review: &#96;&#96;&#96;{prod_review}&#96;&#96;&#96;  

---

**Sample 3:**
<br>
Your task is to generate a short summary of a product \  
review from an ecommerce site to give feedback to the \  
pricing deparmtment, responsible for determining the \  
price of the product.  
  
Summarize the review below, delimited by triple  
backticks, in at most 30 words, and focusing on any aspects \  
that are relevant to the price and perceived value.  
  
Review: &#96;&#96;&#96;{prod_review}&#96;&#96;&#96;  

---

**Sample 4:**
<br>
Your task is to extract relevant information from \  
a product review from an ecommerce site to give \  
feedback to the Shipping department.  
  
From the review below, delimited by triple quotes \  
extract the information relevant to shipping and \  
delivery. Limit to 30 words.  
  
Review: &#96;&#96;&#96;{prod_review}&#96;&#96;&#96;    
