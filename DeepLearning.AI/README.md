# ChatGPT Prompt Engineering for Developers

## Principles of Prompting

### Principle 1: Write clear and specific instructions, where clear does not mean short.

**Tactic 1:** Use delimiters  
&emsp;&emsp;Triple quotes: """   
&emsp;&emsp;Triple backticks: ```   
&emsp;&emsp;Triple dashes: ---  
&emsp;&emsp;Angle brackets: < >  
&emsp;&emsp;XML tags: &lt;tag&gt; &lt;/tag&gt;


**Tactic 2:** Ask for structured output like HTML, JSON, etc.  

**Tactic 3:** Check whether the conditions are satisfied; check assumptions required to do the task.

**Tactic 4:** Few-short prompting; give successful examples of completing tasks then ask model to perform the task. 

### Principle 2: Give the model time to think.

**Tactic 1:** Specify the steps to complete a task.
	Step 1: ...
	Step 2: ...
	...
	Step N: ...
	
**Tactic 2:** Instruct the model to work out its own solution before rushing to a conclusion


## Model Limitations

**Hallucination:**
Makes statements that sound plausible but are not true. 


**Reducing hallucinations:**
First find relevant information, then answer the question based on the relevant information.
