# Coursera-Prompt-Engineering-for-ChatGPT-Vanderbilt-University
Coursera Prompt Engineering for ChatGPT Vanderbilt University

# Module 1 : Course Introduction
## 1.1 Course Overview
### 1.1.V1 Motivating Example: Building a Meal Plan with a Fusion of Food from Ethiopia and Uzbekistan that is Keto
The speaker emphasizes that **large language models (LLMs) like ChatGPT are tools for ideation and iteration**, not just for answering questions or writing essays. They enable **rapid prototyping and refinement** of ideas that would otherwise be difficult or costly to execute.

#### **Example: Meal Plan Exploration**
- The speaker wanted to create a **keto-friendly meal plan** fusing **Uzbek and Ethiopian cuisine** with ingredients from an average US grocery store.
- ChatGPT generated a **structured meal plan** with detailed dishes and ingredient accessibility.
- It **suggested serving sizes** within a **2000-calorie limit**, refining the idea further.

#### **Making It Engaging for a Child**
- The speaker needed to **interest his nine-year-old son**, who is hesitant to try new foods.
- Asked ChatGPT to generate **Pokemon-themed battle stories** for each dish with **cliffhangers** to engage his son.
- The AI produced a **thematic story** that connected the meal with an adventure.

#### **Enhancing Learning with Games**
- At dinner, the family discusses **school topics**, especially **math games**.
- The speaker requested ChatGPT to create a **math game using Pokemon and nutrition concepts**.
- ChatGPT **posed interactive fraction-based math questions**, making the learning process fun.

#### **Turning the Idea into Software**
- Wanting to make the game **more tangible**, the speaker asked ChatGPT to generate **Python code for a web application**.
- ChatGPT produced a **working software prototype**, integrating the math game.

#### **Key Takeaways**
- **LLMs facilitate rapid ideation and refinement**, turning abstract ideas into tangible outcomes.
- **Iteration is key**—each step builds on the previous one, improving functionality.
- **Beyond text generation**, AI can help in planning, storytelling, interactive learning, and even software development.
- **The goal is not just a one-off answer but an evolving process**, where ideas take shape in various forms.

The speaker encourages **thinking of AI as a co-creator**, leveraging its capabilities for creative and complex problem-solving.

### 1.1.V2 Overview of the Course
#### **Introduction**
- **Instructor:** Jules White, Associate Professor of Computer Science at Vanderbilt University.
- **Course Focus:** **Prompt Engineering**—how to effectively interact with large language models (LLMs) like ChatGPT.
- **Goal:** Inspire students to **explore LLMs beyond common misconceptions** (e.g., cheating, plagiarism) and see them as tools to **unlock creativity** and **enhance problem-solving**.

#### **What are Large Language Models?**
- ChatGPT is a **LLM** that can be used for:
  - **Knowledge exploration**
  - **Prototyping**
  - **Content production**
  - **Assessment**
- These models **amplify human capability**, allowing faster execution of creative and technical tasks.

#### **Who Can Take This Course?**
- **No programming experience required.**
- Basic computer skills (file management, using ChatGPT) are helpful.
- Strong **writing skills** and **creative thinking** improve prompt effectiveness.
- **Openness to experimentation** is essential, as best practices are still evolving.

#### **Why Creativity Matters**
- The effectiveness of LLMs depends on the **creativity of the user**.
- **Prompt design** plays a crucial role in getting high-quality outputs.
- Users must be **willing to iterate, experiment, and refine prompts** for optimal results.

#### **Key Concepts Covered in the Course**
1. **Understanding Prompts** – Writing effective inputs to program LLMs for high-quality responses.
2. **Prompt Techniques** – Using patterns like persona-based prompts, question refinement, and cognitive verification.
3. **Prompt Optimization** – Refining prompts through rewriting, combining, splitting, and expanding.
4. **Practical Applications** – Applying LLMs to areas like research, ideation, content creation, and problem-solving.
5. **Few-shot Learning** – Teaching LLMs new tasks using example-driven prompts.

#### **Encouragement to Explore**
- **LLMs are tools for accelerating creativity**—users should leverage them to **bring ideas to life** faster.
- **Iterate and refine ideas continuously** to discover new possibilities.
- The course encourages **hands-on experimentation** with LLMs to unlock their full potential.

#### **Conclusion**
- **Main Theme:** Use LLMs as a tool to **realize and refine ideas**, rather than just answering questions.
- **Objective:** Equip learners with skills to **craft prompts strategically** and maximize AI’s creative potential.
- **Final Message:** Explore, experiment, and use LLMs as a **partner in creativity and problem-solving**.

