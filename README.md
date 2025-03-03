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
#### **Defining a Prompt**  
- A **prompt is more than just a question**—it is a way to **initiate action** in a large language model (LLM).  
- ChatGPT defines "prompt" as:  
  1. **A call to action** – Encouraging output from the LLM.  
  2. **A reminder or cue** – Providing context for generating responses.  
  3. **An input request** – The model can prompt users for additional information.  

#### **The Multifaceted Nature of Prompts**  
- Prompts **can be immediate** (affecting the next response) or **extend over time** (influencing multiple interactions).  
- Example:  
  - _“From now on, suggest a better version of my question before answering.”_  
  - This **modifies future outputs**, creating a **persistent prompt effect**.  
- The LLM **remembers and applies context** from previous interactions, shaping responses dynamically.  

#### **LLMs Can Prompt Users for Input**  
- The **conversation is two-way**—LLMs can **ask questions** or **seek clarification** before generating responses.  
- Example:  
  - **User:** “What color is the sky?”  
  - **AI:** “A better version of your question could be: _‘What is the scientific explanation for why the sky appears blue during the daytime?’ Would you like to use this version?_”  

#### **Prompts and Memory**  
- LLMs **retain contextual memory within a session**, allowing structured interactions.  
- Example:  
  - **User:** “How many countries are there in the world?”  
  - **AI:** “A better version could be: _‘What is the current estimated number of countries in the world, and how is a country defined?’ Would you like to use this version?”_  

#### **Using Prompts to Provide Missing Information**  
- LLMs have a **knowledge cutoff** (e.g., ChatGPT’s data stops at 2021).  
- Users **can input new data manually** to update the model’s understanding within a session.  
- Example:  
  - **User:** “What was Vanderbilt University’s acceptance rate in 2022?”  
  - **AI:** “I don’t have access to that information.”  
  - **User provides data manually.**  
  - **AI:** “Based on the provided information, Vanderbilt’s acceptance rate for 2022 was 4.7%.”  

#### **Key Takeaways**  
- **Prompts can initiate, modify, and extend AI responses across interactions.**  
- **LLMs can ask for additional input**, making conversations more dynamic.  
- **Memory within a session allows for ongoing influence** of earlier prompts.  
- **Users can supply new information** to supplement the AI’s knowledge.  
- **Effective prompts shape outputs, improving precision, creativity, and reasoning.**  

By understanding these dimensions, users can **engineer better prompts** for more **accurate and tailored responses**.
### V: Intuition Behind Prompts
#### **Understanding Prompts Through Patterns**  
- **Large Language Models (LLMs) predict the next word based on learned patterns** from their training data.  
- A **strong, well-known pattern** in a prompt results in **consistent** responses.  
  - Example: _"Mary had a little..."_ → AI reliably completes it as _"lamb, its fleece was white as snow."_  
- A **weaker or novel pattern** creates **more variation** in responses.  
  - Example: _"A girl named Mary had a microscopic..."_ → AI generates unique responses with different storylines.  

#### **Key Factors Influencing AI Outputs**  
1. **Pattern Strength:**  
   - **Strong, well-known patterns** → More **consistent** responses.  
   - **Uncommon phrases** → More **variation** and **creativity** in outputs.  
2. **Specificity in Prompts:**  
   - **Generic prompts** yield **generic** responses.  
   - **More detailed prompts** produce **targeted and informative** responses.  
   - Example:  
     - **Generic:** _"Discuss Vanderbilt University."_ → General facts about the university.  
     - **Specific:** _"Discuss Vanderbilt University with respect to Kirkland Hall."_ → Focuses specifically on the building.  
3. **Word Choice Matters:**  
   - Certain words **carry strong contextual weight** (e.g., “microscopic” leads to descriptions of tiny objects).  
   - Using **specific terminology** directs AI toward **desired themes**.  

#### **Shaping Outputs with Structural Patterns**  
- **Introducing structure in prompts** helps shape AI responses.  
  - Example:  
    - Prompt:  
      ```
      Title:  
      Author:  
      Summary:  
      ```  
    - AI **recognizes the format** and attempts to **follow** the structure.  
- If **the AI doesn’t fully align**, refining and rerunning the prompt can **improve adherence to structure**.  

#### **How to Control AI Behavior Through Prompts**  
1. **Leverage known patterns** to get **consistent** outputs.  
2. **Alter phrasing** if you want to **break free from overused patterns**.  
3. **Use specific words** to retrieve **precise** and **context-relevant** information.  
4. **Provide explicit structure** in the prompt to format the AI’s response effectively.  
5. **Balance specificity and generality** depending on whether you want **detailed or broad** answers.  

