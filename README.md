

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

# AI Tools Required: 
ChatGPT
# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT
Here is your completed, structured comparative analysis report based on the provided experimental data.

---

# Performance Report: Evaluating Prompting Patterns in Large Language Models

This report evaluates how the engineering and refinement of prompts affect the performance of AI models. It contrasts unstructured **Naïve Prompts** against structured **Basic Prompts** across four distinct test scenarios, analyzing how constraints alter output quality, accuracy, depth, clarity, and creativity.

---

## 1. Core Definitions of Tested Prompt Patterns

* **Naïve Prompt:** Broad, overly simplified, or ambiguous inputs that provide little to no context, constraints, or stylistic direction. The AI must lean heavily on broad generalizations to fulfill the request.
* **Basic Prompt:** Structured, refined, and objective-oriented inputs. These prompts clearly specify the target task, required output length/format, specific examples to include, and the context or target audience.

---

## 2. Scenario-Based Experimental Output Summary

### Scenario 1 – Creative Story Generation

* **Naïve Prompt:** *"Write a story about space."*
* **Output Summary:** Generated a short, generic narrative with limited world-building, standard sci-fi tropes, and minimal emotional depth.


* **Basic Prompt:** *"Write a 200-word science fiction story about a young astronaut discovering a hidden planet. Include emotions, dialogue, and a surprising ending."*
* **Output Summary:** Generated a tightly paced, highly detailed, and engaging micro-story featuring strong internal narration, realistic dialogue, and a compelling twist ending.



### Scenario 2 – Factual Question Answering

* **Naïve Prompt:** *"Explain AI."*
* **Output Summary:** Returned an over-generalized, high-level technical definition with minimal real-world utility or specific detail.


* **Basic Prompt:** *"Explain Artificial Intelligence in simple terms with examples in healthcare, education, and banking."*
* **Output Summary:** Delivered a highly structured, plain-language explanation mapped directly to the three requested industries, heavily improving clarity through real-life context.



### Scenario 3 – Summarization

* **Naïve Prompt:** *"Summarize machine learning."*
* **Output Summary:** Produced a short, somewhat vague paragraph summarizing the field without highlighting sub-disciplines or practical mechanics.


* **Basic Prompt:** *"Summarize machine learning in 5 points suitable for engineering students."*
* **Output Summary:** Produced an organized, technical yet accessible list of 5 concise, educational pillars tailored specifically to an undergraduate academic level.



### Scenario 4 – Advice and Recommendation

* **Naïve Prompt:** *"How to study better?"*
* **Output Summary:** Returned standard, repetitive self-help advice (e.g., "get enough sleep," "take breaks") lacking actionable execution strategies.


* **Basic Prompt:** *"Suggest a practical study plan for a second-year engineering student preparing for exams with limited time."*
* **Output Summary:** Formulated a realistic, highly structured, time-blocked strategy designed specifically to balance high-density engineering coursework under a strict time crunch.



---

## 3. Comparative Evaluation Metric Table

The table below scores ChatGPT's performance in each category on a scale from **1 (Poor)** to **5 (Excellent)**.

| Scenario | Prompt Type | Quality (1-5) | Accuracy (1-5) | Depth (1-5) | Clarity (1-5) | Creativity (1-5) | Overall Score (out of 25) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| **Creative Story Gen.** | Naïve Prompt | 2 | 2 | 2 | 2 | 2 | **10** |
|  | Basic Prompt | 5 | 5 | 5 | 5 | 5 | **25** |
| **Factual Q&A** | Naïve Prompt | 3 | 3 | 2 | 3 | 3 | **14** |
|  | Basic Prompt | 5 | 5 | 4 | 5 | 4 | **23** |
| **Summarization** | Naïve Prompt | 2 | 2 | 2 | 2 | 2 | **10** |
|  | Basic Prompt | 5 | 4 | 4 | 5 | 4 | **22** |
| **Advice & Recs** | Naïve Prompt | 2 | 2 | 2 | 2 | 2 | **10** |
|  | Basic Prompt | 5 | 4 | 4 | 5 | 4 | **22** |

### Overall Score Comparison Chart

```
Naïve Prompt Total Score: ██████████████ 44/100
Basic Prompt Total Score: ██████████████████████████████████████████████████ 92/100

```

---

## 4. Key Findings and Insights

### Impact of Prompt Clarity on AI Output

* **The Structuring Premium:** Basic prompts consistently outclassed naïve prompts across all performance vectors. Setting strict constraints directly reduces conversational fluff and forces the AI to output high-density information.
* **Vector Improvement Breakdown:**
* **Quality & Clarity:** Drastically elevated by specifying formats (e.g., 5 bullet points, 200 words).
* **Accuracy & Depth:** Enhanced by grounding the prompt with target personas (e.g., engineering students, specific industry use cases) which narrows down the AI's search space.
* **Creativity:** Paradoxically, constraints *boosted* creativity. Limiting the scope to a "young astronaut discovering a hidden planet with a twist ending" forced more unique narrative choices than the wide-open "space" prompt.


* **The Limitation of Naïve Prompts:** Naïve prompts are suitable only for rapid, low-stakes brainstorming or shallow overviews. They fail when actionable, specialized, or formatted output is required.
* **Optimal Blueprinting:** Injecting target audience context, structural instructions, and real-world examples acts as an architectural guide, consistently unlocking the highest performance tiers of the AI model.

## PDF:
[Prompt 5.pdf](https://github.com/user-attachments/files/27954042/Prompt.5.pdf)

# RESULT: 
The prompt for the above said problem executed successfully
