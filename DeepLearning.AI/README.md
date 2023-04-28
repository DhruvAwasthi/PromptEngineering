# ChatGPT Prompt Engineering for Developers
Prompt engineering is a relatively new discipline for developing and   
optimizing prompts to efficiently use language models (LMs) for a wide  
variety of applications and research topics. Prompt engineering skills  
help to better understand the capabilities and limitations of large  
language models (LLMs). Researchers use prompt engineering to improve  
the capacity of LLMs on a wide range of common and complex tasks such  
as question answering and arithmetic reasoning. Developers use prompt  
engineering to design robust and effective prompting techniques that   
interface with LLMs and other tools.  
<br>
[DeepLearning.AI](https://www.deeplearning.ai/) in partnership with [OpenAI](https://openai.com/) created a short course on  
how to leverage best practices of prompt engineering to use a large  
langauge model (LLM) in a better way.   
<br>
You can access the course [here](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/).  
<br>
The course is taught by [Isa Fulford](https://www.linkedin.com/in/isabella-fulford/) (Member of Technical Staff, OpenAI)  
and [Andrew Ng](https://www.linkedin.com/in/andrewyng/) (Founder, DeepLearning.AI; Co-founder, Coursera)

## Repository Structure
The repository is organized in the following structure:  
```
images/  
    *.png
    
notebooks/
    *.ipynb
    
transcripts/
    *.txt
```
The `images/` directory contains important images captured from the   
lecture videos. This helps capture the important points made during  
the lectures such as iterative prompt development cycle.  
<br>
The `notebooks/` directory contains all the jupyter notebooks used  
during all the lecture videos. The platform does not provide the  
jupyter notebooks, so these might help you if you want to download   
them and run on your own machine.  
<br>
The `transctipts/` directory contains transcript of all the lecture  
videos. It might be helpful if you do not want to watch the entire  
videos or looking for something the instructors said during the lecture.  

## Principles of Prompting

### Principle 1: Write clear and specific instructions, where clear does not mean short.

**Tactic 1:** Use delimiters  
&emsp;&emsp;Triple quotes: """   
&emsp;&emsp;Triple backticks: ```   
&emsp;&emsp;Triple dashes: ---  
&emsp;&emsp;Angle brackets: < >  
&emsp;&emsp;XML tags: &lt;tag&gt; &lt;/tag&gt;


**Tactic 2:** Ask for structured output like HTML, JSON, etc.  

**Tactic 3:** Check whether the conditions are satisfied; check  
assumptions required to do the task.

**Tactic 4:** Few-short prompting; give successful examples of  
completing tasks then ask model to perform the task. 

### Principle 2: Give the model time to think.

**Tactic 1:** Specify the steps to complete a task.  
&emsp;&emsp;Step 1: ...  
&emsp;&emsp;Step 2: ...  
&emsp;&emsp;...  
&emsp;&emsp;Step N: ...  
	
**Tactic 2:** Instruct the model to work out its own solution before  
rushing to a conclusion


## Model Limitations

**Hallucination:**  
Makes statements that sound plausible but are not true. 


**Reducing hallucinations:**  
First find relevant information, then answer the question based on the  
relevant information.
  
<br>  
Happy Prompting!