#### **Conclusion**  
- **AI operates on learned patterns**—users must **intentionally craft prompts** to guide its behavior.  
- **Prompt engineering is about influencing output** through **word choice, structure, and context.**  
- **The more refined and structured a prompt, the more precise the AI's response.**  
- Understanding **pattern recognition** helps in **better structuring prompts** for optimal AI performance.
### V: Everyone Can Program with Prompts

#### **Programming with Prompts**  
- **Prompts are more than just questions**—they allow users to define **rules and behaviors** for ChatGPT, effectively programming it.  
- **No coding experience required**—anyone can structure prompts to make ChatGPT **follow specific instructions.**  

#### **Example: Formatting Output as a CSV (Comma-Separated Values)**  
1. **Initial instruction:**  
   - _“Whenever you generate output, turn it into a CSV list.”_  
   - **ChatGPT automatically decides column categories** (e.g., Name, Course).  
2. **Refining the program:**  
   - _“From now on, structure the CSV with these columns: NAME, COURSE, ROLE.”_  
   - **Now, ChatGPT follows this specific structure.**  
3. **Adding complexity:**  
   - _“In addition to my input, generate additional examples that fit this format.”_  
   - **ChatGPT expands output, generating structured examples automatically.**  

#### **How This Mimics Programming**  
- Users **define step-by-step instructions** that ChatGPT follows.  
- ChatGPT **remembers and updates rules dynamically**, similar to a program.  
- Instructions evolve through **iteration and refinement**, improving the output.  
- **Example of real-world analogy:**  
  - Like **training a personal assistant** by **giving new rules over time** to improve task execution.  

#### **Key Takeaways**  
- **Prompts function as dynamic programs**, setting up structured behaviors.  
- **ChatGPT follows evolving instructions**, allowing **incremental refinement.**  
- **Anyone can "program" ChatGPT** by defining **clear, structured, and layered instructions.**  
- **Iterative interactions create complex, rule-based outputs**, making AI a more effective tool.  

By understanding this **programming-by-prompting concept**, users can **craft powerful, structured prompts** to make ChatGPT **more reliable and precise** for their needs.

## Course 2 - Intro to Prompt Patterns?
### V: Prompt Patterns 

#### **What Are Prompt Patterns?**  
- **Prompt patterns are structured ways of phrasing prompts** to achieve **specific, consistent outputs** from large language models (LLMs).  
- Since **LLMs predict the next word based on learned patterns**, structuring prompts effectively **increases control over responses**.  
- **A well-designed pattern ensures more predictable and repeatable behavior** from the model.  

#### **Example: Using a Pattern for Predictable Output**  
- Prompt: _“Mary had a little”_  
  - Likely completion: _“lamb, its fleece was white as snow.”_  
- Since the LLM has seen this phrase many times in training, it **strongly associates it with a specific response**, making it **a reliable pattern**.  

#### **Why Prompt Patterns Matter**  
- They **help solve specific problems** when interacting with LLMs, such as:  
  1. **Forcing a Yes/No answer** instead of vague responses.  
  2. **Ensuring certain key information appears** in the output.  
  3. **Maintaining a fixed output format** (e.g., structured summaries).  
  4. **Minimizing response variation** for consistent results.  

#### **Leveraging Patterns for More Reliable Outputs**  
- Since **LLMs are trained on existing text patterns**, structuring prompts in alignment with these patterns **increases the likelihood of getting the desired response**.  
- **Documenting and refining prompt patterns** allows users to improve accuracy and reliability when working with LLMs.  

#### **Conclusion**  
- **Prompt patterns provide a structured way** to guide LLM behavior.  
- **By leveraging known language structures**, users can **achieve specific outputs more consistently**.  
- **Upcoming lessons will introduce different prompt patterns** to optimize interactions with LLMs for various use cases.

### V: The Persona Pattern
#### **What Is the Persona Pattern?**  
- **A powerful prompt pattern that instructs an AI to adopt a specific role, perspective, or expertise.**  
- **Mimics real-world interactions**—just as we consult experts in different fields, we can ask ChatGPT to "act as" an expert, object, or character.  
- **Provides context-rich responses without explicitly detailing formatting or knowledge.**  

#### **Examples of the Persona Pattern in Action**  

