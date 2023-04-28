# Prompts - Guidelines for Prompting

This documents lists all the prompt samples used during the lecture on   
`Guidelines for Prompting`.   
<br>
You can find the corresponding jupyter notebook [here](../notebooks/1%20-%20Guidelines%20for%20Prompting.ipynb) and 
transcript [here](../transcripts/1%20-%20Guidelines%20for%20Prompting.txt).

---
   
**Sample 1:**
<br>  
Summarize the text delimited by triple backticks \   
into a single sentence.  
  
&#96;&#96;&#96;{text}&#96;&#96;&#96;

---

**Sample 2:**
<br>  
Generate a list of three made-up book titles along \   
with their authors and genres.   
Provide them in JSON format with the following keys:   
book_id, title, author, genre.  

---

**Sample 3:**
<br>  
You will be provided with text delimited by triple quotes.   
If it contains a sequence of instructions, \   
re-write those instructions in the following format:  
  
Step 1 - ...  
Step 2 - …  
…  
Step N - …  
  
If the text does not contain a sequence of instructions, \   
then simply write \"No steps provided.\"  

&#96;&#96;&#96;{text}&#96;&#96;&#96;

---

**Sample 4:**
<br>  
Your task is to answer in a consistent style.  
  
&lt;child&gt;: Teach me about patience.

&lt;grandparent&gt;: The river that carves the deepest \   
valley flows from a modest spring; the \   
grandest symphony originates from a single note; \   
the most intricate tapestry begins with a solitary thread.  

&lt;child&gt;: Teach me about resilience.

---

**Sample 5:**
<br>  
Perform the following actions:   
1 - Summarize the following text delimited by triple \  
backticks with 1 sentence.  
2 - Translate the summary into French.  
3 - List each name in the French summary.  
4 - Output a json object that contains the following \  
keys: french_summary, num_names.  

Separate your answers with line breaks.  

Text:  
&#96;&#96;&#96;{text}&#96;&#96;&#96;

---

**Sample 6:**
<br>  
Your task is to perform the following actions:   
1 - Summarize the following text delimited by   
  <> with 1 sentence.  
2 - Translate the summary into French.  
3 - List each name in the French summary.  
4 - Output a json object that contains the   
  following keys: french_summary, num_names.  

Use the following format:  
Text: &lt;text to summarize&gt;  
Summary: &lt;summary&gt;  
Translation: &lt;summary translation&gt;  
Names: &lt;list of names in Italian summary&gt;  
Output JSON: &lt;json with summary and num_names&gt;  

Text:  
<{text}>

---

**Sample 7:**
<br>  
Your task is to determine if the student's solution \  
is correct or not.  
To solve the problem do the following:  
- First, work out your own solution to the problem.   
- Then compare your solution to the student's solution \   
and evaluate if the student's solution is correct or not.

Don't decide if the student's solution is correct until   
you have done the problem yourself.  

Use the following format:  
Question:  
&#96;&#96;&#96;  
question here  
&#96;&#96;&#96;  
Student's solution:  
&#96;&#96;&#96;  
student's solution here  
&#96;&#96;&#96;  
Actual solution:  
&#96;&#96;&#96;  
steps to work out the solution and your solution here  
&#96;&#96;&#96;  
Is the student's solution the same as actual solution \  
just calculated:  
&#96;&#96;&#96;  
yes or no  
&#96;&#96;&#96;  
Student grade:  
&#96;&#96;&#96;  
correct or incorrect  
&#96;&#96;&#96;  

Question:  
&#96;&#96;&#96;  
I'm building a solar power installation and I need help \  
working out the financials.   
- Land costs $100 / square foot  
- I can buy solar panels for $250 / square foot  
- I negotiated a contract for maintenance that will cost \  
me a flat $100k per year, and an additional $10 / square \  
foot  

What is the total cost for the first year of operations \  
as a function of the number of square feet.  
&#96;&#96;&#96;   
Student's solution:  
&#96;&#96;&#96;  
Let x be the size of the installation in square feet.  
Costs:  
1. Land cost: 100x  
2. Solar panel cost: 250x  
3. Maintenance cost: 100,000 + 100x

Total cost: 100x + 250x + 100,000 + 100x = 450x + 100,000
&#96;&#96;&#96;  
Actual solution:   

