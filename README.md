<div align="center">
<img src="images/Screenshot 2025-09-14 142421.png" alt="reactjs" width="200" height="100" />  
</div>

<h1 align="center">e6data x IIT BHU Hackathon</h1>


<h3 align="center">The e6data x IIT BHU Hackathon was a three-day event being held from 12th to 14th 
September 2025 at IIT BHU.</h3>

<h3 align="center">We provided with four problem statements, each drawn from critical challenges 
in the fields of data and AI. The problem areas are:
  <ol>
    
  </ol>  
  <ol>
     1. Approximate Query Engine 
  </ol>
  <ol>
     2. Infinitely Scalable Compute 
  </ol>
  <ol>
     3. AI-Powered Database Observability 
  </ol>
  <ol>
     4. Agentic Evaluation 
  </ol>
  
 </h3>
<hr>
<h2 align="center"> 🎯 Problem Statement</h2>
<h3 align = "center"> <u><i>Agentic Evaluation Framework </i></u>
</h3>

<h4>
  Context
</h4>

As AI agents become more powerful, evaluating them becomes critical. When we prompt an 
agent to perform a task, how do we ensure it: 
- Follows instructions exactly? 
- Doesn’t hallucinate facts? 
- Avoids unwarranted assumptions? 
- Provides coherent and accurate responses?

Now imagine this at scale: we have 100 agents, each producing thousands of responses. 
Manual evaluation is impossible. What we need is a scoring framework that can 
automatically grade responses across multiple dimensions. This is a crucial step toward 
building trustworthy AI systems.

<h4>
  The Challenge
</h4>

To design a framework for large-scale agent evaluation that: 
- Accepts prompts, responses, and metadata for 100s of agents. 
- Scores responses across dimensions: 
  - Instruction-following 
  - Hallucination detection 
  - Assumption control 
  - Coherence & accuracy
- Outputs an interpretable performance report.
<hr>

## 🛠 Features

- Scalable architecture for evaluating responses from 100s of agents
- Automated scoring across multiple evaluation dimensions
- Interpretability in performance reports
- Designed for large datasets with thousands of responses
- Supports metadata tracking and analysis


## 🚀 Getting Started

Follow these steps to set up the project locally and start evaluating agent responses.

### 1. Clone the repository

```
git clone https://github.com/visheshb1207/e6data_hackathon.git
cd e6data_hackathon
```
### 2. Install dependencies:

```
pip install -r requirements.txt

```


## 📊 Evaluation Dimensions

The detailed explanation of the key dimensions used to evaluate agent responses:

### <u> Instruction-following </u>
This dimension checks whether the agent’s response aligns with the instructions provided in the prompt. It ensures that the output directly addresses the task without deviating from the requirements.

### Hallucination detection
This dimension identifies cases where the agent invents or fabricates information that is not verified or supported by facts. It helps prevent the spread of misleading or false content.

### Assumption control
This dimension ensures that the agent does not add unwarranted assumptions, biases, or extrapolations beyond what is explicitly asked in the prompt. It maintains the integrity and relevance of the response.

### Coherence & accuracy
This dimension assesses whether the response is logically structured and factually correct. A coherent answer maintains consistency throughout, and accuracy ensures that the information is valid and trustworthy.