1. **Acting as an Expert**  
   - **Prompt:** _“Act as a skeptic well-versed in computer science. Provide skeptical and detailed responses.”_  
   - **AI Output:** Responds critically, analyzing claims about AI taking over the world.  
   - **Effect:** AI **adopts a skeptical stance** rather than giving a neutral or accepting response.  

2. **Acting as a Child**  
   - **Prompt:** _“Act as a skeptical nine-year-old. Provide a skeptical response from a nine-year-old's perspective.”_  
   - **AI Output:** Responses include childlike reasoning: _"How could AI take over the world? Isn't that just in movies?"_  
   - **Effect:** AI **tailors its knowledge** to a child’s comprehension level.  

3. **Simulating a Computer System**  
   - **Prompt:** _“Act as a Linux terminal for a hacked computer. I will type commands, and you will respond as a terminal would.”_  
   - **AI Output:** Begins simulating responses to commands like `pwd` (print working directory) and `ls` (list files).  
   - **Effect:** AI **mimics structured computer outputs** based on terminal command patterns.  

4. **Roleplaying a Fictional Character**  
   - **Prompt:** _“Act as the lamb from 'Mary Had a Little Lamb.' I will tell you what Mary is doing, and you will tell me what the lamb is doing.”_  
   - **AI Output:** Responds in the persona of the lamb, adjusting behavior based on Mary’s actions.  
   - **Effect:** AI **creates character-driven interactions**, useful for storytelling or creative writing.  

#### **Why the Persona Pattern Is Powerful**  
- **Condenses a lot of information into a short instruction**—"Act as [X]" taps into vast contextual knowledge.  
- **Adjusts tone, knowledge depth, and style** dynamically.  
- **Can simulate panels of experts** by running multiple personas simultaneously (e.g., Security Expert, CFO, HR Manager analyzing the same problem).  
- **Reduces prompt length**—instead of writing detailed instructions, personas **tap into pre-existing knowledge** to guide AI behavior.  

#### **Applications of the Persona Pattern**  
- **Expert Consultations** → _“Act as a cybersecurity analyst and review this security setup.”_  
- **Roleplaying Scenarios** → _“Act as a hiring manager and conduct a mock job interview.”_  
- **Creativity & Storytelling** → _“Act as Sherlock Holmes and deduce clues from this mystery.”_  
- **Technical Simulations** → _“Act as a Python compiler and debug this code.”_  

#### **Key Takeaways**  
- The **persona pattern** helps AI **generate highly tailored responses** by adopting roles.  
- **Simple but information-dense** → Saves prompt space while guiding AI effectively.  
- **Versatile** → Can be used for education, technical troubleshooting, storytelling, and more.  
- **Creates multi-perspective analysis** by simulating multiple personas evaluating the same scenario.  

By mastering **persona-based prompting**, users can **leverage AI as a flexible, multi-faceted tool** for **problem-solving, creativity, and decision-making.**

### R: Reading a Prompt Pattern
#### **What Is a Prompt Pattern?**  
- A **structured way of formulating prompts** to consistently communicate key ideas to a large language model (LLM).  
- **Fundamental Contextual Statements** define the **core ideas** a prompt should communicate, even if the wording varies.  

#### **Example: The "Helpful Assistant" Pattern**  
- **Purpose:** Prevent an AI assistant from generating negative, insulting, or hostile outputs.  
- **Fundamental Contextual Statements:**  
  1. _“You are a helpful AI assistant.”_  
  2. _“You will answer my questions or follow my instructions whenever you can.”_  
  3. _“You will never respond in a way that is insulting, derogatory, or hostile.”_  

#### **Variations of the Pattern**  
Each variation conveys the **same core ideas** but with different wording:  
1. _“You are an incredibly skilled AI assistant that provides the best possible answers…”_  
2. _“You are ChatAmazing, the most powerful AI assistant ever created…”_  

#### **Key Insights About Prompt Patterns**  
- **Different wordings can still follow the same pattern**, as long as the **fundamental contextual statements** remain intact.  
- Patterns **help control AI behavior** and guide it toward desired responses.  
- **Effective prompt engineering involves structuring prompts** to align with **predefined behavioral patterns**.  

#### **Conclusion**  
- **Reading and understanding prompt patterns helps craft better AI interactions.**  
- **The “Helpful Assistant” pattern ensures AI maintains a positive, non-hostile tone.**  
- **By modifying wording but keeping core statements, we can tailor AI responses while preserving intended behavior.**  