### 1.1.V3 Motivating Example: Act as a Speech Pathologist
#### **Introduction to the Persona Pattern**  
- **Prompt engineering unlocks advanced capabilities** of ChatGPT and other LLMs.  
- The **Persona Pattern** is a structured way to **ask AI to act as an expert** (e.g., a speech pathologist, doctor, or even an object).  
- This technique **enables AI to generate expert-like insights**, even in fields where the user has no expertise.  

#### **Example: AI as a Speech-Language Pathologist**  
- The speaker used **ChatGPT to assess a child's speech** with the prompt:  
  _"Act as a speech-language pathologist. I will provide a speech sample from a three-year-old, and you will write an assessment."_  
- The **speech sample** provided was: _“I meed way woy.”_  
- ChatGPT generated a **structured report**, identifying:  
  - **Phonological and articulation errors**  
  - **Consonant sound issues** (e.g., difficulty pronouncing "n" and "l")  
  - **Syllable structure problems** (e.g., "way" instead of "play" due to cluster reduction)  

#### **Key Observations**  
- The **AI inferred the intended words** based on phonetic patterns.  
- It provided **terminology and analysis** (e.g., "cluster reduction"), which the user wouldn’t have known to ask for.  
- It **included a disclaimer** noting that **speech development varies in children**, reinforcing responsible AI use.  

#### **Real-World Impact and AI’s Role**  
- The speaker’s **wife, a real speech pathologist,** found the AI’s report detailed but **potentially excessive for a real-world case**.  
- AI is **not replacing professionals** but can **assist in routine tasks**, such as drafting reports, allowing experts to focus on direct patient interaction.  

#### **Conclusion**  
- **Well-structured prompts unlock deep AI capabilities** that users may not realize exist.  
- The **Persona Pattern helps users access domain-specific knowledge** without being experts themselves.  
- **AI is a tool for efficiency, not replacement**, freeing up professionals for higher-value tasks.  
- **With the right prompt structures, AI can bring ideas to life and enhance problem-solving.**

### 1.1.R1 Setting Up an Account and Using ChatGPT

## 1.2 Large Language Models Basics
### 1.2.V1 What are Large Language Models?

#### **What Are Large Language Models (LLMs)?**  
- **LLMs generate text by predicting the next word** based on the input prompt.  
- They **continue generating words** until they determine the response is complete.  
- Responses are built **word by word** using learned language patterns.  

#### **How Do They Work?**  
- Trained on **large datasets from the internet**, learning from text across different domains.  
- Given **partial sentences**, the model **predicts the next word** and refines its response iteratively.  
- Example:  
  - Prompt: _"Mary had a little..."_ → Model predicts **"lamb"** based on learned patterns.  
  - Prompt: _"Roses are red..."_ → Model completes with **"Violets are blue..."**  
- **Context-awareness** is key—models use previous words to make more accurate predictions.  

#### **Rapid Evolution of LLMs**  
- Many models exist beyond ChatGPT: **GPT-4, LLaMa, Alpaca, and others**.  
- The field of **prompt engineering is evolving**, meaning best practices will change over time.  
- **Users should experiment** to adapt to new models and capabilities.  

#### **Key Characteristics of LLMs**  
1. **Outputs May Vary** –  
   - Not always deterministic; the same prompt may yield **different responses**.  
   - Adds **randomness** to improve diversity in text generation.  
2. **Training Data Cutoff** –  
   - Knowledge is limited to when the model was last trained (**e.g., ChatGPT’s knowledge stops at 2021**).  
   - **To include new information**, users must **provide it in the prompt**.  
3. **Not Always Perfect** –  
   - First responses may **contain errors or require refinement**.  
   - Users should iterate and **fine-tune prompts** for better outputs.  

#### **Takeaways for Effective Prompting**  
- **Think of LLMs as tools, not static knowledge bases.**  
- **Design prompts carefully** to leverage their ability to predict and refine responses.  
- **Experimentation and creativity** are key to unlocking their full potential.  
- **Be aware of their limitations** (e.g., outdated knowledge, non-deterministic responses).  

This foundational knowledge will help in writing **better prompts** throughout the course.

### 1.2.V2 Randomness in Output
#### **LLMs Are Not Always Exact or Repeatable**  
- **Large Language Models (LLMs) have inherent randomness**—they won’t always generate the same response for the same input.  
- This **variability is intentional** and can be beneficial in **creative tasks** (e.g., storytelling) but **problematic for precise reasoning** (e.g., Yes/No answers).  
- **Prompt engineering helps control unpredictability**, but **no method guarantees perfect consistency** every time.  

#### **Demonstration of Randomness**  
- The speaker asked **ChatGPT**: _"How many birds are outside my house?"_  
- Each response varied slightly:  
  - **Response 1:** AI explains it **can't perceive the world** and suggests observing outside or setting up a bird feeder.  
  - **Response 2:** AI again states **it has no access to real-world data** but suggests setting up a **camera** instead.  
  - **Response 3:** AI offers similar reasoning but **doesn’t mention cameras**, instead suggesting **bird baths**.  
