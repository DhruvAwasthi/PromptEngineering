# Prompts - Iterative Prompt Development

This documents lists all the prompt samples used during the lecture on   
`Iterative Prompt Development`.   
<br>
You can find the corresponding jupyter notebook [here](../notebooks/2%20-%20Iterative%20Prompt%20Development.ipynb) and 
transcript [here](../transcripts/2%20-%20Iterative%20Prompt%20Development.txt).

--- 

**Sample 1:**
<br>  
Your task is to help a marketing team create a  
description for a retail website of a product based  
on a technical fact sheet.  

Write a product description based on the information  
provided in the technical specifications delimited by  
triple backticks.  

Technical specifications: &#96;&#96;&#96;{fact_sheet_chair}&#96;&#96;&#96;

---

**Sample 2:**
<br>  
Your task is to help a marketing team create a  
description for a retail website of a product based  
on a technical fact sheet.  

Write a product description based on the information  
provided in the technical specifications delimited by  
triple backticks.  

Use at most 50 words.  

Technical specifications: &#96;&#96;&#96;{fact_sheet_chair}&#96;&#96;&#96;

---

**Sample 3:**
<br>  
Your task is to help a marketing team create a  
description for a retail website of a product based  
on a technical fact sheet.  

Write a product description based on the information  
provided in the technical specifications delimited by  
triple backticks.  

The description is intended for furniture retailers,  
so should be technical in nature and focus on the  
materials the product is constructed from.  

Use at most 50 words.  

Technical specifications: &#96;&#96;&#96;{fact_sheet_chair}&#96;&#96;&#96;

---

**Sample 4:**
<br>  
Your task is to help a marketing team create a  
description for a retail website of a product based  
on a technical fact sheet.  

Write a product description based on the information  
provided in the technical specifications delimited by  
triple backticks.  

The description is intended for furniture retailers,  
so should be technical in nature and focus on the  
materials the product is constructed from.  

At the end of the description, include every 7-character  
Product ID in the technical specification.  

Use at most 50 words.  

Technical specifications: &#96;&#96;&#96;{fact_sheet_chair}&#96;&#96;&#96;

--- 

**Sample 5:**
<br>  
Your task is to help a marketing team create a
description for a retail website of a product based
on a technical fact sheet.

Write a product description based on the information
provided in the technical specifications delimited by
triple backticks.

The description is intended for furniture retailers,
so should be technical in nature and focus on the
materials the product is constructed from.

At the end of the description, include every 7-character
Product ID in the technical specification.

After the description, include a table that gives the
product's dimensions. The table should have two columns.
In the first column include the name of the dimension.
In the second column include the measurements in inches only.

Give the table the title 'Product Dimensions'.

Format everything as HTML that can be used in a website.
Place the description in a <div> element.

Technical specifications: &#96;&#96;&#96;{fact_sheet_chair}&#96;&#96;&#96;