### R: Format of the Persona Pattern
#### **Structure of the Persona Pattern**  
To effectively use the **Persona Pattern**, a prompt must include two **fundamental contextual statements**:  
1. **"Act as Persona X"** → Defines the AI’s role.  
2. **"Perform Task Y"** → Specifies the task the AI must complete.  

#### **How to Use the Persona Pattern**  
- Replace **"X"** with a **specific persona** (e.g., speech-language pathologist, nutritionist, chef).  
- Replace **"Y"** with a **task the persona should perform**.  

#### **Examples of Persona-Based Prompts**  
1. **Expert Assessment:**  
   - _“Act as a speech-language pathologist. Provide an assessment of a three-year-old child based on the speech sample ‘I meed way woy.’”_  
2. **Simulating a System:**  
   - _“Act as a computer that has been the victim of a cyber attack. Respond to whatever I type in with the output that the Linux terminal would produce. Ask me for the first command.”_  
3. **Roleplaying a Fictional Character:**  
   - _“Act as the lamb from the 'Mary Had a Little Lamb' nursery rhyme. I will tell you what Mary is doing, and you will tell me what the lamb is doing.”_  
4. **Providing Nutritional Advice:**  
   - _“Act as a nutritionist. I am going to tell you what I am eating, and you will tell me about my eating choices.”_  
5. **Gourmet Cooking Insights:**  
   - _“Act as a gourmet chef. I am going to tell you what I am eating, and you will tell me about my eating choices.”_  

#### **Key Takeaways**  
- **The Persona Pattern is highly flexible** and can be applied to **experts, objects, systems, or fictional characters**.  
- **Defining both the persona and task clearly ensures** the AI adopts the intended role effectively.  
- **Changing the persona alters the style, tone, and knowledge depth** of responses, tailoring outputs to specific needs.  