- **Key takeaway:** Even with a constrained question, **answers are not identical** but follow a similar structure.  

#### **Why This Matters in Prompt Engineering**  
- **LLMs generate variations based on probability**, selecting words that fit the context but aren’t fixed.  
- **This variability must be accounted for** when designing prompts for reliable outputs.  
- **If precision is needed**, users may need to **structure prompts more explicitly** or provide additional context.  

#### **Conclusion**  
- **Expect variation in responses**—LLMs are **not deterministic** like traditional computer programs.  
- **Prompt engineering techniques help reduce randomness**, but some degree of variability is inevitable.  
- **Understanding this behavior is crucial** for crafting effective prompts, especially when seeking **consistent** or **highly structured outputs**.

### Assignment 1 Creating Your First Prompts
#### How exactly can I make the response deterministic ?

To make my responses **deterministic**, you need to control certain parameters in the underlying **language model settings**. Here’s how you can achieve that:

---

##### **1. Use Greedy Decoding (Deterministic)**
By setting **greedy decoding**, the model **always** picks the highest-probability word at each step, leading to **fixed and repeatable outputs**.

##### How to Enable:
- Set **temperature = 0** (removes randomness).
- Disable **top-k sampling** (ensures only the most probable token is selected).
- Disable **top-p (nucleus) sampling**.

✅ **Example Implementation (Python with OpenAI API)**:
```python
import openai

response = openai.ChatCompletion.create(
    model="gpt-4",
    messages=[{"role": "user", "content": "Explain how transformers work."}],
    temperature=0,   # Eliminates randomness
    top_p=1,         # Keeps the highest probability word
    frequency_penalty=0,
    presence_penalty=0
)

print(response["choices"][0]["message"]["content"])
```
📌 **Effect**: The same prompt will **always** yield the same response.

---

##### **2. Use a Fixed Random Seed (Reproducibility)**
If you **must** allow some level of randomness but want reproducibility, setting a **fixed seed** ensures you get the same output across runs.

##### How to Enable:
- Some models (like OpenAI’s API) do **not** expose a random seed setting, but when running a model locally (e.g., `transformers` in PyTorch), you can fix the seed.

✅ **Example (Hugging Face Transformers with PyTorch)**:
```python
import torch
import random
import numpy as np
from transformers import GPT2LMHeadModel, GPT2Tokenizer

# Set deterministic seed
torch.manual_seed(42)
random.seed(42)
np.random.seed(42)

# Load model and tokenizer
model_name = "gpt2"
tokenizer = GPT2Tokenizer.from_pretrained(model_name)
model = GPT2LMHeadModel.from_pretrained(model_name)

# Generate deterministic output
input_text = "Explain how transformers work."
input_ids = tokenizer.encode(input_text, return_tensors="pt")
output = model.generate(input_ids, max_length=100, do_sample=False)  # Greedy decoding

print(tokenizer.decode(output[0], skip_special_tokens=True))
```
📌 **Effect**: The same **seed + settings** will always give the same output.

---

##### **3. Disable Context Variability**
Some models adjust responses based on previous chat history. To make outputs fully deterministic:
- Send **only the latest prompt** (avoid full conversation history).
- Reset state/context after each query.

✅ **Example**:
Instead of:
```python
messages = [
    {"role": "system", "content": "You are an AI assistant."},
    {"role": "user", "content": "Explain transformers."}
]
```
Use:
```python
messages = [{"role": "user", "content": "Explain transformers."}]
```
📌 **Effect**: No dependency on past messages, ensuring identical outputs.

---

##### **Conclusion**
If you want **strict determinism**, do the following:
1. **Set `temperature=0`, disable top-k and top-p sampling** (greedy decoding).
2. **Use a fixed random seed** (for local models).
3. **Avoid context history variability** (send only the latest prompt).

Would you like a setup guide for a specific use case (e.g., OpenAI API, local LLM, or another framework)?


# Module 2 - Introduction to Prompts
## Course 1 - What are Prompts?
### V: What is a Prompt?
### V: Intuition Behind Prompts
### V: Everyone Can Program with Prompts

## Course 2 - Intro to Prompt Patterns?
### V: Prompt Patterns
### V: The Persona Pattern
### R: Reading a Prompt Pattern
### R: Format of the Persona Pattern
### R: Learn More About Prompt Patterns
### Graded Assignment: Applying the Persona Pattern
### R: Staying Connected & Learning More

## Course 3 - Prompts, Conversations and New Information?
### V: Introducing New Information to the Large Language Model
### V: Prompt Size Limitations
### V: Prompts are a Tool for Repeated Use
### V: Root Prompts
### Graded Assignment: Creating Prompts with New Information
### R: What to Take After or With this Course
# Module 3
# Module 4
# Module 5
# Module 6