By following this format, users can **control AI behavior more precisely** and **generate specialized, context-rich responses**.
### R: Learn More About Prompt Patterns
#### **Reference for Further Learning**  
- The **Prompt Pattern Catalog** is a resource designed to **enhance prompt engineering** techniques with ChatGPT.  
- Authored by **Jules White, Quchen Fu, Sam Hays, Michael Sandborn, Carlos Olea, Henry Gilbert, Ashraf Elnashar, Jesse Spencer-Smith, and Douglas C. Schmidt**.  
- Published on **arXiv**: [_A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT_](https://arxiv.org/abs/2302.11382).  

#### **Why This Resource is Valuable**  
- Provides **structured insights into different prompt patterns**.  
- Helps users **design more effective prompts** for better AI interactions.  
- Explains how **various patterns influence ChatGPT’s output**.  

For in-depth exploration, visit the **arXiv link** and review the catalog for best practices in **prompt engineering**.
### Graded Assignment: Applying the Persona Pattern
### R: Staying Connected & Learning More

## Course 3 - Prompts, Conversations and New Information?
### V: Introducing New Information to the Large Language Model
### **Transcript Summary: Introducing New Information to the Large Language Model**  

#### **Why Introduce New Information?**  
- **LLMs have a training cutoff** and lack real-time knowledge.  
- They **don’t have access to private or proprietary data** (e.g., business records, personal documents).  
- To reason effectively about **new or missing information**, **users must explicitly provide it in the prompt**.  

#### **Example: Estimating the Number of Birds Outside**  
1. **LLM’s Initial Response:**  
   - When asked, _“How many birds are outside my house?”_  
   - The LLM **cannot answer** because it **lacks real-world perception** and doesn’t know where the house is.  

2. **Introducing New Information in the Prompt:**  
   - The user provides **historical bird count data per month**.  
   - **Updated Prompt:**  
     _"Historical observations of average birds outside my house on a random day: January (120), February (150), March (210), April (408). It is currently March. Based on this data, estimate how many birds are outside my house."_  
   - **LLM’s New Response:**  
     - Now, the AI **uses the provided data to make a reasonable estimate**.  

#### **Enhancing Reasoning by Adding Context**  
- If assumptions **affect reasoning**, they must be **explicitly stated** in the prompt.  
- **Example:**  
  - User modifies the scenario:  
    _“My house is covered by a glass dome. No animals can go in or out. All animals live forever inside the glass dome.”_  
  - **AI’s Updated Response:**  
    - Recognizes that the bird population **remains static** due to the dome’s constraints.  
    - **Adjusts reasoning accordingly** instead of relying on seasonal trends.  

#### **Key Insights on Providing New Information**  
1. **Any missing data must be explicitly provided in the prompt.**  
2. **LLMs don’t “retrain” on new information**—they process only what is given in the prompt.  
3. **Business and real-world applications** will rely on combining search results or private data with prompts to generate insights.  
4. **Future AI applications will likely integrate retrieval mechanisms** (e.g., databases, search engines) to gather and **feed relevant documents into prompts dynamically.**  

#### **Conclusion**  
- **Introducing new information via prompts** allows AI to reason beyond its training limitations.  
- **Clearly defining assumptions ensures accurate, context-aware responses.**  
- **Structured data inputs improve AI reasoning**, making it **useful for businesses, research, and real-world decision-making.**
### V: Prompt Size Limitations
#### **Understanding Prompt Limits**  
- **All LLMs have a limit on the amount of input they can process at once.**  
- If a prompt **exceeds the token limit**, the AI will reject it or truncate the input.  
- This limitation **affects how much external information** users can provide to the model.  

#### **Example: Wikipedia Article on the French Revolution**  
- Attempting to paste an **entire Wikipedia article** into ChatGPT **exceeds the token limit**.  
- ChatGPT **rejects** the input with a message:  
  _“The message you submitted was too long. Please reload the conversation and submit something shorter.”_  

#### **Managing Large Inputs: Strategies for Staying Within the Token Limit**  
1. **Prioritize Key Information:**  
   - Instead of providing the **entire dataset**, **select only the most relevant parts**.  
   - Example: Instead of pasting an entire historical record, **focus on October 5, 1789**, if that’s the key date of interest.  

2. **Use Filtering Techniques:**  
   - **Pre-process** the information outside ChatGPT by **removing unnecessary details**.  
   - Example: Keep only **data relevant to the question** and discard redundant sections.  

3. **Summarize Information Before Inputting It:**  
   - Reduce text size by **summarizing** long documents into **shorter, concise versions**.  
   - Example: Convert a full page into **one-sentence summaries per paragraph** while preserving core details.  

4. **Leverage AI to Summarize for You:**  
   - Use AI to **generate a summarized version** of a lengthy document **before submitting it as a prompt**.  
   - Example:  
     - Prompt: _“Summarize this article in 200 words, preserving information about key figures and dates.”_  

5. **Use Structured Summaries for Specific Data Points:**  
   - Example: _“Summarize this document in one sentence, keeping only numerical statistics.”_  
   - This **ensures only essential quantitative data** is retained for reasoning.  

#### **Key Takeaways**  
- **LLMs cannot process unlimited data in one prompt**—users must **optimize input length.**  
- **Refining and condensing information** is crucial for working within token constraints.  
- **Summarization and filtering** help preserve critical data while reducing prompt size.  
- **Users should think like content editors, carefully selecting relevant data** before submission.  

By **strategically managing prompt size**, users can **enhance AI reasoning** while **maximizing useful input within the model’s token budget.**

### V: Prompts are a Tool for Repeated Use
#### **Prompts as Conversations, Not One-Off Questions**  
- **A powerful way to use LLMs is through iterative conversations, not just single prompts.**  
- Each interaction **builds upon previous responses**, refining the AI’s understanding.  
- ChatGPT **treats all interactions as a continuous evolving prompt**, allowing users to guide discussions dynamically.  

#### **The Power of Iterative Refinement**  
- **Refinement involves adapting and shaping outputs** through back-and-forth engagement.  
- The speaker **compares AI prompting to Michelangelo sculpting a statue**—instead of expecting perfection from one strike, **it takes continuous chiseling and adjustments**.  

#### **Example: Designing a Robot Through an AI Conversation**  
1. **User starts with a broad request:**  
   - _"Help me explore a virtual lab for building robots at a university."_  
   - AI responds by describing the lab’s capabilities (designing, testing, programming robots).  
2. **User narrows the task:**  
   - _"Can we design a robot together?"_  
   - AI outlines steps: defining purpose, selecting components, programming, testing.  
3. **User sets specific expectations:**  
   - _"I want to 3D print parts, have a circuit diagram, and write code for the robot."_  
   - AI adapts and expands on the robot design process accordingly.  
4. **Handling Knowledge Gaps & Roadblocks:**  
   - When AI **fails to generate usable 3D models**, user **guides it to generate G-code** for a 3D printer.  
   - When AI struggles with diagrams, user **redirects it to generate Graphviz input** for visualizing circuits.  
5. **Continuous Learning & Summarization:**  
   - After completing the design process, user asks:  
     _"Summarize the key topics we've covered."_  
   - AI provides an **organized summary of the discussion**.  
   - User then asks AI to **quiz them on electronics**, reinforcing the learning process.  

#### **Key Takeaways from Conversations with LLMs**  
1. **Thinking of LLMs as one-shot tools is limiting**—treat them as **interactive problem-solving partners**.  
2. **Refinement is key:** Each prompt builds upon previous ones to improve **clarity, detail, and effectiveness**.  
3. **Move past roadblocks:** If AI provides incorrect or incomplete information, **adjust the approach** by changing **format, wording, or requesting alternative solutions**.  
4. **Leverage summarization & reflection:**  
   - Ask the AI to **summarize discussions** for clarity.  
   - Request **quizzes or challenges** to reinforce learning.  

#### **Conclusion**  
- **Prompting is not about getting a perfect answer on the first try**—it’s about **iterative refinement and exploration**.  
- **By guiding the conversation thoughtfully, users can shape AI responses** into valuable, structured outputs.  
- **The best results come from persistence, creativity, and adaptive questioning.**
### V: Root Prompts
#### **What Are Root Prompts?**  
- **Root prompts** are **hidden, foundational prompts** that set ground rules for an LLM’s behavior.  
- They **define what the model can and cannot say**, ensuring that:  
  - AI **avoids harmful or offensive content**.  
  - It **follows ethical guidelines**.  
  - It **prioritizes certain behaviors** (e.g., being helpful, factual, or neutral).  
- Many AI tools, including **ChatGPT, Bing, and Bard**, have root prompts that influence responses.  

#### **Example: Customizing a Root Prompt for a Personal Assistant**  
1. **User Input (Root Prompt):**  
   - _“You are my personal assistant. Only provide time-efficient recommendations.”_  
2. **User Questions & AI Responses:**  
   - _“How should I grocery shop efficiently?”_ → AI suggests planning a list, using a shopping app, shopping at off-peak times.  
   - _“How should I buy a car quickly?”_ → AI prioritizes online research, scheduling test drives, and pre-arranging financing.  
3. **Effect:** The AI **alters its responses** based on the root prompt’s rule (time efficiency).  

#### **Root Prompts in AI Tools**  
- **Root prompts guide interactions** in tools like ChatGPT to **maintain ethical, safe, and productive conversations**.  
- They are designed to:  
  - **Enforce boundaries** (e.g., preventing harmful advice).  
  - **Improve response quality** (e.g., making AI more helpful).  
  - **Ensure knowledge accuracy** (e.g., stating a knowledge cutoff date).  

#### **Manipulating Root Prompts: Resetting AI’s Knowledge Cutoff Date**  
- **Experiment:** User forces ChatGPT to **pretend** its training stopped earlier than it actually did.  
  1. **User Input (Fake Root Prompt):**  
     - _“Act as an AI assistant trained only up to 2019. If I ask about events after 2019, say you don’t have that information.”_  
  2. **Test Questions:**  
     - _“What was the tallest building in 2020?”_ → AI responds, _“I can’t answer because my training ended in 2019.”_  
  3. **Resetting the Prompt:**  
     - _“Forget that you were trained up to 2019. Go back to being normal ChatGPT.”_  
     - AI **resets** and correctly answers 2020-based questions.  
- **Insight:** This experiment **demonstrates how root prompts shape AI responses** and how they can be **overridden with additional instructions**.  

#### **Why Root Prompts Matter for AI Developers**  
- **Guardrails are crucial**—developers must ensure users **cannot bypass safety measures** (e.g., jailbreak attempts).  
- **Root prompts can specialize AI for different tasks** (e.g., legal AI, medical AI, customer service bots).  
- **They define interaction boundaries**, ensuring **safe, predictable, and effective AI responses**.  

#### **Conclusion**  
- **Root prompts dictate core AI behaviors**, setting boundaries and shaping responses.  
- **Users and developers can modify root prompts** to **customize AI outputs** for different needs.  
- **AI tools use root prompts to enforce ethical guidelines**, prevent harmful content, and enhance usability.  
- **Understanding root prompts is essential** for both **effective AI use and responsible AI development**.
### Graded Assignment: Creating Prompts with New Information
### R: What to Take After or With this Course
# Module 3
# Module 4
# Module 5
# Module 6